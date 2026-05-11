# LaunchDarkly — Style Reference
> Midnight Terminal, Violet Haze

**Theme:** dark

LaunchDarkly employs a dark, almost charcoal canvas paired with crisp white text to evoke a serious, technical atmosphere. Accents of vivid violet and electric blue cut through the darkness, signaling interactive elements and key information. Surfaces are softly rounded and slightly elevated, creating a layered, dimensional feel rather than a flat interface. Typography is direct and precise, favoring confident body text over overly decorative headlines, establishing authority through clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon Black | `#191919` | `--color-carbon-black` | Primary surface background for cards and buttons, footer regions, and navigation elements. This deep neutral provides the foundational dark aesthetic |
| Graphite | `#414042` | `--color-graphite` | Dominant page background, providing a slightly lighter dark tone for the overall canvas |
| Deep Space Gray | `#2c2c2c` | `--color-deep-space-gray` | Subtle list item borders and dividers, providing a minimal contrast against darker surfaces |
| Mercury White | `#ffffff` | `--color-mercury-white` | Primary text color for headlines and body text on dark backgrounds, input fields, and brand logos. Offers high contrast and readability |
| Stardust Gray | `#f8f8f2` | `--color-stardust-gray` | Secondary text on some dark surfaces, a slightly warmer off-white for subtle variation |
| Cadet Gray | `#a7a9ac` | `--color-cadet-gray` | Muted body text and subheadings, providing a softer contrast than Mercury White while remaining legible |
| Silver Mist | `#d1d3d4` | `--color-silver-mist` | Tertiary body text, icon borders, and subtle list item text, for less prominent information |
| Input Gray | `#58595b` | `--color-input-gray` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Launch Violet | `#7084ff` | `--color-launch-violet` | Interactive link text and borders, decorative icon accents, and outlined buttons, creating a vibrant focal point |
| Orbital Blue | `linear-gradient(179deg, rgb(64, 91, 255) 1.06%, rgb(112, 132, 255) 123.42%)` | `--color-orbital-blue` | Background for selected states and subtle box shadows, providing a cohesive secondary accent |
| Electric Cyan | `linear-gradient(225deg, rgb(64, 91, 255) -5.3%, rgb(61, 214, 245) 112.86%)` | `--color-electric-cyan` | Highlight accents within gradients for visual distinction |
| Ocean Blue | `#0073e6` | `--color-ocean-blue` | Specific navigation link text, offering a deeper blue variant for certain UI elements |

## Tokens — Typography

### bodyFont — The primary typeface for all body text, navigation items, and most UI elements. Its range of weights and sizes supports a clear information hierarchy without resorting to multiple font families. Default letter spacing is normal for readability, but can be adjusted for specific titles. · `--font-bodyfont`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 26px, 28px, 32px, 36px, 40px, 66px, 84px, 85px, 100px, 125px
- **Line height:** 1.00, 1.09, 1.20, 1.30, 1.40, 1.50, 1.60, 1.71
- **Letter spacing:** 0.1290em, 0.1670em
- **Role:** The primary typeface for all body text, navigation items, and most UI elements. Its range of weights and sizes supports a clear information hierarchy without resorting to multiple font families. Default letter spacing is normal for readability, but can be adjusted for specific titles.

### bodyFont — Used for bolding in body copy, and occasionally for sub-headings or emphasized text in UI elements. · `--font-bodyfont`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 26px, 28px, 32px, 36px, 40px, 66px, 84px, 85px, 100px, 125px
- **Line height:** 1.00, 1.09, 1.20, 1.30, 1.40, 1.50, 1.60, 1.71
- **Letter spacing:** 0.1290em, 0.1670em
- **Role:** Used for bolding in body copy, and occasionally for sub-headings or emphasized text in UI elements.

### bodyFont — Emphasized headlines and crucial information that requires more visual weight without being heavy. Carries key messages in a strong, clear voice against dark backgrounds. · `--font-bodyfont`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 26px, 28px, 32px, 36px, 40px, 66px, 84px, 85px, 100px, 125px
- **Line height:** 1.00, 1.09, 1.20, 1.30, 1.40, 1.50, 1.60, 1.71
- **Letter spacing:** 0.1290em, 0.1670em
- **Role:** Emphasized headlines and crucial information that requires more visual weight without being heavy. Carries key messages in a strong, clear voice against dark backgrounds.

### bodyFont — Used for button text and other elements that require maximum emphasis and distinctness in a functional context. · `--font-bodyfont`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 26px, 28px, 32px, 36px, 40px, 66px, 84px, 85px, 100px, 125px
- **Line height:** 1.00, 1.09, 1.20, 1.30, 1.40, 1.50, 1.60, 1.71
- **Letter spacing:** 0.1290em, 0.1670em
- **Role:** Used for button text and other elements that require maximum emphasis and distinctness in a functional context.

### monoFont — For code snippets and technical displays, providing precise character alignment for improved readability in a development context. · `--font-monofont`
- **Substitute:** Menlo, Consolas, monospace
- **Weights:** 400
- **Sizes:** 16px, 20px, 22px
- **Line height:** 1.09, 1.50, 1.65
- **Role:** For code snippets and technical displays, providing precise character alignment for improved readability in a development context.

### headingFont1 — Single-use extremely large hero headline, providing impactful visual scale without excessive weight, reinforcing modern authority. · `--font-headingfont1`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 125px
- **Line height:** 1.00
- **Role:** Single-use extremely large hero headline, providing impactful visual scale without excessive weight, reinforcing modern authority.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Helvetica — Helvetica — detected in extracted data but not described by AI · `--font-helvetica`
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.5
- **Letter spacing:** 0.007
- **Role:** Helvetica — detected in extracted data but not described by AI

### Sohne — Sohne — detected in extracted data but not described by AI · `--font-sohne`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** Sohne — detected in extracted data but not described by AI

### Sohne Mono — Sohne Mono — detected in extracted data but not described by AI · `--font-sohne-mono`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** Sohne Mono — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 18px | 1.4 | — | `--text-body` |
| body-lg | 22px | 1.4 | — | `--text-body-lg` |
| heading-sm | 26px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | — | `--text-heading` |
| heading-lg | 66px | 1.3 | — | `--text-heading-lg` |
| display-sm | 85px | 1.3 | — | `--text-display-sm` |
| display | 125px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 60px |
| cards | 30px |
| input | 10px |
| buttons | 30px |
| navigation | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.45) 0px 4px 20px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1188px
- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Navigation Link
**Role:** Top navigation items with ghost styling

Background transparent, text 'Mercury White' (#ffffff), no border, 0px radius, 0px padding. Active state uses 'Launch Violet' (#7084ff) text.

### Primary Action Button
**Role:** Calls to action with filled background

Background 'Carbon Black' (#191919), text 'Mercury White' (#ffffff), 30px border-radius, 40px horizontal padding, 40px vertical padding. Used for the prominent 'Get a demo' button.

### Outlined Action Button
**Role:** Secondary action buttons with a border

Background transparent, text 'Mercury White' (#ffffff), border is 1px solid 'Launch Violet' (#7084ff), 60px border-radius, 38px horizontal padding, 16px vertical padding. Used for 'Get started' in the hero.

### Toggle Button
**Role:** Segmented control option

Background transparent, text 'Mercury White' (#ffffff), 30px border-radius, 24px horizontal padding, 10px vertical padding. Active state has a 'Carbon Black' (#191919) background and 'Launch Violet' (#7084ff) text.

### Feature Card
**Role:** Container for feature descriptions or callouts

Background transparent or 'Carbon Black' (#191919), border 1px solid 'Graphite' (#414042), 30px border-radius, 32px horizontal padding, 40px top padding, 24px bottom padding. Provides a subtle visual grouping.

### Input Field
**Role:** User input area

Background 'Mercury White' (#ffffff), text 'Input Gray' (#58595b), border 1px solid 'Input Gray' (#58595b), 10px border-radius (left side) and 0px (right side) for a compound input. 16px horizontal padding, 11px vertical padding.

## Do's and Don'ts

### Do
- Prioritize 'Mercury White' (#ffffff) for all main headings and body text on dark backgrounds to ensure legibility.
- Use 'Launch Violet' (#7084ff) as the primary accent for interactive elements like links and outlined buttons.
- Apply a 30px border-radius to cards and primary action buttons, and 60px to ghost/outlined buttons for a consistent rounded aesthetic.
- Maintain a clear visual hierarchy using 'Graphite' (#414042) for page backgrounds and 'Carbon Black' (#191919) for card/component surfaces.
- Structure content with 16px element gaps and 32px section gaps to provide comfortable density and readability.
- Employ the `monoFont` family for all code snippets and technical examples to differentiate them visually.
- Apply the `rgba(0, 0, 0, 0.45) 0px 4px 20px 0px` shadow only to the main navigation for subtle elevation against the dark background.

### Don't
- Avoid using highly saturated colors for large background areas; reserve chromatic colors for small accent details.
- Do not introduce new border radii beyond 4px, 10px, 30px, 40px, or 60px.
- Never use the `headingFont1` for body text or sub-headings; reserve it strictly for monumental hero headlines.
- Refrain from using hard, sharp corners; all UI interactives and containers should use specified border radii.
- Do not deviate from the specified 'Graphite' (#414042) or 'Carbon Black' (#191919) as primary dark backgrounds.
- Avoid multiple drop shadows on elements; elevation signals should be subtle and singular.
- Do not use generic system fonts when `bodyFont` or `monoFont` are available and semantically appropriate.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Graphite | `#414042` | Base page background |
| 1 | Carbon Black | `#191919` | Card and button backgrounds, Footer |
| 2 | Deep Space Gray | `#2c2c2c` | Subtle border/divider on cards |

## Elevation

- **Navigation Bar:** `rgba(0, 0, 0, 0.45) 0px 4px 20px 0px`

## Imagery

This system primarily uses iconography and UI elements rather than large photographic or illustrative imagery. When present, images like product screenshots are contained within cards with rounded corners. Small, functional icons are typically monochrome or leverage the 'Launch Violet' accent. There is a strong emphasis on clean, legible UI over decorative visuals, with gradients used as a subtle background treatment rather than a primary visual element.

## Layout

The page maintains a centered, max-width layout of 1188px, with a full-bleed dark hero area that establishes the brand tone. Sections are vertically stacked with consistent 32px gaps. Content often alternates between left-aligned text and right-aligned visuals (or vice-versa) in a two-column arrangement. Feature lists are presented with clear checkmarks and subtle card containers. The overall density is comfortable, ensuring information is digestible without feeling sparse, and the fixed top navigation maintains context.

## Agent Prompt Guide

### Quick Color Reference
text: #ffffff
background: #414042
border: #414042
accent: #7084ff
primary action: #191919 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #191919 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create an `Outlined Action Button` with the label 'Get started'. It should have a transparent background, 'Mercury White' text, a 1px solid 'Launch Violet' border, 60px border-radius, and 38px horizontal padding with 16px vertical padding. Font should be `bodyFont` weight 700, 16px.
3. Design a `Feature Card` with a transparent background over the main page background. It should have a 1px solid 'Graphite' (#414042) border, 30px border-radius, 32px horizontal padding, 40px top padding, and 24px bottom padding. Include a header in 'Mercury White' using `bodyFont` weight 500 at 22px and body text in 'Cadet Gray' using `bodyFont` weight 400 at 16px.
4. Create a `Toggle Button` for a segmented control. The inactive state should have a transparent background, 'Mercury White' (#ffffff) text, 30px border-radius, and 24px horizontal and 10px vertical padding. The active state should have a 'Carbon Black' (#191919) background and 'Launch Violet' (#7084ff) text.
5. Generate an `Input Field` with placeholder text 'Email address'. It should have a 'Mercury White' (#ffffff) background, 'Input Gray' (#58595b) text, a 1px solid 'Input Gray' (#58595b) border, with a 10px `radius.input` applied to the left corners and 0px to the right corners. Include 16px horizontal and 11px vertical padding.

## Similar Brands

- **Darklang** — Shares a similar dark-mode interface with a focus on developer tools and abstract, subtle gradient backgrounds.
- **Vercel** — Utilizes a dark, technical aesthetic with white typography and a strong emphasis on product UI and code examples.
- **Auth0** — Exhibits a dark theme with structured layouts, clear typography, and strategic use of a single accent color for calls to action.
- **Linear** — Features a dark, minimalist UI, precise typography, and a subtle but effective use of accent colors for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon-black: #191919;
  --color-graphite: #414042;
  --color-deep-space-gray: #2c2c2c;
  --color-mercury-white: #ffffff;
  --color-stardust-gray: #f8f8f2;
  --color-cadet-gray: #a7a9ac;
  --color-silver-mist: #d1d3d4;
  --color-input-gray: #58595b;
  --color-launch-violet: #7084ff;
  --color-orbital-blue: #405bff;
  --gradient-orbital-blue: linear-gradient(179deg, rgb(64, 91, 255) 1.06%, rgb(112, 132, 255) 123.42%);
  --color-electric-cyan: #61d6f5;
  --gradient-electric-cyan: linear-gradient(225deg, rgb(64, 91, 255) -5.3%, rgb(61, 214, 245) 112.86%);
  --color-ocean-blue: #0073e6;

  /* Typography — Font Families */
  --font-bodyfont: 'bodyFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monofont: 'monoFont', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-headingfont1: 'headingFont1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne-mono: 'Sohne Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-body-lg: 22px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 66px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 85px;
  --leading-display-sm: 1.3;
  --text-display: 125px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1188px;
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 46px;
  --radius-full: 60px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-tags: 60px;
  --radius-cards: 30px;
  --radius-input: 10px;
  --radius-buttons: 30px;
  --radius-navigation: 4px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.45) 0px 4px 20px 0px;

  /* Surfaces */
  --surface-graphite: #414042;
  --surface-carbon-black: #191919;
  --surface-deep-space-gray: #2c2c2c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon-black: #191919;
  --color-graphite: #414042;
  --color-deep-space-gray: #2c2c2c;
  --color-mercury-white: #ffffff;
  --color-stardust-gray: #f8f8f2;
  --color-cadet-gray: #a7a9ac;
  --color-silver-mist: #d1d3d4;
  --color-input-gray: #58595b;
  --color-launch-violet: #7084ff;
  --color-orbital-blue: #405bff;
  --color-electric-cyan: #61d6f5;
  --color-ocean-blue: #0073e6;

  /* Typography */
  --font-bodyfont: 'bodyFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monofont: 'monoFont', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-headingfont1: 'headingFont1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne-mono: 'Sohne Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-body-lg: 22px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 66px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 85px;
  --leading-display-sm: 1.3;
  --text-display: 125px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 46px;
  --radius-full: 60px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.45) 0px 4px 20px 0px;
}
```
