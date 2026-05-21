# Changelog

All notable changes to this repository are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project aims to follow
[Semantic Versioning](https://semver.org/).

This changelog tracks changes to the *repository*. For server news aimed at users, see the
**Announcements** page on the site.

## [Unreleased]

## [1.1.0] - 2026-05-21

### Added

- FAQ answers are now click-to-open collapsible sections (twisties).
- Projects page links to Ruthie, the dinner decider.

### Changed

- Updated the three radio station descriptions.

### Fixed

- `details` collapsibles rendered their inner markdown literally (e.g. visible
  backticks); they now render formatted content.

## [1.0.0] - 2026-05-21

### Changed

- Addressed a multi-persona UX evaluation of the guide: documented the Cloudflare
  Access first-login flow, corrected the radio station URLs and listed all three
  stations, fixed the Jellyfin login-screen description, clarified that Music uses
  the standard Farmhouse login, added Retro Gaming save-state guidance, and named
  each service's underlying software.

## [0.10.0] - 2026-05-21

### Added

- `README.md`, `CONTRIBUTING.md`, `SECURITY.md`, and this changelog.
- `.github/` issue templates and a pull request template.
- A GitHub Actions workflow that build-checks the site on every pull request.
- `.editorconfig` for consistent formatting.
- A **Projects** page (scaffolded) linking to other projects users might enjoy.

## [0.9.0] - 2026-05-10

### Added

- Rebuilt the user guide on the [hugo-book](https://github.com/alex-shpak/hugo-book) theme.
- Applied the Farmhouse design system — custom colors, typography, and spacing.
- Promoted Announcements to top-level navigation.

### Changed

- Refined the landing page layout and spacing.

[Unreleased]: https://github.com/coreytyhurst/userguide/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/coreytyhurst/userguide/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/coreytyhurst/userguide/compare/v0.10.0...v1.0.0
[0.10.0]: https://github.com/coreytyhurst/userguide/compare/v0.9.0...v0.10.0
[0.9.0]: https://github.com/coreytyhurst/userguide/releases/tag/v0.9.0
