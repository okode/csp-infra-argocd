# CSP Common Infraestructure tools

## ArgoCD
```bash
cd charts/argo-cd/
```

First we need to generate the Helm chart lock file.
```bash
helm repo add argo-cd https://argoproj.github.io/argo-helm
```
```bash
helm dep update charts/argo-cd
```

