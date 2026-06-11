# Emerging Tech Proof OS

**Repository template for transforming emerging technology claims into evidence cards, governance checks, and validated releases.**

Emerging Tech Proof OS is a GitHub repository template for evidence-based emerging technology work. It gives a project a clear structure for claims, sources, confidence levels, AI-assisted review, human validation, workflow checks, and release artifacts.

This is not an app to install. It is a repository template you can copy, fork, or adapt.

Start with [`START_HERE.md`](START_HERE.md). It explains the intended workflow for people and AI agents.

## What It Does

It helps a project show that its work is:

1. **Useful**: The mission, use cases, and decision context are clear.
2. **Governed**: Claims are tied to sources, confidence levels, limitations, and review status.
3. **Improving**: Changes are checked, versioned, and released in a repeatable way.

## How People Use It

1. Copy or fork the repository.
2. Add evidence cards for important claims.
3. Use governance gates for AI-assisted or high-impact content.
4. Use decision-ready briefs when a decision needs a structured summary.
5. Run the GitHub Actions checks.
6. Review changes before merging.
7. Publish releases and documentation.

## What Is GitHub-Specific

The templates, doctrine, and evidence model can be used anywhere.

The automation is GitHub-specific because it uses GitHub Actions, GitHub Pages, and GitHub release workflows.

## Core Workflow

```text
Claim
  ↓
Evidence card
  ↓
Governance check
  ↓
Human review
  ↓
Validated release
```

## Main Folders

```text
.github/workflows/       GitHub Actions checks
docs/evidence-cards/     Completed evidence cards
docs/briefs/             Completed decision-ready briefs
docs/governance/         Completed governance gates or review notes
docs/playbooks/          Process guides and repeatable workflows
docs/radar/              Scans, watchlists, and monitoring notes
data/schemas/            Data schemas for structured artifacts
data/synthetic/          Synthetic or sanitized data only
examples/                Public-safe examples
scripts/                 Helper scripts
templates/               Reusable templates
```

## Included Templates

- `templates/evidence-card.md`
- `templates/decision-ready-brief.md`
- `templates/ai-governance-gate.md`

## Included Workflow Checks

- Repo health check
- Documentation check
- Evidence card check
- Synthetic data safety check
- Basic security check
- Release package workflow
- GitHub Pages deployment workflow

## Operating Principles

- Evidence over hype.
- Human judgment remains final.
- AI output must be labeled, reviewed, and validated.
- Public examples must use synthetic, sanitized, or public-safe information.
- Releases should make changes, limitations, and validation status clear.

A release should be called validated only when the relevant evidence cards and review records show completed human review.

## Status

v0.1.2 Foundation Skeleton.

This release is intentionally minimal. It is suitable as a starting point, not a fully hardened production system.
