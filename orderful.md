# Orderful — Style Reference
> Precision on White Canvas

**Theme:** light

Orderful employs a design language of precision and vibrant urgency, utilizing a bright, spacious canvas punctuated by sharp, functional typography. A single vivid orange accent color drives primary actions and highlights, creating immediate visual focus against a largely achromatic interface. Components lean towards lightweight forms with subtle elevation, promoting a sense of speed and efficiency in a data-heavy environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Fog | `#f5f5f5` | `--color-canvas-fog` | Page background, subtle card backgrounds, navigational elements |
| Surface Snow | `#ffffff` | `--color-surface-snow` | Primary card surfaces, button backgrounds, input fields, overlay elements |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong headings, button text, borders, and UI icons, establishing high contrast |
| Graphite Text | `#4a5565` | `--color-graphite-text` | Secondary text, body copy, and muted borders. A slightly softer alternative to Ink Black |
| Slate Gray | `#364153` | `--color-slate-gray` | Navigation text and specific UI elements, slightly darker than Graphite Text |
| Whisper Gray | `#99a1af` | `--color-whisper-gray` | Tertiary text, decorative icons, and subtle borders, for low-priority information |
| Subdued Gray | `#676767` | `--color-subdued-gray` | Section headings with a softer presence than Ink Black |
| Border Ash | `#d4d4d4` | `--color-border-ash` | Hairline borders, subtle dividers, and input field outlines |
| Deep Shadow | `#1f1f1f` | `--color-deep-shadow` | Background for elevated cards or sections, indicating depth |
| Action Blaze | `#e42b0c` | `--color-action-blaze` | Primary call-to-action buttons, active states, and critical highlights – the sole vivid accent |
| Gradient Aura | `linear-gradient(94deg, rgb(255, 2, 1) -33.85%, rgb(255, 120, 2) -1.54%, rgb(255, 2, 1) 73.55%)` | `--color-gradient-aura` | Decorative gradients in hero sections and prominent visual elements, evoking energy and dynamism |

## Tokens — Typography

### telegraf — Primary brand typeface for all headings, body text, buttons, and UI elements. Its sharp, modern geometry supports the authoritative and efficient brand image. The variable letter-spacing, particularly at larger sizes, creates a precise, almost condensed feel for headlines. · `--font-telegraf`
- **Substitute:** Montserrat, Raleway
- **Weights:** 100, 300, 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 30px, 48px, 60px, 72px
- **Line height:** 1.00, 1.20, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** 0, 0, 0, 0, 0, 0, -0.75, -1.44, -1.5, -2.16
- **OpenType features:** `"case", "dlig"`
- **Role:** Primary brand typeface for all headings, body text, buttons, and UI elements. Its sharp, modern geometry supports the authoritative and efficient brand image. The variable letter-spacing, particularly at larger sizes, creates a precise, almost condensed feel for headlines.

### modernGothic — Secondary typeface predominantly used for subtle hints, links, or specific decorative text. Its light weight and 'ss02' stylistic set add a touch of unique character. · `--font-moderngothic`
- **Substitute:** IBM Plex Sans Light
- **Weights:** 300
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** 0
- **OpenType features:** `"ss02"`
- **Role:** Secondary typeface predominantly used for subtle hints, links, or specific decorative text. Its light weight and 'ss02' stylistic set add a touch of unique character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 30px | 1.2 | -0.75px | `--text-heading-lg` |
| display | 48px | 1 | -1.44px | `--text-display` |
| display-lg | 60px | 1 | -1.5px | `--text-display-lg` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** CTA button

Filled with Action Blaze (#e42b0c), white text, 8px border-radius, 12px vertical padding, 24px horizontal padding. Prominently calls to action.

### Secondary Action Button
**Role:** Secondary button

Filled with Ink Black (#000000), white text, 6px border-radius, 12px vertical padding, 24px horizontal padding. Used for important but not primary actions.

### Ghost Button
**Role:** Tertiary button

Transparent background, Ink Black (#000000) text, 8px border-radius, 32px vertical padding, 16px horizontal padding. Used for less prominent actions, often within sections.

### Card - Default
**Role:** Content container

backgroundColor=Surface Snow (#ffffff), 8px border-radius, 32px padding, subtle shadow (rgba(0,0,0,0.1) 0px 1px 3px 0px, rgba(0,0,0,0.1) 0px 1px 2px -1px). Used for feature blocks and testimonial cards.

### Card - Elevated
**Role:** Accentuated content container

backgroundColor=Deep Shadow (#1f1f1f), 8px border-radius, 96px vertical padding, 64px horizontal padding, no shadow. Used for visually distinct sections or hero content on deeper backgrounds.

### Card - Section
**Role:** Full-width section container

backgroundColor=Canvas Fog (#f5f5f5), 8px border-radius, 4px padding. Used to segment page content visually.

### Input Field
**Role:** Data entry control

backgroundColor=Surface Snow (#ffffff), Border Ash (#d4d4d4) 1px border, 4px border-radius, 16px padding. Text color is Ink Black (#000000).

## Do's and Don'ts

### Do
- Always use telegraf for all text elements; prefer weights 400 and above for readability and impact, reserving lighter weights (300) for subheadings only.
- Utilize Action Blaze (#e42b0c) exclusively for primary calls-to-action to maximize its impact and differentiate it from other interactive elements.
- Maintain a clear visual hierarchy of surfaces: Canvas Fog (#f5f5f5) for the base, then Surface Snow (#ffffff) for cards and inputs, and Deep Shadow (#1f1f1f) for prominent, darker content blocks.
- Apply an 8px border-radius to all interactive elements, cards, and input fields to maintain a consistent, slightly softened aesthetic.
- Use Ink Black (#000000) for all primary text and critical UI elements, ensuring maximum contrast and readability on light backgrounds.
- Implement consistent internal padding of 16px and 24px for component elements and text blocks to define clear content areas.
- Employ the mild elevation shadow (rgba(0,0,0,0.1) 0px 1px 3px 0px, rgba(0,0,0,0.1) 0px 1px 2px -1px) sparingly, primarily for interactive cards or elements that require subtle projection.

### Don't
- Do not introduce new chromatic colors; Action Blaze (#e42b0c) is the singular brand accent.
- Avoid using multiple border-radii values; the consistent 8px radius is a core part of the system's shape language.
- Do not apply strong shadows or complex gradients to buttons or cards unless explicitly defined; elements should feel lightweight.
- Refrain from deviating from the defined telegraf and modernGothic font families or their specified weights and letter-spacing values.
- Do not use dark backgrounds interchangeably with light ones; adhere strictly to the light theme model where Canvas Fog (#f5f5f5) is the dominant base.
- Avoid dense packing of content; ensure ample white space and adhere to the 16px element gap and 40px section gap to maintain a comfortable reading experience.

## Elevation

- **Card - Default:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

## Imagery

The imagery consists primarily of abstract, tech-oriented graphics and stylized product UI screenshots. Graphics use a limited color palette, often incorporating transparent overlays of the brand's orange-red gradient, making them feel integrated rather than decorative. Product UI screenshots are contained within structured, often dark, frames, presenting data and system flows with a focused, informational purpose. There are no lifestyle photos or complex illustrations; the visual language is direct and functional. Icons are simple, monochrome, and filled, used semantically to reinforce meaning without adding visual noise. Image density is moderate, used to break up text-heavy sections or highlight key features.

## Layout

The page maintains a centered, max-width contained layout at 1440px. The hero section features a prominent headline to the left, paired with a dynamic, dark-themed product UI visual on the right. Content sections alternate between subtle gray bands (Canvas Fog) and crisp white (Surface Snow), creating a predictable vertical rhythm. Feature blocks are presented in a two-column text-left/image-right alternating pattern or a three-column card grid, providing clear visual organization. Navigation is a sticky top bar, providing persistent access to key sections. The overall density is comfortable, ensuring sufficient breathing room between content blocks and sections.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f5f5f5
border: #d4d4d4
accent: #e42b0c
primary action: #e42b0c (filled action)

Example Component Prompts:
1. Create a Primary Action Button: filled with Action Blaze (#e42b0c), white text (#ffffff), 8px border-radius, 12px vertical padding, 24px horizontal padding, 'telegraf' font family, weight 700.
2. Create a Card - Default: background Surface Snow (#ffffff), 8px border-radius, 32px padding, with elevation shadow rgba(0,0,0,0.1) 0px 1px 3px 0px, rgba(0,0,0,0.1) 0px 1px 2px -1px. Inside, use Graphite Text (#4a5565) for body, and Ink Black (#000000) for heading, both 'telegraf' font.
3. Create a Ghost Button: transparent background, Ink Black (#000000) text, 8px border-radius, 32px vertical padding, 16px horizontal padding, 'telegraf' font family, weight 400.
4. Create an Input Field: background Surface Snow (#ffffff), Border Ash (#d4d4d4) 1px border, 4px border-radius, 16px padding, Ink Black (#000000) text for input, 'telegraf' font family, weight 400.

## Similar Brands

- **Stripe** — Clean, spacious layout with strong typography and a single, vibrant accent color for calls to action against a predominantly white background.
- **Linear** — Focus on high information density, precise typography with careful letter-spacing, and a minimalist aesthetic using a disciplined color palette.
- **Vercel** — Modern-looking product UI with clear, functional components, emphasis on dark-mode for code/product visuals, and strong brand presence through concise text and minimal color.
- **Replit** — Clean white and dark surfaces for UI elements, technical content focus, and a direct visual approach with functional, legible type.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-fog: #f5f5f5;
  --color-surface-snow: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #4a5565;
  --color-slate-gray: #364153;
  --color-whisper-gray: #99a1af;
  --color-subdued-gray: #676767;
  --color-border-ash: #d4d4d4;
  --color-deep-shadow: #1f1f1f;
  --color-action-blaze: #e42b0c;
  --color-gradient-aura: #ff7802;
  --gradient-gradient-aura: linear-gradient(94deg, rgb(255, 2, 1) -33.85%, rgb(255, 120, 2) -1.54%, rgb(255, 2, 1) 73.55%);

  /* Typography — Font Families */
  --font-telegraf: 'telegraf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-moderngothic: 'modernGothic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;
  --text-display-lg: 60px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.5px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;
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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;

  /* Named Radii */
  --radius-all: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-fog: #f5f5f5;
  --color-surface-snow: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #4a5565;
  --color-slate-gray: #364153;
  --color-whisper-gray: #99a1af;
  --color-subdued-gray: #676767;
  --color-border-ash: #d4d4d4;
  --color-deep-shadow: #1f1f1f;
  --color-action-blaze: #e42b0c;
  --color-gradient-aura: #ff7802;

  /* Typography */
  --font-telegraf: 'telegraf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-moderngothic: 'modernGothic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;
  --text-display-lg: 60px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.5px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
}
```
