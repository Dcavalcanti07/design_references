# Sneak in Peace — Style Reference
> Overlaid fashion showcase

**Theme:** light

Sneak in Peace presents a digital fashion platform characterized by a clean, contained UI overlaid on a dynamic background. Its aesthetic balances high-contrast text on bright surfaces with muted interactive elements and a singular vivid red accent for active states. Typography is compact and precise, maintaining a high information density while card-based layouts organize content with subtle elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#3d3d3d` | `--color-midnight-graphite` | Primary text, icon default, border lines on neutral elements |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page background, card surfaces, form inputs |
| Deep Space | `#000000` | `--color-deep-space` | Strongest text contrast, prominent icon and badge borders, background for overlaid elements |
| Concrete Gray | `#8d8d8d` | `--color-concrete-gray` | Muted background for interactive links/cards, secondary text |
| Pale Ash | `#f0eeed` | `--color-pale-ash` | Subtle background for badges and secondary surfaces |
| Wolf Gray | `#9e9e9e` | `--color-wolf-gray` | Peripheral text for copyright, subtle body text |
| Silver Mist | `#b5b5b5` | `--color-silver-mist` | Background for inactive buttons or secondary interactive states |
| Digital Violet | `#142161` | `--color-digital-violet` | Border color for interactive elements and links, decorative accents |
| Action Crimson | `#ba2223` | `--color-action-crimson` | Red action color for filled buttons, selected navigation states, and focused conversion moments. |

## Tokens — Typography

### NTNeuss — Primary UI text for labels, buttons, navigation, and detailed information. Its compact nature supports high information density with active tracking. · `--font-ntneuss`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px
- **Line height:** 1.00, 1.20, 1.50, 2.10
- **Letter spacing:** 0.036em at 14px, 0.122em at 8px
- **Role:** Primary UI text for labels, buttons, navigation, and detailed information. Its compact nature supports high information density with active tracking.

### RecklessNeue-Book — Headlines and descriptive body copy, providing an elegant counterpoint to the more utilitarian NTNeuss. The normal letter spacing contributes to its legibility at larger sizes. · `--font-recklessneue-book`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 16px, 21px
- **Line height:** 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Headlines and descriptive body copy, providing an elegant counterpoint to the more utilitarian NTNeuss. The normal letter spacing contributes to its legibility at larger sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-sm | 11px | 1.5 | — | `--text-body-sm` |
| body | 12px | 1.5 | — | `--text-body` |
| body-lg | 13px | 1.5 | — | `--text-body-lg` |
| heading-sm | 14px | 1.5 | — | `--text-heading-sm` |

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
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 26px |
| cards | 6px |
| badges | 4px |
| inputs | 6px |
| buttons | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.08) 1px 1px 6px -1px` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 6px

## Components

### Live Indicator Button
**Role:** Primary Call to Action

Filled button with 'Action Crimson' (#ba2223) background and 'Canvas White' text. Has a 4px `borderRadius` and generous horizontal padding (19px left, 11px right) with 5px vertical padding, indicating a clear, prominent action element.

### Ghost Schedule Button
**Role:** Secondary Action

Ghost button with 'Silver Mist' (#b5b5b5) background, 'Canvas White' text, and a 4px `borderRadius`. Uses 11px horizontal padding and 5px vertical padding to indicate selectable but non-primary status.

### Navigation Link Button
**Role:** Tertiary Navigation Link

Transparent button with 'Canvas White' text and a 6px `borderRadius`. Minimal padding of 6px horizontal and 1px vertical, used for top-level navigation items like 'Sneak TV'.

### Product Info Card (Detailed)
**Role:** Content Display, Primary Information Card

A card with 'Canvas White' (#ffffff) background at 83% opacity, 6px `borderRadius`, and a subtle `boxShadow` of `rgba(0, 0, 0, 0.08) 1px 1px 6px -1px`. Generous internal padding (40px horizontal, 40px top, 8px bottom) for main content display.

### Product Item Card (Compact)
**Role:** List Item, Product Thumbnail

A card with no background, no border radius, and no shadow, used for individual product listings within a scrollable list. Minimal 0px padding, maintaining a dense layout for product browsing.

### Search Input Field
**Role:** User Input

Input field with 'Canvas White' (#ffffff) background, 'Midnight Graphite' (#3d3d3d) text and border, and 6px `borderRadius`. Features 10px vertical padding and 30px right padding with 0px left padding, suggesting an icon might occupy the left space.

### Category Badge
**Role:** Categorization Label

Badge with 'Pale Ash' (#f0eeed) background and 'Deep Space' (#000000) text. Has a 4px `borderRadius` and compact 7px horizontal, 2px vertical padding. Used to categorize items, e.g., 'Mens'.

## Do's and Don'ts

### Do
- Prioritize 'Canvas White' (#ffffff) and 'Pale Ash' (#f0eeed) for distinct surface levels, reserving 'Canvas White' for primary content cards and 'Pale Ash' for secondary badges or backgrounds.
- Use 'Action Crimson' (#ba2223) exclusively for vital call-to-action buttons and live indicators to maintain its impact and visual hierarchy.
- Apply `borderRadius` of 6px for most interactive elements like cards, buttons, and inputs, but use 4px for smaller interactive elements like badges.
- Employ the `rgba(0, 0, 0, 0.08) 1px 1px 6px -1px` shadow for subtle elevation on primary content cards, avoiding heavy or multiple shadows.
- Maintain high information density with NTNeuss at small sizes and active `letterSpacing` for UI elements (0.036em-0.122em).
- Utilize 6px as the primary `elementGap` for tight vertical spacing between UI elements within a compact layout.
- Ensure 'Midnight Graphite' (#3d3d3d) is the default for most body and interactive text for maximum readability on light backgrounds.

### Don't
- Avoid introducing new saturated colors; adhere strictly to 'Action Crimson' (#ba2223) as the sole vibrant brand accent.
- Do not use heavy shadows or gradients; rely on subtle elevation and clean surface breaks for visual hierarchy.
- Refrain from drastically altering default letter spacing for RecklessNeue-Book; it is intended for fluid readability.
- Do not use border radii larger than 6px for typical UI components, except for specific decorative elements that require 26px.
- Avoid excessive padding on interactive elements; maintain the compact density seen across buttons and badges.
- Do not use dark backgrounds for primary content areas; the theme is predominantly light with overlaid elements.
- Do not introduce complex animations or transitions; stick to provided durations and `ease` timing for a moderate, efficient feel.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and main content cards |
| 1 | Pale Ash | `#f0eeed` | Secondary background for badges and subtle sections |
| 2 | Concrete Gray | `#8d8d8d` | Background for interactive linked cards and product listings |

## Elevation

- **Product Info Card (Detailed):** `rgba(0, 0, 0, 0.08) 1px 1px 6px -1px`

## Imagery

Imagery features tightly cropped product photography on neutral backgrounds, often with model hands interacting with items. Product focus is paramount, with little to no lifestyle context. Iconography is minimalist, likely outlined or solid, with a clean stroke weight, primarily monochrome and functional. Graphics are used sparingly, serving as decorative accents or navigational aids without overwhelming the UI. The overall density is image-heavy in product listings but balanced in informational sections.

## Layout

The page exhibits a full-bleed background often featuring dynamic video or photography, over which a contained, right-aligned UI panel floats. The hero section is characterized by this overlaid panel structure. Content within the UI panel is arranged in a consistent vertical flow, featuring a main informational card followed by a scrollable list of compact product item cards. There is no strict grid for main content outside the panel, but product items within the list appear as uniform, vertically stacked elements. Navigation is minimal, consisting of a top-bar with text links and subtle indicators, while the main UI panel acts as a dynamic content display.

## Agent Prompt Guide

Quick Color Reference:
text: #3d3d3d
background: #ffffff
border: #3d3d3d
accent: #142161
primary action: #ba2223 (filled action)

Example Component Prompts:
1. Create a primary action button: 'Live Indicator Button' with text 'LIVE', background 'Action Crimson' (#ba2223), text 'Canvas White' (#ffffff), 4px radius, 5px vertical padding, 19px left padding, 11px right padding.
2. Create a product information card: 'Product Info Card (Detailed)' with background 'Canvas White' (#ffffff) at 83% opacity, 6px radius, `boxShadow` `rgba(0, 0, 0, 0.08) 1px 1px 6px -1px`, 40px horizontal padding, 40px top padding, 8px bottom padding.
3. Create a category badge: 'Category Badge' with text 'Mens', background 'Pale Ash' (#f0eeed), text 'Deep Space' (#000000), 4px radius, 7px horizontal padding, 2px vertical padding, using NTNeuss weight 400 at 9px with 0.06em letter spacing.
4. Create a secondary action button: 'Ghost Schedule Button' with text 'SCHEDULE', background 'Silver Mist' (#b5b5b5), text 'Canvas White' (#ffffff), 4px radius, 5px vertical padding, 11px horizontal padding.

## Similar Brands

- **GOAT** — Similar focus on luxury product display with clean, contained UI elements overlaid on dynamic backgrounds. Uses a compact information architecture with subtle elevation.
- **Farfetch** — Employs high-contrast text on light surfaces for product listings and detail pages, with a minimal brand accent color and precise typography for a high-end feel.
- **SSENSE** — Features a strong lean towards monochrome visuals and a dominant white canvas, accentuating product imagery and utilizing a compact, almost editorial typography style.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #3d3d3d;
  --color-canvas-white: #ffffff;
  --color-deep-space: #000000;
  --color-concrete-gray: #8d8d8d;
  --color-pale-ash: #f0eeed;
  --color-wolf-gray: #9e9e9e;
  --color-silver-mist: #b5b5b5;
  --color-digital-violet: #142161;
  --color-action-crimson: #ba2223;

  /* Typography — Font Families */
  --font-ntneuss: 'NTNeuss', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-recklessneue-book: 'RecklessNeue-Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 11px;
  --leading-body-sm: 1.5;
  --text-body: 12px;
  --leading-body: 1.5;
  --text-body-lg: 13px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 14px;
  --leading-heading-sm: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-3xl: 26px;

  /* Named Radii */
  --radius-tags: 26px;
  --radius-cards: 6px;
  --radius-badges: 4px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.08) 1px 1px 6px -1px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-pale-ash: #f0eeed;
  --surface-concrete-gray: #8d8d8d;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #3d3d3d;
  --color-canvas-white: #ffffff;
  --color-deep-space: #000000;
  --color-concrete-gray: #8d8d8d;
  --color-pale-ash: #f0eeed;
  --color-wolf-gray: #9e9e9e;
  --color-silver-mist: #b5b5b5;
  --color-digital-violet: #142161;
  --color-action-crimson: #ba2223;

  /* Typography */
  --font-ntneuss: 'NTNeuss', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-recklessneue-book: 'RecklessNeue-Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 11px;
  --leading-body-sm: 1.5;
  --text-body: 12px;
  --leading-body: 1.5;
  --text-body-lg: 13px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 14px;
  --leading-heading-sm: 1.5;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-3xl: 26px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.08) 1px 1px 6px -1px;
}
```
