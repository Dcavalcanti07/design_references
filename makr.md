# MAKR — Style Reference
> Workshop-crafted monochrome utility.

**Theme:** light

MAKR employs a utilitarian workshop aesthetic, characterized by a monochrome palette, robust typography, and minimal decorative elements. The design prioritizes directness and product focus, using abundant white space and a tightly constrained color scheme of near-black text on white or light gray surfaces. Interactions are subdued, relying on subtle background shifts and text changes rather than overt animations or vibrant accent colors. The overall impression is one of crafted precision and understated quality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#1c1717` | `--color-ink` | Primary text, headings, links, borders for outlines, input text. This near-black provides strong contrast on light backgrounds |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, elevated card surfaces, main content areas |
| Fog | `#f0f0f0` | `--color-fog` | Subtle background for secondary sections, light dividers, input field backgrounds |
| Stone | `#a9aea9` | `--color-stone` | Button backgrounds, promotional banners — a muted, desaturated gray to provide a soft interactive surface without strong chromatic emphasis |

## Tokens — Typography

### Sohne Web — Primary typeface for all text content: body, headings, links, and buttons. Its clean, utilitarian nature underpins the brand's direct aesthetic. · `--font-sohne-web`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 11px, 12px, 13px, 14px, 16px, 18px, 20px, 32px
- **Line height:** 1.15, 1.35, 1.40, 1.45, 1.80
- **Letter spacing:** 0.015em at smaller sizes, 0.03em at larger sizes
- **Role:** Primary typeface for all text content: body, headings, links, and buttons. Its clean, utilitarian nature underpins the brand's direct aesthetic.

### CircularXXMonoWeb — Used sparingly for decorative links or specific callouts, lending a technical, almost machine-generated feel. · `--font-circularxxmonoweb`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 13px, 20px
- **Line height:** 1.15
- **Letter spacing:** normal
- **Role:** Used sparingly for decorative links or specific callouts, lending a technical, almost machine-generated feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.45 | 0.165px | `--text-caption` |
| heading | 18px | 1.35 | 0.27px | `--text-heading` |
| heading-lg | 20px | 1.15 | 0.6px | `--text-heading-lg` |
| display | 32px | 1.15 | 0.96px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 60 | 60px | `--spacing-60` |
| 90 | 90px | `--spacing-90` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 90px
- **Card padding:** 12px
- **Element gap:** 5px

## Components

### Primary Filled Button
**Role:** Call to action.

Background: Stone (#a9aea9), Text: Ink (#1c1717), Border: 1px solid Ink (#1c1717), Radius: 0px. Padding 16px top, 10px right, 12px bottom, 20px left. Text uses Sohne Web Regular 13px.

### Text Input
**Role:** Form text entry.

Background: transparent, Text: Ink (#1c1717), Border: 1px solid Ink (#1c1717), Radius: 0px. Padding 1px top, 2px right, 1px bottom, 2px left.

### Product Tag Badge
**Role:** Informational labels for products or promotions.

Background: transparent, Text: Ink (#1c1717). No padding or border. Used as a text-only label.

## Do's and Don'ts

### Do
- Use Ink (#1c1717) for all primary text and Canvas (#ffffff) for primary backgrounds.
- Maintain a rigid 0px border-radius for all UI elements, including buttons, inputs, and cards.
- Apply Sohne Web Regular (400) for all body text, headings, and interactive elements.
- Structure layouts with ample white space, using a section gap of 90px between major content blocks.
- Utilize Stone (#a9aea9) as the background for primary interactive buttons, paired with Ink (#1c1717) text and a 1px Ink border.
- Employ Fog (#f0f0f0) sparingly for subtle background differentiation in secondary content areas or inputs.
- Reserve CircularXXMonoWeb-Regular (400) for specific decorative text elements or unique callouts, not for general content.

### Don't
- Avoid using any saturated or vivid accent colors; the palette is strictly monochrome.
- Do not introduce rounded corners or soft edges on any components.
- Refrain from using drop shadows or elevation effects; elements should appear flat on the canvas.
- Do not use gradients; all colors should be solid fills.
- Avoid decorative typography; maintain the utilitarian style of Sohne Web as the dominant font.
- Do not deviate from the specified spacing units; consistency in 5px element gaps and 90px section gaps is key.
- Do not use default browser link colors; all links must be styled with Ink (#1c1717).

## Imagery

The imagery features tightly cropped, professional product photography against neutral backgrounds (often white, gray, or soft blurs of natural settings). There is a mix of highly detailed product shots and contextual action shots that showcase products in use, without overt lifestyle branding. Photography is often monochromatic or desaturated, aligning with the overall brand aesthetic. Illustrations and abstract graphics are absent. Icons are minimal, utility-based, and appear as simple outlined or filled shapes consistent with the primary text color, #1c1717. Images serve to showcase the product directly and provide functional context, rather than purely decorative or atmospheric roles.

## Layout

The page primarily uses a full-bleed layout, where content sections span the full width of the viewport, particularly for large image blocks and product showcases. Textual content and UI elements are typically contained within a centered max-width content area (implicitly around 1200px based on observable patterns). The hero section often features large, immersive product photography with superimposed text links or minimal headlines. Section rhythm is driven by consistent vertical spacing of 90px and alternating content blocks, sometimes featuring equal-width multi-column grids for presenting product variations or features. Navigation is a minimal top bar with left-aligned brand logo and right-aligned utility links (Account, Cart).

## Agent Prompt Guide

Quick Color Reference:
- text: #1c1717
- background: #ffffff
- border: #1c1717
- accent: no distinct accent color
- primary action: no distinct CTA color

Example Component Prompts:
- Create a product listing card: Canvas (#ffffff) background, 0px radius. Use Sohne Web (400) 18px text for product titles in Ink (#1c1717), and Sohne Web (400) 14px text for prices. Keep 12px padding around content. Outline the bottom of the card with a 1px solid Ink (#1c1717) border.
- Design a 'Subscribe' input field with a 'Submit' button: Input field with transparent background, #1c1717 text, 1px solid #1c1717 border, 0px radius, 1px top/bottom, 2px left/right padding. Adjacent Submit button with Stone (#a9aea9) background, Ink (#1c1717) text, 1px solid Ink (#1c1717) border, 0px radius, 16px top, 10px right, 12px bottom, 20px left padding.
- Create a promotional banner: Stone (#a9aea9) background band, with Sohne Web (400) 13px text in Ink (#1c1717) for promotional messages, centered horizontally. Use 7px top and bottom padding.

## Similar Brands

- **A.P.C.** — Similar focus on minimalist, high-quality products presented with understated typography and a muted color palette.
- **Everlane** — Emphasizes clear product imagery, clean layouts, and a neutral color scheme for an honest, utilitarian feel.
- **Aesop** — Uses a very restrained, almost entirely black and white aesthetic with precise typography and minimal UI elements.
- **Common Projects** — Product-focused e-commerce with a lean, almost academic design, featuring high contrast and no decorative flourishes.
- **Studio McGee** — While different industry, shares the clean, unornamented typographic style and heavy reliance on crisp achromatic tones.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #1c1717;
  --color-canvas: #ffffff;
  --color-fog: #f0f0f0;
  --color-stone: #a9aea9;

  /* Typography — Font Families */
  --font-sohne-web: 'Sohne Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-circularxxmonoweb: 'CircularXXMonoWeb', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.165px;
  --text-heading: 18px;
  --leading-heading: 1.35;
  --tracking-heading: 0.27px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: 0.6px;
  --text-display: 32px;
  --leading-display: 1.15;
  --tracking-display: 0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 90px;
  --card-padding: 12px;
  --element-gap: 5px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #1c1717;
  --color-canvas: #ffffff;
  --color-fog: #f0f0f0;
  --color-stone: #a9aea9;

  /* Typography */
  --font-sohne-web: 'Sohne Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-circularxxmonoweb: 'CircularXXMonoWeb', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.165px;
  --text-heading: 18px;
  --leading-heading: 1.35;
  --tracking-heading: 0.27px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: 0.6px;
  --text-display: 32px;
  --leading-display: 1.15;
  --tracking-display: 0.96px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;
}
```
