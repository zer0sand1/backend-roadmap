# Design System

## Theme
Dark. Tinted warm neutrals. Used in dim ambient light (evening/night study sessions).

## Color Strategy
Restrained. Tinted neutrals carry 95% of the surface. One accent at ≤10%.

### Base
- Background: `#0c0e12` (warm-tinted near-black, not pure #000)
- Surface: `#14161d` (slightly lifted, warm)
- Surface hover: `#1a1d26`
- Border: `rgba(255,255,255,0.06)` (subtle, not harsh)
- Border strong: `rgba(255,255,255,0.10)`

### Text
- Primary: `#e8eaf0` (warm white, not pure #fff)
- Secondary: `#8a8f9d` (muted, readable)
- Tertiary: `#5c6170` (for metadata, labels)

### Accent
- Accent: `#6366f1` (indigo, used sparingly)
- Accent subtle: `rgba(99,102,241,0.08)` (for backgrounds)

### Semantic
- Success: `#4ade80` (subtle green, not neon)
- Warning: `#fbbf24` (subtle amber)
- Info: `#38bdf8` (subtle blue)

## Typography
- Font: Inter (system fallback)
- Mono: JetBrains Mono
- Scale: 2.5rem / 1.75rem / 1.25rem / 1rem / 0.875rem / 0.75rem
- Line height: 1.65 for prose, 1.2 for headings
- Body max-width: 70ch

## Spacing
- Section gap: 3rem (48px)
- Element gap: 1.5rem (24px)
- Card padding: 1.75rem (28px)
- Container max-width: 800px (tight, readable)

## Elevation
- No drop shadows on dark theme. Use border and subtle background lift instead.
- Hover states: background color shift + border color shift

## Motion
- Ease-out-quart for all transitions: `cubic-bezier(0.25, 1, 0.5, 1)`
- Duration: 200ms for hover, 400ms for page transitions
- No layout property animations

## Components

### Navigation
- Fixed top, transparent with subtle backdrop blur
- Bottom border: 1px rgba(255,255,255,0.06)
- Active link: accent color
- Height: 56px

### Project Cards (index list)
- No traditional card shape. Full-width rows with subtle bottom border.
- Hover: background lift + left border accent (2px, not side-stripe — used as progress indicator)
- Number badge: circular, muted background, accent on hover

### Detail Cards (project pages)
- Full-width sections with generous padding
- No card border-radius on main content cards (use border-radius only for small UI elements)
- Use background tints (subtle) instead of left-border stripes for card types
- Section labels: uppercase, tracking, tertiary color

### Code Blocks
- Background: `#0f1117` (darker than surface)
- Border: 1px rgba(255,255,255,0.06)
- Border-radius: 8px
- Padding: 1.25rem

### Verification Goals
- Use subtle success-tinted background (not green border-left)
- Checkmark icon + relaxed spacing
