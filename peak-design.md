# Peak Design — Style Reference
> Photographic gallery on architectural black and white. Product precision through high-contrast typography.

**Theme:** light

This system embodies a utilitarian elegance, pairing stark black and white sections with subdued neutrals to frame product photography. Typography is the primary expressive element, with a high-contrast serif font for arresting headlines that feel established yet contemporary. Subtle button treatments and precise spacing prioritize content clarity and direct interaction, creating a refined, almost stoic, e-commerce experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Hero backgrounds, card backgrounds, primary text on light backgrounds, strong navigational elements; provides maximum contrast and product focus. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, button backgrounds, text on dark backgrounds; establishes a clean, open canvas. |
| Forest Black | `#1a211` | `--color-forest-black` | Primary body text, link text, borders, input text; a very dark, slightly desaturated black that offers strong readability without harshness. |
| Ash Gray | `#eef1f0` | `--color-ash-gray` | Section separators, subtle button backgrounds, input backgrounds; provides soft visual breaks. |
| Charcoal Black | `#0c0c0c` | `--color-charcoal-black` | Input text, secondary text on light backgrounds. |
| Graphite | `#606562` | `--color-graphite` | Secondary text, subtle icon fills, supporting UI elements. |
| Slate Border | `#cccfcd` | `--color-slate-border` | Input borders, subtle dividers; defines boundaries without visual weight. |
| Badge Gray | `#4e4e4` | `--color-badge-gray` | Content badge backgrounds; sets them apart without being an overt accent. |
| Alert Red | `#cc2e39` | `--color-alert-red` | Informational badges, perhaps used sparingly for error states or urgent CTAs, offering a sharp contrast to the neutral palette. |

## Tokens — Typography

### Exposure-10 — Display headlines and main hero statements; its high-contrast serif form provides an immediate sense of gravitas and craftsmanship. · `--font-exposure-10`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 40px, 48px, 80px
- **Line height:** 1.10
- **Letter spacing:** -0.8, -1, -2
- **Role:** Display headlines and main hero statements; its high-contrast serif form provides an immediate sense of gravitas and craftsmanship.

### Geist — Primary body text, navigation labels, and UI elements; its clean, sans-serif structure ensures maximum legibility across all informational content. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px
- **Line height:** 1.0, 1.2, 1.4, 1.5
- **Letter spacing:** 0
- **Role:** Primary body text, navigation labels, and UI elements; its clean, sans-serif structure ensures maximum legibility across all informational content.

### bryant — Uppercase CTAs, navigation links, and badges; its bold, slightly condensed form with generous letter spacing provides a strong, action-oriented voice. · `--font-bryant`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 14px, 16px, 24px, 32px
- **Line height:** 1.0, 1.1, 1.2, 1.4
- **Letter spacing:** 0.53, 0.61, 0.91, 1.22
- **Role:** Uppercase CTAs, navigation links, and badges; its bold, slightly condensed form with generous letter spacing provides a strong, action-oriented voice.

### Geist Mono — Used sparingly for specific product codes or technical details, providing a distinct, precise feel. · `--font-geist-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00
- **Letter spacing:** 0
- **Role:** Used sparingly for specific product codes or technical details, providing a distinct, precise feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 21 | — | `--text-body` |
| body-lg | 16px | 24 | — | `--text-body-lg` |
| subheading | 24px | 26.4 | 0.91px | `--text-subheading` |
| heading | 32px | 35.2 | 1.22px | `--text-heading` |
| heading-lg | 40px | 44 | -0.8px | `--text-heading-lg` |
| display | 48px | 52.8 | -1px | `--text-display` |
| display-lg | 80px | 88 | -2px | `--text-display-lg` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 9999px |
| inputs | 4px |
| buttons | 4px, 32px |

### Layout

- **Section gap:** 72px
- **Card padding:** 0px
- **Element gap:** 4px

## Components

### Primary Ghost Button
**Role:** Primary action button on dark backgrounds

Background transparent, text Forest Black (#1a211e), border Forest Black (#1a211e) 1px, 0px border-radius, 0px vertical padding, 16px horizontal padding. Uses bryant 700, 16px, line-height 1.2.

### Solid Standard Button
**Role:** Standard action button on light backgrounds

Background Cloud White (#ffffff), text Forest Black (#1a211e), 4px border-radius, 12px vertical padding, 24px horizontal padding. Uses Geist 400, 16px, line-height 1.5.

### Pill Accent Button
**Role:** Special accent or navigation button

Background Cloud White (#ffffff), text Forest Black (#1a211e), 32px border-radius, no padding defined from button component itself but contexturally implies 0px-0px. Uses Geist 400, 16px, line-height 1.5.

### Neutral Filled Button
**Role:** Secondary action button for subtle interactions

Background Ash Gray (#eef1f0), text Forest Black (#1a211e), 4px border-radius, 8px vertical padding, 16px horizontal padding. Uses Geist 400, 16px, line-height 1.5.

### Search Input (Header)
**Role:** Top navigation search bar

Background Cloud White (#ffffff), text Forest Black (#1a211e), Slate Border (#cccfcd) 1px border, 4px border-radius, 2px vertical padding, 12px horizontal padding. Placeholder text is implied 'Search for packing cubes'.

### Search Input (Block)
**Role:** Larger search input field

Background Ash Gray (#eef1f0), text Charcoal Black (#0c0c0c), Slate Border (#cccfcd) 1px border, 4px border-radius, 16px vertical padding, 12px horizontal padding. Placeholder text is implied to be Graphite (#606562).

### New Badge
**Role:** Highlighting new arrivals

Background Badge Gray (#4e4e4e), text Cloud White (#ffffff), 9999px border-radius (pill shape), 8px vertical padding, 16px horizontal padding. Uses bryant 700, 14px, line-height 1.0.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#000000) or Cloud White (#ffffff) for hero section backgrounds to create high-contrast statements.
- Use Exposure-10 (substitute Playfair Display) for all display and large heading text to convey craftsmanship and gravitas.
- Apply a 4px border-radius for all interactive elements like buttons and input fields for a subtle softening.
- Reserve bryant font with its characteristic letter-spacing (e.g., 0.61px at 16px) for uppercase action-oriented text and badges.
- Maintain a clear product-focused visual hierarchy by placing product images within cards that have 0px internal padding.
- Utilize Ash Gray (#eef1f0) as a divider or background for secondary UI elements to differentiate without interrupting the high-contrast main scheme.
- Ensure all body and informational text uses Geist (substitute Inter) at 14px or 16px for optimal legibility.

### Don't
- Do not use saturated colors for large background areas; maintain the primary black, white, and neutral palette.
- Avoid generic button styling; ensure clear differentiation between ghost, solid, and accent button variants.
- Do not introduce additional serif fonts; Exposure-10 is the singular serif. Do not use generic sans-serifs — stick to Geist and bryant.
- Avoid complex shadows; prefer flat UI elements or subtle border definitions for depth.
- Do not break the rigid grid layout with overlapping content or free-form elements; content should be contained and aligned.
- Do not use decorative elements that distract from the product imagery or strong typography.
- Do not use bold weights of Geist for normal paragraph text; reserve it for specific UI elements or semantic emphasis.

## Imagery

The visual language is characterized by high-quality product photography, often isolated on neutral backgrounds (white or light gray) for clarity, sometimes set against a stark black backdrop in hero sections. Treatment is crisp, unmasked, and contained within a structured grid. There are lifestyle photography elements, showing products in use, but these are secondary to the primary product-focused shots which emphasize the item itself rather than a narrative. Icons are typically outlined and monochromatic, blending seamlessly with the minimalist aesthetic. Imagery's role is primarily to showcase product details and functionality, acting as explanatory content rather than purely decorative.

## Layout

The page uses a maximum-width contained layout, though specific hero sections extend full-bleed. The hero pattern frequently employs a split-screen approach with a stark black background on one side (containing large, high-contrast serif headlines) and either white space or aspirational lifestyle photography on the other. Sections follow a consistent vertical spacing, often alternating between dark content blocks and light product grids. Content arrangement leans towards clear, centered headline stacks or alternating text-left/image-right compositions. Product display utilizes responsive card grids (e.g., 4-column) with ample padding between items. Navigation is a persistent top bar featuring a minimal logo, functional links, and a search input.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #1a211 (Forest Black)
- Background (Page): #ffffff (Cloud White)
- Background (Hero Dark): #000000 (Absolute Zero)
- CTA Button Background (Solid): #ffffff (Cloud White)
- Accent (Badge): #4e4e4 (Badge Gray)
- Border (Input/Divider): #cccfcd (Slate Border)

### 3-5 Example Component Prompts
1. **Create a Hero Section (Dark):** Use an Absolute Zero (#000000) background. Headline 'Kelp is here to make waves.' using Exposure-10 400, 80px, line-height 1.1, letter-spacing -2.0px, color Cloud White (#ffffff). Body copy 'Outdoor Backpacks and Slings...' in Geist 400, 16px, line-height 1.5, color Cloud White (#ffffff). Include two buttons: 'SHOP OUTDOOR' (Solid Standard Button, Cloud White background, Forest Black text, 4px radius, 12px vertical padding, 24px horizontal padding) and 'EXPLORE THE LINE' (Primary Ghost Button, transparent background, Forest Black text, Forest Black border, 0px radius, 0px vertical padding, 16px horizontal padding). Ensure ample vertical spacing (e.g., 24px between headline and body, 24px between body and buttons).
2. **Create a Product Grid:** Use a Cloud White (#ffffff) background. Display four Product Cards horizontally in a grid. Each card has an Absolute Zero (#000000) background, 8px radius, and 0px padding. Inside each card: an image section (no padding) followed by product text. For product text, use Geist 400, 16px, line-height 1.5, color Cloud White. Product names should be bryant 700, 16px, line-height 1.2, letter-spacing 0.61px, color Cloud White.
3. **Create a Search Input Field (Header):** Background Cloud White (#ffffff), text Forest Black (#1a211e), border Slate Border (#cccfcd) 1px, 4px border-radius, 2px vertical padding, 12px horizontal padding. Placeholder text 'Search for packing cubes' in Graphite (#606562). Font should be Geist 400, 14px, line-height 1.4.
4. **Create a 'New' Badge:** Background Badge Gray (#4e4e4e), text Cloud White (#ffffff), 9999px border-radius, 8px vertical padding, 16px horizontal padding. Font is bryant 700, 14px, line-height 1.0, letter-spacing 0.53px.
5. **Create a Neutral Filled Button:** Background Ash Gray (#eef1f0), text Forest Black (#1a211e), 4px border-radius, 8px vertical padding, 16px horizontal padding. Font is Geist 400, 16px, line-height 1.5.

## Similar Brands

- **Bellroy** — Shares a similar focus on high-quality product photography set against clean, minimalist layouts and a neutral color palette.
- **Fjallraven** — Employs robust, product-centric imagery and a functional, uncluttered interface to showcase durable goods, often with dark/light section contrasts.
- **Osprey Packs** — Uses a similar approach to presenting outdoor gear with large, impactful product shots framed by minimalist UI and strong typography for headlines.
- **Away (luggage)** — Features a direct, photography-driven e-commerce experience with a clean design, strong typography, and a limited, thoughtful color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-cloud-white: #ffffff;
  --color-forest-black: #1a211;
  --color-ash-gray: #eef1f0;
  --color-charcoal-black: #0c0c0c;
  --color-graphite: #606562;
  --color-slate-border: #cccfcd;
  --color-badge-gray: #4e4e4;
  --color-alert-red: #cc2e39;

  /* Typography — Font Families */
  --font-exposure-10: 'Exposure-10', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bryant: 'bryant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 21;
  --text-body-lg: 16px;
  --leading-body-lg: 24;
  --text-subheading: 24px;
  --leading-subheading: 26.4;
  --tracking-subheading: 0.91px;
  --text-heading: 32px;
  --leading-heading: 35.2;
  --tracking-heading: 1.22px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 44;
  --tracking-heading-lg: -0.8px;
  --text-display: 48px;
  --leading-display: 52.8;
  --tracking-display: -1px;
  --text-display-lg: 80px;
  --leading-display-lg: 88;
  --tracking-display-lg: -2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 0px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 32px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 9999px;
  --radius-inputs: 4px;
  --radius-buttons: 4px, 32px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-cloud-white: #ffffff;
  --color-forest-black: #1a211;
  --color-ash-gray: #eef1f0;
  --color-charcoal-black: #0c0c0c;
  --color-graphite: #606562;
  --color-slate-border: #cccfcd;
  --color-badge-gray: #4e4e4;
  --color-alert-red: #cc2e39;

  /* Typography */
  --font-exposure-10: 'Exposure-10', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bryant: 'bryant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 21;
  --text-body-lg: 16px;
  --leading-body-lg: 24;
  --text-subheading: 24px;
  --leading-subheading: 26.4;
  --tracking-subheading: 0.91px;
  --text-heading: 32px;
  --leading-heading: 35.2;
  --tracking-heading: 1.22px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 44;
  --tracking-heading-lg: -0.8px;
  --text-display: 48px;
  --leading-display: 52.8;
  --tracking-display: -1px;
  --text-display-lg: 80px;
  --leading-display-lg: 88;
  --tracking-display-lg: -2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 32px;
  --radius-full: 9999px;
}
```
