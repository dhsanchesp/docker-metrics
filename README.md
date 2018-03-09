Metrics with Prometheus, PushGateway and Grafana
========

Docker containers for [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), and [AlertManager](https://github.com/prometheus/alertmanager).

## Installation

Clone this repository, access the folder docker-metrics, and execute docker-compose up with the following parameters (use -d for detached):

```bash
ADMIN_USER=admin ADMIN_PASSWORD=admin docker-compose up
```

Containers:

* Prometheus `http://<host>:9090`
* AlertManager `http://<host>:9093`
* Grafana `http://<host>:3000`
