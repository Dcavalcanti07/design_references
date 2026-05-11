# Advene — Style Reference
> Whispered luxury on soft parchment.

**Theme:** light

Advene employs a serene, luxurious aesthetic defined by soft, desaturated earth tones and precise typography. The layout is spacious, using generous whitespace to highlight product imagery and textual content. Visual hierarchy is established through subtle variations in neutral backgrounds and font weights, with a distinct absence of aggressive chromatic accents, allowing the natural textures and colors of the products to stand out. Components maintain a ghost-like quality, prioritizing borders over backgrounds for interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, dark backgrounds, navigation elements |
| Parchment | `#eeefea` | `--color-parchment` | Canvas background, secondary surface |
| Faded Stone | `#dfe0db` | `--color-faded-stone` | Main canvas background |
| Ash | `#808080` | `--color-ash` | Muted text, subtle borders, secondary information |
| Warm White | `#ffffff` | `--color-warm-white` | Card backgrounds, button backgrounds, text on dark surfaces |
| Dark Charcoal | `#121212` | `--color-dark-charcoal` | Bold text, prominent borders |
| Muted Earth | `#c1c19f` | `--color-muted-earth` | Accent backgrounds, subtle highlights, background for descriptive text sections |
| Golden Ochre | `#9a9260` | `--color-golden-ochre` | Decorative accents, active states, borders for subtle links |
| Pistachio Custard | `#f7dc99` | `--color-pistachio-custard` | Illustrative fills, branding elements, soft background panels |
| Deep Plum | `#66040c` | `--color-deep-plum` | Strong accent details, icon strokes, borders for certain visual elements. This color feels like a signature feature in the data with very high prominence, despite the hue |
| Cerulean Link | `#007aff` | `--color-cerulean-link` | Outlined button borders, interactive link color |
| Deep Mocha | `#41312c` | `--color-deep-mocha` | Subtle background panels for content blocks |
| Dusty Rose | `#936a4c` | `--color-dusty-rose` | Subtle background panels for content blocks. Distinct from other neutrals by its slight warm tint |
| Cool Gray Mist | `#bdd0d6` | `--color-cool-gray-mist` | Subtle background panels for content blocks |
| Muted Terracotta | `#762b29` | `--color-muted-terracotta` | Subtle background panels for content blocks |
| Warm Pebble | `#aa917d` | `--color-warm-pebble` | Subtle background panels for content blocks |
| Antique Ivory | `#f8e9ac` | `--color-antique-ivory` | Soft accent for background panels, less saturated than Pistachio Custard |
| Earth Gradient Dark | `linear-gradient(45deg, rgb(228, 219, 205) 0%, rgb(228, 219, 205) 49%, rgb(0, 0, 0) 50%, rgb(0, 0, 0) 100%)` | `--color-earth-gradient-dark` | Decorative split gradient backgrounds, transitioning to black for contrast |
| Earth Gradient Light | `linear-gradient(45deg, rgb(204, 187, 146) 0%, rgb(204, 187, 146) 49%, rgb(255, 255, 255) 50%, rgb(255, 255, 255) 100%)` | `--color-earth-gradient-light` | Decorative split gradient backgrounds, transitioning to white |

## Tokens — Typography

### Signifier — Primary headings and body text. The varying line heights for different sizes give a deliberate, considered feel for text blocks. · `--font-signifier`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 14px, 18px, 24px
- **Line height:** 1.20, 1.30, 1.67
- **Role:** Primary headings and body text. The varying line heights for different sizes give a deliberate, considered feel for text blocks.

### Pitch — Small, highly tracked text for labels, categories, and meta information. The expanded letter spacing at small sizes enhances readability and a refined feel. · `--font-pitch`
- **Substitute:** monospace
- **Weights:** 400, 700
- **Sizes:** 11px
- **Line height:** 1.60, 1.70
- **Letter spacing:** 0.0640em
- **Role:** Small, highly tracked text for labels, categories, and meta information. The expanded letter spacing at small sizes enhances readability and a refined feel.

### Arial — Utility text for small buttons and icons. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Utility text for small buttons and icons.

### GTStandard-M — Specialized body text or subheadings, offering an alternative sans-serif voice. · `--font-gtstandard-m`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.50
- **Role:** Specialized body text or subheadings, offering an alternative sans-serif voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.6 | 0.64px | `--text-caption` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.67 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 20px |
| buttons | 20px |
| linksLarge | 41px |

### Layout

- **Section gap:** 60px
- **Card padding:** 0px
- **Element gap:** 6px

## Components

### Ghost Button - Light Text
**Role:** Ghost button with light text on dark backgrounds.

backgroundColor: rgba(0, 0, 0, 0), color: Warm White (#ffffff), borderColor: Warm White (#ffffff), borderRadius: 20px, paddingTop: 0px, paddingRight: 0px, paddingBottom: 0px, paddingLeft: 0px.

### Ghost Button - Dark Text
**Role:** Ghost button with dark text on light backgrounds.

backgroundColor: rgba(0, 0, 0, 0), color: Midnight Ink (#000000), borderColor: Midnight Ink (#000000), borderRadius: 0px, paddingTop: 0px, paddingRight: 0px, paddingBottom: 0px, paddingLeft: 0px.

### Outlined Action Button
**Role:** Outlined action button using the accent color.

backgroundColor: rgba(0, 0, 0, 0), color: Cerulean Link (#007aff), borderColor: Cerulean Link (#007aff), borderRadius: 0px, paddingTop: 0px, paddingRight: 0px, paddingBottom: 0px, paddingLeft: 0px.

### Pill Button - White Fill
**Role:** Pill-shaped button with white fill, black text and border.

backgroundColor: Warm White (#ffffff), color: Midnight Ink (#000000), borderColor: Midnight Ink (#000000), borderRadius: 20px, paddingTop: 0px, paddingRight: 10px, paddingBottom: 0px, paddingLeft: 10px.

### Input Field
**Role:** Standard input field for forms.

backgroundColor: rgba(0, 0, 0, 0), color: Midnight Ink (#000000), borderTopColor: Midnight Ink (#000000), borderRadius: 0px, paddingTop: 15px, paddingRight: 50px, paddingBottom: 15px, paddingLeft: 15px.

### Information Card (Transparent)
**Role:** Transparent card for displaying content without strong visual boundaries.

backgroundColor: rgba(0, 0, 0, 0), borderRadius: 0px, boxShadow: none, paddingTop: 0px, paddingRight: 0px, paddingBottom: 0px, paddingLeft: 0px.

## Do's and Don'ts

### Do
- Prioritize borders and text over solid backgrounds for interactive elements to maintain a lightweight feel.
- Use Signifier for all core text elements, adjusting line height based on size for optimal rhythm.
- Employ Pitch with 0.0640em letter spacing for all small labels and meta-information to enhance legibility and visual texture.
- Maintain generous whitespace in all layouts, using 60px as the standard section gap.
- Utilize Faded Stone (#dfe0db) or Parchment (#eeefea) as primary background colors for sections, allowing content to breathe.
- Apply a 20px border radius to all buttons and links for a soft, consistent shape.
- Introduce Muted Earth (#c1c19f) or Pistachio Custard (#f7dc99) sparingly as background accents for distinct content blocks, ensuring they remain subtle and don't overwhelm the page.

### Don't
- Avoid solid, vibrant backgrounds for primary buttons or calls to action; prefer outlined or ghost styles.
- Do not use letter-spacing on Signifier text, as it is designed to be read without custom tracking.
- Resist using multiple highly saturated colors together; stick to the desaturated brand palette with one or two accent colors for emphasis.
- Do not introduce strong shadows or heavy elevation effects; the design relies on flat, layered surfaces.
- Avoid custom font sizes for Pitch; always use the specified 11px with its defined line heights and letter spacing.
- Do not use dark backgrounds for entire sections unless specifically detailed as a full-bleed hero or footer, as the theme is predominantly light.
- Do not apply padding directly to cards (0px), instead, manage spacing between elements inside the card content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Faded Stone Canvas | `#dfe0db` | Primary page background, base canvas |
| 1 | Parchment Surface | `#eeefea` | Secondary background for sections and content blocks |
| 2 | Warm White Card | `#ffffff` | Card backgrounds, elevated content areas |
| 3 | Muted Earth Panel | `#c1c19f` | Accentuated content panels, visually distinct blocks |

## Imagery

The imagery style is a mix of high-key product photography and atmospheric portraiture. Product shots feature tight crops of items on clean, often white or lightly textured backgrounds, emphasizing form and material. Photography of models appears to be candid and desaturated, sometimes in black and white or with muted, earthy tones, allowing for an understated, editorial feel. Abstract graphics for branding use soft, organic shapes with solid fills, typically in the brand's muted yellow or gold tones. Icons are minimalist, outlined, and monochromatic, matching the thin strokes of the ghost buttons. The density is image-heavy in hero sections, with large visuals dominating the viewport, while textual sections feature imagery primarily for decorative atmosphere or as small, focused product highlights.

## Layout

The page primarily uses a full-bleed layout, where visual content often extends to the viewport edges, especially in hero sections. However, core textual content is contained within a centered column with ample horizontal padding. The hero pattern features a split-screen or large background image with centered or offset text overlays. Sections are delineated by variations in background color (alternating light neutrals and subtle earthy tones) rather than strong dividers, creating a seamless visual flow. Content arrangement frequently alternates between text-left/image-right compositions and centered stacks for feature descriptions. There's an underlying grid for product displays or feature listings, but its column count is variable. The overall density is spacious, allowing elements to breathe. Navigation is a minimal top bar, with 'Shop' and 'About' links centered, and utility links (Account, Cart) aligned to the right. A secondary 'Process' navigation is vertically aligned on the right side of the screen.

## Agent Prompt Guide

Quick Color Reference:
text: Midnight Ink (#000000)
background: Faded Stone (#dfe0db)
border: Midnight Ink (#000000)
accent: Deep Plum (#66040c)
primary action: #007aff (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #007aff border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Design a ghost button for a dark section: text 'Shop Advene' in Warm White (#ffffff) using Signifier 14px, with a border of Warm White (#ffffff) and a 20px border radius. Padding should be 0px on all sides, text aligned center.
3. Implement a content section with a background accent: Use Muted Earth (#c1c19f) as background. Headline 'Our Story' in Midnight Ink (#000000) using Signifier 24px, lineHeight 1.67. Body text 'We believe that beauty...' in Midnight Ink (#000000) using Signifier 18px.
4. Construct an input field: Background rgba(0,0,0,0), text color Midnight Ink (#000000), borderTopColor Midnight Ink (#000000), padding 15px top/bottom, 50px right, 15px left, 0px border radius.

## Similar Brands

- **A.P.C.** — Shares a similar muted color palette, focus on quality product photography, and a clean, almost editorial layout. Minimalist typography.
- **Everlane** — Uses a similar approach to spacious, achromatic layouts with very subtle pops of color and a focus on product presentation over aggressive marketing visuals.
- **The Row** — Known for its understated luxury, minimal design, and emphasis on texture and material over overt branding, reflected in the subtle color shifts and clean typography of Advene.
- **COS** — Features clean, well-structured layouts with ample white space, strong product imagery, and a limited, sophisticated color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-parchment: #eeefea;
  --color-faded-stone: #dfe0db;
  --color-ash: #808080;
  --color-warm-white: #ffffff;
  --color-dark-charcoal: #121212;
  --color-muted-earth: #c1c19f;
  --color-golden-ochre: #9a9260;
  --color-pistachio-custard: #f7dc99;
  --color-deep-plum: #66040c;
  --color-cerulean-link: #007aff;
  --color-deep-mocha: #41312c;
  --color-dusty-rose: #936a4c;
  --color-cool-gray-mist: #bdd0d6;
  --color-muted-terracotta: #762b29;
  --color-warm-pebble: #aa917d;
  --color-antique-ivory: #f8e9ac;
  --color-earth-gradient-dark: #e4dbcd;
  --gradient-earth-gradient-dark: linear-gradient(45deg, rgb(228, 219, 205) 0%, rgb(228, 219, 205) 49%, rgb(0, 0, 0) 50%, rgb(0, 0, 0) 100%);
  --color-earth-gradient-light: #ccbb92;
  --gradient-earth-gradient-light: linear-gradient(45deg, rgb(204, 187, 146) 0%, rgb(204, 187, 146) 49%, rgb(255, 255, 255) 50%, rgb(255, 255, 255) 100%);

  /* Typography — Font Families */
  --font-signifier: 'Signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pitch: 'Pitch', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.6;
  --tracking-caption: 0.64px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.67;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 0px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 41px;

  /* Named Radii */
  --radius-links: 20px;
  --radius-buttons: 20px;
  --radius-linkslarge: 41px;

  /* Surfaces */
  --surface-faded-stone-canvas: #dfe0db;
  --surface-parchment-surface: #eeefea;
  --surface-warm-white-card: #ffffff;
  --surface-muted-earth-panel: #c1c19f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-parchment: #eeefea;
  --color-faded-stone: #dfe0db;
  --color-ash: #808080;
  --color-warm-white: #ffffff;
  --color-dark-charcoal: #121212;
  --color-muted-earth: #c1c19f;
  --color-golden-ochre: #9a9260;
  --color-pistachio-custard: #f7dc99;
  --color-deep-plum: #66040c;
  --color-cerulean-link: #007aff;
  --color-deep-mocha: #41312c;
  --color-dusty-rose: #936a4c;
  --color-cool-gray-mist: #bdd0d6;
  --color-muted-terracotta: #762b29;
  --color-warm-pebble: #aa917d;
  --color-antique-ivory: #f8e9ac;
  --color-earth-gradient-dark: #e4dbcd;
  --color-earth-gradient-light: #ccbb92;

  /* Typography */
  --font-signifier: 'Signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pitch: 'Pitch', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.6;
  --tracking-caption: 0.64px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.67;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 41px;
}
```
