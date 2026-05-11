# Apple (España) — Style Reference
> Polished Glass Canvas

**Theme:** light

Apple's design system showcases premium clarity through a monochrome palette accented by a singular vibrant blue. Typography is compact and precise, utilizing system fonts to create an invisible UI that emphasizes content and product imagery. Surfaces lean light with subtle tonal shifts, while component forms are softened by large, consistent rounded corners. The overall impression is one of meticulous polish, where the technology recedes to highlight the user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#1d1d1f` | `--color-ink` | Primary text, dark surface backgrounds, card borders, and icon fills. Forms the dark foundation of the UI contrast |
| Snow | `#ffffff` | `--color-snow` | Main page backgrounds and component fills in light contexts. Provides a pristine canvas |
| Cloud | `#f5f5f7` | `--color-cloud` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Graphite | `#707070` | `--color-graphite` | Muted secondary text, placeholder text, and subtle icon fills. Used for less prominent information |
| Midnight | `#000000` | `--color-midnight` | Hero section backgrounds, prominent heading text, and strong borders. Used sparingly for maximum impact |
| Silver | `#d6d6d6` | `--color-silver` | Subtle dividers and border elements, particularly within lists |
| Steel | `#474747` | `--color-steel` | Navigation text and specific link colors, offering a slightly softer alternative to Ink |
| Glaucus Blue | `#0066cc` | `--color-glaucus-blue` | Interactive link text and border accents for outlined or ghost actions, signaling interactivity |
| Signal Blue | `#0071e3` | `--color-signal-blue` | Primary Call To Action button backgrounds. This vivid blue is the single chromatic accent that drives user action |
| Emerald Green | `#03aa49` | `--color-emerald-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Electric Violet | `#8668ff` | `--color-electric-violet` | Decorative color, often for product accents or background elements |
| Sunrise Orange | `#ed6300` | `--color-sunrise-orange` | Decorative color, often for product accents or background elements |
| Ocean Teal | `#00a1b3` | `--color-ocean-teal` | Decorative color, often for product accents or background elements |

## Tokens — Typography

### SF Pro Text — Used for all body text, navigation elements, buttons, and most informational content. Its purpose is legibility and compact information delivery, designed to disappear into the background. · `--font-sf-pro-text`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 12px, 14px, 17px, 20px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.33, 1.43, 1.47, 1.83
- **Letter spacing:** -0.0220em at 12px, -0.0190em at 14px, -0.0160em at 17px, -0.0100em at 20px, -0.0030em at 44px
- **OpenType features:** `"numr"`
- **Role:** Used for all body text, navigation elements, buttons, and most informational content. Its purpose is legibility and compact information delivery, designed to disappear into the background.

### SF Pro Display — Reserved for headlines and hero typography, giving prominence and impact. The tighter tracking at larger sizes ensures words still feel connected and impactful, rather than airy. · `--font-sf-pro-display`
- **Substitute:** Inter
- **Weights:** 600, 700
- **Sizes:** 21px, 24px, 28px, 48px, 56px, 60px, 64px, 260px
- **Line height:** 0.85, 1.00, 1.06, 1.07, 1.08, 1.14, 1.33
- **Letter spacing:** -0.0150em at 21px, -0.0090em at 24px, -0.0050em at 28px, -0.0030em at 48px, 0.0070em at 56px, 0.0090em at 60px, 0.0110em at 64px
- **OpenType features:** `"numr"`
- **Role:** Reserved for headlines and hero typography, giving prominence and impact. The tighter tracking at larger sizes ensures words still feel connected and impactful, rather than airy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | -0.26px | `--text-caption` |
| body-sm | 14px | 1.47 | -0.27px | `--text-body-sm` |
| body | 17px | 1.24 | -0.27px | `--text-body` |
| subheading | 20px | 1.33 | -0.2px | `--text-subheading` |
| heading | 28px | 1.07 | -0.14px | `--text-heading` |
| heading-lg | 48px | 1.08 | -0.14px | `--text-heading-lg` |
| display | 60px | 1.06 | 0.54px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 89 | 89px | `--spacing-89` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 28px |
| links | 10px |
| badges | 28px |
| fields | 28px |
| buttons | 980px |

### Layout

- **Section gap:** 30px
- **Card padding:** 28px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled button with Signal Blue background (#0071e3), Snow text (#ffffff), and a highly rounded 'pill' shape (980px radius). Padding is 8px vertical, 15px horizontal.

### Ghost Button (Dark)
**Role:** Secondary action on dark backgrounds

Transparent background (rgba(0, 0, 0, 0)), Snow text (#ffffff / 80% opacity), zero padding, and no border. Often used in navigation or toolbars, with 36px radius for button content areas.

### Ghost Button (Light)
**Role:** Secondary action on light backgrounds

Transparent background (rgba(0, 0, 0, 0)), Ink text (#1d1d1f), zero padding, and no explicit border. Often used in contextual menus or text-heavy action areas, with 28px radius.

### Segmented Control Button
**Role:** Toggle between options or views

Rounded button with rgba(66, 66, 69, 0.72) background, Snow text (#ffffff / 80% opacity), and 36px radius. Used for active states within a button group.

### Light Content Card
**Role:** Prominent content container on light backgrounds

Snow background (#ffffff), 28px border-radius, no shadow, with 0px padding. Designed to lift content subtly from the background.

### Dark Content Card
**Role:** Prominent content container on dark backgrounds

Ink background (#1d1d1f), 28px border-radius, no shadow, with 0px padding. Used for feature blocks where the background theme is dark.

### Badge (Neutral background)
**Role:** Informational tag with subtle background

Cloud background (#f5f5f7), Ink text (#1d1d1f), 0px border-radius, with 160px top padding and 0px horizontal padding. Content-aware padding suggests usage as specific product detail badges.

### Navigation Link
**Role:** Primary navigation item

Text link using SF Pro Text at 17px weight 400, Graphite color (#707070). Default interactive state, no explicit border or background padding.

## Do's and Don'ts

### Do
- Use Ink (#1d1d1f) for all primary body text, headlines, and darker UI elements to maintain high contrast and legibility.
- Apply Snow (#ffffff) as the default page background and for elevated card surfaces in light sections.
- Employ Signal Blue (#0071e3) exclusively for primary action buttons, ensuring a clear and consistent call to action.
- Maintain a large border-radius of 28px for all cards and most interactive elements to convey a soft, approachable feel.
- Prioritize SF Pro Text for all informational and functional text, utilizing its range of weights for hierarchy within body content.
- Reserve SF Pro Display for headlines and prominent display text (e.g., above 28px) to leverage its impactful letter-spacing and strong presence.
- Use Cloud (#f5f5f7) for subtle background shifts to differentiate sections without hard boundaries, creating a soft visual rhythm.

### Don't
- Avoid using multiple chromatic colors for primary calls to action; Signal Blue (#0071e3) holds that exclusive role.
- Do not introduce strong drop shadows; the design relies on subtle tonal shifts and large radii for depth and separation.
- Refrain from using heavily decorative fonts or extreme letter-spacing in body text; legibility and understated precision are key.
- Do not use square corners for interactive elements or cards; the rounded aesthetic is a core part of the brand's tactile feel.
- Avoid dense, information-heavy sections without appropriate negative space; uphold the comfortable density and visual breathing room.
- Do not deviate from the established typography sizes and line heights; precise scale and leading are crucial for visual harmony.
- Do not use gradients as primary surface fills; surfaces should remain flat or subtly textured by background colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Snow Canvas | `#ffffff` | Base page background and primary container fill for content. |
| 1 | Cloud Panel | `#f5f5f7` | Secondary background for sections or cards, providing subtle elevation and visual distinction off the main canvas. |
| 2 | Ink Card | `#1d1d1f` | Elevated card background for presenting product details or features within dark themed sections. |

## Imagery

The visual language is product-centric, dominated by high-quality, often full-bleed photography and realistic product renders. Photography features lifestyle contexts but remains focused on the product's integration. Product shots are meticulously detailed, showcasing devices at various angles and in use. Illustrations are typically minimalist, flat, and serve to explain features or demonstrate concepts, often incorporating geometric shapes. Icons are monochrome, delicate (thin stroke weight), and serve functional UI purposes. Imagery functions to showcase the product with an emphasis on its real-world application and aesthetic appeal, rather than purely decorative atmosphere, occupying significant visual space relative to text.

## Layout

The page primarily uses a max-width contained layout, though the hero section is full-bleed, setting a grand initial impression. The hero features large, centered headline text over a dynamic image background while retaining a traditional top navigation bar. Subsequent sections alternate between light and dark backgrounds, creating a clear vertical rhythm. Content is arranged in alternating text-left/image-right or centered stack patterns. Card grids are used for features, showcasing multiple product benefits. Vertical spacing between sections is generous and consistent, contributing to a spacious feel. The navigation is a sticky top bar, minimal and functional, reinforcing the focus on product content.

## Agent Prompt Guide

Quick Color Reference:
text: #1d1d1f
background: #ffffff
border: #1d1d1f
accent: #0066cc
primary action: #0071e3 (filled action)

Example Component Prompts:
1. Create a hero section: full-bleed background set to Ink (#000000), with a centered 'SF Pro Display' headline at 60px weight 700 (#ffffff, letter-spacing +0.0090em). Beneath, a 'SF Pro Text' subheadline at 20px weight 400 (#ffffff, letter-spacing -0.0100em). Place a primary action button ('Signal Blue' background #0071e3, opaque 'Snow' text #ffffff, 980px radius, 8px vertical padding, 15px horizontal padding) below the subheadline.
2. Design a feature card: 'Snow' background (#ffffff), 28px border-radius, with an 'Ink' (#1d1d1f) heading using 'SF Pro Display' at 28px weight 600 (letter-spacing -0.0050em). Body text uses 'SF Pro Text' at 17px weight 400 (#1d1d1f, letter-spacing -0.0160em). Include a simple 'Glaucus Blue' (#0066cc) text link at 17px weight 400.
3. Create a Primary Action Button: #0071e3 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Samsung** — Similar product-focused imagery, clean layouts, and a restrained color palette that lets the hardware shine.
- **Google (Hardware)** — Emphasis on sleek product photography, system typography, and a clean, accessible UI that prioritizes content.
- **Tesla** — Minimalist design, strong emphasis on product imagery over busy UI, and a focus on essential information presented clearly.
- **Linear** — Clean, compact typography, strategic use of a single accent color for interactivity, and emphasis on product clarity with minimal decorative elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #1d1d1f;
  --color-snow: #ffffff;
  --color-cloud: #f5f5f7;
  --color-graphite: #707070;
  --color-midnight: #000000;
  --color-silver: #d6d6d6;
  --color-steel: #474747;
  --color-glaucus-blue: #0066cc;
  --color-signal-blue: #0071e3;
  --color-emerald-green: #03aa49;
  --color-electric-violet: #8668ff;
  --color-sunrise-orange: #ed6300;
  --color-ocean-teal: #00a1b3;

  /* Typography — Font Families */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: -0.26px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.47;
  --tracking-body-sm: -0.27px;
  --text-body: 17px;
  --leading-body: 1.24;
  --tracking-body: -0.27px;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.07;
  --tracking-heading: -0.14px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.14px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: 0.54px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-89: 89px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 28px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;

  /* Named Radii */
  --radius-cards: 28px;
  --radius-links: 10px;
  --radius-badges: 28px;
  --radius-fields: 28px;
  --radius-buttons: 980px;

  /* Surfaces */
  --surface-snow-canvas: #ffffff;
  --surface-cloud-panel: #f5f5f7;
  --surface-ink-card: #1d1d1f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #1d1d1f;
  --color-snow: #ffffff;
  --color-cloud: #f5f5f7;
  --color-graphite: #707070;
  --color-midnight: #000000;
  --color-silver: #d6d6d6;
  --color-steel: #474747;
  --color-glaucus-blue: #0066cc;
  --color-signal-blue: #0071e3;
  --color-emerald-green: #03aa49;
  --color-electric-violet: #8668ff;
  --color-sunrise-orange: #ed6300;
  --color-ocean-teal: #00a1b3;

  /* Typography */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: -0.26px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.47;
  --tracking-body-sm: -0.27px;
  --text-body: 17px;
  --leading-body: 1.24;
  --tracking-body: -0.27px;
  --text-subheading: 20px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.2px;
  --text-heading: 28px;
  --leading-heading: 1.07;
  --tracking-heading: -0.14px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.14px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: 0.54px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-89: 89px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;
}
```
