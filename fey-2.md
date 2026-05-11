# Fey — Style Reference
> Midnight Command Center: high-definition data on frosted glass.

**Theme:** dark

Fey uses a commanding dark mode palette, leveraging deep blacks and subtle gradients as a backdrop for high-fidelity financial data. White and muted grays provide essential text hierarchy and UI structure, while sparse, vivid chromatic accents draw attention to critical insights and interactive elements. The system emphasizes clarity and data density through compact typography and minimal component padding, offering a direct and focused user experience. Transparency and blurred surfaces create a sense of depth without resorting to heavy shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page background, deep card surfaces, shadow base |
| Charcoal Black | `#0b0b0b` | `--color-charcoal-black` | Default card backgrounds, elevated surfaces |
| Ghost Gray | `#131313` | `--color-ghost-gray` | Slightly lighter card background for layered appearance |
| Muted Ash | `#191919` | `--color-muted-ash` | Subtly elevated card backgrounds, hover states |
| Faded Steel | `#333333` | `--color-faded-steel` | Subtle button backgrounds, deeper text contrast |
| Dark Slate | `#525252` | `--color-dark-slate` | Subtle borders, secondary text, faint shadows |
| Cadet Gray | `#828282` | `--color-cadet-gray` | Muted text, decorative strokes, helper icons |
| Storm Gray | `#868f97` | `--color-storm-gray` | Primary text for body and headings, clear borders |
| Light Asphalt | `#999999` | `--color-light-asphalt` | Tertiary text, subtle separators |
| Silver Mist | `#cccccc` | `--color-silver-mist` | Lighter text for low contrast areas, icon highlights |
| Smoke White | `#e6e6e6` | `--color-smoke-white` | Button text, high-contrast helper text |
| Canvas White | `#ffffff` | `--color-canvas-white` | High-contrast text, primary icons, strong borders |
| Sky Surge | `#479ffa` | `--color-sky-surge` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Tangelo Flame | `#ffa16c` | `--color-tangelo-flame` | Section headlines, accent borders — creating a focal point for key information |
| Zenith Green | `#4ebe96` | `--color-zenith-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Aurora Yellow | `linear-gradient(90deg, rgba(254, 253, 0, 0.2) 0%, rgba(255, 255, 255, 0.2) 11.85%)` | `--color-aurora-yellow` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### calibre — The sole typeface for all content. Its technical, compact nature suits dense financial data and UI. Tightly tracked larger sizes maintain visual precision. · `--font-calibre`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 18px, 24px, 26px, 48px, 54px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.30, 1.32, 1.36, 1.40, 1.50, 1.58
- **Letter spacing:** -0.0800em at 54px, -0.0530em at 48px
- **Role:** The sole typeface for all content. Its technical, compact nature suits dense financial data and UI. Tightly tracked larger sizes maintain visual precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.58 | — | `--text-caption` |
| heading | 18px | 1.3 | — | `--text-heading` |
| heading-lg | 24px | 1.25 | — | `--text-heading-lg` |
| display-sm | 26px | 1.2 | — | `--text-display-sm` |
| display | 48px | 1.1 | -0.96px | `--text-display` |
| display-lg | 54px | 1 | -1.08px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 42 | 42px | `--spacing-42` |
| 103 | 103px | `--spacing-103` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| icons | 6px |
| buttons | 99px |
| heroElement | 275px |
| interactiveElements | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.8) 0px 0px 44px 0px` | `--shadow-xl` |
| subtle | `rgba(0, 0, 0, 0.85) 0px 1px 0px 0px` | `--shadow-subtle` |
| md | `rgba(255, 255, 255, 0.25) 0px 0px 14px 0px` | `--shadow-md` |
| xl-2 | `rgba(0, 0, 0, 0.5) 0px 0px 35px 0px` | `--shadow-xl-2` |

### Layout

- **Page max-width:** 1220px
- **Section gap:** 24px
- **Card padding:** 18px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled button indicating primary action.

Background: #e6e6e6, Text: #000000, Border-radius: 99px, Padding: 7px vertical, 16px horizontal. Font: Calibre, weight 400.

### Ghost Navigation Button
**Role:** Subtle, non-filled button for navigation or secondary actions.

Background: transparent, Text: #ffffff, Border-radius: 50% for icon-only, 99px for text. Padding: 0px.

### Subtle Pill Button
**Role:** Discreet interactive elements or tags.

Background: rgba(255, 255, 255, 0.05), Text: #e6e6e6, Border-radius: 6px, Padding: 3.75px vertical, 8-10px horizontal. Border: 1px solid rgba(255, 255, 255, 0.1).

### Data Card
**Role:** Container for financial data visualizations and text.

Background: #0b0b0b, Border-radius: 16px, Box-shadow: none. Padding: 18px on all sides for content unless explicitly overridden internally.

### Elevated Tooltip Card
**Role:** Floating informational panels.

Background: rgba(62, 62, 62, 0.4), Border-radius: 275px (highly rounded, almost circular), Padding: 17.5px. Inset shadows provide internal depth: rgba(255, 255, 255, 0.32) 1.25px 1.25px 1.25px inset, rgba(255, 255, 255, 0.05) 1.25px -1.25px 1.25px inset.

### Header Bar
**Role:** Sticky site header.

Background: #000000, Border-radius: 12px 12px 0px 0px (rounded top, sharp bottom). Shadow: rgba(0, 0, 0, 0.5) 0px 0px 35px 0px. Minimal internal padding.

## Do's and Don'ts

### Do
- Prioritize Calibre font for all text. Utilize its full range of weights to establish hierarchy, maintaining the crisp, data-centric feel.
- Use Absolute Zero (#000000) for base page backgrounds, Charcoal Black (#0b0b0b) for primary card surfaces, and Ghost Gray (#131313) for subtle layering.
- Apply a 99px border-radius for all primary action buttons, ensuring a consistent, friendly pill shape.
- Introduce Sky Surge (#479ffa) or Tangelo Flame (#ffa16c) sparingly as functional highlights for navigation or critical information, never for large areas.
- Maintain tight letter-spacing for headings (e.g., -0.0800em at 54px) to ensure a compact, controlled visual appearance.
- Employ transparency and backdrop filters (e.g., blur(10px)) for floating elements or overlays to create depth without heavy drop shadows.
- Use 1px solid rgba(255, 255, 255, 0.1) hair-thin borders for subtle separation between elements within cards or lists.

### Don't
- Avoid using multiple font families; Calibre is the sole typeface for branding and content.
- Refrain from large, visually dominating images; focus on product screenshots, data visualizations, or minimal abstract elements.
- Do not use generic box-shadows. Shadows should be subtle, usually with dark hues or inset, as defined in component descriptions.
- Never use highly saturated colors for backgrounds or large text blocks; reserve vivid hues for small, functional accents.
- Avoid excessive padding within components; Fey emphasizes information density and a compact layout.
- Do not introduce strong color gradients across full sections or cards; gradients are reserved for subtle accents or interactive element highlights only.
- Do not use generic system icon sets. Icons should align with the defined outline style and minimal appearance.

## Elevation

- **Header Bar:** `rgba(0, 0, 0, 0.5) 0px 0px 35px 0px`
- **Tooltip/Floating Card:** `rgba(255, 255, 255, 0.32) 1.25px 1.25px 1.25px 0px inset, rgba(255, 255, 255, 0.05) 1.25px -1.25px 1.25px 0px inset, rgba(0, 0, 0, 0.753) 9.22562px 43.5671px 43.3172px 0px`
- **General Elevated Element:** `rgba(0, 0, 0, 0.8) 0px 0px 44px 0px`
- **Button Focus/Active:** `rgba(0, 0, 0, 0.85) 0px 1px 0px 0px, rgba(255, 255, 255, 0.25) 0px 0px 14px 0px`

## Imagery

The site uses high-fidelity product screenshots of the Fey interface, often presented in mockups of devices. These are typically contained within cards or display areas, sometimes featuring subtle atmospheric blur effects or partial transparency. Photography is absent. Icons are minimalist, outlined, and monochromatic, primarily in white or light gray. Visual density is high, with imagery serving to demonstrate product functionality and data visualization rather than decorative atmosphere. Abstract graphics, when present, are subtle gradients or blurred shapes, contributing to depth.

## Layout

The page primarily uses a max-width contained layout of 1220px, with some full-bleed sections, particularly at the top hero and for background elements. The hero features a large, dark visual element with centered text overlays and a sticky top navigation. Sections flow vertically with consistent spacing (24px element and section gap) and often feature two-column arrangements of text on the left and a product screenshot or data visualization on the right. Content blocks are information-dense, often using card grids (likely 3-column judging by visual patterns) for feature showcases. The overall rhythm is structured yet fluid, avoiding stark visual dividers in favor of subtle background shifts and card separation.

## Agent Prompt Guide

**Quick Color Reference**
text: #868f97
background: #000000
border: #ffffff
accent: #479ffa
primary action: no distinct CTA color

**3-5 Example Component Prompts**
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a data card displaying financial metrics: background #0b0b0b, 16px border-radius, 18px padding. Headline text is Calibre weight 600 at 18px, color #868f97. Body text is Calibre weight 400 at 14px, color #868f97.
3. Create a ghost navigation link: transparent background, text #ffffff, Calibre weight 500 at 16px, no padding. Hover state changes text color to #479ffa.
4. Design an elevated tooltip: background rgba(62, 62, 62, 0.4), 275px border-radius, 17.5px padding. Text is Calibre weight 400 at 12px, color #cccccc, with inset shadows that include rgba(255, 255, 255, 0.32) 1.25px 1.25px 1.25px inset.

## Similar Brands

- **Linear** — Similar dark theme, minimalist UI, crisp typography, and compact component design for high-density information display.
- **Stripe (dark mode)** — Employs a deep dark background, restrained accent colors, and strong typographic hierarchy to convey seriousness and precision.
- **Superhuman** — Focus on extreme efficiency, subtle UI, refined typography, and minimal use of color to highlight key actions and data.
- **Figma (dark mode)** — Features a dark canvas with layered, translucent panels and a focus on sharp, functional typography and iconography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-black: #0b0b0b;
  --color-ghost-gray: #131313;
  --color-muted-ash: #191919;
  --color-faded-steel: #333333;
  --color-dark-slate: #525252;
  --color-cadet-gray: #828282;
  --color-storm-gray: #868f97;
  --color-light-asphalt: #999999;
  --color-silver-mist: #cccccc;
  --color-smoke-white: #e6e6e6;
  --color-canvas-white: #ffffff;
  --color-sky-surge: #479ffa;
  --color-tangelo-flame: #ffa16c;
  --color-zenith-green: #4ebe96;
  --color-aurora-yellow: #fffd00;
  --gradient-aurora-yellow: linear-gradient(90deg, rgba(254, 253, 0, 0.2) 0%, rgba(255, 255, 255, 0.2) 11.85%);

  /* Typography — Font Families */
  --font-calibre: 'calibre', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.58;
  --text-heading: 18px;
  --leading-heading: 1.3;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 26px;
  --leading-display-sm: 1.2;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.96px;
  --text-display-lg: 54px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-103: 103px;

  /* Layout */
  --page-max-width: 1220px;
  --section-gap: 24px;
  --card-padding: 18px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-xl: 13.9806px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 275px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-icons: 6px;
  --radius-buttons: 99px;
  --radius-heroelement: 275px;
  --radius-interactiveelements: 10px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.8) 0px 0px 44px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.85) 0px 1px 0px 0px;
  --shadow-md: rgba(255, 255, 255, 0.25) 0px 0px 14px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.5) 0px 0px 35px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-black: #0b0b0b;
  --color-ghost-gray: #131313;
  --color-muted-ash: #191919;
  --color-faded-steel: #333333;
  --color-dark-slate: #525252;
  --color-cadet-gray: #828282;
  --color-storm-gray: #868f97;
  --color-light-asphalt: #999999;
  --color-silver-mist: #cccccc;
  --color-smoke-white: #e6e6e6;
  --color-canvas-white: #ffffff;
  --color-sky-surge: #479ffa;
  --color-tangelo-flame: #ffa16c;
  --color-zenith-green: #4ebe96;
  --color-aurora-yellow: #fffd00;

  /* Typography */
  --font-calibre: 'calibre', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.58;
  --text-heading: 18px;
  --leading-heading: 1.3;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 26px;
  --leading-display-sm: 1.2;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.96px;
  --text-display-lg: 54px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-103: 103px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-xl: 13.9806px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 99px;
  --radius-full-3: 275px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.8) 0px 0px 44px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.85) 0px 1px 0px 0px;
  --shadow-md: rgba(255, 255, 255, 0.25) 0px 0px 14px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.5) 0px 0px 35px 0px;
}
```
