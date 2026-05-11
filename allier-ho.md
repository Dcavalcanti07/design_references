# Allier Ho — Style Reference
> gallery on white canvas

**Theme:** light

Allier Ho employs a sophisticated, minimalist aesthetic, balancing stark monochrome contrasts with unexpected typography and subtle color accents. Typography carries significant weight in defining the brand, pairing a distinguished serif with a modern mono-spaced font for a unique visual voice. Layouts feature clean lines and a compact density, allowing ample negative space to frame content and direct focus, while elements maintain visual lightness through ghost buttons and thin borders.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcfcfc` | `--color-canvas-white` | Page backgrounds, accent card surfaces, default UI elements |
| Midnight Black | `#000000` | `--color-midnight-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ink Grey | `#1c1c1c` | `--color-ink-grey` | Heading text, robust borders |
| Raisin Black | `#262626` | `--color-raisin-black` | Subtle text, secondary borders, subtle background tints |
| Stone Grey | `#a8a8a8` | `--color-stone-grey` | Muted helper text, delicate borders, placeholder elements |
| Purple Haze | `#6c5f7d` | `--color-purple-haze` | Accent backgrounds for hero sections, prominent headings, text block fills |
| Sage Whisper | `#cee6cc` | `--color-sage-whisper` | Subtle highlighting for important body text and decorative elements, soft borders |

## Tokens — Typography

### Crimson Pro — Hero and section headings — the light 300 weight creates an authoritative, restrained voice, contrasting with typical bold headings. · `--font-crimson-pro`
- **Substitute:** Lora
- **Weights:** 300
- **Sizes:** 44px, 50px
- **Line height:** 0.95, 1.15
- **Letter spacing:** -1.496px at 44px, -1.5px at 50px
- **Role:** Hero and section headings — the light 300 weight creates an authoritative, restrained voice, contrasting with typical bold headings.

### Azeret Mono — Body text for descriptions and detail, adding a technical, precise feel. Also used for tags and small labels. · `--font-azeret-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 18px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.12px at 12px, -0.18px at 18px
- **Role:** Body text for descriptions and detail, adding a technical, precise feel. Also used for tags and small labels.

### system-ui, sans-serif — Navigation, meta text, and general UI elements requiring clarity and neutrality at small sizes. · `--font-system-ui-sans-serif`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Navigation, meta text, and general UI elements requiring clarity and neutrality at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.12px | `--text-caption` |
| body | 18px | 1.2 | -0.18px | `--text-body` |
| heading-lg | 44px | 0.95 | -1.496px | `--text-heading-lg` |
| display | 50px | 1.15 | -1.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 200px |

### Layout

- **Section gap:** 40px
- **Card padding:** 18px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** Call-to-action buttons, secondary actions

Ghost button with no background, a 1px border in Midnight Black, text in Midnight Black, and 200px border-radius. Padding of 10px vertical and 18px horizontal.

### Subtle Accent Button
**Role:** Secondary call-to-action, 'View All' links

Background of rgba(0,0,0,0.1) for subtle hover or active state, text in Midnight Black, 1px border in Midnight Black, with 200px border-radius. Padding of 10px vertical and 18px horizontal.

### Primary Navigation Link
**Role:** Main navigation items

Uses system sans-serif font weight 400 at 12px, Midnight Black text color, with 4px top/bottom padding and 40px left/right padding. Underline border appears on hover/active.

### Hero Section Headline
**Role:** Dominant textual element in hero areas

Crimson Pro, weight 300, 50px font size, line height 1.15, letter spacing -1.5px, Sage Whisper text color. Often appears within a Purple Haze background block.

### Body Text Block
**Role:** Standard body copy, project descriptions

Azeret Mono, weight 400, 18px font size, line height 1.2, letter spacing -0.18px, Midnight Black.

### Metadata Tag
**Role:** Categorization and supplementary information

Azeret Mono, weight 400, 12px font size, line height 1.0, letter spacing -0.12px, Stone Grey text color.

## Do's and Don'ts

### Do
- Prioritize Crimson Pro weight 300 for all primary headings, leveraging its delicate appearance for a refined tone.
- Use Azeret Mono for all text that conveys information and detail, maintaining its precise, compact feel.
- Apply Canvas White (#fcfcfc) as the dominant background for body sections to maximize content clarity and spaciousness.
- Utilize Purple Haze (#6c5f7d) exclusively for significant full-width sections or accent blocks to create a distinct visual break.
- Ensure all interactive elements like buttons and links maintain a 200px border-radius for a consistent soft, rounded pill shape.
- Employ a base element gap of 10px between interactive components and small content blocks for compact density.
- Use Midnight Black (#000000) for primary interactive text and subtle borders, reserving it for strong visual anchors.

### Don't
- Avoid using bold or heavy weights for Crimson Pro; the brand relies on its current delicate styling.
- Do not introduce additional background colors unless they are specific brand accents, maintaining the monochrome Canvas White base.
- Refrain from using hard-edged or square buttons; all buttons must reflect the 200px border-radius component styling.
- Do not deviate from the established letter spacing for Crimson Pro and Azeret Mono; these are crucial for typographic identity.
- Avoid excessive use of shadow or elevation effects; the design emphasizes flat planes and clean separation through ample white space.
- Do not use highly saturated or vivid colors outside of the defined brand accents; maintain a muted, controlled palette.
- Do not use generic sans-serif fonts where Crimson Pro or Azeret Mono is specified; their unique character defines the brand's voice.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fcfcfc` | Primary page background, default content surfaces |
| 1 | Purple Haze | `#6c5f7d` | Elevated section backgrounds, accent content blocks |

## Imagery

Imagery primarily consists of contained product screenshots and abstract 3D renders, often showcased within rectangular cards. Photography, when present, is tight-cropped and product-focused, avoiding lifestyle contexts. Illustrations lean towards abstract, organic, and sculptural forms, like the prominent dark ink blob, serving a decorative atmosphere rather than explanatory content. Icons are minimal, likely outlined and monochrome, blending into the UI. The density is image-heavy in portfolio sections, using large visuals to showcase work, while header areas are text-dominant with a single key visual.

## Layout

The page maintains a full-bleed layout for background elements, but content is largely contained within a horizontal maximum width, centered on the screen. The hero section features a full-height, full-width abstract visual with a distinct Purple Haze content block overlaid, containing the primary headline and a ghost button. Section rhythm is characterized by contrasting background colors (Canvas White alternating with Purple Haze sections above the fold) and consistent vertical spacing using a 40px section gap. Content arrangement frequently uses large visual displays for portfolio pieces, often with associated text appearing below. Navigation is a minimalist top bar with centered links, sticky on scroll.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fcfcfc
border: #000000
accent: #6c5f7d
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Canvas White background. Headline 'A multidisciplinary creative' using Crimson Pro, weight 300, 50px, line-height 1.15, letter-spacing -1.5px, Sage Whisper text, contained within a Purple Haze block. Below headline, add a Ghost Button labeled 'learn more' with 1px Midnight Black border, 200px radius, 10px vertical and 18px horizontal padding.

Create a portfolio card: Canvas White background. Primary text 'Bringing the Android rebrand to life' using Azeret Mono, weight 400, 18px, line-height 1.2, letter-spacing -0.18px, Midnight Black. Below, add a Metadata Tag 'Brand' using Azeret Mono, weight 400, 12px, line-height 1.0, letter-spacing -0.12px, Stone Grey text.

Create a secondary heading: 'See the latest & greatest' using Ink Grey, Crimson Pro, weight 300, 44px, line-height 0.95, letter-spacing -1.496px. Center it on a Canvas White background. Below it, add a Subtle Accent Button 'view all work' with rgba(0,0,0,0.1) background, Midnight Black text, 1px Midnight Black border, 200px radius, 10px vertical and 18px horizontal padding.

## Similar Brands

- **Awwwards** — Showcases work with emphasis on large visuals, minimalist UI, and sophisticated typography.
- **Garden Eight** — Combines unique typography, abstract visuals, and a clean, spacious layout for a creative agency feel.
- **Fantasy** — Uses large, impactful hero visuals and a restrained, elegant typographic system against a neutral backdrop.
- **Basic Theory** — Focuses on monochrome UI with strong typographic presence and subtle interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcfcfc;
  --color-midnight-black: #000000;
  --color-ink-grey: #1c1c1c;
  --color-raisin-black: #262626;
  --color-stone-grey: #a8a8a8;
  --color-purple-haze: #6c5f7d;
  --color-sage-whisper: #cee6cc;

  /* Typography — Font Families */
  --font-crimson-pro: 'Crimson Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-azeret-mono: 'Azeret Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-system-ui-sans-serif: 'system-ui, sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.12px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.18px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.496px;
  --text-display: 50px;
  --leading-display: 1.15;
  --tracking-display: -1.5px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 18px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-full: 200px;

  /* Named Radii */
  --radius-buttons: 200px;

  /* Surfaces */
  --surface-canvas-white: #fcfcfc;
  --surface-purple-haze: #6c5f7d;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcfcfc;
  --color-midnight-black: #000000;
  --color-ink-grey: #1c1c1c;
  --color-raisin-black: #262626;
  --color-stone-grey: #a8a8a8;
  --color-purple-haze: #6c5f7d;
  --color-sage-whisper: #cee6cc;

  /* Typography */
  --font-crimson-pro: 'Crimson Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-azeret-mono: 'Azeret Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-system-ui-sans-serif: 'system-ui, sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.12px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.18px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.496px;
  --text-display: 50px;
  --leading-display: 1.15;
  --tracking-display: -1.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-full: 200px;
}
```
