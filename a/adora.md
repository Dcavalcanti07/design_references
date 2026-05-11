# Adora — Style Reference
> Digital Canvas with Violet Bloom. A pristine workspace where key actions pop with vibrant, focused energy.

**Theme:** light

Adora's design system evokes a digital canvas aesthetic with its predominantly white and subtle off-white backgrounds, punctuated by a vivid violet for primary actions and brand presence. Typography is grounded by a modern sans-serif, using a tighter letter-spacing for a precise, organized feel. Cards and interactive elements are softly rounded, creating a friendly and approachable interface, while decorative strokes and fills hint at an underlying creative energy without overwhelming the functional UI.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, internal component backgrounds |
| Cloud Mist | `#e0e0db` | `--color-cloud-mist` | Subtle borders for buttons and cards, faint dividers |
| Slate Text | `#353241` | `--color-slate-text` | Primary body text, neutral links, general UI text |
| Rich Violet | `#21164c` | `--color-rich-violet` | Headlines, important textual elements, primary icon fills |
| Action Violet | `#592eff` | `--color-action-violet` | Primary call-to-action buttons, active badges, distinctive links and interactive icons — provides energetic focus |
| Air Blue | `#bcf2ff` | `--color-air-blue` | Decorative card backgrounds, accent fills in illustrations |
| Lush Green | `#dfff9d` | `--color-lush-green` | Decorative card backgrounds, accent fills in illustrations |
| Sunset Pink | `#ffaae6` | `--color-sunset-pink` | Decorative card backgrounds, accent strokes in illustrations |
| Neon Pink | `#f843c2` | `--color-neon-pink` | Accent text for labels, decorative badges, icon tints |
| Aqua Blue | `#2ed6ff` | `--color-aqua-blue` | Accent text for labels, decorative badges, icon tints |
| Electric Green | `#a2ea13` | `--color-electric-green` | Success states, accent text for labels, decorative badges, icon tints |
| Soft Gray Fill | `#eeeeee` | `--color-soft-gray-fill` | Subtle background fills for minor interactive elements or sections |

## Tokens — Typography

### PolySans — Display and marketing headlines – its heavier weights and tighter line-height create a bold, modern statement without being ostentatious. · `--font-polysans`
- **Substitute:** Montserrat
- **Weights:** 600, 700
- **Sizes:** 18px, 28px, 38px, 58px, 68px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.02
- **Role:** Display and marketing headlines – its heavier weights and tighter line-height create a bold, modern statement without being ostentatious.

### Plus Jakarta Sans — Body text, UI elements, navigation, and secondary headings – its consistent line-height and versatile weights maintain legibility across various contexts. · `--font-plus-jakarta-sans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 32px
- **Line height:** 1.00, 1.10, 1.60
- **Letter spacing:** -0.02
- **Role:** Body text, UI elements, navigation, and secondary headings – its consistent line-height and versatile weights maintain legibility across various contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.1 | — | `--text-caption` |
| body-sm | 16px | 1.1 | — | `--text-body-sm` |
| body | 18px | 1.1 | — | `--text-body` |
| body-lg | 20px | 1.1 | — | `--text-body-lg` |
| heading-sm | 32px | 1.1 | — | `--text-heading-sm` |

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
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 26px |
| badges | 200px |
| buttons | 12px |

### Layout

- **Section gap:** 30px
- **Card padding:** 40px
- **Element gap:** 5px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action

Background: Action Violet (#592eff). Text: Canvas White (#ffffff), Plus Jakarta Sans, weight 400. Radius: 12px. Padding: 0px vertical, 20px horizontal.

### Ghost Button
**Role:** Button with transparent background and defined text/border color

Background: transparent. Text: Slate Text (#353241), Plus Jakarta Sans. Border: Cloud Mist (#e0e0db), 1px solid. Radius: 12px. Padding: 0px vertical, 20px horizontal.

### Outline Nav Button
**Role:** Navigation button with distinct border

Background: transparent. Text: Slate Text (#353241), Plus Jakarta Sans. Border: Slate Text (#353241), 1px solid. Radius: 8px. Padding: 0px vertical, 5px horizontal.

### Feature Card
**Role:** Informational cards displaying content with an associated visual

Background: Canvas White (#ffffff). Radius: 26px. No shadow. Padding: 0px.

### Gradient Accent Card
**Role:** Decorative cards with soft color washes, used for visual breaks or special content sections

Background: Air Blue (#bcf2ff), Lush Green (#dfff9d), or Sunset Pink (#ffaae6). Radius: 64px. Padding: 48px.

### Outline Badge
**Role:** Small, informational tag with colored text

Background: transparent. Text: Neon Pink (#f843c2). Radius: 200px. Padding: 0px vertical, 8px horizontal.

### Icon Button
**Role:** Small, functional buttons likely containing an icon or short text

Background: transparent. Text: Slate Text (#353241). Radius: 16px. Padding: 0px. Used for language switchers or minor controls.

### Call-to-Action Link
**Role:** Text link that functions as a smaller, less prominent call to action than a button

Text: Action Violet (#592eff), Plus Jakarta Sans, weight 500. No underline by default; hover state implies interaction.

## Do's and Don'ts

### Do
- Use Action Violet (#592eff) exclusively for primary interactive elements, ensuring every click feels significant.
- Apply Cloud Mist (#e0e0db) for subtle borders and dividers, maintaining a lightweight visual structure.
- Pair PolySans for all marketing headlines (58px, 68px) with Rich Violet (#21164c) to project confidence.
- Utilize Plus Jakarta Sans for all body text, UI labels, and navigation with Slate Text (#353241) to ensure high legibility.
- Maintain a consistent border-radius of 26px for all main content cards and 12px for conventional buttons, establishing a signature softly rounded aesthetic.
- Implement -0.02em letter-spacing for all text to achieve a precise, condensed appearance.
- Structure layouts with a 'comfortable' density; use 5px element gaps for inline items and 30px for vertical section spacing.

### Don't
- Do not use saturated colors other than Action Violet, Electric Green, Neon Pink, or Aqua Blue for interactive elements.
- Avoid deep shadows or sharp corners on any UI component; elevation should be minimal, if present.
- Do not vary letter-spacing; the consistent tight tracking is fundamental to Adora's precise typographic style.
- Do not introduce gradients into UI components; gradients are reserved for branding or background illustrations if explicitly specified.
- Do not use any font family other than PolySans for headlines and Plus Jakarta Sans for body/UI text.
- Avoid dense or cluttered layouts; maintain ample whitespace and comfortable spacing between elements and sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default container background |
| 2 | Soft Gray Fill | `#eeeeee` | Backgrounds for minor or secondary interactive elements, subtle section breaks |
| 3 | Card White | `#ffffff` | Background for feature cards and main content blocks, with noticeable rounded corners |

## Imagery

Imagery primarily features contained product screenshots and abstract vector illustrations. Product screenshots are clean, showcasing UI in context and sometimes with slight perspective. Illustrations are minimalistic, often outlined with delicate pastel strokes (e.g., light blue clouds) or filled with vivid brand accents (e.g., stylized spark-like elements in Action Violet, Electric Green). Icons are typically outlined and mono-colored, matching text or accent colors. Imagery serves an explanatory and decorative role, enriching content without being overly dominant. There's a balance between informative product visuals and atmospheric abstract graphics. Density is moderate, allowing space for text.

## Layout

The page uses a contained layout model, with max-width content sections centered, particularly evident in the main content blocks. The hero section features a large, centered headline paired with a call-to-action button stack and a background of abstract, outlined decorative elements. Sections adopt a consistent vertical rhythm with comfortable spacing. Content is often arranged in multi-column grids (e.g., 3-column feature grids) or stacked blocks. There's a noticeable pattern of alternating visual focus between text-heavy and image-heavy blocks. The navigation is a classic top bar, appearing fixed or sticky, with product and resource dropdowns.

## Agent Prompt Guide

Quick Color Reference:
- text: #353241
- background: #ffffff
- border: #e0e0db
- accent: #21164c
- primary action: #592eff (filled action)

Example Component Prompts:
- Create a Primary Action Button: #592eff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a feature card: Canvas White background, 26px radius. Headline 'AI-powered Journey Mapping' using PolySans 28px, Rich Violet, letter-spacing -0.02em. Body text 'Automatically visualize every user path across your product lifecycle' using Plus Jakarta Sans 16px, Slate Text, letter-spacing -0.02em. Include an Electric Green (#a2ea13) Outline Badge 'New Feature' with 200px radius.

## Similar Brands

- **Linear** — Shares a precise, structured UI with a singular, strong brand accent color and a focus on clean typography.
- **Framer** — Exhibits a similar approach to spacious, canvas-like layouts with soft, rounded elements and a strong, modern sans-serif typeface for headlines.
- **Supabase** — Uses a similar light theme with a strong single accent color and refined, technical-leaning typography for a professional SaaS feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-mist: #e0e0db;
  --color-slate-text: #353241;
  --color-rich-violet: #21164c;
  --color-action-violet: #592eff;
  --color-air-blue: #bcf2ff;
  --color-lush-green: #dfff9d;
  --color-sunset-pink: #ffaae6;
  --color-neon-pink: #f843c2;
  --color-aqua-blue: #2ed6ff;
  --color-electric-green: #a2ea13;
  --color-soft-gray-fill: #eeeeee;

  /* Typography — Font Families */
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.1;
  --text-body-sm: 16px;
  --leading-body-sm: 1.1;
  --text-body: 18px;
  --leading-body: 1.1;
  --text-body-lg: 20px;
  --leading-body-lg: 1.1;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;

  /* Typography — Weights */
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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 40px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 64px;
  --radius-full-3: 200px;
  --radius-full-4: 800px;

  /* Named Radii */
  --radius-cards: 26px;
  --radius-badges: 200px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-soft-gray-fill: #eeeeee;
  --surface-card-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-cloud-mist: #e0e0db;
  --color-slate-text: #353241;
  --color-rich-violet: #21164c;
  --color-action-violet: #592eff;
  --color-air-blue: #bcf2ff;
  --color-lush-green: #dfff9d;
  --color-sunset-pink: #ffaae6;
  --color-neon-pink: #f843c2;
  --color-aqua-blue: #2ed6ff;
  --color-electric-green: #a2ea13;
  --color-soft-gray-fill: #eeeeee;

  /* Typography */
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.1;
  --text-body-sm: 16px;
  --leading-body-sm: 1.1;
  --text-body: 18px;
  --leading-body: 1.1;
  --text-body-lg: 20px;
  --leading-body-lg: 1.1;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;

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
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 64px;
  --radius-full-3: 200px;
  --radius-full-4: 800px;
}
```
