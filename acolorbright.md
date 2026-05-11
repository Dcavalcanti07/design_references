# Acolorbright — Style Reference
> Black-on-white architectural blueprint.

**Theme:** light

Acolorbright employs a sophisticated, monochromatic design palette, focusing on a stark contrast between near-black text and crisp white surfaces, occasionally interrupted by subtle gray accents. Typography is compact and deliberate, using a single proprietary sans-serif family with precise letter-spacing to optimize information density. Components are lightweight, favoring thin borders and minimal padding, contributing to an open, breathable layout that prioritizes content display over heavy decorative elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1a1a1a` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Graphite | `#666666` | `--color-graphite` | Muted body text, secondary information, subtle backgrounds and borders |
| Storm Gray | `#999999` | `--color-storm-gray` | Decorative text, inactive navigation items, faint borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button backgrounds, primary navigation text |
| Snowdrift | `#f2f2f2` | `--color-snowdrift` | Subtle background for list items or grouped content, providing slight differentiation from Canvas White |
| Onyx | `#000000` | `--color-onyx` | Icon fills, specific button text against lighter backgrounds, heavy borders |
| Charcoal Button | `#262626` | `--color-charcoal-button` | Solid button background for specific calls to action, providing strong contrast |
| Ghost Border | `#e6e6e6` | `--color-ghost-border` | Light border for ghost buttons and subtle separations |
| Case Study Violet | `#6a00ff` | `--color-case-study-violet` | Accent color for case study cards — a vibrant visual identifier |
| Case Study Lime | `#a3ff00` | `--color-case-study-lime` | Accent color for case study cards — a vibrant visual identifier |
| Swiper Blue | `#007aff` | `--color-swiper-blue` | Internal UI accent for components like carousels (swiper theme) |

## Tokens — Typography

### RiformaLLWeb — The primary typeface for all textual content, from body to headlines. Its compact forms and subtle negative letter-spacing contribute to an efficient, modern aesthetic. · `--font-riformallweb`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px, 18px, 24px, 40px, 64px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.25
- **Letter spacing:** -0.01em
- **OpenType features:** `"liga" 0`
- **Role:** The primary typeface for all textual content, from body to headlines. Its compact forms and subtle negative letter-spacing contribute to an efficient, modern aesthetic.

### Arial — Used for specific, small informational text, possibly in legacy components or specific UI elements where system font fallback is preferred. · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for specific, small informational text, possibly in legacy components or specific UI elements where system font fallback is preferred.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | -0.12px | `--text-caption` |
| body | 16px | 1.2 | -0.16px | `--text-body` |
| subheading | 18px | 1.2 | -0.18px | `--text-subheading` |
| heading | 24px | 1.15 | -0.24px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.4px | `--text-heading-lg` |
| display | 64px | 1 | -0.64px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| image | 12px |
| lists | 8px |
| buttons | 8px |
| default | 12px |
| navigation | 8px |
| interactiveIcon | 16px |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Outline Ghost Button
**Role:** Secondary action or informational button.

Text in Graphite (#999999) or Onyx (#000000) on a transparent background, with a 1px border of Ghost Border (#e6e6e6) or Midnight Ink (#1a1a1a). Padding is 1px top/bottom, 6px left/right. Radius is 8px.

### Solid Dark Button
**Role:** Primary Call to Action button.

Background Charcoal Button (#262626) with text in Storm Gray (#999999). Padding is 12px top/bottom, 16px left/right. Radius is 8px.

### Navigation Link
**Role:** Main navigation items.

Text in Midnight Ink (#1a1a1a) or Canvas White (#ffffff). Interactivity may involve a border of Midnight Ink (#1a1a1a) or Canvas White (#ffffff). Radius is 8px for the containing element, potentially 16px for interactive icons.

### Informational Card
**Role:** Content grouping, such as case studies or feature descriptions.

Transparent background with no distinct box-shadow. Radius is 12px. Padding is implicitly flexible depending on content, often 0px, with internal element gaps typically 4px or 8px.

### Case Study Thumbnail
**Role:** Visual representation for portfolio items.

Contains an image or solid color background (e.g., Case Study Violet #6a00ff, Case Study Lime #a3ff00) with a 12px border radius. Often appears without explicit padding.

## Do's and Don'ts

### Do
- Prioritize RiformaLLWeb at 400 weight for all text elements to maintain a consistent tone, using negative letter-spacing of -0.01em.
- Use Midnight Ink (#1a1a1a) for primary text and headings, offering high contrast against Canvas White (#ffffff) backgrounds.
- Employ Canvas White (#ffffff) as the dominant background for all main content areas and cards, creating an open, bright feel.
- Utilize an 8px border-radius for buttons and navigation elements, and a 12px radius for larger content blocks like images or general containers.
- Maintain a comfortable density with an `elementGap` of 12px for vertical rhythm between small items and `sectionGap` of 32px for major content blocks.
- Subtly differentiate background layers using Snowdrift (#f2f2f2) for list items or grouped content, distinct from the primary Canvas White.
- Use thin borders (1px) in Midnight Ink (#1a1a1a) or Ghost Border (#e6e6e6) to define interactive elements or subtle card outlines.

### Don't
- Avoid using highly saturated colors for large background areas; reserve vivid hues like #6a00ff or #a3ff00 for selective accents in case study blocks or graphics.
- Do not deviate from the RiformaLLWeb font family for core interface text; Arial is for specific, small utility text only.
- Do not introduce heavy box shadows or gradients for elevation; maintain a flat aesthetic, using slight background color differentiation for depth when needed.
- Avoid excessive padding within cards; prefer a light touch to keep content compact and allow for generous negative space between components.
- Do not use highly contrasting or varied button styles for primary actions; stick to Solid Dark Button (#262626) or the subtly outlined ghost variants.
- Never use text colors lighter than Graphite (#666666) for body text on Canvas White (#ffffff) backgrounds, as readability will be compromised.
- Do not introduce complex, multi-color icon systems; keep icons monochromatic, typically in Onyx (#000000) or Midnight Ink (#1a1a1a).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default card surface. |
| 1 | Snowdrift | `#f2f2f2` | Subtlety elevated background for list items or distinct content sections. |
| 2 | Charcoal Button | `#262626` | Background for focused interactive elements like primary buttons. |

## Imagery

Imagery primarily consists of high-quality product screenshots, often presented within mockups of devices, along with abstract branding visuals for case studies. Photography is rare and appears to be candid, event-focused, or lifestyle-oriented when used, with a bright, natural color treatment. Illustrations are minimal, tending towards abstract, geometric shapes for branding elements with flat, filled styles using the accent colors. Icons are outlined, monochromatic (typically black or dark gray), and serve a functional rather than decorative role, maintaining a consistent stroke weight. The overall density is balanced, allowing significant text content to coexist with visual examples, but imagery is always contained and never full-bleed.

## Layout

The page adheres to a centered maximum width with responsive margins, providing a clean frame for the content. The hero section introduces a prominent, centered headline over a white background, setting a calm, informative tone. Content sections primarily follow a stacked, linear flow with consistent vertical spacing. Feature and portfolio sections often employ a grid layout, typically three columns for case study thumbnails, with alternating visual styles (product screenshots vs. vibrant color blocks). Navigation is a sticky top bar with a minimal hamburger menu icon, suggesting an uncluttered user experience.

## Agent Prompt Guide

Quick Color Reference:
text: #1a1a1a
background: #ffffff
border: #1a1a1a
accent: #6a00ff
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary headline: 'We’re a brand and product design studio.' using RiformaLLWeb, 64px, weight 400, color Midnight Ink (#1a1a1a), lineHeight 1.0, letterSpacing -0.64px.
2. Create a secondary information paragraph: 'Leading brands choose us.' using RiformaLLWeb, 16px, weight 400, color Graphite (#666666), lineHeight 1.2, letterSpacing -0.16px.
3. Design a Solid Dark Button: Background Charcoal Button (#262626), text Storm Gray (#999999), 12px vertical padding, 16px horizontal padding, 8px border-radius, using RiformaLLWeb 16px weight 400 text.
4. Construct an Informational Card with a Case Study Thumbnail: A 12px border-radius container with a transparent background, containing a graphic with a #6a00ff background and 12px radius. Above the graphic, a descriptive text in RiformaLLWeb 16px, weight 400, color Midnight Ink (#1a1a1a).

## Similar Brands

- **Aether** — Shares a monochromatic palette with crisp white backgrounds and strong black typography, using color sparingly for accents or differentiating content blocks.
- **Brevity** — Similar approach to compact typography and generous negative space, creating a refined, content-focused atmosphere with minimal decorative elements.
- **GraphCMS** — Exhibits a clean, direct visual style with a focus on structured content, subtle grays for hierarchy, and distinct product imagery.
- **Vercel** — Employs a minimalist, functional aesthetic with strong typographic hierarchy, monochromatic UI elements, and a subtle interplay of grays.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1a1a1a;
  --color-graphite: #666666;
  --color-storm-gray: #999999;
  --color-canvas-white: #ffffff;
  --color-snowdrift: #f2f2f2;
  --color-onyx: #000000;
  --color-charcoal-button: #262626;
  --color-ghost-border: #e6e6e6;
  --color-case-study-violet: #6a00ff;
  --color-case-study-lime: #a3ff00;
  --color-swiper-blue: #007aff;

  /* Typography — Font Families */
  --font-riformallweb: 'RiformaLLWeb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: -0.12px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.4px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-image: 12px;
  --radius-lists: 8px;
  --radius-buttons: 8px;
  --radius-default: 12px;
  --radius-navigation: 8px;
  --radius-interactiveicon: 16px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-snowdrift: #f2f2f2;
  --surface-charcoal-button: #262626;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1a1a1a;
  --color-graphite: #666666;
  --color-storm-gray: #999999;
  --color-canvas-white: #ffffff;
  --color-snowdrift: #f2f2f2;
  --color-onyx: #000000;
  --color-charcoal-button: #262626;
  --color-ghost-border: #e6e6e6;
  --color-case-study-violet: #6a00ff;
  --color-case-study-lime: #a3ff00;
  --color-swiper-blue: #007aff;

  /* Typography */
  --font-riformallweb: 'RiformaLLWeb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: -0.12px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.4px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
}
```
