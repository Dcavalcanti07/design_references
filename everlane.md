# Everlane — Style Reference
> Raw linen and exposed grain. This design feels like natural fibers and honest construction, prioritizing unadorned function and understated elegance.

**Theme:** light

The Everlane design system evokes refined simplicity through a largely achromatic palette, allowing product imagery and subtle accents to take center stage. Its characteristic look is defined by a rigorous focus on typography, utilizing custom sans-serif fonts at precise weights and letter-spacing for hierarchical messaging, paired with generous white space. The overall impression is one of calm, deliberate presentation, where visual noise is actively suppressed to highlight content purity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, critical UI elements, strong borders, icons, navigation links — establishes a clear, authoritative presence against light backgrounds. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, interactive element backgrounds — provides a clean, expansive base for content and imagery. |
| Slate Gray | `#4c4c4c` | `--color-slate-gray` | Secondary text, button text on light backgrounds, less prominent links — offers contrast without the starkness of pure black, common in auxiliary information. |
| Cement Gray | `#737373` | `--color-cement-gray` | Tertiary text, subtle borders, inactive states — used for metadata or less emphasized elements, maintaining legibility without drawing primary attention. |
| Ash Gray | `#9b9b9b` | `--color-ash-gray` | Light borders, dividers — provides minimal visual separation. |
| Forest Green | `#d9e9bb` | `--color-forest-green` | Promotional banners, subtle background accents — introduces a muted, natural color without overpowering the achromatic base, suggesting fresh branding or limited-time offers. |

## Tokens — Typography

### Maison Neue Book — The primary typeface for all textual content, from body text to headlines and interactive elements. Its varied weights and precise letter-spacing dictate a clean, breathable hierarchy, establishing a consistent brand voice across all textual communication. The generous line-heights enhance readability for the extensive textual content. · `--font-maison-neue-book`
- **Substitute:** Inter, Arial
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 20px, 24px, 32px
- **Line height:** 1.00, 1.20, 1.25, 1.30, 1.33, 1.35, 1.40, 1.43, 1.50, 1.60, 1.80, 2.25
- **Letter spacing:** 0.0200em, 0.0240em, 0.0300em, 0.0330em, 0.0380em, 0.0400em, 0.0430em, 0.0500em, 0.0600em, 0.0670em
- **Role:** The primary typeface for all textual content, from body text to headlines and interactive elements. Its varied weights and precise letter-spacing dictate a clean, breathable hierarchy, establishing a consistent brand voice across all textual communication. The generous line-heights enhance readability for the extensive textual content.

### Maison Neue Demi — Used for specific headings, providing a slightly stronger emphasis without shifting to a heavy weight or different font family, maintaining the overall light and refined typographic feel. · `--font-maison-neue-demi`
- **Substitute:** Inter Bold, Arial Bold
- **Weights:** 600
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** 0.0200em
- **Role:** Used for specific headings, providing a slightly stronger emphasis without shifting to a heavy weight or different font family, maintaining the overall light and refined typographic feel.

### GTStandard-M — A subtle accent typeface, likely used for specific technical or stylized content, bringing a touch of modern distinctiveness without clashing with the dominant sans-serif. · `--font-gtstandard-m`
- **Substitute:** Roboto Mono, Space Mono
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** 0.0380em
- **Role:** A subtle accent typeface, likely used for specific technical or stylized content, bringing a touch of modern distinctiveness without clashing with the dominant sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.38px | `--text-caption` |
| heading | 24px | 1.25 | 0.48px | `--text-heading` |
| display | 32px | 1.2 | 0.64px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 15px
- **Element gap:** 4-16px

## Components

### Navigation Link
**Role:** Interactive text link within navigation menus.

Text is Maison Neue Book, 400 weight, 12px with 1.5 line height, and a letter-spacing of approx 0.05em (0.6px). Color is Midnight Ink (#000000). No border or background unless active.

### Primary Action Button (Text)
**Role:** Main call-to-action on promotional sections or product details.

Transparent background, Midnight Ink (#000000) text color. Maison Neue Book 400. Text is often uppercase, with 0px padding and a 1px bottom border on hover or active states. Example: 'SHOP DRESSES'.

### Standard Input Field
**Role:** User input for forms and search.

Canvas White (#ffffff) background with Midnight Ink (#121212) text and a 1px border. Padding is 15px top/bottom and 15px left. Font is Maison Neue Book.

### Product Grid Item
**Role:** Displaying individual products in a catalog.

Consists of an image above product title and price. Product title is Midnight Ink (#000000) Maison Neue Book 400, 12px, 1.33 line-height. Price is Maison Neue Book 700. No visible borders or backgrounds on the item container, relying on page background for separation.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and critical interactive elements to maintain high contrast and clarity.
- Maintain a clear visual hierarchy using Maison Neue Book, varying weight (400 for body, 700 for strong emphasis) and size (12px for body, 32px for display) with precise letter spacing.
- Employ Canvas White (#ffffff) as the dominant background color to create a spacious, clean aesthetic.
- Apply 0px border-radius consistently across all elements (buttons, inputs, cards) to preserve a sharp, angular aesthetic.
- Utilize Forest Green (#d9e9bb) sparingly for promotional banners or specific accent areas to introduce color without overwhelming the neutral palette.
- Ensure generous line-height for all text, particularly body text (Maison Neue Book 15px @ 1.6 line-height), to enhance readability in text-heavy sections.

### Don't
- Avoid using bright or overly saturated colors, as they will clash with the muted, natural palette.
- Do not introduce rounded corners; maintain the established sharp, 0px radius for all design elements.
- Refrain from using drop shadows or complex elevation; depth is created through color contrast and thoughtful spacing, not layered effects. If any box-shadow, keep it very subtle and tight.
- Do not deviate from Maison Neue Book for primary text; introduction of other fonts will break the consistent typographic brand.
- Avoid dense information blocks; use ample line-heights and minimal letter-spacing to ensure content feels open and digestible.

## Imagery

Photography is paramount, featuring professional models in a mix of lifestyle and studio settings. The treatment is often desaturated or subtly muted, focusing on showing the clothing on real people in aspirational, yet understated, environments. Images are primarily full-bleed in hero sections or clean, contained product shots on white/light backgrounds. No decorative graphics or illustrations; the visual language is entirely photographic, focusing on product and brand aesthetic. Sparse, simple iconography is used for UI actions.

## Layout

The page maintains a centered, max-width layout for most content, but hero sections frequently utilize full-bleed photography. The hero pattern is typically a large, evocative image with minimal, left-aligned text overlays. Sections are generally separated by consistent vertical spacing (implied 48-80px), creating a breathable rhythm. Content is arranged in flexible patterns, including large full-width image sections, side-by-side text and imagery, and multi-column product grids (e.g., 4-column for product displays). Navigation is a sticky top bar with clearly segmented links.

## Agent Prompt Guide

**Quick Color Reference:**
- Text: #000000 (Midnight Ink)
- Background: #ffffff (Canvas White)
- Accent: #d9e9bb (Forest Green)
- Secondary Text: #4c4c4c (Slate Gray)
- Border: #9b9b9b (Ash Gray)

**3-5 Example Component Prompts:**
1. Create a hero section: full-bleed image background (placeholder 'lifestyle fashion photo'), centered text overlay 'SIMPLY FEMININE' using Maison Neue Book 32px, 700 weight, #000000, 1.20 lineHeight. Below it, a line of body text 'Effortless silhouettes, forever in your wardrobe.' Maison Neue Book 15px, 400 weight, #000000, 1.6 lineHeight. Add a primary action button 'SHOP DRESSES' Maison Neue Book 12px, 400 weight, #000000, transparent background, 0px padding, with a 1px border-bottom only on hover.
2. Design a promotional banner: #d9e9bb (Forest Green) background, 100% width, 32px vertical padding. Centered text 'SPRING ESSENTIALS EVENT' in Maison Neue Book 12px, 400 weight, #000000, 1.5 lineHeight, letter-spacing 0.48px. Include two text links 'Shop Women' and 'Shop Men' in the same style, separated by a vertical divider.
3. Build a product grid: 4 columns, 24px column-gap. Each product item contains a square image placeholder at the top, a product title 'Halter Dress in Ultrasoft Cotton' below, Maison Neue Book 12px, 400 weight, #000000, 1.33 lineHeight. Below the title, a price '€140' in Maison Neue Book 12px, 700 weight, #000000, 1.33 lineHeight. No borders or backgrounds on individual items.
4. Generate a newsletter signup input field: 100% width, Canvas White (#ffffff) background, 1px Midnight Ink (#121212) border, 0px border-radius. Placeholder text 'Enter your email' in Maison Neue Book 15px, 400 weight, #737373 (Cement Gray). Padding 15px top/bottom, 15px left.

## Similar Brands

- **COS** — Shares a focus on minimalist aesthetic, achromatic palette, high-quality photography, and a strong typographic identity for refined fashion.
- **Uniqlo** — Similar emphasis on functional, everyday wear presented in a clean, straightforward e-commerce experience with clear visual hierarchy.
- **ARKET** — Utilizes a clean, editorial-like layout, natural color palette, and high-quality product photography to convey a sense of calm and considered design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-slate-gray: #4c4c4c;
  --color-cement-gray: #737373;
  --color-ash-gray: #9b9b9b;
  --color-forest-green: #d9e9bb;

  /* Typography — Font Families */
  --font-maison-neue-book: 'Maison Neue Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-maison-neue-demi: 'Maison Neue Demi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.38px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.48px;
  --text-display: 32px;
  --leading-display: 1.2;
  --tracking-display: 0.64px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 15px;
  --element-gap: 4-16px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-slate-gray: #4c4c4c;
  --color-cement-gray: #737373;
  --color-ash-gray: #9b9b9b;
  --color-forest-green: #d9e9bb;

  /* Typography */
  --font-maison-neue-book: 'Maison Neue Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-maison-neue-demi: 'Maison Neue Demi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.38px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.48px;
  --text-display: 32px;
  --leading-display: 1.2;
  --tracking-display: 0.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-48: 48px;
}
```
