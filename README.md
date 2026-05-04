# OpenThinking

**OpenThinking** is a narrow skill library for solo builders.

It helps a builder decide:
- whether an idea is worth pursuing
- who it is really for
- what the wedge should be
- what to cut from the MVP
- how to price it
- which GTM channel to start with
- when to keep going or kill the project

This repo is not a founder second brain, not a prompt marketplace, and not a vague AI copilot.
It is a small set of installable decision skills.

## Core rule

> Build something narrow, simple, self-evidently useful, and easy to adopt — then find a real distribution loop.

That rule is the filter for every skill in this repo.

## Why this exists

Solo builders do not usually fail because they cannot generate ideas.
They fail because they:
- pick weak ideas
- target everyone
- build too much
- price badly
- chase too many channels
- keep going long after the evidence is weak

OpenThinking is meant to push against that.

## Install

After this repo is pushed to GitHub:

```bash
npx skills add <owner>/openthinking --list
npx skills add <owner>/openthinking --skill idea-scorecard
```

Local development:

```bash
npx skills add . --list
npx skills add . --skill idea-scorecard
```

## Skills

### Core
- `idea-scorecard` — decide whether an idea is worth pursuing now
- `icp-pain-map` — narrow a vague market into one concrete user and pain
- `wedge-positioning` — pick one narrow entry point and promise
- `mvp-scope-cutter` — cut a product down to the smallest real MVP

### Pricing
- `pricing-motion-selector` — choose freemium, trial, paid starter, or paid pilot

### Growth
- `gtm-channel-picker` — choose one real distribution channel to start with

### Review
- `weekly-review-and-kill-check` — review progress and decide whether to continue, revise, or kill

## What good use looks like

A good usage chain is:

1. run `idea-scorecard`
2. run `icp-pain-map`
3. run `wedge-positioning`
4. run `mvp-scope-cutter`
5. run `pricing-motion-selector`
6. run `gtm-channel-picker`
7. use `weekly-review-and-kill-check` every week after launch

Worked example:
- `examples/solo-builder-decision-flow.md`

## Repo layout

```text
openthinking/
├── skills/      # canonical install surface for skills.sh-compatible tools
├── docs/        # product principles, format docs, publish checklist
├── examples/    # worked examples and end-to-end flows
└── packages/    # internal/source grouping, not required for installation
```

## Publish checklist

Before publishing publicly, use:
- `docs/publish-checklist.md`

## Doctrine docs

These are source material for the initial skills:
- `PLAYBOOK_2026_SAAS.md`
- `GTM_FRAMEWORK.md`
- `PRICING_DECISION_TREE.md`
- `docs/product-principles.md`
- `docs/skill-format.md`

## Non-goals

Do not turn this repo into:
- a founder operating system
- a journaling app
- a generic startup advice dump
- a broad “build your startup with AI” platform
- a 30-skill catalog full of overlap

## Current status

The top-level `skills/` directory is already discoverable by the `skills` CLI.
The repo currently has 7 installable skills and worked examples for the full early decision chain.
