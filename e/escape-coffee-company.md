# Escape Coffee Company — Style Reference
> Raw Concrete Canvas — Bold typography and rich textures anchor a tactile, achromatic experience.

**Theme:** light

Escape Coffee Company presents a rugged, textural commerce experience. High-contrast typography emphasizes bold statements, while a carefully curated achromatic palette allows rich product photography and content backgrounds to dominate. Interaction elements are minimal and integrated, often appearing as subtle outlines or text against dark neutral backgrounds, preserving a raw, authentic feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f5f4f2` | `--color-canvas-white` | Primary page background, UI surfaces, muted borders. This near-white ensures content stands out while providing a soft, natural base |
| Graphite Ink | `#151515` | `--color-graphite-ink` | Primary text, strong accents, filled button backgrounds. Its deep, near-black tone provides strong contrast for legibility and command |
| Asphalt Black | `#000000` | `--color-asphalt-black` | Primary text for specific links, deep shadows, and borders in high-contrast contexts |
| Pale Stone | `#ebe9e6` | `--color-pale-stone` | Subtle background shifts, lighter borders, and ghost button outlines, providing slight visual separation without strong contrast |
| Fog Gray | `#929292` | `--color-fog-gray` | Muted text, secondary information, and subtle background elements for visual depth |
| Pure White | `#ffffff` | `--color-pure-white` | Card backgrounds, modal surfaces, and text on dark backgrounds for maximum contrast |
| Outline Gray | `#8a8a8a` | `--color-outline-gray` | Input borders and subtle UI strokes |
| Subtle Border | `#e3e3e3` | `--color-subtle-border` | Hairline borders and dividers, providing organization without heavy visual weight |

## Tokens — Typography

### TWK Lausanne — Primary typeface for body text, general UI, and many headings. Its wide range of weights and careful letter spacing allows for both compact information and expressive statements. · `--font-twk-lausanne`
- **Substitute:** Inter
- **Weights:** 200, 300, 400, 600, 700
- **Sizes:** 11px, 13px, 14px, 16px, 18px, 19px, 22px, 24px, 28px, 50px
- **Line height:** 1.00, 1.05, 1.06, 1.20, 1.35, 1.81
- **Letter spacing:** -0.0100em, 0.0340em, 0.0430em, 0.0510em, 0.0530em, 0.0600em, 0.0670em, 0.0730em, 0.0750em
- **Role:** Primary typeface for body text, general UI, and many headings. Its wide range of weights and careful letter spacing allows for both compact information and expressive statements.

### Molitor — Impactful display typeface used for hero headlines and large promotional text. Its condensed, strong forms capture attention. · `--font-molitor`
- **Substitute:** Oswald
- **Weights:** 300, 700
- **Sizes:** 26px, 45px, 75px, 250px
- **Line height:** 0.85, 1.00
- **Letter spacing:** -0.0200em, 0.0130em, 0.0210em, 0.0370em
- **Role:** Impactful display typeface used for hero headlines and large promotional text. Its condensed, strong forms capture attention.

### Garaje — Distinctive secondary display typeface for specific titles, badges, and emphasizes text blocks. Its robust, slab-serif like character provides a grounded, artisanal touch. · `--font-garaje`
- **Substitute:** Bebas Neue
- **Weights:** 300, 600, 700
- **Sizes:** 18px, 22px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.0440em, 0.0530em
- **Role:** Distinctive secondary display typeface for specific titles, badges, and emphasizes text blocks. Its robust, slab-serif like character provides a grounded, artisanal touch.

### Arial — System fallback for specific button labels and icons, ensuring broad compatibility. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback for specific button labels and icons, ensuring broad compatibility.

### GTStandard-M — Unique mono-spaced font for code snippets or technical product details, creating a distinct content block. · `--font-gtstandard-m`
- **Substitute:** Space Mono
- **Weights:** 300
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** 0.0600em
- **Role:** Unique mono-spaced font for code snippets or technical product details, creating a distinct content block.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.35 | 0.43px | `--text-caption` |
| subheading | 18px | 1.2 | 0.44px | `--text-subheading` |
| heading-sm | 22px | 1 | 0.53px | `--text-heading-sm` |
| heading | 28px | 1.06 | 0.51px | `--text-heading` |
| heading-lg | 50px | 1 | -0.5px | `--text-heading-lg` |
| display-sm | 75px | 0.85 | -1.5px | `--text-display-sm` |
| display | 250px | 0.85 | -2px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 10px |
| inputs | 7px |
| buttons | 7px |
| default | 3px |
| circular | 50% |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(245, 244, 242) 0px 0px 0px 1.5px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Filled Primary Button
**Role:** Interactive element

Solid Graphite Ink background (#151515) with Pure White text (#f5f4f2). Has a 8px border-radius and 18px vertical, 20px horizontal padding. Identifies key calls to action.

### Ghost Button
**Role:** Interactive element

Transparent background with Graphite Ink text (#151515) and a 1px Graphite Ink border. No border-radius. Padding is 13.5px vertical, 0px horizontal. Used for secondary actions that require less visual weight.

### Text Link Button
**Role:** Interactive element

Transparent background with Pure White text (#f5f4f2) and a 1px Pure White border, 0px radius, 0px vertical padding, 48px horizontal. Used for promotional actions at large scale.

### Circular Ghost Icon Button
**Role:** Interactive element

Transparent background, Pure White text (#f5f4f2), Pure White border with 50% border-radius to create a full circle. Used for navigation icons or small, less prominent actions.

### Product Card
**Role:** Display content

Pure White background (#ffffff) with an asymmetric 16px 16px 0px 0px border-radius. Has 16px padding on top, right, and left, and 54px on bottom. Houses product imagery and details.

### Standard Input Field
**Role:** User input

Pure White background (#ffffff) with a 1px Outline Gray border (#8a8a8a) and 4px border-radius. Padding is 6px vertical, 10px right, 16px left. For general form inputs.

### Full-width Input Field
**Role:** User input

Transparent background with a 1px Canvas White border (#f5f4f2) and 0px border-radius. Has 12px vertical padding. Used for prominent input fields like search or newsletter sign-ups.

## Do's and Don'ts

### Do
- Use Graphite Ink (#151515) for all primary text content to maintain strong contrast against lighter backgrounds.
- Apply Canvas White (#f5f4f2) as the default page background and for subtle UI element borders.
- Prioritize TWK Lausanne for all body copy and standard headings, adjusting weight and letter spacing according to the type scale for functional variation.
- Reserve Molitor for large, impactful headlines (e.g., hero sections) to create significant visual presence.
- Ensure all interactive elements, like buttons, maintain a minimum border-radius of 7px, with product cards using 16px, for subtle softening without appearing overly rounded.
- Utilize 10px as the standard element gap for arranging items within cards or small groupings.
- Employ the Ghost Button variant (transparent background, Graphite Ink border, no radius) for secondary actions or navigation links to maintain a light UI footprint.

### Don't
- Do not introduce new saturated colors; the palette is strictly achromatic with minimal, functional color accents for specific text states.
- Avoid applying heavy drop shadows; elevation is primarily achieved through background color shifts and subtle borders.
- Do not use Molitor or Garaje for body text; their distinct characteristics are intended for display and emphasis only.
- Refrain from using border-radii smaller than 3px or deviating from the established 7px (buttons), 10px (badges), 16px (cards), and 50% (circular) values.
- Do not use generic padding values; adhere to the 16px card padding and 10px element gap for consistent content density.
- Avoid dense, information-heavy sections; ensure comfortable spacing and visual breaks between content blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#f5f4f2` | Base page background, light UI containers, and subtle organizational bands. |
| 1 | Card Surface | `#ffffff` | Elevated content blocks like product cards or form containers, providing a clean boundary. |
| 2 | Panel | `#ebe9e6` | Slightly darker background for specific sections or elements that need subtle differentiation from the main canvas. |
| 3 | Accent Surface | `#151515` | Dark backgrounds for high-contrast sections, primary buttons, or immersive content blocks where lighter text is needed. |

## Imagery

Imagery on Escape Coffee Company is characterized by raw, sometimes grunge-like, high-quality photography interwoven with product shots. The treatment is often full-bleed for hero sections, showing realistic textures like snow, grain, or misty landscapes, creating a mood. Product photography features tight crops of coffee bags or cups, often on contrasting surfaces. There are also detailed, almost blueprint-like illustrations on product packaging, which are abstract and functional. Icons are minimalist, outlined, and monochromatic, typically in Graphite Ink (#151515) or Pure White (#ffffff). Imagery plays a dual role: setting an atmospheric mood and clearly showcasing product details, dominating visual space in hero and collection sections.

## Layout

The site employs a primarily contained layout, utilizing a max-width for content sections, while the hero section breaks this with a full-bleed background image. The hero features a massive, split-word headline ('Go Against The Grain') overlaid directly onto the background, creating immediate impact. Sections generally flow with consistent vertical spacing, often alternating between visual styles (e.g., full-bleed image to white contained section). Content arrangement frequently uses left-aligned text with visual elements on the right, or centered stacks for product listings. There's an underlying grid for product display, likely 3-column, allowing for clear presentation of items. Density varies from image-heavy, spacious heroes to more compact product detail areas. Navigation consists of a sticky top bar and a thin, vertical sidebar on the right for utility links and a hamburger menu.

## Agent Prompt Guide

Quick Color Reference:
- text: #151515
- background: #f5f4f2
- border: #f5f4f2
- accent: no distinct accent color
- primary action: #151515 (filled action)

Example Component Prompts:
- Create a hero section with a full-bleed background image. Overlay a 'Molitor' 250px weight 700 headline in pure white (#ffffff) that reads 'GO AGAINST THE GRAIN'. Include a 'Text Link Button' at the bottom right with 'SHOP NOW' in pure white (#ffffff), 0px vertical padding, 48px horizontal padding, and #ffffff border.
- Design a product listing card: Use a Pure White background (#ffffff), 16px 16px 0px 0px border-radius, and 16px padding (top, right, left) with 54px bottom padding. Inside, feature a product image, followed by product name in 'TWK Lausanne' 18px weight 600, price in 'TWK Lausanne' 16px weight 400, and a 'Wrapped Ghost Button' with 'View Details' in Graphite Ink (#151515) and a #151515 border.
- Construct a search input field: Full-width, transparent background, with a 1px Canvas White border (#f5f4f2) and 0px border-radius. Use 'TWK Lausanne' 14px weight 400 for placeholder text in Fog Gray (#929292). Add 12px vertical padding.

## Similar Brands

- **A-COLD-WALL*** — Aggressive, impactful typography and an intentionally raw, often industrial aesthetic with minimal color.
- **Allbirds** — Focus on natural textures and materials, an earthy, muted palette, and clean product presentation.
- **Patagonia** — Rugged, outdoorsy aesthetic; strong photography; and an emphasis on authentic, sometimes natural-grain backdrops.
- **Acne Studios** — Minimalist layout with a strong emphasis on photography and distinct, often bold, type choices.
- **Aesop** — Understated elegance, focus on product and typography, with sophisticated but muted color applications.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f5f4f2;
  --color-graphite-ink: #151515;
  --color-asphalt-black: #000000;
  --color-pale-stone: #ebe9e6;
  --color-fog-gray: #929292;
  --color-pure-white: #ffffff;
  --color-outline-gray: #8a8a8a;
  --color-subtle-border: #e3e3e3;

  /* Typography — Font Families */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-molitor: 'Molitor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-garaje: 'Garaje', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.35;
  --tracking-caption: 0.43px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.44px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.53px;
  --text-heading: 28px;
  --leading-heading: 1.06;
  --tracking-heading: 0.51px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.5px;
  --text-display-sm: 75px;
  --leading-display-sm: 0.85;
  --tracking-display-sm: -1.5px;
  --text-display: 250px;
  --leading-display: 0.85;
  --tracking-display: -2px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 10px;
  --radius-inputs: 7px;
  --radius-buttons: 7px;
  --radius-default: 3px;
  --radius-circular: 50%;

  /* Shadows */
  --shadow-subtle: rgb(245, 244, 242) 0px 0px 0px 1.5px;

  /* Surfaces */
  --surface-canvas: #f5f4f2;
  --surface-card-surface: #ffffff;
  --surface-panel: #ebe9e6;
  --surface-accent-surface: #151515;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f5f4f2;
  --color-graphite-ink: #151515;
  --color-asphalt-black: #000000;
  --color-pale-stone: #ebe9e6;
  --color-fog-gray: #929292;
  --color-pure-white: #ffffff;
  --color-outline-gray: #8a8a8a;
  --color-subtle-border: #e3e3e3;

  /* Typography */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-molitor: 'Molitor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-garaje: 'Garaje', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.35;
  --tracking-caption: 0.43px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.44px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.53px;
  --text-heading: 28px;
  --leading-heading: 1.06;
  --tracking-heading: 0.51px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.5px;
  --text-display-sm: 75px;
  --leading-display-sm: 0.85;
  --tracking-display-sm: -1.5px;
  --text-display: 250px;
  --leading-display: 0.85;
  --tracking-display: -2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Shadows */
  --shadow-subtle: rgb(245, 244, 242) 0px 0px 0px 1.5px;
}
```
