# Heynds — Style Reference
> Vibrant AI Canvas

**Theme:** light

Heynds presents a bright, clean interface with a clear hierarchy driven by confident typography and a single vibrant orange accent. Surfaces are predominantly stark white, allowing the primary brand color to act as a focused highlight for actions and key information. Subtle organizational borders and minimal elevation maintain a lightweight and efficient feel, reinforcing the product's promise of speed and ease.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ember Orange | `#f53900` | `--color-ember-orange` | Primary action buttons, prominent headings, decorative icons, and links — driving immediate attention and brand recognition |
| Pale Peach | `#ffe0d6` | `--color-pale-peach` | Secondary action buttons, providing a softer, ghosted interactive state that aligns with the brand hue |
| Midnight Charcoal | `#040101` | `--color-midnight-charcoal` | Primary body text, headings, and key UI elements for strong legibility against light backgrounds |
| Canvas White | `#fffafa` | `--color-canvas-white` | Page background, card surfaces, and text for inverse states, establishing a clean, expansive base |
| Border Fog | `#e5e5e5` | `--color-border-fog` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Muted Ash | `#827e7e` | `--color-muted-ash` | Secondary body text, helper text, and less prominent information for reduced emphasis |
| Divider Gray | `#c0bcbc` | `--color-divider-gray` | Subtle background panels or soft dividing lines, often for content blocks |

## Tokens — Typography

### Geist — All textual content, from body to hero headlines. The consistent use of Geist across all sizes and weights establishes a unified, modern voice for the brand, prioritizing clarity and directness. · `--font-geist`
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 32px, 36px, 40px, 48px, 64px, 80px
- **Line height:** 1.00, 1.11, 1.25, 1.33, 1.40
- **Letter spacing:** normal
- **Role:** All textual content, from body to hero headlines. The consistent use of Geist across all sizes and weights establishes a unified, modern voice for the brand, prioritizing clarity and directness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body | 14px | 1.4 | — | `--text-body` |
| body-lg | 16px | 1.4 | — | `--text-body-lg` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 32px | 1.11 | — | `--text-heading` |
| heading-lg | 40px | 1.11 | — | `--text-heading-lg` |
| display | 48px | 1.11 | — | `--text-display` |
| display-lg | 64px | 1 | — | `--text-display-lg` |
| display-xl | 80px | 1 | — | `--text-display-xl` |

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
| 128 | 128px | `--spacing-128` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| buttons | 4px |
| smallComponents | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 112px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Command to drive user action

Filled with Ember Orange (#f53900), text in Canvas White (#fffafa), corners slightly rounded at 6px, and generous horizontal padding of 40px.

### Secondary Ghost Button
**Role:** Alternative action that is less prominent than the primary

Text in Ember Orange (#f53900), a 1px border in Ember Orange (#f53900), Canvas White (#fffafa) background, 6px border-radius, and 40px horizontal padding.

### Soft Secondary Button
**Role:** Subtle call to action, offering a light interactive state

Text in Ember Orange (#f53900), filled with Pale Peach (#ffe0d6), 6px border-radius, and 40px horizontal padding.

### Information Card
**Role:** Container for grouped content

Canvas White (#fffafa) background, 8px border-radius, no inherent padding from the component itself, relying on content for spacing. Uses no box-shadow for a flat appearance.

### Hero Headline
**Role:** Primary visual statement, capturing attention

Geist font, large sizes (e.g., 64px or 80px), Ember Orange for keywords and Midnight Charcoal for descriptive text, normal letter spacing, strong line height for visual impact.

### Accordion Item
**Role:** Expandable content section, typically for FAQs

Features a 1px Border Fog (#e5e5e5) bottom border for separation, with Midnight Charcoal (#040101) text. Typically uses Geist 16px for content.

## Do's and Don'ts

### Do
- Use Ember Orange (#f53900) exclusively for primary calls to action, prominent headlines, and decorative accents.
- Maintain a predominantly Canvas White (#fffafa) background for all main page content and card surfaces.
- Apply Geist font for all text elements, leveraging its various weights and sizes to establish clear typographic hierarchy.
- Utilize 4px border-radius for interactive elements like buttons and primary navigation items.
- Employ a 1px Border Fog (#e5e5e5) for subtle visual divisions and borders around cards or input fields.
- Prioritize generous horizontal padding of 40px for all button variants to create a comfortable click area.
- Implement the 9999px border-radius for small, non-interactive elements like tags or badges to create a pill shape.

### Don't
- Avoid introducing additional chromatic colors that could dilute the impact of Ember Orange.
- Do not use dark backgrounds for main content sections; Canvas White (#fffafa) is the default canvas.
- Refrain from using strong box-shadows; prefer flat elements or subtle 1px elevation shadows.
- Do not vary line-height significantly from the established scale; stick to default Geist line-heights for consistency.
- Avoid tight element spacing; ensure at least 24px between distinct UI elements for a comfortable density.
- Do not create buttons without a distinct visual style (filled, ghosted, or soft); every interactive button needs a consistent type.
- Do not neglect semantic text sizing; ensure body text aligns with 14px or 16px Geist for readability.

## Elevation

- **Card:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`

## Imagery

The site uses a combination of product illustrations and stylized, full-bleed backgrounds. Illustrations are abstract and organic, composed of thin, radiating lines that create a sense of movement and energy, always in a soft white or subtle brand-tinted gradient. Product screenshots are contained within a macOS frame, showcasing the software in its native environment. Icons are simple, filled, and primarily use Ember Orange (#f53900) or Midnight Charcoal (#040101). Imagery serves to create an atmospheric, energetic backdrop while clearly demonstrating the product's functionality.

## Layout

The page maintains a centered max-width content area (implicitly around 1200px) that allows for comfortable reading against a full-width background. The hero section features a prominent, centered headline with Ember Orange accents over an abstract white full-bleed illustration. Sections alternate between purely textual content blocks, text-left/visual-right patterns, and a multi-column feature grid using cards. Vertical rhythm is established by consistent section spacing, typically using the 112px section gap, creating a spacious and digestible flow. Navigation is a compact top bar with a primary action button, remaining sticky on scroll.

## Agent Prompt Guide

Quick Color Reference: 
text: #040101
background: #fffafa
border: #e5e5e5
accent: #f53900
primary action: #f53900 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #f53900 background, #fffafa text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Canvas White (#fffafa) background, 8px radius. Headline in Geist 24px, weight 600, #040101. Body text in Geist 16px, weight 400, #040101. Include a pill-shaped tag with a 9999px radius, Pale Peach (#ffe0d6) background and Ember Orange (#f53900) text.
3. Create an FAQ accordion item: Border Fog (#e5e5e5) 1px bottom border. Question text in Geist 16px, weight 500, #040101. Answer text in Geist 14px, weight 400, Muted Ash (#827e7e).

## Similar Brands

- **Raycast** — A macOS utility with a similar focus on speed and productivity, clean UI, and a single accent color for primary actions.
- **Linear** — Known for its minimalist, high-performance UI, strong typography, and a similar approach to white space and focused colored accents.
- **Craft.do** — A clear, intuitive document editor that values a clean canvas, direct interaction, and purposeful use of color for functional elements.
- **Superhuman** — Emphasizes a rapid, efficient user experience with a clean design, relying on typography and subtle color cues to guide users.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ember-orange: #f53900;
  --color-pale-peach: #ffe0d6;
  --color-midnight-charcoal: #040101;
  --color-canvas-white: #fffafa;
  --color-border-fog: #e5e5e5;
  --color-muted-ash: #827e7e;
  --color-divider-gray: #c0bcbc;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.11;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1.11;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --text-display-xl: 80px;
  --leading-display-xl: 1;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 112px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-buttons: 4px;
  --radius-smallcomponents: 12px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ember-orange: #f53900;
  --color-pale-peach: #ffe0d6;
  --color-midnight-charcoal: #040101;
  --color-canvas-white: #fffafa;
  --color-border-fog: #e5e5e5;
  --color-muted-ash: #827e7e;
  --color-divider-gray: #c0bcbc;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.11;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1.11;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --text-display-xl: 80px;
  --leading-display-xl: 1;

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
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```
