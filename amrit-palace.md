# Amrit Palace — Style Reference
> Opulent Old-World Canvas

**Theme:** dark

Amrit Palace evokes a luxurious, heritage dining experience through a warm, muted palette and classic typography. Deep, inviting colors define the background and text, accented by a subtle, aged gold. Typography blends a contemporary sans-serif with a more ornate, vintage serif for headlines, creating a duality of modern functionality and traditional elegance. Components favor understated outlines and minimal elevation, allowing content and photography to dominate with an air of sophisticated simplicity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Mahogany | `#2c2c2c` | `--color-mahogany` | Primary text, deep surface backgrounds, dark accents and borders — creating a rich, profound base |
| Aged Parchment | `#d8cbb8` | `--color-aged-parchment` | Subtle surface backgrounds, border fills for interactive elements, secondary text, and active navigation states. This color provides a soft, warm contrast |
| Amber Glow | `#d49653` | `--color-amber-glow` | Orange outline accent for tags, dividers, and focused UI edges |
| Soft Linen | `#dfdad5` | `--color-soft-linen` | Light background elements, subtle text highlights, and borders for less prominent components |
| Faded Stone | `#b6ab9c` | `--color-faded-stone` | Subtle, low-contrast borders and dividers, indicating soft visual separation |

## Tokens — Typography

### Satoshi — Body text, navigation, buttons, and most interactive elements — providing a modern, clear foundation. The compact letter spacing on larger sizes maintains a polished feel. · `--font-satoshi`
- **Substitute:** Inter
- **Weights:** 500, 700
- **Sizes:** 12px, 13px, 14px, 15px, 42px, 199px
- **Line height:** 0.80, 1.00, 1.30, 1.40
- **Letter spacing:** -0.0400em at 199px, -0.0160em at 42px, -0.0120em at 15px, -0.0110em at 14px, -0.0100em at 13px, 0.0100em at 12px
- **Role:** Body text, navigation, buttons, and most interactive elements — providing a modern, clear foundation. The compact letter spacing on larger sizes maintains a polished feel.

### TT Ramillas Variable — Dominant display and section headings — its delicate 300 weight and variable nature convey sophistication and luxury, setting a refined tone. · `--font-tt-ramillas-variable`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 22px, 26px, 50px, 65px, 69px, 115px
- **Line height:** 0.80, 0.85, 0.90, 1.00, 1.20
- **Letter spacing:** -0.0400em at 115px, -0.0350em at 69px, -0.0300em at 65px, -0.0060em at 22px
- **Role:** Dominant display and section headings — its delicate 300 weight and variable nature convey sophistication and luxury, setting a refined tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.3 | — | `--text-caption` |
| body-sm | 13px | 1.3 | — | `--text-body-sm` |
| body | 14px | 1.3 | — | `--text-body` |
| body-lg | 15px | 1.3 | — | `--text-body-lg` |
| heading-sm | 42px | 1.3 | — | `--text-heading-sm` |
| heading | 199px | 1.3 | — | `--text-heading` |

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
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 42 | 42px | `--spacing-42` |
| 92 | 92px | `--spacing-92` |
| 206 | 206px | `--spacing-206` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 3px |

### Layout

- **Section gap:** 62px
- **Card padding:** 12-16px
- **Element gap:** 2-20px

## Components

### Ghost Button (Text)
**Role:** Secondary action control

Text in Aged Parchment (#d8cbb8) on a transparent background, 0px border-radius, with 20px vertical padding and no horizontal padding. The text transforms to Mahogany (#2c2c2c) on hover, with an Amber Glow (#d49653) background.

### Outlined Button
**Role:** Primary action, interactive controls.

Bordered with Aged Parchment (#d8cbb8) at 0px radius, text in Aged Parchment (#d8cbb8), no background fill. It is a ghost style button with 20px of vertical padding, no horizontal padding.

### Review Card (Transparent)
**Role:** Displaying short-form testimonials or content blocks.

Transparent background with no box shadow, 0px border-radius. Padding of 52px top, 28px horizontal, 32px bottom.

### Review Card (Aged Parchment)
**Role:** Highlighting key information or user reviews.

Aged Parchment (#d8cbb8) background with no box shadow, 0px border-radius, no internal padding. Used for the Google reviews badge.

## Do's and Don'ts

### Do
- Always use TT Ramillas Variable weight 300 for major headlines (50px-115px) to convey understated elegance, employing tight letter spacing at larger sizes for density.
- Utilize the Aged Parchment (#d8cbb8) for secondary text and subtle background elements for a warm, inviting contrast.
- Apply Amber Glow (#d49653) sparingly as an accent for critical interactive elements or decorative highlights, ensuring it draws attention without overwhelming.
- Maintain a compact element spacing with 2-20px gaps to keep information dense and visually cohesive.
- Use a sharp 0px border-radius for main cards and a subtle 3px radius for all general interactive elements to maintain a modern, uncluttered aesthetic.
- Implement the Ghost Button (Text) for secondary actions to present options without visual clutter, appearing against darker backgrounds.

### Don't
- Avoid strong, vibrant colors outside of the Amber Glow (#d49653) accent, as they contradict the muted, sophisticated palette.
- Do not introduce heavy shadows or strong elevation effects; the design relies on subtle borders and background shifts for depth.
- Refrain from using varied border radii; adhere to the 0px for main layout elements and 3px for smaller interactive components.
- Do not use overly generous horizontal padding within content cards; maintain the compact 28px horizontal padding for transparent review cards.
- Avoid thin line heights on Satoshi body text (e.g. 0.8), use 1.3 or 1.4 for readability, reserving compressed line heights for headlines.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Mahogany Canvas | `#2c2c2c` | Primary background for the darkest sections and pages, serving as a rich, deep foundation. |
| 1 | Aged Parchment Surface | `#d8cbb8` | Secondary background for sections, cards, and interactive elements, providing a lighter, warm contrast. |
| 2 | Soft Linen Overlay | `#dfdad5` | Used for subtle highlights, specific data elements, and the lightest neutral backgrounds, creating soft visual breaks. |

## Imagery

Photography is key, featuring rich, inviting shots of food and interior spaces. Photos are generally dark, moody, and warm-toned, often with a shallow depth of field to keep the focus on the subject, creating an intimate and luxurious atmosphere. Treatment is often full-bleed or large contained blocks, contributing to a sense of immersion. Icons are minimal, outlined, and monochromatic, primarily serving functional navigation roles without drawing excessive attention. Imagery is dominant, often serving as section backgrounds.

## Layout

The page uses a full-bleed layout for sections, often with imagery as the primary background for hero areas and subsequent content blocks. Sections maintain consistent vertical spacing, often with text-left/image-right compositions or centered stacks, but without explicit visual dividers, flowing seamlessly. The hero section is characterized by a full-viewport image with a large, centered headline. Content is rich and dense, often leveraging 3-column card grids for features and reviews. Navigation is a minimal top bar, featuring ghost-style links and outlined action buttons, fixed at the top.

## Agent Prompt Guide

Quick Color Reference: text: #2c2c2c, background: #2c2c2c, border: #d8cbb8, accent: #d49653, primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: full-bleed background image. Headline 'FLAVORS THAT STAY' using TT Ramillas Variable weight 300, 115px, letter-spacing -46px, color #d8cbb8. Subtext 'SERVING CENTRAL FLORIDA' using Satoshi weight 500, 14px, #d8cbb8, letter-spacing -0.154px.
Create an Outlined Button: Border and text in Aged Parchment #d8cbb8, 0px radius, 20px vertical padding, no horizontal padding, Satoshi weight 500, 15px, letter-spacing -0.18px.
Create a Review Card: background transparent, no shadow, 0px border-radius, Padding 52px top, 28px left, 32px bottom, 28px right. Body text in Mahogany #2c2c2c, Satoshi weight 500, 14px, letter-spacing -0.154px.
Create a Testimonial Section Headline: 'WHAT OUR GUESTS SAY' using TT Ramillas Variable weight 300, 65px, letter-spacing -19.5px, color #2c2c2c.
Create a Google Review Badge: background Aged Parchment #d8cbb8, no shadow, 0px border-radius, no internal padding. Main text in Mahogany #2c2c2c, Satoshi weight 700, 13px, letter-spacing -0.13px.

## Similar Brands

- **The Polo Bar** — Shares a rich, dark, and traditional aesthetic with classic typography and warm lighting in imagery.
- **The Aviary** — Exhibits a similar focus on high-quality, moody photography and a blend of modern design with traditional elements.
- **The French Laundry** — Uses a limited, sophisticated color palette and elegant typography to convey exclusivity and a premium dining experience.
- **Carbone** — Features a retro-luxurious feel with deep color schemes, custom typography, and a dramatic visual presentation of food and interiors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-mahogany: #2c2c2c;
  --color-aged-parchment: #d8cbb8;
  --color-amber-glow: #d49653;
  --color-soft-linen: #dfdad5;
  --color-faded-stone: #b6ab9c;

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-ramillas-variable: 'TT Ramillas Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --text-body-sm: 13px;
  --leading-body-sm: 1.3;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 15px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 42px;
  --leading-heading-sm: 1.3;
  --text-heading: 199px;
  --leading-heading: 1.3;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-42: 42px;
  --spacing-92: 92px;
  --spacing-206: 206px;

  /* Layout */
  --section-gap: 62px;
  --card-padding: 12-16px;
  --element-gap: 2-20px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Named Radii */
  --radius-all: 3px;

  /* Surfaces */
  --surface-mahogany-canvas: #2c2c2c;
  --surface-aged-parchment-surface: #d8cbb8;
  --surface-soft-linen-overlay: #dfdad5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-mahogany: #2c2c2c;
  --color-aged-parchment: #d8cbb8;
  --color-amber-glow: #d49653;
  --color-soft-linen: #dfdad5;
  --color-faded-stone: #b6ab9c;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-ramillas-variable: 'TT Ramillas Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --text-body-sm: 13px;
  --leading-body-sm: 1.3;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 15px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 42px;
  --leading-heading-sm: 1.3;
  --text-heading: 199px;
  --leading-heading: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-42: 42px;
  --spacing-92: 92px;
  --spacing-206: 206px;

  /* Border Radius */
  --radius-sm: 3px;
}
```
