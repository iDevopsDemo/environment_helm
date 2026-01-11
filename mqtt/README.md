# MQTT-Broker Chart

This helm charts installs a Mosquitto-MQTT-Broker

## How to use

Just install the helm chart via:

```sh
helm repo add k8s-at-home https://k8s-at-home.com/charts/
helm repo update

helm install -n my-namespace mosquitto k8s-at-home/mosquitto
```

### Optional Parameters

TODO

```sh
helm install -n my-namespace --set nodeSelector."kubernetes\\.io/hostname"=<name of a node> mosquitto k8s-at-home/mosquitto
```

```sh
helm install -n my-namespace --set nodeSelector."kubernetes\\.io/arch"=<arch to use e.g. amd64> mosquitto k8s-at-home/mosquitto
```
