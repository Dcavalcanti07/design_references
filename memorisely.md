# Memorisely — Style Reference
> Whiteboard Clarity, focused on sharp text and understated components.

**Theme:** light

Memorisely presents a clean, productivity-focused interface with a strong sense of clarity. The visual language emphasizes crisp typography, a muted, near-achromatic palette, and subtle elevation primarily through soft, almost invisible borders and minimal shadows. Component shapes lean towards softened rectangles and generous 'pill' forms, creating an approachable yet structured feel. The design system prioritizes content legibility and functional interaction over decorative flair, with a sparse use of color limited to text links and one distinct button style that appears as a muted accent.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page and card backgrounds, button fills |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Primary text, strong headings, icon fills |
| Paper White | `#faf9f6` | `--color-paper-white` | Secondary page backgrounds, subtle card surfaces |
| Smoke Gray | `#171717` | `--color-smoke-gray` | Heavy text, darker button backgrounds. Despite its dark value, it appears as more of a surface color due to context |
| Ghost Ivory | `#f2f0e9` | `--color-ghost-ivory` | Subtle border colors, secondary background distinction |
| Muted Stone | `#878787` | `--color-muted-stone` | Secondary text, descriptive body copy |
| Steel Gray | `#6e6e6e` | `--color-steel-gray` | Muted text, hairline borders, ghost button borders |
| Deep Graphite | `#414141` | `--color-deep-graphite` | Subheadings, slightly darker body text |
| Ink Black | `#212121` | `--color-ink-black` | Mid-dark body text, often for descriptive labels |
| Soft Pewter | `#c9c6bd` | `--color-soft-pewter` | Decorative illustration fill, subtle inactive states |
| Ocean Blue | `#0000ee` | `--color-ocean-blue` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Inter — The primary typeface for all content, from bold headlines to fine print. It maintains readability across various sizes and weights, with tighter tracking for larger display text and normal spacing for body text, creating a modern and efficient feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 13px, 14px, 15px, 16px, 18px, 22px, 32px, 56px
- **Line height:** 1.14, 1.23, 1.25, 1.27, 1.33, 1.38, 1.40, 1.43, 1.44, 1.45, 1.50
- **Letter spacing:** -1.68px at 56px, -1.28px at 32px, -0.48px at 16px
- **Role:** The primary typeface for all content, from bold headlines to fine print. It maintains readability across various sizes and weights, with tighter tracking for larger display text and normal spacing for body text, creating a modern and efficient feel.

### sans-serif — Fallback for system-level UI elements where specific font styling is less critical, ensuring broad compatibility. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback for system-level UI elements where specific font styling is less critical, ensuring broad compatibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 22px | 1.45 | — | `--text-subheading` |
| heading | 32px | 1.43 | -1.28px | `--text-heading` |
| display | 56px | 1.14 | -1.68px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| cards | 12px |
| small | 4px |
| medium | 8px |
| buttons | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(110, 110, 110, 0.1) 0px 0px 0px 1px, rgba(110, 110, ...` | `--shadow-subtle` |
| lg | `rgba(191, 191, 191, 0.25) 0px 1px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, dark and commanding.

Background: #171717, Text: #ffffff, Border Radius: 24px, Padding: 16px 16px. Typography: Inter 400.

### Outline Ghost Button
**Role:** Secondary action or subtle interaction button.

Background: rgba(255, 255, 255, 0), Text: #0000ee, Border: 1px solid #0000ee, Border Radius: 10px, Padding: 6px 12px. Typography: Inter 400.

### Standard Card
**Role:** Content containers for features or listings.

Background: #ffffff, Border Radius: 12px, Box Shadow: none, Padding: 16px. No visible borders, relying on background contrast.

### Hero Card
**Role:** Prominent card for showcasing key information.

Background: #faf9f6, Border Radius: 44px 44px 0px 0px (top rounded), Box Shadow: none, Padding: 40px top/right/left. Content is full width at the bottom.

### Navigation Link
**Role:** Interactive text link within navigation menus.

Text: #0000ee (for active/interactive state), otherwise #000000, Underline appears on hover/active. Typography: Inter 400.

### Small Pill Button
**Role:** Compact interactive element, often for tags or minor actions.

Background: #ffffff, Text: #0000ee, Border: 1px solid #0000ee, Border Radius: 100px, Padding: 8px 20px. Typography: Inter 400.

## Do's and Don'ts

### Do
- Use Inter for all typography, adjusting letter-spacing based on size: -1.68px for 56px text, -1.28px for 32px, and -0.48px for 16px.
- Maintain a subtle, near-achromatic palette, using Canvas White (#ffffff) for primary surfaces and Paper White (#faf9f6) for secondary backgrounds.
- Apply Charcoal Black (#000000) for primary headlines and body text to ensure strong contrast.
- Utilize Ocean Blue (#0000ee) exclusively for interactive text links and ghost button borders, making it the primary accent color.
- Employ a 24px border-radius for primary buttons like Browse bootcamps, and a generous 100px radius for compact pill-shaped elements.
- Prefer soft, contained vertical spacing: 10px for element gaps, 16px for card padding, and approximately 64px for section breaks.
- Elevate components via subtle shadow strokes like `rgba(110, 110, 110, 0.1) 0px 0px 0px 1px, rgba(110, 110, 110, 0.2) 0px 1px 0px 0px` rather than heavy dropshadows.

### Don't
- Do not introduce new saturated colors outside of the defined Ocean Blue (#0000ee) accent.
- Avoid strong, bold decorative borders on cards; prefer subtle background color shifts or nearly invisible hair-line strokes.
- Do not use dark backgrounds for large content blocks or primary navigation; the system is strongly light-themed.
- Refrain from heavy drop shadows; prefer very subtle, single-direction shadows and thin borders for visual separation.
- Do not use varied typefaces; Inter is the sole brand font, with sans-serif as a system fallback.
- Avoid overtly decorative imagery; prefer tightly cropped product or human shots, or clean, minimal icons.
- Do not create very sharp, angular components; prioritize soft, rounded corners with radii of 8px, 12px, or 24px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background, brightest surface for cards and buttons. |
| 2 | Paper White | `#faf9f6` | Secondary page and section backgrounds, providing subtle visual breaks. |
| 3 | Ghost Ivory | `#f2f0e9` | Subtle differentiators for borders or very light accents. |

## Elevation

- **Button:** `rgba(110, 110, 110, 0.1) 0px 0px 0px 1px, rgba(110, 110, 110, 0.2) 0px 1px 0px 0px`
- **Card/Other Elements:** `rgba(191, 191, 191, 0.25) 0px 1px 20px 0px`

## Imagery

Imagery primarily consists of tight product shots or candid-style photography of people engaged in work, often featuring screens or AI-related tools. These visuals are typically contained within cards with rounded corners, rather than full-bleed. Icons are outlined, minimal, and monochromatic, with a soft grey fill for decorative elements. The overall visual tone is explanatory and product-focused, with images supporting the textual content rather than dominating the layout.

## Layout

The page primarily follows a contained layout with content organized into distinct sections featuring consistent vertical spacing. The hero section is full-width with a centered headline and subtext over a plain background. Content typically alternates between stacked blocks and two-column layouts featuring text on one side and a visual on the other. Navigation is a simple top bar, with internal links leading to specific sections. The density is moderate to compact, with clear separation between content blocks.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #6e6e6e
- accent: #0000ee
- primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design an Outline Ghost Button: Background rgba(255, 255, 255, 0), text #0000ee, border 1px solid #0000ee, border-radius 10px, padding 6px vertically, 12px horizontally. Text: Inter 400.
3. Build a Standard Card: Background #ffffff, border-radius 12px, no box-shadow, padding 16px all sides. Add text using Charcoal Black (#000000) and Muted Stone (#878787).
4. Assemble a Hero Section Headline: Text 'Actionable AI Design Engineering' using Charcoal Black (#000000), Inter 56px, line-height 1.14, letter-spacing -1.68px. Below it, a subtext 'We help product designers become design engineers' using Muted Stone (#878787), Inter 18px, line-height 1.4.

## Similar Brands

- **Notion** — Shares a clean, white-space dominant interface with a focus on clear typography and functional components, using color sparingly for interaction.
- **Linear** — Exhibits strong typographic hierarchy, a mostly monochromatic palette, and subtle component styling, creating an efficient and direct user experience.
- **Gumroad** — Features a similar approach to soft, pill-shaped buttons and cards with minimal shadows, contributing to an approachable and modern aesthetic.
- **Figma** — Employs an emphasis on crisp, functional UI elements and a subtle use of color to denote interactivity and status within a primarily light theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-black: #000000;
  --color-paper-white: #faf9f6;
  --color-smoke-gray: #171717;
  --color-ghost-ivory: #f2f0e9;
  --color-muted-stone: #878787;
  --color-steel-gray: #6e6e6e;
  --color-deep-graphite: #414141;
  --color-ink-black: #212121;
  --color-soft-pewter: #c9c6bd;
  --color-ocean-blue: #0000ee;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 22px;
  --leading-subheading: 1.45;
  --text-heading: 32px;
  --leading-heading: 1.43;
  --tracking-heading: -1.28px;
  --text-display: 56px;
  --leading-display: 1.14;
  --tracking-display: -1.68px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 44px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-cards: 12px;
  --radius-small: 4px;
  --radius-medium: 8px;
  --radius-buttons: 24px;

  /* Shadows */
  --shadow-subtle: rgba(110, 110, 110, 0.1) 0px 0px 0px 1px, rgba(110, 110, 110, 0.2) 0px 1px 0px 0px;
  --shadow-lg: rgba(191, 191, 191, 0.25) 0px 1px 20px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-paper-white: #faf9f6;
  --surface-ghost-ivory: #f2f0e9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-charcoal-black: #000000;
  --color-paper-white: #faf9f6;
  --color-smoke-gray: #171717;
  --color-ghost-ivory: #f2f0e9;
  --color-muted-stone: #878787;
  --color-steel-gray: #6e6e6e;
  --color-deep-graphite: #414141;
  --color-ink-black: #212121;
  --color-soft-pewter: #c9c6bd;
  --color-ocean-blue: #0000ee;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 22px;
  --leading-subheading: 1.45;
  --text-heading: 32px;
  --leading-heading: 1.43;
  --tracking-heading: -1.28px;
  --text-display: 56px;
  --leading-display: 1.14;
  --tracking-display: -1.68px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 44px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-subtle: rgba(110, 110, 110, 0.1) 0px 0px 0px 1px, rgba(110, 110, 110, 0.2) 0px 1px 0px 0px;
  --shadow-lg: rgba(191, 191, 191, 0.25) 0px 1px 20px 0px;
}
```
