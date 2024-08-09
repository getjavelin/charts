# Javelin Kubernetes Helm Charts

#### Usage

[Helm](https://helm.sh/) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```code
helm repo add javelin-charts "https://getjavelin.github.io/charts"
```

You can then run `helm search repo javelin-charts` to see the charts.

#### Available Charts

* javelin-common
* javelin-webapp
* javelin-admin
* javelin-core
* javelin-ingress
* javelin-icap
* javelin-promptfoo
* javelin-evals
* javelin-flag
* javelin-redis
* javelin-postgresql
* javelin-elastic
* javelin-kibana

If you want to list all the available versions, then run `helm search repo javelin-charts --versions --devel`
