# BaseHub — Style Reference
> Midnight Command Center: Focused precision on a deep, organized canvas.

**Theme:** dark

BaseHub employs a 'dark modern command center' aesthetic, characterized by a deep, near-black canvas and layered dark gray surfaces. A single vivid orange electrifies interactive elements and critical accents, with subordinate blues for minor semantic cues. Typography is compact and precise, maintaining readability within the dark theme. The system emphasizes clear segmentation through subtle borders rather than heavy shadows or large elevation shifts, creating a focused and organized visual experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#000000` | `--color-deep-space` | Footer background, decorative fills. The deepest black grounding element |
| Canvas Dark | `#040404` | `--color-canvas-dark` | Primary page background, base surface for content blocks |
| Slate Surface | `#0c0c0c` | `--color-slate-surface` | Card backgrounds, slightly elevated surfaces |
| Elevated Ink | `#121212` | `--color-elevated-ink` | Subtly darker elevated surfaces, background for minor body sections |
| Ghost Fill | `#1b1b1b` | `--color-ghost-fill` | Background for ghost buttons and interactive elements in their default state |
| Border Dark | `#252525` | `--color-border-dark` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Faint Gray | `#303030` | `--color-faint-gray` | Background for minor cards or UI elements requiring minimal contrast with darker surfaces |
| Muted Ash | `#646464` | `--color-muted-ash` | Secondary text, descriptive comments, helper text. Soft readability on dark backgrounds |
| Subtle Gray | `#909090` | `--color-subtle-gray` | Tertiary text, inactive icons, hairline borders. Receding visual information |
| Light Text | `#dedede` | `--color-light-text` | Primary text on dark backgrounds, active badge text. High contrast for essential information |
| Bright White | `#f3f3f3` | `--color-bright-white` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| BaseHub Orange | `#ff6c02` | `--color-basehub-orange` | Primary action backgrounds, accent borders, highlights, brand elements. The core accent color evoking activation and importance |
| Orange Bright | `linear-gradient(rgb(255, 108, 2), rgb(255, 155, 81))` | `--color-orange-bright` | Gradient highlight for brand elements, used in conjunction with BaseHub Orange |
| Info Blue | `#55c2ff` | `--color-info-blue` | Informational badges, status indicators, secondary functional accents. Provides a clear, cool contrast to the dominant orange |

## Tokens — Typography

### Geist — Primary typeface for all UI text, headings, and body copy. Its compact nature and precise letter-spacing contribute to the overall technical and focused aesthetic. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 11px, 12px, 13px, 14px, 16px, 18px, 24px, 32px, 48px, 60px
- **Line height:** 1.00, 1.10, 1.14, 1.20, 1.23, 1.40, 1.50
- **Letter spacing:** -0.05em at 60px, -0.04em at 48px, -0.03em at 32px and below
- **Role:** Primary typeface for all UI text, headings, and body copy. Its compact nature and precise letter-spacing contribute to the overall technical and focused aesthetic.

### Geist Mono — Used for code snippets, tags, and specific UI elements requiring a monospaced font. Reinforces the developer-centric nature of the product. · `--font-geist-mono`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.50
- **Letter spacing:** -0.03em
- **Role:** Used for code snippets, tags, and specific UI elements requiring a monospaced font. Reinforces the developer-centric nature of the product.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | — | `--text-caption` |
| body | 14px | 1.4 | -0.05px | `--text-body` |
| subheading | 18px | 1.23 | -0.05px | `--text-subheading` |
| heading | 24px | 1.2 | -0.05px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.05px | `--text-heading-lg` |
| display | 48px | 1.1 | -0.4px | `--text-display` |
| display-lg | 60px | 1 | -0.6px | `--text-display-lg` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 9999px |
| images | 21px |
| buttons | 96px |
| default | 4px |
| small_buttons | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.01) -10px 13px 10px 0px, rgba(0, 0, 0, 0....` | `--shadow-md` |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Main call-to-action button

Filled with BaseHub Orange (#ff6c02), Bright White (#f3f3f3) text at 96px border-radius, 12px horizontal padding. Font: Geist, weight 400.

### Secondary Ghost Button
**Role:** Alternative action button

Ghost Fill (#1b1b1b) background with Light Text (#dedede) on a 96px border-radius, 12px horizontal padding. Font: Geist, weight 400.

### Navigation Link Button
**Role:** Top navigation item

Background transparent, Muted Ash (#646464) text, with an Info Blue (#55c2ff) border on hover. No explicit border-radius (0px). Font: Geist, weight 400.

### Standard Card
**Role:** Content container

Slate Surface (#0c0c0c) background, with a 12px border-radius and a subtle 1px Border Dark (#252525) stroke. No intrinsic padding, content manages its own.

### Quote Card
**Role:** Testimonial or block quote

Elevated Ink (#121212) background with a 16px border-radius and a faint shadow rgba(0, 0, 0, 0.01) -10px 13px 10px, rgba(0, 0, 0, 0.02) -4px 6px 7px, rgba(0, 0, 0, 0.02) -1px 1px 4px 0px. Text is Light Text (#dedede) for quotes, and Muted Ash (#646464) for attribution.

### Tag Badge
**Role:** Categorization or status indicator

Transparent background with Bright White (#f3f3f3) text, 9999px border-radius for pill shape. Often uses Info Blue (#55c2ff) as an accent border or text.

### Input Field
**Role:** Data entry control

Elevated Ink (#121212) background, 4px border-radius, with a 1px Border Dark (#252525) stroke. Text uses Light Text (#dedede).

## Do's and Don'ts

### Do
- Prioritize Deep Space (#000000) for base backgrounds, Canvas Dark (#040404) for main content areas, and Slate Surface (#0c0c0c) for card backgrounds to establish subtle depth.
- Use BaseHub Orange (#ff6c02) exclusively for primary calls-to-action, critical active states, and brand highlights.
- Apply Bright White (#f3f3f3) for main headings and key information, Light Text (#dedede) for primary body text, and Muted Ash (#646464) for secondary or helper text.
- Borders should be hairline 1px strokes using Border Dark (#252525) to define elements rather than heavy shadows or distinct backgrounds.
- Buttons should primarily use a 96px border-radius for a pill shape, with a 4px fallback for smaller interactive elements.
- Maintain a clear visual hierarchy by adjusting text weight within the Geist font family (400, 500, 600) rather than changing font sizes excessively.
- Apply tight letter-spacing to larger headlines (-0.05em at 60px, -0.04em at 48px) and a standard -0.03em for smaller text to preserve its compact feel.

### Don't
- Avoid using multiple vivid colors other than BaseHub Orange and Info Blue to maintain the constrained color palette.
- Do not introduce complex gradients or heavy shadows unless specifically defined for an element like the Quote Card.
- Refrain from using large, decorative imagery that detracts from the UI's functional focus. Imagery should be contained and purposeful.
- Do not use highly saturated or bright backgrounds for content sections; maintain the dark theme for all primary canvases.
- Avoid generic border-radius values (like 8px) on primary components when specific values like 96px for buttons or 12px for cards are defined.
- Do not use line-heights exceeding 1.5, especially for headings, to keep text compact and aligned with the precise aesthetic.
- Do not use system fonts when Geist or Geist Mono are specified, as the custom typefaces are central to the brand's technical feel.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space | `#000000` | Base layer for footer and full-bleed decorative elements, providing ultimate depth. |
| 1 | Canvas Dark | `#040404` | Primary page background layer, setting the dark foundation. |
| 2 | Slate Surface | `#0c0c0c` | Used for main content cards and distinct sections, offering a subtle lift from the canvas. |
| 3 | Elevated Ink | `#121212` | Further elevated elements like input fields or specific interactive components, creating a slight visual hierarchy. |
| 4 | Ghost Fill | `#1b1b1b` | Backgrounds for ghost buttons, indicating interactivity at a shallow elevation. |

## Elevation

- **Quote Card:** `rgba(0, 0, 0, 0.01) -10px 13px 10px 0px, rgba(0, 0, 0, 0.02) -4px 6px 7px 0px, rgba(0, 0, 0, 0.02) -1px 1px 4px 0px`

## Imagery

Imagery is functional and product-focused, featuring crisp screenshots of the BaseHub UI. These are typically contained within cards with rounded corners (4px, 12px, or 21px). Graphics are minimal, often abstract, with a strong emphasis on lines and connections, echoing the developer-centric nature. Icons are primarily outlined or filled with a fine stroke, adhering to the monochrome aesthetic, with BaseHub Orange (#ff6c02) or Info Blue (#55c2ff) for accent. Imagery serves an explanatory or product showcase role, rather than decorative atmosphere, and is generally not full-bleed.

## Layout

The page primarily uses a full-bleed dark background for visual continuity. Content sections often exist within a max-width container, though a specific `pageMaxWidth` is not enforced across the entire site. The hero section is full-bleed, featuring a centered headline and description over the dark background. Sections are separated by consistent vertical spacing (24px `sectionGap`), usually featuring centered text blocks or two-column layouts with text and product visuals. Navigation is a sticky top bar with text links and prominent action buttons. The overall density is comfortable, ensuring textual information remains legible against the dark theme.

## Agent Prompt Guide

**Quick Color Reference**
text: #f3f3f3
background: #040404
border: #252525
accent: #ff6c02
primary action: #ff6c02 (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #ff6c02 background, #303030 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Slate Surface (#0c0c0c) background, 12px border-radius, 1px Border Dark (#252525) stroke. Title 'Streamlined Communication' at 24px Geist weight 500, Bright White (#f3f3f3). Body text at 14px Geist weight 400, Light Text (#dedede).

## Similar Brands

- **Vercel** — Shares a developer-focused dark UI, minimal aesthetic, and reliance on strong accent colors for interactive elements.
- **Linear** — Similar approach to compact typography, high-contrast text on dark backgrounds, and subtle use of borders for UI definition.
- **GitHub** — Employs a utilitarian dark theme with clear code-oriented typefaces and a structured layout for complex information.
- **Notion** — Though lighter, shares the emphasis on a clean, block-based content layout and intuitive, keyboard-driven UI metaphors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #000000;
  --color-canvas-dark: #040404;
  --color-slate-surface: #0c0c0c;
  --color-elevated-ink: #121212;
  --color-ghost-fill: #1b1b1b;
  --color-border-dark: #252525;
  --color-faint-gray: #303030;
  --color-muted-ash: #646464;
  --color-subtle-gray: #909090;
  --color-light-text: #dedede;
  --color-bright-white: #f3f3f3;
  --color-basehub-orange: #ff6c02;
  --color-orange-bright: #ff9b51;
  --gradient-orange-bright: linear-gradient(rgb(255, 108, 2), rgb(255, 155, 81));
  --color-info-blue: #55c2ff;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.05px;
  --text-subheading: 18px;
  --leading-subheading: 1.23;
  --tracking-subheading: -0.05px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.05px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.05px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.4px;
  --text-display-lg: 60px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 21px;
  --radius-full: 96px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 9999px;
  --radius-images: 21px;
  --radius-buttons: 96px;
  --radius-default: 4px;
  --radius-smallbuttons: 4px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.01) -10px 13px 10px 0px, rgba(0, 0, 0, 0.02) -4px 6px 7px 0px, rgba(0, 0, 0, 0.02) -1px 1px 4px 0px;

  /* Surfaces */
  --surface-deep-space: #000000;
  --surface-canvas-dark: #040404;
  --surface-slate-surface: #0c0c0c;
  --surface-elevated-ink: #121212;
  --surface-ghost-fill: #1b1b1b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #000000;
  --color-canvas-dark: #040404;
  --color-slate-surface: #0c0c0c;
  --color-elevated-ink: #121212;
  --color-ghost-fill: #1b1b1b;
  --color-border-dark: #252525;
  --color-faint-gray: #303030;
  --color-muted-ash: #646464;
  --color-subtle-gray: #909090;
  --color-light-text: #dedede;
  --color-bright-white: #f3f3f3;
  --color-basehub-orange: #ff6c02;
  --color-orange-bright: #ff9b51;
  --color-info-blue: #55c2ff;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.05px;
  --text-subheading: 18px;
  --leading-subheading: 1.23;
  --tracking-subheading: -0.05px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.05px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.05px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.4px;
  --text-display-lg: 60px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 21px;
  --radius-full: 96px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.01) -10px 13px 10px 0px, rgba(0, 0, 0, 0.02) -4px 6px 7px 0px, rgba(0, 0, 0, 0.02) -1px 1px 4px 0px;
}
```
