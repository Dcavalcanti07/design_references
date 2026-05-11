# Huddle — Style Reference
> Matte pastel blocks on midnight

**Theme:** dark

Huddle presents a tactile, layered workspace aesthetic: dark background, with soft, rounded cards in varied, muted pastels that suggest individual project spaces. Typography is confident and direct, using a wide range of weights and subtle negative letter-spacing for large titles. Control elements are minimal, often ghost-like or pill-shaped, allowing the pastel project cards to visually dominate the interface. The overall impression is one of organized creativity and collaborative warmth, despite a dark base theme.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `#000000` | `--color-midnight-canvas` | Page backgrounds, primary text, dark buttons |
| Ash Cloud | `#ffffff` | `--color-ash-cloud` | Interface text, light surfaces, button text |
| Slate Text | `#333333` | `--color-slate-text` | Body text for lighter sections, muted UI elements |
| Cream Paper | `#e5e6e1` | `--color-cream-paper` | Elevated card backgrounds, soft borders |
| Warm Violet | `#bbb2ce` | `--color-warm-violet` | Prominent card backgrounds, accent elements |
| Golden Ochre | `#e4b976` | `--color-golden-ochre` | Card backgrounds, secondary accents, borders for specific tags |
| Deep Plum | `#453b60` | `--color-deep-plum` | Violet accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Rose Blush | `#cb9da2` | `--color-rose-blush` | Card backgrounds, badge text |
| Earth Clay | `#65451d` | `--color-earth-clay` | Primary action button background, badge backgrounds – a warm, grounded accent |
| Charcoal Teal | `#3a4444` | `--color-charcoal-teal` | Muted button backgrounds, secondary text, subtle borders |
| Crimson Grit | `#5c2529` | `--color-crimson-grit` | Error states in badges, borders for specific tags, strong accent |

## Tokens — Typography

### Nng — All primary text elements: headlines, body, buttons, and most UI. Its wide range of weights combined with subtle negative letter-spacing for larger sizes gives a confident, modern voice. · `--font-nng`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 18px, 21px, 22px, 29px, 40px, 44px, 69px
- **Line height:** 1.10, 1.20, 1.22, 1.25, 1.30, 1.32, 1.35, 1.42, 1.45, 1.50, 1.58
- **Letter spacing:** -0.0210em at 69px, -0.0110em at 44px, -0.0100em at 40px, -0.0080em at 29px
- **Role:** All primary text elements: headlines, body, buttons, and most UI. Its wide range of weights combined with subtle negative letter-spacing for larger sizes gives a confident, modern voice.

### Roboto — Functional text: badges, meta info, and some descriptive lists. Its slight negative letter-spacing (-0.1030em) provides a compact, legible feel for smaller elements. · `--font-roboto`
- **Substitute:** Roboto
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.25, 1.43
- **Letter spacing:** -0.1030em
- **Role:** Functional text: badges, meta info, and some descriptive lists. Its slight negative letter-spacing (-0.1030em) provides a compact, legible feel for smaller elements.

### Apercu pro mono — Small, informational cues and potentially code-like fragments. Its monospace nature provides a distinct, technical counterpoint to the primary typeface. · `--font-apercu-pro-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.42, 1.43
- **Role:** Small, informational cues and potentially code-like fragments. Its monospace nature provides a distinct, technical counterpoint to the primary typeface.

### Moderat — Small functional links and secondary UI text. Its distinct letter-spacing (-0.0210em) helps differentiate it from other small text, making it feel deliberate. · `--font-moderat`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20, 1.50
- **Letter spacing:** -0.0210em
- **Role:** Small functional links and secondary UI text. Its distinct letter-spacing (-0.0210em) helps differentiate it from other small text, making it feel deliberate.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.58 | — | `--text-caption` |
| body-sm | 14px | 1.43 | -0.103px | `--text-body-sm` |
| body | 16px | 1.5 | -0.011px | `--text-body` |
| subheading | 22px | 1.35 | — | `--text-subheading` |
| heading | 29px | 1.32 | -0.96px | `--text-heading` |
| heading-lg | 44px | 1.22 | -0.96px | `--text-heading-lg` |
| display | 69px | 1.1 | -1.44px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 8px |
| cards | 40px |
| lists | 24px |
| badges | 4px |
| buttons | 1000px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Pill Button - Dark Filled
**Role:** Primary action button

Filled button with Midnight Canvas (#000000) background, Ash Cloud (#ffffff) text and border, featuring an extreme 1000px border-radius for a pill shape. Padding is generous at 12px vertical, 16px horizontal, or 24px vertical, 40px horizontal for larger contexts.

### Pill Button - Earth Clay Filled
**Role:** Emphasis action button

Filled button with Earth Clay (#65451d) background, Golden Ochre (#e4b976) text and border. Features an extreme 100px border-radius. Padding is 24px vertical, 40px horizontal.

### Pill Button - Charcoal Teal Filled
**Role:** Secondary action button

Filled button with Charcoal Teal (#3a4444) background and Ash Cloud (#aebbba) text and border. Features an extreme 100px border-radius. Padding is 24px vertical, 40px horizontal.

### Project Card - Warm Violet
**Role:** Content container for ongoing or active projects

Warm Violet (#bbb2ce) background with 40px border-radius, often appearing as a larger, visually distinct block. Padding is 16px top, 60px bottom, 0px horizontal.

### Project Card - Golden Ochre
**Role:** Content container for shipped projects

Golden Ochre (#e4b976) background with 40px border-radius. No consistent custom padding, often inherits contextual spacing. This is a visual variant for different project statuses.

### Project Card - Deep Plum
**Role:** Content container for 'building' projects

Deep Plum (#453b60) background with 40px border-radius. No consistent custom padding, visually similar to Golden Ochre project cards but with a distinct color.

### Project Card - Midnight Ink
**Role:** Interactive input card

Midnight Canvas (#000000) background, 40px border-radius. Used for interactive sections where a user might input text, suggesting an active area within the dark theme.

### Tag Badge - Crimson Grit
**Role:** Informational tag for categories

Crisp badge with Crimson Grit (#5c2529) background and Rose Blush (#cb9da2) text. Features 4px border-radius and modest 4px vertical, 8px horizontal padding.

### Tag Badge - Charcoal Teal
**Role:** Informational tag for secondary categories

Crisp badge with Charcoal Teal (#3a4444) background and a light gray (#aebbba) text. Features 4px border-radius and modest 4px vertical, 8px horizontal padding.

### Ghost Badge - Charcoal Teal
**Role:** Subtle, interactive tag

Transparent background with Charcoal Teal (#3a4444) text, 40px border-radius. Generous 12px vertical, 14px horizontal padding gives it more presence than other tags, used for clickable filtering.

## Do's and Don'ts

### Do
- Use Midnight Canvas (#000000) for all primary page and card backgrounds to establish the core dark theme.
- Apply 1000px border-radius to all primary action buttons for a distinct pill shape, and 40px for larger card surfaces to create soft, rounded containers.
- Utilize a wide range of Nng weights (300-700) for textual hierarchy, always implementing negative letter-spacing for headlines (e.g., -0.0210em for 69px).
- Employ a variety of muted pastel chromatic colors (Warm Violet, Golden Ochre, Rose Blush, Deep Plum) for card backgrounds to visually differentiate content sections and projects.
- Ensure all primary action buttons use Earth Clay (#65451d) as their background with Golden Ochre (#e4b976) text and border, creating a warm, inviting prompt.
- Maintain comfortable density by consistently applying 12px as the base element gap and card padding where components are stacked or nested.
- Use the system's pre-defined Nng 'Moderat' and 'Apercu pro mono' for specific, small UI elements where a distinct typographic voice is required.

### Don't
- Avoid using harsh, saturated colors; stick to the muted, near-gray chromatic palette to maintain the understated and sophisticated tone.
- Do not introduce sharp corners or square elements; all interactive and content containers should adhere to the established 40px or 100px/1000px border radii.
- Refrain from using strong, contrasting background gradients or shadows that would detract from the flat, layered feel of the pastel cards.
- Do not deviate from the specified negative letter-spacing for headlines; this is a signature typographic trait of the system.
- Never use generic semantic colors (e.g., bright green for success) unless it's a very specific, small icon or badge, as the primary chromatic palette handles most brand messaging.
- Avoid excessive use of borders; lean into color and elevation via distinct background colors for surface separation.
- Do not introduce new typefaces; the existing set of Nng, Roboto, Apercu pro mono, and Moderat covers all necessary typographic roles.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Canvas | `#000000` | Primary page background, base layer |
| 1 | Deep Plum Card | `#453b60` | Interactive elements, input cards, subtle accent areas |
| 2 | Warm Violet Card | `#bbb2ce` | Prominent project cards, key content blocks |
| 3 | Golden Ochre Card | `#e4b976` | Highlight project cards, distinct content segments |
| 4 | Cream Paper Card | `#e5e6e1` | Foreground elements, feedback cards, highly elevated sections (less used) |

## Imagery

The site's imagery strategy is minimal, primarily leveraging abstract visual metaphors delivered through UI elements. Profile images of people are small, circular, and contained, serving as social proof or authorship indicators rather than large photography. Icons are outlined, simple, and monochrome, often appearing within badges. There is an absence of large-scale photography or complex illustrations; the visual language is dominated by typography and layered, colored UI cards.

## Layout

The Huddle layout operates on a centered, max-width contained model, roughly 1200px. The page is composed of distinct vertical sections with consistent spacing, often alternating between a dominant left-aligned text block and a right-aligned display of rounded cards. The hero section features a large, centered headline on the Midnight Canvas background, flanked by small profile image avatars. Content is arranged in a two-column grid, with descriptive text on the left and visually distinct project cards on the right. Section breaks are subtle, often indicated by the introduction of a new content block or project card cluster rather than explicit dividers. Navigation is a minimal top bar.

## Agent Prompt Guide

Quick Color Reference: text: #ffffff, background: #000000, border: #333333, accent: #bbb2ce, primary action: #65451d (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #65451d background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a 'Currently Building' section: Warm Violet (#bbb2ce) card with 40px radius. Inside, a headline 'Smart contract auditor' in Nng weight 500 at 29px, Deep Plum (#453b60), letter-spacing -0.0080em. A Ghost Badge - Charcoal Teal with text 'Product Design'.
3. Create a 'Shipped Projects' list: Rose Blush (#cb9da2) card with 40px radius. Inside, body text 'AI-powered chat platform' in Nng weight 400 at 18px, Crimson Grit (#5c2529). Follow with Tag Badge - Crimson Grit with text '#ai'.

## Similar Brands

- **Linear** — Dark UI with emphasis on distinct colored, rounded cards for task management and project visualization.
- **Dribbble (dark mode)** — Layered content blocks with distinct background colors and pronounced rounded corners on a dark canvas.
- **Raycast** — Minimal dark UI, strong typography, and functional components that use subtle color accents and geometry to delineate interactive areas.
- **Height** — Task-oriented dark mode with visually distinct, often colored, component cards on a quiet background, using bold typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-ash-cloud: #ffffff;
  --color-slate-text: #333333;
  --color-cream-paper: #e5e6e1;
  --color-warm-violet: #bbb2ce;
  --color-golden-ochre: #e4b976;
  --color-deep-plum: #453b60;
  --color-rose-blush: #cb9da2;
  --color-earth-clay: #65451d;
  --color-charcoal-teal: #3a4444;
  --color-crimson-grit: #5c2529;

  /* Typography — Font Families */
  --font-nng: 'Nng', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-pro-mono: 'Apercu pro mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-moderat: 'Moderat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.58;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.103px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.011px;
  --text-subheading: 22px;
  --leading-subheading: 1.35;
  --text-heading: 29px;
  --leading-heading: 1.32;
  --tracking-heading: -0.96px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.22;
  --tracking-heading-lg: -0.96px;
  --text-display: 69px;
  --leading-display: 1.1;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 57.6px;
  --radius-full-2: 100px;
  --radius-full-3: 200px;
  --radius-full-4: 1000px;

  /* Named Radii */
  --radius-tags: 8px;
  --radius-cards: 40px;
  --radius-lists: 24px;
  --radius-badges: 4px;
  --radius-buttons: 1000px;

  /* Surfaces */
  --surface-midnight-canvas: #000000;
  --surface-deep-plum-card: #453b60;
  --surface-warm-violet-card: #bbb2ce;
  --surface-golden-ochre-card: #e4b976;
  --surface-cream-paper-card: #e5e6e1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-ash-cloud: #ffffff;
  --color-slate-text: #333333;
  --color-cream-paper: #e5e6e1;
  --color-warm-violet: #bbb2ce;
  --color-golden-ochre: #e4b976;
  --color-deep-plum: #453b60;
  --color-rose-blush: #cb9da2;
  --color-earth-clay: #65451d;
  --color-charcoal-teal: #3a4444;
  --color-crimson-grit: #5c2529;

  /* Typography */
  --font-nng: 'Nng', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-pro-mono: 'Apercu pro mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-moderat: 'Moderat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.58;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.103px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.011px;
  --text-subheading: 22px;
  --leading-subheading: 1.35;
  --text-heading: 29px;
  --leading-heading: 1.32;
  --tracking-heading: -0.96px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.22;
  --tracking-heading-lg: -0.96px;
  --text-display: 69px;
  --leading-display: 1.1;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 57.6px;
  --radius-full-2: 100px;
  --radius-full-3: 200px;
  --radius-full-4: 1000px;
}
```
