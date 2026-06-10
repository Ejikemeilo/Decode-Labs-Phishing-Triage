# Cyber Security Project 3 — Phishing Awareness Analysis

**Submitted by:** Ejikeme Cyril Ilo
**Project Title:** Phishing Awareness Analysis
**Program:** DecodeLabs Industrial Training Kit (Batch 2026)

## Objective

The objective of this project is to analyze suspicious emails and messages, identify phishing indicators, evaluate associated risks, and recommend appropriate security responses.

---

## Scenario 1: CEO Wire Transfer Request

**Message:**
- **From:** CEO – STRICTLY CONFIDENTIAL `<ceo.urgent@executive-update.com>`
- **Subject:** IMMEDIATE ACTION REQUIRED: Transfer Authorization
- **Content:** "URGENT: Process the attached wire transfer instruction immediately. This is critical and must remain strictly confidential. Do not discuss with anyone. Bypass standard procedure."

### Red Flags Identified
1. Urgent language designed to pressure the recipient.
2. Requests secrecy and discourages verification.
3. Instructs the recipient to bypass normal procedures.
4. Sender domain does not match the organization's official domain.
5. Uses executive authority to influence the recipient.

### Why It Is Unsafe
This message exhibits characteristics of **Business Email Compromise (BEC)**. Attackers impersonate executives to manipulate employees into making unauthorized financial transfers. The urgency and secrecy are intended to prevent verification.

**Risk Level:** HIGH

### Recommended Action
- Do not respond.
- Verify through an official communication channel.
- Report to the security team immediately.
- Block the sender.

---

## Scenario 2: Microsoft Account Security Alert

**Message:**
- **From:** Microsoft Support `<support@logins-updates.com>`
- **Subject:** FW: Urgent: Your Account Security Alert
- **Attachment:** `Security_Update_2024.iso`

### Red Flags Identified
1. Sender-domain mismatch.
2. Fake forwarded email chain.
3. Sense of urgency.
4. Suspicious attachment (.iso file).
5. Mimics a trusted company.

### Why It Is Unsafe
Legitimate Microsoft emails would originate from Microsoft's official domains. The attachment could contain malware designed to compromise systems and steal credentials.

**Risk Level:** CRITICAL

### Recommended Action
- Do not open the attachment.
- Delete or quarantine the email.
- Report the message as phishing.
- Run antivirus scans if interaction occurred.

---

## Scenario 3: ChatGPT Payment Failure Email

**Message:**
- **Subject:** Urgent: ChatGPT Payment Failure
- **Body:** "Your subscription payment failed. Please update your billing information immediately to avoid service interruption."

### Red Flags Identified
1. Creates financial urgency.
2. Requests sensitive payment information.
3. Encourages clicking a billing link.
4. Uses a well-known brand to gain trust.

### Why It Is Unsafe
Attackers frequently impersonate trusted services to steal credit card information and account credentials through fake payment portals.

**Risk Level:** HIGH

### Recommended Action
- Visit the service directly through the official website.
- Never use links provided in suspicious emails.
- Verify account status independently.

---

## Common Phishing Indicators Identified

| Indicator | Description |
|---|---|
| Urgency | Creates pressure to act immediately |
| Authority | Impersonates executives, IT staff, or trusted organizations |
| Fear | Threatens consequences if action is not taken |
| Curiosity | Encourages users to click to learn hidden information |
| Suspicious Domains | Uses lookalike or spoofed domains |
| Dangerous Attachments | Contains executable or unusual file types |
| Requests for Credentials | Attempts to steal passwords or MFA codes |
| Confidentiality Demands | Prevents verification with others |

---

## Types of Phishing Attacks

- **Mass Phishing** – Generic messages sent to many users.
- **Spear Phishing** – Highly targeted attacks using personal information.
- **Whaling** – Targets executives and senior management personnel.
- **Smishing** – Phishing conducted through SMS messages.
- **Vishing** – Voice-based phishing using phone calls.
- **Quishing** – QR-code-based phishing attacks.

---

## Best Practices for Protection

1. Pause before responding to urgent requests.
2. Verify requests using a trusted communication channel.
3. Inspect sender email addresses carefully.
4. Avoid clicking suspicious links.
5. Never share passwords or MFA codes.
6. Report suspicious messages immediately.
7. Keep security software updated.
8. Participate in phishing awareness training.

---

## Conclusion

Phishing remains one of the most effective cyberattack methods because it exploits human psychology rather than technical vulnerabilities. Through careful analysis of sender information, domains, urgency indicators, suspicious attachments, and requests for sensitive information, users can significantly reduce the risk of compromise.

The most effective defense strategy is to **Pause, Verify, and Report** before taking action on any suspicious communication.
