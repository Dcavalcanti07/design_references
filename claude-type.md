# Claude Type — Style Reference
> Gallery of Arched Voids

**Theme:** light

Claude Type presents a stately, minimalist aesthetic focused on displaying luxury typefaces. Its visual language relies on expansive neutral backgrounds, sparse content arrangements, and high-contrast typography. Typography is the primary visual element, with generous use of letter-spacing and custom font features. Images serve as artistic showcases, contained within large, softly rounded or arched frames, giving a gallery-like feel to the content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcfbf7` | `--color-canvas-white` | Page background, large card surfaces, hero backgrounds. Provides a soft, warm white base for content |
| Paper Gray | `#e7e4e0` | `--color-paper-gray` | Slightly desaturated background for select sections and containers, suggesting a subtle paper texture |
| Midnight Ink | `#0d0d0f` | `--color-midnight-ink` | Primary text color for headlines and body. Its near-black depth offers strong contrast |
| Deep Charcoal | `#2b1b1b` | `--color-deep-charcoal` | Secondary text, input text, and subtle borders. Provides a softer dark tone than Midnight Ink for less prominent elements |
| Ghost Fill | `#100401` | `--color-ghost-fill` | Very faint background tint for certain cards, providing a barely-there surface distinction |
| Pure White | `#ffffff` | `--color-pure-white` | Inverse text color for dark backgrounds and subtle button borders |
| Success Green | `#99ff66` | `--color-success-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### MagicUIPro — All text elements, including headings, body, navigation, and buttons. Its single weight and varied sizes emphasize the typographic craft and provide both delicate and impactful expressions through size and meticulous letter-spacing. · `--font-magicuipro`
- **Substitute:** serif font with good ligature support, such as Optima or ITC Garamond
- **Weights:** 400
- **Sizes:** 11px, 12px, 14px, 15px, 18px
- **Line height:** 1.00, 1.40, 1.60, 1.67, 2.00
- **Letter spacing:** Ranges from -0.0230em (tight) to 0.0200em (expanded), providing fine control over typographic texture.
- **OpenType features:** `'dlig'`
- **Role:** All text elements, including headings, body, navigation, and buttons. Its single weight and varied sizes emphasize the typographic craft and provide both delicate and impactful expressions through size and meticulous letter-spacing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.6 | — | `--text-caption` |
| body-sm | 12px | 1.6 | — | `--text-body-sm` |
| body | 14px | 1.6 | — | `--text-body` |
| body-lg | 15px | 1.6 | — | `--text-body-lg` |
| heading-sm | 18px | 1.6 | — | `--text-heading-sm` |

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
| 32 | 32px | `--spacing-32` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 180 | 180px | `--spacing-180` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| buttons | 100px |
| imagery | 900px |
| elements | 10px |

### Layout

- **Section gap:** 180px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Navigation Link
**Role:** Top navigation items and footer links.

Text uses MagicUIPro, Midnight Ink, 15px size, 1.4 lineHeight, 0.001em letterSpacing. Underlined on hover. No padding or distinct background.

### Ghost Button - Light Outline
**Role:** Secondary action buttons, typically against light backgrounds.

Transparent background, Deep Charcoal text. Border is 1px solid Deep Charcoal. 100px border-radius (pill-shaped). Padding 0px vertical, 16px horizontal. Font sizing is context-dependent, but often 15px with 0.001em letter-spacing.

### Ghost Button - Dark Outline (variant)
**Role:** Secondary action buttons against dark backgrounds.

Transparent background, Pure White text. Border is 1px solid Pure White. 100px border-radius (pill-shaped). Padding 0px vertical, 14px horizontal.

### Filled Button - Dark Background
**Role:** Primary action button within dark sections or against images.

Deep Charcoal background, Pure White text. 0px border-radius (square). Padding 0px vertical, 14px horizontal. Often appears in conjunction with image cards.

### Filled Button - Light Background (variant)
**Role:** Primary action button within light sections.

Pure White background, Deep Charcoal text. 100px border-radius (pill-shaped). Padding 0px vertical, 14px horizontal.

### Image Card - Arched Top
**Role:** Display large, artistic images with a distinct visual shape.

Radius of 900px 900px 0px 0px, creating an arched top. Background color of Ghost Fill. No padding, images are full-bleed within the card boundary. Often accompanied by text below the image.

### Image Card - Arched All Sides
**Role:** Primary decorative image container for hero sections or prominent displays.

Radius of 900px on all corners, creating an overall arched or 'soft' rectangular shape. Background color of Ghost Fill initially. No padding.

### Information Card - Rounded
**Role:** Structured content blocks, e.g., for showcasing typefaces with accompanying descriptive text.

Background of Canvas White, 32px border-radius. Padding 16px vertical, 0px horizontal. No shadow.

### Status Chip
**Role:** Small informational tags, often for highlighting product counts or states.

Background color #99ff66. Text color Midnight Ink. Padding 0px vertical, 16px horizontal. 100px border-radius.

### Input Field
**Role:** Text input areas.

Transparent background, border is 1px solid Deep Charcoal. No border-radius. Font style determined by parent context, typically MagicUIPro, 15px, Deep Charcoal.

## Do's and Don'ts

### Do
- Prioritize typography as the primary visual element, using MagicUIPro with careful attention to size and letter-spacing.
- Use Canvas White (#fcfbf7) or Paper Gray (#e7e4e0) for all page and section backgrounds to maintain a clean, airy feel.
- Container imagery within large rounded or arched frames (900px radius) to create a gallery aesthetic.
- Apply 100px border-radius to all interactive elements like buttons and chips to achieve a soft, 'pill-shaped' appearance.
- Maintain generous spacing between sections and elements, with a base element gap of 16px and section gap of 180px, to emphasize content scarcity and luxury.
- Use Midnight Ink (#0d0d0f) for all primary text and Deep Charcoal (#2b1b1b) for secondary text or subtle borders.
- Employ the 'dlig' font feature for all MagicUIPro text to render discretionary ligatures, enhancing typographic elegance.

### Don't
- Avoid strong, vivid chromatic colors. Keep color palette subdued, relying on neutrals and a single subtle accent.
- Do not use sharp 0px corners on any card or actionable UI element; 32px is the minimum for cards, 100px for buttons.
- Do not overcrowd sections with dense content; maintain a comfortable density with ample breathing room.
- Avoid heavy shadows or elevation effects; the design relies on subtle background color shifts for surface distinction.
- Do not use generic system fonts; only MagicUIPro (or its identified substitute) should be used for branding consistency.
- Minimize the use of multiple font weights; the system primarily uses a single weight with size and spacing for visual hierarchy.
- Do not use decorative borders on elements other than subtle outlines for ghost buttons or inputs.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#fcfbf7` | Primary overall background for the majority of page content, providing a warm, clean base. |
| 2 | Paper Gray | `#e7e4e0` | Used for background of specific sections or subtle containers, offering a slight visual shift from the main canvas. |
| 3 | Ghost Fill | `#100401` | A very faint background tint on prominent image cards, providing a barely perceptible surface without strong visual weight. |

## Elevation

This design system intentionally avoids overt shadows. The distinction between surface levels is achieved through subtle background color changes (Canvas White, Paper Gray, Ghost Fill) and the strong visual weight of imagery contained within distinct shapes. There is no traditional 'elevation' through shadows, maintaining a flat, sophisticated aesthetic.

## Agent Prompt Guide

Quick Color Reference:
text: #0d0d0f
background: #fcfbf7
border: #2b1b1b
accent: #99ff66
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary navigation bar: Background Canvas White, with Navigation Links using text color Midnight Ink, MagicUIPro 15px, 0.001em letter-spacing. Include a Ghost Button - Light Outline for 'Cart' at the end.
2. Design an Image Card - Arched All Sides containing an image. Use Ghost Fill as the background. Place a Ghost Button - Dark Outline at the bottom of the card for an 'Explore' action.
3. Implement an Information Card - Rounded: Background Canvas White, 32px border-radius, 16px vertical padding. Include a bold heading in Midnight Ink and body text in Deep Charcoal, both using MagicUIPro with appropriate sizes from the type scale.

## Similar Brands

- **Kerning Cultures** — Shared focus on sophisticated typography, minimalist aesthetic, and rich content presentation with ample negative space.
- **Future Fonts** — Type foundry showcasing new fonts with a clean, editorial layout and strong photographic elements.
- **Hermès** — Luxury brand aesthetic characterized by understated elegance, large impactful imagery within clean layouts, and a very selective color palette.
- **&Walsh agency** — Design agency website utilizing large, eye-catching imagery and bold, yet refined, typography against largely neutral backdrops.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcfbf7;
  --color-paper-gray: #e7e4e0;
  --color-midnight-ink: #0d0d0f;
  --color-deep-charcoal: #2b1b1b;
  --color-ghost-fill: #100401;
  --color-pure-white: #ffffff;
  --color-success-green: #99ff66;

  /* Typography — Font Families */
  --font-magicuipro: 'MagicUIPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.6;
  --text-body-sm: 12px;
  --leading-body-sm: 1.6;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-body-lg: 15px;
  --leading-body-lg: 1.6;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.6;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-180: 180px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 180px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 900px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-buttons: 100px;
  --radius-imagery: 900px;
  --radius-elements: 10px;

  /* Surfaces */
  --surface-canvas-white: #fcfbf7;
  --surface-paper-gray: #e7e4e0;
  --surface-ghost-fill: #100401;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcfbf7;
  --color-paper-gray: #e7e4e0;
  --color-midnight-ink: #0d0d0f;
  --color-deep-charcoal: #2b1b1b;
  --color-ghost-fill: #100401;
  --color-pure-white: #ffffff;
  --color-success-green: #99ff66;

  /* Typography */
  --font-magicuipro: 'MagicUIPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.6;
  --text-body-sm: 12px;
  --leading-body-sm: 1.6;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-body-lg: 15px;
  --leading-body-lg: 1.6;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.6;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-180: 180px;
  --spacing-208: 208px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 900px;
}
```
