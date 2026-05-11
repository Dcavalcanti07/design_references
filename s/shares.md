# Shares — Style Reference
> White-canvas violet-accent structured finance

**Theme:** light

Shares employs a polished, product-centric visual language dominated by a clean white canvas. Its core identity is built around compact, well-defined typographic hierarchy with a distinct violet accent acting as the primary interactive cue. Product surfaces are typically soft gray cards, rounded at generous radii, giving a friendly but structured feel to the data-rich financial tools depicted. The overall impression is one of organized competence and technological clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated element backgrounds, primary buttons, major text |
| Ink Black | `#1f1f1f` | `--color-ink-black` | Primary heading text, strong body text, dark mode canvas, button text on light buttons |
| Carbon Gray | `#333333` | `--color-carbon-gray` | Secondary text, iconography, subtle borders |
| Cloud Gray | `#f6f6f6` | `--color-cloud-gray` | Card backgrounds, section separators, secondary background surfaces |
| Steel Gray | `#888888` | `--color-steel-gray` | Muted body text, helper text, ghost button text |
| Stone Gray | `#b0b0b0` | `--color-stone-gray` | Input borders, subtle dividers, inactive elements |
| Silver Mist | `#e7e7e7` | `--color-silver-mist` | Hairline borders, decorative image borders |
| Slate Gray | `#5d5d5d` | `--color-slate-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Shares Violet | `#594ff4` | `--color-shares-violet` | Calls to action, interactive elements, primary links, brand accents for icons and borders |

## Tokens — Typography

### Aeonik — Primary typeface for all headings, body text, UI elements, and links. Its slightly wide, geometric sans-serif style provides a modern, confident tone, especially with the subtle but consistent boosted letter-spacing. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 500, 700
- **Sizes:** 14px, 15px, 16px, 17px, 18px, 20px, 26px, 36px, 56px, 72px
- **Line height:** 1.00, 1.05, 1.10, 1.15, 1.18, 1.20, 1.33, 1.43, 1.50
- **Letter spacing:** 0.0750em
- **Role:** Primary typeface for all headings, body text, UI elements, and links. Its slightly wide, geometric sans-serif style provides a modern, confident tone, especially with the subtle but consistent boosted letter-spacing.

### Rubik — Used sparingly for specific informational text contexts, likely for labels or small data entries. · `--font-rubik`
- **Substitute:** Roboto
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for specific informational text contexts, likely for labels or small data entries.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.075px | `--text-caption` |
| body | 16px | 1.5 | 0.075px | `--text-body` |
| subheading | 20px | 1.43 | 0.075px | `--text-subheading` |
| heading-sm | 26px | 1.33 | 0.075px | `--text-heading-sm` |
| heading | 36px | 1.18 | 0.075px | `--text-heading` |
| heading-lg | 56px | 1.1 | 0.075px | `--text-heading-lg` |
| display | 72px | 1.05 | 0.075px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 36px |
| small | 4px |
| inputs | 16px |
| buttons | 99px |
| largeFeatures | 60px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.12) 0px 0px 60px -13px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1224px
- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Violet Button
**Role:** Main call to action button.

Filled with Shares Violet (#594ff4), text in Canvas White (#f2f2f2 from data, inferring exact match to white for contrast). Features a generous 99px border radius for a pill shape and 16px vertical, 24px horizontal padding. Letter-spacing follows Aeonik's 0.0750em.

### Light Ghost Button
**Role:** Secondary action or navigation item on light backgrounds.

Transparent background with text and border in Carbon Gray (#5d5d5d or #888888 from data). Features a pill-shaped 99px border radius for menu items and 12px vertical, 32px horizontal padding.

### Text Link Button
**Role:** Minimalist action trigger, often for 'learn more' or navigation.

Completely transparent background, text in Carbon Gray or Slate Gray (#333333 or #5d5d5d). No explicit border radius, effectively square, with 16px vertical and 24px horizontal padding. Letter-spacing follows Aeonik's 0.0750em.

### Product Feature Card
**Role:** Showcasing distinct product features or information blocks.

Background in Cloud Gray (#f6f6f6), with a 36px border radius (often larger 60px for prominent examples). Internal padding is 32px all around, using Aeonik for text and hierarchy.

### FAQ Accordion Card
**Role:** Expandable content sections for frequently asked questions.

Background in Cloud Gray (#f6f6f6), with a 24px border radius. Internal padding is 32px all around for compact questions. Text uses Aeonik.

### Informational Strip
**Role:** Thin, feature summaries or content blocks.

Background in Cloud Gray (#f6f6f6), with a 30px border radius. Padding is 24px all around. Used for smaller content sections like 'Made in France' blocks.

### Navigation Link
**Role:** Primary navigation elements in the header.

Text in Slate Gray (#5d5d5d). No background or explicit radius, relies on typographic spacing. Padding of 16px vertical, 24px horizontal.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the primary page background, establishing a clean, expansive foundation.
- Use Shares Violet (#594ff4) exclusively for primary calls to action and critical interactive elements, ensuring high contrast and immediate recognition.
- Always apply a 99px border radius to buttons for a consistent pill-shaped aesthetic.
- Utilize Cloud Gray (#f6f6f6) for distinct content blocks and card backgrounds, differentiating them from the main canvas.
- Apply Aeonik at weight 500 or 700 for all textual content, maintaining the boosted 0.0750em letter-spacing.
- Structure layout with a 1224px max-width, centrally aligned, and apply 48px vertical section gaps.
- Employ a subtle shadow rgba(0, 0, 0, 0.12) 0px 0px 60px -13px only for product imagery or elevated UI elements to create depth without heaviness.

### Don't
- Avoid using multiple chromatic colors; Shares Violet (#594ff4) is the sole accent.
- Do not use sharp 0px border radii on interactive elements or cards, as the design system favors generous rounding.
- Refrain from heavy, layered shadows; transparency and minimal depth are preferred.
- Do not deviate from the Aeonik typeface unless explicitly for small data points with Rubik.
- Avoid text colors lighter than Steel Gray (#888888) for body copy to maintain readability.
- Do not introduce gradients unless they are subtle and follow existing brand accent guidelines (none detected).
- Limit horizontal padding on content blocks to 24-32px to maintain a spacious, uncluttered feel within the max-width container.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background, base layer. |
| 2 | Cloud Gray | `#f6f6f6` | Content cards, section backgrounds, subtle elevation from the canvas. |

## Elevation

- **Image:** `rgba(0, 0, 0, 0.12) 0px 0px 60px -13px`

## Imagery

This design system uses product screenshots and abstract UI representations to showcase its technology. The imagery features product interfaces within device mockups (phone, desktop app windows) with soft, blue-tinted shadows, often arranged in an overlapping, slightly tilted manner to create a sense of dynamism. Icons are monochrome, often in Carbon Gray, and have a clear, outlined style with consistent stroke weight. The focus is on clean, functional UI visuals rather than lifestyle photography or abstract illustrations, reinforcing the tech-focused brand.

## Layout

The site employs a max-width, centrally contained page model (1224px) for most content, with a clear full-bleed hero section at the top. The hero often features a large, centered headline over a light background. Section rhythm is consistent, primarily using vertical spacing of 48px to separate blocks, with alternating Cloud Gray (#f6f6f6) and Canvas White (#ffffff) backgrounds. Content is often arranged in 2-column layouts (text left, image/product visual right) or centered stacks for feature lists and FAQs. Navigation is a sticky top bar with brand logo, primary calls-to-action, and subtle text links.

## Agent Prompt Guide

Quick Color Reference:
text: #333333
background: #ffffff
border: #e7e7e7
accent: #594ff4
primary action: #594ff4 (filled action)

Example Component Prompts:
1. Create a Hero Block: Full width. Headline 'The next generation of investing tech' 72px Aeonik weight 700 Ink Black (#1f1f1f), letter-spacing 0.075em, centered. Subtext 'Powered by cutting-edge technology, we provide individuals, wealth professionals and institutions with seamless investing products' 18px Aeonik weight 500 Steel Gray (#888888), letter-spacing 0.075em, centered. Below, a Primary Violet Button 'Get started' with Canvas White (#f2f2f2 from data, inferring precise fit to #ffffff) text, 99px radius, 16px vertical, 24px horizontal padding.
2. Create a Primary Action Button: #594ff4 background, #f6f6f6 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create an FAQ Accordion Item: Cloud Gray (#f6f6f6) background, 24px border radius. Padding 32px all sides. Text 'What is Shares?' 18px Aeonik weight 500 Ink Black (#1f1f1f), letter-spacing 0.075em. Right-aligned icon (placeholder for now).

## Similar Brands

- **Linear** — Shares aligns with Linear's use of a very clean, neutral-heavy canvas with a single vibrant accent color for interaction and a focus on precise typography.
- **Framer** — Similar preference for generous rounded corners on cards and buttons, bright primary page background, and a sharp, modern sans-serif typeface with tight tracking.
- **Revolut Business** — Shares shares a functional, product-showcasing visual approach with clean UI elements, subtle elevation, and a consistent branded accent color, common in modern fintech.
- **Stripe** — Follows a similar pattern of a dominant white background, clear typographic hierarchy, and limited color palette with one strong accent color to guide user attention through complex financial information.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1f1f1f;
  --color-carbon-gray: #333333;
  --color-cloud-gray: #f6f6f6;
  --color-steel-gray: #888888;
  --color-stone-gray: #b0b0b0;
  --color-silver-mist: #e7e7e7;
  --color-slate-gray: #5d5d5d;
  --color-shares-violet: #594ff4;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rubik: 'Rubik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.075px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.075px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: 0.075px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: 0.075px;
  --text-heading: 36px;
  --leading-heading: 1.18;
  --tracking-heading: 0.075px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.075px;
  --text-display: 72px;
  --leading-display: 1.05;
  --tracking-display: 0.075px;

  /* Typography — Weights */
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
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1224px;
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 36px;
  --radius-full: 50px;
  --radius-full-2: 60px;
  --radius-full-3: 99px;

  /* Named Radii */
  --radius-cards: 36px;
  --radius-small: 4px;
  --radius-inputs: 16px;
  --radius-buttons: 99px;
  --radius-largefeatures: 60px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 0px 60px -13px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-cloud-gray: #f6f6f6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #1f1f1f;
  --color-carbon-gray: #333333;
  --color-cloud-gray: #f6f6f6;
  --color-steel-gray: #888888;
  --color-stone-gray: #b0b0b0;
  --color-silver-mist: #e7e7e7;
  --color-slate-gray: #5d5d5d;
  --color-shares-violet: #594ff4;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rubik: 'Rubik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.075px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.075px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: 0.075px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: 0.075px;
  --text-heading: 36px;
  --leading-heading: 1.18;
  --tracking-heading: 0.075px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.075px;
  --text-display: 72px;
  --leading-display: 1.05;
  --tracking-display: 0.075px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 36px;
  --radius-full: 50px;
  --radius-full-2: 60px;
  --radius-full-3: 99px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 0px 60px -13px;
}
```
