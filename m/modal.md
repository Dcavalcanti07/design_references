# Modal — Style Reference
> Neon data grid

**Theme:** dark

Modal orchestrates a 'dark mode command center' aesthetic, contrasting deep neutrals with a vibrant, almost neon green. This system emphasizes functionality, with slim, understated UI elements that allow content and data to take center stage. The visual style is rooted in code aesthetics, with fixed-width typography, subtle interactive borders, and glowing digital accents that communicate innovation and precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#000000` | `--color-midnight-graphite` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ash Canvas | `#212525` | `--color-ash-canvas` | Navigation backgrounds, elevated subtle surfaces |
| Code Base | `#3e4a3c` | `--color-code-base` | Muted text in cards, button borders for ghost buttons, secondary icon strokes |
| Mist Border | `#485346` | `--color-mist-border` | Subtle card and link borders, dividers in darker contexts |
| Faded Stone | `#677d64` | `--color-faded-stone` | Muted body text in light sections, soft secondary borders |
| Steel Gray | `#697368` | `--color-steel-gray` | Labels for category groupings, secondary text in components |
| Pale Sage | `#859085` | `--color-pale-sage` | Subtle outlined button borders, minor decorative element borders |
| Moss Detail | `#859984` | `--color-moss-detail` | Link borders and text in body content, secondary button text |
| Cloud Whisper | `#def0dd` | `--color-cloud-whisper` | Card backgrounds in lighter sections, subtle background wash |
| Vivid Apple | `#7fee64` | `--color-vivid-apple` | Primary action button background, active navigation indicators, key interactive element borders |
| System Green | `#c8f9b6` | `--color-system-green` | Headline text in light sections, secondary accent color for highlighted text or borders |
| Digital Glow | `#ddffdc` | `--color-digital-glow` | Primary text on dark backgrounds, ghost button text, link highlights, decorative icon fills |
| Light Aura | `#aed2a4` | `--color-light-aura` | Subtle text accents, secondary text in hero section |
| Snow Peak | `#ffffff` | `--color-snow-peak` | Text on dark backgrounds, primary icon fills, contrast elements |

## Tokens — Typography

### Inter Variable — Body copy, navigation links, button labels, and general UI text. The variable font provides precise control over visual density, enhancing readability especially at smaller sizes. · `--font-inter-variable`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.38, 1.43, 1.50
- **Letter spacing:** 1.2, -0.31, -0.354
- **OpenType features:** `'cv11'`
- **Role:** Body copy, navigation links, button labels, and general UI text. The variable font provides precise control over visual density, enhancing readability especially at smaller sizes.

### Goga — Primary headings and display text. Its distinctive character with specific stylistic alternates ('ss01') is a core part of the brand's visual identity, suggesting a technical yet bold presence. The tightly tracked large sizes create a commanding yet condensed visual. · `--font-goga`
- **Substitute:** Georgia, serif
- **Weights:** 400, 500
- **Sizes:** 20px, 24px, 40px, 54px, 60px, 64px
- **Line height:** 1.00, 1.10, 1.30, 1.33, 1.40, 1.50
- **Letter spacing:** -0.87, -0.81, -0.9, -0.96
- **OpenType features:** `'ss01'`
- **Role:** Primary headings and display text. Its distinctive character with specific stylistic alternates ('ss01') is a core part of the brand's visual identity, suggesting a technical yet bold presence. The tightly tracked large sizes create a commanding yet condensed visual.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | 1.2px | `--text-caption` |
| body | 14px | 1.38 | -0.31px | `--text-body` |
| body-lg | 16px | 1.43 | -0.35px | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 40px | 1.4 | -0.87px | `--text-heading-lg` |
| display-sm | 54px | 1.1 | -0.81px | `--text-display-sm` |
| display | 60px | 1 | -0.9px | `--text-display` |
| display-lg | 64px | 1 | -0.96px | `--text-display-lg` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 8px |
| buttons | 4px |
| tags_pills | 9999px |
| containers-rounded | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 56px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Main call to action

Filled button with a vibrant green background `Vivid Apple` (#7fee64), `Midnight Graphite` (#000000) text, `4px` radius, `8px` vertical and `20px` horizontal padding. The stark contrast makes it highly visible.

### Ghost Button
**Role:** Secondary action with low visual impact

Transparent background, `Digital Glow` (#ddffdc) text and `1px` border, `4px` radius, `8px` vertical and `20px` horizontal padding. Offers an alternative action without competing visually with the primary.

### Subtle Ghost Button
**Role:** Tertiary action or contextual link

Transparent background, muted `Code Base` (#3e4a3c) text and `1px` border, `4px` radius, `8px` vertical and `20px` horizontal padding. Used for less prominent actions.

### Minimal Link Button
**Role:** Text-only action within content

Transparent background, `Digital Glow` (#ddffdc) text, no border, `0px` radius, `0px` padding. Looks like a link but functions as a button.

### Section Card
**Role:** Content grouping within sections

Solid `Midnight Graphite` (#000000) background, no border, `0px` radius, inner content padding varies. Serves as a neutral data container.

### Customer Testimonial Card
**Role:** Elevated highlight for social proof

Transparent background, `16px` padding, no border, `0px` radius. Used for testimonials without a strong visual container.

### Pill Tag
**Role:** Categorization or status indicator

Semi-transparent border in `Pale Sage` (#859085), `Digital Glow` (#ddffdc) text, `9999px` radius for a pill shape, `4px` vertical padding and `12px` horizontal padding. Visually light and friendly.

## Do's and Don'ts

### Do
- Prioritize `Midnight Graphite` (#000000) for all main backgrounds to maintain a dark interface throughout.
- Use `Digital Glow` (#ddffdc) exclusively for primary text and active states on dark backgrounds, and `Midnight Graphite` (#000000) for primary text on light backgrounds, ensuring high contrast.
- Apply `Vivid Apple` (#7fee64) only for primary call-to-action buttons and key interactive elements to create focal points.
- Implement `Goga` for all headlines and `Inter Variable` for body copy and UI elements, adhering to their specified weights and letter spacing.
- Employ a `4px` radius for interactive buttons and `9999px` for pill-shaped elements, maintaining distinct corner treatments.
- Maintain `16px` as the standard element gap and `56px` for section spacing for consistent vertical rhythm.
- Use thin, `1px` borders with `Code Base` (#3e4a3c) or `Mist Border` (#485346) for subtle UI delineation rather than strong graphic containers.

### Don't
- Do not introduce additional saturated colors; restrict the palette to the specified greens and neutrals.
- Avoid using `Midnight Graphite` (#000000) for borders on dark backgrounds unless it's for an active or focus state.
- Do not vary `Goga`'s headline letter spacing and weights from the defined profile; its condensed appearance is signature.
- Never use large, decorative shadows; elevation should be minimal and come from a single, light source effect.
- Do not use box-shadows on cards; cards rely on background color changes or subtle borders for differentiation.
- Avoid full-bleed imagery that covers the entire viewport on principle sections; most imagery should be contained or subtly integrated.
- Do not use generic system fonts as substitutes if `Inter Variable` or `Goga` are not available; find substitutes that preserve the monospace or condensed display quality.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#000000` | Primary page background, providing a deep, dark foundation for all content. |
| 1 | Navigation Surface | `#212525` | Background for the main navigation bar, slightly elevated visually from the base canvas. |
| 2 | Light Panel | `#def0dd` | Background for specific content sections that require a lighter theme or contrast, such as community testimonials. |

## Agent Prompt Guide

Quick Color Reference:
- text: #ddffdc
- background: #000000
- border: #485346
- accent: #7fee64
- primary action: #7fee64 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #7fee64 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a feature section: `Midnight Graphite` (#000000) background. Heading 'Designed to help AI teams deploy faster.' using Goga 40px, weight 500, `System Green` (#c8f9b6), letter-spacing -0.87px. Body text 'Define everything in code, no YAML or config files.' using Inter Variable 16px, weight 400, `Digital Glow` (#ddffdc). A code block card with `Midnight Graphite` (#000000) background, `0px` radius, `16px` padding, `Code Base` (#3e4a3c) borders.
- Create a testimonial card: `Midnight Graphite` (#000000) background. Text (Inter Variable 16px, weight 400, `Digital Glow` (#ddffdc)). Author name (Inter Variable 14px, weight 600, `Digital Glow` (#ddffdc)). Profile image with `9999px` radius, 48px diameter. `16px` padding inside the card.

## Similar Brands

- **Vercel** — Shares a developer-focused dark mode UI with a vibrant accent color, concise text, and a strong emphasis on code and technology.
- **Cockroach Labs** — Uses dark themes and a technical aesthetic, with clear data visualizations and a precise, modern typographic hierarchy.
- **Hugging Face** — Similar focus on AI/ML tools, often employing dark interfaces with bright, functional accents and strong visual contrast for code and data.
- **Render** — Features a dark, clean developer-centric interface with bold typography and a clear separation of elements, often using a single strong accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-ash-canvas: #212525;
  --color-code-base: #3e4a3c;
  --color-mist-border: #485346;
  --color-faded-stone: #677d64;
  --color-steel-gray: #697368;
  --color-pale-sage: #859085;
  --color-moss-detail: #859984;
  --color-cloud-whisper: #def0dd;
  --color-vivid-apple: #7fee64;
  --color-system-green: #c8f9b6;
  --color-digital-glow: #ddffdc;
  --color-light-aura: #aed2a4;
  --color-snow-peak: #ffffff;

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-goga: 'Goga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 1.2px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.31px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.35px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.4;
  --tracking-heading-lg: -0.87px;
  --text-display-sm: 54px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.81px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.9px;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 56px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-links: 8px;
  --radius-buttons: 4px;
  --radius-tagspills: 9999px;
  --radius-containers-rounded: 16px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-navigation-surface: #212525;
  --surface-light-panel: #def0dd;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-ash-canvas: #212525;
  --color-code-base: #3e4a3c;
  --color-mist-border: #485346;
  --color-faded-stone: #677d64;
  --color-steel-gray: #697368;
  --color-pale-sage: #859085;
  --color-moss-detail: #859984;
  --color-cloud-whisper: #def0dd;
  --color-vivid-apple: #7fee64;
  --color-system-green: #c8f9b6;
  --color-digital-glow: #ddffdc;
  --color-light-aura: #aed2a4;
  --color-snow-peak: #ffffff;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-goga: 'Goga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 1.2px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.31px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.35px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.4;
  --tracking-heading-lg: -0.87px;
  --text-display-sm: 54px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.81px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.9px;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```
