# 15five — Style Reference
> Violet-tinged sunrise on white marble

**Theme:** light

15Five employs a vibrant, confident design language with clean white canvases, softened cards, and a striking violet-to-pink gradient. Typography is a blend of bold, impactful headlines and accessible body text. The system uses a specific 'hero' violet as its primary accent, contrasted with touches of warm orange and pink, creating an energetic yet grounded feel. Components are lightweight with generous rounded corners, emphasizing an approachable and modern presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default text for dark elements |
| Warm Mist | `#fff2e8` | `--color-warm-mist` | Subtle background for secondary cards and elevated surface sections, providing visual separation |
| Violet Shadow | `#5e5777` | `--color-violet-shadow` | Muted text, secondary button text, decorative borders, helper text |
| Deep Violet | `#2f115b` | `--color-deep-violet` | Primary text, bold accents, outlined button borders, key interactive elements |
| Midnight Indigo | `#1a0d3f` | `--color-midnight-indigo` | Prominent headings and body text, providing high contrast on light backgrounds |
| Accent Violet | `linear-gradient(90deg, rgb(59, 21, 114) 0%, rgb(26, 13, 63) 100%)` | `--color-accent-violet` | Primary action button background fill, active states for interactive elements — a rich, vibrant brand identifier; Prominent background for hero sections and testimonials, establishing a vibrant brand tone |
| Pink Sunset | `#ffdacf` | `--color-pink-sunset` | Highlight backgrounds, secondary action buttons, gradient accents |
| Fiery Orange | `#ff4b11` | `--color-fiery-orange` | Outlined button borders, subtle highlights and decorative accents |

## Tokens — Typography

### Manrope — Primary sans-serif for all body text, navigation, buttons, and helper content. Its varied weights offer flexibility for hierarchy, maintaining legibility and a contemporary feel across the interface. · `--font-manrope`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 22px, 24px
- **Line height:** 1.00, 1.33, 1.43, 1.44, 1.50, 1.63, 1.64, 2.57
- **Letter spacing:** 0.0020em (at 14px), 0.3750em (for specific uppercase elements)
- **Role:** Primary sans-serif for all body text, navigation, buttons, and helper content. Its varied weights offer flexibility for hierarchy, maintaining legibility and a contemporary feel across the interface.

### DM Serif Display — Distinguished serif typeface for prominent headings, creating a sophisticated and editorial impact with its elegant curves and generous scale. · `--font-dm-serif-display`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 24px, 40px, 52px, 66px
- **Line height:** 1.15, 1.20, 1.25, 1.33
- **Letter spacing:** normal
- **Role:** Distinguished serif typeface for prominent headings, creating a sophisticated and editorial impact with its elegant curves and generous scale.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | 0.002px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.63 | — | `--text-subheading` |
| heading-sm | 22px | 1.64 | — | `--text-heading-sm` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 40px | 1.25 | — | `--text-heading-lg` |
| display | 66px | 1.15 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 84 | 84px | `--spacing-84` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 152 | 152px | `--spacing-152` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 68px |
| general | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 12px 30px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1363px
- **Section gap:** 24px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Call to action.

Filled with Accent Violet (#3b1572), white text, 68px border-radius, 16px padding on top/bottom, 40px on left/right. Commands attention for key actions.

### Light Outlined Button
**Role:** Secondary action or ghost button.

White background, Deep Violet (#2f115b) text, 68px border-radius, 16px padding on top/bottom, 40px on left/right. Provides a subtle interactive element that doesn't compete with primary actions.

### Subtle Nav Link
**Role:** Navigation or in-page links.

Transparent background, Violet Shadow (#5e5777) text, 16px border-radius, 20px padding. Minimally styled for navigation, with a soft border-radius that hints at interactivity.

### Text Only Link
**Role:** Inline textual links.

Transparent background, Midnight Indigo (#1a0d3f) text, no border-radius or padding. Used for simple text links within body content or lists.

### Information Card (Transparent)
**Role:** Content container for data or features.

Transparent background, 0px border-radius, 0px padding on top/bottom, 20px on left/right. Used for presenting information without strong visual boundaries, allowing content to breathe.

### Data Insight Card
**Role:** Displays data metrics or key insights.

White background, 12px border-radius, no padding. A clean, contained surface for showcasing performance metrics or brief information.

### Highlighted Testimonial Card
**Role:** Prominently features customer testimonials.

Pink Sunset (#ffdacf) background, 16px border-radius, with decorative gradient accents. No internal padding defined, relies on content spacing.

### Shadowed Link Box
**Role:** Interactive link blocks with elevation.

Features a white background, 10px border-radius, and a soft shadow (rgba(0, 0, 0, 0.1) 0px 12px 30px 0px). Used for clickable elements that require a distinct elevated presence.

## Do's and Don'ts

### Do
- Use Midnight Indigo (#1a0d3f) for all main headings and primary body text to ensure high contrast and readability.
- Apply Canvas White (#ffffff) as the default background for all primary page content sections and cards.
- Implement the 68px border-radius for all button elements, including both filled and outlined variants, to maintain a consistent soft, approachable shape.
- Utilize Manrope for all functional typography (buttons, nav, body text) and DM Serif Display for major page headings to leverage their distinct roles.
- Incorporate the Hero Gradient (linear-gradient(90deg, #3b1572 0%, #1a0d3f 100%)) as a background for high-impact sections like hero banners and testimonials.
- Maintain a comfortable density with an element gap of 20px and a section gap of 24px between major content blocks.
- Use Accent Violet (#3b1572) as the primary fill color for active buttons and key interactive elements, drawing immediate attention.

### Don't
- Avoid using multiple border styles or weights for interactive elements; stick to 1px solid for subtle hints and no border for purely textual links.
- Do not introduce new typefaces; rely solely on Manrope and DM Serif Display to preserve typographic consistency.
- Resist using harsh or high-contrast shadows; only apply the soft, diffused shadow (rgba(0, 0, 0, 0.1) 0px 12px 30px 0px) for specific elevated components like link cards.
- Do not deviate from the established border radii; avoid sharp corners or excessively small radii as they contradict the system's approachable aesthetic.
- Refrain from using saturated colors other than Accent Violet, Pink Sunset, or Fiery Orange for UI elements; other vibrant hues are reserved for data visualization or illustrations.
- Do not expand the primary color palette with additional blues, greens, or reds unless they are specifically for semantic status indications (success, error).
- Avoid arbitrary letter-spacing adjustments; adhere to the defined Manrope letter-spacing values or normal for DM Serif Display.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, base layer. |
| 1 | Warm Mist | `#fff2e8` | Secondary background for sections, subtle elevation for content blocks. |
| 2 | Pink Sunset | `#ffdacf` | Highlight background for interactive elements or featured content like testimonials. |
| 3 | Accent Violet | `#3b1572` | Background for primary action buttons, signaling interaction points. |
| 4 | Hero Gradient | `#3b1572` | Prominent stylistic background for hero sections and testimonial blocks, providing visual depth and brand emphasis. |

## Elevation

- **Shadowed Link Box:** `rgba(0, 0, 0, 0.1) 0px 12px 30px 0px`

## Imagery

The site predominantly uses clean, product-focused illustrations and data visualizations. Illustrations are often abstract, geometric, and brand-colored, featuring soft gradients. Photography is largely absent, replaced by UI screenshots of the product. Icons are filled, with a consistent stroke weight, and mostly monochromatic or brand-colored. Imagery serves an explanatory and illustrative role, showcasing product features and data outputs rather than decorative atmosphere, contributing to a high-density, text-supported visual experience.

## Layout

The page adheres to a max-width of 1363px, centered for most content, but the initial hero section appears full-bleed with a gradient background. The hero features a large, centered headline and subtext, followed by two prominent call-to-action buttons. Sections below alternate between a white canvas and a subtle Warm Mist (#fff2e8) background, often employing a two-column layout with text on one side and product UI screenshots or data visualizations on the other. A three or four-column card grid is used for feature showcases. Vertical spacing is consistent and comfortable, with a section gap of 24px fostering readability. The navigation is a sticky top bar with a 'Book a Demo' button prominently featured.

## Agent Prompt Guide

Quick Color Reference:
- text: #1a0d3f
- background: #ffffff
- border: #5e5777
- accent: #3b1572
- primary action: #ffdacf (filled action)

Example Component Prompts:
- Create a Primary Action Button: #ffdacf background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a data insight card: White background, 12px border-radius, showing a statistic with heading at 24px Manrope weight 700, #1a0d3f, and body text at 16px Manrope weight 400, #5e5777.
- Create a testimonial component: Pink Sunset (#ffdacf) background, 16px border-radius. Quote text at 18px DM Serif Display weight 400, #1a0d3f. A Light Outlined Button below with text 'Read full story'.

## Motion Philosophy

The system utilizes expressive motion, primarily with 0.4s and 0.3s durations, and 'ease' timing functions. Transitions are common on background, transform, padding, and box-shadow properties, creating fluid and responsive interactions without being overly animated. Subtle changes in state are preferred over jarring, immediate shifts.

## Similar Brands

- **Lattice** — White space, structured layouts, and product interface screenshots mixed with brand-specific color accents.
- **BetterUp** — Uses a limited palette of white and a deep accent color for primary actions, with subtle background gradients.
- **Culture Amp** — Focus on data visualization in cards, soft rounded corners for components, and strong, clear typography on light backgrounds.
- **Brightwheel** — Similar approachable feel with soft rounded shapes, a dominant white canvas, and a vibrant primary accent color for calls to action.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-warm-mist: #fff2e8;
  --color-violet-shadow: #5e5777;
  --color-deep-violet: #2f115b;
  --color-midnight-indigo: #1a0d3f;
  --color-accent-violet: #3b1572;
  --gradient-accent-violet: linear-gradient(90deg, rgb(59, 21, 114) 0%, rgb(26, 13, 63) 100%);
  --color-pink-sunset: #ffdacf;
  --color-fiery-orange: #ff4b11;

  /* Typography — Font Families */
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-serif-display: 'DM Serif Display', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.002px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.63;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.64;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display: 66px;
  --leading-display: 1.15;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-152: 152px;

  /* Layout */
  --page-max-width: 1363px;
  --section-gap: 24px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-full: 68px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 68px;
  --radius-general: 10px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 12px 30px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-mist: #fff2e8;
  --surface-pink-sunset: #ffdacf;
  --surface-accent-violet: #3b1572;
  --surface-hero-gradient: #3b1572;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-warm-mist: #fff2e8;
  --color-violet-shadow: #5e5777;
  --color-deep-violet: #2f115b;
  --color-midnight-indigo: #1a0d3f;
  --color-accent-violet: #3b1572;
  --color-pink-sunset: #ffdacf;
  --color-fiery-orange: #ff4b11;

  /* Typography */
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-serif-display: 'DM Serif Display', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.002px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.63;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.64;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display: 66px;
  --leading-display: 1.15;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-152: 152px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-full: 68px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 12px 30px 0px;
}
```
