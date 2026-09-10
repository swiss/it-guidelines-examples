# IT Guidelines Examples

This repository contains **reference implementations and guidelines** for IT solutions operated on **BIT (Bundesamt für Informatik und Telekommunikation)** platforms.

## Contents

| Directory | Content |
|-----------|---------|
| `helm-charts/` | [Reference Helm charts](helm-charts/README.md) — structure, security, observability, and governance standards for BIT-operated workloads. |

## Purpose

These artifacts are **reference implementations** — not ready-to-deploy artefacts. Teams must:

1. **Adapt** to their workload requirements.
2. **Validate** via BIT CI/CD gates (lint, policy checks, security scans).
3. **Comply** with BIT IT Standards (internal) and platform policies.

## Governance

All artefacts deployed on BIT platforms must pass the **BIT DevSecOps Pipeline Gates** (SAST, SCA, container scan, policy checks).

---

**Maintained by:** BIT Platform Services  
**Reference:** BIT IT Standards & Guidelines (internal)