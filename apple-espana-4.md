# Apple (España) — Style Reference
> Minimalist Dark Immersive

**Theme:** dark

Apple's design system in España uses a stark, high-contrast dark theme with minimal chromatic accents, creating a premium and focused atmosphere. Typography is primarily utilitarian, allowing content to take center stage, while rounded corners and subtle background variations provide surface differentiation. The visual language emphasizes product imagery, creating a highly immersive and product-centric user experience. Interactions are swift and responsive, devoid of heavy animations, prioritizing direct engagement.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `linear-gradient(rgb(0, 0, 0), rgb(17, 17, 17))` | `--color-midnight-canvas` | Primary page background, modal overlays, header background, base for gradients; Subtle background gradient for dark sections, contributing to depth |
| Deep Charcoal | `#111111` | `--color-deep-charcoal` | Section backgrounds, elevated UI elements, base for secondary gradients |
| Graphite | `#1d1d1f` | `--color-graphite` | Primary text color in light theme, subtle divider lines, card backgrounds on dark theme |
| Ghost Gray | `#333336` | `--color-ghost-gray` | Navigation backgrounds, button backgrounds |
| Slate Text | `#424245` | `--color-slate-text` | Muted body text against dark backgrounds |
| Silver Text | `#86868b` | `--color-silver-text` | Secondary text, descriptive elements, inactive states |
| Light Ghost | `#cccccc` | `--color-light-ghost` | Navigation item text, button borders and inactive icon fills |
| White Surface | `#ffffff` | `--color-white-surface` | Card backgrounds, text color on dark backgrounds, active icon fills |
| Off-White Accent | `#f5f5f7` | `--color-off-white-accent` | Section backgrounds, badge backgrounds, primary text color in light mode |
| Branded Blue | `#0071e3` | `--color-branded-blue` | Primary action buttons, interactive link highlights, focus states. This color stands out against the dark neutrals |
| Sky Link Blue | `#0066cc` | `--color-sky-link-blue` | Standard link color for supplementary information; a vibrant alternative to the primary action blue |
| Action Blue | `#2997ff` | `--color-action-blue` | Outlined button borders and link text indicating action or further detail |
| Vibrant Orange | `#f56900` | `--color-vibrant-orange` | Decorative highlights, accent text, and borders for specific content sections |
| Plum Accent | `#8668ff` | `--color-plum-accent` | Infrequent highlights, decorative accents in product descriptions |
| Teal Contrast | `#00a1b3` | `--color-teal-contrast` | Infrequent highlights, decorative accents for specific features |

## Tokens — Typography

### SF Pro Text — Primary text font for body copy, navigational links, buttons, and captions. Its broad range of weights and sizes supports functional and informational roles. · `--font-sf-pro-text`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 10px, 12px, 14px, 17px, 20px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.33, 1.43, 1.47, 1.83
- **Letter spacing:** -0.037em at 10px, -0.022em at 12px, -0.019em at 14px, -0.016em at 17px, -0.010em at 20px, -0.003em at 44px
- **OpenType features:** `"numr"`
- **Role:** Primary text font for body copy, navigational links, buttons, and captions. Its broad range of weights and sizes supports functional and informational roles.

### SF Pro Display — Used for headlines and prominent text elements, this font's slightly condensed appearance at larger sizes, combined with precise letter spacing, creates a commanding yet refined presence. · `--font-sf-pro-display`
- **Substitute:** Inter
- **Weights:** 600, 700
- **Sizes:** 19px, 21px, 24px, 28px, 32px, 56px, 80px
- **Line height:** 1.00, 1.05, 1.13, 1.14, 1.17, 1.19, 1.21
- **Letter spacing:** 0.012em at 80px, 0.011em at 56px, 0.009em at 32px, 0.007em at 28px, 0.004em at 24px, -0.005em at 21px, -0.015em at 19px
- **OpenType features:** `"numr"`
- **Role:** Used for headlines and prominent text elements, this font's slightly condensed appearance at larger sizes, combined with precise letter spacing, creates a commanding yet refined presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.47 | -0.37px | `--text-caption` |
| body | 14px | 1.24 | -0.27px | `--text-body` |
| body-lg | 17px | 1.18 | -0.27px | `--text-body-lg` |
| subheading | 19px | 1.21 | -0.28px | `--text-subheading` |
| heading | 24px | 1.17 | 0.1px | `--text-heading` |
| heading-lg | 44px | 1 | -0.13px | `--text-heading-lg` |
| display | 80px | 1 | 0.96px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 28px |
| links | 10px |
| buttons | 980px |
| elements | 28px |

### Layout

- **Section gap:** 89px
- **Card padding:** 28px
- **Element gap:** 10px

## Components

### Navigation Link
**Role:** Primary navigation item

Ghost button style, `SF Pro Text` weight 400, neutral color `Light Ghost` (#cccccc), no distinct background. On interaction, it may show active states but appears text-only by default.

### Secondary Button
**Role:** Outlined button for secondary actions or information

Background `Deep Charcoal` (#111111), text `White Surface` (#ffffff). Border radius of 36px, mimicking a pill shape. `SF Pro Text` font, weight 600.

### Filled Primary Button
**Role:** Primary Call to Action

Filled button with `Branded Blue` (#0071e3) background and `White Surface` (#ffffff) text. Highly rounded with 980px border-radius. Padding 8px vertical, 15px horizontal. `SF Pro Text` font, weight 600.

### Ghost Text Button
**Role:** Minimalist button for less prominent actions, often within content.

Transparent background with text color `Graphite` (#1d1d1f). Uses `SF Pro Text` at various weights. Radius 28px for a subtle rounded edge.

### Informational Card (Dark)
**Role:** Container for content sections on dark backgrounds.

Background `Graphite` (#1d1d1f), no shadow, 28px border radius. Padding is context-dependent, starting from 0px.

### Informational Card (Light)
**Role:** Container for content sections on light backgrounds.

Background `White Surface` (#ffffff), no shadow, 28px border radius. Padding is context-dependent, starting from 0px.

### Feature Badge (Dark)
**Role:** Small, contained labels for features on dark backgrounds.

Background `Deep Charcoal` (#111111), text `Off-White Accent` (#f5f5f7). No border-radius or padding is explicitly set, suggesting content-driven dimensions.

### Feature Badge (Light)
**Role:** Small, contained labels for features on light backgrounds.

Background `Off-White Accent` (#f5f5f7), text `Graphite` (#1d1d1f). No border-radius or padding is explicitly set, suggesting content-driven dimensions.

## Do's and Don'ts

### Do
- Always use `Midnight Canvas` (#000000) for primary page backgrounds to maintain the dark theme.
- Apply `Branded Blue` (#0071e3) exclusively for primary call-to-action buttons due to its distinct contrast.
- Round all interactive elements like buttons and cards with a `radius` of `28px` or `980px` for a modern, approachable feel.
- Maintain high typographic contrast using `White Surface` (#ffffff) for text on `Midnight Canvas` (#000000) or `Deep Charcoal` (#111111) backgrounds.
- Utilize `SF Pro Display` for all main headlines and `SF Pro Text` for body copy, adhering to their specific letter-spacing rules.
- Employ `elementGap` of `10px` for consistent tight spacing between inline items and `sectionGap` of `89px` for vertical rhythm between major sections.
- Prioritize product photography as the main visual element, presenting it full-bleed in sections with minimal UI distraction.

### Don't
- Do not introduce new chromatic colors for interactive elements; stick to `Branded Blue` (#0071e3) for primary actions.
- Avoid arbitrary elevation or shadows; surfaces differentiate through background color shifts rather than overlaid styles.
- Do not use `SF Pro Text` for main headings – reserve `SF Pro Display` for its distinct character at larger sizes.
- Never center align large blocks of body text; maintain left alignment for readability.
- Do not use hard-edged, 0px radius corners on cards or primary buttons; maintain the established `28px` or `980px` radius.
- Avoid cluttering sections with excessive iconography; use icons sparingly for functional cues only.
- Do not apply heavy animations or transitions; interactions should feel immediate with moderate duration `0.1s` ease transitions.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Canvas | `#000000` | Base page background, full-bleed hero sections, primary unadorned canvas. |
| 1 | Deep Charcoal | `#111111` | Section backgrounds, navigation panels, subtly elevated content blocks. |
| 2 | Graphite | `#1d1d1f` | Card backgrounds, focused content areas, providing a minimal separation from `Deep Charcoal`. |

## Imagery

Imagery is centered on high-fidelity product photography, often full-bleed or tightly cropped against stark, seamless backgrounds (black or white). Photography is either vivid and color-accurate if showcasing the product in use, or black-and-white with a hint of color for dramatic effect or to isolate a feature. Illustrations are minimal and highly abstracted, when present. Icons are typically outlined or filled in monochrome (`White Surface` or `Graphite`), serving functional navigation or explanatory roles with a consistent, thin stroke weight. The overall density is image-heavy, with visuals often dominating sections, punctuated by concise headlines and supporting text.

## Layout

The page primarily uses a full-bleed structure for hero sections and prominent imagery, transitioning to a max-width contained layout for detailed content, effectively centered without a fixed maximum width for larger screens. The hero pattern is typically a full-viewport product image or video with an overlaid centered headline and call-to-action. Section rhythm alternates between dark (`Midnight Canvas`, `Deep Charcoal`) and light (`Off-White Accent`) bands, creating clear visual breaks. Content is arranged in alternating text-left/image-right or image-left/text-right two-column layouts, as well as vertically stacked, centered blocks. Card grids, typically 2 or 3 columns, are used for features. The navigation is a sticky top bar with minimal links and a discrete 'bag' icon, focusing attention on the current page content. The layout is spacious, allowing product imagery and typography to breathe.

## Agent Prompt Guide

### Quick Color Reference
text: #ffffff
background: #000000
border: #cccccc
accent: #f56900
primary action: #0071e3 (filled action)

### 3-5 Example Component Prompts
1. Create a full-bleed hero section: `Midnight Canvas` (#000000) background. Headline at `80px` `SF Pro Display` weight 700, `White Surface` (#ffffff), letter-spacing `0.96px`. A primary button with `Branded Blue` (#0071e3) background, `White Surface` (#ffffff) text, `980px` radius, `8px 15px` padding, using `SF Pro Text` weight 600.
2. Design a feature card for a dark section: `Graphite` (#1d1d1f) background, `28px` radius. Headline at `24px` `SF Pro Display` weight 600, `White Surface` (#ffffff), letter-spacing `0.1mm`. Body text at `17px` `SF Pro Text` weight 400, `Light Ghost` (#cccccc), line-height `1.18`. A `Ghost Text Button` for 'Más información' with `Graphite` (#1d1d1f) text and transparent background.
3. Build a navigation bar: `Midnight Canvas` (#000000) background. Links at `17px` `SF Pro Text` weight 400, `Light Ghost` (#cccccc). Use `elementGap` of `10px` between links. The 'Comprar' button should use `Branded Blue` (#0071e3) background, `White Surface` (#ffffff) text, `980px` radius, `8px 15px` padding.

## Similar Brands

- **Samsung** — Shares a similar focus on product photography, clean typography, and a dark/light alternating theme for sections.
- **Google (Pixel devices)** — Employs high-contrast photography and minimalist UI, allowing product and content to stand out.
- **Bose** — Utilizes product-centric layouts, often with black or white backgrounds and simple, clear typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #000000;
  --gradient-midnight-canvas: linear-gradient(rgb(0, 0, 0), rgb(17, 17, 17));
  --color-deep-charcoal: #111111;
  --color-graphite: #1d1d1f;
  --color-ghost-gray: #333336;
  --color-slate-text: #424245;
  --color-silver-text: #86868b;
  --color-light-ghost: #cccccc;
  --color-white-surface: #ffffff;
  --color-off-white-accent: #f5f5f7;
  --color-branded-blue: #0071e3;
  --color-sky-link-blue: #0066cc;
  --color-action-blue: #2997ff;
  --color-vibrant-orange: #f56900;
  --color-plum-accent: #8668ff;
  --color-teal-contrast: #00a1b3;

  /* Typography — Font Families */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.47;
  --tracking-caption: -0.37px;
  --text-body: 14px;
  --leading-body: 1.24;
  --tracking-body: -0.27px;
  --text-body-lg: 17px;
  --leading-body-lg: 1.18;
  --tracking-body-lg: -0.27px;
  --text-subheading: 19px;
  --leading-subheading: 1.21;
  --tracking-subheading: -0.28px;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --tracking-heading: 0.1px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.13px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: 0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 89px;
  --card-padding: 28px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;

  /* Named Radii */
  --radius-cards: 28px;
  --radius-links: 10px;
  --radius-buttons: 980px;
  --radius-elements: 28px;

  /* Surfaces */
  --surface-midnight-canvas: #000000;
  --surface-deep-charcoal: #111111;
  --surface-graphite: #1d1d1f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-deep-charcoal: #111111;
  --color-graphite: #1d1d1f;
  --color-ghost-gray: #333336;
  --color-slate-text: #424245;
  --color-silver-text: #86868b;
  --color-light-ghost: #cccccc;
  --color-white-surface: #ffffff;
  --color-off-white-accent: #f5f5f7;
  --color-branded-blue: #0071e3;
  --color-sky-link-blue: #0066cc;
  --color-action-blue: #2997ff;
  --color-vibrant-orange: #f56900;
  --color-plum-accent: #8668ff;
  --color-teal-contrast: #00a1b3;

  /* Typography */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.47;
  --tracking-caption: -0.37px;
  --text-body: 14px;
  --leading-body: 1.24;
  --tracking-body: -0.27px;
  --text-body-lg: 17px;
  --leading-body-lg: 1.18;
  --tracking-body-lg: -0.27px;
  --text-subheading: 19px;
  --leading-subheading: 1.21;
  --tracking-subheading: -0.28px;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --tracking-heading: 0.1px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.13px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: 0.96px;

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
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;
}
```
