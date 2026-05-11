# Depot — Style Reference
> Deep space console: focused intensity.

**Theme:** dark

Depot’s aesthetic is a high-contrast dark mode, evoking a command center's precision. Deep, near-black backgrounds frame content, punctuated by vivid green accents that immediately draw the eye to critical interactive elements. A subtle progression of dark grays creates layered surfaces, adding depth and structure without reliance on heavy shadows. The overall impression is one of efficiency and focused power without distraction, like a purpose-built tool designed for speed.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon Black | `#04040b` | `--color-carbon-black` | Primary page background, default text color on light elements. |
| Night Sky | `#121113` | `--color-night-sky` | Card backgrounds, section dividers, slightly elevated surfaces. |
| Ash Gray | `#323035` | `--color-ash-gray` | Button backgrounds, form inputs, secondary content containers. |
| Storm Gray | `#3c393f` | `--color-storm-gray` | Border colors, subtle dividers, inactive states. |
| Cloud Burst | `#b5b2bc` | `--color-cloud-burst` | Secondary text, subtle icon fill, placeholder text. |
| Snow Drift | `#eeeef0` | `--color-snow-drift` | Primary text on dark backgrounds, active states for text and icons. |
| Terminal Green | `#71d083` | `--color-terminal-green` | Call-to-action text, primary interactive element highlights, success states. |
| Canopy Green | `#366740` | `--color-canopy-green` | Call-to-action button backgrounds when paired with Terminal Green text, active indicators. |
| Link Blue | `#70b8ff` | `--color-link-blue` | Hyperlinks, secondary interactive text. |
| Twilight Purple | `#473876` | `--color-twilight-purple` | Border accents for specialized cards or highlight elements. |
| Crimson Spark | `#ff9592` | `--color-crimson-spark` | Alerts or error states, used sparingly for emphasis. |
| Green Burst Gradient | `linear-gradient(to right in oklab, rgba(0, 0, 0, 0) 0%, rgb(70, 167, 88) 50%, rgba(0, 0, 0, 0) 100%)` | `--color-green-burst-gradient` | Decorative hero background accent, draws focus to key sections. |
| Radial Glow Gradient | `radial-gradient(70% 50%, rgba(100, 200, 120, 0.06), rgba(0, 0, 0, 0))` | `--color-radial-glow-gradient` | Subtle background glow for featured content blocks. |

## Tokens — Typography

### Red Hat Display Variable — Headlines and prominent display text. The tight letter-spacing gives a modern, compressed feel, making large text feel sharp and precise. · `--font-red-hat-display-variable`
- **Substitute:** Segoe UI, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 36px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.38, 1.40, 1.50
- **Letter spacing:** -0.0250em
- **Role:** Headlines and prominent display text. The tight letter-spacing gives a modern, compressed feel, making large text feel sharp and precise.

### Red Hat Text Variable — Body copy, navigation, buttons, and most UI elements. The slightly expanded letter-spacing provides excellent readability on dark backgrounds. · `--font-red-hat-text-variable`
- **Substitute:** Roboto, Arial, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.00, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** 0.0250em
- **Role:** Body copy, navigation, buttons, and most UI elements. The slightly expanded letter-spacing provides excellent readability on dark backgrounds.

### Red Hat Mono Variable — Code snippets, technical details, and specific data displays. Its monospace nature ensures alignment for structured information. · `--font-red-hat-mono-variable`
- **Substitute:** SFMono-Regular, monospace
- **Weights:** 400
- **Sizes:** 14px, 18px
- **Line height:** 1.43, 1.56
- **Role:** Code snippets, technical details, and specific data displays. Its monospace nature ensures alignment for structured information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.25px | `--text-caption` |
| body | 14px | 1.43 | 0.35px | `--text-body` |
| heading | 20px | 1.33 | -0.5px | `--text-heading` |
| heading-lg | 36px | 1.11 | -0.9px | `--text-heading-lg` |
| display | 60px | 1 | -1.5px | `--text-display` |

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
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| buttons | 6px |
| default | 6px |
| smallElements | 2px |
| interactiveElements | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Filled button for primary actions. Background `Canopy Green` (#366740), text `Terminal Green` (#71d083), border `Canopy Green` (#366740). Rounded corners at 10px.

### Secondary Action Button
**Role:** Secondary call to action

Ghost button with `Carbon Black` (#04040b) background, `Snow Drift` (#eeeef0) text, and `Storm Gray` (#3c393f) border. Rounded corners at 6px. Padding: 16px vertical, 16px horizontal.

### Tertiary Ghost Button
**Role:** Mildly emphasized action

Transparent background button (`rgba(0, 0, 0, 0)`), `Cloud Burst` (#b5b2bc) text, no visible border (`oklch(0.922 0 0)`). Radius 4px. Padding: 8px vertical, 12px horizontal.

### Navigation Link Button
**Role:** Navigation and internal links

Minimal button for navigation. Background `Ash Gray` (#323035), text `Snow Drift` (#eeeef0), no explicit border. Sharp corners (0px radius). Padding: 20px all sides. Used in header/footer.

### Feature Card
**Role:** Content grouping

Card with `Night Sky` (#121113) background, a subtle inset shadow (`rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset`), and `Ash Gray` (#323035) border. 6px border radius. Internal padding likely 16px.

### Highlight Badge
**Role:** Small, informative label

Small, informative badge with `Canopy Green` (#366740) background, `Terminal Green` (#71d083) text, and `Storm Gray` (#3c393f) border. Rounded corners at 10px. Padding 12px vertical, 16px horizontal for text `Red Hat Text Variable` 16px.

### Hero Headline
**Role:** Primary page title

Uses `Red Hat Display Variable` at 60px size, weights 600 or 700, with `Snow Drift` (#eeeef0) color and tight letter-spacing -0.0250em.

### Secondary Headline
**Role:** Section titles

Uses `Red Hat Display Variable` at 36px size, weights 400 or 500, with `Snow Drift` (#eeeef0) color and tight letter-spacing -0.0250em.

## Do's and Don'ts

### Do
- Use `Carbon Black` (#04040b) for primary page backgrounds to maintain a consistent dark theme.
- Apply `Canopy Green` (#366740) for all primary call-to-action button backgrounds, paired with `Terminal Green` (#71d083) text.
- Implement 6px border radius as the default for most interface elements, with 10px used for key interactive elements like primary buttons.
- Ensure `Red Hat Text Variable` with 0.0250em letter-spacing is used for all body text and secondary UI elements for optimal legibility.
- Maintain a clear visual hierarchy using `Red Hat Display Variable` for headlines, particularly with its tight -0.0250em letter-spacing to distinguish it from body copy.
- Utilize `Ash Gray` (#323035) for button backgrounds and secondary content blocks to create subtle elevation on dark surfaces.

### Don't
- Avoid using bright, high-saturation colors for large background areas; colors like `Terminal Green` (#71d083) are strictly for accents and interactive elements.
- Do not deviate from the specified letter-spacing values across `Red Hat Display Variable` and `Red Hat Text Variable` as they are integral to the system's character.
- Avoid excessive use of shadows; the system relies on layer colors (`Night Sky`, `Ash Gray`) and subtle inset shadows for depth.
- Do not introduce new typefaces; `Red Hat Display`, `Red Hat Text`, and `Red Hat Mono` are the only approved families.
- Refrain from using color in body text that does not meet the specified `Snow Drift` (#eeeef0) or `Cloud Burst` (#b5b2bc) for readability against dark backgrounds.
- Do not use generic square or fully rounded (pill) shapes; adhere to the 6px and 10px radii for a consistent, structured appearance.

## Elevation

- **Feature Card:** `rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset`

## Imagery

This design primarily uses product screenshots and brand-colored illustrations. Product screenshots are typically contained within card-like structures, showing UI elements and code, often with a subtle `Terminal Green` (#71d083) highlight to draw attention to key features. Illustrations are flat, geometric, and follow the brand's green and dark gray palette, used decoratively to break up sections or emphasize concepts, rather than depicting real-world scenarios. Small, mono-color icons, usually `Snow Drift` (#eeeef0) or `Terminal Green` (#71d083), are extensively used to denote features, actions, and navigation elements. The overall density of imagery is balanced, supporting the text-heavy technical content without overwhelming it, acting as visual cues rather than dominant storytelling elements.

## Layout

The layout is predominantly full-bleed dark, with content constrained within a centered max-width, though the exact `pageMaxWidth` is not explicitly defined it appears to allow generous negative space. The hero section features a centered headline over a dark background, with clear calls to action below. Sections are visually distinct, often with solid color backgrounds for separation, like the alternating `Night Sky` (#121113) and `Carbon Black` (#04040b) sections. Content is frequently arranged in two-column layouts, with text and descriptions on one side and a visual (code example, product screenshot, or illustration) on the other. A structured card grid appears for feature showcases. The navigation is a sticky top bar, providing persistent access to key links.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#eeeef0` (Snow Drift)
- Background: `#04040b` (Carbon Black)
- CTA Background: `#366740` (Canopy Green)
- CTA Text: `#71d083` (Terminal Green)
- Border: `#3c393f` (Storm Gray)
- Secondary Text: `#b5b2bc` (Cloud Burst)

### 3-5 Example Component Prompts
1. **Create a Hero Section**: Background `Carbon Black` (#04040b). Headline: 'Build faster. Waste less time.' using `Red Hat Display Variable` at 60px, weight 700, color `Snow Drift` (#eeeef0), letter-spacing -1.5px. Below, a `Primary Action Button` with text 'Get started'.
2. **Generate a Feature Card**: Background `Night Sky` (#121113), with a `Storm Gray` (#3c393f) border and 6px border-radius. Include a subtle inset shadow: `rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset`. Content text should use `Snow Drift` (#eeeef0) with `Red Hat Text Variable` 16px, letter-spacing 0.4px.
3. **Design a Navigation Bar**: Background same as page, `Carbon Black` (#04040b). Navigation links use `Cloud Burst` (#b5b2bc) text (e.g., 'Products', 'Resources'), `Red Hat Text Variable` 16px. Include two right-aligned buttons: a `Navigation Link Button` for 'Sign In' and a `Primary Action Button` for 'Get started'.
4. **Display a Code Block**: Background `Night Sky` (#121113), text `Cloud Burst` (#b5b2bc), using `Red Hat Mono Variable` 14px. Ensure code line spacing is 1.43, with no letter-spacing. Use 6px border-radius for the block.

## Similar Brands

- **Vercel** — Shares a high-contrast dark theme with a vibrant accent color (Vercel uses purple, Depot uses green) for interactive elements and highlights, conveying a technical and developer-focused aesthetic.
- **GitHub** — Employs a clear, structured dark mode with monospace typography for code elements, echoing Depot’s emphasis on developer tools and information density.
- **Linear** — Uses a precise dark UI with subtle background variations for layering and a single, strong accent color, similar to Depot’s approach to visual hierarchy without heavy shadows.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon-black: #04040b;
  --color-night-sky: #121113;
  --color-ash-gray: #323035;
  --color-storm-gray: #3c393f;
  --color-cloud-burst: #b5b2bc;
  --color-snow-drift: #eeeef0;
  --color-terminal-green: #71d083;
  --color-canopy-green: #366740;
  --color-link-blue: #70b8ff;
  --color-twilight-purple: #473876;
  --color-crimson-spark: #ff9592;
  --color-green-burst-gradient: #46a758;
  --gradient-green-burst-gradient: linear-gradient(to right in oklab, rgba(0, 0, 0, 0) 0%, rgb(70, 167, 88) 50%, rgba(0, 0, 0, 0) 100%);
  --color-radial-glow-gradient: #64c878;
  --gradient-radial-glow-gradient: radial-gradient(70% 50%, rgba(100, 200, 120, 0.06), rgba(0, 0, 0, 0));

  /* Typography — Font Families */
  --font-red-hat-display-variable: 'Red Hat Display Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-text-variable: 'Red Hat Text Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-mono-variable: 'Red Hat Mono Variable', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.25px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.35px;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --tracking-heading: -0.5px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.9px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-buttons: 6px;
  --radius-default: 6px;
  --radius-smallelements: 2px;
  --radius-interactiveelements: 10px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon-black: #04040b;
  --color-night-sky: #121113;
  --color-ash-gray: #323035;
  --color-storm-gray: #3c393f;
  --color-cloud-burst: #b5b2bc;
  --color-snow-drift: #eeeef0;
  --color-terminal-green: #71d083;
  --color-canopy-green: #366740;
  --color-link-blue: #70b8ff;
  --color-twilight-purple: #473876;
  --color-crimson-spark: #ff9592;
  --color-green-burst-gradient: #46a758;
  --color-radial-glow-gradient: #64c878;

  /* Typography */
  --font-red-hat-display-variable: 'Red Hat Display Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-text-variable: 'Red Hat Text Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-mono-variable: 'Red Hat Mono Variable', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.25px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.35px;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --tracking-heading: -0.5px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.9px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.5px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.06) 0px 1px 0px 0px inset;
}
```
