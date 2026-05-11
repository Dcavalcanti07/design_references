# Patch — Style Reference
> Electric blueprint, high-fidelity lines

**Theme:** light

Patch uses a high-contrast, energetic visual system built on a primary electric blue and a bold orange accent, reminiscent of a digital blueprint come to life. Typography is heavy and expansive, using bold weights and generous letter-spacing to command attention. Layouts are distinctively structured with strong visual grids and borders, creating a technical yet dynamic feel. Functional elements often break from typical rounded aesthetics, embracing sharp corners and strong outlines.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Blueprint | `#1f00ff` | `--color-blueprint` | Primary brand color for large background areas, major headlines, and section accents. Also used for outlined action borders and subtle text highlights, creating a digital and tech-forward atmosphere |
| Blaze Orange | `#ff622b` | `--color-blaze-orange` | Accent color for primary calls to action, nav highlights, and interactive elements. Its high contrast with Blueprint creates urgency and visual pop |
| Canvas White | `#ffffff` | `--color-canvas-white` | Dominant background for most content sections, ensuring high readability for dark text. Also used for ghost button borders and some icon details |
| Ash Gray | `#ececec` | `--color-ash-gray` | Subtle background for UI elements, hover states, and slight textural variation from pure white |
| Faded Grid | `#d3d3d3` | `--color-faded-grid` | Muted text for inactive states and background grid lines, providing structure without distraction |
| Deep Graphite | `#212121` | `--color-deep-graphite` | Primary text color and background for elevated UI cards, offering strong contrast against light surfaces |
| Surface Light | `#f2f2f2` | `--color-surface-light` | Secondary background for cards, providing a slight elevation above Canvas White |
| Surface Lighter | `#f8f8f8` | `--color-surface-lighter` | Tertiary background for cards, another subtle step in surface hierarchy |

## Tokens — Typography

### Archivo — Used for body text, links, navigation items, and helper text. Its clean sans-serif form provides a neutral base for content, particularly at smaller sizes, occasionally using wider tracking for emphasis. · `--font-archivo`
- **Substitute:** Arial
- **Weights:** 300, 400, 600
- **Sizes:** 10px, 11px, 13px, 14px, 17px, 19px, 23px, 24px, 29px, 38px, 333px
- **Line height:** 1.00, 1.07, 1.11, 1.20, 1.22, 1.33, 1.40, 1.50, 1.58, 1.67, 2.00
- **Letter spacing:** 0.0100em to 0.1000em across sizes
- **Role:** Used for body text, links, navigation items, and helper text. Its clean sans-serif form provides a neutral base for content, particularly at smaller sizes, occasionally using wider tracking for emphasis.

### PP Right — The signature display font for headings, major calls to action, and any element requiring strong visual impact. Its ultra-condensed and heavy nature, combined with tight line heights and tracking, creates a sense of authority and urgency, often in all caps. · `--font-pp-right`
- **Substitute:** Impact
- **Weights:** 400, 800
- **Sizes:** 12px, 13px, 14px, 19px, 21px, 24px, 29px, 33px, 38px, 48px, 62px, 67px, 90px, 95px, 133px, 152px, 200px, 524px
- **Line height:** 0.79, 0.85, 0.86, 0.90, 0.94, 1.00, 1.10, 1.13, 1.20, 1.57, 1.85, 2.00, 2.32
- **Letter spacing:** 0.0200em to 0.0500em across sizes
- **Role:** The signature display font for headings, major calls to action, and any element requiring strong visual impact. Its ultra-condensed and heavy nature, combined with tight line heights and tracking, creates a sense of authority and urgency, often in all caps.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.01px | `--text-caption` |
| body-sm | 14px | 1.58 | 0.01px | `--text-body-sm` |
| body | 17px | 1.2 | 0.01px | `--text-body` |
| subheading | 24px | 1 | 0.02px | `--text-subheading` |
| heading | 48px | 0.86 | 0.029px | `--text-heading` |
| heading-lg | 95px | 0.85 | 0.03px | `--text-heading-lg` |
| display | 333px | 0.79 | 0.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 19 | 19px | `--spacing-19` |
| 21 | 21px | `--spacing-21` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 33 | 33px | `--spacing-33` |
| 35 | 35px | `--spacing-35` |
| 38 | 38px | `--spacing-38` |
| 48 | 48px | `--spacing-48` |
| 90 | 90px | `--spacing-90` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4.7619px |
| buttons | 4.7619px |
| mediumCards | 9.52381px |

### Layout

- **Section gap:** 24px
- **Card padding:** 38px
- **Element gap:** 11px

## Components

### Primary Action Button
**Role:** Filled Call to Action

Blaze Orange (#ff622b) background with Blueprint (#1f00ff) text, 4.7619px border radius, with 0px vertical and 33.3333px horizontal padding. This button stands out with its vivid color combination.

### Inverse Primary Action Button
**Role:** Filled Call to Action for Blueprint backgrounds

Blaze Orange (#ff622b) background with Canvas White (#ffffff) text, 4.7619px border radius, 0px vertical and 33.3333px horizontal padding. Used against the Blueprint background for maximal contrast.

### Ghost Outline Button
**Role:** Secondary action or subtle interaction

Transparent background with Deep Graphite (#212121) text and 1px Deep Graphite border. 0px border radius, 1px vertical and 6px horizontal padding. Offers a minimal, yet clearly interactive presence.

### Standard Card
**Role:** Content container

Canvas White (#ffffff) background with 4.7619px border radius, no box shadow, 0px internal padding. Used for general content grouping, often within a grid layout.

### Blueprint Card
**Role:** Highlight or featured content card

Blueprint (#1f00ff) background with 4.7619px border radius, no box shadow, 0px internal padding. Draws strong attention to specific content in a high-contrast manner.

### Ash Card
**Role:** Subtle feature or informational card

Ash Gray (#ececec) background with 9.52381px border radius, no box shadow, 0px internal padding. Provides a slightly softer visual boundary than the standard card.

### Graphite Card
**Role:** Inverse or brand-dark content card

Deep Graphite (#212121) background with 4.7619px border radius, no box shadow, with 38.0952px internal padding on all sides. Used for important sections that require a darker backdrop.

### Text Input
**Role:** Form entry field

Transparent background with Canvas White (#ffffff) text and 1px Canvas White border. 0px border radius, 1px vertical and 2px horizontal padding. Designed for fields on dark backgrounds, maintaining the outlined aesthetic.

## Do's and Don'ts

### Do
- Use Blueprint (#1f00ff) as the dominant background or headline color for energetic, high-impact sections.
- Apply Blaze Orange (#ff622b) exclusively for primary action buttons and crucial navigation accents to ensure high conversion visibility.
- Employ PP Right weight 800 for all major headlines with tight line-heights (0.85-0.9) and generous letter-spacing (0.029em-0.05em) for maximum impact.
- Utilize Canvas White (#ffffff) as the default page background and for ghost button borders, providing clean canvases for content.
- Ensure all card elements maintain a 4.7619px border radius, except for specific instances like Ash Cards which use 9.52381px.
- Maintain a clear visual hierarchy by using the Faded Grid (#d3d3d3) color for background grids and secondary information.
- Prioritize Archivo for smaller text sizes (10-19px) and all body content to ensure readability despite the dominant bold display font.

### Don't
- Do not use Blaze Orange (#ff622b) for decorative elements or non-actionable text; reserve it strictly for calls to action.
- Avoid using Archivo for headlines or large display text where PP Right's impactful quality is essential.
- Do not introduce additional bold accent colors; the system relies heavily on the Blueprint and Blaze Orange contrast.
- Do not use box shadows for elevation; rely on solid background color changes for surface differentiation.
- Avoid standard rounded buttons; maintain the defined 4.7619px or 0px radii for a distinct, angular feel.
- Do not vary letter-spacing for PP Right headlines outside the specified range of 0.029em-0.05em to preserve its signature expansive look.
- Do not add gradients; the design relies on solid, flat color blocks and sharp contrasts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and default card surface. |
| 1 | Surface Lighter | `#f8f8f8` | Slightly elevated card background. |
| 2 | Surface Light | `#f2f2f2` | Secondary elevated card background, notably used for cards with 9.52381px radius. |
| 3 | Ash Gray | `#ececec` | Background for subtle UI elements and interactive states, slightly darker than other surface neutrals. |
| 4 | Deep Graphite | `#212121` | Highest contrast card background, used for featured content blocks. |

## Imagery

The site uses monochromatic, line-art illustrations contained within white square cards, often with Blueprint borders. These visuals function as explanatory content and abstract metaphors rather than product showcases. Iconography is minimalist, outlined, and shares the same stroke weight aesthetic as the illustrations. Imagery is relatively sparse, with UI and typography dominating the visual space.

## Layout

The page primarily uses a full-bleed layout, particularly for the hero section which spans the entire viewport width with a Deep Graphite background if it was defined, or the Blueprint background with high-contrast type. Content sections often feature implicit grid structures and strong outlines, like the Faded Grid lines. Vertical rhythm is maintained by distinct, spacious section gaps. The navigation is a top bar, with elements breaking out at the edges (like the 'Book a Call' button). Features are often arranged in alternating text/visual blocks or multi-column card grids.

## Agent Prompt Guide

Quick Color Reference:
text: #212121
background: #ffffff
border: #d3d3d3
accent: #1f00ff
primary action: #ff622b (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff622b background, #212121 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Canvas White (#ffffff) background, 4.7619px radius, 0px padding. Inside, use Archivo weight 400 at 14px, Deep Graphite (#212121) text. Include a Ghost Outline Button with Deep Graphite (#212121) text and border, 0px radius, 1px vertical and 6px horizontal padding.
4. Construct a content block: Canvas White (#ffffff) background. Subheading 'BUILD YOUR MARKETING MACHINE' using PP Right weight 800, 62px size, 0.86 lineHeight, 0.029em letterSpacing, Deep Graphite (#212121) text. Followed by body text using Archivo weight 400 at 17px, Deep Graphite (#212121) text, and 0.0100em letterSpacing.

## Similar Brands

- **Superhuman** — High-contrast dark mode with single vibrant accent color and strong typographic hierarchy.
- **Linear** — Strict grid-based layout, preference for outlines and high-contrast elements, minimal decorative imagery emphasis.
- **Tailwind UI** — Emphasis on structured, component-driven design with distinct background layers and sharp radii for some elements.
- **Figma** — Prominent use of a single brand color for accents and interactive states, with a focus on UI clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-blueprint: #1f00ff;
  --color-blaze-orange: #ff622b;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ececec;
  --color-faded-grid: #d3d3d3;
  --color-deep-graphite: #212121;
  --color-surface-light: #f2f2f2;
  --color-surface-lighter: #f8f8f8;

  /* Typography — Font Families */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-right: 'PP Right', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.58;
  --tracking-body-sm: 0.01px;
  --text-body: 17px;
  --leading-body: 1.2;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: 0.02px;
  --text-heading: 48px;
  --leading-heading: 0.86;
  --tracking-heading: 0.029px;
  --text-heading-lg: 95px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: 0.03px;
  --text-display: 333px;
  --leading-display: 0.79;
  --tracking-display: 0.05px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-19: 19px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-33: 33px;
  --spacing-35: 35px;
  --spacing-38: 38px;
  --spacing-48: 48px;
  --spacing-90: 90px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 38px;
  --element-gap: 11px;

  /* Border Radius */
  --radius-md: 4.7619px;
  --radius-lg: 9.52381px;

  /* Named Radii */
  --radius-cards: 4.7619px;
  --radius-buttons: 4.7619px;
  --radius-mediumcards: 9.52381px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-surface-lighter: #f8f8f8;
  --surface-surface-light: #f2f2f2;
  --surface-ash-gray: #ececec;
  --surface-deep-graphite: #212121;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-blueprint: #1f00ff;
  --color-blaze-orange: #ff622b;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ececec;
  --color-faded-grid: #d3d3d3;
  --color-deep-graphite: #212121;
  --color-surface-light: #f2f2f2;
  --color-surface-lighter: #f8f8f8;

  /* Typography */
  --font-archivo: 'Archivo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-right: 'PP Right', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.58;
  --tracking-body-sm: 0.01px;
  --text-body: 17px;
  --leading-body: 1.2;
  --tracking-body: 0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: 0.02px;
  --text-heading: 48px;
  --leading-heading: 0.86;
  --tracking-heading: 0.029px;
  --text-heading-lg: 95px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: 0.03px;
  --text-display: 333px;
  --leading-display: 0.79;
  --tracking-display: 0.05px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-19: 19px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-33: 33px;
  --spacing-35: 35px;
  --spacing-38: 38px;
  --spacing-48: 48px;
  --spacing-90: 90px;

  /* Border Radius */
  --radius-md: 4.7619px;
  --radius-lg: 9.52381px;
}
```
