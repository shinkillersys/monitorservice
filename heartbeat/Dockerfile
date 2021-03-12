FROM docker.elastic.co/beats/heartbeat:7.11.1
COPY config/heartbeat.yml /usr/share/heartbeat/heartbeat.yml
USER root
RUN chmod go-w /usr/share/heartbeat/heartbeat.yml
RUN chown root:heartbeat /usr/share/heartbeat/heartbeat.yml
USER heartbeat