# p1as-eng-dashboards

This repository contains all observability dashboards for the P1AS platform. Dashboards are deployed via Kustomize and managed through ArgoCD.

## Repository Structure

```
.
├── grafana/          # Grafana dashboards (deployed as Kubernetes ConfigMaps)
├── kibana/           # Kibana/OpenSearch Dashboards (legacy — pre-OpenSearch migration)
├── os-dashboards/    # OpenSearch Dashboards (current)
```
---

## Release Workflow

See [Workflow.md](Workflow.md) for the branching and release process. This repo is soft-pinned to the PCB release cycle — all minor releases (e.g. `v1.17.0`, `v1.17.1`) pull dashboards from the same release branch (`v1.17-release-branch`).
