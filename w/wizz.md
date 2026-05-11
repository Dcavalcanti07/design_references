# Wizz — Style Reference
> Fuchsia-powered dark mode

**Theme:** dark

Wizz embraces a bold, high-contrast dark theme with a vibrant fuchsia accent color that creates a playful, energetic atmosphere. Typography is a central element, using distinct custom sans-serif typefaces for sharp, impactful headlines and clear body text. Surfaces are mostly dark and flat, relying on the single accent color for primary actions and highlights, with subtle elevation for key interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page backgrounds, card surfaces, primary text on light backgrounds |
| Ghost White | `#ffffff` | `--color-ghost-white` | Prominent text on dark backgrounds, active states |
| Steel Gray | `#dadada` | `--color-steel-gray` | Muted text, hairline borders, placeholder text |
| Ink Wash | `#444444` | `--color-ink-wash` | Subtle dark backgrounds, input text |
| Charcoal | `#292929` | `--color-charcoal` | Secondary surface backgrounds, ghost button fills |
| Cloud Mist | `#eeeeee` | `--color-cloud-mist` | Input background fill on light surfaces |
| Wizz Fuchsia | `#ff3d9e` | `--color-wizz-fuchsia` | Primary action buttons, links, accents on headings, input active states – creates immediate visual focus and brand recognition |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### PolySans Median — Dominant display and headline font for punchy, modern statements, also used for some body text and navigation items. · `--font-polysans-median`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 13px, 14px, 16px, 18px, 86px
- **Line height:** 0.85, 1.00, 1.10, 1.20, 1.25, 1.44, 1.50, 2.00
- **Letter spacing:** -0.0100em at 86px, 0.0500em at 10-18px
- **Role:** Dominant display and headline font for punchy, modern statements, also used for some body text and navigation items.

### PolySans Neutral — Supplemental body and link text, offering clean readability in smaller contexts. · `--font-polysans-neutral`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.20, 1.30, 1.40, 1.50
- **Role:** Supplemental body and link text, offering clean readability in smaller contexts.

### PolySans Bulky — Used for very large, impactful titles, commanding attention. · `--font-polysans-bulky`
- **Substitute:** Inter Bold
- **Weights:** 700
- **Sizes:** 72px
- **Line height:** 1.00
- **Role:** Used for very large, impactful titles, commanding attention.

### PolySans Slim — Delicate, light-weight text for subtle headings, links, and buttons, conveying a sophisticated restraint. · `--font-polysans-slim`
- **Substitute:** Inter Light
- **Weights:** 300
- **Sizes:** 14px
- **Line height:** 1.00, 1.10
- **Role:** Delicate, light-weight text for subtle headings, links, and buttons, conveying a sophisticated restraint.

### Inter — Default system font for utility text, labels, and card descriptions. · `--font-inter`
- **Substitute:** System UI
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Default system font for utility text, labels, and card descriptions.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.5px | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| heading-sm | 18px | 1.25 | — | `--text-heading-sm` |
| heading | 72px | 1 | — | `--text-heading` |
| display | 86px | 0.85 | -1px | `--text-display` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| inputs | 12px |
| avatars | 24px |
| buttons | 12px |
| navItems | 999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.05) 0px 1px 10px 0px` | `--shadow-md` |
| xl | `rgba(0, 0, 0, 0.3) 0px 1px 30px 0px` | `--shadow-xl` |
| subtle | `rgb(218, 218, 218) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** The main call to action button.

Filled with Wizz Fuchsia (#ff3d9e), text in browser default blue (likely overridden to white in practice), 12px border radius, 10px vertical and 16px horizontal padding.

### Ghost Header Button
**Role:** Used for secondary actions in the header.

Background Charcoal (#292929), text in browser default blue (likely white). Has a 999px border radius (pill shape) with 4px vertical and 10px horizontal padding.

### Nav Link
**Role:** Standard navigation item with minimal styling.

Transparent background, Steel Gray (#dadada) text color, no border or radius, zero padding.

### Cookie Consent Card
**Role:** Information panel for cookie settings.

Midnight Void (#000000) background, 14px border radius, inset border of 1px solid Steel Gray (#dadada).

### Text Input (Dark)
**Role:** Standard text input field in a dark context.

Midnight Void (#000000) background, Ink Wash (#444444) text, Ink Wash (#444444) border, 10px border radius, 10px padding.

### Text Input (Light)
**Role:** Standard text input field in a light context.

Cloud Mist (#eeeeee) background, Ink Wash (#444444) text, Ink Wash (#444444) border, 10px border radius, 10px padding.

## Do's and Don'ts

### Do
- Use Midnight Void (#000000) as the primary background for all major sections unless otherwise specified.
- Apply Wizz Fuchsia (#ff3d9e) for all primary calls to action, ensuring text color contrasts sufficiently.
- Utilize 12px border radius for all inputs, buttons, and cards to maintain a consistent soft, modern feel.
- Employ PolySans Median for all headings to leverage its distinct character, varying weights as needed for hierarchy.
- Maintain a clear visual hierarchy by contrasting Ghost White (#ffffff) for primary text on dark backgrounds and Midnight Void (#000000) for text on lighter neutral sections.
- Use a 999px border radius (pill shape) for all ghost buttons and small informational tags in the header.
- Apply Steel Gray (#dadada) for subtle dividers, borders, and muted supporting text.

### Don't
- Avoid generic system default colors; exclusively use colors from the defined palette.
- Do not use multiple accent colors; Wizz Fuchsia (#ff3d9e) is the sole vibrant accent for interactivity and brand highlighting.
- Do not introduce heavy shadows or gradients on elements; maintain a largely flat and sharp aesthetic with subtle elevation for key interactive components.
- Avoid using serif fonts or highly decorative typefaces; adhere strictly to the PolySans family and Inter for all textual content.
- Do not deviate from the established border radii for components; the varied but specific radii (12px, 999px, 24px) are a key part of the brand's visual identity.
- Do not use broad, full-width content sections; contain most content within a defined horizontal width for better readability and structure.
- Avoid overly bright or light backgrounds for main content areas; maintain the dark-mode aesthetic predominantly.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Background | `#000000` | Dominant background for the entire application and sections. |
| 1 | Card Surface | `#000000` | Background for cards and information panels, often with an inset border for definition. |
| 2 | Subtle Surface | `#292929` | Used for ghost buttons and secondary background elements, providing a slight elevation from the canvas without strong contrast. |
| 3 | Input Background (Light) | `#eeeeee` | Background for input fields, typically on lighter content sections. |

## Elevation

- **Dropdown/Menu:** `rgba(0, 0, 0, 0.05) 0px 1px 10px 0px`
- **Button (promoted):** `rgba(0, 0, 0, 0.3) 0px 1px 30px 0px`
- **Card (inset border):** `rgb(218, 218, 218) 0px 0px 0px 1px inset`

## Imagery

The site uses a mix of dark, immersive gradients for hero sections and UI surfaces (blending purple, orange, pink), contrasted with clean, product-focused photography featuring phone screens and diverse user profile images. Graphics are minimal, relying on simple icons (likely outlined, matching the site's generally sparse visual style). Imagery is primarily decorative atmosphere for the hero and expressive content for user representation, maintaining a high-contrast aesthetic against dark backgrounds.

## Layout

The page primarily uses a full-bleed layout for background elements and a centered, contained content model for text and components, with an implicit max-width. The hero section often features a full-width gradient backdrop with a large, centered headline. Content sections alternate between visually distinct blocks, often presenting a two-column layout with text on one side and a visual (like a phone screenshot or user gallery) on the other. Vertical rhythm is established through consistent section gaps. Navigation is a sticky top bar with pill-shaped buttons and subtly styled links.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #dadada
accent: #ff3d9e
primary action: #ff3d9e (filled action)

Example Component Prompts:
1. Create a Primary Action Button: Wizz Fuchsia (#ff3d9e) background, text color should contrast well (e.g. #ffffff), 12px radius, 10px vertical and 16px horizontal padding, PolySans Slim 14px weight 300 text.
2. Create a Header Ghost Button: Charcoal (#292929) background, Ghost White (#ffffff) text, 999px radius, 4px vertical and 10px horizontal padding, PolySans Median 14px weight 400 text.
3. Create a Cookie Consent Card: Midnight Void (#000000) background, 14px radius, 1px inset border of Steel Gray (#dadada), with Inter 12px weight 400 text for its content.
4. Create a prominent heading: PolySans Bulky 72px weight 700 text, Ghost White (#ffffff) color.

## Similar Brands

- **Discord** — Dark UI with a single vibrant accent color for interaction and branding.
- **Figma** — Sharp, modern typography and a focus on clean, functional dark surfaces with minimal decorative elements.
- **Linear** — High-contrast dark theme, crisp typography, and subtle elevation for core UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #ffffff;
  --color-steel-gray: #dadada;
  --color-ink-wash: #444444;
  --color-charcoal: #292929;
  --color-cloud-mist: #eeeeee;
  --color-wizz-fuchsia: #ff3d9e;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-median: 'PolySans Median', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-neutral: 'PolySans Neutral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-bulky: 'PolySans Bulky', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-slim: 'PolySans Slim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.25;
  --text-heading: 72px;
  --leading-heading: 1;
  --text-display: 86px;
  --leading-display: 0.85;
  --tracking-display: -1px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 45px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-inputs: 12px;
  --radius-avatars: 24px;
  --radius-buttons: 12px;
  --radius-navitems: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 1px 10px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.3) 0px 1px 30px 0px;
  --shadow-subtle: rgb(218, 218, 218) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-canvas-background: #000000;
  --surface-card-surface: #000000;
  --surface-subtle-surface: #292929;
  --surface-input-background-light: #eeeeee;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #ffffff;
  --color-steel-gray: #dadada;
  --color-ink-wash: #444444;
  --color-charcoal: #292929;
  --color-cloud-mist: #eeeeee;
  --color-wizz-fuchsia: #ff3d9e;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-median: 'PolySans Median', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-neutral: 'PolySans Neutral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-bulky: 'PolySans Bulky', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-polysans-slim: 'PolySans Slim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.25;
  --text-heading: 72px;
  --leading-heading: 1;
  --text-display: 86px;
  --leading-display: 0.85;
  --tracking-display: -1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 45px;
  --radius-full: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 1px 10px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.3) 0px 1px 30px 0px;
  --shadow-subtle: rgb(218, 218, 218) 0px 0px 0px 1px inset;
}
```
