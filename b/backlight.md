# Backlight — Style Reference
> Ember-charged industrial efficiency.

**Theme:** light

Backlight uses a high-contrast, bold and direct visual language anchored by a dominant, vivid Ember Orange and deep Charred Ink. Typography is sans-serif, with tight tracking on headlines, conveying a sense of no-nonsense efficiency. Layouts are spacious but information-dense, often leveraging strong color blocks and minimal, purposeful interactive elements to guide the user without visual clutter. The system feels confident and modern, with a strong focus on readability against distinct colored sections.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ember Orange | `#dd3508` | `--color-ember-orange` | Orange accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Peach Crush | `#f3b8a9` | `--color-peach-crush` | Decorative highlights, background elements, navigation indicators, subtle brand touches — a lighter shade of the primary brand color |
| Copper Glow | `#f03909` | `--color-copper-glow` | Orange outline accent for tags, dividers, and focused UI edges. |
| Sand Dune | `#d7cabb` | `--color-sand-dune` | Secondary badge backgrounds, subtle surface variations, muted text in specific contexts — a warm, light neutral with a beige tint |
| Charred Ink | `#151515` | `--color-charred-ink` | Darkest text, hero element colors, section backgrounds, footer background — provides strong contrast and grounding |
| Lead Gray | `#4f4f4f` | `--color-lead-gray` | Primary text color, general body text, and some border elements — a versatile dark gray for content |
| Whisper White | `#ffffff` | `--color-whisper-white` | Primary background for light sections, text on dark backgrounds, active navigation elements, button backgrounds |
| Pale Ash | `#e4ddd5` | `--color-pale-ash` | Subtle background surfaces, card backgrounds, input field borders — a very light, slightly warm gray for secondary surfaces |
| Ghost Gray | `#333333` | `--color-ghost-gray` | Muted text elements, secondary link colors — a slightly lighter dark grey for less prominent text |
| Obsidian Text | `#000000` | `--color-obsidian-text` | Strongest contrasts for text, button text on light backgrounds — absolute black for maximal impact |
| Slate Border | `#1c1c1c` | `--color-slate-border` | Subtle borders and dividers against light backgrounds — a dark, almost black, line weight |

## Tokens — Typography

### Instrument Sans — Primary text font for all headings, body copy, and UI elements. Its clean sans-serif lines ensure clarity and legibility, contributing to the system's efficient aesthetic. Tighter tracking on larger sizes (-0.0200em) creates a crisp, impactful appearance. · `--font-instrument-sans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 28px, 32px, 39px, 48px
- **Line height:** 1.00, 1.15, 1.20, 1.25, 1.30, 1.43
- **Letter spacing:** -0.0200em at large sizes, 0.0200em at small sizes
- **Role:** Primary text font for all headings, body copy, and UI elements. Its clean sans-serif lines ensure clarity and legibility, contributing to the system's efficient aesthetic. Tighter tracking on larger sizes (-0.0200em) creates a crisp, impactful appearance.

### Fragment Mono — Used for specific functional text, like timestamps or code snippets, where its monospace property aids in distinguishing from primary content. Distinctive tight letter-spacing (-0.0800em, -0.0210em) gives it a technical, precise feel. · `--font-fragment-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400, 700
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.15, 1.30
- **Letter spacing:** -0.0800em at 14px, -0.0210em at 16px
- **Role:** Used for specific functional text, like timestamps or code snippets, where its monospace property aids in distinguishing from primary content. Distinctive tight letter-spacing (-0.0800em, -0.0210em) gives it a technical, precise feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body-sm | 14px | 1.43 | -0.8px | `--text-body-sm` |
| body | 16px | 1.43 | -0.32px | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | — | `--text-heading` |
| heading-lg | 39px | 1.15 | — | `--text-heading-lg` |
| display | 48px | 1 | -0.96px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 60px |
| inputs | 4px |
| buttons | 8px |
| callout | 20px |

### Layout

- **Page max-width:** 1361px
- **Section gap:** 170px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Outlined Button
**Role:** Call to action

Ghost button with an Ember Orange border (#dd3508) and text (#dd3508), 8px border-radius, 12px vertical and 16px horizontal padding. Hover states could invert fill and text colors.

### Solid Primary Button
**Role:** Primary action

Solid Whisper White (#ffffff) background with Ember Orange (#dd3508) text, 8px border-radius, 12px vertical and 16px horizontal padding. Used for the prominent 'Get started' action.

### Text Link Button
**Role:** Navigational/Secondary Action

Text in Charred Ink (#151515, or #000000) with no background or border, 80px border-radius (effectively pill-shaped visuals via styling), 0px padding. Seen in navigation and as inline action links.

### Feature Card
**Role:** Content container

Background in Pale Ash (#e4ddd5) or transparent, with 8px border-radius, and 16px padding on all sides. Used for displaying individual features or content blocks.

### Input Field
**Role:** User input

Transparent background with Whisper White (#ffffff) text and a 1px solid Pale Ash (#e4ddd5) border, 4px border-radius, 8px vertical and 12px horizontal padding.

### Tag Badge
**Role:** Categorization/Highlight

Sand Dune (#d7cabb) background with Charred Ink (#151515) text, 60px border-radius (pill shape), 10px vertical and 15px horizontal padding.

### Navigation Tab
**Role:** Primary navigation

Charred Ink (#151515) text on a transparent background for inactive states. Active state features a Peach Crush (#f3b8a9) underline and Whisper White (#ffffff) text.

## Do's and Don'ts

### Do
- Use Ember Orange (#dd3508) as the dominant accent color for large hero sections or for outlined calls to action.
- Apply Instrument Sans for all textual content, utilizing its weight variations (400, 500, 600) for appropriate hierarchy.
- Maintain a clear contrast hierarchy: Charred Ink (#151515) for background elements and primary text, Whisper White (#ffffff) for text on dark backgrounds and primary button fills.
- Implement tight letter-spacing (-0.0200em) for headings and larger text sizes using Instrument Sans to maintain visual crispness.
- Utilize 8px border-radius for buttons and cards, and 4px for inputs, with 60px for badges, to provide consistent component shaping.
- Structure pages with generous section gaps, defaulting to 170px, creating distinct thematic content blocks.
- Employ the Fragment Mono font with its distinctive tight tracking (-0.0800em) for specific, functional metadata or code blocks.

### Don't
- Do not introduce new saturated colors outside of the defined 'Ember' and 'Peach' palette; deviations dilute brand impact.
- Avoid using drop shadows for elevation; rely on color changes and border contrasts to differentiate surfaces.
- Do not apply excessive letter-spacing to any text; the system prioritizes a compact, efficient typographic style.
- Refrain from using heavily decorative gradients; the system prefers solid color blocks and subtle accent lines.
- Do not use overly complex or illustrative imagery; favor clean product screenshots or abstract, brand-colored graphics.
- Avoid small, inconsistent border radii; adhere strictly to the 4px, 8px, 20px, 60px, and 80px radii for components.
- Do not cluster elements too densely; utilize the specified element and card padding (16px) and section gaps (170px) to ensure comfortable 'breathing room'.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#e4ddd5` | Primary background for general content sections, providing a warm, subtle base. |
| 2 | Card Surface | `#ffffff` | Background for individual actionable cards and components, offering a clean, bright layer. |
| 3 | Hero/Footer Background | `#151515` | Dominant dark background for hero sections and footers, creating strong visual anchors and contrast. |
| 4 | Accent Surface | `#dd3508` | Used for high-impact hero backgrounds and prominent content blocks, drawing immediate attention. |

## Imagery

The visual language features product screenshots of UI elements and abstract, geometric graphics that use the brand's primary Ember Orange and Peach Crush colors. Photography, when present, is minimal and likely product-focused rather than lifestyle. Icons are predominantly simple, outlined or solid forms, adhering to a monochrome or brand-colored palette. Imagery serves to explain product functionality or illustrate concepts in an abstract, clean way rather than decorative or social proof.

## Layout

The page uses a maximum width of 1361px, centered, with occasional full-bleed sections. The hero section is often a full-bleed block of Ember Orange or Charred Ink featuring a centered heading and subtext, followed by a call to action. Content sections maintain a consistent vertical rhythm with large section gaps (around 170px), often alternating between lighter Pale Ash and darker Charred Ink or Ember Orange backgrounds. Content arrangement frequently uses left-aligned text blocks with associated visuals or feature listings, often in a clear two-column grid. Navigation is a sticky top bar.

## Agent Prompt Guide

### Quick Color Reference
text: #4f4f4f
background: #e4ddd5
border: #1c1c1c
accent: #dd3508
primary action: #dd3508 (outlined action border)

### 3-5 Example Component Prompts
1. Create a hero section: Ember Orange background (#dd3508). Headline in Instrument Sans weight 600 at 48px, Whisper White text (#ffffff), letter-spacing -0.96px. Subtext in Instrument Sans weight 400 at 18px, Whisper White text (#ffffff).
2. Generate a Feature Card: Pale Ash background (#e4ddd5), 8px border-radius, 16px padding. Title in Instrument Sans weight 500 at 24px, Lead Gray text (#4f4f4f). Body text in Instrument Sans weight 400 at 16px, Lead Gray text (#4f4f4f).
3. Design a Primary Outlined Button: No background, 1px solid Ember Orange border (#dd3508), Ember Orange text (#dd3508), 8px border-radius, 12px vertical and 16px horizonal padding. Text in Instrument Sans weight 500 at 16px, letter-spacing -0.32px.
4. Create a Tag Badge: Sand Dune background (#d7cabb), Charred Ink text (#151515), 60px border-radius, 10px vertical and 15px horizontal padding. Text in Instrument Sans weight 400 at 14px, letter-spacing 0.0200em.
5. Design an Input Field: Transparent background, 1px solid Pale Ash border (#e4ddd5), 4px border-radius, 8px vertical and 12px horizontal padding. Placeholder text in Lead Gray (#4f4f4f), font Instrument Sans weight 400 at 16px.

## Similar Brands

- **Figma** — Clear, minimalist UI with strong accent color use for actions and highlights, alongside crisp typography.
- **Linear** — Efficient and compact typography, high-contrast dark sections, and emphasis on functional UI elements over heavy visuals.
- **Webflow** — Use of strong, vibrant brand colors in large sections, coupled with clean, direct sans-serif typography and structured layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ember-orange: #dd3508;
  --color-peach-crush: #f3b8a9;
  --color-copper-glow: #f03909;
  --color-sand-dune: #d7cabb;
  --color-charred-ink: #151515;
  --color-lead-gray: #4f4f4f;
  --color-whisper-white: #ffffff;
  --color-pale-ash: #e4ddd5;
  --color-ghost-gray: #333333;
  --color-obsidian-text: #000000;
  --color-slate-border: #1c1c1c;

  /* Typography — Font Families */
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragment-mono: 'Fragment Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.8px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 39px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.96px;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1361px;
  --section-gap: 170px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 60px;
  --radius-inputs: 4px;
  --radius-buttons: 8px;
  --radius-callout: 20px;

  /* Surfaces */
  --surface-page-canvas: #e4ddd5;
  --surface-card-surface: #ffffff;
  --surface-herofooter-background: #151515;
  --surface-accent-surface: #dd3508;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ember-orange: #dd3508;
  --color-peach-crush: #f3b8a9;
  --color-copper-glow: #f03909;
  --color-sand-dune: #d7cabb;
  --color-charred-ink: #151515;
  --color-lead-gray: #4f4f4f;
  --color-whisper-white: #ffffff;
  --color-pale-ash: #e4ddd5;
  --color-ghost-gray: #333333;
  --color-obsidian-text: #000000;
  --color-slate-border: #1c1c1c;

  /* Typography */
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragment-mono: 'Fragment Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.8px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 39px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;
}
```
