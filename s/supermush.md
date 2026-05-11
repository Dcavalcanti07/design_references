# SuperMush — Style Reference
> Juicy electric canvas

**Theme:** light

SuperMush employs a vibrant, energetic visual system akin to a modern wellness brand. It layers a crisp white canvas with a bright, electric blue for primary actions and a playful, warm orange for highlighting key information. Typography is direct and confident, favoring sans-serifs with ample letter spacing and line height for readability. Components are lightweight with subtly rounded corners, emphasizing content and a clean user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, input fields, navigation elements |
| Off White Clay | `#f5f4f1` | `--color-off-white-clay` | Secondary surface background, subtle section dividers |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, core iconography, strong borders, footer background |
| Graphite | `#707170` | `--color-graphite` | Muted text, placeholder text in input fields, supporting detail |
| Steel Gray | `#eeeeee` | `--color-steel-gray` | Subtle borders, light dividers, background for disabled states |
| Accent Blue | `#2f59f8` | `--color-accent-blue` | Primary action buttons, interactive elements, significant iconography – brings energy and focus |
| Highlight Orange | `#ff632a` | `--color-highlight-orange` | Promotional banners, decorative elements, accents for key information, secondary content borders |
| Active Yellow | `#eaff00` | `--color-active-yellow` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |

## Tokens — Typography

### Founders Grotesk — Primary headings, body text, navigation elements, input labels – delivers a clean, confident, and highly readable voice across the interface. · `--font-founders-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 17px, 18px, 20px, 32px, 34px, 36px, 40px, 43px, 48px
- **Line height:** 1.00, 1.04, 1.15, 1.17, 1.21, 1.25, 1.40, 1.50, 1.60, 1.67
- **Letter spacing:** normal
- **Role:** Primary headings, body text, navigation elements, input labels – delivers a clean, confident, and highly readable voice across the interface.

### GT Planar — Secondary text, descriptive elements, button text, and certain navigation links – offers a complementary, slightly more technical feel. · `--font-gt-planar`
- **Substitute:** Montserrat
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 11px, 13px, 14px, 16px, 18px, 20px
- **Line height:** 1.00, 1.15, 1.25, 1.29, 1.60
- **Letter spacing:** normal
- **Role:** Secondary text, descriptive elements, button text, and certain navigation links – offers a complementary, slightly more technical feel.

### Font Awesome 5 Pro — Font Awesome 5 Pro — detected in extracted data but not described by AI · `--font-font-awesome-5-pro`
- **Weights:** 300
- **Sizes:** 18px
- **Line height:** 1
- **Role:** Font Awesome 5 Pro — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.6 | — | `--text-caption` |
| body | 14px | 1.25 | — | `--text-body` |
| body-lg | 17px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.21 | — | `--text-subheading` |
| heading | 32px | 1.4 | — | `--text-heading` |
| heading-lg | 36px | 1.15 | — | `--text-heading-lg` |
| display | 48px | 1 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 1.67772e+07px |
| buttons | 50px |
| general | 4px |
| imagery | 8px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Calls to action, form submissions.

Background: Accent Blue (#2f59f8). Text: Canvas White (#ffffff). Fully rounded corners (50px radius). Padding: 10px vertical, 20px horizontal. Font: GT Planar, weight 500.

### Ghost Button (Header Nav)
**Role:** Secondary navigation in header.

Background: transparent. Text: Midnight Ink (#000000). No explicit border radius. Padding: 0px. Font: Founders Grotesk.

### Pill Accent Button
**Role:** Information tags, small labels, sale indicators.

Background: Active Yellow (#eaff00) or Highlight Orange (#ff632a). Text: Midnight Ink (#000000). Fully rounded (50px radius). Padding: 4px vertical, 8px horizontal (inferred small item padding). Font: GT Planar.

### Neutral Rounded Button
**Role:** Quantity selectors, small interactive elements.

Background: #d9d9d9. Text: Midnight Ink (#000000). Fully rounded (50% radius). No explicit padding observed.

### Product Card
**Role:** Displaying product items in grids.

Background: transparent. Border: none. Border-radius: 0px. Internal padding: 0. Some cards may have a subtle transparent background rgba(0, 0, 0, 0.1) and 16px border-radius, with 48px vertical and 16px horizontal internal padding.

### Subtle Elevated Card
**Role:** For reviews or distinct content blocks.

Background: Canvas White (#ffffff). Border-radius: 16px. Padding: 48px vertical, 16px horizontal. No box shadow.

### Pill Input Field
**Role:** Text input forms.

Background: Canvas White (#ffffff). Text color: Graphite (#707170). Border: 1px solid Steel Gray (#eeeeee). Fully rounded corners (1.67772e+07px radius). Padding: 12px vertical, 16px left, 32px right.

## Do's and Don'ts

### Do
- Use Accent Blue (#2f59f8) for all primary calls to action, ensuring a fully rounded 'pill' shape with 50px border-radius and Canvas White (#ffffff) text.
- Apply Highlight Orange (#ff632a) sparingly for promotional banners, secondary content borders, and decorative accents to draw attention.
- Structure primary content on Canvas White (#ffffff) backgrounds, using Off White Clay (#f5f4f1) or transparent backgrounds for secondary sections or cards to create subtle visual breaks.
- Ensure all body text uses Founders Grotesk at appropriate weights, with Midnight Ink (#000000) for primary content and Graphite (#707170) for muted or helper text.
- Utilize a 16px border-radius for all content cards that require a defined surface, maintaining a light background.
- Maintain comfortable spacing with a base unit of 4px. Use 8px as the default element gap and 16px for card padding.
- Highlight sale or special offers with a distinctly bright Active Yellow (#eaff00) background, paired with Midnight Ink (#000000) text and a pill shape.

### Don't
- Do not use dark backgrounds for general page sections; the theme is predominantly light and airy.
- Avoid arbitrary uses of color; Limit saturated colors (Highlight Orange, Accent Blue, Active Yellow) to functional or branding purposes.
- Do not introduce square corners for buttons or interactive elements; prioritize soft, rounded edges (50px or greater radius).
- Do not use complex drop shadows or elevation effects; elements should generally appear flat or with minimal, subtle elevation.
- Avoid using multiple font families beyond Founders Grotesk and GT Planar to maintain brand consistency.
- Do not decrease letter-spacing below 'normal'; the brand maintains an open and readable typographic feel.
- Avoid padding less than 10px on interactive elements to ensure adequate tap/click targets.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background, primary content sections, elevated cards. |
| 2 | Off White Clay | `#f5f4f1` | Secondary background for sections, subtle distinction between content blocks. |

## Imagery

Photography is dominant, featuring lifestyle shots of people using products in active, natural settings (beaches, outdoors) alongside clean, focused product photography. Treatments are largely unedited and natural-looking, showing vibrant colors and real-world contexts. Product shots are typically contained within cards with 8px radius. Icons are monochrome, often using a thin stroke, mainly for utility and navigation, appearing as simple outlines or filled shapes depending on context. Imagery serves both decorative atmosphere and product showcase, usually occupying significant visual space.

## Layout

The page adheres to a max-width contained layout generally centered, though specific section widths can vary to accommodate full-bleed image backgrounds. The hero section often features a full-bleed vibrant image with centered, overlaid text and calls to action. Sections maintain a consistent vertical rhythm, with content arranged in alternating text-left/image-right or centered stacks. Card grids are used for product displays with typically 4 columns. Navigation is a sticky top bar with a distinct brand logo and minimal links, complemented by the prominent Accent Blue 'Shop All' button.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #eeeeee
accent: #ff632a
primary action: #2f59f8 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #2f59f8 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a review card: use Subtle Elevated Card style, with review text in Founders Grotesk weight 400 at 14px, color Midnight Ink (#000000). Reviewer name in GT Planar weight 500 at 12px, color Graphite (#707170).

## Similar Brands

- **Oura Ring** — Uses a similar natural photography style with an emphasis on health and wellness, and a clean, spacious UI.
- **Athletic Greens (AG1)** — Features a light, clean interface with product-focused imagery and subtle use of accent colors to highlight benefits.
- **Huel** — Combines lifestyle photography with a clear, direct typographic approach and functional color accents on product pages.
- **Ritual** — Utilizes a clean white background, vibrant product imagery, and a restrained color palette for calls to action.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-off-white-clay: #f5f4f1;
  --color-midnight-ink: #000000;
  --color-graphite: #707170;
  --color-steel-gray: #eeeeee;
  --color-accent-blue: #2f59f8;
  --color-highlight-orange: #ff632a;
  --color-active-yellow: #eaff00;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-planar: 'GT Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-5-pro: 'Font Awesome 5 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.21;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 1.67772e+07px;
  --radius-buttons: 50px;
  --radius-general: 4px;
  --radius-imagery: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-off-white-clay: #f5f4f1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-off-white-clay: #f5f4f1;
  --color-midnight-ink: #000000;
  --color-graphite: #707170;
  --color-steel-gray: #eeeeee;
  --color-accent-blue: #2f59f8;
  --color-highlight-orange: #ff632a;
  --color-active-yellow: #eaff00;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-planar: 'GT Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-5-pro: 'Font Awesome 5 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.21;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;
}
```
