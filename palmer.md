# Palmer — Style Reference
> Warm gallery space

**Theme:** light

Palmer embraces a tactile, gallery-like aesthetic, presenting dinnerware as curated art objects on an expansive, warm off-white canvas. The visual system is anchored by deep, earthy neutrals that provide a grounded contrast to the product photography. Typography is delicate yet authoritative, using generous letter-spacing to emphasize its custom font. Interaction elements are subtle and demure, blending into the background through ghosted styles and soft, rounded edges, allowing the product to remain the sole focal point.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Creme | `#f5f6ee` | `--color-canvas-creme` | Page backgrounds, card surfaces, ghost button backgrounds – a soft, warm off-white that creates an expansive, inviting backdrop for the dinnerware |
| Inkwell | `#222222` | `--color-inkwell` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Chalk White | `#ffffff` | `--color-chalk-white` | Decorative highlights, text on dark backgrounds when contrast is critical – a crisp white used sparingly to provide visual lift or ensure readability on darker elements |
| Shadow Grey | `#a1a19c` | `--color-shadow-grey` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Deep Licorice | `#000000` | `--color-deep-licorice` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### TWK Lausanne — All textual content, from headings to body text and interactive elements. Its custom nature and varying letter-spacing contribute to Palmer's distinctive typographic voice, feeling refined and spacious. · `--font-twk-lausanne`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 120px
- **Line height:** 0.90, 1.40
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em
- **Role:** All textual content, from headings to body text and interactive elements. Its custom nature and varying letter-spacing contribute to Palmer's distinctive typographic voice, feeling refined and spacious.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | -0.44px | `--text-caption` |
| body | 14px | 1.4 | -0.42px | `--text-body` |
| heading | 18px | 1.4 | -0.36px | `--text-heading` |
| display | 120px | 0.9 | -4.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 66 | 66px | `--spacing-66` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| nav | 3px |
| tags | 100px |
| cards | 9px |
| buttons | 0px |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 12px

## Components

### Ghost Button
**Role:** Default interactive element, secondary actions

Transparent background with Inkwell text and a 1px Inkwell border. Padding is minimal or zero for a light, minimalist look. Letter-spacing is typically -0.0200em for a refined appearance. Ex: 'experience view' button

### Dark Overlay Button
**Role:** Navigation and primary controls

Deep Licorice background with Chalk White text and a 3px border-radius. Padding is 7px for a compact yet solid presence. Used for main navigation items like 'menu' and 'filter'.

### Product Card
**Role:** Displaying individual dinnerware pieces

These cards appear transparent, allowing the Canvas Creme background to show through. Some instances feature a subtle 9px border-radius to soften their edges, while others are sharp 0px. They have no explicit padding or shadow, relying on the imagery and its drop shadow for visual separation.

### Circular Tag
**Role:** Filters and categorization

Implicitly defined by a 100px border-radius, these tags take on a pill-like or circular shape. Text is Inkwell, typically with generous letter-spacing. Background is often Canvas Creme with a subtle Inkwell border.

## Do's and Don'ts

### Do
- Prioritize Canvas Creme (#f5f6ee) as the primary background for all content, creating an airy, gallery-like feel.
- Use Inkwell (#222222) for all primary body text, headings, and interactive element borders.
- Apply TWK Lausanne with generous letter-spacing (-0.0200em to -0.0400em) to all textual elements, emphasizing its custom, refined character.
- Employ ghosted button styles for most interactive elements, using `background-color: transparent` and a thin Inkwell (#222222) border.
- Maintain a clear elementGap of 12px for spacing between most UI elements, supporting a comfortable density.
- Utilize a 9px border-radius for softer contained elements, otherwise prefer 0px for sharp, clean edges as seen on some cards and buttons.
- For top-level navigation, use Deep Licorice (#000000) as background for strong visual anchors. They should be compact with 7px padding and a 3px border radius.

### Don't
- Avoid strong, saturated colors for UI elements; color should primarily come from product photography.
- Do not use heavy shadows or distinct background colors for product cards; let the product imagery and its built-in shadows define elevation.
- Resist using tight letter-spacing on any font; the ample spacing of TWK Lausanne is a core part of the brand identity.
- Do not introduce complex gradients or textures into UI backgrounds or components; surfaces should remain flat and monochromatic.
- Refrain from using bold type weights for emphasis in body copy; weight 300-500 should dominate to maintain the delicate aesthetic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Base Canvas | `#f5f6ee` | The primary background for the entire application, creating an open and airy foundation. |
| 2 | Product Card Surface | `#f5f6ee` | These surfaces are transparent, blending into the Base Canvas. Elevation is implied solely by product imagery and its soft shadows. |
| 3 | Navigation Bar | `#000000` | A solid opaque surface used for the bottom navigation, providing a strong, contrasting anchor for interactive controls. |

## Elevation

- **Product Card (implied):** `The product images themselves have embedded soft drop shadows, creating an illusion of depth without explicit UI element shadows. Actual CSS shadows on page elements are not detected as distinct design system tokens.`

## Agent Prompt Guide

Quick Color Reference:
text: #222222
background: #f5f6ee
border: #222222
accent: none observed
primary action: no distinct CTA color

3-5 Example Component Prompts:
1. Create a transparent top-left logo area: TWK Lausanne weight 400 heading text 'palmer', color #222222. Above it, a ghost button 'experience view' with TWK Lausanne weight 400 body-sm text, color #222222, 1px border #222222, and 0px padding, 0px radius.
2. Design a minimalist bottom navigation bar: #000000 background, 3px border-radius. Include two ghost buttons side-by-side, each with 'menu' or 'filter' text of TWK Lausanne weight 400 body-sm at #ffffff, with 7px padding.
3. Display a dinnerware product card: The card itself is visually transparent (matches Canvas Creme background #f5f6ee, no border, no shadow, 0px or 9px radius). Its content is a product image which already includes a subtle soft shadow, presented without additional UI elements obscuring it. The text 'collection' below it uses TWK Lausanne weight 400 body text, color #222222, with a 12px gap from the image.
4. Produce a detailed product view heading: TWK Lausanne weight 500 display text, color #222222, line-height 0.9, letter-spacing -4.8px ('E x p l o r e P a l m e').

## Similar Brands

- **Figma** — Restrained use of color, relying mostly on neutrals and a single accent, with an emphasis on clarity and function.
- **Stripe** — Clean, spacious layouts with subtle interactive elements and a strong focus on typography and product presentation.
- **Apple (product pages)** — Minimalist backgrounds allowing products to be the hero, using subtle shadows for depth and elegant, custom-feeling typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-creme: #f5f6ee;
  --color-inkwell: #222222;
  --color-chalk-white: #ffffff;
  --color-shadow-grey: #a1a19c;
  --color-deep-licorice: #000000;

  /* Typography — Font Families */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: -0.44px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.42px;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --tracking-heading: -0.36px;
  --text-display: 120px;
  --leading-display: 0.9;
  --tracking-display: -4.8px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-66: 66px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 9px;
  --radius-3xl: 24px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-nav: 3px;
  --radius-tags: 100px;
  --radius-cards: 9px;
  --radius-buttons: 0px;

  /* Surfaces */
  --surface-base-canvas: #f5f6ee;
  --surface-product-card-surface: #f5f6ee;
  --surface-navigation-bar: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-creme: #f5f6ee;
  --color-inkwell: #222222;
  --color-chalk-white: #ffffff;
  --color-shadow-grey: #a1a19c;
  --color-deep-licorice: #000000;

  /* Typography */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: -0.44px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.42px;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --tracking-heading: -0.36px;
  --text-display: 120px;
  --leading-display: 0.9;
  --tracking-display: -4.8px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-66: 66px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 9px;
  --radius-3xl: 24px;
  --radius-full: 100px;
}
```
