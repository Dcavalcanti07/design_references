# Dropmark — Style Reference
> Architectural blueprint on white marble; precise organization within a serene, bright expanse.

**Theme:** light

Dropmark employs a clean, organized visual style featuring a bright, expansive canvas and structural components delineated by subtle borders and minimal elevation. A vibrant, functional blue serves as the primary accent, providing clear focal points against an otherwise muted palette of grays and off-whites. Typography is confident and direct, utilizing both proportional and tabular figures for clarity. The overall impression is one of efficiency and understated reliability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, default button fills |
| Whisper Gray | `#f7f7f1` | `--color-whisper-gray` | Subtle background for UI sections, card backgrounds, fills |
| Border Fog | `#dcdcd4` | `--color-border-fog` | Subtle borders, dividers, card strokes, inset focus rings |
| Text Graphite | `#404040` | `--color-text-graphite` | Primary body text, headings, dark button text, general borders |
| Muted Black | `#111111` | `--color-muted-black` | Stronger body text, bolder borders, provides high contrast |
| Icon Gray | `#7f7f7f` | `--color-icon-gray` | Muted icons, secondary helper text, subtle borders |
| Action Blue | `#00affa` | `--color-action-blue` | Outline button borders, link text, active states, decorative accents for interaction |
| Deep Violet | `#1e2554` | `--color-deep-violet` | Decorative illustration fills, background for abstract graphics |
| Accent Lilac | `#2c2a6c` | `--color-accent-lilac` | Decorative illustration fills |
| Vivid Orange | `#ff5d43` | `--color-vivid-orange` | Decorative illustration fills, vibrant accents in graphics |
| Bright Teal | `#38dede` | `--color-bright-teal` | Decorative illustration fills, functional icon accents |
| Neon Violet | `#9164fa` | `--color-neon-violet` | Decorative illustration fills, vibrant graphic accents |
| Soft Rose | `#f8b3b8` | `--color-soft-rose` | Decorative illustration fills, subtle graphic accents |

## Tokens — Typography

### DropmarkRealText — Body text, navigation, button labels, and secondary headings. Utilizes proportional numbers for general text flow. · `--font-dropmarkrealtext`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 20px, 24px, 40px
- **Line height:** 1.20, 1.50
- **Letter spacing:** normal
- **OpenType features:** `"lnum"`
- **Role:** Body text, navigation, button labels, and secondary headings. Utilizes proportional numbers for general text flow.

### DropmarkRealHead — Primary headings and display text. Its moderate weight provides a firm, clear presence. Tabular figures ('tnum') for alignment in data presentation. · `--font-dropmarkrealhead`
- **Substitute:** Open Sans
- **Weights:** 500
- **Sizes:** 24px, 40px, 60px
- **Line height:** 1.20
- **Letter spacing:** normal
- **OpenType features:** `"lnum", "tnum"`
- **Role:** Primary headings and display text. Its moderate weight provides a firm, clear presence. Tabular figures ('tnum') for alignment in data presentation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| heading-sm | 20px | 1.5 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 40px | 1.2 | — | `--text-heading-lg` |
| display | 60px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 58 | 58px | `--spacing-58` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 3px |
| avatars | 60px |
| buttons | 3px |
| default | 3px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(220, 220, 210) 0px 0px 0px 2px inset` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 60px
- **Card padding:** 30px
- **Element gap:** 10px

## Components

### Primary Outlined Button
**Role:** Call to action button for key interactive elements.

Ghost button with a 1px border of Action Blue (#00affa), with Action Blue (#00affa) text. 3px border-radius and generous horizontal padding. On hover, the background might subtly fill or the border might thicken.

### Filled Navigation Button
**Role:** High-contrast action in the header, always visible.

Filled with Text Graphite (#404040), Text Graphite (#404040) border, with Canvas White (#ffffff) text. Features 3px border-radius and `DropmarkRealText` at 14px weight 400.

### Header Navigation Link
**Role:** Standard navigation item for primary site sections.

Text in Text Graphite (#404040), `DropmarkRealText` at 15px weight 400. No background or border, relying on spacing for separation.

### Feature Card
**Role:** Display individual features or content blocks.

Background of Canvas White (#ffffff) with a 3px border-radius. Features a 1px solid border in Border Fog (#dcdcd4) or Text Graphite (#404040). Internal padding of 30px.

### Avatar/Circular Element
**Role:** User profile images or circular decorative components.

Utilizes a 60px border-radius to create perfect circles, often associated with user icons or small illustrative elements.

### Input Field Focus
**Role:** Visual indicator for active input fields.

When an input field is focused, it displays a 2px inset ring in Border Fog (#dcdcd4).

## Do's and Don'ts

### Do
- Use Action Blue (#00affa) exclusively for primary interactive elements like outlined button borders and text links, not as a background color for filled buttons.
- Prioritize Whisper Gray (#f7f7f1) and Canvas White (#ffffff) for dominant backgrounds to maintain a light, organized visual theme.
- Apply a consistent 3px border-radius to all interactive components like buttons and cards to ensure a unified softness.
- Structure page sections with a 60px vertical gap to create clear visual separation between content blocks.
- Use Text Graphite (#404040) for primary text and headings to ensure readability against light backgrounds.
- Employ `DropmarkRealText` with 'lnum' feature for all body and general interface text for consistent number alignment.
- Apply `DropmarkRealHead` with 'lnum', 'tnum' features for all headings to ensure aligned tabular figures where numbers are prominent.

### Don't
- Avoid using the decorative illustration colors (Deep Violet, Vivid Orange, etc.) for UI elements, reserving them strictly for graphics and illustrations.
- Do not introduce strong drop shadows; rely on subtle borders, inset shadows, and background color shifts for depth.
- Do not use letter-spacing on headings or body text; maintain the 'normal' value for all typography to preserve legibility.
- Avoid deviating from the 3px radius for general component corners; only use 60px for explicitly circular elements.
- Do not use dark backgrounds for major page sections; maintain the light theme with Whisper Gray and Canvas White.
- Do not exceed a page maximum width of 1200px for main content to keep the layout contained and readable.
- Avoid creating filled buttons with Action Blue (#00affa) as the background; its primary role is for outlined elements and links.

## Imagery

The site uses a combination of abstract, geometric illustrations and product-focused graphics. Illustrations are dimensional and colorful, using the full brand/accent color palette (Deep Violet, Vivid Orange, Bright Teal, Neon Violet, Soft Rose) to create dynamic, overlapping scenes that explain features. They serve a decorative and explanatory role, often positioned alongside text. Icons are filled, appearing in brand colors where applicable (e.g., Bright Teal). The overall density of imagery is balanced, supporting the textual content without overwhelming it.

## Layout

The page adheres to a max-width of 1200px, centering primary content blocks. The hero section features a prominent headline centered over descriptive text and two distinct CTA buttons, with a large, colorful illustration occupying the lower half, hinting at the product's visual nature. Sections below often alternate between multi-column layouts, such as three-column grids for feature highlights, and stacked centered blocks. Vertical rhythm is established through consistent 60px section gaps. The navigation is a sticky top bar with text links and a distinct filled 'Sign up' button, keeping essential controls always accessible.

## Agent Prompt Guide

Quick Color Reference: 
text: #404040
background: #ffffff
border: #dcdcd4
accent: #00affa
primary action: #00affa (outlined action border)

Example Component Prompts:
Create an Outlined Primary Action: Transparent background, #00affa border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
Create a feature card: Canvas White (#ffffff) background, 1px solid border #dcdcd4, 3px border-radius, with 30px internal padding. Caption text at 13px DropmarkRealText weight 400, #404040. Title text at 17px DropmarkRealText weight 600, #404040.
Create a navigation link: Text Graphite (#404040) at 15px DropmarkRealText weight 400. No background or border. On hover, text color should change to Action Blue (#00affa).

## Similar Brands

- **Airtable** — Bright, spacious canvas with an emphasis on primary brand color for interaction and a generally clean, accessible aesthetic.
- **Asana** — Productivity tool with a light theme, using a single dominant brand color against a muted palette for visual hierarchy and action.
- **Monday.com** — Utilizes a bright background with clearly defined content blocks and a controlled color palette, featuring functional accents.
- **Abstract** — Clean, light UI with distinct geometric illustrations, separating brand elements from functional UI components.
- **Milanote** — White canvas, emphasis on visual organization, and use of subtle borders/shadows to define content areas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f7f1;
  --color-border-fog: #dcdcd4;
  --color-text-graphite: #404040;
  --color-muted-black: #111111;
  --color-icon-gray: #7f7f7f;
  --color-action-blue: #00affa;
  --color-deep-violet: #1e2554;
  --color-accent-lilac: #2c2a6c;
  --color-vivid-orange: #ff5d43;
  --color-bright-teal: #38dede;
  --color-neon-violet: #9164fa;
  --color-soft-rose: #f8b3b8;

  /* Typography — Font Families */
  --font-dropmarkrealtext: 'DropmarkRealText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dropmarkrealhead: 'DropmarkRealHead', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-58: 58px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 60px;
  --card-padding: 30px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-cards: 3px;
  --radius-avatars: 60px;
  --radius-buttons: 3px;
  --radius-default: 3px;

  /* Shadows */
  --shadow-subtle: rgb(220, 220, 210) 0px 0px 0px 2px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f7f1;
  --color-border-fog: #dcdcd4;
  --color-text-graphite: #404040;
  --color-muted-black: #111111;
  --color-icon-gray: #7f7f7f;
  --color-action-blue: #00affa;
  --color-deep-violet: #1e2554;
  --color-accent-lilac: #2c2a6c;
  --color-vivid-orange: #ff5d43;
  --color-bright-teal: #38dede;
  --color-neon-violet: #9164fa;
  --color-soft-rose: #f8b3b8;

  /* Typography */
  --font-dropmarkrealtext: 'DropmarkRealText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dropmarkrealhead: 'DropmarkRealHead', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-58: 58px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 60px;

  /* Shadows */
  --shadow-subtle: rgb(220, 220, 210) 0px 0px 0px 2px inset;
}
```
