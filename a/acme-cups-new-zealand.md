# Acme Cups New Zealand — Style Reference
> Monochrome product canvas

**Theme:** light

Acme Cups presents a minimalist, product-focused aesthetic with an emphasis on crisp typography and subtle surface variations. The design system prioritizes a clean, organized presentation where product imagery and strong type take center stage, supported by a restrained monochromatic palette. Components are lightweight with sharp, defined edges, conveying a sense of precision and durability rather than softness or excessive ornamentation. The overall impression is one of quiet confidence, letting the product's form and function speak for themselves.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#000000` | `--color-midnight-charcoal` | Primary text, headers, navigation links, button text, crisp borders for cards and inputs. This deep black provides high contrast and a sense of authority |
| Fog Gray | `#e3e2e2` | `--color-fog-gray` | Subtle surface background for buttons and input fields, creating a soft, tactile interaction element without drawing too much attention. Also used for some secondary borders |
| Silver Mist | `#c3c3c3` | `--color-silver-mist` | Hairline separators, card borders, and ghost button borders. A light gray that defines structure without visual heaviness |
| Barely There White | `#fefefe` | `--color-barely-there-white` | Dominant background for product cards and primary content sections, providing a clean canvas. Used for some headings and badges |
| Muted Stone | `#aeaaaa` | `--color-muted-stone` | Muted helper text, secondary navigation links, and ghost button text, indicating less emphasis or secondary information |
| Ink Wash | `#666666` | `--color-ink-wash` | Badge text, providing a slightly softer contrast than true black for informational labels |
| Rust Orange | `#9b1b01` | `--color-rust-orange` | Input border color to signify an error state, providing a clear visual cue for validation |

## Tokens — Typography

### Helvetica Neue — The sole typeface, delivering a functional and direct tone. Its versatility across weights and sizes supports everything from large, impactful marketing headlines to compact product details. The slightly tighter letter-spacing for larger sizes adds to its refined, modern feel. · `--font-helvetica-neue`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 20px, 21px, 26px, 30px, 48px, 148px
- **Line height:** 1.00, 1.04, 1.15, 1.20, 1.30, 1.40, 1.43
- **Letter spacing:** -0.0090em at 148px, 0.0150em at 12px, 0.0200em at 10px
- **OpenType features:** `"kern" 0, "liga" 0`
- **Role:** The sole typeface, delivering a functional and direct tone. Its versatility across weights and sizes supports everything from large, impactful marketing headlines to compact product details. The slightly tighter letter-spacing for larger sizes adds to its refined, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.2px | `--text-caption` |
| heading-lg | 21px | 1.2 | — | `--text-heading-lg` |
| display-sm | 26px | 1.15 | — | `--text-display-sm` |
| display | 30px | 1.15 | — | `--text-display` |
| display-lg | 48px | 1.04 | -0.43px | `--text-display-lg` |
| display-xl | 148px | 1 | -1.33px | `--text-display-xl` |

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
| 28 | 28px | `--spacing-28` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 72 | 72px | `--spacing-72` |
| 76 | 76px | `--spacing-76` |
| 104 | 104px | `--spacing-104` |
| 120 | 120px | `--spacing-120` |
| 124 | 124px | `--spacing-124` |
| 148 | 148px | `--spacing-148` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 3px |
| images | 3px |
| inputs | 3px |
| buttons | 3px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Ghost Primary Button
**Role:** Outlined button for primary actions or navigation within minimal UIs.

Text: Midnight Charcoal (#000000), Helvetica Neue, 16px, weight 500, lineHeight 1.3. Border: 1px solid Midnight Charcoal (#000000). Background: transparent. Padding: 9px top, 12px right, 5px bottom, 12px left. Radius: 2px. This button style maintains a strong presence through its dark border and text.

### Secondary Filled Button
**Role:** Softly filled button for secondary actions or less prominent calls to action.

Text: Midnight Charcoal (#000000), Helvetica Neue, 16px, weight 500. Background: Fog Gray (#e3e2e2). Border: 1px solid Fog Gray (#e3e2e2). Padding: 9px top, 10px right, 7px bottom, 10px left. Radius: 3px. Its subtle background makes it blend into the UI more, offering a softer visual cue.

### Text Link Button
**Role:** Minimal interactive element, blending into text.

Text: Midnight Charcoal (#000000), Helvetica Neue, 16px, weight 500. Background: transparent. Border: 0px. Padding: 0px. Radius: 0px. Used for navigation or in-line actions where a full button is too heavy.

### Muted Text Button
**Role:** Tertiary action or navigational element, indicating lower hierarchy.

Text: Muted Stone (#aeaaaa), Helvetica Neue, 16px, weight 500. Background: transparent. Border: 0px. Padding: 0px. Radius: 0px. Its lighter color makes it visually recessive, ideal for less critical actions or filters.

### Product Grid Card
**Role:** Container for individual product listings in a grid layout.

Background: Barely There White (#fefefe). Border: 0px. Radius: 0px. No shadows. Padding: 0px. This card is purely functional, designed to showcase product imagery and information without visual distraction, reinforcing the clean, direct aesthetic.

### Search Input Field
**Role:** Text input for search functionality.

Text: Midnight Charcoal (#000000). Background: transparent. Border: 1px solid Midnight Charcoal (#000000). Placeholder: Midnight Charcoal (#000000), lighter opacity implied. Padding: 0px top, 14px right, 0px bottom, 0px left. Radius: 0px. A crisp, minimalist input that integrates smoothly into the headers.

### Standard Input Field
**Role:** General text input field with a softer background.

Text: Midnight Charcoal (#000000). Background: Fog Gray (#e3e2e2). Border: 1px solid Midnight Charcoal (#000000). Padding: 12px top, 12px right, 8px bottom, 12px left. Radius: 3px. Offers a slightly more prominent visual affordance than the search input, used for form elements.

### Informational Badge
**Role:** Small descriptive labels or tags.

Text: Ink Wash (#666666), Helvetica Neue, 12px. Background: transparent. Border: 1px solid Silver Mist (#c3c3c3). Padding: 3px top, 2px right, 0px bottom, 2px left. Radius: 3px. Provides unobtrusive categorization or metadata.

## Do's and Don'ts

### Do
- Prioritize Helvetica Neue for all text elements to maintain a consistent, functional voice.
- Use Midnight Charcoal (#000000) for all primary text and headers to ensure maximal contrast and legibility.
- Define clear boundaries with 1px solid Midnight Charcoal (#000000) or Silver Mist (#c3c3c3) for interactive elements and structural divisions.
- Employ Barely There White (#fefefe) as the default background for most content areas and product cards.
- Apply a 3px border-radius consistently to all buttons, badges, and smaller interactive elements to introduce a subtle touch of softness.
- Maintain a compact density, using 8px as a common `elementGap` for horizontal and vertical spacing between components and text blocks.
- Use Fog Gray (#e3e2e2) for backgrounds of secondary buttons and input fields to differentiate them without introducing strong colors.

### Don't
- Do not introduce new typefaces; rely solely on Helvetica Neue.
- Avoid decorative shadows or excessive gradients; keep surfaces flat and defined by borders.
- Do not use saturated colors for UI elements other than semantic cues like error states.
- Do not vary border-radius arbitrarily; stick to 3px for interactive elements and 0px for larger containers like product cards.
- Do not use large, expansive spacing; maintain a sense of compactness and efficiency between elements.
- Do not introduce heavy background imagery or textures behind primary content; keep backgrounds clean and monochromatic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#c3c3c3` | Broad background for the entire page, setting a neutral and understated tone. |
| 1 | Card Surface | `#fefefe` | Primary background for product cards and sections where content is highlighted against the page canvas. |
| 2 | Interactive Surface | `#e3e2e2` | Background for secondary buttons and input fields, providing slight elevation and interaction affordance. |

## Imagery

This design system uses a combination of high-quality product photography and minimal iconography. Photography features tight crops of products, often against neutral or subtly textured backgrounds, emphasizing detail and material. These images can be full-bleed in hero sections (as seen in the homepage header) or contained within a grid for product listings. There is no overt lifestyle photography, keeping the focus entirely on the product itself. Icons are minimal, outlined, and monochromatic (using Midnight Charcoal), serving a purely functional role with a consistent stroke weight. Imagery primarily showcases the product and provides explanatory content within a clean UI.

## Layout

The site employs a contained layout with some full-bleed hero sections. The `pageMaxWidth` appears to be fluid, allowing content to stretch across the viewport but is internally structured to maximum readable width for text columns. The hero section often combines a full-bleed, dark-themed image with centered, stark white typography. Subsequent sections typically follow a grid-based arrangement for product displays, often 4-column, or a two-column text-left/image-right pattern. Vertical rhythm is consistent, with distinct but not overly spacious gaps between content blocks. Navigation is a compact, top-bar sticky header with clear text links.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #c3c3c3
- border: #000000
- accent: no distinct accent color
- primary action: #000000 (filled action)

Example Component Prompts:
- Create a product listing card: Barely There White background (#fefefe), no border, 0px radius, 0px padding. Product title in Midnight Charcoal (#000000), Helvetica Neue, 16px, weight 500. Price in Midnight Charcoal (#000000), Helvetica Neue, 14px, weight 400. Include a 'Add to Cart' Secondary Filled Button.
- Create a Primary Action Button: #000000 background, #e3e2e2 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a hero section with a centered headline: Full-bleed image background (replace with placeholder 16:9 dark image). Headline 'Born from a long-standing ambition' in Barely There White (#fefefe), Helvetica Neue, 48px, weight 700, letter-spacing -0.43px. Subtext 'create products that seamlessly blend form and function.' in Barely There White (#fefefe), Helvetica Neue, 20px, weight 400.
- Create an input field for a form: Background Fog Gray (#e3e2e2), 1px solid Midnight Charcoal (#000000) border, 3px radius. Text Midnight Charcoal (#000000), Helvetica Neue, 15px. Padding: 12px top, 12px right, 8px bottom, 12px left.

## Similar Brands

- **Aēsop** — Monochromatic palette, emphasis on typography, precise layouts, and product-focused imagery without lifestyle elements underscore a functional elegance. Often uses stark contrasts and minimal design elements.
- **MUJI** — Clean, functional design with a minimalist aesthetic, restrained use of color, and focus on product utility. Type is often simple and direct, contributing to an understated brand identity.
- **Stelton** — Danish design brand known for simple, functional products. Visuals are clean, product photography is often isolated, and the UI design supports direct product presentation through a pared-back aesthetic.
- **Arket** — Clean, almost entirely monochromatic UI, strong typographic hierarchy, and a focus on product visuals. The overall feel is one of thoughtful simplicity and directness.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #000000;
  --color-fog-gray: #e3e2e2;
  --color-silver-mist: #c3c3c3;
  --color-barely-there-white: #fefefe;
  --color-muted-stone: #aeaaaa;
  --color-ink-wash: #666666;
  --color-rust-orange: #9b1b01;

  /* Typography — Font Families */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.2px;
  --text-heading-lg: 21px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 26px;
  --leading-display-sm: 1.15;
  --text-display: 30px;
  --leading-display: 1.15;
  --text-display-lg: 48px;
  --leading-display-lg: 1.04;
  --tracking-display-lg: -0.43px;
  --text-display-xl: 148px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.33px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-76: 76px;
  --spacing-104: 104px;
  --spacing-120: 120px;
  --spacing-124: 124px;
  --spacing-148: 148px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 3px;
  --radius-images: 3px;
  --radius-inputs: 3px;
  --radius-buttons: 3px;

  /* Surfaces */
  --surface-page-canvas: #c3c3c3;
  --surface-card-surface: #fefefe;
  --surface-interactive-surface: #e3e2e2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #000000;
  --color-fog-gray: #e3e2e2;
  --color-silver-mist: #c3c3c3;
  --color-barely-there-white: #fefefe;
  --color-muted-stone: #aeaaaa;
  --color-ink-wash: #666666;
  --color-rust-orange: #9b1b01;

  /* Typography */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.2px;
  --text-heading-lg: 21px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 26px;
  --leading-display-sm: 1.15;
  --text-display: 30px;
  --leading-display: 1.15;
  --text-display-lg: 48px;
  --leading-display-lg: 1.04;
  --tracking-display-lg: -0.43px;
  --text-display-xl: 148px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.33px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-76: 76px;
  --spacing-104: 104px;
  --spacing-120: 120px;
  --spacing-124: 124px;
  --spacing-148: 148px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 3px;
}
```
