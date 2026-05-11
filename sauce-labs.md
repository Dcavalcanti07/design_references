# Sauce Labs — Style Reference
> Dark teal command center

**Theme:** dark

Sauce Labs presents a command center aesthetic, blending a dark, deep canvas with vibrant, functional accent colors. Typography is crisp and purposeful, creating clear visual hierarchy against the subdued backgrounds. Components are lightweight yet defined by subtle borders and large, soft radii, suggesting approachability within a sophisticated technical environment. The overall impression is one of clarity and quiet power, where key information and actions are highlighted with precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Teal | `#132322` | `--color-deep-teal` | Page backgrounds, prominent card surfaces, dark text on light backgrounds, outlined button borders and text |
| White Canvas | `#ffffff` | `--color-white-canvas` | Content areas, light card surfaces, primary text on dark backgrounds, ghost button borders and text |
| Black Ink | `#000000` | `--color-black-ink` | Text on light backgrounds, decorative fills, some button borders |
| Fog | `#edf7f5` | `--color-fog` | Subtle surface elevation, alternative light card backgrounds |
| Charcoal Grey | `#0e1a19` | `--color-charcoal-grey` | Dark body text, border color in some contexts |
| Medium Grey | `#666666` | `--color-medium-grey` | Decorative fills primarily for icons and SVG elements |
| Light Grey | `#b2b6b4` | `--color-light-grey` | Muted text, subtle borders around elements |
| Silver Mist | `#d0d3d3` | `--color-silver-mist` | Hairline separators and borders |
| Cool Stone | `#828786` | `--color-cool-stone` | Distinct background for specific card types |
| Vibrant Green | `#3ddc91` | `--color-vibrant-green` | Primary action buttons, active states, feature highlights – a vibrant activation color |
| Product Yellow | `#ffcd48` | `--color-product-yellow` | Accent for specific card backgrounds or illustrative elements |
| Muted Mint | `#97ddbc` | `--color-muted-mint` | Soft accent for card backgrounds, creating a gentle visual distinction |
| Slate Green | `#243b3a` | `--color-slate-green` | Darker, secondary accent for card backgrounds |
| Soft Green | `#192b29` | `--color-soft-green` | Even darker, tertiary accent for card backgrounds, close to the main Deep Teal |

## Tokens — Typography

### Aeonik — Primary UI font for body text, links, and various UI elements. Its clean, contemporary feel underlies the functional aesthetic. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 16px, 18px, 20px, 24px
- **Line height:** 1.20, 1.25, 1.40, 1.45, 1.50
- **Letter spacing:** -0.005em, 0.04em, 0.05em
- **Role:** Primary UI font for body text, links, and various UI elements. Its clean, contemporary feel underlies the functional aesthetic.

### AeonikFono — Used for headings, buttons, and other prominent text elements, often in larger sizes. The geometric, almost monospace character, provides a technical, precise tone. Its generous tracking at larger sizes ensures crispness. · `--font-aeonikfono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 9px, 14px, 16px, 24px, 32px, 40px, 48px, 64px
- **Line height:** 1.10, 1.12, 1.20, 1.22, 1.30, 1.75
- **Letter spacing:** 0.05em
- **Role:** Used for headings, buttons, and other prominent text elements, often in larger sizes. The geometric, almost monospace character, provides a technical, precise tone. Its generous tracking at larger sizes ensures crispness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.25 | 0.04px | `--text-body-sm` |
| body-lg | 16px | 1.25 | -0.08px | `--text-body-lg` |
| subheading | 18px | 1.45 | -0.09px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.12px | `--text-heading-sm` |
| heading | 32px | 1.22 | -0.16px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.2px | `--text-heading-lg` |
| display | 64px | 1.12 | -0.32px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| buttons | 32px |
| large-cards | 60px |
| round-elements | 56px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.04) 1px 0px 9px 2px` | `--shadow-md` |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Ghost Button (Accent Border)
**Role:** Secondary action button for dark backgrounds.

Transparent background, 'Deep Teal' (#132322) border and text color, 56px border-radius, 14px vertical padding, 28px horizontal padding. Font: Aeonik weight 400, 16px. Creates a subtle, outlined presence.

### Ghost Button (White Border)
**Role:** Secondary action button for dark backgrounds.

Transparent background, 'White Canvas' (#ffffff) border and text color, 32px border-radius, 6px vertical padding, 10px horizontal padding. Font: Aeonik weight 400, 16px. Offers higher contrast on dark surfaces.

### Primary Action Button
**Role:** Main call-to-action.

Filled with 'Vibrant Green' (#3ddc91), 'Deep Teal' (#132322) text color, 32px border-radius, 6px vertical padding, 10px horizontal padding. Font: Aeonik weight 400, 16px. Signals a primary interactive element.

### Icon Button (Circular)
**Role:** Small, interactive icon container.

Transparent background, 'Light Grey' (#899191) border, 50% border-radius (circular), 8px padding all around. Text color 'Black Ink' (#000000, 54% opacity). Small, contained, and interactive.

### Overlay Card (Dark)
**Role:** Content card above dark section backgrounds.

Semi-transparent 'Deep Teal' (#132322, 51% opacity) background, 20px border-radius, no shadow, 24px vertical padding, 80px horizontal padding. Provides a slightly elevated, muted surface.

### Accent Card (Slate Green)
**Role:** Content card for visual distinction.

Solid 'Slate Green' (#243b3a) background, 16px border-radius, no shadow, 56px vertical padding, 32px horizontal padding. Creates a darker, more prominent surface.

### Badge Card (Vibrant Green)
**Role:** Decorative or status display card.

Solid 'Vibrant Green' (#3ddc91) background, 60px border-radius, no shadow, 0px padding. Used for small, highly visual elements.

### Accent Card (Muted Mint)
**Role:** Content card with soft green accent.

Semi-transparent 'Muted Mint' (#82c790, 60% opacity) background, 20px border-radius, no shadow, 40px padding all around. Offers a refreshing, softer visual break.

## Do's and Don'ts

### Do
- Use 'Deep Teal' (#132322) as the primary background for sections and cards to maintain the 'command center' feel.
- Apply 'Vibrant Green' (#3ddc91) exclusively for primary calls to action, active states, and critical highlights to ensure its impact.
- Utilize 20px or 60px border-radius for cards and 32px or 56px for buttons to maintain a soft, approachable aesthetic.
- Employ AeonikFono for all headings and prominent text elements, leveraging its crisp geometric form and calculated letter-spacing.
- Maintain a clear visual hierarchy by using 'White Canvas' (#ffffff) for primary text on dark backgrounds and 'Black Ink' (#000000) for text on light backgrounds.
- Leverage 24px for component and section gaps to ensure comfortable density and readability.
- Use light borders like 'Silver Mist' (#d0d3d3) for subtle separation rather than heavy dividers.

### Don't
- Do not introduce new saturated colors beyond the defined brand and accent palette; maintain a controlled chromatic presence.
- Avoid applying strong box-shadows; elevation is achieved through subtle background color shifts or minimal shadows like rgba(0, 0, 0, 0.04) 1px 0px 9px 2px.
- Do not use generic system fonts; stick to Aeonik for body text and AeonikFono for headlines to preserve the brand's typographic identity.
- Avoid arbitrary changes in border-radius; adhere to 20px for cards and 32px for buttons to maintain visual consistency.
- Do not use dark text on dark backgrounds; ensure sufficient contrast with 'White Canvas' (#ffffff) on 'Deep Teal' (#132322) and other dark neutrals.
- Do not overuse 'Vibrant Green'; preserve its role as a functional highlight, not a decorative element.
- Avoid tight spacing; always provide comfortable amounts of padding and margin, generally adhering to a 24px base for element and section gaps.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Teal Canvas | `#132322` | Primary page and section background, often providing the dark base. |
| 1 | Overlay Card (Deep Teal) | `#132322` | Slightly elevated, semi-transparent card surfaces on the primary background. |
| 2 | Accent Card (Slate Green) | `#243b3a` | Distinct, darker card backgrounds for specific content blocks. |
| 3 | White Canvas (Light) | `#ffffff` | Primary light surface for content sections, contrasting with dark elements. |
| 4 | Fog (Light Elevated) | `#edf7f5` | Subtly elevated light card backgrounds. |

## Elevation

- **card:** `rgba(0, 0, 0, 0.04) 1px 0px 9px 2px`

## Imagery

The site uses a combination of abstract, technical illustrations and tight product screenshots. Illustrations are dimensional, depicting UI elements floating in space with visible connections and abstract geometric shapes, often tinted with muted greens and yellows. Product screenshots are clean and focused, showing software interfaces. Icons are monochromatic, primarily outlined, with a moderate stroke weight. Imagery serves mostly an explanatory and atmospheric role, rather than decorative, creating a 'technical diagram' feel without being overly dense, often contained within cards or placed alongside text for direct explanation.

## Layout

The page primarily uses a max-content width layout, with elements often contained within a central column, but feature sections can extend to almost full-bleed with dark backgrounds. The hero section is dark and full-width, centered with a large headline and supporting text, alongside a prominent illustrative graphic. Section rhythm alternates between dark and light backgrounds, with consistent vertical spacing (approximately 24px for element gaps, 24px for card padding, and 24px for section gaps). Content arrangement frequently features centered stacks of text, or text to the left with visual elements (illustrations, screenshots, or card grids) to the right. Card grids (often 3-column) are used for feature presentation.

## Agent Prompt Guide

primary action: #3ddc91 (filled action)
Create a Primary Action Button: #3ddc91 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
• Generate a 'feature card' with an 'Overlay Card (Dark)' style at 24px vertical and 80px horizontal padding, 20px border-radius, background rgba(19,35,34,0.51). Inside, place a subheading: 'AI-Powered Insights' using AeonikFono weight 400, 24px, lineHeight 1.2, letterSpacing -0.12px, color 'White Canvas' (#ffffff).
• Design a secondary navigation link: 'Learn More' using Aeonik weight 400, 16px, lineHeight 1.25, letterSpacing -0.08px, color 'White Canvas' (#ffffff). This should appear as a simple text link.
• Create a client logo section on a 'White Canvas' (#ffffff) background. Display a company logo (e.g., Walmart) within a card using a 'Cool Stone' (#828786) background, 16px border-radius, and 56px vertical/32px horizontal padding. The logo itself should apply a CSS filter for monochrome display (brightness(0) invert(1)).

## Similar Brands

- **Vercel** — Similar dark, technical UI with subtle gradients and a focus on code/product-oriented visuals.
- **Retool** — Shares the dark background, muted accent colors, and structured card-based layouts for complex data.
- **Linear** — Employs a precise, compact typography with carefully controlled spacing and a dark aesthetic, using color sparingly for function.
- **Postman** — Dark UI theme, emphasis on developer tools, and clear functional call-to-actions against a subdued background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-teal: #132322;
  --color-white-canvas: #ffffff;
  --color-black-ink: #000000;
  --color-fog: #edf7f5;
  --color-charcoal-grey: #0e1a19;
  --color-medium-grey: #666666;
  --color-light-grey: #b2b6b4;
  --color-silver-mist: #d0d3d3;
  --color-cool-stone: #828786;
  --color-vibrant-green: #3ddc91;
  --color-product-yellow: #ffcd48;
  --color-muted-mint: #97ddbc;
  --color-slate-green: #243b3a;
  --color-soft-green: #192b29;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonikfono: 'AeonikFono', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.04px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: -0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: -0.09px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.12px;
  --text-heading: 32px;
  --leading-heading: 1.22;
  --tracking-heading: -0.16px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.2px;
  --text-display: 64px;
  --leading-display: 1.12;
  --tracking-display: -0.32px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 50px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 80px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-buttons: 32px;
  --radius-large-cards: 60px;
  --radius-round-elements: 56px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 1px 0px 9px 2px;

  /* Surfaces */
  --surface-deep-teal-canvas: #132322;
  --surface-overlay-card-deep-teal: #132322;
  --surface-accent-card-slate-green: #243b3a;
  --surface-white-canvas-light: #ffffff;
  --surface-fog-light-elevated: #edf7f5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-teal: #132322;
  --color-white-canvas: #ffffff;
  --color-black-ink: #000000;
  --color-fog: #edf7f5;
  --color-charcoal-grey: #0e1a19;
  --color-medium-grey: #666666;
  --color-light-grey: #b2b6b4;
  --color-silver-mist: #d0d3d3;
  --color-cool-stone: #828786;
  --color-vibrant-green: #3ddc91;
  --color-product-yellow: #ffcd48;
  --color-muted-mint: #97ddbc;
  --color-slate-green: #243b3a;
  --color-soft-green: #192b29;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonikfono: 'AeonikFono', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.04px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --tracking-body-lg: -0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: -0.09px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.12px;
  --text-heading: 32px;
  --leading-heading: 1.22;
  --tracking-heading: -0.16px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.2px;
  --text-display: 64px;
  --leading-display: 1.12;
  --tracking-display: -0.32px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 50px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 80px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 1px 0px 9px 2px;
}
```
