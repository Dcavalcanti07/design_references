# Dyotanya — Style Reference
> Playful blueprint on textured paper.

**Theme:** light

Dyotanya's visual system evokes a playful, hand-drawn blueprint aesthetic. It combines elegant serif typography with a stark, compact sans-serif, all set against a canvas of near-white. A single muted blue creates soft accents and interactive elements, often appearing as subtle borders. Dynamic, offset shadows add a touch of whimsy and depth to cards and elements, disrupting the otherwise flat surfaces.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#f5f5f3` | `--color-canvas-white` | Page backgrounds, card surfaces, secondary text background. This off-white ensures high contrast with text while providing a warmer, less stark base than pure white |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong borders, icons. Used for maximum contrast and emphasis against light backgrounds |
| Deep Charcoal | `#333333` | `--color-deep-charcoal` | Secondary text, input text, subtle borders, some interactive element backgrounds. Provides good readability without the harshness of pure black |
| Cloud White | `#ffffff` | `--color-cloud-white` | Button text (especially on accent colors), some subtle element borders |
| Sky Blueprint | `#81aed9` | `--color-sky-blueprint` | Outline borders, button backgrounds, input borders, interactive states. This muted blue is the primary accent, providing a calm, professional yet distinct pop of color |
| Sunset Orange | `#ff8562` | `--color-sunset-orange` | Link text, decorative accents. This vivid orange creates warmth and draws attention to clickable elements |
| Vivid Blue | `#55a1ea` | `--color-vivid-blue` | Accent borders, occasional decorative elements. A more saturated blue than Sky Blueprint, used for subtle visual differentiation |

## Tokens — Typography

### Simeiz — Headlines, expressive display text, and key narrative elements. Its elegant serif form provides a sense of craftsmanship and established authority, especially at larger sizes. · `--font-simeiz`
- **Substitute:** Playfair Display
- **Weights:** 300, 400
- **Sizes:** 16px, 18px, 24px, 30px, 46px, 48px, 80px
- **Line height:** 1.00, 1.20, 1.33, 1.35, 1.54, 1.55, 1.56
- **Role:** Headlines, expressive display text, and key narrative elements. Its elegant serif form provides a sense of craftsmanship and established authority, especially at larger sizes.

### Manrope — Body text, navigation, and compact UI labels. The consistent, modern sans-serif provides strong readability and a contemporary feel, especially with its slight negative letter-spacing for tightness. · `--font-manrope`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px, 18px
- **Line height:** 1.20, 1.29, 1.33, 1.36, 1.38, 1.40, 1.42, 1.43, 1.45, 1.56, 1.57, 1.58
- **Letter spacing:** -0.0360em
- **Role:** Body text, navigation, and compact UI labels. The consistent, modern sans-serif provides strong readability and a contemporary feel, especially with its slight negative letter-spacing for tightness.

### Times — Body text, icon labels, and secondary information on cards. Used sparingly, providing a classic, academic contrast to the primary sans-serif where a more traditional feel is desired. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Body text, icon labels, and secondary information on cards. Used sparingly, providing a classic, academic contrast to the primary sans-serif where a more traditional feel is desired.

### Suisse Intl — Minor labels and specific UI elements requiring a precise, condensed look. · `--font-suisse-intl`
- **Substitute:** Helvetica Neue
- **Weights:** 450
- **Sizes:** 14px
- **Line height:** 1.20
- **Role:** Minor labels and specific UI elements requiring a precise, condensed look.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body | 14px | 1.4 | — | `--text-body` |
| body-lg | 16px | 1.2 | — | `--text-body-lg` |
| subheading | 18px | 1.35 | — | `--text-subheading` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 30px | 1.54 | — | `--text-heading-lg` |
| display | 80px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 3000px |
| cards | 20px |
| inputs | 30px |
| buttons | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(51, 51, 51) 5px -5px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgb(51, 51, 51) 4px -4px 0px 0px` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 48px
- **Card padding:** 48px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action.

Filled with Sky Blueprint (#81aed9), text in Cloud White (#ffffff). Radius is 50px for a soft, pill-like shape. Padding 0px vertical, 15px horizontal.

### Outline Card with Shadow
**Role:** Feature cards, portfolio items.

Canvas White (#f5f5f3) background with Ink Black (#000000) 5px -5px 0px 0px offset shadow. Corner radius of 20px. Internal padding is 48px on all sides.

### Accent Card
**Role:** Highlighting specific content.

Background in Sky Blueprint (#81aed9). Radius is 30px. No box shadow. Internal padding is 0px.

### Round Input Field
**Role:** User input.

Transparent background with a bottom border of Sky Blueprint (#81aed9). Text in Deep Charcoal (#333333). Radius of 30px, with 10px top padding, 20px horizontal padding, and 0px bottom padding. Placeholder text is in Sky Blueprint.

### Thin Border Card
**Role:** Secondary content containers, subtle grouping.

Canvas White (#f5f5f3) background. Radius of 20px or 30px. No box shadow. Padding is 0px.

### Hamburger Menu Icon
**Role:** Navigation toggle.

Ink Black (#000000) lines on a Cloud White (#ffffff) circular background, bordered by Canvas White.

## Do's and Don'ts

### Do
- Use Sky Blueprint (#81aed9) as the primary accent color for all main interactive elements and borders.
- Apply Simeiz font for all heading and display text, prioritizing weights 300 and 400 at larger sizes for an elegant feel.
- Utilize an offset box-shadow of 5px -5px 0px 0px with Deep Charcoal (#333333) for elevated card elements to create a distinctive visual pop.
- Implement a default border-radius of 50px for primary action buttons to achieve a soft, pill-like appearance.
- Maintain a compact visual density, using 10px as a common element gap and 48px for internal card padding for a contained feel.
- Ensure primary text uses Ink Black (#000000) for maximum contrast against Canvas White (#f5f5f3) backgrounds.
- Introduce Sunset Orange (#ff8562) only for critical inline links, creating visual warmth and hierarchy.

### Don't
- Avoid using multiple chromatic colors; stick primarily to Sky Blueprint as the main brand accent and Sunset Orange specifically for links.
- Do not use heavy, dark backgrounds for sections; maintain Canvas White (#f5f5f3) or Cloud White (#ffffff) as dominant surfaces.
- Refrain from using strong, block-like shadows; the distinctive offset shadow is key to the brand's playful elevation.
- Do not deviate from the established border radii; roundness is a key identifier for buttons (50px), inputs (30px), and cards (20px/30px).
- Avoid excessive spacing between elements or sections; the design favors a 'compact' density, so larger gaps should be deliberate and functional.
- Do not use bold weights for Simeiz font; the brand's heading style relies on the lighter 300 or 400 weights for its restrained elegance.
- Do not apply text decoration (underline) on non-link text to avoid confusion; links are primarily identified by Sunset Orange (#ff8562).

## Elevation

- **Card:** `rgb(51, 51, 51) 5px -5px 0px 0px`
- **Other elements:** `rgb(51, 51, 51) 4px -4px 0px 0px`

## Imagery

The imagery style is minimalist and strategic, primarily featuring product shots or abstract elements contained within rounded shapes. Photography, where present (like the portrait or client work examples), uses a clean, high-key treatment, often desaturated or monochrome, allowing the colorful UI elements to stand out. Icons are simple, outlined, and monochromatic (Ink Black), complementing the hand-drawn aesthetic. Animated curly lines act as decorative dividers, adding to the 'blueprint' feel. Imagery serves to showcase work or add subtle visual interest rather than being a dominant content driver, maintaining a text-dominant hierarchy.

## Layout

The page adopts a max-width contained layout, allowing generous external padding that is bordered by a Sky Blueprint frame. The hero section features large, expressive Simeiz typography, dynamically arranged and sometimes overlapping with subtle graphical elements like the decorative curly line. Further sections alternate between white and muted backgrounds (though not explicitly shown in data, implied by general design contrast). Content is arranged in alternating text-left/image-right or vertical stacks. Card grids are prominent for portfolio items, featuring distinct offset shadows. The layout emphasizes ample whitespace and visual hierarchy, with a clear focus on typography in the hero area and organized content blocks below. Navigation is minimal, featuring a discreet hamburger menu in the top right.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f5f5f3
border: #81aed9
accent: #ff8562
primary action: #81aed9 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #81aed9 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a portfolio card: background #f5f5f3, borders 20px radius, shadow #333333 5px -5px 0px 0px, internal padding 48px. Headline text should be Simeiz 24px weight 400, color #000000.
3. Implement an input field: transparent background, bottom border #81aed9, text #333333, radius 30px, horizontal padding 20px, top padding 10px. Placeholder text is Manrope 16px weight 400 in #81aed9.
4. Produce a link: text color #ff8562, font Manrope 16px weight 400. Not underlined.

## Similar Brands

- **Figma** — Utilizes a clean, mostly monochrome interface with a single vibrant accent color for interactive elements and highlights.
- **Webflow** — Features a distinct playful, design-forward aesthetic with custom typography and attention to small, artful details.
- **Basement Studio** — Employs an elegant, often-serif-heavy typography blend with simple layouts and subtle interactive animations.
- **Linear** — Known for a compact UI, strong typographic hierarchy, and the effective use of subtle elevation and borders for structure.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #f5f5f3;
  --color-ink-black: #000000;
  --color-deep-charcoal: #333333;
  --color-cloud-white: #ffffff;
  --color-sky-blueprint: #81aed9;
  --color-sunset-orange: #ff8562;
  --color-vivid-blue: #55a1ea;

  /* Typography — Font Families */
  --font-simeiz: 'Simeiz', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.54;
  --text-display: 80px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 48px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 1.5px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 50px;
  --radius-full-2: 91px;
  --radius-full-3: 100px;
  --radius-full-4: 120px;
  --radius-full-5: 1000px;
  --radius-full-6: 3000px;
  --radius-full-7: 9999px;

  /* Named Radii */
  --radius-tags: 3000px;
  --radius-cards: 20px;
  --radius-inputs: 30px;
  --radius-buttons: 50px;

  /* Shadows */
  --shadow-subtle: rgb(51, 51, 51) 5px -5px 0px 0px;
  --shadow-subtle-2: rgb(51, 51, 51) 4px -4px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #f5f5f3;
  --color-ink-black: #000000;
  --color-deep-charcoal: #333333;
  --color-cloud-white: #ffffff;
  --color-sky-blueprint: #81aed9;
  --color-sunset-orange: #ff8562;
  --color-vivid-blue: #55a1ea;

  /* Typography */
  --font-simeiz: 'Simeiz', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.54;
  --text-display: 80px;
  --leading-display: 1;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-sm: 1.5px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 50px;
  --radius-full-2: 91px;
  --radius-full-3: 100px;
  --radius-full-4: 120px;
  --radius-full-5: 1000px;
  --radius-full-6: 3000px;
  --radius-full-7: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(51, 51, 51) 5px -5px 0px 0px;
  --shadow-subtle-2: rgb(51, 51, 51) 4px -4px 0px 0px;
}
```
