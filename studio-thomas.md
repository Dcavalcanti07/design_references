# Studio Thomas — Style Reference
> Vivid Orange Canvas

**Theme:** light

Studio Thomas employs a bold, high-contrast aesthetic characterized by large, confident typography and limited, impactful color use. A dominant, vivid orange serves as a high-energy backdrop for key messaging, while a soft, near-white neutral provides a calmer surface for secondary content. The design prioritizes stark visual impact with minimal UI elements beyond essential typography and navigation. This system projects a confident, direct, and slightly raw visual presence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Cloud Petal | `#ebe9e3` | `--color-cloud-petal` | Secondary background surfaces, muted text. A warm, very light neutral for content blocks and footers |
| Paper White | `#ffffff` | `--color-paper-white` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Titanium Grey | `#767676` | `--color-titanium-grey` | Input borders. A mid-tone neutral for functional elements |
| Impact Orange | `#ff4f00` | `--color-impact-orange` | Primary brand color, dominant background for hero sections and impactful statements – projects high energy and boldness |

## Tokens — Typography

### Moderat — All textual content, from headlines to body text and interactive elements. Its custom nature reinforces a unique brand voice, using subtle tracking for visual precision. · `--font-moderat`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 16px, 33px, 40px, 120px
- **Line height:** 1.00, 1.13, 1.20, 1.25, 1.60
- **Letter spacing:** -0.0040em, 0.0050em
- **Role:** All textual content, from headlines to body text and interactive elements. Its custom nature reinforces a unique brand voice, using subtle tracking for visual precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.2 | — | `--text-caption` |
| body-sm | 33px | 1.2 | — | `--text-body-sm` |
| body | 40px | 1.2 | — | `--text-body` |
| body-lg | 120px | 1.2 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 30px

## Components

### Ghost Button
**Role:** Call-to-action or secondary navigation button

Transparent background, Midnight Ink text and border, no padding or explicit radius. Appears as a text link with an implied hover treatment.

### Project Link
**Role:** Navigation for project showcases

Rendered as plain text in either Midnight Ink or Paper White, depending on background. Active interaction is subtly shown via underline or color shift, not distinct button styling.

### Basic Form Input
**Role:** Standard text input field

White background, Midnight Ink text (or Titanium Grey placeholder), with a 1px Titanium Grey border. Padding is minimal at 1px vertical and 2px horizontal.

### Main Navigation Toggle
**Role:** Hamburger icon for mobile/secondary navigation

Single-line icon in Midnight Ink or Paper White, indicating hidden menu.

### Hero Headline
**Role:** Primary attention-grabbing text on the hero section

Moderat 120px, weight 400, Paper White or Midnight Ink depending on background, with -0.0040em letter spacing for a tight, impactful display.

## Do's and Don'ts

### Do
- Prioritize high contrast pairings: Midnight Ink (#000000) on Paper White (#ffffff) or Impact Orange (#ff4f00), and Paper White (#ffffff) on Impact Orange (#ff4f00) or Midnight Ink (#000000).
- Use Impact Orange (#ff4f00) as a primary brand accent and background for sections intended to convey significant energy or primary brand messaging.
- Apply Moderat 400 at larger sizes (40px, 120px) for all headings to establish a bold, prominent typographic hierarchy.
- Maintain a default border-radius of 0px for all UI elements to uphold a sharp, unrounded aesthetic.
- Embed subtle letter spacing adjustments using Moderat's defined values (e.g., -0.0040em for larger text) to refine typographic appearance.
- Utilize Cloud Petal (#ebe9e3) for distinct background sections that require a softer contrast than pure white, providing a subtle visual break.
- Employ consistent 40px vertical section gaps to ensure spacious, uncrowded content presentation.

### Don't
- Avoid decorative box-shadows or elevation effects; the design relies on flat, high-contrast surfaces.
- Do not introduce rounded corners on any UI elements; the system explicitly uses 0px radius for a sharp look.
- Refrain from using gradients for backgrounds or components; the system favors solid, impactful color blocks.
- Do not use generic system fonts; Moderat is critical for conveying the brand's unique typographic identity.
- Avoid a high density of UI elements; screens should feel spacious, allowing key content and typography to stand out.
- Do not use multiple accent colors; Impact Orange (#ff4f00) is the sole vibrant color used for brand emphasis.

## Imagery

Imagery is high-contrast and often full-bleed, serving as a backdrop for bold typographic overlays. If photography, it features intimate, often nude human forms or product shots with minimal context. The treatment is natural, unmasked, and aims for raw authenticity rather than glossy perfection. Visuals are dominant, creating an immersive experience, or serve to showcase specific project work in a very direct, unstyled manner. Icons are minimal, typically line-based, matching the monochrome text color scheme.

## Layout

The page primarily utilizes a full-bleed layout for hero sections, often featuring a vast image or solid color field behind a centered, oversized headline. Content sections below are generally full-width but with visible side margins, and feature consistent vertical spacing of 40px between blocks. The arrangement often alternates between text-dominant blocks and full-width imagery, creating a rhythmic flow down the page. Navigation is minimal, consisting of a top-left logo and a right-aligned hamburger menu, ensuring the focus remains on central content and visuals.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ff4f00
border: #000000
accent: #ff4f00
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with a bold statement: `background-color: #ff4f00; display: flex; justify-content: center; align-items: center; height: 75vh;` Inside, place a headline `Moderat, 120px, 400 weight, color: #ffffff, text: 'Design for Bold Brands', letter-spacing: -0.0040em;`.
2. Design a project list item: `background-color: #ebe9e3; padding: 40px 20px; border-radius: 0px;` Inside, include a project title `Moderat, 40px, 400 weight, color: #000000, text: 'Chemical Free Period Care', letter-spacing: 0.0050em;` and a 'View project' link `Moderat, 16px, 400 weight, color: #000000;`.
3. Implement a simple input field: `background-color: #ffffff; border: 1px solid #767676; padding: 1px 2px; border-radius: 0px;` with content `Moderat, 16px, 400 weight, color: #000000;`.
4. Design a footer section: `background-color: #ebe9e3; padding-top: 100px; padding-bottom: 50px;` with project navigation links `Moderat, 16px, 400 weight, color: #000000;`.

## Similar Brands

- **Certain small/boutique design agencies** — They often use an understated UI, focusing on large-scale typography and strong visual imagery (photography/illustration) with an accent color rather than complex componentry.
- **Personal portfolio sites for graphic designers** — Many use bold full-screen imagery and impact-driven typography to showcase work directly, similar to the Studio Thomas approach.
- **Independent fashion brands** — They frequently use a stripped-back, high-contrast visual style with large headlines and evocative photography to create a strong, minimalist brand statement.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-petal: #ebe9e3;
  --color-paper-white: #ffffff;
  --color-titanium-grey: #767676;
  --color-impact-orange: #ff4f00;

  /* Typography — Font Families */
  --font-moderat: 'Moderat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 33px;
  --leading-body-sm: 1.2;
  --text-body: 40px;
  --leading-body: 1.2;
  --text-body-lg: 120px;
  --leading-body-lg: 1.2;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 30px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-petal: #ebe9e3;
  --color-paper-white: #ffffff;
  --color-titanium-grey: #767676;
  --color-impact-orange: #ff4f00;

  /* Typography */
  --font-moderat: 'Moderat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.2;
  --text-body-sm: 33px;
  --leading-body-sm: 1.2;
  --text-body: 40px;
  --leading-body: 1.2;
  --text-body-lg: 120px;
  --leading-body-lg: 1.2;

  /* Spacing */
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-100: 100px;
}
```
