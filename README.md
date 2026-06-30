# microsoft-defender-lab05-protection-history-investigation

## Objective

Investigate Microsoft Defender Protection History and correlate security actions with Windows Defender Operational logs.

---

## Lab Environment

- Windows 10 VM
- Microsoft Defender Antivirus
- Windows Security
- Event Viewer

---

## Skills Practiced

- Microsoft Defender Protection History
- Windows Defender Operational Logs
- Event Viewer Analysis
- Endpoint Investigation
- Defender Event Correlation
- SOC Investigation Workflow

---

## Lab Tasks

- Open Windows Security.
- Navigate to Virus & Threat Protection.
- Review Protection History entries.
- Analyze Protection History notifications.
- Open Windows Defender Operational logs in Event Viewer.
- Review Defender Operational Event IDs.
- Correlate Protection History with Operational log events.
- Document investigation findings.

---

## Key Findings

- Protection History displayed recent security recommendations rather than malware detections.
- No active threats were present on the endpoint.
- Windows Defender Operational log recorded configuration and protection-related events.
- Event ID 5007 confirmed Defender configuration changes.
- Defender antivirus protection remained operational throughout the investigation.

---

## MITRE ATT&CK

No adversary techniques observed during this lab.

The lab focused on defensive monitoring and endpoint visibility.

---

## Learning Outcome

This lab demonstrates how SOC analysts review Microsoft Defender Protection History alongside Windows Defender Operational logs to validate endpoint security status, identify configuration changes, and distinguish informational events from actual security incidents.
