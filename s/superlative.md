# Superlative — Style Reference
> Precision instrument interface—white text glowing on a matte gray panel.

**Theme:** dark

Superlative employs a dark, high-contrast aesthetic that feels like a precision instrument's interface—sharp, functional, and minimal. White and various shades of dark gray define the palette, highlighted by a stark orange accent used for critical indicators. Typography is condensed and uppercase, contributing to a technical, almost industrial feel. Components are stripped down: ghost buttons with thin borders and minimal padding, and tight, disciplined spacing create a sense of focused control.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Superlative Black | `#141414` | `--color-superlative-black` | Primary surface background, text color for light surfaces, prominent borders |
| Instrument Gray | `#232323` | `--color-instrument-gray` | Secondary surface backgrounds, muted text on very dark surfaces, darker borders |
| Panel Gray | `#8c8c8c` | `--color-panel-gray` | Placeholder text, subtle borders, inactive link text, secondary headings |
| Signal Orange | `#e66f27` | `--color-signal-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text on dark backgrounds, ghost button text, active link text |
| Surface White | `#f6f4f2` | `--color-surface-white` | Badge backgrounds, specific content sections when a lighter contrast is needed |
| Divider Gray | `#e4e3e2` | `--color-divider-gray` | Subtle borders and dividers on lighter surfaces |
| Absolute Black | `#000000` | `--color-absolute-black` | Outline button borders, selected text on light backgrounds |

## Tokens — Typography

### SL-Regular-Condensed — Primary display font for headings and calls to action. The wide letter spacing and condensed form create a mechanical, precise feel. · `--font-sl-regular-condensed`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 15px, 23px, 90px
- **Line height:** 1.00, 1.33
- **Letter spacing:** 0.0800em
- **Role:** Primary display font for headings and calls to action. The wide letter spacing and condensed form create a mechanical, precise feel.

### SL-Light — Secondary display font for larger headings, providing legibility at scale while maintaining a lean profile. · `--font-sl-light`
- **Substitute:** Open Sans Light
- **Weights:** 400
- **Sizes:** 25px, 90px
- **Line height:** 1.00, 1.20
- **Letter spacing:** normal
- **Role:** Secondary display font for larger headings, providing legibility at scale while maintaining a lean profile.

### SL-Regular — Body text, navigation links, and smaller UI labels. Its regular width balances the condensed display fonts. · `--font-sl-regular`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Body text, navigation links, and smaller UI labels. Its regular width balances the condensed display fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 15px | 1 | 0.08px | `--text-body` |
| subheading | 23px | 1.33 | 0.08px | `--text-subheading` |
| heading | 25px | 1 | — | `--text-heading` |
| display | 90px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 11 | 11px | `--spacing-11` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 45 | 45px | `--spacing-45` |
| 60 | 60px | `--spacing-60` |
| 90 | 90px | `--spacing-90` |
| 120 | 120px | `--spacing-120` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 15px |
| buttons | 3px |

### Layout

- **Section gap:** 60px
- **Card padding:** 30px
- **Element gap:** 15px

## Components

### Ghost Primary Button
**Role:** Main call to action, outlining key interactive elements.

Text: Ghost White (#ffffff), size 25px SL-Light, weight 400, normal letter-spacing. Border: 1px solid Absolute Black (#000000). Background: transparent. Padding: 18.5px vertical, 45px horizontal. Radius: 0px.

### Ghost Secondary Button
**Role:** Secondary calls to action, maintaining visual weight with interaction.

Text: Panel Gray (#8c8c8c), size 15px SL-Regular-Condensed, weight 400, letter-spacing 0.0800em. Border: 1px solid Panel Gray (#8c8c8c). Background: transparent. Padding: 18.5px vertical, 45px horizontal. Radius: 0px.

### Input Field
**Role:** User input areas for forms.

Placeholder Text: Panel Gray (#8c8c8c). Border: 1px solid Panel Gray (#8c8c8c). Background: transparent. No padding is explicitly defined in variants, implying content-based sizing.

### New Badge
**Role:** Highlighting new features or products.

Background: Surface White (#f6f4f2). Text: Superlative Black (#141414), size 15px SL-Regular-Condensed, weight 400. Padding: 0px vertical, 15px horizontal. Radius: 15px.

## Do's and Don'ts

### Do
- Use Superlative Black (#141414) as the default background for most sections.
- Employ Ghost White (#ffffff) text for primary content on dark backgrounds.
- Borders for interactive components should be 1px solid using Superlative Black (#000000) or Panel Gray (#8c8c8c).
- Apply Signal Orange (#e66f27) sparingly, strictly for functional highlights and indicators, not for primary actions.
- Maintain a tight layout with an element gap of 15px for most UI elements.
- Utilize SL-Regular-Condensed with 0.0800em letter-spacing for all headlines and button text.
- Apply a 15px border radius to badges and a 3px radius to outlined buttons, with 0px for Ghost Buttons.

### Don't
- Avoid using Signal Orange (#e66f27) for actionable button backgrounds or primary calls to action.
- Do not introduce heavy shadows or excessive elevation; maintain a generally flat and minimalist appearance.
- Refrain from using color gradients, as the system relies on solid colors and strong contrast.
- Never use serif fonts; stick to the sans-serif SL typefaces for a consistent technical aesthetic.
- Do not deviate from the specified tight letter-spacing for condensed fonts or normal spacing for regular fonts.
- Avoid complex or ornamental visual elements; simplicity and utility are paramount.
- Do not use large, soft paddings; maintain compact and disciplined spacing around components.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Superlative Black Canvas | `#141414` | Dominant page background, providing a dark, immersive base for content. |
| 1 | Instrument Gray Panel | `#232323` | Used for background of content blocks within the main canvas, offering slight visual separation. |
| 2 | Surface White | `#f6f4f2` | Reserved for occasional use as a contrasting content block background, such as specific badges or info cards. |

## Imagery

This system features prominent, angled product photography of electronic musical instruments, often filling the background without explicit framing. Imagery is focused on the product itself, showcasing its controls and details rather than lifestyle contexts, emphasizing the technical nature of the brand. There are no illustrations; the visual language is strictly photographic or iconographic. Icons are minimal, outlined, and monochromatic, aligning with the precision instrument aesthetic. Imagery serves as atmospheric branding and product showcase, dominating visual space while overlaid with text.

## Layout

The page uses a full-bleed layout for its hero section, with primary content layered over a large product image. Subsequent sections maintain this dark, full-width canvas. Content is often centered and stacked, or uses implicit grid-like arrangements where text overlays parts of the background imagery. There isn't a strict max-width container, allowing for immersive full-bleed imagery, but internal text blocks respect generous margins. Vertical rhythm is established through consistent section gaps of 60px. Navigation is minimal, located at the top-left and top-right corners, rather than a heavy header.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #141414
border: #000000
accent: #e66f27
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a feature callout: Instrument Gray Panel (#232323) background. Title 'The Sound of the Past' at 25px SL-Light weight 400, Ghost White (#ffffff), normal letter-spacing. Subtext 'Crafted for the Future' at 15px SL-Regular weight 400, Ghost White (#ffffff), normal letter-spacing.
3. Create a navigation link: Text 'PRODUCT' in Panel Gray (#8c8c8c), 15px SL-Light weight 400, normal letter-spacing. On hover, change text to Ghost White (#ffffff).
4. Create a 'New' badge: Background Surface White (#f6f4f2), text 'NEW' in Superlative Black (#141414), 15px SL-Regular-Condensed weight 400, letter-spacing 0.0800em. Radius 15px, 0px vertical padding, 15px horizontal padding.

## Similar Brands

- **Teenage Engineering** — Shares a technical, minimalist product aesthetic with strong typography and high-contrast dark interfaces.
- **Arturia** — Similar focus on electronic musical instruments, often featuring dark interfaces with precise controls and clear, functional typography.
- **Native Instruments** — Employs dark modes, structured layouts, and an emphasis on technical clarity in product presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-superlative-black: #141414;
  --color-instrument-gray: #232323;
  --color-panel-gray: #8c8c8c;
  --color-signal-orange: #e66f27;
  --color-ghost-white: #ffffff;
  --color-surface-white: #f6f4f2;
  --color-divider-gray: #e4e3e2;
  --color-absolute-black: #000000;

  /* Typography — Font Families */
  --font-sl-regular-condensed: 'SL-Regular-Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sl-light: 'SL-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sl-regular: 'SL-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1;
  --tracking-body: 0.08px;
  --text-subheading: 23px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.08px;
  --text-heading: 25px;
  --leading-heading: 1;
  --text-display: 90px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 30px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 15px;

  /* Named Radii */
  --radius-badges: 15px;
  --radius-buttons: 3px;

  /* Surfaces */
  --surface-superlative-black-canvas: #141414;
  --surface-instrument-gray-panel: #232323;
  --surface-surface-white: #f6f4f2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-superlative-black: #141414;
  --color-instrument-gray: #232323;
  --color-panel-gray: #8c8c8c;
  --color-signal-orange: #e66f27;
  --color-ghost-white: #ffffff;
  --color-surface-white: #f6f4f2;
  --color-divider-gray: #e4e3e2;
  --color-absolute-black: #000000;

  /* Typography */
  --font-sl-regular-condensed: 'SL-Regular-Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sl-light: 'SL-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sl-regular: 'SL-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1;
  --tracking-body: 0.08px;
  --text-subheading: 23px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.08px;
  --text-heading: 25px;
  --leading-heading: 1;
  --text-display: 90px;
  --leading-display: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 15px;
}
```
