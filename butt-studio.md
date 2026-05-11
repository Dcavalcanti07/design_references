# BUTT STUDIO — Style Reference
> Minimalist canvas, bold typography, selective accents.

**Theme:** light

BUTT STUDIO employs a high-contrast aesthetic blending stark whitespace with deeply saturated accents. Typography is a focal point, using a mix of classic serif and system sans-serif for clear hierarchy. Layouts are spacious, allowing content and bold elements to breathe, while interactions are subtly animated. The overall impression is one of artful simplicity, where carefully chosen details make a strong visual statement without clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, clear surfaces |
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, borders, decorative elements — creates strong contrast against light surfaces |
| Deep Space | `#131313` | `--color-deep-space` | Dark UI elements backgrounds, content blocks like video players |
| Smoke Gray | `#e0e0e0` | `--color-smoke-gray` | Subtle background for button fills and secondary surface differentiation |

## Tokens — Typography

### helvetica — Body text, navigation links, secondary headings, and button labels. Its neutrality provides a stable baseline against more expressive elements. · `--font-helvetica`
- **Substitute:** Avenir Next, Arial
- **Weights:** 400
- **Sizes:** 20px, 40px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.0300em at 40px, -0.0200em at 20px
- **Role:** Body text, navigation links, secondary headings, and button labels. Its neutrality provides a stable baseline against more expressive elements.

### Caslon — Primary headings and artistic display text. The elegant serif creates a sophisticated, editorial feel. · `--font-caslon`
- **Substitute:** Libre Caslon Display
- **Weights:** 400
- **Sizes:** 42px
- **Line height:** 1.00
- **Letter spacing:** -0.0200em
- **Role:** Primary headings and artistic display text. The elegant serif creates a sophisticated, editorial feel.

### Sometimes Times — Specific display text for project titles or highlighted content. Its unique character adds brand personality. · `--font-sometimes-times`
- **Substitute:** Times New Roman (with custom stylistic sets)
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.20
- **Letter spacing:** -0.0200em
- **Role:** Specific display text for project titles or highlighted content. Its unique character adds brand personality.

### helvetica — Body copy on project descriptions, client lists, and features. Ensures readability in informative sections. · `--font-helvetica`
- **Substitute:** Avenir Next, Arial
- **Weights:** 400
- **Sizes:** 20px, 40px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.0200em
- **Role:** Body copy on project descriptions, client lists, and features. Ensures readability in informative sections.

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 70 | 70px | `--spacing-70` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| buttons | 50px |
| headings | 68px |

### Layout

- **Section gap:** 180px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Pill Button
**Role:** Text button with rounded corners for primary actions.

Background: #e0e0e0 (Smoke Gray). Text color: #000000 (Pitch Black). Border: 1px solid #000000. Radius: 50px. Padding: 5px vertical, 20px horizontal. Font: Helvetica 400, 20px, 1.2 line height.

## Do's and Don'ts

### Do
- Always use Canvas White (#ffffff) for the main page background to maintain visual clarity.
- Apply Pitch Black (#000000) for all primary text and borders to ensure strong contrast and visual impact.
- Utilize Caslon 400 at 42px with 1.0 line height and -0.0200em letter spacing for major headlines.
- Maintain an element gap of 20px for consistent vertical spacing between content blocks.
- Incorporate 50px border-radius specifically for all interactive buttons to establish a consistent brand interaction aesthetic.
- Use 180px as the section gap to create generous visual breaks between distinct content areas.

### Don't
- Avoid using multiple accent colors; concentrate on black and white with minimal chromatic interference.
- Do not deviate from the specified font families or their assigned weights; Helvetica, Caslon, and Sometimes Times are the only typefaces.
- Refrain from using hard-edged rectangles for buttons; all buttons must have a 50px border-radius.
- Do not introduce additional background colors for content sections beyond Canvas White, Deep Space, and Smoke Gray.
- Avoid tight spacing between sections; always adhere to the 180px section gap.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background providing expansive whitespace. |
| 1 | Smoke Gray | `#e0e0e0` | Subtle surfaces for buttons and secondary content blocks. |
| 2 | Deep Space | `#131313` | High-contrast background for media players or distinct dark UI sections. |

## Imagery

This site prominently features product screenshots and video embeds, often with a highly artistic or abstract bent. Imagery is typically contained within rectangular frames, with sharp edges, and tends to dominate its immediate section. The visuals themselves vary from vibrant, saturated photography to abstract animations, serving primarily to showcase the studio's portfolio rather than providing decorative atmosphere. Icons, if present, are minimal and likely black outlines against white backgrounds, functioning as clear functional elements.

## Layout

The page primarily employs a max-width contained layout even though `pageMaxWidth` is null, evident by content being centered with significant whitespace on either side. The hero section features oversized, decorative serif typography with a smaller, pill-shaped button overlayed. Content follows a rhythmic pattern of large media blocks (videos/images) paired with adjacent text descriptions, often in a two-column arrangement. Vertical spacing is generous, creating distinct sections without visible dividers. The navigation appears to be a minimal footer with contact information, client lists, and features.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary headline: Caslon 400, 42px, 1.0 line height, #000000, -0.0200em letter-spacing. Accompanied by Helvetica 400, 20px, 1.2 line height, #000000 for a descriptive subtext. Ensure 8px margin-bottom after the headline.
2. Design a 'Download' button: background #e0e0e0, text #000000, 1px solid #000000 border, 50px border-radius, 5px vertical padding, 20px horizontal padding. Text uses Helvetica 400, 20px, 1.2 line height.
3. Implement a video block: background #131313, with content centered. The block should have 30px padding all around. The element should be followed by a copy block with an 180px gap.

## Similar Brands

- **Stripe** — Uses a minimalist layout with ample whitespace and strong typographic hierarchy, emphasizing clarity.
- **Awwwards** — Showcases creative work with large, impactful visuals and a muted UI that lets content shine.
- **AREA 17** — Features a bold, typographic approach with stark contrast between dark and light sections and an emphasis on visual projects.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-pitch-black: #000000;
  --color-deep-space: #131313;
  --color-smoke-gray: #e0e0e0;

  /* Typography — Font Families */
  --font-helvetica: 'helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caslon: 'Caslon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sometimes-times: 'Sometimes Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xl: 20px;
  --leading-xl: 1.2;
  --text-4xl: 40px;
  --leading-4xl: 1;
  --text-4xl-2: 42px;
  --leading-4xl-2: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-70: 70px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 180px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 50px;
  --radius-full-2: 68px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-buttons: 50px;
  --radius-headings: 68px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-smoke-gray: #e0e0e0;
  --surface-deep-space: #131313;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-pitch-black: #000000;
  --color-deep-space: #131313;
  --color-smoke-gray: #e0e0e0;

  /* Typography */
  --font-helvetica: 'helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caslon: 'Caslon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sometimes-times: 'Sometimes Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xl: 20px;
  --leading-xl: 1.2;
  --text-4xl: 40px;
  --leading-4xl: 1;
  --text-4xl-2: 42px;
  --leading-4xl-2: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-70: 70px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 50px;
  --radius-full-2: 68px;
}
```
