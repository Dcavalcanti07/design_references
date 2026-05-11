# Agronomy Workshop — Style Reference
> Monochromatic workwear utility

**Theme:** light

Agronomy Workshop uses a monochrome, workwear-inspired design with a single vivid blue accent. The visual style is rooted in understated typography, a constrained palette focused on black, white, and a range of dark grays, and compact product display. A distinct, slightly wider letter-spacing for monospaced elements introduces a subtle utilitarian contrast, while product imagery is tightly composed on neutral backdrops. Surfaces remain flat and unadorned, relying on content separation and a hint of border-radius for structure.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, dominant component surfaces |
| Rich Black | `#000000` | `--color-rich-black` | Primary text, icon default fill, strong borders, ghost button borders |
| Text Dark | `#1e1e1e` | `--color-text-dark` | Headings, body text, secondary text where emphasis is retained |
| Cool Gray | `#888888` | `--color-cool-gray` | Muted body text, subtle helper text, light borders |
| Light Gray | `#666666` | `--color-light-gray` | Detailed descriptive text, tertiary information |
| Soft Off-White | `#eeede8` | `--color-soft-off-white` | Secondary background color for alternating section subtly, product variant backgrounds |
| Vivid Blue | `#0076ff` | `--color-vivid-blue` | Primary Call-to-Action buttons, interactive links, active states — a sharp, electric contrast against the neutral palette |

## Tokens — Typography

### sans-serif — Fallback and utilitarian interface elements such as basic labels and navigation · `--font-sans-serif`
- **Substitute:** system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback and utilitarian interface elements such as basic labels and navigation

### Gerstner Programm FSL — Body text, detailed product descriptions, and sub-headers — a legible, slightly condensed serif with unique character features for specific typographic control · `--font-gerstner-programm-fsl`
- **Substitute:** serif, 'Times New Roman', Times
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.14
- **Letter spacing:** -0.02
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Body text, detailed product descriptions, and sub-headers — a legible, slightly condensed serif with unique character features for specific typographic control

### ABC Marfa Mono Unlicensed Trial — Small, technical labels, tags, and price indications — its wide tracking reinforces a utilitarian, data-driven feel · `--font-abc-marfa-mono-unlicensed-trial`
- **Substitute:** monospace, 'Courier New', Courier
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.20
- **Letter spacing:** 0.1
- **Role:** Small, technical labels, tags, and price indications — its wide tracking reinforces a utilitarian, data-driven feel

### OT Neue Montreal Medium Semi Squeezed — Prominent headings and section titles — its semi-squeezed form and medium weight provide a compact yet commanding presence without visual heaviness · `--font-ot-neue-montreal-medium-semi-squeezed`
- **Substitute:** sans-serif, system-ui
- **Weights:** 500
- **Sizes:** 32px, 54px
- **Line height:** 0.81, 1.00
- **Letter spacing:** -0.02
- **Role:** Prominent headings and section titles — its semi-squeezed form and medium weight provide a compact yet commanding presence without visual heaviness

### Gerstner Programm FSL Regular — Gerstner Programm FSL Regular — detected in extracted data but not described by AI · `--font-gerstner-programm-fsl-regular`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.14
- **Letter spacing:** -0.02
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Gerstner Programm FSL Regular — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | 1px | `--text-caption` |
| body | 14px | 1.14 | -0.28px | `--text-body` |
| heading-lg | 32px | 0.81 | -0.64px | `--text-heading-lg` |
| display | 54px | 1 | -1.08px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| larger | 20px |
| default | 5px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Filled button

Solid filled button with a vivid blue background, white text, and a slight border-radius. Used for primary calls-to-action like 'Shop'.

### Product Card
**Role:** Product display unit

A container for individual product listings, featuring a subtle off-white background (#eeede8) or white (#ffffff), with text in Text Dark (#1e1e1e) and bordered by Rich Black (#000000) for visual separation. Uses default radius of 5px.

### Image Thumbnail
**Role:** Supporting image

Smaller image previews, typically using a 5px border radius and often appearing on a Soft Off-White (#eeede8) background.

### Badge/Tag
**Role:** Informational label

Small, rectangular labels with a 5px border radius, such as the price tag '$136', likely using ABC Marfa Mono typography.

### Navigation Link
**Role:** Top navigation item

Plain text links in Rich Black (#000000) using the system sans-serif font, usually 12px, for primary navigation elements like 'Index' and 'Shop'.

## Do's and Don'ts

### Do
- Prioritize Rich Black (#000000), Text Dark (#1e1e1e), and Cool Gray (#888888) for all textual content, reserving Vivid Blue (#0076ff) strictly for primary interactive elements.
- Apply Soft Off-White (#eeede8) as a subtle background for secondary content blocks or product details to break up visual space without introducing strong contrast.
- Use Vivid Blue (#0076ff) as the singular accent color for all primary button fills and interactive link states.
- Employ the Gerstner Programm FSL font for all body copy and most secondary headings to maintain the distinct type character, leveraging its 'blwf', 'cv03', 'cv04', 'cv09', 'cv11' features for precise control.
- Ensure headings use OT Neue Montreal Medium Semi Squeezed at 32px or 54px with a letter-spacing of -0.02em for a compact, commanding presence.
- Maintain a default border-radius of 5px for cards, buttons, and image containers, with larger elements using 20px radius.
- Space elements primarily using multiples of 4px, especially 4px for small element gaps and 40px for section separation.

### Don't
- Do not introduce additional chromatic colors beyond Vivid Blue (#0076ff) for interactive elements or brand accents.
- Avoid decorative shadows or excessive elevation; maintain a flat UI aesthetic with subtle borders and background color shifts for distinction.
- Do not use generic sans-serif fonts where Gerstner Programm FSL or OT Neue Montreal Medium Semi Squeezed are specified, to preserve brand identity.
- Do not deviate from the specified letter-spacing for ABC Marfa Mono (0.1em) or OT Neue Montreal Medium Semi Squeezed (-0.02em); these are key to their visual character.
- Avoid using large, full-bleed images in content sections; prefer tightly cropped product or model photography on neutral backgrounds within defined content blocks.
- Do not overuse the Soft Off-White (#eeede8) background; it should serve as a subtle secondary surface, not dominate the canvas.
- Do not apply large, rounded radii (e.g., >20px) to UI elements; stick to 5px for most components and 20px for larger blocks, preserving a structured appearance.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background and default surface for main content blocks. |
| 2 | Soft Off-White | `#eeede8` | Secondary background for product cards or alternating content sections, providing subtle differentiation without strong visual breaks. |

## Imagery

Imagery primarily consists of high-quality product photography and model shots, tightly cropped and presented on neutral, often white or lightly textured, backgrounds. The treatment is clean and isolated, focusing on the product itself with minimal environmental context. Photography aims for realism and detail, absent of heavy filters or artistic effects. Icons (when visible, e.g., in navigation) are simplistic, outlined, and monochromatic, aligning with the overall utilitarian aesthetic. The density is moderate to high, with images typically dominating the visual space within their respective content blocks, serving as product showcases.

## Layout

The page primarily uses a contained layout with content organized into distinct, visually separated blocks. The hero section often presents a large image or visual with text overlaid or alongside. Section rhythm is driven by consistent vertical spacing (40px `sectionGap`) and subtle shifts in background color between Canvas White (#ffffff) and Soft Off-White (#eeede8) for alternating content blocks. Content is arranged in a fluid grid, often featuring side-by-side product views or image-text pairings. A prominent feature is the use of a simple, minimal top navigation bar with 'Index' and 'Shop' links, along with a 'Bag' icon.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000 
- background: #ffffff 
- border: #000000 
- accent: no distinct accent color 
- primary action: no distinct CTA color

Example Component Prompts:
- Create a 'Shop Now' button: background Vivid Blue (#0076ff), text Rich Black (#000000), radius 5px, padding 6px vertical, 20px horizontal. Font: Gerstner Programm FSL Regular, 14px, lineHeight 1.14.
- Create a product headline: Text Dark (#1e1e1e), OT Neue Montreal Medium Semi Squeezed, 32px, lineHeight 0.81, letter-spacing -0.64px.
- Create a standard body text paragraph: Text Dark (#1e1e1e), Gerstner Programm FSL Regular, 14px, lineHeight 1.14, letter-spacing -0.28px.
- Create a product price tag: background Rich Black (#000000), text Canvas White (#ffffff), ABC Marfa Mono Unlicensed Trial Regular, 10px, lineHeight 1.2, letter-spacing 1px, radius 5px, padding 4px vertical, 8px horizontal.
- Create a product listing card: Canvas White (#ffffff) background, 5px radius, with a 1px Rich Black (#000000) border, padding 16px. Use Text Dark (#1e1e1e) for product titles and Cool Gray (#888888) for descriptions.

## Similar Brands

- **A.P.C.** — Monochromatic palette, subtle workwear influence, and focus on product quality through minimalist display.
- **Acne Studios** — Understated and refined aesthetic, emphasis on typography and neutral tones with occasional bold single-color accents.
- **Arket** — Clean, functional design with a focus on product photography and a restrained color palette.
- **Everlane** — Minimalist e-commerce with strong typographic hierarchy, clean layouts, and a focus on essential items.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-rich-black: #000000;
  --color-text-dark: #1e1e1e;
  --color-cool-gray: #888888;
  --color-light-gray: #666666;
  --color-soft-off-white: #eeede8;
  --color-vivid-blue: #0076ff;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gerstner-programm-fsl: 'Gerstner Programm FSL', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-marfa-mono-unlicensed-trial: 'ABC Marfa Mono Unlicensed Trial', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ot-neue-montreal-medium-semi-squeezed: 'OT Neue Montreal Medium Semi Squeezed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gerstner-programm-fsl-regular: 'Gerstner Programm FSL Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 1px;
  --text-body: 14px;
  --leading-body: 1.14;
  --tracking-body: -0.28px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.81;
  --tracking-heading-lg: -0.64px;
  --text-display: 54px;
  --leading-display: 1;
  --tracking-display: -1.08px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-larger: 20px;
  --radius-default: 5px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-soft-off-white: #eeede8;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-rich-black: #000000;
  --color-text-dark: #1e1e1e;
  --color-cool-gray: #888888;
  --color-light-gray: #666666;
  --color-soft-off-white: #eeede8;
  --color-vivid-blue: #0076ff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gerstner-programm-fsl: 'Gerstner Programm FSL', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-marfa-mono-unlicensed-trial: 'ABC Marfa Mono Unlicensed Trial', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ot-neue-montreal-medium-semi-squeezed: 'OT Neue Montreal Medium Semi Squeezed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gerstner-programm-fsl-regular: 'Gerstner Programm FSL Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 1px;
  --text-body: 14px;
  --leading-body: 1.14;
  --tracking-body: -0.28px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.81;
  --tracking-heading-lg: -0.64px;
  --text-display: 54px;
  --leading-display: 1;
  --tracking-display: -1.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 20px;
}
```
