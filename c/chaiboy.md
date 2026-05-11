# CHAIBOY — Style Reference
> Monochromatic minimalist canvas.

**Theme:** dark

CHAIBOY presents a stark, high-contrast dark mode aesthetic, emphasizing minimalism and bold, clean typography. The visual language centers on a monochromatic palette of black, white, and various grays, creating a sophisticated and understated environment. Thin line accents found in borders and ghost buttons provide delicate structure against dark surfaces. The overall impression is one of controlled elegance, using visual sparseness to draw attention to refined products and content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page backgrounds, prominent surface fills, footer background — creates a deep, infinite canvas |
| Frost Gray | `#afafaf` | `--color-frost-gray` | Muted text, inactive element borders, placeholder text within inputs. Provides visual separation without harsh contrast |
| Arctic White | `#ffffff` | `--color-arctic-white` | Primary text, active element borders, button backgrounds for ghost buttons, primary input text — stands out vibrantly against the dark background |

## Tokens — Typography

### NeueHaasGroteskTP55R — NeueHaasGroteskTP55R — detected in extracted data but not described by AI · `--font-neuehaasgrotesktp55r`
- **Weights:** 400
- **Sizes:** 11px, 14px, 18px, 54px
- **Line height:** 0.89, 1.11, 1.27, 1.29
- **OpenType features:** `"case"`
- **Role:** NeueHaasGroteskTP55R — detected in extracted data but not described by AI

### Neue Haas Grotesk Text — The singular typeface for all content, from navigation to headlines. Its precise, neutral geometry supports the minimalist aesthetic, with 'case' font features ensuring consistent uppercase styling for certain elements, maintaining a crisp, editorial feel. · `--font-neue-haas-grotesk-text`
- **Substitute:** Helvetica Neue
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **OpenType features:** `"case"`
- **Role:** The singular typeface for all content, from navigation to headlines. Its precise, neutral geometry supports the minimalist aesthetic, with 'case' font features ensuring consistent uppercase styling for certain elements, maintaining a crisp, editorial feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.29 | — | `--text-caption` |
| body | 14px | 1.11 | — | `--text-body` |
| heading-lg | 18px | 1.27 | — | `--text-heading-lg` |
| display | 54px | 0.89 | — | `--text-display` |

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
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 42 | 42px | `--spacing-42` |
| 51 | 51px | `--spacing-51` |
| 60 | 60px | `--spacing-60` |
| 78 | 78px | `--spacing-78` |
| 90 | 90px | `--spacing-90` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| links | 4px |
| buttons | 4px |
| overall | 4px |

### Layout

- **Section gap:** 60px
- **Card padding:** 16px
- **Element gap:** 5px

## Components

### Ghost Border Button - Frost
**Role:** Secondary action button

Text is Frost Gray (#afafaf) on a transparent background, with a 1px Frost Gray border (#afafaf), 4px border-radius, and padding of 10px top, 16px right, 7px bottom, 16px left. Used for subtle calls to action.

### Underlined Input - Frost
**Role:** Standard text input field

Transparent background with Frost Gray text (#afafaf) and a 1px bottom border in Frost Gray (#afafaf). No border-radius. Padding is 6px top, 0px right, 6px bottom, 0px left.

### Underlined Input - Arctic
**Role:** Prominent text input field

Transparent background with Arctic White text (#ffffff) and a 1px bottom border in Arctic White (#ffffff). No border-radius. Padding is 7px top, 0px right, 5px bottom, 0px left.

### Header Navigation Link
**Role:** Primary navigation item

Arctic White text (#ffffff) at 14px, NeueHaasGroteskTP55R weight 400. Hover state likely introduces a subtle border or color change (not specified).

### Footer Action Link - Muted
**Role:** Footer utility links

Frost Gray text (#afafaf) at 11px, NeueHaasGroteskTP55R weight 400. Used for terms, privacy, and contact information.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) as the primary background color for all main sections and footers.
- Apply NeueHaasGroteskTP55R weight 400 across all typographic elements, prioritizing its unique 'case' font feature for uppercase styling.
- Emphasize content through high-contrast typography, pairing Arctic White (#ffffff) text on Midnight Ink (#000000) backgrounds.
- Implement Frost Gray (#afafaf) for all secondary text, inactive states, and subtle UI lines, ensuring a visual hierarchy without color.
- Maintain a uniform border-radius of 4px for all interactive elements like buttons and cards, contributing to a consistent, subtle softness.
- Structure information using a compact spacing philosophy, with an elementGap of 5px and sectionGap of 60px.
- Utilize 1px borders in Frost Gray (#afafaf) or Arctic White (#ffffff) for inputs and ghost buttons to define interactive areas subtly.

### Don't
- Avoid using any saturated colors unless specifically introduced as a functional accent; the system is strictly monochromatic.
- Do not deviate from the NeueHaasGroteskTP55R font family or weight 400; font consistency is a core brand identifier.
- Refrain from heavy shadows or pronounced elevation; the design relies on flat surfaces and thin borders for depth.
- Do not introduce strong visual gradients; the aesthetic is built on solid color blocks and clear contrasts.
- Avoid large, image-dominant layouts unless the imagery itself is monochromatic and stark, maintaining visual continuity.
- Do not break the 4px border-radius standard; it is a critical micro-design element across interactive components.
- Do not use generic system fonts or default link styling; always apply brand-specific typography and color.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Base Canvas | `#000000` | Dominant background for pages and sections, creating a deep, dark foundation. |
| 2 | Subtle Surface | `#131313` | Slightly lighter dark surface, offering minimal differentiation for secondary content areas or hover states. |
| 3 | Interactive Layer | `#afafaf` | Used for interactive elements like input borders, ghost buttons, and subtle separators, providing a muted interactive layer. |
| 4 | Emphasis Layer | `#ffffff` | Reserved for primary text, active states, and crisp borders, providing high contrast and visual emphasis. |

## Imagery

Imagery is high-contrast, black and white photography, often featuring product or model shots with a stark, artistic feel. Images are primarily contained within content areas, without overlapping elements, and contribute to the overall minimalist and sophisticated mood. Icons are minimal, likely outlined, and monochromatic, integrated seamlessly into the high-contrast UI.

## Layout

The page uses a full-bleed, dark background that extends edge-to-edge. Content appears to be horizontally centered within a maximal width, creating clear boundaries for readability within the expansive dark canvas. The hero section is characterized by a prominent visual element (a large black and white photograph) flanked by the stark black background. Navigation is minimal and positioned at the top, a simple, horizontal list of text links. Sections maintain consistent vertical spacing, creating a calm, unhurried rhythm.

## Agent Prompt Guide

primary action: no distinct CTA color
- Create a secondary action button with a transparent background: Frost Gray (#afafaf) text (NeueHaasGroteskTP55R, 14px, weight 400), 1px Frost Gray (#afafaf) border, 4px border-radius, and 10px paddingTop, 16px paddingRight, 7px paddingBottom, 16px paddingLeft. Text reads 'ORDER NOW'.

## Similar Brands

- **Aēsop** — Shares a monochromatic color palette, emphasis on sophisticated typography, and a minimalist, often dark aesthetic.
- **COS** — Exhibits similar stark, clean photography, a focus on high-quality product presentation, and a restrained UI with minimal color accents.
- **Bang & Olufsen** — Employs an elegant dark theme, premium product imagery, and a refined typographic approach with sparse, deliberate use of UI elements.
- **The Ordinary** — Features a strong emphasis on minimalist packaging and product presentation, using very little color in its digital interface, similar to CHAIBOY's starkness.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-frost-gray: #afafaf;
  --color-arctic-white: #ffffff;

  /* Typography — Font Families */
  --font-neuehaasgrotesktp55r: 'NeueHaasGroteskTP55R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.29;
  --text-body: 14px;
  --leading-body: 1.11;
  --text-heading-lg: 18px;
  --leading-heading-lg: 1.27;
  --text-display: 54px;
  --leading-display: 0.89;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-42: 42px;
  --spacing-51: 51px;
  --spacing-60: 60px;
  --spacing-78: 78px;
  --spacing-90: 90px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 16px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-links: 4px;
  --radius-buttons: 4px;
  --radius-overall: 4px;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-subtle-surface: #131313;
  --surface-interactive-layer: #afafaf;
  --surface-emphasis-layer: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-frost-gray: #afafaf;
  --color-arctic-white: #ffffff;

  /* Typography */
  --font-neuehaasgrotesktp55r: 'NeueHaasGroteskTP55R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.29;
  --text-body: 14px;
  --leading-body: 1.11;
  --text-heading-lg: 18px;
  --leading-heading-lg: 1.27;
  --text-display: 54px;
  --leading-display: 0.89;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-42: 42px;
  --spacing-51: 51px;
  --spacing-60: 60px;
  --spacing-78: 78px;
  --spacing-90: 90px;

  /* Border Radius */
  --radius-md: 4px;
}
```
