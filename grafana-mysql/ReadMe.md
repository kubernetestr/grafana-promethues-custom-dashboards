```console
kubectl apply -f mysql-pv.yaml
kubectl apply -f mysql-deployment.yaml
helm install --name grafana stable/grafana -f grafana-values.yaml
```
