# Public — Style Reference
> Crisp Editorial Clarity: a high-contrast financial journal on a pristine, structured page.

**Theme:** light

Public's design system evokes a confident, editorial demeanor, balancing sharp, sophisticated typography with subtle, functional use of color. The primary palette is a clean, high-contrast monochrome, serving as a neutral canvas for data and product interfaces. Visual accents are delivered through a singular, vivid violet for interactive elements and an electric blue for subtle highlights, creating focal points without visual clutter. Surfaces are predominantly light and spacious, grounded by slim borders and minimal shadow, suggesting precision and clarity in financial tooling.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, darkest backgrounds, prominent borders |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, card surfaces, UI elements requiring high contrast |
| Smoke | `#e9edf3` | `--color-smoke` | Subtle borders, dividers, card outlines, background separation |
| Graphite | `#262626` | `--color-graphite` | Dark card backgrounds, secondary dark text, subtle dark interface elements |
| Ash | `#dce2ea` | `--color-ash` | Muted borders and text, outlines for secondary elements |
| Jet | `#1b2128` | `--color-jet` | Dark navigation text, dark UI element borders, secondary dark backgrounds |
| Slate | `#516880` | `--color-slate` | Secondary text, muted links, subtle informational accents |
| Cloud | `#a8b4bf` | `--color-cloud` | Subtle border accents, light informational text, placeholder content |
| Ultramarine | `#0027b3` | `--color-ultramarine` | Active link text, interactive element borders, functional highlights |
| Azure Glow | `#95d0ff` | `--color-azure-glow` | Decorative icons, light accent fills, subtle hover states |
| Lilac Mist | `#fff0fe` | `--color-lilac-mist` | Light supporting surface for subtle backgrounds and section separation. Do not promote it to the primary CTA color |
| Sky Veil | `#cdf3ff` | `--color-sky-veil` | Gray supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Ocean Deep | `#00379a` | `--color-ocean-deep` | Subtle icon fills, deeper blue decorative elements |
| Nav Blue | `#566e8c` | `--color-nav-blue` | Navigation active states, subtle header text |

## Tokens — Typography

### Denton — Display and primary headings – its light weight at large sizes conveys authority through understatement, setting an intellectual tone. · `--font-denton`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 48px, 52px, 80px
- **Line height:** 1.00, 1.11, 1.12, 1.13
- **Role:** Display and primary headings – its light weight at large sizes conveys authority through understatement, setting an intellectual tone.

### Invest Pro — Secondary headings, subheadings, and emphasized text segments – providing a structured, confident contrast to Inter for key informational blocks. · `--font-invest-pro`
- **Substitute:** IBM Plex Serif
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 32px
- **Line height:** 1.00, 1.13, 1.14, 1.15, 1.17, 1.20, 1.28, 1.29, 1.31, 1.37, 1.38, 1.50
- **Role:** Secondary headings, subheadings, and emphasized text segments – providing a structured, confident contrast to Inter for key informational blocks.

### Invest Pro — More emphatic secondary headings and callouts, providing a slightly bolder touch while retaining the core character of Invest Pro. · `--font-invest-pro`
- **Substitute:** IBM Plex Serif
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 32px
- **Line height:** 1.00, 1.13, 1.14, 1.15, 1.17, 1.20, 1.28, 1.29, 1.31, 1.37, 1.38, 1.50
- **Role:** More emphatic secondary headings and callouts, providing a slightly bolder touch while retaining the core character of Invest Pro.

### Inter — Body copy, navigation, and detailed information – its neutral, legible form supports dense data and long-form content. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 10px, 11px, 12px, 14px, 16px
- **Line height:** 1.00, 1.15, 1.42, 1.43, 1.50, 1.54, 1.60, 2.00
- **Letter spacing:** normal
- **Role:** Body copy, navigation, and detailed information – its neutral, legible form supports dense data and long-form content.

### Inter — Strong emphasis within body text, labels, and small headings, maintaining high readability at smaller sizes. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 10px, 11px, 12px, 14px, 16px
- **Line height:** 1.00, 1.15, 1.42, 1.43, 1.50, 1.54, 1.60, 2.00
- **Letter spacing:** normal
- **Role:** Strong emphasis within body text, labels, and small headings, maintaining high readability at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-lg | 14px | 1.43 | — | `--text-body-lg` |
| heading-sm | 20px | 1.2 | — | `--text-heading-sm` |
| heading | 24px | 1.17 | — | `--text-heading` |
| heading-lg | 32px | 1.28 | — | `--text-heading-lg` |
| display | 48px | 1.11 | — | `--text-display` |
| display-lg | 80px | 1.13 | — | `--text-display-lg` |

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
| 44 | 44px | `--spacing-44` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 16px |
| buttons | 100px |
| default | 4px |
| minimal | 1px |
| partial | 12px |
| smallInteractive | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.08) 0px 1px 10px 0px` | `--shadow-md` |
| lg | `rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205...` | `--shadow-lg` |
| lg-2 | `rgba(0, 0, 0, 0.06) 0px 24px 24px 0px` | `--shadow-lg-2` |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Call to action

An outlined button with transparent background, white text (#ffffff), and a subtle border of Ultramarine (#0027b3) or rgba(255, 255, 255, 0.1). Rounded with 100px radius and 40px horizontal padding. Features a dual colored shadow to hint at interactivity: rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205, 255, 0.25) -8px 8px 30px 0px.

### Filled Action Button
**Role:** Call to action

A solid black button (#000000) with white text (#ffffff). Rounded corners set at 100px, with 40px horizontal padding. Used for primary actions like 'Get started'.

### Section Card
**Role:** Content container

A light gray background card (#fafa_fafa) with 16px border-radius. No shadow, flush padding for internal content. Used to group related features or information.

### Monochrome Elevated Card
**Role:** Accent / Elevated content.

A dark gray background card (#262626) with a subtle shadow (rgba(0, 0, 0, 0.08) 0px 1px 10px 0px). Has 6px border-radius and 16px padding on all sides. Used for focused content blocks, such as AI agent details or market briefs.

### Informational Badge
**Role:** Metadata / Status

Transparent background badge with black text (#000000) and no border radius. Used for small, contextual labels like '3.30% APY*'.

### Feature Link Card
**Role:** Navigation / Feature overview

Transparent background with no border-radius or shadow, 22px left padding. Utilized for introductory feature links like 'Stocks Build your portfolio'.

## Do's and Don'ts

### Do
- Prioritize Ink (#000000) for all primary text and critical headlines to maintain high contrast and legibility.
- Use Ultramarine (#0027b3) exclusively for interactive elements like links and button borders, ensuring functional color remains a distinct accent.
- Apply Denton at Weight 300 for all large headings (48px and above) to convey a sense of understated authority.
- Maintain a default border-radius of 4px for most UI elements, reserving 100px for buttons and 16px for prominent cards.
- Employ Smoke (#e9edf3) for hairline borders and subtle dividers to structure content without heavy visual lines.
- Ensure generous spacing with an 8px element gap and 16px card padding to maintain a spacious, uncluttered layout.
- Use Invest Pro for secondary titles and emphasized text, ensuring it complements Denton without competing for attention.
- Leverage the dual-tinted shadow (rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205, 255, 0.25) -8px 8px 30px 0px) for highly interactive ghost buttons to add distinct visual depth.

### Don't
- Avoid using highly saturated colors outside of the defined Ultramarine (#0027b3) and Azure Glow (#95d0ff) accents.
- Do not introduce heavy drop shadows or decorative gradients on surfaces, as the design maintains minimal elevation.
- Refrain from mixing font families randomly; adhere strictly to Inter for body text, Invest Pro for structured text, and Denton for display headings.
- Do not use border-radius values other than 1px, 4px, 8px, 12px, 16px, 100px, or 999px.
- Do not use #0000ee (browser default link blue) for any link states; use Ultramarine (#0027b3) instead.
- Do not use an element gap smaller than 8px for vertical or horizontal spacing between related items.
- Avoid excessive use of uppercase text; reserve it only for specific, highly constrained labels or navigation items where it's explicitly observed.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, base for light sections. |
| 1 | Section Card | `#fafa_fafa` | Light background for grouping content segments within the main canvas. |
| 2 | Monochrome Elevated Card | `#262626` | Darker, slightly elevated card backgrounds for focused information or interactive elements. |

## Elevation

- **Monochrome Elevated Card:** `rgba(0, 0, 0, 0.08) 0px 1px 10px 0px`
- **Primary Ghost Button:** `rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205, 255, 0.25) -8px 8px 30px 0px`

## Imagery

The visual language for imagery is primarily product-focused and functional. It features clean product screenshots of UI interfaces, often displayed within device mockups. These are presented without heavy filters or dramatic lighting, maintaining a sense of realism and direct utility. Imagery primarily serves an explanatory role, showcasing the product's functionality rather than purely decorative atmosphere. The density is moderate; images are used to break up text-heavy sections and illustrate concepts, but the layout remains text-dominant.

## Layout

The page primarily uses a contained layout with elements centered within a maximum width, though the hero section can be full-bleed. The hero features a large, light-weighted headline centered over a background that integrates product imagery. Sections exhibit a consistent vertical rhythm, often alternating between centered stacks of text, or two-column layouts pairing text with a visual. Content is arranged with a sense of order and precision, frequently utilizing visual separations for clarity. Navigation is a sticky top bar with clearly delineated links and distinct login/signup buttons.

## Agent Prompt Guide

### Quick Color Reference
text: #000000
background: #ffffff
border: #e9edf3
accent: #0027b3
primary action: #0027b3 (outlined action border)

### 3-5 Example Component Prompts
1. Create an Outlined Primary Action: Transparent background, #0027b3 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Design a feature card for 'Bonds': Section Card (#fafa_fafa) background, 16px radius. Title 'Bonds' Invest Pro weight 400, 32px, Ink (#000000). Body text 'Fractionalized access to corporate bonds.' Inter weight 400, 16px, Slate (#516880).
3. Build a navigation menu item for 'Products': Inter weight 400, 16px, Ink (#000000) text. On hover, Ultramarine (#0027b3) text color. Use an 8px element gap between items.
4. Create a 'Market Briefing' block: Monochrome Elevated Card (#262626) background, 6px radius, 16px padding. Headline 'Market Briefing' Invest Pro weight 500, 20px, white text (#ffffff). Body text 'what’s moving the markets each day.' Inter weight 400, 14px, Cloud (#a8b4bf).
5. Construct a cookie consent banner: Canvas (#ffffff) background, 8px radius. Text 'We use cookies...' Inter weight 400, 12px, Slate (#516880). A 'Got it' button using a Filled Action Button style (#000000 background, #ffffff text, 100px radius).

## Similar Brands

- **Linear** — High-contrast monochrome UI with minimal use of accent color, clean spacious layouts, and sharp typography.
- **Rippling** — Editorial feel achieved through distinct, impactful heading fonts contrasting with clean body text, and a restrained color palette.
- **Stripe** — Emphasis on clear information hierarchy, high legibility, subtle borders, and a focus on product functionality over decorative elements.
- **Wealthfront** — Sophisticated use of typography for financial services, a clean and uncluttered interface, and a primary focus on data presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-smoke: #e9edf3;
  --color-graphite: #262626;
  --color-ash: #dce2ea;
  --color-jet: #1b2128;
  --color-slate: #516880;
  --color-cloud: #a8b4bf;
  --color-ultramarine: #0027b3;
  --color-azure-glow: #95d0ff;
  --color-lilac-mist: #fff0fe;
  --color-sky-veil: #cdf3ff;
  --color-ocean-deep: #00379a;
  --color-nav-blue: #566e8c;

  /* Typography — Font Families */
  --font-denton: 'Denton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-invest-pro: 'Invest Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-lg: 14px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.28;
  --text-display: 48px;
  --leading-display: 1.11;
  --text-display-lg: 80px;
  --leading-display-lg: 1.13;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 100px;
  --radius-full-2: 310px;
  --radius-full-3: 375px;
  --radius-full-4: 379px;
  --radius-full-5: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 16px;
  --radius-buttons: 100px;
  --radius-default: 4px;
  --radius-minimal: 1px;
  --radius-partial: 12px;
  --radius-smallinteractive: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.08) 0px 1px 10px 0px;
  --shadow-lg: rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205, 255, 0.25) -8px 8px 30px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.06) 0px 24px 24px 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-section-card: #fafa_fafa;
  --surface-monochrome-elevated-card: #262626;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-smoke: #e9edf3;
  --color-graphite: #262626;
  --color-ash: #dce2ea;
  --color-jet: #1b2128;
  --color-slate: #516880;
  --color-cloud: #a8b4bf;
  --color-ultramarine: #0027b3;
  --color-azure-glow: #95d0ff;
  --color-lilac-mist: #fff0fe;
  --color-sky-veil: #cdf3ff;
  --color-ocean-deep: #00379a;
  --color-nav-blue: #566e8c;

  /* Typography */
  --font-denton: 'Denton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-invest-pro: 'Invest Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-lg: 14px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.28;
  --text-display: 48px;
  --leading-display: 1.11;
  --text-display-lg: 80px;
  --leading-display-lg: 1.13;

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
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 100px;
  --radius-full-2: 310px;
  --radius-full-3: 375px;
  --radius-full-4: 379px;
  --radius-full-5: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.08) 0px 1px 10px 0px;
  --shadow-lg: rgba(255, 196, 250, 0.25) 8px -8px 20px 0px, rgba(56, 205, 255, 0.25) -8px 8px 30px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.06) 0px 24px 24px 0px;
}
```
