# FUTURE_CS_01 – Vulnerability Assessment Report

**Cyber Security Track**  
**Future Interns Internship (2026)**  
**Task 1: Vulnerability Assessment Report for a Live Website (Read-Only Scope)**

## 📋 Project Overview

This repository contains the deliverables for **Cyber Security Task 1** assigned by Future Interns.

I performed a **read-only, passive vulnerability assessment** on a publicly available practice website. The goal was to identify common security weaknesses, classify risks in business-friendly terms, and provide practical remediation steps — exactly as a security consultant would do for a small business or startup.

## 🎯 Target Website
- **URL**: https://www.certifiedhacker.com/
- **Type**: Publicly known ethical hacking / penetration testing practice website
- **Scope**: Only public-facing pages, passive scanning, header analysis, and configuration review (No exploitation, no active attacks, no login attempts)

## 🛠️ Tools Used
- **OWASP ZAP** – Passive scanning only (alerts, headers, cookies, information leakage)
- **Browser DevTools** (Chrome/Firefox) – Security headers, cookies, console errors
- **Wappalyzer** – Technology stack detection
- **Nmap** – Light port and service version scanning (`-sV`)
- **Canva** – Designed the professional Vulnerability Assessment Report (PDF)

All activities strictly followed the **ethical guidelines** provided in the task (public pages only + passive methods).

## 📄 Deliverables Included

- `Vulnerability_Assessment_Report.pdf` → Professional report designed in Canva (Executive Summary, Findings Table with Risk Levels, Remediation Steps, Screenshots)
- `/evidence/` folder → Screenshots of tool outputs, ZAP alerts, security headers, Nmap results, etc.
- This `README.md` file

## 🔍 Key Findings Summary
(You will update this section after completing your scan and report)

Common issues typically observed on this type of practice site include:
- Missing or weak security headers (HSTS, CSP, X-Frame-Options, etc.)
- Information disclosure through server headers or error messages
- Cookie security attribute issues
- Outdated or visible technology components

**Risk levels** were classified as **Low / Medium / High** based on potential business impact.

Full detailed findings, evidence, and remediation steps are available in the PDF report.

## 📌 Scope & Methodology
- **Allowed**: Passive reconnaissance, header checks, configuration analysis
- **Not Performed**: Any active exploitation, brute force, SQL injection, directory brute-forcing with aggressive tools, DoS, etc.
- Assessment conducted as a **security auditor**, not an attacker.

## 🚀 How to View the Report
1. Download `Vulnerability_Assessment_Report.pdf`
2. Open the `/evidence/` folder for supporting screenshots and tool outputs

## 📚 References & Inspiration
- OWASP Web Security Testing Guide (WSTG)
- Sample vulnerability reports from GitHub (as suggested in the task)

---

**Made with ❤️ as part of Future Interns Cyber Security Internship (Task 1 - 2026)**

**Note**: This assessment was performed solely for educational and internship purposes following strict ethical guidelines.
