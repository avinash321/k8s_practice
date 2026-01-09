# k8s_practice
Kubernates Practice
kubectl cluster-info
kubectl version
kubectl api-resources
kubectl api-versions


# Run the minikume using below command
minikube start --driver=docker

# Kubernetes Commands
kubectl apply -f pod.yaml
kubectl get nodes

# PODS
kubectl get pods
kubectl create -f <pod_definition.yaml>
kubectl delete pod <pod_name>
kubectl describe pod <pod_name>
kubectl edit pod <pod_name>

# ReplicaSet
kubectl get replicaset ||  kubectl get rs
kubectl create -f <replicaset.yaml>
kubectl delete rs <replicaset_name>
kubectl describe <replicaset_name>
kubectl edit rs <replicaset_name>
kubectl scale rs <replicaset_name> --replicas=n

