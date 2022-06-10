# Spinnaker Chart

[Spinnaker](http://spinnaker.io/) is an open source, multi-cloud continuous delivery platform.

## Chart Details
This chart will provision a fully functional and fully featured Spinnaker installation
that can deploy and manage applications in the cluster that it is deployed to.

Redis and Minio are used as the stores for Spinnaker state.

For more information on Spinnaker and its capabilities, see it's [documentation](http://www.spinnaker.io/docs).

## Installing the Chart

To install the chart with the release name `zebrax-spinnaker`:

```bash
$ clone this repository
$ kubectl create ns zebrax-spinnaker
$ helm install zx-spinnaker /charts/spinnaker/ --values /charts/spinnaker/values.yaml --namespace zebrax-spinnaker
```
