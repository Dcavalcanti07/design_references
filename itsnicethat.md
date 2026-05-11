# Itsnicethat — Style Reference
> Artist's sketchbook, bursting with vibrant scraps and precise typography.

**Theme:** light

This design system feels like a carefully curated art zine, balancing disciplined, editorial typography with unexpected splashes of vivid, almost childlike color. The overall impression is one of approachable creativity and intellectual curiosity. Sharp corners dominate the UI, making the few instances of extreme roundedness (75px) feel like deliberate, playful exceptions. This tension between strict layout and spontaneous color creates a dynamic, engaging experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Black Ink | `#2b2b2b` | `--color-black-ink` | Primary text, main headings, icons, borders – creates a sharp, authoritative presence against the light background. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, button text – the dominant canvas for content. |
| Frost Gray | `#f0efef` | `--color-frost-gray` | Subtle background for badges and secondary elements, offering a softer lift than Pure White. |
| Medium Gray | `#676767` | `--color-medium-gray` | Secondary text, less prominent borders and icons, receding slightly from Black Ink. |
| Muted Taupe | `#faead9` | `--color-muted-taupe` | Background for specific content blocks, providing a warm, subtle shift. |
| Electric Purple | `#8147ff` | `--color-electric-purple` | Primary brand accent, used for prominent interactive elements like call-to-action buttons – vibrant and energetic. |
| Sunshine Yellow | `#ffd519` | `--color-sunshine-yellow` | Secondary accent for interactive elements and highlighted content – adds a warm, optimistic pop. |
| Deep Indigo | `#6219ff` | `--color-deep-indigo` | Prominent links, suggesting interactivity - a slightly darker, more saturated version of Electric Purple. |
| Risograph Gradient | `linear-gradient(rgb(255, 255, 255) 20%, rgba(0, 0, 0, 0.1) 20%)` | `--color-risograph-gradient` | Subtle background gradient for specific sections, adding a textural feel. |

## Tokens — Typography

### Bradford — Body text, article content, component labels — its slightly condensed, serif form reinforces the editorial, artistic feel, making long-form content engaging. · `--font-bradford`
- **Substitute:** Georgia
- **Weights:** 400, 500
- **Sizes:** 11px, 15px, 17px
- **Line height:** 1.15, 1.47, 1.53, 2.27
- **Letter spacing:** -0.005em at 11px, 0.008em at 15px, 0.027em at 17px
- **Role:** Body text, article content, component labels — its slightly condensed, serif form reinforces the editorial, artistic feel, making long-form content engaging.

### LabilVariable — Prominent headings, titles, and key UI elements — its variable nature and wider letter spacing provides a distinct, modern counterbalance to Bradford's classic feel, adding visual breathing room to larger text blocks. · `--font-labilvariable`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 11px, 13px, 15px, 18px, 25px, 40px
- **Line height:** 1.20, 1.28, 1.40, 1.45, 1.46, 1.73
- **Letter spacing:** 0.025em at 11px, 0.032em at 13px, 0.056em at 15px, 0.067em at 18px, 0.077em at 25px, 0.091em at 40px
- **Role:** Prominent headings, titles, and key UI elements — its variable nature and wider letter spacing provides a distinct, modern counterbalance to Bradford's classic feel, adding visual breathing room to larger text blocks.

### Labil — Secondary headings, metadata, and smaller UI labels — a more compact, structured sans-serif that aids readability in informational contexts. · `--font-labil`
- **Substitute:** Open Sans
- **Weights:** 400, 500
- **Sizes:** 11px, 13px, 17px
- **Line height:** 1.40, 1.45, 1.47
- **Letter spacing:** 0.005em at 11px, 0.091em at 13px
- **Role:** Secondary headings, metadata, and smaller UI labels — a more compact, structured sans-serif that aids readability in informational contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | 0.005px | `--text-caption` |
| body | 15px | 1.47 | 0.008px | `--text-body` |
| heading | 25px | 1.46 | 0.077px | `--text-heading` |
| display | 40px | 1.73 | 0.091px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 113 | 113px | `--spacing-113` |
| 191 | 191px | `--spacing-191` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 75px |
| default | 0px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Primary Ghost Button
**Role:** Call to action, navigation

Transparent background, Black Ink text (#2b2b2b), Black Ink border (#2b2b2b). Text uses Bradford font, weight 400. No border radius. Padding 12.5px vertically, 12.5px horizontally.

### Category Label Button
**Role:** Informational grouping, filtering

Muted Taupe background (#faead9), Black Ink text (#2b2b2b), Black Ink border (#2b2b2b). Text uses Bradford font, weight 400. No border radius. Padding 12.5px vertically, 12.5px horizontally.

### Pill Accent Button
**Role:** Primary call to action (floating nav)

Electric Purple background (#8147ff), Pure White text (#ffffff), Pure White border (#ffffff). Text uses LabilVariable font, weight 400. Border radius 75px. Padding 0px vertically, 20px horizontally.

### Highlighted Button
**Role:** Prominent action

Transparent background, Sunshine Yellow text (#ffd519), Sunshine Yellow border (#ffd519). Text uses LabilVariable font, weight 400. No border radius. Padding 15px top, 16px bottom, 20px horizontally.

### Badge Tag
**Role:** Content categorization

Transparent background, Frost Gray text (#f0efef). Text uses Bradford font, weight 400. No border radius. Padding 5px vertically, 10px horizontally.

### Article Card
**Role:** Content listing

Transparent background, no shadow, no border radius. Padded at 0px. Content is structured within this transparent bounding box, images are essential for visual interest.

### Search Input Field
**Role:** User input

Pure White background (#ffffff), Black Ink text (#000000), Black Ink border (#000000). No border radius. Text uses LabilVariable font, weight 400. Padding 15px top, 16px bottom, 20px horizontally.

## Do's and Don'ts

### Do
- Use Electric Purple (#8147ff) for primary interactive elements to ensure visual magnetism.
- Maintain 0px border-radius for all structural elements and standard buttons to reinforce the sharp, editorial aesthetic.
- Employ a 75px border-radius exclusively for navigation pill buttons to highlight their distinctive interactive role.
- Utilize LabilVariable font at larger sizes for headlines, coupled with its generous letter spacing (e.g., 0.091em at 40px), to create impactful, breathable titles.
- Integrate the Muted Taupe (#faead9) background for selected content sections to provide subtle visual differentiation and warmth.
- Leverage the Bradford font for body text and descriptive elements, ensuring readability and an editorial tone.
- Apply 10px element gap as a default for horizontal and vertical spacing between most inline content elements.

### Don't
- Avoid using shadows for elevation; rely on color and spacing hierarchy instead.
- Do not deviate from the 0px border-radius for anything other than specific navigation pill buttons.
- Refrain from using highly saturated colors for large background areas or extensive text blocks; reserve them for accents.
- Do not introduce additional font families; the current mix of Bradford, LabilVariable, and Labil is deliberate.
- Avoid generic 'modern' or 'sleek' visual tropes; the system's character is in its eclectic editorial feel.
- Do not introduce gradients unless they mirror the subtle 'Risograph Gradient' pattern; avoid complex, multi-stop gradients.

## Imagery

The site primarily uses diverse, high-quality photography and static illustrations to showcase creative work. Imagery is mostly contained within distinct blocks, without significant masks or overlaps, maintaining a structured presentation. Photographs are often bright and product-focused, displaying artworks or designs clearly. Illustrations are varied in style, ranging from whimsical and organic to geometric and flat, always serving to represent artistic content. There's a high density of imagery, particularly within content listings, making the site visually rich and appealing to a creative audience. Icons are minimal, subtle, and outline-based, mostly functional.

## Layout

The page adheres to a max-width, center-aligned model of 1200px, providing structured content presentation. The hero section often features a large headline centered over a background or a split layout with prominent text. Content sections maintain a consistent vertical rhythm, with generous section spacing of 40px. The main content flows in a series of stacked, full-width blocks, often alternating between text-dominant sections and grid-like arrangements of images/cards. Feature sections frequently exhibit a three-column grid for articles. Navigation is a combination of a fixed top bar and a floating pill-shaped menu at the bottom, offering both persistent and contextual navigation.

## Agent Prompt Guide

### Quick Color Reference
Text: #2b2b2b
Background: #ffffff
CTA: #8147ff
Border: #2b2b2b
Accent: #ffd519

### 3-5 Example Component Prompts
1.  **Create a main article headline**: Text 'The joy and power of Risograph: Risotto showcases 400 printed postcards from artists across the globe'. Font LabilVariable, weight 400, size 40px, lineHeight 1.73, letterSpacing 0.091em. Color Black Ink (#2b2b2b).
2.  **Generate a primary call-to-action button for a sticky footer**: Text 'Search'. Background Electric Purple (#8147ff), text Pure White (#ffffff), border Pure White (#ffffff), borderRadius 75px, padding 0px 20px. Font LabilVariable, weight 400, size 17px.
3.  **Produce a category badge**: Text 'Advertising'. Background transparent, text Frost Gray (#f0efef), borderRadius 0px, padding 5px 10px. Font Bradford, weight 400, size 11px.
4.  **Design a hero section with a main title and a subtitle**: Main title: 'It's Nice That' - LabilVariable, weight 400, size 40px, lineHeight 1.73, letterSpacing 0.091em, color Black Ink (#2b2b2b). Subtitle: 'Inspiring Creativity Since 2007' - Bradford, weight 400, size 17px, lineHeight 1.53, letterSpacing 0.027em, color Medium Gray (#676767). Default page background Pure White (#ffffff).
5.  **Create a text input field**: Placeholder text 'Type your search...'. Background Pure White (#ffffff), text Black Ink (#000000), border Black Ink (#000000), borderRadius 0px, padding 15px top, 16px bottom, 20px horiz. Font LabilVariable, weight 400, size 15px.

## Similar Brands

- **AIGA Eye on Design** — Shares a focus on editorial content for creatives, a mixture of sharp-cornered UI with colorful accents, and distinctive typography.
- **Communication Arts** — Exhibits a similar editorial structure for showcasing creative work, relying on strong imagery and clear, structured layouts.
- **Design Milk** — Utilizes a clean, image-heavy grid layout with a strong editorial voice and occasional bold color usage for impact.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-black-ink: #2b2b2b;
  --color-pure-white: #ffffff;
  --color-frost-gray: #f0efef;
  --color-medium-gray: #676767;
  --color-muted-taupe: #faead9;
  --color-electric-purple: #8147ff;
  --color-sunshine-yellow: #ffd519;
  --color-deep-indigo: #6219ff;
  --color-risograph-gradient: #ffffff;
  --gradient-risograph-gradient: linear-gradient(rgb(255, 255, 255) 20%, rgba(0, 0, 0, 0.1) 20%);

  /* Typography — Font Families */
  --font-bradford: 'Bradford', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labilvariable: 'LabilVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil: 'Labil', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.005px;
  --text-body: 15px;
  --leading-body: 1.47;
  --tracking-body: 0.008px;
  --text-heading: 25px;
  --leading-heading: 1.46;
  --tracking-heading: 0.077px;
  --text-display: 40px;
  --leading-display: 1.73;
  --tracking-display: 0.091px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-113: 113px;
  --spacing-191: 191px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-full: 75px;

  /* Named Radii */
  --radius-buttons: 75px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-black-ink: #2b2b2b;
  --color-pure-white: #ffffff;
  --color-frost-gray: #f0efef;
  --color-medium-gray: #676767;
  --color-muted-taupe: #faead9;
  --color-electric-purple: #8147ff;
  --color-sunshine-yellow: #ffd519;
  --color-deep-indigo: #6219ff;
  --color-risograph-gradient: #ffffff;

  /* Typography */
  --font-bradford: 'Bradford', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labilvariable: 'LabilVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil: 'Labil', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.005px;
  --text-body: 15px;
  --leading-body: 1.47;
  --tracking-body: 0.008px;
  --text-heading: 25px;
  --leading-heading: 1.46;
  --tracking-heading: 0.077px;
  --text-display: 40px;
  --leading-display: 1.73;
  --tracking-display: 0.091px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-113: 113px;
  --spacing-191: 191px;

  /* Border Radius */
  --radius-full: 75px;
}
```
