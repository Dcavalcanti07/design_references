# Ambrook — Style Reference
> Rustic ledger on cream parchment

**Theme:** light

Ambrook uses an agricultural-vintage aesthetic, combining a warm, earthy color palette with a robust, serif-like custom typeface for headings and a more utilitarian sans-serif for body text. The design feels grounded and authentic, with a preference for natural textures, soft, rounded corners, and a 'paper-like' off-white background. Visual hierarchy is established through a strong contrast between deep, desaturated neutrals and a potent, moderate yellow accent for key calls to action, all framed within comfortable, well-defined spacing.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greige Canvas | `#fcfaf1` | `--color-greige-canvas` | Primary page background, card surfaces, form fills, light separators — sets a warm, natural base |
| Warm Paper | `#efe9e0` | `--color-warm-paper` | Secondary surface background, subtle separators, link backgrounds — a slightly muted variant of the canvas |
| Soil | `#211b15` | `--color-soil` | Primary body text, dark borders, strong emphasis text — anchors the visual design with a deep, earthy neutral |
| Moss | `#252a23` | `--color-moss` | Heading text, primary dark backgrounds for sections, dark icon fills — a slightly cooler, yet still deep, complement to Soil |
| Field Green | `#434f40` | `--color-field-green` | Muted text, ghost button text, icon fills, inactive navigation items — provides a softer contrast for secondary elements |
| Stone Path | `#96897b` | `--color-stone-path` | Light body text, navigation text, subtle borders — a mid-tone neutral for less prominent textual elements |
| Clay | `#50463c` | `--color-clay` | Subtle borders, secondary icon fills — a warm, mid-dark gray for understated details |
| Harvest Gold | `#e8b672` | `--color-harvest-gold` | Primary call-to-action buttons, interactive highlights — provides a warm, inviting accent for key user actions |
| Faded Harvest | `#f0c891` | `--color-faded-harvest` | Decorative highlights, accent text, occasional icon fills — a lighter, less saturated variant of Harvest Gold |
| Forest Fern | `#7a9779` | `--color-forest-fern` | Outline button borders, decorative strokes, link accents — a muted green that adds a natural accent |
| Weathered Stone | `#c7bcaf` | `--color-weathered-stone` | Divider lines, subtle card borders — a very light, desaturated neutral for delicate visual separation |

## Tokens — Typography

### Lateral — Primary text across the site: body copy, navigation, buttons, and most input fields. Its warmth complements the brand's aesthetic. Use 0.1000em for smaller captions and 0.0580em for interactive elements. · `--font-lateral`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 11px, 13px, 15px, 17px, 19px, 30px, 68px
- **Line height:** 1.11, 1.20, 1.33, 1.43, 1.50, 1.60, 1.71
- **Letter spacing:** -0.0110em, 0.0580em, 0.1000em, 0.1070em
- **Role:** Primary text across the site: body copy, navigation, buttons, and most input fields. Its warmth complements the brand's aesthetic. Use 0.1000em for smaller captions and 0.0580em for interactive elements.

### Lateral Narrow — Secondary headings and specific call-out text. Provides a slightly more condensed feel than standard Lateral, used at -0.0090em for 30px text. · `--font-lateral-narrow`
- **Substitute:** Roboto Condensed
- **Weights:** 400, 500
- **Sizes:** 19px, 30px, 34px
- **Line height:** 1.40, 1.50
- **Letter spacing:** -0.0100em, -0.0090em
- **Role:** Secondary headings and specific call-out text. Provides a slightly more condensed feel than standard Lateral, used at -0.0090em for 30px text.

### Lateral Display — Prominent display headings. Its wide letter-spacing at larger sizes gives a sense of gravitas and spaciousness, creating a distinct brand voice. · `--font-lateral-display`
- **Substitute:** Lora
- **Weights:** 400, 500, 700
- **Sizes:** 38px, 53px, 68px
- **Line height:** 1.00, 1.10, 1.14
- **Letter spacing:** -0.0110em
- **Role:** Prominent display headings. Its wide letter-spacing at larger sizes gives a sense of gravitas and spaciousness, creating a distinct brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.71 | 1px | `--text-caption` |
| body | 15px | 1.5 | — | `--text-body` |
| subheading | 19px | 1.4 | -0.1px | `--text-subheading` |
| heading-sm | 30px | 1.2 | -0.09px | `--text-heading-sm` |
| heading | 38px | 1.14 | -0.11px | `--text-heading` |
| heading-lg | 53px | 1.1 | -0.11px | `--text-heading-lg` |
| display | 68px | 1 | -0.11px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 68 | 68px | `--spacing-68` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 7.5px |
| inputs | 3.75px |
| buttons | 3.75px |
| largeCards | 11.25px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 45px
- **Card padding:** 15px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button

Background: Harvest Gold (#e8b672), text: Moss (#252a23), border-radius: 3.75px. Padding: 0px vertical, 15px horizontal. Represents a clear, inviting call to action.

### Ghost Button
**Role:** Outlined or text-only button

Background: transparent (rgba(0,0,0,0)), text: Field Green (#434f40), border: 0px. Text is often uppercase, conveying a secondary, less urgent action.

### Outlined Accent Button
**Role:** Outlined button with accent

Background: transparent (rgba(0,0,0,0)), text: Moss (#252a23), border: 1px solid Forest Fern (#7a9779), border-radius: 3.75px. Used for actions that need emphasis without being the primary CTA.

### Input Field
**Role:** Form input

Background: transparent (rgba(0,0,0,0)), text: Soil (#211b15), border-bottom: 1px solid Soil (#211b15), border-radius: 3.75px. Padding: 11.25px vertical, 11.25px left, 7.5px right. Emphasizes input through a strong bottom border.

### Standard Card
**Role:** Information container

Background: Greige Canvas (#fcfaf1), border-radius: 7.5px, no shadow. Used for containing features, testimonials, or grouped content, maintaining a light overall feel.

### Text Box Card
**Role:** Text container

Background: Greige Canvas (#fcfaf1), border-radius: 11.25px, no shadow. Padding: 67.5px vertical, 45px horizontal. Used for prominent text blocks, creating a generous visual space around content.

## Do's and Don'ts

### Do
- Prioritize Greige Canvas (#fcfaf1) for all background surfaces to maintain the warm, textural base of the design.
- Use Soil (#211b15) for primary body text and Moss (#252a23) for headings to establish a clear typographic hierarchy with deep, commanding shades.
- Apply Harvest Gold (#e8b672) exclusively for primary calls to action to ensure visual prominence and direct user focus.
- Utilize Lateral Display family for all major headings, applying its characteristic wide letter-spacing of -0.0110em.
- Maintain a default border-radius of 3.75px for interactive elements like buttons and inputs, and 7.5px for standard cards.
- Employ consistent 8px element gaps for inline components and 45px vertical section gaps to ensure comfortable density and visual rhythm.
- Use a 1px solid border in Weathered Stone (#c7bcaf) or Soil (#211b15) for subtle dividers between sections or elements.

### Don't
- Do not introduce highly saturated colors outside the defined Harvest Gold and Forest Fern unless for specific, isolated branding elements.
- Avoid hard-edged, sharp corners; all interactive and container elements should respect the 3.75px or 7.5px radius.
- Do not use generic system fonts; always specify Lateral, Lateral Narrow, or Lateral Display with their corresponding weights and letter spacing.
- Refrain from using strong drop shadows or complex elevation effects; the design relies on subtle borders and background color changes for depth.
- Do not use generic light gray (#cccccc, #eeeeee) for neutrals; always select from the earthy palette (Greige Canvas, Warm Paper, Field Green, etc.).
- Avoid tight line-heights for body text; ensure comfort and legibility by using line-heights > 1.5, especially with Lateral 400 at smaller sizes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Greige Canvas | `#fcfaf1` | Base page and largest card backgrounds |
| 1 | Warm Paper | `#efe9e0` | Secondary background sections, subtle borders, some link backgrounds effectively creating a slightly deeper layer than Greige Canvas |
| 2 | Moss | `#252a23` | Prominent section backgrounds, especially in hero areas, creating a strong contrast from the lighter canvas |

## Imagery

The site uses a mix of candid, slightly desaturated photography and simple, organic line-art illustrations. Photography focuses on real people in natural or work environments, often with a warm, slightly vintage filter, contributing to the 'authentic' and 'grounded' feel. Images are primarily contained within rounded frames or as background elements in sections. Illustrations are monochrome, in the Soil (#211b15) color, acting as descriptive icons or small decorative elements, reinforcing the theme of agriculture and craftsmanship.

## Layout

The page primarily employs a max-width contained layout of 1200px, centered on the screen. The hero section features a centered headline over a background that transitions from a light neutral to a deeper mossy green, often overlaid with textural imagery. Sections alternate between Greige Canvas and Warm Paper backgrounds, creating a clear vertical rhythm. Content is arranged in alternating text-left/image-right patterns, centered stacked content, and multi-column grids (e.g., a 3-column card grid for services). The overall density is comfortable, with ample whitespace provided by 45px section gaps. Navigation is a simple, fixed top bar.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #211b15
- background: #fcfaf1
- border: #211b15
- accent: #7a9779
- primary action: #e8b672 (filled action)

**3-5 Example Component Prompts:**
- Create a Primary Action Button: #e8b672 background, #211b15 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a navigation bar: Greige Canvas (#fcfaf1) background. Nav links at 15px Lateral weight 400, Field Green (#434f40). Ghost Button: transparent background, Field Green (#434f40) text, 3.75px radius.
- Create a feature card: Standard Card background Greige Canvas (#fcfaf1), 7.5px radius. Headline at 30px Lateral Narrow weight 500, Moss (#252a23), letter-spacing -0.009em. Body text at 15px Lateral weight 400, Soil (#211b15).
- Create a testimonial section: Moss (#252a23) background. Large quote text 53px Lateral Display, Faded Harvest (#f0c891), letter-spacing -0.11em. Attribution text 19px Lateral weight 500, Greige Canvas (#fcfaf1).

## Motion Philosophy

Ambrook uses motion sparingly and functionally, characterized by an 'expressive' personality. Transitions for common properties like `color`, `box-shadow`, `background-color`, and `opacity` are typically 0.15s with an `ease` timing function. This suggests swift, smooth feedback without being overly flashy, contributing to a feeling of efficiency and responsiveness. Longer durations (0.3s) suggest more deliberate UI state changes. The presence of cubic-bezier functions hints at custom, nuanced accelerations and decelerations for a polished feel.

## Similar Brands

- **Rippling** — Similar focus on strong primary headings, clear segmentation of content, and a slightly muted professional palette with a single accent color.
- **Bench Accounting** — Shares the brand identity of simplifying complex financial tasks, reflected in clean layouts, soft neutrals, and approachable typography.
- **Gusto** — Utilizes an earthy, friendly aesthetic, with ample whitespace and clear calls to action, though Gusto tends to use more illustrative elements.
- **Grain.com** — Features a similar 'natural' or 'craft' aesthetic with a focus on specific industries, using photography that feels authentic and related to their target audience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greige-canvas: #fcfaf1;
  --color-warm-paper: #efe9e0;
  --color-soil: #211b15;
  --color-moss: #252a23;
  --color-field-green: #434f40;
  --color-stone-path: #96897b;
  --color-clay: #50463c;
  --color-harvest-gold: #e8b672;
  --color-faded-harvest: #f0c891;
  --color-forest-fern: #7a9779;
  --color-weathered-stone: #c7bcaf;

  /* Typography — Font Families */
  --font-lateral: 'Lateral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lateral-narrow: 'Lateral Narrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lateral-display: 'Lateral Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.71;
  --tracking-caption: 1px;
  --text-body: 15px;
  --leading-body: 1.5;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.1px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.09px;
  --text-heading: 38px;
  --leading-heading: 1.14;
  --tracking-heading: -0.11px;
  --text-heading-lg: 53px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.11px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.11px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 45px;
  --card-padding: 15px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 3.75px;
  --radius-lg: 7.5px;
  --radius-xl: 11.25px;

  /* Named Radii */
  --radius-cards: 7.5px;
  --radius-inputs: 3.75px;
  --radius-buttons: 3.75px;
  --radius-largecards: 11.25px;

  /* Surfaces */
  --surface-greige-canvas: #fcfaf1;
  --surface-warm-paper: #efe9e0;
  --surface-moss: #252a23;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greige-canvas: #fcfaf1;
  --color-warm-paper: #efe9e0;
  --color-soil: #211b15;
  --color-moss: #252a23;
  --color-field-green: #434f40;
  --color-stone-path: #96897b;
  --color-clay: #50463c;
  --color-harvest-gold: #e8b672;
  --color-faded-harvest: #f0c891;
  --color-forest-fern: #7a9779;
  --color-weathered-stone: #c7bcaf;

  /* Typography */
  --font-lateral: 'Lateral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lateral-narrow: 'Lateral Narrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lateral-display: 'Lateral Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.71;
  --tracking-caption: 1px;
  --text-body: 15px;
  --leading-body: 1.5;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.1px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.09px;
  --text-heading: 38px;
  --leading-heading: 1.14;
  --tracking-heading: -0.11px;
  --text-heading-lg: 53px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.11px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.11px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 3.75px;
  --radius-lg: 7.5px;
  --radius-xl: 11.25px;
}
```
