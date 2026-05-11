# Cassette — Style Reference
> Granular sonic texture

**Theme:** dark

Cassette employs a retro-futuristic, bold aesthetic centered on high-contrast black and yellow. Textures are a key visual element, with a CRT-like grain applied to background surfaces. Typography is compact and functional, balancing a monospaced font for details with a humanist sans-serif for impact. Components are lightweight with distinctive extreme corner rounding, contrasting with the sharp, graphic angles of the overall layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Oil | `#19181a` | `--color-midnight-oil` | Primary surface background, text on brand yellow accents. Black with a subtle warmth for depth |
| Cassette Yellow | `#f0e226` | `--color-cassette-yellow` | Brand accent, active states, button fills, primary text on dark backgrounds. A vivid, almost neon yellow that defines the brand's energetic feel |
| Ghostly Gray | `#d9d7ce` | `--color-ghostly-gray` | Subtle text, secondary border outlines, muted links. A desaturated light gray |
| True Black | `#000000` | `--color-true-black` | Primary text on light backgrounds, strong borders, graphic elements. Pure black for maximum contrast |
| Paper White | `#f5f4f0` | `--color-paper-white` | Component backgrounds, badge fills, text on dark backgrounds. An off-white resembling aged paper |
| Subtle Line | `#272727` | `--color-subtle-line` | Hairline separators, subtle borders on dark surfaces |
| Pop Pink | `#fac4f0` | `--color-pop-pink` | Decorative block background, illustration accent. A vibrant, moderate pink |
| Tangelo Dream | `#ff8461` | `--color-tangelo-dream` | Decorative block background, illustration accent. A vivid orange |
| Sky Blue | `#2896f3` | `--color-sky-blue` | Decorative block background, illustration accent. A vivid blue |
| Evergreen | `#0db55b` | `--color-evergreen` | Decorative block background, illustration accent. A vivid green |

## Tokens — Typography

### Apercu Pro — Major headings and key marketing statements. The standard sans serif for primary expression. · `--font-apercu-pro`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 15px, 37px, 56px, 60px
- **Line height:** 1.08, 1.20
- **Role:** Major headings and key marketing statements. The standard sans serif for primary expression.

### Apercu Mono Pro — Body text, metadata, labels, and all detailed information. Its monospaced nature contributes to the structured, technical feel. · `--font-apercu-mono-pro`
- **Substitute:** Menlo, Monaco, 'Courier New', monospace
- **Weights:** 400
- **Sizes:** 13px, 14px
- **Line height:** 1.00, 1.16, 1.30
- **Role:** Body text, metadata, labels, and all detailed information. Its monospaced nature contributes to the structured, technical feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1.2 | — | `--text-caption` |
| body-sm | 37px | 1.2 | — | `--text-body-sm` |
| body | 56px | 1.2 | — | `--text-body` |
| body-lg | 60px | 1.2 | — | `--text-body-lg` |

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
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| other | 900px |
| buttons | 900px |

### Layout

- **Section gap:** 48px
- **Card padding:** 13px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call to action

Boldly rounded button with Cassette Yellow fill and Midnight Oil text. Padding is 10px vertically and 13px horizontally. Radius 900px.

### Ghost Button
**Role:** Secondary call to action, navigation items

Outline button with Cassette Yellow text and a 1px Cassette Yellow border on a transparent background. Padding is 10px vertically and 13px horizontally. Radius 900px.

### Info Badge
**Role:** Informational labels, status indicators

Paper White background with True Black text. Square 0px radius. Padding 4px vertically and 4.8px horizontally.

### Outline Badge
**Role:** Subtle categories or labels

Transparent background with Midnight Oil text. Square 0px radius. Often used as a heading for client lists. Top padding 24px, no horizontal padding.

## Do's and Don'ts

### Do
- Use Midnight Oil (#19181a) as the primary background for content areas.
- Apply a 900px border radius to all interactive elements like buttons and any card-like groupings.
- Utilize Cassette Yellow (#f0e226) for all primary calls to action, highlights, and functional icons.
- Set all body text and detailed information in Apercu Mono Pro at 13px or 14px, weight 400 for a consistent technical feel.
- Employ True Black (#000000) for primary text on light backgrounds and for high-contrast borders.
- Maintain an element gap of 8px for tight groupings and apply 13px for internal card padding.
- Use Paper White (#f5f4f0) for component backgrounds and badges that require a lighter surface.

### Don't
- Avoid generic rectangular shapes; always use the extreme 900px border radius for interactive and contained elements.
- Do not introduce additional sans-serif fonts beyond Apercu Pro or mono fonts beyond Apercu Mono Pro.
- Never use Cassette Yellow (#f0e226) for non-interactive text or mere decoration; reserve its impact for active states and brand accents.
- Avoid soft, ambiguous color palettes; maintain the stark contrast between Midnight Oil/True Black and Cassette Yellow.
- Do not use subtle shadows for elevation; rely on strong color blocking and outline borders instead.
- Do not deviate from the grain texture on backgrounds; it's a signature visual element.
- Avoid decorative elements that feel 'modern' or 'clean'; embrace purposeful retro-futuristic graphics and sharp angles.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Oil Canvas | `#19181a` | Primary page background, dark surfaces with a subtle texture. |
| 1 | Paper White Surface | `#f5f4f0` | Background for badges and lighter content blocks. |
| 2 | Cassette Yellow Accent | `#f0e226` | Interactive elements, primary button fills, and bold highlight areas. |

## Imagery

This site features a mix of abstract and product imagery with a distinct texture overlay. Photography includes tight crops of cassette tapes and hands, often against vibrant, contrasting backgrounds. Illustrations are geometric and outlined, sometimes with a distressed or grainy effect, using the brand's accent colors as fillers. Iconography is primarily outlined, featuring an asterisk-like brand mark with a medium stroke weight. Imagery serves both decorative atmosphere and explicit product showcase, with a medium density, balancing text-heavy sections with bold visual statements.

## Layout

The page primarily uses a full-bleed dark background with content centered vertically and horizontally. The hero section features a large, centered headline over the textured dark background, with navigation elements positioned at the top. Sections exhibit consistent vertical spacing, often breaking into alternating full-width blocks or multi-column layouts. A prominent grid is used for client logos (4-column). Text and image content often form L-shaped or Z-shaped arrangements rather than strict symmetrical columns, creating dynamic visual flow. Navigation is a simple top bar with distinct button-like links, sometimes accompanied by a dynamic, 'rotating' graphic.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000 (on light), #f5f4f0 (on dark)
- background: #19181a
- border: #000000 (strong), #f0e226 (accent)
- accent: #f0e226
- primary action: #f0e226 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #f0e226 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a ghost button labeled 'LEARN MORE' on the dark background.
- Create an info badge that reads 'NEW'.
- Create a section divider: 1px solid Subtle Line (#272727) spanning the content width.

## Similar Brands

- **Offf Festival** — Shares a gritty, high-contrast aesthetic with bold typography and a limited, punchy color palette.
- **Future Publishing** — Utilizes a similar retro-graphic style with textured backgrounds and strong color blocking.
- **Adult Swim** — Employs striking black backgrounds, neon accents, and a distinct, consistent typographic voice.
- **Superdeluxe** — Known for its use of unconventional layouts, bold color splashes, and a distinctive, often playful, visual identity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-oil: #19181a;
  --color-cassette-yellow: #f0e226;
  --color-ghostly-gray: #d9d7ce;
  --color-true-black: #000000;
  --color-paper-white: #f5f4f0;
  --color-subtle-line: #272727;
  --color-pop-pink: #fac4f0;
  --color-tangelo-dream: #ff8461;
  --color-sky-blue: #2896f3;
  --color-evergreen: #0db55b;

  /* Typography — Font Families */
  --font-apercu-pro: 'Apercu Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono-pro: 'Apercu Mono Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-body-sm: 37px;
  --leading-body-sm: 1.2;
  --text-body: 56px;
  --leading-body: 1.2;
  --text-body-lg: 60px;
  --leading-body-lg: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;

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
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 13px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-full: 900px;

  /* Named Radii */
  --radius-other: 900px;
  --radius-buttons: 900px;

  /* Surfaces */
  --surface-midnight-oil-canvas: #19181a;
  --surface-paper-white-surface: #f5f4f0;
  --surface-cassette-yellow-accent: #f0e226;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-oil: #19181a;
  --color-cassette-yellow: #f0e226;
  --color-ghostly-gray: #d9d7ce;
  --color-true-black: #000000;
  --color-paper-white: #f5f4f0;
  --color-subtle-line: #272727;
  --color-pop-pink: #fac4f0;
  --color-tangelo-dream: #ff8461;
  --color-sky-blue: #2896f3;
  --color-evergreen: #0db55b;

  /* Typography */
  --font-apercu-pro: 'Apercu Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono-pro: 'Apercu Mono Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-body-sm: 37px;
  --leading-body-sm: 1.2;
  --text-body: 56px;
  --leading-body: 1.2;
  --text-body-lg: 60px;
  --leading-body-lg: 1.2;

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
  --spacing-128: 128px;

  /* Border Radius */
  --radius-full: 900px;
}
```
