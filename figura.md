# Figura — Style Reference
> Midnight Command Console: high-contrast text on deep black surfaces, punctuated by precise interactions and measured spacing.

**Theme:** dark

Figura employs a stark, high-contrast dark mode aesthetic, reminiscent of a command line interface or developer tool. The visual system prioritizes clarity and directness through a predominantly monochrome palette, precise typography, and a compact yet considered spacing system. Interaction is marked by subtle glowing effects and crisp outlines, creating a sense of understated confidence. The design feels sharp, functional, and devoid of superfluous decoration, focusing entirely on speed and outcome.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text color, occasional borders, and the background for elements that flip the dominant dark mode contrast. Used sparingly to provide points of focus and readability |
| Medium Gray | `#8f8f8f` | `--color-medium-gray` | Subtler text, helper text, and secondary borders. Offers a lower contrast than Canvas White against Absolute Zero, ideal for less prominent information |
| Surface Dark | `#1f1f1f` | `--color-surface-dark` | Slightly elevated surface backgrounds, creating a subtle layer over the Absolute Zero canvas without introducing significant visual noise |
| Sky Glint | `linear-gradient(90deg, rgb(212, 234, 239) 0%, rgb(199, 219, 220) 25%, rgb(228, 232, 228) 50%, rgb(160, 197, 239) 75%, rgb(216, 217, 196) 87.5%, rgb(242, 204, 202) 100%)` | `--color-sky-glint` | Subtle, ethereal gradient used for atmospheric background effects or abstract visual elements. A cooler blend of blues and greens |
| Ocean Calm | `linear-gradient(90deg, rgb(179, 213, 223) 0%, rgb(179, 211, 225) 25%, rgb(204, 224, 229) 50%, rgb(215, 233, 237) 75%, rgb(202, 221, 225) 100%)` | `--color-ocean-calm` | Softer, more cohesive background gradient, providing a gentle shift in tone. Used for large, less pronounced background areas |

## Tokens — Typography

### Inter Display — Primary typeface for all headings and body text, establishing a modern, readable tone. The tight letter spacing for larger sizes adds to the brand's sharp and efficient feel. · `--font-inter-display`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 22px, 32px, 36px
- **Line height:** 1.22, 1.33, 1.36, 1.38, 1.40, 1.43, 1.50, 1.87
- **Letter spacing:** -0.0300em at 36px, -0.0200em at 32px, -0.0100em at 22px, 0.0200em for smaller text, 0.1000em for uppercase elements
- **Role:** Primary typeface for all headings and body text, establishing a modern, readable tone. The tight letter spacing for larger sizes adds to the brand's sharp and efficient feel.

### Geist Mono — Monospace typeface primarily used for code snippets, metadata, or decorative, technical accents. Its presence hints at a precision-oriented, developer-friendly brand. · `--font-geist-mono`
- **Substitute:** Fira Code
- **Weights:** 500, 600
- **Sizes:** 10px, 12px
- **Line height:** 1.20, 1.33, 1.40
- **Letter spacing:** 0.0200em, 0.0400em
- **Role:** Monospace typeface primarily used for code snippets, metadata, or decorative, technical accents. Its presence hints at a precision-oriented, developer-friendly brand.

### sans-serif — Fallback for system text and certain very small utility elements, ensuring readability across diverse environments. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback for system text and certain very small utility elements, ensuring readability across diverse environments.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | 0.4px | `--text-caption` |
| heading | 18px | 1.43 | -0.36px | `--text-heading` |
| heading-lg | 20px | 1.38 | -0.4px | `--text-heading-lg` |
| display-sm | 22px | 1.22 | -0.22px | `--text-display-sm` |
| display | 32px | 1.22 | -0.64px | `--text-display` |
| display-lg | 36px | 1.22 | -1.08px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 200px |
| input | 8px |
| badges | 40px |
| buttons | 56px |
| default | 8px |
| largeElement | 32px |

### Layout

- **Section gap:** 96px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Border Button
**Role:** Action Element

Ghost button with an extremely generous border radius of 56px, an 8px vertical padding, 16px horizontal padding. Text color is white, background is transparent. Its outlined aesthetic creates a sense of interactive opportunity without visual dominance.

### Navigation Link
**Role:** Navigation Element

Standard navigation links use Canvas White text against Absolute Zero, 6px vertical padding, 10px horizontal padding, with a system sans-serif font at 12px weight 400. Text transform is uppercase, with a 72px border-radius, giving it a soft, pill-like background hover state.

## Do's and Don'ts

### Do
- Prioritize high contrast: Canvas White (#ffffff) on Absolute Zero (#000000) for all primary text and backgrounds.
- Use Inter Display for all marketing and UI text, applying negative letter-spacing (-0.03em at 36px) to large headlines for a precisely crafted feel.
- Round corners generously for interactive elements: apply 56px radius to all buttons and a 40px radius to smaller, badge-like elements for a soft, approachable feel amidst the stark theme.
- Maintain a compact overall density by adhering to an 8px `elementGap` for stacking elements where breathing room is desired but space is conserved.
- Employ Geist Mono at 10px or 12px with a 0.04em letter-spacing for any technical, code-like, or metadata content.
- Use Medium Gray (#8f8f8f) for secondary, less prominent text, providing visual relief without breaking the monochrome palette.
- Apply Surface Dark (#1f1f1f) for subtle background shifts to indicate layered content or distinct sections, as opposed to heavy shadows or borders.

### Don't
- Avoid generic blue for interactive elements; there is no explicit blue primary action color – rely on ghost button styles and high-contrast text for interactivity.
- Do not introduce heavy shadows; the system relies on subtle background color shifts (`Surface Dark`) for layering, not elevation via drop shadows.
- Refrain from using excessively decorative typography or bright, saturated colors that are not part of the defined accent gradients.
- Avoid uneven spacing; adhere to the 4px base unit and established `elementGap` for internal component spacing to maintain consistency.
- Do not use generic, default corner radii; always reference the specified radii like 56px for buttons and 40px for badges to maintain brand distinctiveness.
- Do not use the primary sans-serif system font (Arial/Helvetica) for anything other than specific utility text as a last resort; default to Inter Display.

## Imagery

This site features product screenshots of mobile applications, presented raw without masks or heavy embellishments, indicating a focus on functionality over stylized marketing. The images are contained within the white phone frames, effectively bringing lighter 'screen' content into the dark interface environment. There are no full-bleed marketing images or abstract illustrations. Iconography is assumed to be minimal and functional, not decorative. Imagery serves a direct explanatory or product showcase role, contributing to a text-dominant layout.

## Layout

The page uses a full-bleed layout, primarily driven by the Absolute Zero background. Content is centrally stacked, featuring a prominent hero section with a centered headline and ghost buttons. Subsequent sections alternate between full-width black backgrounds and sections containing detailed product imagery. Vertical spacing between sections is generous, around 96px, but internal element spacing is compact with an 8px `elementGap`. There is no fixed max-width for the overall page, allowing content to stretch edge-to-edge. Navigation is a simple top bar with left-aligned branding and right-aligned text links leading to distinct pages.

## Agent Prompt Guide

**Quick Color Reference:**
text: #ffffff
background: #000000
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

**3-5 Example Component Prompts:**
1. Create a primary hero section: background Absolute Zero, with a display-lg headline in Canvas White. Below the headline, include a Ghost Border Button (Canvas White text, transparent background, #ffffff border of 1px, 56px radius, 8px vertical padding, 16px horizontal padding) labeled 'Book a call'.
2. Design a navigation bar: background Absolute Zero, with the brand logo on the left and a 'Manifesto' Navigation Link (Canvas White text, 12px sans-serif, 72px radius, 6px vertical padding, 10px horizontal padding) on the right.
3. Implement a section intro: background Surface Dark (#1f1f1f), centered heading-lg in Canvas White. Below, add a small, descriptive caption in Medium Gray (#8f8f8f) using body-sm text.

## Similar Brands

- **Linear** — Shares a high-contrast dark theme, focus on functional UI, and precise typography.
- **Raycast** — Uses a similar developer-tool aesthetic with deep dark backgrounds and stark white text for clarity.
- **Superhuman** — Employs an extremely clean, high-efficiency dark UI with minimal ornamentation and sharp typography.
- **Vercel** — Features a dark, developer-centric interface with clear information hierarchy and often ghost-style buttons.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --color-medium-gray: #8f8f8f;
  --color-surface-dark: #1f1f1f;
  --color-sky-glint: #d4eaef;
  --gradient-sky-glint: linear-gradient(90deg, rgb(212, 234, 239) 0%, rgb(199, 219, 220) 25%, rgb(228, 232, 228) 50%, rgb(160, 197, 239) 75%, rgb(216, 217, 196) 87.5%, rgb(242, 204, 202) 100%);
  --color-ocean-calm: #b3d5df;
  --gradient-ocean-calm: linear-gradient(90deg, rgb(179, 213, 223) 0%, rgb(179, 211, 225) 25%, rgb(204, 224, 229) 50%, rgb(215, 233, 237) 75%, rgb(202, 221, 225) 100%);

  /* Typography — Font Families */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 0.4px;
  --text-heading: 18px;
  --leading-heading: 1.43;
  --tracking-heading: -0.36px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.38;
  --tracking-heading-lg: -0.4px;
  --text-display-sm: 22px;
  --leading-display-sm: 1.22;
  --tracking-display-sm: -0.22px;
  --text-display: 32px;
  --leading-display: 1.22;
  --tracking-display: -0.64px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.22;
  --tracking-display-lg: -1.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 56px;
  --radius-full-2: 72px;
  --radius-full-3: 200px;

  /* Named Radii */
  --radius-pill: 200px;
  --radius-input: 8px;
  --radius-badges: 40px;
  --radius-buttons: 56px;
  --radius-default: 8px;
  --radius-largeelement: 32px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --color-medium-gray: #8f8f8f;
  --color-surface-dark: #1f1f1f;
  --color-sky-glint: #d4eaef;
  --color-ocean-calm: #b3d5df;

  /* Typography */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 0.4px;
  --text-heading: 18px;
  --leading-heading: 1.43;
  --tracking-heading: -0.36px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.38;
  --tracking-heading-lg: -0.4px;
  --text-display-sm: 22px;
  --leading-display-sm: 1.22;
  --tracking-display-sm: -0.22px;
  --text-display: 32px;
  --leading-display: 1.22;
  --tracking-display: -0.64px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.22;
  --tracking-display-lg: -1.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 56px;
  --radius-full-2: 72px;
  --radius-full-3: 200px;
}
```
