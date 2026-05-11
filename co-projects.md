# Co Projects — Style Reference
> Gallery Wall Typography - Massive typographic elements dominate minimal structure, creating visual weight and focus.

**Theme:** light

This design system presents as austere and deliberate, focusing on bold typography and stark contrasts. It feels like a gallery wall or architectural display, emphasizing content through scale and negative space rather than decorative elements. The interplay between massive, graphic text and minimal UI elements creates a contemplative, almost academic atmosphere, highlighting the conceptual nature of the content. A singular borderline gray provides subtle structural division.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, significant negative space in dominant graphic elements. |
| Coal Black | `#000000` | `--color-coal-black` | Primary text color, bold graphic elements—its high contrast against Canvas White defines the visual identity. |
| Borderline Gray | `#e5e7eb` | `--color-borderline-gray` | Subtle borders and dividers, providing minimal visual separation without asserting independent color. |

## Tokens — Typography

### Alpha — Primary display and general purpose font. The 60px size with a 1.0 lineHeight is key to creating the graphic, tightly-stacked effect seen in headlines. Its custom nature suggests a unique, potentially geometric or experimental character that avoids generic system fonts. · `--font-alpha`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 29px, 60px
- **Line height:** 1.00, 1.10, 1.50
- **Letter spacing:** normal
- **Role:** Primary display and general purpose font. The 60px size with a 1.0 lineHeight is key to creating the graphic, tightly-stacked effect seen in headlines. Its custom nature suggests a unique, potentially geometric or experimental character that avoids generic system fonts.

### Takt — Used for body text, links, and some headings. The consistency in weight at 400 across both custom fonts suggests a deliberate choice against hierarchical weight variations, making font family rather than weight the primary differentiator. · `--font-takt`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 16px, 36px
- **Line height:** 1.10, 1.11
- **Letter spacing:** normal
- **Role:** Used for body text, links, and some headings. The consistency in weight at 400 across both custom fonts suggests a deliberate choice against hierarchical weight variations, making font family rather than weight the primary differentiator.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.1 | — | `--text-body` |
| subheading | 29px | 1.1 | — | `--text-subheading` |
| heading | 36px | 1.11 | — | `--text-heading` |
| display | 60px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 32 | 32px | `--spacing-32` |
| 96 | 96px | `--spacing-96` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 96px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Body Text
**Role:** General content text

Body text using `Takt` font, 16px size, 400 weight, `Coal Black` (#000000) color, and 1.1 lineHeight.

### Bordered Element
**Role:** Implicit container or divider

Any element with a `Borderline Gray` (#e5e7eb) border, likely `border-bottom` for content separation, `border-top` for header separation, or `border-right` for vertical division. Border-radius is always 0px.

## Do's and Don'ts

### Do
- Prioritize `Alpha` font at 60px/1.0 lh for major display text to create graphic impact.
- Use `Coal Black` (#000000) for all text and primary graphic elements.
- Maintain `Canvas White` (#ffffff) as the dominant background color for an expansive, clean feel.
- Apply `Borderline Gray` (#e5e7eb) for subtle structural divisions and borders, never as a primary background.
- Utilize 0px for all border-radius values, reinforcing a stark and precise aesthetic.

### Don't
- Avoid using multiple font weights; stick to 400 for both `Alpha` and `Takt`.
- Do not introduce any additional chromatic colors; maintain the achromatic palette.
- Do not use box-shadows or any form of elevation; depth is created through negative space and color contrast.
- Avoid decorative elements like icons, unless they are purely functional and monochromatic.
- Do not vary line-heights excessively; adhere to specified values (1.0 for large Alpha, 1.1/1.11 for Takt/smaller Alpha) for consistent visual rhythm.

## Imagery

The site uses no explicit photography or complex illustrations. Instead, the 'imagery' is formed by massive, stark, black geometric shapes (the 'co' motif). These abstract graphics are full-bleed and serve as both decorative and branding elements, leveraging extreme scale and high contrast. The visual language is entirely contained within the UI and typographic structures, showcasing a pure, unadorned approach to visual identity.

## Layout

The site features a full-bleed page model, allowing large graphic elements to extend to the viewport edges. The hero section is dominated by oversized, centered graphic typography, creating an immediate, impactful visual statement. Content arrangement appears to be a mix of centered stacks and implied grid structures through repetition and alignment, all within a compact information density. There are distinct vertical divisions indicated by subtle borders or section breaks hinted by the `Borderline Gray`. Navigation is a minimalist top bar.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000
- Background: #ffffff
- Border/Divider: #e5e7eb

### 3-5 Example Component Prompts
- Create a primary navigation link: `Alpha` font, 16px size, 400 weight, #000000 color.
- Create a main display headline: `Alpha` font, 60px size, 400 weight, 1.0 lineHeight, #000000 color.
- Create a body text paragraph: `Takt` font, 16px size, 400 weight, 1.1 lineHeight, #000000 color.
- Create a horizontal Divider: 1px solid #e5e7eb, 0px border-radius, with 8px `margin-bottom`.

## Similar Brands

- **AIGA** — Similar focus on typography as primary visual element, stark black and white palette, and grid-based content organization.
- **Actual Source** — Employs oversized, experimental typography and a minimalist, design-forward aesthetic to showcase creative work.
- **Are.na** — Shares a stripped-down, content-focused approach with a premium on visual clarity, often using a limited color palette and strong typography.
- **Field.io** — Relies on bold, graphic elements and a monochromatic scheme to emphasize art and design, often with large-scale typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-coal-black: #000000;
  --color-borderline-gray: #e5e7eb;

  /* Typography — Font Families */
  --font-alpha: 'Alpha', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-takt: 'Takt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.1;
  --text-subheading: 29px;
  --leading-subheading: 1.1;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-32: 32px;
  --spacing-96: 96px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-coal-black: #000000;
  --color-borderline-gray: #e5e7eb;

  /* Typography */
  --font-alpha: 'Alpha', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-takt: 'Takt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.1;
  --text-subheading: 29px;
  --leading-subheading: 1.1;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-display: 60px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-32: 32px;
  --spacing-96: 96px;
  --spacing-208: 208px;
}
```
