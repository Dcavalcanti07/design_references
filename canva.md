# Canva — Style Reference
> Vibrant creative toolkit on a clean canvas.

**Theme:** light

Canva's design language feels like a playful yet precise creative toolkit, balancing vibrant gradients with a clean, functional interface. The primary visual tension arises from the geometric purity of most elements against the expressive, colorful gradients used for marketing sections and hero backgrounds. A crisp achromatic base palette allows the vivid, multi-hued gradients to act as focal points, signaling creative potential. This is reinforced by the consistent use of a custom sans-serif typeface, Canva Sans, which maintains readability even across diverse backgrounds.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, default foreground for most UI components, card backgrounds for feature cards. |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, critical headings, borders for ghost buttons and text links. |
| Midnight Graphite | `#0f1015` | `--color-midnight-graphite` | Darkest card backgrounds, background for various UI elements in feature sections, text on light backgrounds. |
| Storm Gray | `#575a5f` | `--color-storm-gray` | Secondary text, muted interactive elements, button text on lighter backgrounds, borders for some interactive components. |
| Porcelain Accent | `#d7d9de` | `--color-porcelain-accent` | Subtle border accents, box shadows for elevated elements. |
| Canva Violet | `#8b3dff` | `--color-canva-violet` | Primary action background, links, accents for interactive states. |
| Subtle Violet | `#a370fc` | `--color-subtle-violet` | Decorative borders, secondary link accents. |
| Deep Violet | `#9729ff` | `--color-deep-violet` | Fills for icons and decorative elements, borders in specific UI contexts. |
| Coral Glow | `#ff6105` | `--color-coral-glow` | Accent for status indicators, small icons, highlight elements. |
| Passion Red | `#ff3d4d` | `--color-passion-red` | Accent for status indicators, small icons, highlight elements. |
| Fuchsia Pop | `#e950f7` | `--color-fuchsia-pop` | Accent for status indicators, small icons, highlight elements. |
| Hero Aqua-Violet Gradient | `linear-gradient(135deg, rgb(0, 196, 204), rgb(125, 42, 232))` | `--color-hero-aqua-violet-gradient` | Primary hero section background, providing a dynamic and inviting visual entry point. |
| Multi-Spectrum Gradient | `linear-gradient(rgb(153, 43, 255), rgb(90, 50, 250) 222px, rgb(19, 163, 181) 375px, rgb(147, 232, 246) 60%, rgb(255, 255, 255))` | `--color-multi-spectrum-gradient` | Complex background fills for large marketing areas, representing creative diversity. |

## Tokens — Typography

### Times — System fallback text. Used for very small labels or browser-default elements when Canva Sans is unavailable or explicitly overridden. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.20
- **Role:** System fallback text. Used for very small labels or browser-default elements when Canva Sans is unavailable or explicitly overridden.

### Canva Sans — Primary brand typeface for all headings, body text, and UI elements. Its strong yet approachable geometric forms convey professionalism without being overly formal, especially at larger sizes. · `--font-canva-sans`
- **Substitute:** ui-sans-serif, system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 21px, 24px, 28px, 32px, 36px, 56px, 64px, 84px
- **Line height:** 1.06, 1.10, 1.25, 1.33, 1.38, 1.40, 1.50, 1.57
- **Letter spacing:** -1.512, -1.008, -0.648, -0.576, -0.504, -0.432, -0.378, -0.324, -0.16, -0.14
- **OpenType features:** `"ss02" on, "ss03"`
- **Role:** Primary brand typeface for all headings, body text, and UI elements. Its strong yet approachable geometric forms convey professionalism without being overly formal, especially at larger sizes.

### Arial — System fallback or context-specific UI text. Appears in some button and body contexts, ensuring readability on a variety of systems. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** System fallback or context-specific UI text. Appears in some button and body contexts, ensuring readability on a variety of systems.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.57 | -0.14px | `--text-body-sm` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 18px | 1.4 | -0.324px | `--text-subheading` |
| heading-sm | 21px | 1.38 | -0.378px | `--text-heading-sm` |
| heading | 24px | 1.33 | -0.432px | `--text-heading` |
| display-md | 32px | 1.1 | -0.576px | `--text-display-md` |
| display-lg | 36px | 1.06 | -0.648px | `--text-display-lg` |
| display-xl | 56px | 1.06 | -1.008px | `--text-display-xl` |
| display-2xl | 64px | 1.06 | -1.152px | `--text-display-2xl` |
| display-3xl | 84px | 1.06 | -1.512px | `--text-display-3xl` |

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
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| default | 8px |
| buttonsIcon | 48px |
| buttonsLarge | 9999px |
| buttonsSmall | 8px |
| interactiveElements | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(64, 79, 109, 0.06) 0px 0px 0px 0.5px, rgba(24, 44, 8...` | `--shadow-subtle` |
| subtle-2 | `rgba(53, 65, 90, 0.2) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 54px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Filled White Button
**Role:** Call to action, primary navigation elements.

backgroundColor: rgba(255, 255, 255, 0.898), color: rgb(15, 16, 21), borderColor: rgb(15, 16, 21), borderRadius: 8px, padding: 0px 12px.

### Ghost White Button
**Role:** Secondary calls to action, navigation overlays.

backgroundColor: rgba(255, 255, 255, 0), color: rgb(255, 255, 255), borderColor: rgb(255, 255, 255), borderRadius: 8px, padding: 4px 8px.

### Pill Ghost Black Button
**Role:** Subtle interactive elements, filter chips, category selectors.

backgroundColor: rgba(0, 0, 0, 0), color: rgb(0, 0, 0), borderColor: rgb(0, 0, 0), borderRadius: 9999px, padding: 16px 24px.

### Ghost Dark Button
**Role:** Secondary interactive elements, internal navigation in dark sections.

backgroundColor: rgba(15, 16, 21, 0), color: rgb(15, 16, 21), borderColor: rgb(15, 16, 21), borderRadius: 8px, padding: 0px 16px.

### Dark Feature Card
**Role:** Content containers for prominent features or sections.

backgroundColor: rgb(15, 16, 21), borderRadius: 8px, boxShadow: none, padding: 0px.

### Call to Action Button (Canva Violet)
**Role:** Primary action button across the site.

backgroundColor: #8b3dff, color: #ffffff, borderRadius: 8px, padding: 16px 24px.

### Tool Selector Chip
**Role:** Categorization or feature selection within a section.

backgroundColor: #ffffff, color: #0f1015, borderRadius: 9999px, padding: 4px 12px; with interior icons often using accent colors like #E950F7.

## Do's and Don'ts

### Do
- Use Canva Sans for all typographic elements, prioritizing weight 400 for body text, 500 for subheadings, and 600 for main headings.
- Apply a default border-radius of 8px to cards and most interactive elements to maintain visual consistency.
- Utilize '#8b3dff' (Canva Violet) exclusively for primary calls to action, ensuring prominence and brand recognition.
- Pair text on '#0f1015' (Midnight Graphite) backgrounds with '#ffffff' (Canvas White) for optimal contrast and readability.
- Employ the Hero Aqua-Violet Gradient (`linear-gradient(135deg, rgb(0, 196, 204), rgb(125, 42, 232))`) for impactful hero sections or large graphical backgrounds.
- Use 4px as the base unit for all spacing, ensuring consistent gaps between small elements and padding within components.
- Apply the letterSpacing from Canva Sans where specified, such as -0.018em for larger headlines, to fine-tune visual flow.

### Don't
- Avoid using Times or Arial as primary display fonts; they are for system fallback only and do not match the brand's expressive aesthetic.
- Do not deviate from the specified vibrant accent colors (#ff6105, #ff3d4d, #e950f7) for small icons or highlighted elements, to prevent visual dissonance.
- Do not introduce new shadow patterns; adhere to the established box-shadow values like `rgba(64, 79, 109, 0.06) 0px 0px 0px 0.5px, rgba(24, 44, 89, 0.137) 0px 2px 4px 0px, rgba(24, 44, 89, 0.07) 0px 6px 12px 0px` for subtle elevation.
- Do not use '#0f1015' (Midnight Graphite) for primary calls to action; reserve it for card backgrounds and secondary interactive states.
- Do not use generic pill shapes; reserve `9999px` radius specifically for filter chips and distinct interactive elements labeled as pill buttons.
- Do not introduce arbitrary color choices; all colors for interactive elements, backgrounds, and text must derive from the defined palette.
- Avoid excessive use of vivid chromatic colors outside of designated gradients or small accent elements, to maintain a balanced and clean interface.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default light surfaces. |
| 1 | Midnight Graphite | `#0f1015` | Dominant background for elevated feature cards and other content blocks, creating visual distinction during marketing flows. |
| 2 | Canva Violet | `#8b3dff` | Background for primary interactive elements, some hero section content, and accent areas, introducing brand color as an elevated visual layer. |

## Elevation

- **Card/UI Component:** `rgba(64, 79, 109, 0.06) 0px 0px 0px 0.5px, rgba(24, 44, 89, 0.137) 0px 2px 4px 0px, rgba(24, 44, 89, 0.07) 0px 6px 12px 0px`
- **Button (Inset Focus):** `rgba(53, 65, 90, 0.2) 0px 0px 0px 1px inset`
- **Button (Inset Light Focus):** `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset`

## Imagery

The visual language for imagery is a mix of product screenshots, stylized illustrations, and abstract gradient graphics. Product screens are often tightly cropped on pure white or contained within dark cards, showcasing the UI directly without much context. Illustrations and abstract graphics lean into a vivid, multi-hued gradient palette, often featuring organic or softly geometric shapes. Icons are typically filled, utilizing the brand's accent colors or a neutral achromatic palette, and serve both decorative and functional roles. The overall density is balanced, allowing prominent imagery or gradients to capture attention while text remains readable, contributing to an inviting and creative atmosphere.

## Layout

The page model is primarily a max-width contained layout, with content centered within a clear horizontal boundary. However, the hero section utilizes a full-bleed gradient background that extends edge-to-edge, drawing the user in immediately. Sections below the hero frequently feature alternating patterns: a centered headline followed by a horizontal array of cards or a split text-left/image-right (or gradient-graphic-right) arrangement. Card grids are prominent for showcasing features or templates, primarily using 2 or 3 columns. The layout balances spacious breathing room, especially around major headlines and section breaks, with denser information blocks presented in cards. Navigation is a sticky top bar with a clear brand logo and prominent 'Sign up' and 'Log in' calls to action.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #d7d9de
accent: #8b3dff
primary action: #8b3dff (filled action)

Example Component Prompts:
1. Create a Call to Action Button: 'Start designing' text, font Canva Sans weight 400, #ffffff color. Background #8b3dff, 8px radius, 16px 24px padding.
2. Create a Hero Headline: 'What will you design today?' text, font Canva Sans weight 600, #ffffff color, 64px size, 1.06 lineHeight, letter-spacing -1.152px. Set against Hero Aqua-Violet Gradient background (linear-gradient(135deg, rgb(0, 196, 204), rgb(125, 42, 232))).
3. Create a Dark Feature Card: 'Turn conversation into creation with Canva AI 2.0' as a display-lg heading at top, font Canva Sans weight 600, #ffffff color. Background #0f1015, 8px radius, 12px padding. Include a 'Explore Canva AI' button (Ghost White Button variant) within, font Canva Sans 14px, #ffffff color, 4px 8px padding, 8px radius, 1px white border.
4. Create a Tool Selector Chip: 'AI' text, font Canva Sans 14px, #0f1015 color. Background #ffffff, 9999px radius, 4px 12px padding. Include a small icon to its left using the Fuchsia Pop color (#e950f7) as fill.

## Similar Brands

- **Figma** — Clean SaaS UI with strong brand color accents and a focus on product screenshots within the interface.
- **Adobe Express** — Similar market, vibrant marketing gradients contrasted with a functional, inviting UI.
- **Notion** — Effective use of a custom sans-serif font for brand identity and clear information hierarchy in a clean interface.
- **Mailchimp** — Playful yet structured design, combining custom typography with colorful illustrations and a clear content hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-midnight-graphite: #0f1015;
  --color-storm-gray: #575a5f;
  --color-porcelain-accent: #d7d9de;
  --color-canva-violet: #8b3dff;
  --color-subtle-violet: #a370fc;
  --color-deep-violet: #9729ff;
  --color-coral-glow: #ff6105;
  --color-passion-red: #ff3d4d;
  --color-fuchsia-pop: #e950f7;
  --color-hero-aqua-violet-gradient: #00c4cc;
  --gradient-hero-aqua-violet-gradient: linear-gradient(135deg, rgb(0, 196, 204), rgb(125, 42, 232));
  --color-multi-spectrum-gradient: #992bff;
  --gradient-multi-spectrum-gradient: linear-gradient(rgb(153, 43, 255), rgb(90, 50, 250) 222px, rgb(19, 163, 181) 375px, rgb(147, 232, 246) 60%, rgb(255, 255, 255));

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-canva-sans: 'Canva Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.324px;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.378px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.432px;
  --text-display-md: 32px;
  --leading-display-md: 1.1;
  --tracking-display-md: -0.576px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.06;
  --tracking-display-lg: -0.648px;
  --text-display-xl: 56px;
  --leading-display-xl: 1.06;
  --tracking-display-xl: -1.008px;
  --text-display-2xl: 64px;
  --leading-display-2xl: 1.06;
  --tracking-display-2xl: -1.152px;
  --text-display-3xl: 84px;
  --leading-display-3xl: 1.06;
  --tracking-display-3xl: -1.512px;

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
  --spacing-32: 32px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 54px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-default: 8px;
  --radius-buttonsicon: 48px;
  --radius-buttonslarge: 9999px;
  --radius-buttonssmall: 8px;
  --radius-interactiveelements: 16px;

  /* Shadows */
  --shadow-subtle: rgba(64, 79, 109, 0.06) 0px 0px 0px 0.5px, rgba(24, 44, 89, 0.137) 0px 2px 4px 0px, rgba(24, 44, 89, 0.07) 0px 6px 12px 0px;
  --shadow-subtle-2: rgba(53, 65, 90, 0.2) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-midnight-graphite: #0f1015;
  --surface-canva-violet: #8b3dff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-midnight-graphite: #0f1015;
  --color-storm-gray: #575a5f;
  --color-porcelain-accent: #d7d9de;
  --color-canva-violet: #8b3dff;
  --color-subtle-violet: #a370fc;
  --color-deep-violet: #9729ff;
  --color-coral-glow: #ff6105;
  --color-passion-red: #ff3d4d;
  --color-fuchsia-pop: #e950f7;
  --color-hero-aqua-violet-gradient: #00c4cc;
  --color-multi-spectrum-gradient: #992bff;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-canva-sans: 'Canva Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.324px;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.378px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.432px;
  --text-display-md: 32px;
  --leading-display-md: 1.1;
  --tracking-display-md: -0.576px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.06;
  --tracking-display-lg: -0.648px;
  --text-display-xl: 56px;
  --leading-display-xl: 1.06;
  --tracking-display-xl: -1.008px;
  --text-display-2xl: 64px;
  --leading-display-2xl: 1.06;
  --tracking-display-2xl: -1.152px;
  --text-display-3xl: 84px;
  --leading-display-3xl: 1.06;
  --tracking-display-3xl: -1.512px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(64, 79, 109, 0.06) 0px 0px 0px 0.5px, rgba(24, 44, 89, 0.137) 0px 2px 4px 0px, rgba(24, 44, 89, 0.07) 0px 6px 12px 0px;
  --shadow-subtle-2: rgba(53, 65, 90, 0.2) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset;
}
```
