# Figma — Style Reference
> digital drafting board

**Theme:** light

Figma's design language evokes a sophisticated workspace feel, balancing clean utility with creative vibrancy. Dominant neutral tones provide a calm canvas, allowing strategic pops of vivid color to highlight interactive elements and brand identity. This interplay creates both clarity and engagement, reflecting a tool built for focused work yet enabling imaginative output. Rounded 'pill' buttons and soft shadows on cards suggest approachability within an otherwise crisp, almost systematic aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, primary text on dark backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, icon fills, borders, main navigation text, secondary button backgrounds |
| Figma Gray | `#595959` | `--color-figma-gray` | Muted body text, secondary text, subtle borders |
| Surface Off-White | `#e2e2e2` | `--color-surface-off-white` | Background for subtle surface distinction, like some card states or section backgrounds |
| Action Violet | `#4d49fc` | `--color-action-violet` | Primary Call-to-Action button fills — a vibrant focus point against the neutral backdrop for interaction |
| Link Blue | `#00b6ff` | `--color-link-blue` | Link backgrounds used as categorical markers, decorative fills in illustrations or brand elements |
| Link Green | `#24cb71` | `--color-link-green` | Link backgrounds used as categorical markers, decorative fills in illustrations or brand elements |
| Link Orange | `#ff7237` | `--color-link-orange` | Link backgrounds used as categorical markers, decorative fills in illustrations or brand elements |
| Figma Green | `#e4ff97` | `--color-figma-green` | Link backgrounds used as categorical markers |
| Figma Violet | `#c4baff` | `--color-figma-violet` | Link backgrounds used as categorical markers |
| Figma Ash | `#95b9ac` | `--color-figma-ash` | Link backgrounds used as categorical markers |
| Figma Pink | `#cb9fd2` | `--color-figma-pink` | Link backgrounds used as categorical markers |
| Figma Blush | `#ffc9c1` | `--color-figma-blush` | Link backgrounds used as categorical markers |
| Error Red | `#721c1c` | `--color-error-red` | Observed in link backgroundColor. |
| Figma Teal | `#c7f8fb` | `--color-figma-teal` | Link backgrounds used as categorical markers |
| Gradient Teal Bright | `conic-gradient(rgb(51, 223, 223) 0deg, rgb(51, 223, 223) 18deg, rgba(0, 0, 0, 0) 18deg, rgba(0, 0, 0, 0) 30deg)` | `--color-gradient-teal-bright` | Component accent borders and text, part of custom conic gradients |
| Gradient Amber | `conic-gradient(rgb(185, 142, 1) 0deg, rgb(185, 142, 1) 18deg, rgba(0, 0, 0, 0) 18deg, rgba(0, 0, 0, 0) 30deg)` | `--color-gradient-amber` | Component accent borders and text, part of custom conic gradients |

## Tokens — Typography

### figmaSans — Primary typeface for all UI text, headings, and body content. Its custom design provides a distinct, clean aesthetic. The range of weights allows for a nuanced hierarchy, from light to bold. · `--font-figmasans`
- **Substitute:** Inter
- **Weights:** 320, 330, 340, 400, 450, 480, 520, 700
- **Sizes:** 16px, 18px, 24px, 56px, 72px
- **Line height:** 1.00, 1.10, 1.30, 1.35, 1.40, 1.45
- **Letter spacing:** -0.007, -0.008, -0.009, -0.015, -0.02
- **OpenType features:** `"kern"`
- **Role:** Primary typeface for all UI text, headings, and body content. Its custom design provides a distinct, clean aesthetic. The range of weights allows for a nuanced hierarchy, from light to bold.

### figmaMono — Monospaced typeface used for specific technical contexts or code snippets, maintaining legibility with generous letter-spacing. Its presence nods to developers and technical users. · `--font-figmamono`
- **Substitute:** JetBrains Mono
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.00, 1.30
- **Letter spacing:** 0.05, 0.03
- **OpenType features:** `"kern"`
- **Role:** Monospaced typeface used for specific technical contexts or code snippets, maintaining legibility with generous letter-spacing. Its presence nods to developers and technical users.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.3 | 0.6px | `--text-caption` |
| body-sm | 16px | 1.45 | -0.112px | `--text-body-sm` |
| body | 18px | 1.4 | -0.144px | `--text-body` |
| heading | 24px | 1.35 | -0.216px | `--text-heading` |
| heading-lg | 56px | 1.1 | -0.84px | `--text-heading-lg` |
| display | 72px | 1 | -1.44px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 2px |
| buttons | 50px |
| smallButtons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 24px 70px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Text Button
**Role:** navigation link, secondary action

backgroundColor=rgba(0, 0, 0, 0), color=rgb(0, 0, 0), border-radius=0px, padding=8px. Used for navigation and tertiary actions, blending seamlessly into the background.

### Primary Pill Button
**Role:** primary action

backgroundColor=rgba(77, 73, 252, 1), color=rgb(255, 255, 255), borderRadius=50px, paddingTop=8px, paddingRight=18px, paddingBottom=10px, paddingLeft=18px. Distinctive rounded shape and solid fill make it stand out as the key interactive element.

### Secondary Pill Button (Outlined)
**Role:** secondary action

backgroundColor=rgb(255, 255, 255), color=rgb(0, 0, 0), borderTopColor=rgb(0, 0, 0), borderRadius=50px, paddingTop=8px, paddingRight=18px, paddingBottom=10px, paddingLeft=18px. Offers an alternative call to action with a pill shape and bordered appearance.

### Circular Icon Button (Transparent BG)
**Role:** icon button, subtle interaction

backgroundColor=rgba(0, 0, 0, 0.08), color=rgb(0, 0, 0), borderRadius=50%, padding=0px. Used for subtle, icon-only interactions, typically with a light background tint on hover/active states.

### Circular Icon Button (Ghost White)
**Role:** icon button, subtle interaction on dark BG

backgroundColor=rgba(255, 255, 255, 0.16), color=rgb(255, 255, 255), borderRadius=50%, padding=0px. Icon-only interactions for dark contexts, appearing as a ghost element with a white tint.

### Base Card
**Role:** content container

backgroundColor=rgba(0, 0, 0, 0), borderRadius=0px, boxShadow=none, padding=0px. Used as a structural content block without explicit visual styling beyond its defined space.

### Elevated Marketing Card
**Role:** marketing spotlight, showcase

backgroundColor=rgb(230, 230, 230), borderRadius=18px, boxShadow=rgba(0, 0, 0, 0.1) 0px 24px 70px 0px, padding=0px. Features a pronounced shadow and distinct background, designed to visually pop out from the page.

### Standard Content Card
**Role:** information display, nested content

backgroundColor=rgb(255, 255, 255), borderRadius=16px, boxShadow=none, padding=16px. Clean white background and rounded corners without an explicit shadow, serving as a contained information block.

## Do's and Don'ts

### Do
- Use 'Canvas White' (#ffffff) as the primary page background color for a clean, open feel.
- Apply 'Ink Black' (#000000) for all primary text elements to ensure high contrast and readability.
- Reserve 'Action Violet' (#4d49fc) exclusively for primary Call-to-Action button backgrounds to maintain its impact and clear interaction signal.
- Utilize 'Figma Sans' with weight 700 for headings, and 'Figma Sans' weight 400 for body text to establish a clear typographic hierarchy.
- Employ a 'Primary Pill Button' (backgroundColor '#4d49fc', borderRadius '50px') for all main conversions.
- Maintain a comfortable rhythm across sections by using a 'sectionGap' of '24px'.
- Apply a 'cardPadding' of '16px' within content cards to provide adequate breathing room around their content.

### Don't
- Do not use 'Action Violet' (#4d49fc) for decorative elements or non-interactive text to avoid diluting its primary action significance.
- Avoid applying strong shadows to elements other than designated 'Elevated Marketing Card' components to preserve visual flatness and focus.
- Do not use letter spacing variations on body text; keep 'figmaSans' body text at its default (normal) tracking for optimal readability.
- Do not introduce sharp corners on buttons; enforce a '50px' borderRadius for 'Primary Pill Button' or '8px' for smaller 'small Buttons'.
- Refrain from using heavily saturated brand colors (e.g., 'Link Blue', 'Link Green') as primary text or background colors; their role is for accents and categorizing links.
- Do not deviate from the established 'comfortable' spacing density; consistently apply a base unit of '4px' to maintain visual rhythm.
- Avoid using the 'figmaMono' font for extensive body passages; its use is specific for technical code-like content, not general reading.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base layer. |
| 1 | Surface Off-White | `#e2e2e2` | Subtle background for distinct sections or card-like groupings without explicit borders or shadows. |

## Elevation

- **Elevated Marketing Card:** `rgba(0, 0, 0, 0.1) 0px 24px 70px 0px`

## Imagery

The visual language blends product screenshots showcasing complex UI with dynamic, colorful abstract graphics. Product screenshots are typically contained within cards, sometimes overlapping or presented on a slight angle, giving a sense of dynamic motion without being distracting. The abstract graphics utilize vivid, often gradient-infused colors that serve a decorative, atmospheric role, breaking up the otherwise clean UI. Icons are simple, outlined, and monochromatic, used sparingly to support navigation and feature identification. Imagery is used to convey both the 'what' (product UI) and the 'feel' (creative energy).

## Layout

The page primarily employs a max-width contained layout for content, centered to create a focused reading experience. The hero section often breaks this containment, presenting full-bleed, dynamic visuals with a prominent, centralized headline overlay. Sections alternate between simple text blocks and more complex arrangements featuring image-left/text-right or vise-versa. Card grids are used for showcasing multiple examples or products, typically in a responsive column layout. There's a consistent vertical rhythm with 'sectionGap' at '24px', suggesting a comfortable density rather than information-heavy blocks, allowing visuals to breathe. A sticky top navigation bar with clear calls to action reinforces persistent brand presence.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #000000
- accent: #4d49fc
- primary action: #4d49fc (filled action)

Example Component Prompts:
- Create a Primary Action Button: #4d49fc background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a content card: 'Standard Content Card' with 'Canvas White' background, '16px' border-radius, and '16px' padding. Inside, use 'Ink Black' for titles (24px 'figmaSans' weight 520) and 'Figma Gray' for body text (16px 'figmaSans' weight 400).
- Create a Primary Action Button: #4d49fc background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Render an 'Elevated Marketing Card': 'Surface Off-White' background, '18px' border-radius, with the specified shadow (rgba(0, 0, 0, 0.1) 0px 24px 70px 0px).

## Similar Brands

- **Canva** — Bright, contrasting accent colors against a clean, mostly white interface, with a focus on approachable design tools.
- **Webflow** — Clear separation of content blocks with subtle surface changes, and a strong emphasis on interactive elements guided by brand colors.
- **Notion** — Minimalist aesthetic with high contrast text, functional use of color for categorization, and a sophisticated approach to typography.
- **Linear** — Clean, almost sparse UI, relying on precise typography and a limited but impactful accent color palette to guide user attention.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-figma-gray: #595959;
  --color-surface-off-white: #e2e2e2;
  --color-action-violet: #4d49fc;
  --color-link-blue: #00b6ff;
  --color-link-green: #24cb71;
  --color-link-orange: #ff7237;
  --color-figma-green: #e4ff97;
  --color-figma-violet: #c4baff;
  --color-figma-ash: #95b9ac;
  --color-figma-pink: #cb9fd2;
  --color-figma-blush: #ffc9c1;
  --color-error-red: #721c1c;
  --color-figma-teal: #c7f8fb;
  --color-gradient-teal-bright: #33dfdf;
  --gradient-gradient-teal-bright: conic-gradient(rgb(51, 223, 223) 0deg, rgb(51, 223, 223) 18deg, rgba(0, 0, 0, 0) 18deg, rgba(0, 0, 0, 0) 30deg);
  --color-gradient-amber: #b98e01;
  --gradient-gradient-amber: conic-gradient(rgb(185, 142, 1) 0deg, rgb(185, 142, 1) 18deg, rgba(0, 0, 0, 0) 18deg, rgba(0, 0, 0, 0) 30deg);

  /* Typography — Font Families */
  --font-figmasans: 'figmaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figmamono: 'figmaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --tracking-caption: 0.6px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.45;
  --tracking-body-sm: -0.112px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: -0.144px;
  --text-heading: 24px;
  --leading-heading: 1.35;
  --tracking-heading: -0.216px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.84px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-w320: 320;
  --font-weight-w330: 330;
  --font-weight-w340: 340;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-w480: 480;
  --font-weight-w520: 520;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 2px;
  --radius-buttons: 50px;
  --radius-smallbuttons: 8px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 24px 70px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-surface-off-white: #e2e2e2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-figma-gray: #595959;
  --color-surface-off-white: #e2e2e2;
  --color-action-violet: #4d49fc;
  --color-link-blue: #00b6ff;
  --color-link-green: #24cb71;
  --color-link-orange: #ff7237;
  --color-figma-green: #e4ff97;
  --color-figma-violet: #c4baff;
  --color-figma-ash: #95b9ac;
  --color-figma-pink: #cb9fd2;
  --color-figma-blush: #ffc9c1;
  --color-error-red: #721c1c;
  --color-figma-teal: #c7f8fb;
  --color-gradient-teal-bright: #33dfdf;
  --color-gradient-amber: #b98e01;

  /* Typography */
  --font-figmasans: 'figmaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figmamono: 'figmaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.3;
  --tracking-caption: 0.6px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.45;
  --tracking-body-sm: -0.112px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: -0.144px;
  --text-heading: 24px;
  --leading-heading: 1.35;
  --tracking-heading: -0.216px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.84px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 24px 70px 0px;
}
```
