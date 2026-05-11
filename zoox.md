# Zoox — Style Reference
> Muted, precise mobility.

**Theme:** light

Zoox employs a sophisticated, muted aesthetic, blending an off-black and white core with subtle, cool-toned neutrals and a singular vibrant teal accent. Typography is dominant, commanding attention with generous sizing and precise control over letter-spacing. Surfaces vary between stark white, dark gray, and a soft, desaturated teal, creating distinct visual sections without harsh transitions. Components are often outlined or ghosted, relying on subtle borders and rounded corners, avoiding heavy fills or deep shadows to maintain a lightweight, intentional feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0d1212` | `--color-midnight-ink` | Primary text, deep section backgrounds, card backgrounds, dark input borders |
| Cloud Canvas | `#ffffff` | `--color-cloud-canvas` | Page backgrounds, card surfaces, element fills, light iconography |
| Ash Gray | `#565959` | `--color-ash-gray` | Secondary text, footer text, placeholder text |
| Slate Green | `#34484a` | `--color-slate-green` | Decorative borders, active navigation states, button outlines, subtle background tints. A distinctive near-gray that grounds the palette |
| Pale Mint | `#d3e4df` | `--color-pale-mint` | Soft section backgrounds, light card surfaces, subtle dividers |
| Fog | `#696969` | `--color-fog` | Tertiary text, subtle borders |
| Stone Gray | `#7b8889` | `--color-stone-gray` | Heading subtext, less prominent body copy |
| Light Mist | `#9aa3a5` | `--color-light-mist` | Iconography, muted body text details |
| Pale Sage | `#edf4f2` | `--color-pale-sage` | Badge backgrounds, subtle surface variations |
| Teal Accent | `#64d5b3` | `--color-teal-accent` | Teal action color for filled buttons, selected navigation states, and focused conversion moments. |
| Muted Teal | `#5b8279` | `--color-muted-teal` | Subtle decorative elements, less prominent accent text |
| Conic Wave | `conic-gradient(rgb(52, 255, 197) 0deg, rgb(199, 198, 255) 0deg, rgb(167, 207, 255) 0deg, rgb(52, 255, 197) 0deg, rgba(199, 198, 255, 0) 0deg, rgba(199, 198, 255, 0) 360deg)` | `--color-conic-wave` | Decorative background gradients, abstract visual elements, creating an ethereal halo effect |

## Tokens — Typography

### Gt Standard S — UI elements, body text, secondary headings, links, and buttons, providing consistent legibility and a compact, precise tone. Letter spacing is subtly tightened for all sizes to increase visual density. · `--font-gt-standard-s`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 20px, 23px, 30px, 40px, 50px
- **Line height:** 0.75, 1.00, 1.15, 1.20, 1.25, 1.28, 1.30, 1.40, 1.50, 1.88, 2.64
- **Letter spacing:** variable, ranging from -0.0020em to 0.0500em
- **OpenType features:** `"kern" 0`
- **Role:** UI elements, body text, secondary headings, links, and buttons, providing consistent legibility and a compact, precise tone. Letter spacing is subtly tightened for all sizes to increase visual density.

### Gt Standard L — Primary headings and large display text, creating impactful visual statements with their substantial size. These large sizes use normal letter spacing to maintain clarity. · `--font-gt-standard-l`
- **Substitute:** Outfit
- **Weights:** 400
- **Sizes:** 28px, 36px, 56px, 120px
- **Line height:** 1.10, 1.15, 1.20, 1.30
- **Letter spacing:** normal
- **OpenType features:** `"kern" 0`
- **Role:** Primary headings and large display text, creating impactful visual statements with their substantial size. These large sizes use normal letter spacing to maintain clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.28 | — | `--text-caption` |
| body-sm | 13px | 1.28 | — | `--text-body-sm` |
| body | 14px | 1.28 | — | `--text-body` |
| body-lg | 15px | 1.28 | — | `--text-body-lg` |
| heading-sm | 20px | 1.28 | — | `--text-heading-sm` |
| heading | 23px | 1.28 | — | `--text-heading` |
| heading-lg | 30px | 1.28 | — | `--text-heading-lg` |
| display-sm | 40px | 1.28 | — | `--text-display-sm` |
| display | 50px | 1.28 | — | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 36px |
| links | 12px |
| badges | 20px |
| inputs | 18px |
| buttons | 16px |
| navigation | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.2) 0px 0px 4px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 5px

## Components

### Ghost Nav Button
**Role:** Navigation and secondary actions

Text-only button with 'Slate Green' (#34484a) border and text color for outlined or active states. Features a small radius of 12px or 16px. Padding is minimal.

### Primary Action Button
**Role:** Call to action

Filled button with 'Teal Accent' (#64d5b3) background and 'Midnight Ink' (#0d1212) text. Features a 16px border radius, with 15px padding on all sides. Used for primary user actions.

### Outline Ghost Button
**Role:** Subtle secondary actions or interactive elements.

Transparent background with text in 'Ash Gray' (#565959) or 'Midnight Ink' (#0d1212). Borders are hairline or absent, with a very large border radius (33.33%).

### Neutral Card
**Role:** Content container

Transparent background, no shadow, with 20px left/right padding. Used for modular content blocks.

### Elevated Card (Pale Mint)
**Role:** Prominent content container

Background in 'Pale Mint' (#d3e4df), with a 36px border radius and no shadow. Provides 104px top padding and 40px bottom padding, creating a soft, elevated surface.

### Dark Card
**Role:** Thematic content container

Background in 'Midnight Ink' (#0d1212) with a 36px border radius. No padding, used for full-bleed content within its boundaries.

### Header Card (Slate Green)
**Role:** Section header background

Background in 'Slate Green' (#34484a) with no border radius. Provides 80px top and bottom padding.

### Text Input
**Role:** User data entry

White background with 'Midnight Ink' (#0d1212) text. Border color is 'Slate Green' (#34484a) or 'Stone Gray' (#7b8889), with a subtle 1px border. Features an 18px border radius and 20px horizontal padding.

### Neutral Badge
**Role:** Informational labels

Transparent background with 'Midnight Ink' (#0d1212) text. No border radius or padding, used inline for categorization.

### Soft Badge
**Role:** Categorization and status indicators

Background in `Pale Sage` (#edf4f2) with a slight opacity (40%), and 'Midnight Ink' (#0d1212) text. Features a 20px border radius and 7px vertical, 12px horizontal padding.

## Do's and Don'ts

### Do
- Use 'Gt Standard L' weight 400 for all primary headings (28px to 120px) with normal letter spacing to maximize impact.
- Apply 'Teal Accent' (#64d5b3) exclusively for primary action buttons or significant interactive highlights.
- Employ generously rounded corners (16px and 36px) on cards, buttons, and images to soften the overall aesthetic.
- Maintain high contrast between text ('Midnight Ink') and backgrounds ('Cloud Canvas', 'Pale Mint', or 'Slate Green') for optimal legibility.
- Utilize 'Pale Mint' (#d3e4df) for background sections to create soft visual breaks or subtle elevated surfaces.
- Implement 'Slate Green' (#34484a) for subtle borders, ghost button outlines, and interactive navigation elements.
- Ensure letter-spacing is consistently negative for 'Gt Standard S' typography in smaller sizes to maintain its compact appearance.

### Don't
- Do not introduce new vibrant colors outside of 'Teal Accent' (#64d5b3); maintain the muted and achromatic base palette.
- Avoid heavy use of drop shadows; reserve the subtle rgba(0, 0, 0, 0.2) 0px 0px 4px 0px shadow for very specific, subtle elevation.
- Do not use generic system fonts; stick to the 'Gt Standard S' and 'Gt Standard L' families for brand consistency.
- Avoid sharp corners on interactive elements or prominent containers; maintain the established rounded aesthetic.
- Do not use highly saturated backgrounds or overwhelming gradients in full sections; keep backgrounds understated with an occasional conic gradient as a decorative element.
- Refrain from using varied letter spacing on large display type ('Gt Standard L'); keep it 'normal' for maximum clarity.
- Do not create dense, busy layouts; prioritize comfortable spacing (40px section gap, 5px element gap) and ample whitespace.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#d3e4df` | Primary page background, creating a soft, light base. |
| 1 | Base Card | `#ffffff` | Default card and input backgrounds, providing a clean, bright surface. |
| 2 | Elevated Pale Card | `#edf4f2` | Softly elevated card backgrounds, such as the banner for cookie policy, subtly distinct from the base canvas. |
| 3 | Slate Green Section | `#34484a` | Darker, contrasting section backgrounds, providing a visual anchor. |
| 4 | Midnight Ink Card | `#0d1212` | Deepest surface level, used for dark, immersive card backgrounds. |

## Elevation

- **Cookie Policy Card:** `rgba(0, 0, 0, 0.2) 0px 0px 4px 0px`

## Imagery

The imagery features realistic photography of the Zoox robotaxi and interiors, or people interacting within the vehicle, shown in contained, often horizontally cropped or square formats. Treatment involves both full-bleed hero visuals and smaller, isolated images with substantial border-radii (16px to 36px) that soften their impact. Photography is clear, well-lit, and product-focused, showcasing the vehicle and user experience directly. Iconography is minimalist and monochrome, using black or dark gray outlines with a light stroke weight, serving primarily functional roles (e.g., play/pause button). Image density is balanced, used to break up text sections and illustrate features without overwhelming the page.

## Layout

The page primarily uses a max-width contained layout, though specific sections like the hero or thematic backgrounds can be full-bleed. The hero often features a centered headline over a background image or a single color block (e.g., Pale Mint or Slate Green). Vertical rhythm is established through consistent section gaps, creating a comfortable density. Content is arranged using alternating text-left/image-right or image-left/text-right patterns, and in some areas, stacked centered elements. There are implicit grids for features, often two or three columns beneath larger headlines. Navigation is a persistent top bar with ghost buttons, converting to a hamburger menu on smaller viewports. Sticky headers are present, and the overall feel is spacious and organized.

## Agent Prompt Guide

Quick Color Reference:
text: #0d1212
background: #d3e4df
border: #34484a
accent: #5b8279
primary action: #64d5b3 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #64d5b3 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Design a navigation link: Text 'How To Ride' in 'Slate Green' (#34484a), 'Gt Standard S' weight 500, 15px, 0.0100em letter spacing. Ensure minimal 5px padding and a 12px border radius on hover.

## Similar Brands

- **Waymo** — Shares a similar muted, professional aesthetic with an emphasis on product clarity and subtle brand accents.
- **Cruise** — Employs a clean, spacious layout with a restrained color palette and focus on typography for information hierarchy.
- **Volocopter** — Features a light, airy design with minimal color usage and photography-driven sections to showcase innovative transportations.
- **Superhuman** — Exhibits precise typographic control, tight letter-spacing, and a limited, high-contrast color palette with a single accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0d1212;
  --color-cloud-canvas: #ffffff;
  --color-ash-gray: #565959;
  --color-slate-green: #34484a;
  --color-pale-mint: #d3e4df;
  --color-fog: #696969;
  --color-stone-gray: #7b8889;
  --color-light-mist: #9aa3a5;
  --color-pale-sage: #edf4f2;
  --color-teal-accent: #64d5b3;
  --color-muted-teal: #5b8279;
  --color-conic-wave: #34ffc5;
  --gradient-conic-wave: conic-gradient(rgb(52, 255, 197) 0deg, rgb(199, 198, 255) 0deg, rgb(167, 207, 255) 0deg, rgb(52, 255, 197) 0deg, rgba(199, 198, 255, 0) 0deg, rgba(199, 198, 255, 0) 360deg);

  /* Typography — Font Families */
  --font-gt-standard-s: 'Gt Standard S', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-standard-l: 'Gt Standard L', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.28;
  --text-body-sm: 13px;
  --leading-body-sm: 1.28;
  --text-body: 14px;
  --leading-body: 1.28;
  --text-body-lg: 15px;
  --leading-body-lg: 1.28;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.28;
  --text-heading: 23px;
  --leading-heading: 1.28;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.28;
  --text-display-sm: 40px;
  --leading-display-sm: 1.28;
  --text-display: 50px;
  --leading-display: 1.28;

  /* Typography — Weights */
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;

  /* Named Radii */
  --radius-cards: 36px;
  --radius-links: 12px;
  --radius-badges: 20px;
  --radius-inputs: 18px;
  --radius-buttons: 16px;
  --radius-navigation: 16px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 0px 4px 0px;

  /* Surfaces */
  --surface-page-canvas: #d3e4df;
  --surface-base-card: #ffffff;
  --surface-elevated-pale-card: #edf4f2;
  --surface-slate-green-section: #34484a;
  --surface-midnight-ink-card: #0d1212;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0d1212;
  --color-cloud-canvas: #ffffff;
  --color-ash-gray: #565959;
  --color-slate-green: #34484a;
  --color-pale-mint: #d3e4df;
  --color-fog: #696969;
  --color-stone-gray: #7b8889;
  --color-light-mist: #9aa3a5;
  --color-pale-sage: #edf4f2;
  --color-teal-accent: #64d5b3;
  --color-muted-teal: #5b8279;
  --color-conic-wave: #34ffc5;

  /* Typography */
  --font-gt-standard-s: 'Gt Standard S', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-standard-l: 'Gt Standard L', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.28;
  --text-body-sm: 13px;
  --leading-body-sm: 1.28;
  --text-body: 14px;
  --leading-body: 1.28;
  --text-body-lg: 15px;
  --leading-body-lg: 1.28;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.28;
  --text-heading: 23px;
  --leading-heading: 1.28;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.28;
  --text-display-sm: 40px;
  --leading-display-sm: 1.28;
  --text-display: 50px;
  --leading-display: 1.28;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 0px 4px 0px;
}
```
