# Nuri — Style Reference
> Bitcoin on lavender canvas

**Theme:** light

Nuri presents a financial clarity aesthetic: clean, spacious layouts with a focus on bold typography and functional accents. The interface marries a muted, almost pastel color story with crisp dark text, creating an approachable yet authoritative tone. Visual hierarchy is established through stark size differences in typography rather than heavy graphic elements, and rounded shapes maintain a friendly, modern feel across interactive components.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Lavender Mist | `radial-gradient(circle at 50% 0%, rgba(190, 170, 255, 0.45), rgba(0, 0, 0, 0) 48%)` | `--color-lavender-mist` | Hero background, primary brand presence for large visual blocks; Decorative radial gradient for card backgrounds, adding depth with a subtle brand tint |
| Deep Plum | `#2c232e` | `--color-deep-plum` | Primary text, button backgrounds for filled actions, and prominent headings. Creates a strong contrast against lighter backgrounds |
| Slate Text | `#4b5563` | `--color-slate-text` | Secondary text and link colors, providing readability while allowing primary text to stand out |
| Phantom Gray | `#6b7280` | `--color-phantom-gray` | Muted body text and less prominent informational elements |
| Powder Violet | `#e2d9ff` | `--color-powder-violet` | Subtle background for card-like elements, adding a soft, branded surface without being overwhelming |
| Charcoal Icon | `#374151` | `--color-charcoal-icon` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |
| Amber Action | `#f97316` | `--color-amber-action` | Background for primary call-to-action buttons, drawing immediate attention |
| Gallery White | `#ffffff` | `--color-gallery-white` | Page backgrounds, button text on filled actions, and general surface elevation |
| Whisper White | `#f7f2ff` | `--color-whisper-white` | Canvas background, providing a slightly warmer and softer base than pure white |
| Cloud Gray | `#f9fafb` | `--color-cloud-gray` | Secondary background for footer sections or differentiating content blocks |
| Pale Border | `#e2e8f0` | `--color-pale-border` | Hairline borders and dividers, maintaining visual separation without heavy lines |
| Ash Border | `#d1d5db` | `--color-ash-border` | Subtle borders for outlined components |
| Shadow Tint | `#dddcde` | `--color-shadow-tint` | Supporting neutral for secondary UI, dividers, and muted labels. Do not promote it to the primary CTA color |

## Tokens — Typography

### Sharp Grotesk Bold — Display headings. The extreme letter-spacing and heavy weight create a high-impact, almost shouted statement. · `--font-sharp-grotesk-bold`
- **Substitute:** Montserrat Black
- **Weights:** 900
- **Sizes:** 72px, 118px
- **Line height:** 0.90, 1.00
- **Letter spacing:** -0.02, 0.018
- **Role:** Display headings. The extreme letter-spacing and heavy weight create a high-impact, almost shouted statement.

### Harriet Display — Large subheadings and decorative text. Its lighter weights at large sizes offer a classic, almost editorial counterpoint to the bold display font. · `--font-harriet-display`
- **Substitute:** Playfair Display
- **Weights:** 300, 400
- **Sizes:** 24px, 30px, 50px, 55px, 62px, 112px
- **Line height:** 0.90, 0.94, 1.20, 1.33
- **Letter spacing:** normal
- **Role:** Large subheadings and decorative text. Its lighter weights at large sizes offer a classic, almost editorial counterpoint to the bold display font.

### Inter — All body text, interface labels, and smaller functional elements. It provides legibility and a modern, versatile foundation. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 15px, 16px, 17px, 20px, 24px, 28px, 32px
- **Line height:** 0.90, 1.00, 1.20, 1.32, 1.33, 1.40, 1.43, 1.50, 1.63
- **Letter spacing:** normal
- **Role:** All body text, interface labels, and smaller functional elements. It provides legibility and a modern, versatile foundation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body-lg | 17px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 32px | 1.33 | — | `--text-heading` |
| heading-lg | 62px | 0.94 | — | `--text-heading-lg` |
| display | 118px | 0.9 | -0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

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
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 9999px |
| buttons | 8px |
| general | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle | `rgba(44, 35, 46, 0.16) 0px 0px 0px 1px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with Amber Action (#f97316) background and Gallery White (#ffffff) text. Features 9999px radius for a pill shape, and 10px vertical, 16px horizontal padding. A subtle shadow of rgba(44,35,46,0.16) 0px 0px 0px 1px provides slight elevation.

### Ghost Button
**Role:** Secondary action

Transparent background with Charcoal Icon (#374151) text. Features 9999px radius and 0px vertical, 14px horizontal padding. Border is subtle Pale Border (#e2e8f0).

### Flag Selector Button
**Role:** Language or region selection

Subtly opaque Gallery White (rgba(255, 255, 255, 0.9)) background with Slate Text (#4b5563) text. Features 8px radius and 8px vertical, 12px horizontal padding. Border in Ash Border (#d1d5db).

### Large Hero Heading
**Role:** Brand statement

Sharp Grotesk Bold font, 118px size, 900 weight, Deep Plum (#2c232e) color, with a pronounced -0.02em letter-spacing. Anchors the hero section with a bold statement.

### Subtle Card
**Role:** Content container

Background of Powder Violet (#e2d9ff) with an extreme 9999px border-radius, giving it a playful, organic shape. Often employs a Radial Card Highlight gradient effect, from Lavender Mist (#beaaff) to transparent.

### Input Field
**Role:** Data entry

Transparent background with Deep Plum (#2c232e) text. Features 8px vertical, 12px horizontal padding. Pale Border (#e2e8f0) bottom border for a minimal, clean appearance.

## Do's and Don'ts

### Do
- Use Sharp Grotesk Bold at 900 weight for high-impact display text, applying -0.02em letter-spacing at large sizes.
- Employ Lavender Mist (#beaaff) for large background sections or as a brand-identifying visual anchor.
- Apply 9999px border-radius to all buttons and card-like elements to maintain the system's friendly, rounded aesthetic.
- Utilize Deep Plum (#2c232e) for all primary text and critical headings to ensure strong legibility and brand presence.
- Maintain generous vertical spacing between sections, primarily using 48px to create an open and spacious layout.
- Apply Amber Action (#f97316) exclusively for primary call-to-action button backgrounds.
- Use Pale Border (#e2e8f0) for all unhovered borders and subtle dividers to keep the interface light and decluttered.

### Don't
- Avoid using multiple vibrant colors for primary actions; Amber Action (#f97316) is reserved for this purpose to ensure clear hierarchy.
- Do not deviate from the established rounded border-radius values; square corners contradict the system's soft, approachable feel.
- Refrain from using heavy shadows or strong elevation effects; rely on color contrast and typographic scale for hierarchy.
- Do not introduce additional gray tones that are not present in the defined neutral palette, as this will lead to visual inconsistency.
- Avoid overly dense layouts; maintain a spacious design with consistent element and section gaps (24px and 48px respectively).
- Do not use generic system fonts in place of Inter, Harriet Display, or Sharp Grotesk Bold; their specific characteristics define the brand's typographic voice.
- Avoid using Lavender Mist (#beaaff) as a text color; it is intended for large background fills or decorative purposes only.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Whisper White Canvas | `#f7f2ff` | Dominant page background, providing a soft, slightly off-white base for all content. |
| 2 | Gallery White Surface | `#ffffff` | Default background for most UI components and content blocks that need to stand out from the canvas. |
| 3 | Powder Violet Card | `#e2d9ff` | Distinctive background for card elements, using a branded color at a subtle tint. |

## Elevation

- **Primary Action Button:** `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px, rgba(44, 35, 46, 0.16) 0px 0px 0px 1px`

## Imagery

The visual language combines abstract, product-focused illustrations with clean product shots. Illustrations are dimensional and stylized, featuring human figures in everyday tech interactions against subtle background elements, often in brand-aligned purple or green hues. Photography, when present, focuses on tight product crops without extensive lifestyle context. Iconography is clean and outlined, maintaining a light visual weight. Imagery serves to explain product features or create atmospheric context without overwhelming UI elements.

## Layout

The page primarily uses a max-width contained layout, though the hero section often stretches full-bleed. The hero features a large, impactful centered headline against a colored background, sometimes split with a visual element. Section rhythm is generally consistent with substantial vertical spacing (48px section gap). Content is arranged in alternating text-left/image-right or centered stacks. Card-like containers, when present, utilize the distinct 'pill' shape. Navigation is handled by a minimal top bar, with elements pushed to the far corners.

## Agent Prompt Guide

Quick Color Reference:
text: #2c232e
background: #f7f2ff
border: #e2e8f0
accent: #beaaff
primary action: #f97316 (filled action)

Example Component Prompts:

Create a hero section: Whisper White canvas (#f7f2ff). Centered headline 'YOUR MONEY, REDEFINED.' in Sharp Grotesk Bold, 118px, 900 weight, Deep Plum (#2c232e), letter-spacing -0.02em. Subtext 'Instant, secure, and ready for you.' in Harriet Display, 50px, 300 weight, Deep Plum (#2c232e).

Create a Primary Action Button: #f97316 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a ghost navigation button labeled 'Log In': transparent background, Charcoal Icon (#374151) text (Inter, 16px, 400 weight), 9999px radius, Pale Border (#e2e8f0) border, 0px vertical, 14px horizontal padding.

Create a pricing card: Powder Violet (#e2d9ff) background, 9999px radius, 12px cardPadding. Headline 'Basic Plan' in Deep Plum (#2c232e), Inter, 24px, 600 weight. Body text 'Access essential features.' in Charcoal Icon (#374151), Inter, 16px, 400 weight.

## Similar Brands

- **Revolut** — Clean digital banking aesthetic, strong typography, and a modern, often colorful, brand accent against mostly monochrome UI.
- **Stripe** — Emphasis on clear, direct typography, spacious layouts, and a restrained color palette with strategic, bold color accents for impact.
- **Monzo** — Friendly and approachable fintech aesthetic with rounded corners, clear communication, and a distinctive primary brand color.
- **Wise (formerly TransferWise)** — Focus on clarity and trust through clean UI, simple typography, and functional use of color for status and actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-lavender-mist: #beaaff;
  --gradient-lavender-mist: radial-gradient(circle at 50% 0%, rgba(190, 170, 255, 0.45), rgba(0, 0, 0, 0) 48%);
  --color-deep-plum: #2c232e;
  --color-slate-text: #4b5563;
  --color-phantom-gray: #6b7280;
  --color-powder-violet: #e2d9ff;
  --color-charcoal-icon: #374151;
  --color-amber-action: #f97316;
  --color-gallery-white: #ffffff;
  --color-whisper-white: #f7f2ff;
  --color-cloud-gray: #f9fafb;
  --color-pale-border: #e2e8f0;
  --color-ash-border: #d1d5db;
  --color-shadow-tint: #dddcde;

  /* Typography — Font Families */
  --font-sharp-grotesk-bold: 'Sharp Grotesk Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-harriet-display: 'Harriet Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --text-heading-lg: 62px;
  --leading-heading-lg: 0.94;
  --text-display: 118px;
  --leading-display: 0.9;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 9999px;
  --radius-buttons: 8px;
  --radius-general: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle: rgba(44, 35, 46, 0.16) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-whisper-white-canvas: #f7f2ff;
  --surface-gallery-white-surface: #ffffff;
  --surface-powder-violet-card: #e2d9ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-lavender-mist: #beaaff;
  --color-deep-plum: #2c232e;
  --color-slate-text: #4b5563;
  --color-phantom-gray: #6b7280;
  --color-powder-violet: #e2d9ff;
  --color-charcoal-icon: #374151;
  --color-amber-action: #f97316;
  --color-gallery-white: #ffffff;
  --color-whisper-white: #f7f2ff;
  --color-cloud-gray: #f9fafb;
  --color-pale-border: #e2e8f0;
  --color-ash-border: #d1d5db;
  --color-shadow-tint: #dddcde;

  /* Typography */
  --font-sharp-grotesk-bold: 'Sharp Grotesk Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-harriet-display: 'Harriet Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --text-heading-lg: 62px;
  --leading-heading-lg: 0.94;
  --text-display: 118px;
  --leading-display: 0.9;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle: rgba(44, 35, 46, 0.16) 0px 0px 0px 1px;
}
```
