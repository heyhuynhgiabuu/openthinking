---
name: ICP Pain Map
description: Turn a vague audience into one concrete user and urgent pain statement.
version: 0.1.0
tags: [icp, positioning, customer]
inputs: [idea_brief, market_guess, known_user_examples]
outputs: [primary_icp, urgent_pain, current_workaround, rejected_icps]
recommended_next_skills: [wedge-positioning, mvp-scope-cutter]
---

# ICP Pain Map

## Purpose

Use this skill to turn a fuzzy market into one concrete ideal customer profile and one urgent problem worth solving.

## When to use

Use when:
- the idea sounds like it could be for many people
- you need to narrow the first customer
- the pain statement is still vague

## Required inputs

- idea brief
- market guess
- known user examples or anecdotes if available

## Output contract

Return these sections:

1. `Primary ICP`
2. `Urgent pain`
3. `Current workaround`
4. `Why now`
5. `Rejected ICPs`
6. `Recommended next skill`

## Rules

- Pick one main ICP, not a list of five.
- Reject broad markets aggressively.
- Focus on painful repeated work, not abstract interest.
- If the idea has no sharp ICP, say so.

## Stop rules

Stop once there is one primary ICP and one pain statement sharp enough to guide positioning.
