FROM grafana/grafana:latest

COPY datasources /etc/grafana/provisioning/datasources/
COPY dashboards.yml /etc/grafana/provisioning/dashboards/
COPY dashboards /etc/grafana/dashboards/

ENV GF_PATHS_PROVISIONING=/etc/grafana/provisioning/
