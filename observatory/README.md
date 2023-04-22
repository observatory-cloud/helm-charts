## Get started

Lighthouse Observability helm charts based on Grafana.

## Documentation

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
```sh
helm dependency build .
helm upgrade --install <release name> -n <namespace> . -f overwrites.yaml --create-namespace
```

## License