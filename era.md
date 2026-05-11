# Era — Style Reference
> Swiss AI interface on frosted glass

**Theme:** light

Era uses a subdued, commanding aesthetic that pairs clear, functional Swiss typography with a near-monochromatic palette grounded in off-white surfaces and deep charcoal text. Subtle gradients and barely-there grays define boundaries without harshness, creating an atmosphere of quiet authority. Interactions are marked by filled buttons in deep gray, ensuring clarity and precision, while content is presented with generous negative space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#191a17` | `--color-midnight-charcoal` | Primary text, heading text, primary button fills, link default state, essential borders |
| Canvas Fog | `#f3f3f1` | `--color-canvas-fog` | Page background, main card surfaces — establishes the primary light theme base |
| Surface Mist | `#e6e6e4` | `--color-surface-mist` | Secondary surface backgrounds, subtle dividers, ghost button fills |
| Snow Drift | `#ffffff` | `--color-snow-drift` | Button text on dark backgrounds, icon fills, card backgrounds for elevated content |
| Ash Gray | `#868784` | `--color-ash-gray` | Muted secondary text, placeholder text, inactive icon fills, subtle borders |
| Slate Tint | `#3d3d3d` | `--color-slate-tint` | Dark badge backgrounds, text on light badge backgrounds |
| Aqua Haze | `#add2d1` | `--color-aqua-haze` | Light card backgrounds, decorative accents in a cool, desaturated tone |
| Ocean Whisper | `#9dbebe` | `--color-ocean-whisper` | Subtle button backgrounds, complementary accents |
| Twilight Gradient | `linear-gradient(90deg, rgb(201, 197, 225) 0%, rgb(234, 211, 221) 100%)` | `--color-twilight-gradient` | Background for feature cards, creating a soft, ethereal context for product showcases |

## Tokens — Typography

### Saans VF — The primary typeface for all text content. Its variable font nature allows for precise weight selection, conveying a tone that is both authoritative and approachable. Numeric figures are explicitly tabular for alignment, supporting data-rich contexts. · `--font-saans-vf`
- **Substitute:** Inter
- **Weights:** 380, 400, 500, 600, 670
- **Sizes:** 12px, 13px, 15px, 16px, 20px, 30px, 35px, 56px
- **Line height:** 1.15, 1.20, 1.25, 1.30, 1.38, 1.40, 1.50
- **Letter spacing:** -0.24, -0.26, -0.3, -0.32, -0.4, -0.6, -0.7, -1.12
- **OpenType features:** `'lnum' on, 'tnum' on`
- **Role:** The primary typeface for all text content. Its variable font nature allows for precise weight selection, conveying a tone that is both authoritative and approachable. Numeric figures are explicitly tabular for alignment, supporting data-rich contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.24px | `--text-caption` |
| body | 15px | 1.38 | -0.3px | `--text-body` |
| subheading | 20px | 1.3 | -0.4px | `--text-subheading` |
| heading | 30px | 1.25 | -0.6px | `--text-heading` |
| heading-lg | 35px | 1.2 | -0.7px | `--text-heading-lg` |
| display | 56px | 1.15 | -1.12px | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 6px |
| buttons | 9999px |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, commands immediate attention.

Background: Midnight Charcoal (#191a17), Text: Snow Drift (#ffffff). Border radius: 9999px for a pill shape. Padding: 8px vertical, 16px horizontal. Font: Saans VF weight 500.

### Google Login Button
**Role:** External authentication, visually distinct from primary actions but still prominent.

Background: Midnight Charcoal (#191a17), Text: Snow Drift (#ffffff). Border radius: 9999px. Padding: 0px vertical, 16px horizontal. Contains an icon for branding.

### Ghost Button
**Role:** Secondary action or navigation, minimal visual weight.

Background: transparent. Text: Midnight Charcoal (#191a17) or current context's primary text color. Border: 1px solid Midnight Charcoal (#191a17). No padding implied by the data, indicating usage as a discreet text link or icon button.

### Outlined CTA Button
**Role:** Call to action with less emphasis than a filled button, like 'Add to Claude'.

Background: Surface Mist (#e6e6e4). Text: Midnight Charcoal (#191a17). Border: 1px solid Midnight Charcoal (#191a17). Border radius: 9999px. Padding: 8px vertical, 16px horizontal.

### Standard Card
**Role:** Container for content sections, usually on the main canvas.

Background: Canvas Fog (#f3f3f1). Border radius: 12px. Padding: 8px. No shadow, relying on background color difference for distinction.

### Hero Feature Card (Gradient)
**Role:** Highlighting key product features with a soft, engaging visual.

Background: Twilight Gradient (linear-gradient(90deg, #c9c5e1 0%, #ead3dd 100%)). Border radius: 12px. Padding: 0px. Text is directly on the gradient.

### Dark Feature Card
**Role:** Presenting product features in a distinct, dark mode context against the light canvas.

Background: Midnight Charcoal (#191a17). Border radius: 12px. Padding: 0px.

### Light Badge
**Role:** Categorization or small informational labels.

Background: rgba(25, 26, 23, 0.08) (a very light tint of Midnight Charcoal). Text: Midnight Charcoal (#191a17). Border radius: 6px. Padding: 4px vertical, 12px horizontal.

### Dark Badge
**Role:** Secondary categorization or status, with higher contrast.

Background: Slate Tint (#3d3d3d). Text: Snow Drift (#ffffff). Border radius: 6px. Padding: 4px vertical, 12px horizontal.

### FAQ Accordion Item
**Role:** Interactive content disclosure.

Background: transparent. Text: Midnight Charcoal (#191a17). Bottom border: 1px solid Surface Mist (#e6e6e4). Default spacing includes a 16px horizontal padding. No distinct radius, appears as part of a list structure.

## Do's and Don'ts

### Do
- Prioritize Saans VF weight 400 for body text and 600-670 for headings to establish a clear hierarchy.
- Use Midnight Charcoal (#191a17) for all primary text and strong interactive elements.
- Maintain the pill shape (9999px border-radius) for all core action buttons.
- Employ Canvas Fog (#f3f3f1) as the dominant background across all main content areas.
- Incorporate the Twilight Gradient for feature cards or sections requiring a soft, engaging visual lift.
- Align text and UI elements to a consistent 8px grid, especially for padding around cards and button internals.
- Use subtle 1px solid borders in a slightly darker neutral (e.g., a variant of Surface Mist or Ash Gray) for separation over heavy shadows.

### Don't
- Avoid generic system fonts; always specify 'Saans VF' or its closest free substitute, 'Inter'.
- Do not introduce highly saturated colors for functional UI elements; color is used sparingly for accents and controlled gradients.
- Resist using hard, geometric shadows; if elevation is needed, use a very soft, spread-out shadow with low opacity.
- Never break the established type scale; use the predefined sizes and line heights for headings and body text.
- Avoid large, distinct borders on cards; cards are visually separated by background color and subtle radii.
- Do not deviate from the specified border radii; pill shapes (9999px) are for buttons, 12px for cards, and 6px for badges.
- Refrain from dense layouts; utilize generous white space and the specified section and element gaps to create a sense of breathing room.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Fog | `#f3f3f1` | Primary page background — the foundational layer of the light theme. |
| 2 | Surface Mist | `#e6e6e4` | Secondary background color for subtle differentiation of sections or ghost button fills, sitting just above the canvas. |
| 3 | Aqua Haze | `#add2d1` | Accented card backgrounds – visually distinct but still soft, used for feature highlights. |
| 4 | Snow Drift | `#ffffff` | Elevated card backgrounds, creating a clear boundary and sense of lift for important content blocks against the Canvas Fog. |
| 5 | Midnight Charcoal | `#191a17` | Darker card backgrounds for alternative feature presentation or specific UI elements like badges, creating high contrast. |

## Imagery

The site largely relies on product screenshots that are tightly cropped, showcasing interfaces on mobile devices. These images are contained within card-like structures, sometimes with rounded corners matching the UI components. Icons are linear/outlined with a consistent stroke weight, predominantly in Midnight Charcoal or Ash Gray, serving as minimal visual cues rather than decorative elements. There is a strong absence of traditional photography or complex illustrations, emphasizing a functional, UI-focused visual system.

## Layout

The page adheres to a max-width, centered content model, with content areas defined by generous horizontal margins. The hero section features a prominent, left-aligned headline with a right-aligned text block and action buttons, creating an asymmetric balance. Subsequent sections alternate between full-width content bands (like the trusted by partners section) and multi-column layouts for features (e.g., three cards in a grid). The overall rhythm is one of consistent vertical spacing between sections, maintaining a spacious and uncluttered feel, with clear distinctions but no harsh visual breaks. Navigation is a minimalist top bar with discrete text links and a 'get started' button.

## Agent Prompt Guide

Quick Color Reference:
text: #191a17
background: #f3f3f1
border: #e6e6e4
accent: #add2d1
primary action: #191a17 (filled action)

Example Component Prompts:

1. Create a primary call-to-action button: 'Get started free', Midnight Charcoal (#191a17) background, Snow Drift (#ffffff) text, 9999px radius, 8px vertical 16px horizontal padding, 'Saans VF' weight 500.
2. Design a hero feature card with a soft gradient background: 'Fewer financial mistakes.', Twilight Gradient (linear-gradient(90deg, #c9c5e1 0%, #ead3dd 100%)) as background, 'Saans VF' weight 670, #191a17 text, 12px border-radius, 0px padding. Place a mobile product screenshot element inside.
3. Build a ghost button for secondary action: 'Add to Claude', Surface Mist (#e6e6e4) background, #191a17 text, 9999px radius, 8px vertical 16px horizontal padding, 1px solid #191a17 border.
4. Construct a standard content card: Canvas Fog (#f3f3f1) background, 12px border-radius, 16px padding. Headline: 'Money that manages itself.', Saans VF weight 600, 30px, #191a17. Body text: Saans VF weight 400, 15px, #191a17.

## Similar Brands

- **Linear** — Monochromatic interface with crisp typography and subtle surface differentiation for clarity and focus.
- **Stripe** — Emphasis on Swiss-style typography, clean layouts, and functional use of color, primarily neutral with occasional soft accents.
- **Framer** — Minimalist design, strong typography, and a focus on product screenshots within structured layouts, often using gradients for visual interest.
- **Notion** — Systematic use of comfortable density, clear text hierarchy, and a reliance on grayscale for primary UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #191a17;
  --color-canvas-fog: #f3f3f1;
  --color-surface-mist: #e6e6e4;
  --color-snow-drift: #ffffff;
  --color-ash-gray: #868784;
  --color-slate-tint: #3d3d3d;
  --color-aqua-haze: #add2d1;
  --color-ocean-whisper: #9dbebe;
  --color-twilight-gradient: #c9c5e1;
  --gradient-twilight-gradient: linear-gradient(90deg, rgb(201, 197, 225) 0%, rgb(234, 211, 221) 100%);

  /* Typography — Font Families */
  --font-saans-vf: 'Saans VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body: 15px;
  --leading-body: 1.38;
  --tracking-body: -0.3px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.4px;
  --text-heading: 30px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.7px;
  --text-display: 56px;
  --leading-display: 1.15;
  --tracking-display: -1.12px;

  /* Typography — Weights */
  --font-weight-w380: 380;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-w670: 670;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 6px;
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-canvas-fog: #f3f3f1;
  --surface-surface-mist: #e6e6e4;
  --surface-aqua-haze: #add2d1;
  --surface-snow-drift: #ffffff;
  --surface-midnight-charcoal: #191a17;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #191a17;
  --color-canvas-fog: #f3f3f1;
  --color-surface-mist: #e6e6e4;
  --color-snow-drift: #ffffff;
  --color-ash-gray: #868784;
  --color-slate-tint: #3d3d3d;
  --color-aqua-haze: #add2d1;
  --color-ocean-whisper: #9dbebe;
  --color-twilight-gradient: #c9c5e1;

  /* Typography */
  --font-saans-vf: 'Saans VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body: 15px;
  --leading-body: 1.38;
  --tracking-body: -0.3px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.4px;
  --text-heading: 30px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.7px;
  --text-display: 56px;
  --leading-display: 1.15;
  --tracking-display: -1.12px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 9999px;
}
```
