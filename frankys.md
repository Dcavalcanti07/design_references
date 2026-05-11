# FRANKY'S — Style Reference
> Retro Pixelated Arcade

**Theme:** dark

Franky's employs an 8-bit arcade aesthetic, reminiscent of retro computing interfaces and early video games. The UI features a dominant dark mode with soft, paper-like neutral surfaces and vibrant, purposeful chromatic accents. A distinct pixelated font defines all typography, reinforcing a digital-native, nostalgic feel. Elements are framed with thin, sometimes dashed borders, and rounded corners provide a subtle organic counterpoint to the pixel grid.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Screen | `#000000` | `--color-midnight-screen` | Primary screen background, dominant text color, strong borders — controls the overall dark theme contrast |
| Paper Canvas | `#f3e5df` | `--color-paper-canvas` | Card backgrounds, secondary surface fills, inner button shadows — creates the aged paper-like texture against the dark background |
| Off-White Border | `#e5e7eb` | `--color-off-white-border` | Primary UI borders, ghost button borders, dividers — a subtle, slightly cool neutral that defines component edges |
| Subtle Charcoal | `#333333` | `--color-subtle-charcoal` | Background for secondary panels or elements, subtle fills — provides layered depth within the dark mode |
| Ghostly Gray | `#737373` | `--color-ghostly-gray` | Muted text, disabled states, secondary button text — for lower hierarchy information |
| Marigold Gold | `#faa21f` | `--color-marigold-gold` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. |
| Action Green | `#128e44` | `--color-action-green` | Primary call-to-action buttons, active elements — a direct and clear indicator of interactable elements |
| Midnight Gradient Blue | `linear-gradient(to left bottom, rgba(43, 72, 147, 0.3), rgba(207, 67, 8, 0.3))` | `--color-midnight-gradient-blue` | Decorative gradient element — provides a deep, moody blue within a larger gradient |
| Sunset Gradient Orange | `linear-gradient(to left bottom, rgba(43, 72, 147, 0.3), rgba(207, 67, 8, 0.3))` | `--color-sunset-gradient-orange` | Decorative gradient element — a warm, vibrant orange complementing the deep blue in a gradient |

## Tokens — Typography

### Arcade — The sole typeface, 'Arcade', dictates the retro, pixelated aesthetic of the entire interface. Its limited weights and specific sizing evoke a classic video game display. · `--font-arcade`
- **Substitute:** Press Start 2P, IBM Plex Mono
- **Weights:** 400, 700
- **Sizes:** 10px, 14px, 16px, 18px
- **Line height:** 1.25, 1.43, 1.50, 1.56
- **Letter spacing:** normal
- **Role:** The sole typeface, 'Arcade', dictates the retro, pixelated aesthetic of the entire interface. Its limited weights and specific sizing evoke a classic video game display.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.56 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| heading | 18px | 1.25 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 44 | 44px | `--spacing-44` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 12px |
| buttons | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(243, 229, 223) 0px 1px 0px 0px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 44px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Ghost Button Thin Border
**Role:** Secondary action control

Transparent background, Midnight Screen text, 4px padding, 0px border-radius, with a 1px solid Midnight Screen border. Used for 'Win Store Coupons' and '3D/AR' toggles.

### Ghost Button Subtle Border
**Role:** Tertiary action control

Transparent background, Midnight Screen text, 6px vertical padding, 4px horizontal padding, 0px border-radius, with a 1px solid Off-White Border. Used for actions like 'Try in AR'.

### Ghost Button Rounded Subtle Border
**Role:** Tertiary action control with soft corners

Transparent background, Midnight Screen text, 8px padding, 6px border-radius, with a 1px solid Off-White Border. Used for smaller, less prominent actions.

### Pill Button Left Rounded
**Role:** Segmented control left segment

Midnight Screen background with Paper Canvas text, 4px vertical padding and 8-12px horizontal padding. Features a 9999px border-radius on the left side, squared on the right, and an inset shadow of rgb(243, 229, 223) 0px 1px 0px 0px.

### Primary Action Button
**Role:** Main call to action

Action Green background with Midnight Screen text, 4px horizontal padding and a small inner shadow of rgb(243, 229, 223) 0px 1px 0px 0px. Used for 'Add to Cart'.

### Product Card
**Role:** Display individual products and details

Paper Canvas background, 12px padding, and 12px border-radius. Contains product image, name, price, and actions like 'Add to cart'.

### Status Indicator Button
**Role:** Informative button, non-interactive (e.g. 'Out of Stock')

Transparent background, Ghostly Gray text, with a 1px solid Off-White Border. Used to indicate product availability.

## Do's and Don'ts

### Do
- Retain the dominant dark theme foregrounded by Paper Canvas (#f3e5df) elements and Midnight Screen (#000000) text for content.
- Utilize the Arcade font exclusively for all text elements to maintain the pixelated retro aesthetic.
- Frame all interactive and content containers with a 1px solid Off-White Border (#e5e7eb) to define UI boundaries.
- Apply a 12px border-radius to all card-like components and a 6px border-radius to smaller interactive elements like buttons.
- Employ Action Green (#128e44) solely for primary call-to-action buttons like 'Add to Cart'.
- Use Marigold Gold (#faa21f) as a vibrant, distinct accent for top-level promotions or specific highlight features.
- Maintain a compact density for elements, primarily using 4px and 12px for padding and gaps, reserving larger values for section separation.

### Don't
- Avoid using bright white backgrounds; always use Paper Canvas (#f3e5df) for lighter surfaces to maintain the aged paper aesthetic.
- Do not introduce any additional font families or weights beyond the defined Arcade font to preserve the distinctive typography.
- Refrain from using strong, modern drop shadows; prioritize the subtle inset button shadow rgb(243, 229, 223) 0px 1px 0px 0px or flat designs.
- Do not deviate from the specified border-radius values (12px for cards, 6px for buttons) as they contribute to the system's character.
- Never use Action Green (#128e44) for decorative purposes or secondary text; it is strictly reserved for primary actions.
- Avoid introducing new primary accent colors; limit the palette to the defined Marigold Gold (#faa21f) and Action Green (#128e44).
- Do not add gradients arbitrarily; use them sparingly and only with the defined color combinations and directions where appropriate for decorative elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Screen Background | `#000000` | The primary background for the entire application, simulating a dark digital screen. |
| 1 | Base Surface | `#333333` | Used for slightly elevated panels or dividers, providing a subtle layer above the main background. |
| 2 | Paper Canvas Card | `#f3e5df` | The main background for content cards and prominent UI elements, creating a visually distinct, aged-paper effect. |

## Imagery

The site uses product photography paired with stylized graphics. Product images are flat, illustrative representations of hats. The main product display section features a large, dynamic 3D render of a hat against a checkerboard pattern. Icons are minimal, outlined, and monochromatic, matching the pixelated aesthetic. Imagery serves primarily as product showcase and decorative atmosphere, contributing to the retro digital theme.

## Layout

The page uses a contained, centered layout, appearing within a distinct browser-like frame. The hero section features a full-width interactive product view (3D/AR) alongside a dynamic checkerboard background. Below this, content is arranged in a fluid grid of product cards, breaking into a two-column layout on larger screens. Navigation is a minimalist top bar within the browser-like frame, with subtle text links for secondary actions. The layout maintains consistent vertical spacing between sections, creating a compact but clear presentation.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #000000
border: #e5e7eb
accent: #faa21f
primary action: #128e44 (filled action)

**3-5 Example Component Prompts**
1. Create a `Ghost Button Subtle Border` with the text 'TRY IN AR'. Use font 'Arcade', size 14px, weight 400, color #000000. Apply 6px vertical padding, 4px horizontal padding, 0px border-radius, and a 1px solid #e5e7eb border.
2. Create a Primary Action Button: #128e44 background, #f3e5df text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Implement a `Status Indicator Button` reading 'OUT OF STOCK'. Use transparent background, `Arcade` font, size 14px, weight 400, Ghostly Gray (#737373) text, with a 1px solid Off-White Border (#e5e7eb).

## Similar Brands

- **Teenage Engineering** — Shares a raw, functional, and slightly retro UI aesthetic with prominent use of monospace fonts and defined component framing.
- **Panic, Inc.** — Exhibits a playful, distinctive brand language through custom typography and a strong sense of personality in their digital interfaces.
- **Playdate** — Features a monochromatic screen with pixelated graphics and a unique brand typeface, evoking a nostalgic, digital-first experience.
- **AIGA Design Archives (older versions)** — Employs a bold, utilitarian typographic style with strong grid usage, creating a structured and almost 'programmatic' visual. 

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-screen: #000000;
  --color-paper-canvas: #f3e5df;
  --color-off-white-border: #e5e7eb;
  --color-subtle-charcoal: #333333;
  --color-ghostly-gray: #737373;
  --color-marigold-gold: #faa21f;
  --color-action-green: #128e44;
  --color-midnight-gradient-blue: #2b4893;
  --gradient-midnight-gradient-blue: linear-gradient(to left bottom, rgba(43, 72, 147, 0.3), rgba(207, 67, 8, 0.3));
  --color-sunset-gradient-orange: #cf4308;
  --gradient-sunset-gradient-orange: linear-gradient(to left bottom, rgba(43, 72, 147, 0.3), rgba(207, 67, 8, 0.3));

  /* Typography — Font Families */
  --font-arcade: 'Arcade', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.56;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-heading: 18px;
  --leading-heading: 1.25;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-44: 44px;

  /* Layout */
  --section-gap: 44px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 12px;
  --radius-buttons: 6px;

  /* Shadows */
  --shadow-subtle: rgb(243, 229, 223) 0px 1px 0px 0px inset;

  /* Surfaces */
  --surface-screen-background: #000000;
  --surface-base-surface: #333333;
  --surface-paper-canvas-card: #f3e5df;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-screen: #000000;
  --color-paper-canvas: #f3e5df;
  --color-off-white-border: #e5e7eb;
  --color-subtle-charcoal: #333333;
  --color-ghostly-gray: #737373;
  --color-marigold-gold: #faa21f;
  --color-action-green: #128e44;
  --color-midnight-gradient-blue: #2b4893;
  --color-sunset-gradient-orange: #cf4308;

  /* Typography */
  --font-arcade: 'Arcade', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.56;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-heading: 18px;
  --leading-heading: 1.25;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-44: 44px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(243, 229, 223) 0px 1px 0px 0px inset;
}
```
