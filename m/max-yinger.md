# Max Yinger — Style Reference
> Terminal aesthetic, crafted in code.

**Theme:** dark

This design system evokes a sense of digital craftsmanship, like a custom-built terminal for a specialized task. The aesthetic leans into a high-contrast dark theme with stark white, monospace-inspired typography, creating an atmosphere of precision and focused utility. Punctuation marks and symbols are used as visual elements, giving the textual content a coded, programmatic feel. Slight rounding on interactive elements prevents harshness, while the overall minimal approach keeps the focus on core information and interactive 3D elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Basalt Black | `#12130f` | `--color-basalt-black` | Page background, component backgrounds, base for interactive elements. |
| Quartz White | `#e4dfda` | `--color-quartz-white` | Primary text color for headings, body text, and links; provides high contrast against the dark background. Also used for button borders. |
| Flint Gray | `#3c3c38` | `--color-flint-gray` | Subtle border color for interactive elements, creating a soft edge without drawing attention. |

## Tokens — Typography

### Inline VF — Display headings. Its compressed, blocky structure gives a distinct, almost pixel-art feel at large sizes, fitting the digital, coded aesthetic. · `--font-inline-vf`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 80px
- **Line height:** 0.80
- **Letter spacing:** normal
- **Role:** Display headings. Its compressed, blocky structure gives a distinct, almost pixel-art feel at large sizes, fitting the digital, coded aesthetic.

### Arbeit Contrast — Used for main content headings, lists, and prominent links. The contrast in its name suggests its impactful, yet readable nature in this system. The 80px size might be an alternate display heading. · `--font-arbeit-contrast`
- **Substitute:** Space Grotesk
- **Weights:** 400
- **Sizes:** 16px, 30px, 80px
- **Line height:** 1.13, 1.25
- **Letter spacing:** normal
- **Role:** Used for main content headings, lists, and prominent links. The contrast in its name suggests its impactful, yet readable nature in this system. The 80px size might be an alternate display heading.

### Arbeit Technik — Body text, smaller links, and button labels. Its monospace-like appearance aligns with the overall terminal style. · `--font-arbeit-technik`
- **Substitute:** JetBrains Mono
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.25
- **Letter spacing:** -0.0500em
- **Role:** Body text, smaller links, and button labels. Its monospace-like appearance aligns with the overall terminal style.

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 2px |
| buttons | 9999px |
| default | 6px |

### Layout

- **Section gap:** 64px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Pill Ghost Button
**Role:** Interactive elements, external links.

Buttons feature a `Basalt Black` background (rgba(18, 19, 15, 0.4)), `Quartz White` text (#e4dfda), and a subtle `Quartz White` border (rgba(228, 223, 218, 0.2)). Padding is 4px vertical, 12px horizontal, with a 9999px border-radius for a soft, pill-shaped appearance.

## Do's and Don'ts

### Do
- Prioritize `Quartz White` (#e4dfda) for all primary text content against `Basalt Black` (#12130f) backgrounds to maintain high contrast.
- Use `Inline VF` (or 'IBM Plex Mono') at 80px, weight 400, for primary display headings, without letter-spacing adjustments.
- Apply 9999px border-radius to all interactive buttons for a consistent pill shape.
- Utilize Arbeit Technik (or 'JetBrains Mono') for body text and labels, with a -0.05em letter-spacing at 12px.
- Maintain a compact spacing rhythm, using multiples of 4px for element gaps and button padding.
- When introducing subtle borders, use 1px `Flint Gray` (#3c3c38) for minimal visual separation.

### Don't
- Avoid using highly saturated colors; the system relies on achromatic tones and subtle accents.
- Do not deviate from the established font families; custom fonts 'Inline VF', 'Arbeit Contrast', and 'Arbeit Technik' are core to the brand identity.
- Do not use generic square corners for interactive elements; buttons require a 9999px radius.
- Do not introduce heavy box-shadows or complex elevation; the design's depth comes from content arrangement and subtle background changes.
- Do not vary line-height aggressively; stick to the specified 0.80 for display, 1.13-1.25 for headings/body.
- Do not add extra padding around sections beyond the 64px `sectionGap` unless for specific content needs, to preserve density.

## Imagery

The site uses stylized 3D rendered abstract blocks in a soft pink hue, which serve as decorative elements. These blocks are positioned interactively, suggesting a focus on real-time 3D and interaction. They are contained and isolated, not bleeding into the UI, acting as dynamic decorative accents rather than content-carrying visuals. The style is geometric and polished, with a soft, almost glassy texture, contrasting with the stark typography. Icons appear minimal if at all, limited to social media links which are purely text-based within pill buttons.

## Layout

The page is a full-bleed dark canvas with content largely left-aligned and centrally focused. There is no explicit max-width for the main content block, giving a spacious, open feel. The hero section prominently features a large, interactive 3D graphic. Text is structured in distinct blocks with generous vertical spacing (64px `sectionGap`). Social links are stacked vertically on the right, providing a clear access point. The layout gives ample breathing room, highlighting individual content elements rather than dense information.

## Agent Prompt Guide

Quick Color Reference:
- Text: #e4dfda
- Background: #12130f
- Button Background: rgba(18, 19, 15, 0.4)
- Button Border: rgba(228, 223, 218, 0.2)

Example Component Prompts:
- Create a page with a `Basalt Black` (#12130f) background. Add a headline: 'YINGER' using `Inline VF` at 80px, weight 400, `Quartz White` text (#e4dfda).
- Generate a 'Github' button: `Basalt Black` background at 40% opacity (rgba(18, 19, 15, 0.4)), `Quartz White` text (#e4dfda), border `Quartz White` at 20% opacity (rgba(228, 223, 218, 0.2)), 9999px border-radius, 4px vertical padding, 12px horizontal padding.
- Display a body text paragraph: 'UI Engineer who dips his toes in Realtime 3D' using `Arbeit Technik` at 12px, weight 400, `Quartz White` text (#e4dfda), letter-spacing -0.05em, line-height 1.25.
- Create a secondary heading 'Interaction' using `Arbeit Contrast` at 30px, weight 400, `Quartz White` text (#e4dfda), line-height 1.13 and no letter-spacing.

## Similar Brands

- **Vercel** — Dark-mode UI with a focus on code-like typography and minimalist presentation.
- **Linear** — High-contrast dark theme, heavy use of structured typography, and precise spacing for a technical user base.
- **Stripe (developer docs)** — Emphasis on sleek, functional design with monospace fonts and subtle interactive elements in a dark context.
- **Framer** — Modern, clean aesthetic with a focus on interactive elements and subtle 3D graphics in some contexts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-basalt-black: #12130f;
  --color-quartz-white: #e4dfda;
  --color-flint-gray: #3c3c38;

  /* Typography — Font Families */
  --font-inline-vf: 'Inline VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeit-contrast: 'Arbeit Contrast', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeit-technik: 'Arbeit Technik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.25;
  --text-base: 16px;
  --leading-base: 1.25;
  --text-3xl: 30px;
  --leading-3xl: 1.13;
  --text-5xl: 80px;
  --leading-5xl: 0.7;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-links: 2px;
  --radius-buttons: 9999px;
  --radius-default: 6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-basalt-black: #12130f;
  --color-quartz-white: #e4dfda;
  --color-flint-gray: #3c3c38;

  /* Typography */
  --font-inline-vf: 'Inline VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeit-contrast: 'Arbeit Contrast', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arbeit-technik: 'Arbeit Technik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.25;
  --text-base: 16px;
  --leading-base: 1.25;
  --text-3xl: 30px;
  --leading-3xl: 1.13;
  --text-5xl: 80px;
  --leading-5xl: 0.7;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-full: 9999px;
}
```
