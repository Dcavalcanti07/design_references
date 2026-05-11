# Henry — Style Reference
> Distressed newsprint, black-and-white grid

**Theme:** light

Henry.codes creates a dark, brutalist newsprint aesthetic, evoking a digital zine or an old-school BBS. The design uses stark monochrome contrast, large distressed display typography, and intentional visual chaos within a structured grid. Text blocks are dense, and the overall impression is one of raw, unfiltered information, avoiding typical 'clean' SaaS conventions. The system feels hand-coded, with a deliberate lack of smooth gradients, soft shadows, or rounded forms, opting for sharp edges and explicit separation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#2a2722` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas White | `#fafafa` | `--color-canvas-white` | Page background, light surface backgrounds, secondary text, prominent section dividers |
| Graphite Text | `#3e3b36` | `--color-graphite-text` | Secondary text, subheadings, and muted contextual information |
| Ash Gray | `#9f9f9f` | `--color-ash-gray` | Muted text, subtle borders, placeholder content |
| Light Border | `#eeeeee` | `--color-light-border` | Subtle borders for cards and contained sections, creating a very light visual separation |
| Midtone Text | `#666666` | `--color-midtone-text` | Helper text, captions, and fine print |
| Muted Silver | `#b3b3b3` | `--color-muted-silver` | Inactive navigation items, less emphasized text elements |
| Faded Gray | `#a9a9a9` | `--color-faded-gray` | Very subtle narrative text, highly de-emphasized elements |
| Rainbow Band | `linear-gradient(90deg, #c679c4, #fa3d1d, #ffb005)` | `--color-rainbow-band` | Decorative header accent, signifying a non-conformist digital identity |

## Tokens — Typography

### Neue Montreal — Primary text, navigation links, body content, and smaller headings. Its contemporary sans-serif form provides clear readability amidst the otherwise stylized design. · `--font-neue-montreal`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 12px, 16px, 20px, 24px, 32px
- **Line height:** 1.00, 1.10, 1.20, 1.50
- **Letter spacing:** -0.0100em
- **Role:** Primary text, navigation links, body content, and smaller headings. Its contemporary sans-serif form provides clear readability amidst the otherwise stylized design.

### Louize Display — Large, impactful headlines with a distressed, condensed serif character, used to create a strong, almost confrontational visual presence. · `--font-louize-display`
- **Substitute:** Anton
- **Weights:** 400
- **Sizes:** 32px, 35px, 77px, 116px, 126px, 132px
- **Line height:** 0.80, 0.90, 1.10, 1.20
- **Letter spacing:** normal
- **Role:** Large, impactful headlines with a distressed, condensed serif character, used to create a strong, almost confrontational visual presence.

### Louize — Complementary serif for body text and emphasized statements within more traditional paragraphs, bringing a classic but slightly rugged touch. · `--font-louize`
- **Substitute:** Merriweather
- **Weights:** 400
- **Sizes:** 16px, 20px, 24px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.0100em
- **Role:** Complementary serif for body text and emphasized statements within more traditional paragraphs, bringing a classic but slightly rugged touch.

### Manuka — Overlays and background decorative text elements, used at extremely large scales for atmospheric effect, often partially obscured. · `--font-manuka`
- **Substitute:** Oswald
- **Weights:** 400
- **Sizes:** 226px, 371px
- **Line height:** 0.75, 0.80
- **Role:** Overlays and background decorative text elements, used at extremely large scales for atmospheric effect, often partially obscured.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | — | `--text-caption` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 20px | 1.2 | -0.2px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.24px | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.32px | `--text-heading` |
| heading-lg | 77px | 0.9 | — | `--text-heading-lg` |
| display | 132px | 0.8 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| other | 12px |

### Layout

- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Text Content Card, Default
**Role:** Container for articles or body text.

Transparent background, 0px radius, no shadow. Padding 16px all sides. Emphasizes content over containment, blending into the background.

### Text Content Card, Rounded
**Role:** Container for 'Brief Letter' and similar self-contained content.

Transparent background, 12px border radius. Padding 32px top/bottom, 24px left/right. Provides a slightly softer, contained presentation for specific text blocks.

### Navigation Link, Primary
**Role:** Main navigation items in the sidebar or header.

Text in Midnight Ink (#2a2722), Neue Montreal, 16px weight 400. Letter spacing -0.01em. On hover, text color should change to Graphite Text (#3e3b36) and a 1px solid Midnight Ink (#2a2722) border appears below.

### Section Divider Line
**Role:** Visual separation between major content blocks.

A 2px solid line in Midnight Ink (#2a2722) or Canvas White (#fafafa), depending on background contrast, ensuring clear breaks.

### Ghost Button / Outlined Link
**Role:** Interactive elements with a minimal footprint, such as 'read more' or external links.

Text in Midnight Ink (#2a2722), Neue Montreal, 16px weight 400, with a 1px solid Midnight Ink (#2a2722) border. Transparent background. No padding by default, border closely hugs text.

### Editorial Text Block
**Role:** Stylized introductory text or personal notes.

Text in Louize, 20px weight 400, line height 1.2. Centered alignment. Contained within a transparent card with 12px radius, with 2px solid Midnight Ink (#2a2722) border and 32px top/bottom, 24px left/right padding. Text color is Midnight Ink (#2a2722).

## Do's and Don'ts

### Do
- Prioritize high contrast using Midnight Ink (#2a2722) and Canvas White (#fafafa) for all backgrounds and main text.
- Use Neue Montreal for all functional text and body copy to maintain legibility and a consistent modern feel.
- Apply Louize Display at large sizes (77px-132px) for primary headlines, embracing its distressed, imposing character.
- Maintain a clear separation between content blocks using 2px solid lines of either Midnight Ink (#2a2722) or Canvas White (#fafafa).
- Employ a 12px border radius only for specific content cards or overlays, keeping most UI elements sharp-edged.
- Ensure all interactive elements have a clear 1px or 2px Midnight Ink (#2a2722) border for definition, without relying on fill colors.
- Utilize 16px as the primary base for padding inside interactive containers and for general element spacing.

### Don't
- Do not use soft shadows or elevation effects; the design relies on stark lines and dark/light contrast for visual hierarchy.
- Avoid decorative gradients or subtle background textures, beyond the specific 'Rainbow Band' accent.
- Do not introduce highly saturated colors for functional UI elements; color is reserved for decorative accents or very specific indicators.
- Avoid soft, organic shapes or large, friendly radii; maintain sharp corners for most UI elements.
- Do not use multiple font families for body text or navigation; stick to Neue Montreal for consistency in these areas.
- Avoid thin, lightweight dividers; use prominent 2px solid lines to emphasize separation.
- Do not center-align long blocks of body text; reserve centered alignment for short, editorial statements.

## Imagery

This site uses stark, high-contrast, pixelated or halftone-style imagery, primarily in black and white. Images are often illustrative or abstract, occasionally featuring distressed textures or demonic/macabre motifs. They serve a decorative, atmospheric role rather than explanatory or product-showcasing. Visuals can be contained within defined areas, but also used as large, partially obscured background elements (like the 'Manuka' font). Icons, if present, are minimal, outlined, and monochromatic, matching the overall stark aesthetic. The density is image-light relative to text but impact-heavy when visuals do appear.

## Layout

The page primarily uses a full-bleed layout, allowing wide elements to stretch across the viewport, but often contains content within implied horizontal sections. The hero section is full-bleed, featuring large typographic elements. Content alternates between centered stacks and more complex, asymmetrical compositions, sometimes with text overlaying decorative background type. There's a strong vertical rhythm established through large section gaps and explicit horizontal dividers. Navigation is handled through fixed left-hand sidebars and top announcement bars, sometimes using a 'go home' link rather than a traditional logo. The layout feels like an untamed, yet structured, digital canvas, reminiscent of early web design with modern typographical flourishes.

## Agent Prompt Guide

Quick Color Reference:
text: #2a2722
background: #fafafa
border: #2a2722
accent: #c679c4 (gradient: linear-gradient(90deg, #c679c4, #fa3d1d, #ffb005))
primary action: no distinct CTA color

Example Component Prompts:
Create a primary navigation link titled 'Garden': Use Neue Montreal, 16px weight 400, letter spacing -0.16px, color Midnight Ink (#2a2722). Add a 2px solid Midnight Ink (#2a2722) border on hover. 
Create an 'Editorial Note' card displaying a short passage: Use a transparent background card with 12px border radius. Add 32px vertical and 24px horizontal padding. Apply a 2px solid Midnight Ink (#2a2722) border. The text should use Louize, 20px weight 400, line height 1.2, in Midnight Ink (#2a2722) and be center-aligned.
Create a large section headline for 'Selected Works': Use Louize Display, 77px weight 400, normal letter spacing, color Midnight Ink (#2a2722). Ensure it is full-bleed or extends widely across the canvas.

## Similar Brands

- **Are.na** — Monochromatic interface, grid-based content organization, and a focus on raw information display.
- **Brutalist Websites** — Deliberate use of stark typography, raw HTML-like elements, and aversion to conventional 'pleasant' UI design.
- **The Practical Dev (DEV Community)** — High-contrast, text-heavy approach with subtle borders and clear lines for content separation, though less extreme in its aesthetic.
- **Linus Tech Tips (Old Website)** — Early web aesthetic with high contrast, dense information, and a sense of DIY design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #2a2722;
  --color-canvas-white: #fafafa;
  --color-graphite-text: #3e3b36;
  --color-ash-gray: #9f9f9f;
  --color-light-border: #eeeeee;
  --color-midtone-text: #666666;
  --color-muted-silver: #b3b3b3;
  --color-faded-gray: #a9a9a9;
  --color-rainbow-band: #c679c4;
  --gradient-rainbow-band: linear-gradient(90deg, #c679c4, #fa3d1d, #ffb005);

  /* Typography — Font Families */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-louize-display: 'Louize Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-louize: 'Louize', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manuka: 'Manuka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.32px;
  --text-heading-lg: 77px;
  --leading-heading-lg: 0.9;
  --text-display: 132px;
  --leading-display: 0.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-other: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #2a2722;
  --color-canvas-white: #fafafa;
  --color-graphite-text: #3e3b36;
  --color-ash-gray: #9f9f9f;
  --color-light-border: #eeeeee;
  --color-midtone-text: #666666;
  --color-muted-silver: #b3b3b3;
  --color-faded-gray: #a9a9a9;
  --color-rainbow-band: #c679c4;

  /* Typography */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-louize-display: 'Louize Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-louize: 'Louize', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manuka: 'Manuka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.32px;
  --text-heading-lg: 77px;
  --leading-heading-lg: 0.9;
  --text-display: 132px;
  --leading-display: 0.8;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-xl: 12px;
}
```
