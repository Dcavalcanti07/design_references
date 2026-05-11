# reboot — Style Reference
> Architectural blueprint on white marble.

**Theme:** light

This design system evokes the precision of an architectural blueprint, meticulously rendered against stark white. Clarity is paramount, achieved through high contrast and an almost clinical absence of chromatic color. The unique use of near-invisible, outline-only components creates an airy lightness, making every element feel deliberately placed while maintaining a clean, spacious aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces. |
| Type Ink | `#000000` | `--color-type-ink` | Primary text across all elements, delivering crisp contrast. |
| Subtle Gray | `#232323` | `--color-subtle-gray` | Secondary text and headlines, providing softer emphasis than Type Ink. |
| Whisper Gray | `#a7a7a7` | `--color-whisper-gray` | Muted body text and subtle accents, used sparingly for a soft touch. |
| Outline Ash | `#e5e7eb` | `--color-outline-ash` | Borders for subtle containers and interaction states, barely registering against the white. |
| Frost | `#c8c8c8` | `--color-frost` | Lightest gray, for very subtle text elements where minimal prominence is desired. |
| Oceanic Blue Gradient | `linear-gradient(rgb(0, 200, 251), rgb(26, 47, 247))` | `--color-oceanic-blue-gradient` | Illustrative element, adds a futuristic, digital sheen. |
| Sunset Fire Gradient | `linear-gradient(to right bottom, rgb(164, 52, 30), rgb(239, 51, 19), rgb(244, 164, 27))` | `--color-sunset-fire-gradient` | Illustrative element, brings a warm, energetic burst. |

## Tokens — Typography

### Inter — Used across all text roles; headlines use heavier weights, body text maintains readability with 400. Its versatility and clean lines are central to the understated aesthetic. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 40px
- **Line height:** 1.43, 1.50, 1.60, 1.80
- **Letter spacing:** normal
- **Role:** Used across all text roles; headlines use heavier weights, body text maintains readability with 400. Its versatility and clean lines are central to the understated aesthetic.

### Inter — Used for button text and subtle emphasis where a slight increase in weight is needed without becoming bold. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 40px
- **Line height:** 1.43, 1.50, 1.60, 1.80
- **Letter spacing:** normal
- **Role:** Used for button text and subtle emphasis where a slight increase in weight is needed without becoming bold.

### Inter — Dominant for headings and key emphasis. This exact weight (600) balances prominence with the system's overall light touch. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 40px
- **Line height:** 1.43, 1.50, 1.60, 1.80
- **Letter spacing:** normal
- **Role:** Dominant for headings and key emphasis. This exact weight (600) balances prominence with the system's overall light touch.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| display | 40px | 1.8 | — | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.0...` | `--shadow-subtle` |

### Layout

## Components

### Outline Pill Button
**Role:** Primary Call to Action for secondary actions

Text in Type Ink (#000000) or Subtle Gray (#232323). Background is transparent. Border is Outline Ash (#e5e7eb) at 1px, with 9999px border-radius, creating a pill shape. Padding is visually flexible, but based on a 4px-8px vertical, 16px-24px horizontal rhythm.

### Ghost Header Button
**Role:** Navigation items and subtle actions in the header

Transparent background, Type Ink (#000000) text (Inter 500, 14px, 1.43 lineHeight). Features a subtle bottom border in Outline Ash (#e5e7eb) when active, 9999px border radius but relies on padding for the `pill` effect (e.g., 0px vertical, 16px horizontal).

### Information Card with Shadow
**Role:** Used for featured content blocks or structured information display.

Background is Canvas White (#ffffff). Features a prominent multi-layered shadow: rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, ..., 0px 24px 24px -12px. Border radius is 16px. Inner padding is generally 32px.

## Do's and Don'ts

### Do
- Prioritize Inter font at weights 400, 500, and 600 for all text elements to maintain a unified typographic voice.
- Utilize Type Ink (#000000) for primary text and Canvas White (#ffffff) for backgrounds to ensure AAA contrast ratios.
- Apply 9999px border-radius to all buttons and tags to consistently achieve a soft, pill-like shape.
- Employ Outline Ash (#e5e7eb) for all borders, creating a subtle, almost invisible visual separation.
- Maintain generous spacing, with section gaps and large paddings often aligning to 32px or 40px, for an airy and comfortable density.
- Use Subtle Gray (#232323) or Whisper Gray (#a7a7a7) for secondary content to create clear visual hierarchy without harshness.

### Don't
- Avoid strong, saturated chromatic colors in the UI; vibrant gradients are reserved only for illustrative, non-interactive elements.
- Do not use heavy, solid backgrounds for interactive components; instead, leverage transparent fills and subtle borders.
- Refrain from deviating from the Inter font family or its specified weights (400, 500, 600) for any content.
- Do not introduce sharp corners; the soft 16px or 9999px radii are a defining characteristic.
- Avoid excessive use of borders or visual dividers beyond the subtle Outline Ash, as it compromises the minimalist aesthetic.
- Do not reduce primary body text below 16px (Inter 400, 16px, 1.5 lineHeight) to ensure readability.

## Elevation

- **Information Card:** `rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px`

## Imagery

This design primarily relies on abstract, illustrative graphics featuring vibrant gradients (Oceanic Blue Gradient, Sunset Fire Gradient) and occasional subtle, almost iconic imagery. There is a strong absence of photography and realistic illustrations. Icons, when present, are light and feature minimal, often outlined forms, or are simple SVG shapes. The imagery serves a decorative or conceptual role, adding splashes of visual interest without competing with the textual content, maintaining a text-dominant density.

## Layout

The pages conform to a maximum content width, centered on a Canvas White background, creating a structured canvas. The hero section features a prominent, centered headline with a subtext below, allowing ample white space. Content sections typically alternate between left-aligned text blocks and right-aligned abstract graphics or key feature callouts. There's a consistent vertical rhythm of comfortable section gaps (often 32px or 40px). Navigation is a minimal top bar with ghost buttons, suggesting a more app-like or single-page experience.

## Agent Prompt Guide

### Quick Color Reference
- Text (Type Ink): #000000
- Background (Canvas White): #ffffff
- Border (Outline Ash): #e5e7eb
- Secondary Text (Subtle Gray): #232323
- Gradient Accent (Oceanic Blue): #00c8fb

### Example Component Prompts
1. Create a header navigation bar: Canvas White (#ffffff) background. Logo on left. On the right, two 'Ghost Header Button' components for 'Hiring' and 'Web Designer' (Inter 500, 14px, Type Ink #000000 text, 0px vertical padding, 16px horizontal padding).
2. Create a hero section: Canvas White (#ffffff) background. Centered headline 'We build world-class marketing sites for software startups.' (Inter 600, 40px, 1.8 lineHeight, Type Ink #000000). Below, centered body text 'We are a senior product team helping founders showcase how good their products really are.' (Inter 400, 16px, 1.5 lineHeight, Subtle Gray #232323).
3. Create an 'Information Card': Canvas White (#ffffff) background, 16px border-radius, with padding of 32px on all sides. Include the specified multi-layer box-shadow (rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px).

## Similar Brands

- **Linear** — Shares a precise, high-contrast typographic focus on a mostly white background, with minimal use of chromatic color for functional accents.
- **Raycast** — Employs similar ghost button styles, large type, and a clean, almost clinical aesthetic, focusing on direct communication.
- **Vercel** — Features a strong emphasis on typography, ghost-like UI elements, and a high-contrast neutral palette with occasional, deliberate bursts of gradient for impact.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-type-ink: #000000;
  --color-subtle-gray: #232323;
  --color-whisper-gray: #a7a7a7;
  --color-outline-ash: #e5e7eb;
  --color-frost: #c8c8c8;
  --color-oceanic-blue-gradient: #00c8fb;
  --gradient-oceanic-blue-gradient: linear-gradient(rgb(0, 200, 251), rgb(26, 47, 247));
  --color-sunset-fire-gradient: #a4341;
  --gradient-sunset-fire-gradient: linear-gradient(to right bottom, rgb(164, 52, 30), rgb(239, 51, 19), rgb(244, 164, 27));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-display: 40px;
  --leading-display: 1.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Layout */

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-type-ink: #000000;
  --color-subtle-gray: #232323;
  --color-whisper-gray: #a7a7a7;
  --color-outline-ash: #e5e7eb;
  --color-frost: #c8c8c8;
  --color-oceanic-blue-gradient: #00c8fb;
  --color-sunset-fire-gradient: #a4341;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-display: 40px;
  --leading-display: 1.8;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;
}
```
