# Going™ — Style Reference
> energetic journey on lime

**Theme:** light

Going employs a vibrant and energetic design system, using a warm lime green as an expansive canvas, punctuated by deep teal text and a striking violet accent for primary actions. The aesthetic feels playful yet authoritative, with soft, rounded corners and sparse, subtle card shadows. Typography is confident and direct, maintaining legibility against varied backgrounds. The overall impression is one of approachable dynamism, steering clear of corporate sterility.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Lime | `#d7ffc2` | `--color-canvas-lime` | Primary page background, card surfaces, and subtle button accents, evoking a fresh, energetic base |
| Teal Ink | `#004449` | `--color-teal-ink` | Primary text, navigation links, and outlined button borders – a deep, authoritative voice against the lighter backgrounds |
| Action Violet | `#483cff` | `--color-action-violet` | Primary call-to-action buttons, prominent headlines – a vivid, saturated highlight signalling interaction and importance |
| Highlight Green | `#0bff80` | `--color-highlight-green` | Decorative color for some headlines and accents, adding a vibrant, almost neon touch |
| Pitch Black | `#000000` | `--color-pitch-black` | Highly prominent text, borders, and general UI elements requiring maximum contrast |
| Paper White | `#fffef0` | `--color-paper-white` | Button backgrounds, form fields, and secondary text, offering a soft, almost off-white contrast |

## Tokens — Typography

### PP Mori — The primary typeface for all text content, from body to display headings. Its clean, geometric forms provide a modern and legible foundation, while the varied weights allow for clear hierarchy and emphasis. · `--font-pp-mori`
- **Substitute:** Inter
- **Weights:** 400, 475, 600, 700
- **Sizes:** 14px, 16px, 18px, 24px, 28px, 40px, 48px, 80px
- **Line height:** 1.10, 1.14, 1.15, 1.17, 1.33, 1.40, 1.50
- **Letter spacing:** 0.0200em, 0.0600em, 0.1000em
- **Role:** The primary typeface for all text content, from body to display headings. Its clean, geometric forms provide a modern and legible foundation, while the varied weights allow for clear hierarchy and emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.02px | `--text-caption` |
| body-sm | 16px | 1.4 | 0.02px | `--text-body-sm` |
| body | 18px | 1.33 | 0.02px | `--text-body` |
| subheading | 24px | 1.17 | 0.06px | `--text-subheading` |
| heading | 40px | 1.15 | 0.06px | `--text-heading` |
| heading-lg | 48px | 1.14 | 0.06px | `--text-heading-lg` |
| display | 80px | 1.1 | 0.1px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

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
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 900px |
| general | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.04) 0px 2px 8px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 80px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with 'Action Violet' background (#483cff), 'Paper White' text (#fffef0), and a fully rounded ('pill') corner radius of 900px. Padding is 0px vertical and 32px horizontal. Used for primary CTAs like 'Join for free' and 'Get App'.

### Outlined Navigation Button
**Role:** Secondary action / Navigation

Outlined button with 'Teal Ink' border (#004449), 'Paper White' background (#fffef0), and a fully rounded ('pill') corner radius of 900px. Padding is 0px vertical and 32px horizontal. Used for secondary actions like 'Sign Up'.

### Lime Accent Button
**Role:** Tertiary action / Decorative

Filled button with 'Canvas Lime' background (#d7ffc2), 'Teal Ink' text (#004449), and a fully rounded ('pill') corner radius of 900px. Padding is 0px vertical and 32px horizontal. Used for less prominent calls to action or within certain sections.

### Content Card
**Role:** Content container

A card container with 'Canvas Lime' background (#d7ffc2), a 24px border radius, and a subtle shadow: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px. Used for testimonials and feature descriptions.

### Rating Badge
**Role:** Social proof / Endorsement

A decorative badge signaling social proof, using 'Teal Ink' text (#004449) on a transparent background, with no border radius or padding specified directly on the badge element itself, but often embedded within a larger container.

## Do's and Don'ts

### Do
- Prioritize 'Canvas Lime' (#d7ffc2) as the primary background for full sections and content cards to establish the brand's energetic foundation.
- Use 'Action Violet' (#483cff) exclusively for primary call-to-action buttons, ensuring high visual impact and clear user intent.
- Apply a 900px border radius to all interactive buttons and small tags or badges to maintain a soft, approachable, and consistent pill-like shape.
- Set the main body and link text in 'Teal Ink' (#004449) for optimal readability against both 'Canvas Lime' and 'Paper White' backgrounds.
- Maintain a spacious feel by using a section gap of 80px between major content blocks.
- Utilize PP Mori in varying weights (400, 475, 600, 700) to create a clear typographic hierarchy, from subtle body text to bold headlines, adhering to the specified letter-spacing for each size.
- Incorporate a subtle shadow (rgba(0, 0, 0, 0.04) 0px 2px 8px 0px) on 'Content Cards' to provide a gentle lift without heavy visual weight.

### Don't
- Do not introduce additional background or accent colors that deviate from the established palette of 'Canvas Lime', 'Teal Ink', 'Action Violet', and 'Highlight Green'.
- Avoid sharp corners; all primary UI elements (buttons, cards) should reflect the generous 900px or 24px radii.
- Do not use multiple, heavy shadows or complex gradients unless explicitly defined in the system; stick to the single, subtle card shadow for elevation.
- Refrain from using bold type for conversational body text; reserve higher weights for headings and emphasized elements only.
- Do not deviate from the established 16px element gap and 32px card padding, to maintain the brand's consistent spaciousness.
- Do not use 'Highlight Green' (#0bff80) as a functional UI element; it is reserved for decorative headline accents.
- Avoid primary actions that are not 'Action Violet' filled buttons; secondary actions can be outlined or lime-accented, but the main CTA is distinct.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Lime | `#d7ffc2` | Dominant page background, providing an energetic foundation to content sections. |
| 1 | Paper White | `#fffef0` | Alternate page background for hero sections and some content blocks, adding lightness and contrast. |
| 2 | Content Card | `#d7ffc2` | Elevated card surfaces for testimonials and detailed features, distinguished by a subtle shadow and rounded corners. |

## Elevation

- **Content Card:** `rgba(0, 0, 0, 0.04) 0px 2px 8px 0px`

## Agent Prompt Guide

Quick Color Reference:
text: #004449
background: #d7ffc2
border: #004449
accent: #483cff
primary action: #483cff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #483cff background, #fffef0 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

2. Design a feature card: 'Canvas Lime' (#d7ffc2) background, 24px border-radius, shadow: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px. Inner padding is 32px. Headline 'Track prices for all of your trips' in PP Mori weight 600 at 24px, color 'Teal Ink' (#004449), line-height 1.17, letter-spacing 0.06em. Body text 'Tell us your trip details—we’ll track prices and alert you when they change.' in PP Mori weight 400 at 16px, color 'Teal Ink' (#004449), line-height 1.4, letter-spacing 0.02em.

## Similar Brands

- **Calm** — Uses a limited, bright, and calming color palette with soft shapes and gradients to create a serene user experience.
- **Headspace** — Features playful illustrations, a vibrant color scheme, and rounded components to convey an approachable and friendly brand.
- **Oura Ring** — Employs clean and spacious layouts, a distinct accent color, and high-quality product imagery within a clear interface.
- **Credit Karma** — Combines a foundational green hue with clear, actionable CTAs and a clean typographic hierarchy for a trustworthy feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-lime: #d7ffc2;
  --color-teal-ink: #004449;
  --color-action-violet: #483cff;
  --color-highlight-green: #0bff80;
  --color-pitch-black: #000000;
  --color-paper-white: #fffef0;

  /* Typography — Font Families */
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.02px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.02px;
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.17;
  --tracking-subheading: 0.06px;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --tracking-heading: 0.06px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: 0.06px;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: 0.1px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w475: 475;
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
  --spacing-104: 104px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 900px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 900px;
  --radius-general: 16px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px;

  /* Surfaces */
  --surface-canvas-lime: #d7ffc2;
  --surface-paper-white: #fffef0;
  --surface-content-card: #d7ffc2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-lime: #d7ffc2;
  --color-teal-ink: #004449;
  --color-action-violet: #483cff;
  --color-highlight-green: #0bff80;
  --color-pitch-black: #000000;
  --color-paper-white: #fffef0;

  /* Typography */
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.02px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.02px;
  --text-body: 18px;
  --leading-body: 1.33;
  --tracking-body: 0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.17;
  --tracking-subheading: 0.06px;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --tracking-heading: 0.06px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: 0.06px;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: 0.1px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 900px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px;
}
```
