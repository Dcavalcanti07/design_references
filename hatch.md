# Hatch — Style Reference
> Bouncy Typographic Playground

**Theme:** light

Hatch builds a playful yet professional visual system on a soft off-white canvas, using bold, bouncy typography and a distinct accent palette. The design balances a strong typographic presence with whimsical, hand-drawn graphics. Functional elements, like buttons, often feature rounded corners and vibrant fills, creating clear calls to action amidst the light-hearted aesthetic. The overall impression is approachable, energetic, and distinctively memorable, avoiding typical corporate starkness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Creme | `#f5f4f0` | `--color-canvas-creme` | Page background, primary surface for container elements |
| Surface White | `#ffffff` | `--color-surface-white` | Card backgrounds, elevated UI elements, button fills for secondary actions |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Charcoal Text | `#222222` | `--color-charcoal-text` | Body text, secondary headings, link text |
| Muted Slate | `#333333` | `--color-muted-slate` | Navigation text, subtle borders, slightly less prominent textual elements |
| Border Ash | `#dddfe2` | `--color-border-ash` | Fine borders, dividers, ghost link outlines |
| Mint Accent | `#99ffcc` | `--color-mint-accent` | Primary button fills, highlighted text accents, decorative graphic elements. Commands attention cheerfully |
| Sky Blue | `#7bbbff` | `--color-sky-blue` | Decorative graphic accents, secondary highlight elements, product service cards |
| Orchid Pink | `#ff99cc` | `--color-orchid-pink` | Decorative graphic accents, subtle background elements, tertiary highlight |
| Sunset Orange | `#ffcc99` | `--color-sunset-orange` | Decorative graphic accents, tertiary highlights, background for specific card types |
| Deep Violet | `#26153f` | `--color-deep-violet` | Borders for secondary buttons, outlines for navigation items, complements Mint Accent |

## Tokens — Typography

### Recoleta — Primary display font for all headings and prominent titles. Its heavy weight and unique letterforms are a core brand identifier. · `--font-recoleta`
- **Substitute:** Playfair Display
- **Weights:** 700
- **Sizes:** 18px, 24px, 32px, 48px, 64px, 72px, 84px, 151px
- **Line height:** 1.00
- **Letter spacing:** -0.0280em
- **Role:** Primary display font for all headings and prominent titles. Its heavy weight and unique letterforms are a core brand identifier.

### Lota Grotes Que Alt — Primary body font, navigation, and button text. Provides clear readability and a modern, compact feel. · `--font-lota-grotes-que-alt`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 18px, 24px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Primary body font, navigation, and button text. Provides clear readability and a modern, compact feel.

### Lota Grotes Que Alt — Bold body text, subheadings, and emphasized elements. Works in conjunction with the lighter weight for emphasis without introducing new fonts. · `--font-lota-grotes-que-alt`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 14px, 18px, 24px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Bold body text, subheadings, and emphasized elements. Works in conjunction with the lighter weight for emphasis without introducing new fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 18px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.5 | — | `--text-subheading` |
| heading | 32px | 1.3 | -0.67px | `--text-heading` |
| heading-lg | 48px | 1.2 | -1px | `--text-heading-lg` |
| display | 64px | 1.1 | -1.34px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

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
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| pills | 1440px |
| small | 4px |
| buttons | 12px |
| heroElement | 40px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 24px
- **Card padding:** 28px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Main call to action

Mint Accent (#99ffcc) background with Midnight Ink (#000000) text. Border is Deep Violet (#26153f) at 1px thick. Padding 9.6px vertical, 28.8px horizontal. Radius 12px.

### Secondary Outlined Button
**Role:** Alternative call to action

Surface White (#ffffff) background with Midnight Ink (#000000) text. Border is Deep Violet (#26153f) at 1px thick. Padding 9.6px vertical, 28.8px horizontal. Radius 12px.

### Pill Ghost Button
**Role:** Compact, subtle interaction

Surface White (#ffffff) background with Midnight Ink (#000000) text. No explicit border specified; implies a natural border from background. Padding 1px vertical, 6px horizontal. Radius 1440px.

### Default Card
**Role:** Content grouping, feature display

Surface White (#ffffff) background with 16px border-radius. Padding 28px on all sides. No box shadow.

### Hero Feature Card
**Role:** Prominent content showcase

Surface White (#ffffff) background with 20px border-radius. Padding 48px on all sides. No box shadow.

### Full-bleed Card
**Role:** Large visual content container

Surface White (#ffffff) background with 40px border-radius. Uses 100px top padding but 0px for others, suggesting large images/illustrations within. No box shadow.

### Highlighted Heading
**Role:** Emphasis within a headline

A segment of a main heading (Recoleta 700) with a Mint Accent (#99ffcc) background. No extra padding or radius, intended for inline application.

### Navigation Link
**Role:** Primary navigation item

Muted Slate (#333333) text (Lota Grotes Que Alt 400). Padded 7px vertical and 20px horizontal. Unspecified border, but implied interactive behavior based on text color.

## Do's and Don'ts

### Do
- Use Recoleta 700 and Lota Grotes Que Alt (400/700) exclusively for all text elements to maintain typographic consistency.
- Apply Canvas Creme (#f5f4f0) as the base page background and Surface White (#ffffff) for all card backgrounds and elevated components.
- Prioritize Mint Accent (#99ffcc) for primary calls to action, such as button fills, and Deep Violet (#26153f) for secondary button borders.
- Ensure all interactive elements and buttons are given a 12px border-radius, while cards use 16px for a consistent soft-edged aesthetic.
- Maintain a minimum element spacing of 24px and card padding of 28px to ensure a spacious and airy layout.
- Use Midnight Ink (#000000) for high-impact headlines and primary text, reserving Charcoal Text (#222222) for standard body copy.
- Integrate Sky Blue (#7bbbff), Orchid Pink (#ff99cc), and Sunset Orange (#ffcc99) sparingly as decorative graphic accents to infuse playfulness without overwhelming the UI.

### Don't
- Do not introduce new fonts or weights beyond Recoleta 700 and Lota Grotes Que Alt (400/700).
- Avoid using saturation for background surfaces; keep them in the neutral palette of Canvas Creme and Surface White.
- Refrain from using hard-edged elements; prefer rounded corners, with 12px for interactive elements and 16px for cards.
- Do not use generic box shadows; the design relies on flat surfaces with subtle color boundaries, not elevation effects.
- Do not use a narrow content width; ensure content is constrained to a 1200px max-width, with generous horizontal padding.
- Avoid dark-mode interpretations; this system is designed for a light theme with vibrant accents.
- Do not use highly textured backgrounds for UI components; surfaces should remain clean and flat to highlight content and accent colors.

## Imagery

The visual language for imagery and graphics is playful, illustrative, and abstract. It features custom, hand-drawn vector elements with a slightly whimsical, almost doodle-like quality, distinct from typical corporate illustrations. These graphics combine outlines and filled shapes, often leveraging the accent color palette (Sky Blue, Orchid Pink, Sunset Orange, Mint Accent). Examples include speech bubble characters with headphones and scattered geometric shapes (squiggles, dots, lightnings). They serve a decorative and atmospheric role rather than strictly explanatory, adding a sense of energy and brand personality. Image density is moderate, used to break up text-heavy sections and add visual interest, but the UI remains text-dominant.

## Layout

The page adheres to a max-width 1200px contained layout, centered on a Canvas Creme background. The hero section is full-width with a centered, bold Recoleta headline and a mix of primary and secondary buttons, framed by scattered decorative illustrations. Subsequent sections maintain a consistent vertical rhythm, primarily consisting of text-dominant blocks, often with left-aligned headings and body text. Content is frequently presented in clear, discrete cards with generous padding acting as containers. Feature sections often employ multi-column grids or alternating text-and-visual arrangements, maintaining a spacious density between content blocks. A sticky top navigation bar provides consistent access to key links and a prominent 'Book a Call' button.

## Agent Prompt Guide

Quick Color Reference: text: #000000, background: #f5f4f0, border: #26153f, accent: #99ffcc, primary action: #99ffcc (filled action)

Create a Primary Action Button: #99ffcc background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: Surface White background, 16px radius, 28px padding. Headline 'Video Clips' Recoleta 700 at 24px, Midnight Ink. Body text 'We’ll create custom, short-form video clips...' Lota Grotes Que Alt 400 at 18px, Charcoal Text. Include a small decorative graphic in Mint Accent and Sunset Orange.

## Similar Brands

- **Rive** — Shares a playful, illustrative aesthetic with custom graphics and a clean, light UI with distinct accent colors.
- **Framer** — Uses bold, opinionated typography for headlines and a spacious, component-driven layout on a light canvas.
- **Contra** — Exhibits a similar use of vibrant, playful accent colors against a largely neutral background, combined with distinct roundness in UI elements.
- **Linear** — While more stark, it shares the principle of a clear, spacious UI and sharp typographic hierarchy with a distinct brand color used for accents and actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-creme: #f5f4f0;
  --color-surface-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-charcoal-text: #222222;
  --color-muted-slate: #333333;
  --color-border-ash: #dddfe2;
  --color-mint-accent: #99ffcc;
  --color-sky-blue: #7bbbff;
  --color-orchid-pink: #ff99cc;
  --color-sunset-orange: #ffcc99;
  --color-deep-violet: #26153f;

  /* Typography — Font Families */
  --font-recoleta: 'Recoleta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lota-grotes-que-alt: 'Lota Grotes Que Alt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.67px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -1.34px;

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
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-172: 172px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 24px;
  --card-padding: 28px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 1440px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-pills: 1440px;
  --radius-small: 4px;
  --radius-buttons: 12px;
  --radius-heroelement: 40px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-creme: #f5f4f0;
  --color-surface-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-charcoal-text: #222222;
  --color-muted-slate: #333333;
  --color-border-ash: #dddfe2;
  --color-mint-accent: #99ffcc;
  --color-sky-blue: #7bbbff;
  --color-orchid-pink: #ff99cc;
  --color-sunset-orange: #ffcc99;
  --color-deep-violet: #26153f;

  /* Typography */
  --font-recoleta: 'Recoleta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lota-grotes-que-alt: 'Lota Grotes Que Alt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.67px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -1.34px;

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
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 1440px;
}
```
