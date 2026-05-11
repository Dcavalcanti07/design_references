# TWOTWO — Style Reference
> Vivid chartreuse on concrete

**Theme:** light

TWOTWO embraces a bold, athletic visual language defined by strong contrasts and a singular, vibrant accent. The monochromatic canvas of dark grays and white provides a neutral backdrop for vivid chartreuse, which acts as the brand's energetic signature. Typography is direct and confident, echoing a sense of unadorned quality. Components are minimal, relying on shape and color for impact rather than complex ornamentation, creating a focused and dynamic user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, icon fills, strong borders, dark surface background where appropriate for contrast |
| Slate Text | `#323232` | `--color-slate-text` | Secondary text, less prominent borders |
| Ghost Gray | `#1a1a1a` | `--color-ghost-gray` | Subtle link text, tertiary borders, ghost icon fills |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, input fields, card surfaces |
| Chartreuse Flash | `#e3fc03` | `--color-chartreuse-flash` | Primary action buttons, active state indicators, prominent headings, decorative accents — creates high-energy focal points against the neutral palette |

## Tokens — Typography

### WhyteInktrapRegular — Supporting text for smaller elements, product details, and footer content. Its unique character adds subtle brand distinctiveness without shouting. · `--font-whyteinktrapregular`
- **Substitute:** DM Mono
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.60
- **Role:** Supporting text for smaller elements, product details, and footer content. Its unique character adds subtle brand distinctiveness without shouting.

### WhyteBook — Body copy, input text, smaller headings, interactive elements like navigation links and buttons. Provides clear readability at various scales with a confident, open tone. · `--font-whytebook`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 13px, 16px, 18px, 20px, 22px, 26px, 38px
- **Line height:** 1.30, 1.40, 1.60
- **Role:** Body copy, input text, smaller headings, interactive elements like navigation links and buttons. Provides clear readability at various scales with a confident, open tone.

### WhyteRegular — Primary headlines and section titles. The regularity combined with generous sizing creates a strong, yet approachable presence. · `--font-whyteregular`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 32px, 72px
- **Line height:** 1.10, 1.15
- **Role:** Primary headlines and section titles. The regularity combined with generous sizing creates a strong, yet approachable presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.4 | — | `--text-caption` |
| body-sm | 16px | 1.6 | — | `--text-body-sm` |
| body | 18px | 1.6 | — | `--text-body` |
| subheading | 20px | 1.3 | — | `--text-subheading` |
| heading-sm | 22px | 1.3 | — | `--text-heading-sm` |
| heading | 26px | 1.3 | — | `--text-heading` |
| heading-lg | 32px | 1.15 | — | `--text-heading-lg` |
| display | 72px | 1.1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 50px |
| buttons | 50px |
| general | 8px |
| productImages | 16px |

### Layout

- **Section gap:** 68px
- **Card padding:** 32px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** The main call to action element, demanding attention.

Filled with Chartreuse Flash (#e3fc03), text in Midnight Ink (#000000), 50px border-radius, 16px padding on all sides. This button is a distinct, high-contrast focal point.

### Navigation Link / Ghost Button
**Role:** Used for navigation and secondary actions where visual weight should be minimal.

Transparent background, text in Midnight Ink (#000000), 0px border-radius, 0px padding. This component is essentially text-based, relying on position and interaction for presence.

### Search Input Field
**Role:** Standard input for user data entry.

Background is Canvas White (#ffffff), text in Midnight Ink (#000000), 50px border-radius, 16px vertical padding, 32px horizontal padding. Offers a clean, friendly input experience.

### Product Card
**Role:** Container for individual product listings.

Background is Canvas White (#ffffff), 16px border-radius for the card itself and images within. Padding dynamically varies but commonly uses 16px around content and imagery to define clean boundaries.

### Hero Headline
**Role:** Dominant text for primary page messages.

WhyteRegular font, 72px size, 1.1 line-height, Midnight Ink (#000000) or Chartreuse Flash (#e3fc03) color depending on background contrast. Commands attention with directness.

### Product Gallery Item Title
**Role:** Labels for products listed in a grid.

WhyteBook font, 16px size for most items, 400 weight, Midnight Ink (#000000) for high contrast or Slate Text (#323232) for secondary information, with a text-based price like $137. Uses 5px bottom padding.

## Do's and Don'ts

### Do
- Use Chartreuse Flash (#e3fc03) exclusively for primary calls to action or key interactive highlights; avoid decorative overuse.
- Pair Midnight Ink (#000000) text on Canvas White (#ffffff) or Chartreuse Flash (#e3fc03) backgrounds to maintain AAA contrast levels.
- Apply a 50px border-radius to all interactive elements like buttons and input fields for a consistent soft, yet defined, touch.
- Maintain a clear vertical rhythm using 68px for major section separation and 10px between smaller elements.
- Employ WhyteRegular (400) at 72px for hero headlines to establish a bold, impactful brand voice.
- Group product images with a 16px border-radius, ensuring they sit cleanly within their card containers.

### Don't
- Do not introduce additional saturated colors; the Chartreuse Flash (#e3fc03) should remain the single prominent chromatic accent.
- Avoid using border-radius values other than 0px, 8px, 16px, or 50px to prevent visual inconsistency.
- Do not deviate from the specified WhyteInktrapRegular, WhyteBook, and WhyteRegular font families; substitute only when absolutely necessary and with a close visual match.
- Do not use subtle shadows or gradients; the system relies on flat surfaces and high contrast for visual definition.
- Avoid heavily decorated components; rely on color, shape, and typography for visual hierarchy and brand expression.
- Do not use generic system fonts in place of the custom typefaces; the specific character of the type is integral to the brand's identity.

## Imagery

The visual language is dominated by product photography, specifically tight crops of padel rackets and gear. Images are highly focused on the product itself, with a neutral, often gray, studio background that isolates the item. There's no lifestyle photography, suggesting a brand that prioritizes the object's form and function. Iconography, where present, appears to be monochrome (Midnight Ink or Ghost Gray) and outlined, with a clean, functional aesthetic. Imagery serves primarily to showcase and explain product features, with a high density of visual content on product listing pages.

## Layout

The page adheres to a mostly contained, centered page model, with content held within a comfortable maximum width. The hero section is full-bleed with a dark (but not black) overlay, featuring a prominent, centered headline in Chartreuse Flash overlaid on a product shot. Main sections feature consistent vertical spacing, often with product grids (e.g., 3-column layouts) or vertically stacked content blocks. There's a strong visual rhythm of alternation between a full-width hero and then contained, clearly delineated product sections. Navigation is a simple, sticky top header with textual links and key icons.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #ffffff
- border: #000000
- accent: #e3fc03
- primary action: #e3fc03 (filled action)

Example Component Prompts:
- Create a hero section: full-bleed background set to a dark neutral color, with a prominent product image and 'Innovating the padel universe' headline centered in Chartreuse Flash (#e3fc03), WhyteRegular font, 72px size, 1.1 line-height. Below the headline, include a 'Shop Now' button with a Chartreuse Flash (#e3fc03) background, Midnight Ink (#000000) text, 50px radius, 16px padding.
- Design a product listing card: Canvas White (#ffffff) background, 16px radius. Display a product image with 16px radius, a product title ('Drop Racket - PLAY TWO - Jade Green') in WhyteBook, 16px, 400 weight, Midnight Ink (#000000). Add a price '$137' below in Midnight Ink (#000000) with 5px bottom padding. Include a 'Shop Now' button with Chartreuse Flash (#e3fc03) background, Midnight Ink (#000000) text, 50px radius, 16px padding.
- Create a simple navigation link: 'Padel Rackets' in WhyteBook font, 16px size, 400 weight, Midnight Ink (#000000), 0px padding, no background.

## Similar Brands

- **A.P.C.** — Clean, almost austere aesthetic with high-quality photography and restrained use of color.
- **Away** — Product-focused e-commerce with stark backgrounds and minimal UI, letting the product shine.
- **Rapha** — Premium sports brand with a refined, direct, and slightly technical visual style.
- **Aesop** — Meticulous use of typography and subtle color palettes emphasizing product integrity and a calm user experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-slate-text: #323232;
  --color-ghost-gray: #1a1a1a;
  --color-canvas-white: #ffffff;
  --color-chartreuse-flash: #e3fc03;

  /* Typography — Font Families */
  --font-whyteinktrapregular: 'WhyteInktrapRegular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whytebook: 'WhyteBook', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whyteregular: 'WhyteRegular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --text-body: 18px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --text-heading: 26px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 72px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-68: 68px;

  /* Layout */
  --section-gap: 68px;
  --card-padding: 32px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 50px;
  --radius-buttons: 50px;
  --radius-general: 8px;
  --radius-productimages: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-slate-text: #323232;
  --color-ghost-gray: #1a1a1a;
  --color-canvas-white: #ffffff;
  --color-chartreuse-flash: #e3fc03;

  /* Typography */
  --font-whyteinktrapregular: 'WhyteInktrapRegular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whytebook: 'WhyteBook', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whyteregular: 'WhyteRegular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --text-body: 18px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --text-heading: 26px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --text-display: 72px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-68: 68px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;
}
```
