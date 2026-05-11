# Contra — Style Reference
> Frosted glass on dark slate; a refined digital workspace.

**Theme:** light

Contra embraces a sleek, desaturated design language with crisp typography and subtle interactions. The interface prioritizes clear content hierarchy on a largely achromatic canvas, punctuated by a deep slate gray for primary actions and occasional, carefully placed pops of vivid color within content modules. Component surfaces typically feature soft, rounded edges and minimal elevation, fostering a sense of approachability and digital craftsmanship.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text on dark backgrounds |
| Midnight Slate | `#222834` | `--color-midnight-slate` | Primary action button backgrounds, dark text on light backgrounds, prominent headings |
| Ash Gray | `#14171f` | `--color-ash-gray` | Primary text, prominent UI elements, strong borders |
| Phantom Gray | `#677084` | `--color-phantom-gray` | Muted text, helper text, subtle borders, inactive elements |
| Silver Pine | `#9ba2b0` | `--color-silver-pine` | Secondary text, disabled states, subtle borders |
| Porcelain | `#e5e7eb` | `--color-porcelain` | Dividers, hairline borders, input outlines |
| Ghost White | `#f5f6f9` | `--color-ghost-white` | Secondary surface backgrounds, subtle hover states |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Input borders, strong accents against light backgrounds |
| Cloud Gray | `#d0d4dc` | `--color-cloud-gray` | Icon fills, secondary button borders |
| Contra Violet | `#6a57e3` | `--color-contra-violet` | Decorative card backgrounds, accent elements in content modules — a vivid, deep purple |
| Blush Pink | `#45192f` | `--color-blush-pink` | Decorative card backgrounds in certain content modules |
| Electric Pink | `#cd74dd` | `--color-electric-pink` | Decorative card backgrounds, vivid content accent |
| Coral Red | `#ff5a5e` | `--color-coral-red` | Decorative card backgrounds, vibrant accent |
| Lavender Mist | `#ddd8ff` | `--color-lavender-mist` | Softer decorative card backgrounds |
| Lime Zest | `#f0fb96` | `--color-lime-zest` | Vivid green decorative card backgrounds, content accent |
| Ocean Spectrum | `linear-gradient(90deg, rgb(205, 243, 253), rgb(157, 222, 249) 42.88%, rgb(151, 157, 241) 94.62%)` | `--color-ocean-spectrum` | Hero background gradient providing atmospheric visual depth |

## Tokens — Typography

### GT Standard M — Primary font for all body text, navigation items, buttons, and most headings below the main hero. Its presence suggests a modern, functional aesthetic. · `--font-gt-standard-m`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 15px, 16px, 24px
- **Line height:** 1.15, 1.20, 1.33, 1.40, 1.43, 1.50, 1.60
- **Letter spacing:** -0.12, -0.14, -0.15, -0.16, -0.24
- **Role:** Primary font for all body text, navigation items, buttons, and most headings below the main hero. Its presence suggests a modern, functional aesthetic.

### GT Standard L — Used sparingly for larger display text and specialized content, defining the headline visual presence with its distinct tracking. The very tight tracking at 58px gives headlines a condensed, impactful feel. · `--font-gt-standard-l`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 8px, 12px, 19px, 23px, 58px
- **Line height:** 0.88, 1.05, 1.33, 1.39, 1.47
- **Letter spacing:** -0.08, 0.1, 0.04, 0.04, -0.58
- **Role:** Used sparingly for larger display text and specialized content, defining the headline visual presence with its distinct tracking. The very tight tracking at 58px gives headlines a condensed, impactful feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.4 | -0.14px | `--text-body` |
| body-lg | 16px | 1.6 | -0.16px | `--text-body-lg` |
| subheading | 19px | 1.39 | 0.04px | `--text-subheading` |
| heading-lg | 24px | 1.2 | -0.24px | `--text-heading-lg` |
| display | 58px | 0.88 | -0.58px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 68 | 68px | `--spacing-68` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 32px |
| cards | 16px |
| inputs | 0px |
| avatars | 50% |
| buttons | 24px |
| modules | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(34, 40, 52, 0.05) 0px 4px 10px 0px, rgba(34, 40, 52,...` | `--shadow-md` |
| subtle | `rgb(19, 24, 25) 0px 1px 3px 0px inset` | `--shadow-subtle` |
| lg | `rgba(0, 0, 0, 0.05) 0px 10px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 65px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Filled Primary Button
**Role:** Calls to action, form submissions.

Background: Midnight Slate (#222834), Text: Canvas White (#ffffff), Border: none, Radius: 24px, Padding: 0px 24px (vertical padding derived from line-height).

### Ghost Button
**Role:** Secondary actions, filtering, navigation.

Background: transparent, Text: Ash Gray (#14171f), Border: none, Radius: 0px. Used for subtle interactions like filter tags.

### Outlined Input Field
**Role:** User input for forms, search bars.

Background: transparent, Text: Charcoal Black (#000000), Border: 1px solid Charcoal Black (#000000), Radius: 0px, Padding: variable. Placeholder text is Charcoal Black.

### Compact Filter Button
**Role:** Filtering and categorization within content sections.

Background: transparent or Ghost White (#f5f6f9), Text: Ash Gray (#14171f), Border: 1px solid Porcelain (#e5e7eb) or Charcoal Black (#000000), Radius: 50% (circular), Padding: 7px vertical.

### Content Card (Featured)
**Role:** Displaying articles, projects, or featured content.

Background: Canvas White (#ffffff), Border: none, Radius: 16px, Padding: 12px or 16px. Features a subtle bottom shadow: rgba(0,0,0,0.05) 0px 10px 20px 0px (nav card).

### Branded Content Card
**Role:** Showcasing specific branded content with unique backgrounds.

Background: Contra Violet (#6a57e3), Blush Pink (#45192f), Electric Pink (#cd74dd), Coral Red (#ff5a5e), Lavender Mist (#ddd8ff), or Lime Zest (#f0fb96). Text: Canvas White (#ffffff). Radius: 16px. These cards use vivid background colors from the accent palette, serving as eye-catching content blocks.

### Navigation Link
**Role:** Primary site navigation in the header and footer.

Text: Ash Gray (#14171f) or Phantom Gray (#677084). Default state is usually text-only, with no distinct background/border. Hover states are implied to change text color or apply subtle underline (visual evidence not clear, but standard interaction).

## Do's and Don'ts

### Do
- Use Midnight Slate (#222834) exclusively for filled primary buttons and the most prominent text on light backgrounds.
- Apply Canvas White (#ffffff) for all main page backgrounds and component surfaces to maintain a pristine aesthetic.
- Employ GT Standard L 58px with letter-spacing -0.58px for all main section headlines, giving them a distinct condensed aggression.
- Prioritize 24px border-radius for all interactive buttons and 16px for content cards to unify the component curvature.
- Maintain a clear visual hierarchy by limiting saturated colors to decorative content cards and subtle functional accents, keeping core UI achromatic.
- Utilize Phantom Gray (#677084) for secondary text, labels, and hair-thin dividers to preserve visual lightness.
- Ensure input fields have sharp, 0px radius borders in Charcoal Black (#000000) for a precise, functional appearance.

### Don't
- Do not use highly saturated colors for button backgrounds or primary text unless it’s a specific branded content block.
- Avoid heavy shadows or gradients on core UI elements; elevation should be minimal and primarily achieved with the provided soft shadows.
- Do not use default system fonts; always specify GT Standard M or L, or their designated substitutes.
- Refrain from using more than two distinct text sizes within a single component to prevent visual clutter.
- Do not introduce new border radii beyond the defined 24px, 16px, 10px, 4px, 32px, 40px, and 50% for consistency.
- Never use less than 4px element spacing; maintain a minimum of 4px between adjacent elements.
- Do not apply excessive padding; adhere to the 12px card padding and ensure button padding is symmetrical from the center.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background. |
| 1 | Ghost White | `#f5f6f9` | Secondary background for discreet sections or hover states. |

## Elevation

- **Card (Navigation):** `rgba(0, 0, 0, 0.05) 0px 10px 20px 0px`
- **Button:** `rgba(34, 40, 52, 0.05) 0px 4px 10px 0px, rgba(34, 40, 52, 0.04) -2px 18px 18px 0px`

## Imagery

The site uses a mixture of diverse imagery: product screenshots, abstract graphics, and some lifestyle/candid photography within content modules. Product screenshots are typically contained and framed, often with contextual UI elements. Abstract graphics are used decoratively, integrating with the card backgrounds. Photography, when present, is diverse in style but generally contained within card components rather than full-bleed heroes. Icons are minimalist, primarily outlined or filled in achromatic tones. Imagery is utilized both for decorative atmosphere and to showcase creative work, but doesn't dominate page density; text remains a strong focus.

## Layout

The page maintains a centered max-width layout for most content, with a full-bleed hero section at the top featuring a subtle gradient background and centered headline. Content sections follow a consistent vertical rhythm, often alternating between a single-column block and a multi-column (e.g., 4-column) grid of content cards. Navigation is handled by a sticky top bar. Content arrangement often features text-dominant sections followed by image-rich grids. The overall density is balanced, allowing breathing room between sections while presenting information in a structured, digestible manner.

## Agent Prompt Guide

Quick Color Reference: 
text: #14171f
background: #ffffff
border: #e5e7eb
accent: #6a57e3
primary action: #222834 (filled action)

Example Component Prompts:
1. Create a Hero Section: Background is 'Ocean Spectrum' gradient. Headline 'Get more creative' in GT Standard L 58px, weight 400, #14171f, letter-spacing -0.58px. Subtext 'Contra is the commission-free creative network...' in GT Standard M 16px, weight 400, #677084.
2. Create a Primary Action Button: #222834 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a Branded Content Card: Background 'Contra Violet' (#6a57e3), text 'Latest Insights' in Canvas White (#ffffff), GT Standard M 14px weight 500. Radius 16px, padding 12px. Include a small icon inside using Canvas White fill.

## Similar Brands

- **Bēhance** — Showcases creative portfolios with strong visual cards and a clean, project-focused layout.
- **Dribbble** — Emphasizes visual content with cards and a focus on creative professionals, featuring similar subtle achromatic UI with pops of color.
- **Webflow** — Features a modern, crisp aesthetic with well-defined cards, clean typography, and a strategic use of color and subtle backgrounds.
- **Linear** — Exhibits highly refined, minimalistic UI with a strong emphasis on typography, soft neutrals, and efficient information display.
- **Framer** — Utilizes a similar approach to showcasing design work and product features with sharp typography, structured layouts, and limited, impactful color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-slate: #222834;
  --color-ash-gray: #14171f;
  --color-phantom-gray: #677084;
  --color-silver-pine: #9ba2b0;
  --color-porcelain: #e5e7eb;
  --color-ghost-white: #f5f6f9;
  --color-charcoal-black: #000000;
  --color-cloud-gray: #d0d4dc;
  --color-contra-violet: #6a57e3;
  --color-blush-pink: #45192f;
  --color-electric-pink: #cd74dd;
  --color-coral-red: #ff5a5e;
  --color-lavender-mist: #ddd8ff;
  --color-lime-zest: #f0fb96;
  --color-ocean-spectrum: #cdefd0;
  --gradient-ocean-spectrum: linear-gradient(90deg, rgb(205, 243, 253), rgb(157, 222, 249) 42.88%, rgb(151, 157, 241) 94.62%);

  /* Typography — Font Families */
  --font-gt-standard-m: 'GT Standard M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-standard-l: 'GT Standard L', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.16px;
  --text-subheading: 19px;
  --leading-subheading: 1.39;
  --tracking-subheading: 0.04px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 58px;
  --leading-display: 0.88;
  --tracking-display: -0.58px;

  /* Typography — Weights */
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-72: 72px;

  /* Layout */
  --section-gap: 65px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 63px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-tags: 32px;
  --radius-cards: 16px;
  --radius-inputs: 0px;
  --radius-avatars: 50%;
  --radius-buttons: 24px;
  --radius-modules: 10px;

  /* Shadows */
  --shadow-md: rgba(34, 40, 52, 0.05) 0px 4px 10px 0px, rgba(34, 40, 52, 0.04) -2px 18px 18px 0px;
  --shadow-subtle: rgb(19, 24, 25) 0px 1px 3px 0px inset;
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 10px 20px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ghost-white: #f5f6f9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-slate: #222834;
  --color-ash-gray: #14171f;
  --color-phantom-gray: #677084;
  --color-silver-pine: #9ba2b0;
  --color-porcelain: #e5e7eb;
  --color-ghost-white: #f5f6f9;
  --color-charcoal-black: #000000;
  --color-cloud-gray: #d0d4dc;
  --color-contra-violet: #6a57e3;
  --color-blush-pink: #45192f;
  --color-electric-pink: #cd74dd;
  --color-coral-red: #ff5a5e;
  --color-lavender-mist: #ddd8ff;
  --color-lime-zest: #f0fb96;
  --color-ocean-spectrum: #cdefd0;

  /* Typography */
  --font-gt-standard-m: 'GT Standard M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-standard-l: 'GT Standard L', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.16px;
  --text-subheading: 19px;
  --leading-subheading: 1.39;
  --tracking-subheading: 0.04px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 58px;
  --leading-display: 0.88;
  --tracking-display: -0.58px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 63px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-md: rgba(34, 40, 52, 0.05) 0px 4px 10px 0px, rgba(34, 40, 52, 0.04) -2px 18px 18px 0px;
  --shadow-subtle: rgb(19, 24, 25) 0px 1px 3px 0px inset;
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 10px 20px 0px;
}
```
