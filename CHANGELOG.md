# Changelog

All notable changes to Emerging Tech Proof OS are documented here.

## [v0.1.2] - 2026-06-10

### Changed
- Updated public positioning to describe the project as a GitHub repository template.
- Simplified language for universal use by people, teams, and AI agents.
- Clarified that the repository is not an installable app or complete production system.
- Improved documentation so folder purpose and template relationships are clearer.
- Added clearer README guidance on when a release should be called validated.

### Fixed
- Added placeholder documentation to scaffold directories so they survive clone and template use.
- Replaced the no-op documentation check with an internal markdown link and structure check.
- Expanded baseline security scanning across more file types and patterns.
- Strengthened evidence card validation for required fields and placeholder values.
- Standardized evidence card field names between the template and sample.
- Made release artifact summaries dynamic instead of claiming validation by default.
- Changed the artifact manifest to valid CSV format.
- Improved GitHub Pages navigation.

### Added
- Public example evidence card.
- Agent-oriented instructions in `START_HERE.md`.
- `.gitattributes` for consistent text line endings across operating systems.
- Issue templates for evidence requests and workflow improvements.
- Pull request template for review discipline.

## [v0.1.1] - 2026-06-10

### Added
- START_HERE.md, MISSION.md, USE_CASES.md, LIMITATIONS.md, SECURITY.md, CONTRIBUTING.md
- LICENSE (MIT)
- VERSION file
- docs/index.md
- Explicit least-privilege permissions on workflows
- Evidence card validation scoped to `docs/evidence-cards/**`

### Changed
- Renamed security-check.yml to basic-security-check.yml for accuracy.
- Improved repo-health.yml required files list.

### Fixed
- Evidence card validation no longer fails on non-evidence-card templates.
- GitHub Pages no longer deploys an empty site.

## [v0.1.0] - 2026-06-10

Initial foundation skeleton release with core doctrine, templates, and baseline workflows.

## Link Notes

Version links are intentionally not hardcoded in this template. After copying the template into a repository, add compare or release links that point to that repository's actual location.
