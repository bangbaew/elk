FROM docker.elastic.co/logstash/logstash:8.6.1
COPY pipeline.conf /dir
ENTRYPOINT logstash -f /dir/pipeline.conf