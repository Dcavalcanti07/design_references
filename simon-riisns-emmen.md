# Simon Riisnæs Emmen — Style Reference
> Vibrant billboard minimalism.

**Theme:** light

Simon Riisnæs Emmen's design system is an unapologetic exploration of high-contrast typography and bold, simple color blocking. It uses stark black text on primary colored surfaces to create an assertive, almost confrontational visual impact. Elements are defined by strong horizontal and vertical lines, with extremely rounded shapes providing a playful counterpoint to the otherwise rigid structure. The overall impression is one of directness and creative confidence, relying on fundamental design principles rather than elaborate ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, surface background for list items |
| Sunset Blush | `#fd8878` | `--color-sunset-blush` | Primary accent surface for headline blocks – bold background for prominent text |
| Electric Yellow | `#e8fe04` | `--color-electric-yellow` | Secondary accent surface for headline blocks – vibrant background for prominent text |

## Tokens — Typography

### Tex Gyre Heros — Dominant display font for headlines and prominent interactive elements. Its condensed structure and tight letter-spacing at large sizes contribute to the direct, billboard-like aesthetic. Weight 300 for emphasis, 400 for general text. · `--font-tex-gyre-heros`
- **Substitute:** Helvetica Neue
- **Weights:** 300, 400
- **Sizes:** 29px, 32px, 67px, 173px
- **Line height:** 0.90, 1.20
- **Letter spacing:** -1.5px at 173px, -0.48px at 32px, -0.43px at 29px
- **Role:** Dominant display font for headlines and prominent interactive elements. Its condensed structure and tight letter-spacing at large sizes contribute to the direct, billboard-like aesthetic. Weight 300 for emphasis, 400 for general text.

### Editorial New — Subordinate text and details, providing a classic, serif counterpoint to the bold sans-serif headlines. Normal letter-spacing offers readability for body-like content. · `--font-editorial-new`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 29px
- **Line height:** 1.10, 1.44
- **Letter spacing:** normal
- **Role:** Subordinate text and details, providing a classic, serif counterpoint to the bold sans-serif headlines. Normal letter-spacing offers readability for body-like content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 29px | 1.44 | — | `--text-body` |
| subheading | 32px | 1.2 | -0.48px | `--text-subheading` |
| heading | 67px | 0.9 | -1px | `--text-heading` |
| display | 173px | 0.9 | -1.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 13 | 13px | `--spacing-13` |
| 32 | 32px | `--spacing-32` |
| 63 | 63px | `--spacing-63` |
| 95 | 95px | `--spacing-95` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |
| displayBlocks | 720px |

### Layout

- **Section gap:** 95px
- **Card padding:** 6px
- **Element gap:** 6px

## Components

### Header Navigation Link
**Role:** Interactive text link in the page header.

Plain #000000 text at 29px Tex Gyre Heros, weight 400. Subtle underline appears on hover (implied by border evidence).

### Main Navigation/List Item
**Role:** Interactive element for the main content list, indicating projects or articles.

Tex Gyre Heros, 29px or 32px, mostly weight 400, #000000 text. Items are underlined with a 1px #000000 solid border on hover/active states, and have 253px padding-bottom to separate content heavily.

### Headline Display Block - Words
**Role:** Primary attention-grabbing headline element, visually distinct product name.

Set on a Sunset Blush (#fd8878) background with an extremely rounded 720px border-radius. Features large Tex Gyre Heros text, 173px, weight 400, #000000 color, with -1.5px letter-spacing. Padding a minimum of 95px top/bottom and 32px left/right.

### Headline Display Block - Designed
**Role:** Secondary attention-grabbing headline element, visually distinct product noun.

Set on an Electric Yellow (#e8fe04) background with an extremely rounded 720px border-radius. Features large Tex Gyre Heros text, 173px, weight 400, #000000 color, with -1.5px letter-spacing. Padding a minimum of 95px top/bottom and 32px left/right.

## Do's and Don'ts

### Do
- Prioritize high contrast: Always render #000000 text on Canvas White (#ffffff) or Electric Yellow (#e8fe04) / Sunset Blush (#fd8878) backgrounds.
- Use Tex Gyre Heros for all headlines and prominent text, varying weight between 300 and 400 based on emphasis.
- Employ Editorial New only for supportive, descriptive text or small footnotes, always at weight 400.
- Apply the extreme 720px border-radius only to large, block-level background elements, creating a 'pill' shape.
- Define interactive elements with a 1px solid #000000 border on hover, ensuring clear visual feedback.
- Maintain generous vertical spacing with 95px between major sections and 253px for long list item separations, creating a spacious, relaxed rhythm.
- Use distinct, vibrant color blocks (Sunset Blush or Electric Yellow) to highlight key words or section titles.

### Don't
- Avoid using multiple font families for headlines or primary content; stick to Tex Gyre Heros for impact.
- Do not introduce gradients or shadows; the surface treatment is purposefully flat and stark.
- Do not deviate from the core monochromatic palette with additional chromatic colors, beyond Sunset Blush and Electric Yellow.
- Do not use small, subtle radii; either use the extreme 720px or keep corners sharp.
- Avoid decorative imagery or complex illustrations; the visual system is text-dominant and stark.
- Do not center text unless it's a primary display block; content generally aligns left.
- Refrain from using lightweight fonts for small text that needs to be highly readable; save fine weights for large display, and use Editorial New 400 for body.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Electric Yellow | `#e8fe04` | Prominent content blocks / accents |
| 1 | Sunset Blush | `#fd8878` | Prominent content blocks / accents |

## Imagery

This design system primarily relies on pure UI and typography; there is no discernible visual language for photography or complex illustrations. Iconography (if present) is expected to be simple, outlined, and monochromatic (#000000 on #ffffff). The content itself seems to be the primary visual element, often presented as bold text blocks within colored shapes or as simple list items.

## Layout

The page exhibits a full-bleed layout, taking the full width of the viewport without a max-width container, though internal padding defines content areas. The hero section features large, colorful 'pill-shaped' blocks with centered, oversized text. Subsequent sections present content as a vertically stacked list of items, each separated by a prominent horizontal rule and generous padding. There's a strong emphasis on consistent vertical rhythm and clear visual separation between content blocks, with text generally aligned to the left within the page's implied content area.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Header Navigation Link: Use Tex Gyre Heros, weight 400, size 29px, color #000000, with a 1px solid #000000 bottom border on hover.
2. Design a Headline Display Block with 'Words' text: #fd8878 background, 720px border-radius. Text is 'Words', Tex Gyre Heros, 173px, weight 400, #000000 color, letter-spacing -1.5px. Padding 95px vertical, 32px horizontal.
3. Create a Main List Item: #ffffff background, Tex Gyre Heros, 29px, weight 400, #000000 text. Include a 1px solid #000000 bottom border, and 253px padding-bottom for separation. Item reads '01 Make with Notion 2025'.

## Similar Brands

- **Are.na** — Monochromatic, content-first layout with minimal UI chrome and clear informational hierarchy.
- **Brutalist Websites** — Raw HTML aesthetic, strong typography, and limited color palette, embracing a functional, unpolished feel.
- **The Browser Company (Arc browser website)** — Bold, oversized typography, simple color fields, and a distinct, confident brand voice conveyed through visual directness.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-sunset-blush: #fd8878;
  --color-electric-yellow: #e8fe04;

  /* Typography — Font Families */
  --font-tex-gyre-heros: 'Tex Gyre Heros', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 29px;
  --leading-body: 1.44;
  --text-subheading: 32px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading: 67px;
  --leading-heading: 0.9;
  --tracking-heading: -1px;
  --text-display: 173px;
  --leading-display: 0.9;
  --tracking-display: -1.5px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-13: 13px;
  --spacing-32: 32px;
  --spacing-63: 63px;
  --spacing-95: 95px;

  /* Layout */
  --section-gap: 95px;
  --card-padding: 6px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-full: 720px;

  /* Named Radii */
  --radius-default: 0px;
  --radius-displayblocks: 720px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-electric-yellow: #e8fe04;
  --surface-sunset-blush: #fd8878;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-sunset-blush: #fd8878;
  --color-electric-yellow: #e8fe04;

  /* Typography */
  --font-tex-gyre-heros: 'Tex Gyre Heros', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 29px;
  --leading-body: 1.44;
  --text-subheading: 32px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading: 67px;
  --leading-heading: 0.9;
  --tracking-heading: -1px;
  --text-display: 173px;
  --leading-display: 0.9;
  --tracking-display: -1.5px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-13: 13px;
  --spacing-32: 32px;
  --spacing-63: 63px;
  --spacing-95: 95px;

  /* Border Radius */
  --radius-full: 720px;
}
```
