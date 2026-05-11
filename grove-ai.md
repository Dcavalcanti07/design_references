# Grove AI — Style Reference
> Clinical Precision, Green Accent

**Theme:** light

Grove AI presents a precise, scientific aesthetic, balancing stark white canvases with a vibrant, clinical green for key interactions and brand emphasis. Typography combines a modern sans-serif for functional text with a classic serif for impactful headlines, creating a duality of high-tech efficiency and trusted gravitas. Components are clean and subtly elevated, favoring rounded corners and ghost-like elements, lending an approachable yet professional feel to the highly technical domain of AI in clinical trials.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, neutral button backgrounds |
| Grove Green | `#0b835c` | `--color-grove-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Nightfall Black | `#000000` | `--color-nightfall-black` | Primary text, strong borders, icons, interactive button backgrounds for contrast |
| Dark Forrest | `#1c2b27` | `--color-dark-forrest` | Button backgrounds, dark surfaces, textural elements |
| Body Text Charcoal | `#1c1c1e` | `--color-body-text-charcoal` | Secondary text, link text, slightly muted but highly readable |
| Muted Ash | `#303033` | `--color-muted-ash` | Tertiary text, subtle borders, supporting information |
| Card Mist | `#eff1f6` | `--color-card-mist` | Subtle background for card surfaces, distinguishing content blocks without harsh contrast |
| Shadow Gray | `#bfbfbf` | `--color-shadow-gray` | Subtle shadow elements, creating depth without heavy obscuration |
| Supporting Stone | `#676768` | `--color-supporting-stone` | Small print text, helper labels, less prominent textual elements |

## Tokens — Typography

### sans-serif — Catch-all for small interface elements, legal text, and system defaults. Used sparingly to avoid visual conflict with custom typography. · `--font-sans-serif`
- **Weights:** 400, 700
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Catch-all for small interface elements, legal text, and system defaults. Used sparingly to avoid visual conflict with custom typography.

### Geist — Functional UI text, body content, labels, navigation items — providing a modern, legible foundation to the interface. The varied letter-spacing contributes to visual clarity at different scales. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 24px, 32px, 36px, 40px
- **Line height:** 1.00, 1.07, 1.11, 1.14, 1.20, 1.25, 1.40, 1.44, 1.50, 1.65
- **Letter spacing:** -0.0360em at 40px, -0.0310em at 36px, -0.0280em at 32px, -0.0250em at 24px, -0.0200em at 20px, -0.0170em at 18px
- **Role:** Functional UI text, body content, labels, navigation items — providing a modern, legible foundation to the interface. The varied letter-spacing contributes to visual clarity at different scales.

### Libre Caslon Text — Accent headlines and impactful display text, providing a classic, authoritative counterpoint to the modern sans-serif. The subtle tracking adds a sophisticated touch. · `--font-libre-caslon-text`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 36px, 40px, 92px
- **Line height:** 1.20, 1.25
- **Letter spacing:** -0.0110em
- **Role:** Accent headlines and impactful display text, providing a classic, authoritative counterpoint to the modern sans-serif. The subtle tracking adds a sophisticated touch.

### Geist Medium — Geist Medium — detected in extracted data but not described by AI · `--font-geist-medium`
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.88
- **Role:** Geist Medium — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.25 | — | `--text-body` |
| subheading | 20px | 1.2 | -0.4px | `--text-subheading` |
| heading-sm | 24px | 1.11 | -0.6px | `--text-heading-sm` |
| heading | 32px | 1.14 | -0.9px | `--text-heading` |
| heading-lg | 40px | 1.07 | -1.44px | `--text-heading-lg` |
| display | 92px | 1.25 | -1.01px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 40px |
| cards | 20px |
| badges | 999px |
| buttons | 16px |
| default | 8px |
| large-cards | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.35) 0px 0px 1px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.15) 0px 1px 1px 0px` | `--shadow-subtle-3` |
| subtle-4 | `rgba(255, 255, 255, 0.75) 0px 1px 2px 0px inset` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Call to Action Button
**Role:** Prominent interactive element

Filled button with Grove Green background (#0b835c), white text, 0px border radius for key, high-level action buttons. Padding 12px vertical, 20px horizontal.

### Subtle Action Button
**Role:** Secondary interactive element

Ghost button with Dark Forrest (#1c2b27) background and Nightfall Black (#000000) text (browser default link color #0000ee observed), 40px border radius. Padding is not explicitly defined but implied by content size. Used for less prominent actions like 'Read Case Studies'.

### Secondary Outline Button
**Role:** Tier 2 interactive element

White background (#ffffff), browser default link color text (#0000ee observed), 10px borderRadius. Padding 8px vertical, 12px horizontal. Used for 'Sign In' in header.

### Navigation Pill
**Role:** High-level navigation item or tag

Dark Forrest (#1c2b27) background, Nightfall Black (#000000) text (browser default link color #0000ee observed), with 40px border radius, indicating a distinct, selected, or prominent navigation option.

### Default Card
**Role:** Content container

Card Mist (#eff1f6) background, 20px border radius. No explicit shadow. Padding 20px all sides.

### Elevated Content Card
**Role:** Prominent content container

Canvas White (#ffffff) background, 24px border radius. Features a subtle overlay shadow: `rgba(0, 0, 0, 0.06) 0px 0.602187px 1.56569px -0.866667px`, `rgba(0, 0, 0, 0.06) 0px 2.28853px 5.95019px -1.73333px`, `rgba(0, 0, 0, 0.06) 0px 10px 26px -2.6px`. Padding 32px all sides.

### Plain Content Card
**Role:** Simple content grouping

Canvas White (#ffffff) background, 20px border radius, no shadow. Padding 24px all sides.

### Feature Highlight Card
**Role:** Highlighted information container

Card Mist (#eff1f6) background, 20px border radius, no shadow. Padding 32px all sides.

## Do's and Don'ts

### Do
- Use Grove Green (#0b835c) as the dominant accent color, reserving it for primary calls to action, important headings, and brand elements.
- Pair Geist for all body copy and functional UI text, ensuring high legibility, with Libre Caslon Text for headlines to establish a balance of modern efficiency and classic authority.
- Apply a 20px border radius for most cards and content containers, creating a consistently soft and approachable aesthetic.
- Prioritize Canvas White (#ffffff) for backgrounds and primary surfaces, maintaining a clean, expansive feel. Distinguish elevated elements with Card Mist (#eff1f6) or subtle shadows.
- Utilize specific letter-spacing values to enhance readability and visual impact for Geist headings: e.g., -0.0360em for 40px and -0.0250em for 24px.
- Employ Nightfall Black (#000000) as primary text color against light backgrounds, ensuring AAA contrast for readability.
- Maintain consistent vertical rhythm by adhering to a section gap of 40px and card padding of 24px.

### Don't
- Avoid introducing additional chromatic colors that could dilute the impact of Grove Green (#0b835c).
- Do not use heavy, opaque shadows for elevation; instead, prefer the subtle, layered shadow style found on Elevated Content Cards to maintain lightness.
- Refrain from using bold or heavy weights for headline fonts; Libre Caslon Text's 400 weight is key to its restrained visual statement.
- Do not deviate from the established border radii for components; 8px for small elements, 16px for buttons, 20px for cards, and 40px for pills are signature elements.
- Avoid dense or cluttered layouts. Content sections should breathe with ample whitespace, maintaining the comfortable density established by the 10px element gap and 40px section gap.
- Do not use system sans-serif for any primary UI or body text; reserve it only for very small, tertiary information if absolutely necessary.
- Do not randomly vary line heights; adhere to the defined ratios per font size to ensure a consistent textual flow.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and base surface for main content areas. |
| 1 | Card Mist | `#eff1f6` | Secondary background for distinguishable content blocks and default cards. |
| 2 | Elevated Surface White | `#ffffff` | Used for elevated components like testimonial cards, featuring a subtle shadow for emphasis. |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.06) 0px 0.602187px 1.56569px -0.866667px, rgba(0, 0, 0, 0.06) 0px 2.28853px 5.95019px -1.73333px, rgba(0, 0, 0, 0.06) 0px 10px 26px -2.6px`
- **Button:** `rgba(0, 0, 0, 0.15) 0px 1px 1px 0px`
- **Interactive Element Inset:** `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px inset`
- **Interactive Element Border Shadow:** `rgba(0, 0, 0, 0.35) 0px 0px 1px 0px`

## Imagery

Photographs on Grove AI are product-focused, featuring tight crops of faces, primarily of a 'Digital Staff agent' with a clinical, almost AI-generated aesthetic. The treatment blurs backgrounds, keeping the subject sharp and centered, often with a slight green tint that ties into the brand color. Photography is generally light and clean, used for explanatory context to illustrate the AI agent's functionality rather than decorative atmosphere. Icons are filled, monochrome, and used sparingly for clarity.

## Layout

The page uses a maximum-width contained layout rather than full-bleed, with content centered. The hero section is a prominent split visual, often text-left and imagery-right, emphasizing the 'Grace' AI agent. Section rhythm is primarily vertical, with consistent spacing utilizing a 40px section gap. Content is organized into clear blocks, often alternating background colors between Canvas White and Card Mist to delineate sections, favoring two-column layouts and card grids for features. Navigation is a sticky top bar with clearly defined links and a 'Sign In' button.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #000000
- accent: #0b835c
- primary action: #0b835c (filled action)

Example Component Prompts:
- Create a hero section with 'Meet Grace' (Libre Caslon Text, 92px, #0b835c, lineHeight 1.25, letterSpacing -1.01px). Beneath it, add a body text paragraph (Geist, 18px, Nightfall Black). On the right, include an image placeholder with a green tint applied.
- Design a 'Learn More' button: Nightfall Black (#000000) text (browser default link color #0000ee observed), Dark Forrest (#1c2b27) background, 40px border radius, 12px vertical padding, 20px horizontal padding.
- Build an Elevated Content Card: Canvas White (#ffffff) background, 24px border radius, with `rgba(0, 0, 0, 0.06) 0px 10px 26px -2.6px` shadow, 32px padding. Inside, place a heading (Geist, 24px, Body Text Charcoal).
- Create a navigation pill for an active menu item: Dark Forrest (#1c2b27) background, with Nightfall Black (#000000) text (browser default link color #0000ee observed), and a 40px border radius. Content should be Geist, 14px, weight 500.

## Similar Brands

- **Anthropic (product pages)** — Shares a clean, white canvas aesthetic with a focus on AI technology and precise typography.
- **Vercel** — Similar approach to modern sans-serif typography (Geist vs Inter), generous whitespace, and ghost-like interactive elements on a light background.
- **Eight Sleep** — Combines a classic serif for headlines with a clean sans-serif for body text, creating a similar blend of premium and modern feel.
- **DeepMind** — Uses a precise, almost clinical visual language with a strong emphasis on clean UI and functional color accents in an AI context.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-grove-green: #0b835c;
  --color-nightfall-black: #000000;
  --color-dark-forrest: #1c2b27;
  --color-body-text-charcoal: #1c1c1e;
  --color-muted-ash: #303033;
  --color-card-mist: #eff1f6;
  --color-shadow-gray: #bfbfbf;
  --color-supporting-stone: #676768;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-libre-caslon-text: 'Libre Caslon Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-medium: 'Geist Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.11;
  --tracking-heading-sm: -0.6px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.9px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -1.44px;
  --text-display: 92px;
  --leading-display: 1.25;
  --tracking-display: -1.01px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-pill: 40px;
  --radius-cards: 20px;
  --radius-badges: 999px;
  --radius-buttons: 16px;
  --radius-default: 8px;
  --radius-large-cards: 24px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.35) 0px 0px 1px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.15) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.75) 0px 1px 2px 0px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-card-mist: #eff1f6;
  --surface-elevated-surface-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-grove-green: #0b835c;
  --color-nightfall-black: #000000;
  --color-dark-forrest: #1c2b27;
  --color-body-text-charcoal: #1c1c1e;
  --color-muted-ash: #303033;
  --color-card-mist: #eff1f6;
  --color-shadow-gray: #bfbfbf;
  --color-supporting-stone: #676768;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-libre-caslon-text: 'Libre Caslon Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-medium: 'Geist Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.11;
  --tracking-heading-sm: -0.6px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.9px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -1.44px;
  --text-display: 92px;
  --leading-display: 1.25;
  --tracking-display: -1.01px;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.35) 0px 0px 1px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.15) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.75) 0px 1px 2px 0px inset;
}
```
