# Arsenijs Fabrica — Style Reference
> Midnight product showcase

**Theme:** dark

Arsenijs Fabrica employs a darkly atmospheric, brand-forward aesthetic with crisp typography and a striking orange accent. The primary surfaces are dark or black, providing a dramatic backdrop for product imagery and text. Typography is compact and precise, maintaining readability against the deep backgrounds. Color is used sparingly but effectively as functional indicators and eye-catching highlights, creating a sense of focused activity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary surface background, dark text on light backgrounds, strong borders |
| Ghost White | `#ffffff` | `--color-ghost-white` | Light surface background, primary text on dark backgrounds, ghost button text and borders |
| Charcoal | `#0d1717` | `--color-charcoal` | Secondary surface background, dark text, and subtle borders |
| Deep Gray | `linear-gradient(90deg, rgb(17, 17, 17), rgb(17, 17, 17), rgb(255, 255, 255), rgb(17, 17, 17), rgb(17, 17, 17))` | `--color-deep-gray` | Secondary dark background, text, and descriptive borders; Used for background blending and subtle visual transitions in large sections, creating a dynamic gradient experience |
| Light Ash | `#eeeeee` | `--color-light-ash` | Subtle card and element borders on light surfaces |
| Muted Gray | `#818181` | `--color-muted-gray` | Auxiliary text, secondary information on darker backgrounds |
| Valencia Orange | `#ff8562` | `--color-valencia-orange` | Decorative highlights, outlined interactive elements, link color |
| Sunset Fire | `#f7651a` | `--color-sunset-fire` | Accent elements, occasional background fill for highlighted cards or sections. Also used for icons and hover states |
| Flame Glow | `#f15730` | `--color-flame-glow` | Primary Call to Action button background, small illustrative fills |

## Tokens — Typography

### Onest — Primary brand typeface for all headings, body text, navigation, and buttons. Its wide range of weights and optical adjustments with letter-spacing allow it to cover everything from bold declarations to detailed captions with a modern, technical feel. · `--font-onest`
- **Substitute:** Inter
- **Weights:** 200, 300, 400, 500, 600, 800
- **Sizes:** 9px, 10px, 11px, 12px, 14px, 15px, 16px, 18px, 20px, 21px, 23px, 32px, 36px, 48px, 52px, 152px
- **Line height:** 0.90-1.60
- **Letter spacing:** -0.0910em at 152px, -0.0560em at 52px, -0.0190em at 9px
- **Role:** Primary brand typeface for all headings, body text, navigation, and buttons. Its wide range of weights and optical adjustments with letter-spacing allow it to cover everything from bold declarations to detailed captions with a modern, technical feel.

### Times — Used for occasional descriptive text and specific content blocks, providing a classic contrast to the primary typeface. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for occasional descriptive text and specific content blocks, providing a classic contrast to the primary typeface.

### Arial — Used for very small contextual text and specific utility elements. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for very small contextual text and specific utility elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.6 | -0.028px | `--text-body` |
| subheading | 18px | 1.35 | -0.037px | `--text-subheading` |
| heading-sm | 23px | 1.21 | -0.045px | `--text-heading-sm` |
| heading | 36px | 1.09 | -0.052px | `--text-heading` |
| heading-lg | 52px | 1.04 | -0.056px | `--text-heading-lg` |
| display | 152px | 0.9 | -0.091px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 90 | 90px | `--spacing-90` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 600px |
| images | 15px |
| buttons | 55px |
| default | 10px |
| interactiveElements | 30px |

### Layout

- **Section gap:** 50px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Ghost Navigation Button
**Role:** Navigation and secondary actions

Text: Ghost White (#FFFFFF), Background: transparent, Border: transparent. Used for top-level navigation items that reveal their interactive nature on hover.

### Primary Action Button
**Role:** Main calls to action

Background: Flame Glow (#f15730), Text: Ghost White (#FFFFFF), Borderr: transparent, Radius: 55px, Padding: 12.7px vertical, 30px horizontal. Commands attention with its saturated brand color.

### Outlined CTA Button
**Role:** Secondary calls to action or for visual diversity

Background: transparent, Text: Ghost White (#FFFFFF), Border: 1px solid Ghost White (#FFFFFF), Radius: 600px. Presents a prominent action without the full weight of a filled button.

### Ghost Text Button
**Role:** Informational or tertiary actions on light backgrounds

Background: transparent, Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000). For subtle interactive elements that should integrate with surrounding body text.

### Default Card
**Role:** Content grouping

Background: transparent, Border: none, Radius: 0px. Used for flexible content containers that blend seamlessly with the background.

### Rounded Transparent Card
**Role:** Subtly separated content blocks

Background: transparent, Border: 1px solid Light Ash (#eeeeee), Radius: 10px. Provides a hint of separation without adding visual weight.

### Dark Rounded Card
**Role:** Elevated content groupings on dark backgrounds

Background: Midnight Ink (#000000), Border: none, Radius: 10px. Creates a distinct content panel on the primary dark canvas.

### Light Rounded Card
**Role:** Content grouping on light backgrounds

Background: #FBFBFB (derived from --BGColorPassive token), Border: none, Radius: 15px. Offers a softer, lighter surface for product displays or information. Padding: 20px.

### Input Field
**Role:** User data entry

Background: Flame Glow (#f15730), Placeholder text: Ghost White (#FFFFFF), Border: none, Radius: 55px. Visually aligns with primary action calls due to matching background color.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#000000) or Deep Gray (#111111) for backgrounds and Ghost White (#ffffff) for primary text to maintain the dramatic contrast.
- Use Flame Glow (#f15730) exclusively for primary calls to action, such as 'Send' or 'Shop Now' buttons, to maximize impact.
- Apply Onest typeface for all textual elements. Use the detailed letter-spacing values to ensure proper optical balance at different sizes.
- Employ rounded borders extensively: 55px for primary buttons, 600px for pill-shaped elements and subtle 10px or 15px for cards.
- Maintain compact spacing, with a consistent 10px element gap and 20px card padding, to keep the UI dense and focused.
- Use Valencia Orange (#ff8562) only for subtle highlights, interactive links, or outlined elements, avoiding large blocks of color.
- Ensure headings use a high contrast color against their background (e.g., Ghost White on Midnight Ink) and apply negative letter-spacing for visual tightness.

### Don't
- Avoid using bright, disparate colors; stick to the defined black, white, and orange palette.
- Do not deviate from the Onest typeface for primary UI elements; reserve Times and Arial for specific, limited applications only.
- Refrain from adding arbitrary shadows or complex gradients that are not explicitly defined, as elevation is kept minimal.
- Do not introduce large empty spaces; the design system favors a compact and information-dense layout.
- Avoid using Valencia Orange (#ff8562) as a solid background for large sections or primary buttons, as its role is for highlights and outlines.
- Do not use generic square corners; almost all interactive and content areas feature a defined border radius.
- Avoid making text too small without adequate line height due to the compact nature of the typeface; ensure readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Base | `#000000` | Primary page background and foundational dark surfaces. |
| 1 | Charcoal Canvas | `#0d1717` | Secondary background or slightly elevated dark areas, like some content cards or footers. |
| 2 | Deep Gray Panel | `#111111` | Subtle dark panels or dividers, indicating slight separation or emphasis. |
| 3 | Ghost White Overlay | `#ffffff` | Lightest surface, used for overlays, modals (like the skincare community popup), or sections requiring direct contrast against dark backgrounds. |

## Imagery

This site prominently features product images and lifestyle photography. Product visuals often appear as tight crops, potentially full-bleed, emphasizing textures and details. There are also abstract background images that appear to be product-related. Images are treated with softened edges, using radii like 15px. The overall density leans towards image-heavy, with visuals taking significant space, contributing to the brand-forward visual identity.

## Layout

The page primarily uses a full-bleed structure, with content often spanning the entire viewport width, particularly in the hero section. The hero prominently features a large visual with centered, overlaid text. Sections maintain a consistent vertical rhythm, though specific section gaps are flexible. Content is typically arranged in clear, often centrally aligned blocks, providing a focused, editorial feel. Navigation is a sticky top bar, providing persistent access across the experience.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #eeeeee
accent: #ff8562
primary action: #f15730 (filled action)

Example Component Prompts:
1. Create a Hero section: Midnight Ink (#000000) background. Headline 'brand of modern and innovative cosmetics' in Onest weight 800, size 52px, Ghost White (#ffffff), letter-spacing -0.056em. Subtext 'safe cosmetics that can be bright, smil delicious and be aestheticity pleasing' in Onest weight 400, size 18px, Ghost White (#ffffff), line height 1.35. Add a 'shop now' button: background transparent, text Ghost White (#ffffff), border 1px solid Ghost White (#ffffff), radius 600px.
2. Create an Email Signup Modal: Ghost White (#ffffff) background. Title 'skincare community' in Onest weight 600, size 23px, Midnight Ink (#000000). Body text 'discount on first purchase. join the community and get 10% off your first purchase' in Onest weight 400, size 14px, Midnight Ink (#000000). Input field 'Email': background Flame Glow (#f15730), placeholder Ghost White (#ffffff), radius 55px, padding 12.7px vertical, 30px horizontal. 'Send' button: background Ghost White (#ffffff), text Midnight Ink (#000000), radius 55px, padding 12.7px vertical, 30px horizontal.
3. Create a Product Card: Dark Rounded Card with Midnight Ink (#000000) background, 10px radius. Product title in Onest weight 500, size 16px, Ghost White (#ffffff). Price in Onest weight 400, size 14px, Valencia Orange (#ff8562).

## Similar Brands

- **Glossier** — Employs clean typography with strong imagery and a focused color palette, similar to Arsenijs Fabrica's curated brand presence.
- **Aesop** — Utilizes a sophisticated, often dark/monochrome aesthetic with specific typography choices and an emphasis on product-forward visuals, reflecting a similar premium feel.
- **Dribbble (dark mode)** — Features a dark canvas with strong typographical treatments and controlled accent colors, creating an atmosphere of focused content presentation.
- **Byte** — Uses bold, often large typography on dark backgrounds with a single vivid accent color for interactive elements, echoing the dramatic contrast.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-charcoal: #0d1717;
  --color-deep-gray: #111111;
  --gradient-deep-gray: linear-gradient(90deg, rgb(17, 17, 17), rgb(17, 17, 17), rgb(255, 255, 255), rgb(17, 17, 17), rgb(17, 17, 17));
  --color-light-ash: #eeeeee;
  --color-muted-gray: #818181;
  --color-valencia-orange: #ff8562;
  --color-sunset-fire: #f7651a;
  --color-flame-glow: #f15730;

  /* Typography — Font Families */
  --font-onest: 'Onest', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: -0.028px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.037px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.21;
  --tracking-heading-sm: -0.045px;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --tracking-heading: -0.052px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.04;
  --tracking-heading-lg: -0.056px;
  --text-display: 152px;
  --leading-display: 0.9;
  --tracking-display: -0.091px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-90: 90px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 30px;
  --radius-full: 55px;
  --radius-full-2: 60px;
  --radius-full-3: 600px;
  --radius-full-4: 3000px;

  /* Named Radii */
  --radius-pill: 600px;
  --radius-images: 15px;
  --radius-buttons: 55px;
  --radius-default: 10px;
  --radius-interactiveelements: 30px;

  /* Surfaces */
  --surface-midnight-base: #000000;
  --surface-charcoal-canvas: #0d1717;
  --surface-deep-gray-panel: #111111;
  --surface-ghost-white-overlay: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-charcoal: #0d1717;
  --color-deep-gray: #111111;
  --color-light-ash: #eeeeee;
  --color-muted-gray: #818181;
  --color-valencia-orange: #ff8562;
  --color-sunset-fire: #f7651a;
  --color-flame-glow: #f15730;

  /* Typography */
  --font-onest: 'Onest', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: -0.028px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.037px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.21;
  --tracking-heading-sm: -0.045px;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --tracking-heading: -0.052px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.04;
  --tracking-heading-lg: -0.056px;
  --text-display: 152px;
  --leading-display: 0.9;
  --tracking-display: -0.091px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-90: 90px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 30px;
  --radius-full: 55px;
  --radius-full-2: 60px;
  --radius-full-3: 600px;
  --radius-full-4: 3000px;
}
```
