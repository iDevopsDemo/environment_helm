# MYSQL Helm Chart

This chart will deploy a mysql db into the cluster

## How to use

Deploy via Helm

```sh
helm repo add ses-sample https://code.siemens.com/api/v4/projects/502963/packages/helm/devel
helm repo update

helm install -n ses-sample mysql ses-sample/mysql

#in order to deploy pre-release version use
helm install -n ses-sample --devel mysql ses-sample/mysql
```

### Optional Parameters

TODO

```sh
helm upgrade --install -n ses-sample --set nodeSelector."kubernetes\\.io/arch"=amd64 mysql ses-sample/mysql
```
