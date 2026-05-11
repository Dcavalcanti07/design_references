# Empower — Style Reference
> midnight command center, bright button

**Theme:** mixed

Tilt communicates a direct, no-nonsense financial brand with a strong visual identity built on bold, condensed typography and a high-contrast dark theme punctuated by a vibrant, optimistic yellow. Components are lightweight and purposeful, relying on shape and color to convey hierarchy rather than heavy shadows. The overall aesthetic is one of confident utility, where key actions are highlighted by bright accents against a dominant dark canvas, switching to a clean light background for content-heavy sections.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Night Sky | `#100f0f` | `--color-night-sky` | Page background (dark sections), primary dark text, button text on accent backgrounds, footer background |
| Canvas White | `#ffffff` | `--color-canvas-white` | Background for light sections, card surfaces, button text on dark backgrounds |
| Cloud Whisper | `#fffdf6` | `--color-cloud-whisper` | Subtle light background texture, secondary light text, ghost button borders in dark sections |
| Deep Space | `#171616` | `--color-deep-space` | Primary dark background for hero sections and prominent blocks |
| Charcoal Card | `#262525` | `--color-charcoal-card` | Dark card backgrounds within dark sections |
| Metal Gray | `#64635c` | `--color-metal-gray` | Subtle borders, tertiary text for helper messages and captions |
| Button Yellow | `#e4e24e` | `--color-button-yellow` | Primary action buttons, interactive elements, accent highlights — a vivid spark against dark and light themes |
| Muted Yellow | `#faf9b6` | `--color-muted-yellow` | Subtle background for UI elements like cards or secondary highlights |

## Tokens — Typography

### GTAmericaExtended — Primary body text, links, navigation items, and some smaller headings. Its extended width gives a distinctive, confident character to text. · `--font-gtamericaextended`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 11px, 13px, 16px, 18px, 20px, 21px, 26px
- **Line height:** 1.20, 1.27, 1.33, 1.38, 1.48, 1.50
- **Letter spacing:** -0.0300em (at 26px), -0.0280em (at 21px), -0.0190em (at 18px), -0.0150em (at 16px)
- **OpenType features:** `"dlig"`
- **Role:** Primary body text, links, navigation items, and some smaller headings. Its extended width gives a distinctive, confident character to text.

### GTAmericaExpanded — Used for specific button labels and navigation, the expanded width adds emphasis without increasing weight. · `--font-gtamericaexpanded`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px, 16px
- **Line height:** 1.50, 1.54, 1.82
- **Letter spacing:** -0.0230em (at 16px), -0.0190em (at 13px), 0.0940em (at 12px), 0.1000em (at 11px)
- **Role:** Used for specific button labels and navigation, the expanded width adds emphasis without increasing weight.

### Gravity — Primary display font for hero headlines and impactful statements. Its bold presence and extremely tight letter-spacing create an assertive, almost digital feel. · `--font-gravity`
- **Substitute:** Poppins
- **Weights:** 400, 900
- **Sizes:** 16px, 24px, 40px, 48px, 96px, 205px
- **Line height:** 1.00, 1.50
- **Letter spacing:** -0.0210em (at 205px), -0.0100em (at 96px), -0.0060em (at 48px)
- **OpenType features:** `"dlig"`
- **Role:** Primary display font for hero headlines and impactful statements. Its bold presence and extremely tight letter-spacing create an assertive, almost digital feel.

### EmpowerSerif — Secondary display font for large expressive headings, contrasting Gravity with its serif structure but maintaining a strong, direct presence. · `--font-empowerserif`
- **Substitute:** Playfair Display
- **Weights:** 400, 600
- **Sizes:** 16px, 40px, 96px, 205px
- **Line height:** 1.00, 1.50
- **Letter spacing:** -0.0060em (at 205px), -0.0050em (at 96px)
- **Role:** Secondary display font for large expressive headings, contrasting Gravity with its serif structure but maintaining a strong, direct presence.

### GTAmericaExtendedMedium — Used for prominent subheadings, offering a slightly bolder alternative to GTAmericaExtended for increased hierarchy without resorting to heavier display fonts. · `--font-gtamericaextendedmedium`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 36px
- **Line height:** 1.11
- **Letter spacing:** -0.0070em
- **Role:** Used for prominent subheadings, offering a slightly bolder alternative to GTAmericaExtended for increased hierarchy without resorting to heavier display fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 1.1px | `--text-caption` |
| body | 16px | 1.33 | -0.24px | `--text-body` |
| subheading | 26px | 1.2 | -0.78px | `--text-subheading` |
| heading-sm | 36px | 1.11 | -0.252px | `--text-heading-sm` |
| heading | 40px | 1 | -0.24px | `--text-heading` |
| heading-lg | 48px | 1.5 | -0.288px | `--text-heading-lg` |
| display | 96px | 1 | -0.96px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 16777216px |
| modules | 16px |

### Layout

- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action across the site.

Filled button with Button Yellow (#e4e24e) background, Night Sky (#100f0f) text (GTAmericaExpanded, weight 400), and a large border-radius (effectively pill-shaped). Padding is 8px vertical, 16px horizontal.

### Ghost Navigation Button
**Role:** Secondary action or navigation in dark sections.

Transparent background, Cloud Whisper (#fffdf6) text (GTAmericaExtended, weight 400), thin Cloud Whisper (#fffdf6) border, large border-radius (effectively pill-shaped). Padding is 8px vertical, 16px horizontal.

### Ghost Secondary Button
**Role:** Clickable elements requiring less emphasis, often in light sections.

Transparent background, Night Sky (#100f0f) text (GTAmericaExtended, weight 400), thin Night Sky (#100f0f) border, large border-radius (effectively pill-shaped). Padding is 20px all around.

### Dark Photo Card
**Role:** Displaying imagery with associated monetary values against a dark background.

Charcoal Card (#262525) background, 24px border-radius, no shadow. Padding 8px horizontal, 40px bottom relative to content framing imagery at top.

### Light Content Card
**Role:** General content display in light sections.

Cloud Whisper (#fffdf6) background, 16px border-radius, no shadow. Padding 32px top, 24px horizontal, 24px bottom.

### Muted Yellow Content Card
**Role:** Highlighting specific content blocks with a soft accent hue.

Muted Yellow (#faf9b6) background, 24px border-radius, no shadow. Padding 32px all around.

## Do's and Don'ts

### Do
- Use Night Sky (#100f0f) as the primary dark background for main page sections.
- Apply Button Yellow (#e4e24e) exclusively for primary interactive elements, ensuring its vibrancy draws attention.
- For headlines, select Gravity (weight 900) or EmpowerSerif (weight 600) with their specific tight letter-spacing for maximum impact.
- Maintain a large, effectively pill-shaped border-radius for all primary buttons, visually communicating interaction.
- Structure information using a strong contrast between Night Sky (#100f0f) and Canvas White (#ffffff) sections for clear visual separation.
- Employ GTAmericaExtended for body text and navigation, capitalizing on its extended character for a distinctive textual rhythm.
- Use a minimum of 24px border-radius for cards and modules, lending a friendly but structured appearance.

### Don't
- Do not introduce new saturated accent colors; limit accents to shades of yellow.
- Avoid applying heavy drop shadows; cards and elements should primarily rely on background color and border-radius for definition.
- Do not use generic system fonts for any headline or prominent text; stick to the custom font stack for brand consistency.
- Never use Button Yellow (#e4e24e) for text; it is reserved for backgrounds of interactive elements.
- Avoid breaking button styles by using square corners for primary calls to action; always use the large border-radius.
- Do not vary paragraph or body text letter-spacing from the tokenized GTAmericaExtended values, especially for smaller sizes.
- Refrain from using thin light lines on dark backgrounds unless specified as Ghost Button borders or subtle dividers.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Night Sky | `#100f0f` | Primary dark background for the highest level of UI, particularly navigation and footer. |
| 2 | Deep Space | `#171616` | Dominant background for hero sections and expansive dark content blocks, creating depth while maintaining darkness. |
| 3 | Canvas White | `#ffffff` | Background for light feature sections, providing a stark contrast to dark areas and improving readability for dense content. |
| 4 | Cloud Whisper | `#fffdf6` | Subtle light surface within light sections, used for cards or content blocks to create a slight separation without strong borders. |
| 5 | Muted Yellow | `#faf9b6` | Accent surface for specific cards or callouts, offering a soft visual highlight. |

## Imagery

The site heavily features photography of diverse individuals, often presented within circular or rounded containers. Imagery is typically lifestyle-oriented, focusing on people in everyday situations, implying relatability and broad accessibility. Product screenshots occasionally appear, mainly for mobile UI, showcasing a clean and focused interface with brand colors. Icons are outlined, simple, and monochrome, primarily acting as functional indicators rather than decorative elements. Image density is moderate, carefully balanced with bold typography, and serves to humanize the financial services offered.

## Layout

The page exhibits a mixed layout, starting with a full-bleed dark hero section featuring a centered headline. Following sections often alternate between dark and light backgrounds, creating a distinct vertical rhythm. Content is typically arranged in centered stacks or two-column text-left/image-right patterns. A prominent feature is the use of image grids with rounded-corner photo cards. The navigation is a fixed top bar on dark background for clarity, with a maximum content width that appears to be contained within around 1200px after the initial full-bleed hero.

## Agent Prompt Guide

Quick Color Reference:
text: #100f0f
background: #100f0f (dark sections), #ffffff (light sections)
border: #64635c
accent: #e4e24e
primary action: #e4e24e (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #e4e24e background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card for a light section: Cloud Whisper (#fffdf6) background, 16px radius, with a GTAmericaExtended weight 400 headline at 26px and regular GTAmericaExtended body text, both in Night Sky (#100f0f). Add 32px padding all around.
3. Build a navigation bar item: Night Sky (#100f0f) background, GTAmericaExtended weight 400 text at 16px in Cloud Whisper (#fffdf6), and on hover, use a ghost button style with a Cloud Whisper (#fffdf6) border.

## Similar Brands

- **Stripe** — High-contrast dark UIs with bold, angular sans-serif typography and minimal use of accent colors for functional elements.
- **Ramp** — Financial tech that employs a mix of contrasting light and dark sections and strong, condensed display fonts.
- **Mercury Bank** — Modern fintech aesthetic with clean layouts, focused accent colors, and a strong emphasis on typography for brand voice.
- **Wise (formerly TransferWise)** — Direct communication style, functional use of a single strong accent color, and a balance of informational density with clear visual hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-night-sky: #100f0f;
  --color-canvas-white: #ffffff;
  --color-cloud-whisper: #fffdf6;
  --color-deep-space: #171616;
  --color-charcoal-card: #262525;
  --color-metal-gray: #64635c;
  --color-button-yellow: #e4e24e;
  --color-muted-yellow: #faf9b6;

  /* Typography — Font Families */
  --font-gtamericaextended: 'GTAmericaExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtamericaexpanded: 'GTAmericaExpanded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gravity: 'Gravity', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-empowerserif: 'EmpowerSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-gtamericaextendedmedium: 'GTAmericaExtendedMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 1.1px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: -0.24px;
  --text-subheading: 26px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.78px;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.11;
  --tracking-heading-sm: -0.252px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.24px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.5;
  --tracking-heading-lg: -0.288px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 16777216px;
  --radius-modules: 16px;

  /* Surfaces */
  --surface-night-sky: #100f0f;
  --surface-deep-space: #171616;
  --surface-canvas-white: #ffffff;
  --surface-cloud-whisper: #fffdf6;
  --surface-muted-yellow: #faf9b6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-night-sky: #100f0f;
  --color-canvas-white: #ffffff;
  --color-cloud-whisper: #fffdf6;
  --color-deep-space: #171616;
  --color-charcoal-card: #262525;
  --color-metal-gray: #64635c;
  --color-button-yellow: #e4e24e;
  --color-muted-yellow: #faf9b6;

  /* Typography */
  --font-gtamericaextended: 'GTAmericaExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtamericaexpanded: 'GTAmericaExpanded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gravity: 'Gravity', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-empowerserif: 'EmpowerSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-gtamericaextendedmedium: 'GTAmericaExtendedMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 1.1px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: -0.24px;
  --text-subheading: 26px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.78px;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.11;
  --tracking-heading-sm: -0.252px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.24px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.5;
  --tracking-heading-lg: -0.288px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
}
```
