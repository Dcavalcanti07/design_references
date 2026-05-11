# AREA 17 — Style Reference
> Architectural blueprint on white marble.

**Theme:** light

AREA 17 presents a sober, confident visual brand where information hierarchy and clarity are paramount. The design system prioritizes a clean, spacious light theme with strong achromatic contrasts, allowing content to lead. Subtle gray surfaces and crisp borders provide structure without visual clutter, while a single, vibrant yellow accent color is reserved for functional highlights and calls to attention. Typography is meticulously crafted for legibility and presence, relying on distinct sans-serif families.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, input fields, primary card surfaces, active state button background |
| Ink Black | `#1a1a1a` | `--color-ink-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Cloud Gray | `#f2f2f2` | `--color-cloud-gray` | Secondary card backgrounds, neutral button backgrounds, subtly distinct surface levels |
| Ghost Border | `#e6e6e6` | `--color-ghost-border` | Hairline borders for cards, buttons, inputs, structural dividers throughout the layout |
| Faded Stone | `#949494` | `--color-faded-stone` | Muted secondary text, descriptive labels, inactive navigation links |
| Paper Bark | `#f2ede9` | `--color-paper-bark` | Tertiary card backgrounds, introducing a subtle warm undertone for specific content blocks |
| Sunny Yellow | `#fdf313` | `--color-sunny-yellow` | Attention-grabbing highlights, announcement bars, functional elements requiring high visibility |
| Dark Overlay | `#000000` | `--color-dark-overlay` | Modal backgrounds, full-bleed section backgrounds for contrast, certain icon fills |
| Button Gray | `#cccccc` | `--color-button-gray` | Subtly darker background for neutral buttons, creating a slight visual distinction from Cloud Gray |

## Tokens — Typography

### SuisseIntl — Brand and display typography. Its precise tracking and robust forms convey authority and modernity. Used for all main headings, navigation, and button text. · `--font-suisseintl`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 20px, 32px, 42px, 55px
- **Line height:** 1.10, 1.15, 1.40
- **Letter spacing:** -0.0150em (55px), -0.0140em (42px), -0.0130em (32px), 0.0040em (16px)
- **Role:** Brand and display typography. Its precise tracking and robust forms convey authority and modernity. Used for all main headings, navigation, and button text.

### ui-sans-serif — Body copy, helper text, and less emphasized descriptive content. Provides high readability and a clear, functional counterpoint to SuisseIntl. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Body copy, helper text, and less emphasized descriptive content. Provides high readability and a clear, functional counterpoint to SuisseIntl.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | 0.064px | `--text-body` |
| subheading | 20px | 1.4 | 0.08px | `--text-subheading` |
| heading | 32px | 1.15 | -0.416px | `--text-heading` |
| heading-lg | 42px | 1.15 | -0.588px | `--text-heading-lg` |
| display | 55px | 1.1 | -0.825px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 232 | 232px | `--spacing-232` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 8px |
| inputs | 8px |
| buttons | 8px |
| default | 8px |
| navigation | 4px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Neutral Button
**Role:** Default interactive element for general actions.

Background: Cloud Gray (#f2f2f2), Text: Ink Black (#1a1a1a), Border: Ghost Border (#e6e6e6), Radius: 8px, Padding: 16px vertical, 24px horizontal. Uses SuisseIntl font.

### Ghost Button
**Role:** Secondary action or subtle interaction.

Background: transparent (rgba(0,0,0,0)), Text: Ink Black (#1a1a1a), Border: Ghost Border (#e6e6e6), Radius: 4px, Padding: 0px vertical, 12px horizontal. Uses SuisseIntl font.

### Overlay Button
**Role:** Interactive element on dark or image backgrounds.

Background: rgba(0,0,0,0.2), Text: Canvas White (#ffffff), Border: Ghost Border (#e6e6e6), Radius: 8px, Padding: 0. Uses SuisseIntl font.

### White Canvas Button
**Role:** Interactive element with higher contrast on darker backgrounds.

Background: rgba(255,255,255,0.2), Text: Canvas White (#ffffff), Border: Ghost Border (#e6e6e6), Radius: 8px, Padding: 16px vertical, 24px horizontal. Uses SuisseIntl font.

### Base Card
**Role:** Container for content, typically for features or portfolio items.

Background: Cloud Gray (#f2f2f2), Border: none, Radius: 8px, Padding: 0.

### Featured Card
**Role:** Distinguished content container, larger or with specific padding.

Background: Cloud Gray (#f2f2f2), Border: none, Radius: 16px, Padding: 16px vertical, 0 horizontal.

### Accent Card
**Role:** Card with a warmer background hue for thematic grouping.

Background: Paper Bark (#f2ede9), Border: none, Radius: 8px, Padding: 0.

### Standard Input Field
**Role:** User input for forms.

Background: Canvas White (#ffffff), Text: Ink Black (#1a1a1a), Border: Ghost Border (#e6e6e6) 1px solid, Radius: 8px, Padding: 16px all sides. Uses SuisseIntl font.

### Underlined Input Field
**Role:** Minimalist input field, often for search or single-line entries.

Background: transparent (rgba(0,0,0,0)), Text: Ink Black (#1a1a1a), Border: Ink Black (#1a1a1a) on bottom, Radius: 0, Padding: 0. Uses SuisseIntl font.

### Announcement Banner
**Role:** High-visibility information or call to action.

Background: Sunny Yellow (#fdf313), Text: Ink Black (#1a1a1a), Padding: Implied. Typically spans full width at top or bottom of viewport.

## Do's and Don'ts

### Do
- Prioritize SuisseIntl for all headings, navigation, and button text, using its defined weights and line heights for maximum impact.
- Maintain a clear achromatic palette for structural elements and text, relying on Ink Black (#1a1a1a) for primary text and Canvas White (#ffffff) or Cloud Gray (#f2f2f2) for backgrounds.
- Apply Ghost Border (#e6e6e6) at 1px thickness for all separating lines, card outlines, and button borders to establish subtle structure.
- Reserve Sunny Yellow (#fdf313) strictly for announcement banners, urgent calls to attention, or critical highlight elements to ensure its distinctiveness and impact.
- Use 8px border radius for all buttons, typical cards, and input fields to maintain a consistent, gentle corner treatment.
- Employ a base spacing unit of 8px, building all other spacing values (padding, margins, gaps) in multiples of this unit for a harmonious rhythm.
- Implement the type scale precisely, especially the negative letter-spacing for larger SuisseIntl headlines, to achieve the intended sophisticated visual density.
- Use 16px vertical and 24px horizontal padding for standard buttons in the Primary Neutral Button style.

### Don't
- Do not introduce new saturated colors beyond Sunny Yellow (#fdf313) for interface elements; stick to the achromatic palette for UI structure.
- Avoid heavy drop shadows or complex gradients; rely on clean surfacing and crisp borders for perceived depth and separation.
- Do not deviate from the specified SuisseIntl letter-spacing values, particularly for headlines, as it is a core characteristic of the brand's typography.
- Do not use box-shadows on cards; rely on background color changes and borders for visual grouping and hierarchy.
- Avoid arbitrary changes to border radii; use the established 8px for most interactive elements and cards, 4px for navigation items, and 16px for accent cards, or 9999px for pill-shaped elements.
- Do not use generic system fonts for headlines or navigation; SuisseIntl is critical for brand identity.
- Do not use uncontained imagery; apply tight cropping and integrate product visuals within defined content blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base for most content. |
| 1 | Cloud Gray | `#f2f2f2` | Secondary surface for cards, buttons, and content blocks that need to stand out slightly from the canvas. |
| 2 | Paper Bark | `#f2ede9` | Tertiary surface for specific accent cards, introducing a subtle warm distinction. |

## Imagery

This system heavily employs high-quality photography and video. Photography is typically product-focused or showcases individuals in work environments, with a calm, naturalistic treatment emphasizing realism and authenticity. Imagery is used in full-bleed sections (especially video as background) or tightly cropped within content blocks, often without rounded corners. Icons are minimal, adhering to an outlined, light stroke style, primarily serving functional roles with the Ink Black color. There's a notable absence of illustrations or abstract graphics. The visual density of imagery is balanced, with large hero visuals contrasting with text-dominant content sections.

## Layout

The site uses a contained page model, with content centered within a max-width, appearing as if on a canvas, rather than full-bleed. The hero section often features a full-bleed video or dark background with a central bold headline. Section rhythm is primarily driven by consistent vertical spacing (64px to 192px) and alternating light and sometimes dark or warm-toned background sections. Content is arranged in flexible patterns, including large centered text blocks, two-column layouts often alternating text on left/image on right (and vice-versa), and evident card grids for features or portfolio items. Navigation is a persistent top bar, sticky on scroll, featuring minimal text links.

## Agent Prompt Guide

### Quick Color Reference
- text: #1a1a1a
- background: #ffffff
- border: #e6e6e6
- accent: #fdf313
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
- Create a hero section: Full viewport height. Background video behind a large centered headline. Headline: "We partner with the world’s most influential organizations to realize their vision and achieve their greatest impact." using SuisseIntl weight 500, #1a1a1a, size 55px, line-height 1.1, letter-spacing -0.825px.
- Create a content card for a case study: Cloud Gray (#f2f2f2) background, 8px border radius, 0 padding. Inside, place an image, followed by a heading (SuisseIntl 32px, Ink Black #1a1a1a, line-height 1.15, letter-spacing -0.416px), and a text link (SuisseIntl 16px, Ink Black #1a1a1a, line-height 1.4, letter-spacing 0.064px).
- Design a navigation bar item: Text 'Clients' using SuisseIntl weight 400, Ink Black (#1a1a1a), 16px size. Border #e6e6e6 with 4px radius, and 0 padding. When active, use #fdf313 as an underline or background highlight.
- Generate a standard form input field: Canvas White (#ffffff) background, 1px solid Ghost Border (#e6e6e6), 8px border radius, 16px padding on all sides. Placeholder text and input text are Ink Black (#1a1a1a), using SuisseIntl font.

## Similar Brands

- **AIGA** — Clear achromatic UI with strong sans-serif typography and content-centric layout.
- **Pentagram** — Emphasis on bold typography and visual hierarchy over decorative elements; minimal use of color for impact.
- **Koto** — Agency sites with a minimalist aesthetic, sharp contrast, and a focus on content presentation.
- **Upperquad** — Clean, spacious layouts, strong typographic voice, and subtle use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1a1a1a;
  --color-cloud-gray: #f2f2f2;
  --color-ghost-border: #e6e6e6;
  --color-faded-stone: #949494;
  --color-paper-bark: #f2ede9;
  --color-sunny-yellow: #fdf313;
  --color-dark-overlay: #000000;
  --color-button-gray: #cccccc;

  /* Typography — Font Families */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.064px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.08px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.416px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.588px;
  --text-display: 55px;
  --leading-display: 1.1;
  --tracking-display: -0.825px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-232: 232px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 8px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-navigation: 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #f2f2f2;
  --surface-paper-bark: #f2ede9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1a1a1a;
  --color-cloud-gray: #f2f2f2;
  --color-ghost-border: #e6e6e6;
  --color-faded-stone: #949494;
  --color-paper-bark: #f2ede9;
  --color-sunny-yellow: #fdf313;
  --color-dark-overlay: #000000;
  --color-button-gray: #cccccc;

  /* Typography */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.064px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.08px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.416px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.588px;
  --text-display: 55px;
  --leading-display: 1.1;
  --tracking-display: -0.825px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-232: 232px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 9999px;
}
```
