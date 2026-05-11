# Home — Style Reference
> Warm Canvas, Restrained Focus

**Theme:** light

Parallel presents a subdued, almost contemplative design system: a predominantly light, warm-toned canvas serves as a backdrop for high-contrast dark text and interactive elements. Product surfaces and cards are subtly shaded or near-transparent, using elevation sparingly to create focus. Typography is confident and clear, balancing a custom headline font with a versatile sans-serif. The overall feeling is one of considered calm, where interactions are precise rather than flashy, allowing content and functionality to take precedence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Sand | `#e4dfd9` | `--color-canvas-sand` | Page backgrounds, large section fills |
| White Cloud | `#ffffff` | `--color-white-cloud` | Elevated card surfaces, input backgrounds, active button fills, card backgrounds |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong headings, borders for ghost buttons and icons |
| Slate Gray | `#737373` | `--color-slate-gray` | Secondary text, muted headings, helper text |
| Dark Onyx | `#050505` | `--color-dark-onyx` | Heading text, robust body copy |
| Ash Mist | `#c7c7c7` | `--color-ash-mist` | Subtle background surfaces, decorative elements |
| Charcoal Tone | `#4b4b4b` | `--color-charcoal-tone` | Muted links, ghost button text, decorative accents |
| Deep Plum | `#171717` | `--color-deep-plum` | Filled button backgrounds for primary actions |
| Amber Pop | `#ffc42c` | `--color-amber-pop` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Rules Font — Brand headlines — its unique character at larger sizes defines the brand's voice · `--font-rules-font`
- **Substitute:** Playfair Display
- **Weights:** 500
- **Sizes:** 28px, 69px
- **Line height:** 1.10, 1.40
- **Letter spacing:** -0.0200em
- **Role:** Brand headlines — its unique character at larger sizes defines the brand's voice

### ui-sans-serif — General UI text, body copy, navigation, and input fields — prioritizing legibility and clarity · `--font-ui-sans-serif`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 19px, 23px
- **Line height:** 1.20, 1.40, 1.50
- **Letter spacing:** -0.0200em
- **Role:** General UI text, body copy, navigation, and input fields — prioritizing legibility and clarity

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.2 | -0.28px | `--text-caption` |
| body | 16px | 1.4 | -0.32px | `--text-body` |
| subheading | 19px | 1.4 | -0.38px | `--text-subheading` |
| heading-sm | 23px | 1.4 | -0.46px | `--text-heading-sm` |
| heading | 28px | 1.1 | -0.56px | `--text-heading` |
| display | 69px | 1.1 | -1.38px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 54 | 54px | `--spacing-54` |
| 58 | 58px | `--spacing-58` |
| 72 | 72px | `--spacing-72` |
| 74 | 74px | `--spacing-74` |
| 100 | 100px | `--spacing-100` |
| 122 | 122px | `--spacing-122` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 20px |
| inputs | 0px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.07) 0px 6px 27px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Header navigation, secondary actions

Transparent background, White Cloud text at 0.88 opacity, subtle 10px 18px horizontal padding, 10px radius.

### Talent/Employers Toggle
**Role:** Segmented control or primary category selection

Background #171717 (Deep Plum), medium weight text (likely 500 or 600), 9999px radius for pill shape, 10px 18px padding. The active state has a White Cloud background with Charcoal Tone text and 12px border radius.

### Primary Action Button (Filled)
**Role:** Main calls to action

Solid #171717 (Deep Plum) background, White Cloud text, 12px border radius to soften edges, variable padding 10px 18px for interaction states. Example 'Read more'.

### Search Input (Hero)
**Role:** Prominent search fields

Transparent background with White Cloud text at 0.9 opacity, 0px border radius (sharp top/bottom edge), likely a subtle bottom border or shadow for definition.

### Feature Card
**Role:** Content grouping, feature display

White Cloud background, 20px border radius for soft corners, no explicit border visible but uses rgba(0, 0, 0, 0.07) 0px 6px 27px 0px shadow for lift, 0px 0px 32px 0px inner padding for bottom spacing.

### Soft Highlight Button
**Role:** Interactive elements with soft visual emphasis

rgba(255, 255, 255, 0.96) background, rgba(5, 5, 5, 0.72) text, 12px border radius, no padding in variant data (implying text only or inherited).

## Do's and Don'ts

### Do
- Prioritize a Canvas Sand background for main content areas, with White Cloud for elevated cards and feature blocks.
- Use Rules Font weight 500 for all major headlines and titles (69px, 28px) with -0.0200em letter-spacing to maintain brand voice.
- Apply 12px border radius to all interactive buttons and soft highlight elements, and 20px radius for all cards, for a consistent soft-edged feel.
- Ensure primary text is set in Midnight Ink or Dark Onyx, with secondary information and helper text using Slate Gray or Charcoal Tone.
- Utilize a subtle rgba(0, 0, 0, 0.07) 0px 6px 27px 0px shadow on cards and elevated elements to provide depth without harshness.
- Maintain a comfortable information density, with 32px vertical padding on card elements and a consistent 8px element gap within components.

### Don't
- Avoid strong, saturated colors for UI elements; color should only be used as a subtle accent or functional indicator.
- Do not use sharp, 0px border radii on interactive buttons, as the system favors rounded corners for interactives.
- Do not introduce heavy borders or strong gradients on cards or surfaces; the aesthetic relies on subtle elevation and clean backgrounds.
- Avoid dense, compact text blocks; ensure generous line heights and paragraph spacing to maintain readability.
- Do not use dark backgrounds for main content sections outside of the hero, as the system is primarily light-themed.
- Do not rely on outline or ghost buttons for primary calls to action; use the Deep Plum filled button instead.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Sand | `#e4dfd9` | Dominant page background |
| 1 | White Cloud | `#ffffff` | Elevated cards, main information containers |
| 2 | Ash Mist | `#c7c7c7` | Subtle background surfaces, decorative elements that are not interactive |
| 3 | Deep Plum | `#171717` | Interactive elements: button backgrounds, search bar backgrounds in hero |

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.07) 0px 6px 27px 0px`

## Imagery

The site predominantly uses dramatic, high-contrast photography in its hero sections, often with a desaturated or single-tone filter applied, focusing on human subjects in motion or contemplation. Product screenshots are contained within White Cloud cards, typically showing detailed UI elements with clean, sharp edges and minimal context. Icons are minimal, either solid or outlined, often in black or white. Imagery serves both decorative atmosphere and explanatory content, balancing large-scale emotional impact with precise product showcases.

## Layout

The layout is primarily a max-width 1200px centered container, with the hero section often being full-bleed. The hero initially features a large, dark-toned background image overlaid with white, centered headlines and a prominent input field. Subsequent sections employ a consistent vertical rhythm with minimal visual dividers, mostly implied by alternating subtle background shades (Canvas Sand and White Cloud for cards). Content is often arranged in a 2-column grid for text-image pairings or a 3-column card grid for features. The navigation is a sticky top bar with logo, ghost links, and a distinctive pill-shaped toggle for 'Talent'/'Employers'.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000 (Midnight Ink)
- background: #e4dfd9 (Canvas Sand)
- border: #000000 (Midnight Ink)
- accent: #ffc42c (Amber Pop)
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
- Create a hero section: Canvas Sand background fading visually into a desaturated human photo. Centered headline 'Find your life's work' at 69px Rules Font weight 500, Midnight Ink, letter-spacing '-0.0200em'. Subtext 'Land a job that feels like freedom.' at 19px ui-sans-serif weight 400, Slate Gray. Below this, a search input with transparent background, White Cloud text (0.9 opacity), 0px radius. A 'Read more' button immediately below the input: Deep Plum background, White Cloud text, 12px radius, 10px 18px padding.
- Create a feature card: White Cloud background, 20px border radius, shadow rgba(0, 0, 0, 0.07) 0px 6px 27px 0px. Heading 'Hyper personal matches' at 23px ui-sans-serif weight 500, Dark Onyx. Body text 'No fake jobs, just fresh direct roles...' at 16px ui-sans-serif weight 400, Slate Gray. Bottom internal padding 32px.
- Create a navigation bar: Midnight Ink logo. Ghost navigation buttons ('Explore', 'Sign in') with transparent background, White Cloud text (0.88 opacity), 10px 18px padding, 10px radius. Segmented toggle ('Talent', 'Employers') in Deep Plum with White Cloud text, 9999px radius and 10px 18px padding for each segment.

## Similar Brands

- **Airtable** — Uses a light, warm neutral background with distinct, often dark, typographic elements and minimal interface embellishments.
- **Linear** — Employs a precise, UI-focused aesthetic with subtle elevations, limited color use outside of functional highlights, and clear typography.
- **Notion** — Features a clean, minimalist canvas with high-contrast text and a focus on content hierarchy over decorative UI.
- **Superhuman** — Dark UI elements (like buttons) against a predominantly light background create a sense of focused action within a clean experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-sand: #e4dfd9;
  --color-white-cloud: #ffffff;
  --color-midnight-ink: #000000;
  --color-slate-gray: #737373;
  --color-dark-onyx: #050505;
  --color-ash-mist: #c7c7c7;
  --color-charcoal-tone: #4b4b4b;
  --color-deep-plum: #171717;
  --color-amber-pop: #ffc42c;

  /* Typography — Font Families */
  --font-rules-font: 'Rules Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.2;
  --tracking-caption: -0.28px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.32px;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.38px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.46px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -0.56px;
  --text-display: 69px;
  --leading-display: 1.1;
  --tracking-display: -1.38px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-54: 54px;
  --spacing-58: 58px;
  --spacing-72: 72px;
  --spacing-74: 74px;
  --spacing-100: 100px;
  --spacing-122: 122px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 20px;
  --radius-inputs: 0px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.07) 0px 6px 27px 0px;

  /* Surfaces */
  --surface-canvas-sand: #e4dfd9;
  --surface-white-cloud: #ffffff;
  --surface-ash-mist: #c7c7c7;
  --surface-deep-plum: #171717;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-sand: #e4dfd9;
  --color-white-cloud: #ffffff;
  --color-midnight-ink: #000000;
  --color-slate-gray: #737373;
  --color-dark-onyx: #050505;
  --color-ash-mist: #c7c7c7;
  --color-charcoal-tone: #4b4b4b;
  --color-deep-plum: #171717;
  --color-amber-pop: #ffc42c;

  /* Typography */
  --font-rules-font: 'Rules Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.2;
  --tracking-caption: -0.28px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.32px;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.38px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.46px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -0.56px;
  --text-display: 69px;
  --leading-display: 1.1;
  --tracking-display: -1.38px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-54: 54px;
  --spacing-58: 58px;
  --spacing-72: 72px;
  --spacing-74: 74px;
  --spacing-100: 100px;
  --spacing-122: 122px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.07) 0px 6px 27px 0px;
}
```
