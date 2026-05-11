# Workflow — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Workflow adopts a clean, functional workspace aesthetic with a predominantly achromatic palette, emphasizing content and interaction. Subtle surface variations and hairline borders create a sense of depth without heavy shadows. Typography is precise and utilitarian, with a single serif accent for display headlines. Interactive elements are lightly styled, relying on hover states and clear hierarchy rather than bold color to guide user attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#ffffff` | `--color-canvas` | Primary page background, elevated card surfaces |
| Ink | `#1a1a1a` | `--color-ink` | Primary text color for headings and body content, strong borders, dark icons, and inverted surface backgrounds |
| Ash | `#6a6a6a` | `--color-ash` | Secondary text for helper content, weaker border lines, and muted icons |
| Fog | `#f6f6f6` | `--color-fog` | Subtle background for buttons, badges, and alternative section backgrounds |
| Pebble | `#ececec` | `--color-pebble` | Tertiary background for cards and feature blocks, subtly distinct from Canvas |
| Frost | `#e3e3e3` | `--color-frost` | Lightest border lines for dividing elements and weak outlines |
| Driftwood | `#4d3f32` | `--color-driftwood` | Decorative highlights, text accents in specific content sections |
| Success Green | `#547e69` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Success Pale | `#60886f` | `--color-success-pale` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Error Red | `#923d56` | `--color-error-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Success Wash | `#f1fcf6` | `--color-success-wash` | Primary page canvas and white card surfaces. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Inter — Primary typeface for all body text, UI labels, navigation, and button text. Its versatility and geometric neutrality support the functional aesthetic. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px
- **Line height:** 1.00 - 1.91
- **Letter spacing:** -0.0040em, 0.0020em, 0.0030em, 0.0040em
- **Role:** Primary typeface for all body text, UI labels, navigation, and button text. Its versatility and geometric neutrality support the functional aesthetic.

### Crimson Pro — Display typeface for prominent headlines and calls to action. The lighter weight (300) delivers authority through restraint rather than visual density, contrasting with the utilitarian sans-serif. · `--font-crimson-pro`
- **Substitute:** Georgia, serif
- **Weights:** 300
- **Sizes:** 26px, 32px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Display typeface for prominent headlines and calls to action. The lighter weight (300) delivers authority through restraint rather than visual density, contrasting with the utilitarian sans-serif.

### Georgia — Georgia — detected in extracted data but not described by AI · `--font-georgia`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.35, 1.62
- **Role:** Georgia — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 0.003px | `--text-caption` |
| heading-lg | 26px | 1 | — | `--text-heading-lg` |
| display | 32px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 104 | 104px | `--spacing-104` |
| 164 | 164px | `--spacing-164` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 12px |
| input | 8px |
| badges | 6px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.06) 0px 2px 6px 0px` | `--shadow-sm` |
| subtle | `rgba(0, 0, 0, 0.03) 0px 1px 3px 0px, rgba(0, 0, 0, 0.03) ...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Interactive element

Ghost button for primary actions: #f6f6f6 background, Ink (#1a1a1a) text, 8px border radius, 16px horizontal and 8px vertical padding. Subtle, yet clearly interactive.

### Pill Button
**Role:** Interactive element

Circular or pill-shaped button for secondary actions or toggles: rgba(26,26,26,0.65) text and border, 9999px border radius, 16px padding on all sides. Used for minimal, iconic actions.

### Feature Card
**Role:** Container

Information or feature display card: Canvas (#ffffff) background, 12px border radius, 24px padding on all sides. Features a subtle elevation with rgba(0,0,0,0.06) 0px 2px 6px 0px shadow.

### Section Card
**Role:** Container

Minimalist card to group content sections: Pebble (#ececec) background, 12px border radius, no padding in all sides. Used for subtle content separation.

### Pill Badge
**Role:** Content label

Small, informative label: Fog (#f6f6f6) background, Ink (#1a1a1a) text, 6px border radius, 7px horizontal and 4px vertical padding. For tags and status indicators.

### Inline Text Badge
**Role:** Content label

Simple text badge without background: Ink (#1a1a1a) text, minimal padding and no radius. Integrates cleanly into body copy.

### Input Field
**Role:** Form element

Standard text input or selection field: 8px border radius, Ink (#1a1a1a) text, and a 1px border. Placeholder text in Ash (#6a6a6a).

## Do's and Don'ts

### Do
- Prioritize Ink (#1a1a1a) for primary text and Canvas (#ffffff) for backgrounds to ensure AAA contrast.
- Use Inter font for all functional text elements and Crimson Pro weight 300 for display headlines.
- Employ consistent 8px border radius for interactive elements (buttons, inputs) and 12px for cards.
- Adhere to an element gap of 16px to maintain a comfortable density.
- Utilize Fog (#f6f6f6) for secondary button backgrounds and subtle background shifts.
- Apply hairline borders using Frost (#e3e3e3) or Ink (#1a1a1a) for structural separation over heavy dividers.
- Implement the 'Pill Button' style using 9999px border radius for isolated actions or toggles.

### Don't
- Avoid strong, saturated colors for UI backgrounds or primary actions; reserved for semantic feedback or decorative accents.
- Do not deviate from Inter or Crimson Pro for typography; do not introduce additional font families.
- Refrain from using heavy drop shadows; implement subtle elevation with single rgba(0,0,0,0.06) 0px 2px 6px 0px shadows when depth is required.
- Do not use generic gray values; always refer to the defined neutral palette (Ink, Ash, Fog, Pebble, Frost).
- Avoid over-animating; transitions should be subtle, with 0.2s duration and ease timing.
- Do not break the established spacing hierarchy; maintain 16px element gaps and 24px card padding.
- Refrain from using color to indicate interaction unless it's a semantic state (success/error); rely on hover states and subtle background changes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#ffffff` | Base page background and principal surface for content. |
| 2 | Fog | `#f6f6f6` | Secondary background for sections, buttons, and badges to add subtle differentiation. |
| 3 | Pebble | `#ececec` | Tertiary background for elevated cards and feature blocks, providing a slightly darker context. |

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.06) 0px 2px 6px 0px`
- **Card with deeper shadow:** `rgba(0, 0, 0, 0.03) 0px 1px 3px 0px, rgba(0, 0, 0, 0.03) 0px 5px 5px 0px, rgba(0, 0, 0, 0.02) 0px 10px 6px 0px`

## Imagery

The visual language for imagery is primarily functional and integrated with the UI. Product screenshots or abstract graphics are contained within cards or sections, often with rounded corners (8px or 12px) and rarely overlapping. If photography is present, it appears as tight product crops or profile images within UI elements. Icons are predominantly outlined, using Ink (#1a1a1a) or Ash (#6a6a6a), with a consistent medium stroke weight; they serve an explanatory or decorative role rather than a primary content focus. The density is text-dominant, with imagery serving as supportive evidence or visual breaks.

## Layout

The page maintains a centered max-width of 1200px, creating a contained and focused experience. The hero section features a prominent, centered headline with supporting text and a primary action button against the Canvas background. Sections follow a consistent rhythm of alternating white and light gray backgrounds, creating visual segmentation without explicit dividers. Content is generally arranged in stacks or two-column layouts, often with text on one side and a visual element (screenshot, card) on the other. Navigation consists of a clear top bar with text links and subtle ghost buttons, maintaining a clean, unobtrusive presence.

## Agent Prompt Guide

Quick Color Reference:
text: #1a1a1a
background: #ffffff
border: #e3e3e3
accent: #4d3f32
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a feature card: #ffffff background, 12px border radius, box-shadow rgba(0, 0, 0, 0.06) 0px 2px 6px 0px, 24px padding on all sides, heading text #1a1a1a Crimson Pro weight 300 size 26px, body text #1a1a1a Inter weight 400 size 14px.
3. Implement a pill badge: #f6f6f6 background, #1a1a1a text, 6px border radius, 7px horizontal padding, 4px vertical padding, Inter font weight 400, size 12px.
4. Build an input field: 8px border radius, 1px #e3e3e3 border, placeholder text #6a6a6a Inter weight 400, size 14px, label text #1a1a1a Inter weight 500, size 14px.

## Similar Brands

- **Linear** — Monochrome UI with strong typographic hierarchy and minimal, functional use of color, primarily blues and grays.
- **Figma** — Clean, light canvas with a focus on functional UI elements, subtle surfaces, and a well-defined gray scale for controls and text.
- **Stripe** — Utilizes a highly refined neutral palette, precise typography, and a strategic application of subtle accent colors for visual guidance and branding.
- **Notion** — Content-first design with a white canvas, minimal borders, and a focus on clarity through achromatic design choices and a comfortable spacing system.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #ffffff;
  --color-ink: #1a1a1a;
  --color-ash: #6a6a6a;
  --color-fog: #f6f6f6;
  --color-pebble: #ececec;
  --color-frost: #e3e3e3;
  --color-driftwood: #4d3f32;
  --color-success-green: #547e69;
  --color-success-pale: #60886f;
  --color-error-red: #923d56;
  --color-success-wash: #f1fcf6;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-crimson-pro: 'Crimson Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-georgia: 'Georgia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.003px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1;
  --text-display: 32px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-164: 164px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 12px;
  --radius-input: 8px;
  --radius-badges: 6px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 2px 6px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.03) 0px 1px 3px 0px, rgba(0, 0, 0, 0.03) 0px 5px 5px 0px, rgba(0, 0, 0, 0.02) 0px 10px 6px 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-fog: #f6f6f6;
  --surface-pebble: #ececec;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #ffffff;
  --color-ink: #1a1a1a;
  --color-ash: #6a6a6a;
  --color-fog: #f6f6f6;
  --color-pebble: #ececec;
  --color-frost: #e3e3e3;
  --color-driftwood: #4d3f32;
  --color-success-green: #547e69;
  --color-success-pale: #60886f;
  --color-error-red: #923d56;
  --color-success-wash: #f1fcf6;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-crimson-pro: 'Crimson Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-georgia: 'Georgia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.003px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1;
  --text-display: 32px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-164: 164px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 2px 6px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.03) 0px 1px 3px 0px, rgba(0, 0, 0, 0.03) 0px 5px 5px 0px, rgba(0, 0, 0, 0.02) 0px 10px 6px 0px;
}
```
