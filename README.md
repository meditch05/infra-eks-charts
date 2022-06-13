# Helm Repository w/GitLab

## [ busybox-eks-sample ]

```bash
helm repo add eks-sample-app https://gitlab.biz-think.net/paas/sample-charts/charts
helm install -n infra eks-sample-app/busybox-eks-sample
helm uninstall -n infra busybox-eks-sample
# Ref: https://insight.infograb.net/blog/2022/03/14/gitlab-helm-package-registry/
```
