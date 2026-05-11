# Home — Style Reference
> Deconstructed Ledger — high-contrast monochrome with vivid green accents on a textured white canvas.

**Theme:** light

New Form presents a stark, high-contrast digital ledger aesthetic with a playful, deconstructed twist. Its visual style combines bold, almost brutalist typography with a monochrome palette punctuated by a single vibrant green, creating a sense of both heritage finance and disruptive innovation. Imagery is integrated invasively into text blocks, and surfaces are largely flat with minimal elevation, emphasizing data and content over decorative elements. The overall impression is one of confident, almost academic authority, yet with an underlying dynamic energy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fafffa` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text, active states in dark mode context |
| Rich Black | `#121613` | `--color-rich-black` | Primary text, deep surface backgrounds for section breaks, strong borders, and footer |
| Text Black | `#000000` | `--color-text-black` | Content text, borders, default button text, icon stroke |
| Charcoal | `#232924` | `--color-charcoal` | Secondary section backgrounds, subtle text for contrast against lighter Rich Black |
| Slate Gray | `#516254` | `--color-slate-gray` | Muted headings, subtle text elements, borders |
| Light Gray | `#c8d2c8` | `--color-light-gray` | Subtle descriptive text, light borders, less prominent headings |
| Vivid Green | `#2bee4b` | `--color-vivid-green` | Primary action button backgrounds, accent elements like menu toggles, decorative underlines – signifying activation and interaction |
| Mint Shadow | `#93b799` | `--color-mint-shadow` | Green supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |

## Tokens — Typography

### TWK Lausanne — General content, body text, nav items, small details. Its versatility and varying weights support both textual bulk and subtle UI elements. · `--font-twk-lausanne`
- **Substitute:** system-ui
- **Weights:** 200, 350, 400, 550
- **Sizes:** 11px, 14px, 16px, 18px, 72px, 96px, 155px
- **Line height:** 1.00, 1.10, 1.40
- **Letter spacing:** -0.0400em at 155px, -0.0200em at 96px, 0.0100em at 11-18px
- **Role:** General content, body text, nav items, small details. Its versatility and varying weights support both textual bulk and subtle UI elements.

### Editorial New — Hero headlines and large, impactful display text. Its thin weight at large sizes creates a distinctive, almost ethereal presence, demanding attention without shouting. · `--font-editorial-new`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 60px, 140px, 240px
- **Line height:** 0.90
- **Letter spacing:** -0.0200em at 140px, -0.0100em at 60px
- **Role:** Hero headlines and large, impactful display text. Its thin weight at large sizes creates a distinctive, almost ethereal presence, demanding attention without shouting.

### PP Mondwest — Specific display headlines at monumental sizes. Its condensed and heavy form provides an industrial, almost financial data ticker feel, emphasizing raw information. · `--font-pp-mondwest`
- **Substitute:** Impact
- **Weights:** 400
- **Sizes:** 60px, 165px, 295px
- **Line height:** 0.90
- **Letter spacing:** -0.0400em at all sizes
- **Role:** Specific display headlines at monumental sizes. Its condensed and heavy form provides an industrial, almost financial data ticker feel, emphasizing raw information.

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** Times — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | 0.11px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.14px | `--text-body-sm` |
| body | 16px | 1.4 | 0.16px | `--text-body` |
| body-lg | 18px | 1.4 | 0.18px | `--text-body-lg` |
| heading-sm | 60px | 0.9 | -0.6px | `--text-heading-sm` |
| heading | 72px | 1.1 | -1.44px | `--text-heading` |
| heading-lg | 96px | 1 | -1.92px | `--text-heading-lg` |
| display | 155px | 1 | -6.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 50 | 50px | `--spacing-50` |
| 55 | 55px | `--spacing-55` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 190 | 190px | `--spacing-190` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 4.9968px |
| default | 9.9936px |
| imageMasks | 0px |
| menuButtons | 9.9936px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(16, 94, 29, 0.45) 1px 8px 20px 0px` | `--shadow-lg` |
| lg-2 | `rgba(18, 146, 39, 0.25) 1px 8px 20px 0px` | `--shadow-lg-2` |

### Layout

- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Action Button
**Role:** Call to action

Solid Vivid Green (#2bee4b) background with Text Black (#000000) text, 4.9968px border-radius, and generous 20px vertical, 30px horizontal padding. A subtle Mint Shadow rgba(16, 94, 29, 0.45) 1px 8px 20px 0px provides a lift.

### Ghost Navigation Button
**Role:** Navigation links, secondary actions

Transparent background with Text Black (#000000) text, no border. Used for discrete navigational elements or less emphasized actions.

### Menu Toggle Button
**Role:** Global navigation access

Transparent background, Canvas White (#fafffa) text and border. Features a distinct 9.9936px border-radius and large vertical padding for touch targets, giving it a prominent, almost pill-like shape.

### Headline with Image Inlay
**Role:** Hero content, section titles

Large Editorial New or PP Mondwest text (e.g., 240px, 0.9 lineHeight), often Rich Black (#121613). Black and white images are integrated directly into the text lines, acting as visual interruptions and focal points, rather than contained blocks.

### Feature Card
**Role:** Content grouping

Transparent background with 0px border-radius, relying on surrounding layout for definition. Internal images are usually black and white with 0px radius, flush with content.

## Do's and Don'ts

### Do
- Use Vivid Green (#2bee4b) exclusively for primary calls to action, menu indicators, and small functional accents.
- Maintain a high contrast ratio between text and background, primarily using Rich Black (#121613) or Text Black (#000000) on Canvas White (#fafffa).
- Integrate black and white imagery directly into large text blocks without borders or padding, allowing text to wrap organically.
- Apply 4.9968px border-radius to primary action buttons for a consistent interactive element shape.
- Use TWK Lausanne for all body text, navigation, and most UI elements, reserving Editorial New and PP Mondwest for impactful headlines.
- Ensure generous vertical spacing between sections to create a spacious, breathable layout rhythm.
- Favor flat, borderless cards and content blocks, letting negative space and surrounding elements define their boundaries.

### Don't
- Never use Vivid Green (#2bee4b) for generic text or decorative elements not related to action or activation.
- Avoid using multiple chromatic colors; the visual system is anchored by monochrome and a singular green accent.
- Do not add drop shadows or significant elevation to elements other than primary buttons; surfaces should appear flat and digital.
- Do not use rounded corners on imagery or general content cards; maintain a stark, unembellished aesthetic for embedded visuals.
- Avoid decorative gradients; surfaces should be solid colors to reinforce the clean, digital ledger feel.
- Do not condense primary content too tightly; embrace spaciousness and visual breaks.
- Refrain from using generic icon sets; custom, minimalist icons in Text Black (#000000) or Vivid Green (#2bee4b) are preferred.

## Imagery

The visual language is dominated by black and white, often archival, photography of financial infrastructure, technology, and historical business contexts. Images are frequently full-bleed and integrated directly into headline text blocks without padding or borders, creating a fragmented, almost 'glitch art' effect. They serve as historical context and metaphorical anchors, not decorative elements. Iconography is minimalist, outlined, and monochromatic, primarily using Text Black or Vivid Green. The density is moderate, with images playing a crucial, embedded role within typography rather than standard content blocks.

## Layout

The page primarily uses a max-width contained layout with centered content, though elements like the hero headline can span wider with image inlays. The hero features monumental typography with integrated imagery. Sections are largely separated by spacious vertical gaps. Content arrangement frequently alternates between large textual blocks and imagery, creating a dynamic, almost collage-like flow. There's no obvious grid for cards, which appear more as embedded visuals within prose. The navigation is a minimalist top bar with a left-aligned logo and a right-aligned menu toggle.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fafffa
border: #000000
accent: #2bee4b
primary action: #2bee4b (filled action)

Example Component Prompts:
1. Create a primary action button: Vivid Green (#2bee4b) background, Text Black (#000000) text, 4.9968px border-radius, 20px 30px padding, with a shadow of rgba(16, 94, 29, 0.45) 1px 8px 20px 0px.
2. Design a ghost navigation button: Transparent background, Text Black (#000000) text, no border or padding, font TWK Lausanne weight 400 at 16px.
3. Build a hero headline: Text Rich Black (#121613), Editorial New weight 300 at 140px, lineHeight 0.9, letterSpacing -0.0200em. Embed a black and white image directly within the text flow at one or more word breaks, without any padding or borders for the image.

## Similar Brands

- **Stripe** — Focus on developer tooling, clean typography, and a similar approach to using a single accent color for interaction atop a largely monochrome palette.
- **Linear** — High-contrast UI, precise typography with detailed letter-spacing, and a feeling of 'engineered' design.
- **Brave Browser** — Monochromatic interface with a single vibrant accent color (orange) used for key interactive elements.
- **Vercel** — Clean, opinionated typography, high contrast, and a strong sense of a 'developer toolkit' aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fafffa;
  --color-rich-black: #121613;
  --color-text-black: #000000;
  --color-charcoal: #232924;
  --color-slate-gray: #516254;
  --color-light-gray: #c8d2c8;
  --color-vivid-green: #2bee4b;
  --color-mint-shadow: #93b799;

  /* Typography — Font Families */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-mondwest: 'PP Mondwest', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.11px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.16px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: 0.18px;
  --text-heading-sm: 60px;
  --leading-heading-sm: 0.9;
  --tracking-heading-sm: -0.6px;
  --text-heading: 72px;
  --leading-heading: 1.1;
  --tracking-heading: -1.44px;
  --text-heading-lg: 96px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.92px;
  --text-display: 155px;
  --leading-display: 1;
  --tracking-display: -6.2px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-w550: 550;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-55: 55px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-190: 190px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-md: 4.9968px;
  --radius-lg: 9.9936px;
  --radius-xl: 14px;

  /* Named Radii */
  --radius-buttons: 4.9968px;
  --radius-default: 9.9936px;
  --radius-imagemasks: 0px;
  --radius-menubuttons: 9.9936px;

  /* Shadows */
  --shadow-lg: rgba(16, 94, 29, 0.45) 1px 8px 20px 0px;
  --shadow-lg-2: rgba(18, 146, 39, 0.25) 1px 8px 20px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fafffa;
  --color-rich-black: #121613;
  --color-text-black: #000000;
  --color-charcoal: #232924;
  --color-slate-gray: #516254;
  --color-light-gray: #c8d2c8;
  --color-vivid-green: #2bee4b;
  --color-mint-shadow: #93b799;

  /* Typography */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-mondwest: 'PP Mondwest', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.11px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.16px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: 0.18px;
  --text-heading-sm: 60px;
  --leading-heading-sm: 0.9;
  --tracking-heading-sm: -0.6px;
  --text-heading: 72px;
  --leading-heading: 1.1;
  --tracking-heading: -1.44px;
  --text-heading-lg: 96px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.92px;
  --text-display: 155px;
  --leading-display: 1;
  --tracking-display: -6.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-55: 55px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-190: 190px;

  /* Border Radius */
  --radius-md: 4.9968px;
  --radius-lg: 9.9936px;
  --radius-xl: 14px;

  /* Shadows */
  --shadow-lg: rgba(16, 94, 29, 0.45) 1px 8px 20px 0px;
  --shadow-lg-2: rgba(18, 146, 39, 0.25) 1px 8px 20px 0px;
}
```
