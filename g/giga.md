# Giga — Style Reference
> Deep night, mountain vista – a cosmic, digital calm.

**Theme:** dark

Giga's design system evokes a sense of deep, expansive calm, contrasting vast dark landscapes with focused, luminous information. Typography is understated and elegant, prioritizing legibility and a sense of gravitas. Interactive elements offer subtle feedback, and surfaces vary from transparent overlays to opaque dark canvases, creating depth and dimension without heavy use of shadows. The overall aesthetic is one of quiet power and precision, mirroring complex AI capabilities with a refined visual language.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#000000` | `--color-obsidian` | Primary text, icon outlines, dark surface background, borders |
| Ghost | `#ffffff` | `--color-ghost` | Light surface background, light text, highlights |
| Graphite | `#cccccc` | `--color-graphite` | Card backgrounds, subtle dividers |
| Shadow | `#4d4d4d` | `--color-shadow` | Subtle shadow tint for depth |
| Pebble Gray | `#969696` | `--color-pebble-gray` | Muted secondary text |
| Night Sky | `#161717` | `--color-night-sky` | Filled button backgrounds |
| Steel Gray | `#808080` | `--color-steel-gray` | Tertiary text, subtle borders |
| Cosmic Dust | `#8a8f98` | `--color-cosmic-dust` | Placeholder text, low-contrast information text |
| Ember Glow | `#fe2c02` | `--color-ember-glow` | Decorative link accents, alerts — a vivid, urgent highlight |
| Growth Green | `#49de80` | `--color-growth-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Subtle Violet Gradient | `linear-gradient(90deg, rgb(255, 154, 234) -10%, rgb(255, 255, 255) 28%)` | `--color-subtle-violet-gradient` | Decorative background gradient used in product sections |
| Soft Mint Gradient | `linear-gradient(90deg, rgb(195, 234, 202) 0%, rgb(255, 255, 255) 74.8733%)` | `--color-soft-mint-gradient` | Decorative background gradient used in product sections |
| Sky Blue Gradient | `linear-gradient(90deg, rgb(136, 187, 245) 0%, rgb(255, 255, 255) 30%)` | `--color-sky-blue-gradient` | Decorative background gradient used in product sections |

## Tokens — Typography

### sans-serif — System fallback, minimal UI text. · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback, minimal UI text.

### Inter — Primary UI text, body copy, and secondary headlines. Its variable letter-spacing for different sizes provides an adaptive, precise feel without being overtly tracked. · `--font-inter`
- **Weights:** 300, 400, 500
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px, 16px, 29px, 44px
- **Line height:** 1.00, 1.36, 1.50, 1.54, 1.64, 1.70, 1.71, 1.75, 1.85, 1.93, 2.00, 2.22
- **Letter spacing:** -0.0300em, 0.0070em
- **Role:** Primary UI text, body copy, and secondary headlines. Its variable letter-spacing for different sizes provides an adaptive, precise feel without being overtly tracked.

### Geist Mono — Monospaced text for data, code snippets, or subtle highlights where a technical, precise voice is needed. The positive tracking provides visual breathing room. · `--font-geist-mono`
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 14px
- **Line height:** 1.20, 2.00, 2.18
- **Letter spacing:** 0.0090em
- **Role:** Monospaced text for data, code snippets, or subtle highlights where a technical, precise voice is needed. The positive tracking provides visual breathing room.

### Giga Sans Text Trial 500 — Content body text and detailed descriptive text. · `--font-giga-sans-text-trial-500`
- **Weights:** 400, 500
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Content body text and detailed descriptive text.

### Giga Sans Display Trial 500 — Small display headings, where a compact, almost stacked look is desired due to the tight line height. · `--font-giga-sans-display-trial-500`
- **Weights:** 400
- **Sizes:** 22px
- **Line height:** 0.86
- **Letter spacing:** normal
- **Role:** Small display headings, where a compact, almost stacked look is desired due to the tight line height.

### Inter Display — Sub-headings and emphasized body text. The slight tracking enhances readability at smaller display sizes. · `--font-inter-display`
- **Weights:** 400, 500
- **Sizes:** 16px
- **Line height:** 1.50, 1.51, 2.50
- **Letter spacing:** 0.0060em
- **Role:** Sub-headings and emphasized body text. The slight tracking enhances readability at smaller display sizes.

### Emilio Light — Primary headlines and hero text. The light weight and negative letter-spacing for larger sizes lend a sense of understated sophistication and calm, rather than shouting. · `--font-emilio-light`
- **Weights:** 300, 400
- **Sizes:** 24px, 41px, 48px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.0300em, -0.0200em
- **Role:** Primary headlines and hero text. The light weight and negative letter-spacing for larger sizes lend a sense of understated sophistication and calm, rather than shouting.

### Giga Sans Display Trial 400 — Medium-sized display headings. · `--font-giga-sans-display-trial-400`
- **Weights:** 400
- **Sizes:** 30px
- **Line height:** 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Medium-sized display headings.

### Giga Sans Text Trial 400 — Standard body text. · `--font-giga-sans-text-trial-400`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Standard body text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.2 | — | `--text-body` |
| heading | 22px | 0.86 | — | `--text-heading` |
| heading-lg | 30px | 1.33 | — | `--text-heading-lg` |
| display | 48px | 1.2 | -1.44px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| icons | 9999px |
| buttons | 1000px |
| default | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(247, 107, 21, 0.5) 0px 0px 4px 0px` | `--shadow-sm` |
| xl | `rgba(0, 0, 0, 0.7) 0px 12px 32px -16px, rgba(0, 0, 0, 0.7...` | `--shadow-xl` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Ghost Pill Button
**Role:** Secondary action or navigation with minimal visual weight.

Background: rgba(255, 255, 255, 0.05), Text: Obsidian, Border: Obsidian, Padding: 16px all sides, Radius: 1000px.

### Primary Filled Pill Button
**Role:** Main call to action, standing out with a solid background.

Background: Ghost, Text: Obsidian, Border: Obsidian, Padding: 9px vertical, 20px horizontal, Radius: 1000px.

### Dark Filled Pill Button
**Role:** Call to action on lighter backgrounds, inverted version of the primary.

Background: Night Sky, Text: Obsidian, Border: Obsidian, Padding: 9px vertical, 20px horizontal, Radius: 1000px.

### Small Decorative Pill Button
**Role:** Informational or tag-like elements with a subtle, dark background.

Background: rgba(0, 0, 0, 0.1), Text: Obsidian, Border: Obsidian, Padding: 0px vertical, 8px right, 14px left, Radius: 9999px.

### Transparent Card
**Role:** Content container with a very subtle, almost ghost-like presence.

Background: rgba(0, 0, 0, 0.2), Border: none, Radius: 16px, Padding: 24px vertical, 24px right, 0px left.

### Subtle Inset Card
**Role:** Small, nested content area or decorative container.

Background: rgba(0, 0, 0, 0.02), Border: none, Radius: 8px, Padding: 2px all sides.

### Standard Card
**Role:** Primary content grouping container.

Background: rgba(0, 0, 0, 0.02), Border: none, Radius: 16px, Padding: 24px all sides.

## Do's and Don'ts

### Do
- Use Obsidian (#000000) for primary headlines and body text to establish a strong, contrasted foundation.
- Apply Emilio Light font with negative letter-spacing for large headlines (e.g., 48px, weight 300, ls = -0.0300em) to create an elegant, restrained presence.
- Utilize Ghost Pill Button (background: rgba(255, 255, 255, 0.05), text: Obsidian, 1000px radius) for secondary actions or subtle navigational elements.
- Implement a 10px elementGap for consistent tight spacing between most inline and block elements.
- Apply a 1000px border-radius to all buttons for a distinctly pill-shaped, soft appearance.
- Employ Graphite (#cccccc) for card backgrounds and subtle dividers to introduce hierarchical breaks without harsh lines.
- Use Ember Glow (#fe2c02) sparingly as a vivid accent for critical links or calls to attention, ensuring high impact.

### Don't
- Avoid using harsh, opaque borders; prefer subtle transparency or no border at all for containers.
- Do not introduce strong, colored backgrounds for full sections; rely on the subtle neutral palette for depth.
- Refrain from using heavily tracked body text; the Inter font with its specific letter-spacing adjustments should be applied as specified.
- Do not deviate from the pill-shaped radius (1000px) for buttons; it's a signature visual cue.
- Avoid standard box shadows; for elevation, use subtle, diffused shadows like rgba(0, 0, 0, 0.7) 0px 12px 32px -16px.
- Do not use highly saturated colors for large text blocks or backgrounds; reserve them for small, impactful accents.
- Resist using bold font weights for large headlines; the light weight of Emilio Light is key to the system's character.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space | `#000000` | Primary page background, creating a vast, dark canvas. |
| 1 | Subtle Nebula | `#cccccc` | Base background for sections and cards, providing a barely-there structural layer. |
| 2 | Whisper Card | `#00000033` | Elevated card background with slight transparency, allowing underlying elements to subtly show through. |
| 3 | Ghost Panel | `#00000005` | Secondary card backgrounds, an even lighter, more transparent layer. |

## Elevation

- **Card Shadow:** `rgba(0, 0, 0, 0.7) 0px 12px 32px -16px, rgba(0, 0, 0, 0.7) 0px 12px 60px 0px, rgba(255, 255, 255, 0.15) 0px 0px 0px 1px`

## Imagery

This system primarily uses atmospheric, wide-angle photography featuring natural landscapes, often mountains or abstract patterns, with a dark, moody overlay. Imagery is used as a full-bleed background for hero sections, setting a grand, serene tone. When product interfaces are shown, they are clean, contained rectangles with sharp edges against photographic backdrops. Icons are minimal, outlined (Obsidian outline on dark backgrounds, Ghost on light), suggesting a focus on clarity rather than heavy decoration. The overall impression is image-heavy in hero sections, with imagery serving decorative atmosphere and product showcase, usually contained within a content area on darker backgrounds.

## Layout

The page maintains a centered content model with an implied max-width, while hero sections can be full-bleed with panoramic imagery. The initial hero features a full-viewport, dark, landscape photograph with a centered headline stack and a prominent call-to-action. Subsequent sections often alternate between dark backgrounds (#000000) and slightly lighter, more textured dark surfaces (like rgba(0,0,0,0.2) or #cccccc). Content is typically arranged in left-aligned stacks or a two-column layout with text to the left and product visuals/cards to the right. Vertical rhythm is maintained with consistent section gaps of approximately 48px, creating a spacious but deliberate flow. Navigation is primarily a top sticky header with minimal links and a pill-shaped 'Talk to us' button.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000
- background: #000000
- border: #000000
- accent: #fe2c02
- primary action: #161717 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #161717 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: use the Transparent Card with background rgba(0, 0, 0, 0.2), 16px radius, 24px vertical padding. Inside, an icon with Obsidian (#000000) fill and stroke. Below the icon, a heading 'Built to handle complexity' in Inter, weight 500, 29px size, line-height 1.5, color Ghost (#ffffff). Underneath, body text 'Explore Agent Canvas' in Giga Sans Text Trial 500, weight 400, 14px size, color Pebble Gray (#969696).
3. Generate a call-to-action banner: background Night Sky (#161717) spanning full width. Place a heading 'Join the conversation' in Inter, weight 500, 44px size, line-height 1, color Ghost (#ffffff). To its right, a Dark Filled Pill Button with text 'Learn more', background Night Sky (#161717), text Ghost (#ffffff), 9px vertical and 20px horizontal padding, 1000px radius.

## Similar Brands

- **Linear** — Similar focus on dark mode, minimal use of color for functional accents, and sophisticated typography.
- **Anthropic (Claude AI)** — Shares a calm, understated aesthetic for advanced AI products, often employing muted colors and clear hierarchy.
- **Framer** — Known for clean, professional dark mode interfaces with robust product showcases and careful typography.
- **Vercel** — Employs similar dark interface patterns, subtle gradients for depth, and refined, readable typography for developer tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #000000;
  --color-ghost: #ffffff;
  --color-graphite: #cccccc;
  --color-shadow: #4d4d4d;
  --color-pebble-gray: #969696;
  --color-night-sky: #161717;
  --color-steel-gray: #808080;
  --color-cosmic-dust: #8a8f98;
  --color-ember-glow: #fe2c02;
  --color-growth-green: #49de80;
  --color-subtle-violet-gradient: #ff9aea;
  --gradient-subtle-violet-gradient: linear-gradient(90deg, rgb(255, 154, 234) -10%, rgb(255, 255, 255) 28%);
  --color-soft-mint-gradient: #c3eaca;
  --gradient-soft-mint-gradient: linear-gradient(90deg, rgb(195, 234, 202) 0%, rgb(255, 255, 255) 74.8733%);
  --color-sky-blue-gradient: #88bbf5;
  --gradient-sky-blue-gradient: linear-gradient(90deg, rgb(136, 187, 245) 0%, rgb(255, 255, 255) 30%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-giga-sans-text-trial-500: 'Giga Sans Text Trial 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-display-trial-500: 'Giga Sans Display Trial 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-emilio-light: 'Emilio Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-display-trial-400: 'Giga Sans Display Trial 400', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-text-trial-400: 'Giga Sans Text Trial 400', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.2;
  --text-heading: 22px;
  --leading-heading: 0.86;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.33;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 3.85px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-icons: 9999px;
  --radius-buttons: 1000px;
  --radius-default: 10px;

  /* Shadows */
  --shadow-sm: rgba(247, 107, 21, 0.5) 0px 0px 4px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.7) 0px 12px 32px -16px, rgba(0, 0, 0, 0.7) 0px 12px 60px 0px, rgba(255, 255, 255, 0.15) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-deep-space: #000000;
  --surface-subtle-nebula: #cccccc;
  --surface-whisper-card: #00000033;
  --surface-ghost-panel: #00000005;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #000000;
  --color-ghost: #ffffff;
  --color-graphite: #cccccc;
  --color-shadow: #4d4d4d;
  --color-pebble-gray: #969696;
  --color-night-sky: #161717;
  --color-steel-gray: #808080;
  --color-cosmic-dust: #8a8f98;
  --color-ember-glow: #fe2c02;
  --color-growth-green: #49de80;
  --color-subtle-violet-gradient: #ff9aea;
  --color-soft-mint-gradient: #c3eaca;
  --color-sky-blue-gradient: #88bbf5;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-giga-sans-text-trial-500: 'Giga Sans Text Trial 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-display-trial-500: 'Giga Sans Display Trial 500', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-emilio-light: 'Emilio Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-display-trial-400: 'Giga Sans Display Trial 400', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-giga-sans-text-trial-400: 'Giga Sans Text Trial 400', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.2;
  --text-heading: 22px;
  --leading-heading: 0.86;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.33;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 3.85px;
  --radius-md-2: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-sm: rgba(247, 107, 21, 0.5) 0px 0px 4px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.7) 0px 12px 32px -16px, rgba(0, 0, 0, 0.7) 0px 12px 60px 0px, rgba(255, 255, 255, 0.15) 0px 0px 0px 1px;
}
```
