# Cluely — Style Reference
> Radiant cloud-native intelligence: ethereal gradients, frosted glass, and digital blue accents against a bright canvas.

**Theme:** light

Cluely employs a radiant cloud-native aesthetic: light surfaces against a vibrant sky-blue hero, with crisp typography and subtle shadows. The design emphasizes lightness and integration, with ethereal gradients and frosted glass elements creating a sense of an AI assisting from 'within' the system rather than as a heavy external application. Interaction is guided by a singular vivid blue accent, making key actions feel responsive and digitally integrated.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces for cards and modals, primary text for dark backgrounds |
| Subtle Gray | `#e4e4e7` | `--color-subtle-gray` | Background for secondary sections, input borders, ghost button borders, subtle dividers |
| Surface Text | `#000000` | `--color-surface-text` | Primary text on light backgrounds, strong headings, active state icons |
| Paragraph Gray | `#2e3038` | `--color-paragraph-gray` | Body text, navigation items, secondary headings, muted icons |
| Muted Text | `#777a88` | `--color-muted-text` | Helper text, footer links, small annotations, less prominent body copy |
| Sky Canvas | `#f3f8ff` | `--color-sky-canvas` | Subtle background for UI elements, light emphasis on certain sections |
| Digital Blue | `#3c83f6` | `--color-digital-blue` | Primary call-to-action buttons, interactive links, highlights |
| Deep Ocean Gradient Start | `linear-gradient(rgb(5, 68, 169) 0%, rgb(2, 44, 112) 100%)` | `--color-deep-ocean-gradient-start` | Base color for prominent background gradients and elevated button shadows |
| Frost Morning Gradient Start | `radial-gradient(92.09% 126.39% at 50% 100%, rgb(221, 226, 238) 58.91%, rgb(187, 197, 221) 100%)` | `--color-frost-morning-gradient-start` | Subtle background gradient for cards and containers, creating a light, airy feel |
| Process Blue Gradient Start | `radial-gradient(114.65% 114.65% at 9.73% 17.27%, rgb(30, 130, 224) 0px, rgb(28, 56, 234) 100%)` | `--color-process-blue-gradient-start` | Hero background gradient, creating a vibrant and welcoming visual |
| System Green | `#00ff26` | `--color-system-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Teal Tint | `#7df0f8` | `--color-teal-tint` | Highlight backgrounds for text blocks, subtle decorative elements |

## Tokens — Typography

### Geist — The primary typeface for all UI elements, body text, and most headings. Its clean, modern lines balance approachability with technical clarity, used across a wide range of weights and sizes to establish hierarchy. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 9px, 10px, 11px, 12px, 13px, 14px, 16px, 18px, 19px, 20px, 24px, 28px, 30px, 36px, 42px, 48px, 56px
- **Line height:** 1.00, 1.11, 1.13, 1.20, 1.25, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 1.60
- **Letter spacing:** -0.0400em at 56px, -0.0360em at 48px, -0.0250em at 36px, normal at 16px
- **Role:** The primary typeface for all UI elements, body text, and most headings. Its clean, modern lines balance approachability with technical clarity, used across a wide range of weights and sizes to establish hierarchy.

### EB Garamond — Used for hero headings, providing a sophisticated, almost editorial counterpoint to Geist. The larger size and slight tracking create a distinctive, impactful display. · `--font-eb-garamond`
- **Substitute:** Garamond
- **Weights:** 500
- **Sizes:** 80px
- **Line height:** 1.02
- **Letter spacing:** -0.0120em
- **Role:** Used for hero headings, providing a sophisticated, almost editorial counterpoint to Geist. The larger size and slight tracking create a distinctive, impactful display.

### ui-monospace — ui-monospace — detected in extracted data but not described by AI · `--font-ui-monospace`
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.5
- **Role:** ui-monospace — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | -0.14px | `--text-body` |
| subheading | 18px | 1.33 | -0.036px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.025px | `--text-heading-sm` |
| heading | 42px | 1.13 | -0.036px | `--text-heading` |
| heading-lg | 56px | 1 | -0.04px | `--text-heading-lg` |
| display | 80px | 1.02 | -0.012px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 73 | 73px | `--spacing-73` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| cards | 24px |
| inputs | 4px |
| buttons | 1.67772e+07px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(12, 68, 161) 0px 0px 0px 0.5px, rgb(2, 44, 112) 0px -...` | `--shadow-subtle` |
| subtle-2 | `rgba(207, 226, 255, 0.24) 0px 0px 0px 1px, rgba(255, 255,...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.25) 0px -1px 0px 0px` | `--shadow-subtle-3` |
| lg | `rgba(0, 0, 0, 0.05) 0px 2px 20px -1px inset` | `--shadow-lg` |
| lg-2 | `rgba(148, 172, 243, 0.4) 20px 20px 24px 0px, rgba(191, 22...` | `--shadow-lg-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 73px
- **Card padding:** 22px
- **Element gap:** 8px

## Components

### Pill Button - Ghost
**Role:** Secondary action button, often paired with primary actions or for discrete functionalities.

Transparent background, 'Canvas White' text, 'Subtle Gray' 1px border. Extremely rounded corners at 1.67772e+07px for a pill shape. Padding: 0px vertical, 12px horizontal.

### Pill Button - Primary
**Role:** Main call-to-action button, visually distinct and inviting interaction.

Solid 'Digital Blue' background, 'Canvas White' text. Extremely rounded corners at 1.67772e+07px for a pill shape.

### Pill Button - Shadowed Overlay
**Role:** Interactive elements within product screenshots, mimicking OS-level controls.

Semi-transparent background (rgba(24, 23, 28, 0.1)), 'Canvas White' text (oklab(0.999994 0.0000455678 0.0000200868 / 0.4)). Border: oklab(0.999994 0.0000455678 0.0000200868 / 0.15). Pill shaped with 1.67772e+07px radius. Padding: 0px vertical, 8px horizontal.

### Feature Card - Transparent
**Role:** Displaying product features or information blocks without heavy visual presence.

Transparent background, 24px border radius. 22px padding on all sides. No box shadow, relying instead on layout and subtle background variations.

### Content Input Field
**Role:** Standard text input for forms, often with a product-like dark aesthetic.

Transparent background, 'Canvas White' text within. 'Subtle Gray' 1px border at the bottom only for a subtle demarcation. No border radius. Padding: 10px vertical, 10px horizontal.

### Frosted Card - Dark
**Role:** Presenting nested content or highlighting specific information within a dark context.

Semi-transparent dark background (oklab(0.257093 0.000663139 -0.0134566 / 0.5)), 12px border radius. Padding: 12px vertical, 28px horizontal. No box shadow.

## Do's and Don'ts

### Do
- Use Geist at weight 300 for large headings to convey authority via restraint, not volume.
- Apply 1.67772e+07px border radius for all interactive pill-shaped buttons to maintain a soft, modern feel.
- Employ 'Digital Blue' (#3c83f6) exclusively for primary action buttons and prominent interactive links.
- Structure page sections using 'Subtle Gray' (#e4e4e7) as a background for secondary content blocks.
- Incorporate subtle linear gradients like 'Deep Ocean Gradient Start' for elevated button shadows and background depth.
- Prioritize 'Canvas White' (#ffffff) for all main card and modal backgrounds, ensuring ample contrast for text.
- Use 'Frosted Card - Dark' with its oklab(0.257093 0.000663139 -0.0134566 / 0.5) background for content nested within darker product UI components.

### Don't
- Avoid generic square buttons; all standalone actions should adopt the pill shape (radius 1.67772e+07px).
- Refrain from using strong, opaque background colors on cards; prefer transparent or very light neutrals like 'Subtle Gray' or 'Canvas White'.
- Do not introduce new color accents outside of 'Digital Blue' (#3c83f6) for primary interactive elements.
- Do not use heavy, opaque shadows; opt for subtle, often colored, and semi-transparent elevation patterns like those found on buttons and product UI.
- Avoid dense, clustered layouts; maintain generous 'elementGap' of 8px and 'sectionGap' of 73px to preserve spaciousness.
- Do not use system fonts for headings; always use Geist or EB Garamond as specified for distinctiveness.
- Do not use dark backgrounds for main page content; the theme is predominantly light, with dark elements reserved for embedded product UI.

## Elevation

- **Interactive Button / Product UI:** `rgb(12, 68, 161) 0px 0px 0px 0.5px, rgb(2, 44, 112) 0px -1px 0px 0px inset, rgb(129, 182, 255) 0px 0.5px 0px 0px inset`
- **Hover/Focus States:** `rgba(207, 226, 255, 0.24) 0px 0px 0px 1px, rgba(255, 255, 255, 0.8) 0px -0.5px 0px 0px`
- **Input Field Focus:** `rgba(0, 0, 0, 0.05) 0px 2px 20px -1px inset`
- **Accented Interactive Element:** `rgba(148, 172, 243, 0.4) 20px 20px 24px 0px, rgba(191, 229, 251, 0.4) -3px -3px 4px 0px inset, rgba(19, 26, 228, 0.1) 4px 4px 4px 0px inset`

## Imagery

The visual language for imagery is primarily product screenshots presented within a 'frosted glass' macOS-like frame. These screenshots occupy significant visual space, often full-bleed or presented as large, contained components. Photography is minimal, often cropped tightly on product elements. Icons are typically outlined or mono-color (achromatic), with a thin stroke weight, used functionally rather than decoratively. The density is text-dominant for explanatory content, but imagery takes precedence in showcasing the product's UI, serving explanatory and demonstrative roles.

## Layout

The page model is a max-width 1200px centered container, creating a structured and controlled experience. The hero section is full-bleed, featuring a vibrant sky-blue radial gradient background with a centered, large EB Garamond headline. Subsequent sections alternate between white and 'Subtle Gray' backgrounds with consistent vertical spacing. Content is frequently arranged in two-column text-left/visual-right or visual-left/text-right patterns, often embedding product screenshots within transparent or frosted cards. A 3-column card grid is used for features. Navigation is a minimalist top bar, likely sticky, with clear branding and key external links.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #e4e4e7
accent: #3c83f6
primary action: #3c83f6 (filled action)

Example Component Prompts:
Create a hero section: radial-gradient(114.65% 114.65% at 9.73% 17.27%, rgb(30, 130, 224) 0px, rgb(28, 56, 234) 100%) background. Headline 'Undetectable AI for Meetings' at 80px EB Garamond weight 500, #ffffff, letter-spacing -0.012em. Subtext at 18px Geist weight 400, #ffffff. Primary pill button 'Get for Mac' with Digital Blue (#3c83f6) background, white text, 1.67772e+07px radius.

Create a feature card: Transparent background, 24px border radius, 22px padding. Heading at 24px Geist weight 500, #000000. Body text at 14px Geist weight 400, #2e3038. Small pill tag for categorization with 'System Green' (#00ff26) background and #ffffff text, 1.67772e+07px radius.

Create a product input field: Transparent background, #ffffff text. Bottom border 1px solid #e4e4e7. No border radius. Padding 10px.

## Similar Brands

- **Linear** — Monochromatic light interface with thin borders and minimal elevation, complemented by a single chromatic accent for interactions.
- **Raycast** — Application-style UI with frosted glass elements and system-adjacent visual language, designed for productivity tools.
- **Superhuman** — Emphasis on speed and functionality through a clean, light aesthetic, subtle gradients, and focused interactive elements.
- **Craft.do** — Focus on content and subtle background variations with a clean white canvas broken up by soft-edged cards and carefully placed accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #e4e4e7;
  --color-surface-text: #000000;
  --color-paragraph-gray: #2e3038;
  --color-muted-text: #777a88;
  --color-sky-canvas: #f3f8ff;
  --color-digital-blue: #3c83f6;
  --color-deep-ocean-gradient-start: #0544a9;
  --gradient-deep-ocean-gradient-start: linear-gradient(rgb(5, 68, 169) 0%, rgb(2, 44, 112) 100%);
  --color-frost-morning-gradient-start: #ddefe6;
  --gradient-frost-morning-gradient-start: radial-gradient(92.09% 126.39% at 50% 100%, rgb(221, 226, 238) 58.91%, rgb(187, 197, 221) 100%);
  --color-process-blue-gradient-start: #1e82e0;
  --gradient-process-blue-gradient-start: radial-gradient(114.65% 114.65% at 9.73% 17.27%, rgb(30, 130, 224) 0px, rgb(28, 56, 234) 100%);
  --color-system-green: #00ff26;
  --color-teal-tint: #7df0f8;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-eb-garamond: 'EB Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.036px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 42px;
  --leading-heading: 1.13;
  --tracking-heading: -0.036px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 80px;
  --leading-display: 1.02;
  --tracking-display: -0.012px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-73: 73px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 73px;
  --card-padding: 22px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 110.25px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-cards: 24px;
  --radius-inputs: 4px;
  --radius-buttons: 1.67772e+07px;

  /* Shadows */
  --shadow-subtle: rgb(12, 68, 161) 0px 0px 0px 0.5px, rgb(2, 44, 112) 0px -1px 0px 0px inset, rgb(129, 182, 255) 0px 0.5px 0px 0px inset;
  --shadow-subtle-2: rgba(207, 226, 255, 0.24) 0px 0px 0px 1px, rgba(255, 255, 255, 0.8) 0px -0.5px 0px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.25) 0px -1px 0px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 2px 20px -1px inset;
  --shadow-lg-2: rgba(148, 172, 243, 0.4) 20px 20px 24px 0px, rgba(191, 229, 251, 0.4) -3px -3px 4px 0px inset, rgba(19, 26, 228, 0.1) 4px 4px 4px 0px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #e4e4e7;
  --color-surface-text: #000000;
  --color-paragraph-gray: #2e3038;
  --color-muted-text: #777a88;
  --color-sky-canvas: #f3f8ff;
  --color-digital-blue: #3c83f6;
  --color-deep-ocean-gradient-start: #0544a9;
  --color-frost-morning-gradient-start: #ddefe6;
  --color-process-blue-gradient-start: #1e82e0;
  --color-system-green: #00ff26;
  --color-teal-tint: #7df0f8;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-eb-garamond: 'EB Garamond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.036px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 42px;
  --leading-heading: 1.13;
  --tracking-heading: -0.036px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 80px;
  --leading-display: 1.02;
  --tracking-display: -0.012px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-73: 73px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 110.25px;

  /* Shadows */
  --shadow-subtle: rgb(12, 68, 161) 0px 0px 0px 0.5px, rgb(2, 44, 112) 0px -1px 0px 0px inset, rgb(129, 182, 255) 0px 0.5px 0px 0px inset;
  --shadow-subtle-2: rgba(207, 226, 255, 0.24) 0px 0px 0px 1px, rgba(255, 255, 255, 0.8) 0px -0.5px 0px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.25) 0px -1px 0px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 2px 20px -1px inset;
  --shadow-lg-2: rgba(148, 172, 243, 0.4) 20px 20px 24px 0px, rgba(191, 229, 251, 0.4) -3px -3px 4px 0px inset, rgba(19, 26, 228, 0.1) 4px 4px 4px 0px inset;
}
```
