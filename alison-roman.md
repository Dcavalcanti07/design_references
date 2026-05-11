# Alison Roman — Style Reference
> worn book parchment

**Theme:** light

This design system cultivates a literary, artisanal aesthetic through its warm, muted color palette and distinctive serif typography. The layout emphasizes generous white space, drawing the eye to content with an ordered, almost editorial rhythm. Text is predominantly dark, almost black, set against soft, creamy backgrounds, creating a sense of quiet authority and inviting readability. A singular, deep reddish-brown accent color is reserved for buttons and active states, providing grounding punctuation against the otherwise muted tones. Visual elements embrace a raw, unadorned feel with sharp 0px radii.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment Cream | `#f6f0e1` | `--color-parchment-cream` | Page backgrounds, card surfaces, general canvas — provides a warm, inviting base |
| Ink Black | `#290a08` | `--color-ink-black` | Primary text, headings, button backgrounds, interactive elements — establishes a strong, legible presence against light backgrounds. This color also serves as the primary accent, creating functional contrast |
| Paper White | `#ffffff` | `--color-paper-white` | Button text contrast against Ink Black |
| Canvas Dust | `#e5e7eb` | `--color-canvas-dust` | Subtle borders and dividers, indicating soft visual separation without harsh lines |
| Amber Tint | `#fffaec` | `--color-amber-tint` | List item backgrounds, secondary surface fills |
| Fire Brick | `#810c00` | `--color-fire-brick` | Distinct background for prominent cards or sections, used sparingly for strong visual emphasis |
| Goldenrod Highlight | `#fff3cc` | `--color-goldenrod-highlight` | Link hover states, subtle accent for specific textual highlights—adds a touch of warmth |

## Tokens — Typography

### Jannon Neo — Primary headings and large display text — imparts an elegant, classic, and slightly formal tone with its refined serif form and subtly tight tracking. · `--font-jannon-neo`
- **Substitute:** Source Serif Pro
- **Weights:** 300, 400
- **Sizes:** 20px, 32px, 48px, 80px, 120px
- **Line height:** 1.00, 1.10, 1.30
- **Letter spacing:** -0.0300em at 120px, -0.0200em at 80px
- **Role:** Primary headings and large display text — imparts an elegant, classic, and slightly formal tone with its refined serif form and subtly tight tracking.

### Modale Antique — Body text, secondary headings, and emphasized content — a highly legible serif that anchors the editorial feel and carries the bulk of textual information. · `--font-modale-antique`
- **Substitute:** Lora
- **Weights:** 400, 500
- **Sizes:** 18px, 26px, 29px
- **Line height:** 1.00, 1.20, 1.50
- **Letter spacing:** -0.0100em
- **Role:** Body text, secondary headings, and emphasized content — a highly legible serif that anchors the editorial feel and carries the bulk of textual information.

### -apple-system — Fallback and utilitarian text elements where a system font is preferred or to provide clear contrast with the primary serif fonts. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 29px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Fallback and utilitarian text elements where a system font is preferred or to provide clear contrast with the primary serif fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 18px | 1.2 | — | `--text-caption` |
| body-sm | 26px | 1.2 | — | `--text-body-sm` |
| body | 29px | 1.2 | — | `--text-body` |

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
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Page max-width:** 1134px
- **Section gap:** 96px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Button
**Role:** Main call to action

Solid 'Ink Black' background with 'Paper White' text, 0px border radius, and generous horizontal padding of 32px; text is Modale Antique 18px 400 weight.

### Subtle Link
**Role:** Inline navigation and secondary actions

Modale Antique 18px 400 weight text in 'Ink Black' sometimes with 'Goldenrod Highlight' on hover. No underline by default; provides textual reference and navigation.

### Content Card - Default
**Role:** Displaying primary content blocks like product descriptions

Background is transparent, 0px border radius, padding of 24px on all sides. Content driven by typography and imagery without heavy chrome.

### Content Card - Emphasized
**Role:** Highlighting key content sections or product features

Background is 'Fire Brick', 0px border radius, with substantial padding (80px horizontal, 160px vertical). Used sparingly for high-impact content blocks.

### Section Header
**Role:** Main page headings

Jannon Neo, typically 80px or 120px at weight 300 or 400, in 'Ink Black', with tight letter-spacing (-0.0200em or -0.0300em) for a refined, impactful presence.

## Do's and Don'ts

### Do
- Use 'Parchment Cream' for all primary backgrounds to maintain the warm, inviting tone.
- Apply 'Ink Black' for all body text and main headings to ensure strong contrast and legibility.
- Utilize Jannon Neo for all large display headlines (48px and above) with its custom letter-spacing to achieve the distinctive elegant look.
- Maintain a 0px border radius for all UI elements to align with the unadorned, classic aesthetic.
- Prioritize generous vertical spacing, using 96px for section gaps and 48px for major content blocks, to create an open, comfortable layout.
- Reserve 'Ink Black' as a background color for buttons and 'Paper White' for button text to ensure call-to-actions are clear and utilize the brand's primary contrasting pair.
- Use 'Canvas Dust' for subtle borders, like `2px solid #e5e7eb`, to create soft divisions for elements such as image frames or subtle separators.

### Don't
- Avoid using bright, saturated colors outside of 'Fire Brick' and 'Goldenrod Highlight' accents to preserve the muted, sophisticated palette.
- Do not introduce rounded corners (any radius other than 0px) for any UI components, buttons, or cards.
- Do not use heavy box-shadows or gradients; the design relies on flat surfaces and clean typography for visual hierarchy.
- Do not deviate from Jannon Neo or Modale Antique for primary textual content; fallback to system fonts only when explicitly necessary for utility elements.
- Avoid dense, information-heavy sections; prioritize generous white space and comfortable content blocks.
- Do not add additional decorative elements or extensive iconography; the system is text and image-focused with minimal UI chrome.
- Do not use dark backgrounds for main content areas; maintain a light theme for readability unless in very specific, emphasized sections using 'Fire Brick'.

## Agent Prompt Guide

Quick Color Reference:
text: #290a08
background: #f6f0e1
border: #e5e7eb
accent: #810c00
primary action: #290a08 (filled action)

Example Component Prompts:
Create a Primary Action Button: #290a08 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a page section with a main heading: Jannon Neo 80px weight 300 in 'Ink Black' (#290a08), letter-spacing -0.0200em. Below it, add a body text block in Modale Antique 26px weight 400 in 'Ink Black' (#290a08).
Create a featured content card: background 'Fire Brick' (#810c00), 0px radius, 160px vertical padding, 80px horizontal padding. Inside, place text in Modale Antique 26px weight 400, 'Paper White' (#ffffff).
Create a standard text link: Modale Antique 18px weight 400 in 'Ink Black' (#290a08), line height 1.5. On hover, change text color to 'Goldenrod Highlight' (#fff3cc).
Create a subtle image frame: a 2px solid border in 'Canvas Dust' (#e5e7eb), 0px radius, enclosing an image that spans the content width.

## Similar Brands

- **Fallen Leaf Books** — Similar use of classic serif typography and a muted, warm color palette for an editorial, literary feel.
- **Kinfolk Magazine** — Shares a spacious, minimalist layout with high-quality photography and a focus on natural, earthy tones.
- **Margot & The Moon** — Comparable use of soft, off-white backgrounds, strong serif headlines, and minimal UI elements creating a refined, content-focused experience.
- **The Line** — Employs an unadorned, 'no-frills' aesthetic with clean lines, ample negative space, and a reliance on typography and photography to convey sophistication, often with 0px radii.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment-cream: #f6f0e1;
  --color-ink-black: #290a08;
  --color-paper-white: #ffffff;
  --color-canvas-dust: #e5e7eb;
  --color-amber-tint: #fffaec;
  --color-fire-brick: #810c00;
  --color-goldenrod-highlight: #fff3cc;

  /* Typography — Font Families */
  --font-jannon-neo: 'Jannon Neo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-modale-antique: 'Modale Antique', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 18px;
  --leading-caption: 1.2;
  --text-body-sm: 26px;
  --leading-body-sm: 1.2;
  --text-body: 29px;
  --leading-body: 1.2;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1134px;
  --section-gap: 96px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment-cream: #f6f0e1;
  --color-ink-black: #290a08;
  --color-paper-white: #ffffff;
  --color-canvas-dust: #e5e7eb;
  --color-amber-tint: #fffaec;
  --color-fire-brick: #810c00;
  --color-goldenrod-highlight: #fff3cc;

  /* Typography */
  --font-jannon-neo: 'Jannon Neo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-modale-antique: 'Modale Antique', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 18px;
  --leading-caption: 1.2;
  --text-body-sm: 26px;
  --leading-body-sm: 1.2;
  --text-body: 29px;
  --leading-body: 1.2;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-160: 160px;
}
```
