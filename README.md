## Observatory.Cloud - Helm Charts
Observatory is a complete monitoring stack that includes Tracing, Metrics and Logging.

## Documentation
Please go to docs.observatory.cloud for the detailed documentation.

##### Components
* Grafana
* Loki
* Promtail
* Mimir
* Tempo
* Grafana Agent
* Prometheus
* OpenTelemetry Collector

## Installation Guide

You can install charts using Helm 3

#### Example
Basic Installation
```sh
helm repo add obs https://observatory-cloud.github.io/helm-charts/
helm repo update
helm install observatory obs/observatory
```

Disabling/Enabling certain modules:
```sh
helm upgrade --install <release name> -n <namespace> . --set loki.enabled=false --set tempo.enabled=true ..
```

## License

MIT