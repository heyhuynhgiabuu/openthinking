---
name: MVP Scope Cutter
description: Cut a product down to the smallest real MVP worth building.
version: 0.1.0
tags: [mvp, scope, execution]
inputs: [wedge_statement, desired_features, time_target, constraints]
outputs: [must_have_flow, defer_list, non_goals, build_cut]
recommended_next_skills: [pricing-motion-selector, gtm-channel-picker]
---

# MVP Scope Cutter

## Purpose

Use this skill to remove fake platform ambition and identify the smallest product worth building.

## When to use

Use after wedge and positioning are clear enough to define a first version.

## Required inputs

- wedge statement
- desired features
- time target
- constraints

## Output contract

Return these sections:

1. `Must-have flow`
2. `Must-have features`
3. `Defer list`
4. `Non-goals`
5. `2-week or 4-week build cut`
6. `Recommended next skill`

## Rules

- cut aggressively
- prefer one complete flow over many partial features
- call out platform creep explicitly
- do not preserve features just because they sound impressive

## Stop rules

Stop when there is a buildable MVP with clear non-goals.
