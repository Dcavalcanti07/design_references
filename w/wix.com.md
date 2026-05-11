# wix.com — Style Reference
> Animated digital canvas – an interactive, slightly playful yet authoritative workspace.

**Theme:** light

Wix.com's system is a canvas of light, subtly animated surfaces, where interactive elements pulse with a vivid blue. The visual style balances a strong, opinionated display typography with more conventional body text for clarity. Cards and interactive components feature generous rounded corners, giving the interface a friendly, approachable feel, while the dominant white background is punctuated by soft, pastel-toned background fills and gradients.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, icon fill, borders for ghost components, neutral action outlines. Serves as a grounding contrast against the light canvas |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, default card surfaces, primary button text, input backgrounds – the dominant base layer |
| Cloud Gray | `#f1f5f9` | `--color-cloud-gray` | Subtle background surfaces for secondary sections and elevated cards, providing a soft visual break from Canvas White |
| Silver Mist | `#d0d0d0` | `--color-silver-mist` | Divider lines, subtle borders, disabled states, and muted interface elements |
| Steel Blue | `#1c1d21` | `--color-steel-blue` | Secondary text, subheadings, providing a slightly softer yet highly readable alternative to Midnight Ink |
| Sky Blue | `#166aea` | `--color-sky-blue` | Primary action buttons, prominent icons, focus indicators – the main interactive accent color |
| Deep Violet | `#101585` | `--color-deep-violet` | Decorative accents in headings and backgrounds, contributing to the brand's creative and digital essence |
| Lime Zest | `#dff994` | `--color-lime-zest` | Decorative fills and borders, providing a vibrant, energetic visual counterpoint |
| Twilight Indigo | `linear-gradient(106deg, rgb(44, 52, 175) 0%, rgba(206, 255, 126, 0.75) 50%, rgb(44, 52, 175) 100%)` | `--color-twilight-indigo` | Accent text in headlines, adding depth and a premium feel; Dynamic background for hero sections, communicating energy and innovation |
| Ocean Teal | `#024051` | `--color-ocean-teal` | Background for specific card types, indicating a distinct content category |
| Pale Sage | `#d1e6d1` | `--color-pale-sage` | Subtle background for specific card types, a gentle, organic accent |
| Terracotta | `#863a29` | `--color-terracotta` | Distinct background for specific card types, providing warmth and earthiness |
| Amethyst | `#bea3e7` | `--color-amethyst` | Background for specific card types, a soft, creative violet hue |
| Cerise Glow | `#ffc2fe` | `--color-cerise-glow` | Background for specific card types, a bright, playful pink accent |
| Sunflower Yellow | `#fdf4a1` | `--color-sunflower-yellow` | Decorative borders and text accents, adding a cheerful, optimistic touch |
| Info Blue | `#538ab6` | `--color-info-blue` | Blue state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Sky Gradient | `linear-gradient(0deg, rgb(189, 197, 236) 0%, rgba(255, 255, 255, 0) 100%)` | `--color-sky-gradient` | Subtle background for hero sections or elevated areas, creating a soft, ethereal atmosphere |
| Deep Sea Gradient | `linear-gradient(rgb(9, 91, 113) 0%, rgb(1, 64, 81) 97.0737%)` | `--color-deep-sea-gradient` | Background for informational or immersive content blocks |
| Lavender Gradient | `linear-gradient(rgb(143, 163, 255) 0%, rgb(189, 201, 255) 98.2021%)` | `--color-lavender-gradient` | Background for feature highlights, softening the UI with a playful tone |

## Tokens — Typography

### madefor-display — Headlines and prominent display text. Its range of oversized sizes and tight tracking creates a bold, modern voice. · `--font-madefor-display`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 10px, 13px, 14px, 16px, 21px, 24px, 31px, 48px, 82px, 89px, 104px, 184px
- **Line height:** 0.85, 1.00, 1.10, 1.20, 1.30, 1.40, 1.48, 1.50, 1.60
- **Letter spacing:** -0.03, -0.02, -0.01
- **Role:** Headlines and prominent display text. Its range of oversized sizes and tight tracking creates a bold, modern voice.

### wix-madefor-display-v2 — Main display headings, offering a slightly refined take on the primary display font with additional weight options. · `--font-wix-madefor-display-v2`
- **Substitute:** Arial
- **Weights:** 400, 500
- **Sizes:** 20px, 21px, 53px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** normal
- **Role:** Main display headings, offering a slightly refined take on the primary display font with additional weight options.

### madefor-text — Body text and functional interface elements, ensuring readability at smaller sizes with minimal tracking. · `--font-madefor-text`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 10px, 13px, 14px, 15px, 16px, 18px, 21px, 25px
- **Line height:** 1.00, 1.20, 1.29, 1.30, 1.50, 1.60, 1.71
- **Letter spacing:** -0.01
- **Role:** Body text and functional interface elements, ensuring readability at smaller sizes with minimal tracking.

### wix-madefor-text-v2 — Supplementary body text and longer-form content, optimized for reading comfort. · `--font-wix-madefor-text-v2`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 15px, 21px
- **Line height:** 1.30, 1.35, 1.50
- **Letter spacing:** normal
- **Role:** Supplementary body text and longer-form content, optimized for reading comfort.

### madefor-text-mediumbold — Highlighting key information within body text and navigation elements. The subtle weight increase provides emphasis without shouting. · `--font-madefor-text-mediumbold`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 21px, 23px, 24px
- **Line height:** 1.10, 1.20, 1.30, 1.50, 1.60, 1.71
- **Letter spacing:** -0.01
- **Role:** Highlighting key information within body text and navigation elements. The subtle weight increase provides emphasis without shouting.

### madefor-text-bold — Emphasized body text details, providing direct highlights. · `--font-madefor-text-bold`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.60
- **Letter spacing:** normal
- **Role:** Emphasized body text details, providing direct highlights.

### Arial — System fallback and micro-text, used for elements like timestamps or metadata where a simple, universal font is preferred. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 10px, 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback and micro-text, used for elements like timestamps or metadata where a simple, universal font is preferred.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| subheading | 21px | 1.2 | -0.21px | `--text-subheading` |
| heading-sm | 31px | 1.3 | — | `--text-heading-sm` |
| heading | 48px | 1.2 | -1.44px | `--text-heading` |
| heading-lg | 82px | 1.1 | -1.64px | `--text-heading-lg` |
| display | 184px | 0.85 | -5.52px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 68 | 68px | `--spacing-68` |
| 84 | 84px | `--spacing-84` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 50px |
| cards | 20px |
| images | 20px |
| inputs | 999px |
| buttons | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px -1px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 81px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Call to action, primary interaction

Filled with Sky Blue (#166aea), white text (#ffffff), and a 50px border-radius. Padding is 0px top/bottom, 12px horizontal from text edges. Uses madefor-display-v2 at 16px.

### Ghost Button
**Role:** Secondary action, navigation

Transparent background, Midnight Ink (#000000) text, no border or padding visible in data. Uses Arial at 13px.

### Black Rounded Button
**Role:** Alternative call to action, often accentuating a dark background.

Filled with Midnight Ink (#000000), white text (#ffffff), and a 50px border-radius. Padding is 0px top/bottom, 10px right, 36px left. Uses madefor-display at 16px.

### Square Corner Card
**Role:** Content container, information display

Transparent background, no shadow, 0px border-radius. No explicit padding detected by default, content dictates spacing.

### Rounded Corner Card
**Role:** Elevated content container, featured information

Transparent background, no shadow, 20px border-radius. No explicit padding detected by default. Often features soft background fills like Cloud Gray (#f1f5f9) or accent colors.

### Shadowed Navigation Bar
**Role:** Global navigation header

White background, with a subtle dark shadow: `rgba(0, 0, 0, 0.1) 0px -1px 0px 0px`. Contains navigation links and primary actions. Heights vary.

### Rounded Input Field
**Role:** User data entry

White background (#ffffff), Midnight Ink (#000000) text, Info Blue (#538ab6) border on focus. 999px border-radius creates a pill shape. Padding is 3px top/bottom.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary backgrounds and Cloud Gray (#f1f5f9) for secondary content sections, ensuring a bright, spacious feel.
- Use Sky Blue (#166aea) exclusively for primary interactive elements, reserving it for clear calls to action and active states.
- Apply 50px border-radius to all buttons and tags, creating a consistent, friendly pill shape.
- Employ madefor-display for all headlines, utilizing its generous sizes and tight letter-spacing for impact.
- Maintain a comfortable rhythm with an 81px section gap, creating clear visual separation between content blocks.
- Use subtle borders and dividers with Silver Mist (#d0d0d0) to structure content without adding visual weight.
- Infuse dynamism into hero sections with gradient backgrounds like Sky Gradient (#bdc5ec) or Electric Gradient (#2c34af) for visual interest.

### Don't
- Avoid using Midnight Ink (#000000) as a solid background fill for large sections; its primary role is text and sparse borders.
- Refrain from using Sky Blue (#166aea) for purely decorative purposes; it's reserved for functional interactions.
- Do not deviate from the established 20px radius for cards and images, as it's a signature element of the design language.
- Avoid excessive letter-spacing on display fonts; madefor-display benefits from its naturally tight tracking.
- Do not introduce strong, opaque shadows for elevation, as the system relies on subtle, tinted shadows or no shadows at all for depth.
- Do not use generic system fonts for branding or display text, as the custom madefor family is key to visual identity.
- Avoid overly complex nested layouts; prefer clear sectioning with alternating backgrounds and distinct component areas.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, primary stage for content. |
| 1 | Base Card | `#f1f5f9` | Background for secondary content areas or simple cards. |
| 2 | Decorative Card | `#dff994` | Specific card backgrounds using brand or accent colors (e.g., Lime Zest, Pale Sage, Amethyst). |

## Elevation

- **Navigation Bar:** `rgba(0, 0, 0, 0.1) 0px -1px 0px 0px`

## Imagery

The site predominantly uses product screenshots and abstract graphics. Product screenshots are typically contained within cards, often with rounded corners (20px radius) and sometimes featuring a subtle drop-shadow (rgba(50, 48, 126, 0.28) 5.04px 6.48px 15.84px) that visually lifts them from the surface. Illustrations are geometric and often leverage brand accent colors like Lime Zest and Deep Violet. Icons are typically filled with Midnight Ink or Sky Blue, sometimes outlined. Imagery plays an explanatory and product-showcase role, rather than purely decorative, creating a moderately image-heavy but content-dominant density across sections.

## Layout

The page primarily uses a max-width contained model for content, though the hero sections often go full-bleed with gradients or background patterns. The hero pattern frequently features a centered headline over a background that can be either white, a soft gradient, or a dynamic electric gradient. Sections alternate between standard white backgrounds and Cloud Gray (#f1f5f9) bands, creating a clear vertical rhythm. Content arrangement frequently uses a 2-column text+image pattern or centered stacks, with features often presented in multi-column card grids. Navigation is a sticky top bar with global links and primary actions, retaining visibility while scrolling.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #d0d0d0
accent: #dff994
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Cloud Gray (#f1f5f9) background, 20px border-radius, with an Ocean Teal (#024051) accent bar at the top (use as background color). Place a subheading 'Intuitive Design Tools' using madefor-text-mediumbold at 21px, weight 400, in Steel Blue (#1c1d21). Follow with body text in madefor-text at 16px, weight 400, in Midnight Ink (#000000).
3. Generate a form section with a Rounded Input Field for 'Email Address'. The input should have a white background (#ffffff), Midnight Ink (#000000) text at 16px madefor-text, 999px border-radius, and an Info Blue (#538ab6) border on focus. Below the input, add a Ghost Button 'Learn More' using Midnight Ink (#000000) for text.

## Similar Brands

- **Figma** — Clear, bright interface with prominent blue accents for interactive elements and a focus on clean typography.
- **Webflow** — Heavy reliance on custom display fonts for headlines, light canvas, and strong, clear CTA buttons.
- **Notion** — Predominantly light theme, functional use of color for status/tags, and an emphasis on approachable, minimalist components.
- **Canva** — Playful use of gradients and vibrant accent colors against a mostly white background, with friendly rounded corners.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f1f5f9;
  --color-silver-mist: #d0d0d0;
  --color-steel-blue: #1c1d21;
  --color-sky-blue: #166aea;
  --color-deep-violet: #101585;
  --color-lime-zest: #dff994;
  --color-twilight-indigo: #2c34af;
  --gradient-twilight-indigo: linear-gradient(106deg, rgb(44, 52, 175) 0%, rgba(206, 255, 126, 0.75) 50%, rgb(44, 52, 175) 100%);
  --color-ocean-teal: #024051;
  --color-pale-sage: #d1e6d1;
  --color-terracotta: #863a29;
  --color-amethyst: #bea3e7;
  --color-cerise-glow: #ffc2fe;
  --color-sunflower-yellow: #fdf4a1;
  --color-info-blue: #538ab6;
  --color-sky-gradient: #bdc5ec;
  --gradient-sky-gradient: linear-gradient(0deg, rgb(189, 197, 236) 0%, rgba(255, 255, 255, 0) 100%);
  --color-deep-sea-gradient: #095b71;
  --gradient-deep-sea-gradient: linear-gradient(rgb(9, 91, 113) 0%, rgb(1, 64, 81) 97.0737%);
  --color-lavender-gradient: #8f69ff;
  --gradient-lavender-gradient: linear-gradient(rgb(143, 163, 255) 0%, rgb(189, 201, 255) 98.2021%);

  /* Typography — Font Families */
  --font-madefor-display: 'madefor-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-display-v2: 'wix-madefor-display-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text: 'madefor-text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-text-v2: 'wix-madefor-text-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text-mediumbold: 'madefor-text-mediumbold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text-bold: 'madefor-text-bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.21px;
  --text-heading-sm: 31px;
  --leading-heading-sm: 1.3;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -1.44px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.64px;
  --text-display: 184px;
  --leading-display: 0.85;
  --tracking-display: -5.52px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-68: 68px;
  --spacing-84: 84px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 81px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.90625px;
  --radius-lg-2: 11px;
  --radius-xl: 14.4px;
  --radius-2xl: 20px;
  --radius-2xl-2: 22.2656px;
  --radius-3xl: 24.4922px;
  --radius-3xl-2: 29.6875px;
  --radius-3xl-3: 33px;
  --radius-3xl-4: 40px;
  --radius-full: 50px;
  --radius-full-2: 59.375px;
  --radius-full-3: 89.0625px;
  --radius-full-4: 99px;
  --radius-full-5: 667.969px;
  --radius-full-6: 999px;

  /* Named Radii */
  --radius-tags: 50px;
  --radius-cards: 20px;
  --radius-images: 20px;
  --radius-inputs: 999px;
  --radius-buttons: 50px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px -1px 0px 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-base-card: #f1f5f9;
  --surface-decorative-card: #dff994;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f1f5f9;
  --color-silver-mist: #d0d0d0;
  --color-steel-blue: #1c1d21;
  --color-sky-blue: #166aea;
  --color-deep-violet: #101585;
  --color-lime-zest: #dff994;
  --color-twilight-indigo: #2c34af;
  --color-ocean-teal: #024051;
  --color-pale-sage: #d1e6d1;
  --color-terracotta: #863a29;
  --color-amethyst: #bea3e7;
  --color-cerise-glow: #ffc2fe;
  --color-sunflower-yellow: #fdf4a1;
  --color-info-blue: #538ab6;
  --color-sky-gradient: #bdc5ec;
  --color-deep-sea-gradient: #095b71;
  --color-lavender-gradient: #8f69ff;

  /* Typography */
  --font-madefor-display: 'madefor-display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-display-v2: 'wix-madefor-display-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text: 'madefor-text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-text-v2: 'wix-madefor-text-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text-mediumbold: 'madefor-text-mediumbold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text-bold: 'madefor-text-bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.21px;
  --text-heading-sm: 31px;
  --leading-heading-sm: 1.3;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -1.44px;
  --text-heading-lg: 82px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.64px;
  --text-display: 184px;
  --leading-display: 0.85;
  --tracking-display: -5.52px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-68: 68px;
  --spacing-84: 84px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.90625px;
  --radius-lg-2: 11px;
  --radius-xl: 14.4px;
  --radius-2xl: 20px;
  --radius-2xl-2: 22.2656px;
  --radius-3xl: 24.4922px;
  --radius-3xl-2: 29.6875px;
  --radius-3xl-3: 33px;
  --radius-3xl-4: 40px;
  --radius-full: 50px;
  --radius-full-2: 59.375px;
  --radius-full-3: 89.0625px;
  --radius-full-4: 99px;
  --radius-full-5: 667.969px;
  --radius-full-6: 999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px -1px 0px 0px;
}
```
