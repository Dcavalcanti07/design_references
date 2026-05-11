# Garden Eight — Style Reference
> velvety stark minimalism

**Theme:** dark

Garden Eight embraces a monochromatic, stark aesthetic, pairing a velvety dark canvas with contrasting cream accents. Typography plays a central role, leveraging a traditional, elaborate serif for display elements and a modern sans-serif for functional text. The sparse use of color and ample negative space amplifies the visual impact of each element.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1e1f1f` | `--color-midnight-ink` | Page backgrounds, primary text, dark UI elements — provides a rich, deep base for content |
| Soft Vanilla | `#dbd6d0` | `--color-soft-vanilla` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Shadowed Text | `#000000` | `--color-shadowed-text` | Highly contrasting primary text used when Soft Vanilla is background, ensuring maximum legibility |

## Tokens — Typography

### gunsan — Display headlines and brand statements — its ornamental features provide a distinctive, old-world elegance. · `--font-gunsan`
- **Substitute:** Playfair Display
- **Weights:** 600
- **Sizes:** 215px
- **Line height:** 0.77
- **Letter spacing:** normal
- **Role:** Display headlines and brand statements — its ornamental features provide a distinctive, old-world elegance.

### lausanne — All functional text, including body copy, navigation, and labels — its clean, modern lines offer high legibility. · `--font-lausanne`
- **Substitute:** Inter
- **Weights:** 200, 400
- **Sizes:** 12px, 14px, 15px, 215px
- **Line height:** 1.25, 1.30, 1.42, 1.50, 1.60
- **Letter spacing:** normal
- **Role:** All functional text, including body copy, navigation, and labels — its clean, modern lines offer high legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| display | 215px | 0.77 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 27 | 27px | `--spacing-27` |
| 30 | 30px | `--spacing-30` |
| 38 | 38px | `--spacing-38` |
| 45 | 45px | `--spacing-45` |
| 60 | 60px | `--spacing-60` |
| 180 | 180px | `--spacing-180` |
| 210 | 210px | `--spacing-210` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 1440px |
| general | 30px |

### Layout

- **Section gap:** 60px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Ghost Navigation Button
**Role:** Navigation and secondary actions

Text-only buttons using Soft Vanilla for text, appearing as elegant, understated navigation items. Features flexible padding and a thin 1px Soft Vanilla border on hover/active states.

### Pill Outline Button
**Role:** Primary interactive element for calls to action

Features a 1px Soft Vanilla border, Soft Vanilla text, and 1440px border-radius for a distinct pill shape. Padding is 1px top/bottom and 12px left/right.

## Do's and Don'ts

### Do
- Use Midnight Ink (#1e1f1f) for all primary backgrounds and main body text to maintain the dark theme.
- Apply Soft Vanilla (#dbd6d0) for all interactive elements, secondary text, and borders to create contrast.
- Utilize the gunsan font at 215px with line-height 0.77 for all prominent display headlines, embodying an ornate aesthetic.
- Ensure all functional text, including navigation and body copy, uses the lausanne font in weights 200 or 400 for clarity.
- Employ a 1440px border-radius for all button-like elements to achieve a distinct pill-shaped appearance.
- Maintain generous horizontal padding of 180px for main content areas to create a spacious feel.
- Use 1px borders in Soft Vanilla (#dbd6d0) for subtle emphasis on interactive outlines.

### Don't
- Avoid using saturated colors other than Vivid Orange (#dc5648) as it is reserved for rare accent states.
- Do not use box-shadows or elevation effects; the design relies on flat surfaces and high contrast.
- Do not deviate from the defined lausanne (sans-serif) and gunsan (serif) fonts; no other typefaces are permitted.
- Avoid tight spacing between elements; maintain adequate elementGap (4px minimum) and sectionGap (60px) to preserve density.
- Do not use sharp corners on interactive components; ensure buttons always have a 1440px border-radius.
- Do not introduce gradients into UI elements; maintain a flat color palette.
- Avoid centering content horizontally beyond the main display headline; navigation and body text should align left.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Canvas | `#1e1f1f` | Primary page background and default UI surface. |
| 1 | Soft Highlights | `#dbd6d0` | Used for interactive borders and subtle secondary UI elements against the dark canvas. |

## Imagery

The site uses abstract, fluid 3D renders in a monochromatic, matte-cream palette. These visuals are atmospheric and sculptural, appearing as large, background accents that flow around and behind prominent text rather than serving as direct content or product showcases. The visuals are softly lit, giving them a ceramic or plaster-like quality, and contribute to the site's artful, minimalist tone. Icons are minimal, subtle, and outline-based, appearing with the same text color as surrounding elements.

## Layout

The page primarily uses a full-bleed layout, allowing background visuals to extend to the viewport edges. The hero section features a large, ornate display headline centered over the abstract 3D background. Content sections follow a consistent vertical rhythm with minimal visual dividers, flowing seamlessly. Navigation is a compact, right-aligned bar. Text is predominantly left-aligned, creating clear reading paths within the spacious design.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #1e1f1f
- background: #1e1f1f
- border: #dbd6d0
- accent: #dc5648
- primary action: no distinct CTA color

**3-5 Example Component Prompts:**
- Create a site header with 'Garden Eight' (lausanne font, 15px, #1e1f1f) on the left, and a navigation bar on the right with 'Cases', 'About', 'Archives' (lausanne font, 15px, #1e1f1f, 10px horizontal padding).
- Design a hero section with a centered headline 'WHAT CAN WE MAKE NEXT' (gunsan font, 215px, #1e1f1f, line-height 0.77), over a background of abstract cream 3D shapes.
- Build a secondary content block that uses Soft Vanilla (#dbd6d0) for its background, with black text (#000000) and a Ghost Navigation Button (Soft Vanilla text, no background, 1px Soft Vanilla border on hover, 1440px radius, 1px top/bottom, 12px left/right padding).

## Similar Brands

- **Awwwards** — Shares a sophisticated, dark-themed aesthetic with prominent, artistic typography and subtle interactive elements.
- **Locomotive** — Utilizes a minimalist, high-contrast visual style with a strong focus on custom typography and animated micro-interactions.
- **Dogstudio** — Known for bold, sculptural design, often featuring abstract 3D elements and a refined, dark color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1e1f1f;
  --color-soft-vanilla: #dbd6d0;
  --color-shadowed-text: #000000;

  /* Typography — Font Families */
  --font-gunsan: 'gunsan', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lausanne: 'lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-display: 215px;
  --leading-display: 0.77;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-180: 180px;
  --spacing-210: 210px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-buttons: 1440px;
  --radius-general: 30px;

  /* Surfaces */
  --surface-midnight-canvas: #1e1f1f;
  --surface-soft-highlights: #dbd6d0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1e1f1f;
  --color-soft-vanilla: #dbd6d0;
  --color-shadowed-text: #000000;

  /* Typography */
  --font-gunsan: 'gunsan', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lausanne: 'lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-display: 215px;
  --leading-display: 0.77;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-180: 180px;
  --spacing-210: 210px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-full: 1440px;
}
```
