# Alpine Hearing Protection — Style Reference
> Warm minimalist canvas

**Theme:** light

Alpine Hearing Protection uses a soft, warm minimalist aesthetic with a focus on clear hierarchy and subtle branding. A soft off-white canvas provides a gentle backdrop for product-focused content. Typography is compact and confident, primarily in near-black for strong readability. A muted red acts as a key accent for calls to action and critical information, adding a touch of understated urgency.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#200e0e` | `--color-inkwell` | Primary text, core branding elements, active navigation links. Acts as the primary accent background for featured actions |
| Crimson Accent | `#ed212d` | `--color-crimson-accent` | Red decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Pale Peach | `#fde3d6` | `--color-pale-peach` | Text against dark backgrounds, ghost button text, icon fills |
| Sage Green | `#9ac9b5` | `--color-sage-green` | Decorative card backgrounds, accent surfaces for specific product categories |
| Rose Blush | `#dbb0b3` | `--color-rose-blush` | Decorative card backgrounds, accent surfaces for specific product categories |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card backgrounds, light surface elements, default input fills |
| Ghost White | `#f3e7e2` | `--color-ghost-white` | Subtle background for badges, soft borders, light elevation surfaces |
| Warm Linen | `#f8f0ec` | `--color-warm-linen` | Secondary surface backgrounds, card backgrounds, subtle section dividers |
| Ash Gray | `#d2cfcf` | `--color-ash-gray` | Hairline borders, subtle separators, disabled states |
| Pitch Black | `#000000` | `--color-pitch-black` | Secondary text, subtle borders, UI elements in specific contexts |
| Dark Slate | `#202020` | `--color-dark-slate` | Accented card backgrounds, dark mode product showcases |

## Tokens — Typography

### Antarctica — Primary typeface for all headings, body text, and UI elements. Its slightly compressed letterforms with careful tracking create a structured, refined, yet approachable feel across all scales. · `--font-antarctica`
- **Substitute:** Inter
- **Weights:** 400, 500, 545, 600
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 24px, 27px, 42px
- **Line height:** 1.10, 1.15, 1.20, 1.30, 1.45, 1.50, 1.60
- **Letter spacing:** -0.0200em at larger sizes (e.g. 42px), -0.0100em at mid-range (e.g. 24px)
- **Role:** Primary typeface for all headings, body text, and UI elements. Its slightly compressed letterforms with careful tracking create a structured, refined, yet approachable feel across all scales.

### GTStandard-M — Used sparingly for specific informational text, providing a neutral counterpoint to the primary typeface. · `--font-gtstandard-m`
- **Substitute:** Roboto
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for specific informational text, providing a neutral counterpoint to the primary typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.45 | — | `--text-caption` |
| body-lg | 14px | 1.5 | — | `--text-body-lg` |
| heading-sm | 18px | 1.3 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.24px | `--text-heading` |
| heading-lg | 27px | 1.15 | -0.27px | `--text-heading-lg` |
| display | 42px | 1.1 | -0.84px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 2.23px |

### Layout

- **Section gap:** 64px
- **Card padding:** 15px
- **Element gap:** 8px

## Components

### Ghost Text Button
**Role:** Interactive text link or action

backgroundColor: transparent, color: Inkwell (#200e0e), borderRadius: 2.23px, padding: 2px. Primarily used for inline actions and secondary navigation.

### Outline White Button
**Role:** Secondary action or navigation link

backgroundColor: transparent, color: Canvas White (#ffffff), border: 1px solid Canvas White (#ffffff), borderRadius: 0px. Used in hero sections or against dark backgrounds.

### Filled Inkwell Button
**Role:** Primary call to action button

backgroundColor: Inkwell (#200e0e), color: Pale Peach (#fde3d6), borderRadius: 3px, paddingTop: 12px, paddingRight: 16px, paddingBottom: 12px, paddingLeft: 14px. The main button for conversion-driving actions.

### Circular Ghost Button
**Role:** Icon-only button for navigation or controls

backgroundColor: transparent, color: Inkwell (#200e0e), border: 1px solid Inkwell (#200e0e), borderRadius: 100%. Provides interactive elements without distracting visual weight.

### Product Card
**Role:** Display individual products or features

backgroundColor: Warm Linen (#f8f0ec), borderRadius: 0px, boxShadow: none, padding: 0px. Used in grids for product listings, with content arranged internally.

### Dark Showcase Card
**Role:** Highlight premium products or specific features

backgroundColor: Dark Slate (#202020), borderRadius: 2.23px, boxShadow: none, padding: 0px. Provides contrast for specific product displays.

### Text Input Field
**Role:** Form entry for text values

backgroundColor: Canvas White (#ffffff), color: Inkwell (#200e0e), borderTopColor: Inkwell with 10% opacity, borderRadius: 3px, padding: 14px 12px. Input fields are subtle with a light border.

### Outline Badge
**Role:** Categorization or status indicator

backgroundColor: transparent, color: Inkwell (#200e0e), borderRadius: 0px, padding: 10px. Provides a low-key tag for product categories.

### Solid White Badge
**Role:** Highlight product status like 'Top Seller'

backgroundColor: Canvas White (#ffffff), color: Inkwell (#200e0e), borderRadius: 3px, padding: 5px 6px. Clearly visible status indicator on product cards.

## Do's and Don'ts

### Do
- Use Inkwell (#200e0e) for primary text and main calls to action.
- Maintain a clear visual hierarchy with Canvas White (#ffffff) and Warm Linen (#f8f0ec) as primary background surfaces, reserving Inkwell for text and priority elements.
- Apply a consistent border-radius of 2.23px to all interactive elements and contained components like cards and buttons for a unified soft look.
- Utilize Antarctica typeface for all content with dynamic letter-spacing (-0.0200em at large sizes, -0.0100em at mid-sizes) to maintain a compact, refined typographic density.
- Employ a section gap of 64px to create clear separation between content blocks.
- Emphasize only one primary action per view using the Filled Inkwell Button style.
- Use Ash Gray (#d2cfcf) for hairline borders and subtle separators to avoid heavy lines.

### Don't
- Do not introduce strong visual gradients or complex shadow effects; the system relies on flat surfaces and subtle background shifts.
- Avoid using Crimson Accent (#ed212d) as a primary button background; reserve it for semantic indicators or decorative elements.
- Do not deviate from the established type scale and letter-spacing for Antarctica; consistent typography reinforces the brand's precision.
- Do not use generic gray tones for backgrounds or text when Canvas White, Warm Linen, or Inkwell provide specific context and brand expression.
- Avoid large, impactful imagery that dominates the UI; imagery should be product-focused or subtly contextual, allowing UI elements to remain primary.
- Do not use highly saturated colors outside the defined accent palette; maintain a subdued and warm overall color temperature.
- Do not create complex layouts; stick to a max-width centered content area and clear vertical rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background, primary canvas for content, default input fields. |
| 2 | Warm Linen | `#f8f0ec` | Secondary background for sections and product cards, providing slight visual separation. |
| 3 | Ghost White | `#f3e7e2` | Tertiary background for badges or very subtle elevated elements. |
| 4 | Dark Slate | `#202020` | Accent background for specific product showcases or featured cards, creating strong contrast. |

## Imagery

Imagery primarily features product photography and lifestyle shots of people using the products, often with a soft-focus, natural light aesthetic. Product images are typically tightly cropped against minimal or slightly textured backgrounds. Illustrations, when present, are line-art based (like the headphone diagram) with a subtle, muted color palette, serving an explanatory rather than decorative role. Iconography is primarily outlined, maintaining a lightweight feel. Imagery density is moderate, used to break up text and showcase products explicitly, rather than full-bleed decorative elements. The overall impression is authentic and focused on the product's use case.

## Layout

The page uses a contained, centered layout, with much of the content within an implied max-width, while some hero sections break out to full-bleed visuals. The hero section often features large, contextual photography with an overlaid, left-aligned headline and a clear call to action button. Section rhythm is primarily vertical, with consistent spacing between blocks, often alternating between a light Canvas White or Warm Linen background. Content is frequently arranged in text-left/visual-right or visual-left/text-right patterns, creating a dynamic flow. Product listings and feature grids mostly employ 3-column layouts with subtle card styling.

## Agent Prompt Guide

Quick Color Reference:
text: #200e0e
background: #ffffff
border: #d2cfcf
accent: #ed212d
primary action: #200e0e (filled action)

Example Component Prompts:
1. Create a primary hero section: full-bleed image with a dark overlay. Headline 'Block Out The Noise' at 42px Antarctica weight 600, #fde3d6, letter-spacing -0.84px. Below it, an aligned CTA button 'Find Your Calm' with backgroundColor #200e0e, color #fde3d6, borderRadius 3px, padding 12px 16px.
2. Create a product card: backgroundColor #f8f0ec, borderRadius 0px, boxShadow none. Product title 'Alpine PartyPlug Pro' at 18px Antarctica weight 545, #200e0e. Price '€22,95' at 16px Antarctica weight 400, #200e0e. Include a 'Top Seller' badge: backgroundColor #ffffff, color #200e0e, borderRadius 3px, padding 5px 6px.
3. Create an input field: backgroundColor #ffffff, placeholder color rgba(32, 14, 14, 0.5), border 1px solid rgba(32, 14, 14, 0.1), borderRadius 3px, padding 14px 12px. Label 'Email Address' at 14px Antarctica weight 400, #200e0e.

## Similar Brands

- **Calm** — Shares a focus on serene imagery, muted color palettes, and a gentle, inviting typographic approach.
- **Minimalist skincare brands (e.g., Aesop, Fenty Skin)** — Employs clean, product-focused photography, generous white space, and subtle, often monochromatic UI elements to convey sophistication.
- **Dyson** — Features high-quality product photography against simple backgrounds, with a clean, functional UI that subtly emphasizes product design.
- **Headspace** — Uses soft colors, friendly typography, and simplified illustrations to create a calm and approachable digital experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #200e0e;
  --color-crimson-accent: #ed212d;
  --color-pale-peach: #fde3d6;
  --color-sage-green: #9ac9b5;
  --color-rose-blush: #dbb0b3;
  --color-canvas-white: #ffffff;
  --color-ghost-white: #f3e7e2;
  --color-warm-linen: #f8f0ec;
  --color-ash-gray: #d2cfcf;
  --color-pitch-black: #000000;
  --color-dark-slate: #202020;

  /* Typography — Font Families */
  --font-antarctica: 'Antarctica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --text-body-lg: 14px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 27px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.27px;
  --text-display: 42px;
  --leading-display: 1.1;
  --tracking-display: -0.84px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w545: 545;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 15px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2.23px;

  /* Named Radii */
  --radius-default: 2.23px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-linen: #f8f0ec;
  --surface-ghost-white: #f3e7e2;
  --surface-dark-slate: #202020;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #200e0e;
  --color-crimson-accent: #ed212d;
  --color-pale-peach: #fde3d6;
  --color-sage-green: #9ac9b5;
  --color-rose-blush: #dbb0b3;
  --color-canvas-white: #ffffff;
  --color-ghost-white: #f3e7e2;
  --color-warm-linen: #f8f0ec;
  --color-ash-gray: #d2cfcf;
  --color-pitch-black: #000000;
  --color-dark-slate: #202020;

  /* Typography */
  --font-antarctica: 'Antarctica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --text-body-lg: 14px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 27px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.27px;
  --text-display: 42px;
  --leading-display: 1.1;
  --tracking-display: -0.84px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-sm: 2.23px;
}
```
