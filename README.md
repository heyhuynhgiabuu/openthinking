# OpenThinking

**OpenThinking** is a small skill library for solo builders who need better product decisions.

It helps answer:
- is this idea worth pursuing?
- who is it really for?
- what should the wedge be?
- what should I cut from the MVP?
- how should I price it?
- which GTM channel should I start with?
- when should I keep going, revise, or kill the project?

This repo is **not**:
- a founder OS
- a second-brain app
- a prompt marketplace
- a vague AI copilot for everything

It is a narrow set of installable decision skills.

## Core rule

> Build something narrow, simple, self-evidently useful, and easy to adopt — then find a real distribution loop.

That rule is the scope filter for every skill in this repo.

## Why this exists

Solo builders usually do not fail because they lack ideas.
They fail because they:
- pick weak ideas
- target everyone
- build too much
- price badly
- chase too many channels
- keep going after the evidence gets weak

OpenThinking is designed to push against that.

## Install

From GitHub:

```bash
npx skills add heyhuynhgiabuu/openthinking --list
npx skills add heyhuynhgiabuu/openthinking --skill idea-scorecard
```

Local development:

```bash
npx skills add . --list
npx skills add . --skill idea-scorecard
```

## Start here

If you are trying OpenThinking for the first time, use this flow:

1. `idea-scorecard`
2. `icp-pain-map`
3. `wedge-positioning`
4. `mvp-scope-cutter`
5. `pricing-motion-selector`
6. `gtm-channel-picker`
7. `weekly-review-and-kill-check` every week once the project is live

Worked example:
- `examples/solo-builder-decision-flow.md`

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

## What makes a good skill here

Each skill should:
- solve one specific decision problem
- ask only the missing questions
- produce a reusable artifact
- recommend the next skill when appropriate
- stay narrow enough to be reliably useful

## Repo layout

```text
openthinking/
├── skills/      # canonical install surface for skills.sh-compatible tools
├── docs/        # product principles, format docs, publish checklist
├── examples/    # worked examples and end-to-end flows
└── packages/    # internal/source grouping, not required for installation
```

## Important docs

- `docs/product-principles.md`
- `docs/skill-format.md`
- `docs/publish-checklist.md`
- `docs/github-launch-notes.md`

## Non-goals

Do not turn this repo into:
- a founder operating system
- a journaling app
- a generic startup advice dump
- a broad “build your startup with AI” platform
- a 30-skill catalog with overlapping advice

## Current status

- top-level `skills/` directory is discoverable by the `skills` CLI
- 7 installable skills are included
- worked examples exist for the full early decision chain

## License

MIT
