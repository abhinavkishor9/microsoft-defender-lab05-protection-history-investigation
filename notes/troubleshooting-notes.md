# Troubleshooting Notes

## Issue

Protection History does not display malware detections.

### Cause

No threats have been detected recently.

### Resolution

Generate a safe EICAR test detection or review previous Defender labs to populate Protection History.

---

## Issue

Protection History only shows security recommendations.

### Cause

Windows Security records both protection actions and security recommendations.

### Resolution

Verify whether entries represent recommendations or actual threat detections before beginning an investigation.

---

## Issue

Windows Defender Operational log appears empty.

### Cause

Logging has not yet recorded recent Defender activity.

### Resolution

Run a Quick Scan, update Defender signatures, or restart Windows Security before reviewing logs.

---

## Issue

Unable to locate Defender Operational log.

### Resolution

Navigate to:

Applications and Services Logs

→ Microsoft

→ Windows

→ Windows Defender

→ Operational

---

## Issue

Event ID 5007 repeatedly appears.

### Cause

Microsoft Defender configuration or signature-related registry values have changed.

This commonly occurs after:

- Signature updates
- Defender setting modifications
- Windows Security configuration changes

### Resolution

Review the event details and verify whether the change was expected.

---

## Issue

Protection History and Event Viewer timestamps differ slightly.

### Cause

Protection History displays user-facing notifications while Operational logs record backend security events.

### Resolution

Correlate entries using approximate timestamps and event descriptions rather than exact time matches.

---

## Lessons Learned

- Protection History does not always indicate malware.
- Event ID 5007 commonly reflects Defender configuration updates.
- Defender Operational logs provide deeper investigation context than the Windows Security interface.
- Analysts should correlate multiple data sources before determining whether an incident exists.
