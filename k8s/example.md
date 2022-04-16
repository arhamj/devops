# Example

## Components

1. MongoDB
    - Internal service
2. Mongo Express
    - External service

## Services

1. 2 Deployments/Pods
2. 2 Service
3. 1 ConfigMap
4. 1 Secret

## Commands

```shell
kubectl apply -f example/mongo-secret.yml
kubectl apply -f example/mongo-deployment.yml
kubectl apply -f example/mongo-configmap.yml
kubectl apply -f example/mongo-express-deployment.yml

# To assign an external IP
minikube service mongodb-express-service

kubectl get all
```
