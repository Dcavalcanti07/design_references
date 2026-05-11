# Podia — Style Reference
> Playful market stall atop soft-glowing white

**Theme:** light

Podia presents a vibrant digital market stall. Its visual system layers playful, organic shapes over a soft, almost glowing white canvas. Information is presented in distinct, elevated cards with rounded corners that hint at approachability, while typography maintains a friendly confidence. A palette of muted pastels and warm earth tones, punctuated by deep near-black text and accents, creates a welcoming and engaging product-focused environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#06040e` | `--color-ink-black` | Primary text, outline buttons, card borders, interactive elements |
| Deep Ocean | `#10242f` | `--color-deep-ocean` | Secondary text, solid buttons, card background transitions |
| Crystal Canvas | `#ffffff` | `--color-crystal-canvas` | Page backgrounds, prominent card surfaces, primary button text |
| Cloud Gray | `#e1edf2` | `--color-cloud-gray` | Light surface background, subtle button text, icon accents |
| Warm Sand | `#f5f5f5` | `--color-warm-sand` | Main page background, subtle elevated card backgrounds, link backgrounds |
| Sky Blue | `#a5c8d8` | `--color-sky-blue` | Feature card accents, decorative background shapes |
| Lavender Mist | `#cbb0eb` | `--color-lavender-mist` | Feature card accents, decorative background shapes, subtle card borders |
| Sunset Orange | `#e39a4d` | `--color-sunset-orange` | Feature card accents, decorative background shapes |
| Rich Plum | `#1f1738` | `--color-rich-plum` | Feature card backgrounds, secondary actionable contexts |
| Earthy Umber | `#452623` | `--color-earthy-umber` | Feature card backgrounds, decorative elements |
| Light Peach | `#f6ddc4` | `--color-light-peach` | Text for buttons and body copy on dark backgrounds, icon accents |

## Tokens — Typography

### StabilGrotesk — All text elements: headlines, body copy, navigation, and buttons. Its varied weights and negative letter-spacing for larger sizes contribute to a cohesive yet dynamic feel, avoiding a rigid grid. · `--font-stabilgrotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 11px, 12px, 16px, 18px, 20px, 22px, 24px, 36px, 40px, 60px
- **Line height:** 1.00
- **Letter spacing:** -1.8px, -1.2px, -1.08px, -0.72px, -0.66px, -0.6px, -0.54px, -0.48px, -0.36px, -0.33px
- **Role:** All text elements: headlines, body copy, navigation, and buttons. Its varied weights and negative letter-spacing for larger sizes contribute to a cohesive yet dynamic feel, avoiding a rigid grid.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | -0.33px | `--text-caption` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 18px | 1.4 | -0.54px | `--text-subheading` |
| heading-sm | 22px | 1.4 | -0.66px | `--text-heading-sm` |
| heading | 36px | 1.09 | -1.08px | `--text-heading` |
| display | 60px | 1 | -1.8px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 24px |
| cards | 56px |
| links | 8px |
| buttons | 16px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Primary Call to Action

Solid Ink Black (#06040e) background with Cloud Gray (#e1edf2) text. Features generous 16px vertical and 24px horizontal padding with a 14px border radius for a soft, inviting action. Used for 'Start your free trial' and 'Sign up free'.

### Secondary Filled Button
**Role:** Secondary Call to Action

Solid Deep Ocean (#10242f) background with Cloud Gray (#e1edf2) text. Has 10px vertical and 16px horizontal padding with an 8px border radius. Used for 'Learn more' actions.

### Outlined Button
**Role:** Tertiary action or alternative navigation emphasis

Transparent background with Ink Black (#06040e) text and a 1px Ink Black (#06040e) border. Features 10px vertical and 16px horizontal padding with an 8px border radius.

### Hero Feature Card - Sky Blue
**Role:** Primary feature showcase with distinct visual identity

Card with Sky Blue (#a5c8d8) background and Ink Black (#06040e) text content. Rounded corners at 56px radius to signify a soft, approachable container. No discernible padding beyond content flow.

### Hero Feature Card - Sunset Orange
**Role:** Primary feature showcase with distinct visual identity

Card with Sunset Orange (#e39a4d) background and Ink Black (#06040e) text content. Rounded corners at 56px radius. No discernible padding beyond content flow.

### Hero Feature Card - Lavender Mist
**Role:** Primary feature showcase with distinct visual identity

Card with Rich Plum (#1f1738) background and Light Peach (#f6ddc4) text content, with borders of Lavender Mist (#cbb0eb). Rounded corners at 56px radius. No discernible padding beyond content flow.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#06040e) for primary text and interactive outlines to maintain clarity and contrast.
- Use Crystal Canvas (#ffffff) or Warm Sand (#f5f5f5) as primary page and card backgrounds to establish a light, inviting base.
- Apply a 16px border radius to all interactive buttons for a consistent, soft touch.
- Employ the negative letter-spacing from StabilGrotesk for all headings and large text to achieve a modern, condensed appearance.
- Emphasize features using the distinct accent colors—Sky Blue (#a5c8d8), Sunset Orange (#e39a4d), and Lavender Mist (#cbb0eb)—for card backgrounds or decorative elements.
- Maintain an element gap of 16px and card padding of 16px to ensure comfortable information density.
- Utilize Ink Black (#06040e) as the background for primary call-to-action buttons, pairing it with Cloud Gray (#e1edf2) text for high contrast.

### Don't
- Avoid arbitrary border radii; stick to 16px for buttons, 8px for links, and 56px for prominent cards.
- Do not introduce strong, saturated colors unless they are one of the defined accent colors for feature emphasis.
- Do not use generic system fonts; StabilGrotesk is essential for maintaining the brand's typographic personality.
- Avoid heavy shadows or gradients; rely on distinct background colors and rounded corners for visual separation and depth.
- Do not stray from the defined spacing values of 16px for elements and cards, or 40px for section gaps.
- Do not use highly chromatic colors for primary body text; keep body copy in Ink Black (#06040e) or Deep Ocean (#10242f).
- Avoid using Light Peach (#f6ddc4) for backgrounds; its primary role is text on dark surfaces or icon accents.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Base Canvas | `#f5f5f5` | Primary page background. |
| 1 | Card Surface | `#ffffff` | Prominent surface for cards, banners, and primary content blocks. |
| 2 | Tertiary Surface | `#e1edf2` | Subtle background shifts, elevated section backgrounds. |

## Imagery

This site uses a mix of light, candid lifestyle photography, abstract geometric shapes, and stylized product illustrations. Photography focuses on diverse individuals with a slightly desaturated, natural tone, often cropped to a circular or organic shape. Illustrations are flat, two-dimensional, and utilize the brand's accent colors, serving as explanatory content or decorative atmosphere. Product screenshots are typically nested within abstract card designs. Icons are outlined, lightweight, and monochrome, often accompanying text for clarity. The overall density is balanced, with imagery often contained within specific card structures or as floating background graphics, complementing the UI rather than dominating it.

## Layout

The page uses a maximum width containment for most content at the top, then transitions to a full-bleed layout for sections with larger cards and background elements, often with implicit centered content. The hero section features a prominent centered headline over a light background with floating, abstract shapes. Sections follow a rhythm of consistent vertical spacing, often with alternating light and slightly darker gray bands, utilizing card grids for feature showcases (typically three columns, but also two). Content often follows a text-left/image-right or image-left/text-right pattern. The primary navigation is a sticky top bar with minimal links and a clear 'Sign up free' button.

## Agent Prompt Guide

Quick Color Reference:
text: #06040e
background: #f5f5f5
border: #06040e
accent: #a5c8d8
primary action: #10242f (filled action)

Example Component Prompts:
1. Create a hero section with a large headline: use 'StabilGrotesk' weight 700 at 60px, Ink Black (#06040e), letter-spacing -1.8px. Place it above a Deep Ocean (#10242f) filled button with Cloud Gray (#e1edf2) text, 14px radius, 16px vertical padding, 24px horizontal padding.
2. Design a feature card with a Sky Blue (#a5c8d8) background: use 'StabilGrotesk' weight 500 at 22px, Ink Black (#06040e), letter-spacing -0.66px for the title. Ensure a 56px border radius.
3. Build a navigation link: 'StabilGrotesk' weight 400 at 16px, Ink Black (#06040e), with an 8px border radius, and 10px vertical and 16px horizontal padding. The link should transition opacity on hover.
4. Produce a secondary action button: Deep Ocean (#10242f) background, Cloud Gray (#e1edf2) text, 8px border radius, 10px vertical and 16px horizontal padding. Text 'StabilGrotesk' weight 400 at 16px, letter-spacing -0.48px.

## Similar Brands

- **ConvertKit** — Uses a clean, light aesthetic with a focus on creators, employing soft colors and clear typography for its SaaS product.
- **Teachable** — Features a light, inviting color palette and card-based layouts for showcasing courses and creator content, similar to Podia's product-focused approach.
- **Carrd** — Employs a minimalist design with a heavy reliance on distinct content blocks and a clean, spacious layout, often using muted accent colors.
- **CreatorKit** — Similar focus on creator tools with a cheerful, approachable design, using rounded elements and a non-intrusive color palette to highlight features.
- **Stripe** — While more professional, Stripe's use of clean surfaces, thoughtful typography, and subtle color accents for functional elements shares a common design philosophy of clarity and product-centricity with Podia.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #06040e;
  --color-deep-ocean: #10242f;
  --color-crystal-canvas: #ffffff;
  --color-cloud-gray: #e1edf2;
  --color-warm-sand: #f5f5f5;
  --color-sky-blue: #a5c8d8;
  --color-lavender-mist: #cbb0eb;
  --color-sunset-orange: #e39a4d;
  --color-rich-plum: #1f1738;
  --color-earthy-umber: #452623;
  --color-light-peach: #f6ddc4;

  /* Typography — Font Families */
  --font-stabilgrotesk: 'StabilGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.33px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.54px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.66px;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --tracking-heading: -1.08px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 56px;

  /* Named Radii */
  --radius-misc: 24px;
  --radius-cards: 56px;
  --radius-links: 8px;
  --radius-buttons: 16px;

  /* Surfaces */
  --surface-base-canvas: #f5f5f5;
  --surface-card-surface: #ffffff;
  --surface-tertiary-surface: #e1edf2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #06040e;
  --color-deep-ocean: #10242f;
  --color-crystal-canvas: #ffffff;
  --color-cloud-gray: #e1edf2;
  --color-warm-sand: #f5f5f5;
  --color-sky-blue: #a5c8d8;
  --color-lavender-mist: #cbb0eb;
  --color-sunset-orange: #e39a4d;
  --color-rich-plum: #1f1738;
  --color-earthy-umber: #452623;
  --color-light-peach: #f6ddc4;

  /* Typography */
  --font-stabilgrotesk: 'StabilGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.33px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.54px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.66px;
  --text-heading: 36px;
  --leading-heading: 1.09;
  --tracking-heading: -1.08px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 56px;
}
```
