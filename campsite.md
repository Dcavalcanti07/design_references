# Campsite — Style Reference
> Whiteboard with sticky notes — clean, organized, and quietly structured.

**Theme:** light

Campsite presents a pragmatic, focused interface, employing a bright white canvas with layered surfaces that subtly differentiate content. Typography is compact and precise, maintaining clarity in a dense information environment. A controlled palette of neutral grays is punctuated by a functional vivid green and contextual reds/yellows, guiding attention without visual clutter. Components favor soft, rounded forms and minimal elevation, suggesting approachable utility rather than heavy ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#171717` | `--color-ink-black` | Primary text, headings, icons, primary UI elements, dark surface background (limited use in cards) |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, primary card surfaces, ghost button text, essential interface backgrounds |
| Pale Gray | `#f5f5f5` | `--color-pale-gray` | Secondary card surfaces, muted icon fills, subtle background accents |
| Cream Canvas | `#fffdf9` | `--color-cream-canvas` | Dominant page background, base canvas |
| Ash Gray | `#a3a3a3` | `--color-ash-gray` | Muted body text, decorative fills |
| Off White | `#f0f0f0` | `--color-off-white` | Subtle background accents, dividers |
| Slate Gray | `#737373` | `--color-slate-gray` | Secondary text, link text, muted icon fills |
| Charcoal Text | `#525252` | `--color-charcoal-text` | Tertiary text, less prominent UI elements |
| Forest Green | `#22c55e` | `--color-forest-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Warning Red | `#ef4444` | `--color-warning-red` | Red action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Harvest Gold | `#fef3c7` | `--color-harvest-gold` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Warm Umber | `#451a03` | `--color-warm-umber` | Informational text, specific inline highlights, subtle accent text in content blocks |

## Tokens — Typography

### Inter — Primary typeface for all text content, providing a functional, modern feel. The varied letter spacing brings precision to larger display sizes and legibility to smaller body text. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 20px, 22px, 29px, 58px
- **Line height:** 1.00, 1.20, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63, 1.80
- **Letter spacing:** -0.0310em, -0.0180em, -0.0170em, 0.0250em
- **Role:** Primary typeface for all text content, providing a functional, modern feel. The varied letter spacing brings precision to larger display sizes and legibility to smaller body text.

### ui-monospace — Applied to specialized content like code snippets or fixed-width data where character alignment is critical. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400, 600
- **Sizes:** 12px
- **Line height:** 1.00
- **Role:** Applied to specialized content like code snippets or fixed-width data where character alignment is critical.

### emoji — Used for displaying emojis consistently where they appear inline with text. · `--font-emoji`
- **Substitute:** sans-serif
- **Weights:** 500, 600
- **Sizes:** 12px, 14px
- **Line height:** 1.00
- **Role:** Used for displaying emojis consistently where they appear inline with text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.25px | `--text-caption` |
| body | 14px | 1.43 | 0.25px | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading | 29px | 1.2 | -0.49px | `--text-heading` |
| display | 58px | 1 | -1.8px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 12px |
| md | 8px |
| sm | 4px |
| none | 0px |
| circular | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.05) 0px 3px 6px -3px, rgba(0, 0, 0, 0.05)...` | `--shadow-sm` |
| subtle | `rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08)...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.32) 0px 0.5px 0px 0px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.1) 0px 0.5px 0px 0px inset, rgba(0, 0, 0,...` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Secondary action control

Transparent background with Ink Black text, 9999px circular radius, 10px horizontal padding, with a subtle border from rgba(0, 0, 0, 0.1).

### Subtle Gray Button
**Role:** Tertiary action control, tag

Pale Gray background with Ink Black text, a 6px radius, and 10px horizontal padding. The border is rgba(0, 0, 0, 0.1).

### Primary Action Button
**Role:** Call to action

Forest Green background with Arctic White text, 9999px circular radius, 10px horizontal padding. Provides clear visual emphasis for primary actions.

### Interactive Card Shadowed
**Role:** Container for actionable content

Arctic White background, 12px border radius, with a cascading shadow system: rgba(0, 0, 0, 0.05) 0px 3px 6px -3px, rgba(0, 0, 0, 0.05) 0px 2px 4px -2px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px, rgba(0, 0, 0, 0.05) 0px 1px 1px -1px, rgba(0, 0, 0, 0.05) 0px 1px 0px -1px.

### Secondary Surface Card
**Role:** Background for feature blocks or secondary content

Pale Gray background, 12px border radius, with 16px internal padding on all sides. Lacks elevation, creating a flat, distinct surface.

### L-Shape Card
**Role:** Content container with an asymmetric radius

Arctic White background, 8px 0px 0 radial corners, 0px 0px 0 non-radial, applying an elegant asymmetric cut. Features 16px padding and the standard cascading shadow.

### Standard Card
**Role:** Basic content container

Arctic White background, 8px border radius, with standard cascading shadow. No internal padding, for content that manages its own spacing.

## Do's and Don'ts

### Do
- Always use Cream Canvas (#fffdf9) as the base page background to maintain visual spaciousness.
- Apply Forest Green (#22c55e) exclusively for primary actions and success indicators to ensure their high functional prominence.
- Use Inter for all primary text content. Vary letter spacing per type scale role: -1.8px for display text, -0.49px for headings, and 0.25px for body text to optimize legibility.
- Encapsulate interactive content within cards using a 12px border radius and the cascading shadow system for a subtle lift.
- Employ circular radius (9999px) for all button and tag elements to convey a friendly, approachable interaction point.
- Maintain a compact element spacing of 8px between sequential UI items where density permits.
- Utilize Pale Gray (#f5f5f5) for secondary background surfaces that require distinction without strong elevation.

### Don't
- Do not introduce additional vibrant colors; rely on Forest Green, Warning Red, and Harvest Gold for all chromatic needs.
- Avoid heavy drop shadows or strong gradients; surfaces should primarily be differentiated through background color and subtle elevation.
- Do not use generic system fonts; Inter is the established typeface for its specific character and legibility at various sizes.
- Prevent excessive spacing between adjacent elements; the design emphasizes a compact information density with an 8px base unit.
- Do not apply sharp corners to interactive elements; all buttons and tags must use a 9999px circular radius.
- Do not use full-width sections that break the contained layout unless specifically designed as a hero or decorative element.
- Avoid using Cream Canvas (#fffdf9) for interactive elements; it is reserved for the background plane.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cream Canvas | `#fffdf9` | Dominant page background |
| 1 | Arctic White | `#ffffff` | Primary card surfaces, base for elevated components |
| 2 | Pale Gray | `#f5f5f5` | Secondary card surfaces, feature backgrounds, subtle textural differentiation |

## Elevation

- **Interactive Card:** `rgba(0, 0, 0, 0.05) 0px 3px 6px -3px, rgba(0, 0, 0, 0.05) 0px 2px 4px -2px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px, rgba(0, 0, 0, 0.05) 0px 1px 1px -1px, rgba(0, 0, 0, 0.05) 0px 1px 0px -1px`
- **Button/Link Hover:** `rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 2px 2px -1px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgb(255, 255, 255) 0px 1px 0px 0px inset, rgb(255, 255, 255) 0px 1px 2px 1px inset, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px inset`

## Imagery

The site's primary imagery consists of product screenshots featuring the Campsite application's interface. These are often presented flush within content areas, occasionally with an asymmetric top-left corner radius of 8px. Photography is minimal, appearing incidentally within product screenshot content rather than as standalone hero images. Abstract graphics, characterized by vibrant, organic splashes of orange and red, are used sparingly as decorative accents, most notably peeking from sidebars in the product UI presentation. Icons are outlined, simple, and monochrome, adhering to a functional, rather than decorative, role. The overall density of imagery is balanced, with UI screenshots serving an explanatory function, integrated into text-dominant layouts.

## Layout

The page primarily uses a contained layout with a maximum content width centered on the screen. The hero section is full-width, featuring a prominent centered headline over a clean background. Content sections follow a rhythm of consistent vertical spacing (48px section gap). Content is generally arranged in two-column text-left/visual-right patterns or as centered stacks of content cards. Card grids are used for features, suggesting a column-based system. The design is compact to semi-spacious, promoting information density without feeling cramped. Navigation is handled by a sticky top bar.

## Agent Prompt Guide

Quick Color Reference:
text: #171717
background: #fffdf9
border: rgba(0, 0, 0, 0.1)
accent: #451a03
primary action: #22c55e (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #22c55e background, #171717 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Arctic White (#ffffff) background, 12px border radius, apply the main cascading shadow system, with 16px internal padding, using Ink Black (#171717) for its headline (Inter 29px weight 600, letter-spacing -0.49px) and Slate Gray (#737373) for its body text (Inter 14px weight 400).
3. Generate a ghost button: Transparent background, Ink Black (#171717) text, 9999px circular radius, 10px horizontal padding, with a subtle border from rgba(0, 0, 0, 0.1), Inter font weight 400, 14px size.
4. Create a secondary content card: Pale Gray (#f5f5f5) background, 12px border radius, 16px internal padding, no shadow.

## Similar Brands

- **Notion** — Monochrome product UI with subtle surface layering and functional accent colors.
- **Linear** — Clean, compact interface, strong focus on typography, and functional use of color for status/actions.
- **Superhuman** — High information density, precise typography, and a preference for light backgrounds with minimal elevation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #171717;
  --color-arctic-white: #ffffff;
  --color-pale-gray: #f5f5f5;
  --color-cream-canvas: #fffdf9;
  --color-ash-gray: #a3a3a3;
  --color-off-white: #f0f0f0;
  --color-slate-gray: #737373;
  --color-charcoal-text: #525252;
  --color-forest-green: #22c55e;
  --color-warning-red: #ef4444;
  --color-harvest-gold: #fef3c7;
  --color-warm-umber: #451a03;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-emoji: 'emoji', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.25px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.25px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --tracking-heading: -0.49px;
  --text-display: 58px;
  --leading-display: 1;
  --tracking-display: -1.8px;

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
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-lg: 12px;
  --radius-md: 8px;
  --radius-sm: 4px;
  --radius-none: 0px;
  --radius-circular: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 3px 6px -3px, rgba(0, 0, 0, 0.05) 0px 2px 4px -2px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px, rgba(0, 0, 0, 0.05) 0px 1px 1px -1px, rgba(0, 0, 0, 0.05) 0px 1px 0px -1px;
  --shadow-subtle: rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 2px 2px -1px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgb(255, 255, 255) 0px 1px 0px 0px inset, rgb(255, 255, 255) 0px 1px 2px 1px inset, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.32) 0px 0.5px 0px 0px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0.5px 0px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 12px 0px, rgba(0, 0, 0, 0.02) 0px 8px 20px 0px;

  /* Surfaces */
  --surface-cream-canvas: #fffdf9;
  --surface-arctic-white: #ffffff;
  --surface-pale-gray: #f5f5f5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #171717;
  --color-arctic-white: #ffffff;
  --color-pale-gray: #f5f5f5;
  --color-cream-canvas: #fffdf9;
  --color-ash-gray: #a3a3a3;
  --color-off-white: #f0f0f0;
  --color-slate-gray: #737373;
  --color-charcoal-text: #525252;
  --color-forest-green: #22c55e;
  --color-warning-red: #ef4444;
  --color-harvest-gold: #fef3c7;
  --color-warm-umber: #451a03;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-emoji: 'emoji', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.25px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.25px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --tracking-heading: -0.49px;
  --text-display: 58px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 3px 6px -3px, rgba(0, 0, 0, 0.05) 0px 2px 4px -2px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px, rgba(0, 0, 0, 0.05) 0px 1px 1px -1px, rgba(0, 0, 0, 0.05) 0px 1px 0px -1px;
  --shadow-subtle: rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 2px 2px -1px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgb(255, 255, 255) 0px 1px 0px 0px inset, rgb(255, 255, 255) 0px 1px 2px 1px inset, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.32) 0px 0.5px 0px 0px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0.5px 0px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 12px 0px, rgba(0, 0, 0, 0.02) 0px 8px 20px 0px;
}
```
