# 🦉 OArgoX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OArgoX** — GitOps Controller Security Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Offline Argo CD / Flux CD GitOps controller manifest security auditor

---

## ✨ Features

- Stdlib YAML-subset parser — multi-document streams, maps / lists, flow collections, block scalars, lines
- Argo CD — argocd-cm, argocd-rbac-cm, argocd-cmd-params-cm, argocd-secret, repo / cluster Secrets, AppProject, Application
- Flux CD — Git/Helm/OCI sources, Kustomization, HelmRelease, Provider, Receiver, controller multi-tenancy lockdown flags
- Secrets masked; CWE + MITRE ATT&CK; score + grade A+..F
- Export TXT / MD / JSON / CSV / SARIF; --demo; --fail-on

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OArgoX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
