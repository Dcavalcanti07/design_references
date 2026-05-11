# Ashton Bespoke — Style Reference
> Gallery on sandblasted stone

**Theme:** light

Ashton Bespoke evokes a muted, refined elegance with a focus on substantial typography and minimal ornamentation. The system relies on a serene, near-achromatic palette offset by a single deep, earthy accent. Layouts favor generous whitespace and classic arrangements, suggesting a gallery or showroom feel. Components are understated, allowing content and craftsmanship to take precedence, with interaction indicated through subtle shifts rather than bold calls to action.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Stone Canvas | `#e0ded8` | `--color-stone-canvas` | Page backgrounds, large content sections, subtle text backgrounds. Provides a warm, neutral base |
| Midnight Ink | `#262626` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Arctic White | `#ffffff` | `--color-arctic-white` | Navigation backgrounds, selected text for contrast on darker backgrounds. Used sparingly to highlight specific elements |
| Oxblood | `#38141b` | `--color-oxblood` | Footer background, decorative section fills. Provides a deep, rich accent, grounding the overall aesthetic with a sense of luxury and tradition |

## Tokens — Typography

### Arial — Fallback and utilitarian text where bespoke typography is not essential or for system-level elements. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.10
- **Letter spacing:** normal
- **Role:** Fallback and utilitarian text where bespoke typography is not essential or for system-level elements.

### Legquinne Vf — Headlines and prominent display text. The distinctive letter-spacing at larger sizes adds an air of bespoke craftsmanship and precision. · `--font-legquinne-vf`
- **Substitute:** Playfair Display
- **Weights:** 500
- **Sizes:** 32px, 46px, 60px
- **Line height:** 1.10
- **Letter spacing:** -0.99px at 60px, -0.68px at 46px, -0.54px at 32px
- **Role:** Headlines and prominent display text. The distinctive letter-spacing at larger sizes adds an air of bespoke craftsmanship and precision.

### Basisgrotesquepro — Body copy, navigation links, and descriptive text. Its clean, sans-serif nature provides modern readability against ornamental headlines. · `--font-basisgrotesquepro`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.00 at 18px leading, 1.10 at 15px leading, 1.30, 1.40
- **Letter spacing:** 0.31px at 15px, normal at 18px
- **Role:** Body copy, navigation links, and descriptive text. Its clean, sans-serif nature provides modern readability against ornamental headlines.

### Basisgrotesquepro 500 — Basisgrotesquepro 500 — detected in extracted data but not described by AI · `--font-basisgrotesquepro-500`
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.1
- **Letter spacing:** 0.021
- **Role:** Basisgrotesquepro 500 — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 15px | 1.1 | 0.31px | `--text-body` |
| body-lg | 18px | 1.3 | — | `--text-body-lg` |
| heading-sm | 32px | 1.1 | -0.54px | `--text-heading-sm` |
| heading | 46px | 1.1 | -0.68px | `--text-heading` |
| display | 60px | 1.1 | -0.99px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| menus | 4px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Navigation Link
**Role:** Interactive text link in the main navigation.

Uses Basisgrotesquepro, weight 400, size 18px, Midnight Ink text. Underlined with a 1px Midnight Ink border on hover, padding 5px bottom. Border radius 4px.

### Primary Headline
**Role:** Major section titles and hero text.

Legquinne Vf, weight 500, size 60px, line-height 1.1, letter-spacing -0.99px, Midnight Ink. Centered on Stone Canvas or within hero imagery.

### Body Text
**Role:** General paragraph content and descriptive text.

Basisgrotesquepro, weight 400, size 18px, Midnight Ink text on Stone Canvas background.

### Footer Background
**Role:** The background for the site's footer section.

Solid fill using Oxblood (#38141b), with text in Arctic White.

### Image Border
**Role:** Decorative border for featured images.

A 1px solid Midnight Ink (#262626) border around images, applied to the element itself or its container.

### Outlined Callout Link
**Role:** Prominent, subtly interactive link for navigation or action.

Basisgrotesquepro, weight 400, size about 16px, Midnight Ink text. Features a 1px Midnight Ink border with 1px top/bottom padding and 8px left/right padding. Radius 4px.

## Do's and Don'ts

### Do
- Prioritize Legquinne Vf for all headings (size 32px or larger) and Basisgrotesquepro for all body and UI text, ensuring font roles remain distinct.
- Use Stone Canvas (#e0ded8) as the primary background color for most content sections to maintain a bright, airy feel.
- Employ Midnight Ink (#262626) for all primary text, borders, and subtle interactive underlines, providing stark contrast against lighter backgrounds.
- Utilize generous vertical spacing between sections, aiming for at least 40px, to create comfortable breathing room and visual separation.
- Apply a 1px solid Midnight Ink border around all significant images or image containers to frame content elegantly.
- Ensure letter-spacing is precisely applied for Legquinne Vf headlines: -0.99px at 60px, -0.68px at 46px, -0.54px at 32px to capture the intentional visual rhythm.
- Use Oxblood (#38141b) exclusively for the footer background or other deep, rich accent sections, always paired with Arctic White text for readability.

### Don't
- Avoid introducing additional chromatic colors; the palette is intentionally restrained to Stone Canvas, Midnight Ink, Arctic White, and Oxblood.
- Do not use box-shadows or any form of elevation; the design relies on flat surfaces and strong typographic hierarchy for visual depth.
- Refrain from using `normal` letter-spacing for Legquinne Vf; the custom negative tracking is critical to its character.
- Do not use generic system fonts (e.g., Arial) for main headings or body copy except as a fallback.
- Avoid small, dense blocks of text; favor ample line-height and comfortable text spacing.
- Don't add strong accent colors to interactive states; interactions are implied via subtle underlines or color shifts within the existing neutral palette.
- Do not deviate from the established border radii of 4px for menu items and 12px for card or image containers; consistency builds refinement.

## Imagery

The visual language relies heavily on high-quality, product-focused photography that captures details of craftsmanship. Images are generally contained within rectangular frames, with a defined 1px Midnight Ink border, and are often placed in alternating text-and-visual layouts. There's an absence of abstract graphics or illustrations; the focus is entirely on tangible products and the creation process. Icons are minimal, likely consisting of simple, outlined forms that complement the restrained aesthetic. The density is moderate to high, with images playing a prominent role in showcasing the product, not just as decorative elements.

## Layout

The page structure favors a contained layout with a maximum width of 1440px, centered on the screen. The hero section is full-bleed, featuring a muted, often blurred, background image with a centered, prominent headline. Subsequent sections alternate between Stone Canvas and Oxblood backgrounds, creating a clear vertical rhythm. Content is typically arranged in two-column layouts pairing imagery with text, or in centered stacks. Card grids are used for showcasing projects, maintaining consistent spacing and framing. Navigation is a sticky top bar with minimal links and the brand logo, designed to be understated.

## Agent Prompt Guide

Quick Color Reference: 
text: #262626
background: #e0ded8
border: #262626
accent: #38141b
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: full-width background image, centered display headline 'BEAUTIFULLY HANDCRAFTED' using Legquinne Vf weight 500, 60px, line-height 1.1, letter-spacing -0.99px, #262626. 
Create a content section with a 2-column layout: Stone Canvas background. Left column: body copy 'Working from our atelier...' using Basisgrotesquepro weight 400, 18px, #262626. Right column: a product image framed with a 1px #262626 border.
Create a navigation menu: Arctic White background, containing links like 'Projects' using Basisgrotesquepro weight 400, 18px, #262626, with 5px bottom padding and a 1px #262626 border-bottom on hover, 4px radius.
Create a footer: Oxblood background with text 'Contact Us' using Basisgrotesquepro weight 400, 18px, #ffffff. Include a custom link '+44 (0)1730 779 337' using Basisgrotesquepro weight 400, 18px, #ffffff, with a 1px #262626 border (for a subtle interactive-looking element) and 8px horizontal padding, 4px radius.

## Similar Brands

- **B&B Italia** — High-end furniture brand with a similar focus on craftsmanship, minimalist layouts, and rich, subdued color palettes.
- **Devol Kitchens** — Emphasizes bespoke quality with a visual style that balances traditional elements, detailed photography, and understated typography.
- **Rimowa** — Premium luggage brand that uses carefully composed product photography, clean layouts, and a sophisticated, limited color scheme.
- **Frama** — Interior design and homeware brand with a strong emphasis on natural materials, a restrained color palette, and elegant, classic typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-stone-canvas: #e0ded8;
  --color-midnight-ink: #262626;
  --color-arctic-white: #ffffff;
  --color-oxblood: #38141b;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-legquinne-vf: 'Legquinne Vf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basisgrotesquepro: 'Basisgrotesquepro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basisgrotesquepro-500: 'Basisgrotesquepro 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.1;
  --tracking-body: 0.31px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.54px;
  --text-heading: 46px;
  --leading-heading: 1.1;
  --tracking-heading: -0.68px;
  --text-display: 60px;
  --leading-display: 1.1;
  --tracking-display: -0.99px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-menus: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-stone-canvas: #e0ded8;
  --color-midnight-ink: #262626;
  --color-arctic-white: #ffffff;
  --color-oxblood: #38141b;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-legquinne-vf: 'Legquinne Vf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basisgrotesquepro: 'Basisgrotesquepro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basisgrotesquepro-500: 'Basisgrotesquepro 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.1;
  --tracking-body: 0.31px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.54px;
  --text-heading: 46px;
  --leading-heading: 1.1;
  --tracking-heading: -0.68px;
  --text-display: 60px;
  --leading-display: 1.1;
  --tracking-display: -0.99px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
}
```
