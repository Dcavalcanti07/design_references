# ARTU — Style Reference
> Sculptural Minimalism, White Canvas

**Theme:** light

ARTU's design language evokes an art gallery presenting furniture: a pristine, expansive white canvas with precise typography and subtle, structural divisions. A singular, vibrant chartreuse accent introduces an unexpected modernity disrupting the monochromatic order. The interface prioritizes clarity and visual breathing room, utilizing thin borders, minimal elevation, and a distinct lack of heavy UI elements, allowing product imagery to remain the focal point.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, default UI elements |
| Obsidian Ink | `#000000` | `--color-obsidian-ink` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Chartreuse Glow | `#d7ff66` | `--color-chartreuse-glow` | Decorative background accents, footer background, special section highlights. Provides a high-energy, vibrant contrast |
| Passion Red | `#ff1313` | `--color-passion-red` | Red outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### Helvetica Neue Pro — The sole typeface, used for all text from headings to body copy and navigation. Its clean, sans-serif nature maintains a professional and understated tone across all contexts. · `--font-helvetica-neue-pro`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 18px, 20px, 24px, 32px
- **Line height:** 1.00, 1.15, 1.20
- **Letter spacing:** 0.0240em, 0.0220em, 0.0180em, 0.0140em
- **Role:** The sole typeface, used for all text from headings to body copy and navigation. Its clean, sans-serif nature maintains a professional and understated tone across all contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 18px | 1.15 | — | `--text-caption` |
| body-sm | 20px | 1.15 | — | `--text-body-sm` |
| body | 24px | 1.15 | — | `--text-body` |
| body-lg | 32px | 1.15 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 18 | 18px | `--spacing-18` |
| 29 | 29px | `--spacing-29` |
| 31 | 31px | `--spacing-31` |
| 32 | 32px | `--spacing-32` |
| 37 | 37px | `--spacing-37` |
| 42 | 42px | `--spacing-42` |
| 80 | 80px | `--spacing-80` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 32px
- **Card padding:** 18px
- **Element gap:** 11px

## Components

### Navigation Link
**Role:** Top navigation items and in-content links.

Black text, Helvetica Neue Pro 400, 18px-24px depending on context. Active or hovered states are indicated by an Obsidian Ink border-bottom.

### Ghost Input Field
**Role:** Form elements requiring user input.

Transparent background with Obsidian Ink text, 0px border-radius, and minimal padding. These inputs are designed to blend seamlessly into the content flow, typically only showing borders on focus or for structure.

### Primary Heading
**Role:** Main section titles and prominent text.

Helvetica Neue Pro 400, typically 32px, with generous letter-spacing (0.0140em) for an expansive feel, set in Obsidian Ink.

### Body Text
**Role:** Paragraphs and general informational text.

Helvetica Neue Pro 400, 18px-20px, Obsidian Ink. A slightly larger body size supports readability in its spacious layout. Line height is 1.20 for ample vertical room.

### Footer Section
**Role:** Bottom section with contact, navigation, and newsletter.

Set against a vibrant Chartreuse Glow background; text content is Obsidian Ink.

## Do's and Don'ts

### Do
- Maintain a spacious layout with a base unit of 4px and a default element gap of 11px.
- Use Canvas White (#ffffff) as the primary background for most sections to create a clean, gallery-like feel.
- Apply Obsidian Ink (#000000) for all text and structural borders to maximize contrast and clarity.
- Introduce Chartreuse Glow (#d7ff66) sparingly for impactful background sections, such as the footer, or specific highlights.
- Utilize Helvetica Neue Pro 400 for all typographic elements, adjusting size and letter-spacing according to semantic role, e.g., 32px with 0.0140em for headings.
- Ensure all interactive elements, like navigation links, appear as Obsidian Ink text with an Obsidian Ink bottom border on hover/active states.
- Keep border-radii at 0px across all components to maintain a sharp, architectural aesthetic.

### Don't
- Avoid using drop shadows or heavy elevation; the design system relies on flat surfaces and clear visual separation through spacing and borders.
- Do not introduce additional font families or weights beyond Helvetica Neue Pro 400.
- Refrain from using gradients; the aesthetic is flat and relies on solid color blocks.
- Do not use Chartreuse Glow (#d7ff66) or Passion Red (#ff1313) for primary action backgrounds; they are reserved for decorative accents or specific attention-grabbing elements.
- Do not deviate from the established spacing values; consistency in element and section gaps is crucial for the spacious feel.
- Avoid decorative icons or illustrations that are not essential for content comprehension; the focus is on product imagery and clean UI.
- Do not use highly saturated colors for text; reserve them for backgrounds or very specific, minimal accent elements.

## Imagery

The imagery leans heavily on high-quality product photography, specifically furniture. Products are often presented in clean, well-lit environments, sometimes against simple monochromatic backgrounds or concrete textures, suggesting premium craftsmanship. The treatment is direct and focused, with minimal styling in photos, allowing the forms and materials of the furniture to speak for themselves. There are no illustrations or abstract graphics. Icons are minimal, utility-driven, and outlined (e.g., cart, menu arrows), in Obsidian Ink.

## Layout

The page adheres to a full-bleed layout, allowing content to extend to the viewport edges, creating an immersive experience. The hero section features a prominent product presentation with subtle navigation overlaid. Content sections primarily use a flexible grid system, often displaying product images in a columnar or alternating text-and-image pattern. Vertical rhythm is maintained by generous, consistent section gaps. Navigation is a minimalist top bar, with 'English/Cart/Menu' aligned right, and 'ARTU' with primary links to the left. The overall impression is quiet and spacious, with product visuals taking precedence.

## Agent Prompt Guide

Quick Color Reference: 
  text: #000000
  background: #ffffff
  border: #000000
  accent: #d7ff66
  primary action: no distinct CTA color

Example Component Prompts:
  1. Create a header: Obsidian Ink (#000000) text (Helvetica Neue Pro 400, 18px, 0.0240em letter-spacing) for 'ARTU' on the left, and navigation links 'Products', 'Stores', 'About' to the right. All links should have an Obsidian Ink (#000000) bottom border on hover.
  2. Design a product detail section: Canvas White (#ffffff) background. Use a Helvetica Neue Pro 400 heading at 32px with 0.0140em letter-spacing in Obsidian Ink (#000000). Place body text at 20px, 1.20 line height, also in Obsidian Ink. Maintain an element gap of 11px between text blocks.
  3. Build a ghost button: Obsidian Ink (#000000) border, 0px border-radius, transparent background. Text is Helvetica Neue Pro 400 18px in Obsidian Ink (#000000). Padding should be 11px vertical and 24px horizontal.

## Similar Brands

- **Fritz Hansen** — Shares a clean, bright, product-focused aesthetic with an emphasis on furniture photography and minimal UI.
- **Carl Hansen & Søn** — Features a similar gallery-like presentation of high-end furniture on white backgrounds with restrained typography.
- **B&B Italia** — Exhibits a luxury furniture brand experience with large product images and a very clean, spacious digital presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-obsidian-ink: #000000;
  --color-chartreuse-glow: #d7ff66;
  --color-passion-red: #ff1313;

  /* Typography — Font Families */
  --font-helvetica-neue-pro: 'Helvetica Neue Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 18px;
  --leading-caption: 1.15;
  --text-body-sm: 20px;
  --leading-body-sm: 1.15;
  --text-body: 24px;
  --leading-body: 1.15;
  --text-body-lg: 32px;
  --leading-body-lg: 1.15;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-29: 29px;
  --spacing-31: 31px;
  --spacing-32: 32px;
  --spacing-37: 37px;
  --spacing-42: 42px;
  --spacing-80: 80px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 18px;
  --element-gap: 11px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-obsidian-ink: #000000;
  --color-chartreuse-glow: #d7ff66;
  --color-passion-red: #ff1313;

  /* Typography */
  --font-helvetica-neue-pro: 'Helvetica Neue Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 18px;
  --leading-caption: 1.15;
  --text-body-sm: 20px;
  --leading-body-sm: 1.15;
  --text-body: 24px;
  --leading-body: 1.15;
  --text-body-lg: 32px;
  --leading-body-lg: 1.15;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-29: 29px;
  --spacing-31: 31px;
  --spacing-32: 32px;
  --spacing-37: 37px;
  --spacing-42: 42px;
  --spacing-80: 80px;
  --spacing-108: 108px;
}
```
