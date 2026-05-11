# Fold — Style Reference
> Softly lit, data-rich canvas

**Theme:** light

Fold presents a soft, data-informed financial interface built on a minimal light theme. It uses a high-contrast dark text against near-white surfaces, complemented by a single vivid blue for functional accents. Components are lightweight, featuring oversized rounded corners and subtle, cool-toned shadows for a floating effect. Typography is compact and precise, maintaining clarity within an otherwise visually gentle layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, elevated card surfaces, ghost button backgrounds, and key icon fills |
| Whisper Gray | `#f0f1f5` | `--color-whisper-gray` | Secondary background for cards, subtle section dividers, and pill-shaped button backgrounds |
| Ash Gray | `#c7cbdb` | `--color-ash-gray` | Subtle borders, list item backgrounds, and soft background fills for non-interactive elements |
| Graphite | `#dddfe9` | `--color-graphite` | Tertiary background for elevated cards, ghost button borders, and decorative outlines |
| Midnight Ink | `#20294c` | `--color-midnight-ink` | Primary text color for headings and body content, high-contrast icon fills |
| Deep Violet | `#375390` | `--color-deep-violet` | Border color for various UI elements including cards and decorative accents, providing depth without strong saturation |
| Active Blue | `#459af8` | `--color-active-blue` | Primary action color for links and navigation, button backgrounds for critical actions |
| Muted Slate | `#676b89` | `--color-muted-slate` | Secondary text color for body copy, icon fills, and less prominent text elements |
| Soft Stone | `#979db5` | `--color-soft-stone` | Helper text, subtle icon fills, and decorative background accents |
| Ocean Tint | `#0a2d67` | `--color-ocean-tint` | Subtle text accents and small icon details, providing a deeper cool tone |
| Pale Violet Border | `#788dba` | `--color-pale-violet-border` | Subtle border for ghost buttons and interactive elements |
| Gold Highlight | `#ffff00` | `--color-gold-highlight` | Distinct background for highlight cards or specific callouts |

## Tokens — Typography

### GT Walsheim Pro — Primary brand typeface for all text content. Its clean, geometric forms with a casual touch, especially at larger sizes, convey directness while remaining approachable. Heavier weights (600, 700) are used for strong headings and CTAs, while lighter weights (400) maintain readability in body text. Letter spacing is compressed for larger headlines, giving them a compact, impactful appearance typical of financial apps, and relaxed for smaller text. · `--font-gt-walsheim-pro`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 14px, 16px, 17px, 18px, 20px, 24px, 26px, 32px, 64px, 100px
- **Line height:** 0.85, 0.91, 1.00, 1.18, 1.19, 1.20, 1.25, 1.33, 1.41, 1.43, 1.50, 1.75
- **Letter spacing:** -0.125, -0.04, -0.03, 0.025, 0.04
- **Role:** Primary brand typeface for all text content. Its clean, geometric forms with a casual touch, especially at larger sizes, convey directness while remaining approachable. Heavier weights (600, 700) are used for strong headings and CTAs, while lighter weights (400) maintain readability in body text. Letter spacing is compressed for larger headlines, giving them a compact, impactful appearance typical of financial apps, and relaxed for smaller text.

### GT America — Secondary typeface for specific headings that require a slightly different voice than GT Walsheim Pro. It contrasts slightly with the primary font, providing textual variety without clashing, generally used at prominent sizes. · `--font-gt-america`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 24px, 42px
- **Line height:** 1.00, 1.50
- **Letter spacing:** 0
- **Role:** Secondary typeface for specific headings that require a slightly different voice than GT Walsheim Pro. It contrasts slightly with the primary font, providing textual variety without clashing, generally used at prominent sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.04px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.025px | `--text-body-sm` |
| body | 16px | 1.5 | 0.025px | `--text-body` |
| subheading | 18px | 1.4 | -0.03px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.03px | `--text-heading-sm` |
| heading | 32px | 1.19 | -0.04px | `--text-heading` |
| heading-lg | 64px | 0.91 | -0.125px | `--text-heading-lg` |
| display | 100px | 0.85 | -0.125px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| images | 8px |
| buttons | 9999px |
| pillShape | 9999px |
| navigation | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(32, 41, 76, 0.12) 0px 9px 25px 0px` | `--shadow-xl` |
| md | `rgba(32, 41, 76, 0.12) 0px 6px 16px 0px, rgba(32, 41, 76,...` | `--shadow-md` |
| md-2 | `rgba(32, 41, 76, 0.07) 0px 4px 11px 0px, rgba(32, 41, 76,...` | `--shadow-md-2` |
| subtle | `rgba(255, 255, 255, 0.53) 0px 1px 0px 0px` | `--shadow-subtle` |
| sm | `rgba(32, 41, 76, 0.1) 0px 1px 4px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Filled Primary Button
**Role:** Call to action button for critical actions.

Background: Active Blue (#459af8), Text: Canvas White (#ffffff), Border: Deep Violet (#375390), Radius: 9999px, Padding: 8px 8px.

### Ghost Button
**Role:** Secondary action or navigational link with minimal visual weight.

Background: rgba(0, 0, 0, 0), Text: Canvas White (#ffffff), Border: Deep Violet (#375390), Radius: 0px, Padding: 0px 0px.

### Pill Button
**Role:** Tertiary action, status labels, or filters.

Background: Whisper Gray (#f0f1f5), Text: Midnight Ink (#20294c), Border: Pale Violet Border (#788dba), Radius: 9999px, Padding: 8px 12px.

### Subtle Pill Button
**Role:** Less prominent pill-shaped actions, for category tags or non-critical actions.

Background: #fafafa, Text: Midnight Ink (#20294c), Border: rgba(120, 141, 186, 0.5), Radius: 9999px, Padding: 8px 16px.

### Light Card Default
**Role:** Standard informational card, often used for content display.

Background: Canvas White (#ffffff), Border: none, Radius: 12px, Shadow: rgba(32, 41, 76, 0.12) 0px 9px 25px 0px, Padding: 16px.

### Whisper Card Elevated
**Role:** Container for grouped content with a subtle lifted feel.

Background: Whisper Gray (#f0f1f5), Border: none, Radius: 20px, Shadow: none, Padding: 0px.

### Blank Card Container
**Role:** Large container card for sections, often with internal padding handled by children.

Background: Canvas White (#ffffff), Border: none, Radius: 24px, Shadow: rgba(32, 41, 76, 0.12) 0px 9px 25px 0px, Padding: 0px.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#20294c) for all primary text elements to ensure high contrast on light backgrounds.
- Use Active Blue (#459af8) exclusively for interactive elements like links and primary CTA button backgrounds.
- Apply a 9999px border-radius to all buttons and tags to maintain a consistent pill-shaped aesthetic.
- Employ the rgba(32, 41, 76, 0.12) 0px 9px 25px 0px shadow for primary card elevation, creating a soft, cool gradient lift.
- Maintain a comfortable density with a base element gap of 8px and card padding of 16px.
- Use GT Walsheim Pro with compressed letter-spacing for large headlines (-0.1250em at 100px) and normal tracking for body text (0.025em at 16px).
- Utilize Whisper Gray (#f0f1f5) and Ash Gray (#c7cbdb) to define distinct background surfaces and visual hierarchies between sections without sharp transitions.

### Don't
- Do not introduce new saturated accent colors beyond Active Blue (#459af8) unless for semantic states.
- Avoid harsh, high-contrast borders; instead, use muted grays like Deep Violet (#375390) or Pale Violet Border (#788dba) for outlines.
- Do not deviate from the established shadow values; custom shadows will disrupt the subtle elevation effect.
- Refrain from using heavily decorative gradients; the system relies on solid colors and soft shadows.
- Do not use sharp corners; the lowest acceptable card radius is 12px, with many elements using much larger values.
- Do not use small, pixel-perfect type sizes without adequate line height; prioritize readability and breathing room for text content.
- Avoid centered text blocks for large content sections; prefer left-aligned text for better scan-ability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background, light and airy primary surface. |
| 1 | Whisper Gray | `#f0f1f5` | Secondary background for cards and subtle section breaks, slightly receded from the primary canvas. |
| 2 | Ash Gray | `#c7cbdb` | Tertiary background for less prominent elements like list items, or for providing a subtle border effect that separates content. |

## Elevation

- **Light Card Default:** `rgba(32, 41, 76, 0.12) 0px 9px 25px 0px`
- **Blank Card Container:** `rgba(32, 41, 76, 0.12) 0px 9px 25px 0px`
- **Small Card Layer:** `rgba(32, 41, 76, 0.12) 0px 6px 16px 0px, rgba(32, 41, 76, 0.09) 0px 1px 5px 0px`
- **Input Field / Button:** `rgba(32, 41, 76, 0.1) 0px 1px 4px 0px`

## Imagery

The visual language for imagery is characterized by minimalist, line-art illustrations and isolated product screenshots. Illustrations are typically organic, outlined with a fine stroke (resembling Deep Violet or Dark Gray) and filled sparingly or with subtle tints, often showcasing abstract financial concepts or product features. Product screenshots are clean, showcasing the UI on mobile device mockups, presented in a focused manner without distracting backgrounds. Icons are outlined, fine-lined, and monochrome, primarily using Midnight Ink or Muted Slate. Imagery serves an explanatory and decorative role, enhancing content without overwhelming the UI, maintaining a light density by not being full-bleed.

## Layout

The page primarily employs a contained, centered layout, without a fixed max-width, allowing sections to breathe. The hero section often features a large, centered headline over an illustrative graphic. Content is structured in alternating sections, typically with generous vertical spacing (48px section gap). Many sections use a two-column layout that alternates text and visuals (text-left/image-right, then image-left/text-right). Card grids are used for features, showcasing clear division with rounded corners. The overall density is comfortable, with ample whitespace creating a spacious feel. Navigation is handled by a minimalistic top bar and a footer with structured links.

## Agent Prompt Guide

Quick Color Reference:
text: #20294c
background: #ffffff
border: #375390
accent: #459af8
primary action: #459af8 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #459af8 background, #979db5 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design an informational card: `Light Card Default`, background Canvas White, with a heading 'Total Balance' (GT Walsheim Pro, 600, 24px, Midnight Ink) and a value '$12,345' (GT Walsheim Pro, 700, 32px, Midnight Ink).
3. Generate a secondary pill-shaped button: `Pill Button`, text 'Category' (GT Walsheim Pro, 400, 14px, Midnight Ink).

## Similar Brands

- **Fathom Analytics** — Shares a clean, light UI with soft shadows, prominent typography, and a single accent color for interactive elements.
- **Linear** — Similar emphasis on functional, compact typography and a subtle, almost invisible UI until interaction, using soft grays as primary surfaces.
- **Supabase** — Uses subtle elevation, a monochromatic palette with one strong accent color, and clean, geometric sans-serif typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f0f1f5;
  --color-ash-gray: #c7cbdb;
  --color-graphite: #dddfe9;
  --color-midnight-ink: #20294c;
  --color-deep-violet: #375390;
  --color-active-blue: #459af8;
  --color-muted-slate: #676b89;
  --color-soft-stone: #979db5;
  --color-ocean-tint: #0a2d67;
  --color-pale-violet-border: #788dba;
  --color-gold-highlight: #ffff00;

  /* Typography — Font Families */
  --font-gt-walsheim-pro: 'GT Walsheim Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.04px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.025px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.025px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.19;
  --tracking-heading: -0.04px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.91;
  --tracking-heading-lg: -0.125px;
  --text-display: 100px;
  --leading-display: 0.85;
  --tracking-display: -0.125px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 33px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-images: 8px;
  --radius-buttons: 9999px;
  --radius-pillshape: 9999px;
  --radius-navigation: 24px;

  /* Shadows */
  --shadow-xl: rgba(32, 41, 76, 0.12) 0px 9px 25px 0px;
  --shadow-md: rgba(32, 41, 76, 0.12) 0px 6px 16px 0px, rgba(32, 41, 76, 0.09) 0px 1px 5px 0px;
  --shadow-md-2: rgba(32, 41, 76, 0.07) 0px 4px 11px 0px, rgba(32, 41, 76, 0.12) 0px 1px 3px 0px;
  --shadow-subtle: rgba(255, 255, 255, 0.53) 0px 1px 0px 0px;
  --shadow-sm: rgba(32, 41, 76, 0.1) 0px 1px 4px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-whisper-gray: #f0f1f5;
  --surface-ash-gray: #c7cbdb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f0f1f5;
  --color-ash-gray: #c7cbdb;
  --color-graphite: #dddfe9;
  --color-midnight-ink: #20294c;
  --color-deep-violet: #375390;
  --color-active-blue: #459af8;
  --color-muted-slate: #676b89;
  --color-soft-stone: #979db5;
  --color-ocean-tint: #0a2d67;
  --color-pale-violet-border: #788dba;
  --color-gold-highlight: #ffff00;

  /* Typography */
  --font-gt-walsheim-pro: 'GT Walsheim Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.04px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.025px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.025px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.19;
  --tracking-heading: -0.04px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.91;
  --tracking-heading-lg: -0.125px;
  --text-display: 100px;
  --leading-display: 0.85;
  --tracking-display: -0.125px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 33px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(32, 41, 76, 0.12) 0px 9px 25px 0px;
  --shadow-md: rgba(32, 41, 76, 0.12) 0px 6px 16px 0px, rgba(32, 41, 76, 0.09) 0px 1px 5px 0px;
  --shadow-md-2: rgba(32, 41, 76, 0.07) 0px 4px 11px 0px, rgba(32, 41, 76, 0.12) 0px 1px 3px 0px;
  --shadow-subtle: rgba(255, 255, 255, 0.53) 0px 1px 0px 0px;
  --shadow-sm: rgba(32, 41, 76, 0.1) 0px 1px 4px 0px;
}
```
