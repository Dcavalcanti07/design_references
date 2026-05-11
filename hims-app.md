# Hims App — Style Reference
> Rounded digital canvas.

**Theme:** light

The Hims App design system projects a clean, spacious, and subtly playful aesthetic. A generous use of white space and large, rounded corner elements creates an open, approachable feel. Typography is dominant, with large, bold headings drawing attention, while a single vivid violet provides a consistent brand accent. Shadows are soft and diffuse, adding a gentle sense of depth without harsh contrasts, framing content on the bright canvas.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| App Brand Violet | `#5d48db` | `--color-app-brand-violet` | Major brand accent color for headings that announce key features and sections. The color choice ensures these elements are distinct and inviting |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary background for the entire application, card surfaces, and key content blocks. Its extensive use creates an airy and unobstructed visual environment |
| Ink Black | `#000000` | `--color-ink-black` | Primary text color for body copy, navigational elements, and strong headings. Provides high contrast against Canvas White for optimal legibility |
| Subtle Gray | `#f0f0f0` | `--color-subtle-gray` | Background for secondary list items or subtle separators, providing a gentle visual break from pure white. Used for subtle text in less prominent UI elements |
| Deep Charcoal | `#2e2e2e` | `--color-deep-charcoal` | Used for prominent heading text, offering a slightly softer alternative to Ink Black while maintaining strong contrast |
| Border Light Gray | `#e0e0e0` | `--color-border-light-gray` | Fine borders and dividers for lists and subtle UI elements. Its lightness maintains the overall spacious and unburdened aesthetic |
| Muted Text Gray | `#8f8f8f` | `--color-muted-text-gray` | Secondary and helper text, links in less prominent areas. Softens the text appearance for less critical information |

## Tokens — Typography

### sofia — The primary typeface for all text content. Its clean, humanist characteristics support both large, impactful headlines and legible body copy, contributing to the app's friendly and accessible tone. The varied weights and sizes allow for a rich typographic hierarchy. · `--font-sofia`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 35px, 37px, 39px, 44px, 81px, 84px, 85px, 141px, 220px, 280px
- **Line height:** 1.00, 1.04, 1.10, 1.15, 1.18, 1.20, 1.25, 1.33, 1.43, 1.67, 2.44, 2.50, 2.78
- **Letter spacing:** -0.0570em at largest sizes, reducing to -0.0120em for body text
- **Role:** The primary typeface for all text content. Its clean, humanist characteristics support both large, impactful headlines and legible body copy, contributing to the app's friendly and accessible tone. The varied weights and sizes allow for a rich typographic hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | -0.16px | `--text-caption` |
| body-sm | 16px | 1.33 | -0.19px | `--text-body-sm` |
| body | 18px | 1.25 | -0.22px | `--text-body` |
| subheading | 20px | 1.2 | -0.24px | `--text-subheading` |
| heading-sm | 24px | 1.15 | -0.29px | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.38px | `--text-heading` |
| heading-lg | 39px | 1.04 | -0.47px | `--text-heading-lg` |
| display | 81px | 1 | -0.97px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |
| 156 | 156px | `--spacing-156` |
| 160 | 160px | `--spacing-160` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 45px |
| navigation | 52px |
| genericComponent | 30px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.12) 0px 27px 104px 0px` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.11) 0px 8px 127px 0px` | `--shadow-xl-2` |
| xl-3 | `rgba(0, 0, 0, 0.25) 0px 9px 46px 0px` | `--shadow-xl-3` |
| xl-4 | `rgba(0, 0, 0, 0.06) 0px 8px 30px 0px` | `--shadow-xl-4` |

### Layout

- **Section gap:** 90px
- **Card padding:** 32px
- **Element gap:** 20px

## Components

### Primary Header
**Role:** Top navigation bar

A fixed element at the top of the page, acting as the brand anchor and universal download call to action. Features the 'Hims & Hers' logo in Ink Black on Canvas White, with a 'Download now' button to the far right. No background fill, utilizing the page body as its background. Features a soft shadow rgba(0, 0, 0, 0.06) 0px 8px 30px 0px for subtle elevation.

### Download Now Button
**Role:** Primary Call to Action in header

Contained within the header, this button is Canvas White with Ink Black text, 52px border radius. It is a ghost button, defined only by its subtle shadow rgba(0, 0, 0, 0.06) 0px 8px 30px 0px and the text 'Download now'.

### Hero Section Card
**Role:** Prominent content container for hero sections

Large, rounded card used in the hero, often appearing as a device mockup frame. Background is Canvas White with a generous 45px border radius. Its prominence is established by a soft, spread-out shadow: rgba(0, 0, 0, 0.12) 0px 27px 104px 0px.

### Feature Section Heading
**Role:** Large, descriptive titles for major sections

Headings like 'Total care. Totally different.' use App Brand Violet (#5d48db) with a Sofia font, often at very large sizes (81px or 141px) and a line height of 1.0, and letter-spacing -0.0570em. These headings are the primary visual anchor for each content section.

### Informational Card
**Role:** General purpose content container

Used throughout the page for various content blocks. It has a Canvas White background and a 30px border radius, providing a softer boundary than sharp edges. Features a subtle shadow `rgba(0, 0, 0, 0.11) 0px 8px 127px 0px` for minimal uplift.

### List Item with Subtle Gray Background
**Role:** Standard list item for structured content

List items (e.g., in FAQ sections) have a Subtle Gray (#f0f0f0) background with Ink Black text. These items use Border Light Gray (#e0e0e0) for dividers, ensuring visual separation without heavy lines.

## Do's and Don'ts

### Do
- Always use Canvas White (#ffffff) as the primary background for all UI elements to maintain a spacious and clinical aesthetic.
- Apply App Brand Violet (#5d48db) sparingly, primarily for high-impact headings and key brand identifiers where a vibrant accent is desired.
- Utilize large border radii, specifically 45px for cards and 52px for interactive elements in the header, to promote a soft, approachable feel.
- Employ Sofia font for all text content, selecting weights 400 or 500 depending on hierarchy, and meticulously adjust letter-spacing as per the type scale.
- Introduce depth and hierarchy through soft, diffuse shadows like rgba(0, 0, 0, 0.12) 0px 27px 104px 0px for prominent cards, rather than hard lines or strong gradients.
- Maintain generous sectionGap of 90px and elementGap of 20px to ensure an uncluttered and spacious layout.
- Ensure all interactive elements, even ghost buttons, have a clearly defined shadow or border for discoverability.

### Don't
- Avoid using saturated background colors for primary content areas; stick to Canvas White or Subtle Gray to maintain visual lightness.
- Do not introduce sharp corners or small radii; the system's roundedness is a core visual identity.
- Refrain from heavy, opaque dividers or borders. Instead, use Border Light Gray (#e0e0e0) or Subtle Gray (#f0f0f0) backgrounds for visual separation.
- Do not apply bold or black text for every heading; utilize Deep Charcoal (#2e2e2e) for impactful but softer headings and Muted Text Gray (#8f8f8f) for secondary information.
- Avoid complex, multi-color gradient backgrounds on UI components; reserve gradients for large, atmospheric background elements if necessary, ensuring they are subtle.
- Do not use letter-spacing values tighter than -0.0570em for large display text or looser than default for body text.
- Do not cluster elements too closely; always respect the established elementGap of 20px and sectionGap of 90px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and base for all major content areas. |
| 1 | Informational Card Background | `#ffffff` | Background for general content cards, distinguished by soft shadows and radius. |
| 2 | List Item Background | `#f0f0f0` | Background for secondary content blocks like list items or feature details, offering a slight visual break. |

## Elevation

- **Card (Large):** `rgba(0, 0, 0, 0.12) 0px 27px 104px 0px`
- **Card (Standard):** `rgba(0, 0, 0, 0.11) 0px 8px 127px 0px`
- **Header Navigation:** `rgba(0, 0, 0, 0.06) 0px 8px 30px 0px`

## Imagery

The visual language for imagery is characterized by product screenshots within device mockups (specifically phones), often held by hands with diverse skin tones. These images serve a product showcase and explanatory role. Abstract and atmospheric gradients are used in the background to provide mood without distracting from the central product. Icons are filled, bold, and black, representing objects or concepts directly without extraneous detail, emphasizing clear communication. Imagery is contained within rounded frames or device screens, emphasizing integration rather than raw, full-bleed visuals. Visuals are dominant within sections, balancing text-heavy areas.

## Layout

The page primarily employs a max-width contained layout, though the hero section often creates a sense of full-bleed through background gradients and centered elements on a Canvas White backdrop. The hero features a large, centered headline on a gradient background, followed by a prominently placed device mockup showcasing the app. Sections maintain a consistent vertical rhythm with a 90px sectionGap. Content is typically arranged in centered stacks or two-column text-left/image-right configurations. Call-to-action elements like the 'Download now' button are consistently placed in the top right of the sticky header. The composition feels spacious and organized, prioritizing legible content delivery.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e0e0e0
accent: #5d48db
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with a 'Total care. Totally different.' heading: background is a gradient from rgb(150, 133, 255) to rgb(181, 173, 225). Headline 'Total care. Totally different.', color #5d48db, sofia weight 500, size 81px, lineHeight 1.0, letter-spacing -0.97px. Below the headline, place a device mockup within a Canvas White (#ffffff) card with 45px border-radius and shadow rgba(0, 0, 0, 0.12) 0px 27px 104px 0px.
2. Design a feature card for 'Care': Canvas White (#ffffff) background, 30px border-radius, shadow rgba(0, 0, 0, 0.11) 0px 8px 127px 0px. Inside, use a Sofia weight 500 heading, size 32px, Ink Black (#000000), lineHeight 1.1, letter-spacing -0.38px; and body text in Sofia weight 400, size 18px, Muted Text Gray (#8f8f8f), lineHeight 1.25. Use 32px cardPadding.
3. Create a header navigation bar: Height fixed at approximately 70px. Left: 'hims & hers' logo in Ink Black (#000000). Right: ghost 'Download now' button with Ink Black (#000000) text, Sofia weight 500, size 14px, 52px border-radius, shadow of rgba(0, 0, 0, 0.06) 0px 8px 30px 0px, and 16px vertical padding, 22px horizontal padding. The header has a shadow of rgba(0, 0, 0, 0.06) 0px 8px 30px 0px.

## Similar Brands

- **Calm** — Shares a spacious, clean aesthetic with generous white space and soft, rounded UI elements.
- **Headspace** — Similar use of soothing background gradients paired with simple, bold typography and product-focused imagery within device frames.
- **Apple** — Employs an emphasis on clear typography, prominent product showcases (device mockups), and clean, uncluttered layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-app-brand-violet: #5d48db;
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-subtle-gray: #f0f0f0;
  --color-deep-charcoal: #2e2e2e;
  --color-border-light-gray: #e0e0e0;
  --color-muted-text-gray: #8f8f8f;

  /* Typography — Font Families */
  --font-sofia: 'sofia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.16px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: -0.19px;
  --text-body: 18px;
  --leading-body: 1.25;
  --tracking-body: -0.22px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.24px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.29px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.38px;
  --text-heading-lg: 39px;
  --leading-heading-lg: 1.04;
  --tracking-heading-lg: -0.47px;
  --text-display: 81px;
  --leading-display: 1;
  --tracking-display: -0.97px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-156: 156px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 90px;
  --card-padding: 32px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 45px;
  --radius-full: 52px;

  /* Named Radii */
  --radius-cards: 45px;
  --radius-navigation: 52px;
  --radius-genericcomponent: 30px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 27px 104px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.11) 0px 8px 127px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.25) 0px 9px 46px 0px;
  --shadow-xl-4: rgba(0, 0, 0, 0.06) 0px 8px 30px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-informational-card-background: #ffffff;
  --surface-list-item-background: #f0f0f0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-app-brand-violet: #5d48db;
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-subtle-gray: #f0f0f0;
  --color-deep-charcoal: #2e2e2e;
  --color-border-light-gray: #e0e0e0;
  --color-muted-text-gray: #8f8f8f;

  /* Typography */
  --font-sofia: 'sofia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.16px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.33;
  --tracking-body-sm: -0.19px;
  --text-body: 18px;
  --leading-body: 1.25;
  --tracking-body: -0.22px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.24px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.29px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.38px;
  --text-heading-lg: 39px;
  --leading-heading-lg: 1.04;
  --tracking-heading-lg: -0.47px;
  --text-display: 81px;
  --leading-display: 1;
  --tracking-display: -0.97px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-156: 156px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 45px;
  --radius-full: 52px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 27px 104px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.11) 0px 8px 127px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.25) 0px 9px 46px 0px;
  --shadow-xl-4: rgba(0, 0, 0, 0.06) 0px 8px 30px 0px;
}
```
