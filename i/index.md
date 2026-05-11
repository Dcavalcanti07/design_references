# Index — Style Reference
> Midnight Grid Command

**Theme:** dark

Index employs a 'dark void' aesthetic, presenting information on deep, near-black surfaces. Thin, outlined elements and subtle grid lines define structure, while ample letter spacing and precise typography create a sense of calm authority. Interactivity is signaled by high-contrast text and a single muted violet accent, which appears sparingly to prevent visual overhead. The system prioritizes clarity and focus, allowing content to emerge from a dark, minimal backdrop.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Page backgrounds, deepest surface layers, primary text on light backgrounds, hairline borders, ghost button strokes |
| Deep Graphite | `#1c1c1c` | `--color-deep-graphite` | Secondary surface backgrounds, elevated card backgrounds, subtle icon outlines |
| Alabaster | `#ffffff` | `--color-alabaster` | Primary text on dark backgrounds, interactive link text, button backgrounds for ghost buttons, emphasized headings |
| Medium Gray | `#808080` | `--color-medium-gray` | Secondary text, muted borders, placeholder text, subtle UI elements |
| Light Gray | `#ababab` | `--color-light-gray` | Muted helper text, tertiary surface contrast, very subtle borders |
| Dark Gray | `#4d4d4d` | `--color-dark-gray` | Finer details, very subtle borders or small text where slightly more presence than Light Gray is needed |
| Soft Violet | `#7089ba` | `--color-soft-violet` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Raveo Variable — Primary typeface for all headings and most body text. The variable weight contributes to precise visual hierarchy where size and weight are carefully balanced. 'tnum' feature ensures consistent number alignment. · `--font-raveo-variable`
- **Substitute:** Inter Variable
- **Weights:** 400, 500, 1000
- **Sizes:** 12px, 14px, 16px, 24px, 32px, 70px
- **Line height:** 1.10, 1.20, 1.40, 1.50, 1.60, 1.70, 1.80
- **Letter spacing:** -0.04em at 70px, -0.01em at 32px
- **OpenType features:** `'tnum'`
- **Role:** Primary typeface for all headings and most body text. The variable weight contributes to precise visual hierarchy where size and weight are carefully balanced. 'tnum' feature ensures consistent number alignment.

### Geist Mono — Monospaced typeface for small annotations, code snippets, and specific UI labels where fixed-width alignment is desired. The slightly positive letter spacing creates a readable, airy feel. · `--font-geist-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 500
- **Sizes:** 9px, 12px
- **Line height:** 1.60
- **Letter spacing:** 0.02em
- **Role:** Monospaced typeface for small annotations, code snippets, and specific UI labels where fixed-width alignment is desired. The slightly positive letter spacing creates a readable, airy feel.

### sans-serif — Fallback sans-serif for minimal UI elements and basic text where specific branding is less critical. · `--font-sans-serif`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback sans-serif for minimal UI elements and basic text where specific branding is less critical.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.2 | -0.14px | `--text-body` |
| heading-sm | 24px | 1.4 | — | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.32px | `--text-heading` |
| display | 70px | 1.1 | -2.8px | `--text-display` |

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
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 34 | 34px | `--spacing-34` |
| 44 | 44px | `--spacing-44` |
| 50 | 50px | `--spacing-50` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| max | 188px |
| fluid | 100px |
| small | 6px |
| larger | 20px |
| buttons | 50px |

### Layout

- **Section gap:** 50px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Navigation Link
**Role:** Interactive text link in header, footer, and inline content.

Text uses Raveo Variable, weight 400 or 500, size 12px, line height 1.2. Color is Alabaster (#ffffff) on Void Black, or Light Gray (#ababab) for less prominent links. Padding: 5px horizontal, 8px vertical.

### Ghost Button
**Role:** Primary and secondary actions with minimal visual weight.

Text is Alabaster (#ffffff) with Void Black (#000000) border, 1px thick. Background is transparent or a dark neutral. Rounded with 50px radius. Text is Raveo Variable, weight 500, 14px size, line height 1.2, letter spacing -0.01em. Example: 'Book demo' button.

### Early Preview Badge
**Role:** Small informational tag for new features.

Text uses Geist Mono, size 9px, weight 500, letter spacing 0.02em. Background is Void Black (#000000), text is Alabaster (#ffffff). Border is thin, 1px Void Black. Radius 6px or 20px, with padding of 9px horizontally and 5px vertically. Features a small bullet point graphic.

### Feature Card
**Role:** Container for showcasing product benefits or steps.

Background is Deep Graphite (#1c1c1c) or Void Black (#000000), using Alabaster (#ffffff) for prominent headings and Alabaster or Medium Gray (#808080) for body text. Inner padding is 16px to 24px. Features subtle border lines of Void Black or Medium Gray for separation between elements.

### Interactive Icon Circle
**Role:** Used for 'get started' steps, showcasing a visual cue.

Circular background using Deep Graphite (#1c1c1c) with a thin Void Black (#000000) border. Contains a white (#ffffff) line-art icon. Size 48px square, border radius 100px.

## Do's and Don'ts

### Do
- Prioritize Void Black (#000000) and Deep Graphite (#1c1c1c) for backgrounds and surfaces to maintain the dark theme rigidity.
- Use Alabaster (#ffffff) for primary text and headings against dark backgrounds, ensuring maximum contrast.
- Apply Raveo Variable with subtle negative letter spacing (-0.04em for large heads, -0.01em for smaller heads) for headlines to create a sophisticated, restrained appearance.
- Employ Geist Mono for all small, functional labels and annotations, especially where a fixed-width, precise feel is needed.
- Utilize Soft Violet (#7089ba) only as a minimal accent — for small indicators, hover states, or subtle highlights, never for large background areas or primary buttons.
- Maintain a compact spacing density, with 10px as a common element gap and minimal padding around interactive elements.
- Use rounded corners consistently: 50px for primary ghost buttons and smaller circles, 6px for subtle interface elements like badges.

### Don't
- Avoid using saturated colors other than Soft Violet (#7089ba); the design relies on a near-monochromatic palette.
- Do not introduce heavy shadows or overt elevation effects; the design emphasizes flat surfaces and subtle outlines.
- Refrain from large blocks of text; break content into manageable, well-spaced lines with clear hierarchy.
- Do not use generic system fonts for prominent text; Raveo Variable and Geist Mono are essential to the brand's typographic identity.
- Avoid wide page layouts; content should be centered and organized within an implied maximum width, even without a strict pageMaxWidth.
- Do not randomly vary border radii; stick to the specified 6px, 20px, 50px, 100px, and 188px for deliberate shape language.
- Do not use solid background buttons with chromatic colors; primary interactive elements should remain ghosted or neutral.

## Imagery

The imagery aesthetic is minimalist and technical, focusing on abstract line-art illustrations and subtle background patterns. These visuals are typically monochromatic or near-monochromatic, using fine lines and geometric forms to suggest data, networks, and technical processes. Illustrations serve a decorative and explanatory role, subtly enhancing content without distracting. Icons are also line-art, matching the overall sparse aesthetic, contributing to the feeling of a sophisticated, data-driven system. Imagery density is low; the visual system is text-dominant.

## Layout

The page primarily uses a full-bleed dark background, setting a continuous 'void' theme. Content sections are centered with an implicit maximum width, likely around 1000-1200px, maintaining ample negative space on wider screens. The hero section features a large, centered headline over a dark, subtly textured background. Sections maintain consistent vertical spacing, often indicated by faint background grids or thin dividing lines rather than distinct surface layers. Content is arranged in alternating patterns, such as text-left/visual-right, or in 3-column card grids for features. Navigation is a sticky top bar, minimal and dark, with ghost buttons and text links.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #000000
accent: #7089ba
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Void Black background with subtle texture. Centered headline 'Analytics done for you.' in Raveo Variable, size 70px, weight 1000, white (#ffffff), letter-spacing -2.8px. Below it, a subtext 'Surface the exact levers...' in Raveo Variable, size 16px, weight 400, Light Gray (#ababab), centered. Below that, a ghost button 'Book demo' with Alabaster (#ffffff) text, Void Black (#000000) border, 50px radius, 14px text size, 12px vertical and 24px horizontal padding.
2. Design a feature card: Deep Graphite (#1c1c1c) background, 188px radius. Headline 'Onboard call' in Raveo Variable, size 24px, weight 500, Alabaster (#ffffff), centered. Body text 'Share current setup & metrics.' in Raveo Variable, size 14px, weight 400, Medium Gray (#808080). Include a thin Alabaster (#ffffff) circular icon with a Deep Graphite (#1c1c1c) background, 100px radius, 48x48px size, and a 1px Void Black (#000000) border containing a white line-art icon.
3. Implement a navigation link: 'Features' in Raveo Variable, size 12px, weight 400, Alabaster (#ffffff). Padding of 5px horizontal and 8px vertical, no distinct background, on a Void Black (#000000) navigation bar. On hover, apply a subtle text color change to Soft Violet (#7089ba).

## Similar Brands

- **Linear** — Dark UI, fine typography, and emphasis on clear outlines over heavy shadows.
- **Vercel** — Monochromatic dark theme, subtle background textures, and precise typography for a developer-centric feel.
- **Figma** — Minimalist interface, extensive use of line-art icons and subtle gray scales, though in a light theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-deep-graphite: #1c1c1c;
  --color-alabaster: #ffffff;
  --color-medium-gray: #808080;
  --color-light-gray: #ababab;
  --color-dark-gray: #4d4d4d;
  --color-soft-violet: #7089ba;

  /* Typography — Font Families */
  --font-raveo-variable: 'Raveo Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: -0.14px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.32px;
  --text-display: 70px;
  --leading-display: 1.1;
  --tracking-display: -2.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w1000: 1000;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-34: 34px;
  --spacing-44: 44px;
  --spacing-50: 50px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 20px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 188px;

  /* Named Radii */
  --radius-max: 188px;
  --radius-fluid: 100px;
  --radius-small: 6px;
  --radius-larger: 20px;
  --radius-buttons: 50px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-deep-graphite: #1c1c1c;
  --color-alabaster: #ffffff;
  --color-medium-gray: #808080;
  --color-light-gray: #ababab;
  --color-dark-gray: #4d4d4d;
  --color-soft-violet: #7089ba;

  /* Typography */
  --font-raveo-variable: 'Raveo Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: -0.14px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.32px;
  --text-display: 70px;
  --leading-display: 1.1;
  --tracking-display: -2.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-34: 34px;
  --spacing-44: 44px;
  --spacing-50: 50px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 20px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 188px;
}
```
