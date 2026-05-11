# Wispr Flow — Style Reference
> Warm parchment sophistication

**Theme:** light

Wispr Flow embraces a serene, almost academic aesthetic, blending a warm, muted palette with classic serif typography for large displays and a modern sans-serif for functional text. The design is characterized by generous spacing and soft, rounded elements that create a friendly and approachable feel. Dark, rich greens and deep grays are used to anchor sections, while a soft lavender provides a playful, yet restrained, accent for interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment | `#ffffeb` | `--color-parchment` | Page backgrounds, card surfaces, ghost button backgrounds, default borders — creating a soft, warm canvas |
| Ink | `#1a1a1a` | `--color-ink` | Primary text, dark card backgrounds, hero backgrounds, primary borders |
| Forest Canopy | `#034f46` | `--color-forest-canopy` | Section backgrounds, prominent card backgrounds, active button fills |
| Pale Lavender | `#f0d7ff` | `--color-pale-lavender` | Primary action button backgrounds, accent underlines for headings |
| Stone | `#e4e4d0` | `--color-stone` | Subtle border colors, secondary navigation backgrounds |
| Charcoal Text | `#222222` | `--color-charcoal-text` | Secondary text in navigation and neutral buttons |
| Muted Ash | `#8a8a80` | `--color-muted-ash` | Headline text — a softer black for large, elegant typography |
| White | `#ffffff` | `--color-white` | Text on dark backgrounds, icon strokes, active badge borders |
| Sunburst | `#ffa946` | `--color-sunburst` | Accent badge backgrounds, decorative fills in illustrations |

## Tokens — Typography

### Figtree — Body text, UI elements, navigation, buttons, and detailed content — its clean, modern lines provide functional clarity. · `--font-figtree`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 20px, 22px, 24px, 32px
- **Line height:** 0.95, 1.00, 1.30
- **Role:** Body text, UI elements, navigation, buttons, and detailed content — its clean, modern lines provide functional clarity.

### EB Garamond — Display headings and prominent headlines — chosen for its classic, elegant character that introduces a sophisticated, editorial feel. · `--font-eb-garamond`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 32px, 48px, 64px, 120px
- **Line height:** 0.85, 0.95, 1.10, 1.30
- **Letter spacing:** -0.03em at 32px, -0.05em at 48px, -0.07em at 64px, -0.13em at 120px
- **Role:** Display headings and prominent headlines — chosen for its classic, elegant character that introduces a sophisticated, editorial feel.

### Apple Color Emoji — Apple Color Emoji — detected in extracted data but not described by AI · `--font-apple-color-emoji`
- **Weights:** 400
- **Sizes:** 72px
- **Line height:** 1.3
- **Role:** Apple Color Emoji — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.3 | — | `--text-body-sm` |
| body | 16px | 1.3 | — | `--text-body` |
| subheading | 20px | 1.3 | — | `--text-subheading` |
| subheading-lg | 22px | 1.3 | — | `--text-subheading-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | -0.48px | `--text-heading` |
| heading-lg | 48px | 0.95 | -0.48px | `--text-heading-lg` |
| display | 64px | 0.85 | -0.48px | `--text-display` |
| display-xl | 120px | 0.85 | -0.48px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 128 | 128px | `--spacing-128` |
| 168 | 168px | `--spacing-168` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| badges | 992px |
| global | 1600px |
| images | 40px |
| inputs | 14px |
| buttons | 12px |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Interactive element

Buttons with Pale Lavender (#f0d7ff) background and Ink (#1a1a1a) text, rounded corners at 12px. Used for primary calls to action.

### Outline Ghost Button
**Role:** Interactive element

Transparent background with Ink (#222222) border and text, 0px radius. Used for secondary actions that don't need strong emphasis.

### Branded Action Button
**Role:** Interactive element

Forest Canopy (#034f46) background with Parchment (#ffffeb) text, 32px radius. Reserved for prominent, section-specific actions.

### Soft Card
**Role:** Content container

Parchment (#ffffeb) background, 32px padding, 32px border radius. Used for general content grouping on the light canvas.

### Dark Content Card
**Role:** Content container

Ink (#1a1a1a) background, 70px top-padding, 55px horizontal padding, 40px border radius. Used for featured content and sections on dark backgrounds.

### Subtle Badge
**Role:** Categorization/status

Transparent background with Ink (#1a1a1a) text and 992px border radius, 11px vertical and 16px horizontal padding. For discrete labeling.

### Branded Badge
**Role:** Categorization/status

Forest Canopy (#034f46) background with White (#ffffff) text, 1000px border radius, 8px vertical and 16px horizontal padding. For prominent categorization.

## Do's and Don'ts

### Do
- Use Parchment (#ffffeb) as the dominant background color for light sections and Ink (#1a1a1a) for dark sections to maintain visual rhythm.
- Apply EB Garamond for all display and large body headings to convey an academic, sophisticated tone, incorporating its specific letter-spacing values.
- Utilize Pale Lavender (#f0d7ff) exclusively for primary call-to-action buttons to ensure consistent highlight for interactive elements.
- Apply a 12px border-radius to all buttons and a 32px border-radius to cards, creating a consistent soft-edged aesthetic.
- Maintain a comfortable density with generous spacing: 64px for section gaps, 32px for card padding, and an 8px base unit for element gaps.
- Offset large typeface headlines with a subtle underline using Pale Lavender (#f0d7ff) to draw attention without excessive weight.

### Don't
- Avoid using harsh, bright whites or pure blacks that would disrupt the soft, muted color palette.
- Do not deviate from the specified border-radii; sharp corners will undermine the friendly, approachable aesthetic.
- Refrain from heavy drop shadows or excessive elevation, as the design system prioritizes a flat, surface-level presentation.
- Do not introduce additional font families; Figtree and EB Garamond provide the necessary range for both functional and expressive text.
- Avoid overusing saturated colors; limit Sunburst (#ffa946) and Forest Canopy (#034f46) to functional accents and key sections.
- Do not use generic button styles; ensure all interactive elements conform to the Primary, Outline Ghost, or Branded Action Button variants.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Parchment Canvas | `#ffffeb` | Base page background and default light content surfaces. |
| 1 | Ink Content Block | `#1a1a1a` | Prominent dark content sections, hero backgrounds, and featured card surfaces. |
| 2 | Forest Canopy Feature Block | `#034f46` | Distinct, attention-grabbing sections and branded cards. |

## Agent Prompt Guide

Quick Color Reference:
text: #1a1a1a
background: #ffffeb
border: #1a1a1a
accent: #f0d7ff
primary action: #f0d7ff (filled action)

3-5 Example Component Prompts:
1. Create a Primary Action Button: #f0d7ff background, #1a1a1a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Dark Content Card: Ink (#1a1a1a) background, 40px border radius, 70px top padding. White (#ffffff) text at 22px Figtree weight 400 for subheadings and 16px for body. Include a white icon using a White (#ffffff) stroke if possible.
3. Implement a Branded Action Button: Forest Canopy (#034f46) background, White (#ffffff) text at 16px Figtree weight 400, 32px radius and 32px padding overall.
4. Create a Section Header: EB Garamond at 64px, Muted Ash (#8a8a80), letter-spacing -0.07em, with a Pale Lavender (#f0d7ff) underline for emphasis.

## Similar Brands

- **Grammarly** — Focuses on text refinement, uses a clean, bright aesthetic with a single accent color for primary actions.
- **Otter.ai** — AI-powered transcription service with a professional yet accessible visual style, combining light backgrounds with functional accents.
- **Readwise** — Knowledge management tool with a focus on readability and a serene, academic-leaning design with understated colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment: #ffffeb;
  --color-ink: #1a1a1a;
  --color-forest-canopy: #034f46;
  --color-pale-lavender: #f0d7ff;
  --color-stone: #e4e4d0;
  --color-charcoal-text: #222222;
  --color-muted-ash: #8a8a80;
  --color-white: #ffffff;
  --color-sunburst: #ffa946;

  /* Typography — Font Families */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-eb-garamond: 'EB Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-color-emoji: 'Apple Color Emoji', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-subheading-lg: 22px;
  --leading-subheading-lg: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 0.85;
  --tracking-display: -0.48px;
  --text-display-xl: 120px;
  --leading-display-xl: 0.85;
  --tracking-display-xl: -0.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-128: 128px;
  --spacing-168: 168px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 80px;
  --radius-full-3: 992px;
  --radius-full-4: 1000px;
  --radius-full-5: 1600px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-badges: 992px;
  --radius-global: 1600px;
  --radius-images: 40px;
  --radius-inputs: 14px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-parchment-canvas: #ffffeb;
  --surface-ink-content-block: #1a1a1a;
  --surface-forest-canopy-feature-block: #034f46;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment: #ffffeb;
  --color-ink: #1a1a1a;
  --color-forest-canopy: #034f46;
  --color-pale-lavender: #f0d7ff;
  --color-stone: #e4e4d0;
  --color-charcoal-text: #222222;
  --color-muted-ash: #8a8a80;
  --color-white: #ffffff;
  --color-sunburst: #ffa946;

  /* Typography */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-eb-garamond: 'EB Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-color-emoji: 'Apple Color Emoji', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-subheading-lg: 22px;
  --leading-subheading-lg: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 0.85;
  --tracking-display: -0.48px;
  --text-display-xl: 120px;
  --leading-display-xl: 0.85;
  --tracking-display-xl: -0.48px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-128: 128px;
  --spacing-168: 168px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 80px;
  --radius-full-3: 992px;
  --radius-full-4: 1000px;
  --radius-full-5: 1600px;
}
```
