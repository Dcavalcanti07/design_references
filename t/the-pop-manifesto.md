# The Pop Manifesto — Style Reference
> digital zine, high contrast

**Theme:** dark

The Pop Manifesto's visual language is a bold, high-contrast digital zine. It features stark black typography against vibrant, saturated backgrounds, often utilizing a single dominant color per section. The typography leans into a strong, editorial aesthetic with precise tracking and a clear hierarchy. Components are minimal, relying on color blocking and crisp text to define interactions rather than subtle shadows or rounded forms.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Neon Pink | `#ff29f1` | `--color-neon-pink` | Primary background for various sections, providing a high-energy stage for content |
| Electric Blue | `#287aea` | `--color-electric-blue` | Alternate background color, creating distinct content blocks and providing visual interest |

## Tokens — Typography

### Roobert — Body text, navigation, and subheadings; its geometric, sharp quality contributes to the editorial feel. · `--font-roobert`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 15px, 22px, 33px
- **Line height:** 0.70, 1.20
- **Letter spacing:** normal
- **Role:** Body text, navigation, and subheadings; its geometric, sharp quality contributes to the editorial feel.

### Roobert Bold — Small headings and emphasis; provides a more opinionated version of the primary typeface without increasing visual weight with a heavier font weight. · `--font-roobert-bold`
- **Substitute:** Inter Bold
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Small headings and emphasis; provides a more opinionated version of the primary typeface without increasing visual weight with a heavier font weight.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 15px | 1.2 | — | `--text-body-sm` |
| body | 22px | 1.2 | — | `--text-body` |
| body-lg | 33px | 1.2 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 9 | 9px | `--spacing-9` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Card padding:** 25px
- **Element gap:** 20px

## Components

### Section Headline
**Role:** Main content headings for distinct page sections.

Text uses Roobert at 33px, weight 400, color Midnight Ink (#000000), line height 0.70.

### Navigation Link
**Role:** Top-level navigation items.

Text uses Roobert at 15px, weight 400, color Midnight Ink (#000000), line height 1.20. No distinct background or border.

### Image Card
**Role:** Displays photographic content with prominent captions.

An image with no border-radius, followed by Roobert text at 15px, color Midnight Ink (#000000) for caption, and 25px top/bottom padding.

### Interactive Link Block
**Role:** Clickable blocks usually containing descriptive text.

Background is highly saturated (e.g., Neon Pink #ff29f1 or Electric Blue #287aea), text uses Roobert at 15px or 22px, weight 400, color Midnight Ink (#000000), with 25px top/bottom padding.

### Sub-Navigation Link
**Role:** Secondary navigation or category links.

Text uses Roobert at 12px, weight 400, color Midnight Ink (#000000), line height 1.20, with 5px left padding and 9px top padding.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all text and interactive borders to ensure maximum contrast.
- Implement Roobert 400 as the sole typeface, varying size and line height for hierarchy.
- Employ highly saturated, single-color backgrounds like Neon Pink (#ff29f1) or Electric Blue (#287aea) for distinct content blocks, ensuring visual separation.
- Maintain hard, 0px border-radius for all elements, including images and interactive areas.
- Utilize 291px for vertical section gaps to create generous negative space and a spacious feel.
- Apply 20px as the standard horizontal and vertical gap between related elements.
- Assume all interactivity is communicated through text link styles or color block background changes, not subtle hover states or shadows.

### Don't
- Do not use subtle background gradients or textures; stick to flat, vibrant color blocks.
- Avoid softer, desaturated or pastel colors, which would dilute the high-contrast aesthetic.
- Do not introduce rounded corners; all shapes should be sharp 0px radius to preserve the crisp, editorial look.
- Refrain from using drop shadows or complex elevation schemes; rely on color blocking for visual hierarchy.
- Do not use varied typography weights; Roobert 400 is the only weight. Change text size and line height for hierarchy.
- Do not use excessive white space within content blocks; reserve large spacing values for section separation only.
- Do not introduce decorative icons unless they are bold, single-color, and contribute explicitly to the high-contrast identity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Electric Blue Canvas | `#287aea` | Base page background or primary content block background. |
| 1 | Neon Pink Surface | `#ff29f1` | Elevated content block background, providing strong visual distinction from the canvas. |

## Imagery

This site features a mix of photography styles: studio portraits with bold, single-color backdrops (like electric blue), candid lifestyle shots, and black-and-white portraits. Images are mostly contained within rectangular frames, with sharp edges, functioning as content rather than decorative backgrounds. They are high-density, taking up significant visual space to act as focal points.

## Layout

The page uses a full-bleed layout, where content sections stretch the full viewport width. The hero section features a prominent, centered headline over a vibrant background. Content frequently uses a multi-column grid, prominently a 3-column layout for images and associated text. Sections are separated by large vertical gaps (291px) and distinct, solid color changes, creating a strong, block-like rhythm. Navigation is minimal, likely a fixed top bar or simple links within the header and footer.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ff29f1
border: #000000
accent: #287aea
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section with a Neon Pink background, a main headline 'THE POP MANIFESTO' in Midnight Ink, Roobert 33px weight 400, line height 0.70. Below it, a sub-navigation link 'SHOP' in Midnight Ink, Roobert 15px weight 400, line height 1.20.
Create a content block with an Electric Blue background, featuring three image cards laid out horizontally. Each card has a full-bleed image and a caption 'Interview' in Midnight Ink, Roobert 15px, weight 400, with 25px padding above and below.

## Similar Brands

- **032c** — High-contrast, bold typography against stark, often single-color backgrounds, resembling an editorial layout.
- **Paper Magazine** — Editorial aesthetic with a focus on strong visual hierarchy and unconventional use of color blocking for content sections.
- **Dazed Digital** — Full-bleed imagery, strong typographic statements, and a high-fashion, art-oriented visual approach with maximal contrast.
- **SSENSE** — Emphasis on product photography and a clean, direct editorial style that uses typography to create impact.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-neon-pink: #ff29f1;
  --color-electric-blue: #287aea;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-bold: 'Roobert Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 15px;
  --leading-body-sm: 1.2;
  --text-body: 22px;
  --leading-body: 1.2;
  --text-body-lg: 33px;
  --leading-body-lg: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Layout */
  --card-padding: 25px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-none: 0px;

  /* Surfaces */
  --surface-electric-blue-canvas: #287aea;
  --surface-neon-pink-surface: #ff29f1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-neon-pink: #ff29f1;
  --color-electric-blue: #287aea;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-bold: 'Roobert Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 15px;
  --leading-body-sm: 1.2;
  --text-body: 22px;
  --leading-body: 1.2;
  --text-body-lg: 33px;
  --leading-body-lg: 1.2;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
}
```
