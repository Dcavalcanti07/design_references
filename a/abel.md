# Abel — Style Reference
> Minimalist gallery canvas

**Theme:** light

Abel employs a monochrome canvas with sharp, minimal typography and subtle surface variations. The overall aesthetic is one of understated luxury, where product imagery takes center stage against a quiet, desaturated backdrop. Visual emphasis is achieved through stark tonal contrast and precise spacing, rather than color accents or elaborate ornamentation. Components are typically borderless, relying on text color shifts or underline states for interaction cues.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Soft Ivory | `#f6eada` | `--color-soft-ivory` | Secondary background surfaces, hairline borders, subtle dividers |
| Charcoal Noir | `#030303` | `--color-charcoal-noir` | Primary text, key headings, brand accents, button backgrounds for filled actions, strong borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, elevated card backgrounds, inverse text for dark elements |
| Concrete Gray | `#cccccc` | `--color-concrete-gray` | Tertiary background surfaces, subtle visual breaks between content sections |
| Stone Whisper | `#dad9d5` | `--color-stone-whisper` | Muted background elements, very light surface differentiation |
| Ash Cloud | `#807e81` | `--color-ash-cloud` | Helper text, subtle borders, secondary text for less prominent information |

## Tokens — Typography

### Founders Grotesk — Primary typeface for most interface text, headings, and body copy. Its varying lightweight nature contributes to the sophisticated and uncluttered feel, reserving heavier weights for emphasis. · `--font-founders-grotesk`
- **Substitute:** Inter
- **Weights:** 300, 500
- **Sizes:** 13px, 15px, 16px, 18px, 20px, 32px
- **Line height:** 1.10, 1.15, 1.20, 1.25, 1.35, 1.45
- **Letter spacing:** 0.0100em at 13px, 0.0200em at 32px
- **Role:** Primary typeface for most interface text, headings, and body copy. Its varying lightweight nature contributes to the sophisticated and uncluttered feel, reserving heavier weights for emphasis.

### Founders Grotesk Mono — Used for specific functional text like buttons, navigation links, and badges. The monospaced character provides a utilitarian, almost code-like counterpoint to the primary sans-serif, giving precise visual weight to interactive elements. · `--font-founders-grotesk-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 13px, 14px, 16px, 28px
- **Line height:** 0.92, 1.00, 1.10, 1.15
- **Letter spacing:** -0.0200em at 28px, 0.0300em at 12px
- **Role:** Used for specific functional text like buttons, navigation links, and badges. The monospaced character provides a utilitarian, almost code-like counterpoint to the primary sans-serif, giving precise visual weight to interactive elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 0.92 | 0.36px | `--text-caption` |
| body | 14px | 1.1 | 0.42px | `--text-body` |
| heading-sm | 18px | 1.15 | — | `--text-heading-sm` |
| heading | 20px | 1.2 | — | `--text-heading` |
| display | 32px | 1.1 | 0.64px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 73px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Text Link Button
**Role:** Ghost actions or secondary navigation links

Transparent background, Charcoal Noir text (#030303), 0px border radius, 10px vertical padding, 0px horizontal padding. Underlined on hover by default.

### Filled Action Button
**Role:** Primary call-to-action button

Charcoal Noir background (#030303), Canvas White text (#ffffff), 0px border radius, 12px vertical padding, 63px horizontal padding. Uses Founders Grotesk Mono at 16px with 0.0300em letter spacing.

### Underlined Text Input
**Role:** Form input fields

Transparent background, Charcoal Noir text (#030303) and 1px bottom border (#030303), 0px border radius, 10px top padding, 12px bottom padding, 0px horizontal padding. Placeholder text uses a lighter gray.

### Hero Text Overlay
**Role:** Display of key information over full-bleed imagery

Text in Canvas White (#ffffff) or Charcoal Noir (#030303) on transparent dark/light image backgrounds, utilizing Founders Grotesk weights between 300 and 500. Buttons are often Ghost Text Link style with Canvas White text.

### Product Highlight Badge
**Role:** Product descriptive tags or attributes

Transparent background, Charcoal Noir text (#030303), 0px border radius. Uses Founders Grotesk Mono at 12px with 0.0300em letter spacing. Features generous vertical padding (20px) and no horizontal padding.

### Simple Card
**Role:** General content container without visual hierarchy

Transparent background, no border, no shadow, 0px border radius, and 0px padding. It functions primarily as a content grouping container, relying on outer spacing for separation.

### Subtle Highlight Card
**Role:** Interactive or subtly distinct content container

Soft Ivory background (rgba(246, 234, 218, 0.2)), no border, no shadow, 0px border radius, 12px padding on all sides. Used for elements like interactive loyalty program information.

## Do's and Don'ts

### Do
- Prioritize Founders Grotesk 300 for aesthetic elegance in headlines; avoid heavy weights to maintain refined tone.
- Use Charcoal Noir (#030303) for all primary text and critical interactive elements.
- Maintain 0px border-radius across all components to preserve the stark, architectural feel.
- Separate content blocks and elements primarily through generous vertical spacing, using values from the 12px, 20px, 32px, and 73px scale.
- Employ Founders Grotesk Mono specifically for interactive elements like buttons and navigational links to add a technical, precise counterpoint.
- Ensure all backgrounds like Canvas White (#ffffff) and Soft Ivory (#f6eada) offer AAA contrast ratios with Charcoal Noir (#030303) text.
- Use transparent backgrounds and thin borders with Charcoal Noir (#030303) for ghost buttons or input fields.

### Don't
- Avoid chromatic colors; maintain the strictly monochrome palette with subtle neutral variations.
- Do not use box shadows or other elevation effects; the design relies on flat surfaces and clean lines.
- Do not introduce rounded corners; all elements should have sharp, unyielding edges.
- Avoid dense, packed layouts; allow ample whitespace between elements and sections.
- Limit the use of bold typefaces; the aesthetic favors light and regular weights.
- Do not use generic system fonts; Founders Grotesk and Founders Grotesk Mono are central to the brand identity.
- Do not use color to indicate interactive states; rely on text color changes, underlines, or background transparency shifts.

## Imagery

Imagery on Abel is high-impact product photography, typically full-bleed or large formats. Photography is characterized by a slightly desaturated, sometimes warm or green-tinted, filter, giving a moody yet natural feel. Products are often featured directly (perfume bottles) or in evocative, conceptual contexts (people holding bananas). There are no illustrations or distinct icons visible in the screenshots, relying purely on photography and minimal UI elements. Imagery acts as the primary visual storytelling device, with UI elements providing a quiet textual overlay.

## Layout

The page structure is full-bleed, often featuring large, immersive hero sections that span the entire viewport width. Content is generally center-aligned within an implicit column structure, allowing imagery to dominate the background. Sections alternate between full-bleed photographic elements and more text-focused blocks on a white or light-off-white background. Vertical rhythm is established through significant section gaps and consistent padding. Navigation is minimal, consisting of a fixed top bar with a 'Menu' and 'Cart' link, and a prominent brand logo centered within the header.

## Agent Prompt Guide

Quick Color Reference:
text: #030303
background: #ffffff
border: #030303
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Charcoal Noir background on an evocative product image. Headline 'INTRODUCING, MIAMI SPLIT' in Canvas White (#ffffff), Founders Grotesk 500, 32px, with letter-spacing 0.0200em. Subtext 'An edgy white oud. A fragrance that shouldn't work - yet absolutely does' in Canvas White (#ffffff), Founders Grotesk 300, 18px. Ghost button 'DISCOVER MIAMI SPLIT' with Canvas White (#ffffff) text using Founders Grotesk Mono 400, 16px, 0px radius, 10px vertical, 0px horizontal padding.

Create a product card: Canvas White (#ffffff) background. Product name 'THE APARTMENT' in Charcoal Noir (#030303), Founders Grotesk 500, 20px. Subtext '100% NATURAL EAU DE PARFUM 50ML / 1.69FL. OZ' in Charcoal Noir (#030303), Founders Grotesk 300, 13px. Apply 0px padding and 0px radius to the card itself.

No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.

## Similar Brands

- **Aesop** — Shares a monochrome palette, minimalist UI, and emphasis on product photography against clean backgrounds.
- **Byredo** — Similar high-end aesthetic with restrained typography, desaturated imagery, and a focus on essential elements rather than ornamentation.
- **RIMOWA** — Exhibits a refined, functional aesthetic with strong photographic presence, minimal colors, and sharp, clean lines.
- **ARKET** — Uses a clean, high-contrast visual language with a focus on product and content, avoiding excessive UI elements or bright colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-soft-ivory: #f6eada;
  --color-charcoal-noir: #030303;
  --color-canvas-white: #ffffff;
  --color-concrete-gray: #cccccc;
  --color-stone-whisper: #dad9d5;
  --color-ash-cloud: #807e81;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-founders-grotesk-mono: 'Founders Grotesk Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 0.92;
  --tracking-caption: 0.36px;
  --text-body: 14px;
  --leading-body: 1.1;
  --tracking-body: 0.42px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.15;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-display: 32px;
  --leading-display: 1.1;
  --tracking-display: 0.64px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 73px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-soft-ivory: #f6eada;
  --color-charcoal-noir: #030303;
  --color-canvas-white: #ffffff;
  --color-concrete-gray: #cccccc;
  --color-stone-whisper: #dad9d5;
  --color-ash-cloud: #807e81;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-founders-grotesk-mono: 'Founders Grotesk Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 0.92;
  --tracking-caption: 0.36px;
  --text-body: 14px;
  --leading-body: 1.1;
  --tracking-body: 0.42px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.15;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-display: 32px;
  --leading-display: 1.1;
  --tracking-display: 0.64px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
}
```
