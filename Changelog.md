# Changelog

### 1.18.0.0

- Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- Refactor 'Kibana PA Dashboard' queries to exclude healcheckconnection information from them
- PA dashboard migrated from Elasticsearch to Opensearch
- OpenSearch migration: Migrate PF dashboards
- OpenSearch migration: Migrate PA-WAS dashboard
- Add Logstash dashboard
- Fix: Splitted Grafana dashboards into different CMs to avoid length limit issue
- Fix: No data on the Kubernetes Cluster Monitoring dashboard
- Fix: P1AS Ingress Dashboard

_Changes_

- [X] PDO-4722 Grafana: replacement of "grafana-kubernetes-app" plugin
- [X] PDO-4952 Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- [X] PDO-5114 OpenSearch migration: Migrate PA dashboard
- [X] PDO-5116 OpenSearch migration: Migrate PF dashboards
- [X] PDO-5117 OpenSearch migration: Migrate PA-WAS dashboard
- [X] PDO-5142 Add logstash metrics to prometheus
- [X] PDO-5163 Refactor 'Kibana PA Dashboard' queries to exclude healcheckconnection information from them
- [X] PDO-5437 Pods CPU usage/memory usage/network I/O graphs have No data on the Kubernetes Cluster Monitoring dashboard
- [X] PDO-6231 Fix P1AS Ingress Dashboard

### 1.17.0.0

- Create new global repo for dashboards
- Grafana: Modify dashboards to Show Second Region Metrics
- Modify Kibana dashboards to show second region logs

_Changes:_

- [X] PDO-4496 Create new global repo for dashboards
- [X] PDO-4567 Grafana: Modify dashboards to Show Second Region Metrics
- [X] PDO-4568 Kibana: Modify Dashboards to Show Second Region Logs and Metrics

