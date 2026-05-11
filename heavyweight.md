# Heavyweight — Style Reference
> Type foundry catalog on stark white

**Theme:** light

Heavyweight Type embraces a stark, high-contrast aesthetic, juxtaposing crisp black text and borders against expansive white and light gray surfaces. Typography is the undisputed hero, presented in large, impactful custom fonts that demand attention without heavy graphic treatments. The system prioritizes functional clarity and precise visual hierarchy, with minimal use of color, reserving a single vivid green as a subtle 'new' flag, making interactions feel deliberate and highly legible.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Heavy Ink | `#222222` | `--color-heavy-ink` | Primary text, surface borders, general UI elements, active button background, interactive states — controls the overall dark and authoritative tone |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card backgrounds, text on dark buttons — provides a clean, expansive base layer |
| Surface Frost | `#f3f5fa` | `--color-surface-frost` | Secondary surface backgrounds, default button backgrounds — adds subtle depth while maintaining achromatic purity |
| Border Graphite | `#2d2d2d` | `--color-border-graphite` | Subtle borders, dividers, decorative fills — a slightly softer black for structural accents |
| Muted Ash | `#888888` | `--color-muted-ash` | Secondary text, descriptive meta-information, disabled states — offers a softer contrast for less prominent content |
| Accent Green | `#39d17f` | `--color-accent-green` | Green outline accent for tags, dividers, and focused UI edges |

## Tokens — Typography

### Nuckle website — Primary body text, navigation items, button labels — its custom design reinforces brand identity without being overly decorative. The slight positive letter-spacing at smaller sizes ensures legibility and a distinct 'digital' feel. · `--font-nuckle-website`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.14, 1.25
- **Letter spacing:** 0.013em for 14px, 0.014em for 16px
- **Role:** Primary body text, navigation items, button labels — its custom design reinforces brand identity without being overly decorative. The slight positive letter-spacing at smaller sizes ensures legibility and a distinct 'digital' feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.14 | 0.18px | `--text-body` |
| body-lg | 16px | 1.25 | 0.22px | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 30 | 30px | `--spacing-30` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 11px |

### Layout

- **Section gap:** 166px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Default Button
**Role:** Standard interactive element for general actions.

Background: Surface Frost (#f3f5fa). Text: Heavy Ink (#222222). Border: 1px solid Heavy Ink (#222222). Radius: 11px. Padding: 12px vertical, 18px horizontal. Font: Nuckle website (400), 16px, line-height 1.25.

### Primary Dark Button
**Role:** Emphasized action, often a confirmation or acceptance.

Background: Heavy Ink (#222222). Text: Canvas White (#ffffff). Border: 1px solid Canvas White (#ffffff). Radius: 10px. Padding: 7px vertical, 10px horizontal. This button has a slightly smaller radius and padding than the default.

### Outlined Light Button
**Role:** Alternative action, often used in conjunction with a primary dark button.

Background: Canvas White (#ffffff). Text: Heavy Ink (#222222). Border: 1px solid Heavy Ink (#222222). Radius: 10px. Padding: 7px vertical, 10px horizontal. This button has a slightly smaller radius and padding than the default.

### Font Showcase Card (Minimal)
**Role:** Displays font examples with minimal visual chrome.

Background: transparent. No boxShadow. Border radius: 0px. Internal vertical spacing: 4px. Text: Nuckle website, various weights and sizes depending on content. Padding: 0px.

### Font Showcase Card (Image Placeholder)
**Role:** Card with an explicit aspect ratio for image/video content (e.g., animated font previews).

Background: transparent. No boxShadow. Border radius: 11px (likely for a container within the card). Contains a large padding-bottom to enforce aspect ratio. Padding: 0px. Text: Nuckle website, various weights and sizes, often including Accent Green for 'New' tags.

### Navigation Link
**Role:** Top-level navigation items.

Text: Nuckle website (400 or 500 equivalent, 16px). Color: Heavy Ink (#222222). Hover state not explicitly defined but implied to be visually distinct. Padding: 5px vertical, 8px horizontal, with 2px right padding, and 23px or 166px right margin for spacing.

## Do's and Don'ts

### Do
- Use Heavy Ink (#222222) for all primary text and critical UI borders to maintain high contrast and legibility.
- Apply Surface Frost (#f3f5fa) as a default background for interactive components and secondary surfaces to create subtle visual separation.
- Utilize rounded corners with an 11px radius for cards and default buttons, and 10px for smaller buttons, to provide a consistent, tempered aesthetic.
- Employ the Nuckle website font at 16px with a line height of 1.25 for most body text and navigation, ensuring clear readability.
- Reserve Accent Green (#39d17f) exclusively for 'new' markers or similar functional highlights, keeping chromatic color sparse and impactful.
- Maintain generous element spacing of 12px and card padding of 12px for comfortable information density.
- Structure pages with a clear hierarchy using large custom type for headings and minimal decorative elements.

### Don't
- Do not introduce additional saturated colors; maintain the high-contrast achromatic base with Accent Green as the sole highlight.
- Avoid heavy drop shadows or intrusive gradients; rely on crisp borders and distinct surface colors for depth.
- Do not use overly dense layouts; leverage comfortable spacing tokens like `elementGap` (12px) to provide visual breathing room.
- Do not deviate from the specified font families; their custom nature is integral to the brand's identity.
- Do not use small, indistinct borders; prioritize strong, dark borders around interactive elements and cards for clarity.
- Avoid generic, full-bleed imagery without clear product context; imagery should be contained and purposeful.
- Do not use animations that distract; keep motion subtle (e.g., opacity, background-color transitions) to enhance interaction without overwhelming.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background, primary canvas for content |
| 2 | Surface Frost | `#f3f5fa` | Secondary background for card-like elements or interactive components, e.g., default buttons |
| 3 | Heavy Ink Surface | `#222222` | Darkest surface, used for high-contrast elements like selected button backgrounds or header sections to create visual impact |

## Imagery

Imagery largely consists of black-on-black or inverse graphic representations of typography, creating a high-contrast, artistic, and technical aesthetic. These are often contained within cards, sometimes with rounded corners (11px). When photography is used, it appears to be product-focused, showcasing the type in use in a stark, conceptual manner, rather than lifestyle. Icons are simple, outlined, and mostly monochromatic (Heavy Ink). The overall density is image-heavy in the font showcase sections, but the images serve as abstract examples of the typefaces themselves, rather than decorative elements. There are no full-bleed images, and all visuals are tightly integrated into the card structure.

## Layout

The page uses a maximum-width contained layout, approximately 1200px wide, with consistent large horizontal margins. The hero section often features a centered headline over a dark background, immediately emphasizing large typography. Content sections below the hero feature a responsive grid of cards, typically 3-4 columns, each showcasing a different font. Vertical section spacing is generous, with a `sectionGap` of 166px separating major content blocks. Navigation is a persistent top bar, horizontally aligned, with a standard set of links, cart, and account. Individual cards maintain their own internal padding and spacing for content. The visual rhythm is driven by the regular grid of cards against a large, uniform background.

## Agent Prompt Guide

### Quick Color Reference
text: #222222
background: #ffffff
border: #222222
accent: #39d17f
primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a default button with the label 'Submit'. Use Surface Frost (#f3f5fa) background, Heavy Ink (#222222) text and 1px border, Nuckle website font at 16px, 11px radius, and 12px vertical / 18px horizontal padding.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
3. Build a Font Showcase Card: transparent background, no border, no shadow, 0px radius. Inside, feature a large 'Animo' header in Heavy Ink (#222222), and a sub-label 'New' in Accent Green (#39d17f), with 4px vertical element gap between them.
4. Create a top navigation link for 'Projects'. Use Heavy Ink (#222222) Nuckle website font at 16px, with 5px vertical padding and 8px horizontal padding, and 23px right margin for spacing to the next element.

## Similar Brands

- **Pangram Pangram Foundry** — Shares a focus on showcasing custom typography with large text examples against minimal backgrounds and high-contrast color schemes.
- **Future Fonts** — Features a similar grid-based layout for font listings and a high-contrast textual presentation, with an emphasis on the typefaces themselves as the primary visual element.
- **Grilli Type** — Employs a stark, often monochrome palette with strong typographic emphasis and subtle UI animations, akin to Heavyweight's restrained yet impactful style.
- **Swiss Typefaces** — Known for clean, grid-based layouts and a strong focus on minimalist design with high-quality font presentation, using limited color to highlight details.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-heavy-ink: #222222;
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f3f5fa;
  --color-border-graphite: #2d2d2d;
  --color-muted-ash: #888888;
  --color-accent-green: #39d17f;

  /* Typography — Font Families */
  --font-nuckle-website: 'Nuckle website', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.14;
  --tracking-body: 0.18px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: 0.22px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-30: 30px;

  /* Layout */
  --section-gap: 166px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 11px;

  /* Named Radii */
  --radius-all: 11px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-surface-frost: #f3f5fa;
  --surface-heavy-ink-surface: #222222;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-heavy-ink: #222222;
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f3f5fa;
  --color-border-graphite: #2d2d2d;
  --color-muted-ash: #888888;
  --color-accent-green: #39d17f;

  /* Typography */
  --font-nuckle-website: 'Nuckle website', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.14;
  --tracking-body: 0.18px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: 0.22px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-30: 30px;

  /* Border Radius */
  --radius-lg: 11px;
}
```
