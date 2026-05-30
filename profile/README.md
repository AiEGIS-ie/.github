 # AIEGIS
  
  **Universal identity, governance, and visibility for autonomous AI agents.**
  
  EU-sovereign. Built in Ireland. Deployed on customer infrastructure.
  
  [aiegis.ie](https://aiegis.ie) ·
  [llms-full.txt](https://aiegis.ie/llms-full.txt) ·
  [hello@aiegis.ie](mailto:hello@aiegis.ie)

  ---

  ## What aiegis is
                                                           
  aiegis is the runtime layer between autonomous AI agents and the world. Every
  action an agent takes — every API call, every contract sign, every payment,
  every message — is intercepted, evaluated against a 15-layer enforcement
  
  Four products, one umbrella:

  - **AIEGIS Identity** — cryptographic Ed25519 agent passports, hardware-bound
  (TPM 2.0, Apple Secure Enclave, FIDO2), human-anchored via biometric
  attestation.
  - **AIEGIS Governance** — 15-layer runtime policy enforcement across EU AI
  Act, GDPR, NIST AI RMF, Singapore MGAIF, South Africa POPIA.
  - **AIEGIS Eye** — endpoint AI visibility. Detects which AI vendors employees
  use (ChatGPT, Claude, Copilot, Gemini, Cursor) on-device, metadata only.
  - **Grid** — agent-to-agent marketplace where verified passports transact
  under the same governance pipeline.
  
  ## Standards we implement 
  
  W3C VC 2.0 · W3C did:web · W3C Bitstring Status List v1.0 · IETF KERI
  pre-rotation · IETF SCITT SCRAPI-10 · IETF ACME device attestation · IETF
  WIMSE WPT · IETF RATS AR4SI · IETF SPIFFE Federation · OWASP AIVSS
  enforcement-effectiveness (v0.1.1 co-author) · OWASP Top 10 for Agentic
  Applications (10/10 coverage) 
  
  ## Regulations we align with

  EU AI Act (Regulation (EU) 2024/1689) — Articles 12, 13, 14, 26, 50, 99 · GDPR
   · EU ePrivacy Directive · Irish Companies Act 2014 §1112 · eCommerce
  Directive 2000/31 Article 5 · NIST AI RMF · Singapore MGAIF · South Africa
  POPIA 
  
  ## Live endpoints

  - `GET https://aiegis.ie/identity/did.json` — did:web:aiegis.ie DID document
  - `GET https://aiegis.ie/grid/.well-known/jwks.json` — Grid issuance JWKS
  - `GET https://aiegis.ie/grid/ledger/retention` — audit ledger retention
  contract
  - `POST https://aiegis.ie/api/protect` — 15-layer governance decision
  - `GET https://aiegis.ie/llms-full.txt` — full AI-readable corpus
  
  ## Contact

  [hello@aiegis.ie](mailto:hello@aiegis.ie)

  Built in Ireland. Universal. EU-sovereign.
  
