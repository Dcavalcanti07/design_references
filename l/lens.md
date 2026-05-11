# Lens — Style Reference
> Cloud-white digital canvas

**Theme:** light

Lens employs a bright, airy canvas with subtle surface treatments and an almost-monochrome palette. A vivid teal and soft, playful gradients provide functional accents without overpowering the clean structure. Typography is precise and airy, creating a sense of clarity and modern efficiency. Components are lightweight with generous padding and soft, rounded edges, emphasizing user-friendliness and approachability within a sophisticated technical context.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Lens Teal | `#00caa0` | `--color-lens-teal` | Primary brand accent, interactive elements like buttons and active nav items, highlighting key actions. Its vividness cuts through the subdued neutrals |
| Mint Green | `#00d743` | `--color-mint-green` | Decorative fill for SVG icons and illustrations, adding a fresh, energetic touch |
| Charcoal Black | `#2c2d30` | `--color-charcoal-black` | Primary text color for headings, body copy, and icons, ensuring high contrast on light backgrounds |
| Cool Gray | `#afafaf` | `--color-cool-gray` | Secondary text for subtle descriptions, placeholder text, and borders for ghost buttons and input fields |
| White Canvas | `#ffffff` | `--color-white-canvas` | Main page and card backgrounds, providing a clean, expansive foundation |
| Slate Subtle | `#808183` | `--color-slate-subtle` | Muted helper text, delicate dividers, and very subtle icon fills |
| Light Steel | `#c0c0c1` | `--color-light-steel` | Hairline borders and very light graphical elements, barely visible against the white |
| Subtle Card Bkg | `#fbfcff` | `--color-subtle-card-bkg` | Card backgrounds, almost white but providing a faint distinction from the main canvas without introducing heavy contrast |

## Tokens — Typography

### saans — Primary display font for headings and prominent UI elements. Its unique character set ('ss01' feature) provides a distinctive visual signature, maintaining legibility at all sizes with consistent tracking. · `--font-saans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 16px, 21px, 26px, 28px, 46px
- **Line height:** 1.20, 1.35, 1.40
- **Letter spacing:** 0.0150em
- **OpenType features:** `"ss01"`
- **Role:** Primary display font for headings and prominent UI elements. Its unique character set ('ss01' feature) provides a distinctive visual signature, maintaining legibility at all sizes with consistent tracking.

### Inter — Workhorse font for body text, navigation, and button labels. Its negative letter spacing at larger sizes gives it a compact, modern feel while ensuring readability at smaller scales, especially with the 'cv11' feature for character variation. · `--font-inter`
- **Substitute:** Inter, sans-serif
- **Weights:** 400, 500
- **Sizes:** 14px, 15px, 16px, 18px, 20px
- **Line height:** 0.88, 1.10, 1.20, 1.29, 1.40, 1.43, 1.45
- **Letter spacing:** -0.0250em, -0.0220em, -0.0200em, -0.0170em, -0.0150em, -0.0090em, -0.0060em
- **OpenType features:** `"cv11"`
- **Role:** Workhorse font for body text, navigation, and button labels. Its negative letter spacing at larger sizes gives it a compact, modern feel while ensuring readability at smaller scales, especially with the 'cv11' feature for character variation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | -0.14px | `--text-caption` |
| body | 16px | 1.4 | 0.24px | `--text-body` |
| subheading | 21px | 1.35 | 0.315px | `--text-subheading` |
| heading-sm | 26px | 1.2 | 0.39px | `--text-heading-sm` |
| heading | 28px | 1.2 | 0.42px | `--text-heading` |
| display | 46px | 1.2 | 0.69px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 104 | 104px | `--spacing-104` |
| 152 | 152px | `--spacing-152` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 0px |
| buttons | 50px |
| navItems | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px` | `--shadow-subtle` |
| subtle-2 | `color(display-p3 0.172549 0.176471 0.188235 / 0.02) 0px 0...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Ghost Nav Link
**Role:** Navigation button, text-only

backgroundColor=transparent, color=rgba(55,55,55,0.4), borderRadius=0px, padding=0px, font: Inter at 16px, weight 400.

### Primary Action Button
**Role:** Call to action button

backgroundColor=#00caa0, color=#ffffff, borderRadius=50px, padding=11px 24px, font: Inter at 16px, weight 500. Box shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px.

### Developer Action Button
**Role:** Secondary action button (ghost style)

backgroundColor=transparent, color=#2c2d30, borderRadius=50px, padding=11px 24px, font: Inter at 16px, weight 500. Border: 1px solid #afafaf. Box shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px.

### Informative Card
**Role:** Content container for features or details

backgroundColor=rgb(251, 251, 251), borderRadius=16px, padding=24px, font: Inter at 16px, weight 400. Box shadow: none.

### Feature Highlight Card
**Role:** Highlighted content container with iconography

backgroundColor=rgba(45, 45, 48, 0.02), borderRadius=24px, padding=32px, font: saans at 21px, weight 400. Box shadow: none.

### Circular Icon Wrapper
**Role:** Decorative background for icons

backgroundColor=rgba(40, 211, 107, 0.12), borderRadius=50%.

## Do's and Don'ts

### Do
- Prioritize Charcoal Black (#2c2d30) for all primary text and headings against White Canvas (#ffffff), achieving AAA contrast.
- Use Lens Teal (#00caa0) exclusively for primary interactive elements, brand accents, and active states. Do not use it for passive text or large backgrounds.
- Apply a 50px border-radius to all primary action buttons for a soft, approachable feel.
- Maintain generous internal padding on cards and buttons, using 24px for card content padding and 11px vertical padding for buttons, aligning with a comfortable density.
- Employ the 'saans' font for all headings, leveraging its unique 'ss01' feature and positive letter spacing (0.015em).
- Use subtle, soft shadows (rgba(0,0,0,0.05) 0px 0px 0px 1px) only for interactive elements, not for static cards or surfaces.

### Don't
- Do not use dark backgrounds for full sections; maintain the light theme with White Canvas (#ffffff) as the dominant background.
- Avoid generic system fonts; always utilize 'saans' for headings and 'Inter' for body text with their specified font features and letter spacing.
- Do not introduce strong, opaque borders on cards or primary layout elements; rely on subtle background differences or soft washes.
- Refrain from using multiple accent colors; Lens Teal (#00caa0) and Mint Green (#00d743) are the only acceptable chromatic accents.
- Do not use a narrow page width; layout should be full-bleed or extend to edge-to-edge, with content typically centered.
- Avoid heavy drop shadows or multiple shadow layers, as the design uses minimal, single-layer outlines.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#ffffff` | Primary page background |
| 2 | Subtle Card Surface | `#fbfcff` | Background for feature cards, providing a very slight visual lift from the canvas |

## Agent Prompt Guide

Quick Color Reference:
text: #2c2d30
background: #ffffff
border: #afafaf
accent: #00caa0
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

Create an Informative Card: background rgb(251, 251, 251), 16px border-radius, 24px padding. Headline text (saans weight 500, 26px, Charcoal Black). Body text (Inter weight 400, 16px, Charcoal Black).

Create a Feature Highlight Card: background rgba(45, 45, 48, 0.02), 24px border-radius, 32px padding, no shadow. Include a Circular Icon Wrapper (#00d743 with 12% opacity, 50% border-radius) containing a simple icon (Charcoal Black fill).

## Similar Brands

- **Optimism** — Shares a clean, light aesthetic with a single prominent accent color for interactive elements and abstract background graphics.
- **Arbitrum** — Employs an open layout, soft, abstract visuals, and a focused color palette primarily on light backgrounds.
- **Base** — Exhibits a similar use of spacious white layouts, minimal UI, and soft, understated graphic elements to convey technical sophistication.
- **Zora** — Features a light theme, strong typography contrast, and subtle, playful graphical elements integrated with clear content blocks.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-lens-teal: #00caa0;
  --color-mint-green: #00d743;
  --color-charcoal-black: #2c2d30;
  --color-cool-gray: #afafaf;
  --color-white-canvas: #ffffff;
  --color-slate-subtle: #808183;
  --color-light-steel: #c0c0c1;
  --color-subtle-card-bkg: #fbfcff;

  /* Typography — Font Families */
  --font-saans: 'saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.14px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.24px;
  --text-subheading: 21px;
  --leading-subheading: 1.35;
  --tracking-subheading: 0.315px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.39px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: 0.42px;
  --text-display: 46px;
  --leading-display: 1.2;
  --tracking-display: 0.69px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-152: 152px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 0px;
  --radius-buttons: 50px;
  --radius-navitems: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-2: color(display-p3 0.172549 0.176471 0.188235 / 0.02) 0px 0px 0px 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-subtle-card-surface: #fbfcff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-lens-teal: #00caa0;
  --color-mint-green: #00d743;
  --color-charcoal-black: #2c2d30;
  --color-cool-gray: #afafaf;
  --color-white-canvas: #ffffff;
  --color-slate-subtle: #808183;
  --color-light-steel: #c0c0c1;
  --color-subtle-card-bkg: #fbfcff;

  /* Typography */
  --font-saans: 'saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.14px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.24px;
  --text-subheading: 21px;
  --leading-subheading: 1.35;
  --tracking-subheading: 0.315px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.39px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: 0.42px;
  --text-display: 46px;
  --leading-display: 1.2;
  --tracking-display: 0.69px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-152: 152px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-2: color(display-p3 0.172549 0.176471 0.188235 / 0.02) 0px 0px 0px 0px;
}
```
