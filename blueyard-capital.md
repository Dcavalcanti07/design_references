# BlueYard Capital — Style Reference
> Soft-focus intellectual ether.

**Theme:** light

BlueYard employs a subdued, almost ethereal visual language, combining soft, desaturated background gradients with sharp, low-contrast text. This creates a contemplative distance, positioning content as abstract concepts rather than immediate tasks. The color palette is driven by nuanced, muted accents primarily used for content categorization, lending a subtle, academic feeling to information blocks. Typography is spare and precise, reinforcing an impression of rigor and thoughtfulness, rather than bold proclamations.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#090b11` | `--color-ink` | Primary text, core iconography, subdued borders for cards and navigation elements. Its near-black depth offers contrast without harshness against softer backgrounds |
| Graphite | `#3a3a3e` | `--color-graphite` | Secondary text, subtle borders, and placeholder content. This deeper gray provides necessary hierarchy without overpowering the primary text |
| Canvas White | `#ffffff` | `--color-canvas-white` | Background for primary content areas, cards, and interactive elements. Its purity serves as a foundation for other delicate hues |
| Pale Mist | `#b5b0b0` | `--color-pale-mist` | Subtle background for secondary sections and borders, offering a slight visual break from pure white surfaces |
| Sunken Gold | `#ffcf9e` | `--color-sunken-gold` | Accent for themed content cards, signaling a specific category. Its warm, muted quality integrates rather than shouts |
| Cloud Indigo | `#babfff` | `--color-cloud-indigo` | Accent for themed content cards, providing a cool, understated categorization |
| Amethyst Haze | `#e3a2ef` | `--color-amethyst-haze` | Accent for themed content cards, a vivid yet soft indicator for categorization |
| Sky Veil | `#bfe0f7` | `--color-sky-veil` | Accent for themed content cards, a cool, barely-there tint for specific categories |
| Ocean Whisper | `#8ceae4` | `--color-ocean-whisper` | Accent for themed content cards, hinting at a category with a cool, subtle hue |

## Tokens — Typography

### Instrument Sans — The sole typeface, used across all elements from headings to body text. Its clean, geometric sans-serif subtly counters the organic page gradients, providing a grounded clarity. The variable letter-spacing for larger sizes enhances its precise character. · `--font-instrument-sans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 24px, 48px, 54px
- **Line height:** 1.00, 1.20, 1.50
- **Letter spacing:** -1.44, -1.62, -0.72, -0.36
- **Role:** The sole typeface, used across all elements from headings to body text. Its clean, geometric sans-serif subtly counters the organic page gradients, providing a grounded clarity. The variable letter-spacing for larger sizes enhances its precise character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.36px | `--text-caption` |
| body | 24px | 1.5 | -0.72px | `--text-body` |
| heading | 48px | 1.2 | -1.44px | `--text-heading` |
| display | 54px | 1 | -1.62px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 60 | 60px | `--spacing-60` |
| 90 | 90px | `--spacing-90` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 0px |
| cards | 0px |
| images | 0px |
| inputs | 0px |
| buttons | 0px |

### Layout

- **Section gap:** 60px
- **Card padding:** 12px
- **Element gap:** 5px

## Components

### Primary Navigation Button
**Role:** The main menu toggle.

Minimal square button with an icon, `backgroundColor: #ffffff`, `color: #090b11`, and `border-radius: 0px`.

### Text Only Button (Ghost)
**Role:** Used for secondary actions or navigation links with minimal visual weight.

Transparent background, `#090b11` text color with `opacity: 0.8`. `border-radius: 0px`.

### Content Card - Default
**Role:** A neutral container for various content blocks.

`background: transparent`, `border-radius: 0px`, no shadow. Used for subtle content grouping and layout.

### Content Card - Canvas
**Role:** A base card for information presentation.

`background: #ffffff`, `border-radius: 0px`, no shadow, `padding: 0px`.

### Category Tag - Sunken Gold
**Role:** Categorization tag for content blocks.

`background: #ffcf9e`, text `color: #090b11`, `padding: 8px 12px`, `border-radius: 0px`.

### Category Tag - Amethyst Haze
**Role:** Categorization tag for content blocks.

`background: #e3a2ef`, text `color: #090b11`, `padding: 8px 12px`, `border-radius: 0px`.

## Do's and Don'ts

### Do
- Maintain zero border-radius for all interface elements and content cards to reinforce the crisp, structured appearance.
- Utilize Instrument Sans exclusively across all text elements, varying size and weight as defined in the typography section, to uphold typographic consistency.
- Employ the muted accent colors (#ffcf9, #babfff, #e3a2ef, #bfe0f7, #8ceae4) only for thematic content categorization, such as card backgrounds, avoiding their use for primary active states or calls to action.
- Prioritize transparent or white backgrounds for card elements, with `12px` padding where applicable, to maintain a light, airy feel.
- Ensure all primary headings use Instrument Sans at `48px` or `54px` with negative letter-spacing (`-1.44px` or `-1.62px`) for a precise, refined look.
- Structure page sections with a `60px` vertical gap, opting for seamless transitions or subtle background shifts instead of heavy dividers.
- Apply `:last-child { margin-bottom: 0 }` to avoid excessive trailing space within content blocks and carousels, promoting a tidy finish.

### Don't
- Do not introduce rounded corners; all elements must maintain `0px` border-radius.
- Avoid bold or highly saturated colors for calls to action or primary interactive states; maintain a neutral or ghost aesthetic for interactive elements.
- Refrain from using drop shadows or heavy elevation styles; surfaces should remain flat or rely on subtle background gradients for depth.
- Do not deviate from the Instrument Sans typeface or introduce additional font families.
- Do not use explicit borders on cards or primary content blocks unless it's a specific categorical indicator with a muted accent color.
- Avoid large, impactful hero images; prioritize abstract gradients or large typography in hero sections.
- Do not use letter-spacing: normal for headlines or display text; actively use negative letter-spacing for larger type sizes.

## Imagery

Imagery is minimal and abstract, dominated by sophisticated 3D renders of spherical, ethereal objects with subtle glittering textures set against soft, gradient backgrounds. Photography is absent. Icons are typically simple, monochromatic, and have a thin stroke weight. The primary role of visuals is decorative atmosphere and conceptual framing rather than direct explanation or product demonstration. The density is image-light, with visual elements serving as large, soft focal points rather than numerous small details.

## Layout

The page primarily uses a full-bleed layout, stretching content edges to the viewport, particularly for the hero and section backgrounds. Content within these full-bleed sections is centrally aligned, featuring a large, centered headline over an abstract visual. Sections have a consistent vertical rhythm established by `60px` gaps. Content arrangements often involve a centered stack of information, with implicit grids for feature or portfolio items. Navigation is a minimal top-right hamburger icon, suggesting content focus over complex site structure.

## Agent Prompt Guide

Quick Color Reference: text: #090b11, background: #ffffff, border: #3a3a3e (for subdued elements), accent: #ffcf9e, primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Section: Full-bleed soft gradient background from top-left #ffcf9e to bottom-right #babfff. Center a headline 'Will it be Utopia, or Oblivion?' using Instrument Sans, `size: 54px`, `weight: 500`, `color: #090b11`, `letter-spacing: -1.62px`.
2. Design a Category Card: `background: #e3a2ef`, `padding: 8px 12px`, `border-radius: 0px`. Inside, display a text label 'Biology & Chemistry' in Instrument Sans, `size: 12px`, `weight: 400`, `color: #090b11`.
3. Implement a Ghost Navigation Link: Text 'Back to home page' in Instrument Sans, `size: 24px`, `weight: 400`, `color: rgba(9, 11, 17, 0.8)`. No background or border, `border-radius: 0px`.

## Similar Brands

- **OpenAI** — Similar use of abstract, ethereal backgrounds and minimalist UI to convey advanced concepts.
- **Stripe** — Clean typography, subtle use of colors for content differentiation, and an emphasis on clear information hierarchy.
- **Arc Browser** — Distinctive use of gradients and muted color palettes for atmosphere rather than functional emphasis.
- **OtherSide** — Abstract 3D-rendered imagery and a sophisticated, atmospheric visual presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #090b11;
  --color-graphite: #3a3a3e;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #b5b0b0;
  --color-sunken-gold: #ffcf9e;
  --color-cloud-indigo: #babfff;
  --color-amethyst-haze: #e3a2ef;
  --color-sky-veil: #bfe0f7;
  --color-ocean-whisper: #8ceae4;

  /* Typography — Font Families */
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-body: 24px;
  --leading-body: 1.5;
  --tracking-body: -0.72px;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -1.44px;
  --text-display: 54px;
  --leading-display: 1;
  --tracking-display: -1.62px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-60: 60px;
  --spacing-90: 90px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 12px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-tags: 0px;
  --radius-cards: 0px;
  --radius-images: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #090b11;
  --color-graphite: #3a3a3e;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #b5b0b0;
  --color-sunken-gold: #ffcf9e;
  --color-cloud-indigo: #babfff;
  --color-amethyst-haze: #e3a2ef;
  --color-sky-veil: #bfe0f7;
  --color-ocean-whisper: #8ceae4;

  /* Typography */
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-body: 24px;
  --leading-body: 1.5;
  --tracking-body: -0.72px;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -1.44px;
  --text-display: 54px;
  --leading-display: 1;
  --tracking-display: -1.62px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-60: 60px;
  --spacing-90: 90px;

  /* Border Radius */
  --radius-lg: 10px;
}
```
