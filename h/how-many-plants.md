# How Many Plants — Style Reference
> Artisanal plant journal

**Theme:** light

How Many Plants utilizes a playful, illustrative aesthetic reminiscent of an artisanal zine or handcrafted journal. The visual system combines a creamy off-white canvas with deep charcoal text and bold, earthy chartreuse accents. Strong, graphic outlines define components and illustrations, imparting a clean yet distinctly analog feel. Typography mixes a custom display serif for headlines with a typewriter-style sans-serif, enhancing the bespoke and approachable mood. The design emphasizes spaciousness, using generous padding and margin to give elements room to breathe.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Cream | `#f9f5f1` | `--color-canvas-cream` | Page backgrounds, card surfaces, ghost button background, active link borders |
| Inkwell Black | `#222222` | `--color-inkwell-black` | Primary text, heading text, icon fills, strong borders, active button text, search input borders |
| Sprout Green | `#bfb33b` | `--color-sprout-green` | Decorative accents, illustrative elements, button outline (as a shadow), subtle surface background occasionally |

## Tokens — Typography

### Chromatica — Headlines, navigation links, and prominent display text capitalize on its custom serif character for an illustrative, editorial feel. Its tight leading for larger sizes creates a stacked effect, enhancing visual density. · `--font-chromatica`
- **Substitute:** Playfair Display
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px, 24px, 36px
- **Line height:** 0.89, 1.33, 1.43, 1.60, 2.00
- **Role:** Headlines, navigation links, and prominent display text capitalize on its custom serif character for an illustrative, editorial feel. Its tight leading for larger sizes creates a stacked effect, enhancing visual density.

### Hellenictypewriter — Body text, input fields, and button labels gain a warm, approachable, and slightly retro tone through this custom typewriter sans-serif. Its monospaced feel contrasts with the serifs, providing a grounded, readable counterpoint. · `--font-hellenictypewriter`
- **Substitute:** Roboto Mono
- **Weights:** 400, 500
- **Sizes:** 16px, 20px, 28px, 36px
- **Line height:** 1.14, 1.25, 1.33, 1.60
- **Role:** Body text, input fields, and button labels gain a warm, approachable, and slightly retro tone through this custom typewriter sans-serif. Its monospaced feel contrasts with the serifs, providing a grounded, readable counterpoint.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 2 | — | `--text-caption` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 20px | 1.33 | — | `--text-subheading` |
| heading | 24px | 1.43 | — | `--text-heading` |
| display | 36px | 0.89 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 152 | 152px | `--spacing-152` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| inputs | 0px |
| buttons | 0px |
| default | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(191, 179, 59) 6px 6px 0px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1376px
- **Section gap:** 32px
- **Card padding:** 48px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Main call-to-action button for a planted, vintage feel

Ghost button with Canvas Cream background, Inkwell Black text (Hellenictypewriter weight 400), and an Inkwell Black 1px border. Padding is 12px vertical and 48px horizontal. Has a distinctive 6px offset shadow in Sprout Green, creating a 'peeking' border effect.

### Navigation Link
**Role:** Site navigation and sub-navigation

Text link using Chromatica font (weight 400), Inkwell Black color, 0px padding. The active state is indicated by an Inkwell Black bottom border.

### Search Input
**Role:** Site-wide search functionality

Input field with transparent background, Inkwell Black text (Hellenictypewriter), and a 1px Inkwell Black bottom border. Text padding is 0px vertical and 12px right.

### Text Outline Button
**Role:** Secondary action or category filter

Button with transparent background, Inkwell Black text (Hellenictypewriter), and an Inkwell Black 1px border. No explicit padding provided; assumes minimal inherent content padding.

### Illustrative Shelf
**Role:** Decorative background element with layered content

Solid Sprout Green shape with a 1px Inkwell Black border, often serving as a background shelf for text and illustrations. Used in the hero section to frame content.

## Do's and Don'ts

### Do
- Use Canvas Cream (#f9f5f1) as the primary page background for a warm, inviting base.
- Apply Inkwell Black (#222222) for all primary text, headings, and essential borders to ensure strong contrast and graphic definition.
- Accent key interactive elements and illustrative outlines with Sprout Green (#bfb33b), particularly as an offset shadow under buttons.
- Employ Chromatica for all headings and navigation using its defined sizes for a custom editorial feel, embracing its tight line heights at larger sizes.
- Use Hellenictypewriter for body text, button labels, and input fields to convey a handcrafted, accessible tone.
- Maintain a spacious rhythm with 32px vertical section gaps and 16px horizontal element gaps.
- Utilize 0px border-radius consistently across all components (buttons, inputs, cards) to maintain a crisp, hard-edged aesthetic.

### Don't
- Avoid using gradients; the design relies on solid colors and graphic outlines.
- Do not introduce rounded corners; maintain the consistent 0px border-radius.
- Refrain from drop shadows or soft elevation effects; prefer bold, offset box-shadows in Sprout Green for a distinct graphic accent.
- Do not deviate from the two primary fonts; their interplay is crucial to the brand's identity.
- Avoid tight, cramped layouts; prioritize spaciousness and generous padding in all components.
- Do not use highly saturated or vivid colors beyond Sprout Green; the palette is intentionally restrained to foster a calming, natural atmosphere.
- Never use `rgba(0,0,0,0)` or transparent for background elements unless specifically for a ghost button; visible surfaces should always resolve to Canvas Cream.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Cream | `#f9f5f1` | Base page background and primary card surfaces |
| 1 | Sprout Green Accent | `#bfb33b` | Decorative background elements like illustrative shelves, adding a layer of visual interest and brand accent |

## Agent Prompt Guide

Quick Color Reference:
text: #222222
background: #f9f5f1
border: #222222
accent: #bfb33b
primary action: no distinct CTA color

Example Component Prompts:

No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

2. Create a section heading: 'Get to know your plants' using Chromatica font, weight 400, size 36px, line-height 0.89, color Inkwell Black (#222222). Margin-bottom 32px.

3. Create a search input field: Transparent background. Text color Inkwell Black (#222222) (Hellenictypewriter). Bottom border Inkwell Black (#222222) 1px solid. Padding 0px vertical, 12px right. No border-radius.

4. Design a 'Plant Guides' navigation link: Chromatica font, weight 400, size 16px, color Inkwell Black (#222222). Active state indicated by a 1px Inkwell Black (#222222) bottom border.

## Similar Brands

- **The Sill** — Combines natural themes with a clean, graphic, and approachable brand identity, using custom illustrations and a serene color palette.
- **AIGA Eye on Design** — Utilizes a strong editorial aesthetic with custom typefaces, generous white space, and a mix of bold graphics and detailed illustrations.
- **Baggu** — Known for a playful, graphic style with bold outlines, unique color combinations, and a focus on visual storytelling and illustration.
- **Garden Answer (YouTube channel website)** — Focuses on plant care content with an aim to demystify complex topics, using clear, accessible language and a friendly visual tone.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-cream: #f9f5f1;
  --color-inkwell-black: #222222;
  --color-sprout-green: #bfb33b;

  /* Typography — Font Families */
  --font-chromatica: 'Chromatica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hellenictypewriter: 'Hellenictypewriter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 2;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.43;
  --text-display: 36px;
  --leading-display: 0.89;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-152: 152px;

  /* Layout */
  --page-max-width: 1376px;
  --section-gap: 32px;
  --card-padding: 48px;
  --element-gap: 16px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;
  --radius-default: 0px;

  /* Shadows */
  --shadow-subtle: rgb(191, 179, 59) 6px 6px 0px 0px;

  /* Surfaces */
  --surface-canvas-cream: #f9f5f1;
  --surface-sprout-green-accent: #bfb33b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-cream: #f9f5f1;
  --color-inkwell-black: #222222;
  --color-sprout-green: #bfb33b;

  /* Typography */
  --font-chromatica: 'Chromatica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hellenictypewriter: 'Hellenictypewriter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 2;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.43;
  --text-display: 36px;
  --leading-display: 0.89;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-152: 152px;

  /* Shadows */
  --shadow-subtle: rgb(191, 179, 59) 6px 6px 0px 0px;
}
```
