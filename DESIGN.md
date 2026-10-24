---
name: Aureate Obsidian
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#303032'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#d4c78f'
  on-secondary: '#383006'
  secondary-container: '#4f471b'
  on-secondary-container: '#c2b57f'
  tertiary: '#f1c976'
  on-tertiary: '#3f2e00'
  tertiary-container: '#d3ae5d'
  on-tertiary-container: '#594100'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#f1e3a9'
  secondary-fixed-dim: '#d4c78f'
  on-secondary-fixed: '#211b00'
  on-secondary-fixed-variant: '#4f471b'
  tertiary-fixed: '#ffdf9e'
  tertiary-fixed-dim: '#e8c16f'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: 3rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: 0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a high-caliber, editorial-grade student showcase tailored to impress recruiters, design leads, and industry clients. Moving beyond conventional entry-level templates, it frames emerging academic and creative talent within an executive, gallery-level atmosphere.

The aesthetic fuses **Luxury Minimalism** with **Atmospheric Glassmorphism**:
- **Atmosphere:** Deep obsidian and matte charcoal canvases replace default blacks, providing deep acoustic-like quietness.
- **Accents:** Restrained, luminous champagne-to-amber golds cast soft, warm glows, treating project displays like curated museum artifacts under pinpoint lighting.
- **Tone:** Confident, deliberate, highly focused, and intellectually rigorous.

## Colors

The palette establishes an obsidian stage with refined gold light emitters:

- **Primary (`#D4AF37` / Pure Aureate Gold):** Anchor for interactive states, key metrics, and luminous focal points.
- **Secondary (`#F3E5AB` / Pale Champagne):** Reserved for shimmering highlights, active glows, and light typography overlays.
- **Tertiary (`#8C6D23` / Muted Bronze-Gold):** Used for subtle card strokes, inactive states, and low-priority accents.
- **Neutral Palette:**
  - `Canvas / Pitch Obsidian`: `#09090B`
  - `Surface 1 / Charcoal Matte`: `#121214`
  - `Surface 2 / Elevated Slate`: `#1B1B1F`
  - `Border / Gold Sheen Soft`: `rgba(212, 175, 55, 0.18)`
  - `Border / Gold Sheen Focus`: `rgba(212, 175, 55, 0.5)`
  - `Text Primary`: `#F8F8F6`
  - `Text Secondary`: `#A3A3A8`
  - `Text Accent`: `#E6C665`

## Typography

Typography relies on a crisp dual-sans arrangement:
- **Headlines & Body (`Plus Jakarta Sans`):** Offers immaculate geometry, clear humanist contours, and high legibility at all scales without becoming stiff.
- **Labels, Metadata, & Accents (`Space Grotesk`):** Provides a slight technical, architectural rhythm to project dates, tags, and project stats.
- Keep body paragraph lines constrained to 65 characters maximum to preserve editorial poise.

## Layout & Spacing

A strictly responsive 12-column fluid grid system with generous breathing room:
- **Desktop (1024px+):** 12 columns, `margin: 3rem`, `gutter: 1.5rem`, maximum content bounding box of `1280px`.
- **Tablet (640px - 1023px):** 8 columns, `margin: 2rem`, `gutter: 1.25rem`.
- **Mobile (Below 640px):** 4 columns, `margin: 1.25rem`, `gutter: 1rem`.

Generous vertical breathing space ensures that featured academic and client projects do not compete with one another. Stack project summaries with `space-xl` gaps on mobile, scaling to `3.5rem` on desktop.

## Elevation & Depth

Visual hierarchy uses deep atmospheric tiers, perimeter halos, and back-lit gold radiance:
- **Base Level:** `#09090B` solid deep canvas.
- **Surface Elevation (Cards & Panels):** Multi-layered backdrop with `background: rgba(18, 18, 20, 0.75)`, a `1px` translucent gold border (`rgba(212, 175, 55, 0.16)`), and background blur of `16px`.
- **Ambient Shadow (Glow Elevation):** Elevated interactive components emit a warm gold aura rather than a cold shadow: `box-shadow: 0 8px 32px -4px rgba(0, 0, 0, 0.8), 0 0 20px -2px rgba(212, 175, 55, 0.18)`.
- **Focused State:** Border transitions to `rgba(243, 229, 171, 0.65)` with an interior ambient sheen: `box-shadow: 0 0 24px rgba(212, 175, 55, 0.35)`.

## Shapes

The design system embraces a refined Level 2 (`0.5rem` / `8px`) base radius:
- Structural elements (cards, hero panels, code snippets) use `rounded-lg` (`1rem`) for architectural balance.
- Micro elements (buttons, inputs, status pills) use `rounded` (`0.5rem`).
- Strict avoidances: Avoid circular or hyper-round pill buttons for primary actions, preserving a sharp, mature design language.

## Components

### Buttons
- **Primary Aureate Button:** Linear gradient fill (`135deg, #D4AF37 0%, #B89228 100%`) with dark obsidian text (`#09090B`) in `Space Grotesk` medium-bold. Includes an animated `linear-gradient` pseudo-element shimmer moving 120° across the surface on hover. Shadow outputs a direct gold bloom (`0 0 16px rgba(212, 175, 55, 0.4)`).
- **Secondary Ghost Button:** Charcoal backing (`rgba(27, 27, 31, 0.6)`), `1px` border of `rgba(212, 175, 55, 0.3)`, text in `Text Primary`. Hover induces border brightening to `rgba(243, 229, 171, 0.8)` and a faint golden backlight glow.

### Project & Case Study Cards
- Built on `Surface 1` with a `1px` continuous border (`rgba(212, 175, 55, 0.18)`).
- On card hover: The border smoothly brightens to `rgba(212, 175, 55, 0.5)` with an elevated y-axis lift of `-4px` and a diffuse radial drop shadow (`box-shadow: 0 12px 36px rgba(0,0,0,0.8), 0 0 28px rgba(212, 175, 55, 0.15)`).

### Chips & Skill Badges
- Background of `rgba(212, 175, 55, 0.08)`, border `1px` solid `rgba(212, 175, 55, 0.25)`, typography in `label-sm` with color `#F3E5AB`.
- Subtle pulse dot indicator (`4px` diameter) in pure `#D4AF37` for active competencies and current roles.

### Inputs & Contact Fields
- Obsidian well base (`#0E0E10`) with `1px` rim (`rgba(255, 255, 255, 0.08)`).
- Active/Focused state: Rim elevates to `rgba(212, 175, 55, 0.7)` with an inner and outer glow (`0 0 12px rgba(212, 175, 55, 0.25)`). Text in `#F8F8F6`.

### Project Metric & Stat Counters
- Large numbers rendered in `headline-lg` with a champagne-to-gold gradient text mask (`linear-gradient(180deg, #FFFFFF 20%, #D4AF37 100%)`).
- Subtext rendered in `label-sm` uppercase Space Grotesk in neutral tertiary text.