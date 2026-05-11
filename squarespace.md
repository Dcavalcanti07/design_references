# Squarespace — Style Reference
> Editorial White-glove Service

**Theme:** light

Squarespace embodies a refined, editorial aesthetic with a stark contrast between a dominant dark mode hero and a light canvas for content. Typography relies on a precise, custom sans-serif with subtle letter-spacing variations to convey authority. Components are understated, often ghost-like or subtly outlined, emphasizing content over heavy ornamentation. The system prioritizes functional clarity and a premium, minimalist feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page backgrounds, primary text, icon fills, card borders, dark overlay areas — used as the foundational dark neutral |
| Canvas White | `linear-gradient(90deg, rgb(255, 255, 255) 29.44%, rgb(136, 188, 216) 39.97%, rgb(243, 255, 193) 61.04%, rgb(255, 255, 255) 71.57%)` | `--color-canvas-white` | Content surfaces, button text on dark backgrounds, secondary backgrounds, separator lines; Decorative background gradient used for abstract elements or soft transitions |
| Graphite | `#2f2f2f` | `--color-graphite` | Primary action button background — a soft dark gray for filled buttons |
| Silver Mist | `#898989` | `--color-silver-mist` | Muted text, secondary body copy, subtle borders |
| Light Gray | `#dddddd` | `--color-light-gray` | Hairline borders, subtle background tints, deactivated text |

## Tokens — Typography

### Clarkson — Primary typeface for all headings, body text, and interactive elements. Its variable weights and precise letter-spacing create a sophisticated, modern feel, prioritizing clarity and presence. · `--font-clarkson`
- **Substitute:** Open Sans
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 13px, 14px, 15px, 20px, 26px, 40px, 64px, 72px
- **Line height:** 0.93, 1.00, 1.20, 1.40
- **Letter spacing:** -0.06em, -0.05em, -0.04em, -0.02em, -0.01em, -0.001em
- **Role:** Primary typeface for all headings, body text, and interactive elements. Its variable weights and precise letter-spacing create a sophisticated, modern feel, prioritizing clarity and presence.

### Clarkson Serif — Used for specific stylized headings, providing a classic, elegant contrast to the primary sans-serif. Distinctive for its unique letter-spacing at its size. · `--font-clarkson-serif`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 26px
- **Line height:** 1.00
- **Letter spacing:** -0.02em
- **Role:** Used for specific stylized headings, providing a classic, elegant contrast to the primary sans-serif. Distinctive for its unique letter-spacing at its size.

### sans-serif — Fallback for system text, used rarely, primarily for accessibility or default browser styles where custom fonts may fail to load. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Fallback for system text, used rarely, primarily for accessibility or default browser styles where custom fonts may fail to load.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-lg | 15px | 1.4 | — | `--text-body-lg` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading-sm | 26px | 1 | -0.52px | `--text-heading-sm` |
| heading | 40px | 1 | -0.4px | `--text-heading` |
| heading-lg | 64px | 0.93 | -0.64px | `--text-heading-lg` |
| display | 72px | 0.93 | -0.72px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| input | 8px |
| pills | 100px |
| buttons | 8px |
| default | 3px |
| largeButtons | 30px |

### Layout

- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Main call-to-action button for initiating key user flows.

Background: Graphite (#2f2f2f), Text: Canvas White (#ffffff), Border Radius: 8px, Padding: 24px horizontal, 24px vertical.

### Ghost Button
**Role:** Subtle, secondary action button, often used in navigation or alongside a primary button.

Background: transparent, Text: Absolute Zero (#000000), Border: 0px, Padding: 0px.

### Pill Button
**Role:** Decorative or categorized action, such as tags or filter buttons.

Background: transparent, Text: Absolute Zero (#000000), Border: 0px, Border Radius: 100px, Padding: 12px vertical, 16px horizontal.

### Dark Card
**Role:** Content container for featured sections against a light background.

Background: Absolute Zero (#000000), Border Radius: 0px, No shadow. Padding: 16px top, 48px horizontal, 40px bottom.

### Default Card
**Role:** Standard content container, visually distinct through a soft radius.

Background: transparent, Border Radius: 8px, No shadow, Padding: 0px.

### Outline Large Button
**Role:** Alternative call-to-action with a larger, more pronounced border.

Background: Canvas White (#ffffff), Text: Absolute Zero (#000000), Border: 0px, Border Radius: 0px, Padding: 24px horizontal, 24px vertical.

### White Text Input
**Role:** Input fields used primarily on dark backgrounds.

Background: rgba(255, 255, 255, 0.2), Text: Canvas White (#ffffff), Border: transparent, Border Radius: 8px, Padding: 0px.

## Do's and Don'ts

### Do
- Use Absolute Zero (#000000) as the default background for hero sections and footer areas to establish a premium, high-contrast feel.
- Apply Clarkson font consistently for all text, varying weights (300, 400, 500) and sizes according to the type scale to maintain stylistic unity.
- Utilize 8px border radius for all cards, standard buttons, and input fields to ensure a subtle, consistent softness.
- Implement a 100px border radius for pill-shaped elements like tags or category buttons.
- Maintain 12px as the standard `elementGap` for horizontal and vertical spacing between small elements.
- Reserve Graphite (#2f2f2f) for primary actions, ensuring its distinction against the black and white palette.
- Ensure headings use negative letter-spacing from Clarkson font (-0.06em to -0.001em depending on size) to create a tight, editorial look.

### Don't
- Avoid using bright or overly saturated colors, as the palette is largely monochromatic with controlled accents.
- Do not use heavy shadows or deep elevation for components; surfaces should remain flat or subtly defined with borders.
- Do not introduce new font families; the system relies on Clarkson and Clarkson Serif for all typographic needs.
- Avoid arbitrary border radii; stick to 8px, 100px, 3px, and 30px as defined by the system for specific components.
- Do not use generic padding values; adhere to the specified spacing tokens like 12px, 16px, 24px, and 40px.
- Refrain from using color to indicate states (success/error) unless explicitly defined; rely on text and icons for such feedback.
- Do not break the light content / dark hero pattern; this contrast is central to the visual identity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Absolute Zero | `#000000` | Primary background for hero sections and full-width dark blocks, providing a dramatic, elegant canvas. |
| 1 | Canvas White | `#ffffff` | Dominant background for main content areas, providing a clean, bright stage for information. |
| 2 | Light Gray | `#dddddd` | Subtle background for alternating sections or very faint dividers, offering a slight visual break. |

## Imagery

The site uses a mix of high-quality photography and stylized product illustrations. Photography is generally moody and rich, often appearing as full-bleed background imagery with a dark overlay, framing content. Product illustrations are minimal, often 3D renders or abstract shapes, rendered in a subdued, almost monochromatic palette, designed to integrate seamlessly with the UI rather than stand out. Icons are simple, monochrome outlines, used functionally for navigation and features, maintaining a lightweight feel. Imagery serves to establish atmosphere and showcase elegant product usage, rather than being purely decorative.

## Layout

The page structure heavily employs a full-bleed layout for hero sections, transitioning to a maximum-width contained layout (approximately 1200px) for most content sections. The hero typically features a dramatic background image with centered, large typography. Section rhythm alternates between full-bleed dark blocks and contained white sections, creating distinct visual breaks. Content is predominantly arranged in centered stacks or two-column layouts where text and visuals alternate. Feature sections often use a grid of cards, maintaining an overall spacious yet dense presentation. The navigation is a fixed top bar on dark backgrounds, becoming a fixed, visually neutral bar on light sections.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #dddddd
accent: no distinct accent color
primary action: #2f2f2f (filled action)

Example Component Prompts:
Create a primary action button: Background Graphite (#2f2f2f), text Canvas White (#ffffff), Clarkson 400 at 16px, border radius 8px, padding 24px horizontal, 24px vertical.
Create a card for a feature section: Background transparent, border radius 8px, padding 0px. 
Create a hero section headline: Text Absolute Zero (#000000), Clarkson 300 at 72px, line height 0.93, letter spacing -0.72px. 
Create a muted body text element: Text Silver Mist (#898989), Clarkson 400 at 14px, line height 1.4.
Create a simple navigation link: Text Absolute Zero (#000000), Clarkson 400 at 16px, padding 0px.

## Similar Brands

- **Apple** — Shares a similar focus on high-quality product photography, minimalist UI, and editorial graphic design with strong typography.
- **Stripe** — Exhibits a clean, functional aesthetic with restrained use of color, strong sans-serif typography, and clear information hierarchy.
- **Linear** — Employs a sophisticated dark mode with subtle visual cues, highly legible typography, and an emphasis on functional elegance.
- **Framer** — Uses a similar blend of dark and light sections, premium feel through typography and minimal component design, often featuring abstract graphics.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --gradient-canvas-white: linear-gradient(90deg, rgb(255, 255, 255) 29.44%, rgb(136, 188, 216) 39.97%, rgb(243, 255, 193) 61.04%, rgb(255, 255, 255) 71.57%);
  --color-graphite: #2f2f2f;
  --color-silver-mist: #898989;
  --color-light-gray: #dddddd;

  /* Typography — Font Families */
  --font-clarkson: 'Clarkson', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clarkson-serif: 'Clarkson Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-lg: 15px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.52px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.4px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.93;
  --tracking-heading-lg: -0.64px;
  --text-display: 72px;
  --leading-display: 0.93;
  --tracking-display: -0.72px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-input: 8px;
  --radius-pills: 100px;
  --radius-buttons: 8px;
  --radius-default: 3px;
  --radius-largebuttons: 30px;

  /* Surfaces */
  --surface-absolute-zero: #000000;
  --surface-canvas-white: #ffffff;
  --surface-light-gray: #dddddd;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --color-graphite: #2f2f2f;
  --color-silver-mist: #898989;
  --color-light-gray: #dddddd;

  /* Typography */
  --font-clarkson: 'Clarkson', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clarkson-serif: 'Clarkson Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-lg: 15px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.52px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.4px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.93;
  --tracking-heading-lg: -0.64px;
  --text-display: 72px;
  --leading-display: 0.93;
  --tracking-display: -0.72px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-3xl: 30px;
  --radius-full: 100px;
}
```
