# Eduardo del Fraile — Style Reference
> Gallery Black Canvas

**Theme:** dark

Eduardo del Fraile's visual identity is a high-contrast, minimalist showcase of striking product photography. Against a deep, expansive black canvas, content is primarily visual, featuring starkly lit objects. Typographic elements are understated, monochrome, and serve purely functional navigation or descriptive roles. The design prioritizes the visual impact of the work itself, with the UI receding into the background.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Page background, primary canvas, content backdrop, providing infinite depth for product photography |
| Ghost White | `#ffffff` | `--color-ghost-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Muted Gray | `#888888` | `--color-muted-gray` | Secondary text, helper messages, less prominent links — a softer, less assertive contrast than Ghost White |

## Tokens — Typography

### AkzidenzGrotesk — The primary typeface for all textual content, including navigation and body text. Its clean, sans-serif lines support legibility without distracting from the visual content. · `--font-akzidenzgrotesk`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 14px, 15px, 20px, 21px
- **Line height:** 1.30
- **Letter spacing:** normal
- **Role:** The primary typeface for all textual content, including navigation and body text. Its clean, sans-serif lines support legibility without distracting from the visual content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.3 | — | `--text-caption` |
| body-sm | 15px | 1.3 | — | `--text-body-sm` |
| body | 20px | 1.3 | — | `--text-body` |
| body-lg | 21px | 1.3 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |

### Layout

- **Section gap:** 20px
- **Card padding:** 15px
- **Element gap:** 10px

## Components

### Header Navigation Link
**Role:** Primary navigation element

Ghost White text at 15px, AkzidenzGrotesk weight 400. Borders are only present on interaction.

### Brand Logo Text
**Role:** Site identifier

Eduardo del Fraile text at 15px, AkzidenzGrotesk weight 700, Ghost White color.

### Muted Helper Text
**Role:** Contextual navigation or instructional text

Muted Gray text at 14px, AkzidenzGrotesk weight 400. Used for footer instructions.

## Do's and Don'ts

### Do
- Use Void Black (#000000) as the universal page background to provide a consistent dark canvas.
- Utilize Ghost White (#ffffff) for all primary text and interactive elements to ensure high contrast and highlight focus.
- Reserve Muted Gray (#888888) for secondary information or less prominent interactive elements.
- Employ AkzidenzGrotesk (or substitute Inter) for all typography, maintaining a consistent sans-serif aesthetic.
- Apply AkzidenzGrotesk weight 700 for brand names and critical headings, and weight 400 for body and navigation text.
- Maintain a default line height of 1.30 across all text sizes for optimal legibility within dense content blocks.
- Implement 10px padding around primary content blocks within elements and 20px for vertical spacing between sections.

### Don't
- Avoid the use of any chromatic colors in the UI layer; colors should be reserved for content (product photography) only.
- Do not introduce gradients or heavy shadows on UI elements; maintain a flat, minimalist interface aesthetic.
- Refrain from using any borders or backgrounds on navigation links unless specifically for an active or hover state.
- Avoid crowded layouts; prioritize negative space around focal content to enhance its impact.
- Do not use generic system fonts; AkzidenzGrotesk (or its substitute) must be consistently applied.
- Never use text smaller than 14px or larger than 21px for UI elements to maintain visual rhythm.

## Imagery

The site primarily features product photography and 3D renders. Images are treated as hero content, often against the deep black background, showcasing objects in stark, high-contrast lighting. The focus is on the object itself, often with a raw or sculptural quality, without lifestyle context. Imagery is full-bleed or large-scale, dominating the visual space, serving a product showcase and decorative atmosphere role. No specific icon style is discernable beyond a simple Instagram icon.

## Layout

The page uses a full-bleed, dark canvas model. The hero section features large-scale product imagery spanning the width of the viewport. Content then flows vertically with a consistent spacing, showcasing individual projects via immersive visuals. The overall layout is centered and horizontal, giving each product equal visual weight. Navigation is a minimal top-right header, disappearing into the background, with the brand name on the top-left.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #ffffff
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Header Navigation item: 'Work' text, AkzidenzGrotesk weight 400, 15px size, Ghost White (#ffffff).
2. Create a Brand Title: 'Eduardo del Fraile' text, AkzidenzGrotesk weight 700, 15px size, Ghost White (#ffffff).
3. Create Footer Instructional Text: 'Scroll with the mouse' text, AkzidenzGrotesk weight 400, 14px size, Muted Gray (#888888).

## Similar Brands

- **AIGA Design Archives** — Monochromatic interface that prioritizes showcasing visual work without distracting UI elements.
- **Pentagram** — Minimalist navigation and focus on large, impactful imagery to present design projects.
- **The Brand Identity** — High-contrast dark mode with white typography, emphasizing visual content over complex UI.
- **Apple's product pages (for specific products)** — Using a dark, expansive background to highlight individual products with stark lighting and minimal text.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-ghost-white: #ffffff;
  --color-muted-gray: #888888;

  /* Typography — Font Families */
  --font-akzidenzgrotesk: 'AkzidenzGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.3;
  --text-body-sm: 15px;
  --leading-body-sm: 1.3;
  --text-body: 20px;
  --leading-body: 1.3;
  --text-body-lg: 21px;
  --leading-body-lg: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;

  /* Layout */
  --section-gap: 20px;
  --card-padding: 15px;
  --element-gap: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-ghost-white: #ffffff;
  --color-muted-gray: #888888;

  /* Typography */
  --font-akzidenzgrotesk: 'AkzidenzGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.3;
  --text-body-sm: 15px;
  --leading-body-sm: 1.3;
  --text-body: 20px;
  --leading-body: 1.3;
  --text-body-lg: 21px;
  --leading-body-lg: 1.3;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
}
```
