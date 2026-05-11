# Moffitt.Moffitt. - — Style Reference
> monochrome gallery canvas

**Theme:** light

Moffitt.Moffitt. evokes a gallery-like atmosphere, pairing high-contrast monochrome with ample negative space to emphasize content over interface. Its visual language relies on stark black and white, subtly textured neutrals, and a complete absence of vibrant accents. Typography is the primary vehicle for detail, with a focus on distinct display and body faces. Components are minimal and often borderless, blending into the canvas to allow imagery and strong type to command attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, clean sections that emphasize content |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong headlines, button backgrounds, borders, and interactive elements. Establishes high contrast |
| Fog Gray | `#f5f5f5` | `--color-fog-gray` | Subtle background for secondary sections, creating visual segmentation without strong contrast |
| Charcoal Gray | `#595b60` | `--color-charcoal-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Stone Gray | `#888888` | `--color-stone-gray` | Muted text, helper text, and decorative strokes where minimal contrast is desired |
| Divider Gray | `#d8d8da` | `--color-divider-gray` | Fine borders and subtle dividers, providing structural separation |

## Tokens — Typography

### Suisse — Primary sans-serif for all UI text, headings, and body copy. Its range of weights and sizes supports a hierarchical information architecture, from compact labels to prominent titles. · `--font-suisse`
- **Substitute:** Helvetica Neue, Arial
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 16px, 22px, 24px, 40px
- **Line height:** 1.00, 1.13, 1.17, 1.20, 1.25, 1.33, 1.39, 2.00
- **Letter spacing:** normal
- **Role:** Primary sans-serif for all UI text, headings, and body copy. Its range of weights and sizes supports a hierarchical information architecture, from compact labels to prominent titles.

### Lyon — Specialized light-weight serif for small text elements, such as metadata, captions, or callouts. Its delicacy provides a visual counterpoint to the more robust Suisse. · `--font-lyon`
- **Substitute:** Georgia, serif
- **Weights:** 100
- **Sizes:** 13px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Specialized light-weight serif for small text elements, such as metadata, captions, or callouts. Its delicacy provides a visual counterpoint to the more robust Suisse.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | — | `--text-caption` |
| body | 16px | 1.25 | — | `--text-body` |
| subheading | 22px | 1.13 | — | `--text-subheading` |
| heading | 24px | 1.17 | — | `--text-heading` |
| display | 40px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 50px |
| cards | 0px |
| images | 5px |
| inputs | 0px |
| buttons | 50px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Pill Button - Light
**Role:** Interactive element (button).

White background, Ink Black text, 50px border-radius, 11px horizontal padding, 0px vertical padding. Used for secondary actions and tags.

### Pill Button - Dark
**Role:** Interactive element (button).

Ink Black background, Canvas White text, 50px border-radius, 11px horizontal padding, 0px vertical padding. Used for primary actions and prominent tags.

### Ghost Link
**Role:** Interactive text link/button.

Transparent background, Ink Black text, no border-radius or padding. Appears as pure text, often with an implicit interactive area.

### Muted Ghost Link
**Role:** Interactive text link/button (muted).

Transparent background, Stone Gray text, no border-radius or padding. Used for tertiary actions or less prominent links that fade into the background.

### Content Card
**Role:** Container for content.

Transparent background, 0px border-radius, no box shadow, 0px internal padding. Content within defines its visual boundaries.

### Form Input
**Role:** User input field.

Transparent background, Canvas White text, Canvas White 1px border, 0px border-radius, no padding. Minimalist input field for forms.

## Do's and Don'ts

### Do
- Prioritize high contrast between Ink Black (#000000) and Canvas White (#ffffff) for primary text and backgrounds.
- Use Fog Gray (#f5f5f5) as a subtle background for sections to create soft visual transitions, not strong divisions.
- Apply 50px border-radius for all interactive buttons and tags to maintain the distinct pill shape.
- Employ the Suisse font family for all functional text elements, varying weight to establish hierarchy.
- Maintain generous negative space around content blocks, ensuring a breathable and uncrowded layout.
- Use 0px radius for content cards and inputs, ensuring a sharp, modern appearance.
- Ensure borders, when present, are 1px solid using Divider Gray (#d8d8da) or Ink Black (#000000) for clean definition.

### Don't
- Do not introduce any saturated colors; resist the urge to add color for emphasis.
- Avoid using box shadows; prefer flat, stacked surfaces or subtle background color changes for depth.
- Do not use generic button styles; all primary and secondary buttons must adhere to the 50px pill-shape radius.
- Do not add unnecessary padding or borders to cards; keep them visually lightweight and integrated with the canvas.
- Avoid heavy or complex gradients; prefer solid colors or the natural gradients of photography.
- Do not use letter-spacing other than 'normal' for Suisse and Lyon fonts.
- Do not deviate from the specified font families; avoid system defaults or other creative typographies.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default surface for most content sections. |
| 2 | Fog Gray | `#f5f5f5` | Secondary background for alternating content sections, providing a subtle shift in visual texture. |
| 3 | Ink Black | `#000000` | Used as an occasional dark surface for highly impactful sections or controls, creating maximum contrast. |

## Imagery

The visual language is characterized by high-quality photography, often depicting architectural spaces, product shots, or stylized portraits. Images generally have a muted, almost desaturated color palette, aligning with the overall monochrome aesthetic. They are often full-bleed or large format, acting as primary visual content. For iconography, a minimalist, outlined style is preferred, typically in Ink Black or Stone Gray, maintaining a delicate and unobtrusive presence. Imagery serves to establish atmosphere, showcase projects, and provide a sophisticated backdrop, rather than acting as purely decorative elements.

## Layout

The page model is largely full-bleed, but with a strong emphasis on horizontal centering and comfortable negative space. Hero sections often feature large, impactful imagery alongside concise, high-contrast typography. Section rhythm is created through alternating Canvas White and Fog Gray backgrounds, providing clear visual breaks. Content arrangement frequently uses large, single-column blocks for impactful statements, or balanced two-column layouts pairing imagery with text. Navigation is minimal, typically a subtle sticky header with a hamburger menu icon. The overall density is spacious, allowing each element to breathe and resonate.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #d8d8da
accent: no distinct accent color
primary action: #000000 (filled action)

Example Component Prompts:
Create a primary navigation link: text 'Projects' in Suisse weight 400 at 16px, color Ink Black (#000000), no underline. When hovered, text color subtly changes to Charcoal Gray (#595b60).
Create a Pill Button for an important action: Ink Black (#000000) background, Canvas White (#ffffff) text 'Submit' in Suisse weight 400 at 16px, 50px border-radius, 11px horizontal padding, 0px vertical padding.
Create a secondary section heading: text 'Feed' in Suisse weight 400 at 40px, color Ink Black (#000000).
Create a ghost text button for a filter: text 'Music' in Suisse weight 400 at 16px, color Ink Black (#000000), transparent background, no border, no padding. When active, background is Ink Black (#000000) and text is Canvas White (#ffffff).
Create a content card with an image: 0px border-radius, transparent background, containing an image with 5px border-radius and a caption below in Lyon weight 100 at 13px, color Stone Gray (#888888).

## Similar Brands

- **Stripe** — Shares a sophisticated, high-contrast monochrome aesthetic with clean typography and minimal UI elements.
- **Apple** — Employs extensive use of negative space, large impactful imagery, and a focus on subtle surfaces with high contrast text.
- **B&O (Bang & Olufsen)** — Similar focus on premium, minimalist design with a heavy reliance on a black and white palette and quality photography to convey brand value.
- **Linear** — Features a highly refined, almost entirely achromatic UI where typography and crisp lines define components, and color is used sparingly for functional accents (though Linear uses a distinct accent color, Moffitt.Moffitt. explicitly does not).

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-fog-gray: #f5f5f5;
  --color-charcoal-gray: #595b60;
  --color-stone-gray: #888888;
  --color-divider-gray: #d8d8da;

  /* Typography — Font Families */
  --font-suisse: 'Suisse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lyon: 'Lyon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 22px;
  --leading-subheading: 1.13;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-tags: 50px;
  --radius-cards: 0px;
  --radius-images: 5px;
  --radius-inputs: 0px;
  --radius-buttons: 50px;

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
  --color-fog-gray: #f5f5f5;
  --color-charcoal-gray: #595b60;
  --color-stone-gray: #888888;
  --color-divider-gray: #d8d8da;

  /* Typography */
  --font-suisse: 'Suisse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lyon: 'Lyon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 22px;
  --leading-subheading: 1.13;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-full: 50px;
  --radius-full-2: 100px;
}
```
