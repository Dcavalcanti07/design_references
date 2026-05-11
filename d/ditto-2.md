# Ditto — Style Reference
> Parchment and Ink with Marigold Accents

**Theme:** light

Ditto presents a grounded yet vibrant aesthetic, combining rich, deep purple-blue with a sunny yellow accent and a muted, almost parchment-like background. The visual system balances seriousness with approachability, featuring soft, rounded corners and a dense, information-rich layout. Typography leans towards a strong, modern sans-serif for functional elements and a traditional serif for impactful headlines, creating a subtle tension between heritage and forward-thinking. Color is used functionally, with neutral backgrounds forming a canvas for clear hierarchy and a bold accent for interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#130e30` | `--color-midnight-ink` | Primary text, deep surface elements, button backgrounds for secondary actions, interactive states — creates visual depth and anchors content |
| Marigold Burst | `#ffe228` | `--color-marigold-burst` | Primary action buttons, accent details, interactive highlights — a vivid, warm contrast against neutrals and dark tones, signaling key interactions |
| Frosted Sage | `#eff2e5` | `--color-frosted-sage` | Card backgrounds, section separators, input fields — a soft, off-white neutral that adds warmth and texture as a primary surface |
| Paper White | `#f9fbf2` | `--color-paper-white` | Page background, light button backgrounds, light surface elements — provides a clean, bright canvas |
| Graphite | `#222222` | `--color-graphite` | Secondary text, neutral button borders, active navigation text — provides strong contrast while remaining slightly softer than pure black |
| Subtle Ash | `#5f5c6e` | `--color-subtle-ash` | Muted text, helper text, subtle borders, inactive icon fills — a mid-tone gray for subtle visual separation and less prominent information |
| Pure Black | `#000000` | `--color-pure-black` | Input borders, separator lines where strong definition is needed — used sparingly for sharp edges |
| Vivid Shamrock | `#59e25d` | `--color-vivid-shamrock` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Electric Fuchsia | `#e261e5` | `--color-electric-fuchsia` | Decorative accent for illustrations, highlight elements where strong visual interest is required |
| Sky Blue | `#3a93ff` | `--color-sky-blue` | Blue decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |

## Tokens — Typography

### Hedvig Letters Serif — Headlines and prominent display text — the serif style at larger sizes and subtle negative letter-spacing creates a sense of established authority and refined impact. · `--font-hedvig-letters-serif`
- **Substitute:** Georgia
- **Weights:** 400, 700
- **Sizes:** 22px, 32px, 48px, 64px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.25
- **Letter spacing:** -0.0100em
- **Role:** Headlines and prominent display text — the serif style at larger sizes and subtle negative letter-spacing creates a sense of established authority and refined impact.

### Inter — Body copy, navigation, buttons, and all functional UI elements — its neutral, highly legible character ensures clear information delivery across various content densities. Tighter tracking for larger sizes provides a compact, modern feel. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 14px, 16px, 18px, 22px
- **Line height:** 1.20, 1.25, 1.50
- **Letter spacing:** -0.0200em at 22px, -0.0100em at 18px
- **Role:** Body copy, navigation, buttons, and all functional UI elements — its neutral, highly legible character ensures clear information delivery across various content densities. Tighter tracking for larger sizes provides a compact, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.25 | -0.18px | `--text-subheading` |
| heading-sm | 22px | 1.25 | -0.44px | `--text-heading-sm` |
| heading | 32px | 1.15 | -0.32px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.48px | `--text-heading-lg` |
| display | 64px | 1 | -0.64px | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| images | 24px |
| avatars | 1440px |
| buttons | 1440px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Call to action

Filled with Marigold Burst (#ffe228) background, Midnight Ink (#130e30) text, 1440px border-radius, 12px vertical padding, 22px horizontal padding. Uses Inter font.

### Secondary Filled Button
**Role:** Alternative action

Filled with Midnight Ink (#130e30) background, Paper White (#f9fbf2) text, 1440px border-radius, 12px vertical padding, 22px horizontal padding. Uses Inter font.

### Ghost Button
**Role:** Navigation, tertiary actions

Transparent background, Graphite (#222222) text and 1px border. 1440px border-radius, 14.08px vertical padding, 24px horizontal padding. Uses Inter font.

### Content Card
**Role:** Information container

Frosted Sage (#eff2e5) background, 24px border-radius, 24px padding on all sides. No shadow, creating a flat, layered appearance.

### Input Field
**Role:** User input

Transparent background, Midnight Ink (#130e30) text, 0px border-radius, with Pure Black (#000000) bottom border for emphasis. 0px vertical padding, 16px horizontal padding. Uses Inter font.

### Compact Button
**Role:** Within forms or small actions

Paper White (#f9fbf2) background, Midnight Ink (#130e30) text, 1440px border-radius, 1px vertical padding, 6px left padding, 12px right padding. Used for combined elements like input with an appended button.

## Do's and Don'ts

### Do
- Use Midnight Ink (#130e30) for all primary text and main headlines to establish visual weight.
- Apply Marigold Burst (#ffe228) exclusively for primary call-to-action buttons and key interactive highlights, emphasizing its role as the principal accent.
- Maintain a default border-radius of 1440px for all buttons and interactive elements, conveying a soft, approachable feel.
- Structure information using Frosted Sage (#eff2e5) as a background for grouped content like cards, distinct from the Paper White (#f9fbf2) page background.
- Pair Hedvig Letters Serif for all significant headlines (H1-H3) with generous line heights (1.1-1.15) to enhance its distinguished presence.
- Utilize Inter at 14px (weight 400 or 500) for body text with a lineHeight of 1.50 for optimal readability.
- Ensure a consistent 24px padding for all content cards, establishing a clean, structured internal rhythm.

### Don't
- Do not introduce new saturated primary colors; limit the palette to Midnight Ink, Marigold Burst, and the associated decorative accents.
- Avoid applying shadows or heavy borders to cards; maintain a flat, layered surface aesthetic using background colors alone.
- Do not deviate from the specified negative letter-spacing for Hedvig Letters Serif headlines; a tighter track is part of its character.
- Do not use Marigold Burst (#ffe228) for anything other than explicit interactive calls to action or small, intentional highlights, to preserve its impact.
- Do not use generic system fonts when Inter is available; Inter provides the specific modern and legible tone required.
- Do not create buttons with hard, square corners; all buttons must use the 1440px radius for consistency.
- Avoid dense text blocks by ensuring adequate line heights, particularly for Inter body text, and consistent element gaps of 12px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#f9fbf2` | The primary background, clean and bright, for the overall layout. |
| 2 | Content Card | `#eff2e5` | Slightly darker, warmer background for grouped content like cards and sections, providing subtle visual layering without elevation. |
| 3 | Prominent Accent | `#ffe228` | Used for primary interactive elements, standing out as a focal point. |
| 4 | Deep Surface | `#130e30` | Used for dark-themed components or sections, providing strong contrast and visual gravity. |

## Imagery

The imagery strategy heavily features technical product screenshots, depicting dashboards and interfaces, often presented within a device mockup or floating freely on a textured background. These product visuals are clean, detailed, and serve an explanatory content role. When present, decorative elements are abstract, geometric shapes in brand accent colors (Electric Fuchsia, Sky Blue, Vivid Shamrock), often organic or flowing, and used as background embellishments. Photography is sparse, appearing mostly in testimonials as small, contained circular profile pictures. Icons are outlined, fine-lined, and monochrome, often using the Subtle Ash or Midnight Ink color, conveying a lightweight and modern feel. Overall, the visual density is moderate, with product imagery carrying significant informational weight.

## Layout

The page employs a max-width contained layout, likely around 1200px, with content centered. The hero section features a left-aligned, prominent headline and subtext, contrasted with a large, illustrative product screenshot on the right. Below the hero, sections alternate between a centered headline with supportive text and grids of content cards. There's a clear use of 3-column card grids for features and testimonials. Distinct, comfortable vertical spacing (48px section gap) creates a readable rhythm between blocks, while cards within grids maintain a consistent 24px padding. Navigation is a top bar, with 'Log in' and 'Get Started' buttons prominently displayed, indicating key user journeys.

## Agent Prompt Guide

Quick Color Reference:
text: #130e30
background: #f9fbf2
border: #000000
accent: #ffe228
primary action: #ffe228 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ffe228 background, #222222 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a content card: Frosted Sage (#eff2e5) background, 24px border-radius, 24px padding. Contains a Hedvig Letters Serif headline at 32px, weight 700, Midnight Ink (#130e30) color, and Inter body text at 14px, weight 400, Midnight Ink (#130e30) color.
3. Create a navigation ghost button: Transparent background, Graphite (#222222) text and 1px border. 1440px border-radius, 14.08px vertical padding, 24px horizontal padding. Text is Inter font, weight 500, size 16px.
4. Create an input field: Transparent background, 0px border-radius, 0px vertical padding, 16px horizontal padding. Has a Pure Black (#000000) bottom border. Placeholder text in Subtle Ash (#5f5c6e), input text in Midnight Ink (#130e30). Uses Inter font, weight 400, size 16px.

## Similar Brands

- **Rippling** — Uses a similar warm, muted off-white background with bold, rounded buttons and a strong, dark primary text color.
- **Notion** — Employs a clean, minimal UI with soft neutral backgrounds, functional typography, and a prominent dark primary text color, with color used sparingly for functional accents.
- **Webflow** — Features a light, spacious layout with a focus on polished product visuals and clear, legible typography, using accent colors judiciously for interactive elements.
- **Stripe** — Combines a clean, almost monochrome base with a single, vibrant accent color for calls to action, relying on strong typography and ample white space for visual clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #130e30;
  --color-marigold-burst: #ffe228;
  --color-frosted-sage: #eff2e5;
  --color-paper-white: #f9fbf2;
  --color-graphite: #222222;
  --color-subtle-ash: #5f5c6e;
  --color-pure-black: #000000;
  --color-vivid-shamrock: #59e25d;
  --color-electric-fuchsia: #e261e5;
  --color-sky-blue: #3a93ff;

  /* Typography — Font Families */
  --font-hedvig-letters-serif: 'Hedvig Letters Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.44px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.32px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

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

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 1440px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-images: 24px;
  --radius-avatars: 1440px;
  --radius-buttons: 1440px;

  /* Surfaces */
  --surface-page-canvas: #f9fbf2;
  --surface-content-card: #eff2e5;
  --surface-prominent-accent: #ffe228;
  --surface-deep-surface: #130e30;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #130e30;
  --color-marigold-burst: #ffe228;
  --color-frosted-sage: #eff2e5;
  --color-paper-white: #f9fbf2;
  --color-graphite: #222222;
  --color-subtle-ash: #5f5c6e;
  --color-pure-black: #000000;
  --color-vivid-shamrock: #59e25d;
  --color-electric-fuchsia: #e261e5;
  --color-sky-blue: #3a93ff;

  /* Typography */
  --font-hedvig-letters-serif: 'Hedvig Letters Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.44px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.32px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 1440px;
}
```
