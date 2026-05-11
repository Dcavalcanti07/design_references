# 14islands — Style Reference
> Editorial Minimal Canvas — Large, impactful typography commands attention against vast, light-gray expanses.

**Theme:** light

This design system evokes the precision of a high-end editorial layout, prioritizing clear information delivery over decorative elements. The interplay of stark `#070707` text against expansive `#F2F2F2` backgrounds creates a powerful, almost architectural contrast, while the strategic use of `--color-grey-highlight-light` (`#a2a2a9`) provides subtle visual breaks that maintain gravity. Typography drives the aesthetic, with custom fonts `AftenScreen` delivering impactful, tightly kerned headlines and `BentonSans` ensuring legible, understated body copy, resulting in a system that feels both modern and timeless.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f2f2f2` | `--color-canvas-white` | Primary page background, neutral surfaces. Provides a clean, bright stage for content. |
| Deep Graphite | `#070707` | `--color-deep-graphite` | Primary text, headings, icons, actionable element borders. Serves as the dominant dark element for strong contrast. |
| Off White | `#ffffff` | `--color-off-white` | Used sparingly for specific background elements within content areas. Acts as a subtle variation to Canvas White. |
| Soft Gray Highlight | `#a2a2a9` | `--color-soft-gray-highlight` | Secondary text, subtle borders, inactive states, and highlights. Offers a toned-down visual alternative to Deep Graphite. |
| Medium Gray Highlight | `#797979` | `--color-medium-gray-highlight` | Tertiary text, less prominent information. Provides a slightly darker, more readable alternative to Soft Gray Highlight for smaller text. |

## Tokens — Typography

### AftenScreen — Display and large headlines. Its custom, wide letterforms and negative letter-spacing create a distinctive, impactful cadence, making large text feel like design elements themselves. · `--font-aftenscreen`
- **Substitute:** Open Sans, Montserrat
- **Weights:** 400
- **Sizes:** 27px, 75px, 100px, 180px
- **Line height:** 0.80, 1.00, 1.30
- **Letter spacing:** -0.05em at 180px, -0.04em at 100px
- **Role:** Display and large headlines. Its custom, wide letterforms and negative letter-spacing create a distinctive, impactful cadence, making large text feel like design elements themselves.

### BentonSans — Body copy, navigation, small headlines, and functional text. A workhorse font that ensures readability without visual fuss, supporting the dramatic headlines. · `--font-bentonsans`
- **Substitute:** Inter, Lato
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.20, 1.40
- **Letter spacing:** normal
- **Role:** Body copy, navigation, small headlines, and functional text. A workhorse font that ensures readability without visual fuss, supporting the dramatic headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 16px | 1.4 | — | `--text-body` |
| heading-sm | 27px | 1.3 | — | `--text-heading-sm` |
| heading | 75px | 1 | -0.04px | `--text-heading` |
| heading-lg | 100px | 1 | -0.04px | `--text-heading-lg` |
| display | 180px | 0.8 | -0.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 20 | 20px | `--spacing-20` |
| 100 | 100px | `--spacing-100` |
| 108 | 108px | `--spacing-108` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 4.16667px |

### Layout

- **Card padding:** 21px

## Components

### Text Link - Primary
**Role:** Interactive element, navigation links, inline text links

Plain text link in Deep Graphite (#070707) with no background or padding, emphasizing the content's editorial tone. Underline appears on hover/active states, matching text color. Typographic details match BentonSans 16px, 1.4 line height, normal letter spacing.

### Text Link - Secondary
**Role:** Interactive element, secondary navigation links, subtle buttons

Plain text link in Soft Gray Highlight (#a2a2a9) with no background or padding. Used for less prominent interactive elements. Typographic details match BentonSans 16px, 1.4 line height, normal letter spacing.

### Minimal Button - Active
**Role:** Primary action button, selected state button

A button with Deep Graphite (#070707) text and a matching border, without background or padding. Essentially a text link with an implicit clickable area. Typographic details match BentonSans 400.

### Minimal Button - Inactive/Secondary
**Role:** Secondary action button, unselected state button

A button with Soft Gray Highlight (#a2a2a9) text and a matching border, without background or padding. Used for less emphasized actions. Typographic details match BentonSans 400.

### Section Heading
**Role:** Primary headings for content sections

Deep Graphite (#070707) text set in AftenScreen 180px, 0.8 line height, and -0.05em letter spacing. The dramatic scale and tight kerning are a signature brand element.

### Inline Text Highlight
**Role:** Highlighting specific words or phrases.

A segment of text in Medium Gray Highlight (#a2a2a9) within a Deep Graphite (#070707) string, typically using AftenScreen 75px, 1.0 line height, and -0.04em letter spacing. Used for visual variations within display text, like the '&' operator.

### Body Text Paragraph
**Role:** Standard body copy for detailed information.

Paragraphs are set in BentonSans 16px, 1.4 line height, normal letter spacing, and Deep Graphite (#070707) color. Clear and legible for extended reading.

## Do's and Don'ts

### Do
- Prioritize `Canvas White` (`#f2f2f2`) as the main background for content areas and `Deep Graphite` (`#070707`) for all primary text, ensuring visual clarity and impact.
- Use `AftenScreen` at its largest sizes (75px, 100px, 180px) with negative letter-spacing for all hero and section headlines to create dramatic visual tension.
- Employ `BentonSans` at 16px weight 400 with a 1.4 line height for all body copy and secondary informational text to maintain high readability.
- Introduce `Soft Gray Highlight` (`#a2a2a9`) for secondary text elements or visual accents, especially for subheadings or subtle distinctions.
- Apply a consistent `4.16667px` border-radius to all image containers and interactive elements, avoiding sharp corners while still maintaining a structured feel.
- Maintain generous vertical spacing between sections, using values around `100px` to `108px` to ensure content breathes.
- Ensure interactive elements (buttons, links) are either `Deep Graphite` (`#070707`) or `Soft Gray Highlight` (`#a2a2a9`) with no background, relying on text and subtle borders for indication.

### Don't
- Avoid using background colors other than `Canvas White` (`#f2f2f2`) or `Off White` (`#ffffff`) for primary content sections.
- Do not introduce highly saturated or vivid chromatic colors; adhere strictly to the established neutral palette.
- Refrain from using strong box-shadows or complex elevation effects; the design relies on spacing and typography for hierarchy.
- Do not deviate from the specified negative letter-spacing for `AftenScreen` headlines, as this is a core part of its visual identity.
- Avoid pill-shaped or overly rounded elements; the standard `4.16667px` radius should be used consistently.
- Do not use generic system fonts; always specify `BentonSans` or `AftenScreen` (or their approved substitutes) for all text.
- Do not add additional padding or background styles to the 'Minimal Button' components; their design is intentionally understated.

## Imagery

The site uses a mix of high-quality, professional photography and product screenshots. Photography is typically studio-shot, often with muted backgrounds or a focus on the subject. Images are contained, not full-bleed, usually presented in rectangular frames with a subtle `4.16667px` border-radius. In some cases, illustrations or abstract graphics for product showcases are used, often demonstrating clean lines and a somewhat flat aesthetic. Imagery plays an explanatory and showcase role, breaking up text-heavy sections and visually presenting work examples, maintaining a balanced density between visuals and text.

## Layout

The page primarily uses a full-bleed pattern for its background colors (Canvas White), but content within these sections is constrained to a central max-width viewport (implicitly present, though not explicitly defined by a max-width token). The hero section features a large, centered headline over a dark background section, establishing a strong typographic focal point. Sections are clearly delineated by generous vertical spacing (`100px` to `108px`) and sometimes by subtle background color changes (e.g., `#f2f2f2` to a darker block). Content arrangement frequently uses a text-left, image-right or vice-versa alternating pattern, and showcases work in a clean grid-like structure (e.g., 2-column image grid). The navigation is a minimalist top bar, likely sticky, with spaced-out text links.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#070707`
- Background: `#f2f2f2`
- Secondary Text/Highlight: `#a2a2a9`
- Default Border: `#070707`
- Background Alternative: `#ffffff`

### 3-5 Example Component Prompts
1. **Create a hero section:** Set the background to `Deep Graphite` (`#070707`). Center the text. The main headline is 'Design & Technology', with 'Design' and 'Technology' in `AftenScreen` 180px, `Deep Graphite`, `0.8` line height, and `-0.05em` letter spacing. The '&' symbol should be `Soft Gray Highlight` (`#a2a2a9`), `AftenScreen` 75px, `0.8` line height, and `-0.05em` letter spacing. Below, add a subheadline 'Creative agency' in `BentonSans` 16px, `Soft Gray Highlight`, `1.4` line height, normal letter spacing, aligned center.
2. **Generate a content section with alternating layout:** Set the background to `Canvas White` (`#f2f2f2`). Create two columns. Left column: a `Medium Gray Highlight` (`#797979`) text block in `BentonSans` 16px, 1.4 line height, normal letter spacing, with padding `21px`. Right column: a product screenshot with `4.16667px` border-radius.
3. **Design a call-to-action button:** Create a 'Learn More' button with `Deep Graphite` (`#070707`) text on an `rgba(0, 0, 0, 0)` background, and a `Deep Graphite` (`#070707`) border, no padding. The font should be `BentonSans` 16px, 400 weight. Use a focus state with a slightly darker `#070707` border. No border-radius on the element itself, but make sure the content inside respects the overall aesthetic.
4. **Build a navigation bar:** Create a horizontal navigation with `BentonSans` 16px, 400 weight links in `Deep Graphite` (`#070707`). The links should have `normal` letter spacing and no background or padding. Space items with `25px` `margin-right`. Include a logo (text-based '14islands') on the far left, using `BentonSans` 16px at `Deep Graphite`, and 'Contact' on the far right.

## Similar Brands

- **AIGA** — Shares a heavy reliance on typography as primary visual element against a clean, uncluttered background, often using large, impactful titles.
- **Work & Company** — Exhibits a similar high-contrast, editorial aesthetic with generous white space and sharp type treatment for a sophisticated, professional feel.
- **Büro Union** — Employs an austere, almost monochromatic palette with strong emphasis on type hierarchy and negative space to convey authority and precision.
- **Sagmeister & Walsh (old site)** — Features bold, experimental typographic layouts with stark color contrasts and limited visual clutter, making text the hero.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f2f2f2;
  --color-deep-graphite: #070707;
  --color-off-white: #ffffff;
  --color-soft-gray-highlight: #a2a2a9;
  --color-medium-gray-highlight: #797979;

  /* Typography — Font Families */
  --font-aftenscreen: 'AftenScreen', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bentonsans: 'BentonSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.3;
  --text-heading: 75px;
  --leading-heading: 1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 100px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 180px;
  --leading-display: 0.8;
  --tracking-display: -0.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-20: 20px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-160: 160px;

  /* Layout */
  --card-padding: 21px;

  /* Border Radius */
  --radius-md: 4.16667px;

  /* Named Radii */
  --radius-default: 4.16667px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f2f2f2;
  --color-deep-graphite: #070707;
  --color-off-white: #ffffff;
  --color-soft-gray-highlight: #a2a2a9;
  --color-medium-gray-highlight: #797979;

  /* Typography */
  --font-aftenscreen: 'AftenScreen', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bentonsans: 'BentonSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.3;
  --text-heading: 75px;
  --leading-heading: 1;
  --tracking-heading: -0.04px;
  --text-heading-lg: 100px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 180px;
  --leading-display: 0.8;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-20: 20px;
  --spacing-100: 100px;
  --spacing-108: 108px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4.16667px;
}
```
