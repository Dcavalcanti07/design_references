# Glyphy — Style Reference
> Digital Arcade Canvas

**Theme:** light

Glyphy uses a playful, high-contrast aesthetic reminiscent of early web 2.0 with a modern twist. Its primary palette of black text on a pale cream background is punctuated by bright, vivid color gradients for content sections, creating distinct visual energy. Typography combines bold, blocky headlines with pixelated system fonts for a retro-digital feel. Component radii are generous, favoring rounded capsules over sharp corners, contributing to a friendly, accessible interface despite the stark black-on-cream base.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Cream | `#fef9e6` | `--color-canvas-cream` | Page backgrounds, light interactive surfaces, active states in neutral buttons |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong borders and outlines, general iconography |
| Dark Onyx | `#060606` | `--color-dark-onyx` | Button backgrounds, dark interactive surfaces, subtle borders on dark elements |
| Stone Whisper | `#c7c3b4` | `--color-stone-whisper` | Subtle borders for cards and inactive interactive elements, muted structural divisions |
| Steel Gray | `#8d8b80` | `--color-steel-gray` | Secondary text, muted helper text, subtle outlines on cards |
| Sunny Glow | `#fdc331` | `--color-sunny-glow` | Background for accent sections, particularly for primary content categories |
| Sunset Orange | `#fe5722` | `--color-sunset-orange` | Background for accent sections, creating visual progression |
| Vivid Scarlet | `#f0353c` | `--color-vivid-scarlet` | Background for accent sections, indicating a strong point of interest |
| Berry Rouge | `#b4213d` | `--color-berry-rouge` | Background for accent sections, deeper saturation for content distinction |
| Plum Wine | `#671c3b` | `--color-plum-wine` | Background for accent sections, the darkest and most subdued of the color bands |

## Tokens — Typography

### Neue Machina — Primary headlines and navigation links — strong, industrial, and impactful, reserving higher weights for maximum emphasis. · `--font-neue-machina`
- **Substitute:** Space Mono
- **Weights:** 400, 700, 800
- **Sizes:** 21px, 64px, 120px
- **Line height:** 0.75, 1.00
- **Role:** Primary headlines and navigation links — strong, industrial, and impactful, reserving higher weights for maximum emphasis.

### __system85_8a4f0d — Body text, general UI labels, and action text — practical and clear, providing a functional contrast to the display fonts. · `--font-system858a4f0d`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 14px, 16px, 18px, 24px, 32px, 40px
- **Line height:** 1.00, 1.20
- **Role:** Body text, general UI labels, and action text — practical and clear, providing a functional contrast to the display fonts.

### __pixelMPlus10_ff679b — Decorative labels and meta-information fields — adds a distinct retro-digital flavor, especially for Japanese text alongside English headings. · `--font-pixelmplus10ff679b`
- **Substitute:** Press Start 2P
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 18px, 24px, 64px
- **Line height:** 1.00, 1.33
- **Role:** Decorative labels and meta-information fields — adds a distinct retro-digital flavor, especially for Japanese text alongside English headings.

### Arial — Legacy content and embedded elements where specific font rendering is not critical. Used sparingly. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 32px, 64px
- **Line height:** 1.00, 1.33
- **Role:** Legacy content and embedded elements where specific font rendering is not critical. Used sparingly.

### __system85Mono_15db00 — Monospaced text for specific cards or code-like displays. · `--font-system85mono15db00`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00
- **Role:** Monospaced text for specific cards or code-like displays.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | — | `--text-caption` |
| body-sm | 14px | 1 | — | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 21px | 1 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 32px | 1 | — | `--text-heading-lg` |
| display | 64px | 1 | — | `--text-display` |
| display-xl | 120px | 0.75 | — | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| buttons | 28px |
| callouts | 14px |
| navigation | 14px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Dark Button
**Role:** Filled button for main actions on light backgrounds

Background #060606, text #fef9e6, 28px border-radius. Padding 24px vertical, 32px horizontal.

### Light Outline Button
**Role:** Outlined button for secondary actions on dark backgrounds.

Background transparent, text #fef9e6, border 1px solid #fef9e6, 16px border-radius. Padding 0px vertical, 10px horizontal.

### Light Fill Button
**Role:** Filled button for main actions on dark backgrounds.

Background #fef9e6, text #060606, 16px border-radius. Padding 0px vertical, 10px horizontal.

### Muted Outline Button
**Role:** Outlined button for secondary actions on light backgrounds.

Background transparent, text #000000, border 1px solid #c7c3b4, 28px border-radius. Padding 24px vertical, 32px horizontal.

### Section Callout Card
**Role:** Informational cards within sections, driving to deeper content.

Background #fef9e6, border 1px solid #c7c3b4, 14px border-radius. No explicit padding, utilizes section spacing.

### Content List Item
**Role:** Row item within content lists, often with a unique background color.

Dynamic background color (e.g., #fdc331, #fe5722), text #000000. No explicit padding or border-radius on the item itself, its section dictates styling.

## Do's and Don'ts

### Do
- Always use Canvas Cream (#fef9e6) as the primary page background color for all content areas.
- Utilize Midnight Ink (#000000) for all primary text and critical UI borders to maintain high contrast.
- Apply a 28px border-radius to all primary action buttons for a consistent capsule shape.
- Use Neue Machina for section headlines and __pixelMPlus10_ff679b for subtle supporting labels that need a retro digital feel.
- When creating content sections, use the vivid color progression (#fdc331, #fe5722, #f0353c, #b4213d, #671c3b) to clearly delineate areas.
- Maintain a spacious density with a base element gap of 8px and section gaps of 40px to prevent visual clutter.

### Don't
- Do not use dark backgrounds for general page content; restrict Dark Onyx (#060606) to specific button fills or interactive elements.
- Avoid using multiple border styles or colors on a single component; adhere to either Midnight Ink (#000000), Stone Whisper (#c7c3b4), or Dark Onyx (#060606).
- Do not mix __pixelMPlus10_ff679b with regular body text; its distinct style should be reserved for decorative or specific data labels.
- Avoid arbitrary radius values; stick to 28px for buttons and 14px for cards/containers.
- Do not introduce new vivid colors outside the defined gradient progression for content sections.
- Do not use text-shadows or drop-shadows on text; rely on strong contrast for legibility.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Cream | `#fef9e6` | Dominant page and content background. |
| 1 | Dark Onyx | `#060606` | Background for primary buttons and specific interactive areas within lighter sections. |
| 2 | Vivid Gradient Bands | `#fdc331` | Sequential, distinct background colors for major content sections, creating visual rhythm. |

## Imagery

This site predominantly uses clean, functional UI elements and custom typography as its primary visual language, rather than traditional imagery. Icons are minimal, outlined, and monochromatic, primarily serving as functional cues within navigation or interactive elements (like the 'view →' arrow). Text itself is treated as a visual element, heavily stylized with custom fonts. When product examples (like specialized fonts) are shown, they are presented simply on a black or cream background without additional photographic context. The overall impression is text-dominant and graphically stark, with stylized unicode characters acting as decorative embellishments.

## Layout

The layout is primarily max-width contained, although the main hero section can stretch full-bleed on wider screens. The hero features a large, centered brand name with a supporting tagline. Sections are arranged in a strong vertical stack, with a consistent 40px section gap. Distinctive alternating background colors (#fef9e6 or one of the vivid gradient hues) clearly delineate these sections. Content within sections tends to be horizontally responsive, often employing a grid for feature listings (e.g., 3-column card grid for font generators) or left-aligned text blocks. The overall density is spacious, ensuring content breathability. Navigation is a simple top bar, with the brand name on the left and primary links centered, and a sticky header for consistent access.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #fef9e6
- border: #c7c3b4
- accent: #fdc331
- primary action: #060606 (filled action)

**3-5 Example Component Prompts:**
- Create a section divider using Sunny Glow (#fdc331) as the full-width background, with text "Font Generator" (Neue Machina, 700, 40px size, #000000) left-aligned and a 'Try now →' button (Light Outline Button: text #000000, border #000000, 16px radius, 0px vertical 10px horizontal padding).
- Create a Primary Dark Button: background #060606, text #fef9e6, 28px border-radius, 24px vertical 32px horizontal padding, with a label "Generate Fancy Text" (Neue Machina, 400, 21px size).
- Design a feature card displaying a font preview: background #fef9e6, border 1px solid #c7c3b4, 14px border-radius. Title 'Instagram Fonts' (body-sm, __system85_8a4f0d, 700, #000000) and a preview text using a stylized font (display, Arial 64px, #000000).
- Create a header with the logo 'GLYPHY' (Neue Machina, 800, 120px size, #000000) and supporting text 'Copy & paste fancy fonts + cool symbols' (body-sm, __system85_8a4f0d, 400, #000000) aligned under the brand name.

## Similar Brands

- **Cooltext** — Shares a focus on text-based utility tools with stylized output, featuring a similar no-frills, high-contrast UI.
- **FancyTextGuru** — Offers similar functionality around font generation and symbols, often using simple, direct UI with contrasting blocks of content.
- **Picular** — Utilizes a functional, distinct palette of bold colors for content categorization, similar to Glyphy's gradient bands.
- **TextFX** — Provides text manipulation services, and often features a direct, utility-focused interface with clear, bold typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-cream: #fef9e6;
  --color-midnight-ink: #000000;
  --color-dark-onyx: #060606;
  --color-stone-whisper: #c7c3b4;
  --color-steel-gray: #8d8b80;
  --color-sunny-glow: #fdc331;
  --color-sunset-orange: #fe5722;
  --color-vivid-scarlet: #f0353c;
  --color-berry-rouge: #b4213d;
  --color-plum-wine: #671c3b;

  /* Typography — Font Families */
  --font-neue-machina: 'Neue Machina', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system858a4f0d: '__system85_8a4f0d', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pixelmplus10ff679b: '__pixelMPlus10_ff679b', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system85mono15db00: '__system85Mono_15db00', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;
  --text-display-xl: 120px;
  --leading-display-xl: 0.75;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-3xl: 28px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-buttons: 28px;
  --radius-callouts: 14px;
  --radius-navigation: 14px;

  /* Surfaces */
  --surface-canvas-cream: #fef9e6;
  --surface-dark-onyx: #060606;
  --surface-vivid-gradient-bands: #fdc331;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-cream: #fef9e6;
  --color-midnight-ink: #000000;
  --color-dark-onyx: #060606;
  --color-stone-whisper: #c7c3b4;
  --color-steel-gray: #8d8b80;
  --color-sunny-glow: #fdc331;
  --color-sunset-orange: #fe5722;
  --color-vivid-scarlet: #f0353c;
  --color-berry-rouge: #b4213d;
  --color-plum-wine: #671c3b;

  /* Typography */
  --font-neue-machina: 'Neue Machina', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system858a4f0d: '__system85_8a4f0d', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pixelmplus10ff679b: '__pixelMPlus10_ff679b', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system85mono15db00: '__system85Mono_15db00', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;
  --text-display-xl: 120px;
  --leading-display-xl: 0.75;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-3xl: 28px;
}
```
