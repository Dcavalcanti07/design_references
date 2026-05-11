# Duolingo — Style Reference
> Playful Green Arcade

**Theme:** light

This design system feels like a vibrant, welcoming arcade where learning is a game. The dominant vivid green (#58cc02) and rounded forms, especially the 12px border-radius buttons, create a friendly, approachable atmosphere, softening the otherwise crisp text. Typographic hierarchy is clear with distinct weights and sizes for headings and body, often anchored by a deeper neutral (#4b4b4b and #3c3c3c) that provides stability to the lively greens and blues. A crisp white background allows the saturated brand colors and whimsical illustrations to pop, fostering a sense of fun and engagement.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Duolingo Green | `#58cc02` | `--color-duolingo-green` | Observed in heading borderColor, heading color, other backgroundColor. Extracted usage does not support a distinct primary control color. |
| Background Green Accent | `#d7ffb8` | `--color-background-green-accent` | Subtle green accent for backgrounds and decorative borders, creating a gentle contrast with the primary green without overwhelming the eye. |
| Action Blue | `#1cb0f6` | `--color-action-blue` | Link text and ghost button borders, providing an alternate vibrant interactive color that stands out from the dominant green. |
| Dark Heading Blue | `#042c60` | `--color-dark-heading-blue` | Specific heading text and borders, adding depth and an alternative vibrant hue for important textual elements. |
| Deep Violet Accent | `#000437` | `--color-deep-violet-accent` | Specific button text and body text, providing a striking, almost black contrast that hints at an alternative dark mode aesthetic. |
| Shadowed Pine | `#3c3c3c` | `--color-shadowed-pine` | General text, borders for lists and other elements, providing a strong readable neutral for content. |
| Jet Black | `#000000` | `--color-jet-black` | Decorative SVG fills, ensuring high contrast for illustrative elements. |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, surface colors, and text on darker backgrounds. |
| Cloud Gray | `#777777` | `--color-cloud-gray` | Secondary text and navigation elements, providing a softer, muted contrast than Shadowed Pine. |
| Charcoal Text | `#4b4b4b` | `--color-charcoal-text` | Primary heading text and link text, providing a strong, dark anchor that is slightly less stark than pure black. |
| Muted Silver | `#afafaf` | `--color-muted-silver` | Observed in nav borderColor, button borderColor, nav color. Extracted usage does not support a distinct primary control color. |
| Outline Green | `#a5ed6e` | `--color-outline-green` | Outlined action borders and text, providing a distinct interactive style for secondary actions that align with the brand's green palette. |

## Tokens — Typography

### din-round — The primary typeface for body text, links, buttons, and general UI elements. Its rounded yet clear forms contribute to the friendly and approachable brand personality. Utilized across a wide range of weights and sizes to ensure versatility from captions to subheadings. · `--font-din-round`
- **Substitute:** system-ui
- **Weights:** 500, 700
- **Sizes:** 13px, 14px, 15px, 17px, 19px, 32px
- **Line height:** 1.15, 1.18, 1.20, 1.21, 1.23, 1.33, 1.40, 1.41, 1.47
- **Letter spacing:** 0.053em
- **Role:** The primary typeface for body text, links, buttons, and general UI elements. Its rounded yet clear forms contribute to the friendly and approachable brand personality. Utilized across a wide range of weights and sizes to ensure versatility from captions to subheadings.

### feather — Used exclusively for large display headings, this typeface brings a bold, impactful presence. Its distinct character provides a strong visual anchor for key messages on the page. · `--font-feather`
- **Substitute:** serif
- **Weights:** 700
- **Sizes:** 48px, 64px
- **Line height:** 1.20
- **Letter spacing:** -0.020em
- **Role:** Used exclusively for large display headings, this typeface brings a bold, impactful presence. Its distinct character provides a strong visual anchor for key messages on the page.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.47 | 0.053px | `--text-caption` |
| body | 15px | 1.4 | 0.053px | `--text-body` |
| heading-sm | 19px | 1.21 | 0.053px | `--text-heading-sm` |
| heading | 32px | 1.33 | 0.053px | `--text-heading` |
| display | 48px | 1.2 | -0.02px | `--text-display` |
| display-lg | 64px | 1.2 | -0.02px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
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
| links | 12px |
| buttons | 12px |

### Layout

- **Section gap:** 101px
- **Card padding:** 16px
- **Element gap:** 12px

## Components

### Primary Action Button (Filled)
**Role:** Main call to action

Filled button with `Duolingo Green` background (#58cc02). Text uses `Arctic White` (#ffffff) with `din-round` font, weight 700. `12px` border-radius. Padding of `16px` left/right.

### Secondary Action Button (Outlined)
**Role:** Secondary call to action, alternative options

Outlined button with `Outline Green` (#a5ed6e) border and text. Background is transparent. `din-round` font, weight 700. `12px` border-radius. Padding of `16px` left/right.

### Ghost Button (Neutral)
**Role:** Tertiary action, navigation

Transparent background with text and border in `Action Blue` (#1cb0f6). `din-round` font, weight 500. `12px` border-radius. Padding of `16px` left/right.

### Muted Navigation Button
**Role:** Language switcher, secondary navigation

Transparent background with text and border in `Muted Silver` (#afafaf). `din-round` font, weight 500. No specific border radius.

### Primary Headline
**Role:** Page title, main section headings

Text in `Charcoal Text` (#4b4b4b) using `feather` font, weight 700, size 48px or 64px, with letter-spacing -0.020em. Line height 1.2.

### Accent Headline
**Role:** Highlighting key features or sections

Text in `Duolingo Green` (#58cc02) using `feather` font, weight 700, size 48px or 64px, with letter-spacing -0.020em. Line height 1.2.

### Body Text Standard
**Role:** Paragraphs, descriptive content

Text in `Shadowed Pine` (#3c3c3c) using `din-round` font, weight 500, size 14px or 15px, with letter-spacing 0.053em.

### Muted Body Text
**Role:** Secondary descriptions, fine print, meta information

Text in `Cloud Gray` (#777777) using `din-round` font, weight 500, size 13px or 14px, with letter-spacing 0.053em.

### Navigation Link
**Role:** Global navigation items

Text in `Cloud Gray` (#777777) using `din-round` font, weight 500. Minimal padding (e.g., `10px` around), transparent background.

### Status Indicator
**Role:** Small interactive or informational elements

Small elements often using `Duolingo Green` (#58cc02) for background or `Background Green Accent` (#d7ffb8) for borders, with `din-round` text. Features `12px` border-radius.

## Do's and Don'ts

### Do
- Use `Duolingo Green` (#58cc02) for primary interactive elements and key accents to maintain brand recognition.
- Apply `12px` border-radius to all buttons and prominent interactive links for a consistent friendly aesthetic.
- Employ `feather` font with weight 700 and letter-spacing -0.020em for all display-level headings to ensure visual impact.
- Use `Arctic White` (#ffffff) as the primary page background color to allow vibrant brand elements to stand out.
- Ensure generous `elementGap` of `12px` and `sectionGap` of `101px` to create a comfortable, spacious layout.
- Use `outline Green` (#a5ed6e) for secondary actions that need to align with the brand's green while differentiating from the primary filled action.

### Don't
- Do not use `feather` font for body text or small UI elements; reserve it for large headings only.
- Avoid arbitrary color choices outside the defined palette, especially for interactive elements, to prevent dilution of brand identity.
- Do not use sharp corners on buttons or prominent interactive components; always apply a `12px` border-radius.
- Do not clutter sections; maintain the `12px` element gap and `101px` section gap for comfortable density.
- Avoid using `Action Blue` (#1cb0f6) as a filled button background; it is reserved for outlined buttons and links.
- Do not use `Muted Silver` (#afafaf) for main headings or primary calls to action; reserve it for subtle interactive elements.

## Imagery

The visual language is characterized by lively, whimsical 2D illustrations with distinct outlines and a vibrant color palette that closely mirrors the brand system's greens, blues, and other playful accents. These illustrations, featuring diverse characters and fantastical elements, are central to explaining concepts and adding a game-like atmosphere. They are typically contained within sections, sometimes overlapping text or elements, and serve mainly to add decorative atmosphere and explain content in a friendly, engaging way. Iconography is filled and colorful, matching the illustration style. The overall density is balanced, with illustrations occupying significant visual space alongside text blocks, creating a visually rich and engaging experience.

## Layout

The page model is primarily full-bleed with content often centered or arranged in logical two-column (text + image) or three-column card grids. The hero section usually features a prominent illustration alongside a large, centered headline and primary action buttons. Sections maintain a consistent vertical rhythm, often alternating between a main content block and smaller, supportive elements. Content is frequently presented with text on one side and an illustrative graphic on the other, creating a dynamic visual flow. The navigation is a sticky top bar, containing the brand logo and language switcher. The layout is spacious with ample clear space around sections and elements.

## Agent Prompt Guide

Quick Color Reference:
text: #4b4b4b
background: #ffffff
border: #3c3c3c
accent: #a5ed6e
primary action: #a5ed6e (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #a5ed6e border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Create a Secondary Outlined Button: transparent background, `Outline Green` border and text (#a5ed6e), `din-round` weight 700, 12px border-radius, 16px horizontal padding.
3. Create a Main Headline Section: `Arctic White` background. Headline in `Charcoal Text` (#4b4b4b) using `feather` font, weight 700, size 64px, letter-spacing -0.02em. Body text beneath in `Shadowed Pine` (#3c3c3c) using `din-round` font, weight 500, size 15px, letter-spacing 0.053em.
4. Create a Navigation Link: `Cloud Gray` text (#777777), `din-round` font, weight 500, 10px padding, no border or background.

## Similar Brands

- **Headspace** — Uses playful illustrations, rounded forms, and a dominant brand color to create a friendly, approachable user experience.
- **Babbel** — Language learning platform that also relies on clear, colorful UI with distinct brand accents to guide users.
- **Khan Academy** — Educational platform that balances clean UI with clear content hierarchy and a friendly tone, albeit with less overt playfulness.
- **Calm** — Similar approach to using a specific brand color (blue/purple) to evoke a particular mood and using soft shapes for usability.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-duolingo-green: #58cc02;
  --color-background-green-accent: #d7ffb8;
  --color-action-blue: #1cb0f6;
  --color-dark-heading-blue: #042c60;
  --color-deep-violet-accent: #000437;
  --color-shadowed-pine: #3c3c3c;
  --color-jet-black: #000000;
  --color-arctic-white: #ffffff;
  --color-cloud-gray: #777777;
  --color-charcoal-text: #4b4b4b;
  --color-muted-silver: #afafaf;
  --color-outline-green: #a5ed6e;

  /* Typography — Font Families */
  --font-din-round: 'din-round', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-feather: 'feather', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.47;
  --tracking-caption: 0.053px;
  --text-body: 15px;
  --leading-body: 1.4;
  --tracking-body: 0.053px;
  --text-heading-sm: 19px;
  --leading-heading-sm: 1.21;
  --tracking-heading-sm: 0.053px;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --tracking-heading: 0.053px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.2;
  --tracking-display-lg: -0.02px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 101px;
  --card-padding: 16px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-xl: 12px;

  /* Named Radii */
  --radius-links: 12px;
  --radius-buttons: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-duolingo-green: #58cc02;
  --color-background-green-accent: #d7ffb8;
  --color-action-blue: #1cb0f6;
  --color-dark-heading-blue: #042c60;
  --color-deep-violet-accent: #000437;
  --color-shadowed-pine: #3c3c3c;
  --color-jet-black: #000000;
  --color-arctic-white: #ffffff;
  --color-cloud-gray: #777777;
  --color-charcoal-text: #4b4b4b;
  --color-muted-silver: #afafaf;
  --color-outline-green: #a5ed6e;

  /* Typography */
  --font-din-round: 'din-round', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-feather: 'feather', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.47;
  --tracking-caption: 0.053px;
  --text-body: 15px;
  --leading-body: 1.4;
  --tracking-body: 0.053px;
  --text-heading-sm: 19px;
  --leading-heading-sm: 1.21;
  --tracking-heading-sm: 0.053px;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --tracking-heading: 0.053px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.2;
  --tracking-display-lg: -0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-xl: 12px;
}
```
