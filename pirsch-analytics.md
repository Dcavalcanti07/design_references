# Pirsch Analytics — Style Reference
> Warm, grounded analytics

**Theme:** light

Pirsch Analytics presents a friendly, grounded data interface with a palette of soft neutrals and two distinct, warm accent colors: a sunny yellow and a fresh green. Its visual identity centers on legibility and a comfortable, almost tactile feel, achieved through rounded forms, ample spacing, and a consistent preference for black text on light, slightly off-white backgrounds. Components feel light and approachable, with minimal bordering and an emphasis on subtle background differentiation over strong elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, icons, dark button text, borders for outlines and cards — defines the core structural elements against light backgrounds |
| Ghostly Gray | `#f8f5ed` | `--color-ghostly-gray` | Background for cards and subtly differentiated surface elements — provides a soft, warm canvas contrasting with the stark white page background |
| Muted Stone | `#707070` | `--color-muted-stone` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Sunbeam Yellow | `#ffda6e` | `--color-sunbeam-yellow` | Primary call-to-action button backgrounds and illustrative elements — injects a vibrant, energetic visual cue for key interactions |
| Leafy Green | `#6ece9d` | `--color-leafy-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments |

## Tokens — Typography

### DM Sans — The sole typeface, offering clean readability for all content. Weight 500 for headings, and 400 for body text achieves a modern, approachable feel. Distinctive letter-spacing choices for larger display text and smaller metadata create hierarchy. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 28px, 64px
- **Line height:** 1.25, 1.50, 2.22
- **Letter spacing:** -0.016, 0.286
- **OpenType features:** `"ss03", "ss04"`
- **Role:** The sole typeface, offering clean readability for all content. Weight 500 for headings, and 400 for body text achieves a modern, approachable feel. Distinctive letter-spacing choices for larger display text and smaller metadata create hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | -0.016px | `--text-body` |
| body-lg | 18px | 1.5 | -0.016px | `--text-body-lg` |
| subheading | 20px | 1.25 | -0.016px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.016px | `--text-heading-sm` |
| heading | 28px | 1.25 | -0.016px | `--text-heading` |
| display | 64px | 1.25 | -0.016px | `--text-display` |

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
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 24px |
| cards | 24px |
| input | 6px |
| buttons | 12px |

### Layout

- **Section gap:** 48px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Action Button - Yellow
**Role:** Filled button

Background: Sunbeam Yellow (#ffda6e). Text: Midnight Ink (#000000). Radius: 12px. Padding: 0px vertical, 24px horizontal. Used for primary calls to action.

### Secondary Action Button - Green
**Role:** Filled button

Background: Leafy Green (#6ece9d). Text: Midnight Ink (#000000). Radius: 12px. Padding: 0px vertical, 24px horizontal. Used for secondary or alternative calls to action.

### Small Tag Button
**Role:** Informational tag

Background: rgba(0, 0, 0, 0.04). Text: Midnight Ink (#000000). Radius: 24px. Padding: 0px for compact sizing. Used for categories or status labels, like the 'EASY START' tag.

### Content Card
**Role:** Surface for grouped content

Background: Ghostly Gray (#f8f5ed). Radius: 24px. Padding: 48px on all sides. No box shadow, relying on background color for subtle separation from the canvas.

### Text Input Field
**Role:** User data entry

Background: rgba(0, 0, 0, 0.04). Text/Placeholder: Midnight Ink (#000000). Radius: 6px. Padding: 10px vertical, 12px left, 24px right. No visible border in default state.

## Do's and Don'ts

### Do
- Use DM Sans exclusively for all typography, leveraging weights 400 and 500 for primary text and headings respectively.
- Implement Sunbeam Yellow (#ffda6e) for primary interactive elements and Leafy Green (#6ece9d) for secondary actions or positive cues.
- Adhere to a 24px border radius for cards and larger tags, and a 12px radius for buttons to maintain a consistent soft, rounded aesthetic.
- Employ Ghostly Gray (#f8f5ed) as the background for content cards to provide subtle visual separation from the main page canvas.
- Ensure generous spacing, using 'elementGap': 16px for vertical and horizontal separation of sibling elements, and 'sectionGap': 48px between major content blocks.
- Prioritize Midnight Ink (#000000) for all primary text and headings to ensure high contrast and readability on light backgrounds.
- Use Muted Stone (#707070) for secondary descriptive text and subheadings to create a clear hierarchy without resorting to lighter weights of Midnight Ink.

### Don't
- Avoid using harsh shadows or strong borders for elevation; rely on background color differences or ample padding for visual separation.
- Do not deviate from the DM Sans typeface; introducing other fonts would compromise the brand's unified typographic voice.
- Refrain from using heavily saturated or dark background colors; the system is built on a light, subtle achromatic foundation.
- Do not use generic square or overly sharp corners; the brand aesthetic is defined by its soft, rounded edges.
- Avoid dense, information-packed sections without breathing room; maintain the 'comfortable' spacing density with 'elementGap': 16px and 'sectionGap': 48px.
- Do not introduce new accent colors; maintain consistency with Sunbeam Yellow (#ffda6e) and Leafy Green (#6ece9d) for all chromatic interactive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#FFFFFF` | Dominant page background, providing a clean, bright foundation. |
| 1 | Card Surface | `#f8f5ed` | Background for content cards, offering subtle visual depth and warmth against the pure white canvas. |

## Imagery

This site predominantly uses icons and UI elements. Where present, imagery appears as simple, clean product screenshots or abstract graphics. Product graphics often display compact, focused UI snippets, sometimes with a subtle yellow or green accent matching the brand. Icons are generally filled, black, and have a moderate stroke weight, conveying clarity and function. The overall density of imagery is low to moderate, with a strong emphasis on content and clear text, using visuals to explain or highlight rather than to dominate the visual space. Logos of partner brands are grayscale, underscoring the focus on content and analytics rather than visual fanfare.

## Layout

The page adheres to a max-width, center-aligned container model, but the exact value is not explicitly defined, allowing for a flexible appearance. Sections are typically full-width background blocks (implied by the screenshot's white canvas extending to edges), but content within them is contained. The hero section features a prominent headline centered over a background that appears to be the main canvas. Content sections alternate between major textual headers and descriptive paragraphs, often followed by a two-column layout presenting features or benefits with text and supporting visual elements (icons, small sections of UI). Vertical rhythm is created by consistent section gaps of 48px, providing ample breathing room. The layout avoids complex grid structures, favoring stacked blocks and simple column arrangements that underscore clarity and directness. Navigation is implied to be a top bar.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #FFFFFF (implied canvas)
- border: #000000 (for strong outlines), #707070 (for soft outlines)
- accent: #ffda6e
- primary action: #ffda6e (filled action)

**3-5 Example Component Prompts:**
- Create a section divider: Width 100%, height 1px, background color Midnight Ink (#000000), opacity 0.1, centered, with 48px vertical spacing above and below.
- Design a primary call-to-action button: Text 'Start Your Analytics Journey', font DM Sans weight 500, color Midnight Ink (#000000). Background Sunbeam Yellow (#ffda6e). Radius 12px. Padding 0px vertical, 24px horizontal. Minimum height 48px.
- Create a feature card: Background Ghostly Gray (#f8f5ed), border radius 24px. Inside, a heading 'Easy to Integrate' with DM Sans weight 500, #000000, size 24px, followed by body text 'Supports all major platforms and frameworks without hassle' with DM Sans weight 400, #707070, size 16px. Padding inside the card should be 48px.
- Generate an input field: Label 'Your Email' above the field with DM Sans weight 400, #000000, size 16px. Input box background rgba(0, 0, 0, 0.04), text color Midnight Ink (#000000), border radius 6px. Padding 10px vertical, 12px left, 24px right. Placeholder text 'info@example.com' in Muted Stone (#707070).

## Similar Brands

- **Plausible Analytics** — Shares a similar minimal, light-themed SaaS aesthetic with focus on data, simple typography, and clear calls to action.
- **Fathom Analytics** — Employs a clean, approachable design with soft colors and rounded elements, presenting complex data in an unintimidating way.
- **Simple Analytics** — Features a direct, no-frills UI, light color palette, and emphasizes readability, akin to Pirsch's functional visual style.
- **Linear** — Exhibits a subtle, refined use of neutrals and distinct singular accent colors, creating an efficient and calm user experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghostly-gray: #f8f5ed;
  --color-muted-stone: #707070;
  --color-sunbeam-yellow: #ffda6e;
  --color-leafy-green: #6ece9d;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.016px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.016px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.016px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.016px;
  --text-display: 64px;
  --leading-display: 1.25;
  --tracking-display: -0.016px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-tags: 24px;
  --radius-cards: 24px;
  --radius-input: 6px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-canvas: #FFFFFF;
  --surface-card-surface: #f8f5ed;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghostly-gray: #f8f5ed;
  --color-muted-stone: #707070;
  --color-sunbeam-yellow: #ffda6e;
  --color-leafy-green: #6ece9d;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.016px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.016px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.016px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.016px;
  --text-display: 64px;
  --leading-display: 1.25;
  --tracking-display: -0.016px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
}
```
