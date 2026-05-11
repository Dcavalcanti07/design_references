# Flim — Style Reference
> Grid-paper studio, bold blocks.

**Theme:** light

Flim presents a raw, grid-centric design system aiming for an editorial, 'creative-tool' aesthetic. Its visual identity relies on stark black and white contrasts, a visible grid overlay, and a loose, unconstrained presentation of media elements. Typography is bold and tightly tracked for headings, with a monospaced touch for navigation, giving it a technical and precise yet playful feel. Components often use pronounced border radii and occasionally vivid accent colors for distinct, graphic emphasis.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#141414` | `--color-midnight-ink` | Primary text, core backgrounds (secondary), strong borders, filled button backgrounds. Creates high contrast and a dense visual weight |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, text against dark elements. Provides a clean, expansive foundation |
| Pure Black | `#000000` | `--color-pure-black` | Input borders, SVG fills – used for crisp, fine lines and accents |
| Paper White | `#f5f5f5` | `--color-paper-white` | Subtle surface elevation, card backgrounds. Differentiates content areas without strong contrast |
| Ash Gray | `#e9e9e9` | `--color-ash-gray` | Secondary surface. Provides slightly deeper contrast than Paper White |
| Stone Grout | `#d9d9d9` | `--color-stone-grout` | Decorative line strokes, grid lines. Subtle structural elements |
| Vivid Green | `#30a81d` | `--color-vivid-green` | Informational highlights, borders in badges, decorative colored backgrounds. A vibrant accent for functional or small-scale emphasis |
| Sunburst Orange | `#ff8400` | `--color-sunburst-orange` | Small decorative elements, card backgrounds, fills for accent. Adds warmth and attention |
| Forest Green | `#21935b` | `--color-forest-green` | Text and icon coloration in specific contexts. A deeper, more mature green accent |
| Lemon Zest | `#fecc33` | `--color-lemon-zest` | Highlighting text, decorative backgrounds. A bright, playful accent color |

## Tokens — Typography

### Swizzy — Headline and display text. Its condensed, bold nature with tight letter spacing makes it impactful and modern, creating a distinctive brand voice that feels both technical and artistic. · `--font-swizzy`
- **Substitute:** Montserrat, Raleway Bold
- **Weights:** 500
- **Sizes:** 21px, 27px, 47px, 125px
- **Line height:** 0.86, 1.00, 1.10
- **Letter spacing:** -0.02em
- **Role:** Headline and display text. Its condensed, bold nature with tight letter spacing makes it impactful and modern, creating a distinctive brand voice that feels both technical and artistic.

### Arial — Body text and supporting information. A system font choice that ensures broad compatibility and legibility for content. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 700
- **Sizes:** 16px, 32px
- **Line height:** 1.00, 1.13
- **Letter spacing:** normal
- **Role:** Body text and supporting information. A system font choice that ensures broad compatibility and legibility for content.

### PP Neue Montreal Mono — Navigation, input text, and small, technical labels. Its monospaced, spacy character adds a 'code-like' or 'tooling' feel, reinforcing the AI/creative tool aspect of the product. · `--font-pp-neue-montreal-mono`
- **Substitute:** Space Mono, Fira Code
- **Weights:** 400
- **Sizes:** 12px, 15px
- **Line height:** 1.00
- **Letter spacing:** 0.06em
- **Role:** Navigation, input text, and small, technical labels. Its monospaced, spacy character adds a 'code-like' or 'tooling' feel, reinforcing the AI/creative tool aspect of the product.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | 0.72px | `--text-caption` |
| body-lg | 16px | 1 | — | `--text-body-lg` |
| subheading | 21px | 0.86 | -0.42px | `--text-subheading` |
| heading | 27px | 1 | -0.54px | `--text-heading` |
| heading-lg | 32px | 1.13 | — | `--text-heading-lg` |
| display | 125px | 1.1 | -2.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| chips | 160px |
| icons | 16px |
| links | 4px |
| images | 16px |
| buttons | 8px |
| specialHeading | 25.04px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 24px

## Components

### Ghost Button
**Role:** Secondary action. Low visual hierarchy, relies on border for delineation.

Background: rgba(0,0,0,0), Text: #141414, Border: 1px solid #141414, Radius: 0px, Padding: 5px. Typography uses PP Neue Montreal Mono. Emphasizes spacious letter-spacing in labels.

### Filled Button (Accent)
**Role:** Primary action. High visual hierarchy, black background for strong call to action.

Background: #141414, Text: #ffffff, Radius: 8px, Padding: 8px 20px. Typography uses PP Neue Montreal Mono.

### Media Card
**Role:** Content container for visual assets.

Background: #f5f5f5, Radius: 16px, Padding: 0px. Used for images, often with fluid sizing.

### Circular Card (Accent)
**Role:** Decorative or small content container.

Background: #141414, Radius: 50%. Used for avatars or small icons.

### Callout Card (Orange)
**Role:** Promotional or highlighted content block.

Background: #ff8400, Radius: 160px (pill shape), Padding: 32px 40px.

### Text Input
**Role:** User input field with minimal styling.

Background: rgba(0,0,0,0), Text: #141414, Border: 1px solid #000000, Radius: 0px, Padding: 0px. Typography uses PP Neue Montreal Mono.

### Search Input Field
**Role:** Primary search interface.

Background: #f5f5f5, Radius: 16px 0px 0px 16px for the main field and 160px overall for the combined element (input + button). Text: #141414.

## Do's and Don'ts

### Do
- Prioritize high-contrast text against backgrounds: use #141414 on #ffffff or #f5f5f5. 
- Apply Swizzy font (or Montserrat) for all primary headings, using tight letter-spacing of -0.02em.
- Use PP Neue Montreal Mono (or Space Mono) for navigation, buttons, and input fields to maintain the 'technical' aesthetic, ensuring 0.06em letter-spacing.
- Utilize 16px border-radius for all image and card containers to provide a consistent soft-cornered visual.
- Employ the #141414 / #ffffff combination as the default for filled button states.
- Maintain the visible grid pattern using subtle lines as a foundational background element, suggesting a structured canvas.

### Don't
- Avoid using multiple chromatic colors in close proximity; color should primarily function as isolated accents or small functional highlights.
- Do not deviate from the specified negative letter-spacing for headlines or positive letter-spacing for monospaced text.
- Do not use generic system UI fonts where Swizzy or PP Neue Montreal Mono are intended; their distinctiveness is key to the brand.
- Avoid the use of heavy shadows or complex elevation; the design system prefers flat surfaces or subtle background color changes.
- Do not stretch the grid pattern elements unevenly; maintain a consistent background texture on relevant light sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and outermost containers. |
| 1 | Paper White | `#f5f5f5` | Slightly elevated content areas like cards and forms, provides subtle visual separation. |
| 2 | Ash Gray | `#e9e9e9` | Secondary background for card-like elements or subtle banding, deeper contrast against the Canvas White. |

## Imagery

This site features product screenshots prominently, typically contained within rounded-corner cards (16px radius) and presented with an unconstrained, scattered layout reminiscent of a digital mood board. Photography appears rich in detail, often showing film stills or dramatic shots. The imagery serves both decorative atmosphere and explicit content showcasing, with image-heavy sections contrasted by text-dominant areas. Icons are primarily outlined or stroke-based, appearing with the fine lines of Pure Black.

## Layout

The page primarily uses a full-bleed layout, often with a subtle #d9d9d9 grid overlay on light sections acting as a visual foundation. Content is often centered or uses alternating text-left/image-right configurations. The hero section is full-bleed, dominated by a large, bold brand name and a smaller, distinct headline. Images within the grid are freely positioned, giving a loose, collage-like feel. Navigation is a compact, minimal top bar with monospaced text and a ghost-style sign-up button. The overall density feels comfortable, with ample breathing room between major sections.

## Agent Prompt Guide

Quick Color Reference:
text: #141414
background: #ffffff
border: #141414
accent: #30a81d
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Ghost Button: background rgba(0,0,0,0), text #141414, border 1px solid #141414, radius 0px, padding 5px, font PP Neue Montreal Mono 400 15px, letter-spacing 0.06em.
2. Create a Media Card: background #f5f5f5, radius 16px, padding 0px. Ensure it contains an image with a similar 16px radius.
3. Create a primary headline: text 'Flim', font Swizzy 500 125px, color #141414, letter-spacing -0.02em.

## Similar Brands

- **Are.na** — Grid-based content organization, minimalist UI, and a focus on visual discovery with loose, collage-like layouts.
- **Read.cv** — Type-driven, high-contrast black and white aesthetic with monospaced accents and an editorial tone.
- **Linear** — Precision-focused UI with subtle grid lines, high-contrast text, and distinct control elements.
- **Framer** — Clean, modern design tool aesthetic with a focus on negative space, crisp typography, and subtle functional accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-canvas-white: #ffffff;
  --color-pure-black: #000000;
  --color-paper-white: #f5f5f5;
  --color-ash-gray: #e9e9e9;
  --color-stone-grout: #d9d9d9;
  --color-vivid-green: #30a81d;
  --color-sunburst-orange: #ff8400;
  --color-forest-green: #21935b;
  --color-lemon-zest: #fecc33;

  /* Typography — Font Families */
  --font-swizzy: 'Swizzy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono: 'PP Neue Montreal Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.72px;
  --text-body-lg: 16px;
  --leading-body-lg: 1;
  --text-subheading: 21px;
  --leading-subheading: 0.86;
  --tracking-subheading: -0.42px;
  --text-heading: 27px;
  --leading-heading: 1;
  --tracking-heading: -0.54px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.13;
  --text-display: 125px;
  --leading-display: 1.1;
  --tracking-display: -2.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 25.0353px;
  --radius-full: 64px;
  --radius-full-2: 160px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-chips: 160px;
  --radius-icons: 16px;
  --radius-links: 4px;
  --radius-images: 16px;
  --radius-buttons: 8px;
  --radius-specialheading: 25.04px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-paper-white: #f5f5f5;
  --surface-ash-gray: #e9e9e9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-canvas-white: #ffffff;
  --color-pure-black: #000000;
  --color-paper-white: #f5f5f5;
  --color-ash-gray: #e9e9e9;
  --color-stone-grout: #d9d9d9;
  --color-vivid-green: #30a81d;
  --color-sunburst-orange: #ff8400;
  --color-forest-green: #21935b;
  --color-lemon-zest: #fecc33;

  /* Typography */
  --font-swizzy: 'Swizzy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono: 'PP Neue Montreal Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.72px;
  --text-body-lg: 16px;
  --leading-body-lg: 1;
  --text-subheading: 21px;
  --leading-subheading: 0.86;
  --tracking-subheading: -0.42px;
  --text-heading: 27px;
  --leading-heading: 1;
  --tracking-heading: -0.54px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.13;
  --text-display: 125px;
  --leading-display: 1.1;
  --tracking-display: -2.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 25.0353px;
  --radius-full: 64px;
  --radius-full-2: 160px;
}
```
