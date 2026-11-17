[# personal-siem-home-lab
Building and documenting a Wazuh SIEM home lab for security monitoring, detection engineering, and incident response.](https://tech-insider.org/wazuh-siem-tutorial-2026/)
# Personal Wazuh SIEM Home Lab





## Project Overview

This project involves designing, deploying, configuring, and documenting a Security Information and Event Management (SIEM) home lab using Wazuh and Microsoft Hyper-V.

The objective is to develop a functional security monitoring environment capable of collecting, centralizing, analyzing, and detecting suspicious activity across multiple operating systems.

The lab will use dedicated Linux virtual machines hosted on Hyper-V, with Wazuh serving as the centralized security monitoring platform.

This project focuses on developing practical skills in Security Operations Center (SOC) analysis and cybersecurity engineering.

## Project Objectives

### Security Operations (SOC)

- Centralize security logs from monitored endpoints.
- Monitor authentication and system activity.
- Identify suspicious behavior through security alerts.
- Investigate security events and establish incident timelines.
- Map relevant detections to the MITRE ATT&CK framework.
- Document findings and recommended remediation.

### Security Engineering

- Design and deploy a virtualized security monitoring infrastructure.
- Install and configure Wazuh central components.
- Deploy and manage endpoint monitoring agents.
- Configure firewall policies and network access controls.
- Implement File Integrity Monitoring (FIM).
- Configure vulnerability detection and Security Configuration Assessment (SCA).
- Develop and test custom detection rules.
- Automate selected security monitoring tasks using Python, Bash, and PowerShell.

## Technology Stack

| Technology        | Purpose                                  |
| ----------------- | ---------------------------------------- |
| Wazuh             | SIEM and endpoint security monitoring    |
| Microsoft Hyper-V | Virtualization                           |
| Ubuntu Server     | SIEM server operating system             |
| Kali Linux        | Linux security monitoring endpoint       |
| Windows 11        | Windows security monitoring endpoint     |
| Git               | Version control                          |
| GitHub            | Project documentation and source control |
| Python            | Security automation and log analysis     |
| Bash              | Linux administration and automation      |
| PowerShell        | Windows administration and automation    |

*Technologies and configurations will be updated as implementation progresses.*

## Lab Architecture

The planned architecture uses a centralized Wazuh deployment with separate virtual machines for monitored endpoints.

### Central SIEM Server

The Wazuh server will host the following components:

- Wazuh Manager: Security event analysis, rule processing, and agent management.
- Wazuh Indexer: Security alert indexing and storage.
- Wazuh Dashboard: Security monitoring, visualization, and investigation.

### Monitored Endpoints

- Ubuntu Linux
- Kali Linux
- Windows 11

Wazuh agents will collect endpoint telemetry and forward security events to the central Wazuh server.

**Network architecture diagram:** Coming soon.

## Security Monitoring Capabilities

The following capabilities are planned for implementation:

| Capability                        | Objective                                 | Status  |
| --------------------------------- | ----------------------------------------- | ------- |
| Centralized Logging               | Collect endpoint security events          | Planned |
| Authentication Monitoring         | Detect suspicious login activity          | Planned |
| File Integrity Monitoring         | Identify unauthorized file changes        | Planned |
| Vulnerability Detection           | Identify vulnerable software              | Planned |
| Security Configuration Assessment | Evaluate endpoint security configurations | Planned |
| Custom Detection Rules            | Develop additional detection logic        | Planned |
| MITRE ATT&CK Mapping              | Classify detected adversary techniques    | Planned |
| Incident Investigation            | Analyze and document security alerts      | Planned |
| Firewall Management               | Restrict unauthorized network access      | Planned |
| Security Automation               | Automate selected monitoring tasks        | Planned |

## Repository Structure

```text
personal-siem-home-lab/
│
├── README.md
├── architecture/
├── documentation/
├── configurations/
├── firewall/
├── detection-rules/
├── scripts/
├── screenshots/
├── tests/
└── CHANGELOG.md
```

### Documentation

This repository will contain technical documentation covering architecture design, installation procedures, configuration decisions, troubleshooting, detection development, and security investigations.

## Implementation Roadmap

- [ ] Phase 1: Infrastructure and network architecture
- [ ] Phase 2: Wazuh server deployment
- [ ] Phase 3: Endpoint agent installation and enrollment
- [ ] Phase 4: Centralized log collection and validation
- [ ] Phase 5: Firewall configuration and network hardening
- [ ] Phase 6: Security monitoring and detection engineering
- [ ] Phase 7: Controlled security event simulation
- [ ] Phase 8: Incident investigation and reporting
- [ ] Phase 9: Security automation and project evaluation

## Testing and Validation

Security monitoring capabilities will be validated using controlled activities within the isolated lab environment.

Testing will include:

- Simulated authentication failures.
- File creation, modification, and deletion.
- Suspicious process execution.
- Endpoint configuration changes.
- Detection rule validation.
- Firewall connectivity and access-control testing.

Test procedures, expected outcomes, actual results, and supporting evidence will be documented.

## Documentation and Version Control

Git will be used throughout development to track configuration changes, documentation updates, scripts, and detection engineering work.

Meaningful commits will document the progression of the project and the reasoning behind significant implementation decisions.

## Learning Outcomes

This project is intended to develop practical experience in:

- SIEM deployment and administration.
- Linux and Windows system administration.
- Network security and firewall management.
- Security event analysis and log correlation.
- Threat detection and investigation.
- Detection engineering.
- Incident response.
- Security automation.
- Technical documentation and version control.

## Security Disclaimer

This project is an educational cybersecurity home lab.

All security testing and simulated activities will be conducted on systems and networks owned by me or for which I have explicit authorization.

Sensitive information, credentials, private keys, and personal data will not be published in this repository.

## References

- [Wazuh Official Documentation](https://documentation.wazuh.com/current/)
- [Wazuh Quickstart Installation Guide](https://documentation.wazuh.com/current/quickstart.html)
- [Tech Insider - Wazuh SIEM Tutorial 2026](https://tech-insider.org/wazuh-siem-tutorial-2026/)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Microsoft Hyper-V Documentation](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/)

---

**Project Status:** Infrastructure planning and initial architecture design.
