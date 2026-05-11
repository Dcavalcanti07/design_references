# Peggy — Style Reference
> Monochrome Gallery Wall

**Theme:** light

Peggy is a design system built on a monochrome palette with sharp contrasts and minimal embellishment. It employs a modern, sans-serif primary typeface for body text and a distinctive serif for headlines, creating a duality of contemporary clarity and artistic gravitas. Components are lightweight with strong outlines and often stark backgrounds, emphasizing content through a lack of decorative elements. The overall aesthetic is one of understated authority, reflecting a serious approach to the art market.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Fog | `#f4f4f4` | `--color-canvas-fog` | Page backgrounds, subtle borders, navigation dividers, content section backgrounds |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong headings, critical information, header elements |
| White Canvas | `#ffffff` | `--color-white-canvas` | Card backgrounds, selected button backgrounds, prominent surfaces |
| Deep Graphite | `#141414` | `--color-deep-graphite` | Darker background accents, text on light buttons, selected interactive states |
| Muted Ash | `#e2e8f0` | `--color-muted-ash` | Secondary text, subtle decorative elements, helper text |
| Soft Stone | `#666666` | `--color-soft-stone` | Muted text, tertiary information, less emphasized links |

## Tokens — Typography

### Inter — Primary UI text, body copy, navigation items, button labels. Its clean, utilitarian nature supports information clarity throughout the interface. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.50
- **Role:** Primary UI text, body copy, navigation items, button labels. Its clean, utilitarian nature supports information clarity throughout the interface.

### Reckless — Headlines and prominent display text. Its distinct serif form and lighter weights (especially 300) provide an artistic, contemplative voice, differentiating key messages from functional UI. · `--font-reckless`
- **Substitute:** Playfair Display, serif
- **Weights:** 300, 400
- **Sizes:** 20px, 30px, 36px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.20, 1.40
- **Role:** Headlines and prominent display text. Its distinct serif form and lighter weights (especially 300) provide an artistic, contemplative voice, differentiating key messages from functional UI.

### Monument Grotesk — Fine print, footer links, and minor legal text. Its compact, slightly condensed structure delivers information efficiently without demanding attention. · `--font-monument-grotesk`
- **Substitute:** Chivo, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.33
- **Role:** Fine print, footer links, and minor legal text. Its compact, slightly condensed structure delivers information efficiently without demanding attention.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 30px | 1.11 | — | `--text-heading` |
| heading-lg | 36px | 1.2 | — | `--text-heading-lg` |
| display | 48px | 1 | — | `--text-display` |
| display-lg | 60px | 1 | — | `--text-display-lg` |

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
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 168 | 168px | `--spacing-168` |

### Border Radius

| Element | Value |
|---------|-------|
| images | 9999px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Action button with a subtle outline, used for secondary actions or links where emphasis isn't on a filled background.

Background: rgba(0, 0, 0, 0), Text: #666666, Border: #f4f4f4, Radius: 0px, Padding: 0px.

### Filled Primary Button
**Role:** High-emphasis action button with a dark background, indicating primary actions like 'Join Peggy' or 'Download'.

Background: #141414, Text: #ffffff, Border: #f4f4f4, Radius: 0px, Padding: 16px.

### Light Filled Button
**Role:** Action button with a light background for contexts requiring less visual weight, such as within dark backgrounds or for less critical actions.

Background: #ffffff, Text: #141414, Border: #f4f4f4, Radius: 0px, Padding: 20px 40px.

### Simple Card
**Role:** Used for informational display, feature lists, and content grouping. Emphasizes clean content presentation.

Background: rgba(0, 0, 0, 0), Borders: none, Shadows: none, Radius: 0px, Padding: 0px 16px.

### App Download Banner
**Role:** Prominent notification bar for app download. Uses stark black and white for clear call to action.

Background: #141414, Text: #ffffff, Icon-fill: #ffffff, Border: none, Height: 80px.

## Do's and Don'ts

### Do
- Prioritize Inter for all body text, UI elements, and supplementary information for clear readability, using weights 400 and 500.
- Utilize Reckless for all headings, subheadings, and display text, explicitly using weights 300 and 400 to convey a distinctive artistic voice.
- Maintain a strict monochrome palette (#f4f4f4, #000000, #ffffff, #141414, #e2e8f0, #666666) for all UI elements, reserving color only for embedded imagery.
- Apply 0px border-radius to all structural components like buttons, cards, and sections, unless the element is an image with 9999px radius.
- Implement a 1px solid #f4f4f4 border for visual separation of UI elements, such as in navigation or list items.
- Use 16px for `elementGap` to ensure consistent spacing between small interactive elements and text blocks.
- Employ a base `sectionGap` of 32px to create distinct visual breaks between major content blocks.

### Don't
- Avoid introducing any additional chromatic colors into the UI; strictly adhere to the defined monochrome palette.
- Do not use box shadows or elevation effects on cards or panels, maintaining a flat, two-dimensional aesthetic.
- Do not deviate from the 0px border-radius unless specifically applied to images where 9999px (a full circle/pill shape) is required.
- Never use generic sans-serif fonts for headlines; the distinct character of Reckless is essential for brand identity.
- Do not vary line heights outside of the specified values for each typeface; maintain the established vertical rhythm.
- Avoid dense placement of elements; ensure ample use of whitespace, guided by the defined spacing tokens.
- Do not use outline styles on primary action buttons; use distinct background and text colors to convey hierarchy.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Fog | `#f4f4f4` | Dominant page background, low-prominence background areas for sections and dividers. |
| 1 | White Canvas | `#ffffff` | Primary content surfaces like cards, modal backgrounds, and interactive element fills (e.g., light buttons). |
| 2 | Deep Graphite | `#141414` | Accent backgrounds for high-contrast elements such as specific buttons or banner notifications. |

## Imagery

Imagery primarily consists of high-quality product photography (artwork) and atmospheric, often abstract or architectural photographs presented within the content. Photography is generally light-filled and high-key. Icons are monochrome, outlined, and minimal, serving purely functional roles. Product imagery (artworks) often has soft, rounded corners (9999px) for a subtle visual break, but UI elements typically maintain sharp edges. Imagery serves both as decorative atmosphere and explanatory content, illustrating how art interacts with the platform without heavy visual clutter. Density is moderate, balancing large hero images with text-heavy explanatory sections.

## Layout

The page primarily uses a max-width contained layout of 1280px, centered on a light (Canvas Fog) background. The hero section often features a split layout, with a large Reckless headline and Inter body text on one side, and a compelling image or artwork on the other. Sections maintain a consistent vertical rhythm, with clear visual breaks created by the sectionGap. Content organization moves between centered stacks for headings and text, and multi-column grids (like the four-column feature section) for presenting information. Navigation is a minimalist top bar, sticky only for the main logo and 'Join Peggy' button, contrasting with a dark ephemeral alert bar.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #f4f4f4
border: #f4f4f4
accent: no distinct accent color
primary action: no distinct CTA color

**3-5 Example Component Prompts**
1. Create a hero section: Canvas Fog background, with a prominent headline using Reckless weight 300, size 48px, color #000000. Below the headline, include body text in Inter weight 400, size 16px, color #000000. To the right, display an image with a 9999px border-radius.
2. Build a dark app download banner: Deep Graphite background, text 'Download the Peggy App' in Inter weight 400, size 16px, color #ffffff. Include a 'Download Peggy' button with White Canvas background, Deep Graphite text, 0px radius, and 20px 40px padding.
3. Design a feature card: White Canvas background, containing an icon (fill color #000000), a heading 'Secure Payments' in Inter weight 500, size 16px, color #000000, and a small description in Inter weight 400, size 14px, color #666666. No borders or shadows, 16px cardPadding.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Artsy** — Focus on art and artists with a clean, gallery-like aesthetic and sophisticated typography.
- **Saatchi Art** — Prominent display of artwork within a structured, often monochrome digital environment.
- **Square** — Understated visual design, strong typographic hierarchy, and a focus on clean, functional UI elements.
- **MasterClass** — Dramatic use of typography for headlines with a clean, light page structure for content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-fog: #f4f4f4;
  --color-midnight-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-deep-graphite: #141414;
  --color-muted-ash: #e2e8f0;
  --color-soft-stone: #666666;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-grotesk: 'Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 30px;
  --leading-heading: 1.11;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1;
  --text-display-lg: 60px;
  --leading-display-lg: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-168: 168px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-images: 9999px;

  /* Surfaces */
  --surface-canvas-fog: #f4f4f4;
  --surface-white-canvas: #ffffff;
  --surface-deep-graphite: #141414;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-fog: #f4f4f4;
  --color-midnight-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-deep-graphite: #141414;
  --color-muted-ash: #e2e8f0;
  --color-soft-stone: #666666;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-grotesk: 'Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 30px;
  --leading-heading: 1.11;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1;
  --text-display-lg: 60px;
  --leading-display-lg: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-168: 168px;

  /* Border Radius */
  --radius-full: 9999px;
}
```
