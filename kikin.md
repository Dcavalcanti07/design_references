# Kikin — Style Reference
> Forest floor and neon moss: a deep, organic dark-mode canvas lit by electric-green functional elements.

**Theme:** dark

Kikin employs a rugged, eco-conscious aesthetic, juxtaposing a deep, forest-like dark canvas with sharp, assertive typography. Vivid green accents punctuate the UI as functional highlights, while off-white surfaces provide a grounding contrast for content. The system balances a comfortable density with ample breathing room, creating a feeling of spaciousness and clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canvas | `#122315` | `--color-forest-canvas` | Primary page background, text on light surfaces, deep UI elements. This deep green-gray establishes the earthy, dark theme |
| Soft Mist | `#f3ede4` | `--color-soft-mist` | Secondary background for content sections, card surfaces, and subtle text contrast on dark backgrounds. Provides a warm, paper-like feel |
| Deep Graphite | `#333333` | `--color-deep-graphite` | Primary text on light backgrounds, strong borders, and prominent iconography. Creates a sharp contrast against Soft Mist |
| Subtle Ash | `#566053` | `--color-subtle-ash` | Tertiary text for headings on light backgrounds, muted borders, and subtle background shading. A desaturated green-gray that blends with the theme |
| Electric Moss | `#55dd4a` | `--color-electric-moss` | Primary action buttons, active states, and critical highlights. This vivid green provides a strong, energetic focal point |
| Fresh Sprout | `#77e46e` | `--color-fresh-sprout` | Outlined button borders and subtle interactive elements. A lighter, slightly muted variant of Electric Moss, used for secondary actions |
| Sky Water | `#73d3eb` | `--color-sky-water` | Occasional decorative accents and background fills, offering a cool counterpoint to the warm green tones |
| Sunburst Gold | `#ffed52` | `--color-sunburst-gold` | Decorative accents and badge elements, used sparingly for visual pop against the dominant greens and darks |
| Slate Border | `#e5e7eb` | `--color-slate-border` | Subtle border colors and dividers on light backgrounds, providing structure without harshness |
| Soft White | `#ffffff` | `--color-soft-white` | Selected link text and UI elements on dark backgrounds for high contrast |
| Muted Black | `#141414` | `--color-muted-black` | Muted text or icon color on light backgrounds, slightly softer than Deep Graphite |

## Tokens — Typography

### Deacon — Display and prominent headings. Its condensed, bold styling with tight letter-spacing gives a direct, impactful voice. · `--font-deacon`
- **Substitute:** Anton, Impact
- **Weights:** 400, 700, 900
- **Sizes:** 14px, 24px, 32px, 58px, 72px, 101px, 137px, 259px
- **Line height:** 0.80, 0.85, 0.90
- **Letter spacing:** -0.0260em at 259px, -0.0210em at 137px, -0.0150em at 101px, -0.0110em at 72px
- **Role:** Display and prominent headings. Its condensed, bold styling with tight letter-spacing gives a direct, impactful voice.

### Graphik — Navigation, body text, and subheadings. Its clean, geometric form provides clarity and modern sensibility, with varied tracking for different sizes. · `--font-graphik`
- **Substitute:** Inter, Montserrat
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 15px, 16px, 24px, 32px
- **Line height:** 1.13, 1.20, 1.25, 1.40, 1.43
- **Letter spacing:** -0.0400em at 32px, -0.0200em at 24px, -0.0100em at 16px, 0.0180em at 12px
- **Role:** Navigation, body text, and subheadings. Its clean, geometric form provides clarity and modern sensibility, with varied tracking for different sizes.

### Arial — Fallback and utilitarian text elements, ensuring broad compatibility. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 14px, 16px, 40px
- **Line height:** 1.25, 1.43
- **Letter spacing:** normal
- **Role:** Fallback and utilitarian text elements, ensuring broad compatibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | 0.018px | `--text-caption` |
| body | 14px | 1.43 | -0.01px | `--text-body` |
| body-lg | 16px | 1.43 | -0.01px | `--text-body-lg` |
| subheading | 24px | 1.25 | -0.02px | `--text-subheading` |
| heading | 32px | 1.25 | -0.04px | `--text-heading` |
| heading-lg | 58px | 0.9 | -0.011px | `--text-heading-lg` |
| display | 72px | 0.85 | -0.011px | `--text-display` |
| display-xl | 101px | 0.8 | -0.015px | `--text-display-xl` |
| display-xxl | 137px | 0.8 | -0.021px | `--text-display-xxl` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 164 | 164px | `--spacing-164` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 20px |
| default | 10px |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call-to-action button for critical actions.

Background: Electric Moss (#55dd4a). Text: Forest Canvas (#122315). Border-radius: 10px. Padding: 9px vertical, 16px horizontal. Font: Graphik, weight 400.

### Secondary Outlined Button
**Role:** Secondary action button, typically for 'Log In' or ghost states.

Background: transparent. Text: Muted Black (#141414) or Soft White (#ffffff). Border: 1px Fresh Sprout (#77e46e). Border-radius: 100% (circular). No explicit padding in raw data, appears as a circular outline without internal text padding.

### Navigation Link
**Role:** Top navigation items.

Text color: Forest Canvas (#122315) or Soft Mist (#f3ede4) depending on background. Font: Graphik, size 14px, weight 400. Hover state likely involves a subtle color change or underline (not explicitly captured).

### Pill Button
**Role:** Small, informational or filter buttons.

Background: Forest Canvas (#122315). Text: Soft Mist (#f3ede4). Border-radius: 20px. Padding: 8px vertical, 15px horizontal. Font: Graphik, weight 400.

### Hero Headline
**Role:** Main page title and impactful messaging.

Font: Deacon. Sizes: 72px on dark background. Text: Soft White (#ffffff) or Electric Moss (#55dd4a). Letter-spacing: -0.011em for sizes around 72px.

### Section Headline
**Role:** Titles for major content sections.

Font: Deacon. Sizes: 58px on Soft Mist background. Text: Deep Graphite (#333333). Letter-spacing: -0.011em for sizes around 58px.

### Body Text
**Role:** Paragraph content and detailed descriptions.

Font: Graphik. Sizes: 16px. Text: Deep Graphite (#333333) on Soft Mist backgrounds, or Soft Mist (#f3ede4) on Forest Canvas backgrounds. Line height: 1.43.

## Do's and Don'ts

### Do
- Use Forest Canvas (#122315) as the default background for hero sections and primary dark-themed content blocks.
- Prioritize Deacon for all prominent headings and display text to maintain the strong, condensed visual voice.
- Apply Electric Moss (#55dd4a) exclusively for primary calls-to-action and active states to ensure visual hierarchy.
- Utilize Soft Mist (#f3ede4) primarily for background surfaces in lighter content sections, contrasting with Forest Canvas.
- Ensure standard button border-radius is 10px, while informational or small functional elements may adopt a 20px pill shape or full circular radius.
- Maintain a comfortable density with element gaps of 10px and card padding of 12px, building on the 4px base unit.
- Implement letter-spacing adjusted per typo-scale step, specifically tighter tracking for larger Deacon headlines and slightly negative tracking for Graphik body text.

### Don't
- Do not use Electric Moss (#55dd4a) for body text or non-interactive decorative elements; reserve it for functional highlights.
- Avoid arbitrary radii values; stick to 10px for standard elements, 20px/circular for specific components, or implied by component type.
- Do not mix Deacon and Graphik in the same sentence or for equivalent typographic roles; maintain clear separation of use cases.
- Do not use #333333 on Forest Canvas (#122315) backgrounds, as contrast will be insufficient.
- Avoid heavy use of Sky Water (#73d3eb) or Sunburst Gold (#ffed52) for large content blocks; they are accent colors for small visual pops.
- Do not introduce new border styles outside of minimal 1px or 3px solids observed, particularly for interactive elements.
- Resist using a truly full-bleed layout; content should remain within a contained area even if the background extends.

## Imagery

The site uses a mix of stylized, geometric illustrations and high-quality product photography. Illustrations feature organic shapes and natural themes (mountains, trees, water), rendered with solid fills and bold outlines in the brand's color palette (Forest Canvas, Electric Moss, Sky Water, Sunburst Gold). These illustrations serve decorative and atmospheric roles, setting an eco-conscious tone. Product photography is typically clean and isolated, showcasing items (e.g., a blue bottle) with water effects in the background, aiming for a fresh and high-end feel. Iconography is primarily filled, simple, and mono-color, often in Forest Canvas against Soft Mist or white against Forest Canvas.

## Layout

The page primarily uses a max-width contained layout for core content. The hero section is full-bleed, Forest Canvas background with a centered, split headline (Soft White and Electric Moss) above a large, atmospheric illustration. Subsequent sections alternate between the dark Forest Canvas and the light Soft Mist backgrounds, creating a clear vertical rhythm. Content often arranges in two-column layouts, typically with text on one side and a visual (illustration or photograph) on the other. A navigation bar with text links and two pill-shaped buttons is sticky at the top. The overall density is comfortable, with generous vertical spacing between sections and clear visual grouping of elements.

## Agent Prompt Guide

Quick Color Reference: 
text: #f3ede4 (on dark) / #333333 (on light)
background: #122315 (dark) / #f3ede4 (light)
border: #e5e7eb
accent: #73d3eb
primary action: #55dd4a (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #55dd4a background, #141414 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Light Content Block: Soft Mist (#f3ede4) background. Section headline 'GOOD FOR THE PLANET. AND YOUR BUSINESS.' in Deacon at 58px, Deep Graphite (#333333), letter-spacing -0.011em. Body text below in Graphik 16px, Deep Graphite (#333333), line height 1.43.
3. Create a Pill Button Example: Forest Canvas (#122315) background. Text 'repayments' in Graphik 15px, Soft Mist (#f3ede4), letter-spacing -0.01em. Radius 20px. Padding 8px vertical, 15px horizontal.

## Similar Brands

- **Wealthsimple** — Uses bold, impactful headings with tight kerning and a limited but strong color palette, often contrasting dark backgrounds with vibrant accents.
- **Fathom Analytics** — Features a strong dark mode with minimalist UI elements, a geometric sans-serif for body text, and a sole bright accent color for CTAs.
- **Stripe (early branding)** — Employs clean, geometric typography and a focus on essential UI elements, contrasting a muted base with strategic, vivid accent colors.
- **Linear** — Dark-themed UI with strong typographic hierarchy, high-contrast text, and a focus on clean, functional components without heavy decoration.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canvas: #122315;
  --color-soft-mist: #f3ede4;
  --color-deep-graphite: #333333;
  --color-subtle-ash: #566053;
  --color-electric-moss: #55dd4a;
  --color-fresh-sprout: #77e46e;
  --color-sky-water: #73d3eb;
  --color-sunburst-gold: #ffed52;
  --color-slate-border: #e5e7eb;
  --color-soft-white: #ffffff;
  --color-muted-black: #141414;

  /* Typography — Font Families */
  --font-deacon: 'Deacon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: 0.018px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.02px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.04px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.011px;
  --text-display: 72px;
  --leading-display: 0.85;
  --tracking-display: -0.011px;
  --text-display-xl: 101px;
  --leading-display-xl: 0.8;
  --tracking-display-xl: -0.015px;
  --text-display-xxl: 137px;
  --leading-display-xxl: 0.8;
  --tracking-display-xxl: -0.021px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-164: 164px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-pill: 20px;
  --radius-default: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canvas: #122315;
  --color-soft-mist: #f3ede4;
  --color-deep-graphite: #333333;
  --color-subtle-ash: #566053;
  --color-electric-moss: #55dd4a;
  --color-fresh-sprout: #77e46e;
  --color-sky-water: #73d3eb;
  --color-sunburst-gold: #ffed52;
  --color-slate-border: #e5e7eb;
  --color-soft-white: #ffffff;
  --color-muted-black: #141414;

  /* Typography */
  --font-deacon: 'Deacon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: 0.018px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.02px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.04px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.011px;
  --text-display: 72px;
  --leading-display: 0.85;
  --tracking-display: -0.011px;
  --text-display-xl: 101px;
  --leading-display-xl: 0.8;
  --tracking-display-xl: -0.015px;
  --text-display-xxl: 137px;
  --leading-display-xxl: 0.8;
  --tracking-display-xxl: -0.021px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-164: 164px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
}
```
