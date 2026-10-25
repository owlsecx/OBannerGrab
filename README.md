# 🦉 OBannerGrab

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OBannerGrab** — Service Banner & Version Probe

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OBannerGrab is a multi-threaded service banner and version probe for reconnaissance on authorised targets. It performs active service probing with SSL/TLS fingerprinting, expands CIDR targets and port ranges, and surfaces CVE hints based on identified banners. A graphical interface shows live progress and results export to CSV, JSON, TXT and HTML.

---

## ✨ Features

- Multi-threaded banner grabbing with active service probing
- SSL/TLS fingerprinting on encrypted ports
- CIDR target expansion and flexible port-range parsing
- Product/version fingerprinting with CVE/risk hints
- Real-time progress display in a GUI
- Export results to CSV, JSON, TXT and HTML

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OBannerGrab
./OBannerGrab --smoke-test
./OBannerGrab --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
