# Handsome Frank — Style Reference
> Artistic Jungle Canvas

**Theme:** light

Handsome Frank's visual system evokes a vibrant, artistic jungle, leveraging bold colorful blocks against clean, spacious backgrounds. Typography is a confident mix of a bespoke serif for headlines, featuring tight letter-spacing for impact, and a versatile sans-serif for body text. The overall feel is one of creative energy and precision, using color as an active, functional element rather than mere decoration. Layouts are structured but dynamic, allowing hero illustrations to breathe color into the composition.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#160572` | `--color-midnight-ink` | Primary brand color, secondary text against light backgrounds, interactive navigation elements, and decorative strokes in hero sections. Also defines subtle bounding boxes around content |
| Fiery Red | `#ea0706` | `--color-fiery-red` | Accent for headings and other decorative elements. Provides a warm, energetic contrast |
| Warm Ginger | `#e29675` | `--color-warm-ginger` | Decorative accent for headings, links, and icons, adding a subtle, earthy vibrancy |
| Terracotta Orange | `#d64e2e` | `--color-terracotta-orange` | Decorative accent for headings, links, and icons. A bolder, more saturated version of Warm Ginger |
| Crimson Edge | `#df1a19` | `--color-crimson-edge` | Accent for headings, a slightly deeper red than Fiery Red |
| Aqua Glow | `#24e3dc` | `--color-aqua-glow` | Decorative accent for links and other interactive elements, providing a cool, modern highlight |
| Sunny Marigold | `#f9e44d` | `--color-sunny-marigold` | Decorative accent for headings, links, and icons, bringing cheerful energy |
| Warm Canvas Yellow | `#fffac2` | `--color-warm-canvas-yellow` | Background color for headings where a subtle, muted yellow tint is desired |
| Illustrator Blue | `#2544a0` | `--color-illustrator-blue` | Background for primary call-to-action buttons, signaling a direct interaction point |
| Pumpkin Swirl | `#ff7701` | `--color-pumpkin-swirl` | Background for specific call-to-action buttons, adding variety to calls to action |
| Violet Berry | `#4b0f4d` | `--color-violet-berry` | Background for specific call-to-action buttons, offering a dramatic, deep hue |
| Rose Bloom | `#d98199` | `--color-rose-bloom` | Background for specific call-to-action buttons, a soft yet distinct accent |
| Emerald Green | `#24e34c` | `--color-emerald-green` | Decorative accent for links, similar to Aqua Glow but in a green tone |
| Melon Hue | `#eea883` | `--color-melon-hue` | Decorative accent for links, icons, and headings, a softer orange that complements Warm Ginger |
| Absolute Black | `#000000` | `--color-absolute-black` | Primary text color, link color, hero background, and general surface borders |
| Fog Canvas | `#f2ebe6` | `--color-fog-canvas` | Light background for sections, offering a subtle off-white contrast to pure white |
| Pure White | `#ffffff` | `--color-pure-white` | Default page background, heading text on dark backgrounds, icon fill, input and button text |
| Sky Haze | `#eef4fb` | `--color-sky-haze` | Background for headings, providing a very light, cool-toned contrast |
| Cream Canvas | `#fef9ee` | `--color-cream-canvas` | Background for headings and sections, a subtle off-white with a warm undertone |
| Midtone Gray | `#909090` | `--color-midtone-gray` | Muted text or badge background for secondary information like copyrights |
| Dark Wolf | `#2c2c2c` | `--color-dark-wolf` | Secondary text color, slightly softer than absolute black |
| Ash Gray | `#636160` | `--color-ash-gray` | Background for specific neutral ghost buttons |
| Warning Yellow | `#ffff00` | `--color-warning-yellow` | Semantic color for warning badges |

## Tokens — Typography

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400, 700
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Millik — Primary display and heading typeface, characterized by its bespoke serif forms. It sets a distinctive, artistic tone, utilizing tight negative letter-spacing for large sizes to create a dense, impactful visual block. For smaller headings, letter spacing becomes positive for clarity. · `--font-millik`
- **Substitute:** Playfair Display
- **Weights:** 400, 700
- **Sizes:** 20px, 22px, 32px, 38px, 42px, 54px, 70px, 80px, 88px
- **Line height:** 0.95, 0.96, 0.98, 1.00, 1.10, 1.36
- **Letter spacing:** -0.05, -0.042, -0.042, -0.023, -0.021, -0.018, 0.038, 0.02, 0.02
- **Role:** Primary display and heading typeface, characterized by its bespoke serif forms. It sets a distinctive, artistic tone, utilizing tight negative letter-spacing for large sizes to create a dense, impactful visual block. For smaller headings, letter spacing becomes positive for clarity.

### Klarheit Grotesk — Versatile sans-serif for body text, navigation items, badges, and smaller headings. Provides clarity and readability. The semibold weight at 22px is used for prominent subheadings. · `--font-klarheit-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 16px, 22px, 24px
- **Line height:** 1.20, 1.28, 1.36
- **Letter spacing:** normal
- **Role:** Versatile sans-serif for body text, navigation items, badges, and smaller headings. Provides clarity and readability. The semibold weight at 22px is used for prominent subheadings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.2 | — | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 22px | 1.28 | — | `--text-subheading` |
| heading-sm | 24px | 1.36 | — | `--text-heading-sm` |
| heading | 32px | 1 | 1.216px | `--text-heading` |
| heading-lg | 42px | 0.98 | -0.882px | `--text-heading-lg` |
| display | 88px | 0.95 | -4.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 38 | 38px | `--spacing-38` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 86 | 86px | `--spacing-86` |
| 215 | 215px | `--spacing-215` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 30px |
| buttons | 30px |
| bodyElements | 10px |
| circularElements | 50% |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 20px

## Components

### Ghost Button
**Role:** Interactive elements that blend into the background, often for discrete actions or navigation.

Background: rgba(0,0,0,0), Color: rgb(0,0,0), Border: none, Radius: 0px, Padding: 0px.

### Circular Ghost Button
**Role:** Small, discreet interactive elements, often used for icon-only actions.

Background: rgba(0,0,0,0), Color: rgb(0,0,0), Border: none, Radius: 50%, Padding: 0px.

### Pill Accent Button
**Role:** Prominent calls to action with rounded edges, standing out against darker backgrounds.

Background: rgba(0, 0, 0, 0.6), Text: Pure White (#ffffff), Border: 1px solid Pure White (#ffffff), Radius: 30px, Padding: 16px 32px 15px 32px.

### Illustrator Block Button
**Role:** Primary action button for navigating to illustrator portfolios, using specific brand colors.

Background: Illustrator Blue (#2544a0) or other accent colors (Pumpkin Swirl #ff7701, Violet Berry #4b0f4d, Rose Bloom #d98199), Text: Absolute Black (#000000), Border: none, Radius: 0px, Padding: 24px 24px 38px 24px.

### Illustration Card
**Role:** Container for showcasing artist work, designed to let the artwork be the focus.

Background: rgba(0, 0, 0, 0), Radius: 0px, Shadow: none, Padding: 0px.

### Rounded Input Field
**Role:** Text input areas with softened corners.

Background: rgba(0, 0, 0, 0.1), Text: Pure White (#ffffff), Border: none, Radius: 30px, Padding: 16px 32px 15px 32px.

### Warning Dot Badge
**Role:** Small, circular indicator for alerts or status.

Background: Warning Yellow (#ffff00), Text: Absolute Black (#000000), Radius: 50%, Padding: 0px.

### Copyright Notice Badge
**Role:** Muted text for legal information.

Background: rgba(0, 0, 0, 0), Text: Midtone Gray (#909090), Radius: 0px, Padding: 0px.

## Do's and Don'ts

### Do
- Use Millik for all primary headings, applying tight negative letter-spacing for visual impact at larger sizes and subtle positive spacing for smaller headings to enhance clarity.
- Utilize Klarheit Grotesk for all body text, navigation elements, and secondary information, prioritizing its legibility and modern feel.
- Accentuate interactive elements and key information with the brand's vibrant accent colors (Fiery Red, Illustrator Blue, Aqua Glow), ensuring they stand out against neutral backgrounds.
- Maintain a comfortable density with consistent elementGap of 20px and sectionGap of 24px to provide breathing room around content.
- Apply a 30px border-radius to all input fields and primary interactive buttons for a consistent soft, approachable shape.
- Employ Absolute Black (#000000) for primary text on light backgrounds and Pure White (#ffffff) for text on dark backgrounds to ensure high contrast.
- Structure pages with Fog Canvas (#f2ebe6) or Cream Canvas (#fef9ee) as base backgrounds for sections, providing soft transitions.

### Don't
- Avoid using generic blue for links; instead, use brand accent colors like Aqua Glow (#24e3dc) or Emerald Green (#24e34c) when a chromatic link is needed.
- Do not introduce new border radii values beyond 0px, 10px, 30px, and 50% to maintain shape consistency.
- Refrain from adding box shadows to elements unless explicitly defined for a specific component, as the system largely relies on flat surfaces and color contrast.
- Do not use Absolute Black (#000000) as a solid background color for extended sections unless it is the hero with an illustrative overlay.
- Avoid arbitrary changes in letter-spacing for Klarheit Grotesk; it should remain 'normal' unless a specific stylistic reason dictates otherwise.
- Do not use generic button styles; always choose from the defined button variants to ensure consistency in interaction and appearance.
- Do not introduce new typefaces; the system relies exclusively on Millik and Klarheit Grotesk for brand coherence.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pure White Canvas | `#ffffff` | Default page background, providing a clean base for most content. |
| 1 | Cream Canvas | `#fef9ee` | Slightly warmer off-white background for secondary sections, offering subtle visual separation. |
| 2 | Fog Canvas | `#f2ebe6` | Cool-toned off-white background for content blocks, providing an alternative subtle contrast. |
| 3 | Accent Surface | `#ffff00` | Vivid yellow surface used for warning badges or highlight elements. |

## Imagery

The site primarily features vibrant, detailed illustrations as its visual language. These are often full-bleed or large-scale, acting as hero backgrounds or framed within content blocks. The illustrations are diverse in style but consistently rich in color and detail, serving as product showcases and setting an artistic atmosphere. Icons, if present, are minimal and secondary to the main illustrative content. The density is image-heavy, with illustrations taking up significant visual space to emphasize the agency's offerings.

## Layout

The page primarily uses a contained layout with no explicit pageMaxWidth, allowing sections to adapt while text content often aligns within a comfortable reading width. The hero section is a full-bleed, dynamic illustration with centered headline text overlaid. Subsequent sections toggle between clean backgrounds (Fog Canvas, Cream Canvas) to highlight grids of illustration cards. Content arrangement for feature sections includes image-left/text-right or vise-versa implied by the card layouts. A prominent 4-column card grid is used for showcasing illustrators. Vertical rhythm is maintained by consistent section spacing, making the flow comfortable and unhurried. Navigation is a sticky top bar with a hidden menu triggered by a hamburger icon.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #160572
accent: #160572
primary action: #ff7701 (filled action)

Example Component Prompts:
1. Create a Hero Headline: 'Home to the world’s greatest illustrators.' using Millik regular, size 88px, line-height 0.95, letter-spacing -4.4px, color Pure White (#ffffff), centered on a background of Absolute Black (#000000).
2. Create an Illustrator Block Button: 'Browse Illustrators.' using Illustrator Blue (#2544a0) as background, Absolute Black (#000000) text, Klarheit Grotesk regular, size 24px, no border, 0px radius, padding 24px 24px 38px 24px.
3. Create a Pill Accent Button: 'Subscribe Now' using rgba(0, 0, 0, 0.6) background, Pure White (#ffffff) text, 1px solid Pure White (#ffffff) border, 30px radius, padding 16px 32px 15px 32px.

## Similar Brands

- **The Brand Union** — Similar bold, colorful block layouts and emphasis on high-quality visual content with strong typography.
- **Huge Inc.** — Shares a sophisticated yet playful use of vibrant accent colors against clean, spacious neutral backgrounds.
- **Dribbble** — Focus on visual portfolios and a similar approach to presenting diverse creative works within a structured grid.
- **Sagmeister & Walsh** — Uses expressive and custom typography as a core brand element, paired with dynamic and distinctive art direction.
- **Pentagram** — Exhibits a high-end, design-centric approach with careful color choices and strong typographic statements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #160572;
  --color-fiery-red: #ea0706;
  --color-warm-ginger: #e29675;
  --color-terracotta-orange: #d64e2e;
  --color-crimson-edge: #df1a19;
  --color-aqua-glow: #24e3dc;
  --color-sunny-marigold: #f9e44d;
  --color-warm-canvas-yellow: #fffac2;
  --color-illustrator-blue: #2544a0;
  --color-pumpkin-swirl: #ff7701;
  --color-violet-berry: #4b0f4d;
  --color-rose-bloom: #d98199;
  --color-emerald-green: #24e34c;
  --color-melon-hue: #eea883;
  --color-absolute-black: #000000;
  --color-fog-canvas: #f2ebe6;
  --color-pure-white: #ffffff;
  --color-sky-haze: #eef4fb;
  --color-cream-canvas: #fef9ee;
  --color-midtone-gray: #909090;
  --color-dark-wolf: #2c2c2c;
  --color-ash-gray: #636160;
  --color-warning-yellow: #ffff00;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-millik: 'Millik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-klarheit-grotesk: 'Klarheit Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 22px;
  --leading-subheading: 1.28;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.36;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: 1.216px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 0.98;
  --tracking-heading-lg: -0.882px;
  --text-display: 88px;
  --leading-display: 0.95;
  --tracking-display: -4.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-86: 86px;
  --spacing-215: 215px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 30px;

  /* Named Radii */
  --radius-inputs: 30px;
  --radius-buttons: 30px;
  --radius-bodyelements: 10px;
  --radius-circularelements: 50%;

  /* Surfaces */
  --surface-pure-white-canvas: #ffffff;
  --surface-cream-canvas: #fef9ee;
  --surface-fog-canvas: #f2ebe6;
  --surface-accent-surface: #ffff00;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #160572;
  --color-fiery-red: #ea0706;
  --color-warm-ginger: #e29675;
  --color-terracotta-orange: #d64e2e;
  --color-crimson-edge: #df1a19;
  --color-aqua-glow: #24e3dc;
  --color-sunny-marigold: #f9e44d;
  --color-warm-canvas-yellow: #fffac2;
  --color-illustrator-blue: #2544a0;
  --color-pumpkin-swirl: #ff7701;
  --color-violet-berry: #4b0f4d;
  --color-rose-bloom: #d98199;
  --color-emerald-green: #24e34c;
  --color-melon-hue: #eea883;
  --color-absolute-black: #000000;
  --color-fog-canvas: #f2ebe6;
  --color-pure-white: #ffffff;
  --color-sky-haze: #eef4fb;
  --color-cream-canvas: #fef9ee;
  --color-midtone-gray: #909090;
  --color-dark-wolf: #2c2c2c;
  --color-ash-gray: #636160;
  --color-warning-yellow: #ffff00;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-millik: 'Millik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-klarheit-grotesk: 'Klarheit Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 22px;
  --leading-subheading: 1.28;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.36;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: 1.216px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 0.98;
  --tracking-heading-lg: -0.882px;
  --text-display: 88px;
  --leading-display: 0.95;
  --tracking-display: -4.4px;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-86: 86px;
  --spacing-215: 215px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 30px;
}
```
