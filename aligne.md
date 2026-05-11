# ALIGNE — Style Reference
> monochrome canvas, sharp serif

**Theme:** light

ALIGNE embodies a chic, high-contrast aesthetic with a strong emphasis on sharp typography and monochromatic styling. Most interactive elements are outlined or subtle, drawing attention to content imagery while maintaining a refined, understated presentation. Black and white form the core, with a singular vivid blue for functional accents, creating a precise, modern feel for an online fashion brand.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#24170f` | `--color-midnight-ink` | Primary text, dark surface background, subtle borders, focused input fields — a deep, almost black brown that provides strong contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default text on dark elements |
| Charcoal | `#151515` | `--color-charcoal` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Deep Space | `#000000` | `--color-deep-space` | Icon fills, specific list backgrounds, high-contrast states |
| Ash Gray | `#e2e2e2` | `--color-ash-gray` | Hairline borders, subtle dividers, form field outlines |
| Cobalt Accent | `#0073ff` | `--color-cobalt-accent` | Blue accent for outlined action borders, linked labels, and lightweight interactive emphasis. |

## Tokens — Typography

### GT America Mono — Primary body text, navigation links, product details, small labels, and all functional interface text. Its monospaced nature delivers a precise, technical feel, contrasting with traditional fashion typography. · `--font-gt-america-mono`
- **Substitute:** Space Mono, Fira Code
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 24px
- **Line height:** 0.80, 1.00, 1.07, 1.20, 1.28, 1.40, 1.50, 1.60, 1.70
- **Letter spacing:** -0.0620em, 0.0100em, 0.0110em, 0.0630em, 0.0670em, 0.0710em, 0.0930em, 0.1000em, 0.1330em
- **OpenType features:** `"kern"`
- **Role:** Primary body text, navigation links, product details, small labels, and all functional interface text. Its monospaced nature delivers a precise, technical feel, contrasting with traditional fashion typography.

### nimbus-sans-extended — Prominent headings and display text, creating impact through its expanded width and tighter tracking. Its strong uppercase presence provides a bold, editorial statement. · `--font-nimbus-sans-extended`
- **Substitute:** Oswald, Alternate Gothic No1 D
- **Weights:** 400, 700
- **Sizes:** 10px, 15px, 24px, 25px, 40px, 60px
- **Line height:** 0.70, 0.97, 1.00, 1.07, 1.13, 1.20
- **Letter spacing:** 0.0480em, 0.0500em, 0.0800em, 0.1000em, 0.1330em, 0.1500em
- **OpenType features:** `"kern"`
- **Role:** Prominent headings and display text, creating impact through its expanded width and tighter tracking. Its strong uppercase presence provides a bold, editorial statement.

### GTAmericaMonoRegular — Used for specific body text and button labels. It offers a slightly different text texture compared to `GT America Mono` (possibly a fallback or specific variant), maintaining a consistent brand voice. · `--font-gtamericamonoregular`
- **Substitute:** Space Mono, Fira Code
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 14px, 16px
- **Line height:** 1.00, 1.20, 1.50, 1.68
- **Letter spacing:** normal
- **OpenType features:** `"kern"`
- **Role:** Used for specific body text and button labels. It offers a slightly different text texture compared to `GT America Mono` (possibly a fallback or specific variant), maintaining a consistent brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.1px | `--text-caption` |
| heading | 24px | 1.2 | 0.08px | `--text-heading` |
| heading-lg | 40px | 1.13 | 0.1px | `--text-heading-lg` |
| display | 60px | 0.7 | 0.05px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |
| listItems | 3px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.15) 0px 2px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Filled Primary Button (Product)
**Role:** Primary action within a product context, such as 'Add to cart' overlay actions.

Background: Canvas White (#ffffff), Text: Midnight Ink (#24170f), Border: 1px Midnight Ink (#24170f). Radius: 0px. Padding: 4px. Shadow: none.

### Ghost Outline Button (Hero)
**Role:** Call to action within hero sections, such as 'Discover the Collection'.

Background: transparent, Text: Canvas White (#ffffff), Border: 1px transparent, with specific hover color Cobalt Accent (#0073ff). Radius: 0px. Padding: 5px.

### Ghost Outline Button (General)
**Role:** General call to action, active states for filters or menus, like 'View All'.

Background: transparent, Text: Midnight Ink (#24170f), Border: 1px Midnight Ink (#24170f). Radius: 0px. Padding: 16px.

### Ghost Outline Button (Dark Context)
**Role:** Call to action on dark background areas, like signup invitations.

Background: transparent rgba(36, 23, 15, 0.15), Text: Canvas White (#ffffff), Border: 1px Canvas White (#ffffff). Radius: 0px. Padding: 7px 30px.

### Product Card
**Role:** Displaying product items in grids.

Background: transparent, no border or shadow. Radius: 0px. Padding: 0px.

### Text Input
**Role:** Standard form input fields.

Background: transparent, Text color: Midnight Ink (#24170f), Border: 1px Midnight Ink (#24170f). Radius: 0px. No padding.

### Informational Badge
**Role:** Small text labels for status or new arrivals.

Background: transparent, Text: Cobalt Accent (#0073ff). Radius: 0px. No padding. Border: 1px Cobalt Accent (#0073ff) on hover.

## Do's and Don'ts

### Do
- Prioritize a high-contrast palette using Midnight Ink (#24170f) for text and Canvas White (#ffffff) for backgrounds.
- Use GT America Mono for all functional text and body content to maintain a precise, technical feel.
- Employ nimbus-sans-extended uppercase for all primary headings, with tight letter-spacing for visual impact.
- Maintain sharp, 0px border radii for all primary UI elements, contributing to the modern, clean aesthetic.
- Apply Midnight Ink (#24170f) as a subtle 1px border for ghost buttons and input fields for understated interaction.
- Reserve Cobalt Accent (#0073ff) for semantic 'New in' badges and subtle interactive highlights, never for large areas.
- Ensure generous vertical spacing between sections (at least 30px) and a comfortable 20px for internal card padding and element gaps.

### Don't
- Avoid using soft shadows or rounded corners on primary interactive elements; leverage hard edges for a contemporary feel.
- Do not introduce additional vibrant colors beyond Cobalt Accent (#0073ff); stick to the monochromatic base.
- Refrain from heavy, filled buttons as primary actions unless for specific overlaid product interactions.
- Do not vary font families beyond GT America Mono, nimbus-sans-extended, and GTAmericaMonoRegular; these define the brand's typographic voice.
- Avoid decorative gradients or excessive graphic elements; let the imagery and typography lead the design.
- Do not use generic system fonts; stick to the specified custom typefaces for brand consistency.
- Do not use letter-spacing: normal for large headings; apply precise tracking from the design system for distinctiveness.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Dominant page background, providing a clean, bright foundation. |
| 2 | Card Surface | `#ffffff` | Product card backgrounds; visually indistinguishable from the canvas, promoting a seamless flow. |
| 3 | Elevated Details | `#f7f7f7` | Subtle background for UI elements like announcement bars or specific interactive states (hinted by --bg-body-darken). |

## Imagery

This site features high-quality fashion photography, often product-focused or lifestyle shots with models, showcasing clothing items. Images are typically full-bleed in hero sections or contained in grids with raw, uncropped edges and 0px radii. The treatment is often moody in hero sections, transitioning to brighter, well-lit shots for product displays. Imagery plays a dual role: setting an atmospheric mood in heroes and providing explanatory visual content for product listings. The density is image-heavy in sections like new arrivals, allowing visuals to dominate over text. Icons are minimal, outlined, and monochromatic, with a fine stroke weight.

## Layout

The page primarily uses a full-bleed layout for hero sections, filling the viewport with striking photography. Content sections below often embrace a contained max-width model (though a specific max-width isn't strictly defined, sections like 'New Arrivals' appear visually centered within a boundary). The hero is typically a central headline over a background image. Section rhythm is often clean and distinct, with clear vertical spacing, often presenting alternating text-left/image-right or image-left/text-right arrangements for editorial blocks. Product displays utilize consistent 3-column card grids. Navigation is a minimal top bar with discreet text links and icons, often sticky.

## Agent Prompt Guide

Quick Color Reference:
text: #24170f
background: #ffffff
border: #e2e2e2
accent: #0073ff
primary action: #24170f (filled action)

Example Component Prompts:
1. Create a Hero Section: full-bleed background image, overlay with 'SUMMER IN THE CITY' in nimbus-sans-extended weight 700, 60px, #ffffff, letter-spacing 0.05em. Below it, a Ghost Outline Button (Hero) for 'DISCOVER THE COLLECTION' with text #ffffff, transparent background, 5px padding, 0px border-radius, and no border until hover (when it becomes Cobalt Accent #0073ff).
2. Create a Product Grid Section: 'New Arrivals' heading in nimbus-sans-extended weight 700, 40px, #24170f, letter-spacing 0.1em. Body text beneath in GT America Mono weight 400, 14px, #24170f. Followed by a Ghost Outline Button (General) for 'View All' with text #24170f, transparent background, 16px padding, 1px #24170f border, 0px border-radius.
3. Create a Product Card: transparent background, 0px border-radius, 0px padding. Product title in GT America Mono weight 400, 12px, #24170f. Price inGT America Mono weight 400, 12px, #24170f. Add an Informational Badge 'New in' using text #0073ff, transparent background, 0px corner radius, and 0px padding above the product name.

## Similar Brands

- **Acne Studios** — Shares a sophisticated, high-contrast, minimalist aesthetic with crisp typography and understated color palettes.
- **COS (Collection of Style)** — Features a similar focus on clean lines, monochromatic visuals, and premium photography in an e-commerce context.
- **Theory** — Employs an editorial style with strong typographic statements and a refined, uncluttered visual language for fashion.
- **& Other Stories** — Exhibits a contemporary fashion brand approach with a focus on editorial imagery and a clean, spacious UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #24170f;
  --color-canvas-white: #ffffff;
  --color-charcoal: #151515;
  --color-deep-space: #000000;
  --color-ash-gray: #e2e2e2;
  --color-cobalt-accent: #0073ff;

  /* Typography — Font Families */
  --font-gt-america-mono: 'GT America Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-nimbus-sans-extended: 'nimbus-sans-extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtamericamonoregular: 'GTAmericaMonoRegular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.08px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: 0.1px;
  --text-display: 60px;
  --leading-display: 0.7;
  --tracking-display: 0.05px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Named Radii */
  --radius-default: 0px;
  --radius-listitems: 3px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 2px 10px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-card-surface: #ffffff;
  --surface-elevated-details: #f7f7f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #24170f;
  --color-canvas-white: #ffffff;
  --color-charcoal: #151515;
  --color-deep-space: #000000;
  --color-ash-gray: #e2e2e2;
  --color-cobalt-accent: #0073ff;

  /* Typography */
  --font-gt-america-mono: 'GT America Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-nimbus-sans-extended: 'nimbus-sans-extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtamericamonoregular: 'GTAmericaMonoRegular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.08px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: 0.1px;
  --text-display: 60px;
  --leading-display: 0.7;
  --tracking-display: 0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 2px 10px 0px;
}
```
