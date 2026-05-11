# June — Style Reference
> Whiteboard with purple ink

**Theme:** light

June presents a clean, approachable SAAS aesthetic built on a foundation of white space and subtle surface variations. Typography, primarily SF Pro Rounded, strikes a balance between professional clarity and a hint of friendly roundness. A single vivid violet accent color is used sparingly to highlight key information and interactive elements, creating points of visual interest without overwhelming the interface. Components are lightweight with soft shadows and rounded corners, conveying a sense of digital product, not corporate rigidity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fafafa` | `--color-canvas-white` | Primary page background, often paired with darker text elements for strong contrast. Provides an airy, open feel |
| Cloud Gray | `#e9ecef` | `--color-cloud-gray` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Haze White | `#f0f0fe` | `--color-haze-white` | Secondary surface background, used for lifted cards or content blocks to create a subtle depth layer on the Canvas White |
| Inkwell Text | `#151531` | `--color-inkwell-text` | Primary body text, link text, and prominent content. Provides high readability against light backgrounds |
| Midnight Violet | `#2a2a63` | `--color-midnight-violet` | Headings and bolder text elements. Also appears as a border color, adding emphasis |
| Shadow Blue-Gray | `#343a40` | `--color-shadow-blue-gray` | Secondary text, muted helper text, and subtle icon coloring. Provides a softer textual contrast than Inkwell Text |
| Purple Accent | `#6868f7` | `--color-purple-accent` | The primary brand accent, used for prominent cards, or occasionally as a decorative background flourish. Creates a vibrant, technology-focused impression |
| Cloud Shadow | `#cfd0d1` | `--color-cloud-shadow` | Light shadow tint, contributes to elevation effects for cards |
| Soft Shadow | `#c3c4c6` | `--color-soft-shadow` | Slightly deeper shadow tint, used in combination with Cloud Shadow for card elevation |

## Tokens — Typography

### SF Pro Rounded — Primary user interface typeface. Its rounded terminals provide a friendly yet modern feel. Used for all headings, body text, and UI elements. The wide range of weights supports a clear typographic hierarchy. · `--font-sf-pro-rounded`
- **Substitute:** Avenir Next Rounded
- **Weights:** 400, 700, 900
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 40px, 60px
- **Line height:** 1.00, 1.17, 1.19, 1.25, 1.43, 1.50, 1.56
- **Letter spacing:** -0.015em at 12-14px, 0.025em for other sizes
- **OpenType features:** `"kern"`
- **Role:** Primary user interface typeface. Its rounded terminals provide a friendly yet modern feel. Used for all headings, body text, and UI elements. The wide range of weights supports a clear typographic hierarchy.

### Inter — Used for specific secondary content or as a fallback. Maintains readability with a more standard, geometric sans-serif quality. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 16px
- **Line height:** 1.00, 1.50
- **Letter spacing:** normal
- **OpenType features:** `"kern"`
- **Role:** Used for specific secondary content or as a fallback. Maintains readability with a more standard, geometric sans-serif quality.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.18px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.21px | `--text-body-sm` |
| body | 16px | 1.5 | 0.4px | `--text-body` |
| subheading | 18px | 1.56 | 0.45px | `--text-subheading` |
| heading | 24px | 1.5 | 0.6px | `--text-heading` |
| heading-lg | 40px | 1.25 | 1px | `--text-heading-lg` |
| display | 60px | 1 | 1.5px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| prominentCard | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(13, 19, 27, 0.1) 0px 2px 10px 0px, rgba(13, 19, 27, ...` | `--shadow-md` |
| subtle | `rgba(13, 19, 27, 0.05) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(13, 19, 27, 0.25) 0px 0px 1px 0px, rgba(13, 19, 27, ...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 24-80px
- **Card padding:** 48px
- **Element gap:** 24px

## Components

### Navigation Link
**Role:** Global navigation item

Text uses Inkwell Text at 16px. Border appears underneath on hover with Cloud Gray. Element gap of 8px to adjacent items.

### Subtle Elevated Card
**Role:** Content container for secondary information

Background is Canvas White, with a 12px border radius. Shadows are soft: rgba(13, 19, 27, 0.1) 0px 2px 10px 0px, rgba(13, 19, 27, 0.2) 0px 0px 2px 0px. No internal padding specified, implying content manages its own spacing.

### Default Content Card
**Role:** Primary content container within sections

Background is Haze White, with a 12px border radius. Features an inset shadow: rgba(13, 19, 27, 0.05) 0px 0px 0px 1px inset. Provides substantial internal padding of 48px on all sides.

### Prominent Accent Card
**Role:** Highlighting key messages or calls to action

Features a solid Purple Accent background with a larger 20px border radius. Accompanied by a soft, diffused shadow: rgba(13, 19, 27, 0.25) 0px 0px 1px 0px, rgba(13, 19, 27, 0.05) 0px 2px 1px 0px. Generous internal padding of 64px on all sides.

### Signature Line Divider
**Role:** Used in the 'The June Team' section for visual separation

These are effectively decorative images of signatures acting as visual dividers, implying personalized connection.

## Do's and Don'ts

### Do
- Prioritize SF Pro Rounded for all text elements to maintain brand consistency and friendliness.
- Use Canvas White (#fafafa) as the dominant background for all main page canvases.
- Apply Haze White (#f0f0fe) for lifted content cards to create subtle differentiation and hierarchy.
- Employ Cloud Gray (#e9ecef) exclusively for borders and subtle dividers, avoiding heavy outlines.
- Reserve Purple Accent (#6868f7) for high-impact cards or crucial interactive states, ensuring it stands out.
- Maintain generous padding of 48px for default content cards and 64px for prominent accent cards.
- Utilize 12px border radius for most cards and 20px for high-attention accent cards.

### Don't
- Avoid using multiple chromatic colors; stick to Purple Accent as the primary brand color.
- Do not introduce strong, heavy borders; prefer subtle Cloud Gray or soft shadow emphasis.
- Do not deviate from the SF Pro Rounded typeface for headings or primary body text.
- Avoid sharp corners on components; use 12px or 20px radii for all card-like elements.
- Do not use dark backgrounds for large sections of content; maintain the light theme dominance.
- Avoid heavy or complex shadow effects; stick to the specified soft, subtle card shadows.
- Do not adjust letter-spacing on elements outside of the specified values provided for SF Pro Rounded sizes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fafafa` | Base page background |
| 1 | Haze White | `#f0f0fe` | Default slightly elevated card backgrounds |
| 2 | Purple Accent | `#6868f7` | Prominent accent cards |

## Elevation

- **Subtle Elevated Card:** `rgba(13, 19, 27, 0.1) 0px 2px 10px 0px, rgba(13, 19, 27, 0.2) 0px 0px 2px 0px`
- **Default Content Card (inset):** `rgba(13, 19, 27, 0.05) 0px 0px 0px 1px inset`
- **Prominent Accent Card:** `rgba(13, 19, 27, 0.25) 0px 0px 1px 0px, rgba(13, 19, 27, 0.05) 0px 2px 1px 0px`

## Imagery

The site predominantly uses custom hand-drawn 'signature' style imagery for emotional connection, paired with a simple SVG logo. There's an absence of photography or detailed product illustrations. Icons, like the June logo, are monochromatic, filled, and use the brand's primary text colors, maintaining a minimal and functional aesthetic. Imagery acts more as decorative punctuation and brand identity rather than explanatory content or product showcases, making the design very text-dominant.

## Layout

The page uses a maximum-width contained layout rather than full-bleed. The hero section is centered with a prominent headline and subtitle. Content sections follow a consistent vertical rhythm with varying section gaps. The main content often appears within a card-like structure, centered on the page. There's a single, persistent top navigation bar. The overall density is comfortable, with ample whitespace creating clear separation between content blocks.

## Agent Prompt Guide

Quick Color Reference:
text: #151531
background: #fafafa
border: #e9ecef
accent: #6868f7
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary content section: background Haze White (#f0f0fe), 12px border radius, with 48px padding. Inside, a heading 'A new chapter for June' (SF Pro Rounded Bold 60px, #2a2a63, letter-spacing 1.5px) and body text (SF Pro Rounded Regular 16px, #151531, letter-spacing 0.4px).
2. Design a navigation bar: background Canvas White (#fafafa), with 'Product', 'Customers', 'Pricing', 'Content', and 'Changelog' links. Links use Inkwell Text (#151531) at 16px, with an 8px element gap. Active links have a bottom border of 1px Cloud Gray (#e9ecef).
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Linear** — Clean, light UI, sophisticated typography, and minimal use of color accents for functional highlights.
- **Fathom Analytics** — Prominent use of rounded, custom sans-serif typography, abundant whitespace, and a single accent color against a light background.
- **Vercel** — Focus on highly legible text with generous line heights, clean surfaces, and subtle elevation for components.
- **Amie** — Uses a similar principle of a white canvas with flat product surfaces, and compact confident typography with a vivid single accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-cloud-gray: #e9ecef;
  --color-haze-white: #f0f0fe;
  --color-inkwell-text: #151531;
  --color-midnight-violet: #2a2a63;
  --color-shadow-blue-gray: #343a40;
  --color-purple-accent: #6868f7;
  --color-cloud-shadow: #cfd0d1;
  --color-soft-shadow: #c3c4c6;

  /* Typography — Font Families */
  --font-sf-pro-rounded: 'SF Pro Rounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.18px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.21px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: 0.45px;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --tracking-heading: 0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: 1px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: 1.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24-80px;
  --card-padding: 48px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-prominentcard: 20px;

  /* Shadows */
  --shadow-md: rgba(13, 19, 27, 0.1) 0px 2px 10px 0px, rgba(13, 19, 27, 0.2) 0px 0px 2px 0px;
  --shadow-subtle: rgba(13, 19, 27, 0.05) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(13, 19, 27, 0.25) 0px 0px 1px 0px, rgba(13, 19, 27, 0.05) 0px 2px 1px 0px;

  /* Surfaces */
  --surface-canvas-white: #fafafa;
  --surface-haze-white: #f0f0fe;
  --surface-purple-accent: #6868f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-cloud-gray: #e9ecef;
  --color-haze-white: #f0f0fe;
  --color-inkwell-text: #151531;
  --color-midnight-violet: #2a2a63;
  --color-shadow-blue-gray: #343a40;
  --color-purple-accent: #6868f7;
  --color-cloud-shadow: #cfd0d1;
  --color-soft-shadow: #c3c4c6;

  /* Typography */
  --font-sf-pro-rounded: 'SF Pro Rounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.18px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.21px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: 0.45px;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --tracking-heading: 0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: 1px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: 1.5px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 20px;

  /* Shadows */
  --shadow-md: rgba(13, 19, 27, 0.1) 0px 2px 10px 0px, rgba(13, 19, 27, 0.2) 0px 0px 2px 0px;
  --shadow-subtle: rgba(13, 19, 27, 0.05) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(13, 19, 27, 0.25) 0px 0px 1px 0px, rgba(13, 19, 27, 0.05) 0px 2px 1px 0px;
}
```
