# Mux — Style Reference
> Parchment Grid, Terminal Cards

**Theme:** light

Mux embodies a 'developer's playroom' aesthetic: a grid-lined parchment canvas framing dark, rounded interface cards that feel like sophisticated terminal windows. The overall impression is one of playful precision, with clean, monospace-adjacent typography and vibrant orange accents that highlight interactive elements and functional states. Design components are substantial yet friendly, marked by generous radii and a focus on content hierarchy through contrasting dark cards on a light background. Visual interest is maintained through a subtle underlying grid and whimsical 'robot' illustrations.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, deep card backgrounds, active states |
| Greige Canvas | `#e2e4dd` | `--color-greige-canvas` | Dominant page background, low-prominence surfaces |
| Cloud Gray | `#ffffff` | `--color-cloud-gray` | Card surfaces, subtle background shifts, light text |
| Graphite Card | `#242628` | `--color-graphite-card` | Primary card backgrounds, filled buttons |
| Subtle Ash | `#f4f6f4` | `--color-subtle-ash` | Secondary background variations, light UI elements |
| Ghost Border | `#adb9c6` | `--color-ghost-border` | Subtle borders, ghost button outlines, secondary text |
| Slate Text | `#565e67` | `--color-slate-text` | Muted body text, helper text, inactive UI elements |
| Warm Gray Outline | `#828c97` | `--color-warm-gray-outline` | Tertiary borders, decorative strokes, subtle visual dividers |
| Action Orange | `#ff6100` | `--color-action-orange` | Orange outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Interactive Yellow | `#ffb200` | `--color-interactive-yellow` | Highlight accents, badges, interactive prompts, subtle active states – this sunny yellow provides a secondary point of emphasis |
| Warning Yellow | `#bd8209` | `--color-warning-yellow` | Yellow outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Info Blue | `#0091ff` | `--color-info-blue` | Blue accent for outlined action borders, linked labels, and lightweight interactive emphasis. Use as a supporting accent, not as a status color |
| Success Green | `#00be43` | `--color-success-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Aeonik — All primary headings, subheadings, and most body text — its modern, balanced forms create a strong, clear voice. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 14px, 16px, 18px, 21px, 24px, 50px
- **Line height:** 1.15, 1.20, 1.40, 1.50, 2.00
- **Letter spacing:** 0.0200em
- **OpenType features:** `"dlig", "kern"`
- **Role:** All primary headings, subheadings, and most body text — its modern, balanced forms create a strong, clear voice.

### JetBrainsMono — Code snippets, secondary labels, and functional interface text — its monospace structure emphasizes a developer-centric product. · `--font-jetbrainsmono`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.20, 1.50, 1.60
- **Role:** Code snippets, secondary labels, and functional interface text — its monospace structure emphasizes a developer-centric product.

### Rotonto — Hero headlines and large display text — its distinctive, bold presence provides a playful yet authoritative brand statement. · `--font-rotonto`
- **Substitute:** Chalkboard SE
- **Weights:** 400
- **Sizes:** 50px, 66px
- **Line height:** 1.15, 1.20
- **Letter spacing:** 0.0200em
- **Role:** Hero headlines and large display text — its distinctive, bold presence provides a playful yet authoritative brand statement.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | — | `--text-caption` |
| body-sm | 16px | 1.4 | — | `--text-body-sm` |
| body | 18px | 1.4 | — | `--text-body` |
| body-lg | 21px | 1.4 | — | `--text-body-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 50px | 1.3 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 84 | 84px | `--spacing-84` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 28px |
| images | 112px |
| buttons | 9999px |
| input-focus | 2px |
| inline-elements | 7px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 56px
- **Card padding:** 28px
- **Element gap:** 14px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action

Filled with Action Orange (#ff6100), white Aeonik 700 text, 9999px pill radius, 28px horizontal padding, 14px vertical padding.

### Ghost Outline Button - Dark Text
**Role:** Secondary action or navigation link with neutral text on light backgrounds

Transparent background, Ghost Border (#adb9c6) text and border, 0px radius, 0px padding. Uses Aeonik 400.

### Ghost Outline Button - Light Text
**Role:** Secondary action or navigation link with light text on dark backgrounds

Transparent background, Cloud Gray (#ffffff) text and border, 0px radius, 0px padding. Uses Aeonik 400.

### Ghost Outline Button - Monospace Text
**Role:** Code-focused actions or inline controls

Transparent background, Ink (#000000) text, Warm Gray Outline (#828c97) border, 28px padding. Uses JetBrainsMono 400.

### Dark Terminal Card
**Role:** Main content display for features and examples

Graphite Card (#242628) background, 28px border-radius, no shadow. Content padding is typically 28px.

### Light Content Card
**Role:** Elevated white surface for primary content sections

Cloud Gray (#ffffff) background, 28px border-radius, no shadow. 56px vertical padding, 0px horizontal padding.

### Transcript Dark Card
**Role:** Specialized card for code-like content

Ink (#000000) background, 28px 0px 0px 28px border-radius (asymmetric), no shadow. Content padding is typically 28px.

### Small Feature Card
**Role:** Compact informational card, like partner logos

Transparent background, Cloud Gray (#ffffff) border, 28px border-radius. Padding varies, often 28px for symmetrical layout.

### Inline Status Badge
**Role:** Small functional labels or indicators

Transparent background, Interactive Yellow (#ffb200) text color, 0px border-radius, no padding. Uses JetBrainsMono 400.

## Do's and Don'ts

### Do
- Prioritize the Greige Canvas (#e2e4dd) as the primary page background to establish visual warmth and reduce contrast fatigue.
- Use Dark Terminal Cards (Graphite Card #242628 background, 28px radius) for feature blocks and code examples to create visual depth and a 'terminal' aesthetic.
- Employ Action Orange (#ff6100) exclusively for primary call-to-action buttons and critical interactive states to ensure maximum visibility.
- Apply Aeonik 400 at 16px (1.5 lineHeight) for primary body text, maintaining a 0.0200em letter spacing for crisp readability.
- Round all primary interactive elements like buttons and input fields with a 9999px radius to achieve a 'pill' shape.
- Ensure all section gaps utilize 56px vertical spacing, promoting generous breathing room between content blocks.
- Use JetBrainsMono for all code snippets and developer-focused labels to reinforce the technical brand identity.

### Don't
- Avoid using multiple chromatic colors in close proximity; color should be a focused accent, not a diffuse palette.
- Do not introduce strong drop shadows; the design relies on background color shifts and subtle borders for hierarchy, not Z-axis elevation.
- Refrain from using overly decorative or ornate typography; the system favors clean, functional fonts with a technical edge.
- Do not center-align extensive blocks of body text; left-alignment is preferred for readability within the grid system.
- Avoid generic stock photography; instead, use custom illustrations or highly selective, product-focused imagery.
- Do not use sharp 0px corners on interactive or card components; the system consistently applies rounded radii (28px for cards, 9999px for buttons).
- Avoid dense, information-heavy layouts without sufficient padding; maintain the 'spacious' density with 28px card padding and 56px section gaps.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Greige Canvas | `#e2e4dd` | Dominant page background, grid backdrop |
| 1 | Cloud Gray | `#ffffff` | Primary elevated card surfaces, feature backgrounds |
| 2 | Graphite Card | `#242628` | Darker, functional card backgrounds for code or content presentation |

## Imagery

Mux's imagery is minimalistic and functional, oscillating between custom illustrations of 'Mux Robots' and tightly cropped product screenshots. The robots are geometric, line-art style characters with circuit-board accents, often integrated directly into information blocks or used as whimsical decorative elements. Product screenshots are clean, high-fidelity, and typically contained within the Dark Terminal Cards to showcase UI and code snippets. Photography, when present, features real people in a somewhat candid, professional setting, but is secondary to the technical product visuals. Icons are outlined, simple, and monochromatic, aligning with the clean, developer-centric aesthetic. Imagery serves primarily to explain and showcase product functionality, with a secondary role in adding brand personality through the robot characters.

## Layout

The layout is predominantly a max-width 1200px contained grid, centered within the Greige Canvas (#e2e4dd) page background. The hero section is full-bleed, but its content is centrally aligned and contained, featuring a large headline, subtext, and prominent calls to action. Sections alternate between light (Cloud Gray #ffffff) and dark (Graphite Card #242628) backgrounds, creating a distinct vertical rhythm. Content often appears in a 2-column layout (text-left, image/product-right or vice-versa) or a 3-column card grid for features. A subtle, light gray grid pattern underlies the entire canvas, reinforcing the developer 'blueprint' feel. Navigation is a sticky top bar with left-aligned branding and right-aligned interactive buttons.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #e2e4dd
- border: #adb9c6
- accent: #ffb200
- primary action: #242628 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #242628 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Dark Terminal Card (Graphite Card #242628 background, 28px radius). Headline at 24px Aeonik 700, Cloud Gray (#ffffff). Body text at 18px Aeonik 400, Ghost Border (#adb9c6).
3. Create a navigation button: Ghost Outline Button - Dark Text (transparent background, Ghost Border (#adb9c6) text and border, 0px radius, 0px padding) for 'Developers' link.

## Similar Brands

- **Vercel** — Similar developer-tool focus, clean interface, prominent typography, and a grid-like aesthetic.
- **Prisma** — Clear, functional layout, distinct dark surface cards on a lighter background, and emphasis on code snippets.
- **Linear** — Structured UIs, strong focus on information hierarchy, and a restrained color palette with strategic accents.
- **Stripe** — Sophisticated, product-led design with a balance of spaciousness and content clarity, and well-defined UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-greige-canvas: #e2e4dd;
  --color-cloud-gray: #ffffff;
  --color-graphite-card: #242628;
  --color-subtle-ash: #f4f6f4;
  --color-ghost-border: #adb9c6;
  --color-slate-text: #565e67;
  --color-warm-gray-outline: #828c97;
  --color-action-orange: #ff6100;
  --color-interactive-yellow: #ffb200;
  --color-warning-yellow: #bd8209;
  --color-info-blue: #0091ff;
  --color-success-green: #00be43;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'JetBrainsMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-rotonto: 'Rotonto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-body-lg: 21px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 50px;
  --leading-heading: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-112: 112px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 56px;
  --card-padding: 28px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 7px;
  --radius-xl: 14px;
  --radius-3xl: 28px;
  --radius-full: 112px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 28px;
  --radius-images: 112px;
  --radius-buttons: 9999px;
  --radius-input-focus: 2px;
  --radius-inline-elements: 7px;

  /* Surfaces */
  --surface-greige-canvas: #e2e4dd;
  --surface-cloud-gray: #ffffff;
  --surface-graphite-card: #242628;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-greige-canvas: #e2e4dd;
  --color-cloud-gray: #ffffff;
  --color-graphite-card: #242628;
  --color-subtle-ash: #f4f6f4;
  --color-ghost-border: #adb9c6;
  --color-slate-text: #565e67;
  --color-warm-gray-outline: #828c97;
  --color-action-orange: #ff6100;
  --color-interactive-yellow: #ffb200;
  --color-warning-yellow: #bd8209;
  --color-info-blue: #0091ff;
  --color-success-green: #00be43;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'JetBrainsMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-rotonto: 'Rotonto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-body-lg: 21px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 50px;
  --leading-heading: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 7px;
  --radius-xl: 14px;
  --radius-3xl: 28px;
  --radius-full: 112px;
  --radius-full-2: 9999px;
}
```
