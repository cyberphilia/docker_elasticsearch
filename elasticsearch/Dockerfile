ARG STACK_VERSION
FROM docker.elastic.co/elasticsearch/elasticsearch:${STACK_VERSION}

USER root
COPY append_elasticsearch.yml /append_elasticsearch.yml
RUN cat /append_elasticsearch.yml >> /usr/share/elasticsearch/config/elasticsearch.yml && rm /append_elasticsearch.yml
USER elasticsearch