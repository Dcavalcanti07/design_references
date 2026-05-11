# Fable — Style Reference
> whimsical storybook canvas

**Theme:** light

Fable embraces a playful, illustrative aesthetic with strong, inviting typography and a limited but impactful color palette. Bold, contrasting backgrounds in rich greens and blues create distinct sections, often paired with white or near-black text for high readability. Imagery is organic and character-driven, feeling integrated rather than overlaid. Components feature generous padding and distinct, rounded shapes, projecting a friendly and approachable digital experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canopy | `#064c37` | `--color-forest-canopy` | Hero section backgrounds, prominent page sections — grounding but vibrant, setting a rich, inviting tone |
| Ocean Deep | `#43a1d7` | `--color-ocean-deep` | Illustrative accents, secondary section backgrounds — a bright, moderating contrast to the darker greens |
| Midnight Ink | `#161015` | `--color-midnight-ink` | Primary text, darker card backgrounds, bold headings — provides strong contrast against lighter surfaces |
| Deep Space | `#070607` | `--color-deep-space` | Footer background, secondary text, accents against light backgrounds — nearly black, used for maximum contrast |
| Slate Shadow | `#292229` | `--color-slate-shadow` | Button backgrounds, dark text on lighter surfaces — a slightly softer dark than pure black |
| Pearl White | `#ffffff` | `--color-pearl-white` | Primary background for cards and lighter sections, button text, body text on dark backgrounds — a stark contrast element |
| Parchment | `#f7f4ee` | `--color-parchment` | Card backgrounds, secondary container surfaces — a subtle, warm off-white that adds depth without being stark |
| Ghost Gray | `#ededed` | `--color-ghost-gray` | Subtle image backgrounds, borders for contained elements — a very light, almost invisible gray |
| Ink Wash | `#3f383d` | `--color-ink-wash` | Muted body text, secondary icon colors — a dark gray for softer text details |

## Tokens — Typography

### Inter — Primary body text, labels, small print, and various interface elements. The tight tracking at larger sizes gives it a modern, compact feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 8px, 10px, 12px, 14px, 15px, 16px, 18px, 20px, 24px, 30px
- **Line height:** 1.00, 1.13, 1.17, 1.25, 1.33, 1.42, 1.43, 1.50, 1.60
- **Letter spacing:** -0.0420em at 30px, -0.0330em at 24px, -0.0200em at 20px, -0.0180em at 18px, -0.0170em at 16px, -0.0150em at 15px, -0.0140em at 14px, -0.0120em at 12px, -0.0110em at 10px, normal at 8px
- **Role:** Primary body text, labels, small print, and various interface elements. The tight tracking at larger sizes gives it a modern, compact feel.

### Heldane Display — Striking, large-scale headlines. The generous x-height and tight line-height create presence, conveying a sense of classic literature with a modern twist, especially effective at very large sizes like 72px and 80px for hero sections. · `--font-heldane-display`
- **Substitute:** serif
- **Weights:** 400, 500
- **Sizes:** 22px, 26px, 48px, 72px, 80px
- **Line height:** 0.86, 0.88, 0.94, 1.08, 1.09
- **Letter spacing:** normal
- **Role:** Striking, large-scale headlines. The generous x-height and tight line-height create presence, conveying a sense of classic literature with a modern twist, especially effective at very large sizes like 72px and 80px for hero sections.

### Aktiv Grotesk — Used sparingly for specific informational text, like small captions or sub-labels, complementing Inter without overtly competing. · `--font-aktiv-grotesk`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for specific informational text, like small captions or sub-labels, complementing Inter without overtly competing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | -0.11px | `--text-caption` |
| body | 14px | 1.43 | -0.14px | `--text-body` |
| body-lg | 18px | 1.25 | -0.18px | `--text-body-lg` |
| subheading | 22px | 1.09 | — | `--text-subheading` |
| heading | 26px | 1.08 | — | `--text-heading` |
| heading-lg | 48px | 0.94 | — | `--text-heading-lg` |
| display | 72px | 0.88 | — | `--text-display` |
| display-lg | 80px | 0.86 | — | `--text-display-lg` |

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
| 52 | 52px | `--spacing-52` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 60px |
| largeCards | 48px |
| mediumCards | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.4) 0px 4px 20px 0px` | `--shadow-lg` |
| lg-2 | `rgba(0, 0, 0, 0.6) 0px 4px 20px 0px` | `--shadow-lg-2` |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Call to action button

Solid background button for 'Get the app'. Background: Slate Shadow (#292229). Text: Pearl White (#ffffff). Radius: 60px (pill shape). Minimal padding is observed but contextually implies text is internally padded by font-size and line-height.

### Navigation Link
**Role:** Header and footer navigation

Text link on transparent background. Text: Deep Space (#070607) on light backgrounds, Pearl White (#ffffff) on dark backgrounds. No explicit border or radius. Used for 'Join a club', 'Bookstore', 'Blog'.

### Light Theme Filled Button
**Role:** Secondary call to action, interactive elements on dark backgrounds

Solid background button. Background: Pearl White (#ffffff). Text: Midnight Ink (#161015). Radius: 60px (pill shape).

### Card with Shadow
**Role:** Featured content card, elevated interactive elements

Solid background card. Background: Midnight Ink (#161015). Radius: 12px. Shadow: rgba(0, 0, 0, 0.6) 0px 4px 20px 0px. No explicit padding.

### Product Display Card
**Role:** Book cover display, content grid item

Transparent background card, typically used to display images. No explicit radius, shadow, or padding. Content is directly an image or specific product item. (e.g. book covers).

### Parchment Content Card
**Role:** Informational cards, content blocks

Solid background card. Background: Parchment (#f7f4ee). Radius: 48px or 24px (depends on context). Padding: 40px top, 24px right, 34px bottom, 24px left for large cards; 12px all around for smaller cards.

## Do's and Don'ts

### Do
- Use Forest Canopy (#064c37) or Ocean Deep (#43a1d7) for full-width section backgrounds to establish clear visual breaks.
- Apply Heldane Display for all headings, using sizes 48px, 72px, or 80px with weight 500 for maximum impact.
- Default to Inter weight 400 for body text with line-height of 1.42 or 1.43, and letter-spacing adjusted per size for comfortable reading.
- Employ a 60px border-radius for all primary and secondary buttons to maintain a pill-like, friendly aesthetic.
- Pad card elements generously with 40px top, 24px right, 34px bottom, 24px left for primary content cards, and 12px for smaller, tighter content.
- Use Slate Shadow (#292229) for primary button backgrounds with Pearl White (#ffffff) text.
- Incorporate subtle shadows rgba(0, 0, 0, 0.6) 0px 4px 20px 0px for elevated cards, ensuring visual hierarchy without heavy bordering.

### Don't
- Avoid using multiple chromatic colors in close proximity; the palette is designed for distinct section separation.
- Do not use generic sans-serif fonts for headlines; Heldane Display is essential for brand personality.
- Refrain from using hard-edged rectangles for interactive elements; all buttons and many cards require significant border-radius.
- Do not clutter pages with excessive imagery; allow illustrations to breathe and serve as focal points.
- Avoid thin borders for cards and buttons; rely on solid background colors or shadows for definition.
- Do not use letter-spacing: normal for text larger than 16px; Inter requires specific negative tracking for optimal appearance at varied sizes.
- Do not use pure black body text on white backgrounds, opt for Midnight Ink (#161015) or Deep Space (#070607) for softer contrast.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Ocean Deep Canvas | `#43a1d7` | Base background for prominent sections, providing a strong visual anchor. |
| 1 | Parchment Surface | `#f7f4ee` | Primary card and content block background, offering a warm, light surface. |
| 2 | Pearl White Element | `#ffffff` | Background for interactive elements, buttons, and focused content, providing highest contrast. |
| 3 | Midnight Ink Elevated | `#161015` | Background for deeply embedded cards or sections, using a dark tone to create visual depth, often with a shadow. |

## Elevation

- **Card with Shadow:** `rgba(0, 0, 0, 0.6) 0px 4px 20px 0px`
- **Button Shadow:** `rgba(0, 0, 0, 0.4) 0px 4px 20px 0px`

## Imagery

The visual language is characterized by custom, expressive illustrations featuring human-like characters engaging with books or digital devices. These illustrations are typically full-color, organic, and often occupy significant visual space as hero elements or section dividers. They are not contained within strict bounding boxes but rather interact with the text and layout. Photography, when present, tends to be product-focused (e.g., book covers) or subtle lifestyle imagery. Icons are generally filled and have a moderate stroke weight, matching the friendly, approachable aesthetic. Imagery serves both decorative atmosphere and explanatory content, emphasizing community and product interaction, and contributes to a visual density that feels rich but not overwhelming.

## Layout

The page model alternates between full-bleed background sections (especially the hero) and maximum-width contained content blocks, creating a dynamic progression. The hero typically features a centered headline over a brand-colored background, accompanied by a large illustrative element. Section rhythm is established by alternating large blocks of Forest Canopy green and Ocean Deep blue with white or parchment-colored sections. Content is often arranged in a split text-left/image-right pattern or centered stacks. Book displays utilize a dense grid of product cards. The layout feels spacious with comfortable breathing room between sections, and the navigation is a minimal sticky header at the top.

## Agent Prompt Guide

Quick Color Reference:
text: #161015
background: #43a1d7
border: no distinct border color
accent: #43a1d7
primary action: #292229 (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background Slate Shadow (#292229), text Pearl White (#ffffff), 60px border-radius, font Inter weight 500, size 16px, line-height 1.43.
2. Create a Hero Headline: Text 'The modern app for every reader' in Heldane Display weight 500, size 72px, line-height 0.88, color Pearl White (#ffffff).
3. Create a Parchment Content Card (large): background Parchment (#f7f4ee), 48px border-radius, padding 40px top, 24px right, 34px bottom, 24px left.
4. Create a Navigation Link: Text 'Join a club' in Inter weight 400, size 18px, color Deep Space (#070607) on light backgrounds, or Pearl White (#ffffff) on dark backgrounds.
5. Create a Shadowed Card: background Midnight Ink (#161015), 12px border-radius, box-shadow rgba(0, 0, 0, 0.6) 0px 4px 20px 0px.

## Similar Brands

- **Goodreads** — Book-centric social platform, focuses on community and discovery but with a more utilitarian visual style compared to Fable's whimsy.
- **Blinkist** — Content consumption app with bold, illustrative imagery and clear typographic hierarchy for showcasing books/summaries.
- **Wattpad** — Reading app that combines user-generated content with a distinct, often playful, brand identity and strong community features.
- **Headspace** — App-based service with distinctive, organic illustrations as core to its brand identity, using a controlled color palette.
- **Calm** — App that uses evocative, often full-bleed illustrations and photography with a serene color palette to create an immersive experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canopy: #064c37;
  --color-ocean-deep: #43a1d7;
  --color-midnight-ink: #161015;
  --color-deep-space: #070607;
  --color-slate-shadow: #292229;
  --color-pearl-white: #ffffff;
  --color-parchment: #f7f4ee;
  --color-ghost-gray: #ededed;
  --color-ink-wash: #3f383d;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-heldane-display: 'Heldane Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aktiv-grotesk: 'Aktiv Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: -0.18px;
  --text-subheading: 22px;
  --leading-subheading: 1.09;
  --text-heading: 26px;
  --leading-heading: 1.08;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.94;
  --text-display: 72px;
  --leading-display: 0.88;
  --text-display-lg: 80px;
  --leading-display-lg: 0.86;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-52: 52px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 60px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 60px;
  --radius-largecards: 48px;
  --radius-mediumcards: 24px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.4) 0px 4px 20px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.6) 0px 4px 20px 0px;

  /* Surfaces */
  --surface-ocean-deep-canvas: #43a1d7;
  --surface-parchment-surface: #f7f4ee;
  --surface-pearl-white-element: #ffffff;
  --surface-midnight-ink-elevated: #161015;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canopy: #064c37;
  --color-ocean-deep: #43a1d7;
  --color-midnight-ink: #161015;
  --color-deep-space: #070607;
  --color-slate-shadow: #292229;
  --color-pearl-white: #ffffff;
  --color-parchment: #f7f4ee;
  --color-ghost-gray: #ededed;
  --color-ink-wash: #3f383d;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-heldane-display: 'Heldane Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aktiv-grotesk: 'Aktiv Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: -0.11px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.14px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: -0.18px;
  --text-subheading: 22px;
  --leading-subheading: 1.09;
  --text-heading: 26px;
  --leading-heading: 1.08;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.94;
  --text-display: 72px;
  --leading-display: 0.88;
  --text-display-lg: 80px;
  --leading-display-lg: 0.86;

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
  --spacing-52: 52px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 60px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.4) 0px 4px 20px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.6) 0px 4px 20px 0px;
}
```
