# Bootstrap

This directory contains the files required to deploy ArgoCD (Red Hat GitOps).
This is a prerequisite before being able to run `kustomize`.

## How do?

```bash
oc apply -f install-argocd.yml
```

Once the Red Hat GitOps (ArgoCD) operator has been deployed, then continue on with the [`kustomize`](../kustomize/README.md) configuration
