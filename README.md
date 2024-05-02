# Javelin Helm Charts

#### Charts

* javelin-webapp
* javelin-admin
* javelin-core

#### Add helm repo to the system

```
export CHART_NAME="javelin-charts"
helm repo add ${CHART_NAME} "https://getjavelin.github.io/charts"
helm repo update
helm search repo ${CHART_NAME} --versions --devel
```