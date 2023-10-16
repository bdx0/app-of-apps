# app-of-apps

```shell
# bootstrap
kubectl kustomize --enable-helm https://github.com/bdx0/app-of-apps | kubectl apply -f -
```

# Spec

- storage
  - rook/ceph
  - nfs
  - minio
  - samba
- jobs
  - argocd
  - tekton
  - jenkins
  - airflow
- source
  - gitlab
  - gitea
  - github
- container images
  - registry -> habor
- load balaner
  - haproxy
  - ingress-nginx
  - metallb
- distribution message queue

  - kafka

- monitor performance -> metric
- evaluation -> grafana
- improve itself

# Plan

- install rook
- install gitlab
- install jenkins
