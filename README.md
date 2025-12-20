# Highflame Helm Charts

#### Usage

[Helm](https://helm.sh/) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```code
helm repo add javelin-charts "https://highflame-ai.github.io/charts"
helm repo update javelin-charts
```

You can then run `helm search repo javelin-charts` to see the charts.

If you want to list all the available versions, then run `helm search repo javelin-charts --versions --devel`

#### Available Charts

* javelin-elastic

* javelin-generic

* javelin-ingress

* javelin-kibana

* javelin-kafka

* javelin-postgresql

* javelin-redis

* javelin-redteam