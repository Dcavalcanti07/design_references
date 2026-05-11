# Forner — Style Reference
> Earthy, typographic canvas

**Theme:** light

Forner presents a refined, almost austere aesthetic, balancing a limited palette of warm, earthy neutrals with expansive whitespace. Typography takes center stage, featuring distinct display and accent typefaces that exude a quiet confidence. The overall impression is one of intentionality and understated luxury, where visual silence amplifies the impact of carefully chosen elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon Ink | `#484036` | `--color-carbon-ink` | Primary text, darkened background surface, prominent borders |
| Canvas White | `#ecece4` | `--color-canvas-white` | Page backgrounds, large content surfaces, primary UI fill |
| Stone Gray | `#cacab0` | `--color-stone-gray` | Subtle borders, inactive text elements, decorative accents |
| Warm Mist | `#d5d5c4` | `--color-warm-mist` | Muted link text and subtle interactive borders |
| Pale Linen | `#f2e9cf` | `--color-pale-linen` | Subtle background washes, light decorative borders |
| Ash Gray | `#666e72` | `--color-ash-gray` | Secondary text, less prominent borders |
| Deep Charcoal | `#212529` | `--color-deep-charcoal` | High-contrast text elements, critical informational accents |
| Rich Wood | `#33302c` | `--color-rich-wood` | Specific heading text for emphasis, dark borders |

## Tokens — Typography

### ClashDisplay — Primary headings and emphatic titles for clarity and modern presence. · `--font-clashdisplay`
- **Substitute:** General Sans
- **Weights:** 400
- **Sizes:** 17px, 30px, 52px, 56px
- **Line height:** 0.97, 0.98, 1.10, 1.13
- **Letter spacing:** -0.0100em, 0.0200em
- **Role:** Primary headings and emphatic titles for clarity and modern presence.

### Surt — Prominent display text, primary navigation, and large headline elements. Its extended proportions give it a distinct, confident voice. · `--font-surt`
- **Substitute:** Archivo Expanded
- **Weights:** 400
- **Sizes:** 22px, 29px, 45px, 56px, 112px
- **Line height:** 0.98, 1.00, 1.03, 1.10, 1.35, 1.50
- **Letter spacing:** -0.0400em, 0.0110em
- **Role:** Prominent display text, primary navigation, and large headline elements. Its extended proportions give it a distinct, confident voice.

### BigDailyShort — Decorative accents, subheadings, and stylistic quotes. The light italic treatment adds a touch of unconventional elegance. · `--font-bigdailyshort`
- **Substitute:** Playfair Display Italic
- **Weights:** 400
- **Sizes:** 17px, 37px, 45px
- **Line height:** 0.98, 1.00, 1.03
- **Letter spacing:** -0.0500em, 0.0110em, 0.0200em
- **Role:** Decorative accents, subheadings, and stylistic quotes. The light italic treatment adds a touch of unconventional elegance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 17px | 1.5 | 0.34px | `--text-body-sm` |
| body | 22px | 1.35 | -0.88px | `--text-body` |
| subheading | 29px | 1.1 | 0.32px | `--text-subheading` |
| heading | 45px | 1.03 | -2.25px | `--text-heading` |
| heading-lg | 56px | 1 | -2.24px | `--text-heading-lg` |
| display | 112px | 0.98 | -4.48px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 14 | 14px | `--spacing-14` |
| 29 | 29px | `--spacing-29` |
| 43 | 43px | `--spacing-43` |
| 58 | 58px | `--spacing-58` |
| 68 | 68px | `--spacing-68` |
| 86 | 86px | `--spacing-86` |
| 100 | 100px | `--spacing-100` |
| 121 | 121px | `--spacing-121` |
| 144 | 144px | `--spacing-144` |
| 161 | 161px | `--spacing-161` |
| 232 | 232px | `--spacing-232` |
| 233 | 233px | `--spacing-233` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 4px |

### Layout

- **Section gap:** 86px
- **Card padding:** 29px
- **Element gap:** 14px

## Components

### Ghost Navigation Button
**Role:** Menu navigation icon/button

Minimalist navigation toggle with transparent background, 'Carbon Ink' text, and a hairline 'Stone Gray' border that appears on hover/focus. Text has 'Surt' font at 22px, with 0 tracking.

## Do's and Don'ts

### Do
- Prioritize 'Canvas White' (#ecece4) for primary backgrounds to maintain expansiveness, contrasting with 'Carbon Ink' (#484036) for text.
- Use 'Surt' for large, impactful headlines at sizes like 56px and 112px, setting `letter-spacing` to -0.0400em for a tight, elegant feel.
- Apply the `letter-spacing` values specified in the typography section precisely, especially the negative values for display type, to convey the signature typographic character.
- Employ 'BigDailyShort' at 37px or 45px with an italic style for decorative subheadings or impactful quotes, ensuring -0.0500em letter-spacing for distinction.
- Implement a minimal border radius of 4px for elements requiring subtle definition, such as cards or outlined interactive components.
- Maintain generous vertical spacing using 86px for section gaps, creating visual pauses between content blocks.
- Use 'Stone Gray' (#cacab0) for subtle borders on interactive elements, avoiding strong outlines to keep the aesthetic lightweight.

### Don't
- Avoid using highly saturated or vibrant chromatic colors; the system relies on a restrained neutral palette with subtle shifts in tone.
- Do not use heavy box shadows or strong elevation effects; the design language favors flat surfaces and minimal depth.
- Refrain from dense, information-packed layouts; instead, embrace ample whitespace and a generous `elementGap` of 14px to promote readability.
- Do not deviate from the specified `letter-spacing` values; they are crucial for the distinct typographic voice of the brand.
- Avoid large, filled primary action buttons; interactive elements lean towards ghost buttons or subtle text links with implicit affordance.
- Do not introduce decorative gradients or complex overlays; the system prefers clean, solid color applications.
- Omit using generic system fonts; `Surt`, `ClashDisplay`, and `BigDailyShort` define the brand's unique typographic identity.

## Agent Prompt Guide

Quick Color Reference:
text: #484036
background: #ecece4
border: #cacab0
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: 'Canvas White' (#ecece4) background. Headline 'Surt' at 112px, #484036, letter-spacing -4.48px. Beneath it, a subtext in 'BigDailyShort' at 45px, '#484036', letter-spacing -2.25px.
2. Design a 'Menu' button: ghost style with 'Carbon Ink' (#484036) text and a hairline 'Stone Gray' (#cacab0) 1px border. Text should be 'Surt' 22px, with `letter-spacing` 0.0110em. Padding should respect general element spacing.
3. Implement a project card: 'Pale Linen' (#f2e9cf) background, 4px border radius. Title in 'ClashDisplay' 52px, #484036, letter-spacing -0.52px. Description text using 'Surt' 22px, #484036, with letter-spacing 0.32px. Use 29px padding for content.

## Similar Brands

- **Huge Inc.** — Employs an expansive, minimalist aesthetic with a focus on oversized typography and generous whitespace.
- **Pentagram** — Known for highly artistic and concept-driven graphic design that often translates to web, prioritizing strong typographic statements.
- **Studiometa** — Features a similar blend of sophisticated, often custom, typography with a restrained color palette and spacious layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon-ink: #484036;
  --color-canvas-white: #ecece4;
  --color-stone-gray: #cacab0;
  --color-warm-mist: #d5d5c4;
  --color-pale-linen: #f2e9cf;
  --color-ash-gray: #666e72;
  --color-deep-charcoal: #212529;
  --color-rich-wood: #33302c;

  /* Typography — Font Families */
  --font-clashdisplay: 'ClashDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-surt: 'Surt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bigdailyshort: 'BigDailyShort', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 17px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.34px;
  --text-body: 22px;
  --leading-body: 1.35;
  --tracking-body: -0.88px;
  --text-subheading: 29px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.32px;
  --text-heading: 45px;
  --leading-heading: 1.03;
  --tracking-heading: -2.25px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.24px;
  --text-display: 112px;
  --leading-display: 0.98;
  --tracking-display: -4.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-14: 14px;
  --spacing-29: 29px;
  --spacing-43: 43px;
  --spacing-58: 58px;
  --spacing-68: 68px;
  --spacing-86: 86px;
  --spacing-100: 100px;
  --spacing-121: 121px;
  --spacing-144: 144px;
  --spacing-161: 161px;
  --spacing-232: 232px;
  --spacing-233: 233px;

  /* Layout */
  --section-gap: 86px;
  --card-padding: 29px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon-ink: #484036;
  --color-canvas-white: #ecece4;
  --color-stone-gray: #cacab0;
  --color-warm-mist: #d5d5c4;
  --color-pale-linen: #f2e9cf;
  --color-ash-gray: #666e72;
  --color-deep-charcoal: #212529;
  --color-rich-wood: #33302c;

  /* Typography */
  --font-clashdisplay: 'ClashDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-surt: 'Surt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bigdailyshort: 'BigDailyShort', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 17px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.34px;
  --text-body: 22px;
  --leading-body: 1.35;
  --tracking-body: -0.88px;
  --text-subheading: 29px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.32px;
  --text-heading: 45px;
  --leading-heading: 1.03;
  --tracking-heading: -2.25px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.24px;
  --text-display: 112px;
  --leading-display: 0.98;
  --tracking-display: -4.48px;

  /* Spacing */
  --spacing-14: 14px;
  --spacing-29: 29px;
  --spacing-43: 43px;
  --spacing-58: 58px;
  --spacing-68: 68px;
  --spacing-86: 86px;
  --spacing-100: 100px;
  --spacing-121: 121px;
  --spacing-144: 144px;
  --spacing-161: 161px;
  --spacing-232: 232px;
  --spacing-233: 233px;

  /* Border Radius */
  --radius-md: 4px;
}
```
