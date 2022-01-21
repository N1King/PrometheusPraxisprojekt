FROM prom/prometheus:latest

COPY config /etc/prometheus/

CMD        [ "--config.file=/etc/prometheus/prometheus.yml", \
             "--storage.tsdb.path=/prometheus" ]
