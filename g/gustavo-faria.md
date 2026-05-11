# GUSTAVO Faria © — Style Reference
> Minimalist gallery wall

**Theme:** light

Gustavo Faria's portfolio website presents an austere, high-contrast, text-dominant canvas. Information is structured rigidly with subtle typographic variations to create hierarchy rather than color or extensive spacing. The design emphasizes content clarity and directness through a near-monochromatic palette and a compact layout, punctuated by a single, striking personal image that challenges the otherwise stark presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, prominent headings |
| Graphite | `#282828` | `--color-graphite` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Pale Ash | `#dcdcdc` | `--color-pale-ash` | Muted secondary text, subtle dividers, inactive states |
| Blush Tone | `#efc4b2` | `--color-blush-tone` | Background for personal imagery |

## Tokens — Typography

### custom_21879 — Primary headings and interactive links. The tight letter spacing for large text creates a condensed, impactful visual. · `--font-custom21879`
- **Weights:** 400, 700
- **Sizes:** 12px, 142px
- **Line height:** 0.81, 1.00, 1.17, 1.67
- **Letter spacing:** -0.0470em at sizes >= 12px
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** Primary headings and interactive links. The tight letter spacing for large text creates a condensed, impactful visual.

### custom_49610 — Large display headings, specifically for the year range. Its imposing size commands attention in an otherwise subdued layout. · `--font-custom49610`
- **Weights:** 400
- **Sizes:** 125px
- **Line height:** 1.02
- **Letter spacing:** normal
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** Large display headings, specifically for the year range. Its imposing size commands attention in an otherwise subdued layout.

### -apple-system — All body text and descriptive information, providing clarity and system-level familiarity. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0`
- **Role:** All body text and descriptive information, providing clarity and system-level familiarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.17 | -0.047px | `--text-caption` |
| body | 16px | 1 | — | `--text-body` |
| heading | 125px | 1.02 | — | `--text-heading` |
| display | 142px | 0.81 | -0.047px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Card padding:** 0px
- **Element gap:** 1px

## Components

### Work Entry Link
**Role:** Interactive list item

Text link using custom_21879, weight 400 for primary text and Pale Ash for secondary descriptor. Underlined with graphite on hover (or current selected item). No padding, using negative letter-spacing for visual density.

### Navigation Link
**Role:** Top-level navigation

Simple text link in Ink Black, using custom_21879 at 12px, weight 400, with tight letter-spacing. Minimal padding around text.

### Year Range Display
**Role:** Large decorative heading

Large text element using custom_49610, 125px for individual years and custom_21879, 142px for the dash, both in Ink Black, normal letter spacing. Forms a prominent visual anchor on the page.

## Do's and Don'ts

### Do
- Prioritize text as the primary vehicle for information and hierarchy, using color only for stark contrast or subtle guidance.
- Maintain a monochromatic palette with Canvas White backgrounds, Ink Black for primary text, and Graphite or Pale Ash for secondary details.
- Use custom_21879 (or suitable substitute) for all interactive text and primary headings, embracing its tight letter-spacing for visual impact.
- Apply 0px border-radius to all elements to reinforce a sharp, unyielding aesthetic.
- Ensure horizontal lines or borders are 1px thick and use Pale Ash for subtle visual separation between list items or sections.
- Keep spacing between elements minimal, often 1px, to create a compact and dense information display.

### Don't
- Avoid colorful or decorative elements outside of explicit imagery; the interface should remain stark and functional.
- Do not introduce soft shadows or gradients, as the system relies on flat surfaces and hard edges.
- Do not use multiple font families for body text or navigation; stick to the defined typographic system.
- Refrain from generous padding or excessive white space between repeating elements to maintain the compact presentation.
- Do not use bold weights indiscriminately; reserve weight 700 for specific high-emphasis elements identified in `custom_21879` roles.

## Imagery

The site primarily uses idiosyncratic, distorted photography of faces, specifically a self-portrait, contained within irregular, organic cutouts. These images are not product showcases but serve as a strong personal brand statement, directly contrasting the minimalist UI. They operate decoratively and as a focal point, occupying a significant visual area and bringing an element of surrealism to the otherwise structured page. Icons are absent, and UI elements are purely textual or geometric.

## Layout

The page adheres to a predominantly full-bleed model, with a centered content block for the bio and navigation. The hero section features a large, horizontally dominant year range (2019-2025) at the top right, contrasting with the bio on the left. Content is primarily organized into two main columns: a left column for bio text (and a personal image) and a right column for the 'Work Selection' list. The work list items are presented in a compact, vertically stacked format, separated by 1px Pale Ash lines. There is no explicit max-width constraint; content adapts to the viewport. A sticky top navigation containing 'Gustavo Faria', 'Info', and 'Instagram' seems present.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #282828
accent: #efc4b2
primary action: no distinct CTA color

Example Component Prompts:
1. Create a top navigation bar: Canvas White background. 'Gustavo Faria', 'Info', 'Instagram' as text links using custom_21879, weight 400, 12px, Ink Black. Minimal 4px padding between items.
2. Design a work list item: 'Consul' as main text using custom_21879, weight 400, Ink Black, 12px. Secondary text 'Visual Identity, Motion Design' uses -apple-system, 16px, Pale Ash. Separated by a 1px Pale Ash border bottom.
3. Create the large year heading '2025': Use custom_49610, 125px, weight 400, Ink Black, normal letter-spacing.

## Similar Brands

- **Rik Lomas** — Monochromatic palette, text-heavy layout, and distinct visual identity through unique imagery.
- **Julien Van Havere** — Stark white background, strong typographic hierarchy, and minimalist content presentation with bold graphic elements.
- **Studio Fnt** — Emphasis on black and white, unconventional use of typography, and a strong, almost brutalist approach to visual design.
- **Active Theory** — High-contrast, text-forward design with sparse but impactful visual interruptions, often with a surreal or artistic bent.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #282828;
  --color-pale-ash: #dcdcdc;
  --color-blush-tone: #efc4b2;

  /* Typography — Font Families */
  --font-custom21879: 'custom_21879', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom49610: 'custom_49610', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.17;
  --tracking-caption: -0.047px;
  --text-body: 16px;
  --leading-body: 1;
  --text-heading: 125px;
  --leading-heading: 1.02;
  --text-display: 142px;
  --leading-display: 0.81;
  --tracking-display: -0.047px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;

  /* Layout */
  --card-padding: 0px;
  --element-gap: 1px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #282828;
  --color-pale-ash: #dcdcdc;
  --color-blush-tone: #efc4b2;

  /* Typography */
  --font-custom21879: 'custom_21879', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-custom49610: 'custom_49610', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.17;
  --tracking-caption: -0.047px;
  --text-body: 16px;
  --leading-body: 1;
  --text-heading: 125px;
  --leading-heading: 1.02;
  --text-display: 142px;
  --leading-display: 0.81;
  --tracking-display: -0.047px;

  /* Spacing */
}
```
