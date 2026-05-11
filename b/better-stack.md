# Better Stack — Style Reference
> Deep space console

**Theme:** dark

Better Stack employs a 'deep space console' aesthetic, built on a dark, near-black canvas layered with subtly differentiated dark gray surfaces. Typography is compact and precise, maintaining excellent contrast. A single vivid violet hue provides functional accents for interactive elements and brand highlights, creating moments of focus within the muted interface. Components are lightweight with large border radii, suggesting touch-friendly forms on a data-dense, technical interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Abyss | `#0f101a` | `--color-midnight-abyss` | Primary page background, base surface for links, darkest tone in the UI |
| Graphite Panel | `#151621` | `--color-graphite-panel` | Default button background, card backgrounds, and slightly elevated surfaces |
| Steel Overlay | `#1f2433` | `--color-steel-overlay` | Input borders, card borders, and subtle separating lines |
| Faded Steel | `#262935` | `--color-faded-steel` | Outlined button borders, secondary dividers |
| Muted Ash | `#646e87` | `--color-muted-ash` | Faded secondary text, ghost button text, decorative icons |
| Ash Text | `#939db8` | `--color-ash-text` | Primary text color for body copy, interactive states for text elements, and default borders |
| Cloud Whisper | `#c9d3ee` | `--color-cloud-whisper` | Navigation text, crisp text in low-contrast areas, button hover states, icon strokes |
| Pure White | `linear-gradient(165deg, rgb(255, 255, 255) 10.57%, rgb(147, 157, 184) 142.07%)` | `--color-pure-white` | Headline text, high-contrast text elements, input text; Subtle background texture or element fill for cards or graphic elements |
| Zero Black | `#000000` | `--color-zero-black` | Icon fills in certain contexts, part of shadow definitions |
| Focus Violet | `#98a4f7` | `--color-focus-violet` | Brand accent color for links, borders of interactive elements, and key highlights. Creates visual attention against the dark neutrals |
| Blue Violet Gradient | `linear-gradient(353deg, rgb(91, 99, 211) 17.51%, rgb(124, 135, 247) 183.08%)` | `--color-blue-violet-gradient` | Decorative gradient for headers or significant visual elements |

## Tokens — Typography

### Helvetica Now Text — Versatile text font used for body copy, navigation, buttons, and most UI elements. Its compact metrics and varied weights provide clarity and efficiency in a data-rich environment. · `--font-helvetica-now-text`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 20px, 28px, 36px
- **Line height:** 1.00, 1.08, 1.17, 1.20, 1.45, 1.50, 1.55, 1.60, 1.85
- **Letter spacing:** -0.01
- **OpenType features:** `"ss01" on, "ss03" on, "ss04" on, "ss19" on`
- **Role:** Versatile text font used for body copy, navigation, buttons, and most UI elements. Its compact metrics and varied weights provide clarity and efficiency in a data-rich environment.

### Helvetica Now Display — Used for prominent page headlines and key visual statements. Its display-specific optimizations enhance readability and visual impact at larger sizes, maintaining a precise, engineering-like aesthetic. · `--font-helvetica-now-display`
- **Substitute:** Inter
- **Weights:** 500, 700
- **Sizes:** 40px, 53px
- **Line height:** 1.08, 1.10
- **Letter spacing:** -0.01
- **OpenType features:** `"salt" on, "ss02" on, "ss01" on, "ss03" on, "ss04" on, "ss19" on`
- **Role:** Used for prominent page headlines and key visual statements. Its display-specific optimizations enhance readability and visual impact at larger sizes, maintaining a precise, engineering-like aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.6 | — | `--text-body-lg` |
| subheading | 20px | 1.55 | -0.2px | `--text-subheading` |
| heading | 28px | 1.17 | -0.28px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.36px | `--text-heading-lg` |
| display | 53px | 1.08 | -0.53px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 128 | 128px | `--spacing-128` |
| 164 | 164px | `--spacing-164` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 10px |
| buttons | 9999px |
| dialogs | 16px |
| general | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.25) 0px 1px 3px 0px inset` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1320px
- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Button

Filled button for primary actions. Background: Graphite Panel (#151621), Text: Ash Text (#939db8). Padding: 12px vertical, 24px horizontal. Border radius: 9999px. No shadow.

### Ghost Button
**Role:** Button

Ghost button for secondary actions. Background: transparent. Text: Muted Ash (#646e87). Padding: 8px vertical, 6px horizontal. No border or radius defined, implies square edges unless contextually inherited.

### Small Pill Button
**Role:** Button

Small, rounded ghost button with transparent background, Cloud Whisper (#c9d3ee) text, and a 10px border radius. Padding: 0px vertical, 24px horizontal. No shadow.

### Accent Outlined Button
**Role:** Button

Outlined button often used for accent links or calls to action. Background: transparent. Border: 1px solid Focus Violet (#98a4f7). Text: Focus Violet (#98a4f7). Padding: 12px vertical, 24px horizontal. Border radius: 9999px.

### Informative Card
**Role:** Card

Standard content card. Background: Graphite Panel (#151621). Border radius: 16px. Padding: 20px on all sides. No shadow.

### Input Field
**Role:** Input

Input field with a subtle dark background and white text. Background: rgba(0.594223, 0.00140271, -0.0566696, 0.1) which is near-black with 10% opacity. Border: 1px solid Steel Overlay (#1f2433). Text: Pure White (#ffffff). Border radius: 12px. Padding: 0px vertical, 20px horizontal.

## Do's and Don'ts

### Do
- Maintain a clear visual hierarchy by layering neutral background colors: Midnight Abyss (#0f101a) for base, Graphite Panel (#151621) for cards, and Steel Overlay (#1f2433) for borders.
- Use Focus Violet (#98a4f7) sparingly and strategically for brand accents, links, and active states to guide user attention within the dark UI.
- Adopt the rounded, pill-shaped '9999px' border radius for all actionable buttons to ensure a consistent, friendly form.
- Apply Helvetica Now Text font with a -0.01em letter-spacing consistently across all body and UI elements for a compact, technical feel.
- Center-align primary headlines and section titles, especially in full-width hero sections, to create a strong focal point.
- Utilize a base spacing unit of 4px to maintain consistent density and alignment across all components and layouts.
- Implement the linear blue-violet gradient (linear-gradient(353deg, rgb(91, 99, 211) 17.51%, rgb(124, 135, 247) 183.08%)) only for major decorative elements like hero backgrounds or section separators to prevent visual noise.

### Don't
- Avoid using saturated chromatic colors other than Focus Violet (#98a4f7) unless those colors are explicitly for semantic status indicators.
- Do not introduce strong drop shadows; rely on subtle inset shadows (rgba(255, 255, 255, 0.25) 0px 1px 3px 0px inset) or border differences for elevation.
- Do not deviate from the established type scale; maintain the precise letter-spacing and line heights for a consistent typographic rhythm.
- Do not use sharp 0px border radii on interactive elements or cards; the system prioritizes soft, rounded shapes.
- Avoid large, impactful photos or illustrations that break the product's dark, UI-focused aesthetic; prioritize product screenshots and abstract visuals.
- Do not use generic, default blue link colors; ensure all links are styled with Focus Violet (#98a4f7) or Cloud Whisper (#c9d3ee) for consistent branding.
- Refrain from using complex, multi-color decorative gradients casually; reserve them for impactful moments where their presence enhances, not distracts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Abyss | `#0f101a` | Base page and deepest background surface |
| 1 | Graphite Panel | `#151621` | Default background for cards and interactive components, slightly elevated from the base |
| 2 | Steel Overlay | `#1f2433` | Input field borders, providing subtle depth and separation for interactive elements |

## Elevation

- **Nav, Button:** `inset 0px 1px 3px 0px rgba(255, 255, 255, 0.25)`

## Imagery

Imagery is functional and product-focused, primarily consisting of dark-themed UI screenshots that showcase the Better Stack platform. These embeds are contained within cards or placed alongside text. Iconography is minimalist, often monochrome or in Cloud Whisper (#c9d3ee), with clear, outlined styles, appearing at a small to medium stroke weight. No full-bleed photography or complex illustrations are present. The density of imagery is low, with visuals serving explanatory roles rather than decorative atmosphere, letting the UI and typography dominate.

## Layout

The page maintains a max-width of 1320px, with content consistently centered. The hero section is full-bleed with a dark background, featuring a prominent, centered headline and a call to action immediately below. Subsequent sections typically follow a 2-column or text-left/image-right alternating pattern. Vertical rhythm is established by consistent section gaps, with elements frequently grouped into cards that receive 20px of padding. Navigation is a persistent top bar, sticky on scroll, with clear text links.

## Agent Prompt Guide

Quick Color Reference:
text: #939db8
background: #0f101a
border: #1f2433
accent: #98a4f7
primary action: #151621 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #151621 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design an Informative Card: background Graphite Panel (#151621), 16px border radius, 20px padding. Inside, place a heading (Helvetica Now Display, 40px, weight 500, Pure White (#ffffff)) and body text (Helvetica Now Text, 14px, weight 400, Ash Text (#939db8)).
3. Render an Input Field: background rgba(0.594223, 0.00140271, -0.0566696, 0.1), border 1px solid Steel Overlay (#1f2433), text Pure White (#ffffff), 12px border radius, 0px vertical 20px horizontal padding.

## Similar Brands

- **Linear** — Dark UI, focus on structured data, subtle elevation, and a minimalist typographic approach with a single accent color.
- **Vercel** — Technical, dark-themed interface with clean typography, restrained use of color for functional highlights, and a focus on product screenshots.
- **Supabase** — Developer-centric dark mode emphasizing data and code, compact information density, and subtle branding through UI elements.
- **Stripe (dark mode)** — Sophisticated dark theme, precise typography, a strong focus on data visualization, and components designed for internal tool-like functionality.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-abyss: #0f101a;
  --color-graphite-panel: #151621;
  --color-steel-overlay: #1f2433;
  --color-faded-steel: #262935;
  --color-muted-ash: #646e87;
  --color-ash-text: #939db8;
  --color-cloud-whisper: #c9d3ee;
  --color-pure-white: #ffffff;
  --gradient-pure-white: linear-gradient(165deg, rgb(255, 255, 255) 10.57%, rgb(147, 157, 184) 142.07%);
  --color-zero-black: #000000;
  --color-focus-violet: #98a4f7;
  --color-blue-violet-gradient: #5b63d3;
  --gradient-blue-violet-gradient: linear-gradient(353deg, rgb(91, 99, 211) 17.51%, rgb(124, 135, 247) 183.08%);

  /* Typography — Font Families */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.55;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --tracking-heading: -0.28px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 53px;
  --leading-display: 1.08;
  --tracking-display: -0.53px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-128: 128px;
  --spacing-164: 164px;
  --spacing-192: 192px;

  /* Layout */
  --page-max-width: 1320px;
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 26px;
  --radius-3xl-2: 43px;
  --radius-full: 200px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 10px;
  --radius-buttons: 9999px;
  --radius-dialogs: 16px;
  --radius-general: 10px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.25) 0px 1px 3px 0px inset;

  /* Surfaces */
  --surface-midnight-abyss: #0f101a;
  --surface-graphite-panel: #151621;
  --surface-steel-overlay: #1f2433;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-abyss: #0f101a;
  --color-graphite-panel: #151621;
  --color-steel-overlay: #1f2433;
  --color-faded-steel: #262935;
  --color-muted-ash: #646e87;
  --color-ash-text: #939db8;
  --color-cloud-whisper: #c9d3ee;
  --color-pure-white: #ffffff;
  --color-zero-black: #000000;
  --color-focus-violet: #98a4f7;
  --color-blue-violet-gradient: #5b63d3;

  /* Typography */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.55;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --tracking-heading: -0.28px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 53px;
  --leading-display: 1.08;
  --tracking-display: -0.53px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-128: 128px;
  --spacing-164: 164px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 26px;
  --radius-3xl-2: 43px;
  --radius-full: 200px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.25) 0px 1px 3px 0px inset;
}
```
