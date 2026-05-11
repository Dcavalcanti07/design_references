# Brainfish — Style Reference
> Playful productivity, layered surfaces.

**Theme:** light

Brainfish presents a vibrant, playful productivity aesthetic with a dominant light theme and an energetic neon green accent. The interface combines crisp black text and borders with soft, rounded backgrounds for interactive elements. Imagery is abstract or illustrative, maintaining a lighthearted feel. Subtle shadows with a slight offset add a tangible, almost physical quality to components, contrasting with flat backgrounds.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong borders, dark shadows — defines crisp edges and high contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, ghost button fills — provides a bright, expansive base |
| Charcoal Border | `#171717` | `--color-charcoal-border` | Muted borders, secondary text, and less prominent shadow base — adds definition without being as stark as Midnight Ink |
| Shadow Base | `#0a0a0d` | `--color-shadow-base` | Common shadow color — contributes to the subtle lift and depth of elements |
| Pale Ash | `#f5f5f5` | `--color-pale-ash` | Subtle background for footer sections — breaks up large expanses of Canvas White |
| Accent Green | `#a3e635` | `--color-accent-green` | Primary action buttons, active states, brand icons, and decorative fills — signals interaction and highlights key information with high energy |
| Card Saffron | `#fef3c8` | `--color-card-saffron` | Background for specific informational cards — adds a warm, inviting tone to content blocks |
| Card Lavender | `#fae9ff` | `--color-card-lavender` | Background for specific informational cards — introduces a soft, playful tint |
| Card Mint | `#d2fae5` | `--color-card-mint` | Background for specific informational cards — provides a cool, tranquil surface |
| Card Pink | `#f5d1fe` | `--color-card-pink` | Background for specific informational cards — a soft, decorative pop of color |
| Highlight Yellow | `#fbbf25` | `--color-highlight-yellow` | Callout card backgrounds, decorative elements — a vivid, attention-grabbing yellow |
| Honey Dew Gradient | `linear-gradient(rgb(253, 229, 177), rgb(252, 214, 131))` | `--color-honey-dew-gradient` | Decorative background gradient used in some sections — a soft, warm wash |
| Lime Spritz Gradient | `linear-gradient(rgb(219, 244, 181), rgb(198, 238, 137))` | `--color-lime-spritz-gradient` | Decorative background gradient used in some sections — a light, refreshing green blend |
| Sky Breeze Gradient | `linear-gradient(rgb(137, 229, 240), rgb(182, 239, 246) 27%, rgb(204, 243, 250) 35%, rgb(197, 243, 248) 55%)` | `--color-sky-breeze-gradient` | Primary hero background gradient, evoking an open sky with clouds — sets a light, optimistic tone |

## Tokens — Typography

### Satoshi — The primary typeface for all textual elements. Its consistent presence and moderate weights contribute to clear, readable content across all scales, from small UI labels to large headlines. Custom font, no system substitute provides the same character. · `--font-satoshi`
- **Substitute:** system-ui
- **Weights:** 500, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 36px, 48px, 64px
- **Line height:** 1.14, 1.16, 1.33, 1.38, 1.40, 1.42, 1.44, 1.50, 1.57, 1.67
- **Letter spacing:** -0.0210em at 64px, -0.0200em at 48px, -0.0170em at 36px, -0.0100em at 24px, -0.0090em at 20px, -0.0060em at 18px
- **Role:** The primary typeface for all textual elements. Its consistent presence and moderate weights contribute to clear, readable content across all scales, from small UI labels to large headlines. Custom font, no system substitute provides the same character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.67 | — | `--text-caption` |
| body-sm | 14px | 1.57 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.44 | -0.108px | `--text-subheading` |
| heading-sm | 20px | 1.42 | -0.18px | `--text-heading-sm` |
| heading | 24px | 1.4 | -0.24px | `--text-heading` |
| heading-lg | 32px | 1.38 | -0.544px | `--text-heading-lg` |
| display-sm | 36px | 1.33 | -0.612px | `--text-display-sm` |
| display | 48px | 1.16 | -0.96px | `--text-display` |
| display-lg | 64px | 1.14 | -1.344px | `--text-display-lg` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 100px |
| buttons | 4px |
| default | 4px |
| largeCards | 16px |
| extraLargeCards | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(10, 10, 13) 2px 2px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgb(10, 10, 13) 4px 4px 0px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgb(10, 10, 13) 1px 1px 0px 0px` | `--shadow-subtle-3` |
| subtle-4 | `rgb(23, 23, 23) 4px 4px 0px 0px` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Main call-to-action button.

Accent Green (#a3e635) background, Midnight Ink (#000000) text, 4px border-radius, 12px vertical padding, 24px horizontal padding. Features a subtle Charcoal Border (#171717) and Shadow Base (#0a0a0d) 1px 1px 0px 0px box-shadow.

### Ghost Action Button
**Role:** Secondary or outlined actions.

Canvas White (#ffffff) background, Midnight Ink (#000000) text, 4px border-radius, 8px vertical padding, 16px horizontal padding. Features a Charcoal Border (#171717) and Shadow Base (#0a0a0d) 1px 1px 0px 0px box-shadow.

### Text Link Button
**Role:** Minimal or inline actions.

Transparent background, Charcoal Border (#222222) and text. No border-radius. 2px top padding, 4px bottom padding, 0px horizontal padding.

### Content Card
**Role:** Information display card.

Canvas White (#ffffff) background, 8px border-radius, 24px padding. No box-shadow for this variant. Features a 1px solid Charcoal Border (#171717).

### Shadowed Content Card
**Role:** Prominent information display card.

Canvas White (#ffffff) background, 4px border-radius, 18px padding. Features an offset box-shadow: rgb(10, 10, 13) 1px 1px 0px 0px.

### Feature Card (Highlight Yellow)
**Role:** Specific feature highlight or testimonial card.

Highlight Yellow (#fbbf25) background, 8px border-radius, 16px vertical padding, 24px horizontal padding. No box-shadow.

### Subtle Background Card (No Padding)
**Role:** Sectional content container with minimal visual hierarchy.

Transparent background, 0px border-radius, 0px padding top/bottom, 32px padding left/right. No box-shadow or border. Used for full-width content blocks.

### Pill Badge
**Role:** Categorization or tagging element.

Canvas White (#ffffff) background, Midnight Ink (#000000) text, 100px border-radius for a pill shape, 6px vertical padding, 14px horizontal padding. Features a 1px solid Charcoal Border (#171717).

### Text Input Field
**Role:** User input element.

Canvas White (#ffffff) background, Midnight Ink (#000000) text, 4px border-radius, 12px padding all sides. Border color is a muted gray (#737373).

## Do's and Don'ts

### Do
- Use Accent Green (#a3e635) for all primary calls-to-action and active state indicators.
- Apply a subtle offset shadow (rgb(10, 10, 13) 2px 2px 0px 0px) to interactive elements and important cards for a 'lifted' effect.
- Prioritize Satoshi for all text, using varying weights and sizes from the scale to establish hierarchy and ensure consistency.
- Maintain high contrast text at 21.0:1 (Midnight Ink on Canvas White or Pale Ash) for optimal readability.
- Utilize 4px border-radius for buttons and input fields to convey a consistent, subtle roundness.
- Employ the 8px border-radius for standalone content cards, adding a softer, more approachable feel.
- Use distinct accent colors (Card Saffron, Card Lavender, Card Mint, Card Pink, Highlight Yellow) for content cards to visually differentiate sections and information types.

### Don't
- Avoid using bright, saturated colors for large background areas; reserve Canvas White or Pale Ash for expansive surfaces.
- Do not deviate from the Satoshi typeface; avoid system fonts or other custom fonts.
- Never apply aggressive or large drop shadows; stick to the specified subtle offset shadow values.
- Do not use dark backgrounds for main content sections; the theme is primarily light.
- Avoid random border-radii; adhere strictly to the 4px, 8px, and 100px values outlined for specific components.
- Do not use gradients for all backgrounds; reserve them for specific hero or decorative sections as defined.
- Refrain from using thin fonts for body text; Satoshi at 500 weight is the baseline for readability.

## Elevation

- **Button:** `rgb(10, 10, 13) 2px 2px 0px 0px`
- **Navigation Item:** `rgb(10, 10, 13) 2px 2px 0px 0px`
- **Card (prominent):** `rgb(10, 10, 13) 1px 1px 0px 0px`
- **Other:** `rgb(10, 10, 13) 2px 2px 0px 0px`

## Imagery

This design system uses a mix of abstract and illustrative graphics. Graphics are typically contained and used decoratively or to explain concepts. The hero section features light blue gradients with simple white outlined cloud illustrations and small, outlined fish illustrations, creating a playful, ethereal atmosphere. Other sections incorporate simple line icons (like 'Knowledge' or 'Distribution' icons) with a moderate stroke weight, typically monochromatic or occasionally accented with brand colors. Photography is not present. The overall role of imagery is atmospheric and explanatory, presented with a light touch and low density, keeping the UI text-dominant.

## Layout

The page structure utilizes a full-bleed layout for the hero section, featuring a light blue gradient background with centered large headlines. Subsequent sections alternate between full-width color bands (often with subtle gradient backgrounds like Honey Dew or Lime Spritz) and contained content blocks. Content is typically arranged in centered stacks or alternating text-left/image-right (or text-left/card-right) patterns. A 3-column card grid is often used for feature showcases. Vertical spacing between sections is generous and consistent. The navigation is a sticky top bar with a contained max-width, featuring primary action buttons prominently.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #171717
accent: #a3e635
primary action: #a3e635 (filled action)

Example Component Prompts:
Create a Primary Action Button: #a3e635 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a testimonial card: Feature Card (Highlight Yellow #fbbf25) 8px radius, 16px 24px padding. Quote text at 16px Satoshi weight 500 (#000000). Author and title at 14px Satoshi weight 500 (#000000). Below the quote, a Pill Badge (Canvas White #ffffff background, Midnight Ink text, 100px radius, 6px 14px padding, 1px solid Charcoal Border).

Create a general content section: Canvas White background. Headline at 48px Satoshi weight 700 (#000000, letter-spacing -0.96px). Body text at 16px Satoshi weight 500 (#000000). A Ghost Action Button (Canvas White #ffffff background, Midnight Ink text, 4px radius, 8px 16px padding) with a 1px solid Charcoal Border (#171717) and Shadow Base (#0a0a0d) 1px 1px 0px 0px box-shadow.

Create a text input field: Canvas White background, Midnight Ink (#000000) text, 4px radius, 12px padding. Border color: #737373.

## Similar Brands

- **Airtable** — Playful brand colors with rounded corners and a generally light UI aesthetic.
- **Notion** — Clean, predominantly white/light grey UI, sharp typography, and functional but minimal accent colors.
- **Linear** — Crisp typography and borders on a light canvas, with subtle shadows and a precise information density.
- **Figma** — Similar approach to UI elements with distinct border-radii, emphasis on a light theme, and clear, functional type hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-charcoal-border: #171717;
  --color-shadow-base: #0a0a0d;
  --color-pale-ash: #f5f5f5;
  --color-accent-green: #a3e635;
  --color-card-saffron: #fef3c8;
  --color-card-lavender: #fae9ff;
  --color-card-mint: #d2fae5;
  --color-card-pink: #f5d1fe;
  --color-highlight-yellow: #fbbf25;
  --color-honey-dew-gradient: #fce5b1;
  --gradient-honey-dew-gradient: linear-gradient(rgb(253, 229, 177), rgb(252, 214, 131));
  --color-lime-spritz-gradient: #dbeecf;
  --gradient-lime-spritz-gradient: linear-gradient(rgb(219, 244, 181), rgb(198, 238, 137));
  --color-sky-breeze-gradient: #89e5f0;
  --gradient-sky-breeze-gradient: linear-gradient(rgb(137, 229, 240), rgb(182, 239, 246) 27%, rgb(204, 243, 250) 35%, rgb(197, 243, 248) 55%);

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.67;
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.108px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.42;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.38;
  --tracking-heading-lg: -0.544px;
  --text-display-sm: 36px;
  --leading-display-sm: 1.33;
  --tracking-display-sm: -0.612px;
  --text-display: 48px;
  --leading-display: 1.16;
  --tracking-display: -0.96px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.14;
  --tracking-display-lg: -1.344px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 100px;
  --radius-buttons: 4px;
  --radius-default: 4px;
  --radius-largecards: 16px;
  --radius-extralargecards: 20px;

  /* Shadows */
  --shadow-subtle: rgb(10, 10, 13) 2px 2px 0px 0px;
  --shadow-subtle-2: rgb(10, 10, 13) 4px 4px 0px 0px;
  --shadow-subtle-3: rgb(10, 10, 13) 1px 1px 0px 0px;
  --shadow-subtle-4: rgb(23, 23, 23) 4px 4px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-charcoal-border: #171717;
  --color-shadow-base: #0a0a0d;
  --color-pale-ash: #f5f5f5;
  --color-accent-green: #a3e635;
  --color-card-saffron: #fef3c8;
  --color-card-lavender: #fae9ff;
  --color-card-mint: #d2fae5;
  --color-card-pink: #f5d1fe;
  --color-highlight-yellow: #fbbf25;
  --color-honey-dew-gradient: #fce5b1;
  --color-lime-spritz-gradient: #dbeecf;
  --color-sky-breeze-gradient: #89e5f0;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.67;
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.108px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.42;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.38;
  --tracking-heading-lg: -0.544px;
  --text-display-sm: 36px;
  --leading-display-sm: 1.33;
  --tracking-display-sm: -0.612px;
  --text-display: 48px;
  --leading-display: 1.16;
  --tracking-display: -0.96px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.14;
  --tracking-display-lg: -1.344px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-subtle: rgb(10, 10, 13) 2px 2px 0px 0px;
  --shadow-subtle-2: rgb(10, 10, 13) 4px 4px 0px 0px;
  --shadow-subtle-3: rgb(10, 10, 13) 1px 1px 0px 0px;
  --shadow-subtle-4: rgb(23, 23, 23) 4px 4px 0px 0px;
}
```
