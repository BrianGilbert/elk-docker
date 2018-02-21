# Elasticsearch, Logstash, Kibana (ELK) Docker image

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

### Documentation

### Docker Hub

This image is hosted on Docker Hub at [https://hub.docker.com/r/growen/elk/](https://hub.docker.com/r/growen/elk/).

The following tags are available:

- `latest`
### About

Forked from https://github.com/spujadas/elk-docker: the work of [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

Changes include removal of SSL certs (added as a volume when used in conjunction with [docker compose letsencrypt nginx proxy companion](https://github.com/GROwen/docker-compose-letsencrypt-nginx-proxy-companion)

