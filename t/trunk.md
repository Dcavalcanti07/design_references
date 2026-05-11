# Trunk — Style Reference
> Midnight command center, energetic pulse.

**Theme:** dark

Trunk employs a 'digital engineering blueprint' aesthetic: a dark, technical canvas dominated by deep grays and blacks, accented by circuit-like line art and subtle energetic color highlights. Typography is concise and functional, emphasizing density and clarity within constrained blocks. Components feature soft, rounded edges and minimal elevation, promoting a lightweight and efficient user experience typical of development tooling.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#08090b` | `--color-carbon` | Primary surface background, card backgrounds, dark text on light elements |
| Obsidian | `#000000` | `--color-obsidian` | Page background, footer background, deepest dark elements |
| Frost | `#ffffff` | `--color-frost` | Primary text, button backgrounds, interactive elements on dark surfaces |
| Steel Gray | `#232323` | `--color-steel-gray` | Hover states on cards, subtle borders, slightly elevated surface backgrounds |
| Outline Gray | `#e2e8f0` | `--color-outline-gray` | Primary light borders, dividers, subtle inactive element strokes |
| Muted Silver | `#b3b3b5` | `--color-muted-silver` | Secondary text, descriptive body copy, muted icons |
| Ghost Gray | `#c1c5c8` | `--color-ghost-gray` | Tertiary text, helper text, subtle inactive states |
| Whisper White | `#dddddd` | `--color-whisper-white` | Least prominent text, legal copy, very light accent details |
| Slate Shadow | `#89898d` | `--color-slate-shadow` | Subtler background accents, visual texture |
| Vivid Blue | `#2f6eeb` | `--color-vivid-blue` | Violet text accent for links, tags, and emphasized short phrases |
| Verdant Green | `#62c772` | `--color-verdant-green` | Green text accent for links, tags, and emphasized short phrases |
| Flame Orange | `#ec592e` | `--color-flame-orange` | Orange text accent for links, tags, and emphasized short phrases |

## Tokens — Typography

### neue — Primary typeface for all text elements. Features a broad range of weights and compact line heights to allow for dense, yet readable information display, fitting a developer-focused tool. Tighter letter spacing on larger headings creates a refined, intentional feel. · `--font-neue`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 11px, 12px, 14px, 15px, 16px, 17px, 18px, 24px, 36px, 45px, 56px, 60px
- **Line height:** 0.94, 1.00, 1.18, 1.20, 1.25, 1.30, 1.40, 1.50, 1.60
- **Letter spacing:** -0.0280em at 60px, -0.0260em at 56px, -0.0180em at 45px, -0.0130em at 36px, -0.0090em at 24px and below
- **Role:** Primary typeface for all text elements. Features a broad range of weights and compact line heights to allow for dense, yet readable information display, fitting a developer-focused tool. Tighter letter spacing on larger headings creates a refined, intentional feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.3 | -0.16px | `--text-subheading` |
| heading | 24px | 1.25 | -0.21px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.47px | `--text-heading-lg` |
| display | 56px | 0.94 | -1.46px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 18px |
| heroAccent | 999px |
| interactiveElements | 12px |

### Layout

- **Section gap:** 48px
- **Card padding:** 18px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Main call to action

Filled button with Frost background (#ffffff), Carbon text (#08090b), and 18px border radius. Padding is effectively 9px vertical, 12px horizontal after internal element spacing. Used for 'Book a demo'.

### Ghost Secondary Button
**Role:** Secondary action or navigation

Ghost button with transparent background, Carbon text (#08090b), and 0px border radius. Padding is 9px vertical, 12px horizontal. Used for navigation links within the main menu.

### Dark Filled Accent Button
**Role:** Contextual action on dark surfaces

Filled button with Carbon background (#08090b), Frost text (#ffffff), and 18px border radius. Padding is effectively 9px vertical, 12px horizontal. Used for 'Book a demo' in hero.

### Circular Icon Button
**Role:** Navigation or small interactive elements

Small circular button with Steel Gray background (#232323), Frost icon/text (#ffffff), and 50% border radius. Minimal padding, designed to be a compact visual element.

### Elevated Content Card
**Role:** Displaying features or testimonials with visual separation

Card with Carbon background (#08090b) and 24px border radius. Internal padding is generous at 36px vertical, 18px horizontal. No explicit shadow, relies on background contrast for definition.

### Testimonial Card
**Role:** Displaying short quotes or partner logos

Card with transparent background and 18px border radius. Internal padding 24px all around. Used for testimonial cards with a subtle dark border.

### Text Input Field
**Role:** Collecting user input

Transparent background input with Frost text (#ffffff). Border is an Outline Gray (#e2e8f0) bottom border, or fully bordered with same color. Padding is 0px vertical, 14.25px horizontal. No explicit border radius on main input.

## Do's and Don'ts

### Do
- Prioritize Carbon (#08090b) or Obsidian (#000000) for all primary backgrounds and surfaces.
- Use Frost (#ffffff) for primary text on dark backgrounds and for primary button fills.
- Apply 18px border radius to all interactive buttons and 24px to main content cards.
- Utilize interne bold for headlines and body text to ensure high legibility and presence.
- Employ Verdant Green (#62c772), Vivid Blue (#2f6eeb), and Flame Orange (#ec592e) sparingly, primarily for accenting keywords or conveying status, not for general UI elements.
- Maintain tight letter spacing, especially for larger text sizes, as specified in the typography section, to enhance visual density.
- Divide content sections with generous vertical spacing (48px default) to create clear reading rhythm, even on dark backgrounds.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; maintain the dark, muted aesthetic.
- Do not introduce strong shadows or excessive elevation; rely on background color contrast and subtle borders for depth.
- Refrain from using overly decorative fonts or varying typefaces; stick to the specified 'neue' family to maintain consistency.
- Do not use small border radii (under 12px) for primary elements; soft rounded corners are a key identifier.
- Avoid generic icon styles; prefer outlined, mono-color icons with a technical aesthetic.
- Do not use Verdant Green, Vivid Blue, or Flame Orange as primary button background colors; these are accent colors for text and small indicators only.
- Do not center-align large blocks of body text; left-alignment is preferred for readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Obsidian Canvas | `#000000` | Base page background, deepest interactive zones. |
| 1 | Carbon Surface | `#08090b` | Primary component backgrounds like cards, default dark container background. |
| 2 | Steel Gray Component | `#232323` | Subtle interactive element backgrounds, specific hovered states, background for circular buttons. |
| 3 | Slate Shadow Accent | `#89898d` | Minor accent element backgrounds, subtle visual anchors. |
| 4 | Frost Hover | `#ffffff` | Primary button fill on dark, elevated hover states for interactive elements. |

## Imagery

The imagery consists of technical line-art illustrations depicting abstract infrastructure, possibly showing CI/CD pipelines or network flows, rendered in white on dark backgrounds. These graphics are contained within sections and serve a decorative and atmospheric purpose, hinting at the product's technical nature without literal depictions. The imagery reinforces a 'blueprint' or 'schematic' feel. Icons are monochrome outlined or filled, with a consistent stroke weight, and typically appear alongside text for clarity.

## Layout

The page uses a contained layout with some full-bleed sections, maintaining an overall max-width although a specific `pageMaxWidth` value is not provided, the content remains centrally aligned with ample side margins. The hero section is full-bleed, dark, featuring a centered headline and subtle background line art. Content sections alternate between visually distinct areas (e.g., darker backgrounds with product screenshots, then lighter-on-dark content with testimonial cards). Most content blocks follow a stacked or two-column text-right/image-left pattern. Navigation is a sticky top bar with a left-aligned logo and right-aligned links and buttons. Card grids, particularly for testimonials, are present and appear to be 3 or 4 columns.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e2e8f0
accent: #62c772
primary action: #08090b (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #08090b background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a dark content card: background #08090b, border radius 24px, 36px vertical padding and 18px horizontal padding. Title 'Quarantine flaky tests' in Frost (#ffffff) neue weight 500 at 24px, body text 'Stay on top of flakes' in Muted Silver (#b3b3b5) neue weight 400 at 14px.
3. Create a ghost navigation button: transparent background, text 'Docs' in Carbon (#08090b) neue weight 400 at 16px, 9px vertical padding and 12px horizontal padding, no border radius.
4. Produce a section headline: text 'How Trunk improves developer productivity' in Frost (#ffffff) neue weight 700 at 45px, letter-spacing -0.81px, with a top margin of 48px from the previous section.

## Similar Brands

- **Vercel** — Similar dark-mode UI with functional typography and subtle accent colors for code/status indicators.
- **Linear** — Shared aesthetic of compact, information-dense interfaces with strong typographic hierarchy and minimal visual clutter against a dark theme.
- **GitHub** — Employs a precise, developer-centric design language with high contrast text on dark backgrounds and structured information presentation.
- **Datadog** — Uses dark themes and data-rich interfaces, often with line-art graphics and functional component design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #08090b;
  --color-obsidian: #000000;
  --color-frost: #ffffff;
  --color-steel-gray: #232323;
  --color-outline-gray: #e2e8f0;
  --color-muted-silver: #b3b3b5;
  --color-ghost-gray: #c1c5c8;
  --color-whisper-white: #dddddd;
  --color-slate-shadow: #89898d;
  --color-vivid-blue: #2f6eeb;
  --color-verdant-green: #62c772;
  --color-flame-orange: #ec592e;

  /* Typography — Font Families */
  --font-neue: 'neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.16px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.21px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.47px;
  --text-display: 56px;
  --leading-display: 0.94;
  --tracking-display: -1.46px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 18px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 18px;
  --radius-heroaccent: 999px;
  --radius-interactiveelements: 12px;

  /* Surfaces */
  --surface-obsidian-canvas: #000000;
  --surface-carbon-surface: #08090b;
  --surface-steel-gray-component: #232323;
  --surface-slate-shadow-accent: #89898d;
  --surface-frost-hover: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #08090b;
  --color-obsidian: #000000;
  --color-frost: #ffffff;
  --color-steel-gray: #232323;
  --color-outline-gray: #e2e8f0;
  --color-muted-silver: #b3b3b5;
  --color-ghost-gray: #c1c5c8;
  --color-whisper-white: #dddddd;
  --color-slate-shadow: #89898d;
  --color-vivid-blue: #2f6eeb;
  --color-verdant-green: #62c772;
  --color-flame-orange: #ec592e;

  /* Typography */
  --font-neue: 'neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.16px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.21px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.47px;
  --text-display: 56px;
  --leading-display: 0.94;
  --tracking-display: -1.46px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;
}
```
