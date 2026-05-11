# Surface — Style Reference
> Minimalist gallery canvas

**Theme:** light

Arctic Volume presents a bold, editorial aesthetic. It emphasizes high contrast typography on vast, unobtrusive white space. Visuals are treated as distinct collage elements, drawing attention without being enclosed. The overall impression is one of stark graphic clarity, where content is king and design serves to amplify rather than decorate.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Arctic Snow | `#f7f7f7` | `--color-arctic-snow` | Primary page canvas and white card surfaces. Do not promote it to the primary CTA color |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, outlines for buttons, active navigation items, filled button backgrounds, decorative borders |

## Tokens — Typography

### Munken Sans Web — All text elements, from body copy and links to navigation and massive display headings. Its clean, sans-serif geometry with distinct proportions establishes the site's editorial and art-forward feel. · `--font-munken-sans-web`
- **Substitute:** Inter
- **Weights:** 400, 700, 900
- **Sizes:** 16px, 20px, 30px, 40px, 230px
- **Line height:** 1.00, 1.20, 1.35, 1.50
- **Role:** All text elements, from body copy and links to navigation and massive display headings. Its clean, sans-serif geometry with distinct proportions establishes the site's editorial and art-forward feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.35 | — | `--text-subheading` |
| heading-sm | 30px | 1.2 | — | `--text-heading-sm` |
| heading | 40px | 1.2 | — | `--text-heading` |
| display | 230px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** Secondary actions and navigation links

Text in Midnight Ink (#000000) on an Arctic Snow (#f7f7f7) background, with a 1px Midnight Ink (#000000) border. Padding is 6px around the text. Radius is 0px.

### Filled Primary Button
**Role:** Primary calls to action

Text in Arctic Snow (#f7f7f7) on a Midnight Ink (#000000) background, with a 1px Midnight Ink (#000000) border. Padding is 14px vertically and 38px horizontally. Radius is 0px.

### Content Card (Image/Text)
**Role:** Displaying images and associated text in a grid or collage layout

No background color, no borders, no box shadow, and no padding. Content is presented directly. Radius is 0px. Text inside cards uses Midnight Ink (#000000).

## Do's and Don'ts

### Do
- Always use Munken Sans Web for all text elements.
- Implement Midnight Ink (#000000) for all primary text and active states.
- Utilize Arctic Snow (#f7f7f7) as the dominant background color for clarity.
- Adhere to a 0px border-radius for all elements (buttons, cards) to maintain a sharp, editorial edge.
- Maintain high contrast between text and background, typically Midnight Ink on Arctic Snow.
- Employ consistent 48px vertical spacing between major page sections and headings.
- Design with a spacious layout, allowing ample white space around elements.

### Don't
- Avoid rounded corners; all interface elements should have a 0px radius.
- Do not introduce additional saturated colors; the palette is strictly achromatic for UI elements.
- Refrain from using drop shadows or complex elevation; surfaces are flat and direct.
- Do not add padding or borders to primary content cards; they should float freely or be placed directly.
- Avoid decorative gradients or background images for UI components; stick to solid colors.
- Do not use letter-spacing other than normal, except where explicitly specified by type scale.

## Imagery

This site features a heavy reliance on photography and occasional abstract graphics, treated with a collage-like sensibility. Images are typically contained within their own bounding boxes, but arranged in dynamic, overlapping, and seemingly unconstrained layouts, creating a 'mood board' effect. Photography styles vary, from product-focused to artistic lifestyle shots. The imagery serves primarily as decorative atmosphere and content showcase, often appearing in high density relative to text, contributing to the visual-first editorial feel.

## Layout

The page uses a full-bleed layout without a fixed max-width, allowing content to span the browser's width, though elements frequently align to loose vertical columns or grids. The hero section features unusually large, overlapping text with an irregular arrangement of small image cards, setting a dynamic, non-uniform tone. Section rhythm is primarily driven by generous vertical spacing between content blocks. Content arrangement is fluid; sometimes text-left/image-right, but more often a collage of visual elements surrounding central textual content. The navigation is minimal, a simple top-bar with a hamburger menu.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #f7f7f7
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

**3-5 Example Component Prompts**
Create a ghost button: text 'Learn More' in Midnight Ink (#000000), background Arctic Snow (#f7f7f7), 1px border in Midnight Ink (#000000), 6px padding on all sides, 0px border-radius.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
Create a heading: 'Surface N° 3' using Munken Sans Web weight 900 at 230px size, line-height 1.00, color Midnight Ink (#000000).

## Similar Brands

- **AIGA Journal** — Editorial layout with strong typography and minimal UI, high contrast, and focus on image presentation.
- **The New York Times (digital)** — Focus on high-contrast text, spacious layouts, and a clean, journalistic aesthetic with controlled use of imagery.
- **Esquire Magazine (digital)** — Bold type with clear structure on a light background, emphasizing readability and imagery in a clean, uncluttered way.
- **Are.na** — Content-focused with a white canvas, minimal borders, and a focus on visual hierarchy through typography and spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-arctic-snow: #f7f7f7;
  --color-midnight-ink: #000000;

  /* Typography — Font Families */
  --font-munken-sans-web: 'Munken Sans Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-display: 230px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-arctic-snow: #f7f7f7;
  --color-midnight-ink: #000000;

  /* Typography */
  --font-munken-sans-web: 'Munken Sans Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-display: 230px;
  --leading-display: 1;

  /* Spacing */
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
}
```
