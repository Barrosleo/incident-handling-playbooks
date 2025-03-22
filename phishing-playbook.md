# Phishing Email Incident Handling Playbook

## Overview
This playbook provides a structured approach for handling phishing email incidents. It guides teams through the detection, containment, eradication, recovery, and post-incident activity stages.

## Detection
- **Signs of a phishing email:**
  - Suspicious sender email addresses.
  - Urgent or unusual requests.
  - Links leading to suspicious domains.
  - Unexpected attachments.
- **Tools:**
  - Email gateway logs.
  - Anti-phishing tools (e.g., Microsoft Defender for Office 365).
  - Employee reports.
- **Steps:**
  1. Analyze email headers for mismatched domains.
  2. Check URLs against threat intelligence databases.

## Containment
- **Short-Term:**
  - Quarantine the email in all inboxes.
  - Block malicious URLs/IPs in security systems.
  - Alert employees about the phishing campaign.
- **Long-Term:**
  - Reset passwords for affected accounts.
  - Enhance email filtering rules.

## Eradication
- Remove malicious payloads from affected systems.
- Revoke and reset credentials for compromised accounts.
- Scan devices with Endpoint Detection and Response (EDR) tools.

## Recovery
- Verify system integrity and restore affected accounts.
- Monitor for suspicious activity post-recovery.

## Post-Incident Activity
- Conduct a post-incident review to evaluate team performance and improve processes.
- Update playbooks and train employees with simulated phishing exercises.
- Document the incident in a detailed report for future reference.

