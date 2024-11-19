# Homelab Infrastructure

This repository contains Docker Compose configurations for my self-hosted services and applications.

## Services

### System Management
- **Ansible Semaphore**: Web UI for Ansible automation
- **Nginx Proxy**: Reverse proxy for service routing
- **Unifi Network Application**: Network management controller

### Monitoring & Analytics
- **Grafana + InfluxDB**: Metrics visualization and time-series database
- **Pi-hole**: Network-wide ad blocking and DNS management

### Development & Tools
- **IT-Tools**: Collection of development and admin utilities
- **Openwebui**: Web-based interface
- **Penpot**: Design and prototyping platform

### Personal Knowledge Management
- **Obsidian Notes**: Markdown knowledge base
- **Trilium Notes**: Hierarchical note-taking system

### Finance & Trading
- **Freqtrade**: Cryptocurrency trading bot
- **Rotki**: Portfolio tracking and analytics
- **Hoarder**: Asset collection management

### Dashboard
- **Homepage**: Service dashboard and quick links

## Setup

1. Ensure Docker and Docker Compose are installed
2. Clone this repository:
```bash
git clone https://github.com/user52Real/homelab
```
3. Navigate to the desired service directory
4. Copy the example environment file:
```bash
cp .env.example .env
```
5. Configure the `.env` file with your settings
6. Start the service:
```bash
docker-compose up -d
```

## Maintenance

- Services can be updated using:
```bash
docker-compose pull
docker-compose up -d
```

- Monitor logs:
```bash
docker-compose logs -f
```

## Contributing

Feel free to submit issues and enhancement requests.
