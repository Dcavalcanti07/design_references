# Grammarly — Style Reference
> Crisp digital parchment

**Theme:** light

Grammarly presents a grounded, text-first experience centered on clarity and understated precision. Its defining visual characteristic is the near-achromatic palette, almost entirely grays and whites, which creates a quiet background for the functionality. The single strong 'Teal Verdant' accent is reserved almost exclusively for calls to action, generating a strong visual cue without overwhelming the interface. Subtle textural depth is hinted at through the interaction of dark grays and crisp whites, rather than overt shadows or complex color schemes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell Deep | `#0e101a` | `--color-inkwell-deep` | Primary text, deep backgrounds for focus areas, prominent headings. |
| Inkwell Muted | `#1f243c` | `--color-inkwell-muted` | Secondary text, subheadings, subtle branding elements, icon fills. |
| Teal Verdant | `#027e6f` | `--color-teal-verdant` | Primary calls to action, active navigation indicators, key interactive elements — signals forward momentum and success. |
| Slate Blue | `#333954` | `--color-slate-blue` | Tertiary text, background for secondary buttons, subtle graphical accents. |
| Silver Pine | `#4d536` | `--color-silver-pine` | In-active button text, muted body text, secondary icon outlines. |
| Stone Gray | `#6d758d` | `--color-stone-gray` | Default button borders, light graphical elements. |
| Arctic Mist | `#ffffff` | `--color-arctic-mist` | Page backgrounds, card surfaces, primary button backgrounds, inverse text. |
| Snow Drift | `#f5f5f5` | `--color-snow-drift` | Light background surfaces, subtle button states. |
| Frost Gray | `#ebebeb` | `--color-frost-gray` | Subtle borders, button separators. |
| Graphite | `#1c1c1c` | `--color-graphite` | High-contrast small text, icons, prominent lines. |
| Ash | `#545454` | `--color-ash` | Body text for readability, secondary icons. |
| Misty Silver | `#c6cbde` | `--color-misty-silver` | Subtle borders, divider lines, disabled states. |
| Highlight Green | `#00e0ac` | `--color-highlight-green` | Subtle interactive element highlights, small indicators. |

## Tokens — Typography

### matter — Display and main headings; the weight 670 gives titles a substantial, yet not heavy, presence. The negative letter-spacing tightens headlines for impact. · `--font-matter`
- **Substitute:** Open Sans
- **Weights:** 670
- **Sizes:** 20px, 36px, 46px, 52px
- **Line height:** 1.09, 1.11, 1.12, 1.20
- **Letter spacing:** -0.0100em
- **Role:** Display and main headings; the weight 670 gives titles a substantial, yet not heavy, presence. The negative letter-spacing tightens headlines for impact.

### Glyph — Primary body text, navigation elements, button labels, and secondary UI text. Its flexibility across weights and sizes makes it the workhorse for most content. · `--font-glyph`
- **Substitute:** Roboto
- **Weights:** 400, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 22px
- **Line height:** 1.20, 1.25, 1.43, 1.44, 1.45, 1.50, 1.71, 2.29
- **Role:** Primary body text, navigation elements, button labels, and secondary UI text. Its flexibility across weights and sizes makes it the workhorse for most content.

### Inter — Specific use for card content, with particular font features enabled for optimized readability in information dense blocks. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **OpenType features:** `"cv08" on, "ss01"`
- **Role:** Specific use for card content, with particular font features enabled for optimized readability in information dense blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 14px | 1.45 | — | `--text-body-lg` |
| heading | 20px | 1.2 | — | `--text-heading` |
| heading-lg | 36px | 1.12 | -0.48px | `--text-heading-lg` |
| display-sm | 46px | 1.11 | -0.48px | `--text-display-sm` |
| display | 52px | 1.09 | -0.52px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 8px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Primary CTA Button
**Role:** Call to action

backgroundColor=Teal Verdant (#027e6f) with text color Arctic Mist (#ffffff). 6px borderRadius. Padding of 16px vertical and 24px horizontal. Represents the primary user action on the page.

### Secondary Button
**Role:** Alternative action

backgroundColor=Arctic Mist (#ffffff) with text color Graphite (#000000) and Frost Gray (#ebebeb) border. 8px borderRadius. No explicit padding mentioned, implying content-based sizing, but typically 16px horizontal and 8px vertical.

### Ghost Navigation Button
**Role:** Navigation links and secondary actions

Transparent background with Inkwell Muted (#1f243c) text color. Subtle 4px borderRadius, suggesting minimal visual framing for elements like nav items. Padding of 0px vertical and 12px horizontal.

### Tertiary Outline Button
**Role:** Alternative secondary action

backgroundColor=Arctic Mist (#ffffff) with text color Silver Pine (#4d536e) and Stone Gray (#6d758d) border. 6px borderRadius. Padding of 8px vertical and 16px horizontal. Less prominent than primary or secondary buttons.

### Informational Card
**Role:** Content display

Transparent background, 0px borderRadius, no box-shadow. Relies on layout and text for structure, often serving as a container for images or specific content blocks without explicit visual framing.

## Do's and Don'ts

### Do
- Prioritize Inkwell Deep (#0e101a) or Inkwell Muted (#1f243c) for all text to maintain a consistent dark-on-light theme.
- Use Teal Verdant (#027e6f) exclusively for primary calls to action, maintaining its impact and clarity.
- Apply 8px border-radius to all interactive buttons for a consistent soft-edged feel.
- Utilize 'matter' (substitute Open Sans) for all headlines and display text, leveraging its 670 weight and negative letter-spacing for sharp, impactful titles.
- Maintain a comfortable spacing density with a base of 8px, frequently using 8px, 16px, 24px and 32px for gaps and padding.

### Don't
- Avoid introducing additional saturated colors beyond Teal Verdant (#027e6f); the system relies on a near-achromatic palette for its tranquility.
- Do not use box-shadows for elevation; the system uses varying background shades (like Arctic Mist #ffffff and Snow Drift #f5f5f5) to create perceived depth.
- Do not use overly complex background patterns or gradients; stick to solid color surfaces to maintain clarity.
- Avoid excessive variation in typography; 'matter' for headings and 'Glyph' for body text should cover most use cases.
- Do not design full-bleed layouts; content should be subtly constrained, implying a max-width, with consistent horizontal padding for readability.

## Imagery

This site predominantly uses product screenshots and abstract graphic elements. Product screenshots are typically tightly cropped, showcasing UI functionality directly, often within a contained system-like window. Illustrations are abstract and soft geometric, using blurred gradients and light chromatic tints to create ambient atmosphere without being overtly illustrative – they serve a decorative rather than narrative role. Icons are outlined, subtle, and monochromatic, integrated seamlessly with text. The overall approach is highly utilitarian and explanatory, with visuals supporting the product's function rather than creating a rich brand narrative through imagery. Image density is moderate, used to break up text sections and highlight product features.

## Layout

The site features a centered, max-width layout with a primary content column. The hero section often presents a large, centered headline over a plain background, followed by calls to action. Subsequent sections utilize a staggered or simple grid structure, frequently seen as alternating text and image arrangements or multi-column feature lists. There's a clear visual rhythm established by generous vertical spacing between sections (40px) and a consistent internal element spacing (8px base). The design avoids full-bleed imagery, opting for a contained, readable content block approach. Navigation is a persistent top bar, with a prominent 'Get Grammarly' button.

## Agent Prompt Guide

**Quick Color Reference:**
- Text (Primary): #0e101a (Inkwell Deep)
- Background (Page): #ffffff (Arctic Mist)
- CTA (Primary): #027e6f (Teal Verdant)
- Border (Default): #d9d9d9
- Accent: #00e0ac (Highlight Green)

**Example Component Prompts:**
1. Create a hero section: background Arctic Mist (#ffffff). Headline (matter, 52px, 670 weight, -0.0100em letterSpacing, Inkwell Deep #0e101a). Subtext (Glyph, 18px, 400 weight, Inkwell Muted #1f243c). Primary button: Teal Verdant (#027e6f), Arctic Mist (#ffffff) text, 6px radius, 16px vertical/24px horizontal padding.
2. Design a feature card: no background, no border, 0px border-radius. Headline (Glyph, 22px, 700 weight, Inkwell Deep #0e101a). Description (Inter, 16px, 400 weight, Slate Blue #333954). Include a small, outlined icon (path color Inkwell Muted #1f243c) above the headline.
3. Implement a navigation bar: Arctic Mist (#ffffff) background. Logo (SVG fill Inkwell Deep #0e101a). Nav links (Glyph, 14px, 400 weight, Inkwell Muted #1f243c, 4px border-radius, 0px vertical/12px horizontal padding). Active nav link text Teal Verdant (#027e6f).
4. Generate a tertiary button: Arctic Mist (#ffffff) background, Silver Pine (#4d536e) text, Stone Gray (#6d758d) border. 6px border-radius, 8px vertical/16px horizontal padding.

## Similar Brands

- **Notion** — Clean, predominantly white/light gray interface with a strong focus on text and minimal, functional UI elements.
- **Slack** — Utilizes a highly functional and organized layout with subtle use of color for interaction and a generally clean, text-heavy aesthetic.
- **Monday.com** — Relies on clear, defined blocks of content, strong typography for headings, and functional, single-color CTAs against a mostly neutral background.
- **Zapier** — Employs a clean, bright interface with a primary brand color reserved for key actions, emphasizing clarity and productivity through visual restraint.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell-deep: #0e101a;
  --color-inkwell-muted: #1f243c;
  --color-teal-verdant: #027e6f;
  --color-slate-blue: #333954;
  --color-silver-pine: #4d536;
  --color-stone-gray: #6d758d;
  --color-arctic-mist: #ffffff;
  --color-snow-drift: #f5f5f5;
  --color-frost-gray: #ebebeb;
  --color-graphite: #1c1c1c;
  --color-ash: #545454;
  --color-misty-silver: #c6cbde;
  --color-highlight-green: #00e0ac;

  /* Typography — Font Families */
  --font-matter: 'matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-glyph: 'Glyph', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.45;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.48px;
  --text-display-sm: 46px;
  --leading-display-sm: 1.11;
  --tracking-display-sm: -0.48px;
  --text-display: 52px;
  --leading-display: 1.09;
  --tracking-display: -0.52px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-w670: 670;
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
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 38px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell-deep: #0e101a;
  --color-inkwell-muted: #1f243c;
  --color-teal-verdant: #027e6f;
  --color-slate-blue: #333954;
  --color-silver-pine: #4d536;
  --color-stone-gray: #6d758d;
  --color-arctic-mist: #ffffff;
  --color-snow-drift: #f5f5f5;
  --color-frost-gray: #ebebeb;
  --color-graphite: #1c1c1c;
  --color-ash: #545454;
  --color-misty-silver: #c6cbde;
  --color-highlight-green: #00e0ac;

  /* Typography */
  --font-matter: 'matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-glyph: 'Glyph', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.45;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.48px;
  --text-display-sm: 46px;
  --leading-display-sm: 1.11;
  --tracking-display-sm: -0.48px;
  --text-display: 52px;
  --leading-display: 1.09;
  --tracking-display: -0.52px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 38px;
}
```
