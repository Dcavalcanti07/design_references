# Tailscale — Style Reference
> Cloud control panel on pristine paper.

**Theme:** light

Tailscale employs a pragmatic, enterprise-focused interface aesthetic: a spacious, bright white canvas with strong dark typography. Components are functional and subtly elevated, using soft shadows over hard borders, creating a sense of reliability without being overly decorative. A singular vivid red serves as a confident accent for primary actions and key highlights, puncturing an otherwise monochrome scheme of grays and off-whites. The overall impression is one of clarity, efficiency, and understated authority.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, card surfaces, interactive elements like pop-ups and modals |
| Surface Frost | `#f7f5f4` | `--color-surface-frost` | Subtle background for navigation or secondary content blocks, providing a soft lift from the main canvas |
| Canvas Pale | `#eeebea` | `--color-canvas-pale` | General page background for most sections, offering a warm off-white foundation |
| Graphite Black | `#181717` | `--color-graphite-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Storm Gray | `#2e2d2d` | `--color-storm-gray` | Secondary text for body copy, subheadings, and muted link states. Slightly softer than primary text |
| Stone Gray | `#575555` | `--color-stone-gray` | Muted helper text, secondary navigation items, and less prominent information |
| Smoke Gray | `#706e6d` | `--color-smoke-gray` | Tertiary text, copyright information, and borders requiring minimal emphasis |
| Cloud Mist | `#d5d3d2` | `--color-cloud-mist` | Subtle borders and dividers, indicating separation without visual weight |
| Border Light | `#232222` | `--color-border-light` | Ghost button text and borders, secondary action backgrounds |
| Action Red | `#d04841` | `--color-action-red` | Primary call-to-action buttons, active statuses, and key iconography requiring immediate attention. Provides a vivid focal point |
| Action Blue Gradient | `linear-gradient(in oklab, rgb(90, 130, 222) 0px, rgb(50, 73, 148) 100%)` | `--color-action-blue-gradient` | Decorative background gradient, used for visual highlights or product showcases |

## Tokens — Typography

### Inter — The primary typeface for all UI text, body copy, and most headings. Its range of weights and subtle tracking adjustments support both readability and hierachy. Letter spacing is consistently tightened for all sizes. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 20px, 32px, 48px, 64px
- **Line height:** 1.20, 1.43, 1.50
- **Letter spacing:** -0.36, -0.42, -0.48, -0.6, -0.96, -1.44, -1.92
- **Role:** The primary typeface for all UI text, body copy, and most headings. Its range of weights and subtle tracking adjustments support both readability and hierachy. Letter spacing is consistently tightened for all sizes.

### MDIO — A custom monospace-style typeface used sparingly for specific headings, code snippets, or data labels where a distinct, technical feel is desired. Wider tracking distinguishes it from Inter. · `--font-mdio`
- **Substitute:** system-ui, monospace
- **Weights:** 500
- **Sizes:** 12px, 14px, 20px
- **Line height:** 1.20, 1.50
- **Letter spacing:** 0.516, 0.602, 0.86
- **Role:** A custom monospace-style typeface used sparingly for specific headings, code snippets, or data labels where a distinct, technical feel is desired. Wider tracking distinguishes it from Inter.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.36px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.42px | `--text-body-sm` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 20px | 1.5 | -0.6px | `--text-subheading` |
| heading | 32px | 1.2 | -0.96px | `--text-heading` |
| heading-lg | 48px | 1.2 | -1.44px | `--text-heading-lg` |
| display | 64px | 1.2 | -1.92px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 84 | 84px | `--spacing-84` |
| 168 | 168px | `--spacing-168` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 16px |
| buttons | 8px |
| largeElements | 32px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(24, 23, 23, 0.02) 0px 4px 8px 0px` | `--shadow-sm` |
| md | `rgba(24, 23, 23, 0.16) 0px 4px 16px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 24-64px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Hero actions, main CTA buttons.

Background: Action Red (#d04841). Text: Canvas White (#FFFFFF). Radius: 8px. Padding: 10px vertical, 12px horizontal.

### Neutral Ghost Button
**Role:** Secondary calls to action, text links that behave as buttons.

Background: transparent. Text: Graphite Black (#181717). Border: 1px solid Graphite Black (#181717). Radius: 8px. Padding: 10px vertical, 12px horizontal.

### Secondary Ghost Button
**Role:** Tertiary actions, usually within a card or alongside a primary button.

Background: transparent. Text: Storm Gray (#2e2d2d). Border: 1px solid Canvas Pale (#eeebea). Radius: 16px. Padding: 24px.

### Status Tag
**Role:** Small informational labels, categories, or active state indicators.

Background: Canvas White (#FFFFFF). Text: Storm Gray (#2e2d2d). Border: 1px solid Canvas Pale (#eeebea). Radius: 9999px. Padding: 0px vertical, 18px horizontal.

### Feature Card
**Role:** Displaying product features or testimonials in a structured grid.

Background: Canvas White (#FFFFFF). Radius: 16px. Shadow: rgba(24, 23, 23, 0.02) 0px 4px 8px 0px. Padding: 32px.

### Large Feature Card
**Role:** Prominent feature display or marketing content with more visual emphasis.

Background: Canvas White (#FFFFFF). Radius: 32px. Shadow: rgba(24, 23, 23, 0.02) 0px 4px 8px 0px. Padding: 64px.

### Dark Content Panel
**Role:** Highlighting specific content sections with a darker background.

Background: Storm Gray (#2e2d2d). Radius: 32px. No shadow. Padding: 64px vertical, 48px horizontal.

## Do's and Don'ts

### Do
- Prioritize Inter for all typographic needs; reserve MDIO for specific labels or code-like elements.
- Use Graphite Black (#181717) for primary text and Storm Gray (#2e2d2d) for secondary body copy and subheadings.
- Apply Canvas Pale (#eeebea) as the default background for most page sections, and Canvas White (#ffffff) for card surfaces and modals.
- Utilize Action Red (#d04841) exclusively for primary action buttons and unambiguous active states; avoid its use for mere decoration.
- Employ soft shadow rgba(24, 23, 23, 0.02) 0px 4px 8px 0px for cards and elevated elements to provide subtle depth.
- Maintain a default border-radius of 16px for cards and 8px for buttons; use 9999px for pill-shaped elements like tags.
- Ensure consistent element spacing of 12px and card padding of 24px to maintain a comfortable density.

### Don't
- Do not introduce new vibrant colors beyond Action Red (#d04841) or the Action Blue Gradient (#5a82de).
- Avoid using hard borders on cards or primary UI elements; prefer a subtle shadow or light border for separation.
- Do not deviate from the established letter-spacing values, especially the negative tracking for Inter and positive tracking for MDIO.
- Do not use dark backgrounds for large content sections unless it's a specific, contained content panel with a distinct purpose.
- Do not clutter layouts; maintain ample white space around elements and between sections.
- Avoid heavy drop shadows or multiple layers of shadows; stick to the defined soft shadow for elevation.
- Do not use MDIO font for body text or large blocks of content; it is for specific, short labels or code.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Pale | `#eeebea` | Base page background, providing a light, warm foundation. |
| 1 | Canvas White | `#ffffff` | Elevated surfaces like cards, panels, and modals, providing contrast against the base canvas. |
| 2 | Dark Content Panel | `#2e2d2d` | Specific content blocks requiring a dark background for emphasis or thematic break. Does not typically stack on other elevated elements. |

## Elevation

- **Card:** `rgba(24, 23, 23, 0.02) 0px 4px 8px 0px`
- **Navigation Item / Button (on hover/focus):** `rgba(24, 23, 23, 0.16) 0px 4px 16px 0px`

## Imagery

The site primarily uses product screenshots and technical icons. Product screenshots are typically tight crops showcasing interface details, often within device mockups. Iconography is clean, outlined, and minimal, focusing on clarity and functionality; some decorative iconography uses flat, bold shapes with subtle color accents. Photography is absent, emphasizing a functional, software-centric approach. Imagery serves an explanatory or product showcase role, with a lean density that prioritizes text content.

## Layout

The page uses a maximum width containment for its primary content, centered on a light background. The hero section is characterized by a central headline and subtext, followed by a double button CTA group. Subsequent sections alternate between full-width simple card grids (e.g., trust signals like '30,000 businesses') and more complex arrangements that combine text and image/mockup panels. The overall rhythm maintains consistent vertical spacing between major sections, with content delivered in digestible blocks. Navigation is a sticky top bar with clearly delineated primary links and discrete action buttons.

## Agent Prompt Guide

**Quick Color Reference:**
text: #181717
background: #eeebea
border: #d5d3d2
accent: #5a82de
primary action: #d04841 (filled action)

**Example Component Prompts:**
1. Create a Primary Filled Button: background Action Red (#d04841), text Canvas White (#FFFFFF), 8px radius, 10px vertical 12px horizontal padding.
2. Create a Feature Card: background Canvas White (#FFFFFF), 16px radius, shadow rgba(24, 23, 23, 0.02) 0px 4px 8px 0px, 32px padding, with a heading using Inter 32px weight 600 Graphite Black (#181717).
3. Create a Secondary Ghost Button: transparent background, text Storm Gray (#2e2d2d), 1px solid Canvas Pale (#eeebea) border, 16px radius, 24px padding.

## Similar Brands

- **Figma** — Clear, bright UI with functional gray palette and singular brand accent color for actions.
- **Vercel** — Clean, spacious aesthetic focused on developer tools, with subtle shadows and strong typography.
- **Linear** — Minimalist design, strong focus on readability with high-contrast text, and restrained use of color.
- **Stripe** — White space dominant, clean typography, soft product imagery, and a subtle interplay of grays with a focused accent.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f7f5f4;
  --color-canvas-pale: #eeebea;
  --color-graphite-black: #181717;
  --color-storm-gray: #2e2d2d;
  --color-stone-gray: #575555;
  --color-smoke-gray: #706e6d;
  --color-cloud-mist: #d5d3d2;
  --color-border-light: #232222;
  --color-action-red: #d04841;
  --color-action-blue-gradient: #5a82de;
  --gradient-action-blue-gradient: linear-gradient(in oklab, rgb(90, 130, 222) 0px, rgb(50, 73, 148) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mdio: 'MDIO', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.6px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.44px;
  --text-display: 64px;
  --leading-display: 1.2;
  --tracking-display: -1.92px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-168: 168px;

  /* Layout */
  --section-gap: 24-64px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 16px;
  --radius-buttons: 8px;
  --radius-largeelements: 32px;

  /* Shadows */
  --shadow-sm: rgba(24, 23, 23, 0.02) 0px 4px 8px 0px;
  --shadow-md: rgba(24, 23, 23, 0.16) 0px 4px 16px 0px;

  /* Surfaces */
  --surface-canvas-pale: #eeebea;
  --surface-canvas-white: #ffffff;
  --surface-dark-content-panel: #2e2d2d;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f7f5f4;
  --color-canvas-pale: #eeebea;
  --color-graphite-black: #181717;
  --color-storm-gray: #2e2d2d;
  --color-stone-gray: #575555;
  --color-smoke-gray: #706e6d;
  --color-cloud-mist: #d5d3d2;
  --color-border-light: #232222;
  --color-action-red: #d04841;
  --color-action-blue-gradient: #5a82de;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mdio: 'MDIO', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.6px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.44px;
  --text-display: 64px;
  --leading-display: 1.2;
  --tracking-display: -1.92px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-168: 168px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(24, 23, 23, 0.02) 0px 4px 8px 0px;
  --shadow-md: rgba(24, 23, 23, 0.16) 0px 4px 16px 0px;
}
```
