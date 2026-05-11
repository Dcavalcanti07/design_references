# Petertarka — Style Reference
> Gray canvas, vivid art

**Theme:** light

Petertarka's visual system evokes a gallery of abstract works: a muted, almost achromatic canvas where individual 'art pieces' (product showcases) are presented in their own vibrantly colored, often 3D-rendered, contexts. The UI itself is minimalist, relying on precise typography and stark line borders rather than heavy shadows or complex gradients. The spacious layout creates a sense of gravitas and focuses attention on the central visual content, punctuated by crisp, interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Phantom Ink | `#000000` | `--color-phantom-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Fog Bound | `#d8d8d8` | `--color-fog-bound` | Subtle card and section borders, soft dividers |
| Canvas Gray | `#f0f0f0` | `--color-canvas-gray` | Card backgrounds, secondary surface areas |
| Paper White | `#ffffff` | `--color-paper-white` | Navigation text, high-contrast borders |
| Sky Gradient | `linear-gradient(rgb(119, 193, 229) 0%, rgb(142, 208, 239) 100%)` | `--color-sky-gradient` | Decorative background gradient, used for specific showcased projects |

## Tokens — Typography

### GT America — The primary typeface for all textual content. Its varied weights are used to establish hierarchy, with lighter weights (200, 300) lending a contemporary, understated feel to headings and an almost monospaced quality to body text at smaller sizes. · `--font-gt-america`
- **Substitute:** Inter
- **Weights:** 200, 300, 400
- **Sizes:** 16px, 21px, 38px
- **Line height:** 1.00, 1.31, 1.32, 2.37
- **Role:** The primary typeface for all textual content. Its varied weights are used to establish hierarchy, with lighter weights (200, 300) lending a contemporary, understated feel to headings and an almost monospaced quality to body text at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.32 | — | `--text-caption` |
| body-sm | 21px | 1.32 | — | `--text-body-sm` |
| body | 38px | 1.3 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 45 | 45px | `--spacing-45` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Card padding:** 45px
- **Element gap:** 6px

## Components

### Main Navigation Button
**Role:** Hamburger menu button for main navigation

Ghost button with no background: rgba(0, 0, 0, 0). Uses a 1px #000000 border and no border radius (0px). Padding is 15px top/bottom, 10px left/right. Text color is #000000, font GT America, weight 400.

### Project Card
**Role:** Container for individual project showcases

A monolithic rectangular block with no border radius (0px) and no shadows. Background is #f0f0f0. Internal padding is 45px on all sides. Content includes headings, subheadings, and occasionally date stamps. These cards are the 'canvas' for embedded rich media.

### Project Card - Transparent
**Role:** Alternative container for specific project showcases, overlays visual content

Similar to the standard Project Card but with a transparent background (rgba(0, 0, 0, 0)), allowing underlying visuals to show through. No border radius (0px) and no shadows. Internal padding is 45px on all sides.

## Do's and Don'ts

### Do
- Employ GT America for all typographic elements, prioritizing weights 200-400 for a precise feel.
- Maintain a strict 0px border-radius for all UI elements to uphold the stark, architectural aesthetic.
- Use #000000 for primary text and critical interactive borders.
- Utilize #f0f0f0 for all background surfaces of content blocks and cards.
- Ensure generous padding of 45px within card-like components to frame content effectively.
- Construct layouts with substantial vertical separation, mirroring the ~720px section gaps found between project articles.
- Favor ghost-style interactive elements with stark #000000 borders and transparent backgrounds.

### Don't
- Avoid using curved borders or any border-radius greater than 0px.
- Do not introduce shadows or elevation effects; maintain a flat, layered appearance.
- Refrain from adding additional accent colors outside of the contextual usage within embedded content; the UI should remain achromatic.
- Do not use subtle variations of gray for text; stick to #000000 for all primary text content.
- Avoid dense or compact layouts; maintain ample whitespace for a gallery-like presentation.

## Imagery

This site prominently features highly stylized, often surreal 3D illustrations and renders as its core content. These visuals are typically contained within the 0px-radius project cards, occupying significant visual space. The imagery is diverse in color and composition, ranging from vibrant, cartoonish scenes to more abstract, textured pieces, with a strong emphasis on clean digital rendering. Product screenshots or photography are minimal, and when present, are integrated seamlessly into the rendered scenes. Icons are minimal, appearing only for UI elements (like the hamburger menu) in a simple, outlined style.

## Layout

The page adheres to a full-bleed grid layout, where content sections (project cards) span the full width of the viewport. There is no central max-width container, giving a sense of expansive space. The hero section is characterized by a prominent visual taking up a large portion of the initial viewport. Sections stack vertically with significant and consistent spacing, presenting a rhythmic, almost modular progression. Content within sections is often implicitly split into visual and textual areas, but the overall structure emphasizes the contained visual artwork. Navigation is minimal, typically a top-right hamburger menu. The layout feels like a vertical gallery, with each 'artwork' given ample room to breathe.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f0f0f0
border: #000000
accent: #77c1e5
primary action: no distinct CTA color

Example Component Prompts:
Create a primary heading for a project: 'Green Mountain Energy' in GT America, weight 300, size 38px, color #000000, line height 1.0.
Create a project card titled 'Formant.IO': Background #f0f0f0, 0px border-radius, 45px padding on all sides. Inside, display a text label '2022' using GT America, weight 400, size 16px, color #000000. Underneath, add the heading 'Formant.IO' using GT America, weight 300, size 38px, color #000000.
Create a navigation button: 'Commercial' text in GT America, weight 400, size 16px, color #000000. The button is ghost style with a background of rgba(0,0,0,0), a 1px solid #000000 border, 0px border-radius, and 15px top/bottom padding with 10px left/right padding.

## Similar Brands

- **B&O (Bang & Olufsen)** — Shared minimalist UI, stark typography, and focus on product as sculptural artwork against neutral backdrops.
- **Certain Apple marketing pages** — Use of large, isolated product renders and graphic elements on a spacious, almost empty canvas.
- **Anagram (design studio)** — Similar strong emphasis on high-quality, often abstract, visual content framed by a highly restrained and structured achromatic UI.
- **Herman Miller (product pages)** — Large, detailed imagery of product against clean, spacious backgrounds, with typography providing clear hierarchy.
- **Are.na** — Grid-based presentation of diverse visual content with minimal UI ornamentation and focus on content blocks.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-phantom-ink: #000000;
  --color-fog-bound: #d8d8d8;
  --color-canvas-gray: #f0f0f0;
  --color-paper-white: #ffffff;
  --color-sky-gradient: #77c1e5;
  --gradient-sky-gradient: linear-gradient(rgb(119, 193, 229) 0%, rgb(142, 208, 239) 100%);

  /* Typography — Font Families */
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.32;
  --text-body-sm: 21px;
  --leading-body-sm: 1.32;
  --text-body: 38px;
  --leading-body: 1.3;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-45: 45px;

  /* Layout */
  --card-padding: 45px;
  --element-gap: 6px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-phantom-ink: #000000;
  --color-fog-bound: #d8d8d8;
  --color-canvas-gray: #f0f0f0;
  --color-paper-white: #ffffff;
  --color-sky-gradient: #77c1e5;

  /* Typography */
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.32;
  --text-body-sm: 21px;
  --leading-body-sm: 1.32;
  --text-body: 38px;
  --leading-body: 1.3;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-45: 45px;
}
```
