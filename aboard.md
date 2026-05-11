# Aboard — Style Reference
> Warm earth against dark steel

**Theme:** dark

Aboard projects a grounded, sophisticated competence with a dark canvas, warm earthy accents, and a distinctive serif typeface for headlines. Monochrome textures and subtle borders create visual depth and structure, ensuring content feels substantial without being heavy. The design balances a serious, technical impression with approachable elements, using bold orange as a precise highlight for interactive elements and brand accents.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ember Glow | `#de4c00` | `--color-ember-glow` | Primary action backgrounds, link accents, functional icons — a vivid, warm orange that cuts through the dark palette |
| Peach Fuzz | `#efa680` | `--color-peach-fuzz` | Orange outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Deep Forest | `#040c06` | `--color-deep-forest` | Primary page background, extensive dark surfaces, and text on light surfaces |
| Warm Black | `#271503` | `--color-warm-black` | Main text color on light parchment backgrounds, subheadings, and muted body text on dark backgrounds |
| Parchment | `#eadfcf` | `--color-parchment` | Accent backgrounds for cards and highlighted content sections. Also used for some body and heading text on dark backgrounds |
| Stone Slate | `#a49784` | `--color-stone-slate` | Subtle background for navigation and secondary UI elements |
| Light Steel | `#e5e7eb` | `--color-light-steel` | Border colors for inputs, cards, and image outlines. Used widely for structural delineation |
| White Canvas | `#fffefb` | `--color-white-canvas` | Prominent surface accents and primary text color on dark backgrounds, offering high contrast |
| Pale Gray | `#c1bdba` | `--color-pale-gray` | Subtle border color, distinct from Light Steel, for layered elements |
| True Black | `#000000` | `--color-true-black` | Used for text over light backgrounds and occasional structural outlines |

## Tokens — Typography

### Tobias — Display and major headings — its elegant structure and light 300 weight command attention without shouting, providing sophistication. · `--font-tobias`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 24px, 32px, 72px
- **Line height:** 1.10, 1.30
- **Letter spacing:** -0.48, 0.48
- **Role:** Display and major headings — its elegant structure and light 300 weight command attention without shouting, providing sophistication.

### Atkinson Hyperlegible Mono — Specialized text, code snippets, and certain list items — its monospaced nature anchors technical references and offers a distinct textural contrast. · `--font-atkinson-hyperlegible-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 300
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 1.57, 1.60, 1.63, 1.83
- **Letter spacing:** -0.2, 0.5
- **Role:** Specialized text, code snippets, and certain list items — its monospaced nature anchors technical references and offers a distinct textural contrast.

### Work Sans — Navigation, body text, and button labels — a clean, legible workhorse that maintains consistency across interactive elements. · `--font-work-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.63, 1.83
- **Letter spacing:** -0.2, -0.17
- **Role:** Navigation, body text, and button labels — a clean, legible workhorse that maintains consistency across interactive elements.

### ui-sans-serif — Default system font for general UI elements, ensuring broad compatibility and accessibility for supplementary text. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** 0
- **Role:** Default system font for general UI elements, ensuring broad compatibility and accessibility for supplementary text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.57 | 0.5px | `--text-caption` |
| body | 16px | 1.83 | — | `--text-body` |
| heading-sm | 24px | 1.3 | 0.48px | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.48px | `--text-heading` |
| display | 72px | 1.1 | -0.48px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |
| 152 | 152px | `--spacing-152` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| links | 8px |
| buttons | 9999px |
| navigation | 30px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Calls to action that drive core user flow.

Filled with Ember Glow (#de4c00) background and White Canvas (#fffefb) text. Features 9999px border-radius for a pill shape and 10px vertical, 16px horizontal padding.

### Parchment Card Button
**Role:** Secondary action or informational button within content areas.

Filled with Parchment (#f3f2ee) background and True Black (#000000) text. Features 8px border-radius and 24px padding on all sides.

### Navigation Link
**Role:** Top-level navigation items.

Text in Work Sans, weight 400. Text color is White Canvas (#fffefb). Active states may show an Ember Glow accent. Padding is 6px vertical, 16px horizontal.

### Image Card
**Role:** Container for imagery, often with textual overlay.

Features a 1px Light Steel (#e5e7eb) border. Image content is often contained with crisp borders.

### Hero Headline
**Role:** Prominent, attention-grabbing titles for key sections.

Utilizes Tobias font, weight 300, typically at 72px with a letter-spacing of -0.48px. Text color is White Canvas (#fffefb).

## Do's and Don'ts

### Do
- Use Deep Forest (#040c06) as the default background for large page sections to maintain the system's dark theme.
- Apply Ember Glow (#de4c00) exclusively for primary interactive elements, ensuring its impact as a functional accent.
- Employ the Tobias font for all primary headlines, leveraging its elegant 300 weight at larger sizes (e.g., 72px display, 32px heading) for a distinctive brand voice.
- Maintain comfortable element spacing with an 8px base unit using 8px elementGap for small separations and 64px for sectionGap between major content blocks.
- Use 9999px border-radius for all primary buttons to achieve a consistent pill-shaped aesthetic.
- Structure content with clear, subtle delineation using Light Steel (#e5e7eb) borders, especially around interactive and visual components.
- Incorporate Parchment (#eadfcf) backgrounds for highlighted informational cards or secondary content blocks to introduce a warm neutral contrast.

### Don't
- Avoid using Ember Glow (#de4c00) for purely decorative purposes; reserve it for actionable elements to prevent visual noise.
- Do not deviate from the specified font families or their prescribed weights and letter spacing; unique type choices define the brand's readability and tone.
- Refrain from introducing arbitrary background colors; stick to the approved color palette and surface hierarchy to maintain visual coherence.
- Do not use hard, sharp angles for interactive elements; buttons and links should adhere to the established radii of 8px or 9999px.
- Avoid using multiple chromatic colors in close proximity; the design relies on a single accent hue to guide user attention.
- Do not assume default system font usage for body text; Work Sans should be preferred for readability in content areas.
- Do not overcrowd sections; utilize the 64px sectionGap to provide ample breathing room between major content blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Forest Canvas | `#040c06` | Primary page and main section backgrounds. |
| 1 | Stone Slate Base | `#a49784` | Subtle background for persistent elements like navigation bars. |
| 2 | Parchment Highlight | `#eadfcf` | Accent backgrounds for cards, embedded forms, or informational panels, providing visual pop against the primary dark background. |

## Imagery

This site features a blend of high-definition, somewhat desaturated photography and product-focused visuals. Photography (warehouses, office environments) generally serves as full-bleed, atmospheric backgrounds, often slightly darkened or tinted to allow text overlays. Product-related imagery appears as contained, crisp visuals with subtle Light Steel (#e5e7eb) borders. The treatment is functional and explanatory, aiming for clarity and a sense of scale, rather than highly stylized or abstract graphics. Icons appear as simple, functional elements, often filled with Ember Glow (#de4c00) or White Canvas (#fffefb).

## Layout

The page primarily uses a full-bleed layout, particularly for hero sections and full-width image displays. Content often centers with implied wide margins, suggesting a max-width approach despite the full-bleed visual. The hero pattern features a full-viewport image with a large, centered headline in White Canvas (#fffefb) and a prominent Ember Glow (#de4c00) call-to-action. Section rhythm alternates between full-bleed imagery and content blocks with generous vertical spacing (64px sectionGap). Content is arranged in alternating text-left, image-right patterns or as stacked, centered text blocks. Navigation is a sticky top bar, minimally styled, with the Ember Glow Primary Action Button highlighted.

## Agent Prompt Guide

Quick Color Reference:
text: #fffefb
background: #040c06
border: #e5e7eb
accent: #de4c00
primary action: #de4c00 (filled action)

Example Component Prompts:
1. Create a Hero Section: Deep Forest (#040c06) background with a full-bleed, desaturated photograph. Overlay a 72px Tobias font (weight 300, #fffefb, letter-spacing -0.48px) headline. Below it, add a primary action button (Ember Glow #de4c00 background, White Canvas #fffefb text, 9999px radius, 10px vertical 16px horizontal padding).
2. Design a Testimonial Card: Parchment (#eadfcf) background with 8px radius. Use Warm Black (#271503) for body text in Work Sans, weight 400. Include a subtle 1px Light Steel (#e5e7eb) border at its base.
3. Create a Primary Action Button: #de4c00 background, #fffefb text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Craft a Feature Block: Deep Forest (#040c06) background. Apply a heading with Tobias font, 32px, weight 300, and White Canvas (#fffefb) text. Content features Atkinson Hyperlegible Mono for emphasized points and Work Sans for body text, both in White Canvas (#fffefb).

## Similar Brands

- **Stripe** — Similar dark, minimalist aesthetic with functional accent colors and a focus on clean typography for complex technical content.
- **Anthropic** — Shares a sophisticated, muted color palette that allows a single vivid accent to stand out, conveying seriousness and precision.
- **Relume** — Employs distinct primary and secondary typefaces where a decorative serif meets a clean sans-serif for structured content.
- **Vercel** — Dark theme with subtle surface shifts and a primary accent color for calls to action, creating a modern, high-tech impression.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ember-glow: #de4c00;
  --color-peach-fuzz: #efa680;
  --color-deep-forest: #040c06;
  --color-warm-black: #271503;
  --color-parchment: #eadfcf;
  --color-stone-slate: #a49784;
  --color-light-steel: #e5e7eb;
  --color-white-canvas: #fffefb;
  --color-pale-gray: #c1bdba;
  --color-true-black: #000000;

  /* Typography — Font Families */
  --font-tobias: 'Tobias', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atkinson-hyperlegible-mono: 'Atkinson Hyperlegible Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.57;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.83;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: 0.48px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-152: 152px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-links: 8px;
  --radius-buttons: 9999px;
  --radius-navigation: 30px;

  /* Surfaces */
  --surface-deep-forest-canvas: #040c06;
  --surface-stone-slate-base: #a49784;
  --surface-parchment-highlight: #eadfcf;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ember-glow: #de4c00;
  --color-peach-fuzz: #efa680;
  --color-deep-forest: #040c06;
  --color-warm-black: #271503;
  --color-parchment: #eadfcf;
  --color-stone-slate: #a49784;
  --color-light-steel: #e5e7eb;
  --color-white-canvas: #fffefb;
  --color-pale-gray: #c1bdba;
  --color-true-black: #000000;

  /* Typography */
  --font-tobias: 'Tobias', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atkinson-hyperlegible-mono: 'Atkinson Hyperlegible Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.57;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.83;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: 0.48px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-152: 152px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 9999px;
}
```
