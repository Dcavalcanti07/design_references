# HOUSEPLANT — Style Reference
> Artisanal Collector's Canvas

**Theme:** light

HOUSEPLANT's visual system evokes a collectible-driven, high-end artisanal aesthetic. It features a stark contrast between a dominant, warm off-white canvas and deep, earthy neutrals, lending a sophisticated yet grounded feel. Typography is paramount, leveraging a distinctive custom serif for headlines and strong sans-serifs for body text, creating an almost editorial quality. Components are minimal, often borderless or with subtle shadows, allowing the rich product imagery and bold type to command attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#f4f1e0` | `--color-canvas-parchment` | Page background, card surfaces, prominent content areas – a warm, aged white that feels tactile and refined |
| Houseplant Deep Bark | `#321e1e` | `--color-houseplant-deep-bark` | Primary text, filled button backgrounds, critical borders – a very dark, earthy brown that provides strong contrast and a sense of luxury |
| Text Carbon | `#464545` | `--color-text-carbon` | Secondary text, subtle borders, inactive link states – a deep gray for supportive information |
| Surface Shadow | `#bdb498` | `--color-surface-shadow` | Decorative borders, divider lines, subtle background texture – a muted, desaturated tan that adds depth without competing |
| Button Shadow | `#463938` | `--color-button-shadow` | Background for certain content blocks where a softer dark tone is desired, distinct from Deep Bark |
| Pure Black | `#000000` | `--color-pure-black` | Iconography, strong accents, button borders where maximum visual impact is required |
| Pure White Text | `#f4f4f4` | `--color-pure-white-text` | Text on dark backgrounds, active link states in navigation – a crisp white for contrast |

## Tokens — Typography

### Houseplant — Brand headlines, product titles, and key calls-to-action – its unique character defines the brand's sophisticated, bespoke feel. The negative letter-spacing contributes to its tightly-knit, impactful presence. · `--font-houseplant`
- **Substitute:** Playfair Display
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 20px, 21px, 28px, 30px, 32px, 45px, 60px, 70px
- **Line height:** 1.00, 1.15, 1.30, 1.33, 1.44, 1.71, 2.50, 2.79
- **Letter spacing:** -0.020em to -0.050em
- **Role:** Brand headlines, product titles, and key calls-to-action – its unique character defines the brand's sophisticated, bespoke feel. The negative letter-spacing contributes to its tightly-knit, impactful presence.

### Roboto — Fallback text for browser consistency and general UI elements where a neutral, highly readable sans-serif is needed. · `--font-roboto`
- **Substitute:** Roboto
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 2.00
- **Letter spacing:** normal
- **Role:** Fallback text for browser consistency and general UI elements where a neutral, highly readable sans-serif is needed.

### NeueHelvetica55Roman — Body text and descriptive content for clarity and legibility, providing a modern, clean counterbalance to the custom serif. · `--font-neuehelvetica55roman`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.15, 1.63
- **Letter spacing:** normal
- **Role:** Body text and descriptive content for clarity and legibility, providing a modern, clean counterbalance to the custom serif.

### GTStandard-M — Used for specific auxiliary text, possibly emphasizing a structured or informational tone. · `--font-gtstandard-m`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used for specific auxiliary text, possibly emphasizing a structured or informational tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.71 | -0.021px | `--text-body-sm` |
| body | 16px | 1.63 | -0.021px | `--text-body` |
| subheading | 18px | 1.44 | -0.021px | `--text-subheading` |
| heading-sm | 20px | 1.33 | -0.02px | `--text-heading-sm` |
| heading | 28px | 1.3 | -0.02px | `--text-heading` |
| heading-lg | 32px | 1.3 | -0.02px | `--text-heading-lg` |
| display-sm | 45px | 1.15 | -0.047px | `--text-display-sm` |
| display | 60px | 1 | -0.05px | `--text-display` |
| display-lg | 70px | 1 | -0.047px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| buttons | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.1) 0px 2px 8px 0px` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.15) 0px 2px 8px 0px` | `--shadow-sm-2` |

### Layout

- **Card padding:** 0px
- **Element gap:** 20px

## Components

### Filled Brand Button
**Role:** Primary call to action.

Background: Houseplant Deep Bark (#321e1e), Text: Canvas Parchment (#f4f1e0). Padding: 12px vertical, 20px horizontal. Border radius: 4px. Features a subtle bottom border in Canvas Parchment.

### Circular Icon Button
**Role:** Utility actions like cart or user profile.

Background: Pure White Text (#ffffff), Text: Pure Black (#000000). Padding: 1px vertical, 6px horizontal. Border radius: 50% (circular). Border: 1px solid Pure Black.

### Ghost Header Navigation Link
**Role:** Top-level navigation items.

Background: Transparent. Text: Pure White Text (#f4f4f4). No explicit padding or border radius. Underlined on hover or active state using Pure White Text.

### Ghost Footer Nav Link
**Role:** Footer navigation and secondary links.

Background: Transparent. Text: Text Carbon (#464545). No explicit padding or border radius. Minimalist, relying on surrounding layout for hierarchy.

### Shop Now Button (Product Card)
**Role:** Secondary action within product cards.

Background: Houseplant Deep Bark (#321e1e), Text: Canvas Parchment (#f4f1e0). Padding: 0px vertical, 30px horizontal. Border radius: 0px. Used within constrained areas, often at the bottom of a card.

### Elevated Product Card
**Role:** Displaying product items with subtle depth.

Background: Canvas Parchment (#f4f1e0). Border radius: 8px. Box shadow: rgba(0, 0, 0, 0.1) 0px 2px 8px 0px. No internal padding, allowing content to stretch to edges.

### Horizontal Divider
**Role:** Separating content blocks or list items.

1px solid Surface Shadow (#bdb498).

### Minimal Badge
**Role:** Informational labels.

Transparent background. Text: Text Carbon (#464545). No specific border radius or padding, blending into surrounding text.

### Outlined CTA Button (Dark Background)
**Role:** Secondary call to action on dark backgrounds.

Transparent background. Text: Pure White Text (#f4f4f4). Border: 1px solid Pure White Text. Padding: 12px vertical, 20px horizontal. Border radius: 4px.

## Do's and Don'ts

### Do
- Prioritize Canvas Parchment (#f4f1e0) as the dominant background for light sections to maintain the warm, aged base.
- Use Houseplant Deep Bark (#321e1e) for primary text and critical interactive elements, ensuring strong contrast.
- Apply the Houseplant typeface with negative letter-spacing for all primary headings and product names to emphasize brand identity.
- Utilize a border-radius of 4px for interactive buttons and 8px for prominent cards to provide consistent component shaping.
- Employ subtle box shadows (rgba(0, 0, 0, 0.1) 0px 2px 8px 0px) for cards and buttons for gentle elevation, avoiding harsh overlays.
- Maintain a comfortable element gap of 20px between distinct UI components for visual breathing room.
- Contrast Houseplant Deep Bark (#321e1e) against Canvas Parchment (#f4f1e0) for optimal readability and brand impact in text.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; color should predominantly come from product imagery or small accents.
- Do not introduce sharp, angular shapes or radii beyond the defined 4px and 8px, as this deviates from the soft, artisanal feel.
- Refrain from heavy, multi-layered shadows; elevation should be minimal and understated.
- Do not use generic system fonts for headlines or prominent text; the custom Houseplant typeface is essential to brand identity.
- Avoid dense, tightly packed layouts; the design system values comfortable spacing and a focused presentation.
- Do not use highly reflective or glossy textures; the aesthetic leans towards matte, tactile surfaces.
- Do not dilute the contrast between text and background with mid-tone grays; rely on the established dark neutrals on light backgrounds.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Parchment | `#f4f1e0` | Dominant page background, providing a warm, inviting base for content. |
| 1 | Elevated Card Surface | `#f4f1e0` | Used for product cards and informational panels, providing slight elevation with a subtle shadow. |
| 2 | Content Block Dark | `#463938` | Background for specific feature sections or calls to action, providing a deep, grounding contrast. |
| 3 | Button Dark Fill | `#321e1` | Background for primary interactive elements, offering the strongest dark tone in the palette. |

## Elevation

- **card:** `rgba(0, 0, 0, 0.1) 0px 2px 8px 0px`
- **button:** `rgba(0, 0, 0, 0.15) 0px 2px 8px 0px`

## Imagery

Imagery primarily consists of tight product photography or styled product shots, often isolated on neutral backgrounds or within artistic, curated settings. Photography is high-key with soft lighting, minimizing harsh shadows, and focusing on the material and form of the objects. Illustrations (as seen in the 'Italian Collection' hero) are geometric, bold, and utilize brand colors to create impactful, graphic patterns rather than detailed scenes. Icons are minimal, outlined, and monochromatic, primarily serving functional roles. The visual system is image-heavy, showcasing the products as the hero, balancing aesthetic appeal with clear product visibility.

## Layout

The page uses a maximum-width contained layout rather than full-bleed, with content centered. The hero section often features a split-layout with bold graphic elements or photography on one side and a prominent headline with a call to action on the other, sometimes against a full-width background. Sections maintain a consistent vertical rhythm, primarily defined by explicit section gaps, frequently alternating between the Canvas Parchment background and a darker content block (#463938). Content is arranged in flexible grid patterns for product listings (e.g., 3-column carousel of product cards) and alternating text-left / image-right or centered stacks for feature descriptions. Navigation is a sticky top bar with minimal links and iconic utility buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #321e1e
background: #f4f1e0
border: #bdb498
accent: no distinct accent color
primary action: #321e1e (filled action)

Example Component Prompts:
Create a hero section with a 'Filled Brand Button': background #f4f1e0. Headline 'Italian Collection' using Houseplant font at 70px, weight 400, color #321e1e, letter-spacing -0.047em. Subtext 'An ode to Italian hosting' using NeueHelvetica55Roman at 16px, weight 400, color #464545, line-height 1.63. Include a 'Filled Brand Button' with text 'SHOP NOW', background #321e1e, text #f4f1e0, 4px radius, 12px 20px padding.

Create an 'Elevated Product Card': Background #f4f1e0, 8px radius, shadow rgba(0, 0, 0, 0.1) 0px 2px 8px 0px. Title 'Ashtray Set by Seth - Floral' using Houseplant font at 20px, weight 400, color #321e1e, letter-spacing -0.020em. Price '$98.00' using NeueHelvetica55Roman at 16px, weight 400, color #464545. Add a 'Shop Now Button (Product Card)' with text 'SHOP NOW', background #321e1e, text #f4f1e0, 0px radius, 0px 30px padding.

Create a Primary Action Button: #321e1e background, #f4f1e0 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Frama** — Shares a sophisticated, minimalist aesthetic with a focus on natural textures, muted color palettes, and curated product presentation.
- **Aesop** — Similar use of high-quality product photography, stark contrasts with dark typography on light backgrounds, and an overall premium, artistic feel.
- **Our Place** — Employs warm, inviting neutrals, distinctive typography for brand identity, and a strong emphasis on product-as-hero imagery.
- **Tekla Fabrics** — Features a very clean, editorial layout, prominent use of a custom serif font, and a restrained color palette that highlights product quality.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #f4f1e0;
  --color-houseplant-deep-bark: #321e1e;
  --color-text-carbon: #464545;
  --color-surface-shadow: #bdb498;
  --color-button-shadow: #463938;
  --color-pure-black: #000000;
  --color-pure-white-text: #f4f4f4;

  /* Typography — Font Families */
  --font-houseplant: 'Houseplant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehelvetica55roman: 'NeueHelvetica55Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: -0.021px;
  --text-body: 16px;
  --leading-body: 1.63;
  --tracking-body: -0.021px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.021px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.3;
  --tracking-heading: -0.02px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.02px;
  --text-display-sm: 45px;
  --leading-display-sm: 1.15;
  --tracking-display-sm: -0.047px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.05px;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.047px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Layout */
  --card-padding: 0px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-buttons: 4px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 2px 8px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.15) 0px 2px 8px 0px;

  /* Surfaces */
  --surface-canvas-parchment: #f4f1e0;
  --surface-elevated-card-surface: #f4f1e0;
  --surface-content-block-dark: #463938;
  --surface-button-dark-fill: #321e1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #f4f1e0;
  --color-houseplant-deep-bark: #321e1e;
  --color-text-carbon: #464545;
  --color-surface-shadow: #bdb498;
  --color-button-shadow: #463938;
  --color-pure-black: #000000;
  --color-pure-white-text: #f4f4f4;

  /* Typography */
  --font-houseplant: 'Houseplant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehelvetica55roman: 'NeueHelvetica55Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: -0.021px;
  --text-body: 16px;
  --leading-body: 1.63;
  --tracking-body: -0.021px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.021px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.3;
  --tracking-heading: -0.02px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.02px;
  --text-display-sm: 45px;
  --leading-display-sm: 1.15;
  --tracking-display-sm: -0.047px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.05px;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.047px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 2px 8px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.15) 0px 2px 8px 0px;
}
```
