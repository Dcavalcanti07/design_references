# Mintlify — Style Reference
> Digital librarian's desk. Precise information architecture meets subtle brand identity through selective color accents.

**Theme:** light

Mintlify captures an atmosphere of serene, intelligent efficiency, like navigating a well-organized digital library. The predominant use of highly desaturated grays and stark black-on-white provides a clean, information-focused base. A single vivid green (#0c8c5e) acts as a digital beacon, highlighting interactive elements and key information without visual clutter. The visual restraint in color and a subtle elevation system communicate authority through clarity, making complex documentation feel approachable.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, core UI elements, strong contrasts against light backgrounds |
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, inverted text on dark elements |
| Coal | `#08090a` | `--color-coal` | Prominent headings, button backgrounds, elevated text |
| Platinum | `#f2f2f2` | `--color-platinum` | Subtle borders, dividers, subtle background variations |
| Steel | `#dddddd` | `--color-steel` | Thin stroke borders, less noticeable dividers |
| Sage Mark | `#0c8c5` | `--color-sage-mark` | Primary brand accent, interactive elements like CTA buttons, active states, key icons, and selected links. Its vividness provides clear visual cues in an otherwise neutral palette. |
| Emerald Glow | `#00dc8d` | `--color-emerald-glow` | Secondary accent for icons or subtle graphic highlights, complementing the primary Sage Mark. |
| Deep Cobalt | `#0052ff` | `--color-deep-cobalt` | Specific graphic elements, illustrations where a strong, vibrant blue is needed. |

## Tokens — Typography

### Inter — The sole typeface, used across all elements from headings to body text. Its clean, sans-serif design maintains legibility and a modern feel. The slight negative letter spacing on larger sizes adds a touch of sophistication to headlines, while positive spacing on smaller text ensures clarity, creating a subtly formal yet efficient tone. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 13px, 14px, 15px, 16px, 18px, 20px, 24px, 40px, 57px
- **Line height:** 1.10, 1.15, 1.30, 1.33, 1.50, 1.71
- **Letter spacing:** -0.0200em at 57px, -0.0100em at 40px/24px, 0.0500em at 13px
- **Role:** The sole typeface, used across all elements from headings to body text. Its clean, sans-serif design maintains legibility and a modern feel. The slight negative letter spacing on larger sizes adds a touch of sophistication to headlines, while positive spacing on smaller text ensures clarity, creating a subtly formal yet efficient tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.71 | 0.65px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading-sm | 20px | 1.3 | — | `--text-heading-sm` |
| heading | 24px | 1.15 | -0.24px | `--text-heading` |
| heading-lg | 40px | 1.15 | -0.4px | `--text-heading-lg` |
| display | 57px | 1.1 | -1.14px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 201 | 201px | `--spacing-201` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| cards | 16px |
| inputs | 0px |
| buttons | 1.67772e+07px |
| largeElements | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px` | `--shadow-sm` |
| sm-2 | `lab(100 0 0 / 0.05) 0px 2px 4px 0px` | `--shadow-sm-2` |

### Layout

- **Section gap:** 64px
- **Card padding:** 16-24px

## Components

### Text Link
**Role:** Navigation, inline links, secondary actions

backgroundColor=rgba(0,0,0,0), color=rgb(0,0,0) / lab(2.42579 -0.165291 -0.470081), borderRadius=16777216px, paddingTop=0px, paddingRight=0px, paddingBottom=0px, paddingLeft=0px. Appears as pure text initially, relying on context for interactivity.

### Outline Button
**Role:** Call to action, navigation items

backgroundColor=rgba(0,0,0,0), color=rgb(0,0,0), borderTopColor=rgb(0,0,0), borderRadius=4px, paddingTop=0px, paddingRight=0px, paddingBottom=0px, paddingLeft=0px. A subtle interactive element, contrasting with the filled button through its transparent background and border.

### Pill Ghost Button - Light Text
**Role:** Navigation, secondary actions on dark backgrounds

backgroundColor=rgba(0, 0, 0, 0), color=lab(100 0 0), borderTopColor=lab(100 0 0), borderRadius=1.67772e+07px, paddingTop=4px, paddingRight=12px, paddingBottom=4px, paddingLeft=12px. Used for subtle interactions, particularly within headers or on contrasting sections.

### Pill Filled Button - Dark Text
**Role:** Primary call to action in light contexts

backgroundColor=lab(100 0 0), color=lab(2.42579 -0.165291 -0.470081), borderTopColor=lab(100 0 0), borderRadius=1.67772e+07px, paddingTop=4.5px, paddingRight=12px, paddingBottom=4.5px, paddingLeft=12px. Provides strong visual emphasis for conversions when paired with a light background.

### Email Input Field
**Role:** Data entry, form submissions

backgroundColor=rgba(0, 0, 0, 0), color=lab(100 0 0), borderTopColor=lab(100 0 0), borderRadius=0px, paddingTop=0px, paddingRight=12px, paddingBottom=0px, paddingLeft=12px. A minimal input style with no background or border, relying on context and focus states for discoverability.

### Elevated Button (Light)
**Role:** Key interactive elements where a subtle lift is desired.

background: White Canvas (#ffffff), text: Coal (#08090a), shadow: lab(100 0 0 / 0.05) 0px 2px 4px 0px. This variant provides a subtle elevated visual for interactions without being visually heavy.

### Elevated Button (Dark)
**Role:** Key interactive elements on darker backgrounds where a subtle lift is desired.

background: Coal (#08090a), text: White Canvas (#ffffff), shadow: lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px. Offers elevation on darker elements, maintaining visual hierarchy.

## Do's and Don'ts

### Do
- Prioritize Inter font at all sizes and weights; use negative letter spacing on display sizes (57px: -1.14px, 40px: -0.4px) for a refined look and positive spacing (13px: 0.65px) for captions to ensure legibility.
- Use Sage Mark (#0c8c5e) exclusively for primary interactive elements, active states, and essential brand indicators to maintain its visual impact and clarity.
- Apply White Canvas (#ffffff) strictly as the default page background and for card surfaces, allowing content to breathe and accent colors to pop.
- Form inputs should be minimal, using a borderRadius of 0px and a transparent background (rgba(0,0,0,0)), allowing the surrounding design to define their presence.
- Employ the `lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px` shadow for subtle content elevation against dark backgrounds and `lab(100 0 0 / 0.05) 0px 2px 4px 0px` for light backgrounds.
- Maintain a consistent elementGap of 4px, 6px, 8px, 10px, or 12px between adjacent UI elements to ensure a harmonious and comfortable density.
- Round all buttons, and other interactive pill-shaped elements to 1.67772e+07px for a modern, distinct soft edge that contrasts with the sharper 4px and 16px radii found elsewhere.

### Don't
- Do not introduce new typefaces; rely solely on Inter to preserve the visual identity.
- Avoid using highly saturated colors other than Sage Mark (#0c8c5e) or Emerald Glow (#00dc8d) for primary UI elements; reserve others for illustrative accents only.
- Do not deviate from the specified borderRadius values (1.67772e+07px for pills, 0px for inputs, 4px for tags, 16px for cards) to maintain shape consistency.
- Do not use dark backgrounds where White Canvas (#ffffff) is expected, as this would break the light theme consistency and intended contrast ratios.
- Do not use letter-spacing: normal. Always apply precise letter-spacing according to the type scale to maintain typographic rhythm.
- Avoid excessive decoration or complex gradients on UI elements; the design emphasizes clarity and directness.
- Do not add additional shadows beyond the specified `lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px` or `lab(100 0 0 / 0.05) 0px 2px 4px 0px` to maintain a light and intentional elevation profile.

## Elevation

- **Elevated Button (Dark):** `lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px`
- **Elevated Button (Light):** `lab(100 0 0 / 0.05) 0px 2px 4px 0px`

## Imagery

The visual language for imagery leans heavily into abstract illustrations and product-focused visuals. Illustrations feature soft-edged, almost cloud-like shapes with subtle gradients and muted colors (like the light blue and orange clouds in the hero). Product screenshots, when present, are often cleanly cropped and contained within UI elements or cards, focusing on function. Photography is absent. Icons are typically monoline in style, either black on white or the brand's Sage Mark green, providing clear visual cues for functionality. The overall role of imagery is decorative and atmospheric in hero sections, illustrative for concepts, and clearly explanatory for product features, maintaining a text-dominant layout punctuated by strategic visual aids.

## Layout

The site uses a max-width contained layout rather than full-bleed, centering content to enhance focus. The hero section is full-width with large background illustrations, overlaid by a centered headline and call to action. Subsequent sections alternate between clear, distinct blocks with generous vertical spacing (sectionGap of ~64px). Content within sections often defaults to centered stacking or a 2-column layout with text on one side and a visual element or card grid on the other. Card grids often feature 3-5 columns. The navigation is a sticky top bar, providing persistent access without intruding on content. The overall density feels comfortable and spacious, allowing for easy readability.

## Agent Prompt Guide

### Quick Color Reference
- Text: Ink (#000000)
- Background: White Canvas (#ffffff)
- CTA Primary: Sage Mark (#0c8c5e)
- Border Subtle: Platinum (#f2f2f2)
- Heading: Coal (#08090a)

### 3-5 Example Component Prompts
1. Create a Hero Section: Background with abstract cloud illustration. Centered headline 'The Intelligent Knowledge Platform' in Inter weight 600, size 57px, Coal (#08090a), letterSpacing -1.14px. Subhead below it 'Helping teams create and maintain world-class documentation built for both humans and AI' in Inter weight 400, size 18px, Ink (#000000). Below that, a horizontal stack of an Email Input Field on left with a Pill Filled Button - Dark Text (White Canvas background, Coal text) on the right.
2. Create a Navigation Bar: Background White Canvas (#ffffff). Logo 'mintlify' Sage Mark (#0c8c5e). Top-right navigation links: 'Resources', 'Documentation', 'Customers', 'Blog', 'Pricing' as Text Links (Ink #000000). Alongside 'Contact sales' as an Outline Button, and 'Start for free' as a Pill Filled Button - Dark Text (White Canvas background, Coal text, borderRadius 1.67772e+07px, paddingTop 4.5px, paddingRight 12px).
3. Create a Feature Card: White Canvas (#ffffff) background, borderRadius 16px. Padding 24px all sides. Headline 'Quickstart Guide' in Inter weight 600, size 24px, Coal (#08090a). Body text beneath 'Start building intelligent documentation in five minutes' in Inter weight 400, size 16px, Ink (#000000).

## Similar Brands

- **Vercel** — Similar developer-tool aesthetic with strong type hierarchy, minimal use of color, and high-contrast text on clean backgrounds.
- **Linear** — Shares the clean, modern interface with a focus on functionality, precise typography, subtle greys, and reliance on a single, vibrant accent color for interaction.
- **Stripe** — Employs an emphasis on clear, legible typography, strong content organization on a predominantly white background, and strategic use of photography/illustration.
- **Notion** — Features a very clean, structured UI with minimal design elements, focusing on content density and information architecture over heavy visual styling.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-coal: #08090a;
  --color-platinum: #f2f2f2;
  --color-steel: #dddddd;
  --color-sage-mark: #0c8c5;
  --color-emerald-glow: #00dc8d;
  --color-deep-cobalt: #0052ff;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.71;
  --tracking-caption: 0.65px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.4px;
  --text-display: 57px;
  --leading-display: 1.1;
  --tracking-display: -1.14px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-201: 201px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16-24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-cards: 16px;
  --radius-inputs: 0px;
  --radius-buttons: 1.67772e+07px;
  --radius-largeelements: 24px;

  /* Shadows */
  --shadow-sm: lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px;
  --shadow-sm-2: lab(100 0 0 / 0.05) 0px 2px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-white-canvas: #ffffff;
  --color-coal: #08090a;
  --color-platinum: #f2f2f2;
  --color-steel: #dddddd;
  --color-sage-mark: #0c8c5;
  --color-emerald-glow: #00dc8d;
  --color-deep-cobalt: #0052ff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.71;
  --tracking-caption: 0.65px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.4px;
  --text-display: 57px;
  --leading-display: 1.1;
  --tracking-display: -1.14px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-201: 201px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-sm: lab(2.42579 -0.165291 -0.470081 / 0.03) 0px 2px 4px 0px;
  --shadow-sm-2: lab(100 0 0 / 0.05) 0px 2px 4px 0px;
}
```
