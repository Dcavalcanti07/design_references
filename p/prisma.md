# Prisma — Style Reference
> Architectural blueprint on white marble. Light, precise structures with sharp accents.

**Theme:** light

The Prisma design system evokes the precision of a high-performance developer tool. Predominantly achromatic surfaces in shades of cool gray and crisp white create an environment of focus and clarity. A vibrant teal (#14B8A6) acts as a singular, sharp accent, drawing attention to critical actions and active states. Typography is distinct, with a custom geometric sans-serif for headlines that conveys technical authority, complemented by a highly legible system font for body text.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, primary button text. |
| Ghost Gray | `#f3f4f6` | `--color-ghost-gray` | Secondary button backgrounds, navigation elements. |
| Border Frost | `#e2e8f0` | `--color-border-frost` | All borders, separators, and subtle outlines for UI elements. |
| Charcoal Black | `#111827` | `--color-charcoal-black` | Primary headings, prominent body text, providing strong contrast. |
| Obsidian Text | `#1d242f` | `--color-obsidian-text` | General text, secondary headings, card foregrounds — a slightly lighter black than Charcoal Black for softer impact. |
| Muted Stone | `#6b7280` | `--color-muted-stone` | Support text, descriptions, inactive states. |
| Soft Stone | `#718096` | `--color-soft-stone` | Subtle button text, icons requiring lower prominence. |
| Subtle Ash | `#9ca3af` | `--color-subtle-ash` | Subtle decorative elements, less important text. |
| Prisma Teal | `#14b8a6` | `--color-prisma-teal` | Primary call-to-action buttons, active navigation indicators, key interactive elements — signals action and importance vividly. |
| Deep Teal | `#0d9488` | `--color-deep-teal` | Link states, hover effects on brand elements, fills for icons requiring emphasis. |
| Teal Sky Gradient | `linear-gradient(rgb(13, 148, 136) 0%, rgb(255, 255, 255) 100%)` | `--color-teal-sky-gradient` | Background for specific hero or feature sections to create a sense of depth and modernity. |

## Tokens — Typography

### Inter — Primary UI font for body text, navigation, buttons, and detailed information. Its subtle variability in line-height and letter-spacing across sizes is crucial for readability in dense interfaces. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 375, 400, 500, 600, 700
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 22px
- **Line height:** 1.10-1.50
- **Letter spacing:** 0.02em - 0.033em
- **OpenType features:** `"cv01" on, "cv02" on, "cv06" on, "cv07" on, "cv08" on, "cv10" on`
- **Role:** Primary UI font for body text, navigation, buttons, and detailed information. Its subtle variability in line-height and letter-spacing across sizes is crucial for readability in dense interfaces.

### Mona Sans VF — Display font for headings and prominent calls-to-action. The generous letter-spacing at larger sizes gives it an open, authoritative feel, reinforcing a modern, technical aesthetic. · `--font-mona-sans-vf`
- **Substitute:** Arial, sans-serif
- **Weights:** 400, 650, 700, 900
- **Sizes:** 16px, 18px, 24px, 30px, 36px, 40px, 64px
- **Line height:** 1.13-1.56
- **Letter spacing:** 0.1em
- **OpenType features:** `"ss01" on, "ss02" on, "ss05" on, "ss06" on`
- **Role:** Display font for headings and prominent calls-to-action. The generous letter-spacing at larger sizes gives it an open, authoritative feel, reinforcing a modern, technical aesthetic.

### Mona Sans Mono VF — Used for code snippets and technical commands within UI elements, maintaining perfect alignment and clarity for developer-focused content. · `--font-mona-sans-mono-vf`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **OpenType features:** `"ss01" on, "ss02" on, "ss05" on, "ss06" on`
- **Role:** Used for code snippets and technical commands within UI elements, maintaining perfect alignment and clarity for developer-focused content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.45 | 0.033px | `--text-caption` |
| body | 16px | 1.5 | 0.02px | `--text-body` |
| subheading | 18px | 1.4 | 0.02px | `--text-subheading` |
| heading | 24px | 1.33 | 0.1px | `--text-heading` |
| heading-lg | 40px | 1.2 | 0.1px | `--text-heading-lg` |
| display | 64px | 1.13 | 0.1px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 10px |
| default | 6px |
| buttonPill | 1.67772e+07px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.04) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Call to action

Solid Prisma Teal (#14B8A6) background, Cloud White (#FFFFFF) text. 6px border-radius, 16px horizontal padding, 0px vertical padding. Text uses Inter font, weight 500.

### Secondary Ghost Button
**Role:** Secondary action button

Transparent background (rgba(0,0,0,0)), Obsidian Text (#1D242F), with a Border Frost (#E2E8F0) outline. 6px border-radius, 10px horizontal padding, 6px vertical padding. Text uses Inter font.

### Subtle Background Button
**Role:** Tertiary action button

Ghost Gray (#F3F4F6) background, Charcoal Black (#111827) text. 6px border-radius, 16px horizontal padding, 0px vertical padding. Text uses Inter font.

### Pill Ghost Button
**Role:** Small, less prominent actions or tags

Transparent background (rgba(0,0,0,0)), Soft Stone (#718096) text. Extremely high border-radius (1.67772e+07px) creating a pill shape. 6px all-around padding. Text uses Inter font.

### Feature Card
**Role:** Content container

Cloud White (#FFFFFF) background, Border Frost (#E2E8F0) border. 6px border-radius. 16px padding on all sides. Shadow: rgba(0,0,0,0.04) 0px 1px 2px 0px.

### Code Snippet Button
**Role:** Execute or copy technical commands

Transparent background with a Border Frost (#E2E8F0) border. Text is Mona Sans Mono (16px, weight 400). Displays command line syntax.

### Product Navigation Link
**Role:** Top navigation item

Obsidian Text (#1D242F) with Inter font, weight 500. Underlined on hover, transitions to Deep Teal (#0D9488).

## Do's and Don'ts

### Do
- Use Border Frost (#E2E8F0) for all component borders and separators.
- Apply 6px border-radius as the default for most interactive elements and cards, reserving 10px for larger contextual elements.
- Prioritize Prisma Teal (#14B8A6) exclusively for primary calls to action to maintain its impact.
- Employ Mona Sans VF for all primary headings, ensuring a letter-spacing of 0.1em at display sizes for distinctiveness.
- Maintain a clear visual hierarchy by using the progression of Charcoal Black (#111827) for headings, Obsidian Text (#1D242F) for body, and Muted Stone (#6B7280) for secondary details.
- Space elements using multiples of 4px as a base unit, with `elementGap` at 4px, `cardPadding` at 16px, and `sectionGap` at 48px to maintain density and rhythm.
- Use Mona Sans Mono VF (16px, weight 400) for all code-related content, including inline snippets and code block buttons.

### Don't
- Do not introduce new chromatic colors outside of the teal brand palette in interactive contexts.
- Avoid shadows other than rgba(0,0,0,0.04) 0px 1px 2px 0px; elevation is primarily achieved through background color shifts and borders.
- Do not deviate from the specified letter-spacing for Mona Sans VF headings; the 0.1em value is integral to its character.
- Do not use highly rounded forms (like the pill shape) for anything other than small, tertiary buttons or tags.
- Avoid using bold or semi-bold weights for body text; rely on font size and color for emphasis with Inter font.
- Do not use generic system fonts for code snippets; Mona Sans Mono VF ensures consistency and readability for technical content.

## Elevation

- **Card:** `rgba(0, 0, 0, 0.04) 0px 1px 2px 0px`

## Imagery

The visual language for imagery is primarily focused on product screenshots and custom abstract graphics. Text-heavy UI screenshots of the Prisma Studio and code editors are common, presented within contained, sharp-cornered modules with a subtle gray border. Abstract graphics, often in shades of light blue or teal, appear as background elements or subtle decorative flourishes, such as speckles in the hero section or subtle geometric shapes. Icons are typically outlined or filled in a mono-color (either black or Prisma Teal), appearing functional and descriptive rather than purely decorative. The overall density is balanced, with imagery serving explanatory or demonstrative roles alongside ample whitespace.

## Layout

The page uses a centered, max-width layout for most content, with a consistent internal padding. The hero section is full-width with a background gradient, but its content is centrally aligned. Sections generally alternate between centered stacks of content and common left-text/right-image (or vice-versa) patterns. Feature sections often use 3-column card grids. There's a consistent vertical rhythm with sections separated by 'sectionGap' (48px) and internal elements by 'elementGap' (4px). The navigation is a sticky top bar, providing persistent access while scrolling.

## Agent Prompt Guide

### Quick Color Reference
- Text: #1D242F (Obsidian Text)
- Background: #FFFFFF (Cloud White)
- CTA: #14B8A6 (Prisma Teal)
- Border: #E2E8F0 (Border Frost)
- Accent: #0D9488 (Deep Teal)

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: background Prisma Teal (#14B8A6), text Cloud White (#FFFFFF), 6px border-radius, 16px horizontal padding, 0px vertical padding. Text is Inter, weight 500.
2. Design a feature card: background Cloud White (#FFFFFF), border Border Frost (#E2E8F0), 6px border-radius, shadow rgba(0,0,0,0.04) 0px 1px 2px 0px, 16px internal padding. Heading is Mona Sans VF 24px, weight 700, letter-spacing 0.1em, color Charcoal Black (#111827). Body text is Inter 16px, weight 400, color Obsidian Text (#1D242F).
3. Generate a code snippet button: transparent background, Border Frost (#E2E8F0) border. Text uses Mona Sans Mono VF 16px, weight 400, color Obsidian Text (#1D242F). Include a 'copy to clipboard' icon using Font Awesome 7 Pro 16px, weight 400.
4. Build a hero section headline: 'Postgres, perfectly managed.' using Mona Sans VF 64px, weight 900, letter-spacing 0.1em, color Charcoal Black (#111827). Subtext below it: Inter 18px, weight 400, color Muted Stone (#6B7280).

## Similar Brands

- **Vercel** — Shares a clean, developer-centric aesthetic with strong use of system fonts, subtle grays, and a single vibrant accent color for CTAs.
- **Supabase** — Features a similar light theme, crisp typography, and strategic use of a distinct brand color (green) to highlight interactive elements and status.
- **Stripe** — Exemplifies a similar balance of complex technical information presented with clarity, using a well-defined type scale, subtle shadows, and structured, airy layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-white: #ffffff;
  --color-ghost-gray: #f3f4f6;
  --color-border-frost: #e2e8f0;
  --color-charcoal-black: #111827;
  --color-obsidian-text: #1d242f;
  --color-muted-stone: #6b7280;
  --color-soft-stone: #718096;
  --color-subtle-ash: #9ca3af;
  --color-prisma-teal: #14b8a6;
  --color-deep-teal: #0d9488;
  --color-teal-sky-gradient: #0d9488;
  --gradient-teal-sky-gradient: linear-gradient(rgb(13, 148, 136) 0%, rgb(255, 255, 255) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans-vf: 'Mona Sans VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans-mono-vf: 'Mona Sans Mono VF', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.033px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.02px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.1px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.1px;
  --text-display: 64px;
  --leading-display: 1.13;
  --tracking-display: 0.1px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w375: 375;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-w650: 650;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-104: 104px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-large: 10px;
  --radius-default: 6px;
  --radius-buttonpill: 1.67772e+07px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-white: #ffffff;
  --color-ghost-gray: #f3f4f6;
  --color-border-frost: #e2e8f0;
  --color-charcoal-black: #111827;
  --color-obsidian-text: #1d242f;
  --color-muted-stone: #6b7280;
  --color-soft-stone: #718096;
  --color-subtle-ash: #9ca3af;
  --color-prisma-teal: #14b8a6;
  --color-deep-teal: #0d9488;
  --color-teal-sky-gradient: #0d9488;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans-vf: 'Mona Sans VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans-mono-vf: 'Mona Sans Mono VF', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.033px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.02px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.1px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.1px;
  --text-display: 64px;
  --leading-display: 1.13;
  --tracking-display: 0.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 1px 2px 0px;
}
```
