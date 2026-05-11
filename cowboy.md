# Cowboy — Style Reference
> Minimalist Product Canvas

**Theme:** light

Cowboy presents a functional and understated interface, emphasizing clean typography and a largely monochromatic palette. Visuals are grounded in strong product photography, with UI elements maintaining a soft, rounded aesthetic that feels approachable and human. The design prioritizes clarity and a quiet confidence, allowing product imagery and concise messaging to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default input background |
| Ink Black | `#1d1d1d` | `--color-ink-black` | Primary text, filled button backgrounds, prominent headings, dark overlay backgrounds for hero sections |
| Whisper Gray | `#e5e7eb` | `--color-whisper-gray` | Subtle borders, dividers, subtle background on some page sections, text on dark backgrounds |
| Dim Gray | `#737373` | `--color-dim-gray` | Muted helper text, secondary button text, less prominent information |
| Ash Cloud | `#f3f4f6` | `--color-ash-cloud` | Subtle alternative background for card surfaces and alternating sections, providing visual separation |
| Stone Gray | `#a3a3a3` | `--color-stone-gray` | Tertiary text, inactive icons, placeholder text |
| Slate Border | `#6b7280` | `--color-slate-border` | Input field borders |
| Forest Whisper | `#569d5f` | `--color-forest-whisper` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Action Blue | `#2563eb` | `--color-action-blue` | Violet state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |

## Tokens — Typography

### SuisseIntl — Primary brand typeface for all headings, body text, and UI elements. Its strong yet subtle presence defines the textual hierarchy. · `--font-suisseintl`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 24px, 36px, 42px, 44px, 46px, 52px, 72px, 100px
- **Line height:** 0.90, 0.95, 1.00, 1.05, 1.25, 1.33, 1.47, 1.50
- **Letter spacing:** -0.0250em, -0.0250em, -0.0250em, -0.0200em, -0.0200em, -0.0150em, -0.0150em, -0.0150em
- **Role:** Primary brand typeface for all headings, body text, and UI elements. Its strong yet subtle presence defines the textual hierarchy.

### ui-monospace — Used for specific large, technical or decorative headings, providing contrast through its monospaced nature. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 64px
- **Line height:** 1.00
- **Role:** Used for specific large, technical or decorative headings, providing contrast through its monospaced nature.

### intercom-font — Appears in badges and some specific button contexts, providing a concise and functional counterpoint to the primary typeface. · `--font-intercom-font`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Appears in badges and some specific button contexts, providing a concise and functional counterpoint to the primary typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.47 | — | `--text-subheading` |
| heading-sm | 20px | 1.33 | -0.3px | `--text-heading-sm` |
| heading-lg | 36px | 1.05 | -0.54px | `--text-heading-lg` |
| display-sm | 42px | 1 | -0.84px | `--text-display-sm` |
| display | 52px | 0.95 | -1.3px | `--text-display` |
| display-lg | 72px | 0.9 | -1.8px | `--text-display-lg` |
| display-xl | 100px | 0.9 | -2.5px | `--text-display-xl` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |
| 176 | 176px | `--spacing-176` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| buttons | 9999px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.06) 0px 1px 6px 0px, rgba(0, 0, 0, 0.16) ...` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm-2` |

### Layout

- **Section gap:** 60px
- **Card padding:** 48px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, conveying primary interaction.

Background: Ink Black (#1d1d1d), Text: Canvas White (#ffffff), Border Radius: 9999px, Padding: 20px vertical, 24px horizontal. Uses SuisseIntl font.

### Secondary Outlined Button
**Role:** Secondary calls-to-action, less prominent but still interactive.

Background: Canvas White (#ffffff), Text: Ink Black (#1d1d1d), Border: 1px solid Whisper Gray (#e5e7eb) (implied from general border patterns), Border Radius: 9999px, Padding: 12px vertical, 20px horizontal. Uses SuisseIntl font.

### Ghost Header Button
**Role:** Navigation and utility actions within headers, minimal visual weight.

Background: transparent (rgba(0, 0, 0, 0)), Text: Canvas White (#ffffff) on dark backgrounds, Ink Black (#1d1d1d) on light backgrounds; Border: none, Border Radius: 0px.

### Feature Card
**Role:** Displaying product features or key information blocks.

Background: Canvas White (#ffffff), Border Radius: 8px, padding: 48px vertical, 64px horizontal. No visible shadow by default.

### Alternating Section Card
**Role:** Providing visual distinction between content blocks, often for related features.

Background: Ash Cloud (#f3f4f6), Border Radius: 8px, padding: 0px. Used primarily as a background block rather than a content-carrying card.

### Product Display Card
**Role:** Large, immersive display for product imagery or specific model information.

Background: transparent (rgba(0, 0, 0, 0)), Border Radius: 0px, padding: 110.4px vertical, 60px horizontal. Designed to integrate fluidly with imagery.

### Input Field
**Role:** Standard input for user data entry.

Background: Canvas White (#ffffff) or transparent, Text Color: Action Blue (#2563eb) for input value or Canvas White (#ffffff) for placeholder, Border Color: Slate Border (#6b7280), Border Radius: 0px. Padding: 8px vertical, 12px horizontal.

### Round Tag Button
**Role:** Categorization or small actions, highly rounded.

Background: Canvas White (#ffffff), Text: Ink Black (#1d1d1d), Border Radius: 9999px. Padding implied by content.

## Do's and Don'ts

### Do
- Prioritize SuisseIntl for all text elements, setting it with precise letter-spacing based on size from the typography rules.
- Use Ink Black (#1d1d1d) sparingly for primary headings and call-to-action buttons, creating focal points against lighter backgrounds.
- Apply a border-radius of 8px to all cards and general containers for a consistent soft corner aesthetic.
- Apply a border-radius of 9999px to all buttons and tags to create distinct pill shapes.
- Maintain a clear visual hierarchy by limiting saturated colors to functional states or subtle informational blocks like Forest Whisper (#569d5f) and Action Blue (#2563eb).
- Use Whisper Gray (#e5e7eb) for hairline borders and minimal dividers to separate UI elements without heavy lines.
- Ensure generous vertical spacing between sections, adhering to the 60px section gap for readability and breathability.

### Don't
- Avoid introducing additional saturated colors unless explicitly assigned a semantic role; maintain the largely achromatic palette.
- Do not use hard, sharp corners; all significant UI elements like cards and buttons should soften with the established radii of 8px or 9999px.
- Refrain from using strong, opaque box shadows; prefer the subtle elevation provided by the detected shadows for interactive elements if needed, or no shadow at all.
- Do not vary line heights or letter-spacing outside the defined SuisseIntl and ui-monospace typography rules.
- Avoid complex gradients; adhere to solid color fills for backgrounds and surfaces.
- Do not rely on color alone to convey crucial information; always pair color with text or iconography.
- Steer clear of dense, cluttered layouts; prioritize ample white space, especially around body copy and calls to action.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#e5e7eb` | The base background for many sections, providing a subtle off-white foundation. |
| 1 | Primary Surface | `#ffffff` | Standard background for cards, modals, and elements intended to appear on top of the Page Canvas. |
| 2 | Accent Surface | `#f3f4f6` | Alternative background for cards or sections, creating differentiation and depth without strong contrast. |

## Elevation

- **Button (subtle):** `rgba(0, 0, 0, 0.06) 0px 1px 6px 0px, rgba(0, 0, 0, 0.16) 0px 2px 32px 0px`
- **Card (subtle):** `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px`

## Imagery

The visual language predominantly features high-quality product photography of the e-bikes. These are often tightly cropped on pure white or cream backgrounds to highlight product details, or shown in dynamic lifestyle shots with blurred urban environments. Imagery is frequently full-bleed in hero sections or large content blocks, allowing the product to dominate. Icons are minimal, featuring a clean, outlined style in a single color, primarily for functional annotation rather than decoration. The overall impression is product-focused and sleek, with imagery playing a key role in conveying brand identity and product aspiration.

## Layout

The page primarily utilizes a full-bleed layout for hero sections, often featuring large product photography or conceptual imagery. Subsequent content sections frequently adopt a max-width contained pattern, with a strong vertical rhythm. Content often alternates between centered stacks of text and visuals, or two-column layouts where text and product imagery are presented side-by-side. Card grids are used for features or selections. The navigation is a persistent top bar, shifting between transparent on dark heroes and solid on lighter sections. Vertical spacing is comfortable, supporting a clean and uncrowded presentation.

## Agent Prompt Guide

Quick Color Reference:
text: #1d1d1d
background: #ffffff
border: #e5e7eb
accent: no distinct accent color
primary action: #1d1d1d (filled action)

Example Component Prompts:
Create a hero section: full-bleed dark background, centered headline 'Riding reinvented' in SuisseIntl 72px weight 600, Canvas White (#ffffff), letter-spacing -1.8px. Below it, a ghost button with 'Discover Cruiser' text in Canvas White (#ffffff), no background, 0px border-radius, 20px vertical, 24px horizontal padding, with Ink Black (#1d1d1d) text and background on hover.
Create a Primary Filled Button: text 'Book a test ride' in Canvas White (#ffffff), background Ink Black (#1d1d1d), border-radius 9999px, padding 20px vertical, 24px horizontal, SuisseIntl font.
Create a Feature Card: background Canvas White (#ffffff), border-radius 8px, padding 48px, containing a SuisseIntl 24px weight 600 Ink Black (#1d1d1d) heading and SuisseIntl 16px Ink Black (#1d1d1d) body text.
Create an Input Field: background Canvas White (#ffffff), border 1px solid Slate Border (#6b7280), border-radius 0px, placeholder text 'Email address' in Dim Gray (#737373), SuisseIntl 16px.

## Similar Brands

- **VanMoof** — Both brands sell premium e-bikes and share a minimalist aesthetic with a focus on product photography and clean typography.
- **Apple** — The product-centric imagery on clean backgrounds, subtle use of neutrals, and emphasis on product design over decorative UI elements resonate with Apple's visual style.
- **Dyson** — Uses high-contrast, often full-bleed product photography, a restrained color palette, and confident typography to showcase premium industrial design.
- **Aēsop** — Employs an elegant, minimalist approach with a strong emphasis on typography, natural color palettes, and a sense of calm visual space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1d1d1d;
  --color-whisper-gray: #e5e7eb;
  --color-dim-gray: #737373;
  --color-ash-cloud: #f3f4f6;
  --color-stone-gray: #a3a3a3;
  --color-slate-border: #6b7280;
  --color-forest-whisper: #569d5f;
  --color-action-blue: #2563eb;

  /* Typography — Font Families */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-intercom-font: 'intercom-font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.47;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.3px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.54px;
  --text-display-sm: 42px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.84px;
  --text-display: 52px;
  --leading-display: 0.95;
  --tracking-display: -1.3px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -1.8px;
  --text-display-xl: 100px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -2.5px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-176: 176px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 48px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-buttons: 9999px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 1px 6px 0px, rgba(0, 0, 0, 0.16) 0px 2px 32px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;

  /* Surfaces */
  --surface-page-canvas: #e5e7eb;
  --surface-primary-surface: #ffffff;
  --surface-accent-surface: #f3f4f6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1d1d1d;
  --color-whisper-gray: #e5e7eb;
  --color-dim-gray: #737373;
  --color-ash-cloud: #f3f4f6;
  --color-stone-gray: #a3a3a3;
  --color-slate-border: #6b7280;
  --color-forest-whisper: #569d5f;
  --color-action-blue: #2563eb;

  /* Typography */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-intercom-font: 'intercom-font', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.47;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.3px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.54px;
  --text-display-sm: 42px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.84px;
  --text-display: 52px;
  --leading-display: 0.95;
  --tracking-display: -1.3px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -1.8px;
  --text-display-xl: 100px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -2.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-176: 176px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 1px 6px 0px, rgba(0, 0, 0, 0.16) 0px 2px 32px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
}
```
