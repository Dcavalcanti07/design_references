# Dribbble — Style Reference
> Gallery Wall on White Linen — content as art, neutrally framed.

**Theme:** light

Dribbble's aesthetic is an 'organized showcase' — a high-contrast, functionally transparent environment designed to highlight creative work without visual interference. Dominant achromatic tones in the background and foreground create a neutral canvas, allowing the showcased content to provide the primary visual interest. Subtle but consistent border radii unify interactive elements and content containers, creating a sense of approachable professionalism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Stormy Night | `#0d0c22` | `--color-stormy-night` | Primary text, deep backgrounds for focus, button fills. Establishes a strong dark anchor. |
| Anchor Black | `#060318` | `--color-anchor-black` | Deepest text color, secondary backgrounds, important icons. Provides maximum contrast for legibility. |
| Ghost Gray | `#6e6d7a` | `--color-ghost-gray` | Secondary text, subtle link accents, minor graphical elements. Provides a softer counterpoint to primary darks. |
| Dribbble Pink | `#ea4c89` | `--color-dribbble-pink` | Badge accents, interactive element highlights. A warm, vivid pop for attention and branding. |
| Arctic White | `#ffffff` | `--color-arctic-white` | Pure page backgrounds, text on dark buttons, icons. The primary canvas color, maximizing content visibility. |
| Canvas Light | `#f3f3f6` | `--color-canvas-light` | Alternate background sections, subtle dividers. Adds gentle variation to the white canvas without introducing heavy contrast. |
| Chrome Gray | `#9e9ea7` | `--color-chrome-gray` | Border colors, placeholder text, inactive states for buttons and icons. Defines boundaries without being aggressive. |
| Hint Frost | `#e2e8f2` | `--color-hint-frost` | Subtle border or background for certain interactive elements. A very light, cool-toned gray for demarcation. |
| Deep Plum | `#3a3546` | `--color-deep-plum` | Occasional background accents or text providing subtle depth in specific modules. |
| Sapphire Glow | `#956bcd` | `--color-sapphire-glow` | Icon fill for specific interactive states or promotional elements. Provides a vibrant but measured accent. |

## Tokens — Typography

### Mona Sans — Primary typeface for all UI elements, headings, and body text. Its modern, clean lines ensure clarity against high-contrast backgrounds. · `--font-mona-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 450, 500, 600, 700, 800
- **Sizes:** 12px, 13px, 14px, 16px, 48px
- **Line height:** 1.00 - 2.33
- **Letter spacing:** normal
- **OpenType features:** `"ss01" on`
- **Role:** Primary typeface for all UI elements, headings, and body text. Its modern, clean lines ensure clarity against high-contrast backgrounds.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.54 | — | `--text-caption` |
| body | 14px | 1.25 | — | `--text-body` |
| display | 48px | 1.21 | — | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 72 | 72px | `--spacing-72` |
| 220 | 220px | `--spacing-220` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| input | 12px |
| links | 4px |
| badges | 12px |
| buttons | 10000px |

### Layout

- **Section gap:** 40px
- **Element gap:** 4px

## Components

### Primary Navigation Link
**Role:** Interactive element

Text link, color #6e6d7a, no background, font Mona Sans weight 600, size 14px, lineHeight 1.36. Activated state or hover usually shifts to Anchor Black #060318 or Stormy Night #0d0c22.

### Auth Button
**Role:** Call to action

Pill-shaped button with Arctic White background (#ffffff), Stormy Night text (#0d0c22), Mona Sans weight 500, 16px padding on left/right, 10000px border radius.

### Category Filter Button
**Role:** Filter/Tag

Default state: transparent background, Ghost Gray text (#6e6d7a), no border, Mona Sans weight 400, 10000px border radius. Hover/active state uses subtle background or darker text.

### Search Input
**Role:** Data entry

Transparent background, Anchor Black text (#060318), 12px border radius, 24px left padding. Placeholder text uses Ghost Gray (#6e6d7a).

### Filter Tag (Text)
**Role:** Search refinement

Transparent background, Stormy Night text (#0d0c22), Mona Sans weight 400.

### Badge - New
**Role:** Informational tag

Dribbble Pink background (#ea4c89), Arctic White text (#ffffff), 12px border radius, 4px vertical, 6px horizontal padding, Mona Sans weight 600, 12px size.

### Compact Nav Button
**Role:** Navigation/Action

Transparent background, Stormy Night text (#0d0c22), 16px horizontal padding, 10000px border radius.

## Do's and Don'ts

### Do
- Prioritize Mona Sans for all text elements to maintain a unified, modern aesthetic.
- Use Arctic White (#ffffff) as the primary page background and Canvas Light (#f3f3f6) for subtle section differentiation.
- Apply a 10000px border radius to all primary action buttons (e.g., 'Auth Button') to establish a consistent soft, approachable shape.
- Employ Stormy Night (#0d0c22) for main body text and Anchor Black (#060318) for headlines to ensure strong legibility against light backgrounds.
- Use Ghost Gray (#6e6d7a) for secondary text and disabled states to create hierarchy and reduce visual noise.
- Integrate Dribbble Pink (#ea4c89) sparingly for key accents like 'New' badges or interactive element highlights to draw attention.
- Ensure input fields have a 12px border radius and 24px left padding for consistency.

### Don't
- Do not introduce sharp corners on interactive elements; maintain the established border radii for buttons (10000px) and inputs (12px).
- Avoid using highly saturated colors for large background areas; stick to the neutral palette to ensure content remains the focus.
- Do not deviate from the Mona Sans typeface; no other font families should be introduced.
- Refrain from using strong drop shadows or complex gradients; the system relies on flat colors and subtle borders for depth.
- Do not use white text on white backgrounds or similar low-contrast combinations; maintain WCAG AAA contrast ratio where possible (e.g. Stormy Night on Arctic White).
- Avoid excessive use of Dribbble Pink (#ea4c89); it should be reserved for specific branding or high-priority calls to action.
- Do not use inconsistent padding values around elements; adhere to the 4px base unit and established token values for internal spacing.

## Imagery

Photography and product screenshots are the primary visual assets, showcasing digital designs. They are typically contained within rectangular frames, with sharp edges, and often presented in grids or prominent hero sections. The imagery itself provides the color and vibrant energy against the neutral UI backdrop, serving a functional role as product showcase and inspiration. Iconography is minimalist, outlined, and monochromatic, often using Stormy Night (#0d0c22) or Ghost Gray (#6e6d7a).

## Layout

The page model is a max-width contained layout, likely around 1200px, symmetrically centered. The hero section is a split layout with a prominent headline on the left and a large product screenshot/showcase on the right. Section rhythm is primarily consistent vertical spacing with subtle background color variations (Arctic White and Canvas Light). Content is often arranged in 2-column or 3-column grids, particularly for showcasing design 'shots'. The layout is spacious with clear visual separation between blocks of content. Navigation is a sticky top bar.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#0d0c22` (Stormy Night)
- Background: `#ffffff` (Arctic White)
- CTA Button: `#ea4c89` (Dribbble Pink)
- Border/Inactive: `#9e9ea7` (Chrome Gray)
- Accent: `#956bcd` (Sapphire Glow)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Background Arctic White (#ffffff). Left side: Headline 'Discover the World’s Top Designers' at 48px Mona Sans weight 800, Stormy Night (#0d0c22), lineHeight 1.21. Subtext 'Explore work...' at 14px Mona Sans weight 400, Ghost Gray (#6e6d7a), lineHeight 1.25. Right side: large framed image, no border radius.
2. **Generate a Primary Auth Button:** Text 'Sign up' in Arctic White (#ffffff) on a Dribbble Pink (#ea4c89) background. Font Mona Sans weight 600, size 14px, lineHeight 1.36. Corner radius 10000px. Padding 10px vertical, 16px horizontal.
3. **Design a Search Input Field:** Background transparent, text 'What are you looking for?' in Anchor Black (#060318). Placeholder text in Chrome Gray (#9e9ea7). Border Chrome Gray (#9e9ea7), 1px solid. Border radius 12px. Left padding 24px.
4. **Produce a 'New' Badge:** Background Dribbble Pink (#ea4c89), text 'NEW' in Arctic White (#ffffff). Font Mona Sans weight 600, size 12px, lineHeight 1.54. Corner radius 12px. Padding 4px vertical, 6px horizontal.
5. **Create a Filter Tag Button:** Text 'dashboard' in Stormy Night (#0d0c22). Background Canvas Light (#f3f3f6). Font Mona Sans weight 500, size 14px, lineHeight 1.25. Corner radius 10000px. Padding 8px vertical, 16px horizontal.

## Similar Brands

- **Behance** — Similar focus on visual content display with a clean, light UI and neutral backgrounds to highlight creative work.
- **Pexels** — Emphasizes image grids and high-contrast text on a white canvas, allowing photography to dominate the visual interest.
- **Unsplash** — Large, borderless image display with minimalist UI elements and a neutral color palette that defers to the imagery.
- **Figma (landing pages)** — Utilizes a crisp, modern sans-serif typeface, a predominantly white/light background, and carefully placed accent colors for calls to action.
- **Linear** — Shares the clean, functional UI, strong use of a single sans-serif font, and a disciplined approach to color for status and interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-stormy-night: #0d0c22;
  --color-anchor-black: #060318;
  --color-ghost-gray: #6e6d7a;
  --color-dribbble-pink: #ea4c89;
  --color-arctic-white: #ffffff;
  --color-canvas-light: #f3f3f6;
  --color-chrome-gray: #9e9ea7;
  --color-hint-frost: #e2e8f2;
  --color-deep-plum: #3a3546;
  --color-sapphire-glow: #956bcd;

  /* Typography — Font Families */
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.54;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-display: 48px;
  --leading-display: 1.21;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-72: 72px;
  --spacing-220: 220px;

  /* Layout */
  --section-gap: 40px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-input: 12px;
  --radius-links: 4px;
  --radius-badges: 12px;
  --radius-buttons: 10000px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-stormy-night: #0d0c22;
  --color-anchor-black: #060318;
  --color-ghost-gray: #6e6d7a;
  --color-dribbble-pink: #ea4c89;
  --color-arctic-white: #ffffff;
  --color-canvas-light: #f3f3f6;
  --color-chrome-gray: #9e9ea7;
  --color-hint-frost: #e2e8f2;
  --color-deep-plum: #3a3546;
  --color-sapphire-glow: #956bcd;

  /* Typography */
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.54;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-display: 48px;
  --leading-display: 1.21;

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
  --spacing-44: 44px;
  --spacing-72: 72px;
  --spacing-220: 220px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
}
```
