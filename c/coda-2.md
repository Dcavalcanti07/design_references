# Coda — Style Reference
> digital-first canvas

**Theme:** light

Coda operates on a 'digital-first canvas' aesthetic, mixing a soft, near-white background with bold, condensed typography and large, organic shapes in deep forest green. The system leverages strong visual contrast between high-impact headlines and more conservative body text. Components are minimalist with generous corner radii, emphasizing functional clarity over decorative elements, punctuated by dynamic shapes and a striking brand green.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Creme | `#f8f9eb` | `--color-canvas-creme` | Primary page and card backgrounds, serving as a clean, warm base |
| Carbon Black | `#000000` | `--color-carbon-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. |
| Obsidian Gray | `#202020` | `--color-obsidian-gray` | Secondary text, button backgrounds, and subtle borders for depth |
| Forest Green | `#003d21` | `--color-forest-green` | Dominant brand color for large background shapes, card backgrounds, and key accents. Signifies growth and nature |
| Sage Mist | `#c0c2a9` | `--color-sage-mist` | Muted text, subtle borders, and background accents where a soft, near-gray tone is needed |
| Mid-tone Gray | `#5a5a4f` | `--color-mid-tone-gray` | Darker secondary text and icon coloration |
| Light Taupe | `#7c7d76` | `--color-light-taupe` | Muted subheadings and descriptive text elements |
| Pale Ash | `#edeee1` | `--color-pale-ash` | Subtle button borders |
| Aura Green | `#aafdc0` | `--color-aura-green` | Highlight elements, decorative borders, and text accents drawing immediate attention |
| Soft Teal | `#b0f4ff` | `--color-soft-teal` | Decorative background fills for visual variety in cards |
| Lavender Mist | `#d3beff` | `--color-lavender-mist` | Decorative background fills for visual variety in cards |
| Rose Blush | `#ffc0e6` | `--color-rose-blush` | Decorative background fills for visual variety in cards |
| Blue Violet | `#041668` | `--color-blue-violet` | Accent text and decorative element colors |
| Deep Plum | `#2d0078` | `--color-deep-plum` | Accent text and decorative element colors |
| Dark Magenta | `#3f0929` | `--color-dark-magenta` | Accent text and decorative element colors |

## Tokens — Typography

### abcMonumentGrotesk — Primary display font for all headings, impactful calls to action, and prominent text elements. Its condensed structure and variable weight create a modern, direct tone. Use 'normal' letter spacing for smaller sizes, 'tight' for display headings to emphasize impact. · `--font-abcmonumentgrotesk`
- **Substitute:** system-ui
- **Weights:** 400, 500, 800
- **Sizes:** 16px, 18px, 21px, 22px, 25px, 34px, 45px, 54px, 63px, 72px, 134px
- **Line height:** 0.90, 1.00, 1.02, 1.13, 1.30, 1.43, 1.50, 1.71
- **Letter spacing:** -0.01, 0.01
- **Role:** Primary display font for all headings, impactful calls to action, and prominent text elements. Its condensed structure and variable weight create a modern, direct tone. Use 'normal' letter spacing for smaller sizes, 'tight' for display headings to emphasize impact.

### ui-sans-serif — Fallback and general UI text where a system font is appropriate for readability and less emphasis than 'abcMonumentGrotesk'. Primarily for body and link text. · `--font-ui-sans-serif`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Fallback and general UI text where a system font is appropriate for readability and less emphasis than 'abcMonumentGrotesk'. Primarily for body and link text.

### jetBrainsMono — Monospace font for badges, data points, or areas requiring a technical, precise aesthetic. Used sparingly for specific functional emphasis. · `--font-jetbrainsmono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 0.90, 1.00, 1.20, 1.37
- **Role:** Monospace font for badges, data points, or areas requiring a technical, precise aesthetic. Used sparingly for specific functional emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.43 | — | `--text-body-lg` |
| subheading | 21px | 1.13 | — | `--text-subheading` |
| heading-sm | 25px | 1.13 | — | `--text-heading-sm` |
| heading | 34px | 1.13 | — | `--text-heading` |
| heading-lg | 45px | 1.02 | -0.45px | `--text-heading-lg` |
| display | 72px | 0.9 | -0.72px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 9 | 9px | `--spacing-9` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 18 | 18px | `--spacing-18` |
| 27 | 27px | `--spacing-27` |
| 36 | 36px | `--spacing-36` |
| 45 | 45px | `--spacing-45` |
| 63 | 63px | `--spacing-63` |
| 72 | 72px | `--spacing-72` |
| 89 | 89px | `--spacing-89` |
| 107 | 107px | `--spacing-107` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 22.3625px |
| large | 26.835px |
| badges | 9999px |
| buttons | 8.94498px |
| default | 13.4175px |
| extraLarge | 44.725px |

### Layout

- **Section gap:** 63px
- **Card padding:** 13px
- **Element gap:** 9px

## Components

### Ghost Header Navigation Link
**Role:** Navigation item within the header.

backgroundColor=rgba(0, 0, 0, 0), color=Carbon Black, no specific borderRadius, padding=0px. Text is abcMonumentGrotesk, weight 400.

### Pill Button with Outline
**Role:** Secondary action button, often for 'Learn More' or 'Go' actions.

backgroundColor=rgba(0, 0, 0, 0), color=Carbon Black, border=1px solid Carbon Black, borderRadius=13.4175px, padding=13.4175px. Text is abcMonumentGrotesk.

### Filled Primary Button
**Role:** Primary call to action.

backgroundColor=Obsidian Gray, color=Canvas Creme, borderRadius=8.94498px. Text is abcMonumentGrotesk, weight 400.

### Ghost Button with Light Text
**Role:** Action button on dark backgrounds.

backgroundColor=rgba(0, 0, 0, 0), color=Canvas Creme, border=1px solid Canvas Creme, borderRadius=13.4175px. Text is abcMonumentGrotesk, weight 400.

### Transparent Card
**Role:** Informational card with no background fill.

backgroundColor=rgba(0, 0, 0, 0), borderRadius=22.3625px.

### Canvas Creme Card
**Role:** Content container on the main Canvas Creme background.

backgroundColor=Canvas Creme, borderRadius=22.3625px.

### Carbon Black Card
**Role:** Content container used to create visual contrast.

backgroundColor=Carbon Black, borderRadius=0px.

### Pill Badge (Light text on transparent)
**Role:** Small, descriptive tag on dark backgrounds.

backgroundColor=rgba(0, 0, 0, 0), color=Canvas Creme, borderRadius=9999px, padding=0px 8.94498px.

### Pill Badge (Light text on transparent, slightly opaque)
**Role:** Small, descriptive tag with subtle transparency.

backgroundColor=rgba(248, 249, 235, 0.2), color=Canvas Creme, borderRadius=9999px, padding=0px 8.94498px.

## Do's and Don'ts

### Do
- Use Canvas Creme (#f8f9eb) as the dominant background for most sections.
- Apply abcMonumentGrotesk, weight 800, with letter spacing -0.01em for all major headlines to ensure high-impact visual presence.
- Utilize Forest Green (#003d21) for large, decorative background shapes and elements to establish strong brand identity.
- Implement a default border-radius of 22.3625px for cards and 8.94498px for filled buttons, contributing to the soft, modern aesthetic.
- Pair Carbon Black (#000000) for primary text with Canvas Creme (#f8f9eb) backgrounds for optimal contrast (19.7:1 AAA).
- Employ jetBrainsMono for all badges and smaller functional labels to convey precision.
- Maintain comfortable density with an element gap of 9px and a section gap of 63px.

### Don't
- Avoid using multiple chromatic colors in close proximity; the color palette is designed for accent, not proliferation.
- Do not use generic sans-serif fonts for headlines; abcMonumentGrotesk is essential for brand recognition of prominent text.
- Never use dark text on dark backgrounds; ensure sufficient contrast by pairing light text with dark backgrounds or vice-versa.
- Do not introduce sharp, angular corners; all interactive and card-like components should feature generous border radii.
- Refrain from heavy drop shadows; elevation is achieved through color contrast and layered shapes rather than pronounced shadows.
- Do not treat every color in the palette as a functional UI color; some are specifically for decorative backgrounds or accents.
- Avoid generic button styles; prefer outlined or filled buttons that adhere to the specified radii and color contrasts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Creme | `#f8f9eb` | Base page background, light and warm. |
| 1 | Carbon Black | `#000000` | Contrasting background for specific sections and the primary navigation bar. |
| 2 | Forest Green | `#003d21` | Prominent background for large, organic decorative elements, and specific card surfaces. |

## Imagery

This site features a highly controlled visual language, emphasizing abstract 3D renders primarily in shades of Forest Green and Aura Green. Imagery is primarily decorative and atmospheric, often depicting swirling, organic, or connected shapes. Photography is minimal, appearing as tighter product crops or contextual UI screenshots rather than lifestyle. Icons are typically single-color, outlined, and minimal, appearing as functional glyphs or expressive emojis. The visual density is balanced, with imagery serving as large background elements or contained within UI cards, providing visual relief and brand reinforcement against text-heavy sections.

## Layout

The page primarily uses a full-bleed structure without a fixed `pageMaxWidth`, creating expansive sections. The hero section is characterized by a centered, high-impact headline over a light background, often with large, organic, full-width colored shapes (like the Forest Green arc). Section rhythm is created through alternating background colors and large visual dividers (often full-bleed colored sections). Content arrangement frequently utilizes two-column layouts, with text on one side and a visual or card element on the other. A card grid for features is also evident. The layout prioritizes breathing room, with spacious vertical gaps between sections. Navigation is a sticky top bar with a centered logo and right-aligned links and buttons.

## Agent Prompt Guide

primary action: #202020 (filled action)
Create a Primary Action Button: #202020 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
1. Create a hero section: Canvas Creme background. Headline 'CUSTOMIZE MONETIZE MAXIMIZE' at 72px abcMonumentGrotesk weight 800, #000000, letter-spacing -0.01em. Subtext at 25px abcMonumentGrotesk weight 400, #5a5a4f. Include an organic background shape filled with Forest Green.
3. Build a feature card: Canvas Creme Card, 22.3625px radius, 13px padding. Headline at 34px abcMonumentGrotesk weight 500, #000000. Body text at 18px abcMonumentGrotesk weight 400, #5a5a4f.
4. Create a navigation link: Ghost Header Navigation Link with 'Products' text at 16px abcMonumentGrotesk weight 400, #000000.
5. Implement a Badge: Pill Badge (Light text on transparent) with 'Coda portal' text at 12px jetBrainsMono weight 400, #f8f9eb text, 9999px radius, 0px 8.94498px padding.

## Similar Brands

- **Stripe** — Monochrome base palette with a single dominant brand accent color, and strong, compact display typography.
- **Rive** — Prominent use of abstract, often organic, 3D shapes as background and decorative elements, contrasting with clean UI.
- **Framer** — Expansive, full-bleed layouts combined with bold, sans-serif typography used for high-impact headlines and a modern aesthetic.
- **Linear** — Minimalist UI approach with functional components and a focus on content hierarchy through typographic contrast.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-creme: #f8f9eb;
  --color-carbon-black: #000000;
  --color-obsidian-gray: #202020;
  --color-forest-green: #003d21;
  --color-sage-mist: #c0c2a9;
  --color-mid-tone-gray: #5a5a4f;
  --color-light-taupe: #7c7d76;
  --color-pale-ash: #edeee1;
  --color-aura-green: #aafdc0;
  --color-soft-teal: #b0f4ff;
  --color-lavender-mist: #d3beff;
  --color-rose-blush: #ffc0e6;
  --color-blue-violet: #041668;
  --color-deep-plum: #2d0078;
  --color-dark-magenta: #3f0929;

  /* Typography — Font Families */
  --font-abcmonumentgrotesk: 'abcMonumentGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'jetBrainsMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-subheading: 21px;
  --leading-subheading: 1.13;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.13;
  --text-heading: 34px;
  --leading-heading: 1.13;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.02;
  --tracking-heading-lg: -0.45px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -0.72px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-27: 27px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-63: 63px;
  --spacing-72: 72px;
  --spacing-89: 89px;
  --spacing-107: 107px;

  /* Layout */
  --section-gap: 63px;
  --card-padding: 13px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-lg: 8.94498px;
  --radius-xl: 13.4175px;
  --radius-2xl: 17.89px;
  --radius-2xl-2: 22.3625px;
  --radius-3xl: 26.835px;
  --radius-3xl-2: 44.725px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 22.3625px;
  --radius-large: 26.835px;
  --radius-badges: 9999px;
  --radius-buttons: 8.94498px;
  --radius-default: 13.4175px;
  --radius-extralarge: 44.725px;

  /* Surfaces */
  --surface-canvas-creme: #f8f9eb;
  --surface-carbon-black: #000000;
  --surface-forest-green: #003d21;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-creme: #f8f9eb;
  --color-carbon-black: #000000;
  --color-obsidian-gray: #202020;
  --color-forest-green: #003d21;
  --color-sage-mist: #c0c2a9;
  --color-mid-tone-gray: #5a5a4f;
  --color-light-taupe: #7c7d76;
  --color-pale-ash: #edeee1;
  --color-aura-green: #aafdc0;
  --color-soft-teal: #b0f4ff;
  --color-lavender-mist: #d3beff;
  --color-rose-blush: #ffc0e6;
  --color-blue-violet: #041668;
  --color-deep-plum: #2d0078;
  --color-dark-magenta: #3f0929;

  /* Typography */
  --font-abcmonumentgrotesk: 'abcMonumentGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'jetBrainsMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-subheading: 21px;
  --leading-subheading: 1.13;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.13;
  --text-heading: 34px;
  --leading-heading: 1.13;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.02;
  --tracking-heading-lg: -0.45px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -0.72px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-27: 27px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-63: 63px;
  --spacing-72: 72px;
  --spacing-89: 89px;
  --spacing-107: 107px;

  /* Border Radius */
  --radius-lg: 8.94498px;
  --radius-xl: 13.4175px;
  --radius-2xl: 17.89px;
  --radius-2xl-2: 22.3625px;
  --radius-3xl: 26.835px;
  --radius-3xl-2: 44.725px;
  --radius-full: 9999px;
}
```
