# Adminer Helm Chart

## How to use

Deploy via Helm

```sh
#(Optional) In case of private registry usage, login to the registry first:
helm registry login -u myuser oci://ghcr.io/idevopsdemo/charts/adminer

helm install -n my-namespace adminer oci://ghcr.io/idevopsdemo/charts/adminer

#in order to deploy pre-release version use
helm install -n my-namespace --devel adminer oci://ghcr.io/idevopsdemo/charts/adminer
```

### Optional Parameters

TODO

### Test Trigger

Test123
