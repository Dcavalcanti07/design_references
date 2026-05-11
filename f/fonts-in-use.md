# Fonts In Use — Style Reference
> Typographic Archive on Vellum. A precise, ordered display of form and content, like a beautifully cataloged library of type specimens.

**Theme:** light

This design system presents as an academic archive: minimal, almost utilitarian, with a relentless focus on content. The stark monochrome palette of pure black and white emphasizes the typographic examples, with subtle gray surfaces providing structure without distraction. Custom fonts (BentonSansRE and RelayCond) lend a distinct, authoritative voice, reinforcing the site's role as a trusted resource. The tight spacing and modest 2px radius on interactive elements communicate efficiency and precision, prioritizing information delivery over decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#000000` | `--color-inkwell` | Primary text, headings, links, borders for content areas — establishes a strong, definitive presence against lighter backgrounds. |
| Canvas | `#ffffff` | `--color-canvas` | Page background, input fields, and elements requiring high contrast for readability. |
| Mist | `#f0f0f0` | `--color-mist` | Subtle background for list items, section separators, creating soft visual differentiation without breaking the monochrome theme. |
| Pewter | `#dddddd` | `--color-pewter` | Input borders, light dividers — a near-achromatic gray that provides soft definition. |
| Stone | `#cccccc` | `--color-stone` | Less prominent borders and inactive states. |
| Ash | `#999999` | `--color-ash` | Secondary text, placeholder text, disabled states on buttons — indicates less importance or interactivity. |
| Granite | `#b3b3b3` | `--color-granite` | Subtle box-shadows if applied, for a very restrained sense of elevation. |

## Tokens — Typography

### Benton Sans RE — The workhorse sans-serif for body text, links, headings, and navigation. Its condensed nature allows for dense information display, and the varying line heights indicate clear hierarchy in text blocks. · `--font-benton-sans-re`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 9px, 10px, 12px, 14px, 16px
- **Line height:** 1.10, 1.20, 1.60
- **Letter spacing:** normal
- **Role:** The workhorse sans-serif for body text, links, headings, and navigation. Its condensed nature allows for dense information display, and the varying line heights indicate clear hierarchy in text blocks.

### Relay Cond — Used for prominent page titles, navigation, and badges, its condensed, strong presence commands attention with an architectural feel against the more ubiquitous Benton Sans RE. · `--font-relay-cond`
- **Substitute:** Oswald
- **Weights:** 400, 700
- **Sizes:** 18px, 36px
- **Line height:** 1.00, 1.60
- **Letter spacing:** normal
- **Role:** Used for prominent page titles, navigation, and badges, its condensed, strong presence commands attention with an architectural feel against the more ubiquitous Benton Sans RE.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.1 | — | `--text-caption` |
| body | 14px | 1.6 | — | `--text-body` |
| body-lg | 16px | 1.6 | — | `--text-body-lg` |
| subheading | 18px | 1 | — | `--text-subheading` |
| heading | 36px | 1 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 123 | 123px | `--spacing-123` |
| 220 | 220px | `--spacing-220` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 2px |
| buttons | 2px |

### Layout

- **Page max-width:** 1180px
- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Interactive element

Solid Ash background (#999999), Canvas text (#ffffff), 2px border radius, with 5px vertical and 10px horizontal padding. Borders match the button itself.

### Default Input Field
**Role:** User input

Canvas background (#ffffff), Inkwell text (#000000), 2px border radius, with 0px vertical and 10px horizontal padding. Border is Pewter (#dddddd).

### Small Button
**Role:** Pagination/Navigation

Small, square buttons with a subtle 2px radius. Ash background (#999999), Canvas text (#ffffff), 5px vertical and 10px horizontal padding. Borders match button color.

### Staff Pick Badge
**Role:** Decorative/Informational Tag

Transparent background, Inkwell text (#000000), 0px border radius, 0px padding. Uses Relay Cond font at 18px and bold weight 700 to stand out.

## Do's and Don'ts

### Do
- Use Benton Sans RE for all body, paragraph, and standard heading text, varying weight between 400 and 700, and sizes between 10px and 16px to maintain a dense, readable content block.
- Apply Relay Cond exclusively for prominent headings, navigation items, and badges, utilizing its 18px and 36px sizes with weights 400 or 700 to create impact.
- Maintain a strict monochrome palette with Inkwell (#000000) for text, Canvas (#ffffff) for backgrounds, and Mist (#f0f0f0) for subtle section differentiation.
- Implement 2px border radii for all interactive elements like buttons and input fields to imply functionality without softness.
- Separate distinct content sections with a 30px vertical gap, fostering a structured yet compact layout.
- Use 5-10px element spacing to create visual separation between adjacent UI elements without appearing sparse.

### Don't
- Do not introduce chromatic colors outside the established monochrome and sponsor-driven accents for any UI elements; reserve color for content itself.
- Avoid large, rounded corners or fluid, organic shapes; maintain the precise, rectilinear aesthetic with maximum 2px radii.
- Do not use letter-spacing other than 'normal' for any text, as the custom fonts are designed for specific impact without alteration.
- Do not deviate from the established 5px vertical and 10px horizontal padding for buttons; consistency reinforces the utilitarian feel.
- Refrain from using prominent box-shadows or complex elevation patterns; subtle differentiation with gray backgrounds suffices for depth.

## Imagery

The site's visual language is dominated by the type specimens themselves, acting as the primary imagery. These are typically contained within a grid, often cropped, and showcasing diverse typographic applications. There are no lifestyle photos, illustrations, or 3D renders. Icons are minimal, usually simple arrows or abstract shapes for navigation. The focus is entirely on showcasing typography, and the images serve as direct examples, not decorative elements. They are displayed without additional masking or bespoke treatments, appearing to be raw, clear representations of their content.

## Layout

The page adheres to a max-width 1180px, centered layout. The hero section is minimal, primarily text-based with navigation. Content is presented in a dense, multi-column grid, featuring square or rectangular 'cards' each displaying a type example. This grid maintains consistent column gutters (20px column gap) and row spacing (30px marginBottom). Navigation is predominantly horizontal at the top, supplemented by a secondary filter bar. The overall rhythm emphasizes content density and visual cataloging, with sections divided by consistent vertical spacing rather than alternating backgrounds.

## Agent Prompt Guide

### Quick Color Reference
- Text: Inkwell (#000000)
- Background: Canvas (#ffffff)
- Button: Ash (#999999)
- Border (input): Pewter (#dddddd)
- Subtle Background: Mist (#f0f0f0)

### 3-5 Example Component Prompts
1. Create a `Primary Action Button` with the label 'Submit': Ash background (#999999), Canvas text (#ffffff), 2px border radius, 5px vertical padding, 10px horizontal padding, Benton Sans RE font weight 400, size 14px.
2. Create an `Input Field` component with placeholder 'Search...': Canvas background (#ffffff), Inkwell text (#000000), Pewter border (#dddddd), 2px border radius, 0px vertical padding, 10px horizontal padding, Benton Sans RE font size 14px.
3. Generate a `Staff Pick Badge` with the text 'Staff Pick': Transparent background, Inkwell text (#000000), 0px border radius, 0px padding, Relay Cond font weight 700, size 18px.
4. Design a `Gallery Item Card` placeholder, 200px by 200px. Below it, add a title 'Example Typeface': Text Inkwell (#000000), Benton Sans RE weight 700, size 16px, line height 1.2. Below that, 'Designer Name': Text Inkwell (#000000), Benton Sans RE weight 400, size 14px, line height 1.6. Use `elementGap` of 5px between title and designer name.

## Similar Brands

- **Typewolf** — Shares a strong emphasis on showcasing typography, using a clean, content-first layout with minimal decorative elements and a subdued color palette.
- **Wordmark.it** — Focuses on direct display of text in various fonts, prioritizing function over elaborate UI, similar to Fonts In Use's utilitarian approach.
- **The Brand Identity** — Exhibits a grid-based editorial layout for showcasing design work, favoring strong typography and a clean, spacious aesthetic to let the work speak for itself.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #000000;
  --color-canvas: #ffffff;
  --color-mist: #f0f0f0;
  --color-pewter: #dddddd;
  --color-stone: #cccccc;
  --color-ash: #999999;
  --color-granite: #b3b3b3;

  /* Typography — Font Families */
  --font-benton-sans-re: 'Benton Sans RE', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-relay-cond: 'Relay Cond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1;
  --text-heading: 36px;
  --leading-heading: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-123: 123px;
  --spacing-220: 220px;

  /* Layout */
  --page-max-width: 1180px;
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;

  /* Named Radii */
  --radius-inputs: 2px;
  --radius-buttons: 2px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #000000;
  --color-canvas: #ffffff;
  --color-mist: #f0f0f0;
  --color-pewter: #dddddd;
  --color-stone: #cccccc;
  --color-ash: #999999;
  --color-granite: #b3b3b3;

  /* Typography */
  --font-benton-sans-re: 'Benton Sans RE', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-relay-cond: 'Relay Cond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-body-lg: 16px;
  --leading-body-lg: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1;
  --text-heading: 36px;
  --leading-heading: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-123: 123px;
  --spacing-220: 220px;

  /* Border Radius */
  --radius-sm: 2px;
}
```
