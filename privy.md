# Privy — Style Reference
> High-contrast digital architecture.

**Theme:** light

Privy uses a stark, high-contrast visual language with a focus on deep achromatic surfaces, crisp typography, and a single vibrant violet accent. The system balances a dark, high-tech interface for content with a pure white canvas for the primary layout. Components are presented with a solid, almost weighty feel, featuring large contrasting button states and slightly rounded corners to soften the otherwise sharp aesthetic. The overall impression is one of grounded precision and modern functionality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, light section backgrounds, primary text on dark surfaces |
| Ink Black | `#000000` | `--color-ink-black` | Primary text on light surfaces, borders, icons, deep UI element fills |
| Deep Midnight | `#010110` | `--color-deep-midnight` | Dark UI backgrounds, primary action button fill, headings on light canvas |
| Carbon Gray | `#111117` | `--color-carbon-gray` | Card backgrounds, elevated container surfaces, secondary text on light backgrounds |
| Steel Gray | `#22222a` | `--color-steel-gray` | Accent card backgrounds, slightly darker elevated surfaces |
| Muted Stone | `#73737c` | `--color-muted-stone` | Muted helper text, secondary information on light backgrounds |
| Deep Space Violet | `#635bff` | `--color-deep-space-violet` | Accent links, active states, highlights — provides a single powerful chromatic anchor |

## Tokens — Typography

### sans-serif — Small functional text like captions, labels, and utility navigation. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Small functional text like captions, labels, and utility navigation.

### Inter — Body text, input fields, and all text requiring precise tracking for density and hierarchy. Its tighter letter-spacing contributes to the overall compact, crisp feel. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 18px, 20px, 21px, 38px
- **Line height:** 1.00, 1.20, 1.26, 1.27, 1.40, 1.50, 1.60, 1.78, 1.90
- **Letter spacing:** -0.02
- **Role:** Body text, input fields, and all text requiring precise tracking for density and hierarchy. Its tighter letter-spacing contributes to the overall compact, crisp feel.

### ABC Favorit Variable Unlicensed Trial — All display and large headings. Its wide letterforms and extremely tight tracking (up to -0.03em) create a commanding, almost sculpted presence. · `--font-abc-favorit-variable-unlicensed-trial`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 16px, 26px, 28px, 52px, 56px, 76px
- **Line height:** 1.03, 1.07, 1.13, 1.15, 1.23, 1.29
- **Letter spacing:** -0.03
- **Role:** All display and large headings. Its wide letterforms and extremely tight tracking (up to -0.03em) create a commanding, almost sculpted presence.

### ABC Favorit Unlicensed Trial — ABC Favorit Unlicensed Trial — detected in extracted data but not described by AI · `--font-abc-favorit-unlicensed-trial`
- **Weights:** 400
- **Sizes:** 56px
- **Line height:** 1.07
- **Letter spacing:** -0.03
- **Role:** ABC Favorit Unlicensed Trial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.24px | `--text-caption` |
| body-sm | 14px | 1.27 | -0.28px | `--text-body-sm` |
| body | 16px | 1.5 | -0.32px | `--text-body` |
| subheading | 28px | 1.13 | -0.84px | `--text-subheading` |
| heading | 52px | 1.15 | -1.56px | `--text-heading` |
| display | 76px | 1.23 | -2.28px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 70 | 70px | `--spacing-70` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| small | 2px |
| buttons | 100px |
| extreme | 951px |
| primary | 8px |

### Layout

- **Section gap:** 70px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Action button

Filled with Deep Midnight (#010110), text in Canvas White (#ffffff). Features highly rounded corners (100px) and generous 16px padding on all sides. Used for primary calls to action.

### Ghost Button
**Role:** Secondary action button

Transparent background (rgba(0,0,0,0)) with text and border in Deep Space Violet (#635bff). Uses 100px border-radius and 16px padding. Offers a visually lighter alternative to the primary button.

### Light Card
**Role:** Informational container

Background in Carbon Gray (#111117) with 10px border-radius and no shadow. Used for features or grouped content. Internal padding varies.

### Dark Card
**Role:** Emphasized container

Background in Steel Gray (#22222a) with 8px border-radius and no shadow. Used for showcasing specific product features or data.

### Navigation Link
**Role:** Primary navigation item

Text in Ink Black (#000000) for standard states, changing to a subtle border and potentially Deep Space Violet (#635bff) for active states. No explicit background on hover for most nav items.

### Text Input (Dark)
**Role:** Form input field

Transparent background with text and border in Deep Midnight (#010110). No border radius. Text uses Inter font family. Focus state likely involves Deep Space Violet.

## Do's and Don'ts

### Do
- Use ABC Favorit Variable for all display and headline text, with -0.03em letter spacing.
- Apply Canvas White (#ffffff) as the primary page background color for most content sections.
- Use Deep Midnight (#010110) for primary action button backgrounds, with Canvas White text and 100px border-radius.
- Employ Carbon Gray (#111117) and Steel Gray (#22222a) for card and elevated surface backgrounds.
- Introduce Deep Space Violet (#635bff) as the accent color for interactive elements like links and active states.
- Utilize Ink Black (#000000) for primary text on light backgrounds and borders.
- Maintain a default padding of 16px for buttons and a radius of 8px for cards, extending to 100px for pill-shaped elements.

### Don't
- Avoid using multiple accent colors; Deep Space Violet is the sole chromatic highlight.
- Do not deviate from the established type scale and letter spacing values; especially the tight tracking for display fonts.
- Do not use visible drop shadows; the system relies on flat planes and stark color contrast for depth.
- Avoid decorative gradients; rely on solid colors to define areas and elements.
- Do not use generic system fonts for body text; always use Inter for consistent tracking and readability.
- Refrain from introducing borders on cards; contrast is achieved through background color difference.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default content area. |
| 1 | Carbon Gray | `#111117` | First-level elevated surfaces, such as primary content cards. |
| 2 | Steel Gray | `#22222a` | Second-level elevated surfaces or emphasized cards, visually distinct from Carbon Gray. |

## Elevation

This design system explicitly avoids drop shadows for elevation. Depth and hierarchy are established entirely through color contrast between distinct neutral background shades and careful spacing, creating a flat, modern aesthetic.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #635bff
primary action: #010110 (filled action)

Example Component Prompts:
Create a Primary Action Button: #010110 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: Card background in Carbon Gray (#111117) with 8px border-radius, 16px padding. Headline 'Secure by design' using ABC Favorit Variable 26px, Ink Black (#000000), letter-spacing -0.78px. Body text 'Privy combines TEEs and key sharding to secure every wallet.' using Inter 16px, Muted Stone (#73737c), letter-spacing -0.32px.

Create a navigation link: Text 'Solutions' using sans-serif 16px, Ink Black (#000000). On hover, change text to Deep Space Violet (#635bff). No background or border.

## Similar Brands

- **Stripe** — Dominance of achromatic surfaces, clean typography, and a modern B2B SaaS aesthetic.
- **Vercel** — High-contrast dark mode interfaces, sharp yet functional typography, and a minimalist approach to components.
- **Railway** — Systematic use of dark, muted backgrounds with crisp white text and a single accent color for interaction.
- **Linear** — Focus on precise typography, dense information architecture, and efficient use of screen real estate with a restrained color palette.
- **Superhuman** — Emphasis on speed, clarity, and a visual system driven by strong typographic hierarchy and minimal ornamentation over heavy visual effects.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-deep-midnight: #010110;
  --color-carbon-gray: #111117;
  --color-steel-gray: #22222a;
  --color-muted-stone: #73737c;
  --color-deep-space-violet: #635bff;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit-variable-unlicensed-trial: 'ABC Favorit Variable Unlicensed Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit-unlicensed-trial: 'ABC Favorit Unlicensed Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.27;
  --tracking-body-sm: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 28px;
  --leading-subheading: 1.13;
  --tracking-subheading: -0.84px;
  --text-heading: 52px;
  --leading-heading: 1.15;
  --tracking-heading: -1.56px;
  --text-display: 76px;
  --leading-display: 1.23;
  --tracking-display: -2.28px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-70: 70px;

  /* Layout */
  --section-gap: 70px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-lg-2: 10.2px;
  --radius-3xl: 41px;
  --radius-full: 48px;
  --radius-full-2: 100px;
  --radius-full-3: 951px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-small: 2px;
  --radius-buttons: 100px;
  --radius-extreme: 951px;
  --radius-primary: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-carbon-gray: #111117;
  --surface-steel-gray: #22222a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-deep-midnight: #010110;
  --color-carbon-gray: #111117;
  --color-steel-gray: #22222a;
  --color-muted-stone: #73737c;
  --color-deep-space-violet: #635bff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit-variable-unlicensed-trial: 'ABC Favorit Variable Unlicensed Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit-unlicensed-trial: 'ABC Favorit Unlicensed Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.27;
  --tracking-body-sm: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 28px;
  --leading-subheading: 1.13;
  --tracking-subheading: -0.84px;
  --text-heading: 52px;
  --leading-heading: 1.15;
  --tracking-heading: -1.56px;
  --text-display: 76px;
  --leading-display: 1.23;
  --tracking-display: -2.28px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-70: 70px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-lg-2: 10.2px;
  --radius-3xl: 41px;
  --radius-full: 48px;
  --radius-full-2: 100px;
  --radius-full-3: 951px;
}
```
