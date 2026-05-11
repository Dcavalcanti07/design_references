# Hugo & Marie — Style Reference
> Gallery Grid on Canvas

**Theme:** light

Hugo & Marie operates with a refined, understated aesthetic characterized by stark monochrome typography and a deliberately sparse, almost gallery-like layout. Clean, unadorned surfaces provide a neutral canvas for striking visual content, while subtle hints of interactivity appear as ghost buttons and hairline borders. The system prioritizes clarity and a sense of curated space, allowing the visual work to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, headings on light backgrounds, element borders. Background for hero sections and image overlays |
| Graphite | `#0a0a0a` | `--color-graphite` | Decorative borders, secondary text where primary text is Ink Black. Used for subtle emphasis without full black contrast |
| Ash Gray | `#b3b3b3` | `--color-ash-gray` | Muted secondary text, ghost button borders, decorative icon fills. Suggests interaction without high contrast |
| Silver Mist | `#cccccc` | `--color-silver-mist` | Subtle background for badges, text on badges with higher contrast background. Low-prominence UI elements |
| Input Border Gray | `#767676` | `--color-input-border-gray` | Standard input field borders, providing a clear but not dominant delineation |

## Tokens — Typography

### soehne — Primary functional typeface for body text, navigation, links, and buttons. Its versatile weight range supports both compact UI elements and more descriptive content. · `--font-soehne`
- **Substitute:** system-ui
- **Weights:** 300, 400
- **Sizes:** 14px, 16px, 20px, 22px
- **Line height:** 1.00, 1.15, 1.20, 1.40, 1.44, 1.64, 1.80
- **Letter spacing:** 0.008em, 0.020em
- **Role:** Primary functional typeface for body text, navigation, links, and buttons. Its versatile weight range supports both compact UI elements and more descriptive content.

### saol-display — Signature display typeface for impactful headlines. Its extremely light weight and generous tracking create a sophisticated, almost ethereal presence, emphasizing elegance over shouting. · `--font-saol-display`
- **Substitute:** serif
- **Weights:** 100
- **Sizes:** 100px
- **Line height:** 0.95
- **Letter spacing:** -0.010em
- **Role:** Signature display typeface for impactful headlines. Its extremely light weight and generous tracking create a sophisticated, almost ethereal presence, emphasizing elegance over shouting.

### soehne-mono — Monospaced font used for small, functional elements like badges, providing technical precision where needed without disrupting the overall minimal aesthetic. · `--font-soehne-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.31
- **Letter spacing:** normal
- **Role:** Monospaced font used for small, functional elements like badges, providing technical precision where needed without disrupting the overall minimal aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 17 | — | `--text-caption` |
| body | 16px | 23 | 0.128px | `--text-body` |
| subheading | 20px | 23 | 0.16px | `--text-subheading` |
| heading | 22px | 22 | 0.44px | `--text-heading` |
| display | 100px | 95 | -10px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 9999px |

### Layout

- **Section gap:** 90px
- **Card padding:** 20px
- **Element gap:** 5px

## Components

### Ghost Text Button
**Role:** Interactive element, navigation

Minimalist button for navigation or secondary actions. Uses `Canvas White` for text and border against dark backgrounds, or `Ink Black` text with subtle border against light backgrounds. No background fill, providing a 'ghost' appearance. No padding.

### Pill Badge - Light Text
**Role:** Categorization, status indicator

Pill-shaped badge with `Silver Mist` background (rgba(0,0,0,0.2) against dark) and `Canvas White` text. Rounded to `9999px` radius, 6px top/8px bottom vertical padding, 24px horizontal padding.

### Pill Badge - Gray Border
**Role:** Categorization, status indicator

Pill-shaped badge with no background and a border color of `Ash Gray` (rgba(0,0,0,0.2) or #cccccc depending on background). Rounded to `9999px` radius, 6px top/8px bottom vertical padding, 24px horizontal padding.

### Text Input - Dark
**Role:** Data entry

Transparent background input field, `Canvas White` text. `Canvas White` border, 0px radius. Minimal 1px vertical, 2px horizontal padding. Hint text might be `Ash Gray`.

### Text Input - Light
**Role:** Data entry

Input field with `Canvas White` background and `Ink Black` text. `Input Border Gray` (or #767676) border, 0px radius. Minimal 1px vertical, 2px horizontal padding.

## Do's and Don'ts

### Do
- Use `Canvas White` (#ffffff) for all main page and card backgrounds to maintain a clean, expansive feel.
- Employ `saol-display` weight 100 at 100px with -10px letter-spacing for primary headlines to create a striking, elegant visual statement.
- Structure content with ample white space, using `sectionGap` of 90px between major content blocks.
- Maintain a monochromatic palette with only `Ink Black`, `Graphite`, `Ash Gray`, `Silver Mist`, and `Input Border Gray` for UI elements.
- Apply `9999px` border-radius to all badges for a consistent pill shape.
- Prioritize text-based interactions; button backgrounds are typically transparent, with text and borders defining interactivity.
- Ensure input fields use explicit borders like `Input Border Gray` and `Canvas White` to define their boundaries distinctly from the minimalistic buttons.

### Don't
- Avoid using bright or saturated colors for backgrounds, primary text, or interactive elements; reserve accent for content visuals.
- Do not introduce heavy shadows or gradients on UI components, favoring flat surfaces and subtle borders.
- Refrain from using bold or heavy weights for `soehne` when styling headings; its primary use should be for body and navigation.
- Do not add additional padding to ghost buttons; they should remain as minimalist text links with an implied interactive zone.
- Avoid decorative iconography that is colorful or heavily outlined; icons should be monochromatic, using `Ink Black` or `Ash Gray`.
- Do not deviate from the defined `9999px` radius for badges; all interactive tags or status indicators should adopt this pill shape.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, providing a pristine, open base for content. |
| 1 | Input Surface | `#cccccc` | Subtle background for badges or other low-prominence UI elements. |
| 2 | Hero Overlay | `#000000` | Background for full-bleed hero sections or image overlays, creating contrast. |

## Imagery

This site predominantly features striking, high-fidelity photography of human subjects or abstract, art-focused compositions. Imagery is often full-bleed or large-scale, acting as a dramatic backdrop or hero element. When not full-bleed, images are typically presented in a clean grid layout with sharp, unrounded edges. The treatment emphasizes the visual impact of the content, often using monochrome or desaturated palettes, with occasional vibrant but confined bursts of color (e.g., iridescent skin tones, abstract art pieces). Icons are outlined and monochromatic, acting as minimal UI elements rather than detailed graphics. The overall role of imagery is decorative atmosphere and product showcase, leaning heavily into a gallery-like presentation.

## Layout

The page exhibits a max-width contained model post-hero, with content sections having consistent vertical spacing. The hero features a full-bleed background image with a centered, large `saol-display` headline in `Canvas White` text. Subsequent sections primarily utilize a two-column layout, often with text on one side and an image or content block on the other, or a centered stacked arrangement. A consistent grid of four columns is used for displaying image thumbnails. The density is spacious, with significant padding and margin creating ample breathing room around elements. Navigation is a simple top bar, typically fixed or ghosted over the hero, with minimalist text links.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #0a0a0a
- accent: none observed
- primary action: no distinct CTA color

Example Component Prompts:
- Create a hero section: full-bleed image background. Centered headline 'WELCOMING JOHANNA JASKOWSKA' using `saol-display` weight 100, size 100px, #ffffff, letter-spacing -10px. Ghost navigation links on top bar using `soehne` weight 400, size 16px, #ffffff.
- Create a feature section: `Canvas White` background, 90px section gap. Two-column layout: left column contains subheading 'Creative Agency' using `soehne` weight 400, size 22px, #000000; body text 'Our Creative Agency helps bring brands to life...' using `soehne` weight 400, size 16px, #000000. Right column contains an image of an artwork.
- Create a functional badge: fill background with `Silver Mist` (#cccccc), text 'Latest' using `soehne-mono` weight 400, size 13px, #000000. Apply `9999px` border-radius and 6px top, 8px bottom, 24px horizontal padding.

## Similar Brands

- **AIGA** — Minimalist layout, strong focus on showcase visuals, and subtle-to-no decorative UI elements.
- **Made by Google** — Clean white backgrounds with focus on product/visuals and understated typography.
- **Chermayeff & Geismar & Haviv** — Architectural use of space, emphasis on stark monochrome with content driving visual interest.
- **Squarespace** — Often uses a hero image/video with minimal text overlay, followed by clean sections featuring photography and elegant typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #0a0a0a;
  --color-ash-gray: #b3b3b3;
  --color-silver-mist: #cccccc;
  --color-input-border-gray: #767676;

  /* Typography — Font Families */
  --font-soehne: 'soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saol-display: 'saol-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-soehne-mono: 'soehne-mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 17;
  --text-body: 16px;
  --leading-body: 23;
  --tracking-body: 0.128px;
  --text-subheading: 20px;
  --leading-subheading: 23;
  --tracking-subheading: 0.16px;
  --text-heading: 22px;
  --leading-heading: 22;
  --tracking-heading: 0.44px;
  --text-display: 100px;
  --leading-display: 95;
  --tracking-display: -10px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 90px;
  --card-padding: 20px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-badges: 9999px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-input-surface: #cccccc;
  --surface-hero-overlay: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #0a0a0a;
  --color-ash-gray: #b3b3b3;
  --color-silver-mist: #cccccc;
  --color-input-border-gray: #767676;

  /* Typography */
  --font-soehne: 'soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saol-display: 'saol-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-soehne-mono: 'soehne-mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 17;
  --text-body: 16px;
  --leading-body: 23;
  --tracking-body: 0.128px;
  --text-subheading: 20px;
  --leading-subheading: 23;
  --tracking-subheading: 0.16px;
  --text-heading: 22px;
  --leading-heading: 22;
  --tracking-heading: 0.44px;
  --text-display: 100px;
  --leading-display: 95;
  --tracking-display: -10px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-full: 9999px;
}
```
