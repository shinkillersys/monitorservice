FROM docker.elastic.co/logstash/logstash:7.11.1

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
COPY pipeline /usr/share/logstash/pipeline/
COPY config /usr/share/logstash/config/