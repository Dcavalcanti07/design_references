# Midday — Style Reference
> Achromatic ledger, crisp yet silent

**Theme:** light

Midday uses a minimalist, content-focused visual language with a strong emphasis on readability and clean information architecture. The design balances crisp sans-serif with a commanding serif for headlines, all within an open, achromatic canvas. Subtle borders and ghost-like components keep the interface feeling lightweight and direct, with a monochromatic palette reinforcing a sense of serious utility and precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default icon fill — creates a bright, expansive foundation |
| Ink Black | `#121212` | `--color-ink-black` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |
| Ash Gray | `#dbdad7` | `--color-ash-gray` | Hairline borders for cards, buttons, and decorative separators — defines structure without visual weight, echoing traditional ledger paper |
| Deep Graphite | `#18181b` | `--color-deep-graphite` | Primary action button background — provides a strong, serious focal point for key interactions against the light canvas |
| Cool Gray Mist | `#e6e4e0` | `--color-cool-gray-mist` | Subtle background for secondary sections, selected tabs, and subtle hints of elevation — adds textural variation within the neutral palette |
| Muted Stone | `#616161` | `--color-muted-stone` | Secondary text, link text, helper text, and subtle icon strokes — provides hierarchy and de-emphasizes content gently |
| Success Green | `#4caf50` | `--color-success-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Hedvig Letters Sans — Primary UI text, body copy, navigation, button labels, and small headings — maintains clarity and compactness across the interface. · `--font-hedvig-letters-sans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 10px, 11px, 12px, 14px, 16px, 18px, 20px, 24px, 48px, 508px
- **Line height:** 1.00, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** 0.0250em for lighter weights, 0.0500em for smaller body text
- **Role:** Primary UI text, body copy, navigation, button labels, and small headings — maintains clarity and compactness across the interface.

### Hedvig Letters Serif — Prominent headings and display text — its formal, open character with generous negative tracking creates a sense of established authority and elegant presence. · `--font-hedvig-letters-serif`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 24px, 72px
- **Line height:** 1.00, 1.33
- **Letter spacing:** -0.0250em
- **Role:** Prominent headings and display text — its formal, open character with generous negative tracking creates a sense of established authority and elegant presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.5px | `--text-caption` |
| body | 14px | 1.56 | 0.25px | `--text-body` |
| subheading | 18px | 1.4 | 0.25px | `--text-subheading` |
| heading-sm | 24px | 1.33 | -0.25px | `--text-heading-sm` |
| heading | 48px | 1 | -1.2px | `--text-heading` |
| display | 72px | 1 | -1.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 224 | 224px | `--spacing-224` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| icons | 8px |
| input | 0px |
| badges | 9999px |
| buttons | 9999px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 24px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Pill Button - Default
**Role:** Default interactive button

White background (#ffffff), Ink Black text (#121212), 1px Ash Gray border (#dbdad7), 9999px border-radius for a pill shape. Padding 6px vertical, 12px horizontal. Used for secondary actions and navigation entries.

### Solid Button - Primary
**Role:** Primary call to action button

Solid Deep Graphite background (#18181b), Canvas White text (#ffffff), no border, 0px border-radius. Padding 8px vertical, 24px horizontal. Commands attention for key actions like 'Start your trial'.

### Ghost Button
**Role:** Ghost-style button for secondary actions or toggles

Transparent background, Muted Stone text (#616161), 1px Ash Gray border (#dbdad7), 0px border-radius. Padding 8px vertical, 12px horizontal. Used for subtle toggles like 'Monthly'/'Yearly' selectors.

### Integration Card Variant
**Role:** Card for displaying tool integrations

Canvas White background (#ffffff), no shadow, 0px border-radius. Features 20px padding on all sides. Used for displaying individual integration tiles.

### Feature Card
**Role:** Information card for features or pricing

Canvas White background (#ffffff), no shadow, 0px border-radius. Features 20px padding on all sides. Used for presenting pricing tiers or descriptive content blocks.

### Badge - Introducing
**Role:** Informational badge for new features

Transparent background, Muted Stone text (#616161), 1px Ash Gray border (#dbdad7), 9999px border-radius. Padding 6px vertical, 12px horizontal. Used for concise announcements.

## Do's and Don'ts

### Do
- Use Hedvig Letters Sans at weight 400 for all body text and UI elements, with Ink Black (#121212) as the default text color.
- Apply Hedvig Letters Serif at weight 400 and letter-spacing -0.0250em for main headings and display text, using Ink Black (#121212).
- Define all structural boundaries with a 1px solid Ash Gray (#dbdad7) border to maintain a lightweight, precise aesthetic.
- Utilize Canvas White (#ffffff) as the dominant background for all primary content surfaces and page canvas.
- Form primary action buttons with a solid Deep Graphite (#18181b) background and Canvas White (#ffffff) text, always with a 0px border-radius.
- Ensure all interactive elements and badges with a soft, secondary role use a 9999px radii, contrasting with the sharp corners of content cards.
- Maintain a clear visual hierarchy by applying Muted Stone (#616161) for secondary text and helper elements.

### Don't
- Avoid using box-shadows; visible elevation is created through subtle background color changes or strong typographic hierarchy instead.
- Do not introduce additional chromatic colors beyond Success Green (#4caf50), reserving it exclusively for semantic indicators and data accents.
- Never use rounded corners on content cards or panels; maintain the sharp, square aesthetic (0px radius) for all informational containers.
- Do not vary line-height unless explicitly defined by the type scale; follow the specified line-heights for each font size to maintain vertical rhythm.
- Avoid using bold weights for body text; rely on color contrast and spacing for emphasis within paragraphs.
- Do not use gradients for backgrounds or components; the system relies on flat colors and subtle textural variation.
- Refrain from using decorative imagery or full-bleed photography that breaks the clean, high-key achromatic canvas.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, foundational for all content. |
| 1 | Card Base | `#ffffff` | Background for primary content cards and information blocks. |
| 2 | Muted Section | `#e6e4e0` | Background for subtle alternations in section backgrounds or selected interface elements. |

## Imagery

The visual language predominantly features clean, small, outline-style icons with a clear, functional purpose, often rendered in Ink Black. Product screenshots are contained within card-like structures, showcasing UI elements against the site's achromatic background. No large-scale marketing photography or complex illustrations are present, reinforcing a functional, content-first approach. Visuals serve to explain or denote, not to decorate.

## Layout

The page adheres to a max-width 1280px, center-aligned layout, creating a contained and structured experience. The hero section features a prominent, centered headline with supporting text, followed by a dark primary action button against the white canvas. Section rhythm is primarily created through consistent vertical spacing (sectionGap 24px) rather than alternating background colors. Content is often arranged in centered stacks or simple grids, such as 3-column feature/pricing cards or alternating text+icon blocks. Navigation is a minimalist top bar with ghost-like links and a 'Sign in' call to action, maintaining a light footprint.

## Agent Prompt Guide

Quick Color Reference: 
text: #121212
background: #ffffff
border: #dbdad7
accent: #4caf50
primary action: #18181b (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #18181b background, #616161 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a Feature Card: Canvas White background (#ffffff), 0px border-radius, 20px padding. Inside, 'Reporting' as a subheading (18px Hedvig Letters Sans weight 400, #121212, line-height 1.4) followed by body text 'Detailed daily reports' (14px Hedvig Letters Sans weight 400, #121212, line-height 1.56).
3. Create a Ghost Toggle Button: Transparent background, Muted Stone text (#616161), 1px Ash Gray border (#dbdad7), 0px border-radius. Padding 8px vertical, 12px horizontal. Text 'Monthly'.

## Similar Brands

- **Stripe** — High-contrast achromatic palette, minimal borders, and a focus on clarity in product UI, with a similar serif for display text.
- **Linear** — Monochromatic interface with subtle border work and controlled typography, prioritizing information density over visual decoration.
- **Mercury** — Clean, understated financial tech aesthetic, reliance on typography and whitespace to create hierarchy, rather than heavy color or elevation.
- **Segment** — Systematic use of neutral tones, sharp edges for containers, and clear, functional typefaces to convey a sense of technical precision.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #121212;
  --color-ash-gray: #dbdad7;
  --color-deep-graphite: #18181b;
  --color-cool-gray-mist: #e6e4e0;
  --color-muted-stone: #616161;
  --color-success-green: #4caf50;

  /* Typography — Font Families */
  --font-hedvig-letters-sans: 'Hedvig Letters Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hedvig-letters-serif: 'Hedvig Letters Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.56;
  --tracking-body: 0.25px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.25px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.25px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.2px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-224: 224px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 24px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-icons: 8px;
  --radius-input: 0px;
  --radius-badges: 9999px;
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-card-base: #ffffff;
  --surface-muted-section: #e6e4e0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #121212;
  --color-ash-gray: #dbdad7;
  --color-deep-graphite: #18181b;
  --color-cool-gray-mist: #e6e4e0;
  --color-muted-stone: #616161;
  --color-success-green: #4caf50;

  /* Typography */
  --font-hedvig-letters-sans: 'Hedvig Letters Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hedvig-letters-serif: 'Hedvig Letters Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.56;
  --tracking-body: 0.25px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.25px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.25px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.2px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-224: 224px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;
}
```
