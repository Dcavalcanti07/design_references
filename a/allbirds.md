# Allbirds — Style Reference
> Soft Natural Palette. Like hand-woven textiles and smoothed river stones.

**Theme:** light

Allbirds presents a natural, approachable e-commerce experience. Soft neutrals and muted chromatic colors provide a calming backdrop for product-focused layouts. The combination of a friendly sans-serif with a distinctive serif for headlines creates a balance of modern utility and understated elegance. Key elements like buttons and inputs feature large, almost pill-like border radii, contributing to an overall soft and inviting touch.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Black Ink | `#000000` | `--color-black-ink` | Primary text, brand accents, button text on light backgrounds, borders. |
| White Linen | `#ffffff` | `--color-white-linen` | Page backgrounds, card surfaces, button backgrounds, text on dark backgrounds. |
| Charcoal Slate | `#212121` | `--color-charcoal-slate` | Secondary text, dark button backgrounds, navigation elements, subtle borders. |
| Warm Mist | `#e0dacf` | `--color-warm-mist` | Subtle section backgrounds, atmospheric accents maintaining a light theme. |
| Storm Gray | `#525252` | `--color-storm-gray` | Muted secondary text, outlines, and subtle shadows. |
| Muted Olive | `#222519` | `--color-muted-olive` | Background for specific product sections, offering slight earthy contrast. |
| Desert Clay | `#a57e75` | `--color-desert-clay` | Product background swatches, indicating natural tones. |
| Sky Dust | `#879aab` | `--color-sky-dust` | Product background swatches, introducing a cool, soft hue. |
| Sandstone Tan | `#d1b0a4` | `--color-sandstone-tan` | Product background swatches, a light, earthy neutral. |
| Sunlit Ochre | `#9e8949` | `--color-sunlit-ochre` | Product background swatches, a warm and inviting accent. |

## Tokens — Typography

### Geograph — Primary UI font for body text, navigation, buttons, and general informational display. Its clean geometric shape ensures readability across various sizes, anchoring the user interface. · `--font-geograph`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.00, 1.25, 1.33, 1.40, 1.43, 1.50, 1.67
- **Letter spacing:** -0.05em to 0.05em
- **Role:** Primary UI font for body text, navigation, buttons, and general informational display. Its clean geometric shape ensures readability across various sizes, anchoring the user interface.

### Self Modern — Used for distinctive, editorial-style headlines and display text, particularly 'Bold By Nature'. Its traditional serif form provides a contrast to the sans-serif, adding a touch of sophisticated naturalism. · `--font-self-modern`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 18px, 40px
- **Line height:** 1.00, 1.20, 1.50, 1.78
- **Letter spacing:** normal
- **Role:** Used for distinctive, editorial-style headlines and display text, particularly 'Bold By Nature'. Its traditional serif form provides a contrast to the sans-serif, adding a touch of sophisticated naturalism.

### HurmeGeometricSans3-Regular — Limited use, primarily for specific button text where a slightly more open, geometric feel is desired, reinforcing the modern and clean aesthetic. · `--font-hurmegeometricsans3-regular`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.14
- **Letter spacing:** normal
- **Role:** Limited use, primarily for specific button text where a slightly more open, geometric feel is desired, reinforcing the modern and clean aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.025px | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 20px | 1.4 | — | `--text-heading` |
| heading-lg | 24px | 1.33 | — | `--text-heading-lg` |
| display | 40px | 1.2 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| small | 4px |
| inputs | 1.67772e+07px |
| buttons | 1.67772e+07px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(87, 87, 87) 0px 0px 0px 1px inset, rgb(0, 0, 0) 0px 0...` | `--shadow-subtle` |

### Layout

- **Section gap:** 42-90px
- **Element gap:** 4px

## Components

### Primary Filled Button
**Role:** Call to action.

Background: Charcoal Slate (#212121), Text: White Linen (#ffffff), Radius: 1.67772e+07px (pill shape), Padding: 8px vertical, 16px horizontal. Font: Geograph 400, 14px, lineHeight 1.14.

### Secondary Filled Button
**Role:** Alternative call to action.

Background: White Linen (#ffffff), Text: Black Ink (#000000), Radius: 1.67772e+07px (pill shape), Padding: 8px vertical, 16px horizontal. Font: Geograph 400, 14px, lineHeight 1.14.

### Secondary Outlined Button (Light)
**Role:** Subtle action on light backgrounds.

Background: transparent, Text: Black Ink (#000000), Border: 1px Black Ink (#000000), Radius: 0px, Padding: 0px. Font: Geograph 400.

### Secondary Outlined Button (Dark)
**Role:** Subtle action on dark backgrounds.

Background: transparent, Text: White Linen (#ffffff), Border: 1px White Linen (#ffffff), Radius: 1.67772e+07px (pill shape), Padding: 8px vertical, 16px horizontal. Font: Geograph 400.

### Pill Input Field
**Role:** Form input.

Background: White Linen (#ffffff), Text: Black Ink (#000000), Border: 1px Black Ink (#000000), Radius: 1.67772e+07px (pill shape), Padding: 10px vertical, 12px left, 80px right for internal elements. Font: Geograph 400.

### Product Display Card
**Role:** Showcasing individual products.

Background: White Linen (#ffffff) or Muted Olive (#222519), Radius: 16px, Content padding: 8px. Images often full-bleed to the card edges.

### Header Navigation Link
**Role:** Primary navigation.

Text: Charcoal Slate (#212121) or White Linen (#ffffff), Font: Geograph 400, 14px. Hover state potentially indicated by underline or color shift.

### Utility Chip
**Role:** Informational tag like 'NEW ARRIVALS'.

Background: White Linen (#ffffff), Text: Black Ink (#000000), Radius: 4px, Padding: 4px vertical, 8px horizontal, Border: 1px Charcoal Slate (#212121).

## Do's and Don'ts

### Do
- Prioritize Geograph for all body text, navigation, and button labels at its specified weights and sizes to maintain UI consistency.
- Use Self Modern 400 for all marketing headlines and display text to express brand elegance.
- Apply 1.67772e+07px radius to all interactive buttons and inputs for a soft, approachable feel, effectively making them pill-shaped.
- Utilize the color progression from White Linen (#ffffff) background to Charcoal Slate (#212121) buttons for clear contrast and hierarchy.
- Maintain a clear product focus by centering product imagery on clean backgrounds (White Linen, Muted Olive, or other Brand swatch colors).

### Don't
- Avoid using box-shadows extensively; elevation is primarily achieved through background color shifts and subtle borders.
- Do not introduce sharp corners on primary interactive elements like buttons or input fields, as the pill-like radius is a signature brand element.
- Refrain from highly saturated or vibrant accent colors; the brand palette relies on muted, earthy tones and achromatic neutrals.
- Do not deviate from the established font families; Geograph and Self Modern provide a distinct dual-personality to the typography.
- Avoid using thin line-heights on body text; ensure readability with line-heights of 1.4 to 1.5 for optimal comfort.

## Imagery

This site features product-focused photography and lifestyle shots. Product imagery consists of tight crops of footwear on clean, solid-colored backgrounds (often White Linen or muted brand swatches) presented as isolated objects. Lifestyle photography captures models in natural settings (e.g., outdoors, against natural textures), often from a distance, with a focus on conveying a sense of ease and connection to nature. Images are typically full-bleed within sections or contained within cards with rounded corners (16px radius). The overall treatment is natural, not overly contrasty or filtered, emphasizing the authentic appearance of the products and environments. Icons, such as shopping cart and search, are simple, monochromatic fills matching the text color.

## Layout

The page primarily uses a max-width contained layout, though some hero sections extend full-bleed. The hero pattern varies: some feature large full-width product arrangements with text overlay, while others adopt a split layout with a lifestyle image on one side and a headline/CTA on the other. Sections generally feature consistent vertical spacing (sectionGap 42-90px) and often employ 2-column or multi-column grids for presenting products or content blocks. Product listings are presented in responsive card grids. The content flow is primarily linear, with distinct sections visually separated by background color changes or clear vertical spacing. Navigation is a prominent top bar, typically fixed, with a clean, centered logo and right-aligned utility icons.

## Agent Prompt Guide

### Quick Color Reference
- Text: Black Ink (#000000)
- Background: White Linen (#ffffff)
- CTA Background: Charcoal Slate (#212121)
- CTA Text: White Linen (#ffffff)
- Border: Black Ink (#000000)
- Accent: Sunlit Ochre (#9e8949)

### Example Component Prompts
1. Create a primary call-to-action button: background Charcoal Slate (#212121), text White Linen (#ffffff), border-radius 1.67772e+07px, padding 8px 16px, font Geograph 400 14px.
2. Design a product card: background White Linen (#ffffff), border-radius 16px, inner element padding 8px. Include a product image and a 'NEW ARRIVALS' chip (background White Linen, text Black Ink, border 1px Charcoal Slate, radius 4px, padding 4px 8px).
3. Generate a hero section headline: 'Bold By Nature' using Self Modern 400 40px, text Black Ink (#000000), line-height 1.2.
4. Produce an input field: background White Linen (#ffffff), text Black Ink (#000000), border 1px Black Ink (#000000), border-radius 1.67772e+07px, padding 10px 80px 10px 12px. Placeholder text in Storm Gray (#525252).

## Similar Brands

- **Everlane** — Shares a clean, modern aesthetic with a focus on product photography and natural material emphasis.
- **Patagonia** — Uses natural, earthy color palettes and a strong connection to outdoor, lifestyle imagery.
- **Uniqlo** — Has a strong emphasis on simple, functional UI and clear product display with a clean, light default theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-black-ink: #000000;
  --color-white-linen: #ffffff;
  --color-charcoal-slate: #212121;
  --color-warm-mist: #e0dacf;
  --color-storm-gray: #525252;
  --color-muted-olive: #222519;
  --color-desert-clay: #a57e75;
  --color-sky-dust: #879aab;
  --color-sandstone-tan: #d1b0a4;
  --color-sunlit-ochre: #9e8949;

  /* Typography — Font Families */
  --font-geograph: 'Geograph', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-self-modern: 'Self Modern', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hurmegeometricsans3-regular: 'HurmeGeometricSans3-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.025px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 20px;
  --leading-heading: 1.4;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.33;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 42-90px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-small: 4px;
  --radius-inputs: 1.67772e+07px;
  --radius-buttons: 1.67772e+07px;

  /* Shadows */
  --shadow-subtle: rgb(87, 87, 87) 0px 0px 0px 1px inset, rgb(0, 0, 0) 0px 0px 0px 1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-black-ink: #000000;
  --color-white-linen: #ffffff;
  --color-charcoal-slate: #212121;
  --color-warm-mist: #e0dacf;
  --color-storm-gray: #525252;
  --color-muted-olive: #222519;
  --color-desert-clay: #a57e75;
  --color-sky-dust: #879aab;
  --color-sandstone-tan: #d1b0a4;
  --color-sunlit-ochre: #9e8949;

  /* Typography */
  --font-geograph: 'Geograph', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-self-modern: 'Self Modern', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hurmegeometricsans3-regular: 'HurmeGeometricSans3-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.025px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 20px;
  --leading-heading: 1.4;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.33;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-subtle: rgb(87, 87, 87) 0px 0px 0px 1px inset, rgb(0, 0, 0) 0px 0px 0px 1px;
}
```
