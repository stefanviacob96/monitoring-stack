# Containerized Monitoring Stack

A simple DevOps project using Docker Compose to run a monitoring stack with Prometheus and Grafana.

## Technologies
- Docker
- Docker Compose
- Prometheus
- Grafana
- WSL2 (Ubuntu)

## Services
- **Prometheus**: collects metrics
- **Grafana**: visualization dashboard

## How to run

1. Install Docker and Docker Compose
2. Clone the repository
3. Run:

```bash
docker compose up -d
```

## Access
- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

## Grafana default login:
- user: admin
- password: admin
