# Lazy — Style Reference
> Subdued command center

**Theme:** dark

Lazy operates with a 'stealth dark mode' aesthetic, prioritizing content through deep, muted surfaces and delicate typography. A subtle play of light against dark is achieved through soft, localized gradients and sharp, clean borders. The overall impression is one of quiet efficiency and focused productivity, where UI elements recede until interaction, brought to life by crisp text and carefully applied elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0a0a0a` | `--color-midnight-ink` | Deepest surface background, text on light elements, subtle shadows |
| Carbon Gray | `#26272c` | `--color-carbon-gray` | Primary page background, card backgrounds |
| Slate Surface | `#1a1b1f` | `--color-slate-surface` | Elevated card backgrounds, input fields |
| Ash Gray | `#3b3c3e` | `--color-ash-gray` | Subtle elevated surface (e.g., input active state) |
| Ghost Border | `#8a8c93` | `--color-ghost-border` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Whisper Gray | `#62646a` | `--color-whisper-gray` | Secondary text, link borders, icon strokes |
| Muted Text | `#535355` | `--color-muted-text` | Placeholder text, very subtle body text |
| Callout Text | `#e0e0e0` | `--color-callout-text` | Prominent body text, card content text |
| Pure White | `#ffffff` | `--color-pure-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Cloud Burst Gradient Primary | `linear-gradient(270deg, rgb(255, 255, 255), rgb(98, 100, 106))` | `--color-cloud-burst-gradient-primary` | Decorative gradients from near-white to medium gray |
| Deep Space Gradient | `linear-gradient(133.42deg, rgb(108, 109, 119) -135.52%, rgb(26, 27, 31) 135.21%)` | `--color-deep-space-gradient` | Subtle background gradients for panels, header backgrounds |
| Graphite Gradient | `linear-gradient(94.85deg, rgb(140, 140, 147) 0.63%, rgb(63, 63, 67))` | `--color-graphite-gradient` | Background gradients for large feature sections |

## Tokens — Typography

### Inter — The primary typeface for all UI elements, body text, and most informational display. Its range of weights and precise letter-spacing contribute to the crisp, compact feel of the interface. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600
- **Sizes:** 11px, 12px, 13px, 14px, 16px, 20px, 24px, 28px, 55px
- **Line height:** 1.09, 1.10, 1.20, 1.23, 1.25, 1.38, 1.43, 1.50, 1.57, 1.60, 1.83, 2.00
- **Letter spacing:** -0.045em at 55px, -0.042em at 28px, -0.036em at 24px, -0.031em at 20px, -0.025em at 16px, -0.021em at 14px, -0.017em at 13px, -0.005em at 12px, -0.004em at 11px
- **Role:** The primary typeface for all UI elements, body text, and most informational display. Its range of weights and precise letter-spacing contribute to the crisp, compact feel of the interface.

### Migra — A decorative serif font used for select hero headlines and impactful statements. Its slightly wider tracking and unique character shapes provide a touch of distinctive elegance against the otherwise geometric UI. · `--font-migra`
- **Substitute:** serif
- **Weights:** 500
- **Sizes:** 21px, 58px
- **Line height:** 1.09, 1.25
- **Letter spacing:** 0.048em at 58px, 0.026em at 21px
- **Role:** A decorative serif font used for select hero headlines and impactful statements. Its slightly wider tracking and unique character shapes provide a touch of distinctive elegance against the otherwise geometric UI.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | -0.004px | `--text-caption` |
| heading | 20px | 1.25 | -0.031px | `--text-heading` |
| heading-lg | 24px | 1.23 | -0.036px | `--text-heading-lg` |
| display | 58px | 1.09 | 0.048px | `--text-display` |

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
| 120 | 120px | `--spacing-120` |
| 168 | 168px | `--spacing-168` |
| 184 | 184px | `--spacing-184` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 48px |
| badge | 22px |
| cards | 8px |
| input | 4px |
| buttons | 4px |
| formControl | 22px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.12) 0px 12px 12px 0px` | `--shadow-md` |
| sm | `rgba(4, 4, 7, 0.25) 0px 2px 4px 0px, rgba(4, 4, 7, 0.4) 0...` | `--shadow-sm` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 14px
- **Element gap:** 14px

## Components

### Input Field
**Role:** Primary interactive input element

Background #1a1b1f, border 1px solid #8a8c93, text Pure White. Subtle blur(10px) backdrop effect.

### Elevated Tool Card
**Role:** Interactive content container with distinction

Background #3b3c3, border 1px solid #8a8c93, radius 8px, padding 14px. Shadow: `rgba(0, 0, 0, 0.12) 0px 12px 12px 0px`.

### Primary Ghost Button
**Role:** Call to action or navigation link

Text Pure White (or #e0e0e0) on transparent background, border 1px solid #8a8c93, radius 4px, padding 12px horizontal. Hover applies a gradient background.

### Product Feature Card
**Role:** Neutral content display card

Background transparent, radius 8px, no explicit border on background. Text Callout Text (#e0e0e0) with supporting text in Whisper Gray (#62646a).

### Pill Badge
**Role:** Categorization or short label

Background transparent, text Muted Text (#535355), border 1px solid #535355, radius 22px, padding varies 3px-6px.

### Navigation Link
**Role:** Header navigation item

Text Whisper Gray (#62646a), interactive on hover/active with Pure White text. No distinct background or explicit padding, relies on elementGap for spacing.

## Do's and Don'ts

### Do
- Use Carbon Gray (#26272c) as the default background for all new sections.
- Apply Ghost Border (#8a8c93) for hairline separation and subtle element distinction.
- Headlines should leverage Migra 500 for high impact, with letter-spacing 0.048em at 58px and 0.026em at 21px.
- All interactive elements like buttons and inputs should have a border-radius of 4px.
- For card backgrounds, use Slate Surface (#1a1b1f) or Ash Gray (#3b3c3e) and apply a 1px solid #8a8c93 border.
- Text hierarchy should progress from Pure White (#ffffff) for primary headers to Callout Text (#e0e0e0) for body, and Whisper Gray (#62646a) or Muted Text (#535355) for secondary/helper text.
- Ensure large headlines and display text receive negative letter-spacing from Inter, e.g., -0.045em at 55px, for visual density.

### Don't
- Do not introduce highly saturated colors for functional UI elements; reserve them for subtle decorative gradients or brand accents.
- Avoid heavy drop shadows or strong visual separation between elements; prefer thin borders and subtle background shifts.
- Do not use generic system fonts; Inter and Migra are critical for the brand's typographic identity.
- Do not use a default padding or margin of less than 6px for interactive elements; elementGap should be at least 14px.
- Do not use solid backgrounds for primary CTA buttons; they should rely on text, outlined borders, or subtle gradients.
- Avoid large blocks of plain, uncommented text; text should be broken up with clear headings and thoughtful spacing.
- Do not use bright white as a general text color on dark backgrounds without specific contrast considerations; Callout Text (#e0e0e0) is preferred for most body content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#26272c` | Main page background, primary canvas for content display. |
| 1 | Input / Elevated Base | `#1a1b1f` | Default background for interactive inputs and slightly elevated content blocks. |
| 2 | Interactive Card | `#3b3c3` | Background for interactive cards, receiving subtle shadow and border. |
| 3 | Overlay / Gradient Start | `#ffffff` | Used primarily as a starting point for gradients that lighten toward the top, or for highlight elements against very dark backgrounds. |

## Elevation

- **Elevated Tool Card:** `rgba(0, 0, 0, 0.12) 0px 12px 12px 0px`
- **Input Field Focus:** `rgba(4, 4, 7, 0.25) 0px 2px 4px 0px, rgba(4, 4, 7, 0.4) 0px 8px 24px 0px`

## Imagery

The imagery is sparse, focusing on abstract graphic elements like blurred, light-emitting circles and radial gradients that give a sense of depth and focus, akin to a lens flare or spotlight. Product screenshots, when present, are tightly cropped, presented with a slight perspective, and encased within UI elements, never full-bleed. Icons are minimal, outlined, and monochromatic, maintaining a subtle presence. The visual language emphasizes UI over decorative graphics, with any non-UI visuals serving to enhance atmosphere rather than convey explicit information.

## Layout

The page primarily employs a max-width 1200px contained layout, centered on a dark background. The hero section is full-bleed, featuring a grand centered headline over an atmospheric radial gradient. Subsequent sections maintain a consistent vertical rhythm with Carbon Gray (#26272c) backgrounds, interspersed with subtle gradients or slightly lighter surface treatments. Content sections often feature centered typographic stacks for headlines and subheadings, followed by a product screenshot or input simulation. Navigation is a minimal top bar, sticky at scroll, with primary links and a subtle login/signup action.

## Agent Prompt Guide

Quick Color Reference:text: #ffffff, background: #26272c, border: #8a8c93, accent: #6c6d77, primary action: no distinct CTA color
Example Component Prompts:
Create a hero section: radial gradient background starting from Ghost Border, with a centered headline: Migra 58px, #ffffff, letter-spacing 0.048em, line-height 1.09. Subheading: Inter 24px, #e0e0e0, letter-spacing -0.036em, line-height 1.23.
Create an input field: background #1a1b1f, border 1px solid #8a8c93, radius 4px, padding 14px. Placeholder text #535355. Text #ffffff.
Create an elevated tool card: background #3b3c3e, border 1px solid #8a8c93, radius 8px, padding 14px. Shadow: `rgba(0, 0, 0, 0.12) 0px 12px 12px 0px`. Body text #e0e0e0, caption text #62646a.
Create a ghost navigation link: text #62646a, Inter 14px weight 400, no background or border. On hover, text becomes #ffffff.
Create a pill badge: background transparent, border 1px solid #535355, radius 22px, padding 6px horizontal. Text #535355, Inter 12px weight 400.

## Similar Brands

- **Superhuman** — Dark UI with strong emphasis on keyboard shortcuts, subtle gradients, and focused interactions on a deep background.
- **Linear** — Minimalist dark layout, strong typographic hierarchy, and a quiet, efficient aesthetic for a productivity tool.
- **Figma** — Productivity-focused dark UI, crisp text, and use of subtle surface differentiation and elevation for tools and panels.
- **Raycast** — Command-line interface aesthetic adapted to a graphical UI, featuring dark surfaces, precise typography, and a blur effect behind interactive components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-carbon-gray: #26272c;
  --color-slate-surface: #1a1b1f;
  --color-ash-gray: #3b3c3e;
  --color-ghost-border: #8a8c93;
  --color-whisper-gray: #62646a;
  --color-muted-text: #535355;
  --color-callout-text: #e0e0e0;
  --color-pure-white: #ffffff;
  --color-cloud-burst-gradient-primary: #b8b8b8;
  --gradient-cloud-burst-gradient-primary: linear-gradient(270deg, rgb(255, 255, 255), rgb(98, 100, 106));
  --color-deep-space-gradient: #6c6d77;
  --gradient-deep-space-gradient: linear-gradient(133.42deg, rgb(108, 109, 119) -135.52%, rgb(26, 27, 31) 135.21%);
  --color-graphite-gradient: #8c8c93;
  --gradient-graphite-gradient: linear-gradient(94.85deg, rgb(140, 140, 147) 0.63%, rgb(63, 63, 67));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-migra: 'Migra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.004px;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.031px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.23;
  --tracking-heading-lg: -0.036px;
  --text-display: 58px;
  --leading-display: 1.09;
  --tracking-display: 0.048px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-120: 120px;
  --spacing-168: 168px;
  --spacing-184: 184px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 14px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-3xl: 26px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-pill: 48px;
  --radius-badge: 22px;
  --radius-cards: 8px;
  --radius-input: 4px;
  --radius-buttons: 4px;
  --radius-formcontrol: 22px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 12px 12px 0px;
  --shadow-sm: rgba(4, 4, 7, 0.25) 0px 2px 4px 0px, rgba(4, 4, 7, 0.4) 0px 8px 24px 0px;

  /* Surfaces */
  --surface-base-canvas: #26272c;
  --surface-input-elevated-base: #1a1b1f;
  --surface-interactive-card: #3b3c3;
  --surface-overlay-gradient-start: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0a0a0a;
  --color-carbon-gray: #26272c;
  --color-slate-surface: #1a1b1f;
  --color-ash-gray: #3b3c3e;
  --color-ghost-border: #8a8c93;
  --color-whisper-gray: #62646a;
  --color-muted-text: #535355;
  --color-callout-text: #e0e0e0;
  --color-pure-white: #ffffff;
  --color-cloud-burst-gradient-primary: #b8b8b8;
  --color-deep-space-gradient: #6c6d77;
  --color-graphite-gradient: #8c8c93;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-migra: 'Migra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.004px;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.031px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.23;
  --tracking-heading-lg: -0.036px;
  --text-display: 58px;
  --leading-display: 1.09;
  --tracking-display: 0.048px;

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
  --spacing-120: 120px;
  --spacing-168: 168px;
  --spacing-184: 184px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-3xl: 26px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 12px 12px 0px;
  --shadow-sm: rgba(4, 4, 7, 0.25) 0px 2px 4px 0px, rgba(4, 4, 7, 0.4) 0px 8px 24px 0px;
}
```
