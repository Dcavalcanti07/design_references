# Maisonmargiela — Style Reference
> muted runway elegance

**Theme:** light

This design system evokes understated luxury and conceptual fashion, reminiscent of a high-end atelier's minimalist presentation. The dominant use of near-achromatic grays from `#121212` to `#f7f7f2` creates a sophisticated, muted backdrop. Typefaces are the primary vehicle for brand expression: the bespoke Margiela Sans with its numerous weights defines interactive elements and body text, while the subtly elegant Margiela Serif provides an exclusive touch to display large text. A complete absence of sharp accents or strong colors maintains a refined visual restraint, allowing product imagery to capture full attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greige Canvas | `#f7f7f2` | `--color-greige-canvas` | Primary page and content backgrounds, creating a soft, almost antique paper feel. |
| Coal Text | `#121212` | `--color-coal-text` | Dominant text color for headings, body, and navigation, providing high contrast against light backgrounds for legibility without harshness. |
| White Linen | `#ffffff` | `--color-white-linen` | Alternative background for certain elements or subtle accents, used sparingly to introduce slight variation. |
| Ash Detail | `#898989` | `--color-ash-detail` | Secondary text for less prominent information, and subtle borders or outlines. |
| Ghost Gray | `#eaeae6` | `--color-ghost-gray` | Background for subtle transitions or dividers, akin to a faint wash of color. |
| Deep Graphite | `#000000` | `--color-deep-graphite` | High-contrast text for specific headings or key information, often used interchangeably with Coal Text for maximum impact. |
| Subtle Accent | `#d6d6d1` | `--color-subtle-accent` | Underlines, subtle borders, and background hints, providing barely-there visual separation. |

## Tokens — Typography

### Margiela Sans — Primary typeface for all body text, navigation, buttons, and most interactive elements. Its extensive weight range allows for fine-grained hierarchy and emphasis within a consistent modern voice. · `--font-margiela-sans`
- **Substitute:** Inter
- **Weights:** 375, 400, 475, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px
- **Line height:** 1.00, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** 0.007em, 0.010em, 0.067em, 0.077em, 0.091em, 0.125em
- **Role:** Primary typeface for all body text, navigation, buttons, and most interactive elements. Its extensive weight range allows for fine-grained hierarchy and emphasis within a consistent modern voice.

### Margiela Serif — Used for distinctive, editorial elements, providing a classic, refined contrast to the modern sans-serif. Its minimal negative letter-spacing contributes to an elegant, tightly composed appearance at larger sizes. · `--font-margiela-serif`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 14px, 18px, 20px
- **Line height:** 1.30, 1.40
- **Letter spacing:** -0.004em, -0.002em
- **Role:** Used for distinctive, editorial elements, providing a classic, refined contrast to the modern sans-serif. Its minimal negative letter-spacing contributes to an elegant, tightly composed appearance at larger sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| label | 15px | 1.4 | — | `--text-label` |
| display-sm | 18px | 1.3 | -0.07px | `--text-display-sm` |
| display | 20px | 1.3 | -0.08px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 156 | 156px | `--spacing-156` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| inputs | 9999px |
| buttons | 0px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Text Only Button
**Role:** Primary interactive element for navigation and inline actions.

Background: transparent (rgba(0, 0, 0, 0)), Text: Coal Text (#121212), Border-top: transparent, Radius: 0px, Padding: 0px. This button style is visually light, relying on text color and hover states for interaction cues. Used for main navigation items like 'Mujer', 'Hombre'.

### Text Underline Button
**Role:** Secondary call-to-action or link within content.

Background: transparent (rgba(0, 0, 0, 0)), Text: Coal Text (#121212), Border-top: Coal Text (#121212), Radius: 0px, Padding: 0px. Features a subtle underline on the text, indicating a clickable action. Used for 'Descubra más' links.

### Muted Text Underline Button
**Role:** Tertiary action or less emphasized links.

Background: transparent (rgba(0, 0, 0, 0)), Text: rgba(26, 26, 26, 0.55), Border-top: rgba(26, 26, 26, 0.55), Radius: 0px, Padding: 0px. A desaturated version of the Text Underline Button for less prominent interactions.

### Search Field
**Role:** Global search input.

Background: transparent (rgba(0, 0, 0, 0)), Text: Deep Graphite (#000000), Border-top: rgba(18, 18, 18, 0.06), Radius: 9999px, Padding: 0px. Placeholder text is implied to be similar muted gray. The rounded border is a distinct design choice for inputs.

### Standard Input Field
**Role:** Form inputs for data entry.

Background: White Linen (#ffffff), Text: Coal Text (#121212), Border-top: rgba(26, 26, 26, 0.3), Radius: 0px, Padding: 0px vertical, 16px horizontal. Features a subtle, desaturated border and standard padding for form elements.

### Product Thumbnail
**Role:** Displays product images in grids or listings.

Typically full-bleed image within its container, no explicit borders or shadows. Relies on the surrounding whitespace for definition. Typography for product names or prices uses Margiela Sans at various weights over the image or below.

## Do's and Don'ts

### Do
- Do prioritize near-achromatic colors from the Greige Canvas (#f7f7f2) to Coal Text (#121212) scale for all primary UI elements and text.
- Do use Margiela Sans at various weights (375-700) for all functional text, headings, and interactive labels.
- Do apply 0px border-radius to all buttons and cards, maintaining a sharp, precise aesthetic.
- Do use 9999px border-radius exclusively for input fields, making them a distinct, subtly softer element.
- Do maintain minimal padding of 0px for navigation links, integrating them seamlessly into the header.
- Do use Margiela Serif for editorial content or distinctive display text to introduce an elevated, classic contrast.
- Do ensure interactive elements utilize the full color of Coal Text (#121212) or Deep Graphite (#000000) for clarity against lighter backgrounds.

### Don't
- Don't introduce vivid or saturated colors outside of product imagery; the palette is strictly muted.
- Don't use drop shadows; the design relies on subtle background color shifts for depth.
- Don't apply rounded corners to any element other than input fields.
- Don't use generic system fonts; Margiela Sans and Margiela Serif are integral to the brand identity.
- Don't use heavy borders or outlines on elements; rely on text color and subtle background changes for visual separation.
- Don't break the tight letter-spacing for Margiela Serif at display sizes; its elegance depends on precise typography.

## Imagery

The visual language is product-centric and highly art-directed. Photography features tight crops of products (shoes, garments) on muted, often textured studio backgrounds, emphasizing the product's form and material. There is an editorial, almost sculptural quality to the composition, focusing on the object itself rather than lifestyle context. The human models are often positioned to highlight the clothing's silhouette, captured with a slightly desaturated, cool-toned filter, enhancing the high-fashion aesthetic. Images are typically full-bleed within their sections, leveraging the entire viewport for visual impact without explicit masks or ornate treatments. Icons, like the search or cart icons, are minimalist, outlined, and monochromatic, blending seamlessly with the overall design.

## Layout

The site employs a full-bleed layout for hero sections, filling the entire viewport with large, impactful imagery and centered, minimalist text overlays. Content sections beneath the hero typically maintain a comfortable horizontal max-width but with variably loose vertical spacing. The navigation is a minimalist, fixed top bar using text-only links. Content blocks frequently consist of large, single images or stacked text and imagery, creating a spacious and gallery-like flow. There's a subtle grid structure for product listings, but the overall presentation prioritizes large-scale visuals over dense information, creating a luxurious, unhurried browsing experience.

## Agent Prompt Guide

Quick Color Reference:
- Text: #121212 (Coal Text)
- Background: #f7f7f2 (Greige Canvas)
- Input Background: #ffffff (White Linen)
- Muted Detail: rgba(26, 26, 26, 0.55)
- Input Border: rgba(18, 18, 18, 0.06)

Example Component Prompts:
- Create a primary navigation item: text 'Mujer' in Margiela Sans weight 400, size 16px, line-height 1, Coal Text (#121212), background transparent. No padding, no border.
- Generate a 'Descubre más' link: text 'Descubre más' in Margiela Sans weight 400, size 14px, line-height 1.4, Coal Text (#121212), with a border-top of 1px solid #121212. Background transparent, 0px radius, 0px padding.
- Design a search input field: background transparent, text in Margiela Sans, Deep Graphite (#000000), border-top 1px solid rgba(18, 18, 18, 0.06), border-radius 9999px, 0px padding. Placeholder text should be Ash Detail (#898989).
- Create a text heading for an editorial section: 'Primavera-Verano 2026' in Margiela Serif weight 400, size 20px, line-height 1.3, letter-spacing -0.08px, Coal Text (#121212).
- Generate a product card: background Greige Canvas (#f7f7f2), 0px border-radius, 16px padding. Product name in Margiela Sans weight 475, size 14px, Coal Text (#121212).

## Similar Brands

- **Acne Studios** — Shares a minimalist aesthetic driven by high-quality photography, muted palettes, and distinct typography.
- **The Row** — Similar emphasis on understated luxury, clean layouts, and product photography as the primary visual focus.
- **COS** — Features a near-monochromatic color scheme, strong reliance on typography for branding, and spacious product displays.
- **Vestiaire Collective (high-end sections)** — Employs a sophisticated, editorial approach with a focus on product presentation against neutral backgrounds, similar to a fashion magazine.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greige-canvas: #f7f7f2;
  --color-coal-text: #121212;
  --color-white-linen: #ffffff;
  --color-ash-detail: #898989;
  --color-ghost-gray: #eaeae6;
  --color-deep-graphite: #000000;
  --color-subtle-accent: #d6d6d1;

  /* Typography — Font Families */
  --font-margiela-sans: 'Margiela Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-margiela-serif: 'Margiela Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-label: 15px;
  --leading-label: 1.4;
  --text-display-sm: 18px;
  --leading-display-sm: 1.3;
  --tracking-display-sm: -0.07px;
  --text-display: 20px;
  --leading-display: 1.3;
  --tracking-display: -0.08px;

  /* Typography — Weights */
  --font-weight-w375: 375;
  --font-weight-regular: 400;
  --font-weight-w475: 475;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-156: 156px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-inputs: 9999px;
  --radius-buttons: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greige-canvas: #f7f7f2;
  --color-coal-text: #121212;
  --color-white-linen: #ffffff;
  --color-ash-detail: #898989;
  --color-ghost-gray: #eaeae6;
  --color-deep-graphite: #000000;
  --color-subtle-accent: #d6d6d1;

  /* Typography */
  --font-margiela-sans: 'Margiela Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-margiela-serif: 'Margiela Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-label: 15px;
  --leading-label: 1.4;
  --text-display-sm: 18px;
  --leading-display-sm: 1.3;
  --tracking-display-sm: -0.07px;
  --text-display: 20px;
  --leading-display: 1.3;
  --tracking-display: -0.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-156: 156px;

  /* Border Radius */
  --radius-full: 9999px;
}
```
