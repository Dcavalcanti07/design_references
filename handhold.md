# Handhold — Style Reference
> White canvas, focused clarity.

**Theme:** light

Handhold's design system emanates a calm, focused atmosphere, emphasizing clarity and directness. A dominant white background provides an expansive canvas, allowing typography to take center stage. Key information is structured with compact, self-assured headings, while interaction is guided by stark black buttons, suggesting control and precision. The overall impression is one of quiet competence, designed to make complex AI solutions feel approachable and reliable.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, button text on dark backgrounds, subtle dividers |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, button backgrounds, strong borders — establishes authority through high contrast |
| Pale Ash | `#f2f1ed` | `--color-pale-ash` | Secondary background surfaces for cards, alternate button backgrounds – provides subtle visual separation without starkness |
| Midtone Gray | `#737373` | `--color-midtone-gray` | Muted text, helper text, inactive borders — provides hierarchy and lessens visual impact where appropriate |
| Light Gray | `#999999` | `--color-light-gray` | Fine borders, tertiary text |

## Tokens — Typography

### bureauSerif — Headlines and section titles. The uniform light weight (200) across all sizes creates an understated elegance, preferring authority through restraint rather than visual density. · `--font-bureauserif`
- **Substitute:** Georgia, serif
- **Weights:** 200
- **Sizes:** 20px, 28px, 40px, 72px
- **Line height:** 1.00
- **Letter spacing:** -0.0300em
- **Role:** Headlines and section titles. The uniform light weight (200) across all sizes creates an understated elegance, preferring authority through restraint rather than visual density.

### Inter — Body copy, navigation, buttons, and all functional text. Its slightly condensed letter-spacing enhances readability and a sense of professionalism. · `--font-inter`
- **Substitute:** Arial, sans-serif
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.50
- **Letter spacing:** -0.0130em at 16px, -0.0110em at 14px, -0.0090em at 12px
- **Role:** Body copy, navigation, buttons, and all functional text. Its slightly condensed letter-spacing enhances readability and a sense of professionalism.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.009px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.011px | `--text-body-sm` |
| body | 16px | 1.33 | -0.013px | `--text-body` |
| heading-sm | 20px | 1 | -0.03px | `--text-heading-sm` |
| heading | 28px | 1 | -0.03px | `--text-heading` |
| heading-lg | 40px | 1 | -0.03px | `--text-heading-lg` |
| display | 72px | 1 | -0.03px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24-32px |
| links | 8px |
| buttons | 1.67772e+07px |

### Layout

- **Section gap:** 48px
- **Card padding:** 28px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call to action.

Solid Midnight Ink background, Canvas White text. Extremely rounded corners, giving a pill-like shape. Padding: 8px vertical, 16px horizontal. Font: Inter, weight 400.

### Secondary Ghost Button
**Role:** Alternative or less prominent actions.

Transparent background, Midnight Ink text and border. Extremely rounded corners. Padding: 10px vertical, 10px horizontal. Font: Inter, weight 400.

### Navigation Link Button
**Role:** Secondary navigation or utility links.

No background or border. Midnight Ink text. Font: Inter, weight 400. Square corners.

### Subtle Notification Banner
**Role:** Informational banner.

Pale Ash background, Midnight Ink text. No border, no radius. Padding: 10px vertical, 16px horizontal. Font: Inter, weight 400.

### Feature Card
**Role:** Content container for features or testimonials.

Pale Ash background with rounded corners (24px or 32px). No shadow, flat appearance. Padding: 28px on all sides.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and interactive elements to maintain high contrast and clarity.
- Apply bureauSerif weight 200 with -0.0300em letter-spacing for all headlines to achieve the distinct understated elegance.
- Prioritize Canvas White (#ffffff) as the dominant page background to create a spacious and clean canvas.
- Utilize Pale Ash (#f2f1ed) for card backgrounds and subtle variations in surface elevation, avoiding hard shadows.
- Ensure all interactive buttons are extremely rounded (1.67772e+07px radius) to convey a distinct, approachable interactable element.
- Maintain a comfortable density with a consistent 16px element gap for most inline components and a 48px section gap between major content blocks.
- Pair bureauSerif for headings with Inter for body text, never mixing the two families for the same semantic element (e.g., heading or body).
- Embed the blue and yellow flowing abstract graphic at the bottom of hero sections or before prominent client testimonial sections, as a visual anchor.

### Don't
- Avoid using multiple font weights for bureauSerif; it should consistently be weight 200.
- Do not introduce strong shadows or complex gradients unless explicitly called for by a unique component, as surfaces are primarily flat.
- Refrain from using highly saturated colors for backgrounds or large areas; color should primarily be functional accents or part of imagery.
- Do not deviate from the established type scale; maintain the precise sizes and line heights for consistent visual hierarchy.
- Avoid arbitrary border radii; adhere to the 24px/32px for cards and the extreme rounding for buttons.
- Do not use generic system fonts in place of Inter or bureauSerif; the specific letter-spacing and weight profiles are critical to brand identity.
- Avoid heavy borders or outlines on cards and containers; a flat Pale Ash surface is preferred.

## Imagery

The site uses a mix of subtle abstract graphics and black-and-white logos. The main visual element is a fluid, low-contrast abstract wave graphic in muted blues and yellows, serving as a decorative atmospheric element rather than explanatory content. Logos are monochromatic and presented without framing, integrated directly into the layout. There's an absence of photography or detailed illustrations, focusing almost exclusively on UI and typography.

## Layout

The page maintains a centered, max-width contained layout rather than full-bleed. The hero section features a large, centered headline followed by a centered call-to-action block. Section rhythm is primarily vertical, with consistent spacing between content blocks. Content is arranged in simple stacked patterns, sometimes with a subtle visual divider. A prominent abstract wave graphic is used as a visual anchor at the bottom of the hero. Navigation is a minimalist top bar with utility links.

## Agent Prompt Guide

### Quick Color Reference
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: #000000 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Feature Card: Use a Pale Ash background with 24px border-radius. Apply 28px padding. Inside, use a bureauSerif 28px weight 200 heading followed by Inter 16px weight 400 body text, with 16px element gap between elements.
3. Implement a Navigation Item: Use Inter 16px weight 400 Midnight Ink text. No background, no border. This will act as a navigation link.
4. Design a Subtle Notification: Use a Pale Ash background with Inter 16px weight 400 Midnight Ink text. Apply 10px vertical and 16px horizontal padding. No border-radius.

## Similar Brands

- **Linear** — Monochrome palette with high-contrast type and minimal ornamentation, focused on functional UI before aesthetic flourishes.
- **Supabase** — Clean white backgrounds with focus on typography and functional black buttons for calls to action.
- **Raycast** — Simple, uncluttered layouts with clear typographic hierarchy and a limited, high-contrast color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-pale-ash: #f2f1ed;
  --color-midtone-gray: #737373;
  --color-light-gray: #999999;

  /* Typography — Font Families */
  --font-bureauserif: 'bureauSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.009px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.011px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: -0.013px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.03px;
  --text-heading: 28px;
  --leading-heading: 1;
  --tracking-heading: -0.03px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;

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
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 28px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-cards: 24-32px;
  --radius-links: 8px;
  --radius-buttons: 1.67772e+07px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-pale-ash: #f2f1ed;
  --color-midtone-gray: #737373;
  --color-light-gray: #999999;

  /* Typography */
  --font-bureauserif: 'bureauSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.009px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.011px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: -0.013px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.03px;
  --text-heading: 28px;
  --leading-heading: 1;
  --tracking-heading: -0.03px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;

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
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
}
```
