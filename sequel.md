# Sequel — Style Reference
> Black canvas, sharp typography

**Theme:** dark

This design system evokes a sense of understated luxury and serious intent, reflecting a 'dark mode meets gallery space' aesthetic. A dramatic pure black background (#000000) provides a stark canvas for crisp white typography (#ffffff) and subtle, almost invisible components. The system primarily relies on meticulous typography with a custom serif for headlines and a custom sans-serif for body text, creating a strong sense of intellectual weight without visual overwhelm. Rounded lozenges (9999px radius) offer the only soft edges, contrasting sharply with the otherwise linear, rigid structure, suggesting pockets of approachable interaction within a rigorous framework.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page backgrounds, primary dark surfaces, text on light elements. |
| Cloud Whisper | `#ffffff` | `--color-cloud-whisper` | Primary text, critical UI elements, borders for ghost buttons — creating stark contrast against dark backgrounds. |
| Slate Dust | `#f5f5f0` | `--color-slate-dust` | Primary background for solid buttons, providing a subtle off-white alternative to pure white for interactive elements. |
| Steel Gray | `#202020` | `--color-steel-gray` | Secondary background for containers, slightly differentiated from the deepest black. |
| Mist Gray | `#c0c0c0` | `--color-mist-gray` | Subtle text, less prominent borders, and icons. |
| Charcoal Tone | `#333333` | `--color-charcoal-tone` | Badge backgrounds when slightly darker contrast is needed, secondary borders. |
| Ash Accent | `#999999` | `--color-ash-accent` | Tertiary text, descriptive labels, less emphasized information. |
| Light Ash | `#cccccc` | `--color-light-ash` | Fine print, less important body copy. Similar to Ash Accent but slightly lighter. |
| Cadet Gray | `#b3b3b3` | `--color-cadet-gray` | Placeholder text or disabled states, providing a further step down in visual hierarchy. |
| Badge Overlay | `#333333` | `--color-badge-overlay` | Background for transparent badges, providing a muted dark tint. |

## Tokens — Typography

### VisueltPro — Primary sans-serif for body text, navigation, and most UI elements. Its precise tracking and varied weights at numerous sizes provide significant typographic flexibility, maintaining clarity even at small scales. · `--font-visueltpro`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 30px, 32px, 54px, 58px, 115px, 128px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** -0.0500em, -0.0300em, -0.0250em, -0.0200em, 0.0300em, 0.0500em, 0.0700em, 0.0800em
- **Role:** Primary sans-serif for body text, navigation, and most UI elements. Its precise tracking and varied weights at numerous sizes provide significant typographic flexibility, maintaining clarity even at small scales.

### Bradford — Exclusive for large headlines, this custom serif font and its distinct light weight (500) sets a tone of intellectual authority. The negative letter-spacing at display sizes creates a commanding, tightly-knit appearance, making headlines feel sculpted. · `--font-bradford`
- **Substitute:** serif
- **Weights:** 500
- **Sizes:** 32px, 58px, 128px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.0500em, -0.0250em
- **Role:** Exclusive for large headlines, this custom serif font and its distinct light weight (500) sets a tone of intellectual authority. The negative letter-spacing at display sizes creates a commanding, tightly-knit appearance, making headlines feel sculpted.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.3px | `--text-caption` |
| heading | 18px | 1.2 | — | `--text-heading` |
| heading-lg | 20px | 1.2 | — | `--text-heading-lg` |
| display-sm | 22px | 1.2 | — | `--text-display-sm` |
| display | 30px | 1 | — | `--text-display` |
| display-lg | 32px | 1 | -0.8px | `--text-display-lg` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| badges | 9999px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.35) 0px 10px 30px 0px, rgba(255, 255, 255...` | `--shadow-xl` |
| lg | `rgba(0, 0, 0, 0.15) 0px 4px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 47-76px
- **Card padding:** 0px
- **Element gap:** 3-28px

## Components

### Primary Lozenge Button
**Role:** Call to Action

Rounded pill shape, #f5f5f0 background with #000000 text. Uses 9999px border-radius, 24px horizontal padding. Typography: VisueltPro, typically weight 400 for clarity.

### Ghost Lozenge Button
**Role:** Secondary Action

Rounded pill shape. Transparent background, #ffffff text with a #ffffff border. Uses 9999px border-radius, 20px horizontal padding. Typography: VisueltPro, typically weight 400.

### Circular Play Button
**Role:** Media Playback

Perfectly circular with transparent background, #ffffff text/icon, and #ffffff border. Used for video controls. Radius implied by 0px padding and circular shape.

### Standard Card
**Role:** Content container

Transparent background, 0px border radius, no box shadow. Content relies on visual hierarchy rather than distinct container styling.

### Featured Card
**Role:** Prominent content container

Transparent background, 10px border radius, no box shadow. Used for visually separating key content blocks, subtle rounded corners add distinction.

### Lozenge Badge
**Role:** Category/Tag

Rounded pill shape, rgba(200, 200, 200, 0.1) background with #ffffff text. Uses 9999px border-radius, 16px horizontal and 8px vertical padding. Typography: VisueltPro, weight 400, for clear labeling.

### Subtle Pill Badge
**Role:** Secondary Category/Tag

Rounded pill shape, transparent background with #ffffff text. Uses 9999px border-radius. Primarily used for inline or minimalist tagging, relying on text color for emphasis.

## Do's and Don'ts

### Do
- Prioritize #000000 for backgrounds and #ffffff for primary text to maintain high contrast and dramatic impact.
- Use Bradford font exclusively for large headings (32px and above) with its distinct weight 500 and negative letter spacing (-0.0500em or -0.0250em).
- Apply 9999px border-radius to all interactive elements like buttons and badges for distinctive pill shapes.
- Utilize rgba(200, 200, 200, 0.1) for subtle, transparent badge backgrounds, ensuring text remains #ffffff.
- Maintain a clear visual hierarchy using VisueltPro's varied weights and sizes for body copy, navigation, and secondary UI elements, without relying on color for differentiation.
- Employ the negative letter-spacing values from the typography specification for precise text rendering at various sizes.
- Use 10px border-radius only for specific featured cards to provide a subtle visual differentiator against the predominant 0px radius.

### Don't
- Avoid using highly saturated or chromatic colors; stick to the achromatic palette with #ffffff, #000000, and the various grays.
- Do not introduce sharp corners on buttons or badges; the 9999px radius is a signature visual element.
- Refrain from using Bradford font for body text or small UI elements; its use is reserved for large, impactful headlines.
- Do not add additional box-shadows beyond rgba(0, 0, 0, 0.35) 0px 10px 30px 0px for elevated elements and rgba(0, 0, 0, 0.15) 0px 4px 20px 0px for interactive button states.
- Avoid using multiple border styles or weights; maintain simple, thin borders for ghost elements or an absence of borders.
- Do not use generic system fonts in place of VisueltPro or Bradford; their unique characteristics are integral to the brand.
- Avoid excessive spacing that diminishes the dense, deliberate feel; element gaps should adhere to the provided '3-28px' range.

## Elevation

- **Interactive Button:** `rgba(0, 0, 0, 0.15) 0px 4px 20px 0px`
- **Elevated Badge/Element:** `rgba(0, 0, 0, 0.35) 0px 10px 30px 0px, rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset`

## Imagery

The visual language is characterized by sophisticated, high-key photography of individuals, often seen in reflective or contemplative states, suggesting success and thought leadership. Images are full-bleed within the card containers, cropped dynamically, and occasionally feature subtle brand badges overlayed at specific corners. There is an absence of product screenshots or abstract graphics, focusing entirely on human subjects as the core visual narrative. The overall impression is one of aspirational portraiture combined with subtle documentary style, reinforcing a focus on people.

## Layout

The page primarily uses a full-bleed layout, where content sections stretch across the entire viewport width, particularly for hero areas. Inner content is often held within a maximum width but the containers do not explicitly define a pageMaxWidth. The hero section features centered, large typography against a dark background. Content sections follow a vertical rhythm, alternating between prominent headlines and multi-column layouts, often with text on one side and a large image card on the other. Navigation is a minimalist top bar with a primary action button, fading into the dark background. The layout feels spacious yet structured, emphasizing key statements and imagery.

## Agent Prompt Guide

Quick Color Reference:
- Text: #ffffff
- Background: #000000
- CTA Button Background: #f5f5f0
- CTA Button Text: #000000
- Ghost Button Border: #ffffff
- Badge Background: rgba(200, 200, 200, 0.1)

Example Component Prompts:
1. Create a Primary Lozenge Button: background-color #f5f5f0, color #000000, border-radius 9999px, padding 0px 24px, font VisueltPro weight 400. Text: 'Build the future'.
2. Create a Ghost Lozenge Button: background-color transparent, color #ffffff, border 1px solid #ffffff, border-radius 9999px, padding 0px 20px, font VisueltPro weight 400. Text: 'Watch the film'.
3. Create a Featured Card: background-color transparent, border-radius 10px, box-shadow none, padding 0px 0px. Within it, use a full-bleed image and a Lozenge Badge: background-color rgba(200, 200, 200, 0.1), color #ffffff, border-radius 9999px, padding 8px 16px, font VisueltPro weight 400. Badge text: 'Founders'.
4. Create a large headline using Bradford font: color #ffffff, font-family Bradford, font-weight 500, font-size 128px, line-height 1.0, letter-spacing -0.0500em. Text: 'Your Legacy, Made'.

## Similar Brands

- **Alinea** — Shares a dark, minimalist aesthetic with clean typography and a focus on financial services.
- **Relume Library** — Uses subtle grays and whites on a dark canvas, with emphasis on distinctive typography and structured layouts.
- **Linear** — Employs a precise, dark-mode UI with sharp typography and a restrained use of design elements for functional elegance.
- **Stripe** — Known for clean, often dark interface designs, subtle interactive elements, and sophisticated typography choices.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-cloud-whisper: #ffffff;
  --color-slate-dust: #f5f5f0;
  --color-steel-gray: #202020;
  --color-mist-gray: #c0c0c0;
  --color-charcoal-tone: #333333;
  --color-ash-accent: #999999;
  --color-light-ash: #cccccc;
  --color-cadet-gray: #b3b3b3;
  --color-badge-overlay: #333333;

  /* Typography — Font Families */
  --font-visueltpro: 'VisueltPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bradford: 'Bradford', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-heading: 18px;
  --leading-heading: 1.2;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 22px;
  --leading-display-sm: 1.2;
  --text-display: 30px;
  --leading-display: 1;
  --text-display-lg: 32px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.8px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 47-76px;
  --card-padding: 0px;
  --element-gap: 3-28px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-badges: 9999px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.35) 0px 10px 30px 0px, rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px 4px 20px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-cloud-whisper: #ffffff;
  --color-slate-dust: #f5f5f0;
  --color-steel-gray: #202020;
  --color-mist-gray: #c0c0c0;
  --color-charcoal-tone: #333333;
  --color-ash-accent: #999999;
  --color-light-ash: #cccccc;
  --color-cadet-gray: #b3b3b3;
  --color-badge-overlay: #333333;

  /* Typography */
  --font-visueltpro: 'VisueltPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bradford: 'Bradford', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-heading: 18px;
  --leading-heading: 1.2;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 22px;
  --leading-display-sm: 1.2;
  --text-display: 30px;
  --leading-display: 1;
  --text-display-lg: 32px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.35) 0px 10px 30px 0px, rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px 4px 20px 0px;
}
```
