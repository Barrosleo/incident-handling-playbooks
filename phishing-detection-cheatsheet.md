# Phishing Detection Cheatsheet

## Purpose
This cheatsheet provides quick guidelines for identifying phishing emails.

## Red Flags in Phishing Emails
1. **Sender Information:**
   - Look for spoofed email addresses (e.g., admin@amazon-payment-security.com).
2. **Subject Line:**
   - Beware of urgency (e.g., "URGENT: Reset Password Immediately").
3. **Body Content:**
   - Poor grammar and spelling errors.
   - Unusual requests for credentials or financial details.
4. **Links:**
   - Hover over links to see if they redirect to suspicious or mismatched domains.
   - Example: `http://malicious-site.com/reset-password`.

## Tools for Detection
- **Email Header Analyzer:**
  - Analyze the "From" and "Reply-To" fields for mismatched domains.
- **Threat Intelligence:**
  - Cross-check URLs, domains, and attachments against known malicious indicators.
- **Anti-Phishing Software:**
  - Use tools like Microsoft Defender or Proofpoint to detect phishing.

## Best Practices
- Report suspicious emails immediately to the SOC or security team.
- Never click on links or open attachments from unknown senders.
- Use multi-factor authentication (MFA) to protect accounts.

