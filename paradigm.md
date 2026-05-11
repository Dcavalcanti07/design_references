# Paradigm — Style Reference
> Strategic Intelligence Platform: dark obsidian meets stark white

**Theme:** light

Paradigm AI presents a high-contrast visual system featuring a stark dark hero section that transitions into an expansive, bright canvas for content. The aesthetic combines precise, technical typography with subtle graphical flourishes and a functional, restrained color palette, primarily leveraging deep neutrals for structure and specific, controlled accents for interaction and status. Components are intentionally lightweight, favoring soft borders, minimal elevation, and small radii, emphasizing content clarity over heavy ornamentation. Visual hierarchy is established through thoughtful typographic scaling and strategic use of negative space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#080b12` | `--color-midnight-ink` | Primary text, deep backgrounds for hero sections, prominent borders – forming the base dark canvas |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, interactive elements (buttons, links). Serves as the primary light surface |
| Gridline Gray | `#d9d9d9` | `--color-gridline-gray` | Table borders, subtle dividers – providing visual structure without distraction |
| Subtle Ash | `#4f535e` | `--color-subtle-ash` | Secondary text, muted borders, footer text – for less prominent information and structural outlines |
| Surface Off-White | `#f6f7f8` | `--color-surface-off-white` | Alternative background for content sections, subtle card elevation – distinguishing content blocks without high contrast |
| Cool Stone | `#b5b9c4` | `--color-cool-stone` | Tertiary text, inactive element borders, light backgrounds for elements like disabled states |
| Steel Gray | `#808080` | `--color-steel-gray` | Placeholder text, icons, and muted UI elements within a dark context |
| Dark Overlay | `#35373e` | `--color-dark-overlay` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Border Haze | `#edeef1` | `--color-border-haze` | Light borders and backgrounds for specific UI elements, like subtle button fills |
| Cerulean Accent | `#0a33ff` | `--color-cerulean-accent` | Interactive elements, focus indicators, highlight accents – a clear, vivid blue for emphasis |
| Deep Sea Blue | `#061353` | `--color-deep-sea-blue` | Badge text on lighter backgrounds – indicating a specific type or category |
| Lavender Touch | `#dbdbee` | `--color-lavender-touch` | Soft button backgrounds, table row separators – adding a slight tint to neutral surfaces |
| Slate Border | `#848a9c` | `--color-slate-border` | Subtle borders within complex data tables – maintaining structure without heavy lines |
| Twilight Indigo | `#7f90ce` | `--color-twilight-indigo` | Background for secondary action buttons – a muted, purposeful blue |
| Success Green | `#03350f` | `--color-success-green` | Text for success-state badges – indicating positive status |
| Success Background | `#d6ffe0` | `--color-success-background` | Background for success-state badges |
| Warning Yellow | `#423301` | `--color-warning-yellow` | Text for warning-state badges – indicating caution |
| Warning Background | `#faeed1` | `--color-warning-background` | Background for warning-state badges |
| Error Red | `#580101` | `--color-error-red` | Text for error-state badges – indicating negative status |
| Linear Gradient Blue | `linear-gradient(rgb(1, 11, 24), rgb(1, 8, 24) 16%, rgb(16, 59, 145) 49%, rgb(76, 125, 232) 78%, rgb(186, 208, 255) 97%)` | `--color-linear-gradient-blue` | Decorative hero background, emphasizing depth and technology |
| Accent Gradient Blue | `linear-gradient(135deg, rgb(123, 149, 196), rgb(223, 236, 255))` | `--color-accent-gradient-blue` | Subtle background accents, possibly for large graphical elements |

## Tokens — Typography

### PP Neue Montreal — Primary UI font for navigation, body text, buttons, and badges. Its varied weights and negative letter spacing on larger sizes create a precise, modern feel, while numeral tabular lining ensures consistent data display. · `--font-pp-neue-montreal`
- **Substitute:** System UI (e.g. SF Pro Text, Roboto, Noto Sans)
- **Weights:** 400, 450, 500
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 18px, 21px, 22px, 160px
- **Line height:** 1.00, 1.10, 1.20, 1.28, 1.30, 1.40, 1.50, 1.60, 1.80
- **Letter spacing:** -0.1200em, -0.0100em, 0.0100em, 0.1400em, 0.1500em
- **OpenType features:** `'tnum'`
- **Role:** Primary UI font for navigation, body text, buttons, and badges. Its varied weights and negative letter spacing on larger sizes create a precise, modern feel, while numeral tabular lining ensures consistent data display.

### Inter — Secondary sans-serif for detailed information, tables, and tighter spaces. Offers a strong range of smaller sizes and weights for data-heavy interfaces, ensuring legibility at scale. · `--font-inter`
- **Substitute:** Roboto, Noto Sans
- **Weights:** 400, 500, 600, 700
- **Sizes:** 9px, 10px, 11px, 12px, 13px, 14px, 15px
- **Line height:** 1.20, 1.40, 1.60
- **Letter spacing:** -0.0200em, -0.0140em, -0.0120em, -0.0100em, -0.0080em, -0.0060em, 0.0200em
- **Role:** Secondary sans-serif for detailed information, tables, and tighter spaces. Offers a strong range of smaller sizes and weights for data-heavy interfaces, ensuring legibility at scale.

### Atacama VAR — Display font for large headlines. Its very light weights combined with strong negative letter spacing create a distinctive, authoritative yet refined presence for hero text and major section titles. · `--font-atacama-var`
- **Substitute:** Montserrat, Open Sans Light
- **Weights:** 317, 370, 400
- **Sizes:** 44px, 48px, 54px
- **Line height:** 1.00, 1.10, 1.15, 1.20
- **Letter spacing:** -0.0600em, -0.0500em
- **Role:** Display font for large headlines. Its very light weights combined with strong negative letter spacing create a distinctive, authoritative yet refined presence for hero text and major section titles.

### Suisse Intl — Specific utility text, likely for small informational phrases or labels where a slightly wider tracking is desired compared to the main UI font. · `--font-suisse-intl`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** 0.0100em, 0.0800em
- **Role:** Specific utility text, likely for small informational phrases or labels where a slightly wider tracking is desired compared to the main UI font.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.6 | 0.14px | `--text-body` |
| subheading | 22px | 1.4 | -0.22px | `--text-subheading` |
| heading | 44px | 1.15 | -2.64px | `--text-heading` |
| heading-lg | 48px | 1.1 | -2.88px | `--text-heading-lg` |
| display | 160px | 1 | -19.2px | `--text-display` |

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
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 188 | 188px | `--spacing-188` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| cards | 4px |
| input | 4px |
| badges | 4px |
| buttons | 4px |
| largeCard | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgb(255, 255, 255) 0px 0px 24px 0px inset` | `--shadow-lg` |
| subtle | `rgba(0, 0, 0, 0.06) 0px 1px 3px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.04) 0px 1px 3px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(76, 120, 250, 0.14) 0px 0px 0px 3px` | `--shadow-subtle-3` |
| xl | `rgba(0, 0, 0, 0.09) 0px 4px 40px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 14px

## Components

### Primary Ghost Button
**Role:** Main call to action for the hero section and prominent interactions.

Text: Midnight Ink (#080b12), PP Neue Montreal, weight 400. Background: transparent. Border: 1px solid Midnight Ink (#080b12). Padding: 10px vertical, 24px horizontal. Radius: 4px.

### Secondary Ghost Button
**Role:** Auxiliary calls to action, less prominent than the primary.

Text: Cool Stone (#b5b9c4), PP Neue Montreal, weight 400. Background: transparent. Border: 1px solid Cool Stone (#b5b9c4). Padding: 14px vertical, 16px horizontal. Radius: 4px.

### Filled Action Button
**Role:** Interactive button for discrete actions, like 'Enrich'.

Text: Canvas White (#ffffff). Background: Twilight Indigo (#7f90ce). Padding: 10px vertical, 24px horizontal. Radius: 4px.

### Navigation Link
**Role:** Top-level navigation items and in-page links.

Text: Midnight Ink (#080b12) on light backgrounds, Canvas White (#ffffff) on dark backgrounds, PP Neue Montreal, various weights. Background: transparent. No border. No explicit padding.

### Simple Card
**Role:** Standard container for content, features, or data blocks.

Background: Canvas White (#ffffff). Radius: 4px. Shadow: rgba(0, 0, 0, 0.06) 0px 1px 3px 0px. Padding: 12px.

### Sectional Card
**Role:** Larger, more distinct content sections, providing visual separation.

Background: Surface Off-White (#f6f7f8). Radius: 16px. No shadow. Padding: 0px.

### Success Badge
**Role:** Visual indicator for successful or positive statuses.

Text: Success Green (#03350f), Inter, weight 400. Background: Success Background (#e4f3e2). Radius: 4px. Padding: 2px vertical, 6px horizontal.

### Warning Badge
**Role:** Visual indicator for warning or yellow statuses.

Text: Warning Yellow (#423301), Inter, weight 400. Background: Warning Background (#faeed1). Radius: 4px. Padding: 2px vertical, 6px horizontal.

### Error Badge
**Role:** Visual indicator for error or negative statuses.

Text: Error Red (#580101), Inter, weight 400. Background: Error Background (#ffe8ed). Radius: 4px. Padding: 2px vertical, 6px horizontal.

### Table Cell
**Role:** Individual cells within data tables.

Text: Midnight Ink (#080b12), Inter. Border: 1px solid Gridline Gray (#d9d9d9). Background: various, often Canvas White (#ffffff) or Lavender Touch (#dbdbee) for alternating rows. Padding varies between 6-12px.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#080b12) for all primary text and dark UI backgrounds to maintain a strong, authoritative contrast.
- Use Canvas White (#ffffff) as the dominant background for content sections and surfaces that require high readability and a sense of openness.
- Apply 4px border radius for all interactive elements like buttons, badges, and card corners to ensure a consistent, subtle softening.
- Employ Atacama VAR (weights 317-400, with aggressive negative letter spacing) exclusively for large headings (44px and up) to create a distinctive, restrained impact.
- Utilize Lavender Touch (#dbdbee) for subtle background variations in tables or to create a mild distinction for interactive elements.
- Use the Cerulean Accent (#0a33ff) sparingly for focus states, interactive highlights, and brand-specific iconography.
- Maintain a clear visual hierarchy by differentiating text tones: Midnight Ink (#080b12) for primary, Subtle Ash (#4f535e) for secondary, and Cool Stone (#b5b9c4) for tertiary content.

### Don't
- Avoid using highly saturated colors for large surface areas; reserve them strictly for functional accents and status indicators.
- Do not use heavy shadows or gradients on typical cards or buttons; surfaces should appear flat or with minimal, subtle elevation (rgba(0, 0, 0, 0.06) 0px 1px 3px 0px).
- Do not introduce additional font families or weights beyond the defined PP Neue Montreal, Inter, Atacama VAR, and Suisse Intl to preserve typographic consistency.
- Avoid arbitrary border radii; stick to 4px for most elements, 16px for large sectional cards, and 100px for pill-shaped elements.
- Do not clutter content with excessive borders or dividers; use Gridline Gray (#d9d9d9) or Subtle Ash (#4f535e) sparingly for necessary structural separation.
- Do not rely solely on color to convey status; always pair semantic colors with meaningful icons or text labels.
- Avoid inconsistent spacing; adhere to the defined elementGap of 14px, cardPadding of 12px, and sectionGap of 32px for vertical rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default layer for content. |
| 1 | Surface Off-White | `#f6f7f8` | Slightly elevated background for distinct sections or very light card variations. |
| 2 | Card Surface | `#ffffff` | Default background for UI cards, typically with a subtle shadow for definition. |
| 3 | Modal/Elevated Content | `#ffffff` | Higher Z-index elements like modals or dropdowns, with a more pronounced shadow. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.06) 0px 1px 3px 0px`
- **Badge:** `rgba(0, 0, 0, 0.04) 0px 1px 3px 0px`
- **Focus Ring:** `rgba(76, 120, 250, 0.14) 0px 0px 0px 3px`
- **Subtle UI Element:** `rgb(255, 255, 255) 0px 0px 24px 0px inset`

## Imagery

This design system uses a combination of direct product screenshots, stylized illustrations, and functional icons. Product screenshots are typically contained within cards, presented on white or subtly tinted backgrounds, often layered or shown from a slight isometric perspective to showcase multi-panel interfaces. Illustrations are minimal and abstract, using flattened shapes and subtle gradients that echo the brand's blues and grays, serving a decorative or conceptual purpose without being overly detailed. Icons are outlined, with a moderate stroke weight and primarily monochromatic, using Midnight Ink or Subtle Ash for clarity. Imagery density is moderate, used to break up text-heavy sections or to visually explain complex features, without dominating the overall layout.

## Layout

The page structure combines a full-bleed dark hero section with a distinct linear gradient at the top, transitioning into a predominantly max-width (likely 1200px) contained layout for the rest of the content, centered on the page. Sections alternate between Canvas White (#ffffff) and Surface Off-White (#f6f7f8) backgrounds, creating a clear vertical rhythm. Content often arranges in two-column layouts where text and visuals alternate positions, establishing a clear visual flow. Feature lists are clean, often presented as checkmark-led bullet points in single columns. Interactive data tables use fine Gridline Gray (#d9d9d9) borders and subtle row highlighting. Navigation is a sticky top bar with clearly delineated links and a strong 'Request a demo' call to action.

## Agent Prompt Guide

### Quick Color Reference
- primary text: #080b12
- background: #ffffff
- border: #d9d9d9
- accent: #0a33ff
- primary action: #7f90ce (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #7f90ce background, #020202 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a simple feature card: Background #ffffff, 4px border-radius, shadow: rgba(0, 0, 0, 0.06) 0px 1px 3px 0px, 12px padding. Heading: PP Neue Montreal, 22px size, weight 500, #080b12. Body text: Inter, 14px size, weight 400, #4f535e.
3. Implement a success badge: Background #e4f3e2, text #03350f, Inter, 12px size, weight 400, 4px radius, 2px vertical, 6px horizontal padding. Include a simple outlined checkmark icon before text if space allows (icon color: #03350f).

## Similar Brands

- **Linear** — Shares a high-contrast dark theme for focal areas, strong emphasis on precise typography, and functional use of color accents.
- **Replit** — Utilizes a dark background for its code editor/interface combined with a lighter general UI, similar to Paradigm's hero and content sections, and clean, unornamented UI components.
- **Notion** — Features a light, expansive canvas for content, relying on subtle borders and minimal component styling, with clear typographic hierarchy and functional yet restrained accent colors.
- **Vercel** — Similar approach to dark and light modes, with a focus on technical aesthetics, clean lines, and an emphasis on data presentation and functional UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #080b12;
  --color-canvas-white: #ffffff;
  --color-gridline-gray: #d9d9d9;
  --color-subtle-ash: #4f535e;
  --color-surface-off-white: #f6f7f8;
  --color-cool-stone: #b5b9c4;
  --color-steel-gray: #808080;
  --color-dark-overlay: #35373e;
  --color-border-haze: #edeef1;
  --color-cerulean-accent: #0a33ff;
  --color-deep-sea-blue: #061353;
  --color-lavender-touch: #dbdbee;
  --color-slate-border: #848a9c;
  --color-twilight-indigo: #7f90ce;
  --color-success-green: #03350f;
  --color-success-background: #d6ffe0;
  --color-warning-yellow: #423301;
  --color-warning-background: #faeed1;
  --color-error-red: #580101;
  --color-linear-gradient-blue: #103b91;
  --gradient-linear-gradient-blue: linear-gradient(rgb(1, 11, 24), rgb(1, 8, 24) 16%, rgb(16, 59, 145) 49%, rgb(76, 125, 232) 78%, rgb(186, 208, 255) 97%);
  --color-accent-gradient-blue: #7b95c4;
  --gradient-accent-gradient-blue: linear-gradient(135deg, rgb(123, 149, 196), rgb(223, 236, 255));

  /* Typography — Font Families */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atacama-var: 'Atacama VAR', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: 0.14px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.22px;
  --text-heading: 44px;
  --leading-heading: 1.15;
  --tracking-heading: -2.64px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -2.88px;
  --text-display: 160px;
  --leading-display: 1;
  --tracking-display: -19.2px;

  /* Typography — Weights */
  --font-weight-w317: 317;
  --font-weight-w370: 370;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-188: 188px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-cards: 4px;
  --radius-input: 4px;
  --radius-badges: 4px;
  --radius-buttons: 4px;
  --radius-largecard: 16px;

  /* Shadows */
  --shadow-lg: rgb(255, 255, 255) 0px 0px 24px 0px inset;
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 3px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.04) 0px 1px 3px 0px;
  --shadow-subtle-3: rgba(76, 120, 250, 0.14) 0px 0px 0px 3px;
  --shadow-xl: rgba(0, 0, 0, 0.09) 0px 4px 40px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-surface-off-white: #f6f7f8;
  --surface-card-surface: #ffffff;
  --surface-modalelevated-content: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #080b12;
  --color-canvas-white: #ffffff;
  --color-gridline-gray: #d9d9d9;
  --color-subtle-ash: #4f535e;
  --color-surface-off-white: #f6f7f8;
  --color-cool-stone: #b5b9c4;
  --color-steel-gray: #808080;
  --color-dark-overlay: #35373e;
  --color-border-haze: #edeef1;
  --color-cerulean-accent: #0a33ff;
  --color-deep-sea-blue: #061353;
  --color-lavender-touch: #dbdbee;
  --color-slate-border: #848a9c;
  --color-twilight-indigo: #7f90ce;
  --color-success-green: #03350f;
  --color-success-background: #d6ffe0;
  --color-warning-yellow: #423301;
  --color-warning-background: #faeed1;
  --color-error-red: #580101;
  --color-linear-gradient-blue: #103b91;
  --color-accent-gradient-blue: #7b95c4;

  /* Typography */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atacama-var: 'Atacama VAR', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: 0.14px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.22px;
  --text-heading: 44px;
  --leading-heading: 1.15;
  --tracking-heading: -2.64px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -2.88px;
  --text-display: 160px;
  --leading-display: 1;
  --tracking-display: -19.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-188: 188px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-lg: rgb(255, 255, 255) 0px 0px 24px 0px inset;
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 3px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.04) 0px 1px 3px 0px;
  --shadow-subtle-3: rgba(76, 120, 250, 0.14) 0px 0px 0px 3px;
  --shadow-xl: rgba(0, 0, 0, 0.09) 0px 4px 40px 0px;
}
```
