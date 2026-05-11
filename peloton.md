# Peloton — Style Reference
> Dark Studio, Focused Power. Like a high-end fitness studio dimmed for an intense session, with performance data brightly illuminated.

**Theme:** dark

Peloton's design system exudes a premium, focused energy through a dark, high-contrast palette and precise typography. The deep charcoal surfaces with stark white text create an immersive, yet highly legible experience. A vibrant, singular red accent provides crucial points of interaction and brand identity, while large, rounded buttons soften the overall intensity, making the powerful machinery feel approachable.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Peloton Red | `#df1c2f` | `--color-peloton-red` | Primary accent for CTAs, active states, and key brand elements – providing urgency and a singular pop of energy against the dark neutrals. |
| Charcoal Black | `#181a1d` | `--color-charcoal-black` | Dominant background for pages, cards, and overall UI. This deep, near-black provides a premium, immersive canvas. |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color for headlines and body copy, button text, and icon fills against dark backgrounds. Ensures maximum legibility. |
| Cool Gray | `#65666a` | `--color-cool-gray` | Secondary text, subtle borders, and inactive states. Provides hierarchy and reduces visual noise while maintaining contrast. |
| Light Pearl | `#f7f7f7` | `--color-light-pearl` | Subtle background for specific sections or as an alternative to Pure White, offering a slight softness. |
| Silver Mist | `#e4e6e7` | `--color-silver-mist` | Minor backgrounds, subtle dividers, or hover states for neutral elements. |
| Stone Gray | `#a8acb1` | `--color-stone-gray` | Placeholder text, less critical information, and iconography. A softer neutral than Cool Gray. |
| Concrete Gray | `#888b93` | `--color-concrete-gray` | Input borders and secondary visual cues, indicating interactive but not primary elements. |
| Shadow Gradient | `linear-gradient(300deg, rgb(168, 172, 177), rgb(245, 247, 249), rgb(168, 172, 177))` | `--color-shadow-gradient` | Subtle background gradient for specific UI elements or sections, adding depth without strong color. Evokes metallic sheen. |

## Tokens — Typography

### Inter — The sole typeface, Inter, handles all text roles from body to display. Its modern, sans-serif neutrality supports the technical-yet-approachable brand image. Usage of varied weights, particularly 300 for some larger text and a prominent 0.0250em tracking on some elements, allows for distinct vocal tones without introducing new fonts. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 26px, 32px, 36px, 48px
- **Line height:** 1.07, 1.20, 1.25, 1.30, 1.33, 1.38, 1.39, 1.50, 1.69, 1.71
- **Letter spacing:** -0.0080em, -0.0060em, -0.0040em, 0.0250em
- **Role:** The sole typeface, Inter, handles all text roles from body to display. Its modern, sans-serif neutrality supports the technical-yet-approachable brand image. Usage of varied weights, particularly 300 for some larger text and a prominent 0.0250em tracking on some elements, allows for distinct vocal tones without introducing new fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.38 | — | `--text-body-sm` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.39 | — | `--text-subheading` |
| heading | 20px | 1.25 | — | `--text-heading` |
| heading-lg | 26px | 1.39 | — | `--text-heading-lg` |
| display-sm | 32px | 1.33 | — | `--text-display-sm` |
| display | 36px | 1.2 | — | `--text-display` |
| display-lg | 48px | 1.07 | -0.48px | `--text-display-lg` |

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
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 204px |
| cards | 0px |
| images | 6px |
| inputs | 2px |
| buttons | 28px |
| default | 6px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Primary Call to Action

Solid Peloton Red background (#df1c2f) with Pure White text (#ffffff). Features a large 28px border-radius, giving it a friendly, prominent pill-like shape. Padding: 0px vertical, 22px horizontal, creating an elongated form.

### Text Link Button (Invisible)
**Role:** Navigation and subtle interactions

Transparent background with Charcoal Black text (#181a1d). Features 0px border-radius and padding, appearing as pure text that functions as a button. Used for navigation items.

### Rounded Icon Button (Ghost)
**Role:** Interactive icons, secondary actions

Transparent background with Charcoal Black text/icon (#181a1d). Has a 50% border-radius for a perfect circle and 0px padding. Often used for functional icons like account or cart, blending into the UI until interacted with.

### Rounded Icon Button (Subtle Fill)
**Role:** Interactive icons with subtle visual emphasis

Translucent dark gray background (rgba(101, 102, 106, 0.6)) with Charcoal Black text/icon (#181a1d). Features a 50% border-radius and 0px padding, providing a slightly more visually distinct circular button than the ghost variant.

### Product Card
**Role:** Displaying product items

Transparent background (rgba(0,0,0,0)) with 0px border-radius and no box-shadow, allowing content to define its shape. 0px padding, meaning content fills the full card area. Content elements within the card (like images) use a 6px border-radius.

### Standard Input Field
**Role:** User data entry

Pure White background (#ffffff) with Charcoal Black text (#181a1d). Defined by a Concrete Gray border (#888b93) and a small 2px border-radius. Padding of 14px top, 0px bottom, 12px right/left on visible text, suggesting an internal content offset.

## Do's and Don'ts

### Do
- Use Peloton Red (#df1c2f) exclusively for primary CTAs and critical interactive elements to maintain its high impact.
- Maintain high contrast by pairing Pure White text (#ffffff) with Charcoal Black (#181a1d) backgrounds for maximum legibility.
- Apply 28px border-radius to all primary buttons for a consistent, soft-edged, pill-like appearance.
- Use Inter font family for all text elements, leveraging weights (300-700) and specific letter-spacing (-0.008em to 0.025em) to differentiate hierarchy.
- Employ Charcoal Black (#181a1d) as the primary page and section background to establish a premium, dark aesthetic.
- Utilize 0px border-radius for product cards, allowing internal elements to contain their own radii for visual interest.
- Ensure input fields have a 2px border-radius and Concrete Gray (#888b93) border to visually distinguish them from other interactive elements.

### Don't
- Do not introduce additional accent colors; Peloton Red is the single chromatic accent.
- Avoid using box-shadows for elevation; rely on color temperature and surface changes (e.g., translucent fills, gradients) to indicate depth.
- Do not deviate from Inter font family; achieve variety through weights and letter-spacing instead.
- Do not use generic, unrounded buttons; all primary interactive buttons should have the signature 28px radius.
- Avoid excessive spacing between elements; use the base unit of 8px for element gaps to maintain a comfortable density.
- Do not use highly saturated images; imagery should blend with the dark aesthetic, often appearing desaturated or dark-toned.

## Imagery

Imagery primarily consists of product photography, featuring Peloton equipment in dark, studio-like environments. Products are often showcased in tight crops or isolated with subtle ambient lighting, emphasizing their form and function. There's an absence of lifestyle photography or complex scenic backgrounds. Icons are monochrome, often integrated into buttons or navigation, reinforcing the clean, functional aesthetic. Abstract gradients are used sparingly as subtle background elements to add depth, replacing traditional shadows.

## Layout

The layout follows a centered, max-width contained model (though no explicit max-width is indicated, content appears centered). The hero section is full-bleed, using a dark background with centered, prominent typography and action buttons. Sections generally feature consistent vertical spacing, creating clear divisions without harsh lines. Content is often stacked centrally or arranged in simple column structures. Card grids are used for product lineups, presenting items with minimal visual boundaries. Navigation is a top-bar sticky header, complemented by a persistent chat button.

## Agent Prompt Guide

### Quick Color Reference
- Text: #ffffff (Pure White)
- Background: #181a1d (Charcoal Black)
- CTA: #df1c2f (Peloton Red)
- Border: #888b93 (Concrete Gray)
- Accent: #df1c2f (Peloton Red)

### 3-5 Example Component Prompts
1. **Create a hero section:** Use `Charcoal Black` background `#181a1d`. Headline: 'The Cross Training Series' `Inter` `48px` `weight 700` `lineHeight 1.07` `letterSpacing -0.48px`, color `Pure White` `#ffffff`. Sub-headline: 'Powered by Peloton IQ' `Inter` `26px` `weight 500` `lineHeight 1.39`, color `Pure White` `#ffffff`. Body text: 'the next era of fitness is here.' `Inter` `18px` `weight 400` `lineHeight 1.39`, color `Cool Gray` `#65666a`. Two `Primary Filled Buttons` with text 'Explore Bike+' and 'Explore Tread+'.
2. **Generate a Primary Filled Button:** Text 'Get Started'. Background `Peloton Red` `#df1c2f`, text color `Pure White` `#ffffff`. `border-radius: 28px`. `padding: 0px 22px` for inner text.
3. **Design a Product Card:** Transparent background (rgba(0,0,0,0)), `border-radius: 0px`. Placeholder image with `6px border-radius`. Title: 'Peloton Bike' `Inter` `20px` `weight 600`, color `Pure White` `#ffffff`. Price: 'From $1495' `Inter` `16px` `weight 400`, color `Cool Gray` `#65666a`.
4. **Create a Header Navigation Link:** Text 'Apparel', `Inter` `16px` `weight 500`, color `Pure White` `#ffffff`. No background, no border-radius, `0px` padding. On hover, change background to `Peloton Red` `#df1c2f`.
5. **Build an Input Field:** Placeholder text 'Your Email', `Inter` `15px` `weight 400`, color `Cool Gray` `#65666a`. Background `Pure White` `#ffffff`, `border: 1px solid Concrete Gray` `#888b93`, `border-radius: 2px`. `padding-top: 14px`, `padding-left: 12px`.

## Similar Brands

- **Apple** — Shares a use of dark, desaturated photography for products against dark backgrounds, minimalist UI, and a focused color palette.
- **Tesla** — Employs a dark, high-contrast, tech-forward aesthetic with sparse, high-quality product imagery and strong typography.
- **Dyson** — Showcases premium products with clean, almost-monochromatic backgrounds and relies on distinctive single accent colors for brand identity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-peloton-red: #df1c2f;
  --color-charcoal-black: #181a1d;
  --color-pure-white: #ffffff;
  --color-cool-gray: #65666a;
  --color-light-pearl: #f7f7f7;
  --color-silver-mist: #e4e6e7;
  --color-stone-gray: #a8acb1;
  --color-concrete-gray: #888b93;
  --color-shadow-gradient: #a8acb1;
  --gradient-shadow-gradient: linear-gradient(300deg, rgb(168, 172, 177), rgb(245, 247, 249), rgb(168, 172, 177));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.38;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.39;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.39;
  --text-display-sm: 32px;
  --leading-display-sm: 1.33;
  --text-display: 36px;
  --leading-display: 1.2;
  --text-display-lg: 48px;
  --leading-display-lg: 1.07;
  --tracking-display-lg: -0.48px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-104: 104px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 204px;

  /* Named Radii */
  --radius-pill: 204px;
  --radius-cards: 0px;
  --radius-images: 6px;
  --radius-inputs: 2px;
  --radius-buttons: 28px;
  --radius-default: 6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-peloton-red: #df1c2f;
  --color-charcoal-black: #181a1d;
  --color-pure-white: #ffffff;
  --color-cool-gray: #65666a;
  --color-light-pearl: #f7f7f7;
  --color-silver-mist: #e4e6e7;
  --color-stone-gray: #a8acb1;
  --color-concrete-gray: #888b93;
  --color-shadow-gradient: #a8acb1;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.38;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.39;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --text-heading-lg: 26px;
  --leading-heading-lg: 1.39;
  --text-display-sm: 32px;
  --leading-display-sm: 1.33;
  --text-display: 36px;
  --leading-display: 1.2;
  --text-display-lg: 48px;
  --leading-display-lg: 1.07;
  --tracking-display-lg: -0.48px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 204px;
}
```
