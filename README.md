# Monitoring Stack: Prometheus + Grafana + node_exporter

## Состав

- Prometheus (`prometheus/prometheus.yml`)
- Grafana:
  - Datasource (`grafana/datasource.yml`)
  - Dashboards (`grafana/dashboards/*.json`)
- node_exporter (`node_exporter/systemd/`)

## Быстрый старт

1. Установи `Prometheus`, `Grafana`, `node_exporter`
2. Добавь конфиги из этого репо
3. Импортируй дашборд в Grafana

## Полезные команды

```bash
# Проверка Prometheus
curl http://localhost:9090/targets

# Проверка node_exporter
curl http://localhost:9100/metrics
