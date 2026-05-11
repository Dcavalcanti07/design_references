# Altason — Style Reference
> Black & White Gallery

**Theme:** light

Atlason's visual system evokes a gallery of curated industrial design, prioritizing form and function through stark contrasts and precise typography. The aesthetic is black and white, with expansive negative space framing product visuals. Typography is compact and commanding, set in a sans-serif that conveys a sense of modernity and clarity. The overall impression is one of sophisticated minimalism, where every element is intentional and serves to highlight the featured works.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, large content areas, primary light surface |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, headings, prominent borders, secondary dark surface |
| Ash Gray | `#b0b0b0` | `--color-ash-gray` | Muted text, subtle borders, secondary information |

## Tokens — Typography

### haas-grotesk-tx-pro — Body text, navigation links, secondary headings. Its relatively normal letter-spacing ensures comfortable reading for longer passages while maintaining a modern feel. · `--font-haas-grotesk-tx-pro`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 18px, 36px
- **Line height:** 0.90, 1.00, 1.20, 1.30
- **Letter spacing:** normal
- **OpenType features:** `"calt", "kern", "liga", "rclt", "rlig", "rvrn"`
- **Role:** Body text, navigation links, secondary headings. Its relatively normal letter-spacing ensures comfortable reading for longer passages while maintaining a modern feel.

### haas-grotesk-ds-pro — Large headings and display text. The compact line heights, especially at larger sizes, contribute to a tight, impactful visual block, reinforcing the deliberate design aesthetic. · `--font-haas-grotesk-ds-pro`
- **Substitute:** Inter Display
- **Weights:** 500
- **Sizes:** 48px, 106px, 230px, 288px
- **Line height:** 0.77, 0.80, 1.00, 1.20
- **Letter spacing:** normal
- **OpenType features:** `"calt", "kern", "liga", "rclt", "rlig", "rvrn"`
- **Role:** Large headings and display text. The compact line heights, especially at larger sizes, contribute to a tight, impactful visual block, reinforcing the deliberate design aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.3 | — | `--text-body-sm` |
| body | 18px | 1.2 | — | `--text-body` |
| heading-sm | 36px | 1 | — | `--text-heading-sm` |
| heading | 48px | 0.8 | — | `--text-heading` |
| heading-lg | 106px | 0.77 | — | `--text-heading-lg` |
| display | 288px | 0.77 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 112 | 112px | `--spacing-112` |

### Layout

- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Navigation Link (Header)
**Role:** Primary navigation links in headers.

Text in Ink Black (#000000), Haas Grotesk TX Pro weight 500, size 36px, with no explicit padding, relying on surrounding elements for spacing. Interactive state indicated by a 1px Ink Black underline on hover.

### Product Thumbnail Card
**Role:** Displays product images with titles.

Image area with a 1px Ink Black (#000000) border, surrounding text in Haas Grotesk TX Pro, 16px, weight 400. Text has 8px top padding and 10px right/left padding, background is Canvas White (#ffffff).

### Contact Information Block
**Role:** Lists contact details and address.

Body text in Haas Grotesk TX Pro, 16px, weight 400, Ink Black (#000000). Links are also Inlk Black, with a 1px Ink Black (#000000) bottom border for emphasis. Uses 8px vertical spacing between lines.

### Footer Section
**Role:** Contains navigation links and copyright information.

Text in Ash Gray (#b0b0b0), Haas Grotesk TX Pro, 16px. Links are Ink Black (#000000). Elements have 8px padding and 10px spacing.

## Do's and Don'ts

### Do
- Use Canvas White (#ffffff) as the primary background for all page content to maintain a clean, expansive feel.
- Employ Ink Black (#000000) for all primary text, headings, and significant borders to achieve strong contrast and visual impact.
- Utilize Haas Grotesk DS Pro, weight 500, for all display-level headings (48px and above) with compact line heights to create impactful typographic blocks.
- Apply Haas Grotesk TX Pro, weight 400 or 500, for all body text, links, and secondary information, distinguishing its usage from display headings.
- Maintain a clear visual hierarchy by placing product visuals framed by generous Canvas White (#ffffff) space and minimal text overlays.
- Use 8px as the default `elementGap` for vertical spacing between related content elements and 48px for `sectionGap` between distinct content blocks.
- Border product thumbnail cards with a 1px solid Ink Black (#000000) line to create distinct content modules.

### Don't
- Avoid introducing saturated colors outside of embedded imagery; the interface should remain monochrome.
- Do not use subtle variations of black or white for background or text where Ink Black or Canvas White provide sufficient contrast.
- Refrain from using any form of elevation (shadows) on UI elements; the design emphasizes flat surfaces.
- Do not use rounded corners on any UI components; all elements should maintain sharp, defined edges.
- Avoid dense, text-heavy blocks. Break up information with imagery and ample whitespace.
- Do not use generic system fonts; stick to `haas-grotesk-tx-pro` and `haas-grotesk-ds-pro` or their designated substitutes.
- Do not create highly interactive or animated elements; the motion profile is functional and subtle (ease, durations 0.3-0.5s).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and non-interactive content areas. |
| 1 | Product Card White | `#ffffff` | Background for product display cards, framed by borders, to separate contained content. |
| 2 | Overlay Black | `#000000` | Implicit dark surface for graphic elements or full-bleed imagery, creating strong contrast. |

## Elevation

The design intentionally avoids shadows and elevation effects. All elements exist on a single, flat plane, relying on stark color contrast, precise lines, and generous negative space to define hierarchy and separation. This commitment to flatness reinforces the 'gallery' aesthetic, presenting content without visual ornamentation.

## Imagery

The site uses a mix of high-quality product photography and abstract graphic elements. Product photography is typically studio-shot, featuring tight crops, often on neutral or white backgrounds, emphasizing the object itself without external context. Visuals are contained within defined areas, often with Ink Black (#000000) borders, creating a gallery-like presentation. There is a strong interplay of large, impactful images and smaller, supporting visuals, suggesting a curated exhibition. Icons (if present) are minimal, likely outlined, and monochrome, blending seamlessly with the typographic style. The imagery serves to showcase the product design, acting as the primary content without decorative distraction.

## Layout

The page primarily uses a max-width contained layout, though specific hero or section elements may appear full-bleed. The hero pattern features a dominant, often full-bleed or near full-bleed, striking image juxtaposed with large, impactful typography that directly states the brand name or key message. Subsequent sections alternate between large individual content blocks and grid-based layouts, such as 2-column or 3-column feature/product grids. Content arrangement often utilizes a clean, centered stack or side-by-side text and image pairing, with ample vertical spacing between sections. The navigation is minimal, likely a top bar, integrating seamlessly with the large display typography.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: none observed
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Header: Use Ink Black (#000000) for the 'Atlason' brand name (haas-grotesk-ds-pro, 48px, weight 500, lineHeight 0.8em). Subsequent navigation links (e.g., 'Works', 'More') should be Ink Black (#000000), haas-grotesk-tx-pro, 36px, weight 500, with a 1px Ink Black bottom border on hover. The header should align to a conceptual maximum width, but its background is Canvas White (#ffffff).
2. Create a Product Thumbnail Card: Background Canvas White (#ffffff). Image area should have a 1px Ink Black (#000000) border. Below the image, include product title text: Ink Black (#000000), haas-grotesk-tx-pro, 16px, weight 400. Apply 8px top padding and 10px left/right padding to the text block.
3. Create a Contact Information Block: Set the heading for each section (e.g., 'Visit', 'Connect') in Ink Black (#000000), haas-grotesk-tx-pro, 16px, weight 500. Body text (address, phone, email) should use Ink Black (#000000), haas-grotesk-tx-pro, 16px, weight 400. Ensure 8px vertical spacing between lines within the block. Links (email, phone) should have an Ink Black (#000000) 1px bottom border.

## Similar Brands

- **AIGA Design Archives** — Monochromatic palette, large impactful typography, and minimal UI elements focusing on showcasing design work.
- **Kinfolk Magazine** — Emphasis on photography, generous whitespace, and sophisticated, serif-alternative typography creating a refined editorial feel.
- **Apple Design Resources** — Clean white backgrounds, strong product focus, and minimal, precise typography used to highlight objects with clarity.
- **Dieter Rams Collection** — Dedicated to showcasing design, often with black and white imagery, and a UI that recedes to let the designs speak.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #b0b0b0;

  /* Typography — Font Families */
  --font-haas-grotesk-tx-pro: 'haas-grotesk-tx-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grotesk-ds-pro: 'haas-grotesk-ds-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.3;
  --text-body: 18px;
  --leading-body: 1.2;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1;
  --text-heading: 48px;
  --leading-heading: 0.8;
  --text-heading-lg: 106px;
  --leading-heading-lg: 0.77;
  --text-display: 288px;
  --leading-display: 0.77;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-product-card-white: #ffffff;
  --surface-overlay-black: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ash-gray: #b0b0b0;

  /* Typography */
  --font-haas-grotesk-tx-pro: 'haas-grotesk-tx-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grotesk-ds-pro: 'haas-grotesk-ds-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.3;
  --text-body: 18px;
  --leading-body: 1.2;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1;
  --text-heading: 48px;
  --leading-heading: 0.8;
  --text-heading-lg: 106px;
  --leading-heading-lg: 0.77;
  --text-display: 288px;
  --leading-display: 0.77;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-112: 112px;
}
```
