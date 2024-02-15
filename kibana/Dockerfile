ARG STACK_VERSION
FROM docker.elastic.co/kibana/kibana:${STACK_VERSION}

USER root
COPY append_kibana.yml /append_kibana.yml
RUN cat /append_kibana.yml >> /usr/share/kibana/config/kibana.yml && rm /append_kibana.yml
USER kibana
