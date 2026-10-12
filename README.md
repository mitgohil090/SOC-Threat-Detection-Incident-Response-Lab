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
## Project Status and Next Steps

### Completed
- Wazuh single-node lab deployed using Docker Compose.
- Four security monitoring exercises documented with supporting screenshots.
- Custom suspicious-command rule configured and its configuration validated.

### In Progress
- Restoring the Ubuntu Wazuh agent connection.
- Completing end-to-end validation of the custom suspicious-command rule.
- Expanding detection and incident-response exercises.

### Planned Improvements
- Add a lab architecture diagram.
- Improve detection investigation notes.
- Explore incident-response integrations and automation in a controlled lab environment.

The custom rule has not yet been confirmed to generate an end-to-end alert.
## Disclaimer

This project is for educational and defensive security purposes. All tests are performed in a local lab environment.
## Project Documentation

- [Lab Architecture](architecture/README.md)
- [Lab Setup and Tools](setup/README.md)
- [Detection Exercises](detections/README.md)
- [Lab Evidence Guide](evidence/README.md)
- [Wazuh Screenshots](screenshots/README.md)
- [Incident Response Workflow](incident-response/README.md)

## Skills Demonstrated

- Security event monitoring with Wazuh
- Linux authentication-event investigation
- File Integrity Monitoring (FIM)
- Privilege-related event analysis
- Basic detection-rule configuration and validation
- Security documentation and evidence management
