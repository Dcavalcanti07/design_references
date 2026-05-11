# iconwerk — Style Reference
> Gallery of crisp forms

**Theme:** light

The iconwerk system is a minimalist black and white canvas for showcasing custom icon design. It prioritizes clarity and directness through a largely monochrome palette, sparse text, and a loose, airy layout. Visual interest comes from the high-contrast presentation of icons and the generous use of rounded rectangles, creating a playful, object-focused atmosphere. The overall impression is one of curated simplicity, allowing the icons themselves to be the main protagonists.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#000000` | `--color-ink-black` | Primary headings, body text, and icon fills on light surfaces. Do not promote it to the primary CTA color |

## Tokens — Typography

### Arial — System fallback for general text, links, and image captions. Provides a clean, unadorned baseline. · `--font-arial`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.21
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** System fallback for general text, links, and image captions. Provides a clean, unadorned baseline.

### Graphik — Headlines and prominent body text. Graphik's robust modern sans-serif character supports the direct and functional aesthetic. · `--font-graphik`
- **Substitute:** Inter, ui-sans-serif, system-ui
- **Weights:** 400, 600
- **Sizes:** 16px, 21px, 22px, 24px
- **Line height:** 1.18, 1.19, 1.21
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** Headlines and prominent body text. Graphik's robust modern sans-serif character supports the direct and functional aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.21 | — | `--text-body` |
| body-lg | 16px | 1.21 | — | `--text-body-lg` |
| subheading | 21px | 1.18 | — | `--text-subheading` |
| heading-lg | 24px | 1.21 | — | `--text-heading-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 36 | 36px | `--spacing-36` |
| 37 | 37px | `--spacing-37` |
| 44 | 44px | `--spacing-44` |
| 45 | 45px | `--spacing-45` |
| 61 | 61px | `--spacing-61` |
| 62 | 62px | `--spacing-62` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 28px |
| cards | 28px |
| buttons | 28px |

### Layout

- **Section gap:** 45px
- **Card padding:** 18px
- **Element gap:** 5px

## Components

### Icon Card
**Role:** Container for individual icon examples

Squared card with a large 28px border-radius, often filled with a #000000 background for contrast or a neutral white, housing a centered icon image or text. Padding varies but often around 18px.

### Contact Button
**Role:** Primary call to action.

Text-only button with Ink Black text, 28px border-radius applied to an underlying clickable area, with a subtle border for hover states (though not explicitly detected in static data, implied by general design). Padding around text is implied to be minimal to maintain a ghost aesthetic.

## Do's and Don'ts

### Do
- Prioritize extreme visual clarity with #000000 text and borders against white or near-white backgrounds.
- Apply a generous 28px border-radius consistently to all interactive elements, cards, and prominent shapes.
- Maintain ample whitespace; use 45px for vertical section separation and 5px as a base unit for smaller element spacing.
- Use Graphik (or Inter) for all headlines and emphasized text, leveraging weights 400 and 600.
- Employ `"liga"` font feature settings for Graphik to enable ligatures, enhancing typographic refinement.
- Keep chromatic elements to a minimum, using color only for specific icon examples or very deliberate brand accent in content areas.

### Don't
- Avoid using multiple colors for interface elements; stick to the monochrome palette for UI.
- Do not use sharp corners; the 28px radius is a signature visual element.
- Refrain from dense layouts; maintain a spacious feel with generous padding and margins.
- Do not introduce heavy shadows or complex elevation; the system relies on flat, high-contrast surfaces.
- Avoid decorative gradients for UI elements; their absence reinforces clarity.

## Imagery

The site's imagery is primarily product-focused, showcasing various icon designs and product integrations. It features tight crops of actual product hardware (like remote controls, ovens) or abstract scenes (landscapes, wood textures) serving as backgrounds for overlaid icons. Icons themselves are presented either as simple outlines (often #000000 or a specific accent color) on solid backgrounds, or integrated into realistic product mockups. The style is detailed and realistic for product depictions, while icons are clean and graphic, often monochromatic. Icon style leans towards outlined with a consistent stroke weight. Imagery is used to contextualize and demonstrate the icons' versatility rather than for decorative atmosphere.

## Layout

The page uses a full-bleed layout for its main content area, with elements often centered or aligned to a relatively subtle grid. The hero section is a simple introductory text block with a logo. The main content is composed of a prominent 2x2 or 3x2 grid of 'Icon Cards' that alternate between dark and light backgrounds, creating a checkerboard-like visual rhythm. Each card is self-contained. Vertical spacing between content blocks is generous, around 45px. Navigation consists of a minimal top-right floating 'contact' button with a subtle logo.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #FFFFFF (implied, not explicitly in data)
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a header: Top-aligned, minimal, containing the site logo (placeholder for now), and a 'contact' link. The link text is 'contact' in Ink Black, using 14px Arial, 28px border-radius on click area, ensuring the entire header remains visually light and unobtrusive.
2. Create an 'Icon Card': A square white surface with 28px border-radius. Center a placeholder icon (e.g., a simple 'X' shape) in Ink Black within this card. For a variant, display a similar card with an Ink Black fill and a white placeholder icon, maintaining the same 28px radius.

## Similar Brands

- **Linear** — Both use a minimalist, high-contrast monochrome design with subtle rounded corners and a focus on functional clarity.
- **Stripe** — Shares a clean, modern typographic approach and a spacious layout that emphasizes content over heavy UI chrome.
- **Figma** — Similar aesthetic of clean lines, functional typography, and a grid-based presentation, letting the visual assets speak for themselves.
- **Vercel** — Employs strong typography, a monochromatic base, and a focus on direct, uncluttered information delivery with minimal ornamentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #000000;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.21;
  --text-body-lg: 16px;
  --leading-body-lg: 1.21;
  --text-subheading: 21px;
  --leading-subheading: 1.18;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.21;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-37: 37px;
  --spacing-44: 44px;
  --spacing-45: 45px;
  --spacing-61: 61px;
  --spacing-62: 62px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 18px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-3xl: 28px;

  /* Named Radii */
  --radius-tags: 28px;
  --radius-cards: 28px;
  --radius-buttons: 28px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #000000;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.21;
  --text-body-lg: 16px;
  --leading-body-lg: 1.21;
  --text-subheading: 21px;
  --leading-subheading: 1.18;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.21;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-37: 37px;
  --spacing-44: 44px;
  --spacing-45: 45px;
  --spacing-61: 61px;
  --spacing-62: 62px;

  /* Border Radius */
  --radius-3xl: 28px;
}
```
