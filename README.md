# cassandra-px
This repository demonstrates how to deploy Cassandra on Kubernetes, and configure it to use Portworx for persistent storage

## Before you begin
### Install Portworx
Follow instructions here: https://docs.portworx.com/portworx-install-with-kubernetes/

## Using statefulset
```
kubectl apply -f manifest/cassandra-sts.yaml
```

## Using Operator

## Using helm