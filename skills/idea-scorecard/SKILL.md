---
name: Idea Scorecard
description: Evaluate whether a solo-builder idea is worth pursuing now.
version: 0.1.0
tags: [idea-validation, solo-builder, decision]
inputs: [idea, builder_strengths, time_budget, target_customer_guess, business_model_guess]
outputs: [idea_scorecard, decision_recommendation, top_risks, key_assumptions]
recommended_next_skills: [icp-pain-map, wedge-positioning]
---

# Idea Scorecard

## Purpose

Use this skill to decide whether a business idea is worth pursuing now.

It should help a solo builder avoid spending months on an idea that is too broad, too weak, too crowded, or too mismatched with their strengths.

## When to use

Use when:
- you have a raw startup or SaaS idea
- you are considering switching projects
- you need a go / narrow / kill recommendation

Do not use when:
- the project is already live and needs weekly review
- pricing and GTM are already the main question

## Required inputs

- idea
- builder strengths
- available time budget
- target customer guess
- business model guess

If one or two inputs are missing, ask only the minimum clarifying questions.

## Output contract

Return these sections:

1. `Idea summary`
2. `Scorecard`
   - pain severity
   - urgency
   - adoption friction
   - founder-fit
   - distribution plausibility
   - monetization plausibility
   - defensibility
3. `Top risks`
4. `Assumptions to test`
5. `Recommendation`
   - proceed
   - narrow
   - kill
6. `Recommended next skill`

## Rules

- Be blunt.
- Do not flatter weak ideas.
- Prefer narrowing over vague encouragement.
- Call out “interesting but strategically weak” when needed.
- Make a recommendation even if the idea is incomplete.

## Stop rules

Stop once the idea has a clear proceed / narrow / kill recommendation with supporting reasons.
