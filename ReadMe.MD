# WIP !!!

## Install kube-prometheus

- Check https://github.com/mehmetmgrsl/k8s-prometheus-grafana

## Install Loki

- ```helm repo add grafana https://grafana.github.io/helm-charts```

- ```helm install -n monitoring --values loki-values.yaml loki grafana/loki```


# Resources:
1*. https://grafana.com/docs/loki/latest/?pg=oss-loki&plcmt=quick-links

2*. https://github.com/AdminTurnedDevOps/kubernetes-examples/blob/main/open-source-observability-stack/instructions.md

