# Fruitful — Style Reference
> Calm Financial Clarity

**Theme:** light

Fruitful projects a calm, approachable financial tech image through a clean white canvas, softened neutrals, and a prominent, vibrant green brand accent. Typography is modern and unembellished, emphasizing clarity and directness. Components are lightweight with generous rounded corners, conveying a friendly and trustworthy feel, while subtle shadows add minimal depth without heaviness. The overall impression is one of ease and quiet confidence in managing personal finance.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, card backgrounds, all base surfaces |
| Rich Black | `#000000` | `--color-rich-black` | Primary text, prominent headings, and strong borders |
| Subtle Ash | `#eceff4` | `--color-subtle-ash` | Subtle card backgrounds, navigation accents, very light surface differentiation |
| Cool Gray | `#5b616b` | `--color-cool-gray` | Secondary text, muted links, descriptive body copy |
| Deep Fern Green | `#0b7443` | `--color-deep-fern-green` | Primary action buttons, brand logo, active navigation indicators, link hover states — a grounding, trustworthy color |
| Leafy Green | `#61bc76` | `--color-leafy-green` | Decorative icons, light accents on cards, subtle approval indicators |
| Muted Sage | `#d1fadf` | `--color-muted-sage` | Light background wash for sections, subtle button backgrounds, navigation borders |
| Melon Tint | `#fee9d1` | `--color-melon-tint` | Background for feature cards, soft decorative panels, creating warmth |
| Terra Cotta | `#715039` | `--color-terra-cotta` | Muted secondary headings, financial figures, specific card text — provides a warm earthy contrast |
| Sky Mist | `#c7e0f8` | `--color-sky-mist` | Light button backgrounds, subtle hover states, providing a cool undertone |
| Light Peach | `#ffdcb4` | `--color-light-peach` | Light button backgrounds, subtle hover states |
| Mint Green Glow | `radial-gradient(circle, rgb(218, 237, 228), rgb(180, 208, 216))` | `--color-mint-green-glow` | Soft section background, alternate surface, and quiet card fill. Do not promote it to the primary CTA color |

## Tokens — Typography

### PP Neue Montreal — The sole typeface, used across all elements from large display headings to fine print. Its clean, geometric sans-serif form ensures modern readability and consistency. Variable letter-spacing helps optimize legibility across different sizes, from subtle tightening on display sizes to standard tracking for body text. Weight 400 is standard for body, 500 for semi-bold emphasis, and 600/700 for headlines. · `--font-pp-neue-montreal`
- **Substitute:** Inter, Arial, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 18px, 19px, 20px, 21px, 23px, 24px, 26px, 38px, 45px, 48px, 49px, 60px, 91px
- **Line height:** 1.2
- **Letter spacing:** -0.0190em, -0.0100em, -0.0040em
- **Role:** The sole typeface, used across all elements from large display headings to fine print. Its clean, geometric sans-serif form ensures modern readability and consistency. Variable letter-spacing helps optimize legibility across different sizes, from subtle tightening on display sizes to standard tracking for body text. Weight 400 is standard for body, 500 for semi-bold emphasis, and 600/700 for headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.32 | — | `--text-caption` |
| body-sm | 13px | 1.32 | — | `--text-body-sm` |
| body | 16px | 1.32 | — | `--text-body` |
| body-lg | 19px | 1.32 | — | `--text-body-lg` |
| heading-sm | 21px | 1.32 | — | `--text-heading-sm` |
| heading | 24px | 1.3 | — | `--text-heading` |
| heading-lg | 45px | 1.3 | — | `--text-heading-lg` |
| display-sm | 49px | 1.3 | — | `--text-display-sm` |
| display | 91px | 1.3 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 80px |
| images | 12px |
| inputs | 12px |
| buttons | 12px |
| general | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.05) 0px 25px 16px 0px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Section gap:** 48px
- **Card padding:** 48px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call to action button.

Filled with Deep Fern Green (#0b7443), white text, 12px border radius. Padding: 8px vertical, 20px horizontal. Uses PP Neue Montreal, 400 weight.

### Ghost Outline Button
**Role:** Secondary action or alternative call to action.

Transparent background, Cool Gray (#98a2b3) 1px border. Cool Gray (#98a2b3) text, 12px border radius. Padding: 7.55px vertical, 22.66px horizontal. Uses PP Neue Montreal, 400 weight.

### Muted Neutral Button
**Role:** Tertiary action or filter controls.

Subtle Ash (#eceff4) background, Rich Black (#000000) text, 12px border radius. Padding: 8px vertical, 20px horizontal. Uses PP Neue Montreal, 400 weight.

### Feature Card (Peach)
**Role:** Highlighting key features or interactive elements.

Melon Tint (#fee9d1) background, 12px border radius. No visible shadow or additional padding from specific variant data.

### Plain Content Card
**Role:** Standard content containers, often for text or simple UI groups.

Subtle Ash (#eceff4) background, 12px border radius. Padding: 20px vertical, 48px horizontal. No shadow.

### Elevated Marketing Card
**Role:** Promotional or high-impact content block requiring subtle depth.

Light Peach (#fef0c7) background, 10px border radius. Features a soft, layered shadow: rgba(0, 0, 0, 0.05) 0px 25px 16px 0px, rgba(0, 0, 0, 0.1) 0px 10px 10px 0px, rgba(0, 0, 0, 0.1) 0px 3px 6px 0px.

### Attribute Badge (White)
**Role:** Metadata tags for categorizing or describing items.

White text on a transparent background with 80px border radius and a 0.4 opacity white background (#f9fabb, 0.4). Padding: 5.66px in all directions. Uses PP Neue Montreal, 400 weight. (Example: '☀️ Cheerful').

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary backgrounds to maintain an expansive, clean feel.
- Use Deep Fern Green (#0b7443) exclusively for primary calls to action and critical brand accents.
- Reserve Rich Black (#000000) for all primary text and display headings, ensuring strong contrast.
- Apply 12px border radius for all interactive elements like buttons, cards, and images to ensure visual consistency.
- Maintain a comfortable information density using an 8px base unit, evidenced by frequent element gaps.
- Differentiate content blocks with subtle background tints like Subtle Ash (#eceff4) or Melon Tint (#fee9d1) rather than strong borders.

### Don't
- Avoid using multiple vivid colors; restrict the palette to the primary green and selected muted accents.
- Do not introduce strong, dark backgrounds unless clearly for a full-bleed hero section, as the theme is predominantly light.
- Do not use sharp corners; a minimum 12px radius should be present on most significant UI elements.
- Refrain from heavy, intense shadows; employ the light, layered shadow of the 'Elevated Marketing Card' for subtle depth only.
- Avoid generic system fonts; PP Neue Montreal is key to the brand's distinct typographic voice.
- Do not use dark text on dark backgrounds; ensure sufficient contrast (at least 7:1 for body text, 4.5:1 for large text) for all text elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Mint Green Glow | `#e1fdea` | Lightest section background, subtle differentiation |
| 2 | Subtle Ash | `#eceff4` | Card background, softer section backgrounds |
| 3 | Melon Tint | `#fee9d1` | Accent background for feature cards |

## Elevation

- **Marketing Card:** `rgba(0, 0, 0, 0.05) 0px 25px 16px 0px, rgba(0, 0, 0, 0.1) 0px 10px 10px 0px, rgba(0, 0, 0, 0.1) 0px 3px 6px 0px`

## Imagery

Minimal imagery focused primarily on product-related visuals and authentic human portraits. Photography of individuals (guides) is candid, well-lit, and appears within soft-edged card containers, usually with muted background colors like Melon Tint (#fee9d1). Visuals serve to explain services or introduce team members, not for decorative atmosphere. Icons are simple, outlined, and occasionally filled with brand colors like Leafy Green (#61bc76), maintaining a clean UI aesthetic. Visual density is low, making imagery feel deliberate and impactful when present.

## Layout

The page structure is max-width contained, with content centered. The hero section is full-width with a prominent, centered headline over a white background, followed by a video element with rounded corners. Subsequent sections alternate between white and subtle tinted backgrounds (e.g., Melon Tint, Subtle Ash), creating a rhythmic vertical flow. Content is often arranged in a two-column layout with text on one side and imagery/cards on the other, or in feature grids with a comfortable column count. Navigation is a sticky top bar with a clear primary action button on the right.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #d1fadf
accent: #0b7443
primary action: #0b7443 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: 'Get Started' text, filled with Deep Fern Green (#0b7443), white text, 12px radius, 8px vertical padding, 20px horizontal padding, PP Neue Montreal 400 weight.
2. Create a secondary ghost button: 'Learn More' text, transparent background, Cool Gray (#98a2b3) 1px border, Cool Gray (#98a2b3) text, 12px radius, 7.55px vertical padding, 22.66px horizontal padding, PP Neue Montreal 400 weight.
3. Design a feature card: Melon Tint (#fee9d1) background, 12px radius. Place a heading 'Smart Savings' in Rich Black (#000000), PP Neue Montreal 600 weight, and body text 'Automate your financial goals' in Cool Gray (#5b616b), PP Neue Montreal 400 weight. Use 20px top/bottom padding and 48px left/right padding.
4. Create a person card for a guide: Pale Peach (#fef0c7) background, 10px radius, with the specific layered shadow. Include a name 'Jane Doe' in Rich Black (#000000), PP Neue Montreal 500 weight, and a badge 'Collaborative' with white text on an 80px radius rgba(249, 250, 251, 0.4) background, 5.66px padding, PP Neue Montreal 400 weight.

## Type Scale

**role:** caption
**size:** 11
**lineHeight:** 1.33

**role:** body-sm
**size:** 14
**lineHeight:** 1.32

**role:** body
**size:** 16
**lineHeight:** 1.5

**role:** subheading
**size:** 20
**lineHeight:** 1.4

**role:** heading-sm
**size:** 24
**lineHeight:** 1.33

**role:** heading
**size:** 38
**lineHeight:** 1.25
**letterSpacing:** -0.48

**role:** heading-lg
**size:** 48
**lineHeight:** 1.1
**letterSpacing:** -0.91

**role:** display
**size:** 91
**lineHeight:** 0.9
**letterSpacing:** -1.73

## Similar Brands

- **Wealthfront** — Clean white backgrounds, strong sans-serif typography, and a prominent brand accent color for CTAs.
- **Betterment** — Minimalist UI, focus on clear information hierarchy, and soft, approachable aesthetics in financial services.
- **Mint** — Utilizes a balanced combination of functional UI with softer visual elements and a clear brand color.
- **Stripe** — Emphasis on modern, direct typography and a clean, almost monochrome base with thoughtful use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-rich-black: #000000;
  --color-subtle-ash: #eceff4;
  --color-cool-gray: #5b616b;
  --color-deep-fern-green: #0b7443;
  --color-leafy-green: #61bc76;
  --color-muted-sage: #d1fadf;
  --color-melon-tint: #fee9d1;
  --color-terra-cotta: #715039;
  --color-sky-mist: #c7e0f8;
  --color-light-peach: #ffdcb4;
  --color-mint-green-glow: #e1fdea;
  --gradient-mint-green-glow: radial-gradient(circle, rgb(218, 237, 228), rgb(180, 208, 216));

  /* Typography — Font Families */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.32;
  --text-body-sm: 13px;
  --leading-body-sm: 1.32;
  --text-body: 16px;
  --leading-body: 1.32;
  --text-body-lg: 19px;
  --leading-body-lg: 1.32;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.32;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 49px;
  --leading-display-sm: 1.3;
  --text-display: 91px;
  --leading-display: 1.3;

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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 48px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 80px;
  --radius-full-3: 100px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 80px;
  --radius-images: 12px;
  --radius-inputs: 12px;
  --radius-buttons: 12px;
  --radius-general: 12px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 25px 16px 0px, rgba(0, 0, 0, 0.1) 0px 10px 10px 0px, rgba(0, 0, 0, 0.1) 0px 3px 6px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-mint-green-glow: #e1fdea;
  --surface-subtle-ash: #eceff4;
  --surface-melon-tint: #fee9d1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-rich-black: #000000;
  --color-subtle-ash: #eceff4;
  --color-cool-gray: #5b616b;
  --color-deep-fern-green: #0b7443;
  --color-leafy-green: #61bc76;
  --color-muted-sage: #d1fadf;
  --color-melon-tint: #fee9d1;
  --color-terra-cotta: #715039;
  --color-sky-mist: #c7e0f8;
  --color-light-peach: #ffdcb4;
  --color-mint-green-glow: #e1fdea;

  /* Typography */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.32;
  --text-body-sm: 13px;
  --leading-body-sm: 1.32;
  --text-body: 16px;
  --leading-body: 1.32;
  --text-body-lg: 19px;
  --leading-body-lg: 1.32;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.32;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 49px;
  --leading-display-sm: 1.3;
  --text-display: 91px;
  --leading-display: 1.3;

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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 80px;
  --radius-full-3: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 25px 16px 0px, rgba(0, 0, 0, 0.1) 0px 10px 10px 0px, rgba(0, 0, 0, 0.1) 0px 3px 6px 0px;
}
```
