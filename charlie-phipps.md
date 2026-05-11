# Charlie Phipps — Style Reference
> Midnight Command Center: precise lines on a deep, expansive canvas, guided by stark textual contrasts.

**Theme:** dark

Charlie Phipps' design system evokes a digital architect's blueprint, utilizing a stark, high-contrast monochrome palette. The interface relies on precise typographical interplay of a clean sans-serif and a classic serif to establish hierarchy and character. Layouts are spacious, with ample negative space emphasizing content blocks through strict alignment and subtle borders rather than heavy visual containers, creating an atmosphere of considered precision amidst a dark canvas.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `#101011` | `--color-midnight-canvas` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary text color for headlines and body text on dark backgrounds; used for key information and some borders |
| Obsidian Text | `#000000` | `--color-obsidian-text` | Primary text color on light backgrounds |
| Ash Panel | `#ededed` | `--color-ash-panel` | Secondary background surface for cards or sections, providing subtle differentiation from the main canvas |
| Whisper Grey | `#bab7b2` | `--color-whisper-grey` | Muted headline text, providing soft contrast |
| Charcoal Detail | `#888888` | `--color-charcoal-detail` | Subtler text, decorative borders, secondary links, and icons, adding depth without distraction |
| Dark Granite Border | `#262627` | `--color-dark-granite-border` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Deep Space Accent | `#080809` | `--color-deep-space-accent` | Deepest dark for specific text and subtle accent borders |

## Tokens — Typography

### Helvetica Neue — The primary sans-serif for headlines, body text, and interactive elements. Its neutral character provides clarity and adapts to varying scale and tracking for distinct hierarchal purposes. · `--font-helvetica-neue`
- **Substitute:** Arial, Helvetica
- **Weights:** 400
- **Sizes:** 16px, 17px, 19px, 21px, 52px, 64px, 162px
- **Line height:** 0.90, 1.00, 1.20
- **Letter spacing:** -0.0240em at 162px, -0.0130em at 64px, -0.0120em at 52px, -0.0100em at 21px, -0.0040em at 19px, normal at 16px, 17px
- **Role:** The primary sans-serif for headlines, body text, and interactive elements. Its neutral character provides clarity and adapts to varying scale and tracking for distinct hierarchal purposes.

### Times — A serif font used sparingly for atmospheric, smaller captions and metadata, providing a touch of classic contrast against the sans-serif dominance. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** A serif font used sparingly for atmospheric, smaller captions and metadata, providing a touch of classic contrast against the sans-serif dominance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1 | — | `--text-caption` |
| body-sm | 17px | 1 | — | `--text-body-sm` |
| body | 19px | 1 | — | `--text-body` |
| body-lg | 21px | 1 | — | `--text-body-lg` |
| heading-sm | 52px | 1 | — | `--text-heading-sm` |
| heading | 64px | 1 | — | `--text-heading` |
| heading-lg | 162px | 1 | — | `--text-heading-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 13 | 13px | `--spacing-13` |
| 26 | 26px | `--spacing-26` |
| 41 | 41px | `--spacing-41` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 41px
- **Card padding:** 13px
- **Element gap:** 6px

## Components

### Navigation Link
**Role:** Top and bottom navigation items.

Text uses Cloud White on Midnight Canvas background. On hover, the background might transition to Midnight Canvas with an inverse text color, or a subtle border appears using Dark Granite Border. Padding is 2px at the bottom. Smallest text size 13px Times with normal letter spacing, or 16px Helvetica Neue with normal letter spacing.

### Text Card
**Role:** Container for textual content or project summaries.

Background is transparent (rgba(0,0,0,0)). No border or shadow. Internal padding is 13px on all sides. Content uses Cloud White text.

### Interactive Text Box
**Role:** Visually distinct blocks of text that might respond to interaction.

Background is Midnight Canvas. Can have borders or text in Cloud White, Obsidian Text, or Ash Panel. Internal padding varies, often 6px vertical.

### Page Header Nav
**Role:** Persistent top-level navigation.

Contains links (Project Index, Profile) in Cloud White. Implicit borders or active states use Charcoal Detail. Text uses Helvetica Neue 16px, weight 400.

## Do's and Don'ts

### Do
- Prioritize Cloud White (#ffffff) text on midnight Canvas (#101011) whenever possible to leverage the primary brand contrast.
- Use Helvetica Neue for all primary textual content and headings to maintain the sharp, modern tone.
- Reserve the Times typeface for subtle meta-information, captions, or contextual details at 13px size.
- Employ 13px global padding on cards and content blocks for a comfortable density.
- Utilize 0px border-radius across all elements to enforce a precise, architectural aesthetic.
- Apply precise negative letter-spacing from the Helvetica Neue typography profile for all headings to achieve tight, impactful text blocks.
- Use Charcoal Detail (#888888) for all secondary interactive elements like borders and muted links to prevent visual clutter.

### Don't
- Avoid using saturated or chromatic colors; the palette is strictly achromatic to maintain a stark, sophisticated feel.
- Do not introduce rounded corners; all elements should adhere to sharp, squared edges (0px radius).
- Do not use box-shadows or elevation effects; the design relies on flat layers and precise lines for depth.
- Avoid generic system fonts when Helvetica Neue or Times are specified; utilize the provided typefaces for brand consistency.
- Do not deviate from the defined letter-spacing values, especially for headlines, as it’s critical to brand identity.
- Do not use heavy panel backgrounds; instead, use transparent backgrounds or subtle Ash Panel (#ededed) for content separation.

## Imagery

This system features a blend of product photography and contextual imagery. Photography appears as full-bleed, unmasked backgrounds for hero sections, specifically urban landscapes with architectural elements or public transport. Product images within the portfolio are contained, often occupying clean, minimal frames. There's an absence of traditional icons, instead using typographic arrows (e.g., '︎︎︎') for interaction cues. Imagery serves both decorative atmosphere in heroes and explanatory content within the portfolio sections, with a generally high density of visual content.

## Layout

The page exhibits a full-bleed, left-aligned layout, with content primarily flowing top-to-bottom. The hero section features an expansive background image and a large, centered headline that bleeds off the edges. Subsequent sections maintain a generous vertical rhythm, often alternating between large text blocks and image groupings, with a flexible column structure. The navigation is a split top-bar, with a minimal left-aligned brand mark and right-aligned links. There's no strict grid observed for large content blocks; rather, an organic arrangement emphasizing large visual and textual elements within ample negative space. The overall density is comfortable, giving significant breathing room to each content segment.

## Agent Prompt Guide

Quick Color Reference: 
text: #ffffff
background: #101011
border: #262627
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a top navigation bar: background #101011. Left-aligned brand text '● Charlie Phipps' in #ffffff, Helvetica Neue 16px weight 400. Right-aligned links 'Project Index' and 'Profile' in #ffffff, Helvetica Neue 16px weight 400. All elements have 0px radius.
2. Design a hero section: full-width background image. Overlay a large headline 'pps (LDN) Graphic [' in #ffffff, Helvetica Neue 162px weight 400, letter-spacing -0.0240em, centered on the screen. No padding or radius for the headline.
3. Create a text block with a sub-heading: 'Selected works ©2022.' as heading in #ffffff, Helvetica Neue 52px weight 400, letter-spacing -0.0120em. Below it, a paragraph 'Overview of my latest and featured projects (2019 —2022) within Digital Design, Brand Design and Design Direction.' in #ffffff, Helvetica Neue 21px weight 400, letter-spacing -0.0100em. Both text blocks have 13px padding on all sides.

## Similar Brands

- **Stripe** — Shares a stark, high-contrast textual approach with minimal decorative elements, relying on precise typography.
- **Linear** — Utilizes a dark, achromatic theme with clean lines and a focus on functional typography and layout clarity over heavy visual design.
- **Awwwards Nominees (certain portfolios)** — Many portfolio sites adopt a similar full-bleed imagery approach paired with bold typography and a minimal UI frame.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #101011;
  --color-cloud-white: #ffffff;
  --color-obsidian-text: #000000;
  --color-ash-panel: #ededed;
  --color-whisper-grey: #bab7b2;
  --color-charcoal-detail: #888888;
  --color-dark-granite-border: #262627;
  --color-deep-space-accent: #080809;

  /* Typography — Font Families */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1;
  --text-body-sm: 17px;
  --leading-body-sm: 1;
  --text-body: 19px;
  --leading-body: 1;
  --text-body-lg: 21px;
  --leading-body-lg: 1;
  --text-heading-sm: 52px;
  --leading-heading-sm: 1;
  --text-heading: 64px;
  --leading-heading: 1;
  --text-heading-lg: 162px;
  --leading-heading-lg: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-13: 13px;
  --spacing-26: 26px;
  --spacing-41: 41px;

  /* Layout */
  --section-gap: 41px;
  --card-padding: 13px;
  --element-gap: 6px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #101011;
  --color-cloud-white: #ffffff;
  --color-obsidian-text: #000000;
  --color-ash-panel: #ededed;
  --color-whisper-grey: #bab7b2;
  --color-charcoal-detail: #888888;
  --color-dark-granite-border: #262627;
  --color-deep-space-accent: #080809;

  /* Typography */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1;
  --text-body-sm: 17px;
  --leading-body-sm: 1;
  --text-body: 19px;
  --leading-body: 1;
  --text-body-lg: 21px;
  --leading-body-lg: 1;
  --text-heading-sm: 52px;
  --leading-heading-sm: 1;
  --text-heading: 64px;
  --leading-heading: 1;
  --text-heading-lg: 162px;
  --leading-heading-lg: 1;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-13: 13px;
  --spacing-26: 26px;
  --spacing-41: 41px;
}
```
