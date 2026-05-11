# Krepling — Style Reference
> Architectural fluid canvas

**Theme:** light

Krepling employs a fluid, modern aesthetic with a spacious canvas and crisp typography. Its primary design elements are lightweight, often transparent surfaces and a singular vibrant purple accent for interactive elements. Imagery features abstract, almost architectural 3D forms, contrasting with the minimalist UI components. The system emphasizes clear hierarchy and ample whitespace, allowing content and subtle interactivity to take precedence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, text on dark backgrounds |
| Midnight Text | `#000000` | `--color-midnight-text` | Primary headings, body text, icon fills |
| Soft Gray | `#f1f1f1` | `--color-soft-gray` | Secondary card surfaces, subtle background shifts |
| Muted Ash | `#6c6b6b` | `--color-muted-ash` | Secondary text, muted borders, placeholder text |
| Steel Gray | `#b3b3b3` | `--color-steel-gray` | Hairline borders, subtle dividers |
| Deep Midnight | `#171717` | `--color-deep-midnight` | Footer backgrounds, high-contrast dark surfaces |
| Krepling Violet | `#b154f9` | `--color-krepling-violet` | Primary action buttons, interactive element borders, accent graphics |
| Rose Bloom | `#f9c2cf` | `--color-rose-bloom` | Decorative card background |
| Luminous Grape | `#635bff` | `--color-luminous-grape` | Decorative card background |
| Sunburst Yellow | `#ffe01b` | `--color-sunburst-yellow` | Decorative card background |
| Deep Plum | `#4b154c` | `--color-deep-plum` | Decorative card background |
| Sky Blue | `#99e1f4` | `--color-sky-blue` | Decorative card background |
| Grass Green | `#93d33e` | `--color-grass-green` | Decorative card background |
| Vivid Crimson | `#f22f46` | `--color-vivid-crimson` | Decorative card background |
| Ocean Teal | `#03363d` | `--color-ocean-teal` | Decorative card background |
| Electric Blue | `#1ab4d7` | `--color-electric-blue` | Decorative card background |
| Goldenrod | `#ffc439` | `--color-goldenrod` | Decorative card background |
| Sunset Orange | `#ff7a59` | `--color-sunset-orange` | Decorative card background |
| Fiery Red | `#e43225` | `--color-fiery-red` | Decorative card background |
| Gradient Dawn | `linear-gradient(90.01deg, rgb(248, 209, 201) 0.01%, rgb(221, 204, 255) 99.99%)` | `--color-gradient-dawn` | Decorative background gradient |
| Gradient Twilight | `linear-gradient(92.37deg, rgb(183, 138, 255) 16.58%, rgb(254, 156, 114) 90.82%)` | `--color-gradient-twilight` | Decorative background gradient |
| Gradient Sky | `linear-gradient(90deg, rgb(141, 200, 255) 0.01%, rgb(157, 255, 202) 99.99%)` | `--color-gradient-sky` | Decorative background gradient |
| Gradient Horizon | `linear-gradient(92.37deg, rgb(168, 218, 250) 16.58%, rgb(153, 248, 205) 90.82%)` | `--color-gradient-horizon` | Decorative background gradient |
| Gradient Cosmic | `linear-gradient(90deg, rgb(204, 237, 255) 0.01%, rgb(201, 169, 255) 99.99%)` | `--color-gradient-cosmic` | Decorative background gradient |
| Gradient Nebula | `linear-gradient(95.66deg, rgb(119, 181, 255) 18.09%, rgb(167, 130, 255) 88.64%)` | `--color-gradient-nebula` | Decorative background gradient |

## Tokens — Typography

### Regular — Regular — detected in extracted data but not described by AI · `--font-regular`
- **Weights:** 400
- **Sizes:** 16px, 18px, 24px, 32px, 48px, 64px, 80px
- **Line height:** 1.1, 1.2, 1.3
- **Letter spacing:** -0.01, 0.01, 0.02
- **Role:** Regular — detected in extracted data but not described by AI

### Inter — Primary font for all text elements: headings, body copy, links, buttons, and navigation. Features subtle negative letter spacing at larger sizes and expanded tracking for smaller elements, creating both impact and legibility. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.1, 0.1, 0.2
- **Role:** Primary font for all text elements: headings, body copy, links, buttons, and navigation. Features subtle negative letter spacing at larger sizes and expanded tracking for smaller elements, creating both impact and legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.3 | 0.1px | `--text-caption` |
| body | 18px | 1.3 | 0.1px | `--text-body` |
| subheading | 24px | 1.2 | -0.1px | `--text-subheading` |
| heading | 32px | 1.2 | -0.1px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.1px | `--text-heading-lg` |
| display | 64px | 1.1 | -0.1px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| large | 30px |
| buttons | 10px |
| default | 8px |

### Layout

- **Page max-width:** 733px
- **Section gap:** 32px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call-to-action button for critical actions

Filled with Krepling Violet (#b154f9), white text (#ffffff), and a 10px border radius. Padding is 14px vertical, 16px horizontal.

### Ghost Button
**Role:** Secondary or textual actions within a flow

Transparent background, Midnight Text (#000000) for text, 0px border radius, 20px horizontal padding, 48px vertical padding. No distinct border color.

### White Card
**Role:** Content container for features or information blocks

White Canvas (#ffffff) background, 14px border radius. Padding is 0px. No box shadow.

### FAQ Accordion Item
**Role:** Interactive list item for expandable content

Transparent background, 0px border radius. No distinct padding, uses page text styling with subtle indicators for interactivity. The surrounding container uses White Canvas and 14px radius.

### Navigation Link
**Role:** Interactive elements within the main navigation

Primary text color (#000000), no background; padding 12px vertical, 16px horizontal. Underlined on hover or active.

### Workflow Nav Item
**Role:** Contextual navigation within a dashboard or feature section

Default is transparent background with Midnight Text (#000000). Active state uses Soft Gray (#f1f1f1) background with Midnight Text (#000000), 8px border radius. Padding is 14px vertical, 16px horizontal.

## Do's and Don'ts

### Do
- Use Midnight Text (#000000) for all primary body copy and headings on White Canvas (#ffffff).
- Apply Krepling Violet (#b154f9) exclusively for primary interactive elements and brand accents.
- Maintain a clear visual hierarchy by utilizing the spacious 32px `sectionGap` between primary content blocks.
- Ensure all card and surface elements use a 14px border radius for visual consistency across content containers.
- Utilize Ghost Buttons for all actions that are not the primary call-to-action, maintaining transparency and standard text coloring.
- Employ the `Inter` font family at 400 weight for all text; adjust letter spacing according to `letterSpacing` values based on type scale role.
- For decorative elements (cards or UI graphics), leverage the accent color palette and gradients to add visual interest, always contained within distinct shapes.

### Don't
- Do not introduce new saturated colors outside of the defined accent palette; rely on the existing blues, reds, yellows, and purples as decorative elements.
- Avoid using box shadows; the design system relies on flat surfaces and color changes for depth and distinction.
- Do not deviate from the 733px `pageMaxWidth` for primary content columns; content should always be centered within this constraint.
- Refrain from using strong borders for interactive elements; most borders are subtle hairline (`#b3b3b3`) or defined by the Krepling Violet accent.
- Do not clutter components with excessive padding; adhere to the specified `cardPadding` of 20px and element-specific padding values.
- Avoid arbitrary changes to font weights or styles; only the 400 weight of Inter is used, with size and letter spacing variations for hierarchy.
- Do not use dark backgrounds globally; restrict them to specific sections like the footer or contained expressive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Primary page background and default surface for most content. |
| 1 | Soft Gray | `#f1f1f1` | Secondary background for sections or subtle elevation of content blocks. |
| 2 | Deep Midnight | `#171717` | Used for specific high-contrast areas like footers. |

## Imagery

The visual language features abstract 3D forms, often appearing as frosted or translucent pipes and floating amorphous shapes. These elements interact with colorful, icon-like product 'cards' that have rounded corners. Photography is absent; instead, the site uses expressive, somewhat whimsical illustrations that are dimensional and organic, often rendered with soft gradients. Icons are filled, with a consistent, heavier stroke appearance, and are often monochromatic but sometimes incorporate subtle color. Imagery serves a decorative, atmospheric role, creating a sense of dynamic flow and modern capability rather than direct product showcase or informational utility. The overall density of imagery is balanced, with large-scale graphics coexisting with text-dominant sections, giving significant visual space to these abstract elements.

## Layout

The site employs a max-width contained layout set at 733px, with content predominantly centered. The hero section features a unique composition with large abstract 3D elements that break the bounds of the content area, creating a full-bleed visual effect while the text remains centered. Sections generally follow a consistent vertical rhythm with a 32px `sectionGap`. Content is arranged in alternating patterns, often text on one side and a large abstract visual element on the other, or stacked centered blocks. There's an evident card grid structure for feature display. Navigation consists of a clear top bar with primary links and a 'Get Started' button, which remains sticky at the top.

## Agent Prompt Guide

primary action: #b154f9 (filled action)
Create a Primary Action Button: #b154f9 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
1. Create a Primary Action Button: Krepling Violet background (#b154f9), White Canvas text (#ffffff), Inter 400 at 16px, 10px radius, 14px vertical and 16px horizontal padding.
2. Create a White Card: White Canvas background (#ffffff), 14px radius, 0px padding. Inside, place a 'subheading' in Midnight Text (#000000) at 24px Inter 400 and a 'body' text in Midnight Text (#000000) at 18px Inter 400.
3. Create a Ghost Button: Transparent background, Midnight Text (#000000), Inter 400 at 16px, 0px radius, 48px vertical and 20px horizontal padding.
4. Create a Navigation Link: Midnight Text (#000000), Inter 400 at 16px, 12px vertical and 16px horizontal padding, no background, 8px radius.

## Similar Brands

- **Stripe** — Shares a sophisticated, modern aesthetic with ample whitespace, clean typography, and subtle, often abstract, graphic elements.
- **Linear** — Exhibits a similar focus on clarity and speed in its UI, with minimal use of color and precise, functional component design.
- **Figma** — Uses a white canvas, black text, and a single vibrant accent color to highlight interactive elements and convey brand identity.
- **Webflow** — Features a similar combination of abstract 3D visuals and a clean, spacious UI for a technical product geared towards creation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-midnight-text: #000000;
  --color-soft-gray: #f1f1f1;
  --color-muted-ash: #6c6b6b;
  --color-steel-gray: #b3b3b3;
  --color-deep-midnight: #171717;
  --color-krepling-violet: #b154f9;
  --color-rose-bloom: #f9c2cf;
  --color-luminous-grape: #635bff;
  --color-sunburst-yellow: #ffe01b;
  --color-deep-plum: #4b154c;
  --color-sky-blue: #99e1f4;
  --color-grass-green: #93d33e;
  --color-vivid-crimson: #f22f46;
  --color-ocean-teal: #03363d;
  --color-electric-blue: #1ab4d7;
  --color-goldenrod: #ffc439;
  --color-sunset-orange: #ff7a59;
  --color-fiery-red: #e43225;
  --color-gradient-dawn: #f8d1c9;
  --gradient-gradient-dawn: linear-gradient(90.01deg, rgb(248, 209, 201) 0.01%, rgb(221, 204, 255) 99.99%);
  --color-gradient-twilight: #b78aff;
  --gradient-gradient-twilight: linear-gradient(92.37deg, rgb(183, 138, 255) 16.58%, rgb(254, 156, 114) 90.82%);
  --color-gradient-sky: #8dc8ff;
  --gradient-gradient-sky: linear-gradient(90deg, rgb(141, 200, 255) 0.01%, rgb(157, 255, 202) 99.99%);
  --color-gradient-horizon: #a8dafa;
  --gradient-gradient-horizon: linear-gradient(92.37deg, rgb(168, 218, 250) 16.58%, rgb(153, 248, 205) 90.82%);
  --color-gradient-cosmic: #ccedff;
  --gradient-gradient-cosmic: linear-gradient(90deg, rgb(204, 237, 255) 0.01%, rgb(201, 169, 255) 99.99%);
  --color-gradient-nebula: #77b5ff;
  --gradient-gradient-nebula: linear-gradient(95.66deg, rgb(119, 181, 255) 18.09%, rgb(167, 130, 255) 88.64%);

  /* Typography — Font Families */
  --font-regular: 'Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.3;
  --tracking-caption: 0.1px;
  --text-body: 18px;
  --leading-body: 1.3;
  --tracking-body: 0.1px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.1px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.1px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.1px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -0.1px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 733px;
  --section-gap: 32px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 30px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-large: 30px;
  --radius-buttons: 10px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-soft-gray: #f1f1f1;
  --surface-deep-midnight: #171717;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-midnight-text: #000000;
  --color-soft-gray: #f1f1f1;
  --color-muted-ash: #6c6b6b;
  --color-steel-gray: #b3b3b3;
  --color-deep-midnight: #171717;
  --color-krepling-violet: #b154f9;
  --color-rose-bloom: #f9c2cf;
  --color-luminous-grape: #635bff;
  --color-sunburst-yellow: #ffe01b;
  --color-deep-plum: #4b154c;
  --color-sky-blue: #99e1f4;
  --color-grass-green: #93d33e;
  --color-vivid-crimson: #f22f46;
  --color-ocean-teal: #03363d;
  --color-electric-blue: #1ab4d7;
  --color-goldenrod: #ffc439;
  --color-sunset-orange: #ff7a59;
  --color-fiery-red: #e43225;
  --color-gradient-dawn: #f8d1c9;
  --color-gradient-twilight: #b78aff;
  --color-gradient-sky: #8dc8ff;
  --color-gradient-horizon: #a8dafa;
  --color-gradient-cosmic: #ccedff;
  --color-gradient-nebula: #77b5ff;

  /* Typography */
  --font-regular: 'Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.3;
  --tracking-caption: 0.1px;
  --text-body: 18px;
  --leading-body: 1.3;
  --tracking-body: 0.1px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.1px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.1px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.1px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -0.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 30px;
}
```
