# Loki Helm Chart

- loki-stack · grafana/grafana (https://artifacthub.io/packages/helm/grafana/loki-stack)

## Get Repo Info

```console
$ helm repo add grafana https://grafana.github.io/helm-charts
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `loki`:

```console
$ helm install loki --version <version> grafana/loki-stack -f values.yaml
```

## Uninstalling the Chart

To uninstall/delete the loki deployment:

```console
$ helm delete loki
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
