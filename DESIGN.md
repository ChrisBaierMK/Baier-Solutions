# DESIGN.md — Baier Solutions

## 1. Visual theme
Cinematic dark (BMW / Ferrari: oversized type, true black, media-heavy) remixed with cult/indie restraint (A24 / Criterion: editorial rigour, nothing decorative). The one memorable element is the hub — the BAIER core with the family axe in the middle and the four domains drawn out from it on page load. Everything else stays quiet: black, white, one gold.

## 2. Colour tokens
--ink: #000000        (true black — page background on dark bands, text on light)
--paper: #FFFFFF      (light bands)
--muted: #8A8A8A      (secondary text, both modes)
--rule-dark: #262626  (borders on black)
--rule-light: #E3E3E3 (borders on white)
--gold: #B8922E       (the one accent: axe, CTA, focus ring — nothing else)
--gold-ink: #000000   (text on gold)
Rule: black + white dominant, gold is sharp and scarce. No gradients except a single radial vignette behind the hub. No purple, no teal, no cream.

## 3. Typography
Display: Big Shoulders Display, 700/800, tracking -0.01em, sizes 88/56/36 (condensed, industrial — reads like a stencil on a machine)
Body: Archivo, 400/600, 17px, line-height 1.55, max 68 characters per line
Two families, clearly distinct (condensed display vs normal-width grotesque).
No all-caps eyebrows. No single-word colour accents in headlines. No arrows after links.

## 4. Component styling
Button: solid gold, 0 radius, Archivo 15/600, black text; secondary = 1px rule, transparent
Card: none. Content sits on bands separated by 1px rules.
Facts list: 1px rules between rows, label column + value column
Input: 1px rule, visible label above, focus ring = gold, 0 radius
Nav: left wordmark with axe, right 4 links + language toggle. No status dot.

## 5. Layout principles
Max width 1200px, 24px gutter desktop / 16px mobile
Left-aligned text everywhere, including the hero headline
Section rhythm: 112px desktop / 64px mobile
Domains = alternating full-width bands (black / white / black / white), each: headline + facts on the left, one editorial photo on the right (3:2). Where no real photo exists yet, the band runs text-only — no placeholder boxes, no stock, no AI render.
Proof row under the hero: four facts separated by vertical rules, one line each.

## 6. Depth and elevation
Flat. Borders only. Shadows nowhere. One radial vignette behind the hub for atmosphere.

## 7. Imagery rules
Subject: the real things — the barn, the Porsche on the slope, the container showroom, a Menzi Muck on a slope, Action Cloud's ramps.
Lighting: natural, late afternoon where possible; black-and-white allowed and encouraged (it sits inside the tokens).
Crop: 3:2 editorial, subject off-centre; never square, never icons.
Sources: own photos only. MK1930 photos hotlinked from mk1930.ro (own site) until copied into /img.
No stock, no illustrations, no icon grids.

## 8. Do's and don'ts
Do: one page-load reveal (core → spokes draw → nodes stagger in), then nothing moves unless the user acts.
Do: respect prefers-reduced-motion (reveal becomes instant).
Don't: fade-up sections, hover-lift, glassmorphism, blobs, numbered 01/02/03, middle dots, Lucide icons.

## 9. Responsive behaviour
Mobile-first. 16px gutter, no horizontal scroll. The hub becomes a vertical spine: core on top, four nodes hanging below on one line. Photos go full-bleed above their text. Sticky "Scrie-ne" bar on mobile.

## Rejection clause
This must never look like a SaaS template, a Framer wedding site, a construction-equipment dealer page with yellow hazard stripes, or Anthropic's cream-and-terracotta. If the page could belong to another company in Brașov, regenerate.
