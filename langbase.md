# Langbase — Style Reference
> Midnight Terminal, Pulsing Data

**Theme:** dark

Langbase employs a 'dark screen, vibrant code' aesthetic, featuring a predominantly dark canvas illuminated by sharp white text and subtle, precise borders. Gradients appear as dynamic, granular data visualizations rather than soft background fills, implying digital activity. Typography is assertive yet clean, with high contrast serving functional clarity against the deep background. Components are minimalist, relying on subtle borders and high-contrast text for visual definition, reinforcing a technical and focused user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Screen | `#000000` | `--color-midnight-screen` | Page backgrounds, card surfaces, UI elements, button backgrounds for ghost buttons |
| Ghost Ink | `#232324` | `--color-ghost-ink` | Primary UI borders, subtle surface accents, structural dividers |
| Canvas White | `#fafafa` | `--color-canvas-white` | Primary text color for headlines and body, filled button backgrounds, high-contrast UI elements |
| Ash Gray | `#a1a1aa` | `--color-ash-gray` | Secondary text for body copy, muted icons, disabled states |
| Slate Text | `#454546` | `--color-slate-text` | Muted text elements, helper text, subtle interface details |
| Smoke Border | `#5c5c61` | `--color-smoke-border` | Fine element borders, subtle iconography strokes |
| Subtle Cream | `#ebeced` | `--color-subtle-cream` | Lightest UI text for rare highlights or specific text states |
| Deep Plum Gradient | `linear-gradient(rgb(246, 209, 172) 0%, rgb(243, 181, 210) 25%, rgb(243, 181, 210) 30%, rgb(199, 184, 245) 50%, rgb(199, 184, 245) 55%, rgb(167, 234, 220) 75%, rgb(167, 234, 220) 85%, rgb(175, 205, 246) 100%)` | `--color-deep-plum-gradient` | Decorative code block gradients, visualization elements, representing data flow and transformation; Dynamic accents in gradients, representing data processing. Used as base for various process gradients |
| Code Block Highlight | `linear-gradient(to right, rgb(161, 161, 161), rgb(255, 255, 255), rgb(161, 161, 161))` | `--color-code-block-highlight` | Subtle highlight gradient for code block backgrounds or simulated active lines |

## Tokens — Typography

### GeistSans — Primary typeface for all UI elements, headings, body text, and links. Its slightly condensed and precise form maintains consistency across varied content, with a subtle letter-spacing adjustment to enhance impact in larger sizes and readability in smaller. · `--font-geistsans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 48px
- **Line height:** 1.00, 1.17, 1.33, 1.40, 1.43, 1.50, 1.56, 1.71, 1.75
- **Letter spacing:** -0.025
- **Role:** Primary typeface for all UI elements, headings, body text, and links. Its slightly condensed and precise form maintains consistency across varied content, with a subtle letter-spacing adjustment to enhance impact in larger sizes and readability in smaller.

### GeistMono — Mono-spaced typeface used for representing code, data, and technical specifications. The aggressive negative letter-spacing ensures a compact, engineered feel, distinguishing technical content from standard UI text. · `--font-geistmono`
- **Substitute:** JetBrains Mono
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 16px, 60px, 72px
- **Line height:** 1.00, 1.30, 1.33, 1.50, 1.52
- **Letter spacing:** -0.3
- **Role:** Mono-spaced typeface used for representing code, data, and technical specifications. The aggressive negative letter-spacing ensures a compact, engineered feel, distinguishing technical content from standard UI text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.43 | — | `--text-body` |
| body-lg | 18px | 1.43 | — | `--text-body-lg` |
| heading-sm | 20px | 1.43 | — | `--text-heading-sm` |
| heading | 48px | 1.3 | — | `--text-heading` |

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
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| pills | 9999px |
| default | 4px |
| buttonsSmall | 12px |
| buttonsRounded | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle` |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Filled Primary Button
**Role:** Call to action button for primary actions.

White text (#fafafa) on a Canvas White (#fafafa) background, with a #232324 border, 100px border-radius, and 10px vertical, 20px horizontal padding.

### Ghost Button
**Role:** Secondary action or navigational link button.

White text (#fafafa) with a transparent background, a #27272a border, 100px border-radius, and 10px vertical, 20px horizontal padding.

### Subtle Tag Button
**Role:** Small, informational tags within a dark section.

Ghost Ink (#000000) background with Canvas White (#fafafa) text, 0px border-radius, and 4px padding on all sides.

### Card Button
**Role:** Prominent interactive elements for larger sections, such as feature cards or navigation options.

Charcoal transparent background (rgba(28, 28, 30, 0.8)) with Canvas White (#fafafa) text, a #27272a border, 12px border-radius, and 16px vertical, 24px horizontal padding.

### Header Navigation Link
**Role:** Primary navigation links in the header.

GeistSans font, #a1a1aa text color with a #0e0e10 background. No distinct border, padding 4px and margin 24px as a stack.

### Grid Cell
**Role:** Container for partner logos or similar structured content.

Uses a #232324 border with a #000000 background. Text is #fafafa with a 12px padding.

## Do's and Don'ts

### Do
- Use GeistSans for all text content, reserving GeistMono only for explicit code or data rendering.
- Maintain high contrast foreground/background relationships; aim for Canvas White (#fafafa) text on Midnight Screen (#000000) or Ghost Ink (#232324) surfaces.
- Utilize Ghost Ink (#232324) for all primary borders and dividers to maintain the dark, structured aesthetic.
- Apply 9999px for pill-shaped elements and 100px for main buttons, using 12px for larger interactive cards/buttons and 4px as a global default for small UI elements.
- Employ the gradient effects only for data visualizations or background textures that imply activity, not as primary CTA fills.
- Prioritize visual hierarchy through text size and weight changes with consistent letter-spacing adjustments, not through color saturation.
- Use 4px as the base unit for all spacing, ensuring subtle gaps are 4px, content spacing is 12px, and component internal padding at 24px.

### Don't
- Avoid using highly saturated colors for backgrounds or large fills; color should primarily be used for accents or functional highlights.
- Do not deviate from GeistSans or GeistMono for any textual content.
- Do not use generic box-shadows without specifying rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px or otherwise ensuring a subtle, dark-mode appropriate style.
- Do not introduce new border radii beyond 4px, 12px, 100px, and 9999px.
- Do not use more than two levels of text color density per section to prevent visual clutter; stick to Canvas White (#fafafa) and Ash Gray (#a1a1aa).
- Do not use gradients as primary solid colors in components; they are for dynamic, textural effects.
- Avoid large hero imagery; prefer abstract graphics or code-like visualizations over photographs.

## Imagery

The visual language predominantly features abstract, dynamic gradients resembling data processing or code streams, set against deep dark backgrounds. These elements are not purely decorative but give the impression of complex systems at work. Iconography is minimalist, outlined, and monochromatic, maintaining a purely functional role. There is a strong absence of photography or illustrative characters, signaling a focus on pure UI and technical functionality. Imagery serves to explain or enhance the UI through abstract visual representations rather than literal depictions, with a high density of these 'data' elements.

## Layout

The page primarily uses a full-bleed dark page model, with content centered within implicit maximum widths. The hero section features a centered headline and subtext over an extensive abstract gradient graphic. Sections maintain consistent vertical spacing, often indicated by the grid lines on the dark canvas, and transition seamlessly without explicit visual dividers. Content is arranged in alternating patterns, frequently showcasing text alongside abstract visualizations or a grid of partner logos. The navigation is a sticky top bar, minimalist and high-contrast against the dark background. The layout is spacious, allowing crucial information and dynamic graphics to breathe.

## Agent Prompt Guide

**Quick Color Reference**
text: #fafafa
background: #000000
border: #232324
accent: #f6d1ac (gradient base)
primary action: #fafafa (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #fafafa background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a partner logo grid: Midnight Screen (#000000) background. Each logo container is a Grid Cell with a #232324 border, #000000 background, 12px padding, displaying a #fafafa logo. The text 'Trusted by developers at 5000+ companies' uses GeistSans at 16px weight 400, #a1a1aa.

## Similar Brands

- **Vercel** — Dark-themed UI with strong typography, a focus on developer tools, and subtle, code-like graphic accents.
- **Railway** — Minimalist dark interface, prominent use of monospaced fonts, and abstract visual indicators for system activity.
- **Stripe** — Clean, technical aesthetic with strong visual hierarchy, although typically lighter in theme, similar attention to detail in component design.
- **PlanetScale** — Developer-focused platform with a dark theme, high-contrast text, and a polished, professional component library.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-screen: #000000;
  --color-ghost-ink: #232324;
  --color-canvas-white: #fafafa;
  --color-ash-gray: #a1a1aa;
  --color-slate-text: #454546;
  --color-smoke-border: #5c5c61;
  --color-subtle-cream: #ebeced;
  --color-deep-plum-gradient: #f6d1ac;
  --gradient-deep-plum-gradient: linear-gradient(rgb(246, 209, 172) 0%, rgb(243, 181, 210) 25%, rgb(243, 181, 210) 30%, rgb(199, 184, 245) 50%, rgb(199, 184, 245) 55%, rgb(167, 234, 220) 75%, rgb(167, 234, 220) 85%, rgb(175, 205, 246) 100%);
  --color-code-block-highlight: #a1a1a1;
  --gradient-code-block-highlight: linear-gradient(to right, rgb(161, 161, 161), rgb(255, 255, 255), rgb(161, 161, 161));

  /* Typography — Font Families */
  --font-geistsans: 'GeistSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --text-heading: 48px;
  --leading-heading: 1.3;

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
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pills: 9999px;
  --radius-default: 4px;
  --radius-buttonssmall: 12px;
  --radius-buttonsrounded: 100px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-screen: #000000;
  --color-ghost-ink: #232324;
  --color-canvas-white: #fafafa;
  --color-ash-gray: #a1a1aa;
  --color-slate-text: #454546;
  --color-smoke-border: #5c5c61;
  --color-subtle-cream: #ebeced;
  --color-deep-plum-gradient: #f6d1ac;
  --color-code-block-highlight: #a1a1a1;

  /* Typography */
  --font-geistsans: 'GeistSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --text-heading: 48px;
  --leading-heading: 1.3;

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
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
}
```
