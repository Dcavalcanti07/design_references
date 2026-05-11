# Doppler — Style Reference
> Midnight command center. Deep purples on near-black surfaces, highlighted by electric green and violet, feel like precise, secure control.

**Theme:** dark

Doppler's visual style is a 'midnight command center' behind frosted glass, creating an atmosphere of secure, high-tech operations. Deep purples and blacks form the primary palette, suggesting seriousness and advanced technology. Vivid electric green and violet accents cut through the darkness, like indicator lights on a complex dashboard, highlighting crucial actions and information. A subtle border treatment using a near-achromatic light gray provides structure and division without breaking the dark theme, reinforcing the 'frosted glass' feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1c1624` | `--color-midnight-ink` | Primary surface background, text on light elements (buttons). The dominant deep purple-gray setting the dark theme. |
| Deep Plum | `#2d2734` | `--color-deep-plum` | Secondary surface background, subtly deeper than Midnight Ink to create visual layering without heavy shadows. |
| Text Off-White | `#f1f0ec` | `--color-text-off-white` | Primary body text, headers on dark backgrounds, key interactive text. High contrast for readability against dark surfaces. |
| Ash Gray | `#d0c9c4` | `--color-ash-gray` | Secondary text, placeholder text, inactive elements. Provides a softer contrast than Text Off-White. |
| Outline Pale | `#e5e7eb` | `--color-outline-pale` | Subtle borders, dividers, card outlines. A near-achromatic light gray that provides structure on dark backgrounds. |
| Accent Green | `#00f575` | `--color-accent-green` | Primary call-to-action buttons, interactive links, active states. This vibrant green is the main interactive accent. |
| Accent Violet | `#b997ff` | `--color-accent-violet` | Highlighting key headings, brand elements. A vivid violet used sparingly for emphasis, contrasting with the green. |
| Deep Violet Gradient | `linear-gradient(91deg, rgb(133, 90, 255) 14.92%, rgb(255, 86, 50) 90.53%)` | `--color-deep-violet-gradient` | Decorative backgrounds for hero sections, prominent visual elements. Creates a sense of depth and energy. |
| Nebula Pink Radial | `radial-gradient(78.16% 78.1% at 77.15% 26.77%, rgb(255, 158, 250) 0%, rgb(107, 19, 245) 50%, rgb(35, 23, 54) 100%)` | `--color-nebula-pink-radial` | Backgrounds for abstract graphics and brand illustrations, providing a cosmic, high-tech mood. |

## Tokens — Typography

### Doppler Repro — The sole typeface for all content. Its versatility across weights and sizes, combined with micro letter-spacing adjustments, maintains a sleek, optimized feel across headlines and body text. · `--font-doppler-repro`
- **Substitute:** Inter
- **Weights:** 400, 450, 500, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 24px, 32px, 48px, 64px, 96px
- **Line height:** 1.00, 1.05, 1.15, 1.20, 1.40, 1.50
- **Letter spacing:** -0.48, -0.16, 0.14, 0.48
- **Role:** The sole typeface for all content. Its versatility across weights and sizes, combined with micro letter-spacing adjustments, maintains a sleek, optimized feel across headlines and body text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 32px | 1.15 | — | `--text-heading` |
| heading-lg | 48px | 1.05 | -0.48px | `--text-heading-lg` |
| display | 64px | 1 | -0.48px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| cards | 20px |
| buttons | 12px |
| menuItems | 20px |

### Layout

- **Section gap:** 64px
- **Card padding:** 28px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Primary navigation and subtle secondary actions.

backgroundColor=rgba(0, 0, 0, 0), color=rgb(208, 201, 196), no border, 0px border-radius, 0px padding. Uses Ash Gray for text color.

### Primary CTA Button
**Role:** Main calls to action.

backgroundColor=rgb(0, 245, 117), color=rgb(28, 22, 36), 12px border-radius, 10px 16px padding. Text is Midnight Ink, background is Accent Green.

### Badge Button
**Role:** Informational tags or small interactive elements, often in navigation.

backgroundColor=rgba(242, 241, 237, 0.04), color=rgb(241, 240, 236), 20px border-radius, 8px 10px padding. Uses primary body text color and a subtle transparent background, creating a 'frosted glass' effect.

### Feature Card
**Role:** Showcasing integration partners or key features.

backgroundColor=rgba(242, 241, 237, 0.04), 20px border-radius, no box-shadow, 28px padding. Displays content on a slightly elevated, transparent dark surface.

## Do's and Don'ts

### Do
- Use Accent Green (#00f575) exclusively for primary calls-to-action to maximize its impact.
- Apply 'Doppler Repro' font with appropriate letterSpacing from the type scale for all text elements.
- Maintain a 20px border-radius for all cards and informational badges.
- Structure UI elements with Text Off-White (#f1f0ec) on Midnight Ink (#1c1624) or Deep Plum (#2d2734) for optimal contrast in dark mode.
- Utilize Outline Pale (#e5e7eb) for subtle borders and dividers to provide structure without adding visual weight.
- Employ consistent 8px element gaps for most internal component spacing.

### Don't
- Do not use saturated colors other than Accent Green or Accent Violet for interactive elements or brand highlights.
- Avoid box-shadows; use background color layering (Midnight Ink, Deep Plum) and subtle borders for elevation and separation.
- Do not use highly rounded corners (e.g., 9999px) on any elements other than specific, explicit tags.
- Do not introduce additional font families; 'Doppler Repro' covers all typographic needs.
- Avoid using bright, non-text colors (like red, yellow, pure white) for large text blocks, as it undermines the dark theme's sophistication.

## Imagery

Imagery primarily consists of product screenshots and abstract, brand-colored graphics/illustrations. Product screenshots are contained within device mockups or dark-themed UI frames, showcasing the product's interface. Illustrations employ vivid violet, green, and deep purple color palettes, featuring organic, flowing shapes as well as geometric abstractions, often with subtle gradients (Nebula Pink Radial) or glowing effects that integrate seamlessly into the dark theme. Icons are consistently monochrome (Outline Pale on dark backgrounds) and outlined with a medium stroke weight. The visual language centers on explaining complex technical concepts through clear UI examples and atmospheric, abstract visuals rather than photography, contributing to a high-density, informational feel.

## Layout

The layout features a full-bleed dark background (Midnight Ink) with content sections generally confined to a centered, implicit max-width. The hero section employs a split layout: a commanding headline and descriptive text on the left, an illustrative product screenshot on the right, all on a gradient background. Subsequent sections reveal a consistent vertical rhythm of padding (64px sectionGap), alternating between text-centric blocks and grid layouts (e.g., a 4-column card grid for integrations). Content arrangement often uses a text-left, image-right or grid-based pattern. The page is information-dense yet maintains clear visual separation through consistent spacing and subtle surface variations. Navigation is a sticky top bar with ghost buttons and a prominent Accent Green CTA.

## Agent Prompt Guide

### Quick Color Reference
- Text: #f1f0ec
- Background: #1c1624
- CTA: #00f575
- Border: #e5e7eb
- Accent: #b997ff

### Example Component Prompts
1. Create a `Primary CTA Button`: background #00f575, text #1c1624, border-radius 12px, padding 10px 16px. Label with 'Start for Free →'.
2. Design a `Feature Card`: background rgba(242, 241, 237, 0.04), border-radius 20px, padding 28px. Inside, use a heading at 24px 'Doppler Repro' weight 500, #f1f0ec, lineHeight 1.2. Below, body text at 16px 'Doppler Repro' weight 400, #f1f0ec, lineHeight 1.5.
3. Implement a page section titled 'Secure secrets. Prevent breaches. Keep teams moving.': Use a display heading at 'Doppler Repro' 64px weight 700, #f1f0ec, letter-spacing -0.48px. Beneath it, body text 18px #f1f0ec, lineHeight 1.4.
4. Generate a `Badge Button`: background rgba(242, 241, 237, 0.04), text #f1f0ec, border-radius 20px, padding 8px 10px. Label with 'Official Doppler MCP Server'.

## Similar Brands

- **Vercel** — Similar dark-mode aesthetic with emphasis on clean typography and vibrant single-color accents for CTAs.
- **Supabase** — Shared use of deep purple hues and neon accents to convey a modern, developer-centric tool's brand identity.
- **Linear** — Adherence to precise typography, subtle surface layering, and a minimalist dark UI without heavy shadows.
- **GitHub (dark mode)** — Utilizes a dark, muted background with selective use of bright, functional accent colors for interactive elements and status indicators.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1c1624;
  --color-deep-plum: #2d2734;
  --color-text-off-white: #f1f0ec;
  --color-ash-gray: #d0c9c4;
  --color-outline-pale: #e5e7eb;
  --color-accent-green: #00f575;
  --color-accent-violet: #b997ff;
  --color-deep-violet-gradient: #6b13f5;
  --gradient-deep-violet-gradient: linear-gradient(91deg, rgb(133, 90, 255) 14.92%, rgb(255, 86, 50) 90.53%);
  --color-nebula-pink-radial: #231736;
  --gradient-nebula-pink-radial: radial-gradient(78.16% 78.1% at 77.15% 26.77%, rgb(255, 158, 250) 0%, rgb(107, 19, 245) 50%, rgb(35, 23, 54) 100%);

  /* Typography — Font Families */
  --font-doppler-repro: 'Doppler Repro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 28px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 80px;
  --radius-full-2: 120px;
  --radius-full-3: 9999px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-cards: 20px;
  --radius-buttons: 12px;
  --radius-menuitems: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1c1624;
  --color-deep-plum: #2d2734;
  --color-text-off-white: #f1f0ec;
  --color-ash-gray: #d0c9c4;
  --color-outline-pale: #e5e7eb;
  --color-accent-green: #00f575;
  --color-accent-violet: #b997ff;
  --color-deep-violet-gradient: #6b13f5;
  --color-nebula-pink-radial: #231736;

  /* Typography */
  --font-doppler-repro: 'Doppler Repro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 80px;
  --radius-full-2: 120px;
  --radius-full-3: 9999px;
}
```
