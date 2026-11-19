# Claude design skills

Skills for Claude that carry design work the same way every time: a product engagement from brief to handoff, and a brand from idea to a system other people can apply. Written by Mikel Rosenthal, a Chicago designer with 23 years in product, brand and design systems.

Every skill carries rules about what it must not do. Never invent a number. Never report a count you did not count. Say what you could not test. The refusals do more work than the procedures.

## What is here

| Plugin | Skills | For |
|---|---|---|
| `design-practice` | brief-intake, ds-inventory, heuristic-audit, research-synthesis, flow-map, copy-standards, a11y-spec, critique, handoff-spec | A product engagement, from a raw brief to the developer package |
| `brand-systems` | brand-identity, art-direction, ds-drift | A brand identity, the visual direction of a build, and a check that Figma and code tokens agree |

The design-practice plugin also holds a demo runbook, project instructions and seven example outputs. The examples are a composite project, not a client engagement, and their numbers are invented for illustration.

## Install

**Claude Code**, as a plugin marketplace:

```
/plugin marketplace add PitchBlacKnight/claude-design-skills
/plugin install design-practice@pbk-design-skills
/plugin install brand-systems@pbk-design-skills
```

On Claude Code 2.1.275 or later, one line per plugin also works: `/plugin install brand-systems --marketplace PitchBlacKnight/claude-design-skills`.

**Any setup that reads skill folders:** copy a folder from `plugins/*/skills/` into your skills directory, for example `~/.claude/skills/`. Each folder is one skill. Only the `description` line of each `SKILL.md` stays in context until a task matches.

**A Claude project:** add the skill folders to the project and paste `plugins/design-practice/PROJECT-INSTRUCTIONS.md` into the project instructions, so the house rules apply to everything.

## Anatomy of a skill

Every skill has the same parts in the same order, so a second person gets comparable output:

```
---
name: heuristic-audit
description: When to load it, in one line
---
# Title
## When to use
## Procedure
## Severity scale (or rubric)
## Rules
## Bundled files
```

## More

- The skill library, with a side-by-side example: https://mikelrosenthal.com/process/skill-library.html
- NorthStar, a design system with files written for AI agents: https://mikelrosenthal.com/northstar/
- Contact: mikelrosenthal@me.com

MIT licensed. Use them, change them, credit appreciated.
