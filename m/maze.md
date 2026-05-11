# Maze — Style Reference
> Whiteboard clarity, green highlight

**Theme:** light

Maze implements a focused, professional workspace aesthetic with a predominantly achromatic palette, accented sparingly by a vivid lime green and a forest green. Large, confident typography provides strong hierarchy against a light, airy canvas. Components are lightweight with subtle card treatments and soft rounded corners, emphasizing content clarity and swift interaction without heavy ornamentation. The overall layout balances information density with generous breathing room, creating an experience that feels both powerful and approachable.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#f5f4f0` | `--color-canvas` | Page backgrounds, subtle card backgrounds, footer background – provides a soft, warm white base |
| Surface White | `#ffffff` | `--color-surface-white` | Card backgrounds, elevated UI elements, input fills – maintains a crisp white surface for content |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong headings, button text, icon default color – ensures high contrast and legibility |
| Granite Text | `#1c1c1c` | `--color-granite-text` | Body text, secondary headings, darker button backgrounds – provides a slightly softer dark tone than pure black |
| Stone Gray Border | `#d2cec6` | `--color-stone-gray-border` | Hairline borders, subtle dividers, footer borders – provides definition without visual weight |
| Ash Button | `#eae6e1` | `--color-ash-button` | Hover states for backgrounds, subtle button fills – creates a soft, almost imperceptible interaction feedback |
| Muted Text Gray | `#706f6c` | `--color-muted-text-gray` | Muted body text, helper text, subtle outlines – for less prominent information |
| Slate Input Border | `#9e9b94` | `--color-slate-input-border` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Forest Green | `#4b5b0a` | `--color-forest-green` | Brand accent, link hover states, decorative elements – provides a natural, authoritative pop against neutrals |
| Lime Highlight | `#dbf570` | `--color-lime-highlight` | Badge backgrounds, card highlights – a vivid and energetic accent that draws immediate attention |

## Tokens — Typography

### Phonic — Headings and key callouts. The light weights (300) combined with expansive letter spacing on larger sizes create a sense of modern confidence and space. The wider tracking on smaller sizes is an unusual but intentional choice to maintain visual airiness. · `--font-phonic`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400
- **Sizes:** 12px, 14px, 15px, 17px, 22px, 28px, 46px, 58px, 90px, 130px
- **Line height:** 1.00, 1.05, 1.10, 1.15, 1.30, 1.40, 1.41
- **Letter spacing:** -0.0900em at 130px, -0.0700em at 90px, -0.0600em at 58px, -0.0500em at 46px, -0.0400em at 28px, -0.0300em at 22px, -0.0200em at 17px, -0.0100em at 15px, 0.0300em at 12px
- **Role:** Headings and key callouts. The light weights (300) combined with expansive letter spacing on larger sizes create a sense of modern confidence and space. The wider tracking on smaller sizes is an unusual but intentional choice to maintain visual airiness.

### ui-sans-serif — Body text, navigation, and all functional UI labels. It serves as a neutral, highly legible counterpart to the expressive Phonic headings. · `--font-ui-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Body text, navigation, and all functional UI labels. It serves as a neutral, highly legible counterpart to the expressive Phonic headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.36px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.28px | `--text-body-sm` |
| heading-sm | 22px | 1.15 | -0.66px | `--text-heading-sm` |
| heading | 28px | 1.1 | -1.12px | `--text-heading` |
| heading-lg | 46px | 1.05 | -2.3px | `--text-heading-lg` |
| display | 58px | 1.05 | -3.48px | `--text-display` |
| display-lg | 90px | 1 | -6.3px | `--text-display-lg` |
| display-xl | 130px | 1 | -11.7px | `--text-display-xl` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| round | 1.67772e+07px |
| badges | 4px |
| inputs | 8px |
| buttons | 8px |

### Layout

- **Section gap:** 48-64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Dark Button
**Role:** Call-to-action button for primary actions.

Text: Surface White (#ffffff), Background: Granite Text (#1c1c1c), Border: none. Padding: 12px vertical, 16px horizontal. Border Radius: 8px. Text: ui-sans-serif 16px, weight 400.

### Outline Ghost Button
**Role:** Secondary call-to-action or navigational options.

Text: Ink Black (#000000), Background: transparent. Border: 1px Ink Black (#000000). Padding: 12px vertical, 16px horizontal. Border Radius: 8px. Text: ui-sans-serif 16px, weight 400.

### Pill Ghost Button
**Role:** Small, less prominent actions or filters.

Text: Granite Text (#1c1c1c), Background: transparent. Border: 1px Forest Green (#4b5b0a) for hover/active, transparent otherwise. Padding: 8px vertical, 16px horizontal. Border Radius: 1.67772e+07px (pill shape). Text: ui-sans-serif 16px, weight 400.

### Default Card
**Role:** Content containers for features, data, or product previews.

Background: Surface White (#ffffff), Shadow: none (flat). Padding: 16px. Border Radius: 12px.

### Hero Card
**Role:** Prominent display cards for key product features or testimonials.

Background: Surface White (#ffffff), Shadow: none (flat). Padding: 40px vertical, 0px horizontal. Border Radius: 16px. Used for full-width content sections.

### Input Field
**Role:** User input elements.

Background: Surface White (#ffffff), Text: Granite Text (#1c1c1c). Border: 1px Slate Input Border (#9e9b94). Padding: 0px vertical, 8px horizontal. Border Radius: 8px. Text: ui-sans-serif 16px, weight 400. Placeholder text is Muted Text Gray (#706f6c).

### Lime Badge
**Role:** Small informational labels, typically for 'New' features.

Background: Lime Highlight (#dbf570), Text: Granite Text (#1c1c1c). Padding: 1px vertical, 4px horizontal. Border Radius: 4px. Text: Phonic 12px, weight 400.

### Dark Top Banner
**Role:** Promotional banner across the top of the page.

Background: Ink Black (#000000), Text: Surface White (#ffffff). Padding: 8px vertical, 16px horizontal (implied). Text: ui-sans-serif 16px, weight 400. Contains a Forest Green (#4b5b0a) link.

## Do's and Don'ts

### Do
- Use Canvas (#f5f4f0) as the primary page background for all sections, providing a warm, neutral base.
- Apply Phonic font with its light weights (300, 400) and specific letter-spacing variations for all headings to create an expansive, modern feel.
- Maintain a clear functional hierarchy for buttons using Primary Dark Button for main actions and Outline Ghost Button for secondary actions.
- Implement an 8px border radius consistently across all buttons, input fields, and most cards, establishing a soft, approachable feel.
- Utilize Forest Green (#4b5b0a) sparingly, primarily for functional links and subtle decorative strokes, to act as a focused brand accent.
- Employ Lime Highlight (#dbf570) exclusively for small, vivid elements like badges or critical highlights, ensuring its impact is maximized.
- Use Ink Black (#000000) for all primary, high-contrast text elements, especially navigation and call-to-action labels.

### Don't
- Do not introduce new saturated primary colors; adhere to the existing Forest Green (#4b5b0a) and Lime Highlight (#dbf570) as the only chromatic accents.
- Avoid heavy shadows or gradients on UI components; maintain the flat, clean aesthetic with minimal elevation.
- Do not use letter-spacing on ui-sans-serif text sizes; it should remain normal unless explicitly specified on Phonic headings.
- Do not deviate from the established 8px border radius for interactive elements and cards; inconsistent rounding will break the visual cohesion.
- Do not use dark backgrounds for main content sections; the system is built on a light canvas with dark text for optimal readability.
- Avoid overly dense layouts; maintain comfortable element (8px) and card (16px) padding, and generous section spacing (48-64px) to preserve visual breathing room.
- Do not use full-width background colors that are saturated or stark; stick to the Canvas (#f5f4f0) and Surface White (#ffffff) for large background areas.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f5f4f0
border: #d2cec6
accent: #dbf570
primary action: #1c1c1c (filled action)

Example Component Prompts:
1. Create a Primary Dark Button: Background #1c1c1c, text #ffffff. Text: ui-sans-serif 16px weight 400. Padding: 12px vertical, 16px horizontal. Border radius: 8px.
2. Design a Default Card: Background #ffffff, border none, shadow none. Padding: 16px. Border radius: 12px. Contain an h3 heading Phonic 28px weight 300, #000000, letter-spacing -1.12px.
3. Create a Primary Action Button: #1c1c1c background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Generate a Lime Badge: Background #dbf570, text #1c1c1c. Text: Phonic 12px weight 400. Padding: 1px vertical, 4px horizontal. Border radius: 4px.

## Similar Brands

- **Figma** — Shares a light, spacious UI with strong but minimal typography and clear component separation, using a single dominant accent color against mostly neutrals.
- **Vercel** — Features a strong focus on high-contrast text hierarchies, a light and dark theme (though this is primarily light), and clean, unembellished UI elements.
- **Linear** — Exhibits a similar commitment to an achromatic palette with a precise use of typography for visual hierarchy and subtle card-based interfaces, prioritizing function over heavy adornment.
- **Stripe** — Employs an extensive use of white space, a clean sans-serif typeface, and minimal color accents to present complex information in an approachable, professional manner.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #f5f4f0;
  --color-surface-white: #ffffff;
  --color-ink-black: #000000;
  --color-granite-text: #1c1c1c;
  --color-stone-gray-border: #d2cec6;
  --color-ash-button: #eae6e1;
  --color-muted-text-gray: #706f6c;
  --color-slate-input-border: #9e9b94;
  --color-forest-green: #4b5b0a;
  --color-lime-highlight: #dbf570;

  /* Typography — Font Families */
  --font-phonic: 'Phonic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.66px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -1.12px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -2.3px;
  --text-display: 58px;
  --leading-display: 1.05;
  --tracking-display: -3.48px;
  --text-display-lg: 90px;
  --leading-display-lg: 1;
  --tracking-display-lg: -6.3px;
  --text-display-xl: 130px;
  --leading-display-xl: 1;
  --tracking-display-xl: -11.7px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-120: 120px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 48-64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-round: 1.67772e+07px;
  --radius-badges: 4px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #f5f4f0;
  --color-surface-white: #ffffff;
  --color-ink-black: #000000;
  --color-granite-text: #1c1c1c;
  --color-stone-gray-border: #d2cec6;
  --color-ash-button: #eae6e1;
  --color-muted-text-gray: #706f6c;
  --color-slate-input-border: #9e9b94;
  --color-forest-green: #4b5b0a;
  --color-lime-highlight: #dbf570;

  /* Typography */
  --font-phonic: 'Phonic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.66px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -1.12px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -2.3px;
  --text-display: 58px;
  --leading-display: 1.05;
  --tracking-display: -3.48px;
  --text-display-lg: 90px;
  --leading-display-lg: 1;
  --tracking-display-lg: -6.3px;
  --text-display-xl: 130px;
  --leading-display-xl: 1;
  --tracking-display-xl: -11.7px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-120: 120px;
  --spacing-208: 208px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
}
```
