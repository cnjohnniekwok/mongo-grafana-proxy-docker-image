# mongodb-grafana-proxy-docker-image ([Docker Hub](https://hub.docker.com/repository/docker/cnjohnniekwok/mongodb-grafana-proxy-docker-image))
Mongo proxy for grafana MongoDB datasource. This is a docker image for stand alone mongo proxy server that runs along with mongods-grafana-docker-image ([DockerHub](https://hub.docker.com/repository/docker/cnjohnniekwok/mongodb-grafana-docker-image) | [GitHub](https://github.com/cnjohnniekwok/mongodb-grafana-docker-image)).

This mongo-grafna_proxy is mondified to allow multiple database access from using a single MongoDB data source.


Database query syntax:
```
db.<database>.<collection>.aggregate({})
```
