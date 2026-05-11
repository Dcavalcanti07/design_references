# Helloivy — Style Reference
> Architectural blueprint on creamy paper. Black lines precisely segment content on a soft background.

**Theme:** light

Hello Ivy presents as an architectural blueprint rendered on thick, creamy paper, conveying both structure and a subtle warmth. Heavy, bold titles anchor content, while a high-contrast monochromatic palette creates stark visual hierarchy. The signature feature is the strong grid system defined by fine black lines, segmenting content into clear, distinct blocks, as if each piece of information is a precisely cut and placed element within a larger, deliberate composition. Sparse use of color and a focus on sharp edges for everything but interactive elements contributes to a feeling of focused utility and quiet authority.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greige Canvas | `#faf6f0` | `--color-greige-canvas` | Page backgrounds, large content sections — provides a warm, inviting canvas for the high-contrast black elements. |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, icons, button backgrounds — the dominant accent, creating strong contrast and defining structure. |
| Soft Graphite | `#5e697f` | `--color-soft-graphite` | Secondary body text, subtle section headings — provides a softer alternative to Midnight Ink for less prominent textual elements, maintaining readability against Greige Canvas. |
| Pure White | `#ffffff` | `--color-pure-white` | Icon fills, occasional inverse text on dark backgrounds — used sparingly to create highlights and visual breaks. |

## Tokens — Typography

### Unbounded — Display headlines and section titles — its geometric, strong character provides a modern, impactful presence, especially when rendered in high weights and large sizes. The increased letter-spacing at larger sizes adds an airy, deliberate feel. · `--font-unbounded`
- **Substitute:** Montserrat, Poppins
- **Weights:** 400, 500
- **Sizes:** 20px, 34px, 62px, 82px
- **Line height:** 1.10, 1.20, 1.40
- **Letter spacing:** 0.01em, 0.02em
- **Role:** Display headlines and section titles — its geometric, strong character provides a modern, impactful presence, especially when rendered in high weights and large sizes. The increased letter-spacing at larger sizes adds an airy, deliberate feel.

### Inter — Primary body text, subheadings, and UI labels — its legibility and modern geometric construction make it ideal for dense information. The consistent slight negative letter-spacing (-0.02em) across all sizes enhances text density without sacrificing readability. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 27px, 32px
- **Line height:** 1.20, 1.40, 1.50, 1.57, 1.60
- **Letter spacing:** -0.02em
- **Role:** Primary body text, subheadings, and UI labels — its legibility and modern geometric construction make it ideal for dense information. The consistent slight negative letter-spacing (-0.02em) across all sizes enhances text density without sacrificing readability.

### system-ui (sans-serif fallback) — Small utility text, inline links, and discreet UI elements where Inter might be too strong — provides a lighter touch for less critical information or when a subtle system font is preferred. · `--font-system-ui-sans-serif-fallback`
- **Substitute:** inherit
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Small utility text, inline links, and discreet UI elements where Inter might be too strong — provides a lighter touch for less critical information or when a subtle system font is preferred.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.5 | -0.28px | `--text-body-sm` |
| body | 16px | 1.5 | -0.32px | `--text-body` |
| body-lg | 18px | 1.6 | -0.36px | `--text-body-lg` |
| heading-sm | 20px | 1.2 | 0.2px | `--text-heading-sm` |
| heading | 24px | 1.4 | -0.48px | `--text-heading` |
| heading-lg | 34px | 1.2 | 0.34px | `--text-heading-lg` |
| display | 82px | 1.1 | 1.64px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 8px |
| generic | 8px |
| pillButtons | 9999px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Navigation Link
**Role:** Main navigation items

Text uses Inter, 400 weight, 16px, Midnight Ink (#000000). No background or explicit padding, but positioned within clear horizontal spacing.

### Hero Headline
**Role:** Main page title

Unbounded font, 82px size, 1.10 line-height, 0.02em letter-spacing, Midnight Ink (#000000).

### Hero Body Text
**Role:** Introductory paragraph

Inter font, 18px size, 1.60 line-height, -0.02em letter-spacing, Soft Graphite (#5e697f).

### Feature Section Heading
**Role:** Section titles for feature blocks

Unbounded font, 20px size, 1.20 line-height, 0.01em letter-spacing, Midnight Ink (#000000). Often appears uppercase and centrally aligned.

### Footer 'Try it for Free' Button
**Role:** Persistent contact/CTA in footer

Solid Pill Button variant but with Pure White text color for consistency. Midnight Ink (#000000) background, 9999px border-radius. Positioned in a subtle fixed element.

## Do's and Don'ts

### Do
- Always define layout sections with subtle 1px Midnight Ink (#000000) borders against Greige Canvas (#faf6f0) to create a structured, architectural feel.
- Use Unbounded (weight 400-500) for all display headlines, setting letter-spacing to 0.02em for large titles (82px) and 0.01em for smaller section titles (20-34px).
- Apply Inter (weight 400-700) with a consistent -0.02em letter-spacing for all body text, subheadings, and UI labels.
- Utilize Greige Canvas (#faf6f0) as the primary background color for all page sections and content blocks.
- Implement 9999px border-radius for primary action buttons (Solid Pill Buttons) and 8px border-radius for secondary interactive elements (Outline Buttons).
- Maintain high contrast by using Midnight Ink (#000000) for all primary text and interactive elements on Greige Canvas (#faf6f0) backgrounds.
- Isolate Pure White (#ffffff) for subtle highlights, such as icon fills or inverse text on dark button backgrounds.

### Don't
- Avoid using highly saturated, chromatic colors; the palette is strictly monochromatic with a single warm neutral base.
- Do not deviate from the established 1px Midnight Ink (#000000) border style for section dividers and containers.
- Refrain from using drop shadows or complex elevation; depth is created through borders and color contrast.
- Do not introduce rounded corners on non-interactive content blocks or imagery; maintain sharp, defined edges for structure.
- Avoid decorative whitespace or intricate patterns; layout should be clean, grid-based, and functional.
- Do not use generic system fonts for body or heading text where Inter or Unbounded are specified; adhere to the defined typography for brand consistency.

## Imagery

The site uses minimal imagery, primarily focusing on clean UI mockups and desaturated client logos. Product screenshots are contained within distinct bordered sections, appearing like functional 'windows' into the application. Photography is absent. Client logos are grayscale and often subtly outlined, adhering to the monochromatic scheme. The visual language emphasizes product function over lifestyle or abstract art, acting mainly as explanatory content or social proof, contained and never full-bleed.

## Layout

The layout is max-width contained at approximately 1200px, centered on a Greige Canvas background. The hero section features a centered, enormous headline over the background. Section rhythm is created through a strong, visible grid system using fine 1px Midnight Ink borders that divide the page into distinct, almost cell-like blocks. Content often occupies full-width blocks or alternates between two-column text+visual arrangements. A clear client logo grid demonstrates social proof. Navigation is a simple top bar, with a persistent fixed 'Try it for free' button at the bottom right. The overall density is comfortable, with ample whitespace creating breathing room within the strict grid.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000
- Background (Primary): #faf6f0
- CTA Button (Solid): #000000
- Border: #000000
- Text (Secondary): #5e697f

### 3-5 Example Component Prompts
1. **Create a hero section:** Set background to Greige Canvas (#faf6f0). Add a centered headline using Unbounded, 82px, weight 400, #000000, line-height 1.1, letter-spacing 1.64px. Below it, add a body paragraph using Inter, 18px, weight 400, #5e697f, line-height 1.6, letter-spacing -0.36px. Include a Solid Pill Button centered below the text: Midnight Ink (#000000) background, Pure White (#ffffff) text, 9999px radius, 15px 30px padding.
2. **Generate an Outline Button:** Text 'Log In' using Inter, 16px, weight 400, #000000, line-height 1.2. Set background transparent, border 1px solid #000000, border-radius 8px, padding 15px 6px.
3. **Design a Client Logo Grid item:** Create a square container with a 1px solid Midnight Ink (#000000) border. Within, place a desaturated, grayscale logo (e.g., opacity 0.6) centered. Background should be Greige Canvas (#faf6f0).
4. **Produce a Feature Sub-section:** Start with a 1px solid Midnight Ink (#000000) horizontal rule. Below, place a heading 'Improve visibility, stay in the loop.' using Unbounded, 20px, weight 400, #000000, line-height 1.2, letter-spacing 0.2px. Follow with a body paragraph 'Hello Ivy helps creative teams...' using Inter, 16px, weight 400, #5e697f, line-height 1.5, letter-spacing -0.32px.

## Similar Brands

- **Linear** — Monochromatic, high-contrast UI with strong typography and a focus on essential elements, minimal decorative styles.
- **Figma** — Clean, functional typography, emphasis on structure through subtle lines, and a light background with dark text focus.
- **Basecamp** — Subtle, warm neutral backgrounds combined with clear, dark typography and a structured, grid-based approach to content organization.
- **Hey.com** — Distinctive custom typography for headlines and a strong preference for a limited, high-contrast color palette with structured layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greige-canvas: #faf6f0;
  --color-midnight-ink: #000000;
  --color-soft-graphite: #5e697f;
  --color-pure-white: #ffffff;

  /* Typography — Font Families */
  --font-unbounded: 'Unbounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui-sans-serif-fallback: 'system-ui (sans-serif fallback)', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.36px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.2px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.48px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.34px;
  --text-display: 82px;
  --leading-display: 1.1;
  --tracking-display: 1.64px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-buttons: 8px;
  --radius-generic: 8px;
  --radius-pillbuttons: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greige-canvas: #faf6f0;
  --color-midnight-ink: #000000;
  --color-soft-graphite: #5e697f;
  --color-pure-white: #ffffff;

  /* Typography */
  --font-unbounded: 'Unbounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui-sans-serif-fallback: 'system-ui (sans-serif fallback)', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.36px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.2px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.48px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.34px;
  --text-display: 82px;
  --leading-display: 1.1;
  --tracking-display: 1.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 100px;
  --radius-full-2: 9999px;
}
```
