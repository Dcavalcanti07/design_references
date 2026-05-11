# Andercore — Style Reference
> Dark control panel, sharp red accent

**Theme:** dark

Andercore employs a stark, high-contrast visual language set against a deep, near-black canvas, evocative of a digital control panel. A single vivid red punctates the dark background, highlighting primary actions and brand elements with urgent precision. Typography is compact and functional, prioritizing clarity and directness. Components are defined by sharp edges, minimal borders, and a focus on essential functionality, often appearing as ghost elements or solid blocks of color, reinforcing a sense of efficiency and industrial utility.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#0b0405` | `--color-midnight-void` | Primary background for pages and main content sections — creates a deep, dark canvas |
| Ghostly Gray | `#382e30` | `--color-ghostly-gray` | Subtle borders, dividers, and background elements, providing muted separation on dark surfaces |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text, prominent UI elements, and button backgrounds for ghost/secondary actions — high contrast against dark backgrounds |
| Crimson Action | `#e32735` | `--color-crimson-action` | Primary call-to-action buttons, active navigation indicators, and key brand highlights— cuts through deep neutrals |
| Slate Text | `#858182` | `--color-slate-text` | Secondary text, descriptive labels, and badge text— provides softer contrast for less critical information |
| Solid Black | `#000000` | `--color-solid-black` | Used for some decorative fills and as a very dark shadow tint, enhancing depth without adding color |
| Dark Shroud | `#150e0f` | `--color-dark-shroud` | Used for very subtle background variations, appearing almost indistinguishable from Midnight Void but providing slight differentiation |

## Tokens — Typography

### Archivo — Primary typeface for all headings, body text, navigation, and most UI elements. Its strong, sans-serif structure maintains clarity even at small sizes and high contrast ratios. The tight 1.1 line height for large sizes and -0.020em letter spacing create a compact, efficient visual style. · `--font-archivo`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 24px, 40px, 56px
- **Line height:** 1.10, 1.20, 1.50
- **Letter spacing:** -0.02
- **Role:** Primary typeface for all headings, body text, navigation, and most UI elements. Its strong, sans-serif structure maintains clarity even at small sizes and high contrast ratios. The tight 1.1 line height for large sizes and -0.020em letter spacing create a compact, efficient visual style.

### Space Mono — Used for badges and specialized alphanumeric displays, providing a technical, monospaced aesthetic that suggests code or data. · `--font-space-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.50
- **Role:** Used for badges and specialized alphanumeric displays, providing a technical, monospaced aesthetic that suggests code or data.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 40px | 1.1 | -0.8px | `--text-heading` |
| display | 56px | 1.1 | -1.12px | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 4px |
| default | 4px |

### Layout

- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled button for critical calls-to-action.

Background: Crimson Action (#e32735). Text: Pure White (#ffffff). Padding: 12px vertical, 24px horizontal. Border radius: 4px. Text uses Archivo weight 500.

### Secondary Ghost Button
**Role:** Outlined or low-emphasis button for secondary actions.

Background: rgba(255, 255, 255, 0.2). Text: Pure White (#ffffff). Border: rgba(255, 255, 255, 0.1). Padding: 12px vertical, 24px horizontal. Border radius: 4px. Text uses Archivo weight 500.

### Tertiary Link Button
**Role:** Text-based button for navigation or tertiary actions.

Background: transparent. Text: rgba(255, 255, 255, 0.8). Border radius: 0px. Padding: 8px vertical, 16px horizontal. No visual border. Text uses Archivo weight 400.

### Navigation Link Button
**Role:** Navigation item styled as a button for site header.

Background: Dark Shroud (#150e0f). Text: Pure White (#ffffff). Padding: 16px vertical, 32px horizontal. Border radius: 0px. Text uses Archivo.

### Content Card
**Role:** Container for information without visual separation or shadows.

Background: transparent. No border or border-radius (0px). Padding: 0px top, 32px horizontal, 48px bottom. Content layout within cards relies on internal spacing.

### Technical Badge
**Role:** Indicator for categories or specific labels.

Background: transparent. Text: Slate Text (#858182). No border, radius, or padding. Text uses Space Mono weight 400 at 12px.

## Do's and Don'ts

### Do
- Prioritize a dark, immersive background using Midnight Void (#0b0405) for all primary canvases.
- Use Crimson Action (#e32735) exclusively for primary call-to-action elements to create decisive urgency.
- Maintain high contrast for all critical text and interactive elements by using Pure White (#ffffff) against dark backgrounds.
- Apply Archivo at -0.02em letter spacing for headlines and body text to create a compact, information-dense appearance.
- Utilize a consistent 4px border radius for all interactive buttons and navigation containers, while most content areas remain sharp-edged (0px radius).
- Define clear visual hierarchy through color contrast (white text on dark background, red accents) rather than elevation or shadows.
- Employ the 24px `elementGap` for horizontal and vertical spacing between most UI elements, establishing a comfortable density.

### Don't
- Avoid light backgrounds; the system is built for a dark interface, and light themes will contradict the brand's atmosphere.
- Do not introduce additional bright or saturated colors beyond Crimson Action; this dilutes the impact of the primary accent.
- Refrain from using drop shadows or complex elevation; the system's focus is on flat, high-contrast surfaces.
- Do not vary border radii arbitrarily; adhere to 4px for interactive elements and 0px for content cards and sections.
- Avoid decorative imagery that clashes with the technical, industrial aesthetic, like highly organic shapes or soft textures.
- Do not deviate from the specified typefaces and their distinct letter spacing; it is essential for the brand's precise communication.
- Do not use generic gray shades that disrupt the specific neutral scale or the stark contrast pairings.

## Imagery

The visual language focuses on a mix of product photography (large machinery, trucks) and staged human interaction with technology (person using a phone). Photography is often dark and desaturated, overlaid by a strong black tint, contributing to the 'control panel' aesthetic. There is minimal use of abstract graphics or illustrations, favoring real-world context for industrial trade. Small icons are simple, often monochrome or filled, reinforcing functional clarity.

## Layout

The page primarily uses a full-bleed layout with content centered within implied maximum width boundaries. The hero section features a dark, tinted full-bleed image with a prominent, centered headline and calls to action. Subsequent sections alternate between deep dark backgrounds, employing distinct vertical spacing to segment information. Content organization frequently uses alternating text-left/text-right patterns for feature sections, alongside multi-column grid layouts for displaying challenges or benefits. Navigation is a sticky top bar with clearly defined interactive elements.

## Agent Prompt Guide

### Quick Color Reference
text: Pure White (#ffffff)
background: Midnight Void (#0b0405)
border: Ghostly Gray (#382e30)
accent: Crimson Action (#e32735)
primary action: #e32735 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Midnight Void (#0b0405) background. Headline 'AI-powered industrial trade' uses Archivo 56px weight 500, Pure White (#ffffff), letter-spacing -1.12px, line-height 1.1. Subtext Archivo 16px weight 400, Pure White (#ffffff), line-height 1.5. Below are two buttons side-by-side. The first is a Primary Action Button: Crimson Action (#e32735) background, Pure White (#ffffff) text, 12px vertical padding, 24px horizontal padding, 4px radius, using Archivo 500. The second button is a Secondary Ghost Button: rgba(255, 255, 255, 0.2) background, Pure White (#ffffff) text, rgba(255, 255, 255, 0.1) border, 12px vertical padding, 24px horizontal padding, 4px radius, using Archivo 500.
2. Design a feature block: Dark Shroud (#150e0f) background. Heading 'The challenge today' uses Archivo 40px weight 500, Pure White (#ffffff), letter-spacing -0.8px, line-height 1.1. Below are three columns. Each column contains a Technical Badge: Space Mono 12px weight 400, Slate Text (#858182). Below the badge, a subheading uses Archivo 24px weight 500, Pure White (#ffffff), letter-spacing -0.02em, line-height 1.2. Body text in Archivo 14px weight 400, Pure White (#ffffff), line-height 1.5.
3. Create a navigation bar: Midnight Void (#0b0405) background. Left-aligned logo (placeholder). Right-aligned links 'About us' and 'Career' use Archivo 14px weight 400, Pure White (#ffffff), no border. Followed by a Secondary Ghost Button 'Login' (rgba(255, 255, 255, 0.2) background, Pure White (#ffffff) text, rgba(255, 255, 255, 0.1) border, 12px vertical padding, 24px horizontal padding, 4px radius, using Archivo 500). Then a Primary Action Button 'Sign-up as buyer' (Crimson Action (#e32735) background, Pure White (#ffffff) text, 12px vertical padding, 24px horizontal padding, 4px radius, using Archivo 500).

## Similar Brands

- **Palantir** — Dark UI with high-contrast elements, focus on data, and a limited, impactful accent color.
- **Stripe (dark mode)** — Clean, functional typography on a dark background with a strategic use of a single bright accent for actions.
- **Linear** — Minimalist dark interface with sharp edges, strong typography, and a prominent brand color for interactivity.
- **Vercel** — High-contrast dark themes with crisp typography, restrained use of color, and a functional, engineering-focused aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #0b0405;
  --color-ghostly-gray: #382e30;
  --color-pure-white: #ffffff;
  --color-crimson-action: #e32735;
  --color-slate-text: #858182;
  --color-solid-black: #000000;
  --color-dark-shroud: #150e0f;

  /* Typography — Font Families */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 4px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #0b0405;
  --color-ghostly-gray: #382e30;
  --color-pure-white: #ffffff;
  --color-crimson-action: #e32735;
  --color-slate-text: #858182;
  --color-solid-black: #000000;
  --color-dark-shroud: #150e0f;

  /* Typography */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
}
```
