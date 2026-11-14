<h1 align="center">⚡ Web Fuzzing Arsenal</h1>

<p align="center">
  <strong>The complete professional toolkit for web content discovery, parameter mining, backup file hunting, and vulnerability scanning.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Updated-2026-blue?style=flat-square" alt="2026">
  <img src="https://img.shields.io/badge/Tools-13-success?style=flat-square" alt="13 Tools">
  <img src="https://img.shields.io/badge/Commands-90+-orange?style=flat-square" alt="90+ Commands">
  <img src="https://img.shields.io/badge/Wordlists-15-purple?style=flat-square" alt="15 Wordlists">
  <img src="https://img.shields.io/badge/License-Educational-red?style=flat-square" alt="Educational">
</p>

---

## ⚠️ Legal Disclaimer

> **All commands in this guide are for educational purposes and authorized penetration testing only.**
> Using these tools against systems without explicit written permission is a criminal offense in most jurisdictions. Always obtain proper authorization before testing.

---

## 📖 About This Guide

This repository is a curated, hands-on reference for modern **web fuzzing** and **content discovery**. Every tool page includes:

- **Installation** instructions
- **Basic usage** examples
- **Professional commands** ready to copy
- **Option reference tables**
- **Pro tips** and edge cases

> 💡 **Golden Rule:** The tool is not what matters — the **methodology**, the **right wordlist**, and **smart filtering** are. A mediocre fuzzer with a great wordlist beats 10 great fuzzers with bad wordlists.

---

## 🔗 The Professional Recon Pipeline

An 8-step end-to-end workflow for web application reconnaissance:

### Step 1 — Passive Subdomain Enumeration
Collect subdomains without touching the target.
```bash
subfinder -d target.com -all -silent | tee subs.txt
