# Chantlings — Style Reference
> Moonlit Forest Floor: glowing forms in the deep dark

**Theme:** dark

Chantlings uses a nocturnal, atmospheric design language, evoking a digital instrument in a dark, quiet room. The canvas is deep black, allowing subtle gradients and glowing elements to emerge. Typography is highly refined, with an elegant serif for headlines that whispers rather than shouts. Interactive elements are minimal, often ghosted, with one vivid orange accent color for fills, giving a sense of warmth and focused interactivity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Noir | `#000000` | `--color-midnight-noir` | Page background, primary surface for most elements — creates a deep, infinite canvas |
| Ghostly Gray | `#333333` | `--color-ghostly-gray` | Muted text, inactive borders, general UI elements and ghost button text |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text color, background for outlined buttons, secondary borders — creates sharp contrast against the dark canvas |
| Shadow Tint | `#222222` | `--color-shadow-tint` | Subtle borders and muted accents, lighter than Ghostly Gray |
| Active Fire | `#ff8800` | `--color-active-fire` | Filled action buttons, interactive elements — a warm, vivid orange that provides a focused point of interaction |
| Subtle Glow | `#ffaa20` | `--color-subtle-glow` | Outlined action borders, decorative link accents — a slightly softer orange, suggesting a secondary interactive state or highlight |

## Tokens — Typography

### Mija webfont — All text: headlines use weight 300 for a distinguished, unassertive presence; body text and links are also from this family to maintain a consistent, refined voice. · `--font-mija-webfont`
- **Substitute:** Lora, Playfair Display
- **Weights:** 100, 300
- **Sizes:** 14px, 20px, 24px, 25px, 32px
- **Line height:** 0.80, 0.83, 1.00, 1.06, 1.33, 1.42, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** All text: headlines use weight 300 for a distinguished, unassertive presence; body text and links are also from this family to maintain a consistent, refined voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 20px | 1.42 | — | `--text-body` |
| subheading | 24px | 1.06 | — | `--text-subheading` |
| display | 32px | 0.8 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 100 | 100px | `--spacing-100` |
| 108 | 108px | `--spacing-108` |
| 196 | 196px | `--spacing-196` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 50px |
| default | 0px |

### Layout

- **Section gap:** 100px
- **Card padding:** 18px
- **Element gap:** 10px

## Components

### Ghost Navigation Button
**Role:** Header navigation, secondary actions

Transparent background, Ghostly Gray (#333333) text and 1px border, 0px border radius, 18px padding for a minimalist, integrated look. Font is Mija, weight is not explicitly stated but inherits body style.

### Primary Action Button
**Role:** Main calls to action

Active Fire (#ff8800) background, Canvas White (#ffffff) text, 50px border radius for a distinctive pill shape, 18px vertical and 23px horizontal padding. Font is Mija.

### Outlined Accent Link
**Role:** Secondary links with visual emphasis

Transparent background, Subtle Glow (#ffaa20) text and 1px border, 0px border radius, with 100px horizontal padding, often used in decorative contexts. Font is Mija.

### App Store Download Button
**Role:** Directing users to download the app

Features a transparent background with a Canvas White (#ffffff) border, text, and icon. Uses an 18px vertical and 23px horizontal padding, with a 50px radius to match the primary button's pill shape. Font is Mija.

## Do's and Don'ts

### Do
- Prioritize deep Midnight Noir (#000000) for all main backgrounds to maintain the dark, atmospheric tone.
- Use Mija webfont weight 300 for all headlines and significant text at larger sizes (24px, 32px) to convey understated elegance.
- Apply a 50px border-radius to all primary action buttons for a consistent pill-shaped aesthetic.
- Use Active Fire (#ff8800) exclusively for filled primary calls to action to ensure visual hierarchy and warmth.
- Maintain generous sectionGap of 100px between major content blocks to create ample breathing room in the dark layout.
- Use Canvas White (#ffffff) for primary text and Ghostly Gray (#333333) for muted text and subtle UI elements, ensuring readability against the dark background.

### Don't
- Avoid using bright or light backgrounds for main content sections; the system relies on a dark theme.
- Do not introduce sharp, angular shapes for interactive elements; prefer soft curves or pill shapes for buttons.
- Refrain from heavy drop shadows or excessive elevation; the design system favors a flat, subtle luminescence.
- Do not clutter layouts; aim for comfortable density with 100px section gaps and clear, isolated element placement.
- Avoid generic sans-serif fonts; Mija's distinct serif style is central to the brand's sophisticated visual identity.
- Do not use multiple accent colors; concentrate on the Active Fire (#ff8800) and Subtle Glow (#ffaa20) palette for all interactive highlights.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Noir Canvas | `#000000` | Dominant page background, providing a deep, immersive context |

## Imagery

This site uses minimal, abstract, and stylized 3D graphics that seem to pulsate with a soft internal glow. The 'Chantlings' themselves appear as dark, bulbous, vaguely organic shapes with glowing orange internal elements, contained within a dark, almost sculptural environment. Imagery serves an atmospheric and symbolic role rather than explanatory content, blending seamlessly into the dark UI without sharp edges or heavy outlines. The iconography focuses on simple, outlined white forms against the dark background, maintaining a light footprint.

## Layout

The page uses a full-bleed, dark layout without a fixed max-width, allowing background elements to extend edge-to-edge. The hero section features a centered headline and description over a dark, atmospheric visual. Content sections maintain consistent vertical spacing of 100px, although specific internal content structures are minimal, mainly focusing on centered text blocks and a single mobile device visual. Navigation is handled by a minimal top-left logo and a hamburger menu icon on the top right, with no visible sticky header.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #333333
accent: #ffaa20
primary action: #ff8800 (filled action)

3-5 Example Component Prompts:
1. Create a hero section: Midnight Noir (#000000) background. Headline 'Chantlings' at 32px Mija weight 300, Canvas White (#ffffff). Subtext 'Explore tone and harmony...' at 20px Mija, Canvas White (#ffffff). Position prominently centered.
2. Create a Primary Action Button: #ff8800 background, #222222 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a ghost navigation button: Transparent background, Ghostly Gray (#333333) text, 1px Ghostly Gray (#333333) border, 0px border-radius, 18px padding, Mija font. Text 'Heart of Noise'.
4. Create a minimal text link: Canvas White (#ffffff) text using Mija font at 20px, with no explicit background or border, against a Midnight Noir (#000000) canvas. Text 'Press'.

## Similar Brands

- **Calm** — Uses a dark, immersive interface with subtle glow effects and a focus on atmospheric visuals to create a serene user experience.
- **Endel** — Employs dark backgrounds and abstract, often glowing, visual elements to represent sound and create an ambient, focused environment.
- **Headspace (dark mode)** — Similar approach to deep, dark backgrounds with gentle, outlined illustrations and minimal, friendly typography for a calming effect.
- **Arc Browser** — Embraces a highly customized, sometimes dark, UI with a focus on fluid interactions and subtle, integrated visual accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-noir: #000000;
  --color-ghostly-gray: #333333;
  --color-canvas-white: #ffffff;
  --color-shadow-tint: #222222;
  --color-active-fire: #ff8800;
  --color-subtle-glow: #ffaa20;

  /* Typography — Font Families */
  --font-mija-webfont: 'Mija webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 20px;
  --leading-body: 1.42;
  --text-subheading: 24px;
  --leading-subheading: 1.06;
  --text-display: 32px;
  --leading-display: 0.8;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-196: 196px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 18px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-full: 50px;

  /* Named Radii */
  --radius-buttons: 50px;
  --radius-default: 0px;

  /* Surfaces */
  --surface-midnight-noir-canvas: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-noir: #000000;
  --color-ghostly-gray: #333333;
  --color-canvas-white: #ffffff;
  --color-shadow-tint: #222222;
  --color-active-fire: #ff8800;
  --color-subtle-glow: #ffaa20;

  /* Typography */
  --font-mija-webfont: 'Mija webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 20px;
  --leading-body: 1.42;
  --text-subheading: 24px;
  --leading-subheading: 1.06;
  --text-display: 32px;
  --leading-display: 0.8;

  /* Spacing */
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-196: 196px;

  /* Border Radius */
  --radius-full: 50px;
}
```
