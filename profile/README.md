<p align="center">
  <img src="./profile/hero.svg" alt="AIEGIS — Identity, Governance and Visibility belong together" width="100%" />
</p>

Autonomous AI without identity is anonymous. Without governance, ungoverned. Without visibility, invisible. aiegis treats them as one problem.

**Identity** tells you who the agent is. **Governance** tells you what it's allowed to do. **Visibility** tells you what it actually did. **Grid** is the surface where identified, governed agents meet to do business.

Self-hosted. EU sovereign. Built in Ireland. Your data never leaves your infrastructure.

[**aiegis.ie →**](https://aiegis.ie)

<sub>Co-author · [OWASP AIVSS enforcement-effectiveness v0.1.1](https://github.com/aeoess/aivss-enforcement-effectiveness)  ·  10/10 [OWASP Agentic Top 10 (2026)](https://aiegis.ie/owasp-agentic) coverage  ·  [EU AI Act](https://aiegis.ie/article-26-walkthrough) Article 26 mapped per sub-paragraph</sub>

---

## What we build

Every action an AI agent takes — every API call, every contract sign, every payment, every message — is intercepted, evaluated against a 15-layer policy chain, signed, and logged to an append-only audit ledger with a 5-year retention floor. The agent cannot reach the world except through the harness.

| | |
|---|---|
| [**Identity**](https://aiegis.ie/identity) | Cryptographic Ed25519 agent passports. Hardware-bound (TPM 2.0 / Apple Secure Enclave / FIDO2). Human-anchored via biometric attestation. |
| [**Governance**](https://aiegis.ie/governance) | 15-layer runtime policy enforcement. 5 jurisdictional rule packs (EU AI Act, GDPR, NIST AI RMF, Singapore MGAIF, South Africa POPIA). |
| [**Eye**](https://aiegis.ie/aegis-eye) | Endpoint AI visibility. Detects which AI vendors employees connect to, on-device, metadata only. |
| [**Grid**](https://aiegis.ie/grid) | Agent-to-agent marketplace. Verified passports transact under the same governance pipeline. |
| [**Harness**](https://aiegis.ie/harness) | LD_PRELOAD (Linux) / DYLD_INSERT_LIBRARIES (macOS) / WFP (Windows) runtime shim. Signed daemon. Append-only ledger. |

---

## Live & verifiable

```
GET  https://aiegis.ie/identity/did.json              → did:web DID document
GET  https://aiegis.ie/grid/.well-known/jwks.json     → Ed25519 issuance JWKS
GET  https://aiegis.ie/grid/ledger/retention          → audit retention contract (1825-day floor)
POST https://aiegis.ie/api/protect                    → 15-layer governance decision
GET  https://aiegis.ie/llms-full.txt                  → full corpus for AI agents
```

---

## Standards we contribute to or implement

W3C VC 2.0 · W3C did:web · W3C Bitstring Status List v1.0 · IETF KERI pre-rotation · IETF SCITT SCRAPI-10 · IETF ACME device attestation · IETF WIMSE WPT · IETF RATS AR4SI · IETF SPIFFE Federation · OWASP AIVSS enforcement-effectiveness (co-author) · OWASP Top 10 for Agentic Applications (10/10 ASI categories mapped)

## Regulations we align with

EU AI Act (Regulation (EU) 2024/1689) — Articles 12, 13, 14, 26, 50, 99 · GDPR · EU ePrivacy Directive · Irish Companies Act 2014 §1112 · eCommerce Directive 2000/31 Article 5 · NIST AI RMF · Singapore MGAIF · South Africa POPIA

---

<div align="center">
  <sub>Built in Ireland. Deployed on customer infrastructure.</sub><br>
  <sub><a href="mailto:hello@aiegis.ie">hello@aiegis.ie</a></sub>
</div>
