# Portrait — Style Reference
> Generative digital canvas

**Theme:** light

Portrait evokes a generative canvas feel with a bright, spacious theme featuring softly textured cards and borders. A vibrant, multi-hued color spectrum appears as a playful accent, punctuating an otherwise clean, achromatic UI. Typography is confident and dense, using precise tracking to maintain presence. Elements avoid hard edges, preferring generous radii and subtle, layered shadows that lend depth without heaviness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces, primary card backgrounds, interactive element fills |
| Ink Black | `#353535` | `--color-ink-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Charcoal | `#000000` | `--color-charcoal` | Deepest text or icon fills, subtle shadow effects – reserved for maximum contrast or depth |
| Cloud Gray | `#eeeeee` | `--color-cloud-gray` | Subtle borders, secondary card backgrounds, separator lines – creating division without harshness |
| Stone Gray | `#797979` | `--color-stone-gray` | Muted secondary text, ghost button borders, subtle icon strokes – for hierarchy and de-emphasis |
| Pale Blue Mist | `#e8f1ff` | `--color-pale-blue-mist` | Soft accent background for prominent cards or sections, adding a hint of color to large surfaces |
| Ocean Blue | `#08304c` | `--color-ocean-blue` | Prominent heading text, functional iconography, active states, and borders for ghost buttons – a deep, authoritative brand accent |
| Sky Blue | `#084e72` | `--color-sky-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Rainbow Glow | `linear-gradient(90deg, rgb(38, 192, 255), rgb(230, 0, 194) 20%, rgb(255, 73, 78) 40%, rgb(255, 161, 62) 60%, rgb(255, 200, 55) 80%, rgb(0, 204, 61))` | `--color-rainbow-glow` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Success Green | `#00cc3d` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Interactive Violet | `#8e51ff` | `--color-interactive-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### Switzer — Primary UI text for body, captions, navigation, and detailed information. Its default weight of 400 offers clear readability, while varied line heights are used to fine-tune density across different content blocks. · `--font-switzer`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 540, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 16px, 18px, 20px, 24px, 36px
- **Line height:** 1.00, 1.11, 1.38, 1.43, 1.45, 1.50
- **Letter spacing:** 0.025em for small text, 0.14em for decorative caps
- **OpenType features:** `"liga" 0`
- **Role:** Primary UI text for body, captions, navigation, and detailed information. Its default weight of 400 offers clear readability, while varied line heights are used to fine-tune density across different content blocks.

### Basier Circle — Used for headlines and prominent calls to action. Its distinct, tightly tracked letter spacing creates a strong, compact visual presence, especially at larger sizes, preventing headlines from feeling sparse. · `--font-basier-circle`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500, 600
- **Sizes:** 16px, 18px, 20px, 31px, 39px, 44px, 49px, 76px
- **Line height:** 1.00, 1.04, 1.08, 1.10, 1.20, 1.50
- **Letter spacing:** -0.056em at 76px, -0.050em at 49px, -0.013em at 16px
- **Role:** Used for headlines and prominent calls to action. Its distinct, tightly tracked letter spacing creates a strong, compact visual presence, especially at larger sizes, preventing headlines from feeling sparse.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.45 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| subheading | 18px | 1.45 | -0.23px | `--text-subheading` |
| heading-sm | 24px | 1.38 | — | `--text-heading-sm` |
| heading | 39px | 1.08 | -1.25px | `--text-heading` |
| heading-lg | 49px | 1.08 | -1.48px | `--text-heading-lg` |
| display | 76px | 1.04 | -4.26px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 28px |
| containers | 16px |
| formInputs | 8px |
| microElements | 12px |
| imageContainers | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.0...` | `--shadow-md` |
| subtle | `oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) ...` | `--shadow-subtle` |
| subtle-2 | `oklab(0 0 0 / 0.04) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) ...` | `--shadow-subtle-2` |
| subtle-3 | `oklab(0 0 0 / 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.07) ...` | `--shadow-subtle-3` |
| subtle-4 | `oklab(0 0 0 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 1...` | `--shadow-subtle-4` |
| subtle-5 | `oklab(0 0 0 / 0.1) 0px 0px 0px 1px` | `--shadow-subtle-5` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Button
**Role:** Secondary action control

Text-only button with transparent background, Ink Black text, and a 28px border-radius. Primarily used for less emphasized actions or navigation items. Example: 'Login'.

### Outlined Button
**Role:** Primary action button

Button with a 28px border-radius, Ink Black text, a 1px Ink Black border, and a transparent background. Indicates a primary action without the visual dominance of a filled button. Example: 'Sign up'.

### Rainbow Input Field
**Role:** Interactive text input

Text input field with a 28px border-radius and a dynamic 'Rainbow Glow' linear-gradient border on hover/focus. Uses Ink Black text and a Canvas White background.

### Basic Card
**Role:** Content container

White card with 24px border-radius and 16px internal padding. Uses no border and a subtle layer of multi-directional shadow for elevation. Contains various content such as images, text, or interactive elements.

### Elevated Tooltip Card
**Role:** Informational overlay

Card leveraging Pale Blue Mist background, a 26px border-radius, and 6px internal padding. Features a soft, deep shadow stack that provides significant elevation off the primary surface.

### Image Gallery Item
**Role:** Visual content display

Decorative card with a 24px border-radius, 10px internal padding, and a Canvas White background. Often contains an image with complementary corner radius.

### Notification Tag
**Role:** Ephemeral status indicator

Small tag with a 28px border-radius, Pale Blue Mist background, and Sky Blue text. Used for 'New' or similar status labels, typically within navigation or banners. 6px padding.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all main backgrounds and elevated surfaces, ensuring a bright, expansive feel.
- Use Ink Black (#353535) for primary headings and body text, maintaining high contrast for readability.
- Apply a 24px border-radius to all major content cards and images to ensure a consistent soft, rounded aesthetic.
- Incorporate the 'Rainbow Glow' gradient on interactive elements or borders to introduce branded playfulness and visual pop.
- Use Basier Circle for headlines with precise, tight letter-spacing (-0.056em at 76px) to create a compact, confident visual presence.
- Apply layered, subtle shadow stacks to cards and navigation elements for depth, avoiding stark or heavy elevation.
- Maintain a clear visual hierarchy by using Ocean Blue (#08304c) for critical functional icons and active states, drawing attention without being overtly strong.

### Don't
- Avoid using hard, sharp corners; always apply border-radii of 8px or higher to all UI elements.
- Do not introduce strong, solid background colors that conflict with the Canvas White theme, except for accent components.
- Avoid overly dense text blocks; use Switzer with generous line heights and element gaps to ensure comfortable readability.
- Do not use generic system shadows; leverage the multi-directional, low-opacity shadow stacks for consistent brand elevation.
- Refrain from using saturated colors for large paragraph text or backgrounds where they might compete with the vibrant accent colors.
- Do not use letter-spacing values less than -0.013em for body text; tight tracking is reserved for display typography only.
- Avoid placing text directly on top of the 'Rainbow Glow' gradient; reserve the gradient for borders or decorative fills.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and base layer for all content. |
| 2 | Cloud Gray | `#eeeeee` | Secondary background color for subtle section breaks or less prominent cards. |
| 3 | Pale Blue Mist | `#e8f1ff` | Elevated background for focal cards or informative sections, adding a soft chromatic highlight. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px`
- **Hovered Card / Active Navigation:** `oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px`
- **Tooltip / Layered Element:** `oklab(0 0 0 / 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.07) 0px 20px 20px -10px, rgba(0, 0, 0, 0.04) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px`

## Imagery

Imagery on Portrait is primarily photographic, featuring warm, high-key lifestyle shots often presented within contained, rounded-corner cards. Product screenshots are clean and direct, focused on displaying the UI without additional context. Decorative illustrations are used minimally, often as small, colorful accents to complement the vibrant gradients. Icons are generally outlined, matching the lightness of the UI, with strokes in Ocean Blue or Ink Black.

## Layout

The page primarily uses a max-width contained layout, centered at around 1200px. The hero section is full-bleed with a luminous, gradient background and centered headline. Content sections follow a rhythm of spacious vertical separation (48px section gap). Content is arranged in alternating text-left/image-right patterns and multi-column card grids, emphasizing visual balance and comfortable readability. Navigation is a sticky top bar with minimal elements.

## Agent Prompt Guide

Quick Color Reference: 
text: #353535
background: #ffffff
border: #eeeeee
accent: #08304c
primary action: #08304c (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #08304c border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Design a Feature Card: A Basic Card (#ffffff background, 24px radius, layered shadows) containing an image with a 24px radius, 10px padding, and 'Featured Story' as the headline (Basier Circle, weight 500, size 24px, color #353535). Add a 'Read More' link (Switzer, weight 400, size 14px, color #08304c).
3. Create an Outlined 'Sign Up' Button: Use an Outlined Button component with Ink Black text (#353535) and a 1px solid Ink Black border. It should have a 28px border-radius and 12px horizontal padding. Include the text 'Sign up'.
4. Develop a Notification Tag: A small tag using Pale Blue Mist (#e8f1ff) background, 28px border-radius, and text 'New' in Sky Blue (#084e72). Apply 6px padding symmetrically.

## Similar Brands

- **Framer** — Bright, spacious canvas-like interface with strong typography and rounded components, using gradients for accent.
- **Linear** — Focus on subtle elevation through shadows and generous border radii, paired with a clean, light aesthetic.
- **Superhuman** — Precise, tightly tracked typography and a minimalist UI, with color used as functional accents in a mostly achromatic system.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #353535;
  --color-charcoal: #000000;
  --color-cloud-gray: #eeeeee;
  --color-stone-gray: #797979;
  --color-pale-blue-mist: #e8f1ff;
  --color-ocean-blue: #08304c;
  --color-sky-blue: #084e72;
  --color-rainbow-glow: #26c0ff;
  --gradient-rainbow-glow: linear-gradient(90deg, rgb(38, 192, 255), rgb(230, 0, 194) 20%, rgb(255, 73, 78) 40%, rgb(255, 161, 62) 60%, rgb(255, 200, 55) 80%, rgb(0, 204, 61));
  --color-success-green: #00cc3d;
  --color-interactive-violet: #8e51ff;

  /* Typography — Font Families */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier-circle: 'Basier Circle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: -0.23px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.38;
  --text-heading: 39px;
  --leading-heading: 1.08;
  --tracking-heading: -1.25px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -1.48px;
  --text-display: 76px;
  --leading-display: 1.04;
  --tracking-display: -4.26px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w540: 540;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 28px;
  --radius-containers: 16px;
  --radius-forminputs: 8px;
  --radius-microelements: 12px;
  --radius-imagecontainers: 24px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle: oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-2: oklab(0 0 0 / 0.04) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-3: oklab(0 0 0 / 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.07) 0px 20px 20px -10px, rgba(0, 0, 0, 0.04) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-4: oklab(0 0 0 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 10px 16px 14px 0px;
  --shadow-subtle-5: oklab(0 0 0 / 0.1) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #eeeeee;
  --surface-pale-blue-mist: #e8f1ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #353535;
  --color-charcoal: #000000;
  --color-cloud-gray: #eeeeee;
  --color-stone-gray: #797979;
  --color-pale-blue-mist: #e8f1ff;
  --color-ocean-blue: #08304c;
  --color-sky-blue: #084e72;
  --color-rainbow-glow: #26c0ff;
  --color-success-green: #00cc3d;
  --color-interactive-violet: #8e51ff;

  /* Typography */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier-circle: 'Basier Circle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: -0.23px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.38;
  --text-heading: 39px;
  --leading-heading: 1.08;
  --tracking-heading: -1.25px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -1.48px;
  --text-display: 76px;
  --leading-display: 1.04;
  --tracking-display: -4.26px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle: oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-2: oklab(0 0 0 / 0.04) 0px 0px 0px 1px, rgba(0, 0, 0, 0.03) 0px 16px 16px -8px, rgba(0, 0, 0, 0.03) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-3: oklab(0 0 0 / 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.07) 0px 20px 20px -10px, rgba(0, 0, 0, 0.04) 0px 10px 10px -5px, rgba(0, 0, 0, 0.03) 0px 5px 5px -2.5px, rgba(0, 0, 0, 0.03) 0px 3px 3px -1.5px, rgba(0, 0, 0, 0.03) 0px 2px 2px -1px, rgba(0, 0, 0, 0.03) 0px 1px 1px -0.5px;
  --shadow-subtle-4: oklab(0 0 0 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 10px 16px 14px 0px;
  --shadow-subtle-5: oklab(0 0 0 / 0.1) 0px 0px 0px 1px;
}
```
