# Pietrastudio — Style Reference
> Warm digital canvas

**Theme:** light

Pietra exudes a dynamic, clean, digital canvas aesthetic. Its visual system is built on a crisp white backdrop, punctuated by a vibrant, warm orange action color and muted, pastel gradients that provide visual interest and a sense of depth without overwhelming the UI. Typography is compact and understated, allowing the strong contrasts of the brand orange and deep charcoal text to command attention. Components tend towards soft, rounded shapes and subtle shadow effects, creating a friendly yet capable interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text on dark backgrounds |
| Stone Grey | `#f8f6f2` | `--color-stone-grey` | Subtly elevated card surfaces, background for certain sections |
| Midnight Ink | `#1f2026` | `--color-midnight-ink` | Primary text, heading text |
| Ink Wash | `#141414` | `--color-ink-wash` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Slate Text | `#6b6b6b` | `--color-slate-text` | Muted body text, icon fills, helper text |
| Silver Link | `#c4c4c4` | `--color-silver-link` | Disabled text, decorative borders, inactive link text |
| Input Border Gray | `#e8e8ea` | `--color-input-border-gray` | Subtle borders for input fields and dividers |
| Action Orange | `#ff5c3c` | `--color-action-orange` | Primary call-to-action buttons, active states, brand highlights – a vivid, energetic accent |
| Slightly Yellowed | `#fffbe7` | `--color-slightly-yellowed` | Subtle background for specific card states or emphasis |
| Amber Dot | `#f9e070` | `--color-amber-dot` | Decorative dots, specific badge backgrounds, highlights for certain content categories |
| Forest Green | `#57ad6a` | `--color-forest-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Lavender Sky Gradient | `radial-gradient(127.58% 127.5% at 25.04% 20.84%, rgb(83, 90, 255) 0%, rgb(125, 51, 247) 100%)` | `--color-lavender-sky-gradient` | Atmospheric background for hero sections or prominent content blocks |
| Sunset Blush Gradient | `linear-gradient(43deg, rgb(255, 74, 74) 26.92%, rgb(233, 170, 75) 77.91%)` | `--color-sunset-blush-gradient` | Warm, inviting background for decorative elements or contextual overlays. Primarily decorative |
| Ocean Bloom Gradient | `radial-gradient(208.48% 182.32% at -0.04% -0.23%, rgb(65, 175, 255) 0%, rgb(72, 101, 255) 100%)` | `--color-ocean-bloom-gradient` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Emerald Coast Gradient | `radial-gradient(213.37% 213.37% at 27.54% 0%, rgb(113, 206, 81) 0%, rgb(50, 203, 139) 100%)` | `--color-emerald-coast-gradient` | Fresh, natural background for positive feedback or growth-oriented content |
| Orchid Haze Gradient | `radial-gradient(127.58% 127.5% at 25.04% 20.84%, rgb(200, 83, 255) 0%, rgb(247, 51, 239) 100%)` | `--color-orchid-haze-gradient` | Playful, energetic background for dynamic content or showcases |
| Paper Tint Gradient | `linear-gradient(43deg, rgb(249, 219, 219) 26.92%, rgb(253, 241, 223) 77.91%)` | `--color-paper-tint-gradient` | Very subtle background for blending different sections or soft containers |

## Tokens — Typography

### Labil Grotesk — Primary UI font for body text, navigation items, buttons, and form labels. Its compact form and slight negative letter-spacing make it feel efficient and modern. · `--font-labil-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 15px, 16px, 20px, 24px
- **Line height:** 1.00, 1.20, 1.57
- **Letter spacing:** -0.01em
- **Role:** Primary UI font for body text, navigation items, buttons, and form labels. Its compact form and slight negative letter-spacing make it feel efficient and modern.

### Labil-Regular — Used for specific body text needs, links, and subtle details. The 300 weight allows for a lighter touch than the standard Labil Grotesk, which helps differentiate visual hierarchy. · `--font-labil-regular`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.13, 1.20, 1.50
- **Letter spacing:** -0.01em, 0.143em
- **Role:** Used for specific body text needs, links, and subtle details. The 300 weight allows for a lighter touch than the standard Labil Grotesk, which helps differentiate visual hierarchy.

### Labil-Bold — Used for emphasis in body and button text, and for smaller feature headlines. The 48px size with a tighter letter spacing creates a strong, condensed impact for key statements. · `--font-labil-bold`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 20px, 48px
- **Line height:** 1.00, 1.13, 1.20
- **Letter spacing:** -0.02em, -0.01em
- **Role:** Used for emphasis in body and button text, and for smaller feature headlines. The 48px size with a tighter letter spacing creates a strong, condensed impact for key statements.

### Attila-Bold — Reserved for prominent headings and titles. Its distinct bold character ensures hierarchy and a strong brand voice. · `--font-attila-bold`
- **Substitute:** Archivo Black
- **Weights:** 400
- **Sizes:** 32px, 40px, 48px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.02em, -0.013em
- **Role:** Reserved for prominent headings and titles. Its distinct bold character ensures hierarchy and a strong brand voice.

### Attila Sans Uniform — Used for the most impactful display headings. The heavy weight and very tight letter-spacing create a dominant visual statement. · `--font-attila-sans-uniform`
- **Substitute:** Archivo Black
- **Weights:** 700
- **Sizes:** 48px, 50px
- **Line height:** 1.20
- **Letter spacing:** -0.02em
- **Role:** Used for the most impactful display headings. The heavy weight and very tight letter-spacing create a dominant visual statement.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.57 | -0.12px | `--text-caption` |
| body-sm | 14px | 1.57 | -0.14px | `--text-body-sm` |
| body | 16px | 1.57 | -0.16px | `--text-body` |
| subheading | 20px | 1.2 | -0.2px | `--text-subheading` |
| heading | 24px | 1.2 | -0.24px | `--text-heading` |
| heading-lg | 32px | 1 | -0.64px | `--text-heading-lg` |
| display | 48px | 1 | -0.96px | `--text-display` |
| display-xl | 50px | 1.2 | -1px | `--text-display-xl` |

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
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 124 | 124px | `--spacing-124` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| inputs | 8px |
| buttons | 8px |
| largeElements | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255,...` | `--shadow-subtle` |
| xl | `rgba(134, 137, 141, 0.2) 0px 0px 40px 0px` | `--shadow-xl` |
| lg | `rgba(239, 227, 225, 0.3) 5px 5px 24px 0px` | `--shadow-lg` |
| xl-2 | `rgba(133, 136, 140, 0.2) 0px 0px 40px 0px` | `--shadow-xl-2` |
| subtle-2 | `rgba(0, 0, 0, 0.02) 0px 2px 0px 0px` | `--shadow-subtle-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 120px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** The main call-to-action button, signaling key interactions.

Background: #ff5c3c, Text: #ffffff, Border radius: 8px, Padding: 12px vertical, 20px horizontal. Emphasizes urgency and action.

### Secondary Filled Button (Dark)
**Role:** Alternative action button, often for less critical actions.

Background: #141414, Text: #ffffff, Border radius: 8px, Padding: 12px vertical, 20px horizontal. Provides a strong, contrasting alternative.

### Outline Ghost Button (Light Text)
**Role:** Subtle button for secondary actions or links where a filled button is too heavy.

Background: transparent, Text: #1f2026, Border radius: 8px, Padding: 12px vertical, 20px horizontal. Typically paired with a stronger CTA.

### Outlined Ghost Button (Yellow Accent)
**Role:** Contextual action button with a hint of accent color.

Background: transparent, Text: #141414, Border radius: 8px, Padding: 12px vertical, 20px horizontal. Border: 1px #f9e070 solid. Used for actions related to 'learning more' or specific categories.

### Default Card
**Role:** General content container for features, information blocks.

Background: rgba(255, 255, 255, 0.9), Border radius: 12px, Padding: 10px vertical, 12px horizontal. Shadow: rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255, 255, 255, 0.8) -1px -1px 1px 0px inset, rgb(255, 255, 255) 1px 1px 1px 0px inset, rgba(221, 223, 228, 0.5) 5px 5px 24px 0px. Features a soft, inward/outward shadow for subtle depth.

### Input Field
**Role:** Standard user input fields.

Background: transparent, Text: rgba(0, 0, 0, 0.88), Border radius: 6px, Border: 1px solid rgba(0, 0, 0, 0.88), Padding: 4px vertical, 11px horizontal. A dark, solid border gives clear definition.

### Elevated Card (Large Padding)
**Role:** Prominent content card, often for hero content or key features.

Background: rgba(255, 255, 255, 0.9), Border radius: 20px, Padding: 16px. Shadow: rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255, 255, 255, 0.8) -1px -1px 1px 0px inset, rgb(255, 255, 255) 1px 1px 1px 0px inset, rgba(221, 223, 228, 0.5) 5px 5px 24px 0px. Features more rounded corners and generous padding.

## Do's and Don'ts

### Do
- Use Labil Grotesk (or Inter) weight 400 at 16px with line height 1.57 and -0.01em letter spacing for all body copy to maintain legibility and a compact feel.
- Apply Canvas White #ffffff as the default background for the main canvas and most card surfaces.
- Reserve Action Orange #ff5c3c for primary call-to-action buttons and critical interactive elements, ensuring high visibility.
- Utilize a soft, subtle 'neuromorphic' shadow effect from rgba(221, 223, 228, 0.5) 5px 5px 24px 0px for cards and elevated components, paired with inset highlights for depth.
- Employ consistent 8px border radius for all buttons and input fields, with cards using 12px or 20px for a softer, more approachable aesthetic.
- Maintain a clear vertical rhythm using 24px spacing below secondary elements and 12px padding within cards.
- Use Attila-Bold (or Archivo Black) for headlines, especially at 48px with -0.02em letter spacing, to create a strong, condensed visual impact.

### Don't
- Avoid using highly saturated colors outside the defined brand and accent palette; maintain a largely achromatic UI.
- Do not use sharp, square corners on interactive elements; all buttons, inputs, and cards should have a minimum of 8px border radius.
- Refrain from dense text blocks without sufficient line height; ensure body text maintains a line height of 1.57 for readability.
- Do not introduce strong, dark shadows without the complementary light inset shadows; the visual system relies on a subtle, luminous depth.
- Avoid large variations in text letter spacing other than the defined tight values; excessive spacing breaks the compact typographic style.
- Do not use generic system fonts for prominent text; stick to Labil Grotesk or its substitutes for brand consistency.
- Do not add additional decorative borders or heavy outlines to elements; surfaces gain definition through subtle shadows and internal highlights.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Default page background. |
| 1 | Default Card Surface | `#ffffffe6` | Main content cards, slightly translucent. |
| 2 | Subtle Elevated Surface | `#f8f6f2` | Background for secondary sections or subtly elevated container groups. |

## Elevation

- **Card:** `rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255, 255, 255, 0.8) -1px -1px 1px 0px inset, rgb(255, 255, 255) 1px 1px 1px 0px inset, rgba(221, 223, 228, 0.5) 5px 5px 24px 0px`
- **Elevated Other:** `rgba(134, 137, 141, 0.2) 0px 0px 40px 0px`
- **Card (Accent Shadow):** `rgba(239, 227, 225, 0.3) 5px 5px 24px 0px`
- **Button:** `rgba(0, 0, 0, 0.02) 0px 2px 0px 0px`

## Imagery

The visual language for imagery is a mix of product illustrations and abstract, gradient-infused graphics. Illustrations are flat, often depicting stylized people interacting with UI elements, using a limited color palette that aligns with brand accents. Abstract graphics feature soft gradients (like Lavender Sky and Sunset Blush) that provide depth and a dreamy, digital feel without being overly complex. Icons are simple, outlined, often in black or a muted gray to maintain the clean UI. Imagery serves a decorative and explanatory role, providing context for the AI features and creating an inviting, modern atmosphere. Content is focused, with imagery often contained within cards or as background washes, rather than full-bleed photography. Density is balanced, with imagery breaking up text-heavy sections rather than dominating the page.

## Layout

The page primarily uses a max-width contained layout, likely around 1200px, centered on the screen. The hero section often features a large, centered headline paired with a call-to-action and either an abstract gradient background or a product illustration. Section rhythm is driven by consistent vertical spacing, with a calculated section gap around 120px. Content is often arranged in symmetrical stacks or 2-column layouts for text and visuals, and recurring 3-column card grids for features. Components within sections follow a comfortable density with 8px element gaps. The navigation is a typical top bar, fixed or sticky, with the brand logo, navigation links, and primary action buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #1f2026
- background: #ffffff
- border: #e8e8ea
- accent: #ff5c3c
- primary action: #ff5c3c (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff5c3c background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Default Card with soft shadow. Headline 'AI Sourcing agents' using Attila-Bold, weight 400, 24px, #1f2026, letter-spacing -0.24px. Body text 'Automate sourcing, fulfillment...' using Labil Grotesk, weight 400, 15px, #6b6b6b, line-height 1.57. Bottom-aligned text link 'Learn more' using Labil Grotesk, weight 400, 14px, #141414.
3. Build an input field: Input Field component. Placeholder text 'e.g. Can you' in Slate Text (#6b6b6b), Labil Grotesk, weight 400, 16px. Border #e8e8ea. Background Canvas White. Right-aligned submit icon (use a neutral icon color like #1f2026) in a circular button with Canvas White background.

## Similar Brands

- **Stripe** — Clean white backgrounds with a single strong accent color (blue for Stripe, orange for Pietra) and subtle, rounded UI elements.
- **Cal.com** — Soft, 'neuromorphic' shadows on cards and subtle background gradients, paired with modern sans-serif typography.
- **Rive** — Focus on product illustrations embedded in UI, with a vibrant color palette used for specific functional accents against a predominantly light background.
- **Supabase** — Minimalist layout, strong use of a single-color branding, and precise geometric typography for headings.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-stone-grey: #f8f6f2;
  --color-midnight-ink: #1f2026;
  --color-ink-wash: #141414;
  --color-slate-text: #6b6b6b;
  --color-silver-link: #c4c4c4;
  --color-input-border-gray: #e8e8ea;
  --color-action-orange: #ff5c3c;
  --color-slightly-yellowed: #fffbe7;
  --color-amber-dot: #f9e070;
  --color-forest-green: #57ad6a;
  --color-lavender-sky-gradient: #7d32f7;
  --gradient-lavender-sky-gradient: radial-gradient(127.58% 127.5% at 25.04% 20.84%, rgb(83, 90, 255) 0%, rgb(125, 51, 247) 100%);
  --color-sunset-blush-gradient: #e9aa4b;
  --gradient-sunset-blush-gradient: linear-gradient(43deg, rgb(255, 74, 74) 26.92%, rgb(233, 170, 75) 77.91%);
  --color-ocean-bloom-gradient: #4865ff;
  --gradient-ocean-bloom-gradient: radial-gradient(208.48% 182.32% at -0.04% -0.23%, rgb(65, 175, 255) 0%, rgb(72, 101, 255) 100%);
  --color-emerald-coast-gradient: #32cb8b;
  --gradient-emerald-coast-gradient: radial-gradient(213.37% 213.37% at 27.54% 0%, rgb(113, 206, 81) 0%, rgb(50, 203, 139) 100%);
  --color-orchid-haze-gradient: #f732ef;
  --gradient-orchid-haze-gradient: radial-gradient(127.58% 127.5% at 25.04% 20.84%, rgb(200, 83, 255) 0%, rgb(247, 51, 239) 100%);
  --color-paper-tint-gradient: #fddfe3;
  --gradient-paper-tint-gradient: linear-gradient(43deg, rgb(249, 219, 219) 26.92%, rgb(253, 241, 223) 77.91%);

  /* Typography — Font Families */
  --font-labil-grotesk: 'Labil Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil-regular: 'Labil-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil-bold: 'Labil-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-attila-bold: 'Attila-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-attila-sans-uniform: 'Attila Sans Uniform', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.57;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.57;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.64px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.96px;
  --text-display-xl: 50px;
  --leading-display-xl: 1.2;
  --tracking-display-xl: -1px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-124: 124px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 120px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;
  --radius-largeelements: 20px;

  /* Shadows */
  --shadow-subtle: rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255, 255, 255, 0.8) -1px -1px 1px 0px inset, rgb(255, 255, 255) 1px 1px 1px 0px inset, rgba(221, 223, 228, 0.5) 5px 5px 24px 0px;
  --shadow-xl: rgba(134, 137, 141, 0.2) 0px 0px 40px 0px;
  --shadow-lg: rgba(239, 227, 225, 0.3) 5px 5px 24px 0px;
  --shadow-xl-2: rgba(133, 136, 140, 0.2) 0px 0px 40px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.02) 0px 2px 0px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-default-card-surface: #ffffffe6;
  --surface-subtle-elevated-surface: #f8f6f2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-stone-grey: #f8f6f2;
  --color-midnight-ink: #1f2026;
  --color-ink-wash: #141414;
  --color-slate-text: #6b6b6b;
  --color-silver-link: #c4c4c4;
  --color-input-border-gray: #e8e8ea;
  --color-action-orange: #ff5c3c;
  --color-slightly-yellowed: #fffbe7;
  --color-amber-dot: #f9e070;
  --color-forest-green: #57ad6a;
  --color-lavender-sky-gradient: #7d32f7;
  --color-sunset-blush-gradient: #e9aa4b;
  --color-ocean-bloom-gradient: #4865ff;
  --color-emerald-coast-gradient: #32cb8b;
  --color-orchid-haze-gradient: #f732ef;
  --color-paper-tint-gradient: #fddfe3;

  /* Typography */
  --font-labil-grotesk: 'Labil Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil-regular: 'Labil-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-labil-bold: 'Labil-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-attila-bold: 'Attila-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-attila-sans-uniform: 'Attila Sans Uniform', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.57;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.57;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.57;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.64px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.96px;
  --text-display-xl: 50px;
  --leading-display-xl: 1.2;
  --tracking-display-xl: -1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-124: 124px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;

  /* Shadows */
  --shadow-subtle: rgba(193, 194, 222, 0.2) 1px 1px 1px 0px inset, rgba(255, 255, 255, 0.8) -1px -1px 1px 0px inset, rgb(255, 255, 255) 1px 1px 1px 0px inset, rgba(221, 223, 228, 0.5) 5px 5px 24px 0px;
  --shadow-xl: rgba(134, 137, 141, 0.2) 0px 0px 40px 0px;
  --shadow-lg: rgba(239, 227, 225, 0.3) 5px 5px 24px 0px;
  --shadow-xl-2: rgba(133, 136, 140, 0.2) 0px 0px 40px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.02) 0px 2px 0px 0px;
}
```
