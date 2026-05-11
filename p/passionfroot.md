# Passionfroot — Style Reference
> Whimsical data observatory

**Theme:** light

Passionfroot embodies a light and energetic aesthetic, juxtaposing highly structured grids and data visualizations against whimsical, vibrant accent colors and playful 3D illustrations. The system balances professional clarity with an approachable, almost fantastical user experience. Surfaces are primarily crisp white, providing a clean canvas for sharp, purposeful typography and a spectrum of vivid hues that punctuate the interface with a soft, inviting pop.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#1d1d1c` | `--color-ink-black` | Primary text, critical UI elements, strong contrasts. Supports a data-rich environment |
| Canvas White | `#ffffff` | `--color-canvas-white` | Backgrounds for cards, modals, and primary UI surfaces. Provides a clean, bright foundation |
| Surface Frost | `#f8f7f2` | `--color-surface-frost` | Page background, subtle content divisions, light hover states. Creates a soft, almost imperceptible surface depth |
| Ash Gray | `#43423e` | `--color-ash-gray` | Secondary text, button borders, disabled states. A darker supporting neutral for hierarchy |
| Subtle Stone | `#d8d6ce` | `--color-subtle-stone` | Input borders, subtle dividers, ghost button borders. Provides minimal visual separation without distraction |
| Lilac Dream | `#b26bf5` | `--color-lilac-dream` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Cherry Blossom | `#f788d2` | `--color-cherry-blossom` | Decorative card backgrounds, playful highlights. Evokes a friendly, approachable mood |
| Sunset Orange | `#ff9147` | `--color-sunset-orange` | Decorative card backgrounds, accent in illustrations. A warm, energetic pop of color |
| Sky Teal | `#4ad5e8` | `--color-sky-teal` | Decorative card backgrounds, charts, and data visualization accents. Implies clarity and insight |
| Ocean Blue | `#51b1fb` | `--color-ocean-blue` | Decorative card backgrounds, data points. A classic choice for digital products, signifying reliability |
| Sunbeam Yellow | `#ffe747` | `--color-sunbeam-yellow` | Decorative card backgrounds, highlights for attention. Bright and optimistic |
| Velvet Violet | `#b977f8` | `--color-velvet-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Candy Red | `#ee5968` | `--color-candy-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Emerald Green | `#58df8c` | `--color-emerald-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Deep Sea Blue | `#2c91af` | `--color-deep-sea-blue` | Specialized links, icon accents in data visualizations, subtle borders. A more grounded, informational blue |
| Royal Purple | `#8200db` | `--color-royal-purple` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Soft Indigo | `#dab2ff` | `--color-soft-indigo` | Outline for ghost buttons, subtle interactive borders. Provides a softer visual cue than Royal Purple |
| Pale Lavender | `#f3e8ff` | `--color-pale-lavender` | Subtle button backgrounds, light-touch interactive fills. A very light, almost neutral accent |

## Tokens — Typography

### new-kansas — Headings, titles, and display text. Its distinct character adds a bespoke, editorial feel to key messages, differentiating them from standard UI text. · `--font-new-kansas`
- **Substitute:** Georgia or Libre Baskerville
- **Weights:** 400, 500
- **Sizes:** 16px, 20px, 28px, 48px, 64px
- **Line height:** 1.00, 1.20, 1.25, 1.35, 1.45, 1.50
- **Letter spacing:** -1.4px at 64px, -0.96px at 48px, -0.2px at 28px
- **OpenType features:** `"calt", "kern", "liga"`
- **Role:** Headings, titles, and display text. Its distinct character adds a bespoke, editorial feel to key messages, differentiating them from standard UI text.

### Nunito Sans — Body copy, button labels, navigation, and all functional interface text. Its clean, approachable geometry ensures high readability across diverse UI elements. · `--font-nunito-sans`
- **Substitute:** Open Sans or Lato
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.00, 1.25, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** -0.15px at 14px, -0.11px at 10px
- **OpenType features:** `"kern", "liga"`
- **Role:** Body copy, button labels, navigation, and all functional interface text. Its clean, approachable geometry ensures high readability across diverse UI elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.11px | `--text-caption` |
| body | 14px | 1.43 | -0.15px | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.35 | — | `--text-subheading` |
| heading | 28px | 1.25 | -0.2px | `--text-heading` |
| heading-lg | 48px | 1.2 | -0.96px | `--text-heading-lg` |
| display | 64px | 1 | -1.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 73 | 73px | `--spacing-73` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| large | 16px |
| default | 12px |
| extraLarge | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 /...` | `--shadow-subtle` |
| subtle-2 | `oklch(0.958 0.007 98) 0px 0px 0px 1px, oklch(0.23 0.002 9...` | `--shadow-subtle-2` |
| subtle-3 | `oklch(0.876 0.011 98) 0px 0px 0px 1px, oklch(0.23 0.002 9...` | `--shadow-subtle-3` |
| subtle-4 | `oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.2...` | `--shadow-subtle-4` |
| subtle-5 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 3px, rgba(255, 255, ...` | `--shadow-subtle-5` |
| subtle-6 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 3px` | `--shadow-subtle-6` |
| subtle-7 | `oklab(0.999994 0.0000455678 0.0000200868 / 0.07) 0px 0px ...` | `--shadow-subtle-7` |
| subtle-8 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px, rgba(255, 255, ...` | `--shadow-subtle-8` |

### Layout

- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to action, primary interaction.

Background: Canvas White (#ffffff), Text: Ink Black (#1d1d1c), Padding: 10px vertical, 16px horizontal, Radius: 12px. Uses a prominent shadow: rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px.

### Ghost Button (Header)
**Role:** Secondary actions in navigation.

Background: transparent, Text: Ash Gray (#43423e), Border: 1px solid Ash Gray (#43423e), Padding: 8px vertical, 12px horizontal, Radius: 8px. Transitions on hover.

### Text Button
**Role:** Tertiary actions, inline links within controls.

Background: transparent, Text: Ink Black (#1d1d1c), Padding: 10px vertical, 12px horizontal, Radius: 0px. Used for compact navigation or filter options.

### Pill Button
**Role:** Categorization, filters, small contextual actions.

Background: Pale Lavender (#f3e8ff), Text: Royal Purple (#8200db), Border: 1px solid Soft Indigo (#dab2ff), Padding: 4px vertical, 8px horizontal, Radius: 9999px.

### Feature Card (Achromatic)
**Role:** Content presentation, informational blocks.

Background: Canvas White (#ffffff), Radius: 10px, No box-shadow. Utilizes large internal padding, driven by content.

### Feature Card (Playful Color)
**Role:** Visually distinct content blocks, often for charts or vibrant data.

Background: Lilac Dream (#b26bf5), Cherry Blossom (#f788d2), Sunset Orange (#ff9147), Sky Teal (#4ad5e8), Ocean Blue (#51b1fb), Sunbeam Yellow (#ffe747), Candy Red (#ee5968), Emerald Green (#58df8c). Radius: 9999px for decorative elements within cards, 10px for the card itself. No box-shadow. Colors are used as full card backgrounds to create visual separation and appeal.

### Trust Bar Logo Card
**Role:** Showcasing partnerships or integrations.

Background: Surface Frost (#f8f7f2), Radius: 10px. Uses a soft shadow: oklch(0.958 0.007 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px.

### Input Field
**Role:** User input for forms and queries.

Background: Canvas White (#ffffff), Border: 1px solid Subtle Stone (#d8d6ce), Text: Ink Black (#1d1d1c), Placeholder: a slightly lighter gray. Radius: 12px (matches default). Focus state might involve a Royal Purple or Soft Indigo border.

### Navigation Link
**Role:** Top-level navigation items.

Text: Ink Black (#1d1d1c), Hover: Underline or slight background change. Padding: variable based on context but at least 10px horizontal and 5px vertical.

### Floating Action Buttons (Mini)
**Role:** Small, embedded contextual actions within components.

Background: Canvas White (#ffffff), Border: 1px solid Subtle Stone (#d8d6ce), Icon: Ash Gray (#43423e). Padding: 4px, Radius: 12px. Used for micro-interactions like adding new items.

## Do's and Don'ts

### Do
- Use new-kansas for all headings and large display text, ensuring its unique character anchors key messages.
- Prioritize Canvas White (#ffffff) as the primary surface color for all interactive components to maintain clarity and contrast.
- Employ the full palette of vibrant accent colors (Lilac Dream, Cherry Blossom, Sunset Orange, Sky Teal) as full card backgrounds or prominent data visualizations to create playful segmentation.
- Apply all shadows with the rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px stack for elevated UI elements.
- Maintain a default border-radius of 12px for most cards, buttons, and larger interface elements, reserving 9999px for pill-shaped elements.
- Utilize 8px as the default elementGap for tight-knit UI compositions, scaling up to 24px sectionGap for content separation.
- Use Nunito Sans with weights 400-700 and its specified letter spacing for all body copy and functional text to ensure readability.
- Align all page content to a max-width container, letting the hero stretch full-bleed as a visual anchor.
- Use Deep Sea Blue (#2c91af) and Royal Purple (#8200db) for interactive icon accents and highlighted text to guide user action.
- Employ Subtle Stone (#d8d6ce) for all hairline borders and input field outlines to maintain a light, unobtrusive visual structure.
- Incorporate Emerald Green (#58df8c) or Candy Red (#ee5968) as background fills for cards that convey semantic success or error states.

### Don't
- Avoid using purely decorative, highly saturated background gradients on general UI components; reserve color for solid blocks and purposeful data visualization.
- Do not deviate from the specified Nunito Sans and new-kansas font families; do not introduce additional typefaces.
- Do not use dark backgrounds for primary content areas; the system is designed around a light-themed canvas.
- Refrain from using hard, angular corners; all components should adopt the characteristic 12px or 9999px border radii.
- Do not introduce heavy, opaque drop shadows; stick to the light, multi-layered shadows specified for subtle elevation.
- Avoid arbitrary color usage; every use of a chromatic color should have a clear purpose—either decorative accent, semantic indicator, or data visualization.
- Do not implement excessively sparse layouts. The system favors a compact density with intentional spacing for clarity, not emptiness.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Background | `#f8f7f2` | The foundational canvas for the entire page, providing a subtle off-white base. |
| 2 | Primary Card Surface | `#ffffff` | Used for most interactive cards, buttons, and content blocks, offering a crisp, clean background. |
| 3 | Elevated Component Surface | `#f3e8ff` | A very light, almost white accent surface primarily seen on pill-shaped buttons and subtle interactive elements. |

## Elevation

- **Button:** `rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px`
- **Card (Trust Bar):** `oklch(0.958 0.007 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px`
- **Hero Buttons/Cards:** `oklch(0.876 0.011 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px, oklch(0.23 0.002 98 / 0.02) 0px 24px 24px -12px`

## Imagery

This design system heavily features playful, soft 3D illustrations, often personified characters, set against dreamy, fantastical backgrounds (like cloudscapes or starry skies). These illustrations are the primary visual content, serving a decorative and atmospheric role rather than showcasing product features directly. They are full-width or large hero elements, not contained by card borders, and feature soft, rounded forms. Iconography is minimalist and linear, complementing the clean UI without competing with the vivid illustrations. The imagery creates a sense of wonder and accessibility, making complex AI concepts feel approachable.

## Layout

The page model alternates between full-bleed, content-rich hero sections and max-width contained sections. The hero showcases expansive, illustrative backgrounds with centered headlines and calls to action. Subsequent sections often use a consistent vertical rhythm of 24px, with content arranged in alternating text-left/image-right or centered stacked patterns. Card grids are prominent for feature display, making frequent use of the 8px element gap for compact arrangements. Navigation is a sticky top bar, minimally styled with text links and a ghost button, staying out of the way of the content.

## Agent Prompt Guide

### Quick Color Reference
- text: Ink Black (#1d1d1c)
- background: Surface Frost (#f8f7f2)
- border: Subtle Stone (#d8d6ce)
- accent: Lilac Dream (#b26bf5)
- primary action: #43423e (filled action)

### 3-5 Example Component Prompts
- Create a Primary Action Button: #43423e background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

- Create a Trust Bar: Surface Frost (#f8f7f2) background, 24px vertical padding. Display a grid of 6 brand logos, each centered within a Trust Bar Logo Card. Cards have Canvas White (#ffffff) background, 10px radius, and the Trust Bar card shadow.

- Create a Question Input Card: Canvas White (#ffffff) background, 8px radius. The card contains a text input field with a 1px solid Subtle Stone (#d8d6ce) border and 12px radius. To the right of the input, a small Floating Action Button with Canvas White (#ffffff) background, 1px solid Subtle Stone (#d8d6ce) border, 4px padding, and 12px radius, containing an Ash Gray (#43423e) icon. Below the input, a row of three Pill Buttons: 'Plan strategy', 'Run campaign', 'Measure results'. Each pill button has Pale Lavender (#f3e8ff) background, Royal Purple (#8200db) text, 1px solid Soft Indigo (#dab2ff) border, 4px vertical 8px horizontal padding, and 9999px radius.

## Similar Brands

- **Airtable** — Combines playful, colorful accents and illustrations with a highly structured, data-driven UI on a light background.
- **Webflow** — Features a crisp, white-canvas aesthetic with prominent typography and a focus on clean modular components, similar to Passionfroot's structured hero.
- **Notion** — Balances a clean, minimalist UI with strategic use of color for functional elements like tags and highlights, avoiding overly busy visual metaphors.
- **Linear** — Employs an extremely clean, function-first interface where visual lightness and subtle elevation are key, using light neutrals and minimal color for interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #1d1d1c;
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f8f7f2;
  --color-ash-gray: #43423e;
  --color-subtle-stone: #d8d6ce;
  --color-lilac-dream: #b26bf5;
  --color-cherry-blossom: #f788d2;
  --color-sunset-orange: #ff9147;
  --color-sky-teal: #4ad5e8;
  --color-ocean-blue: #51b1fb;
  --color-sunbeam-yellow: #ffe747;
  --color-velvet-violet: #b977f8;
  --color-candy-red: #ee5968;
  --color-emerald-green: #58df8c;
  --color-deep-sea-blue: #2c91af;
  --color-royal-purple: #8200db;
  --color-soft-indigo: #dab2ff;
  --color-pale-lavender: #f3e8ff;

  /* Typography — Font Families */
  --font-new-kansas: 'new-kansas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans: 'Nunito Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.15px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.2px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-large: 16px;
  --radius-default: 12px;
  --radius-extralarge: 24px;

  /* Shadows */
  --shadow-subtle: rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px;
  --shadow-subtle-2: oklch(0.958 0.007 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px;
  --shadow-subtle-3: oklch(0.876 0.011 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px, oklch(0.23 0.002 98 / 0.02) 0px 24px 24px -12px;
  --shadow-subtle-4: oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px;
  --shadow-subtle-5: rgba(255, 255, 255, 0.2) 0px 0px 0px 3px, rgba(255, 255, 255, 0.3) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.2) 0px 0px 0px 3px;
  --shadow-subtle-7: oklab(0.999994 0.0000455678 0.0000200868 / 0.07) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.04) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 8px 0px;
  --shadow-subtle-8: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.12) 0px 2px 6px 0px;

  /* Surfaces */
  --surface-page-background: #f8f7f2;
  --surface-primary-card-surface: #ffffff;
  --surface-elevated-component-surface: #f3e8ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #1d1d1c;
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f8f7f2;
  --color-ash-gray: #43423e;
  --color-subtle-stone: #d8d6ce;
  --color-lilac-dream: #b26bf5;
  --color-cherry-blossom: #f788d2;
  --color-sunset-orange: #ff9147;
  --color-sky-teal: #4ad5e8;
  --color-ocean-blue: #51b1fb;
  --color-sunbeam-yellow: #ffe747;
  --color-velvet-violet: #b977f8;
  --color-candy-red: #ee5968;
  --color-emerald-green: #58df8c;
  --color-deep-sea-blue: #2c91af;
  --color-royal-purple: #8200db;
  --color-soft-indigo: #dab2ff;
  --color-pale-lavender: #f3e8ff;

  /* Typography */
  --font-new-kansas: 'new-kansas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans: 'Nunito Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.15px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.2px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(237, 234, 228) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px;
  --shadow-subtle-2: oklch(0.958 0.007 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px;
  --shadow-subtle-3: oklch(0.876 0.011 98) 0px 0px 0px 1px, oklch(0.23 0.002 98 / 0.04) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.04) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.04) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.02) 0px 12px 12px -6px, oklch(0.23 0.002 98 / 0.02) 0px 24px 24px -12px;
  --shadow-subtle-4: oklch(0.23 0.002 98 / 0.02) 0px 1px 1px -0.5px, oklch(0.23 0.002 98 / 0.02) 0px 3px 3px -1.5px, oklch(0.23 0.002 98 / 0.02) 0px 6px 6px -3px, oklch(0.23 0.002 98 / 0.00999999) 0px 12px 12px -6px;
  --shadow-subtle-5: rgba(255, 255, 255, 0.2) 0px 0px 0px 3px, rgba(255, 255, 255, 0.3) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.2) 0px 0px 0px 3px;
  --shadow-subtle-7: oklab(0.999994 0.0000455678 0.0000200868 / 0.07) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.04) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 8px 0px;
  --shadow-subtle-8: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.12) 0px 2px 6px 0px;
}
```
