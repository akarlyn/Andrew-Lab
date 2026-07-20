---
id: andrew-lab-repository-rules
title: Andrew Lab Repository Rules
type: governance
status: canonical
confidence: high
owner: Andrew S. Karlyn
created: 2026-07-20
updated: 2026-07-20
version: 0.1.0
---

# Andrew Lab Repository Rules

## 1. Public by design

Assume every committed file will be indexed, copied, quoted, and retained publicly. Deletion from GitHub does not guarantee removal from forks, caches, or Git history.

## 2. No private-source ingestion

Do not upload raw exports from ChatGPT, Claude, Gemini, Gmail, Notion, Google Drive, calendars, contacts, or private repositories.

## 3. No confidential context

Do not include client names, private opportunity details, proposal language, internal pricing, relationship notes, nonpublic organizational information, or unpublished personal career strategy unless intentionally cleared for release.

## 4. No secrets

Never commit passwords, API keys, tokens, cookies, private keys, certificates, environment files, or authentication screenshots.

## 5. Public-release review

Any asset originating in Andrew OS or Kindora OS must pass `governance/PUBLIC_RELEASE_CHECKLIST.md` before entering this repository.

## 6. Synthetic or open data only

Use synthetic, anonymized, or properly licensed open data. Do not rely on informal de-identification where re-identification remains plausible.

## 7. Attribution and licensing

Identify third-party sources, licenses, and material dependencies. Do not publish copied proprietary text or assets without permission.

## 8. Experiment discipline

Each experiment should state:

- question or hypothesis;
- inputs and source classification;
- method;
- expected output;
- evaluation criteria;
- risks;
- disposition decision.

## 9. Lifecycle states

Use:

- `draft`
- `active`
- `review`
- `validated`
- `published`
- `archived`
- `deprecated`

## 10. Graduation does not imply synchronization

Andrew Lab is not a mirror of Andrew OS or Kindora OS. Transfer only reviewed assets, and preserve the destination repository's own provenance and governance controls.

## 11. AI-generated content

AI-generated material starts as `draft`. It must be checked for accuracy, confidentiality, licensing, embedded personal information, and fabricated citations before release.

## 12. Stage gates

Do not treat Stage 0 scaffolding as approval to populate later stages automatically. Each stage requires explicit review and approval.
