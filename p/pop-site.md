# Pop Site — Style Reference
> Crisp canvas, bold headlines, electric blue

**Theme:** light

Pop Site uses a crisp, high-contrast light-mode system, emphasizing strong typographic hierarchy and a singular vibrant blue accent. Wide spacing and soft-cornered cards establish an approachable feel, while the dominant dark text against pure white canvases ensures immediate clarity. The design prioritizes visual directness and ease of use through consistent control styling rather than heavy visual flair.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary surface elevation |
| Coal Black | `#000000` | `--color-coal-black` | Primary body text, bold headings, icon fills, strong borders |
| Ink Black | `linear-gradient(0deg, rgb(23, 23, 23) 0%, rgb(0, 0, 0) 100%)` | `--color-ink-black` | Secondary headings, prominent link text, strong borders; Decorative background gradient, typically for visual sections (linear) |
| Slate Gray | `#5e5e5e` | `--color-slate-gray` | Muted body text, helper text, secondary borders |
| Ash Gray | `#6e6e73` | `--color-ash-gray` | Subtle body text, footer text, hairline borders |
| Fog Gray | `#d2d2d7` | `--color-fog-gray` | Subtle background tones, dividers |
| Action Blue | `#3b82f6` | `--color-action-blue` | Primary call-to-action buttons, active states, brand links, interactive borders |
| Outline Blue | `#6ea5ff` | `--color-outline-blue` | Outlined link borders, secondary interactive accents |
| Eclipse Gradient | `radial-gradient(100% 62% at 4.1% 0px, rgb(54, 56, 54) 0%, rgb(0, 0, 0) 100%)` | `--color-eclipse-gradient` | Decorative background gradient with slight radial glow |
| Ember Gradient | `radial-gradient(50% 65% at 50% 0px, rgb(199, 43, 0) 0%, rgb(0, 0, 0) 100%)` | `--color-ember-gradient` | Decorative background gradient with warm radial glow |
| Sky Wash Gradient | `radial-gradient(50% 50% at 75.6% 50%, rgb(224, 233, 255) 0%, rgb(255, 255, 255) 100%)` | `--color-sky-wash-gradient` | Soft background wash, typically within sections or as subtle visual interest |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Satoshi — Primary brand typeface for headings and prominent text. Its compact, almost compressed letterforms and aggressive negative tracking create a modern, direct tone. · `--font-satoshi`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 13px, 15px, 21px, 53px, 93px, 120px
- **Line height:** 0.90, 1.00, 1.20, 1.30, 1.40
- **Letter spacing:** -0.0590em at 120px, -0.0500em at 93px, -0.0460em at 53px, -0.0300em at 21px
- **Role:** Primary brand typeface for headings and prominent text. Its compact, almost compressed letterforms and aggressive negative tracking create a modern, direct tone.

### Inter — Functional typeface for input fields, ensuring legibility at smaller sizes and within interactive elements. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Functional typeface for input fields, ensuring legibility at smaller sizes and within interactive elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.03px | `--text-caption` |
| body | 15px | 1.2 | — | `--text-body` |
| subheading | 21px | 1.3 | -0.03px | `--text-subheading` |
| heading | 53px | 1 | -0.046px | `--text-heading` |
| heading-lg | 93px | 0.9 | -0.05px | `--text-heading-lg` |
| display | 120px | 0.9 | -0.059px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 10px |
| image | 8px |
| buttons | 26px |
| default | 8px |

### Layout

- **Section gap:** 60px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Action Button
**Role:** Filled call to action button

Background: Action Blue (#3b82f6), Text: Coal Black (#000000) (overridden by browser default link color in data, but visually white), Padding: 16px vertical, 24px horizontal. Corner radius: 26px for a soft pill shape.

### Ghost Input Segment Button
**Role:** Segmented control component part or input accessory

Ghost-style button. Background: Canvas White (#fafafc or transparent), Text: Coal Black (#000000), Border: 1px Coal Black (#000000). Specific radius for segmented left component: 0px top-left, 9999px top-right, 9999px bottom-right, 0px bottom-left. Padding is 16px vertical, 12px left, 20px right.

### Ghost Link Button
**Role:** Outlined or text-only button for secondary actions or navigation

Transparent background, Coal Black (#000000) text and border. No explicit padding in data, often used for text links or minimal interactive elements. Radius 0px.

### Content Card
**Role:** Container for features, testimonials, or content blocks

Background: Canvas White (#ffffff), Border radius: 10px. No box-shadow for a flat aesthetic. Padding: 20px on all sides.

### Full-Bleed Media Card
**Role:** Card container for imagery or full-bleed elements

Transparent background with a border radius of 20px. Serves to crop or frame content without adding an extra visual layer.

### Text Input (Base)
**Role:** Styling for text input fields

Transparent background, text color Coal Black (#000000), border color Coal Black (#000000). Radius 0px. No explicit padding mentioned in data, implies system default or inherited.

## Do's and Don'ts

### Do
- Prioritize Satoshi for all headlines and prominent text, using its specific letter-spacing values to create a tight, impactful visual.
- Use Coal Black (#000000) for primary body text and most UI elements against Canvas White (#ffffff) backgrounds for maximum contrast.
- Reserve Action Blue (#3b82f6) exclusively for primary call-to-actions, active states, and brand-aligned interactive elements to maintain its impact.
- Apply a 10px border-radius for content cards and a 26px radius for primary buttons to maintain the brand's soft, approachable form language.
- Maintain generous 60px vertical section gaps to ensure a clear visual separation between content blocks.
- Keep card surfaces flat without shadows, relying on Canvas White (#ffffff) as the background and Coal Black (#000000) for text and borders to define content areas.
- Utilize transparent backgrounds for ghost buttons and input elements, defining them with high-contrast text and border colors like Coal Black (#000000).

### Don't
- Do not introduce additional vibrant colors; the system relies on a single dominant Action Blue (#3b82f6) for brand accents.
- Avoid heavy drop shadows or complex elevation states; the design prefers a clean, flat aesthetic for cards and surfaces.
- Do not use generic sans-serif fonts for headlines; Satoshi's distinctive letter-spacing is key to the brand's typographic identity.
- Do not vary border radii significantly for interactive elements, stick to 26px for primary buttons and 9999px for pill-shaped segments.
- Do not use subtle gray text (#5e5e5 or #6e6e73) for important calls to action; always use contrast-rich Coal Black (#000000) or Canvas White (#ffffff) against colored backgrounds.
- Do not create complex multi-color gradients for functional UI elements; the existing gradients are for decorative backgrounds only.
- Do not deviate from the established spacing units (based on 4px increments); maintain a comfortable, consistent density throughout the pages.

## Imagery

The visual language for imagery is primarily product-focused, featuring tightly cropped device mockups (iPhones) displaying the Pop Site interface. These are typically rendered with soft, subtle depth and often feature contextual elements like hands or desks to indicate use. Photography, where present, appears to be clean and minimal, focused on individuals or teams. Iconography is minimalist, outlined, and monochromatic, often using Coal Black (#000000) against white backgrounds. The overall density is balanced, allowing UI elements and typography to dominate, with imagery serving to illustrate product functionality rather than create atmospheric mood.

## Layout

The site employs a primarily max-width contained layout, likely around 1200px, with content centered. The hero section features a large, centered headline over a white background, flanked by call-to-action buttons. Sections below often alternate between full-width product imagery (specifically iPhone mockups) and content blocks with strong headings and body text. There is a consistent vertical rhythm with generous section gaps, suggesting distinct content areas. Feature sections frequently use a grid of cards (often 3-column), each with a specific image or illustration and descriptive text. Navigation is a simple top bar with text links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #171717
primary action: #3b82f6 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #3b82f6 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a content card: background #ffffff, border-radius 10px, padding 20px on all sides. Headline: Satoshi weight 700, size 21px, color #171717. Body text: #000000, Satoshi weight 400, size 15px.
3. Implement a segmented input field: left segment is ghost button style with background transparent, text #000000, border #000000, border-radius 0px 9999px 9999px 0px, padding 16px vertical, 12px left, 20px right. Text: 'yourname'.
4. Create a hero headline: text 'Make a stunning site, easily', font Satoshi weight 700, size 93px, color #000000, line-height 0.9, letter-spacing -0.05em.

## Similar Brands

- **Stripe** — Similar high-contrast monochrome UI with a single vibrant accent color for interaction and distinct, compact typography for headlines.
- **Linear** — Shares a clean, modern aesthetic with strong typography, ample whitespace, and a focus on functional, subtle UI elements.
- **Figma** — Employs a light theme with clear information hierarchy, subtle surface changes, and prominent, legible text, often leveraging custom fonts.
- **Canva** — Has an approachable and clean design with a focus on strong visual hierarchy and a well-defined accent color to guide user actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-coal-black: #000000;
  --color-ink-black: #171717;
  --gradient-ink-black: linear-gradient(0deg, rgb(23, 23, 23) 0%, rgb(0, 0, 0) 100%);
  --color-slate-gray: #5e5e5e;
  --color-ash-gray: #6e6e73;
  --color-fog-gray: #d2d2d7;
  --color-action-blue: #3b82f6;
  --color-outline-blue: #6ea5ff;
  --color-eclipse-gradient: #363836;
  --gradient-eclipse-gradient: radial-gradient(100% 62% at 4.1% 0px, rgb(54, 56, 54) 0%, rgb(0, 0, 0) 100%);
  --color-ember-gradient: #c72b00;
  --gradient-ember-gradient: radial-gradient(50% 65% at 50% 0px, rgb(199, 43, 0) 0%, rgb(0, 0, 0) 100%);
  --color-sky-wash-gradient: #e0e9ff;
  --gradient-sky-wash-gradient: radial-gradient(50% 50% at 75.6% 50%, rgb(224, 233, 255) 0%, rgb(255, 255, 255) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.03px;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 21px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.03px;
  --text-heading: 53px;
  --leading-heading: 1;
  --tracking-heading: -0.046px;
  --text-heading-lg: 93px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.05px;
  --text-display: 120px;
  --leading-display: 0.9;
  --tracking-display: -0.059px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 22px;
  --radius-3xl: 26px;
  --radius-3xl-2: 42px;
  --radius-full: 999px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 10px;
  --radius-image: 8px;
  --radius-buttons: 26px;
  --radius-default: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-coal-black: #000000;
  --color-ink-black: #171717;
  --color-slate-gray: #5e5e5e;
  --color-ash-gray: #6e6e73;
  --color-fog-gray: #d2d2d7;
  --color-action-blue: #3b82f6;
  --color-outline-blue: #6ea5ff;
  --color-eclipse-gradient: #363836;
  --color-ember-gradient: #c72b00;
  --color-sky-wash-gradient: #e0e9ff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.03px;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 21px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.03px;
  --text-heading: 53px;
  --leading-heading: 1;
  --tracking-heading: -0.046px;
  --text-heading-lg: 93px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.05px;
  --text-display: 120px;
  --leading-display: 0.9;
  --tracking-display: -0.059px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 22px;
  --radius-3xl: 26px;
  --radius-3xl-2: 42px;
  --radius-full: 999px;
  --radius-full-2: 9999px;
}
```
