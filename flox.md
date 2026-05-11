# Flox — Style Reference
> monochromatic console, sharp violet accents

**Theme:** light

Flox employs a 'developer console meets clean document' aesthetic, using crisp achromatic surfaces as a backdrop for highly functional, compact UI elements. Typography is precise and monospace where appropriate, creating a sense of technical clarity. Subtle gradients and vivid violet accents are used sparingly to highlight interactive elements and key brand messaging, while elevation remains minimal, suggesting speed and lightness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#020817` | `--color-midnight-ink` | Primary text, heading text, iconography, active navigation items. Establishes a strong, legible presence against light backgrounds |
| Snow White | `#ffffff` | `--color-snow-white` | Page backgrounds, card surfaces. Provides a clean, bright canvas for content |
| Slate Gray | `#e2e8f0` | `--color-slate-gray` | Hairline borders, dividers, subtle inactive states. Creates visual separation without harshness |
| Anthracite | `#1b1b1b` | `--color-anthracite` | Secondary text, button text on dark backgrounds. A slightly softer contrast than Midnight Ink |
| Light Fog | `#f3f3f3` | `--color-light-fog` | Subtle background for UI elements, light button borders. Provides differentiation between surface levels |
| Obsidian Black | `#0c0c0c` | `--color-obsidian-black` | Primary action button background. Creates a high-contrast, clickable target |
| Electric Violet | `#711aff` | `--color-electric-violet` | Accent for key branding, highlighted text in headlines, decorative elements. Provides a vibrant and energetic pop of color |
| Vivid Rose | `#ff4fae` | `--color-vivid-rose` | Decorative highlights, code syntax highlighting, secondary accents. Complements Electric Violet |
| Violet Gradient A | `linear-gradient(92deg, rgb(130, 71, 255) -9.21%, rgb(244, 123, 255) 104.14%)` | `--color-violet-gradient-a` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Violet Gradient B | `linear-gradient(95deg, rgb(255, 114, 207) -13.39%, rgb(138, 21, 255) 114.46%)` | `--color-violet-gradient-b` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### GeistSans — Primary typeface for all UI text, headings, and body copy. Its compact letter spacing ensures a modern, technical feel at larger sizes while maintaining readability at small sizes. · `--font-geistsans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 76px
- **Line height:** 1.00, 1.10, 1.20, 1.33, 1.35, 1.50
- **Letter spacing:** -0.0460em at 76px, -0.0200em at 24px, -0.0120em at 18px, -0.0110em at 16px, -0.0100em at 14px
- **Role:** Primary typeface for all UI text, headings, and body copy. Its compact letter spacing ensures a modern, technical feel at larger sizes while maintaining readability at small sizes.

### GeistMono — Used for code snippets, terminal commands, and technical references. It provides a precise, fixed-width character that reinforces the developer-focused nature of the product. · `--font-geistmono`
- **Substitute:** Fira Code
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** -0.0140em
- **Role:** Used for code snippets, terminal commands, and technical references. It provides a precise, fixed-width character that reinforces the developer-focused nature of the product.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.12px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.14px | `--text-body-sm` |
| body | 16px | 1.5 | -0.176px | `--text-body` |
| subheading | 18px | 1.35 | -0.216px | `--text-subheading` |
| heading | 24px | 1.33 | -0.48px | `--text-heading` |
| display | 76px | 1 | -3.496px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 12px |
| inputs | 6px |
| buttons | 6px |
| navItems | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.2) 0px -2px 1px 0px inset, rgba(255...` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.04) 0px 2px 8px 0px, rgba(0, 0, 0, 0.08) ...` | `--shadow-sm` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 4px

## Components

### Ghost Button
**Role:** Secondary actions, navigation links, and subtle interactive elements.

Transparent background, Midnight Ink text (#020817), Slate Gray border (#e2e8f0), 6px border-radius, with 4px vertical and 6px horizontal padding. On hover, the text darkens slightly or a subtle background appears.

### Outline Ghost Button
**Role:** Secondary navigation items, links with subtle visual weight.

Transparent background, Anthracite text (#1b1b1b), Light Fog border (#f3f3f3), 12px border-radius, with 12px vertical and 25px horizontal padding.

### Primary Action Button
**Role:** Main calls-to-action.

Obsidian Black background (#0c0c0c), Snow White text (#ffffff), Light Fog border (#f3f3f3), 12px border-radius, with 12px vertical and 25px horizontal padding.

### Gradient Call-to-Action Button
**Role:** Prominent, high-priority calls-to-action.

Background uses 'Violet Gradient A' (linear-gradient(92deg, rgb(130, 71, 255) -9.21%, rgb(244, 123, 255) 104.14%)), Snow White text (#ffffff), 12px border-radius, with 12px vertical and 25px horizontal padding.

### Elevated Card
**Role:** Content containers requiring visual emphasis or separation.

Snow White background (#ffffff), 12px border-radius, with 24px padding on all sides. Features a soft, layered shadow: rgba(0, 0, 0, 0.04) 0px 2px 8px, rgba(0, 0, 0, 0.08) 0px 8px 24px, rgba(0, 0, 0, 0.12) 0px 16px 48px.

### Code Block Card
**Role:** Displays code snippets or terminal output.

Snow White background (#ffffff), 12px border-radius, with 24px padding. Uses the same subtle, layered shadow as Elevated Card. Text uses GeistMono font.

### Bordered List Item
**Role:** Used for structured lists or feature descriptions.

Transparent background, defined by clear borders of Slate Gray (#e2e8f0) between items. Text is Midnight Ink (#020817).

## Do's and Don'ts

### Do
- Use Midnight Ink (#020817) for all primary body text, headlines, and key UI elements to ensure high contrast.
- Employ Snow White (#ffffff) as the default background for all page sections and elevated component surfaces.
- Apply Slate Gray (#e2e8f0) for all hairline borders and subtle dividers to create visual separation without heavy lines.
- Reserve Electric Violet (#711aff) and its associated gradients (Violet Gradient A) for key interactive elements, brand accents, and prominent calls to action.
- Maintain consistent letter spacing as defined in the GeistSans typography scale, especially for headlines, to preserve the system's precise and compact feel.
- Utilize 12px border-radius for cards and primary action buttons, 6px for smaller buttons and navigation items, ensuring a consistent soft corner aesthetic.
- Apply the full layered shadow (rgba(0, 0, 0, 0.04) 0px 2px 8px, rgba(0, 0, 0, 0.08) 0px 8px 24px, rgba(0, 0, 0, 0.12) 0px 16px 48px) only to significant elevated elements like cards or modals.

### Don't
- Avoid using highly saturated colors for large background areas or extensive text blocks; keep the canvas predominantly achromatic.
- Do not deviate from the defined GeistSans and GeistMono font families or their specified weights and letter spacing.
- Do not use generic box-shadows; adhere strictly to the two defined shadow styles for cards and buttons.
- Do not cluster interactive elements too closely; ensure a minimum elementGap of 4px and cardPadding of 24px.
- Do not introduce new border-radius values; stick to the 6px and 12px radii.
- Do not use Electric Violet (#711aff) as primary body text color; it is reserved for accents and interactive states.
- Avoid arbitrary gradients; only use the predefined linear gradients (Violet Gradient A and B) for specific brand accent applications.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Base background for the entire page. |
| 1 | Subtle Surface | `#f3f3f3` | A slightly differentiated background for sections or light component backgrounds subtly set apart from the dominant canvas. |
| 2 | Elevated Card Surface | `#ffffff` | Used for cards and significant containers, appearing on top of the base canvas with distinct shadow. |

## Elevation

- **Primary Action Button (Black):** `rgba(255, 255, 255, 0.2) 0px -2px 1px 0px inset, rgba(255, 255, 255, 0.1) 0px 4px 16px 0px inset, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px`
- **Elevated Card:** `rgba(0, 0, 0, 0.04) 0px 2px 8px 0px, rgba(0, 0, 0, 0.08) 0px 8px 24px 0px, rgba(0, 0, 0, 0.12) 0px 16px 48px 0px`
- **Code Block Card:** `rgba(0, 0, 0, 0.04) 0px 2px 8px 0px, rgba(0, 0, 0, 0.08) 0px 8px 24px 0px, rgba(0, 0, 0, 0.12) 0px 16px 48px 0px`

## Imagery

The site's imagery is primarily composed of clean, contained product screenshots, often depicting code editors or terminal interfaces. These are treated with soft shadows but no strong borders, making them feel integrated into the UI. Icons are simple, outlined or filled, with a consistent stroke weight, and are monochromatic (Midnight Ink) or use subtle violet tints. Decorative graphics are minimal, often abstract grid patterns or geometric shapes incorporating the brand's violet gradients, serving as atmospheric backdrops rather than explicit content. The overall density is text-dominant, with imagery serving to illustrate technical concepts rather than for purely aesthetic purposes.

## Layout

The page adheres to a max-width contained layout, typically centering content within a 1200px width. The hero section features a centered, large headline often with a prominent gradient accent, positioned alongside a product screenshot within a framed card. Section rhythm is predominantly consistent, featuring clear vertical spacing between blocks. Content is arranged in flexible patterns, frequently utilizing two-column layouts with text on one side and associated visuals (like code blocks or icons) on the other, or feature grids with descriptive text. The header navigates across the top with a subtle transparent background, becoming active on scroll.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #020817
- background: #ffffff
- border: #e2e8f0
- accent: #711aff
- primary action: no distinct CTA color

**3-5 Example Component Prompts:**
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create a feature card: Elevated Card component with a Snow White background, 12px border-radius, and its defined shadow stack. Inside, use Midnight Ink (#020817) for a heading (GeistSans, 24px, weight 500, letter-spacing -0.48px) and body text (GeistSans, 16px, weight 400, line-height 1.5, letter-spacing -0.176px). Ensure 24px padding on all sides.

## Similar Brands

- **Vercel** — Shares a clean, developer-focused aesthetic with strong achromatic UI, minimal elevation, and selective use of vibrant accent colors for interaction.
- **Supabase** — Similar emphasis on crisp typography, code-like UI elements, and a restrained color palette that highlights functionality.
- **Replicate** — Leverages a technically-oriented visual language with a focus on clear hierarchy, compact elements, and subtle brand coloring on an otherwise monochrome canvas.
- **Linear** — Exhibits a compact UI, meticulous typography, and a deliberate absence of heavy shadows, creating a lightweight and efficient user experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #020817;
  --color-snow-white: #ffffff;
  --color-slate-gray: #e2e8f0;
  --color-anthracite: #1b1b1b;
  --color-light-fog: #f3f3f3;
  --color-obsidian-black: #0c0c0c;
  --color-electric-violet: #711aff;
  --color-vivid-rose: #ff4fae;
  --color-violet-gradient-a: #8247ff;
  --gradient-violet-gradient-a: linear-gradient(92deg, rgb(130, 71, 255) -9.21%, rgb(244, 123, 255) 104.14%);
  --color-violet-gradient-b: #8a15ff;
  --gradient-violet-gradient-b: linear-gradient(95deg, rgb(255, 114, 207) -13.39%, rgb(138, 21, 255) 114.46%);

  /* Typography — Font Families */
  --font-geistsans: 'GeistSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.176px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.216px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.48px;
  --text-display: 76px;
  --leading-display: 1;
  --tracking-display: -3.496px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 12px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-navitems: 6px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px -2px 1px 0px inset, rgba(255, 255, 255, 0.1) 0px 4px 16px 0px inset, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px, rgba(0, 0, 0, 0.08) 0px 8px 24px 0px, rgba(0, 0, 0, 0.12) 0px 16px 48px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-subtle-surface: #f3f3f3;
  --surface-elevated-card-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #020817;
  --color-snow-white: #ffffff;
  --color-slate-gray: #e2e8f0;
  --color-anthracite: #1b1b1b;
  --color-light-fog: #f3f3f3;
  --color-obsidian-black: #0c0c0c;
  --color-electric-violet: #711aff;
  --color-vivid-rose: #ff4fae;
  --color-violet-gradient-a: #8247ff;
  --color-violet-gradient-b: #8a15ff;

  /* Typography */
  --font-geistsans: 'GeistSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.176px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.216px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.48px;
  --text-display: 76px;
  --leading-display: 1;
  --tracking-display: -3.496px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px -2px 1px 0px inset, rgba(255, 255, 255, 0.1) 0px 4px 16px 0px inset, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 8px 0px, rgba(0, 0, 0, 0.08) 0px 8px 24px 0px, rgba(0, 0, 0, 0.12) 0px 16px 48px 0px;
}
```
