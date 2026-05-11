# until — Style Reference
> Warm parchment, dark charcoal type

**Theme:** light

Until presents a calm, sophisticated aesthetic, combining a nearly monochromatic UI with thoughtful typographic play and tactile surface treatments. The primary canvas is a warm, off-white, contrasted with deep charcoal text and accents. Subtle shadows and rounded corner cards provide gentle dimensionality, making the interface feel grounded and inviting. A single olive green brand accent adds a touch of organic warmth, used sparingly to highlight key information and interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment | `#f7f3ec` | `--color-parchment` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Charcoal | `#121212` | `--color-charcoal` | Primary text, borders, dark card backgrounds |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Footer text, strong accents for outlines, primary text on white |
| Snow | `#ffffff` | `--color-snow` | Button backgrounds, elevated surfaces |
| Soft Stone | `#bebebe` | `--color-soft-stone` | Muted helper text, delicate dividers, inactive states |
| Olive Grove | `#6c853b` | `--color-olive-grove` | Brand accent, highlighted text, subtle background fills for emphasis |
| Sunset Fade | `linear-gradient(90deg, rgb(203, 53, 15) 0%, rgb(244, 224, 153) 50%, rgb(171, 193, 227) 100%)` | `--color-sunset-fade` | Decorative hero background gradient |

## Tokens — Typography

### neueHaasText — Body text, navigation, buttons, captions. Behaves as a highly legible Swiss grotesque, grounding the system with clarity. · `--font-neuehaastext`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.43, 1.50
- **Letter spacing:** -0.009, 0.01
- **Role:** Body text, navigation, buttons, captions. Behaves as a highly legible Swiss grotesque, grounding the system with clarity.

### neueHaasDisplay — Headlines and prominent text. Noticeably tight letter-spacing at larger sizes (-0.037em at 69px) creates a sophisticated, almost artistic visual density, preventing sprawl. · `--font-neuehaasdisplay`
- **Substitute:** Graphik
- **Weights:** 400, 500
- **Sizes:** 16px, 24px, 32px, 39px, 56px, 69px
- **Line height:** 0.90, 0.95, 1.00, 1.10, 1.50
- **Letter spacing:** -0.01, -0.02, -0.021, -0.024, -0.025, -0.037
- **Role:** Headlines and prominent text. Noticeably tight letter-spacing at larger sizes (-0.037em at 69px) creates a sophisticated, almost artistic visual density, preventing sprawl.

### Geist Mono — Small functional text, code snippets, metadata. Its monospaced nature offers a technical counterpoint to the sans-serifs, particularly with its slightly positive letter-spacing (`0.05em` at 12px) to enhance legibility at small sizes. · `--font-geist-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 400, 500
- **Sizes:** 12px, 14px
- **Line height:** 1.00, 1.40, 1.50
- **Letter spacing:** -0.0250em, 0.0500em
- **Role:** Small functional text, code snippets, metadata. Its monospaced nature offers a technical counterpoint to the sans-serifs, particularly with its slightly positive letter-spacing (`0.05em` at 12px) to enhance legibility at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.009px | `--text-body-sm` |
| body | 16px | 1.5 | 0.01px | `--text-body` |
| subheading | 24px | 1 | -0.02px | `--text-subheading` |
| heading-sm | 32px | 0.95 | -0.021px | `--text-heading-sm` |
| heading | 39px | 0.95 | -0.024px | `--text-heading` |
| heading-lg | 56px | 0.9 | -0.025px | `--text-heading-lg` |
| display | 69px | 0.9 | -0.037px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 50px |
| cards | 32px |
| input | 6px |
| images | 24px |
| buttons | 64px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255...` | `--shadow-subtle` |
| xl | `rgba(0, 0, 0, 0.043) 0px 7.5px 30px 0px, rgba(255, 255, 2...` | `--shadow-xl` |

### Layout

- **Page max-width:** 1283px
- **Section gap:** 96px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Ghost Header Button
**Role:** Navigation button in the header, visually transparent until hover.

Background: rgba(0, 0, 0, 0) (transparent), text color: #f7f3ec (Parchment), border: none. On hover, a subtle interaction would likely appear, though not explicitly defined here.

### Primary Filled Button
**Role:** Key action buttons, such as 'Join Us' or 'Join the team'.

Background: #121212 (Charcoal), text color: #ffffff (Snow), border-radius: 64px. Padding is implied by content, but the radius suggests a pill-like structure for all buttons.

### Secondary Filled Button
**Role:** Less prominent actions, often alongside a primary button.

Background: #ffffff (Snow), text color: #121212 (Charcoal), border-radius: 64px.

### Information Card
**Role:** Content containers for text and images, often used in grids.

Background: #f7f3ec (Parchment), border-radius: 32px. Features a subtle, sophisticated inner and outer shadow: `rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px`.

### Header Navigation
**Role:** Top-level navigation element for page sections.

Ghostly, semi-transparent navigation bar with `backdrop-filter: blur(25.5px) brightness(1.04) contrast(1.075)`. Text is #f7f3ec (Parchment) against the hero image, switching to #121212 (Charcoal) or #f7f3ec depending on section background.

## Do's and Don'ts

### Do
- Prioritize Neue Haas Display for all headings and large text, ensuring letter-spacing is applied for aesthetic cohesion.
- Use Parchment (#f7f3ec) as the default background color for main content sections and Snow (#ffffff) for card backgrounds to establish clear visual hierarchy.
- Apply Charcoal (#121212) or Midnight Ink (#000000) for all primary text elements to maintain contrast and legibility.
- Utilize Olive Grove (#6c853b) exclusively for subtle accentuation of key information, links, or decorative elements, never for large areas or primary actions.
- Implement `border-radius: 64px` for all buttons, creating a consistent pill shape for interactive elements.
- Apply `border-radius: 32px` with the subtle shadow `rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px` for all cards to provide gentle depth.
- Maintain a base unit of 8px for spacing, with a consistent `96px` section gap to create clear vertical rhythm.

### Don't
- Do not use highly saturated or vivid colors that are not Olive Grove (#6c853b), as the system relies on a near-monochromatic palette.
- Avoid sharp corners; all functional UI elements should have a defined border-radius, typically 24px, 32px, or 64px.
- Do not introduce heavy, opaque shadows; leverage the subtle card shadow or the contained, softer shadows for depth.
- Do not use generic system fonts; Neue Haas Text and Display are critical for brand identity.
- Avoid breaking component padding suggestions; maintain a `32px` padding around card content.
- Do not use large blocks of bright, solid color for backgrounds; favor the neutral Parchment or Snow, or image backgrounds with subtle filtering.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Parchment | `#f7f3ec` | Base page background, light sections |
| 2 | Snow | `#ffffff` | Elevated card backgrounds, interactive elements |

## Elevation

- **Information Card:** `rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px`
- **Image with elevation:** `rgba(0, 0, 0, 0.043) 0px 7.5px 30px 0px, rgba(255, 255, 255, 0.3) 0px 1px 1px 0px inset`

## Imagery

The site uses high-quality, realistic photography as its primary imagery. These images are often full-bleed or large backgrounds, at times processed with a subtle painterly or grainy filter, suggesting a blend of scientific precision and artistic interpretation. Product photography, when present, focuses on lab environments and people interacting with technology. Iconography is minimal and functional, typically filled and monochromatic charcoal, integrated seamlessly into the text flow. Imagery primarily serves to set an atmosphere and provide context, rather than being purely decorative.

## Layout

The page primarily uses a max-width contained layout of 1283px, centered within the viewport. The hero section is full-bleed, featuring a large background image with centered, large-scale text and a semi-transparent, blur-effect sticky header. Content sections follow a consistent vertical rhythm with 96px section gaps, often employing a dual-column layout alternating text and visuals, or a grid of cards (likely 4-columns based on screenshots). The density is balanced, with ample whitespace providing breathing room around content blocks.

## Agent Prompt Guide

Quick Color Reference: 
- text: #121212
- background: #f7f3ec
- border: #121212
- accent: #6c853b
- primary action: no distinct CTA color

Example Component Prompts:
- Create a Hero Section: full-bleed background, with a semi-transparent floating header featuring 'Join Us' button at text size 16px, weight 400 from neueHaasText, color #121212, and background #ffffff with 64px radius. The main headline appears centered at 69px 'neueHaasDisplay' weight 500, color #f7f3ec, letter-spacing -0.037em.
- Create an Information Card: background #f7f3ec, border-radius 32px, with shadow `rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px`. Inside, a heading at 32px 'neueHaasDisplay' weight 500, color #121212, letter-spacing -0.021em, and body text at 16px 'neueHaasText' weight 400, color #121212.

## Similar Brands

- **Axiom Space** — Scientific theme, clean sans-serif typography, and a subdued color palette with minimal accentuation.
- **Neuralink** — High-tech/scientific product focus, emphasis on refined typography, and a calm, deliberate visual presence.
- **Eight Sleep** — Focus on cutting-edge technology, sophisticated and balanced layouts, and a neutral color scheme with a subtle accent color.
- **Perception Kayaks** — Emphasis on natural elements (green accent, image treatment), modern aesthetic, and uncluttered presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment: #f7f3ec;
  --color-charcoal: #121212;
  --color-midnight-ink: #000000;
  --color-snow: #ffffff;
  --color-soft-stone: #bebebe;
  --color-olive-grove: #6c853b;
  --color-sunset-fade: #c6350f;
  --gradient-sunset-fade: linear-gradient(90deg, rgb(203, 53, 15) 0%, rgb(244, 224, 153) 50%, rgb(171, 193, 227) 100%);

  /* Typography — Font Families */
  --font-neuehaastext: 'neueHaasText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehaasdisplay: 'neueHaasDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.009px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 0.95;
  --tracking-heading-sm: -0.021px;
  --text-heading: 39px;
  --leading-heading: 0.95;
  --tracking-heading: -0.024px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.025px;
  --text-display: 69px;
  --leading-display: 0.9;
  --tracking-display: -0.037px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1283px;
  --section-gap: 96px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 64px;

  /* Named Radii */
  --radius-pill: 50px;
  --radius-cards: 32px;
  --radius-input: 6px;
  --radius-images: 24px;
  --radius-buttons: 64px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.043) 0px 7.5px 30px 0px, rgba(255, 255, 255, 0.3) 0px 1px 1px 0px inset;

  /* Surfaces */
  --surface-parchment: #f7f3ec;
  --surface-snow: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment: #f7f3ec;
  --color-charcoal: #121212;
  --color-midnight-ink: #000000;
  --color-snow: #ffffff;
  --color-soft-stone: #bebebe;
  --color-olive-grove: #6c853b;
  --color-sunset-fade: #c6350f;

  /* Typography */
  --font-neuehaastext: 'neueHaasText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehaasdisplay: 'neueHaasDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.009px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 0.95;
  --tracking-heading-sm: -0.021px;
  --text-heading: 39px;
  --leading-heading: 0.95;
  --tracking-heading: -0.024px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.025px;
  --text-display: 69px;
  --leading-display: 0.9;
  --tracking-display: -0.037px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 64px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px -1px 2px 0px inset, rgba(255, 255, 255, 0.1) 0px 1px 2px 0px inset, rgba(0, 0, 0, 0.1) 0px 0px 2px 0px, rgba(0, 0, 0, 0.05) 0px 3px 17px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.043) 0px 7.5px 30px 0px, rgba(255, 255, 255, 0.3) 0px 1px 1px 0px inset;
}
```
