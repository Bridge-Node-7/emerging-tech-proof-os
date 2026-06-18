# Start Here

Emerging Tech Proof OS is a public-safe repository template for evidence-based emerging technology work.

It helps people and AI agents organize claims, sources, confidence, limitations, review, and release decisions without guessing what the repository is for.

## What This Is

A foundation skeleton for:

- evidence cards
- governance checks
- AI-assisted content review
- baseline repository quality checks
- release discipline
- public/private boundary protection

## What This Is Not

It is not:

- a standalone app
- a software package to install
- a complete production system
- a private engine
- a substitute for expert review
- a source of truth without validation
- a place to publish proprietary, restricted, or sensitive content

## Quick Start

1. Read `MISSION.md`.
2. Read `DOCTRINE.md`.
3. Read `IP_BOUNDARY.md`.
4. Use `templates/evidence-card.md` for claims.
5. Use `templates/ai-governance-gate.md` for AI-assisted content.
6. Use `templates/decision-ready-brief.md` when a decision needs a clear summary.
7. Save completed evidence cards to `docs/evidence-cards/`.
8. Save completed decision-ready briefs to `docs/briefs/`.
9. Save completed governance gates or review notes to `docs/governance/`.
10. Let the GitHub Actions checks run.
11. Review and validate before publishing.

## Which Template Do I Use?

| Template | Use it when |
|---|---|
| `templates/evidence-card.md` | A claim may influence a decision, public release, roadmap, recommendation, or funding conversation. |
| `templates/ai-governance-gate.md` | AI drafted, summarized, classified, scored, or organized meaningful content. |
| `templates/decision-ready-brief.md` | A decision needs a structured summary with evidence, risks, confidence, and next steps. |

## Public-Safe Rule

Before adding content, ask:

1. Is this public-safe?
2. Is this synthetic, sanitized, or already public?
3. Could this expose proprietary work, client context, strategy, credentials, infrastructure, or restricted information?
4. Would this create an unsupported public claim?
5. Does this need private handling first?

If uncertain, keep it private and review before release.

## Agent Instructions

If you are an AI agent using this repository:

- Do not invent evidence.
- Do not treat claims as validated unless the evidence card says they are validated.
- Keep observed facts separate from analysis or inference.
- Preserve confidence levels, limitations, and validation requirements.
- Do not add sensitive data, credentials, internal hostnames, personal data, controlled information, or proprietary details.
- Label AI-assisted content and complete the AI governance gate when meaningful.
- Prefer small, clear edits over broad rewrites.
- Preserve the public discipline boundary.
- Flag anything that may require human, legal, security, or expert review.

## Human Review Rule

Automation checks structure and safety patterns.

Humans decide whether evidence is strong enough for use.

A sample is not validation.  
A checklist is not truth.  
A release note is not proof.

## Release Rule

Before calling a release validated:

- evidence cards must be complete
- governance checks must be complete
- human review must be documented
- limitations must be visible
- release artifacts must match the current files

If those conditions are not met, call it a foundation, sample, draft, or review-ready release.

We are here now. Evidence over hype. Human judgment is final.
