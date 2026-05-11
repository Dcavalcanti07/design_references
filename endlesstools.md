# Endlesstools — Style Reference
> Darkmode vibrant console

**Theme:** dark

Endless Tools employs a dark, high-contrast digital workspace aesthetic. Deep charcoal and true black surfaces form the canvas, punctuated by crisp white text for primary content and subtle gray for secondary information. The system leverages stark typography and meticulously crafted card-like elements with delicate inset borders instead of heavy shadows, creating depth through material treatment rather than traditional elevation. Bright, vivid accents appear sparingly, highlighting interactive elements or brand identity with energetic, almost neon, hues against the monochrome backdrop.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#080808` | `--color-midnight-ink` | Card backgrounds, section backgrounds, input text contrast |
| Stormy Night | `#1e1e1e` | `--color-stormy-night` | Surface backgrounds for interactive elements like input fields |
| Deep Shadow | `#373737` | `--color-deep-shadow` | Button backgrounds, light surface fill for subtle contrast |
| Ash Gray | `#959595` | `--color-ash-gray` | Secondary text, muted helper text, inactive states, subtle borders |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary text, main headings, selected states, button text, crisp borders |
| Charcoal Border | `#505050` | `--color-charcoal-border` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Electric Blue | `#1d9bf0` | `--color-electric-blue` | Link text, interactive borders, accent for active UI elements |
| Vibrant Gradient | `linear-gradient(97.25deg, rgb(184, 255, 69) 3%, rgb(255, 203, 69) 22%, rgb(255, 0, 184) 100%)` | `--color-vibrant-gradient` | Decorative brand element, attention-grabbing background for promotional sections |

## Tokens — Typography

### Inter — Primary sans-serif font for all text content. Variable letter-spacing tightens larger text for modern impact and improves legibility for small sizes. Weight 500 is used for emphasis and headings, while 400 is for body text. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 8px, 12px, 14px, 16px, 18px, 24px, 42px
- **Line height:** 0.83, 1.08, 1.10, 1.11, 1.17, 1.25, 1.29, 1.50, 2.08, 2.19, 2.50
- **Letter spacing:** -0.033em (small text), -0.030em (medium text), -0.025em (large text)
- **Role:** Primary sans-serif font for all text content. Variable letter-spacing tightens larger text for modern impact and improves legibility for small sizes. Weight 500 is used for emphasis and headings, while 400 is for body text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.25 | -0.35px | `--text-body` |
| heading | 18px | 1.17 | -0.45px | `--text-heading` |
| heading-lg | 24px | 1.11 | -0.6px | `--text-heading-lg` |
| display | 42px | 1.08 | -1.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 100 | 100px | `--spacing-100` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 7px |
| default | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(55, 55, 55) 0px 0px 0px 1px` | `--shadow-subtle` |
| subtle-2 | `rgb(55, 55, 55) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(80, 80, 80) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgb(149, 149, 149) 0px 0px 0px 1px inset` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 15px
- **Element gap:** 5px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, conveying primary interaction.

Filled button with Cloud White (#ffffff) background and Midnight Ink (#080808) text. Corner radius is 10px. Padding is 0px vertical, 20px horizontal.

### Secondary Filled Button
**Role:** Secondary action button, providing a less prominent, yet active, option.

Filled button with Deep Shadow (#373737) background and Cloud White (#ffffff) text. Corner radius is 10px. Padding is 0px vertical, 25px horizontal.

### Ghost Button
**Role:** Minimal interaction button, often used for navigation links or less critical actions.

Transparent background with Cloud White (#ffffff) text. No border, no radius. Padding is 0px for a text-link appearance.

### Input Field
**Role:** Text input areas for forms.

Uses Stormy Night (#1e1e1e) background with Cloud White (#ffffff) text. Has a 12px border radius. Padding is 0px vertical, 20px horizontal.

### Content Card
**Role:** Container for distinct content blocks, especially for visual assets or listings.

Midnight Ink (#080808) background with Cloud White (#ffffff) text. Features a 12px border radius and a 1px inset border of Deep Shadow (#373737).

### Tag / Category Label
**Role:** Small descriptive labels for categorization.

Uses Stormy Night (#1e1e1e) as background and Ash Gray (#959595) for text, with 7px border radius and 15px padding. Text is typically in the smallest `Inter` font size.

## Do's and Don'ts

### Do
- Use Midnight Ink (#080808) for card backgrounds and large section backgrounds to maintain the deep dark theme.
- Apply Cloud White (#ffffff) for all primary text content and main headings to ensure maximum contrast and readability.
- Utilize 15px padding for all content cards to give visual elements sufficient breathing room within their containers.
- Employ the `Inter` font with a weight of 500 for headlines and emphasized text, and 400 for body copy.
- Ensure all interactive elements, like links and active borders, use Electric Blue (#1d9bf0) for consistent visual feedback.
- Use a 10px `radius` for standard buttons, cards, and input fields to maintain a soft, approachable geometry.
- Implement the 1px inset border of Deep Shadow (#373737) or Charcoal Border (#505050) on cards and interactive elements for subtle material depth instead of traditional drop shadows.

### Don't
- Avoid using light backgrounds for major sections; the system relies on a dark canvas for visual impact.
- Do not introduce new saturated colors outside of accent uses without clear functional justification.
- Refrain from using heavy drop shadows; prefer subtle inset borders for defining UI elements.
- Do not deviate from the `Inter` font family without a strong brand-specific reason.
- Avoid arbitrary variations in border radius; stick to the established 10px and 7px for consistent aesthetic.
- Do not make buttons or links visually indistinct from surrounding text; always apply the appropriate color or background for interactivity.
- Do not use generic spacing values; adhere to the established compact system with 5px element gaps and 15px card padding.

## Imagery

The site uses a dynamic mix of product screenshots, abstract 3D renders, and occasionally pixel-art-like visuals. These images are often contained within cards with rounded corners, acting as showcases for the 'tools' being offered. The imagery is highly stylized and vibrant, creating a strong contrast against the dark UI. Icons are typically filled, in monochrome white or occasionally in a brand accent color, and are functional rather than decorative, with a clear, minimal stroke-like appearance when outlined. Graphics are primarily demonstrative, illustrating the capabilities of the software, and images occupy a significant portion of the visual space within content sections.

## Layout

The page uses a full-bleed dark background with content generally constrained to a centered, implicit max-width. The hero section features a large, centered headline and subtext, followed by a prominently placed primary action button. Content rhythm is established by continuous vertical flow without distinct alternating bands. A prominent grid layout (3 or 4 columns) effectively showcases product features or card-based content. The navigation is a sticky top bar with logo, prominent 'Sign in' and 'Start for free' buttons, maintaining presence throughout scrolling. Content is presented in a modern, symmetrical stack, allowing the vibrant visual assets to take center stage.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #080808
border: #959595
accent: #1d9bf0
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ffffff background, #080808 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Content Card for a template showcase: background is Midnight Ink (#080808) with a 1px inset border of Deep Shadow (#373737) and a 12px border radius. Inside, place a title 'Modern Forms' in Cloud White (#ffffff) using `Inter` 16px, weight 500. Add two Tag / Category Labels below the title with Ash Gray (#959595) text on Stormy Night (#1e1e1e) background, 7px radius.

## Similar Brands

- **Framer** — Dark UI with vibrant accents used for interactive elements and brand elements, strong focus on presenting creative content in grids.
- **Linear** — High-contrast dark mode with crisp typography, subtle gray scale for surface differentiation, and minimal use of color for functional accents.
- **Render** — Focus on developer tooling with a dark, architectural UI, using subtle borders and elevation rather than heavy shadows to define elements.
- **Supabase** — Clean, functional dark theme that foregrounds code and content, using tight typography and minimal visual clutter.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #080808;
  --color-stormy-night: #1e1e1e;
  --color-deep-shadow: #373737;
  --color-ash-gray: #959595;
  --color-cloud-white: #ffffff;
  --color-charcoal-border: #505050;
  --color-electric-blue: #1d9bf0;
  --color-vibrant-gradient: #b8ff45;
  --gradient-vibrant-gradient: linear-gradient(97.25deg, rgb(184, 255, 69) 3%, rgb(255, 203, 69) 22%, rgb(255, 0, 184) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.25;
  --tracking-body: -0.35px;
  --text-heading: 18px;
  --leading-heading: 1.17;
  --tracking-heading: -0.45px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.6px;
  --text-display: 42px;
  --leading-display: 1.08;
  --tracking-display: -1.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 15px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;

  /* Named Radii */
  --radius-small: 7px;
  --radius-default: 10px;

  /* Shadows */
  --shadow-subtle: rgb(55, 55, 55) 0px 0px 0px 1px;
  --shadow-subtle-2: rgb(55, 55, 55) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(80, 80, 80) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgb(149, 149, 149) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #080808;
  --color-stormy-night: #1e1e1e;
  --color-deep-shadow: #373737;
  --color-ash-gray: #959595;
  --color-cloud-white: #ffffff;
  --color-charcoal-border: #505050;
  --color-electric-blue: #1d9bf0;
  --color-vibrant-gradient: #b8ff45;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.25;
  --tracking-body: -0.35px;
  --text-heading: 18px;
  --leading-heading: 1.17;
  --tracking-heading: -0.45px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.6px;
  --text-display: 42px;
  --leading-display: 1.08;
  --tracking-display: -1.05px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;

  /* Shadows */
  --shadow-subtle: rgb(55, 55, 55) 0px 0px 0px 1px;
  --shadow-subtle-2: rgb(55, 55, 55) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(80, 80, 80) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgb(149, 149, 149) 0px 0px 0px 1px inset;
}
```
