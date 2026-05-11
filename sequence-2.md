# Sequence — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Sequence establishes a sunlit, architectural clarity with a predominant white canvas, delicate grays, and precise monochrome elements. Subtle background gradients add depth without overwhelming the product's clean functionality. Typography is compact and confident, grounding the interface with a technical yet approachable feel. The visual system emphasizes functional directness, using soft elevation and a single, vivid violet accent for key interactions and brand highlights.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page backgrounds, elevated card surfaces, clean visual fields for product elements |
| Cloud Gray | `#f7f7f7` | `--color-cloud-gray` | Subtle background for UI sections, secondary card backgrounds, adds minimal depth to surfaces |
| Ghost Gray | `#efefef` | `--color-ghost-gray` | Lightest button backgrounds, subtle input fields, and soft horizontal dividers |
| Stone Grey | `linear-gradient(122deg, rgba(240, 240, 240, 0.1) -21.06%, rgba(128, 128, 128, 0.08) 49.35%, rgb(255, 255, 255))` | `--color-stone-grey` | Hairline borders, subtle separators, and default input borders. Sets a clean boundary without harshness; Subtle linear background gradient for foundational sections, adding a soft, layered feel to the canvas |
| Graphite | `#505050` | `--color-graphite` | Primary body text, main headings, and active icon fills. Provides strong readability against light backgrounds |
| Dark Slate | `#42424a` | `--color-dark-slate` | Secondary text, metadata, and muted button text. Creates visual separation from primary text |
| Ash | `#757575` | `--color-ash` | Muted text, helper labels, and inactive icon states. Offers a softer contrast |
| Deep Ink | `#1d1d20` | `--color-deep-ink` | Dominant headings and critical information where maximum impact is required |
| Sequence Violet | `#a565ff` | `--color-sequence-violet` | Primary action backgrounds, interactive states, and decorative icon accents. Serves as the primary brand accent color |
| Deep Violet | `#5e5cff` | `--color-deep-violet` | Accent text in navigation or specific body text for emphasis, creates a vibrant highlight |
| Pale Violet Background | `#ebebff` | `--color-pale-violet-background` | Light background wash for emphasized content blocks or subtle visual breaks |
| Muted Violet Glow | `#e0c9ff` | `--color-muted-violet-glow` | Violet supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Accent Green | `#2e7317` | `--color-accent-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Hero Background Gradient | `linear-gradient(90deg, rgb(192, 230, 255), rgb(246, 242, 250) 70%)` | `--color-hero-background-gradient` | Soft linear gradient used for hero sections, blending light blues and whites to create an open, airy feeling |
| Subtle Radial Overlay | `radial-gradient(48.66% 55.03% at 52.96% 48.34%, rgba(186, 217, 249, 0.8) 0%, rgba(234, 234, 255, 0.8) 20%, rgba(186, 217, 249, 0) 100%)` | `--color-subtle-radial-overlay` | Decorative radial gradient for background visual interests, creating a soft, almost ethereal effect |

## Tokens — Typography

### twkLausanne — Primary font for all UI elements: body text, navigation, buttons, and most headings. Its varied weights allow for clear hierarchy and a modern, compact feel. · `--font-twklausanne`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 24px
- **Line height:** 1.00, 1.10, 1.20, 1.25, 1.33, 1.40, 1.43, 1.45, 1.50, 1.56, 1.60, 1.63, 1.67, 1.71, 1.75, 1.78, 1.80, 1.82, 1.85, 2.00
- **Letter spacing:** -0.0030em, -0.0020em
- **Role:** Primary font for all UI elements: body text, navigation, buttons, and most headings. Its varied weights allow for clear hierarchy and a modern, compact feel.

### moderatSerif — Signature font for large display headings. Its subtle serifs at light weights provide a unique, authoritative presence without being overly bold, creating an almost whispered impact. · `--font-moderatserif`
- **Substitute:** Georgia, serif
- **Weights:** 300, 400
- **Sizes:** 40px, 46px
- **Line height:** 1.00
- **Letter spacing:** -0.0250em
- **Role:** Signature font for large display headings. Its subtle serifs at light weights provide a unique, authoritative presence without being overly bold, creating an almost whispered impact.

### sfMono — Monospaced font for code snippets, data readouts, and technical details, ensuring precise character alignment. · `--font-sfmono`
- **Substitute:** Menlo, monospace
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.50, 1.80
- **Letter spacing:** normal
- **Role:** Monospaced font for code snippets, data readouts, and technical details, ensuring precise character alignment.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.002px | `--text-caption` |
| body | 14px | 1.5 | -0.002px | `--text-body` |
| subheading | 18px | 1.4 | -0.003px | `--text-subheading` |
| heading | 24px | 1.33 | -0.003px | `--text-heading` |
| display-sm | 40px | 1 | -0.025px | `--text-display-sm` |
| display | 46px | 1 | -0.025px | `--text-display` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| cards | 8px |
| buttons | 9999px |
| default | 4px |
| largeCards | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(58, 58, 64, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1)...` | `--shadow-subtle` |
| subtle-2 | `rgba(29, 29, 32, 0.08) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| subtle-3 | `rgb(239, 239, 239) 0px 0px 0px 2px, rgba(0, 0, 0, 0.01) 0...` | `--shadow-subtle-3` |
| sm | `rgba(99, 102, 241, 0.4) 0px 0px 8px 2px` | `--shadow-sm` |
| subtle-4 | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px` | `--shadow-subtle-4` |
| subtle-5 | `rgba(117, 117, 117, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0...` | `--shadow-subtle-5` |
| subtle-6 | `rgba(255, 255, 255, 0.14) 0px 1px 0px 0px inset, rgba(13,...` | `--shadow-subtle-6` |
| subtle-7 | `rgba(80, 80, 80, 0.1) 0px 0px 0px 1px` | `--shadow-subtle-7` |
| subtle-8 | `rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1...` | `--shadow-subtle-8` |
| sm-2 | `rgba(0, 0, 0, 0.04) 0px 4px 6px 0px, rgb(242, 242, 242) 0...` | `--shadow-sm-2` |
| subtle-9 | `rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1...` | `--shadow-subtle-9` |
| subtle-10 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-10` |
| subtle-11 | `rgba(117, 117, 117, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0...` | `--shadow-subtle-11` |
| subtle-12 | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset` | `--shadow-subtle-12` |
| subtle-13 | `rgb(165, 101, 255) 0px 0px 0px 1px` | `--shadow-subtle-13` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Action button with an invisible background and text that blends with surrounds till hovered.

Background: transparent. Text: Graphite (#505050). Border: Stone Grey (#e5e7eb) 1px. Radius: 9999px. Padding: 0px 14px 0px 8px.

### Secondary Ghost Button
**Role:** Muted action button or navigation link for less prominent interactions.

Background: transparent. Text: Ash (#757575). Border: Stone Grey (#e5e7eb) 1px. Radius: 4px. Padding: 0px.

### Branded Pill Button
**Role:** Primary call to action, drawing attention with the brand accent color.

Background: Sequence Violet (#a565ff). Text: White (#ffffff). Radius: 4px. Padding: 0px.

### Outline Pill Button
**Role:** Subtle, secondary call to action that needs slightly more emphasis than a ghost button.

Background: Ghost Gray (#efefef). Text: Graphite (#505050). Radius: 20px. Padding: 12px 16px.

### Content Card - Default
**Role:** Container for articles, features, or small product showcases.

Background: Cloud Gray (#f7f7f7). Border: 1px solid rgba(80, 80, 80, 0.1). Radius: 8px. No padding at root, content provides its own inner padding.

### Content Card - Elevated
**Role:** Prominent information containers that require clear separation and subtle 'lift'.

Background: Canvas White (#ffffff, 0.7 opacity). Box Shadow: rgba(117,117,117,0.1) 0px 0px 0px 1px, rgba(0,0,0,0.05) 0px 10px 15px -3px, rgba(0,0,0,0.05) 0px 4px 6px -4px. Radius: 16px 0px 0px 16px for visible corners. No padding at root.

### Input Field - Full Width
**Role:** Standard editable text input for forms.

Background: Canvas White (#ffffff). Text: Graphite (#505050). Border: Stone Grey (#e5e7eb) 1px. Radius: 0px. No padding at root.

### Input Field - Underscored
**Role:** Minimalist input style with only a bottom border, often for search or focused data entry.

Background: transparent. Text: Graphite (#505050). Border-bottom: Stone Grey (#e5e7eb) 1px. Radius: 0px. No padding at root.

## Do's and Don'ts

### Do
- Use twkLausanne font family for all body text, navigation, and most headings, employing its various weights to establish visual hierarchy.
- Apply moderatSerif for signature large display headings between 40px and 46px at weights 300 or 400 with -0.0250em letter spacing.
- Reserve Sequence Violet (#a565ff) exclusively for primary calls to action, brand highlights, and decorative icon accents.
- Implement Canvas White (#ffffff) as the dominant background for all major sections and elevated cards to maintain an airy, expansive feel.
- Define UI element borders with Stone Grey (#e5e7eb) at 1px thickness for a delicate, crisp separation.
- Apply a 9999px border-radius to all buttons for a friendly, pill-shaped aesthetic.
- Employ Cloud Gray (#f7f7f7) for subtle background shifts to differentiate sections without heavy visual dividers.

### Don't
- Avoid using multiple accent colors; keep Sequence Violet (#a565ff) as the singular chromatic highlight for interactive elements.
- Do not introduce strong, opaque background gradients on interface elements, instead opt for subtle, near-transparent washes or blurred effects.
- Do not use heavy, dark drop shadows; maintain a light elevation style with minimal offset and transparency, referencing the existing shadow tokens.
- Refrain from using excessively bold weights for body text; prioritize clarity and a compact information display with twkLausanne at weights 400 or below.
- Do not deviate from the established spacing scale; maintain a compact density, relying on 4px and 8px increments for element gaps and small paddings.
- Avoid sharp, angular corners on cards; use 8px or 16px radius to align with the slightly softer visual style.
- Do not introduce complex color patterns or highly saturated hues outside of the defined brand and accent colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Background | `#e5e7eb` | Dominant background color for the overall page, providing a very subtle off-white base. |
| 2 | Base Surface | `#ffffff` | Default background for most cards, content blocks, and UI elements, ensuring crisp contrast. |
| 3 | Nested Surface | `#f7f7f7` | Slightly darker secondary background used for nested cards or to subtly differentiate content areas. |
| 4 | Elevated Surface | `#ffffff` | Transparent white background with subtle shadow, indicating an elevated or interactive card element. |

## Elevation

- **Card - Elevated:** `rgba(255, 255, 255) 0px 0px 0px 0px, rgba(117, 117, 117, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 10px 15px -3px, rgba(0, 0, 0, 0.05) 0px 4px 6px -4px`
- **Interactive Button/Card:** `rgba(58, 58, 64, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`
- **Focal Interaction Indicator:** `rgba(99, 102, 241, 0.4) 0px 0px 8px 2px`

## Imagery

The site predominantly uses abstract, blueprint-like illustrations, often with a subtle glowing effect or faded outlines against a light background. These conceptual visuals provide context without being literal product screenshots. When product imagery is present, it's typically clean, outlined UI mockups or line-art illustrations of interfaces. Icons are monochromatic, mostly outlined with a consistent stroke weight, and occasionally filled with Sequence Violet (#a565ff) for emphasis. Imagery serves a decorative and atmospheric role, rather than purely informational, creating an intellectual and somewhat futuristic mood. Image density is moderate, carefully balanced with significant white space.

## Layout

The page maintains a centered max-width content area, often implicit, creating a contained and organized feel. The hero section features a centered headline over a subtle, full-bleed gradient background, establishing an open first impression. Section rhythm is predominantly defined by alternating white and subtly grayed backgrounds, often with soft linear gradients, creating a seamless flow without overt dividers. Content is arranged in alternating text-left/visual-right patterns or centered stacked blocks, providing clear visual progression. Grid usage includes multi-column feature lists with icons and descriptions, and card grids for solutions or partners. The overall density is spacious between sections, but content within blocks is compact. Navigation is a sticky top bar with a clear brand logo, primary links, and distinct 'Sign in' and 'Book demo' actions.

## Agent Prompt Guide

Quick Color Reference:
text: #505050
background: #ffffff
border: #e5e7eb
accent: #a565ff
primary action: #a565ff (filled action)

Example Component Prompts:
1. Create a Hero Headline: Use moderatSerif, weight 300, 46px, lineHeight 1.0, letterSpacing -0.025em, color Deep Ink (#1d1d20). The text reads 'The AI Revenue platform for Next Gen Finance teams'.
2. Create a Primary CTA Button: Background Sequence Violet (#a565ff), text Canvas White (#ffffff), twkLausanne weight 500, 16px, lineHeight 1.5, radius 9999px, padding 12px 16px. The text reads 'Book a demo'.
3. Create a Secondary Ghost Link: Text Graphite (#505050), twkLausanne weight 400, 14px, lineHeight 1.5, transparent background, no border. The text reads 'Take a tour →'.
4. Create a Feature Card: Background Canvas White (#ffffff), border 1px solid rgba(80, 80, 80, 0.1), border-radius 8px, padding 24px on all sides for content. Include a heading in Graphite (#505050), twkLausanne weight 600, 18px and body text in Ash (#757575), twkLausanne weight 400, 14px.

## Similar Brands

- **Linear** — Monochromatic interface with heavy reliance on whitespace, delicate borders, and a single, vibrant accent color for interaction.
- **Stripe** — Clean, almost sparse UI, precise typography with subtle letter spacing, and a focus on content hierarchy through varied text weights rather than color.
- **Vercel** — Minimalist design, strong typographic presence, and subtle background textures/gradients that add depth without visual clutter.
- **Notion** — White canvas aesthetic, compact typography, and a system built around content rather than heavy decorative elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f7f7f7;
  --color-ghost-gray: #efefef;
  --color-stone-grey: #e5e7eb;
  --gradient-stone-grey: linear-gradient(122deg, rgba(240, 240, 240, 0.1) -21.06%, rgba(128, 128, 128, 0.08) 49.35%, rgb(255, 255, 255));
  --color-graphite: #505050;
  --color-dark-slate: #42424a;
  --color-ash: #757575;
  --color-deep-ink: #1d1d20;
  --color-sequence-violet: #a565ff;
  --color-deep-violet: #5e5cff;
  --color-pale-violet-background: #ebebff;
  --color-muted-violet-glow: #e0c9ff;
  --color-accent-green: #2e7317;
  --color-hero-background-gradient: #c0e6ff;
  --gradient-hero-background-gradient: linear-gradient(90deg, rgb(192, 230, 255), rgb(246, 242, 250) 70%);
  --color-subtle-radial-overlay: #b9d9f9;
  --gradient-subtle-radial-overlay: radial-gradient(48.66% 55.03% at 52.96% 48.34%, rgba(186, 217, 249, 0.8) 0%, rgba(234, 234, 255, 0.8) 20%, rgba(186, 217, 249, 0) 100%);

  /* Typography — Font Families */
  --font-twklausanne: 'twkLausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-moderatserif: 'moderatSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sfmono: 'sfMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.002px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.002px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.003px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.003px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.025px;
  --text-display: 46px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-cards: 8px;
  --radius-buttons: 9999px;
  --radius-default: 4px;
  --radius-largecards: 16px;

  /* Shadows */
  --shadow-subtle: rgba(58, 58, 64, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px;
  --shadow-subtle-3: rgb(239, 239, 239) 0px 0px 0px 2px, rgba(0, 0, 0, 0.01) 0px 22px 9px 0px, rgba(0, 0, 0, 0.04) 0px 12px 7px 0px, rgba(0, 0, 0, 0.06) 0px 5px 5px 0px, rgba(0, 0, 0, 0.07) 0px 1px 3px 0px;
  --shadow-sm: rgba(99, 102, 241, 0.4) 0px 0px 8px 2px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-5: rgba(117, 117, 117, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.14) 0px 1px 0px 0px inset, rgba(13, 25, 37, 0.08) 0px 1px 1px 0px, rgba(14, 26, 38, 0.05) 0px 0px 0px 1px, rgba(13, 25, 37, 0.05) 0px 2px 3px 0px;
  --shadow-subtle-7: rgba(80, 80, 80, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-8: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-sm-2: rgba(0, 0, 0, 0.04) 0px 4px 6px 0px, rgb(242, 242, 242) 0px 0px 0px 4px, rgba(0, 0, 0, 0.03) 0px 0px 0px 1px;
  --shadow-subtle-9: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-10: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-11: rgba(117, 117, 117, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 10px 15px -3px, rgba(0, 0, 0, 0.05) 0px 4px 6px -4px;
  --shadow-subtle-12: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset;
  --shadow-subtle-13: rgb(165, 101, 255) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-canvas-background: #e5e7eb;
  --surface-base-surface: #ffffff;
  --surface-nested-surface: #f7f7f7;
  --surface-elevated-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-gray: #f7f7f7;
  --color-ghost-gray: #efefef;
  --color-stone-grey: #e5e7eb;
  --color-graphite: #505050;
  --color-dark-slate: #42424a;
  --color-ash: #757575;
  --color-deep-ink: #1d1d20;
  --color-sequence-violet: #a565ff;
  --color-deep-violet: #5e5cff;
  --color-pale-violet-background: #ebebff;
  --color-muted-violet-glow: #e0c9ff;
  --color-accent-green: #2e7317;
  --color-hero-background-gradient: #c0e6ff;
  --color-subtle-radial-overlay: #b9d9f9;

  /* Typography */
  --font-twklausanne: 'twkLausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-moderatserif: 'moderatSerif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sfmono: 'sfMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.002px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.002px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.003px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.003px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.025px;
  --text-display: 46px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(58, 58, 64, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px;
  --shadow-subtle-3: rgb(239, 239, 239) 0px 0px 0px 2px, rgba(0, 0, 0, 0.01) 0px 22px 9px 0px, rgba(0, 0, 0, 0.04) 0px 12px 7px 0px, rgba(0, 0, 0, 0.06) 0px 5px 5px 0px, rgba(0, 0, 0, 0.07) 0px 1px 3px 0px;
  --shadow-sm: rgba(99, 102, 241, 0.4) 0px 0px 8px 2px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-5: rgba(117, 117, 117, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.14) 0px 1px 0px 0px inset, rgba(13, 25, 37, 0.08) 0px 1px 1px 0px, rgba(14, 26, 38, 0.05) 0px 0px 0px 1px, rgba(13, 25, 37, 0.05) 0px 2px 3px 0px;
  --shadow-subtle-7: rgba(80, 80, 80, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-8: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-sm-2: rgba(0, 0, 0, 0.04) 0px 4px 6px 0px, rgb(242, 242, 242) 0px 0px 0px 4px, rgba(0, 0, 0, 0.03) 0px 0px 0px 1px;
  --shadow-subtle-9: rgba(29, 29, 32, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-10: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-11: rgba(117, 117, 117, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 10px 15px -3px, rgba(0, 0, 0, 0.05) 0px 4px 6px -4px;
  --shadow-subtle-12: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset;
  --shadow-subtle-13: rgb(165, 101, 255) 0px 0px 0px 1px;
}
```
