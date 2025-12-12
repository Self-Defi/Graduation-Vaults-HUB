# Graduation-Vaults-HUB

<!-- Self-Defi Architecture Badges -->
[![Self-Defi](https://img.shields.io/badge/Self--Defi-Architecture-0f304d?style=flat&labelColor=111827&color=1f7a3a)](#)
[![Role](https://img.shields.io/badge/Role-Infrastructure-0f304d?style=flat&labelColor=111827&color=1f5fa8)](#)
[![Status](https://img.shields.io/badge/Status-Prototype--Phase-0f304d?style=flat&labelColor=111827&color=cc6b1f)](#)
[![Sovereignty](https://img.shields.io/badge/Sovereignty-First-0f304d?style=flat&labelColor=111827&color=111827)](#)

<!-- Governance & Policy -->
[![License: MIT](https://img.shields.io/badge/License-MIT-0f304d?style=flat&labelColor=111827&color=0f304d)](./LICENSE)
[![Security Policy](https://img.shields.io/badge/Security-Policy-0f304d?style=flat&labelColor=111827&color=0f304d)](./SECURITY.md)
[![Contributing](https://img.shields.io/badge/Contributing-Guide-0f304d?style=flat&labelColor=111827&color=0f304d)](./CONTRIBUTING.md)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-Active-0f304d?style=flat&labelColor=111827&color=0f304d)](./CODE_OF_CONDUCT.md)

---

## Overview

**Graduation Vaults** is a **non-custodial, time-locked donation infrastructure** designed for modern microschools and education-first communities.

This repository is the **public hub** for the Graduation Vaults system:
- Documentation
- Architecture explanations
- Onboarding resources
- Policy framing
- Front-end assets powering **GraduationVaults.com**

The system is built and deployed by **SD Advisory Group (Self-Defi)** using existing decentralized tools — not proprietary custody or closed platforms.

> **Self-Defi never holds keys, never signs transactions, and never touches donated funds.**

---

## What Graduation Vaults Are

Graduation Vaults are **student-specific, on-chain donation vaults** that:

- Are **created per student** (no pooled funds)
- Are governed by **multi-signature approval**
- Are protected by **hard time-locks**
- Unlock only at **graduation** (with rare, documented exceptions)
- Are **fully transparent on-chain**

Each vault is a **dedicated smart account**, not an investment product.

---

## Core Design Principles

### 1. Zero Custody
- SD Advisory Group does not custody assets
- Schools do not custody assets
- No centralized wallets or pooled accounts

### 2. Student-First Governance
- Every student vault requires a **Parent/Guardian signer**
- No unilateral withdrawals
- No early access without documented hardship and consensus

### 3. Transparency by Default
- On-chain balances
- On-chain transaction history
- Read-only dashboards for families and donors

### 4. Separation of Roles
No single party can control funds.

---

## Vault Architecture (Student Vaults)

Each Graduation Vault uses a **3-of-4 multi-signature structure**:

1. **Parent / Guardian** (mandatory signer)
2. **School Representative**
3. **Teacher / Counselor / Staff Member**
4. **Independent Trustee or Community Oversight**

Any withdrawal — including graduation unlock — requires:
- 3 approvals
- The Parent/Guardian must always be one of them

If consensus is not reached, funds remain locked.

---

## Time-Lock Enforcement

- Vaults are locked until the student’s graduation date
- Time-locks are enforced at the smart-contract level
- UI access does not bypass lock rules
- Emergency withdrawals are:
  - Rare
  - Documented
  - Subject to multi-party approval
  - Fully auditable on-chain

---

## School Innovation Vault (Optional)

In addition to individual student vaults, schools may deploy a:

**School Innovation Vault**
- 2-of-3 multi-signature governance
- Used for campus-wide initiatives, infrastructure, or programs
- Transparent and auditable
- Still zero custody for SD Advisory Group

This vault **does not replace** student vaults — it complements them.

---

## Who This System Is For

### Students & Families
- Protected graduation funds
- No speculation
- No investment accounts
- Read-only visibility throughout enrollment

### Schools & Microschools
- Donation infrastructure without custody risk
- Clear role separation
- Reduced compliance exposure
- No internal fund handling

### Donors & Sponsors
- Direct on-chain donations
- Verifiable delivery
- Transparent tracking
- Confidence funds cannot be misused

### Trustees & Community Members
- Neutral oversight
- No money handling
- Governance participation only

---

## What This Repo Contains

This repository powers **GraduationVaults.com** and acts as the canonical documentation hub.

Contents include:
- Static site source
- Architecture explanations
- Onboarding guides (students, parents, staff, trustees, donors)
- Whitepaper references
- Dashboard links
- Policy and governance documents

---

## Live Deployment

This repo is deployed via **GitHub Pages** to:

👉 https://graduationvaults.com

All content is static, auditable, and intentionally simple.

---

## Governance & Compliance Framing

Graduation Vaults are:
- **Donation-based**
- **Non-investment**
- **Non-yield-bearing by default**
- **Non-custodial**

SD Advisory Group provides **infrastructure architecture only**.

We do **not**:
- Take deposits
- Hold private keys
- Manage funds
- Offer financial products
- Promise returns

---

## Roadmap (High Level)

**Phase 1 — Infrastructure & Education (Current)**
- Hub site
- Whitepaper
- Onboarding materials
- Dashboard visibility

**Phase 2 — Expanded School Pilots**
- Additional microschool deployments
- Trustee onboarding refinement
- Governance playbooks

**Phase 3 — Enhanced Transparency**
- Improved dashboards
- Donation analytics
- Role-based views

**Phase 4 — Institutional Packaging**
- Policy bundles for legal review
- School network deployments
- Standardized onboarding kits

---

## Contributions

This project welcomes contributions that:
- Improve clarity and safety
- Strengthen governance language
- Enhance UX and accessibility
- Reduce user error
- Preserve sovereignty-first principles

See:
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`

---

## Contact & Identity

**Graduation Vaults**  
Powered by **Self-Defi / SD Advisory Group**

Digital Infrastructure Architect  
Consultation: https://cal.com/selfdeficonsultant/15min

> Unlock Tomorrow. Today.

