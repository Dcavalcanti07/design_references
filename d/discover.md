# Discover — Style Reference
> High-contrast typographic command center.

**Theme:** light

Fonts Ninja embraces a utilitarian, high-contrast aesthetic reminiscent of an advanced terminal interface, but set on a bright canvas. Typography is paramount, dominating with bold, blocky forms. A single vivid red accent is reserved exclusively for interactive elements, activating controls and signaling actions against an otherwise stark monochrome palette of pure black and white, softened by subtle cool grays. Components emphasize sharp edges and geometric precision, often with asymmetric rounding, creating a functional yet visually distinctive system.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ninja Red | `#ee585a` | `--color-ninja-red` | Primary action backgrounds, link accents, and subtle borders — this vivid red is the sole chromatic element, drawing immediate attention to interactive components and key information |
| Midnight Ink | `#121212` | `--color-midnight-ink` | Primary text, prominent headings, borders on cards and other surface elements, and icon fills. This deep almost-black provides high contrast against light backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Light Steel | `#dbdada` | `--color-light-steel` | Subtle background for UI elements, very light borders, and shadow tints, providing a slight elevation without heavy contrast |
| Slate Gray | `#8e8e93` | `--color-slate-gray` | Muted secondary text, nav items on secondary states, and less prominent borders, used for lower hierarchy information |
| Pure Black | `#000000` | `--color-pure-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### aeonikFont — aeonikFont — detected in extracted data but not described by AI · `--font-aeonikfont`
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 24px, 32px, 44px
- **Line height:** 1, 1.14, 1.15, 1.2, 1.5
- **Letter spacing:** -0.011
- **Role:** aeonikFont — detected in extracted data but not described by AI

### Aeonik Pro — The primary typeface for all text content, from large commanding headlines to small descriptive labels. Its geometric and confident character defines the brand's direct and digital aesthetic. The consistent negative letter spacing across all sizes adds to its modern, compact feel. · `--font-aeonik-pro`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.011
- **Role:** The primary typeface for all text content, from large commanding headlines to small descriptive labels. Its geometric and confident character defines the brand's direct and digital aesthetic. The consistent negative letter spacing across all sizes adds to its modern, compact feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading | 32px | 1.15 | — | `--text-heading` |
| display | 44px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 66 | 66px | `--spacing-66` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| links | 16px |
| buttons | 24px |
| input-filters | 32px |
| asymmetric-button-right | 0px 32px 32px 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(72, 72, 74, 0.16) 0px 2px 32px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Action Button (Filled)
**Role:** Main interactive element

Filled with Ninja Red (#ee585a), Canvas White (#ffffff) text, 24px border-radius, and 16px vertical, 24px horizontal padding. This is the main call to action.

### Asymmetrical Primary Action Button
**Role:** Prominent directional action

Filled with Ninja Red (#ee585a), Canvas White (#ffffff) text, with an asymmetric border-radius of 0px top-left, 32px top-right, 32px bottom-right, and 0px bottom-left. Padding is 16px vertical, 24px horizontal.

### Ghost Button (Text)
**Role:** Secondary action or navigation link

Transparent background, Pure Black (#000000) text, no border-radius or padding, allowing text to seamlessly integrate into content.

### Font Display Card
**Role:** Content container for font examples

Transparent background, no shadow, no padding, 0px border-radius. Displays font examples with text in Midnight Ink (#121212).

### Feature Card
**Role:** Elevated content block

Canvas White (#ffffff) background, 32px border-radius, 48px vertical and 56px horizontal padding. Features no shadow, maintaining a flat aesthetic.

### Filter Badge (Text)
**Role:** Informational tag or filter option

Transparent background, Midnight Ink (#121212) text, no border-radius or padding. Used for categorical labeling or filtering options without visual weight.

## Do's and Don'ts

### Do
- Prioritize Aeonik Pro for all typography, applying -0.011em letter spacing across all sizes to maintain a compact aesthetic.
- Use Ninja Red (#ee585a) exclusively for primary interactive elements and key highlight text; avoid using it for decorative purposes.
- Maintain a high-contrast palette: Midnight Ink (#121212) for primary text and Canvas White (#ffffff) for backgrounds.
- Apply 32px radius for cards and larger container elements, and 24px for primary buttons and input fields.
- Utilize 10px as the default element gap for inline items and small vertical spacing between text blocks.
- Employ consistent 16px vertical and 24px horizontal padding for all filled buttons.
- Ensure all interactive elements and links use either Ninja Red (#ee585a) or Pure Black (#000000) for distinct visual feedback.

### Don't
- Do not introduce new chromatic colors; Ninja Red (#ee585a) is the only allowed accent color.
- Avoid heavy shadows or gradients; rely on color contrast and subtle background shades like Light Steel (#dbdada) for visual depth.
- Do not deviate from the specified asymmetric border-radius of 0px 32px 32px 0px for directional or 'call to action' buttons.
- Do not use type weights outside of 400, 500, or 700 for Aeonik Pro.
- Do not use generic button styles; always apply specific padding, radius, and color tokens from the defined components.
- Avoid complex component compositions; prefer simple, clear UI elements with minimal ornamentation.
- Do not introduce excessive spacing; maintain the compact density using elementGap of 10px and sectionGap of 32px.

## Imagery

This design system prioritizes a 'UI first' approach with minimal decorative imagery. When present, imagery consists of font specimen examples, often monochromatic letterforms. Iconography is minimalist, outlined, and uses the Midnight Ink color, serving purely functional roles. There are no photographs, complex illustrations, or 3D renders. The focus remains on typographic content and clean interface elements.

## Layout

The page structure utilizes a full-bleed model with content centered within a logical maximum width (though not explicitly constrained). The hero section features a large, stark headline against the light canvas. Sections are typically visually separated by consistent vertical spacing of 32px. Content is arranged in flexible card grids, often 3-column, allowing for dense information display. Navigation is a simple top bar with minimal links. The layout feels structured and spacious without being sparse, using white space to highlight content blocks.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #121212
- background: #ffffff
- border: #121212
- accent: #ee585a
- primary action: #ee585a (filled action)

**3-5 Example Component Prompts:**
- Create a Hero Headline: Use Aeonik Pro, 44px size, Midnight Ink (#121212) text, 1.0 line height, -0.011em letter spacing. Text: 'FONTS NINJA'.
- Create a Primary Action Button: #ee585a background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a Feature Card: Canvas White (#ffffff) background, 32px border-radius, 48px vertical and 56px horizontal padding. Content includes Aeonik Pro 16px Midnight Ink (#121212) for body text and 24px for headings.
- Create a Ghost Navigation Link: No background, Pure Black (#000000) text (Aeonik Pro 16px), no padding, no border-radius. Text: 'Bookmarks'.

## Similar Brands

- **Fonts.com** — High-contrast typographic-focused interface with clear cards for font display.
- **Typewolf** — Dominant use of bold, large typography on a light background, emphasizing type examples over other visuals.
- **Google Fonts** — Grid-based display of font specimens within cards, with a clean, functional aesthetic.
- **Linear** — Monochromatic interface with a single, vivid accent color used for primary actions and highlights.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ninja-red: #ee585a;
  --color-midnight-ink: #121212;
  --color-canvas-white: #ffffff;
  --color-light-steel: #dbdada;
  --color-slate-gray: #8e8e93;
  --color-pure-black: #000000;

  /* Typography — Font Families */
  --font-aeonikfont: 'aeonikFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-pro: 'Aeonik Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --text-display: 44px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-66: 66px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 69px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-links: 16px;
  --radius-buttons: 24px;
  --radius-input-filters: 32px;
  --radius-asymmetric-button-right: 0px 32px 32px 0px;

  /* Shadows */
  --shadow-xl: rgba(72, 72, 74, 0.16) 0px 2px 32px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ninja-red: #ee585a;
  --color-midnight-ink: #121212;
  --color-canvas-white: #ffffff;
  --color-light-steel: #dbdada;
  --color-slate-gray: #8e8e93;
  --color-pure-black: #000000;

  /* Typography */
  --font-aeonikfont: 'aeonikFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-pro: 'Aeonik Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --text-display: 44px;
  --leading-display: 1;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-66: 66px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 69px;

  /* Shadows */
  --shadow-xl: rgba(72, 72, 74, 0.16) 0px 2px 32px 0px;
}
```
