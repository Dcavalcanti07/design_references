# Ryan Stephen — Style Reference
> Gallery Grid on White Canvas

**Theme:** light

Ryan Stephen's design system evokes a clean, gallery-like presentation with a strong emphasis on content and minimal UI distraction. It utilizes a spacious, high-contrast monochrome palette to make imagery pop, ensuring the focus remains on the product designs showcased. Typography is understated and functional, blending into the background to support the visual work. Components are highly softened with generous corner radii, creating a friendly, approachable feel for an otherwise stark layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary content areas |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong borders, foundational UI elements that demand high contrast |
| Graphite Text | `#404040` | `--color-graphite-text` | Body text, secondary headings, providing a softer alternative to Ink Black without sacrificing readability |
| Ash Gray | `#8b8b94` | `--color-ash-gray` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |

## Tokens — Typography

### sans-serif — Descriptive labels, image captions, and detailed footer text, serving as the small-print element of the system. · `--font-sans-serif`
- **Substitute:** Arial, Helvetica, 'sans-serif'
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Descriptive labels, image captions, and detailed footer text, serving as the small-print element of the system.

### system-ui — Primary body text, link text, and short descriptions, offering clarity and a slightly robust presence in the UI. · `--font-system-ui`
- **Substitute:** Segoe UI, Roboto, Ubuntu, Cantarell, 'Noto Sans', sans-serif
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Primary body text, link text, and short descriptions, offering clarity and a slightly robust presence in the UI.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| images | 10px |
| components | 10px |

### Layout

- **Section gap:** 100px
- **Card padding:** 40px
- **Element gap:** 20px

## Components

### Profile Description Block
**Role:** Informational text block

A focused text block for personal or project descriptions. Text uses Graphite Text (#404040) at 16px/500 weight, with links using Ash Gray (#8b8b94) at the same size and weight. Contains no explicit padding but is isolated by surrounding spaces.

### Image Gallery Grid Item
**Role:** Displaying visual work

Individual square image containers within a grid layout. Each image has a 10px border-radius, giving it a soft, rounded appearance. Content within the grid item is an image, bordered implicitly by the grid spacing using a 15px gap (row and column).

### Interactive Link
**Role:** Navigational or actionable text

Text links rendered in Ash Gray (#8b8b94) at 16px/500 weight, primarily for secondary actions or related content. There is no explicit hover or active state specified in the data, implying a subtle interaction or reliance on browser defaults.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all large background areas to maintain a spacious, gallery-like feel.
- Use Ink Black (#000000) strictly for primary headings and critical UI elements where maximum contrast is essential, like primary text.
- Apply a consistent 10px border-radius to all image containers and card-like components to ensure a cohesive, softened aesthetic.
- Maintain a visual hierarchy where body text uses Graphite Text (#404040) for readability and softer links use Ash Gray (#8b8b94).
- Structure layouts with a generous 100px section gap for clear delineation between major content blocks, creating an airy feel.
- Employ a base element gap of 20px for consistent spacing between distinct UI components.
- Utilize 15px spacing for items within image grids or compact lists to keep related content visually grouped but distinct.

### Don't
- Do not introduce strong, saturated colors unless they are part of the image content itself; the UI must remain monochrome.
- Avoid sharp corners or square edges on any interactive or content card-like element; always adhere to the 10px radius.
- Do not deviate from the specified typography hierarchy; avoid using 12px for body content or 16px for captions.
- Do not overcrowd sections; preserve the spacious feel by respecting the 100px section gap.
- Avoid heavy borders or strong shadows; the design relies on stark white space and soft radii for definition.
- Do not use generic system font weights other than 400 or 500; the UI's subtle nature depends on these choices.
- Do not use bright or animated hover states for links; interactions should be understated or rely on browser defaults.

## Imagery

The site's imagery consists solely of product screenshots, often depicting hands interacting with phone-based interfaces. The treatment is primarily isolated shots, with little environmental context, putting the product UI itself at the forefront. There's an absence of photography or graphic illustrations, emphasizing actual design output. The role of imagery is demonstrative and portfolio-oriented, serving as the core content rather than decorative elements. The density is image-heavy, forming a dense, uniform grid that dominates the page.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000 
background: #ffffff 
border: #8b8b94 
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
Create a profile introduction: 16px system-ui weight 500, #404040 for body text; links in #8b8b94, 16px system-ui weight 500. Wrap the content in 40px padding. 
Create an image grid item: A square container for an image, with a 10px border-radius. Internally, the image fills the container. Grid items should be separated by 15px elementGap.
Create a ghost link: Text 'Link Text' in #8b8b94, 16px system-ui weight 500. This link is for secondary actions.

## Similar Brands

- **Are.na** — Grid-based presentation of visual content, emphasizing individual work pieces in a clean, minimalist layout with high contrast text.
- **Read.cv** — Focus on personal portfolios with high-contrast text and a clean, spacious canvas for work examples, often image-heavy.
- **Bēhance** — Portfolio site with a strong emphasis on image grids for showcasing design projects, minimal UI to let the work speak.
- **Figma's community pages** — Often uses light backgrounds and structured grids to present files or community content, with a similar understated typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #404040;
  --color-ash-gray: #8b8b94;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 40px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-images: 10px;
  --radius-components: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #404040;
  --color-ash-gray: #8b8b94;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;

  /* Spacing */
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-lg: 10px;
}
```
