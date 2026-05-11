# Shuttle — Style Reference
> Crisp digital canvas

**Theme:** light

Shuttle employs a crisp, utility-focused aesthetic, blending a stark monochrome palette with a single vibrant blue accent. Surfaces are predominantly white or near-white, providing a clean digital canvas for functional elements. Typography is compact and precise, maintaining a high information density without visual clutter, while subtle shadows and rounded corners soften interactive components.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page and card backgrounds, interactive elements — establishes a clean, expansive workspace |
| Cloud Gray | `#f9f9f9` | `--color-cloud-gray` | Subtle background for grouped elements, provides a gentle visual separation from Canvas White |
| Border Fog | `#e5e7eb` | `--color-border-fog` | Hairline borders for cards, inputs, and dividers — delineates content without heavy visual weight |
| Stroke Silver | `#b8b8b8` | `--color-stroke-silver` | Subtle shadows for buttons and cards, creating a sense of shallow elevation |
| Graphite Black | `#000000` | `--color-graphite-black` | Primary text, headings, and significant icon fills — ensures high contrast and clarity |
| Muted Ash | `#a3a3a3` | `--color-muted-ash` | Secondary text and inactive icon strokes — provides visual relief while remaining legible |
| Text Slate | `#525252` | `--color-text-slate` | Body text and links — a softer alternative to Graphite Black for extended reading |
| Shuttle Blue | `#0077ff` | `--color-shuttle-blue` | Primary action buttons, active navigation items, and brand accents — signals interactivity and importance |
| Warning Gold | `#f59e0b` | `--color-warning-gold` | Yellow text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Error Ember | `#ef4444` | `--color-error-ember` | Red text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### InterVariable — Primary UI font for all elements – its consistent negative letter-spacing ensures a tight, modern feel even at smaller sizes. · `--font-intervariable`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 62px
- **Line height:** 1.00, 1.16, 1.25, 1.33, 1.40, 1.43, 1.50, 1.67
- **Letter spacing:** -0.025
- **Role:** Primary UI font for all elements – its consistent negative letter-spacing ensures a tight, modern feel even at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body-sm | 11px | 1.4 | — | `--text-body-sm` |
| body | 12px | 1.4 | — | `--text-body` |
| body-lg | 14px | 1.4 | — | `--text-body-lg` |
| heading-sm | 15px | 1.4 | — | `--text-heading-sm` |
| heading | 16px | 1.4 | — | `--text-heading` |
| heading-lg | 62px | 1.3 | — | `--text-heading-lg` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 9999px |
| inputs | 8px |
| avatars | 9999px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 0px 1px 0px` | `--shadow-subtle` |
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |

### Layout

- **Section gap:** 128px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Key interactions

Filled with Shuttle Blue (#0077ff), white text, and 8px rounded corners. Padding is 0px vertical and 12px horizontal.

### Ghost Button
**Role:** Secondary actions

Transparent background, Graphite Black (#000000) text, and a Border Fog (#e5e7eb) border. No border radius, 0px vertical and 48px horizontal padding.

### Light Ghost Button
**Role:** Contextual actions within cards or other surfaces

White background, Graphite Black (#000000) text, and Border Fog (#e5e7eb) border. Features 8px rounded corners and 0px vertical, 12px right, 6px left padding.

### Elevated Content Card
**Role:** Prominent content blocks

Canvas White (#ffffff) background with 16px border-radius. Features a prominent shadow: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px.

### Subtle Background Card
**Role:** Informational panels

Cloud Gray (#fafafa) background with 24px border-radius. A subtle shadow: rgba(0, 0, 0, 0.25) 0px 0px 1px 0px.

### Simple Input Field
**Role:** User data entry

Transparent background, Graphite Black (#000000) text, and a Border Fog (#e5e7eb) bottom border. Has 6px border-radius and 12px vertical padding.

### Badge/Tag
**Role:** Categorization and status

Utilizes 9999px border-radius for an elliptical shape. Background and text color vary by context but often feature neutral tones or the brand's accent colors.

## Do's and Don'ts

### Do
- Use InterVariable font with the default negative letter-spacing of -0.025em for all text elements to maintain a compact, tight aesthetic.
- Prioritize Canvas White (#ffffff) for primary content backgrounds and Cloud Gray (#f9f9f9) for secondary grouped elements to create subtle depth.
- Apply Shuttle Blue (#0077ff) exclusively for primary calls to action and active states to guide user interaction.
- Borders should primarily use Border Fog (#e5e7eb) at 1px solid, maintaining a light, clean separation of elements.
- Implement 8px border-radius for interactive elements like buttons and inputs, and 16px for content cards to unify component shaping.
- Separate major page sections with a vertical gap of 128px to ensure ample breathing room and clear content distinctions.
- Elevate primary content cards using the prominent shadow rgba(0, 0, 0, 0.25) 0px 25px 50px -12px to give them visual priority.

### Don't
- Avoid using highly saturated colors outside of the defined brand and semantic palette; maintain a predominantly neutral visual space.
- Do not vary letter-spacing for different text sizes or roles, as InterVariable's consistent -0.025em is a signature styling choice.
- Refrain from introducing heavy or opaque background colors for cards or containers; favor transparent or very light backgrounds.
- Do not use box-shadows beyond the specified subtle options; the design minimizes aggressive 3D effects.
- Avoid mixed border radii on the same component (e.g., 8px for one corner, 16px for another); ensure consistent rounding.
- Do not introduce gradients unless they are purely decorative and do not interfere with legibility or functional contrast.
- Do not use excessive visual decoration or embellishment; the system prioritizes clarity and functional simplicity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background |
| 1 | Cloud Gray | `#f9f9f9` | Grouped element backgrounds |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`
- **Subtle Background Card:** `rgba(0, 0, 0, 0.25) 0px 0px 1px 0px`
- **Button:** `rgba(0, 0, 0, 0.25) 0px 0px 1px 0px`

## Imagery

The site's imagery is minimal, focusing on UI elements and functional icons rather than photography or complex illustrations. Icons are primarily outlined or filled with Graphite Black (#000000) or subtle gray tones, occasionally highlighted with a vibrant accent color like Warning Gold (#f59e0b). Visual treatment is clean, contained, and without ornate stylization, emphasizing product utility and clarity. The density is text-dominant, with icons serving as functional aids rather than large decorative elements.

## Layout

The page maintains a full-bleed layout for its overall canvas (Canvas White), but content within sections appears to be centered with a distinct max-width, though not explicitly defined in the data. The header features a compact, centrally aligned navigation with the brand logo, links, and a primary action button. Sections exhibit a consistent vertical rhythm, often using a section gap of 128px. Content arrangement varies, but often involves focused, centered blocks within the main flow. There's an indication of some content alternating with text and implied visuals. The navigation is a sticky top bar, providing persistent access to key actions.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e5e7eb
accent: #0077ff
primary action: #0077ff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #0077ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create an Elevated Content Card: Canvas White (#ffffff) background, 16px border-radius, with shadow rgba(0, 0, 0, 0.25) 0px 25px 50px -12px. Use Graphite Black (#000000) for headlines and Text Slate (#525252) for body copy (both InterVariable, -0.025em letter-spacing).
3. Design a Simple Input Field: Transparent background, Border Fog (#e5e7eb) bottom border, 8px border-radius, 12px vertical padding. Use Graphite Black (#000000) for input text (InterVariable, weight 400, -0.025em letter-spacing).

## Similar Brands

- **Figma** — Clean white interfaces contrasted with functional but minimal use of accent colors, and a focus on sharp, readable typography.
- **Linear** — Emphasis on functional, compact information density, minimal UI ornamentation, and subtle shifts in neutral backgrounds to convey hierarchy.
- **Replit** — A utility-focused aesthetic with a clean white canvas, crisp typography, and strategic splashes of a single vibrant accent color to highlight interactions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f9f9f9;
  --color-border-fog: #e5e7eb;
  --color-stroke-silver: #b8b8b8;
  --color-graphite-black: #000000;
  --color-muted-ash: #a3a3a3;
  --color-text-slate: #525252;
  --color-shuttle-blue: #0077ff;
  --color-warning-gold: #f59e0b;
  --color-error-ember: #ef4444;

  /* Typography — Font Families */
  --font-intervariable: 'InterVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 11px;
  --leading-body-sm: 1.4;
  --text-body: 12px;
  --leading-body: 1.4;
  --text-body-lg: 14px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 15px;
  --leading-heading-sm: 1.4;
  --text-heading: 16px;
  --leading-heading: 1.4;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.3;

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
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 128px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 9999px;
  --radius-inputs: 8px;
  --radius-avatars: 9999px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 0px 1px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #f9f9f9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f9f9f9;
  --color-border-fog: #e5e7eb;
  --color-stroke-silver: #b8b8b8;
  --color-graphite-black: #000000;
  --color-muted-ash: #a3a3a3;
  --color-text-slate: #525252;
  --color-shuttle-blue: #0077ff;
  --color-warning-gold: #f59e0b;
  --color-error-ember: #ef4444;

  /* Typography */
  --font-intervariable: 'InterVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 11px;
  --leading-body-sm: 1.4;
  --text-body: 12px;
  --leading-body: 1.4;
  --text-body-lg: 14px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 15px;
  --leading-heading-sm: 1.4;
  --text-heading: 16px;
  --leading-heading: 1.4;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 0px 1px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
}
```
