# Detection-Engineering-Incident-Response-Lab


# Cybersecurity Portfolio | Detection Engineering, Incident Response & DFIR

Hands-on cybersecurity investigations, Windows security monitoring, threat detection, digital forensics, and cloud security projects built, tested, and documented in an isolated lab environment.

I use this portfolio to demonstrate practical security skills through reproducible investigations, evidence-based analysis, detection logic, and clear technical documentation.

## About This Portfolio

This repository documents my progression in defensive cybersecurity, with a focus on understanding attacker behavior, investigating security telemetry, validating suspicious activity, and improving detection and response workflows.

My primary areas of focus are:

- Security Operations Center (SOC) investigations
- Windows security monitoring and Active Directory security
- Detection engineering and threat hunting
- Incident response and digital forensics
- Cloud security monitoring and investigation
- Security automation with PowerShell and Python
- AI security and emerging attack surfaces

Projects are documented as hands-on exercises with their objectives, methodology, evidence, findings, limitations, and opportunities for improvement.

## Technical Focus

| Area | Technologies and Skills |
|---|---|
| Windows security | Windows 11, Windows Server 2022, Active Directory, Group Policy |
| Endpoint telemetry | Sysmon, Windows Security logs, process creation events |
| Detection engineering | Event analysis, process lineage, detection logic, false-positive analysis |
| Investigation | PowerShell, event correlation, command-line analysis, digital-signature validation |
| Digital forensics | Evidence preservation, timeline analysis, forensic investigation workflows |
| Cloud security | AWS security controls, CloudTrail, IAM, VPC security, EC2 |
| Network security | Network traffic analysis, Wireshark, network security fundamentals |
| Automation | PowerShell and Python for security investigation workflows |
| Threat intelligence | MITRE ATT&CK mapping and adversary behavior analysis |

*Technologies listed reflect my learning and project focus; individual project READMEs describe which tools were actually used and validated.*

## Featured Projects

### 1. Windows Security Telemetry and Detection Engineering

**Status:** In progress

Building and investigating a Windows security lab to understand process execution, authentication activity, endpoint telemetry, and detection opportunities.

Topics include:
- Windows Advanced Audit Policy and Group Policy configuration
- Security Event ID analysis
- Sysmon Event ID 1 process-creation telemetry
- Process lineage and parent-child relationships
- Command-line investigation
- Digital-signature validation
- Evidence collection and investigation reporting
- Detection tuning and false-positive considerations

**Skills demonstrated:** Windows logging, PowerShell, endpoint investigation, evidence-based analysis.

**Project:** `windows-detection-engineering/` *(repository folder to be created or linked when available)*

### 2. Active Directory Security Monitoring

**Status:** In progress

Investigating identity and authentication activity in an isolated Active Directory lab.

Planned areas include:
- Domain authentication and Kerberos event analysis
- Account and group management auditing
- Privileged logon investigation
- Suspicious authentication patterns
- Identity-related detection opportunities
- Defensive validation and investigation documentation

The focus is on understanding the telemetry defenders need to investigate identity-related threats.

**Skills demonstrated:** Active Directory, Windows event logs, identity security, detection engineering.

### 3. Digital Forensics and Incident Response

**Status:** Planned / developing

Developing repeatable workflows for collecting evidence, constructing timelines, investigating endpoint activity, and documenting incident findings.

Planned areas include:
- Evidence handling and preservation
- Endpoint artifact collection
- Timeline construction
- Process execution investigation
- Incident scoping and root-cause analysis
- Containment and recovery decision-making
- Incident reports and response playbooks

**Skills demonstrated:** Forensic reasoning, incident investigation, evidence documentation, response planning.

### 4. AWS Cloud Security and Monitoring

**Status:** Previous project / expanding documentation

Documenting cloud security assessment work involving AWS infrastructure, identity and access controls, network boundaries, and security monitoring.

Areas of focus include:
- IAM permissions and least privilege
- VPC and security group configuration
- EC2 security
- AWS CloudTrail investigation
- Logging and monitoring controls
- Security assessment findings and remediation recommendations

Project documentation will distinguish implemented controls, observed results, and recommendations.

**Skills demonstrated:** Cloud security fundamentals, AWS logging, access control analysis, infrastructure security.

### 5. Network Security and Traffic Analysis

**Status:** Planned / developing

Building practical network investigation skills through controlled lab exercises.

Planned areas include:
- Packet capture and protocol analysis
- DNS and connection behavior
- Identifying unusual network activity
- Correlating network evidence with endpoint telemetry
- Documenting findings and investigation limitations

**Skills demonstrated:** Network analysis, packet inspection, investigative reasoning.

### 6. Security Automation

**Status:** Planned / developing

Developing small, practical scripts to reduce repetitive work during security investigations.

Potential projects include:
- Parsing and normalizing Windows event data
- Extracting process and parent-process relationships
- Summarizing investigation artifacts
- Automating basic triage and report generation
- Improving repeatability and evidence consistency

**Skills demonstrated:** PowerShell, Python, structured data handling, security workflow automation.

### 7. AI Security and Threat Research

**Status:** Research and project development

Exploring defensive security challenges involving AI applications, agents, tool permissions, data access, and credential exposure.

Areas of interest include:
- AI application threat modeling
- Excessive agent permissions
- Secrets and credential protection
- Prompt-injection risks and tool misuse
- Security monitoring for AI-enabled workflows
- Defensive guardrails and incident response

Each project will focus on a defined threat scenario, practical validation, and measurable defensive recommendations.

**Skills demonstrated:** Threat modeling, security research, risk analysis, defensive design.

## Investigation Methodology

I aim to use a consistent workflow across projects:

1. **Define the scenario:** Identify the system, threat, security question, and scope.
2. **Collect evidence:** Gather relevant logs, process records, configurations, or network artifacts.
3. **Investigate:** Correlate timestamps, process relationships, identities, command lines, and other available context.
4. **Validate:** Test assumptions and distinguish observed facts from hypotheses.
5. **Assess:** Explain findings, confidence, false-positive possibilities, and remaining gaps.
6. **Document:** Preserve appropriate evidence and publish a reproducible technical report.
7. **Improve:** Identify detection gaps and propose specific defensive improvements.

## Evidence and Documentation Standards

Where applicable, project documentation includes:

- Objective and lab architecture
- Tools and configuration
- Reproducible investigation steps
- Sanitized screenshots and exported evidence
- Detection logic and validation results
- False-positive considerations
- Limitations and unresolved questions
- Recommended remediation or next steps

I do not treat a process name, an isolated event, or a single indicator as conclusive proof of malicious activity. Findings are based on available evidence and are qualified when additional validation is needed.

## Learning and Development

I am continuously developing practical skills in:

- Windows endpoint monitoring
- Active Directory security
- SOC investigation workflows
- Detection engineering
- Incident response and DFIR
- Cloud security monitoring
- Security automation
- AI security

This repository will evolve as projects are implemented, tested, reviewed, and improved.

## Connect



I'm interested in learning from security practitioners, exchanging investigation techniques, and improving practical defensive security workflows.

## Disclaimer

All lab activities are performed on systems I own or am authorized to test. Offensive techniques, where included, are restricted to controlled lab environments and documented for defensive learning.

This repository is an evolving technical portfolio. Project status and claims are updated as implementations and validation are completed.
