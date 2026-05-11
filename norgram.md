# Norgram — Style Reference
> monochromatic architectural blueprint

**Theme:** mixed

Norgram operates with a stark, high-contrast aesthetic, juxtaposing deep black and pristine white with minimal interruption. The system leans on precise typography and a grid-based rhythm, creating a sense of quiet authority rather than overt design flourishes. Color is used sparingly, primarily for functional accents, ensuring that content and structure remain the focal point. Components emphasize lightweight clarity: flat surfaces, crisp text, and subtle interactions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#000000` | `--color-obsidian` | Primary text, critical borders, main canvas backgrounds in dark sections, player controls |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, subtle card surfaces, primary text on dark backgrounds |
| Deep Graphite | `#141414` | `--color-deep-graphite` | Card backgrounds, secondary dark surface elements |
| Powder Gray | `#efefef` | `--color-powder-gray` | Subtle background accents, muted borders, placeholder text |
| Ash Mist | `#777777` | `--color-ash-mist` | Muted helper text, secondary information text, subtle decorative strokes |
| Soft Stone | `#cecece` | `--color-soft-stone` | Subordinate body text, descriptive labels |
| Whisper Gray | `#b2b2b2` | `--color-whisper-gray` | Ghost button backgrounds and default link backgrounds, indicating non-primary actions |
| Smoked Glass | `rgba(63, 63, 63, 0.4)` | `--color-smoked-glass` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Helvetica Now Display — Primary display text, headlines, main body content, and navigation elements. Its precise tracking at larger sizes maintains clarity and strong visual presence. · `--font-helvetica-now-display`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 36px, 87px
- **Line height:** 1.00, 1.10, 1.17, 1.67
- **Letter spacing:** -0.0200em at 87px, -0.0080em at 36px, -0.0050em at 12px
- **Role:** Primary display text, headlines, main body content, and navigation elements. Its precise tracking at larger sizes maintains clarity and strong visual presence.

### Times — Long-form editorial body text, detailed descriptions, and footer content. The serif choice adds a touch of classic sophistication against the clean sans-serif displays. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Long-form editorial body text, detailed descriptions, and footer content. The serif choice adds a touch of classic sophistication against the clean sans-serif displays.

### Helvetica Now Display — Interactive link text, small labels, and button text when a slightly bolder or more compact presentation is needed than the regular weight. · `--font-helvetica-now-display`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.0060em
- **Role:** Interactive link text, small labels, and button text when a slightly bolder or more compact presentation is needed than the regular weight.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.17 | — | `--text-caption` |
| body-sm | 12px | 1.17 | — | `--text-body-sm` |
| body | 36px | 1.17 | — | `--text-body` |
| body-lg | 87px | 1.17 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 34 | 34px | `--spacing-34` |
| 50 | 50px | `--spacing-50` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4.0678px |
| forms | 10px |
| links | 26px |
| buttons | 7px |

### Layout

- **Section gap:** 68px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Ghost Player Button
**Role:** Interactive control for media playback or navigation within content blocks.

Transparent background with Obsidian text and border. Radius 0px. No padding, focusing purely on the icon or minimal text label. Uses 'Helvetica Now Display - Regular' at 10px.

### Toast Notification Button
**Role:** Close button for ephemeral notifications or alerts.

Background is 'Smoked Glass' (rgba(63, 63, 63, 0.4)) with 'Canvas White' text. Has 7px border-radius and 5px vertical / 7px horizontal padding. Uses 'Helvetica Now Display - Medium' at 12px.

### Basic Content Card
**Role:** Container for showcasing work, images, or small content snippets.

Background is 'Deep Graphite' (#141414) with a minimal border-radius of 4.0678px. No explicit padding, content is flush to edges. Font is 'Helvetica Now Display - Regular'.

### Interactive Link Button
**Role:** Actionable text links in notifications or informational areas.

Background is 'Whisper Gray' (#999999) with 10px border-radius. Padding is 3px for all sides. Text is 'Canvas White' using 'Helvetica Now Display - Medium' at 12px.

### Image Player Controls
**Role:** Controls for navigating through image galleries or project details.

Uses 'Obsidian' for active states against light backgrounds. Icons and text appear with 0px padding and 0px radius.

### Meta Information Text
**Role:** Small, secondary textual information like dates or categories.

Body text using 'Ash Mist' (#777777) or 'Soft Stone' (#cecece), typically 12px 'Helvetica Now Display - Regular'.

## Do's and Don'ts

### Do
- Maintain a stark, high-contrast palette using 'Obsidian' (#000000) for text and 'Canvas White' (#ffffff) for backgrounds, and 'Deep Graphite' (#141414) for dark surfaces.
- Apply 'Helvetica Now Display - Regular' for headlines and main content, utilizing aggressive negative letter-spacing for large titles (-0.0200em at 87px).
- Use geometric, minimal border radii: 4.0678px for cards and larger containers, and 7px for interactive elements like buttons.
- Space elements using a compact rhythm, leveraging 8px for most element gaps and 68px for section separation.
- Convey interaction through subtle background fills like 'Smoked Glass' (rgba(63, 63, 63, 0.4)) or 'Whisper Gray' (#b2b2b2) rather than strongly chromatic accents.
- Prioritize functional clarity over decorative elements; every visual choice must serve to organize or highlight content precisely.

### Don't
- Avoid decorative shadows or complex elevation schemes; surfaces should remain flat or subtly transparent.
- Do not introduce vibrant accent colors; the system relies on a strictly achromatic palette with functional gray tints.
- Refrain from using organic or hand-drawn graphic elements; visuals should be precise, geometric, and structured.
- Avoid excessive padding within containers; content often sits flush with card edges or uses minimal, proportional spacing.
- Do not use generic system fonts for display text; 'Helvetica Now Display' is critical for maintaining the brand's sharp, modern edge.
- Do not apply large, soft rounded corners unless explicitly denoted; default radii are small and precise.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default content areas. |
| 1 | Powder Gray | `#efefef` | Slightly elevated backgrounds, subtle containers, or section dividers. |
| 2 | Deep Graphite | `#141414` | Darker card surfaces and distinct content blocks within a lighter theme. |
| 3 | Obsidian | `#000000` | Dominant background for full-bleed dark sections, showcasing high-contrast content. |
| 4 | Smoked Glass | `#3f3f3f` | Transparent overlay for interactive elements like toast notifications, providing context without obscuring. |

## Imagery

This design system uses a blend of high-fidelity product photography, often showcasing technological devices or industrial designs in controlled, studio-like lighting against monochromatic backgrounds. These are integrated full-bleed or as large content blocks, serving as primary visual content rather than decorative elements. Abstract, minimalist graphics featuring clean lines and geometric structures are also present, often used subtly as background textures or brand elements. Icons are typically monochrome, outlined or filled, with a very fine stroke weight or solid, reflecting the system's overall precision.

## Layout

The layout is primarily a max-width contained grid, but projects and hero sections can expand to full-bleed. The hero pattern prominently features a full-bleed dark background with stark white, centered headlines. Content sections often alternate between light and dark thematic bands, utilizing consistent vertical spacing of 68px between major sections. Within sections, content is arranged in two-column text+image layouts or stacked centered blocks for more focused messages. There's an underlying compact density, with minimal internal padding on elements like cards, allowing imagery and text to command space. Navigation is a minimal top-bar, often ghosted or subtly present.

## Agent Prompt Guide

### Quick Color Reference
text: #000000
background: #ffffff
border: #000000
accent: #777777
primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a dark hero section: 'Obsidian' (#000000) background. Headline 'Forming Essentials' in 'Canvas White' (#ffffff) at 87px 'Helvetica Now Display - Regular', letter-spacing -0.0200em. Subtext 'We collaborate closely...' in 'Soft Stone' (#cecece) at 16px 'Times - Regular', normal letter-spacing.
2. Create a notification toast: 'Smoked Glass' (rgba(63, 63, 63, 0.4)) background, 7px border-radius. Text '2 weeks ago...' in 'Canvas White' (#ffffff) at 12px 'Helvetica Now Display - Medium', letter-spacing -0.0060em. 'Close' button with 'Whisper Gray' (#b2b2b2) background, 7px border-radius, 5px vertical / 7px horizontal padding, 'Canvas White' text at 12px 'Helvetica Now Display - Medium'.
3. Create a content card: 'Deep Graphite' (#141414) background, 4.0678px border-radius, 0px padding. Content title 'Even Realities' in 'Obsidian' (#000000) at 12px 'Helvetica Now Display - Regular', letter-spacing -0.0050em. Subtitle 'Undisturbed Connections' in 'Ash Mist' (#777777) at 10px 'Helvetica Now Display - Regular'.

## Similar Brands

- **Stripe** — Shares a focus on minimal, high-contrast interfaces and precise typography, prioritizing content over decorative styling. Uses subtle grays and deep blacks.
- **Linear** — Exhibits a similar compact information density and a strong reliance on a high-contrast dark/light mode, with a disciplined, functional approach to UI elements.
- **Apple (Product Pages)** — Features clean, full-bleed product photography integrated seamlessly with minimalist text blocks and a precise use of typography to convey authority and elegance.
- **AIGA (Brand Identity Guidelines)** — Mirrors the use of strong typographic hierarchy, high contrast, and a restrained color palette to communicate a sense of authoritative design and clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-graphite: #141414;
  --color-powder-gray: #efefef;
  --color-ash-mist: #777777;
  --color-soft-stone: #cecece;
  --color-whisper-gray: #b2b2b2;
  --color-smoked-glass: #3f3f3f;
  --gradient-smoked-glass: rgba(63, 63, 63, 0.4);

  /* Typography — Font Families */
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.17;
  --text-body-sm: 12px;
  --leading-body-sm: 1.17;
  --text-body: 36px;
  --leading-body: 1.17;
  --text-body-lg: 87px;
  --leading-body-lg: 1.17;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-50: 50px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 68px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4.0678px;
  --radius-md-2: 7px;
  --radius-lg: 10px;
  --radius-3xl: 26px;

  /* Named Radii */
  --radius-cards: 4.0678px;
  --radius-forms: 10px;
  --radius-links: 26px;
  --radius-buttons: 7px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-powder-gray: #efefef;
  --surface-deep-graphite: #141414;
  --surface-obsidian: #000000;
  --surface-smoked-glass: #3f3f3f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-graphite: #141414;
  --color-powder-gray: #efefef;
  --color-ash-mist: #777777;
  --color-soft-stone: #cecece;
  --color-whisper-gray: #b2b2b2;
  --color-smoked-glass: #3f3f3f;

  /* Typography */
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.17;
  --text-body-sm: 12px;
  --leading-body-sm: 1.17;
  --text-body: 36px;
  --leading-body: 1.17;
  --text-body-lg: 87px;
  --leading-body-lg: 1.17;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-50: 50px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 4.0678px;
  --radius-md-2: 7px;
  --radius-lg: 10px;
  --radius-3xl: 26px;
}
```
