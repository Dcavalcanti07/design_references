# Statamic — Style Reference
> Cloud-nine productivity with subtle magic.

**Theme:** light

Statamic embodies an elevated, refined productivity experience with a light, airy canvas and soft, layered card surfaces. Typography is a confident mix of a bespoke serif for large headlines, a functional sans-serif for UI, and a monospaced font for code. Subtle lavender and sky-blue accents, combined with a vibrant green for interactive elements, provide focused punctuation. The overall aesthetic balances creative expression with precise control, offering a premium feel without being overly formal.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `linear-gradient(to right bottom, rgb(51, 65, 85), rgb(25, 26, 27))` | `--color-midnight-graphite` | Primary text, surface borders, navigation background, dark section backgrounds; Hero section backgrounds, deep surface gradient |
| Cloud Canvas | `#ffffff` | `--color-cloud-canvas` | Page backgrounds, card surfaces, secondary interactive borders |
| Slate Mist | `#beb9b3` | `--color-slate-mist` | Muted body text, secondary borders, subtle shadow tint |
| Smoked Pearl | `#5e5a5a` | `--color-smoked-pearl` | Icon fills, list item text, navigation text in darker contexts |
| Stone Gray | `#c2c2c2` | `--color-stone-gray` | Hairline separators, subtle borders |
| Charcoal Text | `#4e5154` | `--color-charcoal-text` | Secondary body text, less prominent UI labels |
| Subtle Grey | `#cbd5e0` | `--color-subtle-grey` | Input borders, ghost button borders |
| Steel Gray | `#3f3f46` | `--color-steel-gray` | Subtle border accents |
| Sky Tint | `#d7e5fe` | `--color-sky-tint` | Decorative border accents, background pattern fills |
| Amethyst Aura | `#4c305a` | `--color-amethyst-aura` | Decorative shadow tinting for depth and atmosphere |
| Blush Pink | `#f5ddee` | `--color-blush-pink` | Decorative border accents, background pattern fills |
| Lavender Haze | `#cbc2ea` | `--color-lavender-haze` | Outlined button borders, focus states |
| Electric Lime | `#d4ff4c` | `--color-electric-lime` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis. Use as a supporting accent, not as a status color |
| Ambient Light Glow 1 | `linear-gradient(233deg, rgba(50, 197, 255, 0.08), rgba(182, 32, 224, 0.08) 51%, rgba(247, 181, 0, 0.08))` | `--color-ambient-light-glow-1` | Subtle background overlay for decorative atmospheric effects |

## Tokens — Typography

### p22-mackinac-pro — Display and marketing headlines – the generous tracking reduction at large sizes gives a distinctive, sophisticated air, making it feel less traditional than typical serifs. · `--font-p22-mackinac-pro`
- **Substitute:** Georgia
- **Weights:** 100, 300, 400, 700
- **Sizes:** 20px, 24px, 30px, 60px, 80px, 96px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** -0.0500em
- **Role:** Display and marketing headlines – the generous tracking reduction at large sizes gives a distinctive, sophisticated air, making it feel less traditional than typical serifs.

### Lexend — UI elements, body text, nav items, and primary buttons – a workhorse sans-serif with subtle character, providing clarity and structure throughout the interface. · `--font-lexend`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 36px
- **Line height:** 1.00, 1.11, 1.25, 1.33, 1.43, 1.50, 1.56, 1.63, 2.00
- **Letter spacing:** -0.0250em at 36px, 0.0500em at 12px
- **Role:** UI elements, body text, nav items, and primary buttons – a workhorse sans-serif with subtle character, providing clarity and structure throughout the interface.

### code-saver — Code snippets, file names, and technical content – a clear, legible monospace font essential for a developer-focused product. · `--font-code-saver`
- **Substitute:** Fira Code
- **Weights:** 300, 700
- **Sizes:** 12px, 14px, 16px, 20px
- **Line height:** 1.33, 1.43, 1.50, 2.00
- **Letter spacing:** 0em
- **Role:** Code snippets, file names, and technical content – a clear, legible monospace font essential for a developer-focused product.

### Lore — Decorative or specific content-related small text, likely for stylistic effect. · `--font-lore`
- **Substitute:** PT Serif
- **Weights:** 300
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** 0em
- **Role:** Decorative or specific content-related small text, likely for stylistic effect.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.6px | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.43 | — | `--text-body-lg` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 36px | 1.33 | -0.9px | `--text-heading-lg` |
| display-sm | 60px | 1.2 | -3px | `--text-display-sm` |
| display | 80px | 1 | -4px | `--text-display` |
| display-lg | 96px | 1 | -4.8px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 208 | 208px | `--spacing-208` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| pills | 9999px |
| buttons | 8px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.05) 0px 2px 6px -16px, rgba(0, 0, 0, 0.25...` | `--shadow-sm` |
| subtle | `rgba(0, 0, 0, 0.15) 0px 2px 3px -2px` | `--shadow-subtle` |
| subtle-2 | `rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1)...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-3` |
| sm-2 | `rgba(0, 0, 0, 0.07) 0px 2px 8px 0px, rgba(0, 0, 0, 0.05) ...` | `--shadow-sm-2` |
| xl | `rgb(76, 48, 90) 0px 11px 37px -18px` | `--shadow-xl` |
| subtle-4 | `rgb(113, 113, 122) 0px 0px 0px 1px` | `--shadow-subtle-4` |
| xl-2 | `rgb(190, 185, 179) 0px 24px 64px -12px` | `--shadow-xl-2` |
| subtle-5 | `rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgb(190, 185, 179)...` | `--shadow-subtle-5` |

### Layout

- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call to action

Background: Cloud Canvas (#ffffff), text: Midnight Graphite (#191a1b), border: 1px solid Midnight Graphite (#191a1b). Radius: 0px. Padding 32px vertical, 12px horizontal. Large, commanding presence.

### Secondary Outlined Button
**Role:** Alternative action, less emphasis

Background: transparent, text: Midnight Graphite (#191a1b), border: 1px solid Midnight Graphite (#191a1b). Radius: 0px. Padding 24px vertical, 16px horizontal. Ghost-like appearance.

### Tertiary Lavender Button
**Role:** Prominent interactive elements with a brand accent

Background: Cloud Canvas (#ffffff), text: Midnight Graphite (#191a1b), border: 1px solid Lavender Haze (#cbc2ea). Radius: 6px. Padding 16px vertical, 48px horizontal. Softer, rounded accent.

### Accent Rounded Button
**Role:** Specific interactive moments, often within a UI card

Background: Cloud Canvas (#ffffff), text: Midnight Graphite (#191a1b), border: 1px solid rgba(124, 103, 203, 0.4). Radius: 8px. Padding 12px all sides. Compact, subtly accented.

### Clean Product Card
**Role:** Showcasing features or content with clear separation

Background: Cloud Canvas (#ffffff), radius: 16px. Shadow: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px. No padding directly on card, content inside uses its own spacing.

### Atmospheric Product Card
**Role:** Highlighting key information with a frosted, elevated feel

Background: rgba(255, 255, 255, 0.7), radius: 16px. Shadow: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px. Padding 48px vertical, 32px horizontal. Translucent with soft elevation.

### Minimal Input Field
**Role:** Data entry fields, often within a dark context

Background: transparent, text: Cloud Canvas (#ffffff), border: 1px solid Cloud Canvas (#ffffff). Radius: 0px. No internal padding derived from this component (handled by text field itself).

## Do's and Don'ts

### Do
- Use p22-mackinac-pro with a letter-spacing of -0.0500em for all display and large headlines to maintain the distinctive sophisticated feel.
- Apply Cloud Canvas (#ffffff) to all primary page and card backgrounds to ensure a consistent, light base layer.
- Employ Midnight Graphite (#191a1b) for primary body text, section headlines, and button text on light backgrounds for strong contrast.
- Utilize a radius of 16px for all standard cards to maintain the soft, friendly aesthetic.
- Accent interactive elements like links and active states with Electric Lime (#d4ff4c) to draw attention and indicate interactivity.
- Build elevation with subtle shadows: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px inset and rgba(0, 0, 0, 0.1) 0px 16px 40px -8px for card elements.
- Maintain comfortable spacing with 16px for element gaps and 32px for vertical section separation.

### Don't
- Avoid using highly saturated colors for large background areas; reserve chromatic colors for functional accents and decorative elements.
- Do not deviate from the established typography hierarchy; resist making body text too large or headlines too small.
- Do not use sharp 0px radii on elements other than the specific 'Primary Filled' and 'Secondary Outlined' buttons unless explicitly defined.
- Do not apply heavy or dark box shadows; maintain the light and subtle elevation style.
- Avoid arbitrary letter spacing on text sizes below 36px, except for decorative body elements that use 0.0500em tracking.
- Do not introduce new border styles other than 1px solid or a subtle dashed line.
- Avoid mixing Lexend with p22-mackinac-pro at similar font sizes; their roles are distinct (UI vs. display).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Primary background for the entire page. |
| 1 | Card Base | `#ffffff` | Background for standard cards, slightly elevated via shadow. |
| 2 | Frosted Card | `#ffffff` | Slightly translucent card backgrounds for a layered, atmospheric effect. |
| 3 | Dark Section | `#191a1b` | Background for hero sections or content blocks that require high contrast. |

## Elevation

- **Card:** `rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px`
- **Image/Link with Hover:** `rgba(0, 0, 0, 0.05) 0px 2px 6px -16px, rgba(0, 0, 0, 0.25) 0px 7px 10px -4px`
- **Subtle UI Element:** `rgba(0, 0, 0, 0.15) 0px 2px 3px -2px`
- **Button:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`

## Imagery

The imagery on Statamic is a mix of product screenshots, abstract ambient graphics, and occasional stylized illustrations. Product screenshots are clean, showcasing UI details with sharp focus and often appear within softly rounded, elevated cards. Abstract graphics feature pastel, ethereal gradients and floating elements (like islands or toucans), primarily serving as atmospheric background elements in hero sections. Icons are generally outlined or filled with crisp, simple forms. Photography is scarce but, when present, integrates into product showcase contexts. Imagery serves to create an inviting atmosphere, explain product features, and ground the technical aspects in a visually appealing, slightly whimsical context. Image density is moderate, carefully balanced with significant areas of clear text.

## Layout

The page primarily uses a contained, centered layout, but the hero section often employs full-bleed ambient graphics that bleed to the edges. The hero itself is typically a centered headline over a background graphic or gradient, with prominent calls to action. Section rhythm alternates between full-width graphical backgrounds and contained, white card-based content blocks, often with consistent vertical spacing of 32px between them. Content is frequently arranged in a simple, readable stack or in two-column text-left/image-right (or vice-versa) alternating patterns. Feature sections often utilize discreet card grids. Navigation is a consistent top bar that remains static at the top of the viewport.

## Agent Prompt Guide

**Quick Color Reference:**
  - text: #191a1b
  - background: #ffffff
  - border: #cbd5e0
  - accent: #cbc2ea
  - primary action: #cbc2ea (outlined action border)

**3-5 Example Component Prompts:**
  - Create a Hero Headline: 'Build sites you're proud of' using p22-mackinac-pro, weight 700, size 96px, lineHeight 1.0, letterSpacing -4.8px, color Midnight Graphite (#191a1b), centered.
  - Design a Lavender Accent Button: 'Learn More', text Midnight Graphite (#191a1b), Lexend font, size 16px, weight 400, border 1px solid Lavender Haze (#cbc2ea), background Cloud Canvas (#ffffff), radius 6px, padding 16px vertical, 48px horizontal.
  - Construct a Clean Product Card: background Cloud Canvas (#ffffff), radius 16px, shadow rgba(94, 90, 90, 0.1) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px. İçerisinde başlık olarak Charcoal Text (#4e5154) ile Lexend font 20px, ağırlık 500, ve body text olarak Smoked Pearl (#5e5a5a) ile Lexend font 16px, ağırlık 400.
  - Create a Small Code Snippet: text Midnight Graphite (#191a1b), code-saver font, size 14px, weight 300, lineHeight 1.5, within a lightly bordered box (border 1px solid Subtle Grey (#cbd5e0), radius 8px, padding 12px).
  - Generate a Secondary Outlined Button: 'Try the Demo', text Midnight Graphite (#191a1b), Lexend font, size 16px, weight 400, border 1px solid Midnight Graphite (#191a1b), background transparent, radius 0px, padding 24px vertical, 16px horizontal.

## Similar Brands

- **Laravel** — Shares a similar light theme, focus on developer tools, and clean, professional aesthetic with subtle brand accents.
- **Sanity.io** — Features a light UI with prominent card-based layouts and functional, yet expressive, typography for product description.
- **Craft CMS** — Employs a sophisticated, minimal UI with fine typographic details and a similar tone of voice for content management solutions.
- **Vercel** — Utilizes a clean, high-contrast UI with a strong emphasis on modern typography and subtle atmospheric background graphics.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #191a1b;
  --gradient-midnight-graphite: linear-gradient(to right bottom, rgb(51, 65, 85), rgb(25, 26, 27));
  --color-cloud-canvas: #ffffff;
  --color-slate-mist: #beb9b3;
  --color-smoked-pearl: #5e5a5a;
  --color-stone-gray: #c2c2c2;
  --color-charcoal-text: #4e5154;
  --color-subtle-grey: #cbd5e0;
  --color-steel-gray: #3f3f46;
  --color-sky-tint: #d7e5fe;
  --color-amethyst-aura: #4c305a;
  --color-blush-pink: #f5ddee;
  --color-lavender-haze: #cbc2ea;
  --color-electric-lime: #d4ff4c;
  --color-ambient-light-glow-1: #32c5ff;
  --gradient-ambient-light-glow-1: linear-gradient(233deg, rgba(50, 197, 255, 0.08), rgba(182, 32, 224, 0.08) 51%, rgba(247, 181, 0, 0.08));

  /* Typography — Font Families */
  --font-p22-mackinac-pro: 'p22-mackinac-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lexend: 'Lexend', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-code-saver: 'code-saver', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-lore: 'Lore', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.9px;
  --text-display-sm: 60px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -3px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -4px;
  --text-display-lg: 96px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.8px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-208: 208px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-pills: 9999px;
  --radius-buttons: 8px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 2px 6px -16px, rgba(0, 0, 0, 0.25) 0px 7px 10px -4px;
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 2px 3px -2px;
  --shadow-subtle-2: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.07) 0px 2px 8px 0px, rgba(0, 0, 0, 0.05) 0px 3px 5px -4px;
  --shadow-xl: rgb(76, 48, 90) 0px 11px 37px -18px;
  --shadow-subtle-4: rgb(113, 113, 122) 0px 0px 0px 1px;
  --shadow-xl-2: rgb(190, 185, 179) 0px 24px 64px -12px;
  --shadow-subtle-5: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgb(190, 185, 179) 0px 24px 64px -12px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-card-base: #ffffff;
  --surface-frosted-card: #ffffff;
  --surface-dark-section: #191a1b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #191a1b;
  --color-cloud-canvas: #ffffff;
  --color-slate-mist: #beb9b3;
  --color-smoked-pearl: #5e5a5a;
  --color-stone-gray: #c2c2c2;
  --color-charcoal-text: #4e5154;
  --color-subtle-grey: #cbd5e0;
  --color-steel-gray: #3f3f46;
  --color-sky-tint: #d7e5fe;
  --color-amethyst-aura: #4c305a;
  --color-blush-pink: #f5ddee;
  --color-lavender-haze: #cbc2ea;
  --color-electric-lime: #d4ff4c;
  --color-ambient-light-glow-1: #32c5ff;

  /* Typography */
  --font-p22-mackinac-pro: 'p22-mackinac-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lexend: 'Lexend', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-code-saver: 'code-saver', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-lore: 'Lore', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.9px;
  --text-display-sm: 60px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: -3px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -4px;
  --text-display-lg: 96px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.8px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-208: 208px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 2px 6px -16px, rgba(0, 0, 0, 0.25) 0px 7px 10px -4px;
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 2px 3px -2px;
  --shadow-subtle-2: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 16px 40px -8px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.07) 0px 2px 8px 0px, rgba(0, 0, 0, 0.05) 0px 3px 5px -4px;
  --shadow-xl: rgb(76, 48, 90) 0px 11px 37px -18px;
  --shadow-subtle-4: rgb(113, 113, 122) 0px 0px 0px 1px;
  --shadow-xl-2: rgb(190, 185, 179) 0px 24px 64px -12px;
  --shadow-subtle-5: rgba(94, 90, 90, 0.1) 0px 0px 0px 1px, rgb(190, 185, 179) 0px 24px 64px -12px;
}
```
