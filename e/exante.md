# Exante — Style Reference
> Crisp green on architectural grid

**Theme:** light

Exante employs a direct, high-contrast visual system using sharp contrasts and clear functional blocks. A vibrant green acts as a primary accent against a stark achromatic palette of black and white. The design emphasizes content clarity with structured layouts and subtle graphical details without relying on heavy shadows or complex gradients. The typography is modern and precise, blending geometric clarity with understated sophistication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default button text |
| Midnight Ink | `#1e211e` | `--color-midnight-ink` | Primary text, solid button backgrounds, primary navigation elements, footer backgrounds |
| Deep Shadow | `#000000` | `--color-deep-shadow` | Strongest text contrast, prominent borders, icon fills |
| Soft Gray | `#4b4d4b` | `--color-soft-gray` | Secondary body text, supporting information |
| Divider Ash | `#d2d3d2` | `--color-divider-ash` | Hairline borders, horizontal rules |
| Exante Green | `#90fc95` | `--color-exante-green` | Accent backgrounds for important sections, graphical elements — a vivid highlight that demands attention |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Alliance No.2 — Primary headlines and display text. Weight 300 for 80px headlines creates a refined, impactful presence through a lighter touch than conventional bold. · `--font-alliance-no2`
- **Substitute:** Montserrat
- **Weights:** 300, 400
- **Sizes:** 24px, 28px, 52px, 58px, 80px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.0500em at 80px, -0.0400em at 58px, -0.0200em at 52px, -0.0100em at 28px
- **OpenType features:** `'ss10', 'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** Primary headlines and display text. Weight 300 for 80px headlines creates a refined, impactful presence through a lighter touch than conventional bold.

### Geist Variable — General body text, links, and navigation items. Provides excellent readability at various sizes for detailed information. · `--font-geist-variable`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 17px, 19px, 21px, 24px
- **Line height:** 1.40
- **Letter spacing:** -0.0200em at 24px, -0.0100em at 17px
- **OpenType features:** `'ss03', 'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** General body text, links, and navigation items. Provides excellent readability at various sizes for detailed information.

### Geist Mono — Code snippets, timestamps, or technical annotations where monospace clarity is desired. Distinctive wide tracking. · `--font-geist-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.20, 1.40
- **Letter spacing:** 0.0600em
- **Role:** Code snippets, timestamps, or technical annotations where monospace clarity is desired. Distinctive wide tracking.

### Geist — Geist — detected in extracted data but not described by AI · `--font-geist`
- **Weights:** 300, 400
- **Sizes:** 19px, 21px, 72px
- **Line height:** 1, 1.4, 1.5
- **Letter spacing:** -0.04
- **Role:** Geist — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.4 | -0.28px | `--text-body` |
| body-lg | 19px | 1.5 | — | `--text-body-lg` |
| subheading | 24px | 1 | -0.48px | `--text-subheading` |
| heading | 52px | 1 | -1.04px | `--text-heading` |
| heading-lg | 58px | 1.2 | -2.32px | `--text-heading-lg` |
| display | 80px | 1.1 | -4px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 124 | 124px | `--spacing-124` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| images | 8px |
| buttons | 2px |
| navItems | 2px |

### Layout

- **Section gap:** 160px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action

Solid background Exante Green, Deep Shadow text, 2px radius, 16px vertical padding, 34px horizontal padding. Font: Geist Variable, 400 weight.

### Secondary Outlined Button (Dark)
**Role:** Ghost button

Transparent background with a 1px Midnight Ink border, Canvas White text. Used for secondary actions in dark contexts. 2px radius, 16px vertical padding, 34px horizontal padding. Font: Geist Variable, 400 weight.

### Secondary Outlined Button (Light)
**Role:** Ghost button

Transparent background with a 1px Deep Shadow border, Midnight Ink text. Used for secondary actions in light contexts. 2px radius, 11px vertical padding, 28px horizontal padding. Font: Geist Variable, 400 weight.

### Feature Card
**Role:** Information display

Canvas White background, 8px border radius, with 16px padding. Content typically includes a heading and body text. Can appear on an Exante Green background.

### Navigation Link
**Role:** Top navigation

Geist Variable 16px, 400 weight, Midnight Ink text on Canvas White header. Underlined on hover. 2px border-radius, 10px horizontal padding.

## Do's and Don'ts

### Do
- Use Alliance No.2 for all headings to maintain consistent brand voice.
- Apply 2px border radius to all buttons and navigation elements for a subtle softness.
- Use Exante Green (#90fc95) sparingly as a functional highlight or background for key informational blocks.
- Maintain a clear hierarchy with Midnight Ink (#1e211e) for primary text and Soft Gray (#4b4d4b) for supporting text.
- Establish clear visual separation between sections using either Exante Green background blocks or ample vertical spacing like 160px section gaps.
- Utilize Geist Variable for all body text for optimal readability.
- Ensure input fields and critical UI elements have a 1px Deep Shadow (#000000) border for definition.

### Don't
- Do not introduce new color accents outside of Exante Green or the established neutral palette.
- Avoid using drop shadows on cards or elements; rely on flat surfaces, borders, or background color changes for separation.
- Do not use generic sans-serif fonts; always use Alliance No.2 or Geist Variable as specified.
- Avoid decorative imagery that competes visually with the clean UI; stick to abstract, geometric, or product-focused visuals.
- Do not deviate from the specified tight letter-spacing for headlines; it is a key typographic characteristic.
- Never use primary filled buttons in colors other than Exante Green or Midnight Ink; avoid mixing button styles.
- Do not implement complex layout patterns; prioritize clarity with centered content or simple column structures.

## Imagery

This site uses abstract, geometric 3D graphics, primarily rendered in a luminous green gradient that echoes the brand's accent color, set against dark or light backgrounds. These graphics serve a decorative and atmospheric role, adding a sense of depth and modernity without depicting real-world objects or people. Product screenshots are minimal or non-existent. Icons are outlines, leveraging the Deep Shadow and Exante Green colors, maintaining a fine stroke weight.

## Layout

The page primarily uses a max-width contained layout sections but incorporates full-bleed hero and feature sections with distinct background colors. The hero section features a full-bleed dark background with a centered headline and subtext, flanked by abstract green geometric shapes. Content is often arranged in alternating text-left/text-right patterns or clear, centered stacks. Feature sections commonly use a multi-column card grid, frequently on an Exante Green background. Vertical rhythm is established through consistent section gaps and clear visual breaks rather than complex dividers. Navigation is a sticky top bar with minimal links and clear call-to-action buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #1e211e
background: #ffffff
border: #d2d3d2
accent: #90fc95
primary action: #1e211e (filled action)

Example Component Prompts:
Create a hero headline: 'AI teammate that handles collections' Alliance No.2, 80px, weight 300, #1e211e, letter-spacing -4px.
Create a primary action button: 'Request a Demo' with background #1e211e, text #ffffff, 2px radius, 16px vertical padding, 34px horizontal padding, Geist Variable 400.
Create a feature card: Canvas White background, 8px radius, 16px padding. Headline: '26%+' Alliance No.2, 52px, weight 400, #000000.  Description: 'Reduction in DSO' Geist Variable, 17px, weight 400, #1e211e.
Create a secondary outlined button: 'Sign In' with 1px #000000 border, text #1e211e, 2px radius, 11px vertical padding, 28px horizontal padding, Geist Variable 400.
Create a callout section with Exante Green background (#90fc95), centered headline 'Go from outstanding invoices to outstanding cash flow in no time.' Alliance No.2, 58px, weight 400, #000000, letter-spacing -2.32px.

## Similar Brands

- **Ramp** — Uses a similar green accent color against a clean, mostly achromatic UI, with sharp edges and clear information architecture.
- **Mercury** — Employs a high-contrast black and white palette with a singular bright accent color, structured typography, and minimal decorative elements.
- **Brex** — Features a strong geometric aesthetic with a distinct color highlight, sharp typography, and a preference for abstract visuals over photography.
- **Stripe** — Known for its clean, purposeful UI, structured layouts, and measured use of color for hierarchy and branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #1e211e;
  --color-deep-shadow: #000000;
  --color-soft-gray: #4b4d4b;
  --color-divider-ash: #d2d3d2;
  --color-exante-green: #90fc95;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-alliance-no2: 'Alliance No.2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-variable: 'Geist Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.28px;
  --text-body-lg: 19px;
  --leading-body-lg: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.48px;
  --text-heading: 52px;
  --leading-heading: 1;
  --tracking-heading: -1.04px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -2.32px;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: -4px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-124: 124px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 160px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-images: 8px;
  --radius-buttons: 2px;
  --radius-navitems: 2px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #1e211e;
  --color-deep-shadow: #000000;
  --color-soft-gray: #4b4d4b;
  --color-divider-ash: #d2d3d2;
  --color-exante-green: #90fc95;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-alliance-no2: 'Alliance No.2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-variable: 'Geist Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.28px;
  --text-body-lg: 19px;
  --leading-body-lg: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.48px;
  --text-heading: 52px;
  --leading-heading: 1;
  --tracking-heading: -1.04px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -2.32px;
  --text-display: 80px;
  --leading-display: 1.1;
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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-124: 124px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
}
```
