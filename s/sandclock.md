# Sandclock — Style Reference
> Midnight Command Center: Tightly tracked typography and a single digital-green accent on a deep, dark canvas.

**Theme:** dark

Sandclock applies a 'midnight command center' aesthetic, designed for focus and serious financial operations. It balances a deep, near-black canvas with crisp white typography and a vibrant green accent to highlight key data and interactive elements. Surfacing is achieved through subtle tonal shifts rather than heavy shadows, maintaining a lightweight feel. Typography is functional and modern, with generous letter-spacing for standard text and tightly tracked headings for immediate impact.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#0a0a0a` | `--color-absolute-zero` | Page backgrounds, card containers, dark button text – creates deep, immersive canvas |
| Deep Space | `#171717` | `--color-deep-space` | Elevated card backgrounds, inner surface containers – provides subtle layering on top of Absolute Zero |
| Void Black | `#222222` | `--color-void-black` | Default card backgrounds, secondary button background, borders – provides primary surface elevation and structure |
| Cosmic Dust | `#9b9b9b` | `--color-cosmic-dust` | Muted body text, secondary headings, helper text – for less prominent information |
| Starlight White | `#ffffff` | `--color-starlight-white` | Primary text, prominent headings, button backgrounds, interactive elements – provides high contrast against dark surfaces |
| Digital Green | `#3fe280` | `--color-digital-green` | Primary action buttons, accented text, active navigation indicators – provides positive confirmation and calls to action |

## Tokens — Typography

### Inter — Body text, navigation, buttons, subheadings – provides clear, readable content with slightly open tracking. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px, 24px, 36px
- **Line height:** 1.11, 1.33, 1.40, 1.43, 1.50
- **Letter spacing:** 0.05em
- **Role:** Body text, navigation, buttons, subheadings – provides clear, readable content with slightly open tracking.

### DM Sans — Secondary body text emphasis – a slightly more condensed option for specific emphasis without heavy tracking. · `--font-dm-sans`
- **Substitute:** sans-serif
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Secondary body text emphasis – a slightly more condensed option for specific emphasis without heavy tracking.

### Aeonik — Display headings – large size and tight negative letter-spacing (-0.025em) provide a distinctive, contemporary headline aesthetic that feels authoritative through its precise compression. · `--font-aeonik`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 72px
- **Line height:** 1.00
- **Letter spacing:** -0.025em
- **Role:** Display headings – large size and tight negative letter-spacing (-0.025em) provide a distinctive, contemporary headline aesthetic that feels authoritative through its precise compression.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.05px | `--text-caption` |
| body-sm | 16px | 1.43 | 0.05px | `--text-body-sm` |
| body | 20px | 1.4 | 0.05px | `--text-body` |
| subheading | 24px | 1.33 | 0.05px | `--text-subheading` |
| heading | 36px | 1.11 | 0.05px | `--text-heading` |
| display | 72px | 1 | -0.025px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 64px |
| cards | 12px |
| buttons | 16px |
| bodyMask | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(24, 39, 75, 0.08) 0px 2px 3px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Pill Ghost Button (Connect Wallet)
**Role:** Main navigation action

Rounded button with Starlight White text on a transparent background, 64px border radius, 8px vertical and 12px horizontal padding. The transparent background implies a less 'committing' action until a connection is made.

### Primary Action Button (Digital Green)
**Role:** Key call to action

Filled button with Digital Green background and Absolute Zero text, 16px border radius, 8px vertical and 16px horizontal padding. Signals the most important user action.

### Secondary Action Button (Void Black)
**Role:** Alternative action button

Filled button with Void Black background and Starlight White text, 16px border radius, 8px vertical and 16px horizontal padding. Offers a clear secondary choice without competing visually with the primary action.

### Feature Card
**Role:** Content grouping

Rectangular card with Void Black background, 12px border radius, and 16px of padding on all sides. Used for grouping related content blocks.

### Vault Performance Card
**Role:** Key data display

Container with Deep Space background, 10px border radius, and 32px vertical padding (0px horizontal). Emphasizes key financial metrics.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#0a0a0a) or Void Black (#222222) as background for deep, immersive surfaces, reserving Deep Space (#171717) for subtle elevation.
- Use Starlight White (#ffffff) for all primary text and critical information to maintain high contrast and readability on dark backgrounds.
- Apply Digital Green (#3fe280) exclusively for primary calls to action, active states, and select data highlights to maintain its impact.
- Ensure headings use Aeonik at weight 400 with tight letter-spacing (-0.025em) for distinct branding.
- Use Inter font family for all body text, navigation, and button labels, applying a slightly open letter-spacing of 0.05em.
- Apply a 12px border radius to all cards and content containers for a consistent, subtly rounded aesthetic.
- Maintain comfortable spacing: 16px between elements and 48px between major sections.

### Don't
- Do not introduce additional vibrant colors; the color palette should remain limited to the specified neutrals and the single Digital Green accent.
- Avoid heavy drop shadows; elevation should primarily be communicated through background color shifts between Absolute Zero, Deep Space, and Void Black.
- Do not use generic system fonts for prominent headings; Aeonik's specific weight and tight tracking are critical to the brand voice.
- Don't use highly dense layouts; ensure ample 16px element spacing and 48px section spacing to maintain readability and focus.
- Avoid small, hard-to-read text. Use Inter 14px as the minimum body text size with a line height of 1.5 for optimal readability.

## Imagery

This site uses a mix of practical, functional iconography and occasional abstract graphics. Icons are monochrome (Starlight White or Cosmic Dust) and mostly filled, with a medium stroke weight where outlines appear, used for functional clarity and status. Graphic elements are minimal and serve more as background textures or subtle decorative touches rather than prominent visuals. There is an absence of photography or complex illustrations, emphasizing a serious, data-focused, and UI-driven product experience. Imagery is low-density, focusing on supporting UI elements rather than being decorative.

## Layout

The page maintains a centered, max-width layout, though the exact max-width is not strictly enforced, allowing sections to breathe. The hero section is full-bleed, dark, featuring a large, centered headline and subtext, followed by two action buttons nested below. Content sections typically alternate between full-width horizontal content blocks (like partner logos) and structured responsive grids (e.g., two-column metric displays or three-column announcement cards). Vertical rhythm is established with consistent 48px section gaps. The navigation is a classic top bar, sticky in appearance, keeping key links and the 'Connect Wallet' button accessible.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #0a0a0a
border: #222222
accent: #3fe280
primary action: #3fe280 (filled action)

Example Component Prompts:
Create a hero section: Absolute Zero background. Headline at 72px Aeonik weight 400, #ffffff, letter-spacing -0.025em. Subtext at 20px Inter weight 400, #9b9b9b, letter-spacing 0.05em. Two buttons: 'Start Earning' (Digital Green background, Absolute Zero text, 16px radius, 8px 16px padding) and 'Buy QUARTZ' (Void Black background, Starlight White text, 16px radius, 8px 16px padding).

Create a Feature Card: Void Black background, 12px border radius, 16px padding. Title at 24px Inter weight 500, #ffffff, letter-spacing 0.05em. Body text at 16px Inter weight 400, #9b9b9b, letter-spacing 0.05em. Icon (Starlight White).

Create a Pill Ghost Button: Starlight White text, 64px border radius, 8px vertical and 12px horizontal padding. Border 1px solid #ffffff.

## Similar Brands

- **Aave** — Similar dark-mode DeFi interface with prominent information display and clear CTAs.
- **Uniswap** — Shares a clean, dark aesthetic with distinct accent colors for interactive elements in a crypto context.
- **Nansen** — Employs a sophisticated dark UI with a focus on data presentation and functional clarity for financial insights.
- **DeFi Llama** — Uses dark backgrounds, clear typography, and minimal color accents to present complex financial data effectively.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #0a0a0a;
  --color-deep-space: #171717;
  --color-void-black: #222222;
  --color-cosmic-dust: #9b9b9b;
  --color-starlight-white: #ffffff;
  --color-digital-green: #3fe280;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.05px;
  --text-body: 20px;
  --leading-body: 1.4;
  --tracking-body: 0.05px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.05px;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --tracking-heading: 0.05px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 64px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pill: 64px;
  --radius-cards: 12px;
  --radius-buttons: 16px;
  --radius-bodymask: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(24, 39, 75, 0.08) 0px 2px 3px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #0a0a0a;
  --color-deep-space: #171717;
  --color-void-black: #222222;
  --color-cosmic-dust: #9b9b9b;
  --color-starlight-white: #ffffff;
  --color-digital-green: #3fe280;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.05px;
  --text-body: 20px;
  --leading-body: 1.4;
  --tracking-body: 0.05px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.05px;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --tracking-heading: 0.05px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 64px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(24, 39, 75, 0.08) 0px 2px 3px 0px;
}
```
