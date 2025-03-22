# Indicator of Compromise (IOC) Template

## What is an IOC?
An Indicator of Compromise (IOC) is evidence that an incident has occurred, such as malicious IP addresses, domain names, or file hashes. Use this template to document IOCs discovered during an investigation.

## Template
| IOC Type        | Details                              | Notes                  |
|------------------|--------------------------------------|------------------------|
| IP Address       | Example: 192.168.1.10               | Associated with C2 traffic. |
| Domain Name      | Example: malicious-site.com         | Used in phishing emails.   |
| File Hash (MD5)  | Example: e99a18c428cb38d5f260853678922e03 | Hash of the malicious payload. |
| File Name        | Example: invoice.doc.exe            | Found in phishing attachment. |
| Registry Key     | Example: HKEY_LOCAL_MACHINE\Software\Malware | Created by malware.        |
| URL              | Example: http://malicious-site.com/payroll-update | Phishing site URL.         |

## Usage
- Populate the table with all discovered IOCs during an investigation.
- Share the IOCs with internal and external threat intelligence teams.
