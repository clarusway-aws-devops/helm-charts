## Get Repository Info

```bash
helm repo add clarusway-community https://raw.githubusercontent.com/clarusway-aws-devops/helm-charts/main
helm repo update
```

## Install petclinic microservices

```bash
helm install petclinic clarusway-community/petclinic_chart
```