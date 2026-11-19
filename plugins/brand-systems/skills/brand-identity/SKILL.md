---
name: brand-identity
description: Build or rework a brand identity system - idea, mark, type and color system, voice, applications and a guidelines page. Use when asked for a brand, identity, logo, mark, brand system, guidelines, style guide or rebrand. Not for building a website; hand the finished system to art-direction for that.
argument-hint: "<brand or client> [what exists already]"
---

# Brand identity

A brand is a system people apply without the designer in the room. The output is that system, rendered and documented, not a single logo.

## 1. Idea and material
- The idea in one sentence: what the brand is as a thing or a world, not a mood. "A field guide that never goes out of print" is an idea. "Bold, modern, trustworthy" is a mood and does not count.
- The raw material: the client's history, product, place, people, documents and photos. Ask for it if it is missing. Do not build from a mood board alone.
- Audience, and the three places the brand will live most (signage, app icon, social, packaging, deck, site).
- If an identity exists, audit it first: what to keep (equity) and what to drop. A rework is not a restart.

## 2. References from outside the web
At least two: type specimens, packaging, signage and wayfinding, record sleeves, book covers, corporate identity manuals (Vignelli, Gerstner, Otl Aicher, Wim Crouwel), film titles. Name the object and what to take from it. At most one web reference.

## 3. Three directions, rendered
Showpiece first, then material, then rule-breaker (see art-direction, section 5). Show each as a sheet: mark or wordmark, type pair, palette, one application. They must differ in idea, not color. Render each as HTML at 1440 and show them side by side. The client picks. This is the one planned stop.

## 4. Build the chosen system
- **Mark:** SVG, built on a grid; primary, secondary and small-size versions; clear space and minimum size measured, not guessed.
- **Type:** primary and support faces chosen from the idea, with a one-line reason; a scale with real sizes.
- **Color:** named tokens with hex, roles (primary, accent, neutral, signal), and contrast pairs that pass 4.5:1 for text.
- **Voice:** three adjectives with "this, not that" examples, plus sample lines (headline, button, error).
- **Applications:** at least three real ones from step 1, rendered.
- Name tokens the way a design system would consume them (`color.brand.primary`), so the brand can feed a system later.

## 5. Guidelines page
One HTML page in segmented sections, not one long list: idea, mark and its rules, type, color, voice, applications, do and do-not. Write a short `DESIGN.md` beside it that a model can read: intent, tokens with roles, type, form, motion, do-not. Log decisions in `DECISIONS.md`.

## Rules
- No invented facts about the client. Missing facts get a [placeholder].
- No claim about a person's experience, tools or results that they have not confirmed.
- Every contrast pair is measured, not estimated.
