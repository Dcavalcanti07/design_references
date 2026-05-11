# VSCO® — Style Reference
> High-contrast geometric abstraction. Like engineering blueprints rendered in bold ink on a white page, punctuated by a single, sharp burst of yellow ink.

**Theme:** light

VSCO's design system creates a raw, utilitarian feel, blending high-contrast black and white with a select, vibrant yellow accent. The heavy reliance on a custom sans-serif font with tight letter-spacing for headlines establishes a direct, unadorned communication style. The overall impression is one of stark professionalism with a hint of creative energy, achieved through the deliberate scarcity of color and the bold, geometric typography.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Black | `#000000` | `--color-absolute-black` | Primary text, headline text, buttons, background for dark sections. Establishes the stark contrast. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, ghost button text. The canvas for all content, amplifying contrast. |
| Fog Gray | `#f2f2f2` | `--color-fog-gray` | Subtle background for alternating sections, differentiating content blocks without visual noise. |
| Steel Gray | `#d9d9d9` | `--color-steel-gray` | Outline for ghost buttons, subtle borders. Adds definition without heaviness. |
| Medium Gray | `#737373` | `--color-medium-gray` | Secondary text, descriptive elements. Provides hierarchy without losing legibility. |
| Amber Glow | `#f1a900` | `--color-amber-glow` | Key CTA buttons, badges, interactive accents. The single, sharp burst of color to draw attention. |
| Sunshine Yellow | `#ffbc3c` | `--color-sunshine-yellow` | Alternate CTA button color, indicating a secondary but still active call-to-action. |

## Tokens — Typography

### VSCO Gothic — The primary typeface for all textual content, from body to display. Its custom nature and geometric structure, particularly the tight negative letter-spacing on display sizes, create a distinctive, authoritative, and modern feel that a system font would not achieve. · `--font-vsco-gothic`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 13px, 15px, 16px, 24px, 29px, 36px, 54px, 89px, 98px
- **Line height:** 0.88, 0.93, 0.95, 1.00, 1.08, 1.10, 1.14, 1.20, 1.24, 1.25, 1.29, 1.30, 1.40, 1.50
- **Letter spacing:** -0.05em at large sizes, 0.05em, 0.08em, 0.10em
- **OpenType features:** `"clig" 0, "liga" 0`
- **Role:** The primary typeface for all textual content, from body to display. Its custom nature and geometric structure, particularly the tight negative letter-spacing on display sizes, create a distinctive, authoritative, and modern feel that a system font would not achieve.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 15px | 1.3 | — | `--text-body` |
| subheading | 24px | 1.25 | — | `--text-subheading` |
| heading | 36px | 1.25 | — | `--text-heading` |
| heading-lg | 54px | 1.14 | — | `--text-heading-lg` |
| display | 98px | 0.93 | -0.98px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 4px |
| images | 4px |
| buttons | 999px |
| navItems | 4px |

### Layout

- **Section gap:** 100px
- **Card padding:** 28-30px
- **Element gap:** 4-20px

## Components

### Primary CTA Button
**Role:** Call to action

Solid black background (#000000), white text (#ffffff), 999px border-radius, 2px vertical padding, 16px horizontal padding. Font is VSCO Gothic, weight 600.

### Ghost Button
**Role:** Secondary action

Transparent background, black text (#000000), 1px solid black border (#000000), 999px border-radius, 2px vertical padding, 28px horizontal padding. Font is VSCO Gothic, weight 400.

### Underlined Navigation Button
**Role:** Navigation links

Transparent background, black text (#000000), 1px solid black border-bottom (#000000), 0px border-radius, 8px vertical padding, 0px horizontal padding. Font is VSCO Gothic, weight 400.

### Amber CTA Button
**Role:** Alternate call to action

Solid amber background (#f1a900), black text (#000000), 999px border-radius, 2px vertical padding, 28px horizontal padding. Font is VSCO Gothic, weight 600.

### Info Badge (Amber)
**Role:** Labels for new features or status

Solid amber background (#f1a900), black text (#000000), 4px border-radius, 4px vertical padding, 6px horizontal padding. Font is VSCO Gothic.

### Pricing Card (Dark)
**Role:** Displays pricing tiers or feature sets

Solid black background (#000000), white text (#ffffff), 0px border-radius, 30px vertical padding, 28px horizontal padding.

### Pricing Card (Light)
**Role:** Displays pricing tiers or feature sets

Solid white background (#ffffff), black text (#000000), 0px border-radius, 30px vertical padding, 28px horizontal padding.

### Hero Headline
**Role:** Main page title

VSCO Gothic, 98px size, 0.93 line-height, -0.05em letter-spacing, pure black text (#000000).

## Do's and Don'ts

### Do
- Prioritize Absolute Black (#000000) and Pure White (#ffffff) for high-contrast pairs, especially for text and background combinations.
- Use VSCO Gothic with negative letter-spacing for headlines (e.g., -0.05em at large sizes) to create a distinct, modern feel.
- Apply 999px border-radius for all primary and secondary buttons, signifying interactive elements.
- Employ Amber Glow (#f1a900) as the exclusive accent color for primary calls-to-action and badges.
- Maintain a tight vertical rhythm using base units of 4px, especially for margin-bottom and padding in blocks and text.
- Utilize Fog Gray (#f2f2f2) to subtly differentiate background sections without introducing strong chromatic shifts.

### Don't
- Avoid using multiple accent colors; Amber Glow (#f1a900) and Sunshine Yellow (#ffbc3c) serve as the only chromatic highlights.
- Do not introduce soft shadows or gradients; the design relies on stark contrast and flat surfaces for depth.
- Omit rounded corners for cards and main content blocks; these should remain sharp (0px radius) to maintain the geometric aesthetic.
- Do not deviate from VSCO Gothic; it is integral to the brand's typographic identity.
- Avoid excessive spacing; elements are presented compactly to maintain information density.
- Do not use subtle gray for actionable elements; interactivity should be clearly indicated by Absolute Black, Pure White, or Amber Glow.

## Imagery

Imagery on this site is dominated by high-quality photography, often depicting people using cameras or artistic, abstract compositions. Images are typically full-bleed in hero sections or contained within fluid, responsive layouts, sometimes with a 4px border-radius. Product screenshots are minimal, focusing on the interface itself. The role of imagery is primarily aspirational and atmospheric, showcasing the potential results of using the product, with a secondary role in explanatory content via illustrative product UI shots. Graphics are largely absent, favoring photography.

## Layout

The page model alternates between full-bleed sections and a max-width contained layout, centered on the page. The hero features a full-bleed background photograph with a prominent, centered headline and subtext over solid white. Subsequent sections often use alternating white and Fog Gray (#f2f2f2) backgrounds with consistent vertical spacing. Content is primarily arranged in two-column layouts featuring text and imagery, or three-column card grids for features. The navigation is a sticky top bar with clearly delineated links and call-to-action buttons. The overall density is compact, presenting information efficiently with minimal whitespace between elements.

## Agent Prompt Guide

### Quick Color Reference
Text: #000000
Background: #ffffff
CTA: #f1a900
Border: #d9d9d9
Accent: #f1a900

### Example Component Prompts
1.  **Create a Hero Section**: Background photo. Centered headline 'WHERE PHOTOGRAPHERS TURN PRO' (VSCO Gothic, 98px, 0.93 lh, -0.05em ls, #000000). Below, body text 'Capture and edit photos with professional apps...' (VSCO Gothic, 15px, 1.3 lh, #000000). Two buttons below that: 'TRY VSCO FOR FREE' (black background #000000, white text #ffffff, 999px radius, 2px vertical padding, 16px horizontal padding) and 'EXPLORE PRO' (Amber Glow background #f1a900, black text #000000, 999px radius, 2px vertical padding, 28px horizontal padding).
2.  **Generate a Feature Card**: Background Pure White (#ffffff), 0px radius, 30px vertical and 28px horizontal padding. Headline 'PHOTO FILTERS' (VSCO Gothic, 24px, 1.25 lh, #000000). Below, a small image with 4px radius. At the bottom, a link 'Learn More' (VSCO Gothic, 15px, 1.3 lh, #000000) with an arrow icon.
3.  **Build a Navigation Bar**: Background Pure White (#ffffff). Links 'Products', 'Solutions', etc. (VSCO Gothic, 15px, 1.3 lh, #000000, 8px vertical padding, 0px horizontal padding, 1px solid black border-bottom). One ghost button 'LOG IN' (transparent background, #000000 text, 1px #000000 border, 999px radius, 2px vertical padding, 28px horizontal padding) and one primary CTA button 'TRY FOR FREE' (black background #000000, white text #ffffff, 999px radius, 2px vertical padding, 16px horizontal padding).
4.  **Create a Section Divider**: Background Fog Gray (#f2f2f2), minimum height 100px. Headline 'EVERYTHING A PHOTOGRAPHER NEEDS' (VSCO Gothic, 54px, 1.14 lh, #000000, -0.05em ls) centered within this section. Below the headline, a row of underlined navigation links, 'WHAT’S NEW', 'CREATE', 'CONNECT', 'WORK', all with black text, 8px vertical padding, and a 1px solid black border-bottom, using VSCO Gothic 15px, 1.3 lh.

## Similar Brands

- **Adobe Creative Cloud** — Similar target audience (creatives), uses a clean, utilitarian aesthetic with high-contrast text and limited accent colors for professional tools.
- **Figma** — Employs a stark, functional interface with strong typography and a measured use of brand accent colors against a mostly monochromatic background.
- **Frame.io** — Features a direct, high-contrast visual style with a focus on product visuals and a precise typographic hierarchy for professional users.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-fog-gray: #f2f2f2;
  --color-steel-gray: #d9d9d9;
  --color-medium-gray: #737373;
  --color-amber-glow: #f1a900;
  --color-sunshine-yellow: #ffbc3c;

  /* Typography — Font Families */
  --font-vsco-gothic: 'VSCO Gothic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 15px;
  --leading-body: 1.3;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.14;
  --text-display: 98px;
  --leading-display: 0.93;
  --tracking-display: -0.98px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 28-30px;
  --element-gap: 4-20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 4px;
  --radius-images: 4px;
  --radius-buttons: 999px;
  --radius-navitems: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-fog-gray: #f2f2f2;
  --color-steel-gray: #d9d9d9;
  --color-medium-gray: #737373;
  --color-amber-glow: #f1a900;
  --color-sunshine-yellow: #ffbc3c;

  /* Typography */
  --font-vsco-gothic: 'VSCO Gothic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 15px;
  --leading-body: 1.3;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.14;
  --text-display: 98px;
  --leading-display: 0.93;
  --tracking-display: -0.98px;

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
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 999px;
}
```
