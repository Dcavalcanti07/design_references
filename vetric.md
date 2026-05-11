# Vetric — Style Reference
> Crystal clarity, data flow

**Theme:** light

Vetric conveys data clarity through a light, expansive canvas, punctuated by crisp, dark typography and an expressive gradient system. The visual style balances technical precision with a soft, almost ethereal quality, using subtle card treatments and a distinct type pairing. Key information is delivered with restraint, allowing the vibrant, dynamic gradients to provide visual interest and signify data flow.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#090a1e` | `--color-midnight-ink` | Primary text, heading text, critical UI elements, main call to action backgrounds, icon fills. Establishes a strong, grounded foundation against the light canvas |
| Arctic Canvas | `#ffffff` | `--color-arctic-canvas` | Primary page background, card surfaces, ghost button backgrounds. Provides a clean, minimalist backdrop for all content |
| Cloud Gray | `#e0e0e0` | `--color-cloud-gray` | Subtle borders, inactive elements, secondary iconography. Creates visual separation without harsh lines |
| Smoke Gray | `#222222` | `--color-smoke-gray` | Navigation text, secondary button text, subtle link text. Provides contrast while remaining distinct from body text |
| Deep Slate | `#444557` | `--color-deep-slate` | Secondary body text, detailed descriptions, helper text. A darker gray for robust information density |
| Misty Blue | `#c3dae3` | `--color-misty-blue` | Hairline card borders, soft dividers. A very light, cool-tinted gray adds a subtle technical feel |
| Sky Flow | `linear-gradient(90deg, rgb(41, 105, 255), rgb(255, 211, 99))` | `--color-sky-flow` | Info badges, decorative accents, subtle icon fills. Represents information and data visualization segments; Decorative visual elements, section separators. Transitions between key brand hues |
| Rose Haze | `linear-gradient(90deg, rgb(247, 92, 195), rgb(41, 105, 255))` | `--color-rose-haze` | Decorative accents, illustrative elements. A vivid pink for visual flourish and brand recognition; Hero section background blend, decorative visual elements. Creates a dynamic, flowing feel |
| Lime Glow | `#5ab040` | `--color-lime-glow` | Success states, positive indicators, badge backgrounds. Signifies positive outcomes |
| Sunbeam | `linear-gradient(90deg, rgb(255, 211, 99), rgb(90, 176, 64))` | `--color-sunbeam` | Warning states, attention indicators, badge backgrounds. Draws attention to important information; Subtle background accents for abstract shapes. Completes the gradient flow with a warm, energetic tone |
| Lavender Mist | `#fff3fb` | `--color-lavender-mist` | Light background for themed cards and badge backgrounds. A very light pink that hints at brand colors |
| Spring Bud | `#eaffed` | `--color-spring-bud` | Light background for themed cards and badge backgrounds. A pale green for success-related surfaces |
| Vanilla Cream | `#fffdea` | `--color-vanilla-cream` | Light background for themed cards and badge backgrounds. A soft yellow for warning-related surfaces |

## Tokens — Typography

### Noto Serif — Display and primary headings. The serif typeface at large sizes provides gravitas and a classic, established feel, contrasting with the more modern sans-serif body. · `--font-noto-serif`
- **Substitute:** Georgia
- **Weights:** 400, 500
- **Sizes:** 26px, 35px, 42px, 49px, 63px, 77px
- **Line height:** 1.00, 1.06, 1.20, 1.33, 1.40, 1.43
- **Letter spacing:** -0.0500em, -0.0400em
- **Role:** Display and primary headings. The serif typeface at large sizes provides gravitas and a classic, established feel, contrasting with the more modern sans-serif body.

### Manrope — Body copy, subheadings, navigation, buttons, and all functional text. Its clean, geometric form ensures readability and a contemporary tone across the interface. · `--font-manrope`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 11px, 14px, 16px, 18px, 19px, 23px, 26px, 70px
- **Line height:** 0.79, 1.00, 1.10, 1.30, 1.33, 1.50
- **Letter spacing:** -0.0600em, -0.0200em, 0.0600em
- **Role:** Body copy, subheadings, navigation, buttons, and all functional text. Its clean, geometric form ensures readability and a contemporary tone across the interface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 0.66px | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 26px | 1.33 | — | `--text-heading-sm` |
| heading | 35px | 1.33 | -1.4px | `--text-heading` |
| heading-lg | 49px | 1.2 | -1.96px | `--text-heading-lg` |
| display | 77px | 1.06 | -3.08px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 28 | 28px | `--spacing-28` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 7px |
| badges | 50% |
| buttons | 7px |
| interactive | 7px |

### Layout

- **Section gap:** 53px
- **Card padding:** 28px
- **Element gap:** 9px

## Components

### Primary Filled Button
**Role:** Main call to action, critical interaction.

Background: Midnight Ink (#090a1e). Text: Arctic Canvas (#ffffff). Radius: 7px. Padding: 10.5px vertical, 28px horizontal. Manrope font.

### Ghost Button
**Role:** Secondary actions, navigation links where no strong call to action is needed.

Background: transparent. Text: Smoke Gray (#222222). No border. No explicit radius, appears as text link. Padding: 0.

### Neutral Outlined Button
**Role:** Ghost button with an explicit border. Secondary actions, team/jobs link.

Background: Arctic Canvas (#ffffff). Text: Midnight Ink (#090a1e). Border: 1px solid Cloud Gray (#d9d9d9 - derived from CSS tokens). Radius: 7px. Padding: 10.5px vertical, 28px horizontal.

### Info Card (Frosted Transparency)
**Role:** Displaying digestible chunks of information, often featuring subtle contextual data.

Background: Arctic Canvas with 70% opacity (rgba(255, 255, 255, 0.7)). Radius: 7px. Padding: 8.59px. No shadow. Border: 1px solid Misty Blue (#c3dae3).

### Themed Data Card - Pink
**Role:** Highlighting specific data points or features with a branded context.

Background: Lavender Mist (#fff3fb). Radius: 24.5px. Padding: 24.5px vertical, 17.5px horizontal. Text color often Rose Haze (#f75cc3). No shadow. Has a blur filter: blur(14px).

### Themed Data Card - Blue
**Role:** Highlighting specific data points or features with a branded context.

Background: #f1f5ff (from `--color--blue-light` token). Radius: 24.5px. Padding: 24.5px vertical, 17.5px horizontal. Text color often Sky Flow (#2969ff). No shadow. Has a blur filter: blur(14px).

### Semantic Badge - Pink
**Role:** Categorization or small highlight for data points.

Background: Lavender Mist (#fff3fb). Text: Rose Haze (#f75cc3). Radius: 50% (circle). Minimal padding. Used for small, circular indicators.

### Semantic Badge - Blue
**Role:** Categorization or small highlight for data points.

Background: #f1f5ff (from `--color--blue-light` token). Text: Sky Flow (#2969ff). Radius: 50% (circle). Minimal padding. Used for small, circular indicators.

## Do's and Don'ts

### Do
- Use Noto Serif for all headings and display text, applying its characteristic negative letter-spacing for visual impact.
- Apply a 7px border-radius consistently to all buttons and cards for a softened, approachable feel.
- Maintain generous vertical spacing between sections, using the implicit sectionGap of approximately 53px.
- Prioritize Midnight Ink (#090a1e) for primary text and call-to-action fills, ensuring high contrast against light backgrounds.
- Employ the gradient system (Vetric Gradient 1, 2, 3) for hero backgrounds and large decorative elements to signify data dynamism and brand energy.
- Pair Manrope for body text and functional UI elements, ensuring readability and a modern, compact presence.
- Utilize faint, near-gray tints (Misty Blue #c3dae3, Cloud Gray #e0e0e0) for borders and subtle element separation to prevent visual heaviness.

### Don't
- Avoid using harsh shadows; prefer subtle transparency and very light borders for depth.
- Do not introduce new saturated primary colors; strictly adhere to Sky Flow, Rose Haze, Lime Glow, and Sunbeam for all chromatic accents.
- Never use generic black or white for text or backgrounds; always opt for Midnight Ink (#090a1e) for dark text and Arctic Canvas (#ffffff) for light backgrounds for brand consistency.
- Do not deviate from the established type scale and letter-spacing for Noto Serif and Manrope; these are critical for brand voice.
- Refrain from dense, information-heavy blocks; break content into digestible cards and maintain spacious layouts.
- Do not use full-bleed imagery without ample negative space; imagery should feel integrated and airy, not overwhelming.
- Avoid bright, contrasting borders; use muted, achromatic tones like Cloud Gray (#e0e0e0) or Misty Blue (#c3dae3) for card and element outlines.

## Imagery

Imagery predominantly consists of abstract, glowing gradients and geometric shapes, particularly a prominent, faceted diamond graphic with a soft, iridescent glow. Photography is minimal, mostly confined to small, functional icons. When present, graphics are treated with transparency and soft blurs (blur(14px)) to maintain an ethereal, data-flow aesthetic. Icons are simple, outlined, and monochromatic, used sparsely for conceptual reinforcement rather than decorative flair. Density is low, allowing significant white space to dominate.

## Layout

The page utilizes a max-width contained layout rather than full-bleed, though the hero section spans full-width with a gradient background. The hero features a large, centered headline and a distinct abstract graphic below it. Content sections alternate between visually distinct blocks: sometimes a full-width abstract gradient background, other times a clean white background with information structured in clear, responsive card grids or two-column text-left/image-right arrangements. The rhythm is spacious and flowing, with generous vertical section gaps and a clear visual hierarchy. Navigation is a simple, right-aligned top bar.

## Agent Prompt Guide

Quick Color Reference:
text: #090a1e
background: #ffffff
border: #e0e0e0
accent: #f75cc3
primary action: #090a1e (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background Midnight Ink (#090a1e), text Arctic Canvas (#ffffff), 7px radius, 10.5px vertical padding, 28px horizontal padding, Manrope font.
2. Create an Info Card: background rgba(255, 255, 255, 0.7), border 1px solid Misty Blue (#c3dae3), 7px radius, 8.59px padding. Body text Deep Slate (#444557).
3. Create a Display Headline: 'Turning Data Chaos Into Clarity' using Noto Serif weight 500, size 77px, line height 1.06, letter spacing -3.08px, color Midnight Ink (#090a1e).

## Similar Brands

- **Figma** — Clear, spacious, light UI with distinct typography and a minimalist approach to color, using accents judiciously.
- **Linear** — Monochromatic backdrop with intentional use of a single vibrant accent color to highlight interactive elements and status.
- **Stripe** — Focus on elegant typography, clean organization of information, and subtle use of gradients and abstract graphics for brand identity.
- **Supabase** — Modern, light UI with clear information hierarchy and tasteful use of gradients or distinct brand colors as visual flourishes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #090a1e;
  --color-arctic-canvas: #ffffff;
  --color-cloud-gray: #e0e0e0;
  --color-smoke-gray: #222222;
  --color-deep-slate: #444557;
  --color-misty-blue: #c3dae3;
  --color-sky-flow: #2969ff;
  --gradient-sky-flow: linear-gradient(90deg, rgb(41, 105, 255), rgb(255, 211, 99));
  --color-rose-haze: #f75cc3;
  --gradient-rose-haze: linear-gradient(90deg, rgb(247, 92, 195), rgb(41, 105, 255));
  --color-lime-glow: #5ab040;
  --color-sunbeam: #ffd363;
  --gradient-sunbeam: linear-gradient(90deg, rgb(255, 211, 99), rgb(90, 176, 64));
  --color-lavender-mist: #fff3fb;
  --color-spring-bud: #eaffed;
  --color-vanilla-cream: #fffdea;

  /* Typography — Font Families */
  --font-noto-serif: 'Noto Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.66px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.33;
  --text-heading: 35px;
  --leading-heading: 1.33;
  --tracking-heading: -1.4px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.96px;
  --text-display: 77px;
  --leading-display: 1.06;
  --tracking-display: -3.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-88: 88px;

  /* Layout */
  --section-gap: 53px;
  --card-padding: 28px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-3xl: 24.5px;

  /* Named Radii */
  --radius-cards: 7px;
  --radius-badges: 50%;
  --radius-buttons: 7px;
  --radius-interactive: 7px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #090a1e;
  --color-arctic-canvas: #ffffff;
  --color-cloud-gray: #e0e0e0;
  --color-smoke-gray: #222222;
  --color-deep-slate: #444557;
  --color-misty-blue: #c3dae3;
  --color-sky-flow: #2969ff;
  --color-rose-haze: #f75cc3;
  --color-lime-glow: #5ab040;
  --color-sunbeam: #ffd363;
  --color-lavender-mist: #fff3fb;
  --color-spring-bud: #eaffed;
  --color-vanilla-cream: #fffdea;

  /* Typography */
  --font-noto-serif: 'Noto Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.66px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.33;
  --text-heading: 35px;
  --leading-heading: 1.33;
  --tracking-heading: -1.4px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.96px;
  --text-display: 77px;
  --leading-display: 1.06;
  --tracking-display: -3.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-3xl: 24.5px;
}
```
