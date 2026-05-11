# Bang & Olufsen — Style Reference
> Gallery of precise objects. A dark, velvet-lined showcase where each product rests, spotlighted with refined exactitude.

**Theme:** mixed

This design system balances classic luxury with contemporary minimalism. Rich, deep indigo (#060daa) and elegant black (#191817) create a sophisticated backdrop, punctuated by a delicate, almost cream-colored off-white (#fcfaee) for textual contrast. The signature element is the custom BeoSupreme typeface, used across all text sizes, which brings a unique, refined character, with precise letter-spacing adjustments at every size. The dominant visual language is clean, centered product photography on stark backgrounds, framed by generous negative space and a strict typographic hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Indigo | `#060daa` | `--color-midnight-indigo` | Footer background, primary accent for deep sections – creating a luxurious, immersive foundation. |
| Carbon Black | `#191817` | `--color-carbon-black` | Dominant text color for headings and body content on light backgrounds, input borders – provides stark contrast and grounded presence. |
| Barely White | `#fcfaee` | `--color-barely-white` | Primary text color on dark backgrounds, selected button text – a creamy off-white that softens the high contrast. |
| Ash Gray | `#555555` | `--color-ash-gray` | Secondary text, subtle link color – offers a muted informational tone against white. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card backgrounds, input backgrounds – provides clean, expansive canvas. |
| Pale Silver | `#e5e5e5` | `--color-pale-silver` | Subtle border colors for inputs – an almost imperceptible divider. |
| Pure Black | `#000000` | `--color-pure-black` | Primary icon color, borders on ghost buttons – a hard, crisp edge or fill. |

## Tokens — Typography

### BeoSupreme — Primary typeface for all headings, body text, and UI elements. Its broad range of weights and precise letter-spacing across sizes is a core visual identity feature, conveying understated luxury. · `--font-beosupreme`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 24px, 36px
- **Line height:** 1.00, 1.15, 1.25, 1.33, 1.43, 1.50, 1.63, 1.67, 1.71, 2.19
- **Letter spacing:** -0.056em at 36px, -0.014em at 24px, 0.006em at 16px, 0.007em at 14px, 0.008em at 12px, then other specific values for a finely tuned optical balance
- **Role:** Primary typeface for all headings, body text, and UI elements. Its broad range of weights and precise letter-spacing across sizes is a core visual identity feature, conveying understated luxury.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | 0.007px | `--text-body` |
| heading | 24px | 1.25 | -0.014px | `--text-heading` |
| display | 36px | 1.15 | -0.056px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 236 | 236px | `--spacing-236` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 2px |
| buttons | 40px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 4px

## Components

### Primary Button (Honey Tone CTA)
**Role:** Call to action

Rounded pill button with 'Carbon Black' (#191817) background and 'Barely White' (#fcfaee) text. Has a 40px border-radius, 8px vertical padding, and 32px horizontal padding. Uses BeoSupreme text.

### Ghost Button (Menu/Search)
**Role:** Navigation/Utility

Transparent background with 'Carbon Black' (#000000) text and border. No border-radius, 0px padding. Used for minimal UI controls.

### Text Link Button
**Role:** Tertiary action/Navigation

Transparent background with 'Barely White' (#fcfaee) text and a 'Barely White' (#fcfaee) bottom border of 1px. 4px vertical padding, 0px horizontal padding. Typically used in dark sections like the hero or footer.

### Feature Card
**Role:** Product display

A completely transparent card with no padding, border, or shadow. It acts as a container for product images and descriptive text. Text is 'Carbon Black' (#191817) and headings use BeoSupreme.

### Input Field
**Role:** User entry

White background (#ffffff) with 'Carbon Black' (#191817) text and a 1px 'Carbon Black' (#191817) bottom border. No border-radius. 1px vertical padding and 2px right padding.

### New Product Badge
**Role:** Highlight new items

Rectangular badge with 'Pure White' (#ffffff) background and 'Carbon Black' (#191817) text. Has a 2px border-radius, 4px vertical padding, and 8px horizontal padding. Uses BeoSupreme text.

## Do's and Don'ts

### Do
- Prioritize the custom 'BeoSupreme' font for all textual content, leveraging its unique character and precise letter-spacing.
- Use 'Midnight Indigo' (#060daa) exclusively for foundational elements like the footer to establish a luxurious, deep anchor.
- Maintain a clear visual hierarchy by contrasting 'Carbon Black' (#191817) text on light backgrounds (#ffffff, #fcfaee) and 'Barely White' (#fcfaee) on dark backgrounds (#060daa).
- Employ the 40px border-radius strictly for primary CTA buttons, ensuring they stand out as the sole 'soft' element.
- Utilize generous negative space around product imagery and text blocks to convey a sense of premium quality and focus, with section gaps around 48px.
- Ensure all interactive elements, especially primary CTAs, meet a minimum contrast ratio of 4.5:1 against their background.
- Use a subtle 1px border for ghost button states and text links to provide definition without visual weight.

### Don't
- Do not introduce additional font families; 'BeoSupreme' defines the typographic identity.
- Avoid using multiple accent colors; 'Midnight Indigo' is reserved for specific, prominent sectional backgrounds.
- Do not deviate from the established border-radius values (0px, 2px, 40px); rounded corners are intentional and scarce.
- Do not use box-shadows; elevation is handled through background color changes and spatial separation.
- Avoid decorative elements or busy backgrounds; the aesthetic emphasizes product clarity and clean UI.
- Do not create dense content blocks; the comfortable density principle with a 4px base unit should be consistently applied.
- Never use the browser default blue for links; control all link colors with 'Carbon Black', 'Ash Gray', or 'Barely White'.

## Imagery

The visual language focuses on meticulously staged product photography. Products are often isolated or tightly cropped, centered on pure white backgrounds or against deep, velvety textiles like the 'Midnight Indigo' in the hero. The treatment is clean and raw-edged, with no masking or overlapping effects. Photography is clearly high-key for white backgrounds and moody/dark for dramatic impact on colored backgrounds, emphasizing the texture and material of the products. Images are explanatory and showcase the product as the hero, occupying significant visual space in sections to convey luxury and technical precision. Icons are minimal, monochromatic, and outlined, primarily in 'Pure Black' or 'Barely White', complementing the UI's precision.

## Layout

The page uses a mixed layout approach, blending full-bleed sections with constrained content. The hero prominently features a full-bleed dark background ('Midnight Indigo') with a large, centered product image and left-aligned headline/CTA. Subsequent sections alternate between full-bleed white backgrounds for product listings (often displaying items in a clean, centered grid of 4) and some potentially full-bleed sections with strong, singular background colors like the red observed. Content is generally centered within a comfortable maximum width when not full-bleed. Vertical rhythm is maintained by consistent spacing between sections (around 48px), creating a spacious and unhurried browsing experience. The navigation is a minimalist sticky top bar, providing persistent access without visual clutter.

## Agent Prompt Guide

### Quick Color Reference
- Text on light: #191817
- Text on dark: #fcfaee
- Page Background: #ffffff
- CTA Background: #191817
- Footer Background: #060daa

### Example Component Prompts
1. Create a hero section: 'Midnight Indigo' (#060daa) full-bleed background. Centered product image. Above it, a 'display' headline: 'Beo Grace' (BeoSupreme, 36px, 1.15lh, -0.056em ls, #fcfaee). Below, a body text: '100 años de artesanía. Un futuro icono.' (BeoSupreme, 16px, 1.33lh, 0.006em ls, #fcfaee). Underneath, a Primary Button: 'Disponible en Honey Tone' (40px radius, 8px 32px padding, #191817 background, #fcfaee text).
2. Generate a product listing grid: 'Pure White' (#ffffff) background. 'subheading' title 'Explore nuestros superventas' (BeoSupreme, 24px, 1.25lh, -0.014em ls, #191817). Display three Feature Cards horizontally, each with a centered product image, 'subheading' product name (BeoSupreme, 16px, 1.33lh, #191817) and price below it, separated by around 24px element gap.
3. Design a form input: 'Pure White' (#ffffff) background. 'Carbon Black' (#191817) text using 'body' style (BeoSupreme, 14px, 1.43lh), with a 1px 'Carbon Black' (#191817) bottom border. Placeholder text color: #555555. Padding: 1px vertical, 2px right.

## Similar Brands

- **Apple** — Shares a focus on pristine product photography on white or dark backgrounds, minimalist UI, and premium brand perception through typography and negative space.
- **Dyson** — Employs high-end product imagery, a clean, spacious layout, and a focus on precise details and materials, often with strong visual sections.
- **Bose (certain product lines)** — Exhibits a similar sophisticated, high-contrast aesthetic with an emphasis on product design and clean typographic presentation for technology goods.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-indigo: #060daa;
  --color-carbon-black: #191817;
  --color-barely-white: #fcfaee;
  --color-ash-gray: #555555;
  --color-pure-white: #ffffff;
  --color-pale-silver: #e5e5e5;
  --color-pure-black: #000000;

  /* Typography — Font Families */
  --font-beosupreme: 'BeoSupreme', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.007px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.014px;
  --text-display: 36px;
  --leading-display: 1.15;
  --tracking-display: -0.056px;

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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-236: 236px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-badges: 2px;
  --radius-buttons: 40px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-indigo: #060daa;
  --color-carbon-black: #191817;
  --color-barely-white: #fcfaee;
  --color-ash-gray: #555555;
  --color-pure-white: #ffffff;
  --color-pale-silver: #e5e5e5;
  --color-pure-black: #000000;

  /* Typography */
  --font-beosupreme: 'BeoSupreme', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.007px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.014px;
  --text-display: 36px;
  --leading-display: 1.15;
  --tracking-display: -0.056px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-236: 236px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-3xl: 40px;
}
```
