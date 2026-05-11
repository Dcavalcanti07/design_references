# Redis Agency — Style Reference
> Dramatic Midnight Sculpture

**Theme:** dark

Redis Agency employs a dramatic, high-contrast dark-mode aesthetic, creating a sense of luxury and seriousness. It pairs large, elegant serif headlines with a compact sans-serif for body text, establishing clear typographic hierarchy. The overall feel is spacious, with generous negative space and minimal, highly rounded components that appear almost sculptural against the black canvas. Color is strictly controlled, centered around a stark black and white palette, accented only by brand-specific imagery or internal details that appear as subtle splashes of vibrancy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `#000000` | `--color-midnight-canvas` | Page backgrounds, large content blocks, foundational surfaces |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, button backgrounds, outline borders, prominent UI elements that demand attention against the dark canvas |
| Slate Text | `#808080` | `--color-slate-text` | Muted body text, secondary information, and borders for subtle segmentation. Provides softer contrast than pure white |
| Dark Stone | `#333333` | `--color-dark-stone` | Fine borders and subtle dividers, offering a very low-contrast separation on dark backgrounds |

## Tokens — Typography

### Times New Roman — Hero headlines and major section titles. Its classic serif form and extremely tight tracking (subtly inverting common design rules) convey gravitas and exclusivity. · `--font-times-new-roman`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 32px, 90px
- **Line height:** 0.82, 1.05
- **Letter spacing:** -1.0em at 90px, -1.0em at 32px
- **Role:** Hero headlines and major section titles. Its classic serif form and extremely tight tracking (subtly inverting common design rules) convey gravitas and exclusivity.

### Suisseintl WebM — Body text, links, buttons, and general UI elements. Its compact, neutral sans-serif form ensures readability and efficiency across smaller text blocks, balancing the expressive headlines. · `--font-suisseintl-webm`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px, 24px, 36px, 38px
- **Line height:** 1.16, 1.20, 1.40
- **Letter spacing:** -0.8em
- **Role:** Body text, links, buttons, and general UI elements. Its compact, neutral sans-serif form ensures readability and efficiency across smaller text blocks, balancing the expressive headlines.

### Editorialnew — Occasional decorative or delicate text elements, its light weight suggesting an editorial, refined touch. · `--font-editorialnew`
- **Substitute:** Georgia
- **Weights:** 100
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Occasional decorative or delicate text elements, its light weight suggesting an editorial, refined touch.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | -0.8px | `--text-caption` |
| body | 16px | 1.4 | -0.8px | `--text-body` |
| subheading | 24px | 1.2 | -0.8px | `--text-subheading` |
| heading | 32px | 1.05 | -1px | `--text-heading` |
| heading-lg | 38px | 1.16 | -0.8px | `--text-heading-lg` |
| display | 90px | 0.82 | -1px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 25 | 25px | `--spacing-25` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 70 | 70px | `--spacing-70` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 24px |
| buttons | 40px |
| default | 44px |

### Layout

- **Section gap:** 70px
- **Card padding:** 25px
- **Element gap:** 22px

## Components

### Filled Primary Button
**Role:** Action button

Ghost White fill, Midnight Canvas text, 40px border-radius, padding of 25px horizontal and 7-9px vertical. Suisseintl WebM font, weight 400.

### Ghost Outline Link
**Role:** Navigation or secondary action link

Midnight Canvas background, Ghost White text, 1px Ghost White border, 24px border-radius. Padding based on content. No distinct hover background change, only text color to white if originally a softer grey.

### Zero-Padding Card
**Role:** Content card/container for case studies

Transparent background, 0px border-radius, no box shadow, 0px padding. Acts as a container for full-bleed content rather than a distinct card surface.

## Do's and Don'ts

### Do
- Prioritize Midnight Canvas (#000000) for all page and section backgrounds to maintain dramatic contrast.
- Use Times New Roman (400) with tight letter-spacing for headlines and Ghost White (#ffffff) for maximum impact.
- Employ Suisseintl WebM (400) for all body text, links, and buttons, using Ghost White (#ffffff) for primary text and Slate Text (#808080) for secondary details.
- Apply a 40px border-radius to all interactive elements like buttons to achieve a soft, rounded aesthetic.
- Maintain generous vertical spacing between sections, using the 70px sectionGap token.
- Utilize 1px Ghost White (#ffffff) borders for subtle delineation of content blocks or interactive elements.
- Ensure all primary call-to-action buttons use a Ghost White (#ffffff) background with Midnight Canvas (#000000) text for high visibility.

### Don't
- Avoid using highly saturated colors for backgrounds or large sections; reserve them strictly for imagery or small accents.
- Do not deviate from the specified font families; avoid system defaults or other decorative fonts.
- Never use hard-edged, 0px border-radius on interactive elements; always lean into the soft, rounded forms.
- Do not introduce shadows for elevation, as the design relies on stark color contrast and negative space for hierarchy.
- Avoid dense information blocks; maintain the spacious and minimalist approach.
- Do not apply excessive letter-spacing to Suisseintl WebM; maintain its compact character with -0.8em tracking.
- Do not use Slate Text (#808080) for primary headlines or critical information where maximum contrast is required.

## Imagery

The site uses a mix of highly stylized and abstract 3D renders (e.g., green organic blobs) and product-focused photography that often features single objects like radishes. Graphics are decorative and atmospheric, adding a sense of organic fluidity and surrealism against the stark UI. Iconography is minimalist, likely outlined or mono-colored, serving functional rather than decorative roles. Imagery is used to create mood and brand identity rather than explanatory content, often full-bleed or large-scale, dominating certain sections to create visual drama.

## Layout

The page primarily uses a full-bleed layout on a Midnight Canvas background, featuring large, dramatic sections. The hero section displays a centered headline with hero imagery. Content sections alternate between visually dominant imagery and text blocks, often with a centered stack approach for headlines and body text. There is a strong emphasis on spaciousness, with ample negative space defining the rhythm between content blocks. Navigation appears to be minimal, likely a top bar and potentially a hamburger menu for mobile, designed to recede and let the content shine.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #ffffff
accent: no distinct accent color
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a hero section: Midnight Canvas background. Headline at 90px Times New Roman weight 400, Ghost White, letter-spacing -1.0px. Subtext at 18px Suisseintl WebM weight 400, Slate Text, letter-spacing -0.8px, centered.
2. Create a Primary Action Button: #ffffff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a secondary text link: Ghost White text at 16px Suisseintl WebM weight 400, letter-spacing -0.8px. On hover, text color remains Ghost White. No background or border. Default underline on hover.

## Similar Brands

- **Awwwards sites** — Dramatic high-contrast themes, large experimental typography, and evocative 3D/abstract imagery.
- **Future Fonts** — Focus on bespoke, expressive typography as a core design element, especially large serif headlines on dark backgrounds.
- **Active Theory** — Use of abstract, organic 3D elements for atmospheric branding against dark backgrounds.
- **B&R Design** — High-contrast dark-mode design with a sophisticated, minimalist approach and limited color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-ghost-white: #ffffff;
  --color-slate-text: #808080;
  --color-dark-stone: #333333;

  /* Typography — Font Families */
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl-webm: 'Suisseintl WebM', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorialnew: 'Editorialnew', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.8px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.8px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.8px;
  --text-heading: 32px;
  --leading-heading: 1.05;
  --tracking-heading: -1px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.8px;
  --text-display: 90px;
  --leading-display: 0.82;
  --tracking-display: -1px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-25: 25px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-70: 70px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 70px;
  --card-padding: 25px;
  --element-gap: 22px;

  /* Border Radius */
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 44.0001px;

  /* Named Radii */
  --radius-links: 24px;
  --radius-buttons: 40px;
  --radius-default: 44px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-ghost-white: #ffffff;
  --color-slate-text: #808080;
  --color-dark-stone: #333333;

  /* Typography */
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl-webm: 'Suisseintl WebM', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorialnew: 'Editorialnew', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.8px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.8px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.8px;
  --text-heading: 32px;
  --leading-heading: 1.05;
  --tracking-heading: -1px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.8px;
  --text-display: 90px;
  --leading-display: 0.82;
  --tracking-display: -1px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-25: 25px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-70: 70px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 44.0001px;
}
```
