# Cards Against Humanity — Style Reference
> High-contrast midnight game board

**Theme:** dark

Cards Against Humanity uses a stark, high-contrast dark mode aesthetic, reminiscent of classic card-game tabletop. Its visual system is built on a foundation of pure black and white, punctuated by vibrant, almost neon, accent colors primarily used in badges and card-like elements. Typography is bold and direct, often in all-caps, with content framed by clear borders but minimal use of soft shadows or gradients. The overall atmosphere is playful yet structured, with distinct elements standing out against the deep background.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page backgrounds, card backgrounds, primary text, solid buttons, default borders, and strong outlines |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text on dark backgrounds, ghost button text and borders, interactive element accents |
| Stinger Red | `#fe2f2f` | `--color-stinger-red` | Red accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Jester Violet | `#7333f1` | `--color-jester-violet` | Badge backgrounds, decorative borders, card accents — adds a playful, distinct brand touch |
| Mischief Yellow | `#d7b73b` | `--color-mischief-yellow` | Badge backgrounds, decorative borders, card accents — a vibrant, slightly off-kilter brand color |
| Neon Yellow | `#fffe5b` | `--color-neon-yellow` | Badge text, card backgrounds — a bright, almost luminous accent for content |
| Ghostly Violet | `#ede5ff` | `--color-ghostly-violet` | Badge text, card backgrounds — a pale, desaturated counterpoint to the vibrant accents |
| Electric Blue | `#1b5bff` | `--color-electric-blue` | Badge text, card backgrounds — a strong, clear accent color |
| Sky Blue | `#a0e9ff` | `--color-sky-blue` | Card backgrounds, decorative elements |
| Vivid Pink | `#ffa0f0` | `--color-vivid-pink` | Card backgrounds, decorative elements |
| Lime Green | `#b4ff91` | `--color-lime-green` | Card backgrounds, decorative elements |
| Burst Orange | `#ff9559` | `--color-burst-orange` | Card backgrounds, decorative elements |

## Tokens — Typography

### Helvetica Neue LT — Primary typeface for all text elements: body, links, buttons, headings, and badges. Its strong presence and varied weights support the direct, bold aesthetic, making even small text feel assertive. · `--font-helvetica-neue-lt`
- **Substitute:** Arial
- **Weights:** 400, 800
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 28px, 40px, 55px, 65px, 80px
- **Line height:** normal
- **Role:** Primary typeface for all text elements: body, links, buttons, headings, and badges. Its strong presence and varied weights support the direct, bold aesthetic, making even small text feel assertive.

### Helvetica Neue — Helvetica Neue — detected in extracted data but not described by AI · `--font-helvetica-neue`
- **Weights:** 700
- **Sizes:** 21px
- **Line height:** 1.38
- **Role:** Helvetica Neue — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.3 | — | `--text-caption` |
| body-sm | 14px | 1.3 | — | `--text-body-sm` |
| body | 16px | 1.3 | — | `--text-body` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 28px | 1.25 | — | `--text-heading` |
| heading-lg | 40px | 1.07 | — | `--text-heading-lg` |
| display | 80px | 0.98 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 13px |
| badges | 38px |
| buttons | 64px |
| default | 0px |
| largeCards | 20px |
| smallButtons | 28px |
| mediumButtons | 32px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(0, 0, 0) 0px 0px 0px 2px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(255, 255, 255) 0px 0px 0px 2px inset` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Ghost Button (Text)
**Role:** Invisible buttons with text only, used for secondary actions or navigation.

Background: transparent (rgba(0, 0, 0, 0)), Text: Canvas White (#ffffff). No padding.

### Ghost Button (Outlined)
**Role:** Secondary action buttons with a border, minimal visual weight.

Background: transparent (rgba(0, 0, 0, 0)), Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000), Radius: 0px. Padding: 0px Top/Bottom, 12px Left/Right.

### Pill Button (Filled)
**Role:** Primary global action buttons, high contrast.

Background: Midnight Ink (#000000), Text: Canvas White (#ffffff). Radius: 64px. Padding: 0px Top/Bottom, 40px Left/Right.

### Pill Button (Outlined)
**Role:** Distinct secondary action buttons, visually rounded.

Background: transparent (rgba(0, 0, 0, 0)), Text: Canvas White (#ffffff), Border: 1px solid Canvas White (#ffffff). Radius: 32px. No padding.

### Base Card
**Role:** Background for product information or content blocks.

Background: transparent (rgba(0, 0, 0, 0)), Radius: 0px. Padding: 20px Top, 0px Right/Bottom/Left.

### White Featured Card
**Role:** Elevated highlight card for special content.

Background: Canvas White (#ffffff), Radius: 13px. No padding.

### Dark Featured Card
**Role:** Elevated highlight card on dark backgrounds.

Background: Midnight Ink (#000000), Radius: 13px. No padding.

### Rounded Input
**Role:** Input fields for data entry.

Background: transparent (rgba(0, 0, 0, 0)), Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000), Radius: 0px. No padding.

### Pill Badge (Stinger Red)
**Role:** Status indicators or categorical labels.

Background: Stinger Red (#fe2f2f), Text: Neon Yellow (#fffe5b), Radius: 38px. Padding: 0px Top/Bottom, 20px Left/Right.

### Pill Badge (Jester Violet)
**Role:** Status indicators or categorical labels.

Background: Jester Violet (#7333f1), Text: Ghostly Violet (#ede5ff), Radius: 38px. Padding: 0px Top/Bottom, 20px Left/Right.

### Pill Badge (Mischief Yellow)
**Role:** Status indicators or categorical labels.

Background: Mischief Yellow (#d7b73b), Text: Electric Blue (#1b5bff), Radius: 38px. Padding: 0px Top/Bottom, 20px Left/Right.

## Do's and Don'ts

### Do
- Always use Midnight Ink (#000000) for page backgrounds and primary text.
- Utilize Canvas White (#ffffff) for text on dark backgrounds and ghost button elements.
- Apply 64px border-radius to primary filled buttons and 38px to badges for consistent rounding.
- Emphasize content blocks with distinct background colors such as Neon Yellow (#fffe5b) or Electric Blue (#1b5bff) for cards.
- Use Stinger Red (#fe2f2f), Jester Violet (#7333f1), or Mischief Yellow (#d7b73b) for badge backgrounds and prominent decorative borders.
- Employ the Helvetica Neue LT typeface at varied weights for all text elements to maintain a unified, bold voice.
- Maintain a spacious density with a base element gap of 10px and card padding of 20px.

### Don't
- Avoid soft shadows; the system relies on hard borders and high contrast for visual separation.
- Do not introduce gradients unless explicitly defined; use solid colors for all UI elements.
- Refrain from using desaturated color palettes; the brand's identity is built on vivid, high-contrast accents.
- Do not deviate from the Helvetica Neue LT font family; its specific weights are crucial to the brand's typographic tone.
- Avoid small, subtle text; the system prefers direct, legible typography, often in larger sizes.
- Do not use generic border radii; adhere to the defined values of 0px, 13px, 20px, 32px, 38px, and 64px for specific components.
- Do not obscure backgrounds with complex imagery; backgrounds should be stark and allow UI elements to pop.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Base Canvas | `#000000` | Dominant background for the entire application, providing a deep, dark foundation. |
| 2 | Featured Card White | `#ffffff` | Primary surface for interactive cards or content blocks, providing strong contrast on the dark canvas. |
| 3 | Featured Card Dark | `#000000` | Used for card-like elements on sections that might already be dark, maintaining the card structure. |
| 4 | Accent Card Yellow | `#fffe5b` | Highlight cards with vibrant color, drawing immediate attention to featured content. |

## Elevation

- **Checkbox (focused/active):** `rgb(0, 0, 0) 0px 0px 0px 2px inset`
- **Checkbox (selected):** `rgb(255, 255, 255) 0px 0px 0px 2px inset`

## Imagery

The visual language of imagery largely consists of product shots of the game cards themselves, often in dynamic, scattered arrangements on a dark background. Photography is high-contrast and often features close-ups of card text. Illustrations are rare but lean towards flat, icon-like graphics that align with the game's direct and often humorous aesthetic. Icons are filled and bold, complementing the strong typography. Imagery serves a decorative atmosphere, showcasing the product playfully, and is image-heavy, contributing significantly to the page's visual impact and brand identity.

## Layout

The page primarily uses a full-bleed layout, where content stretches edge-to-edge, especially for hero sections and large visual elements. Within this, content is often centered vertically and horizontally, creating a sense of directness. Sections maintain consistent vertical spacing, often with visible dividers or alternating contrasting dark and light card-like backgrounds to break up the flow. Element arrangements vary from centered stacks to multi-column grids for presenting different products or features, with a preference for bold, eye-catching presentations that utilize vivid background colors for individual cards. Navigation is handled by a minimal sticky top bar.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #000000
accent: #fe2f2f
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a header navigation link: text 'Shop', Canvas White (#ffffff) using Helvetica Neue LT weight 400 at 16px, no padding or border, transparent background.
2. Create a 'Buy Now' button: text 'Buy Now', Canvas White (#ffffff) using Helvetica Neue LT weight 800 at 16px, background Midnight Ink (#000000), border 1px solid Canvas White (#ffffff), 64px border-radius, 40px left/right padding.
3. Create a 'Black Friday 2018' badge: text 'Black Friday 2018', Neon Yellow (#fffe5b) using Helvetica Neue LT weight 800 at 14px, background Stinger Red (#fe2f2f), 38px border-radius, 20px left/right padding.
4. Design a 'Cookie Settings' modal: Use Midnight Ink (#000000) for the background, 13px border radius. Titles should be Canvas White (#ffffff) Helvetica Neue LT weight 800 at 24px. Body text should be Canvas White (#ffffff) Helvetica Neue LT weight 400 at 16px. Outlined buttons 'Accept All' should have Canvas White (#ffffff) borders and text with 0px radius, 12px left/right padding. Checked checkboxes should have a rgb(0, 0, 0) 0px 0px 0px 2px inset box-shadow.

## Similar Brands

- **Jackbox Games** — High-contrast dark UI, playful and direct typography, minimal imagery outside of game assets.
- **Cards Against Humanity (UK)** — Naturally, maintains identical brand elements: black/white, bold sans-serif, direct language.
- **Exploding Kittens** — Distinctive, often irreverent brand voice reflected in bold typography and high-contrast visuals, though with more illustration.
- **Betrayal at House on the Hill** — Heavy reliance on card-based UI presentation, though with a different thematic aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-stinger-red: #fe2f2f;
  --color-jester-violet: #7333f1;
  --color-mischief-yellow: #d7b73b;
  --color-neon-yellow: #fffe5b;
  --color-ghostly-violet: #ede5ff;
  --color-electric-blue: #1b5bff;
  --color-sky-blue: #a0e9ff;
  --color-vivid-pink: #ffa0f0;
  --color-lime-green: #b4ff91;
  --color-burst-orange: #ff9559;

  /* Typography — Font Families */
  --font-helvetica-neue-lt: 'Helvetica Neue LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.07;
  --text-display: 80px;
  --leading-display: 0.98;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 13px;
  --radius-2xl: 20px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 38px;
  --radius-full: 64px;
  --radius-full-2: 80px;

  /* Named Radii */
  --radius-cards: 13px;
  --radius-badges: 38px;
  --radius-buttons: 64px;
  --radius-default: 0px;
  --radius-largecards: 20px;
  --radius-smallbuttons: 28px;
  --radius-mediumbuttons: 32px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgb(255, 255, 255) 0px 0px 0px 2px inset;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-featured-card-white: #ffffff;
  --surface-featured-card-dark: #000000;
  --surface-accent-card-yellow: #fffe5b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-stinger-red: #fe2f2f;
  --color-jester-violet: #7333f1;
  --color-mischief-yellow: #d7b73b;
  --color-neon-yellow: #fffe5b;
  --color-ghostly-violet: #ede5ff;
  --color-electric-blue: #1b5bff;
  --color-sky-blue: #a0e9ff;
  --color-vivid-pink: #ffa0f0;
  --color-lime-green: #b4ff91;
  --color-burst-orange: #ff9559;

  /* Typography */
  --font-helvetica-neue-lt: 'Helvetica Neue LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.07;
  --text-display: 80px;
  --leading-display: 0.98;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 13px;
  --radius-2xl: 20px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 38px;
  --radius-full: 64px;
  --radius-full-2: 80px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgb(255, 255, 255) 0px 0px 0px 2px inset;
}
```
