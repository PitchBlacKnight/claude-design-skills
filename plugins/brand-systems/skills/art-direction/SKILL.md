---
name: art-direction
description: Sets the visual direction before any page, site, landing page, portfolio, case study, poster or UI is built or restyled. Starts from one idea and real material, renders three genuinely different directions, and keeps style presets out of expressive work. Use for any new visual build or redesign.
argument-hint: "<what is being made> [brand or DESIGN.md path]"
---

# Art direction

Work that comes out generic usually has a list of bans, a borrowed style preset and gallery references, so it lands on the median of current websites. Work that holds up has an idea and real material. This skill makes the idea and the material come first.

## 1. Sort the brief
- **Whose brand,** and whether a `DESIGN.md` or token set exists.
- **Which mode.**
  - *Product mode:* design systems, dashboards, app UI, anything with an existing token set. Follow the system and keep personal taste out.
  - *Expressive mode:* portfolios, marketing sites, case study layouts, posters, campaigns with an open brief. Sections 2 to 5 are mandatory.

## 2. The idea before anything visual
Write two things at the top of the reply:
1. **The idea in one sentence.** What the thing *is*, as an object or a world, not a mood. "An archive that broadcasts" is an idea. "Dark, premium, editorial" is a mood.
2. **The raw material.** The real, specific stuff the design is built from: the client's photos, products, documents, history, the author's own work.

If the material is missing, ask one question to get it. A missing idea is yours to propose.

## 3. Type, color and form come from the idea
- A brand's `DESIGN.md` is the floor. Keep its tokens, then push composition, scale and motion as far as the idea allows.
- New expressive work picks type and color because of the idea, and says why in one line ("a condensed slab because it is a dispatch").
- No brand yet: write a `DESIGN.md` in under 30 lines after a direction is picked, not before.

## 4. References from outside web design first
- **At least two references from outside the web:** record sleeves, posters, books and magazines, film title sequences, signage, event cards, type specimens, packaging. Name the specific object and what to take (grid, type, texture, rhythm).
- **At most one web reference,** studied from real screenshots, used to set the craft bar, never the layout.
- **Remix:** structure from one source, surface from an unrelated one.

## 5. Three directions, rendered, genuinely different
Build each as a real first screen (hero plus the start of the next section), render it at 1440, and show the three side by side, in this order:
1. **The showpiece.** The most striking version of the idea: bold scale, real imagery, considered motion.
2. **The material one.** Built out of the raw material, where the material is the layout.
3. **The rule-breaker.** Breaks one house rule or one web convention on purpose. Name the rule and why breaking it serves the idea. Never break honesty: no invented facts or claims.

If two directions could swap logos with each other or with a stranger's site, redo one. The client picks; then build the chosen one fully. If all three are rejected, go back to the idea rather than tweaking surfaces.

## 6. Style presets: product mode, critique and polish only
Use a style preset or critique skill to tune a built UI, never to set the direction of expressive work. A system's own type and color tokens beat any preset's font or palette list.

## 7. Motion
Every motion has a job (cause and effect, keeping place, revealing structure), written down before the code. Respect `prefers-reduced-motion`. Anything that moves on its own gets a pause control.

## 8. Build, look, push
Render at 1440, 768 and 375 and look at it. Ask the stranger test: if the name were swapped, could this be someone else's site? If yes, find the most generic element (usually the hero type, the section rhythm or the card grid) and replace it with something only this idea would produce. Up to three passes.

## 9. Finish
1. Critique, then polish.
2. Accessibility: WCAG 2.2 AA contrast, visible focus, 24px targets, a full keyboard path.
3. States: empty, loading, error, partial, success, disabled, stressed with real content.
4. Log decisions in `DECISIONS.md`: the problem, options rejected and why, what was tested, what shipped.
