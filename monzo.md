# Monzo — Style Reference
> Hot Coral Digital Craftsmanship — a meticulously crafted digital experience with vibrant accents.

**Theme:** light

Monzo's visual style evokes 'Digital Craftsmanship,' where vibrant and professional is achieved through a carefully balanced suite of design choices. The core is a confident yet approachable dark charcoal text against a pristine paper-white background, creating high contrast. This is punctuated by a singular, vivid hot coral for primary calls-to-action and brand accents, preventing the design from feeling sterile. Signature choices like generously rounded 'pill' buttons and soft shadows on cards hint at a user-friendly, empathetic digital experience, while strict adherence to a clean, spacious layout grounds the design in reliability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#091723` | `--color-midnight-charcoal` | Primary text, prominent UI elements, button backgrounds – establishes a deep, authoritative base against light surfaces. |
| Snow White | `#ffffff` | `--color-snow-white` | Primary background for cards, buttons, and sections – provides a clean, expansive canvas for content. |
| Mist Gray | `#f2f8f3` | `--color-mist-gray` | Dominant page background, secondary card backgrounds – offers a subtle off-white that prevents harshness and provides relief from pure white. |
| Slate Blue | `#112231` | `--color-slate-blue` | Accent backgrounds and specific UI elements – a slightly cooler, darker neutral that adds depth. |
| Silver Dust | `#e3ebe4` | `--color-silver-dust` | Subtle UI backgrounds, dividers – a very light gray providing minimal contrast for separating elements. |
| Steel Gray | `#6b747b` | `--color-steel-gray` | Secondary text, muted links, icons – provides readability for supporting information without competing with primary headings. |
| Ash Gray | `#b5b9bd` | `--color-ash-gray` | Subtle button backgrounds, inactive states – a lighter neutral for less prominent interactive elements. |
| Hot Coral | `#ff4f40` | `--color-hot-coral` | Primary calls-to-action, brand accents, interactive elements – injects energy and guides user attention as a distinct brand identifier. |
| Muted Olive | `#3b4c54` | `--color-muted-olive` | Tertiary button backgrounds with low prominence – a desaturated, cool color for background functions. |
| Graphite Stroke | `#75817` | `--color-graphite-stroke` | Iconography and borders – provides definition to visual elements without being stark black. |

## Tokens — Typography

### MonzoSansText — Body copy, links, navigation, buttons, and general UI text. The uniform letter spacing contributes to a consistent, crisp text block, even at smaller sizes. · `--font-monzosanstext`
- **Substitute:** Inter, Arial
- **Weights:** 400, 600, 700
- **Sizes:** 13px, 16px, 20px, 24px, 32px, 36px
- **Line height:** 0.81, 1.15, 1.38, 1.40, 1.50
- **Letter spacing:** -0.0500em
- **Role:** Body copy, links, navigation, buttons, and general UI text. The uniform letter spacing contributes to a consistent, crisp text block, even at smaller sizes.

### MonzoSansDisplay — Headlines and prominent display text. Its natural letter spacing ensures headings hold presence without feeling overly tight. · `--font-monzosansdisplay`
- **Substitute:** Inter, Arial
- **Weights:** 600, 700, 800
- **Sizes:** 16px, 20px, 25px, 31px, 39px, 44px, 49px, 61px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** normal
- **Role:** Headlines and prominent display text. Its natural letter spacing ensures headings hold presence without feeling overly tight.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | -0.65px | `--text-caption` |
| body-sm | 16px | 1.4 | -0.8px | `--text-body-sm` |
| body | 20px | 1.38 | -1px | `--text-body` |
| subheading | 24px | 1.4 | — | `--text-subheading` |
| heading-sm | 32px | 1.15 | -1.6px | `--text-heading-sm` |
| heading | 36px | 1.15 | -1.8px | `--text-heading` |
| heading-lg | 49px | 1.2 | — | `--text-heading-lg` |
| display | 61px | 1 | — | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| badges | 4px |
| buttons | 500px |
| general | 64px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 0px 10px 0px` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 30px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Call to action

Solid 'Midnight Charcoal' (#091723) background with 'Snow White' (#ffffff) text, using a 500px border-radius for a pill shape. Padding is 12px vertical, 24px horizontal. Text is MonzoSansText weight 400.

### Primary Outlined Button
**Role:** Secondary action or ghost button

Transparent background with 'Midnight Charcoal' (#091723) text and border. No border-radius, resembling a link. No padding.

### Ghost Button with Icon
**Role:** Navigation or interactive element with subtle styling

Transparent background with 'Steel Gray' (rgba(9, 23, 35, 0.6)) text and border. Uses a 24px border-radius, with 20px padding on all sides. Text is MonzoSansText weight 400.

### Light Mode Card
**Role:** Information container, features

Background 'Snow White' (#ffffff), with a 32px border-radius and a subtle shadow (rgba(0, 0, 0, 0.1) 0px 0px 10px 0px). Inner padding is 30px.

### Dark Mode Card
**Role:** Information container, features

Background 'Slate Blue' (#112231), with a 32px border-radius and a subtle shadow (rgba(0, 0, 0, 0.1) 0px 0px 10px 0px). Inner padding is 30px.

### Section Background Card
**Role:** Hero or large content block backgrounds

Background 'Mist Gray' (#f2f8f3), with a large 64px border-radius and no shadow. Generous vertical padding of 128px.

### Status Badge
**Role:** Informational tag

Background 'Mist Gray' (#f2f8f3) with 'Steel Gray' (rgba(9, 23, 35, 0.6)) text. Rounded 4px corners, 4px vertical, 12px horizontal padding. Text is MonzoSansText weight 400.

## Do's and Don'ts

### Do
- Prioritize 'Midnight Charcoal' (#091723) for all primary text and calls-to-action against light backgrounds to ensure AAA contrast.
- Utilize 'Hot Coral' (#ff4f40) exclusively for primary interactive states or brand-specific elements, reserving its impact.
- Implement 500px radius for all primary buttons and interactive pill-shaped elements.
- Apply 'Mist Gray' (#f2f8f3) as the default page background and use 'Snow White' (#ffffff) for distinct content blocks or cards.
- Maintain a clear visual hierarchy by employing MonzoSansDisplay for headlines and MonzoSansText for all body copy and UI elements.
- Ensure all card elements use a 32px border-radius, accompanied by rgba(0, 0, 0, 0.1) 0px 0px 10px 0px shadow for subtle depth.
- Use 24px for all standard element and grid gaps to maintain consistent breathing room between components.

### Don't
- Avoid using multiple chromatic colors; 'Hot Coral' (#ff4f40) is the dominant accent hue.
- Do not deviate from the specified typography sizes, line heights, or letter spacings to preserve brand readability and scale.
- Refrain from using hard-edged borders or square elements where a rounded alternative exists, especially for interactive components.
- Do not introduce complex gradient backgrounds; the system relies on solid color blocks and subtle surface variations.
- Avoid excessive shadow layers or high-contrast shadows; only use the specified light shadow for cards.
- Do not use dark backgrounds without contrasting light text; maintain high readability scores for all content.
- Resist using grayscale or desaturated versions of 'Hot Coral' for functional interactions; use it vividly or not at all.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Mist Gray | `#f2f8f3` | Page background, foundational canvas |
| 1 | Snow White | `#ffffff` | Primary content areas, default cards |
| 2 | Slate Blue | `#112231` | Elevated cards or specific dark sections |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.1) 0px 0px 10px 0px`

## Imagery

The visual language combines expressive full-bleed photography with clean, contained product shots and illustrative elements. Photography features human elements but also focuses on the product (the card). Product imagery is tightly cropped, often showcasing the Hot Coral card against dark, slightly blurred backgrounds. Icons are monoline, 'Graphite Stroke' colored outlines with a moderate stroke weight, used for navigation and feature differentiation. The overall density leans towards balanced, using imagery to establish atmosphere and convey product function without overwhelming text content.

## Layout

The page primarily employs a max-width contained layout, centering content within a 'Mist Gray' (#f2f8f3) canvas, likely around 1200px. The hero section is full-bleed, featuring a dark atmospheric image with central overlay content. Sections maintain a consistent vertical rhythm, primarily defined by the 'sectionGap' of 64px. Content arrangement varies: some sections feature a centered stack, while others use a flexible two-column layout for text and image pairings. There is a clear use of card-based grids for features and information grouping, leveraging the 'Snow White' (#ffffff) and 'Slate Blue' (#112231) surfaces. The navigation is a sticky top bar with clearly segmented 'Personal' and 'Business' options.

## Agent Prompt Guide

### Quick Color Reference
- Primary Text: #091723
- Background: #f2f8f3
- CTA Button: #ff4f40
- Card Background: #ffffff
- Secondary Text: #6b747b
- Border: #75817e

### Example Component Prompts
1. Create a `Primary Filled Button` with the text 'Sign Up Now'. Use `Midnight Charcoal` background, `Snow White` text, and `500px` radius. Padding 12px vertical, 24px horizontal. Text should be `MonzoSansText weight 400`.
2. Build a `Light Mode Card` containing a headline and a paragraph. Use `Snow White` background, `32px` border-radius, and the card shadow `rgba(0, 0, 0, 0.1) 0px 0px 10px 0px`. Inner padding is `30px`. Headline should be `MonzoSansDisplay size 39 weight 700`, paragraph `MonzoSansText size 16 weight 400` with `Steel Gray` text.
3. Design a hero section background using the `Section Background Card` variant (`Mist Gray` background, `64px` border-radius, 128px vertical padding). Overlay a `MonzoSansDisplay size 61 weight 800` headline in `Midnight Charcoal`, and a `MonzoSansText size 20 weight 400` body text in `Midnight Charcoal`.
4. Create a `Status Badge` with the text 'New Feature'. Use `Mist Gray` background, `Steel Gray` text, `4px` border-radius, and `4px` vertical, `12px` horizontal padding. Text is `MonzoSansText weight 400`.

## Similar Brands

- **Revolut** — Shares a fintech aesthetic with strong accent colors against a clean, often light, UI and a clear type hierarchy.
- **Starling Bank** — Similar approachable banking feel, using a defined brand color for CTAs and clear, functional design with generous spacing.
- **N26** — Employs a precise, user-centric interface with simple forms, clear typography, and a prominent brand accent color for interactive elements.
- **Wise (formerly TransferWise)** — Focuses on clarity and trust through a clean layout, strong text contrast, and the strategic use of a single accent color for calls to action.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #091723;
  --color-snow-white: #ffffff;
  --color-mist-gray: #f2f8f3;
  --color-slate-blue: #112231;
  --color-silver-dust: #e3ebe4;
  --color-steel-gray: #6b747b;
  --color-ash-gray: #b5b9bd;
  --color-hot-coral: #ff4f40;
  --color-muted-olive: #3b4c54;
  --color-graphite-stroke: #75817;

  /* Typography — Font Families */
  --font-monzosanstext: 'MonzoSansText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monzosansdisplay: 'MonzoSansDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.65px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.8px;
  --text-body: 20px;
  --leading-body: 1.38;
  --tracking-body: -1px;
  --text-subheading: 24px;
  --leading-subheading: 1.4;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -1.6px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -1.8px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.2;
  --text-display: 61px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 30px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 64px;
  --radius-full-2: 100px;
  --radius-full-3: 500px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-badges: 4px;
  --radius-buttons: 500px;
  --radius-general: 64px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 10px 0px;

  /* Surfaces */
  --surface-mist-gray: #f2f8f3;
  --surface-snow-white: #ffffff;
  --surface-slate-blue: #112231;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #091723;
  --color-snow-white: #ffffff;
  --color-mist-gray: #f2f8f3;
  --color-slate-blue: #112231;
  --color-silver-dust: #e3ebe4;
  --color-steel-gray: #6b747b;
  --color-ash-gray: #b5b9bd;
  --color-hot-coral: #ff4f40;
  --color-muted-olive: #3b4c54;
  --color-graphite-stroke: #75817;

  /* Typography */
  --font-monzosanstext: 'MonzoSansText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monzosansdisplay: 'MonzoSansDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.65px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.8px;
  --text-body: 20px;
  --leading-body: 1.38;
  --tracking-body: -1px;
  --text-subheading: 24px;
  --leading-subheading: 1.4;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -1.6px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -1.8px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.2;
  --text-display: 61px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 64px;
  --radius-full-2: 100px;
  --radius-full-3: 500px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 10px 0px;
}
```
