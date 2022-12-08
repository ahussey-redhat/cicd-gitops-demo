# Kustomize

## Prerequisites
- [ ] Access to a Red Hat OpenShift Container Platform (RHOCP/OCP) cluster, with valid credentials
- [ ] Logged into the RHOCP cluster
- [ ] Run the [bootstrap config](../bootstrap/README.md)

## What do now?

Let's configure the cluster!
```bash
oc kustomize ./kustomize/environments/sno/kustomize.yml | oc apply -f -
```
