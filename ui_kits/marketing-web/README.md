# Marketing Web — UI Kit

A high-fidelity recreation of a Colliers-style **marketing / corporate web** surface, built from the brand guidelines + the digital logo.

> **Status:** interpretive recreation. No production source or Figma was provided.

## Files

- `index.html` — full homepage as a single HTML file. Demonstrates every component below in context.

## Sections demonstrated

| Section | Purpose |
|---|---|
| Sticky nav | Logo · primary nav · ghost CTA · primary CTA |
| Hero | Deep-Blue block, Light-Blue accent block, Highlight-box wordmark, search card |
| Stats strip | KPI numerals in Open Sans Light, accent in Medium Blue + Bold |
| Services grid | 3×2 cards with outline icons in Pale Blue Grey tile |
| Property listings | Filter pills + property cards with status badge, gradient placeholder image, spec row |
| Insight pull-quote | Deep Blue background, Merriweather quote, Light-Blue eyebrow, side-block accent |
| Insights grid | Featured + two stacked report cards |
| CTA strip | Medium-Blue full-bleed, white-on-blue actions |
| Footer | Deep Blue, four-column |

## Visual rules applied

- **Blue dominates** — every full-bleed section uses Deep, Dark or Medium Blue.
- **Two blocks per layout, 3:1 ratio** — hero uses Deep Blue + Medium Blue accent.
- **Highlight box echoes the logo's rounded rectangle** — used on the word "success" in the hero.
- **Logo stripe** appears as a 14px Yellow / Cyan / Red bar at the bottom of the hero.
- **Tagline** never used standalone — present in footer only.
- **Tertiary palette** appears only in the logo stripe and the "FOR SALE" yellow badge — under the 25% cap.

## Component coverage

- Nav (sticky, with backdrop)
- Buttons (primary, secondary, ghost) with hover/press states
- Search card (tabs + grid + submit)
- Stat block
- Service card with outline icon tile
- Filter pills (segmented selection)
- Property card with status badge + gradient image + spec row
- Pull-quote with author block
- Insight card (featured + standard)
- CTA strip
- Footer (multi-column)

## Caveats

- Property images are gradient + line-pattern placeholders. Drop in real cityscape photography for production.
- Icons are Lucide-style hand-rolled SVGs. Swap for Lucide CDN or the brand's own icon library when available.
- All copy is illustrative.
