# Karl — Style Reference
> joyful circus tent, bright and in motion

**Theme:** light

Karl embraces a vibrant, playful aesthetic with a primary color palette of bright yellow and vivid blue, creating a distinct, high-contrast visual identity. Typography is bold and informal, heavily leveraging a custom display font with tight line heights for a 'pop art' feel. The layout is characterized by sweeping, curvilinear forms, especially in the hero section, where cityscapes curve around a large central blue element, suggesting dynamic motion and whimsy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sunshine Yellow | `#FFFF00` | `--color-sunshine-yellow` | Major background for page sections, conveying energy and playfulness |
| Ocean Blue | `#007FFF` | `--color-ocean-blue` | Dominant background for large, organic sections and defining visual elements; it grounds the yellow with a contrasting cool tone |
| Midnight Graphite | `#333333` | `--color-midnight-graphite` | Primary text color for navigation, headlines, and general content, providing strong contrast against the bright backgrounds. Used for subtle button borders |
| Polar White | `#FFFFFF` | `--color-polar-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |

## Tokens — Typography

### Changa One — Headline and display text for all prominent messaging. Its heavy, condensed form at various sizes, along with its specific line heights (e.g., 0.72 for 12px and 0.8 for 20px), contributes to a compact, impactful, and almost comic-book-like visual rhythm, distinct from standard web typography. · `--font-changa-one`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 12px, 20px, 32px, 50px, 75px
- **Line height:** 0.72, 0.80, 1.00, 1.25, 1.67
- **Role:** Headline and display text for all prominent messaging. Its heavy, condensed form at various sizes, along with its specific line heights (e.g., 0.72 for 12px and 0.8 for 20px), contributes to a compact, impactful, and almost comic-book-like visual rhythm, distinct from standard web typography.

### Arial — Supportive body text and explanatory captions, providing accessibility and a counterpoint to the display typeface. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Role:** Supportive body text and explanatory captions, providing accessibility and a counterpoint to the display typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 0.72 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| subheading | 20px | 0.8 | — | `--text-subheading` |
| heading | 32px | 1 | — | `--text-heading` |
| heading-lg | 50px | 1.25 | — | `--text-heading-lg` |
| display | 75px | 1.67 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 45 | 45px | `--spacing-45` |

### Border Radius

| Element | Value |
|---------|-------|
| circular | 1440px |

### Layout

- **Section gap:** 45px
- **Card padding:** 0px
- **Element gap:** 20px

## Components

### Navigation Link
**Role:** Primary navigation item

Text links for navigation, styled in Midnight Graphite (#333333) with a base padding of 10px vertically and 20px horizontally. Uses Arial 14px for accessibility.

### Curved Background Card
**Role:** Decorative background element

A very large, curved background element using Ocean Blue (#007FFF) with an extreme border-radius of 1440px, creating fluid, non-linear sections.

### Main Headline
**Role:** Primary page title or major section heading.

Bold headline using Changa One, weight 400, sizes like 50px or 75px, with tight line heights (e.g. 1.25 for 50px). Text color is Midnight Graphite (#333333) or Polar White (#FFFFFF) depending on background contrast.

### Supporting Text Block
**Role:** Introductory or explanatory text.

Text rendered in Changa One, weight 400, size 32px, lineHeight 1.00, in Midnight Graphite (#333333). Used for prominent but secondary text blocks.

## Do's and Don'ts

### Do
- Prioritize Sunshine Yellow (#FFFF00) as the primary background for most sections to maintain a bright, optimistic tone.
- Use Ocean Blue (#007FFF) only for large, contrasting visual elements or backgrounds, ensuring it creates distinct 'anchor' points within the bright yellow canvas.
- Employ Changa One for all headlines, subheadings, and any text intended for immediate visual impact, varying sizes (12px, 20px, 32px, 50px, 75px) at weight 400.
- Maintain tight line heights for Changa One, adhering to the specified values (e.g., 0.72 for 12px, 0.8 for 20px, 1.00 for 32px) to achieve a compact, 'stacked' text appearance.
- Utilize a 1440px border-radius for large background shapes to create sweeping, circular, or arc-like visual elements that define section structure.
- Apply 10px vertical and 20px horizontal padding for interactive text elements like navigation links to provide generous tap targets and visual breathing room.
- Use the cityscape illustrations as a recurring visual motif, ensuring they are integrated into curvilinear or 'rolled' compositions.

### Don't
- Avoid using gradients; the design system strictly relies on flat, contrasting color blocks.
- Do not introduce drop shadows for elevation; elements are defined by high contrast and placement, not depth effects.
- Refrain from using semi-transparent overlays or subtle background textures; the visual style is characterized by solid, saturated colors.
- Do not deviate from the specified tight line heights for Changa One; increasing them would dilute the compact, impactful aesthetic.
- Avoid standard rectangular card shapes; all significant background elements should use the extreme 1440px radius for curved forms.
- Do not use subtle, muted, or pastel colors; the system's identity is built on vivid, high-saturation hues.
- Do not use generic stock photography; the design leans heavily on custom, playful vector illustrations and clear UI elements.

## Agent Prompt Guide

### Quick Color Reference
- text: #333333 (Midnight Graphite)
- background: #FFFF00 (Sunshine Yellow)
- border: #333333 (Midnight Graphite) for ghost buttons/links
- accent: no distinct accent color
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a hero section: Sunshine Yellow (#FFFF00) background. Centered headline 'Let's roll..' with Changa One, weight 400, size 50px, lineHeight 1.25, in Midnight Graphite (#333333). Below it, a large semicircular Ocean Blue (#007FFF) element with 1440px border-radius, with cityscape illustrations wrapping around it.
2. Design a navigation bar: Full-width, centered text links. Each link: Arial, weight 400, size 14px, in Midnight Graphite (#333333). Padding of 10px vertical, 20px horizontal for each link item.
3. Create a 'About me' text block: Centered, 'I'm Karl, a motion designer.' using Changa One, weight 400, size 32px, lineHeight 1.00, in Polar White (#FFFFFF), against an Ocean Blue (#007FFF) background.

## Similar Brands

- **Awwwards Nominees (some portfolios)** — Experimental layouts, bold typography, and heavy use of custom illustrations as primary visual elements.
- **Some children's book websites** — Playful, bright color palettes, distinctive illustration styles, and a focus on visual storytelling over information density.
- **Webflow showcase sites for cartoonists** — Centered, bold headlines, maximalist illustration styles, and vibrant color usage.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sunshine-yellow: #FFFF00;
  --color-ocean-blue: #007FFF;
  --color-midnight-graphite: #333333;
  --color-polar-white: #FFFFFF;

  /* Typography — Font Families */
  --font-changa-one: 'Changa One', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 0.72;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 20px;
  --leading-subheading: 0.8;
  --text-heading: 32px;
  --leading-heading: 1;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.25;
  --text-display: 75px;
  --leading-display: 1.67;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-45: 45px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 0px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-full: 1440px;

  /* Named Radii */
  --radius-circular: 1440px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sunshine-yellow: #FFFF00;
  --color-ocean-blue: #007FFF;
  --color-midnight-graphite: #333333;
  --color-polar-white: #FFFFFF;

  /* Typography */
  --font-changa-one: 'Changa One', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 0.72;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 20px;
  --leading-subheading: 0.8;
  --text-heading: 32px;
  --leading-heading: 1;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.25;
  --text-display: 75px;
  --leading-display: 1.67;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-45: 45px;

  /* Border Radius */
  --radius-full: 1440px;
}
```
