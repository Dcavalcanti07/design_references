# Anuc Home — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Anuc Home cultivates a tranquil, refined interior design aesthetic, built on a foundation of generous negative space and a clean, light color palette. The typography, a blend of a sturdy sans-serif and an elegant serif, establishes a sense of understated sophistication. Components are minimalist, focusing on structure and form through subtle bordering and ample padding rather than heavy fills or shadows. The overall impression is one of calm authority and thoughtful curation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#1a1a1e` | `--color-ink` | Primary text, critical borders, dark outlines for subtle definition |
| Canvas | `#ffffff` | `--color-canvas` | Main page background, default surface for cards and elements |
| Fog | `#f3f3f2` | `--color-fog` | Subtle background for UI sections, secondary canvas |
| Ash | `#e7e6e4` | `--color-ash` | Background for secondary panels and subtle cards, borders |
| Stone | `#d1d1d2` | `--color-stone` | Muted text, inactive states, dividers, and background elements |
| Flint | `#c1c2bd` | `--color-flint` | Lightest borders, subtle decorative details |
| Charcoal | `#4d4942` | `--color-charcoal` | Sub-headings and descriptive body text, offering a slightly softer contrast than Ink |
| Bronze Accent | `#9a682c` | `--color-bronze-accent` | Decorative highlights, specific navigation elements, and brand accents |
| Slate Accent | `#4a626f` | `--color-slate-accent` | Secondary decorative highlights, specific navigation elements |

## Tokens — Typography

### Instrument Serif — Headlines, expressive display text, and select emphasis. The serif brings a classic, elegant touch, especially at larger sizes. · `--font-instrument-serif`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 15px, 16px, 32px, 52px, 74px
- **Line height:** 1.00, 1.10, 1.20
- **Role:** Headlines, expressive display text, and select emphasis. The serif brings a classic, elegant touch, especially at larger sizes.

### Instrument Sans — Body copy, button text, navigation, and functional UI elements. Its clean lines ensure readability and provide a modern counterpoint to the serif. · `--font-instrument-sans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 15px, 16px, 18px
- **Line height:** 1.20
- **Role:** Body copy, button text, navigation, and functional UI elements. Its clean lines ensure readability and provide a modern counterpoint to the serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 15px | 1.2 | — | `--text-caption` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 32px | 1.2 | — | `--text-heading-sm` |
| heading | 52px | 1.1 | — | `--text-heading` |
| display | 74px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 96 | 96px | `--spacing-96` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 96px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Ghost Button
**Role:** Interactive element for key actions, emphasizing a clean minimal aesthetic.

Background: Canvas (#ffffff), Text: Ink (#1a1a1e), Border: 1px solid Fog (#f3f3f2), Padding: 24px around text, Radius: 0px.

### Secondary Ghost Button
**Role:** Interactive element for secondary actions, offering slightly reduced visual prominence.

Background: Ash (#e7e6e4), Text: Ink (#1a1a1e), Border: 1px solid Fog (#f3f3f2), Padding: 24px around text, Radius: 0px.

### Article Tag Button
**Role:** Categorization tag for articles, with a subtle background.

Background: Stone (#d1d1d2), Text: Ink (#1a1a1e), No border, Padding: 0px top/bottom, 24px left/right, Radius: 0px.

### Navigation Link
**Role:** Primary navigation items in the header.

Text: Ink (#1a1a1e) at 16px Instrument Sans, Background: transparent on hover, accent colors may appear for active states.

### Image Overlay Heading
**Role:** Headline text positioned over hero imagery.

Text: Canvas (#ffffff) at 74px Instrument Serif, lineHeight 1.0, letterSpacing normal.

### Article Card
**Role:** Container for article previews, with a clean, structured appearance.

Background: Canvas (#ffffff) or Ash (#e7e6e4), Text: Ink (#1a1a1e), Border: 1px solid Fog (#f3f3f2), Padding: 24px, Radius: 0px.

### Numbered Section Indicator
**Role:** Sequential numbering for content sections.

Text: Stone (#8d8d8f) at 16px Instrument Sans, with a 1px Stone (#8d8d8f) bottom border, followed by Ink (#4d4942) body text.

## Do's and Don'ts

### Do
- Prioritize Canvas (#ffffff) and Fog (#f3f3f2) for backgrounds to maintain an expansive, light aesthetic.
- Use Instrument Serif for all primary headlines (32px, 52px, 74px) to convey elegance, ensuring a lineHeight of 1.0 at display sizes.
- Use Instrument Sans for all body text, button labels, and secondary UI elements at 15px or 16px.
- Apply 0px border-radius to all components, including buttons and cards, for a sharp, architectural feel.
- Use 24px padding consistently within card-like components and buttons for comfortable content spacing.
- Implement Ink (#1a1a1e) as the primary text color and critical border color for high contrast and definition.
- Utilize 96px for vertical spacing between major sections, creating clear hierarchical separation.

### Don't
- Avoid using saturated background colors; all surfaces should remain within the neutral palette.
- Do not add drop shadows or significant elevations to elements; maintain a flat, layered aesthetic.
- Do not use letter-spacing adjustments for body text or headlines; the default 'normal' tracking is a signature choice.
- Do not introduce rounded corners; strict 0px radius is fundamental to the system's sharp visual identity.
- Avoid decorative gradients; rely on subtle color shifts within the neutral palette for visual interest.
- Do not use strong outlines or heavy borders for interactive elements; subtle borders and background changes suffice.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Primary page background, most content surfaces. |
| 1 | Fog | `#f3f3f2` | Secondary background for distinct sections or very subtle elevated elements. |
| 2 | Ash | `#e7e6e4` | Background for tertiary panels, or interactive elements in their default state. |
| 3 | Stone | `#d1d1d2` | Background for specific informative elements or tags, providing minimum elevation. |

## Imagery

This design system primarily uses high-quality photography of meticulously styled interior spaces. Images are often full-bleed or large-scale, acting as significant visual anchors. Treatment is naturalistic, featuring well-lit, candid-style shots that convey a sense of lived-in elegance and calm. There's a minimal use of non-photographic graphics; icons are monochromatic, thin-stroked, and serve purely functional roles, appearing sparingly as small punctuations within the UI. Imagery plays a dual role: setting an atmospheric tone and showcasing the results of the brand's interior design work, often balanced with expansive white space to draw focus.

## Layout

The page employs a max-width contained layout with content primarily centered, although the hero section appears full-bleed. The hero features a large, split text-left/image-right composition, with the headline centered over the imagery. Vertical rhythm is established through generous and consistent section gaps of 96px, with content blocks often appearing as clean, well-defined areas. Feature sections frequently arrange content in alternating text and image patterns or in structured card grids. Navigation is a minimal top bar, with elements subtly outlined or ghosted against the light background. The overall density is spacious, favoring breathing room over packed information.

## Agent Prompt Guide

Quick Color Reference:
text: #1a1a1e
background: #ffffff
border: #f3f3f2
accent: #9a682c
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: full-bleed image with a centered headline 'Transformamos espacios, conectamos emociones' using Instrument Serif 74px, lineHeight 1.0, #ffffff. Below the headline, include a button 'Agendar consulta' using Canvas (#ffffff) background, Ink (#1a1a1e) text, 1px Fog (#f3f3f2) border, and 24px padding on all sides, 0px radius.
2. Create an article card: 24px padding on all sides, 1px Fog (#f3f3f2) border, 0px radius. Inside, place '16.07.2025 Oficinas con propósito: cómo crear un entorno que potencie la creati...' using Instrument Sans 16px #1a1a1e, followed by a 'Diseño Oficinas' tag using Stone (#d1d1d2) background, Ink (#1a1a1e) text, 0px top/bottom padding, 24px left/right padding, 0px radius.
3. Create a numbered content section: Start with '01' using 16px Instrument Sans, #8d8d8f, with a 1px #8d8d8f bottom border. Below it, place the descriptive text 'Proyectos llave en mano para transformar tu espacio.' using 16px Instrument Sans, #4d4942.

## Similar Brands

- **Farrow & Ball** — Shared emphasis on a refined, muted color palette and classic typography for an elegant, timeless feel.
- **The Future Kept** — Clean, spacious layouts with prominent product photography and minimalist components reinforce a sophisticated, curated aesthetic.
- **Archiweb** — Use of large-scale photography as background elements and a strong focus on typography to convey architectural and design principles.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #1a1a1e;
  --color-canvas: #ffffff;
  --color-fog: #f3f3f2;
  --color-ash: #e7e6e4;
  --color-stone: #d1d1d2;
  --color-flint: #c1c2bd;
  --color-charcoal: #4d4942;
  --color-bronze-accent: #9a682c;
  --color-slate-accent: #4a626f;

  /* Typography — Font Families */
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 52px;
  --leading-heading: 1.1;
  --text-display: 74px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-96: 96px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-none: 0px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-fog: #f3f3f2;
  --surface-ash: #e7e6e4;
  --surface-stone: #d1d1d2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #1a1a1e;
  --color-canvas: #ffffff;
  --color-fog: #f3f3f2;
  --color-ash: #e7e6e4;
  --color-stone: #d1d1d2;
  --color-flint: #c1c2bd;
  --color-charcoal: #4d4942;
  --color-bronze-accent: #9a682c;
  --color-slate-accent: #4a626f;

  /* Typography */
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 15px;
  --leading-caption: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 52px;
  --leading-heading: 1.1;
  --text-display: 74px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-96: 96px;
  --spacing-240: 240px;
}
```
