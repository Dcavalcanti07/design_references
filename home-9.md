# Home — Style Reference
> Vintage paper and playful accents.

**Theme:** light

Airtree uses a warm, vintage-inspired aesthetic defined by its dominant off-white background and deep, almost black, text. Unexpectedly bright, vivid yellow is reserved for high-visibility accents, creating an impression of understated confidence with flashes of playful energy. Typography combines a structured sans-serif with a more expressive, high-contrast display serif. The visual system feels grounded and art-directed, avoiding harshness with rounded forms and a subtle, almost paper-like surface quality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greige Canvas | `#f7f6e3` | `--color-greige-canvas` | Page backgrounds, card surfaces, ghost button borders, muted helper text |
| Charcoal Ink | `#262d29` | `--color-charcoal-ink` | Primary text, button text, main borders, card backgrounds. Its deep, near-black tone provides strong contrast against the Greige Canvas |
| Vivid Yellow | `#ffff48` | `--color-vivid-yellow` | Primary action backgrounds, highlights, and functional accents — used to draw immediate attention |

## Tokens — Typography

### Suisseintl — General UI text, navigation, body copy, and secondary headings. Its structured, clear nature provides readability across various contexts. · `--font-suisseintl`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 13px, 14px, 16px, 19px, 21px, 33px, 42px
- **Line height:** 1.00, 1.15
- **Letter spacing:** normal
- **Role:** General UI text, navigation, body copy, and secondary headings. Its structured, clear nature provides readability across various contexts.

### Suisseintl Book — Used for input text and some link text, a lighter variant emphasizing clarity. · `--font-suisseintl-book`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 13px, 28px
- **Line height:** 1.00, 1.15
- **Letter spacing:** normal
- **Role:** Used for input text and some link text, a lighter variant emphasizing clarity.

### Prody — Primary headings and display text. Its distinct, higher-contrast forms add an art-directed and editorial feel to key messages. · `--font-prody`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 42px, 131px
- **Line height:** 1.00, 1.15
- **Letter spacing:** normal
- **Role:** Primary headings and display text. Its distinct, higher-contrast forms add an art-directed and editorial feel to key messages.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.15 | — | `--text-caption` |
| body | 16px | 1.15 | — | `--text-body` |
| subheading | 19px | 1.15 | — | `--text-subheading` |
| heading | 33px | 1.15 | — | `--text-heading` |
| heading-lg | 42px | 1 | — | `--text-heading-lg` |
| display | 131px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 28 | 28px | `--spacing-28` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 37.44px |
| inputs | 8.424px |
| buttons | 18.72px |
| general | 8.424px |

### Layout

- **Section gap:** 75px
- **Card padding:** 37px
- **Element gap:** 9px

## Components

### Ghost Button
**Role:** Secondary action or navigation link.

Transparent background, Charcoal Ink text (#262d29), and a 1px solid border in Charcoal Ink. Border radius of 18.72px. No explicit padding mentioned, but context suggests minimal.

### Primary Action Button
**Role:** Call to action.

Filled with Vivid Yellow (#ffff48) background, Charcoal Ink text (#262d29). Border radius of 8.424px. Padding: 12.168px vertical, 14.976px horizontal.

### Text Input (Outline)
**Role:** User input fields.

Transparent background, Greige Canvas text (#f7f6e3), Charcoal Ink border (#262d29) at 1px solid. Border radius of 8.424px. Padding: 8.424px vertical, 12.168px horizontal.

### Content Card (Full-width)
**Role:** Informational container for images, descriptions, or embedded content.

Transparent background, no border, no shadow. Padding: 37.44px on all sides. Used for sections that integrate into the main page flow.

### Content Card (Charcoal)
**Role:** Elevated informational container.

Charcoal Ink background (#262d29), no border, no shadow. Border radius of 37.44px. No explicit padding provided in data.

### Navigation Arrows
**Role:** UI controls for carousels or navigaton.

Round button with a 18.72px border radius. Transparent background, Charcoal Ink border (#262d29) and icon. Minimal padding.

## Do's and Don'ts

### Do
- Prioritize Greige Canvas (#f7f6e3) for dominant background areas, even over pure white.
- Use Charcoal Ink (#262d29) for all primary text and main structural borders to maintain visual depth.
- Reserve Vivid Yellow (#ffff48) for critical call-to-action buttons and subtle highlights to maximize its impact.
- Apply Suisseintl for body and general interface text, ensuring readability with its clear, structured forms.
- Use Prody exclusively for large, impactful headlines to create a distinct, art-directed aesthetic.
- Ensure all interactive elements and cards use rounded corners, with 37.44px for larger cards and 18.72px for buttons/smaller cards.
- Maintain a spacious rhythm between content blocks, using 75px as the standard section gap.

### Don't
- Do not introduce new saturated primary colors; only the Vivid Yellow and brand orange (if it appears in other contexts) should be used.
- Avoid sharp corners on any UI elements; all interactive and container components should have a radius from the defined token set.
- Do not use dark backgrounds unless specifically for Charcoal Ink (#262d29) cards, otherwise default to Greige Canvas (#f7f6e3).
- Do not use Prody for body text or small captions; its expressive nature is intended for display purposes only.
- Do not use generic system fonts; always specify Suisseintl or Prody for all textual elements.
- Avoid heavy drop shadows or strong elevation; the design relies on subtle contrasts and rounded forms for visual separation.
- Do not deviate from the defined spacing units; use 9px for element gaps and 37px for card padding to maintain density.

## Imagery

This site features a mix of high-quality, authentic photography and abstract, organic graphic elements. Photography is lifestyle-oriented, often showing groups of people in a natural or professional setting, usually rich in natural light but with a slightly desaturated, warm cast. Imagery is typically contained within rounded cards (37.44px radius) or used as background elements, sometimes with a full-bleed application. Abstract graphics are characterized by organic shapes, specifically large, circular, vivid orange blobs, which act purely as decorative, playful accents, breaking up the otherwise grounded palette. Icons, like the nav arrows, are monochrome, outlined, and sparse in detail. The density leans towards a balanced mix of imagery and text, with visuals framing the content rather than overwhelming it.

## Layout

The page primarily uses a max-width contained layout, allowing for focused content within a central column. The hero section is full-bleed with a subtle gradient background fading from light blue to a warm sandy tone, hosting a large, centered headline and playful orange graphic elements. Subsequent sections often feature alternating two-column layouts of text and visuals, or centered text blocks. Card grids are utilized for features, often with 2-3 columns. Vertical rhythm is established through consistent section gaps, creating a spacious and unhurried feel. Navigation is a minimalist top bar, featuring right-aligned text links and a ghost button, with a sticky behavior indicating its persistence.

## Agent Prompt Guide

### Quick Color Reference
text: #262d29
background: #f7f6e3
border: #262d29
accent: #ffff48
primary action: #ffff48 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section with a centered headline: 'We are tomorrow's tech', using Prody at 131px (size) weight 400, #262d29. Below it, add a ghost button 'Learn More' using Suisseintl at 16px weight 400, #262d29 text, with a 1px #262d29 border, and 18.72px radius.
2. Design a feature card: Charcoal Ink background (#262d29), 37.44px radius, with a Suisseintl Book 28px weight 400 heading in Greige Canvas (#f7f6e3) and a Suisseintl 16px weight 400 body in Greige Canvas (#f7f6e3). Use 37px card padding.
3. Create a primary call-to-action button: 'Get Started Today' with Vivid Yellow background (#ffff48), Suisseintl 16px weight 400 text in Charcoal Ink (#262d29), 8.424px radius, 12.168px vertical padding, 14.976px horizontal padding.
4. Design an input field: transparent background, Greige Canvas text (#f7f6e3), 1px solid Charcoal Ink border (#262d29), 8.424px radius, 8.424px vertical padding, 12.168px horizontal padding. The placeholder text should also be Greige Canvas (#f7f6e3).

## Similar Brands

- **Figma** — Shares a modern, minimalist use of space and clear functional typography, though Airtree's palette is warmer.
- **Webflow** — Exhibits a similar sophisticated, editorial typography approach with a mix of structured sans-serifs and distinctive display fonts.
- **Linear** — Both prioritize sparse, content-focused layouts with subtle visual cues and a limited, intentional color palette.
- **Stripe** — Features a similar combination of a neutral base with a single, highly saturated accent color for primary actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greige-canvas: #f7f6e3;
  --color-charcoal-ink: #262d29;
  --color-vivid-yellow: #ffff48;

  /* Typography — Font Families */
  --font-suisseintl: 'Suisseintl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl-book: 'Suisseintl Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-prody: 'Prody', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.15;
  --text-body: 16px;
  --leading-body: 1.15;
  --text-subheading: 19px;
  --leading-subheading: 1.15;
  --text-heading: 33px;
  --leading-heading: 1.15;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --text-display: 131px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 75px;
  --card-padding: 37px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-lg: 8.424px;
  --radius-2xl: 18.72px;
  --radius-3xl: 37.44px;

  /* Named Radii */
  --radius-cards: 37.44px;
  --radius-inputs: 8.424px;
  --radius-buttons: 18.72px;
  --radius-general: 8.424px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greige-canvas: #f7f6e3;
  --color-charcoal-ink: #262d29;
  --color-vivid-yellow: #ffff48;

  /* Typography */
  --font-suisseintl: 'Suisseintl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl-book: 'Suisseintl Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-prody: 'Prody', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.15;
  --text-body: 16px;
  --leading-body: 1.15;
  --text-subheading: 19px;
  --leading-subheading: 1.15;
  --text-heading: 33px;
  --leading-heading: 1.15;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --text-display: 131px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-lg: 8.424px;
  --radius-2xl: 18.72px;
  --radius-3xl: 37.44px;
}
```
