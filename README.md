# Supervision Lab – Prometheus & Grafana

Monitoring lab deployed with **Docker Compose** to collect infrastructure metrics with **Prometheus** and visualize them in **Grafana** dashboards.

## 🎯 Objective
Set up a monitoring stack to supervise services and detect anomalies (availability, resource usage), a core building block of SOC and IT operations.

## 🏗️ Architecture
- **Prometheus** – scrapes and stores metrics (configured in `prometheus.yml`)
- **Grafana** – connects to Prometheus as a data source and displays dashboards
- **Docker Compose** – deploys the whole stack in one command

## 🚀 Usage
```bash
git clone https://github.com/hiba-jl/supervision-prometheus-grafana.git
cd supervision-prometheus-grafana
docker compose up -d
```
- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

## 🛠️ Tech stack
Prometheus · Grafana · Docker Compose
