# Detection Engineering Portfolio (SIEM, SOAR, Cloud Security)

Cybersecurity and Detection Engineer focused on building high-signal detections, automating incident response (IR), and strengthening cloud and identity security across Microsoft Azure and Google Cloud Platform (GCP).

## What this repository is
A **sanitized, recruiter-friendly portfolio** that demonstrates how I approach:
- Detection engineering and tuning (low-noise, high-confidence alerts)
- Threat hunting and investigation workflows
- SOAR automation design (response playbooks)
- Cloud security posture improvements (Azure and GCP)
- Security operations documentation (runbooks, evidence, repeatability)

No customer data. No internal URLs. No tenant IDs. No logs.

## Core skills and tooling
**SIEM and detection**
- Microsoft Sentinel: KQL (Kusto Query Language), analytics rules, hunting queries, alert tuning
- Splunk ES: SPL (Search Processing Language), detection engineering and correlation
- Google Chronicle: detection rules and investigation workflows

**Response automation (SOAR)**
- Azure Logic Apps: enrichment, notifications, ticketing, containment steps
- Google Cloud Functions: automated actions and integrations

**Cloud and identity security**
- Entra ID (Azure AD): Conditional Access, MFA, privileged access patterns
- GCP: Security Command Center (SCC), guardrails, logging strategy
- Security monitoring and telemetry design: what to log, why it matters, how to detect

## What you will find here (coming next)
- `detections/`  
  A detection index mapped to MITRE ATT&CK with signal intent, common false positives, tuning notes, and response actions.
- `queries/`  
  Generic KQL and SPL query samples written in a safe, reusable style.
- `automation/`  
  SOAR playbook designs (logic steps) for common incidents such as account compromise and suspicious cloud changes.
- `runbooks/`  
  Practical IR runbooks and checklists that show how incidents are handled end-to-end.

## Scope and principles
- **Signal over noise:** detections should be actionable, not alert spam.
- **Repeatability:** if it cannot be documented and run again, it does not scale.
- **Automation with guardrails:** automate safely and leave an audit trail.
- **Cloud-first reality:** identity + cloud telemetry are the modern battleground.

## Contact
LinkedIn: https://www.linkedin.com/in/akil-ahmad
