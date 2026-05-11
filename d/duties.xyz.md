# Duties.xyz — Style Reference
> Raw concrete with meticulous stenciling.

**Theme:** light

This design feels like a stark, industrial space, where information is presented with an almost raw honesty. The heavy, irregular custom typefaces create a sense of directness, balanced by a clean paper-like background and compact, precise layouts. The visual language emphasizes functionality and impact over ornate aesthetics, making bold statements through strong typography and structured content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#f1f0ee` | `--color-canvas` | Page backgrounds, large content blocks, primary negative space. |
| Inkwell | `#252525` | `--color-inkwell` | Primary text, button backgrounds, strong borders — nearly black, but softer than true #000000, creating less harsh contrast. |
| Pitch Black | `#000000` | `--color-pitch-black` | Headlines, structural borders, icons — the most impactful visual element, reserved for core components. |
| Stone Wall | `#dbdad9` | `--color-stone-wall` | Subtle dividers, background for less prominent UI elements, provides a gentle visual break without strong contrast. |
| Faded Mint | `#a7beb1` | `--color-faded-mint` | Very subtle background hint in specific sections, almost a neutral, adds a hint of organic tone to an otherwise achromatic palette. |
| Accent Blue | `#0000ee` | `--color-accent-blue` | Interactive elements, links, button text — a vibrant, almost browser-default blue, jarring in its purity against the monochrome scheme. |

## Tokens — Typography

### AS Therma Bold Condensed — Display headlines and primary section titles — this font's aggressive, condensed form and negative letter spacing define the brand's 'brave' and direct voice. · `--font-as-therma-bold-condensed`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 96px, 128px, 180px
- **Line height:** 0.80
- **Letter spacing:** -0.067em at 96px and 128px, -0.06em at 180px
- **Role:** Display headlines and primary section titles — this font's aggressive, condensed form and negative letter spacing define the brand's 'brave' and direct voice.

### PP Neue Montreal Mono Medium — Subheadings, metadata, and structured text blocks. The monospaced nature introduces a technical, code-like aesthetic without being purely utilitarian. · `--font-pp-neue-montreal-mono-medium`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 14px
- **Line height:** 1.00, 1.15
- **Letter spacing:** normal
- **OpenType features:** `'case', 'dlig', 'ss04', 'ss07', 'ss08', 'zero'`
- **Role:** Subheadings, metadata, and structured text blocks. The monospaced nature introduces a technical, code-like aesthetic without being purely utilitarian.

### PP Neue Montreal SemiBold — Primary body text — provides excellent readability for longer content, a grounding contrast to the more decorative display fonts. · `--font-pp-neue-montreal-semibold`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.20
- **Letter spacing:** normal
- **OpenType features:** `'zero'`
- **Role:** Primary body text — provides excellent readability for longer content, a grounding contrast to the more decorative display fonts.

### sans-serif — Utility text, captions, and navigation links — a lean system font choice for functional elements where clarity and neutrality are key. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Utility text, captions, and navigation links — a lean system font choice for functional elements where clarity and neutrality are key.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 18px | 1.2 | — | `--text-body` |
| display-sm | 96px | 0.8 | -0.067px | `--text-display-sm` |
| display-md | 128px | 0.8 | -0.067px | `--text-display-md` |
| display-lg | 180px | 0.8 | -0.06px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 4px |
| buttons | 32px |
| default | 8px |

### Layout

- **Section gap:** 40-60px
- **Card padding:** 20px

## Components

### Primary Action Button
**Role:** Interactive element

Rounded pill shape with an Inkwell (#252525) background, Accent Blue (#0000ee) text, and a 32px border radius. Uses 16px horizontal padding and 0px vertical padding. Text uses `sans-serif` at 12px.

### Navigation Link
**Role:** Navigation

Uses `sans-serif` at 12px with Inkwell (#252525) text on Canvas (#f1f0ee) background.

### Menu Trigger
**Role:** Navigation

Small, rectangular button with 'Menu' text using `sans-serif` 12px, Inkwell (#252525) text on Canvas (#f1f0ee) background, framed by `dbdad9` borders. Has 32px border radius.

### Sub-Menu Item
**Role:** Navigation

Text in Inkwell (#252525) using `PP Neue Montreal Mono Medium` at 14px, lineHeight 1.0. Appears on a Canvas (#f1f0ee) background.

### Intro Heading
**Role:** Heading

Uses `AS Therma Bold Condensed` 180px, 400 weight, Inkwell (#000000) text with -0.06em letter spacing. Appears on Canvas (#f1f0ee) background.

### About Section Body
**Role:** Body Text

Uses `PP Neue Montreal SemiBold` 18px, 400 weight with Inkwell (#252525) text, lineHeight 1.2. Appearing on Canvas (#f1f0ee) background. Includes the 'zero' font feature.

### Project Card
**Role:** Content display

Image-based cards with 8px border radius, arranged in a horizontal scroll. Implied white background for content within the card, on a Canvas (#f1f0ee) page background.

## Do's and Don'ts

### Do
- Use AS Therma Bold Condensed for all display-level headlines to enforce the 'brave' aesthetic, ensuring -0.06em letter spacing on larger sizes.
- Maintain a clear hierarchy using Pitch Black (#000000) for primary headings and Inkwell (#252525) for body text and secondary elements.
- Employ the 32px border radius for all interactive buttons and menu items to create visual consistency for actionable elements.
- Utilize Canvas (#f1f0ee) as the dominant page background to provide a clean, high-contrast base for all content.
- Apply `PP Neue Montreal Mono Medium` with its specific font features ('case', 'dlig', 'ss04', 'ss07', 'ss08', 'zero') for structured text and metadata to introduce a technical, precise feel.
- Use 10px or 20px horizontal padding consistently for element grouping and spacing within compact sections.

### Don't
- Avoid generic serif or highly decorative fonts that would dilute the brutalist-industrial feel of the display typography.
- Do not introduce strong chromatic colors beyond the Accent Blue for interactive elements, as it would disrupt the monochrome foundation.
- Do not use subtle shadows or gradients, as the design relies on stark contrast and flat surfaces for depth.
- Avoid soft, organic shapes; stick to sharp edges and predefined radii like 8px or 32px for purposeful geometric form.
- Do not break content out of the Canvas (#f1f0ee) or Stone Wall (#dbdad9) backgrounds with arbitrary colors.
- Do not use letter spacing greater than 'normal' for body text; only the display fonts should have negative letter spacing for effect.

## Imagery

The site predominantly uses product photography of tech accessories (phone cases) with a stark, almost scientific treatment — objects are isolated on neutral or abstract backgrounds, often with rocks or lunar-like surfaces, emphasizing their robust or technical nature. Illustrations, when present (like the pizza slices), are flat, playful, and outlined, offering a humanizing contrast to the otherwise functional aesthetic. Images are usually contained within rectangular frames with 8px or 12px corner radii, occasionally appearing full-bleed or with parallax-like independent motion. There's a clear emphasis on showcasing work and products directly, with imagery serving an explanatory or portfolio function rather than purely decorative.

## Layout

The page primarily follows a max-width contained model, centered on the Canvas (#f1f0ee) background. The hero section features a large, visually dominant headline (`AS Therma Bold Condensed`) stacked centrally or slightly offset. Content sections are compact, using a dense 'elementGap' driven flow, often with horizontal scrolling sections for portfolio items. There's a consistent vertical rhythm, but sections are differentiated more by content type and typography than by alternating background colors. Navigation is minimal, often integrated into the footer or revealed by a small 'Menu' button. The layout feels less like a traditional grid and more like carefully arranged boxes of information, providing a sense of constraint and precision.

## Agent Prompt Guide

### Quick Color Reference
- Text: #252525 (Inkwell)
- Background: #f1f0ee (Canvas)
- CTA Background: #252525 (Inkwell)
- CTA Text: #0000ee (Accent Blue)
- Border: #000000 (Pitch Black)

### 3-5 Example Component Prompts
1. Create a primary headline: 'Digital Solutions' using AS Therma Bold Condensed, 128px, 400 weight, #000000, line-height 0.8, letter-spacing -0.067em, on a Canvas (#f1f0ee) background.
2. Design a primary action button: text 'Learn More' using sans-serif 12px, #0000ee text color, #252525 background color, 32px border radius, 16px horizontal padding, 0px vertical padding.
3. Implement a sub-navigation link: 'Design Services' using PP Neue Montreal Mono Medium, 14px, 400 weight, #252525 text color, line-height 1.0, font-feature-settings 'case', 'dlig', 'ss04', 'ss07', 'ss08', 'zero', on a Canvas (#f1f0ee) background.
4. Create a body text paragraph: 'We specialize in crafting bespoke digital experiences.' using PP Neue Montreal SemiBold, 18px, 400 weight, #252525 text color, line-height 1.2, font-feature-settings 'zero', on a Canvas (#f1f0ee) background.

## Similar Brands

- **Brave New World Designs** — Shares a raw, typographic-heavy aesthetic with large, imposing headlines and a tightly controlled, almost monochromatic color palette.
- **Certain Measures** — Similar use of monospaced fonts for metadata and a general sense of structured, compact information presentation, often in a muted color scheme.
- **Sagmeister & Walsh** — Employs bold, unconventional typography and a strong, almost confrontational visual style, leaning into graphic impact over subtle design.
- **Anton & Irene** — Utilizes highly customized, impactful typography and a clean, direct layout to convey a sense of modern, no-nonsense design thinking.
- **Work & Co** — Demonstrates a similar commitment to precision and functionality, using strong typography and a clear, minimal visual hierarchy to focus on content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #f1f0ee;
  --color-inkwell: #252525;
  --color-pitch-black: #000000;
  --color-stone-wall: #dbdad9;
  --color-faded-mint: #a7beb1;
  --color-accent-blue: #0000ee;

  /* Typography — Font Families */
  --font-as-therma-bold-condensed: 'AS Therma Bold Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono-medium: 'PP Neue Montreal Mono Medium', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-pp-neue-montreal-semibold: 'PP Neue Montreal SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 18px;
  --leading-body: 1.2;
  --text-display-sm: 96px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.067px;
  --text-display-md: 128px;
  --leading-display-md: 0.8;
  --tracking-display-md: -0.067px;
  --text-display-lg: 180px;
  --leading-display-lg: 0.8;
  --tracking-display-lg: -0.06px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 40-60px;
  --card-padding: 20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 32px;

  /* Named Radii */
  --radius-small: 4px;
  --radius-buttons: 32px;
  --radius-default: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #f1f0ee;
  --color-inkwell: #252525;
  --color-pitch-black: #000000;
  --color-stone-wall: #dbdad9;
  --color-faded-mint: #a7beb1;
  --color-accent-blue: #0000ee;

  /* Typography */
  --font-as-therma-bold-condensed: 'AS Therma Bold Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal-mono-medium: 'PP Neue Montreal Mono Medium', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-pp-neue-montreal-semibold: 'PP Neue Montreal SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 18px;
  --leading-body: 1.2;
  --text-display-sm: 96px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.067px;
  --text-display-md: 128px;
  --leading-display-md: 0.8;
  --tracking-display-md: -0.067px;
  --text-display-lg: 180px;
  --leading-display-lg: 0.8;
  --tracking-display-lg: -0.06px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 32px;
}
```
