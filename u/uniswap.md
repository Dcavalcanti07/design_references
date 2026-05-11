# Uniswap — Style Reference
> Neon accent on white canvas

**Theme:** light

Uniswap's design system embraces a 'soft tech' aesthetic, balancing a vibrant, almost playful color palette with clean, functional UI elements. The layout features generous negative space and a light canvas, punctuated by rounded cards and ghost buttons. A single vivid pink serves as the primary accent, creating clear calls to action amidst a mostly achromatic interface. Typography is compact and precise, contributing to a feeling of efficiency and modern reliability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, default button fills |
| Surface Frost | `#f9f9f9` | `--color-surface-frost` | Subtle background for card-like elements, indicating a slight elevation from the base canvas |
| Action Pink | `#ff37c7` | `--color-action-pink` | Primary calls to action, active navigation indicators, link highlights — a vibrant, eye-catching color against the neutral backdrop |
| Action Pink Light | `#fef4ff` | `--color-action-pink-light` | Primary page canvas and white card surfaces. Do not promote it to the primary CTA color |
| Text Primary | `#131313` | `--color-text-primary` | Dominant text color for headings and essential body copy, providing strong contrast |
| Text Secondary | `#222222` | `--color-text-secondary` | Secondary text, button text on ghost buttons, and subtle interface details |
| Text Muted | `#6a6a6a` | `--color-text-muted` | Helper text, captions, and deactivated navigation items — a softer grey for less emphasis |
| Text Placeholder | `#acacac` | `--color-text-placeholder` | Placeholder text in input fields and other non-essential text |
| Border Grey | `#f2f2f2` | `--color-border-grey` | Subtle borders for input fields and ghost buttons |
| Icon Violet | `#8251fb` | `--color-icon-violet` | Decorative icons and occasional branded accent text, used sparingly for specific feature highlights |
| Icon Orange | `#ff4d00` | `--color-icon-orange` | Decorative icons and occasional branded accent text, used sparingly for specific feature highlights |
| Icon Teal | `#00c3a0` | `--color-icon-teal` | Decorative icons and occasional branded accent text, used sparingly for specific feature highlights |
| Icon Blue | `#2abdff` | `--color-icon-blue` | Decorative icons and occasional branded accent text, used sparingly for specific feature highlights |
| Semantic Success Green | `#0c8911` | `--color-semantic-success-green` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Semantic Error Red | `#e01a2b` | `--color-semantic-error-red` | Red decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Basel — The primary typeface for all UI elements and content, providing a consistent, compact, and confident tone. Its slight letter-spacing reduction across sizes makes it feel more purposeful and less generic. · `--font-basel`
- **Substitute:** system-ui
- **Weights:** 400, 485, 500, 535
- **Sizes:** 11px, 12px, 13px, 14px, 16px, 18px, 24px, 36px, 52px, 64px
- **Line height:** 0.75, 0.96, 1.00, 1.11, 1.15, 1.19, 1.20, 1.25, 1.30, 1.33, 1.49, 3.00
- **Letter spacing:** -0.020em
- **Role:** The primary typeface for all UI elements and content, providing a consistent, compact, and confident tone. Its slight letter-spacing reduction across sizes makes it feel more purposeful and less generic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.49 | -0.22px | `--text-caption` |
| body | 14px | 1.19 | -0.28px | `--text-body` |
| subheading | 18px | 1.15 | -0.36px | `--text-subheading` |
| heading | 24px | 1.25 | -0.48px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.72px | `--text-heading-lg` |
| display | 64px | 0.96 | -1.28px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 20px |
| md | 12px |
| sm | 8px |
| xl | 24px |
| none | 0px |
| pill | 999999px |
| circle | 50% |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `color(srgb 0.0745098 0.0745098 0.0745098 / 0.00313726) 0p...` | `--shadow-md` |

### Layout

- **Section gap:** 24px
- **Card padding:** 8px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action

Background: Action Pink (#ff37c7). Text: Canvas White (#ffffff). Radius: 999999px (pill). Padding: 4px. Font: Basel, weight 485.

### Ghost Button
**Role:** Secondary and tertiary actions that need less emphasis

Background: transparent. Border: 1px solid Text Primary (#131313). Text: Text Primary (#131313). Radius: 12px. Padding: 8px 12px.

### Filled Secondary Button
**Role:** Secondary action button with a subtle fill

Background: rgba(19, 19, 19, 0.08). Text: Text Secondary (#222222). Radius: 999999px (pill). Padding: 4px. Font: Basel, weight 485.

### Input Card
**Role:** Container for user inputs and content blocks

Background: Surface Frost (#f9f9f9). Radius: 20px. Padding: 0. Shadows: none. Internally may contain elements with Canvas White backgrounds.

### Elevated Content Card
**Role:** Prominent content card, often used for interactive tools or feature showcases

Background: Canvas White (#ffffff). Radius: 24px. Padding: 8px. Shadows: none.

### Minimal Input Field
**Role:** Standard text input field

Background: transparent (often on a Surface Frost card). Text: Text Primary (#131313). Placeholder Text: Text Placeholder (#acacac). Border: transparent. Focus state not explicit but likely a subtle border or glow.

### Navigation Link
**Role:** Top-level navigation items

Text: Text Primary (#131313) for inactive, Action Pink (#ff37c7) for active. Underline: 1px Action Pink (#ff37c7) for active state. Radius: 20px for the hover container. Padding: variable. Font: Basel, weight 400.

## Do's and Don'ts

### Do
- Use Basel typeface at varying weights (400, 485, 500, 535) with a -0.020em letter-spacing for all text elements.
- Prioritize Canvas White (#ffffff) for the primary page background and Surface Frost (#f9f9f9) for card elements to establish surface hierarchy.
- Apply Action Pink (#ff37c7) exclusively for primary calls to action, clear active states, and critical interactive elements.
- Utilize 999999px (pill) radius for all primary action buttons and small interactive elements, and 20px-24px for cards.
- Maintain comfortable spacing with 8px as the primary element gap and 24px for section separation.
- Layer text colors from Text Primary (#131313) to Text Muted (#6a6a6a) to convey information hierarchy clearly.
- Incorporate highly rounded, almost pill-shaped corners (999999px) for buttons and similar interactive elements for a distinct friendly feel.

### Don't
- Do not introduce new saturated colors for interactive elements; rely on the established brand and accent colors.
- Avoid heavy drop shadows or strong elevation effects; a minimal or absent shadow approach is preferred.
- Do not deviate from the Basel typeface or its specified letter-spacing for any UI text.
- Do not use generic square or slightly rounded components; ensure cards have at least a 20px radius.
- Refrain from using deep, dark backgrounds for main content areas, as the system is built on a light canvas.
- Avoid cluttering layouts; always prioritize generous negative space and comfortable density.
- Do not use transparent backgrounds for action buttons when Action Pink (#ff37c7) is available for a filled state.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, providing a bright, expansive base. |
| 1 | Surface Frost | `#f9f9f9` | Background for secondary containers and inputs, indicating a slight lift or contained area. |
| 2 | Elevated Card | `#ffffff` | Prominent cards or interactive components, standing out on the Surface Frost layer; uses the same color as the canvas but distinct by radius. |

## Elevation

- **button:** `color(srgb 0.0745098 0.0745098 0.0745098 / 0.00313726) 0px 0px 10px 0px`

## Imagery

The visual language for imagery leans heavily into abstract, blurred, organic shapes used as background decoration, often with a pastel color palette. These elements are atmospheric rather than informative, adding a soft, playful energy. Icons are typically single-color, clean, and functional, frequently adopting one of the accent colors (#8251fb, #ff4d00, #f50db4, #2abdff, #00c3a0). Photography and screenshots are product-focused and often presented within rounded containers, maintaining the overall soft aesthetic. The density is moderate; imagery serves to break up text and add visual interest without overpowering the UI.

## Layout

The page primarily uses a full-bleed layout, allowing background elements to extend to the edges. Content, however, is contained within an implicit maximum width, centered on the screen, creating clear reading paths. The hero section often features a prominent, centered headline over a diffused graphical background. Sections generally follow a consistent vertical rhythm with minimal visual dividers, flowing seamlessly. Content is frequently arranged in balanced two-column text-left/image-right or text-over-card blocks, with some sections utilizing a three-column card grid for features. The overall density is comfortable, with ample whitespace surrounding content blocks. Navigation is a sticky top bar with clear, compact links and a prominent 'Connect' action button.

## Agent Prompt Guide

Quick Color Reference: 
text: #131313
background: #ffffff
border: #f2f2f2
accent: #ff37c7
primary action: #ff37c7 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff37c7 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design an input card: background Surface Frost (#f9f9f9), radius 20px, no shadows, internal padding 8px for contents, surrounded by 8px element gap from other components.
3. Build a prominent page heading: text Text Primary (#131313), font Basel weight 535, size 64px, lineHeight 0.96, letterSpacing -1.28px.

## Similar Brands

- **Framer** — Shares a light canvas, highly rounded UI elements, and a single vibrant accent color for interaction.
- **Rive** — Similar use of abstract, blurred background graphics and a modern, slightly playful aesthetic on a clean interface.
- **Superhuman** — Employs a precise, compact typography style and a highly functional, minimalist UI with strategic use of color for actions.
- **Linear** — Features a clean white background, deliberate tight spacing, and fine-grained control over typography scale and tracking.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f9f9f9;
  --color-action-pink: #ff37c7;
  --color-action-pink-light: #fef4ff;
  --color-text-primary: #131313;
  --color-text-secondary: #222222;
  --color-text-muted: #6a6a6a;
  --color-text-placeholder: #acacac;
  --color-border-grey: #f2f2f2;
  --color-icon-violet: #8251fb;
  --color-icon-orange: #ff4d00;
  --color-icon-teal: #00c3a0;
  --color-icon-blue: #2abdff;
  --color-semantic-success-green: #0c8911;
  --color-semantic-error-red: #e01a2b;

  /* Typography — Font Families */
  --font-basel: 'Basel', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.49;
  --tracking-caption: -0.22px;
  --text-body: 14px;
  --leading-body: 1.19;
  --tracking-body: -0.28px;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.36px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 64px;
  --leading-display: 0.96;
  --tracking-display: -1.28px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w485: 485;
  --font-weight-medium: 500;
  --font-weight-w535: 535;

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
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 8px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4.8px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-full: 100px;
  --radius-full-2: 999999px;

  /* Named Radii */
  --radius-lg: 20px;
  --radius-md: 12px;
  --radius-sm: 8px;
  --radius-xl: 24px;
  --radius-none: 0px;
  --radius-pill: 999999px;
  --radius-circle: 50%;

  /* Shadows */
  --shadow-md: color(srgb 0.0745098 0.0745098 0.0745098 / 0.00313726) 0px 0px 10px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-surface-frost: #f9f9f9;
  --surface-elevated-card: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f9f9f9;
  --color-action-pink: #ff37c7;
  --color-action-pink-light: #fef4ff;
  --color-text-primary: #131313;
  --color-text-secondary: #222222;
  --color-text-muted: #6a6a6a;
  --color-text-placeholder: #acacac;
  --color-border-grey: #f2f2f2;
  --color-icon-violet: #8251fb;
  --color-icon-orange: #ff4d00;
  --color-icon-teal: #00c3a0;
  --color-icon-blue: #2abdff;
  --color-semantic-success-green: #0c8911;
  --color-semantic-error-red: #e01a2b;

  /* Typography */
  --font-basel: 'Basel', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.49;
  --tracking-caption: -0.22px;
  --text-body: 14px;
  --leading-body: 1.19;
  --tracking-body: -0.28px;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.36px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 64px;
  --leading-display: 0.96;
  --tracking-display: -1.28px;

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
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4.8px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-full: 100px;
  --radius-full-2: 999999px;

  /* Shadows */
  --shadow-md: color(srgb 0.0745098 0.0745098 0.0745098 / 0.00313726) 0px 0px 10px 0px;
}
```
