# Atoms — Style Reference
> Black steel, golden inscription

**Theme:** dark

Atoms employs a minimal, industrial dark-mode aesthetic. Its visual system centers around stark black backgrounds punctuated by a single, muted golden accent color for key text elements and interactive states. Typography is compact and precise, often letter-spaced for subtle emphasis, contributing to a sense of controlled power. Components are lightweight, favoring subtle borders over heavy fills or shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page backgrounds, card surfaces, borders, icon fills |
| Alabaster | `#fff7dd` | `--color-alabaster` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Weathered Gold | `#c8ad86` | `--color-weathered-gold` | Branding elements, prominent headings, and functional decorative accents. This provides a warm, aged contrast to the dark theme, signifying value and stability |
| Faded Ash | `#66635f` | `--color-faded-ash` | Subtle background shifts for contained elements like navigation items, providing minimal visual separation |

## Tokens — Typography

### Switzer — Primary brand typeface for headings and body text. The tight letter spacing for larger sizes ('P h y s i c a l a u t o') conveys a sense of mechanical precision and structure. · `--font-switzer`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 14px, 16px, 44px
- **Line height:** 1.00, 1.13
- **Letter spacing:** -1.848px at 44px, -0.496px at 16px, -0.224px at 14px, -0.12px at 12px, 0.18px at 10px
- **Role:** Primary brand typeface for headings and body text. The tight letter spacing for larger sizes ('P h y s i c a l a u t o') conveys a sense of mechanical precision and structure.

### sans-serif — System fallback for small utility text like navigation, links, and footer elements, maintaining readability at minimal sizes and ensuring robustness. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback for small utility text like navigation, links, and footer elements, maintaining readability at minimal sizes and ensuring robustness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | 0.18px | `--text-caption` |
| body | 14px | 1.13 | -0.224px | `--text-body` |
| display | 44px | 1 | -1.848px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| default | 4px |

### Layout

- **Section gap:** 60px
- **Card padding:** 20px
- **Element gap:** 4px

## Components

### Navigation Link
**Role:** Interactive text link for site navigation.

Text uses Switzer 400 at 12px, Alabaster. Underlined with a 1px Weathered Gold border on hover. Padding of 4px vertically and 6px horizontally.

### Simple Card
**Role:** Container for content like company logos or descriptions.

Absolute Zero background with a 1px border of Weathered Gold. Default border radius of 4px. Internal padding of 20px.

### Metadata Tag
**Role:** Small, descriptive label within cards.

Alabaster text (sans-serif 400, 12px) on an Absolute Zero background with 1px Alabaster border, 4px border-radius, and 4px padding.

### Text Accent Link
**Role:** Inline text link with an arrow indicator.

Weathered Gold text (Switzer 400, 12px) with an accompanying arrow icon. No background or distinct border, relying on color for interaction indication.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#000000) for all backgrounds and primary surfaces.
- Use Alabaster (#fff7dd) for primary text and subtle interface elements.
- Reserve Weathered Gold (#c8ad86) strictly for brand elements, key headings, and interactive highlights to maintain its distinct impact.
- Apply Switzer as the primary typeface for all headings and body text, adhering to the specified letter-spacing for each size.
- Implement a default border-radius of 4px for all container elements and 100px for pill-shaped elements.
- Maintain high contrast (minimum AA) between text and background colors.
- Use 4px as a base for internal element spacing to ensure a compact, dense layout.

### Don't
- Avoid using bright or saturated colors outside of the defined Weathered Gold accent.
- Do not introduce heavy shadows or gradients; the design relies on flat surfaces and subtle borders.
- Do not deviate from the specified letter-spacing for Switzer to preserve the industrial precision.
- Do not use generic system fonts for prominent headings or branding text.
- Avoid large, airy section gaps; maintain a compact layout with 60px as the maximum section separation.
- Do not use Alabaster for backgrounds; it is reserved for text and hairline borders against black surfaces.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#000000` | Dominant page background. |
| 1 | Card Surface | `#000000` | Contained elements like company cards, distinguished by a subtle border. |
| 2 | Interactive Overlay | `#66635f` | Background for interactive elements like navigation menu items on hover or focus. |

## Imagery

The site predominantly uses abstract, geometric imagery and brand logos, all monochromatic or in the brand's muted gold color. Product visuals are absent. Imagery is primarily contained within cards or as central focal points (like the large '+' symbol on the hero), often rendered with a textured or frosted appearance rather than solid fills. Icons are simple, outlined or filled, and primarily black or white against the contrasting background.

## Layout

The page uses a full-bleed dark background with content subtly constrained to a central column (approx. 1000-1200px equivalent, as pageMaxWidth is null but content feels contained). The hero section features a large, centered brand graphic and headline over the dark background. Subsequent sections often employ a grid-based layout for 'companies' or similar feature blocks, with items like 3-column cards. Vertical rhythm is established through consistent section gaps, creating a dense but organized feel. Navigation is a minimalist top bar with text links. The overall density is compact, focusing on essential information within strict boundaries.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #fff7dd
- background: #000000
- border: #000000
- accent: #c8ad86
- primary action: no distinct CTA color

**Example Component Prompts:**
1. Create a Hero Section with the text 'Physical automation to transform industry and move the world.' The background should be Absolute Zero. The heading 'Physical automation to transform industry and move the world.' should use Switzer 400 at 44px, Alabaster text color, and a letter-spacing of -1.848px. Below it, include a 'Read vision' link with Weathered Gold text (Switzer 400, 12px) and an arrow icon.
2. Create a 'Company Card' component for a grid layout. The background is Absolute Zero with a 1px Weathered Gold border, and 4px border-radius. Inside, center a company logo in Alabaster, and a text description below it using Alabaster (Switzer 400, 14px, letter-spacing -0.224px). Include a 'Mining' Metadata Tag, which is Alabaster text (sans-serif 400, 12px) on an Absolute Zero background, 1px Alabaster border, 4px radius, 4px padding.
3. Design a simple 'Footer Link' component. The text is 'Careers' using sans-serif 400 at 12px, Alabaster. It should have 4px vertical and 6px horizontal padding. On hover, the text turns Weathered Gold and gains a 1px Weathered Gold bottom border.

## Similar Brands

- **Anthropic** — Dark UI, minimalist typography, and a single accent color for emphasis.
- **Foundation** — Strict typographic hierarchy, dark aesthetic with tight element spacing, and subtle border usage.
- **Unit21** — Monochromatic interface with high contrast text and a restrained use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-alabaster: #fff7dd;
  --color-weathered-gold: #c8ad86;
  --color-faded-ash: #66635f;

  /* Typography — Font Families */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: 0.18px;
  --text-body: 14px;
  --leading-body: 1.13;
  --tracking-body: -0.224px;
  --text-display: 44px;
  --leading-display: 1;
  --tracking-display: -1.848px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 20px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-default: 4px;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-card-surface: #000000;
  --surface-interactive-overlay: #66635f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-alabaster: #fff7dd;
  --color-weathered-gold: #c8ad86;
  --color-faded-ash: #66635f;

  /* Typography */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: 0.18px;
  --text-body: 14px;
  --leading-body: 1.13;
  --tracking-body: -0.224px;
  --text-display: 44px;
  --leading-display: 1;
  --tracking-display: -1.848px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;
}
```
