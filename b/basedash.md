# Basedash — Style Reference
> Midnight data studio.

**Theme:** dark

Basedash employs a 'dark studio canvas' aesthetic, designed to showcase product functionality with stark clarity against a deep, almost black background. White typography and a single vibrant purple accent provide functional highlights and interactive cues, giving the interface a precise, analytical feel. Components are minimalist, often defined by subtle borders or ghost styles, suggesting a lightweight and highly performant system. The overall impression is one of focused utility, where UI elements serve to illuminate data rather than compete with it.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian Canvas | `#000000` | `--color-obsidian-canvas` | Primary page and hero backgrounds, deep surface base |
| Eclipse Surface | `#050607` | `--color-eclipse-surface` | Card backgrounds, secondary dark surfaces |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, button backgrounds, active navigation elements |
| Ash Gray | `#b3b3b3` | `--color-ash-gray` | Muted text, hairline borders, secondary content |
| Steel Gray | `#808080` | `--color-steel-gray` | Tertiary text, inactive icons, subtle dividers |
| Carbon Detail | `#333333` | `--color-carbon-detail` | Fine borders, subtle text elements |
| Illumination White | `#e8eaee` | `--color-illumination-white` | Subtle background for specific sections, sometimes for borders |
| Vivid Violet | `#9984d8` | `--color-vivid-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Gradient Violet | `linear-gradient(rgba(107, 90, 168, 0.66), rgba(84, 67, 142, 0.64) 44%, rgba(58, 44, 110, 0.68))` | `--color-gradient-violet` | Atmospheric background gradient for accent regions, hinting at depth and digital glow |
| Alert Green | `#3fcb7f` | `--color-alert-green` | Success states, live indicators, or positive metrics within charts/badges |
| Radial Violet Glow | `radial-gradient(rgba(163, 102, 255, 0.38), rgba(123, 78, 245, 0.24) 38%, rgba(82, 49, 184, 0.12) 56%, rgba(0, 0, 0, 0) 78%)` | `--color-radial-violet-glow` | Soft, expanding radial glow often used as subtle background illumination for product showcases |

## Tokens — Typography

### Inter — Primary UI font for body text, navigation, buttons, and most informational elements. Its functional nature maintains clarity across various weights and sizes. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 30px, 34px, 48px
- **Line height:** 1.00, 1.20, 1.33, 1.38, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0300em
- **Role:** Primary UI font for body text, navigation, buttons, and most informational elements. Its functional nature maintains clarity across various weights and sizes.

### Alpha Lyrae — Display font for prominent headlines, used sparingly to create a distinctive, digital aesthetic. Specific stylistic sets ('ss01', 'ss02') contribute to its unique character. · `--font-alpha-lyrae`
- **Weights:** 400
- **Sizes:** 48px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"ss01" on, "ss02" on`
- **Role:** Display font for prominent headlines, used sparingly to create a distinctive, digital aesthetic. Specific stylistic sets ('ss01', 'ss02') contribute to its unique character.

### Iowan Old Style — Serif font for specific body or quote elements at larger sizes, providing a refined textual counterpoint to the sans-serif display type. The light weight (300) combined with slight letter-spacing creates an airy, almost whispered presence. · `--font-iowan-old-style`
- **Substitute:**  serif
- **Weights:** 300
- **Sizes:** 24px
- **Line height:** 1.25
- **Letter spacing:** -0.0250em
- **Role:** Serif font for specific body or quote elements at larger sizes, providing a refined textual counterpoint to the sans-serif display type. The light weight (300) combined with slight letter-spacing creates an airy, almost whispered presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.36px | `--text-caption` |
| heading-sm | 18px | 1.5 | -0.54px | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.6px | `--text-heading` |
| heading-lg | 30px | 1.33 | -0.9px | `--text-heading-lg` |
| display-sm | 34px | 1.2 | -1.02px | `--text-display-sm` |
| display | 48px | 1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 16px |
| fields | 6px |
| buttons | 6px |

### Layout

- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Call to action button for starting free trials or sign-ups.

Solid Ghost White background (#ffffff), Obsidian Canvas text (#000000). Padding is 8px vertical, 20px horizontal. Border-radius of 12px.

### Ghost Accent Button
**Role:** Secondary call to action button, or action that needs subtle visual emphasis.

Transparent background with 25% opacity (oklab(0 0 0 / 0.25)), Ghost White text (#ffffff). Outline border in 10% opacity white (rgba(255, 255, 255, 0.1)). Padding is 8px vertical, 20px horizontal. Border-radius of 12px.

### Navigation Link Button
**Role:** Links within the main navigation bar.

Transparent background, muted Ghost White text (rgba(255, 255, 255, 0.5)). No padding or border-radius; meant to be part of inline navigation.

### Small Dark Button
**Role:** Compact utility buttons, often for logging in or secondary actions in header.

Obsidian Canvas background (#000000), Ghost White text (#ffffff). Outline border in 10% opacity white (rgba(255, 255, 255, 0.1)). Padding 8px vertical, 12px horizontal. Border-radius of 6px.

### Content Card
**Role:** Containers for content blocks like testimonials or feature descriptions.

Solid Eclipse Surface background (#050607), no box-shadow. Border-radius of 14px. Padding 14px vertical, 14px horizontal internally.

### Live Status Badge
**Role:** Used to denote 'Live' status or positive indicators.

Solid Alert Green background (#3fcb7f), Ghost White text at 70% opacity (rgba(255, 255, 255, 0.7)). Very high border-radius (1.67772e+07px) creating a pill shape. No internal padding means text is flush with badge background.

## Do's and Don'ts

### Do
- Use Obsidian Canvas (#000000) as the dominant background color for seamless dark mode cohesion.
- Apply Ghost White (#ffffff) for primary text and calls to action against dark backgrounds to ensure high contrast.
- Employ Vivid Violet (#9984d8) as a border accent for interactive elements or visual framing, not as a primary fill color for buttons.
- Utilize Inter font for all functional text: body, buttons, navigation, and smaller headings at its specified letter spacing -0.0300em.
- Maintain a clear visual hierarchy by limiting Alpha Lyrae to prominent headlines at 48px, with its unique font feature settings "ss01" and "ss02".
- Define card surfaces with Eclipse Surface (#050607) and a 14px border-radius, reserving elevation for occasional, subtle glows.
- Apply 6px border-radius for buttons and input fields, and 16px for cards to maintain consistent shape language.
- Use Alert Green (#3fcb7f) specifically for positive semantic indicators like 'Live' status or success messages.

### Don't
- Avoid using bright, saturated colors for large background areas; stick to the neutral palette for canvas and surfaces.
- Do not introduce strong visual shadows on elements; elevation is primarily achieved through subtle background glows or no shadow at all.
- Do not use Iowan Old Style for general UI text; reserve it for specific, larger body sections or quotes requiring a refined feel.
- Refrain from drastically altering letter-spacing for Inter font; maintain -0.0300em for consistent text density.
- Do not deviate from the established padding values for buttons (8px vertical, 20px horizontal for larger, 8px vertical, 12px horizontal for small) to preserve component weight.
- Avoid adding new radii values; adhere to 6px, 14px/16px, and 999px for consistency across components.
- Do not use Vivid Violet (#9984d8) as a background for primary calls to action, as it functions as an accent border or decorative element.

## Imagery

Imagery on Basedash is primarily functional product screenshots and data visualizations, presented directly with minimal framing. These are often enveloped by subtle atmospheric gradients or glows (like the Radial Violet Glow) that hint at functionality without being distracting. The icons are mostly monochromatic (white), with some being multi-colored, and serve to represent data sources or integrations in a compact, recognizable format. There’s a balance between text dominance and visual explanation, where images clarity illustrates product features.

## Layout

The page structure favors a full-bleed layout, particularly in the hero section, but maintains content within discernable, perhaps implied, max-width constraints in other areas. The hero features a centered headline over a dark, subtly animated product visual. Section rhythm is primarily consistent vertical spacing on a dark canvas, utilizing the Obsidian Canvas as a continuous background rather than alternating light/dark bands. Content is arranged in flexible patterns, including centered stacks for key messages and multi-column grids for integrations. Navigation is a sticky top bar, minimalist and unobtrusive.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #b3b3b3
accent: #9984d8
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Testimonial Card for 'Nathan Baschez Founder · Lex': Eclipse Surface background, 14px border-radius, 14px padding. Quote text in Iowan Old Style weight 300 at 24px, Ghost White text, letter-spacing -0.0250em. Below, add 'Read case study →' as an Ash Gray link.
3. Implement a 'Log in' navigation button: No background, Ghost White text at 50% opacity (rgba(255, 255, 255, 0.5)), Inter weight 400 at 16px, no padding or border-radius.

## Similar Brands

- **Linear** — Dark-themed UI, minimalist components, and a single accent color for interactive elements.
- **Supabase** — Deep dark backgrounds, high-contrast white text, and product-focused imagery with subtle glowing effects.
- **Vercel** — Clean, dark interface with ghost buttons, precise typography, and functional use of white space.
- **Stripe** — Emphasis on clear, readable typography against simple backgrounds, and a focus on product visuals.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian-canvas: #000000;
  --color-eclipse-surface: #050607;
  --color-ghost-white: #ffffff;
  --color-ash-gray: #b3b3b3;
  --color-steel-gray: #808080;
  --color-carbon-detail: #333333;
  --color-illumination-white: #e8eaee;
  --color-vivid-violet: #9984d8;
  --color-gradient-violet: #6b5aa8;
  --gradient-gradient-violet: linear-gradient(rgba(107, 90, 168, 0.66), rgba(84, 67, 142, 0.64) 44%, rgba(58, 44, 110, 0.68));
  --color-alert-green: #3fcb7f;
  --color-radial-violet-glow: #a366ff;
  --gradient-radial-violet-glow: radial-gradient(rgba(163, 102, 255, 0.38), rgba(123, 78, 245, 0.24) 38%, rgba(82, 49, 184, 0.12) 56%, rgba(0, 0, 0, 0) 78%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-alpha-lyrae: 'Alpha Lyrae', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-iowan-old-style: 'Iowan Old Style', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.54px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.9px;
  --text-display-sm: 34px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -1.02px;
  --text-display: 48px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 16px;
  --radius-fields: 6px;
  --radius-buttons: 6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian-canvas: #000000;
  --color-eclipse-surface: #050607;
  --color-ghost-white: #ffffff;
  --color-ash-gray: #b3b3b3;
  --color-steel-gray: #808080;
  --color-carbon-detail: #333333;
  --color-illumination-white: #e8eaee;
  --color-vivid-violet: #9984d8;
  --color-gradient-violet: #6b5aa8;
  --color-alert-green: #3fcb7f;
  --color-radial-violet-glow: #a366ff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-alpha-lyrae: 'Alpha Lyrae', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-iowan-old-style: 'Iowan Old Style', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.36px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.54px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.9px;
  --text-display-sm: 34px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -1.02px;
  --text-display: 48px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-full: 999px;
}
```
