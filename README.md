# Grafana

Add config file in `prometheus/prometheus.yml`

```yml
global:
  scrape_interval: 5s
scrape_configs:
  - job_name: "job_name"
    static_configs:
      - targets: ["localhost:8080"]
```
