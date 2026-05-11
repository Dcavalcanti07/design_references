# Moonli — Style Reference
> Vibrant green digital ledger

**Theme:** light

Moonli’s design system conveys a dynamic, fresh identity through a minimalist layout punctuated by a single vibrant green. Text is largely monochromatic in crisp black and soft gray, relying on thoughtful typography and generous spacing for hierarchy. Components are lightweight with substantial rounded corners, particularly prominent in cards and buttons, emphasizing a soft, approachable digital experience. The vivid green accent color is used strategically to highlight key sections and interactive elements, creating a sense of energy and trust without overwhelming the otherwise clean aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headers, icon strokes, borders, footer background |
| Soft Cloud | `#f3f3f3` | `--color-soft-cloud` | Card backgrounds, subtle surface elevation |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, prominent card surfaces, navigation backgrounds |
| Light Steel | `#e2e2e2` | `--color-light-steel` | Hairline borders, subtle dividers in cards |
| Muted Stone | `#757575` | `--color-muted-stone` | Secondary text, body copy, subtle decorative borders |
| Vivacious Green | `#b8ff65` | `--color-vivacious-green` | Hero section background, prominent card backgrounds, brand accent for key sections |

## Tokens — Typography

### DM Sans — The primary typeface for all text elements. The range of weights from 400 to 700 allows for clear hierarchy, while varied letter-spacing maintains legibility across different sizes, particularly for prominent headings. · `--font-dm-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 16px, 24px, 38px, 48px, 58px
- **Line height:** 1.08, 1.13, 1.17, 1.26, 1.45, 1.50, 1.75
- **Letter spacing:** -0.05em at 58px, -0.03em at 48px, -0.01em at 38px and 24px, 0em at smaller sizes
- **Role:** The primary typeface for all text elements. The range of weights from 400 to 700 allows for clear hierarchy, while varied letter-spacing maintains legibility across different sizes, particularly for prominent headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.75 | — | `--text-caption` |
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 24px | 1.45 | -0.24px | `--text-body` |
| subheading | 38px | 1.26 | -0.38px | `--text-subheading` |
| heading | 48px | 1.17 | -0.48px | `--text-heading` |
| display | 58px | 1.13 | -0.58px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 184 | 184px | `--spacing-184` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 30px |
| cards | 30px |
| buttons | 40px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 25px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Hero Card
**Role:** Main introductory content block

Background is Vivacious Green (#b8ff65), with a strong border-radius of 30px. Padding is substantial, with 112.5px vertically and 20px horizontally. Text is Midnight Ink (#000000).

### Default Card
**Role:** General content container

Background is Canvas White (#ffffff) with a 30px border-radius. Padding is 40px top/bottom and 30px left/right. Has subtle borders and uses Midnight Ink (#000000) for primary text and Muted Stone (#757575) for secondary text.

### Light Surface Card
**Role:** Secondary content container, subtle elevation

Background is Soft Cloud (#f3f3f3) with a 30px border-radius. Generous padding of 100px on all sides. Used for less prominent content blocks.

### Navigation Link
**Role:** Top navigation items

Black text (Midnight Ink #000000) on a Canvas White (#ffffff) background. Font-weight 400. Text size varies, with 16px being common.

### Primary Navigation Button
**Role:** Call to action in navigation

Outline button with a Midnight Ink (#000000) border, 40px border-radius. Text is Midnight Ink (#000000). Padding is 12px vertical and 20px horizontal.

## Do's and Don'ts

### Do
- Prioritize a clean, spacious layout using Canvas White (#ffffff) as the dominant background.
- Use Vivacious Green (#b8ff65) exclusively as a highly visible accent color for hero sections and key content cards, never for general UI elements.
- Apply a 30px border-radius consistently to all cards and content blocks, achieving a soft, approachable aesthetic.
- Use Midnight Ink (#000000) for all main headings and primary text, ensuring strong contrast.
- Delegate Muted Stone (#757575) for all secondary and body text, providing necessary hierarchy while maintaining readability.
- Maintain comfortable density with an `elementGap` of 20px and `cardPadding` of 20px.
- Utilize DM Sans at varying weights and letter-spacings to establish clear typographic hierarchy, especially for larger headlines.

### Don't
- Do not introduce new vivid colors; stick to Vivacious Green (#b8ff65) for all primary accents.
- Avoid sharp corners; all interactive and content containers should use the prescribed 30px or 40px border-radius.
- Do not use box-shadows or complex gradients; rely on background color and border-radius for visual distinction.
- Do not clutter content; ensure generous white space and adhere to the 1280px page max-width.
- Do not use generic system fonts; always specify DM Sans for all text.
- Avoid dense text blocks; break content into manageable sections with ample vertical spacing.
- Do not use a default blue for links; all interactive text should respect the Midnight Ink (#000000) or Muted Stone (#757575) palette.

## Imagery

This design system primarily uses outline-style technical illustrations. These are functional yet playful, rendered in a consistent monochromatic palette (Midnight Ink #000000). They serve an explanatory role, breaking up text and visually representing concepts without being decorative. Photography is absent, and the focus remains on UI elements and line-art graphics, contributing to a clean, product-focused, and slightly abstract feel.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #e2e2e2
- accent: #b8ff65
- primary action: no distinct CTA color

Example Component Prompts:
- Create a Hero Section: Vivacious Green (#b8ff65) background with 30px radius, centered display heading (DM Sans, 58px, 700, -0.58px tracking, #000000), followed by body-sm text (DM Sans, 16px, 400, #000000).
- Create a Default Card: Canvas White (#ffffff) background, 30px radius, 1px solid Light Steel (#e2e2e2) border, 40px vertical, 30px horizontal padding, with a heading (DM Sans, 38px, 500, -0.38px tracking, #000000) and body-sm text (DM Sans, 16px, 400, #757575).
- Create a Navigation Button: outlined with a Midnight Ink (#000000) 1px border, 40px border-radius, 12px vertical and 20px horizontal padding, text in Midnight Ink (#000000) at DM Sans 16px (400 weight).

## Similar Brands

- **Stripe** — Similar emphasis on clean, spacious UI, strong typography, and a strategic use of a single vivid accent color for key elements.
- **Linear** — Monochromatic interface with crisp text, subtle surface variations, and a focus on functionality over heavy decoration, relying on spacing for hierarchy.
- **Figma** — Clean, almost entirely interface-driven aesthetic, using a dominant light surface, strong black text, and minimal color only for key interactive states or branding.
- **Notion** — Reliance on a white canvas and highly legible, functional typography, using subtle grays and minimal color for organizational cues rather than strong branding.
- **Webflow** — Modern design language featuring generous whitespace, focused typography, and a single strong brand accent color that pops against a largely neutral background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-soft-cloud: #f3f3f3;
  --color-canvas-white: #ffffff;
  --color-light-steel: #e2e2e2;
  --color-muted-stone: #757575;
  --color-vivacious-green: #b8ff65;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.75;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 24px;
  --leading-body: 1.45;
  --tracking-body: -0.24px;
  --text-subheading: 38px;
  --leading-subheading: 1.26;
  --tracking-subheading: -0.38px;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --tracking-heading: -0.48px;
  --text-display: 58px;
  --leading-display: 1.13;
  --tracking-display: -0.58px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-184: 184px;
  --spacing-200: 200px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 25px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;

  /* Named Radii */
  --radius-tags: 30px;
  --radius-cards: 30px;
  --radius-buttons: 40px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-soft-cloud: #f3f3f3;
  --color-canvas-white: #ffffff;
  --color-light-steel: #e2e2e2;
  --color-muted-stone: #757575;
  --color-vivacious-green: #b8ff65;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.75;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 24px;
  --leading-body: 1.45;
  --tracking-body: -0.24px;
  --text-subheading: 38px;
  --leading-subheading: 1.26;
  --tracking-subheading: -0.38px;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --tracking-heading: -0.48px;
  --text-display: 58px;
  --leading-display: 1.13;
  --tracking-display: -0.58px;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-184: 184px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
}
```
