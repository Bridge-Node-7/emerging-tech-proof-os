# Limitations (v0.1.2)

This is **v0.1.2 Foundation Skeleton**, not a complete production system.

## Known Limitations

- Workflows use baseline checks. They are not a replacement for full security, compliance, legal, or expert review.
- The documentation site is intentionally minimal.
- Release packaging creates workflow artifacts but does not create GitHub Releases automatically.
- Evidence card validation checks structure and required fields, but it cannot judge whether the evidence is true.
- Human review status must be verified before treating any artifact as validated.
- Synthetic data checks use pattern matching. They can miss sensitive data or produce false positives.
- No CODEOWNERS or advanced branch protection configuration is included yet.

These limitations are documented so users know what this template can and cannot do.

Do not treat this release as fully hardened for high-impact production use without additional review.
