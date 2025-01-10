[![Test Helm Charts](https://github.com/vendgogh/helm-charts/actions/workflows/release.yml/badge.svg)](https://github.com/vendgogh/helm-charts/actions/workflows/release.yml)
[![Commit activity](https://img.shields.io/github/commit-activity/m/vendgogh/helm-charts)](https://github.com/timescale/helm-charts/pulse/monthly)
[![License](https://img.shields.io/github/license/vendgogh/helm-charts)](https://github.com/vendgogh/helm-charts/blob/main/LICENSE)

# Timescale Helm Charts

This repository contains Helm charts to help with the deployment of
[TimescaleDB](https://github.com/timescale/timescaledb/) on Kubernetes. This
project is currently in active development.

## Repository

The Charts are available in a Helm Chart Repository hosted in Amazon S3 bucket.
The following command will make this repository ready for use:
```
helm repo add timescale 'https://vendgogh.github.io/helm-charts/'
```
For more information, have a look at the [Using Helm](https://helm.sh/docs/intro/using_helm/#helm-repo-working-with-repositories) documentation.

## Additional documentation

- [Why use TimescaleDB?](https://docs.timescale.com/introduction)
- [Installing TimescaleDB](https://docs.timescale.com/getting-started/installation)
- [Migrating data to TimescaleDB](https://docs.timescale.com/getting-started/migrating-data)
- [Tutorials and sample data](https://docs.timescale.com/tutorials)

# License

Resources in this repository are released under the [Apache 2.0 license](LICENSE).

# Contributing

If you wish to make contributions to this project, please refer to [Contributor Instructions](CONTRIBUTING.md) for more information.
