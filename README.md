# SOC Threat Detection and Incident Response Lab

## Overview

This project documents a hands-on Security Operations Centre (SOC) lab built with Wazuh SIEM and an Ubuntu endpoint running in WSL2.

The lab focuses on monitoring security events, reviewing alerts, testing file integrity monitoring, and documenting detection and investigation workflows.

## Objectives

- Deploy Wazuh using Docker Compose.
- Configure an Ubuntu endpoint for security monitoring.
- Generate controlled authentication and privilege-related events.
- Test File Integrity Monitoring (FIM).
- Develop and document a custom detection rule.
- Record findings, evidence, and recommended responses.
- Map activities to MITRE ATT&CK where appropriate.

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
| 03 | File integrity monitoring | Verified |
| 04 | Successful privilege-related activity | Verified |
| 05 | Custom suspicious-command detection | Implemented; end-to-end testing incomplete |

These exercises use controlled lab activity. They do not represent the detection of real-world attacks.

## Current Limitations

The Ubuntu Wazuh agent became disconnected during testing. The first four exercises were observed and documented, while end-to-end validation of the fifth custom rule remains incomplete.

## Project Goals

The aim is to develop practical skills in security monitoring, alert investigation, detection engineering, and incident response relevant to entry-level SOC Analyst and Security Analyst roles.

## Disclaimer

This project is for educational and defensive security purposes. All tests are performed in a local lab environment.
