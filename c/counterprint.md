# Counterprint — Style Reference
> Graphic design manual on white canvas

**Theme:** light

Counterprint's visual system evokes a precise, almost utilitarian aesthetic, reminiscent of classic design publishing. The core palette is primarily achromatic, relying on sharp black text against stark white surfaces and soft gray borders. Typography is confident and compact, favoring a system sans-serif for most content, with a custom geometric sans-serif for specific branding. Components are lightweight, emphasizing function over embellishment, with generous use of infinite border-radius for buttons and subtle rounded corners for input fields, providing a touch of approachability within the otherwise rigorous structure.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, hero sections, and primary surface fills. Provides a clean, bright foundation |
| Text Black | `#1c1c1c` | `--color-text-black` | Primary text color for headings, body copy, links, and icons. Establishes strong contrast against light surfaces |
| Border Gray | `#e5e7eb` | `--color-border-gray` | Subtle borders for separating elements, list dividers, and outlined buttons. Defines structure without adding visual weight |

## Tokens — Typography

### Helvetica — Dominant typeface for all interface elements, body text, links, and buttons. Its compact tracking and neutral character contribute to the system's precise, information-dense feel. · `--font-helvetica`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 15px, 20px
- **Line height:** 1.00
- **Letter spacing:** -0.025em
- **Role:** Dominant typeface for all interface elements, body text, links, and buttons. Its compact tracking and neutral character contribute to the system's precise, information-dense feel.

### GTStandard-M — Used for specific branding elements and potentially some content accents, providing a distinct, non-system font texture. · `--font-gtstandard-m`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used for specific branding elements and potentially some content accents, providing a distinct, non-system font texture.

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 11 | 11px | `--spacing-11` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 23 | 23px | `--spacing-23` |
| 28 | 28px | `--spacing-28` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 15px |
| others | 9999px |
| buttons | 9999px |

### Layout

- **Section gap:** 28px
- **Card padding:** 8px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Interactive element

Ghost button with Text Black text on Canvas White background, outlined by Border Gray. Features a 9999px border-radius for a soft, pill-like appearance. Padding is 3.75px vertical and 7.5px horizontal. Uses Helvetica 15px, weight 400.

### Text Link Button
**Role:** Interactive element

Minimalist button appearing as plain text in Text Black, on a transparent background. No explicit padding or border-radius, aligning with content flow. Used for secondary actions or navigation items. Uses Helvetica 15px.

### Search Input Field
**Role:** Data entry

Transparent background input with Text Black text and a Text Black border. Features a 15px border-radius for a softly rounded aesthetic. Padding is 3.75px vertical and 7.5px horizontal. Uses Helvetica 15px.

### Product Grid Item
**Role:** Display component for products

Displays product images, names, and prices. The items are tightly packed with 8px horizontal and 19px vertical spacing between elements. Text is Text Black on a Canvas White background.

### Nav Menu Item
**Role:** Navigation link

Navigation links use Text Black on transparent backgrounds, often outlined with Border Gray, indicating active or hover states. Helvetica 15px, weight 400 is used.

## Do's and Don'ts

### Do
- Use Canvas White (#ffffff) as the default background for all page surfaces and major content blocks.
- Implement Text Black (#1c1c1c) for all primary text, headings, and functional icons to maintain high contrast.
- Apply Border Gray (#e5e7eb) for all hairline separators, subtle outlines, and inactive interactive component borders.
- Utilize 9999px border-radius for all pill-shaped buttons and tags, creating a soft, approachable boundary.
- Maintain a compact typographical rhythm with Helvetica (or system-ui sans-serif substitute) at a letter-spacing of -0.025em for all prominent text.
- Adhere to an 8px base unit for horizontal spacing between elements and 4px for fine-tuned vertical padding.

### Don't
- Avoid introducing additional saturated colors unless explicitly for semantic states (e.g., error) or specific brand-approved product imagery, as the system is intentionally achromatic.
- Do not use heavy shadows or deeply colored backgrounds; surface elevation should be minimal and almost imperceptible, achieved through subtle borders where needed.
- Refrain from using large, decorative typefaces for headlines; the system prioritizes compact, functional typography.
- Do not deviate from the established border-radius values (9999px for buttons/tags, 15px for inputs); arbitrary rounded corners will disrupt the system's feel.
- Avoid excessive padding around interface elements; the site employs a compact density, maximizing information visibility.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and content areas |
| 2 | Border Gray | `#e5e7eb` | Subtle visual separation for lists and card-like elements |

## Imagery

The visual language relies heavily on product-focused photography and vibrant book cover art. Photography either features clean, high-key shots of books and products isolated on simple backgrounds (e.g., solid color blocks). Images are contained within rectangular frames, with no overlapping or complex masking. They are highly central to content, serving as both decorative atmosphere and explanatory content, occupying significant visual space in grid layouts.

## Layout

The page maintains a full-width, non-contained layout, allowing content to stretch across the browser window. The hero section features a dynamic, full-bleed split visual with two large product images. Content is primarily arranged in a dense, multi-column grid for product listings, with consistent vertical spacing between sections. Navigation is minimalist, residing in a lightweight top bar that appears fixed on scroll.

## Agent Prompt Guide

Quick Color Reference: text: #1c1c1c, background: #ffffff, border: #e5e7eb, accent: no distinct accent color, primary action: no distinct CTA color

Example Component Prompts:
1. Create a header: Canvas White background, Text Black text. Right-aligned ghost buttons for 'Menu', 'Search', 'Cart' with 9999px radius, Border Gray outline, 3.75px vertical, 7.5px horizontal padding, Helvetica 15px 400.
2. Design a product grid item: Canvas White background. Product image at top, followed by Helvetica 15px 400 Text Black product title, then price below. Items should be spaced 8px horizontally and 19px vertically.
3. Create a navigation text link: Text Black, Helvetica 15px 400, on a transparent background, no padding or borders. Used in a list format, each item separated by Border Gray line.

## Similar Brands

- **Unit Editions** — Shares a similar minimal aesthetic with strong typography and product-focused imagery in a publishing context.
- **Taschen** — Employs clean, grid-based layouts to showcase books, relying on high-quality product photography and a subdued color palette.
- **Actual Source** — Features a similar web presence for design books, characterized by bold, structured layouts and a strong focus on visual content with minimal UI embellishment.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-text-black: #1c1c1c;
  --color-border-gray: #e5e7eb;

  /* Typography — Font Families */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-base: 15px;
  --leading-base: 1.2;
  --text-xl: 20px;
  --leading-xl: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-23: 23px;
  --spacing-28: 28px;

  /* Layout */
  --section-gap: 28px;
  --card-padding: 8px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-inputs: 15px;
  --radius-others: 9999px;
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-border-gray: #e5e7eb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-text-black: #1c1c1c;
  --color-border-gray: #e5e7eb;

  /* Typography */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-base: 15px;
  --leading-base: 1.2;
  --text-xl: 20px;
  --leading-xl: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-23: 23px;
  --spacing-28: 28px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-full: 9999px;
}
```
