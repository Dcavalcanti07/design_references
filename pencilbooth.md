# PencilBooth — Style Reference
> High-contrast content blueprint

**Theme:** light

PencilBooth employs a crisp, feature-focused interface with a strong emphasis on content showcase over decorative flair. Its visual language relies on high contrast between achromatic elements and precise use of a single vibrant blue accent. The layout is structured and grid-based, favoring clear visual separation and minimal embellishment. Typography is compact and deliberate, designed to support readability without drawing excessive attention away from visual assets.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, icons, borders on light backgrounds — designed for maximum legibility |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces, button backgrounds, primary component fills |
| Whisper Gray | `#f2f2f2` | `--color-whisper-gray` | Soft section background, alternate surface, and quiet card fill. Do not promote it to the primary CTA color |
| Border Fog | `#e5e7eb` | `--color-border-fog` | Hairline borders, dividers, subtle inactive states — provides structure without harshness |
| Muted Stone | `#b2b2b2` | `--color-muted-stone` | Secondary text, disabled states, supporting information — a soft contrast to primary text |
| Shadow Graphite | `#5a5e62` | `--color-shadow-graphite` | Deeper secondary text, helper text for compact informational blocks |
| Sapphire Accent | `#0f1ea1` | `--color-sapphire-accent` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Horizon Blue | `#cfd2ec` | `--color-horizon-blue` | Muted UI surface for disabled controls, low-emphasis panels, and placeholder blocks |
| Sky Interactive | `#8fbaff` | `--color-sky-interactive` | Hover states, focused elements for interactive components, and secondary accent backgrounds |

## Tokens — Typography

### Soehne — Primary typeface for all UI text, headings, and body content. Its tight letter spacing throughout maintains a dense, efficient information display. Weights 400 and 700 provide simple hierarchy. · `--font-soehne`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 32px, 96px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.0100em
- **Role:** Primary typeface for all UI text, headings, and body content. Its tight letter spacing throughout maintains a dense, efficient information display. Weights 400 and 700 provide simple hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | 0.12px | `--text-caption` |
| body-sm | 14px | 1.2 | 0.14px | `--text-body-sm` |
| body | 16px | 1.2 | 0.16px | `--text-body` |
| subheading | 18px | 1.2 | 0.18px | `--text-subheading` |
| heading | 32px | 1.2 | 0.32px | `--text-heading` |
| display | 96px | 1 | 0.96px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 47 | 47px | `--spacing-47` |
| 48 | 48px | `--spacing-48` |
| 100 | 100px | `--spacing-100` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| icons | 9999px |
| links | 2px |

### Layout

- **Section gap:** 47px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Feature Card
**Role:** Showcasing individual features or content blocks.

Background: Whisper Gray (#f2f2f2). Border Radius: 10px. No box shadow. Padding: 0px. Contains iconography and text.

### Interactive List Item
**Role:** Navigation or select options within a list.

Background: Canvas White (#ffffff). Hover background: Sky Interactive (#8fbaff). Text: Midnight Ink (#000000). Border Radius: 2px. Padding: 6px vertical. Iconic styling via rounded icons.

### Selected List Item
**Role:** Currently active or selected item in a list.

Background: Sapphire Accent (#0f1ea1). Text: Canvas White (#ffffff). Border Radius: 2px. Padding: 6px vertical. Features an icon in Canvas White.

### Profile Thumbnail
**Role:** Representing user profiles or content creators.

Background: varied (brand specific). Border Radius: 9999px (circular). Accompanied by a text link in Midnight Ink (#000000) with a 2px border radius on hover.

## Do's and Don'ts

### Do
- Prioritize high contrast pairings for text and backgrounds: Midnight Ink (#000000) on Canvas White (#ffffff) or Whisper Gray (#f2f2f2).
- Use Sapphire Accent (#0f1ea1) as the primary brand color for selected states and key interactive backgrounds.
- Apply a 10px border radius consistently to all card components.
- Maintain a compact information density using the tight letter-spacing (0.0100em) of Soehne for all text.
- Employ Border Fog (#e5e7eb) for all hairline borders and dividers to provide subtle structure.
- Use Sky Interactive (#8fbaff) for background hover states on interactive elements to signal interactivity.
- Round all small decorative icons to 9999px for a pill-like or circular appearance.

### Don't
- Avoid decorative gradients or shadows; rely on color contrast and clear layout for visual hierarchy.
- Do not deviate from the Soehne typeface or its specified weights and letter-spacing for UI elements.
- Refrain from introducing additional accent colors that are not part of the defined Sapphire Accent or Sky Interactive palette.
- Do not use overly verbose copy; present information concisely, leveraging the high-contrast typography.
- Avoid large hero imagery that dominates the page without an explicit function; prioritize content showcase over decorative visuals.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Whisper Gray | `#f2f2f2` | Card backgrounds, secondary interactive surface |
| 2 | Horizon Blue | `#cfd2ec` | Alternating section backgrounds |
| 3 | Sky Interactive | `#8fbaff` | Active states, subtle highlights |
| 4 | Sapphire Accent | `#0f1ea1` | Primary active states, brand highlights |

## Imagery

This design system uses a mixed approach to imagery. Illustrations are flat, graphic, and often utilize brand-specific colors or simple outlines. Photography appears as tight product crops on pure white, showcasing objects without lifestyle context; it is functional and explanatory. Icons are filled, circular (9999px radius), and primarily monochrome (Midnight Ink or Canvas White), serving to visually punctuate list items or features. Imagery is used to explain content or showcase work rather than as decorative filler, contributing to a content-dominant visual hierarchy.

## Layout

The page maintains a centered, max-width layout for most content, but integrates full-bleed sections for impactful visual displays. The hero features a large, left-aligned headline over a white background, setting a direct tone. Sections alternate between Canvas White and Horizon Blue backgrounds, creating a consistent vertical rhythm. Content is arranged in flexible patterns, including 2-column text + image sections and 3-column card grids for features. Navigation is primarily top-bar or via interactive list items integrated into the content flow, emphasizing a direct, uncluttered experience. Section gaps are consistently applied at 47px, creating clear separation between content blocks.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e5e7eb
accent: #0f1ea1
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary headline: Text 'Visual Stories That Stick' in Soehne, 96px, weight 700, #000000, 1.0 line height, letter-spacing 0.96px.
2. Design a feature card: Background Whisper Gray (#f2f2f2), 10px border radius, no shadow. Inside, include a circular icon (9999px radius) filled with Canvas White (#ffffff) and a Soehne-400, 16px, #000000, 1.2 line height, letter-spacing 0.16px body text.
3. Build an interactive list item: Background Canvas White (#ffffff), on hover Sky Interactive (#8fbaff). Text 'Create a new project' in Soehne-400, 16px, #000000, 1.2 line height, letter-spacing 0.16px. Left-aligned, includes a circular icon.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Beehiiv** — Monochromatic interface with a single vibrant accent color, focus on clean typography.
- **ConvertKit** — Clear, direct layout with emphasis on content management, minimal decorative elements.
- **Ghost** — High contrast text on light backgrounds, strong grid structure, and content-first approach.
- **Markup.io** — Sparse UI, accent color for primary actions, and clear delineation of content areas via subtle background shifts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f2f2f2;
  --color-border-fog: #e5e7eb;
  --color-muted-stone: #b2b2b2;
  --color-shadow-graphite: #5a5e62;
  --color-sapphire-accent: #0f1ea1;
  --color-horizon-blue: #cfd2ec;
  --color-sky-interactive: #8fbaff;

  /* Typography — Font Families */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: 0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.18px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.32px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: 0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-47: 47px;
  --spacing-48: 48px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 47px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 10px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-icons: 9999px;
  --radius-links: 2px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-whisper-gray: #f2f2f2;
  --surface-horizon-blue: #cfd2ec;
  --surface-sky-interactive: #8fbaff;
  --surface-sapphire-accent: #0f1ea1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f2f2f2;
  --color-border-fog: #e5e7eb;
  --color-muted-stone: #b2b2b2;
  --color-shadow-graphite: #5a5e62;
  --color-sapphire-accent: #0f1ea1;
  --color-horizon-blue: #cfd2ec;
  --color-sky-interactive: #8fbaff;

  /* Typography */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: 0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.18px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.32px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: 0.96px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-47: 47px;
  --spacing-48: 48px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 10px;
  --radius-full: 9999px;
}
```
