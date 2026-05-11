# Rivian — Style Reference
> Subtle Power, Precision Engineering.

**Theme:** light

This system evokes a sense of understated power and refined utility, much like the vehicles it represents. It balances a strong, nearly achromatic palette with crisp typography and subtle interactive accents. The aesthetic is anchored by deep blacks and bright whites, creating high contrast that feels purposeful rather than stark, while carefully articulated letter-spacing at larger type sizes adds a layer of precision. Rounded corners are reserved almost exclusively for interactive elements, softening points of engagement within an otherwise clean, angular visual language.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, interactive backgrounds, strong accents. |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, card surfaces, inverted text. |
| Slate Gray | `#151515` | `--color-slate-gray` | Secondary text, subtle background fills, borders. |
| Cloud Drifter | `#f2f2f2` | `--color-cloud-drifter` | Subtle background surfaces, hover states for neutrals. |
| Ash Concrete | `#e5e7eb` | `--color-ash-concrete` | Divider lines, subtle borders, background elements. |
| Dark Asphalt | `#212121` | `--color-dark-asphalt` | Input backgrounds, elevated background elements. |
| Chrome Accent | `#cfd0d0` | `--color-chrome-accent` | Subtle UI elements, non-semantic highlights. |
| Sunbeam Yellow | `#ffac00` | `--color-sunbeam-yellow` | Primary CTA background, active nav highlights — a burst of energy against the monochrome. |
| Forest Green | `#629b5c` | `--color-forest-green` | Secondary accent for specific interactive elements. |
| Desert Orange | `#e84826` | `--color-desert-orange` | Tertiary accent for specific interactive elements. |
| Ocean Blue | `#77afd8` | `--color-ocean-blue` | Quaternary accent for specific interactive elements. |
| Sapphire Glow | `#0066ff` | `--color-sapphire-glow` | Decorative illustration fill, subtle UI flourishes. |
| Vivid Green | `#7af400` | `--color-vivid-green` | Decorative illustration fill, subtle UI flourishes. |
| Dark Forrest Gradient | `linear-gradient(rgb(37, 40, 38), rgb(0, 0, 0))` | `--color-dark-forrest-gradient` | Background for hero sections, creating dramatic depth. |
| Horizon Fade Gradient | `linear-gradient(rgb(242, 242, 242) 0%, rgb(139, 168, 189) 100%)` | `--color-horizon-fade-gradient` | Section background, suggesting open sky or subtle elevation. |
| Abyss Blue Gradient | `linear-gradient(rgb(0, 0, 0) 0%, rgb(93, 118, 125) 100%)` | `--color-abyss-blue-gradient` | Deep background for impactful moments, conveying sophistication. |
| Success | `#4a8231` | `--color-success` | Semantic color for positive feedback. |
| Error | `#dc3127` | `--color-error` | Semantic color for critical feedback. |
| Warning | `#d58103` | `--color-warning` | Semantic color for cautionary notifications. |
| Info | `#005e7d` | `--color-info` | Semantic color for informational messages. |

## Tokens — Typography

### Adventure — The primary typeface for all content. Its range of weights and optical adjustments via letter-spacing at larger sizes ensure legibility and a distinct high-fidelity feel, from small captions to large display headings. The precise letter-spacing at display sizes creates a signature tight, technical aesthetic. · `--font-adventure`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 14px, 16px, 20px, 24px, 32px, 36px, 44px, 56px, 72px, 120px
- **Line height:** 0.93, 1.00, 1.07, 1.09, 1.11, 1.13, 1.14, 1.17, 1.20, 1.25, 1.33, 1.40, 1.43, 1.50, 1.55
- **Letter spacing:** -0.045em at 120px, -0.042em at 72px, -0.036em at 56px, -0.031em at 44px, -0.025em at 36px, -0.021em at 32px, -0.02em at 24px, -0.01em at 20px, otherwise normal
- **OpenType features:** `"clig" 0, "liga" 0, "ss01" 0`
- **Role:** The primary typeface for all content. Its range of weights and optical adjustments via letter-spacing at larger sizes ensure legibility and a distinct high-fidelity feel, from small captions to large display headings. The precise letter-spacing at display sizes creates a signature tight, technical aesthetic.

### Liga — Reserved for monumental display headings, likely large brand statements. The extreme size and specific letter-spacing create an impactful, almost structural visual element. · `--font-liga`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 360px
- **Line height:** 1.00
- **Letter spacing:** -0.022em
- **OpenType features:** `"clig", "liga", "ss01"`
- **Role:** Reserved for monumental display headings, likely large brand statements. The extreme size and specific letter-spacing create an impactful, almost structural visual element.

### Sohne — Used for specific utility or annotation text, possibly meta-information, offering a clean, unobtrusive presence at small sizes. · `--font-sohne`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Used for specific utility or annotation text, possibly meta-information, offering a clean, unobtrusive presence at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.55 | — | `--text-caption` |
| heading | 20px | 1.25 | -0.2px | `--text-heading` |
| heading-lg | 24px | 1.2 | -0.24px | `--text-heading-lg` |
| display | 32px | 1.17 | -0.672px | `--text-display` |
| display-lg | 36px | 1.14 | -0.9px | `--text-display-lg` |
| display-xl | 44px | 1.13 | -1.364px | `--text-display-xl` |
| display-xxl | 56px | 1.11 | -2.016px | `--text-display-xxl` |
| display-3xl | 72px | 1.09 | -3.024px | `--text-display-3xl` |
| display-4xl | 120px | 1.07 | -5.4px | `--text-display-4xl` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 4px |
| buttons | 40px |
| general | 8px |

### Layout

- **Section gap:** 24-48px
- **Card padding:** 0px
- **Element gap:** 4-28px

## Components

### Primary Filled Button - Arctic White
**Role:** Primary Call-to-Action

Button with `Arctic White` (#ffffff) background, `Midnight Ink` (#000000) text, `Ash Concrete` (#e5e7eb) border, 40px border radius, 8px vertical padding, 16px horizontal padding. Prominent and approachable.

### Primary Filled Button - Midnight Ink
**Role:** Inverted Primary Call-to-Action

Button with `Midnight Ink` (#000000) background, `Arctic White` (#ffffff) text, `Ash Concrete` (#e5e7eb) border, 40px border radius, 8px vertical padding, 16px horizontal padding. Used against lighter backgrounds for high contrast.

### Ghost Button - Arctic White
**Role:** Secondary Call-to-Action

Transparent background button with `Arctic White` (#ffffff) text, no visible border, 9999px border radius (pill shaped), 8px vertical padding, 12px horizontal padding. Subtle and contextual interaction.

### Ghost Button - Midnight Ink
**Role:** Secondary Call-to-Action on light backgrounds

Transparent background button with `Midnight Ink` (#000000) text, no visible border, 9999px border radius (pill shaped), 8px vertical padding, 12px horizontal padding. Subtle and contextual interaction.

### Link Button
**Role:** Tertiary Call-to-Action

Transparent background button with `Slate Gray` (#151515) text, no border radius (sharp), 12px vertical padding, 16px horizontal padding. Functions as a text link with button-like padding.

### Default Card
**Role:** Content Grouping

Card with transparent background, no border radius, no box shadow, no padding. Used for grouping content without adding additional visual weight.

### Login Input Field
**Role:** Data Entry

Input with `Dark Asphalt` (#212121) background, `Arctic White` (#ffffff) text, `Arctic White` (#ffffff) border, 4px border radius, 20px top padding, 16px horizontal padding, 0px bottom padding. Suggests a dark, secure input experience.

## Do's and Don'ts

### Do
- Prioritize 'Adventure' font for all text, applying specific letter-spacing for display sizes 20px and above, ensuring a precise, technical feel.
- Use `Midnight Ink` (#000000) for primary text on `Arctic White` (#ffffff) backgrounds, and `Arctic White` (#ffffff) text on `Midnight Ink` (#000000) backgrounds for maximum contrast and readability.
- Apply a 40px border radius to all primary and secondary buttons, crafting an approachable, modern form factor.
- Employ the `Sunbeam Yellow` (#ffac00) as the high-visibility accent color for primary call-to-action buttons, creating a deliberate focal point.
- Maintain minimal padding within cards (0px), allowing content to define its own space and emphasizing a clean, unadorned aesthetic.
- Utilize dark backgrounds like `Dark Forrest Gradient` or `Abyss Blue Gradient` for hero sections to create a premium, immersive brand introduction.
- Incorporate subtle, desaturated background colors like `Ash Concrete` (#e5e7eb) and `Cloud Drifter` (#f2f2f2) for section separation while maintaining visual lightness.

### Don't
- Do not use box-shadows for elevation; rely on color shifts between surfaces to indicate depth, maintaining a flat, modern impression.
- Avoid generic border radii; use the specified 40px for buttons and 4px for inputs, reserving other radii sparingly for specific elements.
- Do not introduce additional vibrant hues beyond the established accent colors (`Sunbeam Yellow`, `Forest Green`, `Desert Orange`, `Ocean Blue`), maintaining the sophisticated monochromatic base.
- Refrain from heavy text ornamentation like underlines or excessive bolding; the type scale and precise letter-spacing are sufficient for visual hierarchy.
- Do not use generic system fonts; 'Adventure' is critical for brand identity, with 'Liga' for monumental statements and 'Sohne' for microcopy.
- Do not use static header navigation on lighter body content; ensure it appears on a dark background or with an appropriate transparent overlay to match the brand aesthetic.
- Avoid cluttering card or section backgrounds with gradients – use them strategically for dramatic full-width hero or major content blocks only.

## Imagery

Photography is the dominant visual medium, featuring vehicles in both studio settings (tight product crops on white/gray gradients) and natural, outdoor environments (mountain roads, urban landscapes). The treatment emphasizes the vehicle as the primary subject, often full-bleed or large-scale, conveying capability and lifestyle without explicit human interaction. Photography is high-key in outdoor shots, showcasing clarity and detail, while studio shots lean towards dramatic lighting. Icons are minimal, outlined, and monochromatic, integrated subtly into the UI rather than serving as prominent visual elements.

## Layout

The page primarily uses a max-width contained layout, approximately 1200-1400px, centered on the screen. Hero sections are exceptions, often full-bleed with dramatic photography or large typography over gradient backgrounds, serving as impactful entry points. Content is typically arranged in balanced two-column layouts featuring text alongside visuals (vehicles), or stacked centered content blocks. Sections are clearly delineated by varied backgrounds (light gray, white, or dark gradients), often creating a subtle alternating rhythm down the page. Navigation is a sticky top bar with clear, minimalist links and distinct accent buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Midnight Ink)
- Background: #ffffff (Arctic White)
- CTA: #ffac00 (Sunbeam Yellow)
- Border: #e5e7eb (Ash Concrete)
- Accent: #ffac00 (Sunbeam Yellow)

### 3-5 Example Component Prompts
1. Create a hero section: full-width, background is `Dark Forrest Gradient` (linear-gradient(rgb(37, 40, 38), rgb(0, 0, 0))). Title 'Choose your own savings' using 'Adventure' font, size 56px, weight 500, #ffffff, letter-spacing -0.036em. Subtext 'For a limited time...' using 'Adventure' font, size 16px, weight 400, #ffffff. Add a 'Primary Filled Button - Arctic White' labeled 'View all offers'.
2. Design a navigation bar: `Arctic White` (#ffffff) background, with `Midnight Ink` (#000000) text for main links ('Vehicles', 'Charging'). Include a 'Primary Filled Button - Sunbeam Yellow' with text 'Demo drive', 'Adventure' font, size 14px, weight 600, 40px border radius, 8px vertical padding, 16px horizontal padding.
3. Implement a feature card: `Default Card` styling (transparent background, no shadow/radius/padding). Heading 'Meet R2' using 'Adventure' font, size 44px, weight 500, #000000, letter-spacing -0.031em. Body text 'Explore the lineup and reserve yours today.' using 'Adventure' font, size 20px, weight 400, #000000.
4. Create an input field: for login, use `Dark Asphalt` (#212121) background, `Arctic White` (#ffffff) text, `Arctic White` (#ffffff) border, 4px border radius, 20px top padding, 16px horizontal padding, 0px bottom padding. Placeholder text should be 'Adventure' font, size 16px, weight 400, #b8b8b8.

## Similar Brands

- **Tesla** — Shares a focus on clean, high-contrast UI with photography-driven hero sections and minimal use of decorative elements.
- **Lucid Motors** — Exhibits a similar premium automotive aesthetic, relying on large-scale vehicle imagery, sophisticated typography, and a restrained color palette.
- **Apple** — Uses large type, crisp product photography against clean backgrounds, and a focus on essential UI elements with subtle interactions.
- **Polestar** — Employs dark and light achromatic themes with striking vehicle visuals, tight typography, and a premium, engineered feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-arctic-white: #ffffff;
  --color-slate-gray: #151515;
  --color-cloud-drifter: #f2f2f2;
  --color-ash-concrete: #e5e7eb;
  --color-dark-asphalt: #212121;
  --color-chrome-accent: #cfd0d0;
  --color-sunbeam-yellow: #ffac00;
  --color-forest-green: #629b5c;
  --color-desert-orange: #e84826;
  --color-ocean-blue: #77afd8;
  --color-sapphire-glow: #0066ff;
  --color-vivid-green: #7af400;
  --color-dark-forrest-gradient: #252826;
  --gradient-dark-forrest-gradient: linear-gradient(rgb(37, 40, 38), rgb(0, 0, 0));
  --color-horizon-fade-gradient: #f2f2f2;
  --gradient-horizon-fade-gradient: linear-gradient(rgb(242, 242, 242) 0%, rgb(139, 168, 189) 100%);
  --color-abyss-blue-gradient: #000000;
  --gradient-abyss-blue-gradient: linear-gradient(rgb(0, 0, 0) 0%, rgb(93, 118, 125) 100%);
  --color-success: #4a8231;
  --color-error: #dc3127;
  --color-warning: #d58103;
  --color-info: #005e7d;

  /* Typography — Font Families */
  --font-adventure: 'Adventure', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-liga: 'Liga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.2px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 32px;
  --leading-display: 1.17;
  --tracking-display: -0.672px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.14;
  --tracking-display-lg: -0.9px;
  --text-display-xl: 44px;
  --leading-display-xl: 1.13;
  --tracking-display-xl: -1.364px;
  --text-display-xxl: 56px;
  --leading-display-xxl: 1.11;
  --tracking-display-xxl: -2.016px;
  --text-display-3xl: 72px;
  --leading-display-3xl: 1.09;
  --tracking-display-3xl: -3.024px;
  --text-display-4xl: 120px;
  --leading-display-4xl: 1.07;
  --tracking-display-4xl: -5.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 24-48px;
  --card-padding: 0px;
  --element-gap: 4-28px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 56px;
  --radius-full-2: 80px;
  --radius-full-3: 99px;
  --radius-full-4: 9999px;

  /* Named Radii */
  --radius-inputs: 4px;
  --radius-buttons: 40px;
  --radius-general: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-arctic-white: #ffffff;
  --color-slate-gray: #151515;
  --color-cloud-drifter: #f2f2f2;
  --color-ash-concrete: #e5e7eb;
  --color-dark-asphalt: #212121;
  --color-chrome-accent: #cfd0d0;
  --color-sunbeam-yellow: #ffac00;
  --color-forest-green: #629b5c;
  --color-desert-orange: #e84826;
  --color-ocean-blue: #77afd8;
  --color-sapphire-glow: #0066ff;
  --color-vivid-green: #7af400;
  --color-dark-forrest-gradient: #252826;
  --color-horizon-fade-gradient: #f2f2f2;
  --color-abyss-blue-gradient: #000000;
  --color-success: #4a8231;
  --color-error: #dc3127;
  --color-warning: #d58103;
  --color-info: #005e7d;

  /* Typography */
  --font-adventure: 'Adventure', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-liga: 'Liga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.2px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.24px;
  --text-display: 32px;
  --leading-display: 1.17;
  --tracking-display: -0.672px;
  --text-display-lg: 36px;
  --leading-display-lg: 1.14;
  --tracking-display-lg: -0.9px;
  --text-display-xl: 44px;
  --leading-display-xl: 1.13;
  --tracking-display-xl: -1.364px;
  --text-display-xxl: 56px;
  --leading-display-xxl: 1.11;
  --tracking-display-xxl: -2.016px;
  --text-display-3xl: 72px;
  --leading-display-3xl: 1.09;
  --tracking-display-3xl: -3.024px;
  --text-display-4xl: 120px;
  --leading-display-4xl: 1.07;
  --tracking-display-4xl: -5.4px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 56px;
  --radius-full-2: 80px;
  --radius-full-3: 99px;
  --radius-full-4: 9999px;
}
```
