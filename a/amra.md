# amra — Style Reference
> Frosted glass clarity

**Theme:** light

Amra presents a clean, spacious interface built on a predominantly achromatic palette, punctuated by a single vibrant violet. Text hierarchy is established through size and subtle gray tones rather than bold weights. Components are lightweight with generous padding and distinct corner radii, often featuring frosted glass-like backdrops, creating a sense of digital clarity and depth.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#141414` | `--color-midnight-ink` | Primary text, heading text, strong borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary surfaces |
| Subtle Gray | `#a1a1a1` | `--color-subtle-gray` | Secondary text, muted headings, subtle borders |
| Platinum Mist | `#d0d0d0` | `--color-platinum-mist` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Ash Cloud | `#8a8a8a` | `--color-ash-cloud` | Muted navigation text, tertiary information |
| Future Violet | `#acafff` | `--color-future-violet` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Primary Font — Primary Font — detected in extracted data but not described by AI · `--font-primary-font`
- **Weights:** 400
- **Sizes:** 20px, 30px, 50px
- **Line height:** 1, 1.2
- **Letter spacing:** -0.01
- **Role:** Primary Font — detected in extracted data but not described by AI

### Inter — Headings and prominent body text. The tight letter spacing at larger sizes gives a refined, composed feel. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.0100em
- **Role:** Headings and prominent body text. The tight letter spacing at larger sizes gives a refined, composed feel.

### Inter — Navigation, body copy, and peripheral information. Slightly expanded letter spacing aids readability at smaller scales. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** 0.0290em
- **Role:** Navigation, body copy, and peripheral information. Slightly expanded letter spacing aids readability at smaller scales.

### Secondary Font — Secondary Font — detected in extracted data but not described by AI · `--font-secondary-font`
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1, 2.29
- **Letter spacing:** 0.029
- **Role:** Secondary Font — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1 | 0.464px | `--text-body-sm` |
| body | 16px | 2.29 | 0.464px | `--text-body` |
| subheading | 20px | 1 | -0.2px | `--text-subheading` |
| heading | 30px | 1.2 | -0.3px | `--text-heading` |
| display | 50px | 1.2 | -0.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

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
| 56 | 56px | `--spacing-56` |
| 100 | 100px | `--spacing-100` |
| 104 | 104px | `--spacing-104` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 44px |
| forms | 8px |
| links | 24px |
| buttons | 8px |
| general | 16px |

### Layout

- **Section gap:** 100px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Navigation Button
**Role:** Call to action button in the navigation bar.

Background in Future Violet (#acafff), text in Canvas White (#ffffff), with a corner radius of 8px. It's designed for strong visual impact.

### Navigation Link
**Role:** Standard navigation items.

Text in Midnight Ink (#141414) for current/active states, Ash Cloud (#8a8a8a) for inactive states. Uses Primary Font (Inter, 400, 16px).

### Ghost Button
**Role:** Secondary call to action, offering a less dominant interaction.

Border in Platinum Mist (#d0d0d0) with a 1px solid stroke, no background fill, text in Midnight Ink (#141414). Radius is 24px, indicating a softer, less urgent action.

### Feature Card with Backwash
**Role:** Container for showcasing key features or content blocks.

Background set to rgba(243, 244, 245, 0.4), appearing as a translucent white. Features a generous 44px border-radius, creating a soft, distinct shape. Inner content is positioned with 4px left padding, 32px right padding, and no top/bottom padding relative to the card's boundaries.

### Video Player Icon
**Role:** Interactive element to trigger video content.

A circular icon with a blur(35px) backdrop filter and a light blue to green gradient fill. Text is in Canvas White (#ffffff) set at 14px, indicating a caption or descriptor.

## Do's and Don'ts

### Do
- Use Midnight Ink (#141414) for primary text and headings, employing Subtle Gray (#a1a1a1) for secondary text and muted descriptions.
- Maintain a spacious layout with a section gap of 100px, ensuring generous vertical breathing room between content blocks.
- Apply a 44px border-radius to card-like elements, establishing a distinct soft-edged visual identity.
- Utilize Future Violet (#acafff) strictly for primary interactive backgrounds (e.g., 'Sign In' button) to draw immediate attention.
- Implement backdrop-filter: blur() effects for overlays or selected background cards to evoke a frosted glass aesthetic.
- Ensure all headings use the Primary Font (Inter, 400) with a tight letter-spacing of -0.0100em to achieve a composed, authoritative appearance.

### Don't
- Do not introduce additional saturated colors beyond Future Violet (#acafff) for UI elements; maintain the monochromatic base.
- Avoid heavy shadows or strong elevation; the design favors flat surfaces and subtle, atmospheric blurs for depth.
- Do not use highly contrasting or bold font weights; rely on size and gray scale for typographic hierarchy.
- Do not clutter content within cards; respect the 32px padding and 44px radius, allowing elements within to breathe.
- Refrain from using square or sharp corners for interactive elements or cards; the system prefers soft, rounded edges.
- Do not use dark backgrounds across full sections; the theme is predominantly light, with white canvas and subtle transparent overlays.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background |
| 1 | Card Backwash | `#f3f4f5` | Translucent background for cards, creating a frosted effect with `rgba(243, 244, 245, 0.4)` |

## Imagery

The site predominantly uses abstract, volumetric digital renders, specifically large, blurred gradients that act as ethereal background elements or visual anchors. When photography is present, it's typically high-contrast silhouette imagery, focusing on human interaction with technology, often featuring cool color overlays. Icons are simple, outlined, and monochromatic, used sparingly for functional cues. Imagery serves an atmospheric and mood-setting role, providing a soft, artistic counterpoint to the sharp typography and clean UI.

## Layout

The page adheres to a centered maximum-width layout for main content, though the hero section features a full-bleed background gradient graphic. The hero presents a centered headline stack, often with a large, volumetric gradient at the bottom. Sections maintain a consistent vertical rhythm, primarily using a `sectionGap` of 100px. Content within sections frequently features a two-column alternating text-right/image-left pattern or stacked, centered blocks. The navigation is a sticky top bar with links aligned left and a primary action button to the right.

## Agent Prompt Guide

### Quick Color Reference
text: #141414
background: #ffffff
border: #141414
accent: #acafff
primary action: no distinct CTA color

### 3-5 Example Component Prompts
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a hero section headline: 'Global royalties made simple' using `font-family: Inter, 400, 50px`, `color: #141414`, `line-height: 1.2`, `letter-spacing: -0.5px`.
3. Create a `Ghost Button`: 'Explore the platform' using `border: 1px solid #d0d0d0`, `color: #141414`, `border-radius: 24px`, `padding: 12px 16px`, `font-family: Inter, 400, 16px`, `letter-spacing: 0.464px`.
4. Design a `Feature Card with Backwash`: `background: rgba(243, 244, 245, 0.4)`, `backdrop-filter: blur(35px)`, `border-radius: 44px`, `padding: 0px 32px 0px 4px`.

## Similar Brands

- **Stripe** — Shares a clean, almost monochrome interface with a single vibrant accent color used for primary actions and highlights.
- **Linear** — Exhibits a similar focus on crisp typography, generous whitespace, and minimal, functional UI components achieving a 'fast' aesthetic.
- **Supabase** — Combines a white canvas with select, well-placed gradient elements or abstract backgrounds to add visual interest without clutter.
- **Vercel** — Utilizes a highly structured grid-based layout and a restrained color palette, often with translucent surface treatments for modular content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #a1a1a1;
  --color-platinum-mist: #d0d0d0;
  --color-ash-cloud: #8a8a8a;
  --color-future-violet: #acafff;

  /* Typography — Font Families */
  --font-primary-font: 'Primary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-secondary-font: 'Secondary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: 0.464px;
  --text-body: 16px;
  --leading-body: 2.29;
  --tracking-body: 0.464px;
  --text-subheading: 20px;
  --leading-subheading: 1;
  --tracking-subheading: -0.2px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.3px;
  --text-display: 50px;
  --leading-display: 1.2;
  --tracking-display: -0.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 44px;

  /* Named Radii */
  --radius-cards: 44px;
  --radius-forms: 8px;
  --radius-links: 24px;
  --radius-buttons: 8px;
  --radius-general: 16px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-card-backwash: #f3f4f5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #141414;
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #a1a1a1;
  --color-platinum-mist: #d0d0d0;
  --color-ash-cloud: #8a8a8a;
  --color-future-violet: #acafff;

  /* Typography */
  --font-primary-font: 'Primary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-secondary-font: 'Secondary Font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: 0.464px;
  --text-body: 16px;
  --leading-body: 2.29;
  --tracking-body: 0.464px;
  --text-subheading: 20px;
  --leading-subheading: 1;
  --tracking-subheading: -0.2px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.3px;
  --text-display: 50px;
  --leading-display: 1.2;
  --tracking-display: -0.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 44px;
}
```
