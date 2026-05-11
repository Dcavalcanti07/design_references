# Lightship — Style Reference
> Black & White Canvas: a crisp, high-contrast visual journey on a warm, earthy canvas.

**Theme:** light

Lightship embraces a rugged, understated aesthetic, emphasizing content through a play of stark black and white interrupted by natural textures. Typography is compact and precise, maintaining clarity across varied scales. Interactive elements are either subtly integrated or appear as stark, high-contrast outlines against the dominant photographic or canvas backgrounds. The design prioritizes visual storytelling and a confident, unembellished presentation, using a warm off-white canvas and pure black to define primary surfaces and text.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pure Black | `#000000` | `--color-pure-black` | Primary text, strong borders, dark surface backgrounds, monochrome icons. Used for high-emphasis elements against light backgrounds |
| Canvas | `#ffffff` | `--color-canvas` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Paper White | `#faf6ef` | `--color-paper-white` | Secondary background surfaces and card fills – a warm, muted off-white providing depth to the primary Canvas |
| Subtle Gray | `#999999` | `--color-subtle-gray` | Muted text, secondary borders, subtle dividers. Offers reduced contrast for less critical information |
| Outline Gray | `#d9d9d9` | `--color-outline-gray` | Hairline borders and separators, providing minimal visual interruption |
| Medium Gray | `#a1a1a1` | `--color-medium-gray` | Supporting text, decorative elements, and lower-priority informational text |
| Action Orange | `#fa5c40` | `--color-action-orange` | Decorative background accents, notably for visual emphasis in content areas |

## Tokens — Typography

### F37Bolton — Primary brand typeface for all text content, from body to display headlines. Its compact, confident demeanor supports both functional clarity and bold statements. · `--font-f37bolton`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 20px, 22px, 24px, 34px, 48px, 64px, 72px, 75px
- **Line height:** 1.00, 1.20, 1.25
- **Letter spacing:** -0.0500em, -0.0300em
- **Role:** Primary brand typeface for all text content, from body to display headlines. Its compact, confident demeanor supports both functional clarity and bold statements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.25 | — | `--text-caption` |
| body-sm | 14px | 1.25 | — | `--text-body-sm` |
| body | 16px | 1.25 | — | `--text-body` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.48px | `--text-heading-sm` |
| heading | 34px | 1.2 | — | `--text-heading` |
| heading-lg | 48px | 1.2 | -1.44px | `--text-heading-lg` |
| display | 75px | 1 | -2.25px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| links | 20px |
| inputs | 100px |
| buttons | 20px |

### Layout

- **Section gap:** 100px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Text Button - Dark
**Role:** Ghost

Text in Pure Black, no background or border, used for navigation and secondary actions on light backgrounds. No padding. Border radius 0px.

### Text Button - Light
**Role:** Ghost

Text in Canvas white, no background or border, primarily for navigation and secondary actions on dark backgrounds. No padding. Border radius 0px.

### Outlined Button - Light
**Role:** Ghost

Text in Canvas white with a Canvas white border (1px). Used for high-contrast actions on dark backgrounds. Border radius 20px. No padding.

### Outlined Button - Dark
**Role:** Ghost

Text in Pure Black with a Pure Black border (1px). Used for high-contrast actions on light backgrounds. Border radius 20px. No padding.

### Default Card
**Role:** Content Container

Cards maintain the flat aesthetic with `0px` border-radius and `0px` padding, adapting their background to either Canvas or Paper White, and carrying no shadow.

### Circular Input
**Role:** Text Input

Transparent background with Pure Black text and border, featuring `100px` border-radius for a pill shape. Text is centered. Padding of `24px` on left/right edges.

## Do's and Don'ts

### Do
- Prioritize F37Bolton weight 400 for body text at 16px with Pure Black (#000000) for high readability.
- Use Canvas white (#ffffff) for all primary page backgrounds and component surfaces to maintain a clean, bright aesthetic.
- Apply a 20px border radius to all interactive links and buttons where a radius is needed, ensuring a consistent softened edge.
- Utilize Pure Black (#000000) for all significant borders, including interactive states and menu outlines.
- Maintain minimal padding values like 8px or 16px for comfortable density in elements like list items and small components.
- Ensure all card elements have a border radius of 0px to preserve the sharp, modern edge of content blocks.
- Leverage F37Bolton weight 700 with generous sizes (48px, 64px, 75px) for headlines, using a line-height of 1.0 to 1.2 for compact impact.

### Don't
- Avoid using multiple chromatic colors; limit vibrant accents to the Action Orange (#fa5c40) for specific decorative purposes not as interactive states.
- Do not introduce shadows or artificial elevation, as the design system relies on flat surfaces and high-contrast outlines.
- Do not use highly saturated colors for text or primary UI elements; reserve them for decorative highlights only.
- Avoid large horizontal padding on content sections; the design uses full-bleed imagery and minimal margins for key content.
- Do not use generic system fonts; F37Bolton is core to the brand's typographic identity.
- Resist using gradients or complex background patterns; the design is characterized by solid colors and photographic content contrasting with clean UI.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, general container surfaces. |
| 1 | Paper White | `#faf6ef` | Secondary background for cards and specific content blocks, providing subtle visual separation. |

## Imagery

The imagery features high-resolution lifestyle and product photography of outdoor adventures and the Lightship travel trailer. Photos are often full-bleed or large, contained rectangles with subtly rounded corners (sometimes 20px radius). They are primarily natural, candid, and aspirational, showcasing the product in its intended use context. The overall tone is authentic and rugged, with a focus on immersive scenes and direct product views. Icons are monochrome, simple, and outlined, used functionally within the UI.

## Layout

The page primarily uses a full-bleed layout for hero sections, featuring large photography with overlaying text. Subsequent sections tend towards a more constrained, centered content approach, often arranging content in asymmetric compositions or overlapping elements that break a rigid grid. Section gaps are generous, notably 100px, creating ample whitespace. Navigation is a sticky top bar with minimal links, becoming a floating, semi-transparent bar upon scroll. There are no strict card grids, but rather artfully arranged images that create dynamic visual flow.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #000000
- accent: #fa5c40
- primary action: no distinct CTA color

Example Component Prompts:
- Create a hero section: full-bleed dark photographic background. Headline 'Born for Adventure.' F37Bolton 75px, weight 700, #ffffff, line-height 1.0, letter-spacing -2.25px. Subtext 'Built in America.' F37Bolton 75px, weight 700, #ffffff, line-height 1.0, letter-spacing -2.25px.
- Create a navigation menu item: Text 'AE.1' F37Bolton 16px, weight 400, #000000. No background, no border. Border radius 0px.
- Create an outlined action button for a dark background: Text 'Register' F37Bolton 16px, weight 400, #ffffff. Background rgba(0, 0, 0, 0). Border 1px solid #ffffff. Border radius 20px. No padding.
- Create a testimonial card: Background Paper White (#faf6ef). Content heading F37Bolton 34px, weight 400, #000000, line-height 1.2. Body text F37Bolton 16px, weight 400, #000000. No border, border radius 0px, padding 24px.

## Similar Brands

- **Rivian** — Shares a focus on electric adventure vehicles, using high-quality outdoor photography and a clean, modern aesthetic with minimal UI chrome.
- **Tesla** — Employs an unembellished, confident visual tone with a strong emphasis on product photography and high-contrast typography against clean backgrounds.
- **Aer** — Similar high-contrast monochrome approach with subtle, warm neutrals, and a focus on product visuals and a precise typographic system.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pure-black: #000000;
  --color-canvas: #ffffff;
  --color-paper-white: #faf6ef;
  --color-subtle-gray: #999999;
  --color-outline-gray: #d9d9d9;
  --color-medium-gray: #a1a1a1;
  --color-action-orange: #fa5c40;

  /* Typography — Font Families */
  --font-f37bolton: 'F37Bolton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.48px;
  --text-heading: 34px;
  --leading-heading: 1.2;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.44px;
  --text-display: 75px;
  --leading-display: 1;
  --tracking-display: -2.25px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-links: 20px;
  --radius-inputs: 100px;
  --radius-buttons: 20px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-paper-white: #faf6ef;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pure-black: #000000;
  --color-canvas: #ffffff;
  --color-paper-white: #faf6ef;
  --color-subtle-gray: #999999;
  --color-outline-gray: #d9d9d9;
  --color-medium-gray: #a1a1a1;
  --color-action-orange: #fa5c40;

  /* Typography */
  --font-f37bolton: 'F37Bolton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.48px;
  --text-heading: 34px;
  --leading-heading: 1.2;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.44px;
  --text-display: 75px;
  --leading-display: 1;
  --tracking-display: -2.25px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-full: 100px;
}
```
