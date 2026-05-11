# Ssense — Style Reference
> Gallery Wall Blueprint – A precisely gridded display of curated visuals on a clean, unobtrusive canvas.

**Theme:** light

This design system evokes a raw, editorial aesthetic, balancing high fashion photography with an almost stark, functional UI. The interplay of classic serif typography for headlines and a utilitarian sans-serif for body text creates a tension, amplified by the near-monochromatic palette. Minimal use of color and a focus on content photography establishes a luxurious but unpretentious feel, prioritizing visual storytelling over decorative elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#000000` | `--color-ink-black` | Primary text, navigation links, borders – commands attention against the light background. |
| Charcoal Gray | `#333333` | `--color-charcoal-gray` | Secondary text, subheadings, subtle borders – offers a softer contrast than Ink Black, ensuring readability without harshness. |
| Silver Thread | `#888888` | `--color-silver-thread` | Tertiary text, subtle separators, inactive states – provides a quiet presence for less critical information. |
| Ash Gray | `#979797` | `--color-ash-gray` | Placeholder text, light boundary lines – defines spaces without drawing excessive attention. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page and card backgrounds – provides a clean, expansive backdrop for all content. |
| Paper White | `#f4f4f4` | `--color-paper-white` | Section backgrounds, subtle containers – offers a slightly off-white texture to subtly differentiate content blocks. |
| Alabaster | `#e8e8e8` | `--color-alabaster` | Highlight backgrounds, hover states – provides minimal visual feedback while maintaining a clean aesthetic. |

## Tokens — Typography

### JHA Times Now — Used for editorial headlines and prominent display text. The ultra-light (100) weight for main headlines (56px) is a signature choice, conveying soft sophistication rather than loudness, almost like whispered luxury. Body text at 15px with generous line height (2.00) makes longer reads feel airy. · `--font-jha-times-now`
- **Substitute:** Playfair Display, Lora
- **Weights:** 100, 400
- **Sizes:** 15px, 20px, 56px
- **Line height:** 1.07, 1.20, 1.30, 2.00
- **Letter spacing:** -0.6, -0.24, -0.896
- **Role:** Used for editorial headlines and prominent display text. The ultra-light (100) weight for main headlines (56px) is a signature choice, conveying soft sophistication rather than loudness, almost like whispered luxury. Body text at 15px with generous line height (2.00) makes longer reads feel airy.

### Favorit SSENSE Inter — Small, functional text across the site. Used for navigation, metadata, and fine print, its compact size and clear readability ensure discreet information delivery without cluttering the primary visuals. · `--font-favorit-ssense-inter`
- **Substitute:** Inter, Arial
- **Weights:** 400
- **Sizes:** 11px
- **Line height:** 1.36
- **Role:** Small, functional text across the site. Used for navigation, metadata, and fine print, its compact size and clear readability ensure discreet information delivery without cluttering the primary visuals.

### Favorit SSENSE Inter1 — Versatile sans-serif for body content, subheadings, and larger product titles. Its various weights and tight letter-spacing create a crisp, modern feel, especially at larger sizes, contrasting the serif beautifully. The ultra-light (100) option at 95px is an impactful display choice for minimal branding. · `--font-favorit-ssense-inter1`
- **Substitute:** Inter, Arial
- **Weights:** 100, 400
- **Sizes:** 14px, 19px, 29px, 38px, 95px
- **Line height:** 0.99, 1.16, 1.19, 1.26, 1.37
- **Letter spacing:** -0.462, -0.627, -0.957, -1.408, -4.465
- **Role:** Versatile sans-serif for body content, subheadings, and larger product titles. Its various weights and tight letter-spacing create a crisp, modern feel, especially at larger sizes, contrasting the serif beautifully. The ultra-light (100) option at 95px is an impactful display choice for minimal branding.

### ssense-fonts — Likely used for custom icons or specific brand elements where exact glyph rendering is critical. The bold weight ensures clarity even at small sizes. · `--font-ssense-fonts`
- **Substitute:** Custom icon font (no direct substitute)
- **Weights:** 700
- **Sizes:** 11px
- **Line height:** 1.00
- **Role:** Likely used for custom icons or specific brand elements where exact glyph rendering is critical. The bold weight ensures clarity even at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.36 | — | `--text-caption` |
| body-sm | 14px | 1.37 | -0.462px | `--text-body-sm` |
| subheading | 19px | 1.19 | -0.627px | `--text-subheading` |
| heading | 29px | 1.26 | -0.957px | `--text-heading` |
| heading-lg | 38px | 1.16 | -1.408px | `--text-heading-lg` |
| display | 56px | 1.07 | -0.896px | `--text-display` |
| display-lg | 95px | 0.99 | -4.465px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 31 | 31px | `--spacing-31` |
| 40 | 40px | `--spacing-40` |
| 55 | 55px | `--spacing-55` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 105 | 105px | `--spacing-105` |
| 119 | 119px | `--spacing-119` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 10px |
| default | 0px |

### Layout

- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 10-30px

## Components

### Primary Navigation Link
**Role:** Top-level menu items

Uses 'Favorit SSENSE Inter', 11px, weight 400, Ink Black (#000000). Hover state likely changes color to Charcoal Gray or adds an underline, though no specific hover color was detected.

### Editorial Hero Title
**Role:** Main feature headline

Displays 'JHA Times Now', 56px, weight 100, Charcoal Gray (#333333), with a letter-spacing of -0.896px. This whisper-weight at large size is a core part of the brand's sophisticated visual identity.

### Editorial Hero Description
**Role:** Supporting text for hero section

Uses 'JHA Times Now', 20px, weight 400, Charcoal Gray (#333333), with a line-height of 1.20 and letter-spacing -0.24px. It supports the main title with elegant readability.

### View Editorial Button
**Role:** Call to action for editorial content

Text is 'Favorit SSENSE Inter', 14px, weight 400, Ink Black (#000000). It has a 1px border of Charcoal Gray (#333333) and padding of approximately 10px vertically and 20px horizontally. Background is Canvas White (#ffffff).

### Product Card
**Role:** Display for new arrivals or featured products

Predominantly an image with minimal text beneath. Text for 'Featured' uses 'Favorit SSENSE Inter', 11px, weight 400, Silver Thread (#888888). 'NEW ARRIVALS' uses 'Favorit SSENSE Inter', 14px, weight 400, Ink Black (#000000).

### Footer Link
**Role:** Navigation links in the footer

Uses 'Favorit SSENSE Inter', 11px, weight 400, Ink Black (#000000). Likely has no underline by default, appearing only on hover.

### Minimal Input Field
**Role:** Search or subscription form fields

Characterized by a simple 1px border in Ash Gray (#979797) and background of Canvas White (#ffffff). Text uses Charcoal Gray (#333333).

## Do's and Don'ts

### Do
- Always use a clear hierarchy of #000000 for primary text, #333333 for secondary text, and #888888 for tertiary text.
- Prioritize 'JHA Times Now' (100) at large sizes (56px) for main editorial headlines to achieve a soft, luxurious feel.
- Maintain generous vertical spacing between sections, opting for a minimum 'sectionGap' of 64px.
- Utilize '#f4f4f4' as a background for subtly differentiated content blocks, providing context without visual noise.
- Apply 'Favorit SSENSE Inter' at 11px/400 weight for all utility and metadata text to maintain a consistent discreetness.
- For CTA buttons, use a 1px border of #333333 and a Canvas White (#ffffff) background with Ink Black (#000000) text.
- Use tight letter-spacing for headlines and display text, particularly the negative values for 'Favorit SSENSE Inter1' at larger sizes, to ensure a compact, architectural look.

### Don't
- Avoid using bright or saturated colors; maintain the monochromatic palette with slight textural variations in grays and whites.
- Do not use heavy font weights (e.g., 600-700) for headlines; the ultra-light 'JHA Times Now 100' is preferred for high-impact text.
- Refrain from excessive border radii on elements; most components should be sharp-edged, with minimal rounding only where detected (e.g., 10px on specific links).
- Do not use drop shadows for elevation; rely on background color changes (#f4f4f4, #e8e8e8) or subtle borders to define layers.
- Avoid decorative elements or excessive UI chrome; the design should foreground content and photography.

## Imagery

The visual language is dominated by high-quality fashion photography and product shots. Photography is often full-bleed or large-format, meticulously composed, and typically features dark-haired models with expressive gazes or product shots on clean, reflective surfaces. Images carry significant weight, acting as anchors for editorial content or direct product showcases. There's a mix of candid, slightly gritty editorial photography for articles and polished, stylized studio photography for products. Icons are minimal, likely monochrome, used sparingly for navigation and UI elements. The role of imagery is primarily content-driven: showcasing fashion, presenting products, and setting an editorial mood, making the site image-heavy with photography often overlapping or being tightly gridded.

## Layout

The site employs a full-bleed page model with content often adhering to a flexible grid within wider sections. The hero pattern prominently features a large image paired with a display-sized headline and supporting text, typically in a split-screen or overlay arrangement. Section rhythm is often established through alternating content blocks, sometimes breaking into a multi-column grid for 'Recent' articles or product displays. Content arrangement typically follows a clear visual hierarchy, with large hero blocks yielding to smaller, gridded cards. The navigation includes a sticky top bar and secondary navigation that expands vertically. Density is comfortable, with generous white space around elements, allowing content (especially imagery) to breathe and command attention.

## Agent Prompt Guide

### Quick Color Reference
- **Primary Text:** #000000 (Ink Black)
- **Secondary Text:** #333333 (Charcoal Gray)
- **Background:** #ffffff (Canvas White)
- **Section Background:** #f4f4f4 (Paper White)
- **Borders/Dividers:** #979797 (Ash Gray)

### Example Component Prompts
1. **Create an editorial hero section:** Background is a full-width image. Title: 'JHA Times Now', 56px, weight 100, #333333, letter-spacing -0.896px. Subtitle: 'JHA Times Now', 20px, weight 400, #333333, line-height 1.20, letter-spacing -0.24px. CTA button: 'View Editorial' text, 'Favorit SSENSE Inter', 14px, weight 400, #000000, 1px border #333333, background #ffffff, 15px vertical padding, 20px horizontal padding.
2. **Design a 'Recent Article' card:** Image at the top. Below the image, left-aligned: 'Favorit SSENSE Inter', 11px, weight 400, #888888 for 'RECENT'. Below that, 'Favorit SSENSE Inter1', 19px, weight 400, #000000, line-height 1.19, letter-spacing -0.627px for article title. Bottom line: 'Favorit SSENSE Inter', 11px, weight 400, #888888 for category and date. Card padding 20px, background #ffffff.
3. **Generate a primary navigation menu item:** Text: 'Menswear' using 'Favorit SSENSE Inter', 11px, weight 400, #000000. Underline appears on hover programmatically.
4. **Create a footer link:** Text: 'English' using 'Favorit SSENSE Inter', 11px, weight 400, #000000. Margin right 31px from preceding link for horizontal spacing.
5. **Create a product listing title:** Text: 'NEW ARRIVALS' using 'Favorit SSENSE Inter', 14px, weight 400, #000000. Preceded by 'Featured' in 'Favorit SSENSE Inter', 11px, weight 400, #888888.

## Similar Brands

- **Farfetch** — Similar high-fashion e-commerce focus with a strong emphasis on editorial content and photography, alongside a minimal UI.
- **End.** — Features a clean, image-led product display and editorial style, relying on strong photography and restrained typography.
- **The Business of Fashion** — Shares a sophisticated editorial aesthetic, using a classic serif for headlines and a minimalist sans-serif for body to convey authority and elegance.
- **MatchesFashion** — Employs heavy use of large-format photography and a clean, luxury interface that prioritizes visual impact and product showcasing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #000000;
  --color-charcoal-gray: #333333;
  --color-silver-thread: #888888;
  --color-ash-gray: #979797;
  --color-canvas-white: #ffffff;
  --color-paper-white: #f4f4f4;
  --color-alabaster: #e8e8e8;

  /* Typography — Font Families */
  --font-jha-times-now: 'JHA Times Now', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-ssense-inter: 'Favorit SSENSE Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-ssense-inter1: 'Favorit SSENSE Inter1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ssense-fonts: 'ssense-fonts', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.36;
  --text-body-sm: 14px;
  --leading-body-sm: 1.37;
  --tracking-body-sm: -0.462px;
  --text-subheading: 19px;
  --leading-subheading: 1.19;
  --tracking-subheading: -0.627px;
  --text-heading: 29px;
  --leading-heading: 1.26;
  --tracking-heading: -0.957px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -1.408px;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.896px;
  --text-display-lg: 95px;
  --leading-display-lg: 0.99;
  --tracking-display-lg: -4.465px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-31: 31px;
  --spacing-40: 40px;
  --spacing-55: 55px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-105: 105px;
  --spacing-119: 119px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 10-30px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-small: 10px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #000000;
  --color-charcoal-gray: #333333;
  --color-silver-thread: #888888;
  --color-ash-gray: #979797;
  --color-canvas-white: #ffffff;
  --color-paper-white: #f4f4f4;
  --color-alabaster: #e8e8e8;

  /* Typography */
  --font-jha-times-now: 'JHA Times Now', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-ssense-inter: 'Favorit SSENSE Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-ssense-inter1: 'Favorit SSENSE Inter1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ssense-fonts: 'ssense-fonts', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.36;
  --text-body-sm: 14px;
  --leading-body-sm: 1.37;
  --tracking-body-sm: -0.462px;
  --text-subheading: 19px;
  --leading-subheading: 1.19;
  --tracking-subheading: -0.627px;
  --text-heading: 29px;
  --leading-heading: 1.26;
  --tracking-heading: -0.957px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -1.408px;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.896px;
  --text-display-lg: 95px;
  --leading-display-lg: 0.99;
  --tracking-display-lg: -4.465px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-31: 31px;
  --spacing-40: 40px;
  --spacing-55: 55px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-105: 105px;
  --spacing-119: 119px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 10px;
}
```
