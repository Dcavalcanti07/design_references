# NEAR — Style Reference
> Midnight command center, electrified data streams.

**Theme:** dark

NEAR utilizes a high-contrast dark theme with a prominent, vibrant green accent that electrifies interactive elements and key brand messaging. Typography is weighty for headings and precise for body text, creating a serious yet cutting-edge atmosphere. Components feature stark black fills, white text, and minimal rounded corners, emphasizing functionality and digital precision over organic softness. The overall aesthetic is one of a 'midnight command center'—dark, digital, and punctuated by bursts of algorithmic green.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary background for dark sections, major component fills, and primary text |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text on dark backgrounds, secondary surface fills for contrast, button text |
| Digital Green | `#00ec97` | `--color-digital-green` | Primary action backgrounds, interactive states, key headings, and brand accents. This color provides a vibrant, almost neon highlight against the dark palette |
| Dark Forrest | `#c7f5d8` | `--color-dark-forrest` | Subtle background for UI blocks or sections, offering a desaturated green context without visual noise |
| Slate Border | `#e5e7eb` | `--color-slate-border` | Dividers, hairline borders for subtle separation, and outlining ghost elements |
| Muted Ash | `#757575` | `--color-muted-ash` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Input Pale | `#f2f1e9` | `--color-input-pale` | Input field backgrounds and borders, providing a soft contrast |

## Tokens — Typography

### FKGrotesk — The primary typeface for all content, from headings to body text. Its weights convey a sense of modern authority, with bold for emphasis and lighter weights for readability. · `--font-fkgrotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 16px, 20px, 24px, 44px, 64px, 80px
- **Line height:** 1.00, 1.09, 1.25, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** The primary typeface for all content, from headings to body text. Its weights convey a sense of modern authority, with bold for emphasis and lighter weights for readability.

### Mona Sans — Reserved for small, highly functional text elements like metadata or labels, providing a compact, technical feel. · `--font-mona-sans`
- **Substitute:** Roboto Mono
- **Weights:** 600
- **Sizes:** 12px
- **Line height:** 1.17
- **Letter spacing:** normal
- **Role:** Reserved for small, highly functional text elements like metadata or labels, providing a compact, technical feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.17 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 44px | 1.09 | — | `--text-heading-lg` |
| display | 64px | 1 | — | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 4px |
| buttons | 4px |
| default | 4px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Highest emphasis button, used for main calls to action.

Filled with Digital Green (#00ec97) background, Ghost White (#ffffff) text. Features 4px border radius. Padding: 10px vertical, 40px horizontal.

### Ghost Button
**Role:** Low emphasis, secondary action button.

Transparent background with Midnight Ink (#000000) text. Border is Slate Border (#e5e7eb) with 0px radius. Padding: 16px.

### Text Input Field
**Role:** Standard input for user data.

Ghost White (#ffffff) background, Midnight Ink (#000000) text. Border is Input Pale (#f2f1e9) with 4px radius. Padding: 12px vertical, 16px horizontal.

### Dropdown Navigation Item
**Role:** Navigation links with hover/active states.

Transparent background, Midnight Ink (#000000) text (on light background areas). No distinct border radius (0px). Padding: 16px.

### Info Card
**Role:** Container for grouped information, often used in grids.

Implicitly defined by content blocks on a Dark Forrest (#c7f5d8) background. Uses 8px radius for outer containers.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#000000) for large background areas and major surface fills.
- Use Digital Green (#00ec97) exclusively for primary interactive elements, significant headlines, and brand accents, avoiding overuse.
- Maintain a clear visual hierarchy by contrasting Ghost White (#ffffff) text against dark backgrounds.
- Apply FKGrotesk with varying weights for all content, using 700 for main headings and 400 for body text.
- Ensure all interactive elements, including buttons and inputs, have a consistent 4px border radius.
- Utilize Slate Border (#e5e7eb) for subtle dividers, outlines, and any non-critical borders.
- Maintain a comfortable density with element gaps of 8px and card padding of 16px.

### Don't
- Do not introduce new saturated colors outside of Digital Green (#00ec97) and Dark Forrest (#c7f5d8).
- Avoid applying excessive box shadows; the design relies on flat surfaces and high-contrast color shifts for depth.
- Do not use generic system fonts; FKGrotesk and Mona Sans are integral to the brand's typographic identity.
- Avoid decorative gradients; the aesthetic is flat with single color fills or background imagery.
- Do not deviate from the dominant dark background theme unless in specific, designated light sections supported by design.
- Do not use border-radius values other than 0px, 4px, or 8px.
- Avoid making Ghost Buttons appear too visually heavy; keep their background transparent or very subtle.

## Imagery

The visual language is characterized by abstract, digital generative graphics and iconography. Imagery often features star-like arrays or intricate data streams in varying shades of green, set against deep dark backgrounds. There are no full-bleed photographs or lifestyle imagery. Icons are minimalistic, outlined or filled, mostly in white against black, or in the brand's digital green. The density is moderate, with images serving as atmospheric backdrops or conceptual illustrations rather than content-heavy visuals.

## Layout

The page primarily uses a full-bleed layout for sections, often with centered content within a hidden max-width container, appearing to be around 1200px. The hero section is full-bleed, featuring a dark background with centered, large-scale typography and calls to action. Section rhythm is marked by distinct background changes, alternating between deep black and gradients of digital green. Content commonly uses centered stacks for headlines and subtext, with multi-column layouts for feature displays. Navigation is a sticky top bar, prominent in Ghost White on Midnight Ink, with dropdowns for sub-menus.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e5e7eb
accent: #c7f5d8
primary action: #00ec97 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #00ec97 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a Ghost Button: Transparent background, Midnight Ink (#000000) text 'Resources', bordered with Slate Border (#e5e7eb), 0px radius. Padding: 16px.
3. Create an Input Field: Ghost White (#ffffff) background, Midnight Ink (#000000) text, bordered with Input Pale (#f2f1e9), 4px radius. Padding: 12px vertical, 16px horizontal.
4. Create a Feature Card: Dark Forrest (#c7f5d8) background, 8px radius. Heading 'Unified Commerce' using FKGrotesk weight 500, size 24px, Midnight Ink (#000000) color. Body text 'Unlock asset liquidity.' using FKGrotesk weight 400, size 16px, Midnight Ink (#000000) color. Padding: 16px.

## Similar Brands

- **Solana** — Similar dark theme with a single prominent accent color for interactive elements and brand recognition.
- **Polygon** — Shares the use of abstract digital graphics and a focus on serious, tech-driven typography.
- **Ethereum** — Employs a high-contrast, functional UI with emphasis on clear type and minimal visual clutter, common in blockchain platforms.
- **Chainlink** — Utilizes a dark background with strong typographic statements and a direct, functional component style. 

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-digital-green: #00ec97;
  --color-dark-forrest: #c7f5d8;
  --color-slate-border: #e5e7eb;
  --color-muted-ash: #757575;
  --color-input-pale: #f2f1e9;

  /* Typography — Font Families */
  --font-fkgrotesk: 'FKGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.17;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.09;
  --text-display: 64px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-176: 176px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-inputs: 4px;
  --radius-buttons: 4px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-digital-green: #00ec97;
  --color-dark-forrest: #c7f5d8;
  --color-slate-border: #e5e7eb;
  --color-muted-ash: #757575;
  --color-input-pale: #f2f1e9;

  /* Typography */
  --font-fkgrotesk: 'FKGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.17;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.09;
  --text-display: 64px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
}
```
