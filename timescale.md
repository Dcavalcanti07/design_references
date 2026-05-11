# Timescale — Style Reference
> Industrial Blueprint on stark white.

**Theme:** light

Timescale's design system evokes an industrial blueprint aesthetic with a high-contrast monochrome base accented by a warm, vibrant orange and a functional lime yellow. Strong geometric lines define UI elements, often creating outlined, sketched forms. Surfaces are predominantly stark white, providing a canvas for bold typography and diagrammatic illustrations. Typographic hierarchy is established through a combination of font family, weight, and specific letter-spacing, rather than relying solely on size, creating a dense yet legible information display ideal for technical content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fafafa` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, button backgrounds, strong borders, icons, footer background |
| Shadow Gray | `#6c6c6c` | `--color-shadow-gray` | Muted body text, secondary borders, subtle shadows |
| Silverline | `#b3b3b3` | `--color-silverline` | Decorative borders, tertiary text |
| Action Orange | `#ff5b29` | `--color-action-orange` | Orange outline accent for tags, dividers, and focused UI edges |
| Highlight Yellow | `#f5ff80` | `--color-highlight-yellow` | Green action color for filled buttons, selected navigation states, and focused conversion moments. |

## Tokens — Typography

### Geist — Primary marketing and UI text, headings. The varied letter-spacing at larger sizes contributes to its modern, structured feel. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 52px, 80px
- **Line height:** 1.10, 1.33, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0300em at 80px, -0.0200em at 52px
- **Role:** Primary marketing and UI text, headings. The varied letter-spacing at larger sizes contributes to its modern, structured feel.

### Geist Mono — Code snippets, technical details, and certain emphasized UI labels. The monospace gives a technical, precise tone. · `--font-geist-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 20px, 24px, 28px, 40px, 50px
- **Line height:** 1.10, 1.20, 1.33, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0200em
- **Role:** Code snippets, technical details, and certain emphasized UI labels. The monospace gives a technical, precise tone.

### ui-sans-serif — Default body text and less prominent UI elements where a system font is efficient and legible. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400, 600
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Default body text and less prominent UI elements where a system font is efficient and legible.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | -0.42px | `--text-caption` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 24px | 1.33 | -0.48px | `--text-subheading` |
| heading | 52px | 1.1 | -1.04px | `--text-heading` |
| display | 80px | 1.1 | -2.4px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| links | 8px |
| inputs | 4px |
| buttons | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.6) 0px 3px 4px 0px` | `--shadow-sm` |
| subtle | `rgb(0, 0, 0) 5px 5px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Outlined Primary Button
**Role:** Main call to action, ghost style

Background: Canvas White, Text: Midnight Ink, Border: Midnight Ink 1px solid, Radius: 4px, Padding: 10px vertical, 24px horizontal. Appears sketched.

### Filled Secondary Button
**Role:** Alternative call to action, solid fill

Background: Midnight Ink, Text: Canvas White, Border: Midnight Ink 1px solid, Radius: 4px, Padding: 10px vertical, 16px horizontal. Provides high contrast.

### Highlight Action Button
**Role:** Prominent, distinct call to action

Background: Highlight Yellow, Text: Midnight Ink, Border: Midnight Ink 1px solid, Radius: 4px, Padding: 10px vertical, 40px horizontal. Captures immediate attention.

### Feature Card
**Role:** Content container for features or integrations

Background: Canvas White, Border: None, Border Radius: 12px, Shadow: Midnight Ink 5px 5px 0px 0px. Features a distinctive offset shadow in black, giving a layered, architectural feel. Padding varies.

### Basic Card
**Role:** Simple content container without aggressive shadowing

Background: Canvas White, Border: None, Border Radius: 12px, Shadow: None. Used for sections with more internal padding.

### Text Input Field
**Role:** Standard user input

Background: Canvas White, Text: Midnight Ink, Border: Midnight Ink 1px solid, Border Radius: 4px 0px 0px 4px. Features a slightly asymmetric border radius for visual distinction. Left padding: 8px.

## Do's and Don'ts

### Do
- Prioritize a high-contrast monochrome base using Canvas White (#fafafa) and Midnight Ink (#000000) for structural elements and core text.
- Utilize Action Orange (#ff5b29) exclusively for headlines, key data, and specific decorative accents to draw attention to critical information.
- Implement Highlight Yellow (#f5ff80) for primary interactive elements and attention-grabbing banners.
- Apply a 4px `border-radius` to all buttons and input fields, and 12px `border-radius` to cards, adhering to the crisp geometric aesthetic.
- Employ Geist as the primary typeface for marketing and UI text, adjusting letter-spacing according to size: -0.03em for 80px and -0.02em for 52px.
- Create visual hierarchy in cards using a distinct Midnight Ink 5px 5px 0px 0px offset shadow, avoiding soft, diffused shadows.
- Use a base spacing unit of 8px, with 16px for `elementGap` and `cardPadding`, and 40px for `sectionGap`.

### Don't
- Do not use gradients; the system relies on flat colors and distinct shadows for depth and emphasis.
- Avoid using soft or blurred shadows; elevation is achieved through hard, offset black shadows or clear white backgrounds.
- Do not introduce additional bright accent colors; stick to Action Orange (#ff5b29) and Highlight Yellow (#f5ff80) for all chromatic emphasis.
- Never use `box-shadow` values other than the specified offset black shadow for cards, or rgba(0,0,0,0.6) for subtle hover states.
- Do not deviate from the specified Geist and Geist Mono font families for display and technical text; system fonts should be relegated to body text.
- Avoid round or organic shapes; maintain a geometric, structured appearance with emphasis on square corners and limited rounded edges.
- Do not use generic, default border radii for components; adhere to the specific 4px for buttons/inputs and 12px for cards.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fafafa` | Primary page background and base surface for cards and UI elements. |
| 1 | Highlight Yellow | `#f5ff80` | Ephemeral banners and active state backgrounds. |
| 2 | Midnight Ink | `#000000` | Dominant background for footer and filled interactive elements, providing high contrast. |

## Elevation

- **Feature Card:** `rgb(0, 0, 0) 5px 5px 0px 0px`
- **Other Elements (limited):** `rgba(0, 0, 0, 0.6) 0px 3px 4px 0px`

## Imagery

Imagery is functional, primarily comprising stylized, monochrome isometric illustrations that convey complex data processes. These diagrams use a clean, outlined style with minimal fill, predominantly black lines on a white background, mirroring a blueprint. Icons are outlined, simple, and geometric, maintaining a consistent stroke weight. The visual language of imagery is explanatory and illustrative rather than decorative, focusing on communicating technical concepts clearly and extending the industrial blueprint aesthetic.

## Layout

The page adheres to a contained, centered layout, with content sections having a conceptual max-width. The hero section often features a split layout with bold headlines and interactive elements on one side and a prominent isometric diagram on the other. Sections primarily use consistent vertical spacing (40px `sectionGap`) and often alternate between blocks with hard-edged, offset-shadowed cards and simpler, borderless content areas. Content is frequently arranged in two-column layouts or grids for feature display, maintaining a spacious yet information-dense appearance. Navigation is a sticky top bar with clear branding and high-contrast action buttons.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #fafafa
border: #000000
accent: #ff5b29
primary action: #f5ff80 (filled action)

**3-5 Example Component Prompts**
Create a Primary Action Button: #f5ff80 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a 'Feature Card': background Canvas White (#fafafa), 12px radius, Midnight Ink (#000000) 5px 5px 0px 0px shadow. Inside, add a heading using Action Orange (#ff5b29) Geist weight 600 at 24px, and body text using Midnight Ink (#000000) ui-sans-serif weight 400 at 16px. No internal padding specified, rely on content.
Create a 'Highlight Action Button': background Highlight Yellow (#f5ff80), text Midnight Ink (#000000), 1px solid Midnight Ink (#000000) border, 4px radius, 10px vertical and 40px horizontal padding, using Geist weight 600 at 16px.

## Similar Brands

- **Vercel** — Similar high-contrast monochrome base with a strong accent color, preference for crisp lines and technical illustrations, and a modern geometric typeface.
- **Stripe** — Emphasizes a clean, spacious layout with precise typography and a limited, impactful color palette for key information.
- **Linear** — Uses a dark-on-light theme with strong typographic hierarchy, subtle, functional color accents, and a focus on sharp UI elements and information density.
- **PlanetScale** — Features a similar technical blueprint aesthetic, outlined UI components, and strong use of a single, vibrant accent color against a neutral backdrop.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-midnight-ink: #000000;
  --color-shadow-gray: #6c6c6c;
  --color-silverline: #b3b3b3;
  --color-action-orange: #ff5b29;
  --color-highlight-yellow: #f5ff80;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.48px;
  --text-heading: 52px;
  --leading-heading: 1.1;
  --tracking-heading: -1.04px;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: -2.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-links: 8px;
  --radius-inputs: 4px;
  --radius-buttons: 4px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.6) 0px 3px 4px 0px;
  --shadow-subtle: rgb(0, 0, 0) 5px 5px 0px 0px;

  /* Surfaces */
  --surface-canvas-white: #fafafa;
  --surface-highlight-yellow: #f5ff80;
  --surface-midnight-ink: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-midnight-ink: #000000;
  --color-shadow-gray: #6c6c6c;
  --color-silverline: #b3b3b3;
  --color-action-orange: #ff5b29;
  --color-highlight-yellow: #f5ff80;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.48px;
  --text-heading: 52px;
  --leading-heading: 1.1;
  --tracking-heading: -1.04px;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: -2.4px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.6) 0px 3px 4px 0px;
  --shadow-subtle: rgb(0, 0, 0) 5px 5px 0px 0px;
}
```
