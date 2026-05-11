# Atelier Deux-Cé — Style Reference
> Editorial White Space

**Theme:** light

Atelier Deux-Cé employs a stark, editorial aesthetic, juxtaposing high-contrast monochrome text and imagery against expansive white and off-white canvases. The visual language emphasizes crisp typography, delicate line work, and large-format photography, with color used sparingly as a brand accent within imagery or a single, subtle green in the footer. Most interactive elements are ghost-like, relying on text and soft borders rather than strong fills, creating a highly sophisticated and minimalist experience. The design system is dominated by strong horizontal and vertical rhythms, separating content clearly but with significant breathing room.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight | `#000000` | `--color-midnight` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas | `#ffffff` | `--color-canvas` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Mist | `#d8ddc6` | `--color-mist` | Subtle secondary background for sections, providing a soft tonal shift from the main canvas |
| Sandstone | `#eee5da` | `--color-sandstone` | Background for subtle surface distinction between elements |
| Sage Green | `#259558` | `--color-sage-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Helvetica — Primary text across body, links, navigation, and some headings. Its clean, sans-serif nature underpins the modern, editorial feel. · `--font-helvetica`
- **Substitute:** Arial
- **Weights:** 400, 600
- **Sizes:** 16px, 17px, 20px, 24px
- **Line height:** 1.20
- **Letter spacing:** -0.32px at 16px, -0.68px at 17px
- **Role:** Primary text across body, links, navigation, and some headings. Its clean, sans-serif nature underpins the modern, editorial feel.

### minion-3 — Used for specific heading elements and some body text, providing a classic counterbalance to Helvetica's modernism. · `--font-minion-3`
- **Substitute:** Georgia
- **Weights:** 400
- **Sizes:** 16px, 17px, 24px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for specific heading elements and some body text, providing a classic counterbalance to Helvetica's modernism.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.2 | — | `--text-caption` |
| body-sm | 17px | 1.2 | — | `--text-body-sm` |
| body | 20px | 1.2 | — | `--text-body` |
| body-lg | 24px | 1.2 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 24px

## Components

### Monochrome Link List Item
**Role:** Navigation, category lists

Text in Midnight (#000000) using Helvetica 400 at 16px, no background, no border, with 12px vertical spacing between items.

### Full-Bleed Image Card
**Role:** Portfolio item display

No border, no shadow, 0px radius. Occupies a full area without internal padding. Background is transparent. Text (like 'PLAQ' or 'JOSEPH PERRIER') is Helvetica 400 at 16px, Midnight (#000000). The descriptive text (like 'Visual identity and Design') at 16px Helvetica.

### Header Navigation Link
**Role:** Primary site navigation

Typography set in Helvetica, 16px, weight 400, color Midnight (#000000). Spacing of 8px on top margin. No background or border. Interactivity hinted by text itself.

## Do's and Don'ts

### Do
- Use Midnight (#000000) for all primary text and borders to maintain high contrast and sophistication.
- Prioritize Canvas (#ffffff) as the primary background color for clarity and an expansive feel.
- Employ Helvetica for all interactive text elements and most body copy, reserving minion-3 for specific heading emphasis.
- Maintain 0px border-radius for all cards and visually distinct containers to ensure sharp, editorial edges.
- Separate content sections with significant vertical spacing, following the 40px section gap for rhythm.
- Keep interactive elements, such as links and navigation, as ghost elements, relying on text color and hover states rather than solid fills or strong borders.
- Use Sage Green (#259558) exclusively as a brand color in the footer, avoiding its use for interactive or semantic elements elsewhere.

### Don't
- Never use strong background colors for interactive elements; all actions should appear as ghost or text links.
- Avoid using rounded corners; maintain 0px border-radius across all components for a sharp aesthetic.
- Do not introduce strong shadows or elevation effects; the design relies on flat surface changes and white space for hierarchy.
- Refrain from using saturated colors for body text or primary headlines; stick to Midnight (#000000) for textual content.
- Do not deviate from Helvetica and minion-3 for typography; other fonts would dilute the editorial identity.
- Avoid dense UI layouts; maintain generous spacing between elements and sections.
- Do not use brand or accent colors for semantic states like success/error; keep the palette achromatic with a single brand accent.

## Imagery

The visual language is heavily reliant on striking, often abstract or close-up photography, and product photography staged against neutral or natural backgrounds. Images are typically full-bleed or contained within sharp-edged canvases, with no visible corner rounding. Photography style is high-key and product-focused, with strong textural detail or evocative natural light. It serves as decorative atmosphere and product showcase rather than explanatory content. The site is image-heavy, using large visuals to dominate sections and convey mood.

## Layout

The page primarily uses a full-bleed layout, allowing hero imagery to span the viewport. Content within sections adheres to a comfortable max-width, though the exact value is not fixed. The hero section often features large, split-screen or overlayed imagery with minimal text. Section rhythm is marked by consistent vertical spacing of 40px, creating clear divisions. Content is frequently presented in a simple, single-column stack, often with text-heavy blocks or prominent single images. Navigation is a minimal top bar, featuring the brand identity and hamburger icon.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: #259558
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: full-bleed image on left, text on right. Headline: Helvetica 600 at 24px, #000000, 1.2 line height. Body text: Helvetica 400 at 16px, #000000, 1.2 line height. Horizontal rule: 1px deep, #000000 border top, 24px margin top.
Create a navigation link: 'About' in Helvetica 400, 16px, #000000, no background, 0px border-radius.
Create a footer section: background #259558. Text in Helvetica 400, 16px, #ffffff, 1.2 line height, 40px padding top/bottom. Links in Helvetica 400, 16px, #ffffff.

## Similar Brands

- **AIGA** — Employs an editorial layout, high-contrast typography, and significant white space for content presentation.
- **Studio—JQ** — Minimalist navigation, large-scale imagery without heavy UI elements, dark text on light backgrounds.
- **AREA 17** — Focus on bespoke typography, high resolution imagery, and a clean, spacious grid-based layout for agency portfolios.
- **Basic®.com** — Strong black on white aesthetic, minimalist interactive elements, and a focus on large-format photography for portfolio work.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas: #ffffff;
  --color-mist: #d8ddc6;
  --color-sandstone: #eee5da;
  --color-sage-green: #259558;

  /* Typography — Font Families */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-minion-3: 'minion-3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --text-body: 20px;
  --leading-body: 1.2;
  --text-body-lg: 24px;
  --leading-body-lg: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 24px;

  /* Named Radii */
  --radius-cards: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas: #ffffff;
  --color-mist: #d8ddc6;
  --color-sandstone: #eee5da;
  --color-sage-green: #259558;

  /* Typography */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-minion-3: 'minion-3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --text-body: 20px;
  --leading-body: 1.2;
  --text-body-lg: 24px;
  --leading-body-lg: 1.2;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
}
```
