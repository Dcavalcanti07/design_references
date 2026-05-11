# arte* — Style Reference
> Earthy whimsical harvest

**Theme:** light

The arte* design system embraces an earthy, natural aesthetic with a vibrant, playful twist. A dominant, rich ochre background grounds the experience, punctuated by bright, contrasting brand colors for highlights and interactive elements. Typography is bold and characterful, balancing a whimsical display font with a clean sans-serif for content. Components feature rounded forms, particularly for calls to action, creating a soft and inviting feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Amber Ochre | `#ab5700` | `--color-amber-ochre` | Page backgrounds, large decorative elements, primary accent for highlighting core brand elements and links. Its warmth underpins the natural, food-centric theme |
| Pale Sage | `#e5dccd` | `--color-pale-sage` | Muted text, borders, and subtle backgrounds, providing contrast against the vivid brand colors without being stark white |
| Electric Amethyst | `#7997ff` | `--color-electric-amethyst` | Accent color for links, input backgrounds, and decorative icons. Its bright, cool tone creates a dynamic counterpoint to the warm ochre |
| Sunny Meadow | `#e8e359` | `--color-sunny-meadow` | Primary action background, headings, and key highlights. This vibrant yellow is a signature color, conveying energy and freshness |
| Golden Turmeric | `#d99623` | `--color-golden-turmeric` | Secondary accent for decorative elements and lists, subtly different from Sunny Meadow to add depth |
| Forest Green | `#568037` | `--color-forest-green` | Accent for certain list items and decorative details, reinforcing the natural theme |
| Deep Indigo | `#3d549c` | `--color-deep-indigo` | Header text, list item backgrounds, and occasional decorative elements, providing a deep, sophisticated contrast |
| Rich Earth | `#103d26` | `--color-rich-earth` | Darkest background for text that needs high contrast, such as footer elements or occasional list backgrounds |
| Faded Coral | `#e99686` | `--color-faded-coral` | Subtle accent for certain list backgrounds or decorative elements, adding a soft, organic touch |
| Deep Emerald | `#214534` | `--color-deep-emerald` | Text color against Sunny Meadow backgrounds, button borders, and general body text for strong readability |
| Berry Blush | `#5e335d` | `--color-berry-blush` | Decorative background for specific list items, adding a unique, rich tone |
| Harvest Red | `#c42331` | `--color-harvest-red` | Distinctive background for specific list items, appearing as a strong, singular accent |

## Tokens — Typography

### Poppins — Primary body text, labels, and general UI elements. Provides clear readability and a modern, friendly aesthetic. · `--font-poppins`
- **Substitute:** Roboto
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 16px
- **Line height:** 1.40
- **Role:** Primary body text, labels, and general UI elements. Provides clear readability and a modern, friendly aesthetic.

### Parafina — Display headings and significant brand statements. Its unique character delivers a whimsical, bespoke editorial feel at large sizes. · `--font-parafina`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 20px, 30px, 56px, 70px, 104px, 173px
- **Line height:** 0.80, 0.90, 1.00, 1.40
- **Role:** Display headings and significant brand statements. Its unique character delivers a whimsical, bespoke editorial feel at large sizes.

### ExposureTrial — Specific display headings, offering an alternative bold, condensed style at large sizes to Parafina. · `--font-exposuretrial`
- **Substitute:** Oswald
- **Weights:** 500
- **Sizes:** 56px
- **Line height:** 0.90
- **Role:** Specific display headings, offering an alternative bold, condensed style at large sizes to Parafina.

### GTStandard-M — Occasional detailed text or specific component labels. Adds a structured, slightly technical counterbalance. · `--font-gtstandard-m`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Occasional detailed text or specific component labels. Adds a structured, slightly technical counterbalance.

### ITC_Avant_Garde_Gothic_Medium — Distinctive button text, giving actions a clean, geometric, yet friendly appearance. · `--font-itcavantgardegothicmedium`
- **Substitute:** Avant Garde Gothic
- **Weights:** 400
- **Sizes:** 26px
- **Line height:** 1.20
- **Role:** Distinctive button text, giving actions a clean, geometric, yet friendly appearance.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 26px | 1.2 | — | `--text-heading` |
| heading-lg | 30px | 1.4 | — | `--text-heading-lg` |
| display | 56px | 0.9 | — | `--text-display` |
| display-lg | 70px | 1 | — | `--text-display-lg` |
| display-xl | 104px | 1 | — | `--text-display-xl` |
| display-xxl | 173px | 0.8 | — | `--text-display-xxl` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| other | 64px |
| buttons | 31px |

### Layout

- **Section gap:** 24px
- **Card padding:** 15px
- **Element gap:** 24px

## Components

### Primary Action Button (Sunny Meadow)
**Role:** Filled button for main calls to action

Background: #e8e359 (Sunny Meadow). Text: #214534 (Deep Emerald). Border radius: 31px. Padding: 0px vertical, 24px horizontal. This button stands out with its vivid color, emphasizing key actions.

### Secondary Action Button (Amber Ochre)
**Role:** Filled button for secondary calls to action

Background: #ab5700 (Amber Ochre). Text: #e5dccd (Pale Sage). Border radius: 31px. Padding: 0px vertical, 24px horizontal. Provides a more subdued but still distinct action color.

### Ghost Button (Pale Sage)
**Role:** Minimal call to action, often for navigation or secondary controls

Background: transparent. Text: #e5dccd (Pale Sage). No border radius. No padding. Used for 'Menu' or 'Skip to content' links, appearing as subtle text rather than a prominent button.

### Circular Play Button
**Role:** Iconic interaction for media playback

Background: #e8e359 (Sunny Meadow). Text: #214534 (Deep Emerald). Border radius: 50% (circular). Padding: 1px vertical, 6px horizontal. A compact, clear indicator for media controls.

### Rounded Card
**Role:** Container for content sections

Background: transparent. Border radius: 20px. No box shadow. Padding: 15px. Offers a soft, unobtrusive content grouping.

### Input Field (Electric Amethyst)
**Role:** Interactive text input for forms

Background: #7997ff (Electric Amethyst). Text: #e5dccd (Pale Sage). Border radius: 0px. Padding: 8px vertical, 50px right, 0px left. The vivid background makes the input field a prominent interactive element.

## Do's and Don'ts

### Do
- Use Amber Ochre (#ab5700) as the primary page background color to establish brand identity.
- Apply a 31px border radius to all buttons and prominent interactive elements for a consistent soft, rounded aesthetic.
- Feature Secondary Action Buttons (Amber Ochre, #ab5700) where a prominent action is needed but without the urgency of the Primary Action, using Pale Sage (#e5dccd) for text.
- Set display headings in Parafina (500 weight) with large sizes (e.g., 56px, 70px) and condensed line heights (0.8-1.0) for a distinct brand voice.
- Use Pale Sage (#e5dccd) for muted text and subtle borders against darker backgrounds to ensure legibility without harsh contrast.
- Ensure all interactive elements and key brand accents prominently feature Sunny Meadow (#e8e359) or Electric Amethyst (#7997ff) to draw attention.

### Don't
- Avoid using harsh, stark whites or pure blacks; instead, rely on Pale Sage (#e5dccd) for light contrast and Deep Emerald (#214534) or Rich Earth (#103d26) for darker elements.
- Do not use generic system fonts for headings; Parafina or ExposureTrial should define the brand's typographic personality.
- Do not use square, sharp corners for prominent interactive elements; the 31px border radius is a critical brand identifier.
- Do not create large blocks of solid color without textural elements; the design emphasizes natural, organic feel.
- Avoid excessive spacing that makes content feel sparse; maintain a 'comfortable' density with 24px element gaps and 15px card padding.
- Do not mix multiple vivid colors in a single text block or UI element; reserve bright colors for accents and primary actions.

## Imagery

The visual language combines atmospheric, sun-drenched photography of natural elements (like lush green leaves) with warm, intimate lifestyle photography featuring smiling people gathered around food. Product imagery focuses on a 'farm-to-table' aesthetic with close-up shots of fresh ingredients and prepared dishes. Illustrations are minimal, often in the form of small, decorative, outlined icons or simple graphic elements within the brand colors. Imagery is typically contained, not full-bleed, often interacting with the warm Ochre background, contributing to a sense of natural warmth and community.

## Layout

The page structure is primarily max-width contained, although the hero section extends full-bleed with a prominent centered headline over a background image. Sections alternate between full-width content blocks and content constrained within the primary Amber Ochre background. A relaxed vertical rhythm is established with section gaps around 24px, but variable to accommodate large photographic elements. Content often features large, centered headlines, followed by text blocks and image groupings, suggesting a narrative flow rather than a strict grid. Navigation is a sticky top header with a simple 'Menu' button, indicating a hidden sidebar or overlay menu.

## Agent Prompt Guide

Quick Color Reference:
text: #214534
background: #ab5700
border: #e5dccd
accent: #7997ff
primary action: #e8e359 (filled action)

Example Component Prompts:
1. Create a hero section: Amber Ochre background. Headline 'from our farms to your table' in Parafina weight 500, size 173px, line-height 0.8, color #e8e359. Subtext 'always close to home' in Parafina weight 500, size 56px, line-height 0.9, color #e8e359.
2. Create a Primary Action Button: #e8e359 background, #e5dccd text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a content card: Pale Sage background (#e5dccd), 20px border radius, 15px padding. Body text 'zesty kale caesar' in Poppins weight 400, size 16px, color #214534.
4. Design an input field: Electric Amethyst background (#7997ff), Pale Sage text (#e5dccd), 0px border radius, 8px vertical padding, 50px right padding, 0px left padding. Placeholder text 'e-mail' in Poppins weight 400, size 16px, color #e5dccd.

## Similar Brands

- **Sweetgreen** — Shares a focus on fresh, natural food and uses earthy, vibrant color palettes combined with clean sans-serif typography.
- **Oatly** — Exhibits a playful, editorial-style typography for headlines and a natural, approachable brand aesthetic.
- **Goodee** — Uses a warm, curated natural aesthetic with distinct, high-quality photography and a relaxed layout.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-amber-ochre: #ab5700;
  --color-pale-sage: #e5dccd;
  --color-electric-amethyst: #7997ff;
  --color-sunny-meadow: #e8e359;
  --color-golden-turmeric: #d99623;
  --color-forest-green: #568037;
  --color-deep-indigo: #3d549c;
  --color-rich-earth: #103d26;
  --color-faded-coral: #e99686;
  --color-deep-emerald: #214534;
  --color-berry-blush: #5e335d;
  --color-harvest-red: #c42331;

  /* Typography — Font Families */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parafina: 'Parafina', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-exposuretrial: 'ExposureTrial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-itcavantgardegothicmedium: 'ITC_Avant_Garde_Gothic_Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.4;
  --text-display: 56px;
  --leading-display: 0.9;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --text-display-xl: 104px;
  --leading-display-xl: 1;
  --text-display-xxl: 173px;
  --leading-display-xxl: 0.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 15px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 31px;
  --radius-full: 64px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-other: 64px;
  --radius-buttons: 31px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-amber-ochre: #ab5700;
  --color-pale-sage: #e5dccd;
  --color-electric-amethyst: #7997ff;
  --color-sunny-meadow: #e8e359;
  --color-golden-turmeric: #d99623;
  --color-forest-green: #568037;
  --color-deep-indigo: #3d549c;
  --color-rich-earth: #103d26;
  --color-faded-coral: #e99686;
  --color-deep-emerald: #214534;
  --color-berry-blush: #5e335d;
  --color-harvest-red: #c42331;

  /* Typography */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-parafina: 'Parafina', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-exposuretrial: 'ExposureTrial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-itcavantgardegothicmedium: 'ITC_Avant_Garde_Gothic_Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.4;
  --text-display: 56px;
  --leading-display: 0.9;
  --text-display-lg: 70px;
  --leading-display-lg: 1;
  --text-display-xl: 104px;
  --leading-display-xl: 1;
  --text-display-xxl: 173px;
  --leading-display-xxl: 0.8;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 31px;
  --radius-full: 64px;
}
```
