# Shopify — Style Reference
> Deep Forest Canvas — a digital workspace layered in rich, dark greens and grays, where vivid accents illuminate interactive elements.

**Theme:** dark

Shopify's dark theme presents as a deep, sophisticated digital canvas, evoking the feeling of a high-tech control center. Surfaces articulate depth through subtle shifts in near-black greens and grays, avoiding heavy shadows in favor of tonal variations and crisp white accents. The typography pairs large, authoritative headlines with spacious body text, ensuring clarity even against saturated backgrounds. The design prioritizes direct utility with distinct interactive elements using pure white and a vibrant green, guiding the user's eye without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Midnight | `#02090a` | `--color-canvas-midnight` | Primary page background, deep canvas. |
| Forest Black | `#000000` | `--color-forest-black` | Dominant text color for primary headings on light surfaces, also used for outlines and shadows. |
| Lunar White | `#ffffff` | `--color-lunar-white` | Primary text color on dark backgrounds, interactive elements, and essential UI highlights. |
| Charcoal Slate | `#041e18` | `--color-charcoal-slate` | Card backgrounds and secondary surfaces, creating a subtle layer over the canvas. |
| Border Ash | `#e5e7eb` | `--color-border-ash` | Subtle borders and separators, providing structure without harsh contrast. |
| Steel Gray | `#a1a1aa` | `--color-steel-gray` | Secondary text and informational elements, softer than primary white text. |
| Off Black | `#1e2c31` | `--color-off-black` | Card borders and subtle divisions on dark backgrounds. |
| Subtle Violet | `#010624` | `--color-subtle-violet` | Deep, almost black background for specific sections, adding tonal variation. |
| Deep Teal | `#072720` | `--color-deep-teal` | Navigation backgrounds and selected card states. |
| Text Grey | `#99b3ad` | `--color-text-grey` | Tertiary body text and meta-information. |
| Mid Grey | `#71717a` | `--color-mid-grey` | Less prominent headings and descriptive text. |
| Accent Cyan | `#30deee` | `--color-accent-cyan` | Highlighting specific information or calls to attention within body text. |
| Emerald Interactivel | `#36f4a4` | `--color-emerald-interactivel` | Key interactive elements, branding, and active states—a vibrant signal against the dark palette. |
| Gradient Forest 1 | `linear-gradient(rgb(36, 71, 73) 0%, rgb(24, 46, 47) 100%)` | `--color-gradient-forest-1` | Subtle background gradient for internal sections, establishing depth. |
| Gradient Interstellar Blue | `radial-gradient(rgba(18, 96, 255, 0.35), rgba(0, 0, 0, 0) 50%, rgba(0, 0, 0, 0))` | `--color-gradient-interstellar-blue` | Atmospheric radial gradient for background accent, creating a luminous focal point. |
| Gradient Radiant Teal | `radial-gradient(rgb(21, 112, 118), rgba(0, 0, 0, 0) 65%, rgba(0, 0, 0, 0))` | `--color-gradient-radiant-teal` | Concentric radial gradient for background accent, lending a subtle glow. |
| Gradient Aura | `linear-gradient(126.17deg, rgb(95, 213, 182) 32.74%, rgb(134, 92, 255) 100%)` | `--color-gradient-aura` | Vivid, multi-color gradient used sparingly for eye-catching brand elements. |
| Gradient Deep Forest | `linear-gradient(rgb(10, 44, 48), rgb(6, 21, 24) 80%)` | `--color-gradient-deep-forest` | Deep, layered gradient for background elements, providing robust depth. |
| Gradient Submerged | `radial-gradient(rgb(62, 70, 70), rgb(15, 51, 53) 40%, rgb(6, 26, 28) 70%, rgb(6, 26, 28) 100%)` | `--color-gradient-submerged` | Complex radial gradient for textured backgrounds, suggesting submerged environments. |

## Tokens — Typography

### NeueHaasGrotesk — Primary display and content font. Display sizes use lighter weights like 330 for an approachable, modern feel, while body text uses 400-500 for high readability on dark backgrounds. · `--font-neuehaasgrotesk`
- **Substitute:** Helvetica Neue, Arial
- **Weights:** 330, 400, 500, 550, 600
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 28px, 48px, 55px, 70px, 96px
- **Line height:** 0.83, 0.96, 1.00, 1.14, 1.16, 1.25, 1.28, 1.40, 1.49, 1.50
- **Letter spacing:** 0.0150em, 0.0200em, 0.0400em
- **OpenType features:** `"ss03"`
- **Role:** Primary display and content font. Display sizes use lighter weights like 330 for an approachable, modern feel, while body text uses 400-500 for high readability on dark backgrounds.

### Inter-Variable — Secondary functional font for UI elements, navigation, and detailed information, ensuring legibility at smaller sizes with its optimized variable weights. · `--font-inter-variable`
- **Substitute:** Inter, Roboto
- **Weights:** 400, 420, 450, 550
- **Sizes:** 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.00, 1.20, 1.29, 1.43, 1.50, 1.56
- **Letter spacing:** 0.0600em
- **OpenType features:** `"ss03"`
- **Role:** Secondary functional font for UI elements, navigation, and detailed information, ensuring legibility at smaller sizes with its optimized variable weights.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | 0.06px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.04px | `--text-body-sm` |
| body | 16px | 1.5 | 0.02px | `--text-body` |
| subheading | 20px | 1.4 | 0.015px | `--text-subheading` |
| heading-sm | 28px | 1.28 | — | `--text-heading-sm` |
| heading | 48px | 1.16 | — | `--text-heading` |
| heading-lg | 55px | 1.14 | — | `--text-heading-lg` |
| display | 96px | 0.96 | — | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 340px |
| cards | 12px |
| large | 20px |
| medium | 8px |
| buttons | 9999px |
| default | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.1) 0px 8px 8px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-sm` |
| md | `rgba(0, 0, 0, 0.2) 10px 13px 12px 2px` | `--shadow-md` |
| subtle | `rgba(255, 255, 255, 0.05) 0px 1px 2px 0px, rgba(255, 255,...` | `--shadow-subtle` |
| xl | `rgba(5, 24, 19, 0.05) 0px 20px 60px 0px, rgb(19, 59, 50) ...` | `--shadow-xl` |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary CTA Button
**Role:** Call to action

Pill-shaped button with 'Lunar White' background and 'Forest Black' text, 9999px border-radius, 8px vertical and 20px horizontal padding. Primary button uses this stark contrast to stand out.

### Secondary Outlined Button
**Role:** Secondary action

Outlined button with 'Lunar White' border, transparent background, 'Lunar White' text, 9999px border-radius, 12px vertical and 24px horizontal padding. Used for alternative actions like 'Watch video'.

### Ghost Button
**Role:** Minimal interaction

Implicit button with transparent background and 'Lunar White' text, 9999px border-radius, 12px vertical and 24px horizontal padding, no explicit border. Used for light calls to action or navigation elements.

### Card Surface
**Role:** Content container

Dark card with 'Charcoal Slate' background, 12px border-radius. Features a soft inner shadow of rgba(255, 255, 255, 0.03) inset at the top, and subtle outer shadows for depth.

### Nav Card
**Role:** Informational link container

Card with transparent background, 4px border-radius, and a subtle border of rgba(255, 255, 255, 0.03) inset at the top. Contains minimal padding (4px) for tight content groupings.

### Hero Headline
**Role:** Dominant page title

Uses 'NeueHaasGrotesk' at 70px (or 96px for max display), weight 330, with a 'Lunar White' color. Letter spacing provides ample room for readability, often against dark photographic backgrounds.

### Navigation Link
**Role:** Top-level navigation item

Text link using 'Inter-Variable', 14px, weight 400, in 'Lunar White', often with 'Emerald Interactive' text when active. Uses 10px padding for spacious menu presentation.

## Do's and Don'ts

### Do
- Use 'Canvas Midnight' (#02090a) as the default page background to maintain consistent brand depth.
- Apply 'Emerald Interactive' (#36f4a4) exclusively for primary calls to action, active navigation states, and key interactive elements to create clear affordances.
- Employ the 'NeueHaasGrotesk' light weights (330-400) for all headlines (28px and above) to achieve a sophisticated, restrained authority.
- Maintain a clear visual hierarchy by contrasting 'Lunar White' (#ffffff) text on dark backgrounds for primary content and 'Steel Gray' (#a1a1aa) for secondary or tertiary information.
- Utilize 9999px border-radius for all primary and secondary buttons to ensure recognizably interactive pill shapes.
- Implement the card shadow `rgba(0, 0, 0, 0.1) 0px 8px 8px 0px, ..., rgba(255, 255, 255, 0.03) 0px 1px 0px 0px inset` for elevated content cards on dark surfaces.
- Ensure generous vertical spacing between sections, aiming for a minimum of 'sectionGap' (24px) or larger, to prevent content from feeling cramped.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; restrict chromatic colors to accents and interactive elements.
- Do not deviate from the specified font families 'NeueHaasGrotesk' and 'Inter-Variable' or their designated weights/sizes for body and heading text.
- Refrain from using heavy, opaque shadows for general elevation; rely instead on tonal shifts between surfaces like 'Canvas Midnight' and 'Charcoal Slate'.
- Do not break the 9999px pill button radius for primary interactive elements, as this is a key brand identifier.
- Do not introduce additional gray tones that are not part of the established neutral palette, as this will disrupt the subtle dark layering.
- Avoid using 'Emerald Interactive' (#36f4a4) for large blocks of text or purely decorative elements, as its vivacity should signal interaction or brand identity.
- Do not use generic system borders; always specify exact border colors from the neutral palette like 'Border Ash' (#e5e7eb) for subtle separation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Midnight | `#02090a` | Base page background |
| 1 | Charcoal Slate | `#041e18` | Primary content cards and section backgrounds |
| 2 | Deep Teal | `#072720` | Navigation bar and specific elevated UI elements |

## Elevation

- **Card Surface:** `rgba(0, 0, 0, 0.1) 0px 8px 8px 0px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px, rgba(0, 0, 0, 0.1) 0px 2px 2px 0px, rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.03) 0px 1px 0px 0px inset`
- **List Item/Tooltip:** `rgba(0, 0, 0, 0.2) 10px 13px 12px 2px`
- **Button Focus/Hover:** `rgba(255, 255, 255, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset`
- **Header/Floating Card:** `rgba(5, 24, 19, 0.05) 0px 20px 60px 0px, rgb(19, 59, 50) 0px 1px 0px 0px inset`

## Imagery

This site utilizes a blend of aspirational photography and product-oriented photography. Hero sections often feature high-quality, full-bleed lifestyle or event photography, sometimes with a dark overlay to maintain legibility of white text. Interior sections showcase product screenshots of the Shopify platform itself, often displaying e-commerce site examples. Imagery is generally contained within defined sections or cards, occasionally bleeding out to create visual interest. There is a strong preference for product imagery that highlights the diversity and success of businesses using Shopify, focusing on tangible results rather than abstract concepts. Icons are minimal, utilizing outlined styles in white or 'Emerald Interactive' to complement the dark UI.

## Layout

The layout is primarily a max-width contained design on a dark canvas, utilizing 'pageMaxWidth' for content blocks though the background is full-bleed. The hero section often features a large, often dark-overlayed image or video background with a prominent, centered headline and call-to-action buttons. Subsequent sections alternate between text-heavy content and multi-column visual sections, commonly using 2-column or 3-column card grids for features and examples. Vertical rhythm is established through consistent 'sectionGap' (24px) between content blocks and cards. Navigation is a fixed top bar on a 'Deep Teal' background, with minimal elements.

## Agent Prompt Guide

### Quick Color Reference
- Text Primary: #ffffff (Lunar White)
- Background Base: #02090a (Canvas Midnight)
- CTA Background: #ffffff (Lunar White)
- CTA Text: #000000 (Forest Black)
- Border/Divider: #e5e7eb (Border Ash)
- Accent: #36f4a4 (Emerald Interactive)

### 3-5 Example Component Prompts
1. **Create a hero section:** use `Canvas Midnight` as background. Headline 'Tu negocio puede ser el creador de una nueva categoría' using `NeueHaasGrotesk` at 70px, weight 330, `Lunar White`, `lineHeight` 1.14. Subtext 'Piensa, construye y crece a lo grande con Shopify.' using `NeueHaasGrotesk` at 18px, weight 400, `Steel Gray`, `lineHeight` 1.49. Primary CTA button with text 'Comenzar gratis' using `Primary CTA Button` component, and a secondary action button 'Ver planes' using `Secondary Outlined Button` component.
2. **Generate a feature card:** Background `Charcoal Slate` with `Card Surface` shadow and 12px `cards` radius. Title 'Crea tiendas personalizables' using `NeueHaasGrotesk` at 24px, weight 500, `Lunar White`, with `letterSpacing` 0.015em. Body text 'Personaliza cada aspecto de tu tienda, desde el diseño hasta la función.' using `NeueHaasGrotesk` at 16px, weight 400, `Text Grey`, `lineHeight` 1.5. Incorporate a small icon in `Emerald Interactive`.
3. **Design a navigation bar:** Use `Deep Teal` as the background. Primary links 'Por qué Shopify', 'Productos', 'Precios', 'Enterprise' using `Navigation Link` component. Set active link 'Productos' with `Emerald Interactive` text. Include a 'Comenzar gratis' `Primary CTA Button` and 'Iniciar sesión' `Ghost Button`.

## Similar Brands

- **Figma** — Dark UI with vibrant, functional accent colors and strong typographic hierarchy.
- **Notion** — Highly structured information display, subtle use of neutrals, and emphasis on content clarity over decorative elements in a functional UI.
- **Vercel** — Dark theme, clean typography, and a modern, understated aesthetic with controlled use of accent colors for key actions.
- **Stripe** — Sophisticated use of type, clean and spacious layouts, and a focus on clarity through considered color and spacing, even with a lighter theme focus.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-midnight: #02090a;
  --color-forest-black: #000000;
  --color-lunar-white: #ffffff;
  --color-charcoal-slate: #041e18;
  --color-border-ash: #e5e7eb;
  --color-steel-gray: #a1a1aa;
  --color-off-black: #1e2c31;
  --color-subtle-violet: #010624;
  --color-deep-teal: #072720;
  --color-text-grey: #99b3ad;
  --color-mid-grey: #71717a;
  --color-accent-cyan: #30deee;
  --color-emerald-interactivel: #36f4a4;
  --color-gradient-forest-1: #244749;
  --gradient-gradient-forest-1: linear-gradient(rgb(36, 71, 73) 0%, rgb(24, 46, 47) 100%);
  --color-gradient-interstellar-blue: #1260ff;
  --gradient-gradient-interstellar-blue: radial-gradient(rgba(18, 96, 255, 0.35), rgba(0, 0, 0, 0) 50%, rgba(0, 0, 0, 0));
  --color-gradient-radiant-teal: #157076;
  --gradient-gradient-radiant-teal: radial-gradient(rgb(21, 112, 118), rgba(0, 0, 0, 0) 65%, rgba(0, 0, 0, 0));
  --color-gradient-aura: #5fd5b6;
  --gradient-gradient-aura: linear-gradient(126.17deg, rgb(95, 213, 182) 32.74%, rgb(134, 92, 255) 100%);
  --color-gradient-deep-forest: #0a2c30;
  --gradient-gradient-deep-forest: linear-gradient(rgb(10, 44, 48), rgb(6, 21, 24) 80%);
  --color-gradient-submerged: #3e4646;
  --gradient-gradient-submerged: radial-gradient(rgb(62, 70, 70), rgb(15, 51, 53) 40%, rgb(6, 26, 28) 70%, rgb(6, 26, 28) 100%);

  /* Typography — Font Families */
  --font-neuehaasgrotesk: 'NeueHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.06px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.04px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.015px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.28;
  --text-heading: 48px;
  --leading-heading: 1.16;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1.14;
  --text-display: 96px;
  --leading-display: 0.96;

  /* Typography — Weights */
  --font-weight-w330: 330;
  --font-weight-regular: 400;
  --font-weight-w420: 420;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-w550: 550;
  --font-weight-semibold: 600;

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
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 48px;
  --radius-full-2: 340px;
  --radius-full-3: 405px;
  --radius-full-4: 9999px;

  /* Named Radii */
  --radius-pill: 340px;
  --radius-cards: 12px;
  --radius-large: 20px;
  --radius-medium: 8px;
  --radius-buttons: 9999px;
  --radius-default: 4px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 8px 8px 0px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px, rgba(0, 0, 0, 0.1) 0px 2px 2px 0px, rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.03) 0px 1px 0px 0px inset;
  --shadow-md: rgba(0, 0, 0, 0.2) 10px 13px 12px 2px;
  --shadow-subtle: rgba(255, 255, 255, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset;
  --shadow-xl: rgba(5, 24, 19, 0.05) 0px 20px 60px 0px, rgb(19, 59, 50) 0px 1px 0px 0px inset;

  /* Surfaces */
  --surface-canvas-midnight: #02090a;
  --surface-charcoal-slate: #041e18;
  --surface-deep-teal: #072720;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-midnight: #02090a;
  --color-forest-black: #000000;
  --color-lunar-white: #ffffff;
  --color-charcoal-slate: #041e18;
  --color-border-ash: #e5e7eb;
  --color-steel-gray: #a1a1aa;
  --color-off-black: #1e2c31;
  --color-subtle-violet: #010624;
  --color-deep-teal: #072720;
  --color-text-grey: #99b3ad;
  --color-mid-grey: #71717a;
  --color-accent-cyan: #30deee;
  --color-emerald-interactivel: #36f4a4;
  --color-gradient-forest-1: #244749;
  --color-gradient-interstellar-blue: #1260ff;
  --color-gradient-radiant-teal: #157076;
  --color-gradient-aura: #5fd5b6;
  --color-gradient-deep-forest: #0a2c30;
  --color-gradient-submerged: #3e4646;

  /* Typography */
  --font-neuehaasgrotesk: 'NeueHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.06px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.04px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.015px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.28;
  --text-heading: 48px;
  --leading-heading: 1.16;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1.14;
  --text-display: 96px;
  --leading-display: 0.96;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-208: 208px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 48px;
  --radius-full-2: 340px;
  --radius-full-3: 405px;
  --radius-full-4: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 8px 8px 0px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px, rgba(0, 0, 0, 0.1) 0px 2px 2px 0px, rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(255, 255, 255, 0.03) 0px 1px 0px 0px inset;
  --shadow-md: rgba(0, 0, 0, 0.2) 10px 13px 12px 2px;
  --shadow-subtle: rgba(255, 255, 255, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset;
  --shadow-xl: rgba(5, 24, 19, 0.05) 0px 20px 60px 0px, rgb(19, 59, 50) 0px 1px 0px 0px inset;
}
```
