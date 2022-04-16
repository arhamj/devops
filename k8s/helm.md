# Helm

- It is a package manager for k8s yaml files
- Bundle of Yaml files are known as `Helm` charts
- Helm charts can be pushed to repositories
- Helm is also a template engine. Syntax similar to Golang template
- Helm chart sample dir structure

```
chart/
  Chart.yaml
  values.taml
  charts/
  templates/
```

- V3 gets rid of `Tiller`- an additional service to parse charts and provision resources
- Helm helps with release management and rollbacks

```shell
helm install <name>
helm upgrade <name>
helm rollback <name>
```
