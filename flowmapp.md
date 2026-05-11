# Flowmapp — Style Reference
> Architectural blueprint on white marble, accented with soft, glowing energy.

**Theme:** light

This design evokes a feeling of structured clarity and playful dynamism, balancing functional utility with a touch of modern vibrancy. The primarily white-bodied interface provides a blank canvas, punctuated by a deep blue accent (#0080ff) that guides interaction. Organic, blurred background shapes add a soft, futuristic atmosphere, while the crisp black typography and rounded components (#1600px, #12px) create a friendly yet precise tool.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary button backgrounds. |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, prominent icons, dark button backgrounds. |
| Steel Gray | `#8c9baa` | `--color-steel-gray` | Secondary text, subtle borders, inactive elements. |
| Highlight Blue | `#0080ff` | `--color-highlight-blue` | Call-to-action buttons, interactive elements, key iconography – signaling action and attention. |
| Subtle Blue | `#c5e0fb` | `--color-subtle-blue` | Light background details, subtle button fills, card elements, supporting the primary blue without competing. |
| Gradient Violet | `#0050ff` | `--color-gradient-violet` | Used as the border for cards, it provides a subtle visual lift and defines interactive sections with a touch of color. |
| Pebble Gray | `#dee0e4` | `--color-pebble-gray` | Subtle borders, dividers, and background accents. |
| Charcoal Text | `#222222` | `--color-charcoal-text` | Navigation text, less prominent black text for hierarchical distinction. |

## Tokens — Typography

### Inter — All text elements: headlines, body copy, navigation, buttons. Its broad range of weights and sizes supports a clear typographic hierarchy, making it versatile for both display and utilitarian text. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 24px, 30px, 36px, 48px, 64px, 72px, 84px, 96px, 118px
- **Line height:** 1.0 to 1.67
- **Letter spacing:** -0.0600em at largest sizes, less at smaller sizes
- **Role:** All text elements: headlines, body copy, navigation, buttons. Its broad range of weights and sizes supports a clear typographic hierarchy, making it versatile for both display and utilitarian text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 14px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 36px | 1.14 | -0.48px | `--text-heading` |
| heading-lg | 48px | 1.14 | -0.48px | `--text-heading-lg` |
| display | 72px | 1.09 | -0.48px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 144 | 144px | `--spacing-144` |
| 184 | 184px | `--spacing-184` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 1600px |
| smallUI | 6px |
| largeCards | 32px |
| accentedCards | 20px |
| interactiveElements | 1600px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.06) 0px 0px 18px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1560px
- **Section gap:** 48-80px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Secondary Button (Dark Fill)
**Role:** Secondary Action

Filled with Ink Black (#000000), white text, with 12px radius. Offers a strong alternative action without competing with the primary blue. Padding: 7.04px vertical, 10.08px horizontal.

### Secondary Button (Light Fill)
**Role:** Secondary Action

Filled with Canvas White (#ffffff), Ink Black (#000000) text, with 12px radius. Used for less prominent actions, often within navigation. Padding: 9.92px vertical, 12px horizontal.

### Ghost Button (Blue Accent)
**Role:** Tertiary Action

Transparent background, white text, 1600px radius. Highlighted with rgba(0, 128, 255, 0.2) as background, providing a subtle interactive cue. Padding: 12px all around.

### Standard Card
**Role:** Content Container

Canvas White (#ffffff) background, 12px border-radius, no shadow. Internal padding: 24px.

### Accent Border Card
**Role:** Highlight Container

Transparent background, 20px border-radius, no shadow, with a distinct Gradient Violet (#0050ff) border detected in patterns. Internal padding: 24px.

### Page Header Navigation
**Role:** Global Navigation

Features Canvas White background for text and active links, Steel Gray text for other links. Includes a white secondary button and a pill-shaped primary CTA.

### Callout Icon Card
**Role:** Feature Highlight

Transparent background with 32px radius, no shadow. Padding: 24px. Houses icons or small informational blocks.

## Do's and Don'ts

### Do
- Use Highlight Blue (#0080ff) exclusively for primary calls-to-action and critical interactive feedback.
- Apply 1600px radius for all primary buttons and interactive elements to maintain the 'pill' aesthetic.
- Maintain a clear visual hierarchy by using Ink Black (#000000) for main headings and Canvas White (#ffffff) for card/page backgrounds.
- Utilize the Inter font family across all typographic elements, leveraging its full range of weights (400-700) for distinct hierarchy.
- Ensure consistent internal padding of 24px for all `Standard Card` and `Accent Border Card` components.
- Implement the Steel Gray (#8c9baa) for secondary text and subtle navigational elements to soften visual noise.

### Don't
- Do not introduce new color tones; stick to the defined palette of blues, grays, black, and white.
- Avoid using sharp corners; all significant UI elements like buttons and cards must use a defined border-radius (12px, 20px, 32px, or 1600px).
- Do not apply drop shadows to cards or primary UI elements; visual depth is created through background blur gradients and borders.
- Refrain from using color to denote semantic states (e.g., red for error, green for success) unless explicitly defined within the system; use established brand colors instead.
- Do not deviate from the Inter typeface; avoid introducing any additional font families.
- Avoid excessive use of bold typography; reserve font weight 700 for headlines, and 600 for important subheadings or call-to-action text.

## Elevation

- **Floating Elements / Pop-ups:** `rgba(0, 0, 0, 0.06) 0px 0px 18px 0px`

## Imagery

The site uses a mix of light, playful illustrations and product screenshots, with abstract, organic gradient shapes (#98cafc, #3298fe, #82bffc) creating a vibrant background. Illustrations are simple, two-dimensional, often depicting tiny, functional elements or user interface snippets. Product screenshots are contained within rounded frames, showcasing the application's UI on mobile devices or in flow diagrams. Icons are primarily filled, black, and utilize the rounded aesthetic present throughout the UI. The overall density is balanced, allowing significant whitespace around visual elements, making the images feel airy and decorative rather than information-heavy.

## Layout

The page operates on a max-width contained model of 1560px, maintaining a centered content block throughout. The hero section is full-bleed with a large, centered headline and a prominent primary CTA, visually supported by abstract, blurred gradient shapes that hint at depth and dynamism without direct interaction. Section rhythm is consistent, with clear vertical spacing and sections primarily occupying a single column stack for headlines followed by multi-column arrangements (e.g., 2-column text+icon features, 3-column card grids for features). There's no alternating light/dark banding; the design maintains a mostly white background. Navigation is a sticky top bar with a focused left-aligned logo and right-aligned interactive elements including the primary CTA.

## Agent Prompt Guide

**Quick Color Reference**
- Text: #000000
- Background: #ffffff
- CTA: #0080ff
- Border/Accent: #8c9baa
- Card Surface: #ffffff

**Example Component Prompts**
- Create a `Primary CTA Button`: blue background (#0080ff), white text, 1600px radius, 16px 32px padding, Inter size 16 weight 700.
- Generate a `Standard Card`: white background (#ffffff), 12px radius, no shadow, 24px padding. Headline: Inter size 24 weight 600, Ink Black (#000000). Body: Inter size 14 weight 400, Steel Gray (#8c9baa).
- Design a `Secondary Button (Light Fill)`: white background (#ffffff), black text (#000000), 12px radius, 9.92px 12px padding. Text should be Inter size 16 weight 500.
- Construct a `Page Header Navigation` bar: white background (#ffffff), height 70px. Left-aligned logo, right-aligned 'Log in' link (Inter size 14 weight 500, Ink Black), and 'Try for free' button (Primary CTA Button style).

## Similar Brands

- **Linear** — Clean, predominantly white interfaces with strong typographic hierarchy and a single vivid accent color for interactive elements.
- **Figma** — Focus on functional UI elements, clear content organization, and subtle use of rounded shapes and background gradients to add visual interest.
- **Miro** — Visual emphasis on collaboration tools, with a bright white canvas, clear black text, and distinct clickable areas highlighted by color or subtle borders.
- **Canva** — Combination of clean, accessible UI with playful, often abstract background elements or illustrations to convey creativity and ease of use.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-steel-gray: #8c9baa;
  --color-highlight-blue: #0080ff;
  --color-subtle-blue: #c5e0fb;
  --color-gradient-violet: #0050ff;
  --color-pebble-gray: #dee0e4;
  --color-charcoal-text: #222222;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -0.48px;
  --text-display: 72px;
  --leading-display: 1.09;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-144: 144px;
  --spacing-184: 184px;
  --spacing-200: 200px;

  /* Layout */
  --page-max-width: 1560px;
  --section-gap: 48-80px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 1600px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 1600px;
  --radius-smallui: 6px;
  --radius-largecards: 32px;
  --radius-accentedcards: 20px;
  --radius-interactiveelements: 1600px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 0px 18px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-steel-gray: #8c9baa;
  --color-highlight-blue: #0080ff;
  --color-subtle-blue: #c5e0fb;
  --color-gradient-violet: #0050ff;
  --color-pebble-gray: #dee0e4;
  --color-charcoal-text: #222222;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -0.48px;
  --text-display: 72px;
  --leading-display: 1.09;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-144: 144px;
  --spacing-184: 184px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 1600px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 0px 18px 0px;
}
```
