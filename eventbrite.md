# Eventbrite — Style Reference
> Event listing, vibrant and clear

**Theme:** light

Eventbrite employs a lively discovery-platform aesthetic, featuring a bright, almost white canvas punctuated by a single vivid blue for interaction and branding. Typography is direct and legible, supporting a clear hierarchy without being overt. Components are lightweight with subtle borders and generous rounded corners, emphasizing content flow and event visibility over heavy chrome.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default badge background |
| Porcelain Mist | `#f8f7fa` | `--color-porcelain-mist` | Subtle background for UI elements, hover states for neutral buttons and badges |
| Lavender Ash | `#dbdae3` | `--color-lavender-ash` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Ghost Gray | `#eeedf2` | `--color-ghost-gray` | Active state backgrounds and borders for neutral ghost buttons |
| Inkwell Purple | `#39364f` | `--color-inkwell-purple` | Primary text, prominent headings, default icon color |
| Shadow Graphite | `#585163` | `--color-shadow-graphite` | Secondary text, muted navigation elements, low-emphasis button text, focus outlines |
| Slate Steel | `#6f7287` | `--color-slate-steel` | Tertiary text, subtle button borders on hover/active, decorative icon fills |
| Oceanic Blue | `#3659e3` | `--color-oceanic-blue` | Primary accent for links, interactive elements, outlined buttons, information states |
| Deep Plum | `#1e0a3c` | `--color-deep-plum` | High-contrast headings, text on darker backgrounds, primary button text for outlined/ghost buttons |
| Terra Cotta | `#f05537` | `--color-terra-cotta` | Illustrative accents and occasional card backgrounds — used sparingly for brand emphasis |

## Tokens — Typography

### Neue Plak — Headings, body text, and general interface text – provides a bold, condensed feel for titles, balancing with a clear, readable body. · `--font-neue-plak`
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 32px
- **Line height:** 0.75, 1.00, 1.20, 1.25, 1.33, 1.43, 1.57, 1.71, 1.83, 2.00
- **Letter spacing:** -0.01em at 32px, -0.009em at 24px, 0.01em at 12px
- **Role:** Headings, body text, and general interface text – provides a bold, condensed feel for titles, balancing with a clear, readable body.

### Neue Plak Text — Specific navigation and metadata elements – ensuring clear, compact labeling within tighter UI spaces. · `--font-neue-plak-text`
- **Weights:** 600
- **Sizes:** 14px
- **Line height:** 1.20, 1.43
- **Letter spacing:** normal
- **Role:** Specific navigation and metadata elements – ensuring clear, compact labeling within tighter UI spaces.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.43 | — | `--text-body` |
| body-lg | 18px | 1.43 | — | `--text-body-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | — | `--text-heading` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 20px |
| inputs | 4px |
| buttons | 360px |
| heroCard | 40px 40px 0px 0px |
| navCategory | 100px |

### Layout

- **Section gap:** 77px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Ghost Button
**Role:** Outline style button for secondary actions or navigation.

Background: transparent (rgba(0,0,0,0)). Text: Inkwell Purple (#39364f) or Oceanic Blue (#3659e3). Padding: 0px. Border: 0px. Radius: 0px.

### Pill Button
**Role:** Small, contained button for filters or tags.

Background: Canvas White (#ffffff). Text: Inkwell Purple (#39364f). Border: Lavender Ash (#dbdae3) 1px solid. Border Radius: 360px. Padding: 1px 6px.

### Category Navigation Link
**Role:** Navigational link within category menus, often below a main image.

Background: transparent (rgba(0,0,0,0)). Text: Shadow Graphite (#585163). Border: 0px. Radius: 0px. Padding: 0px.

### Standard Card
**Role:** Container for event listings and general content blocks.

Background: Canvas White (#ffffff). Border: none. Shadow: none. Radius: 16px. Padding: 0px.

### Hero Card
**Role:** Prominent card used in hero sections, often with an integrated image.

Background: transparent (rgba(0,0,0,0)). Border: none. Shadow: none. Radius: 40px 40px 0px 0px. Padding: 0px.

### Compact Card
**Role:** Smaller cards for dense content layouts or galleries.

Background: Canvas White (#ffffff). Border: none. Shadow: none. Radius: 4px. Padding: 0px.

### Filter Badge
**Role:** Small, rounded labels for filtering or categorization.

Background: Canvas White (#ffffff). Text: Inkwell Purple (#39364f). Radius: 20px. Padding: 0px.

### Navigation Search Input
**Role:** Input field for global search functionality in the header.

Background: transparent (rgba(0,0,0,0)). Text: Oceanic Blue (#3659e3). Border: Oceanic Blue (#3659e3) 1px solid at the bottom. Radius: 0px. Padding: 12px 0px 6px 0px.

## Do's and Don'ts

### Do
- Use Canvas White (#ffffff) as the primary page background to create an expansive, light environment.
- Apply Oceanic Blue (#3659e3) exclusively for interactive elements like links, outlined buttons, and input borders to signal functionality.
- Ensure all cards use a radius of 16px, except for hero-style cards which use 40px 40px 0px 0px for a distinct top edge.
- Prioritize Neue Plak family for all text elements, using condensed weights and sizes above 18px for headlines and Neue Plak Text 600 for navigation.
- Maintain a comfortable density with 12px for `elementGap` and `cardPadding` within components to ensure readability.
- Implement Pill Buttons with a 360px radius for a fully rounded, distinct interactive shape.
- Use Lavender Ash (#dbdae3) for hairline borders on lists and cards to keep surfaces clean yet structured.

### Don't
- Avoid using highly saturated colors for large background areas, keeping the interface neutral and accent-driven.
- Do not introduce strong box-shadows on cards or containers; flatness is preferred to maintain a lightweight feel.
- Do not deviate from the Neue Plak family for primary text; it sets the brand's typographic tone.
- Do not use generic square buttons; opt for rounded (360px) or ghost buttons as per the design system.
- Avoid arbitrary uses of Terracotta (#f05537); reserve it for specific illustrative branding rather than widespread UI elements.
- Do not vary from the established spacing units; maintain the 4px base for consistent rhythm and hierarchy.
- Do not clutter card content with excessive internal padding; content should define the card's boundaries, not excessive internal whitespace.

## Imagery

The visual language for imagery is diverse, incorporating photography and custom illustrations. Photography is typically lifestyle or event-focused, sometimes with a slight creative crop but generally left unmasked. Product screenshots appear less frequently. Illustrations are organic, often flat but with some subtle dimension, featuring a muted color palette that occasionally includes branded accents like Terra Cotta. Icons are outlined, conveying functionality without heavy visual weight. Imagery serves both decorative atmosphere in hero sections and explanatory content in event listings, often appearing as contained image blocks within cards, dominating visual space in grid layouts.

## Layout

The site uses a full-bleed page model for its primary background, but content within sections is typically contained and centered within a comfortable max-width. The hero section often features a full-width background image with centered, condensed headline text. Sections follow a consistent vertical rhythm, primarily flowing seamlessly with minimal visual dividers. Content is arranged in flexible grid layouts, with multi-column event cards featuring images prominently. A dominant pattern is a 4-column card grid for event listings. The navigation is a sticky top bar, providing persistent access to search and key actions while scrolling.

## Agent Prompt Guide

Quick Color Reference:
text: #39364f
background: #ffffff
border: #dbdae3
accent: #3659e3
primary action: #3659e3 (outlined action border)

Example Component Prompts:
1. Create an event listing card: Background Canvas White (#ffffff), Inkwell Purple (#39364f) 16px Neue Plak weight 700 for event title, Lavender Ash (#dbdae3) 1px solid border, 16px radius, 0px padding. Image at top.
2. Design a Pill Button for filtering: Background Canvas White (#ffffff), Inkwell Purple (#39364f) 14px Neue Plak weight 600 text, Lavender Ash (#dbdae3) 1px solid border, 360px radius, 1px 6px padding.
3. Create an Outlined Primary Action: Transparent background, #3659e3 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.

## Similar Brands

- **Dice.fm** — Similar focus on event discovery with a clean, light interface and prominent use of imagery within cards.
- **Bandsintown** — Emphasizes clear event listings and artist promotion against a light background.
- **Resident Advisor** — Event-focused platform with a dense but structured card-based layout and a strong visual identity through photography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-porcelain-mist: #f8f7fa;
  --color-lavender-ash: #dbdae3;
  --color-ghost-gray: #eeedf2;
  --color-inkwell-purple: #39364f;
  --color-shadow-graphite: #585163;
  --color-slate-steel: #6f7287;
  --color-oceanic-blue: #3659e3;
  --color-deep-plum: #1e0a3c;
  --color-terra-cotta: #f05537;

  /* Typography — Font Families */
  --font-neue-plak: 'Neue Plak', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-plak-text: 'Neue Plak Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 77px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 360px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 20px;
  --radius-inputs: 4px;
  --radius-buttons: 360px;
  --radius-herocard: 40px 40px 0px 0px;
  --radius-navcategory: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-porcelain-mist: #f8f7fa;
  --color-lavender-ash: #dbdae3;
  --color-ghost-gray: #eeedf2;
  --color-inkwell-purple: #39364f;
  --color-shadow-graphite: #585163;
  --color-slate-steel: #6f7287;
  --color-oceanic-blue: #3659e3;
  --color-deep-plum: #1e0a3c;
  --color-terra-cotta: #f05537;

  /* Typography */
  --font-neue-plak: 'Neue Plak', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-plak-text: 'Neue Plak Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 360px;
}
```
