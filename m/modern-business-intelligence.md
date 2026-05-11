# Modern Business Intelligence — Style Reference
> Deep Forest Data Lab

**Theme:** dark

Mode's visual system evokes a collaborative data laboratory: a rich, deep forest green background serves as the primary canvas, providing a sense of depth. Key information and interactive elements are highlighted with vibrant, almost neon, lime-green block forms, giving content a clear visual 'lift'. Typography is blocky and bold, often enclosed in these highlight containers, creating a distinct, layered hierarchy. Components generally feature softly rounded corners, contrasting with the sharp edges of the text blocks, lending an approachable yet precise feel to the user interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canvas | `#043f2e` | `--color-forest-canvas` | Primary background for pages and sections, dark text for highlighted elements, button borders, subtle accents |
| Paper White | `#eef2e3` | `--color-paper-white` | Default interactive element backgrounds (buttons, nav items), secondary cards, light text on dark backgrounds |
| Data Highlight | `#c8f169` | `--color-data-highlight` | Primary interactive element fill, accent for key information blocks, prominent headlines. This vibrant green provides visual punch |
| Chartreuse Accent | `#78c51c` | `--color-chartreuse-accent` | Secondary accent for textual highlights, occasionally used for backgrounds of critical sections. A slightly deeper green than Data Highlight |
| Deep Green Card | `#2a6f2b` | `--color-deep-green-card` | Background for specific card-like components, adding visual variation while staying within the green palette |
| Black Ink | `#000000` | `--color-black-ink` | Default text color for light backgrounds, borders, and icon fills, providing maximum contrast |
| Pure White | `#fcfcfc` | `--color-pure-white` | Text and icon color on dark backgrounds, subtle borders, footer background |
| Deep Gray Text | `#242423` | `--color-deep-gray-text` | Darker text color, used for specific iconography and illustrations |
| Rose Tint (Decorative) | `#ffbbbe` | `--color-rose-tint-decorative` | Red decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Lavender Tint (Decorative) | `#cecafa` | `--color-lavender-tint-decorative` | Violet decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Sky Tint (Decorative) | `#bbd1fb` | `--color-sky-tint-decorative` | Violet decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |

## Tokens — Typography

### Times — Used sparingly, primarily for specific text elements where a classic serif contrast is desired, such as footnotes or minor decorative text. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Used sparingly, primarily for specific text elements where a classic serif contrast is desired, such as footnotes or minor decorative text.

### Grenette — Headline font, characterized by its substantial presence and slight negative letter-spacing for large sizes, giving it a solid, almost architectural feel. Often appears within highlighted blocks. · `--font-grenette`
- **Substitute:** Georgia
- **Weights:** 400
- **Sizes:** 16px, 36px, 56px, 70px, 72px, 96px
- **Line height:** 0.90, 1.10, 1.20, 1.31
- **Letter spacing:** -0.031em at 96px, -0.03em at 72px, -0.02em at 56px
- **Role:** Headline font, characterized by its substantial presence and slight negative letter-spacing for large sizes, giving it a solid, almost architectural feel. Often appears within highlighted blocks.

### Graphik — Primary sans-serif for body text, navigation, and smaller headings. Its varying letter-spacing from tight for display to slightly open for smaller text helps balance prominence and readability. · `--font-graphik`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 22px, 36px
- **Line height:** 1.00, 1.03, 1.10, 1.18, 1.20, 1.30, 1.44
- **Letter spacing:** -0.01em at 36px, 0.06em at 12-14px
- **Role:** Primary sans-serif for body text, navigation, and smaller headings. Its varying letter-spacing from tight for display to slightly open for smaller text helps balance prominence and readability.

### --fonts-sans — --fonts-sans — detected in extracted data but not described by AI · `--font-fonts-sans`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** --fonts-sans — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.44 | 0.72px | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.18 | — | `--text-subheading` |
| heading | 36px | 1.1 | -0.36px | `--text-heading` |
| display-sm | 56px | 1.1 | -1.12px | `--text-display-sm` |
| display | 72px | 1.1 | -2.16px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 4px |
| blocks | 16px |
| buttons | 16px |

### Layout

- **Section gap:** 56px
- **Card padding:** 32px
- **Element gap:** 12px

## Components

### Primary Highlight Button
**Role:** Call to action button

Filled with Data Highlight (#c8f169), uses Forest Canvas (#043f2e) for text. Features a 16px border-radius and 16px padding on all sides. An example is 'Try for free'.

### Outlined Text Button
**Role:** Secondary action button for ghost controls or minimal interaction

Transparent background (rgba(0,0,0,0)), text and border in Forest Canvas (#043f2e). No border-radius visible, padding 0px. Used for 'Modern BI', 'Resources' within navigation.

### Secondary Ghost Button
**Role:** Outlined button for less prominent actions

Transparent background (rgba(0,0,0,0)), text in Forest Canvas (#043f2e), bordered with Forest Canvas (#043f2e) at 4px radius. Padding is 17px top, 30px horizontal, 16px bottom. Example: 'Request demo'.

### Navigation Link Button
**Role:** Navigation items within headers

Ghost style with Forest Canvas text (#043f2e) and 4px border-radius, 0px padding. Example: 'Sign in'.

### Header Highlight Card
**Role:** Display critical metrics or features in the hero section

Solid Deep Green Card (#2a6f2b) background with 16px border-radius. No internal padding defined, shadowless. Example: the '8.2K' card.

### Main Content Card
**Role:** Structured content blocks within sections

Contained in Forest Canvas (#043f2e) with 8px border-radius, no shadow. Internal padding is 32px vertical and 56px horizontal.

### Highlight Text Block
**Role:** Enclosing striking headlines for emphasis

Background in Data Highlight (#c8f169) with 16px border-radius. Padding varies, creating a chunky, contained look for large text. This component itself has no explicit padding values, as its visual purpose is to contain headlines directly.

## Do's and Don'ts

### Do
- Use Forest Canvas (#043f2e) as the dominant background color for most page sections.
- Highlight primary calls to action and key content blocks with Data Highlight (#c8f169) for visual prominence.
- Apply a consistent 16px border-radius to cards, prominent buttons, and large content blocks for a cohesive, soft-edged look.
- Employ Grenette for display typography and Graphik for all body text, maintaining their distinct letter-spacing values.
- Ensure high contrast text, using Pure White (#fcfcfc) on Forest Canvas (#043f2e) and Black Ink (#000000) on Paper White (#eef2e3).
- Maintain a comfortable information density, using 12px for inter-element spacing and 56px for section gaps.
- Use Paper White (#eef2e3) for default button and nav backgrounds to provide clear contrast against the Forest Canvas.

### Don't
- Avoid using the decorative accent colors (Rose Tint, Lavender Tint, Sky Tint) for interactive UI elements; they are reserved for illustrations.
- Do not introduce sharp corners on cards or primary buttons; maintain the specified 16px radius for these elements.
- Avoid mixing Grenette with Graphik within the same small text block; use Grenette for headlines and Graphik for body/subheadings.
- Do not use generic gray backgrounds; always default to either Forest Canvas (#043f2e) or Paper White (#eef2e3) for structural backgrounds.
- Do not apply drop shadows to cards or elements; the system relies on solid color blocks and borders for separation.
- Avoid excessive use of system fonts; prioritize Graphik and Grenette as the brand typefaces.
- Do not center-align blocks of text or sections; maintain the left-aligned, stacked, and alternating patterns.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Forest Canvas | `#043f2` | Primary page background, providing a deep, rich foundation for the UI. |
| 1 | Paper White | `#eef2e3` | Background for secondary containers, navigation, and sections that require higher contrast against text. |
| 2 | Data Highlight | `#c8f169` | Elevated background for interactive elements and prominent textual blocks, bringing elements to the foreground with a vibrant pop. |

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #043f2e
border: #043f2e
accent: #78c51c
primary action: #c8f169 (filled action)

Example Component Prompts:
1. Create a Hero Section headline: 'Business Intelligence' in Grenette 72px, lineHeight 1.1, letter-spacing -2.16px, background Data Highlight (#c8f169), font color Forest Canvas (#043f2e), with 16px radius.
2. Create a Secondary Ghost Button: 'Request demo' with transparent background, Forest Canvas (#043f2e) text, 1px solid Forest Canvas (#043f2e) border, 4px radius, 17px top padding, 30px horizontal padding, 16px bottom padding.
3. Create a Navigation Item: 'Why Mode' as a link using Graphik 16px, weight 400, Forest Canvas (#043f2e) text, no background or border, 0px padding, 4px radius.

## Similar Brands

- **Figma** — Visual emphasis on functional blocks and a clean, almost 'app-like' presentation of content.
- **Vercel** — Dark primary background contrasted with vibrant, functional accent colors for key information and calls to action.
- **linear.app** — Opinionated typography and a focus on content hierarchy through block-level elements and intentional use of contrast.
- **Notion** — Structured content in block-based formats, though Notion uses a lighter palette, the principle of component-based content is similar.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canvas: #043f2e;
  --color-paper-white: #eef2e3;
  --color-data-highlight: #c8f169;
  --color-chartreuse-accent: #78c51c;
  --color-deep-green-card: #2a6f2b;
  --color-black-ink: #000000;
  --color-pure-white: #fcfcfc;
  --color-deep-gray-text: #242423;
  --color-rose-tint-decorative: #ffbbbe;
  --color-lavender-tint-decorative: #cecafa;
  --color-sky-tint-decorative: #bbd1fb;

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-grenette: 'Grenette', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fonts-sans: '--fonts-sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.44;
  --tracking-caption: 0.72px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.18;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.36px;
  --text-display-sm: 56px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -1.12px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -2.16px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 56px;
  --card-padding: 32px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 4px;
  --radius-blocks: 16px;
  --radius-buttons: 16px;

  /* Surfaces */
  --surface-forest-canvas: #043f2;
  --surface-paper-white: #eef2e3;
  --surface-data-highlight: #c8f169;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canvas: #043f2e;
  --color-paper-white: #eef2e3;
  --color-data-highlight: #c8f169;
  --color-chartreuse-accent: #78c51c;
  --color-deep-green-card: #2a6f2b;
  --color-black-ink: #000000;
  --color-pure-white: #fcfcfc;
  --color-deep-gray-text: #242423;
  --color-rose-tint-decorative: #ffbbbe;
  --color-lavender-tint-decorative: #cecafa;
  --color-sky-tint-decorative: #bbd1fb;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-grenette: 'Grenette', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fonts-sans: '--fonts-sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.44;
  --tracking-caption: 0.72px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.18;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.36px;
  --text-display-sm: 56px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -1.12px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -2.16px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
}
```
