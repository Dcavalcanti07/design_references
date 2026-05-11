# Sublime — Style Reference
> Whiteboard of Ideas: bold strokes on a bright, uncluttered surface, punctuated by sharp, focused annotations.

**Theme:** light

Sublime uses a stark, high-contrast visual language with a dominant white canvas and confident, large typography. Its visual identity is built on oversized headings, minimal UI elements, and a subtle interplay of soft grays, creating a pristine, almost academic feel. The occasional hint of vivid green acts as a functional accent, drawing attention to calls-to-action and active states without overwhelming the restrained palette. Components are lightweight and often borderless, emphasizing content over chrome.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Dominant page background, primary card surfaces |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong borders |
| Charcoal Text | `#181816` | `--color-charcoal-text` | Heading text, icon fills |
| Fog Gray | `#efefef` | `--color-fog-gray` | Subtle background for UI elements, button fills, soft card borders |
| Zinc Gray | `#908f8e` | `--color-zinc-gray` | Muted text, button borders, secondary heading text for contrast |
| Ash Gray | `#a29e9c` | `--color-ash-gray` | Helper text, ghost button text, decorative borders |
| Sage Green | `#38744d` | `--color-sage-green` | Green outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Mint Accent | `#e0f5ff` | `--color-mint-accent` | Subtle background wash for related content sections |
| Lime Highlight | `#cbffa6` | `--color-lime-highlight` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Slate Text | `#6a6967` | `--color-slate-text` | Link text, sub-headings |

## Tokens — Typography

### Control Upright — Primary font for all UI text, headings, and body content. Its custom features give it a distinct, almost monospace-like character, lending an intellectual yet approachable feel. The extremely tight letter spacing at larger sizes (#-0.0200em at 142px, -0.0150em at 64px) creates an intentional, dense typographic block. · `--font-control-upright`
- **Substitute:** Arial Bold
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 28px, 64px, 142px
- **Line height:** 0.90, 1.00, 1.13, 1.16, 1.39
- **Letter spacing:** -0.0200em at 142px, -0.0150em at 64px, 0.0080em at 12px
- **OpenType features:** `"ss12" on, "ss09" on`
- **Role:** Primary font for all UI text, headings, and body content. Its custom features give it a distinct, almost monospace-like character, lending an intellectual yet approachable feel. The extremely tight letter spacing at larger sizes (#-0.0200em at 142px, -0.0150em at 64px) creates an intentional, dense typographic block.

### Times New Roman — Used for specific body content, possibly quotes or detailed explanatory text. The inclusion of a serif font provides a subtle textural contrast to the dominant sans-serif. · `--font-times-new-roman`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.20, 1.39
- **Letter spacing:** -0.0300em at 18px, -0.0200em at 14px
- **OpenType features:** `"ss12" on`
- **Role:** Used for specific body content, possibly quotes or detailed explanatory text. The inclusion of a serif font provides a subtle textural contrast to the dominant sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.39 | 0.008px | `--text-caption` |
| body | 14px | 1.39 | -0.02px | `--text-body` |
| label | 16px | 1.39 | — | `--text-label` |
| subheading | 18px | 1.39 | -0.03px | `--text-subheading` |
| heading-sm | 24px | 1.16 | — | `--text-heading-sm` |
| heading | 28px | 1.13 | — | `--text-heading` |
| heading-lg | 64px | 1 | -0.015px | `--text-heading-lg` |
| display | 142px | 0.9 | -0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 5px |
| footer | 40px |
| buttons | 5px |

### Layout

- **Section gap:** 200px
- **Card padding:** 18px
- **Element gap:** 15px

## Components

### Primary Action Button (Filled)
**Role:** Call-to-action button

Background: Lime Highlight (#cbffa6). Text: Sage Green (#38744d). Border: none. Radius: 5px. Padding: 0px vertical, 17.5px horizontal (derived from 0px height, 17.5px horizontal).

### Secondary Action Button (Ghost)
**Role:** Subtle button for secondary actions or navigation

Background: transparent. Text: Ash Gray (#a29e9c). Border: none. Radius: 0px. Padding: 0px. Used for login or navigation links.

### Neutral Button
**Role:** General utility button

Background: Fog Gray (#efefef). Text: Zinc Gray (#908f8e). Border: 1px solid Zinc Gray (#908f8e). Radius: 5px. Padding: 0px vertical, 17.5px horizontal (derived from 0px height, 17.5px horizontal).

### Text Link Button
**Role:** Interactive text link that behaves like a button

Background: transparent. Text: Midnight Ink (#000000). Border: none. Radius: 0px. Padding: 0px. Used for internal navigation or specific prompts.

### Small Pill Tag
**Role:** Informational tag for related content

Background: Mint Accent (#e0f5ff). Text: Midnight Ink (#000000). Border: 1px solid Midnight Ink (#000000). Radius: 999px. Padding: derived from line height of 16px, 13px horizontal.

### White Card
**Role:** Content container for various information types

Background: Canvas White (#ffffff). Border: 1.5px solid Zinc Gray (#908f8e). Radius: 5px. Padding: 18px on all sides.

## Do's and Don'ts

### Do
- Always use the Control Upright font with its specific font feature settings ('ss12' on, 'ss09' on) for all primary text and headings.
- Prioritize Canvas White (#ffffff) as the dominant page background, maintaining a spacious, bright environment.
- Apply a 5px border-radius consistently for all interactive elements like buttons and cards, creating a unified soft edge.
- Use Midnight Ink (#000000) or Charcoal Text (#181816) for primary text content to ensure high contrast against light backgrounds.
- Employ Lime Highlight (#cbffa6) exclusively for primary action buttons, ensuring visual distinction and clear calls-to-action.
- Maintain a clear element gap of 15px between horizontal components and a section gap of 200px for vertical rhythm.
- Utilize a 999px border-radius for all small, informational tags and pill-shaped elements for a distinct rounded aesthetic.

### Don't
- Do not introduce new saturated colors; limit the chromatic palette to Sage Green (#38744d), Mint Accent (#e0f5ff), and Lime Highlight (#cbffa6).
- Avoid heavy shadows or gradients; the design relies on flat surfaces and subtle border treatments.
- Do not use generic system fonts as substitutes for Control Upright without explicit font feature settings; this compromises the brand's unique typographic feel.
- Do not vary paragraph text sizes or line heights excessively; stick to the defined typographic scale for consistency.
- Do not apply large, ornate borders or decorative elements to components; keep the UI lean and content-focused.
- Avoid dense, complex layouts; favor generous white space and clean, balanced compositions with ample section gaps.
- Do not deviate from the defined border-radii; the specific values (5px, 999px, 40px) are critical to the visual identity.

## Imagery

Imagery is used sparingly, focusing on conceptual renders or highly stylized assets. The hero features a distinctive 3D moss-covered rock formation forming the brand name, lending an organic, whimsical, yet grounded feel. Other visuals include tight crops of product-related content and abstract illustrations within minimalist 'card' containers. Icons are monochromatic and simplistic, typically outlined or filled with Charcoal Text (#181816). The overall impression is illustrative and conceptual rather than photographic or product-heavy.

## Layout

The page primarily uses a full-bleed layout on a white canvas, with content often centered or arranged in multi-column grids within distinct sections. The hero section is full-bleed, featuring large centered text and a prominent visual motif. Subsequent sections maintain a generous vertical rhythm with a 200px section gap. Content structures often involve alternating text and image blocks, or 2-3 column card grids, all contained within the full-width white background, rather than a fixed-width container. Navigation is a minimalist top bar, with 'login' and 'try now' buttons right-aligned.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #ffffff
- border: #908f8e
- accent: #38744d
- primary action: no distinct CTA color

**3-5 Example Component Prompts:**
- Create a hero section: Canvas White background. Headline 'the knowledge tool that sparks creativity' using Control Upright at 142px, Charcoal Text (#181816), line height 0.9, letter-spacing -0.02em. Below that, subtext 'save one thing discover a hundred more' using Control Upright at 28px, Zinc Gray (#908f8e), line height 1.13.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create a White Card: Background Canvas White (#ffffff), 1.5px solid Zinc Gray (#908f8e) border, 5px radius, 18px padding. Inside, a heading 'björk said that' using Control Upright at 18px, Charcoal Text (#181816). Below, a Small Pill Tag 'related' with Mint Accent (#e0f5ff) background, Midnight Ink (#000000) text, 1px solid Midnight Ink (#000000) border, 999px radius, 13px horizontal padding.

## Similar Brands

- **Notion** — High-contrast text on white, focus on content blocks, extensive use of soft grays, and a crisp, functional aesthetic.
- **Linear** — Minimalist UI, strong typographic hierarchy with confident font choices, and monochromatic palette with single accent color.
- **Readwise Reader** — Clean white backgrounds, emphasis on readability through excellent typography, and subtle UI elements that get out of the way of content.
- **Capsule** — Spacious layouts, subtle use of background shades for sectioning, and a general air of 'digital clarity'.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-charcoal-text: #181816;
  --color-fog-gray: #efefef;
  --color-zinc-gray: #908f8e;
  --color-ash-gray: #a29e9c;
  --color-sage-green: #38744d;
  --color-mint-accent: #e0f5ff;
  --color-lime-highlight: #cbffa6;
  --color-slate-text: #6a6967;

  /* Typography — Font Families */
  --font-control-upright: 'Control Upright', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.39;
  --tracking-caption: 0.008px;
  --text-body: 14px;
  --leading-body: 1.39;
  --tracking-body: -0.02px;
  --text-label: 16px;
  --leading-label: 1.39;
  --text-subheading: 18px;
  --leading-subheading: 1.39;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.16;
  --text-heading: 28px;
  --leading-heading: 1.13;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.015px;
  --text-display: 142px;
  --leading-display: 0.9;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 200px;
  --card-padding: 18px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 5px;
  --radius-footer: 40px;
  --radius-buttons: 5px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-charcoal-text: #181816;
  --color-fog-gray: #efefef;
  --color-zinc-gray: #908f8e;
  --color-ash-gray: #a29e9c;
  --color-sage-green: #38744d;
  --color-mint-accent: #e0f5ff;
  --color-lime-highlight: #cbffa6;
  --color-slate-text: #6a6967;

  /* Typography */
  --font-control-upright: 'Control Upright', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.39;
  --tracking-caption: 0.008px;
  --text-body: 14px;
  --leading-body: 1.39;
  --tracking-body: -0.02px;
  --text-label: 16px;
  --leading-label: 1.39;
  --text-subheading: 18px;
  --leading-subheading: 1.39;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.16;
  --text-heading: 28px;
  --leading-heading: 1.13;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.015px;
  --text-display: 142px;
  --leading-display: 0.9;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 999px;
}
```
