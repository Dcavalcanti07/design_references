# WhatsApp.com — Style Reference
> Warm, secure communication.

**Theme:** light

WhatsApp's visual system evokes a friendly, secure communication platform. It builds upon a soft, warm neutral base with a consistent, vibrant green acting as the core accent for primary calls to action. Rounded forms are prevalent, especially in buttons and imagery, contributing to a welcoming, approachable feel. Typography is direct and legible, maintaining clarity within a spacious layout. The overall impression is one of calm competence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Green | `#25d366` | `--color-forest-green` | Primary action buttons, active indicators, brand accent — a vivid green that signifies connection and positive interaction |
| Link Blue | `#0373e9` | `--color-link-blue` | Informational links and secondary interactive borders |
| Midnight Graphite | `#1c1e21` | `--color-midnight-graphite` | Primary text, prominent headings, borders, and some backgrounds for high contrast elements |
| Dark Forest | `#111b21` | `--color-dark-forest` | Footer background, input fields, and other deeper contrast elements |
| Warm Canvas | `#fcf5eb` | `--color-warm-canvas` | Page background, hero section background — a soft, off-white that creates a gentle foundational surface |
| Pure White | `#ffffff` | `--color-pure-white` | Navigation backgrounds, card surfaces, button backgrounds (secondary), and primary text against darker backgrounds |
| Stone Gray | `#5e5e5e` | `--color-stone-gray` | Secondary text, muted helper text, and subtle borders |
| Light Fog | `#f0f4f9` | `--color-light-fog` | Subtle text and borders for less prominent information |

## Tokens — Typography

### WhatsApp Sans Var — The core typeface for all content, from headings to body text. Its variable nature allows for distinct visual hierarchy without changing families, maintaining a consistent brand voice. Weights 400 and 700 are utilized to establish clear importance, providing a direct and friendly tone. · `--font-whatsapp-sans-var`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 12px, 16px, 18px, 48px, 60px, 80px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.33, 1.34, 1.38, 1.39
- **Letter spacing:** normal
- **Role:** The core typeface for all content, from headings to body text. Its variable nature allows for distinct visual hierarchy without changing families, maintaining a consistent brand voice. Weights 400 and 700 are utilized to establish clear importance, providing a direct and friendly tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.34 | — | `--text-caption` |
| body-sm | 16px | 1.39 | — | `--text-body-sm` |
| body | 18px | 1.33 | — | `--text-body` |
| heading-sm | 48px | 1.2 | — | `--text-heading-sm` |
| heading | 60px | 1.1 | — | `--text-heading` |
| display | 80px | 1 | — | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| input | 50px |
| images | 25px |
| buttons | 50px |
| heroContainer | 25px |
| messageBubbles | 25px |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action

Background: Forest Green (#25d366), Text: Midnight Graphite (#1c1e21), Radius: 50px, Padding: 16px vertical, 28px horizontal. Bold and inviting.

### Secondary Ghost Button
**Role:** Outlined button for less prominent actions, often paired with primary

Background: transparent, Text: Midnight Graphite (#1c1e21), Border: 1px solid Midnight Graphite (#1c1e21), Radius: 50px, Padding: 16px vertical, 28px horizontal. Provides an alternative without overshadowing.

### White Background Button
**Role:** Alternative interaction button against darker backgrounds

Background: Pure White (#ffffff), Text: Midnight Graphite (#1c1e21), Border: 1px solid Midnight Graphite (#1c1e21), Radius: 50px, Padding: 16px vertical, 28px horizontal. Offers visibility on contrasting surfaces.

### Navigation Link
**Role:** Text link within the main navigation bar

Text: Midnight Graphite (#1c1e21), default styling. Emphasizes content over decorative elements.

### Card Surface
**Role:** Content containers

Background: transparent, Border-radius: 0px, Padding: 32px. Allows content to breathe against the page background without explicit division.

### Rounded Image Container
**Role:** Visual media display

Border-radius: 25px. Softens the display of images and visual content, matching the overall approachable aesthetic.

### Input Field
**Role:** Form entry

Background: Dark Forest (#111b21), Text: Pure White (#ffffff), Border: 1px solid Pure White (#ffffff), Radius: 50px, Padding: 16px vertical, 28px horizontal. Distinctive for user input within dark sections.

## Do's and Don'ts

### Do
- Use Forest Green (#25d366) exclusively for primary action button backgrounds and critical active states. Do not use it for text or borders (unless outlined button).
- Apply a 50px border-radius to all buttons and input fields to maintain the soft, rounded aesthetic.
- Utilize Warm Canvas (#fcf5eb) as the default page background for sections, creating a consistent light foundation.
- Pair Midnight Graphite (#1c1e21) for primary text and headings against lighter backgrounds like Warm Canvas (#fcf5eb) or Pure White (#ffffff).
- Maintain generous padding of 16px vertically and 28px/32px horizontally for buttons to ensure clear touch targets and visual comfort.
- Structure primary content areas with a default vertical spacing of 64px between sections.
- Use WhatsApp Sans Var for all text hierarchy, with weights 400 for body and 700 for high-impact headlines and calls to action.

### Don't
- Avoid using bright, saturated colors for decorative elements; stick to the defined accent and brand colors for functional highlights only.
- Do not introduce sharp, angular corners; all interactive elements and image containers should adhere to 25px or 50px radii.
- Do not add drop shadows to cards or primary elements; the design relies on flat surfaces and clear visual separation through background colors and spacing.
- Refrain from using thin, light fonts larger than body text; important headings should be WhatsApp Sans Var weight 700.
- Do not use multiple font families; WhatsApp Sans Var is the single typeface for all UI elements.
- Avoid tight element spacing; ensure a minimum of 16px gap between interactive elements and content blocks.
- Do not use dark backgrounds indiscriminately; reserve Dark Forest (#111b21) for specific footer or input contexts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Warm Canvas | `#fcf5eb` | Primary page background, soft and inviting. |
| 1 | Pure White | `#ffffff` | Raised card surfaces, navigation background, offering a clean, distinct content area. |
| 2 | Dark Forest | `#111b21` | Elevated section background (e.g., footer), interactive input fields, creating deep contrast for specific elements. |

## Imagery

The imagery predominantly features candid, natural-looking photography of diverse individuals using mobile devices, often smiling or engaged with their screens. These photos are contained within softly rounded shapes (25px radius) rather than hard-edged rectangles. Some sections also utilize stylized product screens with subtle chat bubbles appearing in a generative, playful manner, hinting at app functionality without being overly prescriptive. Icons are minimalist, outlined, and primarily monochromatic, using the Forest Green accent for interactive states or brand markers. Imagery serves to convey genuine human connection and product-in-use scenarios, creating an empathetic and aspirational tone.

## Layout

The page primarily uses a contained layout, centering content within a flexible max-width, though the hero section often employs a full-bleed visual element with contained text. The hero pattern is typically a split text-left, image-right composition, featuring a large headline paired with primary and secondary call-to-action buttons. Sections alternate between visual-heavy presentations (like the hero and 'Say what you feel' image) and text-dominant content blocks. Vertical rhythm is established through consistent section gaps (around 64px). The layout largely avoids complex grids, preferring clear, stacked content blocks or simple two-column arrangements for feature explanations. Navigation is a sticky top bar with a logo and clear calls to action, maintaining brand presence and accessibility.

## Agent Prompt Guide

Quick Color Reference: 
- text: #1c1e21
- background: #fcf5eb
- border: #1c1e21
- accent: #25d366
- primary action: #25d366 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #25d366 background, #111b21 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a feature card: Pure White (#ffffff) background, 32px padding on all sides, no border-radius. Include heading 'Voice and video calls' (WhatsApp Sans Var, 48px, weight 700, #1c1e21, lineHeight 1.2) and body text 'Keep conversations going with free, reliable calling on any device' (WhatsApp Sans Var, 18px, weight 400, #1c1e21, lineHeight 1.33).
- Generate a footer with a Dark Forest (#111b21) background. Include a copyright notice at 16px 400 weight Pure White (#ffffff) text, and navigation links (WhatsApp Sans Var, 16px, weight 400, Pure White #ffffff text) separated by 16px elementGap for vertical spacing. All text links should have a Pure White (#ffffff) color.

## Similar Brands

- **Telegram** — Clean, communication-focused UI with a distinct accent color for interactive elements and a generally simple, spacious layout.
- **Signal** — Emphasis on privacy and security, translated visually through a restrained palette, clear typography, and minimal decorative elements.
- **Slack** — Productivity-tool aesthetic with a cheerful primary accent color, subtle use of rounded corners, and clear hierarchical typography.
- **Headspace** — Uses a warm, inviting color palette and soft, rounded shapes to create a friendly and approachable user experience, similar to WhatsApp's inviting aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-green: #25d366;
  --color-link-blue: #0373e9;
  --color-midnight-graphite: #1c1e21;
  --color-dark-forest: #111b21;
  --color-warm-canvas: #fcf5eb;
  --color-pure-white: #ffffff;
  --color-stone-gray: #5e5e5e;
  --color-light-fog: #f0f4f9;

  /* Typography — Font Families */
  --font-whatsapp-sans-var: 'WhatsApp Sans Var', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.34;
  --text-body-sm: 16px;
  --leading-body-sm: 1.39;
  --text-body: 18px;
  --leading-body: 1.33;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.2;
  --text-heading: 60px;
  --leading-heading: 1.1;
  --text-display: 80px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

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
  --spacing-56: 56px;
  --spacing-88: 88px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 25px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-input: 50px;
  --radius-images: 25px;
  --radius-buttons: 50px;
  --radius-herocontainer: 25px;
  --radius-messagebubbles: 25px;

  /* Surfaces */
  --surface-warm-canvas: #fcf5eb;
  --surface-pure-white: #ffffff;
  --surface-dark-forest: #111b21;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-green: #25d366;
  --color-link-blue: #0373e9;
  --color-midnight-graphite: #1c1e21;
  --color-dark-forest: #111b21;
  --color-warm-canvas: #fcf5eb;
  --color-pure-white: #ffffff;
  --color-stone-gray: #5e5e5e;
  --color-light-fog: #f0f4f9;

  /* Typography */
  --font-whatsapp-sans-var: 'WhatsApp Sans Var', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.34;
  --text-body-sm: 16px;
  --leading-body-sm: 1.39;
  --text-body: 18px;
  --leading-body: 1.33;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.2;
  --text-heading: 60px;
  --leading-heading: 1.1;
  --text-display: 80px;
  --leading-display: 1;

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
  --spacing-56: 56px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-3xl: 25px;
  --radius-full: 50px;
}
```
