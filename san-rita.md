# San Rita — Style Reference
> Field Notes & Radio Signals — a minimalist topographic map combined with stark, technical typography.

**Theme:** dark

San Rita balances rugged outdoor aesthetics with refined, almost architectural typography. The visual language evokes adventure and groundedness through a dominant muted green (#84907f) and a 'radio-signal' chartreuse accent (#e2ffcc) against a deep forest green background. Oversized, condensed custom typography for headlines grounds the design, while the monospace text adds a technical, almost archival feel, reminiscent of field notes in a wilderness expedition.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canopy | `#161b13` | `--color-forest-canopy` | Primary background for dark sections, footer background — creates a deep, grounding impression. |
| Terrain Shadow | `#2d3329` | `--color-terrain-shadow` | Secondary background, subtle text contrast on dark surfaces — creates varied surface depth within dark areas. |
| Paper White | `#dde2e4` | `--color-paper-white` | Lightest neutral, used for body text on dark backgrounds and some icons — provides crisp readability against dark surfaces. |
| Earth Gray | `#84907f` | `--color-earth-gray` | Main accent for illustrations, some body text, and background elements — provides a muted, organic counterpoint to the vibrant accent. |
| Adventure Chartreuse | `#e2ffcc` | `--color-adventure-chartreuse` | Primary accent for calls to action, headings on dark backgrounds, and interactive elements — creates high contrast and signals interactivity with a vibrant, almost neon quality. |
| Headline Black | `#000000` | `--color-headline-black` | Dominant text color on 'Adventure Chartreuse' backgrounds and for the massive 'F37stout' headlines — provides maximum contrast for key messaging. |

## Tokens — Typography

### F37stout — Display headlines and prominent section titles. The extremely low line-height and often massive sizes create a stark, impactful visual block that feels carved or architectural rather than just typeset. · `--font-f37stout`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 40px, 48px, 366px
- **Line height:** 0.90
- **Letter spacing:** normal
- **Role:** Display headlines and prominent section titles. The extremely low line-height and often massive sizes create a stark, impactful visual block that feels carved or architectural rather than just typeset.

### mono — Body text, navigation items, metadata, and labels. The monospace, slight negative letter-spacing, and small sizes lend a technical, almost coded or field-report aesthetic, reinforcing the 'exploration' theme. · `--font-mono`
- **Substitute:** Space Mono
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 16px
- **Line height:** 1.20
- **Letter spacing:** -0.0100em
- **Role:** Body text, navigation items, metadata, and labels. The monospace, slight negative letter-spacing, and small sizes lend a technical, almost coded or field-report aesthetic, reinforcing the 'exploration' theme.

### Times New Roman — Used sparingly for specific links or secondary textual elements, adding a classic, documentary-style contrast to the stark monospace text. · `--font-times-new-roman`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used sparingly for specific links or secondary textual elements, adding a classic, documentary-style contrast to the stark monospace text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | -0.1px | `--text-caption` |
| body | 16px | 1.2 | -0.16px | `--text-body` |
| heading-sm | 40px | 0.9 | — | `--text-heading-sm` |
| heading | 48px | 0.9 | — | `--text-heading` |
| display | 366px | 0.9 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 67 | 67px | `--spacing-67` |
| 70 | 70px | `--spacing-70` |
| 190 | 190px | `--spacing-190` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Navigation Button
**Role:** Primary Call to Action in header

Button with 'Adventure Chartreuse' background (#e2ffcc), 'Headline Black' text (#000000), rounded corners (radius is part of custom button shape, appearing like a pill in the screenshot). Padding is likely 16px horizontal, 5px vertical based on general spacing and visual analysis. Text is 'mono' font, 10px, weight 400, letter-spacing -0.01em.

### Inline Link
**Role:** Interactive text link

Text uses 'Times' font, 16px, weight 400. Color is 'Paper White' (#dde2e4) on dark backgrounds or 'Headline Black' (#000000) on light accent backgrounds.

### Hero Headline
**Role:** Main heading on hero section

Uses 'F37stout' font, 366px, weight 400, line-height 0.9. Text color is 'Adventure Chartreuse' (#e2ffcc) against a topographical background image.

### Footer Text Block
**Role:** Descriptive text in footer

Text uses 'mono' font, 16px, weight 400, letter-spacing -0.01em. Color is 'Paper White' (#dde2e4). Padding around text blocks is 24px.

### Map Overlay Icon
**Role:** Interactive icon on map background

Icon is SVG, 'Paper White' (#dde2e4) fill, 2px stroke, no background. Positioned with 70px left margin based on visual cues.

## Do's and Don'ts

### Do
- Use 'Adventure Chartreuse' (#e2ffcc) for all primary interactive elements and key headings to maintain brand energy.
- Pair 'F37stout' for display text with 'mono' for body text to create the signature technical-meets-monumental typography.
- Employ consistent 12px or 24px spacing for element gaps and margins, extending to 40px for larger structural gaps.
- Maintain a clear visual hierarchy by limiting 'Times' font usage to specific, less prominent links or references.
- Incorporate 'Earth Gray' (#84907f) subtly within illustrations or as a background hue to add an organic, geological feel.

### Don't
- Avoid using 'Times' font for large headings or core UI elements, as it dilutes the brand's typographic identity.
- Do not introduce new color palettes; stick rigidly to 'Forest Canopy', 'Terrain Shadow', 'Paper White', 'Earth Gray', 'Adventure Chartreuse', and 'Headline Black'.
- Borders or explicit drop shadows are not part of this system; achieve depth through contrasting background colors or layering of content blocks.
- Do not deviate from the specified letter-spacing for 'mono' (-0.01em) as it contributes significantly to its technical character.
- Avoid generic imagery or illustrations; focus on topographic maps, abstract outdoor elements, or tightly cropped, art-directed photography.

## Imagery

Visuals are a mix of abstract topographic map imagery as large background elements, and candid, somewhat gritty photography depicting individuals in outdoor settings. The map imagery is full-bleed and dominant, providing context and atmosphere rather than direct information. Photography uses natural light, appears unprocessed, and is presented as overlapping, slightly rotated rectangles, creating a scrapbook-like or 'field journal' aesthetic. Icons are simple, outlined SVGs, typically 'Paper White' against dark backgrounds, acting as minimal navigational cues or location markers. The overall density is heavy in imagery, allowing large visuals to define sections and convey mood.

## Layout

The page primarily uses a full-bleed layout, particularly for hero sections and embedded background imagery. Content is contained within invisible horizontal bounds, with generous left/right margins (67px, 70px, 190px). The hero section features a dominant fullscreen background image with oversized, centered typography. Sections alternate between full-bleed imagery and solid color backgrounds, establishing visual rhythm. Content often appears in centered stacks or simple two-column arrangements, always prioritizing generous breathing room defined by large spacing tokens. Navigation consists of a clear top bar with minimal elements.

## Agent Prompt Guide

### Quick Color Reference
- Text on dark: #dde2e4
- Text on light: #000000
- Background dark: #161b13
- Background accent: #e2ffcc
- Accent: #84907f

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed background image, overlay a headline `WE ARE SAN RITA` using F37stout font, 366px, weight 400, line-height 0.9, color #e2ffcc. Position the headline centered.
2. Design a navigation button: `SHOW TRAILS` text using mono font, 10px, weight 400, letter-spacing -0.01em, color #000000. Button background color #e2ffcc, with implied pill shape (no explicit radius, visual). Add 16px horizontal and 5px vertical padding.
3. Generate a footer text block: `Born in California, Started in Montreal...` using mono font, 16px, weight 400, letter-spacing -0.01em, color #dde2e4, on a #161b13 background. Ensure 24px internal padding around the text.
4. Produce a secondary heading: `Julien` using F37stout, 40px, weight 400, line-height 0.9, color #dde2e4.
5. Create a body paragraph: `In the stillness of the California desert...` using mono font, 16px, weight 400, line-height 1.2, letter-spacing -0.01em, color #dde2e4, on a #2d3329 background.

## Similar Brands

- **Patagonia** — Shares a rugged, outdoors-focused brand identity with an emphasis on natural textures and earthy tones balanced by specific action-oriented colors.
- **Arc'teryx** — Similar high-performance and technical aesthetic, often using stark typography and utilitarian color palettes in design.
- **Native Teams** — Uses large, impactful condensed typography as a primary visual element, similar to the F37stout usage here.
- **The North Face** — Employs an adventurer/exploration brand story through visual cues and imagery that evoke the wild.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canopy: #161b13;
  --color-terrain-shadow: #2d3329;
  --color-paper-white: #dde2e4;
  --color-earth-gray: #84907f;
  --color-adventure-chartreuse: #e2ffcc;
  --color-headline-black: #000000;

  /* Typography — Font Families */
  --font-f37stout: 'F37stout', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mono: 'mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.1px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-heading-sm: 40px;
  --leading-heading-sm: 0.9;
  --text-heading: 48px;
  --leading-heading: 0.9;
  --text-display: 366px;
  --leading-display: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-5: 5px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-67: 67px;
  --spacing-70: 70px;
  --spacing-190: 190px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canopy: #161b13;
  --color-terrain-shadow: #2d3329;
  --color-paper-white: #dde2e4;
  --color-earth-gray: #84907f;
  --color-adventure-chartreuse: #e2ffcc;
  --color-headline-black: #000000;

  /* Typography */
  --font-f37stout: 'F37stout', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mono: 'mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.1px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.16px;
  --text-heading-sm: 40px;
  --leading-heading-sm: 0.9;
  --text-heading: 48px;
  --leading-heading: 0.9;
  --text-display: 366px;
  --leading-display: 0.9;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-67: 67px;
  --spacing-70: 70px;
  --spacing-190: 190px;
}
```
