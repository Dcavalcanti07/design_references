# Moving Parts — Style Reference
> High-contrast geometric clarity

**Theme:** light

Moving Parts employs a bold, high-contrast aesthetic characterized by large, confident typography and a vibrant blue accent on an otherwise monochrome canvas. Geometric shapes and a grid-like structure provide underlying order, while distinct large radii soften component edges. The design feels sharp and modern, with a strong focus on readability for headlines and crisp functional elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headers, icon strokes, borders, and some background fills on dark sections. High contrast establishes a strong visual hierarchy |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, secondary text on dark backgrounds, and icon fills. Provides a bright, expansive foundation |
| Ghostly Gray | `#121212` | `--color-ghostly-gray` | Secondary text in dark sections, subtle borders, and some elevated dark surfaces. Supports the dark mode appearance with a slightly softer black |
| Fog Grid | `#bcc1c7` | `--color-fog-grid` | Decorative background grids and subtle outlines. Creates texture without distracting from content |
| Warm Mist | `#efefef` | `--color-warm-mist` | Subtle background panels and soft dividers. Adds a touch of warmth to the neutral palette |
| Cloud Gray | `#b3b3b3` | `--color-cloud-gray` | Less prominent text, borders, and subtle shadow effects. Indicates inactive states or secondary information |
| Pale Ash | `#999999` | `--color-pale-ash` | Muted helper text and tertiary information. Recedes into the background for less critical content |
| Deep Royal Blue | `#0000ff` | `--color-deep-royal-blue` | Primary action buttons, interactive elements, highlights, and featured backgrounds. This vivid blue serves as the sole dominant brand accent |
| Emerald Green | `#00d37c` | `--color-emerald-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Conic Spectrum | `conic-gradient(rgb(87, 192, 241) 0%, rgb(74, 166, 232) 13%, rgb(134, 57, 162) 26%, rgb(239, 137, 159) 42%, rgb(234, 57, 42) 55%, rgb(239, 115, 53) 62%, rgb(245, 192, 68) 73%, rgb(245, 255, 84) 84%, rgb(160, 218, 83) 95%, rgb(87, 192, 241) 100%)` | `--color-conic-spectrum` | Decorative gradients in abstract visuals or hero sections. Adds a burst of multi-chromatic energy |

## Tokens — Typography

### Whyte Semi-Mono — Body text, smaller headings, and supplementary information. Its semi-monospaced nature adds a technical, precise feel. · `--font-whyte-semi-mono`
- **Substitute:** Space Mono
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 17px, 18px, 21px, 25px, 27px, 30px, 34px, 35px
- **Line height:** 1.06, 1.15, 1.18, 1.20, 1.36, 1.89, 2.38
- **Letter spacing:** -0.0060em at 35px, 0.0100em at 27px, 0.0400em at 12px
- **Role:** Body text, smaller headings, and supplementary information. Its semi-monospaced nature adds a technical, precise feel.

### Unica77 — Primary headings, navigation, and prominent callouts. Features like 'ss01' for alternate glyphs give it specific brand character. · `--font-unica77`
- **Substitute:** Roboto
- **Weights:** 400, 500, 600, 700
- **Sizes:** 18px, 21px, 22px, 23px, 26px, 27px, 28px, 30px, 31px, 32px, 35px, 38px, 40px, 47px, 51px, 53px, 58px, 62px, 67px, 70px, 100px, 110px
- **Line height:** 0.92, 0.93, 0.94, 0.95, 0.96, 1.00, 1.05, 1.12, 1.19, 1.20, 1.21, 1.22, 1.27, 1.32, 1.37, 1.47, 1.61, 1.71, 1.81
- **Letter spacing:** -0.0400em at 110px, -0.0300em at 62px, -0.0050em at 32px, -0.0040em at 22px, 0.0100em at 21px, 0.0300em at 18px, 0.0400em at 18px
- **OpenType features:** `"salt", "ss01", "ss02", "ss03", "ss04", "ss05", "ss07", "ss08", "ss09"`
- **Role:** Primary headings, navigation, and prominent callouts. Features like 'ss01' for alternate glyphs give it specific brand character.

### PP Neue Montreal — Large, impactful display headlines where tight tracking enhances presence. Used for key section titles. · `--font-pp-neue-montreal`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 27px, 32px, 60px, 81px, 98px
- **Line height:** 0.82, 0.84, 0.85, 0.87, 1.20, 1.21
- **Letter spacing:** -0.0300em at 98px, -0.0100em at 60px, 0.0100em at 27px
- **Role:** Large, impactful display headlines where tight tracking enhances presence. Used for key section titles.

### Druk XXCondensed Super — Massive, compressed display typography for highly visual statements, often paired with graphical elements. · `--font-druk-xxcondensed-super`
- **Substitute:** Oswald Condensed
- **Weights:** 400
- **Sizes:** 195px, 248px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Massive, compressed display typography for highly visual statements, often paired with graphical elements.

### Inter — Inter — detected in extracted data but not described by AI · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 25px, 27px, 28px, 35px, 37px, 42px, 52px
- **Line height:** 0.98, 1.2, 1.38, 1.48
- **Letter spacing:** -0.004, -0.003
- **Role:** Inter — detected in extracted data but not described by AI

### ui-monospace — ui-monospace — detected in extracted data but not described by AI · `--font-ui-monospace`
- **Weights:** 400
- **Sizes:** 26px
- **Line height:** 1.2
- **Role:** ui-monospace — detected in extracted data but not described by AI

### Fraunces 72pt Soft — Fraunces 72pt Soft — detected in extracted data but not described by AI · `--font-fraunces-72pt-soft`
- **Weights:** 100, 200
- **Sizes:** 27px, 36px, 60px
- **Line height:** 1.2, 1.29, 1.35
- **OpenType features:** `"ss01"`
- **Role:** Fraunces 72pt Soft — detected in extracted data but not described by AI

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400, 500, 600
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Fraunces 72pt SuperSoft — Fraunces 72pt SuperSoft — detected in extracted data but not described by AI · `--font-fraunces-72pt-supersoft`
- **Weights:** 200
- **Sizes:** 45px
- **Line height:** 1.06
- **Letter spacing:** -0.01
- **OpenType features:** `"ss01"`
- **Role:** Fraunces 72pt SuperSoft — detected in extracted data but not described by AI

### TAN-BUSTER — TAN-BUSTER — detected in extracted data but not described by AI · `--font-tan-buster`
- **Weights:** 600
- **Sizes:** 91px
- **Line height:** 1.18
- **OpenType features:** `"ss01"`
- **Role:** TAN-BUSTER — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 17px | 1.18 | -0.1px | `--text-body` |
| subheading | 21px | 1.2 | 0.21px | `--text-subheading` |
| heading-sm | 27px | 1.2 | 0.27px | `--text-heading-sm` |
| heading | 60px | 0.85 | -0.6px | `--text-heading` |
| heading-lg | 98px | 0.82 | -2.94px | `--text-heading-lg` |
| display | 248px | 1.2 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 120 | 120px | `--spacing-120` |
| 148 | 148px | `--spacing-148` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 90.3833px |
| icons | 18px |
| images | 14px |
| buttons | 0px |
| largeCards | 106.333px |
| smallElements | 2.5px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.3) 15px 20px 30px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 40px
- **Card padding:** 30px
- **Element gap:** 13px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled button with 'Deep Royal Blue' background, 'Canvas White' text, and 0px border radius. Padding set to 25px vertical, 30px horizontal. Uses Unica77 font.

### Ghost Button (Primary)
**Role:** Secondary action or navigation

Ghost button with transparent background, 'Midnight Ink' text, and 0px border radius. Padding set to 25px vertical, 30px horizontal. Uses Unica77 font.

### Pill Button (Neutral)
**Role:** Status tags or filters

Pill-shaped button with 'Cloud Gray' background, 'Midnight Ink' text, and 18px border-radius. Minimal padding.

### Rounded Corner Card
**Role:** Content container

Card with 'Canvas White' background and 90.3833px border radius. No box shadow evident, assumes a flat presentation.

### Large Rounded Card (Bottom-Flat)
**Role:** Hero or feature container

Card with 'Deep Royal Blue' background and 106.333px 106.333px 0px 0px border-radius, creating a flat bottom edge. No box shadow evident. Large-scale component.

### Text Input (Base)
**Role:** Single-line text entry

Input field with 'Canvas White' background, 'Midnight Ink' text, and 0px border radius. Padding set to 25px vertical, 30px horizontal. Uses Unica77.

## Do's and Don'ts

### Do
- Use 'Midnight Ink' (#000000) for all primary text and headlines to maintain strong contrast.
- Apply 'Deep Royal Blue' (#0000ff) exclusively for primary calls to action and critical interactive elements.
- Utilize Unica77 for headlines and navigation, leveraging its font feature settings for characteristic glyphs and precise tracking.
- Favor large, confident typography for headlines, with tighter letter-spacing on larger sizes and normal spacing on body text.
- Maintain a clear visual hierarchy by limiting saturated colors to 'Deep Royal Blue' and 'Emerald Green' as deliberate accents.
- Employ the specific large border radii of 90.3833px for content cards and 106.333px for prominent containers to define component shapes.
- Ensure all interactive elements provide a comfortable 25px vertical and 30px horizontal padding, as seen on buttons and inputs.

### Don't
- Do not introduce new saturated primary colors; adhere to 'Deep Royal Blue' as the sole dominant brand accent.
- Avoid generic small border radii; use the distinct 0px for buttons or the large values (90.3833px, 106.333px) for cards and containers.
- Do not use subtle gray backgrounds or text colors for primary content or calls to action; reserve them for secondary information or decorative grids.
- Do not add additional box-shadows beyond the single defined `rgba(0, 0, 0, 0.3) 15px 20px 30px 0px` for cards, maintaining a predominantly flat aesthetic.
- Do not break the rigid grid-like layout with free-form overlapping elements, maintaining structured geometric compositions.
- Avoid thin, lightweight typefaces for headlines outside of specific decorative uses; default to heavier weights for impact.
- Do not use 'Arial' or 'ui-monospace' for standard UI elements unless explicitly for code snippets, adhering to the brand's custom typefaces.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and default card surface. |
| 1 | Warm Mist | `#efefef` | Soft background distinction for sections or subtle component elevation. |
| 2 | Ghostly Gray | `#121212` | Accent background for dark sections or strong visual breaks. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.3) 15px 20px 30px 0px`

## Imagery

Imagery primarily consists of bright product screenshots of mobile UI components, often set against a 'Deep Royal Blue' background, emphasizing the product's native context. Abstract geometric shapes, sometimes with vivid conic gradients, act as decorative elements, adding visual interest and motion. Icons are outlined, with a moderate stroke weight, typically 'Midnight Ink' or inverse 'Canvas White', keeping to a minimalist, functional aesthetic. Photography is minimal, used for social proof or team profiles in a clean, high-contrast style. Visual density is balanced: product showcases are image-heavy, while explanatory sections are text-dominant with functional icons.

## Layout

The page primarily uses a max-width contained layout, likely centered, although a specific max-width is not provided. The hero section is characterized by a full-width visual, often a dark background or distinct product visual, with a large, centered headline and a clear call to action below. Section rhythm is driven by alternating background colors (white, dark, solid brand blue) creating distinct blocks of content. Content within sections is often arranged in prominent single-column stacks for headlines, or two-column text-left/image-right or image-left/text-right patterns for feature explanations. Large components like cards can extend this two-column approach to highlight product visuals. Typography dominates the visual hierarchy, with large headlines guiding the eye. Navigation is a persistent top bar, minimal and un-obtrusive.

## Agent Prompt Guide

primary action: #0000ff (filled action)
Create a Primary Action Button: #0000ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a Feature Card: 'Canvas White' (#ffffff) background, 90.3833px border-radius. Headline (Unica77, 32px, weight 700, 'Midnight Ink'). Body text (Whyte Semi-Mono, 17px, weight 400, 'Midnight Ink'). Internal padding of 30px.

Create a Navigation Item: 'Midnight Ink' (#000000) text (Unica77, 21px, weight 500, line-height 1.2) against a 'Canvas White' (#ffffff) background. Normal letter-spacing.

Create an Icon Button: 'Midnight Ink' (#000000) text (Whyte Semi-Mono, 12px, weight 400) or 'Deep Royal Blue' (#0000ff) icon stroke on a 'Canvas White' (#ffffff) background with 18px border radius for the interactive part. Element gap 13px.

## Similar Brands

- **Framer** — Uses large, confident typography against a clean, often monochrome background, with strong accent colors for interactive elements.
- **Linear** — Employs high-contrast text and a minimalist aesthetic with a focus on sharp, functional UI elements and a controlled color palette.
- **Spline** — Features bold, geometric layouts, strong typographic hierarchy, and a limited but impactful accent color.
- **Vercel** — Characterized by its dark mode, high-contrast text, command-line aesthetics, and clean display of code and product snippets.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-ghostly-gray: #121212;
  --color-fog-grid: #bcc1c7;
  --color-warm-mist: #efefef;
  --color-cloud-gray: #b3b3b3;
  --color-pale-ash: #999999;
  --color-deep-royal-blue: #0000ff;
  --color-emerald-green: #00d37c;
  --color-conic-spectrum: #57C0F1;
  --gradient-conic-spectrum: conic-gradient(rgb(87, 192, 241) 0%, rgb(74, 166, 232) 13%, rgb(134, 57, 162) 26%, rgb(239, 137, 159) 42%, rgb(234, 57, 42) 55%, rgb(239, 115, 53) 62%, rgb(245, 192, 68) 73%, rgb(245, 255, 84) 84%, rgb(160, 218, 83) 95%, rgb(87, 192, 241) 100%);

  /* Typography — Font Families */
  --font-whyte-semi-mono: 'Whyte Semi-Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-unica77: 'Unica77', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-druk-xxcondensed-super: 'Druk XXCondensed Super', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fraunces-72pt-soft: 'Fraunces 72pt Soft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fraunces-72pt-supersoft: 'Fraunces 72pt SuperSoft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tan-buster: 'TAN-BUSTER', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 17px;
  --leading-body: 1.18;
  --tracking-body: -0.1px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.21px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.27px;
  --text-heading: 60px;
  --leading-heading: 0.85;
  --tracking-heading: -0.6px;
  --text-heading-lg: 98px;
  --leading-heading-lg: 0.82;
  --tracking-heading-lg: -2.94px;
  --text-display: 248px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-120: 120px;
  --spacing-148: 148px;
  --spacing-172: 172px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 30px;
  --element-gap: 13px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-3xl: 24.1667px;
  --radius-3xl-2: 30.4583px;
  --radius-3xl-3: 35px;
  --radius-full: 50px;
  --radius-full-2: 72.5px;
  --radius-full-3: 76.6667px;
  --radius-full-4: 83.3333px;
  --radius-full-5: 90.3833px;
  --radius-full-6: 106.333px;

  /* Named Radii */
  --radius-cards: 90.3833px;
  --radius-icons: 18px;
  --radius-images: 14px;
  --radius-buttons: 0px;
  --radius-largecards: 106.333px;
  --radius-smallelements: 2.5px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.3) 15px 20px 30px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-mist: #efefef;
  --surface-ghostly-gray: #121212;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-ghostly-gray: #121212;
  --color-fog-grid: #bcc1c7;
  --color-warm-mist: #efefef;
  --color-cloud-gray: #b3b3b3;
  --color-pale-ash: #999999;
  --color-deep-royal-blue: #0000ff;
  --color-emerald-green: #00d37c;
  --color-conic-spectrum: #57C0F1;

  /* Typography */
  --font-whyte-semi-mono: 'Whyte Semi-Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-unica77: 'Unica77', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-druk-xxcondensed-super: 'Druk XXCondensed Super', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fraunces-72pt-soft: 'Fraunces 72pt Soft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fraunces-72pt-supersoft: 'Fraunces 72pt SuperSoft', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tan-buster: 'TAN-BUSTER', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 17px;
  --leading-body: 1.18;
  --tracking-body: -0.1px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.21px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.27px;
  --text-heading: 60px;
  --leading-heading: 0.85;
  --tracking-heading: -0.6px;
  --text-heading-lg: 98px;
  --leading-heading-lg: 0.82;
  --tracking-heading-lg: -2.94px;
  --text-display: 248px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-120: 120px;
  --spacing-148: 148px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-3xl: 24.1667px;
  --radius-3xl-2: 30.4583px;
  --radius-3xl-3: 35px;
  --radius-full: 50px;
  --radius-full-2: 72.5px;
  --radius-full-3: 76.6667px;
  --radius-full-4: 83.3333px;
  --radius-full-5: 90.3833px;
  --radius-full-6: 106.333px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.3) 15px 20px 30px 0px;
}
```
