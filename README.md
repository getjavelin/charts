# Javelin Helm Charts

#### Charts

* javelin-common
* javelin-webapp
* javelin-admin
* javelin-core
* javelin-ingress
* javelin-icap
* javelin-promptfoo
* javelin-evals
* javelin-flag

#### Add helm repo to the system

```
export CHART_NAME="javelin-charts"
helm repo add ${CHART_NAME} "https://getjavelin.github.io/charts"
helm repo update
helm search repo ${CHART_NAME} --versions --devel
```
