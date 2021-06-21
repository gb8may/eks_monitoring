
# Kubernetes EKS monitoring with Prometheus and Grafana via Helm

Pre-requisites:
- eksctl
- kubectl
- helm

Helm version: 3.1.2
```
export DESIRED_VERSION=v3.1.2
curl -L https://git.io/get_helm.sh
```

Cluster deploy
```
eksctl create cluster -f eks_cluster.yaml
```

Monitoring deploy
```
bash monitoring-deploy.sh
```
