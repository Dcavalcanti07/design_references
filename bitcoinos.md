# BitcoinOS — Style Reference
> Dark Command Center

**Theme:** dark

BitcoinOS projects a dark, futuristic command center aesthetic: deep charcoal canvases, stark white typography, and structural borders define its visual identity. Typography is oversized and confident, with a mix of condensed and expanded forms to create a distinct, almost monumental feel. Components are lightweight and often border-defined rather than filled, conveying a sense of precision and advanced technology. The overall impression is one of a high-tech interface, authoritative yet minimal.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Truffle | `#000000` | `--color-midnight-truffle` | Primary text on light surfaces, button text on light backgrounds, primary stroke in dark mode, navigation item borders. Creates stark contrast |
| Digital Canvas | `#101010` | `--color-digital-canvas` | Page background, card backgrounds, footer background. The base dark surface that defines the theme |
| Ash Graphite | `#1a1a1a` | `--color-ash-graphite` | Subtle background for UI elements, slightly elevated from the Digital Canvas |
| Slate Steel | `#272727` | `--color-slate-steel` | High-contrast neutral action fill for primary buttons on light surfaces. |
| Ghost White | `#fffafa` | `--color-ghost-white` | Primary text, heading text, button text, main border color in dark mode. The dominant contrasting element against dark backgrounds |
| Muted Silver | `#bababa` | `--color-muted-silver` | Secondary text, muted links, subtle borders. Reduces visual weight for less critical information |

## Tokens — Typography

### Times — Body text for longer content blocks, paragraph text, providing a classic counterpoint to the more modern display fonts. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Body text for longer content blocks, paragraph text, providing a classic counterpoint to the more modern display fonts.

### Kalice — Navigation items, small labels, and utility text. Its monospace nature provides a technical, data-driven feel. · `--font-kalice`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px, 16px, 24px
- **Line height:** 1.00, 1.40, 1.60
- **Letter spacing:** 0.0400em, 0.0600em
- **Role:** Navigation items, small labels, and utility text. Its monospace nature provides a technical, data-driven feel.

### Review — Component labels, main body headings, primary links, and button text, offering a strong, clear voice with varying tracking for different sizes. · `--font-review`
- **Substitute:** sans-serif
- **Weights:** 700, 900
- **Sizes:** 14px, 18px, 32px
- **Line height:** 0.75, 0.88, 1.00, 1.10
- **Letter spacing:** -0.0100em, 0.0100em, 0.0200em
- **Role:** Component labels, main body headings, primary links, and button text, offering a strong, clear voice with varying tracking for different sizes.

### Review Condensed — Dominant display headlines and hero text. Its condensed, bold nature makes a dramatic, architectural statement, leveraging the large sizes for impact. · `--font-review-condensed`
- **Substitute:** sans-serif
- **Weights:** 900
- **Sizes:** 72px, 128px
- **Line height:** 0.80
- **Letter spacing:** normal
- **Role:** Dominant display headlines and hero text. Its condensed, bold nature makes a dramatic, architectural statement, leveraging the large sizes for impact.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | 0.48px | `--text-caption` |
| body-sm | 14px | 1.1 | -0.14px | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| body-lg | 18px | 1.1 | 0.18px | `--text-body-lg` |
| heading | 32px | 0.88 | 0.64px | `--text-heading` |
| display-lg | 72px | 0.8 | — | `--text-display-lg` |
| display | 128px | 0.8 | — | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 2px |
| buttons | 8px |
| default | 16px |
| decorative | 48px |
| smallComponents | 8px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Interactive elements with minimal visual footprint.

Background: rgba(0, 0, 0, 0), Text: Ghost White (#fffafa), Border: Midnight Truffle (#000000), Radius: 8px, No padding at root level (inherited from parent).

### Outlined Button
**Role:** Secondary action or navigation items.

Background: Slate Steel (#272727), Text: Ghost White (#fffafa), Border: Ghost White (#fffafa), Radius: 8px, No padding at root level.

### Filled Primary Button
**Role:** Main call to action.

Background: Ghost White (#fffafa), Text: Midnight Truffle (#000000), Border: Midnight Truffle (#000000), Radius: 8px, No padding at root level.

### Ghost Card
**Role:** Structural container for content without visual background.

Background: rgba(0, 0, 0, 0), Border: none, Radius: 0px, No padding.

### Standard Card
**Role:** Content presentation with a clear visual boundary.

Background: Ghost White (#fffafa), Border: none, Radius: 8px, Padding: 24px.

### Dark Card
**Role:** Content container for specific sections requiring a darker contrast.

Background: Digital Canvas (#101010), Border: none, Radius: 16px, No padding.

### Circular Card
**Role:** Decorative or specific content cards with a rounded shape.

Background: Digital Canvas (#101010), Border: none, Radius: 100%, No padding.

### Text Input
**Role:** User input fields.

Background: rgba(0, 0, 0, 0), Text: Ghost White (#fffafa), Border: Ghost White (#fffafa), Radius: 0px, Horizontal padding: 16px.

### Navigation Bar Item
**Role:** Primary navigation links and sections.

Font: Kalice, Weight: 400, Color: Ghost White (#fffafa). Often accompanied by a subtle border or minimal background highlight on hover/active.

## Do's and Don'ts

### Do
- Prioritize high contrast between text and background, using Ghost White (#fffafa) on Digital Canvas (#101010) or Midnight Truffle (#000000) on Ghost White for primary content.
- Use Review Condensed (900 weight, 72px or 128px) for all prominent headlines to convey authority and impact.
- Apply 16px border-radius as the default for most container elements like cards and images, with 8px for smaller interactive components like buttons.
- Utilize border-defined elements over solid fills for a lightweight, technical feel. For example, use Ghost Button with rgba(0,0,0,0) background and a Midnight Truffle (#000000) border.
- Maintain a clear vertical rhythm using 64px section gaps and 24px padding within content blocks.
- Employ the Slate Steel (#272727) as a background for secondary interactive components to subtly differentiate them from the main canvas.
- Use Midnight Truffle (#000000) and Ghost White (#fffafa) as the primary colors for borders and strokes to define structural elements.

### Don't
- Avoid using saturated or vibrant colors outside of specific, functional accents (if introduced later) to maintain the dark, industrial aesthetic.
- Do not deviate from the established font families and weights, especially for display typography, as it compromises the strong visual identity.
- Never introduce soft shadows or excessive elevation; the design leans into flat, distinct surfaces and sharp lines.
- Do not use generic padding values; stick to the 8px base unit and derived increments (16px, 24px, 64px) for consistent rhythm.
- Avoid decorative gradients or complex overlays that would detract from the stark, high-contrast visual language.
- Do not use small, light-weight typography for headings; ensure headings are always bold and impactful, using Review or Review Condensed.
- Do not use rounded corners larger than 16px on cards or main components, with the exception of specific decorative elements like the 48px or 100% radius examples.

## Imagery

This design system primarily uses dark, moody abstract 3D renders and illustrative graphics embedded as backgrounds or within masked shapes. These visuals serve an atmospheric and conceptual role rather than directly showcasing products or people. When present, product-type imagery is tightly contained or stylized into geometric shapes. Icons are typically monolinear, white or transparent on dark, with moderate stroke weights. The overall density of imagery is balanced, providing visual interest without overwhelming the stark UI elements, and often creating a tunneling or portal-like effect.

## Layout

The page embraces a full-bleed layout for its hero and main sections, with content often centered within the dark canvas. The hero features a large, centered headline over an immersive abstract background. Section rhythm is primarily defined by consistent vertical spacing (64px) rather than alternating background colors, although subtle variations in dark neutrals exist. Content is frequently arranged in centered stacks or distinct blocks, with visual breaks created by strong typographic statements. Navigation consists of a minimalist sticky header with a hamburger menu for full navigation, and discrete vertical dot navigation along the right edge acting as prominent page anchors.

## Agent Prompt Guide

Quick Color Reference:
text: #fffafa
background: #101010
border: #fffafa
accent: no distinct accent color
primary action: #fffafa (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #fffafa background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Dark Card: background Digital Canvas (#101010), radius 16px. Inside, use Kalice weight 400 at 16px, color Ghost White (#fffafa) for labels, and Review weight 700 at 32px, color Ghost White (#fffafa), letter-spacing 0.64px for a title. Padding 24px inside.
3. Create an Outlined Navigation Item: Background Slate Steel (#272727), text Ghost White (#fffafa), border Ghost White (#fffafa), radius 8px, font Review weight 700 at 14px. No padding at root level; assume parent element handles spacing.

## Similar Brands

- **Alchemy** — Shares a technical, dark mode aesthetic with high-contrast text and geometric layouts, often incorporating abstract background elements.
- **Protocol Labs** — Employs an authoritative dark interface, strong sans-serif typography, and a feeling of advanced, infrastructural technology.
- **Arbitrum** — Features a dark UI with bold, often oversized typography, and a focus on defining elements through borders rather than heavy fills.
- **Filecoin** — Utilizes a dark, technical design with prominent, opinionated typography and a clean yet dense information presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-truffle: #000000;
  --color-digital-canvas: #101010;
  --color-ash-graphite: #1a1a1a;
  --color-slate-steel: #272727;
  --color-ghost-white: #fffafa;
  --color-muted-silver: #bababa;

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kalice: 'Kalice', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-review: 'Review', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-review-condensed: 'Review Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.48px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.1;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-body-lg: 18px;
  --leading-body-lg: 1.1;
  --tracking-body-lg: 0.18px;
  --text-heading: 32px;
  --leading-heading: 0.88;
  --tracking-heading: 0.64px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.8;
  --text-display: 128px;
  --leading-display: 0.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;

  /* Named Radii */
  --radius-links: 2px;
  --radius-buttons: 8px;
  --radius-default: 16px;
  --radius-decorative: 48px;
  --radius-smallcomponents: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-truffle: #000000;
  --color-digital-canvas: #101010;
  --color-ash-graphite: #1a1a1a;
  --color-slate-steel: #272727;
  --color-ghost-white: #fffafa;
  --color-muted-silver: #bababa;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kalice: 'Kalice', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-review: 'Review', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-review-condensed: 'Review Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.48px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.1;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-body-lg: 18px;
  --leading-body-lg: 1.1;
  --tracking-body-lg: 0.18px;
  --text-heading: 32px;
  --leading-heading: 0.88;
  --tracking-heading: 0.64px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.8;
  --text-display: 128px;
  --leading-display: 0.8;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;
}
```
