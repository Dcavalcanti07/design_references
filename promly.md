# Promly — Style Reference
> Midnight gradient with neon accents.

**Theme:** dark

Promly uses a dark, immersive canvas with vibrant violet and blue accents that cut through the deep background like neon. Typography is direct and purposeful, maintaining legibility against the dark, gradient-infused surfaces. Components feature soft, rounded corners and subtle elevation, contributing to an approachable yet impactful aesthetic driven by energetic gradients and photography.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Deep | `#000000` | `--color-canvas-deep` | Page background, primary surface for text and core content |
| Midnight Indigo | `#040723` | `--color-midnight-indigo` | Elevated card surfaces, provides depth against Canvas Deep |
| Ghost Shadow Indigo | `#140f33` | `--color-ghost-shadow-indigo` | Shadow tint for elevated cards, adding a subtle indigo glow |
| Primary Blue Neon | `#3898ec` | `--color-primary-blue-neon` | Primary action buttons, active navigation items — a vivid, electric blue |
| Accent Violet Neon | `#755eff` | `--color-accent-violet-neon` | Outlined button borders, text for secondary actions and highlights — vibrant violet |
| Highlight Violet | `#aa57ff` | `--color-highlight-violet` | Outlined button borders, text for tertiary actions — a lighter, softer violet |
| Content White | `#ffffff` | `--color-content-white` | Primary text, button text on colored backgrounds, navigation links |
| Muted Gray | `#808080` | `--color-muted-gray` | Secondary body text, helper text, subtle outlines |
| Secondary Text Gray | `#999999` | `--color-secondary-text-gray` | Tertiary body text, supporting information |
| Input Text Dark | `#333333` | `--color-input-text-dark` | Input field placeholder text, some link text |
| Input Border Gray | `#cccccc` | `--color-input-border-gray` | Input field borders |
| Outlined Button Dark | `#222222` | `--color-outlined-button-dark` | Outlined button borders and text on light backgrounds |
| Gradient Hero Violet to Black | `linear-gradient(216deg, rgb(167, 85, 251) 20%, rgb(71, 36, 106) 37%, rgb(0, 0, 0) 90%)` | `--color-gradient-hero-violet-to-black` | Background for hero sections, creating a dynamic, immersive entry point |
| Gradient Card Violet to White | `linear-gradient(135deg, rgb(158, 88, 254) 39%, rgb(255, 255, 255))` | `--color-gradient-card-violet-to-white` | Background for feature cards, adding a vibrant and modern touch |
| Success Green | `#0be014` | `--color-success-green` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Avenir — Primary typeface for all headings, body text, and UI elements. Its clean sans-serif nature provides clarity against dark backgrounds, with a range of weights supporting hierarchy. Tighter tracking on larger headings enhances their presence without overwhelming. · `--font-avenir`
- **Substitute:** Avenir Next, Lato
- **Weights:** 300, 400, 700
- **Sizes:** 14px, 16px, 18px, 20px, 25px, 28px, 35px, 45px, 59px, 60px, 64px
- **Line height:** 1.07, 1.11, 1.17, 1.25, 1.36, 1.39, 1.40, 1.43, 1.50, 1.57, 1.69
- **Letter spacing:** -0.067em at 64px, -0.051em at 60px, -0.050em at 59px, -0.047em at 45px, -0.031em at 35px, 0.014em at 20px, 0.018em at 14px
- **Role:** Primary typeface for all headings, body text, and UI elements. Its clean sans-serif nature provides clarity against dark backgrounds, with a range of weights supporting hierarchy. Tighter tracking on larger headings enhances their presence without overwhelming.

### Poppins — Used for specific button labels, adding a slightly more assertive, block-like feel to calls to action. · `--font-poppins`
- **Substitute:** Montserrat, Open Sans
- **Weights:** 700
- **Sizes:** 18px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used for specific button labels, adding a slightly more assertive, block-like feel to calls to action.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | 0.252px | `--text-caption` |
| body-sm | 16px | 1.39 | — | `--text-body-sm` |
| body | 18px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | 0.28px | `--text-subheading` |
| heading-sm | 25px | 1.25 | — | `--text-heading-sm` |
| heading | 28px | 1.17 | — | `--text-heading` |
| heading-lg | 35px | 1.11 | -1.085px | `--text-heading-lg` |
| display | 45px | 1.07 | -2.115px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 25px |
| images | 20px |
| inputs | 12px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(102, 77, 255, 0.2) 0px 4px 100px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1196px
- **Section gap:** 88px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Main call to action.

Filled with Primary Blue Neon (#3898ec), text in Content White (#ffffff), rounded corners at 12px. Padding is 12px vertical, 24px horizontal. Uses Poppins Bold for text.

### Ghost Navigation Button
**Role:** Navigation links or secondary actions that sit directly on the dark canvas.

Transparent background, text in Outlined Button Dark (#222222), no border, 0px radius. Minimal padding of 5px vertical, 10px-30px horizontal, adapting to content. Uses Avenir.

### Violet Outline Button
**Role:** Accentuating secondary actions on dark backgrounds.

Transparent background, border in Accent Violet Neon (#755eff), text in Accent Violet Neon. 12px rounded corners, 12px vertical and 24px horizontal padding. Uses Avenir.

### Highlight Outline Button
**Role:** Tertiary interactive elements, often within cards.

Transparent background, border in Highlight Violet (#aa57ff), text in Highlight Violet. 12px rounded corners, 12px vertical and 24px horizontal padding. Uses Avenir.

### Floating Card
**Role:** Container for content sections, featuring subtle elevation.

Background is Midnight Indigo (#040723), with a 25px border-radius. Features a glow shadow: rgba(102, 77, 255, 0.2) 0px 4px 100px 0px.

### Standard Input Field
**Role:** User input for form elements.

Background is Canvas Deep (#000000), text in Input Text Dark (#333333). Border is 1px solid Input Border Gray (#cccccc), with 12px rounded corners. Padding is 8px vertical, 12px horizontal.

## Do's and Don'ts

### Do
- Always use Canvas Deep (#000000) as the primary page background.
- Apply 25px border-radius to card elements and 12px to buttons and inputs.
- Headlines should use Avenir with negative letter-spacing for sizes above 35px to maintain a refined appearance.
- Accentuate key calls to action with Primary Blue Neon (#3898ec) for filled buttons.
- Utilize the Midnight Indigo (#040723) background for elevated content cards, distinct from the main canvas.
- Maintain a clear visual hierarchy by using Content White (#ffffff) for primary text and Muted Gray (#808080) for secondary details.
- Ensure consistent Comfortable density spacing, with 20px as a common element gap and a section gap of 88px.

### Don't
- Avoid using bright, un-branded colors for large background areas; maintain the dark theme.
- Do not use generic square corners for cards or buttons; adhere to the specified radii of 25px and 12px.
- Refrain from using thin weights for body text without sufficient contrast; use Avenir 400 for general readability.
- Do not introduce additional shadow styles beyond the provided card elevation.
- Avoid deviating from the established letter-spacing values, especially for larger text, to preserve typographic character.
- Do not use a solid background color for hero sections; leverage the Gradient Hero Violet to Black.
- Do not use more than one distinct color for button fills; confine fills to Primary Blue Neon unless for semantic states.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Deep | `#000000` | Base page background |
| 1 | Midnight Indigo | `#040723` | Elevated card and section backgrounds |

## Elevation

- **Floating Card:** `rgba(102, 77, 255, 0.2) 0px 4px 100px 0px`

## Imagery

This site predominantly features photography and product screenshots. Photography is diverse, showing young people in various settings, often with a casual, authentic feel. Images for cards frequently feature rounded corners (20px or 30px) and appear as a grid or scattered collage within hero sections. Product screenshots are typically high-fidelity and contained within UI elements, showcasing app interfaces directly. Icons are used sparingly and seem to be simple, outlined, and monochromatic, with occasional green accents for success-oriented elements. The imagery serves to both establish atmosphere and provide visual evidence of community and product functionality, without being overly decorative or heavy.

## Layout

The page uses a maximum content width of 1196px, centered on the screen, creating a structured and comfortable reading experience. The hero section is full-bleed, blending a linear gradient from violet to black with a large, inviting headline and a collage of rounded-corner participant photos that visually 'pop' off the dark background. Subsequent sections alternate between full-width blocks and contained content. Text+image sections frequently use a side-by-side layout. Vertical spacing between sections is relatively generous, with an 88px section gap contributing to a comfortable density. Navigation is a sticky top bar, accommodating essential links and a 'Donate' button, ensuring actions are always accessible.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #cccccc
accent: #755eff
primary action: #3898ec (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #3898ec background, #222222 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a 'Floating Card': Midnight Indigo (#040723) background, 25px radius, with 'Ghost Shadow Indigo' for elevation. Inside, place a heading 'Find Your Voice' in Avenir Bold, 45px, Content White, letter-spacing -0.047em, and a paragraph of text in Content White at 18px Avenir Regular.

## Similar Brands

- **Discord** — Dark UI with vibrant, saturated accent colors for interactive elements and brand recognition.
- **Figma** — Clean, purposeful typography, a primary dark canvas, and a strong emphasis on interactive elements through color.
- **Notion (dark mode)** — Structured content on a dark background, with clear information hierarchy maintained by careful typography and subtle elevation.
- **Spotify** — Dominant dark theme with colorful gradients and highlights to signify branding and interactivity, often with rounded corners.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-deep: #000000;
  --color-midnight-indigo: #040723;
  --color-ghost-shadow-indigo: #140f33;
  --color-primary-blue-neon: #3898ec;
  --color-accent-violet-neon: #755eff;
  --color-highlight-violet: #aa57ff;
  --color-content-white: #ffffff;
  --color-muted-gray: #808080;
  --color-secondary-text-gray: #999999;
  --color-input-text-dark: #333333;
  --color-input-border-gray: #cccccc;
  --color-outlined-button-dark: #222222;
  --color-gradient-hero-violet-to-black: #a755fb;
  --gradient-gradient-hero-violet-to-black: linear-gradient(216deg, rgb(167, 85, 251) 20%, rgb(71, 36, 106) 37%, rgb(0, 0, 0) 90%);
  --color-gradient-card-violet-to-white: #9e58fe;
  --gradient-gradient-card-violet-to-white: linear-gradient(135deg, rgb(158, 88, 254) 39%, rgb(255, 255, 255));
  --color-success-green: #0be014;

  /* Typography — Font Families */
  --font-avenir: 'Avenir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.252px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.39;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.28px;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.085px;
  --text-display: 45px;
  --leading-display: 1.07;
  --tracking-display: -2.115px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1196px;
  --section-gap: 88px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;

  /* Named Radii */
  --radius-cards: 25px;
  --radius-images: 20px;
  --radius-inputs: 12px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-xl: rgba(102, 77, 255, 0.2) 0px 4px 100px 0px;

  /* Surfaces */
  --surface-canvas-deep: #000000;
  --surface-midnight-indigo: #040723;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-deep: #000000;
  --color-midnight-indigo: #040723;
  --color-ghost-shadow-indigo: #140f33;
  --color-primary-blue-neon: #3898ec;
  --color-accent-violet-neon: #755eff;
  --color-highlight-violet: #aa57ff;
  --color-content-white: #ffffff;
  --color-muted-gray: #808080;
  --color-secondary-text-gray: #999999;
  --color-input-text-dark: #333333;
  --color-input-border-gray: #cccccc;
  --color-outlined-button-dark: #222222;
  --color-gradient-hero-violet-to-black: #a755fb;
  --color-gradient-card-violet-to-white: #9e58fe;
  --color-success-green: #0be014;

  /* Typography */
  --font-avenir: 'Avenir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.252px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.39;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.28px;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.17;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.085px;
  --text-display: 45px;
  --leading-display: 1.07;
  --tracking-display: -2.115px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-3xl-2: 30px;

  /* Shadows */
  --shadow-xl: rgba(102, 77, 255, 0.2) 0px 4px 100px 0px;
}
```
