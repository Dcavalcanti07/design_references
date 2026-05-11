# Arcade — Style Reference
> Crisp Blueprint on White Canvas. Clean surfaces frame sharp typography and a singular, vibrant blue, like a detailed architectural plan on a clear white sheet, accented by a distinct highlight.

**Theme:** light

Arcade presents a composed, polished aesthetic, prioritizing clarity and directness. The dominant whites and near-grayscale elements are punctuated by a single, vibrant blue, focusing attention and directing interaction. Subtle shadows build hierarchy and give a tactile quality to elements, making the UI feel grounded and precise. The generous use of rounded corners softens the otherwise direct typography, creating an accessible but authoritative tone.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button backgrounds, primary text on dark elements. |
| Whisper Gray | `#f9fafb` | `--color-whisper-gray` | Subtle background for UI elements and slight section differentiation. |
| Outline Ash | `#e5e7eb` | `--color-outline-ash` | Primary border color for buttons and input fields, indicating interactive boundaries. |
| Graphite Text | `#111827` | `--color-graphite-text` | Primary text color for headings and body, offering high contrast against light backgrounds. Also used as background for dark sections and button text on light buttons. |
| Slate Text | `#4b5563` | `--color-slate-text` | Secondary text color for body copy, subheadings, and muted links. Provides visual hierarchy by being less dominant than Graphite Text. |
| Silver Text | `#374151` | `--color-silver-text` | Decorative text in navigation and links. A slightly lighter nuance than Slate Text. |
| Steel Accent | `#70747d` | `--color-steel-accent` | Subtle secondary text, border colors, and subtle button states, providing softer visual cues. |
| Arcade Blue | `#2142e7` | `--color-arcade-blue` | Primary brand color for calls to action, active states, and focus indicators. Its vivid nature stands out against the muted neutral palette. |
| Deep Blue Shadow | `#182fa5` | `--color-deep-blue-shadow` | Darker shade of Arcade Blue used for button borders and subtle shadows, adding depth to interactive elements. |
| Dark Gradient Base | `linear-gradient(92deg, rgb(17, 24, 39) 70%, rgba(30, 43, 72, 0.9) 95%)` | `--color-dark-gradient-base` | Base color for complex background gradients, often appearing in hero sections or prominent content blocks. Paired with gradient accents. |
| Blue Gradient Accent | `linear-gradient(90deg, rgb(17, 24, 39) 0%, rgb(17, 24, 39) 45%, rgb(33, 66, 231) 50%, rgb(3, 181, 237) 55%, rgb(17, 24, 39) 60%, rgb(17, 24, 39) 100%)` | `--color-blue-gradient-accent` | Vivd blue accent within gradients, creating dynamic energy within dark sections, used in banners and hero elements. |

## Tokens — Typography

### Inter — The primary typeface for all text content, from headings to body. Its strong legibility and slightly condensed nature support an efficient, clear communication style. Heavier weights (600, 700) are reserved for key titles, while lighter weights (400, 500) serve body and secondary information. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 28px, 30px, 36px, 40px, 48px, 64px
- **Line height:** 1.00, 1.06, 1.07, 1.14, 1.17, 1.22, 1.25, 1.29, 1.30, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 1.67, 1.71
- **Letter spacing:** -0.0250em at 64px, -0.0200em at 48px, -0.0150em at 40px, -0.0100em at 36px and 30px, -0.0070em at 28px and 24px
- **Role:** The primary typeface for all text content, from headings to body. Its strong legibility and slightly condensed nature support an efficient, clear communication style. Heavier weights (600, 700) are reserved for key titles, while lighter weights (400, 500) serve body and secondary information.

### Balig Script — A decorative script font used sparingly for unique brand-specific elements or signatures, providing a touch of personalized flair. It contrasts with Inter's utilitarianism to add personality without compromising overall clarity. · `--font-balig-script`
- **Substitute:** cursive
- **Weights:** 400
- **Sizes:** 40px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** A decorative script font used sparingly for unique brand-specific elements or signatures, providing a touch of personalized flair. It contrasts with Inter's utilitarianism to add personality without compromising overall clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | -0.48px | `--text-heading-sm` |
| heading | 36px | 1.25 | -0.36px | `--text-heading` |
| heading-lg | 48px | 1.17 | -0.96px | `--text-heading-lg` |
| display | 64px | 1.07 | -1.6px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 108 | 108px | `--spacing-108` |
| 112 | 112px | `--spacing-112` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 16px |
| buttons | 12px |
| decorative | 24px |
| large-actions | 72px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(17, 24, 39, 0.2) 0px 8px 8px 0px, rgba(17, 24, 39, 0...` | `--shadow-sm` |
| subtle | `rgba(17, 24, 39, 0.12) 0px 0px 0px 1px, rgba(17, 24, 39, ...` | `--shadow-subtle` |
| xl | `rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39...` | `--shadow-xl` |
| subtle-2 | `rgba(17, 24, 39, 0.12) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| xl-2 | `rgba(17, 24, 39, 0.05) 0px 32px 32px 0px, rgba(17, 24, 39...` | `--shadow-xl-2` |
| xl-3 | `rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39...` | `--shadow-xl-3` |
| subtle-3 | `rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(17, 24, 39, 0...` | `--shadow-subtle-3` |

### Layout

- **Page max-width:** 1304px
- **Section gap:** 96px
- **Card padding:** 48px
- **Element gap:** 8px

## Components

### Secondary Outlined Button
**Role:** Secondary Action

Canvas White (#ffffff) background with Graphite Text (#111827) text. Border Outline Ash (#e5e7eb) and radius 12px. Padding 10px vertical, 16px horizontal. Offers a less prominent action option.

### Ghost Button
**Role:** Navigation & Tertiary Action

Transparent background with Steel Text (#70747d) text. Borders are invisible, radius 12px. Padding 10px vertical, 16px horizontal. Used for less emphasized actions or navigation items that are not primary CTAs.

### Action Input Field
**Role:** User Input with Action

Canvas White (#ffffff) background with Outline Ash (#e5e7eb) border. Text color is Graphite Text (#111827). Radius 16px. Left padding 16px, right padding 114px for an integrated button. Designed for primary data entry with an immediate associated action.

### Text Input Field
**Role:** Standard User Input

Transparent background with Graphite Text (#111827) text. Border color is default, radius 0px. Minimal padding, implying a simpler, integrated-text input.

### Header Navigation Link
**Role:** Primary Navigation

Silver Text (#374151) for default state, transitions to Graphite Text (#111827) or Arcade Blue (#2142e7) on hover/active. Radius 12px for interactive regions. Text style Inter, weight 500, size 16px. Part of the main site navigation.

### Status Chip
**Role:** Informational Badge

Whisper Gray (#f9fafb) background with radius 8px. Text Graphite Text (#111827), Inter, weight 500, size 14px. Padding 4px vertical, 8px horizontal. Used for small informative labels or categories.

### Feature Card
**Role:** Content Grouping

Transparent background, no specific border or shadow. Radius 0px. Padding 0px. Primarily used for visual segmentation of content without imposing heavy visual boundaries.

## Do's and Don'ts

### Do
- Prioritize Inter font for all text elements, leveraging weights 400-700. Reserve Balig Script for highly decorative brand elements if necessary, ensuring it never competes with Inter for readability.
- Use Arctic White (#ffffff) as the base background for most sections, broken by Whisper Gray (#f9fafb) for subtle differentiation, making content feel spacious and clear.
- Apply Arcade Blue (#2142e7) exclusively to primary calls to action and active states, ensuring high visibility and clear user pathways.
- Utilize border radii of 12px for buttons and navigation items, and 16px for input fields and general components, creating a soft but not overly rounded aesthetic.
- Implement consistent letter spacing: -0.0250em for 64px, -0.0200em for 48px, -0.0150em for 40px, -0.0100em for 36px and 30px, and -0.0070em for 28px and 24px, optimizing legibility for larger text.
- Apply subtle elevation provided by rgba(17, 24, 39, 0.04) box shadows to interactive elements and cards, giving a sense of depth and hierarchy without being heavy.

### Don't
- Do not introduce new vibrant colors outside of the defined Arcade Blue (#2142e7) palette; maintain the controlled use of color to avoid visual clutter.
- Avoid using harsh, abrupt transitions or sharp angles. Leverage the established border radii (12px, 16px, 72px) to maintain the soft, approachable feel.
- Do not use dark backgrounds for general body text sections; preserve the light-themed composition for readability and a composed appearance.
- Refrain from excessive use of gradient backgrounds. Limit them to hero sections or distinct banners to maintain their impact.
- Do not deviate from the specified typography scale and letter spacing values. Inconsistent typography disrupts the visual rhythm and perceived quality.
- Avoid arbitrary padding values; stick to the defined spacing scale (4px, 8px, 10px, 12px, 16px, 24px, 32px, 40px, 48px), especially for component internal spacing.

## Elevation

- **Card / Elevated Panel:** `rgba(17, 24, 39, 0.2) 0px 8px 8px 0px, rgba(17, 24, 39, 0.1) 0px 4px 4px 0px, rgba(17, 24, 39, 0.1) 0px 2px 2px 0px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset`
- **Subtle UI Element:** `rgba(17, 24, 39, 0.12) 0px 0px 0px 1px, rgba(17, 24, 39, 0.03) 0px 2px 2px -2px, rgba(17, 24, 39, 0.03) 0px 4px 4px 0px, rgba(17, 24, 39, 0.03) 0px 8px 8px 0px, rgba(17, 24, 39, 0.03) 0px 16px 16px 0px`
- **Button (Normal):** `rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgba(17, 24, 39, 0.16) 0px 0px 0px 1px`
- **Button (Hover/Focus):** `rgba(17, 24, 39, 0.05) 0px 32px 32px 0px, rgba(17, 24, 39, 0.05) 0px 16px 16px 0px, rgba(17, 24, 39, 0.05) 0px 8px 8px 0px, rgba(17, 24, 39, 0.05) 0px 4px 4px 0px, rgba(17, 24, 39, 0.05) 0px 2px 2px -2px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px`
- **Primary Button (with border shadow):** `rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgb(24, 47, 165) 0px 0px 0px 1px`

## Imagery

This site uses product screenshots and abstract gradients. Product screenshots are typically presented as contained UI shots, sometimes with a subtle glow or frame, without full-bleed integration. The abstract gradients are vibrant blue organic shapes, soft-edged and contained to specific background sections like the hero or decorative elements, creating a dynamic, modern feel without sharp graphical elements. Icons are filled, mono-color SVG in the Graphite Text (#111827) color, often appearing in feature lists or interactive elements.

## Layout

The site employs a centered, max-width layout (1304px) for most content, providing a sense of order and focus. The hero section breaks this somewhat, featuring a full-width background gradient contrasted with a centered text block and an interactive input field. Sections generally maintain a consistent vertical spacing of 96px, with alternating content arrangements: either text stacked with a visual below, or a two-column layout with text on one side and a product image/visual on the other, creating a clear and scannable rhythm. Navigation is a sticky top bar with branding, links, and prominent calls to action.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #111827
- Text (Secondary): #4b5563
- Background (Primary): #ffffff
- Background (Subtle): #f9fafb
- CTA Button: #2142e7
- Border (Neutral): #e5e7eb

### 3 Example Component Prompts
1. Create a primary hero section: full-width background gradient (linear: rgb(17,24,39) to rgba(30,43,72,0.9)). Centered headline 'Your product story, built by AI in minutes.' (Inter, 64px, weight 700, #111827, letter-spacing -1.6px). Below, a subheading 'Create beautiful, on-brand demos...' (Inter, 20px, weight 400, #4b5563). Below that, an 'Action Input Field' component (Canvas White background, Outline Ash border, 72px radius) with placeholder text, and an integrated 'Arcade Blue' submit button.
2. Design a secondary button: 'Talk to sales', Ghost Button variant, with Steel Text (#70747d) color, Inter font, 16px size, weight 500. Padding 10px vertical, 16px horizontal, 12px radius. No visible border.
3. Create a feature testimonial card: Whisper Gray (#f9fafb) background. Main text: 'Arcade makes every format effortless.' (Inter, 36px, weight 600, #111827, letter-spacing -0.36px). Apply a subtle UI elevation shadow: rgba(17, 24, 39, 0.12) 0px 0px 0px 1px, rgba(17, 24, 39, 0.03) 0px 2px 2px -2px, rgba(17, 24, 39, 0.03) 0px 4px 4px 0px, rgba(17, 24, 39, 0.03) 0px 8px 8px 0px, rgba(17, 24, 39, 0.03) 0px 16px 16px 0px. Ensure the card has a 16px radius and 48px padding.

## Similar Brands

- **Linear** — Both use a minimalist, high-contrast UI with a single vibrant accent color (blue/purple) against a neutral palette, emphasizing clarity and functionality.
- **Vercel** — Shares the clean aesthetic, dominant white backgrounds, and strategic use of subtle shadows and gradients in hero sections to add depth without clutter.
- **Framer** — Exhibits a similar approach to systematic typography, using Inter as a core font and prioritizing clear text hierarchy with precise letter spacing and line heights.
- **Stripe** — Utilizes a balanced layout with generous white space paired with functional, well-defined components and a focus on polished product visuals within the UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f9fafb;
  --color-outline-ash: #e5e7eb;
  --color-graphite-text: #111827;
  --color-slate-text: #4b5563;
  --color-silver-text: #374151;
  --color-steel-accent: #70747d;
  --color-arcade-blue: #2142e7;
  --color-deep-blue-shadow: #182fa5;
  --color-dark-gradient-base: #111827;
  --gradient-dark-gradient-base: linear-gradient(92deg, rgb(17, 24, 39) 70%, rgba(30, 43, 72, 0.9) 95%);
  --color-blue-gradient-accent: #2142e7;
  --gradient-blue-gradient-accent: linear-gradient(90deg, rgb(17, 24, 39) 0%, rgb(17, 24, 39) 45%, rgb(33, 66, 231) 50%, rgb(3, 181, 237) 55%, rgb(17, 24, 39) 60%, rgb(17, 24, 39) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-balig-script: 'Balig Script', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.36px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 64px;
  --leading-display: 1.07;
  --tracking-display: -1.6px;

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
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-112: 112px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1304px;
  --section-gap: 96px;
  --card-padding: 48px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 72px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 16px;
  --radius-buttons: 12px;
  --radius-decorative: 24px;
  --radius-large-actions: 72px;

  /* Shadows */
  --shadow-sm: rgba(17, 24, 39, 0.2) 0px 8px 8px 0px, rgba(17, 24, 39, 0.1) 0px 4px 4px 0px, rgba(17, 24, 39, 0.1) 0px 2px 2px 0px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset;
  --shadow-subtle: rgba(17, 24, 39, 0.12) 0px 0px 0px 1px, rgba(17, 24, 39, 0.03) 0px 2px 2px -2px, rgba(17, 24, 39, 0.03) 0px 4px 4px 0px, rgba(17, 24, 39, 0.03) 0px 8px 8px 0px, rgba(17, 24, 39, 0.03) 0px 16px 16px 0px;
  --shadow-xl: rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgba(17, 24, 39, 0.16) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(17, 24, 39, 0.12) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(17, 24, 39, 0.05) 0px 32px 32px 0px, rgba(17, 24, 39, 0.05) 0px 16px 16px 0px, rgba(17, 24, 39, 0.05) 0px 8px 8px 0px, rgba(17, 24, 39, 0.05) 0px 4px 4px 0px, rgba(17, 24, 39, 0.05) 0px 2px 2px -2px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px;
  --shadow-xl-3: rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgb(24, 47, 165) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(17, 24, 39, 0.04) 0px 1px 1px -0.5px, rgba(17, 24, 39, 0.04) 0px 3px 3px -1.5px, rgba(17, 24, 39, 0.04) 0px 6px 6px -3px, rgba(17, 24, 39, 0.04) 0px 12px 12px -6px, rgba(17, 24, 39, 0.04) 0px 24px 24px -12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f9fafb;
  --color-outline-ash: #e5e7eb;
  --color-graphite-text: #111827;
  --color-slate-text: #4b5563;
  --color-silver-text: #374151;
  --color-steel-accent: #70747d;
  --color-arcade-blue: #2142e7;
  --color-deep-blue-shadow: #182fa5;
  --color-dark-gradient-base: #111827;
  --color-blue-gradient-accent: #2142e7;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-balig-script: 'Balig Script', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.36px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 64px;
  --leading-display: 1.07;
  --tracking-display: -1.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-112: 112px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 72px;

  /* Shadows */
  --shadow-sm: rgba(17, 24, 39, 0.2) 0px 8px 8px 0px, rgba(17, 24, 39, 0.1) 0px 4px 4px 0px, rgba(17, 24, 39, 0.1) 0px 2px 2px 0px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.06) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset;
  --shadow-subtle: rgba(17, 24, 39, 0.12) 0px 0px 0px 1px, rgba(17, 24, 39, 0.03) 0px 2px 2px -2px, rgba(17, 24, 39, 0.03) 0px 4px 4px 0px, rgba(17, 24, 39, 0.03) 0px 8px 8px 0px, rgba(17, 24, 39, 0.03) 0px 16px 16px 0px;
  --shadow-xl: rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgba(17, 24, 39, 0.16) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(17, 24, 39, 0.12) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(17, 24, 39, 0.05) 0px 32px 32px 0px, rgba(17, 24, 39, 0.05) 0px 16px 16px 0px, rgba(17, 24, 39, 0.05) 0px 8px 8px 0px, rgba(17, 24, 39, 0.05) 0px 4px 4px 0px, rgba(17, 24, 39, 0.05) 0px 2px 2px -2px, rgba(17, 24, 39, 0.1) 0px 0px 0px 1px;
  --shadow-xl-3: rgba(17, 24, 39, 0.04) 0px 32px 32px 0px, rgba(17, 24, 39, 0.04) 0px 16px 16px 0px, rgba(17, 24, 39, 0.04) 0px 8px 8px 0px, rgba(17, 24, 39, 0.04) 0px 4px 4px -2px, rgba(17, 24, 39, 0.04) 0px 2px 2px -1px, rgb(24, 47, 165) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(17, 24, 39, 0.1) 0px 0px 0px 1px, rgba(17, 24, 39, 0.04) 0px 1px 1px -0.5px, rgba(17, 24, 39, 0.04) 0px 3px 3px -1.5px, rgba(17, 24, 39, 0.04) 0px 6px 6px -3px, rgba(17, 24, 39, 0.04) 0px 12px 12px -6px, rgba(17, 24, 39, 0.04) 0px 24px 24px -12px;
}
```
