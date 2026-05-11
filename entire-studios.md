# entire studios — Style Reference
> Gallery White Box – stark, unadorned surfaces presenting content with minimalist precision.

**Theme:** light

This system feels like a minimalist gallery space, emphasizing raw visual impact and an almost ascetic reduction of UI ornamentation. The stark monochromatic palette of deep black and pale slate, punctuated only by occasional bright white elements, directs focus entirely to the content. Type is exclusively monospaced, lending a technical, almost archival quality, while the complete absence of rounded corners or shadows reinforces a sharp, uncompromising aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, icon fill, button borders — defining the core contrasts and visual anchors of the UI. |
| Pale Slate | `#e7ecea` | `--color-pale-slate` | Section backgrounds and subtle dividers, providing a minimal softening against pure white or black. |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds and sometimes as text for maximum contrast against dark elements. |

## Tokens — Typography

### Space Mono — All textual elements: body text, links, buttons, headers. Its monospaced, fixed-width nature is a signature choice, lending a precise, technical, and almost retro-digital atmosphere to all copy. It dictates a structured, grid-like rhythm even in paragraphs. · `--font-space-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.33, 1.50
- **Letter spacing:** normal
- **Role:** All textual elements: body text, links, buttons, headers. Its monospaced, fixed-width nature is a signature choice, lending a precise, technical, and almost retro-digital atmosphere to all copy. It dictates a structured, grid-like rhythm even in paragraphs.

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 6px

## Components

### Ghost Navigation Button
**Role:** Interactive element (e.g. navigation, filters)

Transparent background, Midnight Ink text and border, 0px border-radius. Padding: 0px top/bottom, 6px left/right. Font: Space Mono 12px, weight 400, normal letter spacing. This button is designed to be minimal to not distract from content.

## Do's and Don'ts

### Do
- Maintain a strictly monochromatic palette, primarily utilizing Midnight Ink (#000000), Pale Slate (#e7ecea), and Arctic White (#ffffff).
- Use 'Space Mono' exclusively for all typography at 12px or 16px with respective line heights.
- Apply 0px border-radius to all elements, maintaining sharp, clean edges.
- Utilize 6px as the base unit for horizontal padding and gaps between small inline elements.
- Prioritize text-based UI elements over graphical icons for navigation and actions.

### Don't
- Avoid using any colors outside the defined monochromatic palette for UI elements.
- Do not introduce any rounded corners or soft edges on buttons, cards, or other interactive components.
- Refrain from using drop shadows or complex elevation effects; depth is created through color contrast and plane changes.
- Do not deviate from 'Space Mono' as the sole typeface. No sans-serif or serif fonts.
- Avoid decorative imagery; content visuals should be functional product shots or abstract textural backgrounds.

## Imagery

Imagery consists primarily of high-fashion and editorial photography, either full-bleed as main hero content or tightly integrated with text. The treatment is raw and untamed, with a distinct absence of masks, overlays, or structured framing. Photography drives the mood and ambiance, acting as large, immersive backdrops or focal points, rather than contained decorative elements. Photography is dominant, often full-screen, making the site feel image-heavy despite minimalist UI elements. No specific icons are visible in the provided data beyond generic UI elements.

## Layout

The page maintains a full-bleed structure without a fixed `pageMaxWidth` container, allowing imagery to extend edge-to-edge. The hero section features a centered, large headline over a full-viewport background image. Content sections appear to flow with consistent vertical spacing, creating an airy, gallery-like feel. Navigation is a minimal top bar with left-aligned 'shop' and right-aligned utility links, all in small, uppercase Space Mono. The overall impression is information-dense but visually sparse, driven by strong photography and precise typography.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Midnight Ink)
- Background (Primary): #ffffff (Arctic White)
- Background (Secondary): #e7ecea (Pale Slate)
- Button Border: #000000 (Midnight Ink)

### 3-5 Example Component Prompts
1. Create a hero section: Full-bleed background image. Centered headline 'entire studios' at 16px Space Mono, weight 400, color #000000. Display a transparent ghost navigation button 'Shop' at the top left and 'Search', 'EUR', 'Bag (0)' on the top right, all text #000000, Space Mono 12px, weight 400, with 0px padding-top/bottom and 6px padding-left/right.
2. Create a product listing card: Arctic White background. Image takes 70% height at top, 0px radius. Below image, product name 'Product X' Space Mono 16px weight 400, color #000000, padding 16px. Price '€XXX' Space Mono 12px weight 400, color #000000, padding 16px. No border or shadow, 0px radius for card.
3. Create a secondary information section: Pale Slate background. Centered title 'About Us' Space Mono 16px weight 400, color #000000. Body text below, Space Mono 12px weight 400, color #000000. All text elements vertically spaced by 16px, all elements have 0px radius and 0px padding.

## Similar Brands

- **Acne Studios** — Similar high-fashion, clean, and minimalist aesthetic with stark typography and a focus on abstract or editorial photography.
- **COS** — Shares a monochromatic palette, emphasis on high-quality photography, and a subdued, architectural feel.
- **Our Legacy** — Employs an editorial layout, minimal UI, and strong, often raw, product and lifestyle photography.
- **A-COLD-WALL*** — Uses a similarly stark, almost brutalist approach to UI, with limited color and bold, precise typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-pale-slate: #e7ecea;
  --color-arctic-white: #ffffff;

  /* Typography — Font Families */
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.33;
  --text-base: 16px;
  --leading-base: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 6px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-pale-slate: #e7ecea;
  --color-arctic-white: #ffffff;

  /* Typography */
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.33;
  --text-base: 16px;
  --leading-base: 1.5;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
}
```
