# Bongusta — Style Reference
> Warm Minimalism Canvas

**Theme:** light

Bongusta embraces a minimalist approach with a subtle touch of warmth through its earthy, almost sepia-toned neutral palette. The system prioritizes clarity and directness with crisp typography, understated components, and an absence of heavy shadows or complex gradients. Visual hierarchy is achieved through careful typographic sizing and a singular, deep plum color that acts as the primary interactive and branding accent, offering a sophisticated contrast to the prevalent soft grays. Surfaces are uncluttered, and elevation is minimal, creating an open and airy feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Paper White | `#ffffff` | `--color-paper-white` | Page backgrounds, card surfaces, navigation text in inverted states, badge backgrounds |
| Plum Core | `#321929` | `--color-plum-core` | Primary text, headings, link text, active states, icon fills, outlined button borders and text — a signature color that defines brand identity and interaction with a deep, refined warmth |
| Concrete Gray | `#e0dddf` | `--color-concrete-gray` | Hairline borders, dividers, subtle button borders — provides structure without visual weight |
| Ink Black | `#000000` | `--color-ink-black` | Icon fills, secondary link text, occasional emphasis in body text |
| Shadow Tint | `#808080` | `--color-shadow-tint` | Mid-tone panel surface for subdued dark UI layers and secondary containers. Do not promote it to the primary CTA color |
| Input Charcoal | `#1d1d1f` | `--color-input-charcoal` | Input text, input borders, darker text nuances |
| Ghost Gray | `#f0f0f0` | `--color-ghost-gray` | Lightest borders, very subtle background distinctions |
| Muted Stone | `#636363` | `--color-muted-stone` | Tertiary link colors, secondary helper text |
| Faded Text | `#6f6d6b` | `--color-faded-text` | Product card descriptions, secondary body text |

## Tokens — Typography

### NeueHaasGrotesk — Primary typeface for all body, links, navigation, cards, and labels. Its consistent weight and precise letter-spacing create a highly legible and orderly text system, underpinning the brand's quiet professionalism. · `--font-neuehaasgrotesk`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 11px, 14px, 15px, 16px, 18px, 22px
- **Line height:** 1.00, 1.30, 1.38, 1.50, 1.70
- **Letter spacing:** 0.0070em
- **Role:** Primary typeface for all body, links, navigation, cards, and labels. Its consistent weight and precise letter-spacing create a highly legible and orderly text system, underpinning the brand's quiet professionalism.

### Bongusta — Headline typeface, used for page titles and section headers. This custom font brings a distinctive, confident presence to key headings with its unique character, while maintaining a moderate weight to avoid overwhelming the minimal aesthetic. · `--font-bongusta`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 28px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Headline typeface, used for page titles and section headers. This custom font brings a distinctive, confident presence to key headings with its unique character, while maintaining a moderate weight to avoid overwhelming the minimal aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.7 | 0.154px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.098px | `--text-body-sm` |
| heading | 18px | 1.3 | 0.126px | `--text-heading` |
| heading-lg | 22px | 1 | 0.154px | `--text-heading-lg` |
| display | 28px | 1.5 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| other | 40px |
| buttons | 9999px |
| navigation | 3.5px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(50, 25, 41, 0.15) 0px 2px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 4-10px

## Components

### Pill Ghost Button
**Role:** Primary interactive element for calls to action.

Text color: Plum Core (#321929), transparent background. Border: 1px solid Plum Core (#321929). Padding: 0px. Radius: 9999px. Exhibits a subtle shadow on hover: rgba(50, 25, 41, 0.15) 0px 2px 10px 0px.

### Product Card
**Role:** Displaying product listings, features, and content modules.

Background: transparent. No borders or shadows. Radius: 0px. Internal padding is 0px, relying on external spacing for separation. Text color defaults to Plum Core (#321929).

### Filled Input Field
**Role:** User input for forms and subscriptions.

Background: transparent. Border: 1px solid Input Charcoal (#1d1d1f). Text color: Input Charcoal (#1d1d1f). Padding: 16px vertical, 24px horizontal. Radius: 0px.

### Outline Ghost Button
**Role:** Secondary action or navigation within content area.

Text color: Plum Core (#321929), transparent background. Border: 1px solid Concrete Gray (#e0dddf). Padding: 0px. Radius: 0px.

### White Background Button
**Role:** Used for specific interactive elements that need to stand out on darker backgrounds.

Background: Paper White (#ffffff). Text color: Plum Core (#321929). Border: 1px solid Concrete Gray (#e0dddf). Radius: 0px. Padding: 1px vertical, 5px horizontal.

### Flat Badge
**Role:** Categorization or short status labels.

Text color: Plum Core (#321929), transparent background. Radius: 0px. Padding: 0px.

### White Fill Badge
**Role:** Highlighting news or important tags.

Background: Paper White (#ffffff). Text color: Plum Core (#321929). Radius: 0px. Padding: 1px vertical, 5px horizontal.

## Do's and Don'ts

### Do
- Prioritize NeueHaasGrotesk for all body and UI text at 400 weight with 0.0070em letter-spacing.
- Use Plum Core (#321929) for all primary interactive elements, headings, and branding accents.
- Ensure buttons adhere to a 9999px border-radius, creating a distinct pill shape.
- Maintain a transparent background and 0px border-radius for product cards, letting content define their shape.
- Apply Concrete Gray (#e0dddf) for subtle borders and dividers, maintaining visual lightness.
- Separate major page sections with a vertical gap of approximately 48px to create breathing room.
- Use Bongusta (500 weight, 28px) exclusively for main headings to establish visual hierarchy without heavy bolding.

### Don't
- Avoid heavy drop shadows or complex gradients; rely on flat design and subtle borders for depth.
- Do not introduce new vibrant colors outside the defined palette; color should be used minimally and intentionally.
- Refrain from using bold typography for body text; the system maintains a consistent 400 weight for readability.
- Do not apply rounded corners to cards or input fields; maintain the crisp 0px radius for these elements.
- Avoid tight spacing between elements; ensure a minimum elementGap of 4-10px and sectionGap of 48px.
- Do not alter the letter-spacing of NeueHaasGrotesk; the precise 0.0070em is critical for its aesthetic.
- Never use generic system fonts when NeueHaasGrotesk or Bongusta are appropriate and available.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#808080` | The deepest background layer, rare but present, establishing the base tone. |
| 1 | Base Surface | `#ffffff` | Primary background for pages, cards, and other content blocks, creating a clean white canvas. |

## Imagery

Imagery primarily features product shots or lifestyle photography with a warm, slightly desaturated color palette, often depicting textiles or home goods. Product images are typically contained within a clean, unadorned frame, with no overlapping or complex masking. Icons are outlined, thin-stroked, and monochrome, primarily using Plum Core (#321929) or Ink Black (#000000) for a minimal, functional aesthetic. The density is image-moderate, balancing product showcases with textual information; images serve more as explanatory content and product showcase rather than decorative atmosphere.

## Layout

The page maintains a centered, max-width layout, approximately 1200px wide, with consistent white backgrounds for content. The hero section often features a blurred background image with centered, large text, setting a serene tone. Section rhythm involves alternating content blocks, typically featuring two-column layouts with text and product images. A common pattern includes a grid of product cards, utilizing 0px padding and relying on external element gaps for spacing. Navigation is a minimalistic top bar, possibly sticky, with direct links. The overall density is light and spacious, with ample breathing room between sections and content elements.

## Agent Prompt Guide

### Quick Color Reference
- text: #321929
- background: #ffffff
- border: #e0dddf
- accent: #321929
- primary action: #321929 (outlined action border)

### 3-5 Example Component Prompts
- Create a product listing card: transparent background, 0px border-radius, with product name in NeueHaasGrotesk 15px weight 400 Plum Core (#321929) and price in Faded Text (#6f6d6b) NeueHaasGrotesk 14px weight 400.
- Design a primary action button: Pill Ghost Button with 'Next' text in NeueHaasGrotesk 16px weight 400, Plum Core (#321929) text color and 1px solid border, 9999px radius, and rgba(50, 25, 41, 0.15) 0px 2px 10px 0px shadow on hover.
- Generate a newsletter subscription input field: background transparent, 1px solid Input Charcoal (#1d1d1f) border, Input Charcoal (#1d1d1f) text color, 16px vertical and 24px horizontal padding, 0px radius.
- Produce a page heading: 'Bongusta' using Bongusta font 28px weight 500, normal letter-spacing, and Plum Core (#321929) color.

## Similar Brands

- **Tekla Fabrics** — Both brands use a similar restrained, high-quality product focus with a minimalist design and a refined color palette, centered on textiles.
- **Frama** — Frama shares the emphasis on natural materials, a clean aesthetic, and a subdued, earthy color scheme for presenting home goods.
- **Arket** — Arket exhibits a comparable compact typographic style and minimalist e-commerce presentation with a focus on product photography.
- **Aesop** — Aesop employs a similar sophisticated, text-heavy approach with a limited, high-quality color palette and very clean UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-paper-white: #ffffff;
  --color-plum-core: #321929;
  --color-concrete-gray: #e0dddf;
  --color-ink-black: #000000;
  --color-shadow-tint: #808080;
  --color-input-charcoal: #1d1d1f;
  --color-ghost-gray: #f0f0f0;
  --color-muted-stone: #636363;
  --color-faded-text: #6f6d6b;

  /* Typography — Font Families */
  --font-neuehaasgrotesk: 'NeueHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bongusta: 'Bongusta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.7;
  --tracking-caption: 0.154px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.098px;
  --text-heading: 18px;
  --leading-heading: 1.3;
  --tracking-heading: 0.126px;
  --text-heading-lg: 22px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.154px;
  --text-display: 28px;
  --leading-display: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 4-10px;

  /* Border Radius */
  --radius-md: 3.5px;
  --radius-3xl: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-other: 40px;
  --radius-buttons: 9999px;
  --radius-navigation: 3.5px;

  /* Shadows */
  --shadow-md: rgba(50, 25, 41, 0.15) 0px 2px 10px 0px;

  /* Surfaces */
  --surface-canvas: #808080;
  --surface-base-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-paper-white: #ffffff;
  --color-plum-core: #321929;
  --color-concrete-gray: #e0dddf;
  --color-ink-black: #000000;
  --color-shadow-tint: #808080;
  --color-input-charcoal: #1d1d1f;
  --color-ghost-gray: #f0f0f0;
  --color-muted-stone: #636363;
  --color-faded-text: #6f6d6b;

  /* Typography */
  --font-neuehaasgrotesk: 'NeueHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bongusta: 'Bongusta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.7;
  --tracking-caption: 0.154px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.098px;
  --text-heading: 18px;
  --leading-heading: 1.3;
  --tracking-heading: 0.126px;
  --text-heading-lg: 22px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.154px;
  --text-display: 28px;
  --leading-display: 1.5;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 3.5px;
  --radius-3xl: 40px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(50, 25, 41, 0.15) 0px 2px 10px 0px;
}
```
