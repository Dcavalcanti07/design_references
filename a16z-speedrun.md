# a16z speedrun — Style Reference
> Contrastive Canvas, Precise Details

**Theme:** mixed

The a16z speedrun design system establishes a stark, high-contrast visual identity with a predominant dark background for its hero section, juxtaposed with a serene, light theme for content areas. Typography is compact and precise, utilizing custom Messina Sans families with tight letter-spacing for headlines and body text. Visual interest is introduced through a subtle, warm off-white canvas and discreet gradients for branding elements, creating a sense of grounded modernity rather than overt futurism. Component radii are generally rounded but restrained, contributing to a refined yet approachable feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#000000` | `--color-midnight-graphite` | Primary text, button backgrounds, dominant hero background, accent for structural elements |
| Canvas Fog | `#e5e7eb` | `--color-canvas-fog` | Page background for content sections, subtle borders, card outlines. Provides a soft, almost imperceptible warmth |
| Paper White | `#ffffff` | `--color-paper-white` | Card backgrounds, elevated surfaces, secondary text on dark backgrounds |
| Warm Mist | `#e2dfd8` | `--color-warm-mist` | Subtle background for less prominent sections or supporting surfaces |
| Muted Steel | `#5e5d5c` | `--color-muted-steel` | Secondary text, subtle details, less prominent links, body text in specific contexts |
| Violet Bloom | `radial-gradient(169.597% 169.597% at 0% 7.52345%, rgb(161, 98, 255) 49%, rgba(145, 76, 255, 0) 49.83%)` | `--color-violet-bloom` | Decorative gradients, radial highlights for visual interest. Softly hints at digital innovation |
| Golden Dawn | `radial-gradient(209.904% 209.904% at 0% 7.52345%, rgb(248, 220, 187) 0%, rgb(248, 220, 187) 49%, rgba(226, 223, 216, 0) 50%)` | `--color-golden-dawn` | Decorative gradients, radial highlights for visual interest. Adds a touch of earthy warmth |

## Tokens — Typography

### messinaSans — Primary typeface for all headings and body text, with a focus on heavier weights and tight tracking for impactful, dense headlines. The extremely tight letter-spacing on larger sizes creates a sense of gravitas and precision. · `--font-messinasans`
- **Substitute:** Inter
- **Weights:** 600, 700, 900
- **Sizes:** 13px, 16px, 20px, 32px, 48px, 64px, 72px, 243px
- **Line height:** 1.00, 1.20, 1.23, 1.25, 1.50
- **Letter spacing:** -0.0740em (243px), -0.0500em (72px), -0.0300em (64px, 48px, 32px, 20px), -0.0100em (smaller sizes)
- **Role:** Primary typeface for all headings and body text, with a focus on heavier weights and tight tracking for impactful, dense headlines. The extremely tight letter-spacing on larger sizes creates a sense of gravitas and precision.

### messinaSansCondensed — Used for specific compact elements like buttons and navigation, providing a slightly wider, more structured feel than the regular Messina Sans for these interactive components. · `--font-messinasanscondensed`
- **Substitute:** IBM Plex Sans Condensed
- **Weights:** 600
- **Sizes:** 12px, 16px, 18px
- **Line height:** 1.11, 1.25, 1.33
- **Letter spacing:** 0.0400em (12px), 0.0600em (18px)
- **Role:** Used for specific compact elements like buttons and navigation, providing a slightly wider, more structured feel than the regular Messina Sans for these interactive components.

### Messina Sans — Messina Sans — detected in extracted data but not described by AI · `--font-messina-sans`
- **Weights:** 600
- **Sizes:** 16px
- **Line height:** 1.5
- **Letter spacing:** -0.03
- **Role:** Messina Sans — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.23 | — | `--text-caption` |
| body-sm | 16px | 1.23 | — | `--text-body-sm` |
| body | 20px | 1.23 | — | `--text-body` |
| body-lg | 32px | 1.23 | — | `--text-body-lg` |
| heading-sm | 48px | 1.23 | — | `--text-heading-sm` |
| heading | 64px | 1.23 | — | `--text-heading` |
| heading-lg | 72px | 1.23 | — | `--text-heading-lg` |
| display-sm | 243px | 1.23 | — | `--text-display-sm` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 8px |
| general | 8px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Call to action button for key actions.

Background: Midnight Graphite (#000000), Text: Paper White (#ffffff), Border: 1px solid Canvas Fog (#e5e7eb) for a subtle separation. Radius: 8px. Padding: 8-24px vertical, 12-56px horizontal (variable, typically 24px top, 8px bottom, 56px left, 12px right).

### Ghost Button
**Role:** Secondary and tertiary actions, navigation buttons.

Background: Transparent, Text: Midnight Graphite (#000000), Border: 1px solid Canvas Fog (#e5e7eb). Radius: 8px. Padding: 8-24px vertical, 12-56px horizontal (variable, typically 24px top, 8px bottom, 56px left, 12px right).

### Square Ghost Button
**Role:** Utility buttons in navigation or compact interactive areas.

Background: Transparent, Text: Midnight Graphite (#000000), Border: 1px solid Canvas Fog (#e5e7eb). Radius: 6px. Padding: 8px vertical, 12px horizontal.

### Zero-Radius Ghost Button
**Role:** Minimalist interactive elements or text-like buttons.

Background: Transparent, Text: Midnight Graphite (#000000), Border: 1px solid Canvas Fog (#e5e7eb). Radius: 0px. Padding: 8px vertical, 12px horizontal.

### Feature Card
**Role:** Displaying key features or benefits with visuals and text.

Background: Paper White (#ffffff), no shadow. Radius: 12px. Padding: 0px top, 24px right, 44px bottom, 24px left. Contains a sub-card for images.

### Image Holder Card
**Role:** Container for images within Feature Cards.

Background: Paper White (#ffffff), no shadow. Radius: 8px. No padding, images fill the internal space.

## Do's and Don'ts

### Do
- Use Midnight Graphite (#000000) for all primary text and calls to action on light backgrounds, ensuring AAA contrast.
- Apply Canvas Fog (#e5e7eb) as the primary background for all content sections, providing a soft, almost imperceptible foundation.
- Implement Messina Sans with tight letter-spacing (e.g., -0.0740em for 243px, -0.0300em for 64px) for all large headlines to create a dense, impactful textual presence.
- Round corners of cards to 12px and buttons/general interactive elements to 8px, maintaining a consistent soft edge.
- Maintain a clear visual hierarchy by utilizing the 40px `sectionGap` between major content blocks and a more granular 12px `elementGap` for internal component spacing.
- Integrate radial gradients featuring Violet Bloom (#a162ff) or Golden Dawn (#f8dcbb) sparingly as decorative accents to highlight key areas or imagery.
- Ensure all interactive elements, especially ghost buttons, have a 1px solid Canvas Fog (#e5e7eb) border for subtle definition.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; maintain a neutral base with color used for subtle accents.
- Do not deviate from the specified Messina Sans typography with its tight letter-spacing, as this is a core brand identifier.
- Refrain from introducing heavy drop shadows; the system prioritizes flat design with subtle borders for hierarchy and structure.
- Do not use generic system fonts; always utilize Messina Sans or its condensed variant for any text to preserve brand voice.
- Avoid large imagery with distracting backgrounds; prioritize focused product shots or relevant figures against simple backdrops.
- Do not use gradients as primary button fills or for extensive background washes; they are decorative accents, not structural elements.
- Do not introduce additional border radii; adhere strictly to 8px for buttons and 12px for cards.

## Imagery

The visual language for imagery is a mix of high-quality staged photography of key individuals (likely founders or VCs) used in hero sections, and product-focused or event photography within content cards. Photography is often presented in a natural, candid style but well-lit, with subjects looking engaged. Illustrations, when present, appear to be graphic, sometimes monochromatic, and integrated into the overall visual grid. Icons are minimal, outlined, or filled, with a consistent stroke weight. Imagery serves both decorative atmosphere, particularly in the striking hero image, and explanatory content, showcasing individuals and events related to the brand. Density is balanced, with imagery carefully curated to complement text blocks without overwhelming them.

## Layout

The page primarily uses a full-bleed layout for its hero section, featuring a dark background with a centered headline. Subsequent content sections alternate between a light, contained layout and an occasional dark, full-width element. There is a strong emphasis on consistent vertical spacing, with a 40px section gap creating clear breaks between major content blocks. Content is arranged in a fluid, often two-column grid on larger screens, with text-left/image-right or image-left/text-right alternating patterns. Feature cards are presented in a 3-column grid. The navigation is a fixed top bar with transparent background over the hero, becoming opaque against light sections, and uses a mix of ghost buttons and simple links. The layout feels spacious but purposeful, guiding the eye through information.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #e5e7eb
border: #e5e7eb
accent: #a162ff
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background Midnight Graphite (#000000), text Paper White (#ffffff), border 1px solid Canvas Fog (#e5e7eb), radius 8px, padding 24px top, 8px bottom, 56px left, 12px right.
2. Design a Feature Card: background Paper White (#ffffff), no shadow, radius 12px, padding 0px top, 24px right, 44px bottom, 24px left. Inside, include an Image Holder Card with radius 8px.
3. Make a Ghost Button: background transparent, text Midnight Graphite (#000000), border 1px solid Canvas Fog (#e5e7eb), radius 8px, padding 24px top, 8px bottom, 56px left, 12px right.
4. Create a page section with Canvas Fog background (#e5e7eb), a main heading in Messina Sans 64px weight 900, Midnight Graphite (#000000) with -0.0300em letter spacing, followed by body text in Messina Sans 16px weight 600, Muted Steel (#5e5d5c) with normal letter spacing, separated by a 40px vertical gap to the next section.

## Similar Brands

- **OpenAI** — Uses a similar high-contrast, text-dominant hero with stark typography, shifting to lighter content sections. Focus on a strong brand message with minimal decoration.
- **Vercel** — Shares a foundation of clean, light interfaces with precise, often condensed typography and a strategic use of dark backgrounds for impact or code blocks.
- **Linear** — Employs a strict grid, tight typography, and a reduced color palette to achieve a highly efficient and modern aesthetic, similar to the precision of Messina Sans.
- **Replit** — Combines a dark, command-line aesthetic (seen in the hero) with structured, functional UI components on lighter backgrounds for the main content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-canvas-fog: #e5e7eb;
  --color-paper-white: #ffffff;
  --color-warm-mist: #e2dfd8;
  --color-muted-steel: #5e5d5c;
  --color-violet-bloom: #a162ff;
  --gradient-violet-bloom: radial-gradient(169.597% 169.597% at 0% 7.52345%, rgb(161, 98, 255) 49%, rgba(145, 76, 255, 0) 49.83%);
  --color-golden-dawn: #f8dcbb;
  --gradient-golden-dawn: radial-gradient(209.904% 209.904% at 0% 7.52345%, rgb(248, 220, 187) 0%, rgb(248, 220, 187) 49%, rgba(226, 223, 216, 0) 50%);

  /* Typography — Font Families */
  --font-messinasans: 'messinaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messinasanscondensed: 'messinaSansCondensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.23;
  --text-body-sm: 16px;
  --leading-body-sm: 1.23;
  --text-body: 20px;
  --leading-body: 1.23;
  --text-body-lg: 32px;
  --leading-body-lg: 1.23;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.23;
  --text-heading: 64px;
  --leading-heading: 1.23;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.23;
  --text-display-sm: 243px;
  --leading-display-sm: 1.23;

  /* Typography — Weights */
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 8px;
  --radius-general: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-canvas-fog: #e5e7eb;
  --color-paper-white: #ffffff;
  --color-warm-mist: #e2dfd8;
  --color-muted-steel: #5e5d5c;
  --color-violet-bloom: #a162ff;
  --color-golden-dawn: #f8dcbb;

  /* Typography */
  --font-messinasans: 'messinaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messinasanscondensed: 'messinaSansCondensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.23;
  --text-body-sm: 16px;
  --leading-body-sm: 1.23;
  --text-body: 20px;
  --leading-body: 1.23;
  --text-body-lg: 32px;
  --leading-body-lg: 1.23;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.23;
  --text-heading: 64px;
  --leading-heading: 1.23;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.23;
  --text-display-sm: 243px;
  --leading-display-sm: 1.23;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
