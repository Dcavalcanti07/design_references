# Intra — Style Reference
> monolithic concrete gallery

**Theme:** light

Intra's design system evokes a stark, utilitarian aesthetic, heavily reliant on bold monochromatic contrasts and raw typographic statements. The visual language is defined by a primary background of industrial gray, offset by sharp white and black elements. Cards and key visuals use a reversed dark theme that feels integrated rather than an overlay, maintaining a consistent high-contrast, blocky presence. Typography is the primary decorative element, with large, unembellished sans-serifs commanding attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Gray | `#e4e4e4` | `--color-canvas-gray` | Page background, subtle borders, muted text |
| Ink Black | `#212529` | `--color-ink-black` | Primary text, major headlines, dark card backgrounds |
| Paper White | `#ffffff` | `--color-paper-white` | Text on dark backgrounds, active states, outlines for ghost buttons |
| Absolute Black | `#000000` | `--color-absolute-black` | Button text, borders for ghost buttons, decorative fills |
| Vivid Pink | `#f78da7` | `--color-vivid-pink` | Decorative card backgrounds, accent for list items |
| Vivid Amber | `#fcb900` | `--color-vivid-amber` | Decorative card backgrounds, accent for list items |
| Vivid Clay | `#dc3545` | `--color-vivid-clay` | Decorative card backgrounds, accent for list items |
| Vivid Green Cyan | `#00d084` | `--color-vivid-green-cyan` | Decorative card backgrounds, accent for list items |

## Tokens — Typography

### Whyte — Primary brand typeface for headings and emphasis. Its robust, compact form at 95px commands vertical space, contributing to the site's blocky structure. Used for link and body text at smaller sizes to maintain brand consistency. · `--font-whyte`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 16px, 18px, 20px, 95px
- **Line height:** 1.00, 1.50
- **Role:** Primary brand typeface for headings and emphasis. Its robust, compact form at 95px commands vertical space, contributing to the site's blocky structure. Used for link and body text at smaller sizes to maintain brand consistency.

### -apple-system — Standard system font for paragraph text and descriptive elements. Its neutral appearance provides readability without distracting from the primary Whyte typeset. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px, 20px
- **Line height:** 1.50
- **Role:** Standard system font for paragraph text and descriptive elements. Its neutral appearance provides readability without distracting from the primary Whyte typeset.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| display | 95px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 78 | 78px | `--spacing-78` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 100% |
| buttons | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** Navigation and secondary actions

Transparent background with 0px border-radius. Text color is #000000, border color is #000000. Padding is 1px top/bottom and 6px left/right. Provides a minimal interactive element that merges with the stark aesthetic.

### Product Display Card
**Role:** Showcasing individual product items with strong branding

Solid background like #f78da7 or #fcb900 with a 0px border-radius and no box shadow. Padding is 0px directly within the card, but content is often nested with a 15px internal padding. Text is typically #ffffff.

### Callout Section Card
**Role:** Highlighting specific information like cafe description or hours

Background is #e4e4e4 for main content or #212529 for reversed blocks. Text is #212529 or #ffffff respectively. No border or border-radius, maintaining a sharp, blocky composition. Significant internal padding (e.g., 50px horizontal, 40px vertical) for liberal whitespace.

## Do's and Don'ts

### Do
- Prioritize high contrast between text and background, especially for #212529 on #e4e4e4 and #ffffff on #212529.
- Use Whyte font at 95px for primary headlines to create a bold, blocky statement.
- Apply 0px border-radius to all buttons and cards, enforcing a sharp, geometric aesthetic.
- Maintain a clear visual hierarchy by limiting color primarily to the neutral palette and using accent colors only for product features or decorative card backgrounds.
- Employ consistent 10px element gaps for inline items and 40px section gaps for vertical rhythm.
- Utilize ghost buttons with #000000 text and 0px border for all interactive elements to preserve the monochromatic, utility-focused style.

### Don't
- Do not introduce rounded corners on primary UI elements such as cards or buttons.
- Avoid gradients or soft shadows that would dilute the stark, high-contrast visual identity.
- Do not use subtle color variations for backgrounds; stick to the defined #e4e4e4 and #212529 surfaces.
- Refrain from using lightweight fonts for anything other than body text to preserve the brand's bold typographic presence.
- Do not use imagery in a way that breaks out of the rigid grid or introduces irregular shapes.
- Avoid decorative icons; keep visual elements strictly photographic or abstract geometric shapes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Gray | `#e4e4e4` | Dominant page background for main content areas. |
| 1 | Ink Black Surface | `#212529` | Darker background for prominent cards and reversed UI sections. |

## Imagery

Imagery follows a stark, functional treatment. Product images appear against solid accent colored backgrounds or are tightly cropped within a blocky system. Photography, when present (e.g., people), is embedded directly into the layout without frames or overlays, adopting the inherent rectangularity of the content block. Iconography is absent, favoring a text-and-block dominant approach. Overall, imagery plays a supportive, content-rich role rather than a decorative one, fitting seamlessly into the rigid grid.

## Layout

The site employs a max-width layout (approximately 900px, derived from inner content blocks) for primary content, which is then centered. The hero section is full-bleed, often featuring a large graphic or logo against a contrasting background. Throughout the page, content is arranged in clear, distinct blocks, often in two-column layouts where text and imagery (or another content block) sit side-by-side. Vertical spacing between sections is generous and consistent, creating a breathable yet structured feel. Navigation is minimalist, typically featuring discrete text links that integrate visually with the blocky design.

## Agent Prompt Guide

Quick Color Reference: 
text: #212529
background: #e4e4e4
border: #000000
accent: #f78da7
primary action: no distinct CTA color

Example Component Prompts:
1. Create a large display title: 'INTRA' in Whyte, 95px, #212529, lineHeight 1.0. Place it centered within a #e4e4e4 background block with 40px vertical padding.
2. Build a ghost button: Text 'BUY IN-STORE' in Whyte, 16px, #000000. Add a 0px border-radius, background-color transparent, and a 2px solid #000000 border. Apply 1px vertical and 6px horizontal padding.
3. Design a product card: Background is #f78da7 with 0px border-radius. Inner text 'Costa Rica' in Whyte, 20px, #ffffff. The card should have no padding directly on the card itself, but content inside should respect a 15px internal content padding.

## Similar Brands

- **B&R** — Monochromatic palette with a focus on black, white, and a single accent, and heavy reliance on bold, industrial-style typography for impact.
- **A.P.C.** — Utilitarian web design with stark contrasts, minimalist layouts, and the absence of decorative elements or softened edges.
- **Our Legacy** — Unadorned web experience, direct presentation of content in blocks, and a refined yet raw typographic presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-gray: #e4e4e4;
  --color-ink-black: #212529;
  --color-paper-white: #ffffff;
  --color-absolute-black: #000000;
  --color-vivid-pink: #f78da7;
  --color-vivid-amber: #fcb900;
  --color-vivid-clay: #dc3545;
  --color-vivid-green-cyan: #00d084;

  /* Typography — Font Families */
  --font-whyte: 'Whyte', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-display: 95px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-78: 78px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 100%;
  --radius-buttons: 0px;

  /* Surfaces */
  --surface-canvas-gray: #e4e4e4;
  --surface-ink-black-surface: #212529;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-gray: #e4e4e4;
  --color-ink-black: #212529;
  --color-paper-white: #ffffff;
  --color-absolute-black: #000000;
  --color-vivid-pink: #f78da7;
  --color-vivid-amber: #fcb900;
  --color-vivid-clay: #dc3545;
  --color-vivid-green-cyan: #00d084;

  /* Typography */
  --font-whyte: 'Whyte', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-display: 95px;
  --leading-display: 1;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-78: 78px;
  --spacing-100: 100px;
}
```
