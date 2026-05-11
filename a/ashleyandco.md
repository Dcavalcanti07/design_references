# Ashleyandco — Style Reference
> Warm gray minimalism on unbleached paper.

**Theme:** light

Ashleyandco presents a serene and understated aesthetic, rooted in subtle monochromatic branding. The interface uses generous white space and clean typography, establishing an atmosphere of calm and elegance. Components are defined by their soft ghost states and minimal borders, often blending seamlessly into surfaces, with primary actions expressed through subtle fill and text color shifts. The overall impression is one of quiet luxury, allowing content to take precedence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#f6f3f0` | `--color-canvas` | Page backgrounds, large content sections, subtle background wash for hero areas |
| Ink | `#3c3c3c` | `--color-ink` | Primary text, strong borders, key structural icons, active navigation links. This deep charcoal provides contrast without harshness |
| Onyx | `#000000` | `--color-onyx` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Mist | `#dedfdb` | `--color-mist` | Fine dividers, subtle borders for cards and inputs, delineating sections with minimal visual weight |
| Porcelain | `#ffffff` | `--color-porcelain` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Ash | `#434343` | `--color-ash` | Background for primary buttons, creating a muted call to action against lighter surfaces |
| Stone | `#939393` | `--color-stone` | Muted secondary text, inactive links, subtle helper text, and secondary borders |

## Tokens — Typography

### Neue Haas Grotesk Text — Primary UI font, used for body text, navigation, buttons, and most interactive elements. Its neutral character supports the understated aesthetic. Weights 400 and 500 maintain a clear hierarchy. · `--font-neue-haas-grotesk-text`
- **Substitute:** Helvetica Neue, Arial
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 18px, 24px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.0050em at 24px and 18px, 0.0230em at 12px and 11px
- **Role:** Primary UI font, used for body text, navigation, buttons, and most interactive elements. Its neutral character supports the understated aesthetic. Weights 400 and 500 maintain a clear hierarchy.

### Martina Plant — Decorative display font for headlines and evocative marketing copy. Its distinct character adds a touch of classic sophistication to key textual elements. · `--font-martina-plant`
- **Weights:** 400, 500
- **Sizes:** 20px, 24px, 42px
- **Line height:** 0.72, 1.10
- **Letter spacing:** -0.0050em at 42px and 24px, 0.0140em at 20px
- **Role:** Decorative display font for headlines and evocative marketing copy. Its distinct character adds a touch of classic sophistication to key textual elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.1 | 0.253px | `--text-caption` |
| body | 18px | 1.1 | -0.09px | `--text-body` |
| subheading | 20px | 1.1 | 0.28px | `--text-subheading` |
| heading | 24px | 1.1 | -0.12px | `--text-heading` |
| display | 42px | 0.72 | -0.21px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 10px |

### Layout

- **Section gap:** 80px
- **Card padding:** 20px
- **Element gap:** 15px

## Components

### Ghost Button - Light Text
**Role:** Default interactive element, often for secondary actions or navigation.

Transparent background, #000000 text color, #000000 border color, 0px border-radius, 0px padding. Uses Neue Haas Grotesk Text 400.

### Ghost Button - Muted Text
**Role:** Subtle interactive elements, often found in footers or less prominent areas.

Transparent background, #3c3c3c text color, #3c3c3c border color, 0px border-radius, 0px padding. Uses Neue Haas Grotesk Text 400.

### Ghost Button - Hero White Text
**Role:** Interactive elements against dark or image backgrounds.

Transparent background, #ffffff text color, #ffffff border color, 0px border-radius, 0px padding. Uses Neue Haas Grotesk Text 400.

### Primary Filled Button
**Role:** Key call-to-action button for initiating primary actions.

#434343 background, #f6f3f0 text color, #434343 border color, 0px border-radius. Padding 8px vertical, 20px horizontal. Uses Neue Haas Grotesk Text 400.

### Untouched Card/Media Holder
**Role:** Container for images, product listings, or informational content.

Transparent background, no specific shadow, 0px border-radius, 0px padding. Content within defines its presentation.

### Modal Overlay Card
**Role:** Dialogs and pop-ups that require a distinct surface.

Solid #f6f3f0 background, 10px general border-radius. Padding for internal content is often dynamically defined.

## Do's and Don'ts

### Do
- Prioritize Neue Haas Grotesk Text 400 for all body copy and most UI elements, reserving Martina Plant for headlines to maintain visual hierarchy.
- Use #f6f3f0 (Canvas) as the primary background color for most page sections, ensuring a consistent light aesthetic.
- Employ #3c3c3c (Ink) for primary text and strong outline borders to define interactive areas without heavy fills.
- Define interactive states with subtle border changes using #000000 (Onyx) for active ghost buttons.
- Apply 0px border-radius to most buttons and interactive elements for a crisp, rectangular aesthetic.
- Maintain a clear visual hierarchy by utilizing the 80px section gap for content block separation.
- Use #434343 (Ash) for primary button backgrounds with #f6f3f0 (Canvas) text, creating a soft but distinct call to action.

### Don't
- Avoid using highly saturated or vibrant colors; stick to the established achromatic and muted palette.
- Do not introduce significant box-shadows or elevation effects; the design relies on flat surfaces and subtle borders.
- Do not use generic system fonts; always specify Neue Haas Grotesk Text or Martina Plant.
- Avoid unnecessary decorative elements or heavy gradients; minimalism is key to the brand's identity.
- Do not deviate from the general 0px border-radius for interactive components unless a specific, subtle 10px radius is explicitly required for a card or modal.
- Do not vary line-height significantly from the type scale values; maintain the controlled density.
- Avoid aggressive letter-spacing for body text; apply tracking judiciously as specified by the type profiles.

## Imagery

This site predominantly uses clean, product-focused photography and minimal graphic elements. Photography features tightly cropped products on soft, often desaturated backgrounds, with occasional lifestyle shots that maintain a muted, high-key aesthetic. Images are typically contained within rectangular frames, with sharp edges and no overlap. Icons are minimal, outlined, and monochromatic, with a fine stroke weight. The imagery serves to showcase products and create an atmospheric, curated feel rather than providing dense informational content.

## Layout

The page layout utilizes a contained maximum width for primary content, centered on a light canvas. The hero section often features full-bleed atmospheric photography with text overlaid, immediately establishing a refined tone. Sections are demarcated by consistent vertical spacing (80px), creating a comfortable rhythm. Content typically alternates between text-dominant blocks, two-column text-and-image arrangements, and multi-column product grids. Navigation is a top-bar sticky header, minimal and unobtrusive. The density is spacious, providing ample breathing room around elements.

## Agent Prompt Guide

**Quick Color Reference:**
text: #3c3c3c
background: #f6f3f0
border: #dedfdb
accent: no distinct accent color
primary action: no distinct CTA color

**3-5 Example Component Prompts:**
1. Create a modal header: "Wrong Store Detected" in Neue Haas Grotesk Text 500, 18px, #000000. "CLOSE" in Neue Haas Grotesk Text 400, 12px, #000000, 0px padding. Place these in a #f6f3f0 container with 10px radius.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
3. Implement a muted ghost link: "STAY ON CURRENT STORE" with #3c3c3c text color, Neue Haas Grotesk Text 400, 18px. Ensure there is no background or border, following the ghost button style. 
4. Create a page section with a heading "Shop" in Martina Plant 400, 42px, #000000, letter-spacing -0.21px. Below it, body copy "Browse our complete collection..." in Neue Haas Grotesk Text 400, 18px, #3c3c3c. Set the section background to #f6f3f0, with an 80px top and bottom padding.

## Similar Brands

- **Aesop** — Shares a similar minimal, monochromatic aesthetic with a focus on product photography and elegant typography.
- **Frama** — Exhibits analogous use of understated color palettes, high-quality product imagery, and classic serif/sans-serif typography pairing.
- **Byredo** — Features a comparable sense of luxury and calm, achieved through clean layouts, subtle color use, and sophisticated typography.
- **Jenni Kayne** — Employs an elevated, minimalist approach to e-commerce, using abundant white space and natural, soft tones.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #f6f3f0;
  --color-ink: #3c3c3c;
  --color-onyx: #000000;
  --color-mist: #dedfdb;
  --color-porcelain: #ffffff;
  --color-ash: #434343;
  --color-stone: #939393;

  /* Typography — Font Families */
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martina-plant: 'Martina Plant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.1;
  --tracking-caption: 0.253px;
  --text-body: 18px;
  --leading-body: 1.1;
  --tracking-body: -0.09px;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.28px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.12px;
  --text-display: 42px;
  --leading-display: 0.72;
  --tracking-display: -0.21px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 20px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-default: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #f6f3f0;
  --color-ink: #3c3c3c;
  --color-onyx: #000000;
  --color-mist: #dedfdb;
  --color-porcelain: #ffffff;
  --color-ash: #434343;
  --color-stone: #939393;

  /* Typography */
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martina-plant: 'Martina Plant', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.1;
  --tracking-caption: 0.253px;
  --text-body: 18px;
  --leading-body: 1.1;
  --tracking-body: -0.09px;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.28px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.12px;
  --text-display: 42px;
  --leading-display: 0.72;
  --tracking-display: -0.21px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 10px;
}
```
