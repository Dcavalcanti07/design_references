# Adaline — Style Reference
> Mist-shrouded valley

**Theme:** light

Adaline employs a serene, naturally-inspired aesthetic, combining a nearly monochromatic palette with organic, muted greens and browns. The visual language conveys quiet authority: elegant typography with subtle letter spacing, carefully rounded components, and restrained use of color only for functional elements. Grays are abundant, creating a soft, layered depth, while a single striking green serves as the primary accent, signaling interactive states and brand identity. Components feel integrated with their environment, avoiding harsh contrasts or strong shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#fbfdf6` | `--color-canvas-ice` | Page backgrounds, elevated surface backgrounds, neutral button fills, focus rings |
| Adaline Ink | `#0a1d08` | `--color-adaline-ink` | Primary text, heading text, strong borders, brand accents, button text on light backgrounds |
| Mist Gray | `#c5ccb6` | `--color-mist-gray` | Subtle borders, secondary text, muted backgrounds for layered surfaces, list item delimiters |
| Deep Earth | `#31200b` | `--color-deep-earth` | Decorative fills and strokes in illustrations, occasional subtle text on light backgrounds |
| Valley Green | `#203b14` | `--color-valley-green` | Brand accent for active states, link hover states, icon fills, and ghost button text/borders |
| Stone Moss | `#e0e5d5` | `--color-stone-moss` | Secondary button borders, subtle separator lines, card dividers |
| Amber Seed | `#4a3212` | `--color-amber-seed` | Primary action button background – a warm, muted brown that grounds interactive elements |
| Forest Dew | `#d7e8b5` | `--color-forest-dew` | Light background fill for subtle elements or active navigation items |
| Blackest Night | `#000000` | `--color-blackest-night` | Rare strong contrast element, graphic fills for brand logos |

## Tokens — Typography

### akkurat — Primary brand typeface for all headings, body text, and UI elements. Its slightly condensed and precise forms define the system's clarity. The consistent subtle negative letter spacing across sizes provides legibility while maintaining a focused visual presence. · `--font-akkurat`
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 18px, 47px, 53px
- **Line height:** 0.98, 1.00, 1.33, 1.43, 1.44, 1.67
- **Letter spacing:** -0.0400em
- **OpenType features:** `"calt", "kern"`
- **Role:** Primary brand typeface for all headings, body text, and UI elements. Its slightly condensed and precise forms define the system's clarity. The consistent subtle negative letter spacing across sizes provides legibility while maintaining a focused visual presence.

### fragmentMono — Monospaced typeface used for small, functional UI elements like labels or metadata, providing a clear, technical counterpoint to the primary typeface without being overly dominant due to its fixed size and positive letter spacing. · `--font-fragmentmono`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00
- **Letter spacing:** 0.0200em
- **OpenType features:** `"calt", "kern"`
- **Role:** Monospaced typeface used for small, functional UI elements like labels or metadata, providing a clear, technical counterpoint to the primary typeface without being overly dominant due to its fixed size and positive letter spacing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 18px | 1.43 | — | `--text-body` |
| body-lg | 47px | 1.3 | — | `--text-body-lg` |
| heading-sm | 53px | 1.3 | — | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| images | 8px |
| buttons | 20px |
| navItems | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(99, 143, 61, 0.1) 0px 0px 0px 1px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 4px

## Components

### Primary Action Button (Filled)
**Role:** Emphasized calls to action

Filled with Amber Seed (#4a3212), text in Canvas Ice (#fbfdf6), 20px border-radius, 24px horizontal padding.

### Secondary Action Button (Ghost)
**Role:** Secondary calls to action, less emphasis

Ghost button with Canvas Ice (#fbfdf6) background, Adaline Ink (#0a1d08) text and 1px border. 20px border-radius, 24px horizontal padding. Hover state shifts to Valley Green text and border.

### Tertiary Action Button (Ghost Thin)
**Role:** Minimal calls to action, often in navigation

Ghost button with Canvas Ice (#fbfdf6) background, muted Valley Green (#203b14) text and 1px Stone Moss (#e0e5d5) border. 20px border-radius, 24px horizontal padding.

### Navigation Link
**Role:** Top-level navigation and contextual links

Adaline Ink (#0a1d08) text, akkuraat 400 at 14px, typically 24px horizontal padding and 16px vertical spacing from siblings. Active states may use Forest Dew (#d7e8b5) background or Valley Green text.

### Client Logo Card
**Role:** Display partner logos

Contained within a subtle border of Mist Gray (#c5ccb6), with a Canvas Ice (#fbfdf6) background. Logos are often Blackest Night (#000000) for contrast. 8px border-radius.

## Do's and Don'ts

### Do
- Prioritize Canvas Ice (#fbfdf6) for all primary backgrounds to maintain the light, airy feel.
- Use Adaline Ink (#0a1d08) for primary headings and body text, ensuring a consistent dark, earthy tone.
- Apply Akkurat with a consistent -0.0400em letter spacing for all headings and body text to maintain signature visual precision.
- Employ 20px border-radius for all interactive elements like buttons and navigation items for a softer, approachable feel.
- Reserve Amber Seed (#4a3212) exclusively for the background of primary calls to action to ensure clear visual hierarchy.
- Maintain a clear vertical rhythm using 48px sectional gaps and 24px inner padding for cards.
- Use Valley Green (#203b14) as the primary accent for interactive states, icons, and subtle brand highlights.

### Don't
- Do not use highly saturated or vivid colors outside of designated brand accent areas; the system relies on a muted, natural palette.
- Avoid harsh shadows or strong elevation; the design favors flat, layered surfaces with minimal depth indicators.
- Do not introduce new typefaces; Akkurat and fragmentMono are the only approved fonts.
- Do not use generic square or minimal border radii for buttons or navigation items; always apply 20px for consistency.
- Avoid dense packing of elements; maintain comfortable element gaps (e.g., 4px) and page-level spacing.
- Do not use light text on light backgrounds for interactive elements; ensure sufficient contrast, particularly against Canvas Ice.
- Do not deviate from the established color roles; for instance, only Amber Seed should be a solid button background.

## Imagery

The site predominantly uses abstract, digital-nature illustrations. These feature rendered landscapes reminiscent of real-world photography but with a stylized, digital art aesthetic, such as misty mountains and serene lakes. Imagery serves a decorative and atmospheric role, often as full-bleed backgrounds for hero sections, creating a calm and contemplative mood. There are also product UI screenshots, which appear as contained elements, likely with slight rounding and minimal borders. Icons are minimal, monochromatic, and outlined, maintaining a clean and functional appearance. The overall impression is one of visual spaciousness and low density, letting the abstract visuals set the tone.

## Agent Prompt Guide

Quick Color Reference:
text: #0a1d08
background: #fbfdf6
border: #e0e5d5
accent: #203b14
primary action: #4a3212 (filled action)

Example Component Prompts:
Create a Primary Action Button: #4a3212 background, #fbfdf6 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: use Canvas Ice (#fbfdf6) background and Mist Gray (#c5ccb6) 1px border with 8px radius. Inside, use Akkurat 18px weight 400 for a title, Adaline Ink (#0a1d08). Include a body text paragraph in Akkurat 14px weight 400, Adaline Ink (#0a1d08) with 16px top margin. Apply 24px padding inside the card.

Create a navigation bar: use Canvas Ice (#fbfdf6) background. Left-aligned links 'Products', 'Pricing', 'Blog' in Akkurat 14px weight 400, Adaline Ink (#0a1d08), with 16px elementGap. Right-aligned ghost button 'Watch Demo' with Canvas Ice (#fbfdf6) background, Valley Green (#203b14) text, 1px Stone Moss (#e0e5d5) border, 20px radius, 24px horizontal padding. Next to it, a filled button 'Start for free' with Amber Seed (#4a3212) background, Canvas Ice (#fbfdf6) text, 20px radius, 24px horizontal padding. Ensure all elements have appropriate vertical alignment and 24px horizontal padding within the nav bar. 

## Similar Brands

- **Anthropic AI** — Shares a similar muted, almost monochromatic palette with a single earthy accent color and understated typography.
- **Linear** — Employs precise typography, clean, often border-defined components, and subtle color accents against a neutral canvas to convey professionalism and efficiency.
- **Aether AI** — Features abstract, nature-inspired or digitally rendered backgrounds for hero sections, combined with a focus on UI clarity.
- **Vercel** — Utilizes a clean, often light-themed interface with minimal shadows, precise spacing, and carefully chosen accent colors to highlight interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #fbfdf6;
  --color-adaline-ink: #0a1d08;
  --color-mist-gray: #c5ccb6;
  --color-deep-earth: #31200b;
  --color-valley-green: #203b14;
  --color-stone-moss: #e0e5d5;
  --color-amber-seed: #4a3212;
  --color-forest-dew: #d7e8b5;
  --color-blackest-night: #000000;

  /* Typography — Font Families */
  --font-akkurat: 'akkurat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragmentmono: 'fragmentMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 18px;
  --leading-body: 1.43;
  --text-body-lg: 47px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 53px;
  --leading-heading-sm: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-images: 8px;
  --radius-buttons: 20px;
  --radius-navitems: 20px;

  /* Shadows */
  --shadow-subtle: rgba(99, 143, 61, 0.1) 0px 0px 0px 1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #fbfdf6;
  --color-adaline-ink: #0a1d08;
  --color-mist-gray: #c5ccb6;
  --color-deep-earth: #31200b;
  --color-valley-green: #203b14;
  --color-stone-moss: #e0e5d5;
  --color-amber-seed: #4a3212;
  --color-forest-dew: #d7e8b5;
  --color-blackest-night: #000000;

  /* Typography */
  --font-akkurat: 'akkurat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragmentmono: 'fragmentMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 18px;
  --leading-body: 1.43;
  --text-body-lg: 47px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 53px;
  --leading-heading-sm: 1.3;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;

  /* Shadows */
  --shadow-subtle: rgba(99, 143, 61, 0.1) 0px 0px 0px 1px;
}
```
