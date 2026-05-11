# Stocketa — Style Reference
> Soft-edged transparency on cloud-white

**Theme:** light

Stocketa presents a focused financial interface with a light, almost ethereal feel. Its design language is dominated by soft, rounded forms and transparent components, creating a sense of lightness and openness. Color is used sparingly, primarily for functional accents and a subtle brand gradient, letting the content breathe. Typography is compact and precise, maintaining clarity within dense information displays, while nuanced shadows and inset effects give components a sophisticated, layered depth without heaviness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#e0dde2` | `--color-canvas` | Primary page background, provides a soft, warm-neutral base |
| Ash | `#f0f0f0` | `--color-ash` | Subtle background for UI elements, creates a slight separation from the canvas |
| Graphite | `#000000` | `--color-graphite` | Dominant text color for headings and body content, ensures high contrast on light backgrounds |
| Stone Gray | `#abbdcf` | `--color-stone-gray` | Decorative fills primarily for subtle background graphics and UI elements, contributes to the light, desaturated aesthetic |
| Slate | `#9aa1b2` | `--color-slate` | Muted border color, helper text, and secondary link states, offering softer visual weight than Graphite |
| Cloud Mist | `#a5afcb` | `--color-cloud-mist` | Light borders for subtle separation and decorative elements, harmonizes with the soft UI palette |
| Blue Violet | `#5b638c` | `--color-blue-violet` | Accent stroke for graphics and illustrations, hints at technical sophistication |
| Luminescent Violet | `#995bb9` | `--color-luminescent-violet` | Accent color for important headings, icons, and decorative fills — a primary brand splash |
| Midnight Indigo Outline | `#3a4766` | `--color-midnight-indigo-outline` | Border and text for ghost buttons and interactive elements, a deep, muted action color |
| Highlight Gradient | `linear-gradient(-333deg, rgb(96, 235, 140) -100%, rgb(235, 205, 96) -60%, rgb(235, 133, 96) -20%, rgb(159, 96, 235) 20%, rgb(96, 180, 235) 60%, rgb(96, 235, 110) 100%)` | `--color-highlight-gradient` | Vivid linear gradient used for dynamic background effects or highlighting specific content areas with vibrant color transitions |
| Faint Blue Overlay | `linear-gradient(0deg, rgba(132, 161, 208, 0.33), rgba(0, 0, 0, 0))` | `--color-faint-blue-overlay` | Subtle linear gradient used for soft overlays or to add depth to background elements, enhancing the light and airy feel |

## Tokens — Typography

### averta standard — Primary typeface for all elements, from headings to body text and buttons. It offers a compact, modern feel with precise letter-spacing, ensuring readability and a sleek aesthetic across all scales. The controlled letter-spacing on larger sizes gives headlines a confident, understated presence. · `--font-averta-standard`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700, 800
- **Sizes:** 14px, 15px, 16px, 17px, 19px, 27px, 28px, 50px, 53px, 62px, 98px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.25, 1.35, 1.40
- **Letter spacing:** -0.21, -0.23, -0.26, -0.28, -0.32, -0.44, -0.45, -0.8, -0.85, -1, -1.57
- **Role:** Primary typeface for all elements, from headings to body text and buttons. It offers a compact, modern feel with precise letter-spacing, ensuring readability and a sleek aesthetic across all scales. The controlled letter-spacing on larger sizes gives headlines a confident, understated presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | -0.21px | `--text-caption` |
| body | 16px | 1.4 | -0.26px | `--text-body` |
| subheading | 19px | 1.25 | -0.32px | `--text-subheading` |
| heading | 27px | 1.2 | -0.44px | `--text-heading` |
| heading-lg | 53px | 1.15 | -0.85px | `--text-heading-lg` |
| display | 98px | 1 | -1.57px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| cards | 18px |
| buttons | 100px |
| default | 22px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255...` | `--shadow-md` |

### Layout

- **Section gap:** 40px
- **Card padding:** 14px
- **Element gap:** 16px

## Components

### Ghost Action Button
**Role:** Secondary call to action or navigation link.

Text: Midnight Indigo Outline (#3a4766) on a transparent background, bordered with Midnight Indigo Outline (#3a4766), very rounded corners (100px radius). Padding: 13px vertical, 30px horizontal. Font: averta standard, weight 400.

### Soft Card
**Role:** Container for content, elevated slightly from the background.

Background: rgba(83, 116, 152, 0.07). Border Radius: 18px. Shadow: rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px. No internal padding.

### Feature List Item
**Role:** Padded container for individual features or information blocks.

Padded with 16px vertically. Icon in Luminescent Violet (#995bb9). Text in Graphite (#000000) for main points, Slate (#9aa1b2) for descriptions. Uses averta standard font.

### Content Card (No Shadow)
**Role:** Simple, flat content area on the page background.

Background: transparent. No border radius, no shadow. Padding varies by content, no intrinsic styling.

## Do's and Don'ts

### Do
- Use Canvas (#e0dde2) for primary backgrounds to maintain the light and airy theme.
- Apply a 100px border radius to all buttons and tags to create a consistent, soft, 'pill' shape.
- For primary headings, use Luminescent Violet (#995bb9) with averta standard weight 800 at appropriate scale sizes.
- Employ the Soft Card shadow (rgba(97, 110, 124, 0.114) 0px 4px 15px 0px with insets) for all elevated containers to achieve delicate depth.
- Ensure letter-spacing is applied precisely from the Typography tokens, especially for larger text, to maintain the sophisticated, compact feel (e.g., -1.57px at 98px).
- Separate sections with a `sectionGap` of 40px to provide comfortable visual breaks.

### Don't
- Avoid heavy drop shadows or opaque backgrounds that would counteract the light and transparent aesthetic.
- Do not use saturated colors for large UI areas; chromatic colors are reserved for accents and small functional elements.
- Do not deviate from the averta standard font family or its specified weights and letter-spacing for UI text.
- Avoid sharp corners; all UI components should feature rounded corners, preferably 18px or 22px defaults, or 100px for pill shapes.
- Do not introduce new border colors for interactive elements; use Midnight Indigo Outline (#3a4766) for ghost action borders.
- Do not overuse bold weights; reserve averta standard 800 primarily for main headings.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#e0dde2` | Primary background for the entire application, serving as the base layer. |
| 2 | Ash Surface | `#f0f0f0` | A slightly elevated background color for larger UI elements or sections, providing subtle differentiation. |
| 3 | Soft Card | `#537498` | Interactive cards or information panels that float above the base, distinguished by a subtle shadow and rounded corners. |

## Elevation

- **Soft Card:** `rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px`

## Imagery

The site uses a blend of abstract 3D elements and realistic product screenshots. Product screenshots are cleanly displayed within device frames, demonstrating functionality in a direct, uncluttered manner. Abstract 3D elements, characterized by soft, rounded, light gray forms, mimic organic shapes like pebbles or softly worn artifacts. These are used decoratively in the background, interacting with subtle light and shadow to create a sense of depth and modernity. Icons are outlined, featuring smooth, continuous strokes and are typically monochromatic or highlighted with Luminescent Violet. Visuals play a subtle, atmospheric role rather than a dominant, content-heavy one.

## Layout

The page primarily uses a max-width contained layout, centered on a light canvas. The hero section features a prominent, large headline in the Brand Gradient area, positioned centrally on the left, juxtaposed with a product showcase on the right. Subsequent sections follow a consistent vertical rhythm with minimal content density, using comfortable spacing. Content is largely presented as centered stacks of text with occasional feature lists, each item often accompanied by an icon. There's a subtle grid implied by the arrangement of features, but without hard lines. Navigation appears to be a minimal top bar, suggesting an application-focused approach.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #e0dde2
border: #9aa1b2
accent: #995bb9
primary action: #3a4766 (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #3a4766 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Create a content section with a Soft Card: Background is Canvas (#e0dde2). Inside the Soft Card, place a subheading (averta standard, 19px, weight 600, #000000, letter-spacing -0.32px) and a body element (averta standard, 16px, weight 400, #000000, letter-spacing -0.26px). The card's border radius is 18px and uses the Soft Card shadow.
3. Create a feature list: Use Canvas (#e0dde2) background. Each feature item should have an outlined icon in Luminescent Violet (#995bb9), followed by a body text description (averta standard, 16px, weight 400, #000000, letter-spacing -0.26px). Each item should have 16px vertical padding, with 16px `elementGap` between items.

## Similar Brands

- **Rize** — Shares a clean, light aesthetic with subtle shadows and rounded-corner cards, often using a single strong accent color.
- **Copilot Money** — Features a similar combination of app-like UI, soft gradients, and a preference for light backgrounds with strong typography.
- **Wealthfront** — Utilizes a balanced approach of strong, legible typography, soft UI elements, and a clean overall layout in a financial context.
- **Amie** — Exhibits a sunlit, productivity-workspace language with white canvas, flat product surfaces, and compact, confident typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #e0dde2;
  --color-ash: #f0f0f0;
  --color-graphite: #000000;
  --color-stone-gray: #abbdcf;
  --color-slate: #9aa1b2;
  --color-cloud-mist: #a5afcb;
  --color-blue-violet: #5b638c;
  --color-luminescent-violet: #995bb9;
  --color-midnight-indigo-outline: #3a4766;
  --color-highlight-gradient: #60eb8c;
  --gradient-highlight-gradient: linear-gradient(-333deg, rgb(96, 235, 140) -100%, rgb(235, 205, 96) -60%, rgb(235, 133, 96) -20%, rgb(159, 96, 235) 20%, rgb(96, 180, 235) 60%, rgb(96, 235, 110) 100%);
  --color-faint-blue-overlay: #84a1d0;
  --gradient-faint-blue-overlay: linear-gradient(0deg, rgba(132, 161, 208, 0.33), rgba(0, 0, 0, 0));

  /* Typography — Font Families */
  --font-averta-standard: 'averta standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.21px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.26px;
  --text-subheading: 19px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.32px;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --tracking-heading: -0.44px;
  --text-heading-lg: 53px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.85px;
  --text-display: 98px;
  --leading-display: 1;
  --tracking-display: -1.57px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-88: 88px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 14px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 34px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-cards: 18px;
  --radius-buttons: 100px;
  --radius-default: 22px;

  /* Shadows */
  --shadow-md: rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px;

  /* Surfaces */
  --surface-canvas: #e0dde2;
  --surface-ash-surface: #f0f0f0;
  --surface-soft-card: #537498;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #e0dde2;
  --color-ash: #f0f0f0;
  --color-graphite: #000000;
  --color-stone-gray: #abbdcf;
  --color-slate: #9aa1b2;
  --color-cloud-mist: #a5afcb;
  --color-blue-violet: #5b638c;
  --color-luminescent-violet: #995bb9;
  --color-midnight-indigo-outline: #3a4766;
  --color-highlight-gradient: #60eb8c;
  --color-faint-blue-overlay: #84a1d0;

  /* Typography */
  --font-averta-standard: 'averta standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: -0.21px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.26px;
  --text-subheading: 19px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.32px;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --tracking-heading: -0.44px;
  --text-heading-lg: 53px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.85px;
  --text-display: 98px;
  --leading-display: 1;
  --tracking-display: -1.57px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-88: 88px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 34px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-md: rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px;
}
```
