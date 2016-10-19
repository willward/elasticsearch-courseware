# Setup and Configuration #

* Kibana is an open source installed separately from Elastic Search
* Can be downloaded from <a href="https://www.elastic.co/downloads/kibana" target="_blank">Elastic.co</a> or install using <a href="https://www.elastic.co/guide/en/kibana/4.6/setup.html#setup-repositories" target="_blank">Linux Repositories</a>
* Configuration file: ./kibana.yml
* Important settings:
```
server.port: 5601
server.host: "0.0.0.0"
elasticsearch.url: "http://localhost:9200"
```
* Additional settings detailed <a href="https://www.elastic.co/guide/en/kibana/current/kibana-server-properties.html" target="_blank">here</a>
* Kibana can be installed on the same nodes where Elastic Search is running, or on separate nodes