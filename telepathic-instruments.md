# Telepathic Instruments — Style Reference
> Techno-futurist laboratory

**Theme:** light

Telepathic Instruments blends scientific product UI with artistic ambiguity. The interface centers on a minimal, high-contrast monochrome palette, punctuated by a single vibrant orange accent. Typography is compact and precise, using a bespoke geometric sans-serif that lends a technical yet refined feel. Visuals often feature abstract, blurry backgrounds with sparse, distinct elements foregrounded, creating a sense of unfolding discovery.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#e5e7eb` | `--color-canvas` | Page background, primary surface, subtle borders |
| Charcoal | `#000000` | `--color-charcoal` | Primary text, solid button backgrounds, strong outlines, header bar background |
| Snow | `#ffffff` | `--color-snow` | Button text on dark backgrounds, card backgrounds, light text accents |
| Steel | `#a3a3a3` | `--color-steel` | Muted text, secondary navigation, input borders, icon strokes |
| Ash | `#191919` | `--color-ash` | Darker background accents, subtle fills in complex elements |
| Mercury | `#c2c2c2` | `--color-mercury` | Subtle background accents, dividers |
| Powder | `#dddee2` | `--color-powder` | Light background accents, very subtle surface differentiators |
| Muted Sage | `#d7cdb8` | `--color-muted-sage` | Decorative graphical elements, subtle background textures |
| Amber Glow | `#ff6c2f` | `--color-amber-glow` | Orange action color for filled buttons, selected navigation states, and focused conversion moments. |

## Tokens — Typography

### Suisse Intl — Primary text, headings, general UI labels. The tighter letter-spacing at larger sizes (-0.0300em for 100px) enhances its controlled, technical feel. · `--font-suisse-intl`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px, 18px, 20px, 24px, 100px
- **Line height:** 0.85, 1.20, 1.25, 1.40, 1.50
- **Letter spacing:** -0.0300em, -0.0200em
- **Role:** Primary text, headings, general UI labels. The tighter letter-spacing at larger sizes (-0.0300em for 100px) enhances its controlled, technical feel.

### Suisse Intl Mono — Code snippets, data displays, subtle navigation items, input values. Its fixed-width nature reinforces the technical aesthetic. · `--font-suisse-intl-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Code snippets, data displays, subtle navigation items, input values. Its fixed-width nature reinforces the technical aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.25 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| display | 100px | 0.85 | -0.03px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| large | 32px |
| buttons | 24px |
| default | 2px |
| circular | 9999px |

### Layout

- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action button for primary actions.

Solid Charcoal background (#000000) with Snow text (#ffffff), 24px border radius, 14px vertical padding, 16px horizontal padding. Font is Suisse Intl weight 400.

### Amber Glow Action Button
**Role:** Highlighting a key action for immediate visibility.

Solid Amber Glow background (#ff6c2f) with Snow text (#ffffff), 24px border radius, 14px vertical padding, 16px horizontal padding. Font is Suisse Intl weight 400.

### Ghost Button
**Role:** Secondary and tertiary actions that require less visual emphasis.

Transparent background with Snow text (#ffffff), 0px border radius, 8px padding. Has a 1px Steel (#a3a3a3) border for outline definition. Font is Suisse Intl Mono weight 400.

### Text Link Button
**Role:** Low-prominence inline actions or navigation.

Transparent background with Charcoal text (#000000), 24px border radius, 0px vertical padding, 16px horizontal padding. Font is Suisse Intl weight 400.

### Product Card
**Role:** Displaying product information or content blocks.

Transparent background with 0px border radius and no box shadow. Content relies on surrounding layout for definition. Padding is 0px.

### Form Input
**Role:** User input fields.

Transparent background, Steel text (#a3a3a3), and a 'Steel' bottom border. 0px border radius, 0px vertical padding, 12px horizontal padding. Uses Suisse Intl Mono font. Placeholder text is Steel (#a3a3a3).

## Do's and Don'ts

### Do
- Prioritize Charcoal (#000000) for primary text and Snow (#ffffff) for backgrounds to maintain a high-contrast base.
- Use Amber Glow (#ff6c2f) exclusively for primary calls-to-action like 'Join Mailing List' to ensure its impact.
- Apply Suisse Intl with tight letter-spacing (-0.0300em for 100px text) for headlines to create a sharp, modern feel.
- Use Suisse Intl Mono for any technical or data-driven text, like input fields or code, to convey precision.
- Maintain minimal padding (8px, 12px) and flush card designs (0px border radius, no shadow) to keep surfaces lightweight.
- Construct button corners with a large radius (24px) for a soft, approachable pill-like shape, or 0px for Ghost Buttons.
- Apply backdrop filters for blurring to backgrounds in hero sections or behind overlays to create depth and focus on foreground elements.

### Don't
- Avoid using Amber Glow (#ff6c2f) as a general-purpose color; limit its use to primary interactive elements.
- Do not introduce additional bold or highly saturated colors unless they are part of explicit product branding within content areas.
- Refrain from using heavy box shadows or strong borders on cards; surfaces should appear flat or subtly defined by their surroundings.
- Do not deviate from the specified tight letter-spacing for Suisse Intl at larger sizes; it's key to the typographical identity.
- Avoid creating layouts that feel dense or cluttered; maintain generous negative space and clear section breaks (40px).
- Do not use generic system fonts; always default to Suisse Intl or Suisse Intl Mono for all text elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#e5e7eb` | Primary page and content background. |
| 1 | Card Surface | `#ffffff` | Elevated content blocks on the canvas. |
| 2 | Base Dark Surface | `#000000` | Navbar background, dark content sections, primary buttons. |

## Imagery

Imagery is a mix of abstract, blurry digital graphics and product-focused photography/screenshots. Abstract graphics often feature teal/green hues on dark backgrounds, using blur effects to create depth and mystery. Product photography is clean and focused, showing items like beanies and t-shirts in simple, outdoor settings or clear product shots with minimal distraction. Product screenshots (e.g., the synth plugin) are UI-focused, showcasing the interface clearly. Icons are primarily outlined or filled monochrome, often in Steel or Snow. The overall role of imagery leans towards atmospheric (abstract graphics) and explanatory/showcasing (product shots). Imagery density is moderate; hero sections are image-heavy, while other sections are text-dominant with smaller supporting visuals.

## Layout

The site employs a full-bleed page model, allowing background elements to extend to the edges of the viewport. The hero section is full-bleed with a dark, abstract background and a large, centered headline. Content sections generally use alternating background colors (Canvas / Snow) to define distinct areas, separated by a section gap of 40px. Content within sections tends to be centrally aligned or structured in two-column layouts (text beside image/product feature). There's evidence of card grids for displaying products or user-generated content. The navigation is a sticky top bar, minimal and high-contrast, becoming fully opaque on scroll.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #e5e7eb
border: #a3a3a3
accent: #ff6c2f
primary action: #ff6c2f (filled action)

Example Component Prompts:
1. Create a hero section: Charcoal background. Headline 'This May. All will become clear.' at 100px Suisse Intl weight 400, Snow text (#ffffff), letter-spacing -30px. Centered. Below, an Amber Glow Action Button 'Join Mailing List' (Amber Glow background #ff6c2f, Snow text #ffffff, 24px radius, 14px 16px padding).
2. Design a product card: Transparent background, no border radius, 0px padding. Image of 'Orange Orchid Beanie', beneath it 'Orange Orchid Beanie' as heading-sm Suisse Intl weight 400 #000000, 12px element gap, with a small caption in Suisse Intl Mono weight 400 #a3a3a3.
3. Create a navigation bar item: Text 'Orchid' in Snow (#ffffff) Suisse Intl Mono weight 400 at 16px, normal letter-spacing. Use 6px horizontal padding between items. On hover, text color slightly darkens to Steel (#a3a3a3).

## Similar Brands

- **Teenage Engineering** — Minimalist, technical UI with a focus on core functionality and distinct typography, often using stark contrasts.
- **Arturia** — Clean, dark product interfaces for audio software, blending realism with functional design through precise controls and typography.
- **Native Instruments** — Sophisticated, often dark-themed music production software interfaces with compact controls and distinct monochromatic color palettes accented by specific hues.
- **Orbital.cx** — Abstract, atmospheric, dark-background hero sections with sparse, futuristic typography and highly curated product highlights.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #e5e7eb;
  --color-charcoal: #000000;
  --color-snow: #ffffff;
  --color-steel: #a3a3a3;
  --color-ash: #191919;
  --color-mercury: #c2c2c2;
  --color-powder: #dddee2;
  --color-muted-sage: #d7cdb8;
  --color-amber-glow: #ff6c2f;

  /* Typography — Font Families */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-mono: 'Suisse Intl Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 100px;
  --leading-display: 0.85;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 64px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-large: 32px;
  --radius-buttons: 24px;
  --radius-default: 2px;
  --radius-circular: 9999px;

  /* Surfaces */
  --surface-canvas: #e5e7eb;
  --surface-card-surface: #ffffff;
  --surface-base-dark-surface: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #e5e7eb;
  --color-charcoal: #000000;
  --color-snow: #ffffff;
  --color-steel: #a3a3a3;
  --color-ash: #191919;
  --color-mercury: #c2c2c2;
  --color-powder: #dddee2;
  --color-muted-sage: #d7cdb8;
  --color-amber-glow: #ff6c2f;

  /* Typography */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-mono: 'Suisse Intl Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 100px;
  --leading-display: 0.85;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 64px;
}
```
