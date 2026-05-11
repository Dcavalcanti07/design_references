# Motto® — Style Reference
> Architectural Blueprint on White Canvas. Black lines and precise typography articulate structure and ideas against an expansive, bright background.

**Theme:** light

The Motto® design system evokes an atmosphere of rigorous clarity and understated authority. Its visual language relies on stark contrasts between crisp black text and an expansive canvas of near-white, creating a sophisticated and professional impression. The dominance of bold, custom san-serif typography, particularly the expansive display font, dictates the site's strong visual rhythm. A distinct lack of ornamentation, shadows, or vibrant color accents streamlines the user experience to focus purely on content and impactful messaging.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, essential icons, borders, interactive states for text links, navigation items, and button outlines. It grounds the design in high contrast and definitive presence. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text, and filled button text for contrast. Defines the vast, airy negative space. |
| Charcoal Surface | `#1b1b1c` | `--color-charcoal-surface` | Solid button fills for primary calls to action. Provides a rich, deep counterpoint to Canvas White without introducing color. |
| Cloud Gray | `#f2f2f2` | `--color-cloud-gray` | Subtle background for hero sections or alternating content blocks, offering a slight visual break from pure Canvas White without significant tonal shift. |
| Stone Accent | `#d8d8d8` | `--color-stone-accent` | Divider lines, subtle borders, and background accents, providing minimal separation. |
| Ash Text | `#4d5153` | `--color-ash-text` | Secondary body text and subtle link colors, used for less prominent information or tertiary content. |
| Silver Text | `#848484` | `--color-silver-text` | Lighter body text for lists or less emphasized links, contributing to the grayscale palette. |
| Input Border | `#c8cacd` | `--color-input-border` | Border color for input fields, indicating interactive areas with a fine, light line. |
| Faint Gray | `#717476` | `--color-faint-gray` | Tertiary body text, used for footnotes or less critical content where readability is still important but emphasis is lower. |
| Vivid Purple | `#9c98ef` | `--color-vivid-purple` | Rare, decorative background graphic elements; not part of the primary UI palette. |
| Electric Violet | `#6980ff` | `--color-electric-violet` | Rare, decorative background graphic elements; not part of the primary UI palette. |
| Grass Green | `#beee98` | `--color-grass-green` | Rare, decorative background graphic elements; not part of the primary UI palette. |

## Tokens — Typography

### sans — UI elements, body text, subheadings, and captions. The consistent medium weight (500) across various sizes provides a clean, readable, and authoritative voice for all functional text. · `--font-sans`
- **Substitute:** Inter, Arial, Helvetica, sans-serif
- **Weights:** 500
- **Sizes:** 14px, 15px, 17px, 18px, 20px, 25px, 34px, 48px
- **Line height:** 1.14, 1.26, 1.30, 1.38, 1.40, 1.60
- **Letter spacing:** normal
- **Role:** UI elements, body text, subheadings, and captions. The consistent medium weight (500) across various sizes provides a clean, readable, and authoritative voice for all functional text.

### disp — Headlines and display text. Its large scale and medium weight dictate a commanding visual presence, allowing key messages to dominate without being overtly aggressive. · `--font-disp`
- **Substitute:** Oswald, Impact, sans-serif
- **Weights:** 500
- **Sizes:** 61px, 99px, 138px, 139px, 154px
- **Line height:** 1.00, 1.10
- **Letter spacing:** normal
- **Role:** Headlines and display text. Its large scale and medium weight dictate a commanding visual presence, allowing key messages to dominate without being overtly aggressive.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | — | `--text-caption` |
| body | 17px | 1.38 | — | `--text-body` |
| subheading | 25px | 1.14 | — | `--text-subheading` |
| heading-sm | 34px | 1.14 | — | `--text-heading-sm` |
| heading | 48px | 1.14 | — | `--text-heading` |
| heading-lg | 61px | 1.1 | — | `--text-heading-lg` |
| display-sm | 99px | 1 | — | `--text-display-sm` |
| display | 154px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 21 | 21px | `--spacing-21` |
| 23 | 23px | `--spacing-23` |
| 24 | 24px | `--spacing-24` |
| 29 | 29px | `--spacing-29` |
| 38 | 38px | `--spacing-38` |
| 48 | 48px | `--spacing-48` |
| 58 | 58px | `--spacing-58` |
| 67 | 67px | `--spacing-67` |
| 70 | 70px | `--spacing-70` |
| 77 | 77px | `--spacing-77` |
| 96 | 96px | `--spacing-96` |
| 158 | 158px | `--spacing-158` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 9999px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px

## Components

### Navigation Link
**Role:** Standard interactive navigation item

Text link with default color Pitch Black (#000000), no background, no border, and 0px padding. Uses 'sans' font family at various sizes with weight 500. Active states are not explicitly styled but follow the black text over white canvas principle.

### Ghost Button (Text)
**Role:** Secondary action or informational link styled as a button

Transparent background, Pitch Black (#000000) text and border. 0px padding, 0px border-radius. Uses 'sans' font family.

### Ghost Button (White Text)
**Role:** Secondary action on a dark background

Transparent background, Canvas White (#ffffff) text and border. 0px padding, 0px border-radius. Uses 'sans' font family.

### Filled Button (Pill, Medium)
**Role:** Primary Call to Action

Charcoal Surface (#1b1b1c) background, Canvas White (#ffffff) text. 9999px border-radius, 0px vertical padding, 28.8px horizontal padding. Uses 'sans' font family.

### Ghost Button (Pill, Icon-only)
**Role:** Iconic secondary action

Transparent background, Canvas White (#ffffff) text/icon, Canvas White (#ffffff) border. 9999px border-radius, 15.36px padding on all sides. Uses 'sans' font family.

### Info Card (No Border/Shadow)
**Role:** Neutral content container

Transparent background, 0px border-radius, no box shadow. No intrinsic padding, content padding applied internally. Used for testimonials or feature blocks.

### Text Input (Underlined)
**Role:** User data entry field

Transparent background, Canvas White (#ffffff) text. Input Border (#c8cacd) bottom border. 0px border-radius, 24px top/bottom padding, 48px right padding. Uses 'sans' font family.

## Do's and Don'ts

### Do
- Prioritize high contrast between text (Pitch Black #000000) and background (Canvas White #ffffff or Cloud Gray #f2f2f2) for legibility.
- Use 'disp' font (weight 500) exclusively for large, impactful headlines (61px to 154px) to establish a clear hierarchy and brand voice.
- Maintain a sense of generous whitespace; sections should breathe with sectionGap of 48px and elementGap varying from 8px to 70px.
- Apply 9999px border-radius only to interactive buttons and similar atomic elements like tags, creating distinct 'pill' shapes.
- All non-interactive content containers (cards, content blocks) should have 0px border-radius, reinforcing a sharp, clean aesthetic.
- Use Charcoal Surface (#1b1b1c) for primary button fills to provide a strong visual anchor without introducing chromatic color.

### Don't
- Avoid using drop shadows or heavy gradients; the elevation philosophy is based on content hierarchy and spatial separation, not artificial depth.
- Do not introduce color to UI elements or text beyond the defined neutral palette for brand and accent; chromatic colors are strictly decorative.
- Do not deviate from the 'sans' font family (weight 500) for body text, links, and navigation; avoid mixing font weights that are not explicitly defined.
- Never use rounded corners on cards, content sections, or layout blocks; maintain sharp, angular forms.
- Do not use subtle variations in gray tones for text that reduce contrast below AAA accessibility levels; stick to defined text colors like Pitch Black, Ash Text, or Silver Text.
- Avoid decorative imagery that competes with the bold typography; stick to abstract, monochromatic, or product-focused visuals if present.

## Imagery

The visual language is characterized by an absence of traditional imagery in the main UI areas. Photography is not present. Instead, the focus is on a stark, text-dominant interface, occasionally featuring abstract graphic elements like the asterisk or arrow. When present, graphics are inline and monochromatic (Pitch Black on Canvas White), functional rather than decorative, serving to guide or symbolize concepts. The visual weight is carried almost entirely by typography.

## Layout

The site employs a max-width contained layout, centered on a Canvas White background, creating a stable and focused content area. The hero section is full-width with a dramatic, oversized headline ('disp' font) vertically centered, setting an immediate tone of prominence. Sections maintain consistent vertical spacing, often with a large sectionGap of 48px, leading to a spacious feel. Content is primarily arranged in single-column stacks or simple two-column layouts for text alongside conceptual elements. There is no grid visible for cards or features; content blocks are isolated entities, emphasizing individual messages. The navigation is a persistent top bar, sticky or otherwise always available, maintaining minimal branding and focusing on key links.

## Agent Prompt Guide

### Quick Color Reference
- Text (Pitch Black): #000000
- Background (Canvas White): #ffffff
- Primary Button (Charcoal Surface): #1b1b1c
- Button Text (Canvas White): #ffffff
- Secondary Text (Ash Text): #4d5153
- Subtle BG (Cloud Gray): #f2f2f2

### Example Component Prompts
1. Create a hero section: Canvas White (#ffffff) background. Headline 'Ideas Worth Rallying Around' using 'disp' font, weight 500, size 139px, line-height 1, in Pitch Black (#000000). Subtext 'Motto® is a strategic branding agency...' using 'sans' font, weight 500, size 17px, line-height 1.38, in Pitch Black (#000000). Add a large down arrow graphic (Pitch Black) below the subtext. Ensure generous vertical spacing.
2. "Create a primary call-to-action button: 'Work with us' text, Charcoal Surface (#1b1b1c) background, Canvas White (#ffffff) text. Use 'sans' font, weight 500. Set border-radius to 9999px. Add 0px vertical padding and 28.8px horizontal padding."
3. "Generate a testimonial card grid with two cards: Each card has a Canvas White (#ffffff) background, 0px border-radius, and no box-shadow. Inside, include a headline 'PRAISE FROM CLIENTS' in 'disp' font (size depends on context, but bold), and a body text quote in 'sans' font, weight 500, size 17px, line-height 1.38, in Pitch Black (#000000). Separate cards with a generous element gap. Card content should be left-aligned."
4. "Design a footer section: Background is likely Canvas White (#ffffff). Include navigation links (Pitch Black #000000 text, 'sans' font, weight 500, size 15px) and copyright information (Ash Text #4d5153, 'sans' font, weight 500, size 14px). Ensure ample padding and element gaps, consistent with the spacious theme."

## Similar Brands

- **Linear** — Shares a high-contrast, text-heavy UI with minimal color and bold typographic presence, prioritizing clarity and function over visual embellishment.
- **Stripe (early branding)** — Employs strong, clean typography as a primary design element, with a preference for monochrome palettes and ample whitespace to convey sophistication.
- **Anthropic** — Features a stark, architectural aesthetic with a strong emphasis on large, commanding type and a near-absence of visual decoration, creating an impression of intellectual rigor.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-canvas-white: #ffffff;
  --color-charcoal-surface: #1b1b1c;
  --color-cloud-gray: #f2f2f2;
  --color-stone-accent: #d8d8d8;
  --color-ash-text: #4d5153;
  --color-silver-text: #848484;
  --color-input-border: #c8cacd;
  --color-faint-gray: #717476;
  --color-vivid-purple: #9c98ef;
  --color-electric-violet: #6980ff;
  --color-grass-green: #beee98;

  /* Typography — Font Families */
  --font-sans: 'sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-disp: 'disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body: 17px;
  --leading-body: 1.38;
  --text-subheading: 25px;
  --leading-subheading: 1.14;
  --text-heading-sm: 34px;
  --leading-heading-sm: 1.14;
  --text-heading: 48px;
  --leading-heading: 1.14;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 99px;
  --leading-display-sm: 1;
  --text-display: 154px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-21: 21px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-29: 29px;
  --spacing-38: 38px;
  --spacing-48: 48px;
  --spacing-58: 58px;
  --spacing-67: 67px;
  --spacing-70: 70px;
  --spacing-77: 77px;
  --spacing-96: 96px;
  --spacing-158: 158px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;

  /* Border Radius */
  --radius-lg: 8.64px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-canvas-white: #ffffff;
  --color-charcoal-surface: #1b1b1c;
  --color-cloud-gray: #f2f2f2;
  --color-stone-accent: #d8d8d8;
  --color-ash-text: #4d5153;
  --color-silver-text: #848484;
  --color-input-border: #c8cacd;
  --color-faint-gray: #717476;
  --color-vivid-purple: #9c98ef;
  --color-electric-violet: #6980ff;
  --color-grass-green: #beee98;

  /* Typography */
  --font-sans: 'sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-disp: 'disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body: 17px;
  --leading-body: 1.38;
  --text-subheading: 25px;
  --leading-subheading: 1.14;
  --text-heading-sm: 34px;
  --leading-heading-sm: 1.14;
  --text-heading: 48px;
  --leading-heading: 1.14;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 99px;
  --leading-display-sm: 1;
  --text-display: 154px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-21: 21px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-29: 29px;
  --spacing-38: 38px;
  --spacing-48: 48px;
  --spacing-58: 58px;
  --spacing-67: 67px;
  --spacing-70: 70px;
  --spacing-77: 77px;
  --spacing-96: 96px;
  --spacing-158: 158px;

  /* Border Radius */
  --radius-lg: 8.64px;
  --radius-full: 9999px;
}
```
