# Tracky — Style Reference
> Playful productivity, high-contrast clarity

**Theme:** light

Tracky employs a playful yet focused productivity aesthetic, drawing strongly from a high-contrast dark navy (#151b31) and white (#ffffff) palette. Typography is a key differentiator, mixing a bold, wide sans-serif for impact with a highly readable modern sans for content. Accents are used sparingly as vital punctuation, injecting vivid red (#ff5858) for emphasis and a soft green (#86e0c1) for status, creating clear functional signals. Surfaces are generally flat and minimal, with subtle elevation used only for interactive elements and key cards.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#151b31` | `--color-midnight-ink` | Primary text, deep surface backgrounds, interactive button fills, borders, badge backgrounds — establishes a strong, focused presence |
| Spark Red | `#ff5858` | `--color-spark-red` | Accent for emphasized headlines, active links, and highlighting critical information, adding a dynamic and attention-grabbing element |
| Success Green | `#86e0c1` | `--color-success-green` | Feedback for success states, badges, and positive indicators, providing a soft, reassuring signal |
| Harvest Orange | `#ffb07b` | `--color-harvest-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, ghost button backgrounds/text, primary text on dark surfaces — provides a clean, expansive base |
| Carbon Text | `#333333` | `--color-carbon-text` | Secondary body text and general content text, providing strong readability against light backgrounds |
| Soft Fog | `#f2f2f2` | `--color-soft-fog` | Subtle page section backgrounds and muted borders, offering a gentle visual separation without stark contrast |
| Slate Text | `#6d6f75` | `--color-slate-text` | Muted helper text, secondary information, and subtle link text, creating a softer presence than primary text |
| Shadow Tint | `#e8e7e5` | `--color-shadow-tint` | Subtle shadow tint for cards, providing depth without heaviness |

## Tokens — Typography

### Inter — Body text, UI labels, links, and general content — chosen for its modern readability and versatility across many sizes and weights. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 16px, 18px, 20px, 22px, 24px, 36px, 108px
- **Line height:** 1.00, 1.10, 1.16, 1.18, 1.30, 1.40, 1.50, 1.55, 1.74
- **Letter spacing:** -0.0100em
- **Role:** Body text, UI labels, links, and general content — chosen for its modern readability and versatility across many sizes and weights.

### GRIFTER — Primary headlines and emphasized display text — its bold, wide character and slightly positive letter-spacing convey a confident, energetic brand voice. · `--font-grifter`
- **Substitute:** Impact
- **Weights:** 400, 700
- **Sizes:** 12px, 24px, 36px, 48px, 64px
- **Line height:** 1.00, 1.10, 1.20, 1.41, 2.00
- **Letter spacing:** 0.0300em
- **Role:** Primary headlines and emphasized display text — its bold, wide character and slightly positive letter-spacing convey a confident, energetic brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.12px | `--text-caption` |
| body-sm | 16px | 1.5 | -0.16px | `--text-body-sm` |
| body | 18px | 1.5 | -0.18px | `--text-body` |
| subheading | 20px | 1.4 | -0.2px | `--text-subheading` |
| heading-sm | 22px | 1.3 | -0.22px | `--text-heading-sm` |
| heading | 24px | 1.1 | 0.72px | `--text-heading` |
| heading-lg | 36px | 1.1 | 1.08px | `--text-heading-lg` |
| display | 108px | 1 | -1.08px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100% |
| cards | 16px |
| image | 8px |
| input | 8px |
| badges | 8px |
| buttons | 8px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0...` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) ...` | `--shadow-sm` |
| sm-2 | `rgba(138, 133, 125, 0.2) 0px 1px 4px 0px` | `--shadow-sm-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 15px
- **Element gap:** 20px

## Components

### Ghost Button
**Role:** Secondary action control

Transparent background with a Midnight Ink (#151b31) border, Midnight Ink text (Inter, weight 400), 8px border-radius, and 8px vertical / 24.5px horizontal padding. Features a subtle soft shadow on hover.

### Primary Filled Button
**Role:** Key action control

Solid Midnight Ink (#151b31) background with White Canvas (#ffffff) text (Inter, weight 400), matching Midnight Ink border, 8px border-radius, and 13px vertical / 65px horizontal padding. Used for prominent calls to action.

### Elevated Tool Card
**Role:** Interactive/featured content container

White Canvas (#ffffff) background, 8px border-radius, and a soft card shadow rgba(138, 133, 125, 0.2) 0px 1px 4px 0px. Features 9px vertical / 20px horizontal padding for contained elements.

### Solid Section Card
**Role:** Content grouping container

Midnight Ink (#151b31) background, 16px border-radius, and no shadow. Provides 48px top padding, 120px horizontal padding, and 0px bottom padding for content.

### Feature Badge - Success
**Role:** Informational tag for positive status

Success Green (#86e0c1) background with Midnight Ink (#151b31) text (Inter, weight 400), 8px border-radius, and 8px all-around padding.

### Pill Accent Badge
**Role:** Decorative or small status badge

Midnight Ink (#151b31) background with matching text color, 100% border-radius for a pill shape, and no padding. Used for small, contained visual indicators.

## Do's and Don'ts

### Do
- Prioritize the high-contrast pairing of Midnight Ink (#151b31) and White Canvas (#ffffff) for primary text and backgrounds to maintain visual clarity.
- Use GRIFTER for all major headlines to convey brand confidence, ensuring consistent positive letter-spacing of 0.03em.
- Apply Inter for all body text, UI elements, and labels, opting for a 1.5 line height for optimal readability.
- Use Spark Red (#ff5858) specifically for points of emphasis in headlines or active link states to draw immediate attention without overwhelming the design.
- Maintain a comfortable density with a base spacing unit of 4px and an `elementGap` of 20px for consistent visual rhythm between components.
- Apply 8px global border-radius for buttons, badges, and default elements, reserving 16px for larger content cards to differentiate structural surfaces.
- Employ subtle box shadows only for interactive components and key elevated cards to provide depth without making surfaces heavy.

### Don't
- Avoid using multiple chromatic colors for primary actions; Midnight Ink (#151b31) with White text is the established filled primary button style.
- Do not vary letter-spacing for Inter font family unless specifically defined in the type scale, as its default tracking is optimized for readability.
- Refrain from heavy, multi-layered shadows; elevation is minimal and serves to indicate interactivity or hierarchy, not decoration.
- Do not introduce new decorative elements or overly complex background textures; the design system favors clean surfaces and a direct, functional aesthetic.
- Avoid using Spark Red (#ff5858) for semantic 'error' states, as its primary role is brand highlighting and emphasis.
- Do not deviate from the defined border-radius values; the 8px/16px system is critical for consistent component identity.
- Do not fill Ghost Buttons with color; their transparent background with a distinct border is their defining characteristic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Soft Fog Canvas | `#f2f2f2` | Primary page background and subtle section dividers, offering a gentle, breathable foundation. |
| 1 | White Card Surface | `#ffffff` | Default background for content cards and panels, serving as a bright, clean surface for information. |
| 2 | Midnight Ink Panel | `#151b31` | Elevated card backgrounds and prominent sections, creating strong visual contrast and emphasis. |

## Elevation

- **Interactive Button:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px`
- **Highlighted Button:** `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px`
- **Elevated Tool Card:** `rgba(138, 133, 125, 0.2) 0px 1px 4px 0px`

## Imagery

Imagery features a mix of abstract, doodle-like illustrations and stylized product mockups. Illustrations are single-color outlines (gray, black) with occasional brand-color fills (e.g., blue, green, orange shapes) that appear scattered or in small, contained forms. Product screenshots are typically tight crops on simple, often dark or neutral backgrounds, highlighting the UI functionality directly without additional lifestyle context. Icons are simple, outlined, and monochromatic, used for decorative accents or functional navigation markers. The overall role is to add a playful, approachable personality and to clearly showcase product features in a clean, graphic manner.

## Layout

The page primarily uses a `max-width: 1200px` contained layout, with content centered. The hero section often breaks this, featuring full-bleed dark backgrounds with centered, expressive headlines. Section rhythm is created through alternating background colors (Soft Fog and White Canvas) or by using large Midnight Ink panels for key feature blocks. Content is typically arranged in clear, often two-column, text-left/image-right (or vice-versa) sections, with larger headlines and concise body copy. The layout feels spacious between sections but compact within content blocks, balancing breathability with information density. Navigation is a minimal top bar with simple text links and a ghost 'Login / Sign up' button.

## Agent Prompt Guide

### Quick Color Reference
- text: #151b31
- background: #f2f2f2
- border: #151b31
- accent: #ff5858
- primary action: #151b31 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed Midnight Ink (#151b31) background. Centered headline 'A new project management tool you'll actually love.' using GRIFTER weight 700. The word 'actually love.' should be Spark Red (#ff5858). Add a Primary Filled Button below it, 'Get started', with a Midnight Ink (#151b31) background, White Canvas (#ffffff) text (Inter weight 400), 8px border-radius, and 13px vertical / 65px horizontal padding.
2. Design a feature card: White Canvas (#ffffff) background, 8px border-radius, and the special card shadow rgba(138, 133, 125, 0.2) 0px 1px 4px 0px. Inner contents (e.g., text and icons) should have 9px vertical / 20px horizontal padding.
3. Implement a secondary navigation item: ghost button 'Login / Sign up' with a transparent background, Midnight Ink (#151b31) text (Inter weight 400), a 1px solid Midnight Ink (#151b31) border, 8px border-radius, and 8px vertical / 24.5px horizontal padding.
4. Show a positive status indicator: Feature Badge with Success Green (#86e0c1) background, Midnight Ink (#151b31) text (Inter weight 400), 8px border-radius, and 8px all-around padding.

## Similar Brands

- **Linear** — Shares a high-contrast dark UI (with deep dark blues/greys), structured layout, and a focus on subtle functional accents over decorative flair.
- **Raycast** — Employs a deep dark background with strong white typography for emphasis, similar clean, geometric UI elements, and a lightweight feeling.
- **Notion** — Utilizes a clean, white canvas with well-defined content blocks, clear typographic hierarchy, and a strong functional approach to component design, although with more emphasis on neutral colors.
- **Pitch** — Combines a playful illustration style with a clean, modern UI, using clear type hierarchies and strong accent colors for interactive elements and brand differentiation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #151b31;
  --color-spark-red: #ff5858;
  --color-success-green: #86e0c1;
  --color-harvest-orange: #ffb07b;
  --color-white-canvas: #ffffff;
  --color-carbon-text: #333333;
  --color-soft-fog: #f2f2f2;
  --color-slate-text: #6d6f75;
  --color-shadow-tint: #e8e7e5;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-grifter: 'GRIFTER', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.12px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.16px;
  --text-body: 18px;
  --leading-body: 1.5;
  --tracking-body: -0.18px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: 0.72px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 1.08px;
  --text-display: 108px;
  --leading-display: 1;
  --tracking-display: -1.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 15px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-pill: 100%;
  --radius-cards: 16px;
  --radius-image: 8px;
  --radius-input: 8px;
  --radius-badges: 8px;
  --radius-buttons: 8px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
  --shadow-sm-2: rgba(138, 133, 125, 0.2) 0px 1px 4px 0px;

  /* Surfaces */
  --surface-soft-fog-canvas: #f2f2f2;
  --surface-white-card-surface: #ffffff;
  --surface-midnight-ink-panel: #151b31;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #151b31;
  --color-spark-red: #ff5858;
  --color-success-green: #86e0c1;
  --color-harvest-orange: #ffb07b;
  --color-white-canvas: #ffffff;
  --color-carbon-text: #333333;
  --color-soft-fog: #f2f2f2;
  --color-slate-text: #6d6f75;
  --color-shadow-tint: #e8e7e5;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-grifter: 'GRIFTER', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.12px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.16px;
  --text-body: 18px;
  --leading-body: 1.5;
  --tracking-body: -0.18px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: 0.72px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 1.08px;
  --text-display: 108px;
  --leading-display: 1;
  --tracking-display: -1.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
  --shadow-sm-2: rgba(138, 133, 125, 0.2) 0px 1px 4px 0px;
}
```
