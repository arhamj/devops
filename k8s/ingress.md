# Ingress

- To use ingress we require an ingress controller
- Ingress controller is a separate pod which evaluates the ingress rules and takes care of service
  redirection

## Commands

```shell
# install ingress controller on minikube
sudo minikube addons enable ingress

sudo minikube dashboard --url

kubectl apply -f dashboard/dashboard-ingress.yml
```
