FROM elasticsearch:1.7

RUN plugin install mobz/elasticsearch-head
RUN plugin install elasticsearch/elasticsearch-analysis-kuromoji/2.7.0
RUN plugin install elasticsearch/elasticsearch-analysis-icu/2.7.0

COPY ./elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
