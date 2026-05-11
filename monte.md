# Monte — Style Reference
> Warm Terracotta Cafe

**Theme:** light

Monte evokes a warm, rustic cafe atmosphere with a distinctive terracotta brand color, soft cream backgrounds, and strong typographic contrast. The design emphasizes clear hierarchy through a limited color palette focused on the primary brand hue and subtle neutrals. Components are lightweight with defined borders and generous rounded corners, suggesting an approachable, handcrafted feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Terracotta | `#b84b30` | `--color-terracotta` | Dominant brand color, used for backgrounds, card surfaces, primary text accents, and interactive elements. It defines the site's entire warm visual identity |
| Espresso Shot | `#5f1d1a` | `--color-espresso-shot` | Deep, almost-black accent color used for secondary text and decorative fills, providing rich visual contrast |
| Cream Canvas | `#f8f4e9` | `--color-cream-canvas` | Primary page background and light surface color, creates a soft, inviting base for content |
| Silver Border | `#e5e7eb` | `--color-silver-border` | Subtle border color for UI elements and dividers, offering a delicate visual separation |
| Carbon Text | `#000000` | `--color-carbon-text` | Main body text and icon fill color, ensuring high contrast on light backgrounds |
| Pure Frost | `#ffffff` | `--color-pure-frost` | Inverse text color for dark backgrounds and occasional UI accents |
| Stone Gray | `#666666` | `--color-stone-gray` | Secondary text color for less emphasized information |
| Medium Gray | `#999999` | `--color-medium-gray` | Muted text or decorative details |
| Dark Overlay | `#3e3d3a` | `--color-dark-overlay` | Subtle dark overlay used for specific badge backgrounds |

## Tokens — Typography

### Riposte — Primary display font for headings, calls to action, and prominent page elements. Its varying letter spacing and weights give it a distinct, almost custom-drawn feel, contributing to the brand's unique identity. · `--font-riposte`
- **Substitute:** Georgia, serif
- **Weights:** 400, 600
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 17px, 20px, 23px, 24px, 36px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.25, 1.35, 1.40
- **Letter spacing:** 0.025em, 0.05em, 0.1em
- **Role:** Primary display font for headings, calls to action, and prominent page elements. Its varying letter spacing and weights give it a distinct, almost custom-drawn feel, contributing to the brand's unique identity.

### Apercu Mono — Used for body text, descriptive labels, and input fields. Its monospaced nature and subtle negative letter-spacing add a hint of vintage or functional print aesthetic, balancing the more expressive display font. · `--font-apercu-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px, 15px, 16px
- **Line height:** 1.33, 1.35
- **Letter spacing:** -0.025em
- **Role:** Used for body text, descriptive labels, and input fields. Its monospaced nature and subtle negative letter-spacing add a hint of vintage or functional print aesthetic, balancing the more expressive display font.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.05px | `--text-caption` |
| heading-sm | 20px | 1.1 | — | `--text-heading-sm` |
| heading | 24px | 1 | 0.025px | `--text-heading` |
| display | 36px | 0.9 | 0.1px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| inputs | 9999px |
| buttons | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 5px

## Components

### Ghost Header Button
**Role:** Navigation and secondary actions.

Text in Carbon Text (#000000) on a transparent background, with no defined border radius. Padding of 0px vertical and 16px horizontal. Uses Riposte font.

### Outlined Call to Action Button
**Role:** Primary interactive element.

Text in Terracotta (#b84b30) on a Cream Canvas (#f8f4e9) background, with a 1px Terracotta (#b84b30) border and 9999px border-radius. Padding is 12px vertical and 24px horizontal. Uses Riposte font.

### Terracotta Feature Card
**Role:** Highlights features or product categories.

Terracotta (#b84b30) background with a 14px border-radius. No padding or box-shadow. Imagery or content is placed directly within.

### Transparent Image Overlay Card
**Role:** Used for subtle visual effects over images.

Semi-transparent black (rgba(0,0,0,0.15)) background with 0px border-radius. No padding or box-shadow. Designed to blend with underlying images.

### Rounded Input Field
**Role:** User data entry.

Cream Canvas (#f8f4e9) background, Terracotta (#b84b30) accent text and border, with a 9999px border-radius for a pill-like shape. Padding is 12px vertical and 24px horizontal.

### Ghost Badge
**Role:** Decorative labels or textual accents.

Terracotta (#b84b30) text on a transparent background, 0px border-radius, with 12px vertical padding. Uses Riposte font.

### Overlay Badge
**Role:** Informational labels on darker backgrounds.

White (#ffffff) text on a Dark Overlay (#3e3d3a) background, 0px border-radius. No padding. Uses Riposte font.

## Do's and Don'ts

### Do
- Use Terracotta (#b84b30) as the primary brand color for backgrounds, key interactive elements, and prominent headings to maintain brand identity.
- Apply Cream Canvas (#f8f4e9) as the default page background and for light surface elements, ensuring a soft, inviting base.
- Employ the Riposte font for all headlines, navigation, and call-to-action text, leveraging its distinct letter-spacing and weights for brand personality.
- Utilize Apercu Mono font for body copy and input fields, pairing its functional mono-spaced character with the expressive display font.
- Always use a 9999px border-radius for input fields and an outlined style for primary action buttons to achieve a soft, approachable aesthetic.
- Ensure generous vertical spacing between sections (48px) to create a relaxed, comfortable density.
- Employ the Silver Border (#e5e7eb) for subtle dividers and borders on neutral backgrounds to maintain a delicate visual separation.

### Don't
- Avoid using bright, saturated colors not present in the defined palette, as they will clash with the warm, muted brand theme.
- Do not introduce sharp, angular card or button radii; the system favors soft curves (14px for cards, 9999px for inputs, 0px for navigation buttons).
- Under no circumstances substitute the custom `Riposte` or `Apercu Mono` fonts without ensuring the chosen alternative carries the same distinctive letter-spacing and weight properties.
- Do not use heavy box-shadows; the design favors flat surfaces and borders for depth.
- Avoid excessive use of different font colors; stick to Terracotta, Espresso Shot, Carbon Text, Stone Gray, and Pure Frost to maintain a cohesive scheme.
- Do not create dense, text-heavy blocks without sufficient line height; Riposte and Apercu Mono lines should breathe with their specified line heights.
- Do not use dark backgrounds for entire sections unless Terracotta or Dark Overlay are specifically employed to align with brand colors, otherwise stick to Cream Canvas.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cream Canvas | `#f8f4e9` | Base page background |
| 1 | Terracotta Surface | `#b84b30` | Primary brand surface for hero sections, footer, and feature cards |
| 2 | Dark Overlay Surface | `#3e3d3a` | Specific badge backgrounds, providing contrast for white text |

## Imagery

Imagery primarily features in-situ cafe photography with a warm, natural lighting. Product-focused shots of food and drinks are vibrant and inviting, often with soft backgrounds that don't distract. Illustrations are hand-drawn, line-art style, depicting simple, organic forms of people or objects (like coffee cups) in the Terracotta brand color, serving as decorative accents. Icons are minimal, outlined, in Carbon Text, and used functionally for navigation. Visuals balance atmospheric photography with charming, characterful illustrations, lending a friendly and casual brand feel.

## Layout

The page uses a centered, max-width layout (implicitly around 1200px based on content centering, though not fixed) with a dynamic hero section. The initial hero is full-bleed Terracotta featuring centered large text and an illustrative graphic. Scrolling reveals a Cream Canvas background with a soft card stack containing images. Content sections alternate between images and text, often in a left-right arrangement, with consistent vertical spacing of 48px between major blocks. A fixed header provides minimalist navigation. The overall rhythm is unhurried and spacious, creating a comfortable browsing experience.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f8f4e9
border: #e5e7eb
accent: #b84b30
primary action: #b84b30 (outlined action border)

Example Component Prompts:
1. Create a header navigation button: transparent background, Carbon Text (#000000), Riposte font, weight 400, 0px vertical padding, 16px horizontal padding.
2. Create an Outlined Primary Action: Transparent background, #b84b30 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
3. Create a feature card: Terracotta (#b84b30) background, 14px border-radius, no padding, no shadow.
4. Create a text input field: Cream Canvas (#f8f4e9) background, Terracotta (#b84b30) text and 1px border, Apercu Mono font, weight 400, 12px vertical padding, 24px horizontal padding, 9999px border-radius.
5. Create a ghost badge with Terracotta text: transparent background, Terracotta (#b84b30) text, Riposte font, weight 400, 12px vertical padding, 0px border-radius.

## Similar Brands

- **Aesthetics Coffee** — Similar use of warm, earthy color palettes and minimalist branding for a cafe experience.
- **Ritual Coffee Roasters** — Employs custom typography and a distinct, artisanal feel in their web presence, much like Monte.
- **Intelligentsia Coffee** — Blends clean typography with warm imagery to evoke a sophisticated yet approachable coffee brand.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-terracotta: #b84b30;
  --color-espresso-shot: #5f1d1a;
  --color-cream-canvas: #f8f4e9;
  --color-silver-border: #e5e7eb;
  --color-carbon-text: #000000;
  --color-pure-frost: #ffffff;
  --color-stone-gray: #666666;
  --color-medium-gray: #999999;
  --color-dark-overlay: #3e3d3a;

  /* Typography — Font Families */
  --font-riposte: 'Riposte', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono: 'Apercu Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.05px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.1;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: 0.025px;
  --text-display: 36px;
  --leading-display: 0.9;
  --tracking-display: 0.1px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-inputs: 9999px;
  --radius-buttons: 0px;

  /* Surfaces */
  --surface-cream-canvas: #f8f4e9;
  --surface-terracotta-surface: #b84b30;
  --surface-dark-overlay-surface: #3e3d3a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-terracotta: #b84b30;
  --color-espresso-shot: #5f1d1a;
  --color-cream-canvas: #f8f4e9;
  --color-silver-border: #e5e7eb;
  --color-carbon-text: #000000;
  --color-pure-frost: #ffffff;
  --color-stone-gray: #666666;
  --color-medium-gray: #999999;
  --color-dark-overlay: #3e3d3a;

  /* Typography */
  --font-riposte: 'Riposte', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apercu-mono: 'Apercu Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.05px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.1;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: 0.025px;
  --text-display: 36px;
  --leading-display: 0.9;
  --tracking-display: 0.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-full: 9999px;
}
```
