# Parloa — Style Reference
> Matte Charcoal Canvas

**Theme:** light

Parloa presents a refined, almost austere aesthetic, balancing a predominantly monochrome palette with warm undertones and precise, understated typography. A single vivid orange accent color provides discrete functional highlighting. Surfaces range from a light, almost off-white canvas to deep, matte charcoal, fostering a sense of sophisticated calm. The overall impression is one of confident, measured authority through visual restraint.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#1f1c1b` | `--color-midnight-charcoal` | Primary text, dark backgrounds for sections, form elements, and buttons. Creates a strong, grounded presence |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page background, card surfaces, and text on dark backgrounds. Establishes a clean, expansive workspace |
| Cream Canvas | `#ebe9e1` | `--color-cream-canvas` | Tertiary background for subtle section breaks and large background areas, providing a warm, soft transition |
| Parchment Gray | `#f5f4f0` | `--color-parchment-gray` | Secondary background for navigation, lighter card surfaces, and subtle text contrast on Cream Canvas |
| Stone Accent | `#a69b92` | `--color-stone-accent` | Muted helper text, placeholder text in forms, and subtle border accents. Offers a softer alternative to dark neutrals |
| Raven Black | `#000000` | `--color-raven-black` | Pure black for icons and occasionally for high-contrast body text. Used sparingly to ensure high impact where needed |
| Deep Plum | `#2d2724` | `--color-deep-plum` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Ash Mist | `#c7c1b7` | `--color-ash-mist` | Delicate hairline borders and dividers, providing minimal visual separation |
| Faded Stone | `#d9d6ce` | `--color-faded-stone` | Lightest border color and secondary link text. Offers a very soft visual cue without competition |
| Sunset Orange | `#ff7714` | `--color-sunset-orange` | Orange accent for outlined action borders, linked labels, and lightweight interactive emphasis. |
| Prismatic Veil | `linear-gradient(30deg, rgb(153, 38, 38), rgb(153, 170, 38), rgb(0, 0, 0), rgb(34, 153, 74), rgb(38, 26, 153), rgb(0, 0, 0), rgb(34, 153, 153))` | `--color-prismatic-veil` | Decorative hero background. Not used for functional UI elements, but sets a mood of dynamic complexity |

## Tokens — Typography

### Geist — Primary textual content, navigation, buttons, and form labels. Its crisp, technically-inspired character underpins the system's precise feel. Weights 300 and 400 are common for body text, maintaining a light overall density. · `--font-geist`
- **Substitute:** Inter, Arial, sans-serif
- **Weights:** 300, 400, 500, 600
- **Sizes:** 10px, 11px, 13px, 14px, 16px, 18px
- **Line height:** 1.00, 1.20, 1.30, 1.33, 1.40, 1.50
- **Letter spacing:** 0.01, 0.02
- **Role:** Primary textual content, navigation, buttons, and form labels. Its crisp, technically-inspired character underpins the system's precise feel. Weights 300 and 400 are common for body text, maintaining a light overall density.

### Exposure30 — Headlines and prominent display text. Its elegant, serif nature contrasts with Geist, providing a sense of gravitas and sophistication. Lighter weights (350, 400) keep it from feeling overly heavy, suggesting authority through design rather than bolding. · `--font-exposure30`
- **Substitute:** Playfair Display, serif
- **Weights:** 350, 400
- **Sizes:** 24px, 28px, 42px, 82px, 96px
- **Line height:** 1.00, 1.10, 1.20, 1.30
- **Letter spacing:** -0.01, 0.01
- **Role:** Headlines and prominent display text. Its elegant, serif nature contrasts with Geist, providing a sense of gravitas and sophistication. Lighter weights (350, 400) keep it from feeling overly heavy, suggesting authority through design rather than bolding.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.02px | `--text-caption` |
| body | 14px | 1.5 | 0.01px | `--text-body` |
| subheading | 24px | 1.3 | 0.01px | `--text-subheading` |
| heading-sm | 28px | 1.2 | -0.01px | `--text-heading-sm` |
| heading | 42px | 1.1 | -0.01px | `--text-heading` |
| heading-lg | 82px | 1 | -0.01px | `--text-heading-lg` |
| display | 96px | 1 | -0.01px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Ghost Navigation Button
**Role:** Navigation, secondary actions

Text in Canvas White (#ffffff) on a transparent background, 12px horizontal padding. Borderless, to float lightly in darker hero or nav areas. Font is Geist 14px/1.33.

### Primary Filled Button
**Role:** Key interactions, calls to action

Filled with Midnight Charcoal (#1f1c1b), Canvas White (#ffffff) text. Features 12px vertical and 11.4px horizontal padding, with a 0px border-radius. Font is Geist 14px/1.33.

### Light Filled Button
**Role:** Secondary actions in contrasting sections

Filled with Canvas White (#ffffff), Midnight Charcoal (#1f1c1b) text. Offers 12px vertical and 11.4px horizontal padding and 0px border-radius. Font is Geist 14px/1.33.

### Feature Card
**Role:** Content grouping, feature presentation

Canvas White (#ffffff) background, 24px internal padding, and 0px border-radius without a visible shadow. Components within are spaced using a 16px element gap system.

### Interactive Input Field
**Role:** Text input areas in forms

Midnight Charcoal (#1f1c1b) background with Canvas White (#ffffff) text and a Stone Accent (#a69b92) border by default. Padding is 14px all around on the input. On focus, the background shifts to Deep Plum (#2d2724) with a Canvas White border for clarity.

## Do's and Don'ts

### Do
- Prioritize a monochrome palette with Midnight Charcoal (#1f1c1b) and Canvas White (#ffffff) as primary background and text colors.
- Use Sunset Orange (#ff7714) exclusively for brand accents, links, and active states, never for large background areas or body text.
- Pair Geist for functional UI elements and body text with Exposure30 for headlines, maintaining a distinct typographic hierarchy.
- Maintain 0px border-radius across all components, specifically for cards, buttons, and inputs, to reinforce the sharp, precise aesthetic.
- Employ a base unit of 4px for all spacing; use 24px for component padding and element gaps, and 40px for section gaps.
- Use lighter Exposure30 weights (350, 400) for all display typography to achieve a sophisticated, non-aggressive presence.
- Ensure input fields have a clear visual shift to Deep Plum (#2d2724) on interaction for immediate feedback.

### Don't
- Avoid using Sunset Orange (#ff7714) as a background for buttons or large content blocks; reserve it for subtle emphasis.
- Do not introduce rounded corners; all interface elements must maintain 0px border-radius.
- Refrain from using strong shadows or heavy elevation styles; the design relies on flat planes and subtle background shifts.
- Do not deviate from Geist and Exposure30 for typography; avoid system fonts or other custom typefaces.
- Do not use generic gray values for borders or backgrounds when specific neutral tokens (e.g., Ash Mist #c7c1b7, Parchment Gray #f5f4f0) have been defined.
- Avoid bolding body text for emphasis; use changes in color (Sunset Orange #ff7714) or subtle weight variations within Geist (e.g., 500) for hierarchy.
- Do not rely on animation for primary interaction feedback; static state changes are preferred, though subtle ease transitions are acceptable for aesthetic flow.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cream Canvas | `#ebe9e1` | Base page background, large content sections. |
| 1 | Parchment Gray | `#f5f4f0` | Secondary background for navigation and subtle section differentiation. |
| 2 | Canvas White | `#ffffff` | Card surfaces, prominent content blocks, and elements needing maximum contrast against Midnight Charcoal text. |
| 3 | Midnight Charcoal | `#1f1c1b` | Darker background sections, filled buttons, and form elements. Provides a grounding, high-contrast surface. |
| 4 | Deep Plum | `#2d2724` | Focused input fields, indicating an active state with warmth. |

## Imagery

Imagery on Parloa is primarily focused on abstract or subtly contextualized photography and geometric illustrations. Photography features people (often smiling close-ups) treated with a vibrant, almost ethereal glow, frequently overlaid with a 'Prismatic Veil' gradient that introduces colorful, diffused light refractions. These images are often full-bleed in hero sections, creating an immersive, aspirational atmosphere. Illustrations are linear, geometric, and icon-like, using a monochrome palette (primarily Midnight Charcoal outlines on Canvas White or Cream Canvas backgrounds) to explain concepts clearly. Icons are outlined, with a moderate stroke weight, and follow the dominant monochrome palette for clarity, sometimes accented with Sunset Orange. The overall density is balanced, allowing imagery to occupy significant visual space for mood-setting, but keeping descriptive illustrations concise and functional.

## Layout

The page primarily employs a max-width contained layout, centering content within a 1200px constraint. The hero section is a full-bleed, dark background with a large, centered Exposure30 headline overlaying vibrant, semi-transparent photography. Subsequent sections often alternate between Cream Canvas (#ebe9e1) and Parchment Gray (#f5f4f0) backgrounds, creating clear visual segmentation. Content typically arranges in two-column text and image sections or multi-column card grids (e.g., 3-column with Feature Cards) for presenting solutions. Vertical spacing between sections is comfortable, with a consistent 40px section gap. The navigation is a sticky top bar, using a Parchment Gray background for prominence, with ghost buttons that become filled on click or hover. This creates a rhythmic, structured experience that feels spacious yet organized.

## Agent Prompt Guide

## Quick Color Reference
- text: #1f1c1b (Midnight Charcoal)
- background: #ebe9e1 (Cream Canvas)
- border: #c7c1b7 (Ash Mist)
- accent: #ff7714 (Sunset Orange)
- primary action: #1f1c1b (filled action)

## 3-5 Example Component Prompts
1. Create a Primary Action Button: #1f1c1b background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature section with Cream Canvas (#ebe9e1) background. Include a 3-column grid of 'Feature Card' components, each with a heading-sm in Exposure30 weight 400 (#1f1c1b) and body text in Geist weight 400 (#1f1c1b).
3. Implement a page section titled 'Get in Touch' on a Midnight Charcoal (#1f1c1b) background. Include an 'Interactive Input Field' with placeholder text 'Your Email' and a 'Light Filled Button' with text 'Submit'.

## Similar Brands

- **Linear** — Shares a precise, almost zero-radius component aesthetic, comfortable density, and strong typographic hierarchy with subtle accent colors.
- **Stripe** — Features clean, mostly monochrome layouts with high-quality supporting photography and a systematic approach to typography and spacing, similar to Parloa's measured feel.
- **Anthropic** — Utilizes a calm, expert-driven brand presence through a light, sophisticated color palette, restrained use of accents, and purposeful typography for complex B2B AI offerings.
- **Vercel** — Employs a sharp, minimalist UI with a strong focus on precise typography, monochromatic colors, and a clear, functional hierarchy, though with a different accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #1f1c1b;
  --color-canvas-white: #ffffff;
  --color-cream-canvas: #ebe9e1;
  --color-parchment-gray: #f5f4f0;
  --color-stone-accent: #a69b92;
  --color-raven-black: #000000;
  --color-deep-plum: #2d2724;
  --color-ash-mist: #c7c1b7;
  --color-faded-stone: #d9d6ce;
  --color-sunset-orange: #ff7714;
  --color-prismatic-veil: #992626;
  --gradient-prismatic-veil: linear-gradient(30deg, rgb(153, 38, 38), rgb(153, 170, 38), rgb(0, 0, 0), rgb(34, 153, 74), rgb(38, 26, 153), rgb(0, 0, 0), rgb(34, 153, 153));

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-exposure30: 'Exposure30', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.01px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.01px;
  --text-heading: 42px;
  --leading-heading: 1.1;
  --tracking-heading: -0.01px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.01px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Named Radii */
  --radius-none: 0px;

  /* Surfaces */
  --surface-cream-canvas: #ebe9e1;
  --surface-parchment-gray: #f5f4f0;
  --surface-canvas-white: #ffffff;
  --surface-midnight-charcoal: #1f1c1b;
  --surface-deep-plum: #2d2724;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #1f1c1b;
  --color-canvas-white: #ffffff;
  --color-cream-canvas: #ebe9e1;
  --color-parchment-gray: #f5f4f0;
  --color-stone-accent: #a69b92;
  --color-raven-black: #000000;
  --color-deep-plum: #2d2724;
  --color-ash-mist: #c7c1b7;
  --color-faded-stone: #d9d6ce;
  --color-sunset-orange: #ff7714;
  --color-prismatic-veil: #992626;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-exposure30: 'Exposure30', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.01px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.01px;
  --text-heading: 42px;
  --leading-heading: 1.1;
  --tracking-heading: -0.01px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.01px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
}
```
