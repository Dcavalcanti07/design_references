# Balsa — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Balsa employs a modern, structured aesthetic, blending a pristine white canvas with soft, elevated cards to organize content. Typography is deliberately dense and confident, using strong impactful headlines and compact body text to convey information efficiently. A vibrant yellow and deep violet act as functional highlights, drawing attention to calls-to-action and important information within a predominantly achromatic interface. The overall impression is one of clarity, precision, and productivity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#f7f7f7` | `--color-canvas-ice` | Page backgrounds, subtle surface differentiation |
| Surface White | `#ffffff` | `--color-surface-white` | Card backgrounds, primary interactive surfaces |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong headings, primary interactive elements (buttons, links) |
| Graphite | `#313131` | `--color-graphite` | Secondary text, subheadings, supporting information |
| Storm Gray | `#686868` | `--color-storm-gray` | Muted text, helper text, subtle borders |
| Silver Mist | `#bbbbbb` | `--color-silver-mist` | Decorative card backgrounds, subtle dividers |
| Purple Haze | `#914db2` | `--color-purple-haze` | Pink outline accent for tags, dividers, and focused UI edges |
| Goldenrod | `#ffb700` | `--color-goldenrod` | Highlight cards, callout backgrounds, primary accent for important information — adds focus and urgency |
| Midnight Ink Blue | `#003399` | `--color-midnight-ink-blue` | Link text, outlined button borders — a secondary interactive color distinct from black |

## Tokens — Typography

### sans-serif — Fallback or system font for small UI elements and metadata, ensuring broad compatibility. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback or system font for small UI elements and metadata, ensuring broad compatibility.

### Van Condensed Pro Bold — Impactful headings and display text. Its condensed nature allows for larger sizes without consuming excessive horizontal space, while the strong weight ensures immediate attention. The aggressive negative letter-spacing at larger sizes contributes to a tight, assertive visual feel. · `--font-van-condensed-pro-bold`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 24px, 32px, 48px
- **Line height:** 1.20, 1.50
- **Letter spacing:** -0.0470em at 48px, -0.0310em at 32px
- **Role:** Impactful headings and display text. Its condensed nature allows for larger sizes without consuming excessive horizontal space, while the strong weight ensures immediate attention. The aggressive negative letter-spacing at larger sizes contributes to a tight, assertive visual feel.

### Inter — The primary typeface for body copy, subheadings, and UI elements. Its neutrality and high legibility support densely packed information, while various weights provide a clear typographic hierarchy. The consistent slight negative tracking keeps text blocks compact. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 11px, 14px, 16px
- **Line height:** 1.18, 1.20, 1.29, 1.30, 1.43, 1.50, 1.64, 1.73
- **Letter spacing:** -0.0100em
- **Role:** The primary typeface for body copy, subheadings, and UI elements. Its neutrality and high legibility support densely packed information, while various weights provide a clear typographic hierarchy. The consistent slight negative tracking keeps text blocks compact.

### Roboto Mono — Monospaced font for code snippets, technical details, and any content requiring fixed-width alignment. · `--font-roboto-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 11px, 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Monospaced font for code snippets, technical details, and any content requiring fixed-width alignment.

### Noto Sans Mono — Supplementary monospaced font, likely for specific code or data display. Used sparingly. · `--font-noto-sans-mono`
- **Substitute:** Noto Sans Mono
- **Weights:** 400
- **Sizes:** 11px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Supplementary monospaced font, likely for specific code or data display. Used sparingly.

### Inter-Bold — Inter-Bold — detected in extracted data but not described by AI · `--font-inter-bold`
- **Weights:** 700
- **Sizes:** 11px, 14px, 18px
- **Line height:** 1.2, 1.43, 1.64, 2
- **Letter spacing:** -0.01
- **Role:** Inter-Bold — detected in extracted data but not described by AI

### Inter-Medium — Inter-Medium — detected in extracted data but not described by AI · `--font-inter-medium`
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.43, 1.5, 2
- **Role:** Inter-Medium — detected in extracted data but not described by AI

### Inter-Light — Inter-Light — detected in extracted data but not described by AI · `--font-inter-light`
- **Weights:** 300
- **Sizes:** 11px
- **Line height:** 1.73
- **Letter spacing:** -0.01
- **Role:** Inter-Light — detected in extracted data but not described by AI

### Inter-Black — Inter-Black — detected in extracted data but not described by AI · `--font-inter-black`
- **Weights:** 900
- **Sizes:** 24px
- **Line height:** 1.2
- **Role:** Inter-Black — detected in extracted data but not described by AI

### Inter-SemiBold — Inter-SemiBold — detected in extracted data but not described by AI · `--font-inter-semibold`
- **Weights:** 600
- **Sizes:** 32px
- **Line height:** 1.2
- **Role:** Inter-SemiBold — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.73 | -0.11px | `--text-caption` |
| body | 14px | 1.43 | -0.14px | `--text-body` |
| heading-sm | 18px | 1.43 | -0.18px | `--text-heading-sm` |
| heading | 24px | 1.2 | -1.13px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.99px | `--text-heading-lg` |
| display | 48px | 1.2 | -2.26px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 16px |
| cards | 12px |
| buttons | 6px |
| minimal | 1px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(255, 255, 255) 0px 0px 0px 2px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 0px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 60px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action

Solid Ink Black background with Surface White text. Uses a 6px border radius and generous padding of 12px vertical, 8-12px horizontal. Text is typically 12px system sans-serif.

### Outline Accent Button (Midnight Ink Blue)
**Role:** Secondary call-to-action or informational link

Transparent background with a 1px Midnight Ink Blue border and Midnight Ink Blue text. Uses a 6px border radius, 12px vertical padding, and 8-12px horizontal padding. Text is typically 12px system sans-serif.

### Base Card (No Shadow)
**Role:** Content grouping, pricing tiers in neutral state

Background of rgba(255, 255, 255, 0.8) with a 12px border radius. No shadows, giving a flat, clean appearance. Padding is typically absent for these cards, relying on internal element spacing.

### Elevated Content Card
**Role:** Prominent content blocks, feature descriptions

Surface White background, 12px border radius, and a complex, subtle multi-layer shadow stack (rgba(0,0,0,0.09) starting at 0px 2.15px 3px). Provides significant visual lift without adding heavy dark tones. No internal padding defined at the card level.

### Callout Card (Goldenrod)
**Role:** Highlighting key information, warnings, or tips

Goldenrod background, 12px border radius. Uses a subtle, warm shadow tint (rgba(112, 94, 0, 0.05) starting at 0px 2.15px 1.72px). Features consistent internal padding of 20px horizontal and 20-32px vertical. Text in Ink Black.

### Callout Card (Purple Haze)
**Role:** Highlighting secondary key information or status updates

Purple Haze background, 12px border radius. Uses a subtle, cool-toned shadow (rgba(61, 32, 75, 0.05) starting at 0px 2.15px 1.72px). Features consistent internal padding of 20px horizontal and 20-32px vertical. Text in Ink Black.

## Do's and Don'ts

### Do
- Always use Canvas Ice (#f7f7f7) as the base page background.
- Apply Surface White (#ffffff) for all elevated cards and primary UI elements that require a clean, bright backdrop.
- Prioritize Ink Black (#000000) for all primary text and bold headlines to ensure high contrast and readability.
- Reserve Goldenrod (#ffb700) and Purple Haze (#914db2) exclusively for accent cards, callouts, or small functional indicators, never for large background areas or primary text.
- Maintain a clear visual hierarchy by utilizing Van Condensed Pro Bold for main headings and Inter for all body text, with Inter's various weights for subheadings and emphasis.
- Use 12px border-radius for all cards and container elements to maintain the consistent soft, modern feel.
- Ensure generous vertical spacing between sections, using the defined sectionGap of 60px to provide breathing room.

### Don't
- Avoid using multiple different accent colors on a single screen; limit to Goldenrod or Purple Haze for focused attention.
- Do not use dark backgrounds for main content areas; maintain the light theme with Canvas Ice and Surface White providing the primary surfaces.
- Refrain from using strong, opaque shadows; instead, apply the subtle, tiered shadow stacks seen on Elevated Content Cards for a soft lift.
- Do not vary border radius arbitrarily; adhere to 12px for cards and 6px for buttons and interactive elements.
- Avoid decorative imagery that competes with UI elements; imagery should be contained, product-focused, or purely illustrative.
- Do not introduce new typefaces outside of Van Condensed Pro Bold, Inter, Roboto Mono, Noto Sans Mono, or the system sans-serif fallback.
- Exclude heavy gradients or complex background patterns, maintaining the flat and clean aesthetic of the primary surfaces.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Ice | `#f7f7f7` | Base page background |
| 1 | Surface White | `#ffffff` | Primary interactive cards, content blocks, and UI elements |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.09) 0px 2.14989px 3.00985px -0.5625px, rgba(0, 0, 0, 0.086) 0px 5.09563px 7.13388px -1.125px, rgba(0, 0, 0, 0.082) 0px 9.29495px 13.0129px -1.6875px, rgba(0, 0, 0, 0.08) 0px 15.4528px 21.634px -2.25px, rgba(0, 0, 0, 0.075) 0px 24.9551px 34.9371px -2.8125px, rgba(0, 0, 0, 0.063) 0px 40.849px 57.1886px -3.375px, rgba(0, 0, 0, 0.047) 0px 70.3392px 98.4749px -3.9375px, rgba(0, 0, 0, 0.01) 0px 128px 179.2px -4.5px`
- **Callout Card (Goldenrod):** `rgba(112, 94, 0, 0.05) 0px 2.14989px 1.71992px -0.3125px, rgba(112, 94, 0, 0.05) 0px 5.09563px 4.0765px -0.625px, rgba(112, 94, 0, 0.05) 0px 9.29495px 7.43596px -0.9375px, rgba(112, 94, 0, 0.05) 0px 15.4528px 12.3623px -1.25px, rgba(112, 94, 0, 0.05) 0px 24.9551px 19.9641px -1.5625px, rgba(112, 94, 0, 0.05) 0px 40.849px 32.6792px -1.875px, rgba(112, 94, 0, 0.05) 0px 70.3392px 56.2714px -2.1875px, rgba(112, 94, 0, 0.05) 0px 128px 102.4px -2.5px`
- **Callout Card (Purple Haze):** `rgba(61, 32, 75, 0.05) 0px 2.14989px 1.71992px -0.3125px, rgba(61, 32, 75, 0.05) 0px 5.09563px 4.0765px -0.625px, rgba(61, 32, 75, 0.05) 0px 9.29495px 7.43596px -0.9375px, rgba(61, 32, 75, 0.05) 0px 15.4528px 12.3623px -1.25px, rgba(61, 32, 75, 0.05) 0px 24.9551px 19.9641px -1.5625px, rgba(61, 32, 75, 0.05) 0px 40.849px 32.6792px -1.875px, rgba(61, 32, 75, 0.05) 0px 70.3392px 56.2714px -2.1875px, rgba(61, 32, 75, 0.05) 0px 128px 102.4px -2.5px`
- **Focus Ring:** `rgb(255, 255, 255) 0px 0px 0px 2px`

## Imagery

This site uses product screenshots and contained graphical elements. Product screenshots are typically clean, isolated views of the Balsa interface, often shown within a browser frame on a white background, highlighting specific features or workflows. Illustrations are flat, geometric, and follow brand colors, primarily used for decorative accents or simple icons. Iconography is generally outlined or filled, with varying stroke weights, maintaining a functional purpose rather than being purely ornamental. Imagery serves to explain product features and add visual interest in a contained, text-dominant layout.

## Layout

The page model is primarily centered content within a contained width, though the hero section spans full-bleed. The hero presents a centered headline and subtext, followed by a product screenshot on a clean Canvas Ice background. Sections follow a consistent vertical rhythm, with `sectionGap` (60px) providing ample separation. Content is often arranged in simple, centered stacks, or in 3-column card grids for features and pricing. Navigation is a minimal top-right 'Log in' link.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #f7f7f7
- border: no distinct chromatic border color
- accent: #ffb700
- primary action: #000000 (filled action)

**3-5 Example Component Prompts:**
1. Create a large section headline: 'Docs for building software' using Van Condensed Pro Bold, size 48px, weight 400, color Ink Black, letter-spacing -2.26px. Place it above body text 'Balsa is for organizing ideas...' using Inter, size 16px, weight 400, color Graphite, letter-spacing -0.16px, centered, with 32px vertical spacing between the headline and body text.
2. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Design an Elevated Content Card: 12px border radius, Surface White background, applying the 'Elevated Content Card' shadow style. Inside, include a heading 'Starter' (Inter, 18px, weight 700, Ink Black, letter-spacing -0.18px) and a body text paragraph (Inter, 14px, weight 400, Graphite, letter-spacing -0.14px). Internal padding for main content should be 20px.
4. Create a Callout Card (Goldenrod): Goldenrod background, 12px border radius, applying the 'Callout Card (Goldenrod)' shadow style. Text inside should be Ink Black, using Inter 14px weight 400, letter-spacing -0.14px, with 20px horizontal and 20px top padding and 32px bottom padding.
5. Assemble a list item: using Inter, 14px, weight 400, color Ink Black, letter-spacing -0.14px. Pair it with a small icon (say, a checkmark) and ensure 8px `elementGap` between the icon and text.

## Similar Brands

- **Linear** — Similar focus on pristine white surfaces, crisp typography, and subtle elevation for UI elements.
- **Asana** — White background, structured content blocks, and functional use of accent colors to highlight information in a productivity context.
- **Notion** — Clean document-centric interface, emphasis on text presentation, and strategic use of lightweight components.
- **Figma** — Uses a light theme with soft cards and shadows, strong typography for headings, and functional, contained UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #f7f7f7;
  --color-surface-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #313131;
  --color-storm-gray: #686868;
  --color-silver-mist: #bbbbbb;
  --color-purple-haze: #914db2;
  --color-goldenrod: #ffb700;
  --color-midnight-ink-blue: #003399;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-van-condensed-pro-bold: 'Van Condensed Pro Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-noto-sans-mono: 'Noto Sans Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-light: 'Inter-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-black: 'Inter-Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.73;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -1.13px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.99px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -2.26px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-tags: 16px;
  --radius-cards: 12px;
  --radius-buttons: 6px;
  --radius-minimal: 1px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 0px 0px 0px 2px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 0px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px;

  /* Surfaces */
  --surface-canvas-ice: #f7f7f7;
  --surface-surface-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #f7f7f7;
  --color-surface-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #313131;
  --color-storm-gray: #686868;
  --color-silver-mist: #bbbbbb;
  --color-purple-haze: #914db2;
  --color-goldenrod: #ffb700;
  --color-midnight-ink-blue: #003399;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-van-condensed-pro-bold: 'Van Condensed Pro Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-noto-sans-mono: 'Noto Sans Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-light: 'Inter-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-black: 'Inter-Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.73;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -1.13px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.99px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -2.26px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 0px 0px 0px 2px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 0px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px;
}
```
