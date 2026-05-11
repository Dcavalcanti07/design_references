# Kajabi — Style Reference
> Crisp monochrome command panel on a limitless white canvas.

**Theme:** light

Kajabi's design system is a high-contrast, modern aesthetic pairing deep, commanding neutrals with crisp white surfaces. Typography is the primary visual driver, featuring compact, confident sans-serif headlines and functional body text. Components are minimalist and structured, emphasizing clear information hierarchy over decorative flourishes, with sharp edges and subtle radius rounding maintaining a serious, professional tone.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0a0a0a` | `--color-midnight-ink` | Primary text, dark surface backgrounds, button fills, and strong borders. This color provides a deep, commanding presence |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, light card surfaces, button text. It serves as the expansive, clean base layer |
| Charcoal Surface | `#1f1f1e` | `--color-charcoal-surface` | Elevated dark card backgrounds, distinct sections requiring visual separation from Midnight Ink |
| Ash Gray | `#e9e8e7` | `--color-ash-gray` | Subtle section backgrounds, providing a soft lift from Canvas White without introducing strong color |
| Slate Text | `#535250` | `--color-slate-text` | Secondary text, muted links, subtle borders for less prominent elements |
| Silver Border | `#e0dedc` | `--color-silver-border` | Hairline borders, subtle dividers. A very light gray that prevents harsh lines |
| Stone Accent | `#949189` | `--color-stone-accent` | Muted icon fills, inactive states, and tertiary text |
| Green Accent | `#405b50` | `--color-green-accent` | Rare decorative accents, such as a background highlight for specific sections. Its near-gray saturation allows it to blend into the neutral palette |

## Tokens — Typography

### Haffer — Used universally across headlines, body text, links, and buttons. Its varied weights and negative letter-spacing contribute to the compact, self-assured character of the interface, making text feel deliberate and modern. · `--font-haffer`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 28px, 32px, 40px, 48px, 60px
- **Line height:** 1.00, 1.10, 1.20, 1.43, 1.45, 1.50
- **Letter spacing:** -0.0300em at large sizes, -0.0200em at medium sizes
- **Role:** Used universally across headlines, body text, links, and buttons. Its varied weights and negative letter-spacing contribute to the compact, self-assured character of the interface, making text feel deliberate and modern.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.45 | — | `--text-body-sm` |
| body | 16px | 1.45 | — | `--text-body` |
| subheading | 20px | 1.43 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | — | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.6px | `--text-heading-lg` |
| display | 60px | 1 | -1.8px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 15984px |
| default | 2px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Dark Button
**Role:** Call-to-action button for initiating key actions.

Filled with Midnight Ink (#0a0a0a), Canvas White (#ffffff) text, 2px border-radius, with 12px vertical and 24px horizontal padding. Uses Haffer font, weight 400.

### Ghost Light Button
**Role:** Secondary action or navigational link with low visual hierarchy.

Transparent background, Canvas White (#ffffff) text and 1px border, 2px border-radius, with 12px padding. Uses Haffer font, weight 400.

### Light Button
**Role:** Positive action button where contrast is needed against a dark background.

Filled with Canvas White (#ffffff), Midnight Ink (#0a0a0a) text, 2px border-radius, with 12px vertical and 24px horizontal padding. Uses Haffer font, weight 400.

### Input Field
**Role:** Standard input for user data entry.

Transparent background, Slate Text (#333333) for input value, Midnight Ink (#000000) bottom border, with 12px vertical and 16px horizontal padding. Uses Haffer font.

### Dark Card
**Role:** Container for content within dark sections.

Charcoal Surface (#1f1f1e) background, 4px border-radius, with 40px all-around padding. No box-shadow.

### Transparent Content Card
**Role:** A minimal, borderless grouping element often used for media or subtle content organization.

Transparent background, 0px border-radius, and 0px padding. Primarily used for visual arrangements without defined boundaries.

## Do's and Don'ts

### Do
- Prioritize Haffer typography for all text elements, maintaining negative letter-spacing for larger sizes to achieve a compact aesthetic.
- Use Midnight Ink (#0a0a0a) for primary text and dark backgrounds, and Canvas White (#ffffff) for page backgrounds and light surfaces, establishing the strong monochrome base.
- Apply a 2px border-radius consistently to all interactive elements and contained components like buttons and image frames.
- Establish clear visual hierarchy using distinct solid borders, defaulting to 1px wide lines using Silver Border (#e0dedc) for subtle separation.
- Maintain generous section and element spacing to provide ample breathing room, adhering to 4px increments; use Element Gap (8px) for individual elements and Card Padding (20px) for internal card content.
- Utilize Charcoal Surface (#1f1f1e) for elevated cards or distinct sections to create depth without relying on shadows.

### Don't
- Avoid decorative gradients or strong chromatic colors; restrict accents to Green Accent (#405b50) in specific, minimal use cases.
- Do not deviate from the Haffer font family; custom system fonts are not part of this brand's identity.
- Do not use box-shadows for elevation; rely on background color changes or borders to differentiate layers.
- Never create rounded corners greater than 2px on interactive elements unless designing specific pill-shaped components at 15984px.
- Avoid dense, information-heavy blocks; always ensure ample white space around content and within components.
- Do not use generic system UI elements; all components should map to the specified visual tokens.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Ash Gray | `#e9e8e7` | Subtle background for differentiating content sections |
| 2 | Green Accent | `#405b50` | Accent background for specific content blocks |
| 3 | Charcoal Surface | `#1f1f1` | Elevated card backgrounds within dark sections |
| 4 | Midnight Ink | `#0a0a0a` | Dominant dark background for hero sections and footers |

## Elevation

This design system deliberately avoids visible box-shadows. Elevation and hierarchy are conveyed through changes in background color (e.g., Charcoal Surface on Midnight Ink) and crisp, defined borders, maintaining a flat, modern aesthetic.

## Imagery

The visual language for imagery is primarily photography: portrait-style headshots of individuals, cropped tightly and presented within square or slightly rounded frames. Product shots are also used, often contained with clean backgrounds. All imagery serves an explanatory or social proof role, rather than decorative. Iconography is minimalist, outlined, and monochromatic, integrated seamlessly into the text, retaining a lightweight feel.

## Layout

The page primarily uses a max-width contained layout, though the hero section is full-bleed with a centered headline over a dark background. Sections alternate between light and dark themes, creating distinct visual blocks. Content is often arranged in symmetrical stacks or two-column layouts with text and visuals balanced. Card grids are used for features, showcasing clear divisions between items. Overall density is comfortable, ensuring sufficient negative space.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0a0a
background: #ffffff
border: #e0dedc
accent: #405b50
primary action: #0a0a0a (filled action)

Example Component Prompts:
1. Create a hero section: Midnight Ink (#0a0a0a) background. Headline at 60px Haffer weight 600, Canvas White (#ffffff), letter-spacing -1.8px. Subtext at 20px Haffer weight 400, Canvas White (#ffffff), line-height 1.43. Include a Primary Dark Button.
2. Create a feature card: Ash Gray (#e9e8e7) background. Heading at 24px Haffer weight 500, Midnight Ink (#0a0a0a), line-height 1.2. Body text at 16px Haffer weight 400, Slate Text (#535250), line-height 1.45. Ensure 20px padding and a 2px border-radius.
3. Create a navigation link: Haffer font 16px weight 400, Slate Text (#535250), hover color Midnight Ink (#0a0a0a), with 24px horizontal padding.

## Similar Brands

- **Stripe** — High-contrast monochrome palette with sans-serif type, structured layout, and emphasis on clear content blocks over decorative elements.
- **Linear** — Clean, functional typography, dark mode options with minimal color accents, and a focus on clarity through strict visual hierarchy.
- **Webflow** — Strategic use of dark and light sections, sharp edges or subtle rounding, and strong typographic presence for headlines.
- **Notion** — Productivity-focused, clean UI with a strong emphasis on typography and a muted color palette, primarily distinguishing elements through background shades and subtle borders.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-charcoal-surface: #1f1f1e;
  --color-ash-gray: #e9e8e7;
  --color-slate-text: #535250;
  --color-silver-border: #e0dedc;
  --color-stone-accent: #949189;
  --color-green-accent: #405b50;

  /* Typography — Font Families */
  --font-haffer: 'Haffer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.45;
  --text-body: 16px;
  --leading-body: 1.45;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.6px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-full: 15984px;

  /* Named Radii */
  --radius-pill: 15984px;
  --radius-default: 2px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ash-gray: #e9e8e7;
  --surface-green-accent: #405b50;
  --surface-charcoal-surface: #1f1f1;
  --surface-midnight-ink: #0a0a0a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-charcoal-surface: #1f1f1e;
  --color-ash-gray: #e9e8e7;
  --color-slate-text: #535250;
  --color-silver-border: #e0dedc;
  --color-stone-accent: #949189;
  --color-green-accent: #405b50;

  /* Typography */
  --font-haffer: 'Haffer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.45;
  --text-body: 16px;
  --leading-body: 1.45;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.6px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

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
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-full: 15984px;
}
```
