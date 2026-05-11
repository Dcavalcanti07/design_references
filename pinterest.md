# Pinterest — Style Reference
> Bright Workshop Canvas — A clean, spacious white background provides the stage for vibrant, curated content, like a well-lit studio.

**Theme:** light

Pinterest's design aesthetic is that of a bustling creative workshop — a bright, expansive canvas where visual ideas are quickly surfaced and organized. Large, clean typography draws immediate attention, feeling both direct and friendly, while a vibrant signature red provides energetic points of interaction. Subtle, rounded cornering across all interactive elements, paired with ample whitespace, cultivates an approachable and clear interface that supports rapid content browsing and discovery.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, text elements for contrast, main search bar background. |
| Jet Black | `#000000` | `--color-jet-black` | Primary text, navigation links, button text, icon fills. |
| Graphite | `#211922` | `--color-graphite` | Dominant secondary text, body copy, less prominent links and navigation items. This near-black serves as the primary dark neutral. |
| Ash Gray | `#666666` | `--color-ash-gray` | Subtle secondary text, inactive icons, supporting descriptive text. Provides softer contrast than Graphite. |
| Muted Slate | `#8c8c8c` | `--color-muted-slate` | Input borders, subtle box shadows. Used for visual separation without strong contrast. |
| Whisper Gray | `#e5e5e0` | `--color-whisper-gray` | Subtle background for disabled states or secondary buttons, providing a barely-there separation. |
| Pinterest Red | `#e60023` | `--color-pinterest-red` | Primary calls-to-action (CTAs), prominent interactive elements, branding accents. It's a vibrant, eye-catching color to drive user action. |
| Idea Violet | `#9270d7` | `--color-idea-violet` | Used for specific headlines and promotional text, adding a whimsical, creative accent to key content sections. |
| Discovery Blue | `#2b48d4` | `--color-discovery-blue` | Links, some interactive states. Provides an alternative accent for action items. |
| Highlight Yellow | `#fffd92` | `--color-highlight-yellow` | Used sparingly as a background highlight, drawing attention to specific content areas without being overwhelming. |
| Impact Orange | `#fa5f2` | `--color-impact-orange` | Used as a distinct accent for callouts or special elements, providing a warm, energetic contrast. |

## Tokens — Typography

### Pin Sans — The sole typeface for all UI elements, headings, body text, and interactive components. Its consistent use across all weights and sizes creates a unified, legible, and friendly tone for the entire interface. The negative letter-spacing for all sizes gives it a compact, modern feel. · `--font-pin-sans`
- **Substitute:** Open Sans, Arial
- **Weights:** 400, 500, 600, 700, 900
- **Sizes:** 12px, 14px, 16px, 20px, 32px, 38px, 50px, 70px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** -0.0370em
- **Role:** The sole typeface for all UI elements, headings, body text, and interactive components. Its consistent use across all weights and sizes creates a unified, legible, and friendly tone for the entire interface. The negative letter-spacing for all sizes gives it a compact, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.4 | -0.52px | `--text-body` |
| body-lg | 16px | 1.5 | -0.59px | `--text-body-lg` |
| subheading | 20px | 1.4 | -0.74px | `--text-subheading` |
| heading | 32px | 1.2 | -1.18px | `--text-heading` |
| heading-lg | 38px | 1.2 | -1.41px | `--text-heading-lg` |
| display-sm | 50px | 1 | -1.85px | `--text-display-sm` |
| display | 70px | 1 | -2.59px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| inputs | 16px |
| buttons | 16px |
| navigationItems | 12px |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary CTA Button
**Role:** Call to action

Background: Pinterest Red (#e60023), Text: Jet Black (#000000), Border Radius: 16px, Padding: 6px vertical, 14px horizontal. Pin Sans 400.

### Secondary Ghost Button
**Role:** Secondary action

Background: transparent, Text: Graphite (#211922), Border: transparent, Border Radius: 0px, Padding: 0px. Used for subtle actions within forms or alongside primary CTAs.

### Hovered Secondary Button
**Role:** Secondary action (hover state)

Background: Whisper Gray (#e5e5e0), Text: Jet Black (#000000), Border Radius: 16px, Padding: 6px vertical, 14px horizontal. Used for secondary actions that provide a hover feedback.

### Header Navigation Link
**Role:** Navigation item

Text: Graphite (#211922), Background: transparent, Padding: 0px. Active states often have an underline or are represented by Pinterest Red buttons.

### Primary Navigation Link
**Role:** Main navigation item

Text: Jet Black (#000000), used within main navigation for prominent links like 'Explore', usually paired with subtle background hints on hover/active.

## Do's and Don'ts

### Do
- Prioritize Pin Sans throughout all UI elements, using its negative letter-spacing for a consistent, modern feel.
- Use Pinterest Red (#e60023) exclusively for primary calls-to-action and strong brand emphasis.
- Apply a 16px border-radius to all primary interactive elements like buttons and input fields.
- Maintain a clear visual hierarchy with Canvas White (#ffffff) as the dominant background and Graphite (#211922) as the primary text color.
- Employ the 4px base unit for all spacing decisions, translating to common increments like 4px, 8px, 16px, and 24px and section gaps up to 80px.
- Ensure headings utilize Idea Violet (#9270d7) or Jet Black (#000000) with generous spacing to command attention.

### Don't
- Avoid using highly saturated colors for large background areas; reserve vibrancy for accents and interactive elements.
- Do not introduce new typefaces; Pin Sans must be the only font family in use.
- Refrain from using hard, sharp corners; all interactive and card-like elements should embrace rounded corners, with 16px being common for buttons/inputs.
- Do not use shadows for elevation. Depth in the UI is created through changes in background color and generous spacing.
- Avoid decorative gradients; rely on solid colors and imagery for visual richness.
- Do not use default browser link colors (e.g., blue #0000ee); all links should be styled with Discovery Blue (#2b48d4), Graphite (#211922), or Jet Black (#000000).

## Imagery

This site features a dynamic mix of product photography, lifestyle photography, and abstract graphics, all contained and often masked into organic, squishy shapes or perfect circles (like the hero images). Photography is typically high-key, vibrant, and product-focused, showcasing diverse subjects relevant to user interests (food, fashion, home decor). Illustrations are dimensional and often playful, integrated seamlessly into the content flow as explanatory or decorative elements. Icons are filled and simple, contributing to content clarity. Imagery's role is primarily to showcase and inspire, acting as the core content of the platform, presented densely yet with ample visual breathing room provided by the overall layout.

## Layout

The page employs a max-width centered layout for its main content sections, but the header is full-bleed. The hero section features a split layout: left-aligned headline and CTA on a white background, balanced by an overlapping collage of vibrant, masked photographic elements on the right. Section rhythm is primarily vertical stacking with clear 80px `sectionGap` between distinct content blocks, presenting information in a spacious and uncrowded manner. The site favors a clean, column-based arrangement, featuring large visual content blocks positioned alongside concise text. Navigation is via a sticky top bar, providing persistent access to search and core actions.

## Agent Prompt Guide

### Quick Color Reference
- Text: #211922 (Graphite)
- Background: #ffffff (Canvas White)
- CTA: #e60023 (Pinterest Red)
- Border (Input): #8c8c8c (Muted Slate)
- Accent (Headline): #9270d7 (Idea Violet)

### Example Component Prompts
1. Create a primary call-to-action button: background #e60023, text #000000, 16px border-radius, 6px 14px padding, Pin Sans 400.
2. Design a search input field: background #ffffff, text #000000, 1px border #8c8c8c, 16px border-radius, 11px 15px padding, Pin Sans 400.
3. Generate a main section headline: text #9270d7, Pin Sans 700 at 50px, line-height 1.0, letter-spacing -1.85px.
4. Produce a secondary ghost button: transparent background, text #211922, 0px border-radius, 0px padding, Pin Sans 400.
5. Create a standard body text paragraph: text #211922, Pin Sans 400 at 16px, line-height 1.5, letter-spacing -0.59px.

## Similar Brands

- **Instagram** — Both platforms are visually driven and emphasize content discovery through a clean, light interface, utilizing vibrant imagery and prominent CTAs for engagement.
- **Dribbble** — Similar focus on visual content display, with a clean, uncluttered layout and distinct use of brand-specific accent colors for interactive elements.
- **Airbnb** — Shares a welcoming, approachable feel with ample whitespace, rounded corners, and a focus on high-quality photography as central content, guiding users through a discovery process.
- **Canva** — Employs a bright, expansive canvas with clear typography and a dominant brand color for CTAs, encouraging creativity and interaction within a clean interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-jet-black: #000000;
  --color-graphite: #211922;
  --color-ash-gray: #666666;
  --color-muted-slate: #8c8c8c;
  --color-whisper-gray: #e5e5e0;
  --color-pinterest-red: #e60023;
  --color-idea-violet: #9270d7;
  --color-discovery-blue: #2b48d4;
  --color-highlight-yellow: #fffd92;
  --color-impact-orange: #fa5f2;

  /* Typography — Font Families */
  --font-pin-sans: 'Pin Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.52px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.59px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.74px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -1.18px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.41px;
  --text-display-sm: 50px;
  --leading-display-sm: 1;
  --tracking-display-sm: -1.85px;
  --text-display: 70px;
  --leading-display: 1;
  --tracking-display: -2.59px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 40px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-inputs: 16px;
  --radius-buttons: 16px;
  --radius-navigationitems: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-jet-black: #000000;
  --color-graphite: #211922;
  --color-ash-gray: #666666;
  --color-muted-slate: #8c8c8c;
  --color-whisper-gray: #e5e5e0;
  --color-pinterest-red: #e60023;
  --color-idea-violet: #9270d7;
  --color-discovery-blue: #2b48d4;
  --color-highlight-yellow: #fffd92;
  --color-impact-orange: #fa5f2;

  /* Typography */
  --font-pin-sans: 'Pin Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.52px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.59px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.74px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -1.18px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.41px;
  --text-display-sm: 50px;
  --leading-display-sm: 1;
  --tracking-display-sm: -1.85px;
  --text-display: 70px;
  --leading-display: 1;
  --tracking-display: -2.59px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 40px;
  --radius-full: 999px;
}
```
