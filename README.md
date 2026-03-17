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

## Example Dashboard

![Grafana](screenshots/Grafana-Netowrk-Dashboard.png)
