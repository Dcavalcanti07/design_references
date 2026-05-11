# Studio Few — Style Reference
> Gallery of Type on White Canvas

**Theme:** light

Studio Few embodies a stark, monochromatic aesthetic focused on typography. Surfaces are minimalist, predominantly white, creating a gallery-like backdrop for type specimens. Interaction elements are sharp, high-contrast, and leverage black as a primary action color, emphasizing clarity and directness. The overall feel is one of precise, confident design, allowing the varied and often experimental typefaces to be the central visual event.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, input surfaces, base for content presentation |
| Midnight Black | `#000000` | `--color-midnight-black` | Primary text, button backgrounds, interactive borders, structural outlines — establishes high-contrast dominance |
| Subtle Gray | `#b7b7b7` | `--color-subtle-gray` | Muted UI elements, secondary borders, inactive states, subtle dividers, informational text |
| Anchor Gray | `#333333` | `--color-anchor-gray` | Link text, subtle background textures, borders that recede slightly from primary black |
| Faded Gray | `#858585` | `--color-faded-gray` | Muted link text, less prominent border elements |

## Tokens — Typography

### SterlingVF — General UI text, flexible content, navigation, and detailed information. Its variable weight allows for subtle hierarchy and expressive versatility. · `--font-sterlingvf`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 158px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.43, 1.50, 1.57, 1.60, 1.71, 1.75, 1.86, 2.00
- **Letter spacing:** -0.0200em at large sizes, varying to 0.0170em at smaller sizes
- **Role:** General UI text, flexible content, navigation, and detailed information. Its variable weight allows for subtle hierarchy and expressive versatility.

### Formative — Primary display font for type specimens and prominent headlines. Its bold, condensed nature and tight tracking create a distinct, impactful visual statement. · `--font-formative`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 1.00
- **Letter spacing:** -0.0200em at 158px, -0.0100em at 14px
- **Role:** Primary display font for type specimens and prominent headlines. Its bold, condensed nature and tight tracking create a distinct, impactful visual statement.

### Voyager — Experimental display font for special specimens. Its unique, heavily tracked, and blocky character imparts a distinct, digital aesthetic. · `--font-voyager`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 0.70, 1.00
- **Letter spacing:** -0.1000em at 158px, -0.0200em at 14px
- **Role:** Experimental display font for special specimens. Its unique, heavily tracked, and blocky character imparts a distinct, digital aesthetic.

### AnthroVF — Display font for specific specimens, offering a refined, modern contrast to other display choices. · `--font-anthrovf`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 1.00
- **Letter spacing:** -0.0200em at 158px, -0.0100em at 14px
- **Role:** Display font for specific specimens, offering a refined, modern contrast to other display choices.

### BlokVF — Specialized display font with a blocky, geometric style for unique specimen showcases. · `--font-blokvf`
- **Substitute:** Squarefont
- **Weights:** 400
- **Sizes:** 14px, 115px
- **Line height:** 1.20, 1.71
- **Letter spacing:** normal
- **Role:** Specialized display font with a blocky, geometric style for unique specimen showcases.

### ArbeitProContrastVF — Display font used for showcasing type specimens, characterized by its clean, technical aesthetic. · `--font-arbeitprocontrastvf`
- **Substitute:** Archivo
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 1.00
- **Letter spacing:** -0.0200em at 158px, -0.0100em at 14px
- **Role:** Display font used for showcasing type specimens, characterized by its clean, technical aesthetic.

### Arbeittechnikvf — Technical display font for specific specimens, presenting a structured and precise appearance. · `--font-arbeittechnikvf`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 1.00
- **Letter spacing:** -0.0200em
- **Role:** Technical display font for specific specimens, presenting a structured and precise appearance.

### ApexVF — Display font with a distinct, confident stance for type specimens. · `--font-apexvf`
- **Substitute:** Chivo
- **Weights:** 400
- **Sizes:** 14px, 158px
- **Line height:** 1.71
- **Letter spacing:** normal
- **Role:** Display font with a distinct, confident stance for type specimens.

### Work Sans — Fallback and general body text for broader readability and system integration. · `--font-work-sans`
- **Substitute:** Work Sans
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Fallback and general body text for broader readability and system integration.

### Sterling — Sterling — detected in extracted data but not described by AI · `--font-sterling`
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.5, 1.67, 1.71, 2, 2.17
- **Letter spacing:** 0.017
- **Role:** Sterling — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.71 | — | `--text-caption` |
| body | 14px | 1.5 | 0.17px | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| display-sm | 115px | 1.2 | — | `--text-display-sm` |
| display | 158px | 1 | -2px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 112 | 112px | `--spacing-112` |
| 136 | 136px | `--spacing-136` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 6px |
| buttons | 6px |
| general | 2px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, indicating primary actions.

Solid Midnight Black background (#000000) with Canvas White text (#ffffff). Rounded corners at 6px. Padding of 12px vertical, 24px horizontal. Uses SterlingVF font at 14px.

### Navigation Link
**Role:** Header navigation items and inline links.

Canvas White text (#ffffff) on transparent background. No specific border radius. Uses SterlingVF font at varying sizes and weights for navigation. Horizontal padding of 12-24px.

### Input Field
**Role:** Text input areas for filtering or data entry.

Canvas White background (#ffffff) with Midnight Black text (#000000) and Midnight Black borders. No specific border radius. Uses SterlingVF font at default sizes.

### Type Specimen Panel
**Role:** Container for individual typeface demonstrations.

Each panel features a large typeface sample with controls for size and weight. Background is Canvas White (#ffffff). Text color varies between Midnight Black (#000000) and Subtle Gray (#b7b7b7) for controls. No explicit radius, appears square.

### Ghost Button
**Role:** Secondary action or trial options.

Transparent background with a Midnight Black (#000000) border and text color. 6px border radius. Used for 'Trial' action, indicating a less prominent but still interactive element.

## Do's and Don'ts

### Do
- Prioritize high contrast using Midnight Black (#000000) and Canvas White (#ffffff) for all main content and interactive elements.
- Use SterlingVF for general UI text, body content, and navigation, varying weights for hierarchy.
- Reserve bold, high-impact display fonts like Formative, Voyager, and AnthroVF for showcasing type specimens and major headlines.
- Apply a 6px border radius consistently to all interactive buttons and links.
- Maintain generous horizontal padding of 24px around block-level interactive elements like buttons.
- Employ Subtle Gray (#b7b7b7) for secondary information, muted controls, and dividers to introduce subtle visual breaks.
- Ensure letter-spacing is precisely managed for display fonts, using values like -0.0200em at large sizes to maintain impact.

### Don't
- Avoid introducing chromatic colors; maintain a strictly monochromatic palette featuring only black, white, and various grays.
- Do not use generic system fonts; always specify custom fonts for headlines and body text.
- Never use soft shadows or complex gradients; rely on flat colors, crisp lines, and high contrast for visual hierarchy.
- Do not vary border radius across interactive elements; maintain a consistent 6px for buttons and links.
- Avoid dense or cluttered layouts; leverage ample whitespace to give design elements room to breathe.
- Do not use letter-spacing as a broad stylistic choice; apply it specifically to display typography for visual impact.
- Do not use Canvas White (#ffffff) as the primary action background; Midnight Black (#000000) is reserved for this role.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default UI surface, providing a clean, expansive foundation. |

## Imagery

The visual language is characterized by minimalist, product-focused imagery. This primarily consists of abstract 3D renders or high-quality product mockups of screens showcasing typefaces. Imagery is typically monochrome or desaturated, often appearing on a stark white or light gray background, highlighting the typography itself as the primary visual. The treatment is full-bleed or contained in a way that emphasizes crisp edges and clean compositions. Icons are simple, outlined, and monochromatic, with a thin stroke weight, serving a functional rather than decorative role. Imagery acts as a sophisticated backdrop or direct showcase for the product (fonts), maintaining a strong sense of focus and eliminating distraction, making the site very text-dominant in its information display.

## Layout

The page primarily uses a full-bleed layout, particularly for hero sections and areas showcasing type specimens. Content is horizontally centered within a logical reading width when necessary, though explicit max-width is frequently overridden by full-width content blocks. The hero section features large, centered headlines paired with abstract graphic arrangements illustrating type. Sections often flow seamlessly into one another, with subtle visual breaks created by the shift in content or imagery alignment rather than strong dividers. Type specimen sections employ implicit grids for presenting individual fonts, using consistent vertical padding for rhythm. Navigation is a minimal top-bar, sticky header at the top right, providing unobtrusive access to key areas. The overall density is comfortable, allowing elements breathing room against the predominantly white canvas.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a primary action button: Midnight Black (#000000) background, Canvas White (#ffffff) text. SterlingVF font, weight 400, size 14px. 6px border radius. Padding 12px vertical, 24px horizontal.
2. Design a navigation link: Canvas White (#ffffff) text on transparent background. SterlingVF font, weight 400, size 14px. No specific radius. Padding 12px left/right.
3. Build a display type specimen: Formative font, weight 400, size 158px, letter-spacing -0.0200em, Midnight Black (#000000) text on Canvas White (#ffffff) background.

## Similar Brands

- **Pangram Pangram Foundry** — Similar high-contrast, black and white aesthetic for showcasing high-quality typography with minimalist UI.
- **Future Fonts** — Focus on type specimens with clean layouts and a strong emphasis on typography as the primary visual.
- **Founders Grotesk (Colophon Foundry)** — Uses a similar austere, professional, and monochrome design language to highlight typefaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-subtle-gray: #b7b7b7;
  --color-anchor-gray: #333333;
  --color-faded-gray: #858585;

  /* Typography — Font Families */
  --font-sterlingvf: 'SterlingVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-formative: 'Formative', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-voyager: 'Voyager', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-anthrovf: 'AnthroVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-blokvf: 'BlokVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeitprocontrastvf: 'ArbeitProContrastVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeittechnikvf: 'Arbeittechnikvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apexvf: 'ApexVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sterling: 'Sterling', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.17px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-display-sm: 115px;
  --leading-display-sm: 1.2;
  --text-display: 158px;
  --leading-display: 1;
  --tracking-display: -2px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-112: 112px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;

  /* Named Radii */
  --radius-links: 6px;
  --radius-buttons: 6px;
  --radius-general: 2px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-subtle-gray: #b7b7b7;
  --color-anchor-gray: #333333;
  --color-faded-gray: #858585;

  /* Typography */
  --font-sterlingvf: 'SterlingVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-formative: 'Formative', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-voyager: 'Voyager', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-anthrovf: 'AnthroVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-blokvf: 'BlokVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeitprocontrastvf: 'ArbeitProContrastVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeittechnikvf: 'Arbeittechnikvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apexvf: 'ApexVF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sterling: 'Sterling', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.17px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-display-sm: 115px;
  --leading-display-sm: 1.2;
  --text-display: 158px;
  --leading-display: 1;
  --tracking-display: -2px;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-112: 112px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
}
```
