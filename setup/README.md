# Lab Setup and Tools

## Environment

- Operating system: Windows with Windows Subsystem for Linux 2 (WSL2)
- Linux distribution: Ubuntu
- SIEM platform: Wazuh
- Deployment method: Docker Desktop and Docker Compose

## Main Components

- Wazuh Manager: Processes security events and generates alerts.
- Wazuh Indexer: Stores and indexes security data.
- Wazuh Dashboard: Provides an interface to review alerts.
- Wazuh Agent: Collects endpoint events and sends them to the manager.

## Lab Purpose

The environment is used to practise security monitoring, authentication-event investigation, file integrity monitoring, and detection-rule configuration.

## Current Limitation

The Ubuntu Wazuh agent became disconnected during testing. End-to-end validation of the custom detection rule remains incomplete.
