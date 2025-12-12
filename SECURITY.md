# Security Policy

## Supported Versions
This repo is a front-end + documentation hub. Security concerns still matter because:
- Links and UI patterns can be abused for phishing.
- Misleading copy can cause unsafe custody behavior.

Security reports are handled on a best-effort basis.

## Reporting a Vulnerability
**Do not open public issues for security vulnerabilities.**

Report privately:
- Email: **support@graduationvaults.com**
- Subject: **[SECURITY] Graduation-Vaults-HUB – <short summary>**

Include:
- What you found (clear description)
- Steps to reproduce
- Impact (what can go wrong)
- Evidence (screenshots/URLs) and minimal PoC if relevant

## What We Treat as Security Issues
- Phishing vectors (fake links, redirect abuse, lookalike UI)
- Dependency vulnerabilities that impact production builds
- Exposed secrets (API keys, tokens, credentials)
- XSS / injection / unsafe embedding patterns
- Any guidance that could lead users into unsafe custody behavior

## Response Timeline (Best Effort)
- Acknowledgement: **3–7 days**
- Triage + next steps: **7–14 days**
- Fix timeline depends on severity and scope

## Disclosure
If confirmed, we prefer responsible disclosure after a fix is deployed.
