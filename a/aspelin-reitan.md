# Aspelin Reitan — Style Reference
> Warmly lit gallery

**Theme:** dark

Aspelin Reitan embodies a deep, atmospheric aesthetic, reminiscent of a warmly lit gallery. The palette favors muted earth tones and deep grays, with vibrant yellow accents providing measured bursts of light. Typography is substantial and grounded, set against expansive photographic backdrops for a sense of gravitas and permanence. Visual hierarchy is established through a combination of typography, subtle borders, and the interplay of photography with minimal UI elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Caviar | `#000000` | `--color-midnight-caviar` | Primary text, deep surface contrast, main background for overlay elements. Creates depth and formality |
| Amber Sands | `#ffebd0` | `--color-amber-sands` | Outlined button borders, secondary text, decorative accents. Provides a warm, inviting contrast to darker backgrounds |
| Cream Canvas | `#fff8e9` | `--color-cream-canvas` | Surface backgrounds, elevated cards, link text, body copy in certain sections. Offers a soft, luminous base |
| Golden Harvest | `#fee197` | `--color-golden-harvest` | Interactive elements, navigation highlights, warning states. A vibrant accent that draws the eye and signifies action or information without being aggressive |
| Rich Umber | `#2f2116` | `--color-rich-umber` | Dominant background for page sections, footer background. Establishes a dark, grounding presence |
| Smoke & Mirrors | `#4f3622` | `--color-smoke-mirrors` | Subtle border details, muted text contrasting with lighter backgrounds |
| Desert Clay | `#987f61` | `--color-desert-clay` | Muted accents for secondary links and headings. Adds a touch of earthy warmth |
| Terra Cotta | `#8f534e` | `--color-terra-cotta` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### ModernEra — Primary typeface for all headings, body text, and interactive elements. Its substantial build lends a sense of establishment and clarity across various sizes. · `--font-modernera`
- **Substitute:** Arial
- **Weights:** 400, 500
- **Sizes:** 16px, 18px, 20px, 24px, 28px, 40px
- **Line height:** 1.17, 1.20, 1.22, 1.25, 1.29, 1.40
- **Letter spacing:** normal
- **Role:** Primary typeface for all headings, body text, and interactive elements. Its substantial build lends a sense of establishment and clarity across various sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.29 | — | `--text-heading-sm` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 28px | 1.22 | — | `--text-heading-lg` |
| display | 40px | 1.17 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 8px |
| buttons | 8px |

### Layout

- **Section gap:** 100px
- **Card padding:** 16px
- **Element gap:** 12px

## Components

### Outlined Primary Button
**Role:** Primary call to action.

Ghost button with a 1px border and text in Amber Sands (#ffebd0). Background is transparent. Padding is 45px top, 0px horizontal, 0px bottom.

### Navigation Link Button
**Role:** Main navigation and secondary actions in header.

Transparent background button with Amber Sands (#ffebd0) text and a 1px top border in Amber Sands. No border radius. Top padding 45px, 0px horizontal, 0px bottom.

### Rounded Outlined Button
**Role:** General purpose secondary action button.

Transparent background with Cream Canvas (#fff8e9) text and an 8px border radius. Padding is 9px top, 18px horizontal, 7px bottom. 1px border in Cream Canvas.

### Hero Headline
**Role:** Prominent display text on hero sections.

ModernEra font, size 40px, weight 400, color Cream Canvas (#fff8e9), line height 1.25. Set against a dark, often photographic background.

### Input Field
**Role:** Standard user input fields.

Transparent background, Golden Harvest (#fee197) text and a 1px bottom border in Golden Harvest. Padding is 16px top, 0px left, 16px bottom, 80px right.

## Do's and Don'ts

### Do
- Always pair Midnight Caviar (#000000) or Rich Umber (#2f2116) text with Cream Canvas (#fff8e9) or Amber Sands (#ffebd0) backgrounds for readability.
- Use Golden Harvest (#fee197) exclusively for interactive elements and navigation highlights to maintain its accent status.
- Apply 8px border radius to all buttons and interactive links for consistency.
- Maintain a clear visual hierarchy using ModernEra at different weights and sizes, ensuring 40px headlines and 16px body copy are distinct.
- Utilize outlined buttons with transparent backgrounds and chromatic borders over solid fills to preserve the open, atmospheric feel.
- Prioritize large, impactful photography as primary background elements, with minimal UI overlays.
- Ensure generous vertical spacing between sections (around 100px) to give content breathing room and a sense of gravity.

### Don't
- Avoid using multiple chromatic colors side-by-side; Golden Harvest (#fee197) should be the primary accent.
- Do not introduce heavy drop shadows or vibrant background fills; the system relies on subtle surface changes and atmospheric photography.
- Never use solid background buttons unless explicitly for a critical primary action that needs to stand out beyond the current system.
- Do not deviate from the ModernEra font family; all text elements must use this typeface.
- Avoid tight element spacing; maintain at least 12px between elements for visual comfort and spaciousness.
- Do not use hard-edged, unrounded elements for interactive components; a subtle 8px radius is key to the system's feel.

## Imagery

The visual language is dominated by high-quality, often architectural or interior photography, used as expansive full-bleed backgrounds or large featured images. The photography tends towards real-world scenes, providing context and a sense of place. There are no illustrations or abstract graphics. Icons (seen in 'Menu', 'Søk' buttons) are minimal, single-color outlines, often in Amber Sands or Cream Canvas, designed to recede into the design while remaining functional. Imagery plays a strong decorative and atmospheric role, anchoring sections with realism and depth rather than purely explanatory content.

## Layout

The page model is full-bleed, with content often overlaid directly on large background images or set within wide, contained sections. The hero section is characterized by a full-viewport photographic background with centered, large-scale typography. Section rhythm is marked by consistent, generous vertical spacing (approx. 100px) between blocks of content. Content arrangement frequently features alternating text and image sections, often in large, symmetrical blocks or grids for project showcases. Navigation is minimal, with a sticky top-right menu button and a similar 'Portefølje' button, both becoming transparent overlays upon interaction.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #2f2116
border: #ffebd0
accent: #fee197
primary action: #ffebd0 (outlined action border)

Example Component Prompts:
1. Create a hero section: full-bleed background image, headline 'Hvordan skaper vi steder' ModernEra 40px weight 400, Cream Canvas (#fff8e9), line height 1.25, centered on the page. Overlay a 'Portefølje' navigation link in top right: ModernEra 16px weight 400, Amber Sands (#ffebd0), no background, 1px top border Amber Sands, 45px top padding.
2. Create a project card: Cream Canvas (#fff8e9) background, large project photo covering 70% height, with 'Sommerro, Eiendommer' text ModernEra 16px weight 400, Midnight Caviar (#000000), line height 1.4, below the image. Card has 8px border radius.
3. Create a secondary button: 'Søk' text in ModernEra 16px weight 400, Cream Canvas (#fff8e9), transparent background, 1px border in Cream Canvas (#fff8e9) with 8px border radius, 9px vertical padding and 18px horizontal padding.

## Similar Brands

- **Brummer & Partners** — Similar use of large, impactful photography as backgrounds with minimal UI overlay and strong, contrasting typography.
- **Snøhetta** — Employs a dark, sophisticated palette with architectural photography and a focus on clean, spacious layouts.
- **Æra Strategic Innovation** — Relies on high-quality visuals, a reserved color palette, and clear typography to convey a sense of gravitas and professionalism.
- **Norwegian Architects Association (NAL)** — Shares the use of stunning architectural photography as a core design element, paired with a focus on substantial, readable typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-caviar: #000000;
  --color-amber-sands: #ffebd0;
  --color-cream-canvas: #fff8e9;
  --color-golden-harvest: #fee197;
  --color-rich-umber: #2f2116;
  --color-smoke-mirrors: #4f3622;
  --color-desert-clay: #987f61;
  --color-terra-cotta: #8f534e;

  /* Typography — Font Families */
  --font-modernera: 'ModernEra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.29;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.22;
  --text-display: 40px;
  --leading-display: 1.17;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 16px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;

  /* Named Radii */
  --radius-links: 8px;
  --radius-buttons: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-caviar: #000000;
  --color-amber-sands: #ffebd0;
  --color-cream-canvas: #fff8e9;
  --color-golden-harvest: #fee197;
  --color-rich-umber: #2f2116;
  --color-smoke-mirrors: #4f3622;
  --color-desert-clay: #987f61;
  --color-terra-cotta: #8f534e;

  /* Typography */
  --font-modernera: 'ModernEra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.29;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.22;
  --text-display: 40px;
  --leading-display: 1.17;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
}
```
