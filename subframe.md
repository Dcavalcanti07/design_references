# Subframe — Style Reference
> engineered clarity on frosted glass. A clean, bright surface for complex tools.

**Theme:** light

Subframe employs a minimalist, high-contrast aesthetic that feels precise and engineered. The design emphasizes clarity through a largely achromatic palette, crisp typography, and subtle component treatments. Interactive elements use dark fills or light borders to stand out against the pervasive light gray surfaces, creating a focused experience suitable for a developer-centric tool. The system avoids overt ornamentation, relying on strong typographic hierarchy and restrained spatial relationships.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Fog | `#e5e7eb` | `--color-canvas-fog` | Primary page background, structural borders, subtle neutral elements |
| Inkwell | `#242424` | `--color-inkwell` | Primary text, darkest UI elements, filled button backgrounds — signifies interaction and primary content |
| Ghost White | `#fafafa` | `--color-ghost-white` | Secondary surface background, icon strokes, active states |
| Surface Frost | `#ededed` | `--color-surface-frost` | Card backgrounds, slightly elevated surfaces |
| Code Black | `#171717` | `--color-code-black` | Dominant headings, high-contrast body text |
| Muted Ash | `#a3a3a3` | `--color-muted-ash` | Secondary body text, placeholder text, subtle contextual information |
| Subtle Gray | `#bdbdbd` | `--color-subtle-gray` | Subtle button shadows, low-contrast UI details |
| Helper Gray | `#5c5c5c` | `--color-helper-gray` | Helper text, code comments, less prominent body copy |
| Whisper Gray | `#737373` | `--color-whisper-gray` | Muted captions, helper text, and de-emphasized UI labels |

## Tokens — Typography

### Inter — Primary UI font for all headings, body text, navigation, and buttons. Its versatile weights and condensed nature optimize for a compact, information-dense display. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 500, 600, 700
- **Sizes:** 12px, 14px, 18px, 24px, 28px, 48px, 96px
- **Line height:** 1.00, 1.13, 1.14, 1.17, 1.33, 1.43
- **Letter spacing:** -0.0500em at 96px, -0.0250em at 48px, -0.0050em at 24px and 28px
- **Role:** Primary UI font for all headings, body text, navigation, and buttons. Its versatile weights and condensed nature optimize for a compact, information-dense display.

### ui-monospace — System monospace fallback for code blocks and technical output. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 500
- **Sizes:** 10px
- **Line height:** 1.70
- **Letter spacing:** -0.0060em
- **Role:** System monospace fallback for code blocks and technical output.

### Fragment Mono — Specific monospace font for highlighted code snippets or technical labels, providing a distinct, engineered aesthetic where precision is paramount. · `--font-fragment-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.33
- **Letter spacing:** -0.0250em
- **Role:** Specific monospace font for highlighted code snippets or technical labels, providing a distinct, engineered aesthetic where precision is paramount.

### Instrument Serif — Display font used for extremely large, impactful headings, reserved for hero sections and key messaging to create a sense of scale and authority. · `--font-instrument-serif`
- **Substitute:** Lora
- **Weights:** 400
- **Sizes:** 80px, 128px
- **Line height:** 1.00
- **Letter spacing:** -0.0250em
- **Role:** Display font used for extremely large, impactful headings, reserved for hero sections and key messaging to create a sense of scale and authority.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.7 | -0.06px | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 18px | 1.33 | -0.025px | `--text-body-lg` |
| heading-sm | 24px | 1.17 | -0.005px | `--text-heading-sm` |
| heading | 28px | 1.14 | -0.005px | `--text-heading` |
| heading-lg | 48px | 1.13 | -0.025px | `--text-heading-lg` |
| display | 96px | 1 | -0.05px | `--text-display` |

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
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 24px |
| buttons | 16px |
| navigation | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(255, 255, 255, 0.25) 0px 4px 4px -2px inset, rgba(0,...` | `--shadow-sm` |

### Layout

- **Section gap:** 24-64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Filled Primary Button
**Role:** Main call to action button.

Solid Inkwell background (#242424), Ghost White text (#fafafa), 16px border-radius. Padding of 0px vertical, 16px horizontal. Uses Inter font.

### Outlined Secondary Button
**Role:** Secondary action button, less prominent than primary.

Transparent background, Inkwell text (#242424), 16px border-radius, 1px Canvas Fog border (#e5e7eb). Padding 0px vertical, 16-20px horizontal. Uses Inter font.

### Subtle Interaction Button
**Role:** Ghost button with a light hover state.

Transparent background for default, light gray background on hover (rgba(0, 0, 0, 0.06)). Inkwell text (#242424), 16px border-radius, 1px Canvas Fog border (#e5e7eb). Padding 0px vertical, 20px horizontal. Uses Inter font.

### Nav Button
**Role:** Navigation links styled as buttons.

Transparent background, Inkwell text (#242424), 9999px border-radius (pill shape). Minimal horizontal padding. Uses Inter font.

### Feature Card
**Role:** Container for showcasing product features or content blocks.

Surface Frost background (#ededed), 24px border-radius. No box shadow evident. Generous internal padding and spacing to contain content.

### Tool Selector Toggle
**Role:** Segmented control for tool selection, seen in the hero.

A complex button with a layered shadow and inset effect. Primarily Inkwell (#242424), with subtle lighter elements for active state. Rounded corners. Uses a multi-layered inset shadow: rgba(255, 255, 255, 0.25) 0px 4px 4px -2px inset, rgba(0, 0, 0, 0.25) 0px -4px 4px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset.

### Small Pill Tag
**Role:** Small, rounded labels for categories or status.

Utilizes a 9999px radius (pill shape) with Canvas Fog background (#e5e7eb) and Inkwell text (#242424). Used for filtering or categorization in navigation contexts.

## Do's and Don'ts

### Do
- Prioritize Inter font for all UI text, varying weight (500-700) and sizing to establish clear hierarchy.
- Use Inkwell (#242424) for primary text and calls to action, maintaining high contrast against light backgrounds.
- Apply Canvas Fog (#e5e7eb) as the dominant page background and for subtle borders to delineate sections.
- Reserve the complex inset shadow for interactive controls like the Tool Selector Toggle, indicating depth and functionality.
- Utilize 24px border-radius for cards and content containers, conveying a refined, rounded aesthetic.
- Employ a 9999px border-radius for navigation items and small tags, creating a distinct pill-shaped interactive element.
- Maintain a clear visual hierarchy by limiting prominent colors to achromatic tones, saving any potential accent colors for highly functional or branded elements not present in this dataset.

### Don't
- Avoid introducing saturated colors unless they serve a specific brand or semantic function not supported by the current palette.
- Do not use heavy, complex shadows for general elevation – the system favors a flatter, almost shadowless aesthetic.
- Refrain from using more than two font families on a single page, with specific monospace fonts reserved for technical contexts.
- Do not introduce decorative gradients or texture, as the system relies on clean, flat surfaces.
- Avoid dense, unbroken blocks of text; break up content with generous spacing and strong headlines.
- Do not vary border-radius arbitrarily; stick to 16px for buttons, 24px for cards, and 9999px for pill-shaped elements.
- Resist using small font sizes (below 12px) for any critical information, even for captions, to maintain readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#fafafa` | Base background for sections and general page canvas, providing a bright, airy foundation. |
| 1 | Base Surface | `#e5e7eb` | Dominant background for the overall page, creating a slightly desaturated, muted base. |
| 2 | Card Surface | `#ededed` | Background for cards and elevated content blocks, providing a subtle visual distinction from the base page. |

## Elevation

- **Tool Selector Toggle:** `rgba(255, 255, 255, 0.25) 0px 4px 4px -2px inset, rgba(0, 0, 0, 0.25) 0px -4px 4px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset`

## Imagery

The site's imagery is defined by high-fidelity product screenshots and minimalist 3D renders. These visuals are typically contained within cards or placed centrally, often against a neutral, diffused background. There is a strong emphasis on showcasing the product UI directly, with a clean and almost stark presentation. Icons are outlined, leveraging the system's precise line work and monochrome palette, with a moderately heavy stroke weight. The overall impression is one of functionality and directness, with imagery primarily serving to explain concepts or demonstrate the product, rather than for decorative atmosphere.

## Layout

The page maintains a centered, contained layout with a maximum content width that appears to be around 1200px. The hero section frequently uses a prominent headline centered above a key product visual, often with minimal background styling. Sections primarily flow vertically with consistent, comfortable vertical spacing, evidenced by 24-64px section gaps. Content is typically arranged in stacked blocks or 1-2 column text/image layouts, alternating positions for visual interest. Navigation is handled by a sticky top bar with functional links and distinct 'Log in'/'Start for free' buttons, maintaining a clean header throughout the scroll.

## Agent Prompt Guide

Quick Color Reference:
- text: #242424
- background: #e5e7eb
- border: #e5e7eb
- accent: no distinct accent color
- primary action: #242424 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #242424 background, #fafafa text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Generate a Feature Card with the title 'Real design control.' using Inter weight 600 at 28px, color Code Black (#171717), letter-spacing -0.0050em. The card should have a Surface Frost background (#ededed), 24px border-radius, and no box shadow. Provide ample internal padding of 16px.

## Similar Brands

- **Linear** — Monochromatic palette, crisp typography, and subtle elevation/border treatments for UI elements.
- **Figma** — Focus on product UI screenshots, clean layout, and a highly functional, understated aesthetic without heavy branding.
- **Vercel** — Technical, developer-focused aesthetic using high-contrast text, minimalist design, and strong typography.
- **Tailwind UI** — Understated, utility-first design principles with heavy reliance on neutrals, clean spacing, and well-defined component states.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-fog: #e5e7eb;
  --color-inkwell: #242424;
  --color-ghost-white: #fafafa;
  --color-surface-frost: #ededed;
  --color-code-black: #171717;
  --color-muted-ash: #a3a3a3;
  --color-subtle-gray: #bdbdbd;
  --color-helper-gray: #5c5c5c;
  --color-whisper-gray: #737373;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fragment-mono: 'Fragment Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --tracking-caption: -0.06px;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.025px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.17;
  --tracking-heading-sm: -0.005px;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --tracking-heading: -0.005px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.025px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.05px;

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
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 24-64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 24px;
  --radius-buttons: 16px;
  --radius-navigation: 9999px;

  /* Shadows */
  --shadow-sm: rgba(255, 255, 255, 0.25) 0px 4px 4px -2px inset, rgba(0, 0, 0, 0.25) 0px -4px 4px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset;

  /* Surfaces */
  --surface-canvas: #fafafa;
  --surface-base-surface: #e5e7eb;
  --surface-card-surface: #ededed;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-fog: #e5e7eb;
  --color-inkwell: #242424;
  --color-ghost-white: #fafafa;
  --color-surface-frost: #ededed;
  --color-code-black: #171717;
  --color-muted-ash: #a3a3a3;
  --color-subtle-gray: #bdbdbd;
  --color-helper-gray: #5c5c5c;
  --color-whisper-gray: #737373;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fragment-mono: 'Fragment Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --tracking-caption: -0.06px;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.025px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.17;
  --tracking-heading-sm: -0.005px;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --tracking-heading: -0.005px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.025px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(255, 255, 255, 0.25) 0px 4px 4px -2px inset, rgba(0, 0, 0, 0.25) 0px -4px 4px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset, rgba(255, 255, 255, 0.1) -2px 0px 2px -2px inset;
}
```
