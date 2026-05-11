# Vanmoof — Style Reference
> monochrome canvas, functional red accents

**Theme:** light

VanMoof's design system relies on a stark, contemporary aesthetic, leveraging a predominantly monochrome palette to emphasize product visuals. Components are lightweight and often outlined, with minimal elevation, creating a sense of understated sophistication. Typography is precise and utilitarian, giving an authoritative yet accessible feel. The overall presentation prioritizes directness and clarity, allowing product design and functional accents to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces, primary text on dark backgrounds |
| Ghost Gray | `#e5e7eb` | `--color-ghost-gray` | Subtle UI borders, ghost button outlines, secondary surface backgrounds, and dividers. This is the dominant neutral |
| Carbon Black | `#222222` | `--color-carbon-black` | Primary text, solid button backgrounds for actions, iconography, and strong borders |
| Inkwell | `#000000` | `--color-inkwell` | Strongest textual elements, high-contrast links, and critical headings |
| Deep Slate | `#313131` | `--color-deep-slate` | Secondary text, subtle link hover states, and lighter body text |
| Light Gray | `#e0e0e0` | `--color-light-gray` | Minor background tints, subtle separators |
| Ignition Red | `#ff0000` | `--color-ignition-red` | Product highlights (e.g., bike tail light in hero, map pins) — a rare, high-impact accent for key focal points. (Inferred from screenshot) |

## Tokens — Typography

### Unica77LLWeb — Primary typeface for all UI elements, headings, body text, and links. Its broad range of weights and sizes supports a hierarchical and precise content presentation. · `--font-unica77llweb`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 32px, 48px, 80px, 280px
- **Line height:** 1.00, 1.10, 1.33, 1.43, 1.50, 1.56
- **Letter spacing:** normal
- **Role:** Primary typeface for all UI elements, headings, body text, and links. Its broad range of weights and sizes supports a hierarchical and precise content presentation.

### Unica77Mono — Used for specific, technical-oriented body text and navigation labels; provides a contrasting structured feel to the primary typeface. · `--font-unica77mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for specific, technical-oriented body text and navigation labels; provides a contrasting structured feel to the primary typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.43 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 32px | 1.1 | — | `--text-heading` |
| heading-lg | 48px | 1.1 | — | `--text-heading-lg` |
| display-sm | 80px | 1.1 | — | `--text-display-sm` |
| display-lg | 280px | 1 | — | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| default | 2px |

### Layout

- **Section gap:** 24px
- **Card padding:** 8px
- **Element gap:** 8px

## Components

### Ghost Outline Button (Light)
**Role:** Secondary action button

Transparent background with a 1px #e5e7eb border and #222222 text. Used for subtle actions against light backgrounds. Radius: 2px. No explicit padding in component definition, relies on text padding for sizing.

### Ghost Outline Button (Dark)
**Role:** Secondary action button on dark sections

Transparent background with a 1px #e5e7eb border and #ffffff text. Used for subtle actions against dark backgrounds. Radius: 4px. No explicit padding in component definition, relies on text padding for sizing.

### Primary Filled Button
**Role:** Primary action button

Solid #222222 background with #ffffff text. Used for critical calls to action. Radius: 4px. No explicit padding in component definition, relies on text padding for sizing.

### Product Feature Card
**Role:** Informational display

#eeeeee background, 8px border-radius, no shadow. Padding varies by content, but generally has a top padding of 80px. Used for displaying feature highlights with iconography and text.

### Navigation Link
**Role:** Primary navigation item

#000000 text on transparent background, no border. Text uses Unica77LLWeb weight 400 at 16px.

### Mobile Navbar Item Toggle
**Role:** Mobile menu button

Transparent background with #e5e7eb border and #222222 text, 2px radius.

### Mini Select Country Button
**Role:** Header utility action

Solid #222222 background, #ffffff text, 4px border-radius. Compact button for utility actions.

## Do's and Don'ts

### Do
- Use '#222222' for all primary text and button backgrounds against light canvases.
- Apply '#e5e7eb' as the default border color for all ghost buttons and subtle UI dividers.
- Maintain a clear hierarchical order in typography, using the Unica77LLWeb family for headings (e.g., 280px, 80px) and body text (e.g., 14px, 16px).
- Ensure all interactive elements and cards use a 2px or 8px border-radius, prioritizing 2px for smaller interactive elements like buttons.
- Utilize 'Ignition Red' (#ff0000) only for specific, high-impact product accents or critical status indicators, never for general UI.
- Structure page sections with a '24px' vertical gap between major content blocks to ensure breathing room.
- Employ a base spacing unit of '8px' for padding and gaps between smaller elements within components.

### Don't
- Avoid using multiple chromatic colors; limit color accents strictly to 'Ignition Red' for product highlights.
- Do not introduce complex shadows; maintain a flat or minimally elevated visual style.
- Refrain from using decorative gradients on UI elements; the system prefers solid colors and clean outlines.
- Do not deviate from the specified Unica77LLWeb and Unica77Mono font families; no system fonts are permitted.
- Avoid excessive imagery; when present, it should be high-contrast and product-focused, complementing the monochrome UI.
- Do not use generic button styles; always adhere to the Ghost Outline (Light/Dark) or Primary Filled button specifications.
- Never use radii other than 2px or 8px; custom or interpolated corner rounding is not permitted.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default content areas. |
| 2 | Ghost Gray | `#e5e7eb` | Secondary background areas, subtle panels, and content blocks (e.g., feature cards). |
| 3 | Carbon Black | `#222222` | Accentuated section backgrounds, especially in hero areas, and primary button fills. |

## Imagery

Product photography dominates, featuring tight crops of e-bikes against deep, contrasting monochrome backgrounds (often dark gray/black or white). The imagery is highly stylized, showcasing specific design details and technological features. There is a strong emphasis on the product itself, with minimal lifestyle context. Icons are outlined, minimal, and monochromatic, matching the overall UI's clean aesthetic. Imagery functions primarily as product showcase and explanatory content, occupying significant visual space in hero sections but contained in feature blocks.

## Layout

The page primarily uses a max-width contained layout for most content sections, though hero sections often extend full-bleed with product imagery. The hero pattern frequently features a large, dramatic product shot with expansive typography (e.g., 'S6', 'A5') and overlaid, constrained text blocks and ghost buttons. Section rhythm is marked by consistent vertical spacing (24px `sectionGap`) and often alternates between full-bleed dark product showcases and lighter, contained content blocks. Content is arranged in flexible patterns, including centered stacks for app features and multi-column grids for testimonials or support information. Navigation is a minimalist sticky header with a prominent brand logo, hamburger menu, and cart icon, emphasizing a distraction-free browsing experience.

## Agent Prompt Guide

Quick Color Reference:
text: #222222
background: #ffffff
border: #e5e7eb
accent: #ff0000
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: full-bleed dark gray background. Headline 'S6' at 280px Unica77LLWeb weight 400, #ffffff. Subtext 'The wait’s over. Introducing our ultimate e-bike.' at 16px Unica77LLWeb weight 400, #ffffff, line-height 1.5.
Create a secondary ghost button: 'Explore' text at 14px Unica77LLWeb weight 400, #222222, 1px solid #e5e7eb border, 2px radius, transparent background.
Create a product feature card: '#eeeeee' background, 8px border-radius, top padding 80px, #222222 text at 14px Unica77LLWeb weight 400, line-height 1.5. Include a monochromatic outlined icon.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
Create a main navigation link: 'Products' text at 16px Unica77LLWeb weight 400, #000000, transparent background.

## Similar Brands

- **Cowboy E-bikes** — Similar focus on premium product photography, minimalist UI, and a predominantly monochrome palette accentuating the bikes.
- **Tesla** — Emphasizes product design through stark, high-contrast imagery, large typography, and a clean, direct visual language.
- **Stripe** — Utilizes a highly structured, monochrome interface with precise typography and subtle border treatments for a professional, understated feel.
- **Apple** — Clean, product-centric aesthetic featuring strong photography, ample whitespace, and a focus on premium materials and functional simplicity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghost-gray: #e5e7eb;
  --color-carbon-black: #222222;
  --color-inkwell: #000000;
  --color-deep-slate: #313131;
  --color-light-gray: #e0e0e0;
  --color-ignition-red: #ff0000;

  /* Typography — Font Families */
  --font-unica77llweb: 'Unica77LLWeb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-unica77mono: 'Unica77Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 80px;
  --leading-display-sm: 1.1;
  --text-display-lg: 280px;
  --leading-display-lg: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 8px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-default: 2px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ghost-gray: #e5e7eb;
  --surface-carbon-black: #222222;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghost-gray: #e5e7eb;
  --color-carbon-black: #222222;
  --color-inkwell: #000000;
  --color-deep-slate: #313131;
  --color-light-gray: #e0e0e0;
  --color-ignition-red: #ff0000;

  /* Typography */
  --font-unica77llweb: 'Unica77LLWeb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-unica77mono: 'Unica77Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 80px;
  --leading-display-sm: 1.1;
  --text-display-lg: 280px;
  --leading-display-lg: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
}
```
