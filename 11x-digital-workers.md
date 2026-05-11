# 11x– Digital workers — Style Reference
> High-contrast digital command station

**Theme:** light

The 11x aesthetic centers on a functional, high-contrast digital workspace. It combines stark monochrome surfaces with compact, direct typography. A muted, earthy undertone provides subtle warmth beneath the UI, while a single, vivid teal accent punctuates key information and calls to action. Components are lightweight, favoring ghost elements and subtle elevation, creating a sense of efficiency and focus.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, button backgrounds, strong borders — foundation of the high-contrast UI |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, card surfaces, ghost button text — core light surface |
| Desert Dune | `linear-gradient(rgb(248, 249, 247), rgb(215, 206, 204))` | `--color-desert-dune` | Footer background, secondary card surfaces, and subtle section dividers – provides a soft, warm achromatic base; Subtle background gradient for soft transitions between surfaces |
| Misty Rose | `#d2b596` | `--color-misty-rose` | Subtle background washes, decorative elements — provides a muted, warm accent |
| Digital Teal | `#406e7a` | `--color-digital-teal` | Badge backgrounds, active indicators — a distinct and vivid accent for functional elements |
| Cloud Gray | `#f6f5f5` | `--color-cloud-gray` | Subtle card borders and alternative background for cards — acts as a very light neutral surface |
| Soft Peach | `#f5ece5` | `--color-soft-peach` | Internal card surfaces, subtle background shifts — a slightly warmer, off-white neutral |
| Lavender Mist | `#efe5f9` | `--color-lavender-mist` | Decorative card background — provides a subtle, near-neutral tint |
| Rocky Beige | `#ede2d7` | `--color-rocky-beige` | Decorative card background — provides a subtle, near-neutral tint |
| Slate Gray | `#afaeae` | `--color-slate-gray` | Muted button backgrounds, inactive states — a mid-tone neutral |
| Warm Linen | `#e1dad9` | `--color-warm-linen` | Internal card surfaces, background hover states — a slightly darker neutral than Canvas White but still very light |
| Glacial Blue | `#c5d5e8` | `--color-glacial-blue` | Decorative card background — provides a subtle, near-neutral tint |
| Arctic Teal | `#d4e6eb` | `--color-arctic-teal` | Decorative card background — provides a subtle, near-neutral tint |
| Error Umber | `#4c312b` | `--color-error-umber` | Error badge text/border — used for semantic feedback |

## Tokens — Typography

### ES Allianz — All textual elements from headings to body copy and interface labels. The consistent use of a custom sans-serif font across all scales establishes a unified, crisp, and direct tone. Its variable letter-spacing, particularly tighter at larger sizes, enhances its clean, modern feel. · `--font-es-allianz`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 8px, 14px, 16px, 18px, 19px, 28px, 32px, 46px, 56px, 64px, 74px, 152px
- **Line height:** 1.00
- **Letter spacing:** -0.0450em, -0.0450em, -0.0450em, -0.0400em, -0.0400em, -0.0200em
- **Role:** All textual elements from headings to body copy and interface labels. The consistent use of a custom sans-serif font across all scales establishes a unified, crisp, and direct tone. Its variable letter-spacing, particularly tighter at larger sizes, enhances its clean, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 28px | 1.2 | — | `--text-heading-sm` |
| heading | 46px | 1.1 | -0.04px | `--text-heading` |
| heading-lg | 56px | 1.1 | -0.04px | `--text-heading-lg` |
| display | 152px | 0.85 | -0.045px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 136 | 136px | `--spacing-136` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 8px |
| buttons | 999px |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Primary action

Solid Midnight Ink background with Canvas White text, fully rounded (999px). Padding is 12px vertical, 24px horizontal, signifying a prominent call to action.

### Ghost Nav Link Button
**Role:** Navigation and secondary actions

Transparent background with Midnight Ink text and border, no explicit radius (0px). Padding is 8px vertical, 14px horizontal, used for menu items and less prominent actions maintaining the high-contrast feel.

### Floating Action Button
**Role:** Contextual help

Semi-transparent dark background (rgba(34, 34, 34, 0.4)) with Canvas White text, circular shape (100% radius). This button appears fixed and provides immediate assistance.

### Secondary Filled Button
**Role:** Secondary action

Canvas White background with Midnight Ink text, fully rounded (999px). Padding is 12px vertical, 24px horizontal, offering a visual alternative to the primary button.

### Card, No Padding
**Role:** Container, unpadded

Transparent background, 0px radius, no padding, no shadow. Used for content that extends to edges or for structural grouping.

### Card, Standard Padding
**Role:** Standard content container

Transparent background, 16px radius, 24px padding on all sides, no shadow. A common content block with clear boundaries.

### Card, Muted Background
**Role:** Emphasized content container

Muted Desert Dune background (rgba(215, 206, 204, 0.75)), 16px radius, 16px padding on all sides, no shadow. Used for visually distinct sections or featured content.

### Text Badge
**Role:** Labels, tags, status indicators

Transparent background with Canvas White text, no radius, no padding. Used for simple textual labels embedded within dark sections.

### Digital Teal Badge
**Role:** Informational tags, active states

Digital Teal background (rgba(0, 0, 0, 0.1)) with Canvas White text, 999px radius, 4px vertical, 12px horizontal padding. A visually soft badge for metadata.

### Segmented Badge
**Role:** Category labels, filter tags

Light gray background (rgba(243, 244, 246, 0.1)) with Midnight Ink text, 8px radius, 8px vertical, 16px horizontal padding. Used for filtering and categorization.

### Semantic Error Badge
**Role:** Error or warning tags

Digital Teal background (#406e7a) with Midnight Ink text, 2px radius, no padding. This badge stands out for critical information.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and button backgrounds to maintain high contrast.
- Apply Canvas White (#ffffff) as the primary page background and secondary button fills.
- Always use ES Allianz font with specified weights and letter-spacing for all text elements.
- Implement 999px border-radius for all primary and secondary buttons, and 8px for badges, for a consistently rounded aesthetic.
- Maintain high visual contrast throughout the UI, primarily between Midnight Ink and Canvas White.
- Utilize 16px padding for standard content cards and 24px for more prominent content blocks.
- Incorporate Desert Dune (#d7cecc) for footer backgrounds and subtle section separators to provide a neutral base.

### Don't
- Avoid arbitrary color choices; restrict to the defined palette, using Digital Teal (#406e7a) sparingly for key accents only.
- Do not introduce new font families or weights outside of ES Allianz (400, 500, 700).
- Avoid excessive use of shadows; components should feel lightweight and flat.
- Do not deviate from the established spacing scale (multiples of 8px) to introduce new element or section gaps.
- Disregard strict rounding rules: buttons are 999px, badges 8px, cards 16px.
- Do not place multiple elements too close together; maintain at least an 8px element gap for readability.
- Avoid complex gradients, except for the subtle Terracotta Sunset linear gradient for background transitions.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background |
| 2 | Cloud Gray | `#f6f5f5` | Secondary card surfaces, subtle background shifts |
| 3 | Soft Peach | `#f5ece5` | Tertiary card surfaces, slightly warmer off-white |
| 4 | Desert Dune | `#d7cecc` | Muted card backgrounds, footer background, and subtle section separators |

## Imagery

The visual language features crisp product-focused screenshots of 'digital workers' with human faces, presented in clear, isolated frames. Photography is contained, often with 16px rounded corners, emphasizing the product without lifestyle distractions. Icons are subtle, simple, and monochrome, integrating seamlessly into the UI. Overall, imagery is treated as explanatory content rather than decorative atmosphere, supporting a text-dominant layout with specific visual anchors.

## Layout

The page primarily uses a max-width contained layout, though the hero section spans full-bleed with a dramatic, dark photographic background. Sections mainly alternate between a standard white background and a subtle Desert Dune (#d7cecc) or linear gradient background, creating clear visual segmentation. Content is typically arranged in left-aligned stacks or two-column text-left/image-right configurations. Card grids feature heavily, often with 3-column layouts. The overall density is compact but with generous vertical section spacing, ensuring readability while presenting substantial information. Navigation is a sticky top bar with a prominent 'Get started' button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #406e7a
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background Midnight Ink (#000000), text Canvas White (#ffffff), 999px radius, 12px vertical padding, 24px horizontal padding, font ES Allianz 500 weight 16px.
2. Design a Standard Content Card: background Canvas White (#ffffff), 16px radius, 24px padding, Midnight Ink (#000000) borders of 1px solid, font ES Allianz 400 weight 16px for body text.
3. Implement a Digital Teal Badge: background Digital Teal (#406e7a), text Canvas White (#ffffff), 999px radius, 4px vertical padding, 12px horizontal padding, font ES Allianz 400 weight 14px.
4. Build a Ghost Nav Link Button: transparent background, text Midnight Ink (#000000), 0px radius, 8px vertical padding, 14px horizontal padding, font ES Allianz 500 weight 16px.
5. Create a Hero Headline: text Canvas White (#ffffff), font ES Allianz 700 weight 74px, lineHeight 1.1, letterSpacing -0.045em.

## Similar Brands

- **Linear** — High-contrast monochrome UI with a single accent color and compact typography.
- **Stripe** — Clean, flat aesthetic prioritizing typography, clear information hierarchy, and minimal use of color.
- **Vercel** — Emphasis on dark backgrounds for hero sections, light component styling on white canvases, and direct, functional layouts.
- **Retool** — Business-oriented interface with a focus on data presentation, subtle neutrals, and efficient information density.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-desert-dune: #d7cecc;
  --gradient-desert-dune: linear-gradient(rgb(248, 249, 247), rgb(215, 206, 204));
  --color-misty-rose: #d2b596;
  --color-digital-teal: #406e7a;
  --color-cloud-gray: #f6f5f5;
  --color-soft-peach: #f5ece5;
  --color-lavender-mist: #efe5f9;
  --color-rocky-beige: #ede2d7;
  --color-slate-gray: #afaeae;
  --color-warm-linen: #e1dad9;
  --color-glacial-blue: #c5d5e8;
  --color-arctic-teal: #d4e6eb;
  --color-error-umber: #4c312b;

  /* Typography — Font Families */
  --font-es-allianz: 'ES Allianz', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 46px;
  --leading-heading: 1.1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.04px;
  --text-display: 152px;
  --leading-display: 0.85;
  --tracking-display: -0.045px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;
  --radius-full-2: 9999px;
  --radius-full-3: 16000px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 8px;
  --radius-buttons: 999px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #f6f5f5;
  --surface-soft-peach: #f5ece5;
  --surface-desert-dune: #d7cecc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-desert-dune: #d7cecc;
  --color-misty-rose: #d2b596;
  --color-digital-teal: #406e7a;
  --color-cloud-gray: #f6f5f5;
  --color-soft-peach: #f5ece5;
  --color-lavender-mist: #efe5f9;
  --color-rocky-beige: #ede2d7;
  --color-slate-gray: #afaeae;
  --color-warm-linen: #e1dad9;
  --color-glacial-blue: #c5d5e8;
  --color-arctic-teal: #d4e6eb;
  --color-error-umber: #4c312b;

  /* Typography */
  --font-es-allianz: 'ES Allianz', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 46px;
  --leading-heading: 1.1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.04px;
  --text-display: 152px;
  --leading-display: 0.85;
  --tracking-display: -0.045px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;
  --radius-full-2: 9999px;
  --radius-full-3: 16000px;
}
```
