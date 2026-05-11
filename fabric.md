# Fabric — Style Reference
> Crisp digital canvas with thoughtful ink

**Theme:** light

Fabric crafts a refined digital workspace aesthetic with a predominantly achromatic palette, punctuated by deep, vivid violet for moments of focus and interaction. Typography is a sophisticated blend: a light, elegant serif for headlines sets a contemplative tone against sharp, functional sans-serifs for body text and UI. Surfaces are bright and layered, utilizing subtle shadows and distinct border radii to create depth and organize content without heavy borders. The overall feel is one of intelligent clarity and calm productivity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds |
| Midnight Ink | `#0a0a0a` | `--color-midnight-ink` | Primary text, filled button backgrounds — a rich, near-black for strong contrast |
| Deep Graphite | `#000000` | `--color-deep-graphite` | Strongest text, borders, and UI elements for ultimate contrast and definition |
| Light Pearl | `#f3f3f3` | `--color-light-pearl` | Subtle background for secondary buttons and decorative fills |
| Ash Gray | `#666666` | `--color-ash-gray` | Secondary text, muted borders, and subtle UI elements |
| Slate Text | `#333333` | `--color-slate-text` | Main heading text and important informational text |
| Dark Charcoal | `#404040` | `--color-dark-charcoal` | Supporting body text and navigation links |
| Soft Stone | `#b3b3b3` | `--color-soft-stone` | Muted helper text, secondary labels, and faint borders |
| Regal Violet | `#1100ff` | `--color-regal-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Outline Violet | `#19154e` | `--color-outline-violet` | Borders for links, outlined buttons, and accent text for a softer violet touch |
| Deep Violet | `#3300ff` | `--color-deep-violet` | Decorative SVG fills, often for abstract graphics in product illustrations |

## Tokens — Typography

### GT Alpina Light — Primary headlines and display text. Its light weights (300, 400) create an elegant, almost whispered authority, distinguishing Fabric's tone from bolder, more traditional titles. · `--font-gt-alpina-light`
- **Substitute:** Sans-serif serif
- **Weights:** 300, 400
- **Sizes:** 32px, 52px, 80px
- **Line height:** 1.08, 1.40
- **Letter spacing:** -0.0200em
- **Role:** Primary headlines and display text. Its light weights (300, 400) create an elegant, almost whispered authority, distinguishing Fabric's tone from bolder, more traditional titles.

### Inter — Functional body text, subheadings, links, and navigation. A versatile sans-serif that balances readability with a modern, slightly condensed character. Letter spacing varies by size, tightening slightly for larger text. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 11px, 15px, 16px, 17px, 18px, 26px, 28px
- **Line height:** 1.20, 1.30, 1.40, 1.45, 1.50, 1.60, 2.00
- **Letter spacing:** -0.0200em
- **Role:** Functional body text, subheadings, links, and navigation. A versatile sans-serif that balances readability with a modern, slightly condensed character. Letter spacing varies by size, tightening slightly for larger text.

### Manrope — Bold accents and strong callouts where extra emphasis is needed, such as feature labels or short, punchy statements. · `--font-manrope`
- **Substitute:** system-ui, sans-serif
- **Weights:** 700, 900
- **Sizes:** 18px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Bold accents and strong callouts where extra emphasis is needed, such as feature labels or short, punchy statements.

### sans-serif — Small functional text like footnotes, labels, and metadata. Uses specific font features for typographic precision even at small sizes. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **OpenType features:** `"ccmp", "cv05", "cv11", "kern", "salt"`
- **Role:** Small functional text like footnotes, labels, and metadata. Uses specific font features for typographic precision even at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.2 | -0.17px | `--text-caption` |
| body-lg | 16px | 1.5 | -0.16px | `--text-body-lg` |
| subheading | 18px | 1.4 | -0.18px | `--text-subheading` |
| heading | 26px | 1.5 | -0.52px | `--text-heading` |
| heading-lg | 32px | 1.08 | -0.64px | `--text-heading-lg` |
| display | 52px | 1.08 | -1.04px | `--text-display` |
| display-lg | 80px | 1.08 | -1.6px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| images | 16px |
| buttons | 8px |
| inner-cards | 16px |
| pill-buttons | 40px |
| small-elements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0...` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action button for primary actions

Solid filled button with a 'Midnight Ink' (#0a0a0a) background, white text, and 8px border-radius. Padding is 14px on all sides. Text uses Inter font, weight 500.

### Transparent Pill Button
**Role:** Filter or category selection buttons with a softer presence

White background button with a 'Outline Violet' (#19154e) border and text color, 40px border-radius for a pill shape. Padding is 12px on all sides. Text uses Inter font, weight 500.

### Outline Button
**Role:** Secondary actions or navigation-style buttons

White background button with a 'Outline Violet' (#19154e) border and text color, with 16px border-radius. Padding is 12px on all sides. Text uses Inter font, weight 500.

### Subtle Filled Button
**Role:** Tertiary actions or subtle interactive elements

Light Pearl (#f3f3f3) background button with 'Outline Violet' (#19154e) text, 8px border-radius. Padding is 14px on all sides. Text uses Inter font, weight 500.

### Default Card
**Role:** Container for content, features, or UI elements

Uses Canvas White (#ffffff) as background, 24px border-radius, and 12px padding on all sides. No shadow by default.

### Inner UI Card
**Role:** Nested containers, e.g., for side panels or form groups

Background is `rgba(242, 242, 245, 0.5)` for a subtly lighter surface, with 16px border-radius. No padding for full-bleed content within.

### Accent Card
**Role:** Specialized content blocks or featured items that require visual emphasis

Uses Regal Violet (#1100ff) as background, 16px border-radius, and 16px padding on all sides. No shadow by default.

### Elevated Nav/Button Shadow
**Role:** Standard shadow for interactive elements like buttons and top navigation

Subtle multi-layer shadow to lift elements: `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px`.

## Do's and Don'ts

### Do
- Prioritize GT Alpina Light (300, 400) for all primary headlines, ensuring an elegant and visually distinct text hierarchy.
- Use a default border-radius of 24px for all cards to maintain the consistent soft, rounded aesthetic.
- Apply 'Midnight Ink' (#0a0a0a) for primary filled button backgrounds and 'Canvas White' (#ffffff) for their text, reserving the violet for outlined or ghost interactions.
- Employ 'Regal Violet' (#1100ff) sparingly as an accent for active states, link underlines, and decorative highlights only.
- Maintain a clear visual separation between sections using consistent 'sectionGap' of 40px and 'cardPadding' of 12px.
- Utilize 'Deep Graphite' (#000000) for strong text elements like the main navigation and secondary headings, ensuring high readability against light backgrounds.
- Use pill-shaped buttons with 40px border-radius for filters and secondary navigation cues to distinguish them from primary actions.

### Don't
- Avoid generic bold weights for main headlines; stick to GT Alpina Light's 300 or 400 to preserve the system's elegant tone.
- Do not use highly saturated colors for large background areas or primary text; the system relies on a clean, achromatic base.
- Do not apply heavy shadows; elevation is achieved through subtle `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px` for interactive elements and distinct background layers.
- Do not introduce new typefaces; adhere strictly to GT Alpina Light, Inter, and Manrope for all textual content.
- Avoid arbitrary border-radius values; always use specified radii: 24px for cards, 8px for primary buttons, 40px for pill buttons, and 16px for inner UI elements.
- Do not overuse 'Regal Violet' (#1100ff); its impact comes from its strategic placement as a vivid accent, not a dominant color.
- Never use `rgba(242, 242, 245, 0.5)` as a primary page background; it's designed for subtle layering within card structures, not base canvases.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background |
| 1 | Default Card Background | `#fafafa` | Standard card surfaces and elevated content blocks |
| 2 | Inner UI Card Background | `#f2f2f580` | Subtle, slightly translucent background typically for nested UI or side panels, indicating a secondary surface within a card. |

## Elevation

- **Nav and Buttons:** `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px`

## Imagery

Fabric's imagery aesthetic is a blend of tight product crops on pure white backgrounds, abstract generative graphics, and occasional stylized illustrations. Photography, when present, focuses on device context (e.g., hands holding a phone showcasing the app) rather than traditional lifestyle shots. Product screenshots are typically 'floating' with soft, subtle drop shadows, almost like physical objects. Icons are outlined, minimal, and mono-color, complementing the clean UI. Imagery serves a functional role: showcasing product capabilities, providing abstract visual interest without being distracting, and occasionally illustrating concepts through stylized abstract forms rather than literal representations. The density is image-light, allowing text and UI to dominate, with imagery acting as enhancing visual punctuation.

## Layout

Fabric employs a max-width contained layout, though the hero section often uses a full-bleed background. The page is structured with generous vertical spacing between sections (40px) creating a comfortable rhythm. The hero features a large, centered headline using the distinctive GT Alpina Light font, often accompanied by floating, illustrative product mockups in an asymmetric composition. Content sections frequently alternate between text-on-left/image-on-right or vice-versa, or centered stacks of text. Information is often presented in multi-column card grids for features or testimonials. The navigation is a subtle top bar, featuring a primary filled button for 'Get Fabric free', maintaining a streamlined and uncluttered header experience.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0a0a
background: #ffffff
border: #000000
accent: #1100ff
primary action: #0a0a0a (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #0a0a0a background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Default Card with Canvas White background, 24px radius, 12px padding. Feature title 'AI assistant' using Inter 18px weight 600, Midnight Ink (#0a0a0a). Description text using Inter 15px weight 400, Ash Gray (#666666).
3. Build an inline tag: background 'Regal Violet' (#1100ff), white text, with 16px border-radius, 4px horizontal padding and 2px vertical padding. Text 'Emma' uses sans-serif 12px weight 400.

## Similar Brands

- **Notion** — White canvas aesthetic, emphasis on text and structured information, and a single vibrant accent color (though Notion uses blue).
- **Linear** — Clean, almost achromatic UI with sharp typography, focus on functionality over heavy decoration, and a distinct lack of heavy shadows.
- **Coda** — Productivity workspace with a flexible content canvas, subtle surface layering, and compact information display.
- **Supabase** — Modern SaaS aesthetic with strong typography, a light theme default, and precise use of neutral colors for hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #0a0a0a;
  --color-deep-graphite: #000000;
  --color-light-pearl: #f3f3f3;
  --color-ash-gray: #666666;
  --color-slate-text: #333333;
  --color-dark-charcoal: #404040;
  --color-soft-stone: #b3b3b3;
  --color-regal-violet: #1100ff;
  --color-outline-violet: #19154e;
  --color-deep-violet: #3300ff;

  /* Typography — Font Families */
  --font-gt-alpina-light: 'GT Alpina Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.2;
  --tracking-caption: -0.17px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading: 26px;
  --leading-heading: 1.5;
  --tracking-heading: -0.52px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.64px;
  --text-display: 52px;
  --leading-display: 1.08;
  --tracking-display: -1.04px;
  --text-display-lg: 80px;
  --leading-display-lg: 1.08;
  --tracking-display-lg: -1.6px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-images: 16px;
  --radius-buttons: 8px;
  --radius-inner-cards: 16px;
  --radius-pill-buttons: 40px;
  --radius-small-elements: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-default-card-background: #fafafa;
  --surface-inner-ui-card-background: #f2f2f580;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #0a0a0a;
  --color-deep-graphite: #000000;
  --color-light-pearl: #f3f3f3;
  --color-ash-gray: #666666;
  --color-slate-text: #333333;
  --color-dark-charcoal: #404040;
  --color-soft-stone: #b3b3b3;
  --color-regal-violet: #1100ff;
  --color-outline-violet: #19154e;
  --color-deep-violet: #3300ff;

  /* Typography */
  --font-gt-alpina-light: 'GT Alpina Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.2;
  --tracking-caption: -0.17px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading: 26px;
  --leading-heading: 1.5;
  --tracking-heading: -0.52px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.64px;
  --text-display: 52px;
  --leading-display: 1.08;
  --tracking-display: -1.04px;
  --text-display-lg: 80px;
  --leading-display-lg: 1.08;
  --tracking-display-lg: -1.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px;
}
```
