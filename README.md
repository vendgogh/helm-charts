[![Commit activity](https://img.shields.io/github/commit-activity/m/vendgogh/helm-charts)](https://github.com/timescale/helm-charts/pulse/monthly)

# Vendgogh Helm Charts

This repository contains Helm charts for deploying Vendgogh services on
Kubernetes.

## Adding the Helm repository

To add the Helm repository, run the following command:

```bash
helm repo add vendgogh https://vendgogh.github.io/helm-charts
```

## Installing a chart

To install a chart, run the following command:

```bash
helm install my-release vendgogh/<chart-name>
```

