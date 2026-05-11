# Eddie — Style Reference
> Playful tech-futurism on a clean canvas.

**Theme:** light

Eddie's design system creates a playful yet authoritative feel, blending a clean, energetic achromatic base with vibrant purple and lime green accents. The visual language centers on bold, compact typography and soft, rounded elements. Lightly elevated cards with subtle purple-tinted shadows add depth, while high-contrast text ensures legibility. The overall effect is efficient and approachable, emphasizing a modern tech aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, darkest surface elements, filled buttons, structural borders that define active areas |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, card backgrounds, text on dark interactive elements |
| Pampas | `#f7f4f2` | `--color-pampas` | Secondary surface background, typically for cards and list items |
| French Gray | `#cdcbd0` | `--color-french-gray` | Decorative borders, inactive link underlines, subtle dividers |
| Scarpa Flow | `#4d4c51` | `--color-scarpa-flow` | Muted text, body copy on lighter backgrounds, ghost button borders |
| Lilac Haze | `#d8d1ff` | `--color-lilac-haze` | Accent backgrounds for badges and cards, soft decorative fills |
| Vibrant Lime | `#d2e534` | `--color-vibrant-lime` | Energetic marketing section backgrounds, accent elements, highlight badges |
| Dull Lavender | `#b7b2ff` | `--color-dull-lavender` | Violet state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Aqua Island | `#89cdf3` | `--color-aqua-island` | Informational badges, specific accent backgrounds; provides a cool contrast to the dominant purple |
| Whisper Glow | `#eeeafa` | `--color-whisper-glow` | Subtle shadow tint for elevated components, contributing to the soft, purple-hued depth |

## Tokens — Typography

### Founders Grotesk — All text elements, including headings, body copy, navigation, and interactive component text. Its compact, confident appearance defines the brand's voice. · `--font-founders-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px, 18px, 22px, 26px, 30px, 66px, 67px, 119px
- **Line height:** 0.70, 0.80, 1.00, 1.10, 1.30
- **Letter spacing:** normal
- **Role:** All text elements, including headings, body copy, navigation, and interactive component text. Its compact, confident appearance defines the brand's voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.3 | — | `--text-caption` |
| body-sm | 16px | 1.3 | — | `--text-body-sm` |
| body | 18px | 1.3 | — | `--text-body` |
| subheading | 22px | 1.1 | — | `--text-subheading` |
| heading-sm | 26px | 1.1 | — | `--text-heading-sm` |
| heading | 30px | 1.1 | — | `--text-heading` |
| heading-lg | 66px | 0.8 | — | `--text-heading-lg` |
| display | 119px | 0.7 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 40px |
| badges | 30px |
| buttons | 25px |
| interactiveElements | 15px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(198, 185, 237, 0.3) 5px 5px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 100px
- **Card padding:** 15px
- **Element gap:** 10px

## Components

### Filled Primary Button
**Role:** Main call to action, high importance.

Background: Ink (#000000). Text: Canvas (#ffffff). Border radius: 25px. Padding: 10px vertical, 20px horizontal. Shadow: rgba(198, 185, 237, 0.3) 5px 5px 20px 0px.

### Ghost Accent Button
**Role:** Secondary action that needs to stand out without being a primary CTA. Used in navigation or feature highlights.

Background: Canvas (#ffffff). Text: Ink (#000000). Border radius: 25px. Padding: 15px vertically and horizontally. Border: 1px solid Ink (#000000).

### Pampas Card with Soft Shadow
**Role:** Feature blocks or information containers requiring subtle elevation.

Background: Pampas (#f7f4f2). Border radius: 40px. Shadow: rgba(198, 185, 237, 0.3) 5px 5px 20px 0px. No internal padding specified from analysis.

### Lilac Haze Feature Card
**Role:** Prominent information card, often acting as a section header or key highlight.

Background: Lilac Haze (#d8d1ff). Border radius: 60px. Padding: 30px vertically and horizontally. No explicit shadow.

### Subtle Badge
**Role:** Categorization or short status labels.

Background: transparent. Text: Ink (#000000). No border radius set (0px). Minimal bottom padding of 0.8px.

### Accent Tag Badge
**Role:** Highlighting keywords, categories, or functional states.

Background: Dull Lavender (#b7b2ff). Text: Ink (#000000). Border Radius: 30px. Padding: 5px vertical, 10px horizontal.

### Info Tag Badge
**Role:** Indicating informational status or categories.

Background: Aqua Island (#89cdf3). Text: Ink (#000000). Border Radius: 30px. Padding: 5px vertical, 10px horizontal.

## Do's and Don'ts

### Do
- Prioritize Founders Grotesk for all text at varying weights and sizes, ensuring consistent brand voice.
- Utilize Ink (#000000) for primary text and critical UI elements to maintain high contrast and legibility.
- Use Canvas (#ffffff) or Pampas (#f7f4f2) as dominant background colors for most sections.
- Apply a 25px border radius to all interactive buttons for a soft, approachable feel.
- Accent key sections or interactive elements with Lilac Haze (#d8d1ff), Vibrant Lime (#d2e534), or Dull Lavender (#b7b2ff).
- Employ the rgba(198, 185, 237, 0.3) 5px 5px 20px 0px shadow for cards and buttons that require subtle elevation.
- Maintain a compact density with 10px element gaps for most internal component spacing.

### Don't
- Avoid using highly saturated, primary colors for large background areas unless it is specifically one of the defined accent colors.
- Do not deviate from the Founders Grotesk typeface; introducing other fonts will compromise the brand's typographic identity.
- Never use sharp corners; adhere to the specified border radii for all elements, particularly 25px for buttons and 40px for cards.
- Refrain from heavy, dark shadows; the subtle, purple-tinted shadow is a core part of its visual language.
- Do not introduce complex gradients for UI elements; the system tends towards solid fills or very subtle accent gradients.
- Avoid excessive spacing that creates 'airy' layouts; the density is compact and efficient.
- Do not use multiple accent colors simultaneously in proximity unless they are part of a deliberately designed badge or illustration.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Primary page background. |
| 1 | Pampas | `#f7f4f2` | Secondary background for card components and specific content blocks. |
| 2 | Lilac Haze | `#d8d1ff` | Elevated accent cards or key information sections, often with larger radius. |
| 3 | Vibrant Lime | `#d2e534` | High-impact feature sections, often full-bleed, for visual demarcation and energy. |

## Elevation

- **Card / Button:** `rgba(198, 185, 237, 0.3) 5px 5px 20px 0px`

## Imagery

The imagery leans towards product-focused illustrations and subtle abstract graphics. Illustrations are dimensional and often incorporate the brand's purple and blue-green accent colors, depicting technology or smart devices in a clean, friendly style. These visuals are typically contained within rounded cards or sections, not full-bleed. Icons are primarily solid, in Ink (#000000) or accent colors, with a medium stroke weight where outlines are present, serving functional and decorative roles. The overall density of visuals is moderate, blending with text-heavy sections seamlessly.

## Layout

The page structure is primarily contained with a maximum width, although the hero section appears full-bleed or extends wider. The hero features a centered headline and interactive elements. Sections often alternate between full-width content and structured 2-column or card grid layouts. Vertical spacing between sections is generous, creating distinct content blocks, but internal component density is compact. The navigation is a sticky top bar with a hidden mega-menu triggered by a hamburger icon on smaller screens or a more explicit 'Ça m'intéresse' button. Content is arranged with a clear hierarchy; alternating text-left/image-right is not a dominant pattern, rather emphasis is on distinct content blocks.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #4d4c51
accent: #d8d1ff
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary CTA Button: Background Ink (#000000), text Canvas (#ffffff), 25px border radius, 10px vertical and 20px horizontal padding, with rgba(198, 185, 237, 0.3) 5px 5px 20px 0px shadow.
2. Design a Feature Card: Lilac Haze (#d8d1ff) background, 60px border radius, 30px vertical and horizontal padding, with Founders Grotesk 600 weight text at 26px and Ink (#000000) color.
3. Implement a Ghost Button: Canvas (#ffffff) background, text Ink (#000000), 25px border radius, 15px vertical and horizontal padding, with a 1px solid Ink (#000000) border.
4. Create an Accent Badge: Dull Lavender (#b7b2ff) background, text Ink (#000000), 30px border radius, 5px vertical and 10px horizontal padding, using Founders Grotesk 400 weight at 14px.
5. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Figma** — Clean, compact typography on light surfaces with specific, vibrant accent colors for interactivity and brand distinction.
- **Linear** — Focus on high information density, precise typography, and a limited, functional color palette with a strong accent.
- **Webflow** — Balanced use of crisp typography, soft, rounded UI elements, and strategic application of accent colors to guide attention.
- **Coda** — Applies a similar approach of strong contrasts in text, clean backgrounds, and vivid accent hues for interactive elements and brand personality.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-pampas: #f7f4f2;
  --color-french-gray: #cdcbd0;
  --color-scarpa-flow: #4d4c51;
  --color-lilac-haze: #d8d1ff;
  --color-vibrant-lime: #d2e534;
  --color-dull-lavender: #b7b2ff;
  --color-aqua-island: #89cdf3;
  --color-whisper-glow: #eeeafa;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.3;
  --text-body-sm: 16px;
  --leading-body-sm: 1.3;
  --text-body: 18px;
  --leading-body: 1.3;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.1;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --text-heading-lg: 66px;
  --leading-heading-lg: 0.8;
  --text-display: 119px;
  --leading-display: 0.7;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 15px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-cards: 40px;
  --radius-badges: 30px;
  --radius-buttons: 25px;
  --radius-interactiveelements: 15px;

  /* Shadows */
  --shadow-lg: rgba(198, 185, 237, 0.3) 5px 5px 20px 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-pampas: #f7f4f2;
  --surface-lilac-haze: #d8d1ff;
  --surface-vibrant-lime: #d2e534;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-pampas: #f7f4f2;
  --color-french-gray: #cdcbd0;
  --color-scarpa-flow: #4d4c51;
  --color-lilac-haze: #d8d1ff;
  --color-vibrant-lime: #d2e534;
  --color-dull-lavender: #b7b2ff;
  --color-aqua-island: #89cdf3;
  --color-whisper-glow: #eeeafa;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.3;
  --text-body-sm: 16px;
  --leading-body-sm: 1.3;
  --text-body: 18px;
  --leading-body: 1.3;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.1;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --text-heading-lg: 66px;
  --leading-heading-lg: 0.8;
  --text-display: 119px;
  --leading-display: 0.7;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 60px;

  /* Shadows */
  --shadow-lg: rgba(198, 185, 237, 0.3) 5px 5px 20px 0px;
}
```
