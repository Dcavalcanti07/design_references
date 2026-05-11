# Caldera — Style Reference
> Pixelated Cyber-Playground

**Theme:** light

Caldera embraces a high-contrast digital arcade aesthetic: a muted grey canvas acts as a stark backdrop for vivid, pixelated gradient forms and ultra-bold, tightly tracked typography. Components like cards and buttons feature generous 40px rounded corners, creating a friendly, almost toy-like solidity. The overall atmosphere is playful yet authoritative, using color sparingly for impact and interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Basalt Canvas | `#e2e2df` | `--color-basalt-canvas` | Page backgrounds, subtle card surfaces for secondary information blocks |
| Ash White | `#f7f6f2` | `--color-ash-white` | Primary card surfaces, button backgrounds, element containers |
| Abyssal Ink | `#070607` | `--color-abyssal-ink` | Heading text, primary body text, strong borders |
| Pure White | `#ffffff` | `--color-pure-white` | Input text, icon fills against dark backgrounds, text on filled buttons |
| Digital Orange | `#fc5000` | `--color-digital-orange` | Primary action buttons, prominent card backgrounds, brand accents—commands attention with playful energy |
| Cyber Violet | `#524ae9` | `--color-cyber-violet` | Decorative background shapes, accent cards within complex graphics |
| Pixel Glare | `#f5f28e` | `--color-pixel-glare` | Highlight overlays, graphic accents, subtle background patterns for visual texture |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### PP Neue Corp Compact Ultrabold — Display and heading text. Its ultrabold weight and compact form define the brand's assertive, almost shouting voice. Tight letter-spacing reinforces the density. · `--font-pp-neue-corp-compact-ultrabold`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 26px, 32px, 40px, 48px, 56px, 64px, 80px, 96px, 189px
- **Line height:** 0.94, 0.95, 1.00, 1.10, 1.20
- **Letter spacing:** 0.0200em
- **OpenType features:** `"ss06", "ss10"`
- **Role:** Display and heading text. Its ultrabold weight and compact form define the brand's assertive, almost shouting voice. Tight letter-spacing reinforces the density.

### DM Sans — Body text, navigation links, and input labels. Provides readability and a modern, slightly geometric counterpoint to the display font. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 14px, 16px, 18px, 30px
- **Line height:** 1.11, 1.20, 1.25, 1.50, 1.55
- **Letter spacing:** normal
- **Role:** Body text, navigation links, and input labels. Provides readability and a modern, slightly geometric counterpoint to the display font.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.25 | — | `--text-body-sm` |
| body | 16px | 1.55 | — | `--text-body` |
| subheading | 30px | 1.11 | — | `--text-subheading` |
| heading-sm | 32px | 0.95 | 0.02px | `--text-heading-sm` |
| heading | 56px | 0.94 | 0.02px | `--text-heading` |
| display | 96px | 0.94 | 0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 92 | 92px | `--spacing-92` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 40px |
| inputs | 100px |
| buttons | 800px |
| default | 40px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Call-to-action

Filled button with `Digital Orange (#fc5000)` background, `Pure White (#ffffff)` text (DM Sans 500), `800px` border-radius for pill shape, 12px vertical and 24px horizontal padding.

### Ghost Button
**Role:** Secondary action

Transparent background with `Abyssal Ink (#070607)` border and text (DM Sans 500), `800px` border-radius, 0px vertical and 12px horizontal padding for a minimal pill outline. The browser default blue text of rgb(0,0,238) from the data is a browser artifact, not a design choice for ghost buttons.

### Navigation Link Button
**Role:** Navigation, internal links

Minimalist button with `Ash White (#f7f6f2)` background, `000000` text (DM Sans 500), `40px` border-radius. 16px padding on all sides.

### Stats Card - Orange
**Role:** Informational display

Dedicated information card with `Digital Orange (#fc5000)` background, `40px` border-radius, 40px padding on all sides. Text inside should be `Pure White (#ffffff)` using PP Neue Corp Compact Ultrabold for numbers and DM Sans for labels.

### Stats Card - Ash White
**Role:** Informational display

Dedicated information card with `Ash White (#f7f6f2)` background, `40px` border-radius, 40px padding on all sides. Text inside should be `Abyssal Ink (#070607)` using PP Neue Corp Compact Ultrabold for numbers and DM Sans for labels.

### Basic Content Card
**Role:** Content container

Generic content card with `Ash White (#f7f6f2)` background, `40px` border-radius, 40px padding on all sides. Can contain headings and body text in `Abyssal Ink (#070607)`.

### Auth Input Field
**Role:** User input

Transparent input field with `Pure White (#ffffff)` border and placeholder text, `100px` border-radius for a pill shape, 24px vertical and 32px left padding, 64px right padding. Focus state should highlight the border prominently.

## Do's and Don'ts

### Do
- Prioritize `PP Neue Corp Compact Ultrabold` for all headlines and display text, applying its 'ss06', 'ss10' font feature settings and 0.0200em letter-spacing for consistent brand delivery.
- Use `Digital Orange (#fc5000)` as the exclusive background color for all primary calls-to-action and key informational cards to ensure immediate visual prominence.
- Apply a generous `40px` `border-radius` to all cards, content blocks, and navigation buttons to maintain the inviting, rounded brand aesthetic.
- Employ `Basalt Canvas (#e2e2df)` as the primary page background, creating a muted base that allows the vivid accent colors to pop.
- Ensure pill-shaped elements like primary buttons and input fields consistently use an `800px` or `100px` `border-radius` respectively for a distinct form.
- Maintain a clear visual hierarchy by rendering primary text in `Abyssal Ink (#070607)` on `Ash White (#f7f6f2)` or `Basalt Canvas (#e2e2df)` surfaces.
- Use `40px` padding on all sides of `Ash White (#f7f6f2)` and `Digital Orange (#fc5000)` cards to provide ample breathing room for content.

### Don't
- Avoid using `Pure White (#ffffff)` as a solid background color; reserve it for text fields or text on dark backgrounds to preserve the overall muted canvas.
- Do not deviate from the `40px` card `border-radius` for main content blocks or feature cards; inconsistency will undermine the brand's friendly solidity.
- Refrain from using `Cyber Violet (#524ae9)` as a text color or primary UI element; its role is purely decorative for large background shapes and graphic accents.
- Do not introduce gradients or shadows for elevation on most components; the design relies on flat, solid color blocks and distinct shapes for visual hierarchy.
- Avoid tight spacing (e.g., less than `10px` `elementGap`) between interactive elements to prevent visual clutter and ensure comfortable interaction.
- Do not use generic sans-serif fonts for headlines; `PP Neue Corp Compact Ultrabold`'s distinct character is crucial for brand recognition.
- Do not use the browser default blue link color (rgb(0,0,238)); all links and ghost buttons should use `Abyssal Ink (#070607)` for their text and border.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Basalt Canvas | `#e2e2df` | Base page background, subtle dividers |
| 2 | Ash White | `#f7f6f2` | Primary card backgrounds, navigation containers |
| 3 | Digital Orange Accent | `#fc5000` | Prominent feature cards, primary button fills |

## Imagery

Imagery is functional and abstract: often large, bold, two-tone pixelated graphics featuring `Digital Orange` and `Cyber Violet` in fluid, rounded, non-rectangular shapes. These graphics act as hero background elements or contained visual modules. Product screenshots or logos are typically monochrome `Abyssal Ink` outlines or `Pure White` fills, contained within `Ash White` cards, for a clean, understated product showcase. Icons are simple, outlined `Abyssal Ink` or `Pure White` glyphs, keeping a flat, sharp style.

## Layout

The page adheres to a `1200px` max-width contained layout, centered on a `Basalt Canvas` background. The hero section features a full-width background graphic with a large, centered `PP Neue Corp Compact Ultrabold` headline. Following sections employ consistent vertical `sectionGap` of `40px` and alternate between centered stacked content and two-column layouts with text and image-like graphics side-by-side. Feature blocks and statistics often use `Digital Orange` and `Ash White` cards arranged in a 4-column grid, maintaining a comfortable, open density.

## Agent Prompt Guide

Quick Color Reference:
- text: #070607
- background: #e2e2df
- border: #070607 (for ghost buttons)
- accent: #524ae9
- primary action: #fc5000 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #fc5000 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a feature card grid: `Ash White (#f7f6f2)` background, `40px` radius, 40px all-around padding. Feature headline in `Abyssal Ink (#070607)` using `PP Neue Corp Compact Ultrabold` at 32px weight 400, letter-spacing 0.02em. Body text in `Abyssal Ink (#070607)` using `DM Sans` at 16px weight 500, normal letter-spacing.
- Create a stats display block: `Digital Orange (#fc5000)` cards, `40px` radius, 40px all-around padding. Numbers in `Pure White (#ffffff)` using `PP Neue Corp Compact Ultrabold` at 56px weight 400, letter-spacing 0.02em. Labels in `Pure White (#ffffff)` using `DM Sans` at 18px weight 500, normal letter-spacing.

## Similar Brands

- **Optimism** — Shares a vibrant color palette against a light neutral background and uses simplified, bold graphic shapes.
- **Arbitrum** — Similar focus on blockchain infrastructure with clean, modern typography and distinct accent colors for key elements.
- **Celestia** — Adopts a spacious, minimalist layout combined with strong, geometric typography and a vibrant accent color to highlight product features.
- **StarkWare** — Employs an architectural, block-based UI with specific accent colors and a focus on bold, contemporary typography for a tech-forward feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-basalt-canvas: #e2e2df;
  --color-ash-white: #f7f6f2;
  --color-abyssal-ink: #070607;
  --color-pure-white: #ffffff;
  --color-digital-orange: #fc5000;
  --color-cyber-violet: #524ae9;
  --color-pixel-glare: #f5f28e;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-corp-compact-ultrabold: 'PP Neue Corp Compact Ultrabold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.55;
  --text-subheading: 30px;
  --leading-subheading: 1.11;
  --text-heading-sm: 32px;
  --leading-heading-sm: 0.95;
  --tracking-heading-sm: 0.02px;
  --text-heading: 56px;
  --leading-heading: 0.94;
  --tracking-heading: 0.02px;
  --text-display: 96px;
  --leading-display: 0.94;
  --tracking-display: 0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-92: 92px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 800px;

  /* Named Radii */
  --radius-cards: 40px;
  --radius-inputs: 100px;
  --radius-buttons: 800px;
  --radius-default: 40px;

  /* Surfaces */
  --surface-basalt-canvas: #e2e2df;
  --surface-ash-white: #f7f6f2;
  --surface-digital-orange-accent: #fc5000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-basalt-canvas: #e2e2df;
  --color-ash-white: #f7f6f2;
  --color-abyssal-ink: #070607;
  --color-pure-white: #ffffff;
  --color-digital-orange: #fc5000;
  --color-cyber-violet: #524ae9;
  --color-pixel-glare: #f5f28e;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-corp-compact-ultrabold: 'PP Neue Corp Compact Ultrabold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.55;
  --text-subheading: 30px;
  --leading-subheading: 1.11;
  --text-heading-sm: 32px;
  --leading-heading-sm: 0.95;
  --tracking-heading-sm: 0.02px;
  --text-heading: 56px;
  --leading-heading: 0.94;
  --tracking-heading: 0.02px;
  --text-display: 96px;
  --leading-display: 0.94;
  --tracking-display: 0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-92: 92px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 800px;
}
```
