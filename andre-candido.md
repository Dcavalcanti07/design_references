# André Cândido — Style Reference
> Editorial clarity on parchment

**Theme:** light

André Cândido's visual system evokes a refined, editorial clarity. It pairs classic serif typography for headlines with modern sans-serif for body text, creating a dynamic yet grounded aesthetic. The palette is predominantly black and white, punctuated by a single vibrant yellow accent that signifies highlight and interaction. Components are generally flat with subtle rounded corners, prioritizing content and strong typographic hierarchy over heavy visual treatments.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111118` | `--color-midnight-ink` | Primary text, button backgrounds, dark section backgrounds, subtle borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button text on dark backgrounds, primary borders |
| Graphite | `#222222` | `--color-graphite` | Navigation text, secondary icon fills |
| Steel Gray | `#7c7c7c` | `--color-steel-gray` | Muted helper text, copyright text, hairline borders |
| Silver Mist | `#bdbdbd` | `--color-silver-mist` | Muted borders for descriptive text blocks or lists |
| Mellow Yellow | `#ffed00` | `--color-mellow-yellow` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Editorial New — Main headlines and display text, using a light 200 weight to create an authoritative, literary feel rather than shouting. · `--font-editorial-new`
- **Substitute:** Lora, Playfair Display
- **Weights:** 200
- **Sizes:** 48px, 70px, 72px, 160px
- **Line height:** 1.00, 1.10, 1.20
- **Role:** Main headlines and display text, using a light 200 weight to create an authoritative, literary feel rather than shouting.

### PP Mori — All body text, navigation items, buttons, captions, and secondary headings. The consistent positive letter-spacing adds airiness and distinctness even at smaller sizes. · `--font-pp-mori`
- **Substitute:** Inter, Manrope
- **Weights:** 200, 400, 600
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 24px, 72px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** 0.1070em
- **Role:** All body text, navigation items, buttons, captions, and secondary headings. The consistent positive letter-spacing adds airiness and distinctness even at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.107px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.107px | `--text-body-sm` |
| subheading | 18px | 1.4 | 0.107px | `--text-subheading` |
| heading-sm | 24px | 1.2 | 0.107px | `--text-heading-sm` |
| heading-lg | 48px | 1.1 | — | `--text-heading-lg` |
| display | 72px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| circle | 800px |
| buttons | 24px |
| navigation | 80px |

### Layout

- **Page max-width:** 1360px
- **Section gap:** 71px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call to action for key conversions.

Filled with Midnight Ink (#111118), text in Canvas White (#ffffff). Rounded corners set to 24px for a soft pill shape. Padding is 10px vertical and 16px horizontal.

### Outlined Call to Action Button
**Role:** Secondary action or prompt within a dark section.

Text in Canvas White (#ffffff), with a 1px Canvas White border. Has a 24px border-radius, giving it a pill-like structure. Padding is 8px vertical and 16px horizontal, slightly more compact than the filled variant.

### Project Card
**Role:** Displaying project showcases or portfolio items.

Background is Canvas White (#ffffff) with an 8px border-radius. No explicit shadow, relying on spacing for separation. Inner content has 24px padding on all sides.

### Icon-only Badge (Circular)
**Role:** Decorative or small functional indicator, like 'Available Now' stamp.

Ghost background, text in Midnight Ink (#111118). Often styled with large rounded corners like 800px or 150px to form circles or soft ovals around single elements.

### Navigation Link
**Role:** Site navigation items in the header.

Text in Graphite (#222222). Underlines appear on hover/focus, typically 1px solid Graphite.

### Informational Card
**Role:** Small, interactive content blocks like questionnaire prompts.

Canvas White (#ffffff) background, 8px border-radius, with 24px padding. Content is primarily text using PP Mori type scale.

## Do's and Don'ts

### Do
- Use Editorial New (200 weight) for all primary headlines, ensuring generous line heights to preserve its elegant feel.
- Apply a positive letter-spacing of 0.1070em via PP Mori for all body, nav, and button text to maintain clarity and consistent density.
- Utilize Midnight Ink (#111118) for all primary fills and Canvas White (#ffffff) for backgrounds to emphasize the high-contrast aesthetic.
- Employ a base spacing unit of 8px, using multiples like 16px for element gaps and 24px for card padding to establish a comfortable density.
- Apply a 24px border-radius to all buttons for a distinct, soft pill shape, and 8px for cards to maintain subtle rounding.
- Introduce Mellow Yellow (#ffed00) strictly as an accent for highlights, small interactive indicators, and decorative punctuation, never for large blocks of color.
- Ensure all interactive elements have 1px solid borders using either Midnight Ink or Canvas White, clearly defining their boundaries without heavy styling.

### Don't
- Avoid using multiple vibrant colors; stick to the black, white, and single yellow accent palette to maintain visual calm.
- Do not use heavy shadows or gradients on components; surfaces should remain flat or rely on subtle borders for definition.
- Refrain from tight line heights on Editorial New; its light weight requires more vertical space to breathe.
- Do not vary paragraph letter-spacing widely; keep the PP Mori 0.1070em spacing consistent for all smaller textual elements.
- Avoid excessive imagery; the system emphasizes typography and clean UI elements.
- Do not use sharp 0px radii for main interactive elements like buttons; soft curves define their interactive nature.
- Do not introduce additional gray tones beyond Midnight Ink, Graphite, Steel Gray, and Silver Mist, as this dilutes the achromatic foundation.

## Imagery

Imagery is sparingly used, primarily for product screenshots, abstract geometric shapes, or simple, contained headshots. Photography, when present (e.g., headshots), is clean, well-lit, and product-focused or professional. Illustrations are abstract, geometric, and often feature saturated pops of color against a clean white or dark background, serving as decorative accents or explanatory visuals. Icons are minimalist, outlined, and monochromatic, usually in Midnight Ink, contributing to the clean, modern aesthetic. The density is text-dominant, with imagery acting as visual breaks or supporting elements rather than focal points.

## Layout

The page uses a maximum width of 1360px, maintaining a centered, contained layout for most content. The hero section features a large, centered headline (Editorial New) over a white background, creating an immediate editorial impact. Subsequent sections alternate between white and Midnight Ink (#111118) backgrounds, establishing a distinct visual rhythm. Content is typically arranged in left-aligned blocks or flexible card grids (e.g., the 6-card display of informational cards). Vertical spacing between sections is generous (71px), contributing to a comfortable, uncrowded feel. The navigation is a persistent top bar, with a prominent 'Work with me' button on the right.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #111118
- background: #ffffff
- border: #bdbdbd
- accent: #ffed00
- primary action: #111118 (filled action)

**Example Component Prompts:**
- Create a hero section: Canvas White background. Headline 'Thoughtful design for brilliant brands' using Editorial New 72px, 200 weight, #111118, with 1.0 line-height. Below, a navigation bar with 'Work with me' Primary Filled Button (Midnight Ink #111118, Canvas White #ffffff text, 24px radius, 10px vertical/16px horizontal padding).
- Generate a 'Project Card': Canvas White #ffffff background, 8px border-radius, 24px padding. Title 'Brand refresh for SuperHi' in PP Mori 18px, 400 weight, #111118, letter-spacing 0.107em.
- Design a footer section: Midnight Ink #111118 background. Copyright text '© 2026 André Cândido. All rights reserved.' in PP Mori 12px, 400 weight, Steel Gray #7c7c7c, letter-spacing 0.107em. Include an 'Outlined Call to Action Button' with Canvas White #ffffff text and border, 24px radius, 8px vertical/16px horizontal padding.

## Similar Brands

- **Stripe** — Similar pairing of a classic serif for display text with a clean sans-serif for UI, and high-contrast, sparse color palettes.
- **Linear** — Monochromatic base with a single accent color for interaction, and emphasis on clean typography and spacious layouts.
- **Figma** — Uses a very clean, interface-focused approach with subtle card treatments and a strong typographic hierarchy.
- **SuperHi** — High-quality site with strong typography and a clear, minimal aesthetic, often using a limited color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111118;
  --color-canvas-white: #ffffff;
  --color-graphite: #222222;
  --color-steel-gray: #7c7c7c;
  --color-silver-mist: #bdbdbd;
  --color-mellow-yellow: #ffed00;

  /* Typography — Font Families */
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.107px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.107px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.107px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.107px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --text-display: 72px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --page-max-width: 1360px;
  --section-gap: 71px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 80px;
  --radius-full-3: 150px;
  --radius-full-4: 800px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-circle: 800px;
  --radius-buttons: 24px;
  --radius-navigation: 80px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111118;
  --color-canvas-white: #ffffff;
  --color-graphite: #222222;
  --color-steel-gray: #7c7c7c;
  --color-silver-mist: #bdbdbd;
  --color-mellow-yellow: #ffed00;

  /* Typography */
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.107px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.107px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.107px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.107px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --text-display: 72px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 80px;
  --radius-full-3: 150px;
  --radius-full-4: 800px;
}
```
