# Security Policy

## Supported Version

This is **v0.1.3 Public Proof Boundary Release**.

Security hardening is still intentionally baseline-level.

## Reporting a Vulnerability

Please report security issues through the repository maintainer or GitHub security advisory flow when available.

Do not disclose vulnerabilities publicly before maintainers have a reasonable chance to review.

## Security Posture

This repository includes baseline checks for:

- required files
- common secret patterns
- synthetic data safety
- evidence card structure
- documentation quality
- release artifact generation

These checks support public discipline. They are not a substitute for full security review.

## Public Safety Standard

Public instances of this repository should not contain:

- real credentials or keys
- internal hostnames
- private infrastructure details
- personal data
- client data
- restricted or controlled information
- real incident details that are not already public-safe
- operational vulnerabilities
- proprietary or patent-sensitive technical details before review

Use synthetic, sanitized, or clearly public-safe examples.

## Production Use

For production use, add controls appropriate to the environment, such as:

- branch protection
- required reviews
- CodeQL or equivalent static analysis
- dependency review
- secret scanning
- signed commits or protected release workflows where appropriate
- environment-specific access controls
- audit logging
- legal, security, and compliance review

## AI-Assisted Security Notes

AI may help identify patterns, draft documentation, and check consistency.

AI must not be treated as the final security reviewer.

A human reviewer remains responsible for any security-sensitive release.

We are here now. Public discipline protects what must remain protected.
