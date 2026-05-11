# Sandland Sleep — Style Reference
> Calm twilight, soft edges

**Theme:** light

Sandland Sleep uses a calm, naturalistic visual language designed to evoke tranquility and trust, combining soft, muted backgrounds with clear, legible typography. A dominant dark navy provides a sense of depth and authority, contrasted by a sunny yellow for key calls to action, creating gentle visual punctuation. Surfaces are largely soft-edged cards with subtle elevation, promoting a friendly and approachable feel while maintaining a clean, digital aesthetic. The overall theme is understated and clean, minimizing distractions to focus on clarity and product presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1a365d` | `--color-midnight-ink` | Primary brand color for hero backgrounds, card surfaces, and key icons—establishes a sense of calm and depth |
| Amber Glow | `#fae467` | `--color-amber-glow` | Accent for primary call-to-action buttons, badges, and highlights—injects warmth and guides user attention |
| Scarlet Flash | `#a42325` | `--color-scarlet-flash` | Decorative accent primarily seen in subtle box-shadows, providing a hint of energy |
| Deepest Night | `#000000` | `--color-deepest-night` | Primary text color and significant UI elements like backgrounds and borders for high contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main background for cards, text, and interactive elements, providing a clean, bright foundation |
| Ghost Fog | `#f2ede8` | `--color-ghost-fog` | Background for outer page sections, providing a soft, almost imperceptible warmth to the canvas |
| Subtle Ash | `#e6e6e6` | `--color-subtle-ash` | Subtle borders and dividers, indicating structure without strong visual interruption |
| Stone Gray | `#666666` | `--color-stone-gray` | Muted text for secondary information, helper text, and subtle icon details |
| Pale Pebble | `#faf8f6` | `--color-pale-pebble` | Secondary card background, slightly off-white to create subtle layering |
| Slate Border | `#726f6d` | `--color-slate-border` | Standard input borders and placeholder text color |
| Dark Umbra | `#3d3d3d` | `--color-dark-umbra` | Text color for price points and other specific content areas, a softer alternative to pure black |
| Light Concrete | `#cbd5e0` | `--color-light-concrete` | Background for neutral, ghost buttons, providing a subtle interactive cue |

## Tokens — Typography

### Sandland-550 — Primary typeface for all headings and body text. Its subtle variations in letter spacing across sizes lend a bespoke feel, enhancing readability without drawing attention to the font itself. The regular weight (400) provides a clear, natural voice. · `--font-sandland-550`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 19px, 20px, 24px, 28px, 40px, 48px, 72px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.40, 1.60, 1.67
- **Letter spacing:** -0.0300em at display sizes, 0.0450em for small text, neutral otherwise
- **Role:** Primary typeface for all headings and body text. Its subtle variations in letter spacing across sizes lend a bespoke feel, enhancing readability without drawing attention to the font itself. The regular weight (400) provides a clear, natural voice.

### Inter — Secondary typeface, used sparingly for specific icons or technical annotations, providing a clean, accessible counterpoint. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 24px
- **Line height:** 1.10, 1.40
- **Letter spacing:** normal
- **Role:** Secondary typeface, used sparingly for specific icons or technical annotations, providing a clean, accessible counterpoint.

### GTStandard-M — Used for specific auxiliary informational text, adding a subtle touch of distinctiveness. · `--font-gtstandard-m`
- **Substitute:** Roboto
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used for specific auxiliary informational text, adding a subtle touch of distinctiveness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.45px | `--text-caption` |
| body | 15px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 40px | 1.1 | -0.3px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.3px | `--text-heading-lg` |
| display | 72px | 1 | -0.3px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| input | 0px |
| badges | 10px |
| buttons | 20px |
| circular-elements | 999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 4px 12px 0px` | `--shadow-md` |
| lg | `rgba(0, 0, 0, 0.1) 0px 4px 20px 0px` | `--shadow-lg` |
| subtle | `rgba(0, 0, 0, 0.13) 0px 1px 0px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 44px
- **Card padding:** 30px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with Amber Glow (#fae467) background, Deepest Night (#000000) text, 20px border radius, and generous 16px 24px padding.

### Ghost Outline Button
**Role:** Secondary action

Ghost button with Canvas White (#ffffff) background (90% opacity), Deepest Night (#000000) text, 999px border radius for pill shape, and 1px 6px padding. Used for minimal interactive elements like arrows or small controls.

### Neutral Button
**Role:** Tertiary action

Button with Light Concrete (#cbd5e0) background, Deepest Night (#000000) text, 999px border radius, and 1px 6px padding. Used for subdued interactive elements.

### Default Card
**Role:** Content container

Container with Canvas White (#ffffff) background (60% opacity), 10px border radius, and a subtle shadow rgba(0, 0, 0, 0.1) 0px 4px 12px 0px. Padding is 30px on all sides.

### Elevated Content Card
**Role:** Prominent content display

Container with pure Canvas White (#ffffff) background, 10px border radius, and a more pronounced shadow rgba(0, 0, 0, 0.1) 0px 4px 20px 0px. Padding is 40px on all sides.

### Dark Product Card
**Role:** Product information display

Card with Midnight Ink (#1a365d) background, 10px border radius, no shadow. Used for showcasing products with a distinct visual identity.

### Input Field
**Role:** User input

Transparent background, Slate Border (#726f6d) text and border bottom. Padding is 12px vertical, 0px horizontal. No border radius, relying on the underlying page structure.

### Bestseller Badge
**Role:** Highlight label

Amber Glow (#fae467) background, Deepest Night (#000000) text, 10px border radius, and 5px padding. Used for small, distinctive labels.

## Do's and Don'ts

### Do
- Use Ghost Fog (#f2ede8) as the canvas background for most page sections, occasionally using dark backgrounds like Midnight Ink (#1a365d) for hero or feature areas.
- Apply Deepest Night (#000000) for all primary text elements, ensuring high contrast and legibility.
- Utilize Sandland-550 for all typographic elements, leveraging its weight and letter-spacing variations for hierarchy rather than introducing new font families.
- Wrap interactive elements like buttons and badges in a 20px or 10px border radius, respectively, or 999px for pill-shaped elements.
- Make primary calls to action with a filled Amber Glow (#fae467) button, employing Deepest Night (#000000) for text.
- Maintain a comfortable density with an element gap of 8px and card padding of 30px, ensuring visual breathing room. Section gaps should be 44px.
- Use Subtle Ash (#e6e6e6) for hairline borders and separators to define content zones lightly.

### Don't
- Avoid using highly saturated colors outside of the Amber Glow (#fae467) accent for primary actions; keep the rest of the palette muted or neutral.
- Do not introduce additional font families beyond Sandland-550, Inter, and GTStandard-M; maintain typographic consistency.
- Refrain from using strong, opaque box shadows; stick to the light, soft shadows defined for cards.
- Do not deviate from the established border radii for components; maintain the consistent level of softness.
- Avoid arbitrary color variations for text or background elements; each color should serve a distinct semantic purpose.
- Do not create layouts that extend beyond the 1200px page max width, ensuring a contained and balanced presentation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#f2ede8` | Dominant background for the overall page structure. |
| 2 | Default Card Surface | `#ffffff` | Background for most content cards, providing a soft, slightly elevated context. |
| 3 | Elevated Card Surface | `#faf8f6` | Used for specific cards that require a subtle distinction from the default card, offering faint visual layering. |

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.1) 0px 4px 12px 0px`
- **Elevated Content Card:** `rgba(0, 0, 0, 0.1) 0px 4px 20px 0px`
- **Input Field Focus:** `rgba(0, 0, 0, 0.13) 0px 1px 0px 0px`

## Imagery

Imagery largely consists of tight product photography featuring sleep aid boxes, typically isolated on clean backgrounds or presented diagonally for a dynamic feel. Some illustrations are present, characterized by organic, flat shapes and brand-colored accents (like the blue sheep). Icons are generally outlined or filled with a moderate stroke weight, appearing as line art or simple glyphs, used functionally. The overall density of imagery is balanced, serving both decorative-atmospheric roles (hero section) and explanatory purposes (product display).

## Layout

The page maintains a max-width of 1200px, centered for readability and focus. The hero section features a full-width background with a centered, prominent headline and a Call-to-Action button over softly rendered product imagery. Content sections typically follow a consistent vertical rhythm with alternating background colors (Ghost Fog #f2ede8 and Canvas White #ffffff where cards overlay) and are separated by a section gap of 44px. Information is frequently arranged in a grid of 3-column cards, presenting products or features. Section headers are often centered and descriptive. Navigation is a sticky top bar with a left-aligned brand logo and right-aligned actions and links.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f2ede8
border: #e6e6e6
accent: #1a365d
primary action: #fae467 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #fae467 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Product Card for 'Stay Asleep' on a Default Card surface. The card should have a Canvas White (#ffffff) background, 10px radius, rgba(0, 0, 0, 0.1) 0px 4px 12px 0px shadow, and 30px padding. The product title 'Stay Asleep' should use Sandland-550, size 24px, weight 500, color Deepest Night (#000000).
3. Implement a 'Bestseller' Badge using Amber Glow (#fae467) background, Deepest Night (#000000) text, 10px radius, and 5px padding.

## Similar Brands

- **Oura Ring** — Similar focus on sleep and wellness, with a clean UI, subtle dark backgrounds for key sections, and understated typography.
- **Calm (app)** — Emphasizes a tranquil mood through soft color palettes and clear, uncluttered layouts for a soothing user experience.
- **Hims & Hers** — Direct-to-consumer health brand aesthetic with a combination of clean product shots and a focused, approachable UI.
- **Seed Health** — Modern health and wellness brand with a clean, scientific aesthetic, minimalist cards, and controlled use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1a365d;
  --color-amber-glow: #fae467;
  --color-scarlet-flash: #a42325;
  --color-deepest-night: #000000;
  --color-canvas-white: #ffffff;
  --color-ghost-fog: #f2ede8;
  --color-subtle-ash: #e6e6e6;
  --color-stone-gray: #666666;
  --color-pale-pebble: #faf8f6;
  --color-slate-border: #726f6d;
  --color-dark-umbra: #3d3d3d;
  --color-light-concrete: #cbd5e0;

  /* Typography — Font Families */
  --font-sandland-550: 'Sandland-550', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.45px;
  --text-body: 15px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.3px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.3px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.3px;

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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 44px;
  --card-padding: 30px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-input: 0px;
  --radius-badges: 10px;
  --radius-buttons: 20px;
  --radius-circular-elements: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 4px 12px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 4px 20px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.13) 0px 1px 0px 0px;

  /* Surfaces */
  --surface-page-canvas: #f2ede8;
  --surface-default-card-surface: #ffffff;
  --surface-elevated-card-surface: #faf8f6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1a365d;
  --color-amber-glow: #fae467;
  --color-scarlet-flash: #a42325;
  --color-deepest-night: #000000;
  --color-canvas-white: #ffffff;
  --color-ghost-fog: #f2ede8;
  --color-subtle-ash: #e6e6e6;
  --color-stone-gray: #666666;
  --color-pale-pebble: #faf8f6;
  --color-slate-border: #726f6d;
  --color-dark-umbra: #3d3d3d;
  --color-light-concrete: #cbd5e0;

  /* Typography */
  --font-sandland-550: 'Sandland-550', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.45px;
  --text-body: 15px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.3px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.3px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.3px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 4px 12px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 4px 20px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.13) 0px 1px 0px 0px;
}
```
