# Highflame Helm Charts

#### Usage

[Helm](https://helm.sh/) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```code
helm repo add highflame-charts "https://highflame-ai.github.io/charts"
helm repo update highflame-charts
```

You can then run `helm search repo highflame-charts` to see the charts.

If you want to list all the available versions, then run `helm search repo highflame-charts --versions --devel`

#### Available Charts

* highflame-generic

* highflame-ingress

* highflame-postgres

* highflame-redis

* highflame-redteam
