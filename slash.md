# Slash — Style Reference
> Midnight Ledger, Obsidian Surfaces

**Theme:** dark

Slash adopts a high-contrast dark mode aesthetic for business finance: black canvases, subtly layered dark gray surfaces, and a striking white primary text. Inter typography provides utilitarian clarity, while Ivy Presto adds a touch of classic sophistication to display headlines. The system minimizes color, primarily using off-white for interaction and a warm, golden gradient for subtle accents and visual depth on elevated elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page background, deepest surface level. Creates a sense of depth and seriousness |
| Obsidian Surface | `#030304` | `--color-obsidian-surface` | Elevated card backgrounds, deeper shadows. A subtle lift from the main background |
| Charcoal Canvas | `#08080a` | `--color-charcoal-canvas` | Primary surface background, such as panels and main content areas |
| Pewter Accent | `#121317` | `--color-pewter-accent` | Subtle background for card, button, and other interactive elements, providing a soft lift |
| Slate Gray | `#1c1d22` | `--color-slate-gray` | Component backgrounds, such as card details and selected states. Less saturated than Charcoal Canvas |
| Ash Text | `#5e616e` | `--color-ash-text` | Muted secondary text, placeholder text, subtle borders. For less prominent information |
| Stone Text | `#777a88` | `--color-stone-text` | Tertiary text, subtle icons, inactive navigation items. Lower hierarchy content |
| Silver Text | `#acafb9` | `--color-silver-text` | Helper text, slightly more prominent than Stone Text |
| Porcelain Text | `#cdcdcd` | `--color-porcelain-text` | Less important body text, slight relief from pure white |
| White Frost | `#e2e3e9` | `--color-white-frost` | Dominant body text, strong contrast against dark backgrounds. Also used for outlined borders |
| Pure White | `#ffffff` | `--color-pure-white` | Primary headings, active states, emphasized text, and button backgrounds. The brightest element |
| Golden Gradient | `linear-gradient(103deg, rgb(174, 147, 87), rgb(255, 240, 204) 40%, rgb(174, 147, 87) 70%, rgba(189, 157, 79, 0))` | `--color-golden-gradient` | Decorative highlights, subtle hover effects, linear gradients for elevated elements. Provides a touch of luxury and prestige |

## Tokens — Typography

### Inter — Primary typeface for all UI elements, body text, and functional components. Its clean, sans-serif design maintains legibility and a modern, technical feel across various densities and scales. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 20px, 24px, 32px, 48px, 52px
- **Line height:** 1.00, 1.13, 1.25, 1.33, 1.38, 1.43, 1.50, 1.56
- **Letter spacing:** -0.007, -0.007, -0.013, -0.013, -0.02, -0.02, -0.022, -0.025, -0.025, -0.04, -0.04
- **Role:** Primary typeface for all UI elements, body text, and functional components. Its clean, sans-serif design maintains legibility and a modern, technical feel across various densities and scales.

### Ivy Presto — Decorative display typeface for large, impactful headlines and hero text. The serif design provides an air of traditional luxury and authority, contrasting with the utilitarian Inter. · `--font-ivy-presto`
- **Substitute:** Playfair Display
- **Weights:** 400, 500
- **Sizes:** 32px, 52px, 64px, 88px
- **Line height:** 1.00, 1.13, 1.25
- **Letter spacing:** 0.01, 0.01, 0.01, 0.01
- **Role:** Decorative display typeface for large, impactful headlines and hero text. The serif design provides an air of traditional luxury and authority, contrasting with the utilitarian Inter.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.007px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.013px | `--text-body-sm` |
| body | 16px | 1.38 | -0.02px | `--text-body` |
| subheading | 20px | 1.33 | -0.022px | `--text-subheading` |
| heading | 32px | 1.25 | -0.025px | `--text-heading` |
| heading-lg | 48px | 1.13 | -0.04px | `--text-heading-lg` |
| display | 88px | 1 | 0.01px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 105 | 105px | `--spacing-105` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| md | 10px |
| sm | 2px |
| none | 0px |
| pill | 9999px |

### Layout

- **Page max-width:** 1216px
- **Section gap:** 160px
- **Card padding:** 32px
- **Element gap:** 6px

## Components

### Ghost Navigation Link
**Role:** Navigation links and subtle interactive text.

backgroundColor: rgba(0, 0, 0, 0), color: Pure White (#ffffff), border: none, borderRadius: 0px, padding: 20px 0px.

### Pill Primary Button
**Role:** Main call-to-action buttons.

backgroundColor: Pure White (#ffffff), color: Charcoal Canvas (#08080a), border: none, borderRadius: 9999px, padding: 0px 32px.

### Pill Ghost Button
**Role:** Secondary action buttons, less prominent than primary.

backgroundColor: rgba(0, 0, 0, 0), color: Pure White (#ffffff), border: 1px solid Pure White (#ffffff), borderRadius: 9999px, padding: 6px 10px.

### Sharp Ghost Text Button
**Role:** Minimal interactive elements without strong visual weight.

backgroundColor: rgba(0, 0, 0, 0), color: Pure White (#ffffff), border: none, borderRadius: 4px, padding: 0px 8px.

### Card Standard
**Role:** Container for content sections.

backgroundColor: rgba(0, 0, 0, 0), borderRadius: 10px, boxShadow: none, padding: 0px.

### Pill Input Field
**Role:** Form input fields.

backgroundColor: rgba(0, 0, 0, 0), color: Pure White (#ffffff), border: 1px solid Pure White (#ffffff), borderRadius: 9999px, padding: 10px 20px.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) as the base background for most pages to establish the dark theme.
- Prioritize Inter for all functional text: body, navigation, buttons, and forms, ensuring high legibility.
- Apply Ivy Presto for large headlines (above 32px) to introduce a classic, authoritative counterpoint to Inter.
- Maintain a compact density using 6px for elementGap and 16px as a multiplier for internal component spacing.
- Incorporate subtle Golden Gradient (#cc9166) on hover states or as a background for elevated, interactive elements, never as a solid background color.
- Use Pure White (#ffffff) for primary text and active states to ensure strong contrast and draw attention.
- Round corners with a 10px radius for cards and general content blocks, and 9999px for pill-shaped buttons and inputs.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas, as the system relies on subtle tonal differences.
- Do not use Ivy Presto for body text or small UI elements; reserve it for large display headings.
- Do not break the dark canvas and dark surface hierarchy by introducing light-mode components.
- Refrain from heavy shadows or strong outlines; elevate elements through subtle background shifts and internal padding.
- Do not introduce additional font families or decorative elements that disrupt the high-contrast, professional aesthetic.
- Avoid arbitrary uses of Pure White (#ffffff) for backgrounds; reserve it for primary text and calls to action.
- Do not use gradients for body text or small icons; they are reserved for decorative accents and elevated visuals.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink | `#000000` | Base page background |
| 1 | Obsidian Surface | `#030304` | Primary elevated surface, subtle lift |
| 2 | Charcoal Canvas | `#08080a` | Secondary elevated surface, general content panels |
| 3 | Pewter Accent | `#121317` | Tertiary elevated surface, interactive components |
| 4 | Slate Gray | `#1c1d22` | Further elevated component backgrounds, deeper interactive elements |

## Imagery

This system primarily uses product screenshots and abstract, ethereal graphics. Product screenshots are typically contained within dark, rounded cards, sometimes with a soft blur. Abstract graphics often feature metallic or translucent elements with soft, golden gradients and refractions, creating depth and a premium feel. Icons are monochrome, generally outlined or filled in White Frost. Imagery serves both decorative atmosphere (abstracts) and explanatory content (product UI examples). The density is balanced, with imagery often integrated into information blocks rather than dominating the page.

## Layout

The page adheres to a max-width of 1216px, primarily featuring a centered content model. The hero section often presents a centered headline (Ivy Presto) over a dark, full-bleed background, with a prominent product screenshot or abstract graphic. Sections are demarcated by consistent vertical spacing of 160px, maintaining a spacious rhythm. Content often alternates between text-dominant blocks and graphical elements, including 2-column layouts for text-plus-visuals, and 3-column card grids for features. Navigation is a sticky top bar with a left-aligned logo and right-aligned actions.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e2e3e9
accent: #cc9166
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ffffff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Feature Card: Slate Gray (#1c1d22) background, borderRadius 10px. Title 'Marketing Agencies' in Inter weight 600, 24px, lineHeight 1.25, letterSpacing -0.025, Pure White (#ffffff). Body text ‘Transaction History’ in Inter weight 400, 16px, lineHeight 1.38, letterSpacing -0.02, White Frost (#e2e3e9). Add an icon rendered in Silver Text (#acafb9).
3. Build a Pill Input Field: Background transparent, border 1px solid Pure White (#ffffff), borderRadius 9999px, padding 10px 20px. Placeholder text 'What's your email?' in Ash Text (#5e616e) Inter weight 400, 16px. User input text in Pure White (#ffffff) Inter weight 400, 16px.

## Similar Brands

- **Ramp** — Uses a dark mode UI with a focus on financial data and streamlined interfaces for corporate finance.
- **Mercury** — Employs a sophisticated dark theme, detailed financial dashboards, and clear, functional typography pairings.
- **Brex** — Features a strong dark UI with subtle gradients and a premium feel, common in corporate fintech platforms.
- **Stripe** — Known for meticulous UI design and a focus on clarity through clean typography and a muted color palette, applying a similar level of refinement to dark mode.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-obsidian-surface: #030304;
  --color-charcoal-canvas: #08080a;
  --color-pewter-accent: #121317;
  --color-slate-gray: #1c1d22;
  --color-ash-text: #5e616e;
  --color-stone-text: #777a88;
  --color-silver-text: #acafb9;
  --color-porcelain-text: #cdcdcd;
  --color-white-frost: #e2e3e9;
  --color-pure-white: #ffffff;
  --color-golden-gradient: #cc9166;
  --gradient-golden-gradient: linear-gradient(103deg, rgb(174, 147, 87), rgb(255, 240, 204) 40%, rgb(174, 147, 87) 70%, rgba(189, 157, 79, 0));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivy-presto: 'Ivy Presto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.013px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.022px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.04px;
  --text-display: 88px;
  --leading-display: 1;
  --tracking-display: 0.01px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-105: 105px;
  --spacing-224: 224px;

  /* Layout */
  --page-max-width: 1216px;
  --section-gap: 160px;
  --card-padding: 32px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 10px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-md: 10px;
  --radius-sm: 2px;
  --radius-none: 0px;
  --radius-pill: 9999px;

  /* Surfaces */
  --surface-midnight-ink: #000000;
  --surface-obsidian-surface: #030304;
  --surface-charcoal-canvas: #08080a;
  --surface-pewter-accent: #121317;
  --surface-slate-gray: #1c1d22;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-obsidian-surface: #030304;
  --color-charcoal-canvas: #08080a;
  --color-pewter-accent: #121317;
  --color-slate-gray: #1c1d22;
  --color-ash-text: #5e616e;
  --color-stone-text: #777a88;
  --color-silver-text: #acafb9;
  --color-porcelain-text: #cdcdcd;
  --color-white-frost: #e2e3e9;
  --color-pure-white: #ffffff;
  --color-golden-gradient: #cc9166;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivy-presto: 'Ivy Presto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.013px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.022px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.04px;
  --text-display: 88px;
  --leading-display: 1;
  --tracking-display: 0.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-105: 105px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 10px;
  --radius-full: 9999px;
}
```
