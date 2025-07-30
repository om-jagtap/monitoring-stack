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


