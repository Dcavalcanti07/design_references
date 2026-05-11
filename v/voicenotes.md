# Voicenotes — Style Reference
> Digital Ledger on Canvas

**Theme:** light

Voicenotes employs a 'digital ledger' aesthetic: a strong, classic serif for headlines against a clean, near-white background, contrasted with a functional sans-serif for body text. The visual system prioritizes content clarity and a sense of weighty authority, using subtle light gray surfaces and discreet borders. Elevation is minimal, giving components a flat, integrated feel, while a single intense black button signals primary actions with directness and confidence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `linear-gradient(90deg, rgba(255, 255, 255, 0.7), rgba(209, 250, 219, 0.7) 15%, rgba(102, 240, 224, 0.7) 50%, rgba(0, 136, 255, 0.7) 100%, rgba(255, 255, 255, 0.7) 0px)` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text color for dark buttons; Atmospheric background gradient for decorative or hero sections, adding a subtle blend of pastels |
| Ghost Gray | `#faf9f5` | `--color-ghost-gray` | Subtle page background behind the main content area, providing a barely-there distinction from card surfaces |
| Slate Ink | `#0d0d0d` | `--color-slate-ink` | Primary text color for headlines and body text, button backgrounds for primary actions |
| Subtle Gray | `#e5e7eb` | `--color-subtle-gray` | Hairline borders for cards, inputs, and dividers, creating separation without visual weight |
| Text Gray | `#717171` | `--color-text-gray` | Muted body text, helper text, and secondary icon fills |
| Shadow Blue | `#eaf2f8` | `--color-shadow-blue` | Subtle background color for secondary cards or content sections |
| Deep Graphite | `#222222` | `--color-deep-graphite` | Used for prominent heading text, deeper than Slate Ink for added emphasis |
| Success Green | `#34c759` | `--color-success-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### ui-sans-serif — ui-sans-serif — detected in extracted data but not described by AI · `--font-ui-sans-serif`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** ui-sans-serif — detected in extracted data but not described by AI

### InstrumentSerif-Regular — Display and marketing headlines. Its bold, classic serif evokes trustworthiness and gravitas. · `--font-instrumentserif-regular`
- **Substitute:** Source Serif Pro
- **Weights:** 400
- **Sizes:** 20px, 60px, 80px
- **Line height:** 1.00, 1.17, 1.40
- **Letter spacing:** -0.0200em
- **Role:** Display and marketing headlines. Its bold, classic serif evokes trustworthiness and gravitas.

### Inter — Primary sans-serif for body text, interface labels, and subheadings across all weights. Its slightly compact tracking at smaller sizes maintains readability in dense UIs. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.33, 1.38, 1.40, 1.43, 1.47, 1.50, 1.56, 1.71
- **Letter spacing:** -0.0030em
- **Role:** Primary sans-serif for body text, interface labels, and subheadings across all weights. Its slightly compact tracking at smaller sizes maintains readability in dense UIs.

### Inter — Used for emphasis within body text, navigation items, and button labels, providing clear hierarchy. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 10px, 14px, 16px, 18px
- **Line height:** 1.33, 1.38, 1.43, 1.50, 1.71
- **Letter spacing:** normal
- **Role:** Used for emphasis within body text, navigation items, and button labels, providing clear hierarchy.

### Inter — For strong emphasis, calls to action, and section subheadings, ensuring legibility and quick scanning. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 14px, 15px, 18px
- **Line height:** 1.21, 1.25, 1.33, 1.38, 1.56
- **Letter spacing:** -0.0090em, -0.0030em
- **Role:** For strong emphasis, calls to action, and section subheadings, ensuring legibility and quick scanning.

### Inter — Reserved for small, high-impact text needing maximum prominence. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 10px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Reserved for small, high-impact text needing maximum prominence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.38 | -0.04px | `--text-body` |
| body-lg | 16px | 1.5 | -0.05px | `--text-body-lg` |
| subheading | 18px | 1.47 | -0.05px | `--text-subheading` |
| heading | 20px | 1.4 | -0.05px | `--text-heading` |
| heading-lg | 60px | 1.17 | -1.2px | `--text-heading-lg` |
| display | 80px | 1 | -1.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| forms | 6px |
| avatars | 9999px |
| buttons | 9999px |
| smallCard | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.15) 0px 0px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Navigational or primary action button

Filled button with Slate Ink background (#0d0d0d), white text (#ffffff), and a fully rounded (9999px) border-radius. Padding of 12px vertical and 20px horizontal provides a confident, accessible hit area.

### Subtle Bordered Card
**Role:** Container for content sections

Card with Canvas White background (#ffffff), Subtle Gray border (#e5e7eb) of 1px, and 16px border-radius. Inner padding is 20px on the sides, 20px top, and 28px bottom, creating generous internal spacing.

### Shadowed Flyout Card
**Role:** Elevated menu or tooltip container

Small, elevated card with Canvas White background (#ffffff), 12px border-radius, and a distinct shadow: rgba(0, 0, 0, 0.15) 0px 0px 10px 0px. Used for contextual menus or popovers. Inner padding is 16px on all sides.

### Secondary Background Card
**Role:** Background for feature blocks or subtle distinctions

Card with Shadow Blue background (#eaf2f8) and 16px border-radius, but no border or shadow. Used as a less prominent content container or background panel.

## Do's and Don'ts

### Do
- Use InstrumentSerif-Regular for all primary headings (h1, h2) to leverage its distinct classic feel, with Deep Graphite (#222222) color for maximum impact.
- Apply Slate Ink (#0d0d0d) as the primary text color and button background, ensuring high contrast against Canvas White (#ffffff) or Ghost Gray (#faf9f5).
- All buttons and pill-shaped elements must have a 9999px border-radius for a consistent soft, approachable shape.
- Utilize Subtle Gray (#e5e7eb) for all hairline borders and dividers (1px solid); avoid heavier strokes to maintain a lightweight UI.
- Implement a clear hierarchy for textual information using Inter with its various weights: Regular for body, Medium for labels, SemiBold for subheadings and strong calls-to-action.
- Maintain generous padding for interactive elements; buttons require 12px vertical and 20px horizontal padding as a minimum.
- Use the Ghost Gray (#faf9f5) for the main content background, reserving Canvas White (#ffffff) for explicit cards or elevated surfaces to create subtle depth.

### Don't
- Do not use heavily saturated colors for backgrounds or large areas; chromatically distinct colors are reserved for small, functional accents like status indicators.
- Avoid applying multiple shadows or strong gradients to primary UI elements; the system relies on subtle surface changes and minimal elevation.
- Do not use thin or light text weights for essential body copy; Inter Regular with Slate Ink (#0d0d0d) or Text Gray (#717171) should be the minimum for readability.
- Do not mix serif and sans-serif fonts in the same sentence or for closely related elements; the serif is for impactful headlines, the sans-serif for UI and paragraph text.
- Do not break the compact spacing rhythm; adhere to the 4px base unit, with element gaps around 16px and card padding at 20px, to maintain density.
- Avoid using generic blue for links if it clashes with the brand's subdued chromatic palette; text links should primarily be Slate Ink (#0d0d0d) or Deep Graphite (#222222) with underline.
- Do not introduce square or minimally rounded corners for interactive elements; the consistent 9999px radius for buttons and tags is key to the brand's aesthetic.

## Imagery

Imagery primarily consists of contained product screenshots and tasteful, subtle abstract illustrations. Photography, if present, is of people engaging with the product, often tightly cropped to focus on expression or interaction. Product screenshots are typically presented within mock device frames, maintaining a clean, integrated feel. Icons are monochrome, outlined, and minimal, serving purely functional roles. The density is moderate, balancing descriptive UI elements with explanatory text, avoiding a cluttered or heavily illustrated feel.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px wide, centered on a Ghost Gray background. The hero section is full-bleed with a large, centered serif headline over a subtle gradient graphic. Sections follow a consistent vertical rhythm with ample sectionGap, often featuring side-by-side arrangements of text and graphics or product UIs. Content is generally aligned to a center axis within its contained width, with some sections breaking into grids for features or testimonials.

## Agent Prompt Guide

**Quick Color Reference**
text: #0d0d0d
background: #faf9f5
border: #e5e7eb
accent: #ffffff (for gradient)
primary action: #0d0d0d (filled action)

**3-5 Example Component Prompts**
1. Create a primary call-to-action button: background #0d0d0d, text #ffffff, 9999px radius, 12px vertical padding, 20px horizontal padding, using Inter SemiBold 16px text.
2. Design a feature card: background #ffffff, 1px solid border #e5e7eb, 16px border-radius, 20px padding on all sides, with Inter Regular 14px text #0d0d0d and a heading using InstrumentSerif-Regular 20px text #222222.
3. Build an elevated popover container: background #ffffff, 12px border-radius, box-shadow rgba(0, 0, 0, 0.15) 0px 0px 10px 0px, 16px internal padding, containing Inter Medium 14px text #0d0d0d.
4. Construct a section background panel: background #eaf2f8, 16px border-radius, with no border or shadow, intended to contain other UI elements.
5. Create a primary headline for a section: text 'Meetings end. Your notes don't.' using InstrumentSerif-Regular, 60px, weight 400, color #222222, letter-spacing -1.2px, line-height 1.17.

## Similar Brands

- **Linear** — Monochromatic interface with a single, clear accent color (though Voicenotes' is muted), strong typography, and subtle elevation.
- **Stripe** — Clean, light UI, with emphasis on clear typography, geometric sans-serif for UI, and a reserved use of accent colors.
- **Superhuman** — High-contrast text on light backgrounds, compact yet readable information density, and a focus on functional utility over decorative elements.
- **Arc Browser** — Emphasizes a sophisticated type system of sans-serif for UI and a subtle use of background shades for surface differentiation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --gradient-canvas-white: linear-gradient(90deg, rgba(255, 255, 255, 0.7), rgba(209, 250, 219, 0.7) 15%, rgba(102, 240, 224, 0.7) 50%, rgba(0, 136, 255, 0.7) 100%, rgba(255, 255, 255, 0.7) 0px);
  --color-ghost-gray: #faf9f5;
  --color-slate-ink: #0d0d0d;
  --color-subtle-gray: #e5e7eb;
  --color-text-gray: #717171;
  --color-shadow-blue: #eaf2f8;
  --color-deep-graphite: #222222;
  --color-success-green: #34c759;

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrumentserif-regular: 'InstrumentSerif-Regular', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.04px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.05px;
  --text-subheading: 18px;
  --leading-subheading: 1.47;
  --tracking-subheading: -0.05px;
  --text-heading: 20px;
  --leading-heading: 1.4;
  --tracking-heading: -0.05px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -1.2px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;

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

  /* Layout */
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-forms: 6px;
  --radius-avatars: 9999px;
  --radius-buttons: 9999px;
  --radius-smallcard: 12px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 0px 10px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghost-gray: #faf9f5;
  --color-slate-ink: #0d0d0d;
  --color-subtle-gray: #e5e7eb;
  --color-text-gray: #717171;
  --color-shadow-blue: #eaf2f8;
  --color-deep-graphite: #222222;
  --color-success-green: #34c759;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrumentserif-regular: 'InstrumentSerif-Regular', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.04px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.05px;
  --text-subheading: 18px;
  --leading-subheading: 1.47;
  --tracking-subheading: -0.05px;
  --text-heading: 20px;
  --leading-heading: 1.4;
  --tracking-heading: -0.05px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -1.2px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

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

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 0px 10px 0px;
}
```
