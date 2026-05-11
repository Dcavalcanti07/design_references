# SuperHi — Style Reference
> Vibrant geometry on a clean canvas — a digital workshop buzzing with creative shapes.

**Theme:** light

This system expresses a playful, creative energy through a vibrant, almost primary color palette paired with a functional, crisp sans-serif typography. Geometric and organic shapes in vivid hues act as visual anchors and decorative elements. The intentional use of deep, saturated blue as the primary interactive color, alongside a large, friendly radius for buttons and inputs, creates an approachable but authoritative digital learning environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Gray | `#111118` | `--color-storm-gray` | Primary text color for headlines and body copy, subtle borders, and dark button backgrounds. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, and text on dark interactive elements. |
| Pale Mist | `#f0f6ff` | `--color-pale-mist` | Input backgrounds, subtle section dividers—a barely-there tint of blue. |
| Electric Blue | `#2727e6` | `--color-electric-blue` | Primary brand accent, used for all main call-to-action buttons, active navigation, and key interactive elements. Creates a high-energy focal point. |
| Vivid Green | `#16ab59` | `--color-vivid-green` | Decorative elements, secondary accents, and occasional badges—a burst of organic color. |
| Lemon Zest | `#ffda00` | `--color-lemon-zest` | Decorative geometric shapes and highlight elements, conveying a cheerful, bright sensibility. |
| Sky Tint | `#e1edff` | `--color-sky-tint` | Section backgrounds, footer backgrounds, offering a soft, cool base for content. |
| Cool Aqua | `#91d8ec` | `--color-cool-aqua` | Decorative card backgrounds and unique icon fills for a touch of serene blue. |
| Coral Glow | `#ffbac4` | `--color-coral-glow` | Decorative geometric shapes and highlight elements for a warm, inviting contrast. |
| Sunset Orange | `#ff7715` | `--color-sunset-orange` | Decorative geometric shapes, offering an energetic, warm counterpoint. |
| Flame Red | `#ff4141` | `--color-flame-red` | Accent fill for illustrative elements, providing a strong, vibrant punch. |

## Tokens — Typography

### Haas Grot Text — Primary typeface for all body text, navigation, card descriptions, and secondary headings. Its neutral, accessible nature ensures high readability across various content types. · `--font-haas-grot-text`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 20px, 22px, 24px
- **Line height:** 1.10, 1.25, 1.35, 1.40
- **Letter spacing:** -0.32px, -0.22px, -0.16px, -0.14px
- **Role:** Primary typeface for all body text, navigation, card descriptions, and secondary headings. Its neutral, accessible nature ensures high readability across various content types.

### Haas Grot Disp — Headline typeface, used for display-level text and prominent titles. Its crisp yet friendly form, especially with subtle negative letter-spacing at larger sizes, imparts a modern and engaging tone. · `--font-haas-grot-disp`
- **Substitute:** Neue Haas Grotesk Display
- **Weights:** 400
- **Sizes:** 24px, 35px, 42px, 52px, 62px, 72px, 92px
- **Line height:** 1.00, 1.10, 1.15, 1.35
- **Letter spacing:** -0.72px, -0.70px, -0.84px, -0.94px, -1.24px, -1.44px, -2.76px
- **Role:** Headline typeface, used for display-level text and prominent titles. Its crisp yet friendly form, especially with subtle negative letter-spacing at larger sizes, imparts a modern and engaging tone.

### Martian Mono — Monospaced typeface used for small, functional text such as copyright, code snippets, or subtle metadata. Provides a technical counterpoint to the primary sans-serifs. · `--font-martian-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 17px
- **Line height:** 1.00, 1.30, 1.35
- **Letter spacing:** -0.16px
- **Role:** Monospaced typeface used for small, functional text such as copyright, code snippets, or subtle metadata. Provides a technical counterpoint to the primary sans-serifs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.35 | — | `--text-body` |
| body-lg | 20px | 1.4 | -0.22px | `--text-body-lg` |
| subheading | 22px | 1.1 | -0.16px | `--text-subheading` |
| heading | 24px | 1.25 | -0.72px | `--text-heading` |
| heading-lg | 35px | 1.15 | -0.7px | `--text-heading-lg` |
| display | 42px | 1.1 | -0.84px | `--text-display` |
| display-lg | 52px | 1 | -0.94px | `--text-display-lg` |
| display-xl | 62px | 1 | -1.24px | `--text-display-xl` |
| display-xxl | 72px | 1 | -1.44px | `--text-display-xxl` |
| display-max | 92px | 1 | -2.76px | `--text-display-max` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 48px |
| input | 5000px |
| buttons | 32px |
| default | 24px |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Electric Blue (#2727e6) background with Canvas White (#ffffff) text. Features a 32px border-radius, `Haas Grot Disp` font at 24px weight 400. Padding of 2.4px top/bottom and 9.6px left/right. Used for primary interactive elements.

### Large Primary Action Button
**Role:** Prominent Call to action

Electric Blue (#2727e6) background with Canvas White (#ffffff) text. Features a 48px border-radius, `Haas Grot Disp` font. Larger padding: 3.6px top/bottom and 14.4px left/right. Used for high-emphasis buttons like hero CTAs.

### Text Link Button
**Role:** Secondary action

Transparent background with Storm Gray (#111118) text and no border-radius. `Haas Grot Text` font. No padding. Used for minimal, in-text actions or navigation.

### Tertiary White Button
**Role:** Alternative action

Canvas White (#ffffff) background with Storm Gray (#111118) text. Features a 48px border-radius and `Haas Grot Disp` font. Padding of 3.6px top/bottom and 14.4px left/right. Used for less emphasized but still prominent actions, often alongside primary buttons.

### Default Card
**Role:** Content container

Transparent background with no border-radius or shadow. Padding of 16px top/bottom and 0px left/right. Primarily used for content segmentation without distinct visual boundaries, often relying on typography for hierarchy.

### Accent Blue Card
**Role:** Highlighted content container

Electric Blue (#2727e6) background with no border-radius or shadow. No padding. Likely used for full-bleed sections or backgrounds that function as cards.

### Circular Badge (White)
**Role:** Small informational tag

Canvas White (#ffffff) background with Storm Gray (#111118) text. Features a 5000px border-radius (pill shape). Padding of 8px top/bottom and 16px left/right. Used for small, contained labels or tags.

### Circular Badge (Cool Aqua)
**Role:** Small informational tag with accent

Cool Aqua (#91d8ec) background with Storm Gray (#111118) text. Features a 5000px border-radius (pill shape). Padding of 8px top/bottom and 16px left/right. Used for visually distinct labels or tags.

### Rounded Search Input
**Role:** User input field

Pale Mist (#f0f6ff) background with Storm Gray (#000000) text (placeholder). Features a 5000px border-radius (pill shape). Padding of 12px top/bottom, 68px right, and 16px left. The large right padding suggests an embedded icon.

## Do's and Don'ts

### Do
- Use Electric Blue (#2727e6) for all primary call-to-action buttons and active states to maintain brand consistency.
- Prioritize `Haas Grot Disp` weight 400 with negative letter-spacing for all display-level headings to capture the system's distinctive visual tone.
- Apply the 32px or 48px border-radius to buttons and the 5000px (pill) radius for inputs and badges for a consistent soft, approachable feel.
- Leverage the full palette of accent colors (Lemon Zest #ffda00, Vivid Green #16ab59, Coral Glow #ffbac4, Cool Aqua #91d8ec) for geometric decorative shapes and illustrations to enhance visual interest.
- Maintain comfortable spacing: use 8px for `elementGap` between inline items and `cardPadding` of 16px where content is contained.

### Don't
- Do not use generic square buttons; always apply either a 32px, 48px, or 5000px border-radius to interactive elements.
- Avoid applying heavy drop shadows; the design relies on bold shapes and colored backgrounds for depth, not elevation effects.
- Do not use monochromatic schemes; the brand identity is built on a diverse and vivid accent color palette.
- Refrain from using system fonts like Arial or Helvetica; `Haas Grot Text`, `Haas Grot Disp`, and `Martian Mono` are critical for the brand's unique typographic voice.
- Do not use text links with underlines; use the `Text Link Button` component which typically has no decoration.

## Imagery

The visual language is characterized by bold, two-dimensional geometric and organic shapes (circles, hexagons, triangles, abstract blobs) used as decorative background elements. These shapes employ the vivid accent color palette in a full-bleed, unmasked manner. Photography is either tightly cropped product/screen captures or highly stylized, sometimes within playful mask shapes, focusing on the content being created or the interfaces. Icons are monochromatic, typically filled with Storm Gray or Canvas White, contributing to functionality rather than decoration, distinct from the large geometric shapes. Imagery serves primarily a decorative and atmospheric role, adding life and context without being overly realistic or distracting.

## Layout

The layout primarily uses a full-bleed structure, extending background colors and decorative elements to the viewport edges. Content is generally centered and constrained, often utilizing a single column flow. The hero section is a full-width background with a centered headline and action buttons. Sections establish a visual rhythm through alternating background colors (Canvas White, Sky Tint, Pale Mist) or distinct decorative elements. Content arrangement often features centered stacks or implicit two-column layouts where text and a visual element are horizontally aligned. Navigation is a sticky top bar with a left-aligned logo and right-aligned actions. The page maintains a comfortable density with ample breathing room between sections, emphasizing key information.

## Agent Prompt Guide

### Quick Color Reference
- Text: Storm Gray #111118
- Background: Canvas White #ffffff
- CTA: Electric Blue #2727e6
- Input BG: Pale Mist #f0f6ff
- Accent: Lemon Zest #ffda00
- Secondary Accent: Sky Tint #e1edff

### 3-5 Example Component Prompts
1. Create a primary hero button: Electric Blue background #2727e6, Canvas White text #ffffff, 32px border-radius, `Haas Grot Disp` font (24px, 400 weight, -0.72px letter-spacing), 2.4px top/bottom padding, 9.6px left/right padding. Text: 'See our catalog'.
2. Create a basic white card: Transparent background, no border-radius, no shadow, 16px top/bottom padding, 0px left/right padding. Place a `Haas Grot Text` headline (20px, 400 weight, -0.22px letter-spacing, Storm Gray #111118) inside.
3. Design a pill-shaped search input: Pale Mist background #f0f6ff, Storm Gray #000000 placeholder text, 5000px border-radius, `Haas Grot Text` font (16px, 400 weight), 12px top/bottom padding, 16px left padding, 68px right padding. Placeholder text: 'Search anything'.
4. Generate a section divider and headline: Background color Sky Tint #e1edff, `Haas Grot Disp` headline (42px, 400 weight, -0.84px letter-spacing, Storm Gray #111118). Apply 64px vertical section gap before and after.

## Similar Brands

- **Framer** — Shares a vibrant geometric visual style with bold, flat color accents on a clean light background, and a focus on crisp typography.
- **Gumroad** — Features a similar use of large, friendly pill-shaped buttons and inputs, and an overall playful, colorful approach to digital products.
- **Codecademy** — Employs an educational focus with a clean UI, strong typography, and strategic use of accent colors to highlight interactive elements, though less overtly geometric.
- **Webflow** — Utilizes a highly structured, modern aesthetic with a focus on clear information hierarchy and prominent interactive elements, often with distinct button styles and color usage.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-gray: #111118;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #f0f6ff;
  --color-electric-blue: #2727e6;
  --color-vivid-green: #16ab59;
  --color-lemon-zest: #ffda00;
  --color-sky-tint: #e1edff;
  --color-cool-aqua: #91d8ec;
  --color-coral-glow: #ffbac4;
  --color-sunset-orange: #ff7715;
  --color-flame-red: #ff4141;

  /* Typography — Font Families */
  --font-haas-grot-text: 'Haas Grot Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-disp: 'Haas Grot Disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 20px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.22px;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.16px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.72px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.7px;
  --text-display: 42px;
  --leading-display: 1.1;
  --tracking-display: -0.84px;
  --text-display-lg: 52px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.94px;
  --text-display-xl: 62px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.24px;
  --text-display-xxl: 72px;
  --leading-display-xxl: 1;
  --tracking-display-xxl: -1.44px;
  --text-display-max: 92px;
  --leading-display-max: 1;
  --tracking-display-max: -2.76px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 500px;
  --radius-full-3: 800px;
  --radius-full-4: 5000px;

  /* Named Radii */
  --radius-pill: 48px;
  --radius-input: 5000px;
  --radius-buttons: 32px;
  --radius-default: 24px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-gray: #111118;
  --color-canvas-white: #ffffff;
  --color-pale-mist: #f0f6ff;
  --color-electric-blue: #2727e6;
  --color-vivid-green: #16ab59;
  --color-lemon-zest: #ffda00;
  --color-sky-tint: #e1edff;
  --color-cool-aqua: #91d8ec;
  --color-coral-glow: #ffbac4;
  --color-sunset-orange: #ff7715;
  --color-flame-red: #ff4141;

  /* Typography */
  --font-haas-grot-text: 'Haas Grot Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-disp: 'Haas Grot Disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.35;
  --text-body-lg: 20px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.22px;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.16px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.72px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.7px;
  --text-display: 42px;
  --leading-display: 1.1;
  --tracking-display: -0.84px;
  --text-display-lg: 52px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.94px;
  --text-display-xl: 62px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.24px;
  --text-display-xxl: 72px;
  --leading-display-xxl: 1;
  --tracking-display-xxl: -1.44px;
  --text-display-max: 92px;
  --leading-display-max: 1;
  --tracking-display-max: -2.76px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 500px;
  --radius-full-3: 800px;
  --radius-full-4: 5000px;
}
```
