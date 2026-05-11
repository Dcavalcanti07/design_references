# Franco Maria Ricci Editore — Style Reference
> Ivory Page, Golden Inscription

**Theme:** light

Franco Maria Ricci's design system evokes the gravitas of classic publishing with a pristine white canvas and sharp, high-contrast typography. Its visual identity relies on subtle use of a single, rich gold accent for highlighting and interactive states, creating an understated elegance. Components are minimal, often borderless and shadowless, allowing the content—primarily art books—to command attention. The overall impression is one of sparse luxury and meticulous curation, where visual space is as important as the elements it contains.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surface backgrounds, neutral text |
| Warm Paper | `#f6f6f6` | `--color-warm-paper` | Subtle background for sections, creating a slight textural difference from the main canvas |
| Faded Gray | `#b3b3b3` | `--color-faded-gray` | Muted background elements, creating soft contrast in certain sections |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, iconography — providing high contrast against light surfaces |
| Baroque Gold | `#bc9c5c` | `--color-baroque-gold` | Accent for headings, interactive borders, links, and decorative elements — signifying importance and elegance |

## Tokens — Typography

### BodoniSvntytwoITCStd-Book — Primary typeface for all core content, headings, and UI elements. Its classic serifs contribute to the brand's authoritative and artistic tone. The tightest line-heights are for display-level text, while smaller body text uses more generous spacing. · `--font-bodonisvntytwoitcstd-book`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px, 22px, 42px
- **Line height:** 0.95, 1.25
- **Letter spacing:** normal
- **Role:** Primary typeface for all core content, headings, and UI elements. Its classic serifs contribute to the brand's authoritative and artistic tone. The tightest line-heights are for display-level text, while smaller body text uses more generous spacing.

### BodoniSvntytwoITCStd-BookIt — Used for emphasizing select headings and body text, providing a calligraphic accent within the core Bodoni family. · `--font-bodonisvntytwoitcstd-bookit`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px, 22px, 42px
- **Line height:** 1.25
- **Letter spacing:** normal
- **Role:** Used for emphasizing select headings and body text, providing a calligraphic accent within the core Bodoni family.

### Arial — Secondary sans-serif for functional text, helper text, and some navigation elements, providing legibility at small sizes while maintaining a modern, understated presence. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400, 700
- **Sizes:** 12px, 14px
- **Line height:** 1.25
- **Letter spacing:** normal
- **Role:** Secondary sans-serif for functional text, helper text, and some navigation elements, providing legibility at small sizes while maintaining a modern, understated presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.25 | — | `--text-caption` |
| body-sm | 14px | 1.25 | — | `--text-body-sm` |
| body | 16px | 1.25 | — | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 22px | 1.25 | — | `--text-heading-sm` |
| heading | 42px | 0.95 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

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
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 20px

## Components

### Ghost Button
**Role:** Interactive elements with minimal visual footprint, often acting as links or secondary actions. Their visual weight is conveyed through text and a subtle border or underline.

Background: transparent. Text color: Midnight Ink (#000000). Border: 1px solid Midnight Ink (#000000) only for some variants, others borderless. Radius: 0px. Padding: 0px.

### Outlined Accent Button
**Role:** Primary Call-to-action or important interactive elements, distinguished by the Baroque Gold border.

Background: transparent (rgba(0,0,0,0)). Text color: Baroque Gold (#bc9c5c) or Midnight Ink (#000000). Border: 1px solid Baroque Gold (#bc9c5c). Radius: 0px. Padding: Often 0px, integrated into typography.

### Product Display Card
**Role:** Used to showcase individual product items like books, emphasizing the product image itself.

Background: transparent (rgba(0,0,0,0)). Radius: 0px. Box shadow: none. Padding: 0px top/right/left, 474px bottom (for vertical spacing of content below).

### Text Input (Underlined)
**Role:** Standard input field for forms, with minimal styling.

Background: transparent (rgba(0,0,0,0)). Text color: Midnight Ink (#000000). Border: 1px solid Midnight Ink (#000000) on bottom only. Radius: 0px. Padding: 8px vertical, 0px horizontal.

## Do's and Don'ts

### Do
- Prioritize BodoniSvntytwoITCStd-Book (or a serif substitute) for all headings and body text, especially at larger sizes, to maintain a classic, editorial feel.
- Use Midnight Ink (#000000) for all primary text and main UI borders to ensure high contrast and a strong visual presence.
- Introduce Baroque Gold (#bc9c5c) sparingly, primarily for interactive element borders, links, or decorative accents to draw attention without overwhelming the design.
- Maintain hard, crisp edges: utilize 0px border-radius for all components, including buttons, cards, and input fields.
- Leverage ample whitespace as a primary design element; backgrounds should predominantly be Canvas White (#ffffff) or Warm Paper (#f6f6f6).
- Ensure interactive elements appear as ghost buttons or outlined elements, rather than solid fills, minimizing visual weight.
- When displaying products or imagery, use transparent backgrounds and 0px padding/radius on cards to allow the content to breathe and maintain a gallery-like presentation.

### Don't
- Avoid solid background colors for buttons; they contradict the ghost/outlined aesthetic.
- Do not use highly saturated colors outside the brand's Baroque Gold accent; maintain a largely achromatic palette.
- Refrain from using rounded corners or soft edges on any UI elements; the design emphasizes sharp, precise lines.
- Do not introduce drop shadows for elevation; rely on spacing and subtle background color changes for visual hierarchy.
- Avoid dense, information-heavy layouts; prioritize spaciousness and clear visual separation between elements.
- Do not use font weights other than 400 for serif typefaces, or 400/700 for Arial, to preserve typographic precision.
- Avoid large hero sections with busy imagery; focus on clean typographic statements and minimal visual content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Dominant page background, providing a clean, expansive foundation. |
| 1 | Warm Paper | `#f6f6f6` | Secondary background for content sections, subtly breaking up the main canvas without strong contrast. |
| 2 | Faded Gray | `#b3b3b3` | Background for specific, muted hero or decorative sections, offering a gentle visual shift. |

## Imagery

The visual language focuses heavily on product shots of books, often isolated on neutral backgrounds, showcasing the cover art as the primary visual. When illustrations are present, particularly the Erte artwork, they are highly stylized with strong outlines and often featuring the Baroque Gold as a key color. Iconography tends to be minimalistic, outlined, and in Midnight Ink. Imagery's role is primarily decorative atmosphere and product showcase, with a bias towards text-dominant layouts punctuated by key visuals. The density is moderate, with images usually contained within well-defined, singular areas, not overlapping or full-bleed across sections.

## Layout

The page adheres to a max-width contained layout, though the exact max-width is not defined globally but suggested through consistent margins. The hero section often features a centered headline over a background graphic or illustration. Content flows in distinct sections, often with alternating background colors (Canvas White and Warm Paper) to delineate blocks. A common pattern is a grid-based display for product listings, using 3-column layouts for cards. Navigation is a subtle top bar with minimal elements, suggesting a focus on content browsing rather than complex interactions. The rhythm is spacious and measured, with significant vertical spacing between sections.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #ffffff
- border: #000000
- accent: #bc9c5c
- primary action: #bc9c5c (outlined action border)

**3-5 Example Component Prompts:**
1. Create a section with a heading "Our Selection" (BodoniSvntytwoITCStd-Book, 42px, #000000, lineHeight 0.95), followed by a 3-column grid of Product Display Cards. Each card should have transparent background, 0px border-radius, 0px padding, and contain a product image.
2. Design a navigation link "{ DISCOVER THE SPRING SALES }" using BodoniSvntytwoITCStd-Book, 14px, #000000, with a 1px solid #bc9c5c border-bottom. The element should have 0px padding.
3. Create an input field for a newsletter signup: use a transparent background (rgba(0,0,0,0)), text color #000000, 1px solid #000000 bottom border, 0px border-radius, and 8px vertical padding horizontally centered on the page.
4. Produce a 'Read More' link styled as a Ghost Button: BodoniSvntytwoITCStd-Book, 14px, #000000, with an underline effect defined by a 1px solid #000000 border-bottom, no padding.

## Similar Brands

- **Phaidon** — High-end art book publisher with a focus on editorial design, elegant typography, and product-focused imagery on clean backgrounds.
- **Taschen** — Known for large-format art books, often characterized by classic serif typography, minimal UI, and a premium aesthetic.
- **The New York Times** — Classic serif typography, high-contrast black and white palette with subtle accent colors, and a strong editorial feel for textual content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-warm-paper: #f6f6f6;
  --color-faded-gray: #b3b3b3;
  --color-midnight-ink: #000000;
  --color-baroque-gold: #bc9c5c;

  /* Typography — Font Families */
  --font-bodonisvntytwoitcstd-book: 'BodoniSvntytwoITCStd-Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bodonisvntytwoitcstd-bookit: 'BodoniSvntytwoITCStd-BookIt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --text-heading: 42px;
  --leading-heading: 0.95;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

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
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-none: 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-paper: #f6f6f6;
  --surface-faded-gray: #b3b3b3;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-warm-paper: #f6f6f6;
  --color-faded-gray: #b3b3b3;
  --color-midnight-ink: #000000;
  --color-baroque-gold: #bc9c5c;

  /* Typography */
  --font-bodonisvntytwoitcstd-book: 'BodoniSvntytwoITCStd-Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bodonisvntytwoitcstd-bookit: 'BodoniSvntytwoITCStd-BookIt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --text-heading: 42px;
  --leading-heading: 0.95;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
}
```
