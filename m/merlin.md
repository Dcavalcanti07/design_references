# Merlin — Style Reference
> White canvas, sharp focus

**Theme:** light

Merlin presents a crisp, minimalist interface with a focus on clear hierarchy and actionable elements. Its design relies on a predominantly achromatic palette, using white backgrounds for expansive canvas spaces and dark charcoal for prominent text. Sparse, vivid accent colors provide functional signals and highlight interactivity. Components often feature rounded corners and subtle shadows, suggesting a friendly yet refined digital experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page and card backgrounds, providing a clean, open feel |
| Whisper White | `#fdf8f7` | `--color-whisper-white` | Subtle background for elevated cards or sections, creating a slight distinction from the main canvas |
| Powder White | `#f5f5f4` | `--color-powder-white` | Default page background for larger areas, an almost imperceptible off-white |
| Snowdrift | `#eeeeee` | `--color-snowdrift` | Lightest grey for backgrounds and subtle borders, slightly darker than Powder White |
| Silver Mist | `#dddddd` | `--color-silver-mist` | Divider lines, subtle card borders, and ghost button borders |
| Platinum Grey | `#cccccc` | `--color-platinum-grey` | Slightly darker dividers and borders for increased contrast |
| Carbon | `#1c1d1f` | `--color-carbon` | Primary dark text color for headings and body, ensuring high readability against light backgrounds |
| Lead | `#333333` | `--color-lead` | Secondary but still prominent text color |
| Anthracite | `#6a6b6c` | `--color-anthracite` | Muted text, subheadings, and iconography, offering supportive readability |
| Slate | `#808080` | `--color-slate` | Lightest practical text color for captions and helper text, used for less prominent information |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Dominant text and button background color for primary actions, providing a strong anchor |
| Success Green | `#34c759` | `--color-success-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Accent Blue | `#3575f8` | `--color-accent-blue` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Rainbow Wash | `linear-gradient(rgb(150, 223, 255) 0%, rgb(237, 237, 237) 58.17%, rgb(221, 221, 221) 100%)` | `--color-rainbow-wash` | Ephemeral background gradient for hero sections or decorative elements, creating a dynamic atmospheric effect |

## Tokens — Typography

### Inter — The primary typeface for all text. Its modern, functional aesthetic underpins the system's clarity. A range of weights allows for nuanced hierarchy, from light captions to impactful headlines. The subtle negative letter-spacing for larger sizes creates a sense of gravitas and precision. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600
- **Sizes:** 9px, 10px, 12px, 13px, 14px, 16px, 20px, 23px, 25px, 26px, 30px, 40px, 60px, 70px
- **Line height:** 1.00, 1.13, 1.15, 1.17, 1.40, 1.50, 1.55
- **Letter spacing:** 0.042em, 0.038em, 0.036em, 0.031em, 0.025em, -0.0em, -0.0em, -0.0em, -0.0em, -0.0em, -0.0em, -0.0em, -0.031em, -0.043em
- **Role:** The primary typeface for all text. Its modern, functional aesthetic underpins the system's clarity. A range of weights allows for nuanced hierarchy, from light captions to impactful headlines. The subtle negative letter-spacing for larger sizes creates a sense of gravitas and precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 23px | 1.17 | — | `--text-heading-sm` |
| heading | 40px | 1.15 | — | `--text-heading` |
| display | 70px | 1.13 | -0.043px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15px |
| input | 12.5px |
| buttons | 100px |
| largeCards | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(235, 232, 233) 1px 3px 1px 0px` | `--shadow-subtle` |
| sm | `rgb(238, 238, 238) 0px 3px 8px 0px` | `--shadow-sm` |
| xl | `rgba(0, 0, 0, 0.25) 0px 40px 60px 0px` | `--shadow-xl` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 2px 2px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgb(238, 238, 238) 3px 6px 1px 0px` | `--shadow-subtle-3` |
| subtle-4 | `rgb(221, 221, 221) 0px 2px 1px 0px` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Action button for critical conversions

Background: Charcoal Black (#000000), Text: Canvas White (#ffffff), Radius: 100px, Padding: 5px 15px.

### Success Filled Button
**Role:** Positive action or primary CTA button

Background: Success Green (#34c759), Text: Canvas White (#ffffff), Radius: 12.5px, Padding: 12.5px 25px.

### Ghost Button
**Role:** Secondary actions or links with minimal visual weight

Background: transparent, Text: Charcoal Black (#000000), Border: black 1px solid, Radius: 0px, Padding: 10px 30px.

### Subtle Ghost Button
**Role:** Tertiary actions, less prominent than ghost buttons

Background: transparent, Text: Charcoal Black (#000000), Border: none, Radius: 0px, Padding: 10px 30px.

### Callout Card
**Role:** Feature highlights or interactive educational content

Background: Canvas White (#ffffff), Border Radius: 15px, Shadow: rgb(235, 232, 233) 1px 3px 1px 0px, Padding: 10px 12.5px.

### Dialogue Card
**Role:** Elevated UI elements like modal content or popovers

Background: Canvas White (#ffffff), Border Radius: 25px, Shadow: rgba(0, 0, 0, 0.05) 0px 0.625px 1.875px 0px, rgba(0, 0, 0, 0.1) 0px 0.625px 1.25px 0px, Padding: 0.

### Contained Footer Nav Button
**Role:** Small, functional buttons in confined spaces

Background: Snowdrift (#eeeeee), Text: Canvas White (#ffffff), Radius: 100px, Padding: 5px 15px.

### Testimonial Card
**Role:** Highlighting user feedback or partner logos

Background: Whisper White (#fdf8f7), Border Radius: 20px, No shadow, Padding: 20px.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) or Powder White (#f5f5f4) as primary backgrounds for all main content areas.
- Use Charcoal Black (#000000) for primary text and major headings, ensuring high contrast.
- Apply Inter font family prominently with varied weights to establish clear content hierarchy.
- Utilize Success Green (#34c759) and Accent Blue (#3575f8) sparingly for functional call-to-actions and illustrative visual cues respectively.
- Maintain a default border-radius of 15px for most cards, and 100px for all buttons and tags.
- Implement subtle box shadows like rgb(235, 232, 233) 1px 3px 1px 0px for cards to provide low-fidelity depth without visual clutter.
- Employ `elementGap` of 10px for consistent spacing between distinct UI elements within components and small blocks.
- Apply negative letter-spacing for all headlines (sizes 60px and 70px) to enhance their crispness and impact.

### Don't
- Avoid using multiple chromatic colors alongside Success Green or Accent Blue unless for very specific semantic purposes not defined here.
- Do not introduce heavy, opaque background colors for cards or container elements; maintain the light, airy aesthetic with subtle white variations.
- Refrain from using hard, sharp corners; favor rounded edges as defined by the `radius` tokens for all interactive and container elements.
- Do not use dark backgrounds for large text blocks, as the system is optimized for a light theme and high contrast dark text.
- Avoid large and highly saturated imagery that distracts from the clean UI; prefer contained graphics or product screenshots.
- Do not use letter-spacing on body text or smaller elements (below 40px) as they primarily use `normal` or close to 0px values.
- Do not rely on strong, elaborate shadows; the system favors subtle, almost flat elevations.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Powder White | `#f5f5f4` | Base page background, a subtle, almost unnoticeable off-white. |
| 1 | Canvas White | `#ffffff` | Primary surface for cards, content blocks, and main UI elements. |
| 2 | Whisper White | `#fdf8f7` | Slightly elevated card backgrounds, adding a minor perceptual layer without significant contrast. |

## Elevation

- **Callout Card:** `rgb(235, 232, 233) 1px 3px 1px 0px`
- **Dialogue Card:** `rgba(0, 0, 0, 0.05) 0px 0.625px 1.875px 0px, rgba(0, 0, 0, 0.1) 0px 0.625px 1.25px 0px`
- **Large Header Card:** `rgb(238, 238, 238) 0px 3px 8px 0px`

## Imagery

The site uses a mix of product screenshots, abstract gradient backgrounds, and simple line-art illustrations. Product screenshots are typically high-fidelity and contained within UI cards, showcasing the Merlin interface. Abstract gradients are used as full-bleed header backgrounds, providing a soft, atmospheric backdrop without being distracting. Icons are minimal, outlined, and monochromatic, predominantly in black, serving as functional accents. Overall, imagery is supportive rather than dominant, enhancing content without overwhelming the clean UI.

## Layout

The page primarily follows a centered `pageMaxWidth` with full-bleed sections for decorative elements like the hero gradient. The hero section features a centered headline and description over an atmospheric gradient. Content sections alternate between visually distinct blocks with consistent vertical spacing, often showcasing information in vertically stacked text blocks or simple two-column layouts. The overall density is compact, ensuring clear hierarchical information presentation. Navigation is likely a sticky header not fully visible, with discrete navigation actions in the footer.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f5f5f4
border: #dddddd
accent: #3575f8
primary action: #34c759 (filled action)

Example Component Prompts:
1. Create a Hero Section: Use the Rainbow Wash gradient as a full-bleed background. Center a display headline: 'The world's first AI chief of staff' (Inter, 70px, weight 600, Charcoal Black #000000, letter-spacing -0.043px). Below that, a subtext: 'Merlin finds your highest-impact priorities from your inbox and calendar, then helps you complete them with a single click.' (Inter, 20px, weight 400, Anthracite #6a6b6c, line-height 1.4). Underneath, a Success Filled Button: 'Start free trial' (Success Green #34c759 background, Canvas White #ffffff text, 12.5px radius, 12.5px 25px padding).
2. Create a Callout Card: Use Canvas White (#ffffff) background, 15px radius. Apply subtle shadow: rgb(235, 232, 233) 1px 3px 1px 0px. Internal padding of 10px 12.5px. Add a subheading 'What Merlin Does' (Inter, 23px, weight 500, Carbon #1c1d1f) and body text 'Merlin prioritizes your inbox...' (Inter, 16px, weight 400, Anthracite #6a6b6c).
3. Create a Footer Navigation Button: Use Snowdrift (#eeeeee) background and Canvas White (#ffffff) text (bold, Inter, 14px). Radius should be 100px. Padding 5px 15px. Text: 'Sign up'.

## Similar Brands

- **Notion** — Similar white canvas, clean typography, and sparse use of color for functional elements.
- **Superhuman** — Focus on high-contrast text, minimalist interface, and emphasis on speed and productivity.
- **Linear** — Sharp, functional UI with high information density, precise typography, and subtle component styling.
- **Raycast** — Command-line-like interface with a focus on efficiency, clean typography, and minimal visual noise.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-white: #fdf8f7;
  --color-powder-white: #f5f5f4;
  --color-snowdrift: #eeeeee;
  --color-silver-mist: #dddddd;
  --color-platinum-grey: #cccccc;
  --color-carbon: #1c1d1f;
  --color-lead: #333333;
  --color-anthracite: #6a6b6c;
  --color-slate: #808080;
  --color-charcoal-black: #000000;
  --color-success-green: #34c759;
  --color-accent-blue: #3575f8;
  --color-rainbow-wash: #96dfff;
  --gradient-rainbow-wash: linear-gradient(rgb(150, 223, 255) 0%, rgb(237, 237, 237) 58.17%, rgb(221, 221, 221) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.17;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --text-display: 70px;
  --leading-display: 1.13;
  --tracking-display: -0.043px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 12.5px;
  --radius-xl-2: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 60px;
  --radius-full-2: 65px;
  --radius-full-3: 75px;
  --radius-full-4: 100px;

  /* Named Radii */
  --radius-cards: 15px;
  --radius-input: 12.5px;
  --radius-buttons: 100px;
  --radius-largecards: 40px;

  /* Shadows */
  --shadow-subtle: rgb(235, 232, 233) 1px 3px 1px 0px;
  --shadow-sm: rgb(238, 238, 238) 0px 3px 8px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 40px 60px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-3: rgb(238, 238, 238) 3px 6px 1px 0px;
  --shadow-subtle-4: rgb(221, 221, 221) 0px 2px 1px 0px;

  /* Surfaces */
  --surface-powder-white: #f5f5f4;
  --surface-canvas-white: #ffffff;
  --surface-whisper-white: #fdf8f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-whisper-white: #fdf8f7;
  --color-powder-white: #f5f5f4;
  --color-snowdrift: #eeeeee;
  --color-silver-mist: #dddddd;
  --color-platinum-grey: #cccccc;
  --color-carbon: #1c1d1f;
  --color-lead: #333333;
  --color-anthracite: #6a6b6c;
  --color-slate: #808080;
  --color-charcoal-black: #000000;
  --color-success-green: #34c759;
  --color-accent-blue: #3575f8;
  --color-rainbow-wash: #96dfff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.17;
  --text-heading: 40px;
  --leading-heading: 1.15;
  --text-display: 70px;
  --leading-display: 1.13;
  --tracking-display: -0.043px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 12.5px;
  --radius-xl-2: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 60px;
  --radius-full-2: 65px;
  --radius-full-3: 75px;
  --radius-full-4: 100px;

  /* Shadows */
  --shadow-subtle: rgb(235, 232, 233) 1px 3px 1px 0px;
  --shadow-sm: rgb(238, 238, 238) 0px 3px 8px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 40px 60px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-3: rgb(238, 238, 238) 3px 6px 1px 0px;
  --shadow-subtle-4: rgb(221, 221, 221) 0px 2px 1px 0px;
}
```
