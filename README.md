# Kubernetes-Project

Kubernetes helps manage containerized applications in diffrent deployment environments.

Kubernetes components project based to Deployment using Minikube kubectl

# The Main Components of Kubernetes

 Node- is a  virtual or physical machine.
 
 Pod- abstraction over a container
 
 Service (internal,external)- used for communication
 
 Ingress -route for traffic  cluster
 
 Configmap -used for external configurations of an app
 
 Secret - used in storing secret data or credentials
 
        -data is stored in base64
        
        -we reference secret in pods
 
 Volume -used for data persistence (attached in physical drive or kubernetes cluster
 
 Deployment -this is abstraction on pods
 
 Statefulset -helps in replicating pods and uses databases Mysql or MongoDb
 
             -Deploying satefulset is hard

# Kubernetes Architecture

 1.Master node
 
 -helps in running k8s processes properly
 
 -It includes:
 
 ```
 API Server(api) -which is the entry point to k8s in either UI,API,CLI
 
 C-M(Controller) -keeps track of what happen in the cluster.
 
 Sched(Scheduler) -ensures pods placement and scheduling 
 
 etcd - kubernetes backing store
 
 Virtual network - turns all nodes into one powerful machine.
```
2.Worker nodes

This is where actual work(running applications) happens.

kubelet -is a k8s process that enables cluster communicate with each other.

# Kubernetes Configuration

 

