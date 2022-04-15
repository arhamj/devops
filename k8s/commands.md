# Commands

## Deployment

```shell
# Using CLI options
kubectl create deployment nginx-depl --image=nginx
kubectl edit deployment nginx-depl
kubectl delete deployment nginx-depl

# Using config file
kubectl apply -f deployment/nginx-deployment.yaml
kubectl delete -f nginx-deployment.yaml

kubectl get deployment
```

## Miscellaneous

```shell
# Get component status
kubectl get nodes
kubectl get pod
kubectl get services
kubectl get deployment
kubectl get replicaset

# Debugging
kubectl logs {pod-name}
kubectl exec -it {pod-name} -- bin/bash
```
