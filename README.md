# QuantumAPI Helm Charts

Official Helm charts for deploying the [QuantumAPI](https://quantumapi.eu) platform on Kubernetes.

## Usage

```bash
helm repo add quantumapi https://charts.quantumapi.eu
helm repo update

helm install quantumapi quantumapi/mislata \
  --namespace quantumapi \
  --create-namespace \
  --values values.yaml
```

## Charts

| Chart | Description | Version |
|-------|-------------|---------|
| [mislata](charts/mislata) | Full QuantumAPI platform (Identity, API, Worker, PostgreSQL, Redis) | 0.1.0 |

## Documentation

- [Kubernetes Deployment Guide](https://docs.quantumapi.eu/en/on-premises/kubernetes)
- [Configuration Reference](https://docs.quantumapi.eu/en/on-premises/kubernetes/configuration)
- [Operations Guide](https://docs.quantumapi.eu/en/on-premises/kubernetes/operations)

## License

Proprietary. A valid QuantumAPI on-premises license is required.
