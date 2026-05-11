# Liveblocks — Style Reference
> Midnight data stream. Dark surfaces meet sharp textual readouts and subtle, glowing accents.

**Theme:** dark

This design evokes a high-tech control room aesthetic, blending deep darkness with minimalist precision. Dominant #000000 backgrounds create an immersive, focused environment. Subtle gradients and white text act as illuminated data readouts, while crisp, achromatic grays define interactive elements and containers, maintaining visual order. The interplay of clean typography and precise component definition projects an image of robust, technical reliability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page backgrounds, significant section backgrounds and containers. |
| Ghostly White | `#ffffff` | `--color-ghostly-white` | Primary text, visible borders, icons, and interactive elements. Its high contrast on dark backgrounds drives readability. |
| Graphite Base | `#111111` | `--color-graphite-base` | Secondary backgrounds, subtle elevated surfaces within dark sections. |
| Ash Gray | `#918d8d` | `--color-ash-gray` | Muted text, secondary button text, inactive icons – providing support without competing with primary content. |
| Light Concrete | `#edecee` | `--color-light-concrete` | Subtle light backgrounds for specific sections or elements, offering visual relief against darker tones. |
| Distant Gray | `#b7b4b4` | `--color-distant-gray` | Tertiary text, subtle separators, and less prominent UI elements. |
| Slate Text | `#635f5f` | `--color-slate-text` | Secondary text for details and supplementary information. |
| Digital Blue | `#0090ff` | `--color-digital-blue` | Call-to-action buttons, primary interactive elements – a vivid hue that stands out within the dark palette. |
| Cosmic Violet | `#9f8dfc` | `--color-cosmic-violet` | Accent color for specific UI indicators, links, or highlighted information, adding a touch of digital luminescence. |
| System Teal | `#70e1c8` | `--color-system-teal` | Secondary accent for interactive states or status indicators, balancing the violet with a cool, technological feel. |
| Terminal Red | `#f76e99` | `--color-terminal-red` | Subtle accent for highlighted information or specific UI elements where an alert or active state is needed. |
| Void Radiance | `radial-gradient(50% 50%, lab(0 0 0) 90%, oklch(0.07 0 0) 95%, oklch(0.2 0 0) 97%, oklch(0.3 0 0) 100%)` | `--color-void-radiance` | Subtle background gradient for background elements, providing a deep, immersive feel without harsh lines. |

## Tokens — Typography

### suisse — Primary typeface for all UI elements, headings, body text, and navigation. Its condensed nature at smaller sizes paired with expansive line heights for headlines creates a modern, precise feel. The use of custom letter-spacing across different sizes provides refined typographic control. · `--font-suisse`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 10px, 11px, 12px, 14px, 16px, 20px, 24px, 32px, 48px, 52px, 60px, 64px
- **Line height:** 1.00, 1.05, 1.10, 1.20, 1.25, 1.33, 1.38, 1.43, 1.50
- **Letter spacing:** -0.0200em, -0.0100em, 0.0040em, 0.0060em, 0.0100em, 0.0250em
- **Role:** Primary typeface for all UI elements, headings, body text, and navigation. Its condensed nature at smaller sizes paired with expansive line heights for headlines creates a modern, precise feel. The use of custom letter-spacing across different sizes provides refined typographic control.

### JetBrains Mono — Monospaced font for code snippets, technical details, and any output requiring precise alignment. Its uniform character width reinforces the data-driven aesthetic. · `--font-jetbrains-mono`
- **Substitute:** monospace
- **Weights:** 400, 500
- **Sizes:** 10px, 14px
- **Line height:** 1.00, 1.43
- **Letter spacing:** 0.0250em
- **Role:** Monospaced font for code snippets, technical details, and any output requiring precise alignment. Its uniform character width reinforces the data-driven aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | 0.25px | `--text-caption` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 32px | 1.25 | -0.02px | `--text-heading-lg` |
| display | 48px | 1.2 | -0.02px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 196 | 196px | `--spacing-196` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 12px |
| buttons | 6px |
| default | 4px |
| containers | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(39, 38, 38) 0px 0px 0px 1px` | `--shadow-subtle` |
| subtle-2 | `color(srgb 0.925333 0.925333 0.925333) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Navigation Link
**Role:** Interactive elements in the header and footers.

Text in Ghostly White (#ffffff) on Midnight Void (#000000) background, with a 6px border radius, 4px padding on all sides. On hover, text color remains white, but an underline might appear (not fully specified).

### Primary Ghost Button
**Role:** Secondary call-to-action.

Transparent background (rgba(0, 0, 0, 0)), Ghostly White (#ffffff) text color, with a matching border of 6px radius. Padding is 8px top/bottom, 12px left/right. Provides a clear secondary action without competing with primary CTAs.

### Primary Filled Button
**Role:** Main call-to-action.

Midnight Void (#000000) background, Ghostly White (#ffffff) text. No visible border initially, 8px border radius. Padding is 0px top/bottom, 16px left/right. High contrast and solid fill for prominent action.

### Text Link Button
**Role:** Inline or subordinate actions.

Transparent background, Ash Gray (#918d8d) text. No border, no specific radius. Padding 0px top/bottom, 16px left/right. Used for simple navigation or supplementary actions.

### Tag / Badge
**Role:** Categorization or small status indicators.

Dark background (rgba(0,0,0,0) with some examples), Ash Gray (#918d8d) text. 6px border radius, 4px padding. Often appears with a 1px border matching text color for definition.

### Feature Card
**Role:** Container for showcasing features or content blocks.

Uses Graphite Base (#111111) for background. Padding of 16px on all sides. Features a 4px border radius for a subtle rounded edge against the sharp overall aesthetic. Text and interactive elements within will use Ghostly White or Ash Gray.

### Inline Code Block
**Role:** Displaying short code snippets.

JetBrains Mono font, 14px size, Ghostly White (#ffffff) text. Contained within surrounding text, with a subtle background and border to differentiate it.

## Do's and Don'ts

### Do
- Prioritize Midnight Void (#000000) as the primary background for full-bleed sections, establishing the dark aesthetic.
- Use Ghostly White (#ffffff) for all primary text elements, ensuring maximum contrast and readability on dark backgrounds.
- Apply Digital Blue (#0090ff) exclusively to primary call-to-action buttons for clear visual hierarchy and impact.
- Maintain 6px as the standard border radius for interactive elements like buttons and tags, with containers using 8px.
- Utilize the Suisse font for all headings and body text, varying weights (400, 500) and sizes according to the type scale.
- Incorporate specific letter-spacing values (-0.0200em to 0.0250em) derived from the Suisse font profile for precise typographic control.
- Employ JetBrains Mono for all code snippets and technical text to clearly distinguish it from UI copy.

### Don't
- Avoid introducing additional saturated colors beyond Digital Blue, Cosmic Violet, System Teal, and Terminal Red to preserve the controlled palette.
- Do not use high-saturation colors for large background areas or extensive textual content; reserve them for accents and interactive states.
- Refrain from using strong, opaque shadows; utilize the provided rgb(39, 38, 38) 0px 0px 0px 1px for subtle outlining only.
- Do not deviate from the defined border radii; maintain 6px for buttons and 8px for containers to ensure visual consistency.
- Avoid using decorative fonts or excessive font variations that would disrupt the precise and technical typographic identity.
- Do not add unnecessary padding or margin around elements; adhere to the compact spacing tokens (e.g., 8px element gap, 16px card padding) for content density.
- Never use red as a primary success indicator, as its allocated role as 'Terminal Red' is for specific accents.

## Elevation

- **Subtle Outline:** `rgb(39, 38, 38) 0px 0px 0px 1px`
- **Inset Focus/Active:** `color(srgb 0.925333 0.925333 0.925333) 0px 0px 0px 1px inset`

## Imagery

This design primarily utilizes dark-themed, abstract visuals and product screenshots. Product screenshots are typically full-bleed, showcasing the UI of the 'Liveblocks' product, often with a slightly distorted, vibrant magenta/pink gradient or pattern as a background element. These graphical backdrops provide a raw, energetic contrast to the otherwise structured UI. Illustrations are minimal and functional, acting as icons or small annotations. Photography is absent. The overall visual language for imagery is one of showing the product in action against a dynamic, abstract backdrop that hints at data and energy. Iconography is primarily monochromatic, using Ghostly White or Ash Gray outlines or fills, maintaining the precise and clean UI aesthetic.

## Layout

The page primarily employs a max-width contained layout, centering content within a 1280px constraint, though the hero section frequently uses a full-bleed dark background. The hero pattern features a centered, multi-line headline with a concise subtext, flanked by prominent call-to-action buttons. Section rhythm is driven by consistent vertical spacing, creating ample breathing room, occasionally breaking into alternating data panels or code examples. Content arrangement often utilizes centered stacks for headlines and CTAs, transitioning into 2-column layouts for features (text on one side, visual on the other, alternating). The page is text-dominant in places, with product screenshots serving to break up sections and highlight functionality. A standard top navigation bar persists, maintaining a cohesive header.

## Agent Prompt Guide

### Quick Color Reference
- Text: #ffffff (Ghostly White)
- Background: #000000 (Midnight Void)
- CTA: #0090ff (Digital Blue)
- Border: #918d8d (Ash Gray)
- Accent: #9f8dfc (Cosmic Violet)

### Example Component Prompts
1. Create a primary hero section with a centered headline: Background Midnight Void (#000000). Headline 'Realtime infrastructure for multiplayer apps' in Suisse font, weight 400, size 48px, line-height 1.2, letter-spacing -0.02em, color Ghostly White (#ffffff). Subtext 'Empower collaboration with Liveblocks' in Suisse font, weight 400, size 16px, line-height 1.5, color Ash Gray (#918d8d).
2. Generate a 'Get Started' button: Digital Blue (#0090ff) background, Ghostly White (#ffffff) text. Suisse font, weight 400, size 16px, line-height 1.5. Border radius 6px. Padding 8px top/bottom, 12px left/right. No border. 
3. Design a feature card: Graphite Base (#111111) background. Border radius 8px. Padding 16px. Headline 'Presence Indicators' in Suisse font, weight 500, size 24px, line-height 1.33, color Ghostly White (#ffffff). Body text 'Show who's online and active in real-time' in Suisse font, weight 400, size 14px, line-height 1.43, color Ash Gray (#918d8d).
4. Create a secondary ghost button: Transparent background, Ghostly White (#ffffff) text color. Suisse font, weight 400, size 16px, line-height 1.5. Border 1px solid Ghostly White (#ffffff). Border radius 6px. Padding 8px top/bottom, 12px left/right.
5. Render a code snippet: Wrap the text `useLiveblocks()` in a JetBrains Mono font, weight 400, size 14px, line-height 1.43, color Ghostly White (#ffffff). Add a Graphite Base (#111111) background with 4px padding and a 4px border radius.

## Similar Brands

- **Vercel** — Shares a sophisticated dark-mode aesthetic with strong typography, minimal borders, and pops of vivid accent colors.
- **Stripe** — Similar precision in typography, use of subtle gradients for visual interest, and a focus on clarity through strict adherence to a grid.
- **Linear** — Employs a deep dark theme, highly interactive UI elements, and a clean, function-first approach to component design.
- **GitHub** — Known for their dark interface, emphasis on code readability (monospaced fonts), and a structured, technical aesthetic suitable for developers.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghostly-white: #ffffff;
  --color-graphite-base: #111111;
  --color-ash-gray: #918d8d;
  --color-light-concrete: #edecee;
  --color-distant-gray: #b7b4b4;
  --color-slate-text: #635f5f;
  --color-digital-blue: #0090ff;
  --color-cosmic-violet: #9f8dfc;
  --color-system-teal: #70e1c8;
  --color-terminal-red: #f76e99;
  --color-void-radiance: #000000;
  --gradient-void-radiance: radial-gradient(50% 50%, lab(0 0 0) 90%, oklch(0.07 0 0) 95%, oklch(0.2 0 0) 97%, oklch(0.3 0 0) 100%);

  /* Typography — Font Families */
  --font-suisse: 'suisse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: 0.25px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.02px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-196: 196px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-large: 12px;
  --radius-buttons: 6px;
  --radius-default: 4px;
  --radius-containers: 8px;

  /* Shadows */
  --shadow-subtle: rgb(39, 38, 38) 0px 0px 0px 1px;
  --shadow-subtle-2: color(srgb 0.925333 0.925333 0.925333) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghostly-white: #ffffff;
  --color-graphite-base: #111111;
  --color-ash-gray: #918d8d;
  --color-light-concrete: #edecee;
  --color-distant-gray: #b7b4b4;
  --color-slate-text: #635f5f;
  --color-digital-blue: #0090ff;
  --color-cosmic-violet: #9f8dfc;
  --color-system-teal: #70e1c8;
  --color-terminal-red: #f76e99;
  --color-void-radiance: #000000;

  /* Typography */
  --font-suisse: 'suisse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: 0.25px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.02px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-196: 196px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Shadows */
  --shadow-subtle: rgb(39, 38, 38) 0px 0px 0px 1px;
  --shadow-subtle-2: color(srgb 0.925333 0.925333 0.925333) 0px 0px 0px 1px inset;
}
```
