# bella Kitchen Appliances — Style Reference
> Warm kitchen canvas

**Theme:** light

The bella design system presents a warm, inviting feel through its use of soft, off-white backgrounds and a prominent, vibrant orange accent. Typography is a blend of classic and modern, conveying a comfortable yet sophisticated brand. Product showcases feature rounded cards that bring a friendly, approachable quality, contrasting with the crisp product imagery. The overall impression is clean, approachable, and focused on clear product presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas | `#ebeadf` | `--color-canvas` | Dominant page background for a soft, inviting base layer |
| Snow | `#ffffff` | `--color-snow` | Component backgrounds, button fills, and secondary surface layers |
| Sandstone | `#d5cec0` | `--color-sandstone` | Subtle background for cards and secondary page sections, providing gentle visual separation |
| Tangerine | `#f04923` | `--color-tangerine` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Times — Fallback and decorative usage, often for short, impactful statements or where a classic serif feel is desired. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400, 700
- **Sizes:** 16px, 32px
- **Line height:** 1.00
- **Role:** Fallback and decorative usage, often for short, impactful statements or where a classic serif feel is desired.

### Supreme LL TT — Primary brand typeface for all body text, headings, and interactive elements. Its subtle tracking adds a distinctive, composed feel. · `--font-supreme-ll-tt`
- **Substitute:** Arial
- **Weights:** 400, 700
- **Sizes:** 13px, 14px, 16px, 18px, 22px, 24px, 40px
- **Line height:** 0.89, 1.10, 1.40, 1.50, 1.83
- **Letter spacing:** -0.0500em
- **Role:** Primary brand typeface for all body text, headings, and interactive elements. Its subtle tracking adds a distinctive, composed feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | -0.05px | `--text-caption` |
| heading-sm | 18px | 1.4 | -0.05px | `--text-heading-sm` |
| heading | 22px | 1.1 | -0.05px | `--text-heading` |
| heading-lg | 24px | 1.1 | -0.05px | `--text-heading-lg` |
| display | 40px | 0.89 | -0.05px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 116 | 116px | `--spacing-116` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 999px |
| general | 12px |

### Layout

- **Section gap:** 167px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Text Link
**Role:** Navigational and descriptive links.

Utilizes Ink text color, 0px border-radius, and 0px padding. The hover state implies only text color change or subtle underline.

### Pill Button
**Role:** Primary interaction button for calls to action.

Features a Snow background with Ink text, a border-radius of 999px (full pill shape), and padding of 5px top, 10px right, 10px bottom, 10px left.

### Ghost Button
**Role:** Secondary or alternative actions where visual weight is less important.

Transparent background with Ink text and an Ink border, 0px border-radius, and 0px padding. It integrates seamlessly into surrounding text.

### Product Highlight Card
**Role:** Showcasing featured products or promotions with high visual impact.

Filled with a vivid Tangerine background, corners rounded at 12px. Internal padding is 22px top, 0px horizontal, 24px bottom.

### General Content Card
**Role:** Standard container for product listings and informational blocks.

Uses a soft Sandstone background, with 12px rounded corners. Internal padding is 40px top, 0px horizontal, 48px bottom.

## Do's and Don'ts

### Do
- Use Canvas (#ebeadf) as the base background for most page sections, ensuring a warm and inviting feel.
- Apply Ink (#000000) for all primary text, borders, and iconography to maintain high contrast and legibility.
- Round corners with a 12px radius for all general cards and containers, and 999px for pill-shaped buttons and tags.
- Elevate critical information or calls to action by placing them on Tangerine (#f04923) backgrounds.
- Utilize Supreme LL TT for all typographic elements, leveraging its specific letter-spacing of -0.0500em for a refined appearance.
- Break up content with sections using Sandstone (#d5cec0) to create subtle, visual segmentation without harsh divisions.
- Maintain an element gap of 12px for consistent spacing between interactive elements and content blocks.

### Don't
- Avoid using harsh white backgrounds unless for specific component surfaces, to preserve the warm aesthetic.
- Do not use multiple accent colors; Tangerine (#f04923) should be the singular vibrant accent.
- Do not vary border radii outside of 12px for cards and 999px for buttons, to maintain shape consistency.
- Avoid generic system fonts; always prioritize Supreme LL TT for brand consistency.
- Do not over-emphasize elements with heavy shadows or gradients; the design relies on color and spacing for hierarchy.
- Do not use Tangerine (#f04923) for text or small icons unless against a very light background, due to insufficient contrast against other brand colors.
- Avoid excessive padding or small element gaps, as the system favors comfortable density with an element gap of 12px and card padding of 24px.

## Imagery

The site heavily features product photography, presented as hero assets against vibrant backgrounds or styled within realistic kitchen environments. Products are typically shown cleanly, often against white or neutral backdrops in a studio setting, or as central objects in lifestyle vignettes. Illustrations are minimal, predominantly used for branding or small decorative accents. Icons are monochromatic, using clean outlines. Imagery serves to showcase product functionality and aesthetic appeal.

## Layout

The page structure utilizes a contained layout with a comfortable density. Hero sections are dynamic, often featuring full-bleed vibrant backgrounds with product-focused imagery and overlaid text. Content sections follow a patterned rhythm, alternating between full-width immersive scenes (like the kitchen environment) and structured grid layouts for product display. A consistent vertical spacing strategy is employed using a base unit of 4px. Navigation is handled by a sticky top bar with minimal links. Product grids are typically 4-column, displaying items with associated pricing and 'Bestseller' tags.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ebeadf
border: #000000
accent: #f04923
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary hero section with a blue sky background image. Overlay 'Fits-anywhere™ kitchenware' in Supreme LL TT, 40px, weight 400, #000000. Feature a product rising from the bottom, tied to red balloons, set against this background. On the right, include a Tangerine (#f04923) card with 'BEST-SELLER' in #000000, Supreme LL TT 13px, 999px radius on a Snow (#ffffff) badge, and a centered image of a toaster with 'Shop now' button (Snow background, Ink text, 999px radius, 5px top, 10px right/bottom/left padding) at the bottom.
2. Design a product listing grid: Four columns of product cards against a Canvas (#ebeadf) background. Each card should use the General Content Card style (Sandstone background, 12px radius, 40px top, 0px horizontal, 48px bottom padding). Product names are Supreme LL TT 16px, #000000, and prices are Supreme LL TT 14px, #000000.
3. Create a navigation bar: Snow (#ffffff) background, with 'bella' logo (black text, Supreme LL TT 22px, weight 700) on the left. Navigation links ('Shop', 'bella PRO', 'Recipes', etc.) right-aligned, using #000000 text, Supreme LL TT 16px, 0px padding, no border.

## Similar Brands

- **Our Place** — Soft, muted color palettes mixed with a single vibrant accent, and a focus on aesthetically pleasing kitchenware.
- **Fellow Products** — Clean design with emphasis on product photography against neutral or minimalist backdrops, and a mix of serif/sans-serif typography.
- **Made In Cookware** — Direct product focus, often featuring single accent colors for promotional sections, and a comfortable, approachable content density.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ebeadf;
  --color-snow: #ffffff;
  --color-sandstone: #d5cec0;
  --color-tangerine: #f04923;

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-supreme-ll-tt: 'Supreme LL TT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.05px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.05px;
  --text-heading: 22px;
  --leading-heading: 1.1;
  --tracking-heading: -0.05px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.05px;
  --text-display: 40px;
  --leading-display: 0.89;
  --tracking-display: -0.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-116: 116px;

  /* Layout */
  --section-gap: 167px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 999px;
  --radius-general: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ebeadf;
  --color-snow: #ffffff;
  --color-sandstone: #d5cec0;
  --color-tangerine: #f04923;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-supreme-ll-tt: 'Supreme LL TT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.05px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.05px;
  --text-heading: 22px;
  --leading-heading: 1.1;
  --tracking-heading: -0.05px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.05px;
  --text-display: 40px;
  --leading-display: 0.89;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-116: 116px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 999px;
}
```
