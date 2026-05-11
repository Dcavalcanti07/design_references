# Blok — Style Reference
> energetic timepiece on a clean canvas

**Theme:** light

Blok's design system uses a bright, energetic palette grounded in high-contrast monochromes. A vivid teal accent color provides functional punctuation for primary actions, while secondary interaction is highlighted with a striking blue. Typography is confident and direct, predominantly sans-serif, establishing clear hierarchy. Components are lightweight with minimal use of shadows, favoring crisp borders and rounded edges for interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0a0d0f` | `--color-midnight-ink` | Primary text, deep section backgrounds, primary borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, surface fills, inverse text on dark backgrounds |
| Charcoal Haze | `#2e3438` | `--color-charcoal-haze` | Secondary text, subtle borders, muted icons, footer text |
| Pure Black | `#000000` | `--color-pure-black` | High-contrast text, strong borders |
| Whisper Gray | `#f7f7f7` | `--color-whisper-gray` | Subtle background accents, secondary section backgrounds |
| Footer Gray | `#efefef` | `--color-footer-gray` | Footer background |
| Border Ash | `#d5d6d7` | `--color-border-ash` | Input borders, subtle dividers |
| Muted Stone | `#656565` | `--color-muted-stone` | Badge text, muted informational text |
| Aqua Thrill | `#1dd8e1` | `--color-aqua-thrill` | Primary action buttons, interactive highlights, brand accent color |
| Electric Blue | `#2c75d4` | `--color-electric-blue` | Secondary brand accent, distinctive component backgrounds |

## Tokens — Typography

### Poppins — General body text, links, and various UI elements. Poppins at 17px weight 400 with a line height of 1.5 offers clear readability for longer passages. · `--font-poppins`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 17px, 21px, 24px, 25px
- **Line height:** 1.38, 1.42, 1.50
- **Letter spacing:** normal
- **Role:** General body text, links, and various UI elements. Poppins at 17px weight 400 with a line height of 1.5 offers clear readability for longer passages.

### Cabin — Used for headings and prominent labels, Cabin provides a confident, slightly condensed feel with distinct letter spacing for emphasis, especially at larger sizes like 68px. · `--font-cabin`
- **Substitute:** sans-serif
- **Weights:** 500, 600
- **Sizes:** 12px, 14px, 17px, 20px, 21px, 68px
- **Line height:** 1.00, 1.20, 1.25, 1.50, 1.63
- **Letter spacing:** 0.0640em at 21px, 0.0900em at 68px and 20px
- **Role:** Used for headings and prominent labels, Cabin provides a confident, slightly condensed feel with distinct letter spacing for emphasis, especially at larger sizes like 68px.

### Jost — Employed for impactful headlines, Jost at weight 700 with wide letter spacing creates a strong, editorial presence, making headings visually distinctive. · `--font-jost`
- **Substitute:** sans-serif
- **Weights:** 700
- **Sizes:** 23px, 34px, 42px, 51px
- **Line height:** 1.25, 1.37, 1.38
- **Letter spacing:** 0.0900em
- **Role:** Employed for impactful headlines, Jost at weight 700 with wide letter spacing creates a strong, editorial presence, making headings visually distinctive.

### GTStandard-M — A subtle brand-specific font used for a niche set of page elements, maintaining legibility at a standard body text size. · `--font-gtstandard-m`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 17px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** A subtle brand-specific font used for a niche set of page elements, maintaining legibility at a standard body text size.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.09px | `--text-caption` |
| body-sm | 14px | 1.38 | — | `--text-body-sm` |
| body-lg | 17px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.25 | 0.09px | `--text-subheading` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 42px | 1.37 | 0.09px | `--text-heading-lg` |
| display | 68px | 1 | 0.09px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 50 | 50px | `--spacing-50` |
| 72 | 72px | `--spacing-72` |
| 113 | 113px | `--spacing-113` |
| 166 | 166px | `--spacing-166` |

### Border Radius

| Element | Value |
|---------|-------|
| input | 3px |
| buttons | 100px |
| default | 3px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 50px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Solid Aqua Button
**Role:** Primary Call to Action

Filled button with 'Aqua Thrill' background and 'Midnight Ink' text. Uses a 0px border-radius and generous horizontal padding, 12px vertical and 24px horizontal, for prominent action.

### Pill Ghost Button
**Role:** Secondary action/Filter

Ghost button with transparent background, 'Midnight Ink' text and border. Features a 100px border-radius creating a pill shape, with 6px vertical and 16px horizontal padding. Found for filters or secondary navigation.

### Text Link Button
**Role:** Minimal action

A button styled as a text link, transparent background, 'Charcoal Haze' text and bottom border. No border-radius, with 0px horizontal padding and 0px top padding but 10px bottom padding. Used for discreet actions within text.

### Circular Pagination Button
**Role:** Navigation Control

A circular button with 'Charcoal Haze' background at 5% opacity and 'Midnight Ink' text. Uses a 50% border-radius to create a perfect circle. Zero padding to maintain compact size.

### Block Input Field
**Role:** Text Input

Transparent background input field with 'Midnight Ink' text. Features a 'Border Ash' bottom border and a 0px border-radius. Padding is 11px vertical and 30px horizontal, with 11px bottom margin.

### White Border Input Field
**Role:** Text Input (Alternative)

Transparent background input field with 'Canvas White' text and a 'Canvas White' border, with a 3px border-radius. Features 8px vertical and 10px right padding with 0px left padding. Used against darker backgrounds.

### Simple Badge
**Role:** Informational Status

Transparent background with 'Midnight Ink' text, 0px border-radius and no padding. Used for minimal status indicators.

### Outline Status Badge
**Role:** Informational Status

White background with 'Muted Stone' text and border. Features 0px border-radius and 5px vertical / 10px horizontal padding. Typically used for 'Sold Out' indicators.

## Do's and Don'ts

### Do
- Prioritize 'Midnight Ink' (#0a0d0f) for primary text and 'Canvas White' (#ffffff) for page backgrounds.
- Use 'Aqua Thrill' (#1dd8e1) exclusively for primary call-to-action buttons and prominent interactive elements.
- Apply a 100px border-radius for all pill-shaped buttons and tags to maintain a consistent interactive element style.
- Ensure all headings use a wide letter spacing of 0.0900em as defined in the Cabin and Jost typography tokens.
- Maintain a clear vertical rhythm between sections using a 'sectionGap' of '50px'.
- Use Cabin (500, 600) or Jost (700) for all headings to create distinct visual hierarchy.
- Apply 'Border Ash' (#d5d6d7) for input field outlines and subtle dividers.

### Don't
- Do not use saturated colors other than 'Aqua Thrill' (#1dd8e1) and 'Electric Blue' (#2c75d4) for interactive elements.
- Avoid deep shadows or overly dimensional effects on components; prefer crisp borders and flat surfaces.
- Do not deviate from the specified letter spacing values for headings; consistent tracking is key to brand typography.
- Do not use 'Pure Black' (#000000) for general body text; reserve it for high-contrast headings or specific elements.
- Avoid non-standard border-radii for primary buttons; stick to 0px for solid actions and 100px for pill-shaped secondary actions.
- Do not introduce new typefaces; adhere strictly to Poppins, Cabin, Jost, and GTStandard-M.
- Do not use 'Charcoal Haze' (#2e3438) for large headlines; it is reserved for secondary text and muted elements.

## Imagery

The visual language for imagery focuses on high-quality product photography. Watches are presented as hero objects, often in clean, full-bleed compositions against a dark, atmospheric background (as seen in the first hero). Product shots are contained within neutral frames with crisp edges when displayed in grids, emphasizing the product itself. The site employs an 'icons-only' approach for certain UI elements like navigation for a minimalist feel. Imagery density is moderate, balancing product showcases with textual information.

## Layout

The page primarily uses a max-width contained model at 1200px, creating defined content areas. The hero section is a full-bleed visual experience with a dominant product image and centered textual call-to-action. Subsequent sections often feature a stacked, centered content arrangement (headline, subtext) followed by a grid of product cards. Vertical rhythm is established through consistent section gaps, with clear separation between content blocks. Navigation is a minimal top bar with discreet icons for menu and cart.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0d0f
background: #ffffff
border: #0a0d0f
accent: #2c75d4
primary action: #1dd8e1 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #1dd8e1 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a product name and price card: 'Canvas White' (#ffffff) background, product name in 'Midnight Ink' (#0a0d0f) (Poppins, weight 500, 17px), price in 'Midnight Ink' (#0a0d0f) (Poppins, weight 400, 17px), 3px border-radius, with 12px padding.
3. Create a secondary filter button: transparent background, 'Midnight Ink' (#0a0d0f) text (Cabin, weight 500, 14px), 'Midnight Ink' (#0a0d0f) 1px border, 100px border-radius, 6px vertical and 16px horizontal padding.
4. Create a prominent headline: 'Pure Black' (#000000), font Cabin, weight 600, 68px size, 1.0 lineHeight, 0.0900em letterSpacing.
5. Create an input field: transparent background, 'Midnight Ink' (#0a0d0f) text (Poppins, weight 400, 17px), 'Border Ash' (#d5d6d7) 1px bottom border, 3px border-radius, 11px vertical and 30px horizontal padding.

## Similar Brands

- **Filippo Loreti** — Uses monochrome base with a single pop of color for accents, clean product photography on dark backgrounds, and subtle typography.
- **MVMT Watches** — Similar strong product-focused imagery, high-contrast layouts, and a minimalist design aesthetic for e-commerce.
- **Shore Projects** — Employs clean typography, a spacious layout, and a focus on product visuals over busy interface elements.
- **Daniel Wellington** — Relies on a streamlined, elegant visual style with primary focus on product presentation against white or minimalist backdrops.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0a0d0f;
  --color-canvas-white: #ffffff;
  --color-charcoal-haze: #2e3438;
  --color-pure-black: #000000;
  --color-whisper-gray: #f7f7f7;
  --color-footer-gray: #efefef;
  --color-border-ash: #d5d6d7;
  --color-muted-stone: #656565;
  --color-aqua-thrill: #1dd8e1;
  --color-electric-blue: #2c75d4;

  /* Typography — Font Families */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cabin: 'Cabin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jost: 'Jost', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.09px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.38;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.09px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.37;
  --tracking-heading-lg: 0.09px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: 0.09px;

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
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-50: 50px;
  --spacing-72: 72px;
  --spacing-113: 113px;
  --spacing-166: 166px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 50px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-input: 3px;
  --radius-buttons: 100px;
  --radius-default: 3px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0a0d0f;
  --color-canvas-white: #ffffff;
  --color-charcoal-haze: #2e3438;
  --color-pure-black: #000000;
  --color-whisper-gray: #f7f7f7;
  --color-footer-gray: #efefef;
  --color-border-ash: #d5d6d7;
  --color-muted-stone: #656565;
  --color-aqua-thrill: #1dd8e1;
  --color-electric-blue: #2c75d4;

  /* Typography */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cabin: 'Cabin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jost: 'Jost', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.09px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.38;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.09px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.37;
  --tracking-heading-lg: 0.09px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: 0.09px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-50: 50px;
  --spacing-72: 72px;
  --spacing-113: 113px;
  --spacing-166: 166px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 100px;
}
```
