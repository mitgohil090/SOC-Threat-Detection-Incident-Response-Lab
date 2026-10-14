# SOC Threat Detection and Incident Response Lab

## Overview

This project documents a hands-on Security Operations Centre (SOC) lab built using Wazuh SIEM, Ubuntu Linux, Docker Compose, and Windows Subsystem for Linux 2 (WSL2).

The lab explores security event monitoring, authentication-log analysis, file integrity monitoring, and investigation of privilege-related activity in a controlled environment.

## Objectives

- Deploy Wazuh using Docker Compose.
- Configure an Ubuntu endpoint for security monitoring.
- Generate controlled authentication and privilege-related events.
- Test File Integrity Monitoring (FIM).
- Review and investigate security alerts.
- Document findings, evidence, and recommended responses.

## Tools and Technologies

- Wazuh SIEM
- Ubuntu Linux
- Windows Subsystem for Linux 2 (WSL2)
- Docker Desktop and Docker Compose
- Linux command line
- GitHub and Markdown

## Detection Exercises

| Exercise | Description | Status |
|---|---|---|
| 01 | Single authentication failure | Verified |
| 02 | Repeated authentication failures | Verified |
| 03 | File Integrity Monitoring | Verified |
| 04 | Successful privilege-related activity | Verified |

These exercises use controlled lab activity and are intended for educational and defensive security purposes. They do not represent the detection of real-world attacks.

## Project Status

The four documented exercises were observed and recorded in the local lab environment. Supporting screenshots and documentation are included in this repository.

## Project Goals

The aim is to develop practical skills in security monitoring, alert investigation, Linux security, and incident-response documentation relevant to entry-level SOC Analyst and Security Analyst roles.

## Disclaimer

This project is for educational and defensive security purposes. All tests are performed in a local lab environment.

## Project Documentation

- [Lab Architecture](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/architecture/README.md)
- [Lab Setup and Tools](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/setup/README.md)
- [Detection Exercises](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/detections/README.md)
- [Lab Evidence Guide](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/evidence/README.md)
- [Wazuh Screenshots](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/screenshots/README.md)
- [Incident Response Workflow](https://github.com/mitgohil090/SOC-Threat-Detection-Incident-Response-Lab/blob/main/incident-response/README.md)

## Skills Demonstrated

- Security event monitoring with Wazuh
- Linux authentication-event investigation
- File Integrity Monitoring (FIM)
- Privilege-related event analysis
- Security alert review
- Technical documentation and evidence management
