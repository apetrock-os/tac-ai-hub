# TAC AI Hub
### Project Brief — Internal

A central home for internal AI tools built by the team — with lightweight governance to keep things visible, secure, and sustainable as we build.

---

| | |
|---|---|
| **Owner** | Alexia Petrakos |
| **Status** | In development |
| **Target** | Wednesday review |
| **Stack** | Google Workspace + HubSpot |

---

## Purpose

Three team members have independently built working AI tools to solve real problems. That's a sign of a healthy, curious team. This hub gives those tools a home — and sets the foundation for more to be built safely as AI becomes part of how we work.

The goal is not bureaucracy. It's visibility, accountability, and a culture where building is encouraged and trustworthy.

---

## Current Tool Registry

| Tool | Description | Builder | Status |
|---|---|---|---|
| Employee Recognition | Peer recognition and appreciation tool for the team. | Alexia | Live |
| Learning Hub (LMS) | Internal learning management system for team training and resources. | Eleni | Live |
| Gym Route Builder | Optimized daily route planning for sales reps visiting gym accounts. | Ryan | Live |

---

## Governance Rules

**01 — Domain-locked authentication**
Any tool using Google Workspace or HubSpot login must restrict access to @theabscompany.com accounts only. No personal accounts, no open access.

**02 — HubSpot permissions respected**
Tools built on HubSpot cannot exceed the builder's own permission level. No tool should access, read, or write data beyond what the builder is authorized to do manually.

**03 — No hardcoded credentials**
API keys, tokens, and passwords must never be written into source code. Use environment variables. This applies to every tool regardless of how simple it seems.

**04 — No unauthorized data egress**
Company data must not be sent to third-party APIs or external services without explicit sign-off. When in doubt, ask before connecting.

**05 — Public URLs get logged here**
If a tool is deployed and accessible via a public URL (e.g. Vercel), it must be listed on this page. No dark deployments. Visibility is the accountability mechanism.

---

## Operating Principles

**Build freely**
No approval required to start building. Experimentation is encouraged at every level.

**Deploy visibly**
If it's live and in use, it lives on this page. That's the only process.

**Access responsibly**
Company data and systems require the same care in code as in any other context.

---

## Next Phase

Governance framework to be reviewed and refined with Chris Carolan's team. Future tools will be onboarded through this hub with consistent auth patterns, versioning standards, and documentation.
