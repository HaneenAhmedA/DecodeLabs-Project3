# 🎣 PhishTriage — Phishing Awareness Analyzer
### DecodeLabs Industrial Training Kit | Cyber Security Project 3 | Batch 2026
[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit-00ff88?style=for-the-badge)](https://haneenAhmedA.github.io/DecodeLabs-Project3/phishing-triage.html)
---

## 📌 Project Overview

**PhishTriage** is an interactive phishing awareness analysis tool built as part of the DecodeLabs Cybersecurity Industrial Training Program. The goal is to simulate real-world phishing triage — analyzing suspicious emails, identifying red flags, and classifying threats using a structured decision framework.

This project covers the **detection phase**: understanding how phishing attacks are constructed, what psychological triggers they exploit, and how to respond correctly.

---

## 🎯 Objectives

- Analyze sample phishing emails to identify malicious intent
- Identify suspicious links, lookalike domains, and dangerous keywords
- List and classify red flags present in phishing messages
- Explain why each message is unsafe and what the appropriate response is

---

## 🚀 Features

- **5 Sample Phishing Emails** covering real attack scenarios:
  - IT Password Reset (Spear Phishing)
  - CEO Wire Transfer (Whaling / BEC)
  - PayPal Account Alert (Mass Phishing)
  - ChatGPT Payment Failure (SaaS Impersonation)
  - HR Benefits Form (Internal Impersonation)

- **11-Item Red Flag Checklist** — click through indicators manually per email
- **Live Threat Score** — updates in real time as flags are checked
- **Auto Verdict System** — classifies email as Safe / Suspicious / Malicious
- **Decision Tree** — highlights the correct triage action (Close / Warn User / Block & Escalate)
- **Email Analysis Panel** — breaks down sender anomalies, suspicious URLs, keywords, and psychology triggers
- **Why Unsafe Explanation** — appears automatically when 3+ flags are detected

---

## 🔴 Red Flags Covered

| # | Red Flag | Description |
|---|----------|-------------|
| 1 | Sender-Domain Mismatch | Display name conflicts with actual routing domain |
| 2 | Suspicious / Lookalike URL | Typosquatting, subdomain trap, or combosquatting |
| 3 | Fake Forwarded Chain | Pasted headers from conversations the user wasn't part of |
| 4 | Secrecy / Bypass Instructions | Demands to skip normal procedures |
| 5 | Artificial Urgency | Time pressure: "expires in X hours", "immediately" |
| 6 | Sensitive Info Request | Asks for credentials, MFA codes, or payment details |
| 7 | Threat of Negative Consequence | Account closure, legal action, loss of service |
| 8 | Authority Impersonation | CEO, IT, HR, or government agency spoofing |
| 9 | Dangerous Attachment | Uncommon extensions (.iso, .js, .scr) or suspicious filenames |
| 10 | No Verification Option | Alternate channel verification blocked or impossible |
| 11 | Grammar / Formatting Errors | Broken sentences, odd phrasing, mismatched legal text |

---

## 🧠 Phishing Types Demonstrated

| Type | Description |
|------|-------------|
| Mass Phishing | Generic lures mimicking known brands (PayPal, Microsoft) |
| Spear Phishing | Targeted attack using contextual details |
| Whaling | Targeting executives for high-value wire transfers (BEC) |
| SaaS Impersonation | Impersonating SaaS platforms to steal billing info |
| Internal Impersonation | Spoofing HR or IT from lookalike external domains |

---

## 🔀 Triage Decision Tree

```
Incoming Suspicious Email
├── 0 flags     → SAFE       → Close Email
├── 1–3 flags   → SUSPICIOUS → Warn User
└── 4+ flags    → MALICIOUS  → Block Domain & Escalate
```

---


📸 Screenshots
Main interface — email loaded, no flags checked

<img width="1877" height="907" alt="Screenshot 2026-06-03 114428" src="https://github.com/user-attachments/assets/cef446bb-90ab-4157-b1ce-ea438e7c617e" />

Malicious verdict — 4+ flags checked

<img width="1885" height="909" alt="Screenshot 2026-06-03 114454" src="https://github.com/user-attachments/assets/22b41988-e8ad-4896-b417-b3dcabb7ead1" />

CEO Wire Transfer email analysis

<img width="1874" height="904" alt="Screenshot 2026-06-03 114513" src="https://github.com/user-attachments/assets/687309c0-5a24-4abe-8dc4-5a93992129e4" />

Why Unsafe explanation panel

<img width="904" height="170" alt="Screenshot 2026-06-03 114539" src="https://github.com/user-attachments/assets/c3f1889a-1de3-408a-8b5e-9cedf8be4fe8" />


---

## 🛠️ Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- No frameworks, no dependencies
- Single-file application — open directly in any browser

---

## 📂 How to Run

1. Clone the repository:
```bash
git clone https://github.com/HaneenAhmedA/DecodeLabs-Project3.git
```
2. Open `phishing-triage.html` in any browser — no server needed.

---

## 📄 License

This project was built as part of the DecodeLabs Industrial Training Program. All phishing samples are fictional and created for educational purposes only.
