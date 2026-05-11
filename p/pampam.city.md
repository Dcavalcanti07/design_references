# pampam.city — Style Reference
> Soft Canvas Typography

**Theme:** light

PamPam uses a bright, inviting canvas with clean, minimalist typography and subtle accents. The interface prioritizes clarity and a light, spacious feel, with elements appearing on a slightly off-white background. The design is subtly playful yet functional, using rounded corners and muted chromatic touches for interactive elements and brand differentiation. Overall, the visual style supports a product that is approachable and easy to use.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card and component surfaces in some contexts, text on darker backgrounds |
| Buttermilk | `#faf2ec` | `--color-buttermilk` | Primary background for the application, secondary card and component surfaces |
| Ash Gray | `#e5e5e5` | `--color-ash-gray` | Subtle background for UI elements, dividers, or very light borders |
| Ink Black | `#000000` | `--color-ink-black` | Primary text for headings and body, accent for outlining non-primary buttons and inputs |
| Charcoal | `#1b1917` | `--color-charcoal` | Main heading text color, providing strong contrast against light backgrounds |
| Cool Gray | `#8f8f8f` | `--color-cool-gray` | Muted secondary text, helper text, and subtle interface elements |
| Slate Blue | `#9894a8` | `--color-slate-blue` | Muted interactive text, outlined button borders for secondary actions, and placeholder-like text |
| Field Green | `#2b3ea7` | `--color-field-green` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### -apple-system — Body text, navigation links, and some button labels. Provides universal readability. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 16px, 18px, 24px
- **Line height:** 1.00, 1.20, 1.56
- **Letter spacing:** normal
- **Role:** Body text, navigation links, and some button labels. Provides universal readability.

### inter — Utility text, small labels, and input fields. Enhances legibility at smaller sizes. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 550
- **Sizes:** 14px, 16px, 18px, 19px
- **Line height:** 1.43, 1.47, 1.50, 1.56
- **Letter spacing:** normal
- **OpenType features:** `"cv02", "cv03", "cv04", "cv06", "cv11"`
- **Role:** Utility text, small labels, and input fields. Enhances legibility at smaller sizes.

### nineties — Display headlines and prominent titles. Its unique character defines the brand's typographic voice. · `--font-nineties`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 28px, 48px, 80px
- **Line height:** 1.08
- **Letter spacing:** normal
- **Role:** Display headlines and prominent titles. Its unique character defines the brand's typographic voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 16px | 1.56 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 28px | 1.08 | — | `--text-heading` |
| heading-lg | 48px | 1.08 | — | `--text-heading-lg` |
| display | 80px | 1.08 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 16px |
| general | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgb(99, 135, 244) 0px...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 64px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Standard Button
**Role:** Primary interaction button

Buttermilk background (#faf2ec) with Ink Black text (#000000) and a 16px border-radius. Padding is 16px all around.

### Outlined Muted Button
**Role:** Secondary interaction or ghost button

Transparent background with Slate Blue text (#9894a8) and a Slate Blue border (#9894a8), 0px border-radius. Padding is 8px vertical, 12px horizontal.

### Feature Card
**Role:** Content container for features or examples

Buttermilk background (#faf2ec) with 12px border-radius and no shadow or border. Content inside has no additional padding.

### Standard Input Field
**Role:** Form input elements

Transparent background with Charcoal text (#222222) and Charcoal border (#222222). Padding is 8px vertical.

## Do's and Don'ts

### Do
- Use Buttermilk (#faf2ec) as the default background for most content sections and cards to maintain visual lightness.
- Apply a 12px border-radius to all cards and images for a consistent soft-edged aesthetic.
- Reserve the 'nineties' font for display-level headlines (48px, 80px) using Charcoal (#1b1917) for strong visual impact.
- Utilize Ink Black (#000000) for primary body text and as a strong border color for key interactive elements.
- Maintain comfortable density by using 12px for `elementGap` between most UI components.
- Prioritize the `Standard Button` with a Buttermilk (#faf2ec) background and Ink Black (#000000) text for main calls to action.
- Employ Slate Blue (#9894a8) for subtle interactive text and outlined button borders for less prominent actions immediately adjacent to content.

### Don't
- Avoid using harsh, saturated colors as primary backgrounds; adhere to the neutral palette for canvas and surfaces.
- Do not deviate from the specified border-radius values (e.g., 12px for cards, 16px for buttons) to preserve the design's rounded character.
- Refrain from using the 'nineties' font for body copy or small text, as it is intended for display purposes only.
- Do not introduce strong, intrusive shadows; existing shadows are subtle and provide minimal depth.
- Avoid excessive use of outlines; apply the `Outlined Muted Button` sparingly for secondary actions.
- Do not reduce content padding within cards; maintain the spacious feel with the default 12px card padding.
- Resist using bold font weights for body text; rely on the '-apple-system' and 'inter' fonts at their specified weights for readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White Base | `#ffffff` | Primary page background layer, providing high contrast for text. |
| 1 | Buttermilk Canvas | `#faf2ec` | Secondary background layer for most content areas, cards, and sections. |
| 2 | Ash Gray Detail | `#e5e5e5` | Subtle background for specific UI elements, dividers, or very light container backgrounds. |

## Elevation

- **Card/Interactive Element:** `rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 4px 0px`
- **Accent Element (Inset):** `rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgb(99, 135, 244) 0px 2px 0px 0px inset`
- **Minor Element:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px`

## Agent Prompt Guide

Quick Color Reference:
text: #1b1917
background: #faf2ec
border: #000000 (for strong outlines), #9894a8 (for muted outlines)
accent: #2b3ea7
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a feature card: Buttermilk background (#faf2ec), 12px border-radius, no shadow, no internal padding. Content elements inside should use 'inter' font at 16px with normal letter-spacing.
3. Make a secondary action button with a muted style: Transparent background, Slate Blue text (#9894a8), Slate Blue border (#9894a8), 0px border-radius, 8px vertical padding, 12px horizontal padding. Font '-apple-system' weight 400, 16px.
4. Produce an input field: Transparent background, Charcoal text (#222222), Charcoal border (#222222), 8px vertical padding. Font 'inter' weight 400, 16px with normal letter-spacing.

## Similar Brands

- **Figma** — Clean white interface, soft curves, and a focus on product screenshots within the UI.
- **Notion** — Minimalist aesthetic with high contrast text, comfortable spacing, and soft neutral palettes supporting content.
- **Linear** — Emphasis on crisp typography and subtle use of accent colors to denote interactivity over heavy branding.
- **Webflow** — Product-focused design, use of rounded cards, and a balance of clear text with illustrative visuals.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-buttermilk: #faf2ec;
  --color-ash-gray: #e5e5e5;
  --color-ink-black: #000000;
  --color-charcoal: #1b1917;
  --color-cool-gray: #8f8f8f;
  --color-slate-blue: #9894a8;
  --color-field-green: #2b3ea7;

  /* Typography — Font Families */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nineties: 'nineties', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 28px;
  --leading-heading: 1.08;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --text-display: 80px;
  --leading-display: 1.08;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w550: 550;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 16px;
  --radius-general: 20px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 4px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgb(99, 135, 244) 0px 2px 0px 0px inset;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px;

  /* Surfaces */
  --surface-canvas-white-base: #ffffff;
  --surface-buttermilk-canvas: #faf2ec;
  --surface-ash-gray-detail: #e5e5e5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-buttermilk: #faf2ec;
  --color-ash-gray: #e5e5e5;
  --color-ink-black: #000000;
  --color-charcoal: #1b1917;
  --color-cool-gray: #8f8f8f;
  --color-slate-blue: #9894a8;
  --color-field-green: #2b3ea7;

  /* Typography */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nineties: 'nineties', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 28px;
  --leading-heading: 1.08;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --text-display: 80px;
  --leading-display: 1.08;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 4px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgb(99, 135, 244) 0px 2px 0px 0px inset;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px;
}
```
