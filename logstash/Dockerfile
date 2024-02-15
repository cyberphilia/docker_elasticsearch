ARG STACK_VERSION
FROM docker.elastic.co/logstash/logstash:${STACK_VERSION}

USER root
RUN rm -f /usr/share/logstash/config/certs
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
RUN rm -f /usr/share/logstash/config/logstash.yml
# USER logstash
