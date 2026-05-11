# Qatchup — Style Reference
> Whiteboard doodle transparency.

**Theme:** light

Qatchup employs a whiteboard-chic aesthetic: a bright white canvas paired with high-contrast dark text and controls. Its visual identity relies on precise typography with subtle negative letter-spacing, a playful doodle illustration style, and softly shadowed cards that lift content just above the stark background. Interaction elements are clearly defined through solid fills, outlined variants, and generous radius values, creating a friendly yet direct user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fafafa` | `--color-canvas-white` | Page backgrounds, header backgrounds, card surfaces |
| Absolute Zero | `#292929` | `--color-absolute-zero` | Primary text, darkest surface elements, filled button backgrounds, primary navigation text |
| Graphite | `#696969` | `--color-graphite` | Secondary text, icons, helper text, subdued borders |
| Ink Black | `#080808` | `--color-ink-black` | Headline text, high-contrast text elements |
| Cloud White | `#f4f4f5` | `--color-cloud-white` | Subtle background for ghost button states, card surfaces |
| Silver Mist | `#cccccc` | `--color-silver-mist` | Muted borders and button text |
| Cool Gray | `#e4e4e7` | `--color-cool-gray` | Light borders for images and textual elements |
| Light Steel | `#b2b2b2` | `--color-light-steel` | Tertiary text for card descriptions and subtle details |
| Stone Gray | `#999999` | `--color-stone-gray` | Minor textual details, pricing suffixes |
| Deep Gray | `#222222` | `--color-deep-gray` | Darker iconography and text accents |
| Blue Pop | `#0bA5EC` | `--color-blue-pop` | Decorative card background for specific feature highlights. This is the only vivid color, making it a powerful accent |

## Tokens — Typography

### Aspekta — All primary interface text, including headings, body, buttons, and links. The consistent use of a single font family creates typographic unity, while varied weights and precise letter-spacing sculpt hierarchy. · `--font-aspekta`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 48px, 56px
- **Line height:** 1.14, 1.17, 1.20, 1.25, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 2.00
- **Letter spacing:** -0.0350em at 56px, -0.0100em at 12px
- **Role:** All primary interface text, including headings, body, buttons, and links. The consistent use of a single font family creates typographic unity, while varied weights and precise letter-spacing sculpt hierarchy.

### Fasthand — Decorative introductory text and subtle section labels, providing a handwritten, informal counterpoint to the primary typeface. · `--font-fasthand`
- **Substitute:** Kalam
- **Weights:** 400
- **Sizes:** 32px
- **Line height:** 1.38
- **Letter spacing:** -0.0100em
- **Role:** Decorative introductory text and subtle section labels, providing a handwritten, informal counterpoint to the primary typeface.

### Aspekta 500 — Aspekta 500 — detected in extracted data but not described by AI · `--font-aspekta-500`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** Aspekta 500 — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 2 | -0.12px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.16px | `--text-body-sm` |
| body | 16px | 1.5 | -0.18px | `--text-body` |
| subheading | 18px | 1.43 | -0.29px | `--text-subheading` |
| heading-sm | 20px | 1.4 | -0.32px | `--text-heading-sm` |
| heading | 24px | 1.33 | -0.38px | `--text-heading` |
| heading-lg | 32px | 1.25 | -0.64px | `--text-heading-lg` |
| display | 56px | 1.14 | -1.96px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 32px |
| images | 16px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.0...` | `--shadow-subtle` |
| subtle-2 | `rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.0...` | `--shadow-subtle-2` |
| lg | `rgba(16, 24, 40, 0.08) 0px 17px 23px -6px, rgba(16, 24, 4...` | `--shadow-lg` |
| subtle-3 | `rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.0...` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Key interactions and calls to action.

Filled with Absolute Zero (#292929) background, Canvas White (#fafafa) text, 100px border-radius, and 10px vertical, 16px horizontal padding.

### Ghost Button
**Role:** Secondary actions or navigation items.

Transparent background with Absolute Zero (#292929) text and a 1px Absolute Zero (#292929) border, with 100px border-radius and 10px vertical, 16px horizontal padding.

### Disabled Button
**Role:** Non-interactive elements indicating future availability.

Cloud White (#f4f4f5) background with muted Silver Mist (#cccccc) text, 100px border-radius and 11px vertical, 22px horizontal padding.

### Elevated Content Card
**Role:** Displaying key information with subtle separation from the background.

Canvas White (#fafafa) background, 32px border-radius, and a soft shadow (rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px). Padding is 32px vertical, 24px horizontal.

### Section Divider Card
**Role:** Visually distinct blocks within a section, often serving as backgrounds for content groupings.

Absolute Zero (#292929) background with 32px border-radius. No padding or shadows.

### Badge/Tag
**Role:** Small, informational labels.

Solid Blue Pop (#0bA5EC) background with a 999px border-radius. No padding or content specific styles are present, indicating it's primarily a decorative container.

### List Item Card
**Role:** Individual items in lists, often with no distinct background for a minimal appearance.

Transparent background with 0px border-radius and no shadows or padding, relying on surrounding layout for structure.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#fafafa) for all backgrounds and primary surfaces.
- Use Absolute Zero (#292929) as the default color for most text, buttons, and prominent UI elements.
- Apply Aspekta (Inter) for all functional text; use Fasthand (Kalam) sparingly for decorative headers or accents as seen in the hero section.
- Utilize 100px border-radius for buttons and 32px for cards to maintain a consistently soft, approachable aesthetic.
- Employ the subtle shadow (rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px) to elevate key content cards.
- Maintain negative letter-spacing for headings and larger text sizes to ensure a tight, intentional typographic appearance.
- Use Blue Pop (#0bA5EC) exclusively as a high-impact accent color for small, functional elements or decorative blocks, not for primary text or extensive fills.

### Don't
- Avoid introducing additional saturated colors; maintain the predominantly achromatic palette with Blue Pop (#0bA5EC) as the sole accent.
- Do not use sharp corners; all interactive and content-holding components should employ significant border-radii.
- Refrain from heavy, multi-layered shadows; the design relies on subtle, single-layer elevation where present.
- Do not use generic system fonts; stick to Aspekta (Inter) and Fasthand (Kalam) for brand consistency.
- Avoid complex gradients or patterns; the aesthetic is clean, flat, and uses solid color fields.
- Do not vary line-height significantly from the established typographic scale; maintain the compact, readable vertical rhythm.
- Do not use a narrow page maximum width; content should comfortably expand horizontally within a flexible layout.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fafafa` | Primary page background and base layer for all content. |
| 1 | Cloud White | `#f4f4f5` | Slightly off-white for subtle background variations or ghost button states, creating minimal depth. |
| 2 | Absolute Zero | `#292929` | Darkest background for content blocks requiring high contrast or visual weight, often in monochromatic sections. |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px`
- **Elevated Decorative Element:** `rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 2px 3px 0px, rgba(47, 48, 55, 0.05) 0px 24px 68px 0px, rgba(34, 42, 53, 0.04) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px`
- **Image with Elevation:** `rgba(16, 24, 40, 0.08) 0px 17px 23px -6px, rgba(16, 24, 40, 0.03) 0px 6px 9px -3px`

## Imagery

The site uses line-based, cartoon-style illustrations that resemble hand-drawn doodles, characterized by organic shapes and a multi-color palette that contrasts with the monochrome UI. These illustrations are decorative, providing atmosphere and breaking up text-heavy sections. Product UI elements are presented as clean, white cards with subtle shadows, hinting at product screenshots but rendered in a clean, elevated style. Icons are simple, outlined, and monochromatic, maintaining a light visual weight.

## Layout

The page primarily uses a full-width canvas that contains content sections within a logical, often centered, horizontal alignment. The hero section features a centered headline over a background that combines a white canvas with a playful full-width doodle illustration. Sections alternate between full-width content blocks and those with specific max-widths for legibility. Content is arranged in flexible patterns, including centered stacks and implicit 2-column layouts (text left, text right). Navigation is a minimal top bar with right-aligned links and buttons.

## Agent Prompt Guide

Quick Color Reference: 
text: #080808
background: #fafafa
border: #e4e4e7
accent: #0bA5EC
primary action: #292929 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #292929 background, #fafafa text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create an elevated feedback card: Canvas White (#fafafa) background, 32px border-radius, soft shadow (rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px). Use 32px vertical and 24px horizontal padding. Inside, place a 24px Aspekta weight 500 Ink Black (#080808) title 'Give Feedback', and 16px Aspekta weight 400 Graphite (#696969) description 'Share your thoughts & insights'.
3. Create a ghost navigation button: Transparent background, Aspekta 16px weight 400 Absolute Zero (#292929) text, 100px border-radius, 1px Absolute Zero (#292929) border, and 10px vertical, 16px horizontal padding.

## Similar Brands

- **Typeform** — Shares a clean, white-space heavy design with strong typography and playful, artistic illustrations.
- **Linear** — Utilizes a functional, monochrome palette with a single accent color for interactive elements and focuses on precise typography.
- **Figma** — Employs a clean, bright UI with a focus on clear hierarchy, subtle elevation for cards, and occasional illustrative elements.
- **Notion** — Relies on a minimalist, white canvas punctuated by dark text and a clear, functional typographic scale, often with soft-edged components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-absolute-zero: #292929;
  --color-graphite: #696969;
  --color-ink-black: #080808;
  --color-cloud-white: #f4f4f5;
  --color-silver-mist: #cccccc;
  --color-cool-gray: #e4e4e7;
  --color-light-steel: #b2b2b2;
  --color-stone-gray: #999999;
  --color-deep-gray: #222222;
  --color-blue-pop: #0bA5EC;

  /* Typography — Font Families */
  --font-aspekta: 'Aspekta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fasthand: 'Fasthand', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aspekta-500: 'Aspekta 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.18px;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.29px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.32px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.38px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.64px;
  --text-display: 56px;
  --leading-display: 1.14;
  --tracking-display: -1.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 32px;
  --radius-images: 16px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-subtle: rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 2px 3px 0px, rgba(34, 42, 53, 0.04) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;
  --shadow-subtle-2: rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 2px 3px 0px, rgba(47, 48, 55, 0.05) 0px 24px 68px 0px, rgba(34, 42, 53, 0.04) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;
  --shadow-lg: rgba(16, 24, 40, 0.08) 0px 17px 23px -6px, rgba(16, 24, 40, 0.03) 0px 6px 9px -3px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-canvas-white: #fafafa;
  --surface-cloud-white: #f4f4f5;
  --surface-absolute-zero: #292929;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fafafa;
  --color-absolute-zero: #292929;
  --color-graphite: #696969;
  --color-ink-black: #080808;
  --color-cloud-white: #f4f4f5;
  --color-silver-mist: #cccccc;
  --color-cool-gray: #e4e4e7;
  --color-light-steel: #b2b2b2;
  --color-stone-gray: #999999;
  --color-deep-gray: #222222;
  --color-blue-pop: #0bA5EC;

  /* Typography */
  --font-aspekta: 'Aspekta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fasthand: 'Fasthand', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aspekta-500: 'Aspekta 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.18px;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.29px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.32px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.38px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.64px;
  --text-display: 56px;
  --leading-display: 1.14;
  --tracking-display: -1.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 32px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-subtle: rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 2px 3px 0px, rgba(34, 42, 53, 0.04) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;
  --shadow-subtle-2: rgba(19, 19, 22, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 2px 3px 0px, rgba(47, 48, 55, 0.05) 0px 24px 68px 0px, rgba(34, 42, 53, 0.04) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;
  --shadow-lg: rgba(16, 24, 40, 0.08) 0px 17px 23px -6px, rgba(16, 24, 40, 0.03) 0px 6px 9px -3px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.2) 0px 0px 0.5px 0.5px, rgba(0, 0, 0, 0.08) 0px 1px 1px -0.5px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;
}
```
