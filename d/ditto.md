# Ditto — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Ditto uses an 'architectural blueprint on white marble' visual language, combining a refined, nearly monochromatic canvas with precise geometric typography and a vibrant, playful accent color for highlights and interactive elements. Surfaces are clean and untextured, serving as a bright foundation for highly legible black text. Strategic splashes of saturated color are used for emphasis, badges, or outlined elements, creating an energetic yet organized feel. Components are lightweight and often feature large border-radii, giving a soft, approachable edge to the otherwise crisp design.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, deep backgrounds for contrast, primary filled buttons, strong borders for UI elements |
| Canvas White | `#f7f5f3` | `--color-canvas-white` | Dominant page background, card surfaces, ghost button text |
| Graphite | `#6a6559` | `--color-graphite` | Muted text, secondary navigation, subtle button borders and iconography |
| Warm Gray | `#e2e2e2` | `--color-warm-gray` | Subtle dividers, borders, and light interaction states |
| Pure White | `#ffffff` | `--color-pure-white` | Text on dark backgrounds, badges, and internal accents |
| Harvest Gold | `#ffdd33` | `--color-harvest-gold` | Accent for highlighted content, badges, and occasional backgrounds |
| Power Red | `#ff6137` | `--color-power-red` | Striking accents, outlines, and decorative elements to draw attention |
| Royal Blue | `#0097e6` | `--color-royal-blue` | Accent for links, outlines, and decorative elements |
| Fresh Green | `#3e6b15` | `--color-fresh-green` | Success states, badges, and outlined elements for positive reinforcement |
| Rich Violet | `#b26dc2` | `--color-rich-violet` | Decorative highlights and abstract graphic accents |
| Mustard Seed | `#bbb809` | `--color-mustard-seed` | Decorative outlines and highlights |
| Blush Pink | `#f5c4cc` | `--color-blush-pink` | Decorative outlines and highlights |
| Electric Blue | `#1345eb` | `--color-electric-blue` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### ABC Social — Primary typeface for most UI elements including body text, links, buttons, and smaller headings. The light weights (300, 400) maintain an airy, modern feel, while the generous letter-spacing for smaller text ensures readability. · `--font-abc-social`
- **Substitute:** Inter
- **Weights:** 300, 400, 700
- **Sizes:** 13px, 16px, 18px, 25px, 26px, 35px, 72px, 108px
- **Line height:** 0.89, 1.00, 1.05, 1.10, 1.20, 1.43
- **Letter spacing:** -0.0400em at 108px, -0.0200em at 72px, -0.0140em at 35px, -0.0120em at 26px, -0.0110em at 25px, -0.0100em at 18px, 0.0080em at 16px, 0.0100em at 13px
- **OpenType features:** `'ss07'`
- **Role:** Primary typeface for most UI elements including body text, links, buttons, and smaller headings. The light weights (300, 400) maintain an airy, modern feel, while the generous letter-spacing for smaller text ensures readability.

### ABC Social Extended — Reserved for large, impactful headlines, where its extended proportions demand attention. Its tight letter-spacing at larger sizes contributes to a bold, confident statement, often appearing as fragmented highlights. · `--font-abc-social-extended`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 16px, 18px, 24px, 36px, 40px, 43px, 86px
- **Line height:** 0.88, 1.00, 1.05, 2.63
- **Letter spacing:** -0.0230em at 86px, -0.0220em at 43px, -0.0100em at 36px, 0.0200em at 16px
- **OpenType features:** `'ss07'`
- **Role:** Reserved for large, impactful headlines, where its extended proportions demand attention. Its tight letter-spacing at larger sizes contributes to a bold, confident statement, often appearing as fragmented highlights.

### ABC Social Condensed — Used sparingly for very specific, emphasized text such as badges or callouts. Its heavy weight and condensed form provide strong visual punch and contrast against the lighter primary typeface. · `--font-abc-social-condensed`
- **Substitute:** Inter Condensed
- **Weights:** 900
- **Sizes:** 35px
- **Line height:** 1.20
- **Letter spacing:** -0.0100em
- **OpenType features:** `'ss07'`
- **Role:** Used sparingly for very specific, emphasized text such as badges or callouts. Its heavy weight and condensed form provide strong visual punch and contrast against the lighter primary typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.43 | 0.01px | `--text-caption` |
| body-sm | 16px | 1.43 | 0.008px | `--text-body-sm` |
| body | 18px | 1.43 | -0.01px | `--text-body` |
| subheading | 25px | 1.2 | -0.011px | `--text-subheading` |
| heading | 35px | 1.2 | -0.014px | `--text-heading` |
| heading-lg | 43px | 1.05 | -0.022px | `--text-heading-lg` |
| display-sm | 72px | 1 | -0.02px | `--text-display-sm` |
| display | 86px | 0.88 | -0.023px | `--text-display` |
| display-lg | 108px | 0.89 | -0.04px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 192 | 192px | `--spacing-192` |
| 196 | 196px | `--spacing-196` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 1000px |
| images | 12px |
| inputs | 28px |
| buttons | 100px |

### Layout

- **Section gap:** 60px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Main call to action button.

Solid Midnight Ink (#000000) background with Pure White (#ffffff) text. Features a full pill shape with 1000px border-radius, 15px vertical and horizontal padding, using ABC Social Regular at 16px.

### Ghost Outline Button
**Role:** Secondary call to action, less prominent than primary.

Transparent background with Graphite (#6a6559) text and a matching 1px border. Pill-shaped with 100px border-radius, 8px vertical and 10px horizontal padding, using ABC Social Regular at 16px.

### Ghost Border Button (Pill)
**Role:** Tertiary action or navigational elements requiring minimal visual weight.

Transparent background with Graphite (#6a6559) text and a matching 1px border. Full pill shape with 1000px border-radius, 15px vertical and horizontal padding, using ABC Social Regular at 16px.

### Badge with Background
**Role:** Highlighting status or keyword.

Harvest Gold (#ffdd33) background with Midnight Ink (#000000) text. No border-radius or padding observed directly as a consistent component style, appearing as an inline visual highlight.

### Success Status Badge
**Role:** Indicating a positive status.

Fresh Green (#3e6b15) background with Pure White (#ffffff) text. No border-radius, 6px vertical and 10px horizontal padding, using ABC Social Regular.

### Circular Card Highlight
**Role:** Decorative element or visual accent.

Harvest Gold (#ffdd33) background with a 1000px border-radius, appearing as a large circular shape with no discernible padding, creating a cut-out or background effect rather than a contained card.

### Text Input Field
**Role:** User input for forms.

Pure White (#ffffff) background with Midnight Ink (#000000) text. Border is 1px Midnight Ink (#000000). Features a generous 28px border-radius, 0px vertical and 20px horizontal padding.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and important headings to ensure high legibility against the light canvas.
- Apply Canvas White (#f7f5f3) as the default background for all page sections and elevated surfaces.
- Utilize 1000px border-radius for all primary buttons and large decorative elements to create a soft, pill-shaped aesthetic.
- Employ Harvest Gold (#ffdd33) and Power Red (#ff6137) strategically and sparingly for emphasis, such as badges, outlined boxes, or text highlights, never as primary UI colors.
- Maintain a clear visual hierarchy using ABC Social for body text (16-18px), ABC Social Extended for major headlines (43-86px), and ABC Social Condensed for specific emphasized text like badges.
- Structure content with a consistent 20px element gap and 60px section gap for a comfortable, organized layout.
- Use ABC Social weights 300 and 400 for most text, reserving 700 for strong emphasis within body copy or bold components.

### Don't
- Avoid using multiple accent colors in close proximity; stick to one or two per view to maintain visual clarity.
- Do not introduce heavy shadows or gradients on surfaces; components should remain flat and minimal.
- Never use the accent colors for full background sections, as they are intended for highlights, not foundational colors.
- Avoid using default system fonts. Always use ABC Social variants or their specified substitutes.
- Do not deviate from the established border radii; maintain 1000px for pills, 100px for secondary buttons, and 28px for inputs.
- Resist adding additional padding or margins that break the 4px grid and established spacing tokens.
- Do not use dark backgrounds for large content areas; the system is designed for a light theme with dark text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#f7f5f3` | Dominant page background. |
| 1 | Pure White | `#ffffff` | Background for elevated elements like certain inputs or overlay content. |
| 2 | Harvest Gold | `#ffdd33` | Background for specific highlighted cards or decorative elements. |

## Imagery

This site prominently features highly stylized, abstract graphic elements and product screenshots. The graphics are often playful and dimensional, using the accent color palette to create visual interest rather than realistic representations. Overlapping, torn-paper, or distressed effects are common for accent shapes, giving a handcrafted feel. Product screenshots are clean, high-fidelity, and typically contained within a well-defined UI, focusing on clarity over extensive context. Icons are simple, outlined, and monochromatic, used for navigation or feature delineation, prioritizing function without visual distraction.

## Layout

The page primarily uses a max-width contained layout, with content segments often centered or adopting clean two-column text-left/image-right (or vice-versa) arrangements. The hero section establishes a clear centered headline over a subtle background. Sections alternate between a base Canvas White and occasional Harvest Gold backgrounds for emphasis, creating a clear visual rhythm. Vertical spacing between sections is generous, contributing to a comfortable density. Navigation is a sticky top bar with clearly defined links and primary/secondary call-to-action buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f7f5f3
border: #6a6559
accent: #ffdd33
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #000000 background, #f7f5f3 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a ghost outline button for secondary action: Transparent background, Graphite (#6a6559) text, 1px Graphite (#6a6559) border, 100px border-radius, 8px vertical and 10px horizontal padding, ABC Social regular 16px text.
3. Create a success badge: Fresh Green (#3e6b15) background, Pure White (#ffffff) text, no border-radius, 6px vertical and 10px horizontal padding, ABC Social regular 16px text.
4. Create a text input field: Pure White (#ffffff) background, Midnight Ink (#000000) text, 1px Midnight Ink (#000000) border, 28px border-radius, 0px vertical and 20px horizontal padding, ABC Social regular 16px placeholder text.

## Similar Brands

- **Figma** — Dominant white canvas with dark, highly legible text and a few strong accent colors for UI elements.
- **Linear** — Minimalist, high-contrast typography, focus on structured UIs on light backgrounds, and precise spacing.
- **Notion** — Clean, neutral canvas, emphasis on readability, with a subtle use of color for functional highlights.
- **Webflow** — Bold geometric typography for headlines, spacious layouts, and a blend of achromatic and vibrant accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #f7f5f3;
  --color-graphite: #6a6559;
  --color-warm-gray: #e2e2e2;
  --color-pure-white: #ffffff;
  --color-harvest-gold: #ffdd33;
  --color-power-red: #ff6137;
  --color-royal-blue: #0097e6;
  --color-fresh-green: #3e6b15;
  --color-rich-violet: #b26dc2;
  --color-mustard-seed: #bbb809;
  --color-blush-pink: #f5c4cc;
  --color-electric-blue: #1345eb;

  /* Typography — Font Families */
  --font-abc-social: 'ABC Social', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-social-extended: 'ABC Social Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-social-condensed: 'ABC Social Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.43;
  --tracking-caption: 0.01px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.008px;
  --text-body: 18px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-subheading: 25px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.011px;
  --text-heading: 35px;
  --leading-heading: 1.2;
  --tracking-heading: -0.014px;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.022px;
  --text-display-sm: 72px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.02px;
  --text-display: 86px;
  --leading-display: 0.88;
  --tracking-display: -0.023px;
  --text-display-lg: 108px;
  --leading-display-lg: 0.89;
  --tracking-display-lg: -0.04px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-192: 192px;
  --spacing-196: 196px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 28px;
  --radius-full: 100px;
  --radius-full-2: 1000px;

  /* Named Radii */
  --radius-cards: 1000px;
  --radius-images: 12px;
  --radius-inputs: 28px;
  --radius-buttons: 100px;

  /* Surfaces */
  --surface-canvas-white: #f7f5f3;
  --surface-pure-white: #ffffff;
  --surface-harvest-gold: #ffdd33;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #f7f5f3;
  --color-graphite: #6a6559;
  --color-warm-gray: #e2e2e2;
  --color-pure-white: #ffffff;
  --color-harvest-gold: #ffdd33;
  --color-power-red: #ff6137;
  --color-royal-blue: #0097e6;
  --color-fresh-green: #3e6b15;
  --color-rich-violet: #b26dc2;
  --color-mustard-seed: #bbb809;
  --color-blush-pink: #f5c4cc;
  --color-electric-blue: #1345eb;

  /* Typography */
  --font-abc-social: 'ABC Social', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-social-extended: 'ABC Social Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-social-condensed: 'ABC Social Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.43;
  --tracking-caption: 0.01px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.008px;
  --text-body: 18px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-subheading: 25px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.011px;
  --text-heading: 35px;
  --leading-heading: 1.2;
  --tracking-heading: -0.014px;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.022px;
  --text-display-sm: 72px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.02px;
  --text-display: 86px;
  --leading-display: 0.88;
  --tracking-display: -0.023px;
  --text-display-lg: 108px;
  --leading-display-lg: 0.89;
  --tracking-display-lg: -0.04px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-192: 192px;
  --spacing-196: 196px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 28px;
  --radius-full: 100px;
  --radius-full-2: 1000px;
}
```
