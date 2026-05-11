# Circle — Style Reference
> Galactic UI with soft glow.

**Theme:** light

Circle utilizes a dark canvas with bright, soft UI elements to project an approachable, yet professional, digital community space. Typography is compact and precise, maintaining clarity against gradients and dark backgrounds. Components are fluid and often feature subtle shadows or blurred backdrops, giving them depth without harshness. The system leverages a rich, cool-toned gradient palette for a vibrant, modern feel, reserving pure white for interactive surfaces to highlight action.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Eclipse | `#0a0a0a` | `--color-midnight-eclipse` | Primary text, deep surface backgrounds, navigation bar text and icons |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, active input fills, essential text elements on dark backgrounds |
| Slate Border | `#e4e7eb` | `--color-slate-border` | Subtle borders, dividers, ghost button outlines, inactive input borders |
| Dark Knight | `#191b1f` | `--color-dark-knight` | Secondary text, muted headings, deep accent text on light backgrounds |
| Silver Whisper | `#737373` | `--color-silver-whisper` | Muted helper text, secondary navigation links, placeholder text |
| Deep Indigo | `linear-gradient(142deg, rgb(64, 143, 237) 18.68%, rgb(62, 27, 201) 78.25%)` | `--color-deep-indigo` | Background gradient accent, blending from bright blue to deep violet |
| Sky Burst | `#408fed` | `--color-sky-burst` | Background gradient starting point, contributing to the ambient glow |
| Periwinkle Mist | `#e0eafc` | `--color-periwinkle-mist` | Soft button backgrounds, subtle card accents |
| Lavender Haze | `#f2dbf5` | `--color-lavender-haze` | Soft button backgrounds, subtle card accents, hover states for inputs |
| Peach Cream | `#fff0d8` | `--color-peach-cream` | Soft button backgrounds, subtle card accents |
| Rose Blush | `#ffe0e2` | `--color-rose-blush` | Soft button backgrounds, subtle card accents |
| Ocean Mint | `#e4f6f4` | `--color-ocean-mint` | Soft button backgrounds, subtle card accents |
| Focus Blue | `#539cf2` | `--color-focus-blue` | Blue supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Crimson Alert | `#ef4444` | `--color-crimson-alert` | Red text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Dark Crimson Alert | `#b91c1c` | `--color-dark-crimson-alert` | Red text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Inter — The sole typeface, used across all elements from body text to large display headings. Its versatile weights and precise letter-spacing ensure compact and legible content, crucial for an information-dense UI. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 48px, 56px, 64px
- **Line height:** 1.10, 1.20, 1.21, 1.25, 1.28, 1.29, 1.30, 1.33, 1.40, 1.43, 1.45, 1.50, 1.56
- **Letter spacing:** -0.0500em at 64px, -0.0470em at 56px, -0.0370em at 48px, -0.0160em at 18px-24px, 0.0500em at 10px
- **Role:** The sole typeface, used across all elements from body text to large display headings. Its versatile weights and precise letter-spacing ensure compact and legible content, crucial for an information-dense UI.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.5px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.14px | `--text-body-sm` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 20px | 1.3 | -0.42px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.58px | `--text-heading-sm` |
| heading | 32px | 1.28 | -0.74px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.92px | `--text-heading-lg` |
| display | 48px | 1.21 | -1.24px | `--text-display` |
| display-lg | 56px | 1.2 | -1.45px | `--text-display-lg` |
| headline | 64px | 1.1 | -1.6px | `--text-headline` |

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
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| inputs | 9999px |
| buttons | 9999px |
| decorativeElements | 32px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(169, 169, 169, 0.08) 0px 4px 8px 0px` | `--shadow-sm` |
| subtle | `rgb(83, 156, 242) 0px 0px 0px 2px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1376px
- **Section gap:** 93px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Primary navigation and secondary actions in headers and footers.

Transparent background, text in Midnight Eclipse (#0a0a0a) against Canvas White (#ffffff) or Canvas White against a dark background. Border is solid 1px Slate Border (#e4e7eb). Padding is 14px vertical, 28px horizontal. Fully rounded with 9999px border-radius.

### Accent Filled Button
**Role:** Calls to action or categorical filters.

Background in one of the pastel Accent colors (e.g., Periwinkle Mist #e0eafc), text in Midnight Eclipse (#0a0a0a). Padding is 8px vertical, 16px horizontal. Fully rounded with 9999px border-radius. No explicit border.

### Product Feature Card
**Role:** Displaying product features or content blocks.

Background in Canvas White (#ffffff), with an 8% opacity shadow from #a9a9a9 (rgba(169, 169, 169, 0.08)) offset 0px, 4px blur 8px. Border-radius is 20px. Internal padding is 32px on all sides.

### Translucent Highlight Card
**Role:** Elevated, semi-transparent content areas within contrasting backgrounds.

Semi-transparent Canvas White background (rgba(255, 255, 255, 0.5)). Border-radius is 24px. Internal padding is 20px. No shadow is applied.

### Input Field
**Role:** Standard text input for forms.

Background in Canvas White (#ffffff), text in Midnight Eclipse (#0a0a0a). Border is 1px solid Slate Border (#e2e9e0). Fully rounded with 9999px border-radius. Left padding 24px, vertical 4px. On focus, a 2px blue ring (Focus Blue #539cf2) outlines the input.

### Category Tab Button
**Role:** Segmenting content or filtering categories within a section.

Ghost style with transparent background. Text is Midnight Eclipse (#0a0a0a) or Canvas White (#ffffff) on dark areas. No specific padding or border radius when inactive. Active state often utilizes an Accent Filled Button style.

### Dark Themed Feature Card
**Role:** Presenting features or testimonials on dark background sections.

Translucent background in rgba(255, 255, 255, 0.18). Border-radius is 20px. Internal padding is 8px. No shadow is applied.

## Do's and Don'ts

### Do
- Use Inter for all typography, adjusting weight and letter-spacing according to semantic role and size.
- Apply 9999px border-radius to all interactive elements like buttons and input fields for a consistent soft-edged feel.
- Reserve Canvas White (#ffffff) for primary content surfaces and interactive elements to maintain high contrast and clarity.
- Employ the Deep Indigo to Sky Burst linear gradient as a primary background for hero sections and expressive areas, creating a sense of depth.
- Use Slate Border (#e4e7eb) for subtle dividers, non-essential borders, and outlines to avoid visual clutter.
- Maintain a clear visual hierarchy with Midnight Eclipse (#0a0a0a) for primary text and Silver Whisper (#737373) for secondary/helper text.
- Use an 8px element gap for comfortable spacing between most inline and block elements to ensure readability and comfortable density.

### Don't
- Avoid using harsh, saturated colors as backgrounds to maintain the site's soft, futuristic aesthetic.
- Do not deviate from the Inter typeface; alternative fonts will disrupt the precise typographic harmony.
- Do not use square or sharp-cornered elements; all significant UI components should leverage the established border-radius values.
- Refrain from heavy, opaque shadows; utilize the transparent, diffused rgba(169, 169, 169, 0.08) 0px 4px 8px 0px for subtle elevation.
- Do not introduce new primary action colors; the design system favors accent-tinted light buttons for calls to action.
- Avoid excessive spacing or overly wide line lengths; keep text compact and content focused on the 1376px max-width constraint.
- Do not use plain solid backgrounds for large content blocks where a gradient or blurred backdrop could provide more visual interest and depth.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Dominant page background, primary stage for content. |
| 1 | Accent Pale Rose | `#fef2f2` | Lightest accent background for subtle segmentation or content blocks. |
| 2 | Accent Peach Tint | `#fff0d8` | Mid-level accent background, providing a slightly warmer tone. |
| 3 | Accent Aqua Mist | `#e4f6f4` | Another mid-level accent background, offering a cool, refreshing tint. |
| 4 | Accent Periwinkle | `#e0eafc` | A deeper accent background, used for more pronounced content separation or card backgrounds. |

## Elevation

- **Card:** `rgba(169, 169, 169, 0.08) 0px 4px 8px 0px`
- **Input Focus Ring:** `rgb(83, 156, 242) 0px 0px 0px 2px`

## Imagery

The site favors illustrative, abstract graphics with soft glows and gradients, particularly in hero sections and background patterns. Product screenshots are clean, showcasing UI within contained, slightly rounded frames, often with a subtle shadow or translucent background. Photography, when used, tends to be professional portraits of individuals (e.g., testimonials) presented similarly to cards. Icons are typically outlined or filled, maintaining a consistent stroke weight, and monochrome to integrate seamlessly with the minimal UI.

## Layout

The page primarily uses a max-width contained layout of 1376px, centered on the screen. The hero section is full-bleed, leveraging a dark, gradient background with a centered, prominent headline and a Call to Action block. Sections below often alternate between light (#ffffff) and darker gradient or tinted backgrounds, creating a clear vertical rhythm with consistent ~93px section gaps. Content is arranged using flexible column grids, commonly alternating text-left/image-right patterns, centered stacked content blocks, and 3-column card grids for features. The navigation is a sticky top bar, minimal and semi-transparent, evolving to a solid background on scroll.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0a0a
background: #ffffff
border: #e4e7eb
accent: #e0eafc
primary action: #f2dbf5 (filled action)

Example Component Prompts:
Create a hero section with a centered headline: Background with Deep Indigo to Sky Burst gradient. Headline 'The complete community platform' at 56px Inter weight 700, Canvas White text, letter-spacing -1.45px. Subtext 'Build a home for your community...' at 18px Inter weight 400, Canvas White text, letter-spacing -0.16px. Follow with an email input field and an Accent Filled Button 'Start for free' with Periwinkle Mist background (#e0eafc), Midnight Eclipse text (#0a0a0a), 9999px radius, 8px vertical, 16px horizontal padding.

Create a Product Feature Card: Background Canvas White (#ffffff), box-shadow rgba(169, 169, 169, 0.08) 0px 4px 8px 0px, 20px border-radius. Internal padding 32px. Place a subheading in Midnight Eclipse (#0a0a0a) 24px Inter weight 600, letter-spacing -0.58px, and body text in Silver Whisper (#737373) 16px Inter weight 400, letter-spacing -0.16px.

Create a Ghost Navigation Button: Transparent background. Text 'Product' in Midnight Eclipse (#0a0a0a) when on white background or Canvas White (#ffffff) on dark. 1px solid Slate Border (#e4e7eb) when outlined. 14px vertical, 28px horizontal padding. Fully rounded 9999px border-radius.

## Similar Brands

- **Discord** — Shares a modern, dark-mode aesthetic with vibrant accent colors on UI elements and soft, rounded component styles.
- **Notion** — Employs a clean, minimalist canvas for content with clear typographic hierarchy and subtle interactive states.
- **Gumroad** — Combines a dark header/background with light, card-based content sections, and uses soft, rounded buttons.
- **Linear** — Features a disciplined, compact UI with precise typography, subtle borders, and a focus on functionality within a spacious layout.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-eclipse: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-slate-border: #e4e7eb;
  --color-dark-knight: #191b1f;
  --color-silver-whisper: #737373;
  --color-deep-indigo: #3e1bc9;
  --gradient-deep-indigo: linear-gradient(142deg, rgb(64, 143, 237) 18.68%, rgb(62, 27, 201) 78.25%);
  --color-sky-burst: #408fed;
  --color-periwinkle-mist: #e0eafc;
  --color-lavender-haze: #f2dbf5;
  --color-peach-cream: #fff0d8;
  --color-rose-blush: #ffe0e2;
  --color-ocean-mint: #e4f6f4;
  --color-focus-blue: #539cf2;
  --color-crimson-alert: #ef4444;
  --color-dark-crimson-alert: #b91c1c;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.42px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.58px;
  --text-heading: 32px;
  --leading-heading: 1.28;
  --tracking-heading: -0.74px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.92px;
  --text-display: 48px;
  --leading-display: 1.21;
  --tracking-display: -1.24px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.2;
  --tracking-display-lg: -1.45px;
  --text-headline: 64px;
  --leading-headline: 1.1;
  --tracking-headline: -1.6px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1376px;
  --section-gap: 93px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-inputs: 9999px;
  --radius-buttons: 9999px;
  --radius-decorativeelements: 32px;

  /* Shadows */
  --shadow-sm: rgba(169, 169, 169, 0.08) 0px 4px 8px 0px;
  --shadow-subtle: rgb(83, 156, 242) 0px 0px 0px 2px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-accent-pale-rose: #fef2f2;
  --surface-accent-peach-tint: #fff0d8;
  --surface-accent-aqua-mist: #e4f6f4;
  --surface-accent-periwinkle: #e0eafc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-eclipse: #0a0a0a;
  --color-canvas-white: #ffffff;
  --color-slate-border: #e4e7eb;
  --color-dark-knight: #191b1f;
  --color-silver-whisper: #737373;
  --color-deep-indigo: #3e1bc9;
  --color-sky-burst: #408fed;
  --color-periwinkle-mist: #e0eafc;
  --color-lavender-haze: #f2dbf5;
  --color-peach-cream: #fff0d8;
  --color-rose-blush: #ffe0e2;
  --color-ocean-mint: #e4f6f4;
  --color-focus-blue: #539cf2;
  --color-crimson-alert: #ef4444;
  --color-dark-crimson-alert: #b91c1c;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.42px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.58px;
  --text-heading: 32px;
  --leading-heading: 1.28;
  --tracking-heading: -0.74px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.92px;
  --text-display: 48px;
  --leading-display: 1.21;
  --tracking-display: -1.24px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.2;
  --tracking-display-lg: -1.45px;
  --text-headline: 64px;
  --leading-headline: 1.1;
  --tracking-headline: -1.6px;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-sm: rgba(169, 169, 169, 0.08) 0px 4px 8px 0px;
  --shadow-subtle: rgb(83, 156, 242) 0px 0px 0px 2px;
}
```
