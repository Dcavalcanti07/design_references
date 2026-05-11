# Sonos — Style Reference
> Matte black and white studio backdrop. The design feels like a product photography studio, with stark contrasts and focused lighting. Surfaces are either stark white or deep black, with elements precisely placed.

**Theme:** light

Sonos's design is an exercise in measured minimalism, leveraging high contrast and precise spacing to create a cinematic and functional experience. The core aesthetic relies on a stark black and white palette, allowing content and product imagery to take center stage. Typography is unadorned, favoring legibility and directness, while subtle large radii on interactive elements introduce a soft touch to an otherwise sharp visual identity. This deliberate sparsity amplifies the perceived quality and focus on sound.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Primary text, buttons (inverted), iconography, interactive states, page backgrounds in feature sections. Establishes a bold and commanding presence. |
| Studio White | `#ffffff` | `--color-studio-white` | Page backgrounds, card surfaces, primary button background, inverted text. Provides a clean, expansive canvas. |
| Soft Gray | `#f5f5f5` | `--color-soft-gray` | Subtle background for specific sections, visually distinguishing content blocks without harsh boundaries. |
| Dark Detail | `#2e2e2` | `--color-dark-detail` | Secondary text, subtle accents on darker backgrounds. Offers a slightly softer contrast than Absolute Zero. |
| Pale Border | `#e0e0e0` | `--color-pale-border` | Subtle borders and separators, navigational element outlines. |
| Medium Gray Hint | `#cdcdcd` | `--color-medium-gray-hint` | Finer details like subtle borders or inactive element states. |
| Light Shadow | `#bfbfbf` | `--color-light-shadow` | Border color for certain interactive elements and subtle shadow effects. Adds minimal depth without visual weight. |
| Ghost Gray | `#737373` | `--color-ghost-gray` | Tertiary text, less prominent information, iconography where a softer appearance is desired. |
| Deep Shadow | `#5f5f5f` | `--color-deep-shadow` | Used sparingly for deeper shadow nuances on interactive components. |

## Tokens — Typography

### aktiv-grotesk — The sole typeface,aktiv-grotesk, provides a clean and highly legible foundation across all content. Its sans-serif neutrality ensures focus remains on the product and message, rather than typographic flair. The range of weights and sizes supports a clear visual hierarchy, from detailed body text to commanding headlines, without introducing decorative elements. · `--font-aktiv-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 13px, 14px, 16px, 18px, 21px, 32px, 40px, 48px, 64px, 72px, 96px
- **Line height:** 1.00, 1.20, 1.30, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** The sole typeface,aktiv-grotesk, provides a clean and highly legible foundation across all content. Its sans-serif neutrality ensures focus remains on the product and message, rather than typographic flair. The range of weights and sizes supports a clear visual hierarchy, from detailed body text to commanding headlines, without introducing decorative elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 21px | 1.4 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | — | `--text-heading` |
| heading-lg | 40px | 1.2 | — | `--text-heading-lg` |
| display | 48px | 1.2 | — | `--text-display` |
| display-lg | 64px | 1 | — | `--text-display-lg` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| global | 10px |
| buttons | 80px |
| navigators | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.627) 0px 0px 3px 0px inset, rgb(0, 0, 0) ...` | `--shadow-subtle` |
| lg | `rgba(0, 0, 0, 0.25) 0px 0px 24px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 80px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Icon Button - Ghost
**Role:** Interactive element

Transparent background `rgba(0, 0, 0, 0)`. Text color `rgb(0, 0, 0)`. No border. Perfectly round with `borderRadius: 50%`. No explicit padding, suggesting icon-only or minimal text via flexible content.

### Primary Button - Outlined Black
**Role:** Primary Call to Action

Transparent background `rgba(0, 0, 0, 0)`. Text color `rgb(0, 0, 0)`. Border `1px solid rgb(0, 0, 0)` (Absolute Zero). Pill-shaped with `borderRadius: 80px`. Padding: `16px` vertical, `48px` horizontal. Used for primary actions from light backgrounds.

### Primary Button - Outlined White
**Role:** Primary Call to Action

Transparent background `rgba(0, 0, 0, 0)`. Text color `rgb(255, 255, 255)` (Studio White). Border `1px solid rgb(255, 255, 255)` (Studio White). Pill-shaped with `borderRadius: 80px`. Padding: `16px` vertical, `48px` horizontal. Used for primary actions from dark backgrounds.

### Navigation Link - Ghost White
**Role:** Navigation/Secondary Action

Transparent background `rgba(0, 0, 0, 0)`. Text color `rgb(255, 255, 255)` (Studio White). No border. Pill-shaped with `borderRadius: 80px`. Zero padding, relying on inherited text spacing for clickable area. Used for navigation within dark sections.

### Product Container Card - Raw
**Role:** Image/Content Container

Transparent background `rgba(0, 0, 0, 0)`, no border or shadow, `borderRadius: 0px`. Used for flexible content areas, often containing images or text blocks without distinct visual framing.

### Feature Card - Dark Full-Bleed
**Role:** Prominent Feature Display

Solid `rgb(0, 0, 0)` (Absolute Zero) background, no border or shadow, `borderRadius: 0px`. Generous vertical padding (`224px top/bottom`) creates a prominent section. Used for high-impact feature presentations.

### Information Card - Light Background
**Role:** Informational Content Block

Soft gray `rgb(244, 244, 244)` (Soft Gray via CSS tokens) background, no border or shadow, `borderRadius: 0px`. Features `24px` top padding and `80px` bottom padding. Used for general informational content, creating a subtle break from the main white background.

### Navigation Menu
**Role:** Global Navigation

Top-bar navigation, dynamically light or dark depending on background. Max-width `1440px`. Features `aktiv-grotesk` font at `14px` weight `400` for links. Interactive elements have `80px` or `9999px` border radius when active.

## Do's and Don'ts

### Do
- Prioritize high contrast between text (#000000, #ffffff) and background colors to ensure maximum readability and visual impact.
- Utilize `aktiv-grotesk` exclusively across all content, varying only weight and size to establish clear typographic hierarchy.
- Apply `80px` or `9999px` `borderRadius` to all primary interactive elements like buttons to maintain the signature pill-like shape.
- Use `16px` for vertical spacing between most content blocks and elements, with `48px` as the horizontal padding for buttons to maintain consistent 'comfortable' density.
- Confine body text and core content within a `1440px` `pageMaxWidth` to ensure optimal reading width and a structured layout.
- Implement `Studio White` (#ffffff) as the default page background and `Absolute Zero` (#000000) for text, inverting these for high-impact full-bleed dark sections.

### Don't
- Avoid introducing any additional fonts or decorative typography; maintain `aktiv-grotesk` for all text.
- Do not use subtle changes in color for emphasis; rely on high contrast between `Absolute Zero` and `Studio White` or `Soft Gray` for visual differentiation.
- Refrain from using complex shadow effects; stick to the sparse, minimal drops detected, focusing on flat design with strong color separation.
- Do not deviate from the `80px` or `9999px` radius for interactive elements, as this is a strong brand identifier.
- Avoid breaking content out of the `1440px` `pageMaxWidth` unless it is a full-bleed visual section designed for immersive impact.
- Do not introduce highly saturated or vibrant colors unless they are specific, approved branding elements not present in the current palette, as the system relies on achromatic contrast.

## Elevation

- **Button Focus/Hover:** `rgba(0, 0, 0, 0.627) 0px 0px 3px 0px inset, rgb(0, 0, 0) 0px 0px 3px 0px`
- **Interactive Element Shadow:** `rgba(0, 0, 0, 0.25) 0px 0px 24px 0px`

## Imagery

Imagery is high-quality, product-focused photography and lifestyle shots often deeply integrated into the background. Products are frequently displayed within domestic settings, but without distracting elements, maintaining a clean, aspirational feel. Photography is often desaturated or has a muted, natural color palette, allowing the product itself to stand out. Some sections feature abstract album cover-style graphics, generally in toned-down hues, creating a digital catalog aesthetic. Visuals are typically full-bleed or large, contained within simple geometric shapes (often rectangles). Icons are minimal, outlined, and monochromatic, matching the overall sleek simplicity.

## Layout

The layout is primarily a max-width, center-aligned container at `1440px`, but frequently breaks into full-bleed sections for hero imagery or prominent content blocks. The hero section often features a dark, full-bleed background image with centered, large white text and two prominent pill-shaped CTA buttons. Section rhythm alternates between full-bleed dark sections and contained light sections. Content arrangement typically involves centered text blocks over imagery or a simple stack with generous vertical spacing, suggesting a focus on individual content pieces over densely packed information. Limited grid usage is observed for feature displays, with ample space between elements. Navigation is a sticky top bar, adapting its color scheme (black or white) to ensure contrast against the scrolling content.

## Agent Prompt Guide

### Quick Color Reference
- Text (dark): #000000
- Text (light): #ffffff
- Background (light): #ffffff
- Background (dark): #000000
- Secondary background: #f5f5f5
- Border (light): #e0e0e0

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed dark background with a high-quality product image. Headline 'El sistema de sonido para toda la casa' in aktiv-grotesk 72px, Studio White #ffffff, centered. Below, two pill buttons: 'Explorar Sonos Play' (outlined white, text white, 80px radius, 16px vertical/48px horizontal padding) and 'Explorar todo' (filled black, text white, 80px radius, 16px vertical/48px horizontal padding). Generous vertical spacing for headline and buttons.
2. Create an informational card with the text 'Descubre Sonos Play. Un imponente sonido estéreo con graves profundos en un formato fácil de transportar.'. Use Soft Gray #f5f5f5 background. Text in aktiv-grotesk 18px leading 1.4, Absolute Zero #000000. Include a primary button 'Obtener información' (outlined black, text black, 80px radius, 16px vertical/48px horizontal padding). Card has 24px top padding and 80px bottom padding. Ensure content is within the 1440px max-width wrapper.
3. Design a dark feature section: Absolute Zero #000000 background, full-bleed. Headline 'Descubre música nueva' in aktiv-grotesk 48px leading 1.2, Studio White #ffffff, left-aligned. Body text in aktiv-grotesk 16px leading 1.5, Studio White #ffffff, below headline. Include an outlined white button 'Obtener información' with text white, 80px radius, 16px vertical/48px horizontal padding.
4. Build a basic navigation link: 'Productos' in aktiv-grotesk 14px 400, Absolute Zero #000000. Hover state changes text color slightly darker or adds a subtle underline effect (if explicit hover colors/styles are found).

## Similar Brands

- **Apple** — Both brands utilize a similarly stark, high-contrast, often monochromatic aesthetic with a focus on product imagery against clean backgrounds and strong, simple typography.
- **Bang & Olufsen** — Shares the premium, minimalist feel and emphasis on product design, often using a limited color palette and sophisticated, modern typography.
- **Dyson** — Similar focus on presenting high-tech products with a clean, functional, and slightly futuristic visual language, often leveraging white and dark neutrals.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-studio-white: #ffffff;
  --color-soft-gray: #f5f5f5;
  --color-dark-detail: #2e2e2;
  --color-pale-border: #e0e0e0;
  --color-medium-gray-hint: #cdcdcd;
  --color-light-shadow: #bfbfbf;
  --color-ghost-gray: #737373;
  --color-deep-shadow: #5f5f5f;

  /* Typography — Font Families */
  --font-aktiv-grotesk: 'aktiv-grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1.2;
  --text-display-lg: 64px;
  --leading-display-lg: 1;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;
  --spacing-224: 224px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 80px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;
  --radius-full-3: 9999px;

  /* Named Radii */
  --radius-global: 10px;
  --radius-buttons: 80px;
  --radius-navigators: 20px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.627) 0px 0px 3px 0px inset, rgb(0, 0, 0) 0px 0px 3px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.25) 0px 0px 24px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-studio-white: #ffffff;
  --color-soft-gray: #f5f5f5;
  --color-dark-detail: #2e2e2;
  --color-pale-border: #e0e0e0;
  --color-medium-gray-hint: #cdcdcd;
  --color-light-shadow: #bfbfbf;
  --color-ghost-gray: #737373;
  --color-deep-shadow: #5f5f5f;

  /* Typography */
  --font-aktiv-grotesk: 'aktiv-grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1.2;
  --text-display-lg: 64px;
  --leading-display-lg: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;
  --radius-full-3: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.627) 0px 0px 3px 0px inset, rgb(0, 0, 0) 0px 0px 3px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.25) 0px 0px 24px 0px;
}
```
