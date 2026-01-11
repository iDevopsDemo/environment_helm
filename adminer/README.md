# Adminer Helm Chart

## How to use

Deploy via Helm

```sh
helm repo add ses-sample https://code.siemens.com/api/v4/projects/502963/packages/helm/devel
helm repo update

helm install -n ses-sample adminer ses-sample/adminer

#in order to deploy pre-release version use
helm install -n ses-sample --devel adminer ses-sample/adminer
```

### Optional Parameters

TODO
