# Sparkles — Style Reference
> Whiteboard of playful engineering

**Theme:** light

Sparkles adopts a playful yet precise technical aesthetic: a clean white canvas animated by expressive, cartoonish illustrations. Typography is grounded in a stark, confident black with selective use of lighter neutrals for secondary text. Components are minimal, relying on subtle backgrounds and rounded corners rather than shadows, suggesting a user-friendly system that prioritizes clarity and approachability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0a0a0a` | `--color-midnight-ink` | Primary text, prominent headings, key interface elements |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, form inputs |
| Steel Gray | `#18181b` | `--color-steel-gray` | Button backgrounds for primary actions, secondary text, navigation links |
| Cloud Cover | `#e5e5e5` | `--color-cloud-cover` | Hairline borders, subtle dividers, inactive states |
| Pale Ash | `#f4f4f5` | `--color-pale-ash` | Subtle background for hero sections and some card surfaces |
| Soft Fog | `#fafafa` | `--color-soft-fog` | Subtle background for alternate card surfaces, hover states |
| Pale Stone | `#d4d4d8` | `--color-pale-stone` | Muted body text, helper text, card borders |
| Cool Graphite | `#52525c` | `--color-cool-graphite` | Secondary body text, less prominent links |
| Icon Stroke | `#71717b` | `--color-icon-stroke` | Icon strokes, tertiary text, meta information |
| Input Fill | `#27272a` | `--color-input-fill` | Input background fill, minor body text |
| Muted Border | `#3f3f46` | `--color-muted-border` | Button borders, input borders, less prominent text |
| Success Green | `#54b16c` | `--color-success-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Articulat CF — All body text, navigation items, buttons, and general UI elements. The consistent, slightly open letter spacing on this sans-serif font ensures readability even at smaller sizes. · `--font-articulat-cf`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.33, 1.40, 1.43, 1.50, 1.56, 1.60, 1.75, 1.78
- **Letter spacing:** 0.28em
- **Role:** All body text, navigation items, buttons, and general UI elements. The consistent, slightly open letter spacing on this sans-serif font ensures readability even at smaller sizes.

### Gelica — Prominent headings and display text. Its serif nature and heavier weight provide a bold, distinctive contrast to the sans-serif body text, establishing clear visual hierarchy with authority. · `--font-gelica`
- **Substitute:** Georgia
- **Weights:** 600
- **Sizes:** 36px, 48px, 60px
- **Line height:** 1.00, 1.11
- **Letter spacing:** normal
- **Role:** Prominent headings and display text. Its serif nature and heavier weight provide a bold, distinctive contrast to the sans-serif body text, establishing clear visual hierarchy with authority.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.78 | 0.336px | `--text-caption` |
| body-sm | 14px | 1.75 | 0.392px | `--text-body-sm` |
| body | 16px | 1.56 | 0.448px | `--text-body` |
| subheading | 18px | 1.5 | 0.504px | `--text-subheading` |
| heading-sm | 20px | 1.43 | 0.56px | `--text-heading-sm` |
| heading | 36px | 1.11 | — | `--text-heading` |
| heading-lg | 48px | 1.11 | — | `--text-heading-lg` |
| display | 60px | 1 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| forms | 10px |
| buttons | 10px |
| default | 10px |
| largeCards | 14px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action button

Solid Steel Gray background (#18181b), Canvas White text (#ffffff), 10px border radius, 8px vertical padding, 16px horizontal padding. Features a subtle shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Text Only Button
**Role:** Secondary action or ghost button

Transparent background, Midnight Ink text (#0a0a0a), 0px padding, 8px border radius. Used for less prominent actions within content.

### Navigation Link Button
**Role:** Header navigation item, text-based action

Transparent background, Steel Gray text (#18181b), 10px border radius, 0px vertical padding, 16px horizontal padding.

### Informational Card
**Role:** Content container for features or pricing

Canvas White background (#ffffff), 10px border radius, 24px top/side padding, 28px bottom padding, no shadow.

### Alt Background Card
**Role:** Content container with subtle background

Soft Fog background (#fafafa), 10px border radius, 24px top/side padding, 28px bottom padding, no shadow.

### Large Feature Card
**Role:** Prominent content section, e.g., hero or main feature

Canvas White background (#ffffff), 14px border radius, 40px all-around padding, no shadow.

### Form Input Field
**Role:** User input for forms

Input Fill background (#27272a), Canvas White text (#ffffff), Muted Border color (#3f3f46), 10px border radius, 0px vertical padding, 16px right/left padding, 40px left padding for icon. No shadow.

## Do's and Don'ts

### Do
- Use Gelica font with weight 600 for all primary headings, ensuring line heights of 1.0 or 1.11 for compact presentation.
- Apply Articulat CF for all body text, navigation, and button labels with a letter spacing of 0.28em for consistent readability.
- Prioritize Canvas White (#ffffff) and Pale Ash (#f4f4f5) for background surfaces, distinguishing content blocks with subtle shifts in brightness.
- Employ Midnight Ink (#0a0a0a) or Steel Gray (#18181b) for primary and secondary text to maintain strong contrast on light backgrounds.
- Utilize 10px border radius as the default for buttons, cards, and input fields to maintain a consistent soft edginess.
- Maintain a clear visual hierarchy with generous vertical spacing (40px) between sections and moderate spacing (16px) between UI elements.
- Reserve the Steel Gray (#18181b) filled button for primary calls to action, ensuring it appears as the most direct interactive element.

### Don't
- Avoid applying strong shadows to components; use subtle elevations only as specified for primary buttons or omit them entirely.
- Do not introduce new saturated primary colors; limit the palette to the established neutrals and the single semantic Success Green for decorative use.
- Do not use letter-spacing on display headings (Gelica font); let them maintain a normal tracking.
- Avoid using multiple border styles or colors for cards; maintain a clean, borderless appearance or use Pale Stone (#d4d4d8) for subtle borders.
- Do not use dark backgrounds for entire sections unless justified by a component that explicitly requires it.
- Refrain from using bold or heavy weights for Articulat CF body text; keep it at 400 or 500 for readability.
- Do not overcrowd sections; maintain the comfortable density with clear element and section gaps.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background |
| 1 | Pale Ash | `#f4f4f5` | Subtle background for specific sections or cards to create visual separation without high contrast |
| 2 | Soft Fog | `#fafafa` | Alternative subtle background for cards or containers, slightly off-white |

## Agent Prompt Guide

**Quick Color Reference:**
text: #0a0a0a
background: #ffffff
border: #e5e5e5
accent: #54b16c
primary action: #18181b (filled action)

**3-5 Example Component Prompts:**
1. Create a Primary Action Button: #18181b background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Feature Card on Canvas White background (#ffffff): Articulat CF weight 500 at 18px for a subheading, color Midnight Ink (#0a0a0a), letter-spacing 0.504px, line-height 1.5. Body text Articulat CF weight 400 at 16px, color Cool Graphite (#52525c), letter-spacing 0.448px, line-height 1.56. The card should have a 10px radius and 40px all-around padding.

## Similar Brands

- **Figma** — Clean white interface with prominent black text and a playful, illustration-driven brand identity.
- **Linear** — Minimalist UI, strong typographic hierarchy with a distinct headline font, and a focus on functional, unadorned components.
- **Hey.com** — Usage of a unique, friendly serif font for headings paired with a more conventional sans-serif for body text, on a predominantly white background.
- **Mailchimp** — Playful, organic illustrations and a brand that balances professional utility with approachability and character.
- **GitHub (marketing site)** — Clear, spacious layouts with strong contrast typography against white backgrounds and a focus on developer tools and productivity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-steel-gray: #18181b;
  --color-cloud-cover: #e5e5e5;
  --color-pale-ash: #f4f4f5;
  --color-soft-fog: #fafafa;
  --color-pale-stone: #d4d4d8;
  --color-cool-graphite: #52525c;
  --color-icon-stroke: #71717b;
  --color-input-fill: #27272a;
  --color-muted-border: #3f3f46;
  --color-success-green: #54b16c;

  /* Typography — Font Families */
  --font-articulat-cf: 'Articulat CF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gelica: 'Gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.78;
  --tracking-caption: 0.336px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.75;
  --tracking-body-sm: 0.392px;
  --text-body: 16px;
  --leading-body: 1.56;
  --tracking-body: 0.448px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.504px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: 0.56px;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 14px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-forms: 10px;
  --radius-buttons: 10px;
  --radius-default: 10px;
  --radius-largecards: 14px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-pale-ash: #f4f4f5;
  --surface-soft-fog: #fafafa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-steel-gray: #18181b;
  --color-cloud-cover: #e5e5e5;
  --color-pale-ash: #f4f4f5;
  --color-soft-fog: #fafafa;
  --color-pale-stone: #d4d4d8;
  --color-cool-graphite: #52525c;
  --color-icon-stroke: #71717b;
  --color-input-fill: #27272a;
  --color-muted-border: #3f3f46;
  --color-success-green: #54b16c;

  /* Typography */
  --font-articulat-cf: 'Articulat CF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gelica: 'Gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.78;
  --tracking-caption: 0.336px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.75;
  --tracking-body-sm: 0.392px;
  --text-body: 16px;
  --leading-body: 1.56;
  --tracking-body: 0.448px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.504px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: 0.56px;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --text-display: 60px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 14px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```
