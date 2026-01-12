# Gamesa Sample

This umbrella chart allows to install the entire sample stack at once.

This umbrella chart contains:

* mosquitto
* mysql
* adminer
* comp-a
* comp-b
* comp-c

## How to use

Deploy via Helm

(Optional) In case of private registry usage, login to the registry first:

```sh
helm registry login -u myuser oci://ghcr.io/idevopsdemo/charts/gamesa-sample
```

```sh
helm install -n my-namespace gamesa-sample oci://ghcr.io/idevopsdemo/charts/gamesa-sample

#in order to deploy pre-release version use
helm install -n my-namespace --devel gamesa-sample oci://ghcr.io/idevopsdemo/charts/gamesa-sample
```

### Optional Parameters

TODO
