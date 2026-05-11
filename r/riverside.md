# Riverside — Style Reference
> Midnight production studio

**Theme:** dark

Riverside's aesthetic is a dark-mode canvas punctuated by vibrant purple actions and crisp, clean typography. The interface uses deep, near-black backgrounds as primary surfaces, softened by subtle elevation with faint shadows. Interactive components are intentionally weighty and prominent, contrasting with the overall muted background, while information is delivered with ample whitespace and clear typographic hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#1d1d1d` | `--color-obsidian` | Primary background, card surfaces, dark text |
| White Canvas | `#ffffff` | `--color-white-canvas` | Text on dark backgrounds, active states, button fills for secondary actions, light surface areas |
| Smokey White | `#f6f6f6` | `--color-smokey-white` | Secondary light background sections, light text on dark accents |
| Carbon Black | `#111111` | `--color-carbon-black` | Hero background, prominent dark surfaces |
| Deep Graphite | `#000000` | `--color-deep-graphite` | Headings, strong text, dark navigation elements |
| Silver Mist | `#bfbfbf` | `--color-silver-mist` | Card shadows, muted text, inactive link borders |
| Muted Grey | `#d2d2d2` | `--color-muted-grey` | Subtle borders, secondary text in light areas |
| Dark Shale | `#383838` | `--color-dark-shale` | Helper text on light backgrounds, subtle icons |
| Pale Ash | `#969696` | `--color-pale-ash` | Tertiary text, subtle borders |
| Electric Violet | `#9671ff` | `--color-electric-violet` | Primary action buttons, interactive elements, brand accent |
| Soft Lavender | `#f2eeff` | `--color-soft-lavender` | Subtle background for navigation highlights |
| Twilight Purple | `#ad98fa` | `--color-twilight-purple` | Secondary accent for text and borders |
| Tinted White | `#eae3ff` | `--color-tinted-white` | Soft section background, alternate surface, and quiet card fill. Do not promote it to the primary CTA color |

## Tokens — Typography

### Inter — Primary typeface for all text content including headings, body, navigation, and buttons. Its wide range of weights and sizes supports a detailed typographic hierarchy, from small utilitarian text to large, impactful headlines. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700, 800
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 14px, 16px, 18px, 24px, 30px, 40px, 50px, 56px, 80px
- **Line height:** 0.71, 0.72, 0.73, 0.75, 0.90, 1.00, 1.04, 1.08, 1.14, 1.16, 1.17, 1.18, 1.21, 1.22, 1.25, 1.27, 1.29, 1.38, 1.43, 1.44, 1.50, 1.57, 1.71, 1.73, 1.80, 2.00, 2.14, 2.50
- **Letter spacing:** -0.0060em
- **Role:** Primary typeface for all text content including headings, body, navigation, and buttons. Its wide range of weights and sizes supports a detailed typographic hierarchy, from small utilitarian text to large, impactful headlines.

### IBM Plex Sans — Used for specific heading applications, providing a slightly more structured feel than Inter when needed. · `--font-ibm-plex-sans`
- **Substitute:** Roboto
- **Weights:** 600
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used for specific heading applications, providing a slightly more structured feel than Inter when needed.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.006px | `--text-caption` |
| body | 14px | 1.5 | -0.006px | `--text-body` |
| subheading | 18px | 1.5 | -0.006px | `--text-subheading` |
| heading | 24px | 1.25 | -0.006px | `--text-heading` |
| heading-lg | 40px | 1.18 | -0.006px | `--text-heading-lg` |
| display | 56px | 1.21 | -0.006px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 34 | 34px | `--spacing-34` |
| 43 | 43px | `--spacing-43` |
| 46 | 46px | `--spacing-46` |

### Border Radius

| Element | Value |
|---------|-------|
| hero | 60px |
| cards | 8px |
| badges | 100px |
| images | 4px |
| buttons | 300px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.25) 0px 4px 15px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 43px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Primary Call to Action Button
**Role:** Main interactive button

Filled with Electric Violet (#9671ff), White Canvas (#ffffff) text, 300px border radius, 17px vertical and 46px horizontal padding. This button stands out with its vivid color against dark backgrounds.

### Ghost Navigation Button
**Role:** Navigation and secondary actions

Transparent background, Muted Grey (#d2d2d2) text with a slight opacity (rgba(255,255,255,0.8)), 8px vertical and 10px horizontal padding, 0px border radius. This subtle button blends into the navigation.

### Light Secondary Button
**Role:** Alternate call to action on light backgrounds

Filled with White Canvas (#ffffff), Carbon Black (#111111) text, 300px border radius, 17px vertical and 46px horizontal padding. Offers a solid light-background interaction.

### Dark Content Card
**Role:** Container for content sections

Obsidian (#1d1d1d) background, 8px border radius, no shadow. 34px vertical and 32px horizontal padding. Used for grouping related content on the primary dark canvas.

### Subtle Feature Card
**Role:** Feature or showcase card

Semi-transparent background (rgba(255, 255, 255, 0.05)), 8px border-radius, no shadow. Padding of 26px top, 24px right, 34px bottom, 24px left. Creates a soft, almost frosted effect.

### Elevated Content Card
**Role:** Emphasized content or testimonials

Obsidian (#1d1d1d) background, 4.32px border radius, with a subtle shadow (rgba(0, 0, 0, 0.25) 0px 4px 15px 0px). Padding 15px top, 7px horizontal, 11.5px bottom. This variant indicates slight visual hierarchy.

### Light Badge
**Role:** Categorization or tags

White Canvas (#ffffff) background, Obsidian (#1d1d1d) text, 100px border radius for a pill shape, 16px vertical and 24px horizontal padding. Provides clear, contrasting tags.

## Do's and Don'ts

### Do
- Prioritize Electric Violet (#9671ff) for all primary calls to action to maintain interaction consistency.
- Use Obsidian (#1d1d1d) as the default background for most content sections and cards, creating a consistent dark-mode base.
- Apply White Canvas (#ffffff) for all main body text and crucial information on dark backgrounds, ensuring high legibility.
- Utilize Inter font family with its variable weights for all typographic elements, leveraging its versatility for hierarchy.
- Maintain a 300px border-radius on all primary buttons for a distinct, pill-like appearance.
- Incorporate 8px border-radius for card backgrounds and contained elements using Obsidian (#1d1d1d) or Subtle Feature Card styling.
- Implement -0.0060em letter spacing for Inter font wherever applied, creating a compact and modern text feel.

### Don't
- Avoid using bright, highly saturated colors for large background areas; maintain a dominant dark, muted palette.
- Do not introduce new shadow styles beyond rgba(0, 0, 0, 0.25) 0px 4px 15px 0px, maintaining a consistent, subtle elevation effect.
- Refrain from using thin borders or outlines as primary button styles when a clear call to action is needed; prefer the filled Electric Violet (#9671ff) button.
- Avoid using White Canvas (#ffffff) as a primary background for entire sections, reserving it for text or contained components within darker canvases.
- Do not deviate from the established padding and radius values for specific components like buttons and cards to ensure visual consistency.
- Restrict the use of IBM Plex Sans to specified heading contexts; Inter is the primary typeface for general content.
- Do not overuse Soft Lavender or Tinted White; these are subtle accents, not primary interface colors.

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.25) 0px 4px 15px 0px`

## Imagery

Imagery primarily consists of tight product crops and professional photography of individuals speaking or presenting, often with a product UI overlay. Images are typically contained within cards with 4px or 8px rounded corners, sometimes with a subtle shadow. The overall treatment is realistic and product-focused, serving to showcase the platform's utility with minimal decorative elements. Icons are filled, monochrome, and typically in White Canvas (#ffffff) against dark backgrounds, providing clear functional indicators.

## Layout

The page uses a full-bleed layout for sections, with content mostly constrained to a centered maximum width (implied, not explicit in data but visible in screenshots). The hero section is full-bleed dark with a prominent, centered headline and a person in the foreground. Subsequent sections alternate between dark and light full-width background bands, featuring two-column layouts with text-left/image-right or centered feature stacks. Content blocks are comfortably spaced with ample vertical rhythm, creating a spacious but focused presentation. Navigation is a sticky top bar with a primary action button on the right.

## Agent Prompt Guide

Quick Color Reference:
- text: #ffffff (White Canvas)
- background: #1d1d1d (Obsidian)
- border: #d2d2d2 (Muted Grey)
- accent: #ad98fa (Twilight Purple)
- primary action: #9671ff (filled action)

Example Component Prompts:
- Create a Primary Action Button: #9671ff background, #111111 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Build a feature card: Obsidian (#1d1d1d) background, 8px radius. Heading at 24px Inter weight 600, #ffffff, letter-spacing -0.006em. Body text at 14px Inter weight 400, #ffffff, letter-spacing -0.006em. 34px vertical and 32px horizontal padding.
- Generate a navigation link: Ghost style, #d2d2d2 text, 0px radius, 8px 10px padding. On hover, text color should shift to Twilight Purple (#ad98fa).
- Construct an info badge: White Canvas (#ffffff) background, Obsidian (#1d1d1d) text, 100px radius, 16px 24px padding.

## Similar Brands

- **Linear** — Dark UI with strong purple accents and highly structured, spacious typography.
- **Figma** — Focus on product-centric imagery within UI, subtle card elevation, and a distinct primary action color.
- **Supabase** — Dominant dark theme for the main interface, contrasted with specific vibrant brand colors for calls to action.
- **Vercel** — Professional dark UI with clean typography and a strong emphasis on content hierarchy and clear interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #1d1d1d;
  --color-white-canvas: #ffffff;
  --color-smokey-white: #f6f6f6;
  --color-carbon-black: #111111;
  --color-deep-graphite: #000000;
  --color-silver-mist: #bfbfbf;
  --color-muted-grey: #d2d2d2;
  --color-dark-shale: #383838;
  --color-pale-ash: #969696;
  --color-electric-violet: #9671ff;
  --color-soft-lavender: #f2eeff;
  --color-twilight-purple: #ad98fa;
  --color-tinted-white: #eae3ff;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.006px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.006px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.006px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.006px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.18;
  --tracking-heading-lg: -0.006px;
  --text-display: 56px;
  --leading-display: 1.21;
  --tracking-display: -0.006px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-34: 34px;
  --spacing-43: 43px;
  --spacing-46: 46px;

  /* Layout */
  --section-gap: 43px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16.128px;
  --radius-2xl-2: 20px;
  --radius-3xl: 29.952px;
  --radius-3xl-2: 33.984px;
  --radius-3xl-3: 36px;
  --radius-full: 60px;
  --radius-full-2: 100px;
  --radius-full-3: 300px;

  /* Named Radii */
  --radius-hero: 60px;
  --radius-cards: 8px;
  --radius-badges: 100px;
  --radius-images: 4px;
  --radius-buttons: 300px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 4px 15px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #1d1d1d;
  --color-white-canvas: #ffffff;
  --color-smokey-white: #f6f6f6;
  --color-carbon-black: #111111;
  --color-deep-graphite: #000000;
  --color-silver-mist: #bfbfbf;
  --color-muted-grey: #d2d2d2;
  --color-dark-shale: #383838;
  --color-pale-ash: #969696;
  --color-electric-violet: #9671ff;
  --color-soft-lavender: #f2eeff;
  --color-twilight-purple: #ad98fa;
  --color-tinted-white: #eae3ff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.006px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.006px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.006px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.006px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.18;
  --tracking-heading-lg: -0.006px;
  --text-display: 56px;
  --leading-display: 1.21;
  --tracking-display: -0.006px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-34: 34px;
  --spacing-43: 43px;
  --spacing-46: 46px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16.128px;
  --radius-2xl-2: 20px;
  --radius-3xl: 29.952px;
  --radius-3xl-2: 33.984px;
  --radius-3xl-3: 36px;
  --radius-full: 60px;
  --radius-full-2: 100px;
  --radius-full-3: 300px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.25) 0px 4px 15px 0px;
}
```
