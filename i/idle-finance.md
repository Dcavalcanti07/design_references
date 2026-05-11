# Idle Finance — Style Reference
> Deep-space command center

**Theme:** dark

Idle Finance's aesthetic is a deep-space command center: rich dark blues and grays form primary surfaces, accented by a stark, luminous cyan that creates focus and interaction. Text is crisp and generally light on dark, promoting a sense of precision. Components are contained, often with rounded corners, and float within a spacious layout. Gradients suggest depth and advanced technology, reinforcing the high-tech, data-driven domain of crypto finance.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#17202e` | `--color-midnight-ink` | Primary surface for cards and elevated sections, providing a deep, contained background |
| Astral Gray | `#202a3e` | `--color-astral-gray` | Secondary surface for buttons and interactive elements, a slightly lighter dark gray to distinguish from primary surfaces |
| Star Dust | `#cdd0d6` | `--color-star-dust` | Muted secondary text and subtle boundary lines |
| Void Black | `#000000` | `--color-void-black` | Dominant text color on light backgrounds and borders for elements like data tables or lists. Also used for strokes |
| Polar White | `#ffffff` | `--color-polar-white` | Primary text color on dark backgrounds, active element backgrounds, and emphasized borders |
| Cyber Cyan | `#6ae4ff` | `--color-cyber-cyan` | Key accent color for interactive text, links, button text, and borders, providing a high-contrast, energetic visual highlight |
| Deep Ocean Gradient | `linear-gradient(90deg, rgb(45, 55, 72), rgb(74, 85, 104), rgb(113, 128, 150), rgb(74, 85, 104))` | `--color-deep-ocean-gradient` | Subtle background gradient creating depth and texture on dark surfaces |
| Nebula Core Gradient | `radial-gradient(circle, rgb(8, 33, 143) 40%, rgb(41, 138, 203) 100%)` | `--color-nebula-core-gradient` | Background visual element, suggesting dynamic energy and a central point of activity |
| Emerald Vapor Gradient | `linear-gradient(73.6deg, rgb(52, 237, 179) 2.11%, rgb(0, 209, 255))` | `--color-emerald-vapor-gradient` | Decorative gradient for product showcases or special highlight elements |

## Tokens — Typography

### Open Sans — Primary typeface for all major content: headings, body text, and UI elements. Its slightly condensed nature at larger sizes is distinctive, conveying precision and modernity, while maintaining clarity at small sizes. · `--font-open-sans`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 18px, 20px, 22px, 28px, 36px, 56px, 100px
- **Line height:** 1.00, 1.20, 1.33, 1.36, 1.43, 1.57, 1.60, 1.96, 2.14
- **Letter spacing:** -0.0360em
- **Role:** Primary typeface for all major content: headings, body text, and UI elements. Its slightly condensed nature at larger sizes is distinctive, conveying precision and modernity, while maintaining clarity at small sizes.

### Source Sans Pro — Secondary typeface predominantly used for smaller text elements like links, buttons, and detailed body text where a more conventional sans-serif is needed, offering balance to Open Sans. · `--font-source-sans-pro`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px
- **Line height:** 1.00, 1.17, 1.50, 1.71, 2.00, 2.13, 2.29, 2.33
- **Letter spacing:** normal
- **Role:** Secondary typeface predominantly used for smaller text elements like links, buttons, and detailed body text where a more conventional sans-serif is needed, offering balance to Open Sans.

### Arial — Fallback typeface for specific buttons and other general text where a highly accessible system font is preferred. · `--font-arial`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback typeface for specific buttons and other general text where a highly accessible system font is preferred.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.96 | -0.432px | `--text-caption` |
| body-sm | 14px | 1.6 | -0.504px | `--text-body-sm` |
| body | 18px | 1.57 | -0.648px | `--text-body` |
| subheading | 20px | 1.43 | -0.72px | `--text-subheading` |
| heading-sm | 22px | 1.36 | -0.792px | `--text-heading-sm` |
| heading | 28px | 1.33 | -1.008px | `--text-heading` |
| heading-lg | 36px | 1.2 | -1.296px | `--text-heading-lg` |
| display-sm | 56px | 1 | -2.016px | `--text-display-sm` |
| display | 100px | 1 | -3.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

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
| 40 | 40px | `--spacing-40` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 136 | 136px | `--spacing-136` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 24px |
| cards | 15px |
| links | 8px |
| buttons | 80px |
| smallButtons | 4px |

### Layout

- **Section gap:** 64px
- **Card padding:** 66px
- **Element gap:** 16px

## Components

### Filled Primary Button
**Role:** Primary call to action.

Background: Polar White #ffffff, Text: Void Black #000000, Border: Void Black #000000, Radius: 4px, Padding: 10px vertically (9.99999px from data), 24px horizontally.

### Outlined Accent Button
**Role:** Call to action with secondary emphasis or promoting brand color.

Background: transparent rgba(0, 0, 0, 0), Text: Cyber Cyan #6ae4ff, Border: Cyber Cyan #6ae4ff, Radius: 16px, Padding: 12px.

### Ghost Bordered Button
**Role:** Minimal call to action, often for navigation or secondary actions.

Background: transparent rgba(0, 0, 0, 0), Text: Polar White #ffffff, Border: Polar White #ffffff, Radius: 80px, Padding: 5px vertically, 30px horizontally.

### Data Card
**Role:** Display financial metrics or product features.

Background: Midnight Ink #17202, Radius: 15px, Padding: 66px. Inner text is primarily Cyber Cyan #6ae4ff for key values.

### Nested Dark Card
**Role:** Sub-element within a larger card or section, like badges within data cards.

Background: Astral Gray #202a3, Text: Cyber Cyan #6ae4ff, Border: Cyber Cyan #6ae4ff, Radius: 16px, Padding: 12px.

### Large Feature Card
**Role:** Prominent information blocks with generous padding.

Background: Midnight Ink #17202, Radius: 15px, Padding: 66px.

### Outline Input Field
**Role:** Form input elements.

Background: transparent rgba(0, 0, 0, 0), Text: Polar White #ffffff, Border: Polar White #ffffff, Radius: 0px, Padding: 1px vertically, 2px horizontally.

## Do's and Don'ts

### Do
- Use Midnight Ink #17202 as the base background for most surfaced elements, ensuring a consistent dark theme.
- Apply Cyber Cyan #6ae4ff for all interactive elements like links, buttons with text, and prominent data points to guide user attention.
- Maintain a clear visual hierarchy with generous vertical spacing between sections, using multiples of 24px and 16px as element gaps.
- Employ a distinctive global letter-spacing of -0.0360em from Open Sans for all headlines and significant text elements.
- Use a large border-radius of 80px for ghost buttons to give them a soft, pill-like appearance, differentiating them from other interactive elements.
- Prioritize transparency and subtle surface elevation through color changes rather than heavy shadows to maintain a sleek, modern feel.
- All cards should use a 15px border-radius with Midnight Ink #17202 backgrounds to establish a consistent container style.

### Don't
- Avoid using primary text colors on anything but dark backgrounds; they are not intended for light surfaces.
- Do not introduce strong, unbranded chromatic colors that are not Cyber Cyan #6ae4ff, as this breaks the established accent palette.
- Do not use sharp 0px corners, as components uniformly apply 4px, 15px, or 80px radii, even for inputs.
- Do not pack elements tightly; maintain the comfortable density with consistent element gaps of 16px.
- Do not add drop shadows to cards or interactive elements, as the system relies on background color shifts for hierarchy.
- Do not vary font families outside of Open Sans, Source Sans Pro, and Arial, or introduce new weights for these fonts than specified.
- Do not add additional decorative gradients that differ from Deep Ocean Gradient, Nebula Core Gradient, or Emerald Vapor Gradient.

## Imagery

The visual language focuses on abstract, technological graphics, particularly nuanced dark background gradients that imply depth and complexity. Icons are primarily monochromatic, using the Cyber Cyan accent for clarity or occasionally white. There is a strong absence of human or lifestyle photography. Product screenshots may appear but are usually framed within dark UI elements. The overall density is image-light, with visuals serving as atmospheric backdrops or functional indicators, not primary content.

## Layout

The page primarily uses a full-bleed dark background that progressively lightens towards the center, often forming a radial gradient effect, but content is typically contained within a maximum width. The hero section is full-bleed, characterized by a large centered headline over a dark gradient. Sections generally alternate between background gradients or solid dark hues. Content is often arranged in centered stacks or symmetrical multi-column grids (like 3-column cards for features), with substantial vertical spacing between blocks. Navigation is via a sticky top bar, minimalist and unobtrusive.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #17202e
border: #ffffff
accent: #6ae4ff
primary action: #ffffff (filled action)

Example Component Prompts:
Create a hero section with a large heading: use Open Sans, 100px size, weight 400, #ffffff color, line-height 1.0, and letter-spacing -3.6px. Place on a background using Nebula Core Gradient.

Create a Data Card: background Midnight Ink #17202e, border-radius 15px, and padding 66px. Inside, use Open Sans, 18px, weight 400, color Cyber Cyan #6ae4ff for key values, with Open Sans 14px, #cdd0d6 for labels.

Create a Ghost Bordered Button: background transparent rgba(0, 0, 0, 0), text Polar White #ffffff, border Polar White #ffffff, border-radius 80px, padding 5px vertically, 30px horizontally, using Source Sans Pro, 14px, weight 400.

Generate an Outlined Accent Button: with transparent rgba(0, 0, 0, 0) background, Cyber Cyan #6ae4ff text, Cyber Cyan #6ae4ff border, 16px border-radius, and 12px padding. Use Source Sans Pro, 12px, weight 400.

## Similar Brands

- **Aave** — Dark UI with contained cards, similar typographic treatment, and emphasis on data presentation in a financial context.
- **Uniswap** — High-tech, dark mode UI with a single vivid accent color for interactive elements and data visuals.
- **Arbitrum** — Focus on gradients and abstract background visuals in a dark-themed decentralized finance context.
- **Yearn Finance** — Data-heavy interface with a minimalist dark theme, compact typography, and strategic use of color for key metrics.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #17202e;
  --color-astral-gray: #202a3e;
  --color-star-dust: #cdd0d6;
  --color-void-black: #000000;
  --color-polar-white: #ffffff;
  --color-cyber-cyan: #6ae4ff;
  --color-deep-ocean-gradient: #2d3748;
  --gradient-deep-ocean-gradient: linear-gradient(90deg, rgb(45, 55, 72), rgb(74, 85, 104), rgb(113, 128, 150), rgb(74, 85, 104));
  --color-nebula-core-gradient: #08218f;
  --gradient-nebula-core-gradient: radial-gradient(circle, rgb(8, 33, 143) 40%, rgb(41, 138, 203) 100%);
  --color-emerald-vapor-gradient: #34edb3;
  --gradient-emerald-vapor-gradient: linear-gradient(73.6deg, rgb(52, 237, 179) 2.11%, rgb(0, 209, 255));

  /* Typography — Font Families */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.96;
  --tracking-caption: -0.432px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: -0.504px;
  --text-body: 18px;
  --leading-body: 1.57;
  --tracking-body: -0.648px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.72px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: -0.792px;
  --text-heading: 28px;
  --leading-heading: 1.33;
  --tracking-heading: -1.008px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.296px;
  --text-display-sm: 56px;
  --leading-display-sm: 1;
  --tracking-display-sm: -2.016px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -3.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-136: 136px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 66px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 15px;
  --radius-3xl: 24px;
  --radius-full: 80px;

  /* Named Radii */
  --radius-misc: 24px;
  --radius-cards: 15px;
  --radius-links: 8px;
  --radius-buttons: 80px;
  --radius-smallbuttons: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #17202e;
  --color-astral-gray: #202a3e;
  --color-star-dust: #cdd0d6;
  --color-void-black: #000000;
  --color-polar-white: #ffffff;
  --color-cyber-cyan: #6ae4ff;
  --color-deep-ocean-gradient: #2d3748;
  --color-nebula-core-gradient: #08218f;
  --color-emerald-vapor-gradient: #34edb3;

  /* Typography */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-sans-pro: 'Source Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.96;
  --tracking-caption: -0.432px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: -0.504px;
  --text-body: 18px;
  --leading-body: 1.57;
  --tracking-body: -0.648px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.72px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: -0.792px;
  --text-heading: 28px;
  --leading-heading: 1.33;
  --tracking-heading: -1.008px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.296px;
  --text-display-sm: 56px;
  --leading-display-sm: 1;
  --tracking-display-sm: -2.016px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -3.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-136: 136px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 15px;
  --radius-3xl: 24px;
  --radius-full: 80px;
}
```
