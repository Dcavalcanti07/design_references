# Workable — Style Reference
> Clean canvas, purposeful accents

**Theme:** light

Workable employs a direct and dynamic visual language, built on a clean canvas with a distinctive teal and dark forest green palette. Components are designed to be lightweight, with rounded corners that soften the strong typographic choices. Color is used purposefully for clear accents, interactive states, and to differentiate content blocks, while maintaining an overall sense of order and professionalism. The system balances functional clarity with subtle visual interest, avoiding heavy ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Porcelain | `#fff5ee` | `--color-canvas-porcelain` | Page background, primary light surface |
| White | `#ffffff` | `--color-white` | Card backgrounds, elevated UI elements |
| Midnight Ink | `#0f161e` | `--color-midnight-ink` | Primary text, strong headings, dark UI elements |
| Harbor Mist | `#333942` | `--color-harbor-mist` | Subtle text, muted links, secondary information |
| Forest Canopy | `#012620` | `--color-forest-canopy` | Dark section backgrounds, hero background, decorative fills |
| Deep Teal | `#004038` | `--color-deep-teal` | Primary text color for navigation and headings, outlined button borders, active states |
| Fresh Teal | `linear-gradient(90deg, rgb(0, 245, 220), rgb(213, 255, 77) 48.5%, rgb(183, 115, 255))` | `--color-fresh-teal` | Card backgrounds, tag backgrounds, vibrant accents; Key product graphic fills, vibrant UI elements |
| Muted Sage | `#00544c` | `--color-muted-sage` | Secondary text, sub-brand accents, borders |
| Soft Peach | `#fde8ce` | `--color-soft-peach` | Informational card backgrounds, subtle highlight surfaces |
| Muted Mandarin | `#ffdcbf` | `--color-muted-mandarin` | Accent card backgrounds |
| Sky Haze | `#bee9f4` | `--color-sky-haze` | Accent card backgrounds |
| Lime Glow | `#d5ff4d` | `--color-lime-glow` | Decorative stroke, vibrant highlighting in illustrations |
| Spring Bud | `#7edcaf` | `--color-spring-bud` | Highlight text, decorative fills and borders |

## Tokens — Typography

### Proxima Nova — Primary UI typeface for all content including navigation, body text, headings, and buttons. Its clean, sans-serif structure provides clarity and a modern feel. · `--font-proxima-nova`
- **Substitute:** Open Sans
- **Weights:** 400, 700
- **Sizes:** 16px, 18px, 20px, 24px, 32px, 56px, 72px
- **Line height:** 1.00, 1.13, 1.14, 1.17, 1.20, 1.22, 1.25, 1.38, 1.50, 1.56, 1.75
- **Letter spacing:** normal
- **Role:** Primary UI typeface for all content including navigation, body text, headings, and buttons. Its clean, sans-serif structure provides clarity and a modern feel.

### Source Serif Pro — Used sparingly for specific body copy elements, offering a contrasting serif touch. · `--font-source-serif-pro`
- **Substitute:** Merriweather
- **Weights:** 400
- **Sizes:** 24px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for specific body copy elements, offering a contrasting serif touch.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 18px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.22 | — | `--text-heading-sm` |
| heading | 32px | 1.17 | — | `--text-heading` |
| heading-lg | 56px | 1.13 | — | `--text-heading-lg` |
| display | 72px | 1 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 25px |
| buttons | 16px |
| navigation | 8px |

### Layout

- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Call to action with minimal visual weight

Background transparent, text color #0f161, 0px border-radius, no padding defined. Best for inline actions or secondary CTA when a filled button is elsewhere.

### Secondary Ghost Button
**Role:** Outlined action with rounded corners

Background transparent, text color #0f161, 16px border-radius. Often used for navigation CTAs.

### Default Card
**Role:** Content container for features or information blocks

Background #ffffff, 16px border-radius, 32px padding on all sides. No shadow.

### Highlight Card - Soft Peach
**Role:** Emphasized content container with a warm background tint

Background #fde8ce, 16px border-radius, 32px padding on all sides. No shadow.

### Highlight Card - Fresh Teal
**Role:** Emphasized content container with a vivid background tint

Background #00f5dc, 16px border-radius, 32px padding on all sides. No shadow.

### Highlight Card - Muted Mandarin
**Role:** Emphasized content container with a warm orange background tint

Background #ffdcbf, 16px border-radius, 32px padding on all sides. No shadow.

### Ghost Badge
**Role:** Informational tag or label

Background transparent, text color #0f161, 0px border-radius, no padding defined. Used for meta-information.

### Navigation Link Button
**Role:** Actionable link within navigation

Text color #0f161, 16px border-radius, 0px padding. Used for 'Log in' and 'Request a demo'.

### Contained Navigation Button
**Role:** The primary call to action in the navigation bar

Background #004038, text color white, 16px border-radius. This is a filled button, contrasting with the ghost type.

## Do's and Don'ts

### Do
- Use Proxima Nova for all text elements to maintain typographic consistency.
- Apply 16px border-radius to all cards and buttons for a unified, soft edge.
- Utilize Forest Canopy (#012620) for dark section backgrounds and Deep Teal (#004038) for primary action outlines or filled navigation buttons.
- Employ 32px padding for internal card content and around main section elements.
- Maintain an 8px elementGap between smaller UI components for comfortable dense layouts.
- Prioritize Canvas Porcelain (#fff5ee) as the primary page background to create a clean, light base.
- Use Fresh Teal (#00f5dc) and Soft Peach (#fde8ce) as background tints for cards to visually group or highlight content.

### Don't
- Avoid arbitrary color usage; reserve brand and accent colors for functional roles or distinct highlights, not general decoration.
- Do not introduce complex shadows or extreme elevation; the design favors flat surfaces and subtle distinctions.
- Refrain from using overly decorative fonts; stick to Proxima Nova and Source Serif Pro for a clear, modern appearance.
- Do not deviate from the established 16px and 8px border-radii; random smaller or larger radii will break visual cohesion.
- Avoid dense, unbroken blocks of text; break content with headings, lists, and visual components.
- Do not use dark backgrounds for general page content; restrict them to hero sections or distinct visual breaks.
- Refrain from using system default link colors; ensure all links use either Midnight Ink (#0f161e) or Harbor Mist (#333942) unless an explicit accent link style is defined.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Porcelain | `#fff5ee` | Base page background |
| 1 | White | `#ffffff` | Primary card and elevated component background |
| 2 | Soft Peach | `#fde8ce` | Accentuated card backgrounds for differentiation |
| 3 | Muted Mandarin | `#ffdcbf` | Secondary accent card background |
| 4 | Sky Haze | `#bee9f4` | Tertiary accent card background |

## Imagery

This system primarily uses photography for human elements (diverse faces in cards) and abstract, colorful gradients for product-focused graphics. Photography is typically tightly cropped to faces, conveying a relatable human connection. Illustrations are characterized by abstract shapes and bold gradients, often resembling fluid organic forms rather than hard-edged geometry. Icons (when visible) are typically outlined with a moderate stroke weight, emphasizing clarity and lightness. Imagery serves both decorative atmosphere, product showcase, and providing human context within the UI. The density of imagery is moderate, used to break up text and add visual interest, rather than overwhelming the layout.

## Layout

The page primarily uses a full-bleed structure, with content sections extending across the viewport width, though a clear implicit max-width ensures readability. Hero sections often feature a full-bleed background (e.g., Forest Canopy) with centered headings. Content typically alternates between two-column layouts (text left, image right) and centered stacks. Feature sections use a 3-column card grid. Vertical spacing between sections is consistent at 32px, creating a comfortable yet information-dense rhythm. The navigation is a persistent top bar featuring a logo, product/pricing links, and two call-to-action buttons, maintaining a fixed presence.

## Agent Prompt Guide

### Quick Color Reference
text: #0f161e
background: #fff5ee
border: #0f161e
accent: #00f5dc
primary action: #004038 (outlined action border)

### 3-5 Example Component Prompts
1. Create a hero section with a Forest Canopy (#012620) background. Headline 'The future-ready HR platform' using Proxima Nova, size 56px, weight 700, color white, lineHeight 1.13. Subtext 'Redefining HR...' using Proxima Nova, size 18px, weight 400, color white, lineHeight 1.5. Include a ghost button 'Request a demo' (background transparent, text #0f161e, 0px radius) and a contrasting filled button 'Start a free trial' (background #004038, text white, 16px radius, padding 11px 24px).
2. Design a feature card: Default Card (background #ffffff, 16px radius, 32px padding). Heading 'Talent CRM database' using Proxima Nova, size 24px, weight 700, color #0f161e. Body text 'Manage your talent pool...' using Proxima Nova, size 16px, weight 400, color #333942.
3. Implement a navigation bar: Background transparent. Logo in Deep Teal (#004038). Navigation links ('Product', 'Pricing') text in Midnight Ink (#0f161e), Proxima Nova, size 16px, weight 400. 'Log in' button as a secondary ghost button (background transparent, text #0f161e, 16px radius, padding 12px 24px). 'Request a demo' button as a secondary ghost button (background transparent, text #0f161e, 16px radius, padding 12px 24px). 'Start a free trial' button as a contained navigation button (background #004038, text white, 16px radius, padding 12px 24px).
4. Create a highlight card showing an applicant: Highlight Card - Soft Peach (background #fde8ce, 16px radius, 32px padding). Text 'Applicant tracking system' using Proxima Nova, size 16px, weight 700, color #0f161e. Use an image of a person (16px radius).

## Similar Brands

- **Rippling** — Clean SaaS UI with strong typography and a clear accent color, often featuring human elements in product context.
- **Gusto** — Similar light, approachable aesthetic for HR/payroll, utilizing distinct, soft background colors within content blocks.
- **BambooHR** — Employs a clean layout, clear hierarchy, and uses color strategically for accents and calls to action against a predominantly light background.
- **Greenhouse** — Focus on clean, functional interfaces with distinct branded colors for interactive elements and clear content segmentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-porcelain: #fff5ee;
  --color-white: #ffffff;
  --color-midnight-ink: #0f161e;
  --color-harbor-mist: #333942;
  --color-forest-canopy: #012620;
  --color-deep-teal: #004038;
  --color-fresh-teal: #00f5dc;
  --gradient-fresh-teal: linear-gradient(90deg, rgb(0, 245, 220), rgb(213, 255, 77) 48.5%, rgb(183, 115, 255));
  --color-muted-sage: #00544c;
  --color-soft-peach: #fde8ce;
  --color-muted-mandarin: #ffdcbf;
  --color-sky-haze: #bee9f4;
  --color-lime-glow: #d5ff4d;
  --color-spring-bud: #7edcaf;

  /* Typography — Font Families */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-serif-pro: 'Source Serif Pro', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.13;
  --text-display: 72px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-104: 104px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 25px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 25px;
  --radius-buttons: 16px;
  --radius-navigation: 8px;

  /* Surfaces */
  --surface-canvas-porcelain: #fff5ee;
  --surface-white: #ffffff;
  --surface-soft-peach: #fde8ce;
  --surface-muted-mandarin: #ffdcbf;
  --surface-sky-haze: #bee9f4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-porcelain: #fff5ee;
  --color-white: #ffffff;
  --color-midnight-ink: #0f161e;
  --color-harbor-mist: #333942;
  --color-forest-canopy: #012620;
  --color-deep-teal: #004038;
  --color-fresh-teal: #00f5dc;
  --color-muted-sage: #00544c;
  --color-soft-peach: #fde8ce;
  --color-muted-mandarin: #ffdcbf;
  --color-sky-haze: #bee9f4;
  --color-lime-glow: #d5ff4d;
  --color-spring-bud: #7edcaf;

  /* Typography */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-serif-pro: 'Source Serif Pro', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.13;
  --text-display: 72px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 25px;
}
```
