# Database

## PostgreSQL

```bash
kubectl kustomize --enable-helm kubernetes/overlays/core/databases/postgresql/base | kubectl apply -f -

```

### Apps

```bash
kubectl kustomize --enable-helm kubernetes/overlays/core/databases/postgresql/apps/default | kubectl apply -f -

```
