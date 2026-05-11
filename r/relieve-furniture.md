# Relieve Furniture — Style Reference
> Sustainable canvas, precise purpose

**Theme:** light

Relieve Furniture uses a calm, sustainable efficiency aesthetic: light, airy canvases, subtle elevation, and a focused palette of muted greens and purples. Typography is precise and airy, conveying information clearly without visual clutter. Components often feature soft rounded corners, suggesting approachability within an otherwise crisp, structured layout. The overall impression is one of organized, eco-conscious professionalism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Fog | `#f6f7f7` | `--color-canvas-fog` | Secondary surface background, subtle button backgrounds, light card backgrounds |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Primary background for cards, modals, and default page sections |
| Ash Cloud | `#e7e5e4` | `--color-ash-cloud` | Hairline borders, subtle dividers, inactive UI elements |
| Midnight Forest | `#0b392f` | `--color-midnight-forest` | Primary body text, headers, strong borders, dark iconography, navigation links |
| Verdant Sprout | `#0cea9e` | `--color-verdant-sprout` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Amethyst Glow | `#6f52d3` | `--color-amethyst-glow` | Accent for key headings, primary navigation hover states, and highlighted text |
| Deep Plum | `#6043ba` | `--color-deep-plum` | Background for secondary action buttons, often ghosted or outlined |
| Graphite Text | `#374151` | `--color-graphite-text` | Secondary text, muted links, and low-emphasis information |
| Stone Grey | `#778a83` | `--color-stone-grey` | Muted text, placeholder text, disabled element borders |
| Coal Black | `#000000` | `--color-coal-black` | Strongest text, card backgrounds for high contrast sections, critical iconography |
| Slate Blue | `#7f6de1` | `--color-slate-blue` | Background for feature cards, often used in contrast with dark text |
| Dark Forest | `#0b704e` | `--color-dark-forest` | Subtle green text accents, secondary green links |
| Carbon Gray | `#333c39` | `--color-carbon-gray` | Dark button backgrounds, contrasting small elements |

## Tokens — Typography

### Planar — The primary typeface for all text content including headings, body, buttons, and navigation. Its slightly condensed nature and varying weights, especially the lighter 200 and 300 for larger headings, contribute to the site's airy and precise feel. · `--font-planar`
- **Substitute:** system-ui, sans-serif
- **Weights:** 200, 300, 400
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 16px, 17px, 20px, 22px, 24px, 26px, 32px, 36px
- **Line height:** 1.00, 1.15, 1.20, 1.40, 1.50, 1.60, 1.70, 2.00
- **Letter spacing:** 0.18, -0.9
- **Role:** The primary typeface for all text content including headings, body, buttons, and navigation. Its slightly condensed nature and varying weights, especially the lighter 200 and 300 for larger headings, contribute to the site's airy and precise feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.7 | — | `--text-caption` |
| body | 14px | 1.6 | — | `--text-body` |
| heading-sm | 22px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 32px | 1.15 | — | `--text-heading-lg` |
| display | 36px | 1 | -0.9px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 61 | 61px | `--spacing-61` |
| 100 | 100px | `--spacing-100` |
| 134 | 134px | `--spacing-134` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| chips | 9999px |
| images | 8px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.25) 0px 0px 15px 0px` | `--shadow-md` |
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Ghost Primary Button
**Role:** Default action button variant, outlines call-to-actions.

Transparent background, 'Midnight Forest' #0b392f text and 1px border, 0px border-radius, no padding (text-only link style).

### Subtle Recessed Button
**Role:** Secondary action button for internal navigation or less prominent actions.

'Canvas Fog' #f6f7f7 background, 'Midnight Forest' #0b392f text, 1px 'Ash Cloud' #e7e5e4 border, 8px border-radius, 10px vertical and 20px horizontal padding.

### Dark Filled Button
**Role:** Prominent action button for high-attention calls to action.

'Carbon Gray' #333c39 background, 'Snowdrift' #ffffff text, 8px border-radius, 10px padding all around. Used for primary actions like 'Book a free call'.

### Flat Content Card
**Role:** Information display card, primarily for textual content or small images without elevation.

'Canvas Fog' #f6f7f7 background, 8px border-radius, 20px padding (top, right, left) and 5px bottom padding, no shadow.

### Elevated Tooltip Card
**Role:** Interactive pop-up or dialog card for focused information.

'Snowdrift' #ffffff background, 12px border-radius, 15px padding all around. Shadow: rgba(0, 0, 0, 0.25) 0px 0px 15px 0px.

### Text-Only Card
**Role:** Flexible card for information display, often used without distinct background or borders.

Transparent background, 0px border-radius, no specific padding, no shadow.

### Image Feature Card
**Role:** Card with background image, typically featuring a large image or visual element.

'Coal Black' #000000 background (for contrast with white text overlay), 8px border-radius, 660px top padding (for image), no shadow. Content usually overlays the image.

### Highlight Tag
**Role:** Small informational tag, often for 'New' features or status updates.

'Verdant Sprout' #0cea9 background, black text, 9999px border-radius (pill shape), fixed 1px top/bottom and 2px left/right padding.

## Do's and Don'ts

### Do
- Use 'Midnight Forest' #0b392f for primary text, links, and strong borders to maintain brand consistency.
- Apply 'Canvas Fog' #f6f7f7 as the background for secondary content blocks and subtle button variants.
- Reserve 'Verdant Sprout' #0cea9 and 'Amethyst Glow' #6f52d3 for functional highlights, accents, and call-to-action indicators, avoiding decorative overuse.
- Utilize Planar font with a weight of 400 for body text and 300 for prominent headings, maintaining an airy and readable aesthetic.
- Apply 8px border-radius consistently to all buttons, cards, and images, creating a soft, approachable feel.
- Ensure generous use of 10px element gaps and 20px card padding for a compact, yet not crowded, information density.
- Use rgba(0, 0, 0, 0.25) 0px 0px 15px 0px for all elevated components to provide subtle depth without heavy visual weight.

### Don't
- Do not introduce strong, saturated colors beyond 'Verdant Sprout' #0cea9 or 'Amethyst Glow' #6f52d3 for UI elements.
- Avoid heavy shadows or gradients on primary UI elements; surfaces should appear mostly flat or with subtle elevation.
- Do not use highly decorative or script fonts; stick to the Planar family to maintain the system's clean, precise tone.
- Do not deviate from the established 8px and 12px border radii for components; sharp corners are not part of this design language.
- Do not create dense, text-heavy blocks without adequate line-height (1.6 for body text) or clear visual separation.
- Avoid using multiple font sizes for adjacent text elements; stick to the defined type scale to maintain visual hierarchy.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Snowdrift | `#ffffff` | Primary page and card backgrounds. |
| 2 | Canvas Fog | `#f6f7f7` | Secondary background for sections and subtle component fills. |
| 3 | Coal Black | `#000000` | High-contrast background for feature cards with overlaid white text. |
| 4 | Slate Blue | `#7f6de1` | Background for specific feature cards, offering a touch of color contrast. |

## Elevation

- **Elevated Tooltip Card:** `rgba(0, 0, 0, 0.25) 0px 0px 15px 0px`
- **Card with subtle shadow:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

## Imagery

Imagery on Relieve Furniture typically features tightly cropped, professional product photography (office furniture, tech devices) or diverse team member photographs. Product shots often appear against neutral or dark backgrounds, highlighting the object itself. Photos are high-key and well-lit. Illustrations are minimal and functional, often appearing as subtle decorative elements or icons in a solid, filled style. Icons are clean, outlined, and monochromatic, primarily in 'Midnight Forest' #0b392f or 'Verdant Sprout' #0cea9e. There is a strong emphasis on visuals that communicate modern utility and sustainability, with imagery acting as explanatory content or product showcases rather than decorative atmosphere.

## Layout

The site employs a max-width contained layout, typically centered, with notable exceptions such as full-bleed header and hero sections. The hero prominently features a centered headline over a white background, with calls to action below. Section rhythm is generally consistent with vertical spacing, often alternating between white and very light gray backgrounds, creating distinct content blocks. Content is arranged in alternating text-left/image-right or image-left/text-right patterns, and in grids for cards, particularly 2-column layouts. The overall density is compact but with sufficient breathing room provided by consistent margins and padding, contributing to a clean, organized feel. A sticky top navigation bar provides consistent access to primary sections.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #0b392f
- background: #ffffff
- border: #e7e5e4
- accent: #0cea9e
- primary action: #0cea9e (filled action)

**3-5 Example Component Prompts:**
- Create a Hero Headline: 'The future of sustainable offices is circular' using Planar font, size 36px, weight 300, color #0b392f, letter-spacing -0.9px, centered on a #ffffff background.
- Create a Subtle Recessed Button: 'I want to browse circular furniture' using Planar font, size 14px, weight 400, color #0b392f, background #f6f7f7, border 1px solid #e7e5e4, 8px border-radius, 10px vertical and 20px horizontal padding.
- Create an Elevated Tooltip Card: 'Need help finding the right furniture?' using Planar font, size 14px, weight 400, color #0b392f. Background #ffffff, 12px border-radius, 15px padding all around, with a shadow of rgba(0, 0, 0, 0.25) 0px 0px 15px 0px.
- Create a Highlight Tag: 'NEW' using Planar font, size 10px, weight 400, color #000000, background #0cea9e, 9999px border-radius, 1px vertical and 2px horizontal padding.
- Create a Dark Filled Button: 'Book a free call with a team member today' using Planar font, size 14px, weight 400, color #ffffff, background #333c39, 8px border-radius, 10px padding all around.

## Similar Brands

- **OpenSpace** — Monochromatic light-theme with a single, vivid brand accent color and clean typography.
- **Fieldguide** — Focus on subtle surface variation for hierarchy, combined with minimal shadow usage and a similar compact feel.
- **Balsamiq** — Emphasis on functional, direct UI elements, unadorned typography, and a subdued color palette for productivity.
- **Linear** — Precise, slightly condensed typography, sparse use of color for functional indicators, and compact component design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-fog: #f6f7f7;
  --color-snowdrift: #ffffff;
  --color-ash-cloud: #e7e5e4;
  --color-midnight-forest: #0b392f;
  --color-verdant-sprout: #0cea9e;
  --color-amethyst-glow: #6f52d3;
  --color-deep-plum: #6043ba;
  --color-graphite-text: #374151;
  --color-stone-grey: #778a83;
  --color-coal-black: #000000;
  --color-slate-blue: #7f6de1;
  --color-dark-forest: #0b704e;
  --color-carbon-gray: #333c39;

  /* Typography — Font Families */
  --font-planar: 'Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 36px;
  --leading-display: 1;
  --tracking-display: -0.9px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-61: 61px;
  --spacing-100: 100px;
  --spacing-134: 134px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-chips: 9999px;
  --radius-images: 8px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 0px 15px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;

  /* Surfaces */
  --surface-snowdrift: #ffffff;
  --surface-canvas-fog: #f6f7f7;
  --surface-coal-black: #000000;
  --surface-slate-blue: #7f6de1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-fog: #f6f7f7;
  --color-snowdrift: #ffffff;
  --color-ash-cloud: #e7e5e4;
  --color-midnight-forest: #0b392f;
  --color-verdant-sprout: #0cea9e;
  --color-amethyst-glow: #6f52d3;
  --color-deep-plum: #6043ba;
  --color-graphite-text: #374151;
  --color-stone-grey: #778a83;
  --color-coal-black: #000000;
  --color-slate-blue: #7f6de1;
  --color-dark-forest: #0b704e;
  --color-carbon-gray: #333c39;

  /* Typography */
  --font-planar: 'Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 36px;
  --leading-display: 1;
  --tracking-display: -0.9px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-61: 61px;
  --spacing-100: 100px;
  --spacing-134: 134px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 0px 15px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
}
```
