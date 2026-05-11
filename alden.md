# Alden — Style Reference
> open white canvas

**Theme:** light

Alden uses a bright, open light-mode aesthetic on a clean white canvas. Product interfaces are depicted with a subtle, soft gray background within the overall page. Typography is modern and airy, with generous line heights and subtle letter spacing for readability. Color is used sparingly: a muted sage green for primary actions, and a soft sky blue for a single emphasized text style, creating a focused visual hierarchy. Components are lightweight with rounded corners, prioritizing clear information display.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Charcoal Text | `#28262a` | `--color-charcoal-text` | Primary text, headings, dark surface backgrounds |
| Ash Gray | `#4a4a4c` | `--color-ash-gray` | Secondary text, muted borders, placeholder text |
| Parchment | `#f3f1eb` | `--color-parchment` | Subtle background for UI elements within cards, product mockups |
| Whisper Gray | `#dddcdd` | `--color-whisper-gray` | Muted badge backgrounds, light bordering for subtle dividers |
| Cloud Gray | `#cbcbcb` | `--color-cloud-gray` | Tertiary text, light borders, subtle separators |
| Zenith Blue | `#97cde5` | `--color-zenith-blue` | Highlight color for specific keywords in headings, card backgrounds where visual emphasis is needed |
| Sage Green | `#c8dfaa` | `--color-sage-green` | Primary action buttons, accented card backgrounds – conveys confirmation and forward momentum |

## Tokens — Typography

### Stk bureau Sans Book Trial — Dominant text for body, navigation, buttons, and most UI elements. Its clean, modern sans-serif form maintains clarity across all sizes. · `--font-stk-bureau-sans-book-trial`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 30px, 32px, 40px, 48px, 56px
- **Line height:** 1.00, 1.20, 1.30, 1.33, 1.50
- **Letter spacing:** -0.04em at 56px, -0.03em at 48px, -0.02em at 30-40px, 0.02em at 12-18px
- **Role:** Dominant text for body, navigation, buttons, and most UI elements. Its clean, modern sans-serif form maintains clarity across all sizes.

### Stk bureau Serif Book Trial — Used for hero headlines and key marketing statements; its serif character adds a touch of classic authority and gravitas, contrasting the sans-serif for hierarchy. · `--font-stk-bureau-serif-book-trial`
- **Substitute:** Playfair Display
- **Weights:** 400, 500
- **Sizes:** 24px, 40px, 48px, 56px, 258px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** -0.04em at 56px, -0.03em at 48px, -0.02em at 40px
- **Role:** Used for hero headlines and key marketing statements; its serif character adds a touch of classic authority and gravitas, contrasting the sans-serif for hierarchy.

### Inter — Inter — detected in extracted data but not described by AI · `--font-inter`
- **Weights:** 400
- **Sizes:** 32px, 40px
- **Line height:** 1.2, 1.3
- **Letter spacing:** -0.02
- **Role:** Inter — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.24px | `--text-caption` |
| body-sm | 14px | 1.33 | 0.28px | `--text-body-sm` |
| body | 16px | 1.3 | 0.32px | `--text-body` |
| subheading | 18px | 1.2 | 0.28px | `--text-subheading` |
| heading | 30px | 1.2 | -0.6px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.8px | `--text-heading-lg` |
| display | 56px | 1 | -2.24px | `--text-display` |

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
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 4px |
| badges | 30px |
| images | 24px |
| buttons | 100px |

### Layout

- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action.

Background: Sage Green (#c8dfaa). Text: Charcoal Text (#28262a). Border: none. Padding: 8px vertical, 20px horizontal. Radius: 100px (pill shape).

### Ghost Text Link
**Role:** Navigation links and subtle interactive elements.

Background: transparent. Text: Ash Gray (#4a4a4c). Border: none. Padding: 0. Type: Stk bureau Sans Book Trial, 16px, weight 400.

### Primary Card (Default)
**Role:** Informational cards displaying content in a structured layout.

Background: transparent (Canvas White). No internal padding indicated by content. Radius: 0px. Shadow: none.

### Accent Card (Charcoal)
**Role:** Elevated card for content requiring visual distinction, often product screenshots.

Background: Charcoal Text (#28262a). Padding: none. Radius: 16px. Shadow: none.

### Accent Card (Sage Green)
**Role:** Card with brand color background, often used for highlighting features.

Background: Sage Green (#c8dfaa). Padding: none. Radius: 16px. Shadow: none.

### Accent Card (Zenith Blue)
**Role:** Card with accent color background, for distinct content blocks or steps.

Background: Zenith Blue (#97cde5). Padding: none. Radius: 16px. Shadow: none.

### Muted Text Badge
**Role:** Categorization or informational tags with subtle presence.

Background: rgba(40, 38, 42, 0.16) (Charcoal Text 16% opacity). Text: Charcoal Text (#28262a). Padding: 0px vertical, 12px horizontal. Radius: 30px.

### White Background Badge
**Role:** Contextual tags used against varied backgrounds.

Background: Canvas White (#ffffff). Text: Charcoal Text (#28262a). Padding: 0px vertical, 16px horizontal. Radius: 50px.

## Do's and Don'ts

### Do
- Use Canvas White (#ffffff) as the default background for all pages and most content surfaces.
- Apply Sage Green (#c8dfaa) exclusively to primary calls to action and visual elements that signify completion or success.
- Utilize Stk bureau Sans Book Trial (or Inter) for all UI text, body copy, and component labels at weights 400-600.
- Employ a 100px border radius for all primary buttons to achieve a consistent pill shape.
- Maintain generous element spacing with a base unit of 16px between most interactive elements and content blocks.
- Reserve Stk bureau Serif Book Trial (or Playfair Display) for major headlines to establish a clear typographic hierarchy and visual anchor.
- Padding within cards should consistently use 40px on all sides, unless a specific component variant dictates otherwise.

### Don't
- Do not introduce new saturated colors; stick to the defined Sage Green and Zenith Blue for chromatic elements.
- Avoid using drop shadows for elevation; rely on background color changes or subtle borders for visual separation.
- Do not use transparent backgrounds for primary calls to action; always use Sage Green to ensure visibility and clarity.
- Refrain from using strong bold weights for body text; prioritize lighter weights (400, 500) from Stk bureau Sans Book Trial.
- Do not deviate from the defined border radii; maintain 100px for buttons, 30px for badges, and 16px for cards.
- Avoid tight line spacing, particularly for headlines; adhere to the generous line heights of 1.2-1.5 for optimal readability.
- Do not introduce decorative gradients; the design relies on solid colors and subtle achromatic shifts for depth.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Background | `#ffffff` | Dominant page and base section background. |
| 1 | Subtle UI Surface | `#f3f1eb` | Background for secondary UI elements, such as contained product mockups or subtle content blocks. |
| 2 | Accent Card Surface | `#c8dfaa` | Prominent card backgrounds, often for features or key information blocks. |

## Imagery

The imagery style is primarily product-focused, featuring UI screenshots of the Alden application within a muted 'Parchment' colored card. These are often contained with soft rounded corners (16px radius). Icons are subtle, primarily outlined or ghosted in 'Ash Gray' or 'Charcoal Text', and serve functional rather than decorative purposes. There are occasional small, soft-focused profile images (avatars) of people, likely for testimonials or team members, appearing either as circular cutouts or integrated into UI mockups. The overall density is text-dominant, with imagery serving to clarify feature explanations rather than create a rich visual atmosphere.

## Layout

The page layout is primarily a max-width contained design, centered on the screen, visible after the initial hero section. The hero prominently features a bold, centered headline over a clean white background, with a primary action button below. Sections alternate between simple centered text stacks and two-column layouts, often with text on one side and an illustrative UI mockup or graphic on the other. Vertical rhythm is established through consistent section gaps, relying on background color shifts (white to Parchment) to delineate content blocks rather than strong dividers. Navigation is a simple top bar, with a 'Get Started' button as a distinct, colored primary action.

## Agent Prompt Guide

Quick Color Reference:
text: #28262a
background: #ffffff
border: #4a4a4c
accent: #97cde5
primary action: #c8dfaa (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #c8dfaa background, #28262a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a 'Product Feature Card': Background is Parchment (#f3f1eb), 16px border radius, 40px padding. Inside, use a headline 'Effortless Scheduling' with Stk bureau Sans Book Trial, 30px, weight 600, #28262a, and body text 'Automate caregiver assignments with smart AI.' Stk bureau Sans Book Trial, 16px, weight 400, #4a4a4c.
3. Create a 'Testimonial Block': Canvas White background, 40px padding. Quote text: 'The healthcare landscape continues to evolve rapidly.' using Stk bureau Serif Book Trial, 24px, weight 400, #28262a, with 'optimized care delivery system' highlighted in Zenith Blue (#97cde5). Below, use a person's name 'Tim Harold' in Stk bureau Sans Book Trial, 16px, weight 500, #28262a, with a profile image using 24px border radius.

## Similar Brands

- **Rippling** — Clean white backgrounds, muted accent colors, and a focus on product UI screenshots for feature explanation.
- **Linear** — Minimalist aesthetic with high contrast text on light backgrounds and subtle interaction states.
- **Gusto** — Bright, approachable light-mode design with a single prominent brand color accent for actions and highlights.
- **Notion** — Prioritizes content clarity with a clean white canvas, limited color palette, and clear typographic hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-text: #28262a;
  --color-ash-gray: #4a4a4c;
  --color-parchment: #f3f1eb;
  --color-whisper-gray: #dddcdd;
  --color-cloud-gray: #cbcbcb;
  --color-zenith-blue: #97cde5;
  --color-sage-green: #c8dfaa;

  /* Typography — Font Families */
  --font-stk-bureau-sans-book-trial: 'Stk bureau Sans Book Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-stk-bureau-serif-book-trial: 'Stk bureau Serif Book Trial', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: 0.28px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.28px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.8px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -2.24px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 4px;
  --radius-badges: 30px;
  --radius-images: 24px;
  --radius-buttons: 100px;

  /* Surfaces */
  --surface-canvas-background: #ffffff;
  --surface-subtle-ui-surface: #f3f1eb;
  --surface-accent-card-surface: #c8dfaa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-text: #28262a;
  --color-ash-gray: #4a4a4c;
  --color-parchment: #f3f1eb;
  --color-whisper-gray: #dddcdd;
  --color-cloud-gray: #cbcbcb;
  --color-zenith-blue: #97cde5;
  --color-sage-green: #c8dfaa;

  /* Typography */
  --font-stk-bureau-sans-book-trial: 'Stk bureau Sans Book Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-stk-bureau-serif-book-trial: 'Stk bureau Serif Book Trial', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: 0.28px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.28px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.8px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -2.24px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 50px;
  --radius-full-2: 100px;
}
```
