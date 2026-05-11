# Adopt — Style Reference
> monastic elegance on aged parchment

**Theme:** light

Adopt's design system creates an atmosphere of understated authority, blending classic typographic elegance with a spacious, monastic layout. Predominantly monochrome with subtle ivory and charcoal hues, an almost-absence of color directs focus entirely to the large, expressive typography. Thin dividing lines and generous whitespace structure content, allowing the custom serif and sans-serif fonts to dictate the visual rhythm and weight. Components are designed to be invisible, serving content rather than drawing attention to themselves.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment | `#FFFEF8` | `--color-parchment` | Page background, primary canvas — a soft, off-white that feels warm and antique |
| Charcoal Black | `#1e1e1e` | `--color-charcoal-black` | Primary text, section headings, subtle borders for ghost elements, and decorative rules that delineate content sections without visual weight |
| Obsidian | `#0D0D0D` | `--color-obsidian` | Secondary surface background, an even deeper, almost imperceptible dark hint relative to Parchment, hinting at subtle depth |
| Ash Grey | `#8C8C8C` | `--color-ash-grey` | Muted secondary text, descriptive labels, and decorative borders for secondary elements. Provides a whisper of contrast without asserting dominance |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### ITCGaramondStdLightNarrow — Dominant headlines and large decorative text — weight 300 speaks with authority through restraint, avoiding the typical heavy heading. Its narrow width creates a distinct elegant presence. · `--font-itcgaramondstdlightnarrow`
- **Substitute:** EB Garamond
- **Weights:** 300, 400
- **Sizes:** 80px, 130px
- **Line height:** 0.90, 0.92
- **Letter spacing:** -0.0200em
- **Role:** Dominant headlines and large decorative text — weight 300 speaks with authority through restraint, avoiding the typical heavy heading. Its narrow width creates a distinct elegant presence.

### PPNeueMontreal — Body text, navigation, and supporting information — a modern sans-serif that provides clear readability and a compact, confident anchor to the expansive serif headings. Its slightly positive letter-spacing creates an open feel. · `--font-ppneuemontreal`
- **Substitute:** Inter
- **Weights:** 500, 600
- **Sizes:** 18px
- **Line height:** 1.33
- **Letter spacing:** 0.0100em
- **Role:** Body text, navigation, and supporting information — a modern sans-serif that provides clear readability and a compact, confident anchor to the expansive serif headings. Its slightly positive letter-spacing creates an open feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 18px | 1.33 | 0.18px | `--text-body` |
| heading | 80px | 0.92 | -1.6px | `--text-heading` |
| display | 130px | 0.9 | -2.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 12 | 12px | `--spacing-12` |
| 23 | 23px | `--spacing-23` |
| 50 | 50px | `--spacing-50` |
| 70 | 70px | `--spacing-70` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 122px
- **Card padding:** 50px
- **Element gap:** 7px

## Components

### Ghost Navigation Button
**Role:** Interactive control without a background; relies on text color for visibility and an underline on hover/active states.

Text color is Midnight Ink (#000000), 0px border-radius, 0px padding. The interaction is subtle, focusing on the text itself.

### Section Divider
**Role:** Visual separation between content blocks, maintaining a minimalist aesthetic.

A thin horizontal rule (HR element) with a border color of Charcoal Black (#1E1E1E) or Ash Grey (#8C8C8C), demonstrating minimal visual weight.

## Do's and Don'ts

### Do
- Prioritize generous whitespace, using a minimum of 50px padding on section sides and 122px between major sections.
- Utilize ITCGaramondStdLightNarrow for all primary headings, particularly at larger sizes like 80px and 130px, with its signature -0.02em letter spacing.
- Use PPNeueMontreal at 18px / 1.33 lh for all body text, ensuring a consistent 0.01em letter spacing.
- Employ Parchment (#FFFEF8) as the dominant background color for all primary content areas.
- Reserve Charcoal Black (#1E1E1E) for primary text and thin, understated horizontal rule borders.
- Design interactive elements (buttons, links) as ghost components, relying on text color (Midnight Ink #000000) and underlines for interaction states.
- Maintain a uniform 0px border-radius for all interface elements to preserve a sharp, architectural feel.

### Don't
- Avoid using box-shadows or any form of elevation; the design relies on space and typography for hierarchy.
- Do not introduce strong accent colors; maintain the predominantly achromatic palette with Parchment, Charcoal Black, Obsidian, and Ash Grey.
- Do not use generic system fonts; PPNeueMontreal and ITCGaramondStdLightNarrow are critical to the brand identity.
- Avoid tight, dense layouts; spaciousness is key to the design's elegant and authoritative feel.
- Refrain from using solid background fills for interactive elements; all buttons and links should appear 'ghosted' or text-only.
- Do not deviate from the specified letter-spacing values (-0.0200em for headings, 0.0100em for body text), as they are central to the typographic expression.
- Do not add rounded corners to any component; all radii should be 0px.

## Imagery

The site predominantly uses typography as its visual language, with very minimal imagery. When present, images are secondary to the text. The visual density is image-light, text-dominant. Icons are minimalistic, likely outlined if present, and monochrome to integrate seamlessly with the stark aesthetic. The role of any imagery would be purely decorative or to provide subtle context, never to dominate the page.

## Layout

The page maintains a centered, contained layout for most content, often within a global max-width (implied, not explicit in data but consistent visually). Hero sections typically feature large, centered headlines over a 'Parchment' background. Content rhythm is established through consistent vertical section gaps (122px) and a minimal horizontal rule as a divider. Sections often feature two-column arrangements for descriptive text and lists, with a clear left-aligned bias. The navigation features a minimalist top bar.

## Agent Prompt Guide

Quick Color Reference: 
text: #1E1E1E
background: #FFFEF8
border: #1E1E1E
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary heading section: Background Parchment (#FFFEF8). Headline 'Our Working Model' using ITCGaramondStdLightNarrow, weight 300, 130px size, line height 0.9, letter spacing -2.6px, color Charcoal Black (#1E1E1E). Subtext 'is fluid, adapting to both partner and project.' using PPNeueMontreal, weight 500, 18px size, line height 1.33, letter spacing 0.18px, color Charcoal Black (#1E1E1E). Top padding 122px, side padding 50px.
2. Create a ghost navigation button: Text 'previous' using PPNeueMontreal, weight 500, 18px size, line height 1.33, letter spacing 0.18px, color Midnight Ink (#000000). No background or borders, 0px padding. 
3. Create a descriptive text block: Background Parchment (#FFFEF8). Text 'We are experienced' at 18px PPNeueMontreal, weight 600, color Charcoal Black (#1E1E1E). Followed by body text at 18px PPNeueMontreal, weight 500, color Charcoal Black (#1E1E1E), line height 1.33, letter spacing 0.18px. Element gap of 7px between heading and body text. Side padding 50px.

## Similar Brands

- **Amie** — Monochromatic palette with a single, subtle accent hue and emphasis on crisp, restrained typography.
- **Linear** — Minimalist aesthetic dominated by thoughtful typography, high contrast neutrals, and a focus on content over decorative elements.
- **Blinkist** — Clean, spacious layouts with text-heavy content, relying on strong typographic hierarchy rather than extensive imagery.
- **Alinea** — Elegant serif headlines against a light background, paired with a modern sans-serif for body copy, conveying a sense of classic-meets-contemporary.
- **Frank and Oak** — Uses a slightly off-white, warm canvas background, generous negative space, and a refined combination of serif and sans-serif fonts to establish a sophisticated, unburdened brand presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment: #FFFEF8;
  --color-charcoal-black: #1e1e1e;
  --color-obsidian: #0D0D0D;
  --color-ash-grey: #8C8C8C;
  --color-midnight-ink: #000000;

  /* Typography — Font Families */
  --font-itcgaramondstdlightnarrow: 'ITCGaramondStdLightNarrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontreal: 'PPNeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.18px;
  --text-heading: 80px;
  --leading-heading: 0.92;
  --tracking-heading: -1.6px;
  --text-display: 130px;
  --leading-display: 0.9;
  --tracking-display: -2.6px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-12: 12px;
  --spacing-23: 23px;
  --spacing-50: 50px;
  --spacing-70: 70px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 122px;
  --card-padding: 50px;
  --element-gap: 7px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment: #FFFEF8;
  --color-charcoal-black: #1e1e1e;
  --color-obsidian: #0D0D0D;
  --color-ash-grey: #8C8C8C;
  --color-midnight-ink: #000000;

  /* Typography */
  --font-itcgaramondstdlightnarrow: 'ITCGaramondStdLightNarrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontreal: 'PPNeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.18px;
  --text-heading: 80px;
  --leading-heading: 0.92;
  --tracking-heading: -1.6px;
  --text-display: 130px;
  --leading-display: 0.9;
  --tracking-display: -2.6px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-12: 12px;
  --spacing-23: 23px;
  --spacing-50: 50px;
  --spacing-70: 70px;
  --spacing-80: 80px;
  --spacing-140: 140px;
}
```
