# Beau — Style Reference
> monochrome precision, vibrant core

**Theme:** light

Beau employs a crisp, structured aesthetic with a high-contrast monochrome palette. The design emphasizes clear information hierarchy through distinct text sizing and weight, creating a feeling of efficient precision. Components are lightweight and purposeful, relying on shape and direct color contrast rather than heavy ornamentation or shadows. A striking multi-color gradient introduces vibrancy in specific sections, acting as an energetic backdrop for otherwise stark content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, active states for text and icons. Provides a bright, expansive base for all content |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, button backgrounds, strong borders, dark card surfaces. Establishes a bold and clear contrast against Canvas White |
| Subtle Gray | `#999999` | `--color-subtle-gray` | Secondary text, muted headings, subtle borders. Used for information that needs to recede slightly from primary content |
| Whisper Gray | `#666666` | `--color-whisper-gray` | Tertiary text, descriptive labels, less emphasized content. Creates a softer textual presence |
| Silver Mist | `#b3b3b3` | `--color-silver-mist` | Subtle background fill, badge backgrounds. Provides a soft, slightly-there surface |
| Electric Gradient | `linear-gradient(135deg, rgb(255, 131, 8), rgb(255, 80, 67) 50%, rgb(57, 43, 213))` | `--color-electric-gradient` | Decorative background for energetic sections, feature highlights. Brings a dynamic and modern feel to the monochrome scheme |

## Tokens — Typography

### Geist — The primary typeface for all text content, from headings to body text. Its clean, geometric forms, combined with specific letter-spacing and feature settings, contribute to the precise and modern feel. The slight negative letter-spacing for larger sizes enhances visual density without sacrificing legibility. · `--font-geist`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 14px, 17px, 20px, 28px, 33px, 40px, 56px
- **Line height:** 1.10, 1.15, 1.20, 1.30, 1.40
- **Letter spacing:** -0.0200em at 56px, -0.0100em at 40px and below
- **OpenType features:** `"ss01" on, "ss03" on, "ss04" on`
- **Role:** The primary typeface for all text content, from headings to body text. Its clean, geometric forms, combined with specific letter-spacing and feature settings, contribute to the precise and modern feel. The slight negative letter-spacing for larger sizes enhances visual density without sacrificing legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | -0.14px | `--text-caption` |
| body | 17px | 1.4 | -0.17px | `--text-body` |
| subheading | 20px | 1.3 | -0.2px | `--text-subheading` |
| heading | 28px | 1.2 | -0.28px | `--text-heading` |
| heading-lg | 33px | 1.15 | -0.33px | `--text-heading-lg` |
| display | 40px | 1.1 | -0.4px | `--text-display` |
| display-lg | 56px | 1.1 | -1.12px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| buttons | 200px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.06) 0px 2px 6px 0px` | `--shadow-sm` |

### Layout

- **Page max-width:** 1428px
- **Section gap:** 72px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Main call to action button.

Filled with Midnight Ink (#000000) with Canvas White (#ffffff) text. Features a highly rounded 200px border-radius, emphasizing its actionable nature. Padding is 0px vertical and 18px horizontal, with internal text dictating height.

### Ghost Action Button
**Role:** Secondary action button, or for navigation.

Outlined in Canvas White (#ffffff) with matching text. Also features a 200px border-radius for consistency. No vertical padding, 18px horizontal padding.

### White Card
**Role:** Content container for features or information.

Background is Canvas White (#ffffff), with a subtle shadow (rgba(0,0,0,0.06) 0px 2px 6px 0px). Corners are rounded at 6px. Inner padding of 24px on all sides.

### Dark Card
**Role:** Container for content in dark mode sections.

Solid Midnight Ink (#000000) background, no shadow. Corners are rounded with a 6px radius. Inner padding of 24px on all sides.

### Compact Tag Badge
**Role:** Informational tags or status indicators.

Background is Silver Mist (rgba(0,0,0,0.3) which is effectively #b3b3b3 with lower opacity in a light context) with Canvas White (#ffffff) text. Features 6px border-radius. Padding is 12px vertical and 18px horizontal.

## Do's and Don'ts

### Do
- Prioritize high-contrast pairing of Midnight Ink (#000000) and Canvas White (#ffffff) for primary content and actions.
- Use Geist at weight 400 for body text and 500 for headlines, ensuring the specified letter-spacing for optimal legibility.
- Apply a 200px border-radius to all buttons for a consistent, soft pill shape, and 6px to cards for subtle corner rounding.
- Use a base unit of 6px for all spacing decisions, translating to common elements gaps of 24px and section gaps of 72px.
- Introduce the Electric Gradient (linear-gradient(135deg, rgb(255, 131, 8), rgb(255, 80, 67) 50%, rgb(57, 43, 213))) sparingly as a background for impactful, energetic sections only.
- When using cards, default to Canvas White (#ffffff) with a soft shadow (rgba(0,0,0,0.06) 0px 2px 6px 0px) to indicate elevated content.

### Don't
- Avoid using saturated colors other than Electric Gradient; maintain a strict monochrome palette for all other UI elements.
- Do not use heavy, complex shadows; only apply the subtle rgba(0,0,0,0.06) 0px 2px 6px 0px shadow for elevated cards.
- Do not vary border radii significantly; stick to 200px for buttons/pills and 6px for cards/containers.
- Do not use generic system fonts; always utilize Geist with its specific weights and font feature settings for brand consistency.
- Avoid excessive use of the Electric Gradient; it should act as a highlight, not a dominant background for all sections.
- Do not create complex multi-layered backgrounds; surfaces should primarily be Canvas White or Midnight Ink for clarity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and default surface for most content sections. |
| 1 | Dark Card | `#000000` | Alternative background for specific content blocks that require higher visual contrast or a 'dark mode' feel within the light theme. |
| 2 | White Card with Shadow | `#ffffff` | Elevated card surfaces, differentiated by a subtle shadow to indicate hierarchy and interactivity. |
| 3 | Silver Mist | `#b3b3b3` | Used for compact badges and certain decorative elements, providing a muted background. |

## Imagery

Imagery primarily consists of product screenshots and abstract UI representations, often presented on dark backgrounds or within contained sections. These are treated with soft 6px rounded corners, matching the card aesthetic. There are no full-bleed photographs or lifestyle imagery. Icons appear to be outlined, monochrome (black or white, depending on background), with a medium stroke weight, serving an explanatory and decorative role at a medium density.

## Layout

The typical page layout is a max-width 1428px centered container, with full-width sections that internally constrain content. The hero section often features a centered headline over a white background. Sections establish rhythm through consistent 72px vertical spacing. Content is arranged in alternating patterns, such as text on one side and a product UI screenshot/illustration on the other. Feature sections utilize grids of cards, and prominent information is often presented in centered, stacked blocks for clarity.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #ffffff
border: #999999
accent: #ff8308
primary action: #000000 (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: White Card component with padding 24px, containing a heading 'Reduce cycles by 75%' in Geist weight 500, size 28px, Midnight Ink (#000000), letter-spacing -0.28px. Below it, add body text 'No more back-and-forth emails requesting corrections' in Geist weight 400, size 17px, Whisper Gray (#666666).
4. Show a status badge: Use the Compact Tag Badge component with text 'Pending Review' in Canvas White (#ffffff), with Silver Mist background (rgba(0,0,0,0.3)), 12px vertical padding, 18px horizontal padding, 6px border-radius.

## Similar Brands

- **Linear** — Monochrome UI with sharp typography, minimal surface textures, and deliberate use of spacing for clarity.
- **Stripe** — Clean, predominantly white canvas with strong dark typography, subtle card elevation, and a distinct lack of heavy ornamentation.
- **Vercel** — Emphasis on high-contrast text and dark elements on a light background, paired with a modern, technical typeface and minimalist component design.
- **Supabase** — Uses a dark-mode inspired aesthetic (black on white contrasts) even in a light theme, with clean, rounded interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-subtle-gray: #999999;
  --color-whisper-gray: #666666;
  --color-silver-mist: #b3b3b3;
  --color-electric-gradient: #ff8308;
  --gradient-electric-gradient: linear-gradient(135deg, rgb(255, 131, 8), rgb(255, 80, 67) 50%, rgb(57, 43, 213));

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.14px;
  --text-body: 17px;
  --leading-body: 1.4;
  --tracking-body: -0.17px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.28px;
  --text-heading-lg: 33px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.33px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -0.4px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.1;
  --tracking-display-lg: -1.12px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1428px;
  --section-gap: 72px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 200px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-buttons: 200px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 2px 6px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-dark-card: #000000;
  --surface-white-card-with-shadow: #ffffff;
  --surface-silver-mist: #b3b3b3;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-subtle-gray: #999999;
  --color-whisper-gray: #666666;
  --color-silver-mist: #b3b3b3;
  --color-electric-gradient: #ff8308;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.14px;
  --text-body: 17px;
  --leading-body: 1.4;
  --tracking-body: -0.17px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.28px;
  --text-heading-lg: 33px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.33px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -0.4px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.1;
  --tracking-display-lg: -1.12px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 200px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 2px 6px 0px;
}
```
