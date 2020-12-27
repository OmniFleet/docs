# Installing Prometheus Operator Notes

Installing via helm chart https://github.com/prometheus-community/helm-charts

Using the kube-prometheus-stack
helm install promstack prometheus-community/kube-prometheus-stack -n observability -f values.yaml
