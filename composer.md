# Composer — Style Reference
> Algorithmic Canvas

**Theme:** light

Composer employs a vibrant, 'algorithmic canvas' aesthetic: a stark light background overlaid with an expressive, often overlapping, grid of saturated color blocks. Typography is bold and confident, prioritizing readability with high contrast. Components are minimal and functional, with a strong emphasis on contrasting rounded elements (buttons) against the sharp, rectilinear geometry of decorative color blocks. The system balances a sense of playful, dynamic visual interest with a clear, direct presentation of complex financial information.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f7f7f7` | `--color-canvas-white` | Page backgrounds, default surfaces, light card backgrounds |
| Ash Gray | `#e5e7eb` | `--color-ash-gray` | Subtle borders, dividers, subtle background distinction for sections |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, prominent headings, solid button fills |
| Graphite | `#101516` | `--color-graphite` | Darker backgrounds, specific text accents for contrast |
| Steel Gray | `#bec6cc` | `--color-steel-gray` | Secondary borders, subtle inactive elements |
| Composer Blue | `#1871da` | `--color-composer-blue` | Primary Call to Action buttons, interactive highlights, navigational accents — signifies active states and key actions; Shadow effect for interactive elements, adding dimensionality with brand tint |
| Emerald Green | `#31805a` | `--color-emerald-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. |
| Bubblegum Pink | `#ffb4ed` | `--color-bubblegum-pink` | Background for transparent text overlays, decorative blocks, highlighting specific words |
| Vivid Green | `#1ec072` | `--color-vivid-green` | Decorative blocks and illustrations, visually distinct from Emerald Green |
| Hot Pink | `linear-gradient(90deg, rgb(246, 96, 159) 20px, rgba(0, 0, 0, 0) 1%)` | `--color-hot-pink` | Overlapping decorative blocks, specific button highlights, more intense than Bubblegum Pink; Transparent linear gradient for overlaying color blocks |
| Cadet Blue | `#1f86ff` | `--color-cadet-blue` | Decorative block fills, distinct from Composer Blue in saturation |
| Sunny Yellow | `#ffbb38` | `--color-sunny-yellow` | Decorative block fills, provides a warm contrast to the cooler blues and greens |
| Sunset Orange | `#ff5500` | `--color-sunset-orange` | Distinct secondary button fills |
| Action Red | `#c60808` | `--color-action-red` | Red action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Neue Haas Grotesk Display — Brand headlines, prominent callouts, and interface elements requiring high impact and distinct brand voice. The larger sizes feature tight negative letter-spacing for a bold, condensed feel, while smaller sizes are more open for readability. · `--font-neue-haas-grotesk-display`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 20px, 24px, 32px, 36px, 56px, 64px, 244px
- **Line height:** 1.00, 1.07, 1.11, 1.20, 1.25, 1.30, 1.33, 1.40, 1.43, 1.50
- **Letter spacing:** -0.96px at 56px, -1.22px at 64px, -4.88px at 244px, 0.22px at 24px, 0.224px at 14px
- **Role:** Brand headlines, prominent callouts, and interface elements requiring high impact and distinct brand voice. The larger sizes feature tight negative letter-spacing for a bold, condensed feel, while smaller sizes are more open for readability.

### Inter — Body text, navigation items, descriptive labels, and all informational content. Its balanced proportions and range of weights provide excellent legibility for supportive content. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 9px, 10px, 12px, 14px, 16px
- **Line height:** 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** 0.4px at 16px
- **OpenType features:** `'calt'`
- **Role:** Body text, navigation items, descriptive labels, and all informational content. Its balanced proportions and range of weights provide excellent legibility for supportive content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.43 | 0.224px | `--text-body-sm` |
| body | 16px | 1.43 | 0.4px | `--text-body` |
| subheading | 24px | 1.33 | 0.24px | `--text-subheading` |
| heading | 36px | 1.25 | 0.225px | `--text-heading` |
| heading-lg | 56px | 1.11 | -0.96px | `--text-heading-lg` |
| display | 244px | 1 | -4.88px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| small | 2px |
| button | 9999px |
| default | 6px |
| circular | 100px |
| cardAccentCorner | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(24, 113, 218, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |
| xl | `rgba(0, 0, 0, 0.01) 45px 68px 33px 0px, rgba(0, 0, 0, 0.0...` | `--shadow-xl` |
| xl-2 | `rgba(31, 33, 35, 0.03) 54px 82px 39px 0px, rgba(31, 33, 3...` | `--shadow-xl-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Main call to action for key conversions.

Solid Composer Blue fill (#1871da) with crisp white text (#ffffff), 9999px pill-shaped radius, 16px vertical and 32px horizontal padding. Uses Neue Haas Grotesk Display weight 500.

### Ghost Nav Link
**Role:** Navigation items and secondary inline actions.

Transparent background with Midnight Ink text (#000000), no border, no padding. Uses Inter weight 500 at 16px.

### Contained White Card
**Role:** Standard content containers with subtle elevation.

Canvas White background (#ffffff), 6px border-radius, subtle multi-layer shadow (rgba(0, 0, 0, 0.01) 45px 68px 33px 0px, rgba(0, 0, 0, 0.02) 25px 38px 27px 0px, rgba(0, 0, 0, 0.03) 11px 17px 20px 0px, rgba(0, 0, 0, 0.04) 3px 4px 11px 0px), 16px padding.

### Dark Overlay Card
**Role:** Content within dark sections or for visual contrast.

Graphite background (#262d2f), 6px border-radius, subtle dark shadow (rgba(31, 33, 35, 0.03) 54px 82px 39px 0px, rgba(31, 33, 35, 0.09) 31px 46px 33px 0px, rgba(31, 33, 35, 0.15) 14px 20px 24px 0px, rgba(31, 33, 35, 0.18) 3px 5px 13px 0px), no padding.

### Header 'Sign Up' Button
**Role:** Distinguished action button in the header.

Solid Midnight Ink fill (#000000) with Canvas White text (#ffffff), 9999px pill-shaped radius, 16px 24px padding.

### Block Pattern Button (Colored)
**Role:** Accent buttons embedded within colorful layouts or for specific feature highlights.

Solid background in accent colors (e.g., Emerald Green #31805a, Hot Pink #f6609f, Sunset Orange #ff5500) with Midnight Ink text (#000000), 0px radius (sharp corners), 16px vertical and 12px horizontal padding. Uses Neue Haas Grotesk Display weight 400.

## Do's and Don'ts

### Do
- Prioritize Neue Haas Grotesk Display for all headings and high-impact text, using negative letter-spacing for sizes 24px and above to create a condensed, bold appearance.
- Use a default 6px border-radius for cards and content containers, creating soft, approachable corners.
- Apply 9999px (pill-shaped) border-radius specifically to interactive buttons and tags to distinguish them as actionable elements.
- Utilize the vibrant accent colors (#31805a, #ffb4ed, #1ec072, #f6609f, #ffbb38, #1f86ff) primarily as large, overlapping or scattered geometric blocks for visual interest, contrasting with the overall neutral canvas.
- Ensure high contrast between text and background, typically using Midnight Ink (#000000) on Canvas White (#ffffff) or Graphite (#101516) for legibility.
- Implement consistent internal padding of 16px for cards and primary content blocks to maintain a sense of spaciousness.
- For interactive accent shadows, use rgba(24, 113, 218, 0.25) 0px 1px 2px 0px to provide subtle depth and tie into the brand blue.

### Don't
- Avoid using the accent colors for extensive blocks of body text; they are for illustrative and highlighted elements.
- Do not introduce new border radii beyond 2px, 6px, 12px, 100px, or 9999px for UI elements.
- Do not use subtle elevation shadows on small, interactive components like buttons; they should remain flat or use the accent blue shadow.
- Avoid generic serif fonts; stick to the sans-serif system of Neue Haas Grotesk Display and Inter for all typography.
- Refrain from using monochromatic background blocks as the primary visual element; complement or overlay them with the geometric accent color blocks.
- Do not use dark backgrounds for entire sections where the dominant theme is light, unless explicitly defined as a distinct, contained dark module (e.g., the dark Overlay Card).
- Avoid dense, wall-to-wall textual layouts; break up content with generous spacing and visual elements like charts or code blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#f7f7f7` | Primary page background, expansive and neutral base. |
| 1 | Light Card Surface | `#ffffff` | Elevated cards and contained content blocks, slightly brighter than the canvas. |
| 2 | Dark Card Surface | `#262d2f` | Cards or containers within dark-themed sections, providing strong contrast. |
| 3 | Accent Card Surface | `#31805a` | Cards or blocks with a saturated brand accent background. |

## Elevation

- **Contained White Card:** `rgba(0, 0, 0, 0.01) 45px 68px 33px 0px, rgba(0, 0, 0, 0.02) 25px 38px 27px 0px, rgba(0, 0, 0, 0.03) 11px 17px 20px 0px, rgba(0, 0, 0, 0.04) 3px 4px 11px 0px`
- **Dark Overlay Card:** `rgba(31, 33, 35, 0.03) 54px 82px 39px 0px, rgba(31, 33, 35, 0.09) 31px 46px 33px 0px, rgba(31, 33, 35, 0.15) 14px 20px 24px 0px, rgba(31, 33, 35, 0.18) 3px 5px 13px 0px`
- **Interactive Element Shadow:** `rgba(24, 113, 218, 0.25) 0px 1px 2px 0px`

## Imagery

The site uses a combination of abstract, geometric color blocks for decorative atmosphere and a minimal, focused approach for product imagery. Photography is sparse, when present, it features tightly cropped product screenshots or abstract compositions. Icons are typically mono-color, outlined, or subtly filled, maintaining a lightweight feel. Imagery and graphics serve to break up text, provide visual cues, and reinforce the 'algorithmic' and 'building' metaphors with modular shapes, rather than showing extensive lifestyle or human-centric content. The density is moderate to high, with visuals occupying significant space but in a structured, non-overwhelming manner. The primary visual story is told through bold typography and the interplay of colored shapes.

## Agent Prompt Guide

**Quick Color Reference**
- text: #000000
- background: #f7f7f7
- border: #e5e7eb
- accent: #1871da
- primary action: #ff5500 (filled action)

**3-5 Example Component Prompts**
- Create a Primary Action Button: #ff5500 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a text section: Canvas White background (#f7f7f7). Heading 'AI-powered strategy creation' at 56px Neue Haas Grotesk Display, Midnight Ink (#000000), letter-spacing -0.96px. Body text 'Explain your goals...' at 16px Inter, Midnight Ink (#000000). Section padding: 32px.
- Create a contained feature card: Light Card Surface background (#ffffff), 6px border-radius, subtle multi-layer shadow. Card padding 16px. Heading 'Discover pre-built strategies' at 24px Neue Haas Grotesk Display, Midnight Ink (#000000). Body text below at 14px Inter, Midnight Ink (#000000).
- Create a pill-shaped header button: Midnight Ink background (#000000), Canvas White text (#ffffff), 9999px radius, 16px vertical and 24px horizontal padding. Text 'Sign Up' using Inter weight 500.

## Similar Brands

- **Rive.app** — Shares a similar aesthetic of a light canvas punctuated by vibrant, often moving, geometric shapes and confident, large typography.
- **Linear.app** — Employs a strict grid, generous spacing, and a focused approach to typography, balanced with subtle background textures or graphical elements, though Linear is more muted.
- **Framer** — Features bold, often interactive, typography as a central design element, combined with a clear layout and a disciplined use of color accents on a generally neutral background.
- **Vercel** — Known for a clean, developer-focused aesthetic that combines functional UI with subtle animated backgrounds and strong typographic hierarchy, much like Composer's structured yet dynamic feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f7f7f7;
  --color-ash-gray: #e5e7eb;
  --color-midnight-ink: #000000;
  --color-graphite: #101516;
  --color-steel-gray: #bec6cc;
  --color-composer-blue: #1871da;
  --color-emerald-green: #31805a;
  --color-bubblegum-pink: #ffb4ed;
  --color-vivid-green: #1ec072;
  --color-hot-pink: #f6609f;
  --gradient-hot-pink: linear-gradient(90deg, rgb(246, 96, 159) 20px, rgba(0, 0, 0, 0) 1%);
  --color-cadet-blue: #1f86ff;
  --color-sunny-yellow: #ffbb38;
  --color-sunset-orange: #ff5500;
  --color-action-red: #c60808;

  /* Typography — Font Families */
  --font-neue-haas-grotesk-display: 'Neue Haas Grotesk Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.224px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.4px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.24px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: 0.225px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.96px;
  --text-display: 244px;
  --leading-display: 1;
  --tracking-display: -4.88px;

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
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-small: 2px;
  --radius-button: 9999px;
  --radius-default: 6px;
  --radius-circular: 100px;
  --radius-cardaccentcorner: 12px;

  /* Shadows */
  --shadow-subtle: rgba(24, 113, 218, 0.25) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.01) 45px 68px 33px 0px, rgba(0, 0, 0, 0.02) 25px 38px 27px 0px, rgba(0, 0, 0, 0.03) 11px 17px 20px 0px, rgba(0, 0, 0, 0.04) 3px 4px 11px 0px;
  --shadow-xl-2: rgba(31, 33, 35, 0.03) 54px 82px 39px 0px, rgba(31, 33, 35, 0.09) 31px 46px 33px 0px, rgba(31, 33, 35, 0.15) 14px 20px 24px 0px, rgba(31, 33, 35, 0.18) 3px 5px 13px 0px;

  /* Surfaces */
  --surface-canvas-white: #f7f7f7;
  --surface-light-card-surface: #ffffff;
  --surface-dark-card-surface: #262d2f;
  --surface-accent-card-surface: #31805a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f7f7f7;
  --color-ash-gray: #e5e7eb;
  --color-midnight-ink: #000000;
  --color-graphite: #101516;
  --color-steel-gray: #bec6cc;
  --color-composer-blue: #1871da;
  --color-emerald-green: #31805a;
  --color-bubblegum-pink: #ffb4ed;
  --color-vivid-green: #1ec072;
  --color-hot-pink: #f6609f;
  --color-cadet-blue: #1f86ff;
  --color-sunny-yellow: #ffbb38;
  --color-sunset-orange: #ff5500;
  --color-action-red: #c60808;

  /* Typography */
  --font-neue-haas-grotesk-display: 'Neue Haas Grotesk Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.224px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.4px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.24px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: 0.225px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.96px;
  --text-display: 244px;
  --leading-display: 1;
  --tracking-display: -4.88px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(24, 113, 218, 0.25) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.01) 45px 68px 33px 0px, rgba(0, 0, 0, 0.02) 25px 38px 27px 0px, rgba(0, 0, 0, 0.03) 11px 17px 20px 0px, rgba(0, 0, 0, 0.04) 3px 4px 11px 0px;
  --shadow-xl-2: rgba(31, 33, 35, 0.03) 54px 82px 39px 0px, rgba(31, 33, 35, 0.09) 31px 46px 33px 0px, rgba(31, 33, 35, 0.15) 14px 20px 24px 0px, rgba(31, 33, 35, 0.18) 3px 5px 13px 0px;
}
```
