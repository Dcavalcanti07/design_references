# Andrei Rybin — Style Reference
> Gallery Wall Contrast

**Theme:** light

Andrei Rybin's portfolio employs a stark, high-contrast monochrome aesthetic, treating UI elements and content as if projected onto a gallery wall. The primary visual tension comes from the interplay of deep blacks and pure whites, accented by subtle, soft gray text for descriptive elements. Typography is understated and functional, ensuring content primacy, while rounded corners give a subtle softness to otherwise sharp, defined blocks.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, surface base for content blocks |
| Midnight Black | `#000000` | `--color-midnight-black` | Primary text, strong borders, dark-themed areas within content blocks |
| Stone Gray | `#858585` | `--color-stone-gray` | Secondary text, muted headlines, subtle boundary lines in components |
| Ash Gray | `#8e8e90` | `--color-ash-gray` | Tertiary text, descriptive labels, placeholder text |

## Tokens — Typography

### sans-serif — Used for utility text, links, and system-level details where a compact, highly readable default is preferred. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for utility text, links, and system-level details where a compact, highly readable default is preferred.

### Inter — Headings and primary body text. Its subtle tracking variations across sizes prevent it from feeling too rigid, balancing modern utility with a hint of crafted precision. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px, 24px
- **Line height:** 1.20, 1.23, 1.30
- **Letter spacing:** -0.204px at 12px, 0.192px at 24px
- **Role:** Headings and primary body text. Its subtle tracking variations across sizes prevent it from feeling too rigid, balancing modern utility with a hint of crafted precision.

### .SFNSText — .SFNSText — detected in extracted data but not described by AI · `--font-sfnstext`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Letter spacing:** -0.017
- **Role:** .SFNSText — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading-sm | 24px | 1.23 | 0.192px | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 40px |
| small | 8px |
| medium | 16px |

### Layout

- **Section gap:** 120px
- **Card padding:** 6px
- **Element gap:** 10px

## Components

### Portfolio Project Card
**Role:** Showcase individual projects

Content block with a `Midnight Black` background for the phone frame and `Canvas White` for the surrounding card, using a `16px` border-radius. A `10px` gap separates internal elements. Text labels use `Ash Gray` (12px, Inter, 400).

### Header Navigation Link
**Role:** Primary site navigation

Text link using `Midnight Black` color, `12px` font size (sans-serif, 400 weight), with a tight `2px` spacing between elements. On hover, it may show a `Midnight Black` border.

### Hero Section Text Block
**Role:** Main introductory content

Centered large text using `Midnight Black` for primary headline (24px, Inter, 400) and `Ash Gray` (12px, Inter, 400) for descriptive subtext, separated by `10px` vertical spacing.

### Decorative Border Element
**Role:** Visual separator for content sections or components

A hairline border, typically `1px` wide, rendered in `Midnight Black` or `Stone Gray`.

## Do's and Don'ts

### Do
- Use `Canvas White` (#ffffff) for all main page backgrounds and `Midnight Black` (#000000) for strong contrast text and contained dark modules.
- Prioritize `Inter` font for all primary textual content and headings, with a default weight of 400.
- Apply `16px` border-radius for main content cards and `40px` radius for larger, more illustrative blocks or containers.
- Maintain a `10px` `elementGap` for consistent internal spacing within components like image galleries or text lists.
- Use subtle text colors like `Stone Gray` (#858585) or `Ash Gray` (#8e8e90) for secondary information, subheadings, and descriptive text to soften visual impact.
- Structure sections with `120px` vertical `sectionGap` unless specifically nesting content.

### Don't
- Avoid introducing any saturated colors; only implement the defined monochrome palette of `Canvas White`, `Midnight Black`, `Stone Gray`, and `Ash Gray`.
- Do not deviate from the specified `400` font weight for `Inter` or `sans-serif` fonts, as the system relies on this consistent light weight.
- Do not use generic `8px` `border-radius` for main cards; reserve `16px` for cards and `40px` for more prominent blocks.
- Do not use letter-spacing values other than `-0.204px` for 12px Inter text or `0.192px` for 24px Inter text; default to normal tracking for other text.
- Do not assume the `sans-serif` system font has distinct sizes beyond `12px`; use Inter for all larger textual elements.
- Do not apply drop shadows or complex elevation effects; the design relies on flat, direct contrast.

## Elevation

The design intentionally avoids complex shadows or elevation effects, relying instead on high-contrast color shifts and clearly defined borders to differentiate elements. Surfaces are largely flat, emphasizing a two-dimensional, graphic quality. This approach contributes to the 'gallery wall' aesthetic, making each block feel like a distinctly mounted piece of work.

## Imagery

This site features product photography, specifically close-up shots of mobile app interfaces predominantly on black-screened phone mockups. Images are contained within distinct blocks, often but not exclusively with rounded corners (16px or 40px radius), creating a sense of framed display rather than full-bleed immersion. The primary role of imagery is to showcase product design work, with a focus on detailed UI rather than lifestyle or abstract concepts. Icons are minimal, with a simple outlined or filled style, typically in `Midnight Black` or `Stone Gray`, serving functional rather than decorative purposes. The density is image-heavy, with blocks of product visuals dominating the layout, creating a gallery-like experience.

## Layout

The page uses a maximum-width contained model for the header and top-level navigation, while the main content area for project showcases appears to be full-bleed horizontally, allowing large visual blocks to fill the screen width. The hero section is subtle, featuring a centered block of text. Content is primarily arranged in a grid of project cards, often two columns, with large visual blocks stacked vertically. There is a strong emphasis on consistent vertical spacing between major sections (`120px`). The navigation is a minimal top bar with discreet text links, remaining static at the top.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Header Navigation Link: Text 'Showreel' in `Midnight Black` (#000000), 12px sans-serif weight 400, no letter-spacing, with a 2px horizontal element gap from adjacent links.
2. Create a Portfolio Project Card: Container background `Canvas White` (#ffffff), 16px border-radius. Inside, place a `Midnight Black` (#000000) rectangular phone mockup. Below it, add text 'AI character → Chat' in `Ash Gray` (#8e8e90), 12px Inter weight 400, letter-spacing -0.204px.
3. Create a descriptive text block: 'Welcome to my space on the internet...' in `Ash Gray` (#8e8e90), 12px Inter weight 400, line-height 1.2, centered within its container with 10px element gap to any preceding heading.
4. Create a main page section header: 'Hello, I'm Andrei Rybin' in `Midnight Black` (#000000), 24px Inter weight 400, letter-spacing 0.192px.
5. Create a divider line: A 1px solid line in `Midnight Black` (#000000).

## Similar Brands

- **Apple Developer** — Clean, monochrome aesthetic with a strong focus on product and minimal UI elements.
- **Linear** — Understated typography, high contrast, and use of dark sections within a light theme for content blocks.
- **Figma** — Emphasis on showcasing digital tools and UI, with a focused, functional layout and minimal decorative elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-stone-gray: #858585;
  --color-ash-gray: #8e8e90;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sfnstext: '.SFNSText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.23;
  --tracking-heading-sm: 0.192px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 120px;
  --card-padding: 6px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-large: 40px;
  --radius-small: 8px;
  --radius-medium: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-stone-gray: #858585;
  --color-ash-gray: #8e8e90;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sfnstext: '.SFNSText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.23;
  --tracking-heading-sm: 0.192px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;
}
```
