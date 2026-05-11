# Acceptandproceed — Style Reference
> Gallery Canvas, Subtle Presence

**Theme:** light

Accept&Proceed presents a subtly textured, spacious environment that feels like a quiet gallery space. Neutral tones dominate, allowing content and subtle interaction cues to stand out. Typography is precise and understated, maintaining a sense of refined professionalism. Interactions are minimal and direct, avoiding heavy graphics or loud effects, reinforcing an atmosphere of focused artistic curation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, major borders, subtle ghost button borders, essential iconography |
| Fog | `#8c8c8c` | `--color-fog` | Muted text, secondary borders, background for inactive badge states |
| Cloud Cover | `#ecebe7` | `--color-cloud-cover` | Background for filled buttons and interactive elements, providing a subtle lift from the canvas |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, elevated surface backgrounds in light theme |
| Warm Linen | `#f9f7f3` | `--color-warm-linen` | Secondary page and card backgrounds, serving as a subtly warmer alternative to pure white |
| Steel Gaze | `#a2a1a1` | `--color-steel-gaze` | Hairline borders for badges and small UI elements, providing structure with minimal visual weight |
| Carbon Text | `#333333` | `--color-carbon-text` | Text within specific input fields, slightly softer than Midnight Ink |

## Tokens — Typography

### Messina Sans — Primary typeface for all UI elements, body text, headings, and interactive components. Its consistent weight and precise tracking maintain a readable, contemporary feel across all sizes. · `--font-messina-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 8px, 10px, 14px, 17px, 20px, 24px, 34px, 50px, 72px
- **Line height:** 1.00, 1.28, 1.29, 1.33, 1.40, 1.41, 1.43, 1.60, 1.71
- **Letter spacing:** -0.01em
- **Role:** Primary typeface for all UI elements, body text, headings, and interactive components. Its consistent weight and precise tracking maintain a readable, contemporary feel across all sizes.

### Letterformvariations 04 Dmgx — Decorative typeface used for specific display text or artistic branding elements, providing a distinct, bespoke character at larger sizes. · `--font-letterformvariations-04-dmgx`
- **Substitute:** PT Serif
- **Weights:** 400
- **Sizes:** 34px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Decorative typeface used for specific display text or artistic branding elements, providing a distinct, bespoke character at larger sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | -0.01px | `--text-body` |
| button | 17px | 1.41 | -0.01px | `--text-button` |
| subheading | 20px | 1.4 | -0.01px | `--text-subheading` |
| heading-sm | 24px | 1.29 | -0.01px | `--text-heading-sm` |
| heading | 34px | 1.33 | -0.01px | `--text-heading` |
| heading-lg | 50px | 1.6 | -0.01px | `--text-heading-lg` |
| display | 72px | 1.71 | -0.01px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 3.4px |
| inputs | 100px |
| buttons | 20px |

### Layout

- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Filled Button: Read Story Large
**Role:** Primary interactive button for calls to action.

Background: Cloud Cover (#ecebe7), Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000), Radius: 20px. Padding variable but a common instance is 12px vertical, 33px horizontal. Font: Messina Sans 400.

### Ghost Button: Navigation Link
**Role:** Subtle navigation or secondary action within content. Inherits text color from parent context.

Background: transparent, Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000). No border-radius. Padding of 15px vertical, 0px horizontal. Font: Messina Sans 400.

### Pill Button: Curved Left
**Role:** Unique interactive element, often for specialized actions or tags, with an asymmetric pill shape.

Background: rgba(0, 0, 0, 0.05) (a very light black tint), Text: Midnight Ink (#000000), Border: 1px solid Midnight Ink (#000000), Radius: 100px 0px 0px 100px (curved left side). Padding 8px vertical, 18-20px horizontal. Font: Messina Sans 400.

### Project Card: Image Top
**Role:** Container for project previews, featuring an imagery block and descriptive text.

Background: transparent, no explicit border or shadow, Radius: 8px. Internally, content may use 12px or 15px padding. Image blocks are sharp-edged, but the containing card defines 8px rounded corners.

### Soft Badge: Outlined Text
**Role:** Categorization or tagging element, visually lightweight.

Background: transparent, Text: Midnight Ink (#000000), Border: 1px solid Steel Gaze (#a2a1a1), Radius: 3.4px. No padding at the badge level, internal element spacing (4px) may apply.

### Muted Badge: Grey Background
**Role:** Secondary categorization, distinct from active or primary tags.

Background: Fog (#8c8c8c), Text: Midnight Ink (#000000), no explicit border. No border-radius. No padding at the badge level.

### Rounded Input Field: Curved Left
**Role:** Input element with a distinct rounded style for forms.

Background: rgba(0, 0, 0, 0.05), Placeholder Text: Carbon Text (#333333), Border: 1px solid Midnight Ink (#000000), Radius: 100px 0px 0px 100px (curved left side). Padding 8px vertical, 20px left. Font: Messina Sans 400.

### Listen Button: Minimal
**Role:** Interactive element for audio content, integrated subtly into lists.

Background: transparent, Text: Midnight Ink (#000000), no explicit border or radius. Padding is around 15px vertical, 0px horizontal for alignment within list items. Font: Messina Sans 400.

## Do's and Don'ts

### Do
- Use Fog (#8c8c8c) for all muted text, secondary icon outlines, and inactive UI elements.
- Apply a 20px border-radius to all primary action buttons, using Cloud Cover (#ecebe7) for the background and Midnight Ink (#000000) for text and border.
- Maintain -0.01em letter-spacing for all Messina Sans text elements to preserve typographic precision.
- Organize content into clean card structures with an 8px border-radius, remaining transparent and shadowless.
- Utilize Warm Linen (#f9f7f3) or Canvas White (#ffffff) as primary neutral surface backgrounds, alternating for visual segmentation.
- Implement the 3.4px border-radius for badges to create subtle corner rounding distinct from larger components.
- Ensure a minimum elementGap of 8px between discrete UI elements, especially within containers like badges or form fields.

### Don't
- Do not introduce strong accent colors; confine the palette to the established neutrals for content segmentation and interaction.
- Avoid heavy drop shadows or significant elevation; the design relies on subtle background shifts and borders for separation.
- Do not use generic button styles; prefer the pre-defined Filled, Ghost, or Pill variants with their specific radii and visual properties.
- Refrain from using varied letter-spacings beyond the Messina Sans default; maintain consistent tracking.
- Do not use highly saturated imagery; imagery should be high-contrast or desaturated to complement the neutral palette.
- Avoid decorative gradients; the system prefers flat colors and subtle textural shifts.
- Do not vary line heights significantly; adhere to the Messina Sans predefined line-height scale for all text roles.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Warm Linen | `#f9f7f3` | Secondary background layer, often for content sections or cards |
| 2 | Cloud Cover | `#ecebe7` | Interactive elements like filled buttons, providing a subtle pop over backgrounds |

## Imagery

Imagery primarily features product shots, abstract digital renderings (like the globe), and high-contrast event photography. Photography leans towards moody or impactful scenes with desaturated or monochrome treatments, emphasizing shape and form over vibrant color. Illustrations are digital, often abstract and volumetric like the blue globe effect, serving an explanatory or atmospheric role rather than literal representation. Icons are minimal, outlined, thin, and monochrome (Midnight Ink) for functionality. Imagery is often contained within card structures or hero sections, acting as key content rather than decorative filler, and sometimes full-bleed in hero sections.

## Layout

The site uses a max-width contained layout with centered content blocks, punctuated by occasional full-bleed hero sections. The header is sticky and minimal. Sections are vertically stacked with consistent spacing (48px sectionGap), creating a rhythmic flow. Content often alternates between left-aligned text and right-aligned visuals or vice-versa within a two-column grid. Project listings often utilize a multi-column card grid pattern. Density is comfortable, with ample whitespace providing breathable separation between elements and sections.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a transparent project card: background transparent, no border or shadow, 8px border-radius. Inside place an image full width and a heading 'Featured Project' in Messina Sans 400, 24px, -0.01em letter-spacing, color Midnight Ink (#000000).
3. Generate a soft badge: background transparent, text Midnight Ink (#000000), 1px solid Steel Gaze (#a2a1a1) border, 3.4px border-radius. Text 'Technology' in Messina Sans 400, 8px, -0.01em letter-spacing. Use 4px elementGap around its content.

## Similar Brands

- **Kontrapunkt** — Shares a precise, minimal, and typography-driven aesthetic with careful use of negative space and neutral palette.
- **B-Reel** — Features a similar gallery-like presentation of work, often with large imagery and understated UI in a light theme.
- **North Kingdom** — Utilizes a clean, art-focused approach with a premium feel, relying on strong visuals and subtle UI interactions within a neutral framework.
- **Basic/Dept** — Employs an editorial layout and sophisticated achromatic palette to highlight high-quality imagery and precise typography for agency work.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-fog: #8c8c8c;
  --color-cloud-cover: #ecebe7;
  --color-canvas-white: #ffffff;
  --color-warm-linen: #f9f7f3;
  --color-steel-gaze: #a2a1a1;
  --color-carbon-text: #333333;

  /* Typography — Font Families */
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-letterformvariations-04-dmgx: 'Letterformvariations 04 Dmgx', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-button: 17px;
  --leading-button: 1.41;
  --tracking-button: -0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: -0.01px;
  --text-heading: 34px;
  --leading-heading: 1.33;
  --tracking-heading: -0.01px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.6;
  --tracking-heading-lg: -0.01px;
  --text-display: 72px;
  --leading-display: 1.71;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 3.4px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 3.4px;
  --radius-inputs: 100px;
  --radius-buttons: 20px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-linen: #f9f7f3;
  --surface-cloud-cover: #ecebe7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-fog: #8c8c8c;
  --color-cloud-cover: #ecebe7;
  --color-canvas-white: #ffffff;
  --color-warm-linen: #f9f7f3;
  --color-steel-gaze: #a2a1a1;
  --color-carbon-text: #333333;

  /* Typography */
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-letterformvariations-04-dmgx: 'Letterformvariations 04 Dmgx', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-button: 17px;
  --leading-button: 1.41;
  --tracking-button: -0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: -0.01px;
  --text-heading: 34px;
  --leading-heading: 1.33;
  --tracking-heading: -0.01px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.6;
  --tracking-heading-lg: -0.01px;
  --text-display: 72px;
  --leading-display: 1.71;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-md: 3.4px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 100px;
}
```
