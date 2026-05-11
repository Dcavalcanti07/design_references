# Jp — Style Reference
> monochrome digital canvas, precisely framed

**Theme:** light

This system conveys a precise and product-focused atmosphere, grounded in a stark achromatic palette. The interplay of near-white backgrounds with dark grayscale text and interactive elements creates a clean, high-contrast visual hierarchy. Rounded corners on interactive elements (100px) soften the otherwise sharp 12px corners of content areas, suggesting approachability within a structured framework. Vivid blue accents are reserved for badges, acting as rare, focused indicators.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button backgrounds, text on dark backgrounds. Gives a clean, expansive feeling. |
| Carbon Black | `#202020` | `--color-carbon-black` | Primary heading text, button backgrounds for prominent actions. Provides strong visual impact and contrast. |
| Graphite | `#333333` | `--color-graphite` | Body text, link text, icons. Ensures high readability on light backgrounds. |
| Stone Gray | `#555555` | `--color-stone-gray` | Text for secondary information, button text on white backgrounds. Provides a softer contrast than Graphite. |
| Silver Lining | `#e6e6e6` | `--color-silver-lining` | Button borders, subtle dividers. Defines boundaries without harshness. |
| Zinc | `#838383` | `--color-zinc` | Support text, secondary body copy. Slightly lighter than Stone Gray for less emphasis. |
| Sky Blue | `#4177ff` | `--color-sky-blue` | Informational badges, occasional accents. A single, distinct vibrant color for highlights. |
| Ocean Blue | `#41a9ff` | `--color-ocean-blue` | Alternative accent for badges. Slightly lighter shade of Sky Blue, used for variety. |

## Tokens — Typography

### Ppneuemontreal — Primary typeface for all UI elements, headings, and body text. The consistent letter-spacing across weights and sizes provides a tight, structured feel characteristic of digital interfaces. · `--font-ppneuemontreal`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 16px, 18px, 38px
- **Line height:** 1.00, 1.11, 1.20, 1.40, 1.43, 1.60
- **Letter spacing:** 0.02em
- **Role:** Primary typeface for all UI elements, headings, and body text. The consistent letter-spacing across weights and sizes provides a tight, structured feel characteristic of digital interfaces.

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 100px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.45) 0px 5px 5px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 0px
- **Element gap:** 4-18px

## Components

### Primary Action Button
**Role:** Main call to action

Carbon Black (#202020) background, Canvas White (#ffffff) text, 100px border radius, 12px vertical padding, 26px horizontal padding. Prominent and high contrast.

### Secondary Outline Button
**Role:** Navigation, filtering

Transparent background, Stone Gray (#555555) text and border, 100px border radius, 14px vertical padding, 24px horizontal padding. Subtle but clearly interactive.

### Selection Toggle Button
**Role:** Category selection (e.g., 'All', 'Exclusive')

Canvas White (#ffffff) background, Graphite (#3b3b3b) text, Silver Lining (#e6e6e6) border, 100px border radius, 8px padding. Used for group selection with clear active state.

### Informational Badge - Sky Blue
**Role:** Categorization, status indicators

Sky Blue (#4177ff) background, Graphite (#333333) text, 100px border radius, 0px padding. Provides a clear, non-intrusive label.

### Informational Badge - Canvas White
**Role:** Categorization, status indicators

Canvas White (#ffffff) background, Graphite (#333333) text, 100px border radius, 0px padding. A neutral option for less emphasis.

## Do's and Don'ts

### Do
- Prioritize Graphite (#333333) for body text on Canvas White (#ffffff) backgrounds to maintain AAA contrast.
- Use 100px border radius for all interactive elements like buttons and badges to signal affordance and approachability.
- Reserve Carbon Black (#202020) for dominant headlines and primary call-to-action button backgrounds.
- Apply Spacings of 8px, 10px, 12px, 14px, 18px to maintain a compact, structured layout, particularly around interactive elements.
- Utilize Ppneuemontreal at 0.02em letter-spacing consistently across all sizes and weights to maintain a crisp, digital aesthetic.

### Don't
- Avoid using multiple chromatic colors; Sky Blue (#4177ff) and Ocean Blue (#41a9ff) are the only allowed accents.
- Do not introduce sharp corners on interactive buttons or badges; maintain '100px' radius for these elements.
- Do not use dark backgrounds for large text blocks, as the system favors a light base with dark text.
- Avoid excessive line heights; the tight line height values (e.g., 1.0, 1.11, 1.2) should be maintained for a dense, composed feel.
- Refrain from using strong box shadows on general UI elements; the system relies on flat design with subtle borders for separation.

## Imagery

The site heavily features product screenshots (template previews) presented within Canvas White (#ffffff) frames with 12px rounded corners. These previews are tightly cropped and often showcase digital interfaces or abstract graphic compositions. There is no lifestyle photography; the focus is entirely on the digital product itself, treated as an object of design. Illustrations, if present, are minimal and likely integrated within the templates themselves, not as separate decorative elements of the site. Icons are outlined, simple, and monochrome, complementing the clean UI. The overall density of imagery is high, with a large grid of template cards dominating the layout, making it visually rich despite the lack of complex decorative graphics.

## Layout

The page uses a `max-width` contained model for its primary content, centered on a Canvas White background. The hero section features a centered headline and subtext, followed by a centrally aligned action button. Below the hero, a prominent filter bar with segmented toggle buttons suggests content organization. The main content area is a dense, responsive grid of template preview cards, which appear to use a 3-column layout at desktop sizes. Sections are clearly delineated by the content within, rather than strong visual separators or alternating background colors. The layout is compact, prioritizing information density without feeling cramped, with consistent vertical spacing between sections and elements.

## Type Scale

**role:** caption
**size:** 10
**lineHeight:** 1.4
**letterSpacing:** 0.02

**role:** body-sm
**size:** 11
**lineHeight:** 1.4
**letterSpacing:** 0.02

**role:** body
**size:** 12
**lineHeight:** 1.4
**letterSpacing:** 0.02

**role:** subheading
**size:** 14
**lineHeight:** 1.4
**letterSpacing:** 0.02

**role:** heading
**size:** 18
**lineHeight:** 1.11
**letterSpacing:** 0.02

**role:** display
**size:** 38
**lineHeight:** 1
**letterSpacing:** 0.02

## Agent Prompt Guide

**Quick Color Reference:** Text: #333333, Background: #ffffff, CTA: #202020, Border: #e6e6e6, Accent: #4177ff

**Example Component Prompt 1: Primary Action Button**
Create a button: background #202020, text #ffffff, border-radius 100px, padding 12px 26px, font 'Ppneuemontreal' weight 500, letter-spacing 0.02em.

**Example Component Prompt 2: Secondary Outline Button**
Create a button: background transparent, text #555555, border 1px solid #555555, border-radius 100px, padding 14px 24px, font 'Ppneuemontreal' weight 400, letter-spacing 0.02em.

**Example Component Prompt 3: Template Preview Card**
Create a card: background #ffffff, border-radius 12px, box-shadow none, padding 0px. Inside, place an image that fills the card, maintaining the 12px corner radius.

**Example Component Prompt 4: Informational Badge - Sky Blue**
Create a badge: background #4177ff, text #333333, border-radius 100px, font 'Ppneuemontreal' weight 400, letter-spacing 0.02em, 0px padding around content (text content such as 'Exclusive').

## Similar Brands

- **Framer** — Shares a clean, high-contrast black-and-white aesthetic with minimal, vibrant spot colors and focus on digital product display.
- **Superlist** — Employs an achromatic color palette for UI, emphasizing functionality and content with minimal decorative elements.
- **Linear** — Known for a precise, digital-first UI with tight typography, high contrast, and a restrained use of vibrant accent colors.
- **Raycast** — Features a dark/light mode with sharp, functional typography and a focus on displaying software interfaces crisply, similar to the template cards.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-carbon-black: #202020;
  --color-graphite: #333333;
  --color-stone-gray: #555555;
  --color-silver-lining: #e6e6e6;
  --color-zinc: #838383;
  --color-sky-blue: #4177ff;
  --color-ocean-blue: #41a9ff;

  /* Typography — Font Families */
  --font-ppneuemontreal: 'Ppneuemontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.6;
  --text-xs-2: 11px;
  --leading-xs-2: 1.4;
  --text-xs-3: 12px;
  --leading-xs-3: 1.4;
  --text-sm: 13px;
  --leading-sm: 1;
  --text-sm-2: 14px;
  --leading-sm-2: 1.43;
  --text-base: 16px;
  --leading-base: 1.4;
  --text-lg: 18px;
  --leading-lg: 1.11;
  --text-4xl: 38px;
  --leading-4xl: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 0px;
  --element-gap: 4-18px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 100px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.45) 0px 5px 5px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-carbon-black: #202020;
  --color-graphite: #333333;
  --color-stone-gray: #555555;
  --color-silver-lining: #e6e6e6;
  --color-zinc: #838383;
  --color-sky-blue: #4177ff;
  --color-ocean-blue: #41a9ff;

  /* Typography */
  --font-ppneuemontreal: 'Ppneuemontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1.6;
  --text-xs-2: 11px;
  --leading-xs-2: 1.4;
  --text-xs-3: 12px;
  --leading-xs-3: 1.4;
  --text-sm: 13px;
  --leading-sm: 1;
  --text-sm-2: 14px;
  --leading-sm-2: 1.43;
  --text-base: 16px;
  --leading-base: 1.4;
  --text-lg: 18px;
  --leading-lg: 1.11;
  --text-4xl: 38px;
  --leading-4xl: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.45) 0px 5px 5px 0px;
}
```
