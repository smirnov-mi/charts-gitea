# HELM chart repository for Gitea

## Pre-req.

### required
K8s
Helm
Storage-class


### optional
Database
acme

## Values

see: https://gitea.com/gitea/helm-chart#database-defaults


## Install

connect this repo:
```bash
helm repo add https://smirnov-mi.github.io/charts-gitea/    [--insecure-skip-tls-verify]
```

verify that you see your package:
```bash
helm search repo gitea
```


## See also

https://dl.gitea.com/charts/

https://docs.gitea.com/installation/install-on-kubernetes?_highlight=kubernetes
