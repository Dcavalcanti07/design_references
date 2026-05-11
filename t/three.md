# Three — Style Reference
> Midnight Command Center – essential tools illuminated against deep darkness.

**Theme:** dark

Three.Tools presents a 'midnight command center' aesthetic, designed for focused productivity. Its visual system prioritizes stark contrast and a tightly controlled dark palette punctuated by a single, vivid orange accent. Typography is compact and precise, maintaining readability on dark surfaces. Components are lightweight with subtly rounded edges, blending into the dark canvas, using minimal elevation to delineate functionality rather than decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#111111` | `--color-absolute-zero` | Primary page background, base surface for main content blocks |
| Obsidian Deep | `#181818` | `--color-obsidian-deep` | Secondary card and background surfaces, slightly elevated above the base |
| Charcoal Grey | `#343434` | `--color-charcoal-grey` | Tactile button backgrounds, subtle borders, and input elements |
| Cadet Grey | `#2b2a2a` | `--color-cadet-grey` | Footer background |
| Cloudburst | `#cacaca` | `--color-cloudburst` | Primary text on dark backgrounds, active states, and icon borders |
| Slate Mist | `#999999` | `--color-slate-mist` | Secondary text, muted headings, and list item borders |
| Pewter Light | `#8d8d8d` | `--color-pewter-light` | Subtle heading text color |
| Steel Gray | `#666666` | `--color-steel-gray` | Tertiary text, less prominent headings |
| Pure White | `#ffffff` | `--color-pure-white` | Input background, badges, and the lightest text for high contrast on dark |
| Ink Black | `#000000` | `--color-ink-black` | Input text, icon fills, and some badge borders |
| Blush Light | `#e9e6e6` | `--color-blush-light` | Subtle background for ghost buttons, decorative fills |
| Ember Glow | `#ff4300` | `--color-ember-glow` | Primary call-to-action buttons, interactive accents – providing a warm, vivid focus point |

## Tokens — Typography

### -apple-system — Primary typeface for all content elements, from body text to headlines, relying on weight and size to establish hierarchy. The default system font ensures fast loading and consistency on native platforms. Tightly tracked larger sizes enhance its crisp, digital feel. · `--font-apple-system`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 9px, 10px, 12px, 14px, 16px, 18px, 20px, 22px, 24px, 46px, 48px, 68px
- **Line height:** 1.00, 1.25
- **Letter spacing:** -0.008, -0.011, -0.015, -0.016, -0.025, -0.03, -0.056, -0.056, -0.056, -0.056, -0.056, -0.056
- **Role:** Primary typeface for all content elements, from body text to headlines, relying on weight and size to establish hierarchy. The default system font ensures fast loading and consistency on native platforms. Tightly tracked larger sizes enhance its crisp, digital feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading | 18px | 1.25 | -0.03px | `--text-heading` |
| heading-lg | 24px | 1.25 | -0.056px | `--text-heading-lg` |
| display | 68px | 1 | -0.056px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 76 | 76px | `--spacing-76` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| badges | 7px |
| inputs | 20px |
| buttons | 15px |
| buttonsCircular | 999px |

### Layout

- **Page max-width:** 1107px
- **Section gap:** 100px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Action Button
**Role:** Filled button indicating a significant call to action.

Background: Ember Glow (#ff4300), Text: Pure White (#ffffff), Border Radius: 16px. Minimal padding on text to maintain dense appearance. Example: 'Get Notified'.

### Neutral Action Button
**Role:** Filled button for secondary actions or navigation.

Background: Charcoal Grey (#343434), Text: Cloudburst (#cacaca), Border Radius: 999px (pill-shaped). Minimal padding. Example: 'Artboard'.

### Ghost Button
**Role:** Low-prominence button for less critical actions.

Background: transparent, Text: Cloudburst (#cacaca). No explicit border radius, blends with surrounding content. Example: 'Get access' in header.

### Feature Card
**Role:** Container for showcasing features or testimonials.

Background: Obsidian Deep (#181818) or Absolute Zero (#111111) or #111111, Border Radius: 20px or 24px. No shadow, flat appearance. Padding 20px (derived from elementGap and cardPadding rules).

### Text Input (White)
**Role:** Standard input field for user entry.

Background: Pure White (#ffffff), Text: Ink Black (#000000), Border Radius: 22px. Uses a solid white fill with black text for content-entry contrast. Example: 'Type your email...' field.

### Beta Badge
**Role:** Small informational tag.

Background: Pure White (#ffffff), Text: Ink Black (#000000), Border Radius: 7px. Padding: 1px vertical, 5px horizontal.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#111111) as the base background for most full-page sections to maintain the dark theme.
- Use Ember Glow (#ff4300) exclusively for primary calls to action, ensuring it stands out against the dark monochromatic palette.
- Apply -apple-system font family for all text, manipulating hierarchy through size and distinct letter-spacing values (e.g., larger sizes for tighter tracking).
- Utilize a 20px border-radius for cards and inputs to provide a consistent, subtle softness, reserving 999px for pill-shaped buttons.
- Maintain a comfortable density with element gaps of 20px between interface elements and 100px between major sections.
- Keep components flat with no box shadows; depth is conveyed through subtle changes in background color (e.g., Absolute Zero to Obsidian Deep).
- Ensure all interactive text, especially in ghost buttons, uses Cloudburst (#cacaca) against dark backgrounds for visibility.

### Don't
- Avoid using multiple chromatic colors; limit the palette rigidly to maintain the impactful Ember Glow accent.
- Do not introduce heavy shadows or gradients on component surfaces, as this contradicts the clean, flat aesthetic.
- Refrain from using excessively open letter-spacing for large headlines; larger sizes should have tighter tracking as defined.
- Do not deviate from the established border radii; maintain 20px for cards/inputs and 15px/999px for buttons.
- Avoid large hero images that break the dark, UI-focused atmosphere; abstract 3D elements or product shots are preferred.
- Do not use light theme elements unless explicitly part of a contained input component, as the site is predominantly dark.

## Imagery

Imagery is functional and abstract, focusing on 3D geometric shapes and product screenshots (browser extension UI). Photography or traditional illustrations are absent. When present, images are often contained within dark surfaces with rounded corners. Icons are typically filled or outlined, monochrome, and used sparingly for functionality. The overall density is text-dominant, with imagery serving as supportive, often animated, visual explanations or brand identity elements rather than primary content.

## Layout

The page primarily uses a max-width contained layout, centering content within an 1107px maximum width, though the initial hero section appears full-bleed. The hero features a large, centered headline over a dark background with an abstract 3D graphic. Sections typically maintain consistent vertical spacing (100px gap) and commonly feature a stacked, centered content arrangement or simple split sections. Card grids are used for showcasing features. Navigation is handled by a minimal top bar with ghost controls, staying fixed for quick access.

## Agent Prompt Guide

### Quick Color Reference
- text: #cacaca (Cloudburst)
- background: #111111 (Absolute Zero)
- border: #343434 (Charcoal Grey)
- accent: #ff4300 (Ember Glow)
- primary action: #ff4300 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #ff4300 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Obsidian Deep (#181818) background, 20px border-radius. Inside, a heading 'Inspect scenes.' using -apple-system, 18px, weight 700, Cloudburst (#cacaca), letter-spacing -0.030. Below, body text 'Get visibility into your graph.' using -apple-system, 14px, weight 700, Slate Mist (#999999), letter-spacing -0.016.

## Similar Brands

- **Framer** — Dark-mode UI with sharp typography, subtle surface variations, and compact component design for a developer audience.
- **Linear** — Focus on dark theme, strong functional typography, and minimal use of color for interaction points against a mostly monochromatic background.
- **Raycast** — Dark interface, command-line aesthetic, high contrast text, and compact UI elements without heavy shadows.
- **Superhuman** — Highly functional, dark-themed UI that prioritizes speed and efficiency, using clear typography and limited color for accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #111111;
  --color-obsidian-deep: #181818;
  --color-charcoal-grey: #343434;
  --color-cadet-grey: #2b2a2a;
  --color-cloudburst: #cacaca;
  --color-slate-mist: #999999;
  --color-pewter-light: #8d8d8d;
  --color-steel-gray: #666666;
  --color-pure-white: #ffffff;
  --color-ink-black: #000000;
  --color-blush-light: #e9e6e6;
  --color-ember-glow: #ff4300;

  /* Typography — Font Families */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading: 18px;
  --leading-heading: 1.25;
  --tracking-heading: -0.03px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.056px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.056px;

  /* Typography — Weights */
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1107px;
  --section-gap: 100px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 999px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-badges: 7px;
  --radius-inputs: 20px;
  --radius-buttons: 15px;
  --radius-buttonscircular: 999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #111111;
  --color-obsidian-deep: #181818;
  --color-charcoal-grey: #343434;
  --color-cadet-grey: #2b2a2a;
  --color-cloudburst: #cacaca;
  --color-slate-mist: #999999;
  --color-pewter-light: #8d8d8d;
  --color-steel-gray: #666666;
  --color-pure-white: #ffffff;
  --color-ink-black: #000000;
  --color-blush-light: #e9e6e6;
  --color-ember-glow: #ff4300;

  /* Typography */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading: 18px;
  --leading-heading: 1.25;
  --tracking-heading: -0.03px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.056px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.056px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 999px;
}
```
