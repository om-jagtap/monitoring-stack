# Monitoring Stack (Prometheus + Grafana + Node Exporter)

This repository contains configuration and service files for setting up a monitoring stack on Linux.

## Components
- **Prometheus:** Metrics collection
- **Node Exporter:** Exposes host metrics
- **Grafana:** Visualization and dashboards

## Quick Start
1. Install binaries for Prometheus, Node Exporter, and Grafana
2. Copy service files from this repo to `/etc/systemd/system/`
3. Edit `prometheus.yml` as per your targets
4. Enable and start services:
   ```bash
   sudo systemctl daemon-reload
   sudo systemctl enable --now prometheus node_exporter grafana-server
screenshot
Grafana Dashboard >> <img width="1360" height="607" alt="image" src="https://github.com/user-attachments/assets/17ec8949-4d17-45e3-afde-a59a64f8d650" />
Node Exporter Metrice >> <img width="1365" height="606" alt="image" src="https://github.com/user-attachments/assets/3ae59caa-ae6e-40e1-b19a-92af72790dc2" />


