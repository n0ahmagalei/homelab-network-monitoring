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

![Pi-Hole Dashbiard](screenshots/Pi-Hole-Dashboard)

## Grafana Dashboards

![Grafana Network Monitor](screenshots/Grafana-Network-Dashboard)

![Grafana Hardware Monitor](screenshots/Grafana-Hardware-Usage-Dashboard)

## Wireguard VPN

![Accepted Devices for VPN access](screenshots/Wireguard-VPN)

## Discord Alerts

![Daily Stats](screenshots/Discord-Daily-Stats)
![Suspicious Activity](screenshots/Discord-Suspicious-Acitvity)
![DNS Spikes](screenshots/Discord-DNS-Spike-Alerts)
![Connection Check](screenshots/Discord-Check-Connection)


