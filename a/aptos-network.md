# Aptos Network — Style Reference
> Blockchain blueprint on warm concrete

**Theme:** light

Aptos Network embraces an institutional-grade, tech-forward canvas, expressed through a subdued palette of warm greys, cool blues, and a single muted green. The design blends serif headlines with monospaced code-like blocks, creating a visual tension between established authority and digital innovation. Subtle inset borders and bold, simple type define components, with interactive flourishes appearing as unexpected geometric patterns or soft color shifts.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#f9f9f0` | `--color-canvas-parchment` | Primary page background, light surface |
| Midnight Ink | `#0f0e0b` | `--color-midnight-ink` | Primary text, strong borders, dark surface backgrounds |
| Greige Stone | `#6d6c67` | `--color-greige-stone` | Muted text, secondary borders, subtle dividers |
| Ash Concrete | `#555450` | `--color-ash-concrete` | Tertiary text, less prominent borders |
| Slate Code | `#3d3b34` | `--color-slate-code` | Code block backgrounds, subtle darker surface elements |
| Muted Sage | `#d5fad3` | `--color-muted-sage` | Hero section background, subtle background accents |
| Warm Clay | `#9d937c` | `--color-warm-clay` | Hero section background, earthy accents |
| Light Mauve Grid | `#ccc5a3` | `--color-light-mauve-grid` | Shadow effect for visual grids, decorative stroke in backgrounds |
| Sky Blue Grid | `linear-gradient(to right, rgb(186, 219, 238), rgb(186, 219, 238) 44.0625px, rgb(15, 14, 11) 44.0625px, rgb(15, 14, 11) 88.125px)` | `--color-sky-blue-grid` | Shadow effect for visual grids, decorative active state backgrounds |
| Interim Button Fill | `#21201c` | `--color-interim-button-fill` | Solid background for primary action buttons, signaling an active choice |

## Tokens — Typography

### Season Serif — Primary display font for headings and strong statements. Unique weights (like 335, 340, 358) give a delicate, almost whispered authority, contrasting with the often bold sans-serifs of many tech sites. This approach suggests a more refined, established presence. · `--font-season-serif`
- **Substitute:** Playfair Display
- **Weights:** 335, 340, 358, 363, 400, 420, 444
- **Sizes:** 9px, 16px, 18px, 20px, 24px, 55px, 90px, 120px
- **Line height:** 0.95, 1.00, 1.10, 1.25, 1.30, 1.40, 1.50, 1.63
- **Letter spacing:** -0.0300em, -0.0200em, -0.0100em, 0.0100em, 0.0200em
- **OpenType features:** `"calt"`
- **Role:** Primary display font for headings and strong statements. Unique weights (like 335, 340, 358) give a delicate, almost whispered authority, contrasting with the often bold sans-serifs of many tech sites. This approach suggests a more refined, established presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.5 | 0.01px | `--text-body-sm` |
| body | 18px | 1.4 | 0.01px | `--text-body` |
| subheading | 20px | 1.3 | -0.01px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.01px | `--text-heading-sm` |
| heading | 55px | 1.1 | -0.02px | `--text-heading` |
| heading-lg | 90px | 1 | -0.03px | `--text-heading-lg` |
| display | 120px | 0.95 | -0.03px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 90 | 90px | `--spacing-90` |
| 150 | 150px | `--spacing-150` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 16777215px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(15, 14, 11) -1px 0px 0px 0px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(204, 197, 163) -1px 0px 0px 0px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(186, 219, 238) -1px 0px 0px 0px inset` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 45px
- **Card padding:** 30px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Call to action.

Filled button with a dark background, light text, and generous padding for emphasis. Has an extremely large border radius, effectively making it a pill shape. Background: #21201c, Text: #f9f9f0, Padding: 30px on all sides, Radius: 16777215px, Border: none.

### Pill Button
**Role:** General interactive buttons for navigation or secondary actions.

Compact button with a pill shape. Background: #0f0e0b, Text: #f9f9f0, Radius: 16777215px, Padding: 0px vertical, 20px horizontal, Border: 1px solid #f9f9f0.

### Ghost Link Button
**Role:** Tertiary actions or navigation items where visual weight should be minimal.

Text-only button without background or significant padding. Background: transparent, Text: #0f0e0b, Radius: 0px, Padding: 0px, Border: 1px solid #0f0e0b (implied underline/hover effect).

### Outlined Pill Button
**Role:** Secondary interactive elements for a subtle yet defined action.

Ghost button with a thin outline, maintaining a pill shape. Background: transparent, Text: #0f0e0b, Radius: 16777215px, Padding: 15px vertical, 20px horizontal, Border: 1px solid #0f0e0b.

### Feature Card
**Role:** Content container for features or information blocks.

Transparent background with no explicit border or shadow, relying on layout for definition. Background: transparent, Radius: 0px, Padding: 0px.

## Do's and Don'ts

### Do
- Use Season Serif weights in the 300s (335, 340, 358) for headlines to create a lighter, more restrained authority.
- Apply 'Canvas Parchment' (#f9f9f0) as the primary page background for a consistent light theme.
- Utilize 'Midnight Ink' (#0f0e0b) for all primary text and critical UI borders to ensure high contrast.
- Employ the 'Interim Button Fill' (#21201c) only for primary action buttons that require a solid fill and high visibility.
- Maintain a clear visual hierarchy by limiting saturated colors ('Muted Sage', 'Warm Clay', 'Sky Blue Grid') to background sections and decorative elements, not interactive components or text.
- Implement the large border radius (16777215px) for all buttons to achieve a consistent pill-shaped aesthetic.
- Use subtle inset shadows like rgb(15, 14, 11) -1px 0px 0px 0px inset when defining visual grids or code blocks, not for standard elevation.

### Don't
- Do not use dark backgrounds for large text blocks; reserve 'Midnight Ink' (#0f0e0b) for text over light backgrounds.
- Avoid using multiple different border radii for interactive elements; stick to the defined pill shape or sharp zero-radius for ghost elements.
- Do not introduce strong, solid background colors on most cards; prioritize transparent backgrounds for a lightweight feel.
- Refrain from using generic drop shadows for depth; prefer subtle inset shadows or rely on background color shifts for elevation.
- Do not vary letter spacing excessively; follow established letter spacing values per type scale role for a consistent textual rhythm.
- Avoid using chromatic colors for functional text, such as button labels or body copy; these are reserved for backgrounds and decorative elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Parchment | `#f9f9f0` | Base page background. |
| 2 | Muted Sage | `#d5fad3` | Hero and feature section background, slight lift off the base. |
| 3 | Warm Clay | `#9d937c` | Alternative hero and feature section background, offering a warmer tone. |
| 4 | Slate Code | `#3d3b34` | Darker background for code blocks or emphasis sections. |

## Imagery

The visual language blends abstract, geometric patterns with the raw aesthetic of code. Photography is largely absent; instead, the site uses abstract checkered grids (often with blue or amber tints) that subtly mimic the appearance of a blockchain or data structure. These grids are sometimes overlaid with code snippets, enhancing the tech-forward, developer-centric feel. Icons are monochrome, simple, and typically filled, maintaining a minimalist appearance with a consistent stroke weight, often appearing in 'Midnight Ink' (#0f0e0b) against a light background or 'Canvas Parchment' (#f9f9f0) against dark elements. Imagery serves a decorative and atmospheric purpose, reinforcing the brand's 'foundational tech' identity rather than explaining content literally.

## Layout

The page primarily uses a full-bleed layout, allowing background colors to stretch across the viewport regardless of content width. Sections often alternate between full-width colored backgrounds (like 'Muted Sage' and 'Warm Clay') and the default 'Canvas Parchment'. The hero section uses a large, centered serif headline over a solid background, sometimes accompanied by interactive elements or an abstract graphic on one side. Content is typically arranged in two-column layouts or centered stacks, with generous vertical spacing between sections (45px section gap) for a comfortable density. Navigation is a persistent top bar with minimal styling, including a 'Get Started' pill button.

## Agent Prompt Guide

Quick Color Reference:
text: #0f0e0b
background: #f9f9f0
border: #0f0e0b
accent: #d5fad3
primary action: #21201c (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #21201c background, #f9f9f0 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a navigation bar: 'Pill Button' with content 'Get Started', font-family Season Serif, 16px, weight 400, #f9f9f0, -0.01em letter-spacing. Place it alongside 'Ghost Link Buttons' for other navigation items (e.g., 'About', 'Ecosystem').
3. Construct a feature block: use the 'Warm Clay' (#9d937c) background. Include a headline at 55px, weight 340, #0f0e0b, letter-spacing -0.02em. A body text paragraph at 18px, weight 400, #6d6c67, 0.01em letter-spacing. Add an 'Outlined Pill Button' labeled 'Discover'.

## Similar Brands

- **Solana** — Similar use of subtle background patterns and code-like imagery to convey a blockchain identity with a lean, functional UI.
- **Protocol Labs** — Employs a combination of traditional serif typography for headlines and monospaced fonts for technical content, similar to Aptos Network's blend of 'Season Serif' and code blocks.
- **Chainlink** — A minimalist, light-themed interface with a few distinct accent colors and a focus on clean typography for conveying complex technical information.
- **Circle (USDC)** — Sophisticated use of a controlled color palette and strong typography to create a sense of trust and institutional reliability in the financial tech space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #f9f9f0;
  --color-midnight-ink: #0f0e0b;
  --color-greige-stone: #6d6c67;
  --color-ash-concrete: #555450;
  --color-slate-code: #3d3b34;
  --color-muted-sage: #d5fad3;
  --color-warm-clay: #9d937c;
  --color-light-mauve-grid: #ccc5a3;
  --color-sky-blue-grid: #badbee;
  --gradient-sky-blue-grid: linear-gradient(to right, rgb(186, 219, 238), rgb(186, 219, 238) 44.0625px, rgb(15, 14, 11) 44.0625px, rgb(15, 14, 11) 88.125px);
  --color-interim-button-fill: #21201c;

  /* Typography — Font Families */
  --font-season-serif: 'Season Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.01px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: 0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 55px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-heading-lg: 90px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 120px;
  --leading-display: 0.95;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-w335: 335;
  --font-weight-w340: 340;
  --font-weight-w358: 358;
  --font-weight-w363: 363;
  --font-weight-regular: 400;
  --font-weight-w420: 420;
  --font-weight-w444: 444;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-150: 150px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 30px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 16777215px;

  /* Shadows */
  --shadow-subtle: rgb(15, 14, 11) -1px 0px 0px 0px inset;
  --shadow-subtle-2: rgb(204, 197, 163) -1px 0px 0px 0px inset;
  --shadow-subtle-3: rgb(186, 219, 238) -1px 0px 0px 0px inset;

  /* Surfaces */
  --surface-canvas-parchment: #f9f9f0;
  --surface-muted-sage: #d5fad3;
  --surface-warm-clay: #9d937c;
  --surface-slate-code: #3d3b34;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #f9f9f0;
  --color-midnight-ink: #0f0e0b;
  --color-greige-stone: #6d6c67;
  --color-ash-concrete: #555450;
  --color-slate-code: #3d3b34;
  --color-muted-sage: #d5fad3;
  --color-warm-clay: #9d937c;
  --color-light-mauve-grid: #ccc5a3;
  --color-sky-blue-grid: #badbee;
  --color-interim-button-fill: #21201c;

  /* Typography */
  --font-season-serif: 'Season Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.01px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: 0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 55px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-heading-lg: 90px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.03px;
  --text-display: 120px;
  --leading-display: 0.95;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-150: 150px;
  --spacing-180: 180px;

  /* Shadows */
  --shadow-subtle: rgb(15, 14, 11) -1px 0px 0px 0px inset;
  --shadow-subtle-2: rgb(204, 197, 163) -1px 0px 0px 0px inset;
  --shadow-subtle-3: rgb(186, 219, 238) -1px 0px 0px 0px inset;
}
```
