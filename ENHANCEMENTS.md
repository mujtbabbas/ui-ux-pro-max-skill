# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/nextlevelbuilder/ui-ux-pro-max-skill>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, and credit.

- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus npm
  updates for cli/, gallery/ and stack/, and pip updates for the ui-styling
  scripts under .claude/skills/ and cli/assets/; upstream had no Dependabot
  config).

- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation for the docs and skill files; upstream
  tests, release, smoke-stacks and catalog workflows kept as-is).

- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of nextlevelbuilder/ui-ux-pro-max-skill at
  upstream release v2.15.0 (snapshot commit
  56ea9cf174ed86786187daa9de0e6247cb0747e4, upstream HEAD dated 2026-10-15;
  skill.json in tree is version 2.15.0).

- Fork history severed; all files and the MIT licence (LICENSE) preserved
  as-is, including the gallery/data/styles.csv symlink and all binary
  assets (screenshots and canvas fonts).
