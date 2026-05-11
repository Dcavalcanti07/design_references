# Mezmo — Style Reference
> Data-dense lavender precision

**Theme:** light

Mezmo crafts a sunlit, data-dense interface with a near-monochromatic palette accented by a singular, vivid lavender. The visual system balances complex information display with a light touch, utilizing crisp typography for clarity and soft shadows for subtle depth. Interactive elements are clearly defined through color and subtle elevation, while content sections maintain a clean, organized appearance with defined borders and generous internal spacing. The overall impression is one of approachable technical precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#0a090c` | `--color-inkwell` | Primary text, deep surface outlines, key UI accents, dark backgrounds for contrasting elements |
| Canvas | `#e6e6e5` | `--color-canvas` | Page background, section separators |
| Paper White | `#ffffff` | `--color-paper-white` | Card backgrounds, button fills, modal surfaces |
| Ash Gray | `#f4f4f4` | `--color-ash-gray` | Subtle background for UI elements, light surface fills |
| Steel Gray | `#c3c3c3` | `--color-steel-gray` | Shadow tints, muted borders, subtle dividers |
| Grout | `#d1d5db` | `--color-grout` | Hairline borders, subtle background tints, card separators |
| Charcoal | `#2d2d2d` | `--color-charcoal` | Dark badge backgrounds, sub-primary text |
| Twilight Lavender | `linear-gradient(90deg, rgba(117, 97, 177, 0.376), rgba(116, 169, 185, 0.376))` | `--color-twilight-lavender` | Emphatic borders for active states, selected items, decorative highlights, and significant content separators; Gradient for prominent background sections, creating a subtle visual anchor; Gradient used for background elements and subtle decorative effects |
| Cerulean Mist | `#96beca` | `--color-cerulean-mist` | Primary Call To Action button backgrounds, interactive elements |
| Subtle Teal | `#74a9b9` | `--color-subtle-teal` | Muted supporting text, contextual highlights, secondary information text |
| Radiant Yellow | `#f4b811` | `--color-radiant-yellow` | Yellow outline accent for tags, dividers, and focused UI edges |
| Calm Green | `#9db161` | `--color-calm-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Onest Variable — The primary typeface for all UI elements, headings, body text, and interactive components. Its variable nature allows for precise weight control, supporting a dense information display without visual clutter. The lighter weights are used for larger headings, creating a sophisticated tension against traditional bold headlines. · `--font-onest-variable`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 9px, 10px, 11px, 12px, 13px, 14px, 16px, 17px, 18px, 19px, 20px, 22px, 24px, 26px, 30px, 36px, 48px
- **Line height:** 1.00, 1.05, 1.13, 1.20, 1.23, 1.25, 1.33, 1.45, 1.50, 1.55
- **Letter spacing:** 0.0400em, 0.0600em, 0.1200em
- **Role:** The primary typeface for all UI elements, headings, body text, and interactive components. Its variable nature allows for precise weight control, supporting a dense information display without visual clutter. The lighter weights are used for larger headings, creating a sophisticated tension against traditional bold headlines.

### monospace — Dedicated to code snippets, data output, and technical explanations, providing clear demarcation from regular interface text. Its fixed-width nature ensures consistent alignment for structured information. · `--font-monospace`
- **Substitute:** SF Mono, Consolas
- **Weights:** 300, 500, 600
- **Sizes:** 9px, 10px, 11px, 12px
- **Line height:** 1.50
- **Letter spacing:** 0.0570em
- **Role:** Dedicated to code snippets, data output, and technical explanations, providing clear demarcation from regular interface text. Its fixed-width nature ensures consistent alignment for structured information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.04px | `--text-caption` |
| body | 14px | 1.5 | 0.04px | `--text-body` |
| subheading | 18px | 1.5 | 0.04px | `--text-subheading` |
| heading | 24px | 1.25 | 0.06px | `--text-heading` |
| heading-lg | 36px | 1.25 | 0.06px | `--text-heading-lg` |
| display | 48px | 1.05 | 0.12px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| input | 5px |
| badges | 4px |
| buttons | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.2) 0px 2px 5px 0px` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.2) 2px 2px 8px 0px` | `--shadow-sm-2` |
| sm-3 | `rgba(0, 0, 0, 0.2) 2px 2px 5px 0px` | `--shadow-sm-3` |
| sm-4 | `rgba(10, 9, 12, 0.04) 0px 1px 4px 0px` | `--shadow-sm-4` |
| subtle | `rgba(10, 9, 12, 0.03) 0px 1px 3px 0px` | `--shadow-subtle` |
| lg | `rgba(117, 97, 177, 0.063) 0px 4px 20px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call to action, interactive elements.

Background: Cerulean Mist (#96beca), Text: Inkwell (#031403), Border: Cerulean Mist (#96beca), Radius: 8px, Padding: 10px 20px.

### Ghost Button
**Role:** Secondary actions that need less emphasis.

Background: transparent, Text: Inkwell (#031403), Border: 1px Inkwell (#031403), Radius: 6px, Padding: 5.28px 12px.

### Text Link Button
**Role:** Inline actions or navigation without a distinct container.

Background: transparent, Text: Inkwell (#031403), Border: 1px Inkwell (#031403) at top, No radius, Padding: 5px 0px.

### Elevated Card
**Role:** Container for content that requires subtle prominence, e.g., features, testimonials.

Background: Paper White (#ffffff), Radius: 9px, Padding: 16px, Shadow: rgba(0, 0, 0, 0.2) 2px 2px 8px 0px.

### Subtle Elevated Card
**Role:** Secondary content cards, often within informational sections.

Background: Paper White (#ffffff), Radius: 16px, Padding: 16px, Shadow: rgba(10, 9, 12, 0.04) 0px 1px 4px 0px.

### Dark Overlay Card
**Role:** Cards used for specialized content, often within dark-themed sections or as overlays.

Background: Inkwell (#0a090c), Radius: 10px, No shadow, No padding.

### Default Badge
**Role:** Categorization, short descriptive labels.

Background: Ash Gray (#d8d8d6), Text: Charcoal (#404040), Radius: 4px, Padding: 4px 8px.

### Inverted Badge
**Role:** Contextual labels on dark backgrounds.

Background: Charcoal (#2d2d2d), Text: Paper White (#ffffff), Radius: 4px, Padding: 4px 8px.

## Do's and Don'ts

### Do
- Use Onest Variable weight 300 for headlines at sizes 36px and above, conveying authority through restraint.
- Prioritize Cerulean Mist (#96beca) for all primary call-to-action button backgrounds to ensure visual consistency.
- Apply Twilight Lavender (#7561b1) as a consistent accent for active states, selected items, and important content dividers.
- Ensure all input fields and interactive elements use a 5px border-radius, while cards use 8px or 16px for subtle variation.
- Utilize Inkwell (#0a090c) for primary text and surface outlines to establish a strong structural backbone.
- Maintain a clear visual hierarchy by employing soft shadows like rgba(0, 0, 0, 0.2) 2px 2px 8px 0px for elevated cards.
- Employ monospace font for all code snippets and technical data to distinguish it from standard UI text.

### Don't
- Do not introduce new saturated primary colors beyond Cerulean Mist (#96beca) and Twilight Lavender (#7561b1).
- Avoid using heavy, dark backgrounds for general content areas; maintain the light Canvas (#e6e6e5) or Paper White (#ffffff) as dominant surfaces.
- Do not apply excessive box-shadows; keep elevation subtle as per the defined shadow tokens.
- Do not use generic system fonts; always prefer Onest Variable for UI, and monospace for code.
- Avoid arbitrary letter-spacing; stick to the defined tighter letter-spacing for display text and normal for body text.
- Do not deviate from the established border radii; cards are 8px or 16px, buttons and inputs are 5-6px, badges are 4px.
- Do not use gradients for simple background fills; reserve them for prominent background sections or specific decorative elements to maintain impact.

## Imagery

This site predominantly uses internal UI components and data visualizations as its primary imagery. Where present, product screenshots are tightly cropped and often set against plain, light backgrounds. Iconography is primarily functional, minimal, and monochromatic, utilizing Inkwell (#0a090c) for filled states. The site is text-dominant, with visual elements serving to break up information and illustrate technical concepts rather than creating decorative atmosphere. There are subtle background gradients used for hero sections, which serve as atmospheric washes rather than containing rich imagery.

## Layout

The page adheres to a max-width contained layout, typically around 1200px, horizontally centered. The hero section is full-bleed, often featuring a subtle background gradient with a centered headline. Content sections follow a consistent vertical rhythm with defined spacing, typically alternating between text-left/visual-right patterns or centered stacks of information. Card grids are used for features, generally in 3-column arrangements. The navigation is a sticky header at the top, concise and functionally oriented. The layout density aims for clarity and scannability, balancing information-rich blocks with sufficient breathing room.

## Agent Prompt Guide

### Quick Color Reference
text: #0a090c
background: #e6e6e5
border: #d1d5db
accent: #7561b1
primary action: #96beca (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #96beca background, #0a090c text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design an Elevated Card for a feature: Paper White background (#ffffff), 9px radius, 16px padding. Text: 'Mezmo's Active Telemetry reduces millions of raw events into...' (Onest Variable, 14px, weight 400, #0a090c, lineHeight 1.5). Apply shadow rgba(0, 0, 0, 0.2) 2px 2px 8px 0px.
3. Implement a data metric display: Use Inkwell (#0a090c) for the label 'DEDUPLICATE', and Radiant Yellow (#f4b811) for the value '1.8M' (Onest Variable, 24px, weight 500, lineHeight 1.25, letter-spacing 0.06em). Include a Calm Green (#9db161) indicator text '↓ 68%' (Onest Variable, 12px, weight 400). All text on an Ash Gray (#f4f4f4) surface.
4. Build an Inverted Badge: Background Charcoal (#2d2d2d), text Paper White (#ffffff), 4px radius, 4px 8px padding, containing the text 'AURA' (Onest Variable, 12px, weight 500).
5. Create a technical documentation block: Canvas background (#e6e6e5). Code example box with Inkwell background (#0a090c), monospace font, 11px size, #ffffff color for code, line height 1.5, letter-spacing 0.057em.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #0a090c;
  --color-canvas: #e6e6e5;
  --color-paper-white: #ffffff;
  --color-ash-gray: #f4f4f4;
  --color-steel-gray: #c3c3c3;
  --color-grout: #d1d5db;
  --color-charcoal: #2d2d2d;
  --color-twilight-lavender: #7561b1;
  --gradient-twilight-lavender: linear-gradient(90deg, rgba(117, 97, 177, 0.376), rgba(116, 169, 185, 0.376));
  --color-cerulean-mist: #96beca;
  --color-subtle-teal: #74a9b9;
  --color-radiant-yellow: #f4b811;
  --color-calm-green: #9db161;

  /* Typography — Font Families */
  --font-onest-variable: 'Onest Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.04px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.04px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.04px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.06px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: 0.06px;
  --text-display: 48px;
  --leading-display: 1.05;
  --tracking-display: 0.12px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 14px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-input: 5px;
  --radius-badges: 4px;
  --radius-buttons: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 5px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 2px 2px 8px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.2) 2px 2px 5px 0px;
  --shadow-sm-4: rgba(10, 9, 12, 0.04) 0px 1px 4px 0px;
  --shadow-subtle: rgba(10, 9, 12, 0.03) 0px 1px 3px 0px;
  --shadow-lg: rgba(117, 97, 177, 0.063) 0px 4px 20px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #0a090c;
  --color-canvas: #e6e6e5;
  --color-paper-white: #ffffff;
  --color-ash-gray: #f4f4f4;
  --color-steel-gray: #c3c3c3;
  --color-grout: #d1d5db;
  --color-charcoal: #2d2d2d;
  --color-twilight-lavender: #7561b1;
  --color-cerulean-mist: #96beca;
  --color-subtle-teal: #74a9b9;
  --color-radiant-yellow: #f4b811;
  --color-calm-green: #9db161;

  /* Typography */
  --font-onest-variable: 'Onest Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.04px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.04px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.04px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.06px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: 0.06px;
  --text-display: 48px;
  --leading-display: 1.05;
  --tracking-display: 0.12px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 14px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 5px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 2px 2px 8px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.2) 2px 2px 5px 0px;
  --shadow-sm-4: rgba(10, 9, 12, 0.04) 0px 1px 4px 0px;
  --shadow-subtle: rgba(10, 9, 12, 0.03) 0px 1px 3px 0px;
  --shadow-lg: rgba(117, 97, 177, 0.063) 0px 4px 20px 0px;
}
```
