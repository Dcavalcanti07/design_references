# Copy — Style Reference
> Strategic blueprint on polished steel. Organized hierarchy and vibrant violet accents against a muted canvas.

**Theme:** light

This design system projects a high-tech, enterprise feel through its stark contrasts and precise typography. Dominant dark and vivid violet accents create a sense of digital sophistication, while a meticulous hierarchy of grays and precise spacing ensure clarity. The interplay of strong, weighted headlines against more muted body text establishes authority, characteristic of B2B SaaS platforms.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#171717` | `--color-midnight-ink` | Primary text, deep backgrounds, icon fills. |
| Cloud Burst | `#f6fafb` | `--color-cloud-burst` | Primary page and card backgrounds, input fields. |
| Slate Echo | `#e4edf1` | `--color-slate-echo` | Subtle borders, form field outlines, divider lines. |
| Ash Veil | `#e2e8eb` | `--color-ash-veil` | Button borders, subtle highlights. |
| Graphite Tone | `#5d5d5d` | `--color-graphite-tone` | Secondary text, descriptive labels. |
| Violet Impulse | `#693edf` | `--color-violet-impulse` | Primary Call-to-Action buttons, active navigation, key interactive elements. Its vividness provides a clear focal point against the neutral palette. |
| Deep Space Violet | `#3b0d96` | `--color-deep-space-violet` | Darker accent for buttons and specific background sections, providing depth within the brand's violet spectrum. |
| Dawn Violet | `#c1b9f4` | `--color-dawn-violet` | Lighter accent used for subtle indicators or progress elements, softening the brand's primary color when needed. |

## Tokens — Typography

### ABC Normal — Display and marketing headlines. The custom font elevates the brand's visual identity, especially with its precise letterSpacing and tight line heights, giving titles a sophisticated, controlled feel. · `--font-abc-normal`
- **Substitute:** Montserrat
- **Weights:** 500, 600
- **Sizes:** 24px, 26px, 28px, 32px, 48px, 56px, 88px
- **Line height:** 1.00, 1.18, 1.31, 1.40, 1.42, 1.50
- **Letter spacing:** -0.0200em at display sizes (88px, 56px), 0.0050em at 24px and 26px font sizes
- **Role:** Display and marketing headlines. The custom font elevates the brand's visual identity, especially with its precise letterSpacing and tight line heights, giving titles a sophisticated, controlled feel.

### ABC Normal Regular — Descriptive body text for prominent statements or feature descriptions, maintaining the brand's unique typographic voice at a slightly more readable weight. · `--font-abc-normal-regular`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 26px
- **Line height:** 1.31
- **Letter spacing:** 0.0100em
- **Role:** Descriptive body text for prominent statements or feature descriptions, maintaining the brand's unique typographic voice at a slightly more readable weight.

### Inter — All functional text, including navigation, body copy, button labels, and captions. Its broad weight and size range provide versatility for information hierarchy, while slight negative letter spacing on larger sizes maintains a polished, modern feel. · `--font-inter`
- **Substitute:** Inter Variable
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 22px, 24px
- **Line height:** 1.17, 1.33, 1.43, 1.45, 1.50, 1.57, 1.69, 2.00
- **Letter spacing:** -0.0200em at 24px, -0.0050em at 22px
- **Role:** All functional text, including navigation, body copy, button labels, and captions. Its broad weight and size range provide versatility for information hierarchy, while slight negative letter spacing on larger sizes maintains a polished, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 2 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.43 | — | `--text-body` |
| subheading | 22px | 1.57 | -0.22px | `--text-subheading` |
| heading | 24px | 1.45 | -0.48px | `--text-heading` |
| heading-lg | 26px | 1.31 | 0.26px | `--text-heading-lg` |
| display | 88px | 1 | -1.76px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 4px |
| default | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(204, 217, 224, 0.2) 0px -3px 0px 0px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.1) 0px 1px 0px 0px` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 72px
- **Card padding:** 30px
- **Element gap:** 16px

## Components

### Login Button
**Role:** Secondary call to action

Outline button with `Midnight Ink` (#171717) text and a 2px stroke border in `Ash Veil` (#e2e8eb). Has a 4px border radius. Padding is 0px top/bottom, 16px left/right.

### Input Field
**Role:** User data entry

Background `Cloud Burst` (#f6fafb), `Midnight Ink` (#171717) text. Border `Slate Echo` (#e4edf1) 0px radius. Padding 0px top/bottom, 18px left, 8px right. This input visually blends with the background suggesting a clear, unobstructed path for data.

### Process Step
**Role:** Sequential information display

Transparent background, no border radius, no shadow. Padding 0px top/bottom, 32px right, 0px left for the content block. Highlighted by `Violet Impulse` (#693edf) and its shades through the background shape, serving as active state indicators.

### Sub-Navigation Button
**Role:** Internal navigation

`Midnight Ink` (#171717) text on a transparent background with no border radius. Explicitly styled with padding 8px top/bottom, 24px left/right. Used for secondary navigation elements within sections.

### Tag Badge
**Role:** Categorization label

Transparent background, `Midnight Ink` (#171717) text. No border radius, no padding. Used for simple categorization and filtering.

### Primary Navigation Link
**Role:** Main site navigation

`Midnight Ink` (#171717) text on a transparent background, no border radius. These links have a hover state that brings out the `Violet Impulse` color, often as an underline.

## Do's and Don'ts

### Do
- Use `Violet Impulse` (#693edf) exclusively for primary CTAs and active states.
- Apply `Midnight Ink` (#171717) for all primary text, ensuring maximum contrast against light backgrounds.
- Maintain 4px `radius` for all general UI elements like cards and secondary buttons.
- Ensure input fields use `Cloud Burst` (#f6fafb) background and `Slate Echo` (#e4edf1) borders for consistent form styling.
- Prioritize `ABC Normal` font for all display headings to leverage its distinctive letter spacing and authoritative presence.
- Implement -0.0200em letter spacing for `ABC Normal` headlines at 48px and larger sizes.

### Don't
- Do not use shadows for elevation; emphasize depth through varied background colors and precise spacing.
- Avoid using `Violet Impulse` (#693edf) for body text or non-interactive elements, to preserve its impact as an accent.
- Do not introduce additional border radii; consistently use 4px or 0px.
- Refrain from using `Inter` for major headlines. Its role is for functional and extended text.
- Do not deviate from the established spacing unit; use multiples of 4px for all padding and margins.
- Avoid introducing additional visual accents or graphical elements that compete with the brand's violet spectrum.

## Imagery

The site uses a combination of abstract, geometric illustrations and product screenshots. Illustrations are brand-colored (shades of violet) and appear to abstract complex processes into clear, interconnected visual pathways (e.g., the branching flow on the hero section). Product screenshots, when present implicitly via card examples, are tightly framed and seem to showcase UI elements rather than full contexts. The overall approach is to use visuals for conceptual explanation or function demonstration, not for emotional connection or lifestyle imagery. Icons are filled, mono-color (Midnight Ink or Violet Impulse) and appear simple and illustrative rather than highly detailed, reinforcing clarity and directness. Imagery density is low, making text and UI elements dominant.

## Layout

The site employs a max-width contained layout, typically centered, with a default `sectionGap` of 72px creating ample vertical breathing room between content blocks. The hero section is full-bleed with a dark background and a central, large headline, immediately grounding the user. Most content sections alternate between text-left/image-right and image-left/text-right patterns, often within a 2-column grid. Feature lists are presented in 3-column card grids. The navigation is a sticky top bar, providing persistent access. The overall density is spacious, prioritizing readability and clear information hierarchy over packed content.

## Agent Prompt Guide

### Quick Color Reference
- Text: #171717
- Page Background: #f6fafb
- CTA Button: #693edf
- Border/Divider: #e4edf1
- Accent: #3b0d96

### 3-5 Example Component Prompts
1. Create a primary call to action button: `Violet Impulse` #693edf background, `White` #ffffff text, no border radius (0px), padding 18px vertical, 24px horizontal. Text is Inter Bold 700 at 16px.
2. Design a feature card: `Cloud Burst` #f6fafb background, 4px border radius. Padding 30px on all sides. Headline uses ABC Normal 500 at 28px, `Midnight Ink` #171717. Body text uses Inter 400 at 16px, `Midnight Ink` #171717.
3. Implement an input field: `Cloud Burst` #f6fafb background, `Slate Echo` #e4edf1 border, no border radius. Text input uses Inter 400 at 16px, `Midnight Ink` #171717. Padding 0px vertical, 18px left, 8px right.
4. Generate a section subheading: ABC Normal 600 at 56px, `Midnight Ink` #171717, letter-spacing -0.0200em.

## Similar Brands

- **Anthropic** — Uses a similar high-contrast, text-dominant interface with strong black/white typography and a single, vibrant accent color for interaction.
- **Vercel** — Employs an enterprise-grade dark/light theme, stark typography, and a strategic use of color for functional elements and status indicators, avoiding decorative imagery.
- **Linear** — Known for its clean, spacious layout, precise typography, and a functional design that foregrounds content with minimal visual distractions, akin to this site's approach.
- **Plaid** — Features a similar B2B SaaS aesthetic with a focus on structured information, clear visual hierarchy, and a restrained use of vibrant brand colors against a largely neutral palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #171717;
  --color-cloud-burst: #f6fafb;
  --color-slate-echo: #e4edf1;
  --color-ash-veil: #e2e8eb;
  --color-graphite-tone: #5d5d5d;
  --color-violet-impulse: #693edf;
  --color-deep-space-violet: #3b0d96;
  --color-dawn-violet: #c1b9f4;

  /* Typography — Font Families */
  --font-abc-normal: 'ABC Normal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-normal-regular: 'ABC Normal Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-subheading: 22px;
  --leading-subheading: 1.57;
  --tracking-subheading: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.45;
  --tracking-heading: -0.48px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.31;
  --tracking-heading-lg: 0.26px;
  --text-display: 88px;
  --leading-display: 1;
  --tracking-display: -1.76px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 30px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-buttons: 4px;
  --radius-default: 4px;

  /* Shadows */
  --shadow-subtle: rgba(204, 217, 224, 0.2) 0px -3px 0px 0px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 1px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #171717;
  --color-cloud-burst: #f6fafb;
  --color-slate-echo: #e4edf1;
  --color-ash-veil: #e2e8eb;
  --color-graphite-tone: #5d5d5d;
  --color-violet-impulse: #693edf;
  --color-deep-space-violet: #3b0d96;
  --color-dawn-violet: #c1b9f4;

  /* Typography */
  --font-abc-normal: 'ABC Normal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-normal-regular: 'ABC Normal Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-subheading: 22px;
  --leading-subheading: 1.57;
  --tracking-subheading: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.45;
  --tracking-heading: -0.48px;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.31;
  --tracking-heading-lg: 0.26px;
  --text-display: 88px;
  --leading-display: 1;
  --tracking-display: -1.76px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Shadows */
  --shadow-subtle: rgba(204, 217, 224, 0.2) 0px -3px 0px 0px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 1px 0px 0px;
}
```
