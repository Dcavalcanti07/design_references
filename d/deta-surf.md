# Deta Surf — Style Reference
> Sky-bound clarity

**Theme:** light

Deta Surf uses a refreshing, sky-inspired aesthetic, where a vivid blue gradient forms the primary background, evoking expanse and clarity. UI elements are typically white, rounded cards, often with subtle shadows that provide a soft lift from the blue canvas. Typography blends elegant, traditional serifs for headlines with clean, modern sans-serifs for body text, creating a contrast that feels both authoritative and accessible. Interactive elements feature a bright, vivid blue, acting as functional punctuation against the otherwise serene palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Canvas | `linear-gradient(rgb(74, 158, 255) 0%, rgb(123, 184, 255) 50%, rgb(168, 213, 255) 100%)` | `--color-sky-canvas` | Page background, hero section background — its gradient brings depth and a sense of open space |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary surface for cards, input fields, and some button backgrounds — providing a clean, bright contrast to the blue |
| Fog Gray | `#f3f4f6` | `--color-fog-gray` | Secondary surface for cards and subtle background accents, offering a slightly muted alternative to Cloud White |
| Deep Space Blue | `#009afc` | `--color-deep-space-blue` | Primary action color for filled buttons and interactive accents — a vivid hue that stands out as active |
| Ocean Shadow | `#006dc8` | `--color-ocean-shadow` | Deep blue used for button and card shadows, tying elevation effects back to the brand's blue palette instead of generic gray; Inset shadow for active button states, providing a depressed effect |
| Graphite Text | `#000000` | `--color-graphite-text` | Primary text color for headings and body content, offering high contrast against light surfaces |
| Slate Text | `#5b6882` | `--color-slate-text` | Muted text for secondary information, icons, and helper text |
| Light Steel Border | `#e5e7eb` | `--color-light-steel-border` | Hairline borders, dividers, and ghost button outlines – providing subtle separation |
| Faint Blue Border | `#cfe9fd` | `--color-faint-blue-border` | Subtle border color for ghost buttons and some card outlines against lighter backgrounds |
| Ash Gray | `#808080` | `--color-ash-gray` | Tertiary text color for fine print and less prominent content |
| Deta Pink Glow | `#ed008d` | `--color-deta-pink-glow` | Brand icon accent, creating a small, bright visual pop |

## Tokens — Typography

### Switzer — Body text, navigation, and most UI elements. A clean, modern sans-serif that balances readability with a slightly condensed feel at smaller sizes, providing a practical counterpoint to Gambarino's expressive nature. · `--font-switzer`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 15px, 16px, 17px, 18px, 20px, 60px
- **Line height:** 1.00, 1.11, 1.20, 1.40, 1.43, 1.45, 1.50, 1.56, 1.60
- **Letter spacing:** -0.0090em
- **Role:** Body text, navigation, and most UI elements. A clean, modern sans-serif that balances readability with a slightly condensed feel at smaller sizes, providing a practical counterpoint to Gambarino's expressive nature.

### Gambarino — Headlines and emphasis text. Its classic, confident serif forms give authority and distinction, particularly at larger sizes. Not a generic sans-serif, giving it a distinctive voice. · `--font-gambarino`
- **Substitute:** Georgia
- **Weights:** 400, 500
- **Sizes:** 16px, 18px, 20px, 36px, 40px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.20, 1.40, 1.50, 1.56
- **Letter spacing:** -0.0100em
- **Role:** Headlines and emphasis text. Its classic, confident serif forms give authority and distinction, particularly at larger sizes. Not a generic sans-serif, giving it a distinctive voice.

### Tanker — Specialized for 'Open Source' badge and potentially code snippets. A distinct, wide-tracked typeface that creates a bold, technical aesthetic for specific highlights. · `--font-tanker`
- **Substitute:** Monospace
- **Weights:** 400
- **Sizes:** 16px, 19px
- **Line height:** 1.30, 1.50
- **Letter spacing:** 0.0500em
- **Role:** Specialized for 'Open Source' badge and potentially code snippets. A distinct, wide-tracked typeface that creates a bold, technical aesthetic for specific highlights.

### Inter — Inter — detected in extracted data but not described by AI · `--font-inter`
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.5
- **Letter spacing:** -0.009
- **Role:** Inter — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.108px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.126px | `--text-body-sm` |
| body | 16px | 1.5 | -0.144px | `--text-body` |
| subheading | 20px | 1.4 | -0.2px | `--text-subheading` |
| heading | 48px | 1.11 | -0.48px | `--text-heading` |
| display | 60px | 1 | -0.6px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 9999px |
| general | 8px |
| inputField | 16.2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle-2 | `rgb(0, 109, 200) 0px -4px 0px 0px inset, rgba(0, 0, 0, 0....` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call-to-action

Background: Deep Space Blue (#009afc). Text: Cloud White (#ffffff). Radius: 9999px (pill shape). Padding: 12px vertical, 48px horizontal. Shadow: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px for soft elevation.

### Ghost Open Source Button
**Role:** Secondary action or status indicator

Background: transparent. Text: Graphite Text (#000000). Border: Light Steel Border (#e5e7eb) 1px solid. Radius: 9999px (pill shape). Padding minimal/content-driven.

### Search/Notebook Input
**Role:** Interactive input field

Background: Cloud White (#ffffff). Text: Graphite Text (#000000). Placeholder text: Slate Text (#5b6882). Border: none. Radius: 16.2px. Inset shadow: Ocean Shadow (#006dc8) 0px -4.8px 0px 0px for a subtle depth effect.

### Standard Card
**Role:** Content container

Background: Cloud White (#ffffff). Radius: 12px. Padding: 16px. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for a subtle lift.

### Muted Card Background
**Role:** Secondary content container

Background: Fog Gray (#f3f4f6). Radius: 16px. No shadow, keeping it visually grounded.

### Header Navigation Link
**Role:** Global navigation item

Text: Cloud White (#ffffff). No background, minimal padding. Subtle underline on hover. Font: Switzer, 16px, weight 500.

### Text Link in Body
**Role:** Interactive text element

Text: Slate Text (#5b6882). Underlined on hover. Font: Switzer or Gambarino based on context, default is 16px, weight 400.

## Do's and Don'ts

### Do
- Use Sky Canvas (#a8d5ff) with its default linear gradient for primary backgrounds to establish an expansive feel.
- Employ Cloud White (#ffffff) for all interactive cards and input surfaces to create bright, readable content blocks.
- Apply a 9999px border-radius to all buttons for a friendly, pill-shaped aesthetic.
- Set primary action buttons with Deep Space Blue (#009afc) background and Cloud White (#ffffff) text to guide user interaction.
- Maintain a clear visual hierarchy by using Gambarino for headlines (sizes 20px-60px) and Switzer for body text (sizes 12px-18px).
- Use a subtle shadow rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for cards to provide minimal depth without visual heaviness.
- Leverage Faint Blue Border (#cfe9fd) for ghost button borders or secondary outlines to soften interactive elements.

### Don't
- Avoid sharp corners; all UI elements should have a radius of at least 8px, with interactive elements preferring 16.2px or 9999px.
- Do not introduce strong, dark backgrounds other than the hero gradient; maintain a predominantly light aesthetic for content sections.
- Refrain from using generic gray shadows for interactive elements; instead, use Ocean Shadow (#006dc8) for blue-tinted elevation.
- Do not apply excessive letter-spacing to body text; maintain the subtle negative tracking specified in Switzer and Gambarino for dense readability.
- Avoid using multiple vivid accent colors; Deep Space Blue (#009afc) should be the primary chromatic accent for user interaction.
- Do not deviate from the specified font families; Switzer and Gambarino are key to the brand's typographic identity.
- Do not use transparent backgrounds for text-heavy content cards; always provide a solid Cloud White or Fog Gray background for readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Sky Canvas | `#a8d5ff` | Dominant background for the page, setting the atmospheric tone with its gradient. |
| 1 | Fog Gray | `#f3f4f6` | Subtle background for less prominent cards, providing a soft contrast to the primary canvas. |
| 2 | Cloud White | `#ffffff` | Primary surface for interactive elements, content cards, and input fields, offering high contrast and perceived cleanliness. |

## Elevation

- **Standard Card:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Primary Filled Button:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Input Field:** `rgb(0, 109, 200) 0px -4.8px 0px 0px inset, rgba(0, 0, 0, 0.1) 0px 2.4px 4.8px 0px`

## Imagery

Imagery primarily consists of conceptual 3D renders (e.g., notebook, floating elements) and stylized, high-key photography of hands interacting with small, digital-like objects. The renders are often slightly tilted or floating to convey lightness and innovation. Photos are clean and bright, frequently using water or reflective surfaces, featuring product elements rather than lifestyle scenes. Icons are simple, outlined or filled, with a consistent stroke weight and occasionally feature the Deta Pink Glow accent. Visuals are used decoratively to enhance the 'elevate your thinking' metaphor.

## Layout

The page uses a full-bleed layout for the hero section, featuring a prominent blue gradient background and centered, large typography. Subsequent sections appear to use a max-width content container, centered on the page. Content arrangement often alternates between text-dominant blocks and visual elements, creating a balanced rhythm. A visual grid is subtly suggested by the placement of multiple floating card-like elements in the hero. Vertical spacing is comfortable, with clear separation between sections. The navigation is a minimal top bar with brand logo and utilitarian links (Students, GitHub).

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #a8d5ff
border: #e5e7eb
accent: #ed008d
primary action: #009afc (filled action)

Example Component Prompts:
Create a hero section with a gradient background using linear-gradient(rgb(74, 158, 255) 0%, rgb(123, 184, 255) 50%, rgb(168, 213, 255) 100%). Headline: 'Elevate your thinking.' (Gambarino, 60px, Graphit Text #000000, letter-spacing -0.6px). Subtitle: 'Surf is an intelligent notebook...' (Switzer, 20px, Slate Text #5b6882, letter-spacing -0.18px).

Create a Primary Action Button: #009afc background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a Standard Card: background Cloud White #ffffff, radius 12px, padding 16px. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px. Text: 'Notes for "Surf Demo" Video' (Switzer, 18px, Graphite Text #000000).

Implement an interactive Search Input: Cloud White #ffffff background, radius 16.2px, inset shadow rgb(0, 109, 200) 0px -4.8px 0px 0px, placeholder text Slate Text (#5b6882) 'Web Search' (Switzer, 16px).

## Similar Brands

- **Linear** — Clean, light UI with soft shadows and a strong emphasis on content, often using a distinct accent color for interactive elements.
- **Notion** — White card-based interfaces, prominent sans-serifs for body text, and a strong focus on content clarity over decorative elements.
- **Dropbox** — Use of fluid, friendly shapes and gradients, often paired with bright, inviting visual elements and a clean type system.
- **Raycast** — Emphasis on subtle shadows, rounded corners, and a predominantly light mode with a minimal, functional aesthetic for productivity apps.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-canvas: #a8d5ff;
  --gradient-sky-canvas: linear-gradient(rgb(74, 158, 255) 0%, rgb(123, 184, 255) 50%, rgb(168, 213, 255) 100%);
  --color-cloud-white: #ffffff;
  --color-fog-gray: #f3f4f6;
  --color-deep-space-blue: #009afc;
  --color-ocean-shadow: #006dc8;
  --color-graphite-text: #000000;
  --color-slate-text: #5b6882;
  --color-light-steel-border: #e5e7eb;
  --color-faint-blue-border: #cfe9fd;
  --color-ash-gray: #808080;
  --color-deta-pink-glow: #ed008d;

  /* Typography — Font Families */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gambarino: 'Gambarino', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tanker: 'Tanker', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.108px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.126px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.144px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading: 48px;
  --leading-heading: 1.11;
  --tracking-heading: -0.48px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 1.058px;
  --radius-md: 3.139px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16.2px;
  --radius-2xl-2: 19.652px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30.75px;
  --radius-3xl-3: 42.918px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 9999px;
  --radius-general: 8px;
  --radius-inputfield: 16.2px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-2: rgb(0, 109, 200) 0px -4px 0px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-sky-canvas: #a8d5ff;
  --surface-fog-gray: #f3f4f6;
  --surface-cloud-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-canvas: #a8d5ff;
  --color-cloud-white: #ffffff;
  --color-fog-gray: #f3f4f6;
  --color-deep-space-blue: #009afc;
  --color-ocean-shadow: #006dc8;
  --color-graphite-text: #000000;
  --color-slate-text: #5b6882;
  --color-light-steel-border: #e5e7eb;
  --color-faint-blue-border: #cfe9fd;
  --color-ash-gray: #808080;
  --color-deta-pink-glow: #ed008d;

  /* Typography */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gambarino: 'Gambarino', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tanker: 'Tanker', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.108px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.126px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.144px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading: 48px;
  --leading-heading: 1.11;
  --tracking-heading: -0.48px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-sm: 1.058px;
  --radius-md: 3.139px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16.2px;
  --radius-2xl-2: 19.652px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30.75px;
  --radius-3xl-3: 42.918px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-2: rgb(0, 109, 200) 0px -4px 0px 0px inset, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;
}
```
