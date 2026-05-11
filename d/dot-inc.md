# Dot Inc. — Style Reference
> Crisp monochrome utility with orange spark

**Theme:** light

Dot Inc. employs a stark, functional aesthetic with high-contrast monochrome UI elements, punctuated by a single vibrant orange accent. The design feels spacious and robust, using generous padding and rounded corners to soften otherwise sharp information blocks. Typography is clear and direct, reinforcing a sense of precise utility. This system prioritizes straightforward presentation in a light theme environment, with color reserved for interactive elements and brand recognition.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, all primary UI canvases |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, core informational elements, general UI text |
| Ash Gray | `#e5e7eb` | `--color-ash-gray` | Subtle borders, dividers, ghost button outlines. Provides separation without visual weight |
| Dark Graphite | `#1f1f1f` | `--color-dark-graphite` | Headings, section titles, alternative dark backgrounds in thematic blocks |
| Stone Gray | `#b7bfc1` | `--color-stone-gray` | Card borders, subtle box shadows |
| Cloud Gray | `#f5f5f5` | `--color-cloud-gray` | Secondary surface background, background for alternating content blocks |
| Charcoal Text | `#333333` | `--color-charcoal-text` | Body text, list items, secondary informational text |
| Mid Gray | `#707070` | `--color-mid-gray` | Muted helper text, secondary body copy, less prominent UI labels |
| Light Gray | `#dddddd` | `--color-light-gray` | Subtle button backgrounds, inactive states |
| Sunburst Orange | `#ff5a2f` | `--color-sunburst-orange` | Primary call-to-action buttons, badge backgrounds, brand highlights. Creates urgency and focus; Semantic error states in badges |
| Flame Orange | `#f15b2b` | `--color-flame-orange` | Orange text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |

## Tokens — Typography

### Plus Jakarta Sans — The sole typeface for all textual content. Its clean, geometric form supports technical communication while various weights provide hierarchy without additional typefamilies. Weight 800 is used for impactful headlines, while weight 400 is common for body text, ensuring legibility and a contemporary feel. · `--font-plus-jakarta-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600, 700, 800
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 30px, 32px, 40px, 46px, 50px, 60px, 80px
- **Line height:** 1.34, 1.40, 1.45, 1.50, 1.60, 1.64, 1.78, 1.80
- **Letter spacing:** normal
- **Role:** The sole typeface for all textual content. Its clean, geometric form supports technical communication while various weights provide hierarchy without additional typefamilies. Weight 800 is used for impactful headlines, while weight 400 is common for body text, ensuring legibility and a contemporary feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.6 | — | `--text-body-sm` |
| body | 16px | 1.64 | — | `--text-body` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | 24px | 1.45 | — | `--text-heading-sm` |
| heading | 32px | 1.4 | — | `--text-heading` |
| heading-lg | 46px | 1.34 | — | `--text-heading-lg` |
| display | 80px | 1.34 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| forms | 30px |
| badges | 20px |
| images | 20px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.25) 0px 4px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 24px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Primary call-to-action button, highly visible.

Background: Sunburst Orange (#ff5a2f), Text: Canvas White (#ffffff). Border radius: 30px. Padding: 12px vertical, 24px horizontal. No box shadow in default state.

### Outlined Call to Action Button
**Role:** Secondary action button, providing a clear but less dominant call to action.

Background: transparent. Text: Flame Orange (#f15b2b). Border: 1px solid Flame Orange (#f15b2b). Border radius: 8px.

### Ghost Button
**Role:** Tertiary action button or navigation item.

Background: transparent, Text: Ink Black (#000000). No border, minimal padding. Border radius: 0px or 100% for icons.

### Standard Card
**Role:** Container for content sections, features, or product details.

Background: Canvas White (#ffffff). Border radius: 20px. Padding: 48px vertical, 36px horizontal. No box shadow.

### Alternating Background Card
**Role:** Container for content sections in an alternating background layout.

Background: Cloud Gray (#f5f5f5). Border radius: 20px. Padding: 20px vertical, 40px horizontal. No box shadow.

### Feature Badge
**Role:** Highlights key features or attributes.

Background: transparent. Text: Sunburst Orange (#ff5a2f). Border radius: 20px. Padding: 6px vertical, 14px horizontal.

### Image Card
**Role:** Container for product imagery with descriptive text.

Background: Canvas White (#ffffff). Border radius: 30px. Padding: 40px all around. No box shadow.

## Do's and Don'ts

### Do
- Use Sunburst Orange (#ff5a2f) exclusively for primary action backgrounds and brand highlights.
- Maintain a clear visual hierarchy with Plus Jakarta Sans: use heavier weights (700, 800) for headlines and 400 for body text.
- Apply generous vertical spacing between sections, adhering to multiples of 24px for `elementGap` and `sectionGap`.
- Round all interactive elements like buttons and badges with a 30px or 8px radius to convey approachability; use 20px for cards and images.
- Utilize Ash Gray (#e5e7eb) for subtle borders and dividers to maintain a light and spacious feel.
- Ensure all primary text uses Ink Black (#000000) or Dark Graphite (#1f1f1f) for maximum contrast against light surfaces.
- Employ the `Cloud Gray` (#f5f5f5) as a background for alternating content blocks to create visual rhythm without heavy division.

### Don't
- Do not introduce new typefaces; rely solely on Plus Jakarta Sans for all typographic needs.
- Avoid using multiple chromatic colors; restrict accents to the defined Sunburst Orange and Flame Orange derivatives.
- Do not apply drop shadows broadly to cards or sections; reserve the subtle shadow for interactive buttons only.
- Do not deviate from the established border radii; irregular rounding breaks the visual rhythm.
- Avoid dense, information-heavy layouts; favor spacious arrangements and clear visual separation.
- Do not use highly saturated colors for backgrounds; stick to the neutral palette for canvas and surfaces.
- Do not use dark backgrounds for entire pages; the system is designed around a dominant light theme.

## Imagery

This system features a mix of product shots and subtle ambient visuals. Product imagery is typically clean, tightly cropped, and often set against muted or dark backgrounds to emphasize the device itself. Visuals can fill containers or be softly rounded (20px radius). There is minimal use of photography or human elements, focusing instead on the technology. Icons are outlined, simple, and monochrome, often using Ink Black or a muted gray. Imagery functions primarily to showcase products and illustrate features directly.

## Layout

The page primarily uses a full-bleed top section often with a hero image, transitioning into a contained max-width content area (implicitly around 1200px based on component widths). Vertical rhythm is established through consistent section gaps (around 24px). Content often alternates between image-left/text-right and text-left/image-right patterns, providing dynamic flow. Card grids are used for features, showcasing multiple items in a structured layout. The overall density is spacious with ample white space between elements and sections, enhancing readability and focus. Navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #e5e7eb
- accent: #f15b2b
- primary action: #ff5a2f (filled action)

Example Component Prompts:
- Create a 'Find a Reseller' button: background Sunburst Orange (#ff5a2f), text Canvas White (#ffffff), radius 30px, 12px 24px padding.
- Create a secondary 'Request a Demo' button: transparent background, text Flame Orange (#f15b2b), border 1px solid Flame Orange (#f15b2b), radius 8px.
- Create a product feature card: background Canvas White (#ffffff), border radius 20px, 48px 36px padding, heading Ink Black (#000000) weight 700, body Charcoal Text (#333333).
- Create a navigation link: transparent background, text Ink Black (#000000), font Plus Jakarta Sans weight 500, size 16px.
- Create a section header: text Dark Graphite (#1f1f1f) weight 800, size 46px, line height 1.34, element gap 24px below.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #e5e7eb;
  --color-dark-graphite: #1f1f1f;
  --color-stone-gray: #b7bfc1;
  --color-cloud-gray: #f5f5f5;
  --color-charcoal-text: #333333;
  --color-mid-gray: #707070;
  --color-light-gray: #dddddd;
  --color-sunburst-orange: #ff5a2f;
  --color-flame-orange: #f15b2b;

  /* Typography — Font Families */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --text-body: 16px;
  --leading-body: 1.64;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.45;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.34;
  --text-display: 80px;
  --leading-display: 1.34;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 27px;
  --radius-3xl-2: 30px;
  --radius-full: 50px;
  --radius-full-2: 54px;
  --radius-full-3: 100px;
  --radius-full-4: 999px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-forms: 30px;
  --radius-badges: 20px;
  --radius-images: 20px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 4px 10px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #e5e7eb;
  --color-dark-graphite: #1f1f1f;
  --color-stone-gray: #b7bfc1;
  --color-cloud-gray: #f5f5f5;
  --color-charcoal-text: #333333;
  --color-mid-gray: #707070;
  --color-light-gray: #dddddd;
  --color-sunburst-orange: #ff5a2f;
  --color-flame-orange: #f15b2b;

  /* Typography */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --text-body: 16px;
  --leading-body: 1.64;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.45;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.34;
  --text-display: 80px;
  --leading-display: 1.34;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-208: 208px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 27px;
  --radius-3xl-2: 30px;
  --radius-full: 50px;
  --radius-full-2: 54px;
  --radius-full-3: 100px;
  --radius-full-4: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 4px 10px 0px;
}
```
