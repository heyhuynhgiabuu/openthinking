# Skill Format

This repo uses a `skills.sh`-style structure.

The canonical install surface is the top-level `skills/` directory.
Each skill lives in its own folder and must contain a `SKILL.md` with YAML frontmatter.

## Required layout

```text
skills/
└── <skill>/
    ├── SKILL.md
    ├── examples.md
    └── eval.md
```

## `SKILL.md`

`SKILL.md` is the main artifact.
It must start with YAML frontmatter including at least:

- `name`
- `description`

OpenThinking also standardizes these optional fields:
- `version`
- `tags`
- `inputs`
- `outputs`
- `recommended_next_skills`

After the frontmatter, the body should define:
- what the skill does
- when to use it
- required inputs
- clarifying question policy
- output contract
- stop rules
- next recommended skills

## `examples.md`

Contains:
- example invocations
- example inputs
- expected output shapes
- anti-examples if needed

## `eval.md`

Contains:
- what good output must include
- failure modes
- regression prompts or test scenarios

## Minimal frontmatter example

```md
---
name: Idea Scorecard
description: Evaluate whether a solo-builder idea is worth pursuing now.
version: 0.1.0
tags: [idea-validation, solo-builder, decision]
inputs: [idea, builder_strengths, time_budget, target_customer_guess, business_model_guess]
outputs: [idea_scorecard, decision_recommendation, top_risks, key_assumptions]
recommended_next_skills: [icp-pain-map, wedge-positioning]
---
```

## Design rules

- one skill = one decision job
- do not combine multiple major decisions in one skill
- outputs must be structured and reusable
- avoid broad motivational language
- prefer clear judgment over endless options
- ask at most the minimum clarifying questions required

## Output principle

The unit of value is not a chat response.
The unit of value is a reusable decision artifact.

## Skill quality bar

A skill is not ready if:
- it produces generic advice
- it overlaps heavily with another skill
- it cannot define a clear output shape
- it is mostly philosophy instead of action
- it has no obvious repeatable use case
