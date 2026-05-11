# Control — Style Reference
> Terminal aesthetic, industrial, high-contrast, no-frills

**Theme:** light

Control presents a stark, high-contrast digital canvas, reminiscent of a developer's IDE or terminal, prioritizing clear information display over decorative flourishes. Its aesthetic is defined by a dominant black-on-white text, punctuated by precise, functional pops of vivid green and orange. Typefaces are chosen for their technical, almost glitch-art quality, and components adhere to a sharp, unrounded aesthetic, mirroring command-line interfaces or early web design. The overall impression is one of directness, utility, and a slight retro-futuristic edge.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary content areas |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong borders, dark overlay backgrounds |
| Smoke Gray | `#f5f5f4` | `--color-smoke-gray` | Subtle background for secondary sections or elevated cards |
| Ghost Gray | `#d2d2d2` | `--color-ghost-gray` | Muted text, subtle borders, inactive elements |
| Utility Gray | `#3d3d3d` | `--color-utility-gray` | Secondary text, component borders, subtle backgrounds for content blocks |
| Subtle Gray | `#c6c6c0` | `--color-subtle-gray` | Sub-footer text, fine lines, subtle ghost element borders |
| Muted Gray | `#babab9` | `--color-muted-gray` | Helper text, less prominent information, subtle borders |
| Inert Gray | `#acaca6` | `--color-inert-gray` | Inactive interface elements, placeholder text, lightest accent details |
| Action Orange | `#ff5c02` | `--color-action-orange` | Orange action color for filled buttons, selected navigation states, and focused conversion moments. |
| Highlight Green | `#01ea40` | `--color-highlight-green` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis |
| Accent Yellow | `#ffdb4d` | `--color-accent-yellow` | Decorative highlights, specific labels, component borders — adds a secondary visual pop |
| Dim Gray | `#7a7a7a` | `--color-dim-gray` | Neutral button treatment for secondary actions and selected controls. |

## Tokens — Typography

### Melange — Headlines and display text — its sharp, angular forms and tight tracking give a bold, almost 'sliced' aesthetic · `--font-melange`
- **Substitute:** Georgia Pro
- **Weights:** 500
- **Sizes:** 16px, 25px, 36px, 71px, 146px
- **Line height:** 1.01, 1.03, 1.06, 1.07, 1.52, 2.38
- **Letter spacing:** -0.058em at 146px, -0.055em at 71px, -0.051em at 36px, -0.050em at 25px, -0.037em at 16px
- **Role:** Headlines and display text — its sharp, angular forms and tight tracking give a bold, almost 'sliced' aesthetic

### Favorit Mono — Interface labels, navigation, secondary body text, and any element requiring a monospaced, technical feel; its uniform width aligns with the grid-based visual language · `--font-favorit-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 9px, 10px, 16px
- **Line height:** 1.20, 1.33, 2.00, 2.20, 2.38, 2.40
- **Letter spacing:** -0.03em at 16px, 0.02em at 10px, -0.037em for general use
- **Role:** Interface labels, navigation, secondary body text, and any element requiring a monospaced, technical feel; its uniform width aligns with the grid-based visual language

### Arial — Default body text and general interface elements where a sans-serif is needed for legibility, providing a baseline of clarity against the more stylized typefaces · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Default body text and general interface elements where a sans-serif is needed for legibility, providing a baseline of clarity against the more stylized typefaces

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.2 | -0.48px | `--text-body` |
| subheading | 25px | 1.07 | -1.25px | `--text-subheading` |
| heading | 36px | 1.06 | -1.84px | `--text-heading` |
| heading-lg | 71px | 1.03 | -3.9px | `--text-heading-lg` |
| display | 146px | 1.01 | -8.47px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 15 | 15px | `--spacing-15` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| pill | 273px |
| large | 40px |
| small | 8px |
| button | 0px |

### Layout

- **Section gap:** 64px
- **Card padding:** 0px
- **Element gap:** 15px

## Components

### Primary Action Button (Filled)
**Role:** CTA button for primary actions

Solid Action Orange (#ff5c02) background with Canvas White (#ffffff) text. No border radius, sharp corners for a direct interaction feel. Padding as per content, but typically 0px implicitly around text.

### Secondary Action Button (Filled)
**Role:** CTA button for secondary actions

Solid Dim Gray (#7a7a7a) background with Ink Black (#000000) text. No border-radius. Used for 'Reject' type actions.

### Ghost Link Button
**Role:** Tertiary navigation or interactive elements

Transparent background with Highlight Green (#01ea40) text and border. No border-radius. Emphasizes interaction without visual weight.

### Info Card
**Role:** Content container for information grouping

Canvas White (#ffffff) background with an 8px border-radius, giving a slightly softer edge than buttons. No box-shadow for a flat, un-elevated appearance. Implicit padding for content.

### Elevated Card
**Role:** Content container with slight visual separation

Smoke Gray (#f5f5f4) background, 8px border-radius. Again, no shadow. Used for distinguishing content blocks from the main Canvas White background.

### Cookie Consent Panel
**Role:** System message overlay

A dark, somewhat translucent panel (not precisely specified, but visually #3d3d3d or #000000) with no border radius, containing buttons for user choices. Displays a stark, functional warning.

## Do's and Don'ts

### Do
- Use Ink Black (#000000) for all primary text and strong borders against white backgrounds.
- Implement sharp, unrounded corners (radius: 0px) for all interactive buttons and inputs to maintain a utilitarian aesthetic.
- Utilize Type Melange for prominent headlines, applying its tight negative letter-spacing for visual impact.
- Incorporate Favorit Mono for all navigation, small labels, and any text that benefits from a consistent, technical monospaced feel.
- Reserve Action Orange (#ff5c02) exclusively for primary 'accept' or 'start' actions; use Highlight Green (#01ea40) only for active links and positive states.
- Maintain a clear visual hierarchy by limiting color pops to functional accents; keep main content and backgrounds in the neutral palette.
- Ensure generous use of Canvas White (#ffffff) for backgrounds to create a highly readable, open design reminiscent of a blank workspace.

### Don't
- Do not use rounded corners on any buttons or inputs; maintain the 0px radius for a consistent, sharp aesthetic.
- Avoid gradients or complex shadows for elevation; rely on solid colors and borders for visual separation.
- Do not introduce additional chromatic colors beyond Action Orange, Highlight Green, and Accent Yellow, to preserve the stark, focused palette.
- Do not use overly decorative imagery or soft, organic shapes; stick to geometric forms and high-contrast visuals.
- Do not use multiple font sizes or weights haphazardly; adhere strictly to the defined type scale and its associated styles.
- Avoid soft, desaturated background tones for primary content areas; ensure strong contrast with Ink Black (#000000) text on Canvas White (#ffffff).
- Do not use subtle gray (#babab9, #acaca6) text on white backgrounds for primary content, as it lacks sufficient contrast and dilutes the bold aesthetic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base layer for all content. |
| 1 | Smoke Gray | `#f5f5f4` | Slightly elevated card backgrounds, secondary sections for visual separation without direct elevation. |

## Imagery

The site primarily uses product screenshots and abstract, grid-based graphics that mimic a design tool interface. Screenshots appear within a faux browser/canvas frame, often cropped to show key UI elements. Photography, when present, is usually contained within these frames, often with a somewhat distressed or low-fi quality. Icons are minimal, outlined, or solid black, maintaining the utilitarian, high-contrast theme. Imagery serves to demonstrate the product's functionality and aesthetic rather than decorative atmosphere, often appearing within a green grid overlay, reinforcing the idea of a design workspace.

## Layout

The page primarily uses a full-bleed layout, particularly in the hero section, which features a large, centered headline and subtext over the Canvas White background. Content then transitions into a series of full-width blocks, often alternating between stark black text on white and areas incorporating the distinct grid graphic. There's a strong emphasis on consistent vertical spacing between sections. The overall presentation is somewhat sparse, giving breathing room to the bold typography and contained product visuals. Navigation is a simple, right-aligned text menu in the header, with social links also following this minimalist approach.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #000000
- accent: #01ea40
- primary action: #ff5c02 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff5c02 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a header navigation link: using Favorit Mono at 16px, weight 400, Ink Black (#000000) text. On hover, change text to Highlight Green (#01ea40).
3. Construct an Info Card: Canvas White (#ffffff) background, 8px border-radius, no shadow. Content to use Ink Black (#000000) for titles (Melange, 36px, weight 500, letter-spacing -1.84px) and Utility Gray (#3d3d3d) for body text (Arial, 16px, weight 400).

## Similar Brands

- **Webflow** — Shares a direct, product-focused UI with an emphasis on visual development tools and a clean design.
- **Framer** — Utilizes a clean, high-contrast interface with custom typography and strong visual branding for a design tool.
- **Linear** — Exhibits a similar minimalist aesthetic, high-contrast text on neutral backgrounds, and precise, functional use of color accents.
- **Notion** — Employs an unadorned, high-contrast document-centric design with an emphasis on textual information and a clean, almost 'blank canvas' feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-smoke-gray: #f5f5f4;
  --color-ghost-gray: #d2d2d2;
  --color-utility-gray: #3d3d3d;
  --color-subtle-gray: #c6c6c0;
  --color-muted-gray: #babab9;
  --color-inert-gray: #acaca6;
  --color-action-orange: #ff5c02;
  --color-highlight-green: #01ea40;
  --color-accent-yellow: #ffdb4d;
  --color-dim-gray: #7a7a7a;

  /* Typography — Font Families */
  --font-melange: 'Melange', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-mono: 'Favorit Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.48px;
  --text-subheading: 25px;
  --leading-subheading: 1.07;
  --tracking-subheading: -1.25px;
  --text-heading: 36px;
  --leading-heading: 1.06;
  --tracking-heading: -1.84px;
  --text-heading-lg: 71px;
  --leading-heading-lg: 1.03;
  --tracking-heading-lg: -3.9px;
  --text-display: 146px;
  --leading-display: 1.01;
  --tracking-display: -8.47px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-15: 15px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 0px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 40px;
  --radius-full: 80px;
  --radius-full-2: 273px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-pill: 273px;
  --radius-large: 40px;
  --radius-small: 8px;
  --radius-button: 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-smoke-gray: #f5f5f4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-smoke-gray: #f5f5f4;
  --color-ghost-gray: #d2d2d2;
  --color-utility-gray: #3d3d3d;
  --color-subtle-gray: #c6c6c0;
  --color-muted-gray: #babab9;
  --color-inert-gray: #acaca6;
  --color-action-orange: #ff5c02;
  --color-highlight-green: #01ea40;
  --color-accent-yellow: #ffdb4d;
  --color-dim-gray: #7a7a7a;

  /* Typography */
  --font-melange: 'Melange', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-mono: 'Favorit Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.48px;
  --text-subheading: 25px;
  --leading-subheading: 1.07;
  --tracking-subheading: -1.25px;
  --text-heading: 36px;
  --leading-heading: 1.06;
  --tracking-heading: -1.84px;
  --text-heading-lg: 71px;
  --leading-heading-lg: 1.03;
  --tracking-heading-lg: -3.9px;
  --text-display: 146px;
  --leading-display: 1.01;
  --tracking-display: -8.47px;

  /* Spacing */
  --spacing-15: 15px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 40px;
  --radius-full: 80px;
  --radius-full-2: 273px;
}
```
