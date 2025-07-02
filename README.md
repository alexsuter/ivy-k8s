# Axon Ivy on Kubernetes

Exploring how to the deploy the Axon Ivy Engine on Kubernetes

## minikube

1. Install minikube https://minikube.sigs.k8s.io/docs/start
2. Install kubectl https://kubernetes.io/docs/tasks/tools/
3. Start minikube `minikube start`
4. Show dashboard `minikube dashboard`

## namespace

1. Create a new namespace `kubectl create namespace sandbox`
2. Show all namespaces `kubectl get namespaces`
3. Delete a namespace `kubectl delete namespace sandbox`

4. Show current namespace `kubectl config view --minify --output 'jsonpath={..namespace}'`
5. Switch namespace `kubectl config set-context --current --namespace=sandbox`
