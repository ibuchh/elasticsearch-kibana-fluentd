# Introduction
Elasticsearch is a search engine that is responsible for storing our logs and allowing for them to be queried. Fluentd sends log messages from Kubernetes to Elasticsearch, whereas Kibana is a graphical interface for viewing and querying the logs stored in Elasticsearch.
## Elasticsearch
Elasticsearch is deployed as a StatefulSet, which is like a Deployment, but allows for maintaining state on storage volumes.
