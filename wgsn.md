# WGSN — Style Reference
> High-contrast monochrome canvas.

**Theme:** light

WGSN's visual system evokes a precise, authoritative environment through high-contrast typography and a stark monochrome palette. Information is presented on a clean white canvas, punctuated by dark, almost black, interactive elements. The design prioritizes clear communication and efficient navigation, using compact components and minimal decorative flourishes. Large, impactful headlines command attention, while subtle gray text provides supporting details, establishing a clear visual hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default text color for dark components |
| Ink Black | `#000000` | `--color-ink-black` | Primary headline text, key interface elements on white backgrounds, section backgrounds, accent for focus states |
| Graphite | `#333333` | `--color-graphite` | Secondary text, link text, borders for dark ghost buttons |
| Steel Gray | `#666666` | `--color-steel-gray` | Muted body text, subtle borders, inactive elements |
| Ash Gray | `#999999` | `--color-ash-gray` | Placeholder text, very subtle borders, decorative lines |
| Fog Gray | `#f5f5f5` | `--color-fog-gray` | Subtle background for card surfaces and input fields, creating soft visual separation |
| Divider Gray | `#cccccc` | `--color-divider-gray` | Hairline separators and subtle outlines |
| Input Text Gray | `#495057` | `--color-input-text-gray` | Text color specifically for input fields |
| Button Solid Black | `#212121` | `--color-button-solid-black` | Primary button background, active navigation backgrounds — an almost-black that offers better contrast than pure black against white text |

## Tokens — Typography

### DM Sans — The sole typeface, used across all elements from headlines to body text. Its clean, geometric sans-serif nature underpins the system's precise and direct communication style. Varied letter-spacing tightens tracking for larger display text and loosens it slightly for smaller body text, enhancing legibility at different scales. · `--font-dm-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 17px, 18px, 20px, 24px, 28px, 32px, 36px, 40px, 48px, 92px
- **Line height:** 0.79, 1.10, 1.17, 1.18, 1.20, 1.33, 1.50, 1.60, 1.90
- **Letter spacing:** -0.0110em at larger sizes (e.g. 92px), 0.0560em at smaller sizes (e.g. 12px)
- **Role:** The sole typeface, used across all elements from headlines to body text. Its clean, geometric sans-serif nature underpins the system's precise and direct communication style. Varied letter-spacing tightens tracking for larger display text and loosens it slightly for smaller body text, enhancing legibility at different scales.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 14px | 1.6 | 0.784px | `--text-body-lg` |
| heading-sm | 18px | 1.6 | -0.198px | `--text-heading-sm` |
| heading | 20px | 1.6 | -0.22px | `--text-heading` |
| heading-lg | 24px | 1.5 | -0.264px | `--text-heading-lg` |
| display-sm | 32px | 1.33 | -0.352px | `--text-display-sm` |
| display | 48px | 1.18 | -0.528px | `--text-display` |
| display-lg | 92px | 0.79 | -1.012px | `--text-display-lg` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 8px |
| buttons | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(0, 0, 0) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1370px
- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 18px

## Components

### Primary Filled Button
**Role:** Call-to-action button for initiating key actions.

Filled with Button Solid Black (#212121), white text (Canvas White, #ffffff). Uses a highly rounded (40px) border-radius for a distinct visual. Padding is 12px top, 22px right, 11px bottom, 22px left.

### Outlined Light Button
**Role:** Secondary action button on dark backgrounds.

Transparent background, white text (Canvas White, #ffffff), outlined with Canvas White (#ffffff). Inherits the 40px border-radius and 12px top, 22px right, 11px bottom, 22px left padding of other buttons.

### Outlined Dark Button
**Role:** Secondary action button on light backgrounds.

Transparent background, text in Graphite (#333333), outlined with Ink Black (#000000). Also uses 40px border-radius and 12px top, 22px right, 11px bottom, 22px left padding.

### Standard Card
**Role:** Container for content sections, often with imagery.

Transparent background with a 0px border-radius by default, or Fog Gray (#f5f5f5) background with 16px border-radius where elevation is implied. No box-shadows are used. Padding is internal to content blocks, not on the card itself (0px total).

### Feature Card
**Role:** Prominent content card, often with an associated image.

White background (Canvas White, #ffffff) and a 16px border-radius. No box-shadow. Padding is internal to content blocks (0px on the card itself), emphasizing the content within.

### Primary Input Field
**Role:** Standard editable text input.

Background is Fog Gray (#f5f5f5), text color is Input Text Gray (#495057). Has a distinct 8px border-radius. Padding is 13px all around, with the border color matching the background, indicating an inset style rather than an explicit border.

### Dark Overlay Input
**Role:** Input field designed for dark backgrounds.

Transparent background with white text (Canvas White, #ffffff). Has a 0px border-radius, relying on an Ink Black (#000000) border bottom for definition. Padding is 4px top, 12px right, 4px bottom, 0px left.

### Headline Badge
**Role:** Small, descriptive text element above headlines.

Transparent background with muted white text (Canvas White, #ffffff at 70% opacity). Minimal styling with 0px border-radius and no padding, designed to sit unobtrusively.

## Do's and Don'ts

### Do
- Use DM Sans exclusively for all typography, leveraging its weights and responsive letter-spacing for hierarchy.
- Maintain high contrast ratios for text and interactive elements. Against Canvas White (#ffffff), use Ink Black (#000000) or Button Solid Black (#212121).
- Apply a 40px border-radius to all interactive buttons and navigation elements for a consistent soft pill-shape.
- Utilize Fog Gray (#f5f5f5) sparingly for subtle surface distinction on cards and input fields, never for primary background.
- Ensure section gaps between content blocks are consistent, defaulting to elementGap (18px) or sectionGap (32px) for major divisions.
- Use Steel Gray (#666666) for secondary informational text, not for primary content or interactive labels.
- Adopt the maximum page width of 1370px for all main content, centered on the screen.

### Don't
- Avoid using box-shadows for elevation; rely on background color changes or subtle borders for visual layering.
- Do not introduce new colors; adhere strictly to the monochrome palette with its specific gray values.
- Do not deviate from the defined border-radii; 40px for buttons, 16px for cards, and 8px for inputs are fixed values.
- Avoid decorative gradients; the system is flat and high-contrast.
- Do not use highly saturated brand colors. The visual system does not rely on typical chromatic accents.
- Do not use overly dense text blocks without appropriate contrast; prioritize readability with varied text weights and colors.
- Avoid complex overlapping elements; maintain a clean, organized, and explicit separation of components.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base for content. |
| 1 | Fog Gray | `#f5f5f5` | Secondary background for cards and input fields, providing slight visual depth without shadows. |
| 2 | Ink Black | `#000000` | Hero sections, footers or prominent callout blocks, acting as a high-contrast anchor. |

## Imagery

Imagery consists primarily of tight product crops, lifestyle photography, and abstract studio shots, often presented without strong visual effects. Photography is contained within cards or grids, rarely full-bleed, emphasizing the product or a specific detail. There are no consistent illustration styles, implying a focus on real-world examples and sophisticated UI. Icons are typically solid, monochromatic, with a moderate stroke weight, serving functional roles rather than decorative ones. The density is moderate, allowing space for text, with imagery mainly serving to contextualize content.

## Layout

The page adheres to a max-width of 1370px, centered on the screen. The hero section is characterized by a full-bleed dark background (Ink Black) with a prominent centered headline, framed by images for visual interest. Content sections alternate between the primary Canvas White and the slightly distinct Fog Gray backgrounds, creating a clear vertical rhythm. Content is generally arranged in two-column text-left/image-right or centered stacks. Feature sections often employ a multi-column card grid. The navigation is a sticky top bar, providing persistent access to key links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #666666
accent: no distinct accent color
primary action: #212121 (filled action)

Example Component Prompts:
Create a Primary Action Button: #212121 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a feature card: Fog Gray (#f5f5f5) background, 16px radius. Heading at 24px DM Sans weight 700 (#000000). Body text at 14px DM Sans weight 400, Steel Gray (#666666). A link using Ink Black (#000000) with a subtle Ink Black (#000000) inset border on hover.
Create a modal button group for a cookie consent banner: two buttons side-by-side. 'Accept all' button: Button Solid Black (#212121) background, Canvas White (#ffffff) text, 40px radius. 'Reject all' button: transparent background, Graphite (#333333) text, Ink Black (#000000) border, 40px radius. Both with 12px top, 22px right, 11px bottom, 22px left padding.
Create an input field: Background Fog Gray (#f5f5f5), text Input Text Gray (#495057), 8px radius. Padding: 13px all sides. Border color matches background. Placeholder text Ash Gray (#999999).
Create a header navigation link: text Graphite (#333333), DM Sans weight 500, size 16px, transparent background.

## Similar Brands

- **Figma** — Monochromatic interface with strict color hierarchy and focus on clear typography for tool presentation.
- **Stripe** — Clean, high-contrast aesthetic with abundant white space and a deliberate use of blacks and grays to convey sophistication.
- **Linear** — Minimalist dark/light mode interface with strong emphasis on typography and functional, compact components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #333333;
  --color-steel-gray: #666666;
  --color-ash-gray: #999999;
  --color-fog-gray: #f5f5f5;
  --color-divider-gray: #cccccc;
  --color-input-text-gray: #495057;
  --color-button-solid-black: #212121;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: 0.784px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.6;
  --tracking-heading-sm: -0.198px;
  --text-heading: 20px;
  --leading-heading: 1.6;
  --tracking-heading: -0.22px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.5;
  --tracking-heading-lg: -0.264px;
  --text-display-sm: 32px;
  --leading-display-sm: 1.33;
  --tracking-display-sm: -0.352px;
  --text-display: 48px;
  --leading-display: 1.18;
  --tracking-display: -0.528px;
  --text-display-lg: 92px;
  --leading-display-lg: 0.79;
  --tracking-display-lg: -1.012px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1370px;
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 18px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 8px;
  --radius-buttons: 40px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-fog-gray: #f5f5f5;
  --surface-ink-black: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #333333;
  --color-steel-gray: #666666;
  --color-ash-gray: #999999;
  --color-fog-gray: #f5f5f5;
  --color-divider-gray: #cccccc;
  --color-input-text-gray: #495057;
  --color-button-solid-black: #212121;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: 0.784px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.6;
  --tracking-heading-sm: -0.198px;
  --text-heading: 20px;
  --leading-heading: 1.6;
  --tracking-heading: -0.22px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.5;
  --tracking-heading-lg: -0.264px;
  --text-display-sm: 32px;
  --leading-display-sm: 1.33;
  --tracking-display-sm: -0.352px;
  --text-display: 48px;
  --leading-display: 1.18;
  --tracking-display: -0.528px;
  --text-display-lg: 92px;
  --leading-display-lg: 0.79;
  --tracking-display-lg: -1.012px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 0px 0px 0px 1px inset;
}
```
