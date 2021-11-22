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
