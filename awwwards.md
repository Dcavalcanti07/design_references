# Awwwards — Style Reference
> Monochrome Grid Blueprint

**Theme:** light

This design system feels like a hyper-organized digital archive, presenting information with stark contrast and deliberate typography. A heavy reliance on achromatic tones (#222222, #e9e9e9, #ffffff) creates a crisp, no-nonsense canvas. The custom Inter Tight typeface with its wide range of weights and tight line heights defines a distinctive, modern editorial voice. Small, deliberate rounded corners and minimal visual decoration ensure focus remains squarely on core content, like a precise technical schematic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#222222` | `--color-midnight-graphite` | Primary text, headings, prominent icons, button text on light backgrounds. Establishes a bold and clear visual hierarchy against the light neutrals. |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, card backgrounds, button text on dark backgrounds. Provides expansive clean canvases and high contrast. |
| Pale Ash | `#e9e9e9` | `--color-pale-ash` | Secondary backgrounds for soft elevation and subtle button states. Creates faint visual differentiation without strong color shifts. |
| Deep Pewter | `#808080` | `--color-deep-pewter` | Table borders and dividers. A darker neutral for structural elements. |
| Silver Mist | `#dedede` | `--color-silver-mist` | Subtle borders, inactive elements, supporting icon fills. Provides a light touch of separation and detail. |
| Sunset Orange | `#fa5d29` | `--color-sunset-orange` | Link highlights, occasional accent text. A vivid, warm pop against the dominant neutrals for interactive elements or rare emphasis. |
| Lemon Zest | `#fff083` | `--color-lemon-zest` | Highlighting badges, occasional alert backgrounds. A secondary vivid accent for less critical attention. |

## Tokens — Typography

### Inter Tight — The sole typeface for all content. Its narrow metrics and precise line heights from 0.93 to 3.00 create a distinctive, information-dense, modern aesthetic across all scales, from micro-text to impactful display headlines where 127px at 0.93 line height creates a commanding visual block. · `--font-inter-tight`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 19px, 21px, 22px, 24px, 32px, 42px, 127px
- **Line height:** 0.93, 1.00, 1.10, 1.17, 1.20, 1.27, 1.29, 1.36, 1.44, 1.45, 1.50, 1.70, 1.75, 1.87, 2.00, 2.15, 2.40, 3.00
- **Letter spacing:** normal
- **Role:** The sole typeface for all content. Its narrow metrics and precise line heights from 0.93 to 3.00 create a distinctive, information-dense, modern aesthetic across all scales, from micro-text to impactful display headlines where 127px at 0.93 line height creates a commanding visual block.

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| small | 4px |
| default | 8px |
| cardInteractive | 14px |

### Layout

- **Section gap:** 40px
- **Card padding:** 8px
- **Element gap:** 4px

## Components

### Primary Ghost Button
**Role:** Navigation, secondary actions

Text-only button with Midnight Graphite (#222222) text. No background, no padding, no border, and 0px border-radius. Relies on text color and hover states for interaction.

### Solid Dark Button
**Role:** Call-to-action, primary action

Solid Midnight Graphite (#222222) background with Arctic White (#ffffff) text. 8px border-radius and horizontal padding of 20px. Vertical padding is managed by line-height.

### Secondary Solid Button
**Role:** Affirmative actions, less prominent CTAs

Solid Pale Ash (#e9e9e9) background with Midnight Graphite (#222222) text. 8px border-radius and horizontal padding of 15.6px. Vertical padding is managed by line-height.

### Interactive Card with Round Corners
**Role:** Clickable content blocks, featured items

Arctic White (#ffffff) background with 14px border-radius. No box shadow or padding on the card itself; content provides internal spacing. Used for visually distinct interactive blocks.

### Standard Content Card
**Role:** Informational blocks, list items

Transparent background with 0px border-radius. No box shadow or padding. Acts as a container for related information using only internal content spacing.

### Search Input Field
**Role:** Site search, form entries

Transparent background, Midnight Graphite (#222222) text. Left padding of 38px, no explicit border-radius (0px). Underlined by inferred style from input fields.

### Badge with Background
**Role:** Categorization, short labels

Transparent background with Arctic White (#ffffff) text and 8px border-radius. Padding is 0, visual context provides spacing.

### Padded Detail Badge
**Role:** Specific score or data labels

Transparent background with Midnight Graphite (#222222) text. 4px border-radius. Padded with 2px top, 1px bottom, and 8px left/right. Provides a contained, minimal label.

## Do's and Don'ts

### Do
- Always use Inter Tight across all text elements, maintaining consistent font identity.
- Prioritize Midnight Graphite (#222222) for all primary text and Arctic White (#ffffff) for backgrounds to ensure AAA contrast.
- Apply 8px border-radius for interactive elements like buttons and general cards, for a consistent soft-edge feel.
- Utilize Pale Ash (#e9e9e9) for subtle background differentiation, such as secondary button states or layered content blocks.
- Ensure horizontal element spacing for text-based components is a multiple of 4px, seen in 6px and 8px common values.
- Reserve Sunset Orange (#fa5d29) for key interactive elements or critical alerts, leveraging its vividness sparingly.

### Don't
- Avoid introducing additional typefaces; Inter Tight is the singular typographic voice.
- Do not use strong drop shadows; the system relies on background color shifts and borders for depth.
- Do not vary from the established border radii for interactive elements; 8px and 4px radii are key to the visual language.
- Avoid excessive color; maintain the dominant achromatic palette, using accent colors only for designated functional purposes.
- Do not use generic padding values; adhere to the 4px base unit or derived token values for consistent density.
- Avoid design elements that introduce significant visual clutter; simplicity and directness are paramount.

## Imagery

The site's imagery strategy is a mix of high-quality lifestyle photography and occasional abstract graphics. Photography featuring people often has a muted, desaturated color palette, focusing on natural light and an unposed, candid feel. Products, when present, appear within these lifestyle contexts rather than isolated. The images are typically full-bleed or large masked areas, often serving as background elements behind overlaid text. They are raw-edged, without explicit rounded corners, contrasting with the rounded UI elements. Text overlays are common, creating a magazine-like editorial presentation where visuals provide atmospheric context rather than direct product showcase.

## Layout

The layout primarily follows a max-width contained model for navigational elements and most content, but the hero section often utilizes full-bleed imagery. The overall structure is centered. The hero pattern is a large visual with overlaid text, capturing immediate attention. Section rhythm is generally consistent with substantial vertical spacing (approximately 40px, inferred from section gaps), creating a breathable, spacious feel. Content arrangement frequently uses large, single columns for prominent headlines and text, transitioning to more traditional article-like layouts further down the page. The information density is 'comfortable', balancing white space with impactful content blocks. Navigation is a prominent sticky top bar with clearly defined interactive elements.

## Agent Prompt Guide

### Quick Color Reference
- Text: #222222 (Midnight Graphite)
- Background: #ffffff (Arctic White)
- CTA Background: #222222 (Midnight Graphite)
- CTA Text: #ffffff (Arctic White)
- Accent: #fa5d29 (Sunset Orange)
- Subtle Background: #e9e9e9 (Pale Ash)

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: Solid Midnight Graphite background, Arctic White text (Inter Tight weight 400, 16px, 1.25 line-height), 8px border-radius, 20px horizontal padding.
2. Design a navigation link: Midnight Graphite text (Inter Tight weight 400, 15px, 1.2 line-height), no background, no padding, 0px border-radius.
3. Implement a detail badge: Transparent background, Midnight Graphite text (Inter Tight weight 400, 10px, 1.4 line-height), 4px border-radius, 8px horizontal padding, 2px top padding, 1px bottom padding.
4. Build an interactive card: Arctic White background, 14px border-radius, no shadow, no internal padding on the card itself. Content inside will define spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #222222;
  --color-arctic-white: #ffffff;
  --color-pale-ash: #e9e9e9;
  --color-deep-pewter: #808080;
  --color-silver-mist: #dedede;
  --color-sunset-orange: #fa5d29;
  --color-lemon-zest: #fff083;

  /* Typography — Font Families */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.7;
  --text-xs-2: 11px;
  --leading-xs-2: 1;
  --text-xs-3: 12px;
  --leading-xs-3: 2.4;
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-sm-2: 14px;
  --leading-sm-2: 2;
  --text-base: 15px;
  --leading-base: 1.87;
  --text-base-2: 16px;
  --leading-base-2: 1.75;
  --text-lg: 18px;
  --leading-lg: 0.93;
  --text-lg-2: 19px;
  --leading-lg-2: 1.45;
  --text-xl: 21px;
  --leading-xl: 1.36;
  --text-xl-2: 22px;
  --leading-xl-2: 1.27;
  --text-2xl: 24px;
  --leading-2xl: 1.17;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 8px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-small: 4px;
  --radius-default: 8px;
  --radius-cardinteractive: 14px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #222222;
  --color-arctic-white: #ffffff;
  --color-pale-ash: #e9e9e9;
  --color-deep-pewter: #808080;
  --color-silver-mist: #dedede;
  --color-sunset-orange: #fa5d29;
  --color-lemon-zest: #fff083;

  /* Typography */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.7;
  --text-xs-2: 11px;
  --leading-xs-2: 1;
  --text-xs-3: 12px;
  --leading-xs-3: 2.4;
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-sm-2: 14px;
  --leading-sm-2: 2;
  --text-base: 15px;
  --leading-base: 1.87;
  --text-base-2: 16px;
  --leading-base-2: 1.75;
  --text-lg: 18px;
  --leading-lg: 0.93;
  --text-lg-2: 19px;
  --leading-lg-2: 1.45;
  --text-xl: 21px;
  --leading-xl: 1.36;
  --text-xl-2: 22px;
  --leading-xl-2: 1.27;
  --text-2xl: 24px;
  --leading-2xl: 1.17;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;
}
```
