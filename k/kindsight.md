# Kindsight — Style Reference
> Warm academia, tailored intelligence

**Theme:** light

Kindsight establishes an earthy, academic aesthetic with a strong emphasis on content hierarchy and a deliberate, almost vintage feel. The system combines precise, generously tracked serif headlines with functional sans-serif body text against a canvas of warm, muted neutrals. Vibrant amber and terracotta accents punctuate the otherwise subdued palette, drawing attention to calls-to-action and key information. Components are distinct and substantial, often with rounded corners, contributing to an impression of thoughtful craftsmanship.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greengage | `#3d4128` | `--color-greengage` | Hero background, footer background, dark card text, subtle button borders — a deep, muted green that anchors sections and provides a strong contrast for light text |
| Sunbeam | `#e1f079` | `--color-sunbeam` | Decorative highlights, emphasized heading elements, light button backgrounds — a vivid, almost neon green-yellow that injects energy and modernity into the otherwise mature palette |
| Terracotta Sunset | `#de7653` | `--color-terracotta-sunset` | Primary action button backgrounds and borders, link highlight — a warm, inviting reddish-orange that signifies interactivity and draws immediate attention |
| Ember Clay | `#e7573d` | `--color-ember-clay` | Secondary action button backgrounds and borders — a slightly more saturated, red-leaning orange for calls to action, maintaining warmth |
| Off-Black Pine | `#0e0f0a` | `--color-off-black-pine` | Primary text, strong borders, icon fills — the darkest neutral, used for high contrast text and structural lines |
| Vanilla Beam | `#faf5f1` | `--color-vanilla-beam` | Page background, input backgrounds, navigation highlights, subtle card borders — a warm, light cream that provides the primary canvas |
| Paper White | `#fefffa` | `--color-paper-white` | Elevated card backgrounds, light button text — a brighter off-white used for surfaces atop the main canvas, adding a subtle lift |
| Barely There | `#e5e1d6` | `--color-barely-there` | Subtle background sections, divider lines — a very light, desaturated warm gray for low-contrast section breaks |
| Rich Earth | `#24280f` | `--color-rich-earth` | Form input text, secondary neutral text — a dark, slightly green-tinted neutral, offering a softer alternative to Off-Black Pine |

## Tokens — Typography

### Founders Grotesk — Primary UI text, body copy, navigation, buttons, and most informational elements. Its clean, utilitarian nature allows the distinctive serif to shine, providing a legible and approachable voice. · `--font-founders-grotesk`
- **Substitute:** Inter
- **Weights:** 200, 300, 400, 500
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 24px, 32px, 40px
- **Line height:** 0.85, 1.04, 1.07, 1.11, 1.17, 1.20, 1.33, 1.36, 1.40, 2.00
- **Letter spacing:** -0.0250em at 40px, -0.0170em at 32px, -0.0100em at 24px, -0.0080em at 18px
- **Role:** Primary UI text, body copy, navigation, buttons, and most informational elements. Its clean, utilitarian nature allows the distinctive serif to shine, providing a legible and approachable voice.

### Times Now — Distinguished display headlines and prominent calls-to-action. The generous negative tracking and classic serif forms convey authority and gravitas, making key statements feel impactful and polished. · `--font-times-now`
- **Substitute:** Source Serif Pro
- **Weights:** 200, 300
- **Sizes:** 30px, 40px, 50px, 60px, 80px, 120px
- **Line height:** 0.78, 0.84, 0.86, 0.90, 1.00
- **Letter spacing:** -0.0640em at 120px, -0.0500em at 80px, -0.0490em at 60px, -0.0400em at 50px, -0.0340em at 40px, -0.0170em at 30px
- **Role:** Distinguished display headlines and prominent calls-to-action. The generous negative tracking and classic serif forms convey authority and gravitas, making key statements feel impactful and polished.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body | 16px | 1.4 | — | `--text-body` |
| body-lg | 18px | 1.33 | -0.144px | `--text-body-lg` |
| subheading | 24px | 1.2 | -0.24px | `--text-subheading` |
| heading | 40px | 1.11 | -1.36px | `--text-heading` |
| heading-lg | 60px | 0.9 | -2.94px | `--text-heading-lg` |
| display | 80px | 0.84 | -4px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 92 | 92px | `--spacing-92` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 18px |
| cards | 24px |
| inputs | 51px |
| buttons | 10px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 12px

## Components

### Filled Terracotta Button
**Role:** Primary action

Solid `Terracotta Sunset` (#de7653) background with `Paper White` (#fefffa) text. Rounded corners at `10px` radius. Padding `14px` vertical, `35px` horizontal.

### Filled Ember Button
**Role:** Secondary action

Solid `Ember Clay` (#e7573d) background with `Paper White` (#fefffa) text. Rounded corners at `10px` radius. Padding `8px` vertical, `26px` horizontal.

### Outline Terracotta Button
**Role:** Ghost action

Transparent background with `Terracotta Sunset` (#de7653) text and `Terracotta Sunset` (#de7653) border. Rounded corners at `10px` radius. Padding `14px` vertical, `35px` horizontal.

### Filled Sunbeam Button
**Role:** Accent action

Solid `Sunbeam` (#e1f079) background with `Off-Black Pine` (#0e0f0a) text. Rounded corners at `10px` radius. Padding `14px` vertical, `35px` horizontal.

### Standard Card
**Role:** Content container

Pervasive content container, on `Vanilla Beam` (#faf5f1) background. White, `Paper White` (#fefffa) background with `24px` border radius. Padding `60px` vertical, `54px` horizontal. No shadows.

### Full-Width Section Card
**Role:** Background section

Used as full-width sections to differentiate content blocks. `Vanilla Beam` (#faf5f1) background, `0px` border radius. Padding `37px` top, `126px` bottom.

### Text Input Field
**Role:** Form element

Rounded input field with `Vanilla Beam` (#faf5f1) background and `Rich Earth` (#24280f) text. `51px` border radius, no border visible. Padding `15px` horizontal.

## Do's and Don'ts

### Do
- Prioritize `Times Now` for all headings 30px and above, featuring its characteristic tight letter-spacing to command attention.
- Use `Founders Grotesk` for all body copy and UI elements, ensuring readability and supporting the academic tone established by the serif headlines.
- Restrict calls-to-action to `Terracotta Sunset` (#de7653) for primary actions and `Ember Clay` (#e7573d) for secondary actions, maintaining a clear visual hierarchy.
- Employ `Sunbeam` (#e1f079) as a vivid accent color for specific decorative text elements or unique button styles, utilizing its striking contrast.
- Build surfaces using `Vanilla Beam` (#faf5f1) as the base, layering `Paper White` (#fefffa) for elevated cards and `Barely There` (#e5e1d6) for subtle section differentiation.
- Apply `24px` border radius to all content cards and panels, and `10px` to all buttons, for a consistent soft-edged feel.
- Maintain a generous `40px` vertical padding in content cards to ensure breathable content blocks.

### Don't
- Avoid using `Sunbeam` (#e1f079) or `Terracotta Sunset` (#de7653) for body text or large blocks of informational content, as they are reserved for accents and actions.
- Do not introduce strong shadows or excessive gradients; rely on color temperature and subtle surface changes for depth and hierarchy.
- Refrain from using overly narrow line heights or default letter spacing for `Times Now` headlines; leverage the defined tight tracking to preserve its distinctive appearance.
- Avoid sharp, `0px` radius corners for interactive elements or cards; `10px` and `24px` radii are central to the brand's tactile feeling.
- Do not deviate from the core neutral palette (`Off-Black Pine`, `Vanilla Beam`, `Paper White`, `Barely There`, `Rich Earth`) for backgrounds and text unless specifically using an accent color.
- Do not use dark-mode elements or extensive dark backgrounds outside of the designated `Greengage` (#3d4128) hero/footer areas.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Vanilla Bean Canvas | `#faf5f1` | Primary page background and default content canvas. |
| 2 | Paper White Card | `#fefffa` | Elevated card backgrounds, offering a subtle visual lift from the canvas. |
| 3 | Barely There Section | `#e5e1d6` | Low-contrast background for section differentiation. |

## Imagery

Imagery primarily features product screenshots displaying dashboard interfaces, often contained within `Paper White` (#fefffa) cards with `24px` rounded corners. When photography is used, it often shows stylized, warmly lit individuals engaging with technology, maintaining an authentic, human-centric but professional feel. Icons are clean, minimal, and predominantly `Off-Black Pine` (#0e0f0a). The overall density is balanced, allowing ample whitespace while showcasing key product features and relevant human elements.

## Layout

The page adheres to a `1440px` max-width contained layout, centered on the screen. The hero section often features a full-bleed `Greengage` (#3d4128) background with a large, centered `Times Now` headline and a visual product showcase. Subsequent sections generally alternate between `Vanilla Bean Canvas` (#faf5f1) and `Barely There` (#e5e1d6) backgrounds. Content is frequently arranged in two-column text-left/image-right or image-left/text-right patterns, with occasional centered stacks for testimonials or calls to action. A multi-column grid is used for features or partner logos.

## Agent Prompt Guide

### Quick Color Reference
text: #0e0f0a
background: #faf5f1
border: #0e0f0a
accent: #de7653
primary action: #de7653 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #de7653 background, #0a0a0a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a standard content card: `Paper White` (#fefffa) background, `24px` border radius, no shadow. Headline in `Times Now` 40px weight 300, `Off-Black Pine` (#0e0f0a), letter-spacing -1.36px. Body text in `Founders Grotesk` 16px weight 400, `Off-Black Pine` (#0e0f0a).
4. Create a text input field: `Vanilla Beam` (#faf5f1) background, `Rich Earth` (#24280f) text in `Founders Grotesk` 16px weight 400. `51px` border radius. `15px` horizontal padding, no vertical padding.

## Similar Brands

- **Anthropic** — Combines a warm, muted color palette with a clean, understated UI and strong typography.
- **Attio** — Features a distinct serif font for headings paired with a legible sans-serif for body, on a light, warm background with subtle accents.
- **Linear** — Uses a highly structured, content-focused layout with a restrained color palette, though with brighter accents.
- **Fathom Analytics** — Presents data-driven insights with a clear, calm aesthetic, using a soft, light background and thoughtful type pairing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greengage: #3d4128;
  --color-sunbeam: #e1f079;
  --color-terracotta-sunset: #de7653;
  --color-ember-clay: #e7573d;
  --color-off-black-pine: #0e0f0a;
  --color-vanilla-beam: #faf5f1;
  --color-paper-white: #fefffa;
  --color-barely-there: #e5e1d6;
  --color-rich-earth: #24280f;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-now: 'Times Now', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.144px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.11;
  --tracking-heading: -1.36px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -2.94px;
  --text-display: 80px;
  --leading-display: 0.84;
  --tracking-display: -4px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-92: 92px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-tags: 18px;
  --radius-cards: 24px;
  --radius-inputs: 51px;
  --radius-buttons: 10px;

  /* Surfaces */
  --surface-vanilla-bean-canvas: #faf5f1;
  --surface-paper-white-card: #fefffa;
  --surface-barely-there-section: #e5e1d6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greengage: #3d4128;
  --color-sunbeam: #e1f079;
  --color-terracotta-sunset: #de7653;
  --color-ember-clay: #e7573d;
  --color-off-black-pine: #0e0f0a;
  --color-vanilla-beam: #faf5f1;
  --color-paper-white: #fefffa;
  --color-barely-there: #e5e1d6;
  --color-rich-earth: #24280f;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-now: 'Times Now', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.144px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.11;
  --tracking-heading: -1.36px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -2.94px;
  --text-display: 80px;
  --leading-display: 0.84;
  --tracking-display: -4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-92: 92px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 50px;
}
```
