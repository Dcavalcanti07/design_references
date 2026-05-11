# Made With Gsap — Style Reference
> High-contrast digital canvas.

**Theme:** light

Made With Gsap leverages a high-contrast aesthetic with stark white and deep black surfaces, punctuated by a single neon green. Typography is large, bold, and tightly tracked, creating a commanding, almost aggressive presence that draws immediate attention. Component styling is sharp and minimal, favoring crisp edges and functional design over decorative flourishes. The overall impression is one of directness, efficiency, and a powerful, energetic feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f1f1f1` | `--color-canvas-white` | Primary page backgrounds, button fills, neutral text |
| Midnight Ink | `#121212` | `--color-midnight-ink` | Primary text, deep surface backgrounds, borders |
| Accent Green | `#c9fe6e` | `--color-accent-green` | Primary action buttons, vibrant highlights, iconic elements |
| Deep Gray | `#252525` | `--color-deep-gray` | Subtle border colors, background for card elements |
| Muted Ash | `#777777` | `--color-muted-ash` | Secondary text, subtle instructional copy |
| Pure White | `#ffffff` | `--color-pure-white` | Highlighted text on dark backgrounds, inverse styling for contrast |

## Tokens — Typography

### LayGrotesk — All textual content, from headings to body text and navigation. The very tight letter spacing, especially at larger sizes, creates a highly condensed and impactful visual block for headlines. The generous line heights compensate for readability at smaller sizes. The custom font features indicate a strong typographic brand identity. · `--font-laygrotesk`
- **Substitute:** Inter
- **Weights:** 500, 700
- **Sizes:** 12px, 18px, 22px, 40px, 44px, 65px, 100px, 114px, 250px
- **Line height:** 0.80, 0.88, 0.90, 1.00, 1.08, 1.11, 1.20, 1.30, 2.28
- **Letter spacing:** -0.0400em at 250px, -0.0300em at 114px, -0.0200em at 65px and 44px, -0.0100em at 40px and 22px
- **OpenType features:** `"cswh", "dlig", "hlig", "kern", "liga", "ss02"`
- **Role:** All textual content, from headings to body text and navigation. The very tight letter spacing, especially at larger sizes, creates a highly condensed and impactful visual block for headlines. The generous line heights compensate for readability at smaller sizes. The custom font features indicate a strong typographic brand identity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.08 | — | `--text-caption` |
| body-sm | 18px | 1.08 | — | `--text-body-sm` |
| body | 22px | 1.08 | — | `--text-body` |
| body-lg | 40px | 1.08 | — | `--text-body-lg` |
| heading-sm | 44px | 1.08 | — | `--text-heading-sm` |
| heading | 65px | 1.08 | — | `--text-heading` |
| heading-lg | 100px | 1.08 | — | `--text-heading-lg` |
| display-sm | 114px | 1.08 | — | `--text-display-sm` |
| display | 250px | 1.08 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| links | 2px |
| buttons | 2px |

### Layout

- **Section gap:** 30px
- **Card padding:** 25px
- **Element gap:** 15px

## Components

### Primary Action Button
**Role:** Call to action button

Filled with Accent Green (#c9fe6e), text in Midnight Ink (#121212), and sharp 2px border radius. Padding of 0px top/bottom and 16px left/right, emphasizing horizontal space for the highly tracked text.

### Hero Outline Button
**Role:** Secondary action button/ghost button

No background, White (#f1f1f1) text with a 1px border in Midnight Ink (#121212), 0px border-radius, 0px top/bottom padding and 15px left/right padding. Used for subtle actions without drawing too much attention.

### Navigation Link Button
**Role:** Navigation link

White text (#f1f1f1) on a transparent background, with a 2px border-radius. No padding is explicitly set on navigation links themselves, relying on external spacing.

### Dark Card
**Role:** Content container for features or examples

Solid black background (#121212) with a pronounced 12px border radius, no shadow. Internal padding of 25px on all sides provides ample breathing room for content within the dark module.

### Content Input
**Role:** User input field

Transparent background with Pure White (#ffffff) text and a white border. No padding or border radius specified, implying a flat, integrated appearance.

## Do's and Don'ts

### Do
- Use Midnight Ink (#121212) for all primary text on Canvas White (#f1f1f1) backgrounds, ensuring maximum contrast.
- Apply LayGrotesk, weights 500 or 700, with a tight letter spacing appropriate for its size, especially for all headlines and UI labels.
- Elevate primary calls to action with Accent Green (#c9fe6e) filled buttons with Midnight Ink (#121212) text and 2px radius.
- Maintain high contrast throughout the UI, pairing Canvas White (#f1f1f1) with Midnight Ink (#121212) for backgrounds and text.
- Utilize 12px border-radius for cards and content modules, and 2px for buttons and interactive elements, for consistent shape language.
- Prioritize explicit vertical spacing of 7px for elements within sections and 15px as a general element gap.

### Don't
- Avoid using multiple chromatic colors; limit color accents strictly to Accent Green (#c9fe6e).
- Do not use generic system fonts; always specify LayGrotesk with its exact weights and features.
- Do not introduce soft shadows or excessive gradients; rely on crisp edges and high-contrast color blocks for visual separation.
- Do not use subtle variations of neutral colors; stick to the defined Canvas White (#f1f1f1), Midnight Ink (#121212), and Deep Gray (#252525).
- Do not use large, rounded buttons or cards; maintain the hard-edged, minimalist aesthetic with smaller border radii.

## Agent Prompt Guide

Quick Color Reference:
- text: #121212
- background: #f1f1f1
- border: #121212
- accent: #c9fe6e
- primary action: #c9fe6e (filled action)

Example Component Prompts:
- Create a hero headline: 'A collection of JS effects Made With Gsap' in LayGrotesk, weight 700, size 100px, line-height 0.88, letter-spacing -0.0200em, color Midnight Ink (#121212) on a Midnight Ink background.
- Design a primary action button: text 'Start learning now' in LayGrotesk, weight 700, size 18px, color Midnight Ink (#121212), on an Accent Green (#c9fe6e) background, with 2px border radius, 0px vertical padding, 16px horizontal padding.
- Construct a dark content card: Midnight Ink (#121212) background, 12px border radius, 25px padding on all sides, with body text in Pure White (#ffffff) using LayGrotesk weight 500 at 18px.
- Create a ghost 'Explore collection' button: text 'Explore collection' in LayGrotesk, weight 700, size 18px, color Canvas White (#f1f1f1), transparent background, 0px border radius, 0px vertical padding, 15px horizontal padding, with a 1px border in Midnight Ink (#121212).

## Similar Brands

- **Stripe** — Uses a similar approach of sharp UI, high contrast, and a single, vibrant accent color against a largely monochrome palette to highlight key actions and information.
- **Figma** — Shares the use of strong typography, clean spacious layouts, and functional components without heavy ornamentation, relying on typography and color contrast for hierarchy.
- **Vercel** — Employs a sophisticated dark mode with high-contrast text, minimalist controls, and a focus on code/developer-centric aesthetic, similar to the direct and functional feel here.
- **Linear** — Features a tight, productivity-oriented UI with compact typography, clean lines, and a deliberate use of color for functional elements rather than decorative, creating a fast and efficient tool feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f1f1f1;
  --color-midnight-ink: #121212;
  --color-accent-green: #c9fe6e;
  --color-deep-gray: #252525;
  --color-muted-ash: #777777;
  --color-pure-white: #ffffff;

  /* Typography — Font Families */
  --font-laygrotesk: 'LayGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.08;
  --text-body-sm: 18px;
  --leading-body-sm: 1.08;
  --text-body: 22px;
  --leading-body: 1.08;
  --text-body-lg: 40px;
  --leading-body-lg: 1.08;
  --text-heading-sm: 44px;
  --leading-heading-sm: 1.08;
  --text-heading: 65px;
  --leading-heading: 1.08;
  --text-heading-lg: 100px;
  --leading-heading-lg: 1.08;
  --text-display-sm: 114px;
  --leading-display-sm: 1.08;
  --text-display: 250px;
  --leading-display: 1.08;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 25px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-links: 2px;
  --radius-buttons: 2px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f1f1f1;
  --color-midnight-ink: #121212;
  --color-accent-green: #c9fe6e;
  --color-deep-gray: #252525;
  --color-muted-ash: #777777;
  --color-pure-white: #ffffff;

  /* Typography */
  --font-laygrotesk: 'LayGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.08;
  --text-body-sm: 18px;
  --leading-body-sm: 1.08;
  --text-body: 22px;
  --leading-body: 1.08;
  --text-body-lg: 40px;
  --leading-body-lg: 1.08;
  --text-heading-sm: 44px;
  --leading-heading-sm: 1.08;
  --text-heading: 65px;
  --leading-heading: 1.08;
  --text-heading-lg: 100px;
  --leading-heading-lg: 1.08;
  --text-display-sm: 114px;
  --leading-display-sm: 1.08;
  --text-display: 250px;
  --leading-display: 1.08;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
