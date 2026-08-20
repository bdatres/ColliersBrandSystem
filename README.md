# Colliers Design System

A digital-first interpretation of the **Colliers Visual Identity Guidelines** — packaged as reusable tokens, components and templates for prototyping and production work.

> **Tagline:** "Accelerating success." **Industry:** Global commercial real estate services & investment management.

---

## About Colliers

Colliers is a global diversified professional services and investment management company specialising in commercial real estate. Their brand voice positions them as **enterprising, expert advisors** to property occupiers, owners and investors. The brand promise — *"We accelerate success"* — frames every touchpoint.

### Mission

> Maximize the potential of property and real assets to accelerate the success of our clients, our investors and our people.

### Core Values

- **Be enterprising** to exceed expectations.
- **Collaborate** to drive exceptional results.
- **Invest in relationships** to deliver enduring value.
- **Be experts** to lead the industry into the future.
- **Do what's right** for our clients, people and communities.

### Surfaces represented

Colliers operates across many surfaces. The materials provided here describe the **master visual identity** rather than any single product. The UI kit included demonstrates how the identity translates to a **marketing / corporate web** surface (the most common application of the brand on screen). Other surfaces — investor reports, market research PDFs, property listings, presentations — share the same primitives.

---

## Sources

- `reference/Colliers_Brand_Guidelines.md` — full visual identity guidelines as provided.
- `reference/2024_US_CopyStyleGuide_v02.pdf` — the official Colliers U.S. Copy Style Guide (grammar, punctuation, terminology), rebuilt as `Colliers Copy Style Guide.html`.
- `reference/social-templates/` — official Colliers social media templates kept as source context: PPTX (1x1 Property Marketing, 1x1/4x5/9x16 Spotlights) and PDF (4x5/9x16 Property Marketing).
- `reference/pitch-templates/` — official Colliers pitch deck source context: Property Sales Pitch Template (PDF), Office Occupier Pitch Template, Corporate Services (PPTX).
- `reference/bov-templates/` — official Colliers Broker Opinion of Value (BOV) source context: Opinion of Value — Digital Template (16x9) and Multifamily Opinion of Value (PDF).
- `reference/proposal-templates/` — official Colliers proposal & marketing source context: Office Proposal Template - Digital (PDF).
- `reference/om-templates/` — official Colliers Offering Memorandum (OM/CIM) source context: Multifamily Portfolio CIM template, Industrial CIM Template - Interactive - Widescreen, Brochure CIM Template Office RGB Widescreen (PDF).
- `assets/icons/` — official Colliers asset-class icon set (Agribusiness & Land, Healthcare & Retirement, Hospital Services, Hotels, Industrial & Logistics, Multifamily, Office, Residential, Retail), each in Dark Blue, Medium Blue and White colorways.
- `assets/colliers-logo.png` — Colliers Digital logo (full color, on blue background, 1572×896, transparent PNG).
- `fonts/` — the **licensed brand fonts**, self-hosted: Open Sans (Light → ExtraBold + italics), Open Sans Condensed (Light / Bold), and Merriweather (Light → Black + italics). Wired into `@font-face` rules in `colors_and_type.css`.
- No codebase or Figma file was provided. Component recreations are derived from the guidelines and the logo's visual DNA, plus public knowledge of Colliers' typical applications. **If a Figma library or codebase is available, attach it and we'll align the UI kit to it.**

---

## Content Fundamentals

How Colliers writes.

### Voice

**Confident, credible, passionate, human, authentic.** Never dry, arrogant, condescending, aggressive or disingenuous. The brand explicitly trades formality for clarity — *"real words, clear language, honest and not unnecessarily formal."*

### Tone calibration

- **Confident, not arrogant.** Grounded in knowledge, experience and data; willing to be bold and take smart risks.
- **Human, not casual.** Plain English, but professional — this is enterprise real estate, not a lifestyle brand.
- **Passionate, not breathless.** Conviction shows in specifics, not adjective stacks.

### Person & address

- **"We"** for Colliers. *"We are enterprising. We invest in relationships."*
- **"You" / "your"** for the reader (client or employee). *"Your success is our success."*
- Avoid third-person corporate distance ("Colliers offers…") in marketing copy. Use it sparingly in formal reports.

### Sentence shape

- Short declaratives stacked together. *"We are enterprising. Our expert advice… leads the industry into the future. We invest in relationships to create enduring value."*
- Use a one-line summary line as a closer. *"At Colliers, we accelerate success."*
- Pair a values statement with a "for our people / for our clients" split when the audience matters.

### Casing

- **Sentence case** for headlines, body, and the tagline ("Accelerating success.").
- **ALL CAPS** reserved for *document/section headings* in Open Sans Bold with +100–175 tracking — never inline body emphasis.
- Title Case is **not** the default. Use sparingly, mostly for proper nouns and product/report names.

### Punctuation & grammar

- Oxford-style commas are common in their materials.
- Em-dashes are welcome for parenthetical asides — like this — but not overused.
- "&" can replace "and" in headlines and titles (*"Tables, Charts & Maps"*) but spell it out in body copy.

### Numerals & units

- Spell out one through nine; numerals for 10+. *"Minimum size 80px"*, *"two or three steps brighter"*.
- Use proper units (px / mm / pt) and stick with them. SI-style spacing: `0.5"` or `13mm`, not "half an inch".

### Emphasis rules (from the guidelines, applied to copy)

- One or two words of emphasis per sentence — no more.
- Don't combine more than one type of emphasis (don't bold *and* recolor the same word).
- Approved patterns: **color shift** (two steps brighter/darker), **weight shift** (two weights heavier), **color underscore**, **color highlight box** (medium-blue rounded box with white text).

### Emoji & exclamation marks

- **No emoji.** This is a B2B real-estate brand. Emoji read as casual or unserious.
- Exclamation marks are rare — let confident statements stand on their own.

### Examples in the wild

> *"We are enterprising. Our expert advice to property occupiers, owners and investors leads the industry into the future."*

> *"What sets us apart is not what we do, but how we do it."*

> *"Your success is our success; we are dedicated to driving exceptional results with the right property solutions for you, wherever you operate."*

Notice: short sentences, "we/you" address, no jargon, ends on a confident assertion.

---

## Visual Foundations

### Color

- **Blue dominates.** Every design must be anchored by one of the three primary darker blues: **Deep Blue `#000759`**, **Colliers Dark Blue `#25408F`**, or **Medium Blue `#1C54F4`**. White and Pale Blue Grey balance the saturation.
- Three palettes, with strict rules:
  - **Primary** (blues + white) — the only palette allowed for graphic *blocks* and the logo.
  - **Secondary** (cool blue-greys) — text, backgrounds, sectioning. Cannot be used for blocks.
  - **Tertiary** (red, yellow, orange, purple, teal, cyan, cool grey) — sparingly, only for charts/illustration; capped at 25% of any composition; never for text/keyline/blocks.
- Tints permitted at **80 / 60 / 40 / 20 / 10%**. Use them for chart series, map regions, sub-sections.
- Medium Blue and Light Blue are flagged as **digital-first** — they shift in print. Print-only work should lean on Deep Blue, Dark Blue, Pale Blue, White.
- **Red caveat:** because red reads as "negative trend," only use Colliers Red on data points that are actually negative or declining.

### Type

- **Open Sans** is the workhorse — sans-serif, neutral, highly legible. Used at Light (large headlines), Regular (body, subheads), Semibold (small-size headlines, emphasis), Bold (CTAs, labels). The full weight range (Light → ExtraBold, plus italics) is **self-hosted in `fonts/`**; Verdana is the documented fallback.
- **Merriweather** is the warm, editorial counterpoint — serif, used for pull quotes, subheads in long-form, the occasional authoritative headline, and **KPI / stat figures**. Self-hosted Light → Black with italics; Georgia is the fallback. **Never mix Open Sans and Merriweather on the same line.**
- **Open Sans Condensed** (Light / Bold) is self-hosted too — reserved for footnotes, legal copy, and dense table data.
- **Document/section headings** are always Open Sans Bold, ALL CAPS, +100–175 tracking — that's the brand's "eyebrow" cue.
- Default body color is *not* black — it's a deep blue or deep blue-grey. Black is only allowed when branding is unnecessary.

### Spacing & layout

- 8pt-grid friendly tokens (`--space-1 … --space-24`).
- The logo defines the smallest reusable spatial unit: **clear space = 2× the height of the logo's color stripes** on every side.
- Compositions favor generous margins, dominant blue regions, and one to two large *blocks* anchored to an edge or floated on the canvas.

### Backgrounds

- **No photography slop.** Backgrounds are usually solid blue (Deep, Dark, or Medium), white, or Pale Blue Grey. Photography exists but always sits inside frames, never as a hero wash.
- **No gradients in the body** — gradients are reserved for *keyline* graphic elements (frames, extending highlights), always paired with Pale Blue Grey or White.
- **No textures or patterns** in the marketing system. Maps may use line/dot textures.
- The brand's signature "background" *is* an expanse of Deep Blue or Dark Blue with a single bold word in Open Sans Light.

### Graphic elements

**Blocks** and **keylines** are the brand's signature compositional device. Full specimens live in section 07 of `Colliers Design System.html`, in the standalone `Colliers Blocks and Keyline.html`, and across the `preview/block-*.html` and `preview/keyline-*.html` cards.

- **Blocks** — flat, solid primary-blue rectangles for compositional emphasis and hierarchy.
  - Maximum **two** per layout. If two are used they must **visibly overlap**, be **varied in size** (≥ 3:1 ratio), and at least one side of one block must **extend past** the other (never "flushed", never merely touching).
  - Single blocks can be **anchored** to an edge or **float** anywhere on the canvas. No firm rules on size/proportion.
  - **Color:** primary blues only (Deep, Dark, Medium). The accent block must be **two or three steps brighter/darker, or white** — e.g. Deep + Medium/Light/White, *not* Deep + Dark (insufficient contrast). The secondary palette can be a background but **never a block**; the logo-stripe Light Blue is **never** a block.
  - **Opacity** may drop to 95% over a photo or another block — **never** use Multiply or other layer effects.
  - **Padding:** keep generous margins around copy inside a block; never crowd the type.
- **Keyline** — a thin (≈1.5pt) dark-blue rule that frames, organizes or connects. **Seven options:** Framed, Left-aligned, Right-aligned, Encompassing, Extending, Organizing, Connecting. Best colors are the three darker blues; Light Blue only on very light images.
  - **Blocks + keyline:** a keyline may overlap a block as long as it isn't the same color/tint; where it crosses a block it **breaks**, leaving a gap equal to half the layout margin; a frame can hold one color or **switch colors** as it leads into a darker/lighter background.
  - **Keyline gradient:** three colors (Medium, Light, Deep Blue), always paired with Pale Blue Grey or White as the lightest stop. Frames begin/end on the darker color with a Pale Blue Grey highlight near the 20% mark; extending highlights run from 60% of the dark color to 100% Pale Blue Grey. Position the transition between 20–60%.
  - **Tagline:** for framed / left-right / encompassing keylines the tagline **intersects** the bottom of the frame; for organizing / extending / connecting keylines it sits in the **bottom corner**, not on the line. "Accelerating success." is the only copy that locks up with a keyline.
- **Do not lift the logo stripe** (the yellow/cyan/red bar under the wordmark) as a decorative element elsewhere in the system. It belongs to the logo only.

### Animation & motion

- The guidelines don't specify motion, but the brand reads as **restrained**: short fades (`200–300ms`), `ease-out` curves, no bounces, no parallax, no springy overshoot. Use motion to clarify, not delight.
- Tokens: `--dur-fast: 120ms`, `--dur-normal: 200ms`, `--dur-slow: 320ms`; `--ease-standard: cubic-bezier(0.2, 0, 0, 1)`.

### Hover & press

- **On light surfaces:** hover is a soft Medium-Blue tint (`rgba(28,84,244,0.08)`); press deepens to \~16%. Text-only links shift from Medium Blue → Dark Blue.
- **On dark/blue surfaces:** hover is a 12% white wash; press is a 24% white wash.
- **Buttons:** primary buttons darken on hover (Medium Blue → Dark Blue → Deep Blue on press). Avoid scaling/shrinking; the brand is composed, not playful.
- **Icons:** alternate blue shade or white for hover, per guidelines.

### Borders & dividers

- Hairline rule: 0.5pt / 1px in `--col-deep-blue-grey` at \~16% opacity (`--divider`) — borrowed from the table spec.
- Keylines are 1pt, dark-blue, sometimes gradient (Medium → Pale Blue Grey, Light → Pale Blue Grey, Deep → Pale Blue Grey).

### Shadow & elevation

- Restrained. The logo guidelines explicitly forbid drop shadows, so UI elevation should remain subtle. Three steps: `--shadow-1` (resting card), `--shadow-2` (hovered card / popover), `--shadow-3` (modal). All shadows are tinted with Deep Blue at low alpha — never neutral grey.

### Corner radii

- The logo's pronounced rounded rectangle is the brand's most distinctive geometric note. It directly inspires the **highlight box** (rounded medium-blue box around emphasized words) — *"a nod to the rounded corners of the Colliers logo."*
- Token radii: `--radius-sm: 4px`, `--radius-md: 8px`, `--radius-lg: 12px`, `--radius-xl: 20px`. Use `--radius-xl` for hero blocks and any "highlight box" treatment to echo the logo.

### Cards

- White surface, 12–20px radius, hairline border (`--divider`), `--shadow-1` resting / `--shadow-2` hovered. No colored left-border accents, no gradient borders.

### Transparency, blur

- **Transparency:** Blocks may drop to 95% opacity over photography; tints (10/20/40/60/80%) for chart series and map regions. No frosted-glass / iOS-style blurs in the brand system.
- **Blur:** Not part of the visual language. Avoid backdrop blurs.

### Imagery

- When photography is used, it skews **cool, well-lit, architectural**. Real cityscapes, building lobbies, occupied office space — never warm sepia, b&w, or grainy stock. Photography sits inside frames or under solid blocks, never alone as a hero.

### Iconography

See [Iconography](#iconography) below.

### Data visualisation — tables, charts & maps

The brand treats data as a first-class visual surface, and the rules are strict:

- **Tables** — Open Sans, \~9pt; Dark Blue / Dark Blue Grey data, white/pale headers. 0.5pt dividers or alternating Light Grey / Extra Light Blue rows at 40% opacity. All-caps headers in Open Sans Bold, +50 tracking. Copy left-aligned, decimals right-aligned, decimal-free figures may center. Open Sans Condensed for footnotes and dense data.
- **Charts** — minimalist; include only the essentials. Labels in all-caps Open Sans Bold, +50 tracking. Color by priority: **Deep → Dark → Medium → Light → Pale Blue**, then tints (80/60/40/20/10%), then secondary/tertiary only when more differentiation is needed. **Red is reserved for negative/declining data.**
- **Maps** — clean and minimal. Four approved coverage palettes (Pale Blue Grey/White, Grey/White, Light Blue Grey/White, Light Blue Grey/Pale Blue Grey). Borders at 0.25pt and 50% of the landmass color. **Offices are always yellow dots** (Deep Blue stroke where contrast is needed), labelled in 5pt Open Sans Bold. Sub-regions use tints of one primary blue; property maps add simple single-color amenity icons.

Live specimens: `preview/tables.html`, `preview/charts.html`, `preview/chart-colors.html`, `preview/maps.html`, and section 08 of `Colliers Design System.html`.

---

## Iconography

Colliers icons are **outline / line icons**, drawn at a **uniform 1pt stroke**, using only the **primary palette** (single color per icon — typically Deep Blue, Dark Blue, or Medium Blue on light; white on dark). Branded icons feature *"small, occasional line breaks that connect to the keyline element"* — a stylistic detail where a stroke gap aligns with the surrounding frame.

Rules from the guidelines:

- Always primary palette only.
- One color per icon. No two-tone, no fills, no gradients.
- Stroke weight scales proportionally for large formats but reads as 1pt at standard size.
- Hover state: alternate blue shade (Medium Blue ↔ Dark Blue) or white on a dark surface.
- **No emoji**, no Unicode glyphs as decorative icons.

### Practical implementation

Official asset-class and capability-set icon sets are now bundled in `assets/icons-library/` (dark blue, medium blue, and white colorways) and shown in full in `preview/icons-asset-class.html`. For any icon need outside those two sets, we recommend **Lucide** (`lucide.dev`) — a clean 24px/1.5pt outline set that matches the Colliers stroke aesthetic. **This is a substitution, not a brand-mandated set** — flag for the user. To use:

```html
<script src="https://unpkg.com/lucide@latest"></script>
<i data-lucide="building-2"></i>
<script>lucide.createIcons();</script>
```

Override stroke color with CSS `color: var(--col-dark-blue);` and stroke width 1.5–2 to match.

When adding **custom Colliers icons**, draw them in a 24px artboard, 1.5px stroke, rounded line caps, single color, with the optional "broken stroke that connects to a keyline" detail when they appear inside a framed composition.

### Logo

- `assets/colliers-logo.png` — full-color, 1572×896, transparent background.
- Minimum on screen: 80px wide.
- Clear space: 2× stripe-height on all sides.
- Never recolor, rotate, add shadows, or use on a colored/photo background without the white keyline.

---

## File Index

```
README.md                          ← this file (brand overview + foundations)
SKILL.md                           ← Agent-Skills entry point
colors_and_type.css                ← all design tokens (CSS vars) + @font-face

Colliers Design System.html        ← MASTER reference — all 9 sections, one scrollable page
Colliers Design System (standalone).html   ← self-contained export of the above (fonts/logo inlined)
Colliers Blocks and Keyline.html   ← standalone Blocks + keylines chapter
Colliers Data and Maps.html        ← standalone Data & maps chapter
Colliers Data and Maps (standalone).html   ← self-contained export of the above
Colliers Copy Style Guide.html     ← full U.S. copy / grammar / terminology reference
Colliers Copy Style Guide (standalone).html   ← self-contained export of the above

assets/
  colliers-logo.png                ← primary brand mark (full color)
  icons-library/                   ← full asset-class + capability-set icon set (dark/medium blue, white)
fonts/                             ← licensed brand fonts (Open Sans, Open Sans Condensed, Merriweather)
reference/
  Colliers_Brand_Guidelines.md     ← original guidelines, verbatim
  Colliers-Map-Style.json          ← production Esri/ArcGIS vector-tile map style (real GIS colors)

preview/                           ← card-sized specimens for the Design System tab
  _card.css                        ← shared card chrome
  — Color:   colors-primary, colors-secondary, colors-tertiary, colors-tints, colors-semantic, colorspace
  — Type:     type-families, type-scale (incl. Merriweather display headline), type-section-heading (2 options), type-emphasis
  — Spacing:  spacing-scale, radii, elevation
  — Components: buttons, inputs, badges, cards, stat-block, icons-asset-class (asset class + capability set)
  — Blocks:   block-single, keyline-variants (7 options), keyline-tagline, keyline-gradient,
               blocks-keyline-composed (situational reference — not a core pattern)
  — Data:     tables, charts, chart-colors, maps, colorspace
  — Maps:     map-style-live (live MapLibre render of the production Esri vector style)
  — Brand:    logo

ui_kits/
  marketing-web/
    index.html                     ← interactive marketing-site demo (brand applied in context)
    README.md
```

---

## The master document

`Colliers Design System.html` is the single scrollable reference. Ten numbered sections:

| # | Section | Covers |
| --- | --- | --- |
| 01 | Brand & voice | Story, values, tone, the writing rules |
| 02 | Color | Primary / secondary / tertiary palettes, tints, semantic roles |
| 03 | Typography | Open Sans + Merriweather scale, emphasis, section headings |
| 04 | Spacing & radii | 8-point grid, corner radii echoing the logo |
| 05 | Elevation | Restrained, blue-tinted shadows |
| 06 | Components | Buttons, inputs, badges, cards, KPI figures, icons |
| 07 | Blocks & keylines | The signature composition — overlapping, gap space, frame color, 7 keyline options, gradients, tagline placement |
| 08 | Data & maps | Tables, charts, chart color priority, coverage maps, production map-style color values |
| 09 | Logo | Usage, clear space, minimum size, don'ts |
| 10 | Legal & disclaimers | Required disclaimer copy for proposals, reports, decks, and websites |

Export any chapter as a self-contained file on request (the `(standalone)` files inline fonts + logo and work offline).

---

## Legal & Disclaimers

Every proposal, research report, marketing collateral, presentation, and website page carrying Colliers content must include this disclaimer, verbatim:

> **Legal disclaimer** This document/email has been prepared by Colliers for advertising and general information only. Colliers makes no guarantees, representations or warranties of any kind, expressed or implied, regarding the information including, but not limited to, warranties of content, accuracy and reliability. Any interested party should undertake their own inquiries as to the accuracy of the information. Colliers excludes unequivocally all inferred or implied terms, conditions and warranties arising out of this document and excludes all liability for loss and damages arising there from. This publication is the copyrighted property of Colliers and/or its licensor(s). © 2026. All rights reserved. This communication is not intended to cause or induce breach of an existing listing agreement. *\[Include your market's legal name here. (ex. Colliers International Group Inc.)\]*

- **Do not alter the wording.** This exact copy is required on all proposals, research reports and marketing collateral.
- Swap in your market's legal entity name where bracketed.
- Only Global Finance and Communications-approved announcements may include the Colliers NASDAQ/TSX ticker (**CIGI**) in a press release or boilerplate.
- Set small but legible — Open Sans Condensed suits the length — never below accessible contrast/size.

---

## Caveats & open questions

- **No real codebase or Figma access** was provided. UI kit components are derived from the guidelines + logo, not from production source. Pixel fidelity to existing Colliers digital products is not guaranteed.
- **Iconography is substituted with Lucide** (close stroke match). The Colliers branded icon set is not bundled — see the Iconography section.
- **No slide-deck template** ships yet — no sample deck was attached. Provide one and we'll build a `slides/` folder that reuses these primitives.

If any of these gaps matter, link the source and we'll iterate.
