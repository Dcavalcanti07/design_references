# Ready — Style Reference
> layered frosted glass

**Theme:** light

Ready presents a vivid, multi-layered calendar productivity experience. The light canvas serves as a stage for deeply saturated, dimensional cards that pop with a gradient-tinted frosted-glass effect. Typography is assertive and compact, anchored by heavy headlines, while colorful accents highlight key actions and data. The design uses elevation and saturated background fills to create distinct interactive zones, moving away from flat interfaces.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, body text |
| Ash Mist | `#f5f3f2` | `--color-ash-mist` | Subtle background stripe in navigation, subtle borders |
| Graphite Text | `#333333` | `--color-graphite-text` | Primary text, heading text |
| Slate Link | `#8b8c96` | `--color-slate-link` | Muted link text, secondary text, ghost button borders |
| Deep Plum | `#55269c` | `--color-deep-plum` | Card background, accent for data visualization or featured elements |
| Amethyst Haze | `#6c77b0` | `--color-amethyst-haze` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Lavender Sky | `#817da6` | `--color-lavender-sky` | Subtle card background, layered surface |
| Radiant Orchid | `#8f4d75` | `--color-radiant-orchid` | Card background, accent for data visualization or featured elements |
| Violet Flash | `#7b4096` | `--color-violet-flash` | Card background, accent for data visualization or featured elements |
| Action Lavender | `#7366fe` | `--color-action-lavender` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| System Black | `#000000` | `--color-system-black` | Icon fills, decorative SVG elements |
| Indigo Radial | `radial-gradient(circle farthest-side at 50% 100%, rgb(53, 28, 175), rgba(245, 244, 241, 0) 80%)` | `--color-indigo-radial` | Subtle background gradient for elevated UI elements, creating depth |

## Tokens — Typography

### GT Walsheim — Impactful headings to capture attention, creating a commanding presence without excessive size. · `--font-gt-walsheim`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 56px, 64px
- **Line height:** 1.00
- **Letter spacing:** 0
- **Role:** Impactful headings to capture attention, creating a commanding presence without excessive size.

### GT America Standard — Primary body text, navigation elements, and detailed labels at a variety of sizes. The expanded letter spacing offsets the light weight. · `--font-gt-america-standard`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** 0.167
- **Role:** Primary body text, navigation elements, and detailed labels at a variety of sizes. The expanded letter spacing offsets the light weight.

### GT America Standard — Standard weight for body copy, emphasizing clarity and readability against varied backgrounds. · `--font-gt-america-standard`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** 0.167
- **Role:** Standard weight for body copy, emphasizing clarity and readability against varied backgrounds.

### GT America Standard — Medium weight for strong emphasis within body text and compact UI labels. · `--font-gt-america-standard`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** 0.167
- **Role:** Medium weight for strong emphasis within body text and compact UI labels.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.25 | 0.167px | `--text-caption` |
| body-sm | 14px | 1.33 | 0.167px | `--text-body-sm` |
| body | 16px | 1.33 | 0.167px | `--text-body` |
| subheading | 18px | 1.43 | 0.167px | `--text-subheading` |
| heading-sm | 24px | 1.25 | 0.167px | `--text-heading-sm` |
| heading | 56px | 1 | — | `--text-heading` |
| display | 64px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| images | 16px |
| inputs | 24px |
| buttons | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 11px 11px 40px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 80px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Header Heading
**Role:** Main page titles and prominent section headings.

Uses GT Walsheim, weight 700, size 56px or 64px, color Graphite Text (#333333). Line height of 1.0 for a compact, impactful look.

### Sub-Heading Text
**Role:** Secondary headings or large body text emphasis.

Uses GT America Standard, weight 300, size 24px, color Graphite Text (#333333). Letter spacing 0.167em, line height 1.25.

### Body Text Standard
**Role:** General paragraph content and descriptions.

Uses GT America Standard, weight 400, size 16px, color Graphite Text (#333333). Letter spacing 0.167em, line height 1.33.

### Muted Link/Label
**Role:** Navigation links, secondary actions, or helper text.

Uses GT America Standard, weight 400, size 14px, color Slate Link (#8b8c96). Letter spacing 0.167em, line height 1.43.

### Product Feature Card
**Role:** Showcasing key features or content blocks.

Background color dynamically picked from Deep Plum (#55269c), Amethyst Haze (#6c77b0), Lavender Sky (#817da6), Radiant Orchid (#8f4d75), or Violet Flash (#7b4096). Border radius of 32px. No intrinsic padding, content manages its own spacing via 48px top/bottom and 16px left/right (or more depending on section rhythm). Optional shadow: rgba(0, 0, 0, 0.1) 11px 11px 40px 0px.

### Nav Bar Item
**Role:** Top navigation links.

Uses GT America Standard, weight 400, size 14px, color Graphite Text (#333333). Padding of 48px top/bottom and 16px right/left. Border radius of 32px. Active state indicated by Action Lavender text (#7366fe).

### Primary Card Container
**Role:** Main data display areas, nested cards.

Background Canvas White (#ffffff), border-radius 16px. Optional subtle shadow: rgba(0, 0, 0, 0.1) 11px 11px 40px 0px. Padding of 24px inside.

## Do's and Don'ts

### Do
- Use color Canvas White (#ffffff) as the primary background for content areas and cards, establishing a clean base.
- Apply Graphite Text (#333333) for all main headings and body text, ensuring high contrast and legibility.
- Utilize rich, vibrant colors from the 'brand' group (e.g., Deep Plum #55269c, Amethyst Haze #6c77b0) as distinct background fills for interactive and featured cards, moving away from flat design.
- Incorporate a border-radius of 32px for large interactive elements and hero cards, and 24px for buttons and inputs, providing a soft, modern shape.
- Employ the GT Walsheim font at weight 700 for all primary headings, creating a strong visual hierarchy.
- Maintain a clear vertical rhythm using section gaps of 80px between major content blocks, with card padding at 24px and element gaps at 16px for internal spacing.
- Use the Indigo Radial gradient to add subtle depth to elevated interface elements, mimicking a frosted glass effect.

### Don't
- Avoid using flat, desaturated background colors for main content sections; leverage the vibrant brand colors for distinction.
- Do not deviate from the specified GT Walsheim font for commanding headline text; its specific weight and line-height are key to brand identity.
- Refrain from using default browser link colors (e.g., #0000ee); always use Slate Link (#8b8c96) for muted links and Action Lavender (#7366fe) for highlighted interactive states.
- Do not use sharp 0px border-radii for interactive elements or cards; embrace the rounded aesthetic with 32px, 24px, or 16px radii.
- Avoid excessive use of drop shadows; reserve the rgba(0, 0, 0, 0.1) 11px 11px 40px 0px shadow for truly elevated or focused components.
- Do not over-colorize text or UI elements; rely on the strategic placement of Action Lavender (#7366fe) for functional accents, keeping most typography in neural tones.
- Do not use generic system fonts as substitutes unless specified; GT America Standard and GT Walsheim define the typographic voice.

## Elevation

- **Elevated Card/Modal:** `rgba(0, 0, 0, 0.1) 11px 11px 40px 0px`

## Imagery

The visual language for imagery leans towards clean product screenshots of UI elements in use, often contained within a distinct colored card-like frame, rather than full-bleed photography. These product visuals are treated with soft shadows to give them an elevated, floating appearance. Icons are primarily filled with System Black, demonstrating a subtle, functional aesthetic rather than heavy illustration. The focus is on content and demonstrating the product directly, with imagery serving an explanatory rather than decorative role. Imagery density is moderate, carefully balancing UI examples with clear textual explanations.

## Layout

The layout follows a contained, centered page model without a fixed max-width, allowing sections to breathe. The hero section features a prominent, centered headline and subtext, often with a large, elevated product screenshot beneath. Subsequent sections typically alternate between descriptive text on the left and a product feature visual on the right (or vice-versa). Content is arranged with generous vertical spacing, using a consistent 80px section gap. The overall rhythm emphasizes spaciousness, allowing individual content blocks and textured cards to stand out. Navigation is a minimal, top-aligned bar and a left-aligned sidebar in the main application view.

## Agent Prompt Guide

### Quick Color Reference
text: #333333
background: #ffffff
border: #f5f3f2
accent: #7366fe
primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a hero section: Canvas White background. Headline 'The calendar you need to meet' using GT Walsheim 700 at 64px, color Graphite Text (#333333), line height 1.0. Subtext 'Ready evolves your calendar...' using GT America Standard 400 at 18px, color Graphite Text (#333333), line height 1.43, letter-spacing 0.167em. Below, an elevated product image with a 32px border radius, apply shadow rgba(0, 0, 0, 0.1) 11px 11px 40px 0px.
2. Design a feature card: Background color Amethyst Haze (#6c77b0), border radius 32px. Inside, use a heading 'Automated Templates' with GT America Standard 500 at 24px, color Canvas White (#ffffff), letter-spacing 0.167em. Body text 'Templates allow you to recreate...' with GT America Standard 400 at 16px, color Canvas White (#ffffff), letter-spacing 0.167em.
3. Build a prominent 'Team Meeting' card (as seen in screenshot): Main background Canvas White (#ffffff) with a subtle Indigo Radial gradient, border radius 16px, shadow rgba(0, 0, 0, 0.1) 11px 11px 40px 0px. Inner details include a 'Going' tag with Action Lavender (#7366fe) text, and a date 'Nov 15th at 10-11am' using GT America Standard 400 at 14px, color Graphite Text (#333333). Add a 'Join Zoom' button with Slate Link (#8b8c96) border, 24px radius, and GT America Standard 400 at 14px, color Slate Link (#8b8c96).
4. Create a top navigation bar: Background Canvas White (#ffffff). Include a brand logo (placeholder text 'Ready') on the left, color Graphite Text (#333333), GT America Standard 500 at 18px. On the right, navigation links 'Features', 'Pricing', 'Contact' using GT America Standard 400 at 14px, color Graphite Text (#333333). Active link should use Action Lavender (#7366fe) for text.

## Similar Brands

- **Amie** — Shares a vibrant, task-oriented calendar interface with a focus on colorful UI elements and strong typography.
- **Linear** — Exhibits a similar design philosophy of clean, functional UI mixed with subtle elevation and a strong brand accent color for interactive elements.
- **Raycast** — Utilizes a modern, compact layout with impactful typography and a sophisticated approach to layering and card-based UIs.
- **Superhuman** — Employs an aesthetic that is clean, highly functional, with specific color accents for different interaction states within a productivity context.
- **Height** — Features a strong emphasis on card-based layouts and a visually appealing, slightly tactile interface for project management tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ash-mist: #f5f3f2;
  --color-graphite-text: #333333;
  --color-slate-link: #8b8c96;
  --color-deep-plum: #55269c;
  --color-amethyst-haze: #6c77b0;
  --color-lavender-sky: #817da6;
  --color-radiant-orchid: #8f4d75;
  --color-violet-flash: #7b4096;
  --color-action-lavender: #7366fe;
  --color-system-black: #000000;
  --color-indigo-radial: #351caf;
  --gradient-indigo-radial: radial-gradient(circle farthest-side at 50% 100%, rgb(53, 28, 175), rgba(245, 244, 241, 0) 80%);

  /* Typography — Font Families */
  --font-gt-walsheim: 'GT Walsheim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-standard: 'GT America Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --tracking-caption: 0.167px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: 0.167px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: 0.167px;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --tracking-subheading: 0.167px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.167px;
  --text-heading: 56px;
  --leading-heading: 1;
  --text-display: 64px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-images: 16px;
  --radius-inputs: 24px;
  --radius-buttons: 24px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 11px 11px 40px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ash-mist: #f5f3f2;
  --color-graphite-text: #333333;
  --color-slate-link: #8b8c96;
  --color-deep-plum: #55269c;
  --color-amethyst-haze: #6c77b0;
  --color-lavender-sky: #817da6;
  --color-radiant-orchid: #8f4d75;
  --color-violet-flash: #7b4096;
  --color-action-lavender: #7366fe;
  --color-system-black: #000000;
  --color-indigo-radial: #351caf;

  /* Typography */
  --font-gt-walsheim: 'GT Walsheim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-standard: 'GT America Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --tracking-caption: 0.167px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: 0.167px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: 0.167px;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --tracking-subheading: 0.167px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.167px;
  --text-heading: 56px;
  --leading-heading: 1;
  --text-display: 64px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 11px 11px 40px 0px;
}
```
