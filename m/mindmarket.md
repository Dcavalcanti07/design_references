# MindMarket — Style Reference
> Organic illustrations on calm canvas

**Theme:** light

MindMarket utilizes a playful and inviting aesthetic, combining a calm, earthy neutral palette with vibrant, illustrative accents. The design system emphasizes approachable typography, generous spacing, and organic, rounded shapes to convey a friendly yet authoritative presence. Color is used sparingly for functional highlights and to punctuate sections with energetic, brand-aligned hues. Components feel lightweight, with emphasis on soft, large radii and minimal borders.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greige Canvas | `#f5f1e4` | `--color-greige-canvas` | Soft section background, alternate surface, and quiet card fill. Do not promote it to the primary CTA color |
| Midnight Graphite | `#2c2e2a` | `--color-midnight-graphite` | Primary text, headings, most iconography, borders for outlined elements — a deep, near-black that feels soft and modern |
| Clean White | `#ffffff` | `--color-clean-white` | Primary page canvas and white card surfaces. Do not promote it to the primary CTA color |
| Muted Stone | `#e0dbce` | `--color-muted-stone` | Subtle secondary backgrounds, default button states — a light, earthy gray |
| Darkest Night | `#000000` | `--color-darkest-night` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ash Whisper | `#80827f` | `--color-ash-whisper` | Muted body text, borders for ghost components |
| Light Steel | `#d5d5d4` | `--color-light-steel` | Subtle borders and dividers, especially in navigation |
| Market Green | `#8ed462` | `--color-market-green` | Accent color for borders, subtle background tints, and active states — represents growth and freshness |
| Vibrant Yellow | `#f5e211` | `--color-vibrant-yellow` | Illustrative accents, footer sections — adds a cheerful, energetic pop |
| Insight Blue | `#2ba0ff` | `--color-insight-blue` | Accent color for specific iconography, borders on select cards — indicates information and clarity |
| Action Red | `#ff705d` | `--color-action-red` | Accent color for specific iconography, borders on select cards, illustrative elements — evokes attention and dynamism |

## Tokens — Typography

### Inter — The primary typeface for all textual content, from headings to body copy and UI elements. Its clean, modern character, combined with subtle negative letter-spacing for display sizes, ensures legibility and a refined feel. Weight 500 is used for emphasis without being overly bold, maintaining the approachable tone. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 9px, 15px, 17px, 18px, 20px, 30px, 53px, 81px, 140px, 144px
- **Line height:** 0.95, 1.15, 1.20, 1.25, 1.50, 2.00
- **Letter spacing:** -0.0600em at largest sizes, -0.0400em at smaller heading sizes, normal at body text
- **Role:** The primary typeface for all textual content, from headings to body copy and UI elements. Its clean, modern character, combined with subtle negative letter-spacing for display sizes, ensures legibility and a refined feel. Weight 500 is used for emphasis without being overly bold, maintaining the approachable tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.5 | — | `--text-body-sm` |
| body-lg | 18px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | 30px | 1.25 | — | `--text-heading-sm` |
| heading | 53px | 1.25 | -0.04px | `--text-heading` |
| heading-lg | 81px | 1.15 | -0.06px | `--text-heading-lg` |
| display | 140px | 0.95 | -0.06px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 20 | 20px | `--spacing-20` |
| 60 | 60px | `--spacing-60` |
| 136 | 136px | `--spacing-136` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 63.75px |
| badges | 50px |
| inputs | 10px |
| buttons | 50px |
| containers | 25.5px |

### Layout

- **Section gap:** 85px
- **Card padding:** 21px
- **Element gap:** 21px

## Components

### Primary Ghost Button
**Role:** Interactive element

Text-only button with no background or border, using Midnight Graphite (#2c2e2a) text. Used for navigation links and secondary actions that don't require strong visual hierarchy.

### Quote Button
**Role:** Call to action

Rounded button with a 50px border-radius, background Greige Canvas (#f5f1e4) and text Midnight Graphite (#2c2e2a). Features a subtle border of Market Green (#8ed462) on active states. Padding 11px vertical, 17px horizontal.

### Navigation Menu Button
**Role:** UI control

A ghost button for menu toggling, featuring a prominent border-radius of 50px. Uses Midnight Graphite (#2c2e2a) for iconography. Text 'Get a quote' is in clean white, with a dark background.

### Rounded Info Card
**Role:** Content container

Card with a large 63.75px border-radius, background of Greige Canvas (#f5f1e4) and no visible shadow. Padding of 21px vertical and 42.5px horizontal (left starts at 21.25px). Borders can be dynamically colored with Brand Green, Insight Blue or Action Red like #8ed462, #2ba0ff, #ff705d.

### Section Highlight Card
**Role:** Content container

White background card with a 20px border-radius, used for emphasizing information blocks, like 'No more chaos.' content. Features an internal padding of 21px around content, with a primary call to action using Action Red (#ff705d) as text color.

### Feature Badge
**Role:** Informational label

Text in Midnight Graphite (#2c2e2a) on a transparent background, but with an inherent 50px border-radius to align with the rounded aesthetic. Padding is minimal at 6px. Used for concise attribute display.

## Do's and Don'ts

### Do
- Use Inter for all typography, maintaining a consistent brand voice across all content and UI elements.
- Prioritize Greige Canvas (#f5f1e4) and Clean White (#ffffff) for backgrounds and surfaces to maintain a light, airy feel.
- Apply a large border-radius of 63.75px to main content cards and 50px to buttons and badges for a soft, organic aesthetic.
- Utilize Midnight Graphite (#2c2e2a) for primary text and headings, ensuring high contrast against light backgrounds.
- Introduce brand colors—Market Green (#8ed462), Vibrant Yellow (#f5e211), Insight Blue (#2ba0ff), and Action Red (#ff705d)—as accents for borders, iconography, and illustrative elements, not as full background fills.
- Maintain generous padding of 21px for card content and a consistent 21px element gap to ensure comfortable readability and visual breathing room.
- Employ a subtle negative letter-spacing for larger headlines (e.g., -0.0600em at 144px, -0.0400em at 53px) to prevent them from feeling too open.

### Don't
- Avoid using harsh, saturated primary colors for large background areas; reserve them for accents and highlights.
- Do not use sharp corners or small border radii; maintain the soft, rounded aesthetic with values like 63.75px or 50px.
- Refrain from dense layouts; utilize the prescribed section (85px) and element (21px) gaps to ensure ample whitespace.
- Do not introduce new typefaces; rely solely on Inter to keep the typographic system cohesive.
- Avoid heavy shadows or gradients; the design emphasizes a flat and clean aesthetic, with only subtle borders and color shifts for depth.
- Do not use small, precise adjustments in spacing; stick to the established 4px grid and defined spacing tokens.
- Resist using a truly black background; opt for the deep Midnight Graphite (#2c2e2a) for dark elements to maintain softness.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Greige Canvas | `#f5f1e4` | Base page background and default large content areas |
| 1 | Clean White | `#ffffff` | Elevated card backgrounds and focused content blocks |

## Imagery

The visual language relies heavily on playful, organic illustrations featuring diverse, stylized characters in dynamic poses. These illustrations are dimensional, using a mix of solid brand colors (Market Green, Vibrant Yellow, Insight Blue, Action Red) and neutrals, often with organic, cloud-like elements or abstract shapes around them. Product context is minimal; the imagery serves to create a friendly, human-centric atmosphere rather than showcase specific tools. Icons are minimal, either outlined or filled in Midnight Graphite (#2c2e2a) or Clean White (#ffffff), maintaining a soft stroke weight. The imagery density is moderate, used strategically to break up text sections and add visual interest, often appearing partially off-screen.

## Layout

The page maintains a centered, contained layout with no explicit `pageMaxWidth` but generally respecting clear content boundaries, often surrounded by the Greige Canvas background. The hero section features a full-bleed Market Green (#8ed462) background with a large, centered headline and a supporting illustrative element. Sections alternate visually, often featuring different background colors or large illustrative elements that provide organic, curvilinear dividers between content blocks rather than sharp lines. Content is primarily arranged in two-column text and image layouts or centered stacks for stronger statements. Card grids for features are common, featuring large rounded cards. Navigation is a sticky top bar, providing persistent access to links and actions.

## Agent Prompt Guide

### Quick Color Reference
- text: #2c2e2a
- background: #f5f1e4
- border: #2c2e2a
- accent: #8ed462
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
- Create a hero section: Market Green (#8ed462) background. Headline 'Real human insights' using Inter at 81px, weight 400, #2c2e2a, letter-spacing -0.06. Subtext 'One global partner' using Inter at 20px, weight 400, #2c2e2a.
- Design a customer testimonial card: Rounded Info Card with a 63.75px radius, Greige Canvas (#f5f1e4) background, 21px padding. Body text 'MindMarket delivers global qualitative market research...' in Inter, 17px, weight 400, #2c2e2a. Add a 'Get a quote' button using text #2c2e2a, background #f5f1e4, 50px border-radius, 11px vertical, 17px horizontal padding.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Mailchimp** — Similar use of playful, organic illustrations and a clean interface with a distinctive brand accent color.
- **Webflow** — Employs a precise typographic system with Inter, combines neutrals with vibrant accent colors, and uses generous spacing.
- **Stripe** — Minimalist aesthetic with soft rounded edges, high contrast typography, and strategic use of a limited color palette for functional highlights.
- **Framer** — Focus on highly legible typography, subtle surface differentiation, and a preference for soft, rounded shapes over sharp ones.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greige-canvas: #f5f1e4;
  --color-midnight-graphite: #2c2e2a;
  --color-clean-white: #ffffff;
  --color-muted-stone: #e0dbce;
  --color-darkest-night: #000000;
  --color-ash-whisper: #80827f;
  --color-light-steel: #d5d5d4;
  --color-market-green: #8ed462;
  --color-vibrant-yellow: #f5e211;
  --color-insight-blue: #2ba0ff;
  --color-action-red: #ff705d;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.25;
  --text-heading: 53px;
  --leading-heading: 1.25;
  --tracking-heading: -0.04px;
  --text-heading-lg: 81px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.06px;
  --text-display: 140px;
  --leading-display: 0.95;
  --tracking-display: -0.06px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-136: 136px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 85px;
  --card-padding: 21px;
  --element-gap: 21px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 25.5px;
  --radius-full: 50px;
  --radius-full-2: 63.75px;

  /* Named Radii */
  --radius-cards: 63.75px;
  --radius-badges: 50px;
  --radius-inputs: 10px;
  --radius-buttons: 50px;
  --radius-containers: 25.5px;

  /* Surfaces */
  --surface-greige-canvas: #f5f1e4;
  --surface-clean-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greige-canvas: #f5f1e4;
  --color-midnight-graphite: #2c2e2a;
  --color-clean-white: #ffffff;
  --color-muted-stone: #e0dbce;
  --color-darkest-night: #000000;
  --color-ash-whisper: #80827f;
  --color-light-steel: #d5d5d4;
  --color-market-green: #8ed462;
  --color-vibrant-yellow: #f5e211;
  --color-insight-blue: #2ba0ff;
  --color-action-red: #ff705d;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.25;
  --text-heading: 53px;
  --leading-heading: 1.25;
  --tracking-heading: -0.04px;
  --text-heading-lg: 81px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.06px;
  --text-display: 140px;
  --leading-display: 0.95;
  --tracking-display: -0.06px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-136: 136px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 25.5px;
  --radius-full: 50px;
  --radius-full-2: 63.75px;
}
```
