# Halfhelix — Style Reference
> High-contrast monochrome, violet punctuation

**Theme:** light

Halfhelix employs a contemporary, slightly austere visual language characterized by high-contrast monochrome UI accented by a singular vivid violet. Text is used as a primary structural element, with generous leadings creating rhythm. Components are lightweight with minimal adornment, favoring subtle outlines and dark overlays for hierarchy in a compact layout. The system balances a dark, high-contrast hero with a predominantly light content theme, creating a dynamic progression from attention-grabbing to informative.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, darkest backgrounds (hero, footer), borders, button text, icon fills |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, primary card surfaces, light button backgrounds, hover states, accent borders |
| Lead | `#484a4c` | `--color-lead` | Input backgrounds, subtle borders, secondary text in dark contexts |
| Fog | `#ededed` | `--color-fog` | Light surface backgrounds, neutral badge backgrounds, button backgrounds for secondary actions |
| Stone | `#808080` | `--color-stone` | Secondary button backgrounds, muted background elements |
| Platinum | `#dbdbdb` | `--color-platinum` | Fine borders, subtle dividers, tertiary text in light contexts |
| Charcoal | `#262626` | `--color-charcoal` | Darker input backgrounds, alternate dark card backgrounds |
| Steel | `#686c6d` | `--color-steel` | Body text, icon outlines, secondary text |
| Silver | `#a5a7a8` | `--color-silver` | Subtle button borders, tertiary visual accents |
| Violet Impulse | `#2749ff` | `--color-violet-impulse` | Brand accent, highlighting key elements, decorative backgrounds in a very limited, functional capacity |

## Tokens — Typography

### Suisse Intl — The sole typeface, Suisse Intl, at weight 400 defines all typographic hierarchy. The tight letter-spacing for larger sizes creates a sophisticated, compact feel, avoiding a shouting effect despite large display sizes. Line height of 1.0 reduces visual bulk for display text, with 1.1 and 1.2 used for body text at smaller sizes, maintaining readability while keeping it dense. · `--font-suisse-intl`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 24px, 32px, 40px, 48px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.0400em at 48px, -0.0200em at 32px, -0.0100em at 24px and below
- **Role:** The sole typeface, Suisse Intl, at weight 400 defines all typographic hierarchy. The tight letter-spacing for larger sizes creates a sophisticated, compact feel, avoiding a shouting effect despite large display sizes. Line height of 1.0 reduces visual bulk for display text, with 1.1 and 1.2 used for body text at smaller sizes, maintaining readability while keeping it dense.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | -0.12px | `--text-caption` |
| body | 14px | 1.1 | -0.14px | `--text-body` |
| heading-sm | 18px | 1.2 | -0.18px | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.24px | `--text-heading` |
| heading-lg | 32px | 1.1 | -0.64px | `--text-heading-lg` |
| display | 48px | 1 | -1.92px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 3px |
| circular | 1440px |

### Layout

- **Section gap:** 60px
- **Card padding:** 15px
- **Element gap:** 5px

## Components

### Primary Dark Button
**Role:** Call-to-action button for dark contexts.

Background: rgba(0, 0, 0, 0.5), Text: #ffffff, Border: 1px solid #ffffff, Border-radius: 3px, Padding: 10px 15px.

### Ghost Dark Button
**Role:** Secondary action button for dark contexts.

Background: transparent, Text: #ffffff, Border: 1px solid #ffffff, Border-radius: 3px, Padding: 10px.

### Neutral Light Button
**Role:** Default action button for light contexts.

Background: #ffffff, Text: #000000, Border: 1px solid #000000, Border-radius: 3px, Padding: 10px.

### Neutral Disabled Button
**Role:** Disabled or less prominent action button for light contexts.

Background: #ededed, Text: #000000, Border: 1px solid #000000, Border-radius: 3px, Padding: 10px 15px.

### Image Card
**Role:** Displaying project images or content teasers.

Background: transparent, Border-radius: 0px, no shadow, no padding.

### Information Card
**Role:** Cards containing functional information or contextual content.

Background: #ededed, Border-radius: 3px, no shadow, no padding.

### Overlay Card
**Role:** Elevated cards for interactive elements, like cookie consents.

Background: rgba(0, 0, 0, 0.5), Border-radius: 3px, no shadow, Padding: 15px 10px.

### Search Input
**Role:** Text input areas with a subtle dark background.

Background: rgba(0.15, 0.15, 0.15, 1) or #484a4c, Text: #ffffff. Border: none. Border-radius: 3px.

### Light Badge
**Role:** Categorization or status indicator on light backgrounds.

Background: #ededed, Text: #000000, Border-radius: 3px, Padding: 2px 5px.

### Dark Badge
**Role:** Categorization or status indicator on dark backgrounds.

Background: rgba(0.15, 0.15, 0.15, 1), Text: #ffffff, Border-radius: 3px, Padding: 2px 5px.

## Do's and Don'ts

### Do
- Use Suisse Intl (or Inter as substitute) weight 400 for all text, manipulating size and letter-spacing for hierarchy, not weight.
- Apply #000000 (Ink) as primary text color against light backgrounds, and #ffffff (Canvas) against dark backgrounds.
- Utilize 'Violet Impulse' (#2749ff) strictly for branding accents, functional highlights, or decorative background fills, never for primary text.
- Maintain a default border-radius of 3px for all interactive elements like buttons, badges, and inputs, and for informational cards.
- Employ #ededed (Fog) for secondary background surfaces or passive component states in light themes.
- Structure interactive elements like buttons with explicit background colors or borders, avoiding ambiguous ghost states with no visual definition.
- Favor white (`#ffffff`) as the dominant page canvas, with distinct darker sections for hero and footer areas to create contrast.

### Don't
- Avoid using multiple font weights or families; adhere exclusively to Suisse Intl (Inter) weight 400.
- Do not introduce new vibrant colors into the palette; stick to the defined achromatic scale and the single violet accent.
- Refrain from heavy drop shadows or elaborate gradients; surfaces should remain flat or use subtle 3px radius.
- Do not use #2749ff (Violet Impulse) for large blocks of text or as a background for primary functional elements outside of specific brand contexts.
- Avoid creating elevation through stacked box shadows; the design relies on clear background/border differences and minimal radius.
- Do not treat every section of the page as full-bleed; content areas should be contained within clear vertical rhythm.
- Do not embed information within images without providing equivalent accessible text, as imagery is highly decorative and often cropped.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Base page background |
| 1 | Fog | `#ededed` | Secondary backgrounds, informational cards |
| 2 | Stone | `#808080` | Tertiary backgrounds, muted interactive elements |
| 3 | Ink Overlay | `#000000` | Hero background, footer background, overlay panels, interactive overlays |

## Imagery

The imagery consists predominantly of tightly cropped, high-quality product photography or selective detail shots that blur into the background. The treatment is often raw-edged, occasionally masked into a full-bleed presentation, but primarily contained within grid-like structures. There's an absence of lifestyle photography, focusing instead on the texture, material, and form of objects. Icons are minimalist, outlined, and monochromatic, taking on the surrounding text color. Images serve a decorative and evocative role, hinting at the brands they represent rather than explicitly showcasing product features, with a high density, often dominating entire sections.

## Layout

The page primarily employs a max-width contained layout, typically with content centered, though specific sections can lean full-bleed for visual impact. The hero section is full-bleed and dark, featuring a large, centered headline against illustrative or ambient video backgrounds. Sectional rhythm alternates between these full-bleed visual statements and tighter, text-dominant sections on white canvas. Content arrangement frequently uses a multi-column grid for showcasing projects, with implicit visual dividers through background shifts. Overall density is balanced, with generous vertical spacing between major sections but compact text blocks. Navigation includes a sticky header with a minimal logo and primary links, along with an overlay search.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #dbdbdb
accent: #2749ff
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Section: Full-bleed black background (#000000). Headline in Suisse Intl 48px, line-height 1.0, letter-spacing -1.92px, color #ffffff. Subtext in Suisse Intl 16px, line-height 1.2, letter-spacing -0.16px, color #ededed. Place a Ghost Dark Button: background transparent, text #ffffff, border 1px solid #ffffff, radius 3px, padding 10px.
2. Design an Information Card: Background #ededed, radius 3px, no shadow, padding 15px. Title in Suisse Intl 24px, line-height 1.2, letter-spacing -0.24px, color #000000. Body text in Suisse Intl 14px, line-height 1.1, letter-spacing -0.14px, color #686c6d.
3. Create a Navigation Item: Text in Suisse Intl 14px, line-height 1.1, letter-spacing -0.14px, color #000000. Underline on hover: 1px solid #000000. Padding 5px.

## Similar Brands

- **Stripe** — Monochromatic base with a single, vivid brand accent and clean, minimalist typography.
- **Huge Inc.** — Agency website with large, impactful typography as a primary design element and a strong use of black and white imagery.
- **Shopify Partners** — Focus on clean layouts, compact UI elements, and a professional, tech-oriented aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-lead: #484a4c;
  --color-fog: #ededed;
  --color-stone: #808080;
  --color-platinum: #dbdbdb;
  --color-charcoal: #262626;
  --color-steel: #686c6d;
  --color-silver: #a5a7a8;
  --color-violet-impulse: #2749ff;

  /* Typography — Font Families */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.12px;
  --text-body: 14px;
  --leading-body: 1.1;
  --tracking-body: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.64px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.92px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 15px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-default: 3px;
  --radius-circular: 1440px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-fog: #ededed;
  --surface-stone: #808080;
  --surface-ink-overlay: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-lead: #484a4c;
  --color-fog: #ededed;
  --color-stone: #808080;
  --color-platinum: #dbdbdb;
  --color-charcoal: #262626;
  --color-steel: #686c6d;
  --color-silver: #a5a7a8;
  --color-violet-impulse: #2749ff;

  /* Typography */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.12px;
  --text-body: 14px;
  --leading-body: 1.1;
  --tracking-body: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.64px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.92px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-full: 1440px;
}
```
