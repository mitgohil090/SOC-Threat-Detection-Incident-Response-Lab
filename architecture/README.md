# Lab Architecture

## Environment

- Wazuh SIEM deployed using Docker Compose.
- Ubuntu endpoint running in WSL2.
- Wazuh agent configured for security event monitoring.

## Data Flow

Ubuntu endpoint → Wazuh agent → Wazuh manager → Alert investigation

## Current Status

The Wazuh environment is deployed locally. The Ubuntu agent is currently disconnected, so further end-to-end testing is pending.

## Architecture Diagram

```mermaid
flowchart TD
    A["Ubuntu WSL Endpoint<br/>Wazuh Agent"] -->|Security events| B["Wazuh Manager"]
    B -->|Alerts and indexed data| C["Wazuh Indexer"]
    C --> D["Wazuh Dashboard"]
    E["Your Browser"] -->|HTTPS| D

    style A fill:#dbeafe,stroke:#2563eb,color:#111827
    style B fill:#d1fae5,stroke:#059669,color:#111827
    style C fill:#fef3c7,stroke:#d97706,color:#111827
    style D fill:#ede9fe,stroke:#7c3aed,color:#111827
```
