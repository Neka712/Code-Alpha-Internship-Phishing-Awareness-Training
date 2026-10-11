# Code-Alpha-Internship-Phishing-Awareness-Training
# CodeAlpha_PhishingAwarenessTraining

##  Overview
This project is part of the CodeAlpha Cybersecurity Internship (Task 2: Phishing Awareness Training). It is a presentation designed to help users recognize phishing emails and fake websites, understand social engineering tactics, and apply best practices to avoid falling victim — illustrated with two real, forensically analyzed email samples.

##  Objective
- Create a presentation focused on phishing attacks
- Explain how to recognize phishing emails and fake websites
- Educate about social engineering tactics used by attackers
- Provide best practices and tips to avoid falling victim
- Include real-world examples and quiz questions for better engagement

##  Tools & Materials Used
- Email header analysis (Notepad, raw .eml inspection)
- Authentication checks: SPF, DKIM, DMARC
- AbuseIPDB (IP reputation/WHOIS lookups)
- VirusTotal / urlscan (URL and redirect-chain analysis)
- MX Toolbox (domain health checks)
- Microsoft PowerPoint

##  Social Engineering Tactics Covered
- Urgency
- Authority
- Fear
- Curiosity & reward
- Trust exploitation
- Scarcity

##  Real-World Case Studies
1. Legitimate Email — a RedCloud recruitment notification sent via Teamtailor. SPF, DKIM and DMARC all passed; sending infrastructure traced to Amazon SES; all domains (From, Return-Path, body link) were consistent; content was personalized with no urgency tactics.
2. Phishing Email — an email impersonating Amazon requesting urgent account verification. SPF and DMARC failed; sender address did not match the Message-ID domain; the sending IP traced to an unrelated residential ISP; the embedded link passed through a Google redirect and a URL shortener before landing on a typosquat domain, which was confirmed as Phishing by a security vendor on VirusTotal.

##  Spotting a Fake Website
- Read the domain carefully for misspellings, extra words, or unusual endings (.xyz, .top, .info)
- Watch for typosquatting (e.g. "arnazon.com", "amaz0n-login.com")
- A padlock icon only confirms encryption, not legitimacy
- When in doubt, type the known address directly rather than clicking through

## Best Practices
- Verify independently through the official app or website
- Enable multi-factor authentication (MFA)
- Never enter credentials via a link in an unsolicited email
- Report suspicious emails to IT/security
- Verify unusual requests through a separate communication channel
- Practice recognizing red flags regularly

##  Knowledge Check
The presentation closes with a two-part quiz covering social engineering recognition, the two case studies, and safe-browsing habits.

##  Deliverable in This Repository
- Phishing_Awareness_Training_Presentation.pptx — the full presentation

##  Author
Philomena Ekhaizor — CodeAlpha Cybersecurity Internship
