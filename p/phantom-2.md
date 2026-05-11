# Phantom — Style Reference
> Soft Violet Dreamscape: A calming digital space where gentle curves meet understated color, feeling secure and approachable.

**Theme:** light

Phantom presents a light, playful, yet sophisticated aesthetic, establishing trust through a unique palette of muted violets and near-achromatic grays. A signature rounded-rectangle form dominates, appearing in primary buttons, hero containers, and navigation elements. The custom 'Phantom' typeface, with its 350-weight headlines, feels intimate and approachable, avoiding the starkness of many crypto platforms while maintaining clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Phantom Violet | `#3c315b` | `--color-phantom-violet` | Primary text, interactive elements (links, navigation items), primary button text. This muted violet forms the brand's core, appearing where attention is needed but aggression is avoided. |
| Lavender Mist | `#e2dffe` | `--color-lavender-mist` | Primary button background, providing a soft, almost glowing contrast to the Phantom Violet text. Also used as a subtle hover state or background highlight, contributing to the approachable feel. |
| Grape Glow | `#ab9ff2` | `--color-grape-glow` | Accent for secondary button backgrounds and occasionally as an SVG fill. A more saturated but still soft violet, used to draw moderate attention. |
| Success Green | `#2ec08b` | `--color-success-green` | Used for success indicators and badges, a vibrant but not harsh green that complements the violet palette without clashing. |
| Paper White | `#fdfcfe` | `--color-paper-white` | Page backgrounds, card surfaces, and text on dark backgrounds. A slightly off-white that feels warmer than pure white. |
| Charcoal Black | `#1c1c1c` | `--color-charcoal-black` | Text on light backgrounds, certain secondary button backgrounds. A deep, desaturated black that provides strong contrast without being stark. |
| Silver Ash | `#e9e8ea` | `--color-silver-ash` | Subtle background for UI elements like certain buttons or input fields, creating a barely-there separation. |
| Fog Gray | `#f4f2f4` | `--color-fog-gray` | Minor background accents or very light borders, a whisper of a neutral shade. |
| Stone Gray | `#86848d` | `--color-stone-gray` | Subtler text, icons, and navigation elements, offering a secondary text color that recedes slightly. |

## Tokens — Typography

### Phantom — Primary typeface for all text elements. The 350 weight is used prominently for large headlines, creating an intimate, almost whisper-like tone for potentially complex financial topics. The negative letter-spacing contributes to a tightly composed, unified visual block of text. · `--font-phantom`
- **Weights:** 350, 400
- **Sizes:** 13px, 15px, 16px, 20px, 24px, 30px, 64px, 80px, 96px
- **Line height:** 1.00, 1.10, 1.20, 1.21, 1.25, 1.35, 1.40
- **Letter spacing:** -0.025
- **Role:** Primary typeface for all text elements. The 350 weight is used prominently for large headlines, creating an intimate, almost whisper-like tone for potentially complex financial topics. The negative letter-spacing contributes to a tightly composed, unified visual block of text.

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| cards | 24px |
| input | 0px |
| buttons | 32px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgb(226, 223, 254) 0px 0px 4px 0px` | `--shadow-sm` |

### Layout

- **Card padding:** 24px

## Components

### Primary Action Button
**Role:** Main call to action

Rounded rectangle button using Lavender Mist (#e2dffe) background and Phantom Violet (#3c315b) text. `Phantom` font, often 15px or 16px, weight 400. Padding: 12px vertical, 20px horizontal. Border radius 32px. Subtle box shadow: #e2dffe 0px 0px 4px 0px.

### Inverted Dark Button
**Role:** Secondary action or featured button on dark backgrounds

Dark button with Charcoal Black (#1c1c1c) background and Paper White (#fdfcfe) text. `Phantom` font. Padding: 48px vertical, 48px horizontal for larger variants. Border radius 24px.

### Ghost Button - Light
**Role:** Tertiary action or navigation

Transparent background with Paper White (#fdfcfe) text and border. `Phantom` font. Padding: 16px all sides. Border radius 32px.

### Dark Card Button
**Role:** Button variant for dark cards/sections.

Uses Charcoal Black (#1c1c1c) background with Paper White (#fdfcfe) text. `Phantom` font. Rounded corners: 24px. Large vertical padding: 48px top, 0px bottom.

### Light Card Button
**Role:** Button variant for light cards/sections.

Uses Silver Ash (#e9e8ea) background with Charcoal Black (#1c1c1c) text. `Phantom` font. Rounded corners: 24px. Large vertical padding: 48px top, 0px bottom.

### Navigation Link
**Role:** Primary navigation elements

Phantom Violet (#3c315b) text. `Phantom` font, typically 16px, weight 400. No explicit padding or background, text-based link.

### Success Badge
**Role:** Status indicator or small tag

Circular badge with Success Green (#2ec08b) background and Phantom Violet (#3c315b) text. Border radius 50%. Zero padding, implies content dictates size.

### Hero Section Container
**Role:** Main content block for hero sections

Large rounded-rectangle container with variable background color (e.g., Lavender Mist #e2dffe, or broader page purples). Border radius 24px. Significant internal padding (48px horizontal, 32px vertical) for content isolation.

## Do's and Don'ts

### Do
- Prioritize Phantom Violet (#3c315b) for primary text and interactive elements to maintain brand identity.
- Use Lavender Mist (#e2dffe) for primary button backgrounds and subtle interactive highlights.
- Apply a 24px border radius for main content blocks and card-like elements, and 32px for primary buttons.
- Use the Phantom font with a 350 weight and -0.025em letter spacing for display headlines (64px, 80px, 96px).
- Employ a base unit of 4px for all spacing measurements, translating to values like 4px, 8px, 12px, 16px, etc.
- Use Paper White (#fdfcfe) as the dominant page background color to support the soft, light theme.
- Ensure contrast ratio of 13:1 or higher for text-to-background combinations, using Charcoal Black (#1c1c1c) on light backgrounds like Paper White (#fdfcfe) and Lavender Mist (#e2dffe).

### Don't
- Avoid harsh, saturated colors that deviate from the muted violet and near-achromatic palette, except for specific semantic indicators like Success Green.
- Do not use sharp corners or square elements; maintain the rounded-rectangle and circular forms consistently.
- Refrain from using bold or heavy font weights for headlines; the 350 weight of Phantom font is a brand signature.
- Do not introduce unnecessary box shadows; elevation is minimal, confined to subtle effects like #e2dffe 0px 0px 4px 0px for interactive elements.
- Avoid high-contrast text on bright backgrounds, instead opting for the slightly desaturated Charcoal Black (#1c1c1c) on Paper White (#fdfcfe).
- Steer clear of aggressive or overly dynamic animations; the design encourages a calm and stable user experience.
- Do not vary letter spacing unless explicitly defined; the -0.025em for Phantom font is a stylistic choice, not a general rule.

## Layout

The layout is primarily a max-width contained design with content centered, but sections vary in background color. The hero section often features a full-width background, typically a solid color like Lavender Mist, with content centered. Subsequent sections alternate between Paper White backgrounds and more saturated violet backgrounds, creating a clear visual rhythm. Content is generally arranged in centered stacks, with strong emphasis on large, centrally aligned headlines and descriptive body text. Navigation is a sticky top bar, centered within the max-width container, featuring rounded buttons for primary actions.

## Agent Prompt Guide

### Quick Color Reference
- Text (primary): #3c315b
- Background (page): #fdfcfe
- CTA Button Background: #e2dffe
- CTA Button Text: #3c315b
- Accent (secondary button): #ab9ff2

### Example Component Prompts
1. Create a Primary Action Button: `backgroundColor: #e2dffe`, `color: #3c315b`, `borderRadius: 32px`, `padding: 12px 20px`, `fontFamily: Phantom`, `fontSize: 16px`, `fontWeight: 400`, `boxShadow: 0px 0px 4px 0px #e2dffe`.
2. Generate a Hero Section Headline: Centered `Phantom` font, `fontSize: 80px`, `fontWeight: 350`, `letterSpacing: -0.025em`, `color: #3c315b`, on a `backgroundColor: #e2dffe` hero container with `borderRadius: 24px`.
3. Design a Navigation Link: `color: #3c315b`, `fontFamily: Phantom`, `fontSize: 16px`, `fontWeight: 400`, with a subtle hover state changing text `color` to a slightly darker `#1c1c1c`.
4. Produce a Dark Card Button: `backgroundColor: #1c1c1c`, `color: #fdfcfe`, `borderRadius: 24px`, `padding: 48px 48px 0px 48px`, `fontFamily: Phantom`, `fontSize: 20px`, `fontWeight: 400`.

## Similar Brands

- **WalletConnect** — Shares a similar light, modern, and friendly aesthetic with rounded components and a focus on clean typography for blockchain services.
- **Rainbow Wallet** — Utilizes a soft, inviting color palette and playful illustrations, similar to Phantom's approachable yet crypto-focused design.
- **Magic Eden** — Presents a refined, clean interface in the crypto space, employing subtle color variations for hierarchy and smooth transitions.
- **Zapper.fi** — Features a light, information-dense UI with clear color coding and a focus on readability, akin to Phantom's functional clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-phantom-violet: #3c315b;
  --color-lavender-mist: #e2dffe;
  --color-grape-glow: #ab9ff2;
  --color-success-green: #2ec08b;
  --color-paper-white: #fdfcfe;
  --color-charcoal-black: #1c1c1c;
  --color-silver-ash: #e9e8ea;
  --color-fog-gray: #f4f2f4;
  --color-stone-gray: #86848d;

  /* Typography — Font Families */
  --font-phantom: 'Phantom', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-base: 15px;
  --leading-base: 1.21;
  --text-base-2: 16px;
  --leading-base-2: 1.2;
  --text-xl: 20px;
  --leading-xl: 1.25;
  --text-2xl: 24px;
  --leading-2xl: 1.35;
  --text-3xl: 30px;
  --leading-3xl: 1.2;
  --text-5xl: 64px;
  --leading-5xl: 1;
  --text-5xl-2: 80px;
  --leading-5xl-2: 1.1;
  --text-5xl-3: 96px;
  --leading-5xl-3: 1.1;

  /* Typography — Weights */
  --font-weight-w350: 350;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --card-padding: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 96px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-cards: 24px;
  --radius-input: 0px;
  --radius-buttons: 32px;

  /* Shadows */
  --shadow-sm: rgb(226, 223, 254) 0px 0px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-phantom-violet: #3c315b;
  --color-lavender-mist: #e2dffe;
  --color-grape-glow: #ab9ff2;
  --color-success-green: #2ec08b;
  --color-paper-white: #fdfcfe;
  --color-charcoal-black: #1c1c1c;
  --color-silver-ash: #e9e8ea;
  --color-fog-gray: #f4f2f4;
  --color-stone-gray: #86848d;

  /* Typography */
  --font-phantom: 'Phantom', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-base: 15px;
  --leading-base: 1.21;
  --text-base-2: 16px;
  --leading-base-2: 1.2;
  --text-xl: 20px;
  --leading-xl: 1.25;
  --text-2xl: 24px;
  --leading-2xl: 1.35;
  --text-3xl: 30px;
  --leading-3xl: 1.2;
  --text-5xl: 64px;
  --leading-5xl: 1;
  --text-5xl-2: 80px;
  --leading-5xl-2: 1.1;
  --text-5xl-3: 96px;
  --leading-5xl-3: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 96px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-sm: rgb(226, 223, 254) 0px 0px 4px 0px;
}
```
