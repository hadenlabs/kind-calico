# 🐳 Kind (Kubernetes in Docker)

## ✅ Requirements

- [Kind](https://kind.sigs.k8s.io) installed
- [Task](https://taskfile.dev) installed (for running predefined tasks)

---

## 🌐 Create Docker Network for Kind

```bash
task kind:network
```

> This command sets up the required Docker network so Kind cluster containers can communicate properly.

---

## 📦 Default Cluster

1. Copy the default configuration example:

   ```bash
   cp provision/kind/cluster/default.example.yml provision/kind/cluster/default.yml
   ```

2. Create the cluster:

   ```bash
   kind create cluster --config provision/kind/cluster/default.yml
   ```

---

## 🐯 Cluster with Calico (CNI)

1. Copy the Calico configuration example:

   ```bash
   cp provision/kind/cluster/calico.example.yml provision/kind/cluster/calico.yml
   ```

2. Create the cluster:

   ```bash
   kind create cluster --config provision/kind/cluster/calico.yml
   ```

> Make sure to apply Calico manifests after the cluster is up.

---

## 🔐 TLS Certificates

Generate TLS certificates for the Kind cluster:

```bash
task kind:certificates
```

### 🔑 Private Key (`key`)

```bash
task kind:certificates:key
```

### 📄 Certificate (`crt`)

```bash
task kind:certificates:crt
```
