# Groq — Style Reference
> Precision orange glow on matte gray. Like a control panel's critical warning light in a sophisticated machine.

**Theme:** light

Groq's aesthetic marries industrial-minimalism with high-energy accents. A muted, near-achromatic palette of warm grays and off-whites provides a calm, technical canvas. The single, vivid orange (#F43E01) provides an immediate, focused punch of energy and urgency, appearing exclusively on key interactive elements. Space Grotesk, with its wide letter-spacing only at smaller sizes, creates a modern, spacious feel even at high information density, while IBM Plex Mono anchors technical detail with its fixed-width precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian Slate | `#2d2f33` | `--color-obsidian-slate` | Primary text, headline color, dark surface backgrounds. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, button text, elevated card surfaces. |
| Warm Mist | `#f3f3ee` | `--color-warm-mist` | Light background for sections and UI elements, subtle contrast against Canvas White. |
| Ash Concrete | `#e8e8de` | `--color-ash-concrete` | Card backgrounds, slightly darker variant of Warm Mist for deeper partitioning. |
| Deep Pewter | `#2a2a25` | `--color-deep-pewter` | Button backgrounds, dark elements, providing strong contrast. |
| Steel Gray | `#c2c2be` | `--color-steel-gray` | Border colors, subtle dividers. |
| Soft Stone | `#69695d` | `--color-soft-stone` | Secondary text, descriptive elements, lighter contrast against dark backgrounds. |
| Faded Quartz | `#9c9c90` | `--color-faded-quartz` | Tertiary text, subtle UI elements, disabled states. |
| Neon Zest | `#f43e01` | `--color-neon-zest` | Primary call-to-action buttons, active states, key interactive indicators — this vivid orange is the sole brand accent, demanding attention. |
| Deep Ember | `#c23101` | `--color-deep-ember` | Darker shade of Neon Zest, used for hover states or subtle brand accents in darker contexts. |
| Lavender Haze | `#e09afe` | `--color-lavender-haze` | Decorative color for specific content sections, not interactive. |
| Violet Tint | `#d377fd` | `--color-violet-tint` | Minor decorative accent, borderline invisible in usage. |

## Tokens — Typography

### Space Grotesk — Primary typeface for all headings, body text, and UI elements. Its slightly condensed forms and negative letter-spacing for larger sizes contribute to a sleek, modern, yet readable presentation. · `--font-space-grotesk`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400
- **Sizes:** 13px, 14px, 15px, 17px, 19px, 21px, 24px, 28px, 32px, 36px, 46px
- **Line height:** 0.90, 1.00, 1.30, 1.40, 1.57
- **Letter spacing:** -0.0200em
- **Role:** Primary typeface for all headings, body text, and UI elements. Its slightly condensed forms and negative letter-spacing for larger sizes contribute to a sleek, modern, yet readable presentation.

### IBM Plex Mono — Used for code snippets, technical figures, and any content requiring monospace precision. Its elevated letter-spacing emphasizes its distinct, technical role. · `--font-ibm-plex-mono`
- **Substitute:** monospace
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 14px
- **Line height:** 1.17, 1.20, 1.30, 1.40, 1.57
- **Letter spacing:** 0.1000em
- **Role:** Used for code snippets, technical figures, and any content requiring monospace precision. Its elevated letter-spacing emphasizes its distinct, technical role.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.57 | 0.1px | `--text-caption` |
| body-lg | 15px | 1.57 | -0.3px | `--text-body-lg` |
| heading-sm | 24px | 1.4 | -0.48px | `--text-heading-sm` |
| heading | 32px | 1.3 | -0.64px | `--text-heading` |
| heading-lg | 36px | 1 | -0.72px | `--text-heading-lg` |
| display | 46px | 0.9 | -0.92px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 5px |
| cards | 0px |
| forms | 10px |
| buttons | 1000px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 48-80px
- **Card padding:** 0px
- **Element gap:** 4-16px

## Components

### Primary Action Button
**Role:** Call to action

Background: Neon Zest (#f43e01), Text: Canvas White (#ffffff), Border: Canvas White (#ffffff). Radius: 1000px (full pill). Padding: 10px vertical, 16px horizontal. This is the prominent interactive element. Text uses Space Grotesk.

### Ghost Button
**Role:** Secondary action

Background: transparent (rgba(0,0,0,0)), Text: Obsidian Slate (#2d2f33), Border: Obsidian Slate (#2d2f33). Radius: 1000px. Padding: 0px. Used for subtle navigation or less critical actions. Text uses Space Grotesk.

### Utility Button
**Role:** Tertiary action

Background: Deep Pewter (#2a2a25), Text: Warm Mist (#f3f3ee), No border. Radius: 5px. Padding: 12px. Used for footer or less prominent interaction. Text uses Space Grotesk.

### Navigation Link
**Role:** Header navigation

Background: transparent (rgba(0,0,0,0)), Text: Obsidian Slate (#2d2f33), No border. Radius: 1000px. Padding: 10px vertical, 16px horizontal, or 0px. Used for top navigation items. Text uses Space Grotesk.

### Hero Card
**Role:** Informational block

Background: transparent (rgba(0,0,0,0)), No border, No shadow. Radius: 0px. Padding: 0px. Used in the main content area for visual emphasis. Text uses Space Grotesk.

### Testimonial Card
**Role:** Social proof

Background: Ash Concrete (#e8e8de), No border, No shadow. Radius: 0px. Padding: 0px. Used for customer quotes. Text uses Space Grotesk.

## Do's and Don'ts

### Do
- Always use Neon Zest (#f43e01) exclusively for primary calls to action or critical indicators to preserve its impact.
- Maintain a clear visual hierarchy by limiting headline weights to Space Grotesk 300 or 400, rather than bolder weights, to align with the understated authority.
- Apply a 1000px border-radius to all primary interactive elements (buttons, navigation pills) for a consistent, modern softness.
- Utilize a base spacing unit of 8px, applying multiples like 4px, 8px, 12px, 16px for comfortable density.
- Use Space Grotesk with -0.0200em letter spacing for headlines to give them an expansive, deliberate feel.
- Employ IBM Plex Mono only for technical content, ensuring its 0.1000em letter spacing clearly distinguishes it from untracked text.

### Don't
- Never introduce additional vivid color accents; Neon Zest (#f43e01) is the sole saturated brand color.
- Avoid using drop shadows for elevation; rely on background color changes (e.g., Canvas White, Warm Mist, Ash Concrete) for depth.
- Do not vary border radii outside of the established 1000px for buttons, 5px for utility elements, and 0px for informational cards to maintain shape consistency.
- Do not use generic system fonts; always specify Space Grotesk or IBM Plex Mono for brand consistency.
- Avoid arbitrary uses of uppercase; only apply to specific, clearly defined labels or components following established patterns.

## Imagery

This site prominently features a mixed visual language. Product screenshots are contained and serve an explanatory role. These are often tightly cropped, emphasizing the hardware or specific UI. The brand uses abstract, clean graphics to illustrate concepts, which are geometric and often monochromatic or leverage the subtle neutral palette. There's also some usage of partner logos in a grayscale, badge-like style for social proof. The overall density is balanced, with imagery serving both decorative atmosphere and explanatory content roles, often nestled within text blocks or acting as visual anchors in sections. When present, icons are filled and subtle, blending into the UI rather than standing out.

## Layout

The page adheres to a max-width contained model (1440px), where content is centered within a clear canvas. The hero section often adopts a split-layout pattern, with a prominent headline and call-to-action on one side and a product visual or abstract graphic on the other. Section rhythm alternates between light (Canvas White, Warm Mist) and darker (Black, Deep Pewter) backgrounds, creating clear visual breaks and an implicit flow down the page. Content arrangement frequently uses a text-left/image-right alternating pattern. There's also a grid for customer testimonials, appearing in a three-column layout. The overall density is comfortable, with generous section gaps. A sticky header with top-level navigation ensures constant access to key links and a 'Start Building' CTA.

## Agent Prompt Guide

### Quick Color Reference
- Text (primary): #2d2f33
- Background (page): #ffffff
- Background (section): #f3f3ee
- CTA (button): #f43e01
- CTA (text): #ffffff
- Border (subtle): #c2c2be

### 3-5 Example Component Prompts
1. Create a primary hero button: 'Start Building' text with Space Grotesk, 400 weight, 14px size, Canvas White (#ffffff) text color. Background is Neon Zest (#f43e01), border is Canvas White (#ffffff). Corner radius is 1000px, padding 10px vertical and 16px horizontal.
2. Design a section with a Warm Mist (#f3f3ee) background: Use a headline 'To deliver different results, you need a different stack.' with Space Grotesk, 46px size, 0.9 lineHeight, 300 weight, Obsidian Slate (#2d2f33) color, and -0.0200em letter spacing. Below it, add a body paragraph with Space Grotesk, 15px size, 1.57 lineHeight, 400 weight, Soft Stone (#69695d) color.
3. Implement a Testimonial Card: Ash Concrete (#e8e8de) background, 0px border-radius, 0px padding. Inside, use a quote in Space Grotesk, 17px size, 1.57 lineHeight, 400 weight, Obsidian Slate (#2d2f33) color.
4. Generate a technical explanation block: Deep Pewter (#2a2a25) background with Canvas White (#ffffff) as the main text color at 14px (Space Grotesk). Include an inline code snippet using IBM Plex Mono, 12px size, 1.4 lineHeight, 400 weight, Canvas White (#ffffff) color, and 0.1000em letter spacing.

## Similar Brands

- **Vercel** — Similar approach to using a refined neutral palette with a single, highly saturated accent color for primary actions, and a preference for modern sans-serif typography.
- **Netlify** — Shares a technical, developer-centric aesthetic with clear, functional layouts and a balance of informational graphics and concise text, avoiding decorative flourishes.
- **Stripe** — Employs a clean, spacious layout, strong typography with subtle letter-spacing adjustments, and selective use of brand colors to highlight key information in an understated, authoritative manner.
- **Linear** — Features a highly optimized, minimalist UI with a near-achromatic base, strong typography for hierarchy, and pops of color for interaction, reflecting a focus on efficiency and precision.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian-slate: #2d2f33;
  --color-canvas-white: #ffffff;
  --color-warm-mist: #f3f3ee;
  --color-ash-concrete: #e8e8de;
  --color-deep-pewter: #2a2a25;
  --color-steel-gray: #c2c2be;
  --color-soft-stone: #69695d;
  --color-faded-quartz: #9c9c90;
  --color-neon-zest: #f43e01;
  --color-deep-ember: #c23101;
  --color-lavender-haze: #e09afe;
  --color-violet-tint: #d377fd;

  /* Typography — Font Families */
  --font-space-grotesk: 'Space Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.57;
  --tracking-caption: 0.1px;
  --text-body-lg: 15px;
  --leading-body-lg: 1.57;
  --tracking-body-lg: -0.3px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.72px;
  --text-display: 46px;
  --leading-display: 0.9;
  --tracking-display: -0.92px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 48-80px;
  --card-padding: 0px;
  --element-gap: 4-16px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-misc: 5px;
  --radius-cards: 0px;
  --radius-forms: 10px;
  --radius-buttons: 1000px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian-slate: #2d2f33;
  --color-canvas-white: #ffffff;
  --color-warm-mist: #f3f3ee;
  --color-ash-concrete: #e8e8de;
  --color-deep-pewter: #2a2a25;
  --color-steel-gray: #c2c2be;
  --color-soft-stone: #69695d;
  --color-faded-quartz: #9c9c90;
  --color-neon-zest: #f43e01;
  --color-deep-ember: #c23101;
  --color-lavender-haze: #e09afe;
  --color-violet-tint: #d377fd;

  /* Typography */
  --font-space-grotesk: 'Space Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.57;
  --tracking-caption: 0.1px;
  --text-body-lg: 15px;
  --leading-body-lg: 1.57;
  --tracking-body-lg: -0.3px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.72px;
  --text-display: 46px;
  --leading-display: 0.9;
  --tracking-display: -0.92px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-full: 1000px;
}
```
