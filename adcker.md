# Adcker — Style Reference
> Monolithic text, stark contrast

**Theme:** light

Adcker employs a bold, high-contrast visual system built around monolithic typography and a stark achromatic palette. Dominant dark text on off-white surfaces creates a strong, unapologetic presence.  Subtle variations in background light neutrals provide a sense of depth, while minimal interactive elements keep the focus on the powerful typographic statements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ebon Black | `#191919` | `--color-ebon-black` | Primary text, prominent headings, borders for ghost components, active states. This intense black provides the foundational contrast for the monochromatic system |
| Linen Canvas | `#efedea` | `--color-linen-canvas` | Main page background, default surface for most UI elements. Its slightly warm off-white prevents a sterile feel |
| Frosted Gray | `#e3e1de` | `--color-frosted-gray` | Secondary background, subtle dividers, accent areas that require slightly more separation from the main canvas. Offers a quiet visual break |
| Neon Blue | `#007aff` | `--color-neon-blue` | Swiper navigation theme color (inferred from CSS token). Acts as a rare, functional accent in an otherwise achromatic system |

## Tokens — Typography

### nhm — Primary display font for hero headlines and key brand statements. Its tight tracking and robust weights create a powerful, commanding presence, defining the brand's voice. · `--font-nhm`
- **Substitute:** Montserrat
- **Weights:** 400, 700
- **Sizes:** 16px, 21px, 173px, 185px
- **Line height:** 0.78, 1.00, 1.10, 1.20
- **Letter spacing:** -0.05em
- **Role:** Primary display font for hero headlines and key brand statements. Its tight tracking and robust weights create a powerful, commanding presence, defining the brand's voice.

### psr — Body text and supporting information. This legible sans-serif ensures clarity for longer content, contrasting with the dramatic display font. · `--font-psr`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 21px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Body text and supporting information. This legible sans-serif ensures clarity for longer content, contrasting with the dramatic display font.

### Kumbh Sans — Used for hero headline variations and large typographic elements. Its similarity to 'nhm' reinforces the heavy, impactful headline style. · `--font-kumbh-sans`
- **Substitute:** Oswald
- **Weights:** 400
- **Sizes:** 173px, 185px
- **Line height:** 0.78, 0.80
- **Letter spacing:** -0.05em
- **Role:** Used for hero headline variations and large typographic elements. Its similarity to 'nhm' reinforces the heavy, impactful headline style.

### psl — Large subheadings and impactful text blocks. This font provides a slightly more condensed feel than the primary display fonts, maintaining a strong typographic hierarchy. · `--font-psl`
- **Substitute:** Barlow Condensed
- **Weights:** 400
- **Sizes:** 34px, 69px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.015em
- **Role:** Large subheadings and impactful text blocks. This font provides a slightly more condensed feel than the primary display fonts, maintaining a strong typographic hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.1 | — | `--text-caption` |
| body-sm | 21px | 1.1 | — | `--text-body-sm` |
| body | 173px | 1.1 | — | `--text-body` |
| body-lg | 185px | 1.1 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 112 | 112px | `--spacing-112` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 200px
- **Card padding:** 15px
- **Element gap:** 4px

## Components

### Navigation Link
**Role:** Standard interactive text link in headers and footers.

Text uses 'Ebon Black' (#191919) at 16px, weight 400. On hover or active state, a 1px 'Ebon Black' (#191919) border appears at the bottom with 2px padding.

### Ghost Button (Outlined)
**Role:** Visually subtle interactive element for secondary actions, such as navigation items or 'Read More' links.

Text color is 'Ebon Black' (#191919) with a 1px solid 'Ebon Black' (#191919) border. Background is transparent or 'Linen Canvas' (#efedea). No distinct border-radius, implying sharp corners. Padding varies but often includes 15px along vertical axis.

### Hero Large Text
**Role:** Dominant, attention-grabbing text for hero sections.

Text color is 'Ebon Black' (#191919), varying between 173px and 185px, with a line-height as low as 0.78 and letter-spacing of -0.05em. Uses 'nhm' or 'Kumbh Sans' font families, weight 400 or 700. Often appears centered.

### Body Text Block
**Role:** Main paragraph content.

Text is 'Ebon Black' (#191919) at 21px, weight 400, with normal letter pacing. Uses the 'psr' font family. Line height is 1.0. Appears on 'Linen Canvas' (#efedea) background.

### Section Subheading
**Role:** Secondary headings that introduce content blocks.

Text is 'Ebon Black' (#191919), sizes 34px or 69px, font family 'psl', weight 400, with a letter spacing of -0.015em.

## Do's and Don'ts

### Do
- Prioritize 'Ebon Black' (#191919) for all primary text, headings, and outlines on light backgrounds.
- Utilize 'Linen Canvas' (#efedea) as the primary background for all major sections and UI components.
- Employ the 'nhm' and 'Kumbh Sans' fonts with tight letter-spacing (-0.05em) for all large, impactful headlines.
- Maintain a clear visual hierarchy by contrasting the large, heavy display fonts with the more open 'psr' font for body text.
- Use 'Frosted Gray' (#e3e1de) sparingly for subtle background differentiation in secondary content blocks or dividers, maintaining overall achromatic feel.
- Ensure interactive elements like ghost buttons use 'Ebon Black' (#191919) for both text and border to maintain visual consistency.
- Implement motion using 'ease' timing functions and 0.7s durations for a deliberate, controlled feel.

### Don't
- Avoid introducing additional saturated colors beyond 'Neon Blue' (#007aff) without specific functional justification.
- Do not use soft shadows or complex gradients; the system relies on stark achromatic contrast.
- Refrain from using lightweight fonts for primary headlines; the system's identity is built on heavy, commanding typography.
- Do not deviate from the established tight letter-spacing for display fonts; it is a signature characteristic.
- Avoid overly decorative elements; clarity and directness are paramount.
- Do not use rounded corners beyond 0px; the system emphasizes sharp, defined edges.
- Avoid dense, information-heavy layouts; maintain ample negative space, especially around typographic elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Linen Canvas | `#efedea` | Primary page background and default surface for most UI elements. |
| 2 | Frosted Gray | `#e3e1de` | Subtle secondary background or accent areas, providing a minimal visual lift from the main canvas. |

## Imagery

This design system relies heavily on stark typography rather than extensive imagery. When images are present, like the embedded 'Showreel' image, they appear as tight crops of individuals, focusing directly on the face with a natural, sunlit feel. These are contained within typographic arrangements, not bleeding across the layout. The iconography, if present (not clearly visible in the screenshot), would likely be minimal, perhaps outlined, to support the clean, high-contrast aesthetic.

## Layout

The page exhibits a max-width contained layout, though the exact max-width isn't specified, content is centered with ample horizontal padding. The hero section is characterized by massive, centered typographic statements broken by small, contained inset images or text. Sections have consistent vertical spacing, often indicated by generous padding of '200px' as a section gap. Content arrangement appears to be primarily centered blocks, with strong visual separation between major typographic statements.

## Agent Prompt Guide

Quick Color Reference: text: #191919, background: #efedea, border: #191919, accent: #007aff, primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Headline: Text 'THE ART' and 'OF HACKING SOCIAL' in 'Ebon Black' (#191919), font 'nhm' (or 'Kumbh Sans') at 185px, weight 700 with letter-spacing -0.05em, line-height 0.78, centered on 'Linen Canvas' (#efedea). Embed a cropped image between lines as seen in the original, maintaining the stark typographical visual break.
2. Create a Ghost Navigation Item: Text 'Menu' in 'Ebon Black' (#191919), font 'nhm' at 16px, weight 400. Border bottom 1px solid 'Ebon Black' (#191919) with 2px padding-bottom.
3. Create a Body Text Block: Text 'In a world where everyone is...' in 'Ebon Black' (#191919), font 'psr' at 21px, weight 400, normal letter-spacing, line-height 1.0, on 'Linen Canvas' (#efedea).

## Similar Brands

- **AIGA** — Dominant, impactful typography as the primary visual element, stark black-on-white contrast.
- **House Industries** — Heavy reliance on custom, bold display typefaces with tight letter-spacing for brand identity.
- **Grilli Type** — Minimalist, high-contrast layouts driven by strong typographic statements and limited color palettes.
- **Certain graphic design portfolios** — Focus on large, experimental typography and a restricted grayscale palette to emphasize content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ebon-black: #191919;
  --color-linen-canvas: #efedea;
  --color-frosted-gray: #e3e1de;
  --color-neon-blue: #007aff;

  /* Typography — Font Families */
  --font-nhm: 'nhm', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-psr: 'psr', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kumbh-sans: 'Kumbh Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-psl: 'psl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.1;
  --text-body-sm: 21px;
  --leading-body-sm: 1.1;
  --text-body: 173px;
  --leading-body: 1.1;
  --text-body-lg: 185px;
  --leading-body-lg: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-112: 112px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 200px;
  --card-padding: 15px;
  --element-gap: 4px;

  /* Named Radii */
  --radius-default: 0px;

  /* Surfaces */
  --surface-linen-canvas: #efedea;
  --surface-frosted-gray: #e3e1de;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ebon-black: #191919;
  --color-linen-canvas: #efedea;
  --color-frosted-gray: #e3e1de;
  --color-neon-blue: #007aff;

  /* Typography */
  --font-nhm: 'nhm', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-psr: 'psr', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kumbh-sans: 'Kumbh Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-psl: 'psl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.1;
  --text-body-sm: 21px;
  --leading-body-sm: 1.1;
  --text-body: 173px;
  --leading-body: 1.1;
  --text-body-lg: 185px;
  --leading-body-lg: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-112: 112px;
  --spacing-200: 200px;
}
```
