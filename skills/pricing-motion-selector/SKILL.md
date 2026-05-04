---
name: Pricing Motion Selector
description: "Choose the right pricing motion for a product: freemium, trial, paid pilot, or paid starter."
version: 0.1.0
tags: [pricing, monetization, saas]
inputs: [product_shape, support_burden, cost_to_serve, onboarding_complexity, buyer_type]
outputs: [pricing_motion, why_this_fits, why_others_fail, test_plan]
recommended_next_skills: [gtm-channel-picker, weekly-review-and-kill-check]
---

# Pricing Motion Selector

## Purpose

Use this skill to choose the right pricing motion for a product.

## When to use

Use when the product shape is clear enough to evaluate:
- self-serve vs sales-assisted
- free vs paid entry
- support burden and time-to-value

## Required inputs

- product shape
- support burden
- cost to serve
- onboarding complexity
- buyer type

## Output contract

Return these sections:

1. `Recommended pricing motion`
2. `Why it fits`
3. `Why the alternatives are weaker`
4. `Upgrade trigger`
5. `Pricing test plan`

## Rules

- make one primary recommendation
- do not default to freemium just because it sounds modern
- use economics and adoption shape as the deciding factors

## Stop rules

Stop when there is one clear pricing motion and a realistic first pricing test.
