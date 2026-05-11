# Adanola — Style Reference
> monochrome fashion catalog

**Theme:** light

Adanola embraces a fashion-forward, understated aesthetic with a stark monochrome palette that highlights product imagery. The design relies on high-contrast typography and subtle interactions, creating a premium feel without visual clutter. Surfaces remain clean and unadorned, allowing product photography to command attention, while functional elements use solid black for emphasis and clarity. Spacing is tight and deliberate, promoting a compact, content-focused presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text and borders, text on dark backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, headings, filled button backgrounds, primary action borders, navigation elements, icons |
| Ash Gray | `#e5e7eb` | `--color-ash-gray` | Subtle section backgrounds, passive states, secondary surface elements |
| Disabled Gray | `#d1d5db` | `--color-disabled-gray` | Disabled button backgrounds |
| Faded Stone | `#cccccc` | `--color-faded-stone` | Muted UI surface for disabled controls, low-emphasis panels, and placeholder blocks. Do not promote it to the primary CTA color |
| Text Secondary Black | `#00000080` | `--color-text-secondary-black` | Secondary text, muted details, placeholder text before interaction |
| Wishlist Red | `#dc2626` | `--color-wishlist-red` | Accent for wishlist active state, subtle urgency |
| Focus Blue | `#41a1e6` | `--color-focus-blue` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Subtle Gradient | `linear-gradient(to right, rgb(223, 226, 225) 50%, rgb(103, 139, 199) 50%)` | `--color-subtle-gradient` | Decorative background gradient used for specific sections, providing a soft transition between cool and warm neutrals |

## Tokens — Typography

### Favorit — Primary typeface for all UI elements: body text, headings, links, and buttons. Its wide range of weights and sizes, combined with consistent letter-spacing, establishes a confident, precise voice. · `--font-favorit`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 9px, 12px, 14px, 16px, 20px, 30px
- **Line height:** 1.00, 1.20, 1.33, 1.40
- **Letter spacing:** 0.025em
- **Role:** Primary typeface for all UI elements: body text, headings, links, and buttons. Its wide range of weights and sizes, combined with consistent letter-spacing, establishes a confident, precise voice.

### swym-font — Used for utility buttons and icon labels, suggesting a functional, compact nature. · `--font-swym-font`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Used for utility buttons and icon labels, suggesting a functional, compact nature.

### Arial — Fallback and minimal textual content where a system font is preferred, ensuring broad compatibility. · `--font-arial`
- **Substitute:** Helvetica Neue, Helvetica, sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and minimal textual content where a system font is preferred, ensuring broad compatibility.

### Nunito Sans — Used sparingly for specific input fields or secondary information, providing a slightly softer counterpoint to Favorit for distinct elements. · `--font-nunito-sans`
- **Substitute:** sans-serif
- **Weights:** 400, 700
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used sparingly for specific input fields or secondary information, providing a slightly softer counterpoint to Favorit for distinct elements.

### Source Sans Pro — Auxiliary font for minor text elements or specific system messages. · `--font-source-sans-pro`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Auxiliary font for minor text elements or specific system messages.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.4 | — | `--text-body` |
| heading | 20px | 1.33 | — | `--text-heading` |
| display | 30px | 1.33 | — | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| nav | 4px |
| buttons | 4px |

### Layout

- **Section gap:** 64px
- **Card padding:** 0px
- **Element gap:** 4px

## Components

### Primary Filled Button
**Role:** Calls to action, form submissions, and active navigation items.

Solid Ink Black background (#000000), Canvas White text (#ffffff), no border-radius (0px), with padding 11px vertical and 24px horizontal. Uses Favorit 16px font.

### Ghost Button
**Role:** Secondary actions, filtering, or navigation where visual weight needs to be minimal.

Transparent background (rgba(0,0,0,0)), Ink Black text (#000000), no border-radius (0px), with minimal padding (4px vertical, 8px horizontal). Uses Favorit 12px font.

### Quick Add Button
**Role:** Ephemeral action buttons presented over product images.

Translucent white background (rgba(255,255,255,0.75)), Ink Black text (#000000), no border-radius (0px), with no explicit padding defined, indicating tight internal spacing determined by context.

### Product Card
**Role:** Displaying product items in grids.

Transparent background (rgba(0,0,0,0)), no border-radius (0px), no box shadow, with no internal padding on the main card container, allowing imagery to bleed to edges.

### Text Input
**Role:** User input fields.

Canvas White background (#ffffff), Ink Black text (#000000), solid Ink Black border (1px solid #000000), no border-radius (0px), with 16px left padding. Placeholder text is Muted Text Secondary Black (#00000080).

### Icon Button
**Role:** Interactive icons in header or product listings.

No background, Ink Black (#000000) or Canvas White (#ffffff) for icon fill/stroke, with 4px border-radius, acting as a small target area for interaction.

### Subtle Nav Tag
**Role:** Category navigation tags or filters.

Transparent background, Ink Black text (#000000), 4px border-radius, with 6px vertical and 10px horizontal padding. Uses Favorit 12px font.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#000000) and Canvas White (#ffffff) for all primary UI elements, reserving color for semantic and subtle accent needs.
- Apply Favorit font (weights 400, 500, 700) with 0.025em letter-spacing for all headings and body text to maintain a consistent, precise typographic tone.
- Use a 0px border-radius for most interactive elements and cards, emphasizing a sharp, contemporary design.
- Employ the Primary Filled Button style (#000000 background, #ffffff text) for all key calls to action.
- Maintain a compact elementGap of 4px to keep UI dense and content-focused. Larger vertical gaps are reserved for distinct section breaks.
- Use Ash Gray (#e5e7eb) or Faded Stone (#cccccc) for subtle background changes between visual sections, maintaining overall lightness.
- Ensure all input fields have a 1px solid Ink Black border, a Canvas White background, and at least 16px left padding.

### Don't
- Avoid using multiple colors for primary textual hierarchy; rely on Ink Black (#000000) for all main text.
- Do not introduce rounded corners arbitrarily; only apply 4px border-radius to specific navigation and small interactive elements (e.g. icon buttons).
- Do not use generic gray buttons for calls to action; always use Ink Black (#000000) filled buttons for primary actions.
- Never create heavy drop shadows or significant elevation that distracts from product imagery; surfaces should remain flat.
- Do not break the established typographic letter-spacing pattern of 0.025em for Favorit, especially on headings.
- Avoid using background colors other than Canvas White or Ash Gray for large section backgrounds, to preserve the monochrome aesthetic.
- Do not add internal padding to Product Cards; let product imagery define the card's visual boundaries.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base layer for content. |
| 1 | Ash Gray | `#e5e7eb` | Subtle background for secondary content blocks or alternating sections. |
| 2 | Faded Stone | `#cccccc` | Background for certain interactive areas, e.g., pagination or carousels. |

## Imagery

This design largely relies on high-quality, full-bleed product photography, often featuring models in active poses. Photos are rarely masked, presenting raw edges and occupying a significant visual space. Images are typically bright, well-lit, and focus on the apparel. Icons are minimal, outlined, and monochromatic, primarily Ink Black, serving functional roles rather than decorative ones. Imagery is content-dominant, directly showcasing products with minimal surrounding UI interference.

## Layout

The site uses a max-width contained layout generally, with a full-bleed hero section. The hero prominently features large product imagery and a centered headline. Sections alternate between full-width content blocks and multi-column grids (like the 3-column product grid). Vertical rhythm is maintained through consistent spacing, though individual card padding is omitted to maximize image presence. Navigation is a compact, sticky top bar with a hidden mega-menu behavior.

## Agent Prompt Guide

### Quick Color Reference
text: #000000
background: #ffffff
border: #000000
accent: #dc2626
primary action: #000000 (filled action)

### 3-5 Example Component Prompts
1. Create a header navigation link: Favorit 12px, weight 400, #000000, 0.025em letter-spacing. On hover, apply a 1px solid #000000 underline.
2. Design a primary call-to-action button: Solid #000000 background, #ffffff text (Favorit 16px, weight 500, 0.025em letter-spacing), 0px border-radius, 11px vertical padding, 24px horizontal padding.
3. Build a product card item: No background, no internal padding, 0px border-radius. Product name uses Favorit 14px, weight 400, #000000, with a price below in Favorit 12px, weight 400, #000000.
4. Compose a centered hero headline: Favorit 30px, weight 700, #000000, 0.025em letter-spacing. Subtext uses Favorit 16px, weight 400, #000000.
5. Create an input field: Canvas White background (#ffffff), 1px solid Ink Black border (#000000), 0px border-radius, 16px left padding, Favorit 14px, weight 400, #000000 text. Placeholder text is Text Secondary Black (#00000080).

## Similar Brands

- **SKIMS** — Monochromatic focus on bodywear and loungewear, using high-quality product photography with minimal UI embellishments.
- **Alo Yoga** — Premium activewear brand with a clean, high-contrast aesthetic, emphasizing product imagery and simple typography.
- **Gymshark** — E-commerce platform for activewear, utilizes a similar product-focused visual style with strong black and white elements and direct calls to action.
- **Everlane** — Minimalist e-commerce with a strong emphasis on clean typography and product-centric visuals, often with monochrome palettes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #e5e7eb;
  --color-disabled-gray: #d1d5db;
  --color-faded-stone: #cccccc;
  --color-text-secondary-black: #00000080;
  --color-wishlist-red: #dc2626;
  --color-focus-blue: #41a1e6;
  --color-subtle-gradient: #dfccbe;
  --gradient-subtle-gradient: linear-gradient(to right, rgb(223, 226, 225) 50%, rgb(103, 139, 199) 50%);

  /* Typography — Font Families */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-swym-font: 'swym-font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans: 'Nunito Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --text-display: 30px;
  --leading-display: 1.33;

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

  /* Layout */
  --section-gap: 64px;
  --card-padding: 0px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-nav: 4px;
  --radius-buttons: 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ash-gray: #e5e7eb;
  --surface-faded-stone: #cccccc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #e5e7eb;
  --color-disabled-gray: #d1d5db;
  --color-faded-stone: #cccccc;
  --color-text-secondary-black: #00000080;
  --color-wishlist-red: #dc2626;
  --color-focus-blue: #41a1e6;
  --color-subtle-gradient: #dfccbe;

  /* Typography */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-swym-font: 'swym-font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans: 'Nunito Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --text-display: 30px;
  --leading-display: 1.33;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;

  /* Border Radius */
  --radius-md: 4px;
}
```
