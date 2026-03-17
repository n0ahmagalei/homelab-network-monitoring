# Raspberry Pi Homelab – Network Monitoring & Security

This project documents my self-hosted homelab environment built to monitor
network traffic, block malicious domains, and visualize DNS activity.

## Infrastructure

- Raspberry Pi 4
- Docker containers
- Pi-hole DNS sinkhole
- Grafana monitoring dashboards
- Prometheus exporters
- WireGuard VPN for remote access
- Discord webhook alerting

## Features

- Network-wide ad and malware blocking
- DNS query monitoring per device
- Real-time dashboards in Grafana
- Automated alerts for outages and suspicious DNS activity
- Remote access via WireGuard VPN

## Tech Stack

- Docker
- Linux
- Pi-hole
- Grafana
- Prometheus
- WireGuard
- Bash scripting

## Architecture

![Network Diagram](architecture/network-diagram.png)

## Pi-Hole Dashboard

![Pi-Hole Dashbiard](screenshots/Pi-Hole-Dashboard.png)

## Grafana Dashboards

### Network Monitor
![Grafana Network Monitor](screenshots/Grafana-Network-Dashboard.png)

### Hardware Monitor
![Grafana Hardware Monitor](screenshots/Grafana-Hardware-Usage-Dashboard.png)

## Wireguard VPN

### Accepted Devices

![Accepted Devices for VPN access](screenshots/Wireguard-VPN.png)

## Discord Alerts

### Daily Stats
![Daily Stats](screenshots/Discord-Daily-Stats.png)

### Suspicious Activity
![Suspicious Activity](screenshots/Discord-Suspicious-Domains.png)

### DNS Spikes
![DNS Spikes](screenshots/Discord-DNS-Spikes.png)

### Connection Check
![Connection Check](screenshots/Discord-Connection.png)


