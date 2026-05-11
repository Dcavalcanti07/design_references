# Waka Waka — Style Reference
> Gallery Wall Catalog: off-white canvas, stark black typography, and carefully placed product visuals.

**Theme:** light

Waka Waka employs a stark, editorial aesthetic, reminiscent of print. Its visual system centers on high-contrast typography against an off-white canvas, conveying information with an almost journalistic directness. The layout is disciplined and grid-bound, using generous negative space around bold type and product photography to lend an artifact-like quality to content. Color is minimal, primarily serving as a background for the content block, with deep charcoal black for all text and UI elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#edeae4` | `--color-canvas-parchment` | Page background, primary surface for content blocks |
| Ink Jot | `#28282a` | `--color-ink-jot` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### Waka Sans — The primary typeface for all content, from monumental headings to functional body text and navigation. Its heavy weights in large sizes dominate the visual field, creating a poster-like impact, while lighter weights provide clarity for smaller text. · `--font-waka-sans`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 14px, 18px, 24px, 560px
- **Line height:** 0.80, 0.83, 1.00, 1.20, 1.60
- **Letter spacing:** -0.09em at 560px, -0.03em at 24px, -0.02em at 18px
- **Role:** The primary typeface for all content, from monumental headings to functional body text and navigation. Its heavy weights in large sizes dominate the visual field, creating a poster-like impact, while lighter weights provide clarity for smaller text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body-sm | 14px | 1 | — | `--text-body-sm` |
| body | 18px | 1 | — | `--text-body` |
| body-lg | 24px | 1 | — | `--text-body-lg` |
| heading-sm | 560px | 1 | — | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 27 | 27px | `--spacing-27` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Page max-width:** 445px
- **Section gap:** 40-54px
- **Card padding:** 20px
- **Element gap:** 6-20px

## Components

### Page Canvas
**Role:** The primary content container

A single content block centered on the page with 'Canvas Parchment' (#edeae4) background, constrained to a maximum width of 445px. There are no explicit borders or shadows, relying on the contrast with the page background for definition.

### Hero Headline
**Role:** Prominent display text

Uses Waka Sans at 560px, weight 700, color 'Ink Jot' (#28282a). Letter-spacing is -0.09em for dramatic visual effect against the 'Canvas Parchment' background.

### Navigation Link
**Role:** Site navigation

Waka Sans, 14px, weight 400, color 'Ink Jot' (#28282a). These are minimal, text-only links within the header and footer.

### Body Text
**Role:** :Standard paragraph and descriptive text

Waka Sans, 14px, weight 400, color 'Ink Jot' (#28282a) with lineHeight 1.6.

### Functional Details
**Role:** Metadata, timestamps, and smaller labels

Waka Sans, 10px, weight 400, color 'Ink Jot' (#28282a). Used for compact, informational text blocks.

## Do's and Don'ts

### Do
- Prioritize 'Canvas Parchment' (#edeae4) as the main background for content areas, providing a neutral, gallery-like surface.
- Use 'Ink Jot' (#28282a) for all text and UI elements to maintain high contrast and a consistent monochrome palette.
- Employ Waka Sans at 560px with weight 700 and -0.09em letter-spacing for all prominent display headlines, creating a poster-like visual impact.
- Maintain a clear page max-width of 445px for primary content blocks to create a focused, contained reading experience.
- Utilize Waka Sans at 14px, weight 400, and lineHeight 1.6 for body text, ensuring legibility within the compact layout.
- Intersperse content with liberal white space; `elementGap` should range from 6px to 20px, and `sectionGap` between 40px and 54px.
- Maintain a strict '0px' border-radius across all elements to reinforce the sharp, editorial aesthetic.

### Don't
- Avoid using any saturated colors beyond the strict 'Ink Jot' and 'Canvas Parchment' palette.
- Do not introduce shadows or complex gradients; the design relies on flat surfaces and stark contrast.
- Refrain from varying font families; Waka Sans is the exclusive typeface for the entire system.
- Do not break the page max-width containment; all primary content should adhere to the 445px constraint.
- Avoid decorative graphical elements; imagery should be product-focused and photography-based.
- Do not implement any border-radius greater than 0px; all corners must remain sharp.
- Do not use subtle neutrals to hint at hierarchy; rely on type size, weight, and spacing for visual differentiation.

## Imagery

Imagery consists exclusively of product photography, primarily showcasing furniture. The treatment is stark and isolated: tightly cropped subjects against neutral, often studio-like backgrounds, with a focus on form and material. Photos are contained within layout blocks, maintaining sharp, unmasked edges. There are no lifestyle shots, illustrations, or iconography beyond simple text-based interactives; the objects themselves convey the aesthetic and brand. Images are high-contrast and often monochromatic, mirroring the color palette.

## Layout

The page model is centered and constrained to a maximum width of 445px, creating a narrow, column-like presentation reminiscent of a printed page. The hero pattern features a monumental, centered headline 'Waka' spanning the width. Content arrangement alternates between large, impactful type elements and product photographs, often in a two-column or stacked composition within the narrow canvas. Vertical rhythm is established by distinct gaps between sections and elements, relying on negative space rather than explicit dividers. Navigation is minimal, consisting of text links in a fixed header and footer.

## Motion Philosophy

The system utilizes subtle motion, primarily for interaction feedback on opacity and transform, with `ease` timing functions. Durations are generally fast to moderate (0.3s to 0.4s), ensuring responsiveness without drawing excessive attention. Transitions are sparingly used, reinforcing the static, editorial feel of the design. Long duration transitions (0.6s) suggest more significant state changes, but the overall approach prioritizes quick and direct feedback over elaborate animations.

## Agent Prompt Guide

primary action: no distinct CTA color

## Similar Brands

- **AIGA Eye on Design** — Shares a stark, editorial layout with bold typography, high contrast, and minimal color.
- **The Brand Identity** — Employs oversized type, a restricted color palette, and a focus on clean, grid-based content presentation.
- **Norm Architects** — Features a minimalist aesthetic with neutral tones, strong focus on product display, and a quiet, sophisticated typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #edeae4;
  --color-ink-jot: #28282a;

  /* Typography — Font Families */
  --font-waka-sans: 'Waka Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --text-body: 18px;
  --leading-body: 1;
  --text-body-lg: 24px;
  --leading-body-lg: 1;
  --text-heading-sm: 560px;
  --leading-heading-sm: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-27: 27px;

  /* Layout */
  --page-max-width: 445px;
  --section-gap: 40-54px;
  --card-padding: 20px;
  --element-gap: 6-20px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #edeae4;
  --color-ink-jot: #28282a;

  /* Typography */
  --font-waka-sans: 'Waka Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --text-body: 18px;
  --leading-body: 1;
  --text-body-lg: 24px;
  --leading-body-lg: 1;
  --text-heading-sm: 560px;
  --leading-heading-sm: 1;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-27: 27px;
}
```
