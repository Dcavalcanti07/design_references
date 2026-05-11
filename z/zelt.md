# Zelt — Style Reference
> Warm beige canvas with yellow accents

**Theme:** light

Zelt embraces a soft, approachable professionalism with a warm, near-achromatic palette punctuated by a single vivid yellow. The typography is confident and spacious, featuring a clean sans-serif with subtle letter-spacing adjustments for hierarchy and visual texture. Components are light, using soft rounded corners and minimal elevation, allowing the structural beige-gray backgrounds to define visual space rather than strong borders or heavy shadows. This creates an inviting and understated user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#121718` | `--color-midnight-graphite` | Primary text, icon fills, strong borders, dark surface elements |
| Canvas Cloud | `#ffffff` | `--color-canvas-cloud` | Card backgrounds, section backgrounds, main content area fills |
| Warm Mist | `#f6f3ef` | `--color-warm-mist` | Subtle section backgrounds, alternate card surfaces, soft dividers |
| Soft Stone | `#e4e0dd` | `--color-soft-stone` | Page background, large hero sections – provides a gentle, warm base layer |
| Deep Charcoal | `#2f2f2f` | `--color-deep-charcoal` | Footer background, elevated card variants – provides contrast for darker sections |
| Utility Gray | `#444444` | `--color-utility-gray` | Ghost button backgrounds, specific link backgrounds for subtle interaction |
| Amber Glow | `#ffcd6d` | `--color-amber-glow` | Primary action buttons, active navigation indicators, interactive highlights – provides the main chromatic accent |
| Soft Amber | `#ffe2aa` | `--color-soft-amber` | Header alert background, secondary accent highlight – a lighter tint of the primary accent |

## Tokens — Typography

### sans-serif — The primary typeface for all text. A range of weights and adjusted letter-spacing create a clear hierarchy: tighter tracking for large headlines, normal for body text. This gives a modern and legible feel without being overly dense. · `--font-sans-serif`
- **Substitute:** system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'
- **Weights:** 300, 400, 500, 700
- **Sizes:** 8px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 23px, 24px, 29px, 32px, 43px, 58px, 76px, 86px, 101px
- **Line height:** 0.95, 1.00, 1.02, 1.15, 1.16, 1.20, 1.24, 1.35, 1.40, 1.60, 2.63
- **Letter spacing:** -0.043, -0.037, -0.03, -0.025, -0.02, -0.012, -0.01, -0.007, -0.003
- **Role:** The primary typeface for all text. A range of weights and adjusted letter-spacing create a clear hierarchy: tighter tracking for large headlines, normal for body text. This gives a modern and legible feel without being overly dense.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | -0.003px | `--text-caption` |
| body | 16px | 1.6 | -0.007px | `--text-body` |
| subheading | 23px | 1.2 | -0.012px | `--text-subheading` |
| heading | 43px | 1.02 | -0.025px | `--text-heading` |
| heading-lg | 58px | 0.95 | -0.03px | `--text-heading-lg` |
| display | 76px | 0.95 | -0.037px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 72 | 72px | `--spacing-72` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 4px |
| tags | 8px |
| cards | 12px |
| buttons | 12px |

### Layout

- **Section gap:** 43px
- **Element gap:** 14px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action

Background: Amber Glow (#ffcd6d), Text: Midnight Graphite (#121718), Border Radius: 12px, Padding: 14px horizontal, 5-8px vertical (derived from observed button uses like 'Get started')

### Ghost Button
**Role:** Outlined button for secondary actions or links

Background: rgba(0,0,0,0), Text: Midnight Graphite (#121718), Border: 1px solid Midnight Graphite (#121718), Border Radius: 0px or 12px depending on context (e.g. for link text vs. dedicated ghost button), Padding: minimal or 0px. (Based on observed link buttons).

### Soft Card
**Role:** Container for content sections with subtle elevation

Background: Canvas Cloud (#ffffff), Border Radius: 12px, Box Shadow: none, Padding: 43.2px.

### Alternate Card (Warm Mist)
**Role:** Subtle background card for specific content types

Background: Warm Mist (#f6f3ef), Border Radius: 12px, Box Shadow: none, Padding: 0px.

### Alternate Card (Deep Charcoal)
**Role:** Darker card for emphasized sections

Background: Deep Charcoal (#2f2f2f), Border Radius: 12px, Box Shadow: none, Padding: 43.2px top/bottom, 72px left/right.

### Navigation Link
**Role:** Interactive text link within the navigation bar

Text: Midnight Graphite (#121718), no specific background unless active, minimal padding 5px horizontal / 0px vertical.

### Header Alert Bar
**Role:** Banner for important announcements

Background: Soft Amber (#ffe2aa), Text: Midnight Graphite (#121718), Height: 48px.

## Do's and Don'ts

### Do
- Use Midnight Graphite (#121718) as the default for all body text and prominent interactive elements.
- Apply Soft Stone (#e4e0dd) as the primary page background color for major sections to establish the warm, neutral canvas.
- Utilize an Amber Glow (#ffcd6d) background for all primary call-to-action buttons, ensuring text is Midnight Graphite (#121718).
- Employ a 12px border-radius for all cards and primary action buttons to maintain a consistent soft aesthetic.
- Maintain a spacious feel by using 43.2px padding within cards and as vertical section gaps.
- Set the base line-height for body text at 1.6 and apply the observed letter-spacing values from the typography scale to preserve visual hierarchy and legibility.
- Prioritize card backgrounds of Canvas Cloud (#ffffff) or Warm Mist (#f6f3ef) for most content blocks, reserving Deep Charcoal (#2f2f2f) for distinct, darker sections.

### Don't
- Avoid using harsh borders or strong drop shadows; surfaces are defined by subtle color variations and soft curves.
- Do not introduce new vibrant colors outside of the Amber Glow (#ffcd6d) and Soft Amber (#ffe2aa) accents.
- Refrain from tight spacing between major content sections; ensure ample vertical and horizontal breathing room.
- Do not use highly decorative or script fonts; stick to the sans-serif family with its defined weights and letter-spacing for all text.
- Assume all links act as primary calls-to-action; many textual links should remain understated, using only Midnight Graphite (#121718) text.
- Avoid making any element less than 8px border-radius, except for specific contextual text links where 0px is used.
- Do not use dark backgrounds for general content sections; reserve Deep Charcoal (#2f2f2f) for distinct, limited-use blocks like footers or specific card variations.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Soft Stone | `#e4e0dd` | Primary page background, base canvas |
| 1 | Warm Mist | `#f6f3ef` | Secondary background, subtle distinction for content blocks |
| 2 | Canvas Cloud | `#ffffff` | Card backgrounds, main content area fills |
| 3 | Deep Charcoal | `#2f2f2f` | Accented card backgrounds, footer |

## Imagery

This site prominently features abstract 3D renders with soft, diffused lighting and smooth, organic shapes, often in neutral tones (e.g., a large white spherical element at the bottom of the hero). There is an absence of traditional photography or complex illustrations. Icons are minimal, outlined, and monochromatic, usually in Midnight Graphite. The visual density is low, emphasizing purity and clean UI over rich imagery. Imagery serves as decorative atmosphere rather than direct explanatory content, creating a subtle, modern feel.

## Layout

The page adheres to a default full-bleed layout for the hero section with a centered, dominant headline and supporting text. Content below typically follows a contained, centered model, though an explicit page max-width is not strongly defined in the data. Sections are clearly demarcated by variations in background color (Soft Stone, Warm Mist, Canvas Cloud, Deep Charcoal) creating a visual rhythm. Content within sections is often structured in centered stacks or implied multi-column arrangements where modules (like cards) sit alongside each other. Navigation is a sticky top bar, centered within a contained width, with a primary action button on the far right.

## Agent Prompt Guide

Quick Color Reference:
text: #121718
background: #e4e0dd
border: #121718 (for outline control)
accent: #ffcd6d
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Soft Stone background. Headline 'HR Software for the Employee Lifecycle' using sans-serif, weight 500, size 58px, #121718, letter-spacing -0.03em, line-height 0.95. Subtext 'Get a 360° employee view across HR, Payroll and IT' using sans-serif, weight 400, size 18px, #121718, line-height 1.4.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
3. Create a navigation bar item: Text 'Product' using sans-serif, weight 400, size 16px, #121718, with 5px left/right padding. On hover, background Soft Amber (#ffe2aa).
4. Create a Soft Card: Background Canvas Cloud (#ffffff), border-radius 12px, box-shadow none, padding 43.2px. Inside, a heading 'Employee Benefits' using sans-serif, weight 500, size 29px, #121718.

## Similar Brands

- **Rippling** — Shares a similar light, spacious UI with strong, clear typography and a focus on clean cards as content containers.
- **Gusto** — Features a warm, understated color palette with a prominent single accent color used for primary actions, contrasting with mostly neutral backgrounds.
- **BambooHR** — Employs an inviting, user-friendly aesthetic with soft rounded edges, ample white space, and a clear, functional visual hierarchy, similar to Zelt's approachable tone.
- **Carta** — Utilizes sophisticated typography and often uses full-bleed hero sections with minimalist design, relying on subtle background shifts and strong headlines.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #121718;
  --color-canvas-cloud: #ffffff;
  --color-warm-mist: #f6f3ef;
  --color-soft-stone: #e4e0dd;
  --color-deep-charcoal: #2f2f2f;
  --color-utility-gray: #444444;
  --color-amber-glow: #ffcd6d;
  --color-soft-amber: #ffe2aa;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: -0.003px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: -0.007px;
  --text-subheading: 23px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.012px;
  --text-heading: 43px;
  --leading-heading: 1.02;
  --tracking-heading: -0.025px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.03px;
  --text-display: 76px;
  --leading-display: 0.95;
  --tracking-display: -0.037px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-72: 72px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 43px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-misc: 4px;
  --radius-tags: 8px;
  --radius-cards: 12px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-soft-stone: #e4e0dd;
  --surface-warm-mist: #f6f3ef;
  --surface-canvas-cloud: #ffffff;
  --surface-deep-charcoal: #2f2f2f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #121718;
  --color-canvas-cloud: #ffffff;
  --color-warm-mist: #f6f3ef;
  --color-soft-stone: #e4e0dd;
  --color-deep-charcoal: #2f2f2f;
  --color-utility-gray: #444444;
  --color-amber-glow: #ffcd6d;
  --color-soft-amber: #ffe2aa;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: -0.003px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: -0.007px;
  --text-subheading: 23px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.012px;
  --text-heading: 43px;
  --leading-heading: 1.02;
  --tracking-heading: -0.025px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.03px;
  --text-display: 76px;
  --leading-display: 0.95;
  --tracking-display: -0.037px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-72: 72px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
