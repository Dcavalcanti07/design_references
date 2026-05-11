# DICE — Style Reference
> High-contrast monochrome canvas

**Theme:** light

DICE uses a bold, monochrome aesthetic with a stark black-and-white foundation that provides a high-contrast canvas. Typography is assertive, carrying much of the brand's voice, while subtle hints of energetic accent colors occasionally punctuate the otherwise achromatic interface. Component surfaces are flat and minimal, often relying on high contrast and distinct shapes rather than shadows for visual separation, embodying a robust, no-nonsense utility.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, background for active elements, hero sections at full width, borders, icons. Provides extreme contrast |
| Arctic White | `#ffffff` | `--color-arctic-white` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Ash Gray | `#d9d9d9` | `--color-ash-gray` | Subtle background for UI blocks or dividers, distinct from main canvas but without adding chromaticism |
| Cloud White | `#eeeeee` | `--color-cloud-white` | Background for secondary images or distinct button states, a slightly muted white for soft separation |
| Medium Gray | `#808080` | `--color-medium-gray` | Muted helper text, secondary body copy, less prominent borders. Reduces visual hierarchy subtly |
| Dark Gray | `#595959` | `--color-dark-gray` | Placeholder text in search inputs, outline borders for ghost buttons, secondary navigation text. Stronger than Medium Gray but not as dominant as Pitch Black |
| Charcoal | `#333333` | `--color-charcoal` | Background for specific interactive buttons (e.g., app store links), providing a soft alternative to Pitch Black |
| Electric Blue | `#0000FE` | `--color-electric-blue` | Informational highlights, occasional link accents (derived from `--blue` token) |

## Tokens — Typography

### Favorit — Versatile workhorse typeface for all body text, navigation, and most interactive elements. Its slight monospace character and geometric structure provide a technical yet friendly tone. · `--font-favorit`
- **Substitute:** Inter
- **Weights:** 350, 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 28px
- **Line height:** 1.15, 1.19, 1.21, 1.22, 1.25, 1.33, 1.40, 1.50
- **Letter spacing:** 0.0600em
- **OpenType features:** `"ss02", "ss03", "ss05", "ss06", "ss08"`
- **Role:** Versatile workhorse typeface for all body text, navigation, and most interactive elements. Its slight monospace character and geometric structure provide a technical yet friendly tone.

### Foggy — The primary display font for oversized headlines. Its compressed, heavy form creates an immediate, impactful statement, giving major headings a declarative, almost poster-like presence. Low line height creates tight stacks. · `--font-foggy`
- **Substitute:** Impact
- **Weights:** 400
- **Sizes:** 106px
- **Line height:** 0.83
- **Letter spacing:** normal
- **OpenType features:** `"ss02", "ss03", "ss05", "ss06", "ss08"`
- **Role:** The primary display font for oversized headlines. Its compressed, heavy form creates an immediate, impactful statement, giving major headings a declarative, almost poster-like presence. Low line height creates tight stacks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.25 | — | `--text-caption` |
| body-sm | 14px | 1.25 | — | `--text-body-sm` |
| body | 16px | 1.25 | — | `--text-body` |
| body-lg | 18px | 1.25 | — | `--text-body-lg` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 28px | 1.25 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 20px |
| cards | 4px |
| images | 8px |
| buttons | 40px |
| navigation | 20px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled button with Pitch Black background, Arctic White text (Favorit, weight 400), and a large 40px border-radius, giving it a soft, pill-shaped aesthetic. Padding 22px horizontal, implied vertical from inherent height.

### Secondary Ghost Button
**Role:** Alternative actions or less prominent calls

Ghost button with a border of Dark Gray (#595959), transparent background, and 20px border-radius. Text in Dark Gray (#595959), Favorit font. Padding 8px vertical, 16px horizontal.

### SearchBar Input
**Role:** Global site search and filtering

Input field with a Pitch Black text, Dark Gray (#595959) placeholder text, and Arctic White background. Features a soft, rounded 20px border-radius and a full-height appearance.

### Event Card
**Role:** Displaying event listings

Cards have a simple 4px border-radius and transparent background, relying on content and imagery for definition. Text (Favorit, multiple weights/sizes) is Pitch Black by default. Image backgrounds can be Cloud White (#eeeeee).

### App Download Button
**Role:** Link to app stores

Filled button with Charcoal (#333333) background and Arctic White text (Favorit, weight 400). Features a 20px border-radius and 8px vertical / 16px horizontal padding.

### Pill Navigation Item
**Role:** Navigation links within headers or footers

Text link or button with a 20px border-radius, often with Pitch Black text on Arctic White background, or Arctic White text on Pitch Black for active states. Implicit horizontal padding from text content.

## Do's and Don'ts

### Do
- Prioritize high contrast between primary foreground (Pitch Black) and background (Arctic White).
- Use Foggy exclusively for large, impactful headlines (106px at 0.83 line height) to maintain its declarative visual weight.
- Apply Favorit at 0.0600em letter-spacing universally for body, navigation, and interactive text to maintain the characteristic density.
- Utilize 40px border-radius for all primary action buttons, ensuring a consistent pill-shaped interaction target.
- Employ the 8px base unit for consistent element spacing where individual elements require small buffers.
- Introduce accent colors (Neon Green, Electric Blue) sparingly, reserving them for functional states, icons, or crucial brand highlights.
- Keep card and section backgrounds flat and monochrome (Arctic White or Ash Gray) to support the content without distraction.

### Don't
- Avoid using Foggy for body copy or small text — its legibility is optimized for large display sizes.
- Do not introduce soft shadows or gradients for primary surface elevation; rely on high-contrast color shifts and borders.
- Refrain from using strong chromatic colors for backgrounds or large UI areas; maintain the black-and-white dominance.
- Do not deviate from the specified Favorit font feature settings ("ss02", "ss03", "ss05", "ss06", "ss08") as they are integral to the brand's typographic identity.
- Avoid arbitrary padding or margin values; adhere to the 4px base unit and derived spacing tokens like 8px for element gaps and 24px for section gaps.
- Do not use multiple, distinct border-radius values on elements of the same type; buttons should consistently be 40px radius, cards 4px, etc.

## Imagery

The visual language predominantly features high-contrast product screenshots (like the phone UI) with clean, sharp edges, often against solid Pitch Black or Arctic White backgrounds. Illustrations are minimalistic and abstract, using thick outlines and primarily black-and-white palettes, occasionally highlighted with a single vivid accent color like Neon Green. Icons are solid, bold, and monoline, conveying clarity and directness. Imagery serves to showcase product functionality or add a distinctive brand personality through abstract, almost 'sticker-like' graphic elements. It's an image-rich but text-dominant system, where images provide visual breaks and emphasis without overwhelming the content.

## Layout

The page structure is primarily max-width contained for content sections, but utilizes full-bleed hero and footer sections that extend edge-to-edge. The hero section often presents a split layout: a dominant, oversized headline and supporting text on one side, paired with a large product visual (e.g., a phone UI) on the other. Content sections typically flow with consistent vertical spacing (24px section gaps), often displaying card grids (e.g., event listings with 3-5 columns) or feature lists. Navigation is a sticky top bar with clear text links and a prominent Primary Action Button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #4BFA94
primary action: #000000 (filled action)

Example Component Prompts:
Create a hero section: full-bleed Pitch Black (#000000) background. Headline 'WELCOME TO THE ALTERNATIVE' in Foggy, 106px, weight 400, color Arctic White (#ffffff), line-height 0.83. Subtext 'Incredible live shows. Upfront pricing. Relevant recommendations. DICE makes going out easy.' in Favorit, 18px, weight 400, color Arctic White (#ffffff), line-height calc(18px * 1.5). Below, a Primary Action Button labeled 'GET THE APP' (Pitch Black background, Arctic White text, 40px radius).

Create a secondary ghost button for 'Browse events': 2px solid border in Dark Gray (#595959), transparent background. Text 'Browse events' in Favorit, 16px, weight 400, color Dark Gray (#595959). Padding 8px vertical, 16px horizontal, 20px border-radius.

Create an event card: Arctic White (#ffffff) background, 4px border-radius. Image background 'Cloud White' (#eeeeee) with 8px border-radius. Event title in Favorit, 18px, weight 700, color Pitch Black (#000000). Event details in Favorit, 14px, weight 400, color Pitch Black (#000000).

## Similar Brands

- **Resident Advisor** — Monochrome aesthetic with strong typography and minimal UI elements.
- **Boiler Room** — Focus on music events, black-and-white branding with occasional neon accents.
- **Mixmag** — Bold, condensed display typography and strong visual impact using limited color.
- **Songkick** — Direct, functional UI for event discovery, prioritizing content over decorative elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-arctic-white: #ffffff;
  --color-ash-gray: #d9d9d9;
  --color-cloud-white: #eeeeee;
  --color-medium-gray: #808080;
  --color-dark-gray: #595959;
  --color-charcoal: #333333;
  --color-electric-blue: #0000FE;

  /* Typography — Font Families */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-foggy: 'Foggy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-body-lg: 18px;
  --leading-body-lg: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;

  /* Typography — Weights */
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-misc: 20px;
  --radius-cards: 4px;
  --radius-images: 8px;
  --radius-buttons: 40px;
  --radius-navigation: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-arctic-white: #ffffff;
  --color-ash-gray: #d9d9d9;
  --color-cloud-white: #eeeeee;
  --color-medium-gray: #808080;
  --color-dark-gray: #595959;
  --color-charcoal: #333333;
  --color-electric-blue: #0000FE;

  /* Typography */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-foggy: 'Foggy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.25;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-body-lg: 18px;
  --leading-body-lg: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 100px;
}
```
