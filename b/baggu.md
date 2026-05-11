# Baggu — Style Reference
> Earthy utilitarian canvas

**Theme:** light

Baggu presents a playful, utilitarian aesthetic with a grounded, earthy color palette and a strong geometric type identity. The design emphasizes clear, highly contrasted text against muted backgrounds, allowing product photography to introduce most of the vibrancy. Components are minimal, relying on strong typography and subtle borders for structure rather than heavy shadows or complex gradients. The overall density is compact yet breathable, making product information accessible without feeling crowded.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#f6f4ee` | `--color-canvas-parchment` | Page backgrounds, card surfaces, ghost button backgrounds, input backgrounds |
| Night Ink | `#000000` | `--color-night-ink` | Primary text, headings, icons, borders, filled button backgrounds. Creates high contrast against Canvas Parchment for maximum readability |
| Faded Stone | `#7b7a77` | `--color-faded-stone` | Muted secondary text, subtle borders, helper text |
| Vivid Green | `#298018` | `--color-vivid-green` | Green outline accent for tags, dividers, and focused UI edges |

## Tokens — Typography

### studioPro — Primary typeface for all text elements: headings, body copy, links, buttons, and navigation. Its geometric clarity and varied weights establish a modern, approachable tone. The specific font features for numbers and characters contribute to its distinctive identity. · `--font-studiopro`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.38, 1.50
- **Letter spacing:** -0.0250em at 18px headings, -0.0100em at 14px, normal at 12px
- **OpenType features:** `"case", "ss02" 0, "ss03", "ss06", "ss07", "ss08", "ss09"`
- **Role:** Primary typeface for all text elements: headings, body copy, links, buttons, and navigation. Its geometric clarity and varied weights establish a modern, approachable tone. The specific font features for numbers and characters contribute to its distinctive identity.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2, 1.5
- **Role:** Times — detected in extracted data but not described by AI

### Metropolis — Metropolis — detected in extracted data but not described by AI · `--font-metropolis`
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.14
- **Letter spacing:** -0.004
- **Role:** Metropolis — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 14px | 1.38 | -0.01px | `--text-body` |
| heading | 18px | 1.2 | -0.025px | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 44 | 44px | `--spacing-44` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 4px |
| buttons | 24px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Navigation Link
**Role:** Top navigation menu items and info links.

Typography: studioPro, 400 weight, 16px size. Default color is Night Ink (#000000). No explicit padding, relying on natural text spacing, with potential 16px right padding for grouping. Underscored on hover.

### Primary Ghost Button
**Role:** Interactive elements with a minimal visual footprint, such as 'Shop' or product info actions.

Background: Canvas Parchment (#f6f4ee), Text: Night Ink (#000000). Border: Night Ink (#000000), 0px rounded, 0px padding. Uses the dominant page background for its surface, with text providing the interaction cue.

### Product Thumbnail Card
**Role:** Displays product images in a grid layout.

Implicitly uses Canvas Parchment (#f6f4ee) as background. No explicit borders or shadows, relying on surrounding spacing to define the boundary. Images are full-bleed within their card area.

### Product Grid Item
**Role:** Contains product image, name, and price.

Image followed by text. Product name (studioPro 400, 14px, Night Ink #000000) and price (studioPro 400, 14px, Night Ink #000000) are vertically stacked. Overall padding is 16px around the content.

### Accent Filled Button
**Role:** Call-to-action button, e.g., 'SUBSCRIBE'.

Background: Night Ink (#000000), Text: Canvas Parchment (#f6f4ee). Border radius: 24px (pill shape). Padding: 0px top/bottom, 20px left/right. The high contrast makes this button prominent.

### Text Input Field
**Role:** Standard text input for forms, e.g., email subscription.

Background: Canvas Parchment (#f6f4ee). Border color: Canvas Parchment (#f6f4ee), 4px radius. Uses Vivid Green (#298018) for text after input. Padding: 6px top, 8px bottom, 0px left/right.

## Do's and Don'ts

### Do
- Prioritize Canvas Parchment (#f6f4ee) as the dominant background for body and surface elements to maintain a light, airy feel.
- Use Night Ink (#000000) for all primary text, headings, and essential UI elements to guarantee maximum contrast and readability.
- Employ studioPro at various weights and sizes as the sole typeface to maintain a consistent geometric and modern typographic voice.
- Apply 24px border-radius for high-impact buttons to create a soft, pill-like shape, distinguishing them from other UI elements.
- Utilize Vivid Green (#298018) sparingly as an accent for critical links or semantic indicators, ensuring it stands out against the neutral palette.
- Maintain a compact elementGap of 4px to keep related content visually grouped and optimize information density.
- Construct interaction prompts and buttons with minimal styling, defaulting to text-based links or ghost buttons unless a strong call to action requires a filled background.

### Don't
- Avoid using multiple typefaces; studioPro is the singular brand voice.
- Do not introduce strong drop shadows; the design relies on flat surfaces and subtle borders for depth.
- Refrain from complex background gradients; the aesthetic is grounded in solid, earthy colors.
- Do not deviate from the 4px base unit for spacing, as it dictates the compact density of the layout.
- Avoid arbitrary color usage; decorative elements should integrate with the existing neutral and single-brand accent palette.
- Do not use generic button shapes; buttons should be either 0px radius for ghost actions or 24px radius for prominent filled actions.
- Do not introduce heavy panels or strong visual separators for cards; rely on natural content grouping and Canvas Parchment for surfaces.

## Imagery

The imagery predominantly features product photography, often against plain, uniform light gray or white backgrounds. Products are isolated and well-lit, with occasional styled shots that introduce human elements (hands, legs) to showcase scale and usage without distracting from the item itself. The photography has a clean, editorial look, emphasizing the product's texture and form. Icons are minimal, utilizing the brand's primary text color (#000000) and an outlined style. Imagery is heavy, particularly in product grids, dominating visual space while text plays a supporting role.

## Layout

The page employs a max-width contained layout, not overtly full-bleed, typically centered on the screen. The hero section frequently showcases a split with a central product image or a curated visual, with navigation elements positioned at the top edge. Sections are distinct, often using consistent vertical spacing, creating a clean flow. Content is arranged in flexible grids, particularly for product displays, which show multiple items per row (e.g., 3-column product grids). Text content often appears below images in a stacked format. The primary navigation is a compact, minimal top bar, with functional icons for search and cart.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f6f4ee
border: #000000
accent: #298018
primary action: no distinct CTA color

Example Component Prompts:
Create a navigation bar: Background Canvas Parchment (#f6f4ee). Left text 'SHOP' and 'INFO' (studioPro 400, 16px, Night Ink #000000). Right text 'CART (0)' and search icon (studioPro 400, 16px, Night Ink #000000).
Create a product grid item: Containing a product image. Below it, 'Nylon Bowler Bag' (studioPro 400, 14px, Night Ink #000000), followed by price '$58' (studioPro 400, 14px, Night Ink #000000). Entire item has 16px padding.
Create a subscribe button: Background Night Ink (#000000), text 'SUBSCRIBE' (studioPro 400, 14px, Canvas Parchment #f6f4ee), 24px border-radius, 20px horizontal padding.
Create an input field: Background Canvas Parchment (#f6f4ee), placeholder text 'Email address' (studioPro 400, 14px, Faded Stone #7b7a77). Border Canvas Parchment (#f6f4ee) with 4px radius. Text input color Vivid Green (#298018).

## Similar Brands

- **Aritzia** — Similar light, earthy tone with high-contrast black text and a strong focus on product photography against clean backgrounds.
- **Everlane** — Shared minimalist aesthetic with high-quality product imagery, often isolating products on neutral backdrops, and a strong, clean geometric typeface.
- **Cuyana** — Features a similar premium product focus within a neutral color palette, relying on strong typography and understated UI elements for a refined feel.
- **Glossier** — While more colorful, it shares the use of product isolation, a clean type treatment, and a generally light background with pops of branding color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #f6f4ee;
  --color-night-ink: #000000;
  --color-faded-stone: #7b7a77;
  --color-vivid-green: #298018;

  /* Typography — Font Families */
  --font-studiopro: 'studioPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-metropolis: 'Metropolis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.01px;
  --text-heading: 18px;
  --leading-heading: 1.2;
  --tracking-heading: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-44: 44px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-inputs: 4px;
  --radius-buttons: 24px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #f6f4ee;
  --color-night-ink: #000000;
  --color-faded-stone: #7b7a77;
  --color-vivid-green: #298018;

  /* Typography */
  --font-studiopro: 'studioPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-metropolis: 'Metropolis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.01px;
  --text-heading: 18px;
  --leading-heading: 1.2;
  --tracking-heading: -0.025px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-44: 44px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 24px;
}
```
