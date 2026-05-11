# Obviously — Style Reference
> Whiteboard command center

**Theme:** light

Zams employs a clean, purposeful aesthetic built on a stark white canvas punctuated by vivid purple accents. Typography is compact and precise, driving information flow without visual clutter. Interactive elements use a subtle hover animation and a distinct purple to guide user focus, while components remain lightweight, prioritizing function over heavy adornment. The system balances a professional, data-driven feel with approachable, almost playful graphics.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, icon fills, button text for ghost buttons |
| Graphite | `#272727` | `--color-graphite` | Headings, strong text, footer backgrounds |
| Dark Wolf | `#5d5d5d` | `--color-dark-wolf` | Secondary text, subtle borders, placeholder text |
| Slate Gray | `#4f4f4f` | `--color-slate-gray` | Muted text, navigation links |
| Silver Mist | `#e0e0e0` | `--color-silver-mist` | Hairline separators, default button borders |
| Fog White | `#f6f6f6` | `--color-fog-white` | Subtle section backgrounds, alternate card backgrounds |
| Muted Stone | `#a69ea7` | `--color-muted-stone` | Tertiary text, less prominent borders |
| Regal Violet | `#7451f2` | `--color-regal-violet` | Primary action buttons, active states, brand accent |
| Amethyst Border | `#5952a1` | `--color-amethyst-border` | Border for primary action buttons |
| Azure Blue | `#0072c6` | `--color-azure-blue` | Info badges, link accents |
| Sky Tint | `#d6e5ff` | `--color-sky-tint` | Background for informational badges |

## Tokens — Typography

### DM Sans — Body copy, subheadings, navigation links, button text, and badges. Its versatility makes it the workhorse for most UI elements, maintaining a compact yet readable appearance. · `--font-dm-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 9px, 12px, 14px, 15px, 16px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.60
- **Letter spacing:** -0.0200em at 16px, 0.0200em at 14px
- **Role:** Body copy, subheadings, navigation links, button text, and badges. Its versatility makes it the workhorse for most UI elements, maintaining a compact yet readable appearance.

### Martian Mono — Specific, technical information, code snippets, or areas requiring precise, monospaced alignment. Its distinct character provides visual contrast for functional elements. · `--font-martian-mono`
- **Substitute:** SFMono-Regular, Consolas, Liberation Mono, Menlo, monospace
- **Weights:** 400, 500
- **Sizes:** 11px, 16px
- **Line height:** 1.00, 1.10, 1.20, 1.27, 1.60
- **Letter spacing:** 0.0130em at 16px, 0.0220em at 11px
- **OpenType features:** `'ss01' on, 'tnum'`
- **Role:** Specific, technical information, code snippets, or areas requiring precise, monospaced alignment. Its distinct character provides visual contrast for functional elements.

### Lustria — Bold headlines, high-impact titles, and prominent calls to attention. The varied letter-spacing creates a distinctive, almost editorial feel for main content blocks. · `--font-lustria`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 20px, 32px, 36px, 42px, 52px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.0500em at 52px, -0.0480em at 42px, -0.0190em at 20px
- **OpenType features:** `'swsh' 2`
- **Role:** Bold headlines, high-impact titles, and prominent calls to attention. The varied letter-spacing creates a distinctive, almost editorial feel for main content blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| legalDisclaimer | 11px | 1.27 | 0.24px | `--text-legaldisclaimer` |
| body-sm | 14px | 1.6 | 0.28px | `--text-body-sm` |
| heading-sm | 20px | 1.2 | -0.38px | `--text-heading-sm` |
| heading | 32px | 1.1 | -1.54px | `--text-heading` |
| heading-lg | 36px | 1.1 | -1.73px | `--text-heading-lg` |
| display | 52px | 1.1 | -2.6px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 100px |
| buttons | 4px |
| navItems | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.2) 0px 2px 4px 0px` | `--shadow-sm` |

### Layout

- **Page max-width:** 1296px
- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with Regal Violet background (#7451f2), Canvas White text, and a slightly darker Amethyst Border (#5952a1). Rounded with 4px radius. Padding is 8px vertical, 16px horizontal.

### Secondary Ghost Button
**Role:** Alternative action

Ghost button with Canvas White background, Graphite text (#272727), and Silver Mist border (#e0e0e0). Rounded with 4px radius. Padding is 8px vertical, 16px horizontal. Shadow on hover rgba(0, 0, 0, 0.2) 0px 2px 4px 0px.

### Navigation Link Button
**Role:** Tertiary action with minimal styling

Text-only button with Slate Gray text (#4f4f4f), 0px radius, acting as an outlined link with a Silver Mist border (#e0e0e0) only visible on the bottom. Generous padding of 16px all around.

### Integration Grid Item
**Role:** Interactive logo display

Square item with Canvas White background, subtle Silver Mist border on all sides. Content (logo) is centered. Implicit 4px radius. Uses 16px padding on all sides for the inner elements.

### Basic Info Badge
**Role:** Informational label

Small badge with Sky Tint background (#d6e5ff), Azure Blue text (#0072c6), and 100px border radius for a pill shape. Tight 2px vertical, 6px horizontal padding.

### Text-only Badge
**Role:** Subtle categorization

Transparent background, Dark Wolf text (#5d5d5d), 0px radius. No padding, designed for inline labeling.

### Feature Card
**Role:** Content container for features

Canvas White background, subtle border of Silver Mist (#e0e0e0) on all sides. Internal padding is 16px. Implicit 4px radius.

### Stacked Footer Link
**Role:** Standard footer navigation

Link with Dark Wolf text (#5d5d5d) on a Graphite background (#272727). No border or radius, uses 8px padding vertically.

## Do's and Don'ts

### Do
- Always use Regal Violet (#7451f2) for primary calls to action, ensuring it remains the dominant interactive color.
- Maintain high contrast text: use Ink Black (#000000) or Graphite (#272727) on Canvas White (#ffffff) backgrounds for all body and heading copy.
- Implement a 4px `radius` for all interactive buttons and navigation items to convey a consistent soft crispness.
- Utilize `elementGap` of 8px for consistent spacing between distinct UI elements within a component or layout block.
- Ensure headings use the Lustria font with negative letter-spacing (-0.0500em to -0.0190em) to create a distinctive, impactful presentation.
- Leverage Fog White (#f6f6f6) and Canvas White (#ffffff) for subtle background variations between sections, creating visual rhythm without hard divisions.
- Apply `rgba(0, 0, 0, 0.2) 0px 2px 4px 0px` shadow exclusively to ghost buttons on hover for a minimal elevation effect.

### Don't
- Avoid using chromatic colors for large background areas; maintain a dominant Canvas White (#ffffff) or Fog White (#f6f6f6) base.
- Do not use Lustria for body text or small labels; reserve it for headlines to preserve its unique impact and legibility.
- Do not introduce new border radii beyond 4px for buttons/cards and 100px for badges; consistency is key.
- Do not use dark backgrounds without explicit consideration for text contrast, primarily limiting dark areas to the footer and ensuring text is Canvas White (#ffffff).
- Avoid arbitrary letter-spacing on DM Sans; use only the defined -0.0200em for specific elements and 0.0200em for others.
- Do not use any color other than Regal Violet (#7451f2) for primary filled buttons; this is the brand's main interactive color.
- Do not create heavy, ornate components; components should generally be lightweight with minimal borders and subtle shadows if any.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Primary page background, default content area |
| 1 | Subtle Section | `#f6f6f6` | Alternate background for distinct content sections |
| 2 | Info Card | `#d6e5ff` | Background for informational badges or temporary alerts |
| 3 | Elevated Control | `#e0e0e0` | Background for subtle controls or interactive elements |
| 4 | Dominant Action | `#7451f2` | Background for primary calls to action |

## Elevation

- **Ghost Button Hover:** `rgba(0, 0, 0, 0.2) 0px 2px 4px 0px`

## Imagery

The imagery features highly stylized, almost playful 3D illustrations of anthropomorphic geometric shapes with friendly faces. These are used primarily as decorative elements to provide character and visual warmth to otherwise sparse sections. Product screenshots of the UI are clean, flat, and contained within white panels, often showcasing internal tool interfaces with clear data presentation. Icons are predominantly filled, simple, and monochrome, with a few instances of multi-color brand icons for integrations. The overall density of imagery is balanced, with large, impactful illustrations contrasting clear, informative UI screenshots, avoiding photography for a more abstract, brand-controlled visual identity.

## Layout

The page adheres to a max-width 1296px contained layout, centered on a Canvas White background. The hero section is full-width, featuring a prominent centered headline and a large product screenshot set against the white canvas. Sections alternate between full-width and narrower content blocks, often employing a 2-column layout for text and imagery or an integration grid. Vertical spacing between sections is generous and consistent at 64px, contributing to a comfortable, uncrowded feel. The navigation is a sticky top bar, minimal and uncluttered, with Brand Black text links and a Regal Violet Primary Action Button on the far right.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #ffffff
- border: #e0e0e0
- accent: #7451f2
- primary action: #7451f2 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #7451f2 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a feature card: Canvas White background, Silver Mist border. Headline 'Meeting Intelligence that makes every rep close like your top 10%' using Lustria weight 400 at 36px, Graphite text, letter-spacing -1.73px. Body text 'Best reps know their leads...' using DM Sans weight 400 at 15px, Dark Wolf text, letter-spacing -0.3px. Add an Azure Blue Info Badge 'COMING SOON' where appropriate.
- Create an integration grid: Fog White section background. Each grid item is a plain Canvas White square card with an elementGap 8px separating them. Use Muted Stone (#a69ea7) for less prominent border lines, if any.

## Similar Brands

- **Stripe** — Clean white backgrounds, minimal UI elements, and a strong brand accent color for interactive components.
- **Linear** — Focus on highly functional, understated design with precise typography and subtle interactive feedback.
- **Rive** — Integration of playful, simple 3D illustrations within a clean, product-focused UI.
- **Webflow** — Structured, grid-based layouts, emphasis on clear content hierarchy, and subtle animation for interactivity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #272727;
  --color-dark-wolf: #5d5d5d;
  --color-slate-gray: #4f4f4f;
  --color-silver-mist: #e0e0e0;
  --color-fog-white: #f6f6f6;
  --color-muted-stone: #a69ea7;
  --color-regal-violet: #7451f2;
  --color-amethyst-border: #5952a1;
  --color-azure-blue: #0072c6;
  --color-sky-tint: #d6e5ff;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-lustria: 'Lustria', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-legaldisclaimer: 11px;
  --leading-legaldisclaimer: 1.27;
  --tracking-legaldisclaimer: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: 0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.38px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -1.54px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.73px;
  --text-display: 52px;
  --leading-display: 1.1;
  --tracking-display: -2.6px;

  /* Typography — Weights */
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
  --spacing-80: 80px;
  --spacing-104: 104px;

  /* Layout */
  --page-max-width: 1296px;
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-badges: 100px;
  --radius-buttons: 4px;
  --radius-navitems: 4px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-subtle-section: #f6f6f6;
  --surface-info-card: #d6e5ff;
  --surface-elevated-control: #e0e0e0;
  --surface-dominant-action: #7451f2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #272727;
  --color-dark-wolf: #5d5d5d;
  --color-slate-gray: #4f4f4f;
  --color-silver-mist: #e0e0e0;
  --color-fog-white: #f6f6f6;
  --color-muted-stone: #a69ea7;
  --color-regal-violet: #7451f2;
  --color-amethyst-border: #5952a1;
  --color-azure-blue: #0072c6;
  --color-sky-tint: #d6e5ff;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martian-mono: 'Martian Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-lustria: 'Lustria', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-legaldisclaimer: 11px;
  --leading-legaldisclaimer: 1.27;
  --tracking-legaldisclaimer: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: 0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.38px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -1.54px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.73px;
  --text-display: 52px;
  --leading-display: 1.1;
  --tracking-display: -2.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 4px 0px;
}
```
