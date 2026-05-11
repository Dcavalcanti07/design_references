# Integrated Biosciences — Style Reference
> Dark Academia Laboratory: A meticulously organized workbench under a cool, precise spotlight.

**Theme:** mixed

Integrated Bio's design system presents a serious, academic aesthetic with a striking dark canvas and intentionally muted chromatic accents. Typography is the primary visual communicator, featuring a custom sans-serif with generous scaling and tight tracking that commands attention without overpowering. Surfaces are predominantly dark or off-white, acting as clean backdrops for content, with borders serving to define interactive elements or subtle divisions. The overall impression is one of modern scientific rigor, where visual flourish is minimal, and focus remains on data and information.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page backgrounds, footer backgrounds, primary text on light surfaces |
| Carbon | `#222f30` | `--color-carbon` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Fog | `#4d5757` | `--color-fog` | Muted body text, subtle borders |
| Sage Mist | `#c9cbbe` | `--color-sage-mist` | Subtle headlines, decorative borders – imparts a soft, weathered quality to dark backgrounds |
| Cloud Canvas | `#e7e8e1` | `--color-cloud-canvas` | Card backgrounds, secondary surface backgrounds – a slightly warm off-white |
| Light Gray | `#eeeeee` | `--color-light-gray` | Card backgrounds, elevated surface backgrounds – a cool, pale gray for contrast |
| Off-White | `#f7f7f5` | `--color-off-white` | Dominant page background in light sections, hero background – a clean, nearly canvas-like base |
| Polar White | `#ffffff` | `--color-polar-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Bio-Green | `#cef79e` | `--color-bio-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Deep Sea | `#445e5f` | `--color-deep-sea` | Decorative fills, subtle background accents |

## Tokens — Typography

### Aspekta — Headline, body text, navigation — the primary typeface, used across all major text elements. The custom font provides a distinctive, modern-without-being-trendy character. · `--font-aspekta`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 18px, 19px, 22px, 24px, 36px, 42px, 58px, 75px, 89px, 111px, 158px
- **Line height:** 1.00, 1.10, 1.20, 1.30
- **Letter spacing:** -0.001, -0.001, -0.001, -0.006, -0.006, -0.02, -0.02, -0.02, -0.03, -0.03, -0.03, -0.03
- **Role:** Headline, body text, navigation — the primary typeface, used across all major text elements. The custom font provides a distinctive, modern-without-being-trendy character.

### Roboto Mono — Small labels, code snippets, metadata — used sparingly to provide a technical, structured counterpoint to Aspekta. · `--font-roboto-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 13px, 14px, 15px
- **Line height:** 1.00, 1.23
- **Letter spacing:** -0.007, -0.008, -0.02
- **Role:** Small labels, code snippets, metadata — used sparingly to provide a technical, structured counterpoint to Aspekta.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.2 | — | `--text-caption` |
| body-sm | 18px | 1.2 | — | `--text-body-sm` |
| body | 22px | 1.2 | — | `--text-body` |
| body-lg | 24px | 1.2 | — | `--text-body-lg` |
| heading-sm | 42px | 1.2 | — | `--text-heading-sm` |
| heading | 58px | 1.2 | — | `--text-heading` |
| heading-lg | 75px | 1.2 | — | `--text-heading-lg` |
| display-sm | 111px | 1.2 | — | `--text-display-sm` |
| display | 158px | 1.2 | — | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| cards | 40px |
| buttons | 8px |
| default | 8px |

### Layout

- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 8px

## Components

### Navigation Button
**Role:** Outlined Button

Ghost button with an 8px border-radius, 4px padding on all sides, 1px border in Carbon (#222f30) or Polar White (#ffffff), with text in Aspekta weight 400.

### Header Action Button
**Role:** Filled Button

Solid Carbon (#222f30) button with Polar White (#ffffff) text (Aspekta weight 400), 8px border-radius, and 4px padding.

### Primary Action CTA Button (Text-only)
**Role:** Text Button

Text link on dark background, Aspekta weight 400, Polar White (#ffffff) color. Accompanied by a square Bio-Green (#cef79e) arrow icon.

### News Article Card
**Role:** Content Grid Item

A card with Off-White (#f7f7f5) background, 40px border-radius, and 40px internal padding. Content includes small-size Roboto Mono labels and Aspekta headlines, with a 1px Polar White border for definition. Image is full-bleed within the card's width atop the padding.

### Text Input
**Role:** Form Element

An input field with a 1px Polar White (#ffffff) border, 8px border-radius, and generous internal padding (17px left/right, 4px top/bottom).

### Monospace Data Tag
**Role:** Informational Label

Small text elements using Roboto Mono, such as '01 / 02' pagination or 'WHAT WE DO' labels. Text color is Carbon (#222f30) or Polar White (#ffffff), with a subtle rectangular background of Bio-Green (#cef79e) for emphasis.

## Do's and Don'ts

### Do
- Prioritize Aspekta weight 400 for all primary text, adjusting size to establish hierarchy—large headlines (75-158px) use tight tracking (-0.03em), body text (16-19px) uses minimal tracking (-0.001em).
- Employ the Midnight Ink (#000000) or Carbon (#222f30) for dark backgrounds, contrasting with Polar White (#ffffff) for primary text where readability is paramount.
- Use Off-White (#f7f7f5) or Cloud Canvas (#e7e8e1) as secondary backgrounds for content sections and cards in lighter contexts, framed by 1px Polar White (#ffffff) borders.
- Define interactive elements and sections with subtle 1px borders using Carbon (#222f30) or Polar White (#ffffff), or Sage Mist (#c9cbbe) for a softer presence on dark interfaces.
- Apply Bio-Green (#cef79e) sparingly as an accent for functional indicators, small decorative elements, or subtle background highlights, ensuring it acts as a precise punctuation mark.
- Maintain a comfortable density with 40px section gaps and card padding, with smaller 8px element gaps for details, creating clear content separation.
- Ensure all buttons and navigational elements utilize an 8px border-radius, while cards and larger containers feature a more generous 40px radius, providing a distinct shape language.

### Don't
- Avoid generic drop shadows or heavy elevation; surface differentiation primarily occurs through background color changes (#f7f7f5, #e7e8e1, #eeeeee) and subtle borders.
- Do not introduce additional vibrant colors; adhere strictly to the established Bio-Green (#cef79e) and Deep Sea (#445e5f) accents for chromatic emphasis.
- Refrain from using excessively open letter-spacing for headlines or body text; the system relies on a tightly tracked, confident typographic voice.
- Do not neglect the 1px border for interactive elements; it is crucial for defining clickable areas and maintaining the system's precise aesthetic.
- Avoid using Bio-Green (#cef79e) as a primary action background; it functions as an accent, not a call-to-action fill.
- Do not use high-fidelity, busy photography; prefer scientific or abstract imagery that complements the academic tone, or product-focused clean graphics.
- Avoid dense, unbroken blocks of text; break content into digestible sections with clear headings and sufficient inter-element spacing.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Base | `#000000` | Primary page background, especially in hero sections and immersive experiences. |
| 1 | Off-White Canvas | `#f7f7f5` | Dominant background for content sections in light mode, primary light canvas. |
| 2 | Cloud Card | `#e7e8e1` | Background for secondary content cards or containers, offering a warm subtle contrast to Off-White. |
| 3 | Light Gray Card | `#eeeeee` | Background for additional content cards, providing a cooler, more neutral variation. |

## Imagery

This system primarily uses scientific and abstract imagery. Visuals are typically product-focused or show magnified biological structures, often with internal glow effects or stylized connections. Photography is minimal, if present, and tends to be clinical or abstract rather than lifestyle. Illustrations are geometric and clean, often outlined or using filled shapes that hint at molecular or data structures. Icons are minimal, outlined, and monochromatic, usually in Polar White on dark backgrounds or Carbon on light. Imagery serves to explain complex concepts or showcase scientific processes, rather than purely decorative purposes. Density is moderate, with images often contained within cards or as full-width elements in alternating sections.

## Layout

The page primarily uses a full-bleed layout, allowing sections to fill the viewport width. The hero section features a dark background with a large, centered headline and a secondary text block at the bottom left. Content sections alternate between dark and light backgrounds, creating a clear vertical rhythm. Inner content is often constrained, with text-heavy sections using a single column or a broad central column for readability. Card grids, like the 'Newsroom' section, use a multi-column layout with generous spacing. Navigation is a simple top bar, with elements flushed to the right, maintaining a minimal and unobtrusive presence.

## Agent Prompt Guide

Quick Color Reference:
text: #222f30 (on light), #ffffff (on dark)
background: #000000 (dark mode), #f7f7f5 (light mode)
border: #222f30 (dark interactive), #ffffff (light interactive)
accent: #cef79e
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a 'What We Do' section with an Off-White (#f7f7f5) background. Include a title at 58px Aspekta weight 400, Carbon (#222f30), letter-spacing -0.02em. Below, add a Monospace Data Tag: 'WHAT WE DO' in Roboto Mono weight 400, 14px, Carbon (#222f30), with a Bio-Green (#cef79e) rectangular background.
3. Create a News Article Card on a Light Gray (#eeeeee) background with a 40px border-radius. Inside, use 40px padding. Place a small label, 'Publications', at 13px Roboto Mono weight 400, Carbon (#222f30). Below, a headline at 42px Aspekta weight 400, Carbon (#222f30), letter-spacing -0.02em. The card will contain a full-width image and a 'Read Article' link.

## Similar Brands

- **Stripe** — Similar approach to clean, modern typography and a focus on precise UI elements over decorative visuals, though Stripe uses a lighter palette.
- **Linear** — Dark-themed UI with strong typographic hierarchy, subtle borders for defining interactive areas, and minimal use of color accents for functionality.
- **Vercel** — Emphasis on dark mode, clear information architecture, and a 'developer-tool' aesthetic with precise borders and functional, non-distracting colors.
- **Figma** — Structured interface, strong use of a custom sans-serif font for brand identity, and systematic application of neutral colors with controlled accent hues.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-carbon: #222f30;
  --color-fog: #4d5757;
  --color-sage-mist: #c9cbbe;
  --color-cloud-canvas: #e7e8e1;
  --color-light-gray: #eeeeee;
  --color-off-white: #f7f7f5;
  --color-polar-white: #ffffff;
  --color-bio-green: #cef79e;
  --color-deep-sea: #445e5f;

  /* Typography — Font Families */
  --font-aspekta: 'Aspekta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 18px;
  --leading-body-sm: 1.2;
  --text-body: 22px;
  --leading-body: 1.2;
  --text-body-lg: 24px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 42px;
  --leading-heading-sm: 1.2;
  --text-heading: 58px;
  --leading-heading: 1.2;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 111px;
  --leading-display-sm: 1.2;
  --text-display: 158px;
  --leading-display: 1.2;

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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-cards: 40px;
  --radius-buttons: 8px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-midnight-base: #000000;
  --surface-off-white-canvas: #f7f7f5;
  --surface-cloud-card: #e7e8e1;
  --surface-light-gray-card: #eeeeee;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-carbon: #222f30;
  --color-fog: #4d5757;
  --color-sage-mist: #c9cbbe;
  --color-cloud-canvas: #e7e8e1;
  --color-light-gray: #eeeeee;
  --color-off-white: #f7f7f5;
  --color-polar-white: #ffffff;
  --color-bio-green: #cef79e;
  --color-deep-sea: #445e5f;

  /* Typography */
  --font-aspekta: 'Aspekta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 18px;
  --leading-body-sm: 1.2;
  --text-body: 22px;
  --leading-body: 1.2;
  --text-body-lg: 24px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 42px;
  --leading-heading-sm: 1.2;
  --text-heading: 58px;
  --leading-heading: 1.2;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 111px;
  --leading-display-sm: 1.2;
  --text-display: 158px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;
}
```
