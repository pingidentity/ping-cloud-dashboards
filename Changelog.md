# Changelog

### 1.19.0.0

- Created Grafana Dashboard to visualize Kubernetes volumes metrics
- OpenSearch migration: update grafana dashboards datasource
- Added Grafana Dashboards to visualize Kubernetes API metrics and Autoscaler stats
- OpenSearch migration: Implement Monitoring
- Fix: kubernetes-dashboards configmap "Too long" error
- Fix: PingAccess OSD dashboard incorrect visualisations
- Fix: OpenSearch PA-WAS dashboard: Tor/Threat geoIP marks are not displayed on Audit Map
- Fix: Pods CPU usage/memory usage/network I/O graphs have No data on the Kubernetes Cluster Monitoring dashboard
- Update OpenSearch version to 2.8.0 in dasboards data
- Logstash main pipeline refactoring
- Add Karpenter capacity and performance Grafana dashboard
- Add new metric for Kubernetes API Server Performance dashboard
- Fix P1AS Ingress Dashboard
- Add volume-autoscaler dashboard
- Upgrade grafana-operator, grafana-folders
- Fix wrong field in on ‘Ping Access Full System Logs' graph ‘Ping Access dashboard’
- Fix ingress label selector on the "PingOne Advanced Services Ingress Usage" dashboard
- Fix karpeneter dashboard
- Fix Grafana PA/PF Topology Dashboard

_Changes_

- [X] PDO-5245 Update grafana dashboards datasource
- [X] PDO-5265 Create Grafana Dashboard to visualize Kubernetes volumes metrics
- [X] PDO-5266 Create Grafana Dashboard to visualize Kubernetes API metrics
- [X] PDO-5307 Add OpenSearch monitoring
- [X] PDO-5500 OpenSearch PA-WAS dashboard: Tor/Threat geoIP marks are not displayed on Audit Map
- [X] PDO-5528 Logstash main pipeline refactoring
- [X] PDO-5530 Refactor Grafana 'PingAccess Topology Dashboard' queries to exclude healthcheckconnection information from them
- [X] PDO-5596 PingAccess OSD dashboard is broken
- [X] PDO-5601 os-dashboards-pf configMap breaks developer, and new ci/cd deploys
- [X] PDO-5830 Pods CPU usage/memory usage/network I/O graphs have No data on the Kubernetes Cluster Monitoring dashboard
- [X] PDO-5873 Update OpenSearch/OSD to v2.8
- [X] PDO-5923 Karpenter capacity and performance Grafana dashboard
- [X] PDO-6091 Add new metric for Kubernetes API Server Performance dashboard
- [X] PDO-6231 Fix P1AS Ingress Dashboard
- [X] PDO-6334 Kubernetes-Volume-Autoscaler: create the Grafana Dashboard
- [X] PDO-6560 Upgrade grafana-operator, grafana-folders
- [X] PDO-6676 Identify and map numeric fields in Elastic
- [X] PDO-6872 Fix wrong field in on Ping Access dashboard
- [X] PDO-6869 Fix karpeneter dashboard
- [X] PDO-7076 Fix ingress label selector
- [X] PDO-7081 Grafana PA/PF Topology Dashboard

### 1.18.0.0
- Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- Refactor 'Kibana PA Dashboard' queries to exclude healcheckconnection information from them
- PA dashboard migrated from Elasticsearch to Opensearch
- OpenSearch migration: Migrate PF dashboards
- OpenSearch migration: Migrate PA-WAS dashboard
- Add Logstash dashboard
- Fix: Splitted Grafana dashboards into different CMs to avoid length limit issue

_Changes_

- [X] PDO-4722 Grafana: replacement of "grafana-kubernetes-app" plugin
- [X] PDO-4952 Refactor 'Grafana PingFederate Topology Dashboard' queries to exclude healcheckconnection information from them
- [X] PDO-5114 OpenSearch migration: Migrate PA dashboard
- [X] PDO-5116 OpenSearch migration: Migrate PF dashboards
- [X] PDO-5117 OpenSearch migration: Migrate PA-WAS dashboard
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

