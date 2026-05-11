# Waabi — Style Reference
> monochromatic impact with magenta precision

**Theme:** light

Waabi operates on a robust, authoritative visual language, characterized by stark contrasts between light and dark surfaces and bold, compact typography. A single vibrant magenta provides functional accents, drawing attention to calls-to-action and active states against the predominantly monochromatic palette. Components are designed for clarity and impact, with generous rounded corners hinting at a friendly usability layer beneath the serious brand posture. The overall impression is one of confident, high-tech efficiency.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#191818` | `--color-midnight-graphite` | Primary text, deep surface backgrounds, strong borders — establishing a high-contrast foundation |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, most content areas — serving as the clean default canvas |
| Cloud Gray | `#e8e6e3` | `--color-cloud-gray` | Secondary card backgrounds, subtle section dividers, muted background fills — adding a soft, layered depth |
| Silver Pine | `#808080` | `--color-silver-pine` | Secondary text, subtle borders, inactive states — providing lower contrast detail without disappearing |
| Soft Fog | `#8c8b8b` | `--color-soft-fog` | Helper text, ghost button borders, subtle lines — for less prominent informational elements |
| Steel Light | `#cccccc` | `--color-steel-light` | Divider lines, subtle card borders — for thin graphical separation |
| Muted Stone | `#d1d5dc` | `--color-muted-stone` | Card backgrounds, subtle graphic elements — offering an alternative light neutral surface |
| Accent Magenta | `#ff2c6b` | `--color-accent-magenta` | Primary action buttons, active indicators, decorative highlights — the sole vibrant accent for interactivity and emphasis |

## Tokens — Typography

### Zagma — Headlines, expressive titles, and large display text — characterized by its expansive tracking and compact line height, making it feel vast yet impactful. · `--font-zagma`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 10px, 16px, 20px, 24px, 40px, 60px, 80px, 130px, 150px
- **Line height:** 0.85, 0.90, 1.10, 1.20, 1.25, 1.40, 1.50
- **Letter spacing:** -0.0480em, -0.0400em, -0.0300em, -0.0300em, -0.0200em
- **Role:** Headlines, expressive titles, and large display text — characterized by its expansive tracking and compact line height, making it feel vast yet impactful.

### NeueHaas — Body text, captions, and functional UI labels — providing a readable, slightly narrow contrast to the display font. Its subtle positive letter-spacing ensures legibility at smaller sizes. · `--font-neuehaas`
- **Substitute:** Open Sans
- **Weights:** 400, 500
- **Sizes:** 10px, 11px, 12px, 15px
- **Line height:** 1.40, 1.60
- **Letter spacing:** 0.0100em, 0.0200em
- **Role:** Body text, captions, and functional UI labels — providing a readable, slightly narrow contrast to the display font. Its subtle positive letter-spacing ensures legibility at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.4 | 0.15px | `--text-body-sm` |
| subheading | 20px | 1.4 | -0.6px | `--text-subheading` |
| heading | 40px | 1.25 | -1.2px | `--text-heading` |
| heading-lg | 80px | 1.2 | -2.4px | `--text-heading-lg` |
| display | 150px | 0.85 | -7.2px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 50px |
| containers-lg | 63.4059px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 96px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Main CTA for key actions

Solid filled button with Accent Magenta background (#ff2c6b), Canvas White text (#ffffff), and a generous 50px border-radius for a soft, pill-like appearance. Padding is 0px top/bottom and 24px left/right, relying on line-height for vertical alignment.

### Ghost Button - Light Text
**Role:** Secondary action on dark backgrounds

Transparent background with Canvas White text (#ffffff). Border color is a very subtle transparent white, `oklab(0.999994 0.0000455678 0.0000200868 / 0.15)`, and a 1.67772e+07px radius for maximum rounding. No explicit padding, text-based sizing.

### Ghost Button - Dark Text
**Role:** Secondary action on light backgrounds

Transparent background with Midnight Graphite text (#191818). Border color is a subtle transparent gray, `oklab(0.210168 0.00151306 0.000472009 / 0.15)`, and a 1.67772e+07px radius. No explicit padding, text-based sizing.

### Link Button
**Role:** Tertiary action for navigation or emphasis

Styled as a text link with transparent background, Midnight Graphite text (#191818). Padding is 0px top/bottom and 10px left/right, no border or radius.

### Neutral Card - Light
**Role:** Content container on light backgrounds

Cloud Gray background (#e8e6e3) with a 12px border-radius and no box-shadow, for a flat, matte surface. No intrinsic padding.

### Neutral Card - Dark
**Role:** Content container on dark backgrounds

Midnight Graphite background (#191818) with a 12px border-radius and no box-shadow, creating a strong contrast or section break. No intrinsic padding.

### Muted Card
**Role:** Subtle content container on light backgrounds

Muted Stone background (#d1d5dc) with a 12px border-radius and no box-shadow, for a slightly warmer, less stark surface than Cloud Gray. No intrinsic padding.

## Do's and Don'ts

### Do
- Always use a 12px border-radius for all content cards to maintain a consistent soft edge.
- Apply Accent Magenta (#ff2c6b) exclusively for primary calls-to-action or critical active states.
- Prioritize large, compact 'Zagma' typography for headlines, using its negative letter-spacing for visual density.
- Utilize Cloud Gray (#e8e6e3) and Canvas White (#ffffff) as the primary alternating background surfaces for section differentiation.
- Ensure interactive elements like buttons have a 50px border-radius, creating a distinct pill shape.
- Break up large content sections with a sectionGap of 96px for ample breathing room.
- Use NeueHaas for all body text and UI labels, ensuring letter-spacing of 0.01em or 0.02em for legibility.

### Don't
- Do not introduce new vibrant colors outside of Accent Magenta (#ff2c6b); maintain the strict monochromatic palette.
- Avoid excessive use of drop shadows; the design relies on bold color blocks and border-radius for visual separation.
- Refrain from using long line lengths for body text; keep text blocks concise to maintain readability with NeueHaas.
- Do not deviate from the established type scale; maintain the precise sizes and letter-spacing for Zagma and NeueHaas.
- Avoid small, subtle changes in neutral tones for background; use the defined Cloud Gray, Canvas White, Midnight Graphite, and Muted Stone for clear surface distinction.
- Do not use generic square corners; aim for the established soft radii on all containers and interactive elements.
- Never use text as the primary call-to-action unless it is a defined Link Button with appropriate padding and transparent background.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Cloud Gray | `#e8e6e3` | Secondary background, primary card surfaces |
| 2 | Muted Stone | `#d1d5dc` | Tertiary card backgrounds, softer content panels |
| 3 | Midnight Graphite | `#191818` | High-contrast sections, dark cards, prominent backgrounds |

## Imagery

Photography features tight product crops of trucks for self-driving technology or abstract, graphic representations of digital systems. Images are usually contained within cards or masked shapes, never full-bleed. Illustrations are minimal, predominantly flat, geometric, and often outlined, using the brand's monochromatic colors or Accent Magenta. Icons are outlined, simple, and monochrome, often appearing as subtle functional elements. Imagery serves to showcase technology and provide visual context in a clean, contained manner rather than decorative atmosphere, often presented against stark white or dark backgrounds.

## Layout

The page maintains a centered, max-width layout, typically around 1200px. The hero section often features a large, impactful Zagma headline against a clean background. Sections alternate between Canvas White and Cloud Gray or Midnight Graphite, creating clear visual segmentation with a consistent vertical rhythm of 96px section gaps. Content is arranged in alternating text-left/image-right or vertical stacks, often utilizing 2-column or 3-column card grids for features and insights. Navigation is a sticky top bar with a centralized logo and right-aligned links. The overall density is comfortable, with generous white space around elements.

## Agent Prompt Guide

Quick Color Reference: 
text: #191818
background: #ffffff
border: #191818 
accent: #ff2c6b
primary action: #ff2c6b (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff2c6b background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a content card: Cloud Gray background (#e8e6e3), 12px radius, no shadow. Inside, have a subheading at 40px Zagma weight 400, #191818, letter-spacing -1.2px. Below that, a paragraph of body text at 15px NeueHaas weight 400, #808080, line-height 1.4, letter-spacing 0.15px. Ensure card has 24px padding.
3. Create a navigation button for a dark background: Ghost Button - Light Text. Label it 'Home' with Canvas White text (#ffffff). Ensure it has a very subtle transparent white border.

## Similar Brands

- **Aurora** — Both use a high-tech, somewhat stark aesthetic with limited color palettes, focusing on product and technology imagery.
- **Waymo** — Share an emphasis on clear, functional UI with a preference for clean whites and grays, using a single accent color for interaction.
- **Plus.ai** — Exhibit similar brand confidence through bold typography and a minimal, high-contrast visual design, common in self-driving technology companies.
- **TuSimple** — Both feature a corporate yet modern feel, relying on strong visual segments and carefully chosen typography to convey authority without being overly decorative.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #191818;
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #e8e6e3;
  --color-silver-pine: #808080;
  --color-soft-fog: #8c8b8b;
  --color-steel-light: #cccccc;
  --color-muted-stone: #d1d5dc;
  --color-accent-magenta: #ff2c6b;

  /* Typography — Font Families */
  --font-zagma: 'Zagma', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehaas: 'NeueHaas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.6px;
  --text-heading: 40px;
  --leading-heading: 1.25;
  --tracking-heading: -1.2px;
  --text-heading-lg: 80px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -2.4px;
  --text-display: 150px;
  --leading-display: 0.85;
  --tracking-display: -7.2px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 96px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 40px;
  --radius-full: 50px;
  --radius-full-2: 63.4059px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 50px;
  --radius-containers-lg: 63.4059px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #e8e6e3;
  --surface-muted-stone: #d1d5dc;
  --surface-midnight-graphite: #191818;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #191818;
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #e8e6e3;
  --color-silver-pine: #808080;
  --color-soft-fog: #8c8b8b;
  --color-steel-light: #cccccc;
  --color-muted-stone: #d1d5dc;
  --color-accent-magenta: #ff2c6b;

  /* Typography */
  --font-zagma: 'Zagma', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neuehaas: 'NeueHaas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.6px;
  --text-heading: 40px;
  --leading-heading: 1.25;
  --tracking-heading: -1.2px;
  --text-heading-lg: 80px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -2.4px;
  --text-display: 150px;
  --leading-display: 0.85;
  --tracking-display: -7.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 40px;
  --radius-full: 50px;
  --radius-full-2: 63.4059px;
}
```
