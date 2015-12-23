# Elasticsearch Docker Image
build from [official image](https://github.com/docker-library/elasticsearch)

## Features
A few plugins are installed:

- [analysis-kuromoji](https://github.com/elastic/elasticsearch-analysis-kuromoji)
- [analysis-icu](https://github.com/elastic/elasticsearch-analysis-icu)

and `script.engine.groovy.inline.search` is `on`


## Usage
```
docker run -d heathrow/elasticsearch:latest
```

[https://github.com/docker-library/elasticsearch](https://github.com/docker-library/elasticsearch)
