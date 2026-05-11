# Artandcommerce — Style Reference
> monochrome gallery canvas

**Theme:** dark

Art + Commerce employs an austere, high-contrast visual system that prioritizes content over decoration. Its dark canvas serves as a gallery wall for large-format imagery, punctuated by fine-lined typography and a strong emphasis on horizontal and vertical rules. The visual density is minimal, giving imagery ample negative space to command attention, while interactive elements are subtly defined through crisp borders and tight letter-spacing.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Night | `#000000` | `--color-deep-night` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ghost White | `#e7e7e7` | `--color-ghost-white` | Subtle border within navigation elements, offering a nearly-black-on-black distinction for interaction states |

## Tokens — Typography

### Adobe Garamond — Principle typeface for headings, larger display text, and significant links. Its classic serifs provide an editorial, almost archival feel against the minimal background. · `--font-adobe-garamond`
- **Substitute:** Cormorant Garamond
- **Weights:** 400
- **Sizes:** 16px, 20px, 56px
- **Line height:** 1.10, 1.30
- **Letter spacing:** -0.0180em
- **Role:** Principle typeface for headings, larger display text, and significant links. Its classic serifs provide an editorial, almost archival feel against the minimal background.

### Akzidenz Grotesk — Used for navigation, body text, and smaller informational labels. Its geometric sans-serif nature provides a modern, functional counterpoint to the Garamond, with tight, tracked-out spacing for clarity in small sizes. · `--font-akzidenz-grotesk`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 700
- **Sizes:** 8px, 10px, 16px
- **Line height:** 1.00, 1.25, 1.30
- **Letter spacing:** 0.0270em, 0.0300em, 0.0330em, 0.0380em
- **Role:** Used for navigation, body text, and smaller informational labels. Its geometric sans-serif nature provides a modern, functional counterpoint to the Garamond, with tight, tracked-out spacing for clarity in small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.3 | — | `--text-caption` |
| body-sm | 20px | 1.3 | — | `--text-body-sm` |
| body | 56px | 1.3 | — | `--text-body` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 44 | 44px | `--spacing-44` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Layout

- **Section gap:** 44px
- **Card padding:** 16px
- **Element gap:** 12px

## Components

### Navigation Link
**Role:** Primary navigation element

Text in Akzidenz Grotesk weight 400 at 16px, color Deep Night. Features a subtle bottom border of 1px solid Deep Night on hover or active state, with 12px vertical padding and 16px horizontal padding. The border uses Ghost White for emphasis within the dark theme.

## Do's and Don'ts

### Do
- Prioritize large, editorial imagery as the focal point on every page.
- Use Deep Night (#000000) for all backgrounds and primary text to maintain a high-contrast, gallery-like aesthetic.
- Employ Adobe Garamond (substitute Cormorant Garamond) for all primary headings and display text, setting it at 56px line-height 1.1 with -0.0180em letter-spacing.
- Use Akzidenz Grotesk (substitute Open Sans) at 16px, weight 400, for navigation and body copy, with prominent letter-spacing (0.027em-0.038em) for legibility.
- Define interactive elements like navigation items with fine 1px borders using Ghost White (#e7e7e7) against the Deep Night background.
- Maintain generous vertical spacing between content sections, using a consistent sectionGap of 44px.
- Ensure horizontal grid items (like image galleries) have column and row gaps of 8px for a comfortable density.

### Don't
- Avoid using any vibrant accent colors; the palette is strictly monochrome to highlight imagery.
- Do not use box-shadows or other elevation effects; all elements should appear flat against the background.
- Refrain from using bold or heavy weights for headings; Adobe Garamond 400 should convey weight through size, not density.
- Do not apply large border radii to any elements; maintain sharp, crisp edges.
- Avoid decorative gradients or background patterns; clean, solid colors are paramount.
- Do not introduce unnecessary visual complexity; the design should feel spartan and content-focused.
- Never use automatic letter-spacing for Akzidenz Grotesk text; tracking must be explicitly set to its specific positive values (0.027em - 0.038em).

## Imagery

This system heavily relies on large, impactful photography, often full-bleed or occupying significant viewport space. Photography is the content, not just decoration, featuring artful, often surreal or high-fashion editorial imagery. Images are typically raw-edged without masks or contained frames, letting them blend seamlessly into the dark canvas. The visual language is image-heavy, providing atmospheric context and showcasing the work itself. There are no consistent icon styles or illustrations; the focus is exclusively on photographic content.

## Layout

The page adheres to a full-bleed layout, where hero imagery extends to the edges of the viewport. Content then flows vertically with large visual sections dominating the screen, often displaying single, impactful images with minimal accompanying text. Vertical rhythm is established through consistent section gaps (44px) between large content blocks. The navigation is a minimal top bar, fixed to the top left, with simple text links. Content arrangement for image grids utilizes tight 8px gaps, emphasizing the collective body of work rather than individual separation.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #000000
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary navigation item: Akzidenz Grotesk weight 400, 16px, letter-spacing 0.0300em, color Deep Night (#000000), with 12px vertical padding and 16px horizontal padding. On hover, add a 1px solid Ghost White (#e7e7e7) bottom border.
2. Create a hero section with an image: Background Deep Night (#000000). Image full-bleed. Overlay headline: Adobe Garamond weight 400, 56px, line-height 1.1, letter-spacing -0.0180em, color Deep Night (#000000). Bottom caption: Akzidenz Grotesk weight 400, 10px, letter-spacing 0.0380em, color Deep Night (#000000), aligned left.

## Similar Brands

- **AWARDS.COM** — Monochrome, text-heavy navigation with prominent letter-spacing and a focus on high-quality visual content.
- **Magnum Photos** — Dark, minimal background putting full emphasis on large, high-resolution photography as the primary content.
- **Art Basel** — Editorial feel with classic serifs, minimal UI, and a strong dark mode to showcase art pieces.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-night: #000000;
  --color-ghost-white: #e7e7e7;

  /* Typography — Font Families */
  --font-adobe-garamond: 'Adobe Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-akzidenz-grotesk: 'Akzidenz Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.3;
  --text-body-sm: 20px;
  --leading-body-sm: 1.3;
  --text-body: 56px;
  --leading-body: 1.3;

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
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 44px;
  --card-padding: 16px;
  --element-gap: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-night: #000000;
  --color-ghost-white: #e7e7e7;

  /* Typography */
  --font-adobe-garamond: 'Adobe Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-akzidenz-grotesk: 'Akzidenz Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.3;
  --text-body-sm: 20px;
  --leading-body-sm: 1.3;
  --text-body: 56px;
  --leading-body: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;
}
```
