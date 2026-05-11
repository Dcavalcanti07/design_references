# Artboard — Style Reference
> Warm digital canvas

**Theme:** light

Artboard's design system evokes a digital canvas with a subtle, inviting warmth. It pairs crisp, authoritative typography with soft, rounded UI elements, creating a friendly yet professional feel for creative tools. Subtle background tints create visual segmentation and a sense of 'depth' for product showcases, while a clear dark accent color grounds text and interactive elements. The overall aesthetic is one of clean functionality combined with a welcoming, artisanal touch.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, default card surfaces, text on dark elements |
| Forest Ink | `#0d1400` | `--color-forest-ink` | Primary text, headings, button backgrounds, interactive element borders, strong contrast against light backgrounds |
| Dune Beige | `#ffe4c3` | `--color-dune-beige` | Accent card backgrounds, subtle section demarcation |
| Sky Tint | `#cbedff` | `--color-sky-tint` | Accent card backgrounds, subtle section demarcation |
| Mint Leaf | `#caf3aa` | `--color-mint-leaf` | Accent card backgrounds, subtle section demarcation |
| Sage Whisper | `#838976` | `--color-sage-whisper` | Muted secondary text, badge text, subtle icon strokes, hairline borders |
| Artboard Green | `#aaff00` | `--color-artboard-green` | Icon backgrounds, decorative highlights |

## Tokens — Typography

### system-ui — Body text, links, buttons, and navigation elements. Its neutrality provides a stable baseline for UI components. · `--font-system-ui`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 16px
- **Line height:** 1.00, 1.50
- **Letter spacing:** 0.031em
- **Role:** Body text, links, buttons, and navigation elements. Its neutrality provides a stable baseline for UI components.

### Vend Sans — Headlines and badges. Features tight tracking at larger sizes (-0.033em at 61px) for a compact, impactful appearance, contrasting with positive letter-spacing for smaller badge elements. · `--font-vend-sans`
- **Substitute:** ui-sans-serif, Noto Sans, system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 11px, 13px, 19px, 43px, 61px
- **Line height:** 1.20, 1.50
- **Letter spacing:** -0.033em, -0.023em, 0.039em, 0.045em
- **Role:** Headlines and badges. Features tight tracking at larger sizes (-0.033em at 61px) for a compact, impactful appearance, contrasting with positive letter-spacing for smaller badge elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 0.495px | `--text-caption` |
| body | 16px | 1.5 | 0.496px | `--text-body` |
| subheading | 19px | 1.2 | 0.741px | `--text-subheading` |
| heading | 43px | 1.2 | -0.989px | `--text-heading` |
| display | 61px | 1.2 | -2.013px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 8px |
| buttons | 8px |
| navItems | 8px |

### Layout

- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Primary Filled Button
**Role:** Main call-to-action button

Solid Forest Ink (#0d1400) background, Canvas White (#ffffff) text, 8px border-radius, 12px vertical and 24px horizontal padding. Prominent and direct.

### Ghost Button
**Role:** Secondary action button, text-based

Canvas White (#ffffff) background, Forest Ink (#0d1400) text, subtle 1px border using rgba(13, 20, 0, 0.1), 8px border-radius, 12px vertical and 24px horizontal padding. Lightweight and less intrusive.

### Standard Card
**Role:** Content container for mockups and features

Transparent background, 12px border-radius, no shadow. Content is paramount, cards serve as simple frames.

### Color-Tinte Card
**Role:** Promotional or featured content card

Varied subtle background colors (Dune Beige #ffe4c3, Sky Tint #cbedff, Mint Leaf #caf3aa), 12px border-radius. Features 24px vertical padding and 0px horizontal padding, promoting vertical content flow.

### Ghost Badge
**Role:** Informational tag for categories or features

Transparent background, Sage Whisper (#838976) text, 8px border-radius, 4px vertical and 8px horizontal padding. Subtly highlights keywords.

## Do's and Don'ts

### Do
- Use Forest Ink (#0d1400) for all primary headings and active states, ensuring strong readability on light backgrounds.
- Implement 12px border-radius for all content cards to maintain a soft, approachable feel.
- Utilize Dune Beige (#ffe4c3), Sky Tint (#cbedff), and Mint Leaf (#caf3aa) interchangeably for accent card backgrounds to add visual interest and segmentation.
- Apply Vend Sans typography for all display and headline text, leveraging its weighted tracking for impact.
- Maintain a clear visual hierarchy with subtle 1px border lines in rgba(13, 20, 0, 0.1) for ghost buttons and interactive element outlines.
- Keep components lightweight: prioritize transparent backgrounds and explicit borders over heavy shadows or filled panels for most UI elements.
- Ensure generous padding using the 4px base unit, specifically 12px vertically and 24px horizontally, for primary buttons to create clear interactive targets.

### Don't
- Avoid using harsh, saturated colors that deviate from the established muted and natural accent palette.
- Do not introduce strong drop shadows; rely on background color changes or subtle hairline borders for elevation and separation.
- Do not use generic system fonts for headlines; Vend Sans is crucial for the brand's distinctive typographic voice.
- Avoid tight spacing around interactive elements; always use the specified sectionGap and elementGap to give components breathing room.
- Do not deviate from the 8px and 12px border-radius values for buttons, badges, and cards respectively; consistency is key to the soft aesthetic.
- Refrain from using gradients on non-illustrative UI elements; the system relies on solid colors and subtle tinting for depth.
- Do not compromise on the color contrast between text and background, especially for Forest Ink (#0d1400) on light surfaces, which maintains AAA readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default neutral surface |
| 1 | Accent Card Surface | `#ffe4c3` | Alternating background for showcasing product categories or features |
| 1 | Accent Card Surface | `#cbedff` | Alternating background for showcasing product categories or features |
| 1 | Accent Card Surface | `#caf3aa` | Alternating background for showcasing product categories or features |

## Imagery

The imagery consists mainly of product mockups, featuring close-ups of digital devices, apparel, and print materials. These are treated as contained elements with soft 12px rounded corners, often presented against pure white or subtly tinted backgrounds that match the accent card colors. The mockups themselves are realistic, high-fidelity renders, emphasizing a professional and polished, yet approachable, output from the tool. Iconography (e.g., in badges) is subtle, using a muted Sage Whisper color and thin strokes, adding functional clarity without competing with the product visuals. The overall role is product showcase and explanatory content, with a high density of visual examples throughout the page.

## Layout

The page uses a maximum-width contained layout, though a `pageMaxWidth` value was not explicitly detected, the content appears centered with ample side margins. The hero section is full-width with a centered headline and description over a subtle beige background, followed by a band of ghost-style feature badges aligned centrally. Below this, content is arranged in multi-column grids (likely 3-column or 4-column) for displaying mockups, with alternating subtly tinted background colors between main sections. The navigation is a sticky top bar with a logo, centered menu items, and right-aligned actions, maintaining a clean and accessible header.

## Agent Prompt Guide

Quick Color Reference: 
text: #0d1400
background: #ffffff
border: rgba(13, 20, 0, 0.1) 
accent: #ffe4c3
primary action: #0d1400 (filled action)

Example Component Prompts:
Create a Primary Action Button: #0d1400 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a product showcase card: Tinted with Dune Beige (#ffe4c3) background. 12px radius, 24px vertical padding. Include a title at 19px Vend Sans weight 600, #0d1400, and a small ghost badge with Sage Whisper text (#838976), 8px radius, 4px 8px padding.

Create a navigation bar: Canvas White background. Nav links at 16px system-ui weight 400, #0d1400. Include a Primary Filled button with Forest Ink (#0d1400) background, Canvas White text, 8px radius, 12px 24px padding.

## Similar Brands

- **Placeit** — Offers a similar service with a clean UI focused on presenting product mockups, often using rounded cards and a subdued color palette.
- **Smartmockups** — Shares the emphasis on realistic product mockups and a user-friendly interface with clear, accessible navigation and calls to action.
- **Canva** — Provides a similar online editor experience for design, with a focus on simplicity, inviting visual style, and accessible tools for non-designers, reflected in soft shapes and clear typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-forest-ink: #0d1400;
  --color-dune-beige: #ffe4c3;
  --color-sky-tint: #cbedff;
  --color-mint-leaf: #caf3aa;
  --color-sage-whisper: #838976;
  --color-artboard-green: #aaff00;

  /* Typography — Font Families */
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-vend-sans: 'Vend Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.495px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.496px;
  --text-subheading: 19px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.741px;
  --text-heading: 43px;
  --leading-heading: 1.2;
  --tracking-heading: -0.989px;
  --text-display: 61px;
  --leading-display: 1.2;
  --tracking-display: -2.013px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 8px;
  --radius-buttons: 8px;
  --radius-navitems: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-accent-card-surface: #ffe4c3;
  --surface-accent-card-surface: #cbedff;
  --surface-accent-card-surface: #caf3aa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-forest-ink: #0d1400;
  --color-dune-beige: #ffe4c3;
  --color-sky-tint: #cbedff;
  --color-mint-leaf: #caf3aa;
  --color-sage-whisper: #838976;
  --color-artboard-green: #aaff00;

  /* Typography */
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-vend-sans: 'Vend Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.495px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.496px;
  --text-subheading: 19px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.741px;
  --text-heading: 43px;
  --leading-heading: 1.2;
  --tracking-heading: -0.989px;
  --text-display: 61px;
  --leading-display: 1.2;
  --tracking-display: -2.013px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
