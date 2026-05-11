# Tech Barcelona — Style Reference
> High-contrast geometric blueprint

**Theme:** light

Tech Barcelona uses a bold and graphic black-and-white canvas, punctuated by a single vibrant blue accent. The typography is compact and confident, primarily utilizing a light-weight sans-serif for both headings and body text, establishing an authoritative yet accessible tone. Components are sharp and unfussy, favoring crisp borders and minimal elevation over elaborate styling, with a strong emphasis on a clear, almost monochromatic visual hierarchy that directs attention to key information and interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, deep surface backgrounds, strong borders — establishing a high-contrast foundation for content |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, surface accents, white text on dark backgrounds, ghost button borders |
| Ink Text | `#212529` | `--color-ink-text` | Secondary text, dark navigation links, default icon fills, default button borders |
| Light Gray Divider | `#cccccc` | `--color-light-gray-divider` | Subtle borders, dividers, ghost button borders in light contexts |
| Headline Black | `#090707` | `--color-headline-black` | Dominant headlines, large text blocks for brand emphasis |
| Ice Blue Accent | `#0075ff` | `--color-ice-blue-accent` | Primary action buttons, interactive highlights, navigational indicators — providing a vivid, singular point of interest |
| Shadow White | `#eeeeee` | `--color-shadow-white` | Subtle button shadow, hinting at minimal elevation |

## Tokens — Typography

### FavoritPro-Light — The primary typeface for all text elements. The consistently light weight (400) across all sizes creates a refined, understated authority, resisting the common tendency to use bold weights for emphasis. · `--font-favoritpro-light`
- **Substitute:** Open Sans, Arial
- **Weights:** 400
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 20px, 22px, 50px, 80px
- **Line height:** 1.00, 1.14, 1.15, 1.20, 1.30, 1.33, 1.50, 1.59
- **Letter spacing:** -0.045em at 80px, -0.010em at 50px, 0.080em at 14px, 0.090em at 12px
- **Role:** The primary typeface for all text elements. The consistently light weight (400) across all sizes creates a refined, understated authority, resisting the common tendency to use bold weights for emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.9px | `--text-caption` |
| body | 14px | 1.5 | 0.08px | `--text-body` |
| heading-sm | 18px | 1.33 | — | `--text-heading-sm` |
| heading | 20px | 1.2 | — | `--text-heading` |
| heading-lg | 22px | 1.15 | — | `--text-heading-lg` |
| display | 50px | 1.14 | -0.01px | `--text-display` |
| display-xl | 80px | 1 | -0.045px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 23 | 23px | `--spacing-23` |
| 25 | 25px | `--spacing-25` |
| 32 | 32px | `--spacing-32` |
| 35 | 35px | `--spacing-35` |
| 50 | 50px | `--spacing-50` |
| 143 | 143px | `--spacing-143` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(238, 238, 238) 1px 1px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 50px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action.

Filled with Ice Blue Accent (#0075ff), text in Canvas White (#ffffff). Padding of 16px top, 27px right, 17px bottom, 28px left. No border radius.

### Ghost Bordered Button
**Role:** Secondary action button with a border and transparent background.

Transparent background, text in Canvas White (#ffffff). Border is 1px solid Canvas White (#ffffff). Padding of 5px top, 10px right, 5px bottom, 10px left. No border radius.

### Text Link Button
**Role:** Tertiary action or navigational link styled as a button.

Transparent background, text in Ink Text (#212529). Border is 1px solid Ink Text (#212529) only on the bottom. No padding or border radius.

### White Text Link Button
**Role:** Text link for navigation or small actions on dark backgrounds.

Transparent background, text in Canvas White (#ffffff). No border or padding specified, implying inline link styling.

### Muted Card
**Role:** Container for content, particularly news items.

Transparent background, no shadow, no border radius. Implied padding is 0px.

## Do's and Don'ts

### Do
- Prioritize high-contrast combinations using Midnight Ink (#000000), Canvas White (#ffffff), and Ink Text (#212529) for all textual content to maintain strong legibility.
- Utilize Ice Blue Accent (#0075ff) exclusively for primary calls to action or key interactive states, ensuring it remains a distinct highlight.
- Maintain sharp, 0px border radii for all components, including buttons and cards, to reinforce the geometric and precise aesthetic.
- Employ FavoritPro-Light (weight 400) for all typography, adjusting font size instead of weight for hierarchy, following the established type scale.
- Apply the subtle Shadow White (#eeeeee) box shadow (1px 1px 0px 0px) to interactive elements like buttons to provide slight depth without heavy elevation.
- Use Light Gray Divider (#cccccc) for hairline borders and subtle separations, offering visual breaks without introducing strong contrast.

### Don't
- Avoid using multiple accent colors; Ice Blue Accent (#0075ff) is the sole chromatic highlight.
- Do not introduce rounded corners; all elements should adhere to the 0px border-radius.
- Refrain from using bold or heavy font weights for emphasis; leverage letter spacing and size from the type scale instead.
- Do not apply drop shadows to cards or general surfaces; reserve soft shadows for interactive elements as defined.
- Avoid decorative gradients or complex backgrounds; maintain a flat, high-contrast, black-and-white base.
- Do not use padding less than 10px for button content, unless it is a purely text-based link button.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and light surface areas. |
| 2 | Content Black | `#000000` | Dominant background for main content blocks, high-contrast sections. |

## Elevation

- **Button:** `rgb(238, 238, 238) 1px 1px 0px 0px`

## Imagery

This design system uses a minimalist approach to imagery, primarily employing the brand's geometric, QR-code-like logo as a decorative background element or prominent identifier. Photography is used sparingly and appears to be real-world architectural shots, acting as contextual backdrops rather than focal points. Icons are monochrome, simple, and functional, likely either filled or outlined with a fine stroke, adhering to the stark black-and-white aesthetic. Imagery serves primarily as atmospheric context or brand reinforcement, with a very high textual density across the site.

## Layout

The page primarily uses a max-width contained layout, though the hero section can be full-bleed with a large, centered headline against a dark background or with an architectural image. Sections exhibit strong vertical rhythm with consistent spacing, often alternating between dark (Midnight Ink) and light (Canvas White) backgrounds. Content is organized in clear, stacked blocks and implicit two-column layouts where text and visuals interact. Navigation is confined to a persistent top bar featuring minimal links and a high-contrast 'Join Us' button.

## Agent Prompt Guide

Quick Color Reference:
text: #212529
background: #ffffff
border: #cccccc
accent: #0075ff
primary action: #0075ff (filled action)

Example Component Prompts:
Create a Primary Action Button: #0075ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a navigation item: White Text Link Button with text 'Community', Canvas White (#ffffff), 14px FavoritPro-Light, 0.08em letter spacing.
Create a content card for a featured story: Muted Card with a Midnight Ink (#000000) background. Heading at 22px FavoritPro-Light, Canvas White (#ffffff). Body text at 14px FavoritPro-Light, Canvas White (#ffffff). Add a Light Gray Divider (#cccccc) as a bottom border to separate from other elements.

## Similar Brands

- **Stripe** — Monochromatic approach with a single, clear accent color and strong typographic hierarchy.
- **Linear** — Emphasis on high contrast, clean lines, and a structured, functional aesthetic without decorative elements.
- **GitHub** — Code-editor like clarity, high information density, and precise use of typography and subtle borders.
- **Vercel** — Minimalist design with a focus on core content, clear interactive elements, and a stark black/white palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-ink-text: #212529;
  --color-light-gray-divider: #cccccc;
  --color-headline-black: #090707;
  --color-ice-blue-accent: #0075ff;
  --color-shadow-white: #eeeeee;

  /* Typography — Font Families */
  --font-favoritpro-light: 'FavoritPro-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.9px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.33;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 22px;
  --leading-heading-lg: 1.15;
  --text-display: 50px;
  --leading-display: 1.14;
  --tracking-display: -0.01px;
  --text-display-xl: 80px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.045px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-32: 32px;
  --spacing-35: 35px;
  --spacing-50: 50px;
  --spacing-143: 143px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Named Radii */
  --radius-default: 0px;

  /* Shadows */
  --shadow-subtle: rgb(238, 238, 238) 1px 1px 0px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-content-black: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-ink-text: #212529;
  --color-light-gray-divider: #cccccc;
  --color-headline-black: #090707;
  --color-ice-blue-accent: #0075ff;
  --color-shadow-white: #eeeeee;

  /* Typography */
  --font-favoritpro-light: 'FavoritPro-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.9px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.33;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 22px;
  --leading-heading-lg: 1.15;
  --text-display: 50px;
  --leading-display: 1.14;
  --tracking-display: -0.01px;
  --text-display-xl: 80px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.045px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-32: 32px;
  --spacing-35: 35px;
  --spacing-50: 50px;
  --spacing-143: 143px;

  /* Shadows */
  --shadow-subtle: rgb(238, 238, 238) 1px 1px 0px 0px;
}
```
