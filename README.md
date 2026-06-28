# TRIAGE — Phishing Detection & Awareness Toolkit

A rule-based SOC-style console that analyzes emails and URLs for common phishing indicators, built as a capstone project for the **GTU | IBM SkillsBuild — From Vulnerability to Defense** cybersecurity training program.

## What it does

TRIAGE checks submitted URLs and emails against a set of known phishing patterns and returns a transparent risk score with reasoning — not a black-box verdict.

**Detection signals:**
- Domain impersonation & typosquatting (Levenshtein/edit-distance matching against known brand domains)
- Sender / Reply-To domain mismatches
- Urgency and pressure language ("verify now," "account suspended," etc.)
- Structural red flags — raw IP hosts, suspicious TLDs, excessive subdomains/hyphens
- Direct requests for credentials or personal information

## How to use it

Open `index.html` in any browser — no installation, no server, no dependencies. Everything runs client-side; no data leaves your browser.

Or visit the live version: https://github.com/shkfaizan119-create/triage-phishing-toolkit.git
website link :- file:///C:/Users/Faizan/Downloads/phishing-toolkit-website.html

## Tech

Single-file HTML/CSS/JavaScript. No frameworks, no build step.

## Limitations

This is a rule-based detector, not a machine-learning classifier — it catches known patterns reliably but can miss novel phishing techniques. It does not perform live WHOIS, domain-age, or SPF/DKIM/DMARC checks. Built for educational and awareness purposes.

## Built for

GTU | IBM SkillsBuild Skill-Based Training Program 2026 — *From Vulnerability to Defense: Cyber Security Systems*
