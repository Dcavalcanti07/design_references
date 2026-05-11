# Awesomic — Style Reference
> white canvas, bold monochrome

**Theme:** light

Awesomic presents a crisp, modern aesthetic on a clean white canvas. It leverages high-contrast typography for impactful statements and a sophisticated palette of achromatic neutrals. Color is used sparingly, primarily as a vivid accent for critical content highlights and functional indicators. Components feature distinctive large radii, suggesting a friendly yet refined digital experience, with subtle shadows adding depth without overt skeuomorphism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#09090b` | `--color-midnight-ink` | Primary text, prominent headings, solid interactive buttons – a deep near-black that grounds content |
| Graphite | `#3f3f46` | `--color-graphite` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Steel Gray | `#71717a` | `--color-steel-gray` | Iconography and subtle decorative accents |
| Silver Mist | `#a1a1aa` | `--color-silver-mist` | Helper text, subtle borders, and placeholder text |
| Faded Gray | `#d4d4d8` | `--color-faded-gray` | Light borders and dividers for nuanced content separation |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, and text on dark backgrounds |
| Canvas White | `#f4f4f5` | `--color-canvas-white` | Subtle background for UI elements, sections, and input fields |
| Whisper Gray | `#ececee` | `--color-whisper-gray` | Surface backgrounds for cards and sections, providing a slight elevation from the main canvas |
| Jet Black | `#18181b` | `--color-jet-black` | Text on white backgrounds where high contrast is needed, and icon fills |
| Deep Gray | `#222222` | `--color-deep-gray` | Link colors and certain text elements for a slightly softer contrast than Midnight Ink |
| Vibrant Magenta | `#fe45e2` | `--color-vibrant-magenta` | Accent for highlighting key information within cards, decorative flourishes |
| Ember Glow | `#ff5a00` | `--color-ember-glow` | Orange state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |

## Tokens — Typography

### Cosmica — The sole typeface for all content, from headings to body text and UI elements. Its confident weights and varied sizes establish hierarchy without needing multiple typefaces. The consistent use of a single font family provides a unified and predictable content experience. · `--font-cosmica`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 32px, 40px, 56px, 64px
- **Line height:** 1.00, 1.12, 1.25, 1.28, 1.31, 1.35, 1.45, 1.48, 1.50, 1.55, 1.56, 1.62, 1.64, 1.68, 1.80
- **Letter spacing:** normal
- **Role:** The sole typeface for all content, from headings to body text and UI elements. Its confident weights and varied sizes establish hierarchy without needing multiple typefaces. The consistent use of a single font family provides a unified and predictable content experience.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.56 | — | `--text-body` |
| body-lg | 16px | 1.62 | — | `--text-body-lg` |
| subheading | 18px | 1.64 | — | `--text-subheading` |
| heading | 32px | 1.28 | — | `--text-heading` |
| heading-lg | 40px | 1.25 | — | `--text-heading-lg` |
| display-sm | 56px | 1.12 | — | `--text-display-sm` |
| display | 64px | 1 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 36px |
| badges | 12px |
| inputs | 12px |
| buttons | 12px |
| imageMasks | 48px |
| navigation | 12px |
| smallerCards | 28px |
| largeElements | 64px |
| iconContainers | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.5) 0px 0.5px 0px 0px inset, rgba(11...` | `--shadow-subtle` |
| subtle-2 | `rgb(228, 228, 231) 0px 1px 0px 0px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(255, 255, 255) 0px 0.5px 0px 0px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgb(255, 255, 255) 0px -0.5px 0px 0px` | `--shadow-subtle-4` |
| subtle-5 | `rgb(228, 228, 231) 0px -1px 0px 0px` | `--shadow-subtle-5` |
| md | `rgba(0, 0, 0, 0.04) 0px 4px 12px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 40px
- **Card padding:** 28px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Low-prominence action button for navigation or secondary actions

White background, Graphite text and border (#3f3f46). Padding 20px on all sides, 36px radius. Text uses Cosmica, weight 400.

### Primary Filled Button
**Role:** High-prominence call to action

Midnight Ink background (#09090b), Cloud White text (#ffffff). Padding 14px vertical, 18px horizontal (smaller variant), or 12px vertical, 16px horizontal (larger variant). Radius 16px or 14px. Text uses Cosmica, weight 400.

### Secondary Ghost Button
**Role:** Minimalist button for filtering or tagging

Transparent background, Jet Black text (#18181b), 12px radius. Padding 4px vertical, 8px horizontal. No border.

### Filled Brand Card
**Role:** Content card with prominent background

Canvas White background (#f4f4f5), 36px border radius. Padding varies from 28px top to 32px bottom.

### Elevated Subtle Card
**Role:** Content card with slight background distinction

Whisper Gray background (#ececee), 28px border radius. Uniform 24px padding. No shadow.

### Default Input Field
**Role:** Standard user input field

Cloud White background (#ffffff), Faded Gray border on focus, 14px radius. Placeholder text is Steel Gray. Padding 12px vertical, 16px left, 12px right.

### Dark Themed Badge
**Role:** Categorization tag for dark backgrounds

Transparent background, Cloud White text (#ffffff), 12px radius. Padding 4px vertical, 8px horizontal.

### Accent Status Badge (Ember Glow)
**Role:** Highlighting status or key attributes with urgency

Ember Glow background (#ff5a00), Cloud White text (#ffffff), 12px radius. Padding 4px vertical, 8px horizontal.

## Do's and Don'ts

### Do
- Use Cosmica with explicit weights for all text elements; do not use system fonts.
- Pair high-contrast text colors like Midnight Ink (#09090b) or Jet Black (#18181b) for primary content and navigation against Cloud White (#ffffff) or Canvas White (#f4f4f5) backgrounds.
- Apply significantly rounded corners (e.g., 36px for cards, 12px for buttons/inputs) to all contained elements for a consistent soft aesthetic.
- Reserve vibrant accent colors like Vibrant Magenta (#fe45e2) and Ember Glow (#ff5a00) for highly specific, functional highlights or decorative touches, not general UI elements.
- Structure sections with clear vertical rhythm using a base unit of 8px, particularly for element gaps, building up to section gaps of 40px.
- Maintain a clean, achromatic background palette using Cloud White (#ffffff), Canvas White (#f4f4f5), and Whisper Gray (#ececee) for distinct surface levels.
- Employ the outlined/ghost button style for secondary actions, using Graphite (#3f3f46) for text and border against a white background.

### Don't
- Avoid introducing additional saturated colors beyond Vibrant Magenta and Ember Glow; the palette is intentionally restrained.
- Do not use subtle shadows for elevation on cards or sections; the design relies on background color shifts and large radii for visual distinction.
- Refrain from using multiple font families or decorative typography; stick to the Cosmica family for all textual content.
- Do not use dark backgrounds for full sections; the theme is predominantly light with dark elements contained within white or light gray surfaces.
- Avoid small, tight radii; larger radii are a defining characteristic of the brand's friendliness.
- Do not vary line-height unless explicitly defined in the type scale data; maintain tight leading for headings and comfortable values for body text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud White Canvas | `#ffffff` | Primary page background, base layer. |
| 1 | Canvas White Panel | `#f4f4f5` | Secondary background for sections, a subtle shift from the base canvas. |
| 2 | Whisper Gray Card | `#ececee` | Background for elevated content cards, providing a distinct, but soft, separation. |

## Elevation

- **Interactive Button:** `rgba(255, 255, 255, 0.5) 0px 0.5px 0px 0px inset, rgba(117, 123, 133, 0.4) 0px 9px 14px -5px inset, rgb(44, 46, 52) 0px 0px 0px 1.5px, rgba(0, 0, 0, 0.14) 0px 4px 6px 0px`
- **Card/Link subtly elevated:** `rgb(228, 228, 231) 0px 1px 0px 0px inset`

## Imagery

Imagery largely consists of tight product crops, abstract visual representations of data/movement, and focused portrait photography. Product screenshots are typically presented without full-bleed backgrounds. Illustrations are flat, filled, and often abstract. Icons are primarily outlined or subtle fills, maintaining a minimalist aesthetic. Photography (e.g., team members) is staged and professional, with a mostly neutral color treatment, sometimes in circular masks. The overall density is balanced, allowing prominent typography to take center stage while visuals support messaging.

## Layout

The page primarily uses a max-width contained layout, allowing for crisp edges against the white canvas. The hero section often features a large, impactful headline with associated descriptive text and a call to action. Section rhythm is driven by alternating white and light gray (Canvas White) backgrounds, creating a subtle visual break. Content is generally arranged in two-column layouts, often with text on one side and a supporting visual on the other, or feature grids composed of cards with significant corner radii. The navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

Quick Color Reference:
text: #09090b
background: #ffffff
border: #3f3f46
accent: #fe45e2
primary action: #09090b (filled action)

Example Component Prompts:
Create a Primary Action Button: #09090b background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a feature card: Whisper Gray background (#ececee), 28px radius, uniform 24px padding. Headline uses Cosmica 32px weight 500 #09090b, body text uses Cosmica 16px weight 400 #3f3f46.
Create a content card with accent: Cloud White background (#ffffff), 36px radius. Contains a small square with Vibrant Magenta (#fe45e2) background for decorative highlighting. Text uses Cosmica 14px weight 400 #3f3f46.

## Similar Brands

- **Figma** — Shares a clean, white-space dominant UI with a focus on high-contrast text and minimal use of saturated brand colors.
- **Linear** — Exhibits a similar compact information density, sharp typographic hierarchy, and a restrained color palette primarily leveraging neutrals.
- **Superhuman** — Features a powerful typography-driven interface on a light background, prioritizing function over decorative elements, with subtle use of color for status and interactive cues.
- **Stripe** — Employs an elegant and spacious layout with a consistent use of large border radii on cards and buttons, paired with a sophisticated, mostly achromatic color scheme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #09090b;
  --color-graphite: #3f3f46;
  --color-steel-gray: #71717a;
  --color-silver-mist: #a1a1aa;
  --color-faded-gray: #d4d4d8;
  --color-cloud-white: #ffffff;
  --color-canvas-white: #f4f4f5;
  --color-whisper-gray: #ececee;
  --color-jet-black: #18181b;
  --color-deep-gray: #222222;
  --color-vibrant-magenta: #fe45e2;
  --color-ember-glow: #ff5a00;

  /* Typography — Font Families */
  --font-cosmica: 'Cosmica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.56;
  --text-body-lg: 16px;
  --leading-body-lg: 1.62;
  --text-subheading: 18px;
  --leading-subheading: 1.64;
  --text-heading: 32px;
  --leading-heading: 1.28;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 56px;
  --leading-display-sm: 1.12;
  --text-display: 64px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 28px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 56px;
  --radius-full-3: 64px;
  --radius-full-4: 80px;
  --radius-full-5: 1000px;
  --radius-full-6: 10000px;

  /* Named Radii */
  --radius-cards: 36px;
  --radius-badges: 12px;
  --radius-inputs: 12px;
  --radius-buttons: 12px;
  --radius-imagemasks: 48px;
  --radius-navigation: 12px;
  --radius-smallercards: 28px;
  --radius-largeelements: 64px;
  --radius-iconcontainers: 40px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.5) 0px 0.5px 0px 0px inset, rgba(117, 123, 133, 0.4) 0px 9px 14px -5px inset, rgb(44, 46, 52) 0px 0px 0px 1.5px, rgba(0, 0, 0, 0.14) 0px 4px 6px 0px;
  --shadow-subtle-2: rgb(228, 228, 231) 0px 1px 0px 0px inset;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0.5px 0px 0px inset;
  --shadow-subtle-4: rgb(255, 255, 255) 0px -0.5px 0px 0px;
  --shadow-subtle-5: rgb(228, 228, 231) 0px -1px 0px 0px;
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 4px 12px 0px;

  /* Surfaces */
  --surface-cloud-white-canvas: #ffffff;
  --surface-canvas-white-panel: #f4f4f5;
  --surface-whisper-gray-card: #ececee;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #09090b;
  --color-graphite: #3f3f46;
  --color-steel-gray: #71717a;
  --color-silver-mist: #a1a1aa;
  --color-faded-gray: #d4d4d8;
  --color-cloud-white: #ffffff;
  --color-canvas-white: #f4f4f5;
  --color-whisper-gray: #ececee;
  --color-jet-black: #18181b;
  --color-deep-gray: #222222;
  --color-vibrant-magenta: #fe45e2;
  --color-ember-glow: #ff5a00;

  /* Typography */
  --font-cosmica: 'Cosmica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.56;
  --text-body-lg: 16px;
  --leading-body-lg: 1.62;
  --text-subheading: 18px;
  --leading-subheading: 1.64;
  --text-heading: 32px;
  --leading-heading: 1.28;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 56px;
  --leading-display-sm: 1.12;
  --text-display: 64px;
  --leading-display: 1;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 56px;
  --radius-full-3: 64px;
  --radius-full-4: 80px;
  --radius-full-5: 1000px;
  --radius-full-6: 10000px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.5) 0px 0.5px 0px 0px inset, rgba(117, 123, 133, 0.4) 0px 9px 14px -5px inset, rgb(44, 46, 52) 0px 0px 0px 1.5px, rgba(0, 0, 0, 0.14) 0px 4px 6px 0px;
  --shadow-subtle-2: rgb(228, 228, 231) 0px 1px 0px 0px inset;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0.5px 0px 0px inset;
  --shadow-subtle-4: rgb(255, 255, 255) 0px -0.5px 0px 0px;
  --shadow-subtle-5: rgb(228, 228, 231) 0px -1px 0px 0px;
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 4px 12px 0px;
}
```
