---
name: ds-drift
description: Read-only check that a design system's Figma variables and its code tokens still agree. Reports added, missing and changed values; changes nothing. Use for drift, tokens out of sync, checking Figma against code, or before a design system release.
argument-hint: "<system name> [figma file key] [token file path]"
---

# Design system drift check

Read only. Never write to Figma or the token files in this skill.

1. **Resolve the system.** Get the Figma file key and the code folder. Read the system's `design-rules.md` if present.
2. **Read Figma.** With the Figma MCP server, read every variable collection with its modes: name, type, value per mode, alias target.
3. **Read code.** Find the token source (CSS custom properties, JSON token files or a Figma variables export). Normalize names: `color/brand/primary` and `--color-brand-primary` are the same token.
4. **Diff.** Four lists: only in Figma, only in code, value differs (show both values per mode), alias differs. Ignore formatting differences (`#FFF` vs `#ffffff`, `16px` vs `1rem` at a 16px root).
5. **Report.** A short table per list, counts first. Flag raw hex or px in components where a token exists. Propose a name for any new value as a named token. Apply nothing; changes happen only after the owner picks them.

## Rules
- Never report a count you did not count.
- Say what could not be read (a collection without access, a mode with no values).
