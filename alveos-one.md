# Alveos One — Style Reference
> Warm gray calm.

**Theme:** light

Alveos One projects a calm, understated elegance through a light, desaturated palette and subtle transitions. It uses a soft, warm gray canvas for its heroic sections, contrasting with crisp white surfaces for content, creating a gentle visual depth. Typography balances a friendly sans-serif for body text with distinct, tracked characters for branding accents. Components are minimally styled, often relying on generous rounded corners and ghost button interactions to maintain an airy feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Warmth | `radial-gradient(50% 95% at 50% 108.6%, rgb(252, 249, 247) 0%, rgb(168, 156, 138) 100%)` | `--color-canvas-warmth` | Page backgrounds, large content sections, hero background base — provides a soft, inviting canvas; Hero background gradient start point |
| Surface White | `#ffffff` | `--color-surface-white` | Card backgrounds, elevated content areas, crisp text contrast |
| Deep Graphite | `#05060b` | `--color-deep-graphite` | Primary action button background, footer background — a rich, near-black for key interactive elements |
| Text Black | `#000000` | `--color-text-black` | Primary text, strong headings, borders, and some icons |
| Headline Dark | `#262628` | `--color-headline-dark` | Prominent headings and section titles |
| Body Gray | `#575757` | `--color-body-gray` | General body text, secondary information |
| Muted Text | `#a5a5a5` | `--color-muted-text` | Copyright text, helper messages, and subtle labels |
| Line Gray | `#d1cfcd` | `--color-line-gray` | Subtle borders, dividers, and background elements, often with soft shadows |
| Ghost Fill | `#030f1c` | `--color-ghost-fill` | Ghost button background for secondary actions, subtle branding element in navigation |

## Tokens — Typography

### sans-serif — Navigation, buttons, and small labels — the broad letter spacing creates an airy, distinct presentation, especially for uppercase text. · `--font-sans-serif`
- **Substitute:** system
- **Weights:** 400, 600
- **Sizes:** 10px, 12px, 18px
- **Line height:** 1.20, 1.30
- **Letter spacing:** 0.444em
- **Role:** Navigation, buttons, and small labels — the broad letter spacing creates an airy, distinct presentation, especially for uppercase text.

### Hanken Grotesk — Headings, titles, and select prominent text — its subtle character features provide a unique, modern feel. · `--font-hanken-grotesk`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 16px, 18px, 20px, 24px, 28px, 36px, 38px, 52px
- **Line height:** 1.10, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** normal
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Headings, titles, and select prominent text — its subtle character features provide a unique, modern feel.

### Inter — Generic body text and descriptive content where high legibility is paramount without overt styling. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Generic body text and descriptive content where high legibility is paramount without overt styling.

### -apple-system — -apple-system — detected in extracted data but not described by AI · `--font-apple-system`
- **Weights:** 400, 500, 600
- **Sizes:** 11px, 12px
- **Line height:** 1.2, 1.48
- **Role:** -apple-system — detected in extracted data but not described by AI

### SF Mono — SF Mono — detected in extracted data but not described by AI · `--font-sf-mono`
- **Weights:** 600
- **Sizes:** 9px
- **Line height:** 1
- **Letter spacing:** 0.02
- **Role:** SF Mono — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | 4.44px | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.5 | — | `--text-heading` |
| heading-lg | 36px | 1.1 | — | `--text-heading-lg` |
| display | 52px | 1.1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 50 | 50px | `--spacing-50` |
| 80 | 80px | `--spacing-80` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 25px |
| images | 20px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.06) 0px 1px 5px 0px` | `--shadow-sm` |
| xl | `rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05)...` | `--shadow-xl` |
| md | `rgba(0, 0, 0, 0.05) 0px 2px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 50px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Filled Primary Button
**Role:** Calls to action, key navigation elements.

Background: Deep Graphite (#05060b). Text: Canvas Warmth (#fcf9f7). Radius: 12px. Padding: 14px vertical, 30px horizontal. Uses a system sans-serif font.

### Ghost Navigation Button
**Role:** Secondary navigation, subtle actions within sections.

Background: Ghost Fill (#030f1c) with 0% opacity. Text: Canvas Warmth (#fcf9f7). Radius: 12px. Padding: 7px vertical, 20px horizontal. Uses a system sans-serif font with broad letter spacing.

### Content Card with Shadow
**Role:** Showcasing features, product benefits, or testimonials.

Background: Surface White (#ffffff). Radius: 16px. Padding: 0px. Shadow: rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px.

### Simple Content Card
**Role:** Grouped information blocks, image containers.

Background: Surface White (#ffffff). Radius: 25px. Padding: 20px vertical, 25px horizontal. No shadow.

### Minimal Card
**Role:** Content background for media or embedded elements.

Background: Surface White (#ffffff). Radius: 20px. Padding: 0px. No shadow.

### Subtle Background Card
**Role:** Highlighting related content or categories subtly.

Background: rgba(0, 0, 0, 0.04). Radius: 10px. Padding: 0px. No shadow.

## Do's and Don'ts

### Do
- Use Hanken Grotesk for all headings and prominent titles, leveraging its unique font features like 'blwf', 'cv03', 'cv04', 'cv09', 'cv11'.
- Apply Canvas Warmth (#fcf9f7) as the primary background for full-bleed sections and hero areas to establish a soft, inviting tone.
- Utilize rounded corners generously: 25px for general card elements, 20px for image containers, and 12px for interactive buttons.
- Render primary action buttons with Deep Graphite (#05060b) background and Canvas Warmth (#fcf9f7) text, rounded to 12px.
- Reserve the system sans-serif font with 0.444em letter-spacing for all navigation links and button labels to maintain a branded, airy appearance.
- Employ a subtle shadow like rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px for elevated content cards, rather than solid borders.
- Maintain comfortable visual breathing room with 10px element spacing and 20px card padding.

### Don't
- Avoid using highly saturated, vivid colors; the palette prioritizes muted, earthy tones and achromatic values.
- Do not use sharp 0px border-radii for interactive elements or content containers; all interactive and content-holding components require rounded corners.
- Refrain from heavy, pronounced shadows; elevation should be subtle and soft, indicated by a faint blur and minimal offset.
- Do not introduce new font families; adhere strictly to Hanken Grotesk for display, Inter for body, and system sans-serif for accents.
- Avoid solid, contrasting borders on cards and buttons unless it's a ghost button interaction; rely on background and shadow for definition.
- Do not use dark backgrounds for full content sections; maintain a predominantly light theme with Canvas Warmth (#fcf9f7) and Surface White (#ffffff).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Warmth | `#fcf9f7` | Base page background or large section background, providing a soft, warm foundation. |
| 1 | Surface White | `#ffffff` | Primary surface for content cards, panels, and areas requiring crisp contrast. |
| 2 | Subtle Background Card | `#0a0a0a` | Very slightly elevated or background shaded areas (rgba(0, 0, 0, 0.04) resolves to this near-black with transparency). |

## Elevation

- **Content Card:** `rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px`
- **Body Content:** `rgba(0, 0, 0, 0.06) 0px 1px 5px 0px`

## Imagery

The visual language for imagery is characterized by tightly cropped, product-focused photography and naturalistic lifestyle shots within rounded cards. Photography often features human subjects interacting subtly with the product or in states of calm/focus. Colors in imagery appear natural and sometimes sun-drenched, contributing to a sense of well-being. Icons are minimal, likely outlined and monochromatic, serving a functional purpose. Image density is balanced, allowing significant text blocks while visuals break up sections without overwhelming the layout, primarily serving an explanatory or aspirational role within soft-edged cards.

## Layout

The page primarily uses a full-bleed structure for hero and section backgrounds, but content within these sections is often centered and contained. The hero features a large radial gradient blending Canvas Warmth with a warmer gray, centered text, and a product image. Sections alternate between light and warm gray backgrounds (Canvas Warmth) for visual rhythm. Content is arranged in alternating 2-column sections (text-left/image-right) and centered stacks. Card grids are utilized for features, displaying images and text within generously rounded containers. Navigation is a simple top bar with text links and a filled primary button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fcf9f7
border: #d1cfcd
accent: no distinct accent color
primary action: #05060b (filled action)

Example Component Prompts:
Create a hero section with a radial gradient from #fcf9f7 to #a89c8a, containing a centered heading 'Listen to your breath and shift your state in real time.' using Hanken Grotesk 52px weight 500, #262628, normal letter-spacing, and a subtext 'Alveos One detects breathing changes...' using Inter 16px weight 400, #575757. Below, place a 'Pre-Order Now' button with background #05060b, text #fcf9f7, 12px radius, 14px vertical and 30px horizontal padding, using system sans-serif 12px weight 600 with 0.444em letter-spacing.

Generate a 'Discover more' content card: Background #ffffff, 25px radius. Inside, place a product image with 20px radius at the top, a heading 'Find Your Calm' with Hanken Grotesk 24px weight 600, #262628, and descriptive text 'Breathe with awareness. Alveos One helps you...' with Inter 16px weight 400, #575757, using 20px internal padding. Add a subtle shadow 'rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px' for elevation.

Create a secondary navigation link labeled 'Science': Use system sans-serif 12px weight 400, #000000, with 0.444em letter-spacing. On hover, apply a mild interaction without changing its background directly but possibly adding a subtle underscore or increasing visual weight slightly without deviating from the neutral palette.

Design a 'Join the waiting list' button: Background #05060b, text #fcf9f7, 12px radius, 14px vertical and 30px horizontal padding, using system sans-serif 12px weight 600 with 0.444em letter-spacing. Place it on a Canvas Warmth (#fcf9f7) background section with 50px section gap above and below.

## Similar Brands

- **Oura Ring** — Shares a focus on wellness tech, a clean, human-centered aesthetic, and subtle branding through product-focused imagery combined with soft, minimal UI.
- **Eight Sleep** — Exhibits a similar sophisticated, light UI with soft neutrals, high-quality product photography, and a calm, approachable tone. Uses subtle shadows for depth.
- **Calm (app website)** — Employs serene color palettes, simple layouts, and a focus on soft typography and imagery to convey a sense of peace and well-being, similar to Alveos's understated elegance.
- **Whoop** — Fitness tech with a similar approach to clean, modern product display combined with a mostly neutral palette and focused, clear typographical hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-warmth: #fcf9f7;
  --gradient-canvas-warmth: radial-gradient(50% 95% at 50% 108.6%, rgb(252, 249, 247) 0%, rgb(168, 156, 138) 100%);
  --color-surface-white: #ffffff;
  --color-deep-graphite: #05060b;
  --color-text-black: #000000;
  --color-headline-dark: #262628;
  --color-body-gray: #575757;
  --color-muted-text: #a5a5a5;
  --color-line-gray: #d1cfcd;
  --color-ghost-fill: #030f1c;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hanken-grotesk: 'Hanken Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-mono: 'SF Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 4.44px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --text-display: 52px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-150: 150px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 25px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 25px;
  --radius-images: 20px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 1px 5px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 2px 10px 0px;

  /* Surfaces */
  --surface-canvas-warmth: #fcf9f7;
  --surface-surface-white: #ffffff;
  --surface-subtle-background-card: #0a0a0a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-warmth: #fcf9f7;
  --color-surface-white: #ffffff;
  --color-deep-graphite: #05060b;
  --color-text-black: #000000;
  --color-headline-dark: #262628;
  --color-body-gray: #575757;
  --color-muted-text: #a5a5a5;
  --color-line-gray: #d1cfcd;
  --color-ghost-fill: #030f1c;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hanken-grotesk: 'Hanken Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-mono: 'SF Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 4.44px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --text-display: 52px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-150: 150px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 25px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 1px 5px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.08) 0px 8px 30px 0px, rgba(0, 0, 0, 0.05) 0px 2px 8px 0px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 2px 10px 0px;
}
```
