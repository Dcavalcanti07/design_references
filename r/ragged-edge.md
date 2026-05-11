# Ragged Edge — Style Reference
> Kinetic typographic canvases

**Theme:** light

Ragged Edge employs a sophisticated, high-contrast, black-on-white aesthetic that emphasizes bold typography and a striking, motion-blurred hero gradient. The design balances raw, impactful text with clean, often spacious layouts. Surfaces are predominantly white, punctuated by dark text and accents. Interactive elements maintain a tactile, rounded feel while staying visually understated, allowing the powerful headlines and dynamic hero to dominate.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#181f1f` | `--color-midnight-ink` | Primary text, deep surface backgrounds, filled button backgrounds. Creates high contrast and visual weight |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, high-contrast text on dark surfaces, icon fills, card borders. Provides ample whitespace |
| Fog Gray | `#d1d2d2` | `--color-fog-gray` | Hairline borders, subtle dividers, muted link borders |
| Muted Slate | `#a3a5a5` | `--color-muted-slate` | Secondary text, placeholder text in inputs, ghost button text and borders. Offers softer hierarchy |
| Graphite | `#000000` | `--color-graphite` | Dominant background for specific sections, high-contrast text |
| Pristine Mist | `#eaf7f3` | `--color-pristine-mist` | Canvas background, subtle background for nav elements. The lightest base surface |
| Lagoon Violet | `#516fea` | `--color-lagoon-violet` | Outlined button borders — a singular, vivid accent color that provides interactive focus |
| Deep Mocha | `#1f3233` | `--color-deep-mocha` | Darker background surface for content blocks or specific sections |
| Motion Blur Gradient | `linear-gradient(0deg, rgba(255, 194, 64, 0), rgb(255, 194, 64), rgb(255, 196, 244), rgb(150, 235, 235), rgba(150, 235, 235, 0))` | `--color-motion-blur-gradient` | Striking hero background, decorative element. Provides a dynamic, energetic visual |
| Alert Red | `#f56565` | `--color-alert-red` | Red text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Grit-Regular — Body text, navigation items, links, and general UI elements. Its strong, humanist character serves as the workhorse typeface. · `--font-grit-regular`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px, 30px, 56px
- **Line height:** 1.00, 1.20, 1.25, 1.43, 1.50, 2.60
- **Letter spacing:** normal
- **OpenType features:** `"kern"`
- **Role:** Body text, navigation items, links, and general UI elements. Its strong, humanist character serves as the workhorse typeface.

### ABCDiatypeExpanded-Bold — Prominent headlines and impactful statements. Its expanded, bold form demands attention and defines the brand's direct, confident voice. · `--font-abcdiatypeexpanded-bold`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 10px, 12px, 16px, 20px, 40px, 78px, 82px
- **Line height:** 1.10, 1.15, 1.20, 2.00
- **Letter spacing:** -0.0200em at 78-82px, -0.0100em at 40px
- **OpenType features:** `"kern"`
- **Role:** Prominent headlines and impactful statements. Its expanded, bold form demands attention and defines the brand's direct, confident voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.1 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.25 | -0.2px | `--text-subheading` |
| heading | 40px | 1.15 | -0.4px | `--text-heading` |
| display | 78px | 1.1 | -1.56px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 180 | 180px | `--spacing-180` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 40px |
| inputs | 54px |
| buttons | 64px |
| navigationItems | 64px |

### Layout

- **Section gap:** 180px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Navigation Item
**Role:** Subtle interactive navigation links

Text only, Grit-Regular at 14px, color Midnight Ink at 40% opacity, no padding or border, 0px radius.

### Filled Primary Button
**Role:** High-priority call to action button

Background Midnight Ink, text Canvas White, 64px border radius, 12px vertical padding, 16px horizontal padding. Uses Grit-Regular.

### Outlined Accent Button
**Role:** Secondary call to action button with brand accent

Background Midnight Ink, text Canvas White, 54px border radius, border 1px solid Lagoon Violet, 0px vertical padding, 34px horizontal padding. Uses ABCDiatypeExpanded-Bold to make its statement.

### Soft Input Field
**Role:** User input text field

Transparent background, Muted Slate text, border 1px solid Midnight Ink, 54px border radius, 0px vertical padding, 34px horizontal padding. Uses Grit-Regular.

### Nav Button
**Role:** Top navigation menu item

Text Grit-Regular, color Midnight Ink, 64px border radius, 12px vertical padding, 16px horizontal padding, background Pristine Mist for active states.

### Hero Headline
**Role:** Dominant page title in hero section

ABCDiatypeExpanded-Bold, size 78px-82px, color Canvas White, letter spacing -0.0200em.

### Content Headline
**Role:** Section or detail page headlines

ABCDiatypeExpanded-Bold, size 40px, color Midnight Ink, letter spacing -0.0100em.

## Do's and Don'ts

### Do
- Use Midnight Ink (#181f1f) for all primary text and dominant UI elements to maintain high contrast.
- Apply 64px border radius to all interactive buttons and navigation items for a consistent modern softness.
- Utilize ABCDiatypeExpanded-Bold for all major headlines to create an impactful and authoritative presence.
- Employ the Motion Blur Gradient as a background for hero sections or key visual statements to convey energy.
- Maintain a clear visual hierarchy by using Canvas White (#ffffff) as the dominant background color for content areas.
- Ensure generous spacing; use 180px between major sections and 16px for element gaps to create a comfortable density.
- Reserve Lagoon Violet (#516fea) exclusively for outlining secondary buttons or for subtle interactive accents.

### Don't
- Do not introduce new primary colors; the palette is intentionally limited to high-contrast neutrals with a singular accent.
- Avoid generic border radii; adhere strictly to 64px for buttons, 54px for inputs, and 40px for cards.
- Do not use highly saturated colors for large UI areas; color is used sparingly for impact and functionality.
- Do not center text bodies or long paragraphs; align left to maintain readability and structure.
- Avoid heavy shadows or complex elevation; the design relies on flat surfaces and high contrast.
- Do not use standard sans-serif fonts for headlines; always use ABCDiatypeExpanded-Bold for its distinctive character.
- Do not use pixel-perfect spacing for every element; rely on the base unit of 4px and established spacing tokens.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pristine Mist Canvas | `#eaf7f3` | Primary page background for a fresh, clean base. |
| 1 | Canvas White Content | `#ffffff` | Default background for most content blocks and cards atop the canvas. |
| 2 | Deep Mocha Section | `#1f3233` | Distinct, darker background for contrasting content sections. |
| 3 | Midnight Ink Elevated | `#181f1f` | Darkest background for high-contrast elements, filled buttons, or specific feature areas. |
| 4 | Graphite Overlay | `#000000` | Used for hero background if not gradient, or as a very dark, impactful surface. |

## Imagery

This site utilizes two distinct imagery styles: a dynamic, motion-blurred linear gradient for its hero and static, clean product photography within content sections. The gradient primarily serves as a decorative, atmospheric backdrop, conveying energy and movement. Product photography is typically contained, focuses on the object itself, and often features a minimal or white background to maintain clarity and focus, contrasting with the vibrant hero. Icons, if present, are likely subtle or integrated into the typographic style.

## Layout

The page primarily uses a full-bleed layout, particularly for its hero section where a dynamic gradient spans the entire viewport. Content sections feature a max-width, maintaining comfortable readability on wider screens. The rhythm alternates between stark white and occasional darker background sections, creating clear content blocks. Content is arranged in alternating text-left/image-right or stacked, centered compositions, emphasizing strong headlines. Vertical spacing is generous, particularly the 180px section gap, contributing to an airy, 'comfortable' density.

## Agent Prompt Guide

Quick Color Reference:
text: #181f1f
background: #eaf7f3
border: #d1d2d2
accent: #516fea
primary action: #181f1f (filled action)

Example Component Prompts:
1. Create a Hero Section with a full-bleed Motion Blur Gradient background. Overlay the text 'RAGGED EDGE' using ABCDiatypeExpanded-Bold, size 82px, color Canvas White, letter-spacing -0.0200em.
2. Create a Primary Action Button: #181f1f background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Implement a Content Section displaying a headline 'Never be the same again' using ABCDiatypeExpanded-Bold, size 40px, color Midnight Ink, letter-spacing -0.0100em. Below, add body text 'Ragged Edge is a brand company...' using Grit-Regular, size 16px, color Midnight Ink.
4. Create a Ghost Navigation Item for 'Happenings' using Grit-Regular, size 14px, color Midnight Ink at 40% opacity, 0px padding, 0px radius.

## Similar Brands

- **AIGA** — High-contrast, bold typography and a modern, spacious layout with strong visual impact.
- **Huge** — Prominent use of large, impactful headlines, clean layouts, and a limited color palette focused on brand messaging.
- **Pentagram** — Emphasis on strong typography, high-contrast visuals, and a minimalist approach to color save for impactful accents.
- **FutureBrand** — Modern design agency aesthetic with significant whitespace, strong grid structures, and clear typographic hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #181f1f;
  --color-canvas-white: #ffffff;
  --color-fog-gray: #d1d2d2;
  --color-muted-slate: #a3a5a5;
  --color-graphite: #000000;
  --color-pristine-mist: #eaf7f3;
  --color-lagoon-violet: #516fea;
  --color-deep-mocha: #1f3233;
  --color-motion-blur-gradient: #ffc240;
  --gradient-motion-blur-gradient: linear-gradient(0deg, rgba(255, 194, 64, 0), rgb(255, 194, 64), rgb(255, 196, 244), rgb(150, 235, 235), rgba(150, 235, 235, 0));
  --color-alert-red: #f56565;

  /* Typography — Font Families */
  --font-grit-regular: 'Grit-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcdiatypeexpanded-bold: 'ABCDiatypeExpanded-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.2px;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --tracking-heading: -0.4px;
  --text-display: 78px;
  --leading-display: 1.1;
  --tracking-display: -1.56px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 180px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 54px;
  --radius-full-2: 64px;

  /* Named Radii */
  --radius-cards: 40px;
  --radius-inputs: 54px;
  --radius-buttons: 64px;
  --radius-navigationitems: 64px;

  /* Surfaces */
  --surface-pristine-mist-canvas: #eaf7f3;
  --surface-canvas-white-content: #ffffff;
  --surface-deep-mocha-section: #1f3233;
  --surface-midnight-ink-elevated: #181f1f;
  --surface-graphite-overlay: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #181f1f;
  --color-canvas-white: #ffffff;
  --color-fog-gray: #d1d2d2;
  --color-muted-slate: #a3a5a5;
  --color-graphite: #000000;
  --color-pristine-mist: #eaf7f3;
  --color-lagoon-violet: #516fea;
  --color-deep-mocha: #1f3233;
  --color-motion-blur-gradient: #ffc240;
  --color-alert-red: #f56565;

  /* Typography */
  --font-grit-regular: 'Grit-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcdiatypeexpanded-bold: 'ABCDiatypeExpanded-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.2px;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --tracking-heading: -0.4px;
  --text-display: 78px;
  --leading-display: 1.1;
  --tracking-display: -1.56px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 54px;
  --radius-full-2: 64px;
}
```
