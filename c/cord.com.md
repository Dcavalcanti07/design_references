# cord.com — Style Reference
> Sky blueprint on frosted glass

**Theme:** light

Cord establishes a professional, tech-oriented aesthetic with a light canvas and a dominant, desaturated blue acting as foundational brand identity. Typography is compact and precise, using a single typeface across all elements. Surfaces leverage soft, rounded corners and subtle shadows, suggesting a friendly yet organized digital environment. The system feels lightweight, with ample negative space and strategically placed accents of vivid blue for interactivity and critical information.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, elevated sections |
| Midnight Ink | `#0b3658` | `--color-midnight-ink` | Primary text, prominent headings, link text, borders, active states, information icons — forms the core of the brand's typographic and structural color |
| Cloud Gray | `#dde7ee` | `--color-cloud-gray` | Hairline borders, muted link borders, subtle card outlines, separators — provides delineation without visual weight |
| Oceanic Blue | `#4e9ad9` | `--color-oceanic-blue` | Call-to-action buttons, active navigation elements, interactive link highlights — the primary accent color that signifies action and engagement |
| Subtle Mist | `#e6f1fa` | `--color-subtle-mist` | Hover states, subtle background fills for sections or interactive elements — offers a gentle visual feedback |
| Slate Text | `#486984` | `--color-slate-text` | Secondary body text, less prominent links, ghost button borders — provides a softer contrast for supporting content |
| Muted Stone | `#688dac` | `--color-muted-stone` | Muted helper text, placeholder text in forms, subtle descriptions — an even lighter text color for tertiary information |
| Soft Ash | `#97b5ce` | `--color-soft-ash` | Headlines with decreased prominence, subtle text elements |
| Subtle Gray | `#c8d8e4` | `--color-subtle-gray` | Ghost button backgrounds, secondary button background with minimal impact |
| Success Teal | `#42b3b1` | `--color-success-teal` | Teal outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Error Red | `#f56c6c` | `--color-error-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Warning Orange | `#e2a365` | `--color-warning-orange` | Orange outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Twilight Gradient | `linear-gradient(278deg, rgb(123, 126, 230) 5.46%, rgb(74, 81, 148) 95.65%)` | `--color-twilight-gradient` | Decorative background gradient used in hero sections or prominent visual blocks |
| Deep Space Gradient | `linear-gradient(78deg, rgb(12, 61, 100) 7.69%, rgb(25, 36, 67) 124.07%)` | `--color-deep-space-gradient` | Decorative background gradient providing a darker, more intense brand presence |

## Tokens — Typography

### Figtree — The sole typeface, Figtree, establishes a unified and modern voice. Its clean geometry and varied weights allow for distinct hierarchy from large, impactful display text to crisp, legible body copy and functional elements. Reduced letter-spacing on larger sizes creates visual density. · `--font-figtree`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700, 800
- **Sizes:** 10px, 14px, 16px, 18px, 20px, 22px, 24px, 32px, 48px, 100px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.30, 1.40, 1.43, 1.50, 2.00, 2.81
- **Letter spacing:** -0.005, -0.004, -0.003, -0.002, -0.001, 0.01
- **Role:** The sole typeface, Figtree, establishes a unified and modern voice. Its clean geometry and varied weights allow for distinct hierarchy from large, impactful display text to crisp, legible body copy and functional elements. Reduced letter-spacing on larger sizes creates visual density.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.1px | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.3 | — | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.002px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.003px | `--text-heading-lg` |
| display | 48px | 1.1 | -0.004px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| badges | 5px |
| fields | 8px |
| avatars | 50% |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(11, 54, 88, 0.08) 0px 12px 48px 0px` | `--shadow-xl` |
| xl-2 | `rgba(11, 54, 88, 0.08) 0px 4px 32px 0px` | `--shadow-xl-2` |
| md | `rgba(11, 54, 88, 0.04) 0px 4px 12px 0px` | `--shadow-md` |
| xl-3 | `rgba(11, 54, 88, 0.08) 0px -20px 80px 0px` | `--shadow-xl-3` |
| sm | `rgb(255, 255, 255) 0px 0px 8px 16px` | `--shadow-sm` |
| xl-4 | `rgba(11, 54, 88, 0.04) 0px 4px 32px 0px` | `--shadow-xl-4` |
| xl-5 | `rgba(11, 54, 88, 0.08) 0px -4px 32px 0px` | `--shadow-xl-5` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 28px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action.

Filled with Oceanic Blue (#4e9ad9), white text, 8px border-radius, 12px vertical padding, 20px horizontal padding. Font: Figtree weight 600.

### Outlined Accent Button
**Role:** Secondary action or navigation link.

Transparent background, Oceanic Blue (#4e9ad9) text and 1px border, 8px border-radius, 12px vertical padding, 20px horizontal padding. Font: Figtree weight 600.

### Ghost Circular Action Button
**Role:** Icon-only action within components or headers.

Transparent background, Oceanic Blue (#4e9ad9) icon/text, 50% border-radius (circular), 8px padding. Font: Figtree weight 600.

### Text Link Button
**Role:** Inline or minimal action.

Transparent background, Midnight Ink (#0b3658) text, no border or padding, no border-radius. Font: Figtree weight 400.

### Elevated Card
**Role:** Content container for features, job listings, or product info.

Canvas White (#ffffff) background, 24px border-radius, 28px padding, with a subtle shadow: rgba(11, 54, 88, 0.08) 0px 12px 48px 0px.

### Basic Card
**Role:** Minimal container, often for lists or grids.

Transparent background, 0px border-radius, no shadow, 0px padding. Used for simple grouping of content such as image grids.

### Search Input
**Role:** Interactive text input for search functionality.

Transparent background, Midnight Ink (#0b3658) text and border, 0px border-radius, 0px padding. Placeholder text uses Muted Stone (#688dac).

### Soft Badge
**Role:** Categorization or status indicator.

Transparent background, Slate Text (#486984) text, 5px border-radius, 3px vertical padding, 5px horizontal padding. Font: Figtree weight 400.

## Do's and Don'ts

### Do
- Use Midnight Ink (#0b3658) for all primary text and main headings.
- Apply Oceanic Blue (#4e9ad9) exclusively for primary interactive elements, such as filled buttons and active navigation items.
- Prioritize Canvas White (#ffffff) as the dominant background for all main page content and most card surfaces.
- Implement a 24px border-radius for cards, while ensuring buttons maintain an 8px border-radius for consistency.
- Utilize the Figtree typeface across all typographic elements, adjusting weight and size to convey hierarchy.
- Separate primary sections with a 'sectionGap' of 64px to ensure ample breathing room.
- Apply the subtle shadow rgba(11, 54, 88, 0.08) 0px 12px 48px 0px for elevated cards to provide depth.

### Don't
- Do not introduce new typefaces; rely solely on Figtree for all text.
- Avoid using saturated colors for backgrounds or large areas; maintain a light and neutral canvas.
- Do not apply strong, opaque borders to cards or interactive elements; favor subtle borders with Cloud Gray (#dde7ee) or transparent styles.
- Refrain from using hard, square corners; ensure elements consistently use varied but specific border-radii from 5px to 24px.
- Do not deviate from the established spacing hierarchy; avoid arbitrary padding or margins.
- Do not use dark backgrounds for main content areas in the light theme, except for specific hero banners using established gradients.
- Avoid heavy drop shadows; all elevation should be achieved using the specified subtle shadow tokens.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Background | `#ffffff` | Dominant background for the entire page, providing a clean, light base. |
| 1 | Elevated Card Surface | `#ffffff` | Background for primary content cards and interactive modules, distinguished by subtle shadow. |
| 2 | Subtle Fill | `#e6f1fa` | Lightest background for interactive elements on hover, or for secondary content blocks requiring a minimal lift. |
| 3 | Ghost Button Background | `#c8d8e4` | Used for ghost buttons or indicators for options with lowest visual prominence. |

## Elevation

- **Elevated Card:** `rgba(11, 54, 88, 0.08) 0px 12px 48px 0px`
- **Smaller Card:** `rgba(11, 54, 88, 0.08) 0px 4px 32px 0px`
- **Button:** `rgba(11, 54, 88, 0.04) 0px 4px 12px 0px`

## Imagery

The visual language predominantly features clean, product-focused photography and small, filled, monochrome icons. Photography typically depicts small groups of people in a professional context, often within team settings, cropped to create an accessible and direct connection with the viewer. Logos are prominent. Icons are simple, filled, and use the brand's blues or muted grays, maintaining functional clarity rather than decorative embellishment. Imagery serves to establish social proof and illustrate the platform's community, maintaining a relatively high density within grid layouts without overwhelming the page.

## Layout

The page adheres to a max-width contained model, centered on a Canvas White (#ffffff) background. The hero section often features a gradient background with prominent, centered typography. Content sections below alternate between card grids, primarily 3-column, and two-column layouts featuring imagery alongside text. Vertical rhythm is governed by a consistent 'sectionGap' of 64px, creating clear separation. Navigation is managed through a sticky top bar with clear actions and links. The footer is organized into multiple columns for sitemap detail.

## Agent Prompt Guide

Quick Color Reference:
- text: #0b3658
- background: #ffffff
- border: #dde7ee
- accent: #4e9ad9
- primary action: #4e9ad9 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #4e9ad9 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a feature card: Canvas White background, 24px border-radius, 28px padding, with an Elevated Card shadow. Inside, a heading-sm in Midnight Ink, followed by body text in Slate Text. Include a Soft Badge in the top right.
- Create a search input: Transparent background with a 1px Cloud Gray (#dde7ee) border and 8px border-radius. Placeholder text in Muted Stone (#688dac). Text input should be Midnight Ink. Include a Ghost Circular Action Button with an 'X' icon for clearing.

## Similar Brands

- **LinkedIn** — Professional networking and job platforms often feature a clean, blue-centric design with clear information hierarchy for job listings and profiles.
- **Replit** — Modern developer tool interfaces often leverage light backgrounds with a single strong accent color for interactive elements and deep, readable text colors.
- **Notion** — Productivity tools often use a high-contrast text on light background, with subtle borders and clear functional typography, and round-cornered card styles.
- **Linear** — SaaS tools aiming for efficiency often feature monochromatic interfaces, precise typography with reduced letter-spacing for large text, and a distinctive accent color for primary actions, favoring clean lines and subtle elevation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #0b3658;
  --color-cloud-gray: #dde7ee;
  --color-oceanic-blue: #4e9ad9;
  --color-subtle-mist: #e6f1fa;
  --color-slate-text: #486984;
  --color-muted-stone: #688dac;
  --color-soft-ash: #97b5ce;
  --color-subtle-gray: #c8d8e4;
  --color-success-teal: #42b3b1;
  --color-error-red: #f56c6c;
  --color-warning-orange: #e2a365;
  --color-twilight-gradient: #7b7ee6;
  --gradient-twilight-gradient: linear-gradient(278deg, rgb(123, 126, 230) 5.46%, rgb(74, 81, 148) 95.65%);
  --color-deep-space-gradient: #0c3d64;
  --gradient-deep-space-gradient: linear-gradient(78deg, rgb(12, 61, 100) 7.69%, rgb(25, 36, 67) 124.07%);

  /* Typography — Font Families */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.1px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.002px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.003px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.004px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 28px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 35px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-badges: 5px;
  --radius-fields: 8px;
  --radius-avatars: 50%;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-xl: rgba(11, 54, 88, 0.08) 0px 12px 48px 0px;
  --shadow-xl-2: rgba(11, 54, 88, 0.08) 0px 4px 32px 0px;
  --shadow-md: rgba(11, 54, 88, 0.04) 0px 4px 12px 0px;
  --shadow-xl-3: rgba(11, 54, 88, 0.08) 0px -20px 80px 0px;
  --shadow-sm: rgb(255, 255, 255) 0px 0px 8px 16px;
  --shadow-xl-4: rgba(11, 54, 88, 0.04) 0px 4px 32px 0px;
  --shadow-xl-5: rgba(11, 54, 88, 0.08) 0px -4px 32px 0px;

  /* Surfaces */
  --surface-canvas-background: #ffffff;
  --surface-elevated-card-surface: #ffffff;
  --surface-subtle-fill: #e6f1fa;
  --surface-ghost-button-background: #c8d8e4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #0b3658;
  --color-cloud-gray: #dde7ee;
  --color-oceanic-blue: #4e9ad9;
  --color-subtle-mist: #e6f1fa;
  --color-slate-text: #486984;
  --color-muted-stone: #688dac;
  --color-soft-ash: #97b5ce;
  --color-subtle-gray: #c8d8e4;
  --color-success-teal: #42b3b1;
  --color-error-red: #f56c6c;
  --color-warning-orange: #e2a365;
  --color-twilight-gradient: #7b7ee6;
  --color-deep-space-gradient: #0c3d64;

  /* Typography */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.1px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.002px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.003px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.004px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 35px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;

  /* Shadows */
  --shadow-xl: rgba(11, 54, 88, 0.08) 0px 12px 48px 0px;
  --shadow-xl-2: rgba(11, 54, 88, 0.08) 0px 4px 32px 0px;
  --shadow-md: rgba(11, 54, 88, 0.04) 0px 4px 12px 0px;
  --shadow-xl-3: rgba(11, 54, 88, 0.08) 0px -20px 80px 0px;
  --shadow-sm: rgb(255, 255, 255) 0px 0px 8px 16px;
  --shadow-xl-4: rgba(11, 54, 88, 0.04) 0px 4px 32px 0px;
  --shadow-xl-5: rgba(11, 54, 88, 0.08) 0px -4px 32px 0px;
}
```
