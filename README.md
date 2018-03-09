Metrics with Prometheus, Grafana and AlertManager
========

Docker containers for [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), and [AlertManager](https://github.com/prometheus/alertmanager).

## Installation

Clone this repository, access the folder docker-metrics, and execute docker-compose up with the following parameters (use -d for detached):

```bash
ADMIN_USER=admin ADMIN_PASSWORD=admin docker-compose up
```

Containers:

* Prometheus `http://<host>:9090`
* Prometheus Pushgateway `http://<host>:9091`
* AlertManager `http://<host>:9093`
* Grafana `http://<host>:3000`
