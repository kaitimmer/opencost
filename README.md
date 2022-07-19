<img src="./opencost-header.png"/>

# OpenCost — your favorite open source cost monitoring tool for Kubernetes

OpenCost models give teams visibility into current and historical Kubernetes spend and resource allocation. These models provide cost transparency in Kubernetes environments that support multiple applications, teams, departments, etc.


OpenCost was originally developed and open sourced by [Kubecost](https://kubecost.com). This project combines a [specification](/spec/) as well as a Golang implementation of these detailed requirements.

![OpenCost allocation UI](/allocation-drilldown.gif)

To see the full functionality of OpenCost you can view [OpenCost features](https://opencost.io). Here is a summary of features enabled:

- Real-time cost allocation by Kubernetes service, deployment, namespace, label, statefulset, daemonset, pod, and container
- Dynamic asset pricing enabled by integrations with AWS, Azure, and GCP billing APIs
- Supports on-prem k8s clusters with custom pricing sheets
- Allocation for in-cluster resources like CPU, GPU, memory, and persistent volumes.
- Allocation for AWS & GCP out-of-cluster resources like RDS instances and S3 buckets with key (optional)
- Easily export pricing data to Prometheus with /metrics endpoint ([learn more](PROMETHEUS.md))
- Free and open source distribution (Apache2 license)

## Getting Started

You can deploy OpenCost on any Kubernetes 1.8+ cluster in a matter of minutes, if not seconds!

Visit the full documentation for [recommended install options](https://www.opencost.io/docs/install). Compared to building from source, installing from Helm is faster and includes all necessary dependencies.

## Usage

- User interface
- [Cost APIs](https://github.com/kubecost/docs/blob/master/apis.md)
- [CLI / kubectl cost](https://github.com/kubecost/kubectl-cost)
- [Prometheus metric exporter](kubecost-exporter.md)

## Contributing

We :heart: pull requests! See [`CONTRIBUTING.md`](CONTRIBUTING.md) for information on buiding the project from source
and contributing changes.

## Community

If you need any support or have any questions on contributing to the project, you can reach us on [Slack](https://join.slack.com/t/kubecost/shared_invite/enQtNTA2MjQ1NDUyODE5LWFjYzIzNWE4MDkzMmUyZGU4NjkwMzMyMjIyM2E0NGNmYjExZjBiNjk1YzY5ZDI0ZTNhZDg4NjlkMGRkYzFlZTU) or via email at [team@kubecost.com](team@kubecost.com).

## FAQ

You can view [OpenCost documentation](https://www.opencost.io/docs/FAQ) for a list of commonly asked questions.