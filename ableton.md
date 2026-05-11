# Ableton — Style Reference
> High-contrast digital studio. A canvas of stark black and white, illuminated by electric blue.

**Theme:** light

This design system presents a digital canvas for creative tools, characterized by its stark, high-contrast monochrome base with strategic, vibrant accents. The primary palette of black and white, occasionally softened by light gray, is frequently punctuated by a singular, intense violet-blue. This creates an energetic, almost electric, feel, reflecting the dynamic nature of music production. Typography is assertive and direct yet uses a soft geometry, balancing instruction with visual appeal.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, button text, iconic elements – provides strong legibility and defines structural outlines. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button backgrounds – the primary stage for all content. |
| Studio Gray | `#eeeeee` | `--color-studio-gray` | Input field backgrounds, subtle background separations – provides minimal visual distinction in UI elements. |
| Electric Violet | `#0000ff` | `--color-electric-violet` | Interactive elements like navigation links, primary call-to-action buttons, active states – a high-energy focal point that signifies interaction and importance. |
| Melody Red | `#ff8389` | `--color-melody-red` | Categorization badges on content cards – a warm, vibrant accent for content taxonomy. |
| Synth Teal | `#00d2be` | `--color-synth-teal` | Categorization badges on content cards – a cool, energetic accent for content taxonomy. |

## Tokens — Typography

### futura-pt — The primary typeface for all content, from headings to body text and interactive elements. Its geometric forms provide a technical yet approachable feel, integral to the brand's identity creating a forward-thinking aesthetic. · `--font-futura-pt`
- **Substitute:** Futura
- **Weights:** 400, 700
- **Sizes:** 14px, 16px, 20px, 24px, 30px, 40px, 90px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** normal
- **OpenType features:** `'kern'`
- **Role:** The primary typeface for all content, from headings to body text and interactive elements. Its geometric forms provide a technical yet approachable feel, integral to the brand's identity creating a forward-thinking aesthetic.

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 203 | 203px | `--spacing-203` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 69px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Primary Call-to-Action Button
**Role:** Action

Solid Electric Violet background (#0000ff) with Canvas White text (#ffffff), no border-radius, 7px vertical and 30px horizontal padding. Font is futura-pt 400.

### Category Tag Button - Melody Red
**Role:** Categorization

Solid Melody Red background (#ff8389) with Midnight Ink text (#000000), no border-radius, 1.96px vertical and 11.9px horizontal padding. Font is futura-pt 400.

### Category Tag Button - Synth Teal
**Role:** Categorization

Solid Synth Teal background (#00d2be) with Midnight Ink text (#000000), no border-radius, 1.96px vertical and 11.9px horizontal padding. Font is futura-pt 400.

### Ghost Button
**Role:** Secondary action

Transparent background, Midnight Ink text (#000000), no border-radius or visible padding, typically used for inline actions.

### Basic Card
**Role:** Content container

Transparent background, no border-radius, no box shadow, 0px padding. Acts as a structural grouping without adding visual weight.

### Input Field
**Role:** Form Element

Studio Gray background (#eeeeee) with Midnight Ink text (#000000), no border-radius, 8px vertical and 15px horizontal padding. Font is futura-pt 400.

### Navigation Link
**Role:** Navigation

Midnight Ink text (#000000) for unselected state, Electric Violet (#0000ff) for active/hover state. Font is futura-pt 400, 16px. No specific padding detected, relies on element spacing.

### Hero Headline
**Role:** Primary heading

Midnight Ink text (#000000), futura-pt 700 at 90px size, line-height 1.0. Used for dominant page titles capturing immediate attention.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text elements to ensure high contrast.
- Apply Canvas White (#ffffff) as the default background for content sections.
- Utilize Electric Violet (#0000ff) exclusively for primary interactive elements, such as CTA buttons and active navigation links, to draw attention.
- Maintain a consistent `0px` border-radius across all buttons, cards, and input fields for a sharp, unyielding aesthetic.
- Employ futura-pt throughout the UI, with variations in weight and size to create hierarchy while retaining brand consistency.
- Maintain minimal vertical padding of 1.96px for utility tags with a vibrant background and 7px for primary action buttons.

### Don't
- Avoid using drop shadows or complex gradients; the aesthetic relies on flat, high-contrast surfaces.
- Do not introduce additional rounded corners beyond `0px`; sharp edges are a defining characteristic.
- Do not deviate from the futura-pt typeface; alternative fonts will dilute the brand's typographic identity.
- Refrain from using Electric Violet (#0000ff) for purely decorative elements; reserve it for interactive or highlight states.
- Do not use background colors other than Canvas White (#ffffff) or Studio Gray (#eeeeee) for primary content containers; chromatic colors are for accents only.
- Avoid excessive spacing between elements; a comfortable but not overly sparse density is preferred, often using `10px` element gaps.

## Imagery

The visual language is utilitarian and product-focused, featuring tight shots of hardware and software interfaces. Photography often captures studio environments or creative practitioners interacting with Ableton's tools, lending an authentic, creator-centric feel. Treatments are generally full-bleed or contained within sharp-edged containers, with a raw, unpolished quality that suggests real-world usage rather than glossy abstraction. Icons are monochrome, often Midnight Ink on Canvas White backgrounds, with a clear, outlined style that complements the geometric typography. Imagery serves primarily to showcase the product's functionality and its place in the creative process, blending seamlessly with the high-contrast UI.

## Layout

The page exhibits a mix of full-bleed and constrained content. The hero section is full-bleed, showcasing a product shot with a large, centered headline. Subsequent sections often feature a `1200px` max-width centered container, breaking into two-column layouts with text on one side and a corresponding image or nested content cards on the other. Vertical rhythm is established through consistent section gaps, maintaining a comfortable density. Navigation is a sticky top bar, providing persistent access to key tools. Content is arranged to present information in visually digestible blocks, often in grids of 3, keeping visual clutter to a minimum and emphasizing direct interaction with media and text.

## Agent Prompt Guide

**Quick Color Reference:**
- Text: #000000 (Midnight Ink)
- Background: #ffffff (Canvas White)
- CTA: #0000ff (Electric Violet)
- Border: #000000 (Midnight Ink - where applicable)
- Accent: #ff8389 (Melody Red)

**3-5 Example Component Prompts:**
1. Create a primary call-to-action button: background #0000ff, text #ffffff, futura-pt 400 16px, padding 7px 30px, border-radius 0px, text 'Try Live 12 free'.
2. Design a content card: transparent background, 0px border-radius, no shadow. Above the content, place a category tag: background #ff8389, text #000000, futura-pt 400 14px, padding 1.96px 11.9px, text 'Downloads'.
3. Generate a primary heading: text #000000, futura-pt 700 90px, line-height 1.0, text 'Rent-to-own – now available for all upgrades'.
4. Create an input field: background #eeeeee, text #000000, futura-pt 400 16px, padding 8px 15px, border-radius 0px, placeholder text 'Search...'.
5. Implement a navigation link: text #000000, futura-pt 400 16px, on hover/active change text to #0000ff, text 'Shop'.

## Similar Brands

- **Native Instruments** — Dominance of black and white surfaces with strategic, often single-color, high-contrast accents, and sharp UI elements.
- **Teenage Engineering** — Minimalist aesthetic with a focus on geometric forms, high contrast, and a 'tool-like' functional visual identity.
- **Splice** — Clean, modern UI that leverages a restricted color palette for clarity, punctuated by bright, functional accent colors.
- **Bitwig Studio** — Dark UI elements combined with clean lines and occasional vibrant color indicators for functions, reflecting a technical software interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-studio-gray: #eeeeee;
  --color-electric-violet: #0000ff;
  --color-melody-red: #ff8389;
  --color-synth-teal: #00d2be;

  /* Typography — Font Families */
  --font-futura-pt: 'futura-pt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 14px;
  --leading-sm: 1.5;
  --text-base: 16px;
  --leading-base: 1.5;
  --text-xl: 20px;
  --leading-xl: 1.5;
  --text-2xl: 24px;
  --leading-2xl: 1.5;
  --text-3xl: 30px;
  --leading-3xl: 1.4;
  --text-4xl: 40px;
  --leading-4xl: 1.2;
  --text-5xl: 90px;
  --leading-5xl: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-203: 203px;

  /* Layout */
  --section-gap: 69px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-studio-gray: #eeeeee;
  --color-electric-violet: #0000ff;
  --color-melody-red: #ff8389;
  --color-synth-teal: #00d2be;

  /* Typography */
  --font-futura-pt: 'futura-pt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 14px;
  --leading-sm: 1.5;
  --text-base: 16px;
  --leading-base: 1.5;
  --text-xl: 20px;
  --leading-xl: 1.5;
  --text-2xl: 24px;
  --leading-2xl: 1.5;
  --text-3xl: 30px;
  --leading-3xl: 1.4;
  --text-4xl: 40px;
  --leading-4xl: 1.2;
  --text-5xl: 90px;
  --leading-5xl: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-203: 203px;
}
```
