Symfony Docker Stack
==================

Docker compose containers to run a symfony app to local development
DO NOT USE THIS IN PROD

Images
======

- MySQL 5.7
- Nginx (Latest)
- PHP-FPM 7.1
- Redis (alpine)
- Elastic Search 6.1
- Logstash 6.1
- Kibana 6.1

Networks
========

- symfony_docker_stack

Ports
=====

Default ports exposed

Volumes
=======

- db: MySQL DB files
- elastic_search_data: ElasticSearch index data
- Config volumes from *docker* folder