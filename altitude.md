# Altitude — Style Reference
> Midnight command center

**Theme:** dark

Altitude employs a dark, sophisticated interface reminiscent of a high-end trading terminal. Typography contrasts classic serif headlines with modern sans-serif body text, creating a blend of authority and clarity. Surfaces appear as soft, subtly elevated panels against a deep charcoal canvas, with crisp white text and muted gray accents for depth. The visual system prioritizes precise information delivery within a focused, low-distraction environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Charcoal | `#181818` | `--color-deep-charcoal` | Page backgrounds, elevated card surfaces, table backgrounds |
| Graphite | `#262626` | `--color-graphite` | Interface borders, table headers, subtly elevated UI elements |
| Ghost White | `#eeeeee` | `--color-ghost-white` | Primary text, active states, contrasting borders on dark backgrounds |
| Cloud White | `#ffffff` | `--color-cloud-white` | High-prominence card backgrounds, selected icon fills |
| Ash Gray | `#e4e4e4` | `--color-ash-gray` | Secondary text, muted borders, subtle surface accents |
| Lead Gray | `#323232` | `--color-lead-gray` | Muted text, table borders, subtle background tints |
| Cool Steel | `#5e5d59` | `--color-cool-steel` | Placeholder text, inactive UI elements, subtle gray badges |
| Dark Indigo | `#1a365d` | `--color-dark-indigo` | Decorative border accents, section backgrounds, subtle color hints in charts |
| Vivid Blue | `#2b7fff` | `--color-vivid-blue` | Decorative highlights, background fills for small information blocks |
| Sky Blue | `#5c9fe9` | `--color-sky-blue` | Chart elements, supporting background fills |
| Deep Ocean | `#2b5797` | `--color-deep-ocean` | Subtle background fills, supporting border colors for data visualization |
| Golden Gradient | `linear-gradient(to right bottom, oklch(0.279 0.041 260.031) 0%, oklch(0.208 0.042 265.755) 100%)` | `--color-golden-gradient` | Background for secondary action buttons, indicating selection or hierarchy |

## Tokens — Typography

### Libre Baskerville — Headlines and prominent display text – creates a classic, authoritative feel through serif elegance, contrasting with the modern UI. · `--font-libre-baskerville`
- **Substitute:** Georgia
- **Weights:** 400, 500
- **Sizes:** 36px, 48px, 72px
- **Line height:** 1.10, 1.15, 1.25
- **Letter spacing:** -0.0250em
- **Role:** Headlines and prominent display text – creates a classic, authoritative feel through serif elegance, contrasting with the modern UI.

### Inter — Primary UI text, body copy, navigation, and button labels – provides modern clarity and versatility across all interactive elements. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px, 16px, 18px, 28px
- **Line height:** 1.20, 1.25, 1.33, 1.38, 1.43, 1.50, 1.63
- **Letter spacing:** normal
- **Role:** Primary UI text, body copy, navigation, and button labels – provides modern clarity and versatility across all interactive elements.

### Fira Code — Monospaced text for code snippets, data fields, or command-line like interactions – signals technical content. · `--font-fira-code`
- **Substitute:** monospace
- **Weights:** 400, 600
- **Sizes:** 10px, 14px, 16px
- **Line height:** 1.43, 1.50
- **Letter spacing:** 0.1000em
- **Role:** Monospaced text for code snippets, data fields, or command-line like interactions – signals technical content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.1px | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading | 36px | 1.15 | -0.025px | `--text-heading` |
| heading-lg | 48px | 1.15 | -0.025px | `--text-heading-lg` |
| display | 72px | 1.1 | -0.025px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 136 | 136px | `--spacing-136` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| default | 4px |
| largeCards | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51,...` | `--shadow-md` |
| subtle | `oklab(0 0 0 / 0.2) 0px 0px 0px 1px, rgba(51, 51, 51, 0.05...` | `--shadow-subtle` |
| subtle-2 | `oklab(0.999994 0.0000455678 0.0000200868 / 0.1) 0px 0px 0...` | `--shadow-subtle-2` |
| subtle-3 | `oklab(0.95 0 0 / 0.1) 0px 0px 0px 1px` | `--shadow-subtle-3` |
| subtle-4 | `rgb(232, 110, 88) 0px 0px 0px 2px, rgba(51, 51, 51, 0.05)...` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 72px
- **Element gap:** 8px

## Components

### Primary Outlined Button
**Role:** Call to action button for primary actions.

Ghost White text on a transparent background, with a Ghost White 1px border. Padding is 8px vertical, 16px horizontal; no border radius.

### Compact Outlined Button
**Role:** Smaller, less prominent action buttons often used in toolbars or secondary navigation.

Ghost White text on a transparent background, with a Ghost White 1px border. Padding is 0px, 4px border radius.

### Minimal Chip Button
**Role:** Smallest interactive elements, useful for tags or filters.

Ghost White text on a transparent background, with a Ghost White 1px border. Padding is 6px vertical, 8px horizontal; 2px border radius.

### Ghost Filter Button
**Role:** Subtle filter or selection buttons in light-themed panels.

Foreground color from light card panels on a light gray background, 4px border radius. Used within specific light-themed components.

### Elevated Content Card
**Role:** Primary content containers for information blocks.

Cloud White background with 24px vertical padding and 32px horizontal padding. Features an 8px border-radius and a subtle shadow: rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px.

### Transparent Navigation Card
**Role:** Structural container for navigation elements, often with implicit borders.

Transparent background, no border radius or box shadow. Padding is 0px.

### Dark Overlay Card
**Role:** Elevated dark cards for focused content within dark sections.

Deep Charcoal background with 8px border radius and a 1px oklab(0.95 0 0 / 0.1) border, 16px top padding and 0px bottom/side padding.

### Input Field
**Role:** Standard input fields for text entry.

Transparent background with Ghost White text and a Ghost White 1px bottom border. Padding is 8px vertical, 10px horizontal; no border radius.

### Muted Status Badge
**Role:** Informational tags for categorization or status.

Cool Steel background with semitransparent Ghost White text, 4px border radius. Padding is 2px vertical, 8px horizontal.

## Do's and Don'ts

### Do
- Use Libre Baskerville for all headings to establish a distinguished and authoritative tone, ensuring a consistent letterSpacing of -0.025em.
- Maintain a clear visual hierarchy with Deep Charcoal (#181818) as the primary canvas, contrasting with Cloud White (#ffffff) for prominent card surfaces.
- Apply Ghost White (#eeeeee) for all primary text, interactive elements, and key borders to ensure legibility against dark backgrounds.
- Implement a subtle box-shadow for Elevated Content Cards: rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px, to provide elevation without heavy visual weight.
- Utilize 8px for card border radii and 4px for buttons and badges to create subtle softness while maintaining a structured feel.
- Employ Graphite (#262626) for subtle interface borders and separators, providing definition without harsh lines.
- Structure layout with a minimum sectionGap of 72px for generous vertical breathing room between content blocks.

### Don't
- Avoid using bright, saturated colors for backgrounds or large surface areas; chromatic colors should be reserved for small accents or charts.
- Do not deviate from the established typographic scale and font families; mixing in other fonts or arbitrary sizes will break the brand's sophisticated balance.
- Refrain from heavy, opaque shadows; aim for light, diffused elevation as defined by the system's tokenized shadows.
- Do not introduce square corners; all interactive elements and cards should have a minimum of 4px border-radius.
- Avoid dense, information-heavy sections without appropriate spacing; ensure sectionGap of 72px and elementGap of 8px are respected.
- Do not use highly saturated primary action buttons; actions should be outlined buttons with Ghost White text on a transparent background.
- Never use generic blue as primary UI accent; instead, leverage Dark Indigo (#1a365d) for brand-aligned coloring and Vivid Blue (#2b7fff) for specific highlights.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Charcoal Canvas | `#181818` | Primary page background and base layer for all content. |
| 1 | Graphite Surface | `#262626` | Elevated panels, table headers, and background for certain UI elements. |
| 2 | Cloud White Card | `#ffffff` | Prominent content cards that pop against the dark background. |

## Elevation

- **Elevated Content Card:** `rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px`
- **Primary Outlined Button (Hover/Focus):** `oklab(0 0 0 / 0.2) 0px 0px 0px 1px, rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px`
- **Product Mockup Shadow:** `oklab(0.999994 0.0000455678 0.0000200868 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.3) 0px 8px 24px 0px, rgba(0, 0, 0, 0.2) 0px 2px 8px 0px`

## Imagery

The site predominantly uses product screenshots with a sleek, dark-mode UI, often appearing within a macOS-like window frame. There's a minimal use of abstract geometric graphics like a subtle mountain range line art, serving as decorative atmosphere rather than content. Iconography is primarily monochromatic, outlined, and minimal, echoing the system's restrained aesthetic. Images are rarely full-bleed, usually contained within cards or product mocks, focusing on product showcase and explanatory content in a highly structured, text-dominant layout.

## Layout

The page primarily uses a full-bleed structure without a fixed max-width container, creating an expansive feel. The hero section is full-bleed dark with a prominent centered headline over abstract line art. Content sections alternate between dark backgrounds and light (Cloud White) cards, providing a clear visual rhythm. Content is arranged in left-aligned or centered stacks, occasionally employing a two-column text-left/visual-right pattern. Navigation is a sticky top bar with minimal links and a login button. Vertical spacing between main sections appears generous, contributing to a comfortable density.

## Agent Prompt Guide

Quick Color Reference:
- text: #eeeeee
- background: #181818
- border: #262626
- accent: #1a365d
- primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Deep Charcoal (#181818) background. Headline 'AI for Finance.' in Libre Baskerville weight 400, 72px, #eeeeee, letter-spacing -0.025em. Subtext 'World-class AI that helps bankers and investors win more.' in Inter weight 400, 18px, #eeeeee. Include a 'Request a Demo' button: transparent background, 16px 8px padding, #eeeeee text and 1px border, 0px radius.
2. Create an Elevated Content Card: Cloud White (#ffffff) background, 24px 32px padding, 8px border-radius, with shadow rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px. Inside, place a heading 'Automated Workflows' in Libre Baskerville weight 400, 36px, #181818.
3. Create an Input Field: transparent background, 10px 8px padding, Inter weight 400, 14px, #eeeeee text, with a 1px solid #eeeeee bottom border and 0px radius.

## Similar Brands

- **Replit** — Shares a dark-mode UI with strong typographic contrast and focus on code/data environments.
- **Linear** — Features a similar restrained dark theme, minimal borders, and compact, precise UI elements for productivity.
- **Stripe Dashboards** — Employs a dark, information-rich dashboard aesthetic with careful use of typography and subtle UI surfacing.
- **Vercel** — Utilizes a sophisticated dark theme, prominent sans-serif typography for content, and a clean interface for developers.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-charcoal: #181818;
  --color-graphite: #262626;
  --color-ghost-white: #eeeeee;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #e4e4e4;
  --color-lead-gray: #323232;
  --color-cool-steel: #5e5d59;
  --color-dark-indigo: #1a365d;
  --color-vivid-blue: #2b7fff;
  --color-sky-blue: #5c9fe9;
  --color-deep-ocean: #2b5797;
  --color-golden-gradient: #404040;
  --gradient-golden-gradient: linear-gradient(to right bottom, oklch(0.279 0.041 260.031) 0%, oklch(0.208 0.042 265.755) 100%);

  /* Typography — Font Families */
  --font-libre-baskerville: 'Libre Baskerville', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fira-code: 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.025px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 72px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-default: 4px;
  --radius-largecards: 16px;

  /* Shadows */
  --shadow-md: rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;
  --shadow-subtle: oklab(0 0 0 / 0.2) 0px 0px 0px 1px, rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;
  --shadow-subtle-2: oklab(0.999994 0.0000455678 0.0000200868 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.3) 0px 8px 24px 0px, rgba(0, 0, 0, 0.2) 0px 2px 8px 0px;
  --shadow-subtle-3: oklab(0.95 0 0 / 0.1) 0px 0px 0px 1px;
  --shadow-subtle-4: rgb(232, 110, 88) 0px 0px 0px 2px, rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;

  /* Surfaces */
  --surface-deep-charcoal-canvas: #181818;
  --surface-graphite-surface: #262626;
  --surface-cloud-white-card: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-charcoal: #181818;
  --color-graphite: #262626;
  --color-ghost-white: #eeeeee;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #e4e4e4;
  --color-lead-gray: #323232;
  --color-cool-steel: #5e5d59;
  --color-dark-indigo: #1a365d;
  --color-vivid-blue: #2b7fff;
  --color-sky-blue: #5c9fe9;
  --color-deep-ocean: #2b5797;
  --color-golden-gradient: #404040;

  /* Typography */
  --font-libre-baskerville: 'Libre Baskerville', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fira-code: 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.025px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-md: rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;
  --shadow-subtle: oklab(0 0 0 / 0.2) 0px 0px 0px 1px, rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;
  --shadow-subtle-2: oklab(0.999994 0.0000455678 0.0000200868 / 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.3) 0px 8px 24px 0px, rgba(0, 0, 0, 0.2) 0px 2px 8px 0px;
  --shadow-subtle-3: oklab(0.95 0 0 / 0.1) 0px 0px 0px 1px;
  --shadow-subtle-4: rgb(232, 110, 88) 0px 0px 0px 2px, rgba(51, 51, 51, 0.05) 0px 2px 15px 0px, rgba(51, 51, 51, 0.05) 0px 1px 2px -1px;
}
```
