# Mother Design — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Mother Design operates with a high-contrast, starkly typographic visual system, channeling the precision of an architectural drawing onto a white canvas. Its deliberate use of un-styled text as clickable elements, minimal decorative elements, and strong grid lines defines a no-frills, functional aesthetic. Typography carries the primary visual weight, with large, confident headlines and tightly tracked text emphasizing clarity and directness. The overall feeling is one of structural rigor and intentional simplicity, where content and interaction are prioritized over visual embellishment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, navigation backgrounds, default button backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Smoke Grey | `#f4f4f4` | `--color-smoke-grey` | Subtle background for specific sections, establishing a secondary layered surface |
| Muted Stone | `#808080` | `--color-muted-stone` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Divider Line | `#262626` | `--color-divider-line` | Subtle dividers and borders within content areas. (Based on --hr-color: rgba(0,0,0,.15)) |

## Tokens — Typography

### Basis — Primary brand typeface for all headings, body text, nav items, and buttons. Its wide range of weights and negative letter-spacing for larger sizes creates a distinctive, assertive presence. · `--font-basis`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 10px, 14px, 16px, 48px, 60px, 110px, 226px
- **Line height:** 1.00, 1.10, 1.20, 1.50
- **Letter spacing:** -0.01, -0.01, -0.01, -0.02, -0.04, -0.04, -0.04
- **Role:** Primary brand typeface for all headings, body text, nav items, and buttons. Its wide range of weights and negative letter-spacing for larger sizes creates a distinctive, assertive presence.

### Basis Mono — Monospaced font for specific technical details, code snippets, or subtle secondary information where a fixed-width aesthetic is desired. · `--font-basis-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** 0.06
- **Role:** Monospaced font for specific technical details, code snippets, or subtle secondary information where a fixed-width aesthetic is desired.

### Times — Used sparingly for decorative elements or specific content where a traditional serif contrast is intended. Appears to be a default fallback on the site, not a primary voice. · `--font-times`
- **Substitute:** Georgia
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** 0.06
- **Role:** Used sparingly for decorative elements or specific content where a traditional serif contrast is intended. Appears to be a default fallback on the site, not a primary voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.01px | `--text-caption` |
| body-sm | 14px | 1.2 | -0.01px | `--text-body-sm` |
| body | 16px | 1.5 | -0.01px | `--text-body` |
| subheading | 48px | 1 | -0.02px | `--text-subheading` |
| heading | 60px | 1 | -0.04px | `--text-heading` |
| heading-lg | 110px | 1 | -0.04px | `--text-heading-lg` |
| display | 226px | 1 | -0.04px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 200px
- **Card padding:** 16px
- **Element gap:** 20px

## Components

### Navigation Link
**Role:** Text-based navigation item in header

Text in Basis, #000000, 16px. Underline on hover. No background or padding. Interactivity is conveyed through text styling rather than distinct button visuals.

### Subtle Accent Button
**Role:** Button with background but no visible border or padding beyond text.

Background #ffffff, text #000000. Used for secondary actions in contexts that already have a strong visual container. Text 16px Basis, weight 400, tightly tracked. No borders, no intrinsic padding beyond text content; container provides visual separation.

### Ghost Bordered Button
**Role:** Transparent button with 1px black border. Used for generic interactive elements.

Background transparent, text #000000, 1px #000000 border. No explicit border-radius. Padding 0px. Text 16px Basis, weight 400. This is the most common interactive element style.

### Muted Ghost Button
**Role:** Transparent button with grey text and border, indicating a less prominent action or disabled state.

Background transparent, text #808080, 1px #808080 border. Text 16px Basis, weight 400. No border-radius or padding.

### Input Field
**Role:** Standard text input field

Transparent background, text #000000, 1px #000000 border. No border-radius or padding. Uses Basis font.

### Project Card
**Role:** Container for portfolio items or content blocks

Implied border of 1px Ink Black. No explicit background color, relying on Canvas White. Uses 0px border-radius. Padding of 16px on larger blocks, 0 on image-heavy media cards. Primarily defined by its visual container lines.

## Do's and Don'ts

### Do
- Prioritize Ink Black text (#000000) on Canvas White (#ffffff) backgrounds for maximum contrast and essential information.
- Use Basis font for all textual content, adjusting weights and letter-spacing for hierarchy as defined in the typography section.
- Define interactive areas primarily through 1px Ink Black (#000000) borders and text-based links, rather than strong background fills.
- Maintain a default border-radius of 0px across all components to reinforce the sharp, precise aesthetic.
- Employ Smoke Grey (#f4f4f4) sparingly for subtle section breaks or secondary surface differentiation, always contrasting with Ink Black text.
- Use Muted Stone (#808080) for helper text, disabled states, or less prominent links.
- Implement the 20px elementGap consistently for horizontal and vertical spacing between most elements.

### Don't
- Avoid using gradients or shadows; the design relies on flat, high-contrast surfaces and sharp edges.
- Do not use background colors on primary buttons; rely on borders and text color for interaction cues.
- Refrain from introducing decorative imagery that deviates from the grid-like, monochromatic aesthetic.
- Do not use rounded corners on any elements; all corners should be sharp 0px radius.
- Avoid excessive use of color; the system is built on a neutral palette with minimal accentuation.
- Do not vary line-height significantly from the defined values in the typography section; maintain tight leading.
- Avoid large internal padding on interactive elements; content should often sit close to implied borders.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, default surface for most content blocks. |
| 1 | Smoke Grey | `#f4f4f4` | Secondary background for specific hero sections or content areas to create subtle visual separation. |

## Imagery

The site uses a mix of high-quality product photography and occasionally vibrant, conceptual illustrations within its portfolio pieces, but these are largely contained within defined content blocks. UI-wise, imagery is minimal and serves a functional or demonstrative purpose. Photography is typically clean, with subjects clearly delineated; illustrations lean towards bold, often abstract forms within a specific brand's palette. Icons are outlined, Ink Black (#000000) on Canvas White (#ffffff), maintaining the high-contrast aesthetic with a very fine stroke weight. Imagery is contained, often within implicit 0px radius cards, and does not overlap elements. The density is relatively high, with images and text often occupying equal visual space in a balanced, grid-like manner.

## Layout

The page adheres to a full-bleed layout, where content stretches to the viewport edges, creating a continuous canvas. The hero section is characterized by large, impactful typography that extends across the full width. Section rhythm is driven by sharp, 1px Ink Black (#000000) horizontal and vertical dividing lines, creating a visual grid system often with large whitespace blocks. Content is arranged in alternating patterns, frequently split into two main columns, with text-heavy blocks contrasting with image or embedded video blocks. The layout emphasizes strong vertical alignment and horizontal flow, with extensive use of 1px borders to define content areas. Navigation is a minimalist top-bar, fixed and sticky, composed of text links and ghost buttons. Density varies, with large headlines and ample whitespace on some sections, while others present information in more compact, grid-based arrangements.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #000000
- accent: no distinct accent color
- primary action: no distinct CTA color

Example Component Prompts:
- Create a section divider: 1px solid border, color #000000, full-width. 
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create a main headline: 'Bold Statement' in Basis 110px (weight 600), color #000000, letter-spacing -0.04em, line-height 1.0.
- Create an input field: Background transparent, 1px solid #000000 border, 0px border-radius. Placeholder text 'Enter text here' in Canvas White, text input color #000000, Basis 16px font.

## Similar Brands

- **Huge** — Similar high-contrast, minimalist aesthetic with strong typography and minimal decorative elements.
- **Pentagram** — Emphasizes a grid-based layout and sophisticated typography over rich imagery, focusing on clear communication.
- **Work & Co** — Known for clean, functional interfaces with strong typographic hierarchy and a limited color palette.
- **Manual (Design Studio)** — Strong use of black and white, sharp lines, and a focus on content over heavy UI styling.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-smoke-grey: #f4f4f4;
  --color-muted-stone: #808080;
  --color-divider-line: #262626;

  /* Typography — Font Families */
  --font-basis: 'Basis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-mono: 'Basis Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.01px;
  --text-subheading: 48px;
  --leading-subheading: 1;
  --tracking-subheading: -0.02px;
  --text-heading: 60px;
  --leading-heading: 1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 110px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 226px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 200px;
  --card-padding: 16px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-default: 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-smoke-grey: #f4f4f4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-smoke-grey: #f4f4f4;
  --color-muted-stone: #808080;
  --color-divider-line: #262626;

  /* Typography */
  --font-basis: 'Basis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-mono: 'Basis Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.01px;
  --text-subheading: 48px;
  --leading-subheading: 1;
  --tracking-subheading: -0.02px;
  --text-heading: 60px;
  --leading-heading: 1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 110px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 226px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-200: 200px;
}
```
