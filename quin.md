# Quin — Style Reference
> Digital parchment workflow

**Theme:** light

Quin adopts a 'digital parchment' aesthetic, blending a warm, muted palette with sharp, geometric typography. The design emphasizes a structured, tactile feel with numerous thin borders and distinct achromatic and chromatic surface layers. The overall impression is one of calm, focused productivity, where key information and interactive elements are highlighted by a soft yellow accent.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#141414` | `--color-midnight-ink` | Primary text, dark surface backgrounds, strong borders — creates a grounded, high-contrast base for content and interaction |
| Paper White | `#fffcf2` | `--color-paper-white` | Main page background, light card surfaces, default button backgrounds — establishes a warm, off-white canvas for the UI |
| Greige Mist | `#d0cec6` | `--color-greige-mist` | Subtle button borders, secondary text, muted dividers — a light neutral for delineating elements without harshness |
| Aged Paper | `#f0ecdf` | `--color-aged-paper` | Secondary surface backgrounds, section dividers, very soft borders — adds depth and texture to the light surfaces |
| Graphite | `#545454` | `--color-graphite` | Link text, secondary text, subtle borders, inactive states — provides readability for secondary information |
| Warm Umber | `#68655b` | `--color-warm-umber` | Tertiary text, background for darker sections, subtle borders — a deep, warming neutral for atmospheric sections or less prominent text |
| Deep Ash | `#222222` | `--color-deep-ash` | Body text, navigation items, borders — darker neutral for core text and structural outlines |
| Harvest Gold | `#f7cf49` | `--color-harvest-gold` | Call-to-action fills, active state indicators, accent badges, primary input borders — the signature accent color, denoting activation and importance |
| Muted Wood | `#492812` | `--color-muted-wood` | Secondary brand accent, decorative elements, occasional button backgrounds — a warm, rich tone for complementary branding |
| Sky Blue | `#a9e1ff` | `--color-sky-blue` | Information callouts, success indicators, informational badges — a clear blue for conveying positive or informational status |
| Placeholder Grey | `#a19c8c` | `--color-placeholder-grey` | Placeholder text, light decorative elements — a desaturated neutral slightly warmer than pure gray |

## Tokens — Typography

### Instrument Sans Variable — Primary brand typeface for all headings and body text. Its sharp, geometric forms and varied weights define the brand's clear, efficient communication style. The tight negative letter-spacing for larger sizes creates a sense of compression and precision, making headlines feel impactful without being visually ornate. · `--font-instrument-sans-variable`
- **Substitute:** Inter Variable
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 20px, 26px, 28px, 32px, 40px, 44px, 56px, 80px, 96px
- **Line height:** 0.75, 0.92, 1.00, 1.05, 1.10, 1.15, 1.20, 1.25, 1.35, 1.50, 1.71
- **Letter spacing:** -0.0330em at 96px, -0.0290em at 80px, -0.0200em at 56px, -0.0180em at 44px, -0.0170em at 40px, -0.0090em at 32px, -0.0070em at 28px and 26px, tending towards normal at smaller sizes
- **OpenType features:** `'kern' on, 'ss01' on, 'ss03' on, 'ss05' on, 'ss07' on, 'ss08' on, 'ss12' on`
- **Role:** Primary brand typeface for all headings and body text. Its sharp, geometric forms and varied weights define the brand's clear, efficient communication style. The tight negative letter-spacing for larger sizes creates a sense of compression and precision, making headlines feel impactful without being visually ornate.

### Geist Mono — Used for badges, navigation, and other functional UI elements where a fixed-width, technical aesthetic is desired. The generous positive letter-spacing adds a distinct, almost coded feel to these components, contrasting with the primary typeface. · `--font-geist-mono`
- **Substitute:** Space Mono
- **Weights:** 300, 400
- **Sizes:** 12px, 14px, 16px, 26px
- **Line height:** 1.00, 1.10, 2.00
- **Letter spacing:** 0.2000em at 26px, 0.1710em at 16px, 0.1070em at 14px, 0.1000em at 12px
- **OpenType features:** `'kern' on, 'ss01' on, 'ss03' on, 'ss05' on, 'ss07' on, 'ss08' on, 'ss12' on`
- **Role:** Used for badges, navigation, and other functional UI elements where a fixed-width, technical aesthetic is desired. The generous positive letter-spacing adds a distinct, almost coded feel to these components, contrasting with the primary typeface.

### Font Awesome 7 Sharp — Font Awesome 7 Sharp — detected in extracted data but not described by AI · `--font-font-awesome-7-sharp`
- **Weights:** 900
- **Sizes:** 26px, 40px
- **Line height:** 1
- **Letter spacing:** 0.046
- **Role:** Font Awesome 7 Sharp — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | 0.107px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.046px | `--text-body-sm` |
| body | 16px | 1.71 | 0.171px | `--text-body` |
| subheading | 20px | 1.25 | -0.007px | `--text-subheading` |
| heading-sm | 26px | 1.25 | -0.007px | `--text-heading-sm` |
| heading | 40px | 1.05 | -0.017px | `--text-heading` |
| heading-lg | 56px | 1 | -0.02px | `--text-heading-lg` |
| display | 96px | 0.92 | -0.033px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 0px |
| inputs | 0px |
| buttons | 0px |

### Layout

- **Section gap:** 59px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Call-to-action button, dark filled

Filled with Midnight Ink (#141414), text in Greige Mist (#d0cec6). Text set at 20px Instrument Sans Variable, weight 400. No border-radius, maintaining a sharp, rectangular shape. Vertical padding 28px, horizontal 40px.

### Secondary Ghost Button
**Role:** Outlined button, light background

Ghost button with Paper White (#fffcf2) background, border and text in Graphite (#545454). Text at 24px Instrument Sans Variable, weight 400. Square corners (0px radius). Generous 24px vertical and horizontal padding.

### Accent Tag Button
**Role:** Segmented control option / tag

Used for filtering or categorization. Background is Paper White (#fffcf2), text is Warm Umber (#68655b). Border in Aged Paper (#f0ecdf). Padding 20px vertical, 24px horizontal. No radius.

### Active Navigation Badge
**Role:** Active state indicator for navigation/filters

Filled with Harvest Gold (#f7cf49), text in Midnight Ink (#141414). Geist Mono font, weight 400, typically 14px. Padding 6px vertical, 12px horizontal. No border-radius.

### Information Badge
**Role:** Informational state indicator

Filled with Sky Blue (#a9e1ff), text in Midnight Ink (#141414). Geist Mono font, weight 400, typically 14px. Padding 6px vertical, 12px horizontal. No border-radius.

### Basic Card
**Role:** Content container

Filled with Greige Mist (#d0cec6). No border or shadow, relying on background color for separation. Internal padding of 24px on all sides. Sharp, 0px radius corners.

### Dark Content Card
**Role:** Dark content container for contrast

Filled with Midnight Ink (#141414). No border or shadow. Internal padding of 48px vertical, 24px horizontal. Sharp, 0px radius corners.

### Primary Input Field
**Role:** Text input field

Background in Graphite (#545454), border in Harvest Gold (#f7cf49). Text placeholder color in Harvest Gold (#f7cf49). No padding detected on the field itself, relies on user input to define dimensions. Sharp, 0px radius corners.

## Do's and Don'ts

### Do
- Prioritize Instrument Sans Variable for all primary content and headings, leveraging its compressed letter-spacing for visual punch.
- Use Geist Mono exclusively for UI elements that require a technical or tagged feel, always with generous positive letter-spacing.
- Employ Midnight Ink (#141414) for primary text and dark backgrounds, establishing strong contrast.
- Utilize Paper White (#fffcf2) and Aged Paper (#f0ecdf) as primary and secondary background surfaces to build a layered, tactile feel.
- Apply Harvest Gold (#f7cf49) sparingly for active states, calls-to-action, and key indicators to maintain its visual impact.
- Maintain a consistent 0px border-radius across all buttons, cards, and interactive elements for a sharp, geometric aesthetic.
- Use thin, 1px borders in neutrals like Greige Mist (#d0cec6) or Aged Paper (#f0ecdf) to define regions without heavy visual weight.

### Don't
- Avoid using any non-system fonts for text, as the custom typefaces are essential to Quin's identity.
- Do not introduce rounded corners, as the system explicitly uses 0px radius for all components.
- Refrain from adding arbitrary color accents; stick to Harvest Gold (#f7cf49) for primary highlights and Sky Blue (#a9e1ff) for semantic info.
- Do not use drop shadows or complex elevation; the system relies on flat colors and distinct borders for layering.
- Avoid generic spacing values; adhere to the 8px base unit with defined gaps for elements (24px) and sections (59px).
- Do not lighten or darken the primary colors for hover/active states; use the specified brand-colors--black-hover or other defined interaction states.
- Never use text colors lighter than Graphite (#545454) on light backgrounds to prevent readability issues.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Paper Canvas | `#fffcf2` | Dominant page background, providing a warm, off-white foundation. |
| 2 | Aged Paper Surface | `#f0ecdf` | Secondary background color for sections and subtle content groupings, adding visual texture. |
| 3 | Greige Card | `#d0cec6` | Background for basic cards and contained content sections, visually separating content from the canvas. |
| 4 | Midnight Ink Section | `#141414` | Distinct dark sections, providing strong visual contrast or a header/footer background. |

## Imagery

The imagery aesthetic is highly focused on product UI and relevant integrations. Photography consists of tight crops of product screens on devices (laptops, phones) with a clean, unobtrusive background (wood texture, white/light desk). Illustrations are minimal, primarily functional, like the brand logo or small icons within the UI. Iconography is generally monochromatic, using the primary text color, with a medium stroke weight. Imagery serves primarily to showcase the product's interface and integrations, acting as explanatory content rather than decorative atmosphere. The density is moderate, with images typically contained within clearly defined sections and balanced by text.

## Layout

The page primarily uses a max-width contained layout, though the hero section and some full-width stripes push the background colors to the edges. The hero pattern features a centered, large headline over a full-bleed muted background, with product screenshots often positioned below or to the side of text. Sections alternate between light, warm backgrounds (Paper White, Aged Paper) and darker, more saturated color blocks (Midnight Ink, Sky Blue, Muted Wood) creating a rhythmic, banded flow. Content often uses two-column layouts, with text on one side and a product visual or integration grid on the other. Navigation is a sticky top bar with clearly delineated sections and a ghost 'Get Started' button.

## Agent Prompt Guide

Quick Color Reference: text: #141414, background: #fffcf2, border: #d0cec6, accent: #f7cf49, primary action: #f7cf49 (filled action)

Example Component Prompts:
1. Create an 'About Us' section: Aged Paper (#f0ecdf) background. Headline at 56px Instrument Sans Variable, weight 600, #141414, letter-spacing -1.12px. Body text at 16px Instrument Sans Variable, weight 400, #222222, line-height 1.71. Two-column grid with elementGap 24px.
2. Build a newsletter signup card: Greige Card (#d0cec6) background, 24px padding. Headline at 26px Instrument Sans Variable, weight 500, #141414, letter-spacing -0.442px. Input field with Graphite (#545454) background, Harvest Gold (#f7cf49) border, and Harvest Gold (#f7cf49) placeholder text. Button with Midnight Ink (#141414) background, Greige Mist (#d0cec6) text, 0px radius, 28px vertical padding, 40px horizontal padding.
3. Design a feature list item: Paper White (#fffcf2) background with a 1px Greige Mist (#d0cec6) border. Icon (use any appropriate functional icon) in #141414. Heading at 20px Instrument Sans Variable, weight 600, #141414. Description at 14px Instrument Sans Variable, weight 400, #545454.
4. Create a top navigation bar: Paper White (#fffcf2) background, 1px Greige Mist (#d0cec6) bottom border. Navigation links `Login` and `Pricing` using Instrument Sans Variable, 14px, #545454. Active tab badge for 'Features' using Harvest Gold (#f7cf49) background, Midnight Ink (#141414) text, Geist Mono 14px, letter-spacing 1.5px, 6px vertical padding, 12px horizontal padding. Ghost 'Get Started' button bordered by #d0cec6, text #141414, 0px radius, 28px vertical padding, 40px horizontal padding.

## Similar Brands

- **Airtable** — Similar focus on organized information hierarchy, clean UI, and a subtle but distinct color accent.
- **Linear** — Emphasizes structured, efficient interfaces with sharp lines and purposeful typography, often utilizing a single accent color.
- **Notion** — Features a white-canvas approach, clear content blocks, and a productivity-focused utility aesthetic.
- **Supabase** — Uses a similar warm-neutral palette with a strong, minimal geometric aesthetic and emphasis on clear content separation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-paper-white: #fffcf2;
  --color-greige-mist: #d0cec6;
  --color-aged-paper: #f0ecdf;
  --color-graphite: #545454;
  --color-warm-umber: #68655b;
  --color-deep-ash: #222222;
  --color-harvest-gold: #f7cf49;
  --color-muted-wood: #492812;
  --color-sky-blue: #a9e1ff;
  --color-placeholder-grey: #a19c8c;

  /* Typography — Font Families */
  --font-instrument-sans-variable: 'Instrument Sans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-font-awesome-7-sharp: 'Font Awesome 7 Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: 0.107px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.046px;
  --text-body: 16px;
  --leading-body: 1.71;
  --tracking-body: 0.171px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.007px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.007px;
  --text-heading: 40px;
  --leading-heading: 1.05;
  --tracking-heading: -0.017px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.02px;
  --text-display: 96px;
  --leading-display: 0.92;
  --tracking-display: -0.033px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 59px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;

  /* Surfaces */
  --surface-paper-canvas: #fffcf2;
  --surface-aged-paper-surface: #f0ecdf;
  --surface-greige-card: #d0cec6;
  --surface-midnight-ink-section: #141414;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-paper-white: #fffcf2;
  --color-greige-mist: #d0cec6;
  --color-aged-paper: #f0ecdf;
  --color-graphite: #545454;
  --color-warm-umber: #68655b;
  --color-deep-ash: #222222;
  --color-harvest-gold: #f7cf49;
  --color-muted-wood: #492812;
  --color-sky-blue: #a9e1ff;
  --color-placeholder-grey: #a19c8c;

  /* Typography */
  --font-instrument-sans-variable: 'Instrument Sans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-font-awesome-7-sharp: 'Font Awesome 7 Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: 0.107px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.046px;
  --text-body: 16px;
  --leading-body: 1.71;
  --tracking-body: 0.171px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.007px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.007px;
  --text-heading: 40px;
  --leading-heading: 1.05;
  --tracking-heading: -0.017px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.02px;
  --text-display: 96px;
  --leading-display: 0.92;
  --tracking-display: -0.033px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
}
```
