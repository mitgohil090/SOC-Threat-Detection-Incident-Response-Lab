# Incident Response Notes

## Investigation Workflow

### 1. Identify
Review the Wazuh alert, timestamp, rule ID, severity, and affected endpoint.

### 2. Investigate
Examine related authentication events, command activity, or file changes to understand what happened.

### 3. Assess
Determine whether the event appears expected, suspicious, or requires further investigation. Do not classify an event as an attack based on a single alert alone.

### 4. Respond
For a confirmed security incident, follow the organisation's procedures. Possible actions include escalating to a senior analyst, containing an affected endpoint, or disabling a compromised account when authorised.

### 5. Document
Record the evidence, investigation steps, findings, actions taken, and any remaining uncertainty.

## Lab Learning

The Wazuh exercises provide practice reviewing authentication failures, privilege-related activity, and file integrity alerts.

These are educational exercises, not confirmed real-world security incidents.
