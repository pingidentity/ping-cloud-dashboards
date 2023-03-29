# Changelog

### 1.18.0.0

- Replaced "grafana-kubernetes-app" plugin functionality with a few Kubernetes infrastructure monitoring dashboards
- Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- Refactor 'Kibana PA Dashboard' queries to exclude healcheckconnection information from them
- Add Logstash dashboard

_Changes_

- [X] PDO-4722 Grafana: replacement of "grafana-kubernetes-app" plugin
- [X] PDO-4952 Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- [X] PDO-5142 Add logstash metrics to prometheus
- [X] PDO-5163 Refactor 'Kibana PA Dashboard' queries to exclude healcheckconnection information from them

### 1.17.0.0

- Create new global repo for dashboards
- Grafana: Modify dashboards to Show Second Region Metrics
- Modify Kibana dashboards to show second region logs

_Changes:_

- [X] PDO-4496 Create new global repo for dashboards
- [X] PDO-4567 Grafana: Modify dashboards to Show Second Region Metrics
- [X] PDO-4568 Kibana: Modify Dashboards to Show Second Region Logs and Metrics

