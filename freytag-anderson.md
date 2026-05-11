# Freytag Anderson — Style Reference
> Black canvas, stark typography

**Theme:** dark

Freytag Anderson employs a minimalist, high-contrast aesthetic, building a visual language of quiet authority. Its dark-mode foundation with stark white typography creates dramatic legibility, while purposeful negative space and a constrained color palette emphasize content and text as primary visual elements. Interactions are subtle, relying on hover states and minimal accents rather than overt visual cues, conveying a sense of understated confidence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Dark | `#000000` | `--color-canvas-dark` | Page backgrounds, primary text color for light elements on dark surfaces, borders for text-based components |
| Canvas Light | `#fafafa` | `--color-canvas-light` | Primary text color for dark elements on light surfaces, background for certain components and hover states |
| Elevated Dark | `#1c1c1c` | `--color-elevated-dark` | Subtle background for layered elements over Canvas Dark |
| Subtle Dark | `#141109` | `--color-subtle-dark` | Alternative subtle background, almost imperceptible against Canvas Dark |
| Muted UI Gray | `#dcdcdc` | `--color-muted-ui-gray` | Border colors for interactive elements, background for ghost buttons, secondary text color on dark backgrounds |
| Warm Hint Gray | `#c2b5ae` | `--color-warm-hint-gray` | Very subtle background for specific sections, adding warmth against the dark theme |

## Tokens — Typography

### FAVORIT — Primary typeface for all body text, links, buttons, and most headings. Its utilitarian feel supports the direct, no-nonsense brand message. · `--font-favorit`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 15px, 17px, 41px
- **Line height:** 1.00, 1.18, 1.20, 1.40, 1.70
- **Letter spacing:** -0.0220em, -0.0200em
- **Role:** Primary typeface for all body text, links, buttons, and most headings. Its utilitarian feel supports the direct, no-nonsense brand message.

### Clarkson — Used for specific supporting text, providing a slightly more structured but still understated alternative to FAVORIT. · `--font-clarkson`
- **Substitute:** Open Sans
- **Weights:** 300, 400
- **Sizes:** 17px
- **Line height:** 1.40, 1.70
- **Letter spacing:** -0.0200em
- **Role:** Used for specific supporting text, providing a slightly more structured but still understated alternative to FAVORIT.

### halyard-display — Used for minor interactive elements and specific UI text, contributing to the clean, modern feel. · `--font-halyard-display`
- **Substitute:** Roboto
- **Weights:** 300
- **Sizes:** 15px, 17px
- **Line height:** 1.20, 1.40
- **Letter spacing:** -0.0200em, 0.0200em
- **Role:** Used for minor interactive elements and specific UI text, contributing to the clean, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1.2 | — | `--text-caption` |
| body-sm | 17px | 1.2 | — | `--text-body-sm` |
| body | 41px | 1.2 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 29 | 29px | `--spacing-29` |
| 43 | 43px | `--spacing-43` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 300px |

### Layout

- **Section gap:** 43px
- **Card padding:** 0px
- **Element gap:** 17px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, conveying prominence through fill.

Background: Muted UI Gray (#dcdcdc), Text: Canvas Dark (#000000), Border: Muted UI Gray (#dcdcdc) with 300px radius, Padding: 12px vertical, 20px horizontal.

### Ghost Button
**Role:** Secondary action or navigation element, minimal visual weight.

Background: transparent, Text: Canvas Dark (#000000), Border: Canvas Dark (#000000), Padding: 1px vertical, 6px horizontal.

### Feature Card
**Role:** Group related content without adding visual noise.

Background: transparent, no shadow, no border, no padding, 0px radius. Relies on layout for separation.

### Text Link
**Role:** Interactive text for navigation or references.

Text: Canvas Light (#fafafa), no underline by default, visually distinct only on hover or active states (handled by interaction patterns).

## Do's and Don'ts

### Do
- Prioritize text content and layout over decorative elements.
- Use Canvas Dark (#000000) for all main backgrounds and Canvas Light (#fafafa) for primary text in reversed contexts.
- Maintain high contrast ratios for all text elements.
- Apply 0px radius for all general containers and cards to maintain a sharp, deliberate edge.
- Use FAVORIT font for all body text and headings in varying sizes and weights, leveraging its clean, versatile character.
- Ensure generous negative space around all content blocks, using 17px as a base element gap.
- Employ the 300px radius for all interactive buttons and tags, creating a distinctive pill shape.

### Don't
- Do not introduce strong accent colors; maintain the achromatic palette.
- Avoid using drop shadows or complex gradients; rely on flat surfaces and high contrast for visual hierarchy.
- Do not deviate from the specified font families; avoid generic system fonts.
- Do not add unnecessary borders or dividers; rely on spacing and typography for content separation.
- Avoid large imagery or elaborate illustrations; focus on text and minimal UI elements.
- Do not use generic button shapes; ensure all buttons adhere to the pill-shaped 300px radius.
- Avoid horizontal padding on cards; keep card content flush unless explicitly specified.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#000000` | Dominant background for the entire page, providing a dark, immersive base. |
| 1 | Subtle Layer | `#1c1c1c` | Used for subtle background shifts to differentiate content sections without adding visual weight. |
| 2 | Highlight Surface | `#fafafa` | Used for reversed text elements, or very specific UI points when the content calls for a light treatment. |

## Imagery

The site primarily uses photography, often treated with a dark, moody filter and motion blur, conveying a dynamic atmosphere rather than static content. When clear, imagery appears as full-bleed background elements under text. Product imagery, if present, would likely be integrated subtly or presented with minimal adornment. Icons are minimal, represented by simple geometric shapes (e.g., a hamburger menu icon). The density is text-dominant, with imagery serving as an atmospheric backdrop.

## Layout

The page maintains a full-bleed layout, taking advantage of the dark background. The hero section features large, centered headlines over a dynamic, dark motion background. Content sections flow vertically with consistent, spacious internal padding, often featuring large, centered text blocks or a more traditional left-aligned text approach within the dark canvas. There are no clear card grids on the main page, reinforcing the text-heavy, spacious feel. Navigation is minimal, typically a subtle right-aligned menu icon leading to an overlay.

## Agent Prompt Guide

Quick Color Reference:
text: #fafafa
background: #000000
border: #dcdcdc
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with 'Hello. We’re Freytag Anderson' centered. Use Canvas Light (#fafafa) as text color. The font should be FAVORIT weight 400 at 41px line-height 1.00.
2. Design a supporting text block using Clarkson weight 300 at 17px line-height 1.40, color Canvas Light (#fafafa).
3. Create a secondary ghost button with the text 'Show More'. Use Canvas Dark (#000000) for border and text, 1px vertical padding, 6px horizontal padding. Font halyard-display weight 300 at 15px with letter-spacing 0.0200em.

## Similar Brands

- **AIGA** — Uses large type, dark backgrounds, and an emphasis on editorial content over flashy visuals.
- **Basic Agency** — Monochrome palette, large typography, and minimalist layouts focused on high-impact text. Features dynamic background videos/imagery.
- **Work & Co** — Emphasis on black and white contrasting text, generous whitespace, and a content-first approach without heavy UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-dark: #000000;
  --color-canvas-light: #fafafa;
  --color-elevated-dark: #1c1c1c;
  --color-subtle-dark: #141109;
  --color-muted-ui-gray: #dcdcdc;
  --color-warm-hint-gray: #c2b5ae;

  /* Typography — Font Families */
  --font-favorit: 'FAVORIT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clarkson: 'Clarkson', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-halyard-display: 'halyard-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --text-body: 41px;
  --leading-body: 1.2;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-43: 43px;

  /* Layout */
  --section-gap: 43px;
  --card-padding: 0px;
  --element-gap: 17px;

  /* Border Radius */
  --radius-full: 300px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 300px;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-subtle-layer: #1c1c1c;
  --surface-highlight-surface: #fafafa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-dark: #000000;
  --color-canvas-light: #fafafa;
  --color-elevated-dark: #1c1c1c;
  --color-subtle-dark: #141109;
  --color-muted-ui-gray: #dcdcdc;
  --color-warm-hint-gray: #c2b5ae;

  /* Typography */
  --font-favorit: 'FAVORIT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clarkson: 'Clarkson', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-halyard-display: 'halyard-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --text-body: 41px;
  --leading-body: 1.2;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-43: 43px;

  /* Border Radius */
  --radius-full: 300px;
}
```
