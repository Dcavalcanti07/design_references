# Air — Style Reference
> Expansive sky, clean canvas.

**Theme:** dark

Air's design system evokes a digital canvas under an expansive, almost dreamlike sky. It marries a high-contrast dark text with clean, slightly rounded white and muted gray surfaces. Typography mixes confident, weighty statements with lighter, more fluid headings, creating a dynamic yet composed visual hierarchy. Accents are sparingly applied but impactful, often appearing as subtle outlines or functional indicators, maintaining an overall atmosphere of refined utility.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud Canvas | `#ffffff` | `--color-cloud-canvas` | Page backgrounds, elevated card surfaces, active states — acts as a luminous digital canvas that captures details |
| Midnight Ink | `#1b1b1b` | `--color-midnight-ink` | Primary text, prominent icons, dark outlined elements – provides strong contrast against lighter surfaces |
| Vapor Gray | `#f5f5f5` | `--color-vapor-gray` | Subtle background for input fields, secondary card surfaces — a soft, almost imperceptible base layer |
| Charcoal Void | `#000000` | `--color-charcoal-void` | Strongest textual contrast, borders for ghost buttons, deepest shadow effects — sparingly used for maximum impact |
| Sky Blue | `#426188` | `--color-sky-blue` | Heading accents, decorative border elements — a muted, sophisticated blue that hints at depth without being overtly bold |
| Vivid Azure | `#2b7fff` | `--color-vivid-azure` | Outlined action buttons, active link states, interactive indicators — a bright, functional blue that makes interactive elements accessible and clear |

## Tokens — Typography

### Control — Dominant body text, buttons, navigation items across various sizes. Its 500 weight provides a clear, confident voice for everyday UI. · `--font-control`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 12px, 13px, 14px, 16px, 20px
- **Line height:** 1.10, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Dominant body text, buttons, navigation items across various sizes. Its 500 weight provides a clear, confident voice for everyday UI.

### Control Compressed — Extremely large, impactful display text for hero sections or brand statements. Its compressed heavy weight creates a monumental, almost architectural feel. · `--font-control-compressed`
- **Substitute:** Oswald
- **Weights:** 900
- **Sizes:** 259px
- **Line height:** 0.85
- **Letter spacing:** normal
- **Role:** Extremely large, impactful display text for hero sections or brand statements. Its compressed heavy weight creates a monumental, almost architectural feel.

### Control Cursive — Distinctive, flowing script for stylistic flourishes, brand elements, or unique headings. Its cursive nature adds a touch of organic elegance against the structured UI. · `--font-control-cursive`
- **Substitute:** Dancing Script
- **Weights:** 400, 500
- **Sizes:** 20px, 32px, 56px
- **Line height:** 1.00, 1.10, 1.50
- **Letter spacing:** normal
- **Role:** Distinctive, flowing script for stylistic flourishes, brand elements, or unique headings. Its cursive nature adds a touch of organic elegance against the structured UI.

### Control TNT — Specialized headings and prominent body text. The name 'TNT' suggests an underlying impactful quality, used to draw attention to key messages. · `--font-control-tnt`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 20px, 32px
- **Line height:** 1.10, 1.50
- **Letter spacing:** normal
- **Role:** Specialized headings and prominent body text. The name 'TNT' suggests an underlying impactful quality, used to draw attention to key messages.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| heading | 20px | 1.5 | — | `--text-heading` |
| heading-lg | 32px | 1.1 | — | `--text-heading-lg` |
| display | 259px | 0.85 | — | `--text-display` |

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
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| images | 11px |
| inputs | 4px |
| buttons | 8px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Primary navigation and subtle calls to action.

backgroundColor: rgba(0,0,0,0), color: #ffffff, borderColor: #ffffff, borderRadius: 0px, padding: 0px 16px 0px 16px. Underlines on hover/active.

### Outlined Action Button
**Role:** Primary calls to action for interactive elements.

backgroundColor: rgba(0,0,0,0), color: #1b1b1b, borderColor: #2b7fff, borderRadius: 8px, padding: 0px 0px 0px 0px. The outline provides visual punch.

### Basic Card
**Role:** Content grouping for informational blocks with minimal visual adornment.

backgroundColor: rgba(0,0,0,0), borderRadius: 0px, boxShadow: none, padding: 0px.

### Elevated Content Card
**Role:** Card for featuring key content sections.

backgroundColor: #f5f5f5, borderRadius: 12px, boxShadow: none, padding: 20px. Uses a soft background for distinction.

### Hero Image Card
**Role:** Large, immersive card for images or visual content.

backgroundColor: rgba(0,0,0,0), borderRadius: 14px, boxShadow: none, padding: 0px.

### Standard Input Field
**Role:** User entry fields for forms.

backgroundColor: #f5f5f5, color: #1b1b1b, borderTopColor: rgba(0,0,0,0.1), borderRadius: 4px, padding: 10px.

## Do's and Don'ts

### Do
- Use 'Cloud Canvas' (#ffffff) for all main page backgrounds and elevated card surfaces.
- Apply 'Midnight Ink' (#1b1b1b) for primary text elements to ensure strong readability.
- Employ 'Control' font at 500 weight for all body text and common UI labels.
- Utilize 'Vivid Azure' (#2b7fff) exclusively for borders of primary outlined actions and active link states.
- Round corners with 8px radius for all buttons and navigation items.
- Implement a base element gap of 8px (2 base units) between most UI elements for consistent comfortable density.
- Use 'Control Compressed' at 259px size and 900 weight for high-impact display headlines to command attention.

### Don't
- Do not use saturated brand colors (#426188, #2b7fff) for large background areas or extensive text blocks.
- Avoid arbitrary border radii; stick to 4px for inputs, 8px for buttons, and 14px for significant cards.
- Do not introduce heavy drop shadows, as the system relies on subtle surface changes and crisp contrast for hierarchy.
- Refrain from using 'Charcoal Void' (#000000) for body text; reserve it for distinct headings or strong outlines.
- Do not deviate from the specified font families or weights for their intended roles to maintain typographic identity.
- Avoid tight spacing; maintain a minimum 8px element gap and 48px section gap for comfortable visual separation.
- Do not create filled primary buttons; the system emphasizes outlined chromatic actions with 'Vivid Azure' borders.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Base | `#fff8dc` | The foundational, immersive background color that gives the landing page its atmospheric feel. Note: This color is not part of the UI component system and only applies to hero/backgrounds. |
| 1 | Haze Surface | `#f5f5f5` | Subtle backgrounds for input fields and secondary card surfaces, providing a gentle lift from the page base. |
| 2 | Cloud Canvas | `#ffffff` | Primary surface for cards, modals, and other prominent UI elements, providing a clean, bright canvas against text. |

## Imagery

The site uses a mix of abstract 3D renders with soft, atmospheric gradients for hero sections, and clean, contained product screenshots for demonstrating functionality. Photography is minimal, if present. Icons are primarily outlined or ghost-style with a moderate stroke weight, often in 'Midnight Ink' or 'Cloud Canvas' to match the overall monochrome UI, with 'Vivid Azure' accents for interactive states. Imagery is generally contained within defined areas or sections, serving both atmospheric and explanatory roles without excessive layering or full-bleed treatment outside the hero.

## Layout

The overarching page layout is full-bleed, using an atmospheric gradient background behind a centered content container for most sections. The hero features an expansive full-viewport background with large, centered marketing text. Section rhythm is marked by consistent vertical spacing of 48px, often with alternating background colors or distinct visual treatments separating blocks. Content arranges into clear, often two-column text-left/visual-right sections, with features presented in grid-like structures featuring cards. Navigation is a sticky top bar with ghost buttons, transitioning to outlined buttons or color changes on interaction, maintaining a relatively minimal profile.

## Agent Prompt Guide

Quick Color Reference:
text: #1b1b1b
background: #ffffff
border: #1b1b1b
accent: #426188
primary action: #2b7fff (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #2b7fff border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Design an elevated content card: background-color: #f5f5f5, border-radius: 12px, padding: 20px. Place a 'Midnight Ink' #1b1b1b heading (Control 500, 20px, 1.5 line-height) and 'Midnight Ink' #1b1b1b body text (Control 500, 14px, 1.5 line-height) inside.
3. Implement an input field: background-color: #f5f5f5, text color: #1b1b1b, border-color: rgba(0,0,0,0.1), border-radius: 4px, padding: 10px. Placeholder text color should be a lighter neutral from the palette (e.g., a subdued gray version of #1b1b1b).
4. Create a hero section: Full-bleed background with a subtle gradient (no specific color available from tokens, suggest a light sky purple to orange, e.g., linear-gradient(135deg, #a7b7e8, #f5d7b5)). Overlay a large 'Control Compressed' 900 weight 259px headline in #1b1b1b, normal letter-spacing, line-height 0.85. Below, add a secondary 'Control Cursive' 500 weight 56px heading in #1b1b1b, normal letter-spacing, line-height 1.1.

## Similar Brands

- **Figma** — Clean white and muted gray surfaces with sharp, functional typography and a single core accent color for interactions.
- **Linear** — High-contrast text on bright backgrounds, with a focus on structured layouts and subtle use of accent colors for status or active states.
- **Notion** — Minimalist UI featuring primarily white surfaces for content creation, strong typographic hierarchy, and limited, focused use of color.
- **Coda** — Document-focused UI with clean white backgrounds, clear text, and an emphasis on structure and organized information presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-canvas: #ffffff;
  --color-midnight-ink: #1b1b1b;
  --color-vapor-gray: #f5f5f5;
  --color-charcoal-void: #000000;
  --color-sky-blue: #426188;
  --color-vivid-azure: #2b7fff;

  /* Typography — Font Families */
  --font-control: 'Control', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-compressed: 'Control Compressed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-cursive: 'Control Cursive', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-tnt: 'Control TNT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading: 20px;
  --leading-heading: 1.5;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --text-display: 259px;
  --leading-display: 0.85;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-xl: 14px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-images: 11px;
  --radius-inputs: 4px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-page-base: #fff8dc;
  --surface-haze-surface: #f5f5f5;
  --surface-cloud-canvas: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-canvas: #ffffff;
  --color-midnight-ink: #1b1b1b;
  --color-vapor-gray: #f5f5f5;
  --color-charcoal-void: #000000;
  --color-sky-blue: #426188;
  --color-vivid-azure: #2b7fff;

  /* Typography */
  --font-control: 'Control', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-compressed: 'Control Compressed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-cursive: 'Control Cursive', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-control-tnt: 'Control TNT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading: 20px;
  --leading-heading: 1.5;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --text-display: 259px;
  --leading-display: 0.85;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-xl: 14px;
}
```
