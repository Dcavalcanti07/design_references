# Laura Monin — Style Reference
> Gallery Grid Serenity

**Theme:** light

Laura Monin's design system evokes an editorial, gallery-like experience with a distinct focus on imagery and classic typography. The minimal, high-contrast monochrome palette ensures visual content takes center stage, while elegant serifs for headlines and classic sans-serifs for body text provide a timeless, refined touch. It prioritizes breathable negative space and structured, but flexible, arrangements of visual elements, creating an atmosphere of understated luxury and artistic presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Text Black | `#000000` | `--color-text-black` | Primary text, headings, navigational links, and subtle borders around imagery |

## Tokens — Typography

### neue-haas-grotesk-display — General body text, navigation elements, image captions, and descriptive labels. Its clean, narrow form maintains clarity in a design focused on imagery. · `--font-neue-haas-grotesk-display`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 12px, 14px, 18px, 22px
- **Line height:** 1.15, 1.20
- **Letter spacing:** normal
- **Role:** General body text, navigation elements, image captions, and descriptive labels. Its clean, narrow form maintains clarity in a design focused on imagery.

### title — Prominent display headings and artistic titles. The negative letter spacing enhances its elegant, curated feel, giving a bespoke editorial touch. · `--font-title`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 58px, 158px
- **Line height:** 1.20
- **Letter spacing:** -0.0180em
- **Role:** Prominent display headings and artistic titles. The negative letter spacing enhances its elegant, curated feel, giving a bespoke editorial touch.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.15 | — | `--text-caption` |
| body | 14px | 1.15 | — | `--text-body` |
| subheading | 18px | 1.15 | — | `--text-subheading` |
| heading | 22px | 1.15 | — | `--text-heading` |
| display-sm | 58px | 1.2 | -0.63px | `--text-display-sm` |
| display | 158px | 1.2 | -2.84px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 9 | 9px | `--spacing-9` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 29 | 29px | `--spacing-29` |
| 37 | 37px | `--spacing-37` |
| 182 | 182px | `--spacing-182` |
| 236 | 236px | `--spacing-236` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| images | 0px |

### Layout

- **Card padding:** 9px
- **Element gap:** 7px

## Components

### Navigation Link
**Role:** Top-right global navigation items.

Uses neue-haas-grotesk-display at 12px weight 400, color #000000. Underlined on hover (not explicitly shown but common interaction). Spacing between items is 16px.

### Hero Title
**Role:** Main page headline / artistic statement.

Utilizes the 'title' font at 158px weight 400, color #000000, with -0.0180em letter-spacing. Centered on the page, serving as a large, impactful visual anchor.

### Image Caption
**Role:** Descriptive text accompanying visual content.

Formatted with neue-haas-grotesk-display at 12px weight 400, color #000000. Often appears directly above or below an image, using a 7px bottom margin (if it's a list item).

### Info/Contact Link
**Role:** Small, functional links for contact or additional information.

neue-haas-grotesk-display at 12px weight 400, color #000000. Often appears in close proximity to a larger visual element or as secondary navigation.

### Gallery Image Card
**Role:** Primary content display for portfolio images.

Images are displayed with sharp 0px corners, often bordered with a thin #000000 stroke on hover or interaction (implied by color role evidence). Text captions are placed in close vertical proximity.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all backgrounds and primary containers to achieve a bright, expansive feel.
- Use Text Black (#000000) for all text elements to maintain high contrast and an editorial aesthetic.
- Reserve the 'title' font for large display headlines, applying its specific -0.0180em letter-spacing for an elegant, bespoke look.
- Apply neue-haas-grotesk-display for all body copy, navigation, and supplementary text roles, strictly at weight 400.
- Maintain generous vertical spacing between sections, using values such as 255px (sectionGap) to create a sense of calm and visual breathing room.
- Frame images with no border-radius (0px) to enhance the gallery-like, art-focused presentation.
- Utilize a minimal element gap of 7px to imply close association between elements like image and caption lists.

### Don't
- Avoid using any saturated colors for UI elements; stick to the dominant #ffffff and #000000 palette.
- Do not introduce rounded corners (e.g., 4px, 8px) on any image containers or cards; all visuals should retain sharp, rectilinear edges.
- Refrain from using heavily bolded text across the interface; the system relies on weight 400 for both primary fonts.
- Do not overcrowd sections; maintain generous negative space consistent with the 255px sectionGap.
- Avoid adding unnecessary shadows or complex visual effects; the design emphasizes flatness and clarity.
- Do not deviate from the specified font families; their distinct characteristics are central to the brand's identity.
- Do not introduce additional padding or margins that disrupt the established spacing rhythm defined by 7px element gaps and 255px section margins.

## Imagery

The site relies primarily on high-quality, product-focused photography and lifestyle fashion shots. Images are treated with sharp, non-rounded edges, appearing as self-contained 'cards' on a vast white canvas. They serve as the main content, often paired with minimal text overlays or adjacent captions. The aesthetic is often bright, airy, and reflective of fashion photography, giving a sophisticated, magazine-like feel. Icons are not a prominent feature, and illustrations are absent, emphasizing photographic realism.

## Layout

The page primarily employs a full-bleed layout for the canvas, but content, especially imagery, is centrally anchored and surrounded by significant negative space. The hero element is a large, centered, serif headline. Images are arranged in an asymmetrical, editorial grid, often floating with generous whitespace. Sections appear to flow seamlessly without strong visual dividers, relying on spacious vertical gaps (approx. 255px). Navigation is minimal, located at the top-right.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000 (implied for image outlines/interactive states)
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a page header: background #ffffff. Top-level navigation 'Index', 'Infos', 'Archives' using neue-haas-grotesk-display at 12px weight 400, color #000000, with 16px right margin between items. Place navigation at the top-right.
2. Design a central Hero section: centered 'La Croisette' title using 'title' font at 158px weight 400, color #000000, with letter-spacing -0.0180em. Follow with a text description 'Fashion & Textile Designer' using neue-haas-grotesk-display at 18px weight 400, color #000000, centered, directly below the title.
3. Implement a gallery item: display an image with 0px radius. Below it, a caption like 'LAURA MONIN' using neue-haas-grotesk-display at 12px weight 400, color #000000. Ensure 7px vertical spacing between the image and the caption.

## Similar Brands

- **The Row** — Shares a stark, minimalist aesthetic with heavy reliance on monochrome palette, generous whitespace, and sharp-edged photography.
- **Acne Studios** — Employs an editorial layout style, often with large display typography and a focus on fashion photography as the primary content.
- **Vogue.com** — Features a classic editorial grid with high-impact imagery and a balance of elegant serif headlines and clean sans-serif body text.
- **Frank Ocean's Homer** — Uses a clean, image-centric, high-contrast black and white interface with custom, distinctive typography for a luxury feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-text-black: #000000;

  /* Typography — Font Families */
  --font-neue-haas-grotesk-display: 'neue-haas-grotesk-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-title: 'title', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.15;
  --text-body: 14px;
  --leading-body: 1.15;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --text-heading: 22px;
  --leading-heading: 1.15;
  --text-display-sm: 58px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -0.63px;
  --text-display: 158px;
  --leading-display: 1.2;
  --tracking-display: -2.84px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-29: 29px;
  --spacing-37: 37px;
  --spacing-182: 182px;
  --spacing-236: 236px;

  /* Layout */
  --card-padding: 9px;
  --element-gap: 7px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-images: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-text-black: #000000;

  /* Typography */
  --font-neue-haas-grotesk-display: 'neue-haas-grotesk-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-title: 'title', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.15;
  --text-body: 14px;
  --leading-body: 1.15;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --text-heading: 22px;
  --leading-heading: 1.15;
  --text-display-sm: 58px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -0.63px;
  --text-display: 158px;
  --leading-display: 1.2;
  --tracking-display: -2.84px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-29: 29px;
  --spacing-37: 37px;
  --spacing-182: 182px;
  --spacing-236: 236px;
}
```
