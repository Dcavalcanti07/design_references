# Not Real — Style Reference
> High-contrast editorial canvas

**Theme:** light

NotReal employs a stark, print-inspired aesthetic characterized by high-contrast typography and a restrained achromatic palette. The design system emphasizes generous white space and precise visual hierarchy through font choices, rather than color or complex layouts. Project showcases act as vibrant focal points within an otherwise minimalist, editorial grid.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f2f2f2` | `--color-canvas-white` | Primary page and surface background |
| Ink Black | `#292a2c` | `--color-ink-black` | Primary text, navigation links, and element borders |
| Deepest Black | `#000000` | `--color-deepest-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### Telegraf — Body copy, navigation, descriptive text, and secondary headings. Its clean, technical feel provides legibility across various scales. · `--font-telegraf`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 18px, 20px, 24px, 25px, 55px
- **Line height:** 0.75, 1.00, 1.08, 1.10, 1.25, 1.33, 1.67, 2.00
- **Letter spacing:** 0.002em, 0.021em, 0.025em, 0.033em, 0.040em
- **Role:** Body copy, navigation, descriptive text, and secondary headings. Its clean, technical feel provides legibility across various scales.

### Ogg — Primary headings and artistic display text. Its high contrast and elegant serifs provide a distinct, editorial brand identity, with tight negative tracking to maintain a compact appearance. · `--font-ogg`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 24px, 26px, 55px
- **Line height:** 1.06, 1.10, 1.50
- **Letter spacing:** -0.036em, -0.020em
- **Role:** Primary headings and artistic display text. Its high contrast and elegant serifs provide a distinct, editorial brand identity, with tight negative tracking to maintain a compact appearance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.67 | — | `--text-body-sm` |
| body | 18px | 1.33 | 0.38px | `--text-body` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.1 | -0.48px | `--text-heading-sm` |
| display | 55px | 0.75 | -1.98px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 11 | 11px | `--spacing-11` |
| 18 | 18px | `--spacing-18` |
| 44 | 44px | `--spacing-44` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 44px
- **Card padding:** 18px
- **Element gap:** 11px

## Components

### Primary Navigation Link
**Role:** Top-level navigation element

Text in Ink Black (telegraf, 400, 18px, 1.33 lh, 0.38px ls), with a bottom border of 1px Deepest Black on hover or active state.

### Site Logo
**Role:** Brand identifier

Exclusively uses Ogg, 400 weight, 55px size, with -1.98px letter spacing. Color is Ink Black, positioned prominently in the top left.

### Hero Description Block
**Role:** Introductory text for the agency

Set in Telegraf 400, Ink Black, using 15px text and 1.67 line height for body, and a 25px size with 1.08 line height for key phrases. Utilizes a compact letterSpacing of 0.025em for emphasis.

### Project Thumbnail Card
**Role:** Showcase individual projects

Consists of an image filling its container, with no visible borders or radius. Text below uses Telegraf 400, 15px, Ink Black for tags and project title in Ogg 400, 26px with -0.52px letter spacing.

### Copyright/Status Text
**Role:** Informational text in footer or sidebar

Small text in Telegraf 400, 15px, Ink Black, with a tight lineHeight of 1.67. Often rotated or positioned vertically to save space.

## Do's and Don'ts

### Do
- Prioritize high contrast between text (#292a2c, #000000) and background (#f2f2f2).
- Use Ogg font for all prominent headings and brand elements to establish a distinct editorial tone, applying its specific negative letter spacing for a dense effect.
- Employ Telegraf for all body text, navigation, and secondary UI elements, maintaining its default letter spacing for optimal readability.
- Maintain a compact density for typography by using specified line heights such as 1.33 for 18px body text and 0.75 to 1.10 for larger headings.
- Structure layouts with generous Canvas White (#f2f2f2) surrounding content blocks to create breathing room and emphasize core visual elements.
- Apply Deepest Black (#000000) as a 1px border for interactive states or as an accent border for text links and visual separators.
- Ensure all imagery is crisp and occupies significant visual space, acting as the primary splash of color and detail against the monochrome UI.

### Don't
- Do not introduce new color hues; strictly adhere to the achromatic palette with #f2f2f2, #292a2c, and #000000.
- Avoid decorative elements like shadows, gradients, or complex background patterns; rely on typography and spacing for visual hierarchy.
- Do not use generic system fonts or fallbacks as primary UI text; Telegraf and Ogg are fundamental to the brand's identity.
- Prevent cluttered layouts; prioritize white space, using 44px for section gaps and 18px for internal padding around content.
- Do not round corners on any UI elements; all shapes should be sharp and angular, reflecting a precise, craft-oriented aesthetic.
- Avoid using multiple font families beyond Telegraf and Ogg; maintain typographic simplicity.
- Do not apply excessive padding or margin to small text elements; keep them dense and contained within 11px general element spacing.

## Imagery

Imagery primarily consists of high-quality, product-focused 3D renders and CGI, often showcasing intricate textures and dynamic lighting. The treatment is full-bleed or contained within a sharp, rectangular frame, never overlapping or with rounded corners. Images serve as vibrant, expressive focal points that break the monochromatic UI, acting as a product showcase to explain content and impress. Density is high within the image blocks themselves, but these blocks are surrounded by text-dominant and spacious negative space.

## Layout

The page exhibits a full-bleed layout for its overall structure, embracing the screen edges. The hero section features the logo and navigation prominently at the top, with a centered description block, while project showcases are arranged in an alternating text-left/image-right pattern or stacked vertically. Sections maintain consistent vertical spacing of 44px, creating a rhythmic, clean flow. There is a strong single-column grid for content blocks, with images often spanning full width, and an implicit two-column grid for text-and-image pairings. Navigation is a minimal top-bar, always visible.

## Agent Prompt Guide

Quick Color Reference:
text: #292a2c
background: #f2f2f2
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

3-5 Example Component Prompts:
Create a navigation bar: Background Canvas White (#f2f2f2). Links in Telegraf 400, 18px, #292a2c (0.38px ls), with a 1px Deepest Black (#000000) bottom border on hover. The logo is Ogg 400, 55px, #292a2c, -1.98px ls.

Generate a project entry card: Full-width image. Title below in Ogg 400, 26px, #000000 (-0.52px ls). Project tags below in Telegraf 400, 15px, #292a2c, with default letter spacing. No borders or radius.

Design the agency description block: Use Telegraf 400, #292a2c. Key phrases at 25px (1.08 lh, 0.025em ls), body text at 15px (1.67 lh). Text aligned left, with 44px vertical padding above and below.

## Similar Brands

- **AIGA Design** — Similar emphasis on high-contrast black and white, oversized serif typography for headings, and a content-forward, grid-based layout.
- **Working Not Working** — Shares a portfolio-centric layout with prominent imagery, clean sans-serif body text, and a minimalist navigation.
- **Chermayeff & Geismar & Haviv** — Exhibits a classic modernist approach with strong typographic hierarchy, a limited color palette, and high-quality hero imagery for case studies.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f2f2f2;
  --color-ink-black: #292a2c;
  --color-deepest-black: #000000;

  /* Typography — Font Families */
  --font-telegraf: 'Telegraf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ogg: 'Ogg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.67;
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.38px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.48px;
  --text-display: 55px;
  --leading-display: 0.75;
  --tracking-display: -1.98px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-11: 11px;
  --spacing-18: 18px;
  --spacing-44: 44px;

  /* Layout */
  --section-gap: 44px;
  --card-padding: 18px;
  --element-gap: 11px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f2f2f2;
  --color-ink-black: #292a2c;
  --color-deepest-black: #000000;

  /* Typography */
  --font-telegraf: 'Telegraf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ogg: 'Ogg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.67;
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.38px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.48px;
  --text-display: 55px;
  --leading-display: 0.75;
  --tracking-display: -1.98px;

  /* Spacing */
  --spacing-11: 11px;
  --spacing-18: 18px;
  --spacing-44: 44px;
}
```
