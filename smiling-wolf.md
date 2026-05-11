# Smiling Wolf — Style Reference
> monochromatic editorial precision

**Theme:** light

Smiling Wolf employs a minimalist, high-contrast aesthetic reminiscent of print editorial design. A stark visual dialogue between near-black and off-white creates a sense of gravitas and directness. Typography, featuring custom fonts, is treated with precision, utilizing subtle letter-spacing adjustments and specific ligatures to convey detail and craft. The UI is largely monochromatic, relying on robust typographic hierarchy and precise spacing to define structure rather than color or extensive visual ornamentation. Components are understated, often presented as text-based interactive elements or subtle outlined cards.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#000000` | `--color-ink-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Paper White | `#f7f3f0` | `--color-paper-white` | Page backgrounds, card surfaces, secondary text on dark backgrounds. Creates a soft, almost tactile canvas |
| Charcoal | `#131713` | `--color-charcoal` | Dark section backgrounds, primary text on light backgrounds, elevated surface background. Provides strong contrast against lighter text and elements |
| Muted Ash | `#bebcb9` | `--color-muted-ash` | Subtle border colors, secondary text elements. Offers a lighter shade within the dark tonal range |
| Stone Gray | `#858582` | `--color-stone-gray` | Tertiary text, subtle separators, disabled states. A low-contrast neutral for supporting information |

## Tokens — Typography

### Bagoss Standard — Primary headings and body text, conveying a distinctive and precise brand voice. The tight letter-spacing and custom features contribute to a refined, almost type-specimen feel. Weights 400 and 520 are used for prominent headings, while 385 is for lighter body text. · `--font-bagoss-standard`
- **Substitute:** serif
- **Weights:** 385, 400, 520
- **Sizes:** 14px, 20px, 59px, 63px
- **Line height:** 0.98, 1.00, 1.15, 1.40
- **Letter spacing:** 0.0100em, 0.0100em, -0.0100em, -0.0200em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary headings and body text, conveying a distinctive and precise brand voice. The tight letter-spacing and custom features contribute to a refined, almost type-specimen feel. Weights 400 and 520 are used for prominent headings, while 385 is for lighter body text.

### General Grotesque Mono — Small labels, metadata, and structured information where monospaced precision is desired. The generous letter-spacing enhances readability at small sizes. · `--font-general-grotesque-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 9px, 10px
- **Line height:** 1.60
- **Letter spacing:** 0.1000em, 0.1000em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Small labels, metadata, and structured information where monospaced precision is desired. The generous letter-spacing enhances readability at small sizes.

### sans-serif — System fallback for small utility text like navigation links or ancillary information where a robust, universally available sans-serif is appropriate. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** System fallback for small utility text like navigation links or ancillary information where a robust, universally available sans-serif is appropriate.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| label | 10px | 1.6 | 1px | `--text-label` |
| body | 14px | 1.4 | 0.14px | `--text-body` |
| subheading | 20px | 1.15 | 0.2px | `--text-subheading` |
| display-sm | 59px | 1 | -0.59px | `--text-display-sm` |
| display | 63px | 0.98 | -1.26px | `--text-display` |

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
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 90 | 90px | `--spacing-90` |
| 120 | 120px | `--spacing-120` |
| 180 | 180px | `--spacing-180` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| buttons | 4px |
| default | 4px |

### Layout

- **Section gap:** 60px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Text Link
**Role:** Navigation, inline actions, and footer links

Uses Ink Black (#000000) or Paper White (#f7f3f0) text, with no explicit underline by default. On interaction, it may underline or change color to reinforce clickability. Radius is implicitly 4px when used as a wider interactive block.

### Ghost Button
**Role:** Secondary calls to action and interactive elements displayed as text links with subtle borders.

No background fill. Uses Ink Black (#000000) for text and a 1px border. Padding is implicitly driven by content and line height, with inner vertical spacing of 4px and horizontal of 8px. Border radius is 4px. Example: 'Start a Project' buttons.

### Footer Item
**Role:** Structured list items in the footer

Text in Ink Black (#000000) on a Charcoal (#131713) background, with a 1px Ink Black (#000000) border separating items. Internal row gap is 10px. Elements have a 4px radius.

### Featured Project Card
**Role:** Showcasing project previews

A container with no explicit border or shadow, relying on content and negative space (#f7f3f0 background implied for surrounding canvas). Images inside have a 4px border radius. Padding around content in the card is 20px on left/right. Body text within the card uses Charcoal (#131713).

### Navigation Bar
**Role:** Main site navigation

Text links in Ink Black (#000000) or Paper White (#f7f3f0) on a contrasting background. Uses `sans-serif` at 12px weight 400. Horizontal element gaps are 10px.

## Do's and Don'ts

### Do
- Use Ink Black (#000000) for primary text on Paper White (#f7f3f0) backgrounds and Paper White (#f7f3f0) on Charcoal (#131713) backgrounds to maintain high contrast.
- Apply `Bagoss Standard` `letter-spacing: -0.0100em` for all large headings (59px and 63px) to create a tight, editorial feel.
- Maintain a default border radius of 4px for all interactive elements and media containers.
- Implement consistent vertical spacing of 60px between major sections to ensure ample breathing room.
- Use `General Grotesque Mono` with `letter-spacing: 0.1000em` for small utilitarian text like tags or meta information to enhance legibility at small sizes.
- Utilize a ghost button style with a 1px Ink Black (#000000) border for secondary actions, avoiding filled buttons unless explicitly defined.

### Don't
- Avoid arbitrary color usage; stick to the defined black, white, and gray palette for UI elements.
- Do not use generic sans-serif fonts for headlines; `Bagoss Standard` is essential for brand identity.
- Resist adding unnecessary shadows or complex gradients; the design relies on flat surfaces and high contrast.
- Do not vary border radii; a consistent 4px radius is applied across all shapely elements.
- Avoid tight vertical spacing in sections; ensure a minimum `sectionGap` of 60px.
- Do not introduce strong accent colors for interactive elements unless proven by explicit brand guidelines outside this system. The system uses achromatic feedback.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Paper White Canvas | `#f7f3f0` | Dominant background for the overall page and most content sections, providing a soft, almost tactile base. |
| 2 | Charcoal Surface | `#131713` | Used for distinct dark sections, such as hero blocks or footers, creating a strong visual contrast against the Paper White canvas. Content surfaces are elevated on this dark base. |

## Imagery

This site predominantly uses embedded product images and stylized photography within content areas rather than large decorative hero visuals. Imagery, when present, tends to be contained and presented with a 4px border radius. There's a suggestive use of highly stylized visual content in project showcases, often with a subtle desaturated or tinted quality, making the UI itself the primary visual focus. Icons are minimalistic, likely outline-based, colored with Ink Black.

## Layout

The page primarily employs a max-width contained layout, though specific sections (like the 'Work with us' section) can be full-bleed with a dark background. The hero section features a centered, large headline over a dark background. Content arrangement often utilizes contrasting background blocks, with text-heavy sections or lists having defined vertical rhythm. A fluid column-based layout is implied for project showcases, adapting to available space for image and description blocks. The navigation is a sticky top bar with minimal links and a footer that uses a stacked, bordered list of links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f7f3f0
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a dark hero section with a large heading: `Charcoal (#131713)` background. Headline: `Work with us or say hello.` in `Paper White (#f7f3f0)`, `Bagoss Standard` `display` size (63px), weight 520, `letter-spacing -1.26px`. Below it, a ghost button: `Start a Project` in `Paper White (#f7f3f0)`, 1px `Paper White (#f7f3f0)` border, 4px radius, `Bagoss Standard` `subheading` size (20px), weight 400.
2. Create a footer section: `Charcoal (#131713)` background. Inner content: Vertical list of links, each using `Ink Black (#000000)` border, 1px thick, font `General Grotesque Mono` `label` size (10px), `letter-spacing 1px`, `Paper White (#f7f3f0)` text. The list items have `rowGap: 10px`.

## Similar Brands

- **Huge Inc.** — Similar high-contrast, minimalist design with a strong focus on typography and subtle element interactions.
- **Fantasy** — Employs an editorial-style layout with large, impactful typography and predominantly monochromatic color schemes.
- **B-Reel** — Uses a similar approach to showcasing work with minimal UI and a clean, spacious aesthetic, prioritizing content over heavy design elements.
- **Basic Agency** — Relies on sophisticated typography and a restricted color palette to convey premium branding and digital craftsmanship.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #000000;
  --color-paper-white: #f7f3f0;
  --color-charcoal: #131713;
  --color-muted-ash: #bebcb9;
  --color-stone-gray: #858582;

  /* Typography — Font Families */
  --font-bagoss-standard: 'Bagoss Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-grotesque-mono: 'General Grotesque Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-label: 10px;
  --leading-label: 1.6;
  --tracking-label: 1px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: 0.14px;
  --text-subheading: 20px;
  --leading-subheading: 1.15;
  --tracking-subheading: 0.2px;
  --text-display-sm: 59px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.59px;
  --text-display: 63px;
  --leading-display: 0.98;
  --tracking-display: -1.26px;

  /* Typography — Weights */
  --font-weight-w385: 385;
  --font-weight-regular: 400;
  --font-weight-w520: 520;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-90: 90px;
  --spacing-120: 120px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-buttons: 4px;
  --radius-default: 4px;

  /* Surfaces */
  --surface-paper-white-canvas: #f7f3f0;
  --surface-charcoal-surface: #131713;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #000000;
  --color-paper-white: #f7f3f0;
  --color-charcoal: #131713;
  --color-muted-ash: #bebcb9;
  --color-stone-gray: #858582;

  /* Typography */
  --font-bagoss-standard: 'Bagoss Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-grotesque-mono: 'General Grotesque Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-label: 10px;
  --leading-label: 1.6;
  --tracking-label: 1px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: 0.14px;
  --text-subheading: 20px;
  --leading-subheading: 1.15;
  --tracking-subheading: 0.2px;
  --text-display-sm: 59px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.59px;
  --text-display: 63px;
  --leading-display: 0.98;
  --tracking-display: -1.26px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-90: 90px;
  --spacing-120: 120px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
}
```
