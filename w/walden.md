# Walden — Style Reference
> Forest floor stillness

**Theme:** light

Walden cultivates a serene, contemplative aesthetic, grounding product presentation in an almost stark, naturalistic minimalism. The visual language centers on muted, earthy neutrals with high contrast for text, creating a sense of understated luxury. Typography is functional and refined, ensuring clarity while blending into the quiet composition. Components are lightweight and largely border-driven, minimizing visual noise to allow product imagery and natural backgrounds to dominate.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Shadow | `#3f3f3f` | `--color-forest-shadow` | Primary text, informational body copy, general UI elements, icon fill |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text on dark backgrounds, primary navigation text |
| Earth Stone | `#d3cec5` | `--color-earth-stone` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| True Black | `#030302` | `--color-true-black` | Action button backgrounds, strong borders for interactive elements, primary navigation text on light backgrounds |
| Muted Grey | `#686867` | `--color-muted-grey` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Light Stone | `#acacac` | `--color-light-stone` | Lightest border lines, dividers |

## Tokens — Typography

### Graphik — Primary typeface for all text content: body, headings, navigation, and input fields. Its clean, geometric form maintains the minimal aesthetic. · `--font-graphik`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 600
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.40, 1.67
- **Letter spacing:** normal
- **Role:** Primary typeface for all text content: body, headings, navigation, and input fields. Its clean, geometric form maintains the minimal aesthetic.

### Geist — Used for specific interactive elements and labels, providing a distinct, slightly more technical feel while maintaining legibility. · `--font-geist`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00, 1.10, 1.20, 1.40
- **Letter spacing:** normal
- **Role:** Used for specific interactive elements and labels, providing a distinct, slightly more technical feel while maintaining legibility.

### GTStandard-M — A distinct serif-like typeface employed for specialized content or decorative text elements, enhancing perceived craftsmanship and quality. · `--font-gtstandard-m`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** A distinct serif-like typeface employed for specialized content or decorative text elements, enhancing perceived craftsmanship and quality.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 14px | 1.2 | — | `--text-body` |
| heading | 18px | 1.1 | — | `--text-heading` |
| display | 20px | 1.1 | — | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(211, 206, 197) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(3, 3, 2) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(211, 206, 197) 0px 1px 0px 0px` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 64px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Ghost Navigation Button (Light)
**Role:** Navigation links and secondary actions within light UI sections.

Transparent background with Canvas White text, no padding, and no border. Used for top navigation and subtle calls to action.

### Contained Footer Button
**Role:** Interactive elements within the footer or compact UI sections.

Transparent background with Canvas White text, 2px border-radius, 16px vertical padding, 4px horizontal padding. Border appears in white on hover.

### Filled Primary Button
**Role:** Main calls to action requiring emphasis.

True Black background with Canvas White text. Has a 2px border-radius, 16px vertical padding, and 24px horizontal padding. The border is explicitly white on render.

### Outlined Text Link
**Role:** Links and actions in text-heavy areas, often within product details.

Transparent background with True Black text, 8px horizontal padding, no vertical padding. Has a 1px True Black border on the bottom. No explicit border-radius (0px).

### Search/Input Field
**Role:** Text input areas for search or forms.

Transparent background with True Black text. Features 12px vertical padding. Bottom border is 1px thick in True Black. A 1px inset shadow in Earth Stone appears on focus.

## Do's and Don'ts

### Do
- Prioritize product imagery and natural backgrounds; frame them as the primary visual focus.
- Use Forest Shadow (#3f3f3f) for primary text and Canvas White (#ffffff) for backgrounds to maintain a high contrast, minimal reading experience.
- Apply True Black (#030302) as the background for primary action buttons or as a strong border for interactive elements.
- Maintain minimal border radii: 2px for buttons and 16px for cards, reinforcing a subtle, structured aesthetic.
- Ensure generous vertical spacing between sections, using the sectionGap of '64px' to create a breathable layout.
- Utilize 1px borders in Earth Stone (#d3cec5) or True Black (#030302) for UI separation rather than heavy shadows or fills.
- Use Graphik (sans-serif) for all primary text content; reserve Geist and GTStandard-M for specific utility or decorative instances.

### Don't
- Avoid vivid or highly saturated colors for UI elements; color should be sparingly applied and mostly achromatic.
- Do not use heavy drop shadows or complex gradients; rely on subtle inset shadows and single-color fills.
- Do not introduce decorative elements that distract from product photography or natural imagery.
- Avoid dense, information-heavy blocks of text; break content into manageable, well-spaced segments.
- Do not use generic system fonts; stick to Graphik, Geist, and GTStandard-M to preserve brand distinctiveness.
- Avoid radius values outside of 2px for buttons and 16px for larger cards.
- Do not introduce gratuitous motion or animations; transitions should be subtle and functional.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Dominant page background, providing a clean, expansive foundation. |

## Elevation

- **Interactive Link Border:** `inset 0px 0px 0px 1px rgb(211, 206, 197)`
- **Primary Button Border (Focus/Hover):** `inset 0px 0px 0px 1px rgb(3, 3, 2)`
- **Input Field Inset Shadow:** `0px 1px 0px 0px rgb(211, 206, 197)`

## Imagery

The visual language for imagery is characterized by high-quality, deliberately composed product photography set within natural, minimalist environments (forests, mossy landscapes, raw wood). Photography often features products isolated or in serene contexts, emphasizing their form and materiality. Treatment is typically full-bleed or large-scale, dominating sections of the page. There are also stark product shots on clean, abstract backgrounds. Icons, when present, are simple, outlined, and monochromatic, used for functional navigation cues. The density is image-heavy, with large visuals serving as atmosphere and product showcase, allowing text to act as supporting detail.

## Layout

The page model is full-bleed, allowing large-scale imagery to extend to the viewport edges, creating an immersive experience. The hero sections feature large, atmospheric photography with centered text overlays for headings and calls to action. Section rhythm is predominantly defined by large photographic blocks alternating fluidly, connected by minimal UI. Content arrangement often juxtaposes large hero images with smaller, descriptive text blocks or product grids. Navigation is a persistent, minimal top bar with left-aligned brand and right-aligned utility links, maintaining overall content visibility.

## Agent Prompt Guide

Quick Color Reference:
text: #3f3f3f
background: #ffffff
border: #d3cec5
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section with 'Space for the Self.' as the heading, 'Shop Best Sellers' as the link, using a full-width immersive nature photo. Heading text: Graphik, size 20px, weight 400, color #3f3f3f. Link text: Graphik, size 14px, weight 400, color #3f3f3f, with a 1px #3f3f3f bottom border.

No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

Create a navigation link for 'Shop'. Use Graphik, size 16px, weight 400, color #3f3f3f. The link should have no background and no explicit borders.

## Similar Brands

- **Aēsop** — Similar focus on minimalist product presentation within natural/architectural settings, restrained color palette, and premium typography.
- **MUJI** — Emphasizes natural materials, functional design, and a muted, achromatic color scheme creating a sense of calm simplicity.
- **The Future Kept** — Utilizes large-scale, atmospheric photography to showcase products, combined with a sparse, elegant UI and strong emphasis on natural textures.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-shadow: #3f3f3f;
  --color-canvas-white: #ffffff;
  --color-earth-stone: #d3cec5;
  --color-true-black: #030302;
  --color-muted-grey: #686867;
  --color-light-stone: #acacac;

  /* Typography — Font Families */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-heading: 18px;
  --leading-heading: 1.1;
  --text-display: 20px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 2px;

  /* Shadows */
  --shadow-subtle: rgb(211, 206, 197) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgb(3, 3, 2) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(211, 206, 197) 0px 1px 0px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-shadow: #3f3f3f;
  --color-canvas-white: #ffffff;
  --color-earth-stone: #d3cec5;
  --color-true-black: #030302;
  --color-muted-grey: #686867;
  --color-light-stone: #acacac;

  /* Typography */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-heading: 18px;
  --leading-heading: 1.1;
  --text-display: 20px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgb(211, 206, 197) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgb(3, 3, 2) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(211, 206, 197) 0px 1px 0px 0px;
}
```
