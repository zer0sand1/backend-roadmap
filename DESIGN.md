# Design System

## Theme
Dark. Warm charcoal base with muted slate accent. Used by developers studying late at night — the page is the main light source in a dim room.

## Color Strategy
Restrained. Tinted warm neutrals carry 92% of the surface. One accent (muted slate blue) at ≤8%.

### Base (OKLCH)
- Background: `oklch(0.13 0.01 55)` — deep warm charcoal
- Surface: `oklch(0.165 0.012 55)` — elevated panels
- Surface card: `oklch(0.20 0.015 55)` — project cards
- Border: `oklch(0.26 0.015 55 / 0.4)`

### Text
- Primary: `oklch(0.90 0.008 55)` — near-white with warm cast
- Secondary: `oklch(0.70 0.015 55)` — readable mid-tone
- Tertiary: `oklch(0.55 0.012 55)` — metadata
- Muted: `oklch(0.42 0.01 55)` — labels

### Accent
- Accent: `oklch(0.55 0.06 250)` — muted slate blue
- Accent subtle: `oklch(0.55 0.06 250 / 0.15)`
- Secondary accent: `oklch(0.58 0.06 195)` — muted teal

### Semantic
- Success: `oklch(0.60 0.08 145)` — muted green
- Warning: `oklch(0.60 0.08 70)` — warm amber
- Error: `oklch(0.55 0.10 25)` — muted red
- Info: `oklch(0.55 0.08 350)` — muted rose
- Secondary: `oklch(0.55 0.07 285)` — muted violet

## Typography
- Font: Inter
- Mono: JetBrains Mono
- Scale: 2.5rem / 1.75rem / 1.25rem / 1rem / 0.875rem / 0.75rem
- Line height: 1.75 for prose (compensated for dark mode), 1.2 for headings
- Letter-spacing: 0.01em on body (dark mode compensation)
- Body max-width: 70ch
- Heading wrap: `text-wrap: balance`

## Spacing
- Section gap: 5rem (80px)
- Element gap: 1.5rem (24px)
- Card padding: 2rem (32px)
- Container max-width: 720px (tight, readable)

## Motion
- Ease-out-quart: cubic-bezier(0.25, 1, 0.5, 1)
- Duration: 200ms for hover

## Principles
- Dark and warm, not cold or cyberpunk
- Reading comfort is #1 — high contrast, compensated typography
- Subtle borders, no heavy shadows (depth via surface lightness)
- Calm, editorial feel — like a well-printed technical book at night
