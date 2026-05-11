# Flying Papers — Style Reference
> Punchy Pulp Comic

**Theme:** light

Flying Papers uses a vibrant, playful visual language with high-contrast color pairings and bold, expressive typography. The design emphasizes chunky, outlined elements and a distinct personality, favoring blocky shapes and thick borders over subtle gradients or shadows. Color is used to define graphic blocks and highlight key information, rather than for deep hierarchy or functional states. The overall impression is energetic and almost cartoonish.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Grape Soda | `#8584bd` | `--color-grape-soda` | Page background, large hero sections |
| Lemon Drop | `#f4ed36` | `--color-lemon-drop` | Yellow accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Warm Dough | `#f9cc73` | `--color-warm-dough` | Secondary brand accent for text, outlined elements, and some card elements |
| Deep Plum | `#61609a` | `--color-deep-plum` | Card backgrounds, creating visual breaks from the main Grape Soda background |
| Rose Blush | `#f8c1ba` | `--color-rose-blush` | Muted accent for borders and text, offering a softer alternative to the main brand colors |
| Sage Clay | `#b5c995` | `--color-sage-clay` | Muted accent for borders and text, providing a natural tone amidst the more vivid brand colors |
| Forest Floor | `#375027` | `--color-forest-floor` | Footer background, providing a grounding, darker tone |
| Orchid Bloom | `#ac4f98` | `--color-orchid-bloom` | Specific card backgrounds, adding variety to the color palette for content blocks |
| Crimson Pop | `#c94245` | `--color-crimson-pop` | Specific card backgrounds, puncturing the palette with a bold red |
| Licorice Stick | `#000000` | `--color-licorice-stick` | Primary text, borders, and icon fills |
| Whipped Cream | `#f9f5f2` | `--color-whipped-cream` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Deep Charcoal | `#1a1a1a` | `--color-deep-charcoal` | Muted text, some borders, and secondary backgrounds |

## Tokens — Typography

### ObviouslyVariable — Primary display and heading font. Its heavy weights and wide letter-spacing create a bold, impactful, and almost stamped visual style. · `--font-obviouslyvariable`
- **Weights:** 800, 900
- **Sizes:** 18px, 20px, 30px, 100px, 113px, 130px, 133px, 149px, 184px, 241px, 244px, 341px
- **Line height:** 0.80, 0.90, 1.00
- **Letter spacing:** 0.02em
- **OpenType features:** `"calt" 0`
- **Role:** Primary display and heading font. Its heavy weights and wide letter-spacing create a bold, impactful, and almost stamped visual style.

### DegularVariable — Body text and functional labels, providing a clean, legible contrast to the expressive headings. · `--font-degularvariable`
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Body text and functional labels, providing a clean, legible contrast to the expressive headings.

### DegularDisplay-Bold — Subheadings and emphasized text, offering a slightly more pronounced weight and tracking than regular body text. · `--font-degulardisplay-bold`
- **Weights:** 700
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** 0.05em
- **Role:** Subheadings and emphasized text, offering a slightly more pronounced weight and tracking than regular body text.

### bergen_monoregular — Navigation and utility text, contributing a technical, legible feel with its monospaced origin. · `--font-bergenmonoregular`
- **Substitute:** Space Mono
- **Weights:** 400, 600
- **Sizes:** 12px, 14px
- **Line height:** 0.80, 1.00
- **Letter spacing:** normal
- **OpenType features:** `"calt" 0`
- **Role:** Navigation and utility text, contributing a technical, legible feel with its monospaced origin.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 14px | 0.8 | — | `--text-body` |
| heading | 18px | 1 | 0.36px | `--text-heading` |
| heading-lg | 20px | 1 | 0.4px | `--text-heading-lg` |
| display-sm | 30px | 0.9 | 0.6px | `--text-display-sm` |
| display-md | 100px | 0.8 | 2px | `--text-display-md` |
| display | 341px | 0.8 | 6.82px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| buttons | 0px |
| elements | 6px |
| roundElements | 100px |

### Layout

- **Section gap:** 40px
- **Card padding:** 17px
- **Element gap:** 17px

## Components

### Primary Outlined Button
**Role:** Main call-to-action button.

Transparent background with a 3px Lemon Drop (#f4ed36) border, 0px border-radius, and Licorice Stick (#000000) text. Padding is implied by text size as 0px from raw data.

### Secondary Outlined Button (Neutral)
**Role:** Secondary action or ghost button.

Transparent background with a 3px Licorice Stick (#000000) border, 0px border-radius, and Licorice Stick (#000000) text. Padding is implied by text size as 0px from raw data.

### Text Link (Light)
**Role:** Interactive text link on dark backgrounds.

Transparent background with no border, Whipped Cream (#f9f5f2) text. Padding is implied by text size as 0px from raw data.

### Text Link (Dark)
**Role:** Interactive text link on light backgrounds.

Transparent background with no border, Licorice Stick (#000000) text. Padding is implied by text size as 0px from raw data.

### Neutral Card
**Role:** Basic content container.

Transparent background, 6px border-radius, no shadow, with 17px padding on all sides. Primarily houses content without a distinct background color.

### Deep Plum Card
**Role:** Prominent content card with brand color background.

Solid Deep Plum (#61609a) background, 6px border-radius, no shadow, with 17px padding on all sides.

### Orchid Bloom Card
**Role:** Accent content card to provide visual variation.

Solid Orchid Bloom (#ac4f98) background, 6px border-radius, no shadow, with 17px padding on all sides.

### Crimson Pop Card
**Role:** Highlight content card for emphasis.

Solid Crimson Pop (#c94245) background, 6px border-radius, no shadow, with 17px padding on all sides.

## Do's and Don'ts

### Do
- Use Grape Soda (#8584bd) as the default background for full-page sections to uphold the brand's energetic foundation.
- Apply Lemon Drop (#f4ed36) exclusively for high-impact headlines and outlined calls-to-action, balancing its vividness with the background.
- Utilize ObviouslyVariable Bold for all headlines, employing letter-spacing 0.02em and scaling sizes to achieve visual dominance.
- Always apply a 3px solid border to interactive elements, preferring Lemon Drop (#f4ed36) for primary actions and Licorice Stick (#000000) for secondary options.
- Ensure all card elements have a border-radius of 6px, providing a subtle softness against otherwise sharp edges.
- Employ Licorice Stick (#000000) as the primary text color on light backgrounds and Lemon Drop (#f4ed36) or Whipped Cream (#f9f5f2) on dark backgrounds for accessibility.
- Maintain a default element gap of 17px and card padding of 17px for consistent visual breathing room within components.

### Don't
- Do not use generic system shadows or subtle gradients; the design relies on flat blocks and sharp contrasts for its personality.
- Avoid solid filled buttons for primary actions; prioritize the outlined button style with a 3px border in brand colors.
- Do not introduce new typefaces; restrict typography to ObviouslyVariable, DegularVariable, and bergen_monoregular as specified.
- Do not use neutral colors as primary accents; color should always convey energy and brand personality.
- Do not vary card radii; all cards should consistently use a 6px border-radius.
- Avoid dense, information-heavy layouts; sections should breathe with ample vertical and horizontal spacing.
- Do not use subtle color variations for hierarchy; use distinct chromatic colors or strong achromatic contrast for clear differentiation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Grape Soda Canvas | `#8584bd` | Primary page background and large, immersive sections. |
| 2 | Whipped Cream Surface | `#f9f5f2` | Secondary backgrounds, such as for navigation elements or subtle content areas. |
| 3 | Deep Plum Card Surface | `#61609a` | Prominent card backgrounds, providing a distinct color block within the layout. |

## Imagery

The site's imagery focuses on an almost cartoonish, often abstract, and slightly mischievous aesthetic. This is exemplified by the peering character on the hero screen. There's a strong preference for icons over photography and a visual language that feels illustrative and graphic, almost like a bold sticker or comic book art. Graphics are typically filled, not outlined, and utilize the brand's vivid color palette. They serve a decorative and brand-reinforcing role rather than providing literal product showcases or realistic context. Imagery density is moderate, with key graphics acting as focal points.

## Layout

The page employs a full-bleed layout for its main sections, with content often centered or using large, blocky elements. The hero section is dominated by a large, centered headline and a graphic element against a full-width brand background. Subsequent sections follow a consistent vertical rhythm, often featuring alternating background colors. Content is typically arranged in clear, stacked blocks or occasionally in two-column layouts. The presence of card variants suggests a grid-like arrangement for some content blocks, breaking up the full-width flow. Navigation is generally a minimal top bar, suggesting an informal approach, and the footer is clearly defined with a distinct background.

## Agent Prompt Guide

**Quick Color Reference**
- text: #000000
- background: #8584bd
- border: #000000
- accent: #2d8ebc
- primary action: #f4ed36 (outlined action border)

**3-5 Example Component Prompts**
- Create a hero section: Grape Soda (#8584bd) background, main headline 'HOW OLD ARE YOU?' in Lemon Drop (#f4ed36), ObviouslyVariable Bold 341px, letter-spacing 6.82px. Include a Secondary Outlined Button with 'I'M OVER 18, LET ME IN' text in Licorice Stick (#000000), 3px #000000 border, no radius, 0px padding. Below it, a Text Link (Light) saying 'I'M NOT OVER 18 YET' in Whipped Cream (#f9f5f2).
- Create a Deep Plum Card: Deep Plum (#61609a) background, 6px radius, 17px padding. Inside, 'Product Title' in Licorice Stick (#000000) (ObviouslyVariable 30px, letter-spacing 0.6px) and 'Short description of product' in body text style Licorice Stick (#000000) (DegularVariable 10px).
- Create a footer section: Forest Floor (#375027) background, with navigation links 'Shop', 'About us' styled as Text Link (Light) in Whipped Cream (#f9f5f2), bergen_monoregular 12px.

## Similar Brands

- **Brainpop** — Shares a vibrant, cartoonish aesthetic with high-contrast colors and bold, graphic elements.
- **Mailchimp (old branding)** — Exhibits a playful tone with distinctive, bold typography and a limited but impactful color palette for brand identity.
- **Bravado** — Utilizes a highly stylized, illustrative approach with strong typography and a focus on unique visual assets.
- **Liquid Death** — Employs an edgy, graphic-heavy style with strong, singular color accents and prominent typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-grape-soda: #8584bd;
  --color-lemon-drop: #f4ed36;
  --color-warm-dough: #f9cc73;
  --color-deep-plum: #61609a;
  --color-rose-blush: #f8c1ba;
  --color-sage-clay: #b5c995;
  --color-forest-floor: #375027;
  --color-orchid-bloom: #ac4f98;
  --color-crimson-pop: #c94245;
  --color-licorice-stick: #000000;
  --color-whipped-cream: #f9f5f2;
  --color-deep-charcoal: #1a1a1a;

  /* Typography — Font Families */
  --font-obviouslyvariable: 'ObviouslyVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-degularvariable: 'DegularVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-degulardisplay-bold: 'DegularDisplay-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bergenmonoregular: 'bergen_monoregular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 0.8;
  --text-heading: 18px;
  --leading-heading: 1;
  --tracking-heading: 0.36px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.4px;
  --text-display-sm: 30px;
  --leading-display-sm: 0.9;
  --tracking-display-sm: 0.6px;
  --text-display-md: 100px;
  --leading-display-md: 0.8;
  --tracking-display-md: 2px;
  --text-display: 341px;
  --leading-display: 0.8;
  --tracking-display: 6.82px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 17px;
  --element-gap: 17px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-buttons: 0px;
  --radius-elements: 6px;
  --radius-roundelements: 100px;

  /* Surfaces */
  --surface-grape-soda-canvas: #8584bd;
  --surface-whipped-cream-surface: #f9f5f2;
  --surface-deep-plum-card-surface: #61609a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-grape-soda: #8584bd;
  --color-lemon-drop: #f4ed36;
  --color-warm-dough: #f9cc73;
  --color-deep-plum: #61609a;
  --color-rose-blush: #f8c1ba;
  --color-sage-clay: #b5c995;
  --color-forest-floor: #375027;
  --color-orchid-bloom: #ac4f98;
  --color-crimson-pop: #c94245;
  --color-licorice-stick: #000000;
  --color-whipped-cream: #f9f5f2;
  --color-deep-charcoal: #1a1a1a;

  /* Typography */
  --font-obviouslyvariable: 'ObviouslyVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-degularvariable: 'DegularVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-degulardisplay-bold: 'DegularDisplay-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bergenmonoregular: 'bergen_monoregular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 0.8;
  --text-heading: 18px;
  --leading-heading: 1;
  --tracking-heading: 0.36px;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.4px;
  --text-display-sm: 30px;
  --leading-display-sm: 0.9;
  --tracking-display-sm: 0.6px;
  --text-display-md: 100px;
  --leading-display-md: 0.8;
  --tracking-display-md: 2px;
  --text-display: 341px;
  --leading-display: 0.8;
  --tracking-display: 6.82px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 100px;
}
```
