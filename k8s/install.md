# Installation

## Components
- Docker
- Minikube

## MacOS

### Install docker desktop

- https://docs.docker.com/desktop/mac/install/

### Install `minikube`
```
brew update
brew install minikube
minikube
kubectl
```
### Create cluster
```
minikube start --vm-driver=docker
kubectl get nodes
minikube status
kubectl version
```
