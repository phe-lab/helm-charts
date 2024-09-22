# PheLab - Helm Charts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/phelab)](https://artifacthub.io/packages/search?repo=phelab)
[![release-charts](https://github.com/phe-lab/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/phe-lab/helm-charts/actions/workflows/release.yaml)
[![pages-build-deployment](https://github.com/phe-lab/helm-charts/actions/workflows/pages/pages-build-deployment/badge.svg?branch=gh-pages)](https://github.com/phe-lab/helm-charts/actions/workflows/pages/pages-build-deployment)

PheLab's Helm Charts for Kubernetes.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```bash
helm repo add phelab https://charts.phelab.com
helm repo update
```

You can then run `helm search repo instant-chart` to see the charts.
