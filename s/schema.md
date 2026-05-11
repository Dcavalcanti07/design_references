# Schema — Style Reference
> Abstract art playground

**Theme:** light

Schema by Figma employs a bold, graphic language, reminiscent of abstract art on an interactive canvas. Its foundation is a stark black and white palette, punctuated by large, flat blocks of vivid and muted chromatic colors that act as dividers and background accents. Typography is primarily functional, featuring custom sans-serifs that maintain clarity even at large display sizes, often against contrasting backgrounds. The layout is structured yet playfully asymmetric, utilizing full-width sections that transition between solid colors and complex, overlapping geometric patterns, often making strong use of negative space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, light canvas sections, text on dark backgrounds |
| Pale Mist | `#e2e2e2` | `--color-pale-mist` | Subtle borders, secondary icons, light background elements |
| Charcoal Text | `#0f0f0f` | `--color-charcoal-text` | Headings, body text where slightly softer than pure black |
| Jade Accent | `#24cb71` | `--color-jade-accent` | Section backgrounds, decorative accents, illustration elements |
| Aqua Wash | `#c7f8fb` | `--color-aqua-wash` | Section backgrounds, subtle calls to attention, illustration elements |

## Tokens — Typography

### Figma VF-normal-700-75 — Figma VF-normal-700-75 — detected in extracted data but not described by AI · `--font-figma-vf-normal-700-75`
- **Weights:** 400
- **Sizes:** 24px
- **Line height:** 1.2
- **Role:** Figma VF-normal-700-75 — detected in extracted data but not described by AI

### Figma Sans Text — Primary UI text for buttons, navigation, body copy, and some headings. Its varied weights support clear hierarchy without sacrificing readability. · `--font-figma-sans-text`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 13px, 16px, 18px, 24px, 72px
- **Line height:** 1.00, 1.20, 1.22, 1.40
- **Letter spacing:** -0.02em at 72px, 0.03em at 13px
- **Role:** Primary UI text for buttons, navigation, body copy, and some headings. Its varied weights support clear hierarchy without sacrificing readability.

### Figma Sans Display — Used for prominent headlines and display text, its compressed line heights enhance visual impact and create a tight, modern aesthetic. · `--font-figma-sans-display`
- **Substitute:** Inter Display
- **Weights:** 400, 700
- **Sizes:** 16px, 24px, 32px, 56px, 72px, 86px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.30, 1.40
- **Letter spacing:** -0.02em at larger sizes (e.g., 86px), reverting to 0.03em at smaller.
- **Role:** Used for prominent headlines and display text, its compressed line heights enhance visual impact and create a tight, modern aesthetic.

### Source Sans Pro — Auxiliary body text, likely for longer content blocks or specific informational areas, offering high legibility. · `--font-source-sans-pro`
- **Substitute:** Roboto
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Auxiliary body text, likely for longer content blocks or specific informational areas, offering high legibility.

### Figma Mono — Monospaced text for technical details, code snippets, or specific labels where character alignment is key. · `--font-figma-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.30, 1.40
- **Letter spacing:** 0.03em
- **Role:** Monospaced text for technical details, code snippets, or specific labels where character alignment is key.

### Figma VF-normal-400-100 — Figma VF-normal-400-100 — detected in extracted data but not described by AI · `--font-figma-vf-normal-400-100`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Letter spacing:** 0.03
- **Role:** Figma VF-normal-400-100 — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.22 | — | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading | 32px | 1.1 | — | `--text-heading` |
| heading-lg | 56px | 1 | -1.12px | `--text-heading-lg` |
| display | 72px | 1 | -1.44px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 20px |
| buttons | 20px |

### Layout

- **Section gap:** 60px
- **Card padding:** 16px
- **Element gap:** 24px

## Components

### Ghost Button
**Role:** Primary interactive element for event registration or key actions.

Text-based, with an implied boundary. No explicit background or border, but appears within a container with a 1px solid #000000 line as a separator.

### Navigation Link
**Role:** Top-level navigation items.

Uses Figma Sans Text, weight 400, at 16px, color #000000. Underlined on hover or active states. Padding of 8px vertically and 16px horizontally.

### Section Divider Accent
**Role:** Visual separator for content blocks, creating graphic interest.

Large blocks of solid color, like #24cb71 or #c7f8fb, used as full-width backgrounds for sections, providing visual rhythm.

### Speaker Card
**Role:** Display individual speaker profiles.

Features a circular monochrome portrait against a solid, vibrant background color (e.g., #24cb71, #c7f8fb), with speaker name in Figma Sans Text 600 and title in Figma Sans Text 400, both #000000.

## Do's and Don'ts

### Do
- Prioritize #000000 and #ffffff as primary text and background colors respectively, establishing a high-contrast foundation.
- Use Figma Sans Display for all major headings and prominent text elements, leveraging its varied sizes and tight line heights for impact.
- Apply -0.02em letter-spacing to Figma Sans Display at larger sizes (56px and up) to maintain visual density.
- Utilize Jade Accent (#24cb71) and Aqua Wash (#c7f8fb) as large, flat background color blocks to define sections and provide strong visual breaks.
- Maintain a clear element gap of 24px between distinct interface elements for spaciousness.
- Incorporate 1px solid #000000 borders for subtle delineation of interactive states or containers where a delicate definition is needed.

### Don't
- Avoid using soft shadows or gradients for elevation; surfaces should primarily be flat and distinct through color blocks or sharp outlines.
- Do not introduce additional sans-serif fonts; restrict typography to the specified Figma Sans Text, Figma Sans Display, and Source Sans Pro for consistency.
- Refrain from small, intricate patterns; favor large, bold geometric shapes and solid color fields for graphical elements.
- Do not introduce more than two distinct chromatic accent colors per page to maintain the graphic rigor.
- Avoid standard button styles with fills and explicit borders for primary actions; use ghost button treatments or text links within defined areas.
- Do not use smaller spacing units (e.g., 4px, 8px) for large section separation; reserve 60px for section gaps and 24px for component-level spacing.

## Imagery

The imagery is a blend of abstract geometric compositions and tightly cropped, high-contrast monochrome photography. Abstract graphics feature overlapping circles, squares, and polygonal shapes in a vibrant, unpredictable palette, often used as full-bleed backgrounds or section dividers. Photography consists of black and white headshots with high contrast, often set against a single, bold background color (like Jade Accent or Aqua Wash), giving a graphic, almost poster-like quality. Icons are minimal, outlined, and monochromatic, with a fine stroke weight, serving primarily as functional UI elements rather than elaborate decoration. The approach is graphic-heavy, with imagery functioning decoratively and to provide strong visual anchors.

## Layout

The page primarily uses a full-bleed layout, where sections extend across the full width of the viewport, with content often centered or left-aligned within. The hero section features a stark black background with a large, centered headline. Subsequent sections alternate between solid color backgrounds and more complex, abstract graphic patterns. Content often uses a centered stacking approach or a 2-column layout (text left, image right) within these full-width bands. A 4-column grid is evident for speaker profiles. Vertical spacing is consistent between sections, often using the 60px section gap. Navigation is a minimal top bar, fixed to the top, with simple text links.

## Agent Prompt Guide

primary action: no distinct CTA color

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #e2e2e2;
  --color-charcoal-text: #0f0f0f;
  --color-jade-accent: #24cb71;
  --color-aqua-wash: #c7f8fb;

  /* Typography — Font Families */
  --font-figma-vf-normal-700-75: 'Figma VF-normal-700-75', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-sans-text: 'Figma Sans Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-sans-display: 'Figma Sans Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-mono: 'Figma Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-figma-vf-normal-400-100: 'Figma VF-normal-400-100', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.22;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.12px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 16px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-links: 20px;
  --radius-buttons: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #e2e2e2;
  --color-charcoal-text: #0f0f0f;
  --color-jade-accent: #24cb71;
  --color-aqua-wash: #c7f8fb;

  /* Typography */
  --font-figma-vf-normal-700-75: 'Figma VF-normal-700-75', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-sans-text: 'Figma Sans Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-sans-display: 'Figma Sans Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figma-mono: 'Figma Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-figma-vf-normal-400-100: 'Figma VF-normal-400-100', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.22;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.12px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-2xl: 20px;
}
```
