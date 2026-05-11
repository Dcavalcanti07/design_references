# Operate — Style Reference
> digital ledger, subtle grid

**Theme:** light

Operate employs a digital ledger aesthetic, presenting information within a subtle, grid-like framework. The visual style is highly structured yet feels artisanal, achieved through custom typefaces and a dominant cool green palette with nuanced neutrals. Interactive elements are sparingly used, drawing attention with their distinct green hues against a backdrop of muted, almost monochromatic surfaces and text. Components are light, using thin, inset borders and a preference for ghost-like interactions over heavy fills.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Fog | `#e0e0e0` | `--color-canvas-fog` | Primary page and section backgrounds, card surfaces where a subtle lift is desired |
| Inkwell | `#29211e` | `--color-inkwell` | Primary body text, bold headings, borders on dark elements |
| Ghostly Gray | `#ffffff` | `--color-ghostly-gray` | Text on dark backgrounds, subtle card backgrounds, overlay backgrounds |
| Shadowed Steel | `#453b41` | `--color-shadowed-steel` | Subtle background for card sections, decorative borders and inset shadows |
| Ash Outline | `#e5e5e5` | `--color-ash-outline` | Subtle background for UI elements, light borders |
| Verdant Text | `#09352e` | `--color-verdant-text` | Decorative icons, secondary text, content within cards, an infrequent accent color |
| Primary Green | `#85c093` | `--color-primary-green` | Primary action button backgrounds, highlighted card surfaces, functional fills |
| Lively Green | `#117025` | `--color-lively-green` | Green text accent for links, tags, and emphasized short phrases |
| Deep Moss | `#007010` | `--color-deep-moss` | Green text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Subtle Green Tint | `#77aa83` | `--color-subtle-green-tint` | Soft background washes, very light surface hints |
| Accent Violet | `#433787` | `--color-accent-violet` | Highlight elements, specific link backgrounds or decorative features, used sparingly |

## Tokens — Typography

### muoto — Used for smaller text elements like captions, meta information, and some button labels. Its micro-adjustments in letter-spacing for different sizes indicate a precise typographic control for legibility at small scales. · `--font-muoto`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px
- **Line height:** 1.17, 1.18, 1.23, 1.33, 1.38, 1.46, 1.62
- **Letter spacing:** -0.012em, -0.011em, -0.010em, -0.009em
- **OpenType features:** `"liga" 0`
- **Role:** Used for smaller text elements like captions, meta information, and some button labels. Its micro-adjustments in letter-spacing for different sizes indicate a precise typographic control for legibility at small scales.

### denim — The primary font for body text, headings, and interactive elements. The consistent positive letter-spacing across weights gives a slightly open, airy feel, contrasting with the tighter tracking of 'muoto'. · `--font-denim`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 32px, 48px
- **Line height:** 1.11, 1.14, 1.15, 1.17, 1.19, 1.29, 1.35, 1.40, 1.44, 1.50, 1.56, 1.63
- **Letter spacing:** 0.012em
- **OpenType features:** `"liga" 0`
- **Role:** The primary font for body text, headings, and interactive elements. The consistent positive letter-spacing across weights gives a slightly open, airy feel, contrasting with the tighter tracking of 'muoto'.

### cinetype — Reserved for highly specific, almost monospaced or display-like text where character spacing is used for visual effect or precise alignment, suitable for code snippets or data labels. Large letter-spacing values create a staccato rhythm. · `--font-cinetype`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.14, 1.19
- **Letter spacing:** -0.008em, 0.050em, 0.175em, 0.300em
- **OpenType features:** `"liga" 0`
- **Role:** Reserved for highly specific, almost monospaced or display-like text where character spacing is used for visual effect or precise alignment, suitable for code snippets or data labels. Large letter-spacing values create a staccato rhythm.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.46 | -0.13px | `--text-caption` |
| body | 14px | 1.17 | 0.17px | `--text-body` |
| heading | 20px | 1.19 | 0.24px | `--text-heading` |
| heading-lg | 32px | 1.29 | 0.38px | `--text-heading-lg` |
| display | 48px | 1.35 | 0.58px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 12px |
| default | 4px |
| heroElement | 18px |
| circularElements | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(9, 53, 45, 0.05) 0px 5px 6px -4px, rgba(174, 202, 19...` | `--shadow-sm` |
| subtle | `rgb(202, 211, 210) 0px 0px 0px 0.5px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(64, 68, 66) 0px 0px 0px 0.5px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(224, 229, 229) 0px -0.5px 0px 0px inset` | `--shadow-subtle-3` |
| md | `rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, ...` | `--shadow-md` |
| sm-2 | `rgba(0, 0, 0, 0.25) 0px 5px 5px 0px` | `--shadow-sm-2` |
| sm-3 | `rgba(0, 0, 0, 0.1) 0px 5px 7.5px -5px` | `--shadow-sm-3` |
| md-2 | `rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, ...` | `--shadow-md-2` |

### Layout

- **Section gap:** 42px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Minimal call to actions or secondary links that maintain visual lightness.

backgroundColor=rgba(0, 0, 0, 0), color=rgb(17, 112, 37) (Lively Green), borderRadius=0px, padding=0px, border-top=oklch(0 0 none / 0.1) which is a very subtle nearly invisible white border.

### Pill Button
**Role:** Prominent actions and primary CTAs.

backgroundColor=rgb(222, 222, 222), color=rgb(41, 33, 30) (Inkwell), borderRadius=12px, padding=7px 13px, border-top-color=rgb(41, 33, 30) (Inkwell).

### Green Accent Button
**Role:** Emphasis buttons, used for specific interactive elements.

backgroundColor=rgb(133, 192, 147) (Primary Green), color=lab(40.4038 -46.3181 39.9606) (likely a dark desaturated green for contrast), borderRadius=9999px, padding=0px.

### Dark Inset Card
**Role:** Content container for features or pricing, subtle depth.

backgroundColor=rgb(26, 25, 26), borderRadius=10px, paddingTop=15px, paddingRight=18px, paddingBottom=20px, paddingLeft=18px, boxShadow=rgb(69, 59, 65) 0px 0px 0px 1.25px inset.

### Light Panel Card
**Role:** Floating content blocks or informational panels.

backgroundColor=rgb(247, 247, 247), borderRadius=12px, boxShadow=none, padding=0px.

### Segment Card
**Role:** Visual segmentation for lists or detailed data displays.

backgroundColor=rgb(12, 14, 14), borderRadius=6px 0px 0px 6px, boxShadow=rgb(64, 68, 66) 0px 0px 0px 0.5px inset, padding=0px.

### Green Highlight Card
**Role:** Indicating active or selected states for cards.

backgroundColor=rgb(133, 192, 147) (Primary Green), borderRadius=12px, boxShadow=none, paddingTop=5px, paddingRight=11px, paddingBottom=10px, paddingLeft=11px.

## Do's and Don'ts

### Do
- Use Primary Green (#85c093) only for primary action backgrounds or highlighted surfaces, and Lively Green (#117025) or Deep Moss (#007010) for text links and active states.
- Implement the 'muoto' font for all microtext, captions, and any element requiring precise, compact legibility with variable letter-spacing for different sizes.
- Apply a consistent horizontal `elementGap` of 8px between inline elements to maintain a compact yet readable density.
- Utilize an `inset` shadow of rgb(64, 68, 66) 0.5px for card borders to create subtle definition without heavy elevation.
- Maintain a default border-radius of 12px for cards and filled buttons, with 9999px for pill-shaped elements.
- Ensure all interactive elements, especially those using 'cinetype', respect the distinct letter-spacing values like 0.050em or 0.175em for visual impact.
- Structure page sections with a `sectionGap` of 42px to provide clear visual separation between content blocks.

### Don't
- Avoid using saturated greens as generic background colors for large sections; reserve them for functional highlights and interactive states.
- Do not deviate from the specified consolidated letter-spacing values within their respective font families and sizes.
- Do not introduce heavy drop shadows; prefer subtle inset borders and minimal, low-opacity box-shadows for elevation.
- Do not use generic system fonts in place of 'muoto', 'denim', or 'cinetype'; their specific letter-spacing and weights are integral to the brand's typographic identity.
- Do not apply padding to buttons that lack explicit padding values in their component definition; default to the provided 0px for Ghost Buttons.
- Avoid arbitrary changes to the subtle neutral palette; distinct neutral shades (#e0e0e0, #29211, #ffffff, #e5e5e5) serve specific surface and text roles.
- Do not mix 'cinetype' with other fonts for body text or headlines where its distinct wide letter-spacing would disrupt readability unnecessarily.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Fog | `#e0e0e0` | Primary page background. |
| 1 | Ghostly Gray | `#ffffff` | Layered backgrounds like modals or secondary light cards. |
| 2 | Light Panel Card | `#f7f7f7` | Elevated card surfaces. |
| 3 | Dark Inset Card | `#1a191a` | Darker, inset content containers. |

## Elevation

- **Card:** `rgb(64, 68, 66) 0px 0px 0px 0.5px inset`
- **Box:** `rgba(9, 53, 45, 0.05) 0px 5px 6px -4px, rgba(174, 202, 197, 0.08) 0px 1px 1px 0.5px`

## Imagery

This design system uses minimal, abstract graphics. The primary visual element is a dynamic data visualization represented by scattered circles and a flowing blue area against a green, dotted grid. Photography and complex illustrations are absent. Icons are typically single-color, adhering to the brand's green palette or subtle neutrals, appearing outlined or filled in contexts needing emphasis. Imagery serves a decorative, atmospheric role rather than explanatory content, suggesting data and process without literal representation. The visual density is image-heavy in the hero but otherwise text-dominant, relying on typographic variations and structured layout for rhythm.

## Layout

The page primarily utilizes a full-bleed structure. The hero section features a wide, interactive data visualization, dominated by the brand's green and blue tones. Content is arranged using a mix of implied grid systems and centered stacks. The overall structure suggests a compact density with elements often having close proximity, particularly within card components. Navigation is minimal, consisting of a top bar with subtle links and a left sidebar for meta-information like document date.

## Agent Prompt Guide

### Quick Color Reference
- text: #29211e
- background: #e0e0e0
- border: #e0e0e0
- accent: #433787
- primary action: #85c093 (filled action)

### 3-5 Example Component Prompts
- Create a pricing section card: Use Dark Inset Card component with secondary body text in Verdant Text (#09352e) and a Pill Button (#222222 background, #29211e text, 12px radius, 7px 13px padding).
- Design a feature callout: Use a Green Highlight Card (133, 192, 147 background, 12px radius, 5px 11px padding) with a 'denim' heading at size 20px, lineHeight 1.19, #29211e color. Body text in 'denim' at 14px, lineHeight 1.17, #29211e color.
- Build a header navigation link: Text in 'denim' font, 14px, lineHeight 1.17, Deep Moss (#007010) on hover. Include a Ghost Button with text `Request early access` in Lively Green (#117025) and 0px padding/radius.
- Create a meta-information label: Text in 'muoto' font, 11px, lineHeight 1.46, with letterSpacing -0.012em, color Verdant Text (#09352e).
- Construct a main headline: Use 'denim' font, size 48px, lineHeight 1.35, letterSpacing 0.58px, color Inkwell (#29211e).

## Similar Brands

- **Linear** — Monochromatic interface with subtle interaction colors, compact density, and geometric custom typography.
- **Superhuman** — High-contrast text on neutral backgrounds, focus on speed and efficiency through UI, and minimalist design components.
- **Notion** — Clean information architecture, heavily text-driven but with structured and subtle visual elements for organization.
- **Carta** — Data-heavy interface with precise typography and a restrained color palette, often using green as a functional accent.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-fog: #e0e0e0;
  --color-inkwell: #29211e;
  --color-ghostly-gray: #ffffff;
  --color-shadowed-steel: #453b41;
  --color-ash-outline: #e5e5e5;
  --color-verdant-text: #09352e;
  --color-primary-green: #85c093;
  --color-lively-green: #117025;
  --color-deep-moss: #007010;
  --color-subtle-green-tint: #77aa83;
  --color-accent-violet: #433787;

  /* Typography — Font Families */
  --font-muoto: 'muoto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-denim: 'denim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cinetype: 'cinetype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.46;
  --tracking-caption: -0.13px;
  --text-body: 14px;
  --leading-body: 1.17;
  --tracking-body: 0.17px;
  --text-heading: 20px;
  --leading-heading: 1.19;
  --tracking-heading: 0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.29;
  --tracking-heading-lg: 0.38px;
  --text-display: 48px;
  --leading-display: 1.35;
  --tracking-display: 0.58px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 42px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 12px;
  --radius-default: 4px;
  --radius-heroelement: 18px;
  --radius-circularelements: 9999px;

  /* Shadows */
  --shadow-sm: rgba(9, 53, 45, 0.05) 0px 5px 6px -4px, rgba(174, 202, 197, 0.08) 0px 1px 1px 0.5px;
  --shadow-subtle: rgb(202, 211, 210) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgb(64, 68, 66) 0px 0px 0px 0.5px inset;
  --shadow-subtle-3: rgb(224, 229, 229) 0px -0.5px 0px 0px inset;
  --shadow-md: rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, 0.04) 0px 0px 5.5px -0.5px;
  --shadow-sm-2: rgba(0, 0, 0, 0.25) 0px 5px 5px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.1) 0px 5px 7.5px -5px;
  --shadow-md-2: rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, 0.04) 0px 0px 5.5px -0.5px, rgb(224, 229, 229) 0px 0px 0px 0.5px inset;

  /* Surfaces */
  --surface-canvas-fog: #e0e0e0;
  --surface-ghostly-gray: #ffffff;
  --surface-light-panel-card: #f7f7f7;
  --surface-dark-inset-card: #1a191a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-fog: #e0e0e0;
  --color-inkwell: #29211e;
  --color-ghostly-gray: #ffffff;
  --color-shadowed-steel: #453b41;
  --color-ash-outline: #e5e5e5;
  --color-verdant-text: #09352e;
  --color-primary-green: #85c093;
  --color-lively-green: #117025;
  --color-deep-moss: #007010;
  --color-subtle-green-tint: #77aa83;
  --color-accent-violet: #433787;

  /* Typography */
  --font-muoto: 'muoto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-denim: 'denim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cinetype: 'cinetype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.46;
  --tracking-caption: -0.13px;
  --text-body: 14px;
  --leading-body: 1.17;
  --tracking-body: 0.17px;
  --text-heading: 20px;
  --leading-heading: 1.19;
  --tracking-heading: 0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.29;
  --tracking-heading-lg: 0.38px;
  --text-display: 48px;
  --leading-display: 1.35;
  --tracking-display: 0.58px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-sm: rgba(9, 53, 45, 0.05) 0px 5px 6px -4px, rgba(174, 202, 197, 0.08) 0px 1px 1px 0.5px;
  --shadow-subtle: rgb(202, 211, 210) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgb(64, 68, 66) 0px 0px 0px 0.5px inset;
  --shadow-subtle-3: rgb(224, 229, 229) 0px -0.5px 0px 0px inset;
  --shadow-md: rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, 0.04) 0px 0px 5.5px -0.5px;
  --shadow-sm-2: rgba(0, 0, 0, 0.25) 0px 5px 5px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.1) 0px 5px 7.5px -5px;
  --shadow-md-2: rgba(8, 18, 17, 0.01) 0px 0px 16px -1px, rgba(8, 18, 17, 0.04) 0px 0px 5.5px -0.5px, rgb(224, 229, 229) 0px 0px 0px 0.5px inset;
}
```
