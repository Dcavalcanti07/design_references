# Minimal Collective — Style Reference
> Gallery grit, monochromatic precision.

**Theme:** dark

Minimal Collective employs a muted, structured dark-mode aesthetic, reminiscent of an underground art gallery's concrete walls at dusk. The design prioritizes clear information hierarchy over visual flair, using a restricted achromatic palette with stark black as the dominant background and white for primary text. Typography is a focal point, with a custom geometric sans-serif font exhibiting varied, precise letter-spacing to create distinct visual rhythm. Layout is ordered and grid-constrained, with interactions subtly defined by slight shifts in background depth and crisp borders rather than vibrant color accents.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Graphite | `#5a5a5a` | `--color-graphite` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Parchment White | `#ffffff` | `--color-parchment-white` | Primary text on dark backgrounds, active states, emphasized labels, and element borders for high contrast |

## Tokens — Typography

### PolySans — The sole typeface for all text elements. Its geometric forms provide a modern, technical feel, and its consistent weight but varied letter-spacing across sizes is a signature trait. · `--font-polysans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px, 23px, 27px, 32px, 50px, 77px
- **Line height:** 0.90, 1.00, 1.20, 1.43
- **Letter spacing:** -0.0560em, -0.0440em, -0.0370em, -0.0320em, -0.0290em, -0.0200em
- **Role:** The sole typeface for all text elements. Its geometric forms provide a modern, technical feel, and its consistent weight but varied letter-spacing across sizes is a signature trait.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | -0.02px | `--text-caption` |
| body | 16px | 1.43 | -0.029px | `--text-body` |
| subheading | 18px | 1.2 | -0.032px | `--text-subheading` |
| heading-sm | 23px | 1.2 | -0.037px | `--text-heading-sm` |
| heading | 27px | 1.2 | -0.044px | `--text-heading` |
| heading-lg | 32px | 1 | -0.044px | `--text-heading-lg` |
| display | 77px | 0.9 | -0.056px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 9 | 9px | `--spacing-9` |
| 14 | 14px | `--spacing-14` |
| 18 | 18px | `--spacing-18` |
| 45 | 45px | `--spacing-45` |
| 54 | 54px | `--spacing-54` |
| 144 | 144px | `--spacing-144` |
| 173 | 173px | `--spacing-173` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 4.5px |
| default | 4.5px |

### Layout

- **Section gap:** 144px
- **Card padding:** 18px
- **Element gap:** 14px

## Components

### Header Navigation Link
**Role:** Primary navigation links

Uses PolySans at 14px, Graphite text color and a bottom border of 1px Void Black. On hover/active, text color is Parchment White and border changes to Parchment White.

### Main Heading
**Role:** Hero and major section titles

Large text, typically PolySans up to 77px, Parchment White, with tight letter-spacing of -0.056em for dramatic impact on dark backgrounds.

### Project Card Link
**Role:** Interactive content blocks for projects/articles

A square or rectangular block with an image or graphic. Text consists of PolySans at various sizes, Parchment White for titles, and Graphite for metadata. Minimal padding and a border outline in Void Black or Parchment White when interactive. Corner radius is 4.5px.

### Badge (Text Only)
**Role:** Categorization and metadata labels within content

Transparent background with Parchment White text (PolySans), no padding or border, used for labels like 'EDITORIAL' or 'PREMIERE'.

### Badge (Outlined)
**Role:** Categorization and metadata labels with visual distinction

Transparent background with Parchment White text (PolySans), 4.5px padding (vertical: 4.5px, horizontal: 6.3px), and a 4.5px border radius. Used for 'EDITORIAL' or 'PREMIERE' but with a clear visual boundary.

### Text Input (Underlined)
**Role:** Capturing user input

Graphite text on a transparent background, with a 1px solid Void Black bottom border. Padding of 18px on top and 4.5px at the bottom. No explicit border radius on the input itself.

## Do's and Don'ts

### Do
- Prioritize Void Black (#000000) for all significant backgrounds and borders to maintain the dark, structured aesthetic.
- Use Parchment White (#ffffff) exclusively for primary text and high-contrast interactive states against dark backgrounds.
- Apply precise letter-spacing values to PolySans as defined in the typography section, ensuring appropriate visual density for each text size.
- Utilize Graphite (#5a5a5a) for secondary information, input text, and subtle background differentiation on interactive elements.
- Maintain a subtle, comfortable density in layouts, especially between interactive elements, using `elementGap: 14px` and `sectionGap: 144px`.
- Incorporate a consistent border radius of 4.5px for all card-like elements, badges, and interactive components.
- Define interactive states with border changes and text color shifts using Parchment White, rather than introducing new chromatic colors.

### Don't
- Avoid introducing saturated colors; the palette is strictly achromatic, with any color appearing only as part of content imagery.
- Do not use heavy shadows or gradients for elevation; rely on subtle background color shifts (e.g., Void Black to Graphite) and crisp borders.
- Do not use generic font sizes or letter-spacing values; adhere to the specific PolySans scale and letter-spacing definitions.
- Avoid large, rounded button styles; interactive elements should favor minimal borders, subtle background changes, or smaller radii like 4.5px.
- Do not break the grid alignment; maintain strict vertical and horizontal rhythm with defined spacing tokens.
- Refrain from using bold or heavier font weights; PolySans 400 is the only weight available, focusing on form and spacing for emphasis.
- Avoid overly complex layouts or decorative flourishes; maintain the 'gallery grit' aesthetic with clear, functional arrangements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#5a5a5a` | Base background for sections and content blocks, providing a subtle contrast to the deepest black. |
| 1 | Primary Surface | `#000000` | Dominant background for the page, cards, and interactive elements, serving as the main 'void'. |

## Imagery

This site features a blend of photography and abstract graphics. Photography is often presented as raw crops or within defined boundaries, sometimes with a desaturated or muted color treatment to blend with the achromatic theme. Abstract graphics primarily consist of geometric patterns, often line-based like the large overlapping arcs in the hero section, contributing to a technical, structured feel. Icons, if present, are minimal outlined versions. Imagery serves primarily to set atmospheric mood or to showcase specific content (e.g., album art, event photos) within a structured grid, rather than for decorative excess. The density is image-heavy within content modules, but the overall page avoids full-bleed hero images, favoring a structured UI.

## Layout

The page primarily uses a full-bleed layout, particularly for the hero section with a centered headline against a dark background overlaid with geometric grid lines. Content sections often appear in distinct vertical bands, though seamless transitions are common. A prominent pattern is the division into two main columns, often featuring text on one side and an image or content block on the other, or a symmetric grid of project cards. Navigation is handled by a minimal fixed header bar at the top, a hamburger menu for mobile/secondary nav items, and a persistent footer at the bottom. The section rhythm is largely consistent, with ample vertical spacing like `sectionGap: 144px` creating breathing room between major content blocks.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #000000
accent: none observed
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Headline: 'Operating at the intersection of music, art and technology' with Parchment White (#ffffff) text, PolySans 77px, line height 0.9, letter-spacing -0.056em, centered on a Void Black (#000000) background that features a subtle geometric line grid overlay.
2. Design a Project Card Link: Use Void Black (#000000) as background, border all sides 1px Void Black. Inside, place an image, then a title in Parchment White (#ffffff) with PolySans 23px and line height 1.2, letter-spacing -0.037em. Add a Badge (Outlined) with 'EDITORIAL' in Parchment White (#ffffff) PolySans 14px, 4.5px padding, and 4.5px border radius. Ensure card padding is 18px.
3. Implement a Header Navigation Link: 'Editorial' using Graphite (#5a5a5a) PolySans 14px text, line height 1.43, letter-spacing -0.020em. Apply a 1px solid Void Black (#000000) bottom border. On hover, change text to Parchment White (#ffffff) and bottom border to 1px solid Parchment White.

## Similar Brands

- **A24** — Monochromatic, design-focused aesthetic with strong typography and minimal UI, letting content (film stills) take center stage.
- **The Fader** — Emphasis on journalistic content within a curated layout, using a limited color palette and strong typography to convey a 'cool' and artistic brand.
- **Resident Advisor** — Dark-mode interface, structured layout for music-related content, and a focus on essential information hierarchy over flashy visuals.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-graphite: #5a5a5a;
  --color-parchment-white: #ffffff;

  /* Typography — Font Families */
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.02px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.029px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.032px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.037px;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --tracking-heading: -0.044px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.044px;
  --text-display: 77px;
  --leading-display: 0.9;
  --tracking-display: -0.056px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-45: 45px;
  --spacing-54: 54px;
  --spacing-144: 144px;
  --spacing-173: 173px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 144px;
  --card-padding: 18px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 4.5px;

  /* Named Radii */
  --radius-badges: 4.5px;
  --radius-default: 4.5px;

  /* Surfaces */
  --surface-canvas: #5a5a5a;
  --surface-primary-surface: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-graphite: #5a5a5a;
  --color-parchment-white: #ffffff;

  /* Typography */
  --font-polysans: 'PolySans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.02px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.029px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.032px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.037px;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --tracking-heading: -0.044px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.044px;
  --text-display: 77px;
  --leading-display: 0.9;
  --tracking-display: -0.056px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-45: 45px;
  --spacing-54: 54px;
  --spacing-144: 144px;
  --spacing-173: 173px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-md: 4.5px;
}
```
