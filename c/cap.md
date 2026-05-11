# Cap — Style Reference
> Crisp utility on a bright canvas.

**Theme:** light

Cap presents as a pragmatic, highly functional UI with a focus on delivering a clean canvas for content. The design prioritizes clear information hierarchy through a crisp achromatic palette and structured typography. Subtle surface distinctions and soft, pill-shaped interactions provide a friendly yet professional feel. A single vibrant blue acts as the primary accent, drawing attention to calls-to-action and interactive elements without overwhelming the primary content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcfcfc` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, clean content areas |
| Ghost Gray | `#e5e7eb` | `--color-ghost-gray` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Smoke Gray | `#e0e0e0` | `--color-smoke-gray` | Hairline borders, subtle background washes for distinction, secondary button borders |
| Accent Blue | `#2563eb` | `--color-accent-blue` | Primary call-to-action buttons, active states, key interactive elements. A vivid blue that signals action |
| Focus Blue | `#1e40af` | `--color-focus-blue` | Darker blue used for borders of accented buttons, providing depth and focus |
| Base Black | `#000000` | `--color-base-black` | Primary text for headings and body, ensuring high contrast on light backgrounds |
| Carbon Text | `#202020` | `--color-carbon-text` | Secondary text, link text, slightly softer than pure black for improved readability in blocks |
| Muted Ash | `#838383` | `--color-muted-ash` | Muted helper text, disabled states, unobtrusive subheadings, subtle icons |
| Soft Shadow | `#f0f0f0` | `--color-soft-shadow` | Subtle background for UI elements that require a slight lift, providing minimal visual hierarchy |
| Subtle Elevation | `#e0ecfc` | `--color-subtle-elevation` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Indicator Red | `#ef4444` | `--color-indicator-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Primary Gradient Highlight | `linear-gradient(135deg, rgb(102, 126, 234), rgb(118, 75, 162))` | `--color-primary-gradient-highlight` | Decorative background for featured elements or sections, adding visual interest with a soft, shifting color |

## Tokens — Typography

### defaultFont — Primary typeface for all UI elements, headings, and body text. The range of weights supports a clear typographic hierarchy, from light captions to impactful display headings. Tight letter spacing on larger sizes adds a sense of modern precision. · `--font-defaultfont`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 9px, 10px, 11px, 12px, 14px, 15px, 16px, 18px, 20px, 30px, 36px, 52px, 60px
- **Line height:** 1.00, 1.07, 1.11, 1.20, 1.25, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 1.60, 1.63, 1.71, 2.00, 2.18, 2.40, 2.67
- **Letter spacing:** 0.025em for small text, 0.05em for headers, 0.2em for uppercase tracking.
- **Role:** Primary typeface for all UI elements, headings, and body text. The range of weights supports a clear typographic hierarchy, from light captions to impactful display headings. Tight letter spacing on larger sizes adds a sense of modern precision.

### ui-monospace — Used for code snippets, timestamps, and other technical or data-oriented content where a fixed-width font improves readability and alignment. · `--font-ui-monospace`
- **Substitute:** Menlo
- **Weights:** 400, 500
- **Sizes:** 8px, 10px
- **Line height:** 1.40, 2.40, 3.00
- **Role:** Used for code snippets, timestamps, and other technical or data-oriented content where a fixed-width font improves readability and alignment.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | 0.02px | `--text-body` |
| subheading | 18px | 1.33 | 0.05px | `--text-subheading` |
| heading-sm | 30px | 1.25 | 0.05px | `--text-heading-sm` |
| heading | 36px | 1.2 | 0.05px | `--text-heading` |
| heading-lg | 52px | 1.07 | 0.05px | `--text-heading-lg` |
| display | 60px | 1 | 0.05px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |
| 168 | 168px | `--spacing-168` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 12px |
| md | 6px |
| sm | 2px |
| card | 16px |
| none | 0px |
| pill | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.2) 0px 1.5px 0px 0px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px` | `--shadow-subtle-2` |
| md | `rgba(0, 0, 0, 0.05) 0px 4px 10px 0px` | `--shadow-md` |
| subtle-3 | `rgba(191, 219, 254, 0.5) 0px 1px 2px 0px` | `--shadow-subtle-3` |
| xl | `rgba(0, 0, 0, 0.05) 0px 20px 25px -5px, rgba(0, 0, 0, 0.0...` | `--shadow-xl` |
| md-2 | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md-2` |
| subtle-4 | `rgba(221, 214, 254, 0.5) 0px 1px 2px 0px` | `--shadow-subtle-4` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle-5 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-5` |
| subtle-6 | `rgba(255, 255, 255, 0.4) 0px 1.5px 0px 0px inset` | `--shadow-subtle-6` |
| xl-2 | `rgba(0, 0, 0, 0.4) 0px 60px 40px 3px` | `--shadow-xl-2` |
| xl-3 | `rgba(0, 0, 0, 0.18) 0px 8px 32px 0px` | `--shadow-xl-3` |
| md-3 | `rgba(0, 0, 0, 0.12) 0px 4px 16px 0px` | `--shadow-md-3` |
| sm-2 | `rgba(18, 22, 31, 0.02) 0px 2px 8px 0px` | `--shadow-sm-2` |
| md-4 | `rgba(0, 0, 0, 0.25) 0px 4px 14px 0px, rgba(0, 0, 0, 0.1) ...` | `--shadow-md-4` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action.

Solid Accent Blue (#2563eb) background, Focus Blue (#1e40af) border, Base White (#fcfcfc) text, pill-shaped (9999px radius), with 20px horizontal padding. Text color is #fcfcfc.

### Ghost Button
**Role:** Secondary actions or navigation items.

Transparent background, Ghost Gray (#e5e7eb) border, Base Black (#000000) text, pill-shaped (9999px radius). Minimal padding, often used for links or subtle actions.

### Navigation Link
**Role:** Primary navigation elements.

Transparent background, Muted Ash (#838383) text, no explicit border on inactive state. Small padding around text (8px).

### Feature Card
**Role:** Content container for features or testimonials.

Canvas White (#fcfcfc) background, 16px border-radius. Features a soft shadow: `rgba(0, 0, 0, 0.05) 0px 20px 25px -5px, rgba(0, 0, 0, 0.05) 0px 8px 10px -6px`. Padding of 24px.

### Option Select Card
**Role:** Interactive choice element, particularly for mode selection.

Canvas White (#fcfcfc) background, 12px border-radius, no shadow by default. Features 24px padding.

### Interactive Chip
**Role:** Small interactive elements like tags or filter options.

Rounded shape (9999px radius), with a background of either Canvas White (#fcfcfc) or Accent Blue (#2563eb) for active states. Text color is Base Black (#000000) for neutral and Canvas White (#fcfcfc) for active.

### Mac Style Button
**Role:** Icon or image-based buttons replicating OS controls.

Canvas White (#fcfcfc) background, 12px border-radius, with a subtle border of Smoke Gray (#e0e0e0). Padding of 24px.

## Do's and Don'ts

### Do
- Use Base Black (#000000) for primary headlines and Carbon Text (#202020) for most body copy to maintain legibility and contrast.
- Apply Accent Blue (#2563eb) exclusively for primary calls-to-action and active interactive states; avoid it for decorative purposes.
- Employ Ghost Gray (#e5e7eb) for all neutral borders and dividers to keep the UI light and spacious.
- Utilize a 9999px (pill) border-radius for all interactive buttons and small tags, and 16px for larger cards like Feature Cards.
- Maintain the compact spacing rhythm by consistently using 8px for `elementGap` and 24px for `cardPadding`.
- Ensure all interactive elements have a clear visual indication for 'active' or 'selected' states, typically with Accent Blue (#2563eb) or a similar level of visual prominence.
- Favor soft, subtle shadows (e.g., `rgba(0, 0, 0, 0.05) 0px 20px 25px -5px`) for cards and elevated elements, rather than hard, dark shadows.

### Don't
- Do not use highly saturated colors other than Accent Blue (#2563eb) unless it's for illustrative or brand-specific gradients.
- Avoid deep or complex nested shadows; rely on the minimal soft shadow for elevation.
- Do not introduce strong background colors on sections without explicit need, keeping the dominant Canvas White (#fcfcfc) as the base.
- Refrain from using varied letter-spacing treatments on body text; confine tight tracking to headings and specific UI elements.
- Do not use dark backgrounds for main content areas; maintain the light theme for overall UI consistency.
- Avoid overly bold or heavy typography for subheadings and body text; prioritize clarity and a lightweight feel.
- Do not break the established radius patterns; consistent use of pill shapes for interactive elements and rounded corners for containers is critical.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fcfcfc` | Base page background and primary content areas. |
| 1 | Feature Card Surface | `#fcfcfc` | Elevated cards that contain content, distinguished by subtle shadow. |
| 2 | Subtle Elevation | `#e0ecfc` | Hints at interactivity or selection, used for specific control panels or hover effects. |

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.05) 0px 20px 25px -5px, rgba(0, 0, 0, 0.05) 0px 8px 10px -6px`
- **Interactive Button:** `rgba(255, 255, 255, 0.2) 0px 1.5px 0px 0px inset, rgba(0, 0, 0, 0.05) 0px 4px 10px 0px`

## Imagery

Cap's visual language for imagery focuses on high-fidelity product screenshots, often presented within a stylized macOS window frame, clearly demonstrating the software in action. These are typically contained within cards, not full-bleed, emphasizing the clean UI over expansive visuals. Icons are outlined, monochromatic, or occasionally rendered in Accent Blue, maintaining a light stroke weight and a functional, illustrative style. The content is text-dominant, with imagery serving as explanatory and supportive evidence of product capabilities, rather than decorative atmosphere.

## Layout

The page adheres to a max-width contained layout, typically centered around 1200px, creating a structured and predictable reading experience. The hero section features a prominent, left-aligned headline and supporting text, contrasted by a product screenshot on the right. Vertical rhythm is established through consistent section gaps, sometimes broken by alternating very light gray (#fcfcfc to #f0f0f0) background bands. Content is primarily arranged in two-column text and visual blocks, or three-column card grids for features, promoting scanability and clear separation of information. The navigation is a sticky top bar with a clear brand logo, product links, and distinct 'Login' and 'Sign Up' buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #fcfcfc
- border: #e5e7eb
- accent: #667EEA (gradient start color)
- primary action: #2563eb (filled action)

Example Component Prompts:
- Create a Primary Action Button: #2563eb background, #fcfcfc text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Render a Feature Card: Canvas White (#fcfcfc) background, 16px border-radius, with the standard soft shadow. Provide 24px padding inside. Title 'One app, every workflow' at 36px defaultFont weight 700 with Base Black (#000000) text, and body 'Whether you need speed...' at 16px defaultFont weight 400 with Carbon Text (#202020) text.
- Design an Interactive Chip for 'Instant Mode': Canvas White (#fcfcfc) background, pill-shaped (9999px radius), with an Active Accent Blue (#2563eb) border, Base Black (#000000) text. Inner padding of 6px vertical, 10px horizontal. Include a small outlined icon in Accent Blue (#2563eb).

## Similar Brands

- **Linear** — Exhibits a precise, compact typography system and a monochromatic interface with functional color accents, prioritizing utility.
- **Supabase** — Uses a similar approach to white space, structured content blocks, and a clear, functional color palette.
- **Amie** — Features a sunlit, canvas-like aesthetic with subtle surface variations and a singular vivid primary action color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcfcfc;
  --color-ghost-gray: #e5e7eb;
  --color-smoke-gray: #e0e0e0;
  --color-accent-blue: #2563eb;
  --color-focus-blue: #1e40af;
  --color-base-black: #000000;
  --color-carbon-text: #202020;
  --color-muted-ash: #838383;
  --color-soft-shadow: #f0f0f0;
  --color-subtle-elevation: #e0ecfc;
  --color-indicator-red: #ef4444;
  --color-primary-gradient-highlight: #667EEA;
  --gradient-primary-gradient-highlight: linear-gradient(135deg, rgb(102, 126, 234), rgb(118, 75, 162));

  /* Typography — Font Families */
  --font-defaultfont: 'defaultFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.05px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: 0.05px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: 0.05px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: 0.05px;

  /* Typography — Weights */
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-140: 140px;
  --spacing-168: 168px;
  --spacing-180: 180px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-lg: 12px;
  --radius-md: 6px;
  --radius-sm: 2px;
  --radius-card: 16px;
  --radius-none: 0px;
  --radius-pill: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 1.5px 0px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 4px 10px 0px;
  --shadow-subtle-3: rgba(191, 219, 254, 0.5) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.05) 0px 20px 25px -5px, rgba(0, 0, 0, 0.05) 0px 8px 10px -6px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: rgba(221, 214, 254, 0.5) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.4) 0px 1.5px 0px 0px inset;
  --shadow-xl-2: rgba(0, 0, 0, 0.4) 0px 60px 40px 3px;
  --shadow-xl-3: rgba(0, 0, 0, 0.18) 0px 8px 32px 0px;
  --shadow-md-3: rgba(0, 0, 0, 0.12) 0px 4px 16px 0px;
  --shadow-sm-2: rgba(18, 22, 31, 0.02) 0px 2px 8px 0px;
  --shadow-md-4: rgba(0, 0, 0, 0.25) 0px 4px 14px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-canvas-white: #fcfcfc;
  --surface-feature-card-surface: #fcfcfc;
  --surface-subtle-elevation: #e0ecfc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcfcfc;
  --color-ghost-gray: #e5e7eb;
  --color-smoke-gray: #e0e0e0;
  --color-accent-blue: #2563eb;
  --color-focus-blue: #1e40af;
  --color-base-black: #000000;
  --color-carbon-text: #202020;
  --color-muted-ash: #838383;
  --color-soft-shadow: #f0f0f0;
  --color-subtle-elevation: #e0ecfc;
  --color-indicator-red: #ef4444;
  --color-primary-gradient-highlight: #667EEA;

  /* Typography */
  --font-defaultfont: 'defaultFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.05px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: 0.05px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: 0.05px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: 0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-140: 140px;
  --spacing-168: 168px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 1.5px 0px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px;
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 4px 10px 0px;
  --shadow-subtle-3: rgba(191, 219, 254, 0.5) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.05) 0px 20px 25px -5px, rgba(0, 0, 0, 0.05) 0px 8px 10px -6px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: rgba(221, 214, 254, 0.5) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.4) 0px 1.5px 0px 0px inset;
  --shadow-xl-2: rgba(0, 0, 0, 0.4) 0px 60px 40px 3px;
  --shadow-xl-3: rgba(0, 0, 0, 0.18) 0px 8px 32px 0px;
  --shadow-md-3: rgba(0, 0, 0, 0.12) 0px 4px 16px 0px;
  --shadow-sm-2: rgba(18, 22, 31, 0.02) 0px 2px 8px 0px;
  --shadow-md-4: rgba(0, 0, 0, 0.25) 0px 4px 14px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px;
}
```
