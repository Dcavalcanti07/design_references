# Ventriloc — Style Reference
> Analytical architecture on a clean canvas

**Theme:** light

Ventriloc employs an analytical architecture aesthetic: a pristine gray-on-white canvas for data visualization. The design relies on sharp contrasts between dark text and light backgrounds, with a singular warm accent color, 'Sunset Orange', used to highlight key data points and interactive elements. Components are lightweight, often outlined or ghost-like, conveying a sense of precision and responsiveness without heavy ornamentation. The overall impression is one of clarity and focused information delivery.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#202020` | `--color-midnight-graphite` | Primary text, darkest surface elements, active button text, strong borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Pure backgrounds, key card surfaces, navigation background |
| Slate Mist | `#efefef` | `--color-slate-mist` | Secondary card backgrounds, subtle section breaks |
| Cloud Whisper | `#f5f5f5` | `--color-cloud-whisper` | Muted backgrounds, navigation item backgrounds, light borders |
| Warm Ivory | `#ebe6dd` | `--color-warm-ivory` | Subtle background shifts for content separation |
| Dark Shale | `#4d4d4d` | `--color-dark-shale` | Secondary text, muted links, subtle dividers |
| Silver Ash | `#828282` | `--color-silver-ash` | Tertiary text, inactive navigation items, placeholder text |
| Light Pearl | `#e8e8e8` | `--color-light-pearl` | Thin dividers and subtle background accents |
| Sunset Orange | `#ff682c` | `--color-sunset-orange` | Decorative accents, data visualization elements, highlight color for UI components |
| Data Gold | `#816729` | `--color-data-gold` | Data visualization elements, secondary icon color, subtle branding accents |

## Tokens — Typography

### Inter — Body text, navigation items, button labels, small data points, most UI elements. Inter provides a highly legible, modern feel for dense information. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px
- **Line height:** 1.15, 1.20, 1.25, 1.33, 1.38, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Body text, navigation items, button labels, small data points, most UI elements. Inter provides a highly legible, modern feel for dense information.

### PolySans — Headlines, featured text, and select emphasis. Its slightly condensed and tightly spaced nature gives a distinctive, sharp, and authoritative voice. · `--font-polysans`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 12px, 13px, 16px, 32px, 40px, 66px
- **Line height:** 0.91, 1.00, 1.13, 1.19, 1.20, 1.38
- **Letter spacing:** -0.0200em
- **Role:** Headlines, featured text, and select emphasis. Its slightly condensed and tightly spaced nature gives a distinctive, sharp, and authoritative voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 15px | 1.33 | — | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 32px | 1.19 | -0.64px | `--text-heading-sm` |
| heading | 40px | 1.13 | -0.8px | `--text-heading` |
| display | 66px | 0.91 | -1.32px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| large | 20px |
| inputs | 20px |
| avatars | 200px |
| buttons | 20px |
| default | 8px |

### Layout

- **Section gap:** 80px
- **Card padding:** 40px
- **Element gap:** 20px

## Components

### Standard Nav Link
**Role:** Navigation item within headers and footers.

Text in Midnight Graphite (#202020), no background, 2px bottom border in Midnight Graphite on hover/active. Font is Inter 400 at 16px, line-height 1.25, normal letter-spacing, 0px padding. Vertical spacing of 8px around items.

### Muted Nav Link
**Role:** Navigation item, typically for less prominent sections or inactive states.

Text in Silver Ash (#828282), no background, no border. Font is Inter 400 at 16px, line-height 1.25, normal letter-spacing.

### Primary Ghost Button
**Role:** Call to action, typically in sections with high visual contrast.

Transparent background, Midnight Graphite (#202020) text, 2px bottom border in Midnight Graphite. Font is Inter 400 at 16px, line-height 1.25, normal letter-spacing. Padding is 0px top/bottom, 18px left/right. 20px border radius.

### Secondary Ghost Button
**Role:** Discreet calls to action or secondary actions.

Transparent background, Silver Ash (#828282) text, no border. Font is Inter 400 at 16px, line-height 1.25, normal letter-spacing. Padding 0px top/bottom, 0px left/right. 20px border radius.

### Highlight Card
**Role:** Information display, often for data visualizations or key summaries.

Background #efefef, 6px top-left border radius, 0px for others. Padding 70px top, 0px other sides. No shadow.

### Rounded Info Card
**Role:** General content container with softer edges.

Background #efefef, 20px border radius for all corners. No shadow.

### Metric Badge
**Role:** Small data labels or status indicators.

Transparent background, Midnight Graphite (#202020) text. No border radius. Inter 400 at 16px, normal letter spacing. No explicit padding.

## Do's and Don'ts

### Do
- Prioritize Midnight Graphite (#202020) for all primary text and strong interactive elements to maintain high legibility.
- Utilize Canvas White (#ffffff) and Slate Mist (#efefef) as primary background and card surface colors, respectively, to establish clear visual hierarchy.
- Employ PolySans exclusively for headlines and featured content at larger sizes (32px, 40px, 66px) with a consistent letter spacing of -0.0200em to define distinct brand voice.
- Use Inter for all body text, smaller UI elements, and navigation, ensuring high readability across functional components.
- Apply Sunset Orange (#ff682c) sparingly for data visualization highlights, icon accents, and as a decorative accent for interactive states, never as a background for primary buttons.
- Maintain a default border-radius of 8px for most cards, and a more pronounced 20px for buttons and prominent interactive elements, creating a soft, approachable feel.
- Structure layouts with a comfortable 20px element gap for internal component spacing and a more generous 80px section gap for clear content block separation.

### Don't
- Avoid using highly saturated colors for large backgrounds or extensive text; the palette is predominantly neutral with targeted accents.
- Do not deviate from the established PolySans for headlines or Inter for body text; typographic variations should be limited to weight and size within these families.
- Refrain from adding arbitrary shadows or complex gradients; the system prioritizes flat surfaces and subtle elevation.
- Do not use accent colors like Sunset Orange (#ff682c) or Data Gold (#816729) for general body text or navigational elements where primary text color is required.
- Avoid tight spacing: ensure generous padding (e.g., 40px for cards) and element gaps (20px) to maintain a comfortable reading experience.
- Do not introduce additional border radii other than 3px, 8px, 12px, 20px, and 200px (for avatars/pills); consistency in corner rounding is key.
- Avoid using multiple font weights or styles within a single sentence or small interactive component, beyond what is defined in the typography section, to prevent visual clutter.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Cloud Whisper | `#f5f5f5` | Lightest card backgrounds, very subtle background shifts |
| 2 | Slate Mist | `#efefef` | Primary card backgrounds, distinct content containers |
| 3 | Warm Ivory | `#ebe6dd` | Alternative subtle background for visual separation |

## Imagery

The visual language focuses on a mix of product screenshots and abstract, data-driven illustrations. Product screenshots are typically clean, depicting dashboard interfaces with charts and metrics against a light background, sometimes slightly cropped or angled. Illustrations are organic, abstract data visualizations using the accent colors of Sunset Orange and Data Gold. Icons are outlined, simple, and functional, with a consistent stroke weight, occasionally filled with accent colors for emphasis. Imagery serves an explanatory and informative role, showcasing the product's capabilities and providing visual context to the data-driven narrative.

## Layout

The page primarily employs a contained layout with a comfortable maximum width, centered on a Canvas White background. The hero section is a split two-column layout, featuring a large PolySans headline and body text on the left, juxtaposed with product screenshots displaying analytics on the right. Sections alternate between full-width content and max-width containers, often with a consistent 80px vertical section gap. Content arrangement frequently uses two-column layouts, either text alongside imagery or data cards. There's a minimal, sticky top navigation bar with text links and a 'Contact us' button. The overall density is comfortable, ensuring sufficient breathing room between elements.

## Agent Prompt Guide

Quick Color Reference:
text: #202020
background: #ffffff
border: #202020
accent: #ff682c
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a feature card: Slate Mist (#efefef) background, 8px border-radius (top-left 6px others 0px), 70px top padding. Headline 'Finance Dashboard' using PolySans 32px, #202020, letter-spacing -0.64px. Body text 'Track revenues and profits' using Inter 14px, #4d4d4d.

## Similar Brands

- **Stripe** — Clean, predominantly white/light gray interface with strong typography and a single vibrant accent color for interaction and data.
- **Linear** — Minimalist aesthetic featuring crisp typography, clear information hierarchy, and a restrained color palette focused on functionality.
- **Figma** — High-contrast text on light surfaces, with functional, outlined components and a focus on displaying dense information cleanly.
- **Amplitude** — Data visualization heavy interface, using light backgrounds, dark text, and subtle accent colors to highlight metrics and graphs.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #202020;
  --color-canvas-white: #ffffff;
  --color-slate-mist: #efefef;
  --color-cloud-whisper: #f5f5f5;
  --color-warm-ivory: #ebe6dd;
  --color-dark-shale: #4d4d4d;
  --color-silver-ash: #828282;
  --color-light-pearl: #e8e8e8;
  --color-sunset-orange: #ff682c;
  --color-data-gold: #816729;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 15px;
  --leading-body: 1.33;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.19;
  --tracking-heading-sm: -0.64px;
  --text-heading: 40px;
  --leading-heading: 1.13;
  --tracking-heading: -0.8px;
  --text-display: 66px;
  --leading-display: 0.91;
  --tracking-display: -1.32px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 40px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 200px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-large: 20px;
  --radius-inputs: 20px;
  --radius-avatars: 200px;
  --radius-buttons: 20px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-whisper: #f5f5f5;
  --surface-slate-mist: #efefef;
  --surface-warm-ivory: #ebe6dd;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #202020;
  --color-canvas-white: #ffffff;
  --color-slate-mist: #efefef;
  --color-cloud-whisper: #f5f5f5;
  --color-warm-ivory: #ebe6dd;
  --color-dark-shale: #4d4d4d;
  --color-silver-ash: #828282;
  --color-light-pearl: #e8e8e8;
  --color-sunset-orange: #ff682c;
  --color-data-gold: #816729;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 15px;
  --leading-body: 1.33;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.19;
  --tracking-heading-sm: -0.64px;
  --text-heading: 40px;
  --leading-heading: 1.13;
  --tracking-heading: -0.8px;
  --text-display: 66px;
  --leading-display: 0.91;
  --tracking-display: -1.32px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 200px;
}
```
