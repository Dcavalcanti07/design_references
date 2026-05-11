# Yung Studio — Style Reference
> Monochromatic Command Center. Pure black canvas where sharp white elements punctuate with precision and ample negative space.

**Theme:** dark

This design system presents a stark, high-contrast aesthetic, mimicking a digital command console. Its core identity is built on pure black and white, creating immediate visual impact. The generous negative space and tight letter-spacing in headlines maintain an air of intentional precision, while the signature 9999px pill-shaped buttons introduce a single, playful soft edge.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page backgrounds, card backgrounds, text on white buttons – the foundational darkness. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, button backgrounds, interactive elements – the dominant light element creating high contrast. |
| Accent Violet | `#c692ff` | `--color-accent-violet` | Subtle background accents, specific contextual highlights; provides the only chromatic color for visual differentiation. |

## Tokens — Typography

### PolySans-Slim — Body text, smaller headings, supporting information, links, and various content elements. Its uniform weight contributes to a calm, readable tone across varied text sizes. · `--font-polysans-slim`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 20px, 30px, 40px
- **Line height:** 1.00, 1.10, 1.35
- **Letter spacing:** -0.0100em
- **Role:** Body text, smaller headings, supporting information, links, and various content elements. Its uniform weight contributes to a calm, readable tone across varied text sizes.

### PolySans-Neutral — Display headings and prominent interactive elements like buttons. The extremely tight letter-spacing at large sizes creates a dense, impactful visual block rather than sprawling text, like a bold declaration. · `--font-polysans-neutral`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 60px, 160px
- **Line height:** 0.90, 1.10
- **Letter spacing:** -0.0200em
- **Role:** Display headings and prominent interactive elements like buttons. The extremely tight letter-spacing at large sizes creates a dense, impactful visual block rather than sprawling text, like a bold declaration.

### PolySans-Bulky — Specialized links and secondary headings. This family variation offers a bulkier form factor for specific emphasis at a mid-range size. · `--font-polysans-bulky`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 28px
- **Line height:** 1.01
- **Letter spacing:** -0.0100em
- **Role:** Specialized links and secondary headings. This family variation offers a bulkier form factor for specific emphasis at a mid-range size.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.35 | — | `--text-body` |
| body-lg | 20px | 1.1 | — | `--text-body-lg` |
| subheading | 28px | 1.01 | -0.28px | `--text-subheading` |
| heading | 30px | 1.1 | -0.3px | `--text-heading` |
| heading-lg | 40px | 1 | -0.4px | `--text-heading-lg` |
| display | 60px | 0.9 | -1.2px | `--text-display` |
| display-xl | 160px | 0.9 | -3.2px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 14 | 14px | `--spacing-14` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 68 | 68px | `--spacing-68` |
| 110 | 110px | `--spacing-110` |
| 124 | 124px | `--spacing-124` |
| 222 | 222px | `--spacing-222` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 9999px |
| default | 10px |

### Layout

- **Section gap:** 60-124px
- **Card padding:** 0px
- **Element gap:** 20-24px

## Components

### Primary Action Button
**Role:** Interactive element

White background (`#ffffff`), black text (`#000000`). Fully rounded with `9999px` border-radius. Generous padding: `31.968px` top, `22.032px` bottom, `49.968px` sides. Uses PolySans-Neutral font, weight 400, for clear call to action.

### Naked Content Card
**Role:** Content container

Transparent background (`rgba(0, 0, 0, 0)`) with `0px` border-radius. No box-shadow or padding, integrating seamlessly into the negative space. Used for showcasing work items or article previews.

### Text Link
**Role:** Navigation/Internal link

Uses PolySans-Slim for general links, or PolySans-Bulky at 28px for prominent links. Text color is `Ghost White` (`#ffffff`) against `Midnight Void` (`#000000`), no underline by default.

### Header Logo
**Role:** Brand identity

Uses PolySans-Slim at a 20px size, weight 400, `Ghost White` (`#ffffff`), positioned top-left on the `Midnight Void` (`#000000`) background.

## Do's and Don'ts

### Do
- Maintain a strict achromatic palette, using only `Midnight Void` (#000000) for backgrounds and `Ghost White` (#ffffff) for primary foreground elements.
- Apply `9999px` border-radius to all interactive element buttons for a consistent pill shape.
- Utilize PolySans-Neutral with -0.0200em letter-spacing for all significant headings to create a dense, impactful typographic appearance.
- Implement `--obe` (#c692ff) sparingly as the sole chromatic accent, allowing it to highlight specific backgrounds or subtle contextual elements.
- Ensure generous `50px` horizontal padding for content sections and `20-24px` vertical spacing between elements to preserve ample negative space.
- Employ PolySans-Slim as the default font for all body copy and most secondary text at weight 400, ensuring clear readability across sizes.

### Don't
- Avoid introducing any additional saturated colors beyond the designated `--ube` (#c692ff) to prevent diluting the distinct monochrome aesthetic.
- Do not use box-shadows or drop shadows; depth is implied solely through stark contrast and generous negative space.
- Refrain from deviating from the specified PolySans typefaces; custom fonts are a core identifier, and system defaults would undermine the brand.
- Do not add borders or background colors to content cards; they should appear as seamless blocks of text on the `Midnight Void` background.
- Avoid using radii other than `0px` for content containers and `9999px` for buttons, to maintain precision and the signature rounded forms.
- Do not clutter content sections; maintain the spacious `50px` horizontal padding and ample vertical element gaps to preserve legibility and impact.

## Imagery

This site features a clean visual language predominantly based on illustration and graphic elements, with minimal and direct application. The hero section displays large, custom, playful illustrations in pure white on a black background, with a hand-drawn, almost explosive quality, acting as a direct visual representation of the 'Yung' brand. The overall impression is that imagery serves a decorative, brand-identity building purpose rather than explanatory content, with a high visual density only in a dedicated hero area, transitioning to text-dominant content. Icons are minimal, represented by the white hamburger menu, suggesting a clean, outlined style. No photography is visible, reinforcing a graphic-first approach.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#ffffff`
- Background: `#000000`
- Button Background: `#ffffff`
- Button Text: `#000000`
- Accent: `#c692ff`

### 3-5 Example Component Prompts
1. **Create a Primary Action Button:** Text 'Get Started', background `Ghost White` (`#ffffff`), text `Midnight Void` (`#000000`), `9999px` border-radius. Padding: `31.968px` top, `22.032px` bottom, `49.968px` left and right. Font: PolySans-Neutral, weight 400, size 16px, `1.1` lineHeight, `-0.0200em` letter-spacing.
2. **Design a Hero Section:** Full-bleed `Midnight Void` (`#000000`) background. Headline 'We Define Tomorrow' in PolySans-Neutral, size 160px, weight 400, `0.9` lineHeight, `-0.0200em` letter-spacing, color `Ghost White` (`#ffffff`). Add a sub-headline 'Strategy to Action' in PolySans-Slim, size 40px, weight 400, `1.0` lineHeight, `-0.0100em` letter-spacing, color `Ghost White` (`#ffffff`). A `20px` `marginBottom` should separate headline from sub-headline.
3. **Implement a Content Block:** Background `Midnight Void` (`#000000`). Title 'Featured Work' in PolySans-Slim, size 30px, weight 400, `1.1` lineHeight, `-0.0100em` letter-spacing, color `Ghost White` (`#ffffff`). Body text 'Our latest projects blend design thinking with bold execution.' in PolySans-Slim, size 20px, weight 400, `1.1` lineHeight, `-0.0100em` letter-spacing, `Ghost White` color. Use `50px` horizontal padding for the block and `24px` `marginBottom` between title and body.
4. **Create a Text Link:** Text 'Learn More', font PolySans-Bulky, size 28px, weight 400, `1.01` lineHeight, `-0.0100em` letter-spacing, color `Ghost White` (`#ffffff`). No underline, no background, and no padding.

## Similar Brands

- **Akin Gump** — Stark black and white color scheme; emphasis on strong typography and ample negative space for a premium, editorial feel.
- **Baidu Ventures** — Dominant dark background with high-contrast white text, using spacious layouts and minimal visual clutter.
- **Huge Inc.** — Bold, expressive typography at large sizes often against a dark background, asserting brand identity through text.
- **Figma (dark mode)** — Monochromatic focus with a single accent color for interactive elements, maintaining clarity within a dark interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #ffffff;
  --color-accent-violet: #c692ff;

  /* Typography — Font Families */
  --font-polysans-slim: 'PolySans-Slim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-neutral: 'PolySans-Neutral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-bulky: 'PolySans-Bulky', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 20px;
  --leading-body-lg: 1.1;
  --text-subheading: 28px;
  --leading-subheading: 1.01;
  --tracking-subheading: -0.28px;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --tracking-heading: -0.3px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.4px;
  --text-display: 60px;
  --leading-display: 0.9;
  --tracking-display: -1.2px;
  --text-display-xl: 160px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-110: 110px;
  --spacing-124: 124px;
  --spacing-222: 222px;

  /* Layout */
  --section-gap: 60-124px;
  --card-padding: 0px;
  --element-gap: 20-24px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 9999px;
  --radius-default: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #ffffff;
  --color-accent-violet: #c692ff;

  /* Typography */
  --font-polysans-slim: 'PolySans-Slim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-neutral: 'PolySans-Neutral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-bulky: 'PolySans-Bulky', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 20px;
  --leading-body-lg: 1.1;
  --text-subheading: 28px;
  --leading-subheading: 1.01;
  --tracking-subheading: -0.28px;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --tracking-heading: -0.3px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.4px;
  --text-display: 60px;
  --leading-display: 0.9;
  --tracking-display: -1.2px;
  --text-display-xl: 160px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -3.2px;

  /* Spacing */
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-110: 110px;
  --spacing-124: 124px;
  --spacing-222: 222px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 9999px;
}
```
