# Adnaut — Style Reference
> Midnight Command Center: high-contrast dark surfaces with neon yellow alerts guiding every interaction.

**Theme:** dark

Adnaut employs a 'digital command center' aesthetic, built on a dark canvas with high-contrast elements and a prominent vivid yellow accent. The layout is structured and modular, utilizing cards and defined sections. Typography leans towards modern, clean sans-serifs, with an emphasis on distinct weights for hierarchy. The yellow accent color acts as a functional marker, highlighting actions and key information, while subtle green provides a secondary semantic cue. Overall, the system projects an efficient, data-driven atmosphere.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#1f1d01` | `--color-deep-space` | Page backgrounds, large container surfaces – the dominant dark canvas for the UI |
| Charcoal Canvas | `#282828` | `--color-charcoal-canvas` | Secondary background surfaces for cards, darker navigation elements, and interactive states |
| Graphite | `#707070` | `--color-graphite` | Subtle borders, inactive states, and divider lines, providing gentle visual separation without stark contrast |
| Silver Text | `#d7d7d7` | `--color-silver-text` | Primary body text, headers, and essential informational elements |
| Pure White | `#ffffff` | `--color-pure-white` | High-contrast text on accent colors, icon fills, and occasional highlight elements |
| Smoke | `#c0c0c0` | `--color-smoke` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Pale Mist | `#f2f2f2` | `--color-pale-mist` | Secondary text in lighter contexts, subtle border lines, or icon fills |
| Ink Black | `#000000` | `--color-ink-black` | Text on bright yellow backgrounds, specific icons, providing ultimate contrast |
| Adnaut Gold | `#ffe900` | `--color-adnaut-gold` | Primary action backgrounds, interactive elements, prominent highlights, and brand logos — defines the brand's active state |
| Terminal Green | `#00ff1a` | `--color-terminal-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Geist — The primary sans-serif for body text, navigation elements, and some informational text, offering a clean, contemporary feel. The varied weights provide hierarchy within smaller text blocks. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 14px, 16px, 20px
- **Line height:** 1.00, 1.10, 1.50
- **Role:** The primary sans-serif for body text, navigation elements, and some informational text, offering a clean, contemporary feel. The varied weights provide hierarchy within smaller text blocks.

### Archivo — Used for prominent headings and subheadings, particularly the extra-light weight (100 or 300) to establish a sophisticated, airy presence that contrasts with the dark background. Larger sizes without letter spacing maintain readability despite the light weight. The 400 weight is used for body copy on cards. · `--font-archivo`
- **Substitute:** Roboto, Lato
- **Weights:** 100, 300, 400
- **Sizes:** 16px, 18px, 24px, 32px, 56px, 64px
- **Line height:** 1.00, 1.50
- **Role:** Used for prominent headings and subheadings, particularly the extra-light weight (100 or 300) to establish a sophisticated, airy presence that contrasts with the dark background. Larger sizes without letter spacing maintain readability despite the light weight. The 400 weight is used for body copy on cards.

### Geistmono — A monospace font primarily for navigation, specific labels, and functional text where a technical, data-centric feel is desired. · `--font-geistmono`
- **Substitute:** Inconsolata, Fira Code
- **Weights:** 400, 600
- **Sizes:** 14px, 16px, 24px, 56px
- **Line height:** 1.00, 1.50
- **Role:** A monospace font primarily for navigation, specific labels, and functional text where a technical, data-centric feel is desired.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 24px | 1.5 | — | `--text-heading-sm` |
| heading | 32px | 1 | — | `--text-heading` |
| heading-lg | 56px | 1 | — | `--text-heading-lg` |
| display | 64px | 1 | — | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| input | 4px |
| small | 3.69px |
| buttons | 4px |
| default | 16px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled button

Solid Adnaut Gold (#ffe900) background with Ink Black (#000000) text, 4px border-radius, and generous horizontal padding (17px left/right, 12px top/bottom). Used for main calls to action.

### Card Nav Button
**Role:** Interactive navigation/list item

Background Charcoal Canvas (#282828), Silver Text (#d7d7d7), with a soft Graphite (#707070) border when outlined. 16px border-radius, 48px top/bottom, 32px left/right padding. Often acts as a larger, tappable card-like button.

### Ghost Nav Link
**Role:** Navigation link / secondary action

Transparent background with Silver Text (#d7d7d7). No border-radius or padding, minimal line under active items. Used for navigation menus and in-text links.

### Feature Card - Gold
**Role:** Highlighting key information or features

Solid Adnaut Gold (#ffe900) background, with Ink Black (#000000) text. Has a 16px border-radius and 48px padding on all sides. Used for important, visually distinct content blocks.

### Feature Card - Dark
**Role:** Standard content card

Solid Charcoal Canvas (#282828) background, with Silver Text (#d7d7d7). Has a 16px border-radius and 48px padding on all sides. Used for general content presentation.

### Hero Section Container
**Role:** Full-bleed section for introductory content

Uses Deep Space (#1f1d01) as its primary background for large, immersive blocks. No specific border radius, padding varies to full bleed, but content within is often contained. Features custom shadowy drop-shadows as visual flair.

## Do's and Don'ts

### Do
- Always use Deep Space (#1f1d01) as the base page background for a consistent dark theme.
- Highlight primary calls to action with Adnaut Gold (#ffe900) for button backgrounds and a 4px border-radius.
- Maintain a clear content hierarchy using Archivo for headlines (weights 100-300) and Geist for body text (weights 300-400).
- Apply 16px border-radius to all cards and major content blocks to soften the UI.
- Utilize Terminal Green (#00ff1a) sparingly for specific semantic emphasis, such as 'Sustainably', rather than general accents.
- Employ Geistmono for navigation items and technical labels to reinforce the data-driven brand identity.
- Use Silver Text (#d7d7d7) as the default color for all body text and charcoal-based component text.

### Don't
- Avoid using bright, saturated colors for backgrounds unless it is an Adnaut Gold (#ffe900) feature card.
- Do not overuse Terminal Green (#00ff1a); reserve it strictly for semantic positive highlights.
- Do not introduce new border radii; stick to 16px for cards, 4px for buttons, and 3.69px for smaller elements.
- Do not apply drop shadows indiscriminately; use them only as explicitly defined for hero elements or with the blue-tinted shadow for elevation.
- Do not place text directly on Adnaut Gold (#ffe900) backgrounds without using Ink Black (#000000) for contrast.
- Avoid using white for large content blocks or backgrounds; prioritize varying shades of dark neutrals.
- Do not exceed a page width of 1200px for content; the layout is contained, not full-bleed for internal content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Deep Space | `#1f1d01` | Base page background |
| 2 | Charcoal Canvas | `#282828` | Secondary backgrounds, card surfaces, darker navigation |

## Elevation

- **Hero Section Container:** `drop-shadow(rgb(112, 112, 112) 0px 0px 2px) drop-shadow(rgba(252, 240, 192, 0.6) -4px 1px 6px)`

## Imagery

The visual language combines abstract 3D renders of glowing, geometric forms (cubes, spheres, interconnected lines) with conceptual illustrations that imply data flow and connectivity. Imagery is often set against the dark background, using subtle glows and transparency. Photography is minimal, primarily tight product-focused crops if present. Icons are typically outlined and achromatic or filled with accent colors. Imagery serves primarily decorative and atmospheric roles, emphasizing a futuristic and technical product showcase.

## Layout

The page primarily uses a contained layout within a maximum width of 1200px (inferred from common breakpoint strategies by examining element widths and padding), centered on the screen. The hero section is full-bleed, featuring a large, centered headline and a background of abstract graphics. Subsequent sections alternate between dark backgrounds (Deep Space #1f1d01) and Charcoal Canvas (#282828) for different content blocks, creating a distinct visual rhythm. Content is generally arranged in two-column layouts or centered stacks, with features presented in multi-column card grids. Navigation is a sticky top bar with a secondary footer navigation for more detailed links, both using the monospace font and ghost link style.

## Agent Prompt Guide

Quick Color Reference:
text: #d7d7d7
background: #1f1d01
border: #707070
accent: #ffe900
primary action: #ffe900 (filled action)

Example Component Prompts:
1. Create a Hero Headline: 'Your navigator in the Ad-Tech universe.' using Archivo, weight 300, size 64px, color #d7d7d7, line-height 1.0. Place it centered within a full-bleed Deep Space (#1f1d01) section.
2. Design a Primary Action Button: 'LET'S TALK' with background Adnaut Gold (#ffe900), text Ink Black (#000000), Geist font, weight 600, size 16px, 4px border-radius, and 12px top/bottom, 17px left/right padding.
3. Make a Feature Card: Background Charcoal Canvas (#282828), 16px border-radius, 48px padding. Headline 'Drive business impact' in Archivo weight 400, size 24px, color #d7d7d7. Body text in Geist weight 400, size 16px, color #d7d7d7.
4. Create a Ghost Navigation Link: 'Services' using Geistmono, weight 400, size 16px, color #d7d7d7, with a transparent background and no radius or padding.

## Similar Brands

- **Datadog** — Dark UI with vibrant, functional accent colors for data visualization and interactive elements.
- **Amplitude** — Structured dark-mode UI, heavy reliance on card components, and a strong emphasis on data-driven product presentation.
- **Linear** — Minimalist dark aesthetic, compact typography (monospaced for some elements), and a single bright color accent for interactive states.
- **Vercel** — Dark interface, subtle gradients and shadows, and a clean, technical typography approach.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #1f1d01;
  --color-charcoal-canvas: #282828;
  --color-graphite: #707070;
  --color-silver-text: #d7d7d7;
  --color-pure-white: #ffffff;
  --color-smoke: #c0c0c0;
  --color-pale-mist: #f2f2f2;
  --color-ink-black: #000000;
  --color-adnaut-gold: #ffe900;
  --color-terminal-green: #00ff1a;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'Geistmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 3.69px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-input: 4px;
  --radius-small: 3.69px;
  --radius-buttons: 4px;
  --radius-default: 16px;

  /* Surfaces */
  --surface-deep-space: #1f1d01;
  --surface-charcoal-canvas: #282828;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #1f1d01;
  --color-charcoal-canvas: #282828;
  --color-graphite: #707070;
  --color-silver-text: #d7d7d7;
  --color-pure-white: #ffffff;
  --color-smoke: #c0c0c0;
  --color-pale-mist: #f2f2f2;
  --color-ink-black: #000000;
  --color-adnaut-gold: #ffe900;
  --color-terminal-green: #00ff1a;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'Geistmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;

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

  /* Border Radius */
  --radius-md: 3.69px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
}
```
