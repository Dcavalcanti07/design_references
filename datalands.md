# Datalands — Style Reference
> Monochromatic Canvas, Vivid Punctuation

**Theme:** dark

Datalands embraces a stark, high-contrast dark mode aesthetic, where deep black functions as a vast canvas for bold, expressive typography and selective pops of chromatic color. The design system emphasizes strong visual statements through custom, often unconventional typefaces and generously spaced layouts. Interaction elements such as buttons and inputs feature large radii, giving them a distinct soft, almost friendly, tactile quality against the severe background. Color is used sparingly but impactfully as an accent for calls to action or to highlight specific UI elements, breaking the monochrome with vibrant hues.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page backgrounds, primary text, borders, dark overlay for content visibility |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text on dark backgrounds, icon fills, card backgrounds |
| Storm Gray | `#111212` | `--color-storm-gray` | Input text and input borders on light surfaces |
| Mist | `#f3f3ef` | `--color-mist` | Input field backgrounds, light surface elements |
| Charcoal | `#3d3d3d` | `--color-charcoal` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Light Gray | `#d9d9d9` | `--color-light-gray` | Muted body text on dark backgrounds |
| Twilight Black | `#1d1a1a` | `--color-twilight-black` | Subtle dark background for distinct interactive elements or cards |
| Deep Space Blue | `#122d8b` | `--color-deep-space-blue` | Decorative illustration accents, SVG fills |
| Cyan Sky | `#94bcee` | `--color-cyan-sky` | Highlight backgrounds, brand accent for specific sections |
| Fuchsia Pulse | `#fc74dd` | `--color-fuchsia-pulse` | Primary call-to-action button background — a vibrant pop against the dark UI |
| Lava Orange | `#ff4c33` | `--color-lava-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### OZIK Black — Display headlines and hero text. The singular heavy weight and massive size create an immediate, impactful visual statement, making text into an architectural element. · `--font-ozik-black`
- **Substitute:** Black Ops One
- **Weights:** 400
- **Sizes:** 358px
- **Line height:** 0.83, 1.50
- **Letter spacing:** -0.0100em
- **Role:** Display headlines and hero text. The singular heavy weight and massive size create an immediate, impactful visual statement, making text into an architectural element.

### Basis Grotesque Pro — Primary body text, subheadings, and larger content headings. Its wide range of sizes allows it to establish clear hierarchy from detailed text to prominent section titles, maintaining a consistent, refined feel. · `--font-basis-grotesque-pro`
- **Weights:** 400
- **Sizes:** 14px, 18px, 22px, 35px, 38px, 42px, 60px, 80px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.45
- **Letter spacing:** -0.0400em, -0.0360em, -0.0100em, -0.0080em, -0.0030em, -0.0020em, 0.0200em
- **Role:** Primary body text, subheadings, and larger content headings. Its wide range of sizes allows it to establish clear hierarchy from detailed text to prominent section titles, maintaining a consistent, refined feel.

### Martian Mono — Used for navigation, metadata, labels, and specific interactive elements. The monospace nature introduces a technical, precise undertone, offering a clear contrast to the more expressive primary headings. · `--font-martian-mono`
- **Weights:** 400
- **Sizes:** 13px, 16px
- **Line height:** 1.25, 1.45
- **Letter spacing:** normal, 0.0500em, 0.1000em, -0.0500em, 0.0200em
- **Role:** Used for navigation, metadata, labels, and specific interactive elements. The monospace nature introduces a technical, precise undertone, offering a clear contrast to the more expressive primary headings.

### Martian Mono Std xLt Extra-light — Martian Mono Std xLt Extra-light — detected in extracted data but not described by AI · `--font-martian-mono-std-xlt-extra-light`
- **Weights:** 200, 600
- **Sizes:** 18px
- **Line height:** 1.4
- **Role:** Martian Mono Std xLt Extra-light — detected in extracted data but not described by AI

### Martian Mono Std xLt — Martian Mono Std xLt — detected in extracted data but not described by AI · `--font-martian-mono-std-xlt`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.45
- **Letter spacing:** -0.05
- **Role:** Martian Mono Std xLt — detected in extracted data but not described by AI

### Martian Mono Nr xLt — Martian Mono Nr xLt — detected in extracted data but not described by AI · `--font-martian-mono-nr-xlt`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** Martian Mono Nr xLt — detected in extracted data but not described by AI

### Martian Mono Extra-light — Martian Mono Extra-light — detected in extracted data but not described by AI · `--font-martian-mono-extra-light`
- **Weights:** 200
- **Sizes:** 12px
- **Line height:** 1
- **Role:** Martian Mono Extra-light — detected in extracted data but not described by AI

### Martian Mono ExtraLight — Martian Mono ExtraLight — detected in extracted data but not described by AI · `--font-martian-mono-extralight`
- **Weights:** 400
- **Sizes:** 15px
- **Line height:** 1.25
- **Letter spacing:** 0.02
- **Role:** Martian Mono ExtraLight — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | 0.05px | `--text-caption` |
| body | 14px | 1.45 | -0.003px | `--text-body` |
| body-lg | 18px | 1.4 | -0.008px | `--text-body-lg` |
| heading-sm | 22px | 1.25 | -0.01px | `--text-heading-sm` |
| heading | 35px | 1.25 | -0.036px | `--text-heading` |
| heading-lg | 60px | 1.2 | -0.04px | `--text-heading-lg` |
| display | 358px | 0.83 | -0.01px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 38 | 38px | `--spacing-38` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 30px |
| links | 30px |
| inputs | 96px |
| buttons | 96px |
| decorativeElements | 300px |

### Layout

- **Section gap:** 80px
- **Card padding:** 48px
- **Element gap:** 10px

## Components

### Ghost Navigation Button
**Role:** Navigation and secondary actions.

Transparent background with #000000 text. Padding: 10px vertical, 4px horizontal. No border, no border-radius. Minimalist, designed to blend with the background until hovered.

### Primary Action Button
**Role:** Key interaction calls to action.

Solid #fc74dd background with #3d3d3d text. Padding: 48px vertical, 36px horizontal. Large border-radius of 96px creates a pill-shaped button. High contrast and soft edges for prominent actions.

### Dark Overlay Button
**Role:** Interactive elements within dark sections, often containing media.

Semi-transparent dark background rgba(56, 50, 50, 0.51) with #000000 text. No padding, no border. Small 8px border-radius. Subtly interactive.

### Circular Link Button
**Role:** Decorative and functional links, often with icons.

Transparent background, #0000ee text (browser default). Large border-radius of 300px, making it circular. Generous 48px padding creates a substantial clickable area. Used for eye-catching navigation.

### Pill Input Field
**Role:** Data entry fields requiring user input.

#f3f3ef background, #111212 text and border. Padding: 48px vertical, 36px horizontal. Large border-radius of 96px for a soft, pill-shaped input. The light background stands out against the dark canvas.

## Do's and Don'ts

### Do
- Prioritize #000000 as the dominant background for most sections to maintain the system's dark theme.
- Use OZIK Black at its largest sizes for hero text and major headings, establishing text as a monumental visual element.
- Apply 96px border-radius to all primary interactive elements like buttons and input fields for a soft, pill-like aesthetic.
- Emphasize actions with the #fc74dd Fuchsia Pulse as a vibrant background color for primary CTA buttons.
- Utilize Martian Mono for all navigation items, labels, and meta-information to introduce a technical, structured feel.
- Ensure generous vertical spacing between sections, using at least '80px' sectionGap for a comfortable, uncrowded layout.
- Use #ffffff for primary titles and body text against dark backgrounds, ensuring maximum contrast and readability.

### Don't
- Avoid using light backgrounds extensively; the system relies on a predominantly dark canvas.
- Do not use subtle variations of gray for backgrounds; maintain the stark contrast between #000000 and the few light elements.
- Do not introduce small, sharp-edged buttons or input fields; maintain the generous 96px border-radius for softness.
- Avoid generic sans-serif fonts for display or body text; the custom typefaces are integral to the brand's unique voice.
- Do not use muted or desaturated colors for primary calls to action; vibrancy is key for accent colors.
- Do not clutter layouts; maintain ample elementGap and cardPadding for clear, purposeful visual hierarchy.
- Avoid using default browser link colors unless specifically for unstyled, secondary links within body text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#000000` | Dominant background for the entire application, creating a deep, immersive dark mode. |
| 1 | Input Surface | `#f3f3ef` | Background for interactive input fields, providing clear contrast against the dark canvas. |
| 2 | Actionable Surface | `#1d1a1a` | Background for certain interactive elements or cards, offering a slight visual elevation from the canvas. |

## Imagery

The visual language for imagery is minimal and functional. Photography is not present. Illustrations appear as abstract, geometric shapes (circles, rectangles) with bold, vivid colors (like neon green or orange) on dark backgrounds, often used as data visualizations. Icons are simple, outlined, and monochromatic (white on black or black on colored backgrounds) with a medium stroke weight. Imagery serves primarily as explanatory content or decorative atmosphere, providing visual interest without distracting from the highly typographic focus. Image density is low, making way for ample negative space and large typography.

## Layout

The page maintains a full-bleed dark canvas, with content primarily flowing vertically. The hero section features monumental, centered typography over a stark black background. Subsequent sections follow a rhythm of consistent vertical spacing, creating an uncrowded feel. Content arrangement often appears as centered stacks of text, or less frequently, as split sections with text and abstract visuals. There's a subtle grid usage for showcasing case studies or features, often within a card-like structure. Navigation is a minimalist top bar, displaying concise information and subtle interactive elements, ensuring the main content remains the focus.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #111212 (for inputs), #000000 (for ghost buttons)
accent: #fc74dd
primary action: #fc74dd (filled action)

Example Component Prompts:
1. Create a hero section: #000000 background. Centered headline 'Datalands' at 358px OZIK Black weight 400, #ffffff, letter-spacing -0.01em. Top-right 'Let’s talk' button: #fc74dd background, #3d3d3d text, 96px border-radius, 48px vertical/36px horizontal padding.
2. Create an input field: #f3f3ef background, #111212 text and border, 96px border-radius, 48px vertical/36px horizontal padding. Placeholder text in Martian Mono weight 200, 18px.
3. Create a secondary navigation link: Transparent background, #000000 text, 10px vertical/4px horizontal padding, no border, no border-radius. Font is sans-serif 12px weight 400.

## Similar Brands

- **Awwwards** — Extensive use of dark modes, large impactful typography, and experimental layouts for visual impact.
- **Build with Assembly** — Strong emphasis on custom, bold fonts, deep dark backgrounds, and selective use of vibrant accent colors for CTA.
- **Locomotive Agency** — Combination of dark aesthetic with oversized, custom typography and a focus on visual storytelling through unique graphic elements.
- **Superlist** — Minimalist UI, focus on functional typography and generous spacing, with subtle interactive elements on a dark theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-storm-gray: #111212;
  --color-mist: #f3f3ef;
  --color-charcoal: #3d3d3d;
  --color-light-gray: #d9d9d9;
  --color-twilight-black: #1d1a1a;
  --color-deep-space-blue: #122d8b;
  --color-cyan-sky: #94bcee;
  --color-fuchsia-pulse: #fc74dd;
  --color-lava-orange: #ff4c33;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ozik-black: 'OZIK Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-grotesque-pro: 'Basis Grotesque Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-std-xlt-extra-light: 'Martian Mono Std xLt Extra-light', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-std-xlt: 'Martian Mono Std xLt', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-nr-xlt: 'Martian Mono Nr xLt', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-extra-light: 'Martian Mono Extra-light', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-extralight: 'Martian Mono ExtraLight', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.05px;
  --text-body: 14px;
  --leading-body: 1.45;
  --tracking-body: -0.003px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.008px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 35px;
  --leading-heading: 1.25;
  --tracking-heading: -0.036px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.04px;
  --text-display: 358px;
  --leading-display: 0.83;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 48px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 18px;
  --radius-3xl: 30px;
  --radius-3xl-2: 34px;
  --radius-full: 49px;
  --radius-full-2: 60px;
  --radius-full-3: 96px;
  --radius-full-4: 300px;

  /* Named Radii */
  --radius-cards: 30px;
  --radius-links: 30px;
  --radius-inputs: 96px;
  --radius-buttons: 96px;
  --radius-decorativeelements: 300px;

  /* Surfaces */
  --surface-base-canvas: #000000;
  --surface-input-surface: #f3f3ef;
  --surface-actionable-surface: #1d1a1a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ghost-white: #ffffff;
  --color-storm-gray: #111212;
  --color-mist: #f3f3ef;
  --color-charcoal: #3d3d3d;
  --color-light-gray: #d9d9d9;
  --color-twilight-black: #1d1a1a;
  --color-deep-space-blue: #122d8b;
  --color-cyan-sky: #94bcee;
  --color-fuchsia-pulse: #fc74dd;
  --color-lava-orange: #ff4c33;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ozik-black: 'OZIK Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-grotesque-pro: 'Basis Grotesque Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-std-xlt-extra-light: 'Martian Mono Std xLt Extra-light', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-std-xlt: 'Martian Mono Std xLt', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-nr-xlt: 'Martian Mono Nr xLt', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-extra-light: 'Martian Mono Extra-light', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-martian-mono-extralight: 'Martian Mono ExtraLight', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --tracking-caption: 0.05px;
  --text-body: 14px;
  --leading-body: 1.45;
  --tracking-body: -0.003px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.008px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 35px;
  --leading-heading: 1.25;
  --tracking-heading: -0.036px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.04px;
  --text-display: 358px;
  --leading-display: 0.83;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 18px;
  --radius-3xl: 30px;
  --radius-3xl-2: 34px;
  --radius-full: 49px;
  --radius-full-2: 60px;
  --radius-full-3: 96px;
  --radius-full-4: 300px;
}
```
