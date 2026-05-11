# Superthread — Style Reference
> Whiteboard with vivid highlighter

**Theme:** light

Superthread employs a focused, productive canvas aesthetic: a light, near-white background paired with substantial dark typography. Interactions are defined by crisp borders and a singular vivid yellow accent color, signaling active states and primary calls to action through underlays and button fills. The design prioritizes visual clarity and information density, using soft, contained cards and minimal shadows to structure content without added visual weight. Typography is the workhorse, providing structure and clear hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Stormy Night | `#1d2939` | `--color-stormy-night` | Primary text, dark surface backgrounds, button background, critical borders – provides strong contrast against light canvas |
| Midnight Ink | `#101828` | `--color-midnight-ink` | Hero headlines, critical body text – for ultimate emphasis |
| Cadet Gray | `#667085` | `--color-cadet-gray` | Secondary text, muted headings, placeholder text |
| Pale Indigo | `#1d2a53` | `--color-pale-indigo` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Superthread Yellow | `linear-gradient(83deg, rgb(255, 204, 52) 0%, rgb(255, 170, 0) 100%)` | `--color-superthread-yellow` | Yellow accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Cool Stone | `#475467` | `--color-cool-stone` | Subtle background for UI elements and decorative fills |
| Canvas White | `#f9fafb` | `--color-canvas-white` | Page background, primary surface |
| Pure White | `#ffffff` | `--color-pure-white` | Card backgrounds, elevated UI surfaces, button text on dark backgrounds |
| Ash Mist | `#e4e7ec` | `--color-ash-mist` | Subtle button backgrounds, light borders, subtle dividers |
| Cloud Gray | `#F2F4F7` | `--color-cloud-gray` | Subtle background for alternating sections or input fields |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 16px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Vela Sans — Primary headings and subheadings, brand elements. Distinctive letter-spacing and varied weights give it a confident, modern feel. Semibold at 80px for display, regular and medium for subheadings and body. Includes unique font features for character variation and precise control. · `--font-vela-sans`
- **Substitute:** Inter, 'Helvetica Neue', Arial, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 80px
- **Line height:** 1.10, 1.20, 1.33, 1.40, 1.50, 1.70
- **Letter spacing:** -0.01, 0.02
- **OpenType features:** `'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** Primary headings and subheadings, brand elements. Distinctive letter-spacing and varied weights give it a confident, modern feel. Semibold at 80px for display, regular and medium for subheadings and body. Includes unique font features for character variation and precise control.

### Noto Sans — Supporting body text and informational content where a reliable, legible sans-serif is needed. · `--font-noto-sans`
- **Substitute:** Open Sans, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 16px, 18px
- **Line height:** 1.40
- **Letter spacing:** 0
- **Role:** Supporting body text and informational content where a reliable, legible sans-serif is needed.

### SF Pro Display — SF Pro Display — detected in extracted data but not described by AI · `--font-sf-pro-display`
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 16px
- **Line height:** 1.2
- **Role:** SF Pro Display — detected in extracted data but not described by AI

### gs-inter-2020-11 — gs-inter-2020-11 — detected in extracted data but not described by AI · `--font-gs-inter-2020-11`
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 15px
- **Line height:** 1.2
- **Role:** gs-inter-2020-11 — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.2 | — | `--text-body` |
| body-lg | 18px | 1.4 | — | `--text-body-lg` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 32px | 1.2 | — | `--text-heading-lg` |
| display | 80px | 1.1 | -0.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

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
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 4px |
| default | 10px |
| cardLarge | 16px |
| buttonPill | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.22) 0px 4px 30px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 40px
- **Card padding:** 25px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call to action button.

Filled with Superthread Yellow (#ffaa00), text in Stormy Night (#1d2939), 10px border radius, 13px vertical padding, 20px horizontal padding. Typography: Vela Sans, weight 600.

### Secondary Ghost Button
**Role:** Outlined button for secondary actions.

Transparent background, text in Stormy Night (#1d2939), 1px border in Stormy Night (#1d2939), 8px border radius, 8px vertical padding, 16px horizontal padding. Typography: Vela Sans, weight 600.

### Tertiary Tab Button
**Role:** Buttons for filtering or switching views, often in groups.

Ash Mist (#e4e7ec) background, text in Stormy Night (#1d2939), 10px border radius, 13px vertical padding, 20px horizontal padding. Typography: Vela Sans, weight 600.

### Navigation Link
**Role:** Interactive text link in navigation.

Text in Stormy Night (#1d2939), with an active state signified by a 3px solid underline in Superthread Yellow (#ffaa00).

### Elevated Content Card
**Role:** Used for featured content or panels requiring emphasis.

Pure White (#ffffff) background, 10px border radius, with a subtle box-shadow: rgba(0, 0, 0, 0.18) 0px 0.6px 0.6px -1.25px, rgba(0, 0, 0, 0.16) 0px 2.3px 2.3px -2.5px, rgba(0, 0, 0, 0.06) 0px 10px 10px -3.75px. Internal padding varies from 24px-25px.

### Muted Background Card
**Role:** Used for grouping related content with less visual prominence.

Transparent background with a slight tint from rgba(152, 162, 179, 0.07), 10px border radius, no shadow. Padding 25px on all sides.

### Hero Section Tab
**Role:** Interactive tab for feature selection in the hero section.

Stormy Night (#1d2939) background for active state, Pure White (#ffffff) text, 12px border radius. Inactive tabs are transparent with Stormy Night text.

## Do's and Don'ts

### Do
- Prioritize text in Stormy Night (#1d2939) or Midnight Ink (#101828) against Canvas White (#f9fafb) or Pure White (#ffffff) for readability.
- Use Superthread Yellow (#ffaa00) exclusively for primary calls to action, active navigation states, and headline underlines to maintain focus.
- Apply a default border radius of 10px to most interactive elements and cards for a consistent, soft-edged feel.
- Maintain consistent vertical spacing between sections using 'sectionGap' at 40px for a clean flow.
- Employ Vela Sans for all headings and brand-critical text, leveraging its specific letter-spacing settings and alternative glyphs ('blwf', 'cv03', 'cv04', 'cv09', 'cv11').
- Use a default elementGap of 10px for internal spacing within components and between closely related elements.
- Structure content with either Elevated Content Cards (Pure White, #ffffff, with shadow) or Muted Background Cards (transparent tinted, no shadow) based on required prominence.

### Don't
- Do not introduce new vivid colors; keep the palette disciplined around neutrals, Superthread Yellow, and hints of Pale Indigo.
- Avoid heavy shadows or gradients on surfaces except for the defined Elevated Content Card shadow style.
- Do not deviate from the specified typography families; avoid system fonts for headings and brand elements where Vela Sans is intended.
- Do not overuse Superthread Yellow; reserve it for truly primary interactions to prevent visual noise.
- Avoid arbitrary border-radius values; stick to the defined 4px, 10px, 16px, or 50px tokens.
- Do not use dark backgrounds for large content blocks; the system is optimized for a light canvas.
- Do not use letter-spacing on Noto Sans or other body text; reserve for Vela Sans headlines as specified.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#f9fafb` | Primary page background |
| 1 | Pure White | `#ffffff` | Default card backgrounds and main content panels |
| 2 | Cloud Gray | `#F2F4F7` | Alternate section backgrounds or subtle content containers |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.18) 0px 0.602187px 0.602187px -1.25px, rgba(0, 0, 0, 0.16) 0px 2.28853px 2.28853px -2.5px, rgba(0, 0, 0, 0.06) 0px 10px 10px -3.75px`
- **Product Mockup Container:** `rgba(0, 0, 0, 0.22) 0px 4px 30px 0px`

## Imagery

This system features a mix of product screenshots and abstract graphics. Product screenshots are typically contained within cards with rounded corners, showcasing the UI directly. Imagery acts as direct contextual evidence or provides a clean aesthetic, rather than heavy decorative elements. Icons are typically single-color, filled style, using Stormy Night (#1d2939) or Cadet Gray (#667085), with a moderate stroke weight. The overall density is balanced, with imagery serving an explanatory or showcase role alongside text-dominant layouts.

## Layout

The page primarily uses a contained layout with content centered within a logical maximum width (though not explicitly defined, sections imply a consistent inner container). The hero section is full-width with a centered headline and subheading, followed by interactive tabs. Content sections are typically alternating bands of Canvas White and Cloud Gray, employing a text-left/image-right or centered stack pattern. Card grids are used for features, showcasing multiple content blocks in an organized fashion. The vertical rhythm relies on consistent sectionGap values for clear separation, while navigation is a sticky top bar.

## Agent Prompt Guide

### Quick Color Reference
- text: #1d2939 (Stormy Night)
- background: #f9fafb (Canvas White)
- border: #1d2939 (Stormy Night)
- accent: #1d2a53 (Pale Indigo)
- primary action: #1d2939 (filled action)

### 3-5 Example Component Prompts
1. **Create a Hero Headline:** Centered text "Where work gets done" in Midnight Ink (#101828), Vela Sans SemiBold, size 80px, lineHeight 1.1, letter-spacing -0.01em. Underline 'done' with a 3px solid Superthread Yellow (#ffaa00) border. Include a subheading below it in Stormy Night (#1d2939), Vela Sans Regular, size 24px, lineHeight 1.33.
2. Create a Primary Action Button: #1d2939 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. **Design an Interactive Tab Group:** Two tabs. Active tab: Stormy Night (#1d2939) background, Pure White (#ffffff) text, Vela Sans SemiBold, size 16px, borderRadius 12px. Inactive tab: transparent background, Stormy Night (#1d2939) text, Vela Sans Regular, size 16px, borderRadius 12px. Both use 8px vertical padding, 16px horizontal padding.
4. **Create an Elevated Content Card:** Pure White (#ffffff) background, 10px border radius, with box-shadow rgba(0, 0, 0, 0.18) 0px 0.6px 0.6px -1.25px, rgba(0, 0, 0, 0.16) 0px 2.3px 2.3px -2.5px, rgba(0, 0, 0, 0.06) 0px 10px 10px -3.75px. Internal padding of 25px. Headline inside card: Stormy Night (#1d2939), Vela Sans SemiBold, size 24px, lineHeight 1.33.

## Similar Brands

- **Linear** — Monochromatic base with a single vibrant accent color for interaction and status, strong emphasis on crisp typography.
- **Notion** — White canvas philosophy, card-based interface, and subtle use of elevation for content organization.
- **Asana** — Productivity-focused UI with clear hierarchy, distinct primary actions, and a generally unembellished, functional aesthetic.
- **Height** — Clean, understated UI where dark text on light backgrounds is paramount, and hierarchy is managed through font weight and size rather than excessive color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-stormy-night: #1d2939;
  --color-midnight-ink: #101828;
  --color-cadet-gray: #667085;
  --color-pale-indigo: #1d2a53;
  --color-superthread-yellow: #ffaa00;
  --gradient-superthread-yellow: linear-gradient(83deg, rgb(255, 204, 52) 0%, rgb(255, 170, 0) 100%);
  --color-cool-stone: #475467;
  --color-canvas-white: #f9fafb;
  --color-pure-white: #ffffff;
  --color-ash-mist: #e4e7ec;
  --color-cloud-gray: #F2F4F7;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-vela-sans: 'Vela Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-noto-sans: 'Noto Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gs-inter-2020-11: 'gs-inter-2020-11', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: -0.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 25px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-small: 4px;
  --radius-default: 10px;
  --radius-cardlarge: 16px;
  --radius-buttonpill: 50px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 0px 4px 30px 0px;

  /* Surfaces */
  --surface-canvas-white: #f9fafb;
  --surface-pure-white: #ffffff;
  --surface-cloud-gray: #F2F4F7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-stormy-night: #1d2939;
  --color-midnight-ink: #101828;
  --color-cadet-gray: #667085;
  --color-pale-indigo: #1d2a53;
  --color-superthread-yellow: #ffaa00;
  --color-cool-stone: #475467;
  --color-canvas-white: #f9fafb;
  --color-pure-white: #ffffff;
  --color-ash-mist: #e4e7ec;
  --color-cloud-gray: #F2F4F7;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-vela-sans: 'Vela Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-noto-sans: 'Noto Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gs-inter-2020-11: 'gs-inter-2020-11', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.2;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 80px;
  --leading-display: 1.1;
  --tracking-display: -0.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 0px 4px 30px 0px;
}
```
