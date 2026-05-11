# Readymag — Style Reference
> Vibrant digital gallery. Each content block is a self-contained, high-contrast visual statement.

**Theme:** light

This design system is a dynamic canvas, blending stark, high-contrast typography with an unpredictable, vibrant color palette. It feels like a digital art gallery, designed for maximal visual impact where each content block is an independent exhibit. The deliberate clash of intense, vivid colors with a predominantly achromatic base creates a playful yet assertive atmosphere, eschewing traditional corporate polish for expressive, almost rebellious, visual communication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page and card backgrounds, primary body text background. |
| Type Black | `#000000` | `--color-type-black` | Primary text color for headings and body, icon fills. |
| Charcoal Text | `#282828` | `--color-charcoal-text` | Secondary text and body copy, subtle borders. |
| Surface Gray | `#f4f4f4` | `--color-surface-gray` | Button backgrounds, subtle background accents. |
| Light Gray | `#e7e7e7` | `--color-light-gray` | Section backgrounds, graphic elements. |
| UI Gray | `#808080` | `--color-ui-gray` | Subtle icons, supporting text. |
| Accent Grape | `#8800ff` | `--color-accent-grape` | Prominent headings and graphic elements, indicating key brand messages with a bold stroke. |
| Electric Violet | `#2c0fb1` | `--color-electric-violet` | Borders and graphic accents, providing a deep, energetic contrast. |
| Sunset Orange | `#ec520b` | `--color-sunset-orange` | Primary call-to-action buttons, drawing immediate attention. |
| Warning Orange | `#ff5000` | `--color-warning-orange` | Highlights within graphic elements, secondary buttons. |
| Vivid Yellow | `#ffcc00` | `--color-vivid-yellow` | Backgrounds for distinctive sections, graphic elements, imparting a cheerful, active feel. |
| Forest Green | `#b2cc00` | `--color-forest-green` | Decorative backgrounds, graphic elements, introducing organic vitality. |
| Deep Teal | `#00362b` | `--color-deep-teal` | Section backgrounds, lending depth and sophistication to content areas. |
| Warning Red | `#ff0000` | `--color-warning-red` | Highlighting specific graphic elements, drawing emphatic attention. |

## Tokens — Typography

### -apple-system — Default system font for body text, links, and various UI elements. Its neutrality allows the custom fonts to stand out. Default letter spacing is slightly tighter than normal for a concise appearance. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.00, 1.25
- **Letter spacing:** -0.006em
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** Default system font for body text, links, and various UI elements. Its neutrality allows the custom fonts to stand out. Default letter spacing is slightly tighter than normal for a concise appearance.

### custom_37866 — Primary brand typeface for all headlines, subheadings, and emphasized text. Its unique character, especially with the aggressively tight letter spacing at larger sizes, creates a distinct, modern, and sometimes avant-garde feel. The varied letter spacing across sizes is a key aesthetic choice. · `--font-custom37866`
- **Substitute:** Helvetica Neue, Arial
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 18px, 30px, 32px, 40px, 80px
- **Line height:** 1.00, 1.43, 1.83, 2.67, 2.70
- **Letter spacing:** -0.025em, -0.027em, -0.014em, -0.053em, -0.044em, -0.067em, -0.050em
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** Primary brand typeface for all headlines, subheadings, and emphasized text. Its unique character, especially with the aggressively tight letter spacing at larger sizes, creates a distinct, modern, and sometimes avant-garde feel. The varied letter spacing across sizes is a key aesthetic choice.

### Graphik — Used for specific body text and links, providing a clean, geometric sans-serif contrast to the more expressive primary custom font. Its generous line-heights make smaller text blocks readable. · `--font-graphik`
- **Substitute:** Graphik
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.50, 2.00
- **Letter spacing:** -0.002em, -0.003em
- **Role:** Used for specific body text and links, providing a clean, geometric sans-serif contrast to the more expressive primary custom font. Its generous line-heights make smaller text blocks readable.

### xgnl — A highly distinctive, bold, and condensed typeface used sparingly for impactful small text elements or experimental typographic treatments, creating moments of visual surprise due to its extremely tight letter spacing and low line height. · `--font-xgnl`
- **Substitute:** Impact, Anton
- **Weights:** 700
- **Sizes:** 16px
- **Line height:** 0.88
- **Letter spacing:** -0.056em
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** A highly distinctive, bold, and condensed typeface used sparingly for impactful small text elements or experimental typographic treatments, creating moments of visual surprise due to its extremely tight letter spacing and low line height.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 2.7 | -0.25px | `--text-caption` |
| detail | 14px | 2.67 | -0.378px | `--text-detail` |
| body-alt | 16px | 2 | -0.048px | `--text-body-alt` |
| subheading | 18px | 1.83 | -0.252px | `--text-subheading` |
| heading-sm | 30px | 1 | -1.59px | `--text-heading-sm` |
| heading | 32px | 1.43 | -1.408px | `--text-heading` |
| heading-lg | 40px | 1 | -2.68px | `--text-heading-lg` |
| display | 80px | 1 | -4px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 86 | 86px | `--spacing-86` |
| 201 | 201px | `--spacing-201` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 10px |
| buttons | 200px |
| modules | 20px |
| illustrations | 16px |

### Layout

- **Card padding:** 0px
- **Element gap:** 6px

## Components

### Primary Call to Action Button
**Role:** Critical user actions to advance through the site.

Rounded pill shape with `200px` border-radius. Background is `Sunset Orange (#ec520b)` with `Type Black (#000000)` text, shifting to `Canvas White (#ffffff)` on hover. Padding is `0px` top/bottom, `24px` left/right.

### Pill Navigation Button
**Role:** Main navigation and secondary actions in headers.

Rounded pill shape with `200px` border-radius. Background is `Surface Gray (#f4f4f4)` with `Type Black (#000000)` text. Padding is `0px` top/bottom, `24px` left/right.

### Ghost Navigation Link
**Role:** Minimalist interactive text links.

No background, `Charcoal Text (#282828)` text, no border. Padding is `0px` all around. Uses system font `-apple-system`.

### Unstyled Card
**Role:** Content containers that rely on background color for differentiation.

Background `Canvas White (#ffffff)`, `0px` border-radius, no box-shadow. Padding is `0px` all around, content provides its own spacing.

### Hero Headline
**Role:** Prominent, attention-grabbing titles.

Uses `custom_37866` font, `80px` size, `weight 400`, `line-height 1.00`, `letter-spacing -0.050em`. Color is `Type Black (#000000)`.

### Interactive Block Headline
**Role:** Headlines within interactive cards or sections.

Uses `custom_37866` font, `40px` size, `weight 400`, `line-height 1.00`, `letter-spacing -0.067em`. Color is `Type Black (#000000)` or `Canvas White (#ffffff)` depending on background.

## Do's and Don'ts

### Do
- Always use `200px` border-radius for primary and secondary action buttons to maintain the pill shape.
- Utilize `custom_37866` with its distinctive tight letter spacing (e.g., `-0.050em` at `80px`) for all major headlines to create an impactful typographic statement.
- Employ the vivid brand and accent colors (e.g., `Accent Grape #8800ff`, `Vivid Yellow #ffcc00`, `Deep Teal #00362b`) as full-bleed section backgrounds to delineate content blocks.
- Prioritize `Sunset Orange (#ec520b)` for all high-priority call-to-action buttons.
- Maintain high contrast text on backgrounds: `Type Black (#000000)` on `Canvas White (#ffffff)` and `Canvas White (#ffffff)` on any vivid background color.
- Use `0px` padding on card components, allowing internal content to define its own layout and spacing.

### Don't
- Never use soft, muted accent colors; the palette is defined by high-chroma, vivid hues.
- Avoid generic box-shadows for elevation; rely on stark shifts in background color between sections for visual depth.
- Do not use subtle letter-spacing for headlines; the aggressive negative letter spacing of `custom_37866` is a signature of this system.
- Do not constrain content to a fixed page width globally; sections should alternate between full-bleed and contained elements.
- Avoid excessive use of `-apple-system` for headlines; reserve it for body text where neutrality is desired.
- Do not use subtle border-radius values below `10px` for UI components; the system favors either sharp 0px corners or distinctly rounded forms like `10px`, `16px`, `20px` or `200px`.

## Imagery

Imagery is highly abstract and often serves as a backdrop or decorative element rather than a direct content focus. Product screenshots are minimal, focusing on UI elements in isolation. There is a strong emphasis on stark, geometric shapes and typographic art as visual content. Photography, when present, is often part of a collage or a design sample within the product showcase, not lifestyle imagery. Icons are minimal, mostly `Type Black (#000000)` filled, with a blocky, bold outline. The visual density of images varies, with some sections being very image-heavy and others completely text-dominant, creating a dynamic rhythm.

## Layout

The page exhibits a highly dynamic and sectioned layout, alternating between full-bleed background sections and content blocks with varying implicit maximum widths. The hero section often features a centered headline over a visually dense, collage-like background. Sections are delineated by dramatic shifts in background color, providing visual breaks rather than relying on consistent vertical spacing. Content arrangement frequently uses a mix of centered stacks, text blocks, and full-width banners. There is no rigid grid system explicitly visible, rather a fluid arrangement of diverse content types. Navigation is a sticky top bar, minimal for core actions. A floating '5' interactive element suggests strong spatial interaction.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#000000` (Type Black)
- Background: `#ffffff` (Canvas White)
- CTA: `#ec520b` (Sunset Orange)
- Border (accent): `#2c0fb1` (Electric Violet)
- Accent (graphic): `#8800ff` (Accent Grape)

### 3-5 Example Component Prompts
1. Create a primary call to action button: `Sunset Orange (#ec520b)` background, `Canvas White (#ffffff)` text, `200px` border-radius, `0px` top/bottom padding, `24px` left/right padding. Text label 'Get Started'.
2. Design a hero section headline: `custom_37866` font, `80px` size, `weight 400`, `line-height 1.00`, `letter-spacing -0.050em`, `Type Black (#000000)` color. Text content 'Design Freely'.
3. Generate a section background div: `Vivid Yellow (#ffcc00)` as the background color, with `86px` right margin and `86px` left margin. No border, `0px` padding.
4. Create a minimalist navigation link: `-apple-system` font, `16px` size, `weight 400`, `line-height 1.25`, `Charcoal Text (#282828)` color. Text 'Solutions'.
5. Implement an interactive block headline: `custom_37866` font, `40px` size, `weight 400`, `line-height 1.00`, `letter-spacing -0.067em`, `Canvas White (#ffffff)` color.

## Similar Brands

- **AIGA Design** — Exploits bold, often oversized typography and a willingness to use vibrant, unexpected color combinations for each content block.
- **Figma** — Clear emphasis on design tool functionality with bold, high-contrast UI and a playful approach to color in illustrations and branding.
- **CSS Design Awards** — Features a highly dynamic, experimental layout with varying section backgrounds and a focus on visual impact over strict grid adherence.
- **Webflow** — Empowers design freedom with a focus on visual delivery, leading to diverse and sometimes unconventional page compositions.
- **Supabase** — Uses strong, often dark, background elements with vibrant accent colors to create visual pop and clear calls to action, though Readymag's aesthetic is more chaotic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-type-black: #000000;
  --color-charcoal-text: #282828;
  --color-surface-gray: #f4f4f4;
  --color-light-gray: #e7e7e7;
  --color-ui-gray: #808080;
  --color-accent-grape: #8800ff;
  --color-electric-violet: #2c0fb1;
  --color-sunset-orange: #ec520b;
  --color-warning-orange: #ff5000;
  --color-vivid-yellow: #ffcc00;
  --color-forest-green: #b2cc00;
  --color-deep-teal: #00362b;
  --color-warning-red: #ff0000;

  /* Typography — Font Families */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom37866: 'custom_37866', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-xgnl: 'xgnl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2.7;
  --tracking-caption: -0.25px;
  --text-detail: 14px;
  --leading-detail: 2.67;
  --tracking-detail: -0.378px;
  --text-body-alt: 16px;
  --leading-body-alt: 2;
  --tracking-body-alt: -0.048px;
  --text-subheading: 18px;
  --leading-subheading: 1.83;
  --tracking-subheading: -0.252px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -1.59px;
  --text-heading: 32px;
  --leading-heading: 1.43;
  --tracking-heading: -1.408px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.68px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-86: 86px;
  --spacing-201: 201px;

  /* Layout */
  --card-padding: 0px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 30px;
  --radius-full: 102px;
  --radius-full-2: 200px;

  /* Named Radii */
  --radius-tags: 10px;
  --radius-buttons: 200px;
  --radius-modules: 20px;
  --radius-illustrations: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-type-black: #000000;
  --color-charcoal-text: #282828;
  --color-surface-gray: #f4f4f4;
  --color-light-gray: #e7e7e7;
  --color-ui-gray: #808080;
  --color-accent-grape: #8800ff;
  --color-electric-violet: #2c0fb1;
  --color-sunset-orange: #ec520b;
  --color-warning-orange: #ff5000;
  --color-vivid-yellow: #ffcc00;
  --color-forest-green: #b2cc00;
  --color-deep-teal: #00362b;
  --color-warning-red: #ff0000;

  /* Typography */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom37866: 'custom_37866', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-xgnl: 'xgnl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2.7;
  --tracking-caption: -0.25px;
  --text-detail: 14px;
  --leading-detail: 2.67;
  --tracking-detail: -0.378px;
  --text-body-alt: 16px;
  --leading-body-alt: 2;
  --tracking-body-alt: -0.048px;
  --text-subheading: 18px;
  --leading-subheading: 1.83;
  --tracking-subheading: -0.252px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -1.59px;
  --text-heading: 32px;
  --leading-heading: 1.43;
  --tracking-heading: -1.408px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.68px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -4px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-86: 86px;
  --spacing-201: 201px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 30px;
  --radius-full: 102px;
  --radius-full-2: 200px;
}
```
