# Ankar AI — Style Reference
> Midnight command center, crisp information

**Theme:** light

Ankar AI presents a focused, high-contrast digital workspace. Its character is defined by a deep, near-black background paired with stark white text for primary content, ensuring commands are clear and deliberate. Type choices are precise, with a strong, narrow sans-serif for headings that conveys authority, complemented by functional monospaced fonts for technical details. Interaction points are subtle and integrate into the dark canvas, utilizing a sharp, minimal border for emphasis rather than color fills, creating an experience of quiet, understated power.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#000000` | `--color-inkwell` | Primary text, icon fills, strong borders, dark surface backgrounds |
| Canvas | `#ffffff` | `--color-canvas` | Page background, primary surface color |
| Deep Graphite | `#171717` | `--color-deep-graphite` | Secondary surface background, prominent button background, darker text sections |
| Cloud Gray | `#f8f8f8` | `--color-cloud-gray` | Subtle background for UI elements, light surface alternative |
| Smoke Gray | `#b9b9b9` | `--color-smoke-gray` | Subtle background tints, muted borders |
| Ash Stone | `#979797` | `--color-ash-stone` | Muted body text, helper text, secondary borders |
| Dark Stone | `#515151` | `--color-dark-stone` | Subtle helper text, less prominent body text |
| Light Steel | `#cfcfcf` | `--color-light-steel` | Light borders, inactive states, subtle text in darker contexts |
| Ember Orange | `linear-gradient(90deg, #c679c4, #fa3d1d, #ffb005)` | `--color-ember-orange` | Interface accents, subtle highlights, potentially code syntax |
| Crimson Hue | `#ff2600` | `--color-crimson-hue` | Interface accents, subtle highlights |

## Tokens — Typography

### sans-serif — Base system font for incidental UI elements and fallbacks. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Base system font for incidental UI elements and fallbacks.

### Switzer — Primary UI text, body content, and navigation items. Features ('blwf', 'cv03', 'cv04', 'cv09', 'cv11') hint at distinct character forms or ligatures for a refined appearance. · `--font-switzer`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 14px, 16px, 18px
- **Line height:** 1.00, 1.30, 1.58
- **Letter spacing:** normal
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Primary UI text, body content, and navigation items. Features ('blwf', 'cv03', 'cv04', 'cv09', 'cv11') hint at distinct character forms or ligatures for a refined appearance.

### Kibitz Pro Light — Headlines and display text. The ultra-light weight creates a sense of gravitas through restraint, making the text whisper authority rather than shout it. Letter spacing is consistently tightened for prominence. · `--font-kibitz-pro-light`
- **Substitute:** Lato Light
- **Weights:** 300
- **Sizes:** 24px, 32px, 40px, 48px, 64px
- **Line height:** 0.98, 1.00, 1.04, 1.06, 1.20
- **Letter spacing:** -0.01em
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Headlines and display text. The ultra-light weight creates a sense of gravitas through restraint, making the text whisper authority rather than shout it. Letter spacing is consistently tightened for prominence.

### Space Mono — Monospaced text for code snippets, data, or technical labels where fixed width characters are beneficial for alignment and reading. · `--font-space-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.30, 1.58
- **Letter spacing:** normal
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Monospaced text for code snippets, data, or technical labels where fixed width characters are beneficial for alignment and reading.

### Switzer Variable — Switzer Variable — detected in extracted data but not described by AI · `--font-switzer-variable`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Switzer Variable — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 14px | 1.3 | — | `--text-body` |
| heading-sm | 24px | 1.04 | -0.24px | `--text-heading-sm` |
| heading | 32px | 1.06 | -0.32px | `--text-heading` |
| heading-lg | 40px | 1 | -0.4px | `--text-heading-lg` |
| display | 48px | 0.98 | -0.48px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 4px |
| circular | 100px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call-to-action button for initiating primary actions.

Filled with Deep Graphite (#171717), white text, with minimal 2px radius and 10px vertical and 16px horizontal padding.

### Ghost Header Button
**Role:** Secondary action in the header, blends into the navigation.

Transparent background, Inkwell (#000000) text with 2px radius. Very minimal padding and no border, effectively a text link styled as a button.

### Ghost Card Action Button
**Role:** Action within a card or content area, subtle and borderless.

Transparent background, Inkwell (#000000) text. No visible radius, padding or borders, relying on text styling for interaction affordance.

### Navigation Link
**Role:** Standard navigation item in the header.

Inkwell (#000000) text on a Canvas (#ffffff) background for light sections, or Deep Graphite (#171717) text on a Deep Graphite background. No borders or distinct background apart from hover states not captured.

### Feature Card
**Role:** Used to showcase key features or modules.

A Deep Graphite (#171717) background for the content area, with a subtle border in Ash Stone (#979797). Interior padding is 16px. Rounded corners are not explicitly defined, suggesting sharp edges or minimal default radius.

## Do's and Don'ts

### Do
- Prioritize Inkwell (#000000) for all primary body text, headings, and bold UI labels.
- Use Canvas (#ffffff) as the dominant page background for most sections, including all content cards and surfaces.
- Implement Deep Graphite (#171717) for secondary backgrounds, especially for interactive elements like buttons and some content sections.
- Apply Kibitz Pro Light weight 300 with -0.01em letter-spacing for all significant headlines (40px or above) to maintain an authoritative, restrained tone.
- Utilize Switzer for body text and UI elements at 12px to 18px, adhering to a 1.0 lineHeight for compact presentation.
- Define interactive elements such as buttons and form fields with a subtle 4px border-radius.
- Use Ash Stone (#979797) for muted helper text, descriptive paragraphs, and light borders on cards.

### Don't
- Avoid using highly saturated colors for large surface areas or backgrounds — save them for minimal accents.
- Do not use generic system fonts for primary content or prominent headlines; always use Switzer or Kibitz Pro Light.
- Refrain from heavy shadow stacks or elaborate gradients for elevation; maintain a flat, high-contrast aesthetic.
- Do not use letter-spacing on body text or small UI elements unless explicitly defined for a specific token or component.
- Avoid large, airy padding on cards or components; maintain a compact, information-dense layout with 16px card padding.
- Do not introduce unnecessary chromatic colors for buttons or links where Inkwell (#000000) or Deep Graphite (#171717) with white text suffice.
- Never introduce curved sections or elements; maintain sharp, angular forms for most UI components and layouts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Base page background |
| 1 | Cloud Gray | `#f8f8f8` | Subtle elevated background for sections or large panels |
| 2 | Deep Graphite | `#171717` | Prominent interactive elements like buttons or dark container backgrounds |
| 3 | Inkwell | `#000000` | Overlays, very dark immersive sections |

## Imagery

The imagery strategy is centered around product clarity and abstract mood-setting. The hero section features abstract, radiant light leaks and nebulae in hues of orange, red, and blue, creating a dynamic but dark atmospheric backdrop. Further down, product-focused images and illustrations are rectangular, often contained within cards with sharp, clean edges. Customer testimonials feature framed video embeds or candid headshots with minimal adornment. Icons are generally filled, monochromatic (white on dark backgrounds, black on light), and have a substantial visual weight to them, serving descriptive rather than purely decorative roles. The overall density of imagery is balanced, supporting text-heavy explanations with visual anchors without overwhelming the primary content.

## Layout

The page primarily employs a max-width contained layout, though the hero section is full-bleed, extending its dark, radiant background across the entire viewport. Content sections alternate between these full-width immersive experiences and narrower, centered content blocks. The hero features a large, centered headline over the abstract background. Subsequent sections often use a clear vertical rhythm, with consistent section gaps of 64px. Content arrangements frequently utilize two-column layouts, particularly for text-left/image-right (or vice-versa) alternating patterns, providing visual interest. There are also 4-column card grids for presenting features, maintaining a structured, organized feel. Navigation is handled by a sticky top bar that remains static at the top of the viewport, ensuring constant access to key links.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #979797
accent: #ff7e2e
primary action: #171717 (filled action)

Example Component Prompts:
1. Create a primary filled button: Deep Graphite (#171717) background, Canvas (#ffffff) text, 4px radius, 10px vertical and 16px horizontal padding, Switzer 400 at 14px.
2. Create a feature card: Canvas (#ffffff) background, 16px padding, Ash Stone (#979797) 1px border. Headline: Kibitz Pro Light 300 at 24px, Inkwell (#000000). Body text: Switzer 400 at 14px, Dark Stone (#515151). Add a small icon at the top with Inkwell (#000000) fill.
3. Create a Primary Action Button: #171717 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **OpenAI** — Shares a high-contrast dark mode aesthetic with ample whitespace and distinct typographic hierarchy.
- **Relume** — Similar approach to monochrome palettes with subtle usage of gradients for atmosphere and a concise, structured layout.
- **Vercel** — A developer-focused product with clear, compact UI elements, effective use of typography, and high-contrast visuals.
- **Linear** — Dark-themed interface with sharp edges, minimal embellishments, and a focus on clarity through considered typography and neutral color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #000000;
  --color-canvas: #ffffff;
  --color-deep-graphite: #171717;
  --color-cloud-gray: #f8f8f8;
  --color-smoke-gray: #b9b9b9;
  --color-ash-stone: #979797;
  --color-dark-stone: #515151;
  --color-light-steel: #cfcfcf;
  --color-ember-orange: #ff7e20;
  --gradient-ember-orange: linear-gradient(90deg, #c679c4, #fa3d1d, #ffb005);
  --color-crimson-hue: #ff2600;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kibitz-pro-light: 'Kibitz Pro Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-switzer-variable: 'Switzer Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.04;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.06;
  --tracking-heading: -0.32px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.4px;
  --text-display: 48px;
  --leading-display: 0.98;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-default: 4px;
  --radius-circular: 100px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-cloud-gray: #f8f8f8;
  --surface-deep-graphite: #171717;
  --surface-inkwell: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #000000;
  --color-canvas: #ffffff;
  --color-deep-graphite: #171717;
  --color-cloud-gray: #f8f8f8;
  --color-smoke-gray: #b9b9b9;
  --color-ash-stone: #979797;
  --color-dark-stone: #515151;
  --color-light-steel: #cfcfcf;
  --color-ember-orange: #ff7e20;
  --color-crimson-hue: #ff2600;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kibitz-pro-light: 'Kibitz Pro Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-switzer-variable: 'Switzer Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.04;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.06;
  --tracking-heading: -0.32px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.4px;
  --text-display: 48px;
  --leading-display: 0.98;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;
}
```
