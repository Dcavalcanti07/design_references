# HeroKit — Style Reference
> Dark mode canvas with vivid yellow punctuation

**Theme:** dark

HeroKit exhibits a high-contrast aesthetic with an almost exclusively dark mode canvas accented by a single, vibrant yellow. Type is primarily tight, uppercase sans-serif, using a custom font family for headlines and body text. Surfaces are flat and borderless, relying on the stark background contrast and subtle content blocks for definition. The system feels direct and bold, allowing illustrative elements to provide visual energy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page backgrounds, card surfaces, primary text, prominent borders, button backgrounds |
| Pearl | `#ffffff` | `--color-pearl` | Interface accents, selected link text and borders against dark backgrounds |
| Gunmetal | `#333333` | `--color-gunmetal` | Subtle text against dark backgrounds |
| Steel Gray | `#999999` | `--color-steel-gray` | Placeholder text, muted helper text, inactive links |
| Medium Gray | `#808080` | `--color-medium-gray` | Secondary text, disabled element outlines |
| Electric Yellow | `#ffffa7` | `--color-electric-yellow` | Primary action backgrounds, highlight text, interactive element focus state borders, brand accent |
| Vivid Canary | `#fddd05` | `--color-vivid-canary` | Decorative background fills, less prominent brand accent |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### PP Neue Montreal — Dominant textual voice for headlines and body text. Large headlines use specific tight tracking to create gravity without excessive weight. · `--font-pp-neue-montreal`
- **Substitute:** system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif
- **Weights:** 400
- **Sizes:** 16px, 20px, 30px, 32px, 50px, 120px, 144px
- **Line height:** 1.00, 1.08, 1.20, 1.30, 1.40
- **Letter spacing:** -0.02em at 50px, -0.01em at 16px
- **Role:** Dominant textual voice for headlines and body text. Large headlines use specific tight tracking to create gravity without excessive weight.

### ABC Monument Grotesk — Hero headlines, creating distinctive, highly compressed display typography for maximum impact on a dark canvas. · `--font-abc-monument-grotesk`
- **Substitute:** system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif
- **Weights:** 400
- **Sizes:** 120px
- **Line height:** 1.00
- **Letter spacing:** -0.04em at 120px
- **Role:** Hero headlines, creating distinctive, highly compressed display typography for maximum impact on a dark canvas.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.2 | -0.16px | `--text-body` |
| subheading | 20px | 1.08 | -0.2px | `--text-subheading` |
| heading-sm | 30px | 1 | -0.3px | `--text-heading-sm` |
| heading | 50px | 1 | -1px | `--text-heading` |
| display | 120px | 1 | -4.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 16px |
| default | 8px |

### Layout

- **Section gap:** 64px
- **Card padding:** 14px
- **Element gap:** 10px

## Components

### Navigation Link
**Role:** Standard navigation item for top bar

Black text (#000000) on a transparent background, 14px horizontal padding, 10px vertical padding, 8px border radius. Hover state shows Pearl text (#ffffff) with Electric Yellow (#ffffa7) border and background accent.

### Primary Action Button
**Role:** Main call-to-action button, visually prominent

Electric Yellow background (#ffffa7), Absolute Zero text (#000000), 14px horizontal padding, 10px vertical padding, 8px border radius.

### Secondary Action Button
**Role:** Less prominent action button, typically ghost or outlined style

Absolute Zero background (#000000), Pearl text (#ffffff). Appears as a ghost button with a thin border.

### Product Card
**Role:** Container for showcasing individual product items or components

Absolute Zero background (#000000), 8px border radius, no box shadow, 0 padding unless specified by content.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#000000) for general backgrounds and card surfaces to maintain the dark mode canvas.
- Use Electric Yellow (#ffffa7) sparingly and intentionally as the primary high-contrast accent for interactive elements and brand highlights.
- Apply a comfortable density with an element gap of 10px for most UI elements.
- Utilize 8px border radius for all interactive components and cards to maintain consistency.
- Implement tight letter-spacing for all heading sizes, especially -0.04em for display text, to create a condensed, impactful look.
- Employ PP Neue Montreal for all body text and most headings to maintain brand typography.
- Ensure sufficient contrast for all text against backgrounds, adhering to AAA standards where possible.

### Don't
- Avoid using multiple chromatic colors; Electric Yellow should be the primary accent.
- Do not use generic system fonts where PP Neue Montreal or ABC Monument Grotesk are specified; maintain the custom typographic signature.
- Refrain from using drop shadows or complex elevation; surfaces should remain flat against the dark canvas.
- Do not introduce large variations in border radius; stick to 8px and 16px where explicitly required for larger elements.
- Avoid overly spacious layouts; maintain a comfortable density with a base unit of 4px and 10px element gaps.
- Avoid decorative gradients unless clearly defined as brand elements; stick to solid color backgrounds.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000000` | Dominant page background, deepest layer. |
| 1 | Card Base | `#000000` | Cards and content blocks, visually distinct from page background by content, not color. |

## Imagery

This site uses large, three-dimensional abstract graphics and product renders. These are typically full-bleed or large contained elements with soft, organic shapes and vibrant, often gradient-like colors against the dark background. Photography or traditional illustrations are absent. Icons are minimal, outlined, and monochromatic, primarily serving as functional UI elements rather than decorative art. Imagery is dense, often occupying significant visual space to showcase product content rather than serving as mere decoration.

## Layout

The page primarily uses a full-bleed dark mode canvas. The hero section features a centered, oversized headline contrasting with a dynamic visual element. Section rhythm is often established by full-width dark blocks, sometimes broken by full-bleed imagery. Content often appears in stacked, centered arrangements, or in grid patterns for product showcases. Navigation is a compact, sticky top bar, providing persistent access without intruding on content. The layout prioritizes visual impact and direct messaging.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #ffffff
- background: #000000
- border: #000000
- accent: #ffffa7
- primary action: #ffffa7 (filled action)

**3-5 Example Component Prompts:**
- Create a hero section: Absolute Zero background (#000000). Headline 'Supercharge your website' in ABC Monument Grotesk weight 400, 120px, #ffffff, letter-spacing -4.8px. Body text 'Create stunning visuals' in PP Neue Montreal weight 400, 20px, #ffffff, letter-spacing -0.2px. Primary action button 'Get started for free' (Electric Yellow background #ffffa7, Absolute Zero text #000000, 8px radius, 14px horizontal padding, 10px vertical padding).
- Design a navigation bar item: 'How it works' in PP Neue Montreal weight 400, 12px, #000000. Underlined with a 1px Electric Yellow border (#ffffa7). Text color changes to Pearl (#ffffff) on hover. 8px radius, 14px horizontal padding, 10px vertical padding.
- Build a product card: Absolute Zero background (#000000), 8px border radius, with a placeholder image and a title 'Blobmixer' in PP Neue Montreal weight 400, 16px, #ffffff. Muted helper text below the title '• HERO' in Steel Gray (#999999) 12px.

## Similar Brands

- **Framer** — Heavy reliance on dark mode with a single bright accent color (blue), minimalist component styling, and bold, tight typography.
- **Spline** — Dark UI, prominent use of abstract 3D renders as hero elements, and a similar approach to showcasing digital creations.
- **Read.cv** — Monochromatic interface with a single vibrant accent (green), strong typographic hierarchy, and clean, flat design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-pearl: #ffffff;
  --color-gunmetal: #333333;
  --color-steel-gray: #999999;
  --color-medium-gray: #808080;
  --color-electric-yellow: #ffffa7;
  --color-vivid-canary: #fddd05;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-monument-grotesk: 'ABC Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.08;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.3px;
  --text-heading: 50px;
  --leading-heading: 1;
  --tracking-heading: -1px;
  --text-display: 120px;
  --leading-display: 1;
  --tracking-display: -4.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 14px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-large: 16px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-canvas: #000000;
  --surface-card-base: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-pearl: #ffffff;
  --color-gunmetal: #333333;
  --color-steel-gray: #999999;
  --color-medium-gray: #808080;
  --color-electric-yellow: #ffffa7;
  --color-vivid-canary: #fddd05;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-monument-grotesk: 'ABC Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.08;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.3px;
  --text-heading: 50px;
  --leading-heading: 1;
  --tracking-heading: -1px;
  --text-display: 120px;
  --leading-display: 1;
  --tracking-display: -4.8px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
}
```
