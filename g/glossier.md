# Glossier — Style Reference
> Photographic vibrancy on crisp white canvas. Imagine a brightly lit product shot, vibrant and rich, placed on a pristine white gallery wall.

**Theme:** light

Glossier's visual style is a 'modern classic' — grounded in a stark, high-contrast black and white palette, then infused with bursts of vibrant, youthful color. The interplay of minimalist typography and photography, punctuated by a signature vivid yellow, creates an aspirational yet approachable feel. Sharp rectangular forms dominate the layout, establishing a sense of order, softened slightly by the inviting warmth of the product imagery.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, iconography, solid button backgrounds, borders. Establishes a bold and clear presence against light backgrounds. |
| Snow | `#ffffff` | `--color-snow` | Page backgrounds, card surfaces, button text. Provides a clean, expansive backdrop. |
| Ash | `#666666` | `--color-ash` | Secondary text, subtle instructional text, input placeholders. A softer contrast for less prominent information. |
| Fog | `#e8e8e8` | `--color-fog` | Badge backgrounds, input borders. Provides a subtle distinction without visual noise. |
| Whisper | `#f7f7f7` | `--color-whisper` | Subtle background for navigation or section dividers. Used for delicate background differentiation. |
| Lemon Zest | `#fff116` | `--color-lemon-zest` | Primary call-to-action buttons, accent highlights, brand logotype. Its vivid saturation provides energetic focal points. |
| Twilight Indigo | `#0600ff` | `--color-twilight-indigo` | New product badges. Offers a clear, distinct visual indicator for new items. |

## Tokens — Typography

### Apercu — Primary typeface for all body text, headings, navigational elements, and buttons. Its clean, geometric sans-serif quality maintains a professional yet approachable tone. · `--font-apercu`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 20px, 32px
- **Line height:** 1.00, 1.09, 1.15, 1.17, 1.20, 1.23, 1.30, 1.40, 1.43, 1.46, 1.63, 1.67, 1.70
- **Letter spacing:** 0.002em at 12px, 0.003em at 14px, 0.04em at 16px
- **Role:** Primary typeface for all body text, headings, navigational elements, and buttons. Its clean, geometric sans-serif quality maintains a professional yet approachable tone.

### Apercu Mono — Used sparingly for technical or code-like elements where fixed-width spacing is desired, providing subtle typographic variation. · `--font-apercu-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Used sparingly for technical or code-like elements where fixed-width spacing is desired, providing subtle typographic variation.

### GTStandard-M — A secondary display font, used for specific highlighted text blocks, contributing to a distinctive brand voice. · `--font-gtstandard-m`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** A secondary display font, used for specific highlighted text blocks, contributing to a distinctive brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.24px | `--text-caption` |
| body | 14px | 1.43 | 0.42px | `--text-body` |
| heading | 20px | 1.23 | — | `--text-heading` |
| display | 32px | 1.09 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 34 | 34px | `--spacing-34` |
| 40 | 40px | `--spacing-40` |
| 41 | 41px | `--spacing-41` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 40-80px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call-to-action

Solid black background (Ink #000000), white text (Snow #FFFFFF), 0px border-radius, 8px vertical padding, 16px horizontal padding. Font: Apercu Bold 16px, normal letter-spacing, line-height 1.23.

### Secondary Action Button
**Role:** Supporting call-to-action

Transparent background, black text (Ink #000000) and 1px bottom border. 0px padding. Font: Apercu Regular 16px, normal letter-spacing.

### Outlined Product Card Button
**Role:** Product interaction button on cards

Faint gray background (240,240,240), black text (Ink #000000), 0px border-radius, 6px top padding, 5px right/bottom/left padding, 1px black border. Font: Apercu Bold 14px, normal letter-spacing.

### Search Input Field
**Role:** Collecting user input for search

White background (Snow #FFFFFF), gray text (Ash #666666), 1px border with Fog (#e8e8e8) color, 0px border-radius, 22px top padding, 8px right/left padding, 6px bottom padding. Font: Apercu Regular 16px.

### New Badge
**Role:** Highlighting new products or features

Dark blue background (Twilight Indigo #0600ff), black text (Ink #000000), 0px border-radius, 1px vertical padding, 8px horizontal padding. Font: Apercu Regular 12px.

### Info Message Badge
**Role:** General information badge

Light gray background (Fog #e8e8e8), black text (Ink #000000), 0px border-radius, 1px vertical padding, 8px horizontal padding. Font: Apercu Regular 12px.

## Do's and Don'ts

### Do
- Maintain a primary color palette of Ink (#000000) for text and Snow (#FFFFFF) for backgrounds to ensure high contrast and readability.
- Utilize Apercu for all text elements; vary weights (400, 500, 700) and sizes (12px, 14px, 16px, 20px, 32px) to establish clear hierarchy.
- Apply precise letter-spacing adjustments to Apercu typography: 0.002em at 12px, 0.003em at 14px, and 0.04em at 16px for optimal visual balance.
- Reserve Lemon Zest (#fff116) strictly for primary call-to-action buttons and brand accents to maximize its impact and recognition.
- Implement a consistent 0px border-radius across all buttons, cards, and input fields to uphold the sharp, modern aesthetic.
- Use 8px for element spacing by default, increasing to 14px for more significant separations between related content blocks.

### Don't
- Avoid introducing gradients or shadows; the aesthetic relies on flat colors and crisp edges to define elements.
- Do not use highly saturated colors other than Lemon Zest (#fff116) or Twilight Indigo (#0600ff) in prominent UI elements, as this dilutes brand identity.
- Refrain from varying border-radius values; all UI elements should consistently use 0px radius.
- Do not deviate from Apercu as the primary brand font; alternative fonts like Apercu Mono or GTStandard-M have highly specific and limited use cases.
- Avoid organic or highly decorative imagery; favor clean, product-focused photography or abstract visuals.
- Do not dilute the Lemon Zest (#fff116) accent by applying it to secondary actions or informational text.

## Imagery

The visual language is characterized by high-key, product-focused photography and clean UI. Photography is typically full-bleed or large, emphasizing product details, often with strong directional light and rich but natural color saturation. Images are contained within sharp, rectangular forms, with no visible masking or overlapping. Illustrations, if present (not clearly visible in screenshots), adhere to a flat, clean aesthetic. Icons are simple, outlined, and monochromatic (Ink #000000). The imagery's primary role is to showcase products and evoke an aspirational, lifestyle mood without being overtly staged, balancing product focus with atmospheric context. Imagery dominates hero sections and category blocks, giving the site a visually rich yet uncluttered feel.

## Layout

The page primarily uses a max-width contained model for most content, centered on the page, with some full-bleed hero sections. The hero banner often features a large image with an overlaying text block or brand element, creating visual drama. Section rhythm is fluid, with consistent vertical spacing but alternating content arrangements—sometimes a large hero, then a two-column grid, followed by a multi-column product display. Content is arranged in alternating text-left/image-right or centered stacks. Product grids utilize a 4-column layout. Spacing between sections is comfortable, allowing elements to breathe. Navigation consists of a sticky top bar with clear product categories and utility icons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Ink)
- Background: #FFFFFF (Snow)
- CTA: #fff116 (Lemon Zest)
- Border: #E8E8E8 (Fog)
- Accent: #0600ff (Twilight Indigo)

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: background #fff116 (Lemon Zest), text #000000 (Ink), radius 0px, padding 8px 16px, font Apercu Bold 16px, line-height 1.23.
2. Design a new product badge: background #0600ff (Twilight Indigo), text #000000 (Ink), radius 0px, padding 1px 8px, font Apercu Regular 12px.
3. Implement a standard body text paragraph: color #000000 (Ink), font Apercu Regular 14px, line-height 1.43, letter-spacing 0.42px.
4. Build a product listing card: transparent background, 0px border-radius, 0px padding. Inside, an image above a product title (Apercu Regular 16px, #000000) and price (Apercu Regular 14px, #666666). Add an 'Add to Bag' button (background rgba(240,240,240,1), text #000000, 0px borderRadius, padding 6px 5px, 1px black border) centered at the bottom.

## Similar Brands

- **Fenty Beauty** — Shares a brand identity built on high-quality product photography and a strong, singular accent color against a clean, minimal backdrop.
- **Aesop** — Exhibits a similar commitment to minimalist typography and high-contrast text on clean backgrounds, emphasizing product aesthetics over overly decorative UI.
- **Drunk Elephant** — Utilizes a clean, white-dominant aesthetic with select vibrant color accents to highlight products and maintain a fresh, approachable feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-snow: #ffffff;
  --color-ash: #666666;
  --color-fog: #e8e8e8;
  --color-whisper: #f7f7f7;
  --color-lemon-zest: #fff116;
  --color-twilight-indigo: #0600ff;

  /* Typography — Font Families */
  --font-apercu: 'Apercu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono: 'Apercu Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.24px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.42px;
  --text-heading: 20px;
  --leading-heading: 1.23;
  --text-display: 32px;
  --leading-display: 1.09;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-41: 41px;

  /* Layout */
  --section-gap: 40-80px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-snow: #ffffff;
  --color-ash: #666666;
  --color-fog: #e8e8e8;
  --color-whisper: #f7f7f7;
  --color-lemon-zest: #fff116;
  --color-twilight-indigo: #0600ff;

  /* Typography */
  --font-apercu: 'Apercu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono: 'Apercu Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.24px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.42px;
  --text-heading: 20px;
  --leading-heading: 1.23;
  --text-display: 32px;
  --leading-display: 1.09;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-41: 41px;
}
```
