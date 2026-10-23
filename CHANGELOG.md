# Changelog

All notable changes to this standalone edition of awesome-python are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus pip updates for the root `pyproject.toml` / uv dependency groups.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the guide; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's `ci.yml` and `deploy-website.yml` workflows were kept as-is.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence discrepancy flagged, not changed: the `LICENSE` file in tree is CC BY 4.0, while `pyproject.toml` declares `license = "MIT"`. Both are upstream's own texts and are preserved exactly as-is.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [vinta/awesome-python](https://github.com/vinta/awesome-python) at upstream commit `4818b99562e663de4537fb0dae4b2ff6570e048e` (upstream HEAD dated 2026-10-19).
- Fork history severed; all files and the licence file (`LICENSE`, CC BY 4.0 text) preserved as-is.
