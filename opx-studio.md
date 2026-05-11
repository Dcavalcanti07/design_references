# OPX Studio — Style Reference
> Deep night canvas

**Theme:** dark

OPX Studio employs a high-contrast, minimalist dark aesthetic, making content feel bold and impactful. The design prioritizes stark text-heavy layouts on a deep black canvas, with subtle gray borders and accents to define interactive elements. Photography and visuals are given prominence within these dark sections, often full-bleed. Typography is confident and direct, relying on strong weights and generous letter-spacing to command attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight | `#020202` | `--color-midnight` | Page background, primary surface for content blocks |
| Void Black | `#000000` | `--color-void-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ghost Gray | `#292a2c` | `--color-ghost-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Snow | `#ffffff` | `--color-snow` | Primary text color for headlines and body copy, hover state for ghost buttons, primary border for ghost buttons |
| Slate Mist | `#9b9b9b` | `--color-slate-mist` | Muted helper text, secondary navigation text, subtle decorative borders |

## Tokens — Typography

### Open Sans — Standard body text for descriptive content. Its common availability balances the custom typeface for readability. · `--font-open-sans`
- **Substitute:** Noto Sans
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.67
- **Letter spacing:** normal
- **Role:** Standard body text for descriptive content. Its common availability balances the custom typeface for readability.

### OPX-Medium — Headlines, navigation, main body copy, and link text where impact is needed. Its singular weight at varying sizes creates a very formal, architectural hierarchy. · `--font-opx-medium`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 18px, 20px, 26px, 35px, 50px, 80px, 111px
- **Line height:** 1.00, 1.07, 1.21, 1.29, 1.38, 1.40, 1.42, 1.73
- **Letter spacing:** normal
- **Role:** Headlines, navigation, main body copy, and link text where impact is needed. Its singular weight at varying sizes creates a very formal, architectural hierarchy.

### Untitled — Small, functional link text. Its slightly bolder weight ensures legibility even at smaller sizes in the dark theme. · `--font-untitled`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.67
- **Letter spacing:** normal
- **Role:** Small, functional link text. Its slightly bolder weight ensures legibility even at smaller sizes in the dark theme.

### Helvetica — Helvetica — detected in extracted data but not described by AI · `--font-helvetica`
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.67
- **Role:** Helvetica — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.67 | — | `--text-caption` |
| body | 18px | 1.67 | — | `--text-body` |
| subheading | 20px | 1.42 | — | `--text-subheading` |
| heading-sm | 26px | 1.4 | — | `--text-heading-sm` |
| heading | 35px | 1.38 | — | `--text-heading` |
| heading-lg | 50px | 1.29 | — | `--text-heading-lg` |
| display | 80px | 1.21 | — | `--text-display` |
| display-lg | 111px | 1 | — | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 30 | 30px | `--spacing-30` |
| 50 | 50px | `--spacing-50` |
| 80 | 80px | `--spacing-80` |
| 99 | 99px | `--spacing-99` |
| 100 | 100px | `--spacing-100` |
| 150 | 150px | `--spacing-150` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 45px |
| buttons | 45px |

### Layout

- **Section gap:** 100px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Ghost Button
**Role:** Outlined clickable element for secondary actions and case study links.

Text: Void Black (#000000), OPX-Medium 18px. Border: 1px solid Snow (#ffffff), 45px radius. Padding: 7px vertical, 30px horizontal.

### Navigation Link
**Role:** Primary navigation item.

Text: Snow (#ffffff), OPX-Medium 111px. Hover state changes text to Ghost Gray (#292a2c). No background or explicit padding, relies on high font size for separation.

### Footer Link
**Role:** Informational links in the footer.

Text: Slate Mist (#9b9b9b), Untitled 500 at 14px for main info, Open Sans 400 at 18px for social links. No distinct background or border.

### Content Card Headline
**Role:** Headline for project previews.

Text: Snow (#ffffff), OPX-Medium at 26px for project titles. Paired closely with Ghost Button below.

## Do's and Don'ts

### Do
- Always use Midnight (#020202) for primary page backgrounds to maintain the dark canvas theme.
- Utilize Snow (#ffffff) for all main headings and primary body text to ensure maximum contrast.
- Apply Ghost Gray (#292a2c) to borders and secondary interactive elements for subtle definition.
- Implement a 45px border-radius for all interactive components like buttons and cards to preserve the soft, rounded aesthetic.
- Maintain generous vertical spacing with 100px between major sections to emphasize content segmentation.

### Don't
- Avoid introducing bright or saturated colors beyond imagery, as the system relies on a high-contrast achromatic palette.
- Do not use small line heights for display typography; maintain the defined line heights for OPX-Medium to ensure strong visual impact and clarity.
- Do not use box-shadows or elevation effects, as the system achieves visual depth through color contrast and spacing.
- Never use less than 20px of padding around content within confined elements.
- Do not vary from the specific text color choices for primary or secondary text; Snow and Slate Mist define the text hierarchy.

## Imagery

The site uses high-quality, often full-bleed photography and product mockups. Imagery is typically well-lit against dark or neutral backgrounds, showcasing product UI or professional-looking scenes with a focus on human interaction. Visuals serve an explanatory or showcase role, often appearing as large blocks that break up the text. Icons are minimal, outlined, and monochromatic, integrated within the text for decorative accents or link indicators.

## Layout

The page primarily uses a max-width contained layout alternating with full-bleed sections for imagery. The hero section features a centered headline over a full-width background, setting a bold, direct tone. Content often arranges in two-column layouts, with text-left and visual-right, or stacked centered blocks. There's a subtle grid for project showcases, featuring 3-column cards. Vertical spacing between sections is consistently large, creating a spacious and intentional rhythm. Navigation is minimal, consisting of a sticky top bar with two main links.

## Agent Prompt Guide

primary action: no distinct CTA color

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight: #020202;
  --color-void-black: #000000;
  --color-ghost-gray: #292a2c;
  --color-snow: #ffffff;
  --color-slate-mist: #9b9b9b;

  /* Typography — Font Families */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-opx-medium: 'OPX-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-untitled: 'Untitled', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.67;
  --text-body: 18px;
  --leading-body: 1.67;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.4;
  --text-heading: 35px;
  --leading-heading: 1.38;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.29;
  --text-display: 80px;
  --leading-display: 1.21;
  --text-display-lg: 111px;
  --leading-display-lg: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-99: 99px;
  --spacing-100: 100px;
  --spacing-150: 150px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-3xl: 45px;

  /* Named Radii */
  --radius-cards: 45px;
  --radius-buttons: 45px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight: #020202;
  --color-void-black: #000000;
  --color-ghost-gray: #292a2c;
  --color-snow: #ffffff;
  --color-slate-mist: #9b9b9b;

  /* Typography */
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-opx-medium: 'OPX-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-untitled: 'Untitled', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.67;
  --text-body: 18px;
  --leading-body: 1.67;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.4;
  --text-heading: 35px;
  --leading-heading: 1.38;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.29;
  --text-display: 80px;
  --leading-display: 1.21;
  --text-display-lg: 111px;
  --leading-display-lg: 1;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-99: 99px;
  --spacing-100: 100px;
  --spacing-150: 150px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-3xl: 45px;
}
```
