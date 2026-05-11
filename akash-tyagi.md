# Akash Tyagi — Style Reference
> Fuchsia glow within a midnight canvas.

**Theme:** dark

Akash Tyagi's portfolio design emphasizes a refined, almost austere dark mode aesthetic, brought to life with a single, highly saturated fuchsia accent. Typography is intentionally understated with generous letter spacing, creating a spacious and contemplative feel. Components are minimal, relying on subtle backgrounds and borders rather than heavy visual treatments, ensuring the focus remains on content over chrome. The overall impression is one of confident restraint, where visual hierarchy is established through precise typographic treatment and strategic splashes of color.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Eclipse | `#000000` | `--color-midnight-eclipse` | Page backgrounds, card surfaces, primary text for selected work titles for contrast |
| Silver Whisper | `#efe6d8` | `--color-silver-whisper` | Primary body text, secondary headings, ghost link text against dark backgrounds |
| Stormy Gray | `#aca69c` | `--color-stormy-gray` | Muted body text, subtle borders, inactive link text |
| Deep Iron | `#736e68` | `--color-deep-iron` | Less prominent body text, tertiary headings, subtle borders |
| Charcoal Haze | `#605c56` | `--color-charcoal-haze` | Fine print, less important descriptive text |
| Fuchsia Pulse | `#ffa1f7` | `--color-fuchsia-pulse` | Primary action backgrounds, decorative icon fills, active highlight text — a singular vibrant accent cutting through the dark tranquility |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Geist Pixel Triangle — Large headings and titles, creating a distinct visual break with its specific tracking. · `--font-geist-pixel-triangle`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 30px
- **Line height:** 1.33
- **Letter spacing:** -0.0330em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Large headings and titles, creating a distinct visual break with its specific tracking.

### Geist — Body copy, links, general headings with precise tracking for a refined feel. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 500, 600
- **Sizes:** 13px, 14px, 15px
- **Line height:** 1.14, 1.23, 1.33
- **Letter spacing:** -0.0310em, -0.0290em, -0.0130em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Body copy, links, general headings with precise tracking for a refined feel.

### Geist Mono — Monospaced text for specific utilitarian elements like timestamps, and button text. · `--font-geist-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400, 500
- **Sizes:** 13px
- **Line height:** 1.23, 1.54
- **Letter spacing:** -0.0310em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Monospaced text for specific utilitarian elements like timestamps, and button text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.23 | — | `--text-caption` |
| body-sm | 14px | 1.23 | — | `--text-body-sm` |
| body | 15px | 1.23 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 104 | 104px | `--spacing-104` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| forms | 1000px |
| buttons | 40px |

### Layout

- **Section gap:** 200px
- **Card padding:** 12px
- **Element gap:** 16px

## Components

### Primary Fuchsia Button
**Role:** Call-to-action button

Fuchsia Pulse background (#ffa1f7), Midnight Eclipse text (#000000, though data shows #0000ee due to browser default, this is overridden to match page dark theme), 40px border-radius, 4px vertical padding, 12px horizontal padding. Uses Geist Mono font, weight 400.

### Ghost Link Button
**Role:** Secondary action or subtle navigation

Transparent background, Silver Whisper text (#efe6d8), 0px border-radius, 4px vertical padding, 0px horizontal padding. Uses Geist font, weight 500.

### Primary Heading
**Role:** Main page titles and prominent section headers.

Geist Pixel Triangle, 30px, weight 400, Midnight Eclipse color (#000000) or Silver Whisper (#efe6d8) when on dark sections for readability, letter-spacing -0.0330em.

### Section Subtitle
**Role:** Descriptive text below headings or in sidebars.

Geist font, 15px, weight 500, Silver Whisper text (#efe6d8), letter-spacing -0.0130em.

### Body Paragraph
**Role:** Standard body text for longer content blocks.

Geist font, 14px, weight 500, Silver Whisper text (#efe6d8), letter-spacing -0.0290em.

### Detail Text
**Role:** Smaller, less prominent details like timestamps or context.

Geist Mono font, 13px, weight 400, Stormy Gray text (#aca69c), letter-spacing -0.0310em.

## Do's and Don'ts

### Do
- Use Midnight Eclipse (#000000) as the foundational background for all primary surfaces.
- Apply Fuchsia Pulse (#ffa1f7) exclusively for primary calls to action and critical accent elements to maintain its impact.
- Employ Geist Pixel Triangle at 30px with -0.0330em letter-spacing for all significant headings to establish authority.
- Maintain a comfortable vertical rhythm using `sectionGap` of 200px between major content blocks.
- Utilize rounded corners with a 40px radius for all interactive buttons to soften their appearance.
- Favor `elementGap` of 16px to separate most horizontal and vertical elements, offering breathing room.
- Use Silver Whisper (#efe6d8) for all primary text content to ensure high contrast against the dark background.

### Don't
- Avoid introducing additional saturated colors; the Fuchsia Pulse accent is deliberately singular.
- Do not use generic system fonts for text that should carry brand identity; stick to Geist, Geist Mono, or Geist Pixel Triangle.
- Do not vary border radii significantly; interactive elements use 40px, non-interactive forms use 1000px for pill shapes.
- Never overcrowd sections; rely on the generous `sectionGap` of 200px to provide visual separation and hierarchy.
- Do not use box shadows or other elevation effects; the design relies on flat planes and typographic hierarchy.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000000` | Dominant background for the entire application, providing a deep, immersive dark mode experience. |

## Elevation

The design system intentionally avoids the use of shadows or elevation. All UI elements exist on a flat plane, with depth and hierarchy created through careful use of typography, color contrast, and spacing. This contributes to the clean, uncluttered, and direct aesthetic of the interface.

## Imagery

The site uses product screenshots and contained visual elements rather than large atmospheric photos. Product visuals are presented as direct, uncropped displays within a contained space, often showing dark mode interfaces. There are no decorative illustrations. Icons, when present, appear to be minimal, outlined, or filled in a monochromatic style, acting as functional rather than ornamental graphics. Imagery serves purely explanatory or product showcase roles, ensuring a text-dominant, high-information density layout.

## Layout

The page adheres to a mostly full-bleed layout, particularly for the main content areas, with elements typically aligned to the left side or centrally within defined content zones. The hero section is dark with large, centered text. Content is primarily arranged in single or two-column sections, often with text on the left and a visual element (like a product screenshot) on the right, or stacked in centered blocks. Vertical rhythm is established through consistent, large `sectionGap` (200px). The navigation is minimal, typically a top-right email link or simple bottom-left social links against the dark canvas.

## Agent Prompt Guide

Quick Color Reference:
text: #efe6d8
background: #000000
border: #aca69c
accent: #ffa1f7
primary action: #ffa1f7 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: 'Book an intro call' text, Fuchsia Pulse background (#ffa1f7), Midnight Eclipse text (#000000), 40px radius, 4px 12px padding, Geist Mono 13px weight 400.
2. Create a section heading: 'SELECTED WORK' text, Geist Pixel Triangle 30px weight 400, Silver Whisper text (#efe6d8), letter-spacing -0.0330em.
3. Create a body paragraph: 'Digital product designer focused on building high-quality web and mobile experiences.' text, Geist 14px weight 500, Silver Whisper text (#efe6d8), letter-spacing -0.0290em.
4. Create a footer link: 'Linkedin' text, Geist 13px weight 500, Stormy Gray text (#aca69c), letter-spacing -0.0310em.

## Similar Brands

- **Dark Mode Portfolios** — Monochromatic dark interface with a single vibrant accent color for interaction.
- **Linear** — Understated typography with generous letter-spacing, focus on functionality over heavy decoration.
- **Figma** — Minimal UI elements, strong reliance on text semantics for hierarchy, and a very limited, deliberate color palette.
- **Stripe** — Crisp typography and clean layout, with subtle background elements and a focused use of color for key actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-eclipse: #000000;
  --color-silver-whisper: #efe6d8;
  --color-stormy-gray: #aca69c;
  --color-deep-iron: #736e68;
  --color-charcoal-haze: #605c56;
  --color-fuchsia-pulse: #ffa1f7;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-pixel-triangle: 'Geist Pixel Triangle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.23;
  --text-body-sm: 14px;
  --leading-body-sm: 1.23;
  --text-body: 15px;
  --leading-body: 1.23;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-104: 104px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 200px;
  --card-padding: 12px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-forms: 1000px;
  --radius-buttons: 40px;

  /* Surfaces */
  --surface-canvas: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-eclipse: #000000;
  --color-silver-whisper: #efe6d8;
  --color-stormy-gray: #aca69c;
  --color-deep-iron: #736e68;
  --color-charcoal-haze: #605c56;
  --color-fuchsia-pulse: #ffa1f7;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-pixel-triangle: 'Geist Pixel Triangle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.23;
  --text-body-sm: 14px;
  --leading-body-sm: 1.23;
  --text-body: 15px;
  --leading-body: 1.23;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-104: 104px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 1000px;
}
```
