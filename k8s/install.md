# Installation

## Components

- Docker
- Minikube

## MacOS

### Install docker desktop

- https://docs.docker.com/desktop/mac/install/

### Install `minikube`

```shell
brew update
brew install minikube
minikube
kubectl
brew install kubectx
```

### Create cluster

```shell
minikube start --vm-driver=docker
kubectl get nodes
minikube status
kubectl version
```

### Restart

```shell
minikube stop
minikube delete
rm -rf ~/.minikube/
minikube start
```
