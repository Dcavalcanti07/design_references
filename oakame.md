# Oakâme — Style Reference
> Rustic Elegance, Anchored Earth

**Theme:** light

Oakâme projects an aesthetic of understated natural luxury, blending rustic textures with refined typography. The visual language centers on a muted, warm off-white canvas and deep, grounding charcoal text, creating a sense of calm and heritage. Subtle outlining for interactive elements and a distinct absence of decorative elements emphasize the product as the hero, allowing the natural materials to speak for themselves. The overall impression is one of crafted authenticity and quiet confidence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Earth Parchment | `#f6f1eb` | `--color-earth-parchment` | Page backgrounds, card surfaces, ghost button backgrounds, subtle hover states — a warm off-white that feels natural and aged |
| Deep Charcoal | `#403a34` | `--color-deep-charcoal` | All primary text, headings, prominent borders, and filled button backgrounds — a dark, grounding neutral that provides strong contrast |
| Woocommerce Complement | `#e9e6ed` | `--color-woocommerce-complement` | WooCommerce secondary backgrounds, subtle separators |

## Tokens — Typography

### BwGradual — The sole typeface, used for all textual elements. Its versatility across many weights and sizes, from small navigation links to expansive hero headlines, creates a cohesive and distinguished voice. The generous letter spacing for small text and negative for large text are signature characteristics. · `--font-bwgradual`
- **Substitute:** Open Sans or Lato for body, Playfair Display or Lora for headings
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 18px, 20px, 40px, 50px, 60px, 120px, 180px, 250px
- **Line height:** 1.10, 1.20, 1.24, 1.25, 1.30, 1.40, 1.50
- **Letter spacing:** -0.0560em at 250px, 0.1000em at 10px, 0.0830em at 12px
- **Role:** The sole typeface, used for all textual elements. Its versatility across many weights and sizes, from small navigation links to expansive hero headlines, creates a cohesive and distinguished voice. The generous letter spacing for small text and negative for large text are signature characteristics.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 1px | `--text-caption` |
| body | 18px | 1.4 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 40px | 1.25 | — | `--text-heading-sm` |
| heading | 50px | 1.2 | — | `--text-heading` |
| heading-lg | 60px | 1.2 | — | `--text-heading-lg` |
| display | 120px | 1.1 | -1.344px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 68 | 68px | `--spacing-68` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 150px
- **Card padding:** 0px
- **Element gap:** 20px

## Components

### Ghost Button
**Role:** Secondary calls to action and navigation links.

Background: Earth Parchment (#f6f1eb), Text: Deep Charcoal (#403a34), Border: 1px solid Deep Charcoal (#403a34), Padding: 15px vertical, 50px horizontal. Radius: 0px.

### Filled Button
**Role:** Primary calls to action.

Background: Deep Charcoal (#403a34), Text: Earth Parchment (#f6f1eb), Border: 1px solid Deep Charcoal (#403a34), Padding: 10px vertical, 20px horizontal. Radius: 0px.

### Product Card (Background)
**Role:** Used for product listings where the image is against a solid background.

Background: Earth Parchment (#f6f1eb), Border: none, Shadow: none, Padding: 0px. Radius: 0px.

### Product Card (Transparent)
**Role:** Used for product listings where the image naturally blends with the page background.

Background: transparent (rgba(0, 0, 0, 0)), Border: none, Shadow: none, Padding: 0px. Radius: 0px.

## Do's and Don'ts

### Do
- Prioritize Deep Charcoal (#403a34) for all primary text and interactive element outlines.
- Use Earth Parchment (#f6f1eb) as the dominant background color for canvas and card surfaces.
- Apply a 0px border-radius to all UI elements, maintaining a crisp and structured aesthetic.
- When using Ghost Buttons, ensure a 1px solid border of Deep Charcoal (#403a34) with Earth Parchment (#f6f1eb) background.
- Employ BwGradual font for all text, manipulating sizes and letter-spacing to create visual hierarchy.
- Maintain a clear visual separation between sections using the implied sectionGap of 150px, rather than dividers or heavy backgrounds.
- Utilize letter-spacing: -0.056em for display-sized headlines (250px) to give them a refined, quiet presence.

### Don't
- Do not introduce additional background colors; maintain the Earth Parchment (#f6f1eb) dominant canvas.
- Avoid using drop shadows or complex elevation; the design relies on flat surfaces and clear borders.
- Do not use highly saturated or chromatic colors outside of specific WooCommerce semantic contexts.
- Do not round corners on any UI component; all elements should be sharp and angular.
- Avoid decorative graphical elements or overwhelming imagery; the product photography and clean UI are the focus.
- Do not deviate from BwGradual font family; it defines the brand's typographic voice.
- Do not vary the border width for interactive elements from 1px; consistency is key to their subtle presence.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#f6f1eb` | Primary page background and foundational surface. |

## Imagery

Photography is the primary visual medium, showcasing product items directly or in natural, well-lit settings that evoke texture and craftsmanship. Images are generally contained within their sections, with some full-bleed hero moments that establish atmosphere. The treatment is focused on rich detail of the wood and fabric, often with warm, natural lighting. Product catalog images are pure crops on a light background. Icons, when present (like in the header), are thin-stroked and monochrome, providing functional cues without drawing significant visual attention.

## Layout

The overarching page layout is full-bleed, with content sections primarily centered and constrained within an implicit maximum width, giving a spacious feel but without strict container edges. The hero section often features large, immersive photography that spans the full viewport width, anchored by a large, understated headline. Sections flow seamlessly, separated by ample vertical spacing, without explicit dividers. Content frequently alternates between large text blocks and product imagery, sometimes in multi-column grids for feature showcases or product categories. Navigation is a minimalist top bar, with prominent branding and subtle iconographic links.

## Agent Prompt Guide

Quick Color Reference:
- text: #403a34
- background: #f6f1eb
- border: #403a34
- accent: no distinct accent color
- primary action: #403a34 (filled action)

Example Component Prompts:
- Create a primary navigation link: text Deep Charcoal (#403a34), font BwGradual, weight 400, size 12px, line-height 1.5, letter-spacing 0.996px. Active state to have a 1px solid bottom border of Deep Charcoal (#403a34).
- Design a hero section headline: text Deep Charcoal (#403a34), font BwGradual, weight 700, size 250px, line-height 1.1, letter-spacing -1.344px.
- Render a Ghost button for a secondary action: background Earth Parchment (#f6f1eb), text Deep Charcoal (#403a34), border 1px solid Deep Charcoal (#403a34), padding 15px 50px, border-radius 0px.
- Generate a Filled Button for a main call to action: background Deep Charcoal (#403a34), text Earth Parchment (#f6f1eb), border 1px solid Deep Charcoal (#403a34), padding 10px 20px, border-radius 0px.
- Construct a product listing card: background Earth Parchment (#f6f1eb), padding 0px, border-radius 0px, no shadow. Product image contained within.

## Similar Brands

- **Frama** — Shares a minimal aesthetic with natural materials, precise typography, and a focus on product photography.
- **Muuto** — Exhibits a similar Scandinavian-inspired feel with high-quality furniture, light backgrounds, and clean lines.
- **B&B Italia** — Characterized by premium furniture display, large imagery, and refined, understated typography on a largely neutral palette.
- **Menu Design** — Known for contemporary design with a strong emphasis on product visuals and a muted, sophisticated color scheme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-earth-parchment: #f6f1eb;
  --color-deep-charcoal: #403a34;
  --color-woocommerce-complement: #e9e6ed;

  /* Typography — Font Families */
  --font-bwgradual: 'BwGradual', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 1px;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.25;
  --text-heading: 50px;
  --leading-heading: 1.2;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.2;
  --text-display: 120px;
  --leading-display: 1.1;
  --tracking-display: -1.344px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-68: 68px;

  /* Layout */
  --section-gap: 150px;
  --card-padding: 0px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-none: 0px;

  /* Surfaces */
  --surface-base-canvas: #f6f1eb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-earth-parchment: #f6f1eb;
  --color-deep-charcoal: #403a34;
  --color-woocommerce-complement: #e9e6ed;

  /* Typography */
  --font-bwgradual: 'BwGradual', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 1px;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.25;
  --text-heading: 50px;
  --leading-heading: 1.2;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.2;
  --text-display: 120px;
  --leading-display: 1.1;
  --tracking-display: -1.344px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-68: 68px;
}
```
