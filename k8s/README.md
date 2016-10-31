Some tips
=========

ConfigMap
---------

To unset broker.id to allow for multiple replicas:

```kubectl create configmap nobrokerid-kafka --from-file=kafka.servers.properties --namespace=kafka-ns```
