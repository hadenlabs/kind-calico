# Ingress Controller

## Nginx

### base

```bash
kubectl kustomize --enable-helm kubernetes/overlays/system/nginx/base | kubectl apply -f -
```

### ingress-nginx

```bash
kubectl kustomize --enable-helm kubernetes/overlays/system/nginx/apps/ingress-nginx | kubectl apply -f -
```
