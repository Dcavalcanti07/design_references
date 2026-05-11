# Glein — Style Reference
> Monochromatic architectural clarity: product as sculpture, framed by pure light and shadow.

**Theme:** light

Glein embraces a stark, high-contrast aesthetic reminiscent of black-and-white photography, presenting product with minimal visual distraction. The design prioritizes readability and directness through utilitarian custom typography and a precise, monochromatic color palette. Surfaced content often features a muted, off-white background, creating subtle depth while maintaining an overall light theme. Components are frequently borderless or use fine, dark strokes to delineate elements, emphasizing content through clear separation rather than heavy ornamentation. Layouts are structured and rectilinear, relying on robust typographic hierarchy to guide the eye.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Raven Black | `#000000` | `--color-raven-black` | Primary text, interactive elements, section borders, button backgrounds, accent details — a deep, true black creates strong contrast against light surfaces, grounding the UI |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page and card backgrounds, default text for dark buttons — provides a clean, expansive foundation for content |
| Warm Parchment | `#ebe6dc` | `--color-warm-parchment` | Secondary background accent, subtle surface differentiation — a warm, desaturated off-white softens larger content blocks without introducing overt color |
| Muted Ash | `#b3b3b3` | `--color-muted-ash` | Light secondary text, subtle borders — used for less prominent text elements or decorative navigation elements where a full contrast is not desired |

## Tokens — Typography

### F-Grotesk — Headlines, body text, general UI elements — a custom grotesque sans-serif provides a sturdy, direct, and highly legible voice. Its geometric simplicity reinforces the brand's 'product as sculpture' ethos. · `--font-f-grotesk`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 13px, 15px, 20px, 30px, 111px
- **Line height:** 1.00, 1.19, 1.20, 1.30
- **Role:** Headlines, body text, general UI elements — a custom grotesque sans-serif provides a sturdy, direct, and highly legible voice. Its geometric simplicity reinforces the brand's 'product as sculpture' ethos.

### Maison-Neue-Mono — Callouts, metadata, navigation, button labels — a custom monospaced sans-serif offers a technical, precise counterpoint to F-Grotesk, lending an artisanal, craft-focused feel to functional text. · `--font-maison-neue-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 13px, 15px, 20px
- **Line height:** 1.00, 1.19, 1.20, 1.30
- **Role:** Callouts, metadata, navigation, button labels — a custom monospaced sans-serif offers a technical, precise counterpoint to F-Grotesk, lending an artisanal, craft-focused feel to functional text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1 | — | `--text-caption` |
| body | 15px | 1 | — | `--text-body` |
| subheading | 20px | 1.19 | — | `--text-subheading` |
| heading | 30px | 1.2 | — | `--text-heading` |
| display | 111px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 42 | 42px | `--spacing-42` |
| 156 | 156px | `--spacing-156` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 42px
- **Card padding:** 24px
- **Element gap:** 13px

## Components

### Filled Primary Button
**Role:** Primary Call to Action

Solid Raven Black background (#000000) with Canvas White text (#ffffff). Features 2.25px vertical padding and 6px horizontal padding. No border radius, maintaining a sharp, utilitarian edge.

### Ghost Button
**Role:** Secondary Action

Transparent background with Raven Black text (#000000). Used for subtle actions or navigation elements that should not dominate the visual hierarchy. No padding or border radius for a seamless integration with text.

### Navigation Link
**Role:** Primary Navigation

Raven Black text (#000000) with no background or border. Text is typically Maison-Neue-Mono at 15px. Emphasizes content over interactive chrome.

### Callout Badge
**Role:** Informational Display

Maison-Neue-Mono 400 text, 13px size, with no background, intended for short informational text like 'mehr anzeigen'. It appears frequently as a text label overlaying images or section titles.

### Cookie Consent Modal
**Role:** Privacy Notice

A rectangular overlay with Canvas White background (#ffffff) and Raven Black text (#000000). Contains primary and secondary buttons for user input, displaying a sharp 0px border-radius to match the overall aesthetic.

## Do's and Don'ts

### Do
- Always use Raven Black (#000000) for primary text and interactive elements to maintain high contrast and legibility.
- Prioritize Canvas White (#ffffff) as the base background for main content areas, reserving Warm Parchment (#ebe6dc) for subtle content block distinctions.
- Employ F-Grotesk for all primary headings and body text to convey a direct, sculptural presence.
- Utilize Maison-Neue-Mono for nav links and button labels, leveraging its monospaced character for a precise, crafted feel.
- Maintain hard, 0px border-radii for all buttons and interactive elements, reinforcing the sharp, architectural visual language.
- Structure layouts with implied grid systems and strong vertical rhythm, using minimal explicit dividers where possible.
- Ensure all interactive elements maintain a hover state that aligns with the Raven Black and Canvas White contrast, such as a background fill on Raven Black from a ghost element.

### Don't
- Avoid introducing any saturated colors; the system is strictly achromatic, with no accent hues beyond brand neutrals.
- Do not soften edges with border-radii; all interactive elements and contained components should maintain crisp, 0px corners.
- Refrain from using drop shadows or heavy elevation styles; rely on color contrast and subtle background changes for layering.
- Do not use generic sans-serif fonts; custom F-Grotesk and Maison-Neue-Mono are essential to the brand's unique typographic fingerprint.
- Avoid decorative gradients or complex overlays; maintain a flat, stark aesthetic for backgrounds and surfaces.
- Do not break rhythm with irregular spacing; adhere to the defined base unit of 6px and derived element/section gaps.
- Do not use any iconography that deviates from simple, single-color line art in Raven Black or Muted Ash.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, default content surfaces |
| 1 | Warm Parchment | `#ebe6dc` | Secondary background, subtle content block separation, card backgrounds |
| 2 | Overlay/Active | `#000000` | Full-bleed hero sections, solid button fills, active states, text against light backgrounds |

## Imagery

This site uses large, editorial-style product photography, often featuring models against minimalist, neutral backgrounds. Images are typically full-bleed within their section or occupy significant visual space, acting as primary content elements rather than mere decorations. The photography style is high-key and focused, with clean crops and natural lighting that emphasizes product textures and forms. There are no overt illustrations or abstract graphics; instead, imagery directly showcases the product. Icons are minimal, single-color (Raven Black), and functional, receding into the UI rather than drawing attention. The density is image-heavy, with large product visuals dominating sections and text used sparingly to frame or narrate.

## Layout

The page primarily follows a max-width contained model with sections flowing vertically, but often features full-bleed hero sections or large image blocks that break this convention to create visual impact. The hero section frequently uses large background imagery with centered overlay text or split-screen layouts. Sections maintain a consistent vertical rhythm, often alternating between large image blocks and cleaner text-dominant areas. Content is arranged in flexible grid patterns, frequently two-column for text alongside visuals, or implicit grids for product displays. The overall density is balanced, allowing breathing room around large images while maintaining readable text blocks. Navigation is a sticky top bar, minimal and unembellished, emphasizing direct links.

## Agent Prompt Guide

**Quick Color Reference:**
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

**3-5 Example Component Prompts:**
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a `Navigation Link` for 'Nachhaltige Materialien'. Text color is Raven Black (#000000), using Maison-Neue-Mono, weight 400, size 15px. No background, no border, no padding.
4. Create a product listing section. The section background is Warm Parchment (#ebe6dc). The product title 'T-Shirts' should use F-Grotesk, weight 400, size 30px, in Raven Black (#000000). Below the title, include a `Callout Badge` 'mehr anzeigen' in Maison-Neue-Mono, weight 400, size 13px, Raven Black (#000000).

## Similar Brands

- **Acne Studios** — Stark, high-contrast black and white palette, minimalist typography, and editorial-style product photography.
- **COS (Collection of Style)** — Focus on clean lines, utilitarian design, and a restrained color palette in product presentation and website UI.
- **A.P.C.** — Understated design, emphasis on material quality over ornamentation, and a monochromatic visual language.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-raven-black: #000000;
  --color-canvas-white: #ffffff;
  --color-warm-parchment: #ebe6dc;
  --color-muted-ash: #b3b3b3;

  /* Typography — Font Families */
  --font-f-grotesk: 'F-Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-maison-neue-mono: 'Maison-Neue-Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1;
  --text-body: 15px;
  --leading-body: 1;
  --text-subheading: 20px;
  --leading-subheading: 1.19;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 111px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-42: 42px;
  --spacing-156: 156px;

  /* Layout */
  --section-gap: 42px;
  --card-padding: 24px;
  --element-gap: 13px;

  /* Named Radii */
  --radius-default: 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-warm-parchment: #ebe6dc;
  --surface-overlayactive: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-raven-black: #000000;
  --color-canvas-white: #ffffff;
  --color-warm-parchment: #ebe6dc;
  --color-muted-ash: #b3b3b3;

  /* Typography */
  --font-f-grotesk: 'F-Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-maison-neue-mono: 'Maison-Neue-Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1;
  --text-body: 15px;
  --leading-body: 1;
  --text-subheading: 20px;
  --leading-subheading: 1.19;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-display: 111px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-42: 42px;
  --spacing-156: 156px;
}
```
