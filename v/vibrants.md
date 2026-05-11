# Vibrants — Style Reference
> white canvas, vibrant accents

**Theme:** light

Vibrants uses a clean, bright aesthetic where information is presented on a spacious white canvas. Typography is primarily functional, with clear sans-serifs defining structure, while a custom display font adds a touch of friendly sophistication to headlines. The system relies on a focused color palette, primarily neutral for backgrounds and text, punctuated by a vibrant green accent color that signals action. Components are lightweight with subtle rounding and minimal elevation, maintaining an airy and approachable feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#021422` | `--color-midnight-ink` | Primary text, darker backgrounds, footer background, primary button background for filled state. Creates a strong contrast against white |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, ghost button backgrounds, primary button text. Serves as the primary canvas |
| Fog Gray | `#e6e8e9` | `--color-fog-gray` | Hairline dividers, subtle borders, navigation separators. Provides soft visual separation without harsh lines |
| Canvas Ice | `#f2f6ff` | `--color-canvas-ice` | Subtle background for specific card sections, indicating a slight shift in surface level |
| Smoke Stone | `#ccd2d7` | `--color-smoke-stone` | Card borders, muted badge backgrounds. Offers a slightly darker neutral for structural guidance |
| Forest Green | `#00852e` | `--color-forest-green` | Primary action background, promotional badge accents. A vivid, singular accent color for interaction and highlighting offers |
| Sky Blue | `#91c3ff` | `--color-sky-blue` | Outline button borders, secondary interactive text/icons. A moderate blue used for ghost/outlined CTA states |
| Deep Ocean | `#001f38` | `--color-deep-ocean` | Secondary text, descriptive elements within cards. A muted blue-gray for supporting content |
| Asphalt Gray | `#808f9c` | `--color-asphalt-gray` | Muted descriptive text, card subheadings. Softer than primary text for secondary information |
| Charcoal Haze | `#6a7c89` | `--color-charcoal-haze` | Lighter supporting body text, small print. Even softer than Asphalt Gray for less prominent text |
| Star Dust | `#ffb931` | `--color-star-dust` | Decorative icon accents, subtle highlights. A warm yellow primarily used for small decorative elements |
| Rainbow Wash Gradient | `linear-gradient(300deg, rgba(114, 77, 153, 0.05) 0px, rgba(58, 61, 138, 0.05) 17.39%, rgba(2, 175, 224, 0.05) 34.81%, rgba(95, 183, 62, 0.05) 51.04%, rgba(255, 237, 0, 0.05) 66.67%, rgba(237, 116, 43, 0.05) 83.16%, rgba(222, 39, 53, 0.05))` | `--color-rainbow-wash-gradient` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Montserrat — Body copy, button text, navigation links, and smaller supporting text. Provides clear readability and a functional, modern sans-serif base. · `--font-montserrat`
- **Substitute:** Arial
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 20px
- **Line height:** 1.00, 1.14, 1.20, 1.33, 1.38, 1.50, 1.71, 1.80
- **Letter spacing:** 1.3px at 10px, 1.0px at 12px
- **Role:** Body copy, button text, navigation links, and smaller supporting text. Provides clear readability and a functional, modern sans-serif base.

### new-kansas — Brand headlines, prominent titles. Its custom nature provides a unique, friendly yet authoritative voice, especially in larger sizes with subtle negative tracking. · `--font-new-kansas`
- **Substitute:** Georgia
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 15px, 16px, 18px, 20px, 22px, 24px, 28px, 32px, 36px, 44px, 48px
- **Line height:** 1.00, 1.13, 1.17, 1.20, 1.22, 1.25, 1.29, 1.33, 1.43, 1.50, 1.75, 2.00
- **Letter spacing:** -0.96px at 48px, -0.72px at 36px, -0.44px at 22px
- **Role:** Brand headlines, prominent titles. Its custom nature provides a unique, friendly yet authoritative voice, especially in larger sizes with subtle negative tracking.

### Inter — Card titles, meta information, and secondary headings. Complements Montserrat with slightly tighter tracking for structured content, offering a more contemporary feel. · `--font-inter`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px
- **Line height:** 1.00, 1.08, 1.20, 1.23, 1.25, 1.33
- **Letter spacing:** -1.04px at 13px, -0.28px at 12px
- **Role:** Card titles, meta information, and secondary headings. Complements Montserrat with slightly tighter tracking for structured content, offering a more contemporary feel.

### rift-soft — Promotional badges. Its chunky, bold display style with wide letter-spacing creates immediate visual impact for offers. · `--font-rift-soft`
- **Substitute:** Impact
- **Weights:** 600
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** 1.008px at 16px
- **Role:** Promotional badges. Its chunky, bold display style with wide letter-spacing creates immediate visual impact for offers.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 1.3px | `--text-caption` |
| body | 14px | 1.71 | — | `--text-body` |
| heading-sm | 22px | 1.43 | -0.44px | `--text-heading-sm` |
| heading | 36px | 1.25 | -0.72px | `--text-heading` |
| display | 48px | 1.2 | -0.96px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 20px |
| cards | 8px |
| badges | 3px |
| inputs | 8px |
| buttons | 8px |

### Layout

- **Section gap:** 39px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Highlight key actions.

Background: Forest Green (#00852e), Text: Cloud White (#ffffff), Border Radius: 8px, Padding: 16px vertical, 32px horizontal. Uses Montserrat bold. For high-conversion actions.

### Outline Accent Button
**Role:** Secondary calls to action, prominent links.

Background: Cloud White (#ffffff), Text: Sky Blue (#91c3ff), Border: 1px solid Sky Blue (#91c3ff), Border Radius: 0px. Minimal padding, text-based. For actions that need emphasis but not a strong fill.

### Dark Filled Button
**Role:** Primary Call to action, often in hero sections.

Background: Midnight Ink (#021422), Text: Cloud White (#ffffff), Border Radius: 5px, Padding: 18px vertical, 80px horizontal. Uses Montserrat with generous horizontal padding for visual weight.

### Pill Outline Button
**Role:** Filter options, secondary choices.

Background: Cloud White (#ffffff), Text: Midnight Ink (#021422), Border: 1px solid Midnight Ink (#021422), Border Radius: 20px (pill shape), Padding: 20px vertical, 32px horizontal. Provides a friendly, selectable appearance.

### Product Card
**Role:** Display individual patch products.

Background: transparent, Border Radius: 8px 8px 0px 0px (top), 0px 0px 8px 8px (bottom), Box Shadow: none. Content padding: 16px. Designed as two stacked components (image part, text part) with subtle corner rounding, maintaining an airy feel.

### Promotional Badge
**Role:** Highlight discounts and offers.

Background: Forest Green (#00852e), Text: Cloud White (#ffffff), Border Radius: 3px, Padding: 3px vertical, 6px horizontal. Uses rift-soft font for high visibility.

### Neutral Tag Badge
**Role:** Categorization or status indicators.

Background: Smoke Stone (#ccd2d7), Text: Midnight Ink (#021422), Border Radius: 32px (pill shape). Minimal padding, often for icons or short labels.

## Do's and Don'ts

### Do
- Use Midnight Ink (#021422) for all primary body text and most headings to ensure strong contrast and legibility.
- Apply Cloud White (#ffffff) as the dominant background color for pages and cards to maintain a spacious and clean aesthetic.
- Reserve Forest Green (#00852e) exclusively for primary call-to-action buttons and prominent promotional badges.
- Employ new-kansas for main headlines and titles, leveraging its custom weight and negative letter-spacing for brand distinction.
- Maintain an inverse border radius for card elements, using 8px at the product image's top and 8px at the content area's bottom, with a seamless middle for content flow.
- Use a minimum element gap of 16px to ensure comfortable spacing between UI elements and content blocks.
- Apply a 1px solid Fog Gray (#e6e8e9) border for subtle dividers and navigation item separation, not for card outlines.

### Don't
- Do not use highly saturated colors for large background areas; limit them to accents and interactive elements.
- Avoid generic system fonts for headlines; the custom new-kansas and rift-soft families are integral to brand identity.
- Do not introduce strong drop shadows; keep elevation subtle, if present at all, to maintain the light and airy feel.
- Do not use multiple accent colors prominently; rely on Forest Green (#00852e) and Sky Blue (#91c3ff) for most interactive states.
- Avoid dense, information-heavy blocks of text; break content into manageable cards or sections with ample white space.
- Do not use hard, sharp corners on interactive elements; consistently apply 8px or 3px radii for buttons and badges, or 20px/32px for pill shapes.
- Refrain from dark mode implementations; the system is designed explicitly for a light theme with high contrast primary text and backgrounds.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud White Canvas | `#ffffff` | Primary page background and default surface for most content cards. |
| 1 | Canvas Ice Card | `#f2f6ff` | Subtle background for specific card sections, indicating a slight elevation or different content grouping. |

## Imagery

The site uses a mix of minimal product photography and stylized abstract representations. Product imagery features tight crops of patches, often on a white or simple background, focusing solely on the item. Illustrations associated with products (like 'Calm Down' or 'Stay Focused') are stylized, flat, and incorporate gradient backgrounds or color overlays. Icons are simple, outlined, and monochromatic, used for navigation and minor functional elements. The overall visual language is one of clarity and focus, where images serve either to directly showcase the product or to convey an abstract benefit.

## Layout

The page primarily utilizes a max-width contained layout, allowing for generous side margins on larger screens. The hero section is full-width with a split text-left/visual-right pattern, effectively introducing the product. Content below the hero alternates between full-width sections and grid-based arrangements. A prominent 3-column card grid is used for displaying product categories ('Our Patches', 'Our Bundles'), ensuring a consistent visual rhythm. Vertical spacing between sections is comfortable, contributing to the airy feel. Navigation consists of a sticky top bar with a left-aligned logo and right-aligned utilitarian icons.

## Agent Prompt Guide

### Quick Color Reference
text: #021422
background: #ffffff
border: #e6e8e9
accent: #00852e
primary action: #00852e (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Cloud White (#ffffff) background. Headline 'Start feeling better, naturally' `new-kansas` at 48px, weight 700, Midnight Ink (#021422), letter-spacing -0.96px. Subtext 'Feel better with bio-frequency patches for stress, sleep, focus, and recovery.' `Montserrat` at 16px, weight 400, #021422. Primary Filled Button 'SHOP PATCHES': Forest Green (#00852e) background, Cloud White (#ffffff) text, 8px radius, 16px vertical, 32px horizontal padding.
2. Create a product card for a patch: Background transparent. Title 'Bounce Back Patches' `Inter` at 16px, weight 600, #021422. Subtitle 'Essential Pack' `Asphalt Gray` (#808f9c) at 14px, weight 400. Display a Promotional Badge '40% OFF': Forest Green (#00852e) background, Cloud White (#ffffff) text, 3px radius, 3px vertical, 6px horizontal padding.
3. Create a navigation link: `Montserrat` at 14px, weight 500, Midnight Ink (#021422). No background, no border, normal letter spacing. Use 12px vertical padding on hover. The hover state changes text color to Sky Blue (#91c3ff).

## Similar Brands

- **Oura Ring** — Similar white canvas, premium product focus, and accent colors for status/interaction.
- **WHOOP** — Clean, health-tech aesthetic with a focus on clear typography and functional color accents.
- **Calm** — Uses a calm, spacious layout with a dominant light/white theme and specific accent colors for key actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #021422;
  --color-cloud-white: #ffffff;
  --color-fog-gray: #e6e8e9;
  --color-canvas-ice: #f2f6ff;
  --color-smoke-stone: #ccd2d7;
  --color-forest-green: #00852e;
  --color-sky-blue: #91c3ff;
  --color-deep-ocean: #001f38;
  --color-asphalt-gray: #808f9c;
  --color-charcoal-haze: #6a7c89;
  --color-star-dust: #ffb931;
  --color-rainbow-wash-gradient: #724d99;
  --gradient-rainbow-wash-gradient: linear-gradient(300deg, rgba(114, 77, 153, 0.05) 0px, rgba(58, 61, 138, 0.05) 17.39%, rgba(2, 175, 224, 0.05) 34.81%, rgba(95, 183, 62, 0.05) 51.04%, rgba(255, 237, 0, 0.05) 66.67%, rgba(237, 116, 43, 0.05) 83.16%, rgba(222, 39, 53, 0.05));

  /* Typography — Font Families */
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-new-kansas: 'new-kansas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rift-soft: 'rift-soft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 1.3px;
  --text-body: 14px;
  --leading-body: 1.71;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.44px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.72px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.96px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 39px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-pill: 20px;
  --radius-cards: 8px;
  --radius-badges: 3px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-cloud-white-canvas: #ffffff;
  --surface-canvas-ice-card: #f2f6ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #021422;
  --color-cloud-white: #ffffff;
  --color-fog-gray: #e6e8e9;
  --color-canvas-ice: #f2f6ff;
  --color-smoke-stone: #ccd2d7;
  --color-forest-green: #00852e;
  --color-sky-blue: #91c3ff;
  --color-deep-ocean: #001f38;
  --color-asphalt-gray: #808f9c;
  --color-charcoal-haze: #6a7c89;
  --color-star-dust: #ffb931;
  --color-rainbow-wash-gradient: #724d99;

  /* Typography */
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-new-kansas: 'new-kansas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rift-soft: 'rift-soft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 1.3px;
  --text-body: 14px;
  --leading-body: 1.71;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.44px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.72px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 50px;
}
```
