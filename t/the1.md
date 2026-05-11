# The1 — Style Reference
> Brutalist Canvas, Bold Statements

**Theme:** light

THE1 employs a brutalist-adjacent aesthetic, contrasting oversized, confident typography against a stark, neutral background. Visual interest comes from bold, full-bleed color blocks that serve as vibrant backdrops for imagery, creating a deliberate tension with the otherwise minimalist UI. Interactive elements are understated, often using ghost styling or minimal borders, allowing the bold color fields and strong type to dominate the visual hierarchy. The overall impression is one of directness and impact, favoring large-scale graphic statements over intricate details or subtle gradients.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Gray | `#d9d9d9` | `--color-canvas-gray` | Page backgrounds, large structural elements, subtle distinctions for content sections |
| Text Black | `#000000` | `--color-text-black` | Primary text, headings, icons, strong borders |
| Surface Black | `#1f1f1f` | `--color-surface-black` | Minimal interactive element backgrounds, outlining ghost buttons, secondary text |
| Vivid Green | `#027b49` | `--color-vivid-green` | Large, full-bleed decorative background blocks for specific content zones, creating visual breaks and focal points |
| Vivid Pink | `#f19ec8` | `--color-vivid-pink` | Large, full-bleed decorative background blocks for specific content zones, adding dynamic, high-contrast visual sections |
| Vivid Red | `#fa4d43` | `--color-vivid-red` | Large, full-bleed decorative background blocks for specific content zones, signaling boldness and attention |
| Vivid Yellow | `#fbb833` | `--color-vivid-yellow` | Large, full-bleed decorative background blocks, adding an energetic and bright counterpoint |

## Tokens — Typography

### KH Teka — Headlines and primary content. Its oversized, tight-tracked presence defines the site's bold and direct voice. · `--font-kh-teka`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 15px, 18px, 26px, 60px, 215px
- **Line height:** 0.70, 0.80, 1.00, 1.10, 1.20
- **Letter spacing:** -0.06em at 215px, -0.03em at 18px
- **Role:** Headlines and primary content. Its oversized, tight-tracked presence defines the site's bold and direct voice.

### sans-serif — Small body text, labels, and helper text, providing a highly legible contrast to the large headlines. · `--font-sans-serif`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Small body text, labels, and helper text, providing a highly legible contrast to the large headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1 | — | `--text-caption` |
| body-sm | 18px | 1 | — | `--text-body-sm` |
| body | 26px | 1 | — | `--text-body` |
| body-lg | 60px | 1 | — | `--text-body-lg` |
| heading-sm | 215px | 1 | — | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 100 | 100px | `--spacing-100` |
| 130 | 130px | `--spacing-130` |
| 170 | 170px | `--spacing-170` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 30px |
| general | 100px |
| circular | 5000px |

### Layout

- **Section gap:** 40px
- **Card padding:** 14px
- **Element gap:** 10px

## Components

### Ghost Primary Button
**Role:** Call to action for key interactions.

Text in Text Black (#000000) on transparent background, with a 1px border in Surface Black (#1f1f1f). Significantly rounded with a 30px border-radius. Padding 6px vertical, 14px horizontal. Uses sans-serif font at 12px, weight 400.

### Image Card with Color Background
**Role:** Displaying property options or feature highlights.

Each card uses a full-bleed image (implied) over one of the 'Vivid' brand colors (#027b49, #f19ec8, #fa4d43, #fbb833) as its background. No explicit borders or shadows. The content text is often Text Black (#000000).

### Navigation Link
**Role:** Main site navigation and contextual links.

Text Black (#000000) using KH Teka Regular, 15px. Underlined on hover (implied).

### Hero Headline
**Role:** Dominant page titles and impactful statements.

Very large KH Teka Regular, 215px, weight 400, with tight letter-spacing (-0.06em). Uses Text Black (#000000).

## Do's and Don'ts

### Do
- Prioritize oversized KH Teka headlines with Text Black (#000000) and tight letter-spacing, allowing them to dominate the visual field.
- Use Vivid Green (#027b49), Vivid Pink (#f19ec8), Vivid Red (#fa4d43), and Vivid Yellow (#fbb833) as full-bleed background sections to create strong visual breaks between content blocks.
- Maintain a clear hierarchy with Text Black (#000000) for primary text and Surface Black (#1f1f1f) for secondary text or ghost button outlines.
- Apply a 30px border-radius to all interactive buttons and smaller element containers for a consistent, soft edge.
- Ensure generous negative space around large typographic elements and content blocks, primarily using Canvas Gray (#d9d9d9) as the background.
- Use a default element gap of 10px and small vertical padding of 6px/14px for buttons to maintain a compact density.
- Favor ghost buttons with a thin Surface Black (#1f1f1f) border over filled buttons, unless a specific background contrast is required within a colored section.

### Don't
- Avoid subtle gradients or soft shadows; the design relies on stark contrasts and flat color fields.
- Do not introduce new typefaces; rely solely on KH Teka and a system sans-serif for all typographic needs.
- Refrain from using small, intricate decorations or excessive iconography; content and typography should be the primary visual focus.
- Do not deviate from the established rounded border radii; avoid sharp corners or varying radii across similar components.
- Avoid cluttering the layout; content blocks should be distinct and not overlap visually.
- Do not use highly saturated colors for text or primary UI elements; reserve the 'Vivid' colors for full-bleed background sections only.
- Do not introduce complex component states or animations that distract from the static visual impact.

## Imagery

Imagery consists of tight, architectural product photography, primarily focusing on building exteriors. Each image is presented as part of a full-bleed block, often paired with a vibrant, solid color background, creating a segmented but cohesive visual identity. Graphics are primarily the oversized, bold typography, which functions as a key visual element rather than a pure informational vehicle. Icons are minimal, outlined, and in Text Black.

## Layout

The page model is full-bleed, using the entire viewport width for backgrounds. The hero section features oversized, centered headlines over a Canvas Gray background. Content sections alternate between the Canvas Gray background and large, full-bleed blocks of vibrant brand colors, each often containing an architectural image. Content arrangement is typically aligned left with generous vertical spacing between sections, sometimes featuring a compact product listing format.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #d9d9d9
border: #1f1f1f
accent: #027b49
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Canvas Gray (#d9d9d9) background. Headline 'For the one' using KH Teka 215px, weight 400, Text Black (#000000), letter-spacing -0.06em. Below it, the word 'Creative' using the same style. Add a small body text 'Office space at NDSM-wharf...' using sans-serif 12px, weight 400, Text Black (#000000). Below that, a ghost button: Text Black (#000000) on transparent, 1px border in Surface Black (#1f1f1f), 30px radius, 6px 14px padding, sans-serif 12px.

Create an image card for 'The Green': Full-bleed background of Vivid Green (#027b49). Image of a building on top. Below the image, text 'The Green' in Text Black (#000000), sans-serif 12px, weight 400. Subtext 'Available from 400 sq.m. LFA' in Text Black (#000000), sans-serif 12px, weight 400.

Create a navigation item: Link 'About' in Text Black (#000000) using KH Teka 15px, weight 400.

Generate a 'Why are we the one?' section: Canvas Gray (#d9d9d9) background. Heading 'Why are we the one?' using KH Teka 60px, weight 400, Text Black (#000000), letter-spacing -0.03em. Underneath, a full-bleed section with Vivid Red (#fa4d43) background.

## Similar Brands

- **AIGA** — Exploits oversized typography and bold, flat color blocking on a minimalist canvas.
- **The Brand New (blog)** — Focus on crisp typography, high contrast, and a direct, almost brutalist approach to visual communication.
- **Studio Dumbar** — Known for bold, graphic statements with strong colors and assertive typography, often with a stark, minimal backdrop.
- **Superside** — Uses large type, simple layouts, and impactful hero sections with a focus on product or architectural visuals.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-gray: #d9d9d9;
  --color-text-black: #000000;
  --color-surface-black: #1f1f1f;
  --color-vivid-green: #027b49;
  --color-vivid-pink: #f19ec8;
  --color-vivid-red: #fa4d43;
  --color-vivid-yellow: #fbb833;

  /* Typography — Font Families */
  --font-kh-teka: 'KH Teka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1;
  --text-body-sm: 18px;
  --leading-body-sm: 1;
  --text-body: 26px;
  --leading-body: 1;
  --text-body-lg: 60px;
  --leading-body-lg: 1;
  --text-heading-sm: 215px;
  --leading-heading-sm: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-130: 130px;
  --spacing-170: 170px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 14px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-full: 100px;
  --radius-full-2: 200px;
  --radius-full-3: 5000px;

  /* Named Radii */
  --radius-buttons: 30px;
  --radius-general: 100px;
  --radius-circular: 5000px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-gray: #d9d9d9;
  --color-text-black: #000000;
  --color-surface-black: #1f1f1f;
  --color-vivid-green: #027b49;
  --color-vivid-pink: #f19ec8;
  --color-vivid-red: #fa4d43;
  --color-vivid-yellow: #fbb833;

  /* Typography */
  --font-kh-teka: 'KH Teka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1;
  --text-body-sm: 18px;
  --leading-body-sm: 1;
  --text-body: 26px;
  --leading-body: 1;
  --text-body-lg: 60px;
  --leading-body-lg: 1;
  --text-heading-sm: 215px;
  --leading-heading-sm: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-130: 130px;
  --spacing-170: 170px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-full: 100px;
  --radius-full-2: 200px;
  --radius-full-3: 5000px;
}
```
