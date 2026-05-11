# Contrast — Style Reference
> Vivid pulse on a static canvas.

**Theme:** light

Contrast employs a clean, high-contrast visual system with energetic pops of vivid color on a predominantly achromatic canvas. Sharp, direct typography in black creates a confident and clear hierarchy. Components are lightweight and float subtly with soft shadows, prioritizing information and interaction over heavy ornamentation. The overall impression is one of modern, efficient clarity with a focused urgency for action.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Red Action | `#ff5065` | `--color-red-action` | Primary action buttons, active states, and focus indicators — generates urgency and draws immediate attention |
| Orange Highlight | `#ff7a59` | `--color-orange-highlight` | Accent for headings, decorative icons, and subtle text highlights. Creates a secondary focal point with energetic warmth |
| Amber Detail | `#ff5c35` | `--color-amber-detail` | Used for smaller decorative elements, icons, and some text, adding a vibrant detail layer |
| Jet Black | `#000000` | `--color-jet-black` | Primary text, strong contrasts, icon fills, and defining borders. Provides anchor points in the bright UI |
| Canvas White | `#ffffff` | `--color-canvas-white` | Base page backgrounds, card surfaces, and primary button text. Creates a spacious, bright environment |
| Ebony Text | `#0e0f10` | `--color-ebony-text` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Slate Gray | `#2f3133` | `--color-slate-gray` | Subtle card backgrounds, badge backgrounds, and tertiary text or borders |
| Whisper Gray | `#f4f4f8` | `--color-whisper-gray` | Subtle background for sections, creating visual separation without strong contrast |
| Dark Neutral Button | `#1c1d1e` | `--color-dark-neutral-button` | Background for secondary or ghost buttons, offering a strong alternative to the primary Red Action |
| Stone Text | `#7a7b7c` | `--color-stone-text` | Muted text, helper text, and less prominent iconography or borders, maintaining legibility with reduced visual weight |
| Mid Gray | `#666666` | `--color-mid-gray` | Supporting text for bodies and links, providing a slightly softer contrast than Jet Black |
| Pewter Accent | `#4a4b4c` | `--color-pewter-accent` | Accent color for specific card text and borders, signaling subtle detail or secondary information |

## Tokens — Typography

### Gilroy — The primary typeface for all text content, from navigation and body text to prominent headings and buttons. Its varied weights are used to establish information hierarchy, with bolder weights for headlines and calls to action, and lighter weights for body text, maintaining a confident, direct tone. · `--font-gilroy`
- **Substitute:** system-ui
- **Weights:** 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 48px, 56px
- **Line height:** 0.80, 1.00, 1.11, 1.17, 1.20, 1.25, 1.33, 1.43, 1.50, 1.56, 1.60, 1.78, 1.80, 1.88, 1.90
- **Letter spacing:** normal
- **Role:** The primary typeface for all text content, from navigation and body text to prominent headings and buttons. Its varied weights are used to establish information hierarchy, with bolder weights for headlines and calls to action, and lighter weights for body text, maintaining a confident, direct tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.56 | — | `--text-body-lg` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading | 48px | 1.17 | — | `--text-heading` |
| display | 56px | 1.11 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 100px |
| cards | 24px |
| small | 4px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(38, 42, 62, 0.06) 0px 5px 25px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** High-priority call to action

Filled button with Red Action background (#ff5065), Canvas White text (#ffffff), and a 20px (large) or 24px (hero) border-radius. Padding is generous: 24px vertical, 40px horizontal.

### Dark Secondary Button
**Role:** Secondary action or ghost button

Filled button with Dark Neutral Button background (#1c1d1e), Canvas White text (#ffffff), and a 24px border-radius. Features large padding: 40px vertical, 40px horizontal.

### Light Outlined Button
**Role:** Tertiary action button or subtly interactive element

White background (#ffffff), Ebony Text (#0e0f10) text, with a light border rgba(14, 15, 16, 0.15). Radius is 20px for larger instances, 16px for smaller. Padding is 24px vertical, 40px horizontal (large) or 16px vertical, 24px horizontal (small).

### Elevated Card
**Role:** Content container that stands out

Canvas White background (#ffffff), 24px border-radius, and a subtle shadow (rgba(38, 42, 62, 0.06) 0px 5px 25px 0px). Inner content is padded by 32px on all sides.

### Ghost Card
**Role:** Content container with minimal visual impact

Transparent background, 16px or 24px border-radius, no shadow, and no internal padding from the card itself (content dictates padding). Used for structural grouping rather than visual prominence.

### Feature Badge
**Role:** Small, informational label

Slate Gray background (#2f3133), Canvas White text (#ffffff), with a large 100px border-radius (pill shape). Horizontal padding of 12px, no vertical padding.

## Do's and Don'ts

### Do
- Use Red Action (#ff5065) exclusively for primary calls-to-action or critical indicators, ensuring it is a singular focal point.
- Maintain a clear visual hierarchy by differentiating headings with Jet Black (#000000) and body text with Ebony Text (#0e0f10) or Stone Text (#7a7b7c).
- Apply a minimal shadow (rgba(38, 42, 62, 0.06) 0px 5px 25px 0px) to elevated cards, ensuring components feel light and layered, not heavy.
- Utilize the 100px border-radius for all buttons and badges to consistently maintain a modern, continuous pill shape.
- Structure page sections with varying backgrounds like Canvas White (#ffffff) and Whisper Gray (#f4f4f8) to create visual breaks with a comfortable density.
- Apply a consistent 32px padding within elevated card components to give content breathing room.
- Pair Gilroy 700 with Jet Black (#000000) or Gilroy 600 with Ebony Text (#0e0f10) for headings to achieve a direct, commanding tone.

### Don't
- Do not introduce additional saturated colors beyond Red Action, Orange Highlight, and Amber Detail; maintain the clean achromatic base.
- Avoid heavy borders or solid color backgrounds on cards unless it's a specific, interactive action, to preserve the light and floating aesthetic.
- Do not vary letter-spacing from 'normal'; the Gilroy typeface already provides sufficient distinction.
- Refrain from using shadows on elements other than elevated cards; elevation should be a subtle indicator, not pervasive.
- Do not use generic system fonts; always specify Gilroy to uphold the brand's typographic signature.
- Avoid creating new text sizes or line heights; adhere strictly to the established type scale to maintain rhythm and hierarchy.
- Do not over-use the Orange Highlight (#ff7a59) or Amber Detail (#ff5c35); these are accents for emphasis, not general-purpose colors.

## Elevation

- **Elevated Card:** `rgba(38, 42, 62, 0.06) 0px 5px 25px 0px`

## Imagery

The visual language for imagery primarily features product screenshots or candid business photography, often tightly cropped or contained within rounded card components. Images are typically integrated directly into content blocks, serving an explanatory or testimonial role rather than purely decorative. Icons are often simple, outlined, and monochromatic, occasionally featuring a brand accent color. Density is moderate; imagery supports the textual content without overwhelming it.

## Layout

The page maintains a centered, max-width layout, approximately 1200px, with content contained within this boundary. The hero section presents a prominent centered headline and body text over a clean white background, flanked by call-to-action buttons. Sections alternate between pure white and subtle Whisper Gray (#f4f4f8) backgrounds, creating a clear vertical rhythm. Content is generally arranged in two-column layouts, often with text on one side and a visual element (like a card or image) on the other. Card grids, typically 3 or 4 columns, are used to showcase features or testimonials. Navigation is a persistent top bar, with interactive elements clearly marked.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #7a7b7c
accent: #ff7a59
primary action: #ff5065 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff5065 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create an Elevated Card: Canvas White background (#ffffff), 24px radius, shadow rgba(38, 42, 62, 0.06) 0px 5px 25px 0px. Internal content should have 32px padding on all sides. Heading (Gilroy 20px, weight 600, Jet Black #000000). Body text (Gilroy 16px, weight 500, Stone Text #7a7b7c).
3. Create a Dark Secondary Button: Dark Neutral Button background (#1c1d1e), Canvas White text (#ffffff), 24px radius, 40px vertical padding, 40px horizontal padding. Text (Gilroy 16px, weight 600).
4. Create a Feature Badge: Slate Gray background (#2f3133), Canvas White text (#ffffff), 100px radius, 12px horizontal padding, 0px vertical padding. Text (Gilroy 14px, weight 500).

## Similar Brands

- **Calendly** — Similar light, spacious UI with strong black typography and a single vibrant accent color for primary actions.
- **Linear** — Employs a minimal, high-contrast aesthetic with sharp typography, subtle surface differentiation, and focused use of brand colors for interaction.
- **Vercel** — Shares a clean, modern design with clear typography, structured layouts, and a limited, purposeful color palette on a light background.
- **Notion** — Focuses on a minimalist aesthetic with strong typography on a white canvas, using color sparingly for functional accents and interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-red-action: #ff5065;
  --color-orange-highlight: #ff7a59;
  --color-amber-detail: #ff5c35;
  --color-jet-black: #000000;
  --color-canvas-white: #ffffff;
  --color-ebony-text: #0e0f10;
  --color-slate-gray: #2f3133;
  --color-whisper-gray: #f4f4f8;
  --color-dark-neutral-button: #1c1d1e;
  --color-stone-text: #7a7b7c;
  --color-mid-gray: #666666;
  --color-pewter-accent: #4a4b4c;

  /* Typography — Font Families */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.56;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --text-display: 56px;
  --leading-display: 1.11;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 120px;

  /* Named Radii */
  --radius-tags: 100px;
  --radius-cards: 24px;
  --radius-small: 4px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-xl: rgba(38, 42, 62, 0.06) 0px 5px 25px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-red-action: #ff5065;
  --color-orange-highlight: #ff7a59;
  --color-amber-detail: #ff5c35;
  --color-jet-black: #000000;
  --color-canvas-white: #ffffff;
  --color-ebony-text: #0e0f10;
  --color-slate-gray: #2f3133;
  --color-whisper-gray: #f4f4f8;
  --color-dark-neutral-button: #1c1d1e;
  --color-stone-text: #7a7b7c;
  --color-mid-gray: #666666;
  --color-pewter-accent: #4a4b4c;

  /* Typography */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.56;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --text-display: 56px;
  --leading-display: 1.11;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 120px;

  /* Shadows */
  --shadow-xl: rgba(38, 42, 62, 0.06) 0px 5px 25px 0px;
}
```
