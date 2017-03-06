# Kafka Broker for Kubernetes

This is a development Kafka broker for Kubernetes. 
It uses two containers in a pod to instantiate Zookeeper and Kafka. 

It does not support scaling and it is not intented for production usage.

## Run

Ensure you are connected to a **Kubernetes** or **Openshift** cluster, then execute:

```
mvn fabric8:deploy
```

It will be deployed and started in the current namespace.

## Credits
- This project is based on the work of [Matthew Farrellee](https://github.com/mattf)