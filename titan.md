# Titan — Style Reference
> monochrome financial ledger

**Theme:** light

Titan presents a refined, high-contrast, monochrome aesthetic, marrying the sharpness of financial precision with an underlying human warmth. Its visual language prioritizes clear information hierarchy and direct interaction, utilizing stark black and white with subtle, almost imperceptible, warm off-white and gray undertones for depth. Components are lightweight and interaction-focused, often featuring generous padding and distinctive pill-shaped radii to create a sense of approachability within a formal system. The design feels grounded and authoritative, not through heavy elements, but through its disciplined use of space, typography, and a distinct lack of decorative flourishes, allowing content and functionality to lead.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111111` | `--color-midnight-ink` | Primary text, darkest surface. Creates stark contrast against lighter backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text. The primary backdrop for all content |
| Off-White Sage | `#f3efeb` | `--color-off-white-sage` | Subtle background for card variants and secondary sections, provides a soft, warm surface distinction |
| Faded Stone | `#e9eaeb` | `--color-faded-stone` | Subtle borders and dividers, navigation backgrounds, a very light gray that acts as an almost invisible separator |
| Gunmetal Gray | `#615e5b` | `--color-gunmetal-gray` | Secondary text, muted helper text, and subtle icon details. Provides lower contrast for less prominent information |
| Soft Concrete | `#d8d3cc` | `--color-soft-concrete` | Subtle borders for ghost buttons and card containers, provides minimal visual separation |
| Action Black | `#000000` | `--color-action-black` | Primary button backgrounds, key interactive elements. The pure black stands out against the near-white canvas |
| Highlight Orange | `#ff9900` | `--color-highlight-orange` | Decorative strokes and subtle highlights, often within SVG elements. A small splash of vivid color |

## Tokens — Typography

### Geist — Primary typeface for all UI elements, headings, body text, and links. Its clean, modern lines reinforce the site's precision. Key use cases: weight 700 at 60px for prominent hero headlines, weight 400 at 16px for body content. Features 'ss02' and 'ss03' for consistent brand character. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 60px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.50
- **Letter spacing:** -0.0300em, 0.0200em, 0.0300em
- **OpenType features:** `"ss02", "ss03"`
- **Role:** Primary typeface for all UI elements, headings, body text, and links. Its clean, modern lines reinforce the site's precision. Key use cases: weight 700 at 60px for prominent hero headlines, weight 400 at 16px for body content. Features 'ss02' and 'ss03' for consistent brand character.

### Geist Mono — Used sparingly for data displays or code-like elements, lending a technical and precise feel. Its monospaced nature is a deliberate choice for presenting numerical or categorical information. Features 'ss08' for specific character variations. · `--font-geist-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 400, 500
- **Sizes:** 11px, 13px, 20px, 28px, 48px
- **Line height:** 1.00, 1.10
- **Letter spacing:** -0.0100em, 0.0300em
- **OpenType features:** `"ss08"`
- **Role:** Used sparingly for data displays or code-like elements, lending a technical and precise feel. Its monospaced nature is a deliberate choice for presenting numerical or categorical information. Features 'ss08' for specific character variations.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body-sm | 12px | 1.2 | — | `--text-body-sm` |
| body | 14px | 1.2 | — | `--text-body` |
| body-lg | 16px | 1.2 | — | `--text-body-lg` |
| heading-sm | 20px | 1.2 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 32px | 1.2 | — | `--text-heading-lg` |
| display-sm | 40px | 1.2 | — | `--text-display-sm` |
| display | 60px | 1.2 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| small | 10px |
| medium | 20px |
| buttons | 160px |
| navigation | 140px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 80px
- **Card padding:** 28px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Call to action

Filled with Action Black (#000000) background, Canvas White (#ffffff) text, and a highly rounded 160px border-radius. Padding is 24px horizontal, with implied vertical padding from line height for text.

### Ghost Button
**Role:** Secondary action or link

Transparent background with Midnight Ink (#111111) text and a subtle Soft Concrete (#d8d3cc) 1px border, 160px border-radius. Padding is 24px horizontal and 11px vertical.

### Navigation Link Button
**Role:** Tertiary action or inline navigation link

Transparent background with Midnight Ink (#111111) text, no visible border, and a 140px border-radius. Minimal horizontal padding of 18px and vertical padding of 11px for a refined, clickable area.

### Feature Card
**Role:** Informational content container

Background of Off-White Sage (#f3efeb), with a 20px border-radius, and generous 28px padding on all sides. Used for important informational blocks.

### Expanded Feature Card
**Role:** Detailed content container

Similar to Feature Card, with an Off-White Sage (#f3efeb) background and 32px border-radius, but featuring larger 56px padding on top/bottom and 28-56px variable horizontal padding for more expansive content.

### Stat Display Card
**Role:** Quick view data presentation

Transparent background, 32px border-radius, with 32px top/bottom padding and 18-28px horizontal padding. Content is separated by implicit spacing, not explicit internal borders.

### Inline Text Link
**Role:** Navigation or contextual information link

Midnight Ink (#111111) text, with no underline for a clean appearance. Implied padding when interactive derived from a base unit of 10px.

## Do's and Don'ts

### Do
- Use Midnight Ink (#111111) as the primary text color against Canvas White (#ffffff) or Off-White Sage (#f3efeb) to maintain high contrast.
- Apply a 160px border-radius to all primary and ghost buttons, and 140px to navigation elements for a consistent pill-shaped aesthetic.
- Separate major content sections with 80px vertical spacing to ensure comfortable density and visual breathing room.
- Utilize Geist at weight 700 for headings, sizes 40px and 60px, with -0.0300em letter spacing to create impactful, condensed titles.
- Use Geist Mono sparingly for numerical data or technical terms, leveraging its 'ss08' feature for distinct presentation.
- Implement Soft Concrete (#d8d3cc) for subtle 1px borders on ghost buttons and divider lines to avoid heavy visual separation.
- Employ Off-White Sage (#f3efeb) as a background for secondary content blocks or cards to provide a warm, soft distinction from the main Canvas White background.

### Don't
- Avoid introducing additional saturated colors; maintain the predominantly monochrome palette with only subtle Highlight Orange accents in decorative elements.
- Do not use box-shadows for elevation; rely on background color changes or subtle borders for surface differentiation.
- Do not use generic circular or square button radii; adhere to the specific 160px and 140px values for interactive elements.
- Avoid dense, unbroken blocks of text; break up content with generous padding, section gaps, and clear typographic hierarchy.
- Do not use default browser link styles; all links should be styled with Midnight Ink (#111111) and no underline by default.
- Do not use thin or light text weights for body copy; ensure readability with Geist at weight 400 or 500 for paragraph text.
- Avoid cluttering the layout; maintain the spacious and comfortable density by respecting elementGap of 24px and cardPadding of 28px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Dominant page background, main content area. |
| 2 | Off-White Sage | `#f3efeb` | Secondary background for cards and distinct content sections, offering a subtle visual break. |
| 3 | Faded Stone | `#e9eaeb` | Background for subtle borders, navigation elements, or very light dividers, almost blending into the canvas. |

## Imagery

The site uses a combination of high-contrast, black-and-white, highly detailed illustrations and occasional, stark product/lifestyle photography. Illustrations are the primary visual element, depicting urban landscapes (like a cityscape) or abstract financial concepts with fine linework, often with a single bird or abstract element for movement. Photography is minimal, often cropped tightly on individuals (lifestyle) or objects, maintaining the monochrome or desaturated tone. Icons are outlined, thin stroke, and monochromatic, used functionally rather than decoratively. The overall density of imagery is balanced; it serves to add atmosphere and context without overwhelming the clean UI.

## Layout

The page follows a contained, centered layout, with content constrained to a `pageMaxWidth` of 1200px. The hero section is a two-column split, with a bold headline and primary CTA on the left, balanced by a large, detailed monochrome illustration on the right. Section rhythm is consistent, primarily using 80px vertical gaps between major content blocks. Content is often presented in a grid-like fashion, such as the three-column card grid for feature highlights. Navigation is a simple, sticky top bar with logo, prominent brand name, a few text links, and filled/ghost buttons for login/signup. The density is comfortable, ensuring plenty of whitespace around elements.

## Agent Prompt Guide

Quick Color Reference:
- text: #111111
- background: #ffffff
- border: #e9eaeb
- accent: #ff9900
- primary action: #000000 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Generate a Feature Card titled 'Equity Compensation' using Off-White Sage (#f3efeb) background, 20px border-radius, padding 28px. Inside, use Geist weight 500 at 24px for the title and Geist weight 400 at 16px for body text, both in Midnight Ink (#111111).
- Build a Ghost Button 'See More' with Canvas White (#ffffff) background, Midnight Ink (#111111) text, Soft Concrete (#d8d3cc) 1px border, and 160px border-radius, with 24px horizontal padding and 11px vertical padding.

## Similar Brands

- **Wealthfront** — High-contrast, professional, and clean interface with a focus on clear typography and understated design.
- **Linear** — Monochromatic color palette with carefully selected grays and a strong emphasis on typography for information hierarchy.
- **Stripe** — Minimalist aesthetic characterized by abundant whitespace, crisp typography, and functional use of color only for accents and interactive elements.
- **Kraken** — Financial platform with a serious, high-contrast, black-and-white visual style that conveys trustworthiness and precision.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-canvas-white: #ffffff;
  --color-off-white-sage: #f3efeb;
  --color-faded-stone: #e9eaeb;
  --color-gunmetal-gray: #615e5b;
  --color-soft-concrete: #d8d3cc;
  --color-action-black: #000000;
  --color-highlight-orange: #ff9900;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body-sm: 12px;
  --leading-body-sm: 1.2;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-body-lg: 16px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 40px;
  --leading-display-sm: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 80px;
  --card-padding: 28px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 32px;
  --radius-full: 140px;
  --radius-full-2: 160px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-small: 10px;
  --radius-medium: 20px;
  --radius-buttons: 160px;
  --radius-navigation: 140px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-off-white-sage: #f3efeb;
  --surface-faded-stone: #e9eaeb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-canvas-white: #ffffff;
  --color-off-white-sage: #f3efeb;
  --color-faded-stone: #e9eaeb;
  --color-gunmetal-gray: #615e5b;
  --color-soft-concrete: #d8d3cc;
  --color-action-black: #000000;
  --color-highlight-orange: #ff9900;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body-sm: 12px;
  --leading-body-sm: 1.2;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-body-lg: 16px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 40px;
  --leading-display-sm: 1.2;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 32px;
  --radius-full: 140px;
  --radius-full-2: 160px;
}
```
