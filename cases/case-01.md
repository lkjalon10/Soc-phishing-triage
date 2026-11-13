# Case 01: [Alert rule name, e.g. SOC282 Phishing Alert – Deceptive Mail Detected]

**Verdict:** True Positive / False Positive | **Severity:** Low / Medium / High | **Escalated:** Yes / No

## Summary
One or two sentences: what happened and what I decided.

## Alert details
- Date/time:
- Alert rule:
- Recipient:
- Sender:
- Subject:
- Device action (allowed / blocked):

## Investigation
1. Header analysis: SPF / DKIM / DMARC results
2. URL check: VirusTotal, URLScan (what each showed)
3. Sender IP: AbuseIPDB result
4. Attachment: hash + sandbox result
5. Did the user click? (log evidence)

## IOCs (defanged)
| Type | Value |
|---|---|
| Sender | example@badsite[.]com |
| URL | hxxps://badsite[.]com/login |
| IP | 203.0.113[.]45 |

## Containment
What I did or would do: block the sender, purge the email, reset the password, isolate the host.

## MITRE ATT&CK
T1566 – Phishing

## What I learned
One or two honest lines.
