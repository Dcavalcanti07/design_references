# Fey — Style Reference
> Deep-space observatory control panel. Functionality, precision, and high-contrast data visualization on a near-black canvas.

**Theme:** dark

This design system evokes a sense of focused intelligence, like a deep-space observatory on a moonless night. Its near-black backgrounds provide a canvas for crisp white text and subtle, precise data visualizations. The deliberate restraint in chromatic color, limited to a single vivid blue for interaction and a warm orange for highlighting, creates a high-contrast experience where functionality takes aesthetic precedence. Fine typographical details and varying shades of dark gray give depth to the UI elements, preventing visual fatigue inherent in purely flat dark interfaces.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0b0b0b` | `--color-midnight-ink` | Major surface backgrounds, card bases. |
| Obsidian Deep | `#131313` | `--color-obsidian-deep` | Elevated card backgrounds, modal backdrops, adding subtle surface differentiation. |
| Coal Dust | `#191919` | `--color-coal-dust` | Accent backgrounds, subtle dividers. |
| Slate Text | `#868f97` | `--color-slate-text` | Secondary body text, disabled states, iconography. |
| Ash Gray | `#999999` | `--color-ash-gray` | Tertiary text, subtle descriptions. |
| Silver Accents | `#cccccc` | `--color-silver-accents` | Subtle interactive elements, subtle outlines. |
| Light Smoke | `#e6e6e6` | `--color-light-smoke` | Near-white elements in dark mode, button text for dark buttons. |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text, prominent iconography, active states, key data readouts. |
| Cosmic Blue | `#479ffa` | `--color-cosmic-blue` | Interactive elements, active navigation items, primary calls to action — signifying state changes and focus. |
| Solar Flare | `#ffa16c` | `--color-solar-flare` | Prominent headings and highlights, drawing immediate attention to key information without being intrusive. |
| Emerald Profit | `#4ebe96` | `--color-emerald-profit` | Positive data indicators, success states. |
| Warn Gradient 1 | `linear-gradient(97.13deg, rgb(255, 161, 108) 8.47%, rgb(85, 27, 16) 108.41%)` | `--color-warn-gradient-1` | Decorative gradient often used for feature highlights. |
| Cool Gradient 1 | `linear-gradient(96.44deg, rgb(182, 214, 255) 6.12%, rgb(57, 63, 86) 110.28%)` | `--color-cool-gradient-1` | Decorative gradient, often paired with data visualizations or abstract elements. |
| Vibrant Gradient 1 | `linear-gradient(96.44deg, rgb(214, 254, 81) 6.12%, rgb(88, 81, 11) 110.28%)` | `--color-vibrant-gradient-1` | Decorative gradient, suggesting energy and growth. |

## Tokens — Typography

### calibre — The primary typeface for all textual content. Its clean, slightly technical geometry is chosen for data legibility in financial contexts and its modern character. Varied weights ensure clear hierarchy from high-impact headlines to detailed data tables. · `--font-calibre`
- **Substitute:** Inter, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 18px, 24px, 26px, 48px, 54px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.30, 1.32, 1.36, 1.40, 1.50, 1.58
- **Letter spacing:** -0.08em, -0.08em, -0.053em
- **Role:** The primary typeface for all textual content. Its clean, slightly technical geometry is chosen for data legibility in financial contexts and its modern character. Varied weights ensure clear hierarchy from high-impact headlines to detailed data tables.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.36 | — | `--text-body` |
| heading-sm | 18px | 1.25 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.053px | `--text-heading` |
| heading-lg | 26px | 1.1 | -0.053px | `--text-heading-lg` |
| display | 48px | 1 | -0.08px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 42 | 42px | `--spacing-42` |
| 103 | 103px | `--spacing-103` |
| 190 | 190px | `--spacing-190` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| general | 10px |
| input-sm | 6px |
| buttons-pill | 99px |
| buttons-square | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.8) 0px 0px 44px 0px` | `--shadow-xl` |
| subtle | `rgba(0, 0, 0, 0.85) 0px 1px 0px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1220px

## Components

### Primary Navigation Link
**Role:** Interactive element

Text only, Pure White (#ffffff) on hover, otherwise Slate Text (#868f97). Uses Calibre 14px weight 400.

### Navigation Button - Ghost
**Role:** Interactive element

Circular button with 50% border radius. Background transparent, border #ffffff, text Pure White (#ffffff). On hover, background rgba(255, 255, 255, 0.08). Used for quick actions in nav.

### Navigation Button - Filled
**Role:** Interactive element

Pill-shaped button with 99px border radius. Background Light Smoke (#e6e6e6), text Black (#000000). Padding 7px vertical, 16px horizontal. Used for primary CTAs in nav.

### Notification Bubble Button
**Role:** System feedback

Rounded rectangular button with 6px border radius. Background rgba(255, 255, 255, 0.05). Border bottom rgba(255, 255, 255, 0.1). Text Light Smoke (#e6e6e6). Padding 3.75px vertical, 8-10px horizontal. Shadow: rgba(0, 0, 0, 0.85) 0px 1px 0px 0px. Used for compact alerts.

### App Preview Card
**Role:** Content display

Background Obsidian Deep (#131313). Border radius 16px. Shadow: Rgba(0, 0, 0, 0.8) 0px 0px 44px 0px. Used for displaying UI previews effectively with elevation.

### Pill Accent Tag
**Role:** Categorization/state

Pill-shaped with 99px border radius. Background transparent, text Light Smoke (#e6e6e6) or Emerald Profit (#4ebe96). Calibre 12px weight 400. Used for labels like 'Buy', 'Sell', 'Gainers', 'Losers'.

### Profile Avatar
**Role:** User identification

Circular graphic with 50px border-radius, often containing a small image. Used for user or entity representation in lists.

## Do's and Don'ts

### Do
- Use Midnight Ink (#0b0b0b) for primary page backgrounds to establish the dark theme.
- Apply Calibre font family with weight 400 for body text and 600 for prominent subheadings.
- Employ Cosmic Blue (#479ffa) exclusively for interactive elements and active states.
- Utilize Solar Flare (#ffa16c) for decorative headings and key value highlights.
- Maintain a clear visual hierarchy by differentiating surfaces with Obsidian Deep (#131313) for elevated elements on Midnight Ink (#0b0b0b) backgrounds.
- Apply 99px border radius for all primary calls-to-action buttons for a distinct pill shape.
- Space elements using multiples of 4px and 8px, reserving larger increments for section gaps (900-1100px) and card padding (18px vertical, 20px horizontal).

### Don't
- Do not use chromatic colors other than Cosmic Blue (#479ffa) or Solar Flare (#ffa16c) for branding or interactive elements.
- Avoid using drop shadows on elements that are not meant to signify elevation, like primary page backgrounds.
- Do not use border radii smaller than 6px for interactive elements; for cards and larger containers, use 16px.
- Never lighten text color for emphasis in a dark theme; rely on Pure White (#ffffff) for primary text and Light Smoke (#e6e6e6) or Slate Text (#868f97) for secondary/tertiary.
- Avoid dense information blocks without sufficient elementGap (min 4px, avg 8-20px) to maintain legibility.

## Elevation

- **App Preview Card:** `rgba(0, 0, 0, 0.8) 0px 0px 44px 0px`
- **Notification Bubble Button:** `rgba(0, 0, 0, 0.85) 0px 1px 0px 0px`

## Imagery

The visual language focuses on a mix of product screenshots and abstract, moody photography. Product screenshots are contained within device mockups (laptops, possibly tablets) and showcase the UI in context, often with a slight perspective to imply depth. Photography is dark and atmospheric, focusing on solitary figures or close-ups, often with obscured faces, suggesting introspection or focused work. Imagery serves to establish mood and showcase the product's interface rather than being purely decorative. Icons are mono-color and outline-based, or filled and simple, reinforcing the clean, functional aesthetic.

## Layout

The page primarily uses a max-width contained layout of 1220px, with content centered. The hero section is full-bleed, featuring a large, dark visual with a prominent centered headline and descriptive text. Subsequent sections alternate between full-bleed dark backgrounds and slightly lighter dark gray backgrounds (Obsidian Deep) to create visual rhythm. Content within sections often employs a prominent left-aligned headline followed by a flexible grid or alternating text-left/image-right (or product screenshot) arrangements. Card grids are used for features, showcasing clear divisions. Vertical spacing between sections is generous (900-1100px), contributing to a spacious feel despite the information density.

## Agent Prompt Guide

### Quick Color Reference
- Text: #ffffff (Pure White)
- Background: #0b0b0b (Midnight Ink)
- CTA: #e6e6e6 (Light Smoke) with #000000 text
- Accent: #479ffa (Cosmic Blue)
- Elevated Surface: #131313 (Obsidian Deep)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Full-bleed background #0b0b0b. Centered headline 'Make better investments.' using Calibre 54px weight 700 letterSpacing -0.08em #ffffff. Subtext 'Explore a new era of effortless financial research at your fingertips.' using Calibre 18px weight 400 #868f97. Include a 'Learn more' button: background #e6e6e6, text #000000, 99px border radius, 7px 16px padding.
2. **Generate a Feature Card:** Background #131313, 16px border radius, padding 18px 20px. Headline 'Morning recap' using Calibre 16px weight 600 #ffffff. Body text 'Trump's renewed tariff push is shaking markets...' using Calibre 14px weight 400 #868f97. Add an inactive ghost button in the top right, 50% border radius, background rgba(0,0,0,0), border #ffffff, text #ffffff.
3. **Design a Navigation Bar:** Background #0b0b0b. Left-aligned brand logo (use a placeholder icon, e.g., square). Right-aligned menu items: 'Features', 'Pricing', 'Updates', 'Students', 'App' (Calibre 14px weight 400 #868f97, #ffffff on hover/active). Include a 'Learn more' button: Background #e6e6e6, text #000000, 99px border radius, 7px 16px padding.
4. **Create a Pill-shaped Tag:** Background transparent, border #ffa16c (Solar Flare). Text 'Buy' (Calibre 12px weight 500 #ffa16c), 99px border radius. Padding 4px 8px. Simulate for a stock transaction list.

## Similar Brands

- **Linear** — Dark-mode UI with sharp edges, restrained accent colors, and strong typographic hierarchy for productivity tools.
- **Raycast** — Focus on command-line aesthetic translated into a sleek, dark-themed UI for developer tools, emphasizing performance.
- **Superhuman** — High-contrast dark theme, meticulous attention to typography, and minimal chromatic elements for an efficiency-focused application.
- **Revolut (dark mode)** — Financial app with a dark-mode interface, emphasizing data visualization and a clean, modern aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0b0b0b;
  --color-obsidian-deep: #131313;
  --color-coal-dust: #191919;
  --color-slate-text: #868f97;
  --color-ash-gray: #999999;
  --color-silver-accents: #cccccc;
  --color-light-smoke: #e6e6e6;
  --color-pure-white: #ffffff;
  --color-cosmic-blue: #479ffa;
  --color-solar-flare: #ffa16c;
  --color-emerald-profit: #4ebe96;
  --color-warn-gradient-1: #ffa16c;
  --gradient-warn-gradient-1: linear-gradient(97.13deg, rgb(255, 161, 108) 8.47%, rgb(85, 27, 16) 108.41%);
  --color-cool-gradient-1: #b6d6ff;
  --gradient-cool-gradient-1: linear-gradient(96.44deg, rgb(182, 214, 255) 6.12%, rgb(57, 63, 86) 110.28%);
  --color-vibrant-gradient-1: #d6fe51;
  --gradient-vibrant-gradient-1: linear-gradient(96.44deg, rgb(214, 254, 81) 6.12%, rgb(88, 81, 11) 110.28%);

  /* Typography — Font Families */
  --font-calibre: 'calibre', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.36;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.053px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.053px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-103: 103px;
  --spacing-190: 190px;

  /* Layout */
  --page-max-width: 1220px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-xl: 13.9806px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 275px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-general: 10px;
  --radius-input-sm: 6px;
  --radius-buttons-pill: 99px;
  --radius-buttons-square: 6px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.8) 0px 0px 44px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.85) 0px 1px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0b0b0b;
  --color-obsidian-deep: #131313;
  --color-coal-dust: #191919;
  --color-slate-text: #868f97;
  --color-ash-gray: #999999;
  --color-silver-accents: #cccccc;
  --color-light-smoke: #e6e6e6;
  --color-pure-white: #ffffff;
  --color-cosmic-blue: #479ffa;
  --color-solar-flare: #ffa16c;
  --color-emerald-profit: #4ebe96;
  --color-warn-gradient-1: #ffa16c;
  --color-cool-gradient-1: #b6d6ff;
  --color-vibrant-gradient-1: #d6fe51;

  /* Typography */
  --font-calibre: 'calibre', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.36;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.053px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.053px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-103: 103px;
  --spacing-190: 190px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-xl: 13.9806px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 275px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.8) 0px 0px 44px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.85) 0px 1px 0px 0px;
}
```
