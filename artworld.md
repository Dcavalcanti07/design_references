# ARTWORLD — Style Reference
> monochrome gallery canvas

**Theme:** dark

ARTWORLD projects an austere, gallery-like visual identity, dominated by stark black and white. Typography takes center stage, mixing a bold, modern sans-serif with an elegant serif in both regular and italic styles. The layout is spacious, giving elements ample room to breathe, while interactions are subtly expressed through text-only links and ghost borders.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Black | `#000000` | `--color-canvas-black` | Page backgrounds, primary text, structural borders, logo text — creates a high-contrast, bold foundation |
| Surface White | `#ffffff` | `--color-surface-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |

## Tokens — Typography

### Graphik Light — Body text, navigation links, secondary information, and small descriptive labels. · `--font-graphik-light`
- **Substitute:** Inter
- **Weights:** 300
- **Sizes:** 12px, 16px, 20px
- **Line height:** 1.20, 1.50, 1.58
- **Letter spacing:** -0.0650em
- **Role:** Body text, navigation links, secondary information, and small descriptive labels.

### Cardinal Fruit — Primary headings and brand elements, conveying a sophisticated and art-focused aesthetic. · `--font-cardinal-fruit`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 18px, 65px, 75px
- **Line height:** 1.00, 1.09, 1.20
- **Letter spacing:** -0.0310em, -0.0100em
- **Role:** Primary headings and brand elements, conveying a sophisticated and art-focused aesthetic.

### Cardinal Fruit Italic — Display headings, artist names, and highlighted textual content to add emphasis and elegance. · `--font-cardinal-fruit-italic`
- **Substitute:** Playfair Display Italic
- **Weights:** 300
- **Sizes:** 16px, 65px, 75px
- **Line height:** 1.00, 1.09, 1.50
- **Letter spacing:** -0.0310em, -0.0100em
- **Role:** Display headings, artist names, and highlighted textual content to add emphasis and elegance.

### Cardinal Classic Italic — Specialized body contexts, captions, and footers, offering a subtle, refined touch. · `--font-cardinal-classic-italic`
- **Substitute:** Playfair Display Italic
- **Weights:** 300
- **Sizes:** 18px
- **Line height:** 1.20
- **Letter spacing:** -0.0110em
- **Role:** Specialized body contexts, captions, and footers, offering a subtle, refined touch.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.78px | `--text-caption` |
| body-sm | 16px | 1.5 | -1.04px | `--text-body-sm` |
| body | 18px | 1.2 | -0.198px | `--text-body` |
| body-lg | 20px | 1.58 | -1.3px | `--text-body-lg` |
| display-sm | 65px | 1 | -2.015px | `--text-display-sm` |
| display | 75px | 1.09 | -0.75px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 49 | 49px | `--spacing-49` |
| 76 | 76px | `--spacing-76` |
| 90 | 90px | `--spacing-90` |
| 95 | 95px | `--spacing-95` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Do's and Don'ts

### Do
- Use Canvas Black (#000000) for all primary backgrounds and primary text.
- Apply Surface White (#ffffff) for inverse text or decorative elements on dark backgrounds.
- Prioritize Graphik Light (300) for all functional text, maintaining -0.0650em letter-spacing.
- Reserve Cardinal Fruit (300) and its italic variants for headings and prominent textual features, using specific letter-spacing values like -0.0310em or -0.0100em.
- Maintain a spacious density for all layouts, with a minimum element gap of 20px and section gap of 40px.
- Ensure all interactive elements are text-based or have subtle ghost borders in Canvas Black (#000000).
- Adhere to a strict monochrome palette; avoid introducing any chromatic colors unless explicitly stated for semantic purposes (which are not present in this system).

### Don't
- Do not use box shadows or other elevation effects; all surfaces should remain flat.
- Avoid colored backgrounds or elements other than Canvas Black (#000000) or Surface White (#ffffff).
- Do not introduce rounded corners; maintain sharp, crisp edges for all elements.
- Refrain from using heavily decorative gradients or textures.
- Do not deviate from the specified font families, weights, and letter-spacing values to maintain the distinct typographic hierarchy.
- Avoid dense, information-packed layouts; preserve ample whitespace around elements.
- Do not use explicit button backgrounds for primary actions; rely on text-only links or ghost borders defined by Canvas Black.

## Imagery

This system features no visible photographic or illustrative imagery on the main white canvas. The visual language is purely typographic, with the exception of possible small, unobtrusive icons that would maintain the monochrome, crisp aesthetic. The brand identity is communicated through font choices and composition rather than pictorial content.

## Layout

The page operates on a full-bleed structure, with content (primarily text) filling the horizontal space. The hero section is characterized by large, often italicized display typography. Sections exhibit consistent vertical spacing, creating an airy, uncrowded experience. Content is arranged in stacked text blocks, with some elements appearing in two-column structures implicitly through alignment rather than explicit grids. Navigation is minimal, likely integrated as discreet text links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #000000
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary heading: 'ARTWORLD' using Cardinal Fruit (300) at 75px, #000000, letter-spacing -0.75px.
2. Create an artist name list item: 'Marc Hibbert' using Cardinal Fruit Italic (300) at 65px, #000000, letter-spacing -2.015px.
3. Create a body text paragraph: 'is an Artist Management Agency, launched in 2017 we develop...' using Graphik Light (300) at 20px, #000000, letter-spacing -1.3px.

## Similar Brands

- **The Row** — Minimalist, monochrome aesthetic with text-focused layouts and luxury typography.
- **A-POC by Issey Miyake** — Emphasis on singular statement typefaces, high contrast black and white, and refined, spacious layouts.
- **Studio Dielman** — Stark, type-driven design with limited color palette and a clear, almost architectural approach to spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-black: #000000;
  --color-surface-white: #ffffff;

  /* Typography — Font Families */
  --font-graphik-light: 'Graphik Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-fruit: 'Cardinal Fruit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-fruit-italic: 'Cardinal Fruit Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-classic-italic: 'Cardinal Classic Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.78px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -1.04px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.198px;
  --text-body-lg: 20px;
  --leading-body-lg: 1.58;
  --tracking-body-lg: -1.3px;
  --text-display-sm: 65px;
  --leading-display-sm: 1;
  --tracking-display-sm: -2.015px;
  --text-display: 75px;
  --leading-display: 1.09;
  --tracking-display: -0.75px;

  /* Typography — Weights */
  --font-weight-light: 300;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-49: 49px;
  --spacing-76: 76px;
  --spacing-90: 90px;
  --spacing-95: 95px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-black: #000000;
  --color-surface-white: #ffffff;

  /* Typography */
  --font-graphik-light: 'Graphik Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-fruit: 'Cardinal Fruit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-fruit-italic: 'Cardinal Fruit Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cardinal-classic-italic: 'Cardinal Classic Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.78px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -1.04px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.198px;
  --text-body-lg: 20px;
  --leading-body-lg: 1.58;
  --tracking-body-lg: -1.3px;
  --text-display-sm: 65px;
  --leading-display-sm: 1;
  --tracking-display-sm: -2.015px;
  --text-display: 75px;
  --leading-display: 1.09;
  --tracking-display: -0.75px;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-49: 49px;
  --spacing-76: 76px;
  --spacing-90: 90px;
  --spacing-95: 95px;
}
```
