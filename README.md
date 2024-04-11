# Mimir Singleton Helm
This is a basic helm chart that provides the ability to run Grafana Mimir as a single binary.

## Usage

```bash
helm repo add https://intergral.github.io/mimir-singleton-helm/
helm install mimir mimir-singleton/mimir-singleton --namespace mimir
```
