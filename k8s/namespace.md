# Namespace

## Default namespaces

1. Kube system
2. Kube public
3. Kube node lease
4. Default

## Why use namespace?

1. Structure components
2. Avoid conflicts between teams
3. Share services b/w/ different environments
4. Access management & resource quota

## Note

1. Configmap and secret can't be shared across namespaces
2. Service can be shared across namespaces
3. Volume and node is public at cluster level and can't be namespaced
    - `kubectl api-resources --namespaced=false`
    - `kubectl api-resources --namespaced=true`

## Commands

```shell
kubectl create namespace mongo
kubens mongo
```
