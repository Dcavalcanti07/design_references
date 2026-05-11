# Ciridae — Style Reference
> Monochrome Grid, Abstract Glow. Precision-engineered UI on a dark, almost black canvas, with typography as the primary visual texture and light playing like reflections off dark metal.

**Theme:** dark

This AI transformation firm's design identity is a stark, high-contrast monochrome world, like a precision instrument in a dark laboratory. The design consistently avoids color beyond white and black, using the absence of color to convey seriousness and focus. The only chromatic hint is a subtle, almost unnoticeable orange, creating an atmosphere of contained power. This system focuses on sharp typography and generous padding around interactive elements, suggesting careful deliberation in every interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Black | `#000000` | `--color-absolute-black` | Backgrounds, prominent text, icon fills. |
| Deep Charcoal | `#0B0B0B` | `--color-deep-charcoal` | Secondary backgrounds, subtle elevated surfaces. |
| Warm Graphite | `#272A2A` | `--color-warm-graphite` | Tertiary backgrounds, deeper surface layers. |
| Pure White | `#FFFFFF` | `--color-pure-white` | Primary text, button labels, interactive elements, prominent iconography. Creates high contrast against dark backgrounds. |
| Ash Gray | `#CECECE` | `--color-ash-gray` | Subtle borders, inactive text, secondary iconography. |
| Steel Gray | `#858585` | `--color-steel-gray` | Placeholder text, minor borders, tertiary text. |
| Subtle Orange | `#CC6437` | `--color-subtle-orange` | Rare accent color for specific information hints or subtle emphasis. Its limited use makes any appearance notable. |
| White to Ash Gradient | `linear-gradient(rgb(255, 255, 255), rgba(206, 206, 206, 0.5))` | `--color-white-to-ash-gradient` | Used for a subtle linear fade, providing a soft transition effect. |

## Tokens — Typography

### Pragmatica Cond — Primary headings, navigation, prominent statements, and general UI labels. Its condensed form and tight letter-spacing create a sharp, efficient aesthetic. · `--font-pragmatica-cond`
- **Substitute:** Open Sans Condensed
- **Weights:** 400
- **Sizes:** 14px, 16px, 20px, 32px, 62px
- **Line height:** 0.90, 1.00, 1.05, 1.10, 1.43
- **Letter spacing:** -0.02em
- **Role:** Primary headings, navigation, prominent statements, and general UI labels. Its condensed form and tight letter-spacing create a sharp, efficient aesthetic.

### Pragmatica — Secondary headings and larger body text blocks where slightly more breath is needed compared to Pragmatica Cond. · `--font-pragmatica`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 15px, 24px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.02em, -0.01em
- **Role:** Secondary headings and larger body text blocks where slightly more breath is needed compared to Pragmatica Cond.

### Roboto Mono — Body copy and informational text. The monospaced nature subtly reinforces a technical, code-adjacent brand identity. · `--font-roboto-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 11px, 14px
- **Line height:** 0.90, 1.00, 1.10, 1.20
- **Letter spacing:** -0.02em
- **Role:** Body copy and informational text. The monospaced nature subtly reinforces a technical, code-adjacent brand identity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.1 | -0.22px | `--text-caption` |
| body-sm | 14px | 1 | -0.28px | `--text-body-sm` |
| heading | 20px | 1.05 | -0.4px | `--text-heading` |
| heading-lg | 24px | 1.2 | -0.24px | `--text-heading-lg` |
| display | 32px | 1.1 | -0.64px | `--text-display` |
| display-lg | 62px | 1.43 | -1.24px | `--text-display-lg` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 1440px |
| subtle | 4px |
| buttons | 1440px |
| general | 10px |

### Layout

- **Section gap:** 48px
- **Element gap:** 4px

## Components

### Ghost Button
**Role:** Primary Action

Transparent background, Pure White text, Pure White 1px border. Extremely large 1440px border-radius for a pill shape. Padding 10px vertical, 18px horizontal. Uses Pragmatica Cond 400.

### Circular Badge
**Role:** Informational Tag

Transparent background, Pure White text. Extremely large 1440px border-radius. Padding 5px vertical, 11px horizontal. Uses Pragmatica Cond 400.

### Monochrome Badge
**Role:** Neutral Tag

Steel Gray background, Deep Charcoal text. Extremely large 1440px border-radius. Padding 7px vertical, 10px horizontal. Uses Pragmatica Cond 400.

### Navigation Link
**Role:** Primary Navigation

Pure White text. Uses Pragmatica Cond 400 at 14px with -0.02em letter-spacing. Minimal padding around text.

## Do's and Don'ts

### Do
- Prioritize high contrast text-on-dark backgrounds using Pure White (#FFFFFF) text on Deep Charcoal (#0B0B0B) or Absolute Black (#000000).
- Use pill-shaped radii (1440px) for all buttons and badges to create a distinct, modern form.
- Apply -0.02em letter-spacing to all text elements using Pragmatica Cond for a uniform, crisp typographic texture.
- Maintain generous internal padding of 10px vertical and 18px horizontal for buttons, and 5-7px vertical, 10-11px horizontal for badges.
- Reserve Subtle Orange (#CC6437) for extremely limited, high-impact accent moments, such as subtle borders or interactive states, to maximize its effect.

### Don't
- Do not introduce additional chromatic colors; the palette is strictly monochrome with a single, subtle orange accent.
- Avoid using box-shadows or drop-shadows for elevation; rely on background color changes from Deep Charcoal to Warm Graphite.
- Do not vary letter-spacing for Pragmatica Cond; it rigidly adheres to -0.02em.
- Do not use conventional square or slightly rounded corners; elements should either be perfectly sharp or pill-shaped (1440px radius).
- Avoid decorative imagery or large photography; rely on abstract graphics and a minimal UI approach.

## Elevation

This design intentionally avoids all traditional drop shadows for elevation. Instead, depth and hierarchy are established solely through subtle shifts in background colors: from Absolute Black to Deep Charcoal to Warm Graphite. This creates a layered, recessed effect, as if UI elements are embedded into distinct planes of a dark, machined surface, maintaining a flat yet textured aesthetic.

## Imagery

The visual language is abstract and conceptual. It predominantly features blurred, out-of-focus light flares and bokeh effects against a dark background, evoking a sense of depth, atmosphere, and advanced technology without being explicit. There are no conventional photographs or detailed illustrations. Product representation is limited to minimalist, iconic renderings of the brand's star-shaped logo, often with glossy or reflective finishes. Icons are outlines, leveraging the Pure White on dark contrast. The density is extremely low, with imagery serving as decorative atmosphere rather than explanatory content, enhancing the perception of a sophisticated, almost mysterious, high-tech entity.

## Layout

The page primarily uses a full-bleed dark background, creating an expansive, borderless feel. The hero section is full-screen, featuring the brand logo centrally over the abstract, atmospheric background, with minimal surrounding text. Content sections are primarily centered, with a strong emphasis on large, singular text blocks or simple two-column arrangements that alternate textual explanations with subtle graphic elements. There's no immediately apparent grid for complex content, favoring a stacked, spacious approach. Navigation is minimal, consisting of top-left and top-right ghost buttons. Vertical spacing between content blocks is generous, providing significant breathing room and contributing to the overall sense of minimalist luxury.

## Agent Prompt Guide

### Quick Color Reference
- Text: #FFFFFF
- Background: #0B0B0B
- CTA: #FFFFFF (border/text on transparent background)
- Border: #FFFFFF
- Accent: #CC6437

### 3-5 Example Component Prompts
1. Create a Hero Section: Full-bleed background with abstract blurred light effect. Center the main brand logo (white outline). Below it, display the `display-lg` headline 'CIRIDAE' in Pure White (#FFFFFF), Pragmatica Cond 400, 62px, 1.43 lineHeight, -1.24px letterSpacing. Add a 'START NOW' ghost button (Pure White border and text, 1440px radius, 10px vertical 18px horizontal padding) in the top left, and a 'MENU' ghost button (Pure White border and text, 1440px radius, 10px vertical 18px horizontal padding) in the top right.
2. Create a feature block: Warm Graphite (#272A2A) background with 48px vertical sectionGap. Display a `heading` 'WORKFLOW REDESIGN' in Pure White (#FFFFFF), Pragmatica Cond 400, 20px, 1.05 lineHeight, -0.4px letterSpacing. Below it, add body text 'We map how work... end-to-end.' in Pure White (#FFFFFF), Roboto Mono 400, 14px, 1.0 lineHeight, -0.28px letterSpacing. Ensure ample 20px horizontal padding.
3. Design a Call-to-Action button: 'EXPLORE ALL' text in Pure White (#FFFFFF), Pragmatica Cond 400, 14px, 0.90 lineHeight, -0.28px letterSpacing. Transparent background, 1px Pure White (#FFFFFF) border, 1440px border-radius, 10px vertical and 18px horizontal padding. The element gap around it should be 4px.
4. Create a small informational badge: 'NEW' text in Pure White (#FFFFFF), Pragmatica Cond 400, 14px, 0.9 lineHeight, -0.28px letterSpacing. Transparent background, 1440px border-radius, 5px vertical and 11px horizontal padding.

## Similar Brands

- **Anthropic** — Monochromatic dark theme, emphasis on text as primary UI element, minimalist abstract background imagery.
- **Linear** — High-contrast dark mode, precise typography with careful letter-spacing, and a focus on clean, functional UI over decorative elements.
- **Supabase** — Clear distinction between foreground and background through high contrast, use of monospaced fonts for code-like precision, and a subdued aesthetic.
- **Vercel** — Dark UI, emphasis on typography and negative space, and modern, sleek interactive components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-black: #000000;
  --color-deep-charcoal: #0B0B0B;
  --color-warm-graphite: #272A2A;
  --color-pure-white: #FFFFFF;
  --color-ash-gray: #CECECE;
  --color-steel-gray: #858585;
  --color-subtle-orange: #CC6437;
  --color-white-to-ash-gradient: #FFFFFF;
  --gradient-white-to-ash-gradient: linear-gradient(rgb(255, 255, 255), rgba(206, 206, 206, 0.5));

  /* Typography — Font Families */
  --font-pragmatica-cond: 'Pragmatica Cond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pragmatica: 'Pragmatica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.1;
  --tracking-caption: -0.22px;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: -0.28px;
  --text-heading: 20px;
  --leading-heading: 1.05;
  --tracking-heading: -0.4px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 32px;
  --leading-display: 1.1;
  --tracking-display: -0.64px;
  --text-display-lg: 62px;
  --leading-display-lg: 1.43;
  --tracking-display-lg: -1.24px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 48px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-badges: 1440px;
  --radius-subtle: 4px;
  --radius-buttons: 1440px;
  --radius-general: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-black: #000000;
  --color-deep-charcoal: #0B0B0B;
  --color-warm-graphite: #272A2A;
  --color-pure-white: #FFFFFF;
  --color-ash-gray: #CECECE;
  --color-steel-gray: #858585;
  --color-subtle-orange: #CC6437;
  --color-white-to-ash-gradient: #FFFFFF;

  /* Typography */
  --font-pragmatica-cond: 'Pragmatica Cond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pragmatica: 'Pragmatica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.1;
  --tracking-caption: -0.22px;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: -0.28px;
  --text-heading: 20px;
  --leading-heading: 1.05;
  --tracking-heading: -0.4px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 32px;
  --leading-display: 1.1;
  --tracking-display: -0.64px;
  --text-display-lg: 62px;
  --leading-display-lg: 1.43;
  --tracking-display-lg: -1.24px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-full: 1440px;
}
```
