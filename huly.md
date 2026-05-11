# Huly — Style Reference
> Midnight Command Center

**Theme:** dark

Huly uses a luminous Dark Mode aesthetic, pairing deep, almost black backgrounds with stark white text and electric accent colors. Product surfaces are treated as frosted glass overlays with subtle elevation. Typography is precise and utilitarian, with compact headlines creating a sense of density. Accents are used sparingly to highlight interactive elements and create a dynamic, glowing experience against the dark canvas.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#090a0c` | `--color-pitch-black` | Primary background for the page canvas and prominent sections, creating a deep, immersive dark mode |
| Charcoal Grey | `#111111` | `--color-charcoal-grey` | Background for elevated cards and section headers, providing a subtle lift from the canvas |
| Shadow Ink | `#303236` | `--color-shadow-ink` | General text, input borders, and dividers where contrast with lighter elements is needed |
| Ash Cloud | `#4a4b50` | `--color-ash-cloud` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Storm Grey | `#61656b` | `--color-storm-grey` | Muted helper text and hairline borders, offering gentle visual separation |
| Battleship Grey | `#95979e` | `--color-battleship-grey` | Secondary body text and subtle icon fills for less prominent information |
| Silver Mist | `#a9a9aa` | `--color-silver-mist` | Placeholder text and disabled states, a lighter shade for low-priority elements |
| Cloud Burst | `#d1d1d1` | `--color-cloud-burst` | Ghost button background or border for secondary actions, appearing as a soft highlight |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text, critical icons, and active states, standing out starkly against dark backgrounds |
| Electric Blue | `#5683da` | `--color-electric-blue` | Call-to-action button backgrounds and primary interactive elements, providing a strong visual magnet |
| Sunset Orange | `#ff8964` | `--color-sunset-orange` | Decorative highlights and secondary accent where a warm glow is desired |
| Warm Ivory Gradient | `linear-gradient(103.7deg, rgba(188, 155, 143, 0.1) 38.66%, rgba(233, 132, 99, 0.1) 68.55%, rgb(233, 132, 99) 85.01%, rgb(255, 255, 255) 92.12%)` | `--color-warm-ivory-gradient` | Subtle background gradient for certain sections or cards, contributing to an ethereal glow |
| Peach Bloom Gradient | `linear-gradient(90deg, rgb(255, 235, 164) 50%, rgba(0, 0, 0, 0) 50%)` | `--color-peach-bloom-gradient` | Decorative background gradient used for soft, warm visual interest |

## Tokens — Typography

### Esbuild — Display and main section headings. The tight line heights and significant letter-spacing control create a dense, impactful statement, giving these headlines a commanding but not overwhelming presence. It’s a custom-selected font that provides distinctive character. · `--font-esbuild`
- **Substitute:** Montserrat
- **Weights:** 400, 500, 600
- **Sizes:** 28px, 32px, 80px, 84px
- **Line height:** 0.80, 0.90, 1.00
- **Letter spacing:** -0.0500em, -0.0400em, -0.0300em, -0.0200em
- **Role:** Display and main section headings. The tight line heights and significant letter-spacing control create a dense, impactful statement, giving these headlines a commanding but not overwhelming presence. It’s a custom-selected font that provides distinctive character.

### Inter — All body text, subheadings, navigation, and UI elements. Inter is chosen for its clarity and legibility at various sizes, offering functional precision across the interface. Varied weights handle hierarchy in smaller text blocks. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 18px, 22px, 24px
- **Line height:** 1.00, 1.13, 1.25, 1.38, 1.50
- **Letter spacing:** -0.0400em, -0.0200em, -0.0150em, -0.0100em
- **Role:** All body text, subheadings, navigation, and UI elements. Inter is chosen for its clarity and legibility at various sizes, offering functional precision across the interface. Varied weights handle hierarchy in smaller text blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.4px | `--text-caption` |
| body-lg | 14px | 1.5 | -0.56px | `--text-body-lg` |
| heading-sm | 22px | 1.25 | -0.44px | `--text-heading-sm` |
| heading | 28px | 1 | -1.4px | `--text-heading` |
| heading-lg | 32px | 0.9 | -1.6px | `--text-heading-lg` |
| display | 80px | 0.8 | -4px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 160 | 160px | `--spacing-160` |
| 180 | 180px | `--spacing-180` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| lists | 30px |
| inputs | 4px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.35) 0px 4px 16px 0px` | `--shadow-md` |
| subtle | `rgba(255, 255, 255, 0.4) 0px 0px 0px 6px` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.15) 0px 4px 6px 0px` | `--shadow-sm` |
| xl | `rgba(0, 0, 0, 0.5) 0px 6px 25px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 73px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled with Electric Blue (#5683da), text in Canvas White (#ffffff), with a 4px border-radius. Padding is 10px right/left, 0px top/bottom. Represents the primary user action on the page.

### Ghost Primary Button
**Role:** Secondary call-to-action

Transparent background with Canvas White (#ffffff) text and a Canvas White (#ffffff) 0px border. Padding is 12px top/bottom and 12px right/left. Used for less prominent but still important actions.

### Pill Button
**Role:** Tertiary action or filter tag

Filled with Cloud Burst (#d1d1d1), text in Shadow Ink (#303236), with a 9999px border-radius (pill shape). Generous horizontal padding (64px left/right), 0px vertical. Used for broad, visually distinct actions.

### Navigation Link
**Role:** Top navigation item

Transparent background button with Shadow Ink (#303236) text and border, 0px radius. Minimal padding and no distinctive background, for navigation. On hover, text becomes Canvas White (#ffffff).

### Standard Card
**Role:** Content container

Charcoal Grey (#111111) background with a 12px border-radius and no visible box shadow. Provides contained sections for content organization.

### Elevated Tooltip Card
**Role:** Interactive detail container

Appears to be a Charcoal Grey (#111111) background with a 12px border-radius, accompanied by a soft, diffused shadow `rgba(0, 0, 0, 0.35) 0px 4px 16px 0px` to suggest interactivity or temporary focus.

### Accent Bordered List Item
**Role:** Highlighted list item

Charcoal Grey (#111111) background with a 30px border-radius. Features a glowing border effect using `rgba(255, 255, 255, 0.4) 0px 0px 0px 6px` to draw attention.

## Do's and Don'ts

### Do
- Use Pitch Black (#090a0c) for primary page backgrounds and Canvas White (#ffffff) for primary text to maintain high contrast.
- Apply Electric Blue (#5683da) exclusively for primary call-to-action buttons, ensuring high visibility and consistency for interactive elements.
- Utilize Esbuild for all main headings (80px, 84px) with tight line heights (0.8, 0.9) and generous negative letter-spacing (-0.05em to -0.02em) for compact, impactful typography.
- Set all interactive buttons and tags to a 9999px border-radius for a distinct pill-like shape.
- Employ Charcoal Grey (#111111) for all card backgrounds, providing a subtle elevation from the main page body.
- Maintain an element gap of 12px for consistent vertical and horizontal spacing between discrete UI elements.
- Implement softer shadows like `rgba(0, 0, 0, 0.15) 0px 4px 6px 0px` for general elevated elements, and `rgba(0, 0, 0, 0.35) 0px 4px 16px 0px` for more pronounced interactions like tooltips or focus states.

### Don't
- Do not use saturated colors for large background areas or extensive text blocks; restrict them to accents and interactive elements.
- Avoid using default system shadows; use the defined custom shadow tokens for all elevation effects.
- Do not vary border-radius for buttons and tags outside of 9999px; this is a signature aesthetic.
- Never use line heights greater than 1.5, especially for headlines, as the typography is designed for compaction.
- Do not introduce new color gradients; adhere strictly to the defined brand and accent gradients.
- Avoid breaking the dark mode aesthetic by introducing large sections of light backgrounds unless explicitly for contrasting content. When using lighter backgrounds for sections (e.g. #f6f6f6), ensure they are still within the neutral palette.
- Do not use letter spacing >= 0; the system prefers negative tracking to keep text compact and intentional.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pitch Black Canvas | `#090a0c` | Base background for the entire application, creating a deep dark mode foundation. |
| 1 | Charcoal Grey Card | `#111111` | Primary surface for cards, content blocks, and subtle segmentation within the dark canvas. |
| 2 | Ash Cloud Overlay | `#4a4b50` | Used for interactive elements or modal backgrounds that appear on top of cards, indicating a higher interaction layer. |
| 3 | Silver Mist Panel | `#d1d1d1` | Ghost button backgrounds and elements that require a stark contrast or highlighted status within the dark UI. |

## Elevation

- **Elevated Tooltip Card:** `rgba(0, 0, 0, 0.35) 0px 4px 16px 0px`
- **Card with subtle shadow:** `rgba(0, 0, 0, 0.15) 0px 4px 6px 0px`
- **Highlighted List Item (glowing border):** `rgba(255, 255, 255, 0.4) 0px 0px 0px 6px`

## Imagery

This site features product screenshots and abstract glowing visual effects. Product screenshots are contained within dark UI elements, often with soft internal shadows, presented in a minimal, focused manner. The abstract visuals, characterized by luminous beams and soft gradients, are used decoratively, often as full-bleed background elements behind hero sections or to add ethereal depth to UI blocks, creating a futuristic and dynamic atmosphere. Icons are primarily outlined or mono-colored, designed for clarity and integration into the dark UI.

## Layout

The page primarily uses a max-width contained layout of 1280px, with content centered. The hero section is full-bleed, a deep dark background with a striking central glowing abstract graphic. Subsequent sections alternate between dark backgrounds with product UI examples and lighter, almost white, background sections for informational content. Content frequently uses a two-column text-left/image-right or centered stacked sections. Spacing between sections is generous (73px). Navigation is a sticky top bar with minimal styling and calls to action.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #090a0c
border: #303236
accent: #ff8964
primary action: #5683da (filled action)

Example Component Prompts:
1. Create a primary action button: Electric Blue (#5683da) background, Canvas White (#ffffff) text, 4px border-radius, 0px vertical padding, 10px horizontal padding.
2. Create a standard card: Charcoal Grey (#111111) background, 12px border-radius, no shadow, with Shadow Ink (#303236) as an internal divider.
3. Create a navigation link: Transparent background, Shadow Ink (#303236) text (Inter, weight 500, size 16px), 0px radius, 12px vertical/horizontal padding. On hover, change text color to Canvas White (#ffffff).
4. Create a hero headline: Text 'Everything App for your teams' (Esbuild, weight 600, size 80px), Canvas White (#ffffff) color, line height 0.8, letter-spacing -4px.
5. Create a secondary text block: Text 'Huly, an open-source platform...' (Inter, weight 400, size 18px), Battleship Grey (#95979e) color, line height 1.5, letter-spacing -0.15em.

## Similar Brands

- **Linear** — Dark mode UI with similar treatment of product screenshots, crisp typography, and a single vibrant accent color for interaction.
- **Raycast** — Emphasis on dark, minimalist interfaces and subtle glowing effects, paired with functional, compact text.
- **Superhuman** — Focus on high-contrast dark environments and precise typography with controlled letter-spacing for a 'fast' feel.
- **Vercel** — Modern dark aesthetic prominently featuring code snippets and subtle glowing effects in hero sections, paired with clean sans-serif typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #090a0c;
  --color-charcoal-grey: #111111;
  --color-shadow-ink: #303236;
  --color-ash-cloud: #4a4b50;
  --color-storm-grey: #61656b;
  --color-battleship-grey: #95979e;
  --color-silver-mist: #a9a9aa;
  --color-cloud-burst: #d1d1d1;
  --color-canvas-white: #ffffff;
  --color-electric-blue: #5683da;
  --color-sunset-orange: #ff8964;
  --color-warm-ivory-gradient: #f6f6f6;
  --gradient-warm-ivory-gradient: linear-gradient(103.7deg, rgba(188, 155, 143, 0.1) 38.66%, rgba(233, 132, 99, 0.1) 68.55%, rgb(233, 132, 99) 85.01%, rgb(255, 255, 255) 92.12%);
  --color-peach-bloom-gradient: #ffebaa;
  --gradient-peach-bloom-gradient: linear-gradient(90deg, rgb(255, 235, 164) 50%, rgba(0, 0, 0, 0) 50%);

  /* Typography — Font Families */
  --font-esbuild: 'Esbuild', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.4px;
  --text-body-lg: 14px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.56px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.44px;
  --text-heading: 28px;
  --leading-heading: 1;
  --tracking-heading: -1.4px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.6px;
  --text-display: 80px;
  --leading-display: 0.8;
  --tracking-display: -4px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-160: 160px;
  --spacing-180: 180px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 73px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-lists: 30px;
  --radius-inputs: 4px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.35) 0px 4px 16px 0px;
  --shadow-subtle: rgba(255, 255, 255, 0.4) 0px 0px 0px 6px;
  --shadow-sm: rgba(0, 0, 0, 0.15) 0px 4px 6px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 6px 25px 0px;

  /* Surfaces */
  --surface-pitch-black-canvas: #090a0c;
  --surface-charcoal-grey-card: #111111;
  --surface-ash-cloud-overlay: #4a4b50;
  --surface-silver-mist-panel: #d1d1d1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #090a0c;
  --color-charcoal-grey: #111111;
  --color-shadow-ink: #303236;
  --color-ash-cloud: #4a4b50;
  --color-storm-grey: #61656b;
  --color-battleship-grey: #95979e;
  --color-silver-mist: #a9a9aa;
  --color-cloud-burst: #d1d1d1;
  --color-canvas-white: #ffffff;
  --color-electric-blue: #5683da;
  --color-sunset-orange: #ff8964;
  --color-warm-ivory-gradient: #f6f6f6;
  --color-peach-bloom-gradient: #ffebaa;

  /* Typography */
  --font-esbuild: 'Esbuild', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.4px;
  --text-body-lg: 14px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.56px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.44px;
  --text-heading: 28px;
  --leading-heading: 1;
  --tracking-heading: -1.4px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.6px;
  --text-display: 80px;
  --leading-display: 0.8;
  --tracking-display: -4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-160: 160px;
  --spacing-180: 180px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.35) 0px 4px 16px 0px;
  --shadow-subtle: rgba(255, 255, 255, 0.4) 0px 0px 0px 6px;
  --shadow-sm: rgba(0, 0, 0, 0.15) 0px 4px 6px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 6px 25px 0px;
}
```
