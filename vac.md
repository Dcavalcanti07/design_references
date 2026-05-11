# V–A–C — Style Reference
> Architectural grid on white

**Theme:** light

V–A–C embraces a highly structured, almost architectural aesthetic, presenting content within a minimalist, monochrome grid. Information is delivered with an academic rigor: thin lines, expansive white space, and stark black typography create a sense of directness without embellishment. The design prioritizes visual organization and content discovery through a precise, fixed-width layout and sparse use of interactive elements, giving the impression of an expertly curated digital catalog.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text (dark theme) |
| Ink Black | `#000000` | `--color-ink-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Accent Gray | `#999999` | `--color-accent-gray` | Decorative strokes, subtle secondary graphical elements |

## Tokens — Typography

### Diagramatika Text — Body copy, link text, card subtitles, input text — conveys clear information without demanding attention. · `--font-diagramatika-text`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 16px, 20px
- **Line height:** 1.00, 1.10, 1.15
- **Letter spacing:** normal
- **Role:** Body copy, link text, card subtitles, input text — conveys clear information without demanding attention.

### Diagramatika Display — Headlines, section titles, card titles — large and impactful, yet light in weight, establishing hierarchy subtly. · `--font-diagramatika-display`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 24px, 34px, 35px
- **Line height:** 0.88, 0.90, 1.15
- **Letter spacing:** normal
- **Role:** Headlines, section titles, card titles — large and impactful, yet light in weight, establishing hierarchy subtly.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.15 | — | `--text-body-sm` |
| body | 20px | 1.1 | — | `--text-body` |
| subheading | 24px | 1.15 | — | `--text-subheading` |
| heading | 34px | 0.9 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 20 | 20px | `--spacing-20` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 150px
- **Card padding:** 0px
- **Element gap:** 5px

## Components

### Ghost Text Button (Dark Text)
**Role:** Primary interactions and navigation links

Transparent background with Ink Black text. No padding, border, or radius. Text uses Diagramatika Text or Display, weight 400. Example: 'Search' or 'Load more'.

### Ghost Text Button (Light Text)
**Role:** Interactive elements on dark sections, such as language toggles

Transparent background with Canvas White text. No padding, border, or radius. Text uses Diagramatika Text, weight 400. Example: 'ru' / 'en'.

### Minimal Card
**Role:** Displaying informational blocks like event listings

Transparent background with no border-radius or box-shadow. Content is tightly aligned, often directly on the canvas. Padding is 0px. Top padding can vary (258px, 271px, 274px, 275px) depending on image height. Example: Event listings like 'Alexandra Sukhareva. Beginnings'.

### Line Input
**Role:** Form inputs for search or data entry

Transparent background with Ink Black text and a 1px Ink Black underline. Left padding is 2px. No border radius. Text uses Diagramatika Text, weight 400.

## Do's and Don'ts

### Do
- Use 'Ink Black' (#000000) for all text color, borders, and interactive elements where contrast is paramount.
- Maintain a strict '0px' border-radius for all interactive and display elements, adhering to the sharp, angular aesthetic.
- Employ 'Diagramatika Text' (400) for all body copy and most UI labels, prioritizing clarity over decoration.
- Employ 'Diagramatika Display' (400) for headlines and major navigational elements, with sizes 24px, 34px, or 35px.
- Ensure ample whitespace between sections using '150px' vertical spacing (`sectionGap`).
- Design all interactive elements, such as buttons and links, as transparent backgrounds with only text and a border where necessary.
- Utilize 'Accent Gray' (#999999) sparingly for subtle decorative strokes, not for primary UI elements.

### Don't
- Avoid using any colors other than Canvas White, Ink Black, and Accent Gray for primary UI elements and text.
- Do not introduce any border-radius greater than '0px' on any component or surface.
- Never apply box-shadows or elevation effects; the design system relies on flat surfaces and lines.
- Do not introduce any explicit background colors for cards; they should appear as content directly on the canvas.
- Avoid decorative imagery that breaks the monochrome, grid-based aesthetic, unless it is content within a card.
- Do not use letter-spacing adjustments; all typography should maintain 'normal' letter-spacing.
- Refrain from using any gradient fills; surfaces should be solid colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default surface for content. |

## Imagery

Imagery largely consists of contained, unedited photographs and occasionally product/installation shots, serving as direct content rather than decorative elements. They are displayed within minimalist card containers without rounded corners or shadows, sitting directly on the white canvas. The treatment is raw, with no specific color filters beyond the original photo's intent. Icons (like the arrow for events) are minimal, outlined, and monochromatic, using 'Ink Black' (#000000). Imagery functions as explanatory content or event showcases, allowing the text to provide context.

## Layout

The page operates on a full-bleed model horizontally, with content contained within a flexible-width, vertically oriented grid. The hero section often features a clean line and heading (like 'GES-2', 'V', 'A', 'C') at the top, acting as a navigational anchor. Section rhythm is dictated by a consistent '150px' vertical gap between content blocks. Content is arranged primarily in a two-column grid where text and imagery flow in a linear, timeline-like sequence down the page without alternating patterns. Navigation is minimal, consisting of text links in the header and alongside sections, with a fixed position vertical navigation bar with rotated text. The design is compact in its element spacing but generous in its section spacing.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #000000 (primary visual accent)
primary action: no distinct CTA color

Example Component Prompts:
Create a header link: Using Diagramatika Text 400 at 16px, color #000000, no background.
Create an event card title: 'The Oldest Person in the World.' using Diagramatika Display 400 at 34px, color #000000.
Create a search input: Transparent background input with a 1px #000000 bottom border, 2px padding-left, using Diagramatika Text 400 at 16px, color #000000.
Create a navigation marker: Vertical text 'Architecture' using Diagramatika Text 400 at 16px, color #000000, rotated -90deg.

## Similar Brands

- **The Tate Modern** — Similar white-space-heavy, precise typographic approach for an institutional feel.
- **MoMA Design Store** — Employs a stark, grid-based layout with minimal color, focusing on content and product arrangement.
- **Studio—JQ** — Many portfolio sites use a similar monochrome, high-contrast, no-radius aesthetic with strong typography.
- **Bauhaus Archive** — Historical design influences that prioritize function, clean lines, and a minimalist color palette, similar to the V–A–C approach.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-accent-gray: #999999;

  /* Typography — Font Families */
  --font-diagramatika-text: 'Diagramatika Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-diagramatika-display: 'Diagramatika Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.15;
  --text-body: 20px;
  --leading-body: 1.1;
  --text-subheading: 24px;
  --leading-subheading: 1.15;
  --text-heading: 34px;
  --leading-heading: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-20: 20px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-150: 150px;

  /* Layout */
  --section-gap: 150px;
  --card-padding: 0px;
  --element-gap: 5px;

  /* Named Radii */
  --radius-all: 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-accent-gray: #999999;

  /* Typography */
  --font-diagramatika-text: 'Diagramatika Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-diagramatika-display: 'Diagramatika Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.15;
  --text-body: 20px;
  --leading-body: 1.1;
  --text-subheading: 24px;
  --leading-subheading: 1.15;
  --text-heading: 34px;
  --leading-heading: 0.9;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-20: 20px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-150: 150px;
}
```
