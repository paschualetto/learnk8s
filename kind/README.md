# Kind cluster

## Installation

```
curl -Lo ./kind https://kind.sigs.k8s.io/d1/v0.17.0/kind-linux-amd64
chmod +x ./kind
sudo mv ./kind /usr/local/bin/kind
```


## Usefull commands

```
kind create cluster --config cluster.yaml --name <cluster_name>
kind delete cluster --name <cluster_name>
```