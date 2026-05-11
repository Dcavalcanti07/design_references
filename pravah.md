# Pravah — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Pravah employs a sophisticated, near-monochromatic aesthetic that evokes the clarity of an engineering blueprint. Type-heavy layouts with precise letter tracking and ample whitespace are punctuated by subtle surface differentiations. The system leverages stark contrasts between near-black text and off-white backgrounds, with interactive elements relying on contained shapes and subtle borders rather than bold color fills.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#181011` | `--color-carbon` | Primary text, heading text, strong borders, icons, link text |
| Porcelain | `#f3f1ed` | `--color-porcelain` | General page background, primary canvas for most content |
| Snow | `#ffffff` | `--color-snow` | Card backgrounds, elevated surfaces, specific badge backgrounds, ghost button text (on dark sections) |
| Charcoal | `#222222` | `--color-charcoal` | Secondary heading text, slightly softer than Carbon for less emphasis |
| Stone | `#aaaaaa` | `--color-stone` | Muted text, helper text, subtle outlines for ghost elements |
| Fog | `#d8d4d4` | `--color-fog` | Hairline borders, decorative SVG fills |
| Deep Plum | `#302023` | `--color-deep-plum` | Hero section background (dark theme variant background), decorative gradients, background fills for illustrative elements |

## Tokens — Typography

### ABCfavorit Book — Primary typeface for all text content. Weight 400 is used for body text, descriptive elements. The tight letter-spacing at larger sizes, like 48px, creates a condensed, impactful presence. Wide letter-spacing at 0.1em is reserved for uppercase badges. · `--font-abcfavorit-book`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 15px, 17px, 20px, 28px, 32px, 40px, 48px
- **Line height:** 1.10, 1.30, 1.40, 1.50
- **Letter spacing:** -0.0200em, 0.1000em
- **OpenType features:** `"ss04" on, "ss11" on`
- **Role:** Primary typeface for all text content. Weight 400 is used for body text, descriptive elements. The tight letter-spacing at larger sizes, like 48px, creates a condensed, impactful presence. Wide letter-spacing at 0.1em is reserved for uppercase badges.

### ABCfavorit Book — Used for emphasized text, navigation items, and subheadings, where a stronger visual hierarchy is needed. Paired with a tight letter-spacing for headlines to maximize impact and reduce visual noise. · `--font-abcfavorit-book`
- **Weights:** 700
- **Sizes:** 12px, 14px, 15px, 17px, 20px, 28px, 32px, 40px, 48px
- **Line height:** 1.10, 1.30, 1.40, 1.50
- **Letter spacing:** -0.0200em, 0.1000em
- **OpenType features:** `"ss04", "ss11"`
- **Role:** Used for emphasized text, navigation items, and subheadings, where a stronger visual hierarchy is needed. Paired with a tight letter-spacing for headlines to maximize impact and reduce visual noise.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 1.2px | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| subheading | 20px | 1.3 | — | `--text-subheading` |
| heading-sm | 28px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.64px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.8px | `--text-heading-lg` |
| display | 48px | 1.1 | -0.96px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| buttons | 100px |
| default | 4px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Call to action, subtle interaction

Transparent background, Carbon text color (#181011), 1px Carbon border, 100px border radius (pill shape). Padding of 8px vertical and 20px horizontal. Used for primary calls to action on light backgrounds.

### Filled Button
**Role:** Call to action, emphasized interaction

Snow background (#ffffff), Carbon text color (#181011), 100px border radius (pill shape). Padding of 8px vertical and 20px horizontal. Used for primary calls to action on dark backgrounds for clear visibility.

### Subtle Link Button
**Role:** Secondary action, navigation.

Transparent background, Carbon text color (#181011), 4px border-radius, subtle background color of rgba(24, 16, 17, 0.05) on hover/active. Padding of 4px vertical and 16px horizontal.

### Feature Card
**Role:** Content grouping (default/light).

Transparent background, 8px border-radius. No explicit shadow. Padding of 0px top/bottom, 48px left/right. Used for feature blocks within a section with a clear background distinction.

### Dark Overlay Card
**Role:** Content grouping (dark/elevated).

Semi-transparent dark background (rgba(255, 255, 255, 0.1)), 8px border-radius. Padding of 12px vertical and 20px horizontal. Used for cards on dark backgrounds or to create a translucent overlay effect.

### Subtle Content Card
**Role:** Contained information block.

Light gray background (rgba(24, 16, 17, 0.05)), 4px border-radius. Padding of 20px all around. Used for less prominent content blocks or to subtly differentiate information.

### Pill Badge
**Role:** Status indicator, small label.

Snow background (#ffffff), Carbon text color (#181011), 4px border-radius. Padding of 1.92px vertical and 8px horizontal. Used for visual tags and status indicators like 'Critical', 'Problem'.

### Ghost Badge
**Role:** Contextual label.

Transparent background, Snow text color (#ffffff), 4px border-radius. Padding of 1.92px vertical and 8px horizontal. Used for labels on dark backgrounds with minimal footprint.

## Do's and Don'ts

### Do
- Use Carbon (#181011) for all primary body text and most headings.
- Apply Porcelain (#f3f1ed) as the default background for most page sections.
- Prioritize ABCfavorit Book with tight letter-spacing for all headlines (e.g., -0.0200em at 48px) to achieve a modern, condensed feel.
- Use 100px border-radius for all primary buttons to create a consistent pill shape.
- Maintain a clear visual hierarchy with ample whitespace, using 64px for vertical section separation.
- When a button needs to be filled, use Snow (#ffffff) background with Carbon text (#181011) for maximum contrast on dark backgrounds.
- Utilize rgba(255, 255, 255, 0.1) for translucent cards or overlays on darker sections to create depth without full opacity.

### Don't
- Avoid excessive color; color should primarily be functional, not decorative.
- Do not use generic system fonts; always utilize ABCfavorit Book or its substitute.
- Refrain from using bold shadows or gradients for elevation; surfaces should primarily rely on background color changes or subtle blurs.
- Do not break the established type scale; maintain consistent sizes and line heights across headings and body text.
- Avoid highly saturated colors for interface elements unless it's for a semantic status indicator.
- Do not use square buttons; all interactive buttons should have a 'pill' radius (100px).
- Avoid dense layouts; embrace comfortable spacing with a minimum of 8px between elements and 24px inner padding for cards.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#f3f1ed` | Primary page background, expansive white space |
| 1 | Card Light | `#1810110d` | Subtle content containers, slight differentiation from canvas |
| 2 | Card Elevated | `#ffffff` | Prominent information blocks, button backgrounds on dark fields |
| 3 | Overlay Translucent | `#ffffff1a` | Translucent cards or overlays, particularly on dark backgrounds. |

## Imagery

This site uses a mix of abstract, technical line-art illustrations and data visualizations. Illustrations are often geometric, outlined, and monochromatic, featuring visual metaphors for connectivity, power grids, and data flow. They are typically contained within sections rather than full-bleed, and serve an explanatory role. Product screenshots or photography are absent. Icons are minimalist, outlined, and follow the monochromatic theme, often in Carbon (#181011) or Fog (#d8d4d4). Imagery is used to visualize technical concepts rather than as decorative atmosphere, maintaining a text-dominant but visually supported feel.

## Layout

The page primarily uses a max-width contained layout with content centered, typically around 1200px. The hero section features a full-bleed dark background (Deep Plum) with a prominent centered headline and a call to action. Subsequent sections alternate between the Porcelain (#f3f1ed) background and occasional subtly tinted light gray sections, maintaining consistent vertical spacing at 64px. Content is frequently arranged in two-column layouts, often with text on one side and an illustrative graphic or data visualization on the other. Navigation is a simple top bar with text links, centered with the logo. The overall density is spacious rather than compact, emphasizing clarity and readability.

## Agent Prompt Guide

Quick Color Reference:
text: #181011
background: #f3f1ed
border: #181011
accent: #302023
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Deep Plum background (#302023). Headline 'The grid is at its limits.' in ABCfavorit Book weight 400, 48px, Snow color (#ffffff), letter-spacing -0.96px. Below it, a Ghost Button with text 'Get In Touch', Snow text (#ffffff), 1px Snow border (#ffffff), 100px radius, 8px vertical padding, 20px horizontal padding.
Create a feature card: Porcelain background (#f3f1ed). Inside, a Subtle Content Card with background rgba(24, 16, 17, 0.05), border-radius 4px, 20px padding. Title 'Forecasting is getting harder' in Carbon (#181011) ABCfavorit Book weight 700, 20px. Body text 'Extreme weather, EVs, and rooftop solar are making demand and generation harder to predict.' in Carbon (#181011) ABCfavorit Book weight 400, 15px.
Create a navigation bar: Porcelain background (#f3f1ed). Links 'Problem', 'Technology', 'Team' in Carbon (#181011) ABCfavorit Book weight 700, 14px, 4px vertical padding, 16px horizontal padding. The 'Get In Touch' link should be a Ghost Button with Carbon text (#181011), 1px Carbon border (#181011), 100px radius, 8px vertical padding, 20px horizontal padding.
Create a status badge: Pill Badge component with Snow background (#ffffff), Carbon text (#181011), 4px border-radius, 1.92px vertical padding, 8px horizontal padding. Text 'Critical' in ABCfavorit Book weight 700, 12px, letter-spacing 0.1em.

## Similar Brands

- **OpenAI** — Similar emphasis on sophisticated typography, clean, high-contrast layouts, and a restrained monochromatic color palette with minimal accent color use.
- **Linear** — Shares a preference for sharp, technical aesthetics, compact typography with precise letter-spacing in headings, and a focus on functional UI over decorative elements.
- **Vercel** — Employs a similar design language of dark/light theme splits on alternating sections, modern sans-serif typography, and subtle component styling with rounded corners.
- **Stripe** — Mirroring a focus on clean, spacious layouts, strong typographic hierarchy, and limited, carefully chosen color accents against a predominantly neutral palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #181011;
  --color-porcelain: #f3f1ed;
  --color-snow: #ffffff;
  --color-charcoal: #222222;
  --color-stone: #aaaaaa;
  --color-fog: #d8d4d4;
  --color-deep-plum: #302023;

  /* Typography — Font Families */
  --font-abcfavorit-book: 'ABCfavorit Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 1.2px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.8px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-buttons: 100px;
  --radius-default: 4px;

  /* Surfaces */
  --surface-canvas: #f3f1ed;
  --surface-card-light: #1810110d;
  --surface-card-elevated: #ffffff;
  --surface-overlay-translucent: #ffffff1a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #181011;
  --color-porcelain: #f3f1ed;
  --color-snow: #ffffff;
  --color-charcoal: #222222;
  --color-stone: #aaaaaa;
  --color-fog: #d8d4d4;
  --color-deep-plum: #302023;

  /* Typography */
  --font-abcfavorit-book: 'ABCfavorit Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 1.2px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.8px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 100px;
}
```
