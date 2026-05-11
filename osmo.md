# Osmo — Style Reference
> high-contrast digital workbench

**Theme:** light

Osmo utilizes a developer-focused, high-contrast, 'digital workbench' aesthetic. It pairs a stark monochrome palette of deep grays and crisp whites with a single vibrant green accent, creating a commanding yet precise visual experience. Typography is assertive, featuring highly tracked, condensed headlines that establish authority. Components are minimal, relying on subtle borders and high radius to define interactive elements, maintaining a compact and functional layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#201d1d` | `--color-ink-black` | Primary text, deep surface backgrounds, dark borders for interactive elements |
| Arctic White | `#f4f4f4` | `--color-arctic-white` | Page backgrounds, light surface backgrounds, light text for dark elements |
| Concrete Gray | `#eaeaea` | `--color-concrete-gray` | Card backgrounds, input fields, subtle background elements |
| Steel Gray | `#312e2e` | `--color-steel-gray` | Mid-tone card backgrounds, borders |
| Deep Charcoal | `#151313` | `--color-deep-charcoal` | Darker card backgrounds, prominent borders |
| Pure Black | `#000000` | `--color-pure-black` | Deepest backgrounds, occasional overlays |
| Silver Mist | `#e1e1e1` | `--color-silver-mist` | Subtle light card backgrounds, list dividers |
| Light Stone | `#d8d8d8` | `--color-light-stone` | Very light borders, secondary text |
| Graphite | `#2a2727` | `--color-graphite` | Dark neutral card backgrounds |
| Warm Gray | `#4f4c4c` | `--color-warm-gray` | Secondary borders, darker backgrounds |
| Soft Gray | `#b8b8b8` | `--color-soft-gray` | Muted text, image borders |
| Electric Green | `#a1ff62` | `--color-electric-green` | Primary action indicators, active states, badges, decorative icon accents — signifies progress and activation |
| Digital Violet | `#6840ff` | `--color-digital-violet` | Secondary accent for certain card backgrounds and decorative borders, often paired with dark surfaces |
| Alert Red | `#f84131` | `--color-alert-red` | Decorative accents, occasional borders — draws attention |

## Tokens — Typography

### Haffer VF — Primary body text, subheadings, and UI labels. Its versatility in weights and slight letter spacing supports readability while maintaining a modern, structured feel. · `--font-haffer-vf`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 19px, 20px, 22px, 24px, 27px
- **Line height:** 1.00, 1.08, 1.10, 1.11, 1.20, 1.25, 1.30, 1.54, 1.56
- **Letter spacing:** -0.0200em at large sizes, becoming tighter at smaller body sizes (-0.0070em)
- **Role:** Primary body text, subheadings, and UI labels. Its versatility in weights and slight letter spacing supports readability while maintaining a modern, structured feel.

### Haffer XH — Dominant display and section headings. The extremely tight letter spacing and high weights create a commanding, almost architectural presence, making text feel like a precise, engineered component. · `--font-haffer-xh`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 20px, 40px, 44px, 48px, 62px, 64px, 80px, 112px, 150px
- **Line height:** 0.85, 0.90, 0.95, 1.00, 1.05, 1.08
- **Letter spacing:** -0.0600em at 150px, -0.0500em at 112px, -0.0400em at 80px, -0.0300em at 62px
- **Role:** Dominant display and section headings. The extremely tight letter spacing and high weights create a commanding, almost architectural presence, making text feel like a precise, engineered component.

### Haffer Mono — Used for code snippets, small labels, and data points where a fixed-width, technical aesthetic is desired. · `--font-haffer-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 9px, 11px, 12px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Used for code snippets, small labels, and data points where a fixed-width, technical aesthetic is desired.

### Brisa Pro — Decorative script headings, providing a softer, often handwritten contrast to the geometric primary fonts. Used sparingly for accent. · `--font-brisa-pro`
- **Substitute:** Dancing Script
- **Weights:** 400
- **Sizes:** 25px
- **Line height:** 0.80
- **Letter spacing:** normal
- **Role:** Decorative script headings, providing a softer, often handwritten contrast to the geometric primary fonts. Used sparingly for accent.

### -apple-system — -apple-system — detected in extracted data but not described by AI · `--font-apple-system`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Letter spacing:** -0.01
- **Role:** -apple-system — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 18px | 1.3 | -0.18px | `--text-subheading` |
| heading-sm | 24px | 1 | -0.24px | `--text-heading-sm` |
| heading | 48px | 0.95 | -1.44px | `--text-heading` |
| heading-lg | 80px | 0.9 | -3.2px | `--text-heading-lg` |
| display | 150px | 0.85 | -9px | `--text-display` |

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
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| high | 16px |
| none | 0px |
| pill | 48px |
| small | 2px |
| medium | 5px |
| circular | 1600px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button - Dark
**Role:** Secondary action or navigation link.

Transparent background with a 1px border and text in Ink Black (#201d1d). Uses 2px radius and 18px horizontal padding, with minimal vertical padding (0px top, 1px bottom) for a visually compact appearance.

### Ghost Button - Light
**Role:** Secondary action or navigation link on dark backgrounds.

Transparent background with a 1px border and text in Arctic White (#f4f4f4). Uses 2px radius and 18px horizontal padding, with minimal vertical padding (0px top, 1px bottom).

### Pill Ghost Button - Light
**Role:** Specialized secondary action, often for filters or tags.

Transparent background with a 1px border and text in Arctic White (#f4f4f4). Features a high 48px radius for a pill shape and 18px horizontal padding.

### Unstyled Link Button
**Role:** Contextual actions or text links that behave like buttons but visually integrate into body text.

No background, no borders, text in Ink Black (#201d1d), zero padding and radius. Blends into content.

### Default Card
**Role:** Content grouping, larger interactive elements.

Often transparent or Concrete Gray (#eaeaea) background with 0px radius and no shadow. Padding varies significantly but can be as large as 148px for specific sections.

### Dark Card - Rounded
**Role:** Highlighted content panels or focused interactive cards.

Deep Charcoal (#312e2e) background with a 5px border radius. Features 6px padding on three sides.

### Minimal Card
**Role:** Small feature blocks or image containers.

Transparent background with a 3px border radius and no shadow.

### Spacious Card
**Role:** Visual blocks needing internal padding for content.

Transparent background with 5px border radius. Features consistent 8px padding.

### Input Field
**Role:** Standard user input element.

Concrete Gray (#eaeaea) background with Ink Black (#201d1d) text. Has a 3px border radius and 12px vertical, 16px horizontal padding.

### Neutral Badge
**Role:** Categorization or small status indicators.

Transparent background with Arctic White (#f4f4f4) text, 2px border radius, and compact 4px vertical, 6px horizontal padding.

### Circular Badge
**Role:** Small, distinct labels, often for numbers or short tags.

Transparent background with Arctic White (#f4f4f4) text and a very high 1600px border radius for a circular or pill shape. Compact 4px vertical, 6px horizontal padding.

## Do's and Don'ts

### Do
- Prioritize a high-contrast palette using Ink Black (#201d1d) and Arctic White (#f4f4f4) as primary background and text colors.
- Use Electric Green (#a1ff62) exclusively for primary interactive elements, active states, and small functional accents.
- Apply Haffer XH for all major headlines with aggressive negative letter spacing for a sharp, technical look.
- Utilize ghost buttons with 1px borders and minimal vertical padding (e.g., 0px top, 1px bottom) as the standard button style.
- Maintain high border radii like 1600px or 48px for badges, tags, and specialized interactive elements to create soft, approachable shapes.
- Employ the 8px element gap for consistent horizontal and vertical spacing between UI components and small text blocks.
- Ensure cards use either 0px or 5px radius; avoid intermediate values for content containers.

### Don't
- Avoid using saturated colors other than Electric Green for primary UI emphasis; keep the palette largely monochrome.
- Do not use box shadows for elevation; rely on color contrast and subtle borders to define surface hierarchy.
- Do not use generic system fonts when Haffer VF or Haffer XH are available; the custom typography is a core brand element.
- Refrain from heavy, filled button styles; prefer ghost or outlined buttons to maintain a lightweight feel.
- Do not add excessive line height to headings; Haffer XH has intentionally tight line heights (e.g., 0.85-1.08) that should be respected.
- Avoid large, ornamental imagery; focus on functional visuals like product screenshots or abstract graphics that integrate clearly into the UI.
- Do not break the compact layout by adding large, irregular spacing unless explicitly for a full-bleed hero or content section.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Arctic White Canvas | `#f4f4f4` | Primary page background, expansive light areas. |
| 2 | Concrete Gray Card | `#eaeaea` | Default card and input field background, providing a subtle elevation from the canvas. |
| 3 | Silver Mist Panel | `#e1e1e1` | Secondary light card background, list backgrounds. |
| 4 | Deep Charcoal Module | `#312e2` | Darker card backgrounds, prominent content blocks for contrast. |
| 5 | Ink Black Overlay | `#201d1d` | Deepest backgrounds, navigation bars, and interactive panel backgrounds. |

## Elevation

Osmo deliberately avoids traditional box-shadows. Instead, it defines visual hierarchy and depth through sharp color contrast between distinct monochrome surfaces (e.g., Ink Black on Arctic White), combined with subtle 1px borders. Tilted component arrangements and occasional background gradients (though none are distinct enough to token) contribute to a sense of dimensional layering without relying on soft shadows, reinforcing a precise, engineered aesthetic.

## Imagery

The imagery on Osmo is primarily functional and technical, featuring tightly cropped product screenshots and code examples within a 'workbench' context. Visuals are typically contained within cards, often with a slight tilt or rotation, creating a dynamic but organized presentation. Graphics are sparse, used for subtle visual accents (like the asterisk logo) or abstract geometric shapes (like the dotted circle for 'Play Reel'). Icons are outlined, fine-stroke, monochrome, and used functionally for navigation and conceptual representation. There's a strong emphasis on showcasing the 'product' itself through high-quality, focused captures rather than lifestyle photography.

## Layout

The page primarily uses a contained, centered layout, typically with a max width, providing a stable and focused reading experience. The hero section often features a large, highly tracked headline centered over a light background, sometimes with a subtle visual texture or a floating element. Content sections frequently alternate between light (Arctic White) and dark (Ink Black) backgrounds, creating a clear visual rhythm. Content is generally arranged in stacked blocks or two-column layouts, with text on one side and a visual element (card, image) on the other. A notable pattern is the use of tilted cards for product showcases, lending a dynamic, almost 'object on a desk' feel. Navigation is handled by a fixed top bar with ghost buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #201d1d
background: #f4f4f4
border: #201d1d
accent: #a1ff62
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a feature card: Deep Charcoal (#312e2e) background, 5px radius, 6px padding all around. Headline in Haffer XH 40px weight 400, #f4f4f4, letter-spacing -1.6px. Body text in Haffer VF 16px weight 400, #b8b8b8.
4. Build an input field: Concrete Gray (#eaeaea) background, 3px radius. Placeholder text '#b8b8b8', input text #201d1d, Haffer VF 16px weight 400. Padding 12px vertical, 16px horizontal.

## Similar Brands

- **Linear** — Monochromatic interface with a single vibrant accent color for interaction and status indicators, paired with compact, technical typography.
- **Figma** — Focus on developer tooling, high-fidelity mockups, and precise UI with a strong emphasis on typography and a clean, functional aesthetic.
- **Supabase** — High-contrast dark mode with sharp typography and distinct highlight colors for code and interactive elements.
- **Vercel** — Architectural, minimal design with strong typography, ample whitespace, and a focus on essential UI elements through subtle borders rather than heavy visual adornments.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #201d1d;
  --color-arctic-white: #f4f4f4;
  --color-concrete-gray: #eaeaea;
  --color-steel-gray: #312e2e;
  --color-deep-charcoal: #151313;
  --color-pure-black: #000000;
  --color-silver-mist: #e1e1e1;
  --color-light-stone: #d8d8d8;
  --color-graphite: #2a2727;
  --color-warm-gray: #4f4c4c;
  --color-soft-gray: #b8b8b8;
  --color-electric-green: #a1ff62;
  --color-digital-violet: #6840ff;
  --color-alert-red: #f84131;

  /* Typography — Font Families */
  --font-haffer-vf: 'Haffer VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haffer-xh: 'Haffer XH', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haffer-mono: 'Haffer Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-brisa-pro: 'Brisa Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.24px;
  --text-heading: 48px;
  --leading-heading: 0.95;
  --tracking-heading: -1.44px;
  --text-heading-lg: 80px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -3.2px;
  --text-display: 150px;
  --leading-display: 0.85;
  --tracking-display: -9px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 160px;
  --radius-full-3: 220px;
  --radius-full-4: 800px;
  --radius-full-5: 1300px;
  --radius-full-6: 1600px;
  --radius-full-7: 8000px;

  /* Named Radii */
  --radius-high: 16px;
  --radius-none: 0px;
  --radius-pill: 48px;
  --radius-small: 2px;
  --radius-medium: 5px;
  --radius-circular: 1600px;

  /* Surfaces */
  --surface-arctic-white-canvas: #f4f4f4;
  --surface-concrete-gray-card: #eaeaea;
  --surface-silver-mist-panel: #e1e1e1;
  --surface-deep-charcoal-module: #312e2;
  --surface-ink-black-overlay: #201d1d;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #201d1d;
  --color-arctic-white: #f4f4f4;
  --color-concrete-gray: #eaeaea;
  --color-steel-gray: #312e2e;
  --color-deep-charcoal: #151313;
  --color-pure-black: #000000;
  --color-silver-mist: #e1e1e1;
  --color-light-stone: #d8d8d8;
  --color-graphite: #2a2727;
  --color-warm-gray: #4f4c4c;
  --color-soft-gray: #b8b8b8;
  --color-electric-green: #a1ff62;
  --color-digital-violet: #6840ff;
  --color-alert-red: #f84131;

  /* Typography */
  --font-haffer-vf: 'Haffer VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haffer-xh: 'Haffer XH', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haffer-mono: 'Haffer Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-brisa-pro: 'Brisa Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.24px;
  --text-heading: 48px;
  --leading-heading: 0.95;
  --tracking-heading: -1.44px;
  --text-heading-lg: 80px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -3.2px;
  --text-display: 150px;
  --leading-display: 0.85;
  --tracking-display: -9px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 160px;
  --radius-full-3: 220px;
  --radius-full-4: 800px;
  --radius-full-5: 1300px;
  --radius-full-6: 1600px;
  --radius-full-7: 8000px;
}
```
