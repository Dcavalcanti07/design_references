# V7labs — Style Reference
> Dark Slate Operational Hub

**Theme:** mixed

V7 presents a data-driven, operational aesthetic with a strong dark mode emphasis contrasted by a single vibrant orange accent. Heavy-set headlines command attention, while compact, meticulously tracked body text conveys information efficiency. Surfaces are cool and dark, often in shades of gray, creating a backdrop for the brand's bold orange highlights, which are reserved for functional elements. Component shapes lean towards pronounced circularity and soft, rounded containers.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, critical UI elements, background sections in dark layouts. The foundational dark color |
| White Canvas | `#ffffff` | `--color-white-canvas` | Primary background for light sections, inverse text on dark backgrounds, active states |
| Ghost Gray | `#f7f6f5` | `--color-ghost-gray` | Secondary page background, subtle dividers, input fields. Provides slight visual separation from White Canvas |
| Charcoal Surface | `#292929` | `--color-charcoal-surface` | Dark surface background for cards and panels, borders, secondary text in dark mode |
| Deep Gray | `#1c1c1c` | `--color-deep-gray` | Elevated dark backgrounds, footer background – darker than Charcoal Surface |
| Card Gray | `#484848` | `--color-card-gray` | Background for information cards, slightly lighter than text color in dark sections to create subtle contrast |
| Muted Ash | `#989897` | `--color-muted-ash` | Muted body text, placeholder text, secondary icons. Provides a softer alternative to Charcoal Surface for less prominent information |
| Link Ink | `#00104e` | `--color-link-ink` | Interactive link color, outlined button borders. A deep, saturated blue-violet for interaction |
| Action Orange | `#ff683d` | `--color-action-orange` | Orange outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Danger Red | `#ec580a` | `--color-danger-red` | Orange outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Info Blue | `#2663eb` | `--color-info-blue` | Violet outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Warning Yellow | `#ce8c04` | `--color-warning-yellow` | Yellow outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Success Green | `#14a249` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Martina Plantijn Light — Display and marketing headlines. Weight 300 for large sizes creates a sophisticated, authoritative tone, while 400 for smaller headings offers robust readability without losing elegance. · `--font-martina-plantijn-light`
- **Substitute:** serif
- **Weights:** 300, 400
- **Sizes:** 24px, 30px, 40px, 60px
- **Line height:** 1.00, 1.07, 1.33, 1.40
- **Letter spacing:** -0.02em at 60px, -0.01em at 24px
- **Role:** Display and marketing headlines. Weight 300 for large sizes creates a sophisticated, authoritative tone, while 400 for smaller headings offers robust readability without losing elegance.

### STK Bureau — Primary user interface text, navigation, and input labels. Its precise tracking ensures compact, information-dense areas remain legible and sharp. · `--font-stk-bureau`
- **Substitute:** Roboto
- **Weights:** 400, 430
- **Sizes:** 9px, 10px, 12px, 14px, 16px, 18px, 21px, 24px
- **Line height:** 1.00, 1.08, 1.11, 1.14, 1.17, 1.25, 1.40, 1.43, 1.56
- **Letter spacing:** -0.027em at 24px, -0.025em at 21px, -0.02em at 18px, -0.01em at 16px
- **Role:** Primary user interface text, navigation, and input labels. Its precise tracking ensures compact, information-dense areas remain legible and sharp.

### Inter Variable — Small functional text, captions, and secondary information where legibility at small sizes is paramount. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Small functional text, captions, and secondary information where legibility at small sizes is paramount.

### Inter — System-level text, tooltips, and default body copy for straightforward content. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System-level text, tooltips, and default body copy for straightforward content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading | 18px | 1.17 | -0.36px | `--text-heading` |
| heading-lg | 21px | 1.14 | -0.525px | `--text-heading-lg` |
| display | 60px | 1 | -1.2px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 40px |
| cards | 8px |
| forms | 160px |
| buttons | 160px |
| circular | 99px |
| secondaryElements | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 39px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Pill Button - Filled
**Role:** Primary action button with a rounded, pill-like shape.

Background: Charcoal Surface (#292929), Text: White Canvas (#ffffff), Border Radius: 160px, Padding: 12px vertical, 20px horizontal.

### Pill Button - Outlined
**Role:** Secondary action button with a distinct border accent.

Background: transparent, Text: Link Ink (#00104e) or primary brand text for navigation, Border Color: Link Ink (#00104e), Border Radius: 160px, Padding: 12px vertical, 20px horizontal.

### White Text Button
**Role:** Light-themed or ghost button.

Background: White Canvas (#ffffff), Text: Midnight Ink (#000000), Border Radius: 160px, Padding: 0px.

### Standard Content Card
**Role:** Container for information modules within a dark section.

Background: Card Gray (#484848), Border Radius: 14px, Padding: 10px.

### Compact Content Card
**Role:** Smaller variant of the content card for denser information display.

Background: Card Gray (#484848), Border Radius: 7px, Padding: 4px.

### Light Overlay Card
**Role:** Slightly transparent card for highlighting content over a dark background.

Background: rgba(255, 255, 255, 0.12), Border Radius: 8px, Padding: 8px horizontal, 14px vertical.

### Pill Input Field
**Role:** Form input field with a distinctive pill shape.

Background: Ghost Gray (#f7f6f5), Text/Placeholder: Charcoal Surface (#292929), Border Color: Charcoal Surface (#292929), Border Radius: 160px, Padding: 10px vertical, 16px horizontal.

## Do's and Don'ts

### Do
- Prioritize Martina Plantijn Light for all prominent headlines (H1-H3), using weight 300 for large sizes (above 40px) to achieve a sophisticated, non-shouting presence.
- Utilize STK Bureau for all UI text, navigation, and most body content, applying its tight letter-spacing to maintain a compact, high-information density aesthetic.
- Implement Action Orange (#ff683d) exclusively for primary calls-to-action and essential interactive highlights; avoid using it for decorative purposes.
- Apply Charcoal Surface (#292929) as the default background for cards and content blocks within dark sections, ensuring visual consistency across components.
- Ensure interactive elements like buttons and input fields feature prominent rounded borders (160px or 40px radius) to emphasize their clickable nature.
- Use Link Ink (#00104e) sparingly for outlined button borders and text links, establishing a secondary interactive color that complements the brand orange.
- Maintain a clear visual hierarchy by using Midnight Ink (#000000) for primary text against light backgrounds and White Canvas (#ffffff) for primary text against dark backgrounds.

### Don't
- Do not introduce new saturated accent colors outside of the established brand and semantic palette; color should be functional, not decorative.
- Avoid using Martina Plantijn Light for body text or small UI elements, as its elegance is lost at smaller point sizes and its character designed for impact.
- Do not deviate from the specified border radii; the distinct rounding (e.g., 160px for buttons, 8px for cards) is a core part of the visual identity.
- Refrain from using drop shadows excessively; the system favors flat surfaces and subtle elevation, mainly rgba(0, 0, 0, 0.25) 0px 1px 2px 0px for minor depth.
- Do not mix light and dark surface colors randomly; sections should either commit to a full dark background (Charcoal Surface, Deep Gray) or a light background (White Canvas, Ghost Gray).
- Avoid generic system fonts unless explicitly specified for supplementary content; the custom typography is crucial for brand recognition and voice.
- Do not use Action Orange (#ff683d) for non-interactive elements or generic display text; its purpose is to guide user action.

## Agent Prompt Guide

Quick Color Reference:
text: #000000 (light sections), #ffffff (dark sections)
background: #f7f6f5 (light base), #292929 (dark base)
border: #000000 (light UI elements), #00104e (interactive outlined buttons)
accent: #ff683d
primary action: #292929 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: background #292929, text #ffffff, border radius 160px, padding 12px vertical, 20px horizontal, using STK Bureau weight 430, size 16px.
2. Design a Dark Content Card: background #484848, border radius 14px, padding 10px, with content text #ffffff at STK Bureau weight 400, size 14px.
3. Implement a Hero Section Headline: Martina Plantijn Light weight 300, size 60px, color #ffffff, letter-spacing -1.2px, centered against a background of Action Orange (#ff683d).

## Similar Brands

- **Rippling** — Similar bold, data-forward typography and strong calls to action against a clean or contrasting background.
- **Retool** — Employs a functional, compact UI vocabulary with a strong emphasis on dark modes and clear information hierarchy through card-based layouts.
- **Vanta** — Shares a sophisticated yet direct visual communication style, often using a single strong accent color to denote action or brand presence within a largely neutral palette.
- **Gusto** — Uses large, declarative headlines with specific font choices and distinct, heavily rounded buttons for calls to action.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-ghost-gray: #f7f6f5;
  --color-charcoal-surface: #292929;
  --color-deep-gray: #1c1c1c;
  --color-card-gray: #484848;
  --color-muted-ash: #989897;
  --color-link-ink: #00104e;
  --color-action-orange: #ff683d;
  --color-danger-red: #ec580a;
  --color-info-blue: #2663eb;
  --color-warning-yellow: #ce8c04;
  --color-success-green: #14a249;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martina-plantijn-light: 'Martina Plantijn Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-stk-bureau: 'STK Bureau', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading: 18px;
  --leading-heading: 1.17;
  --tracking-heading: -0.36px;
  --text-heading-lg: 21px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -0.525px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.2px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w430: 430;
  --font-weight-medium: 500;

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
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 39px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 33px;
  --radius-3xl-2: 40px;
  --radius-full: 99px;
  --radius-full-2: 120px;
  --radius-full-3: 160px;

  /* Named Radii */
  --radius-tags: 40px;
  --radius-cards: 8px;
  --radius-forms: 160px;
  --radius-buttons: 160px;
  --radius-circular: 99px;
  --radius-secondaryelements: 2px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-ghost-gray: #f7f6f5;
  --color-charcoal-surface: #292929;
  --color-deep-gray: #1c1c1c;
  --color-card-gray: #484848;
  --color-muted-ash: #989897;
  --color-link-ink: #00104e;
  --color-action-orange: #ff683d;
  --color-danger-red: #ec580a;
  --color-info-blue: #2663eb;
  --color-warning-yellow: #ce8c04;
  --color-success-green: #14a249;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martina-plantijn-light: 'Martina Plantijn Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-stk-bureau: 'STK Bureau', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading: 18px;
  --leading-heading: 1.17;
  --tracking-heading: -0.36px;
  --text-heading-lg: 21px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -0.525px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.2px;

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
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 33px;
  --radius-3xl-2: 40px;
  --radius-full: 99px;
  --radius-full-2: 120px;
  --radius-full-3: 160px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```
