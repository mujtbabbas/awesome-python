# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/vinta/awesome-python>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, and credit. (README "Categories" is a
  project-category index, not a page contents list, so no Contents entry
  was added for the About section.)

- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus pip
  updates for the root pyproject.toml / uv dependency groups).

- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation for the guide; upstream ci.yml and
  deploy-website.yml workflows kept as-is).

- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).
- Licence discrepancy flagged, NOT changed: the LICENSE file in tree is
  CC BY 4.0, while pyproject.toml declares license = "MIT". Both are
  upstream's own texts and are preserved exactly as-is.

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of vinta/awesome-python at upstream commit
  4818b99562e663de4537fb0dae4b2ff6570e048e (upstream HEAD dated 2026-10-19).

- Fork history severed; all files and the licence file (LICENSE, CC BY 4.0
  text) preserved as-is.
