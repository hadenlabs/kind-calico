# Kind

## Network

```bash
task kind:network
```

## Default

```bash
cp -rf provision/kind/cluster/default.example.yml provision/kind/cluster/default.yml
```

### Make Kind

```bash
kind create cluster --config provision/kind/cluster/default.yml
```

## Calico

```bash
cp -rf provision/kind/cluster/calico.example.yml provision/kind/cluster/calico.yml
```

### Make Kind

```bash
kind create cluster --config provision/kind/cluster/calico.yml
```

## Certificates

```bash
task kind:certificates
```

### key

```bash
task kind:certificates:key
```

### crt

```bash
task kind:certificates:crt
```
