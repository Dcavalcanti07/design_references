# Flecto — Style Reference
> Rounded emerald portal

**Theme:** light

Flecto employs a high-contrast dark green canvas accented by a vibrant, energetic lighter green for key interactive elements. Rounded corners are ubiquitous, creating a soft, approachable aesthetic for sections and components. Typography is crisp and modern, featuring custom sans-serif fonts with subtle letter-spacing variations to enhance legibility and visual rhythm. The overall impression is one of structured friendliness, with clear visual hierarchy driven by color and shape rather than complex elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Emerald Canvas | `#004737` | `--color-emerald-canvas` | Teal accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Mint Accent | `#56f09f` | `--color-mint-accent` | Vivid accent color for primary buttons, active states, highlighted cards, and decorative icons. Creates a strong visual focal point against the Emerald Canvas |
| Paper White | `#fffbec` | `--color-paper-white` | Secondary background for header, select cards, and areas requiring visual separation. Provides a bright contrast to the main canvas |
| Off Black | `#032019` | `--color-off-black` | Primary text color for dark backgrounds, dark footer elements, and some borders |
| Soft Mint | `#d4ffe8` | `--color-soft-mint` | Lighter accent for ghost button borders, subtle highlights, and background washes. Provides a softer interaction point than Mint Accent |
| Muted Sage | `#99b5af` | `--color-muted-sage` | Secondary text color, muted icon details, and borders for inactive list items |
| Cream Card | `#faf2d5` | `--color-cream-card` | Subtle background for specific cards, offering a warmer neutral alternative to Paper White |
| Deep Violet | `#8f37ff` | `--color-deep-violet` | Decorative accent color, used for specific data points or icon strokes to provide a punch of distinct hue |
| True Black | `#000000` | `--color-true-black` | Icon fills and very subtle borders on white backgrounds |
| Pure White | `#ffffff` | `--color-pure-white` | Primary page canvas and white card surfaces. Do not promote it to the primary CTA color |
| Dark Wolf | `#222222` | `--color-dark-wolf` | Default text on light backgrounds and borders for some neutral ghost buttons |
| Grey Shadow | `#ccdad7` | `--color-grey-shadow` | Delicate borders and subtle background tints, often seen around elements on light surfaces |
| Stone Grey | `#939393` | `--color-stone-grey` | Muted text or placeholder text in light contexts |
| Light Moss | `#afc5c0` | `--color-light-moss` | Subtle background or border color in content areas |

## Tokens — Typography

### Aeonik — Primary display and body font, used for most headings, prominent text, and UI elements. The `tnum` feature ensures uniform numbers, while the varied letter-spacing provides a distinct, modern texture to headlines and smaller text alike. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 19px, 20px, 24px, 26px, 28px, 32px, 33px, 36px, 56px, 60px, 64px, 66px, 74px
- **Line height:** 1.00, 1.10, 1.14, 1.15, 1.20, 1.22, 1.23, 1.29, 1.30, 1.38, 1.40, 1.44, 1.46, 1.50, 1.60, 1.67, 1.86, 1.92, 1.94, 2.03, 2.09, 2.12, 2.79, 2.88
- **Letter spacing:** -0.0430em at 74px, -0.0300em at 66px, -0.0200em at 56px, 0.0100em at 12px
- **OpenType features:** `'tnum'`
- **Role:** Primary display and body font, used for most headings, prominent text, and UI elements. The `tnum` feature ensures uniform numbers, while the varied letter-spacing provides a distinct, modern texture to headlines and smaller text alike.

### roobert-regular — Secondary body font for supporting text, navigation items, and descriptive content. Maintains legibility at smaller sizes with standard letter-spacing. · `--font-roobert-regular`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.40, 1.87
- **Letter spacing:** normal
- **Role:** Secondary body font for supporting text, navigation items, and descriptive content. Maintains legibility at smaller sizes with standard letter-spacing.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading | 36px | 1.14 | — | `--text-heading` |
| heading-lg | 56px | 1 | -0.2px | `--text-heading-lg` |
| display | 74px | 1 | -0.43px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 38 | 38px | `--spacing-38` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 60px |
| buttons | 10px |
| default | 19px |
| sections | 40px |
| iconButtons | 100% |
| smallWidgets | 5.76px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.04) 0px 3px 2px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 174px
- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action button for primary actions

Background: Mint Accent (#56f09f), Text: Off Black (#032019), Padding: 12px horizontal, 0px vertical (implied by content height). Border radius: 10px. Uses Aeonik font, weight 400.

### Ghost Button
**Role:** Secondary action or navigation link

Background: transparent (rgba(0,0,0,0)), Text: Dark Wolf (#222222), Border: 1px solid Dark Wolf (#222222), Padding: 0px vertical, 12px-24px horizontal. Border radius: 0px. Uses Aeonik font at 16px.

### Outlined Button (Emerald)
**Role:** Call to action with brand emphasis, but not filled.

Background: transparent (rgba(0,0,0,0)), Text: Emerald Canvas (#004737), Border: 1px solid Emerald Canvas (#004737), Padding: 0px. Border radius: 0px. Uses Aeonik font.

### Outlined Button (Soft Mint)
**Role:** Call to action with subtle brand emphasis, typically on dark backgrounds.

Background: transparent (rgba(0,0,0,0)), Text: Soft Mint (#d4ffe8), Border: 1px solid Soft Mint (#d4ffe8), Padding: 0px. Border radius: 0px. Uses Aeonik font.

### Pill Button (Text)
**Role:** Small, rounded control or category tag.

Background: transparent (rgba(0,0,0,0)), Text: Dark Wolf (#222222), Border: 1px solid Dark Wolf (#222222), Border radius: 100% (full pill shape).

### Basic Card
**Role:** Content container on Paper White backgrounds.

Background: Pure White (#ffffff), Border radius: 10px 0px 0px 10px, Shadow: rgba(0, 0, 0, 0.04) 0px 3px 2px 0px, Padding: 20px vertical, 0px horizontal.

### Highlight Card (Mint)
**Role:** Prominent information card or feature highlight.

Background: Mint Accent (#56f09f), Border radius: 19.2px, no shadow, no explicit padding (assumed content-driven).

### Dark Card (Emerald)
**Role:** Content card on light backgrounds, creating strong contrast.

Background: Emerald Canvas (#004737), Border radius: 14.4px, no shadow, no explicit padding (assumed content-driven).

### Plain Card
**Role:** Simple content grouping without visual emphasis.

Background: transparent (rgba(0,0,0,0)), Border radius: 0px, no shadow, Padding: 28.8px.

## Do's and Don'ts

### Do
- Prioritize Emerald Canvas (#004737) as the dominant background color for full-bleed sections to establish brand identity.
- Use Mint Accent (#56f09f) exclusively for primary calls to action, active indicators, and key highlights to maintain its impact.
- Apply a default border-radius of 19px for most card-like elements and content containers for a consistently soft appearance.
- Use the Aeonik font with varied letter-spacing as outlined in the typography section for all headings and prominent text.
- Ensure interactive components primarily use rounded shapes, with specific radii like 10px for buttons and 40px for larger section containers.
- Design for a 'compact' density, using 10px as the default element gap to group related items closely.
- Prefer outlined buttons using brand colors (Emerald Canvas or Soft Mint) over filled neutral buttons for secondary actions or links.

### Don't
- Avoid using multiple vivid accent colors; restrict strong chromatic accents to Mint Accent (#56f09f).
- Do not break the established rounding pattern; avoid sharp corners for interactive elements or cards unless explicitly part of a decorative shape.
- Do not use generic system fonts for headings; always use Aeonik for brand consistency and its distinct letter-spacing.
- Avoid excessive use of shadows; stick to the rgba(0, 0, 0, 0.04) 0px 3px 2px 0px for discrete card elevation only.
- Do not introduce large, open whitespace between elements; maintain the 'compact' density for optimal information display.
- Avoid using Cream Card (#faf2d5) as a primary background; reserve it for specific card surfaces to provide subtle variation.
- Do not use Emerald Canvas (#004737) for body text on light backgrounds; use Dark Wolf (#222222) instead for readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Emerald Canvas | `#004737` | Primary background for full-width thematic sections and visual anchors. |
| 1 | Paper White | `#fffbec` | Secondary background for header and content sections, creating visual breathing room. |
| 2 | Pure White | `#ffffff` | Elevated card surfaces and interactive element backgrounds on lighter sections. |
| 3 | Cream Card | `#faf2d5` | Specialized card backgrounds offering a warmer, slightly differentiated surface. |

## Elevation

- **Basic Card:** `rgba(0, 0, 0, 0.04) 0px 3px 2px 0px`

## Imagery

This site features abstract, geometric visual elements, particularly a key-like graphic constructed from pixelated blocks. There are no photographs or complex illustrations. Icons are outlined, mono-color, and minimal, matching the clean UI aesthetic. Visual space is dominated by UI elements and typography, with graphics serving primarily as decorative atmosphere and brand representation rather than explanatory content. Image density is low.

## Layout

The page primarily uses a contained layout with a maximum width of 174px for content blocks, centered within the browser. The hero section features a full-bleed Emerald Canvas (#004737) background with a large, centered headline and a graphic. Sections often alternate between full-bleed brand color (Emerald Canvas) and a contained Paper White (#fffbec) or Pure White (#ffffff) background. Vertical section rhythm is consistent, with clear visual breaks between blocks. Content is often arranged in visually distinct blocks that occasionally feature rounded cutouts and overlays. Navigation is a simple top bar with a sticky header and minimal links.

## Agent Prompt Guide

Quick Color Reference: 
text: #032019
background: #004737
border: #004737
accent: #56f09f
primary action: #004737 (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #004737 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Create a Hero Section with Emerald Canvas background: Headline 'Unlock your Potential' in Aeonik, 74px, weight 400, White (#ffffff), letter-spacing -0.43px. Sub-headline 'Your future is now' in Aeonik, 24px, weight 400, Soft Mint (#d4ffe8).
3. Create a Basic Card on Paper White background: Text 'Card Title' in Aeonik, 36px, weight 400, Dark Wolf (#222222). Body text 'Card description here' in roobert-regular, 16px, weight 400, Dark Wolf (#222222). Background Pure White (#ffffff), border-radius 10px 0px 0px 10px, box-shadow rgba(0, 0, 0, 0.04) 0px 3px 2px 0px.
4. Create an Outlined Button (Soft Mint): Background rgba(0,0,0,0), text Soft Mint (#d4ffe8), border 1px solid Soft Mint (#d4ffe8), border-radius 0px. Text 'Learn More' using Aeonik font, weight 400.

## Similar Brands

- **Keyhole** — Shares a strong brand-color focused aesthetic with minimal neutrals, and distinctively rounded interactive elements.
- **Paddle** — Uses bright accent colors against darker backgrounds and has a similar modern, bold typography approach in headlines.
- **Pitch** — Employs clean, structured layouts with a focus on geometric shapes and a limited, high-impact color palette against white or dark canvases.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-emerald-canvas: #004737;
  --color-mint-accent: #56f09f;
  --color-paper-white: #fffbec;
  --color-off-black: #032019;
  --color-soft-mint: #d4ffe8;
  --color-muted-sage: #99b5af;
  --color-cream-card: #faf2d5;
  --color-deep-violet: #8f37ff;
  --color-true-black: #000000;
  --color-pure-white: #ffffff;
  --color-dark-wolf: #222222;
  --color-grey-shadow: #ccdad7;
  --color-stone-grey: #939393;
  --color-light-moss: #afc5c0;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-regular: 'roobert-regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.2px;
  --text-display: 74px;
  --leading-display: 1;
  --tracking-display: -0.43px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-38: 38px;
  --spacing-40: 40px;

  /* Layout */
  --page-max-width: 174px;
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 3.36px;
  --radius-md-2: 5.76px;
  --radius-lg: 10px;
  --radius-xl: 14.4px;
  --radius-2xl: 19px;
  --radius-3xl: 25.4118px;
  --radius-3xl-2: 28.8px;
  --radius-3xl-3: 37px;
  --radius-3xl-4: 40px;
  --radius-3xl-5: 46px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-pill: 60px;
  --radius-buttons: 10px;
  --radius-default: 19px;
  --radius-sections: 40px;
  --radius-iconbuttons: 100%;
  --radius-smallwidgets: 5.76px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 3px 2px 0px;

  /* Surfaces */
  --surface-emerald-canvas: #004737;
  --surface-paper-white: #fffbec;
  --surface-pure-white: #ffffff;
  --surface-cream-card: #faf2d5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-emerald-canvas: #004737;
  --color-mint-accent: #56f09f;
  --color-paper-white: #fffbec;
  --color-off-black: #032019;
  --color-soft-mint: #d4ffe8;
  --color-muted-sage: #99b5af;
  --color-cream-card: #faf2d5;
  --color-deep-violet: #8f37ff;
  --color-true-black: #000000;
  --color-pure-white: #ffffff;
  --color-dark-wolf: #222222;
  --color-grey-shadow: #ccdad7;
  --color-stone-grey: #939393;
  --color-light-moss: #afc5c0;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-regular: 'roobert-regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.2px;
  --text-display: 74px;
  --leading-display: 1;
  --tracking-display: -0.43px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-38: 38px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 3.36px;
  --radius-md-2: 5.76px;
  --radius-lg: 10px;
  --radius-xl: 14.4px;
  --radius-2xl: 19px;
  --radius-3xl: 25.4118px;
  --radius-3xl-2: 28.8px;
  --radius-3xl-3: 37px;
  --radius-3xl-4: 40px;
  --radius-3xl-5: 46px;
  --radius-full: 60px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 3px 2px 0px;
}
```
