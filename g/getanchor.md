# Getanchor — Style Reference
> Warm Professional Canvas

**Theme:** light

Anchor's design system evokes a sense of understated authority. It centers on a stark achromatic palette for structure and text, punctuated by a single warm orange for primary calls to action. Clear spacing and a highly legible sans-serif typeface create a professional yet approachable feel, while subtle elevation and rounded corners soften the technical edge. The overall impression is one of efficiency and directness, with visual weight reserved for crucial interactions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Anchor Ink | `#1e1e1e` | `--color-anchor-ink` | Primary text, structural borders, dark surface accents, footer background |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, elevated card backgrounds, active navigation elements |
| Pale Stone | `#f5f2f0` | `--color-pale-stone` | Secondary surface backgrounds, subtle content segmentation |
| Off-White | `#f0e9e5` | `--color-off-white` | Subtle light surface, muted text, ghost button backgrounds |
| Dusty Rose | `#e3d7cd` | `--color-dusty-rose` | Section background, a warm light base for content blocks |
| Charcoal | `#292929` | `--color-charcoal` | Subtle dark background variant for specific sections |
| Cadet Grey | `#767676` | `--color-cadet-grey` | Muted secondary text, helper text, inactive elements |
| Light Taupe | `#e2e2e2` | `--color-light-taupe` | Subtle borders, dividers, accents |
| Mist Grey | `#c9c9c7` | `--color-mist-grey` | Subtle background for UI elements, light borders |
| Action Orange | `#ee884f` | `--color-action-orange` | Primary call to action buttons, interactive element accents — conveying urgency and focus |
| Subtle Violet | `#9da5c7` | `--color-subtle-violet` | Decorative background for featured product sections |
| Subtle Sage | `#adc2b2` | `--color-subtle-sage` | Decorative background for featured product sections |

## Tokens — Typography

### Archivo — All textual content, from headings to body text and navigation. Its condensed geometric style provides a contemporary feel without sacrificing readability. Letter spacing is subtly tightened for headlines for impact, and slightly expanded for smaller UI elements for clarity. · `--font-archivo`
- **Substitute:** Arial, Helvetica Neue, sans-serif
- **Weights:** 400, 600
- **Sizes:** 11px, 13px, 14px, 15px, 16px, 18px, 36px, 44px, 52px, 68px
- **Line height:** 1.3
- **Letter spacing:** -0.0300em, -0.0100em, 0.0600em
- **Role:** All textual content, from headings to body text and navigation. Its condensed geometric style provides a contemporary feel without sacrificing readability. Letter spacing is subtly tightened for headlines for impact, and slightly expanded for smaller UI elements for clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 0.06px | `--text-caption` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 36px | 1.2 | -0.01px | `--text-heading-sm` |
| heading | 44px | 1.1 | -0.03px | `--text-heading` |
| heading-lg | 52px | 1 | -0.03px | `--text-heading-lg` |
| display | 68px | 0.9 | -0.03px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 4800px |
| buttons | 4px |
| default | 4px |
| navigation | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.01) 0px 4px 1px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle` |

### Layout

- **Section gap:** 196px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with 'Action Orange' (#ee884f) background and Canvas White (#ffffff) text. Features 4px border-radius and 8px vertical, 16px horizontal padding. Indicates a primary conversion point.

### Ghost Button
**Role:** Secondary action

Ghost button with Anchor Ink (#1e1e1e) text and transparent background. Padding of 24px around text. Used for less emphasized actions or navigation.

### Pill Ghost Button
**Role:** Informational tag or filter

Ghost button with `rgba(30, 30, 30, 0.2)` semi-transparent background, Anchor Ink (#1e1e1e) text, and a virtually infinite 4800px border-radius to create a pill shape. Padding is 0px vertical, 8px horizontal. Used for small, contained labels or actions.

### Navigation Item Button
**Role:** Navigation

Button with Pale Stone (#f5f2f0) background and Anchor Ink (#1e1e1e) text. Features 0px border-radius and 24px padding. Used in main navigation for product features.

### Card Surface
**Role:** Content container

Default card has a Canvas White (#ffffff) background and 4px border-radius. Padding of 24px vertical and horizontal. Applies a subtle shadow (rgba(0,0,0,0.01) 0px 4px 1px,...).

### Text Input Field
**Role:** User input

Input fields have a light background, likely Canvas White (#ffffff) or Pale Stone (#f5f2f0), with a subtle 1px border in a light grey tone, often Light Taupe (#e2e2e2) or Mist Grey (#c9c9c7). Active states may involve a slightly darker border or shadow.

## Do's and Don'ts

### Do
- Use Anchor Ink (#1e1e1e) for primary body text, headings, and most borders to establish visual weight and clarity.
- Employ Canvas White (#ffffff) as the primary background for all elevated elements, cards, and interactive components.
- Highlight primary calls to action exclusively with Action Orange (#ee884f), ensuring it stands out against the muted palette.
- Apply a consistent 4px border-radius to all interactive elements like buttons and cards, creating a soft, friendly touch.
- Maintain generous spacing around sections (sectionGap: 196px) to give content ample breathing room and create a calm rhythm.
- Use Archivo font for all typography, ensuring a unified and consistent textual appearance.
- Utilize Pale Stone (#f5f2f0) or Off-White (#f0e9e5) for secondary background surfaces to differentiate content blocks subtly without introducing strong color.

### Don't
- Do not introduce new vivid colors; stick to Anchor Ink and Action Orange for all functional color accents.
- Avoid aggressive shadows; instead, use the subtle shadow style `rgba(0,0,0,0.01) 0px 4px 1px 0px, rgba(0,0,0,0.04) 0px 2px 1px 0px, rgba(0,0,0,0.06) 0px 1px 1px 0px` for minimal elevation.
- Refrain from using sharp, angular corners; the consistent use of 4px radius is core to the system's feel.
- Do not vary line-height significantly from the established Archivo scales to maintain typographic consistency and hierarchy.
- Avoid cluttering sections; prioritize clear hierarchy and ample white space (elementGap: 24px) over dense information displays.
- Do not use dark backgrounds for general content areas; the system is designed around a light-mode foundation with occasional dark footer/hero accents.
- Do not use unrounded buttons; all buttons should respect the 4px or 4800px radius.

## Elevation

- **Card Surface:** `rgba(0,0,0,0.01) 0px 4px 1px 0px, rgba(0,0,0,0.04) 0px 2px 1px 0px, rgba(0,0,0,0.06) 0px 1px 1px 0px`
- **Navigation and Buttons:** `rgba(0,0,0,0.01) 0px 4px 1px 0px, rgba(0,0,0,0.04) 0px 2px 1px 0px, rgba(0,0,0,0.06) 0px 1px 1px 0px`

## Imagery

The visual language for imagery leans towards functional UI mockups and clean, abstract product visuals. Photography is absent. Illustrations are minimalistic, often depicting connected services or abstract concepts in a flat, outlined style. Icons are simple, monochrome, and have a consistent stroke weight, used primarily for functional explanations rather than decorative purposes. Imagery serves to explain product features and showcase the UI, maintaining a text-dominant layout with imagery serving as supportive content rather than full-bleed atmosphere.

## Layout

The page employs a contained layout with some full-bleed sections. The hero prominently features a split design with a large, bold headline on the left against a Canvas White background, and a product UI screenshot on the right against a muted background (Subtle Violet or Subtle Sage). Sections alternate between Canvas White and Dusty Rose backgrounds, creating a clear vertical rhythm. Content often arranges in two-column layouts, balancing text and supporting visuals. Navigation is a sticky top bar with minimal links and a prominent 'Book a demo' button. Density is comfortable, with generous breathing room between content blocks, fostering a sense of professionalism and clarity.

## Agent Prompt Guide

Quick Color Reference: 
  text: #1e1e1e
  background: #ffffff
  border: #e2e2e2
  accent: #ee884f (no distinct CTA color)
  primary action: #ee884f (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ee884f background, #1e1e1e text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a navigation text link: `color: #1e1e1e; font-weight: 400; font-size: 15px; letter-spacing: 0.06em;`
3. Create a content card: `background-color: #ffffff; border-radius: 4px; padding: 24px; box-shadow: rgba(0,0,0,0.01) 0px 4px 1px 0px, rgba(0,0,0,0.04) 0px 2px 1px 0px, rgba(0,0,0,0.06) 0px 1px 1px 0px;`
4. Create a hero section headline: `font-size: 68px; font-weight: 600; color: #1e1e1e; line-height: 0.9; letter-spacing: -0.03em;`

## Similar Brands

- **Rippling** — Monochrome base with a single-color accent for CTA, clean grid layouts, and product UI screenshots.
- **Linear** — Stark achromatic UI, subtle elevations, highly legible sans-serif typography, and functional component design.
- **Coda** — White canvas, focused typography, minimal use of color, and clear separation of content blocks.
- **Vercel** — Emphasis on dark text on light backgrounds, strong typographic hierarchy, and clean, unembellished interface elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-anchor-ink: #1e1e1e;
  --color-canvas-white: #ffffff;
  --color-pale-stone: #f5f2f0;
  --color-off-white: #f0e9e5;
  --color-dusty-rose: #e3d7cd;
  --color-charcoal: #292929;
  --color-cadet-grey: #767676;
  --color-light-taupe: #e2e2e2;
  --color-mist-grey: #c9c9c7;
  --color-action-orange: #ee884f;
  --color-subtle-violet: #9da5c7;
  --color-subtle-sage: #adc2b2;

  /* Typography — Font Families */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.01px;
  --text-heading: 44px;
  --leading-heading: 1.1;
  --tracking-heading: -0.03px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 68px;
  --leading-display: 0.9;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 196px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 4800px;

  /* Named Radii */
  --radius-pill: 4800px;
  --radius-buttons: 4px;
  --radius-default: 4px;
  --radius-navigation: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.01) 0px 4px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 1px 0px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-anchor-ink: #1e1e1e;
  --color-canvas-white: #ffffff;
  --color-pale-stone: #f5f2f0;
  --color-off-white: #f0e9e5;
  --color-dusty-rose: #e3d7cd;
  --color-charcoal: #292929;
  --color-cadet-grey: #767676;
  --color-light-taupe: #e2e2e2;
  --color-mist-grey: #c9c9c7;
  --color-action-orange: #ee884f;
  --color-subtle-violet: #9da5c7;
  --color-subtle-sage: #adc2b2;

  /* Typography */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.01px;
  --text-heading: 44px;
  --leading-heading: 1.1;
  --tracking-heading: -0.03px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 68px;
  --leading-display: 0.9;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 4800px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.01) 0px 4px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 1px 0px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0px;
}
```
