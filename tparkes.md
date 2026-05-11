# Tparkes — Style Reference
> High-contrast digital canvas.

**Theme:** light

Tparkes employs a stark, high-contrast digital canvas aesthetic. Typography, driven by a custom sans-serif, plays a central role, using a deliberate interplay of heavy weights and large sizes for impact, balanced by subdued text colors. Surfaces remain monochromatic, relying on deep gray and pure white for definition. The overall impression is one of directness and clarity, with UI details kept minimal to let content speak.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces |
| Carbon Text | `#333333` | `--color-carbon-text` | Primary text across all surfaces |
| Smoke Gray | `#b3b3b3` | `--color-smoke-gray` | Muted text, subheadings, and secondary information |
| Midnight Black | `#000000` | `--color-midnight-black` | Prominent text, navigation links, and strong borders |
| Mist Border | `#d6d6d6` | `--color-mist-border` | Subtle hairline borders and dividers |
| Silver Link | `#808080` | `--color-silver-link` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Accent Yellow | `#f5ffbe` | `--color-accent-yellow` | Highlighting card backgrounds — a soft, almost pastel tint providing a subtle content break |

## Tokens — Typography

### Instrumentsans — Primary display font for headings, navigation, and prominent text. Its bold weights at large sizes grab attention without being overly decorative, maintaining a strong, direct presence. · `--font-instrumentsans`
- **Substitute:** Montserrat, Inter
- **Weights:** 600, 700
- **Sizes:** 10px, 17px, 22px, 24px, 86px
- **Line height:** 0.83, 0.95, 1.09, 1.18, 1.20, 1.80
- **Letter spacing:** -0.0350em
- **Role:** Primary display font for headings, navigation, and prominent text. Its bold weights at large sizes grab attention without being overly decorative, maintaining a strong, direct presence.

### Arial — Body text and supporting information. It provides a highly readable and neutral counterpoint to the primary display font, ensuring legibility for longer content blocks. · `--font-arial`
- **Substitute:** Helvetica Neue, sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** -0.2140em
- **Role:** Body text and supporting information. It provides a highly readable and neutral counterpoint to the primary display font, ensuring legibility for longer content blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 12 | -0.35px | `--text-caption` |
| body-sm | 14px | 20 | -2.996px | `--text-body-sm` |
| body | 17px | 20 | -0.595px | `--text-body` |
| subheading | 22px | 26 | -0.77px | `--text-subheading` |
| heading | 24px | 28 | -0.84px | `--text-heading` |
| display | 86px | 103 | -3.01px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| icons | 8px |
| images | 16px |
| buttons | 8px |

### Layout

- **Section gap:** 120px
- **Card padding:** 10px
- **Element gap:** 20px

## Components

### Text Accent Card
**Role:** Highlights specific content blocks or portfolio entries.

Background is Accent Yellow (#f5ffbe), border-radius 12px. Padding 10px on all sides. Content inside uses primary text colors.

### Header Navigation Link
**Role:** Primary navigation elements in the page header.

Text uses Midnight Black (#000000) with Instrumentsans font, size 17px, weight 600, letter-spacing -0.0350em. No explicit background or border, appears as plain text link.

### Ghost Action Link
**Role:** Interactive elements, typically for navigation or calls to explore.

Text is Silver Link (#808080) with Arial font, size 14px, weight 400. Has an implicit 1px silver border on interaction or focus, but appears as text-only by default.

### Profile Avatar
**Role:** User or brand identifier.

Circular image with a 16px border-radius, contained within an 8px radius container. May have a subtle 1px solid Mist Border (#d6d6d6).

### Project Preview Image
**Role:** Visual representation of projects or work.

Images primarily with 16px border-radius, occasionally 8px. Often presented without explicit borders to form a clean, contained block.

## Do's and Don'ts

### Do
- Use Instrumentsans ExtraBold (weight 700) for all main headings and prominent texts to convey directness.
- Maintain a clear distinction between Carbon Text (#333333) for primary content and Smoke Gray (#b3b3b3) for secondary or muted descriptions.
- Apply 12px border-radius consistently to all card-like containers, and 16px to larger image blocks.
- Ensure section gaps are consistently 120px to create ample visual breathing room between content blocks.
- Utilize Canvas White (#ffffff) as the dominant background color to maintain a bright, high-contrast appearance.
- Implement Accent Yellow (#f5ffbe) sparingly and only for card backgrounds where a distinct, soft highlight is needed.
- Use 1px solid Mist Border (#d6d6d6) for subtle dividers or outlines, avoiding heavy strokes.

### Don't
- Do not introduce additional background colors; maintain the primary Canvas White and occasional Accent Yellow for cards.
- Avoid using multiple font sizes for body text; stick to the defined Arial 14px for consistency.
- Do not use letter-spacing values other than the specified -0.0350em for Instrumentsans and -0.2140em for Arial.
- Do not apply shadows or complex elevation to elements; surfaces are largely flat.
- Do not use saturated or bright accent colors beyond the subtle Accent Yellow; maintain a monochrome primary palette.
- Avoid decorative gradients; surfaces should be solid colors.
- Do not deviate from the established radius values: 12px for cards, 16px for images, 8px for smaller interactive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background. |
| 2 | Accent Yellow | `#f5ffbe` | Subtle background for highlighted content cards. |

## Imagery

This system features a mix of high-fidelity product screenshots, abstract geometric illustrations, and occasional outlined icons. Product screenshots are typically dark-themed, providing a stark contrast against the light UI, often full-width or large blocks, and are precisely cropped with rounded 16px corners to eliminate any extraneous context. Illustrations are flat, geometric, and monochrome, often using a distinct single brand color or dark gray on a white background, serving as decorative accents or visual metaphors. Icons are outlined, with a moderate stroke weight, and monochromatic – predominantly black or gray. Imagery serves both as decorative atmosphere and direct product showcases, maintaining a balance between aesthetic appeal and informational density.

## Layout

The page primarily uses a full-bleed layout, where content sections often span the full width of the viewport. The hero section features a large, centered text block. Subsequent sections typically alternate between full-width visuals (like product screenshots) and text-dominant areas. Content within these full-width sections is not strictly constrained by a max-width, maintaining a spacious, open feel. Vertical rhythm is governed by a consistent 120px section gap, creating strong visual separation. Navigation is a simple top-right bar with minimal text links. A multi-column grid is used for displaying case studies or visual feeds, suggesting modular content blocks. The overall density is comfortable, with generous white space around elements.

## Agent Prompt Guide

Quick Color Reference: 
- text: #333333
- background: #ffffff
- border: #d6d6d6
- accent: #f5ffbe
- primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Canvas White background. Headline 'I'm Tom Parkes, a digital design lead' using Instrumentsans 86px, weight 700, Carbon Text (#333333), letter-spacing -3.01px.
2. Create a Text Accent Card: Accent Yellow (#f5ffbe) background, 12px border-radius, 10px padding. Inside, place a heading 'My Visual Feed' using Instrumentsans 24px, weight 700, Carbon Text (#333333).
3. Create a Ghost Action Link: 'Explore my work' using Arial 14px, weight 400, Silver Link (#808080), letter-spacing -2.996px. No background, no visible border by default.

## Similar Brands

- **Figma** — Clean, predominantly light UI with strong typography as a core visual element, and minimal, functional use of color.
- **Read.cv** — Emphasis on typographic hierarchy and a limited, high-contrast color palette for personal portfolio presentation.
- **Linear** — Sharp, clean aesthetic with a focus on dark mode product screenshots contrasted against a lighter overall UI, and efficient use of space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-carbon-text: #333333;
  --color-smoke-gray: #b3b3b3;
  --color-midnight-black: #000000;
  --color-mist-border: #d6d6d6;
  --color-silver-link: #808080;
  --color-accent-yellow: #f5ffbe;

  /* Typography — Font Families */
  --font-instrumentsans: 'Instrumentsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 12;
  --tracking-caption: -0.35px;
  --text-body-sm: 14px;
  --leading-body-sm: 20;
  --tracking-body-sm: -2.996px;
  --text-body: 17px;
  --leading-body: 20;
  --tracking-body: -0.595px;
  --text-subheading: 22px;
  --leading-subheading: 26;
  --tracking-subheading: -0.77px;
  --text-heading: 24px;
  --leading-heading: 28;
  --tracking-heading: -0.84px;
  --text-display: 86px;
  --leading-display: 103;
  --tracking-display: -3.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 120px;
  --card-padding: 10px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 26px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-icons: 8px;
  --radius-images: 16px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-accent-yellow: #f5ffbe;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-carbon-text: #333333;
  --color-smoke-gray: #b3b3b3;
  --color-midnight-black: #000000;
  --color-mist-border: #d6d6d6;
  --color-silver-link: #808080;
  --color-accent-yellow: #f5ffbe;

  /* Typography */
  --font-instrumentsans: 'Instrumentsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 12;
  --tracking-caption: -0.35px;
  --text-body-sm: 14px;
  --leading-body-sm: 20;
  --tracking-body-sm: -2.996px;
  --text-body: 17px;
  --leading-body: 20;
  --tracking-body: -0.595px;
  --text-subheading: 22px;
  --leading-subheading: 26;
  --tracking-subheading: -0.77px;
  --text-heading: 24px;
  --leading-heading: 28;
  --tracking-heading: -0.84px;
  --text-display: 86px;
  --leading-display: 103;
  --tracking-display: -3.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 26px;
}
```
