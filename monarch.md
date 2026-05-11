# Monarch — Style Reference
> Warm, confident financial clarity

**Theme:** light

Monarch presents a financial platform with a comfortable, professional aesthetic. It pairs a warm, inviting orange as its primary accent with a clean, light canvas, creating an approachable yet authoritative feel. Typography uses a custom serif for headlines, conveying trust, while a modern sans-serif offers crisp product information. Components are subtly elevated with rounded corners and soft shadows for a tactile, user-friendly experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Monarch Flame | `#ff692d` | `--color-monarch-flame` | Primary action buttons, brand icons, key highlights — a vibrant, warm orange that signifies action and positive engagement |
| Burnt Orange | `#f35b16` | `--color-burnt-orange` | Promotional text, secondary emphasis for features |
| Sunny Glow | `#ffbc0b` | `--color-sunny-glow` | Decorative icon accents, subtle highlight elements in charts |
| Crimson Ember Gradient | `linear-gradient(to right, rgb(229, 72, 77), rgb(255, 105, 45))` | `--color-crimson-ember-gradient` | Promotional banner backgrounds, creating a striking, inviting entry point |
| Porcelain White | `#ffffff` | `--color-porcelain-white` | Card backgrounds, primary surface areas, text on dark backgrounds |
| Canvas Oat | `#efecea` | `--color-canvas-oat` | Page background, secondary surface areas, subtle content separation |
| Slate Border | `#dcd9d6` | `--color-slate-border` | Hairline borders, dividers, subtle outlines for ghost buttons and inputs — establishes separation without harshness |
| Deep Charcoal | `#22201d` | `--color-deep-charcoal` | Primary text, headings, prominent iconography — provides strong contrast for readability |
| Muted Stone | `#777573` | `--color-muted-stone` | Secondary text, subheadings, helper text, and copyright information |
| Light Gray Icons | `#cccccc` | `--color-light-gray-icons` | Neutral icon fills and strokes, providing visual balance in complex UIs |

## Tokens — Typography

### ABC Oracle — Body text, navigation, buttons, and detailed interface elements. Its clean, geometric form ensures readability across various sizes. · `--font-abc-oracle`
- **Substitute:** Inter
- **Weights:** 100, 350, 400, 500
- **Sizes:** 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.30, 1.33, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0120em, -0.0100em, 0.0500em
- **Role:** Body text, navigation, buttons, and detailed interface elements. Its clean, geometric form ensures readability across various sizes.

### Copernicus — Primary headlines and impactful display text. The serif font with its light 350 weight creates a refined, authoritative presence, lending a sense of established trust rather than shouting. · `--font-copernicus`
- **Substitute:** Merriweather
- **Weights:** 350
- **Sizes:** 32px, 40px, 48px
- **Line height:** 1.20
- **Letter spacing:** -0.0670em, -0.0600em, -0.0500em
- **Role:** Primary headlines and impactful display text. The serif font with its light 350 weight creates a refined, authoritative presence, lending a sense of established trust rather than shouting.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.05px | `--text-caption` |
| body | 16px | 1.5 | -0.012px | `--text-body` |
| subheading | 20px | 1.3 | -0.012px | `--text-subheading` |
| heading | 32px | 1.2 | -0.067px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.06px | `--text-heading-lg` |
| display | 48px | 1.2 | -0.05px | `--text-display` |

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
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| inputs | 8px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(34, 32, 29, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |
| md | `rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29...` | `--shadow-md` |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with Monarch Flame background (#ff692d), Porcelain White text (#ffffff), 9999px border-radius, and 16px horizontal padding. Shadow rgba(34, 32, 29, 0.05) 0px 1px 2px 0px.

### Secondary Ghost Button
**Role:** Alternative action

Ghost button with transparent background, Deep Charcoal text (#22201d), Slate Border (#dcd9d6) with a 1px solid style, 9999px border-radius, and 12px horizontal padding. Text is ABC Oracle, 14px, weight 400.

### Navigation Link Button
**Role:** Navigation and internal links

Subtle ghost button for navigation. Transparent background, Deep Charcoal text (#22201d), Slate Border (#dcd9d6), 9999px border-radius, 12px horizontal and 8px vertical padding. Text is ABC Oracle, 14px, weight 400.

### Canvas Card
**Role:** Content grouping

White background (#ffffff), 8px border-radius, 24px padding. No shadow by default.

### Subtle Canvas Card
**Role:** Content grouping (light emphasis)

Light oatmeal background (#efecea), 12px border-radius, 32px padding. No shadow by default.

### App Screenshot Card
**Role:** Product detail showcase

White background with 75% opacity (#ffffff), 12px border-radius, 24px padding. Often used to embed product screenshots, blending into the background to highlight content.

### Sectional Card with Shadow
**Role:** Elevated content block

White background (#ffffff), 12px border-radius and an elevation shadow rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29, 0.1) 0px 4px 6px -4px. Padding is implicitly 24px.

## Do's and Don'ts

### Do
- Use Monarch Flame (#ff692d) exclusively for primary calls to action or key brand highlights.
- Apply Deep Charcoal (#22201d) for all primary body text and headings to ensure strong readability.
- Employ Copernicus font weight 350 for all page-level headlines to maintain a refined and established tone.
- Always use a 9999px border-radius for buttons and navigation items to convey a soft, approachable feel.
- Distribute content vertically using 'sectionGap' at 64px to provide ample breathing room between major content blocks.
- Utilize Canvas Oat (#efecea) as the dominant page background color for all main content sections outside of the hero.
- Ensure input fields and secondary elements use a Slate Border (#dcd9d6) with a 1px solid stroke.

### Don't
- Do not use Monarch Flame (#ff692d) for general text or borders; reserve it for functional components.
- Avoid using multiple serif fonts for headlines; Copernicus is the designated serif heading font.
- Do not use dark backgrounds for main content areas; maintain a light theme dominant with Canvas Oat and Porcelain White.
- Never apply harsh or overly dark shadows; stick to the specified soft elevation styles for subtle depth.
- Do not deviate from the established spacing scale; maintain comfortable density with 'elementGap' at 16px and 'cardPadding' at 24px.
- Avoid sharp corners on interactive elements and cards; enforce 9999px for buttons and 8px/12px for cards.
- Do not use the Crimson Ember Gradient for anything other than header banners or specific promotional calls due to its intensity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Oat | `#efecea` | Dominant page background, providing a warm, subtle base for content. |
| 1 | Porcelain White | `#ffffff` | Primary surface for cards, dialogs, and content blocks, offering crisp contrast against the canvas. |
| 2 | Elevated Porcelain White | `#ffffff` | Cards or components that require a subtle sense of elevation, typically accompanied by a soft shadow. |

## Elevation

- **Button:** `rgba(34, 32, 29, 0.05) 0px 1px 2px 0px`
- **Card:** `rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29, 0.1) 0px 4px 6px -4px`

## Imagery

The site uses a combination of stock photography featuring people in a casual, warm setting, paired with abstract, data-visualization-like UI overlays. Product screenshots of the Monarch app are presented on soft, neutral background cards or within simulated device frames, always in a contained and isolated manner. Iconography is minimalist, often monochrome in Deep Charcoal or Slate Border, with occasional accents of Monarch Flame or Sunny Glow for emphasis. The imagery serves both decorative atmosphere (lifestyle photos) and clear explanatory content (product UIs), maintaining a balance between human connection and financial clarity.

## Layout

The page primarily uses a max-width contained layout, though the initial hero section spans full-bleed with a dark background. The hero features a large, centered headline over a background image with frosted product UI overlays. Subsequent sections alternate between a light Canvas Oat (#efecea) and Porcelain White (#ffffff) background, creating a visual rhythm. Content is arranged in flexible patterns, including centered stacked text blocks and alternating two-column layouts (text on left, product visual on right). A 3-column card grid is used for feature presentation. The overall density is comfortable, with generous vertical spacing between sections. Navigation is primarily a sticky top bar with clearly labeled links and distinct sign-in/sign-up buttons.

## Agent Prompt Guide

### Quick Color Reference
text: #22201d
background: #efecea
border: #dcd9d6
accent: #ff692d
primary action: #ff692d (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #ff692d background, #22201d text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: background #ffffff, border-radius 8px, padding 24px, headline 'Know where you stand' in Copernicus 32px, text #22201d, subtext in ABC Oracle 16px, text #22201d.
3. Build a ghost navigation link: text 'For Professionals', background transparent, text color #22201d, border-color #dcd9d6, border-style 1px solid, border-radius 9999px, padding 8px 12px.
4. Construct an elevated information card with a headline: background #ffffff, border-radius 12px, shadow rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29, 0.1) 0px 4px 6px -4px, padding 32px, headline 'Everything you need, all in one app' in Copernicus 40px, text #22201d.

## Similar Brands

- **Mint** — Similar financial management focus with a clean, functional UI and clear data visualization.
- **You Need A Budget (YNAB)** — Employs a comfortable, organized layout with clear action-oriented elements and a positive, encouraging tone.
- **Personal Capital** — Combines lifestyle imagery with structured financial dashboards and a professional yet accessible aesthetic.
- **Wealthfront** — Uses a similar approach to typography, pairing a classic serif for headlines with a modern sans-serif for body text, creating a blend of authority and clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-monarch-flame: #ff692d;
  --color-burnt-orange: #f35b16;
  --color-sunny-glow: #ffbc0b;
  --color-crimson-ember-gradient: #e5484d;
  --gradient-crimson-ember-gradient: linear-gradient(to right, rgb(229, 72, 77), rgb(255, 105, 45));
  --color-porcelain-white: #ffffff;
  --color-canvas-oat: #efecea;
  --color-slate-border: #dcd9d6;
  --color-deep-charcoal: #22201d;
  --color-muted-stone: #777573;
  --color-light-gray-icons: #cccccc;

  /* Typography — Font Families */
  --font-abc-oracle: 'ABC Oracle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-copernicus: 'Copernicus', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.012px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.012px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.067px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.06px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.05px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-w350: 350;
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
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-inputs: 8px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(34, 32, 29, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29, 0.1) 0px 4px 6px -4px;

  /* Surfaces */
  --surface-canvas-oat: #efecea;
  --surface-porcelain-white: #ffffff;
  --surface-elevated-porcelain-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-monarch-flame: #ff692d;
  --color-burnt-orange: #f35b16;
  --color-sunny-glow: #ffbc0b;
  --color-crimson-ember-gradient: #e5484d;
  --color-porcelain-white: #ffffff;
  --color-canvas-oat: #efecea;
  --color-slate-border: #dcd9d6;
  --color-deep-charcoal: #22201d;
  --color-muted-stone: #777573;
  --color-light-gray-icons: #cccccc;

  /* Typography */
  --font-abc-oracle: 'ABC Oracle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-copernicus: 'Copernicus', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.012px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.012px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.067px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.06px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(34, 32, 29, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(34, 32, 29, 0.1) 0px 10px 15px -3px, rgba(34, 32, 29, 0.1) 0px 4px 6px -4px;
}
```
