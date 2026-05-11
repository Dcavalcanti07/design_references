# Atlassian — Style Reference
> organized digital workspace

**Theme:** light

Atlassian's visual system evokes a highly organized and collaborative digital workspace, built on a foundation of crisp, accessible neutrality and punctuated by vibrant brand accents. The prominent use of `Slate 900` text on `Canvas Frost` backgrounds ensures high legibility, while `Periwinkle 500` brings an energetic, inviting feel to interactive elements. The system maintains order through a meticulous spacing hierarchy and subtle shadows on key cards, presenting a precise yet approachable tool for complex teamwork.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Frost | `#ffffff` | `--color-canvas-frost` | Page backgrounds, elevated surfaces, primary text on dark backgrounds |
| Slate 900 | `#000000` | `--color-slate-900` | Primary text, strong borders |
| Graphite Base | `#101214` | `--color-graphite-base` | Dark surface backgrounds, secondary text, subtle borders |
| Periwinkle 500 | `#1868db` | `--color-periwinkle-500` | Primary actions, interactive link text, brand iconography — signals activity and focus. |
| Steel Grey | `#1c2b42` | `--color-steel-grey` | Darker neutral text, UI elements, strong outlines for interactive states. |
| Ash Cloud | `#f0f1f2` | `--color-ash-cloud` | Ghost button backgrounds, subtle UI element backgrounds, light borders. |
| Storm Sky | `#42526e` | `--color-storm-sky` | Input borders, muted icon fills — indicates informational context or secondary UI elements. |
| Harvest Gold | `#fca700` | `--color-harvest-gold` | Highlight accents, secondary calls to action, decorative graphic fills — provides warm contrast. |
| Subtle Mist | `#b7b9be` | `--color-subtle-mist` | Subtle list item borders, card shadows. |
| Sky Haze | `#e9f2fe` | `--color-sky-haze` | Hover states, subtle background accents, less prominent button backgrounds. |
| Midnight Shadow | `#292a2e` | `--color-midnight-shadow` | Subtle text shades, deeper neutral borders. |
| Frost Shadow | `#c2c7d0` | `--color-frost-shadow` | Card shadow color, provides slight depth for elevated surfaces. |
| Conic Energy | `conic-gradient(rgb(191, 99, 243) 170deg, rgb(252, 167, 0) 171deg, rgb(252, 167, 0) 230deg, rgb(77, 140, 237) 231deg, rgb(77, 140, 237) 360deg)` | `--color-conic-energy` | Distinctive brand gradient for hero sections and illustrative elements — signals dynamism and multi-faceted solutions. |

## Tokens — Typography

### Charlie Text — Primary body copy, subheadings, and UI labels. Its range of weights supports both content hierarchy and functional clarity without overwhelming the interface. · `--font-charlie-text`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 13px, 14px, 16px, 20px, 24px
- **Line height:** 0.88, 1.00, 1.20, 1.25, 1.29, 1.40, 1.50, 2.29
- **Letter spacing:** normal
- **Role:** Primary body copy, subheadings, and UI labels. Its range of weights supports both content hierarchy and functional clarity without overwhelming the interface.

### Charlie Display — Headlines and prominent display text. Its bolder weights and tighter tracking create a confident and impactful presence, particularly at larger scales. · `--font-charlie-display`
- **Substitute:** Poppins
- **Weights:** 400, 500, 700, 800
- **Sizes:** 14px, 24px, 28px, 32px, 40px, 44px, 48px, 70px, 80px
- **Line height:** 1.00, 1.10, 1.14, 1.17, 1.19, 1.20, 1.25, 1.43
- **Letter spacing:** 0.0120em at smaller sizes, tightening to 0.0300em at larger display sizes for visual precision.
- **Role:** Headlines and prominent display text. Its bolder weights and tighter tracking create a confident and impactful presence, particularly at larger scales.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.4 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.29 | 0.288px | `--text-heading-sm` |
| heading | 32px | 1.17 | 0.384px | `--text-heading` |
| heading-lg | 40px | 1.2 | 0.48px | `--text-heading-lg` |
| display | 48px | 1.19 | 0.576px | `--text-display` |
| display-lg | 70px | 1 | 0.84px | `--text-display-lg` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| buttons | 10000px |
| general | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0....` | `--shadow-subtle` |

### Layout

- **Section gap:** 24px
- **Card padding:** 20px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Filled Button

Solid `Periwinkle 500` background with `Canvas Frost` text. Features a full pill shape via `10000px` border-radius. Padding: `6px` top, `8px` bottom, `22px` horizontal.

### Text Link Button
**Role:** Ghost Button

Transparent background with `Slate 900` text. Border-radius `3px`. Padding: `8px` top, `0px` bottom, `32px` right, `0px` left. Best for secondary actions or navigation.

### Pill Ghost Button
**Role:** Ghost Button

Light `Ash Cloud` background with `Slate 900` text. Rounded `28px` border-radius. Padding: `1px` top/bottom, `30px` horizontal.

### Icon Button
**Role:** Round Ghost Button

Transparent background with `Slate 900` icon. Full circle shape via `100%` border-radius. Padding: `6px` all sides.

### Elevated Content Card
**Role:** Informational Card

White background with `20px` border-radius. Features a subtle shadow: `rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px`. Internal padding: `30px` top/bottom, `20px` horizontal.

### Transparent Card
**Role:** Informational Card

Transparent background with `0px` border-radius and no shadow. Internal padding: `0px` all sides. For content that blends into the background.

### Rounded Top Card
**Role:** Informational Card

Transparent background with `20px 20px 0px 0px` border-radius for the top corners and no shadow. Internal padding: `0px` all sides. Used for sections that visually connect to content below.

### Outline Input Field
**Role:** Form Input

Transparent background, `Storm Sky` border-bottom. Placeholder text in `Storm Sky`. No padding, no border-radius. Minimalist design for data entry.

## Do's and Don'ts

### Do
- Use `Periwinkle 500` (#1868db) exclusively for primary interactive elements to clearly signpost actions.
- Maintain high contrast by pairing `Slate 900` (#000000) or `Steel Grey` (#1c2b42) text on `Canvas Frost` (#ffffff) backgrounds.
- Apply `20px` border-radius consistently for all elevated cards and product views to establish visual softness.
- Utilize `10000px` border-radius for all primary buttons to create a clear, approachable call to action.
- Employ `Charlie Display` at `70px` or `80px` for hero headlines using weight `700` or `800` to create significant visual impact.
- Use `4px` as the base unit for horizontal and vertical spacing between elements to ensure a harmonious grid.
- Implement the `rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px` shadow for all elevated cards to provide subtle depth.

### Don't
- Do not use `Harvest Gold` (#fca700) for interactive elements, reserve it for accents and decorative purposes.
- Avoid using multiple border-radii values for buttons; stick to `10000px` for primary actions and `28px` for secondary pill buttons.
- Do not introduce new shadow styles; consistency is key with the defined `card` shadow.
- Refrain from deviating from the defined `4px` spacing unit to avoid visual clutter and maintain a consistent rhythm.
- Do not alter the letter-spacing values from `normal` for Charlie Text and the specific `0.0120em` or `0.0300em` for Charlie Display.
- Avoid using `Storm Sky` (#42526e) as a primary text color, as its primary role is for inputs and muted UI details.
- Do not use transparent backgrounds with `0px` border-radius for cards that hold critical, distinct content; reserve them for blending sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Frost | `#ffffff` | Primary page background |
| 1 | Ash Cloud | `#f0f1f2` | Subtle background for ghost buttons and certain UI components |

## Elevation

- **Elevated Content Card:** `rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px`

## Imagery

The site uses a combination of abstract, multicolored graphic elements (often based on the Conic Energy gradient) alongside functional product screenshots. Photography is minimal, appearing primarily within video thumbnails or abstracted for background context. Product screenshots are contained, precise, and often feature dark UI themes to contrast with the light page background, highlighting the software's functionality. Icons are primarily monochromatic, filled-style, in `Slate 900` or `Steel Grey`. Imagery primarily serves to illustrate concepts and showcase product features rather than purely decorative atmosphere, with specific graphical treatments often containing text or video. The overall density of imagery is balanced, with a strong emphasis on integrating visuals directly with explanatory content.

## Layout

The page maintains a centered max-width, with sections featuring consistent vertical spacing. The hero section often utilizes a full-bleed dark background with centered headlines and prominent primary action buttons. Content sections frequently alternate between split layouts (text on one side, visual on the other) and centered stacks. Card grids are used to display features or related content in a structured manner. The navigation is a persistent top bar, with elements organized into clear categories. The layout conveys an organized, information-dense yet breathable experience.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #1c2b42
accent: #fca700
primary action: #1868db (filled action)

Example Component Prompts:
1. Create a Primary Action Button: `Periwinkle 500` background (#1868db), `Canvas Frost` text (#ffffff), `10000px` radius. Padding: `6px` top, `22px` right, `8px` bottom, `22px` left. Text: 'Get Started'.
2. Create an Elevated Content Card: `Canvas Frost` background (#ffffff), `20px` radius, shadow: `rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px`. Internal padding: `30px` top/bottom, `20px` horizontal.
3. Create a Headline using Charlie Display: `Slate 900` text (#000000), `Charlie Display` font, weight `800`, size `48px`, line-height `1.19`, letter-spacing `0.576px`. Text: 'Unleash your superteam'.

## Similar Brands

- **Jira** — Clear information hierarchy, structured UI, and vibrant accent colors on a neutral background.
- **Confluence** — Emphasis on collaborative content, structured cards, and a similar approach to typography for readability.
- **Asana** — Bright, inviting accent colors against clean, professional neutrals. Prioritizes task and project clarity.
- **Slack** — Uses a limited but impactful brand color palette, focusing on functional elements with clear visual cues.
- **Microsoft 365 (SaaS interfaces)** — Extensive use of functional UI elements, clear type hierarchy, and accessible color palettes for productivity apps.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-frost: #ffffff;
  --color-slate-900: #000000;
  --color-graphite-base: #101214;
  --color-periwinkle-500: #1868db;
  --color-steel-grey: #1c2b42;
  --color-ash-cloud: #f0f1f2;
  --color-storm-sky: #42526e;
  --color-harvest-gold: #fca700;
  --color-subtle-mist: #b7b9be;
  --color-sky-haze: #e9f2fe;
  --color-midnight-shadow: #292a2e;
  --color-frost-shadow: #c2c7d0;
  --color-conic-energy: #bf63f3;
  --gradient-conic-energy: conic-gradient(rgb(191, 99, 243) 170deg, rgb(252, 167, 0) 171deg, rgb(252, 167, 0) 230deg, rgb(77, 140, 237) 231deg, rgb(77, 140, 237) 360deg);

  /* Typography — Font Families */
  --font-charlie-text: 'Charlie Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-charlie-display: 'Charlie Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: 0.288px;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --tracking-heading: 0.384px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.48px;
  --text-display: 48px;
  --leading-display: 1.19;
  --tracking-display: 0.576px;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --tracking-display-lg: 0.84px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 20px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 5px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 40px;
  --radius-full: 10000px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-buttons: 10000px;
  --radius-general: 2px;

  /* Shadows */
  --shadow-subtle: rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px;

  /* Surfaces */
  --surface-canvas-frost: #ffffff;
  --surface-ash-cloud: #f0f1f2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-frost: #ffffff;
  --color-slate-900: #000000;
  --color-graphite-base: #101214;
  --color-periwinkle-500: #1868db;
  --color-steel-grey: #1c2b42;
  --color-ash-cloud: #f0f1f2;
  --color-storm-sky: #42526e;
  --color-harvest-gold: #fca700;
  --color-subtle-mist: #b7b9be;
  --color-sky-haze: #e9f2fe;
  --color-midnight-shadow: #292a2e;
  --color-frost-shadow: #c2c7d0;
  --color-conic-energy: #bf63f3;

  /* Typography */
  --font-charlie-text: 'Charlie Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-charlie-display: 'Charlie Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: 0.288px;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --tracking-heading: 0.384px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.48px;
  --text-display: 48px;
  --leading-display: 1.19;
  --tracking-display: 0.576px;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --tracking-display-lg: 0.84px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 5px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 40px;
  --radius-full: 10000px;

  /* Shadows */
  --shadow-subtle: rgba(9, 30, 66, 0.31) 0px 0px 1px 0px, rgba(9, 30, 66, 0.25) 0px 1px 1px 0px;
}
```
