# My Brentano — Style Reference
> Earthy botanical canvas

**Theme:** light

My Brentano embraces a refined, organic aesthetic creating a calm, content-forward experience. Neutral, earthy tones combined with a strong, custom sans-serif typeface define its signature. The layout emphasizes clear structural organization with subtle borders and minimal use of color, allowing product imagery and text to take precedence. Components are lightweight and understated, integrating seamlessly into the canvas rather than standing out as distinct elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button fills, input backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, link borders, button borders, navigation borders, input borders – providing crisp definition against light surfaces |
| Charcoal Text | `#212529` | `--color-charcoal-text` | Body text, heading text, list text, primary site borders – a slightly softer alternative to pure black for extensive text blocks and structural outlines |

## Tokens — Typography

### Studio Feixen Sans Writer Book — Primary typeface for all body text, headings, links, and buttons. Its 'Writer Book' style denotes a commitment to legibility and a slightly editorial, handcrafted feel that distinguishes it from standard sans-serifs. · `--font-studio-feixen-sans-writer-book`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 15px, 18px, 25px, 30px, 60px
- **Line height:** 1.20, 1.67, 2.08, 2.50
- **Letter spacing:** normal
- **Role:** Primary typeface for all body text, headings, links, and buttons. Its 'Writer Book' style denotes a commitment to legibility and a slightly editorial, handcrafted feel that distinguishes it from standard sans-serifs.

### Studio Feixen Sans Writer Book — Used for emphasized text and headings, maintaining the same clean aesthetic as the regular weight while adding clarity. · `--font-studio-feixen-sans-writer-book`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 12px, 15px, 18px, 25px, 30px, 60px
- **Line height:** 1.20, 1.67, 2.08, 2.50
- **Letter spacing:** normal
- **Role:** Used for emphasized text and headings, maintaining the same clean aesthetic as the regular weight while adding clarity.

### Studio Feixen Sans Book — A lighter-touch variant of the primary typeface, used sparingly for specific body elements and input text to provide subtle visual differentiation. · `--font-studio-feixen-sans-book`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 30px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** A lighter-touch variant of the primary typeface, used sparingly for specific body elements and input text to provide subtle visual differentiation.

### Studio Feixen Sans Writer Book Regular — Studio Feixen Sans Writer Book Regular — detected in extracted data but not described by AI · `--font-studio-feixen-sans-writer-book-regular`
- **Weights:** 400
- **Sizes:** 30px
- **Line height:** 1.2
- **Role:** Studio Feixen Sans Writer Book Regular — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.67 | — | `--text-caption` |
| body | 15px | 1.67 | — | `--text-body` |
| subheading | 18px | 1.67 | — | `--text-subheading` |
| heading-sm | 25px | 1.2 | — | `--text-heading-sm` |
| heading | 30px | 1.2 | — | `--text-heading` |
| display | 60px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |
| circularElements | 100% |

### Layout

- **Section gap:** 30px
- **Card padding:** 10px
- **Element gap:** 10px

## Components

### Circular Ghost Button
**Role:** Decorative or iconic buttons, cart badge.

Ghost style with #ffffff background, #000000 border, and #000000 text. Features a 100% border radius for a circular shape, with no internal padding for a compact, icon-only appearance.

### Rectangular Outlined Button
**Role:** Primary action buttons for purchasing or navigation.

Outlined button with #ffffff background, #000000 border, and #000000 text. Has a 0px border radius, with 5px vertical and 10px horizontal padding. Font is Studio Feixen Sans Writer Book at appropriate size.

### Ghost Navigation Link
**Role:** Subtle navigation elements.

Text link with transparent background and #000000 text. No border radius or padding. Used for simple text-based navigation or inline actions.

### Basic Input
**Role:** Form fields for user entry.

Standard input field with #ffffff background, #000000 border, and #000000 text. Has a 0px border radius, with 5px padding on all sides. Uses Studio Feixen Sans Book for text.

### Header Navigation Item
**Role:** Interactive clickable item in the main site navigation.

A text link element, using Ink Black (#000000) for text, with a transparent background. Implied border on hover/active states suggested by surrounding elements or interaction.

## Do's and Don'ts

### Do
- Prioritize Studio Feixen Sans Writer Book 400 for all body text and general interface elements, ensuring consistent legibility.
- Use Charcoal Text (#212529) for standard body text and structural borders to maintain a slightly softer contrast, reserving Ink Black (#000000) for high-impact text and outlines.
- Maintain a clear visual hierarchy with borders over shadows; use 1px solid Ink Black (#000000) borders for distinct elements like inputs and buttons.
- Implement a 10px element gap for most horizontal and vertical spacing between small interactive components, such as list items or buttons inside a container.
- Utilize 0px border radius for most container elements and buttons to maintain a sharp, clean aesthetic, with the exception of specific circular elements using 100% radius.

### Don't
- Avoid introducing additional accent colors; stick to the neutral palette for all functional UI elements.
- Do not use drop shadows for elevation; rely exclusively on borders and background color changes to define element depth.
- Refrain from using overly decorative or image-heavy backgrounds; surfaces should remain Canvas White (#ffffff) to keep focus on content and products.
- Avoid excessive padding within elements; maintain a compact density with 5px or 10px padding for most components.
- Do not deviate from the custom font families; system fonts should not be used as a substitute.

## Imagery

The imagery focuses on close-up product photography and abstract, organic macro shots of natural ingredients. Product shots are typically clean, isolated crops on neutral or slightly textured backgrounds, emphasizing the product itself with minimal lifestyle context. Abstract macro photography provides atmospheric backdrops, often with soft focus and muted, natural color palettes. Icons are minimalist, outlined, and monochrome, integrating seamlessly into the UI for functional cues rather than decorative accents. The overall density is balanced, allowing significant whitespace to frame both text and imagery.

## Layout

The page employs a contained, centered layout, allowing content to breathe within a defined maximum width. The hero section features a prominent, centered headline over a background that combines full-bleed abstract imagery with product photography. Content sections alternate between visually engaging abstract images and clear textual blocks, often structured in single or implied two-column arrangements. Vertical rhythm is established through consistent section gaps, creating a clean flow. Navigation is a minimal top bar, featuring text links and subtle iconic elements, maintaining a compact header area.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary navigation item: text 'Shop' using Studio Feixen Sans Writer Book weight 400, color Ink Black (#000000), no background or border, with elementGap 10px from adjacent items.
2. Create an input field: 0px border-radius, 1px solid Ink Black (#000000) border, Canvas White (#ffffff) background, 5px padding on all sides, placeholder text in Charcoal Text (#212529) using Studio Feixen Sans Book 400.
3. Create a secondary button: Text 'View Details' using Studio Feixen Sans Writer Book weight 400, size 15px, color Ink Black (#000000), Canvas White (#ffffff) background, 1px solid Ink Black (#000000) border, 0px border radius, 5px vertical and 10px horizontal padding.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Aēsop** — Shares a similar minimalist aesthetic, focus on product-centric imagery, and a refined, custom-feeling typography against a neutral palette.
- **Byredo** — Utilizes clean product photography and a strong, distinctive san-serif typeface with a restrained color palette for a sophisticated yet approachable feel.
- **Grown Alchemist** — Features a strong emphasis on natural products with a monochromatic design and precise typography that aligns with a premium, organic brand identity.
- **Tata Harper Skincare** — Employs a content-forward design with high-quality product imagery and a clean, legible typeface, using minimal color for a natural and trustworthy brand presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-charcoal-text: #212529;

  /* Typography — Font Families */
  --font-studio-feixen-sans-writer-book: 'Studio Feixen Sans Writer Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-studio-feixen-sans-book: 'Studio Feixen Sans Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-studio-feixen-sans-writer-book-regular: 'Studio Feixen Sans Writer Book Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.67;
  --text-body: 15px;
  --leading-body: 1.67;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 10px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-default: 0px;
  --radius-circularelements: 100%;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-charcoal-text: #212529;

  /* Typography */
  --font-studio-feixen-sans-writer-book: 'Studio Feixen Sans Writer Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-studio-feixen-sans-book: 'Studio Feixen Sans Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-studio-feixen-sans-writer-book-regular: 'Studio Feixen Sans Writer Book Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.67;
  --text-body: 15px;
  --leading-body: 1.67;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-30: 30px;
  --spacing-40: 40px;
}
```
