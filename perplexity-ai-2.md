# Perplexity AI — Style Reference
> Ivory Desk, Graphite Tools — a pristine, brightly lit workspace filled with essential gray instruments.

**Theme:** light

This system projects an academic, almost clinical, aesthetic through a severely limited palette of desaturated off-whites and dark grays, creating an atmosphere of focused utilitarianism. The meticulous use of varying gray tones defines clear information hierarchy and interaction states without relying on strong color accents. Sharp corners mix with extreme pill-shaped elements, establishing a visual tension between precise structure and approachable interaction, characteristic of AI tools balancing complexity with user-friendliness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#000000` | `--color-inkwell` | Primary text, interactive icons, active states – commands immediate attention against the subtle backgrounds. |
| Paper White | `#FFFFFF` | `--color-paper-white` | Main page background, pristine canvas for content. The brightest neutral. |
| Parchment | `#FAF8F5` | `--color-parchment` | Interactive element backgrounds like search bars and buttons in inactive states, providing a soft contrast to the main background. |
| Graphite | `#27251` | `--color-graphite` | Secondary text, subtle backgrounds for elevated elements, and borders for input fields – registers as dark but softer than pure black. |
| Faded Stone | `#92918B` | `--color-faded-stone` | Placeholder text, subtle contextual information, providing low-contrast visual guiding. |
| Dusk Gray | `#72706B` | `--color-dusk-gray` | Tertiary text, inactive icons, divider lines – defines softer visual cues and non-critical information. |

## Tokens — Typography

### pplxSans — All text elements, including body, navigation, and headings. Its use across all types creates a cohesive, restrained tone. The custom font contributes to a distinctive feel, avoiding common system fonts for a unique subtle character. · `--font-pplxsans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.50, 2.00
- **Letter spacing:** normal
- **Role:** All text elements, including body, navigation, and headings. Its use across all types creates a cohesive, restrained tone. The custom font contributes to a distinctive feel, avoiding common system fonts for a unique subtle character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |

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
| 32 | 32px | `--spacing-32` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 8px |
| buttons | 9999px |
| navigation | 8px |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Navigation Item (Active)
**Role:** Indicates current selected item in the sidebar navigation.

Background: Parchment (#FAF8F5), Text: Inkwell (#000000), Border Radius: 8px, Padding: 4px vertical, 12px horizontal. `pplxSans` 400 at 16px.

### Primary Navigation Item (Inactive)
**Role:** Non-selected items in the sidebar navigation.

Background: transparent, Text: Graphite (#27251E), Border Radius: 8px, Padding: 4px vertical, 12px horizontal. `pplxSans` 400 at 16px.

### Search Input Field
**Role:** Main input area for user queries.

Background: Parchment (#FAF8F5), Border Radius: 8px, Left padding 16px, Right padding 12px. Placeholder text: Dusk Gray (#72706B). `pplxSans` 400 at 16px.

### Pill Button (Default)
**Role:** General action button with a rounded style.

Background: transparent, Text: Faded Stone (#92918B), Border Radius: 9999px, Padding: 0px. `pplxSans` 400 at 14px.

### Pill Button (Accent)
**Role:** Interactive elements within the search bar or filter tags.

Background: Graphite (#27251E), Text: Paper White (#FDFBFA), Border Radius: 9999px, Padding 0px. `pplxSans` 400 at 14px.

## Do's and Don'ts

### Do
- Prioritize Graphite (#27251E) for secondary text and subtle UI elements to maintain a restrained aesthetic.
- Use Paper White (#FFFFFF) as the predominant background, with Parchment (#FAF8F5) for interactive surfaces to create depth without strong shadows.
- Apply 9999px border-radius to all interactive buttons and tags for a distinctive pill shape.
- Maintain 8px border-radius for input fields and active navigation items to denote interactive, contained elements.
- Use Inkwell (#000000) exclusively for primary text and critical interactive icons for maximum clarity and contrast.
- Ensure 4px vertical padding for list items and 8px for internal element gaps to maintain a compact density.
- Use the `pplxSans` font at weight 400 for all body and informational text for consistent tone.

### Don't
- Avoid chromatic colors; this system relies exclusively on shades of gray and off-white.
- Do not use box-shadows that are anything other than extremely subtle; surface differentiation comes from color variants, not elevation.
- Do not introduce square buttons or elements if they contain interactive copy or serve as primary actions; use the 9999px radius.
- Do not vary font families; stick strictly to `pplxSans` (or 'Inter') for all typographic elements.
- Do not use font weights other than 400 or 500.
- Avoid large spacing values; the design emphasizes information density with 4px and 8px increments.

## Elevation

This design systematically avoids strong shadows or complex elevation schemes. Instead, surface differentiation and hierarchy are established primarily through subtle color variations between closely related neutrals (Paper White, Parchment, Graphite). This approach maintains a flat, precise, and understated aesthetic, focusing user attention on content and interaction logic rather than visual depth effects.

## Imagery

The site uses an icons-only approach, with no photography, illustrations, or complex graphics. Icons are monochrome, primarily Inkwell (#000000) or Graphite (#27251E), and are used functionally to denote actions or categories. Their role is purely explanatory, supporting the text-dominant interface. The density is very low, presenting a purely UI-driven experience without decorative visuals.

## Layout

The page adheres to a two-column, fixed-width layout. A left sidebar (900px wide) serves as primary navigation, featuring a search input and content categories. The main content area occupies the rest of the available width, centered, and contains the core interactive elements. The hero section prominently displays the brand name 'perplexity' centered, followed by the main AI query input field. Section rhythm is consistent, separated by distinct horizontal gaps and color differentiation rather than borders, creating a spacious yet focused interface. Content is primarily stacked vertically in the main area, with smaller interactive elements arranged horizontally.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000 (Inkwell)
- Background (Page): #FFFFFF (Paper White)
- Background (Surface/Active Nav): #FAF8F5 (Parchment)
- Text (Secondary): #27251 (Graphite)
- Border/Input Placeholder: #92918B (Faded Stone)

### Example Component Prompts
1. Create a `Primary Navigation Item (Active)`: Background Parchment (#FAF8F5), Text Inkwell (#000000), Border Radius 8px, Padding 4px vertical 12px horizontal. Use `pplxSans` 400 at 16px.
2. Create a `Search Input Field`: Background Parchment (#FAF8F5), Border Radius 8px. Left padding 16px, Right padding 12px. Placeholder text Faded Stone (#92918B). Use `pplxSans` 400 at 16px.
3. Create a `Pill Button (Accent)`: Background Graphite (#27251E), Text Paper White (#FDFBFA), Border Radius 9999px, Padding 0px. Use `pplxSans` 400 at 14px.
4. Design a `Prompt Suggestion Card` with content 'Try Computer'. Background Paper White (#FFFFFF), Border Radius 16px, Padding 16px. Text Faded Stone (#92918B) `pplxSans` 400 at 14px.

## Similar Brands

- **Notion** — Monochromatic interface with off-white/gray palette, emphasizing text and functional elements over decorative visuals. Similar component styling with subtle background shifts.
- **Linear** — Predominantly type-driven, compact layout, and a focus on shades of gray for hierarchy rather than strong accent colors. Uses similar sharp/pill radius contrast.
- **ChatGPT** — Text-heavy AI interface with a clean, understated aesthetic, minimal use of color, and high legibility. Similar input and interactive button styling.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #000000;
  --color-paper-white: #FFFFFF;
  --color-parchment: #FAF8F5;
  --color-graphite: #27251;
  --color-faded-stone: #92918B;
  --color-dusk-gray: #72706B;

  /* Typography — Font Families */
  --font-pplxsans: 'pplxSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-32: 32px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 8px;
  --radius-buttons: 9999px;
  --radius-navigation: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #000000;
  --color-paper-white: #FFFFFF;
  --color-parchment: #FAF8F5;
  --color-graphite: #27251;
  --color-faded-stone: #92918B;
  --color-dusk-gray: #72706B;

  /* Typography */
  --font-pplxsans: 'pplxSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-32: 32px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;
}
```
