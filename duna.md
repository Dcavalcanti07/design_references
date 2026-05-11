# Duna — Style Reference
> Understated Compliance Authority

**Theme:** light

Duna employs a quietly confident and sophisticated aesthetic, characterized by a near-monochromatic palette and subtle textural shifts. Typography is precise and highly tracked, creating a sense of understated authority. Surfaces are clean and layered, with minimal elevation, allowing content to take precedence. The overall impression is one of grounded reliability, eschewing overt flash for refined clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong headings, critical icons, high-contrast borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, ghost button backgrounds, default borders |
| Near White | `#f7f7f5` | `--color-near-white` | Subtle section backgrounds, alternate surface treatment, cookie banner background |
| Deep Charcoal | `#292421` | `--color-deep-charcoal` | Secondary headings, prominent body text, darker icons and fills |
| Subtle Gray | `#898683` | `--color-subtle-gray` | Muted body text, helper text, subtle borders |
| Card Wash | `#edece7` | `--color-card-wash` | Distinct card background color, differentiating content blocks from the canvas |
| Quiet Black | `#1a1816` | `--color-quiet-black` | Tertiary text, icon fills, understated borders |
| Medium Gray | `#444444` | `--color-medium-gray` | Input placeholder text, cookie banner text |
| Onyx Button Background | `#160f0c` | `--color-onyx-button-background` | Filled button backgrounds for primary calls to action |
| Light Steel | `#b2afae` | `--color-light-steel` | Decorative icon fills, subtle illustrative elements |
| Slate Text | `#0d0d0d` | `--color-slate-text` | Dark body text, dark icon strokes |
| Input Fill | `#eeeeee` | `--color-input-fill` | Input field background color |
| Accent Purple | `#1b0624` | `--color-accent-purple` | Heading color, brand accents, selected decorative borders/strokes — a subtle, dark chromatic touch that feels like a shadow, not a highlight |
| Muted Slate | `#766a7c` | `--color-muted-slate` | Small informational button backgrounds (e.g., news announcements) — a desaturated, almost neutral chromatic tint |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### GT America — Primary typeface for all headings, body text, and links. The varied tracking values create a sophisticated, tailored feel, with tighter spacing for larger display text and normal spacing for smaller body text. · `--font-gt-america`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.50
- **Letter spacing:** -0.0600em at 72px, -0.0500em at 44px, normal at 14px
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary typeface for all headings, body text, and links. The varied tracking values create a sophisticated, tailored feel, with tighter spacing for larger display text and normal spacing for smaller body text.

### GT America Trial Rg — Specific body text usage, particularly for descriptive paragraphs where slightly looser tracking is preferred. · `--font-gt-america-trial-rg`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.50, 1.60, 1.71
- **Letter spacing:** normal
- **Role:** Specific body text usage, particularly for descriptive paragraphs where slightly looser tracking is preferred.

### GT America Trial Md — Used for specific large headings and numerical data, leveraging tabular figures for alignment and slightly tighter tracking for impact. · `--font-gt-america-trial-md`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 17px, 80px
- **Line height:** 1.00, 1.76
- **Letter spacing:** -0.0120em
- **OpenType features:** `"tnum" on, "zero" on`
- **Role:** Used for specific large headings and numerical data, leveraging tabular figures for alignment and slightly tighter tracking for impact.

### GT America Medium — Used for emphasized body text or subheadings, with a distinct negative letter-spacing for a condensed appearance. · `--font-gt-america-medium`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.50
- **Letter spacing:** -0.0200em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Used for emphasized body text or subheadings, with a distinct negative letter-spacing for a condensed appearance.

### Inter — Supplemental font for card details and some smaller body text, used in contexts requiring greater system font fallback stability. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.20, 1.50
- **Letter spacing:** normal
- **Role:** Supplemental font for card details and some smaller body text, used in contexts requiring greater system font fallback stability.

### GT America Regular — GT America Regular — detected in extracted data but not described by AI · `--font-gt-america-regular`
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 44px, 72px
- **Line height:** 1, 1.1, 1.2, 1.3, 1.4, 1.5
- **Letter spacing:** -0.06, -0.05, -0.03, -0.02, -0.01, -0.006, 0.02
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** GT America Regular — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.71 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 20px | 1.5 | -0.4px | `--text-heading-sm` |
| heading | 24px | 1.3 | -0.72px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.96px | `--text-heading-lg` |
| display | 40px | 1.1 | -2px | `--text-display` |
| display-lg | 44px | 1.1 | -2.2px | `--text-display-lg` |
| display-xl | 72px | 1 | -4.32px | `--text-display-xl` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 140 | 140px | `--spacing-140` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| images | 24px |
| inputs | 8px |
| buttons | 999px |
| smallElements | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Main call to action button.

Background: Onyx Button Background (#160f0c), Text: Canvas White (#ffffff), Border Radius: 999px, Padding: 8px vertical, 14px horizontal.

### Ghost Button
**Role:** Secondary action or navigation outside of primary flows.

Background: transparent (rgba(26, 23, 21, 0)), Text: Midnight Ink (#000000), Border: 1px Midnight Ink (#000000), Border Radius: 999px, Padding: 6px vertical, 20px horizontal.

### Announcement Pill
**Role:** Small, informational component to highlight news or status.

Background: Muted Slate (#766a7c), Text: Canvas White (#ffffff) / Midnight Ink (#000000) (if dark background), Border Radius: 999px, Padding: 6px vertical, 20px horizontal.

### Simple Card
**Role:** Basic container for information, features a subtle background to distinguish from canvas.

Background: Card Wash (#edece7), Border Radius: 16px, Box Shadow: none, Padding: 0px.

### Elevated Card
**Role:** Interactive or featured card with a light shadow for depth.

Background: Canvas White (#ffffff), Border Radius: 14px, Box Shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset, Padding: 0px.

### Text Input Active
**Role:** User input field.

Background: Input Fill (#eeeeee), Text: Medium Gray (#444444), Placeholder: Medium Gray (#444444), Border: 1px Medium Gray (#444444), Border Radius: 8px, Padding: 10px.

### Navigation Link
**Role:** Top-level navigation items.

Text: Midnight Ink (#000000), Hover: Underlined with Midnight Ink (#000000) (not observed but inferred). No distinct background, padding for interactive area: 4px vertical, 6px horizontal.

### Cookie Consent Banner
**Role:** Non-intrusive notification banner.

Background: Near White (#f7f7f5), Text: Medium Gray (#444444), Border Radius: Not specified, but implied from overall shape language.

## Do's and Don'ts

### Do
- Use GT America with specific letter-spacing adjustments for all headings to maintain the refined and precise typographic hierarchy.
- Utilize Canvas White (#ffffff) as the dominant page background, reserving Near White (#f7f7f5) for subtle section differentiation or specific component backgrounds.
- Apply a 999px border-radius to all buttons and small interactive elements to achieve a consistent pill-like shape.
- Distinguish cards by using either Card Wash (#edece7) for simple containers or Canvas White (#ffffff) with an inset shadow for elevated content.
- Prioritize Onyx Button Background (#160f0c) with Canvas White (#ffffff) text for primary calls to action, maintaining a premium, understated feel.
- Employ Accent Purple (#1b0624) sparingly and strategically for impactful headings or brand-specific graphical elements, not as a general accent color.
- Maintain comfortable element spacing using a base unit of 10px, with larger gaps for sections to ensure content breathing room.

### Don't
- Avoid using highly saturated colors for interface elements; the brand relies on a nearly monochromatic palette with restrained chromatic accents.
- Do not use heavy drop shadows; elevation is primarily conveyed through subtle background shifts and a very soft inset shadow on specific cards.
- Do not introduce decorative borders or strong differentiating lines; surfaces are generally seamless or subtly defined by background color changes.
- Never use generic system fonts for headings or body text; always map to the GT America family to preserve the distinct typographic personality.
- Avoid arbitrary radius values; adhere to the established radii of 999px for buttons, 16px for cards, and 8px for inputs.
- Do not implement complex gradients or bold background patterns; the system favors clean, flat surfaces.
- Do not vary line-height aggressively across body text; stick to the established ratios to maintain consistent reading rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background, base for most content blocks. |
| 2 | Near White | `#f7f7f5` | Secondary section background, providing subtle differentiation without strong contrast. |
| 3 | Input Fill | `#eeeeee` | Background for interactive input fields. |
| 4 | Card Wash | `#edece7` | Specific card background, providing a slightly darker, more opaque surface than the canvas. |

## Elevation

- **Elevated Card:** `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset`

## Imagery

Imagery primarily consists of evocative, painted landscape illustrations acting as large background heroes, featuring muted sunrise/sunset tones with soft, organic forms. Product imagery uses tightly cropped, detailed product screenshots or abstract graphics to illustrate concepts, often isolated on clean white backgrounds. Icons are minimal, outlined, monochromatic, and used for functional clarity rather than excessive decoration. The overall density is text-dominant, with imagery serving as atmospheric backdrops or focused explanatory elements.

## Layout

The page primarily uses a max-width contained layout, likely around 1200px, horizontally centered. The hero section is full-bleed with a large illustrative background and centered headline, followed by a 'news pill' that breaks the full-width image. Subsequent sections feature a consistent vertical rhythm, often with a centered stack of content (headline, body, buttons) or multi-column grids for features and data. There's a subtle alternating section pattern, primarily between Canvas White (#ffffff) and Near White (#f7f7f5) backgrounds. Navigation is a sticky top bar with left-aligned branding and right-aligned buttons/links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #1b0624
primary action: #160f0c (filled action)

Example Component Prompts:
Create a hero section: full-bleed background set to a painted landscape illustration. Centered headline at 72px GT America, Accent Purple (#1b0624), letter-spacing -0.0600em. Subtext at 18px GT America, Subtle Gray (#898683), letter-spacing normal. Primary filled button below subtext: Onyx Button Background (#160f0c), Canvas White (#ffffff) text, 999px radius, 8px vertical 14px horizontal padding.

Create a feature card: Elevated Card with Canvas White (#ffffff) background, 14px radius, rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset shadow. Headline at 24px GT America, Midnight Ink (#000000), letter-spacing -0.0300em. Body text at 16px GT America Trial Rg, Deep Charcoal (#292421).

Create a ghost navigation button: Transparent background, Midnight Ink (#000000) text, 1px Midnight Ink (#000000) border, 999px radius, 6px vertical 20px horizontal padding, GT America 400 weight.

## Similar Brands

- **Linear** — Monochromatic interface with precise typography and subtle elevation, focused on content clarity.
- **Stripe** — Clean, understated aesthetic with a disciplined use of typography and a minimalist color palette for UI elements.
- **Amie** — Light canvas, highly compact typography, and a deliberate absence of strong chromatic accents in the main UI.
- **Anthropic** — Heavy reliance on clean neutrals, sophisticated typography, and minimal use of color to convey authority and seriousness.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-near-white: #f7f7f5;
  --color-deep-charcoal: #292421;
  --color-subtle-gray: #898683;
  --color-card-wash: #edece7;
  --color-quiet-black: #1a1816;
  --color-medium-gray: #444444;
  --color-onyx-button-background: #160f0c;
  --color-light-steel: #b2afae;
  --color-slate-text: #0d0d0d;
  --color-input-fill: #eeeeee;
  --color-accent-purple: #1b0624;
  --color-muted-slate: #766a7c;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-trial-rg: 'GT America Trial Rg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-trial-md: 'GT America Trial Md', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-medium: 'GT America Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-regular: 'GT America Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.71;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.72px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -2px;
  --text-display-lg: 44px;
  --leading-display-lg: 1.1;
  --tracking-display-lg: -2.2px;
  --text-display-xl: 72px;
  --leading-display-xl: 1;
  --tracking-display-xl: -4.32px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-140: 140px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 60px;
  --radius-full-2: 99px;
  --radius-full-3: 799px;
  --radius-full-4: 959px;
  --radius-full-5: 999px;
  --radius-full-6: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-images: 24px;
  --radius-inputs: 8px;
  --radius-buttons: 999px;
  --radius-smallelements: 12px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-near-white: #f7f7f5;
  --surface-input-fill: #eeeeee;
  --surface-card-wash: #edece7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-near-white: #f7f7f5;
  --color-deep-charcoal: #292421;
  --color-subtle-gray: #898683;
  --color-card-wash: #edece7;
  --color-quiet-black: #1a1816;
  --color-medium-gray: #444444;
  --color-onyx-button-background: #160f0c;
  --color-light-steel: #b2afae;
  --color-slate-text: #0d0d0d;
  --color-input-fill: #eeeeee;
  --color-accent-purple: #1b0624;
  --color-muted-slate: #766a7c;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america: 'GT America', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-trial-rg: 'GT America Trial Rg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-trial-md: 'GT America Trial Md', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-medium: 'GT America Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-regular: 'GT America Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.71;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.72px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.96px;
  --text-display: 40px;
  --leading-display: 1.1;
  --tracking-display: -2px;
  --text-display-lg: 44px;
  --leading-display-lg: 1.1;
  --tracking-display-lg: -2.2px;
  --text-display-xl: 72px;
  --leading-display-xl: 1;
  --tracking-display-xl: -4.32px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-140: 140px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 60px;
  --radius-full-2: 99px;
  --radius-full-3: 799px;
  --radius-full-4: 959px;
  --radius-full-5: 999px;
  --radius-full-6: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;
}
```
