# Portal — Style Reference
> Frosted glass on a gradient dawn

**Theme:** light

Portal's visual system evokes a serene, organized workspace language: spacious layouts with ethereal background gradients and frosted glass components. Typography is confident yet understated, mixing a retro-inspired display face with a highly legible sans-serif for content. A dominant achromatic palette is punctuated by a singular vivid blue accent, giving interactive elements a distinct, clean 'power-on' feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Canvas | `#f7f7f7` | `--color-sky-canvas` | Page backgrounds, subtly textured card surfaces. The dominant light neutral that defines the working context |
| White Frost | `#ffffff` | `--color-white-frost` | Elevated card surfaces, navigation background, and text on darker backgrounds. Often appears with translucency or inset shadows |
| Ink | `#000000` | `--color-ink` | Primary text, borders, and main icon fills. Provides strong contrast against primary light surfaces |
| Charcoal Text | `#3e3e3e` | `--color-charcoal-text` | Secondary body text providing slightly softer contrast than primary Ink |
| Muted Ash | `#636363` | `--color-muted-ash` | Tertiary body text and helper labels, a softer alternative to Charcoal Text |
| Portal Blue | `#007aff` | `--color-portal-blue` | Primary action background, interactive element highlights, and decorative accents. This vivid blue is the single splash of color that signifies interaction and brand |
| Blue Aura | `#8cc2ff` | `--color-blue-aura` | Blue supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Perfectly Nineties Regular — Headline typeface for major page titles and key statements. Its unique, slightly retro character creates a distinctive brand voice. · `--font-perfectly-nineties-regular`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 36px, 48px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Headline typeface for major page titles and key statements. Its unique, slightly retro character creates a distinctive brand voice.

### Inter — Functional UI text, navigation, body copy, and secondary headings. Its generous x-height and clear forms ensure legibility across all sizes and weights. Used with specific font features for additional refinement. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 12px, 14px, 16px, 18px
- **Line height:** 1.20, 1.30, 1.35
- **Letter spacing:** -0.0200em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Functional UI text, navigation, body copy, and secondary headings. Its generous x-height and clear forms ensure legibility across all sizes and weights. Used with specific font features for additional refinement.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.35 | -0.28px | `--text-body` |
| heading | 36px | 1 | — | `--text-heading` |
| display | 48px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| navs | 22px |
| cards | 16px |
| icons | 22px |
| other | 22px |
| images | 22px |
| buttons | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(247, 247, 247) 0px 0px 0px 5px` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset, rgba(...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgb(247, 247, 247) 0px 0px 0px 1px` | `--shadow-subtle-4` |
| subtle-5 | `rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0...` | `--shadow-subtle-5` |
| subtle-6 | `rgb(140, 194, 255) 0px 1px 0px 1px inset` | `--shadow-subtle-6` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Ghost Button
**Role:** Call to action button with high contrast text and a 'ghost' background.

Background: Sky Canvas (#f7f7f7), Text: Ink (#000000), Border Radius: 50px, Padding: 0px 36px 0px 36px.

### Primary Action Button
**Role:** Filled call to action button, emphasizing interactions.

Background: Portal Blue (#007aff), Text: Ink (#000000), Border Radius: 50px, Padding: 0px 36px 0px 36px.

### Default Card
**Role:** Standard content container for features or information blocks.

Background: White Frost (#ffffff), Border Radius: 14px, Padding: 16px. No direct shadow, relying on background contrast.

### Frosted Card
**Role:** Enhanced content container with a translucent, semi-frosted appearance.

Background: rgba(255, 255, 255, 0.6), Border Radius: 24px, Padding: 20px. Features a backdrop blur filter for its translucent effect.

### Elevated Bubble Card
**Role:** Prominent, rounded card with a soft shadow for hierarchy.

Background: rgba(255, 255, 255, 0.8), Border Radius: 50px, Shadow: rgba(0, 0, 0, 0.03) 0px 0.6px 2.3px, rgba(0, 0, 0, 0.04) 0px 2.3px 8.7px, rgba(0, 0, 0, 0.08) 0px 10px 38px.

### Compact Card
**Role:** Smaller content container for lists or items needing less visual space.

Background: White Frost (#ffffff), Border Radius: 24px, Padding: 12px 20px.

## Do's and Don'ts

### Do
- Prioritize Sky Canvas (#f7f7f7) for main page backgrounds to maintain a light, airy feel.
- Use Portal Blue (#007aff) exclusively for primary interactive elements and crucial brand accents.
- Apply Perfect Nineties Regular for section titles at 36px or 48px, never for body text.
- Use Inter font with a letter-spacing of -0.0200em for all body and UI text.
- Ensure all buttons have a 50px border-radius, creating distinctive pill shapes.
- Leverage backdrop blur filters on translucent White Frost cards to achieve the frosted glass effect.
- Maintain a comfortable density with 10px element gaps and 16px card padding.

### Don't
- Avoid using multiple accent colors; Portal Blue (#007aff) is the only chromatic highlight.
- Do not use box-shadows to signify elevation for most cards; rely visually on background contrast and translucency.
- Do not vary border-radius significantly within component types; stick to defined radii for buttons, cards, etc.
- Do not use Perfect Nineties Regular for small text or functional labels, reserve it for display use.
- Avoid tight, dense layouts; maintain spaciousness with defined section and element gaps.
- Do not introduce heavy borders or harsh dividers; use soft inset shadows or subtle background differences for separation.
- Do not use dark backgrounds for entire sections unless they serve as a stylized hero element.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Sky Canvas | `#f7f7f7` | Base page background. Provides a soft, clean foundation for content. |
| 2 | White Frost | `#ffffff` | Primary card and elevated component background. Often appears with translucency (rgba(255,255,255,0.6)) and features backdrop blurring for a frosted effect. |

## Elevation

- **Elevated Bubble Card:** `rgba(0, 0, 0, 0.03) 0px 0.602187px 2.28831px -0.416667px, rgba(0, 0, 0, 0.04) 0px 2.28853px 8.69643px -0.833333px, rgba(0, 0, 0, 0.08) 0px 10px 38px -1.25px`
- **Primary Action Button (active/focus):** `rgb(140, 194, 255) 0px 1px 0px 1px inset`

## Imagery

This site uses product screenshots with a distinct 'frosted glass' or 'iOS-like' interface overlaid onto abstract, natural landscape photography. Imagery serves a decorative and atmospheric role, creating a sense of calm and aspiration. Screenshots are often contained within rounded rectangular frames and feature translucent UI elements, consistent with the overall frosted aesthetic. Icons are simple, outlined or filled, and primarily monochrome, supporting the clean UI.

## Layout

The page primarily uses a full-bleed layout for background imagery, specifically for the hero section with a gradient sky. Content areas are centered within a soft, visually contained structure, implicitly adhering to a max-width for readability. The hero features a large, centered headline over the atmospheric background, with a central call-to-action. Subsequent sections employ generous vertical spacing, suggesting a comfortable, unhurried reading experience. Content typically alternates between stacked text blocks and embedded product screenshots.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f7f7f7
border: #000000
accent: #007aff
primary action: #007aff (filled action)

Example Component Prompts:
Create a Primary Action Button: #007aff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a Default Card: Background White Frost (#ffffff), 14px border-radius, 16px padding. Inside, a heading 'About This Project' using Inter, 16px, 600 weight, #000000, and body text using Inter, 14px, #3e3e3e, letter-spacing -0.0200em.

Create a Frosted Card with Product Shot: A Frosted Card (rgba(255,255,255,0.6) background, 24px border-radius, 20px padding) containing a cropped product screenshot with 22px border radius, and text content below it. Ensure backdrop blur is applied to the card.

Create an Elevated Bubble Card: Background rgba(255, 255, 255, 0.8), 50px border-radius, with the specified shadow. Inside, simple text content with a Muted Ash (#636363) color.

## Backdrop Blur Philosophy

A core visual element of Portal is the use of `backdrop-filter: blur()` to create a 'frosted glass' effect on cards and other elevated elements. This achieves a distinct layered look, allowing background graphics to subtly show through while maintaining content legibility. This effect is crucial for lighter, semi-transparent surfaces like the Frosted Card (rgba(255,255,255,0.6)).

## Similar Brands

- **Linear** — Monochromatic UI with a single vivid accent color, restrained typography, and a focus on clean, spacious layouts.
- **Superhuman** — Emphasis on speed, minimal UI, distinct typography, and subtle component styling with a preference for light themes.
- **Amie** — Use of atmospheric background imagery, light canvas, and primary functional blues for interactive elements.
- **Apple (recent macOS/iOS UI)** — Prevalent use of translucency, backdrop blur, soft shadows, and rounded 'bubble' shapes for UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-canvas: #f7f7f7;
  --color-white-frost: #ffffff;
  --color-ink: #000000;
  --color-charcoal-text: #3e3e3e;
  --color-muted-ash: #636363;
  --color-portal-blue: #007aff;
  --color-blue-aura: #8cc2ff;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-perfectly-nineties-regular: 'Perfectly Nineties Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.35;
  --tracking-body: -0.28px;
  --text-heading: 36px;
  --leading-heading: 1;
  --text-display: 48px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-navs: 22px;
  --radius-cards: 16px;
  --radius-icons: 22px;
  --radius-other: 22px;
  --radius-images: 22px;
  --radius-buttons: 50px;

  /* Shadows */
  --shadow-subtle: rgb(247, 247, 247) 0px 0px 0px 5px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset, rgba(255, 255, 255, 0.4) 0px 0px 30px 0px inset, rgba(255, 255, 255, 0.8) 0px 0px 12px 0px inset;
  --shadow-subtle-3: rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset;
  --shadow-subtle-4: rgb(247, 247, 247) 0px 0px 0px 1px;
  --shadow-subtle-5: rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.15) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 3px 2px 0px;
  --shadow-subtle-6: rgb(140, 194, 255) 0px 1px 0px 1px inset;

  /* Surfaces */
  --surface-sky-canvas: #f7f7f7;
  --surface-white-frost: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-canvas: #f7f7f7;
  --color-white-frost: #ffffff;
  --color-ink: #000000;
  --color-charcoal-text: #3e3e3e;
  --color-muted-ash: #636363;
  --color-portal-blue: #007aff;
  --color-blue-aura: #8cc2ff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-perfectly-nineties-regular: 'Perfectly Nineties Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.35;
  --tracking-body: -0.28px;
  --text-heading: 36px;
  --leading-heading: 1;
  --text-display: 48px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-subtle: rgb(247, 247, 247) 0px 0px 0px 5px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset, rgba(255, 255, 255, 0.4) 0px 0px 30px 0px inset, rgba(255, 255, 255, 0.8) 0px 0px 12px 0px inset;
  --shadow-subtle-3: rgba(255, 255, 255, 0.6) 0px 0.5px 0px 0.5px inset;
  --shadow-subtle-4: rgb(247, 247, 247) 0px 0px 0px 1px;
  --shadow-subtle-5: rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.15) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 3px 2px 0px;
  --shadow-subtle-6: rgb(140, 194, 255) 0px 1px 0px 1px inset;
}
```
