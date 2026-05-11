# Planhat — Style Reference
> Crisp monochrome command center

**Theme:** light

Planhat employs a precise, high-contrast digital interface that balances serious subject matter with subtle visual intrigue. Dark, almost textured backgrounds underpin crisp white foregrounds, with typography serving as the primary design element through its varying weights and exact spacing. Minimal color accents are used strategically, highlighting interactive elements and brand elements without overwhelming the monochrome palette. The overall impression is one of clarity and focused information delivery.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Twilight Ink | `#000000` | `--color-twilight-ink` | Primary text, surface backgrounds, borders for outlined components |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, primary text on dark backgrounds |
| Coal Text | `#121211` | `--color-coal-text` | Secondary text, input text |
| Icon Gray | `#575551` | `--color-icon-gray` | Subtle decorative icons, muted graphic elements |
| Slate Border | `#958d7e` | `--color-slate-border` | Default link text, outlined button borders |

## Tokens — Typography

### Geigy LL Duplex Var Variable Reg — Primary brand typeface for headings and prominent body text. Its variable nature and specific letter spacing create a precise, engineered feel. · `--font-geigy-ll-duplex-var-variable-reg`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 18px, 24px, 32px, 48px, 60px, 113px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.40
- **Letter spacing:** -0.0600em at 113px, -0.0450em at 60px, -0.0350em at 48px, -0.0300em at 32px, -0.0200em at 24px
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary brand typeface for headings and prominent body text. Its variable nature and specific letter spacing create a precise, engineered feel.

### Inter — Functional typeface for body copy, links, and form inputs. Its clean, legible structure supports the primary typeface for information density. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 1.00, 1.20, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0200em at 16px, -0.0150em at 14px, -0.0100em at 12px, 0.1000em at 10px
- **Role:** Functional typeface for body copy, links, and form inputs. Its clean, legible structure supports the primary typeface for information density.

### sans-serif — Fallback font primarily used for small, utility-level text and contexts where Inter's specific features are not required. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback font primarily used for small, utility-level text and contexts where Inter's specific features are not required.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | -0.21px | `--text-body` |
| subheading | 18px | 1.4 | -0.36px | `--text-subheading` |
| heading | 32px | 1.1 | -0.96px | `--text-heading` |
| heading-lg | 48px | 1.1 | -1.68px | `--text-heading-lg` |
| display | 60px | 1 | -2.7px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 999px |
| links | 4px |
| images | 4px |
| inputs | 4px |
| buttons | 4px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 5px

## Components

### Primary Outlined Button
**Role:** Call to action button for significant actions

Background transparent, text 'Twilight Ink' (#000000), border 'Twilight Ink' (#000000) 1px thick, 4px border-radius, padding 10px vertical, 18px horizontal (left), 16px horizontal (right). Font 'sans-serif' weight 400, 12px.

### Secondary Outlined Button
**Role:** Subtle call to action

Background transparent, text 'Twilight Ink' (#000000), border 'Twilight Ink' (#000000) 1px thick, 4px border-radius, padding 6px vertical, 14px horizontal. Font 'sans-serif' weight 400, 12px.

### Pill Card
**Role:** Decorative card for badges or small content blocks

Background 'Twilight Ink' (#000000), border-radius 999px. No padding or shadow.

### Ghost Input Field
**Role:** Input element with minimal styling, typically for search or filter

Transparent background, text 'Coal Text' (#121211), border 'Coal Text' (#121211) 1px thick, 0px border-radius. No explicit padding.

### Subtle Background Input
**Role:** Input field for data entry in a form

Background light gray (#F6F6F8, derived from hints), text 'Twilight Ink' (#000000), border 'Twilight Ink' (#000000) 1px thick, 4px border-radius. No explicit padding.

## Do's and Don'ts

### Do
- Use 'Twilight Ink' (#000000) for all primary body text and main headings to maintain high contrast and readability.
- Apply 'Canvas White' (#ffffff) as the dominant background for all content sections, ensuring a clean and expansive feel.
- Utilize 'Geigy LL Duplex Var Variable Reg' for all headline levels, leveraging its unique letter spacing and variable features for distinctiveness.
- Employ 'Inter' for all functional text such as body copy, UI labels, and form inputs, prioritizing legibility and information density.
- Maintain a compact element gap of 5px between adjacent UI elements to keep interfaces tight and focused.
- Apply a 4px border-radius consistently to all interactive elements including buttons, input fields, and small cards.
- Use 'Slate Border' (#958d7e) only for outlined buttons and links, never as a background color.

### Don't
- Avoid using multiple chromatic colors; limit color accents to functional highlights only.
- Do not introduce heavy shadows or gradients; rely on defined borders and background shifts for surface differentiation.
- Do not deviate from the specified letter-spacing values for 'Geigy LL Duplex Var Variable Reg' as they are critical to its signature appearance.
- Do not use generic system sans-serif for body text or headlines where 'Inter' or 'Geigy LL Duplex Var Variable Reg' are specified.
- Avoid large, uncontained images; all imagery should be treated and contained within defined boundaries.
- Do not use border-radius values other than 4px, 999px, or 100px for component shaping.
- Do not use animated transitions with durations less than 0.3s; ensure moderate pace for UI changes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background |
| 2 | Subtle Background | `#f6f6f8` | Background for input fields and subtle content containers |
| 3 | Twilight Ink | `#000000` | Dark contrast sections and overlays |

## Imagery

The visual language predominantly features abstract, dark, and textured photography or graphics for hero sections, creating a mood of depth and technology. For interior content, product screenshots are presented in clean, contained frames, often with rounded corners, emphasizing functionality and conceptual diagrams. Icons are monochrome, following an outlined style with a consistent stroke weight, and primarily serve to illustrate or highlight features rather than add decorative color. Imagery is always contained, never full-bleed, and integrated to explain content rather than solely for atmospheric effect across the entire page.

## Layout

The page structure uses a centered max-width container, contrasting with full-bleed hero sections that set the initial tone. The hero features a centered headline over a dark, textured background. Subsequent sections alternate between light and dark backgrounds, with consistent vertical spacing creating a rhythmic flow. Content is often arranged in multi-column grids, including alternating text-left/image-right patterns and 3-column feature grids for showcases. A particularly dense customer logo grid showcases social proof. Navigation is a sticky top bar with clearly defined 'Log In' and 'Request a Demo' buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with a dark textured background. Headline: 'Deploy AI with confidence' using 'Geigy LL Duplex Var Variable Reg' at 60px, weight 400, 'Canvas White' (#ffffff) color, letter spacing -2.7px. Subtext: 'Planhat provides B2B enterprises...' in 'Inter' at 18px, weight 400, 'Canvas White' (#ffffff) color. Include a 'Request a Demo' button: transparent background, 'Canvas White' text, 'Canvas White' border, 4px radius, 10px vertical 18px horiz (left) 16px horiz (right) padding, font 'sans-serif' 12px weight 400.
2. Create a feature card: 'Canvas White' (#ffffff) background, 4px border-radius, 'Coal Text' (#121211) primary text, 'Icon Gray' (#575551) secondary text in 'Inter' 14px weight 400. Use 16px padding on all sides. 
3. Create an outlined navigation link: 'Slate Border' (#958d7e) text color, no background, 4px border-radius, 6px vertical 14px horizontal padding. Font 'sans-serif' 12px weight 400.

## Similar Brands

- **Anthropic** — Monochrome palette with high-contrast elements and strong typographic hierarchy, emphasizing content clarity.
- **Vercel** — Clean, technical aesthetic with dark backgrounds for hero sections, and precise, functional UI elements.
- **Linear** — Focus on highly structured, dense information display with minimal decorative flair and a strong reliance on typography and defined borders.
- **Supabase** — Developer-centric, high-contrast design using a mostly achromatic color scheme and crisp geometric sans-serif fonts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-twilight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-coal-text: #121211;
  --color-icon-gray: #575551;
  --color-slate-border: #958d7e;

  /* Typography — Font Families */
  --font-geigy-ll-duplex-var-variable-reg: 'Geigy LL Duplex Var Variable Reg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.21px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.68px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -2.7px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-cards: 999px;
  --radius-links: 4px;
  --radius-images: 4px;
  --radius-inputs: 4px;
  --radius-buttons: 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-subtle-background: #f6f6f8;
  --surface-twilight-ink: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-twilight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-coal-text: #121211;
  --color-icon-gray: #575551;
  --color-slate-border: #958d7e;

  /* Typography */
  --font-geigy-ll-duplex-var-variable-reg: 'Geigy LL Duplex Var Variable Reg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.21px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.68px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -2.7px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 100px;
  --radius-full-2: 999px;
}
```
