# ElevenReader — Style Reference
> diffused light on a minimalist stage

**Theme:** light

This design evokes a sense of airy professionalism, like a digital stage bathed in diffused light presenting focused information. The near-monochromatic palette uses subtle off-whites and grays to create spaciousness, punctuated by sharp black text and interactive elements. The deliberate contrast between full-round pill shapes and sharp 16px corners on cards establishes a nuanced balance between approachable softness and precise functionality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, buttons, brand elements — provides stark contrast on light backgrounds. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, button text — ensures clarity and an open feel. |
| Ash Gray | `#e5e5e5` | `--color-ash-gray` | Subtle borders, dividers, inactive states — defines structure without distraction. |
| Pale Mist | `#f2f2f2` | `--color-pale-mist` | Secondary button backgrounds, section backgrounds — provides a gentle visual break from stark white. |
| Faded Sky | `#f2f5fc` | `--color-faded-sky` | Subtle background shading — introduces a hint of cool without overt color. |
| Steel Gray | `#767676` | `--color-steel-gray` | Secondary text, descriptive elements — lighter than primary text for hierarchy. |
| Charcoal Haze | `#6e6e6` | `--color-charcoal-haze` | Tertiary text, subtle hints — even less prominent than secondary text. |
| Muted Lavender | `#c8d5f4` | `--color-muted-lavender` | Decorative background accent — provides a very subtle chromatic undertone without becoming a brand color. |
| Verdant Aura | `radial-gradient(50% 50%, rgb(36, 63, 43) 0%, rgb(66, 141, 116) 54%, rgb(165, 177, 221) 78.5%, rgb(236, 230, 244) 99%)` | `--color-verdant-aura` | Accent gradient start, contributing to atmospheric background effects. |
| Forest Dew | `linear-gradient(rgb(255, 255, 255) 6.04%, rgb(198, 231, 214) 59.83%)` | `--color-forest-dew` | Subtle background gradient end, creating a soft, natural transition. |

## Tokens — Typography

### WaldenburgHF — Display and primary section headings — custom font lending a distinct, modern digital signature. · `--font-waldenburghf`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 28px, 32px, 48px
- **Line height:** 1.10
- **Letter spacing:** 0.01
- **Role:** Display and primary section headings — custom font lending a distinct, modern digital signature.

### Inter — All body text, navigation, buttons, and secondary headings — provides high readability and a clean, technical feel. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.10, 1.40, 1.43, 1.60
- **Letter spacing:** 0.01
- **Role:** All body text, navigation, buttons, and secondary headings — provides high readability and a clean, technical feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | 0.01px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.01px | `--text-body-sm` |
| body | 16px | 1.43 | 0.01px | `--text-body` |
| subheading | 18px | 1.6 | 0.01px | `--text-subheading` |
| heading | 28px | 1.1 | 0.01px | `--text-heading` |
| heading-lg | 32px | 1.1 | 0.01px | `--text-heading-lg` |
| display | 48px | 1.1 | 0.01px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 2px |
| buttons | 9999px |
| ctaCard | 30px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(16, 24, 40, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1304px
- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Secondary Action Button
**Role:** Filled button for secondary actions.

Background: Pale Mist (#f2f2f2), Text: Midnight Ink (#000000), Border: Ash Gray (#e5e5e5), Radius: 9999px, Padding: 0px 16px.

### Tertiary Action Button
**Role:** Outline button for less prominent actions.

Background: Cloud White (#ffffff), Text: Midnight Ink (#000000), Border: Ash Gray (#e5e5e5), Radius: 9999px, Padding: 0px 12px.

### Ghost Button
**Role:** Minimal button for subtle interactions.

Background: transparent (rgba(0,0,0,0)), Text: Midnight Ink (#000000), Border: Ash Gray (#e5e5e5), Radius: 9999px, Padding: 2px 12px.

### Transparent Card
**Role:** Card with no background, for organizing content.

Background: transparent (rgba(0,0,0,0)), Border: none, Radius: 0px, Shadow: none, Padding: 0px.

### Rounded Information Card
**Role:** Card for containing distinct information blocks.

Background: transparent (rgba(0,0,0,0)), Border: none, Radius: 16px, Shadow: none, Padding: 0px 64px.

### Navigation Link
**Role:** Top navigation item.

Text: Midnight Ink (#000000), Underline: none, Font: Inter, Weight: 400, Size: 16px, Line Height: 1.43.

### Hero Headline
**Role:** Primary page title.

Text: Midnight Ink (#000000), Font: WaldenburgHF, Weight: 700, Size: 48px, Line Height: 1.1, Letter Spacing: 0.01em.

### QR Code Callout
**Role:** Promotional card for app download.

Background: Cloud White (#ffffff), Border: 1px solid Ash Gray (#e5e5e5), Radius: 16px, Padding: 20px, Shadow: rgba(16, 24, 40, 0.05) 0px 1px 2px 0px.

## Do's and Don'ts

### Do
- Use Cloud White (#ffffff) as the primary page background to maintain an open and airy aesthetic.
- Apply Midnight Ink (#000000) for all primary text elements and main CTA backgrounds for maximum contrast.
- Round all interactive buttons and navigation elements with a 9999px radius for visual softness and approachability.
- Utilize WaldenburgHF font for headlines (28px, 32px, 48px) at weight 700 to establish a bold yet refined presence.
- Employ Ash Gray (#e5e5e5) for thin borders and dividers to structure content subtly.
- Maintain generous vertical spacing between sections, primarily using the 40px `sectionGap` token.
- Group related information within cards with a 16px border-radius and minimal or no background (#ffffff or transparent).

### Don't
- Avoid strong, saturated colors; stick to the neutral palette and only use subtle chromatic hints for atmosphere.
- Do not use sharp corners for interactive elements; buttons and navigation should always be fully rounded (9999px).
- Refrain from heavy shadows; subtle shadows like `rgba(16, 24, 40, 0.05) 0px 1px 2px 0px` are acceptable only for floating elements.
- Do not vary from the Inter font family for body text, navigation, and secondary UI elements to maintain consistency.
- Avoid tight element spacing; ensure a minimum `elementGap` of 8px to preserve an uncluttered layout.
- Do not use dark backgrounds for main content sections; the system is designed for a light theme with ample whitespace.

## Imagery

The visual language is dominantly product-focused, featuring tight crops of mobile device screens showcasing the ElevenReader app UI. These are typically contained and isolated, without decorative masks or overlapping elements. Photography appears absent. Illustrations consist of 2D, filled icons with a light stroke weight, used primarily for functional purposes (e.g., QR code). Abstract gradients occasionally provide decorative background context, but they are soft and desaturated, never overwhelming the UI. The density is text-dominant, with imagery serving to explain or demonstrate product features rather than create atmosphere.

## Layout

The page adheres to a max-width contained model (1304px), with content centered within this boundary. The hero section is a full-width presentation featuring a bold, centered headline and subtext, often laid over a subtle background gradient. Section rhythm is predominantly defined by consistent vertical spacing, creating spacious breathing room between content blocks. Content arrangement frequently uses horizontally aligned elements, such as multi-column layouts for features or news articles. Navigation is a sticky top bar, containing branding, main links, and clear calls-to-action on the right. Sidebars are not present, maintaining a clean, linear flow.

## Agent Prompt Guide

Quick Color Reference:
- Text: Midnight Ink (#000000)
- Background: Cloud White (#ffffff)
- CTA Primary: Midnight Ink (#000000)
- Border: Ash Gray (#e5e5e5)
- Secondary BG: Pale Mist (#f2f2f2)

Example Component Prompts:
1. Create a primary call-to-action button: background Midnight Ink (#000000), text Cloud White (#ffffff), border Ash Gray (#e5e5e5), radius 9999px, padding 0px 16px, with text 'Start Free Trial'.
2. Design a section headline: text Midnight Ink (#000000), font WaldenburgHF, weight 700, size 48px, line height 1.1, letter spacing 0.01em, with content 'Listen to anything'.
3. Generate a secondary button: background Pale Mist (#f2f2f2), text Midnight Ink (#000000), border Ash Gray (#e5e5e5), radius 9999px, padding 0px 16px, with text 'Try It Now'.
4. Create a standard body paragraph: text Midnight Ink (#000000), font Inter, weight 400, size 16px, line height 1.43, letter spacing 0.01em.
5. Design an information card with 16px radius: background transparent (rgba(0,0,0,0)), border none, padding 0px 64px.

## Similar Brands

- **OpenAI** — Shares a clean, minimalist aesthetic with high contrast text on light backgrounds and a focus on clarity for AI products.
- **Readwise** — Features a similar spacious, text-dominant layout with subtle interactive cues and full-round buttons for primary actions.
- **Amplitude** — Employs a professional, white-space heavy design with clear typography and restrained use of color, often applying soft gradients for atmospheric effect.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #e5e5e5;
  --color-pale-mist: #f2f2f2;
  --color-faded-sky: #f2f5fc;
  --color-steel-gray: #767676;
  --color-charcoal-haze: #6e6e6;
  --color-muted-lavender: #c8d5f4;
  --color-verdant-aura: #243f2b;
  --gradient-verdant-aura: radial-gradient(50% 50%, rgb(36, 63, 43) 0%, rgb(66, 141, 116) 54%, rgb(165, 177, 221) 78.5%, rgb(236, 230, 244) 99%);
  --color-forest-dew: #c6e7d6;
  --gradient-forest-dew: linear-gradient(rgb(255, 255, 255) 6.04%, rgb(198, 231, 214) 59.83%);

  /* Typography — Font Families */
  --font-waldenburghf: 'WaldenburgHF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --tracking-subheading: 0.01px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: 0.01px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.01px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: 0.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-200: 200px;

  /* Layout */
  --page-max-width: 1304px;
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 30px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 2px;
  --radius-buttons: 9999px;
  --radius-ctacard: 30px;

  /* Shadows */
  --shadow-subtle: rgba(16, 24, 40, 0.05) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #e5e5e5;
  --color-pale-mist: #f2f2f2;
  --color-faded-sky: #f2f5fc;
  --color-steel-gray: #767676;
  --color-charcoal-haze: #6e6e6;
  --color-muted-lavender: #c8d5f4;
  --color-verdant-aura: #243f2b;
  --color-forest-dew: #c6e7d6;

  /* Typography */
  --font-waldenburghf: 'WaldenburgHF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --tracking-subheading: 0.01px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: 0.01px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.01px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: 0.01px;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 30px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(16, 24, 40, 0.05) 0px 1px 2px 0px;
}
```
