# Elvina Prasad — Style Reference
> Academic monograph with confident typography.

**Theme:** light

This system projects an academic, almost stark modernity with its high-contrast monochrome palette. The design relies on generous white space and bold typography for impact. Interaction is subtle, using ghost buttons and thin borders rather than heavy fills. The overall atmosphere is discerning and direct, prioritizing content and clarity over decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text color on dark backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, icon fill, background for hero sections |
| Text Graphite | `#333333` | `--color-text-graphite` | Secondary text, link text, borders for ghost buttons and images |
| Surface Frost | `#f7f7f7` | `--color-surface-frost` | Subtle background for UI elements and alternate section backgrounds, providing a soft contrast |

## Tokens — Typography

### Neue Montreal — The primary typeface for headlines, body text, and UI elements. Its large scale and precise letter-spacing contribute to the academic and confident tone. · `--font-neue-montreal`
- **Weights:** 300, 400, 500
- **Sizes:** 11px, 18px, 27px, 178px
- **Line height:** 1.00, 1.10, 1.30, 1.40
- **Letter spacing:** 0.0500em
- **Role:** The primary typeface for headlines, body text, and UI elements. Its large scale and precise letter-spacing contribute to the academic and confident tone.

### Neue Montreal Variable — Used for navigation, links, and specific UI elements, it mirrors the primary typeface's characteristics while offering some subtle variations. · `--font-neue-montreal-variable`
- **Weights:** 400
- **Sizes:** 14px, 32px, 38px, 40px
- **Line height:** 1.00, 1.43
- **Letter spacing:** 0.0500em
- **Role:** Used for navigation, links, and specific UI elements, it mirrors the primary typeface's characteristics while offering some subtle variations.

### Arial — Fallback font, or for small, utility-style text like helper text or captions. · `--font-arial`
- **Substitute:** System Sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Role:** Fallback font, or for small, utility-style text like helper text or captions.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.05px | `--text-body-sm` |
| body | 18px | 1.3 | 0.05px | `--text-body` |
| subheading | 27px | 1.1 | 0.05px | `--text-subheading` |
| heading-sm | 32px | 1 | 0.05px | `--text-heading-sm` |
| heading | 40px | 1 | 0.05px | `--text-heading` |
| display | 178px | 1 | 0.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 21 | 21px | `--spacing-21` |
| 29 | 29px | `--spacing-29` |
| 32 | 32px | `--spacing-32` |
| 50 | 50px | `--spacing-50` |
| 72 | 72px | `--spacing-72` |
| 85 | 85px | `--spacing-85` |
| 89 | 89px | `--spacing-89` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 85px
- **Card padding:** 21px
- **Element gap:** 16px

## Components

### Ghost Navigation Link
**Role:** Primary navigation element

Text link using Neue Montreal Variable at 40px, Text Graphite color, with no background and a 1px solid Text Graphite border on hover or active states. This creates a subtle interactive response.

### Body Text Block
**Role:** Standard paragraph content

Uses Neue Montreal at 18px / 1.3 line height, Ink Black color, with generous overall padding of 21px or more. This prioritizes readability and emphasizes the content.

### Hero Headline
**Role:** Main page headline

Uses Neue Montreal at 178px / 1.0 line height, Canvas White on an Ink Black background, or Ink Black on a Canvas White background. The massive scale and tight line height create a bold, overlapping visual effect.

### Scroll Indicator Text
**Role:** Directional UI helper

Small label for directional cues, uses Arial 14px, Text Graphite color, often accompanied by an icon. Emphasizes utility over display.

### Minimal Call to Action Button
**Role:** Secondary action button

A very minimalist button style consisting of a 1px solid Text Graphite border and Text Graphite body text (Neue Montreal Variable 14px), with a transparent background. No distinct background color, relying on borders for definition.

### Image Border
**Role:** Framing for visual content

Images are typically framed with a 1px solid '#333333' border, giving them a subtle definition against the background.

## Do's and Don'ts

### Do
- Prioritize Neue Montreal for all textual elements unless explicitly specified otherwise, using its full range of weights (300, 400, 500).
- Maintain a bold, high-contrast aesthetic using Ink Black on Canvas White or Canvas White on Ink Black as the primary foreground/background pairs.
- Apply a consistent letter-spacing of 0.0500em for all Neue Montreal and Neue Montreal Variable text to maintain its unique visual signature.
- Utilize 'Text Graphite' (#333333) for all border details, ensuring a unified and subtle visual separation for elements like buttons and images.
- Use generous vertical spacing, typically 85px between major sections, to create an open and uncrowded page layout.
- Employ 'Surface Frost' (#f7f7f7) sparingly as a subtle background for secondary UI elements or to break up white sections without introducing strong color.

### Don't
- Avoid decorative gradients or shadows; the visual system is flat and direct, relying on high contrast and typography.
- Do not introduce strong accent colors or vivid hues unless for specific visual assets (e.g., product screenshots) that are considered content, not UI.
- Resist the temptation to add rounded corners; elements should predominantly use sharp, 0px radii.
- Do not deviate from the specified letter-spacing of 0.0500em for display and body text, as it's a key brand identifier.
- Avoid dense, information-heavy blocks of text; instead, break content into manageable, well-spaced paragraphs.

## Agent Prompt Guide

Quick Color Reference: text: #000000, background: #ffffff, border: #333333, accent: no distinct accent color, primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Ink Black background. Headline 'Human centred designs' using Neue Montreal 178px weight 400, Canvas White color. Add a 'KEEP SCROLLING' body-sm caption in #ffffff with a simple outlined arrow icon, #ffffff stroke.
2. Design a portfolio item card: Canvas White background. An image with a 1px solid #333333 border. A subheading 'Phare Branding' using Neue Montreal 27px weight 400, Ink Black color, with 21px padding.
3. Implement a ghost navigation button for 'MENU': Neue Montreal Variable 40px weight 400, Ink Black color. No background, 1px solid #333333 border on hover.

## Similar Brands

- **Figma** — High-contrast minimalist interface, focus on direct typography and functional elements.
- **Linear** — Clean, almost sparse UI with deliberate use of spacing and emphasis on clear type hierarchy.
- **Are.na** — Grid-based layouts, focus on content and strong visual separation with minimal decorative styling.
- **Dropbox Design** — Subtle use of color, heavy reliance on grayscale, and powerful typography for brand expression.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-text-graphite: #333333;
  --color-surface-frost: #f7f7f7;

  /* Typography — Font Families */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-montreal-variable: 'Neue Montreal Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.05px;
  --text-body: 18px;
  --leading-body: 1.3;
  --tracking-body: 0.05px;
  --text-subheading: 27px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.05px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: 0.05px;
  --text-display: 178px;
  --leading-display: 1;
  --tracking-display: 0.05px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-21: 21px;
  --spacing-29: 29px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-72: 72px;
  --spacing-85: 85px;
  --spacing-89: 89px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 85px;
  --card-padding: 21px;
  --element-gap: 16px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-text-graphite: #333333;
  --color-surface-frost: #f7f7f7;

  /* Typography */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-montreal-variable: 'Neue Montreal Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.05px;
  --text-body: 18px;
  --leading-body: 1.3;
  --tracking-body: 0.05px;
  --text-subheading: 27px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.05px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: 0.05px;
  --text-display: 178px;
  --leading-display: 1;
  --tracking-display: 0.05px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-21: 21px;
  --spacing-29: 29px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-72: 72px;
  --spacing-85: 85px;
  --spacing-89: 89px;
  --spacing-180: 180px;
}
```
