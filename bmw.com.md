# BMW.com — Style Reference
> Precision-engineered monochrome luxury; every detail is intentional, nothing is superfluous.

**Theme:** light

This design system projects an image of understated luxury and precision, typical of a high-end automotive brand. The focus on a monochrome palette with sharp contrasts and subtle textural shifts creates a refined, almost clinical atmosphere. Typography is the primary visual differentiator, using a bespoke font that balances technical exactness with approachable forms, especially in larger display sizes where its clarity is paramount. There is minimal use of color, which emphasizes content and maintains a strong, consistent brand presence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#262626` | `--color-obsidian` | Primary text, interactive elements, navigation links, button text — forms the core dark against light contrast. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, prominent navigational elements — establishes the primary visual canvas. |
| Graphite Grey | `#bbbbbb` | `--color-graphite-grey` | Secondary navigation text, subtle borders, contextual information — provides sufficient contrast on dark surfaces while appearing subdued on light ones. |
| Frost | `#f1f1f1` | `--color-frost` | Subtle background accents, dividers — provides a very light contrast against Canvas White. |
| Deep Space | `#262626` | `--color-deep-space` | Footer background — anchors the page with a solid, dark foundation. |
| Electric Blue | `#1c69d4` | `--color-electric-blue` | Interactive highlights, focus states — a vibrant, technical accent for user interaction. |

## Tokens — Typography

### BMWTypeNextLatin — Body text, navigation, interactive elements, button labels, and general UI text. Its precise forms reflect the brand's engineering heritage, ensuring clarity across all contexts. · `--font-bmwtypenextlatin`
- **Substitute:** Open Sans
- **Weights:** 400, 700, 900
- **Sizes:** 16px, 18px
- **Line height:** 1.15, 1.20, 1.30, 1.60, 1.63
- **Letter spacing:** normal
- **Role:** Body text, navigation, interactive elements, button labels, and general UI text. Its precise forms reflect the brand's engineering heritage, ensuring clarity across all contexts.

### BMWTypeNextLatin Light — Primary display headlines; the light weight at large sizes conveys authority through refinement rather than aggression, creating a sophisticated brand voice. It's unexpected at this scale, establishing an elegant, high-impact presence. · `--font-bmwtypenextlatin-light`
- **Substitute:** Open Sans Light
- **Weights:** 300
- **Sizes:** 60px
- **Line height:** 1.30
- **Letter spacing:** normal
- **Role:** Primary display headlines; the light weight at large sizes conveys authority through refinement rather than aggression, creating a sophisticated brand voice. It's unexpected at this scale, establishing an elegant, high-impact presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.63 | — | `--text-body` |
| subheading | 18px | 1.6 | — | `--text-subheading` |
| display | 60px | 1.3 | — | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 0px |
| default | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Text Link Button
**Role:** Primary Call to Action

Ghost-style button with no background, Obsidian text (#262626), zero border radius, and minimal horizontal padding (12px). Emphasizes action through text rather than a contained shape.

### Navigation Link
**Role:** Primary Navigation

Text in Obsidian (#262626) by default, switching to Graphite Grey (#bbbbbb) in the footer. Line height of 1.63 and zero padding, relying on surrounding layout for spacing, with zero border radius.

### Heading Text Badge
**Role:** Section Labels

Descriptive text in Obsidian (#262626) with no background or borders, often used to introduce sections or categories with zero padding and border radius.

## Do's and Don'ts

### Do
- Prioritize BMWTypeNextLatin for all text elements to maintain brand consistency.
- Use Canvas White (#ffffff) as the dominant background color for main content areas.
- Apply Obsidian (#262626) for primary text and interactive elements to ensure high contrast.
- Utilize BMWTypeNextLatin Light weight 300 at 60px for prominent headings to create an impactful yet refined statement.
- Maintain zero border-radius on all components to preserve the precise, angular aesthetic.
- Employ Electric Blue (#1c69d4) sparingly for interactive highlights and focus states, ensuring it stands out against the monochrome palette.

### Don't
- Avoid using saturated or chromatic colors outside of the designated Electric Blue accent.
- Do not introduce rounded corners or soft shapes, as the aesthetic is defined by sharp precision.
- Refrain from heavy shadows or overt elevation a primary means of drawing attention; rely on typography and strong contrast.
- Do not deviate from the BMWTypeNextLatin font family; consistency is key to the brand's visual identity.
- Avoid excessive padding around interactive textual elements like links; use 0-12px as seen in button examples.

## Imagery

Imagery features high-quality product photography, often focusing on close-up detailed crops (like the wheel) or larger views of vehicles. The treatment is full-bleed or wide, contained within sections, without visible masks or rounded corners. Photography is often presented in a moody, low-key lighting style with distinct color casts (e.g., blue tints) rather than bright, high-key studio shots. The role of imagery is primarily decorative and aspirational, showcasing the product while also setting a sophisticated atmosphere. The site is image-heavy, relying on visuals to convey brand essence alongside concise textual information.

## Layout

The page structure is primarily max-width contained, but hero sections often utilize full-bleed photography. The main content areas tend to be centered. The hero uses a background image with text overlay, establishing an immediate brand impression. Section rhythm is clear, using a dominant white background for content with a distinct, dark footer (#262626) that grounds the page. Content is arranged in a fluid, stacked manner, often with large images followed by textual information, leading to multi-column layouts within the footer. The density is spacious, with significant white space around content, allowing elements to breathe. Navigation consists of a sticky top bar with branding and primary links, along with a comprehensive multi-column footer.

## Agent Prompt Guide

### Quick Color Reference
- Text: #262626 (Obsidian)
- Background: #ffffff (Canvas White)
- CTA/Highlight: #1c69d4 (Electric Blue)
- Border/Secondary: #bbbbbb (Graphite Grey)
- Footer Background: #262626 (Deep Space)

### Example Component Prompts
1. Create a page header: Canvas White (#ffffff) background. Left-aligned BMW logo. Right-aligned navigation link 'Home' in Obsidian (#262626), BMWTypeNextLatin weight 400, size 16px, line height 1.63. Include a search icon in Obsidian (#262626).
2. Design a primary headline section: BMWTypeNextLatin Light weight 300, size 60px, line height 1.3, Obsidian (#262626) text, centered, with 40px margin-top and 40px margin-bottom. Below, add a Text Link Button 'Find your BMW' in Obsidian (#262626), BMWTypeNextLatin weight 400, size 16px, 12px horizontal padding, 0px vertical padding, no background, 0px border radius.
3. Develop a footer section: Deep Space (#262626) background. Four columns of links with titles like 'Quick Links' as Heading Text Badge in Graphite Grey (#bbbbbb), BMWTypeNextLatin weight 700, size 16px. Individual links in Graphite Grey (#bbbbbb), BMWTypeNextLatin weight 400, size 16px, line height 1.63.

## Similar Brands

- **Audi** — High-end automotive, clean monochrome aesthetic with a focus on product visuals and sophisticated typography.
- **Mercedes-Benz** — Luxury brand website with a similar emphasis on impactful, large-scale imagery and a refined, understated UI.
- **Porsche** — Premium automotive with a precise, almost technical design language, using a bespoke font and minimal color palette.
- **Apple** — Product-focused, clean design with significant white space, strong typography, and high-quality photography as central brand elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #262626;
  --color-canvas-white: #ffffff;
  --color-graphite-grey: #bbbbbb;
  --color-frost: #f1f1f1;
  --color-deep-space: #262626;
  --color-electric-blue: #1c69d4;

  /* Typography — Font Families */
  --font-bmwtypenextlatin: 'BMWTypeNextLatin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bmwtypenextlatin-light: 'BMWTypeNextLatin Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.63;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --text-display: 60px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-buttons: 0px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #262626;
  --color-canvas-white: #ffffff;
  --color-graphite-grey: #bbbbbb;
  --color-frost: #f1f1f1;
  --color-deep-space: #262626;
  --color-electric-blue: #1c69d4;

  /* Typography */
  --font-bmwtypenextlatin: 'BMWTypeNextLatin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bmwtypenextlatin-light: 'BMWTypeNextLatin Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.63;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --text-display: 60px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-100: 100px;
}
```
