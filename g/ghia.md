# Ghia — Style Reference
> Mediterranean terrace at sunset. Imagine terracotta hues meeting deep berry and cream tones, with products highlighted by soft, diffuse lighting.

**Theme:** light

Ghia's design evokes a feeling of vintage Mediterranean warmth mixed with modern clarity, like a sun-drenched European terrace. This is achieved through a primary palette of deep berry reds and creams, offset by a distinctive sage green and muted blue. Custom-designed typography, particularly the FHA Condensed French NC, lends a playful yet sophisticated hand-lettered quality, reinforcing the artisanal product. Circular pill shapes are reserved for interactive elements, softening the overall presentation while maintaining a clean, editorial layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sangria Berry | `#651c32` | `--color-sangria-berry` | Primary brand color for text, links, accents, and high-emphasis backgrounds. Signals luxury and depth, like a rich non-alcoholic wine. |
| Almond Cream | `#fef6ee` | `--color-almond-cream` | Primary background color and text for inverse sections. Provides a soft, warm canvas reflecting the brand's natural ingredients. |
| Blush Rose | `#ef6079` | `--color-blush-rose` | Accent color for prominent call-to-action buttons and interactive states. A vivid shade of red that suggests energy and vibrancy without being aggressive. |
| Coastal Fog | `#abd2eb` | `--color-coastal-fog` | Secondary accent color, often seen in interactive elements like input borders in a muted, desaturated blue. Provides a calming counterpoint to the warmer tones. |
| Frosted Sage | `#b6cfd0` | `--color-frosted-sage` | Specific button background color. A cool, desaturated green that adds a natural, earthy touch. |
| Earth Clay | `#e5e7eb` | `--color-earth-clay` | Subtle border and background for product cards. A light, almost imperceptible grey that adds structure without visual weight. |
| Warm Taupe | `#dfcac8` | `--color-warm-taupe` | Border color for certain interactive elements. A soft, reddish-brown neutral that complements the main palette. |
| Rich Soil | `#3e4938` | `--color-rich-soil` | Darkest neutral background color, hinting at deep, natural elements. |
| Summer Glow | `#f0e87b` | `--color-summer-glow` | Highlight color used sparingly for badges or icons. This vivid yellow adds a pop of cheerful energy. |
| Pure White | `#ffffff` | `--color-pure-white` | Text against dark backgrounds, or pure white product backdrops. Provides crisp contrast. |
| Deepest Ink | `#000000` | `--color-deepest-ink` | Iconography and occasional text where maximum contrast is required. |

## Tokens — Typography

### Vivey 22 Positive — Body text, navigation links, and smaller captions. Its clean legibility ensures all supportive content is approachable. · `--font-vivey-22-positive`
- **Substitute:** Segoe UI
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 18px
- **Line height:** 1.00, 1.25, 1.30, 1.33, 1.43, 1.50, 1.56
- **Letter spacing:** normal
- **Role:** Body text, navigation links, and smaller captions. Its clean legibility ensures all supportive content is approachable.

### FHA Condensed French NC — Display headings and prominent calls to action. Its distinctive condensed and slightly playful character is a core part of the brand's visual identity, evoking a traditional, artisanal feel. · `--font-fha-condensed-french-nc`
- **Substitute:** Oswald
- **Weights:** 400
- **Sizes:** 24px, 30px, 32px, 38px, 44px, 48px, 52px, 72px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.33
- **Letter spacing:** normal
- **Role:** Display headings and prominent calls to action. Its distinctive condensed and slightly playful character is a core part of the brand's visual identity, evoking a traditional, artisanal feel.

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| other | 24px |
| buttons | 9999px |
| productTags | 16px |

### Layout

- **Section gap:** 96px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary CTA Button
**Role:** Call to Action

Background: Blush Rose (#ef6079), Text: Pure White (#ffffff), Border Radius: 16px. Padding: 0px 16px (vertical padding managed by line-height of text).

### Outline Ghost Button
**Role:** Secondary Action

Background: transparent, Text: Sangria Berry (#651c32), Border: Sangria Berry (#651c32). Border Radius: 0px. Used for subtle actions like 'OUR STORY'.

### Pill Button
**Role:** Action/Filter

Background: Frosted Sage (#b6cfd0), Text: Sangria Berry (#651c32), Border Radius: 9999px. Padding: 4px 16px. Used for category filters or small, rounded CTAs.

### Navigation Link
**Role:** Navigation

Background: transparent, Text: Almond Cream (#fef6ee), no explicit padding or radius. Used in the header navigation.

### Pricing Input Field
**Role:** Product Configuration

Background: transparent, Text: Coastal Fog (#abd2eb), Border: Earth Clay (#e5e7eb) at bottom only. No border radius. Padding: 12px 0px. Used for editable quantity or selection fields.

## Do's and Don'ts

### Do
- Use FHA Condensed French NC (Oswald) for all display headings to convey the brand's unique character.
- Apply Sangria Berry (#651c32) as the primary brand color for text and interactive elements, reserving Blush Rose (#ef6079) for primary call-to-action buttons.
- Ensure all buttons intended for interactive clicks use a 9999px border radius for a distinct 'pill' shape, or 16px for a soft cornered rectangle.
- Employ Almond Cream (#fef6ee) as the dominant background color for light sections to maintain a warm and inviting feel.
- Maintain a clear visual hierarchy by limiting Frosted Sage (#b6cfd0) and Coastal Fog (#abd2eb) to specific functional elements like pill buttons or subtle input indicators.
- Utilize Vivey 22 Positive (Segoe UI) at its various weights and sizes for all body text, links, and captions to ensure legibility and a consistent textual voice.

### Don't
- Do not introduce new color tones outside of the established palette of reds, creams, sage, and muted blues.
- Avoid using sharp, 0px border radii on primary interactive components; reserve them for decorative elements or non-interactive containers.
- Do not deviate from the specified font families or their primary roles; FHA Condensed French NC is for display, Vivey 22 Positive for body.
- Refrain from using strong, visible box shadows; the design relies on color contrasts and background changes for depth.
- Do not use generic system greys; utilize Earth Clay (#e5e7eb) or Warm Taupe (#dfcac8) for subtle borders and backgrounds.
- Avoid excessive use of vivid accent colors; Blush Rose (#ef6079), Frosted Sage (#b6cfd0), and Coastal Fog (#abd2eb) are intended as controlled accents, not dominant hues.

## Imagery

Photography is the primary visual medium, focusing almost exclusively on product shots. Products are often arranged artfully, sometimes with liquid being poured, showcasing the drink's color and texture. Treatment is typically clean and well-lit, with products frequently against pure white and some instances of natural surface backgrounds. Imagery is contained, rather than full-bleed, often cropped tightly on the product itself. Illustrations are minimal, seen in small, stylized icons like the '0% alcohol' badges, which are flat, single-color, and aligned with the brand's specific shades.

## Layout

The page uses a flexible, content-out layout that appears full-bleed but often contains content within implied horizontal boundaries, giving sections room to breathe. The hero section features a large, often full-width background image with centered, prominent FHA Condensed French NC typography. Section rhythm alternates between strong brand-colored backgrounds (Sangria Berry) and lighter, Almond Cream (#fef6ee) sections, creating clear content blocks. Content arrangement frequently features centered stacked content and product grids, with a strong emphasis on product photography. The navigation bar is a sticky top bar, providing persistent access across the site.

## Agent Prompt Guide

### Quick Color Reference
- Text (Sangria Berry): `#651c32`
- Background (Almond Cream): `#fef6ee`
- Primary CTA (Blush Rose): `#ef6079`
- Border (Earth Clay): `#e5e7eb`
- Accent (Frosted Sage): `#b6cfd0`

### 3-5 Example Component Prompts
1. Create a hero section with a background image. Overlay a headline: 'ALL OF THE SPIRIT, NONE OF THE BOOZE' in FHA Condensed French NC, size 72px, weight 400, color Almond Cream (#fef6ee). Below, place a Primary CTA Button: background Blush Rose (#ef6079), text Pure White (#ffffff), 16px border radius, text 'SHOP BESTSELLERS' in Vivey 22 Positive, size 16px, weight 700. Provide 24px vertical padding on the button text.
2. Design a product grid card. Background color transparent, 0px border radius. Include a product image at the top. Below the image, add a product title 'APÉRITIF' in FHA Condensed French NC, size 24px, weight 400, color Sangria Berry (#651c32). Add a description immediately below: 'Vibrant, fresh and satisfyingly bitter. Great for mixing, just add bubbles.' in Vivey 22 Positive, size 14px, weight 400, color Sangria Berry (#651c32). At the bottom, include 'Add to cart - $38' as an Outline Ghost Button for Sangria Berry (#651c32) with a 0px border radius.
3. Create a pill filter button: background Frosted Sage (#b6cfd0), text Sangria Berry (#651c32), 9999px border radius. Text 'APÉRITIF', in Vivey 22 Positive, size 14px, weight 400. Padding 4px vertical, 16px horizontal.
4. Generate a header navigation bar. Background Sangria Berry (#651c32). Links 'Shop', 'Build Your Own Bundle', 'Recipes', 'Subscription', 'Find In Store' in Vivey 22 Positive, size 16px, weight 400, color Almond Cream (#fef6ee). No underlines or borders.

## Similar Brands

- **KIN Euphorics** — Shares a non-alcoholic beverage focus with a sophisticated, product-centered visual style and a distinct brand color palette.
- **Olipop** — Utilizes custom display typography and a colorful, playful aesthetic for a beverage brand, similar to Ghia's use of FHA Condensed French NC.
- **Brightland** — High-quality food product e-commerce with a focus on elegant photography, custom branding, and a distinct, warm color palette.
- **Seedlip** — Another premium non-alcoholic spirit, featuring a refined and often dark-mode aesthetic with elegant product photography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sangria-berry: #651c32;
  --color-almond-cream: #fef6ee;
  --color-blush-rose: #ef6079;
  --color-coastal-fog: #abd2eb;
  --color-frosted-sage: #b6cfd0;
  --color-earth-clay: #e5e7eb;
  --color-warm-taupe: #dfcac8;
  --color-rich-soil: #3e4938;
  --color-summer-glow: #f0e87b;
  --color-pure-white: #ffffff;
  --color-deepest-ink: #000000;

  /* Typography — Font Families */
  --font-vivey-22-positive: 'Vivey 22 Positive', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fha-condensed-french-nc: 'FHA Condensed French NC', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.5;
  --text-xs-2: 12px;
  --leading-xs-2: 1.33;
  --text-sm: 13px;
  --leading-sm: 1.25;
  --text-sm-2: 14px;
  --leading-sm-2: 1.43;
  --text-base: 15px;
  --leading-base: 1.33;
  --text-base-2: 16px;
  --leading-base-2: 1.5;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-2xl: 24px;
  --leading-2xl: 1.33;
  --text-3xl: 30px;
  --leading-3xl: 1.2;
  --text-3xl-2: 32px;
  --leading-3xl-2: 1.1;
  --text-4xl: 38px;
  --leading-4xl: 1.1;
  --text-4xl-2: 44px;
  --leading-4xl-2: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-other: 24px;
  --radius-buttons: 9999px;
  --radius-producttags: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sangria-berry: #651c32;
  --color-almond-cream: #fef6ee;
  --color-blush-rose: #ef6079;
  --color-coastal-fog: #abd2eb;
  --color-frosted-sage: #b6cfd0;
  --color-earth-clay: #e5e7eb;
  --color-warm-taupe: #dfcac8;
  --color-rich-soil: #3e4938;
  --color-summer-glow: #f0e87b;
  --color-pure-white: #ffffff;
  --color-deepest-ink: #000000;

  /* Typography */
  --font-vivey-22-positive: 'Vivey 22 Positive', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fha-condensed-french-nc: 'FHA Condensed French NC', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.5;
  --text-xs-2: 12px;
  --leading-xs-2: 1.33;
  --text-sm: 13px;
  --leading-sm: 1.25;
  --text-sm-2: 14px;
  --leading-sm-2: 1.43;
  --text-base: 15px;
  --leading-base: 1.33;
  --text-base-2: 16px;
  --leading-base-2: 1.5;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-2xl: 24px;
  --leading-2xl: 1.33;
  --text-3xl: 30px;
  --leading-3xl: 1.2;
  --text-3xl-2: 32px;
  --leading-3xl-2: 1.1;
  --text-4xl: 38px;
  --leading-4xl: 1.1;
  --text-4xl-2: 44px;
  --leading-4xl-2: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 9999px;
}
```
