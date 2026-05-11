# Audyr — Style Reference
> Structural Grid on White Canvas

**Theme:** light

Audyr employs a stark, almost monochromatic design language, built on a foundation of generous whitespace and structural borders. Type is compact and authoritative, primarily Inter, maintaining good readability despite a tight letter-spacing. Interaction is clearly signaled through subtle elevation changes and solid fills, making the experience feel direct and efficient.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#262626` | `--color-ink` | Primary text, heading text, strong accents, filled button backgrounds. Its deep, almost black tone creates strong contrast against light surfaces |
| Canvas White | `#ffffff` | `--color-canvas-white` | Base page background, card surfaces, and text on dark elements |
| Fog | `#ededed` | `--color-fog` | Subtle surface accents, hairline borders, and secondary backgrounds, providing visual separation without strong contrast |
| Muted Gray | `#686868` | `--color-muted-gray` | Secondary body text, helper text, and subtle control labels |
| Cool Gray | `#515151` | `--color-cool-gray` | Iconography and slightly darker secondary text for visual hierarchy |
| Dark Surface | `#171717` | `--color-dark-surface` | Background for elevated elements or focused content areas, providing a dark contrast to the predominantly light theme |
| Subtle Gray | `#929292` | `--color-subtle-gray` | Placeholder text and disabled element text, offering minimal visibility |
| Border Silver | `#737373` | `--color-border-silver` | Decorative strokes and fine borders, lighter than Ink but darker than Fog |
| Line White | `#cbcbcb` | `--color-line-white` | Subtle border and shadow accents, almost white but providing a whisper of definition |
| Accent Slate | `#101828` | `--color-accent-slate` | Navigation links and occasional thematic accents, a very dark, slightly tinted gray |

## Tokens — Typography

### Inter — Primary typeface for all text elements. Its clean, functional design supports the brand's direct communication, using multiple weights to establish subtle visual hierarchy within a generally compact layout. The consistent, slightly negative letter-spacing contributes to a refined, professional feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 24px, 30px, 36px, 48px
- **Line height:** 1.00, 1.11, 1.15, 1.25, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** -0.0250em
- **Role:** Primary typeface for all text elements. Its clean, functional design supports the brand's direct communication, using multiple weights to establish subtle visual hierarchy within a generally compact layout. The consistent, slightly negative letter-spacing contributes to a refined, professional feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.3px | `--text-caption` |
| body | 14px | 1.38 | -0.35px | `--text-body` |
| heading-sm | 20px | 1.25 | -0.5px | `--text-heading-sm` |
| heading | 24px | 1.15 | -0.6px | `--text-heading` |
| heading-lg | 30px | 1.11 | -0.75px | `--text-heading-lg` |
| display | 48px | 1 | -1.2px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 18px |
| images | 8px |
| buttons | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.04) 0px 1px 3px 0px` | `--shadow-subtle` |
| subtle-2 | `lab(0 0 0 / 0.05) 0px 1px 2px 0px` | `--shadow-subtle-2` |
| subtle-3 | `oklab(0.999994 0.0000455678 0.0000200868 / 0.16) 0px 1px ...` | `--shadow-subtle-3` |
| subtle-4 | `lab(0 0 0 / 0.05) 0px 1px 3px 0px, lab(0 0 0 / 0.05) 0px ...` | `--shadow-subtle-4` |
| xl | `lab(0 0 0 / 0.1) 0px 25px 50px -12px` | `--shadow-xl` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Section gap:** 145px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call-to-action button for critical actions.

Background: Ink (#262626), Text: Canvas White (#ffffff). Padding: 16px vertical, 0px horizontal (internal text padding often inferred). Border Radius: 10px or 4px depending on context. Text uses Inter font, varying weights and sizes based on context.

### Ghost Button
**Role:** Secondary action button, visually subtle.

Background: transparent (rgba(0,0,0,0)), Text: Ink (#262626). Border: implicit 1px solid Fog (#ededed) for visual separation when not hovered. Padding: 16px vertical, 0px horizontal. Border Radius: 8px. Text uses Inter font.

### Pill Ghost Button
**Role:** Tertiary navigation or filter button with a distinct shape.

Background: transparent (rgba(0,0,0,0)), Text: Ink (#262626). Border: none. Padding: 8px vertical, 16px horizontal. Border Radius: 1.67772e+07px (effectively full pill shape). Text uses Inter font.

### Navigation Link
**Role:** Top-level navigation items.

Text: Accent Slate (#101828) at 16px Inter, weight 400. Subtle underline on hover/active state.

### Hero Action Wrapper
**Role:** Container for primary action buttons in hero sections.

Background: Canvas White (#ffffff). Border: 1px solid Fog (#ededed) with a 6px radius. No padding, acting as a minimalist wrapper for internal elements.

### Light Card with Soft Shadow
**Role:** Content container for features or pricing tiers.

Background: Canvas White (#ffffff). Border Radius: 18px. Shadow: lab(0 0 0 / 0.1) 0px 25px 50px -12px. Padding: 32px on all sides.

### Clean Card
**Role:** Minimalist content container with no shadow.

Background: Fog (#ededed) or Canvas White (#ffffff). Border Radius: 18px. No shadow. Padding: 0px or 32px depending on content. Used for displaying logos or unadorned content blocks.

### Internal Active Tab
**Role:** Indicator for active selection within a segmented control or tab group.

Background: Ink (#262626). Text: Canvas White (#ffffff). Border Radius: 10px. Padding: 0px vertical, 11px horizontal for text fitting.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) or Fog (#ededed) for section backgrounds, creating a spacious and light-filled environment.
- Use Ink (#262626) for all primary text, headings, and crucial interactive elements to ensure strong contrast and clear communication.
- Apply Inter font with a slight negative letter-spacing (-0.0250em) across all text elements to maintain a compact, refined typographic aesthetic.
- Implement an 18px border radius for most cards and larger containers to impart a soft, approachable geometry.
- Utilize fine 1px borders in Fog (#ededed) or Border Silver (#737373) for structural division rather than heavy lines or strong background colors.
- Employ the lab(0 0 0 / 0.1) 0px 25px 50px -12px shadow for an impactful, single-layer elevation effect on key cards.
- Ensure generous vertical section gaps of 145px to create distinct content blocks and prevent visual clutter.

### Don't
- Avoid strong chromatic colors for primary UI elements; reserve them only for rare, contextual accents not found in this system.
- Do not use dark backgrounds for general page content; the design assumes a light canvas with darker elements as exceptions.
- Refrain from using heavy drop shadows or multiple shadow layers; elevation is subtle, often based on single, soft shadows.
- Avoid decorative imagery that competes with the clean UI; visual attention should be drawn to content and core functional elements.
- Do not deviate from Inter font; its specific weights and letter-spacing are integral to the brand's typographic identity.
- Avoid tight spacing around major sections; the design relies on generous whitespace for clarity and hierarchy.
- Do not use highly saturated colors for 'success' or 'error' indicators; rely on subtle color differentiation or iconography alongside the monochromatic palette.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ededed` | Dominant background for the page, providing a crisp, clean foundation. |
| 1 | Card White | `#ffffff` | Default background for cards and contained sections, slightly elevated above the canvas. |
| 2 | Dark Surface | `#171717` | Background for focused elements or content areas that require strong visual separation. |

## Elevation

- **Light Card with Soft Shadow:** `lab(0 0 0 / 0.1) 0px 25px 50px -12px`
- **Subtle Button Shadow:** `lab(0 0 0 / 0.05) 0px 1px 2px 0px`
- **Subtle Bordered Element Shadow:** `oklab(0.999994 0.0000455678 0.0000200868 / 0.16) 0px 1px 0px 0px inset, oklab(0.268999 -0.00000260025 0.00000627339 / 0.24) 0px 1px 2px 0px`
- **Subtle Card Shadow:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`

## Imagery

The visual system predominantly uses UI elements and strong typography over decorative imagery. When present, imagery (e.g., product screenshots showing dashboards or feature interfaces) is contained within cards or tight crops, maintaining a functional, explanatory role. There are no large hero images or abstract illustrations. Icons are minimal, typically outlined (though some filled instances exist), using neutral tones like Cool Gray or Ink, with a lighter stroke weight for subtlety. Imagery serves to inform and showcase the product's functionality, not to create atmosphere or tell a story.

## Layout

The page adheres to a maximum-width contained layout, though the exact max-width is not strictly defined, allowing content to breathe within a central column. The hero section is characterized by a centered headline and subtext with stacked, contrasting action buttons. Subsequent sections follow a consistent vertical rhythm with significant section gaps (145px). Content often alternates between centered single-column stacks and two-column layouts, sometimes featuring text on one side and a product screenshot or list on the other. Navigation consists of a transparent sticky header with text links and two distinct buttons, one ghosted and one filled, on the right. Pricing is presented in a multi-column card grid.

## Agent Prompt Guide

Quick Color Reference:
text: #262626
background: #ededed
border: #ededed
accent: #101828
primary action: #262626 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #262626 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a pricing card: background #ffffff, 18px radius, shadow lab(0 0 0 / 0.1) 0px 25px 50px -12px, 32px padding. Heading 'Hobby' at 20px Inter weight 600, #262626. Price '$16 / month' at 36px Inter weight 600, #262626. List items at 14px Inter weight 400, #262626, with a subtle gray icon (Cool Gray #515151).
3. Create an internal tab navigation item labeled 'Actions': Background #262626, text #ffffff, 10px radius, 0px vertical 11px horizontal padding. Font: Inter, weight 500, 14px, letter-spacing -0.35px.

## Similar Brands

- **Linear** — Monochromatic interface, strong typography, and subtle elevation for UI elements.
- **Stripe (Dashboard)** — Clean, functional design with a focus on data presentation, subtle borders, and controlled use of neutral colors.
- **Superhuman** — High-contrast text on light backgrounds, with compact, efficient UI components and minimal decorative elements.
- **Raycast** — Focus on textual interfaces, stark contrast, and a lack of extraneous visual flourishes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #262626;
  --color-canvas-white: #ffffff;
  --color-fog: #ededed;
  --color-muted-gray: #686868;
  --color-cool-gray: #515151;
  --color-dark-surface: #171717;
  --color-subtle-gray: #929292;
  --color-border-silver: #737373;
  --color-line-white: #cbcbcb;
  --color-accent-slate: #101828;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.3px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.35px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.5px;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 145px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-2xl: 18px;

  /* Named Radii */
  --radius-cards: 18px;
  --radius-images: 8px;
  --radius-buttons: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 1px 3px 0px;
  --shadow-subtle-2: lab(0 0 0 / 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: oklab(0.999994 0.0000455678 0.0000200868 / 0.16) 0px 1px 0px 0px inset, oklab(0.268999 -0.00000260025 0.00000627339 / 0.24) 0px 1px 2px 0px;
  --shadow-subtle-4: lab(0 0 0 / 0.05) 0px 1px 3px 0px, lab(0 0 0 / 0.05) 0px 1px 2px -1px;
  --shadow-xl: lab(0 0 0 / 0.1) 0px 25px 50px -12px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;

  /* Surfaces */
  --surface-canvas-white: #ededed;
  --surface-card-white: #ffffff;
  --surface-dark-surface: #171717;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #262626;
  --color-canvas-white: #ffffff;
  --color-fog: #ededed;
  --color-muted-gray: #686868;
  --color-cool-gray: #515151;
  --color-dark-surface: #171717;
  --color-subtle-gray: #929292;
  --color-border-silver: #737373;
  --color-line-white: #cbcbcb;
  --color-accent-slate: #101828;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.3px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: -0.35px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.5px;
  --text-heading: 24px;
  --leading-heading: 1.15;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.2px;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-2xl: 18px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.04) 0px 1px 3px 0px;
  --shadow-subtle-2: lab(0 0 0 / 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: oklab(0.999994 0.0000455678 0.0000200868 / 0.16) 0px 1px 0px 0px inset, oklab(0.268999 -0.00000260025 0.00000627339 / 0.24) 0px 1px 2px 0px;
  --shadow-subtle-4: lab(0 0 0 / 0.05) 0px 1px 3px 0px, lab(0 0 0 / 0.05) 0px 1px 2px -1px;
  --shadow-xl: lab(0 0 0 / 0.1) 0px 25px 50px -12px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```
