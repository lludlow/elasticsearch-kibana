## Elasticsearch and Kibana in one container

Only runs v7.7.0

Simple and lightweight docker image for previewing Elasticsearch and Kibana.

### Usage

    docker run -d -p 9200:9200 -p 5601:5601 nshou/elasticsearch-kibana

You can connect to Elasticsearch through `localhost:9200` and explore Kibana via `localhost:5601`.

### Tags

Tag     | Elasticsearch | Kibana
------- | ------------- | ------
latest  | 7.7.0         | 7.7.0

