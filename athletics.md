# Athletics — Style Reference
> Minimalist typographic canvas

**Theme:** dark

Athletics presents a stark, high-contrast visual system: a commanding black canvas frames bold, serif typography. Text is primarily oversized and statement-making, with a clean sans-serif secondary font for functional elements. The design emphasizes deliberate spacing and an absence of adornment, relying on strong typographic hierarchy and pure black-on-white surfaces to convey authority and precision. Most interactive elements are outlined or ghosted, adding to the minimal, confident aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Gown | `#000000` | `--color-midnight-gown` | Page background, primary text on white surfaces, input text, form borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text on black surfaces, button backgrounds, element borders, input text |
| Shadow Ink | `#1d1d1d` | `--color-shadow-ink` | Footer background, input background, button borders for ghost buttons |
| Muted Ash | `#d6d5d0` | `--color-muted-ash` | Subtle secondary text, decorative borders, faint accent text |

## Tokens — Typography

### Feature Deck — Large display headlines and section titles. The delicate weight at such large sizes conveys a sense of elegant authority and intentionality. · `--font-feature-deck`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 72px, 82px, 116px
- **Line height:** 1.05, 1.10
- **Letter spacing:** -0.018, -0.009, -0.018
- **Role:** Large display headlines and section titles. The delicate weight at such large sizes conveys a sense of elegant authority and intentionality.

### Söhne — Body text, navigation items, secondary headings, and functional interface text. Its neutrality supports the dramatic serif headlines. · `--font-shne`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 16px, 17px, 22px
- **Line height:** 1.30, 1.50
- **Letter spacing:** 0, 0, 0
- **Role:** Body text, navigation items, secondary headings, and functional interface text. Its neutrality supports the dramatic serif headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 17px | 1.5 | — | `--text-body-lg` |
| subheading | 22px | 1.3 | — | `--text-subheading` |
| heading | 72px | 1.05 | -0.018px | `--text-heading` |
| heading-lg | 82px | 1.1 | -0.009px | `--text-heading-lg` |
| display | 116px | 1.1 | -0.018px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 9999px |
| default | 8px |

### Layout

- **Page max-width:** 30px
- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 24px

## Components

### Primary Ghost Button
**Role:** Interactive element

White text on transparent background, bordered by Canvas White (#ffffff). Features a fully rounded 'pill' shape with 9999px border-radius and 20px vertical padding. Used for primary calls to action like 'Subscribe'.

### Subtle Input Field
**Role:** Form Element

Text input with Canvas White (#ffffff) text on a Shadow Ink (#1d1d1d) background. Defined by a bottom border of Canvas White (#ffffff) and no border radius. Features 20px padding at the bottom for text entry.

## Do's and Don'ts

### Do
- Prioritize high-contrast text pairings, with Canvas White (#ffffff) text on Midnight Gown (#000000) backgrounds or vice versa.
- Use Feature Deck font exclusively for large, impactful headlines (72px, 82px, 116px) with precise letter-spacing (-0.018em or -0.009em).
- Apply Söhne font for all body text, navigation, and functional UI elements at 16px, 17px, or 22px with normal letter spacing.
- Maintain a clear visual hierarchy by limiting color primarily to the neutral palette of #000000, #ffffff, #1d1d1d, and #d6d5d0.
- Enforce a 9999px border-radius on all interactive buttons for a consistent pill shape.
- Utilize 24px as a common element gap for consistent content grouping and vertical rhythm.
- Use a minimum of 48px vertical padding for distinct section separation.

### Don't
- Avoid introducing additional chromatic colors; the system is built on an achromatic foundation.
- Do not use box shadows or other elevation effects, as the system relies on flat surfaces and high contrast for definition.
- Do not deviate from the specified font families or their designated weights and sizes; they are core to the brand's voice.
- Do not use generic square or slightly rounded corners for buttons; all buttons must have a 9999px radius.
- Avoid cluttering the layout; maintain generous spacing between components and sections.
- Do not use more than one border on input fields; rely on a bottom border for minimal definition.
- Do not use animated gradients or complex visual effects; keep elements stark and direct.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Midnight Canvas | `#000000` | Primary page background, base layer. |
| 2 | Shadowed Element | `#1d1d1d` | Subtle interactive surfaces like input backgrounds or footer areas. |
| 3 | Reflecting White | `#ffffff` | Dominant text color on dark backgrounds, and the fill for ghosted interactive elements. |

## Elevation

The design intentionally avoids shadows, relying on extreme contrast between Midnight Gown (#000000) and Canvas White (#ffffff) for visual separation and hierarchy. Flat surfaces and clean edges are central to the brand's precise, confident aesthetic.

## Imagery

Imagery is minimal and abstract, often featuring dark, high-contrast, or monochromatic treatments. The prominent 'A' logo in the hero section is a graphic overlay with a photo reflected within, indicating a preference for integrated, less literal visuals. When present, images serve as atmospheric elements or conceptual metaphors rather than direct product showcases. Icons are absent, and UI is primarily text-driven. Graphics aim for sophistication through obscurity and artistic framing.

## Layout

The page primarily employs a full-bleed dark theme, with content contained within a loose max-width hinted at 30px (referring to significant left/right padding derived from the data's max-width analysis which likely used relative units) and centered. The hero section is full-bleed black with a large, centered typographic statement and a dark, layered graphic. Sections maintain a consistent vertical rhythm, often separating content with 48px `sectionGap` before transitioning into text-heavy blocks, sometimes with a classic two-column layout where a large headline on the left is complemented by smaller body text on the right. Navigation is a minimalist top bar. The overall density is comfortable, allowing ample white space (or rather, black space) to emphasize content.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #ffffff
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Midnight Gown (#000000) background. Centered headline 'Athletics is a brand innovation studio.' using Feature Deck font, 116px size, weight 300, Canvas White (#ffffff) color, letter-spacing -0.018em. Place a large, dark, conceptual graphic behind the headline. Ensure 144px vertical margin around the section.
2. Create a ghost button: 'Subscribe' text using Söhne font, 16px size, weight 400, Canvas White (#ffffff) color. Button has a Shadow Ink (#1d1d1d) background and 1px Canvas White (#ffffff) border, 9999px border-radius, 20px top and bottom padding, 0px left and right padding.
3. Create a two-column content block: Left column for a heading 'We help our clients design their place in the world.' using Feature Deck font, 72px size, weight 300, Canvas White (#ffffff) color, letter-spacing -0.018em. Right column for body text 'Brands come to us with ambition. We turn that ambition into a sharp vision...' using Söhne font, 17px size, weight 400, Muted Ash (#d6d5d0) color. Separate columns with 64px `columnGap`. Section features a Midnight Gown (#000000) background and 128px vertical padding.
4. Create a minimal input field: Placeholder text 'Email address' in Canvas White (#ffffff), actual input text in Canvas White (#ffffff) (Söhne font, 17px, weight 400). Background is Shadow Ink (#1d1d1d). Field has no border-radius and a bottom border of Canvas White (#ffffff), 20px padding at the bottom.

## Similar Brands

- **Huge Inc.** — Shares a sophisticated, often monochromatic look with strong typography and minimal UI elements.
- **Anagram Studio** — Known for bold, clean typefaces, minimalist layouts, and a strong dark-mode aesthetic.
- **Pentagram** — Employs classic typography and restrained visual systems to convey authority and design excellence.
- **B-Reel** — Often uses dark themes, large display type, and a focus on high-impact visual statements over dense UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-gown: #000000;
  --color-canvas-white: #ffffff;
  --color-shadow-ink: #1d1d1d;
  --color-muted-ash: #d6d5d0;

  /* Typography — Font Families */
  --font-feature-deck: 'Feature Deck', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-shne: 'Söhne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --text-heading: 72px;
  --leading-heading: 1.05;
  --tracking-heading: -0.018px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.009px;
  --text-display: 116px;
  --leading-display: 1.1;
  --tracking-display: -0.018px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Layout */
  --page-max-width: 30px;
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-buttons: 9999px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-midnight-canvas: #000000;
  --surface-shadowed-element: #1d1d1d;
  --surface-reflecting-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-gown: #000000;
  --color-canvas-white: #ffffff;
  --color-shadow-ink: #1d1d1d;
  --color-muted-ash: #d6d5d0;

  /* Typography */
  --font-feature-deck: 'Feature Deck', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-shne: 'Söhne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 17px;
  --leading-body-lg: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --text-heading: 72px;
  --leading-heading: 1.05;
  --tracking-heading: -0.018px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.009px;
  --text-display: 116px;
  --leading-display: 1.1;
  --tracking-display: -0.018px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;
}
```
