# Regisgrumberg — Style Reference
> Black canvas, white light

**Theme:** dark

Regisgrumberg embraces a conceptual, dark-mode aesthetic with high contrast and stark white typography as the primary visual element. The design uses very little color, focusing instead on dynamic typographic arrangements and a sense of depth and movement created by shifting text. The overall impression is digital, experimental, and direct, with UI elements acting as functional accents rather than decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#000000` | `--color-deep-space` | Page backgrounds, text for certain components, primary canvas |
| Star Dust | `#ffffff` | `--color-star-dust` | Primary text, interactive elements, accent borders, and background for featured interactive elements |
| Ghost Gray | `#c4c4c4` | `--color-ghost-gray` | Secondary text, subtle borders, and inactive UI elements |
| Iron Oxide | `#363636` | `--color-iron-oxide` | Subtle surface variation for navigation or secondary containers |

## Tokens — Typography

### monospace — Functional text, small labels, code snippets. Its fixed-width character reinforces a technical, structured feel. · `--font-monospace`
- **Substitute:** 'IBM Plex Mono', 'Fira Code', 'JetBrains Mono'
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.00, 1.20
- **Letter spacing:** normal
- **Role:** Functional text, small labels, code snippets. Its fixed-width character reinforces a technical, structured feel.

### Times — Likely used for specific stylistic text or as a fallback; its serif nature would provide a high contrast to the primary sans-serifs, creating visual tension. · `--font-times`
- **Substitute:** 'Times New Roman', 'Georgia'
- **Weights:** 400
- **Sizes:** 
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Likely used for specific stylistic text or as a fallback; its serif nature would provide a high contrast to the primary sans-serifs, creating visual tension.

### Montserrat — General body text and subheadings. Its clean, geometric form provides excellent readability against dark backgrounds. · `--font-montserrat`
- **Substitute:** 'Inter', 'Lato'
- **Weights:** 400, 600
- **Sizes:** 11px, 14px, 18px, 24px, 30px, 36px
- **Line height:** 1.00, 1.20, 2.78
- **Letter spacing:** normal
- **Role:** General body text and subheadings. Its clean, geometric form provides excellent readability against dark backgrounds.

### Anton — Bold, impactful headlines and display text. Its condensed and heavy style demands attention, creating strong typographic statements. · `--font-anton`
- **Substitute:** 'Oswald', 'Impact'
- **Weights:** 500
- **Sizes:** 18px, 24px, 48px, 90px, 150px
- **Line height:** 1.00, 1.20
- **Letter spacing:** normal
- **Role:** Bold, impactful headlines and display text. Its condensed and heavy style demands attention, creating strong typographic statements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1 | — | `--text-caption` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 30px | 1.2 | — | `--text-heading` |
| heading-lg | 36px | 1.2 | — | `--text-heading-lg` |
| display | 150px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 23 | 23px | `--spacing-23` |
| 42 | 42px | `--spacing-42` |
| 54 | 54px | `--spacing-54` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| circle | 100% |
| elements | 2px |

### Layout

- **Page max-width:** 100px
- **Section gap:** 42px
- **Card padding:** 23px
- **Element gap:** 23px

## Components

### Text Only Button - default
**Role:** Minimal interactive element, common for navigation or secondary actions.

Background: transparent (rgba(0,0,0,0)), Text: Deep Space (#000000), Border: none, Radius: 0px, Padding: 0px.

### Text Only Button - ghost
**Role:** Minimal interactive element for navigation or secondary actions on dark backgrounds.

Background: transparent (rgba(0,0,0,0)), Text: Ghost Gray (#c4c4c4), Border: none, Radius: 0px, Padding: 0px.

### Circular Interactive Button
**Role:** Prominent interactive element for primary calls to action, like 'Enter'.

Background: Star Dust (#ffffff), Text: Deep Space (#000000), Border: none, Radius: 100%, Padding: 0px. The tight padding implies only text inside the circle.

### Navigation Link
**Role:** Interactive text link within navigation areas.

Text: Deep Space (#000000), typically uses Montserrat or monospace font families.

### Hero Headline
**Role:** Dominant display text for main page sections.

Font: Anton, sizes from 48px to 150px, weight 500, lineHeight 1.0 or 1.2, Text: Star Dust (#ffffff).

### Body Text
**Role:** Standard paragraph text.

Font: Montserrat, size 14px or 18px, weight 400, lineHeight 1.2 or 2.78, Text: Ghost Gray (#c4c4c4).

### Small Text / Caption
**Role:** Small descriptive text or labels.

Font: monospace, size 13px, weight 400, lineHeight 1.0 or 1.2, Text: Ghost Gray (#c4c4c4).

## Do's and Don'ts

### Do
- Use Deep Space (#000000) as the predominant background color for all page sections.
- Employ Star Dust (#ffffff) for all primary text, headlines, and interactive elements for maximum contrast.
- Utilize Montserrat for general body copy and subheadings, adjusting weight between 400 and 600 for emphasis.
- Apply Anton font for all impactful headlines, using its large sizes (48px, 90px, 150px) to command attention.
- Maintain a spacious density with element and section gaps centered around 23px and 42px respectively.
- For primary call-to-action buttons, use the Circular Interactive Button style: Star Dust (#ffffff) background with Deep Space (#000000) text and a 100% border radius.
- All interactive elements should have 0px border radius and 0px padding unless a specific component dictates otherwise (e.g., circular button).

### Don't
- Avoid introducing additional saturated colors unless explicitly for a semantic state (which are not defined in this system).
- Do not use subtle gradients or complex shadows for elevation; keep surfaces mostly flat and rely on typographic hierarchy and spaciousness.
- Refrain from using Times font for general UI; reserve it for specific decorative or content-driven contexts, if at all.
- Do not use generic square buttons; default to text-only or the prescribed circular button for primary actions.
- Avoid heavy borders or dividers; rely on color contrast and spacing to define UI areas.
- Do not vary letter-spacing; all typography uses normal letter-spacing unless explicitly stated.
- Do not allow text elements to be set with a background color different from the main surface color, maintaining high contrast.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space Canvas | `#000000` | Primary page background and default surface for most content. |
| 1 | Iron Oxide Secondary | `#363636` | Subtle background for UI elements like navigation bars, providing minimal differentiation. |
| 2 | Star Dust Interactive | `#ffffff` | Background for isolated interactive elements like circular buttons, creating a focal point. |

## Imagery

The site uses minimal imagery, focusing almost exclusively on text as its primary visual element. The interactive spiral typography on the hero is the main graphical feature, transforming text into a dynamic visual. If any imagery were to be introduced, it should be highly conceptual, abstract, or purely functional (e.g., product screenshots) to align with the stark, high-contrast, text-dominant aesthetic. There is no evidence of photography, illustrative styles, or icons on the provided page, suggesting a preference for type over traditional imagery.

## Layout

The page primarily utilizes a full-bleed dark canvas, with content structured in a max-width of 100px indicated for certain sections, giving a very tight and controlled inner content area or implying highly specific contextual layouts given the overall page width. The hero features a centered, interactive typographic element. Sections appear to flow seamlessly with consistent vertical spacing and no distinct visual dividers. The overall density is spacious, contrasting minimal content against a vast, dark background.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #000000
accent: #ffffff
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Deep Space (#000000) background. Headline 'WEIRD WEBSITE' using Anton font, 90px, weight 500, lineHeight 1.0, Star Dust (#ffffff) text.
Create a navigation link: 'WORK' using Montserrat font, 18px, weight 400, lineHeight 1.2, Deep Space (#000000) text (on a lighter surface if applicable, otherwise Star Dust).
Create a primary 'ENTER' button: Star Dust (#ffffff) background, Deep Space (#000000) text centered, 100% border-radius, using Montserrat font, 13px, weight 400.
Create a body text block: Ghost Gray (#c4c4c4) text, Montserrat font, 14px, weight 400, lineHeight 2.78, with 23px padding-top, 42px padding-right and padding-left, centered horizontally.

## Similar Brands

- **Awwwards** — High contrast, experimental typography, and dark mode UI with a focus on interactive elements.
- **Bruno Simon** — Extremely interactive and code-driven portfolio sites that prioritize unconventional navigation and strong typographical presence.
- **Locomotive** — Dark-mode, high-contrast visual identity with bold typography and a modern, often animation-heavy feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #000000;
  --color-star-dust: #ffffff;
  --color-ghost-gray: #c4c4c4;
  --color-iron-oxide: #363636;

  /* Typography — Font Families */
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-anton: 'Anton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 150px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-12: 12px;
  --spacing-23: 23px;
  --spacing-42: 42px;
  --spacing-54: 54px;
  --spacing-108: 108px;

  /* Layout */
  --page-max-width: 100px;
  --section-gap: 42px;
  --card-padding: 23px;
  --element-gap: 23px;

  /* Border Radius */
  --radius-sm: 2px;

  /* Named Radii */
  --radius-circle: 100%;
  --radius-elements: 2px;

  /* Surfaces */
  --surface-deep-space-canvas: #000000;
  --surface-iron-oxide-secondary: #363636;
  --surface-star-dust-interactive: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #000000;
  --color-star-dust: #ffffff;
  --color-ghost-gray: #c4c4c4;
  --color-iron-oxide: #363636;

  /* Typography */
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-anton: 'Anton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 150px;
  --leading-display: 1;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-23: 23px;
  --spacing-42: 42px;
  --spacing-54: 54px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-sm: 2px;
}
```
