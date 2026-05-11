# Spacelab — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Spacelab employs a stark, high-contrast visual language reminiscent of architectural blueprints or gallery spaces. Typography is critical, with a single, highly legible sans-serif used across all scales, grounding the design in clarity and precision. The visual field prioritizes ample negative space; elements are sparsely distributed, creating a sense of calm and order. A single muted violet-blue serves as the primary accent, providing a deep, grounding touch of color against an otherwise achromatic palette of black, white, and subtle grays. Component styling is minimalist and functional, relying on sharp edges and direct expression rather than ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text on dark elements |
| Ink Black | `#000000` | `--color-ink-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Graphite | `#2c2222` | `--color-graphite` | Body text, secondary text, subtle card borders, default icon fill |
| Stone Gray | `#b2b4b1` | `--color-stone-gray` | Muted secondary text, inactive link states, hairline borders |
| Deep Violet | `#495472` | `--color-deep-violet` | Primary brand accent, button backgrounds, active card states. This muted, deep tone provides authority without aggression |

## Tokens — Typography

### Helvetica Neue — The primary typeface for all content. Its crisp, neutral form supports the system's objective clarity. The wide range of sizes with consistent letter-spacing across all weights maintains a precise, consistent visual texture. · `--font-helvetica-neue`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 15px, 17px, 19px, 21px, 30px, 62px
- **Line height:** 1.00, 1.07, 1.10, 1.15, 1.20
- **Letter spacing:** 0.0110em
- **Role:** The primary typeface for all content. Its crisp, neutral form supports the system's objective clarity. The wide range of sizes with consistent letter-spacing across all weights maintains a precise, consistent visual texture.

### HelveticaNeue-Light — HelveticaNeue-Light — detected in extracted data but not described by AI · `--font-helveticaneue-light`
- **Weights:** 400
- **Sizes:** 17px
- **Line height:** 1.2
- **Letter spacing:** 0.011
- **Role:** HelveticaNeue-Light — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1 | 0.011px | `--text-caption` |
| body-sm | 17px | 1.2 | 0.011px | `--text-body-sm` |
| body | 19px | 1.1 | 0.011px | `--text-body` |
| subheading | 21px | 1.15 | 0.011px | `--text-subheading` |
| heading | 30px | 1.2 | 0.011px | `--text-heading` |
| display | 62px | 1.07 | 0.011px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 21 | 21px | `--spacing-21` |
| 42 | 42px | `--spacing-42` |
| 84 | 84px | `--spacing-84` |
| 147 | 147px | `--spacing-147` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| cards | 0px |
| small | 4px |
| buttons | 0px |

### Layout

- **Section gap:** 42px
- **Card padding:** 21px
- **Element gap:** 21px

## Components

### Primary Action Button
**Role:** Interactive element

Solid filled button with Deep Violet background (#495472) and Canvas White (#ffffff) text. Features sharp, unrounded corners (0px radius) and generous padding (21px horizontal, 21px vertical). There is no border, creating a monolithic block. Uses Helvetica Neue 400 at an appropriate size with 0.0110em letter-spacing.

### Navigation Link List
**Role:** Navigation element

A vertical list of navigational links, with Ink Black (#000000) for active or primary links and Stone Gray (#b2b4b1) for secondary or inactive options. Each link has 21px of bottom margin and no visible border, maintaining a minimalist appearance. Uses Helvetica Neue 400.

### Feature Card
**Role:** Content display

A frameless content container with a transparent background (rgba(0,0,0,0)) and no shadow, creating a flat, integrated feel within the layout. It uses Ink Black (#000000) for primary content and includes significant horizontal padding (21px), but no vertical padding by default on title type elements, relying on the overall layout for vertical rhythm. Text uses Helvetica Neue.

### Circular Image Card
**Role:** Visual content display

A card designated for showcasing visuals, characterized by a truly circular shape (100% border-radius). The background is Deep Violet (#495472) and has no shadow. Heavy top padding (84px) and bottom padding (42px) with no horizontal padding, indicating an image-dominant display. The image itself would be contained within, likely cropped to fit the circle.

### Subtle Link Text
**Role:** Secondary navigation or semantic link

Text link using Stone Gray (#b2b4b1) on a light background, indicating a secondary or less prominent interactive element. This allows primary black text to stand out while still signaling interactivity. Uses Helvetica Neue 400.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the dominant background, creating an expansive, gallery-like canvas for all content.
- Use Ink Black (#000000) for primary headings and prominent text elements to ensure high contrast and visual weight.
- Apply Deep Violet (#495472) exclusively for primary interactive elements like button backgrounds and active states, making actions deliberate and distinct.
- Maintain sharp, unrounded corners (0px radius) for all primary components like buttons and cards, reinforcing a precise, architectural aesthetic.
- Employ a consistent 21px `elementGap` and `cardPadding` for horizontal and some vertical spacing, establishing a clear and comfortable rhythm.
- Use Helvetica Neue 400 across all typographic elements with a consistent 0.0110em letter-spacing to ensure legibility and a unified, refined voice.
- Integrate Stone Gray (#b2b4b1) for less prominent text, inactive links, or subtle decorative lines to provide visual texture without competing with primary content.

### Don't
- Avoid using rounded corners on any primary interactive elements or content containers; the system is defined by its sharp, clean edges.
- Do not introduce additional chromatic colors beyond the established Deep Violet (#495472) as the primary brand accent, to maintain a minimalist palette.
- Refrain from using shadows or gradients on interactive elements or surfaces; the design relies on flat, direct visual communication.
- Do not increase letter-spacing beyond 0.0110em for any text, as the system relies on tight, controlled typography for its crisp appearance.
- Avoid dense UI layouts; maintain generous negative space around elements and between sections to emphasize clarity and breathability.
- Do not use decorative background patterns or expressive textures; the design values clean, solid surfaces and high contrast.
- Avoid mixing typefaces; the design relies on the singular, precise character of Helvetica Neue for all textual expression.

## Imagery

The site heavily features high-resolution photography, specifically of architectural interiors and people within these spaces. Images are contained and often full-width or large-scale, acting as primary content blocks. When shown in component context, like the Circular Image Card, they are cropped precisely. There's an absence of decorative illustrations or abstract graphics. Photography is likely high-key but can include natural lighting, maintaining a realistic and professional aesthetic. Icons are minimal, likely monochromatic and vector-based, serving purely functional roles.

## Layout

The page adheres to a maximal-width, side-aligned layout with no explicit pageMaxWidth, allowing content to stretch. The hero section features a prominent brand name and navigation vertically aligned to the left, occupying significant negative space adjacent to a large, compelling image. Content sections appear to be vertically stacked, defined by generous vertical spacing (42px `sectionGap`) and large visual blocks, often with a clear left-aligned typographic emphasis and a significant image on the right or below. The main layout seems to be a two-column division between navigation/branding (left, narrow) and content (right, wide), which then breaks into full-width content blocks. The rhythm is sparse and open, creating a sense of spaciousness and ease of focus.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #495472
primary action: #495472 (filled action)

Example Component Prompts:
Create a primary navigation link: uses Helvetica Neue 400 at 19px, Ink Black (#000000), 0.0110em letter-spacing, with 21px bottom margin.
Create a hero section: Canvas White (#ffffff) background. Headline at 62px Helvetica Neue 400, Ink Black (#000000), 0.0110em letter-spacing, 1.07 line height. Align text left with significant negative space. Include a large, architectural photograph on the right.
Create a Primary Action Button: #495472 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a subtle informational link: uses Helvetica Neue 400 at 17px, Stone Gray (#b2b4b1), 0.0110em letter-spacing.

## Similar Brands

- **Norm Architects** — Shares a minimalist approach, heavy use of black and white, and focus on architectural photography with subtle typographic details.
- **Archi.design** — Employs similar high-contrast neutral palette and large-scale imagery, emphasizing clean lines and spatial clarity.
- **B&B Italia** — Uses large product/architectural imagery, crisp sans-serif typography, and a refined, uncluttered presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #2c2222;
  --color-stone-gray: #b2b4b1;
  --color-deep-violet: #495472;

  /* Typography — Font Families */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helveticaneue-light: 'HelveticaNeue-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1;
  --tracking-caption: 0.011px;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.011px;
  --text-body: 19px;
  --leading-body: 1.1;
  --tracking-body: 0.011px;
  --text-subheading: 21px;
  --leading-subheading: 1.15;
  --tracking-subheading: 0.011px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: 0.011px;
  --text-display: 62px;
  --leading-display: 1.07;
  --tracking-display: 0.011px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-21: 21px;
  --spacing-42: 42px;
  --spacing-84: 84px;
  --spacing-147: 147px;

  /* Layout */
  --section-gap: 42px;
  --card-padding: 21px;
  --element-gap: 21px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-cards: 0px;
  --radius-small: 4px;
  --radius-buttons: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #2c2222;
  --color-stone-gray: #b2b4b1;
  --color-deep-violet: #495472;

  /* Typography */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helveticaneue-light: 'HelveticaNeue-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1;
  --tracking-caption: 0.011px;
  --text-body-sm: 17px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.011px;
  --text-body: 19px;
  --leading-body: 1.1;
  --tracking-body: 0.011px;
  --text-subheading: 21px;
  --leading-subheading: 1.15;
  --tracking-subheading: 0.011px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: 0.011px;
  --text-display: 62px;
  --leading-display: 1.07;
  --tracking-display: 0.011px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-21: 21px;
  --spacing-42: 42px;
  --spacing-84: 84px;
  --spacing-147: 147px;

  /* Border Radius */
  --radius-md: 4px;
}
```
