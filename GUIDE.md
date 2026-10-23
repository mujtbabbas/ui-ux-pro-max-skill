# Reader's Guide — ui-ux-pro-max-skill

## What this project is

**UI UX Pro Max** is an **Agent Skill that gives AI coding assistants design
intelligence**: a searchable knowledge base of UI styles, colour palettes,
font pairings, chart choices, UX rules and stack-specific guidance that the
agent queries while it builds, so generated interfaces come out designed
rather than defaulted. The README's badges summarise the scale: **192
reasoning rules** and **79 searchable UI styles**, driven by Python search
scripts.

## How the content is organised

- `src/ui-ux-pro-max/` — the skill source:
  - `data/` — the design knowledge base (styles, palettes, typography, UX
    rules, charts, per-stack guidance) that the search scripts query.
  - `scripts/` — the search/design-system engine (BM25-style lookups and the
    design-system generator).
  - `templates/` — templates used when installing the skill into a project.
- `skill.json` — the skill manifest (name, version, entry points).
- `cli/` — the **ui-ux-pro-max-cli** npm package: the installer users run to
  drop the skill into their agent setup (with its own `src/`, `tests/` and
  assets).
- [`README.md`](README.md) — the manual: **What's New in v2.0**, **Features**,
  **Basic vs. Premium Version Comparison**, **Installation**,
  **Prerequisites**, **Usage**, **Examples**, the advanced **Design System
  Command**, **Architecture & Contributing**, **Troubleshooting**, and
  **Compatible Agents**. Translations sit beside it: `README.id.md`,
  `README.ko.md`, `README.vi.md`, `README.zh.md`.
- Showcase material: `gallery/`, `preview/`, `projects/`, `screenshots/` —
  generated designs demonstrating the skill's output; `docs/` — further
  documentation; `stack/` — a bundled example project showing the skill in a
  full repo layout; `.claude/`/`.claude-plugin/` — Claude packaging.

## How to use it

1. Install via the **Installation** section (the npm CLI route is the
   standard one) for your agent — see **Compatible Agents**.
2. Ask your agent for UI work; the skill makes it search `data/` first
   (styles, palettes, rules) and build to the result.
3. For a whole design system in one go, use the **Design System Command**
   from the README.

## About this standalone edition

This repository is a standalone edition of
[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors; licence MIT (see `LICENSE`).
