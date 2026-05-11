# herding.app — Style Reference
> Graphite workshop under a soft spotlight. Surfaces are not black, but deep charcoal, illuminated by concentrated white text and a single vibrant highlight for interactive elements.

**Theme:** dark

This design system evokes a digital craftsman's workshop feel, with a muted dark palette and subtle elevation shifts creating a sense of depth and organization. The interplay of soft, almost invisible backgrounds with crisp white typography and geometric accents defines a precise yet approachable atmosphere. Rounded corners on interactive elements provide a gentle contrast to the otherwise stark, modular structure, hinting at user-friendliness within a powerful system.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Slate | `#232320` | `--color-storm-slate` | Page background, primary card surfaces, foundational UI elements. |
| Deep Graphite | `#1c1c1a` | `--color-deep-graphite` | Background for secondary panels and sub-sections, indicating a subtle recess or grouping. |
| Ash Stone | `#2e2e2b` | `--color-ash-stone` | Elevated card backgrounds, slightly lighter than the base Storm Slate, indicating a raised surface. |
| Iron Oxide | `#35352f` | `--color-iron-oxide` | Tertiary card backgrounds or hover states, providing a slightly warmer, more textured feel. |
| Zinc Gray | `#3e3e38` | `--color-zinc-gray` | Lightest background for elevated surfaces or active states, offering subtle distinction. |
| Quartz Dust | `#45453` | `--color-quartz-dust` | Button backgrounds for secondary actions, blending into the dark theme. |
| Ghost White | `#fffffe` | `--color-ghost-white` | Primary text, headings, icons, interactive element labels — the dominant foreground color that cuts through the dark background. |
| Silver Thread | `#a3a29c` | `--color-silver-thread` | Secondary text, subtle borders, inactive states, providing high contrast without being pure white. |
| Whisper Gray | `#75746c` | `--color-whisper-gray` | Descriptive text, icon details, placeholder text — a softer neutral that recedes slightly. |
| Ember White | `#fefeda0e` | `--color-ember-white` | Low-opacity button background that suggests interaction without high contrast. |
| Active Charcoal | `#7f7e77` | `--color-active-charcoal` | Solid background for primary interactive buttons, indicating an active or selected state. |

## Tokens — Typography

### Styrene — Universal font for all text elements: headings, body text, buttons, and links. Its geometric, slightly condensed form supports the precise, structured aesthetic and makes technical content approachable. · `--font-styrene`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 11px, 14px, 15px, 20px, 27px, 45px
- **Line height:** 1.12
- **Letter spacing:** -0.0500em
- **Role:** Universal font for all text elements: headings, body text, buttons, and links. Its geometric, slightly condensed form supports the precise, structured aesthetic and makes technical content approachable.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.56 | -0.55px | `--text-caption` |
| body-sm | 14px | 1.2 | -0.7px | `--text-body-sm` |
| subheading | 20px | 1.2 | -1px | `--text-subheading` |
| heading | 27px | 1.12 | -1.35px | `--text-heading` |
| display | 45px | 1.12 | -2.25px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| pills | 9999px |
| buttons | 16px |
| default | 7.5px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset, rgba(8, 9, 1...` | `--shadow-xl` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Interactive element

Rounded rectangle button. Background: `Ember White` (rgba(254, 254, 218, 0.055)), Text: `Whisper Gray` (rgba(255, 252, 236, 0.392)) in Styrene 15px/400. Rounded corners 16px. Padding: 0px vertical, 16px horizontal.

### Text Link Button
**Role:** Interactive element

Transparent button with `Ghost White` text (rgba(255, 255, 254, 0.92)) in Styrene 15px/400. No border radius, 0px padding. Focuses on pure functionality with minimal visual adornment.

### Accent Call-to-Action Button
**Role:** Primary Call to Action

Solid background button for critical actions. Background: `Active Charcoal` (rgb(127, 126, 119)), Text: `Slate` (rgb(22, 22, 21)) in Styrene 15px/400. Rounded corners 16px. Padding: 0px vertical, 16px horizontal.

### Pill Button
**Role:** Contextual filter or tag

Highly rounded button. Background: rgba(255, 255, 236, 0.173), Text: `Ghost White` (rgba(255, 255, 254, 0.92)) in Styrene 15px/400. Radius: 9999px. Padding: 0px vertical, 0px horizontal. Used for compact, standalone actions.

### Information Card (Level 1)
**Role:** Content container

Background: `Ash Stone` (#2e2e2b), with 7.5px border radius. Padding: minimum 16px on all sides, often 32px vertical and 45px horizontal. Features a subtle inner shadow defined by `rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset`.

### Information Card (Level 2)
**Role:** Nested content container

Background: `Deep Graphite` (#1c1c1a), with 7.5px border radius. Used for content nested within Level 1 cards or distinct content blocks.

### Feature Icon Card
**Role:** Atomic feature display

Small square card with `Quartz Dust` (#45453e) background, 7.5px radius. Contains icons or short labels, typically used in grids. Internally padded with 8px.

## Do's and Don'ts

### Do
- Use `Storm Slate` (#232320) as the foundational background for pages and large sections to ensure a consistent dark theme.
- Apply `Ghost White` (#fffffe) for all primary text, headings, and interactive elements to ensure readability against dark backgrounds.
- Maintain the Styrene font at weight 400 for all typography, adjusting size and line-height according to the type scale.
- Utilize 16px corner radius for most interactive buttons and 7.5px for content cards, establishing a consistent softening of rectangular forms.
- Apply `rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset` shadow for subtle internal depth on elevated card components.
- Employ `Ember White` (rgba(254, 254, 218, 0.055)) as a low-opacity background for secondary buttons, indicating interactivity without demanding attention.
- Use `9999px` radius exclusively for pill-shaped buttons and tags to create a distinctive, self-contained interactive element.

### Don't
- Do not introduce highly saturated colors for backgrounds or major UI elements; maintain the low-chroma dark palette.
- Avoid using drop shadows for elevation; rely on the subtle inset shadow and background color shifts (`Deep Graphite` vs `Ash Stone`) to indicate depth.
- Do not use multiple font families; all text must be Styrene 400.
- Avoid arbitrary padding or margin values; adhere strictly to the 4px base unit spacing scale (4px, 8px, 12px, 16px, 32px, 45px).
- Do not use pure black (#000000) for backgrounds; `Storm Slate` (#232320) is the darkest base color.
- Do not use plain rectangular buttons without corner radius; all interactive buttons should have at least 16px radius, or 9999px for pills.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#232320` | The primary background for the entire application, providing a deep, consistent canvas. |
| 1 | Base Card | `#2e2e2b` | Standard content containers, slightly raised from the page canvas, indicating primary content blocks. |
| 2 | Nested Card | `#1c1c1a` | Containers for content nested within Base Cards or for visually distinct, slightly recessed sections. |

## Elevation

- **Information Card (Level 1):** `rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset, rgba(8, 9, 1, 0.024) 0px 24px 29px 0px inset, rgba(8, 9, 1, 0.02) 0px 11px 14px 0px inset, rgba(8, 9, 1, 0.01) 0px 6px 7px 0px inset, rgba(8, 9, 1, 0.008) 0px 2.5px 2px 0px inset, rgba(8, 9, 1, 0.047) 0px 0px 0px 1px inset`

## Imagery

The visual language is dominantly UI and abstract. There are no photographs or complex illustrations. Product screenshots are contained within UI components, often at an angle, blending into the dark theme. Icons are monochromatic, filled `Ghost White` against dark backgrounds, with a clean, geometric style. The key visual element is a vibrant green-to-blue linear gradient used as a background or highlight in specific sections, providing a burst of digital energy against the muted dark interface. This gradient is treated as a contained accent, not a full-bleed element, emphasizing precision.

## Layout

The layout is a max-width 1280px centered container, providing ample breathing room within the dark canvas. The hero section features a left-aligned, large headline, contrasted by right-aligned information cards. Content sections throughout the site are primarily modular, organized into distinct rectangular cards or panels. Grids are evident for feature displays (3-column) and interactive element arrangements. Vertical spacing between sections is generous (48px standard). The site employs a sticky top navigation bar with minimal elements, maintaining a focused user experience.

## Agent Prompt Guide

### Quick Color Reference
- Text: `Ghost White` (#fffffe)
- Background: `Storm Slate` (#232320)
- Primary CTA background: `Active Charcoal` (#7f7e77)
- Secondary CTA background: `Ember White` (rgba(254, 254, 218, 0.055))
- Border/Divider: `Silver Thread` (#a3a29c)

### 3-5 Example Component Prompts
1. **Create a hero section:** Left-aligned heading 'Bookmarking for internet herders.' using Styrene 45px/400 `Ghost White` and -2.25px letter spacing. Add body text 'Herdi.ng is a no-frills visual bookmarking tool...' using Styrene 15px/400 `Ghost White` and -0.75px letter spacing. Ensure the section background is `Storm Slate` (#232320).
2. **Generate a primary action button:** Button labeled 'Sign up' with `Active Charcoal` (#7f7e77) background, `Slate` (#161615) text (Styrene 15px/400, -0.75px letter spacing), 16px border-radius, and 0px vertical, 16px horizontal padding.
3. **Design an information card:** Background `Ash Stone` (#2e2e2b), 7.5px border-radius, `rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset` shadow. Inside, add a title 'Sign up for the early beta.' with `Ghost White` text (Styrene 20px/400, -1px letter spacing), and body text 'Only for testing purposes.' with `Whisper Gray` text (Styrene 15px/400, -0.75px letter spacing). Apply 32px vertical and 45px horizontal internal padding.
4. **Create a theme switcher pill button:** A button labeled 'Theme switcher' with background `rgba(255, 255, 236, 0.173)`, `Ghost White` text (Styrene 15px/400, -0.75px letter spacing), and 9999px border-radius. Include 0px vertical and 0px horizontal padding, with an icon (using `Ghost White` fill) to the left of the text, separated by 8px.

## Similar Brands

- **Linear** — Monochromatic dark mode UI with sharp typography and subtle elevation through background color shifts, often using contained accent gradients.
- **Raycast** — Command-line interface aesthetic applied to a GUI, featuring strong use of dark neutrals, precise typography, and highly functional, minimalistic components.
- **Arc Browser** — Heavy reliance on dark gray values, geometric design elements, and contained bursts of colorful gradients or highlights against a muted UI.
- **GitHub (Dark Mode)** — Systematic use of varying shades of dark gray backgrounds to denote hierarchy and structure, combined with crisp white text and selective accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-slate: #232320;
  --color-deep-graphite: #1c1c1a;
  --color-ash-stone: #2e2e2b;
  --color-iron-oxide: #35352f;
  --color-zinc-gray: #3e3e38;
  --color-quartz-dust: #45453;
  --color-ghost-white: #fffffe;
  --color-silver-thread: #a3a29c;
  --color-whisper-gray: #75746c;
  --color-ember-white: #fefeda0e;
  --color-active-charcoal: #7f7e77;

  /* Typography — Font Families */
  --font-styrene: 'Styrene', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.56;
  --tracking-caption: -0.55px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.7px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -1px;
  --text-heading: 27px;
  --leading-heading: 1.12;
  --tracking-heading: -1.35px;
  --text-display: 45px;
  --leading-display: 1.12;
  --tracking-display: -2.25px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 7.5px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 1485px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pills: 9999px;
  --radius-buttons: 16px;
  --radius-default: 7.5px;

  /* Shadows */
  --shadow-xl: rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset, rgba(8, 9, 1, 0.024) 0px 24px 29px 0px inset, rgba(8, 9, 1, 0.02) 0px 11px 14px 0px inset, rgba(8, 9, 1, 0.01) 0px 6px 7px 0px inset, rgba(8, 9, 1, 0.008) 0px 2.5px 2px 0px inset, rgba(8, 9, 1, 0.047) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-page-canvas: #232320;
  --surface-base-card: #2e2e2b;
  --surface-nested-card: #1c1c1a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-slate: #232320;
  --color-deep-graphite: #1c1c1a;
  --color-ash-stone: #2e2e2b;
  --color-iron-oxide: #35352f;
  --color-zinc-gray: #3e3e38;
  --color-quartz-dust: #45453;
  --color-ghost-white: #fffffe;
  --color-silver-thread: #a3a29c;
  --color-whisper-gray: #75746c;
  --color-ember-white: #fefeda0e;
  --color-active-charcoal: #7f7e77;

  /* Typography */
  --font-styrene: 'Styrene', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.56;
  --tracking-caption: -0.55px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.7px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -1px;
  --text-heading: 27px;
  --leading-heading: 1.12;
  --tracking-heading: -1.35px;
  --text-display: 45px;
  --leading-display: 1.12;
  --tracking-display: -2.25px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 7.5px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 1485px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-xl: rgba(8, 9, 1, 0.08) 0px 56px 72px 0px inset, rgba(8, 9, 1, 0.024) 0px 24px 29px 0px inset, rgba(8, 9, 1, 0.02) 0px 11px 14px 0px inset, rgba(8, 9, 1, 0.01) 0px 6px 7px 0px inset, rgba(8, 9, 1, 0.008) 0px 2.5px 2px 0px inset, rgba(8, 9, 1, 0.047) 0px 0px 0px 1px inset;
}
```
