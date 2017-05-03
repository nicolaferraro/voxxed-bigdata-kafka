# Voxxed BigData Kafka

This repository contains the code of the Kafka broker used as demo at Voxxed talks in 2017.

It is a development Kafka broker for Kubernetes. 
It uses two containers in a pod to instantiate Zookeeper and Kafka. 

It does not support scaling and it is not intented for production usage.
 
## Running

1) Start [Openshift Origin Development Environment](https://github.com/openshift/origin/blob/master/docs/cluster_up_down.md). 

2) Execute: `mvn clean fabric8:deploy`

It will be deployed and started in the current namespace.

## Credits
- This project is based on the work of [Matthew Farrellee](https://github.com/mattf)