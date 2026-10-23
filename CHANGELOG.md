# Changelog

All notable changes to this standalone edition of ui-ux-pro-max-skill are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus npm updates for `cli/`, `gallery/` and `stack/`, and pip updates for the ui-styling scripts under `.claude/skills/` and `cli/assets/` (upstream had no Dependabot config).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the docs and skill files; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's tests, release, smoke-stacks and catalog workflows were kept as-is.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) at upstream release v2.15.0 (snapshot commit `56ea9cf174ed86786187daa9de0e6247cb0747e4`, upstream HEAD dated 2026-10-15; `skill.json` in tree is version 2.15.0).
- Fork history severed; all files and the MIT licence (`LICENSE`) preserved as-is, including the `gallery/data/styles.csv` symlink and all binary assets (screenshots and canvas fonts).
