# Voiceflow — Style Reference
> AI Blueprint on White Canvas

**Theme:** light

Voiceflow presents a light and airy interface, built on a spacious canvas of off-white and crisp backgrounds, punctuated by a single vibrant blue for primary actions. Typography is precise and clear, with a preference for slightly condensed sans-serifs for body text and a light, elegant serif for dramatic headlines. Cards and elements feature large, comfortable padding and rounded corners, creating a friendly yet professional feel. The overall impression is one of confident, approachable AI technology, with visual complexity reserved for product demonstrations.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Skybound Blue | `#397dff` | `--color-skybound-blue` | Primary Call-to-Action buttons and interactive elements, representing activation and core functionality |
| Amber Pop | `#f55c15` | `--color-amber-pop` | Accent for badges, status indicators, and subtle highlights — a burst of energy to draw attention to key information |
| Impact Red | `#ff0000` | `--color-impact-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Ultramarine | `#1956f3` | `--color-ultramarine` | A deeper, more saturated blue used sparingly for large background fills, providing a dramatic accent |
| Inkwell | `#171717` | `--color-inkwell` | Primary heading text and critical information, providing strong contrast on light backgrounds |
| Deep Graphite | `#262626` | `--color-deep-graphite` | Secondary text, dark backgrounds for subtle distinctions, and focused elements like secondary buttons |
| Anchor Gray | `#333333` | `--color-anchor-gray` | Muted text, borders, and dividers where a softer presence is desired than Deep Graphite |
| Slate Text | `#525252` | `--color-slate-text` | Body copy and standard informational text, ensuring readability without being overly stark |
| Quiet Stone | `#737373` | `--color-quiet-stone` | Helper text, subtle borders, and placeholder content. Creates a whisper of presence |
| Silver Thread | `linear-gradient(90deg, rgb(161, 161, 161) 0%, rgb(161, 161, 161) 40%, rgb(115, 115, 115) 45%, rgb(64, 64, 64) 50%, rgb(115, 115, 115) 55%, rgb(161, 161, 161) 60%, rgb(161, 161, 161) 100%)` | `--color-silver-thread` | Hairline borders, disabled states, and very subtle UI elements, offering minimum contrast; Background for transparent UI elements, providing a frosted effect |
| Platinum Mist | `#d4d4d4` | `--color-platinum-mist` | Light borders, inactive states, and structural dividers that define content regions without drawing focus |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page backgrounds, card surfaces, and text on dark backgrounds, providing a clean default surface |
| Whisper White | `#f5f5f4` | `--color-whisper-white` | Subtle background for UI elements or sections to provide a minimal visual break from Canvas White |
| Light Cloud | `#edeeee` | `--color-light-cloud` | Alternate background for sections or secondary surface treatments, providing a slightly darker canvas than Whisper White |
| Border Ash | `#e5e5e5` | `--color-border-ash` | Default borders and subtle separators for cards and input fields. Clearly defines boundaries |

## Tokens — Typography

### Tiempos Headline — Primary display and section headings. The light weight (300) conveys authority through restraint, preferring elegance over shouting. Used for the prominent product name and key messages. · `--font-tiempos-headline`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 20px, 36px, 40px, 48px, 56px, 64px
- **Line height:** 1.00, 1.13, 1.14, 1.16, 1.20, 1.30
- **Letter spacing:** -0.0400em for larger sizes like 56px, tapering to -0.0170em at 20px
- **Role:** Primary display and section headings. The light weight (300) conveys authority through restraint, preferring elegance over shouting. Used for the prominent product name and key messages.

### Selecta — Body copy, UI labels, buttons, navigation, and detailed information. Its slightly condensed forms maintain a compact yet readable presence across the interface. · `--font-selecta`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 8px, 13px, 14px, 15px, 16px, 18px
- **Line height:** 0.80, 1.00, 1.16, 1.38, 1.44, 1.47, 1.50, 1.55, 1.75
- **Letter spacing:** Ranges from 0.0400em at 8px to 0.0180em at 18px
- **Role:** Body copy, UI labels, buttons, navigation, and detailed information. Its slightly condensed forms maintain a compact yet readable presence across the interface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 16px | 1.47 | 0.25px | `--text-body-lg` |
| subheading | 20px | 1.3 | -0.34px | `--text-subheading` |
| heading | 36px | 1.14 | -0.72px | `--text-heading` |
| heading-lg | 48px | 1.13 | -0.96px | `--text-heading-lg` |
| display | 56px | 1.16 | -1.68px | `--text-display` |

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
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 100px |
| cards | 20px |
| buttons | 999px |
| productImageCard | 14px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Main call to action

Filled button with Skybound Blue (#397dff) background, Canvas White (#ffffff) text, and a 999px border-radius for a soft, pill-like shape. Padding is generous: 10px vertical, 20px horizontal.

### Secondary Ghost Button
**Role:** Alternative action

Ghost button with transparent background, Quiet Stone (#737373) text and border, featuring a 999px border-radius. Padding is 10px vertical, 20px horizontal, matching the primary action for size parity but reduced visual weight.

### Small Dark Tag
**Role:** Informational tag

Used for quick labels, with Deep Graphite (#262626) background and Canvas White (#ffffff) text. Features minimal 2px vertical, 4px horizontal padding, and a 999px border-radius.

### Content Card
**Role:** Container for information

Background is Canvas White (#ffffff) with 20px border-radius. Features 24px internal padding for comfortable content separation. No default shadow for a light aesthetic.

### Product Feature Card
**Role:** Showcasing product screens

Transparent background with a distinct 14px border-radius (top-right corner), sometimes featuring a subtle blur effect on its backdrop. Used for displaying product UI snippets.

### Informational Badge
**Role:** Highlighting keywords or categories

Transparent background with Amber Pop (#f55c15) text, no padding. Used for concise, high-visibility labels like 'Omnichannel Support'.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary backgrounds and Content Card surfaces, maintaining a bright and open feel.
- Use Skybound Blue (#397dff) exclusively for primary interactive elements, ensuring all core actions are distinctly colored.
- Apply a 999px border-radius to all buttons and tags, creating a consistent, friendly pill shape.
- Employ Tiempos Headline (weight 300) for all major headings to convey quiet authority and elegance.
- Use 24px as the primary value for `elementGap` and `cardPadding` to ensure a consistent, comfortable density.
- Define UI borders and dividers using Platinum Mist (#d4d4d4) for soft separation, or Quiet Stone (#737373) for slightly more emphasis.
- Allow imagery, especially product mockups, to feature transparent or semi-transparent backgrounds to integrate seamlessly with the light canvas.

### Don't
- Avoid using saturated colors in large blocks unless specifically for brand accents like Ultramarine (#1956f3).
- Do not introduce heavy shadows or gradients; maintain the light and airy surface treatment.
- Refrain from using Tiempos Headline for body text or small labels; reserve it for large display typography.
- Do not deviate from the established border-radius values (999px, 20px, 14px) for interactive elements and cards.
- Avoid tightly packed content where `elementGap` is less than 8px; ensure generous breathing room.
- Do not use multiple chromatic colors for primary calls to action; Skybound Blue (#397dff) is the sole accent for interactive elements.
- Never use generic system fonts; always specify 'Selecta' for body and UI, and 'Tiempos Headline' for headings.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default container surface. |
| 2 | Whisper White | `#f5f5f4` | Subtle secondary background for alternate sections or elevated UI elements. |
| 3 | Light Cloud | `#edeeee` | Tertiary background for visually distinct sections or more pronounced surface variations. |
| 4 | Frosted Glass | `#a1a1a180` | Semi-transparent overlay or background for modal-like components, utilizing a backdrop blur. |

## Imagery

The visual language predominantly features product screenshots and UI mockups, often presented on transparent or semi-transparent backgrounds. These are used to explain functionality and showcase the product directly, rather than relying on abstract concepts or lifestyle photography. When photography is used, it's typically environmental (e.g., aerial views of landscapes) as a background for text or product displays, or professional headshots for social proof. Icons are minimal, outlined, and mostly monochrome, reinforcing a focus on UI clarity. The density of imagery is balanced, with product shots interspersed with text-heavy sections to explain features.

## Layout

The page uses a maximum-width contained layout, likely around 1200px, centered on a Canvas White background. The hero section features a centered, visually strong headline on a white canvas above a subtle full-width gradient or image background, followed by prominent calls-to-action. Content sections alternate between single-column centered text blocks, two-column text-left/image-right or image-left/text-right arrangements. There is a distinct three-column card grid used for features and testimonials. Vertical spacing between sections is generous and consistent, creating comfortable reading rhythm. The navigation is a sticky top bar, providing persistent access to key links and calls to action.

## Agent Prompt Guide

### Quick Color Reference
- text: #171717 (Inkwell)
- background: #ffffff (Canvas White)
- border: #e5e5e5 (Border Ash)
- accent: #f55c15 (Amber Pop)
- primary action: #397dff (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #397dff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a `content card`: Canvas White (#ffffff) background, 20px border-radius, with 24px internal padding. Display body text at 14px Selecta weight 400, Slate Text (#525252). Highlight a keyword using an Informational Badge with transparent background, Amber Pop (#f55c15) text, no padding.
3. Create a `product feature section`: Light Cloud (#edeeee) background. Two columns: left is a heading at 36px Tiempos Headline weight 300, Inkwell (#171717), letter-spacing -0.72px. Right is an image contained within a Product Feature Card with a 14px top-right border-radius, transparent background, and backdrop-filter blur(24px).

## Similar Brands

- **Stripe** — Similar preference for light backgrounds, minimal shadows, and a strong, single accent color (Stripe's purple, Voiceflow's blue) for primary actions and brand emphasis.
- **Linear** — Shares a clean, productive UI aesthetic with structured layouts, precise typography, and a strategic use of neutrals to define hierarchy without visual clutter.
- **Figma** — Utilizes a spacious, canvas-like design approach with prominent content cards, subtle borders, and an emphasis on showcasing product UI elements within the interface itself.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-skybound-blue: #397dff;
  --color-amber-pop: #f55c15;
  --color-impact-red: #ff0000;
  --color-ultramarine: #1956f3;
  --color-inkwell: #171717;
  --color-deep-graphite: #262626;
  --color-anchor-gray: #333333;
  --color-slate-text: #525252;
  --color-quiet-stone: #737373;
  --color-silver-thread: #a1a1a1;
  --gradient-silver-thread: linear-gradient(90deg, rgb(161, 161, 161) 0%, rgb(161, 161, 161) 40%, rgb(115, 115, 115) 45%, rgb(64, 64, 64) 50%, rgb(115, 115, 115) 55%, rgb(161, 161, 161) 60%, rgb(161, 161, 161) 100%);
  --color-platinum-mist: #d4d4d4;
  --color-canvas-white: #ffffff;
  --color-whisper-white: #f5f5f4;
  --color-light-cloud: #edeeee;
  --color-border-ash: #e5e5e5;

  /* Typography — Font Families */
  --font-tiempos-headline: 'Tiempos Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-selecta: 'Selecta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 16px;
  --leading-body-lg: 1.47;
  --tracking-body-lg: 0.25px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.34px;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.16;
  --tracking-display: -1.68px;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-2xl: 20px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 100px;
  --radius-cards: 20px;
  --radius-buttons: 999px;
  --radius-productimagecard: 14px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-whisper-white: #f5f5f4;
  --surface-light-cloud: #edeeee;
  --surface-frosted-glass: #a1a1a180;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-skybound-blue: #397dff;
  --color-amber-pop: #f55c15;
  --color-impact-red: #ff0000;
  --color-ultramarine: #1956f3;
  --color-inkwell: #171717;
  --color-deep-graphite: #262626;
  --color-anchor-gray: #333333;
  --color-slate-text: #525252;
  --color-quiet-stone: #737373;
  --color-silver-thread: #a1a1a1;
  --color-platinum-mist: #d4d4d4;
  --color-canvas-white: #ffffff;
  --color-whisper-white: #f5f5f4;
  --color-light-cloud: #edeeee;
  --color-border-ash: #e5e5e5;

  /* Typography */
  --font-tiempos-headline: 'Tiempos Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-selecta: 'Selecta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 16px;
  --leading-body-lg: 1.47;
  --tracking-body-lg: 0.25px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.34px;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.16;
  --tracking-display: -1.68px;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-2xl: 20px;
  --radius-full: 100px;
  --radius-full-2: 999px;
}
```
