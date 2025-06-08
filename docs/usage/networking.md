# Networking

## Calico

```bash
kubectl kustomize --enable-helm kubernetes/overlays/system/apps/networking/apps/calico | kubectl apply --server-side -f -

```

## Cilium

```bash
kubectl kustomize --enable-helm kubernetes/overlays/system/apps/networking/apps/cilium | kubectl apply -f -
```
