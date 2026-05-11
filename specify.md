# Specify — Style Reference
> Subdued white canvas, violet sparks

**Theme:** light

Specify employs a light-themed interface with subtle gray surfaces that provide depth without harsh contrast. Prominent, controlled typography, primarily in a dark charcoal, guides the user, punctuated by a single vibrant violet accent color that denotes interactive elements and brand presence. Components are gently rounded and softly shadowed, creating a friendly yet precise tool-like aesthetic for a design token engine.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, elevated card surfaces, primary text on dark backgrounds |
| Charcoal Text | `#000000` | `--color-charcoal-text` | Primary text, prominent borders, icons |
| Carbon Surface | `#1a1d1e` | `--color-carbon-surface` | Secondary dark surfaces, subtle dark buttons, dark section backgrounds |
| Ash Gray | `#f6f7f9` | `--color-ash-gray` | Section backgrounds, subtle input fields, utility components |
| Cloud Gray | `#ebedef` | `--color-cloud-gray` | Muted section backgrounds, subtle dividers |
| Medium Gray | `#8d8e8f` | `--color-medium-gray` | Secondary text, helper text, borders for secondary elements |
| Graphite | `#5f6162` | `--color-graphite` | Muted text, less prominent dividers |
| Subtle Dark Background | `#151718` | `--color-subtle-dark-background` | Hero section background, dark mode surfaces when switching themes or for specific components |
| Specify Violet | `#624de3` | `--color-specify-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Highlight Violet | `radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(141, 74, 247) 0%, rgb(255, 255, 255) 100%)` | `--color-highlight-violet` | Accent for links and decorative elements, often in gradients; Decorative background gradient, typically in hero sections or feature blocks |
| Highlight Blue | `radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(29, 88, 192) 0%, rgb(255, 255, 255) 100%)` | `--color-highlight-blue` | Accent for links and decorative elements; Decorative background gradient, typically in hero sections or feature blocks |
| Highlight Green | `radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(0, 150, 57) 0%, rgb(255, 255, 255) 100%)` | `--color-highlight-green` | Accent for links and decorative elements; Decorative background gradient, typically in hero sections or feature blocks |
| Linear Gradient Violet | `linear-gradient(270deg, rgb(110, 86, 207) 0%, rgb(249, 209, 255) 100%)` | `--color-linear-gradient-violet` | Decorative background gradient for banner elements, adds a subtle highlight |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Inter — Primary typeface for all UI text, headings, and body copy. Its functional yet friendly geometry anchors the interface. Weights 600 and 700 are used for emphasized elements and larger headings respectively, while 400 and 500 cover general text and subheadings. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 8px, 10px, 12px, 14px, 16px, 20px, 24px, 32px, 48px, 64px
- **Line height:** 1.00, 1.13, 1.17, 1.20, 1.25, 1.50, 1.60, 1.71, 2.00, 2.40, 3.00
- **Role:** Primary typeface for all UI text, headings, and body copy. Its functional yet friendly geometry anchors the interface. Weights 600 and 700 are used for emphasized elements and larger headings respectively, while 400 and 500 cover general text and subheadings.

### Fira Code — Monospace typeface exclusively for code snippets, token values, or technical labels where consistent character width is key. · `--font-fira-code`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.57
- **Role:** Monospace typeface exclusively for code snippets, token values, or technical labels where consistent character width is key.

### Inter-Medium — Inter-Medium — detected in extracted data but not described by AI · `--font-inter-medium`
- **Weights:** 500
- **Sizes:** 8px, 12px, 14px, 16px
- **Line height:** 1.5, 1.71, 2, 3
- **Role:** Inter-Medium — detected in extracted data but not described by AI

### Inter-SemiBold — Inter-SemiBold — detected in extracted data but not described by AI · `--font-inter-semibold`
- **Weights:** 600
- **Sizes:** 8px, 12px, 14px, 16px, 20px, 24px, 32px
- **Line height:** 1, 1.2, 1.25, 1.5, 1.6, 1.71, 2, 3
- **Letter spacing:** -0.031
- **Role:** Inter-SemiBold — detected in extracted data but not described by AI

### Inter-Bold — Inter-Bold — detected in extracted data but not described by AI · `--font-inter-bold`
- **Weights:** 700
- **Sizes:** 48px, 64px
- **Line height:** 1.13, 1.17
- **Letter spacing:** -0.021, -0.016
- **Role:** Inter-Bold — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 14px | 1.71 | — | `--text-body-lg` |
| heading-sm | 20px | 2.4 | — | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.62px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.99px | `--text-heading-lg` |
| display | 48px | 1.17 | -0.76px | `--text-display` |
| display-lg | 64px | 1.13 | -1.02px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| small | 6px |
| buttons | 6px |
| default | 6px |
| circular | 100px |
| pillButtons | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.2) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) ...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.2) 0px 1px 0px 0px inset, rgba(0, 0...` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.1) 0px 3px 2px -1px, rgba(0, 0, 0, 0.12) ...` | `--shadow-subtle-4` |
| sm | `rgba(0, 0, 0, 0.14) 0px 4px 6px -2px, rgba(0, 0, 0, 0.16)...` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.12) 0px 8px 8px -4px, rgba(0, 0, 0, 0.18)...` | `--shadow-sm-2` |
| lg | `rgba(0, 0, 0, 0.08) 0px 12px 24px 0px, rgba(0, 0, 0, 0.06...` | `--shadow-lg` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call to action button.

Background: Charcoal Text (#000000), Text: White Canvas (#ffffff), Padding: 12px vertical, 20px horizontal. Radius: 6px.

### Ghost Button (dark text)
**Role:** Secondary action button for less prominent interactions.

Background: transparent, Text: Charcoal Text (#000000), Border: 1px solid Charcoal Text (#000000), Padding: 10px vertical, 5px horizontal. Radius: 0px.

### Pill Button (Dark Background)
**Role:** Specialized button for small actions or tags.

Background: Subtle Dark Background (#151718), Text: Specify Violet (#624de3), Padding: 4px vertical, 16px horizontal. Radius: 6px.

### Standard Card
**Role:** Information container, feature display.

Background: White Canvas (#ffffff), Padding: 16px all sides. Radius: 16px. Shadow: Medium elevation.

### Ghost Card
**Role:** Decorative or less prominent information display, often on dark backgrounds.

Background: rgba(255, 255, 255, 0.2), Padding: 24px vertical, 40px horizontal. Radius: 16px. No shadow.

### Testimonial Card
**Role:** Displaying quotes or user feedback

Background: Cloud Gray (#ebedef), Radius: 8px, No padding detected.

### Header Navigation Link
**Role:** Primary navigation element in the header.

Text: Medium Gray (#8d8e8f). On hover, text becomes Specify Violet (#624de3).

## Do's and Don'ts

### Do
- Use Charcoal Text (#000000) for all primary body and heading text for maximum contrast on light backgrounds.
- Apply Specify Violet (#624de3) exclusively for interactive elements like links, buttons, and active states to guide user interaction.
- Implement Standard Cards with White Canvas (#ffffff) background, 16px radius, and the medium elevation shadow for displaying content blocks.
- Maintain a clear visual hierarchy using the Inter font family with judicious application of weights: 600 or 700 for headings, 500 for subheadings, and 400 for body text.
- Utilize Ash Gray (#f6f7f9) for section backgrounds to break up White Canvas (#ffffff) areas cleanly.
- Apply 6px border-radius as the default for small interactive elements such as buttons and tags.
- Ensure consistent 8px element gaps to maintain a compact yet breathable density between components.

### Don't
- Do not use Charcoal Text (#000000) on dark backgrounds where White Canvas (#ffffff) should be used for readability.
- Avoid using multiple vibrant accent colors; stick to Specify Violet (#624de3) as the dominant brand accent.
- Do not introduce sharp corners; maintain the overall soft and approachable feel with prescribed border radii.
- Do not use shadows on Ghost Cards or elements intended to appear flat against a background.
- Avoid arbitrary changes in line-height; adhere to the typographic scale's defined values to ensure vertical rhythm.
- Do not use Fira Code (monospace) for general UI text; it is reserved for code-like content only.
- Do not create new background gradients; use the provided Hero Gradient variations for decorative impacts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Primary page background and base surface. |
| 1 | Ash Gray | `#f6f7f9` | Secondary background for sections and content blocks, providing subtle visual separation. |
| 2 | Standard Card | `#ffffff` | Elevated card surfaces with shadows, used for distinct content containers. |
| 3 | Subtle Dark Background | `#151718` | Hero sections or banners, creating a strong visual break and contrast. |

## Elevation

- **Button:** `rgba(0, 0, 0, 0.2) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px`
- **Card:** `rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px`
- **Hover button:** `rgba(255, 255, 255, 0.2) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px`

## Imagery

This design system uses a mix of three types of visual elements: detailed product illustrations and abstract 3D renders for showcasing the product's technical nature, minimal line icons for UI clarity, and occasional partner logos. The product illustrations feature a dark, atmospheric background with glowing, geometrically structured elements (cubes, lines, circuitry) that visually represent data flow and modularity. These are not full-bleed but contained within discrete sections. Icons are line-based (outlined style), monochromatic, and used functionally. Photography is absent, placing full emphasis on UI and conceptual graphics. Imagery density is moderate, used strategically to break up text-dominant sections and explain concepts.

## Layout

The page primarily uses a max-width contained layout of approximately 1200px, centered horizontally. The hero section often breaks this containment, exhibiting a full-bleed dark background with a centered headline and abstract graphics. Section rhythm alternates between full-bleed dark sections and contained light sections. Content arrangement typically follows a left-aligned, almost magazine-like flow in lighter sections, with alternating text-left/visual-right patterns, and feature grids. Darker sections often feature centered content stacks. An 8px base unit is used for padding and gaps, creating a compact density, but overall sections have significant vertical spacing (40px) providing ample breathing room. The navigation is a sticky top bar.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #ffffff
- border: #000000
- accent: #624de3
- primary action: #1a1d1e (filled action)

**3-5 Example Component Prompts:**
- Create a section with an Ash Gray background: #f6f7f9. Inside, add a Standard Card: background #ffffff, 16px padding, 16px radius, shadow rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px.
- Create a Ghost Button: transparent background, text Charcoal Text (#000000), 10px vertical and 5px horizontal padding, 0px radius, 1px solid Charcoal Text (#000000) border.
- Create a Hero section: Subtle Dark Background (#151718), a centered Inter display-lg heading at 64px, weight 700, #ffffff, letter-spacing -1.02px. Below it, add an Inter body-lg text at 14px, weight 400, #8d8e8f.
- Create a Primary Action Button: #1a1d1e background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Stripe** — Shares a sophisticated, clean aesthetic with a focus on polished UI, subtle shadows, and a strong, accessible type hierarchy on a light background.
- **Vercel** — Similar approach to dark hero sections with glowing elements contrasting with predominantly light-themed content sections.
- **Linear** — Employs an aesthetic focused on functional design, clear information architecture, and reserved use of color for key interactions or branding.
- **Figma** — Utilizes a clean, white-dominant interface punctuated by precise, functional typography and strategic use of a single vivid accent color for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-charcoal-text: #000000;
  --color-carbon-surface: #1a1d1e;
  --color-ash-gray: #f6f7f9;
  --color-cloud-gray: #ebedef;
  --color-medium-gray: #8d8e8f;
  --color-graphite: #5f6162;
  --color-subtle-dark-background: #151718;
  --color-specify-violet: #624de3;
  --color-highlight-violet: #8d4af7;
  --gradient-highlight-violet: radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(141, 74, 247) 0%, rgb(255, 255, 255) 100%);
  --color-highlight-blue: #1d58c0;
  --gradient-highlight-blue: radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(29, 88, 192) 0%, rgb(255, 255, 255) 100%);
  --color-highlight-green: #009639;
  --gradient-highlight-green: radial-gradient(50% 84.5% at -14.7% -11.9%, rgb(0, 150, 57) 0%, rgb(255, 255, 255) 100%);
  --color-linear-gradient-violet: #6e56cf;
  --gradient-linear-gradient-violet: linear-gradient(270deg, rgb(110, 86, 207) 0%, rgb(249, 209, 255) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fira-code: 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.71;
  --text-heading-sm: 20px;
  --leading-heading-sm: 2.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.62px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.99px;
  --text-display: 48px;
  --leading-display: 1.17;
  --tracking-display: -0.76px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.13;
  --tracking-display-lg: -1.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 1000px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-small: 6px;
  --radius-buttons: 6px;
  --radius-default: 6px;
  --radius-circular: 100px;
  --radius-pillbuttons: 40px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.2) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.2) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 3px 2px -1px, rgba(0, 0, 0, 0.12) 0px 1px 1px -1px;
  --shadow-sm: rgba(0, 0, 0, 0.14) 0px 4px 6px -2px, rgba(0, 0, 0, 0.16) 0px 12px 16px -4px;
  --shadow-sm-2: rgba(0, 0, 0, 0.12) 0px 8px 8px -4px, rgba(0, 0, 0, 0.18) 0px 20px 24px -4px;
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 12px 24px 0px, rgba(0, 0, 0, 0.06) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-ash-gray: #f6f7f9;
  --surface-standard-card: #ffffff;
  --surface-subtle-dark-background: #151718;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-charcoal-text: #000000;
  --color-carbon-surface: #1a1d1e;
  --color-ash-gray: #f6f7f9;
  --color-cloud-gray: #ebedef;
  --color-medium-gray: #8d8e8f;
  --color-graphite: #5f6162;
  --color-subtle-dark-background: #151718;
  --color-specify-violet: #624de3;
  --color-highlight-violet: #8d4af7;
  --color-highlight-blue: #1d58c0;
  --color-highlight-green: #009639;
  --color-linear-gradient-violet: #6e56cf;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fira-code: 'Fira Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.71;
  --text-heading-sm: 20px;
  --leading-heading-sm: 2.4;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.62px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.99px;
  --text-display: 48px;
  --leading-display: 1.17;
  --tracking-display: -0.76px;
  --text-display-lg: 64px;
  --leading-display-lg: 1.13;
  --tracking-display-lg: -1.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 1000px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.2) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 6px 16px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.2) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.08) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 4px 8px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 3px 2px -1px, rgba(0, 0, 0, 0.12) 0px 1px 1px -1px;
  --shadow-sm: rgba(0, 0, 0, 0.14) 0px 4px 6px -2px, rgba(0, 0, 0, 0.16) 0px 12px 16px -4px;
  --shadow-sm-2: rgba(0, 0, 0, 0.12) 0px 8px 8px -4px, rgba(0, 0, 0, 0.18) 0px 20px 24px -4px;
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 12px 24px 0px, rgba(0, 0, 0, 0.06) 0px 2px 4px 0px;
}
```
