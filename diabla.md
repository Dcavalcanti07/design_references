# Diabla — Style Reference
> Tropical Modernism Pop

**Theme:** light

Diabla's visual system evokes a playful, modern aesthetic set against a backdrop of sun-drenched outdoor living. The design is characterized by crisp white and a soft pastel pink canvas, punctuated by a vibrant, almost neon red accent for crucial interactions and branding. Typography is elegant and airy, maintaining a degree of formality even amidst the relaxed, resort-like imagery. Components are lightweight with defined outlines, contributing to an open, spacious feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Coral Kiss | `#ed2e38` | `--color-coral-kiss` | Brand accent, outline buttons, active links, functional icons — a vivid pop against the muted palette |
| Carbon | `#333333` | `--color-carbon` | Primary body text, dark borders, general UI text |
| Deep Ink | `#000000` | `--color-deep-ink` | Headlines, strong text emphasis, button borders with a bold presence |
| Shell Pink | `#fcf0f3` | `--color-shell-pink` | Page backgrounds, card surfaces, subtle input backgrounds — provides a soft, warm canvas |
| Pure White | `#ffffff` | `--color-pure-white` | Alternative input backgrounds, card surfaces |
| Rosy Clouds | `#F9C2CC` | `--color-rosy-clouds` | Secondary accent for decorative elements, soft blocks |

## Tokens — Typography

### Linotype Helvetica Neue LT Std Roman — Body text, links, smaller headings, UI labels — provides a clean, neutral voice for information. · `--font-linotype-helvetica-neue-lt-std-roman`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 22px, 33px
- **Line height:** 1.00, 1.09, 1.13, 1.20, 1.22, 1.29, 1.30, 1.43, 1.50, 1.80, 2.00, 2.33, 2.80
- **Letter spacing:** normal
- **Role:** Body text, links, smaller headings, UI labels — provides a clean, neutral voice for information.

### Linotype Helvetica Neue LT Std Lt — Large display headlines — thin weight at massive sizes creates an airy, modern, almost whispered statement. · `--font-linotype-helvetica-neue-lt-std-lt`
- **Substitute:** Helvetica Neue Light
- **Weights:** 400
- **Sizes:** 80px, 110px
- **Line height:** 0.88, 0.91
- **Letter spacing:** normal
- **Role:** Large display headlines — thin weight at massive sizes creates an airy, modern, almost whispered statement.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | — | `--text-caption` |
| body | 14px | 1.22 | — | `--text-body` |
| body-lg | 18px | 1.2 | — | `--text-body-lg` |
| heading-sm | 22px | 1.13 | — | `--text-heading-sm` |
| heading | 33px | 1.09 | — | `--text-heading` |
| heading-lg | 80px | 0.91 | — | `--text-heading-lg` |
| display | 110px | 0.88 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 14px |
| inputs | 0px |
| buttons | 14px |

### Layout

- **Section gap:** 80px
- **Card padding:** 25px
- **Element gap:** 10px

## Components

### Outlined Button - Coral Kiss
**Role:** Primary action button, often paired with an icon.

Text: Coral Kiss (#ed2e38), Linotype Helvetica Neue LT Std Roman, weight 400. Background: transparent. Border: 1px solid Coral Kiss (#ed2e38). Padding: 0px vertical, 20px horizontal. Border radius: 14px.

### Outlined Button - Deep Ink
**Role:** Secondary action or ghost button.

Text: Deep Ink (#000000), Linotype Helvetica Neue LT Std Roman, weight 400. Background: transparent. Border: 1px solid Deep Ink (#000000). Padding: 0px vertical, 0px horizontal. Border radius: 0px.

### Input - Underlined Coral Kiss
**Role:** Text input field with focus.

Text: Coral Kiss (#ed2e38). Background: transparent. Border: 1px solid Coral Kiss (#ed2e38) on bottom, otherwise transparent. Border-radius: 0px.

### Input - Shell Pink Background Circle
**Role:** Small input or selection with a circular, soft background.

Text: Coral Kiss (#ed2e38). Background: Shell Pink (#fcf0f3). Border: 1px solid Coral Kiss (#ed2e38). Border-radius: 50% (circular). Padding: 0px.

## Do's and Don'ts

### Do
- Always use Coral Kiss (#ed2e38) as the primary brand accent for interactive elements and highlights.
- Maintain a clear visual hierarchy by limiting large headlines to Linotype Helvetica Neue LT Std Lt at sizes 80px or 110px.
- Apply Shell Pink (#fcf0f3) for ambient backgrounds and card surfaces to establish the site's warm, light base.
- Utilize a 14px border radius for interactive elements like buttons and links to create a consistent soft, rounded treatment.
- Employ consistent 0px vertical padding with 20px horizontal padding for primary outlined buttons to create a flat, elongated look.
- Break up page content with alternating sections using Shell Pink (#fcf0f3) and Pure White (#ffffff) backgrounds.
- Use Linotype Helvetica Neue LT Std Roman (400) for all body text, links, and minor headings with normal letter spacing.

### Don't
- Avoid using multiple chromatic colors; Coral Kiss (#ed2e38) should be the singular vibrant accent.
- Do not use heavy shadows or significant elevation; maintain a flat, open aesthetic.
- Refrain from using solid fill buttons; the primary action style is an outlined button with Coral Kiss (#ed2e38).
- Never deviate from the specified font families or their intended roles and weights.
- Do not introduce complex gradient fills; the system relies on solid colors and subtle background variations.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Shell Pink Canvas | `#fcf0f3` | Primary page background, base for most content blocks. |
| 2 | Pure White Panel | `#ffffff` | Elevated card backgrounds, alternative input fields. |

## Imagery

Diabla features high-quality, aspirational photography and 3D renders of their furniture in lush, tropical or Mediterranean outdoor settings. The visuals are clean and focus on product integration within an idealized lifestyle. Photography is generally high-key, with natural lighting and vibrant but soft colors that blend with the brand's playful aesthetic. Imagery often serves as a full-bleed hero or contained rectangles, seamlessly integrated with text. Icons are minimal, outlined, and used descriptively for navigation and small functional elements.

## Layout

The page primarily uses a full-bleed layout for hero sections, filling the viewport with striking imagery and large text overlays. Subsequent sections follow a max-width contained pattern, with content centered. Section rhythm is established through consistent vertical spacing around 80px, creating a comfortable density. Content often alternates between text-dominant blocks and imagery or product showcases, following a flexible grid for features and product displays. The overall structure is open and breathable, avoiding dense information blocks.

## Agent Prompt Guide

Quick Color Reference: 
- text: #333333
- background: #fcf0f3
- border: #ed2e38
- accent: #ed2e38
- primary action: #ed2e38 (outlined action border)

Example Component Prompts:
- Create a hero overlay with the title 'SALONE DEL MOBILE': text Linotype Helvetica Neue LT Std Lt, weight 400, size 110px, line-height 0.88, color Pure White (#ffffff).
- Make an 'EXPLORE' button for navigation: text Coral Kiss (#ed2e38), Linotype Helvetica Neue LT Std Roman, weight 400. Background transparent, 1px solid Coral Kiss (#ed2e38) border. 14px border-radius, with 0px vertical and 20px horizontal padding.
- Design a text block with a subheading 'FOUR SEASONS': subheading text Coral Kiss (#ed2e38), Linotype Helvetica Neue LT Std Roman, weight 400, size 33px. Body text Carbon (#333333), Linotype Helvetica Neue LT Std Roman, weight 400, size 14px, line height 1.22.
- Produce an input field for a newsletter signup: Text Coral Kiss (#ed2e38), Linotype Helvetica Neue LT Std Roman, weight 400, size 14px. Background Shell Pink (#fcf0f3). No borders, 50% border radius for a circular shape. 5px vertical padding and 5px right margin.

## Similar Brands

- **Kettal** — Luxury outdoor furniture brands with a focus on clean lines, high-quality photography, and minimalist UI.
- **Ferm Living** — Modern design aesthetic, often using soft color palettes and emphasis on interior/exterior lifestyle imagery.
- **Hay Design** — Focus on playful modern design, often incorporates bright, unexpected accent colors against a neutral backdrop.
- **Muuto** — Contemporary Scandinavian design language, blending natural elements with modern forms and vibrant accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-coral-kiss: #ed2e38;
  --color-carbon: #333333;
  --color-deep-ink: #000000;
  --color-shell-pink: #fcf0f3;
  --color-pure-white: #ffffff;
  --color-rosy-clouds: #F9C2CC;

  /* Typography — Font Families */
  --font-linotype-helvetica-neue-lt-std-roman: 'Linotype Helvetica Neue LT Std Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linotype-helvetica-neue-lt-std-lt: 'Linotype Helvetica Neue LT Std Lt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.22;
  --text-body-lg: 18px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.13;
  --text-heading: 33px;
  --leading-heading: 1.09;
  --text-heading-lg: 80px;
  --leading-heading-lg: 0.91;
  --text-display: 110px;
  --leading-display: 0.88;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 25px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-xl: 14px;

  /* Named Radii */
  --radius-links: 14px;
  --radius-inputs: 0px;
  --radius-buttons: 14px;

  /* Surfaces */
  --surface-shell-pink-canvas: #fcf0f3;
  --surface-pure-white-panel: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-coral-kiss: #ed2e38;
  --color-carbon: #333333;
  --color-deep-ink: #000000;
  --color-shell-pink: #fcf0f3;
  --color-pure-white: #ffffff;
  --color-rosy-clouds: #F9C2CC;

  /* Typography */
  --font-linotype-helvetica-neue-lt-std-roman: 'Linotype Helvetica Neue LT Std Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linotype-helvetica-neue-lt-std-lt: 'Linotype Helvetica Neue LT Std Lt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.22;
  --text-body-lg: 18px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.13;
  --text-heading: 33px;
  --leading-heading: 1.09;
  --text-heading-lg: 80px;
  --leading-heading-lg: 0.91;
  --text-display: 110px;
  --leading-display: 0.88;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-xl: 14px;
}
```
