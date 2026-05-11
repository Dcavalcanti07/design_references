# Aevi Wellness — Style Reference
> Nordic calm on white canvas

**Theme:** light

Aevi Wellness projects a serene, minimalist aesthetic with a dominant cool blue and white palette. Typography is light and sparse, allowing product imagery and ample negative space to define the visual experience. Functional elements, like buttons and borders, employ a muted blue, creating a gentle yet distinct call to action without harsh contrasts. The overall impression is one of calm efficacy, emphasizing purity and natural simplicity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page backgrounds, unselected card surfaces, light text on dark backgrounds |
| Charcoal Text | `#231f20` | `--color-charcoal-text` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Sky Mist | `#d5e0ea` | `--color-sky-mist` | Secondary background for sections, ghost button fills, and unselected borders. Creates subtle separation |
| Midnight Ink | `#000000` | `--color-midnight-ink` | High-contrast text, borders, and icon fills, used sparingly for emphasis |
| Nordic Blue | `#a3bfdb` | `--color-nordic-blue` | Primary action button backgrounds, accent elements in banners. A muted blue that signifies interaction |
| Deep Sea Violet | `#134fc2` | `--color-deep-sea-violet` | Violet outline accent for tags, dividers, and focused UI edges |

## Tokens — Typography

### Primary Font — Primary Font — detected in extracted data but not described by AI · `--font-primary-font`
- **Weights:** 300
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 1.29, 1.3, 1.31, 1.33
- **Role:** Primary Font — detected in extracted data but not described by AI

### Custom Font 1 — Primary font for body text, form inputs, and general interface elements. The light weight maintains the brand's delicate aesthetic. · `--font-custom-font-1`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 1.29, 1.30, 1.31, 1.33
- **Letter spacing:** normal
- **Role:** Primary font for body text, form inputs, and general interface elements. The light weight maintains the brand's delicate aesthetic.

### Custom Font 2 — Used for emphasized body text and card titles, providing a slight increase in visual weight for hierarchy. · `--font-custom-font-2`
- **Substitute:** Open Sans
- **Weights:** 
- **Sizes:** 14px
- **Line height:** 1.29
- **Letter spacing:** normal
- **Role:** Used for emphasized body text and card titles, providing a slight increase in visual weight for hierarchy.

### Custom Font 3 — Specifically for buttons and strong calls to action, ensuring clarity and impact despite the generally light typography. The varied line height suggests adaptability for different button contexts. · `--font-custom-font-3`
- **Substitute:** Montserrat
- **Weights:** 
- **Sizes:** 14px
- **Line height:** 1.21, 2.71
- **Letter spacing:** normal
- **Role:** Specifically for buttons and strong calls to action, ensuring clarity and impact despite the generally light typography. The varied line height suggests adaptability for different button contexts.

### Custom Font 4 — Heading font. Its thin weight against larger sizes creates an airy, elegant feel rather than overt dominance, characteristic of luxury branding. · `--font-custom-font-4`
- **Substitute:** Playfair Display
- **Weights:** 
- **Sizes:** 24px, 28px, 36px, 42px, 54px
- **Line height:** 1.08, 1.09, 1.10, 1.11
- **Letter spacing:** normal
- **Role:** Heading font. Its thin weight against larger sizes creates an airy, elegant feel rather than overt dominance, characteristic of luxury branding.

### Tertiary Font — Tertiary Font — detected in extracted data but not described by AI · `--font-tertiary-font`
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.29
- **Role:** Tertiary Font — detected in extracted data but not described by AI

### Button Font — Button Font — detected in extracted data but not described by AI · `--font-button-font`
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.21, 2.71
- **Role:** Button Font — detected in extracted data but not described by AI

### Heading Font — Heading Font — detected in extracted data but not described by AI · `--font-heading-font`
- **Weights:** 300
- **Sizes:** 24px, 28px, 36px, 42px, 54px
- **Line height:** 1.08, 1.09, 1.1, 1.11
- **Role:** Heading Font — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.29 | — | `--text-caption` |
| body | 14px | 1.29 | — | `--text-body` |
| heading-sm | 24px | 1.08 | — | `--text-heading-sm` |
| heading | 36px | 1.09 | — | `--text-heading` |
| heading-lg | 42px | 1.1 | — | `--text-heading-lg` |
| display | 54px | 1.11 | — | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 2px |
| cards | 0px |
| inputs | 0px |
| buttons | 60px |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to action button

Filled with Nordic Blue (#a3bfdb), text in Charcoal Text (#231f20), with a generous 60px border radius for a soft, pill-like appearance. Padding is 0px top/bottom and 24px left/right, text vertically centered via line-height.

### Ghost Button
**Role:** Secondary action or subtle navigation

Transparent background, text in Charcoal Text (#231f20). Bordered by Sky Mist (#d5e0ea) with a sharp 2px radius and no internal padding, suggesting a minimal interactive element.

### Subtle Ghost Button
**Role:** Tertiary action or inline link within content

Transparent background, text in Charcoal Text (#231f20), with no border or explicit radius. Padding is 0px. Used for subtle prompts like 'DISCOVER AEVI SKINCARE'.

### White Background Card
**Role:** Product display card

Background of Canvas White (#ffffff), no border or shadow, sharp 0px radius. Internal padding of 16px right/left and 8px top/bottom.

### Invisible Card
**Role:** Layout container for content

Fully transparent background, no border, no shadow, 0px radius. Primarily used for organizing content without visual boundaries.

### Input Field
**Role:** Form input element

Transparent background with Charcoal Text (#231f20) for input value and border. Features 0px border radius and 8px top/bottom padding for a clean, understated look.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the dominant background; use Sky Mist (#d5e0ea) for secondary sections to create subtle depth.
- Apply 60px border radius to all primary interactive elements like buttons for a consistent soft, pill-shaped aesthetic.
- Use Charcoal Text (#231f20) for main body copy and Charcoal Text (#231f20) for headings to maintain a unified dark text color.
- Employ Nordic Blue (#a3bfdb) exclusively for primary action backgrounds, linking this specific color directly to user interaction.
- Maintain the light aesthetic for headings (Custom Font 4, weight 300) even at large sizes to convey understated luxury.
- Ensure all cards use a 0px border radius, contrasting with the soft buttons and maintaining a clean, structured content presentation.

### Don't
- Avoid using saturated or vivid colors for large background areas; maintain a light and muted color scheme.
- Do not introduce heavy shadows or overt elevation effects; rely on color shifts (Canvas White, Sky Mist) for perceived depth.
- Do not use highly decorative fonts for body text or labels; stick to the specified Custom Font 1 for clarity and minimalist appeal.
- Do not vary border radius on buttons; always use 60px for pill-shaped elements and 2px or 0px for other smaller interactive elements like tags.
- Avoid dense blocks of text; apply ample element and section spacing to support the airy, minimalist aesthetic.
- Do not use dark backgrounds for primary content areas; the brand identity is built on a predominantly light theme.

## Imagery

Imagery features high-key, bright product photography and lifestyle shots. Products are often shown in clean, natural settings or in close-up against white. Photography tends to be soft-focused with natural lighting, or tight crops of bottles, emphasizing the product itself. Illustrations are largely absent, favoring realism and product-focused visuals. Icons, when present, are simple, outlined, and monochromatic, maintaining a light stroke weight. The role of imagery is primarily product showcase and aspirational atmosphere, providing visual breaks in content.

## Layout

The page primarily uses a full-bleed layout for hero sections, transitioning to a max-width contained layout for content blocks, implicitly centered. The hero often features a large image with an overlaying, centered brand name and a call to action. Section rhythm is created through alternating pastel blue (Sky Mist) and white backgrounds, defining distinct content areas. Content arrangement varies, including alternating text-left/image-right patterns and centered stacked elements. Responsive column grids are used for product displays and feature highlights. The layout maintains a spacious feel with generous vertical padding between sections, contributing to an uncluttered aesthetic. Navigation is likely a sticky top navigation, given the general e-commerce pattern and visual header elements.

## Agent Prompt Guide

Quick Color Reference: 
text: #231f20
background: #ffffff
border: #231f20
accent: #134fc2
primary action: #a3bfdb (filled action)

Example Component Prompts:
Create a Primary Action Button: #a3bfdb background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a product card: Canvas White (#ffffff) background, 0px radius, 16px cardPadding. Product title in Custom Font 2 at 14px, weight 500, color #231f20. Pricing in Custom Font 1 at 14px, weight 300, color #231f20.
Create a banner section: Sky Mist (#d5e0ea) background. Centered text 'Dermatologist-tested skincare for sensitive skin—powered by Nordic botanicals' in Custom Font 1 at 16px, weight 300, color #231f20.
Create an input field: transparent background, border #231f20, 0px radius, 8px padding. Placeholder text in Custom Font 1 at 14px, weight 300, color #231f20.

## Similar Brands

- **Glossier** — Shares a clean, minimalist aesthetic with an emphasis on soft colors, significant negative space, and large product photography.
- **Aesop** — Similar approach to understated luxury via sparse typography, muted color palettes, and a focus on product presentation rather than bold graphics.
- **Byredo** — Employs elegant, thin typography and a very clean, often monochromatic visual style to communicate sophistication and purity.
- **Skincare brands like Drunk Elephant** — Utilizes prominent product photography, clean white backgrounds, and a focus on natural ingredients, but Aevi uses a softer, more muted color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-text: #231f20;
  --color-sky-mist: #d5e0ea;
  --color-midnight-ink: #000000;
  --color-nordic-blue: #a3bfdb;
  --color-deep-sea-violet: #134fc2;

  /* Typography — Font Families */
  --font-primary-font: 'Primary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-1: 'Custom Font 1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-2: 'Custom Font 2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-3: 'Custom Font 3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-4: 'Custom Font 4', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tertiary-font: 'Tertiary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-button-font: 'Button Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-heading-font: 'Heading Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.29;
  --text-body: 14px;
  --leading-body: 1.29;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.08;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --text-display: 54px;
  --leading-display: 1.11;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-tags: 2px;
  --radius-cards: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 60px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-text: #231f20;
  --color-sky-mist: #d5e0ea;
  --color-midnight-ink: #000000;
  --color-nordic-blue: #a3bfdb;
  --color-deep-sea-violet: #134fc2;

  /* Typography */
  --font-primary-font: 'Primary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-1: 'Custom Font 1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-2: 'Custom Font 2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-3: 'Custom Font 3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom-font-4: 'Custom Font 4', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tertiary-font: 'Tertiary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-button-font: 'Button Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-heading-font: 'Heading Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.29;
  --text-body: 14px;
  --leading-body: 1.29;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.08;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --text-display: 54px;
  --leading-display: 1.11;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 60px;
}
```
