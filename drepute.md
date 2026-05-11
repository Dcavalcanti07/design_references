# Drepute — Style Reference
> Midnight Lake Serenity: a tranquil, dark expanse punctuated by crisp, minimal text and subtle, interactive glints of light.

**Theme:** dark

Drepute employs a dark, contemplative aesthetic, grounding itself in the deep blues and blacks of a stark night sky or a still lake. Typography is central, using elegant serifs for prominent messages and clear sans-serifs for utility. The interface is highly minimal, with muted controls and a focus on content, relying on white text on dark backgrounds and thin borders for structure. Interactivity is suggested by subtle outlines and a scarcity of vibrant color, making any color highlight feel purposeful and significant.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Lake | `#161616` | `--color-midnight-lake` | Page backgrounds, hero section background, primary card surfaces — the dominant deep, dark canvas |
| Night Sky | `#000000` | `--color-night-sky` | Primary text on light backgrounds, dark button borders, subtle decorative strokes |
| Snow Drift | `#ffffff` | `--color-snow-drift` | Primary text on dark backgrounds, interactive element backgrounds, input borders, ghost icon fills |
| Ash Gray | `#bfbfbf` | `--color-ash-gray` | Muted text, placeholder text in inputs, subtle element borders |
| Slate Dew | `#a9a9a9` | `--color-slate-dew` | Secondary body text, supporting information text, less prominent borders |
| Pebble Stone | `#7f8080` | `--color-pebble-stone` | Tertiary text, navigation links, and subtle outlined button borders |
| Teal Accent | `#00a4a6` | `--color-teal-accent` | Highlighting interactive links, subtle ghost button borders — a singular, cool accent color that draws attention without shouting |
| Mountain Mist | `#8995a9` | `--color-mountain-mist` | Border for interaction components, indicating a soft, interactive boundary |

## Tokens — Typography

### Source Sans Pro — Primary text for body content, buttons, inputs, and navigation — provides a clear, modern counterpoint to the more decorative display font. · `--font-source-sans-pro`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 14px, 16px
- **Line height:** 1.20, 1.50
- **Letter spacing:** -1.14px at 16px, -1.0px at 14px
- **Role:** Primary text for body content, buttons, inputs, and navigation — provides a clear, modern counterpoint to the more decorative display font.

### Playfair Display — Expressive serif for primary headings and prominent display text — its elegant, classic character lends gravity and distinctiveness to key messages. · `--font-playfair-display`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px, 44px, 62px
- **Line height:** 1.20, 1.25
- **Letter spacing:** normal
- **Role:** Expressive serif for primary headings and prominent display text — its elegant, classic character lends gravity and distinctiveness to key messages.

### Montserrat — Used for distinctive, high-impact headings — its bold weight and tight tracking create a strong focal point. · `--font-montserrat`
- **Substitute:** Arial
- **Weights:** 700
- **Sizes:** 26px
- **Line height:** 1.20
- **Letter spacing:** -3.85px at 26px
- **Role:** Used for distinctive, high-impact headings — its bold weight and tight tracking create a strong focal point.

### GD Sherpa — GD Sherpa — detected in extracted data but not described by AI · `--font-gd-sherpa`
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.2
- **Role:** GD Sherpa — detected in extracted data but not described by AI

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** Times — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.2 | -1px | `--text-body-sm` |
| body | 16px | 1.2 | -1.14px | `--text-body` |
| subheading | 26px | 1.2 | -3.85px | `--text-subheading` |
| heading | 44px | 1.25 | — | `--text-heading` |
| display | 62px | 1.25 | — | `--text-display` |

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
| 56 | 56px | `--spacing-56` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 4px |
| buttons | 4px |

### Layout

- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Light Outlined Button
**Role:** Secondary action button on dark backgrounds.

Text: #000000. Background: #ffffff. Border: 1px solid #8995a9 (Mountain Mist). Padding: 8px vertical, 24px horizontal. Radius: 4px. Font: Source Sans Pro, 16px weight 400, line height 1.2.

### Solid Text Button (default)
**Role:** Primary action button, used primarily against lighter areas or when a strong contrast is needed.

Text: #000000. Background: #ffffff. Border: 1px solid #000000 (Night Sky). Padding: 8px vertical, 32px horizontal. Radius: 4px. Font: Source Sans Pro, 16px weight 400, line height 1.2.

### Text Input
**Role:** Standard input field for user data.

Text: #bfbfbf (Ash Gray). Background: rgba(22, 22, 22, 0) (transparent). Border: 1px solid #ffffff (Snow Drift). Padding: 23px top, 7px bottom, 16px horizontal. Radius: 4px. Font: Source Sans Pro, 16px weight 400, line height 1.2.

### Brand Logo
**Role:** Primary brand identifier in navigation.

Text: #ffffff (Snow Drift). Font: Playfair Display, 16px weight 400, line height 1.2.

### Hero Headline
**Role:** Large, prominent text for hero sections.

Text: #ffffff (Snow Drift). Font: Playfair Display, 62px weight 400, line height 1.25.

## Do's and Don'ts

### Do
- Ground all primary layouts in 'Midnight Lake' (#161616) as the dominant background color to maintain the deep, dark aesthetic.
- Use 'Snow Drift' (#ffffff) for all main headings and body text on dark backgrounds to ensure strong contrast and legibility.
- Apply 'Playfair Display' for all primary display text and headings, leveraging its elegant serif character.
- Structure interactive elements with minimal, crisp borders, such as 1px solid 'Mountain Mist' (#8995a9) for secondary actions or 'Teal Accent' (#00a4a6) for active links.
- Maintain a tight layout with 'elementGap' of 24px and component radii consistently at 4px.
- Introduce 'Teal Accent' (#00a4a6) sparingly, strictly for links and interactive outlines where a subtle highlight is desired, avoiding its use as a filled button background.
- Employ Source Sans Pro for all functional text, like buttons, inputs, and body copy, to provide a modern, legible contrast to the decorative serifs.

### Don't
- Avoid using bright or overly saturated colors as primary backgrounds; the system relies on deep, subdued tones.
- Do not introduce heavy shadows or gradients; rely on clean, flat surfaces and crisp borders for visual definition.
- Refrain from using multiple distinct accent colors; 'Teal Accent' (#00a4a6) should largely be the sole chromatic highlight.
- Do not fill primary action buttons with 'Teal Accent' (#00a4a6); reserve it for outlines or text accents.
- Avoid excessive imagery or complex visual elements in content areas; prioritize clean typography and functional UI.
- Do not deviate from the established small border radius of 4px; rounded edges should be consistent and subtle.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Lake Canvas | `#161616` | The foundational dark background for the entire page and large hero sections, providing a deep, contemplative base. |
| 1 | Elevated Component Surface | `#000000` | Used for elements that subtly rise from the main canvas, like footers, input containers, or distinct content blocks. |
| 2 | Interactive Overlay | `#ffffff` | Applied to interactive backgrounds such as buttons or alerts that need to pop against dark surfaces, serving as a bright, crisp layer. |

## Imagery

The site primarily features a single, full-bleed night landscape photograph as a hero background, depicting mountains reflected in a still lake under a starry sky. This imagery serves as a decorative, atmospheric backdrop rather than conveying specific content. There is no other prominent use of photography, illustration, or complex graphics. Icons are minimal, likely monochromatic or ghost-style (such as the chat icon), serving strictly functional roles.

## Layout

The page employs a full-bleed layout for its hero section, featuring a centered headline over the background image. Subsequent sections, like the 'Subscribe' area, appear to use a max-width contained layout, vertically centered with clear, consistent spacing. The overall rhythm is one of spaciousness with minimal, focused content blocks stacked vertically, relying on generous vertical padding and strong typographic contrasts to define sections. A thin banner at the top acts as a secondary, lighter navigation or alert area. The navigation itself is a simple top bar, also full-width, displaying the brand name and possibly a few links.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #161616
border: #000000
accent: #00a4a6
primary action: #00a4a6 (outlined action border)

Example Component Prompts:
Create a hero section: 'Midnight Lake' (#161616) background. Centered headline 'Launching Soon' at 62px Playfair Display weight 400, 'Snow Drift' (#ffffff). Above that, the logo 'Drepute' at 16px Playfair Display weight 400, 'Snow Drift' (#ffffff).
Create a 'Learn More' button: 'Snow Drift' (#ffffff) background, 'Night Sky' (#000000) text (Source Sans Pro 16px weight 400), 1px solid 'Midnight Lake' (#000000) border, 4px radius, 8px vertical padding, 32px horizontal padding.
Create a subscribe section: 'Midnight Lake' (#161616) background. Centered heading 'Subscribe' at 44px Playfair Display weight 400, 'Snow Drift' (#ffffff). An input box with transparent background, 'Ash Gray' (#bfbfbf) placeholder text (Source Sans Pro 16px weight 400), 1px solid 'Snow Drift' (#ffffff) border, 4px radius, 23px top / 7px bottom / 16px horizontal padding.
Create a navigation bar: 'Midnight Lake' (#161616) background. 'Drepute' logo as 16px Playfair Display weight 400 in 'Snow Drift' (#ffffff). Navigation link 'Learn More' in 'Pebble Stone' (#7f8080) at 14px Source Sans Pro weight 400.

## Similar Brands

- **Calm (App)** — Similar use of dark, tranquil landscape imagery as background for a minimal interface, focused on a serene atmosphere.
- **Linear** — Shared aesthetic of a dark theme with crisp white text and a focus on clean, functional typography with minimal color accents for interaction.
- **Superhuman** — Employs a stark dark mode, prioritizing typography and speed, with subtle interactive elements rather than heavy visual adornment.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-lake: #161616;
  --color-night-sky: #000000;
  --color-snow-drift: #ffffff;
  --color-ash-gray: #bfbfbf;
  --color-slate-dew: #a9a9a9;
  --color-pebble-stone: #7f8080;
  --color-teal-accent: #00a4a6;
  --color-mountain-mist: #8995a9;

  /* Typography — Font Families */
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gd-sherpa: 'GD Sherpa', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -1px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -1.14px;
  --text-subheading: 26px;
  --leading-subheading: 1.2;
  --tracking-subheading: -3.85px;
  --text-heading: 44px;
  --leading-heading: 1.25;
  --text-display: 62px;
  --leading-display: 1.25;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-56: 56px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-inputs: 4px;
  --radius-buttons: 4px;

  /* Surfaces */
  --surface-midnight-lake-canvas: #161616;
  --surface-elevated-component-surface: #000000;
  --surface-interactive-overlay: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-lake: #161616;
  --color-night-sky: #000000;
  --color-snow-drift: #ffffff;
  --color-ash-gray: #bfbfbf;
  --color-slate-dew: #a9a9a9;
  --color-pebble-stone: #7f8080;
  --color-teal-accent: #00a4a6;
  --color-mountain-mist: #8995a9;

  /* Typography */
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gd-sherpa: 'GD Sherpa', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -1px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -1.14px;
  --text-subheading: 26px;
  --leading-subheading: 1.2;
  --tracking-subheading: -3.85px;
  --text-heading: 44px;
  --leading-heading: 1.25;
  --text-display: 62px;
  --leading-display: 1.25;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-56: 56px;

  /* Border Radius */
  --radius-md: 4px;
}
```
