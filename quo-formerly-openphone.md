# Quo (formerly OpenPhone) — Style Reference
> High-contrast digital workspace.

**Theme:** light

Quo adopts a stark, high-contrast digital workspace aesthetic: a spacious white canvas punctuated by bold black typography and strategic use of a single vivid lime accent. The design feels direct and functional, leveraging strong visual hierarchy created by heavy black text and subtle, almost invisible UI elements. Components are lightweight with minimal borders, emphasizing content over chrome, and utilizing soft gray backgrounds for subtle differentiation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, headings, strong borders, filled button backgrounds, brand logo |
| Surface Gray | `#f7f6f5` | `--color-surface-gray` | Secondary surface backgrounds, subtle card backgrounds, soft button fills |
| Supporting Text Grey | `#4d4d4d` | `--color-supporting-text-grey` | Body text, secondary descriptive text |
| Subtle Border Gray | `#cccccc` | `--color-subtle-border-gray` | Hairline borders, dividers, disabled states |
| Dark Charcoal | `#0a0a0c` | `--color-dark-charcoal` | Deepest background for contrast, specialized text |
| Lime Accent | `#edfc47` | `--color-lime-accent` | Green decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |

## Tokens — Typography

### Inter — Body text, navigation, links, captions, small functional labels. A versatile workhorse for content, maintaining readability at all sizes. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.00, 1.20, 1.30, 1.50
- **Letter spacing:** normal
- **Role:** Body text, navigation, links, captions, small functional labels. A versatile workhorse for content, maintaining readability at all sizes.

### Roobert — Headlines, section titles, and prominent callouts. The specific 500 weight and tight letter-spacing create a confident, assertive tone without being overtly heavy. · `--font-roobert`
- **Substitute:** Arial
- **Weights:** 500
- **Sizes:** 20px, 24px, 40px, 48px, 56px, 64px, 88px
- **Line height:** 0.90, 1.10, 1.20
- **Letter spacing:** -0.0200em at large sizes, -0.0100em at smaller headline sizes
- **Role:** Headlines, section titles, and prominent callouts. The specific 500 weight and tight letter-spacing create a confident, assertive tone without being overtly heavy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.2 | -0.2px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.24px | `--text-heading-sm` |
| heading | 40px | 1.1 | -0.8px | `--text-heading` |
| heading-lg | 56px | 0.9 | -1.12px | `--text-heading-lg` |
| display | 88px | 0.9 | -1.76px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 100 | 100px | `--spacing-100` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 100px |
| cards | 10px |
| buttons | 6px |
| default | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.1) 0px 11px 17px -10px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action

Solid Ink Black (#000000) background with Canvas White (#ffffff) text. Features a 6px border radius and generous 16px horizontal/vertical padding. Dominant action element.

### Ghost Button
**Role:** Secondary action / navigation link

Transparent background with Ink Black (#000000) text and a 1px Ink Black (#000000) border. No border radius. Minimum 8px vertical and 16px horizontal padding.

### Soft Filled Button
**Role:** Light background action / tag

Surface Gray (#f7f6f5) background with Ink Black (#000000) text. Features a 10px border radius and 16px horizontal/vertical padding. Used for filters or less prominent actions.

### Default Card
**Role:** Content container

Transparent background, 10px border radius, no box shadow. 32px internal padding on all sides. Used for structured information blocks.

### Surface Accent Card
**Role:** Information display

Surface Gray (#f7f6f5) background, 10px border radius, no box shadow. No internal padding by default, allowing content to control spacing. Used for visually distinct content blocks.

### Elevated Tooltip Card
**Role:** Ephemeral information

Transparent background with a subtle shadow (rgba(0, 0, 0, 0.1) 0px 11px 17px -10px) and 10px border radius. Padding set to 24px vertical and 32px horizontal. Used for UI overlays or popups.

### Navigation Link
**Role:** Header navigation

Ink Black (#000000) text at 16px Inter 500 weight. Transparent background, no border, no padding or radius. Interactive but visually minimal.

### Subtle Badge
**Role:** Highlight label

Transparent background with Ink Black (#000000) text. No padding or radius. Used for small, unobtrusive labels.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#000000) for primary text and calls to action against Canvas White (#ffffff).
- Use Roobert 500 with tight letter-spacing for all headlines and impactful text, emphasizing confidence.
- Apply Surface Gray (#f7f6f5) for subtle background differentiation on cards and soft buttons, maintaining a muted base.
- Incorporate Lime Accent (#edfc47) sparingly for interactive elements, highlights, and decorative touches to provide energetic punctuation.
- Ensure generous internal padding of 32px for main content cards to create a spacious feel.
- Maintain a clear visual hierarchy with strong contrast between text and background, adhering to AAA accessibility standards where possible.
- Utilize 10px border radii for most containers and 6px for buttons, with 100px for pill-shaped elements like tags.

### Don't
- Avoid using multiple accent colors; rely on Lime Accent (#edfc47) as the sole chromatic highlight.
- Do not use heavy shadows or gradients; components should generally remain flat or subtly elevated with minimal box-shadows.
- Do not introduce complex background patterns; maintain large areas of Canvas White (#ffffff) or Surface Gray (#f7f6f5).
- Do not use generic system fonts for headlines; always default to Roobert 500 for brand consistency.
- Avoid excessive use of borders; elements should primarily rely on background color to define their boundaries.
- Do not use rounded corners larger than 10px for cards or smaller than 6px for active buttons.
- Do not clutter layouts; aim for comfortable density and clear visual separation with generous spacing.

## Elevation

This design system purposefully avoids heavy, pronounced shadows. The single detected shadow (rgba(0, 0, 0, 0.1) 0px 11px 17px -10px) is minimal and primarily used for ephemeral or overlay components like tooltips or modals. This choice reinforces a flat, direct, and efficient UI philosophy, where elements are differentiated by background color and strong typographic hierarchy rather than simulated depth, making interactions feel fast and unburdened.

## Imagery

The visual language for imagery is minimal and functional, primarily using product screenshots and software interface depictions. These are often flat, contained within subtle card-like structures with 10px rounded corners, or occasionally full-bleed to showcase the UI. Photography is absent. Illustrations are rare, but when present, they appear as simple, almost outlined or filled icons with a flat, geometric style (e.g., illustrated money stacks in the hero). Icons are typically outlined and monochrome, carrying a consistent stroke weight. Imagery serves an explanatory or product showcase role, focusing on functionality rather than atmosphere or branding, leading to a text-dominant layout with imagery providing visual anchors.

## Layout

The page adheres to a max-width of 1200px, with content centrally aligned. The hero section is full-width, featuring a prominent centered headline over a white background, occasionally with large, simple illustrative elements. The section rhythm is primarily continuous white space, occasionally broken by soft Surface Gray (#f7f6f5) background bands that seamlessly transition into the next feature block. Content is arranged in alternating text-left/image-right or text-right/image-left patterns, often within multi-column card grids (e.g., 2-column or 3-column feature setups). The layout is spacious with clear vertical separation between sections. Navigation consists of a simple top bar with primary links and prominent 'Log in' and 'Try for free' ghost and filled buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #cccccc
accent: #edfc47
primary action: #000000 (filled action)

Example Component Prompts:
Create a Primary Filled Button: solid Ink Black (#000000) background, Canvas White (#ffffff) text, Roobert 500 at 16px, 6px border radius, 16px vertical and horizontal padding.
Create a Default Card: Canvas White (#ffffff) background, 10px border radius, no shadow, 32px internal padding on all sides.
Create a Navigation Link: Ink Black (#000000) text, Inter 500 at 16px, no background, no border, no padding.
Create a Hero Headline: 'Money is on the Line' in Ink Black (#000000), Roobert 500 at 88px, letter-spacing -1.76px, centered on a Canvas White (#ffffff) background.

## Similar Brands

- **Superhuman** — High-contrast text on white surfaces, minimal UI chrome, dark-colored primary actions, and a focus on speed.
- **Linear** — Clean, almost monochrome interface, strong typographic hierarchy, subtle card dividers, and a focus on efficient interaction through lightweight components.
- **Notion** — White canvas, emphasis on content, soft background grays for subtle UI elements, and a system built around flexible blocks.
- **Figma** — Dominant white canvas, high-contrast text, clear functional typography, and subtle use of background colors for interactive states.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-surface-gray: #f7f6f5;
  --color-supporting-text-grey: #4d4d4d;
  --color-subtle-border-gray: #cccccc;
  --color-dark-charcoal: #0a0a0c;
  --color-lime-accent: #edfc47;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.12px;
  --text-display: 88px;
  --leading-display: 0.9;
  --tracking-display: -1.76px;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-tags: 100px;
  --radius-cards: 10px;
  --radius-buttons: 6px;
  --radius-default: 10px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 11px 17px -10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-surface-gray: #f7f6f5;
  --color-supporting-text-grey: #4d4d4d;
  --color-subtle-border-gray: #cccccc;
  --color-dark-charcoal: #0a0a0c;
  --color-lime-accent: #edfc47;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.12px;
  --text-display: 88px;
  --leading-display: 0.9;
  --tracking-display: -1.76px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 11px 17px -10px;
}
```
