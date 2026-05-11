# Peppermint — Style Reference
> Midnight festival, playful neon

**Theme:** dark

Peppermint uses a vibrant, playful dark theme with deep indigo as its canvas, punctuated by an energetic palette of pastel pink, teal, and yellow for accents and illustrations. Typography is bold and highly condensed for display, contrasting with a more comfortable sans-serif for body text, creating a dynamic visual hierarchy. Components often feature large border-radii and generous padding, contributing to a friendly, approachable feel within the dark mode context.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Indigo | `#0a1d4b` | `--color-deep-indigo` | Page backgrounds, primary accent for borders and text on light surfaces. Serves as a primary action background when needed |
| Warm Vanilla | `#fcf6ea` | `--color-warm-vanilla` | Text on dark backgrounds, primary surface accent for borders, outlines for active elements |
| Powder Snow | `#ffffff` | `--color-powder-snow` | Primary text on dark backgrounds, button text, decorative icon fills |
| Ash Gray | `#474b60` | `--color-ash-gray` | Muted text, secondary borders, hint text in forms |
| Lavender Bloom | `#9c8bf9` | `--color-lavender-bloom` | Primary action button background, header background on dark sections |
| Sugared Almond | `#faedd2` | `--color-sugared-almond` | Secondary background, faint surface accent on lighter cards for visual interest |
| Mint Glaze | `#68dacb` | `--color-mint-glaze` | Decorative illustration accents, card backgrounds for feature highlights |
| Azure Haze | `#bcdff0` | `--color-azure-haze` | Decorative illustration strokes and outlines |
| Starry Night | `#162d67` | `--color-starry-night` | Secondary card backgrounds, slightly darker variant of Deep Indigo for layered surfaces |
| Coral Pink | `#ffb8d9` | `--color-coral-pink` | Decorative illustration strokes for vibrancy |
| Blush Rose | `#ffe9f4` | `--color-blush-rose` | Card backgrounds on lighter sections, providing a soft, engaging surface |
| Sunny Marigold | `#fbc333` | `--color-sunny-marigold` | Decorative illustration strokes and highlights |

## Tokens — Typography

### Excon — Headlines and display text — its condensed, heavy form and negative letter-spacing create a bold, impactful, and modern statement. · `--font-excon`
- **Substitute:** Anton, Impact
- **Weights:** 400, 500, 700
- **Sizes:** 24px, 25px, 45px, 48px, 50px, 60px, 90px, 128px, 130px, 151px, 274px
- **Line height:** 0.87, 0.92, 1.00, 1.09
- **Letter spacing:** -0.1000em at 274px, -0.0550em at 130px, -0.0510em at 128px, -0.0460em at 90px, -0.0440em at 60px, -0.0400em at 50px, -0.0390em at 48px
- **Role:** Headlines and display text — its condensed, heavy form and negative letter-spacing create a bold, impactful, and modern statement.

### Generalsans — Body text, links, and buttons — providing legibility and a friendly feel that balances the strong display font. · `--font-generalsans`
- **Substitute:** Inter, Eina01
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.14, 1.22, 1.25, 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Body text, links, and buttons — providing legibility and a friendly feel that balances the strong display font.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.22 | — | `--text-subheading` |
| heading-sm | 24px | 1.09 | -0.6px | `--text-heading-sm` |
| heading | 48px | 1 | -1.9px | `--text-heading` |
| heading-lg | 60px | 0.92 | -2.64px | `--text-heading-lg` |
| display | 130px | 0.87 | -7.15px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 27 | 27px | `--spacing-27` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 38 | 38px | `--spacing-38` |
| 40 | 40px | `--spacing-40` |
| 42 | 42px | `--spacing-42` |
| 50 | 50px | `--spacing-50` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| forms | 16px |
| accents | 36px |
| buttons | 48px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action.

Background: Lavender Bloom (#9c8bf9). Text: Powder Snow (#ffffff), Generalsans, weight 400. Radius: 48px (pill shape). Padding: 16px vertical, 20px horizontal.

### Hero Action Button
**Role:** Large, prominent button for hero sections.

Background: Deep Indigo (#0a1d4b). Text: Warm Vanilla (#faedd2), Generalsans, weight 400. Radius: 100px (oval). Padding: 36px vertical, 100px horizontal.

### FAQ Accordion Card
**Role:** Container for frequently asked questions, with interactive state.

Background: Warm Vanilla (#faedd2). Radius: 24px. Padding: 20px top, 38px horizontal, 36px bottom.

### Feature Card (Blush Rose)
**Role:** Highlighting key features with a soft, distinct background.

Background: Blush Rose (#ffe9f4). Radius: 24px. Padding: 20px top, 38px horizontal, 36px bottom.

### Illustrative Feature Card (Mint Glaze)
**Role:** Card acting as a canvas for illustrations or imagery.

Background: Mint Glaze (#68dacb). Radius: 20px. Padding and shadows are often zero, implying content (images) fills the space.

## Do's and Don'ts

### Do
- Prioritize Deep Indigo (#0a1d4b) for main backgrounds and primary text on light sections.
- Use Excon for all headlines and display text, applying the defined negative letter-spacing for impact.
- Apply 48px border-radius to all primary action buttons, creating a distinct pill shape.
- Use Lavender Bloom (#9c8bf9) exclusively for active state indicators and primary button fills.
- Employ Generous horizontal padding of 20px for buttons and 38px for cards to maintain an airy feel.
- Ensure all body text uses Generalsans, weight 400, with normal letter-spacing for readability.
- Layer surfaces by using Starry Night (#162d67) as a slightly elevated background over Deep Indigo (#0a1d4b).

### Don't
- Avoid using purely achromatic grays; prefer those with a subtle warm tint like Ash Gray (#474b60) or Warm Vanilla (#faedd2).
- Do not break the established type scale or letter-spacing of Excon headlines; their unique tracking is a core brand element.
- Do not use saturated colors for large text blocks; reserve them for accents, decorative elements, or small labels.
- Avoid sharp corners; ensure all interactive elements and cards use a minimum of 20px border-radius.
- Do not introduce strong drop shadows; the design relies on color contrast and layered surfaces for depth instead.
- Do not use the vibrant accent colors (#ffb8d9, #fbc333) as primary text or background colors; they are for decorative strokes and highlights.
- Avoid dense, information-heavy layouts; allow ample spacing (minimum 10px element gap) between UI elements.

## Imagery

This system features highly stylized, dimensional illustrations with organic, flowing shapes and vibrant, mixed color palettes (Coral Pink, Mint Glaze, Sunny Marigold). Images are typically contained within cards with rounded corners or integrated into abstract hero backgrounds, acting as both decorative atmosphere and explanatory content. They feature bold outlines and filled shapes, often depicting hands interacting with digital devices or abstract financial concepts. Iconography is primarily filled, with varying stroke weights, and often adopts the brand's accent colors for visual pop.

## Layout

The page primarily uses a full-bleed dark background with content centered and constrained within a comfortable width, though no fixed max-width is indicated globally. The hero section is full-bleed, featuring a large, centered headline and a prominent Call to Action, with abstract illustrative elements extending beyond typical content bounds. Section rhythm varies; predominantly dark sections are visually divided by large, colorful illustrative areas. Content is arranged in alternating text-left/image-right or text/illustration stacks, with a common use of 3-column card grids for features. Vertical spacing is generous, creating a spacious and comfortable browsing experience. Navigation is handled by a minimal sticky header with a centered logo and a single ghost-style action button.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #0a1d4b
border: #fcf6ea
accent: #9c8bf9
primary action: #9c8bf9 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #9c8bf9 background, #474b60 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a Feature Card: Blush Rose (#ffe9f4) background, 24px radius, 20px top padding, 38px horizontal padding, 36px bottom padding. Title 'Instant Payouts' using Excon SemiBold at 24px, Deep Indigo (#0a1d4b). Body text 'Funds available immediately' using Generalsans Regular at 16px, Ash Gray (#474b60).
3. Create an Accordion Item for an FAQ section: Warm Vanilla (#faedd2) background, 24px radius. Title 'How secure is Peppermint?' using Generalsans Semibold at 18px, Deep Indigo (#0a1d4b). Body text underneath (when open) using Generalsans Regular at 16px, Ash Gray (#474b60).

## Similar Brands

- **Stripe** — Dark UI with bold typography and illustrative, colorful accents for product features.
- **Ramp** — Modern fintech aesthetic, combining dark backgrounds with a vibrant accent color and strong, impactful headlines.
- **Linear** — Highly functional dark-mode interface with carefully selected accent colors for interactive elements and strong typographic hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-indigo: #0a1d4b;
  --color-warm-vanilla: #fcf6ea;
  --color-powder-snow: #ffffff;
  --color-ash-gray: #474b60;
  --color-lavender-bloom: #9c8bf9;
  --color-sugared-almond: #faedd2;
  --color-mint-glaze: #68dacb;
  --color-azure-haze: #bcdff0;
  --color-starry-night: #162d67;
  --color-coral-pink: #ffb8d9;
  --color-blush-rose: #ffe9f4;
  --color-sunny-marigold: #fbc333;

  /* Typography — Font Families */
  --font-excon: 'Excon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-generalsans: 'Generalsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.09;
  --tracking-heading-sm: -0.6px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.9px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -2.64px;
  --text-display: 130px;
  --leading-display: 0.87;
  --tracking-display: -7.15px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-27: 27px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-50: 50px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-forms: 16px;
  --radius-accents: 36px;
  --radius-buttons: 48px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-indigo: #0a1d4b;
  --color-warm-vanilla: #fcf6ea;
  --color-powder-snow: #ffffff;
  --color-ash-gray: #474b60;
  --color-lavender-bloom: #9c8bf9;
  --color-sugared-almond: #faedd2;
  --color-mint-glaze: #68dacb;
  --color-azure-haze: #bcdff0;
  --color-starry-night: #162d67;
  --color-coral-pink: #ffb8d9;
  --color-blush-rose: #ffe9f4;
  --color-sunny-marigold: #fbc333;

  /* Typography */
  --font-excon: 'Excon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-generalsans: 'Generalsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.09;
  --tracking-heading-sm: -0.6px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.9px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -2.64px;
  --text-display: 130px;
  --leading-display: 0.87;
  --tracking-display: -7.15px;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-27: 27px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-50: 50px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-full: 48px;
  --radius-full-2: 100px;
}
```
