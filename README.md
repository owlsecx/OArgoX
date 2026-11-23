# 🦉 OArgoX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OArgoX** — GitOps Controller Security Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OArgoX is an offline, read-only auditor for GitOps controller manifests, covering Argo CD and Flux CD. Using a stdlib YAML-subset parser it reviews argocd config maps and secrets, AppProjects and Applications, plus Flux sources, Kustomizations, HelmReleases, Providers and Receivers. Secrets are masked, findings are mapped to CWE and MITRE ATT&CK, and results roll up into a 0–100 score and A+…F grade.

---

## ✨ Features

- Audits Argo CD argocd-cm / rbac-cm / cmd-params-cm, secrets, AppProject and Application
- Audits Flux CD Git/Helm/OCI sources, Kustomization, HelmRelease, Provider and Receiver
- Flags unverified sources, risky sync policy and multi-tenancy lockdown gaps
- Secrets masked; CWE + MITRE ATT&CK mapping with remediation
- Hardened manifest templates for Argo CD and Flux
- Export TXT/MD/JSON/CSV/SARIF, self-test --demo and CI fail-on gates

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OArgoX ./manifests/
./OArgoX app.yaml --format sarif -o report.sarif --fail-on high
./OArgoX --demo
./OArgoX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*
