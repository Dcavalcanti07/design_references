# Drive Capital — Style Reference
> Type-driven retro blueprint

**Theme:** light

Drive Capital uses a distinct print-inspired visual style, featuring bold, condensed typography and subtle parchment-like backgrounds. The visual system is built around a single, vibrant blue accent color against a warm, off-white canvas, lending a retro yet impactful feel. Visuals are intentionally sparse, relying on strong typographic hierarchy and clean, outlined component styling to convey information. The overall impression is one of purposeful simplicity and understated confidence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment | `#fff8f1` | `--color-parchment` | Page background, text for contrast, faint accents |
| Steel Blue | `#e2e8f0` | `--color-steel-blue` | Decorative dividers, subtle borders |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong borders |
| Drive Blue | `#006eff` | `--color-drive-blue` | Primary headings, interactive elements, button borders, decorative strokes — the single splash of vivid color in an otherwise subdued palette |

## Tokens — Typography

### Founders Grotesk — Body copy, captions, buttons, and subheadings. Its condensed width and precise tracking keep text compact and intentional. · `--font-founders-grotesk`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 16px, 18px, 21px, 28px, 38px
- **Line height:** 0.95, 1.00, 1.20, 1.25, 1.50
- **Letter spacing:** -0.0200em
- **OpenType features:** `"clig", "liga"`
- **Role:** Body copy, captions, buttons, and subheadings. Its condensed width and precise tracking keep text compact and intentional.

### Editorial New — Dominant display headlines. Its delicate thin weights and generous sizing create a bold yet elegant statement, contrasting with the dense body copy. · `--font-editorial-new`
- **Substitute:** Lora
- **Weights:** 100, 300
- **Sizes:** 62px, 77px, 120px
- **Line height:** 0.95, 1.00
- **Letter spacing:** -0.0200em
- **OpenType features:** `"clig", "liga"`
- **Role:** Dominant display headlines. Its delicate thin weights and generous sizing create a bold yet elegant statement, contrasting with the dense body copy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.5 | -0.32px | `--text-caption` |
| body | 18px | 1.25 | -0.36px | `--text-body` |
| subheading | 21px | 1.2 | -0.42px | `--text-subheading` |
| heading-sm | 28px | 1 | -0.56px | `--text-heading-sm` |
| heading | 38px | 0.95 | -0.76px | `--text-heading` |
| heading-lg | 62px | 1 | -1.24px | `--text-heading-lg` |
| display | 120px | 0.95 | -2.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 20 | 20px | `--spacing-20` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 43 | 43px | `--spacing-43` |
| 144 | 144px | `--spacing-144` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 60.0048px |

### Layout

- **Section gap:** 29px
- **Card padding:** 14px
- **Element gap:** 20px

## Components

### Outline Button - Tickets
**Role:** Primary interactive element for calls to action.

An outlined button with text in Drive Blue (#006eff) and a 1px border in Drive Blue (#006eff). It features a very high border-radius of 60.0048px, giving it a pill shape. Padding is 10.8px top/bottom and 43.2px left/right. Uses Founders Grotesk typography.

### Section Divider
**Role:** Visual separation between content blocks.

A thin 1px horizontal line in Steel Blue (#e2e8f0), used to delineate sections or information groups without heavy visual interruption. Often paired with generous vertical spacing above and below.

## Do's and Don'ts

### Do
- Prioritize Founders Grotesk for all functional text, bodies, and button labels at its specified weights and letter-spacing.
- Use Editorial New only for large, impactful headlines, adhering to its thin weights and precise letter-spacing for maximum effect.
- Maintain the Parchment (#fff8f1) background for most surfaces to preserve the light, minimal aesthetic.
- Employ Drive Blue (#006eff) sparingly as the primary accent for interactive elements, headlines, and key visual markers.
- Use the pill-shaped button style with a 60.0048px radius for all interactive buttons to maintain consistency.
- Apply generous vertical spacing, primarily 29px for sections and 20px between elements, to create a spacious layout.
- Delineate content with thin Steel Blue (#e2e8f0) lines rather than heavy boxes or shadows.

### Don't
- Avoid using multiple chromatic colors; limit color accents strictly to Drive Blue (#006eff).
- Do not introduce shadows; the design relies on flat surfaces and outlines for depth.
- Do not deviate from the specified typefaces, Founders Grotesk and Editorial New, or their provided weights and letter-spacing.
- Avoid tight vertical spacing; allow elements and sections to breathe.
- Do not use solid background colors for buttons; stick to the outlined treatment with Drive Blue.
- Avoid using images or heavy graphics that detract from the type-driven aesthetic, unless they are simple, line-art illustrations.
- Do not use dark backgrounds; the system is designed exclusively for a light theme with the Parchment primary background.

## Imagery

The site uses minimal, simple, and clean line-art style illustrations, as seen with the car graphic. These illustrations are typically brand-colored with slight shading, serving a decorative and thematic role rather than conveying complex information. Icons are outlined, simple, and mono-color (Drive Blue). The imagery is sparse, allowing text and typography to dominate the visual hierarchy. Density is text-heavy.

## Layout

The page enforces a centered, contained layout for most content, with a max-width likely controlled by the prominent 144px left/right padding. The hero section often combines a large, centered headline with a relevant line-art illustration. Sections are separated by simple horizontal lines and generous vertical spacing, creating an airy rhythm. Content blocks appear to be stacked vertically, often with smaller sub-sections using a two-column distribution for dates and times, or left-right alignment for text and prompts. Navigation is minimal, likely restricted to a top header with limited links or implied by the page structure itself rather than a persistent nav bar.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fff8f1
border: #e2e8f0
accent: #006eff
primary action: #006eff (outlined action border)

Example Component Prompts:
1. Create a hero banner: Parchment (#fff8f1) background. Centered headline 'THE SUMMER DRIVE' in Editorial New, size 120px, weight 300, Drive Blue (#006eff), letter-spacing -2.4px. Below it, a thin Steel Blue (#e2e8f0) divider line, followed by a lighter text 'A NO-WORK, WORK-EVENT...' in Founders Grotesk, size 21px, weight 300, Midnight Ink (#000000), letter-spacing -0.42px. Beneath, place a line-art illustration of a car.
2. Create an event detail block: Parchment (#fff8f1) background. Left-aligned date '06.24.21', Founders Grotesk, size 38px, weight 300, Drive Blue (#006eff), letter-spacing -0.76px. Above it, a small label 'DATE' in Founders Grotesk, size 16px, weight 400, Midnight Ink (#000000). To the right, a similar block for 'TIME' and '5-10 PM'. Use a thin Steel Blue (#e2e8f0) divider between these pairs and the main headline section.
3. Create an outlined button for 'Tickets': Background transparent, 1px border in Drive Blue (#006eff), text 'Tickets' in Founders Grotesk, size 18px, weight 400, Drive Blue (#006eff), letter-spacing -0.36px. Border radius 60.0048px. Padding 10.8px vertical, 43.2px horizontal. Place two, side-by-side: one under 'STANDARD HALL' and one under 'RESERVE NOW'.

## Similar Brands

- **AIGA** — Strong emphasis on typography as a primary design element, often with condensed or display typefaces.
- **Figma - Config events** — Event-focused pages often use bold, impactful type as the main visual draw, with a limited color palette.
- **Verge** — Uses a clean, print-inspired aesthetic with strong typographic choices and a limited, impactful color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment: #fff8f1;
  --color-steel-blue: #e2e8f0;
  --color-midnight-ink: #000000;
  --color-drive-blue: #006eff;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --tracking-caption: -0.32px;
  --text-body: 18px;
  --leading-body: 1.25;
  --tracking-body: -0.36px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.42px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.56px;
  --text-heading: 38px;
  --leading-heading: 0.95;
  --tracking-heading: -0.76px;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.24px;
  --text-display: 120px;
  --leading-display: 0.95;
  --tracking-display: -2.4px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-7: 7px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-43: 43px;
  --spacing-144: 144px;
  --spacing-150: 150px;

  /* Layout */
  --section-gap: 29px;
  --card-padding: 14px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-full: 60.0048px;

  /* Named Radii */
  --radius-buttons: 60.0048px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment: #fff8f1;
  --color-steel-blue: #e2e8f0;
  --color-midnight-ink: #000000;
  --color-drive-blue: #006eff;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --tracking-caption: -0.32px;
  --text-body: 18px;
  --leading-body: 1.25;
  --tracking-body: -0.36px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.42px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.56px;
  --text-heading: 38px;
  --leading-heading: 0.95;
  --tracking-heading: -0.76px;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.24px;
  --text-display: 120px;
  --leading-display: 0.95;
  --tracking-display: -2.4px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-43: 43px;
  --spacing-144: 144px;
  --spacing-150: 150px;

  /* Border Radius */
  --radius-full: 60.0048px;
}
```
