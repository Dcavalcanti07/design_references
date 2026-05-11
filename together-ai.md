# Together AI — Style Reference
> Shifting geometric planes under a deep indigo sky. Bold textual headlines punctuate against a canvas of near-black and clinical white, punctuated by soft, almost pastel blocks of color.

**Theme:** mixed

This system evokes a sense of advanced analytical capability, balancing deep, technical backgrounds with moments of soft-hued clarity. The predominant use of near-black and white creates a high-contrast, data-centric atmosphere. Subtle, pastel-like card colorations provide distinct 'data blocks' against the stark background. Hard-edged rectilinear forms dominate, with soft corner radii only appearing on interactive elements, grounding the digital sophistication with approachable interaction points. Large, whispering headlines in a custom AI-inspired typeface set a tone of quiet authority.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#010120` | `--color-midnight-ink` | Page background (dark sections), primary button background, navigation background — establishes the core dark ambiance, suggesting depth and technical sophistication. |
| Canvas White | `#FFFFFF` | `--color-canvas-white` | Page background (light sections), text on dark, interactive element text, primary surface for content — provides expansive contrast and visual breathing room. |
| Void Black | `#000000` | `--color-void-black` | Primary text color on light backgrounds, button text, icon default — provides maximum contrast against Canvas White and light pastels. |
| Smoke Gray | `#4D4D4D` | `--color-smoke-gray` | Secondary body text, subtle borders — softens informational text without losing legibility against light backgrounds. |
| Frost Gray | `#D6D6D6` | `--color-frost-gray` | Subtle borders, dividers, disabled states — offers a minimal visual separation. |
| Sky Blue Block | `#C1DFF9` | `--color-sky-blue-block` | Informational card background, content blocks — provides a light, approachable surface for data points. |
| Cosmic Pink Block | `#FDE3F6` | `--color-cosmic-pink-block` | Informational card background, content blocks — adds a contrasting, soft chromatic element. |
| Dawn Orange Block | `#FFDCCD` | `--color-dawn-orange-block` | Informational card background, content blocks — warms up data presentation without being visually aggressive. |
| Cyan Whisper | `#C8F6F9` | `--color-cyan-whisper` | Callout backgrounds, subtle accent fills — a very light, almost ethereal touch of color. |
| Regal Violet | `#BDBBFF` | `--color-regal-violet` | Accent elements, interactive indicators, underlines — a sophisticated, slightly desaturated violet for emphasis. |
| Electric Orange | `#FC4C02` | `--color-electric-orange` | Small interactive iconography, decorative fills — a vibrant, high-chroma accent appearing sparingly. |
| Magenta Flash | `#EF2CC1` | `--color-magenta-flash` | Small interactive iconography, decorative fills — a sharp, vivid pink for specific energetic accents. |
| Cyan Glow | `#70E9F0` | `--color-cyan-glow` | Backgrounds for specific programmatic blocks — a cool, technical cyan. |

## Tokens — Typography

### The Future — Primary typeface for all headings, body text, navigation, and general UI. The custom, almost futuristic aesthetic in varying weights maintains a consistent modern and intelligent tone without being overtly decorative. The tight letter-spacing at larger sizes gives headlines a crisp, intentional feel, preventing them from feeling loose despite the generous line heights. · `--font-the-future`
- **Substitute:** Montserrat, Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 22px, 28px, 40px, 64px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.25, 1.30, 1.40
- **Letter spacing:** -0.0300em at 64px, -0.0200em at 40px, -0.0150em at 28px, -0.0100em at 22px
- **Role:** Primary typeface for all headings, body text, navigation, and general UI. The custom, almost futuristic aesthetic in varying weights maintains a consistent modern and intelligent tone without being overtly decorative. The tight letter-spacing at larger sizes gives headlines a crisp, intentional feel, preventing them from feeling loose despite the generous line heights.

### PP Neue Montreal Mono — Used for code snippets, secondary labels, and small annotations. Its monospace nature provides a technical, data-driven counterpoint to 'The Future', reinforcing the AI platform's underlying complexity and precision. · `--font-pp-neue-montreal-mono`
- **Substitute:** IBM Plex Mono, Space Mono
- **Weights:** 400, 500
- **Sizes:** 10px, 11px, 13px, 16px
- **Line height:** 1.00, 1.40
- **Letter spacing:** 0.0070em at 16px, 0.0050em at 13px
- **Role:** Used for code snippets, secondary labels, and small annotations. Its monospace nature provides a technical, data-driven counterpoint to 'The Future', reinforcing the AI platform's underlying complexity and precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.007px | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 22px | 1.3 | -0.44px | `--text-subheading` |
| heading | 28px | 1.25 | -0.42px | `--text-heading` |
| heading-lg | 40px | 1.15 | -0.8px | `--text-heading-lg` |
| display | 64px | 1.1 | -1.92px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 16px |
| medium | 8px |
| default | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(1, 1, 32, 0.1) -10px 0px 75px 0px` | `--shadow-xl` |

### Layout

## Components

### Primary Dark Button
**Role:** Call to Action

backgroundColor: #000000, color: #FFFFFF, borderRadius: 4px, padding: 16px. Used for main actions against light backgrounds.

### Secondary Ghost Button
**Role:** Secondary Action

backgroundColor: rgba(255, 255, 255, 0.12), color: #FFFFFF, borderRadius: 4px, padding: 16px. Provides a subtle action against dark backgrounds without competing with primary CTAs.

### Light Ghost Button
**Role:** Secondary Action on Light Background

backgroundColor: rgba(0, 0, 0, 0.08), color: #000000, borderRadius: 4px, padding: 16px. A subdued action on light backgrounds.

### Badge (Dark Background)
**Role:** Categorization, Status

backgroundColor: rgba(255, 255, 255, 0.12), color: #FFFFFF, borderRadius: 4px, padding: 2px 8px. Applied to elements on dark surfaces.

### Badge (Light Background)
**Role:** Categorization, Status

backgroundColor: rgba(0, 0, 0, 0.04), color: #000000, borderRadius: 4px, padding: 2px 8px. Applied to elements on light surfaces.

### Light Information Card
**Role:** Content Display, Feature Highlight

backgroundColor: rgba(255, 255, 255, 0.08), borderRadius: 4px, padding: 20px 40px. Used for content blocks on dark backgrounds.

### Colored Information Card (Blue)
**Role:** Statistical Highlight

backgroundColor: #C1DFF9, borderRadius: 0px, padding: 20px. Used for specific data points or feature blocks, like the 2x faster card.

### Colored Information Card (Pink)
**Role:** Statistical Highlight

backgroundColor: #FDE3F6, borderRadius: 0px, padding: 20px. Used for specific data points or feature blocks.

### Colored Information Card (Orange)
**Role:** Statistical Highlight

backgroundColor: #FFDCCD, borderRadius: 0px, padding: 20px. Used for specific data points or feature blocks.

### Navigation Bar
**Role:** Global Navigation

backgroundColor: rgba(255, 255, 255, 0.08) within a primary background of #010120, backdrop-filter: blur(10px), boxShadow: rgba(1, 1, 32, 0.1) -10px 0px 75px 0px. Features a subtle frosted glass effect on a dark background.

## Do's and Don'ts

### Do
- Use 'The Future' font for all primary textual content to maintain a consistent high-tech, yet approachable, brand voice.
- Apply a 4px `borderRadius` to all buttons and badges for subtle modern rounding.
- Prioritize `Midnight Ink` (#010120) and `Canvas White` (#FFFFFF) for primary background and text combinations, achieving high contrast.
- Utilize `Regal Violet` (#BDBBFF) as the primary accent color for active navigation states and subtle interactive highlights.
- Frame informational cards with `20px 40px` padding when on dark backgrounds, using `rgba(255, 255, 255, 0.08)` as background.
- Employ `PP Neue Montreal Mono` for all technical annotations, code blocks, or data-specific text to differentiate programmatic content.
- Ensure large headlines (64px) apply `-0.0300em` letter-spacing for visual tightness.

### Don't
- Do not introduce new border radii beyond 4px, 8px, or 16px; prefer the consistent 4px default for interactive elements.
- Avoid using highly saturated, vivid colors for large background blocks; reserve them only for small, pointed iconography or specific branding elements.
- Do not use generic system fonts; 'The Future' and 'PP Neue Montreal Mono' are integral to the brand's unique character.
- Do not deviate from the established padding scale; consistent spacing reinforces information hierarchy.
- Avoid applying shadows directly to most content cards; depth is achieved primarily through background shifts and subtle layering of semi-transparent surfaces.
- Do not place body copy in colors other than `Void Black` or `Canvas White` on their respective contrasting backgrounds, or `Smoke Gray` for secondary text.
- Avoid overly playful or organic shapes; the aesthetic is sharp, precise, and tech-focused.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space BG | `#010120` | Primary dark page background, foundational layer for deep sections. |
| 1 | Subtle Dark Card | `#ffffff14` | Lightly elevated cards or content blocks on dark backgrounds, providing minimal visual separation. |
| 2 | Frosted Nav | `#ffffff14` | Navigation bar background, featuring a backdrop blur to create a 'frosted glass' effect over content below. |

## Elevation

- **Navigation Bar:** `rgba(1, 1, 32, 0.1) -10px 0px 75px 0px`

## Imagery

The visual language is split between abstract 3D renders and subtle iconography, with an absence of traditional photography. Large, abstract 3D graphics in the hero section feature overlapping, translucent geometric forms with soft gradients and blurred edges, suggesting complexity and interconnectedness. These are rendered to appear ethereal yet structured, against a dark backdrop. Elsewhere, icons are simple, often monochromatic, and directly support the accompanying text, serving an explanatory role. The overall density of imagery is moderate, strategically placed to illustrate concepts or provide visual breaks without dominating the content.

## Layout

The site employs a mixed layout model, primarily adopting a full-bleed dark hero section with a centered, split text and abstract visual. Subsequent sections alternate between full-width dark backgrounds and standard content-width, centered light sections. Vertical spacing between sections is generous, leading to a spacious, comfortable density. Content arrangement often utilizes a centered stack for headlines and subtext, followed by feature blocks in a 3-column grid, or alternating text-left/visual-right patterns. The navigation is a sticky top bar, often subtly transparent/frosted over the dark hero, then opaque on light backgrounds.

## Agent Prompt Guide

### Quick Color Reference
- Text (dark bg): #FFFFFF
- Text (light bg): #000000
- Background (dark): #010120
- Background (light): #FFFFFF
- CTA Button BG (dark): #000000
- CTA Button BG (ghost): rgba(255, 255, 255, 0.12)
- Accent: #BDBBFF

### Example Component Prompts
1. Create a Hero Headline: 'Build what's next on the AI Native Cloud'. Use 'The Future' font, weight 500, size 64px, line-height 1.1, letter-spacing -1.92px, color #FFFFFF. Place it on a #010120 background.
2. Design a Primary Dark Action Button: 'Start building'. Use 'The Future' font, weight 400, size 16px, line-height 1.4, color #FFFFFF. Background #000000, borderRadius 4px, padding 16px.
3. Construct a Light Information Card: '2x Faster Inference'. Use 'The Future' font for body, weight 400, size 16px, line-height 1.4, color #000000. Background #C1DFF9, no border, borderRadius 0px, padding 20px.
4. Produce a Badge for Dark Background: 'Developers'. Use 'The Future' font, weight 400, size 14px, line-height 1.4, color #FFFFFF. Background rgba(255, 255, 255, 0.12), borderRadius 4px, padding 2px 8px.
5. Generate a Footer Link: 'About Us'. Use 'The Future' font, weight 400, size 14px, line-height 1.4, color #FFFFFF. No explicit background, standard hover will be a mild opacity shift, such as on rgba(255,255,255,0.08).

## Similar Brands

- **Linear** — Shares a deep dark mode aesthetic with crisp typography and subtle interactive elements, favoring dark backgrounds over light.
- **Anthropic** — Similar approach to high-contrast text on dark backgrounds, using minimal color accents to highlight key information or interactive states.
- **Vercel** — Employs technical, precise typography, a clean layout, and restrained use of color within a primarily dark UI.
- **Supabase** — Combines prominent technical headlines with structured content blocks and a developer-centric interface, often with dark modes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #010120;
  --color-canvas-white: #FFFFFF;
  --color-void-black: #000000;
  --color-smoke-gray: #4D4D4D;
  --color-frost-gray: #D6D6D6;
  --color-sky-blue-block: #C1DFF9;
  --color-cosmic-pink-block: #FDE3F6;
  --color-dawn-orange-block: #FFDCCD;
  --color-cyan-whisper: #C8F6F9;
  --color-regal-violet: #BDBBFF;
  --color-electric-orange: #FC4C02;
  --color-magenta-flash: #EF2CC1;
  --color-cyan-glow: #70E9F0;

  /* Typography — Font Families */
  --font-the-future: 'The Future', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono: 'PP Neue Montreal Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.44px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.42px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.8px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -1.92px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-large: 16px;
  --radius-medium: 8px;
  --radius-default: 4px;

  /* Shadows */
  --shadow-xl: rgba(1, 1, 32, 0.1) -10px 0px 75px 0px;

  /* Surfaces */
  --surface-deep-space-bg: #010120;
  --surface-subtle-dark-card: #ffffff14;
  --surface-frosted-nav: #ffffff14;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #010120;
  --color-canvas-white: #FFFFFF;
  --color-void-black: #000000;
  --color-smoke-gray: #4D4D4D;
  --color-frost-gray: #D6D6D6;
  --color-sky-blue-block: #C1DFF9;
  --color-cosmic-pink-block: #FDE3F6;
  --color-dawn-orange-block: #FFDCCD;
  --color-cyan-whisper: #C8F6F9;
  --color-regal-violet: #BDBBFF;
  --color-electric-orange: #FC4C02;
  --color-magenta-flash: #EF2CC1;
  --color-cyan-glow: #70E9F0;

  /* Typography */
  --font-the-future: 'The Future', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono: 'PP Neue Montreal Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.007px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.44px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.42px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.8px;
  --text-display: 64px;
  --leading-display: 1.1;
  --tracking-display: -1.92px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-xl: rgba(1, 1, 32, 0.1) -10px 0px 75px 0px;
}
```
