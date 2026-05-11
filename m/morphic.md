# Morphic — Style Reference
> Midnight Command Canvas — a high-contrast dark mode for creative focus.

**Theme:** dark

Morphic employs a dark, immersive interface, reminiscent of a command center for creative production. The design is characterized by its ample use of deep black backgrounds and dark gray surfaces, providing high contrast for white text and UI elements. A vivid blue serves as the primary accent color, reserved for key actions and highlights, giving a 'switched-on' feel to active components. Typography is compact and precise, maintaining clarity within the high-contrast dark theme. Interactivity is subtle, often indicated by color changes rather than heavy shadows or complex animations.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#0075ff` | `--color-absolute-zero` | Primary action backgrounds, interactive elements, brand highlights — a clear, vivid blue provides immediate visual feedback |
| Ebony Canvas | `#000000` | `--color-ebony-canvas` | Page backgrounds, primary container fills, text color for light surfaces |
| Nightfall Gray | `#212121` | `--color-nightfall-gray` | Secondary surface backgrounds, elevated panels, and distinct content blocks within the dark canvas |
| Charcoal Surface | `#292929` | `--color-charcoal-surface` | Tertiary surface backgrounds, subtle hover states for dark buttons |
| Deep Graphite | `#333333` | `--color-deep-graphite` | Minor button backgrounds, subtle content separators |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary text, iconography, active state fills on dark backgrounds, ghost button backgrounds |
| Light Mist | `#f5f5f5` | `--color-light-mist` | Secondary text, button text, subtle iconography |
| Outline Haze | `#e5e7eb` | `--color-outline-haze` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Muted Silver | `#999999` | `--color-muted-silver` | Muted helper text, secondary navigation text, inactive icon fills |
| Subtle Gray | `#737373` | `--color-subtle-gray` | Placeholder text, link text in neutral contexts, supportive body copy |
| Anchor Graphite | `#525252` | `--color-anchor-graphite` | Timestamps and duration indicators, less prominent contextual information |
| Dim Gray | `#404040` | `--color-dim-gray` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |

## Tokens — Typography

### Inter — The primary typeface for all text content, from headings to body copy and interface elements. Its multiple weights and compact line heights ensure legibility and a consistent modern feel against dark backgrounds. Tighter letter spacing on larger sizes maintains visual density. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 40px, 52px
- **Line height:** 1.00, 1.15, 1.17, 1.20, 1.29, 1.33, 1.38, 1.40, 1.44, 1.48, 1.50
- **Letter spacing:** -0.0620em, -0.0480em, -0.0220em, -0.0200em, -0.0150em, -0.0140em, -0.0100em
- **Role:** The primary typeface for all text content, from headings to body copy and interface elements. Its multiple weights and compact line heights ensure legibility and a consistent modern feel against dark backgrounds. Tighter letter spacing on larger sizes maintains visual density.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.1px | `--text-caption` |
| body | 14px | 1.33 | -0.22px | `--text-body` |
| body-lg | 16px | 1.29 | -0.256px | `--text-body-lg` |
| subheading | 18px | 1.2 | -0.27px | `--text-subheading` |
| heading | 20px | 1.15 | -0.28px | `--text-heading` |
| heading-lg | 40px | 1.17 | -0.96px | `--text-heading-lg` |
| display | 52px | 1 | -1.352px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 140 | 140px | `--spacing-140` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| cards | 10px |
| buttons | 7px |
| heroCards | 32px |
| largeElements | 16px |
| superLargeElements | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |

### Layout

- **Section gap:** 96px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action.

Background: Absolute Zero (#0075ff). Text: Light Mist (#f5f5f5). Padding: 8px vertical, 12px horizontal. Border radius: 7px.

### Secondary Ghost Button
**Role:** Outline button for secondary actions, often in groups with a primary button.

Background: rgba(100, 100, 100, 0.16) for a very subtle dark overlay. Text: Light Mist (#f5f5f5). Padding: 9px vertical, 18px horizontal. Border radius: 100px (pill shape).

### Muted Ghost Button
**Role:** Low-prominence buttons in interface sections, such as action bars or content filters.

Background: rgba(100, 100, 100, 0.1) for a subtle dark wash. Text: Cloud White (#ffffff). Padding: 8px vertical, 12px to 16px horizontal. Border radius: 100px (pill shape).

### Card without Background
**Role:** Content card with no visible background, relying on content for definition, often used for image grids.

Background: rgba(0, 0, 0, 0) (fully transparent). Border radius: 0px. No box shadow.

### Content Thumbnail Card
**Role:** Interactive cards displaying visual content, often with overlaid text.

Background: lab(0 0 0 / 0.6) (translucent dark). Border radius: 10px. No box shadow. Padding: 0px.

### Feature Highlight Card
**Role:** Elevated card for prominent features or sections, characterized by a soft, rounded appearance.

Background: rgba(255, 255, 255, 0.05) (translucent subtle white). Border radius: 32px. No box shadow. Padding: 0px.

### Pill Tag
**Role:** Small, rounded labels for categories, states, or short information snippets.

Background: Ebony Canvas (#000000). Text: Cloud White (#ffffff). Border radius: 100px. Padding (variable based on content).

## Do's and Don'ts

### Do
- Prioritize Cloud White (#ffffff) text on Ebony Canvas (#000000) or Nightfall Gray (#212121) backgrounds for all primary content.
- Use Absolute Zero (#0075ff) exclusively for primary calls to action or essential interactive elements.
- Apply a 7px border radius to all filled buttons to maintain a consistent, moderately rounded feel.
- Utilize Inter font consistently across all text elements, adjusting weight and letter spacing according to semantic role and size.
- Maintain horizontal spacing between elements with 8px (elementGap) or 12px for denser layouts, ensuring visual separation.
- Employ Nightfall Gray (#212121) for distinct background panels to create visual separation without losing dark theme immersion.

### Don't
- Avoid using saturated colors other than Absolute Zero (#0075ff) for UI elements; chromatic color should be a rare accent.
- Do not use heavy, opaque shadows on UI elements; prefer subtle, dark-mode friendly elevation effects when necessary (e.g., rgba(0, 0, 0, 0.1) shadows).
- Refrain from drastically altering button padding; stick to the defined vertical (8-9px) and horizontal (12-18px) ranges.
- Do not introduce sharp, unrounded corners for interactive components or cards; leverage the defined radii (7px, 10px, 16px, 32px, 100px).
- Avoid using light backgrounds for major sections; the canvas should predominantly be Ebony Canvas (#000000) or Nightfall Gray (#212121).
- Do not use generic system fonts; Inter is the sole typeface for brand consistency.

## Imagery

The visual language relies heavily on impactful, high-resolution photography and video stills, often focused on creative processes or dynamic scenes. Imagery is typically displayed within cards with soft 10px rounded corners or full-bleed across sections, but never overlapping organically. There's a preference for dark, cinematic product shots or abstract visuals that complement the dark UI. Icons are minimal, mostly monochrome (Cloud White #ffffff or Muted Silver #999999), outlined, and functional, serving to explain or navigate rather than decorate. The density is image-heavy, with large blocks of visuals interspersed with concise text.

## Layout

The page uses a full-bleed layout for the base canvas, which is Ebony Canvas (#000000), but often contains content within a logical max-width structure (though not explicitly defined, the header and main content blocks appear centered and constrained). The hero section typically features a large, dark background with centered, prominent headlines and a two-button Call-to-Action. Sections maintain a consistent vertical rhythm with 96px gaps. Content is arranged in alternating visual patterns, such as a large image grid (multiple columns) followed by more textual blocks. Navigation is a sticky top bar, minimally styled with Cloud White text on the dark canvas.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e5e7eb
accent: #0075ff
primary action: #0075ff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #0075ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a content card grid item: Card without Background with a large image inside, overlaid with 'Time-freeze effect' as heading-lg size (40px Inter, weight 700, #ffffff, letter-spacing -0.96px) and 'Run workflow' button (Muted Ghost Button: rgba(100, 100, 100, 0.1) background, #ffffff text, 8px vertical padding, 12px to 16px horizontal, 100px radius).
3. Create a feature block: Nightfall Gray (#212121) background. Heading 'Explore with Canvas' at heading-lg (40px Inter, weight 700, #ffffff, letter-spacing -0.96px). Below, a Pill Tag 'New' with Ebony Canvas (#000000) background, #ffffff text, and 100px radius.

## Similar Brands

- **Framer** — Dark UI with a single vivid accent color for interactivity, strong typography, and emphasis on product visuals.
- **Linear** — Minimalist dark theme, precise typography, and a deliberate use of color for functional elements rather than decoration.
- **Raycast** — Command-line interface aesthetic translated to a UI, high-contrast dark mode, sharp but functional use of color accents.
- **Vercel** — Dark theme with clean lines, functional use of a brand blue accent, and focused on showcasing dynamic content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #0075ff;
  --color-ebony-canvas: #000000;
  --color-nightfall-gray: #212121;
  --color-charcoal-surface: #292929;
  --color-deep-graphite: #333333;
  --color-cloud-white: #ffffff;
  --color-light-mist: #f5f5f5;
  --color-outline-haze: #e5e7eb;
  --color-muted-silver: #999999;
  --color-subtle-gray: #737373;
  --color-anchor-graphite: #525252;
  --color-dim-gray: #404040;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.1px;
  --text-body: 14px;
  --leading-body: 1.33;
  --tracking-body: -0.22px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.29;
  --tracking-body-lg: -0.256px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.27px;
  --text-heading: 20px;
  --leading-heading: 1.15;
  --tracking-heading: -0.28px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 52px;
  --leading-display: 1;
  --tracking-display: -1.352px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-140: 140px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-cards: 10px;
  --radius-buttons: 7px;
  --radius-herocards: 32px;
  --radius-largeelements: 16px;
  --radius-superlargeelements: 24px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #0075ff;
  --color-ebony-canvas: #000000;
  --color-nightfall-gray: #212121;
  --color-charcoal-surface: #292929;
  --color-deep-graphite: #333333;
  --color-cloud-white: #ffffff;
  --color-light-mist: #f5f5f5;
  --color-outline-haze: #e5e7eb;
  --color-muted-silver: #999999;
  --color-subtle-gray: #737373;
  --color-anchor-graphite: #525252;
  --color-dim-gray: #404040;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.1px;
  --text-body: 14px;
  --leading-body: 1.33;
  --tracking-body: -0.22px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.29;
  --tracking-body-lg: -0.256px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.27px;
  --text-heading: 20px;
  --leading-heading: 1.15;
  --tracking-heading: -0.28px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 52px;
  --leading-display: 1;
  --tracking-display: -1.352px;

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
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-140: 140px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
}
```
