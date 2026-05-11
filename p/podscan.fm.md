# Podscan.fm — Style Reference
> Whiteboard with digital highlights

**Theme:** light

Podscan employs a productivity-focused aesthetic with a clean white canvas and soft, elevated components. Typography is clear and direct, using both a system sans-serif for body text and a tighter custom sans-serif for headings, creating distinct information hierarchies. A spectrum of saturated, functional colors provides visual disambiguation and branding for unique features or states, puncturing the otherwise minimalist gray palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#f4f4f5` | `--color-absolute-zero` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Graphite | `#52525b` | `--color-graphite` | Secondary text, muted helper text, table content |
| Mid Grey | `#71717a` | `--color-mid-grey` | Tertiary text, link text, lighter body copy |
| Silver Pine | `#a1a1aa` | `--color-silver-pine` | Muted body text, placeholder text, inactive icons |
| Cloud Whisper | `#d4d4d8` | `--color-cloud-whisper` | Light borders, inactive input borders, subtle dividers |
| Ash Felt | `#e5e7eb` | `--color-ash-felt` | Hairline borders, subtle separators, card borders |
| White Smoke | `#fafafe` | `--color-white-smoke` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, primary button backgrounds |
| Midnight Ink | `#18181b` | `--color-midnight-ink` | Primary text, headers, strong body copy |
| Emerald Spark | `#059669` | `--color-emerald-spark` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Radiant Green | `#10b981` | `--color-radiant-green` | Distinct icon accent, interactive elements' stroke and fill |
| Vivid Violet | `#9333ea` | `--color-vivid-violet` | Violet action color for filled buttons, selected navigation states, and focused conversion moments. |
| Hyper Blue | `#2563eb` | `--color-hyper-blue` | Accent color for features, icon color and stroke |
| Magenta Burst | `#ec4899` | `--color-magenta-burst` | Icon stroke and fill, accent background for specific sections |
| Crimson Flux | `#db2777` | `--color-crimson-flux` | Accent for features, icon color and stroke |
| Azure Haze | `#a5b4fc` | `--color-azure-haze` | Decorative border for pricing cards, inactive states |
| Amethyst Tint | `#e9d5ff` | `--color-amethyst-tint` | Decorative border for pricing cards, muted accents |
| Leafy Green | `#16a34a` | `--color-leafy-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Warning Yellow | `#eab308` | `--color-warning-yellow` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Scarlet Alert | `#b91c1c` | `--color-scarlet-alert` | Red text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Inter Tight — Headings and key callouts. Its tightness creates a modern, condensed feel suitable for prominent textual elements, commanding attention without being overly bold. · `--font-inter-tight`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 20px, 24px, 30px, 36px, 60px
- **Line height:** 1.00, 1.11, 1.20, 1.33, 1.40, 1.43
- **Letter spacing:** -0.029em at 14px to -0.011em at 60px
- **Role:** Headings and key callouts. Its tightness creates a modern, condensed feel suitable for prominent textual elements, commanding attention without being overly bold.

### ui-sans-serif — Body text, navigation, buttons, and general UI elements. Its clean, readable nature ensures clarity across various UI contexts, preferring system fonts for efficiency. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 30px
- **Line height:** 1.20, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.033em at 12px to -0.013em at 30px
- **Role:** Body text, navigation, buttons, and general UI elements. Its clean, readable nature ensures clarity across various UI contexts, preferring system fonts for efficiency.

### ui-monospace — Used sparingly for code snippets or specific data displays, providing a technical contrast to the primary sans-serifs. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** -0.033em
- **Role:** Used sparingly for code snippets or specific data displays, providing a technical contrast to the primary sans-serifs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | -0.396px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.406px | `--text-body-sm` |
| body | 16px | 1.5 | -0.4px | `--text-body` |
| subheading | 18px | 1.56 | -0.36px | `--text-subheading` |
| heading-sm | 20px | 1.4 | -0.4px | `--text-heading-sm` |
| heading | 24px | 1.33 | -0.48px | `--text-heading` |
| heading-lg | 30px | 1.2 | -0.6px | `--text-heading-lg` |
| display | 60px | 1 | -0.66px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 112 | 112px | `--spacing-112` |
| 168 | 168px | `--spacing-168` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| icons | 8px |
| inputs | 12px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| subtle-2 | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle-2` |
| md-2 | `rgba(5, 150, 105, 0.2) 0px 10px 15px -3px, rgba(5, 150, 1...` | `--shadow-md-2` |
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl-2` |

### Layout

- **Section gap:** 72px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Call to Action Button
**Role:** Filled button indicating the primary path forward.

Background: Emerald Spark (#059669), text: Pure White (#ffffff). Padding: 14px vertical, 32px horizontal. Border radius: 8px. Text uses ui-sans-serif, weight 400.

### Secondary Ghost Button
**Role:** Subtle action, less prominent than primary.

Background: Pure White (#ffffff), text: Midnight Ink (#18181b). Border: 1px solid Ash Felt (#e5e7eb). Padding: 12px vertical, 16px horizontal. Border radius: 12px. Text uses ui-sans-serif, weight 400.

### Tertiary Tab Button
**Role:** Small, information-based button for categories or filtering.

Background: White Smoke (#fafafe), text: Graphite (#52525b). Border: 1px solid Ash Felt (#e5e7eb). Padding: 4px vertical, 10px horizontal. Border radius: 9999px (pill-shaped). Text uses ui-sans-serif, weight 400.

### Floating Card
**Role:** Elevated container for content sections, usually informative.

Background: Pure White (#ffffff). Padding: 32px. Border radius: 12px. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Clean Card
**Role:** Basic container for grouped content, minimal elevation.

Background: Pure White (#ffffff). Padding: 16px. Border radius: 8px. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Flat Card
**Role:** Simple background grouping without elevation.

Background: Absolute Zero (#f4f4f5). Padding: 16px. Border radius: 8px. No shadow.

### Pricing Tier Card (Professional)
**Role:** Highlighting a specific pricing tier with brand accent.

Background: Pure White (#ffffff). Padding: 32px. Border radius: 12px. Border: 2px solid Emerald Spark (#059669). Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px. Features a 'Most Popular' tag with Emerald Spark (#10b981) background.

### Search Input
**Role:** Text input field for searching content.

Background: Pure White (#ffffff), text: Midnight Ink (#18181b), placeholder: Silver Pine (#a1a1aa). Border: 1px solid Ash Felt (#e5e7eb). Padding: 12px vertical, 48px left, 112px right. Border radius: 12px. Icon is part of the input, ui-sans-serif font.

### Pill Tag
**Role:** Small, interactive tag for filtering or highlighting terms.

Background: White Smoke (#fafafa), text: Mid Grey (#71717a). Border: 1px solid Ash Felt (#e5e7eb). Padding: 4px vertical, 10px horizontal. Border radius: 9999px. Text uses ui-sans-serif, weight 400.

## Do's and Don'ts

### Do
- Use Pure White (#ffffff) as the default canvas for primary content blocks.
- Prioritize Emerald Spark (#059669) for all primary calls to action, ensuring full background fill.
- Apply Ash Felt (#e5e7eb) for fine borders, separating UI elements and defining input fields.
- Utilize Inter Tight for all prominent headings above 24px, adjusting letter-spacing according to its scale.
- Maintain an 8px border-radius for all interactive buttons that require a defined boundary.
- Use a minimum element space of 8px (often 16px) around interactive elements.
- Employ the subtle shadow rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for elevated cards to create minimal depth.

### Don't
- Avoid using highly saturated colors for large surface areas; reserve them for functional accents and icons.
- Do not use dark backgrounds for full sections; the theme is predominantly light and airy.
- Do not deviate from the established border radii; maintain 9999px for tags, 8px for buttons, and 12px for cards and inputs.
- Never introduce new font families; rely strictly on ui-sans-serif, Inter Tight, and ui-monospace.
- Avoid deep, heavy shadows; rely on minimal elevation provided by rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.
- Do not use different weights of Inter Tight for body text; reserve it for headings and key phrases.
- Do not use brand or accent colors (e.g., Vivid Violet, Hyper Blue) for text unless it is for an icon, link, or specific header described in the tokens, to maintain neutral content readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pure White Canvas | `#ffffff` | Primary page background and default component surface |
| 1 | White Smoke Surface | `#fafafe` | Subtle background for specific UI elements like inputs and tertiary buttons, slightly distinct from canvas |
| 2 | Absolute Zero Background | `#f4f4f5` | Alternative background for sections and larger containers, providing a slight contrast to the main canvas without introducing significant color |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Floating Card (larger):** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Navigation:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

## Imagery

This site predominantly uses clean, color-accented icons with solid fills or precise strokes for functional visual communication. There is minimal use of photography or complex illustrations. Product screenshots are typically presented as contained within clean, rounded frames. Iconography is a mix of mono-color (often using accent colors like Radiant Green or Vivid Violet) and occasional two-tone designs, maintaining clear, legible forms, and serving an explanatory and decorative role.

## Layout

The page adheres to a max-width contained layout, approximately 1200px, with content consistently centered. The hero section features a prominent, centered headline and subtext, followed by two primary call-to-action buttons. Sections alternate between pure white and light gray backgrounds, creating a subtle visual rhythm. Content is often arranged in card grids (3-column, 4-column) or text-over-icon blocks. Navigation is a sticky top bar with a left-aligned logo and right-aligned primary links and one primary action button.

## Agent Prompt Guide

Quick Color Reference:
text: #18181b
background: #ffffff
border: #e5e7eb
accent: #10b981
primary action: #059669 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #059669 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a pricing card 'Starter': Pure White (#ffffff) background, 12px border radius, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px shadow. Heading 'Starter' at 24px Inter Tight weight 700, #18181b, letter-spacing -0.48px. Feature text in Graphite (#52525b) at 16px ui-sans-serif weight 400. Button 'Get Started' with Pure White (#ffffff) background, Midnight Ink (#18181b) text, 8px radius, 12px 16px padding, ui-sans-serif weight 400.
3. Create a search input field: Pure White (#ffffff) background, 12px border radius, 1px solid Ash Felt (#e5e7eb). Placeholder text 'Search' in Silver Pine (#a1a1aa) at 16px ui-sans-serif weight 400. Current input text 'podcast' in Midnight Ink (#18181b) at 16px ui-sans-serif weight 400. Include a search icon in Silver Pine (#a1a1aa).

## Similar Brands

- **Ahrefs** — Clean, predominantly white SaaS UI with strong typography, minimal illustration, and functional color accents.
- **SEMrush** — Data-heavy platform focusing on clear presentation, system fonts, and a vibrant color palette for data visualization and interaction.
- **ClickUp** — Productivity tool with a clean, light theme, a strong emphasis on card-based layouts, and functional color coding for elements and statuses.
- **Linear** — Minimalist UI, focus on speed and clarity, system typography with careful letter-spacing, and subtle, intentional use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #f4f4f5;
  --color-graphite: #52525b;
  --color-mid-grey: #71717a;
  --color-silver-pine: #a1a1aa;
  --color-cloud-whisper: #d4d4d8;
  --color-ash-felt: #e5e7eb;
  --color-white-smoke: #fafafe;
  --color-pure-white: #ffffff;
  --color-midnight-ink: #18181b;
  --color-emerald-spark: #059669;
  --color-radiant-green: #10b981;
  --color-vivid-violet: #9333ea;
  --color-hyper-blue: #2563eb;
  --color-magenta-burst: #ec4899;
  --color-crimson-flux: #db2777;
  --color-azure-haze: #a5b4fc;
  --color-amethyst-tint: #e9d5ff;
  --color-leafy-green: #16a34a;
  --color-warning-yellow: #eab308;
  --color-scarlet-alert: #b91c1c;

  /* Typography — Font Families */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: -0.396px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.406px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: -0.36px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.48px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.6px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.66px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-168: 168px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-icons: 8px;
  --radius-inputs: 12px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-md-2: rgba(5, 150, 105, 0.2) 0px 10px 15px -3px, rgba(5, 150, 105, 0.2) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;

  /* Surfaces */
  --surface-pure-white-canvas: #ffffff;
  --surface-white-smoke-surface: #fafafe;
  --surface-absolute-zero-background: #f4f4f5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #f4f4f5;
  --color-graphite: #52525b;
  --color-mid-grey: #71717a;
  --color-silver-pine: #a1a1aa;
  --color-cloud-whisper: #d4d4d8;
  --color-ash-felt: #e5e7eb;
  --color-white-smoke: #fafafe;
  --color-pure-white: #ffffff;
  --color-midnight-ink: #18181b;
  --color-emerald-spark: #059669;
  --color-radiant-green: #10b981;
  --color-vivid-violet: #9333ea;
  --color-hyper-blue: #2563eb;
  --color-magenta-burst: #ec4899;
  --color-crimson-flux: #db2777;
  --color-azure-haze: #a5b4fc;
  --color-amethyst-tint: #e9d5ff;
  --color-leafy-green: #16a34a;
  --color-warning-yellow: #eab308;
  --color-scarlet-alert: #b91c1c;

  /* Typography */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: -0.396px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.406px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: -0.36px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.48px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.6px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.66px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-168: 168px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-md-2: rgba(5, 150, 105, 0.2) 0px 10px 15px -3px, rgba(5, 150, 105, 0.2) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
}
```
