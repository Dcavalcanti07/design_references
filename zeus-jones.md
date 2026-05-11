# Zeus Jones — Style Reference
> Ethereal canvas with typographic gravitas. A sun-drenched, off-white digital gallery where bold typography and artful backgrounds coalesce.

**Theme:** light

Zeus Jones projects a refined, artistic sensibility with a foundational off-white canvas and a rich, muted chromatic dark gray that anchors all textual and interactive elements. The design is characterized by large, confident typography that mixes serifs and sans-serifs, creating a dynamic yet sophisticated feel. Playful, pill-shaped buttons with deep curves add a touch of approachability against substantial spacing and a generally sparse layout. The hero section often features dramatic, ethereal gradient backgrounds that contrast with the otherwise understated UI.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#fcfaf3` | `--color-canvas-parchment` | Page backgrounds, navigation backgrounds, default text for dark surfaces — forms the primary backdrop of the site |
| Greyscale Architect | `#1a1c2c` | `--color-greyscale-architect` | Primary text, informational elements, button backgrounds, borders, link text, card text. This deep, muted gray serves as the dominant structural color |
| Card Dove | `#ebe9e4` | `--color-card-dove` | Card backgrounds, secondary surface variations, providing a subtle visual separation from the main canvas |
| Night Icon | `#000000` | `--color-night-icon` | Decorative SVG icons, occasional text elements where maximum contrast is desired, creating a sharp graphic presence |
| Hero Gradient | `linear-gradient(280deg, #b485ca, #e34c98, #60e0a5, #9c8ec4, #c9b13c)` | `--color-hero-gradient` | Dominant hero section background, providing a distinct, vibrant, and atmospheric entrance to the site — contrasts with the otherwise neutral palette |

## Tokens — Typography

### ZJSansDisplay — Primary sans-serif for headings, body text, navigation items, and interactive elements. It provides a modern, confident tone. · `--font-zjsansdisplay`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 16px, 18px, 24px, 40px, 48px, 60px, 90px
- **Line height:** 1.00, 1.07, 1.11, 1.20, 1.25, 1.30, 1.50, 1.60
- **Letter spacing:** -0.0200em at large sizes, 0.0500em at smaller sizes
- **Role:** Primary sans-serif for headings, body text, navigation items, and interactive elements. It provides a modern, confident tone.

### FeatureDeckLight — Hero headlines and large display text, characterized by its extremely light weight. It creates a sense of gravitas and spaciousness, conveying authority through restraint. · `--font-featuredecklight`
- **Substitute:** Lora Light
- **Weights:** 100
- **Sizes:** 60px, 90px
- **Line height:** 1.07, 1.11
- **Letter spacing:** -0.0200em
- **Role:** Hero headlines and large display text, characterized by its extremely light weight. It creates a sense of gravitas and spaciousness, conveying authority through restraint.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.6px | `--text-caption` |
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 18px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.3 | — | `--text-subheading` |
| heading | 40px | 1.25 | — | `--text-heading` |
| heading-lg | 48px | 1.2 | -0.96px | `--text-heading-lg` |
| display | 60px | 1.07 | -1.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

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
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 20px |
| cards | 20px |
| buttons | 1584px |
| headings | 1000px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 16px

## Components

### Ghost Navigation Link
**Role:** Navigation item and basic textual link.

Transparent background, 'Greyscale Architect' text (#1a1c2c), no border, no padding or radius. Used for minimalist navigation and inline links.

### Pill Button
**Role:** Primary call to action.

Filled with 'Greyscale Architect' (#1a1c2c) and 'Canvas Parchment' (#fcfaf3) text. Features an extremely high border-radius (1782px or 1584px) to create a pill shape. Padding is generous at 16px vertical, 32px horizontal or 12px vertical, 20px horizontal.

### Work Showcase Card
**Role:** Displaying work examples.

Background is 'Card Dove' (#ebe9e4) with a 20px border-radius and no box-shadow. Contains imagery and descriptive text.

### Underlined Input Field
**Role:** Standard text input.

Transparent background, 'Greyscale Architect' (#1a1c2c) text. Features a bottom border of 'Greyscale Architect' and no border-radius. Padding is 0px horizontal, 8px bottom.

### Header Navigation
**Role:** Top-level site navigation.

Inherits page background and features minimal ghost links and a menu icon. It's a full-width container that uses generous spacing and aligns elements to the edges.

## Do's and Don'ts

### Do
- Use 'Canvas Parchment' (#fcfaf3) as the default background for all page sections unless an accent background is specified.
- Employ 'Greyscale Architect' (#1a1c2c) for all primary body text, headlines, and interactive elements to maintain visual consistency.
- Apply ZJSansDisplay at weight 400 for most body and navigation text, with specific larger sizes for headings as defined in the type scale.
- Utilize FeatureDeckLight weight 100 for large, impactful display headings (60px, 90px) to establish a distinctive, light-weight typographic presence.
- Ensure all interactive buttons conform to the pill shape with a radius of 1584px or 1782px.
- Maintain comfortable '20px' border-radius for cards, images, and other contained UI elements.
- Incorporate a 40px section gap between major content blocks to ensure ample breathing room and a spacious layout.

### Don't
- Avoid using bright, saturated colors for primary UI elements; reserve high chroma for abstract backgrounds or illustrative accents.
- Do not use box-shadows for elevation; rely on background color changes or subtle borders for surface distinction.
- Do not break the pill-shaped button aesthetic with square or slightly rounded corners; always aim for maximum curvature.
- Avoid tight, condensed layouts; emphasize spaciousness and generous internal padding for components.
- Do not use generic system fonts; always adhere to ZJSansDisplay and FeatureDeckLight for brand consistency.
- Do not introduce heavy borders or outlines; stick to ghost interactions or solid, rich dark gray fills for interactive elements.
- Never center align large blocks of text; maintain a left-aligned, spacious text presentation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Parchment | `#fcfaf3` | Primary page background layer |
| 1 | Card Dove | `#ebe9e4` | Secondary background layer for cards and contained content |
| 2 | Greyscale Architect | `#1a1c2c` | Deepest surface layer, used for interactive elements like filled buttons or navigation panels that appear on top of other surfaces |

## Imagery

The site uses a mix of bespoke, abstract gradient backgrounds (often full-bleed in hero sections) and carefully curated product/project showcase imagery. Photography and product shots are contained within cards with 20px rounded corners, often monochromatic or with a muted color palette to blend with the overall design. Icons are minimalist, typically black (#000000) or 'Greyscale Architect' (#1a1c2c) and filled, reflecting a clean, direct visual style. Imagery functions primarily to showcase work and set an atmosphere, not as merely decorative elements. Density is medium, with images serving as visual anchors within content blocks.

## Layout

The page primarily uses a full-bleed structure, particularly for impactful hero sections like the gradient background. Content within sections is often given ample horizontal padding, creating a comfortable breathing room. Sections maintain a consistent vertical rhythm with a 40px `sectionGap`. Layouts within sections frequently alternate between text-dominant blocks and engaging, multi-column card grids for showcasing work. The header is a sticky, full-width element, providing persistent navigation. The overall feel is spacious and uncrowded, allowing key typographic elements and imagery to stand out.

## Agent Prompt Guide

### Quick Color Reference
text: #1a1c2c
background: #fcfaf3
border: #1a1c2c
accent: #9c8ec4 (Hero Gradient)
primary action: #1a1c2c (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #1a1c2c background, #fcfaf3 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a work showcase card: 'Card Dove' (#ebe9e4) background, 20px border-radius, no shadow, and internal content. Headline for the card example should be 'Rural American Mindset' using ZJSansDisplay weight 500, 24px, #1a1c2c. Body text below it using ZJSansDisplay weight 400, 18px size, #1a1c2c.
3. Implement a simple navigation link: no background, 'Greyscale Architect' (#1a1c2c) text color, ZJSansDisplay weight 400, 16px size. For example, text 'Work'.

## Similar Brands

- **Huge** — Known for large, confident typography on light backgrounds and a focus on digital experience design.
- **Fantasy** — Features impactful visual heroes with dramatic backgrounds and clean, sans-serif typography as a core element.
- **Work & Co** — Utilizes significant whitespace and a refined, minimal color palette to highlight content and typography, similar to the light canvas approach and deep-gray text.
- **Locomotive** — Employs bold, elegant typography and distinctive custom typefaces, often against a neutral or atmospheric background, for a sophisticated brand presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #fcfaf3;
  --color-greyscale-architect: #1a1c2c;
  --color-card-dove: #ebe9e4;
  --color-night-icon: #000000;
  --color-hero-gradient: #9c8ec4;
  --gradient-hero-gradient: linear-gradient(280deg, #b485ca, #e34c98, #60e0a5, #9c8ec4, #c9b13c);

  /* Typography — Font Families */
  --font-zjsansdisplay: 'ZJSansDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-featuredecklight: 'FeatureDeckLight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --text-heading: 40px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 60px;
  --leading-display: 1.07;
  --tracking-display: -1.2px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-full: 1000px;
  --radius-full-2: 1584px;
  --radius-full-3: 1782px;

  /* Named Radii */
  --radius-all: 20px;
  --radius-cards: 20px;
  --radius-buttons: 1584px;
  --radius-headings: 1000px;

  /* Surfaces */
  --surface-canvas-parchment: #fcfaf3;
  --surface-card-dove: #ebe9e4;
  --surface-greyscale-architect: #1a1c2c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #fcfaf3;
  --color-greyscale-architect: #1a1c2c;
  --color-card-dove: #ebe9e4;
  --color-night-icon: #000000;
  --color-hero-gradient: #9c8ec4;

  /* Typography */
  --font-zjsansdisplay: 'ZJSansDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-featuredecklight: 'FeatureDeckLight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --text-heading: 40px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 60px;
  --leading-display: 1.07;
  --tracking-display: -1.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-full: 1000px;
  --radius-full-2: 1584px;
  --radius-full-3: 1782px;
}
```
