# Axelar — Style Reference
> Dark Grid Neon Flux

**Theme:** dark

Axelar projects a secure, institutional presence through a dark mode aesthetic with structural grid patterns and minimalist information display. The UI uses a deep, rich black canvas, accented by a single vibrant orange for primary actions and subtle, jewel-toned highlights for status indicators. Typography is confident and dense, anchoring the precise, almost technical feel. Components feel like robust, segmented elements within a larger system, with sharp edges and subtle internal divisions rather than soft forms or heavy shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Apex | `#04070a` | `--color-midnight-apex` | Page backgrounds, overall canvas, deep section backgrounds and footers |
| Obsidian Surface | `#000000` | `--color-obsidian-surface` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Charcoal Panel | `#0f1214` | `--color-charcoal-panel` | Secondary surface panels, linked background states, and navigation accents |
| Smoke Gray | `#1a1d1f` | `--color-smoke-gray` | Muted text, subtle borders, and placeholder styles in dark contexts |
| Ash Outline | `#676f7a` | `--color-ash-outline` | Subtle icons, secondary borders, and disabled text against dark backgrounds |
| Alabaster Text | `#f0f5fa` | `--color-alabaster-text` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Polar White | `#ffffff` | `--color-polar-white` | Highlight text for high contrast elements, active states, borders on light cards, and decorative elements |
| Amber Thrust | `linear-gradient(270deg, rgb(255, 99, 20) 24%, rgb(255, 61, 0))` | `--color-amber-thrust` | Primary call-to-action buttons, active navigation indicators, and impactful card backgrounds — creates urgency and focus; Subtle gradient for primary actions or brand highlights, from vibrant orange to deep crimson |
| Jade Glow | `#33ffac` | `--color-jade-glow` | Success indicators, glowing accents, and functional badges — a vivid positive feedback color |
| Amethyst Spark | `#ff2ad4` | `--color-amethyst-spark` | Decorative highlights, specific badge labels, or dynamic UI feedback |
| Techno Blue | `#5b76ff` | `--color-techno-blue` | Informational highlights, specific badge labels, or data visualization elements |
| Arctic Current | `#16c4ff` | `--color-arctic-current` | Secondary informational accents, highlighting specific features or status |

## Tokens — Typography

### Clashgrotesk — Headlines, navigation items, and prominent UI text — its confident, wide forms provide a strong, modern voice, especially at larger sizes with tight tracking. · `--font-clashgrotesk`
- **Substitute:** Montserrat
- **Weights:** 500, 600
- **Sizes:** 14px, 16px, 19px, 21px, 28px, 37px, 56px, 70px, 74px
- **Line height:** 1.00, 1.25, 1.50
- **Letter spacing:** -0.033em
- **Role:** Headlines, navigation items, and prominent UI text — its confident, wide forms provide a strong, modern voice, especially at larger sizes with tight tracking.

### Inter — Body text, subheadings, and UI elements where clarity and comfortable readability are paramount, providing a neutral yet robust foundation. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 16px, 19px, 21px
- **Line height:** 1.25
- **Role:** Body text, subheadings, and UI elements where clarity and comfortable readability are paramount, providing a neutral yet robust foundation.

### DM Mono — Badges, code snippets, and meta-information — its monospaced nature evokes a developer-centric, precise interaction with technology. · `--font-dm-mono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 19px
- **Line height:** 1.00, 1.25, 1.33
- **Role:** Badges, code snippets, and meta-information — its monospaced nature evokes a developer-centric, precise interaction with technology.

### F77 Minecraft — Decorative elements or specific stylized text, lending a distinct, pixelated digital aesthetic for unique brand moments. · `--font-f77-minecraft`
- **Substitute:** Pixelify Sans
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.25
- **Letter spacing:** 0.246em
- **Role:** Decorative elements or specific stylized text, lending a distinct, pixelated digital aesthetic for unique brand moments.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | — | `--text-caption` |
| body-sm | 14px | 1.25 | -0.033px | `--text-body-sm` |
| body | 16px | 1.25 | — | `--text-body` |
| subheading | 19px | 1.25 | — | `--text-subheading` |
| heading-sm | 21px | 1.25 | — | `--text-heading-sm` |
| heading | 28px | 1.25 | -0.033px | `--text-heading` |
| heading-lg | 37px | 1.25 | -0.033px | `--text-heading-lg` |
| display-sm | 56px | 1.25 | -0.033px | `--text-display-sm` |
| display | 74px | 1.25 | -0.033px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 9 | 9px | `--spacing-9` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 42 | 42px | `--spacing-42` |
| 43 | 43px | `--spacing-43` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 100px |
| inputs | 24px |
| buttons | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(255, 255, 255) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(225, 230, 235) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |

### Layout

- **Page max-width:** 1584px
- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Highest priority interaction

Filled with Amber Thrust (#ff6314), Polar White (#ffffff) text, 24px border-radius, 12px vertical padding, 24px horizontal padding. A visually dominant, full-bleed button.

### Outline Ghost Button
**Role:** Secondary action or navigation

Transparent background, Polar White (#ffffff) border and text, 24px border-radius, 12px vertical padding, 24px horizontal padding. Offers a clear interactive state without visual heaviness.

### Category Card
**Role:** Grouping related content or trusted brands

Charcoal Panel (#0f1214) background, 8px border-radius. Contains internal content without explicit padding, using child margins for spacing. Borders are often implied by layout.

### Highlight Card
**Role:** Featured content section

Amber Thrust (#ff6314) background, 8px border-radius. Uses 24px padding on all sides, drawing strong visual attention to its content.

### Neutral Input Field
**Role:** User data entry

Transparent background, Polar White (#ffffff) inset border of 1px, 24px border-radius. Alabaster Text (#f0f5fa) for input, Smoke Gray (#1a1d1f) for placeholder. 12px vertical padding, 16px horizontal padding.

### Status Badge
**Role:** Small, informational tags

100px border-radius (pill shape), Alabaster Text (#f0f5fa), with backgrounds varying between Jade Glow (#33ffac), Amethyst Spark (#ff2ad4), Techno Blue (#5b76ff). No explicit padding, text defines size.

### Alert Banner
**Role:** Top-level announcements

Transparent background, bold text at 16px Clashgrotesk (weight 500) and Amber Thrust (#ff6314) for links. Subtle accent colors like Arctic Current (#16c4ff) are used for specific callouts within the banner.

### Light Content Card
**Role:** Alternate light theme sections, like process descriptions

Polar White (#ffffff) background, 8px border-radius. Uses 24px padding with Dark Ink (#04070a) text. Functions as a deliberate high-contrast break from the dominant dark UI.

## Do's and Don'ts

### Do
- Prioritize a dark aesthetic with Midnight Apex (#04070a) as the primary background and Obsidian Surface (#000000) for components.
- Use Amber Thrust (#ff6314) exclusively for primary calls-to-action and active states to maintain strong visual focus.
- Apply Clashgrotesk (weights 500, 600) for all headings and navigation using a tight letter-spacing of -0.033em.
- Ensure all buttons, inputs, and selected navigation items consistently use a 24px border-radius for a distinct rounded rectangle shape.
- Employ DM Mono at 12px or 14px for all technical labels, code snippets, and meta-information, maintaining a developer-centric feel.
- Use a comfortable density with 24px as a common element gap and card padding for clear separation.
- Incorporate subtle, scattered accent colors like Amethyst Spark (#ff2ad4) or Arctic Current (#16c4ff) as small, functional indicators, never for large areas.

### Don't
- Avoid light backgrounds outside of designated contrasting sections; the default should always be dark.
- Do not introduce new color accents; stick to the defined palette of Amber Thrust, Jade Glow, Amethyst Spark, Techno Blue, and Arctic Current.
- Do not use generic sans-serif fonts for headlines; Clashgrotesk is a signature element.
- Avoid heavy drop shadows or excessive elevation; maintain a subtle, flat surface feel with minimal visual depth.
- Do not use highly saturated brand imagery or photography; keep visuals abstract, technical, or monochromatic.
- Never dilute the impact of Amber Thrust (#ff6314) by using it for non-action or decorative elements.
- Do not deviate from the established spacing units; consistency with 6px base grid and 24px element gaps is crucial.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Apex Canvas | `#04070a` | The foundational dark background for the entire page, providing depth and contrast. |
| 1 | Obsidian Surface | `#000000` | Primary interactive or contained surfaces like navigation and hero elements, slightly elevated from the canvas. |
| 2 | Charcoal Panel | `#0f1214` | Secondary structured content panels and card backgrounds, offering a subtle visual break within dark sections. |
| 3 | Amber highlight | `#ff6314` | High-impact cards or feature blocks that explicitly draw attention against the dark background. |

## Elevation

- **Link with Inset Border:** `rgb(255, 255, 255) 0px 0px 0px 1px inset`
- **Input Focus Ring:** `rgb(225, 230, 235) 0px 0px 0px 1px inset`

## Imagery

The site uses abstract, geometric grid patterns and subtle, glowing orb-like indicators. Product screenshots are minimal or implied, focusing on conceptual diagrams. Photography is absent. Icons are typically monocolor, line-drawn, or simple filled shapes, serving as functional indicators or decorative elements within the grid. The overall density of imagery is low; it functions primarily as atmospheric backdrop or conceptual illustration rather than detailed content.

## Layout

The layout is predominantly a max-width contained grid (1584px) with content centered. The hero section is full-bleed dark, featuring a large, centered headline over an abstract grid background, flanked by primary calls-to-action. Sections alternate between deep blacks and subtle charcoal panels, creating distinct visual blocks. Content often arranges in 2-column or 4-column card grids, particularly for lists of trusted partners. Vertical spacing between sections is consistent, giving a balanced, controlled rhythm. Navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

primary action: #ff6314 (filled action)
Create a Primary Action Button: #ff6314 background, #04070a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
2. Create a 'Trusted By' section: Obsidian Surface (#000000) background. Heading 'Trusted by Industry Leaders' at 56px Clashgrotesk weight 600, #f0f5fa, letter-spacing -0.033em. Arrange 4 Category Cards, each with a Charcoal Panel (#0f1214) background and 8px radius, titled 'Enterprise', 'RWAs', 'DeFi', 'Wallets', and containing their respective logos as icons with Alabaster Text (#f0f5fa) labels. Each category title should have a small colored circular accent badge: 'Enterprise' with Amethyst Spark (#ff2ad4), 'RWAs' with Amber Thrust (#ff6314), 'DeFi' with Jade Glow (#33ffac), 'Wallets' with Arctic Current (#16c4ff).
3. Create a 'Features' section: Polar White (#ffffff) background. Headline 'All Of Crypto At Your Fingertips' at 56px Clashgrotesk weight 600, #04070a, letter-spacing -0.033em. Three Highlight Cards (Amber Thrust background #ff6314, Polar White text #ffffff, 8px radius, 24px padding), each with a large abstract icon and a subheading in Clashgrotesk weight 600, size 28px, letter-spacing -0.033em. Body text in Inter weight 400, size 16px.

## Similar Brands

- **Solana** — Similar dark, technical aesthetic with bright, singular accent colors for energy and focus.
- **Polygon** — Uses a dark background, geometric patterns, and strong, clear typography to convey technical authority.
- **Chainlink** — Dark UI, structured layout with clear information hierarchy, and a professional, data-driven visual tone.
- **Uniswap** — Employs a deep dark mode, high-contrast typography, and concise UI elements for a precise, functional feel.
- **Alchemy** — Developer-centric dark theme, clear typographic hierarchy, and limited, impactful accent colors to guide attention.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-apex: #04070a;
  --color-obsidian-surface: #000000;
  --color-charcoal-panel: #0f1214;
  --color-smoke-gray: #1a1d1f;
  --color-ash-outline: #676f7a;
  --color-alabaster-text: #f0f5fa;
  --color-polar-white: #ffffff;
  --color-amber-thrust: #ff6314;
  --gradient-amber-thrust: linear-gradient(270deg, rgb(255, 99, 20) 24%, rgb(255, 61, 0));
  --color-jade-glow: #33ffac;
  --color-amethyst-spark: #ff2ad4;
  --color-techno-blue: #5b76ff;
  --color-arctic-current: #16c4ff;

  /* Typography — Font Families */
  --font-clashgrotesk: 'Clashgrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-f77-minecraft: 'F77 Minecraft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: -0.033px;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 19px;
  --leading-subheading: 1.25;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.033px;
  --text-heading-lg: 37px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.033px;
  --text-display-sm: 56px;
  --leading-display-sm: 1.25;
  --tracking-display-sm: -0.033px;
  --text-display: 74px;
  --leading-display: 1.25;
  --tracking-display: -0.033px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-42: 42px;
  --spacing-43: 43px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --page-max-width: 1584px;
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 100px;
  --radius-inputs: 24px;
  --radius-buttons: 24px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgb(225, 230, 235) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-midnight-apex-canvas: #04070a;
  --surface-obsidian-surface: #000000;
  --surface-charcoal-panel: #0f1214;
  --surface-amber-highlight: #ff6314;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-apex: #04070a;
  --color-obsidian-surface: #000000;
  --color-charcoal-panel: #0f1214;
  --color-smoke-gray: #1a1d1f;
  --color-ash-outline: #676f7a;
  --color-alabaster-text: #f0f5fa;
  --color-polar-white: #ffffff;
  --color-amber-thrust: #ff6314;
  --color-jade-glow: #33ffac;
  --color-amethyst-spark: #ff2ad4;
  --color-techno-blue: #5b76ff;
  --color-arctic-current: #16c4ff;

  /* Typography */
  --font-clashgrotesk: 'Clashgrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-f77-minecraft: 'F77 Minecraft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: -0.033px;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 19px;
  --leading-subheading: 1.25;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.033px;
  --text-heading-lg: 37px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.033px;
  --text-display-sm: 56px;
  --leading-display-sm: 1.25;
  --tracking-display-sm: -0.033px;
  --text-display: 74px;
  --leading-display: 1.25;
  --tracking-display: -0.033px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-42: 42px;
  --spacing-43: 43px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgb(225, 230, 235) 0px 0px 0px 1px inset;
}
```
