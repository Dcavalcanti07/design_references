# Tailark Pro — Style Reference
> Gallery of Digital Artifacts — like a minimalist gallery showcasing pixel-perfect UI elements on subtly textured white walls.

**Theme:** light

Tailark Pro presents an airy, contemporary aesthetic that feels like an interactive museum exhibition of digital components. It achieves this with an almost entirely achromatic palette, punctuated by carefully selected, vibrant accents on interactive elements or illustrative details. The use of multiple shades of near-white for backgrounds and surfaces, combined with subtle, layered box-shadows, creates depth and structure without heavy lines or strong color contrasts. Typography is primarily utilitarian sans-serif, anchoring the UI, while a mono-spaced font adds a technical, precision-engineered feel to code-like elements. Asymmetric and varied border radii on cards create a dynamic, modern presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#09090b` | `--color-ink-black` | Primary text, prominent icons, dark backgrounds for contrast sections. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page background, card surfaces, interactive indicator highlights. |
| Silver Gray | `#e4e4e7` | `--color-silver-gray` | Default borders, subtle dividers, secondary background. |
| Dim Gray | `#52525c` | `--color-dim-gray` | Secondary text, muted icons, subtle background for text sections. |
| Charcoal Black | `#404040` | `--color-charcoal-black` | Box shadows, deeper background tones. |
| Steel Gray | `#5f5f61` | `--color-steel-gray` | Tertiary text, background for subtle interactive elements. |
| Light Pearl | `#848485` | `--color-light-pearl` | Placeholder text, disabled element text. |
| Cloud Gray | `#d4d4d8` | `--color-cloud-gray` | Muted text, less prominent borders. |
| Pebble Gray | `#c2c2c2` | `--color-pebble-gray` | Subtle borders and background accents. |
| Dusty Gray | `#a6a6a6` | `--color-dusty-gray` | Subtle shadows, disabled state borders. |
| Dark Granite | `#474748` | `--color-dark-granite` | Darker background accents, specific text elements. |
| Slate Blue | `#71717b` | `--color-slate-blue` | Hint text, less prominent UI elements. |
| Violet Glow | `#615fff` | `--color-violet-glow` | Accent color for interactive elements, primary buttons, and highlight states – brings a futuristic energy. |
| Teal Burst | `#64debe` | `--color-teal-burst` | Accent color for illustrative elements and subtle background gradients, suggesting growth and innovation. |
| Lavender Mist | `#b0afff` | `--color-lavender-mist` | Muted violet for subtle accents and backgrounds within illustrations, providing a softer brand touch. |
| Sunstone | `#e17100` | `--color-sunstone` | Vivid orange for specific secondary accents or informational highlights, drawing attention when needed. |
| Emerald Spark | `#00d492` | `--color-emerald-spark` | Vivid green for positive indicators, financial gains, or as an illustrative accent. |
| Sky Blue | `#2b7fff` | `--color-sky-blue` | Vivid blue for informational cues, links, and illustrative accents, conveying clarity. |
| Tangerine | `#fe9a00` | `--color-tangerine` | Vivid yellow-orange for small illustrative tags or highlights, indicating a type or category. |
| Forest Green | `#00bc7d` | `--color-forest-green` | Vivid green for specific application UI elements. |
| Crimson | `#ff2056` | `--color-crimson` | Vivid red for error states or specific interactive accents. |
| Gradient Turquoise Green | `linear-gradient(to right in oklab, rgb(0, 224, 217) 0%, rgb(99, 246, 85) 100%)` | `--color-gradient-turquoise-green` | A dynamic gradient primarily used for header backgrounds or prominent feature sections, suggesting fluidity and modernity. |

## Tokens — Typography

### ui-sans-serif — Primary UI text for body content, navigation, buttons, and headings. Its clean, neutral presence ensures readability across all UI elements. · `--font-ui-sans-serif`
- **Substitute:** system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 16px, 18px, 20px, 30px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63, 1.71
- **Letter spacing:** normal
- **Role:** Primary UI text for body content, navigation, buttons, and headings. Its clean, neutral presence ensures readability across all UI elements.

### Geist Mono — Used for code snippets, command line interfaces, and technical labels to convey precision and data-centric accuracy. · `--font-geist-mono`
- **Substitute:** monospace
- **Weights:** 100, 400, 600
- **Sizes:** 10px, 12px, 24px, 30px
- **Line height:** 1.20, 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Used for code snippets, command line interfaces, and technical labels to convey precision and data-centric accuracy.

### Mulish — A secondary body font for specific descriptive text, providing a slightly softer counterpoint to the primary sans-serif. · `--font-mulish`
- **Substitute:** 'Mulish', sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** normal
- **Role:** A secondary body font for specific descriptive text, providing a slightly softer counterpoint to the primary sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| heading | 20px | 1.25 | — | `--text-heading` |
| display | 30px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 84 | 84px | `--spacing-84` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| input | 4px |
| buttons | 6px |
| default | 6px |
| largeCards | 32px |
| extraLargeCards | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 0px 0px 1px` | `--shadow-subtle` |
| subtle-2 | `oklab(0.141 0.00136173 -0.00480696 / 0.075) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| subtle-3 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065...` | `--shadow-subtle-3` |
| subtle-4 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065...` | `--shadow-subtle-4` |
| subtle-5 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px` | `--shadow-subtle-5` |
| subtle-6 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065...` | `--shadow-subtle-6` |
| subtle-7 | `oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 1px 3px 0p...` | `--shadow-subtle-7` |
| subtle-8 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) ...` | `--shadow-subtle-8` |
| subtle-9 | `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065...` | `--shadow-subtle-9` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle-10 | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle-10` |
| subtle-11 | `oklab(0.141 0.00136173 -0.00480696 / 0.1) 0px 0px 0px 1px...` | `--shadow-subtle-11` |
| subtle-12 | `rgb(0, 0, 0) 0px 0px 0px 1px, oklab(0 0 0 / 0.2) 0px 20px...` | `--shadow-subtle-12` |
| subtle-13 | `oklab(0.999994 0.0000455678 0.0000200868 / 0.05) 0px 0px ...` | `--shadow-subtle-13` |
| sm-2 | `oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.06...` | `--shadow-sm-2` |

### Layout

- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Default Button
**Role:** Interactive element

Ghost button with `Ink Black` text on transparent background, subtle `Silver Gray` border and `6px` border-radius. Padding: `8px` vertical, `16px` horizontal.

### White Text Button
**Role:** Secondary action

Ghost button with `Ghost White` text on transparent background, bordered by a translucent white, `6px` border-radius. Padding: `8px` vertical, `16px` horizontal.

### Small Button
**Role:** Compact action

Ghost button with `Ink Black` text on transparent background, `6px` border-radius. Padding: `0px` vertical, `4-8px` horizontal.

### Rounded Small Button
**Role:** Compact action with softer edges

Ghost button with `Ink Black` text on transparent background, `8px` border-radius. Padding: `8px` vertical, `12px` horizontal.

### Illustration Card
**Role:** Displaying illustration or feature previews

Card with `oklab(0.999994 0.0000455678 0.0000200868 / 0.75)` background, `0px` border-radius, no shadow. Padding: `32px` all sides.

### Elevated Card Top Rounded
**Role:** Container for content, elevated off the surface

Card with `oklab(0.984998 -0.00000956655 0.0000230074 / 0.75)` background, `40px` top-left, `40px` top-right, `0px` bottom-left/right border-radius. Subtle shadow: `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px`. Padding: `8px` top/sides, `0px` bottom.

### Standard Elevated Card
**Role:** General content container with elevation

Card with `Ghost White` background, `16px` border-radius. Prominent shadow: `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px`. Padding: `32px` all sides.

### Dynamic Elevated Card Top Rounded
**Role:** Feature card with distinct top visual

Card with `Ghost White` background, `32px` top-left, `32px` top-right, `0px` bottom-left/right border-radius. Subtle shadow: `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px`. Padding: `8px` top, `24px` sides, `64px` bottom.

### Interactive Input
**Role:** Single-line text input field

Input field with a translucent `oklab(0.141 0.00136173 -0.00480696 / 0.05)` background, `Ink Black` text, `4px` border-radius. Border: `oklab(0.141 0.00136173 -0.00480696 / 0.075)`. Padding: `2px` vertical, `8px` horizontal.

## Do's and Don'ts

### Do
- Prioritize `Ghost White` (#ffffff) for page backgrounds and large surface areas to maintain an open, minimalist feel.
- Use `Ink Black` (#09090b) for primary text and headings, ensuring high contrast against light backgrounds.
- Apply `Violet Glow` (#615fff) exclusively for primary interactive elements like buttons and active states to guide user attention.
- Construct depth through subtle, layered box-shadows (e.g., `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px`) rather than hard borders for cards and elevated components.
- Vary card corner radii, including asymmetric options (e.g., `40px` top-rounded, `0px` bottom) to create a dynamic and modern grid layout.
- Use `ui-sans-serif` at weight 400 for all body text to ensure optimal readability and neutrality across the UI.
- Adhere to an `8px` element gap for consistent and compact spacing between most UI components.

### Don't
- Avoid using multiple vibrant chromatic colors concurrently; reserve them for specific interactive elements or within illustrations.
- Do not introduce strong, opaque borders on cards or sections; rely on subtle `Silver Gray` (#e4e4e7) or transparent outlines.
- Refrain from using heavy shadows that obscure content; elevation should be perceived as subtle lifts, not dark depths.
- Do not use generic sans-serif fonts where `Geist Mono` is intended for a technical or code-like context.
- Avoid large negative spacing or white space beyond `48px` between main sections; maintain a compact information density.
- Do not default to uniform `6px` radius for all elements; strategically apply `16px`, `32px`, or `40px` radii to cards for visual rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Background | `#ffffff` | The foundational background for the entire page, providing a crisp, expansive white space. |
| 1 | Default Card/Surface | `#ffffff` | The primary surface for most content cards, appearing directly on the canvas. |
| 2 | Translucent Elevated Card | `#oklab(0.999994 0.0000455678 0.0000200868 / 0.75)` | A slightly translucent white background used for certain card variants, allowing a hint of the canvas to show through. |
| 3 | Subtle Elevated Card | `#oklab(0.984998 -0.00000956655 0.0000230074 / 0.75)` | A near-white background for cards with a very subtle off-white tint, providing a distinct identity while maintaining lightness. |

## Elevation

- **Elevated Card Top Rounded:** `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px`
- **Standard Elevated Card:** `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px`
- **Dynamic Elevated Card Top Rounded:** `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px`

## Imagery

The site uses a mix of highly stylized illustrations and product-like UI mockups. Illustrations are dimensional and often represent digital artifacts, documents, or data visualizations, set against white or subtly tinted backgrounds. They often feature brand accent colors like `Violet Glow` or `Emerald Spark`. UI mockups are clean, sharp, and focused on showcasing product interfaces. Icons are monochromatic or duo-toned with `Ink Black` and an accent color, frequently outlined with a small stroke weight, and have a modern, geometric style. Imagery acts as both decorative atmosphere and explanatory content, creating a gallery-like feel where every visual element is a curated piece.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px, centered horizontally. The hero section is full-width with a dark gradient background, centrally aligning its headline. Content sections below often feature alternating `Ghost White` and very subtle `Silver Gray` or `Translucent Elevated Card` backgrounds, creating a soft band rhythm. Content is arranged in modular grids, particularly prominent in the illustration gallery with a consistent `8px` element gap. A notable pattern is the use of 2-column or 3-column card grids, with cards featuring varied corner radii for visual interest. The header is sticky, compact, and contains primary navigation and action buttons.

## Agent Prompt Guide

### Quick Color Reference
- Primary Text: `#09090b` (Ink Black)
- Page Background: `#ffffff` (Ghost White)
- Call to Action: `#615fff` (Violet Glow)
- Default Border: `#e4e4e7` (Silver Gray)
- Secondary Text: `#52525c` (Dim Gray)

### 3-5 Example Component Prompts
- Create a navigation link: `Ink Black` text, `ui-sans-serif` weight 400, size 14px, on a transparent background, with `4px` padding right and left. On hover, apply `Violet Glow` to text.
- Create a standard elevated card: `Ghost White` background, `16px` border-radius, `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px` shadow, and `32px` padding on all sides. Use `Ink Black` for headline (`ui-sans-serif` 30px, weight 700) and `Dim Gray` for body text (`ui-sans-serif` 14px, weight 400, lineHeight 1.43).
- Create a primary action button: `Violet Glow` background, `Ghost White` text (`ui-sans-serif` 14px, weight 600), `6px` border-radius, `8px` vertical and `16px` horizontal padding. Apply a subtle ghost shadow `oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 0px 0px 1px`.
- Create an input field: Background `oklab(0.141 0.00136173 -0.00480696 / 0.05)`, text `Ink Black`, border `oklab(0.141 0.00136173 -0.00480696 / 0.075)`, `4px` border-radius, `2px` vertical and `8px` horizontal padding. Placeholder text should be `Light Pearl`.
- Create a top-rounded feature card: Background `Ghost White`, `32px` top-left and top-right radius (0px elsewhere), `oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px` shadow. Padding should be `8px` top, `24px` sides, and `64px` bottom.

## Similar Brands

- **Stripe** — Shares a clean, modern aesthetic with a focus on functional UI, crisp typography, and minimal use of color within an otherwise neutral palette, using bright accents sparingly.
- **Linear** — Exhibits similar attention to detail in UI components, elegant use of spacing, and a pragmatic approach to typography, favoring system fonts or neutral typefaces with precise weighting.
- **Vercel** — Employs an almost entirely achromatic UI with subtle elevations and shadows to create depth, punctuated by a single, vibrant brand accent color to highlight interactivity, similar to Tailark Pro's use of violet.
- **Figma** — Features a light, spacious design with white canvases and detailed, functional UI elements. Uses varying levels of gray and subtle shadows to differentiate UI layers and creates visual interest with specific component radii.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #09090b;
  --color-ghost-white: #ffffff;
  --color-silver-gray: #e4e4e7;
  --color-dim-gray: #52525c;
  --color-charcoal-black: #404040;
  --color-steel-gray: #5f5f61;
  --color-light-pearl: #848485;
  --color-cloud-gray: #d4d4d8;
  --color-pebble-gray: #c2c2c2;
  --color-dusty-gray: #a6a6a6;
  --color-dark-granite: #474748;
  --color-slate-blue: #71717b;
  --color-violet-glow: #615fff;
  --color-teal-burst: #64debe;
  --color-lavender-mist: #b0afff;
  --color-sunstone: #e17100;
  --color-emerald-spark: #00d492;
  --color-sky-blue: #2b7fff;
  --color-tangerine: #fe9a00;
  --color-forest-green: #00bc7d;
  --color-crimson: #ff2056;
  --color-gradient-turquoise-green: #00e0d9;
  --gradient-gradient-turquoise-green: linear-gradient(to right in oklab, rgb(0, 224, 217) 0%, rgb(99, 246, 85) 100%);

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-mulish: 'Mulish', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --text-display: 30px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
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
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-input: 4px;
  --radius-buttons: 6px;
  --radius-default: 6px;
  --radius-largecards: 32px;
  --radius-extralargecards: 40px;

  /* Shadows */
  --shadow-subtle: oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 0px 0px 1px;
  --shadow-subtle-2: oklab(0.141 0.00136173 -0.00480696 / 0.075) 0px 0px 0px 1px;
  --shadow-subtle-3: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px;
  --shadow-subtle-4: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px;
  --shadow-subtle-5: oklab(0 0 0 / 0.075) 0px 0px 0px 1px;
  --shadow-subtle-6: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px;
  --shadow-subtle-7: oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 1px 3px 0px, oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 1px 2px -1px;
  --shadow-subtle-8: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-9: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 20px 25px -5px, oklab(0 0 0 / 0.065) 0px 8px 10px -6px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-10: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-11: oklab(0.141 0.00136173 -0.00480696 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-12: rgb(0, 0, 0) 0px 0px 0px 1px, oklab(0 0 0 / 0.2) 0px 20px 25px -5px, oklab(0 0 0 / 0.2) 0px 8px 10px -6px;
  --shadow-subtle-13: oklab(0.999994 0.0000455678 0.0000200868 / 0.05) 0px 0px 0px 1px;
  --shadow-sm-2: oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px;

  /* Surfaces */
  --surface-canvas-background: #ffffff;
  --surface-default-cardsurface: #ffffff;
  --surface-translucent-elevated-card: #oklab(0.999994 0.0000455678 0.0000200868 / 0.75);
  --surface-subtle-elevated-card: #oklab(0.984998 -0.00000956655 0.0000230074 / 0.75);
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #09090b;
  --color-ghost-white: #ffffff;
  --color-silver-gray: #e4e4e7;
  --color-dim-gray: #52525c;
  --color-charcoal-black: #404040;
  --color-steel-gray: #5f5f61;
  --color-light-pearl: #848485;
  --color-cloud-gray: #d4d4d8;
  --color-pebble-gray: #c2c2c2;
  --color-dusty-gray: #a6a6a6;
  --color-dark-granite: #474748;
  --color-slate-blue: #71717b;
  --color-violet-glow: #615fff;
  --color-teal-burst: #64debe;
  --color-lavender-mist: #b0afff;
  --color-sunstone: #e17100;
  --color-emerald-spark: #00d492;
  --color-sky-blue: #2b7fff;
  --color-tangerine: #fe9a00;
  --color-forest-green: #00bc7d;
  --color-crimson: #ff2056;
  --color-gradient-turquoise-green: #00e0d9;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-mulish: 'Mulish', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --text-display: 30px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;

  /* Shadows */
  --shadow-subtle: oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 0px 0px 1px;
  --shadow-subtle-2: oklab(0.141 0.00136173 -0.00480696 / 0.075) 0px 0px 0px 1px;
  --shadow-subtle-3: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px;
  --shadow-subtle-4: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px;
  --shadow-subtle-5: oklab(0 0 0 / 0.075) 0px 0px 0px 1px;
  --shadow-subtle-6: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px;
  --shadow-subtle-7: oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 1px 3px 0px, oklab(0.141 0.00136173 -0.00480696 / 0.05) 0px 1px 2px -1px;
  --shadow-subtle-8: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-9: oklab(0 0 0 / 0.075) 0px 0px 0px 1px, oklab(0 0 0 / 0.065) 0px 20px 25px -5px, oklab(0 0 0 / 0.065) 0px 8px 10px -6px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-10: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-11: oklab(0.141 0.00136173 -0.00480696 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-12: rgb(0, 0, 0) 0px 0px 0px 1px, oklab(0 0 0 / 0.2) 0px 20px 25px -5px, oklab(0 0 0 / 0.2) 0px 8px 10px -6px;
  --shadow-subtle-13: oklab(0.999994 0.0000455678 0.0000200868 / 0.05) 0px 0px 0px 1px;
  --shadow-sm-2: oklab(0 0 0 / 0.065) 0px 4px 6px -1px, oklab(0 0 0 / 0.065) 0px 2px 4px -2px;
}
```
