# LE CAMP — Style Reference
> Modern Mountaineering Ascent: Crisp white canvas, bold typography, and sharp red accents guide the upward journey.

**Theme:** light

LE CAMP employs a 'modern mountaineering' aesthetic, blending a clean, spacious white canvas with bold, confident typography and a striking red accent. The design feels grounded yet aspirational, using strong contrasts and precise spacing to create a sense of clear direction and focused interaction. Visual elements, particularly the distinct badges, leverage outlined forms and vivid color accents for impact, reinforcing a brand identity that is both structured and dynamic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight | `#000000` | `--color-midnight` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, card text, ghost button text and borders, general UI elements |
| Ash | `#767676` | `--color-ash` | Input borders, placeholder text |
| Summit Red | `#fe3a3a` | `--color-summit-red` | CTA buttons, primary interactive elements, brand accents. This vivid red serves as the focal point, signaling key actions and brand presence |

## Tokens — Typography

### Agrandir — Headlines and prominent display text. The use of a custom font with a light weight (350) for headlines against a strong 600 weight for subheadings creates a unique blend of understated authority and clear emphasis. · `--font-agrandir`
- **Substitute:** Montserrat
- **Weights:** 350, 600
- **Sizes:** 18px, 26px, 90px
- **Line height:** 1.00, 1.20
- **Role:** Headlines and prominent display text. The use of a custom font with a light weight (350) for headlines against a strong 600 weight for subheadings creates a unique blend of understated authority and clear emphasis.

### DM Sans — Body text, navigation, general UI elements, and button labels. Its clean and legible structure ensures clarity across various content types. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.30, 1.40
- **Role:** Body text, navigation, general UI elements, and button labels. Its clean and legible structure ensures clarity across various content types.

### DM Mono — Small functional text like captions or specific nav items. The monospace character adds a technical, precise feel, reinforced by subtle letter spacing. · `--font-dm-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 10px, 14px
- **Line height:** 1.30
- **Letter spacing:** 0.0400em
- **Role:** Small functional text like captions or specific nav items. The monospace character adds a technical, precise feel, reinforced by subtle letter spacing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.3 | 0.04px | `--text-caption` |
| body | 14px | 1.3 | — | `--text-body` |
| body-lg | 16px | 1.4 | — | `--text-body-lg` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading | 26px | 1 | — | `--text-heading` |
| display | 90px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| buttons | 10px |
| navItems | 10px |
| pillButtons | 35px |

### Layout

- **Section gap:** 40px
- **Card padding:** 60px
- **Element gap:** 5px

## Components

### Primary Action Button
**Role:** Filled button indicating primary call to action.

Background: Summit Red (#fe3a3a), Text: Canvas (#ffffff), Border Radius: 10px, Padding: 10px vertical, 20px horizontal.

### Ghost Header Button
**Role:** Outlined button used in navigation or secondary actions.

Background: transparent, Text: Canvas (#ffffff), Border: 1px solid Canvas (#ffffff), Border Radius: 0px.

### Pill Ghost Button
**Role:** Minimalist interactive element with a pill-shaped outline.

Background: transparent, Text: Midnight (#000000), Border: 1px solid Midnight (#000000), Border Radius: 35px, Padding: 0px.

### Monochrome Card
**Role:** Content container for features or programs.

Background: Midnight (#000000), Border Radius: 20px, Padding: 60px all sides.

### Text Input
**Role:** Basic text input field.

Background: transparent, Text: Midnight (#000000), Border Bottom: 1px solid Ash (#767676), Border Radius: 0px.

## Do's and Don'ts

### Do
- Always use 'Agrandir' 350 for main headings to achieve a light, confident presence.
- Apply Summit Red (#fe3a3a) only to primary action buttons and meaningful accents, never for decorative purposes.
- Maintain generous padding of 60px for all card components to emphasize content.
- Use DM Sans 400 for all body text and UI labels, ensuring clear hierarchy and readability.
- Employ a 10px border-radius for all standard buttons and navigation items and 20px for cards to maintain soft but defined edges.
- Utilize DM Mono 400 with its distinct letter spacing (0.0400em) for small, functional text where a technical aesthetic is desired.
- Ensure a 40px vertical gap between main sections to provide comfortable visual breaks.

### Don't
- Do not introduce additional bold or semibold weights for DM Sans; stick to 400 for consistent text hierarchy.
- Avoid using decorative shadows; the design relies on flat surfaces and strong color contrasts for depth.
- Do not vary letter spacing for DM Sans or Agrandir; reserve it exclusively for DM Mono.
- Never use Summit Red (#fe3a3a) for text unless it's on a Canvas (#ffffff) background for primary CTAs.
- Do not apply rounded corners greater than 20px to cards or less than 10px to buttons, unless it's a specific pill button.
- Avoid using any gradients; the aesthetic is built on solid colors and strong contrasts.
- Do not introduce new neutral colors beyond Midnight, Canvas, and Ash; work within this established grayscale for UI elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Primary page background and default content surface. |
| 1 | Midnight Card | `#000000` | Elevated content containers for programs and features, providing strong contrast against the Canvas background. |

## Imagery

The site uses a mix of photographic backgrounds and highly stylized, outlined badge-like illustrations. Photography is dark-toned and atmospheric (e.g., lake and mountains), serving as a full-bleed backdrop in the hero section, creating mood. Illustrations are distinctive, featuring bold, color-outlined shapes (red, blue, white) against a black fill, acting as key branding elements or program identifiers. Icons are simple, outlined, and monochromatic, maintaining a clean UI without overwhelming with detail. Imagery acts both as atmospheric decor and descriptive content, with a clear separation between immersive photography and structured, graphical information.

## Layout

The page typically uses a max-width contained layout except for the hero section which is full-bleed. The hero features a large, centered headline over a dark photographic background, flanked by program badges. Subsequent sections alternate between full-width content blocks and contained layouts. Content is generally arranged in logical right/left visual pairings or centered stacks. Vertical rhythm is established through consistent section gaps, creating a spacious and comfortable density. Main navigation is a fixed top bar with a 'Contact' button and a prominent 'Menu' toggle, remaining mostly functional and out of the way.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #000000
- accent: #fe3a3a
- primary action: #fe3a3a (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #fe3a3a background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a monochrome card: Background Midnight (#000000), Border Radius 20px, Padding 60px. Headline needs Agrandir 600, 26px, Canvas (#ffffff), lineHeight 1.0. Body text needs DM Sans 400, 16px, Canvas (#ffffff), lineHeight 1.3.
3. Make a Ghost Header Button: Background transparent, Text Canvas (#ffffff), Border 1px solid Canvas (#ffffff), Border Radius 0px, Padding 10px vertical and 20px horizontal.
4. Create a hero section headline: Agrandir 350, 90px, Canvas (#ffffff), lineHeight 1.0. This should be centered over a dark image background.
5. Implement a text input field: Background transparent, Text Midnight (#000000), Border Bottom 1px solid Ash (#767676), Border Radius 0px, Font DM Sans 400, 16px.

## Similar Brands

- **Figma** — Uses a similar approach of a clean, bright canvas with a distinct, vivid accent color (purple for Figma, red for LE CAMP) to highlight interactive elements.
- **Linear** — Shares a focus on structured, compact UI with sharp contrasts and minimal decorative elements, creating a sense of efficiency and directness.
- **Asana** — Employs a white background with strong, functional typography and a clear, singular brand color to guide user actions and hierarchy.
- **Anthropic** — Combines prominent, custom display typography with a restrained color palette and well-defined interactive elements on a clean canvas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas: #ffffff;
  --color-ash: #767676;
  --color-summit-red: #fe3a3a;

  /* Typography — Font Families */
  --font-agrandir: 'Agrandir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.3;
  --tracking-caption: 0.04px;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 26px;
  --leading-heading: 1;
  --text-display: 90px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 60px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 35px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-buttons: 10px;
  --radius-navitems: 10px;
  --radius-pillbuttons: 35px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-midnight-card: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas: #ffffff;
  --color-ash: #767676;
  --color-summit-red: #fe3a3a;

  /* Typography */
  --font-agrandir: 'Agrandir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.3;
  --tracking-caption: 0.04px;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 26px;
  --leading-heading: 1;
  --text-display: 90px;
  --leading-display: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 35px;
}
```
