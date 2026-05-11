# Hex — Style Reference
> Analytical Clarity on Canvas: A pristine digital workspace where data takes center stage, framed by muted sophistication and precise typography.

**Theme:** light

Hex delivers a sophisticated, data-centric aesthetic, characterized by a clean white canvas that highlights nuanced typography and subtle violet accents. The design balances precise information display with hints of visual depth through soft shadows and varied typefaces. Interactive elements are thoughtfully understated, relying on outlines and muted states rather than bold fills, ensuring the focus remains on the analytical content and user workflow.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fffcfc` | `--color-canvas-white` | Page background, card backgrounds, input fields, primary surfaces — the foundational light backdrop for all content |
| Obsidian Ink | `#01011b` | `--color-obsidian-ink` | Primary text, informational UI elements, card outlines, dark surface accents — a deep, muted violet-black that anchors primary content |
| Eggplant Gray | `linear-gradient(90deg, rgb(49, 38, 59) 0%, rgb(1, 1, 27) 100%)` | `--color-eggplant-gray` | Secondary text, subtle borders, navigation text, and outlined button borders — a dark, desaturated gray with a hint of violet providing subtle contrast; Background for rich data visualization or complex interactive panels, providing a deep, immersive context |
| Charcoal Grey | `#14141c` | `--color-charcoal-grey` | Headings, strong text, navigation text, prominent borders — a slightly warmer, very dark gray for emphasis |
| Cement Gray | `#717a94` | `--color-cement-gray` | Muted helper text, secondary icon fills, faint dividing lines — a cool, light grey for low-emphasis elements |
| Dusk Violet | `#43394c` | `--color-dusk-violet` | Subtle borders, navigation items, descriptive text — a mid-tone desaturated violet for a sense of quiet authority |
| Platinum Mist | `#ecedf2` | `--color-platinum-mist` | Subtle background panels, table headers, soft dividers — a very light, cool gray for secondary surface differentiation |
| Slate Cloud | `#dbd7da` | `--color-slate-cloud` | Light borders, grid lines, subtle component separators — a pale, slightly warm gray |
| Minsk Violet | `#473982` | `--color-minsk-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Indigo Punch | `#6f63b7` | `--color-indigo-punch` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Lavender Field | `#9e91d6` | `--color-lavender-field` | Secondary data visualization, softened accents — a moderate violet for complementary data representation |
| Rose Quartz | `#f5c0c0` | `--color-rose-quartz` | Subtle indicators, decorative graphic elements — a muted red that provides a soft, warm counterpoint |
| Sunset Fade Gradient | `linear-gradient(45deg, rgb(205, 160, 165), rgb(49, 38, 59))` | `--color-sunset-fade-gradient` | Decorative graphical elements, expressive backgrounds where a dynamic color transition is desired |

## Tokens — Typography

### PP Editorial New — Display headlines — an extremely light-weight serif that creates a sense of gravitas and refined authority, setting a delicate, yet prominent tone for key brand statements. · `--font-pp-editorial-new`
- **Substitute:** Playfair Display
- **Weights:** 200
- **Sizes:** 78px
- **Line height:** 1.30
- **Letter spacing:** -0.0240em
- **Role:** Display headlines — an extremely light-weight serif that creates a sense of gravitas and refined authority, setting a delicate, yet prominent tone for key brand statements.

### PP Formula SemiExtended — Prominent marketing headlines, impactful feature titles — a bold, semi-extended sans-serif that commands attention with its strong, wide presence. · `--font-pp-formula-semiextended`
- **Substitute:** Archivo Expanded
- **Weights:** 700
- **Sizes:** 60px
- **Line height:** 1.30
- **Letter spacing:** -0.0310em
- **Role:** Prominent marketing headlines, impactful feature titles — a bold, semi-extended sans-serif that commands attention with its strong, wide presence.

### PP Formula — Section headings, key UI labels — a very bold, compact sans-serif that delivers high impact in a smaller footprint, excellent for concise titles. · `--font-pp-formula`
- **Substitute:** Archivo Black
- **Weights:** 800
- **Sizes:** 28px
- **Line height:** 1.30
- **Letter spacing:** -0.0250em
- **Role:** Section headings, key UI labels — a very bold, compact sans-serif that delivers high impact in a smaller footprint, excellent for concise titles.

### IBM Plex Sans — General body text, UI labels, subheadings, and data labels — providing legibility and versatility across various content densities and functional needs. Distinctly tight letter-spacing at larger sizes gives a modern, compact feel. · `--font-ibm-plex-sans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 16px, 20px, 24px, 26px
- **Line height:** 1.20, 1.30, 1.40, 1.60, 1.83, 2.20, 2.33
- **Letter spacing:** -0.0350em, -0.0250em
- **Role:** General body text, UI labels, subheadings, and data labels — providing legibility and versatility across various content densities and functional needs. Distinctly tight letter-spacing at larger sizes gives a modern, compact feel.

### Lato — Small text, captions, metadata, and fine print — used for subtle informational text due to its slightly condensed feel and moderate letter-spacing. · `--font-lato`
- **Substitute:** Open Sans
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 12px, 14px
- **Line height:** 1.20, 1.40, 1.83, 2.00, 2.20
- **Letter spacing:** -0.0140em
- **Role:** Small text, captions, metadata, and fine print — used for subtle informational text due to its slightly condensed feel and moderate letter-spacing.

### Cinetype — Navigation, buttons, and functional UI elements — a versatile geometric sans-serif for interactive components, ensuring clarity and crispness. Normal letter-spacing maintains readability at smaller UI sizes. · `--font-cinetype`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.00, 1.50, 1.57
- **Letter spacing:** normal
- **Role:** Navigation, buttons, and functional UI elements — a versatile geometric sans-serif for interactive components, ensuring clarity and crispness. Normal letter-spacing maintains readability at smaller UI sizes.

### IBM Plex Mono — Code snippets, data fields, and technical information — providing a consistent, fixed-width appearance crucial for displaying code and structured data clearly. · `--font-ibm-plex-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 11px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Code snippets, data fields, and technical information — providing a consistent, fixed-width appearance crucial for displaying code and structured data clearly.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | -0.14px | `--text-caption` |
| heading | 24px | 1.3 | — | `--text-heading` |
| heading-lg | 28px | 1.3 | -0.7px | `--text-heading-lg` |
| display | 78px | 1.3 | -1.872px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 96 | 96px | `--spacing-96` |
| 108 | 108px | `--spacing-108` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| badges | 9999px |
| inputs | 6px |
| buttons | 3px |
| default | 3px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(71, 57, 130, 0.1) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, ...` | `--shadow-subtle-2` |
| subtle-3 | `rgb(255, 255, 255) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgba(71, 57, 130, 0.15) 0px 0px 0px 4px` | `--shadow-subtle-4` |
| subtle-5 | `rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, ...` | `--shadow-subtle-5` |
| md | `rgba(0, 0, 0, 0.05) 0px 0px 11px 0px inset, rgba(0, 0, 0,...` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 70px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Action button

Transparent background with a 1px Eggplant Gray (#31263b) border, 3px corner radius, and Obsidian Ink (#01011b) text. Padding is 9.6px vertical and 13.6px horizontal, using Cinetype font at 16px.

### Standard Card
**Role:** Information container

Canvas White (#fffcfc) background with a 6px border radius, featuring a layered shadow: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px (thin border), rgba(49, 38, 59, 0.09) 0px 103px 103px 0px (large, distant shadow), rgba(49, 38, 59, 0.1) 0px 26px 57px 0px (closer, softer shadow). No internal padding indicated by default.

### Modal Card
**Role:** Interactive container

Frosted Canvas White (rgba(253, 253, 253, 0.4)) background with a larger 12px border radius. This card uses a complex, soft, multi-layered shadow with an inset #000000 shadow for depth, suggesting a floating, ethereal quality. Internal padding of 38px vertical and 45px horizontal defines its content area.

### Text Input
**Role:** Data entry

Transparent background, Obsidian Ink (#01011b) text and 1px border, with a 6px border radius. Internal padding is 12px on all sides, ensuring ample space for input. Focus states are indicated by an inset white shadow.

### Nav Button
**Role:** Navigation link

Transparent background, Eggplant Gray (#31263b) text, with Cinetype font at 16px. Implicitly, interaction involves a border change or background fill, as seen on the 'Get Started' button when hovered/active.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#fffcfc) for all primary backgrounds to maintain a clean, expansive aesthetic.
- Use Obsidian Ink (#01011b) for primary body text and most UI elements, reserving Charcoal Grey (#14141c) for headings.
- Apply Eggplant Gray (#31263b) as the default border color for outlined elements and secondary text.
- Utilize Minsk Violet (#473982) sparingly for accents, interactive states, and to highlight key application functionality.
- Ensure all cards use a 6px border radius and the layered shadow style: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.09) 0px 103px 103px 0px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px.
- Implement the display typography in PP Editorial New at 78px, weight 200, with -0.0240em letter-spacing for all hero headlines.
- Maintain a compact spacing density, predominantly using 8px for element gaps and 3px for general corner radii (buttons, links).

### Don't
- Avoid using bold, filled buttons unless explicitly specified for a primary action, favoring ghost buttons with Eggplant Gray (#31263b) borders.
- Do not introduce strong, saturated colors unless they are part of the defined brand or accent palette, maintaining the subdued aesthetic.
- Refrain from using heavily textured or patterned backgrounds; surfaces should remain clean and uniform.
- Do not deviate from the specified typefaces; the interplay of serif for display and sans-serif for UI is crucial to the brand's typographic identity.
- Avoid excessive use of heavy shadows or opaque overlays, as the system relies on subtle depth and clear separation.
- Do not use letter-spacing values greater than normal for any text, especially body or caption text, as the design uses tight tracking to aid clarity.
- Avoid 9999px radius for anything other than small tags or badges; standard components use radii of 3px, 6px, or 12px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fffcfc` | Primary page background, base surface for the entire application. |
| 1 | Platinum Mist | `#ecedf2` | Secondary background for sections, tables, and subtle content blocks, providing a slight elevation from the main canvas. |
| 2 | Frost Card | `#fffcfc` | Component surfaces, cards, and interactive elements, distinguished by subtle shadow elevation rather than color change. |

## Elevation

- **Card:** `rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.09) 0px 103px 103px 0px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px`
- **Hovered Card:** `rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px`
- **Modal/Overlay Card:** `rgba(0, 0, 0, 0.05) 0px 0px 11px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 16px 24px -8px, rgba(0, 0, 0, 0.05) 0px 8px 12px -4px, rgba(0, 0, 0, 0.05) 0px 4px 6px -2px`
- **Input Focus:** `rgb(255, 255, 255) 0px 0px 0px 1px inset`

## Agent Prompt Guide

Quick Color Reference:
text: #01011b
background: #fffcfc
border: #31263b
accent: #473982
primary action: #31263b (outlined action border)

Example Component Prompts:
1. Create a Hero Headline section: Canvas White (#fffcfc) background. Headline at 78px PP Editorial New weight 200, Obsidian Ink (#01011b), letter-spacing -1.872px. Subtext at 20px IBM Plex Sans weight 400, Eggplant Gray (#31263b), letter-spacing -0.5px. Add a ghost button: transparent background, 1px Eggplant Gray (#31263b) border, 3px radius, Cinetype font at 16px, Obsidian Ink (#01011b) text, 9.6px vertical padding, 13.6px horizontal padding.
2. Design a Feature Card: Canvas White (#fffcfc) background, 6px radius, with shadow 'rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.09) 0px 103px 103px 0px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px'. Title in Charcoal Grey (#14141c) at 24px IBM Plex Sans weight 600, body text in Obsidian Ink (#01011b) at 16px IBM Plex Sans weight 400.
3. Create a User Input Field: Canvas White (#fffcfc) background, 1px Obsidian Ink (#01011b) border, 6px radius. Placeholder text in Cement Gray (#717a94) at 16px IBM Plex Sans weight 400. Input text in Obsidian Ink (#01011b) at 16px IBM Plex Sans weight 400. 12px padding on all sides.
4. Build a Navigation Link: Text 'Products' in Eggplant Gray (#31263b) at 16px Cinetype weight 500. No background, no border. On hover, text color changes to Minsk Violet (#473982).

## Similar Brands

- **Figma** — Similar approach to clean, white interface with prominent product screenshots embedded into the UI and a focus on subtle interactive elements.
- **Linear** — Emphasizes clear typography with a blend of serif and sans-serif for distinct roles, minimalist UI patterns, and strong brand presence through content rather than heavy styling.
- **Amplitude** — Heavy use of data visualization within a light, analytical product interface, pairing a primary monospace font with a versatile sans-serif.
- **Notion** — Clear, crisp typography on a spacious white canvas, allowing content to take precedence, with functional components integrating seamlessly into the flow.
- **Vercel** — Precise, almost austere typography, with an emphasis on code and technical content within a clean, high-contrast light-mode interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fffcfc;
  --color-obsidian-ink: #01011b;
  --color-eggplant-gray: #31263b;
  --gradient-eggplant-gray: linear-gradient(90deg, rgb(49, 38, 59) 0%, rgb(1, 1, 27) 100%);
  --color-charcoal-grey: #14141c;
  --color-cement-gray: #717a94;
  --color-dusk-violet: #43394c;
  --color-platinum-mist: #ecedf2;
  --color-slate-cloud: #dbd7da;
  --color-minsk-violet: #473982;
  --color-indigo-punch: #6f63b7;
  --color-lavender-field: #9e91d6;
  --color-rose-quartz: #f5c0c0;
  --color-sunset-fade-gradient: #cd5973;
  --gradient-sunset-fade-gradient: linear-gradient(45deg, rgb(205, 160, 165), rgb(49, 38, 59));

  /* Typography — Font Families */
  --font-pp-editorial-new: 'PP Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-formula-semiextended: 'PP Formula SemiExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-formula: 'PP Formula', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lato: 'Lato', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cinetype: 'Cinetype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.14px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.7px;
  --text-display: 78px;
  --leading-display: 1.3;
  --tracking-display: -1.872px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-96: 96px;
  --spacing-108: 108px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 70px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 99px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-badges: 9999px;
  --radius-inputs: 6px;
  --radius-buttons: 3px;
  --radius-default: 3px;

  /* Shadows */
  --shadow-subtle: rgba(71, 57, 130, 0.1) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.09) 0px 103px 103px 0px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgba(71, 57, 130, 0.15) 0px 0px 0px 4px;
  --shadow-subtle-5: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 0px 11px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 16px 24px -8px, rgba(0, 0, 0, 0.05) 0px 8px 12px -4px, rgba(0, 0, 0, 0.05) 0px 4px 6px -2px;

  /* Surfaces */
  --surface-canvas-white: #fffcfc;
  --surface-platinum-mist: #ecedf2;
  --surface-frost-card: #fffcfc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fffcfc;
  --color-obsidian-ink: #01011b;
  --color-eggplant-gray: #31263b;
  --color-charcoal-grey: #14141c;
  --color-cement-gray: #717a94;
  --color-dusk-violet: #43394c;
  --color-platinum-mist: #ecedf2;
  --color-slate-cloud: #dbd7da;
  --color-minsk-violet: #473982;
  --color-indigo-punch: #6f63b7;
  --color-lavender-field: #9e91d6;
  --color-rose-quartz: #f5c0c0;
  --color-sunset-fade-gradient: #cd5973;

  /* Typography */
  --font-pp-editorial-new: 'PP Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-formula-semiextended: 'PP Formula SemiExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-formula: 'PP Formula', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lato: 'Lato', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cinetype: 'Cinetype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.14px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.7px;
  --text-display: 78px;
  --leading-display: 1.3;
  --tracking-display: -1.872px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-96: 96px;
  --spacing-108: 108px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 99px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(71, 57, 130, 0.1) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.09) 0px 103px 103px 0px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgba(71, 57, 130, 0.15) 0px 0px 0px 4px;
  --shadow-subtle-5: rgba(49, 38, 59, 0.22) 0px 0px 0px 1px, rgba(49, 38, 59, 0.1) 0px 26px 57px 0px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 0px 11px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 16px 24px -8px, rgba(0, 0, 0, 0.05) 0px 8px 12px -4px, rgba(0, 0, 0, 0.05) 0px 4px 6px -2px;
}
```
