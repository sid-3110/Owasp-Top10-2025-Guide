# 🛡️ OWASP Top 10 — Complete Beginner's Interactive Guide

> A free, self-contained interactive web guide that takes absolute beginners from zero web security knowledge to OWASP Top 10 interview-ready. No sign-up. No install. Works fully offline. Responsive on every device.

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Open_Guide-e84141?style=for-the-badge)](https://sid-3110.github.io/owasp-beginners-guide/owasp-guide.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Modules](https://img.shields.io/badge/Modules-19-blue?style=for-the-badge)]()
[![Zero Install](https://img.shields.io/badge/Setup-Zero_Install-orange?style=for-the-badge)]()
[![Responsive](https://img.shields.io/badge/Devices-Mobile%20%7C%20Tablet%20%7C%20Desktop-a78bfa?style=for-the-badge)]()

---

## 🎯 Who Is This For?

- 🔰 **Absolute beginners** — no prior web or security knowledge required
- 🎓 Students preparing for **Security+, CEH, BTL1, eWPT** exams
- 💼 Anyone prepping for a **SOC Analyst, AppSec, or Pentester** interview
- 🐛 **Bug bounty hunters** starting out — OWASP is your target list
- 👩‍💻 Developers who want to understand what they're defending against

---

## 📚 What's Covered — 19 Modules

### Foundation (Start Here)
| Module | Topic |
|--------|-------|
| 01 | What is Cybersecurity? CIA Triad, why OWASP matters for your career |
| 02 | How Web Applications Work — HTML, CSS, JS, APIs, databases explained simply |
| 03 | HTTP, HTTPS & Status Codes — reading requests, responses, and attack patterns |
| 04 | What is OWASP? — history, methodology, why every interview asks about it |

### OWASP Top 10 — 2025
| # | Vulnerability | Covered |
|---|---------------|---------|
| A01 | Broken Access Control (IDOR, privilege escalation) | ✅ Full |
| A02 | Cryptographic Failures (HTTP vs HTTPS, password storage) | ✅ Full |
| A03 | Injection (SQL Injection step by step) | ✅ Full |
| A04 | Insecure Design (business logic flaws) | ✅ Full |
| A05 | Security Misconfiguration (default creds, verbose errors) | ✅ Full |
| A06 | Vulnerable & Outdated Components (Log4Shell walkthrough) | ✅ Full |
| A07 | Identification & Auth Failures (brute force, credential stuffing) | ✅ Full |
| A08 | Software & Data Integrity Failures (supply chain, SolarWinds) | ✅ Full |
| A09 | Security Logging & Monitoring Failures | ✅ Full |
| A10 | Server-Side Request Forgery (SSRF) | ✅ Full |

### Essential Extras
| Module | Topic |
|--------|-------|
| Extra | XSS Deep Dive — Stored, Reflected, DOM-based |
| Extra | CSRF Deep Dive — forged requests explained |
| Extra | SSRF vs CSRF — clear comparison |

### Career Application
| Module | Topic |
|--------|-------|
| 17 | SOC Analyst Alert Response — every OWASP attack as a real SIEM alert + investigation steps |
| 18 | Quick Quiz — 5 interview-style questions with instant feedback |

---

## ✨ Features

- **Fully responsive** — works on mobile phones, tablets (iPad), laptops, and large monitors
- **Mobile sidebar drawer** — hamburger menu (☰) slides in the full navigation on small screens
- **Zero setup** — single HTML file, open directly in browser, works fully offline
- **Real attack demonstrations** — actual payload examples in annotated code blocks
- **SOC alert view** — every vulnerability shown as a real SIEM/WAF alert with investigation steps
- **Interactive quiz** — 5 questions with instant explanations
- **Sidebar navigation** — jump to any module instantly
- **Keyboard navigation** — ← → arrow keys to move between modules
- **Progress bar** — visual completion tracking
- **Analogies for every concept** — designed for complete beginners
- **Dark professional UI** — readable, distraction-free

---

## 📱 Device Support

| Device | Experience |
|--------|-----------|
| 📱 Mobile (≤768px) | Hamburger menu, stacked layout, scrollable tables, full-width buttons |
| 📱 Small phones (≤390px) | Ultra-compact, single-column everything |
| 📟 Tablet / iPad (768–1024px) | Narrowed sidebar, 2-column grids, optimized padding |
| 💻 Laptop / Desktop (1024–1400px) | Full sidebar, all features |
| 🖥️ Large monitors (≥1400px) | Expanded content width, larger typography |

---

## 🚀 Quick Start

### View Online
```
https://sid-3110.github.io/owasp-beginners-guide/owasp-guide.html
```

### Run Locally
```bash
git clone https://github.com/sid-3110/owasp-beginners-guide.git
cd owasp-beginners-guide

# macOS
open owasp-guide.html

# Windows — double-click the file, or:
start owasp-guide.html

# Any OS with Python
python3 -m http.server 8080
# Visit: http://localhost:8080/owasp-guide.html
```

**No npm. No pip. No dependencies. One file. Works offline.**

---

## 🗂️ Repository Structure

```
owasp-beginners-guide/
├── owasp-guide.html     # The complete interactive guide (single file)
├── README.md            # This file
└── LICENSE              # MIT License
```

---

## 🎓 Learning Path This Guide Follows

```
1. What is security? (CIA Triad)
      ↓
2. How web apps are built (Frontend → Backend → Database)
      ↓
3. HTTP language (requests, methods, status codes)
      ↓
4. OWASP context (why it matters, how data is collected)
      ↓
5. All 10 vulnerabilities (definition → attack → real example → SOC alert → fix)
      ↓
6. XSS, CSRF, SSRF deep dives
      ↓
7. SOC analyst alert response reference card
      ↓
8. Interview quiz to test retention
```

---

## 🤝 Contributing

Contributions welcome. Especially needed:
- More quiz questions
- Additional real-world breach examples
- API security / OWASP API Top 10 module
- Lab environment setup guide

1. Fork the repo
2. `git checkout -b feature/your-improvement`
3. Make changes + test in browser (resize to mobile!)
4. Submit Pull Request

---

## ⭐ Star This Repo

If this helped you prepare for an interview or understand something that was confusing — please star it. It helps other learners find it.

---

## 📜 License

MIT — free to use, share, and modify for any purpose.

---

## 🔗 Connect

Built by Siddharth Kamble
- LinkedIn: https://www.linkedin.com/in/siddharth-kamble-311046mvp
- GitHub: https://github.com/sid-3110

---
*Open an issue if anything is outdated, incorrect, or missing. PRs are always welcome.*
