# Lightdash — Style Reference
> Codebase blueprint on frosted glass

**Theme:** light

Lightdash employs a precise, tech-forward aesthetic using a monochromatic palette punctuated by a single vibrant accent. Typography is a key identifier, balancing strong, impactful sans-serif headlines with clean, readable body text. Components favor soft curves and subtle elevation, appearing lightweight yet defined, maintaining a sense of digital clarity and focused productivity. The overall design feels robust and intelligent, reflecting its AI/BI platform nature.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1a1b25` | `--color-midnight-ink` | Primary text for headings and interactive elements, button backgrounds for ghost/outlined variants |
| Charcoal Slate | `#272835` | `--color-charcoal-slate` | Hero section text, secondary button backgrounds, and subtle borders |
| Deep Indigo | `#36394a` | `--color-deep-indigo` | Input backgrounds, primary body text, and some borders |
| Steel Gray | `#666d80` | `--color-steel-gray` | Secondary body text and muted informational details |
| Cloud Gray | `#818898` | `--color-cloud-gray` | Tertiary text, decorative elements, and subtle icon strokes |
| Stone Wash | `#a4abb8` | `--color-stone-wash` | Light helper text, link borders, and subtle descriptive text |
| Off-White | `#f8fafb` | `--color-off-white` | Subtle background for UI elements, light cards |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, high-contrast text |
| Lava Cloud | `#eceff3` | `--color-lava-cloud` | Subtle background for alternating sections or distinct UI areas |
| Ghost Fill | `#f6f8fa` | `--color-ghost-fill` | Background for subtle surface differentiation, such as active states or hovering elements |
| Electric Violet | `#5e4cff` | `--color-electric-violet` | Primary action buttons, interactive highlights, and brand accents to draw attention |
| Lavender Mist | `#dfdbff` | `--color-lavender-mist` | Subtle button backgrounds, decorative accents, and soft focus states |
| Pixel Purple | `#c8ccf3` | `--color-pixel-purple` | Decorative background fills, hinting at digital patterns and data visualizations |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Britti Sans Trial Semibold — Primary headlines and impactful display text. The tight letter-spacing at larger sizes gives a sense of modern precision and weight without being bold, authoritative through restraint. · `--font-britti-sans-trial-semibold`
- **Substitute:** Montserrat
- **Weights:** 400, 600
- **Sizes:** 18px, 48px, 56px, 57px, 76px
- **Line height:** 0.90, 0.95, 1.00, 1.56
- **Letter spacing:** -0.025em, -0.020em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary headlines and impactful display text. The tight letter-spacing at larger sizes gives a sense of modern precision and weight without being bold, authoritative through restraint.

### Britti Sans Medium — Subheadings, section titles, and prominent UI labels. A slightly more relaxed tracking than display text, maintaining legibility at various intermediate sizes. · `--font-britti-sans-medium`
- **Substitute:** Montserrat
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px
- **Line height:** 1.11, 1.14, 1.20, 1.25, 1.30, 1.80, 2.00
- **Letter spacing:** -0.020em, -0.010em, 0.010em
- **Role:** Subheadings, section titles, and prominent UI labels. A slightly more relaxed tracking than display text, maintaining legibility at various intermediate sizes.

### Britti Sans Trial Regular — Specific display text, often used for numerical data or secondary large-scale headings, offering a slightly lighter visual presence than semibold. · `--font-britti-sans-trial-regular`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 48px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.020em
- **Role:** Specific display text, often used for numerical data or secondary large-scale headings, offering a slightly lighter visual presence than semibold.

### Inter — Body text, navigation, input fields, and most UI elements. Its variable weights provide flexibility for hierarchy without introducing additional type families. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 9px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 24px
- **Line height:** 1.00, 1.19, 1.20, 1.33, 1.38, 1.43, 1.50, 1.54, 1.63, 1.78
- **Letter spacing:** -0.020em, -0.015em, -0.010em
- **Role:** Body text, navigation, input fields, and most UI elements. Its variable weights provide flexibility for hierarchy without introducing additional type families.

### Inter Variable — Specific body text instances, often for slightly larger or more prominent paragraph content, leveraging the variable font features for fine-tuned density. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 14px, 16px, 18px
- **Line height:** 1.25, 1.43, 1.54, 1.67, 1.70
- **Letter spacing:** -0.010em
- **Role:** Specific body text instances, often for slightly larger or more prominent paragraph content, leveraging the variable font features for fine-tuned density.

### IBM Plex Mono — Monospaced text for code snippets, data displays, or precise technical information. Maintains a consistent visual rhythm. · `--font-ibm-plex-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.50
- **Letter spacing:** -0.020em
- **Role:** Monospaced text for code snippets, data displays, or precise technical information. Maintains a consistent visual rhythm.

### Micro 5 — Highly stylized, decorative headlines or special numeric displays, used sparingly for specific visual impact that evokes digital code or retro computing. · `--font-micro-5`
- **Substitute:** Micro 5 (Google Fonts)
- **Weights:** 400
- **Sizes:** 31px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Highly stylized, decorative headlines or special numeric displays, used sparingly for specific visual impact that evokes digital code or retro computing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | -0.01px | `--text-body` |
| subheading | 18px | 1.3 | -0.01px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.01px | `--text-heading-sm` |
| heading | 32px | 1.14 | — | `--text-heading` |
| heading-lg | 48px | 1 | -0.025px | `--text-heading-lg` |
| display | 76px | 0.9 | -0.025px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 12px |
| inputs | 0px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.05) 0px 2px 5px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-sm` |
| subtle | `rgba(18, 18, 18, 0.1) 0px 1px 1px 0px, rgba(18, 18, 18, 0...` | `--shadow-subtle` |
| subtle-2 | `rgba(39, 40, 53, 0.1) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(39, 40, 53, 0.1) 0px 0px 0px 1px, rgba(39, 40, 53, 0...` | `--shadow-subtle-3` |
| subtle-4 | `rgba(39, 40, 53, 0.05) 0px 0px 0px 1px, rgba(39, 40, 53, ...` | `--shadow-subtle-4` |
| lg | `rgba(0, 0, 0, 0.01) 0px 54px 21px 0px, rgba(0, 0, 0, 0.05...` | `--shadow-lg` |

### Layout

- **Section gap:** 40-64px
- **Card padding:** 24-32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action.

Filled button with Electric Violet (#5e4cff) background, white text, 8px border-radius, and 12px vertical, 20px horizontal padding. Uses Inter font weight 500.

### Secondary Ghost Button
**Role:** Secondary action or subtle interaction.

Ghost button with a transparent background, Midnight Ink (#1a1b25) border, a minimum 1px border stroke, 8px border-radius, and 12px vertical, 20px horizontal padding. Text color is Midnight Ink (#1a1b25). Uses Inter font weight 500.

### Tertiary Filled Button
**Role:** Informational actions or less prominent calls to action.

Filled button with Lava Mist (#dfdbff) background, Midnight Ink (#1a1b25) text, 8px border-radius, and 12px vertical, 20px horizontal padding.

### Interactive Chip Button
**Role:** Filter chips or toggleable options.

Card-like button with a light background (rgba(5, 5, 19, 0.04)), 26px border-radius for a pill shape, and 12px padding all around. No shadow.

### Elevated Feature Card
**Role:** Showcasing product features or key information.

Card with Canvas White (#ffffff) background, 20px border-radius, and a prominent shadow stack (rgba(39, 40, 53, 0.05) 0px 0px 0px 1px, rgba(39, 40, 53, 0.01) 0px 50px 20px 0px, etc.). Padding of 24px top, 32px horizontal, 20px bottom.

### Simple Information Card
**Role:** Containing lists, text, or less emphasized content.

Card with Canvas White (#ffffff) background, 12px border-radius, and a subtle 1px border shadow (rgba(39, 40, 53, 0.1) 0px 0px 0px 1px). Padding of 28px top/bottom, 22px horizontal.

### Segmented Control Item
**Role:** Selectable options within a group.

Segmented control item with a background of rgba(5, 5, 19, 0.06), 26px border-radius, and 16px top, 8px horizontal, 8px bottom padding. No shadow.

### Dark Input Field
**Role:** User input for forms in a dark context.

Input field with a Deep Indigo (#36394a) background, white text, and a white border (rgb(255, 255, 255)). Standard 10px vertical and 20-24px horizontal padding. No border-radius, implying sharp corners or system default.

## Do's and Don'ts

### Do
- Use Electric Violet (#5e4cff) exclusively for primary calls-to-action and critical interactive highlights.
- Apply Britti Sans Trial Semibold for all primary headings, using the specified letter-spacing for each size.
- Maintain a clear visual hierarchy by limiting saturated colors to Electric Violet and its softer accent tints.
- Utilize Canvas White (#ffffff) as the dominant page background and primary card surfaces for visual breathability.
- Implement 8px border-radius for all buttons and 12px for cards to maintain consistent soft-edged elements.
- Differentiate UI surfaces using Charcoal Slate (#272835) for darker elements and Lava Cloud (#eceff3) for subtle background variations.
- Employ IBM Plex Mono for all code blocks or technical data displays to ensure typographic distinction and readability.

### Don't
- Do not introduce new saturated hues outside of the established Electric Violet and its related accent shades.
- Avoid using drop shadows on functional UI elements unless it's a card from the 'Elevated Feature Card' component.
- Do not vary letter-spacing for Britti Sans headlines from the specified -0.025em for large sizes and -0.020em for smaller sizes.
- Never use generic system fonts for branding or primary content where Britti Sans or Inter are specified.
- Do not use Electric Violet (#5e4cff) for body text or large blocks of content; it is reserved for action and accent.
- Avoid excessive use of very dark backgrounds; the system leans heavily on light mode with dark neutral accents.
- Do not apply large, rounded corners (e.g., 20px) to anything other than the specific Elevated Feature Card and pill-shaped elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default surface for content. |
| 1 | Ghost Fill | `#f6f8fa` | Subtle background for distinct sections, hover states, or input wrappers. |
| 2 | Lava Cloud | `#eceff3` | Alternating section backgrounds and more pronounced content dividers. |
| 3 | Off-White | `#f8fafb` | Background for specific UI components or elevated informational blocks. |

## Elevation

- **cards:** `rgba(39, 40, 53, 0.1) 0px 0px 0px 1px`
- **elevated cards:** `rgba(39, 40, 53, 0.05) 0px 0px 0px 1px, rgba(39, 40, 53, 0.01) 0px 50px 20px 0px, rgba(39, 40, 53, 0.02) 0px 30px 18px 0px, rgba(39, 40, 53, 0.04) 0px 13px 13px 0px, rgba(39, 40, 53, 0.05) 0px 3px 7px 0px`
- **layered UI elements:** `rgba(0, 0, 0, 0.05) 0px 2px 5px 0px, rgba(0, 0, 0, 0.04) 0px 9px 9px 0px, rgba(0, 0, 0, 0.02) 0px 20px 12px 0px, rgba(0, 0, 0, 0.01) 0px 35px 14px 0px, rgba(0, 0, 0, 0.01) 0px 0px 0px 1px`

## Imagery

Imagery treatment is primarily focused on abstract, pixelated backgrounds and product UI screenshots. The pixelated patterns, often in shades of violet or dark grays (Pixel Purple #c8ccf3), provide a technical, data-driven atmosphere. Product screenshots feature clean, contained UI elements on dark backgrounds, often with simple, illustrative icons. Icons are predominantly outlined, thin stroke weight, maintaining the minimalist and precise aesthetic. The visual density is balanced, allowing prominent text to lead, with imagery serving as supportive illustration or product showcase rather than decorative flourish for its own sake.

## Layout

The page adheres to a max-width contained layout with content centered, though specific sections may break this for full-bleed effects. The hero section features a prominent headline centered over a nuanced background of dark neutrals and pixelated violet accents. Section rhythm is primarily defined by consistent vertical spacing, creating breathing room, and alternating background colors (Canvas White vs. Lava Cloud) to delineate content blocks. Content arrangement often utilizes two-column layouts with text-left/image-right or centered stacks. Navigation is a sticky top bar, providing persistent access to key links.

## Agent Prompt Guide

Quick Color Reference:
text: #272835
background: #ffffff
border: #b4acff
accent: #c8ccf3
primary action: #5e4cff (filled action)

Example Component Prompts:
Create a hero section: Canvas White (#ffffff) background. Headline 'Agentic BI. Analytics at the speed of code' using Britti Sans Trial Semibold 76px, Charcoal Slate (#272835), letter-spacing -0.025em. Subtext 'The only open source AI-native BI platform...' using Inter 18px, Steel Gray (#666d80). Primary call-to-action button 'Start for free' with Electric Violet (#5e4cff) background, white text, 8px radius, 12px vertical, 20px horizontal padding.

Create a Simple Information Card: Canvas White (#ffffff) background, 12px border-radius, subtle 1px border shadow (rgba(39, 40, 53, 0.1) 0px 0px 0px 1px). Padding 28px top/bottom, 22px horizontal. Headline 'Documentation' using Britti Sans Medium 24px, Midnight Ink (#1a1b25). Body text 'Explore our API guides...' using Inter 16px, Deep Indigo (#36394a).

Create a Dark Input Field: Deep Indigo (#36394a) background, with a 1px solid white border, no border-radius. Placeholder text 'Enter your email' should be Cloud Gray (#818898) using Inter 16px. Text input should be Canvas White (#ffffff).

## Similar Brands

- **Vercel** — Monochromatic interface with a single vibrant accent color for interaction and brand emphasis.
- **Linear** — Precise, condensed typography and minimalist UI with soft-edged components and subtle elevation.
- **Supabase** — Developer-focused aesthetic, clean layouts, and a restrained color palette with a single bright highlight.
- **Figma** — Emphasis on clear type hierarchy, lightweight components on white backgrounds, and functional use of color for status/interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1a1b25;
  --color-charcoal-slate: #272835;
  --color-deep-indigo: #36394a;
  --color-steel-gray: #666d80;
  --color-cloud-gray: #818898;
  --color-stone-wash: #a4abb8;
  --color-off-white: #f8fafb;
  --color-canvas-white: #ffffff;
  --color-lava-cloud: #eceff3;
  --color-ghost-fill: #f6f8fa;
  --color-electric-violet: #5e4cff;
  --color-lavender-mist: #dfdbff;
  --color-pixel-purple: #c8ccf3;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-trial-semibold: 'Britti Sans Trial Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-medium: 'Britti Sans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-trial-regular: 'Britti Sans Trial Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-micro-5: 'Micro 5', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 76px;
  --leading-display: 0.9;
  --tracking-display: -0.025px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40-64px;
  --card-padding: 24-32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-full: 80px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 12px;
  --radius-inputs: 0px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 2px 5px 0px, rgba(0, 0, 0, 0.04) 0px 9px 9px 0px, rgba(0, 0, 0, 0.02) 0px 20px 12px 0px, rgba(0, 0, 0, 0.01) 0px 35px 14px 0px, rgba(0, 0, 0, 0.01) 0px 0px 0px 1px;
  --shadow-subtle: rgba(18, 18, 18, 0.1) 0px 1px 1px 0px, rgba(18, 18, 18, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(39, 40, 53, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(39, 40, 53, 0.1) 0px 0px 0px 1px, rgba(39, 40, 53, 0.08) 0px 24px 24px -12px, rgba(39, 40, 53, 0.08) 0px 12px 12px -6px, rgba(39, 40, 53, 0.08) 0px 6px 6px -3px, rgba(39, 40, 53, 0.08) 0px 2px 2px -1px;
  --shadow-subtle-4: rgba(39, 40, 53, 0.05) 0px 0px 0px 1px, rgba(39, 40, 53, 0.01) 0px 50px 20px 0px, rgba(39, 40, 53, 0.02) 0px 30px 18px 0px, rgba(39, 40, 53, 0.04) 0px 13px 13px 0px, rgba(39, 40, 53, 0.05) 0px 3px 7px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.01) 0px 54px 21px 0px, rgba(0, 0, 0, 0.05) 0px 30px 18px 0px, rgba(0, 0, 0, 0.09) 0px 13px 13px 0px, rgba(0, 0, 0, 0.1) 0px 3px 7px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ghost-fill: #f6f8fa;
  --surface-lava-cloud: #eceff3;
  --surface-off-white: #f8fafb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1a1b25;
  --color-charcoal-slate: #272835;
  --color-deep-indigo: #36394a;
  --color-steel-gray: #666d80;
  --color-cloud-gray: #818898;
  --color-stone-wash: #a4abb8;
  --color-off-white: #f8fafb;
  --color-canvas-white: #ffffff;
  --color-lava-cloud: #eceff3;
  --color-ghost-fill: #f6f8fa;
  --color-electric-violet: #5e4cff;
  --color-lavender-mist: #dfdbff;
  --color-pixel-purple: #c8ccf3;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-trial-semibold: 'Britti Sans Trial Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-medium: 'Britti Sans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-britti-sans-trial-regular: 'Britti Sans Trial Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-micro-5: 'Micro 5', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.01px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 76px;
  --leading-display: 0.9;
  --tracking-display: -0.025px;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-full: 80px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 2px 5px 0px, rgba(0, 0, 0, 0.04) 0px 9px 9px 0px, rgba(0, 0, 0, 0.02) 0px 20px 12px 0px, rgba(0, 0, 0, 0.01) 0px 35px 14px 0px, rgba(0, 0, 0, 0.01) 0px 0px 0px 1px;
  --shadow-subtle: rgba(18, 18, 18, 0.1) 0px 1px 1px 0px, rgba(18, 18, 18, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(39, 40, 53, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(39, 40, 53, 0.1) 0px 0px 0px 1px, rgba(39, 40, 53, 0.08) 0px 24px 24px -12px, rgba(39, 40, 53, 0.08) 0px 12px 12px -6px, rgba(39, 40, 53, 0.08) 0px 6px 6px -3px, rgba(39, 40, 53, 0.08) 0px 2px 2px -1px;
  --shadow-subtle-4: rgba(39, 40, 53, 0.05) 0px 0px 0px 1px, rgba(39, 40, 53, 0.01) 0px 50px 20px 0px, rgba(39, 40, 53, 0.02) 0px 30px 18px 0px, rgba(39, 40, 53, 0.04) 0px 13px 13px 0px, rgba(39, 40, 53, 0.05) 0px 3px 7px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.01) 0px 54px 21px 0px, rgba(0, 0, 0, 0.05) 0px 30px 18px 0px, rgba(0, 0, 0, 0.09) 0px 13px 13px 0px, rgba(0, 0, 0, 0.1) 0px 3px 7px 0px;
}
```
