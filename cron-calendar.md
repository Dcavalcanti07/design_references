# Cron Calendar — Style Reference
> Minimal dark cockpit. Clean contrast of white text on deep gray surfaces, punctuated by a vivid orange accent.

**Theme:** dark

This design system evokes a refined, understated dark mode, like a well-crafted instrument panel in a high-end vehicle. Its strength lies in a stark contrast between near-black surfaces and bright white typography, creating immediate clarity. A single, vibrant orange serves as the primary accent, drawing attention only to key interactive elements. The system feels direct and functional, prioritizing information hierarchy and calls to action over decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cron Black | `#0f0d0a` | `--color-cron-black` | Primary page background, footer background. |
| Deep Graphite | `#161412` | `--color-deep-graphite` | Button backgrounds for secondary actions. |
| Bright White | `#ffffff` | `--color-bright-white` | Primary text color for headlines, body, navigation items, and button text, ensuring high contrast against dark backgrounds. |
| Subtle Gray | `#cccccc` | `--color-subtle-gray` | Secondary text, link underlines, subtle borders and outlines. Provides a softer visual hierarchy than pure white. |
| Action Orange | `#ff4700` | `--color-action-orange` | Primary call-to-action buttons, prominent interactive elements requiring immediate attention. This is the sole vivid chromatic color used. |
| Soft Ember | `#451e0` | `--color-soft-ember` | Shadow tint for action-oriented elements, contributing to a subtle glow rather than a harsh distinction. |
| Deep Ember | `#8b2e09` | `--color-deep-ember` | More saturated shadow tint for action-oriented elements, creating depth. |

## Tokens — Typography

### Helvetica Neue — Used universally across all text elements: headlines, body copy, navigation, buttons, and footer links. The wide range of weights and sizes allows for distinct hierarchy within a single, consistent typeface, particularly the oversized weight 700 for display headings. · `--font-helvetica-neue`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 13px, 15px, 22px, 140px
- **Line height:** 0.90, 1.00, 1.50, 1.70, 2.88
- **Letter spacing:** -0.0210em, 0.0100em
- **Role:** Used universally across all text elements: headlines, body copy, navigation, buttons, and footer links. The wide range of weights and sizes allows for distinct hierarchy within a single, consistent typeface, particularly the oversized weight 700 for display headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.7 | — | `--text-caption` |
| body-sm | 15px | 1.7 | 0.15px | `--text-body-sm` |
| body | 22px | 1.5 | — | `--text-body` |
| display | 140px | 0.9 | -2.94px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 4px |
| navigationPills | 9999px |

### Layout

- **Section gap:** 80px
- **Element gap:** 16px

## Components

### Primary Call-to-Action Button
**Role:** Interactive element

Background: Action Orange (#ff4700). Text: Bright White (#ffffff), Helvetica Neue weight 700. Padding: 0px top, 24px right, 1px bottom, 24px left. Border radius: 4px. No border.

### Secondary Button
**Role:** Interactive element

Background: Deep Graphite (#161412). Text: Bright White (#ffffff), Helvetica Neue weight 400. Padding: 0px top, 24px right, 1px bottom, 24px left. Border radius: 4px. Subtle Gray (#cccccc) top border. This button is used for secondary actions or contextual information.

### Header Navigation Link
**Role:** Navigation

Text: Bright White (#ffffff), Helvetica Neue weight 400, size 15px, line height 1.7. Appears as inline text, not buttonized except for 'Sign up'.

### Footer Link
**Role:** Navigation

Text: Bright White (#ffffff), Helvetica Neue weight 400, size 13px, line height 1.7. Used for legal and informational links.

## Do's and Don'ts

### Do
- Maintain a clear visual hierarchy by limiting prominent chromatic colors to the Action Orange (#ff4700) for primary CTAs.
- Utilize Bright White (#ffffff) text for primary content and Subtle Gray (#cccccc) for secondary, ensuring high readability on dark backgrounds.
- Apply Helvetica Neue universally, leveraging its differing weights (e.g., 700 for display, 400 for body) to establish content importance.
- Employ `sectionGap` of 80px between main content blocks to maintain a spacious, uncluttered flow.
- Use 4px border radius for all actionable buttons to provide subtle rounding without compromising precision.
- Apply `padding` of 0px top, 24px right, 1px bottom, 24px left for all buttons, maintaining a consistent minimalist vertical spacing.
- Use a 9999px border radius for tags and prominent notifications like 'Cron is now Notion Calendar' to create distinct pill shapes.

### Don't
- Do not introduce additional vivid chromatic colors beyond the established Action Orange (#ff4700) to maintain focus.
- Avoid using box shadows that introduce strong light colors or blur, as the system relies on flat, high-contrast surfaces augmented by subtle amber tints.
- Do not create extensive text blocks using Helvetica Neue at sizes larger than 22px; large text is reserved for display headlines.
- Avoid generic button styles; every button should either be Primary Call-to-Action (Action Orange) or Secondary (Deep Graphite).
- Do not vary `elementGap` from 16px unless explicitly for full-bleed section alignment or dense content blocks.
- Do not use overly complex or illustrative imagery; prefer UI screenshots or abstract graphics to align with the functional aesthetic.

## Elevation

The design strongly favors flat UI surfaces and high contrast over complex shadows. Where elevation is present (e.g., subtle button glows), it's achieved through a subdued, slightly chromatic tint in the `box-shadow` rather than distinct layers or heavy blurring, maintaining the system's clean, precise feel.

## Imagery

The visual language for imagery is predominantly product screenshots, showcasing the cron calendar interface in dark mode. These are presented without ornate treatments, simply as contained, rectangular displays of the application. The primary role of imagery is explanatory and product-showcasing, focusing on functional aspects of the UI rather than decorative or atmospheric elements. There's a notable absence of lifestyle photography or complex illustrations, reinforcing the tool's utilitarian and professional identity.

## Layout

The overarching layout is a max-width contained model, centered on the page, providing clear boundaries for content. The hero section is full-bleed dark with a strong centered headline and smaller subtext that guides the eye towards the central product showcase. Section rhythm is primarily established by consistent vertical spacing (80px `sectionGap`) rather than alternating background colors, although subtle variations in surface color (not evident in the main screenshot but common in dark themes) may exist. Content is generally arranged in a stacked, single-column fashion for primary messaging, potentially transitioning to multi-column grids for features or details. Navigation is a simple top bar with left-aligned branding and right-aligned links and a primary CTA button, sticky to the top of the viewport.

## Agent Prompt Guide

1. Quick Color Reference:
   - Text: #ffffff
   - Background: #0f0d0a
   - CTA: #ff4700
   - Secondary Text: #cccccc
   - Secondary Background: #161412

2. Example Component Prompts:
   - Create a hero section: 'Cron Black' background. Headline 'It's about time.' in 'Bright White', Helvetica Neue weight 700, size 140px, line height 0.9, letter spacing -2.94px. Subtext 'Cron is the next-generation calendar for professionals and teams.' in 'Bright White', Helvetica Neue weight 400, size 22px, line height 1.5. Center align all text. Ensure a top padding of 80px above the headline.
   - Generate a secondary button: 'Deep Graphite' background. Text 'Cron is now Notion Calendar →' in 'Bright White', Helvetica Neue weight 400, size 15px, letter spacing 0.15px. Padding 0px 24px 1px 24px. Border radius 4px. Top border 1px 'Subtle Gray'.
   - Design a primary navigation bar: 'Cron Black' background. Logo left-aligned. Right-aligned links 'Blog', 'Changelog', 'Docs', 'Login' in 'Bright White', Helvetica Neue weight 400, size 15px, line height 1.7. Followed by a 'Primary Call-to-Action Button' 'Sign up'.

## Similar Brands

- **Superhuman** — Shares a high-contrast dark theme, focus on a single accent color for interaction, and clean typographic emphasis.
- **Linear** — Features a similar dark UI, emphasis on crisp typography, and functional component design for a developer/professional audience.
- **Notion** — Adopts a very similar philosophy of minimalist design, strong typographic hierarchy, and a clear, uncluttered interface across its platform.
- **Figma (dark mode)** — Exhibits analogous dark-mode UI principles with stark white text on dark gray, minimal use of color, and a focus on clarity for tool-based interfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cron-black: #0f0d0a;
  --color-deep-graphite: #161412;
  --color-bright-white: #ffffff;
  --color-subtle-gray: #cccccc;
  --color-action-orange: #ff4700;
  --color-soft-ember: #451e0;
  --color-deep-ember: #8b2e09;

  /* Typography — Font Families */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.7;
  --text-body-sm: 15px;
  --leading-body-sm: 1.7;
  --tracking-body-sm: 0.15px;
  --text-body: 22px;
  --leading-body: 1.5;
  --text-display: 140px;
  --leading-display: 0.9;
  --tracking-display: -2.94px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 80px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-buttons: 4px;
  --radius-navigationpills: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cron-black: #0f0d0a;
  --color-deep-graphite: #161412;
  --color-bright-white: #ffffff;
  --color-subtle-gray: #cccccc;
  --color-action-orange: #ff4700;
  --color-soft-ember: #451e0;
  --color-deep-ember: #8b2e09;

  /* Typography */
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.7;
  --text-body-sm: 15px;
  --leading-body-sm: 1.7;
  --tracking-body-sm: 0.15px;
  --text-body: 22px;
  --leading-body: 1.5;
  --text-display: 140px;
  --leading-display: 0.9;
  --tracking-display: -2.94px;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;
}
```
