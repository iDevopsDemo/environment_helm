# MYSQL Helm Chart

This chart will deploy a mysql db into the cluster

## How to use

Deploy via Helm

```sh
#(Optional) In case of private registry usage, login to the registry first:
helm registry login -u myuser oci://ghcr.io/idevopsdemo/charts/mysql

helm install -n my-namespace mysql oci://ghcr.io/idevopsdemo/charts/mysql

#in order to deploy pre-release version use
helm install -n my-namespace --devel mysql oci://ghcr.io/idevopsdemo/charts/mysql
```

### Optional Parameters

TODO

```sh
helm upgrade --install -n my-namespace --set nodeSelector."kubernetes\\.io/arch"=amd64 mysql oci://ghcr.io/idevopsdemo/charts/mysql
```
