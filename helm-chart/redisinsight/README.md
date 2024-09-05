# redisinsight
Redis GUI Helm Chart

```
helm repo add redisinsight https://mrnim94.github.io/redisinsight/
"redisinsight" has been added to your repositories

helm search repo redisinsight
NAME                                            CHART VERSION   APP VERSION     DESCRIPTION
redisinsight/redisinsight        1.0.0          2.54         A Helm chart for Kubernetes
```

## Install Helm and create package and index helm

```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh

helm package ./helm-chart/redisinsight/
helm repo index ./
```
