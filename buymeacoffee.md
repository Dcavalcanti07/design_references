# Buymeacoffee — Style Reference
> Warm, buoyant community canvas

**Theme:** light

Buy Me a Coffee embraces a friendly, tactile visual system that feels like a vibrant community space. Light, rounded cards with soft shadows float on a subtle off-white canvas, inviting interaction. A playful, energetic yellow serves as the primary brand accent, injecting warmth and positivity into calls to action and highlighted elements. Typography is clean and approachable, maintaining high readability with ample contrast, while bold headlines declare the brand's purpose with confidence but not aggression. The overall impression is one of supportive ease, much like a casual coffee shop interaction made digital.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#e5e7eb` | `--color-canvas` | Page backgrounds, subtle borders, dividers — a soft, almost imperceptible foundation |
| Surface | `#ffffff` | `--color-surface` | Card backgrounds, modal surfaces, primary content containers, button backgrounds for ghost or secondary actions |
| Deep Graphite | `#222222` | `--color-deep-graphite` | Primary text for headings and body content, offering strong contrast against light surfaces |
| Text Accent | `#717171` | `--color-text-accent` | Subtler text, secondary information, muted headings, and helper text |
| Rich Black | `#000000` | `--color-rich-black` | Highest contrast text, icons, and occasionally card backgrounds where absolute clarity is paramount |
| Goldenrod | `#ffdd00` | `--color-goldenrod` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Amber Glow | `#f7d046` | `--color-amber-glow` | Secondary brand accent, often seen on cards or subtly active background states |
| Sunset Coral | `#d8573f` | `--color-sunset-coral` | Orange outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Blush Tone | `#f5d5cf` | `--color-blush-tone` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |

## Tokens — Typography

### ui-sans-serif — ui-sans-serif — detected in extracted data but not described by AI · `--font-ui-sans-serif`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** ui-sans-serif — detected in extracted data but not described by AI

### Circular — Body text and general interface elements. The 400 weight is a confident, readable baseline. · `--font-circular`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 22px, 24px, 40px
- **Line height:** 1.20, 1.33, 1.50, 1.67
- **Letter spacing:** -0.42px at 10px, -0.47px at 14px, -0.56px at 16px, -0.68px at 24px
- **Role:** Body text and general interface elements. The 400 weight is a confident, readable baseline.

### Circular — Headlines and prominent text. The interplay of 64px and 96px with distinct letter-spacing creates gravitas without shouting. · `--font-circular`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 14px, 16px, 20px, 24px, 64px, 96px
- **Line height:** 0.99, 1.00, 1.17, 1.20, 1.25, 1.50
- **Letter spacing:** 0.19px at 14px, -0.6px at 24px, -1.6px at 64px, -2.4px at 96px
- **Role:** Headlines and prominent text. The interplay of 64px and 96px with distinct letter-spacing creates gravitas without shouting.

### Circular — Emphasized components, strong callouts, and occasionally bold headlines for high-impact statements. · `--font-circular`
- **Substitute:** system-ui, sans-serif
- **Weights:** 700
- **Sizes:** 14px, 16px, 20px, 24px, 64px, 96px
- **Line height:** 0.99, 1.00, 1.17, 1.20, 1.25, 1.50
- **Letter spacing:** 0.19px at 14px, -0.62px at 24px, -1.6px at 64px, -2.4px at 96px
- **Role:** Emphasized components, strong callouts, and occasionally bold headlines for high-impact statements.

### Circular — Powerful, condensed statements or short, impactful headlines. Rarely used, but effective when needed. · `--font-circular`
- **Substitute:** system-ui, sans-serif
- **Weights:** 900
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 22px, 24px, 40px
- **Line height:** 1.20, 1.33, 1.50, 1.67
- **Letter spacing:** -0.42px at 10px, -0.47px at 14px, -0.56px at 16px, -0.68px at 24px
- **Role:** Powerful, condensed statements or short, impactful headlines. Rarely used, but effective when needed.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.42px | `--text-caption` |
| body | 14px | 1.5 | -0.47px | `--text-body` |
| heading-sm | 22px | 1.2 | -0.68px | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.62px | `--text-heading` |
| heading-lg | 40px | 1.2 | -1.24px | `--text-heading-lg` |
| display | 64px | 1 | -1.6px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| links | 16px |
| images | 8px |
| inputs | 8px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.15) 0px 0px 2px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Support Card
**Role:** Informational display for creators, featuring a soft shadow and rounded corners.

Background: #ffffff, border-radius: 24px, box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 1.955px 0px, rgba(0, 0, 0, 0.04) 0px 7.821px 39.106px 0px, rgba(0, 0, 0, 0.05) 0px 1.955px 4.888px 0px, padding: 16px.

### Pill-shaped Creator Card
**Role:** Compact display for creators, often used in lists or carousels, with a strong pill-like radius.

Background: #ffffff, border-radius: 9999px, box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 3.859px 0px, rgba(0, 0, 0, 0.04) 0px 15.438px 77.189px 0px, rgba(0, 0, 0, 0.05) 0px 3.859px 9.649px 0px, padding: 0px.

### Marketing Feature Card
**Role:** Large, inviting card for presenting key features or sections, generous padding and soft radius.

Background: #ffffff, border-radius: 40px, box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 2.794px 0px, rgba(0, 0, 0, 0.04) 0px 11.174px 55.871px 0px, rgba(0, 0, 0, 0.05) 0px 2.794px 6.984px 0px, padding: 32px.

### Interactive Item Card
**Role:** Smaller card for interactive elements like input fields or message bubbles, with a subtle semantic background and no shadow.

Background: rgba(216, 87, 63, 0.05), border-radius: 8px, box-shadow: none, padding: 0px.

### Call-to-Action Button
**Role:** Primary action button, bright and inviting, commanding attention with its distinct color and rounded shape.

Background: #ffdd00, text color: #000000, border-radius: 9999px, minimal padding; text: Circular Book, font-size: 16px, line-height 1.5, letter-spacing normal.

### Semantic Action Button
**Role:** Action button used for support-related interactions, with a warm, desaturated red hue.

Background: #d8573f, text color: #ffffff, border-radius: 9999px, type: Circular Medium, 16px, letter-spacing -0.34px.

### Header Navigation Link
**Role:** Standard top navigation link for general information.

Text color: #222222, font: Circular Book, 16px, line-height 1.5, letter-spacing normal, no background, minimal padding.

## Do's and Don'ts

### Do
- Prioritize Canvas (#e5e7eb) for main page backgrounds and Surface (#ffffff) for card and container backgrounds.
- Use Goldenrod (#ffdd00) for all primary calls to action backgrounds to maintain brand recognition and visual hierarchy.
- Apply a 9999px border-radius to all buttons and small interactive elements to achieve a friendly, pill-like appearance.
- Utilize the subtle shadow style `rgba(0, 0, 0, 0.15) 0px 0px 2px 0px, rgba(0, 0, 0, 0.04) 0px 8px 40px 0px, rgba(0, 0, 0, 0.05) 0px 2px 5px 0px` for cards to give a comfortable lift without heaviness.
- Employ Deep Graphite (#222222) and Rich Black (#000000) for headlines and body text to ensure high contrast and readability on light surfaces.
- Maintain a clear vertical rhythm using 24px as the section gap and 16px as the element gap where applicable.
- Use 'Circular' font family for all text elements; prefer weights 400 and 500 for body and medium headlines, and bolder weights for impactful titles with specified negative letter-spacing.

### Don't
- Do not introduce strong, saturated background colors outside of brand or semantic accents.
- Avoid using sharp corners or radii smaller than 8px for cards or primary interactive elements.
- Do not deviate from the 'Circular' typeface for any text; do not substitute with system fonts unless explicitly specified for a fallback.
- Refrain from using complex, multi-color gradients; stick to solid color accents or very subtle background tints.
- Do not apply heavy or dark shadows; the subtle, light shadow style is integral to the brand's friendly feel.
- Do not use #e5e7eb as a primary text color against #ffffff or similar light backgrounds; it's reserved for background and subtle borders.
- Avoid using any other yellow shades for primary CTAs; Goldenrod (#ffdd00) is specific to this role.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Base | `#e5e7eb` | The foundational background for the entire page, providing a slight off-white anchor. |
| 2 | Primary Surface | `#ffffff` | Used for content cards, modals, and interactive elements, allowing text and UI to stand out clearly. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.15) 0px 0px 1.955px 0px, rgba(0, 0, 0, 0.04) 0px 7.821px 39.106px 0px, rgba(0, 0, 0, 0.05) 0px 1.955px 4.888px 0px`

## Imagery

The visual language features contained, white-background rectangles that simulate floating cards. These often house product screenshots or user-generated content, giving a glimpse into the platform's functionality and community. Avatar images are circular, reinforcing the soft, friendly aesthetic. Icons are primarily filled, using the brand's accent colors or dark neutrals, and have a moderate stroke weight if outlined, acting as small functional markers. Imagery primarily serves to illustrate real-world application and social proof, with a moderate density.

## Layout

The page uses a maximum width of 1200px, creating a contained, centered experience. The hero section features a prominent, centered headline over a white background, flanked by floating 'creator card' elements that break the grid subtly, suggesting a dynamic, community-driven platform. Content sections generally follow a vertical stacking pattern, with consistent vertical spacing. Text-heavy blocks alternate with visual elements like embedded screenshots within slightly elevated cards, creating a readable and inviting flow without complex grid structures.

## Agent Prompt Guide

Quick Color Reference:
text: #222222
background: #e5e7eb
border: #e5e7eb
accent: #ffdd00
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a creator support card: background Surface (#ffffff), border-radius 24px, apply the light card shadow, with primary text Deep Graphite (#222222) using Circular 400 at 16px, and secondary text Text Accent (#717171) Circular 400 at 14px.
3. Build a 'Support $3' button: background Sunset Coral (#d8573f), text Surface (#ffffff), border-radius 9999px, text 'Support $3' in Circular 500 weight, 16px size.
4. Construct a section heading: text Deep Graphite (#222222), font Circular 500 weight, 64px size, letter-spacing -1.6px, text 'Fund your creative work'. 

## Similar Brands

- **Patreon** — Creator-first platform with a focus on community and support, similar friendly and approachable UI.
- **Gumroad** — Empowers creators to sell digital products, sharing a similar focus on individual creator economic empowerment and clean aesthetics.
- **Stripe** — Clean, understated UI with functional accent colors on a largely monochromatic canvas, emphasizing clarity and efficiency.
- **Ghost** — Platform for independent publishers, featuring a clean, readable design with a focus on content creation and community.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #e5e7eb;
  --color-surface: #ffffff;
  --color-deep-graphite: #222222;
  --color-text-accent: #717171;
  --color-rich-black: #000000;
  --color-goldenrod: #ffdd00;
  --color-amber-glow: #f7d046;
  --color-sunset-coral: #d8573f;
  --color-blush-tone: #f5d5cf;

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-circular: 'Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.47px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.68px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.62px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.24px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-links: 16px;
  --radius-images: 8px;
  --radius-inputs: 8px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 0px 2px 0px, rgba(0, 0, 0, 0.04) 0px 8px 40px 0px, rgba(0, 0, 0, 0.05) 0px 2px 5px 0px;

  /* Surfaces */
  --surface-canvas-base: #e5e7eb;
  --surface-primary-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #e5e7eb;
  --color-surface: #ffffff;
  --color-deep-graphite: #222222;
  --color-text-accent: #717171;
  --color-rich-black: #000000;
  --color-goldenrod: #ffdd00;
  --color-amber-glow: #f7d046;
  --color-sunset-coral: #d8573f;
  --color-blush-tone: #f5d5cf;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-circular: 'Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.47px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.68px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.62px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.24px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 0px 2px 0px, rgba(0, 0, 0, 0.04) 0px 8px 40px 0px, rgba(0, 0, 0, 0.05) 0px 2px 5px 0px;
}
```
