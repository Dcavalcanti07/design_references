# Gt-planar — Style Reference
> Midnight mainframe with glowing terminals.

**Theme:** dark

GT Planar channels 'cyberpunk utility': a deep dark canvas with vibrant, almost neon, monochromatic accents of electric violet and glowing green. Typography is hyper-controlled and precise, often uppercase, with distinct pixel-perfect white borders defining interactive elements. This creates a high-fidelity, command-line interface aesthetic where every visual element serves a clear, functional purpose in a deeply contrasted, high-tech environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Page background, primary text on bright surfaces, button text on electric purple fills, hairline borders |
| Screen White | `#ffffff` | `--color-screen-white` | Interface text, icon strokes, active state borders, text on dark surfaces, accent shadows |
| Input Dark | `#1a0014` | `--color-input-dark` | Input field backgrounds, subtle elevated surface |
| Subtle Gray | `#949494` | `--color-subtle-gray` | Muted text, inactive element borders, secondary information |
| Border Gray | `#606060` | `--color-border-gray` | Fine, utilitarian borders on neutral elements |
| Electric Violet | `#6100ff` | `--color-electric-violet` | Primary action button backgrounds, interactive text, button borders, active accents |
| Fluorescent Green | `#00ff85` | `--color-fluorescent-green` | Primary Call to Action button background, active state borders, and high-emphasis information. This provides a stark contrast to the violet |
| Deep Space Violet | `#29006c` | `--color-deep-space-violet` | Secondary action button backgrounds, elevated card surfaces with a subtle tint |
| Safety Yellow | `#fcff76` | `--color-safety-yellow` | Green outline accent for tags, dividers, and focused UI edges |
| Alert Red | `#ff003d` | `--color-alert-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Indicator Orange | `#ff8a00` | `--color-indicator-orange` | Orange outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### GT Planar — The sole typeface, GT Planar, defines the entire text hierarchy from micro-interactions to monumental headlines. Its variable weights emphasize precision and stark contrast, making it crucial for the 'cyberpunk utility' aesthetic. The wide range of sizes and letter-spacing values allows for hyper-controlled text density. · `--font-gt-planar`
- **Substitute:** Space Mono, IBM Plex Mono
- **Weights:** 300, 400, 700
- **Sizes:** 11px, 14px, 16px, 17px, 20px, 24px, 25px, 32px, 37px, 58px, 86px, 115px, 146px, 187px, 230px, 274px
- **Line height:** 0.80, 0.90, 0.95, 1.00, 1.09, 1.10, 1.14, 1.15, 1.17, 1.19, 1.20, 1.24, 1.43, 1.50, 1.63
- **Letter spacing:** -0.2000em, -0.0500em, -0.0100em, -0.0050em, 0.0050em, 0.0080em, 0.0110em, 0.0150em, 0.0200em, 0.0250em, 0.0400em, 0.0460em, 0.0500em, 0.0700em, 0.7000em
- **OpenType features:** `"kern", "ss04"; "kern", "ss01", "ss02", "ss03"; "kern", "ss01", "ss02"; "kern", "ss03", "ss04" 0; "kern", "ss01"; "kern", "ss02"; "kern", "ss03"; "kern", "lnum", "tnum"`
- **Role:** The sole typeface, GT Planar, defines the entire text hierarchy from micro-interactions to monumental headlines. Its variable weights emphasize precision and stark contrast, making it crucial for the 'cyberpunk utility' aesthetic. The wide range of sizes and letter-spacing values allows for hyper-controlled text density.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.43 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.17 | 0.015px | `--text-body-sm` |
| body | 16px | 1.15 | 0.011px | `--text-body` |
| subheading | 24px | 1.1 | 0.008px | `--text-subheading` |
| heading | 58px | 0.95 | -0.005px | `--text-heading` |
| heading-lg | 86px | 0.9 | -0.01px | `--text-heading-lg` |
| display-sm | 146px | 0.8 | -0.05px | `--text-display-sm` |
| display | 274px | 0.8 | -0.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 29 | 29px | `--spacing-29` |
| 50 | 50px | `--spacing-50` |
| 58 | 58px | `--spacing-58` |
| 100 | 100px | `--spacing-100` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| buttons | 9999px |
| default | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) 0p...` | `--shadow-subtle` |

### Layout

- **Section gap:** 25px
- **Card padding:** 25px
- **Element gap:** 5px

## Components

### Primary Action Button (Violet Fill)
**Role:** Main interactive element for actions.

Filled with Electric Violet (#6100ff), black text, no border radius, 0px padding. Focus on background color for interaction.

### Outlined Button (Violet Border)
**Role:** Secondary action or ghost button.

Transparent background, Electric Violet (#6100ff) text, Electric Violet (#6100ff) 1px border. 5px padding, 0px border-radius.

### Dark Elevated Button (Violet Border)
**Role:** Tertiary action or grouped controls.

Deep Space Violet (#29006c) background, Electric Violet (#6100ff) accent text, Electric Violet (#6100ff) 1px border. No border radius, 0px padding.

### Fluorescent Action Button
**Role:** Prominent, high-contrast call to action.

Fluorescent Green (#00ff85) background, Void Black (#000000) text, Fluorescent Green (#00ff85) 1px border. 25px top/bottom padding, 50px left/right padding, 0px border-radius.

### Text Input
**Role:** Data entry fields.

Input Dark (#1a0014) background, Screen White (#ffffff) text, Screen White (#ffffff) 1px border. No border radius, 0px padding.

### Navigation Link Outlined (Red)
**Role:** Accentuated navigation item for warnings/promotions.

Transparent background, Alert Red (#ff003d) text. Defined by a 1px Alert Red (#ff003d) border instead of a fill, 10px padding, 0px border-radius.

### Navigation Link Outlined (Yellow)
**Role:** Accentuated navigation item for warnings/promotions.

Transparent background, Safety Yellow (#fcff76) text. Defined by a 1px Safety Yellow (#fcff76) border instead of a fill, 10px padding, 0px border-radius.

## Do's and Don'ts

### Do
- Prioritize Void Black (#000000) as the dominant background color for most sections to maintain a dark, immersive theme.
- Use Electric Violet (#6100ff) only for primary interactive elements, active states, and critical information to maximize its impact.
- Employ the GT Planar typeface exclusively, varying weight and size meticulously to establish hierarchy rather than mixing font families.
- Define interactive elements with stark 1px Screen White (#ffffff) or accent-colored borders (Electric Violet #6100ff, Alert Red #ff003d, Safety Yellow #fcff76) and 0px border-radius for a precise, angular look.
- Apply negative letter-spacing for large display text and positive letter-spacing for smaller, utilitarian text to enhance the precise, engineered feel.
- Use 0px border-radius for most UI elements like buttons, inputs, and cards, reserving 9999px for small, tag-like elements.
- Construct layouts with clear, often horizontal, divisions and compact spacing to pack information densely without feeling cluttered.

### Don't
- Avoid using soft shadows or gradients that suggest depth or realism, as the system relies on stark contrasts and flat surfaces.
- Do not introduce additional font families; GT Planar is the sole typographic voice.
- Refrain from using pastel or desaturated colors; all accent colors must be vivid and highly saturated.
- Never add rounded corners to primary buttons, inputs, or cards; maintain the hard-edged aesthetic except for very specific tag-like elements.
- Do not use more than two accent colors prominently in a single view to maintain focus and prevent visual noise.
- Avoid large, unbordered blocks of color unless they serve as a full-bleed hero, instead opting for precise borders around elements.
- Do not use generic spacing values; adhere to the 4px base unit and derived tokens for compact, consistent rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000000` | Primary page background, deep void for content. |
| 1 | Input Surface | `#1a0014` | Input fields and subtly recessed interactive areas. |
| 2 | Elevated Violet Surface | `#29006c` | Background for secondary interactive elements or elevated content modules. |

## Elevation

- **Interactive Elements:** `rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) 0px 1px 0px 0px, rgb(255, 255, 255) 1px 1px 0px 0px, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset`

## Imagery

This design system uses no traditional imagery like photography or illustration. Instead, visual elements are generated dynamically, resembling wireframes or high-speed light trails, contributing to a sense of data visualization and kinetic energy. The focus is entirely on UI elements and stark typography. Icons, where present, are monochromatic outlines with sharp angles and thin strokes.

## Layout

The page model is full-bleed but features tightly controlled maximum width content areas. The hero section often utilizes a full-viewport, dynamically generated visual background with centered, stark headlines. Section rhythm is primarily seamless, with content blocks often flowing directly into one another or defined by subtle internal dividers rather than alternating background bands. Content arrangement varies from centered stacks of text to more complex, grid-based interactive elements where text and functional UI are integrated directly into the visual experience. The overall density is compact, even within the full-bleed canvas, ensuring information is readily accessible. Navigation is handled via a fixed top bar with minimal, bordered text links.

## Agent Prompt Guide

Quick Color Reference: 
text: #ffffff
background: #000000
border: #ffffff
accent: #6100ff
primary action: #6100ff (filled action)

Example Component Prompts:
Create a primary action button: Fluorescent Action Button with text 'DOWNLOAD NOW'.
Create a navigation link: Outlined Button (Violet Border) with text 'TYPETESTER'.
Create a hero section: Void Black background. Main heading at 274px GT Planar weight 700, Screen White, letter-spacing -0.20em, with a sub-heading at 58px GT Planar weight 400, Screen White, letter-spacing -0.005em. Include a Fluorescent Action Button with text 'START YOUR JOURNEY'.
Create an input field: Text Input with placeholder text 'Enter email address' in Subtle Gray (#949494) and user input in Screen White (#ffffff).

## Similar Brands

- **The Future is Type** — Shares a strong emphasis on a single, technically precise monospace/geometric typeface, using it to build an entire visual identity.
- **Hyper Island** — Employs high-contrast dark themes with vivid, sometimes neon, single-color accents for interactivity and focus.
- **Certain graphic design portfolios** — Focuses heavily on typographic experimentation and visual starkness, treating text as the primary graphic element.
- **Gandi.net** — Features a dark UI with bright, saturated key action colors and minimalist, functional design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-screen-white: #ffffff;
  --color-input-dark: #1a0014;
  --color-subtle-gray: #949494;
  --color-border-gray: #606060;
  --color-electric-violet: #6100ff;
  --color-fluorescent-green: #00ff85;
  --color-deep-space-violet: #29006c;
  --color-safety-yellow: #fcff76;
  --color-alert-red: #ff003d;
  --color-indicator-orange: #ff8a00;

  /* Typography — Font Families */
  --font-gt-planar: 'GT Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.17;
  --tracking-body-sm: 0.015px;
  --text-body: 16px;
  --leading-body: 1.15;
  --tracking-body: 0.011px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.008px;
  --text-heading: 58px;
  --leading-heading: 0.95;
  --tracking-heading: -0.005px;
  --text-heading-lg: 86px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.01px;
  --text-display-sm: 146px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.05px;
  --text-display: 274px;
  --leading-display: 0.8;
  --tracking-display: -0.2px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-50: 50px;
  --spacing-58: 58px;
  --spacing-100: 100px;
  --spacing-150: 150px;

  /* Layout */
  --section-gap: 25px;
  --card-padding: 25px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-buttons: 9999px;
  --radius-default: 0px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) 0px 1px 0px 0px, rgb(255, 255, 255) 1px 1px 0px 0px, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset;

  /* Surfaces */
  --surface-canvas: #000000;
  --surface-input-surface: #1a0014;
  --surface-elevated-violet-surface: #29006c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-screen-white: #ffffff;
  --color-input-dark: #1a0014;
  --color-subtle-gray: #949494;
  --color-border-gray: #606060;
  --color-electric-violet: #6100ff;
  --color-fluorescent-green: #00ff85;
  --color-deep-space-violet: #29006c;
  --color-safety-yellow: #fcff76;
  --color-alert-red: #ff003d;
  --color-indicator-orange: #ff8a00;

  /* Typography */
  --font-gt-planar: 'GT Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.17;
  --tracking-body-sm: 0.015px;
  --text-body: 16px;
  --leading-body: 1.15;
  --tracking-body: 0.011px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.008px;
  --text-heading: 58px;
  --leading-heading: 0.95;
  --tracking-heading: -0.005px;
  --text-heading-lg: 86px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.01px;
  --text-display-sm: 146px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.05px;
  --text-display: 274px;
  --leading-display: 0.8;
  --tracking-display: -0.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-50: 50px;
  --spacing-58: 58px;
  --spacing-100: 100px;
  --spacing-150: 150px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) 0px 1px 0px 0px, rgb(255, 255, 255) 1px 1px 0px 0px, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset;
}
```
