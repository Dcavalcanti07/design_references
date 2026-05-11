# Relace — Style Reference
> Blueprint on off-white marble

**Theme:** light

Relace embraces an 'architectural blueprint on white marble' aesthetic, marrying sophisticated typography with a minimalist, high-contrast monochrome palette. The interface relies on crisp black text against a creamy off-white canvas, subtly punctuated by a single vibrant goldenrod yellow that functions as the brand's primary accent. Spacing is comfortable, creating breathing room around content blocks, while rounded corners soften interactive elements. The system projects a sense of precise, deliberate engineering.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Cream | `#fffef2` | `--color-canvas-cream` | Page backgrounds, main canvas, light utility sections. Offers a soft, warm base for content |
| Ink Black | `#000000` | `--color-ink-black` | Primary body text, headings, prominent borders, icons. Provides high contrast against light backgrounds |
| Rich Coal | `#191918` | `--color-rich-coal` | Used for slightly softer body text than Ink Black, also for backgrounds of darker content blocks and secondary borders. Maintains high contrast while adding subtle depth |
| Pale Stone | `#edece0` | `--color-pale-stone` | Subtle background for panels and content groupings, providing a faint visual separation from Canvas Cream |
| Muted Slate | `#75756f` | `--color-muted-slate` | Secondary text, disabled states, ghost button text and borders. Softer contrast for less emphasis |
| Warm Gray | `#bab9b0` | `--color-warm-gray` | Low-contrast background for subtle design elements or dividers |
| Goldenrod Accent | `#fcaa2d` | `--color-goldenrod-accent` | Yellow outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Parabole Trial — Primary text for headings, body, and prominent links. Its refined design gives a strong, intellectual character, particularly with its tight tracking at larger sizes. · `--font-parabole-trial`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 14px, 20px
- **Line height:** 1.06, 1.50
- **Letter spacing:** -0.05em at 64px, -0.04em at 40px, -0.03em at 20px and 14px, 0.04em at 16px
- **Role:** Primary text for headings, body, and prominent links. Its refined design gives a strong, intellectual character, particularly with its tight tracking at larger sizes.

### Decima Mono Pro — Used for code snippets, secondary labels, and descriptive text requiring a technical, precise feel. · `--font-decima-mono-pro`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 10px, 12px, 16px
- **Line height:** 1.10
- **Letter spacing:** 0.03em at 10px, 0.04em at 16px
- **Role:** Used for code snippets, secondary labels, and descriptive text requiring a technical, precise feel.

### Karla — Fallback and utilitarian text where a less formal, more readable sans-serif is appropriate, often for smaller text elements. · `--font-karla`
- **Substitute:** Karla
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and utilitarian text where a less formal, more readable sans-serif is appropriate, often for smaller text elements.

### Parabole Trial Regular Text — Parabole Trial Regular Text — detected in extracted data but not described by AI · `--font-parabole-trial-regular-text`
- **Weights:** 400
- **Sizes:** 10px, 12px, 16px, 18px, 36px, 40px, 64px
- **Line height:** 1.1, 1.2, 1.5
- **Letter spacing:** -0.05, -0.04, 0.04
- **Role:** Parabole Trial Regular Text — detected in extracted data but not described by AI

### Parabole Trial Regular Display — Parabole Trial Regular Display — detected in extracted data but not described by AI · `--font-parabole-trial-regular-display`
- **Weights:** 400
- **Sizes:** 36px, 40px, 64px
- **Line height:** 1.1
- **Letter spacing:** -0.05, -0.04
- **Role:** Parabole Trial Regular Display — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.1 | — | `--text-caption` |
| body | 16px | 1.5 | 0.64px | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 36px | 1.1 | -1.8px | `--text-heading-sm` |
| heading | 40px | 1.1 | -1.6px | `--text-heading` |
| display | 64px | 1.1 | -3.2px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| icons | 800px |
| buttons | 800px |
| controls | 2px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to Action

Text: Ink Black, Parabole Trial 400. Background: Goldenrod Accent. Padding: 10px vertical, 20px horizontal. Border-radius: 800px (full pill).

### Ghost Outline Button
**Role:** Secondary Action

Text: Muted Slate, Parabole Trial 400. Background: Canvas Cream. Border: 1px Muted Slate. Padding: 10px vertical, 20px horizontal. Border-radius: 800px (full pill).

### Navigation Link
**Role:** Top Navigation Item

Text: Rich Coal, Parabole Trial 400 at 12px (line-height 1.2). Padding: 8px vertical, 20px horizontal. No background or border.

### Main Heading
**Role:** Primary Content Title

Text: Ink Black, Parabole Trial 400 at 64px, line-height 1.1, letter-spacing -0.05em.

### Body Text
**Role:** Standard Paragraph Text

Text: Rich Coal, Parabole Trial 400 at 16px, line-height 1.5.

### Inline Badge
**Role:** Decorative Label

Text: Ink Black, Parabole Trial 400. Background: transparent. Padding: 96px top, 40px left/right. Border-radius: 0px.

### FAQ Accordion Item
**Role:** Expandable Content Header

Text: Ink Black, Parabole Trial 500 at 14px. Background: Canvas Cream. Bottom Border: 1px Rich Coal. Padding: 12px vertical. Icon: Plus/minus icon in Ink Black.

## Do's and Don'ts

### Do
- Prioritize Parabole Trial for all primary text elements, adjusting weight and letter-spacing according to type scale for strong visual impact.
- Use Goldenrod Accent (#fcaa2d) exclusively for primary calls to action, brand highlights, and small functional elements.
- Employ the 800px border-radius for all interactive buttons and prominent icons to create a consistent 'pill' shape.
- Maintain high contrast by typically pairing Ink Black (#000000) or Rich Coal (#191918) with Canvas Cream (#fffef2) or Pale Stone (#edece0).
- Separate content sections with ample vertical spacing, prioritizing 40px and 60px section gaps.
- Use Decima Mono Pro for all code-related content and small, precise labels, ensuring 0.03em or 0.04em letter spacing.
- Leverage the distinct levels of gray (Canvas Cream, Pale Stone, Muted Slate) to provide subtle surface distinction without relying on shadows.

### Don't
- Avoid using Goldenrod Accent (#fcaa2d) for general text or decorative elements that are not interactive or brand-critical.
- Do not introduce additional chromatic colors; the palette is intentionally limited to the monochrome range plus one accent.
- Refrain from using hard, square corners on interactive elements; favor the established 800px or 2px radii.
- Do not deviate from the specified type scales and letter-spacing for Parabole Trial – these are critical to the brand's typographic voice.
- Avoid generic drop shadows; rely on background color changes (e.g., Pale Stone) for separation between elements where possible.
- Do not use generic system fonts when Parabole Trial or Decima Mono Pro are available, even for small text.
- Do not clutter layouts; maintain comfortable spacing between elements and sections as defined by the element and section gaps.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Cream | `#fffef2` | Primary page background and base for most content. |
| 2 | Pale Stone | `#edece0` | Used for subtly differentiated content blocks and panels, offering a slight visual lift from the canvas. |

## Imagery

The imagery style is minimal and functional. Photography, when present in full-bleed sections, appears as desaturated, atmospheric natural landscapes (e.g., mountains), usually serving as a background for UI elements. Product screenshots are typically dark-themed code editors or terminal windows, presented within larger UI blocks without additional borders. There are also abstract, geometric line illustrations and simple, filled or outlined monochrome icons (e.g., plus signs, arrows, checkmarks) in Ink Black or Muted Slate. Imagery is used decoratively rather than informatively, contributing to atmosphere or breaking large text blocks, without dominating the visual space.

## Layout

The page primarily uses a full-bleed structure but contains content within a logical max-width. The hero section often features a split layout with a large, tracked headline on the left and supporting text/CTAs on the right, sometimes overlaid on a subtle background image. Sections alternate between pure white/cream backgrounds and very light gray backgrounds and occasionally dark-themed content blocks for code examples or unique features. Content is arranged in left-aligned blocks, often with a two-column or three-column grid for features and frequently asked questions, exhibiting consistent vertical spacing between major sections (40-60px). Navigation is a fixed top bar on a Canvas Cream background, with an integrated primary action button.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #fffef2
- border: #191918
- accent: #fcaa2d
- primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a main page hero heading: Text 'Models built for coding agents' in Ink Black (#000000), Parabole Trial, 400 weight, 64px font size, 1.1 line-height, -3.2px letter-spacing.
3. Create a secondary ghost button: Text 'Sign Up for Free' in Muted Slate (#75756f), Parabole Trial, 400 weight. Background Canvas Cream (#fffef2). 1px border in Muted Slate (#75756f). Padding 10px vertical, 20px horizontal. Border-radius 800px.
4. Create a page section with a Pale Stone (#edece0) background, containing body text in Rich Coal (#191918) using Parabole Trial, 400 weight, 16px font size, 1.5 line-height. Ensure a vertical section gap of 40px.

## Similar Brands

- **Linear** — Shares a meticulous, high-contrast monochrome aesthetic with a single, clear brand accent color and precise typography.
- **Replit** — Similar focus on developer tools with an emphasis on code-editor styling and a clean, functional UI, albeit with different color palettes.
- **Vercel** — Employs a sophisticated, minimalist design with strong typography, ample whitespace, and a high-tech feel, often using subtle background patterns.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-cream: #fffef2;
  --color-ink-black: #000000;
  --color-rich-coal: #191918;
  --color-pale-stone: #edece0;
  --color-muted-slate: #75756f;
  --color-warm-gray: #bab9b0;
  --color-goldenrod-accent: #fcaa2d;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial: 'Parabole Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-decima-mono-pro: 'Decima Mono Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial-regular-text: 'Parabole Trial Regular Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial-regular-display: 'Parabole Trial Regular Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.64px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -1.8px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -1.6px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 800px;

  /* Named Radii */
  --radius-icons: 800px;
  --radius-buttons: 800px;
  --radius-controls: 2px;

  /* Surfaces */
  --surface-canvas-cream: #fffef2;
  --surface-pale-stone: #edece0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-cream: #fffef2;
  --color-ink-black: #000000;
  --color-rich-coal: #191918;
  --color-pale-stone: #edece0;
  --color-muted-slate: #75756f;
  --color-warm-gray: #bab9b0;
  --color-goldenrod-accent: #fcaa2d;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial: 'Parabole Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-decima-mono-pro: 'Decima Mono Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial-regular-text: 'Parabole Trial Regular Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parabole-trial-regular-display: 'Parabole Trial Regular Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.64px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -1.8px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -1.6px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -3.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 800px;
}
```
