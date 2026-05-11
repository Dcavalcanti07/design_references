# Spotify — Style Reference
> Ebony Canvas, Spotlight Content

**Theme:** dark

This design system conjures a dark, immersive command center for digital media consumption. A deep ebony canvas creates a sense of gravitas, while subtle tonal variations in surfaces define hierarchical layers without relying on heavy shadows. Carefully chosen muted and vivid chromatic accents punctuate content, drawing attention to media rather than interface chrome. Rounded corners for interactive elements provide a soft contrast to the otherwise sharp, precise lines of the content blocks. Typography prioritizing readability and clear information hierarchy completes a focused and understated aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ebony Canvas | `#000000` | `--color-ebony-canvas` | Page background, primary canvas, base level surface. |
| Iron Accent | `#121212` | `--color-iron-accent` | Secondary surface background, card backgrounds, sidebar background — slightly elevated from the canvas. |
| Charcoal Surface | `#1f1f1f` | `--color-charcoal-surface` | Content container backgrounds, active navigation indicators. This is the primary filled button background. |
| Graphite Text | `#b3b3b3` | `--color-graphite-text` | Primary body text, neutral icons, subtly present borders. |
| Pure White Text | `#ffffff` | `--color-pure-white-text` | High-contrast text, prominent headers, interactive element text, button text, and main section titles to ensure legibility against dark backgrounds. Also used for borders on ghost buttons and input fields. |
| Muted Grey | `#767676` | `--color-muted-grey` | Placeholder text in search inputs, secondary descriptive text, subtle borders. |
| Spotify Green | `#1ed760` | `--color-spotify-green` | Observed in body backgroundColor. |
| Signal Purple | `linear-gradient(90deg, rgba(175, 40, 150), rgba(80, 155, 245))` | `--color-signal-purple` | Background for promotional banners, drawing attention with moderate saturation. |
| Deep Space Blue | `#1078a8` | `--color-deep-space-blue` | Diverse album/artist card backgrounds, providing subtle thematic variation. |
| Sunset Red | `#dc392b` | `--color-sunset-red` | Diverse album/artist card backgrounds, providing subtle thematic variation. |

## Tokens — Typography

### SpotifyMixUI — Primary text font for body content, labels, captions, and interactive elements. Its multiple weights support hierarchical distinctions without changing typefaces. · `--font-spotifymixui`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 11px, 12px, 13px, 14px, 16px
- **Line height:** 1.20, 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Primary text font for body content, labels, captions, and interactive elements. Its multiple weights support hierarchical distinctions without changing typefaces.

### SpotifyMixUITitle — Dedicated font for prominent headings, ensuring clear hierarchy and brand distinction at larger sizes. Its single bold weight delivers impact. · `--font-spotifymixuititle`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 24px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Dedicated font for prominent headings, ensuring clear hierarchy and brand distinction at larger sizes. Its single bold weight delivers impact.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.33 | — | `--text-caption` |
| body-sm | 12px | 1.33 | — | `--text-body-sm` |
| body | 13px | 1.33 | — | `--text-body` |
| body-lg | 14px | 1.33 | — | `--text-body-lg` |
| heading-sm | 16px | 1.33 | — | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 48 | 48px | `--spacing-48` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| input | 500px |
| buttons | 9999px |
| default | 6px |
| circular | 50% |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.5) 0px 8px 24px 0px` | `--shadow-lg` |
| subtle | `rgb(18, 18, 18) 0px 1px 0px 0px, rgb(124, 124, 124) 0px 0...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1085px
- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Filled Button
**Role:** Primary action

Background: Charcoal Surface (#1f1f1f), Text: Pure White Text (#ffffff), Padding: 12px vertical, 12px horizontal. Border radius: 9999px. Used for main calls to action.

### Ghost Button
**Role:** Secondary action

Background: transparent (rgba(0,0,0,0)), Text: Graphite Text (#b3b3b3), Border: 1px solid Graphite Text (#b3b3b3), Padding: 12px all around. Border radius: 9999px.

### High-Visibility Ghost Button
**Role:** Prominent secondary action

Background: transparent (rgba(0,0,0,0)), Text: Pure White Text (#ffffff), Border: 1px solid Pure White Text (#ffffff), Padding: 0px. Used for emphasized secondary actions like 'Install App'.

### Media Content Card
**Role:** Content display

Background: transparent (rgba(0,0,0,0)), Border radius: 6px, Padding: 12px all around. Used for individual album covers, playlists, or artist profiles.

### Container Card
**Role:** Grouped content

Background: Iron Accent (#121212), Border radius: 6px, Padding: 0px (internal elements manage their own spacing). Used to group related content, like playlist creation prompts.

### Search Input (Header)
**Role:** Global input field

Background: Charcoal Surface (#1f1f1f), Text: Pure White Text (#ffffff), Placeholder text: Muted Grey (#767676), Padding: 12px vertical, 48px left, 96px right. Border radius: 500px.

### Promotional Banner
**Role:** System message banner

Background: linear-gradient(90deg, rgb(175, 40, 150), rgb(80, 155, 245)), Text: Pure White Text (#ffffff), Padding: 12px vertical, 24px horizontal. Border radius: 0px.

### Side Navigation Container
**Role:** Persistent navigation

Background: Ebony Canvas (#000000), internal elements often use Iron Accent (#121212) as background, with no overall container padding.

## Do's and Don'ts

### Do
- Prioritize Ebony Canvas (#000000) for large background areas and Iron Accent (#121212) for content surfaces to establish depth.
- Use Pure White Text (#ffffff) for all main headings and prominent interactive text to ensure optimal contrast.
- Apply Iron Accent (#121212) for elevated card backgrounds and Charcoal Surface (#1f1f1f) for interactive fills like button backgrounds or active states.
- Accurately use Spotify Green (#1ed760) only for active indicators and brand highlights, like the Spotify logo or play controls.
- Employ 9999px radius for all interactive buttons and pill-shaped elements to maintain a consistent interactive affordance.
- Adhere to the 6px border radius for content cards and containers to create a soft, contained visual.
- Apply 12px vertical and horizontal padding consistently to interactive buttons and card content areas.

### Don't
- Do not use saturated colors from media content cards (e.g., #c80808, #508162) for UI elements; they are reserved for mood setting within content.
- Avoid using excessive box-shadows; rely on surface color changes from Ebony Canvas to Iron Accent to Charcoal Surface for visual hierarchy.
- Do not break the 9999px radius for buttons, as it is a core identifier of interactive elements.
- Restrict Pure White Text (#ffffff) usage to prominent text where high contrast is essential, otherwise use Graphite Text (#b3b3b3) for secondary content.
- Do not introduce new color gradients; adhere only to the Signal Purple gradient for specific promotional banners.
- Avoid using a page-level padding; content should align to the defined max-width of 1085px centrally.
- Do not introduce custom font styles or weights outside of SpotifyMixUI and SpotifyMixUITitle. Maintain 'normal' letter spacing for all text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Ebony Canvas | `#000000` | Base page background, deepest layer. |
| 1 | Iron Accent | `#121212` | Secondary background layer, cards, sidebar. |
| 2 | Charcoal Surface | `#1f1f1f` | Interactive elements, input fields, and active states. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.5) 0px 8px 24px 0px`
- **Header/Sidebar Overlay:** `rgb(18, 18, 18) 0px 1px 0px 0px, rgb(124, 124, 124) 0px 0px 0px 1px inset`

## Imagery

This design primarily uses media album art and artist photography as its visual content. Album covers are presented within contained, square cards with a 6px border-radius, while artist portraits are typically circular. Both styles are rendered as content, not integrated into the UI. Photography of artists tends to be product-focused, showcasing the artist directly. Icons are minimal, monochromatic, and outlined, primarily serving functional navigation and interaction. The system is text-dominant, with imagery acting as visual anchors and content preview rather than decorative elements, creating a focused, content-first experience.

## Layout

The page structure is largely contained within a max-width of 1085px, featuring a persistent left sidebar navigation and a sticky top header. The main content area uses a flexible grid system, alternating between single-column stacks for 'Your Library' prompts and multi-column grids for content like 'Trending songs' and 'Popular artists'. Sections have consistent vertical spacing. The overall density is compact, maximizing content visibility without feeling cramped. The hero section is integrated within the main content area, not a distinct full-bleed element, with primary content appearing immediately within the defined max-width block.

## Agent Prompt Guide

Quick Color Reference:
text: #b3b3b3
background: #000000
border: #b3b3b3
accent: #1ed760
primary action: #1f1f1f (filled action)

Example Component Prompts:
Create a primary action button: Background Charcoal Surface (#1f1f1f), text Pure White Text (#ffffff), 9999px radius, 12px vertical and horizontal padding.
Create a content card a la 'Trending Songs': Background transparent, 6px radius. Text Pure White Text (#ffffff) for titles, Graphite Text (#b3b3b3) for subtitles. Image is full-bleed within the card's 6px radius.
Generate a header search input: Background Charcoal Surface (#1f1f1f), placeholder text Muted Grey (#767676), Pure White Text (#ffffff) for input, 500px radius, 12px vertical, 48px left, 96px right padding.
Create a ghost button for secondary actions: Background transparent, text Graphite Text (#b3b3b3), 1px solid Graphite Text (#b3b3b3) border, 9999px radius, 12px all around padding.
Develop a promotional banner at the bottom of the page: Background Signal Purple gradient, text Pure White Text (#ffffff), 12px vertical, 24px horizontal padding, 0px radius.

## Similar Brands

- **Netflix** — Dark UI with vibrant media thumbnails and prominent white text for titles, creating a content-forward experience.
- **Apple Music** — Focus on content cards, subtle dark backgrounds, and white typography for clarity, often using gradients within album art.
- **Tidal** — Heavy reliance on dark backgrounds with high-contrast text and interactive elements, prioritizing media visuals.
- **Twitch** — Dark interface, clear content blocks, and limited brand accent colors (purple for Twitch), ensuring content is the focal point.
- **YouTube (Dark Mode)** — Deep gray backgrounds, white text for readability, and clear delineation of video content blocks.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ebony-canvas: #000000;
  --color-iron-accent: #121212;
  --color-charcoal-surface: #1f1f1f;
  --color-graphite-text: #b3b3b3;
  --color-pure-white-text: #ffffff;
  --color-muted-grey: #767676;
  --color-spotify-green: #1ed760;
  --color-signal-purple: #6f74a4;
  --gradient-signal-purple: linear-gradient(90deg, rgba(175, 40, 150), rgba(80, 155, 245));
  --color-deep-space-blue: #1078a8;
  --color-sunset-red: #dc392b;

  /* Typography — Font Families */
  --font-spotifymixui: 'SpotifyMixUI', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-spotifymixuititle: 'SpotifyMixUITitle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.33;
  --text-body-sm: 12px;
  --leading-body-sm: 1.33;
  --text-body: 13px;
  --leading-body: 1.33;
  --text-body-lg: 14px;
  --leading-body-lg: 1.33;
  --text-heading-sm: 16px;
  --leading-heading-sm: 1.33;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
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
  --spacing-48: 48px;
  --spacing-172: 172px;

  /* Layout */
  --page-max-width: 1085px;
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-full: 500px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-input: 500px;
  --radius-buttons: 9999px;
  --radius-default: 6px;
  --radius-circular: 50%;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.5) 0px 8px 24px 0px;
  --shadow-subtle: rgb(18, 18, 18) 0px 1px 0px 0px, rgb(124, 124, 124) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-ebony-canvas: #000000;
  --surface-iron-accent: #121212;
  --surface-charcoal-surface: #1f1f1f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ebony-canvas: #000000;
  --color-iron-accent: #121212;
  --color-charcoal-surface: #1f1f1f;
  --color-graphite-text: #b3b3b3;
  --color-pure-white-text: #ffffff;
  --color-muted-grey: #767676;
  --color-spotify-green: #1ed760;
  --color-signal-purple: #6f74a4;
  --color-deep-space-blue: #1078a8;
  --color-sunset-red: #dc392b;

  /* Typography */
  --font-spotifymixui: 'SpotifyMixUI', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-spotifymixuititle: 'SpotifyMixUITitle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.33;
  --text-body-sm: 12px;
  --leading-body-sm: 1.33;
  --text-body: 13px;
  --leading-body: 1.33;
  --text-body-lg: 14px;
  --leading-body-lg: 1.33;
  --text-heading-sm: 16px;
  --leading-heading-sm: 1.33;

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
  --spacing-48: 48px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-full: 500px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.5) 0px 8px 24px 0px;
  --shadow-subtle: rgb(18, 18, 18) 0px 1px 0px 0px, rgb(124, 124, 124) 0px 0px 0px 1px inset;
}
```
