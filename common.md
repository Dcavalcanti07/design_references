# Common — Style Reference
> Whiteboard with digital neon accents

**Theme:** light

Common presents a clean, productivity-focused interface built on a nearly achromatic palette.  A playful gradient and two vibrant accent colors punctuate the UI, creating a dynamic contrast against the muted background. Components are lightweight and low-to-no shadow, emphasizing flat surfaces and a sense of speed. Typography is structured and compact, supporting a dense information display without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight | `#000000` | `--color-midnight` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Page backgrounds, card surfaces, button backgrounds, input fields, providing a clean canvas |
| Silver Pine | `#e0dfe1` | `--color-silver-pine` | Subtle borders for input fields and other UI elements, creating soft separation |
| Charcoal Slate | `#282729` | `--color-charcoal-slate` | Headings, prominent text, and darker accents for icons, creating depth against lighter neutrals |
| Frost Gray | `#c1c0c2` | `--color-frost-gray` | Hairline card borders, providing a light visual containment without harsh lines |
| Ash Cloud | `#a09da1` | `--color-ash-cloud` | Muted icon fills and navigation item borders, indicating secondary importance |
| Dark Granite | `#3d3a3e` | `--color-dark-granite` | Filled button backgrounds for primary actions, providing a strong interactive target |
| Deep Ink | `#141315` | `--color-deep-ink` | Very dark text or borders, used sparingly for emphasis |
| Stone Dust | `#757575` | `--color-stone-dust` | Muted icon fills and secondary text |
| Gallery White | `#f0eff0` | `--color-gallery-white` | Subtle background for certain body sections, providing a slight elevation from the pure white canvas |
| Sky Blue Spark | `#338fff` | `--color-sky-blue-spark` | Link text, icon accents, and outlined interactive borders, injecting a crisp, functional color |
| Electric Violet | `#7a33ff` | `--color-electric-violet` | Link text, icon fill, and outlined interactive borders, providing a secondary vibrant accent |
| Spectrum Burst | `linear-gradient(90deg, rgb(0, 121, 204), rgb(5, 15, 163) 27%, rgb(255, 16, 0) 59%, rgb(255, 16, 0))` | `--color-spectrum-burst` | Used as a vibrant, multi-hued decorative element to highlight key sections or buttons |
| Soft Spectrum Burst | `linear-gradient(90deg, rgba(255, 31, 0, 0.3), rgba(255, 128, 215, 0.3), rgba(0, 121, 204, 0.3))` | `--color-soft-spectrum-burst` | Translucent background overlay, adding a subtle touch of brand color without obscuring content |

## Tokens — Typography

### NeueHaasUnica — Primary UI font for body text, form inputs, buttons, navigation, and many interactive elements. Its precise tracking and numerical features support a compact, data-rich display. · `--font-neuehaasunica`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 24px, 32px, 36px
- **Line height:** 1.00, 1.15, 1.43, 1.50, 1.71
- **Letter spacing:** 0.0100em at 14px, 0.0200em at 16px
- **OpenType features:** `"lnum" on, "tnum" on`
- **Role:** Primary UI font for body text, form inputs, buttons, navigation, and many interactive elements. Its precise tracking and numerical features support a compact, data-rich display.

### Silka — Used for larger headings and distinct sections to provide an alternative geometric feel. Its heavier weights offer a clear hierarchy. · `--font-silka`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 20px, 24px, 28px
- **Line height:** 1.17, 1.40, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Used for larger headings and distinct sections to provide an alternative geometric feel. Its heavier weights offer a clear hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.71 | 0.14px | `--text-caption` |
| body | 16px | 1.5 | 0.32px | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.43 | — | `--text-heading-sm` |
| heading | 28px | 1.17 | — | `--text-heading` |
| heading-lg | 32px | 1.15 | — | `--text-heading-lg` |
| display | 36px | 1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 5px |
| inputs | 6px |
| buttons | 6px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(40, 39, 41, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 24px
- **Card padding:** 8px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Action

Solid Dark Granite (#3d3a3e) background with Midnight (#000000) text (or white for contrast). 6px border-radius, with 4px vertical padding and 16px horizontal padding. Example: 'Sign in' button.

### Ghost Button
**Role:** Action

Transparent background, Midnight (#000000) border, and Midnight (#000000) text. 6px border-radius, with 4px vertical padding and 16px horizontal padding. Example: 'About' button.

### Monochrome Card
**Role:** Container

Snowdrift (#ffffff) background, 5px border-radius, and a subtle drop shadow rgba(40, 39, 41, 0.05) 0px 1px 2px 0px. Internal content padding is 8px. Used for displaying individual items or grouped content.

### Outline Card
**Role:** Container

Snowdrift (#ffffff) background, 4px border-radius, no shadow, with 0px internal padding. Used for high-density content areas where visual layering is less important.

### Transparent Card
**Role:** Container

Transparent background, no border-radius, no shadow. 8px vertical padding, 0px horizontal. Used for sections that seamlessly integrate into the background while maintaining logical grouping.

### Text Input Field
**Role:** Input

Snowdrift (#ffffff) background, Silver Pine (#e0dfe1) border. 6px border-radius, Charcoal Slate (#282729) text, 10px vertical padding and 12px left padding. Placeholder text is lighter.

### Gradient CTA Button
**Role:** Action

Spectrum Burst gradient background (linear-gradient). Snowdrift (#ffffff) text. Used for prominent calls to action like 'Launch Token'.

### Small Interactive Card
**Role:** Navigation/Call-to-action

Snowdrift (#ffffff) background, 6px border-radius. A Charcoal Slate (#282729) border on hover. Padding is 8px. Used for compact navigation items like 'Create Your Community'.

## Do's and Don'ts

### Do
- Use Midnight (#000000) for all primary text and strong borders to ensure high contrast and readability.
- Apply Snowdrift (#ffffff) as the default background for pages and main content cards.
- Utilize Dark Granite (#3d3a3e) for filled primary action buttons with 6px border-radius.
- Employ Sky Blue Spark (#338fff) or Electric Violet (#7a33ff) for link text and small interactive accents.
- Maintain a compact visual density with default element spacing of 8px and card padding of 8px.
- Apply a consistent 6px border-radius for buttons, inputs, and most interactive cards.
- Use the Spectrum Burst gradient for high-priority, visually distinct calls-to-action or hero components.

### Don't
- Do not use highly saturated colors for large background areas; limit them to accents and interactive states.
- Avoid deep, heavy shadows; use the rgba(40, 39, 41, 0.05) 0px 1px 2px 0px shadow sparingly for subtle elevation on cards.
- Do not vary border-radius excessively; stick to 6px for most common interactive elements and 5px for cards.
- Avoid using multiple different shades of gray for primary text; default to Midnight (#000000) or Charcoal Slate (#282729).
- Do not introduce new font families beyond NeueHaasUnica and Silka.
- Refrain from using complex, decorative gradients outside of the defined Spectrum Burst style.
- Do not create dense layouts without clear visual breakpoints; prioritize consistent spacing and separation.

## Elevation

- **Monochrome Card:** `rgba(40, 39, 41, 0.05) 0px 1px 2px 0px`

## Imagery

The site uses a 'no imagery, pure UI' approach with a strong emphasis on clean interface elements. Icons, where present, are monolinear and typically filled with neutral colors like Stone Dust (#757575) or Charcoal Slate (#282729), or occasionally accented with Sky Blue Spark (#338fff) or Electric Violet (#7a33ff). The visual density is higher on UI elements than on decorative graphics. Graphics are minimalist and functional, such as the two-dot pink/blue motif, conveying information or status rather than atmosphere.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section is characterized by a prominent background element, potentially a gradient or a large card. Sections follow a consistent vertical rhythm, often delineated by distinct cards or transparent containers. Content is arranged in stacked text blocks or simple horizontal arrangements, like a text input field followed by action buttons. Navigation includes a sticky top bar and a collapsed left sidebar.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #e0dfe1
accent: #338fff
primary action: #3d3a3e (filled action)

Example Component Prompts:
1. Create a neutral card: Snowdrift (#ffffff) background, 5px border-radius, rgba(40, 39, 41, 0.05) 0px 1px 2px 0px shadow, 8px padding. Headline text 'Trending' in Charcoal Slate (#282729) Silka weight 700 at 24px, no letter-spacing. Link 'Tokens →' in Sky Blue Spark (#338fff) NeueHaasUnica weight 400 at 16px, 0.0200em letter-spacing.
2. Create a primary action button: Dark Granite (#3d3a3e) background, Midnight (#000000) text NeueHaasUnica weight 400 at 16px, 6px border-radius, 4px vertical padding, 16px horizontal padding. Example text: 'Sign in'.
3. Create an input field: Snowdrift (#ffffff) background, Silver Pine (#e0dfe1) border, 6px border-radius, 10px vertical padding, 12px left padding. Placeholder text in Stone Dust (#757575) NeueHaasUnica weight 400 at 16px. Example placeholder: 'Type your idea...'.
4. Create a Primary Action Button: #3d3a3e background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Linear** — Monochromatic base palette with a single, vibrant brand accent used for highlights and interactive elements.
- **Figma** — Clean, predominantly white canvas with subtle card shadows and a compact, functional typography system.
- **Tailwind UI** — Systematic use of neutral grays for surfaces, text, and borders, supporting varied content without visual noise.
- **Vercel** — Minimalist UI, focus on clear information hierarchy, and restrained use of color for functional emphasis.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight: #000000;
  --color-snowdrift: #ffffff;
  --color-silver-pine: #e0dfe1;
  --color-charcoal-slate: #282729;
  --color-frost-gray: #c1c0c2;
  --color-ash-cloud: #a09da1;
  --color-dark-granite: #3d3a3e;
  --color-deep-ink: #141315;
  --color-stone-dust: #757575;
  --color-gallery-white: #f0eff0;
  --color-sky-blue-spark: #338fff;
  --color-electric-violet: #7a33ff;
  --color-spectrum-burst: #0079cc;
  --gradient-spectrum-burst: linear-gradient(90deg, rgb(0, 121, 204), rgb(5, 15, 163) 27%, rgb(255, 16, 0) 59%, rgb(255, 16, 0));
  --color-soft-spectrum-burst: #ff1f00;
  --gradient-soft-spectrum-burst: linear-gradient(90deg, rgba(255, 31, 0, 0.3), rgba(255, 128, 215, 0.3), rgba(0, 121, 204, 0.3));

  /* Typography — Font Families */
  --font-neuehaasunica: 'NeueHaasUnica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-silka: 'Silka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.71;
  --tracking-caption: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.43;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 36px;
  --leading-display: 1;

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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 8px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-full: 80px;

  /* Named Radii */
  --radius-cards: 5px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-subtle: rgba(40, 39, 41, 0.05) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight: #000000;
  --color-snowdrift: #ffffff;
  --color-silver-pine: #e0dfe1;
  --color-charcoal-slate: #282729;
  --color-frost-gray: #c1c0c2;
  --color-ash-cloud: #a09da1;
  --color-dark-granite: #3d3a3e;
  --color-deep-ink: #141315;
  --color-stone-dust: #757575;
  --color-gallery-white: #f0eff0;
  --color-sky-blue-spark: #338fff;
  --color-electric-violet: #7a33ff;
  --color-spectrum-burst: #0079cc;
  --color-soft-spectrum-burst: #ff1f00;

  /* Typography */
  --font-neuehaasunica: 'NeueHaasUnica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-silka: 'Silka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.71;
  --tracking-caption: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.43;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 36px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-full: 80px;

  /* Shadows */
  --shadow-subtle: rgba(40, 39, 41, 0.05) 0px 1px 2px 0px;
}
```
