# 2.AG — Style Reference
> Clinical clarity, soft curves.

**Theme:** light

2.AG presents a scientifically grounded, clean aesthetic built on a foundation of cool-toned neutrals and wireframe graphics. Typography is compact and precise, utilizing two `Inter` variants for a refined, data-driven feel. Strategic pops of vivid teal serve as clear action indicators and highlight key product benefits, while surfaces remain predominantly light gray or white, creating an airy, clinical canvas. Components are lightweight with substantial rounded corners, softening the technical edge.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Teal | `#244d54` | `--color-midnight-teal` | Dark background for hero sections and feature blocks; accent on outline buttons and icon strokes, establishing a sophisticated brand presence |
| Activation Green | `#2ecea0` | `--color-activation-green` | Primary action button backgrounds, announcement bar fill, and product benefit highlights — a vivid, energetic accent color to draw attention |
| Lagoon Mist | `#6dddbd` | `--color-lagoon-mist` | Subtle link accents and decorative text in content sections, providing a lighter brand touch |
| Deep Graphite | `#000000` | `--color-deep-graphite` | Primary text for headings and body content, bold outlines, and default icon fills, providing maximum contrast against light surfaces |
| Medium Gray | `#151515` | `--color-medium-gray` | Secondary text for less prominent information, often used for smaller headings or descriptive annotations |
| Silver Cloud | `#e5e7eb` | `--color-silver-cloud` | Subtle borders separating elements, ghost button outlines, and dividers, providing visual structure without harshness |
| Pure White | `#ffffff` | `--color-pure-white` | Backgrounds for main content areas, cards, product forms, and button text, ensuring a clean and bright canvas |
| Light Pearl | `#f0f1f2` | `--color-light-pearl` | Subtle background for alternating sections and feature cards, adding a slight distinction from the main page background |
| Sky Fog | `#999999` | `--color-sky-fog` | Placeholder text in inputs and less critical border elements |
| Text Gray | `#858585` | `--color-text-gray` | Muted body text and secondary informational text, offering a slightly softer contrast than Deep Graphite |

## Tokens — Typography

### Inter Tight — Primary typeface for most UI elements including body text, links, smaller headings, and button labels. Its tight tracking provides a compact, technical feel. · `--font-inter-tight`
- **Substitute:** Open Sans, Lato
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 24px, 30px, 36px, 45px, 62px
- **Line height:** 1.00, 1.21, 1.25, 1.30, 1.33, 1.35, 1.40, 1.50, 1.60, 1.86
- **Letter spacing:** 0.0050em (at 10px), 0.0200em (at 12px), 0.0300em (at 13px), 0.0900em (at 14px), 0.1000em (at 15px)
- **OpenType features:** `"kern"`
- **Role:** Primary typeface for most UI elements including body text, links, smaller headings, and button labels. Its tight tracking provides a compact, technical feel.

### Inter — Used for larger headings and product titles where a slightly wider, more commanding presence is desired with a subtle negative tracking for gravitas. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 18px, 28px, 48px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.0420em (at 16px, 18px, 28px, 48px)
- **Role:** Used for larger headings and product titles where a slightly wider, more commanding presence is desired with a subtle negative tracking for gravitas.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.05px | `--text-caption` |
| body | 14px | 1.5 | 0.05px | `--text-body` |
| body-lg | 16px | 1.4 | -0.042px | `--text-body-lg` |
| subheading | 18px | 1.25 | -0.042px | `--text-subheading` |
| heading | 28px | 1.2 | -0.042px | `--text-heading` |
| heading-lg | 36px | 1.1 | -0.042px | `--text-heading-lg` |
| display | 48px | 1.1 | -0.042px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 250px |
| cards | 12px |
| inputs | 5px |
| buttons | 50px |
| default | 12px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 50px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Outline Button - Dark
**Role:** Action button with transparent background for secondary actions or navigation.

backgroundColor: rgba(0, 0, 0, 0), color: #244d54, borderColor: #244d54, borderRadius: 30px, paddingTop: 10px, paddingRight: 16px, paddingBottom: 10px, paddingLeft: 16px. Text uses Inter Tight.

### Activation Button - Filled
**Role:** Primary call-to-action button, visually prominent.

backgroundColor: #2ecea0, color: #ffffff, borderColor: #2ecea0, borderRadius: 50px, paddingTop: 7px, paddingRight: 30px, paddingBottom: 7px, paddingLeft: 30px. Text uses Inter Tight.

### Pill Outline Button - Dark
**Role:** Small, information-based button for categorizations or filters.

backgroundColor: rgba(0, 0, 0, 0), color: #000000, borderColor: #000000, borderRadius: 250px, paddingTop: 10px, paddingRight: 20px, paddingBottom: 12px, paddingLeft: 20px. Text uses Inter Tight.

### Product Feature Card
**Role:** Displaying product benefits or descriptive information.

backgroundColor: #f0f1f2, borderRadius: 20px, boxShadow: none, paddingTop: 30px, paddingRight: 30px, paddingBottom: 30px, paddingLeft: 30px.

### Review Card
**Role:** Showcasing user testimonials.

backgroundColor: #f5f5f5, borderRadius: 12px, boxShadow: none, paddingTop: 24px, paddingRight: 24px, paddingBottom: 24px, paddingLeft: 24px.

### Primary Hero Card
**Role:** Prominent information card used in key landing sections.

backgroundColor: #244d54, borderRadius: 20px, boxShadow: none, paddingTop: 35px, paddingRight: 35px, paddingBottom: 35px, paddingLeft: 35px.

### Underlined Input Field
**Role:** Text input field with an emphasis on the bottom border.

backgroundColor: rgba(0, 0, 0, 0), color: #000000, borderColor: #244d54 (bottom border), borderRadius: 5px, paddingTop: 12px, paddingRight: 40px, paddingBottom: 12px, paddingLeft: 17px. Placeholder text is #999999.

### Circular Input Field
**Role:** Input field with fully rounded corners, likely for search or simple text entry.

backgroundColor: #ffffff, color: #000000, borderColor: rgba(0, 0, 0, 0.4), borderRadius: 1.67772e+07px (~9999px), paddingTop: 16px, paddingRight: 16px, paddingBottom: 16px, paddingLeft: 16px. Placeholder text is #999999.

## Do's and Don'ts

### Do
- Prioritize Inter Tight for UI text, ensuring compact headings and precise body content. Use a letter-spacing of 0.0050em for small text (10px) but remove for larger headings, replacing with negative tracking of -0.0420em for `Inter` headings where needed.
- Utilize Pure White (#ffffff) as the primary canvas, with Light Pearl (#f0f1f2) for subtly differentiated background sections and Review Cards.
- Use Activation Green (#2ecea0) exclusively for primary calls-to-action and key product benefits, maintaining its high impact.
- Apply substantial border radii of 50px for buttons and 12-20px for cards, giving elements a soft, approachable feel.
- Employ Midnight Teal (#244d54) for dark hero section backgrounds and outlining secondary action buttons.
- Maintain an element gap of 8px for vertical stacking of small components and a consistent 16px for card padding.
- Use Deep Graphite (#000000) for all primary body and heading text for maximum legibility against light backgrounds.

### Don't
- Avoid using Activation Green (#2ecea0) purely for decorative purposes; reserve it for interactive elements or critical highlights.
- Do not introduce sharp corners; maintain the established rounded aesthetic for all UI elements, with minimum 5px radius for inputs and 12px for cards.
- Refrain from using strong drop shadows or complex gradients; rely on clean surface distinctions and subtle borders for depth.
- Do not deviate from the Inter and Inter Tight typefaces; no other font families should be introduced.
- Avoid arbitrary uses of color; every shade should serve a clear functional or brand-distinctive purpose.
- Do not use generic gray text. Text should either be Deep Graphite (#000000) for prominence, Medium Gray (#151515) for secondary content, or Text Gray (#858585) for muted text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Main Canvas | `#ffffff` | Primary page background and main content areas. |
| 1 | Accent Surface 1 | `#f0f1f2` | Subtly differentiated background for alternating sections and feature cards. |
| 2 | Accent Surface 2 | `#f5f5f5` | Background for review cards and other elevated content blocks. |
| 3 | Deep Surface | `#244d54` | Dark background for hero sections or prominent content blocks. |

## Imagery

The imagery focuses on highly stylized, scientific visualizations and clean product photography. The hero section features a wireframe 3D human model with glowing points of relief, suggesting precision and technology. Product shots are isolated on pristine white or softly blurred backgrounds, highlighting the product itself. Illustrations are minimal, primarily functional icons with a thin stroke. The overall imagery is explanatory and product-focused, avoiding lifestyle shots and maintaining a clinical, high-tech atmosphere, image density is moderate, carefully balanced with text.

## Layout

The page primarily uses a max-width contained layout, likely around 1200px, with content centered. The hero section is full-bleed with a dark Midnight Teal background, featuring a large headline and a prominent scientific graphic. Sections below alternate between Pure White and Light Pearl backgrounds, often using a 2-column text-left/visual-right pattern. Card grids are prevalent for features and testimonials, typically arranged in a masonry-like pattern or a 3-column grid. Vertical spacing between sections is comfortable, establishing a clear rhythm. Navigation is a simple top bar with a sticky header.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000 (Deep Graphite)
- background: #ffffff (Pure White)
- border: #e5e7eb (Silver Cloud)
- accent: #244d54 (Midnight Teal)
- primary action: #2ecea0 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Midnight Teal (#244d54) background. Headline 'A breakthrough in topical cannabinoids' in Inter, size 48px, weight 500, color #ffffff, letter-spacing -0.042em. Center a Ghost Outline Button - Dark: 'Get Relief', color #ffffff, border #ffffff, borderRadius 30px, padding 10px 16px.
2. Design a product feature card: Light Pearl (#f0f1f2) background, borderRadius 20px, padding 30px. Headline 'Rapid Relief Cream' in Inter, size 28px, weight 500, color #000000. Follow with some body text in Inter Tight, size 16px, weight 400, color #000000, line-height 1.5. Include an Activation Button - Filled: 'Add to Cart', background color #2ecea0, text color #ffffff, borderRadius 50px, padding 7px 30px.
3. Create a review card: Light Pearl (#f5f5f5) background, borderRadius 12px, padding 24px. Review text in Inter Tight, size 18px, weight 400, color #000000, line-height 1.5. Author name in Inter Tight, size 14px, weight 500, color #858585, letter-spacing 0.09em.
4. Show an Underlined Input Field: background transparent, text color #000000, bottom border 1px solid #244d54, borderRadius 5px, padding 12px 17px. Placeholder text is Sky Fog (#999999).

## Similar Brands

- **Athletic Greens** — Similar clean, health-science aesthetic with a focus on product benefits and a restrained color palette featuring strategic green accents.
- **Whoop** — High-tech, data-driven visual language, featuring dark backgrounds interspersed with light sections, and a focus on sleek product presentation.
- **Calm** — Use of soothing, deep accent colors against light backgrounds to convey a sense of well-being and scientific rigor without being overly clinical.
- **Care/of** — Emphasis on clean typography, structured layouts, and product-centric imagery with subtle but specific brand accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-teal: #244d54;
  --color-activation-green: #2ecea0;
  --color-lagoon-mist: #6dddbd;
  --color-deep-graphite: #000000;
  --color-medium-gray: #151515;
  --color-silver-cloud: #e5e7eb;
  --color-pure-white: #ffffff;
  --color-light-pearl: #f0f1f2;
  --color-sky-fog: #999999;
  --color-text-gray: #858585;

  /* Typography — Font Families */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.05px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.042px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.042px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.042px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.042px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.042px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 50px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 50px;
  --radius-full-2: 250px;

  /* Named Radii */
  --radius-tags: 250px;
  --radius-cards: 12px;
  --radius-inputs: 5px;
  --radius-buttons: 50px;
  --radius-default: 12px;

  /* Surfaces */
  --surface-main-canvas: #ffffff;
  --surface-accent-surface-1: #f0f1f2;
  --surface-accent-surface-2: #f5f5f5;
  --surface-deep-surface: #244d54;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-teal: #244d54;
  --color-activation-green: #2ecea0;
  --color-lagoon-mist: #6dddbd;
  --color-deep-graphite: #000000;
  --color-medium-gray: #151515;
  --color-silver-cloud: #e5e7eb;
  --color-pure-white: #ffffff;
  --color-light-pearl: #f0f1f2;
  --color-sky-fog: #999999;
  --color-text-gray: #858585;

  /* Typography */
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.05px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.042px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.042px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.042px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.042px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -0.042px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 50px;
  --radius-full-2: 250px;
}
```
