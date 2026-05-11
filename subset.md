# Subset — Style Reference
> Organic Canvas, Understated Authority

**Theme:** light

Subset embraces a grounded, natural aesthetic, combining the tactile feel of organic materials with a clean, unadorned interface. The visual design prioritizes clear product presentation against a muted, almost oatmeal-colored canvas, punctuated by utilitarian typography and a few carefully chosen, moderately saturated accent colors. Components are minimal and unfussy, focusing on function over adornment, embodying a sense of reliable simplicity. Color is used sparingly, primarily to distinguish states or add a subtle brand signature rather than for bold visual statements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Oatmeal Canvas | `#f5f4ee` | `--color-oatmeal-canvas` | Page backgrounds, card surfaces — a soft, natural base |
| Ink | `#241f20` | `--color-ink` | Primary text, borders, icons, and significant structural elements. Almost black, but with a barely-there warmth |
| Pure White | `#ffffff` | `--color-pure-white` | Contrasting text colors, selected component backgrounds, input fields, and badge borders |
| Cool Stone | `#808080` | `--color-cool-stone` | Muted text, secondary icons, and subtle borders |
| Rich Earth | `#000000` | `--color-rich-earth` | Bold text, specific icon fills, and strong outlines |
| Deep Forest | `#233735` | `--color-deep-forest` | Prominent button backgrounds and borders for primary actions — a sophisticated, deep green-gray |
| Mineral Blue | `#6487ba` | `--color-mineral-blue` | Secondary action button backgrounds and borders, link colors — a calm, inviting blue |
| Spring Bud | `#8bbd78` | `--color-spring-bud` | Decorative icons, borders, and subtle typographic accents for specific elements |
| Sunset Orange | `#ff965b` | `--color-sunset-orange` | Highlight elements like badges, decorative icons, and rating stars — a vivid, energetic accent |
| Misty Rose | `#edcdc2` | `--color-misty-rose` | Background for specific content sections or decorative elements — a soft, desaturated blush tone |
| Olive Green | `#5b7763` | `--color-olive-green` | Background for specific content sections or decorative elements |
| Dark Plum | `#27293d` | `--color-dark-plum` | Decorative background for featured links |
| Warm Berry | `#5c2722` | `--color-warm-berry` | Decorative background for featured links |

## Tokens — Typography

### FoundersGrotesk — Used for all body text, navigation elements, buttons, and form labels. Its robust versatility and wide range of weights and sizes make it the system's workhorse, providing a grounded, utilitarian feel with subtle tracking variations for different scales. · `--font-foundersgrotesk`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 18px, 20px, 24px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.40, 1.43, 1.46, 1.50, 1.53, 1.60, 1.63
- **Letter spacing:** 0.0180em, 0.0210em, 0.0240em, 0.0250em, 0.0270em, 0.0280em, 0.0300em, 0.0330em, 0.1000em, 0.1500em
- **Role:** Used for all body text, navigation elements, buttons, and form labels. Its robust versatility and wide range of weights and sizes make it the system's workhorse, providing a grounded, utilitarian feel with subtle tracking variations for different scales.

### TTRamillas_Light — Exclusively for display headlines and prominent section titles. Its light weight and negative letter-spacing create an elegant and airy contrast to the FoundersGrotesk, conveying authority through refinement rather than bold impact. · `--font-ttramillaslight`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 18px, 20px, 24px, 32px, 40px, 42px
- **Line height:** 1.00, 1.20, 1.24, 1.29, 1.38, 1.40, 1.53
- **Letter spacing:** -0.0100em
- **Role:** Exclusively for display headlines and prominent section titles. Its light weight and negative letter-spacing create an elegant and airy contrast to the FoundersGrotesk, conveying authority through refinement rather than bold impact.

### GTStandard-M — A singular use case as a mono-spaced variant, likely for specific metadata or code-like elements where fixed-width characters are desired. · `--font-gtstandard-m`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 17px
- **Line height:** 1.50
- **Letter spacing:** 0.0250em
- **Role:** A singular use case as a mono-spaced variant, likely for specific metadata or code-like elements where fixed-width characters are desired.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | 0.3px | `--text-caption` |
| heading | 18px | 1.4 | -0.1px | `--text-heading` |
| heading-lg | 24px | 1.29 | -0.1px | `--text-heading-lg` |
| display | 42px | 1 | -0.1px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 0px |
| inputs | 0px |
| buttons | 0px |
| circularElements | 50% |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action.

Background: Deep Forest (#233735). Text: Pure White (#ffffff). Padding: 16px vertical, 32px horizontal. Border radius: 0px. Typography: FoundersGrotesk, 16px, 400 weight.

### Secondary Action Button
**Role:** Filled button for alternative calls to action.

Background: Mineral Blue (#6487ba). Text: Pure White (#ffffff). Padding: 16px vertical, 32px horizontal. Border radius: 0px. Typography: FoundersGrotesk, 16px, 400 weight.

### Ghost Button
**Role:** Outlined button for less prominent actions.

Background: transparent. Text: Ink (#241f20). Border: 1px Ink (#241f20). Padding: 0px. Border radius: 50% for icon-only, 0px for text. Typography: FoundersGrotesk.

### Informative Badge
**Role:** Small, distinct label for status or newness.

Background: Sunset Orange (#ff965b). Text: Pure White (#ffffff). Padding: 8px vertical, 10px horizontal. Border radius: 0px. Typography: FoundersGrotesk, 13px, 400 weight.

### Product Card
**Role:** Container for product listings.

Background: Oatmeal Canvas (#f5f4ee). Padding: 16px on all sides. Border radius: 0px. No shadow. Content flows within.

### Transparent Content Card
**Role:** Card with transparent background, often used in hero or overlay contexts.

Background: transparent. Padding: 48px vertical, 16px horizontal. Border radius: 0px. No shadow. Primarily for text and internal elements.

### Text Input
**Role:** Standard form input field.

Background: Pure White (#ffffff). Text: Ink (#241f20). Border: 1px Ink (#241f20). Padding: 18px vertical, 18px left, 40px right. Border radius: 0px. Placeholder text is in a lighter neutral.

## Do's and Don'ts

### Do
- Prioritize FoundersGrotesk for all functional text, ensuring precise letter-spacing at different scales to maintain a compact, legible feel.
- Use TTRamillas_Light for all marketing headlines; its light weight and negative tracking provide an elegant contrast.
- Maintain a strict 0px border-radius for all component cards, badges, and primary/secondary buttons to preserve the structured, unadorned aesthetic.
- Apply Oatmeal Canvas (#f5f4ee) as the primary background for all static content areas, grounding the interface in a natural, soft tone.
- Use Deep Forest (#233735) for filled primary action buttons and Mineral Blue (#6487ba) for secondary actions; these are the core chromatic accents.
- Separate content sections with ample vertical spacing (64px sectionGap) for visual breathing room, avoiding horizontal dividers between major content blocks.
- Employ a 50% border-radius for all circular interactive elements and small ghost buttons, creating distinct visual cues.

### Don't
- Avoid using drop shadows on any components; the system relies on flat surfaces and clear borders for definition.
- Do not introduce new typefaces; FoundersGrotesk and TTRamillas_Light are the only approved fonts.
- Refrain from using gradients for backgrounds or components; the design emphasizes flat, solid colors.
- Do not use saturated chroma for general text or borders; stick to the neutral palette for UI elements to maintain a muted appearance.
- Avoid decorative icons or illustrations that are not rendered in Spring Bud (#8bbd78) or Sunset Orange (#ff965b); color accents are reserved and intentional.
- Do not deviate from the specified padding and margin values; the compact density is carefully calibrated.
- Never use `box-shadow` for elevation, as this design system eschews overt layering effects.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Oatmeal Canvas | `#f5f4ee` | Base page background and default card surface. |
| 2 | Pure White | `#ffffff` | Elevated card backgrounds, input fields, and certain contrasting UI elements. |

## Imagery

The imagery leans heavily on product photography and lifestyle shots featuring models. Photography is characterized by tight crops for products on white or light backgrounds, emphasizing texture and detail, and lifestyle shots showing people wearing the clothes, often with a natural, candid feel and muted lighting. The overall treatment is realistic and unretouched, celebrating authentic body shapes and natural settings. Icons are minimal, either outlined or filled in achromatic tones, with occasional accents of Spring Bud or Sunset Orange for decorative or functional purposes. The density is mixed; some sections are text-dominant, while product grids are image-heavy, balancing showcase with information.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section often features a full-bleed image with an overlaid transparent content card for text and calls to action. Sections generally maintain consistent vertical spacing, creating structured blocks of content. Feature sections commonly use a grid of cards or alternating text-left / image-right arrangements. The navigation is a classic top bar, which appears to be fixed on scroll for persistent access.

## Agent Prompt Guide

Quick Color Reference: 
text: #241f20
background: #f5f4ee
border: #241f20
accent: #ff965b
primary action: #233735 (filled action)

Example Component Prompts:
1. Create a primary action button: background #233735, text #ffffff, 16px vertical/32px horizontal padding, 0px border-radius, FoundersGrotesk 16px weight 400.
2. Create an informative badge: background #ff965b, text #ffffff, 8px vertical/10px horizontal padding, 0px border-radius, FoundersGrotesk 13px weight 400.
3. Create a product card: background #f5f4ee, 16px padding on all sides, 0px border-radius.
4. Create a hero section: full-bleed image with an overlaid transparent card (background rgba(0,0,0,0), 48px vertical/16px horizontal padding) containing a headline in TTRamillas_Light 42px weight 400 color Ink (#241f20) and a secondary action button (background #6487ba, text #ffffff, 16px vertical/32px horizontal padding, 0px border-radius, FoundersGrotesk 16px weight 400).
5. Create a standard text input: background #ffffff, text #241f20, border 1px #241f20, 18px top/bottom/left padding, 40px right padding, 0px border-radius.

## Similar Brands

- **Kotn** — Shares a focus on organic materials, muted color palettes, and a clean, product-focused e-commerce experience.
- **Everlane** — Similar emphasis on essential, quality basics with an understated and transparent brand aesthetic.
- **CUUP** — Utilizes a clean, white-space heavy layout with focused product photography and a minimalist typographic approach.
- **Brooklinen** — Employs an achromatic visual style with an occasional soft accent color, simple product presentation, and classic typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-oatmeal-canvas: #f5f4ee;
  --color-ink: #241f20;
  --color-pure-white: #ffffff;
  --color-cool-stone: #808080;
  --color-rich-earth: #000000;
  --color-deep-forest: #233735;
  --color-mineral-blue: #6487ba;
  --color-spring-bud: #8bbd78;
  --color-sunset-orange: #ff965b;
  --color-misty-rose: #edcdc2;
  --color-olive-green: #5b7763;
  --color-dark-plum: #27293d;
  --color-warm-berry: #5c2722;

  /* Typography — Font Families */
  --font-foundersgrotesk: 'FoundersGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ttramillaslight: 'TTRamillas_Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --tracking-heading: -0.1px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.29;
  --tracking-heading-lg: -0.1px;
  --text-display: 42px;
  --leading-display: 1;
  --tracking-display: -0.1px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;
  --radius-circularelements: 50%;

  /* Surfaces */
  --surface-oatmeal-canvas: #f5f4ee;
  --surface-pure-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-oatmeal-canvas: #f5f4ee;
  --color-ink: #241f20;
  --color-pure-white: #ffffff;
  --color-cool-stone: #808080;
  --color-rich-earth: #000000;
  --color-deep-forest: #233735;
  --color-mineral-blue: #6487ba;
  --color-spring-bud: #8bbd78;
  --color-sunset-orange: #ff965b;
  --color-misty-rose: #edcdc2;
  --color-olive-green: #5b7763;
  --color-dark-plum: #27293d;
  --color-warm-berry: #5c2722;

  /* Typography */
  --font-foundersgrotesk: 'FoundersGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ttramillaslight: 'TTRamillas_Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --tracking-heading: -0.1px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.29;
  --tracking-heading-lg: -0.1px;
  --text-display: 42px;
  --leading-display: 1;
  --tracking-display: -0.1px;

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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-160: 160px;
}
```
