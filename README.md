# 🦉 OWeb

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OWeb** — Web Recon & Security Analysis Suite ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OWeb is a web-application reconnaissance and assessment suite that fingerprints technologies, enumerates endpoints and checks for common web misconfigurations. It crawls a target, identifies server and framework details, inspects security headers and surfaces potential issues. It runs as a desktop application for authorized web-security testing.

---

## ✨ Features


- Technology fingerprinting (server, framework, CMS) from responses and headers
- Endpoint enumeration and crawling of the target application
- Security-header inspection (HSTS, CSP, X-Frame-Options and more)
- Detection of common web misconfigurations and information disclosure
- Export of findings for reporting
- Desktop UI in the OWLSec theme with an offline --self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OWeb
./OWeb --self-test
./OWeb --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
