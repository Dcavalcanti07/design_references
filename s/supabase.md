# Supabase — Style Reference
> Midnight Terminal Interface — a dark, organized, and quietly powerful workspace.

**Theme:** dark

Supabase embodies a technical, deeply functional aesthetic like a high-performance terminal where every element serves a clear purpose. Dark, layered surfaces create a sense of depth and focus, akin to illuminated code on a dark screen. The primary green accent color, `Supabase Green`, acts as a confident highlight, drawing attention to interactive elements without being overwhelming. Typography prioritizes clarity and a dense information hierarchy, ensuring readability even with intricate data displays.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Abyss | `#000000` | `--color-midnight-abyss` | Deepest background elements, occasional graphic fill. |
| Ebony Canvas | `#121212` | `--color-ebony-canvas` | Primary page background, base surface for components. |
| Graphite Base | `#242424` | `--color-graphite-base` | Alternative surface background, button background for secondary actions, subtle borders. |
| Steel Surface | `#2e2e2` | `--color-steel-surface` | Card backgrounds, elevated UI elements, default input backgrounds. The subtle deviation from pure black creates visual layering. |
| Carbon Border | `#393939` | `--color-carbon-border` | Input borders, dividers, subtle separators. |
| Iron Outline | `#4d4d4d` | `--color-iron-outline` | Subtle text, icon strokes, secondary graphic elements, subtle borders. |
| Mid-Gray Text | `#898989` | `--color-mid-gray-text` | Muted body text, secondary information, disabled states. |
| Silver Highlight | `#b4b4b4` | `--color-silver-highlight` | Lightest neutral text for contrast on dark backgrounds, secondary navigation items. |
| Whiteout | `#fafafa` | `--color-whiteout` | Primary headings, body text, interactive text on buttons, icons. High contrast for critical information. |
| Supabase Green | `#3ecf8` | `--color-supabase-green` | Key interaction accents, prominent headings, success indicators, interactive links. The signature brand color. |
| Deep Sea Green | `#1f4b37` | `--color-deep-sea-green` | Subtle border for primary action buttons, hover states that deepen the brand green. |
| Forest Call to Action | `#006239` | `--color-forest-call-to-action` | Primary call-to-action button background. Opaque and declarative. |
| Glow Green | `#00c573` | `--color-glow-green` | Link hover states, subtle accent in decorative elements if needed. |
| Shadow Green | `#002918` | `--color-shadow-green` | Rare background color, likely for specific brand moments or deep elements. |

## Tokens — Typography

### Circular — Primary UI font for all headings, body text, labels, and buttons. Offers excellent readability and a strong character with its subtly humanist touch. · `--font-circular`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 36px, 72px
- **Line height:** 1.00, 1.11, 1.20, 1.25, 1.33, 1.38, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0070em
- **Role:** Primary UI font for all headings, body text, labels, and buttons. Offers excellent readability and a strong character with its subtly humanist touch.

### Source Code Pro — Monospaced font for code snippets, technical data, or whenever a fixed-width, precise feel is required. · `--font-source-code-pro`
- **Substitute:** Menlo
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** 0.1000em
- **Role:** Monospaced font for code snippets, technical data, or whenever a fixed-width, precise feel is required.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.56 | -0.007px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.007px | `--text-body-sm` |
| body | 16px | 1.43 | -0.007px | `--text-body` |
| subheading | 18px | 1.38 | -0.007px | `--text-subheading` |
| heading | 24px | 1.33 | -0.007px | `--text-heading` |
| heading-lg | 36px | 1.25 | -0.007px | `--text-heading-lg` |
| display | 72px | 1.11 | -0.007px | `--text-display` |

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
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 6px |
| buttons | 6px |
| pillButtons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |

### Layout

- **Card padding:** 24px

## Components

### Ghost Button
**Role:** secondary action

backgroundColor: transparent, color: #fafafa, border: none, borderRadius: 6px, padding: 8px.

### Secondary Button
**Role:** secondary action

backgroundColor: #242424, color: #fafafa, borderColor: #393939, borderRadius: 6px, padding: 8px 16px.

### Primary Call to Action Button
**Role:** primary action

backgroundColor: #006239, color: #fafafa, borderColor: rgba(62, 207, 142, 0.3), borderRadius: 6px, padding: 8px 16px.

### Alert Pill Button (State of Startups)
**Role:** informational alert

backgroundColor: #121212, color: #fafafa, borderColor: #2e2e2, borderRadius: 9999px, padding: 8px 32px.

### Feature Card
**Role:** content container

backgroundColor: #121212, borderRadius: 16px, boxShadow: none, padding: 24px.

### Text Input (with focus ring)
**Role:** data entry

backgroundColor: rgba(250, 250, 250, 0.027), color: #fafafa, borderColor: #393939, borderRadius: 6px, padding: 8px. Focus state likely uses a #3ecf8 border or shadow.

## Do's and Don'ts

### Do
- Use 'Circular' font at weight 400 or 500 for all UI text, except code blocks.
- Adopt #fafafa for primary text and headings against dark backgrounds to ensure AAA contrast.
- Apply #3ecf8 ('Supabase Green') exclusively for active states, primary links, and key brand affirmations.
- Maintain a clear visual hierarchy by utilizing #121212 as the base surface and #2e2e2 for elevated cards and modals.
- Utilize 6px radius for interactive elements like buttons and inputs, transitioning to 16px for larger content cards.
- Employ the 9999px radius sparingly, only for 'Pill Buttons' that act as prominent announcements or unique navigational elements.
- Ensure all interactive elements have a clear visual feedback using either a color change to 'Glow Green' or a subtle border change to 'Deep Sea Green'.

### Don't
- Avoid arbitrary color usage; every color should map to a defined role in the palette.
- Do not use shadows for elevation; rely on background color changes from #121212 to #2e2e2 to differentiate surface levels.
- Do not apply `Source Code Pro` for general body text or headlines; reserve it specifically for code or data display.
- Refrain from using mixed color backgrounds or gradients unless explicitly defined as a brand graphical element.
- Do not break the established spacing scale; maintain 8px increments or derived values (e.g., 24px, 32px) for consistency.
- Avoid excessive text decoration; links are identified by color ('Supabase Green') rather than underlines or heavy styling.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Ebony Canvas | `#121212` | Primary page background |
| 1 | Steel Surface | `#2e2e2` | Elevated cards, modals, and distinct content sections |
| 2 | Graphite Base | `#242424` | Input backgrounds, secondary button backgrounds, subtle hover states |

## Elevation

Supabase intentionally avoids traditional box shadows for elevation. Instead, depth and hierarchy are communicated through distinct background color shifts. Elements on a higher 'layer' utilize a lighter, less saturated dark tone (#2e2e2e) against the base page background (#121212), creating a clean, high-contrast separation without blur or visual noise. The only shadow detected is a subtle one on buttons, likely for a minimal pressed state, not for general elevation.

## Imagery

The visual language for imagery is primarily functional and technical. Product shots are minimalist, showcasing UI directly against dark backgrounds, often with code-like visual elements. Illustrations, where present, are abstract and geometric, utilizing line art and flat fills in shades of gray and `Supabase Green`. Icons are outlined, minimal, and mono-colored, complementing the overall technical aesthetic. Photography is absent, replaced by stylized graphics or product UI snippets. Images serve an explanatory or demonstrative role rather than decorative one, maintaining a high density of visual information without clutter. The elephant logo is abstracted and used as a subtle background texture.

## Layout

The page adheres to a mostly full-bleed layout, particularly in hero sections, with content centered within an implied max-width. The hero section is characterized by a full-width dark background with a large, centered headline that uses two distinct colors (`Whiteout` and `Supabase Green`) for visual emphasis. Content sections alternate between visually seamless dark backgrounds and slightly lighter dark surfaces for cards. There's a clear rhythm of stacked content blocks and feature sections that often alternate between text on one side and a visual or conceptual graphic on the other. Card grids, typically 3-column, are used to present features, maintaining consistent padding. Navigation is a sticky top bar, minimal and persistent. The overall density is comfortable, providing breathing room around critical information.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): `#fafafa`
- Background (Canvas): `#121212`
- CTA (`Supabase Green`): `#006239`
- Border (Input/Secondary): `#393939`
- Accent (Heading/Link): `#3ecf8e`

### 3 Example Component Prompts
1. Create a hero section with `Ebony Canvas` background. Headline 'Build in a weekend' in `Whiteout` and 'Scale to millions' in `Supabase Green`, both `Circular` font, 72px size, 1.11 lineHeight, -0.007em letterSpacing. Below, create a `Primary Call to Action Button` and a `Secondary Button`.
2. Design a feature card: Use `Steel Surface` background, 16px borderRadius, 24px padding. Inside, place a 'Circular' font, 18px size, 1.38 lineHeight heading in `Whiteout`, followed by 'Circular' font, 14px size, 1.5 lineHeight body text in `Mid-Gray Text`.
3. Implement a navigation bar item: Text 'Pricing' `Circular` font, 16px size, 1.43 lineHeight in `Whiteout`. On hover, the text color changes to `Supabase Green` (`#3ecf8e`).

## Similar Brands

- **Vercel** — Shares a sophisticated dark-mode UI with a single prominent accent color, minimalist typography, and a focus on developer tools and product-centric visuals.
- **GitHub** — Similar dark, code-editor aesthetic, strong emphasis on functional UI elements, subtle use of color for status/interactive elements, and clear typographic hierarchy for technical content.
- **Linear** — Exhibits a highly refined dark theme, meticulous spacing, and a strong reliance on typographic scale and subtle foreground/background color shifts rather than heavy shadows for depth.
- **Stripe (dark mode examples)** — Employs a clean, deep dark background with crisp, readable text and strategic use of a single strong accent color to denote key actions and branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-abyss: #000000;
  --color-ebony-canvas: #121212;
  --color-graphite-base: #242424;
  --color-steel-surface: #2e2e2;
  --color-carbon-border: #393939;
  --color-iron-outline: #4d4d4d;
  --color-mid-gray-text: #898989;
  --color-silver-highlight: #b4b4b4;
  --color-whiteout: #fafafa;
  --color-supabase-green: #3ecf8;
  --color-deep-sea-green: #1f4b37;
  --color-forest-call-to-action: #006239;
  --color-glow-green: #00c573;
  --color-shadow-green: #002918;

  /* Typography — Font Families */
  --font-circular: 'Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-code-pro: 'Source Code Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --tracking-caption: -0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.007px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.007px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.007px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.007px;
  --text-display: 72px;
  --leading-display: 1.11;
  --tracking-display: -0.007px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-224: 224px;

  /* Layout */
  --card-padding: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-pillbuttons: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;

  /* Surfaces */
  --surface-ebony-canvas: #121212;
  --surface-steel-surface: #2e2e2;
  --surface-graphite-base: #242424;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-abyss: #000000;
  --color-ebony-canvas: #121212;
  --color-graphite-base: #242424;
  --color-steel-surface: #2e2e2;
  --color-carbon-border: #393939;
  --color-iron-outline: #4d4d4d;
  --color-mid-gray-text: #898989;
  --color-silver-highlight: #b4b4b4;
  --color-whiteout: #fafafa;
  --color-supabase-green: #3ecf8;
  --color-deep-sea-green: #1f4b37;
  --color-forest-call-to-action: #006239;
  --color-glow-green: #00c573;
  --color-shadow-green: #002918;

  /* Typography */
  --font-circular: 'Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-source-code-pro: 'Source Code Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --tracking-caption: -0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.007px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.007px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.007px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.007px;
  --text-display: 72px;
  --leading-display: 1.11;
  --tracking-display: -0.007px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
}
```
