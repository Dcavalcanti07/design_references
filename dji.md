# DJI — Style Reference
> Precision instrument display. A stark, high-contrast digital interface where light and shadow define advanced technology.

**Theme:** light

This system evokes a sense of technical precision and premium product display, balancing stark black-and-white hero sections with clean, information-rich content areas. The use of a single vivid blue for interactive elements cuts through the achromatic palette, acting like a power indicator light. Subtle grayscale variations create depth and hierarchy without relying on heavy shadows, maintaining a lightweight, almost floating aesthetic crucial for showcasing high-tech hardware.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Major headings, primary text, icon fills, and hero section backgrounds — establishes a strong, commanding presence. |
| Arctic Snow | `#ffffff` | `--color-arctic-snow` | Page backgrounds, card surfaces, and primary button backgrounds — provides a clean canvas for product focus. |
| Glacial White | `#f7f9fa` | `--color-glacial-white` | Subtle background for content sections, slightly warmer than Arctic Snow to introduce minimal variation. |
| Platinum Gray | `#ededed` | `--color-platinum-gray` | Card backgrounds and secondary content areas, offering a soft contrast against Arctic Snow. |
| Charcoal Black | `#272727` | `--color-charcoal-black` | Footer backgrounds and other dark-mode elements, a deeper black to delineate sections. |
| Shadow Ink | `#040404` | `--color-shadow-ink` | Secondary text and borders, providing a softer contrast than Midnight Void. |
| Storm Gray | `#6c7073` | `--color-storm-gray` | Input borders, button borders, and tertiary text— a mid-tone gray for subtle definition. |
| Slate Text | `#595959` | `--color-slate-text` | Body text and navigation links, a dark but not stark gray for readability on light backgrounds. |
| Phantom Gray | `#303233` | `--color-phantom-gray` | Navigation active states and specific dark text elements, a darker variant of Slate Text. |
| Ash Gray | `#8c8c8c` | `--color-ash-gray` | Secondary information text and inactive elements, a lighter gray for less prominent details. |
| Active Blue | `#0070d5` | `--color-active-blue` | Interactive elements, primary links, and active navigation indicators — this vivid blue signals user interaction. |
| Deep Sea Blue | `#3b63a9` | `--color-deep-sea-blue` | Less prominent interactive states or subtle accent backgrounds, a slightly muted blue. |
| Sky Link Hover | `#2490e3` | `--color-sky-link-hover` | Hover state for links, a lighter, more vibrant blue. |
| Ocean Link Active | `#0058b0` | `--color-ocean-link-active` | Active state for links, a darker, deeper blue. |
| Button Gradient Blue | `#0060e7` | `--color-button-gradient-blue` | Subtle background for specific blue buttons, hinting at a gradient though not explicitly defined. |

## Tokens — Typography

### Open Sans — The primary typeface for all content, from navigation to body text and headings. Its clean, geometric forms provide excellent readability across various weights and sizes, supporting the tech-focused aesthetic. The varied letter-spacing at larger sizes adds a subtle sense of precision. · `--font-open-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.00, 1.10, 1.13, 1.17, 1.20, 1.25, 1.33, 1.43, 1.50, 2.00
- **Letter spacing:** -0.0300em, -0.0200em
- **Role:** The primary typeface for all content, from navigation to body text and headings. Its clean, geometric forms provide excellent readability across various weights and sizes, supporting the tech-focused aesthetic. The varied letter-spacing at larger sizes adds a subtle sense of precision.

### Arial — Used for specific, small button texts, maintaining system-level legibility for minor controls. · `--font-arial`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Used for specific, small button texts, maintaining system-level legibility for minor controls.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.03px | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.33 | — | `--text-body-lg` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading | 20px | 1.2 | — | `--text-heading` |
| heading-lg | 24px | 1.17 | — | `--text-heading-lg` |
| display-sm | 32px | 1.13 | -0.03px | `--text-display-sm` |
| display | 40px | 1.1 | -0.03px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| inputs | 4px |
| buttons | 64px |
| navButtons | 99px |
| specialNav | 1408px |
| heroElements | 60px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 16px 16px 0px` | `--shadow-md` |
| md-2 | `rgba(0, 0, 0, 0.1) 0px 8px 16px 0px` | `--shadow-md-2` |

### Layout

- **Card padding:** 16px

## Components

### Primary Navigation Link
**Role:** Main navigation items

Color Slate Text (#595959) by default, transforms to Phantom Gray (#303233) on hover, with a letter-spacing of -0.02em for a slightly more compact feel. Text size 16px, weight 400. Letter spacing is subtly reduced from -0.03em for display sizes to -0.02em for nav, adding visual stability.

### Global Call to Action Button (Blue)
**Role:** Main calls to action

Background Active Blue (#0070d5), text Arctic Snow (#ffffff). Rounded with 99px border-radius, padding 10px vertically and 16px horizontally. Open Sans, weight 500, size 16px. A vivid, fully saturated accent against the predominantly neutral palette.

### Ghost Text Button (Dark Text, Light BG)
**Role:** Minimal interactive text elements

Transparent background, Midnight Void (#000000) text (or equivalent dark neutral). Minimal padding (5px vertical, 16px horizontal) and 64px radius. Used for 'Leer más' style links that appear button-like but are not primary actions. Example has 64px border radius but no border.

### Compact Navigation Button
**Role:** Store button in the utility navigation

Background Active Blue (#0070d5), text Arctic Snow (#ffffff). Border radius 8px, but potentially squared off on one side (e.g., `0px 8px 8px 0px`). Padding 1px vertically and 6px horizontally. Uses Arial, weight 400, size 13px, for small, functional text.

### Search Input Field
**Role:** Site search functionality

Transparent background, Arctic Snow (#ffffff) text, and Storm Gray (#6c7073) border. Border radius 4px, but potentially squared off on one side (e.g., `4px 0px 0px 4px`). Padding 4px vertically, 12px left. Used for search inputs, contrasting with dark navigation bars.

### Hero Section Header
**Role:** Dominant titles on hero sections

Midnight Void (#000000) or Arctic Snow (#ffffff) text, depends on background. Open Sans, weight 300, size 40px, with -0.03em letter spacing. The light weight at large size creates a sophisticated, almost whispered authority, rather than shouting.

### Utility Navigation Button
**Role:** Small interactive icons/buttons in header

Transparent background, Midnight Void (#000000) text. Round (50% border radius) for icon buttons. Arial, weight 400, size 13px, padding 1px vertical, 6px horizontal. Indicates a functional, system-level interaction.

## Do's and Don'ts

### Do
- Do use Midnight Void (#000000) for primary headlines and Arctic Snow (#ffffff) for page backgrounds, maintaining high contrast for product focus.
- Do apply Active Blue (#0070d5) exclusively for primary interactive elements like call-to-action buttons and critical links.
- Do use Open Sans font family for all textual content, opting for weight 300 for display headlines to convey subtle authority.
- Do consistently apply a 64px border-radius for all ghost buttons and minor interactive elements, creating a soft, tactile feel.
- Do utilize the shadow rgba(0, 0, 0, 0.1) 0px 8px 16px 0px for elevated cards, providing subtle depth without being aggressive.
- Do use 10px vertical and 16px horizontal padding for primary buttons to ensure a comfortable tap target.
- Do employ a spacing hierarchy from 4px to 16px for element gaps to maintain a comfortable visual density.

### Don't
- Don't introduce additional saturated colors; the palette relies on a single vibrant blue accent within an achromatic scale.
- Don't use aggressive, hard shadows; elevation should be subtle and support the clean aesthetic.
- Don't deviate from Open Sans; maintain the distinct typographic voice established by its varied weights and specific letter-spacing.
- Don't use sharp, angular corners for buttons; all interactive buttons should have at least a 64px border-radius.
- Don't place ghost buttons directly on highly textured backgrounds without sufficient contrast; they are designed for clean product showcases.
- Don't alter the letter spacing patterns for headlines or navigation; these are carefully set to create a specific visual cadence.
- Don't use more than two levels of elevation (page background, subtle card lift) to preserve the lightweight feel.

## Elevation

- **Card:** `rgba(0, 0, 0, 0.1) 0px 8px 16px 0px`
- **Navigation Panel:** `rgba(0, 0, 0, 0.1) 0px 16px 16px 0px`

## Imagery

This site prominently features high-resolution product photography, often isolated on stark black or white backgrounds, emphasizing the product itself as the hero. Products are shown in tight crops or 3/4 views, highlighting their design and functionality without distracting lifestyle context. Photography is crisp, well-lit, and used full-bleed or contained within clean, often card-like structures. There's a minimal use of abstract graphics or conceptual illustrations, reinforcing the focus on tangible hardware. Icons are mostly monochrome, with minimal stroke weight, adhering to the clean, technical aesthetic.

## Layout

The page primarily uses a `max-width` contained layout for content sections but features full-bleed hero sections that dominate the viewport, using dark backgrounds to highlight product photography. Header is sticky and spans full-width. Content sections alternate between visually distinct blocks, with clear vertical spacing, often showcasing product cards in grids or alternating text-left/image-right arrangements. The initial hero pattern features a centered headline over a dark background with a prominent product visual. The overall density is comfortable, ensuring breathing room around product displays and textual information.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000
- Background (Primary): #ffffff
- CTA Button: #0070d5
- Border (Input): #6c7073
- Accent (Active Link): #0070d5

### Example Component Prompts
1. Create a Hero Section: full-width, background Midnight Void (#000000). Centered headline 'El mundo en mi bolsillo' (Open Sans, weight 300, 40px, #ffffff, letter-spacing -0.03em). Below it, a ghost button 'Leer más' (Arctic Snow #ffffff text, transparent background, 1px Arctic Snow #ffffff border, 64px radius, 10px vertical 16px horizontal padding).
2. Create a Product Card: background Platinum Gray (#ededed), border-radius 4px, shadow rgba(0, 0, 0, 0.1) 0px 8px 16px 0px. Inside, use Midnight Void (#000000) for product titles (Open Sans, weight 600, 24px) and Slate Text (#595959) for descriptions (Open Sans, weight 400, 16px).
3. Create a Primary CTA Button: background Active Blue (#0070d5), text Arctic Snow (#ffffff), border-radius 99px. Padding 10px vertical, 16px horizontal. Text 'Comprar' (Open Sans, weight 500, 16px).
4. Create a Search Input Field: transparent background, Storm Gray (#6c7073) border, border-radius 4px. Placeholder text Ash Gray (#8c8c8c), input text Arctic Snow (#ffffff) (Open Sans, weight 400, 16px). Padding 4px vertical, 12px left.

## Similar Brands

- **Apple** — Shares a focus on product photography on clean backgrounds, high-contrast typography, and a limited accent color palette.
- **Sony** — Similar approach to showcasing high-tech consumer electronics with a clean, 'prosumer' aesthetic, often using dark hero shots.
- **GoPro** — Emphasizes product design and functionality through clear, often isolated imagery, paired with a functional, legible UI.
- **Framework** — Utilizes a clean, technical visual language with strong typographic hierarchy and minimal UI embellishments to highlight advanced hardware.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-arctic-snow: #ffffff;
  --color-glacial-white: #f7f9fa;
  --color-platinum-gray: #ededed;
  --color-charcoal-black: #272727;
  --color-shadow-ink: #040404;
  --color-storm-gray: #6c7073;
  --color-slate-text: #595959;
  --color-phantom-gray: #303233;
  --color-ash-gray: #8c8c8c;
  --color-active-blue: #0070d5;
  --color-deep-sea-blue: #3b63a9;
  --color-sky-link-hover: #2490e3;
  --color-ocean-link-active: #0058b0;
  --color-button-gradient-blue: #0060e7;

  /* Typography — Font Families */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.33;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.17;
  --text-display-sm: 32px;
  --leading-display-sm: 1.13;
  --tracking-display-sm: -0.03px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-112: 112px;

  /* Layout */
  --card-padding: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 60px;
  --radius-full-2: 64px;
  --radius-full-3: 99px;
  --radius-full-4: 1408px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-inputs: 4px;
  --radius-buttons: 64px;
  --radius-navbuttons: 99px;
  --radius-specialnav: 1408px;
  --radius-heroelements: 60px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 16px 16px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 8px 16px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-arctic-snow: #ffffff;
  --color-glacial-white: #f7f9fa;
  --color-platinum-gray: #ededed;
  --color-charcoal-black: #272727;
  --color-shadow-ink: #040404;
  --color-storm-gray: #6c7073;
  --color-slate-text: #595959;
  --color-phantom-gray: #303233;
  --color-ash-gray: #8c8c8c;
  --color-active-blue: #0070d5;
  --color-deep-sea-blue: #3b63a9;
  --color-sky-link-hover: #2490e3;
  --color-ocean-link-active: #0058b0;
  --color-button-gradient-blue: #0060e7;

  /* Typography */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.33;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.17;
  --text-display-sm: 32px;
  --leading-display-sm: 1.13;
  --tracking-display-sm: -0.03px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 60px;
  --radius-full-2: 64px;
  --radius-full-3: 99px;
  --radius-full-4: 1408px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 16px 16px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 8px 16px 0px;
}
```
