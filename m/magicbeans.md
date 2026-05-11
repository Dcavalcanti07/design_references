# Magicbeans — Style Reference
> Notion-esque productivity canvas

**Theme:** light

Magic Beans employs a clean, Notion-inspired aesthetic with abundant white space and high-contrast typography. Accents of vibrant orange and green punctuate the monochrome base, primarily through subtle iconography, adding a touch of playfulness to an otherwise business-focused interface. Emphasis is placed on clear information hierarchy through distinct text sizing and bold headings, while soft card shadows and fully rounded buttons suggest an approachable, user-friendly experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, UI elements |
| Ghostly Gray | `#faf9f7` | `--color-ghostly-gray` | Secondary card backgrounds, footer background – subtle depth against Canvas White |
| Carbon Black | `#000000` | `--color-carbon-black` | Primary text, button backgrounds, accent elements, notification bars – high contrast for readability |
| Graphite | `#1a1a19` | `--color-graphite` | Strong text, primary action text on light backgrounds, button backgrounds – used almost interchangeably with Carbon Black for core text and interactive elements |
| Charcoal | `#333331` | `--color-charcoal` | Secondary text for body copy and headings, providing a softer alternative to Graphite while maintaining contrast |
| Light Steel | `#e5e7eb` | `--color-light-steel` | Hairline borders, subtle dividers, ghost button borders – provides visual separation without heaviness |
| Fog | `#f0f0f0` | `--color-fog` | Card borders, providing a slightly darker demarcation than Light Steel |
| Subtle Gray | `#808080` | `--color-subtle-gray` | Muted helper text, placeholder text |
| Magic Orange | `#ff5310` | `--color-magic-orange` | Orange text accent for links, tags, and emphasized short phrases. |
| Magic Green | `#44c67f` | `--color-magic-green` | Green text accent for links, tags, and emphasized short phrases |
| Accent Green | `#81e9b0` | `--color-accent-green` | Lighter variant of Magic Green, used for decorative borders and subtle backgrounds in Notion-style UI elements |
| Product Blue | `#0098f1` | `--color-product-blue` | Accent for product illustrations and occasional informational highlights |

## Tokens — Typography

### Inter — Primary typeface for all UI elements, headings, and body copy. Its versatility across weights supports a clear content hierarchy on the Notion-inspired surfaces while maintaining legibility. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 24px, 40px, 64px
- **Line height:** 0.90, 1.00, 1.18, 1.20, 1.33, 1.41, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Primary typeface for all UI elements, headings, and body copy. Its versatility across weights supports a clear content hierarchy on the Notion-inspired surfaces while maintaining legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 40px | 1.2 | — | `--text-heading-lg` |
| display | 64px | 0.9 | — | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| forms | 9999px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02...` | `--shadow-xl` |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action button

Filled with Carbon Black or Graphite, white text, fully rounded (9999px radius). Used for primary actions like 'Log in to get started'.

### Feature Card (Subtle Shadow)
**Role:** Container for showcasing features or information

Background Canvas White, 12px border-radius, with a soft, layered shadow for subtle elevation: rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02) 0px 53px 32px 0px, rgba(0, 0, 0, 0.03) 0px 24px 24px 0px, rgba(0, 0, 0, 0.04) 0px 6px 13px 0px. Padding variable.

### Feature Card (Ghostly Background)
**Role:** Alternative container for features or as a secondary content block

Background Ghostly Gray (#faf9f7), 16px border-radius, no shadow. Internal padding 32px.

### Notificaton Banner
**Role:** Top-level communication for important updates

Full-width black background with white text, providing high contrast for critical messages. Appears at the very top of the page.

### Notion-style Dashboard Card
**Role:** Internal UI component for displaying summarized data

Canvas White background, 16px border-radius, no shadow, with 24px internal padding. Features Notion-like internal elements with subtle borders and data indicators.

## Do's and Don'ts

### Do
- Use Inter font family for all text elements, leveraging weights 400, 500, 600, or 700 to establish hierarchy.
- Apply Canvas White (#ffffff) as the primary background for all page sections and elevated component surfaces.
- Employ Carbon Black (#000000) or Graphite (#1a1a19) for primary text and calls-to-action, ensuring high contrast.
- Round all interactive elements like buttons and form fields to a 9999px radius for a soft, approachable feel.
- Utilize Magic Orange (#ff5310) and Magic Green (#44c67f) exclusively for subtle iconography, feature highlights, or specific semantic indicators, not as primary action colors.
- Define clear vertical rhythm using 64px for primary section gaps and 8px for small element spacing.

### Don't
- Do not introduce new color hues beyond the defined brand and accent colors; maintain the predominantly achromatic palette.
- Avoid using extensive drop shadows or heavy borders, opting instead for subtle elevation or hairline definition with Light Steel (#e5e7eb) or Fog (#f0f0f0).
- Do not deviate from the Inter font family or introduce decorative fonts.
- Do not use brand or accent colors for large background areas or extensive text blocks; their role is strictly for highlights and small functional elements.
- Avoid overly complex layouts; prioritize clear, centered content blocks and intuitive information flow facilitated by ample white space.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default surface for elevated cards or clean UI sections. |
| 2 | Ghostly Gray | `#faf9f7` | Secondary background for sections or cards needing a subtle differentiation from the main canvas. |

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02) 0px 53px 32px 0px, rgba(0, 0, 0, 0.03) 0px 24px 24px 0px, rgba(0, 0, 0, 0.04) 0px 6px 13px 0px`

## Imagery

This site features minimal imagery, primarily focusing on clean UI and product screenshots. The visual language is centered around abstract, jelly-bean-shaped organic outlines in brand accent colors (orange, green, yellow) that float decoratively in the background, reinforcing the 'Magic Beans' name. Icons are simple, outlined, and monochromatic, occasionally tinted with brand colors for emphasis or function. The overall density is text-dominant, with imagery serving as supportive branding rather than primary content.

## Layout

The page maintains a centered, contained layout with no explicit max-width, allowing content to naturally scale while providing comfortable side margins. The hero section is full-width, with a large, centered headline and a central call-to-action. Content sections alternate between visually distinct blocks, often presenting 2-column layouts with text and product visuals. Vertical rhythm is established through consistent section gaps and ample padding within internal components. A sticky top bar navigation with basic links keeps key actions accessible.

## Agent Prompt Guide

Quick Color Reference:
text: #1a1a19
background: #ffffff
border: #e5e7eb
accent: #ff5310
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a Feature Card (Subtle Shadow): Canvas White (#ffffff) background, 12px border-radius, shadow: rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02) 0px 53px 32px 0px, rgba(0, 0, 0, 0.03) 0px 24px 24px 0px, rgba(0, 0, 0, 0.04) 0px 6px 13px 0px. Internal content should have 32px padding, with a heading at 24px Graphite (#1a1a19) weight 600, and body text at 16px Charcoal (#333331) weight 400.
3. Create a Notion-style Dashboard Card: Canvas White (#ffffff) background, 16px border-radius, no shadow, 24px padding. Inside, include a heading 'Dashboard' at 24px Graphite (#1a1a19) weight 600, and two data display elements side-by-side. Each data element should have Light Steel (#e5e7eb) border, 'Revenue' or 'Expenses' text 14px Graphite (#1a1a19) weight 500, and associated value like '$57,300' at 40px Graphite (#1a1a19) weight 700. Use Magic Green (#44c67f) for 'Revenue' icon and Magic Orange (#ff5310) for 'Expenses' icon.

## Similar Brands

- **Notion** — Clean, predominantly white canvas, emphasis on typography for hierarchy, and minimalist UI elements.
- **Linear** — High-contrast text on light backgrounds, strong emphasis on functional typography, and subtle card-based layouts.
- **Stripe** — Minimalist design, strong typography, and strategic use of subtle brand colors for accents on an otherwise neutral palette.
- **Superhuman** — Focus on extreme minimalism, fast UI, sharp text, and a clean interface that prioritizes function over ornamentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghostly-gray: #faf9f7;
  --color-carbon-black: #000000;
  --color-graphite: #1a1a19;
  --color-charcoal: #333331;
  --color-light-steel: #e5e7eb;
  --color-fog: #f0f0f0;
  --color-subtle-gray: #808080;
  --color-magic-orange: #ff5310;
  --color-magic-green: #44c67f;
  --color-accent-green: #81e9b0;
  --color-product-blue: #0098f1;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 64px;
  --leading-display: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-forms: 9999px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02) 0px 53px 32px 0px, rgba(0, 0, 0, 0.03) 0px 24px 24px 0px, rgba(0, 0, 0, 0.04) 0px 6px 13px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ghostly-gray: #faf9f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghostly-gray: #faf9f7;
  --color-carbon-black: #000000;
  --color-graphite: #1a1a19;
  --color-charcoal: #333331;
  --color-light-steel: #e5e7eb;
  --color-fog: #f0f0f0;
  --color-subtle-gray: #808080;
  --color-magic-orange: #ff5310;
  --color-magic-green: #44c67f;
  --color-accent-green: #81e9b0;
  --color-product-blue: #0098f1;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 64px;
  --leading-display: 0.9;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 94px 38px 0px, rgba(0, 0, 0, 0.02) 0px 53px 32px 0px, rgba(0, 0, 0, 0.03) 0px 24px 24px 0px, rgba(0, 0, 0, 0.04) 0px 6px 13px 0px;
}
```
