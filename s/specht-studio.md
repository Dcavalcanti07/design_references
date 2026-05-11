# Specht Studio — Style Reference
> Gallery Grid Monochrome

**Theme:** light

Specht Studio employs a stark, high-contrast visual language reminiscent of a curated gallery wall. The primary interaction is through image-heavy blocks, framed by thin borders and text in a sparse, functional sans-serif. The design emphasizes content arrangement and bold typographic treatments, with color sparsely used and predominantly achromatic for navigation and core information, allowing the rich, varied artwork to provide visual interest and chromatic depth.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Black Ink | `#000000` | `--color-black-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Midtone Gray | `#666666` | `--color-midtone-gray` | Secondary text, link borders when inactive, image borders and some iconography |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, primary surfacing |

## Tokens — Typography

### Helvetica Neue — All text elements: headings, body copy, navigation, and links. The consistent use of a single font family and weight across all roles creates a unified, no-nonsense typographic voice. · `--font-helvetica-neue`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 15px, 16px, 25px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** All text elements: headings, body copy, navigation, and links. The consistent use of a single font family and weight across all roles creates a unified, no-nonsense typographic voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1.4 | — | `--text-caption` |
| body-sm | 16px | 1.4 | — | `--text-body-sm` |
| body | 25px | 1.3 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 67px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Navigation Link
**Role:** Primary site navigation items.

Text in Black Ink (#000000) at 15px Helvetica Neue, with a 10px bottom margin. Hover state reveals a subtle border. Padding: 0px 0px 2px 0px.

### Image Grid Item
**Role:** Display individual portfolio pieces or art.

A square or rectangular content block containing an image, bordered by a 1px solid #666666 line. Text labels below the image are in Midtone Gray (#666666), 16px Helvetica Neue, with a 10px bottom margin. Each item feels like a distinct piece on a gallery wall.

### Project Title Link
**Role:** Headline for individual project entries on the grid.

Black Ink (#000000) with a 10px bottom margin, 12px left margin, 13px bottom margin, 24px right/left top padding, 11px top margin, and 10px top margin.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all background surfaces to maintain a clean, gallery-like aesthetic.
- Use Black Ink (#000000) for all primary text, headings, and active navigation states.
- Frame interactive blocks and images with subtle 1px solid borders using Midtone Gray (#666666) or Black Ink (#000000).
- Apply normal letter-spacing for all Helvetica Neue type, avoiding condensed or expanded tracking.
- Maintain a clear visual hierarchy using spacing; utilize 10px as the default element separation and 67px for section breaks.
- Keep brand accent colors confined to embedded imagery or content rather than UI elements.

### Don't
- Do not use saturated colors for UI elements; chromaticity should primarily come from background content.
- Avoid heavy shadows or gradients on any UI component; elevation is achieved through framing, not depth effects.
- Do not introduce additional font families or weights beyond Helvetica Neue 400.
- Refrain from large, contrasting background blocks that break the predominantly light theme, except where content specifically dictates.
- Do not introduce complex UI elements or decorative flourishes; maintain a functional, content-focused approach.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary navigation link: Helvetica Neue 400, 15px, #000000, normal letter-spacing, with a 2px bottom border on hover in Black Ink (#000000).
2. Create an image grid item: A 1px solid border in Midtone Gray (#666666). Below the image, display text in Helvetica Neue 400, 16px, #666666, with a 10px bottom margin.
3. Create a project title heading: Helvetica Neue 400, 25px, #000000, normal letter-spacing, with 10px bottom margin and 24px right/left/top padding, and 11px top margin.

## Similar Brands

- **Are.na** — Grid-based content display, minimal UI, and focus on visual assets over heavy text.
- **OFFICE Magazine** — High-contrast monochrome typography with heavy reliance on strong imagery to convey brand identity.
- **Working Not Working** — Portfolio-centric site with large visual elements arranged in a grid, neutral palette allowing work to shine.
- **Sight Unseen** — Emphasizes curated content through a clean, graphic user interface with a similar treatment of images and text.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-black-ink: #000000;
  --color-midtone-gray: #666666;
  --color-canvas-white: #ffffff;

  /* Typography — Font Families */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 25px;
  --leading-body: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-35: 35px;

  /* Layout */
  --section-gap: 67px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-black-ink: #000000;
  --color-midtone-gray: #666666;
  --color-canvas-white: #ffffff;

  /* Typography */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 25px;
  --leading-body: 1.3;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-35: 35px;
}
```
