# Seed — Style Reference
> Forest & Snow Laboratory

**Theme:** light

Seed's visual system evokes a natural science aesthetic: a dominant muted forest green paired with clean snow white surfaces. Typography is compact and precise, maintaining authority without visual bulk. Rounded 'pill' shapes for interactive elements soften the visual language, contrasting with the scientific rigor suggested by its content. Subtle variations in green and near-white surface colors create depth, while crisp typography and minimal embellishments keep the focus on product clarity and scientific integrity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Green | `#1c3a13` | `--color-forest-green` | Primary brand color, background for action buttons, primary text in dark sections, and decorative borders. Establishes a natural, scientific tone |
| Snow White | `#fcfcf7` | `--color-snow-white` | Primary page background, text on dark backgrounds, and borders for ghost buttons. Acts as a clean, expansive canvas |
| Pale Green | `#d3fa99` | `--color-pale-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. |
| Frosted Glass | `#c4c7c4` | `--color-frosted-glass` | Subtle background for card surfaces and UI elements, imparting a translucent or diffused feel |
| Warm Gray | `#eeeee9` | `--color-warm-gray` | Secondary page and section background color, providing visual separation from Snow White |
| Charcoal Text | `#000000` | `--color-charcoal-text` | Primary text color on light backgrounds, ensuring high contrast and legibility |
| Muted Product Green | `#757c5d` | `--color-muted-product-green` | Background for product cards (DM-02) indicating product color palette |
| Muted Product Yellow | `#9f995b` | `--color-muted-product-yellow` | Background for product cards (AM-02) indicating product color palette |
| Muted Product Teal | `#698e79` | `--color-muted-product-teal` | Background for product cards (PM-02) indicating product color palette |
| Ghost Button Gray | `#b3b3b3` | `--color-ghost-button-gray` | Background for ghost buttons, providing a subtle interactive cue against neutral backgrounds |
| Dark Overlay | `#666666` | `--color-dark-overlay` | Incidental background color, likely for overlay or modal effects |

## Tokens — Typography

### Seed Sans — Primary typeface for all UI elements, headlines, body text, and interactive components. The variable letter spacing creates distinct rhythms for display vs. body text, giving headlines a tighter, more impactful feel while maintaining readability at smaller sizes. · `--font-seed-sans`
- **Substitute:** Inter
- **Weights:** 300, 350, 400, 500
- **Sizes:** 8px, 10px, 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 48px
- **Line height:** 0.90, 1.00, 1.10, 1.17, 1.20, 1.30, 1.40, 1.50, 2.19
- **Letter spacing:** -0.0300em at 48px, -0.0250em at 40px, -0.0200em at 32px, -0.0150em at 24px, -0.0100em at 20px, -0.0070em at 18px, -0.0030em at 16px, -0.0020em at 14px
- **OpenType features:** `"ss05"`
- **Role:** Primary typeface for all UI elements, headlines, body text, and interactive components. The variable letter spacing creates distinct rhythms for display vs. body text, giving headlines a tighter, more impactful feel while maintaining readability at smaller sizes.

### Seed Sans Mono — Mono-spaced typeface, primarily used for technical details, product codes, or metadata. Its consistent width columns lend a precise, structured feel. · `--font-seed-sans-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 300, 400
- **Sizes:** 12px, 16px
- **Line height:** 1.50
- **Letter spacing:** 0.0150em
- **Role:** Mono-spaced typeface, primarily used for technical details, product codes, or metadata. Its consistent width columns lend a precise, structured feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | -0.05px | `--text-body` |
| subheading | 24px | 1.17 | -0.36px | `--text-subheading` |
| heading | 32px | 1.1 | -0.64px | `--text-heading` |
| heading-lg | 40px | 1 | -1px | `--text-heading-lg` |
| display | 48px | 0.9 | -1.44px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 1188px |
| inputs | 8px |
| buttons | 1584px |

### Layout

- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action

Solid Forest Green background (#1c3a13), Snow White text (#fcfcf7), 1584px border radius for a pill shape. Padding is 16px vertical, 24px horizontal. This button signifies immediate, primary action.

### Ghost Action Button
**Role:** Secondary action or link

Transparent background, Forest Green text (#1c3a13) and 1px border (#1c3a13), with 0px border-radius. Padding is 7px vertical, 10.5px horizontal. Used for less prominent actions, often paired with a primary button.

### Ghost Pill Button
**Role:** Interactive navigation or filter

Semi-transparent dark background (rgba(0,0,0,0.3)), Snow White text (#fcfcf7), 1584px border-radius. Padding is 16px vertical, 24px horizontal. Appears commonly in product sections or navigation overlays.

### Nav Pill Button
**Role:** Interactive navigation or filter on light backgrounds

Snow White background (#fcfcf7), Forest Green text (#1c3a13), 1584px border-radius. Padding is 16px vertical, 24px horizontal. Utilized for navigational elements within hero sections or light UI where contrast is desired.

### Product Card
**Role:** Displaying product information

Transparent background, 16px border-radius. Inner padding is not explicitly defined at a card level but elements within will respect 16px padding. Used in grids to showcase different products.

### Product Card with Background
**Role:** Featured product display

Forest Green background (#1c3a13), 16px border-radius. Padding is 48px vertical, 128px horizontal. Used for prominent product listings.

### Frosted Input Field
**Role:** User text input

Transparent background, Snow White text (#fcfcf7) Placeholder text is a lighter shade of Snow White, 1px Snow White border (#fcfcf7), 8px border-radius. Padding is 14px vertical, 20px horizontal.

### Bestseller Badge
**Role:** Product differentiator

Pale Green background (#d3fa99), 1188px border-radius for a capsule shape. Used as a small, vivid accent to categorize products.

## Do's and Don'ts

### Do
- Prioritize Forest Green (#1c3a13) for primary actions and key brand elements against light backgrounds.
- Use Snow White (#fcfcf7) for all primary page backgrounds and text on dark UI sections.
- Employ the 1584px border-radius for all primary buttons and interactive pill-shaped elements.
- Apply Seed Sans with appropriate letter-spacing: tighter for headlines (e.g., -1.44px at 48px), looser for body text (e.g., -0.05px at 16px).
- Maintain high contrast (minimum 7:1) for all text against its background to ensure readability.
- Use the 8px base unit for all spacing between elements, creating a comfortable density.
- Feature product imagery with a monochromatic or muted color palette to align with the brand's natural aesthetic.

### Don't
- Avoid using bright or overly saturated colors unless specifically for a 'Bestseller' badge or similar subtle accent.
- Do not deviate from the rounded 'pill' shape for primary interactive elements; avoid sharp corners for buttons.
- Do not introduce strong shadows or heavy elevation, as the design relies on flat or slightly frosted surfaces.
- Do not use generic system fonts; always use Seed Sans for primary text and Seed Sans Mono for technical details.
- Do not clutter layouts; maintain generous white space and an element gap of 8px to ensure visual calm.
- Do not use gradients unless explicitly defined and approved; the system relies on solid colors and subtle transparency.
- Avoid decorative imagery that clashes with the scientific, nature-inspired product focus.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Snow White Canvas | `#fcfcf7` | Primary page background and outermost UI layer, offering a clean, bright foundation. |
| 1 | Warm Gray Section | `#eeeee9` | Secondary background for distinct content sections, providing subtle visual breaks. |
| 2 | Frosted Card | `#c4c7c4` | Background for cards and elevated UI components, slightly muted and diffused. |
| 3 | Forest Green Surface | `#1c3a13` | Accent background for featured cards or UI elements to draw attention. |
| 4 | Dark Overlay | `#666666` | Background for subtle overlay elements or ghost button states. |

## Imagery

The visual language focuses on clear product photography, often with soft lighting and muted, natural color palettes. Products are typically shown contained, with minimal backgrounds, emphasizing their form and texture. Icons are largely semantic, outlined or filled, and monochrome. Imagery serves an explanatory or product showcase role, rather than decorative atmosphere. The density is balanced, allowing product visuals to breathe within a text-dominant layout.

## Layout

The page primarily uses a contained layout with a comfortable maximum width. The hero section often features a full-bleed visual element with text overlaid or alongside. Section rhythm is structured and alternating, with clear vertical spacing and distinct background colors (Snow White and Warm Gray). Content is arranged in alternating text-left/image-right or centered stacks. Product grids are typically 4-column structures, with cards maintaining consistent padding and radius. The navigation is a fixed top bar, often featuring pill-shaped buttons and a centered logo, contributing to a clean and accessible interface.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fcfcf7
border: #1c3a13
accent: #d3fa99
primary action: #1c3a13 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: solid Forest Green background (#1c3a13), Snow White text (#fcfcf7), 1584px border radius, 16px vertical padding, 24px horizontal padding, 'Shop Now' label.
2. Create a Product Card: transparent background, 16px border radius, with a 'Bestseller' badge using Pale Green background (#d3fa99) and 1188px radius, title 'DS-01 Daily Synbiotic' at Seed Sans 24px weight 400 (#000000), and a Ghost Action Button with a Forest Green border (#1c3a13), 'Shop Now' label.
3. Create a Section Header: 'A healthy gut can change your life.' at Seed Sans 48px weight 400 (#000000), letter-spacing -1.44px, left-aligned, followed by body text 'Our capsule-in-capsule technology delivers...' at Seed Sans 16px weight 400 (#000000) with 8px element-gap below the header.

## Similar Brands

- **Athletic Greens** — Shares a focus on health supplements with a clean, natural, and scientific visual approach, often using greens and whites.
- **Oura Ring** — Utilizes a sophisticated, modern aesthetic with high-quality product photography, minimal UI chrome, and a focus on essential information.
- **Thrive Market** — Employs an organic, earthy feel with clear product displays and an emphasis on natural ingredients, similar to Seed's color palette.
- **Whoop** — Features a performance-oriented, structured layout with clean typography, restrained color use, and detailed scientific explanations.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-green: #1c3a13;
  --color-snow-white: #fcfcf7;
  --color-pale-green: #d3fa99;
  --color-frosted-glass: #c4c7c4;
  --color-warm-gray: #eeeee9;
  --color-charcoal-text: #000000;
  --color-muted-product-green: #757c5d;
  --color-muted-product-yellow: #9f995b;
  --color-muted-product-teal: #698e79;
  --color-ghost-button-gray: #b3b3b3;
  --color-dark-overlay: #666666;

  /* Typography — Font Families */
  --font-seed-sans: 'Seed Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-seed-sans-mono: 'Seed Sans Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.05px;
  --text-subheading: 24px;
  --leading-subheading: 1.17;
  --tracking-subheading: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1px;
  --text-display: 48px;
  --leading-display: 0.9;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 1188px;
  --radius-full-2: 1386px;
  --radius-full-3: 1584px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 1188px;
  --radius-inputs: 8px;
  --radius-buttons: 1584px;

  /* Surfaces */
  --surface-snow-white-canvas: #fcfcf7;
  --surface-warm-gray-section: #eeeee9;
  --surface-frosted-card: #c4c7c4;
  --surface-forest-green-surface: #1c3a13;
  --surface-dark-overlay: #666666;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-green: #1c3a13;
  --color-snow-white: #fcfcf7;
  --color-pale-green: #d3fa99;
  --color-frosted-glass: #c4c7c4;
  --color-warm-gray: #eeeee9;
  --color-charcoal-text: #000000;
  --color-muted-product-green: #757c5d;
  --color-muted-product-yellow: #9f995b;
  --color-muted-product-teal: #698e79;
  --color-ghost-button-gray: #b3b3b3;
  --color-dark-overlay: #666666;

  /* Typography */
  --font-seed-sans: 'Seed Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-seed-sans-mono: 'Seed Sans Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.05px;
  --text-subheading: 24px;
  --leading-subheading: 1.17;
  --tracking-subheading: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1px;
  --text-display: 48px;
  --leading-display: 0.9;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 1188px;
  --radius-full-2: 1386px;
  --radius-full-3: 1584px;
}
```
