# Ko-fi — Style Reference
> Warm, creative craft studio

**Theme:** light

Ko-fi embraces a cozy, approachable aesthetic with soft, rounded elements and a palette grounded in warm neutrals and a single vibrant blue for calls to action. The design emphasizes chunky typography and generous spacing to create a friendly, unhurried feel. Content is primarily organized within white, rounded cards, offset from a creamy background, using subtle borders to define structure rather than harsh lines. Playful iconography and illustrations reinforce the warm, creator-friendly atmosphere.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Oat | `#e9dfd2` | `--color-canvas-oat` | Page background, subtle button backgrounds, input borders – a warm, light neutral creating a soft, inviting base |
| Background Paper | `#ffffff` | `--color-background-paper` | Card backgrounds, elevated surfaces, button text against dark backgrounds, input fields – providing a clean, bright layer for content |
| Text Ink | `#202020` | `--color-text-ink` | Primary text, headings, button text on light backgrounds – a deep, near-black for high contrast readability |
| Border Stone | `#e5e7eb` | `--color-border-stone` | Subtle borders on cards, navigation elements, inputs – providing soft delineation without visual heaviness |
| Outline Ebony | `#000000` | `--color-outline-ebony` | Card borders, image borders, graphic accents – a crisp dark outline for definition |
| Action Sky | `#72a4f2` | `--color-action-sky` | Primary action button backgrounds – a vivid blue that stands out against the warm neutrals, signaling interactivity |
| Footer Slate | `#aac9f7` | `--color-footer-slate` | Footer background – a muted blue providing a distinct, cool background for the bottom section |
| Icon Ember | `#ff5a16` | `--color-icon-ember` | Decorative icon accents, subtle brand highlights – an energetic orange for small, functional color punctuation |

## Tokens — Typography

### DM Sans — Used for all body text, secondary headings, navigation, and button labels, maintaining a consistent, approachable sans-serif voice throughout. · `--font-dm-sans`
- **Weights:** 400, 600
- **Sizes:** 14px, 16px, 20px, 24px, 30px
- **Line height:** 1.20, 1.33, 1.40, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Used for all body text, secondary headings, navigation, and button labels, maintaining a consistent, approachable sans-serif voice throughout.

### bogue-black — The signature display typeface for main headlines and hero text. Its chunky, friendly forms convey warmth and approachability, giving a distinct brand voice. · `--font-bogue-black`
- **Substitute:** Bungee Outline (for a similar chunky, playful feel without the specific outlined characters) or maybe Public Sans Black (for a broad bold feel)
- **Weights:** 400
- **Sizes:** 60px, 72px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** The signature display typeface for main headlines and hero text. Its chunky, friendly forms convey warmth and approachability, giving a distinct brand voice.

### Font Awesome 6 Pro — Font Awesome 6 Pro — detected in extracted data but not described by AI · `--font-font-awesome-6-pro`
- **Weights:** 900
- **Sizes:** 20px
- **Line height:** 1
- **Role:** Font Awesome 6 Pro — detected in extracted data but not described by AI

### Font Awesome 6 Brands — Font Awesome 6 Brands — detected in extracted data but not described by AI · `--font-font-awesome-6-brands`
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1
- **Role:** Font Awesome 6 Brands — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 30px | 1.2 | — | `--text-heading` |
| display | 60px | 1 | — | `--text-display` |
| display-lg | 72px | 1 | — | `--text-display-lg` |

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
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 40px |
| images | 40px |
| inputs | 9999px |
| buttons | 9999px |
| components | 24px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Call to action button

Filled with Action Sky (#72a4f2), Text Ink (#202020) text, and a highly rounded border (9999px). Padding is 20px vertical, 28px horizontal, creating a substantial, inviting target.

### Secondary Neutral Button
**Role:** Secondary action or categorized filters

Background in neutral Canvas Oat (#e9dfd2), Text Ink (#202020) text, with an extremely rounded border (9999px). Padding is 10px vertical, 20px horizontal for a lighter touch than primary actions.

### Dark Icon Button
**Role:** Navigation or less prominent actions

Text Ink (#202020) background, Background Paper (#ffffff) text, and highly rounded border (9999px). Generous 20px vertical, 28px horizontal padding. Accommodates icons gracefully.

### Hero Content Card
**Role:** Prominent information display

Background Paper (#ffffff) background, with a soft 40px border-radius, and generous inner padding of 96px vertical and 80px horizontal. Presents key information in a framed, substantial way.

### Feature Image Card
**Role:** Visual grid elements

Canvas Oat (#e9dfd2) background with 40px border-radius. No padding, designed to contain visual content directly, allowing images to extend to the edges.

### Input Field
**Role:** User input

Background Paper (#ffffff) background, Text Ink (#202020) text, with a Border Stone (#e5e7eb) border. No explicit padding or border-radius indicated by data, suggesting it adapts to context or inherits.

### Navigation Link
**Role:** Top navigation menu item

Text Ink (#202020) text color. Rendered as a simple text link without explicit background or border, relying on surrounding spacing for definition.

## Do's and Don'ts

### Do
- Prioritize Canvas Oat (#e9dfd2) for all main page backgrounds, establishing the site's warm, inviting tone.
- Use Bogue Black for all primary headlines (60px-72px), preserving its distinct, friendly character.
- Apply a 9999px border-radius to all interactive elements like buttons and tags for a consistently soft, approachable shape.
- Utilize Action Sky (#72a4f2) exclusively for prominent calls to action, ensuring it draws attention effectively.
- Frame primary content within Background Paper (#ffffff) cards that feature a 40px border-radius, clearly segmenting information.
- Maintain an element gap of 20px for internal card elements and component spacing, contributing to the comfortable density.
- Use Outline Ebony (#000000) for distinct, thin borders around visual elements like image cards to add definition.

### Don't
- Avoid using sharp-edged elements; all significant corners should have a radius of at least 24px and often 40px or 9999px.
- Do not introduce new primary accent colors; Action Sky (#72a4f2) and Icon Ember (#ff5a16) are the only acceptable chromatic accents.
- Refrain from heavy shadows or pronounced elevation, maintaining the light and airy feel of the surfaces.
- Do not use DM Sans for main page headlines; save it for body text and supportive roles.
- Avoid overly dense layouts; ensure generous vertical spacing between sections (40px) and within cards (96px).
- Do not deviate from the specified padding values for buttons; the 20px vertical/28px horizontal for primary, and 10px vertical/20px horizontal for secondary, are critical for their visual weight.
- Do not use dark backgrounds for main content sections; reserve light neutrals like Background Paper (#ffffff) and Canvas Oat (#e9dfd2) for this purpose.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Oat | `#e9dfd2` | Base page background |
| 1 | Background Paper | `#ffffff` | Primary content cards and elevated UI elements |

## Imagery

The site uses playful, outlined illustrations with rounded, character-like forms, often featuring hearts or digital accoutrements, rendered in black outline with occasional subtle, flat fill colors. Photography is used for creator showcases, typically with a contained, rounded (40px radius) treatment, presenting portraits of real people. Icons are predominantly Font Awesome 6 Pro/Brands, appearing as outlined or solid, mono-colored in Text Ink, used for categorizing content or providing small visual cues. Imagery serves both decorative atmosphere and explanatory content, adding a human and friendly touch without overwhelming the UI.

## Layout

The page uses a maximum content width that appears contained and centered, creating ample negative space on wider screens against the Canvas Oat background. The hero section features a large, centered headline and subtext, followed by a primary call to action, supported by a distinct illustration below. Sections alternate between full-width content blocks and prominent, rounded cards that create visual separation. Content frequently employs a single-column or two-column layout within these cards, often with text on one side and an image or illustration on the other, creating a clear reading rhythm. Navigation is a simple top bar with left-aligned branding and right-aligned links and a 'Sign up free' button.

## Agent Prompt Guide

Quick Color Reference: 
text: #202020
background: #e9dfd2
border: #e5e7eb
accent: #72a4f2
primary action: #72a4f2 (filled action)

Example Component Prompts:
Create a primary action button: Action Sky background (#72a4f2), Text Ink text (#202020), 9999px border-radius, 20px vertical padding, 28px horizontal padding.
Create a Primary Action Button: #72a4f2 background, #202020 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a hero content card: Background Paper background (#ffffff), 40px border-radius, 96px vertical padding, 80px horizontal padding. Include an H2 in DM Sans 30px, #202020, and body text in DM Sans 16px, #202020.
Create a secondary neutral button for filtering: Canvas Oat background (#e9dfd2), Text Ink text (#202020), 9999px border-radius, 10px vertical padding, 20px horizontal padding.

## Similar Brands

- **Gumroad** — Shares a creator-focused platform identity with simplified UI and clear calls to action, aiming for discoverability and direct support.
- **Figma community** — Similar emphasis on a warm, friendly design system for a creative community, utilizing rounded corners and clear typography.
- **Mailchimp** — Leverages bold, friendly typography, a light background, and one-two primary accent colors for a brand that feels approachable and supportive.
- **Patreon** — Focuses on creator support with a clean, easy-to-navigate interface, often using soft neutrals and distinct branding elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-oat: #e9dfd2;
  --color-background-paper: #ffffff;
  --color-text-ink: #202020;
  --color-border-stone: #e5e7eb;
  --color-outline-ebony: #000000;
  --color-action-sky: #72a4f2;
  --color-footer-slate: #aac9f7;
  --color-icon-ember: #ff5a16;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bogue-black: 'bogue-black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-pro: 'Font Awesome 6 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-brands: 'Font Awesome 6 Brands', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1;
  --text-display-lg: 72px;
  --leading-display-lg: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

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
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 40px;
  --radius-images: 40px;
  --radius-inputs: 9999px;
  --radius-buttons: 9999px;
  --radius-components: 24px;

  /* Surfaces */
  --surface-canvas-oat: #e9dfd2;
  --surface-background-paper: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-oat: #e9dfd2;
  --color-background-paper: #ffffff;
  --color-text-ink: #202020;
  --color-border-stone: #e5e7eb;
  --color-outline-ebony: #000000;
  --color-action-sky: #72a4f2;
  --color-footer-slate: #aac9f7;
  --color-icon-ember: #ff5a16;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bogue-black: 'bogue-black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-pro: 'Font Awesome 6 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-brands: 'Font Awesome 6 Brands', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1;
  --text-display-lg: 72px;
  --leading-display-lg: 1;

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
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;
}
```
