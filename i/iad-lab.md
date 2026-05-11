# Iad-lab — Style Reference
> Academic Dark Canvas – a stark, authoritative presentation with bold typographic statements on a deep charcoal ground.

**Theme:** dark

IAD-Lab's visual identity centers around stark contrasts and heavy typography, creating an assertive, academic tone. The dark canvas provides a backdrop for crisp white text and geometric imagery, prioritizing content legibility. Minimal use of color ensures that any visual elements that do use color, such as hero imagery, carry significant impact. Component styling uses softened corners and generous spacing, allowing individual elements to exist distinctly within the dark layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Charcoal | `#222222` | `--color-storm-charcoal` | Page background, primary surface |
| Cloud White | `#f8f8f8` | `--color-cloud-white` | Primary text, headings, list backgrounds, ghost button borders — defining the core readable elements |
| Slate Ink | `#2a2b2d` | `--color-slate-ink` | Muted text elements, icon fills — a subtle step darker than Storm Charcoal for secondary details |
| Subtle Ash | `#757577` | `--color-subtle-ash` | Navigation highlight background, secondary surface layer — a mid-gray for subtle interaction states |

## Tokens — Typography

### Neue Haas Unica — Global text, headings, navigation elements — providing a confident, clear voice with a modernist lean. · `--font-neue-haas-unica`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 700
- **Sizes:** 16px, 18px, 24px, 27px, 36px
- **Line height:** 1.10, 1.25, 1.30, 1.35
- **Letter spacing:** normal
- **Role:** Global text, headings, navigation elements — providing a confident, clear voice with a modernist lean.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.35 | — | `--text-body` |
| body-lg | 18px | 1.3 | — | `--text-body-lg` |
| subheading | 24px | 1.25 | — | `--text-subheading` |
| heading-sm | 27px | 1.25 | — | `--text-heading-sm` |
| heading | 36px | 1.1 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 20px |
| headings | 15px |

### Layout

- **Section gap:** 24px
- **Card padding:** 20px
- **Element gap:** 24px

## Components

### Ghost Navigation Item
**Role:** Navigation

Text labels with Cloud White (#f8f8f8) text, no background, and subtle hover states using Subtle Ash (#757577) for list item background.

### Section Heading
**Role:** Title

Bold text (Neue Haas Unica 700, 36px) in Cloud White (#f8f8f8), often paired with a 15px border radius under the heading text, indicating a conceptual grouping.

### Text Block
**Role:** Content

Standard body text (Neue Haas Unica 400, 16px) in Cloud White (#f8f8f8) for high readability on Storm Charcoal (#222222) backgrounds. Generous vertical spacing of 24px around blocks.

### Hero Title
**Role:** Headline

Large, bold, uppercase text (Neue Haas Unica 700, potentially much larger than 36px, likely filling the screen) in Cloud White (#f8f8f8). The letter-spacing is normal despite its size, contributing to its block-like appearance.

### Pill Navigation Dot
**Role:** Navigation

Small circular (20px radius) navigation dots, possibly appearing as a vertical stack. Inactive dots are Slate Ink (#2a2b2d), active dots are Cloud White (#f8f8f8).

### List Item Card
**Role:** Content Display

List items presented as cards with a Cloud White (#f8f8f8) border and a 20px border radius. Text is in Slate Ink (#2a2b2d) on a Cloud White (#f8f8f8) background.

## Do's and Don'ts

### Do
- Always use Storm Charcoal (#222222) as the primary background for sections and canvases.
- Prioritize Neue Haas Unica 700 for all significant headlines and calls to attention, using Cloud White (#f8f8f8) for maximum contrast.
- Apply 20px border radius to all interactive elements, cards, and list items for a consistent softened aesthetic.
- Maintain a clear visual hierarchy by using Cloud White (#f8f8f8) for primary text and titles, and Slate Ink (#2a2b2d) for secondary details or within light-colored containers.
- Utilize 24px as the default vertical and horizontal element spacing to ensure comfortable readability and distinct content blocks.
- Integrate the 15px border radius token specifically with headings to create a subtle, structured visual break or emphasis.

### Don't
- Avoid using multiple chromatic colors; color should be introduced sparingly and for specific visual impact in imagery.
- Do not use subtle variations of dark gray for backgrounds; maintain the stark contrast between Storm Charcoal (#222222) and Cloud White (#f8f8f8).
- Do not introduce strong shadows or excessive elevation; the design relies on flat surfaces and minimal depth.
- Avoid tight spacing; maintain the generous 24px element and section gaps to prevent visual clutter, especially in text-heavy areas.
- Do not use custom letter-spacing; all text, regardless of size, should use 'normal' tracking for block-like typographic presence.
- Never use rounded corners less than 15px; the design language favors a distinctly soft, rounded feel for all contained elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Storm Charcoal Canvas | `#222222` | Primary page and content background. |
| 1 | Subtle Ash Interface | `#757577` | Secondary surface, used for interactive elements like navigation highlights. |
| 2 | Cloud White Surface | `#f8f8f8` | Elevated content containers, list backgrounds, and areas of high-contrast information display. |

## Agent Prompt Guide

Quick Color Reference:
text: #f8f8f8
background: #222222
border: no distinct border color
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary hero section: use Storm Charcoal (#222222) as the background. Display the headline 'IMAGINE' in Neue Haas Unica 700, Cloud White (#f8f8f8), extremely large (e.g., 120px) and centered. Mask an abstract geometric image (muted red/pink tones) into the bottom-left corner of the hero section. Align a pill navigation dot stack vertically on the right side, using Cloud White (#f8f8f8) for the active dot and Slate Ink (#2a2b2d) for inactive dots.
2. Design a content block for 'Interaction Design Lab Bern—25': use Cloud White (#f8f8f8) text, Neue Haas Unica 400, 16px, line height 1.35. Position this text block with a 24px top margin over a Storm Charcoal (#222222) background.
3. Build a navigation list item: Text 'Kaufen' in Neue Haas Unica 400, 16px, Cloud White (#f8f8f8). The list item itself should have a Subtle Ash (#757577) background on hover, with a 20px border-radius applied to the item.

## Similar Brands

- **AIGA** — Stark type-focused layouts on dark backgrounds with minimal color and bold statements.
- **Are.na** — Focus on content and structure over heavy UI, using a simple dark canvas and high-contrast text.
- **Stripe press releases** — Heavy, confident typography in large sizes, often against a plain background, creating an immediate sense of authority.
- **Future Fonts** — Experimental graphic design with bold typography as a primary visual element, often against dark or neutral backdrops.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-charcoal: #222222;
  --color-cloud-white: #f8f8f8;
  --color-slate-ink: #2a2b2d;
  --color-subtle-ash: #757577;

  /* Typography — Font Families */
  --font-neue-haas-unica: 'Neue Haas Unica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 20px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-default: 20px;
  --radius-headings: 15px;

  /* Surfaces */
  --surface-storm-charcoal-canvas: #222222;
  --surface-subtle-ash-interface: #757577;
  --surface-cloud-white-surface: #f8f8f8;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-charcoal: #222222;
  --color-cloud-white: #f8f8f8;
  --color-slate-ink: #2a2b2d;
  --color-subtle-ash: #757577;

  /* Typography */
  --font-neue-haas-unica: 'Neue Haas Unica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 20px;
}
```
