# Bento — Style Reference
> Vibrant, playful canvases

**Theme:** light

Linktree employs a vibrant, high-contrast visual system built around playful, oversized typography and boldly colored, flat surfaces. The design makes liberal use of curved shapes, particularly extreme pill-like radii, creating a soft yet dynamic feel. Color functions primarily as an energetic accent, rotating through vivid primary and secondary hues to delineate sections and highlight interactive elements, while core content remains anchored by highly legible black text on clean white or near-white backgrounds. Components are lightweight with minimal elevation, emphasizing color and shape over heavy borders or shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#1e2330` | `--color-ink` | Primary text, deep neutral backgrounds for headers and footers, button text on light backgrounds |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, text on dark backgrounds |
| Marble Fog | `#f3f3f1` | `--color-marble-fog` | Subtle background for UI elements and sections, ghost button backgrounds |
| Ash Concrete | `#676b5f` | `--color-ash-concrete` | Muted text, link borders when not active, placeholder text |
| Charcoal Grey | `#222222` | `--color-charcoal-grey` | Darker text, button borders |
| Chartreuse Kick | `#d2e823` | `--color-chartreuse-kick` | Primary action buttons, accented card backgrounds, vibrant section backgrounds |
| Hydrangea Bold | `#2665d6` | `--color-hydrangea-bold` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Lavender Pop | `#e9c0e9` | `--color-lavender-pop` | Accent cards, button backgrounds, decorative graphics |
| Iris Deep | `#061492` | `--color-iris-deep` | Deep blue accent for cards and specific buttons |
| Dahlia Grape | `#502274` | `--color-dahlia-grape` | Rich violet background for content sections |
| Crimson Currant | `#780016` | `--color-crimson-currant` | Deep red background for specific content sections and cards |
| Forest Green | `#254f1a` | `--color-forest-green` | Dark green accent for cards and specific text |
| Marigold Gold | `#d6a337` | `--color-marigold-gold` | Warm gold accent for cards |

## Tokens — Typography

### Arial — Standard body text and interface elements. A highly legible system font for dense content. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Standard body text and interface elements. A highly legible system font for dense content.

### Linksans Linksansvf — Display and headings. The varying letter-spacing creates controlled visual impact, becoming tighter at larger sizes for density. · `--font-linksans-linksansvf`
- **Substitute:** Inter
- **Weights:** 400, 500, 700, 800
- **Sizes:** 14px, 16px, 18px, 24px, 28px, 56px, 80px
- **Line height:** 1.00, 1.06, 1.07, 1.20, 1.30, 1.50
- **Letter spacing:** -0.0200em at 24-80px, -0.0100em at 18px
- **Role:** Display and headings. The varying letter-spacing creates controlled visual impact, becoming tighter at larger sizes for density.

### Linksans — Subheadings, navigation items, and larger body text. This family maintains a consistent geometric feel with subtle variations in tracking. · `--font-linksans`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 13px, 14px, 15px, 20px, 24px, 25px, 51px
- **Line height:** 1.06, 1.20, 1.31, 1.50, 2.32
- **Letter spacing:** -0.0430em at 51px, -0.0240em at 24-25px, -0.0200em at 20px, -0.0130em for smaller sizes
- **Role:** Subheadings, navigation items, and larger body text. This family maintains a consistent geometric feel with subtle variations in tracking.

### yerk — yerk — detected in extracted data but not described by AI · `--font-yerk`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.5
- **Role:** yerk — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | -0.19px | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.31 | -0.58px | `--text-subheading` |
| heading | 28px | 1.2 | -0.56px | `--text-heading` |
| heading-lg | 51px | 1.06 | -2.2px | `--text-heading-lg` |
| display | 80px | 1 | -1.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 65 | 65px | `--spacing-65` |
| 128 | 128px | `--spacing-128` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| inputs | 8px |
| buttons | 99px |
| pillForms | 1000px |
| largeCards | 64px |
| navigation | 8px |

### Layout

- **Page max-width:** 1504px
- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Pill Accent Button
**Role:** Primary calls to action

A pill-shaped button with Chartreuse Kick (#d2e823) background and Ink (#1e2330) text. Uses 99px border-radius, 20px vertical padding, and 26px horizontal padding. Energetic and highly visible.

### Filled Square Button
**Role:** Secondary action buttons, form submission

A square button with Marble Fog (#f3f3f1) background and Ink (#1e2330) text. Uses 8px border-radius, 22px vertical padding, and 26px horizontal padding.

### Ghost Text Button
**Role:** Tertiary actions, navigation links

A transparent button with Ink (#1e2330) text and no background or border. Used for discrete actions or internal navigation. No explicit padding, relies on text-based spacing.

### Navigation Link
**Role:** Top navigation items

Transparent background with Ink text. Text size 16px, Linesans Linksansvf, weight 400. No explicit padding or border radius on interaction.

### Hero Section Card
**Role:** Decorative content containers

Transparent background with a 32px border-radius. No box shadow. Used for showcasing images or illustrations within the hero section.

### Colored Feature Card
**Role:** Highlighting key features or statistics

These cards use various brand colors like Hydrangea Bold (#2665d6), Lavender Pop (#e9c0e9), Iris Deep (#061492), Forest Green (#254f1a), Marigold Gold (#d6a337), or Crimson Currant (#780016) backgrounds. They feature an extreme 64px or 1000px border-radius, with no box shadow or padding.

### Input Field
**Role:** User data entry

Pure White (#ffffff) background with a 1px solid Ink (#000000) border, 8px border-radius. Placeholder text uses Ash Concrete (#757575). 8px vertical padding, 16px horizontal padding.

## Do's and Don'ts

### Do
- Use Chartreuse Kick (#d2e823) for primary call-to-action buttons, ensuring a 99px border-radius and Ink (#1e2330) text.
- Apply extreme large border radii (64px, 1000px) to decorative cards and feature blocks to maintain a playful aesthetic.
- Prioritize Linksans Linksansvf or Linksans for all headings and subheadings, adjusting letter-spacing according to the specified type scale for visual cohesion.
- Maintain a clear visual hierarchy by using Pure White (#ffffff) or Marble Fog (#f3f3f1) as background for most content areas, contrasted with Ink (#1e2330) text.
- Employ the specified brand colors – Chartreuse Kick, Hydrangea Bold, Lavender Pop, Iris Deep, Dahlia Grape, Crimson Currant, Forest Green, Marigold Gold – as vibrant, full-block section backgrounds on a rotating basis.
- Use Arial for standard body text at 16px to ensure optimal readability for longer passages.
- Apply 10px as the default elementGap for consistency in vertical spacing between discrete UI elements.

### Don't
- Avoid using drop shadows on cards or buttons; the design system relies on color, shape, and bold typography for visual differentiation.
- Do not introduce new color hues; strictly adhere to the defined brand and neutral palettes to maintain brand consistency.
- Do not deviate from the specified border-radii; the curved aesthetic is a core part of the brand identity making specific values critical.
- Avoid using subtle grays for interactive elements; actions should be clearly distinguished with vibrant brand colors.
- Do not use generic system fonts for display or heading text; it dilutes the distinctive typographic voice.
- Do not apply padding or margins that break the established elementGap (10px) and sectionGap (48px) rhythm.
- Do not use less than 20px vertical padding on primary buttons; the generous padding is integral to their confident presence.

## Imagery

Linktree primarily uses product screenshots and contained lifestyle photography for branding, often with a unique treatment. Product-focused imagery is presented full-bleed or within cards, frequently tinted or placed on brand-colored backgrounds, with rounded corners of varying degrees (from 8px to extreme 1000px pills and 64px large radii). Photography is high-key, vibrant, and features people interacting with digital products or engaging in creative activities. Illustrations are simple, filled, geometric, and often utilize the brand's vibrant color palette, serving decorative and explanatory roles. Icons are filled and monochromatic, complementing the flat UI. Visual density is moderate, allowing imagery to break up text-heavy sections and act as visual anchors.

## Layout

The page uses a maximum content width of 1504px, with content centered. The hero section is full-bleed, aggressively using a brand color as its background (e.g., Chartreuse Kick or Hydrangea Bold) with large, bold, centered typography. Subsequent sections alternate between vibrant solid color backgrounds and Pure White or Marble Fog, creating clear visual segmentation. Content arrangement frequently features large, centered headlines followed by a button, or alternating text-left / visual-right layouts. Card grids are used for features, showcasing product benefits within a collection of creatively shaped and colored containers. The layout is spacious with distinct vertical section spacing, lending an open and friendly feel. A sticky top navigation bar provides consistent access to key sections.

## Agent Prompt Guide

Quick Color Reference: 
text: #1e2330
background: #ffffff
border: #000000
accent: #2665d6
primary action: #d2e823 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #d2e823 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a standard input field: '#ffffff' background, 1px solid '#000000' border, 8px border-radius, 8px vertical padding, 16px horizontal padding, placeholder text '#757575'.
3. Create a hero section heading: 'Linksans Linksansvf' weight 800 80px, letter-spacing -1.6px, '#1e2330' color, centered over a '#d2e823' background.

## Similar Brands

- **Canva** — Shares a vibrant, illustrative style with bold colors and rounded shapes, prioritizing visual appeal over stark professionalism.
- **Fiverr** — Employs energetic, often bright color palettes and visually distinct components to convey creativity and action.
- **Gumroad** — Features a direct, creator-focused design with an emphasis on bold calls to action and approachable, clear layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #1e2330;
  --color-pure-white: #ffffff;
  --color-marble-fog: #f3f3f1;
  --color-ash-concrete: #676b5f;
  --color-charcoal-grey: #222222;
  --color-chartreuse-kick: #d2e823;
  --color-hydrangea-bold: #2665d6;
  --color-lavender-pop: #e9c0e9;
  --color-iris-deep: #061492;
  --color-dahlia-grape: #502274;
  --color-crimson-currant: #780016;
  --color-forest-green: #254f1a;
  --color-marigold-gold: #d6a337;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans-linksansvf: 'Linksans Linksansvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans: 'Linksans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-yerk: 'yerk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.19px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.31;
  --tracking-subheading: -0.58px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.56px;
  --text-heading-lg: 51px;
  --leading-heading-lg: 1.06;
  --tracking-heading-lg: -2.2px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-65: 65px;
  --spacing-128: 128px;
  --spacing-216: 216px;

  /* Layout */
  --page-max-width: 1504px;
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 29.09px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 41.6px;
  --radius-full: 64px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-inputs: 8px;
  --radius-buttons: 99px;
  --radius-pillforms: 1000px;
  --radius-largecards: 64px;
  --radius-navigation: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #1e2330;
  --color-pure-white: #ffffff;
  --color-marble-fog: #f3f3f1;
  --color-ash-concrete: #676b5f;
  --color-charcoal-grey: #222222;
  --color-chartreuse-kick: #d2e823;
  --color-hydrangea-bold: #2665d6;
  --color-lavender-pop: #e9c0e9;
  --color-iris-deep: #061492;
  --color-dahlia-grape: #502274;
  --color-crimson-currant: #780016;
  --color-forest-green: #254f1a;
  --color-marigold-gold: #d6a337;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans-linksansvf: 'Linksans Linksansvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans: 'Linksans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-yerk: 'yerk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.19px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.31;
  --tracking-subheading: -0.58px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.56px;
  --text-heading-lg: 51px;
  --leading-heading-lg: 1.06;
  --tracking-heading-lg: -2.2px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-65: 65px;
  --spacing-128: 128px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 29.09px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 41.6px;
  --radius-full: 64px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;
}
```
