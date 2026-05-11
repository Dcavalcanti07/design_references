# Shade — Style Reference
> High-contrast utility with violet accent. A clean white canvas underpins sharp black text and functional components, highlighted by a single, vivid violet.

**Theme:** light

Shade employs a stark, high-contrast visual language with a focus on functional typography and precise spacing. The design uses a dominant neutral palette relieved by a single vibrant violet accent. Components feature sharp edges or large, bold radii, often with strong box shadows for emphasis, conveying a sense of directness and polished utility. Surfaces are generally flat, with subtle elevation coming from shadows rather than color shifts.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, UI elements requiring high contrast with text |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, high-contrast outlines, icons |
| Coal Black | `#131315` | `--color-coal-black` | Strong headings, button backgrounds, elevated surface backgrounds where text needs high contrast |
| Light Fog | `#f1f1f1` | `--color-light-fog` | Subtle background for UI elements, button box shadows, soft divider lines |
| Steel Gray | `#717173` | `--color-steel-gray` | Muted body text, secondary information, inactive states, subtle element backgrounds |
| Stone Gray | `#a0a0a0` | `--color-stone-gray` | Placeholder text, subtle box shadows, light borders |
| Warm Gray | `#d0d0d0` | `--color-warm-gray` | Hairline separators, very light element backgrounds, subtle shadow tints |
| Deep Gray | `#444444` | `--color-deep-gray` | Input text, input borders, less prominent body text |
| Dark Gray | `#333333` | `--color-dark-gray` | Cookie banner text, secondary button borders, button text |
| Digital Violet Light | `#dacefd` | `--color-digital-violet-light` | Subtle border accent for UI elements, supporting visual cues |
| Digital Violet Bold | `#6941c6` | `--color-digital-violet-bold` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Digital Violet Vivid | `conic-gradient(rgba(0, 0, 0, 0) 200deg, rgb(133, 92, 247))` | `--color-digital-violet-vivid` | Decorative background fills, active states, conical gradients for specific elements |

## Tokens — Typography

### Inter Display — Primary headings and body text, providing a distinctive, tightly spaced feel for key content. The custom features tune its appearance for legibility and aesthetic. · `--font-inter-display`
- **Weights:** 400
- **Sizes:** 10px, 14px, 16px, 18px, 20px, 21px, 24px, 28px, 32px, 36px, 40px, 48px, 56px, 72px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.22, 1.25, 1.30, 1.40, 1.43, 1.57
- **Letter spacing:** -0.0300em at large sizes, -0.0100em at smaller sizes
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"; "ss01", "ss07", "ss08"`
- **Role:** Primary headings and body text, providing a distinctive, tightly spaced feel for key content. The custom features tune its appearance for legibility and aesthetic.

### sans-serif — Fallback for general UI text, links, and buttons, ensuring basic content readability without demanding specific font support. Used where Inter Display is not explicitly applied. · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback for general UI text, links, and buttons, ensuring basic content readability without demanding specific font support. Used where Inter Display is not explicitly applied.

### Aux Mono Regular — Monospaced text for specific data points or code examples, offering a technical and precise feel. The tight letter-spacing emphasizes its distinct character. · `--font-aux-mono-regular`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00, 1.29
- **Letter spacing:** -0.0400em at 14px, -0.0100em
- **Role:** Monospaced text for specific data points or code examples, offering a technical and precise feel. The tight letter-spacing emphasizes its distinct character.

### Inter — General body text, card content, and secondary button labels, providing a highly legible and versatile textual layer. This standard variant of Inter balances readability with the custom Inter Display. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.00, 1.20, 1.50
- **Letter spacing:** normal
- **Role:** General body text, card content, and secondary button labels, providing a highly legible and versatile textual layer. This standard variant of Inter balances readability with the custom Inter Display.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | — | `--text-caption` |
| body | 14px | 1.29 | -0.48px | `--text-body` |
| subheading | 18px | 1.22 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 32px | 1.4 | — | `--text-heading` |
| heading-lg | 40px | 1.15 | — | `--text-heading-lg` |
| display | 56px | 1.1 | -1.68px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| input | 9px |
| buttons | 20px |
| default | 9px |
| largeButtons | 35px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(241, 241, 241) 8px 8px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(226, 226, 227, 0.5) 10px 10px 0px -2px` | `--shadow-subtle-2` |
| sm | `rgba(19, 19, 21, 0.12) 0px 1px 4px 0px` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.2) 0px 3px 4px 0px` | `--shadow-sm-2` |
| subtle-3 | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 100px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Main call-to-action button for initiating key flows.

Background: Coal Black (#131315), Text: Canvas White (#ffffff). Padding: 20px all sides. Border Radius: 20px. Uses a sharp, pronounced box-shadow below.

### Secondary Outlined Button
**Role:** Secondary call-to-action, less prominent than the filled primary.

Background: Canvas White (#ffffff), Text: Midnight Ink (#000000). Border: 1px solid Midnight Ink (#000000). Padding: 20px all sides. Border Radius: 0px. A square, minimalist aesthetic.

### Ghost Accent Button
**Role:** Minimal impact button, often for navigation or secondary actions, using brand accent.

Background: transparent, Text: Digital Violet Bold (#6941c6). Border: 1px solid Digital Violet Bold (#6941c6). Padding: 10px top/bottom, 15px left/right. Border Radius: 0px. Used for 'Shade Raises $14M in New Funding' banner.

### Ghost Neutral Button
**Role:** Minimal impact button, for subtle interactive elements or navigation.

Background: transparent, Text: Midnight Ink (#000000). Border: 1px solid Midnight Ink (#000000). Padding: 10px top/bottom, 20px/10px left/right. Border Radius: 0px.

### Search/Navigation Tab
**Role:** Interactive tabs for filtering or navigating content sections.

Background: Canvas White (#ffffff), Text: Midnight Ink (#000000) for active, Steel Gray (#717173) for inactive. Border: 1px inset rgba(0,0,0,0.05). Underlines with a solid bar color.

### Product Feature Card
**Role:** Displaying product features or content blocks.

Background: Canvas White (#ffffff). Border Radius: 14px. Box Shadow: inset 0px 0px 0px 1px rgba(0, 0, 0, 0.05). No padding defined, content is expected to dictate internal spacing.

### Default Input Field
**Role:** Standard text input element.

Background: rgb(238, 238, 238), Text: Deep Gray (#444444), Border: 1px solid Deep Gray (#444444). Padding: 10px all sides. Border Radius: 8px.

### Small Pill Button
**Role:** Compact interactive element or tag, typically for meta-information or minor actions.

Background: Coal Black (#131315). Text: rgb(0,0,238) (browser default link blue, not a brand choice). Radius: 20px. Padding: 10px top/bottom, 20px left/right.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary backgrounds and Coal Black (#131315) or Midnight Ink (#000000) for primary text to maintain high contrast.
- Use Inter Display for all headings, leveraging its full range of sizes and letter-spacing for visual impact and hierarchy.
- Apply a 20px border-radius for primary buttons and 14px for cards, ensuring consistent application of these distinct rounded corners.
- Emphasize interactive elements and call-to-actions with Digital Violet Bold (#6941c6) for borders or text, or Coal Black (#131315) for filled backgrounds.
- Maintain a clear elementGap of 10px for vertical rhythm between individual UI components.
- Employ the hard 8px 8px 0px 0px F1F1F1 shadow for buttons to give them a distinct, almost debossed appearance.
- Use Ghost Neutral buttons (transparent background, Midnight Ink border and text) for less prominent actions, reserving filled or accented buttons for key interactions.

### Don't
- Avoid using multiple chromatic colors; restrict accents primarily to the Digital Violet palette.
- Do not introduce soft or subtle shadows where a hard, offset shadow is expected; adhere to the distinct shadow style on buttons.
- Refrain from using generic font families or weights when Inter Display or Aux Mono Regular are available for specific roles.
- Do not deviate from the established border radii of 0px for some interactive elements and 14px/20px/35px for others, as these are signature elements.
- Avoid introducing background gradients outside of the specified conic-gradient for special accent areas.
- Do not use generic gray scales for text when Steel Gray (#717173), Deep Gray (#444444), or Dark Gray (#333333) are available for semantic text roles.
- Do not use transparent or blurry backgrounds when solid color surfaces are the default. Sharp contrasts are key.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and high-contrast surfaces. |
| 1 | Light Fog | `#f1f1f1` | Subtle background for grouped UI elements or light separators. |
| 2 | Default Card | `#ffffff` | Default card background, distinguished by its subtle inset border shadow. |
| 3 | Coal Black Elevated | `#131315` | Darker background for primary filled buttons and specific elevated UI sections. |

## Elevation

- **Primary Filled Button:** `rgb(241, 241, 241) 8px 8px 0px 0px`
- **Link/Other with Shadow:** `rgba(226, 226, 227, 0.5) 10px 10px 0px -2px`
- **Button Soft Shadow:** `rgba(19, 19, 21, 0.12) 0px 1px 4px 0px`
- **Card Inset Border:** `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset`

## Imagery

This design system uses a blend of tightly cropped product screenshots and high-quality photography, often with a subtle film grain or warm color grade, alongside a highly functional icon set. Lifestyle photography is present but primarily contained, never full-bleed, depicting people using technology or interacting in studio environments. Illustrations are minimal to none. Icons are typically outlined or filled, mostly monochrome (Midnight Ink or Canvas White), with a consistent stroke weight. Imagery serves mostly an explanatory or product showcase role, occasionally decorative for atmosphere, but never heavily stylized or abstract. The density is balanced, with imagery breaking up text-dominant sections, but not overwhelming the page.

## Layout

The page primarily uses a max-width contained model, with a consistent vertical rhythm. The hero section often features a centered headline over a white background with a secondary subheading and two action buttons (one filled, one outlined). Sections alternate between simple centered stacks of text, and two-column layouts featuring text on one side and a visual element (like a product screenshot or video frame) on the other. A notable element is a horizontal tab navigation using ghost buttons. Feature grids, if present, are likely simple 3-column structures. Ample white space creates a comfortable, airy density between content blocks. Navigation is a sticky top bar with a left-aligned logo and right-aligned links and buttons.

## Agent Prompt Guide

### Quick Color Reference
* text: #000000
* background: #ffffff
* border: #000000
* accent: #6941c6
* primary action: #131315 (filled action)

### 3-5 Example Component Prompts
* Create a Primary Action Button: #131315 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
* **Feature Card with Inset Border:** Create a card with background #ffffff, 14px radius, box-shadow rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset. Inside, add a 24px Inter Display heading and 14px Inter body text. 
* **Accent Banner with Ghost Button:** Create a banner section with subtle Digital Violet Light (#dacefd) background, containing a text label in Inter 14px #6941c6. Include a 'Shade Raises $14M in New Funding' Ghost Accent Button: background transparent, text #6941c6, border 1px solid #6941c6, 10px top/bottom, 15px left/right padding, 0px radius.
* **Standard Input Field:** Design an input field with background #eeeeee, text #444444, border 1px solid #444444, 8px radius, 10px padding.
* **Navigation Tab:** Create a navigation tab component. Active tab: background #ffffff, text #000000, border-bottom 2px solid #6941c6. Inactive tab: background #ffffff, text #717173, no border-bottom.

## Similar Brands

- **Figma** — High-contrast text on white surfaces, functional typography, and judicious use of a single vibrant accent color for interaction and brand points.
- **Linear** — Clean, almost sparse UI with strong typographic hierarchy, preference for greyscales and a specific, restrained accent color, and precise geometric shapes.
- **Webflow** — Emphasis on crisp, high-contrast UI elements, strong use of box-shadows for component elevation and depth, and a focused color palette.
- **Vercel** — Minimalist aesthetic with sharp edges or distinct large radii, powerful headings, and a focus on content over heavy visual decoration, using a limited color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-coal-black: #131315;
  --color-light-fog: #f1f1f1;
  --color-steel-gray: #717173;
  --color-stone-gray: #a0a0a0;
  --color-warm-gray: #d0d0d0;
  --color-deep-gray: #444444;
  --color-dark-gray: #333333;
  --color-digital-violet-light: #dacefd;
  --color-digital-violet-bold: #6941c6;
  --color-digital-violet-vivid: #855cf8;
  --gradient-digital-violet-vivid: conic-gradient(rgba(0, 0, 0, 0) 200deg, rgb(133, 92, 247));

  /* Typography — Font Families */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aux-mono-regular: 'Aux Mono Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.29;
  --tracking-body: -0.48px;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.68px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 9px;
  --radius-xl: 14px;
  --radius-2xl: 20px;
  --radius-2xl-2: 23px;
  --radius-3xl: 35px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-input: 9px;
  --radius-buttons: 20px;
  --radius-default: 9px;
  --radius-largebuttons: 35px;

  /* Shadows */
  --shadow-subtle: rgb(241, 241, 241) 8px 8px 0px 0px;
  --shadow-subtle-2: rgba(226, 226, 227, 0.5) 10px 10px 0px -2px;
  --shadow-sm: rgba(19, 19, 21, 0.12) 0px 1px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 0px 3px 4px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-light-fog: #f1f1f1;
  --surface-default-card: #ffffff;
  --surface-coal-black-elevated: #131315;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-ink: #000000;
  --color-coal-black: #131315;
  --color-light-fog: #f1f1f1;
  --color-steel-gray: #717173;
  --color-stone-gray: #a0a0a0;
  --color-warm-gray: #d0d0d0;
  --color-deep-gray: #444444;
  --color-dark-gray: #333333;
  --color-digital-violet-light: #dacefd;
  --color-digital-violet-bold: #6941c6;
  --color-digital-violet-vivid: #855cf8;

  /* Typography */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aux-mono-regular: 'Aux Mono Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.29;
  --tracking-body: -0.48px;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.4;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.68px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 9px;
  --radius-xl: 14px;
  --radius-2xl: 20px;
  --radius-2xl-2: 23px;
  --radius-3xl: 35px;

  /* Shadows */
  --shadow-subtle: rgb(241, 241, 241) 8px 8px 0px 0px;
  --shadow-subtle-2: rgba(226, 226, 227, 0.5) 10px 10px 0px -2px;
  --shadow-sm: rgba(19, 19, 21, 0.12) 0px 1px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 0px 3px 4px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;
}
```
